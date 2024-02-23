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

Total: 242

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Latitude E6420              | Notebook    | [f4dcc8c239](https://linux-hardware.org/?probe=f4dcc8c239) | Jan 26, 2024 |
| Acer          | Aspire A317-53              | Notebook    | [efa0303d01](https://linux-hardware.org/?probe=efa0303d01) | Jan 24, 2024 |
| Dell          | Inspiron 3482               | Notebook    | [bbcb062420](https://linux-hardware.org/?probe=bbcb062420) | Dec 29, 2023 |
| Lenovo        | IdeaPad 300-17ISK 80QH      | Notebook    | [0c55b9f3e3](https://linux-hardware.org/?probe=0c55b9f3e3) | Dec 28, 2023 |
| Lenovo        | IdeaPad 300-17ISK 80QH      | Notebook    | [9197fe40a7](https://linux-hardware.org/?probe=9197fe40a7) | Dec 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [e36502092e](https://linux-hardware.org/?probe=e36502092e) | Dec 27, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [b000376310](https://linux-hardware.org/?probe=b000376310) | Dec 26, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [ff3773b480](https://linux-hardware.org/?probe=ff3773b480) | Dec 26, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [1265cfb294](https://linux-hardware.org/?probe=1265cfb294) | Dec 21, 2023 |
| ASUSTek       | P5G41-M                     | Desktop     | [cbab9e248d](https://linux-hardware.org/?probe=cbab9e248d) | Dec 20, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [6067c56124](https://linux-hardware.org/?probe=6067c56124) | Dec 19, 2023 |
| Intel         | Unknown                     | Desktop     | [3ae9554945](https://linux-hardware.org/?probe=3ae9554945) | Dec 05, 2023 |
| Dell          | 0PRR48 A01                  | Desktop     | [0942eb512e](https://linux-hardware.org/?probe=0942eb512e) | Nov 30, 2023 |
| HP            | EliteBook 640 14 inch G9... | Notebook    | [51b0a49d02](https://linux-hardware.org/?probe=51b0a49d02) | Nov 27, 2023 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [99719fb0f6](https://linux-hardware.org/?probe=99719fb0f6) | Nov 27, 2023 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [eec1358334](https://linux-hardware.org/?probe=eec1358334) | Nov 27, 2023 |
| Dell          | System XPS L502X            | Notebook    | [33f54ee5dc](https://linux-hardware.org/?probe=33f54ee5dc) | Nov 16, 2023 |
| HP            | ZBook 17 G5                 | Notebook    | [4377844e75](https://linux-hardware.org/?probe=4377844e75) | Nov 02, 2023 |
| Lenovo        | ZIWB2                       | Notebook    | [9e6bd45db9](https://linux-hardware.org/?probe=9e6bd45db9) | Oct 29, 2023 |
| Lenovo        | ZIWB2                       | Notebook    | [2537a6e7b9](https://linux-hardware.org/?probe=2537a6e7b9) | Oct 26, 2023 |
| Gigabyte      | H270-HD3P-CF                | Desktop     | [43fedd61b1](https://linux-hardware.org/?probe=43fedd61b1) | Oct 23, 2023 |
| Gigabyte      | H270-HD3P-CF                | Desktop     | [22baba8799](https://linux-hardware.org/?probe=22baba8799) | Oct 23, 2023 |
| Lenovo        | ThinkPad T480 20L50101US    | Notebook    | [c6913c1b75](https://linux-hardware.org/?probe=c6913c1b75) | Oct 16, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [188b107eb5](https://linux-hardware.org/?probe=188b107eb5) | Oct 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [7e1caa679f](https://linux-hardware.org/?probe=7e1caa679f) | Sep 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [5a57428971](https://linux-hardware.org/?probe=5a57428971) | Sep 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [bab5438645](https://linux-hardware.org/?probe=bab5438645) | Sep 22, 2023 |
| HP            | 829A                        | Mini pc     | [52aac4ac46](https://linux-hardware.org/?probe=52aac4ac46) | Sep 16, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [794f6d999a](https://linux-hardware.org/?probe=794f6d999a) | Sep 12, 2023 |
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
| Ubuntu Studio 20.04 | 84        | 41.18%  |
| Ubuntu Studio 22.04 | 63        | 30.88%  |
| Ubuntu Studio 23.04 | 13        | 6.37%   |
| Ubuntu Studio 20.10 | 13        | 6.37%   |
| Ubuntu Studio 22.10 | 9         | 4.41%   |
| Ubuntu Studio 21.10 | 7         | 3.43%   |
| Ubuntu Studio 21.04 | 5         | 2.45%   |
| Ubuntu Studio 23.10 | 4         | 1.96%   |
| Ubuntu Studio 18.04 | 3         | 1.47%   |
| Ubuntu Studio 19.10 | 2         | 0.98%   |
| Ubuntu Studio 16.04 | 1         | 0.49%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu Studio | 202       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 6.2.0-1009-lowlatency  | 6         | 2.87%   |
| 5.15.0-56-lowlatency   | 5         | 2.39%   |
| 5.15.0-46-lowlatency   | 5         | 2.39%   |
| 5.13.0-28-lowlatency   | 5         | 2.39%   |
| 6.2.0-1003-lowlatency  | 4         | 1.91%   |
| 5.4.0-52-lowlatency    | 4         | 1.91%   |
| 5.4.0-42-lowlatency    | 4         | 1.91%   |
| 6.2.0-1012-lowlatency  | 3         | 1.44%   |
| 5.8.0-55-lowlatency    | 3         | 1.44%   |
| 5.8.0-50-lowlatency    | 3         | 1.44%   |
| 5.8.0-44-lowlatency    | 3         | 1.44%   |
| 5.8.0-25-lowlatency    | 3         | 1.44%   |
| 5.4.0-65-lowlatency    | 3         | 1.44%   |
| 5.4.0-26-lowlatency    | 3         | 1.44%   |
| 5.15.0-67-lowlatency   | 3         | 1.44%   |
| 5.15.0-58-lowlatency   | 3         | 1.44%   |
| 5.15.0-52-lowlatency   | 3         | 1.44%   |
| 5.15.0-50-lowlatency   | 3         | 1.44%   |
| 5.15.0-48-lowlatency   | 3         | 1.44%   |
| 5.15.0-47-lowlatency   | 3         | 1.44%   |
| 5.11.0-44-lowlatency   | 3         | 1.44%   |
| 5.11.0-34-lowlatency   | 3         | 1.44%   |
| 6.5.0-13-lowlatency    | 2         | 0.96%   |
| 6.2.0-1018-lowlatency  | 2         | 0.96%   |
| 6.2.0-1014-lowlatency  | 2         | 0.96%   |
| 5.8.0-48-lowlatency    | 2         | 0.96%   |
| 5.8.0-29-lowlatency    | 2         | 0.96%   |
| 5.4.0-94-lowlatency    | 2         | 0.96%   |
| 5.4.0-58-lowlatency    | 2         | 0.96%   |
| 5.4.0-56-lowlatency    | 2         | 0.96%   |
| 5.4.0-45-lowlatency    | 2         | 0.96%   |
| 5.19.0-1021-lowlatency | 2         | 0.96%   |
| 5.19.0-1017-lowlatency | 2         | 0.96%   |
| 5.19.0-1015-lowlatency | 2         | 0.96%   |
| 5.19.0-1007-lowlatency | 2         | 0.96%   |
| 5.15.0-89-lowlatency   | 2         | 0.96%   |
| 5.15.0-79-lowlatency   | 2         | 0.96%   |
| 5.15.0-76-lowlatency   | 2         | 0.96%   |
| 5.15.0-71-lowlatency   | 2         | 0.96%   |
| 5.15.0-69-lowlatency   | 2         | 0.96%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 53        | 25.98%  |
| 5.15.0  | 52        | 25.49%  |
| 5.8.0   | 23        | 11.27%  |
| 6.2.0   | 22        | 10.78%  |
| 5.11.0  | 15        | 7.35%   |
| 5.19.0  | 13        | 6.37%   |
| 5.13.0  | 10        | 4.9%    |
| 6.5.0   | 6         | 2.94%   |
| 4.15.0  | 3         | 1.47%   |
| 5.3.0   | 2         | 0.98%   |
| 6.2.8   | 1         | 0.49%   |
| 5.7.6   | 1         | 0.49%   |
| 5.17.1  | 1         | 0.49%   |
| 5.15.6  | 1         | 0.49%   |
| 4.4.0   | 1         | 0.49%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 53        | 25.98%  |
| 5.15    | 53        | 25.98%  |
| 6.2     | 23        | 11.27%  |
| 5.8     | 23        | 11.27%  |
| 5.11    | 15        | 7.35%   |
| 5.19    | 13        | 6.37%   |
| 5.13    | 10        | 4.9%    |
| 6.5     | 6         | 2.94%   |
| 4.15    | 3         | 1.47%   |
| 5.3     | 2         | 0.98%   |
| 5.7     | 1         | 0.49%   |
| 5.17    | 1         | 0.49%   |
| 4.4     | 1         | 0.49%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 200       | 99.01%  |
| i686    | 1         | 0.5%    |
| aarch64 | 1         | 0.5%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KDE5            | 103       | 50.74%  |
| XFCE            | 81        | 39.9%   |
| GNOME           | 11        | 5.42%   |
| LXQt            | 3         | 1.48%   |
| MATE            | 2         | 0.99%   |
| KDE             | 1         | 0.49%   |
| GNOME Flashback | 1         | 0.49%   |
| Cinnamon        | 1         | 0.49%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 190       | 93.6%   |
| Wayland | 9         | 4.43%   |
| Tty     | 4         | 1.97%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 95        | 47.03%  |
| TDM     | 49        | 24.26%  |
| LightDM | 45        | 22.28%  |
| GDM     | 11        | 5.45%   |
| LXDM    | 1         | 0.5%    |
| GDM3    | 1         | 0.5%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 79        | 38.92%  |
| fr_FR      | 25        | 12.32%  |
| de_DE      | 14        | 6.9%    |
| en_GB      | 11        | 5.42%   |
| C          | 9         | 4.43%   |
| it_IT      | 8         | 3.94%   |
| ru_RU      | 7         | 3.45%   |
| pt_BR      | 6         | 2.96%   |
| en_CA      | 5         | 2.46%   |
| es_ES      | 4         | 1.97%   |
| en_AU      | 3         | 1.48%   |
| nl_NL      | 2         | 0.99%   |
| hu_HU      | 2         | 0.99%   |
| es_MX      | 2         | 0.99%   |
| es_AR      | 2         | 0.99%   |
| en_IE      | 2         | 0.99%   |
| en_AG      | 2         | 0.99%   |
| Unknown    | 2         | 0.99%   |
| sv_SE      | 1         | 0.49%   |
| sk_SK      | 1         | 0.49%   |
| nl_BE      | 1         | 0.49%   |
| nb_NO      | 1         | 0.49%   |
| fr_FR.UTF8 | 1         | 0.49%   |
| fr_CH      | 1         | 0.49%   |
| fr_BE      | 1         | 0.49%   |
| es_NI      | 1         | 0.49%   |
| es_GT      | 1         | 0.49%   |
| es_CR      | 1         | 0.49%   |
| en_NG      | 1         | 0.49%   |
| en_IL      | 1         | 0.49%   |
| en_DE      | 1         | 0.49%   |
| de_CH      | 1         | 0.49%   |
| de_AT      | 1         | 0.49%   |
| ca_ES      | 1         | 0.49%   |
| ca_AD      | 1         | 0.49%   |
| bg_BG      | 1         | 0.49%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 120       | 59.41%  |
| BIOS | 82        | 40.59%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 193       | 95.54%  |
| Overlay | 7         | 3.47%   |
| Xfs     | 1         | 0.5%    |
| Ext2    | 1         | 0.5%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 133       | 65.84%  |
| MBR  | 69        | 34.16%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 165       | 80.88%  |
| Yes       | 39        | 19.12%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 112       | 55.17%  |
| Yes       | 91        | 44.83%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| ASUSTek Computer                     | 36        | 17.82%  |
| Dell                                 | 30        | 14.85%  |
| Lenovo                               | 29        | 14.36%  |
| Hewlett-Packard                      | 27        | 13.37%  |
| Gigabyte Technology                  | 16        | 7.92%   |
| Apple                                | 8         | 3.96%   |
| Acer                                 | 8         | 3.96%   |
| Toshiba                              | 4         | 1.98%   |
| MSI                                  | 4         | 1.98%   |
| Intel                                | 4         | 1.98%   |
| Fujitsu                              | 4         | 1.98%   |
| ASRock                               | 3         | 1.49%   |
| HUAWEI                               | 2         | 0.99%   |
| AZW                                  | 2         | 0.99%   |
| win element                          | 1         | 0.5%    |
| System76                             | 1         | 0.5%    |
| Sony                                 | 1         | 0.5%    |
| Shenzhen Meigao Electronic Equipment | 1         | 0.5%    |
| Samsung Electronics                  | 1         | 0.5%    |
| Razer                                | 1         | 0.5%    |
| Raspberry Pi Foundation              | 1         | 0.5%    |
| Pegatron                             | 1         | 0.5%    |
| Packard Bell                         | 1         | 0.5%    |
| Microsoft                            | 1         | 0.5%    |
| Medion                               | 1         | 0.5%    |
| Intel Client Systems                 | 1         | 0.5%    |
| IBM                                  | 1         | 0.5%    |
| GPU Company                          | 1         | 0.5%    |
| Google                               | 1         | 0.5%    |
| Getac                                | 1         | 0.5%    |
| Foxconn                              | 1         | 0.5%    |
| ECS                                  | 1         | 0.5%    |
| DEPO Computers                       | 1         | 0.5%    |
| COM1                                 | 1         | 0.5%    |
| Clevo                                | 1         | 0.5%    |
| Avell High Performance               | 1         | 0.5%    |
| ATOPNUC                              | 1         | 0.5%    |
| Acidanthera                          | 1         | 0.5%    |
| Unknown                              | 1         | 0.5%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| ASUS All Series                            | 4         | 1.98%   |
| Lenovo G50-45 80E3                         | 2         | 0.99%   |
| HP Pavilion dv6                            | 2         | 0.99%   |
| Dell OptiPlex 790                          | 2         | 0.99%   |
| ASUS TUF Gaming X570-PLUS                  | 2         | 0.99%   |
| ASUS PRIME X570-PRO                        | 2         | 0.99%   |
| ASUS M4A785-M                              | 2         | 0.99%   |
| Apple iMac18,3                             | 2         | 0.99%   |
| Unknown                                    | 2         | 0.99%   |
| win element MoreFine S500+                 | 1         | 0.5%    |
| Toshiba Satellite L755D                    | 1         | 0.5%    |
| Toshiba Satellite L505                     | 1         | 0.5%    |
| Toshiba Satellite C855                     | 1         | 0.5%    |
| Toshiba Satellite A505                     | 1         | 0.5%    |
| System76 Thelio                            | 1         | 0.5%    |
| Sony VGN-NS31M_W                           | 1         | 0.5%    |
| Shenzhen Meigao Electronic Equipment HX90G | 1         | 0.5%    |
| Samsung 305V4A/305V5A                      | 1         | 0.5%    |
| Razer Blade Stealth 13 Late 2019           | 1         | 0.5%    |
| RPi Raspberry Pi 4 Model B Rev 1.4         | 1         | 0.5%    |
| Pegatron FL368AA-UUZ SR5612CH              | 1         | 0.5%    |
| Packard Bell IMEDIA S3220                  | 1         | 0.5%    |
| MSI MS-7E02                                | 1         | 0.5%    |
| MSI MS-7C95                                | 1         | 0.5%    |
| MSI MS-7A57                                | 1         | 0.5%    |
| MSI MS-7752                                | 1         | 0.5%    |
| Microsoft Surface Laptop 3                 | 1         | 0.5%    |
| Medion MD34207/C746                        | 1         | 0.5%    |
| Lenovo ZIWB2                               | 1         | 0.5%    |
| Lenovo ThinkPad X250 20CL001LMB            | 1         | 0.5%    |
| Lenovo ThinkPad X230 2333A86               | 1         | 0.5%    |
| Lenovo ThinkPad X230 2325AJG               | 1         | 0.5%    |
| Lenovo ThinkPad X230 23245S1               | 1         | 0.5%    |
| Lenovo ThinkPad X1 Yoga Gen 7 21CDCTO1WW   | 1         | 0.5%    |
| Lenovo ThinkPad X1 Carbon 6th 20KHCTO1WW   | 1         | 0.5%    |
| Lenovo ThinkPad X1 Carbon 2nd 20A80035US   | 1         | 0.5%    |
| Lenovo ThinkPad W530 2447IG0               | 1         | 0.5%    |
| Lenovo ThinkPad T530 24296HG               | 1         | 0.5%    |
| Lenovo ThinkPad T520 4243K86               | 1         | 0.5%    |
| Lenovo ThinkPad T480 20L50101US            | 1         | 0.5%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo ThinkPad                            | 14        | 6.93%   |
| Dell OptiPlex                              | 9         | 4.46%   |
| Dell Inspiron                              | 9         | 4.46%   |
| HP Compaq                                  | 8         | 3.96%   |
| Lenovo IdeaPad                             | 6         | 2.97%   |
| Dell Latitude                              | 6         | 2.97%   |
| Acer Aspire                                | 6         | 2.97%   |
| HP EliteBook                               | 5         | 2.48%   |
| ASUS ROG                                   | 5         | 2.48%   |
| Toshiba Satellite                          | 4         | 1.98%   |
| Dell Precision                             | 4         | 1.98%   |
| ASUS All                                   | 4         | 1.98%   |
| HP Pavilion                                | 3         | 1.49%   |
| Fujitsu ESPRIMO                            | 3         | 1.49%   |
| ASUS TUF                                   | 3         | 1.49%   |
| Lenovo Legion                              | 2         | 0.99%   |
| Lenovo G50-45                              | 2         | 0.99%   |
| HP ZBook                                   | 2         | 0.99%   |
| ASUS VivoBook                              | 2         | 0.99%   |
| ASUS PRIME                                 | 2         | 0.99%   |
| ASUS P8P67                                 | 2         | 0.99%   |
| ASUS M4A785-M                              | 2         | 0.99%   |
| ASUS ASUS                                  | 2         | 0.99%   |
| Apple iMac18                               | 2         | 0.99%   |
| Unknown                                    | 2         | 0.99%   |
| win element MoreFine                       | 1         | 0.5%    |
| System76 Thelio                            | 1         | 0.5%    |
| Sony VGN-NS31M                             | 1         | 0.5%    |
| Shenzhen Meigao Electronic Equipment HX90G | 1         | 0.5%    |
| Samsung 305V4A                             | 1         | 0.5%    |
| Razer Blade                                | 1         | 0.5%    |
| RPi Raspberry                              | 1         | 0.5%    |
| Pegatron FL368AA-UUZ                       | 1         | 0.5%    |
| Packard Bell IMEDIA                        | 1         | 0.5%    |
| MSI MS-7E02                                | 1         | 0.5%    |
| MSI MS-7C95                                | 1         | 0.5%    |
| MSI MS-7A57                                | 1         | 0.5%    |
| MSI MS-7752                                | 1         | 0.5%    |
| Microsoft Surface                          | 1         | 0.5%    |
| Medion MD34207                             | 1         | 0.5%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 23        | 11.39%  |
| 2019 | 17        | 8.42%   |
| 2018 | 15        | 7.43%   |
| 2011 | 15        | 7.43%   |
| 2016 | 14        | 6.93%   |
| 2012 | 14        | 6.93%   |
| 2021 | 13        | 6.44%   |
| 2014 | 13        | 6.44%   |
| 2013 | 13        | 6.44%   |
| 2009 | 11        | 5.45%   |
| 2017 | 10        | 4.95%   |
| 2015 | 10        | 4.95%   |
| 2008 | 10        | 4.95%   |
| 2022 | 8         | 3.96%   |
| 2010 | 8         | 3.96%   |
| 2007 | 4         | 1.98%   |
| 2005 | 3         | 1.49%   |
| 2023 | 1         | 0.5%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 94        | 46.53%  |
| Desktop        | 90        | 44.55%  |
| All in one     | 7         | 3.47%   |
| Mini pc        | 6         | 2.97%   |
| Convertible    | 3         | 1.49%   |
| System on chip | 1         | 0.5%    |
| Tablet         | 1         | 0.5%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 190       | 94.06%  |
| Enabled  | 12        | 5.94%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 200       | 99.01%  |
| Yes  | 2         | 0.99%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 58        | 28.57%  |
| 16.01-24.0  | 41        | 20.2%   |
| 8.01-16.0   | 40        | 19.7%   |
| 32.01-64.0  | 25        | 12.32%  |
| 3.01-4.0    | 18        | 8.87%   |
| 64.01-256.0 | 10        | 4.93%   |
| 24.01-32.0  | 4         | 1.97%   |
| 1.01-2.0    | 4         | 1.97%   |
| 2.01-3.0    | 3         | 1.48%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 61        | 29.61%  |
| 2.01-3.0   | 53        | 25.73%  |
| 4.01-8.0   | 38        | 18.45%  |
| 3.01-4.0   | 35        | 16.99%  |
| 8.01-16.0  | 14        | 6.8%    |
| 0.51-1.0   | 4         | 1.94%   |
| 24.01-32.0 | 1         | 0.49%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 111       | 54.68%  |
| 2      | 66        | 32.51%  |
| 3      | 10        | 4.93%   |
| 4      | 5         | 2.46%   |
| 7      | 3         | 1.48%   |
| 5      | 3         | 1.48%   |
| 0      | 2         | 0.99%   |
| 16     | 1         | 0.49%   |
| 11     | 1         | 0.49%   |
| 10     | 1         | 0.49%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 115       | 56.65%  |
| Yes       | 88        | 43.35%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 182       | 89.66%  |
| No        | 21        | 10.34%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 150       | 74.26%  |
| No        | 52        | 25.74%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 115       | 56.93%  |
| No        | 87        | 43.07%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Computers | Percent |
|------------------------|-----------|---------|
| USA                    | 50        | 24.75%  |
| France                 | 25        | 12.38%  |
| Germany                | 22        | 10.89%  |
| Italy                  | 12        | 5.94%   |
| Russia                 | 8         | 3.96%   |
| Brazil                 | 8         | 3.96%   |
| Spain                  | 7         | 3.47%   |
| UK                     | 6         | 2.97%   |
| Canada                 | 6         | 2.97%   |
| Belgium                | 5         | 2.48%   |
| Austria                | 5         | 2.48%   |
| Australia              | 4         | 1.98%   |
| Sweden                 | 3         | 1.49%   |
| Norway                 | 3         | 1.49%   |
| Netherlands            | 3         | 1.49%   |
| Mexico                 | 3         | 1.49%   |
| Taiwan                 | 2         | 0.99%   |
| Switzerland            | 2         | 0.99%   |
| Romania                | 2         | 0.99%   |
| Ivory Coast            | 2         | 0.99%   |
| Hungary                | 2         | 0.99%   |
| Costa Rica             | 2         | 0.99%   |
| Bulgaria               | 2         | 0.99%   |
| Argentina              | 2         | 0.99%   |
| Yemen                  | 1         | 0.5%    |
| Turkey                 | 1         | 0.5%    |
| South Africa           | 1         | 0.5%    |
| Slovakia               | 1         | 0.5%    |
| Poland                 | 1         | 0.5%    |
| Peru                   | 1         | 0.5%    |
| Nigeria                | 1         | 0.5%    |
| Nicaragua              | 1         | 0.5%    |
| Luxembourg             | 1         | 0.5%    |
| Kenya                  | 1         | 0.5%    |
| Israel                 | 1         | 0.5%    |
| Ireland                | 1         | 0.5%    |
| Indonesia              | 1         | 0.5%    |
| Guatemala              | 1         | 0.5%    |
| Finland                | 1         | 0.5%    |
| Bosnia and Herzegovina | 1         | 0.5%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Paris         | 4         | 1.96%   |
| Vienna        | 3         | 1.47%   |
| Stockholm     | 3         | 1.47%   |
| Madrid        | 3         | 1.47%   |
| Houston       | 3         | 1.47%   |
| Turin         | 2         | 0.98%   |
| Stuttgart     | 2         | 0.98%   |
| San Francisco | 2         | 0.98%   |
| Moscow        | 2         | 0.98%   |
| Montreal      | 2         | 0.98%   |
| Mississauga   | 2         | 0.98%   |
| Hamburg       | 2         | 0.98%   |
| Groningen     | 2         | 0.98%   |
| Fürth        | 2         | 0.98%   |
| Denver        | 2         | 0.98%   |
| Budapest      | 2         | 0.98%   |
| Bucharest     | 2         | 0.98%   |
| Béziers      | 2         | 0.98%   |
| Abidjan       | 2         | 0.98%   |
| Zele          | 1         | 0.49%   |
| Zanesville    | 1         | 0.49%   |
| Yonkers       | 1         | 0.49%   |
| Yekaterinburg | 1         | 0.49%   |
| Wroclaw       | 1         | 0.49%   |
| Woonsocket    | 1         | 0.49%   |
| Woodland Park | 1         | 0.49%   |
| Wildenfels    | 1         | 0.49%   |
| West Mifflin  | 1         | 0.49%   |
| Warner Robins | 1         | 0.49%   |
| Villetaneuse  | 1         | 0.49%   |
| Villefontaine | 1         | 0.49%   |
| Verviers      | 1         | 0.49%   |
| Verdal        | 1         | 0.49%   |
| Velleron      | 1         | 0.49%   |
| Toulouse      | 1         | 0.49%   |
| Toronto       | 1         | 0.49%   |
| Tilburg       | 1         | 0.49%   |
| Taylor        | 1         | 0.49%   |
| Tarragona     | 1         | 0.49%   |
| Taipei        | 1         | 0.49%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| WDC                   | 50        | 60     | 16.18%  |
| Samsung Electronics   | 50        | 63     | 16.18%  |
| Seagate               | 36        | 60     | 11.65%  |
| Toshiba               | 19        | 20     | 6.15%   |
| SanDisk               | 18        | 19     | 5.83%   |
| SK hynix              | 11        | 12     | 3.56%   |
| Hitachi               | 11        | 12     | 3.56%   |
| Kingston              | 10        | 11     | 3.24%   |
| Intel                 | 10        | 14     | 3.24%   |
| Crucial               | 9         | 9      | 2.91%   |
| Unknown               | 7         | 7      | 2.27%   |
| Phison                | 5         | 5      | 1.62%   |
| HGST                  | 5         | 6      | 1.62%   |
| PNY                   | 4         | 4      | 1.29%   |
| Micron Technology     | 4         | 4      | 1.29%   |
| Team                  | 3         | 3      | 0.97%   |
| SPCC                  | 3         | 3      | 0.97%   |
| JMicron Technology    | 3         | 3      | 0.97%   |
| Intenso               | 3         | 3      | 0.97%   |
| China                 | 3         | 3      | 0.97%   |
| ASMT                  | 3         | 3      | 0.97%   |
| Apple                 | 3         | 5      | 0.97%   |
| A-DATA Technology     | 3         | 4      | 0.97%   |
| UMIS                  | 2         | 2      | 0.65%   |
| KIOXIA                | 2         | 2      | 0.65%   |
| Fujitsu               | 2         | 2      | 0.65%   |
| Corsair               | 2         | 3      | 0.65%   |
| BHT                   | 2         | 2      | 0.65%   |
| XPG                   | 1         | 1      | 0.32%   |
| Wibtek                | 1         | 1      | 0.32%   |
| USB 3.0               | 1         | 2      | 0.32%   |
| Union Memory          | 1         | 1      | 0.32%   |
| TO Exter              | 1         | 1      | 0.32%   |
| Silicon Motion        | 1         | 1      | 0.32%   |
| SCY                   | 1         | 1      | 0.32%   |
| Reeinno               | 1         | 1      | 0.32%   |
| Realtek Semiconductor | 1         | 1      | 0.32%   |
| Realtek               | 1         | 1      | 0.32%   |
| Phison Electronics    | 1         | 1      | 0.32%   |
| Patriot               | 1         | 1      | 0.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB                    | 4         | 1.17%   |
| Seagate ST500DM002-1BD142 500GB           | 4         | 1.17%   |
| Seagate ST2000DM001-1ER164 2TB            | 4         | 1.17%   |
| Samsung SSD 870 EVO 1TB                   | 4         | 1.17%   |
| Samsung SSD 860 EVO 500GB                 | 4         | 1.17%   |
| Seagate ST2000DM008-2FR102 2TB            | 3         | 0.87%   |
| Kingston SA400S37240G 240GB SSD           | 3         | 0.87%   |
| Crucial CT500MX500SSD1 500GB              | 3         | 0.87%   |
| WDC WDS200T2B0A-00SM50 2TB SSD            | 2         | 0.58%   |
| WDC WD10EZEX-08WN4A0 1TB                  | 2         | 0.58%   |
| WDC PC SN530 SDBPNPZ-512G-1002 512GB      | 2         | 0.58%   |
| Toshiba MQ04ABF100 1TB                    | 2         | 0.58%   |
| Toshiba HDWD130 3TB                       | 2         | 0.58%   |
| Toshiba DT01ACA100 1TB                    | 2         | 0.58%   |
| Toshiba DT01ACA050 500GB                  | 2         | 0.58%   |
| Team T253X6001T 1TB SSD                   | 2         | 0.58%   |
| SPCC Solid State Disk 256GB               | 2         | 0.58%   |
| SK hynix SKHynix_HFM512GDHTNI-87A0B 512GB | 2         | 0.58%   |
| Seagate ST5000LM000-2AN170 5TB            | 2         | 0.58%   |
| Seagate Expansion Desk 8TB                | 2         | 0.58%   |
| Seagate Expansion 1TB                     | 2         | 0.58%   |
| SanDisk SSD PLUS 240GB                    | 2         | 0.58%   |
| SanDisk SDSSDA240G 240GB                  | 2         | 0.58%   |
| Samsung SSD 970 EVO Plus 500GB            | 2         | 0.58%   |
| Samsung SSD 970 EVO Plus 1TB              | 2         | 0.58%   |
| Samsung SSD 960 PRO 512GB                 | 2         | 0.58%   |
| Samsung SSD 860 EVO 1TB                   | 2         | 0.58%   |
| Samsung SSD 850 EVO 500GB                 | 2         | 0.58%   |
| Samsung MZ7TD256HAFV-000L7 256GB SSD      | 2         | 0.58%   |
| Samsung HD753LJ 752GB                     | 2         | 0.58%   |
| Phison Sabrent 2TB                        | 2         | 0.58%   |
| Kingston SA400S37480G 480GB SSD           | 2         | 0.58%   |
| Kingston SA400S37120G 120GB SSD           | 2         | 0.58%   |
| JMicron Generic 8GB                       | 2         | 0.58%   |
| Crucial CT1000MX500SSD1 1TB               | 2         | 0.58%   |
| China SSD 1TB                             | 2         | 0.58%   |
| Apple SSD SM0032L 32GB                    | 2         | 0.58%   |
| Apple HDD ST1000DM003 1TB                 | 2         | 0.58%   |
| XPG GAMMIX S7 1TB                         | 1         | 0.29%   |
| Wibtek W800S 512GB SSD                    | 1         | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 38        | 48     | 30.65%  |
| Seagate             | 35        | 58     | 28.23%  |
| Toshiba             | 18        | 19     | 14.52%  |
| Hitachi             | 11        | 12     | 8.87%   |
| Samsung Electronics | 5         | 5      | 4.03%   |
| HGST                | 5         | 6      | 4.03%   |
| JMicron Technology  | 2         | 2      | 1.61%   |
| Fujitsu             | 2         | 2      | 1.61%   |
| Apple               | 2         | 2      | 1.61%   |
| USB 3.0             | 1         | 2      | 0.81%   |
| Unknown             | 1         | 1      | 0.81%   |
| TO Exter            | 1         | 1      | 0.81%   |
| Maxtor              | 1         | 1      | 0.81%   |
| Inateck             | 1         | 1      | 0.81%   |
| ASMT                | 1         | 1      | 0.81%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 29        | 34     | 27.36%  |
| SanDisk             | 15        | 16     | 14.15%  |
| Kingston            | 9         | 10     | 8.49%   |
| Crucial             | 8         | 8      | 7.55%   |
| WDC                 | 4         | 4      | 3.77%   |
| PNY                 | 4         | 4      | 3.77%   |
| SPCC                | 3         | 3      | 2.83%   |
| Micron Technology   | 3         | 3      | 2.83%   |
| Intenso             | 3         | 3      | 2.83%   |
| China               | 3         | 3      | 2.83%   |
| Team                | 2         | 2      | 1.89%   |
| SK hynix            | 2         | 2      | 1.89%   |
| BHT                 | 2         | 2      | 1.89%   |
| ASMT                | 2         | 2      | 1.89%   |
| A-DATA Technology   | 2         | 2      | 1.89%   |
| Wibtek              | 1         | 1      | 0.94%   |
| Toshiba             | 1         | 1      | 0.94%   |
| SCY                 | 1         | 1      | 0.94%   |
| Reeinno             | 1         | 1      | 0.94%   |
| Patriot             | 1         | 1      | 0.94%   |
| OCZ                 | 1         | 1      | 0.94%   |
| NGFF                | 1         | 1      | 0.94%   |
| Lexar               | 1         | 1      | 0.94%   |
| Leven               | 1         | 1      | 0.94%   |
| KingSpec            | 1         | 1      | 0.94%   |
| Intel               | 1         | 1      | 0.94%   |
| Integral            | 1         | 1      | 0.94%   |
| EDGE eMe            | 1         | 1      | 0.94%   |
| Dogfish             | 1         | 1      | 0.94%   |
| Corsair             | 1         | 1      | 0.94%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 98        | 161    | 37.26%  |
| SSD     | 89        | 113    | 33.84%  |
| NVMe    | 65        | 85     | 24.71%  |
| MMC     | 8         | 9      | 3.04%   |
| Unknown | 3         | 3      | 1.14%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 150       | 254    | 62.24%  |
| NVMe | 65        | 84     | 26.97%  |
| SAS  | 18        | 24     | 7.47%   |
| MMC  | 8         | 9      | 3.32%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 110       | 140    | 52.63%  |
| 0.51-1.0   | 64        | 77     | 30.62%  |
| 1.01-2.0   | 17        | 20     | 8.13%   |
| 4.01-10.0  | 8         | 24     | 3.83%   |
| 3.01-4.0   | 7         | 9      | 3.35%   |
| 2.01-3.0   | 3         | 4      | 1.44%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 56        | 27.32%  |
| 251-500        | 38        | 18.54%  |
| 501-1000       | 37        | 18.05%  |
| 1001-2000      | 29        | 14.15%  |
| More than 3000 | 15        | 7.32%   |
| 51-100         | 12        | 5.85%   |
| 21-50          | 10        | 4.88%   |
| 1-20           | 6         | 2.93%   |
| 2001-3000      | 2         | 0.98%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 64        | 31.07%  |
| 21-50          | 34        | 16.5%   |
| 101-250        | 33        | 16.02%  |
| 251-500        | 21        | 10.19%  |
| 51-100         | 17        | 8.25%   |
| 501-1000       | 16        | 7.77%   |
| More than 3000 | 9         | 4.37%   |
| 1001-2000      | 8         | 3.88%   |
| 2001-3000      | 4         | 1.94%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                     | 3         | 3      | 6.98%   |
| Samsung Electronics SSD 870 EVO 1TB                 | 2         | 3      | 4.65%   |
| Samsung Electronics HD753LJ 752GB                   | 2         | 2      | 4.65%   |
| WDC WD5000LPVX-75V0TT0 500GB                        | 1         | 1      | 2.33%   |
| WDC WD5000AVDS-63U7B1 500GB                         | 1         | 1      | 2.33%   |
| WDC WD5000AAKS-00TMA0 500GB                         | 1         | 1      | 2.33%   |
| WDC WD3200BPVT-80ZEST0 320GB                        | 1         | 1      | 2.33%   |
| WDC WD3200BEKT-75PVMT1 320GB                        | 1         | 1      | 2.33%   |
| WDC WD3200BEKT-60V5T1 320GB                         | 1         | 1      | 2.33%   |
| WDC WD2500BEVT-22ZCT0 250GB                         | 1         | 1      | 2.33%   |
| WDC WD1600AAJS-08L7A0 160GB                         | 1         | 1      | 2.33%   |
| WDC WD10EZEX-22BN5A0 1TB                            | 1         | 1      | 2.33%   |
| WDC WD10EAVS-32D7B1 1TB                             | 1         | 1      | 2.33%   |
| WDC WD10EADS-00M2B0 1TB                             | 1         | 1      | 2.33%   |
| UMIS RPITJ512VME2OWD 512GB                          | 1         | 1      | 2.33%   |
| Toshiba MQ01ABF050 500GB                            | 1         | 1      | 2.33%   |
| Toshiba MK1637GSX 160GB                             | 1         | 1      | 2.33%   |
| Toshiba HDWE140 4TB                                 | 1         | 1      | 2.33%   |
| Seagate ST9500420AS 500GB                           | 1         | 1      | 2.33%   |
| Seagate ST9320320AS 320GB                           | 1         | 1      | 2.33%   |
| Seagate ST8000DM004-2CX1 8TB                        | 1         | 6      | 2.33%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 1         | 1      | 2.33%   |
| Seagate ST3320820AS 320GB                           | 1         | 1      | 2.33%   |
| Seagate ST3200822AS 200GB                           | 1         | 1      | 2.33%   |
| Seagate ST1000VM002-9ZL162 1TB                      | 1         | 1      | 2.33%   |
| Seagate ST1000LM049-2GH172 1TB                      | 1         | 1      | 2.33%   |
| Samsung Electronics SSD 960 PRO 512GB               | 1         | 1      | 2.33%   |
| Samsung Electronics HN-M500MBB 500GB                | 1         | 1      | 2.33%   |
| Samsung Electronics HM320JI 320GB                   | 1         | 1      | 2.33%   |
| Micron Technology MTFDDAV256TBN-1AR15ABHA 256GB SSD | 1         | 1      | 2.33%   |
| KingSpec P3-256 256GB SSD                           | 1         | 1      | 2.33%   |
| Intel SSDSCKKF180H6H 180GB                          | 1         | 1      | 2.33%   |
| Hitachi HTS723232A7A364 320GB                       | 1         | 1      | 2.33%   |
| Hitachi HTS545050B9A300 500GB                       | 1         | 1      | 2.33%   |
| Hitachi HDS721010CLA332 1TB                         | 1         | 1      | 2.33%   |
| Hitachi HDS5C1010CLA382 1TB                         | 1         | 1      | 2.33%   |
| HGST HTS721010A9 1TB                                | 1         | 1      | 2.33%   |
| A-DATA Technology SU650 240GB SSD                   | 1         | 1      | 2.33%   |
| A-DATA Technology SP550 240GB SSD                   | 1         | 1      | 2.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 16     | 26.19%  |
| WDC                 | 10        | 11     | 23.81%  |
| Samsung Electronics | 7         | 8      | 16.67%  |
| Hitachi             | 4         | 4      | 9.52%   |
| Toshiba             | 3         | 3      | 7.14%   |
| A-DATA Technology   | 2         | 2      | 4.76%   |
| UMIS                | 1         | 1      | 2.38%   |
| Micron Technology   | 1         | 1      | 2.38%   |
| KingSpec            | 1         | 1      | 2.38%   |
| Intel               | 1         | 1      | 2.38%   |
| HGST                | 1         | 1      | 2.38%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 16     | 33.33%  |
| WDC                 | 10        | 11     | 30.3%   |
| Samsung Electronics | 4         | 4      | 12.12%  |
| Hitachi             | 4         | 4      | 12.12%  |
| Toshiba             | 3         | 3      | 9.09%   |
| HGST                | 1         | 1      | 3.03%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 31        | 39     | 77.5%   |
| SSD  | 7         | 8      | 17.5%   |
| NVMe | 2         | 2      | 5%      |

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
| Works    | 173       | 288    | 72.38%  |
| Malfunc  | 40        | 49     | 16.74%  |
| Detected | 24        | 32     | 10.04%  |
| Failed   | 2         | 2      | 0.84%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 140       | 52.24%  |
| AMD                          | 44        | 16.42%  |
| Samsung Electronics          | 21        | 7.84%   |
| SanDisk                      | 10        | 3.73%   |
| SK hynix                     | 9         | 3.36%   |
| Phison Electronics           | 8         | 2.99%   |
| Marvell Technology Group     | 6         | 2.24%   |
| ASMedia Technology           | 5         | 1.87%   |
| Union Memory (Shenzhen)      | 3         | 1.12%   |
| Nvidia                       | 3         | 1.12%   |
| Realtek Semiconductor        | 2         | 0.75%   |
| Kingston Technology Company  | 2         | 0.75%   |
| JMicron Technology           | 2         | 0.75%   |
| VIA Technologies             | 1         | 0.37%   |
| Toshiba America Info Systems | 1         | 0.37%   |
| Silicon Motion               | 1         | 0.37%   |
| Silicon Image                | 1         | 0.37%   |
| Seagate Technology           | 1         | 0.37%   |
| Micron/Crucial Technology    | 1         | 0.37%   |
| Micron Technology            | 1         | 0.37%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.37%   |
| LSI Logic / Symbios Logic    | 1         | 0.37%   |
| KIOXIA                       | 1         | 0.37%   |
| Apple                        | 1         | 0.37%   |
| ADATA Technology             | 1         | 0.37%   |
| Adaptec                      | 1         | 0.37%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 30        | 9.65%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 13        | 4.18%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 12        | 3.86%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 10        | 3.22%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 9         | 2.89%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 9         | 2.89%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 7         | 2.25%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 7         | 2.25%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 6         | 1.93%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 6         | 1.93%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 6         | 1.93%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 1.61%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 5         | 1.61%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 5         | 1.61%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 5         | 1.61%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 5         | 1.61%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 4         | 1.29%   |
| Phison E12 NVMe Controller                                                     | 4         | 1.29%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 1.29%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4         | 1.29%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 4         | 1.29%   |
| AMD 400 Series Chipset SATA Controller                                         | 4         | 1.29%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 3         | 0.96%   |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 0.96%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 3         | 0.96%   |
| Intel SATA Controller [RAID mode]                                              | 3         | 0.96%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 3         | 0.96%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 3         | 0.96%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 3         | 0.96%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 0.96%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 3         | 0.96%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 3         | 0.96%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 3         | 0.96%   |
| AMD 500 Series Chipset SATA Controller                                         | 3         | 0.96%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 256GB                          | 2         | 0.64%   |
| SK hynix BC511 NVMe SSD                                                        | 2         | 0.64%   |
| Samsung NVMe SSD SM0032L                                                       | 2         | 0.64%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 0.64%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 2         | 0.64%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2         | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 153       | 56.88%  |
| NVMe | 66        | 24.54%  |
| IDE  | 28        | 10.41%  |
| RAID | 18        | 6.69%   |
| SAS  | 3         | 1.12%   |
| SCSI | 1         | 0.37%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 148       | 73.27%  |
| AMD    | 53        | 26.24%  |
| ARM    | 1         | 0.5%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| AMD Ryzen 5 4600H with Radeon Graphics  | 4         | 1.98%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 3         | 1.49%   |
| Intel Core i5-6500 CPU @ 3.20GHz        | 3         | 1.49%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 3         | 1.49%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 3         | 1.49%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 2         | 0.99%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 2         | 0.99%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 2         | 0.99%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 2         | 0.99%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 2         | 0.99%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 2         | 0.99%   |
| Intel Core i7-2630QM CPU @ 2.00GHz      | 2         | 0.99%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz       | 2         | 0.99%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 2         | 0.99%   |
| Intel Core i5-4590 CPU @ 3.30GHz        | 2         | 0.99%   |
| Intel Core i5-4440 CPU @ 3.10GHz        | 2         | 0.99%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 2         | 0.99%   |
| Intel Core i5-2540M CPU @ 2.60GHz       | 2         | 0.99%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 2         | 0.99%   |
| Intel Core i5-10300H CPU @ 2.50GHz      | 2         | 0.99%   |
| Intel Core i5 CPU 650 @ 3.20GHz         | 2         | 0.99%   |
| Intel Celeron N4000 CPU @ 1.10GHz       | 2         | 0.99%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 2         | 0.99%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 2         | 0.99%   |
| AMD Ryzen 9 5900HX with Radeon Graphics | 2         | 0.99%   |
| AMD Ryzen 9 3950X 16-Core Processor     | 2         | 0.99%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 2         | 0.99%   |
| AMD Ryzen 7 5825U with Radeon Graphics  | 2         | 0.99%   |
| AMD Ryzen 5 5600G with Radeon Graphics  | 2         | 0.99%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 2         | 0.99%   |
| AMD Phenom II X4 945 Processor          | 2         | 0.99%   |
| Intel Xeon W-2150B CPU @ 3.00GHz        | 1         | 0.5%    |
| Intel Xeon CPU E5420 @ 2.50GHz          | 1         | 0.5%    |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz     | 1         | 0.5%    |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz      | 1         | 0.5%    |
| Intel Processor 5Y10 CPU @ 0.80GHz      | 1         | 0.5%    |
| Intel Pentium Dual CPU T3400 @ 2.16GHz  | 1         | 0.5%    |
| Intel Pentium D CPU 3.40GHz             | 1         | 0.5%    |
| Intel Pentium CPU G3220 @ 3.00GHz       | 1         | 0.5%    |
| Intel Pentium 4 CPU 3.20GHz             | 1         | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i5          | 51        | 25.25%  |
| Intel Core i7          | 46        | 22.77%  |
| Other                  | 13        | 6.44%   |
| Intel Core i3          | 13        | 6.44%   |
| AMD Ryzen 5            | 12        | 5.94%   |
| AMD Ryzen 7            | 9         | 4.46%   |
| Intel Core 2 Duo       | 6         | 2.97%   |
| Intel Celeron          | 6         | 2.97%   |
| AMD Ryzen 9            | 6         | 2.97%   |
| Intel Xeon             | 4         | 1.98%   |
| Intel Core i9          | 4         | 1.98%   |
| AMD Phenom II X4       | 4         | 1.98%   |
| AMD E                  | 3         | 1.49%   |
| Intel Pentium 4        | 2         | 0.99%   |
| AMD Ryzen 3            | 2         | 0.99%   |
| AMD FX                 | 2         | 0.99%   |
| AMD Athlon II X2       | 2         | 0.99%   |
| AMD A4                 | 2         | 0.99%   |
| Intel Pentium Dual     | 1         | 0.5%    |
| Intel Pentium D        | 1         | 0.5%    |
| Intel Pentium          | 1         | 0.5%    |
| Intel Genuine          | 1         | 0.5%    |
| Intel Core 2 Quad      | 1         | 0.5%    |
| Intel Core 2           | 1         | 0.5%    |
| AMD Ryzen Threadripper | 1         | 0.5%    |
| AMD Ryzen 3 PRO        | 1         | 0.5%    |
| AMD E2                 | 1         | 0.5%    |
| AMD E1                 | 1         | 0.5%    |
| AMD Athlon X4          | 1         | 0.5%    |
| AMD Athlon Dual Core   | 1         | 0.5%    |
| AMD Athlon 64 X2       | 1         | 0.5%    |
| AMD A6                 | 1         | 0.5%    |
| AMD A10                | 1         | 0.5%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 82        | 40.59%  |
| 2      | 69        | 34.16%  |
| 6      | 23        | 11.39%  |
| 8      | 14        | 6.93%   |
| 10     | 4         | 1.98%   |
| 16     | 3         | 1.49%   |
| 12     | 3         | 1.49%   |
| 1      | 3         | 1.49%   |
| 32     | 1         | 0.5%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 201       | 99.5%   |
| 2      | 1         | 0.5%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 134       | 66.34%  |
| 1      | 68        | 33.66%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 201       | 99.5%   |
| 32-bit         | 1         | 0.5%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 39        | 19.12%  |
| 0x306c3    | 14        | 6.86%   |
| 0x206a7    | 14        | 6.86%   |
| 0x306a9    | 13        | 6.37%   |
| 0x906ea    | 8         | 3.92%   |
| 0x506e3    | 5         | 2.45%   |
| 0x306d4    | 5         | 2.45%   |
| 0x806ea    | 4         | 1.96%   |
| 0x806c1    | 4         | 1.96%   |
| 0x0a50000c | 4         | 1.96%   |
| 0x08701021 | 4         | 1.96%   |
| 0x08600104 | 4         | 1.96%   |
| 0xa0652    | 3         | 1.47%   |
| 0x906e9    | 3         | 1.47%   |
| 0x706e5    | 3         | 1.47%   |
| 0x406e3    | 3         | 1.47%   |
| 0x40651    | 3         | 1.47%   |
| 0x106e5    | 3         | 1.47%   |
| 0x10676    | 3         | 1.47%   |
| 0x0a50000d | 3         | 1.47%   |
| 0x08600106 | 3         | 1.47%   |
| 0x08108109 | 3         | 1.47%   |
| 0x010000c8 | 3         | 1.47%   |
| 0xf41      | 2         | 0.98%   |
| 0xa0655    | 2         | 0.98%   |
| 0x906ed    | 2         | 0.98%   |
| 0x6fd      | 2         | 0.98%   |
| 0x206d7    | 2         | 0.98%   |
| 0x106a5    | 2         | 0.98%   |
| 0x07030105 | 2         | 0.98%   |
| 0x010000b6 | 2         | 0.98%   |
| 0xf65      | 1         | 0.49%   |
| 0x906ec    | 1         | 0.49%   |
| 0x906a3    | 1         | 0.49%   |
| 0x90675    | 1         | 0.49%   |
| 0x806e9    | 1         | 0.49%   |
| 0x706a1    | 1         | 0.49%   |
| 0x6fb      | 1         | 0.49%   |
| 0x6f6      | 1         | 0.49%   |
| 0x506ca    | 1         | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 26        | 12.87%  |
| Haswell          | 19        | 9.41%   |
| SandyBridge      | 18        | 8.91%   |
| Zen 2            | 16        | 7.92%   |
| Skylake          | 16        | 7.92%   |
| IvyBridge        | 15        | 7.43%   |
| Zen 3            | 9         | 4.46%   |
| Penryn           | 7         | 3.47%   |
| Nehalem          | 6         | 2.97%   |
| K10              | 6         | 2.97%   |
| Broadwell        | 6         | 2.97%   |
| Westmere         | 5         | 2.48%   |
| TigerLake        | 5         | 2.48%   |
| CometLake        | 5         | 2.48%   |
| Zen+             | 4         | 1.98%   |
| IceLake          | 4         | 1.98%   |
| Core             | 4         | 1.98%   |
| Alderlake Hybrid | 4         | 1.98%   |
| Puma             | 3         | 1.49%   |
| Piledriver       | 3         | 1.49%   |
| NetBurst         | 3         | 1.49%   |
| Excavator        | 3         | 1.49%   |
| Unknown          | 3         | 1.49%   |
| K8 Hammer        | 2         | 0.99%   |
| Goldmont plus    | 2         | 0.99%   |
| Goldmont         | 2         | 0.99%   |
| Bobcat           | 2         | 0.99%   |
| Zen              | 1         | 0.5%    |
| Steamroller      | 1         | 0.5%    |
| Silvermont       | 1         | 0.5%    |
| K10 Llano        | 1         | 0.5%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 107       | 44.96%  |
| Nvidia | 75        | 31.51%  |
| AMD    | 56        | 23.53%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 10        | 4.12%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 8         | 3.29%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 8         | 3.29%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 7         | 2.88%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 6         | 2.47%   |
| Intel HD Graphics 530                                                       | 6         | 2.47%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 6         | 2.47%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 5         | 2.06%   |
| Intel HD Graphics 5500                                                      | 5         | 2.06%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5         | 2.06%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 5         | 2.06%   |
| Intel UHD Graphics 620                                                      | 4         | 1.65%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 4         | 1.65%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 4         | 1.65%   |
| Intel HD Graphics 630                                                       | 4         | 1.65%   |
| Intel Core Processor Integrated Graphics Controller                         | 4         | 1.65%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 4         | 1.65%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4         | 1.65%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3         | 1.23%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3         | 1.23%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3         | 1.23%   |
| Intel Iris Plus Graphics G7                                                 | 3         | 1.23%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 3         | 1.23%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 3         | 1.23%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 2         | 0.82%   |
| Nvidia GT218 [GeForce 210]                                                  | 2         | 0.82%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 2         | 0.82%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2         | 0.82%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 2         | 0.82%   |
| Nvidia GK208BM [GeForce 920M]                                               | 2         | 0.82%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2         | 0.82%   |
| Nvidia GF108M [GeForce GT 525M]                                             | 2         | 0.82%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 2         | 0.82%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 2         | 0.82%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2         | 0.82%   |
| Intel HD Graphics 500                                                       | 2         | 0.82%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 2         | 0.82%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2         | 0.82%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 2         | 0.82%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 2         | 0.82%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 75        | 37.13%  |
| 1 x AMD        | 45        | 22.28%  |
| 1 x Nvidia     | 44        | 21.78%  |
| Intel + Nvidia | 24        | 11.88%  |
| AMD + Nvidia   | 6         | 2.97%   |
| Intel + AMD    | 3         | 1.49%   |
| 2 x AMD        | 2         | 0.99%   |
| Other          | 1         | 0.5%    |
| 2 x Nvidia     | 1         | 0.5%    |
| 2 x Intel      | 1         | 0.5%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 165       | 81.28%  |
| Proprietary | 36        | 17.73%  |
| Unknown     | 2         | 0.99%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 89        | 43.84%  |
| 0.01-0.5   | 30        | 14.78%  |
| 1.01-2.0   | 27        | 13.3%   |
| 0.51-1.0   | 22        | 10.84%  |
| 3.01-4.0   | 14        | 6.9%    |
| 7.01-8.0   | 7         | 3.45%   |
| 5.01-6.0   | 6         | 2.96%   |
| 8.01-16.0  | 6         | 2.96%   |
| 2.01-3.0   | 1         | 0.49%   |
| 16.01-24.0 | 1         | 0.49%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 30        | 13.22%  |
| LG Display              | 21        | 9.25%   |
| AU Optronics            | 21        | 9.25%   |
| Goldstar                | 17        | 7.49%   |
| BOE                     | 15        | 6.61%   |
| Dell                    | 13        | 5.73%   |
| Chimei Innolux          | 13        | 5.73%   |
| Hewlett-Packard         | 12        | 5.29%   |
| Philips                 | 11        | 4.85%   |
| Acer                    | 11        | 4.85%   |
| Ancor Communications    | 8         | 3.52%   |
| Apple                   | 6         | 2.64%   |
| Lenovo                  | 4         | 1.76%   |
| Sharp                   | 3         | 1.32%   |
| BenQ                    | 3         | 1.32%   |
| ASUSTek Computer        | 3         | 1.32%   |
| AOC                     | 3         | 1.32%   |
| ONN                     | 2         | 0.88%   |
| Iiyama                  | 2         | 0.88%   |
| Hannspree               | 2         | 0.88%   |
| Fujitsu Siemens         | 2         | 0.88%   |
| Eizo                    | 2         | 0.88%   |
| Chi Mei Optoelectronics | 2         | 0.88%   |
| ViewSonic               | 1         | 0.44%   |
| VIE                     | 1         | 0.44%   |
| Unknown                 | 1         | 0.44%   |
| UGD                     | 1         | 0.44%   |
| TVT                     | 1         | 0.44%   |
| TCH                     | 1         | 0.44%   |
| Targa Visionary         | 1         | 0.44%   |
| Sony                    | 1         | 0.44%   |
| Seiki                   | 1         | 0.44%   |
| Onkyo                   | 1         | 0.44%   |
| NEC Computers           | 1         | 0.44%   |
| MSI                     | 1         | 0.44%   |
| Medion                  | 1         | 0.44%   |
| LG Philips              | 1         | 0.44%   |
| KTC                     | 1         | 0.44%   |
| HKC                     | 1         | 0.44%   |
| HannStar                | 1         | 0.44%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 2         | 0.84%   |
| ONN 100002487 ONN0101 1920x1080 517x323mm 24.0-inch                   | 2         | 0.84%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 2         | 0.84%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 0.84%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 2         | 0.84%   |
| Hannspree HF207 HSG18C5 1600x900 443x249mm 20.0-inch                  | 2         | 0.84%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 2         | 0.84%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 2         | 0.84%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch       | 2         | 0.84%   |
| BOE LCD Monitor BOE0747 1920x1080 345x195mm 15.6-inch                 | 2         | 0.84%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 340x190mm 15.3-inch        | 2         | 0.84%   |
| AU Optronics LCD Monitor AUO229E 1600x900 382x214mm 17.2-inch         | 2         | 0.84%   |
| Apple iMac APPAE11 3840x2160 597x336mm 27.0-inch                      | 2         | 0.84%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 2         | 0.84%   |
| ViewSonic VA2432-FHD VSCB639 1920x1080 527x296mm 23.8-inch            | 1         | 0.42%   |
| VIE LED MONITOR VIE2302 1920x1080 473x296mm 22.0-inch                 | 1         | 0.42%   |
| Unknown LCD Monitor SAMSUNG 5760x2160                                 | 1         | 0.42%   |
| UGD Artist 12 pro UGD1102 1920x1080 256x144mm 11.6-inch               | 1         | 0.42%   |
| TVT T910 TVT005E 1280x1024 376x301mm 19.0-inch                        | 1         | 0.42%   |
| TCH TYPE-C TCH5600 1920x1080 344x194mm 15.5-inch                      | 1         | 0.42%   |
| Targa Visionary LCD 24-1 Wide TARA240 1920x1080 521x293mm 23.5-inch   | 1         | 0.42%   |
| Sony TV *00 SNY8004 3840x2160 1218x685mm 55.0-inch                    | 1         | 0.42%   |
| Sharp LQ150P1JX51 SHP14B4 2496x1664 317x211mm 15.0-inch               | 1         | 0.42%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch               | 1         | 0.42%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.42%   |
| Seiki SE19HE01 SEK078A 1366x768 410x230mm 18.5-inch                   | 1         | 0.42%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch     | 1         | 0.42%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch     | 1         | 0.42%   |
| Samsung Electronics SyncMaster SAM059A 1920x1080 477x268mm 21.5-inch  | 1         | 0.42%   |
| Samsung Electronics SyncMaster SAM0467 1920x1200 518x324mm 24.1-inch  | 1         | 0.42%   |
| Samsung Electronics SyncMaster SAM03E0 1440x900 410x257mm 19.1-inch   | 1         | 0.42%   |
| Samsung Electronics SyncMaster SAM02F3 1680x1050 474x296mm 22.0-inch  | 1         | 0.42%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch  | 1         | 0.42%   |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x257mm 19.1-inch   | 1         | 0.42%   |
| Samsung Electronics SyncMaster SAM01AB 1280x1024 312x234mm 15.4-inch  | 1         | 0.42%   |
| Samsung Electronics SyncMaster SAM010B 1280x1024 340x270mm 17.1-inch  | 1         | 0.42%   |
| Samsung Electronics SMS27A350H SAM07CE 1920x1080 598x336mm 27.0-inch  | 1         | 0.42%   |
| Samsung Electronics SMB2330HD SAM0710 1920x1080 510x290mm 23.1-inch   | 1         | 0.42%   |
| Samsung Electronics SMB2330HD SAM070E 1920x1080 510x290mm 23.1-inch   | 1         | 0.42%   |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch    | 1         | 0.42%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 105       | 49.3%   |
| 1366x768 (WXGA)    | 31        | 14.55%  |
| 3840x2160 (4K)     | 18        | 8.45%   |
| 1280x1024 (SXGA)   | 11        | 5.16%   |
| 1680x1050 (WSXGA+) | 10        | 4.69%   |
| 1600x900 (HD+)     | 7         | 3.29%   |
| 1920x1200 (WUXGA)  | 6         | 2.82%   |
| 2560x1440 (QHD)    | 5         | 2.35%   |
| 1440x900 (WXGA+)   | 4         | 1.88%   |
| 1280x800 (WXGA)    | 3         | 1.41%   |
| 3440x1440          | 2         | 0.94%   |
| 1360x768           | 2         | 0.94%   |
| Unknown            | 2         | 0.94%   |
| 5760x2160          | 1         | 0.47%   |
| 3280x1080          | 1         | 0.47%   |
| 2880x1800          | 1         | 0.47%   |
| 2496x1664          | 1         | 0.47%   |
| 2160x1440          | 1         | 0.47%   |
| 1600x1200          | 1         | 0.47%   |
| 1400x1050          | 1         | 0.47%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 56        | 24.67%  |
| 27      | 21        | 9.25%   |
| 21      | 20        | 8.81%   |
| 23      | 19        | 8.37%   |
| 24      | 18        | 7.93%   |
| 17      | 15        | 6.61%   |
| 13      | 14        | 6.17%   |
| 14      | 10        | 4.41%   |
| 19      | 9         | 3.96%   |
| 22      | 8         | 3.52%   |
| 31      | 6         | 2.64%   |
| 18      | 6         | 2.64%   |
| 12      | 5         | 2.2%    |
| 20      | 4         | 1.76%   |
| Unknown | 3         | 1.32%   |
| 84      | 2         | 0.88%   |
| 65      | 1         | 0.44%   |
| 54      | 1         | 0.44%   |
| 52      | 1         | 0.44%   |
| 50      | 1         | 0.44%   |
| 43      | 1         | 0.44%   |
| 40      | 1         | 0.44%   |
| 34      | 1         | 0.44%   |
| 32      | 1         | 0.44%   |
| 26      | 1         | 0.44%   |
| 16      | 1         | 0.44%   |
| 11      | 1         | 0.44%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 77        | 34.84%  |
| 501-600     | 53        | 23.98%  |
| 401-500     | 41        | 18.55%  |
| 351-400     | 16        | 7.24%   |
| 201-300     | 13        | 5.88%   |
| 601-700     | 8         | 3.62%   |
| 1001-1500   | 4         | 1.81%   |
| Unknown     | 3         | 1.36%   |
| 701-800     | 2         | 0.9%    |
| 1501-2000   | 2         | 0.9%    |
| 801-900     | 1         | 0.45%   |
| 901-1000    | 1         | 0.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 157       | 76.59%  |
| 16/10   | 29        | 14.15%  |
| 5/4     | 10        | 4.88%   |
| 3/2     | 3         | 1.46%   |
| Unknown | 3         | 1.46%   |
| 4/3     | 2         | 0.98%   |
| 21/9    | 1         | 0.49%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 56        | 25.23%  |
| 201-250        | 51        | 22.97%  |
| 301-350        | 22        | 9.91%   |
| 81-90          | 19        | 8.56%   |
| 151-200        | 15        | 6.76%   |
| 141-150        | 13        | 5.86%   |
| 351-500        | 8         | 3.6%    |
| 251-300        | 7         | 3.15%   |
| 121-130        | 7         | 3.15%   |
| More than 1000 | 6         | 2.7%    |
| 71-80          | 5         | 2.25%   |
| 61-70          | 5         | 2.25%   |
| Unknown        | 3         | 1.35%   |
| 501-1000       | 2         | 0.9%    |
| 51-60          | 1         | 0.45%   |
| 131-140        | 1         | 0.45%   |
| 111-120        | 1         | 0.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 86        | 40%     |
| 121-160       | 53        | 24.65%  |
| 101-120       | 53        | 24.65%  |
| 161-240       | 16        | 7.44%   |
| Unknown       | 3         | 1.4%    |
| More than 240 | 2         | 0.93%   |
| 1-50          | 2         | 0.93%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 159       | 77.94%  |
| 2     | 42        | 20.59%  |
| 3     | 2         | 0.98%   |
| 0     | 1         | 0.49%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 111       | 35.81%  |
| Realtek Semiconductor             | 108       | 34.84%  |
| Qualcomm Atheros                  | 31        | 10%     |
| Broadcom                          | 16        | 5.16%   |
| MediaTek                          | 7         | 2.26%   |
| ASIX Electronics                  | 4         | 1.29%   |
| TP-Link                           | 3         | 0.97%   |
| Ralink                            | 3         | 0.97%   |
| Nvidia                            | 3         | 0.97%   |
| Broadcom Limited                  | 3         | 0.97%   |
| Ralink Technology                 | 2         | 0.65%   |
| Ericsson Business Mobile Networks | 2         | 0.65%   |
| DisplayLink                       | 2         | 0.65%   |
| Aquantia                          | 2         | 0.65%   |
| ZyDAS                             | 1         | 0.32%   |
| Wacom                             | 1         | 0.32%   |
| Qualcomm Atheros Communications   | 1         | 0.32%   |
| NetGear                           | 1         | 0.32%   |
| Motorola PCS                      | 1         | 0.32%   |
| Microsoft                         | 1         | 0.32%   |
| Marvell Technology Group          | 1         | 0.32%   |
| InterBiometrics                   | 1         | 0.32%   |
| Input Club                        | 1         | 0.32%   |
| ICS Advent                        | 1         | 0.32%   |
| Huawei Technologies               | 1         | 0.32%   |
| Hewlett-Packard                   | 1         | 0.32%   |
| Dell                              | 1         | 0.32%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 76        | 20.88%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 18        | 4.95%   |
| Intel Wireless 7265                                                           | 10        | 2.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 8         | 2.2%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 8         | 2.2%    |
| Intel Cannon Lake PCH CNVi WiFi                                               | 7         | 1.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 6         | 1.65%   |
| Intel Wireless 8265 / 8275                                                    | 6         | 1.65%   |
| Intel I211 Gigabit Network Connection                                         | 6         | 1.65%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 6         | 1.65%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 5         | 1.37%   |
| Intel Wireless 8260                                                           | 5         | 1.37%   |
| Intel Wi-Fi 6 AX201                                                           | 5         | 1.37%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                       | 5         | 1.37%   |
| Intel Ethernet Connection I217-LM                                             | 5         | 1.37%   |
| Realtek 802.11ac NIC                                                          | 4         | 1.1%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 4         | 1.1%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                       | 4         | 1.1%    |
| Intel Wi-Fi 6 AX200                                                           | 4         | 1.1%    |
| Intel Ethernet Connection (2) I219-V                                          | 4         | 1.1%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 3         | 0.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 3         | 0.82%   |
| Intel Wireless 7260                                                           | 3         | 0.82%   |
| Intel WiFi Link 5100                                                          | 3         | 0.82%   |
| Intel Ethernet Controller I225-V                                              | 3         | 0.82%   |
| Intel Centrino Ultimate-N 6300                                                | 3         | 0.82%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                   | 3         | 0.82%   |
| Broadcom BCM4331 802.11a/b/g/n                                                | 3         | 0.82%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 3         | 0.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 2         | 0.55%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 2         | 0.55%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 2         | 0.55%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2         | 0.55%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 2         | 0.55%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 2         | 0.55%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 2         | 0.55%   |
| Nvidia MCP77 Ethernet                                                         | 2         | 0.55%   |
| Intel Wireless 3160                                                           | 2         | 0.55%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                               | 2         | 0.55%   |
| Intel Ethernet Connection I219-V                                              | 2         | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 75        | 49.02%  |
| Realtek Semiconductor           | 24        | 15.69%  |
| Qualcomm Atheros                | 24        | 15.69%  |
| Broadcom                        | 10        | 6.54%   |
| MediaTek                        | 6         | 3.92%   |
| TP-Link                         | 3         | 1.96%   |
| Ralink                          | 3         | 1.96%   |
| Ralink Technology               | 2         | 1.31%   |
| ZyDAS                           | 1         | 0.65%   |
| Wacom                           | 1         | 0.65%   |
| Qualcomm Atheros Communications | 1         | 0.65%   |
| NetGear                         | 1         | 0.65%   |
| Microsoft                       | 1         | 0.65%   |
| Broadcom Limited                | 1         | 0.65%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                                           | 10        | 6.49%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 7         | 4.55%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 6         | 3.9%    |
| Intel Wireless 8265 / 8275                                                    | 6         | 3.9%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 6         | 3.9%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 5         | 3.25%   |
| Intel Wireless 8260                                                           | 5         | 3.25%   |
| Intel Wi-Fi 6 AX201                                                           | 5         | 3.25%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                       | 5         | 3.25%   |
| Realtek 802.11ac NIC                                                          | 4         | 2.6%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 4         | 2.6%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                       | 4         | 2.6%    |
| Intel Wi-Fi 6 AX200                                                           | 4         | 2.6%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 3         | 1.95%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 3         | 1.95%   |
| Intel Wireless 7260                                                           | 3         | 1.95%   |
| Intel WiFi Link 5100                                                          | 3         | 1.95%   |
| Intel Centrino Ultimate-N 6300                                                | 3         | 1.95%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                   | 3         | 1.95%   |
| Broadcom BCM4331 802.11a/b/g/n                                                | 3         | 1.95%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 2         | 1.3%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 2         | 1.3%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2         | 1.3%    |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 2         | 1.3%    |
| Intel Wireless 3160                                                           | 2         | 1.3%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                               | 2         | 1.3%    |
| Intel Comet Lake PCH CNVi WiFi                                                | 2         | 1.3%    |
| Intel Alder Lake-P PCH CNVi WiFi                                              | 2         | 1.3%    |
| Broadcom BCM43142 802.11b/g/n                                                 | 2         | 1.3%    |
| ZyDAS ZD1211B 802.11g                                                         | 1         | 0.65%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                                      | 1         | 0.65%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 1         | 0.65%   |
| TP-Link 802.11ac WLAN Adapter                                                 | 1         | 0.65%   |
| TP-Link 802.11ac NIC                                                          | 1         | 0.65%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                   | 1         | 0.65%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1         | 0.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 1         | 0.65%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 1         | 0.65%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                   | 1         | 0.65%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter                       | 1         | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 93        | 46.73%  |
| Intel                    | 70        | 35.18%  |
| Broadcom                 | 10        | 5.03%   |
| Qualcomm Atheros         | 9         | 4.52%   |
| ASIX Electronics         | 4         | 2.01%   |
| Nvidia                   | 3         | 1.51%   |
| DisplayLink              | 2         | 1.01%   |
| Broadcom Limited         | 2         | 1.01%   |
| Aquantia                 | 2         | 1.01%   |
| MediaTek                 | 1         | 0.5%    |
| Marvell Technology Group | 1         | 0.5%    |
| ICS Advent               | 1         | 0.5%    |
| Hewlett-Packard          | 1         | 0.5%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 76        | 37.44%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 18        | 8.87%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 8         | 3.94%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 8         | 3.94%   |
| Intel I211 Gigabit Network Connection                                          | 6         | 2.96%   |
| Intel Ethernet Connection I217-LM                                              | 5         | 2.46%   |
| Intel Ethernet Connection (2) I219-V                                           | 4         | 1.97%   |
| Intel Ethernet Controller I225-V                                               | 3         | 1.48%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 3         | 1.48%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 2         | 0.99%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 2         | 0.99%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 2         | 0.99%   |
| Nvidia MCP77 Ethernet                                                          | 2         | 0.99%   |
| Intel Ethernet Connection I219-V                                               | 2         | 0.99%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 0.99%   |
| Intel Ethernet Connection I217-V                                               | 2         | 0.99%   |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 0.99%   |
| Intel Ethernet Connection (7) I219-LM                                          | 2         | 0.99%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2         | 0.99%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 0.99%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 0.99%   |
| Intel 82574L Gigabit Network Connection                                        | 2         | 0.99%   |
| Intel 82567LM Gigabit Network Connection                                       | 2         | 0.99%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                              | 2         | 0.99%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 2         | 0.99%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 2         | 0.99%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1         | 0.49%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.49%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 1         | 0.49%   |
| Realtek Killer E2600 GbE Controller                                            | 1         | 0.49%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.49%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.49%   |
| Nvidia MCP61 Ethernet                                                          | 1         | 0.49%   |
| MediaTek File-CD Gadget                                                        | 1         | 0.49%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 0.49%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 0.49%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.49%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.49%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 0.49%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 182       | 53.69%  |
| WiFi     | 150       | 44.25%  |
| Modem    | 6         | 1.77%   |
| Unknown  | 1         | 0.29%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 109       | 50.23%  |
| Ethernet | 108       | 49.77%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 114       | 56.44%  |
| 1     | 82        | 40.59%  |
| 3     | 4         | 1.98%   |
| 0     | 2         | 0.99%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 155       | 76.35%  |
| Yes  | 48        | 23.65%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 57        | 49.14%  |
| Qualcomm Atheros Communications | 9         | 7.76%   |
| Realtek Semiconductor           | 8         | 6.9%    |
| Apple                           | 7         | 6.03%   |
| Cambridge Silicon Radio         | 6         | 5.17%   |
| Broadcom                        | 6         | 5.17%   |
| MediaTek                        | 4         | 3.45%   |
| ASUSTek Computer                | 4         | 3.45%   |
| IMC Networks                    | 3         | 2.59%   |
| Realtek                         | 2         | 1.72%   |
| Ralink Technology               | 2         | 1.72%   |
| Lite-On Technology              | 2         | 1.72%   |
| Hewlett-Packard                 | 2         | 1.72%   |
| Dell                            | 2         | 1.72%   |
| Ralink                          | 1         | 0.86%   |
| Foxconn International           | 1         | 0.86%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 26        | 22.41%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 9         | 7.76%   |
| Intel AX201 Bluetooth                               | 8         | 6.9%    |
| Realtek Bluetooth Radio                             | 6         | 5.17%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6         | 5.17%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 5         | 4.31%   |
| MediaTek Wireless_Device                            | 4         | 3.45%   |
| Intel AX200 Bluetooth                               | 4         | 3.45%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 4         | 3.45%   |
| Apple Bluetooth USB Host Controller                 | 4         | 3.45%   |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 2.59%   |
| Intel Bluetooth Device                              | 3         | 2.59%   |
| Realtek Bluetooth Radio                             | 2         | 1.72%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 1.72%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 1.72%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 1.72%   |
| IMC Networks Bluetooth Radio                        | 2         | 1.72%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2         | 1.72%   |
| Apple Bluetooth Host Controller                     | 2         | 1.72%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.86%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 0.86%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.86%   |
| Ralink CSR BS8510                                   | 1         | 0.86%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.86%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.86%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.86%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.86%   |
| Intel AX210 Bluetooth                               | 1         | 0.86%   |
| IMC Networks Wireless_Device                        | 1         | 0.86%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 0.86%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.86%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.86%   |
| Dell Wireless 370 Bluetooth Mini-card               | 1         | 0.86%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.86%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 0.86%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 0.86%   |
| ASUS BT-270 Bluetooth Adapter                       | 1         | 0.86%   |
| ASUS BCM20702A0                                     | 1         | 0.86%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 0.86%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 143       | 42.69%  |
| AMD                                  | 63        | 18.81%  |
| Nvidia                               | 62        | 18.51%  |
| C-Media Electronics                  | 7         | 2.09%   |
| Texas Instruments                    | 5         | 1.49%   |
| Yamaha                               | 4         | 1.19%   |
| M-Audio                              | 3         | 0.9%    |
| Logitech                             | 3         | 0.9%    |
| JMTek                                | 3         | 0.9%    |
| Focusrite-Novation                   | 3         | 0.9%    |
| QinHeng Electronics                  | 2         | 0.6%    |
| PreSonus Audio Electronics           | 2         | 0.6%    |
| Mackie Designs                       | 2         | 0.6%    |
| Generalplus Technology               | 2         | 0.6%    |
| Creative Technology                  | 2         | 0.6%    |
| ASUSTek Computer                     | 2         | 0.6%    |
| ZOOM                                 | 1         | 0.3%    |
| Yealink Network Technology           | 1         | 0.3%    |
| Xilinx                               | 1         | 0.3%    |
| Thesycon Systemsoftware & Consulting | 1         | 0.3%    |
| Textech International                | 1         | 0.3%    |
| Tenx Technology                      | 1         | 0.3%    |
| TEAC                                 | 1         | 0.3%    |
| Studiologic                          | 1         | 0.3%    |
| SteelSeries ApS                      | 1         | 0.3%    |
| Samson Technologies                  | 1         | 0.3%    |
| Plantronics                          | 1         | 0.3%    |
| MIDITECH                             | 1         | 0.3%    |
| Medeli Electronics                   | 1         | 0.3%    |
| Mark of the Unicorn                  | 1         | 0.3%    |
| Lenovo                               | 1         | 0.3%    |
| KTMicro                              | 1         | 0.3%    |
| Harman                               | 1         | 0.3%    |
| Evolution Electronics                | 1         | 0.3%    |
| Ensoniq                              | 1         | 0.3%    |
| Dell                                 | 1         | 0.3%    |
| BR23                                 | 1         | 0.3%    |
| Behringer.......                     | 1         | 0.3%    |
| BEHRINGER International              | 1         | 0.3%    |
| Audient                              | 1         | 0.3%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                            | 21        | 5.37%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 15        | 3.84%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 15        | 3.84%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 14        | 3.58%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 14        | 3.58%   |
| Intel Cannon Lake PCH cAVS                                                        | 12        | 3.07%   |
| Intel Sunrise Point-LP HD Audio                                                   | 11        | 2.81%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 10        | 2.56%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 9         | 2.3%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 9         | 2.3%    |
| AMD Starship/Matisse HD Audio Controller                                          | 9         | 2.3%    |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 8         | 2.05%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 8         | 2.05%   |
| AMD FCH Azalia Controller                                                         | 7         | 1.79%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 6         | 1.53%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 6         | 1.53%   |
| Intel Broadwell-U Audio Controller                                                | 6         | 1.53%   |
| Intel 200 Series PCH HD Audio                                                     | 6         | 1.53%   |
| Nvidia GF108 High Definition Audio Controller                                     | 5         | 1.28%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 5         | 1.28%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 5         | 1.28%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 5         | 1.28%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                         | 4         | 1.02%   |
| Intel Comet Lake PCH cAVS                                                         | 4         | 1.02%   |
| AMD Kabini HDMI/DP Audio                                                          | 4         | 1.02%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 4         | 1.02%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 4         | 1.02%   |
| Texas Instruments PCM2902 Audio Codec                                             | 3         | 0.77%   |
| Nvidia TU116 High Definition Audio Controller                                     | 3         | 0.77%   |
| Nvidia GT216 HDMI Audio Controller                                                | 3         | 0.77%   |
| Nvidia GP108 High Definition Audio Controller                                     | 3         | 0.77%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 3         | 0.77%   |
| Nvidia GP106 High Definition Audio Controller                                     | 3         | 0.77%   |
| Nvidia GP104 High Definition Audio Controller                                     | 3         | 0.77%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 3         | 0.77%   |
| Nvidia GF119 HDMI Audio Controller                                                | 3         | 0.77%   |
| Nvidia GA106 High Definition Audio Controller                                     | 3         | 0.77%   |
| Nvidia GA102 High Definition Audio Controller                                     | 3         | 0.77%   |
| Intel Haswell-ULT HD Audio Controller                                             | 3         | 0.77%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 3         | 0.77%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 54        | 22.04%  |
| SK hynix            | 50        | 20.41%  |
| Kingston            | 28        | 11.43%  |
| Micron Technology   | 23        | 9.39%   |
| Unknown             | 19        | 7.76%   |
| Crucial             | 15        | 6.12%   |
| Corsair             | 12        | 4.9%    |
| G.Skill             | 10        | 4.08%   |
| Patriot             | 6         | 2.45%   |
| Ramaxel Technology  | 5         | 2.04%   |
| Nanya Technology    | 3         | 1.22%   |
| A-DATA Technology   | 3         | 1.22%   |
| Timetec             | 2         | 0.82%   |
| Elpida              | 2         | 0.82%   |
| Wodposit            | 1         | 0.41%   |
| Unifosa             | 1         | 0.41%   |
| Transcend           | 1         | 0.41%   |
| Smart               | 1         | 0.41%   |
| S                   | 1         | 0.41%   |
| PNY                 | 1         | 0.41%   |
| OCZ                 | 1         | 0.41%   |
| M                   | 1         | 0.41%   |
| HBS                 | 1         | 0.41%   |
| Goldkey             | 1         | 0.41%   |
| Aeneon              | 1         | 0.41%   |
| 0194808980CE        | 1         | 0.41%   |
| Unknown             | 1         | 0.41%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s  | 4         | 1.49%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s   | 4         | 1.49%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s | 3         | 1.12%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s | 3         | 1.12%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s  | 3         | 1.12%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s    | 3         | 1.12%   |
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3600MT/s    | 3         | 1.12%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s   | 3         | 1.12%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                | 2         | 0.74%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s               | 2         | 0.74%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s           | 2         | 0.74%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s | 2         | 0.74%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s   | 2         | 0.74%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s | 2         | 0.74%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s | 2         | 0.74%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s | 2         | 0.74%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s            | 2         | 0.74%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s  | 2         | 0.74%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s  | 2         | 0.74%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s  | 2         | 0.74%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s  | 2         | 0.74%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s  | 2         | 0.74%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s | 2         | 0.74%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s    | 2         | 0.74%   |
| Patriot RAM 2400 C15 Series 16GB SODIMM DDR4 2667MT/s  | 2         | 0.74%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s    | 2         | 0.74%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s  | 2         | 0.74%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3400MT/s | 2         | 0.74%   |
| Wodposit RAM WPBH26D408SWA-8G 8GB SODIMM DDR4 2667MT/s | 1         | 0.37%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s         | 1         | 0.37%   |
| Unknown RAM Module 512MB DIMM DDR 533MT/s              | 1         | 0.37%   |
| Unknown RAM Module 512MB DIMM DDR                      | 1         | 0.37%   |
| Unknown RAM Module 4GB DIMM SDRAM                      | 1         | 0.37%   |
| Unknown RAM Module 4GB DIMM DDR2 667MT/s               | 1         | 0.37%   |
| Unknown RAM Module 4GB DIMM 400MT/s                    | 1         | 0.37%   |
| Unknown RAM Module 4096MB SODIMM LPDDR3 1600MT/s       | 1         | 0.37%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                | 1         | 0.37%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s               | 1         | 0.37%   |
| Unknown RAM Module 256MB DIMM DDR                      | 1         | 0.37%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s          | 1         | 0.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 87        | 42.23%  |
| DDR4    | 84        | 40.78%  |
| DDR2    | 13        | 6.31%   |
| SDRAM   | 6         | 2.91%   |
| Unknown | 6         | 2.91%   |
| LPDDR4  | 3         | 1.46%   |
| DDR     | 3         | 1.46%   |
| LPDDR3  | 2         | 0.97%   |
| LPDDR5  | 1         | 0.49%   |
| DDR5    | 1         | 0.49%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 107       | 52.45%  |
| DIMM         | 82        | 40.2%   |
| Row Of Chips | 11        | 5.39%   |
| RIMM         | 1         | 0.49%   |
| FB-DIMM      | 1         | 0.49%   |
| Chip         | 1         | 0.49%   |
| Unknown      | 1         | 0.49%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 76        | 32.48%  |
| 4096  | 75        | 32.05%  |
| 16384 | 29        | 12.39%  |
| 2048  | 27        | 11.54%  |
| 32768 | 13        | 5.56%   |
| 1024  | 11        | 4.7%    |
| 512   | 2         | 0.85%   |
| 256   | 1         | 0.43%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 62        | 27.56%  |
| 3200    | 24        | 10.67%  |
| 2667    | 21        | 9.33%   |
| 1333    | 15        | 6.67%   |
| 2400    | 14        | 6.22%   |
| 2133    | 11        | 4.89%   |
| 3600    | 10        | 4.44%   |
| 1334    | 9         | 4%      |
| 667     | 8         | 3.56%   |
| 1866    | 5         | 2.22%   |
| 800     | 5         | 2.22%   |
| 1800    | 4         | 1.78%   |
| 1066    | 4         | 1.78%   |
| Unknown | 4         | 1.78%   |
| 4267    | 3         | 1.33%   |
| 4199    | 2         | 0.89%   |
| 3400    | 2         | 0.89%   |
| 3266    | 2         | 0.89%   |
| 2933    | 2         | 0.89%   |
| 1867    | 2         | 0.89%   |
| 1067    | 2         | 0.89%   |
| 533     | 2         | 0.89%   |
| 6400    | 1         | 0.44%   |
| 4802    | 1         | 0.44%   |
| 3500    | 1         | 0.44%   |
| 3466    | 1         | 0.44%   |
| 3000    | 1         | 0.44%   |
| 2934    | 1         | 0.44%   |
| 2800    | 1         | 0.44%   |
| 2666    | 1         | 0.44%   |
| 2472    | 1         | 0.44%   |
| 1639    | 1         | 0.44%   |
| 1632    | 1         | 0.44%   |
| 400     | 1         | 0.44%   |

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
| Chicony Electronics                    | 23        | 19.17%  |
| IMC Networks                           | 9         | 7.5%    |
| Realtek Semiconductor                  | 8         | 6.67%   |
| Logitech                               | 8         | 6.67%   |
| Microdia                               | 7         | 5.83%   |
| Suyin                                  | 6         | 5%      |
| Sunplus Innovation Technology          | 6         | 5%      |
| Syntek                                 | 5         | 4.17%   |
| Quanta                                 | 5         | 4.17%   |
| Apple                                  | 5         | 4.17%   |
| Lite-On Technology                     | 3         | 2.5%    |
| Cheng Uei Precision Industry (Foxlink) | 3         | 2.5%    |
| Bison Electronics                      | 3         | 2.5%    |
| Xiongmai                               | 2         | 1.67%   |
| Sonix Technology                       | 2         | 1.67%   |
| Samsung Electronics                    | 2         | 1.67%   |
| Philips (or NXP)                       | 2         | 1.67%   |
| Microsoft                              | 2         | 1.67%   |
| Acer                                   | 2         | 1.67%   |
| ViewSonic                              | 1         | 0.83%   |
| ViewQuest Technologies                 | 1         | 0.83%   |
| Trust                                  | 1         | 0.83%   |
| Sweex                                  | 1         | 0.83%   |
| Sunplus IT                             | 1         | 0.83%   |
| Silicon Motion                         | 1         | 0.83%   |
| SHENZHEN AONI ELECTRONIC               | 1         | 0.83%   |
| Ricoh                                  | 1         | 0.83%   |
| Razer USA                              | 1         | 0.83%   |
| MacroSilicon                           | 1         | 0.83%   |
| Luxvisions Innotech Limited            | 1         | 0.83%   |
| Jieli Technology                       | 1         | 0.83%   |
| Intel                                  | 1         | 0.83%   |
| Importek                               | 1         | 0.83%   |
| HRY                                    | 1         | 0.83%   |
| Dynex                                  | 1         | 0.83%   |
| Dell                                   | 1         | 0.83%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                         | 6         | 4.96%   |
| Syntek Integrated Camera                          | 5         | 4.13%   |
| IMC Networks Integrated Camera                    | 4         | 3.31%   |
| Realtek Lenovo EasyCamera                         | 3         | 2.48%   |
| IMC Networks USB2.0 HD UVC WebCam                 | 3         | 2.48%   |
| Chicony Integrated Camera [ThinkPad]              | 3         | 2.48%   |
| Chicony HD User Facing                            | 3         | 2.48%   |
| Xiongmai web camera                               | 2         | 1.65%   |
| Suyin USB 2.0 Camera                              | 2         | 1.65%   |
| Suyin Asus Integrated Webcam                      | 2         | 1.65%   |
| Sunplus Integrated_Webcam_HD                      | 2         | 1.65%   |
| Sunplus HD WebCam                                 | 2         | 1.65%   |
| Sonix USB2.0 HD UVC WebCam                        | 2         | 1.65%   |
| Samsung Galaxy series, misc. (MTP mode)           | 2         | 1.65%   |
| Realtek Integrated_Webcam_HD                      | 2         | 1.65%   |
| Microdia Integrated_Webcam_HD                     | 2         | 1.65%   |
| Logitech Webcam C270                              | 2         | 1.65%   |
| Chicony HP HD Camera                              | 2         | 1.65%   |
| Chicony HD Webcam                                 | 2         | 1.65%   |
| Bison Integrated Camera                           | 2         | 1.65%   |
| Apple FaceTime HD Camera (Built-in)               | 2         | 1.65%   |
| Apple FaceTime HD Camera                          | 2         | 1.65%   |
| ViewSonic PC Camera                               | 1         | 0.83%   |
| ViewQuest Ability GABB Webcam                     | 1         | 0.83%   |
| Trust AUKEY PC-LM1A Webcam                        | 1         | 0.83%   |
| Sweex WC060 Series HD Webcam                      | 1         | 0.83%   |
| Suyin HP Webcam                                   | 1         | 0.83%   |
| Suyin HP TrueVision HD Integrated Webcam          | 1         | 0.83%   |
| Sunplus IT AUKEY PC-LM1 USB Camera                | 1         | 0.83%   |
| Sunplus HD 720P webcam                            | 1         | 0.83%   |
| Sunplus Dell HD Webcam                            | 1         | 0.83%   |
| Silicon Motion WebCam SCB-1100N                   | 1         | 0.83%   |
| SHENZHEN AONI ELECTRONIC NexiGo N930AF FHD Webcam | 1         | 0.83%   |
| Ricoh Sony Vaio Integrated Webcam                 | 1         | 0.83%   |
| Realtek VGA WebCam                                | 1         | 0.83%   |
| Realtek USB Camera                                | 1         | 0.83%   |
| Realtek HP Wide Vision HD Camera                  | 1         | 0.83%   |
| Razer USA Gaming Webcam [Kiyo]                    | 1         | 0.83%   |
| Quanta ov9734_techfront_camera                    | 1         | 0.83%   |
| Quanta Laptop_Integrated_Webcam_2HDM              | 1         | 0.83%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 8         | 44.44%  |
| Shenzhen Goodix Technology | 4         | 22.22%  |
| Synaptics                  | 3         | 16.67%  |
| LighTuning Technology      | 1         | 5.56%   |
| Focal-systems.Corp         | 1         | 5.56%   |
| AuthenTec                  | 1         | 5.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader        | 2         | 11.11%  |
| Validity Sensors VFS 5011 fingerprint sensor      | 2         | 11.11%  |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 2         | 11.11%  |
| Shenzhen Goodix  Fingerprint Device               | 2         | 11.11%  |
| Shenzhen Goodix Fingerprint Reader                | 2         | 11.11%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 1         | 5.56%   |
| Validity Sensors VFS5011 Fingerprint Reader       | 1         | 5.56%   |
| Validity Sensors VFS301 Fingerprint Reader        | 1         | 5.56%   |
| Validity Sensors Fingerprint scanner              | 1         | 5.56%   |
| Synaptics Fingerprint reader [HP G6]              | 1         | 5.56%   |
| LighTuning ES603 Swipe Fingerprint Sensor         | 1         | 5.56%   |
| Focal-systems.Corp FT9201Fingerprint.Ì         | 1         | 5.56%   |
| AuthenTec AES2501 Fingerprint Sensor              | 1         | 5.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Broadcom            | 5         | 41.67%  |
| Upek                | 3         | 25%     |
| Alcor Micro         | 2         | 16.67%  |
| Lenovo              | 1         | 8.33%   |
| Chicony Electronics | 1         | 8.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 25%     |
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 25%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 16.67%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 16.67%  |
| Lenovo Integrated Smart Card Reader                                          | 1         | 8.33%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 8.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 144       | 71.29%  |
| 1     | 50        | 24.75%  |
| 2     | 7         | 3.47%   |
| 3     | 1         | 0.5%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 18        | 28.57%  |
| Graphics card            | 13        | 20.63%  |
| Chipcard                 | 10        | 15.87%  |
| Net/wireless             | 8         | 12.7%   |
| Multimedia controller    | 3         | 4.76%   |
| Camera                   | 3         | 4.76%   |
| Sound                    | 2         | 3.17%   |
| Unassigned class         | 1         | 1.59%   |
| Storage                  | 1         | 1.59%   |
| Modem                    | 1         | 1.59%   |
| Communication controller | 1         | 1.59%   |
| Card reader              | 1         | 1.59%   |
| Bluetooth                | 1         | 1.59%   |

