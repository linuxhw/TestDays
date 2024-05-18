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

Total: 253

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | AERO 15-X9                  | Notebook    | [a62c895461](https://linux-hardware.org/?probe=a62c895461) | Apr 26, 2024 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [25245adc43](https://linux-hardware.org/?probe=25245adc43) | Apr 26, 2024 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [1572659f68](https://linux-hardware.org/?probe=1572659f68) | Apr 24, 2024 |
| Samsung       | 730QCJ/730QCR               | Notebook    | [0d6a3363b8](https://linux-hardware.org/?probe=0d6a3363b8) | Apr 15, 2024 |
| ASUSTek       | P5WDG2 WS Pro               | Desktop     | [c370aff195](https://linux-hardware.org/?probe=c370aff195) | Apr 13, 2024 |
| Unknown       | Unknown                     | Desktop     | [b3cf1a2d4e](https://linux-hardware.org/?probe=b3cf1a2d4e) | Apr 05, 2024 |
| Acer          | Aspire A317-53              | Notebook    | [ddd85b18e6](https://linux-hardware.org/?probe=ddd85b18e6) | Apr 04, 2024 |
| HP            | Pavilion 15                 | Notebook    | [520fd1241e](https://linux-hardware.org/?probe=520fd1241e) | Mar 14, 2024 |
| ARDOR GAMI... | V15x_V17xPNKPNJPNH          | Notebook    | [cf518d2630](https://linux-hardware.org/?probe=cf518d2630) | Mar 10, 2024 |
| MSI           | Alpha 15 A4DEK              | Notebook    | [bf844ef78f](https://linux-hardware.org/?probe=bf844ef78f) | Mar 09, 2024 |
| Lenovo        | ThinkPad L540 20AV004VGE    | Notebook    | [05d6a4d686](https://linux-hardware.org/?probe=05d6a4d686) | Feb 03, 2024 |
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

![OS](./All/images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Ubuntu Studio 20.04 | 84        | 39.44%  |
| Ubuntu Studio 22.04 | 68        | 31.92%  |
| Ubuntu Studio 23.04 | 13        | 6.1%    |
| Ubuntu Studio 20.10 | 13        | 6.1%    |
| Ubuntu Studio 22.10 | 9         | 4.23%   |
| Ubuntu Studio 23.10 | 7         | 3.29%   |
| Ubuntu Studio 21.10 | 7         | 3.29%   |
| Ubuntu Studio 21.04 | 5         | 2.35%   |
| Ubuntu Studio 18.04 | 3         | 1.41%   |
| Ubuntu Studio 19.10 | 2         | 0.94%   |
| Ubuntu Studio 24.04 | 1         | 0.47%   |
| Ubuntu Studio 16.04 | 1         | 0.47%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu Studio | 210       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 6.2.0-1009-lowlatency  | 6         | 2.74%   |
| 5.15.0-56-lowlatency   | 5         | 2.28%   |
| 5.15.0-46-lowlatency   | 5         | 2.28%   |
| 5.13.0-28-lowlatency   | 5         | 2.28%   |
| 6.2.0-1003-lowlatency  | 4         | 1.83%   |
| 5.4.0-52-lowlatency    | 4         | 1.83%   |
| 5.4.0-42-lowlatency    | 4         | 1.83%   |
| 6.5.0-27-lowlatency    | 3         | 1.37%   |
| 6.2.0-1012-lowlatency  | 3         | 1.37%   |
| 5.8.0-55-lowlatency    | 3         | 1.37%   |
| 5.8.0-50-lowlatency    | 3         | 1.37%   |
| 5.8.0-44-lowlatency    | 3         | 1.37%   |
| 5.8.0-25-lowlatency    | 3         | 1.37%   |
| 5.4.0-65-lowlatency    | 3         | 1.37%   |
| 5.4.0-26-lowlatency    | 3         | 1.37%   |
| 5.15.0-67-lowlatency   | 3         | 1.37%   |
| 5.15.0-58-lowlatency   | 3         | 1.37%   |
| 5.15.0-52-lowlatency   | 3         | 1.37%   |
| 5.15.0-50-lowlatency   | 3         | 1.37%   |
| 5.15.0-48-lowlatency   | 3         | 1.37%   |
| 5.15.0-47-lowlatency   | 3         | 1.37%   |
| 5.11.0-44-lowlatency   | 3         | 1.37%   |
| 5.11.0-34-lowlatency   | 3         | 1.37%   |
| 6.5.0-25-lowlatency    | 2         | 0.91%   |
| 6.5.0-15-lowlatency    | 2         | 0.91%   |
| 6.5.0-13-lowlatency    | 2         | 0.91%   |
| 6.2.0-1018-lowlatency  | 2         | 0.91%   |
| 6.2.0-1014-lowlatency  | 2         | 0.91%   |
| 5.8.0-48-lowlatency    | 2         | 0.91%   |
| 5.8.0-29-lowlatency    | 2         | 0.91%   |
| 5.4.0-94-lowlatency    | 2         | 0.91%   |
| 5.4.0-58-lowlatency    | 2         | 0.91%   |
| 5.4.0-56-lowlatency    | 2         | 0.91%   |
| 5.4.0-45-lowlatency    | 2         | 0.91%   |
| 5.19.0-1021-lowlatency | 2         | 0.91%   |
| 5.19.0-1017-lowlatency | 2         | 0.91%   |
| 5.19.0-1015-lowlatency | 2         | 0.91%   |
| 5.19.0-1007-lowlatency | 2         | 0.91%   |
| 5.15.0-89-lowlatency   | 2         | 0.91%   |
| 5.15.0-79-lowlatency   | 2         | 0.91%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 54        | 25.35%  |
| 5.4.0   | 53        | 24.88%  |
| 5.8.0   | 23        | 10.8%   |
| 6.2.0   | 22        | 10.33%  |
| 5.11.0  | 15        | 7.04%   |
| 5.19.0  | 13        | 6.1%    |
| 6.5.0   | 12        | 5.63%   |
| 5.13.0  | 10        | 4.69%   |
| 4.15.0  | 3         | 1.41%   |
| 5.3.0   | 2         | 0.94%   |
| 6.8.0   | 1         | 0.47%   |
| 6.2.8   | 1         | 0.47%   |
| 5.7.6   | 1         | 0.47%   |
| 5.17.1  | 1         | 0.47%   |
| 5.15.6  | 1         | 0.47%   |
| 4.4.0   | 1         | 0.47%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 55        | 25.82%  |
| 5.4     | 53        | 24.88%  |
| 6.2     | 23        | 10.8%   |
| 5.8     | 23        | 10.8%   |
| 5.11    | 15        | 7.04%   |
| 5.19    | 13        | 6.1%    |
| 6.5     | 12        | 5.63%   |
| 5.13    | 10        | 4.69%   |
| 4.15    | 3         | 1.41%   |
| 5.3     | 2         | 0.94%   |
| 6.8     | 1         | 0.47%   |
| 5.7     | 1         | 0.47%   |
| 5.17    | 1         | 0.47%   |
| 4.4     | 1         | 0.47%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 208       | 99.05%  |
| i686    | 1         | 0.48%   |
| aarch64 | 1         | 0.48%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KDE5            | 111       | 52.61%  |
| XFCE            | 81        | 38.39%  |
| GNOME           | 11        | 5.21%   |
| LXQt            | 3         | 1.42%   |
| MATE            | 2         | 0.95%   |
| KDE             | 1         | 0.47%   |
| GNOME Flashback | 1         | 0.47%   |
| Cinnamon        | 1         | 0.47%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 197       | 93.36%  |
| Wayland | 10        | 4.74%   |
| Tty     | 4         | 1.9%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 103       | 49.05%  |
| TDM     | 49        | 23.33%  |
| LightDM | 45        | 21.43%  |
| GDM     | 11        | 5.24%   |
| LXDM    | 1         | 0.48%   |
| GDM3    | 1         | 0.48%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 83        | 39.34%  |
| fr_FR      | 25        | 11.85%  |
| de_DE      | 15        | 7.11%   |
| en_GB      | 11        | 5.21%   |
| it_IT      | 9         | 4.27%   |
| C          | 9         | 4.27%   |
| ru_RU      | 8         | 3.79%   |
| pt_BR      | 6         | 2.84%   |
| es_ES      | 5         | 2.37%   |
| en_CA      | 5         | 2.37%   |
| en_AU      | 3         | 1.42%   |
| nl_NL      | 2         | 0.95%   |
| hu_HU      | 2         | 0.95%   |
| es_MX      | 2         | 0.95%   |
| es_AR      | 2         | 0.95%   |
| en_IE      | 2         | 0.95%   |
| en_AG      | 2         | 0.95%   |
| Unknown    | 2         | 0.95%   |
| sv_SE      | 1         | 0.47%   |
| sk_SK      | 1         | 0.47%   |
| nl_BE      | 1         | 0.47%   |
| nb_NO      | 1         | 0.47%   |
| fr_FR.UTF8 | 1         | 0.47%   |
| fr_CH      | 1         | 0.47%   |
| fr_BE      | 1         | 0.47%   |
| es_NI      | 1         | 0.47%   |
| es_GT      | 1         | 0.47%   |
| es_CR      | 1         | 0.47%   |
| en_NG      | 1         | 0.47%   |
| en_IL      | 1         | 0.47%   |
| en_DE      | 1         | 0.47%   |
| de_CH      | 1         | 0.47%   |
| de_AT      | 1         | 0.47%   |
| ca_ES      | 1         | 0.47%   |
| ca_AD      | 1         | 0.47%   |
| bg_BG      | 1         | 0.47%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 125       | 59.52%  |
| BIOS | 85        | 40.48%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 201       | 95.71%  |
| Overlay | 7         | 3.33%   |
| Xfs     | 1         | 0.48%   |
| Ext2    | 1         | 0.48%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 139       | 66.19%  |
| MBR  | 71        | 33.81%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 170       | 79.81%  |
| Yes       | 43        | 20.19%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 116       | 54.98%  |
| Yes       | 95        | 45.02%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| ASUSTek Computer                     | 38        | 18.1%   |
| Lenovo                               | 30        | 14.29%  |
| Dell                                 | 30        | 14.29%  |
| Hewlett-Packard                      | 28        | 13.33%  |
| Gigabyte Technology                  | 16        | 7.62%   |
| Apple                                | 8         | 3.81%   |
| Acer                                 | 8         | 3.81%   |
| MSI                                  | 5         | 2.38%   |
| Toshiba                              | 4         | 1.9%    |
| Intel                                | 4         | 1.9%    |
| Fujitsu                              | 4         | 1.9%    |
| ASRock                               | 3         | 1.43%   |
| Samsung Electronics                  | 2         | 0.95%   |
| HUAWEI                               | 2         | 0.95%   |
| AZW                                  | 2         | 0.95%   |
| Unknown                              | 2         | 0.95%   |
| win element                          | 1         | 0.48%   |
| System76                             | 1         | 0.48%   |
| Sony                                 | 1         | 0.48%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.48%   |
| Razer                                | 1         | 0.48%   |
| Raspberry Pi Foundation              | 1         | 0.48%   |
| Pegatron                             | 1         | 0.48%   |
| Packard Bell                         | 1         | 0.48%   |
| Microsoft                            | 1         | 0.48%   |
| Medion                               | 1         | 0.48%   |
| Intel Client Systems                 | 1         | 0.48%   |
| IBM                                  | 1         | 0.48%   |
| GPU Company                          | 1         | 0.48%   |
| Google                               | 1         | 0.48%   |
| Getac                                | 1         | 0.48%   |
| Foxconn                              | 1         | 0.48%   |
| ECS                                  | 1         | 0.48%   |
| DEPO Computers                       | 1         | 0.48%   |
| COM1                                 | 1         | 0.48%   |
| Clevo                                | 1         | 0.48%   |
| Avell High Performance               | 1         | 0.48%   |
| ATOPNUC                              | 1         | 0.48%   |
| ARDOR GAMING                         | 1         | 0.48%   |
| Acidanthera                          | 1         | 0.48%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| ASUS All Series                            | 4         | 1.9%    |
| Unknown                                    | 3         | 1.43%   |
| Lenovo G50-45 80E3                         | 2         | 0.95%   |
| HP Pavilion dv6                            | 2         | 0.95%   |
| Dell OptiPlex 790                          | 2         | 0.95%   |
| ASUS TUF Gaming X570-PLUS                  | 2         | 0.95%   |
| ASUS PRIME X570-PRO                        | 2         | 0.95%   |
| ASUS M4A785-M                              | 2         | 0.95%   |
| Apple iMac18,3                             | 2         | 0.95%   |
| win element MoreFine S500+                 | 1         | 0.48%   |
| Toshiba Satellite L755D                    | 1         | 0.48%   |
| Toshiba Satellite L505                     | 1         | 0.48%   |
| Toshiba Satellite C855                     | 1         | 0.48%   |
| Toshiba Satellite A505                     | 1         | 0.48%   |
| System76 Thelio                            | 1         | 0.48%   |
| Sony VGN-NS31M_W                           | 1         | 0.48%   |
| Shenzhen Meigao Electronic Equipment HX90G | 1         | 0.48%   |
| Samsung 730QCJ/730QCR                      | 1         | 0.48%   |
| Samsung 305V4A/305V5A                      | 1         | 0.48%   |
| Razer Blade Stealth 13 Late 2019           | 1         | 0.48%   |
| RPi Raspberry Pi 4 Model B Rev 1.4         | 1         | 0.48%   |
| Pegatron FL368AA-UUZ SR5612CH              | 1         | 0.48%   |
| Packard Bell IMEDIA S3220                  | 1         | 0.48%   |
| MSI MS-7E02                                | 1         | 0.48%   |
| MSI MS-7C95                                | 1         | 0.48%   |
| MSI MS-7A57                                | 1         | 0.48%   |
| MSI MS-7752                                | 1         | 0.48%   |
| MSI Alpha 15 A4DEK                         | 1         | 0.48%   |
| Microsoft Surface Laptop 3                 | 1         | 0.48%   |
| Medion MD34207/C746                        | 1         | 0.48%   |
| Lenovo ZIWB2                               | 1         | 0.48%   |
| Lenovo ThinkPad X250 20CL001LMB            | 1         | 0.48%   |
| Lenovo ThinkPad X230 2333A86               | 1         | 0.48%   |
| Lenovo ThinkPad X230 2325AJG               | 1         | 0.48%   |
| Lenovo ThinkPad X230 23245S1               | 1         | 0.48%   |
| Lenovo ThinkPad X1 Yoga Gen 7 21CDCTO1WW   | 1         | 0.48%   |
| Lenovo ThinkPad X1 Carbon 6th 20KHCTO1WW   | 1         | 0.48%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A80035US   | 1         | 0.48%   |
| Lenovo ThinkPad W530 2447IG0               | 1         | 0.48%   |
| Lenovo ThinkPad T530 24296HG               | 1         | 0.48%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo ThinkPad                            | 15        | 7.14%   |
| Dell OptiPlex                              | 9         | 4.29%   |
| Dell Inspiron                              | 9         | 4.29%   |
| HP Compaq                                  | 8         | 3.81%   |
| Lenovo IdeaPad                             | 6         | 2.86%   |
| Dell Latitude                              | 6         | 2.86%   |
| Acer Aspire                                | 6         | 2.86%   |
| HP EliteBook                               | 5         | 2.38%   |
| ASUS ROG                                   | 5         | 2.38%   |
| Toshiba Satellite                          | 4         | 1.9%    |
| HP Pavilion                                | 4         | 1.9%    |
| Dell Precision                             | 4         | 1.9%    |
| ASUS All                                   | 4         | 1.9%    |
| Fujitsu ESPRIMO                            | 3         | 1.43%   |
| ASUS TUF                                   | 3         | 1.43%   |
| ASUS PRIME                                 | 3         | 1.43%   |
| Unknown                                    | 3         | 1.43%   |
| Lenovo Legion                              | 2         | 0.95%   |
| Lenovo G50-45                              | 2         | 0.95%   |
| HP ZBook                                   | 2         | 0.95%   |
| ASUS VivoBook                              | 2         | 0.95%   |
| ASUS P8P67                                 | 2         | 0.95%   |
| ASUS M4A785-M                              | 2         | 0.95%   |
| ASUS ASUS                                  | 2         | 0.95%   |
| Apple iMac18                               | 2         | 0.95%   |
| win element MoreFine                       | 1         | 0.48%   |
| System76 Thelio                            | 1         | 0.48%   |
| Sony VGN-NS31M                             | 1         | 0.48%   |
| Shenzhen Meigao Electronic Equipment HX90G | 1         | 0.48%   |
| Samsung 730QCJ                             | 1         | 0.48%   |
| Samsung 305V4A                             | 1         | 0.48%   |
| Razer Blade                                | 1         | 0.48%   |
| RPi Raspberry                              | 1         | 0.48%   |
| Pegatron FL368AA-UUZ                       | 1         | 0.48%   |
| Packard Bell IMEDIA                        | 1         | 0.48%   |
| MSI MS-7E02                                | 1         | 0.48%   |
| MSI MS-7C95                                | 1         | 0.48%   |
| MSI MS-7A57                                | 1         | 0.48%   |
| MSI MS-7752                                | 1         | 0.48%   |
| MSI Alpha                                  | 1         | 0.48%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 24        | 11.43%  |
| 2019 | 17        | 8.1%    |
| 2018 | 16        | 7.62%   |
| 2013 | 15        | 7.14%   |
| 2012 | 15        | 7.14%   |
| 2011 | 15        | 7.14%   |
| 2021 | 13        | 6.19%   |
| 2016 | 13        | 6.19%   |
| 2014 | 13        | 6.19%   |
| 2015 | 11        | 5.24%   |
| 2009 | 11        | 5.24%   |
| 2008 | 11        | 5.24%   |
| 2022 | 10        | 4.76%   |
| 2017 | 10        | 4.76%   |
| 2010 | 8         | 3.81%   |
| 2007 | 4         | 1.9%    |
| 2005 | 3         | 1.43%   |
| 2023 | 1         | 0.48%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 99        | 47.14%  |
| Desktop        | 93        | 44.29%  |
| All in one     | 7         | 3.33%   |
| Mini pc        | 6         | 2.86%   |
| Convertible    | 3         | 1.43%   |
| System on chip | 1         | 0.48%   |
| Tablet         | 1         | 0.48%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 197       | 93.81%  |
| Enabled  | 13        | 6.19%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 208       | 99.05%  |
| Yes  | 2         | 0.95%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 60        | 28.3%   |
| 16.01-24.0  | 44        | 20.75%  |
| 8.01-16.0   | 42        | 19.81%  |
| 32.01-64.0  | 26        | 12.26%  |
| 3.01-4.0    | 18        | 8.49%   |
| 64.01-256.0 | 11        | 5.19%   |
| 24.01-32.0  | 4         | 1.89%   |
| 1.01-2.0    | 4         | 1.89%   |
| 2.01-3.0    | 3         | 1.42%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 64        | 29.91%  |
| 2.01-3.0   | 54        | 25.23%  |
| 4.01-8.0   | 39        | 18.22%  |
| 3.01-4.0   | 36        | 16.82%  |
| 8.01-16.0  | 16        | 7.48%   |
| 0.51-1.0   | 4         | 1.87%   |
| 24.01-32.0 | 1         | 0.47%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 116       | 54.72%  |
| 2      | 67        | 31.6%   |
| 3      | 12        | 5.66%   |
| 4      | 5         | 2.36%   |
| 5      | 4         | 1.89%   |
| 7      | 3         | 1.42%   |
| 0      | 2         | 0.94%   |
| 16     | 1         | 0.47%   |
| 11     | 1         | 0.47%   |
| 10     | 1         | 0.47%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 120       | 56.87%  |
| Yes       | 91        | 43.13%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 189       | 89.57%  |
| No        | 22        | 10.43%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 157       | 74.76%  |
| No        | 53        | 25.24%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 122       | 58.1%   |
| No        | 88        | 41.9%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country                | Computers | Percent |
|------------------------|-----------|---------|
| USA                    | 53        | 25.24%  |
| France                 | 25        | 11.9%   |
| Germany                | 23        | 10.95%  |
| Italy                  | 13        | 6.19%   |
| Russia                 | 9         | 4.29%   |
| Spain                  | 8         | 3.81%   |
| Brazil                 | 8         | 3.81%   |
| UK                     | 6         | 2.86%   |
| Canada                 | 6         | 2.86%   |
| Belgium                | 5         | 2.38%   |
| Austria                | 5         | 2.38%   |
| Sweden                 | 4         | 1.9%    |
| Australia              | 4         | 1.9%    |
| Norway                 | 3         | 1.43%   |
| Netherlands            | 3         | 1.43%   |
| Mexico                 | 3         | 1.43%   |
| Taiwan                 | 2         | 0.95%   |
| Switzerland            | 2         | 0.95%   |
| Romania                | 2         | 0.95%   |
| Ivory Coast            | 2         | 0.95%   |
| Hungary                | 2         | 0.95%   |
| Costa Rica             | 2         | 0.95%   |
| Bulgaria               | 2         | 0.95%   |
| Argentina              | 2         | 0.95%   |
| Yemen                  | 1         | 0.48%   |
| Turkey                 | 1         | 0.48%   |
| South Africa           | 1         | 0.48%   |
| Slovakia               | 1         | 0.48%   |
| Poland                 | 1         | 0.48%   |
| Peru                   | 1         | 0.48%   |
| Nigeria                | 1         | 0.48%   |
| Nicaragua              | 1         | 0.48%   |
| Luxembourg             | 1         | 0.48%   |
| Kenya                  | 1         | 0.48%   |
| Israel                 | 1         | 0.48%   |
| Ireland                | 1         | 0.48%   |
| Indonesia              | 1         | 0.48%   |
| Guatemala              | 1         | 0.48%   |
| Finland                | 1         | 0.48%   |
| Bosnia and Herzegovina | 1         | 0.48%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Stockholm     | 4         | 1.88%   |
| Paris         | 4         | 1.88%   |
| Madrid        | 4         | 1.88%   |
| Vienna        | 3         | 1.41%   |
| Houston       | 3         | 1.41%   |
| Turin         | 2         | 0.94%   |
| Stuttgart     | 2         | 0.94%   |
| San Francisco | 2         | 0.94%   |
| Moscow        | 2         | 0.94%   |
| Montreal      | 2         | 0.94%   |
| Mississauga   | 2         | 0.94%   |
| Hamburg       | 2         | 0.94%   |
| Groningen     | 2         | 0.94%   |
| Fürth        | 2         | 0.94%   |
| Denver        | 2         | 0.94%   |
| Budapest      | 2         | 0.94%   |
| Bucharest     | 2         | 0.94%   |
| Béziers      | 2         | 0.94%   |
| Abidjan       | 2         | 0.94%   |
| Zele          | 1         | 0.47%   |
| Zanesville    | 1         | 0.47%   |
| Yonkers       | 1         | 0.47%   |
| Yekaterinburg | 1         | 0.47%   |
| Wroclaw       | 1         | 0.47%   |
| Woonsocket    | 1         | 0.47%   |
| Woodland Park | 1         | 0.47%   |
| Wildenfels    | 1         | 0.47%   |
| West Mifflin  | 1         | 0.47%   |
| Warner Robins | 1         | 0.47%   |
| Villetaneuse  | 1         | 0.47%   |
| Villefontaine | 1         | 0.47%   |
| Verviers      | 1         | 0.47%   |
| Verdal        | 1         | 0.47%   |
| Velleron      | 1         | 0.47%   |
| Toulouse      | 1         | 0.47%   |
| Toronto       | 1         | 0.47%   |
| Tilburg       | 1         | 0.47%   |
| Taylor        | 1         | 0.47%   |
| Tarragona     | 1         | 0.47%   |
| Taipei        | 1         | 0.47%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 53        | 66     | 16.31%  |
| WDC                         | 52        | 62     | 16%     |
| Seagate                     | 38        | 63     | 11.69%  |
| Toshiba                     | 19        | 20     | 5.85%   |
| SanDisk                     | 19        | 20     | 5.85%   |
| Kingston                    | 12        | 13     | 3.69%   |
| Hitachi                     | 12        | 13     | 3.69%   |
| SK hynix                    | 11        | 12     | 3.38%   |
| Intel                       | 10        | 16     | 3.08%   |
| Crucial                     | 9         | 9      | 2.77%   |
| Unknown                     | 7         | 7      | 2.15%   |
| PNY                         | 5         | 6      | 1.54%   |
| Phison                      | 5         | 5      | 1.54%   |
| HGST                        | 5         | 6      | 1.54%   |
| Micron Technology           | 4         | 4      | 1.23%   |
| Team                        | 3         | 3      | 0.92%   |
| SPCC                        | 3         | 3      | 0.92%   |
| JMicron Technology          | 3         | 3      | 0.92%   |
| Intenso                     | 3         | 3      | 0.92%   |
| China                       | 3         | 3      | 0.92%   |
| ASMT                        | 3         | 3      | 0.92%   |
| Apple                       | 3         | 5      | 0.92%   |
| A-DATA Technology           | 3         | 4      | 0.92%   |
| UMIS                        | 2         | 2      | 0.62%   |
| KIOXIA                      | 2         | 2      | 0.62%   |
| Kingston Technology Company | 2         | 3      | 0.62%   |
| Fujitsu                     | 2         | 2      | 0.62%   |
| Corsair                     | 2         | 3      | 0.62%   |
| BHT                         | 2         | 2      | 0.62%   |
| XPG                         | 1         | 1      | 0.31%   |
| Wibtek                      | 1         | 1      | 0.31%   |
| USB 3.0                     | 1         | 2      | 0.31%   |
| Union Memory                | 1         | 1      | 0.31%   |
| TO Exter                    | 1         | 1      | 0.31%   |
| Timetec                     | 1         | 1      | 0.31%   |
| Silicon Motion              | 1         | 1      | 0.31%   |
| SCY                         | 1         | 1      | 0.31%   |
| Reeinno                     | 1         | 1      | 0.31%   |
| Realtek Semiconductor       | 1         | 1      | 0.31%   |
| Realtek                     | 1         | 1      | 0.31%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB                    | 4         | 1.11%   |
| Seagate ST500DM002-1BD142 500GB           | 4         | 1.11%   |
| Seagate ST2000DM001-1ER164 2TB            | 4         | 1.11%   |
| Samsung SSD 870 EVO 1TB                   | 4         | 1.11%   |
| Samsung SSD 860 EVO 500GB                 | 4         | 1.11%   |
| Seagate ST2000DM008-2FR102 2TB            | 3         | 0.83%   |
| Seagate Expansion+ Desk 4TB               | 3         | 0.83%   |
| Kingston SA400S37240G 240GB SSD           | 3         | 0.83%   |
| Crucial CT500MX500SSD1 500GB              | 3         | 0.83%   |
| WDC WDS200T2B0A-00SM50 2TB SSD            | 2         | 0.55%   |
| WDC WD10SPZX-21Z10T0 1TB                  | 2         | 0.55%   |
| WDC WD10EZEX-08WN4A0 1TB                  | 2         | 0.55%   |
| WDC PC SN530 SDBPNPZ-512G-1002 512GB      | 2         | 0.55%   |
| Toshiba MQ04ABF100 1TB                    | 2         | 0.55%   |
| Toshiba HDWD130 3TB                       | 2         | 0.55%   |
| Toshiba DT01ACA100 1TB                    | 2         | 0.55%   |
| Toshiba DT01ACA050 500GB                  | 2         | 0.55%   |
| Team T253X6001T 1TB SSD                   | 2         | 0.55%   |
| SPCC Solid State Disk 256GB               | 2         | 0.55%   |
| SK hynix SKHynix_HFM512GDHTNI-87A0B 512GB | 2         | 0.55%   |
| Seagate ST5000LM000-2AN170 5TB            | 2         | 0.55%   |
| Seagate Expansion 2TB                     | 2         | 0.55%   |
| SanDisk SSD PLUS 240GB                    | 2         | 0.55%   |
| SanDisk SDSSDA240G 240GB                  | 2         | 0.55%   |
| Samsung SSD 970 EVO Plus 500GB            | 2         | 0.55%   |
| Samsung SSD 970 EVO Plus 1TB              | 2         | 0.55%   |
| Samsung SSD 960 PRO 512GB                 | 2         | 0.55%   |
| Samsung SSD 860 EVO 1TB                   | 2         | 0.55%   |
| Samsung SSD 850 EVO 500GB                 | 2         | 0.55%   |
| Samsung MZ7TD256HAFV-000L7 256GB SSD      | 2         | 0.55%   |
| Samsung HD753LJ 752GB                     | 2         | 0.55%   |
| PNY CS900 1TB SSD                         | 2         | 0.55%   |
| Phison Sabrent 1TB                        | 2         | 0.55%   |
| Kingston SA400S37480G 480GB SSD           | 2         | 0.55%   |
| Kingston SA400S37120G 120GB SSD           | 2         | 0.55%   |
| JMicron Generic 320GB                     | 2         | 0.55%   |
| Crucial CT1000MX500SSD1 1TB               | 2         | 0.55%   |
| China SSD 1TB                             | 2         | 0.55%   |
| Apple SSD SM0032L 32GB                    | 2         | 0.55%   |
| Apple HDD ST1000DM003 1TB                 | 2         | 0.55%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 39        | 49     | 30.47%  |
| Seagate             | 37        | 60     | 28.91%  |
| Toshiba             | 18        | 19     | 14.06%  |
| Hitachi             | 12        | 13     | 9.38%   |
| Samsung Electronics | 5         | 5      | 3.91%   |
| HGST                | 5         | 6      | 3.91%   |
| JMicron Technology  | 2         | 2      | 1.56%   |
| Fujitsu             | 2         | 2      | 1.56%   |
| Apple               | 2         | 2      | 1.56%   |
| USB 3.0             | 1         | 2      | 0.78%   |
| Unknown             | 1         | 1      | 0.78%   |
| TO Exter            | 1         | 1      | 0.78%   |
| Maxtor              | 1         | 1      | 0.78%   |
| Inateck             | 1         | 1      | 0.78%   |
| ASMT                | 1         | 1      | 0.78%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 29        | 34     | 25.89%  |
| SanDisk             | 15        | 16     | 13.39%  |
| Kingston            | 11        | 12     | 9.82%   |
| Crucial             | 8         | 8      | 7.14%   |
| WDC                 | 5         | 5      | 4.46%   |
| PNY                 | 5         | 6      | 4.46%   |
| SPCC                | 3         | 3      | 2.68%   |
| Micron Technology   | 3         | 3      | 2.68%   |
| Intenso             | 3         | 3      | 2.68%   |
| China               | 3         | 3      | 2.68%   |
| Team                | 2         | 2      | 1.79%   |
| SK hynix            | 2         | 2      | 1.79%   |
| BHT                 | 2         | 2      | 1.79%   |
| ASMT                | 2         | 2      | 1.79%   |
| A-DATA Technology   | 2         | 2      | 1.79%   |
| Wibtek              | 1         | 1      | 0.89%   |
| Toshiba             | 1         | 1      | 0.89%   |
| SCY                 | 1         | 1      | 0.89%   |
| Reeinno             | 1         | 1      | 0.89%   |
| Patriot             | 1         | 1      | 0.89%   |
| OCZ                 | 1         | 1      | 0.89%   |
| NGFF                | 1         | 1      | 0.89%   |
| LITEON              | 1         | 1      | 0.89%   |
| Lexar               | 1         | 1      | 0.89%   |
| Leven               | 1         | 1      | 0.89%   |
| KingSpec            | 1         | 1      | 0.89%   |
| Intel               | 1         | 1      | 0.89%   |
| Integral            | 1         | 1      | 0.89%   |
| External            | 1         | 1      | 0.89%   |
| EDGE eMe            | 1         | 1      | 0.89%   |
| Dogfish             | 1         | 1      | 0.89%   |
| Corsair             | 1         | 1      | 0.89%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 102       | 165    | 36.82%  |
| SSD     | 94        | 120    | 33.94%  |
| NVMe    | 70        | 95     | 25.27%  |
| MMC     | 8         | 9      | 2.89%   |
| Unknown | 3         | 3      | 1.08%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 157       | 263    | 61.57%  |
| NVMe | 70        | 94     | 27.45%  |
| SAS  | 20        | 26     | 7.84%   |
| MMC  | 8         | 9      | 3.14%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 117       | 150    | 53.18%  |
| 0.51-1.0   | 65        | 75     | 29.55%  |
| 1.01-2.0   | 19        | 22     | 8.64%   |
| 3.01-4.0   | 10        | 12     | 4.55%   |
| 4.01-10.0  | 6         | 22     | 2.73%   |
| 2.01-3.0   | 3         | 4      | 1.36%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 59        | 27.44%  |
| 251-500        | 41        | 19.07%  |
| 501-1000       | 37        | 17.21%  |
| 1001-2000      | 31        | 14.42%  |
| More than 3000 | 17        | 7.91%   |
| 51-100         | 12        | 5.58%   |
| 21-50          | 10        | 4.65%   |
| 1-20           | 6         | 2.79%   |
| 2001-3000      | 2         | 0.93%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 66        | 30.7%   |
| 21-50          | 35        | 16.28%  |
| 101-250        | 35        | 16.28%  |
| 251-500        | 22        | 10.23%  |
| 51-100         | 18        | 8.37%   |
| 501-1000       | 16        | 7.44%   |
| More than 3000 | 10        | 4.65%   |
| 1001-2000      | 9         | 4.19%   |
| 2001-3000      | 4         | 1.86%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


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

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


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

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


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

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 31        | 39     | 77.5%   |
| SSD  | 7         | 8      | 17.5%   |
| NVMe | 2         | 2      | 5%      |

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
| Works    | 181       | 306    | 72.69%  |
| Malfunc  | 40        | 49     | 16.06%  |
| Detected | 26        | 35     | 10.44%  |
| Failed   | 2         | 2      | 0.8%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 144       | 51.25%  |
| AMD                          | 47        | 16.73%  |
| Samsung Electronics          | 24        | 8.54%   |
| SanDisk                      | 11        | 3.91%   |
| SK hynix                     | 9         | 3.2%    |
| Phison Electronics           | 8         | 2.85%   |
| Marvell Technology Group     | 6         | 2.14%   |
| ASMedia Technology           | 5         | 1.78%   |
| Union Memory (Shenzhen)      | 3         | 1.07%   |
| Nvidia                       | 3         | 1.07%   |
| Kingston Technology Company  | 3         | 1.07%   |
| Silicon Motion               | 2         | 0.71%   |
| Realtek Semiconductor        | 2         | 0.71%   |
| JMicron Technology           | 2         | 0.71%   |
| VIA Technologies             | 1         | 0.36%   |
| Toshiba America Info Systems | 1         | 0.36%   |
| Silicon Image                | 1         | 0.36%   |
| Seagate Technology           | 1         | 0.36%   |
| Micron/Crucial Technology    | 1         | 0.36%   |
| Micron Technology            | 1         | 0.36%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.36%   |
| LSI Logic / Symbios Logic    | 1         | 0.36%   |
| KIOXIA                       | 1         | 0.36%   |
| Apple                        | 1         | 0.36%   |
| ADATA Technology             | 1         | 0.36%   |
| Adaptec                      | 1         | 0.36%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 33        | 10.12%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 14        | 4.29%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 13        | 3.99%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 10        | 3.07%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 9         | 2.76%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 9         | 2.76%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 7         | 2.15%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 7         | 2.15%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 6         | 1.84%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 6         | 1.84%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 6         | 1.84%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 1.53%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 5         | 1.53%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 5         | 1.53%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 5         | 1.53%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 5         | 1.53%   |
| AMD 400 Series Chipset SATA Controller                                         | 5         | 1.53%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 4         | 1.23%   |
| Phison E12 NVMe Controller                                                     | 4         | 1.23%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 1.23%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 4         | 1.23%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4         | 1.23%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 4         | 1.23%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 4         | 1.23%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 3         | 0.92%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 0.92%   |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 0.92%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 3         | 0.92%   |
| Intel SATA Controller [RAID mode]                                              | 3         | 0.92%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 3         | 0.92%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 0.92%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 3         | 0.92%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 3         | 0.92%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 3         | 0.92%   |
| AMD 500 Series Chipset SATA Controller                                         | 3         | 0.92%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 256GB                          | 2         | 0.61%   |
| SK hynix BC511 NVMe SSD                                                        | 2         | 0.61%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 2         | 0.61%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 2         | 0.61%   |
| Samsung NVMe SSD SM0032L                                                       | 2         | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 159       | 56.58%  |
| NVMe | 71        | 25.27%  |
| IDE  | 29        | 10.32%  |
| RAID | 18        | 6.41%   |
| SAS  | 3         | 1.07%   |
| SCSI | 1         | 0.36%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 153       | 72.86%  |
| AMD    | 56        | 26.67%  |
| ARM    | 1         | 0.48%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| AMD Ryzen 5 4600H with Radeon Graphics  | 4         | 1.9%    |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 3         | 1.43%   |
| Intel Core i5-6500 CPU @ 3.20GHz        | 3         | 1.43%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 3         | 1.43%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 3         | 1.43%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 2         | 0.95%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 2         | 0.95%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 2         | 0.95%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 2         | 0.95%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 2         | 0.95%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 2         | 0.95%   |
| Intel Core i7-2630QM CPU @ 2.00GHz      | 2         | 0.95%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz       | 2         | 0.95%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 2         | 0.95%   |
| Intel Core i5-4590 CPU @ 3.30GHz        | 2         | 0.95%   |
| Intel Core i5-4440 CPU @ 3.10GHz        | 2         | 0.95%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 2         | 0.95%   |
| Intel Core i5-2540M CPU @ 2.60GHz       | 2         | 0.95%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 2         | 0.95%   |
| Intel Core i5-10300H CPU @ 2.50GHz      | 2         | 0.95%   |
| Intel Core i5 CPU 650 @ 3.20GHz         | 2         | 0.95%   |
| Intel Celeron N4000 CPU @ 1.10GHz       | 2         | 0.95%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 2         | 0.95%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 2         | 0.95%   |
| AMD Ryzen 9 5900HX with Radeon Graphics | 2         | 0.95%   |
| AMD Ryzen 9 3950X 16-Core Processor     | 2         | 0.95%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 2         | 0.95%   |
| AMD Ryzen 7 5825U with Radeon Graphics  | 2         | 0.95%   |
| AMD Ryzen 5 5600G with Radeon Graphics  | 2         | 0.95%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 2         | 0.95%   |
| AMD Phenom II X4 945 Processor          | 2         | 0.95%   |
| Intel Xeon W-2150B CPU @ 3.00GHz        | 1         | 0.48%   |
| Intel Xeon CPU E5420 @ 2.50GHz          | 1         | 0.48%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz     | 1         | 0.48%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz      | 1         | 0.48%   |
| Intel Processor 5Y10 CPU @ 0.80GHz      | 1         | 0.48%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz  | 1         | 0.48%   |
| Intel Pentium D CPU 3.40GHz             | 1         | 0.48%   |
| Intel Pentium CPU G3220 @ 3.00GHz       | 1         | 0.48%   |
| Intel Pentium 4 CPU 3.20GHz             | 1         | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i5          | 53        | 25.24%  |
| Intel Core i7          | 46        | 21.9%   |
| Other                  | 15        | 7.14%   |
| Intel Core i3          | 13        | 6.19%   |
| AMD Ryzen 5            | 12        | 5.71%   |
| AMD Ryzen 7            | 11        | 5.24%   |
| Intel Core 2 Duo       | 6         | 2.86%   |
| Intel Celeron          | 6         | 2.86%   |
| AMD Ryzen 9            | 6         | 2.86%   |
| Intel Xeon             | 4         | 1.9%    |
| Intel Core i9          | 4         | 1.9%    |
| AMD Phenom II X4       | 4         | 1.9%    |
| AMD E                  | 3         | 1.43%   |
| Intel Pentium 4        | 2         | 0.95%   |
| Intel Core 2 Quad      | 2         | 0.95%   |
| AMD Ryzen 3            | 2         | 0.95%   |
| AMD FX                 | 2         | 0.95%   |
| AMD Athlon II X2       | 2         | 0.95%   |
| AMD A4                 | 2         | 0.95%   |
| Intel Pentium Dual     | 1         | 0.48%   |
| Intel Pentium D        | 1         | 0.48%   |
| Intel Pentium          | 1         | 0.48%   |
| Intel Genuine          | 1         | 0.48%   |
| Intel Core 2           | 1         | 0.48%   |
| AMD Ryzen Threadripper | 1         | 0.48%   |
| AMD Ryzen 3 PRO        | 1         | 0.48%   |
| AMD E2                 | 1         | 0.48%   |
| AMD E1                 | 1         | 0.48%   |
| AMD Athlon X4          | 1         | 0.48%   |
| AMD Athlon Dual Core   | 1         | 0.48%   |
| AMD Athlon 64 X2       | 1         | 0.48%   |
| AMD A8                 | 1         | 0.48%   |
| AMD A6                 | 1         | 0.48%   |
| AMD A10                | 1         | 0.48%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 85        | 40.48%  |
| 2      | 70        | 33.33%  |
| 6      | 23        | 10.95%  |
| 8      | 16        | 7.62%   |
| 10     | 5         | 2.38%   |
| 12     | 4         | 1.9%    |
| 16     | 3         | 1.43%   |
| 1      | 3         | 1.43%   |
| 32     | 1         | 0.48%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 209       | 99.52%  |
| 2      | 1         | 0.48%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 140       | 66.67%  |
| 1      | 70        | 33.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 209       | 99.52%  |
| 32-bit         | 1         | 0.48%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 43        | 20.28%  |
| 0x306c3    | 14        | 6.6%    |
| 0x206a7    | 14        | 6.6%    |
| 0x306a9    | 13        | 6.13%   |
| 0x906ea    | 8         | 3.77%   |
| 0x506e3    | 5         | 2.36%   |
| 0x306d4    | 5         | 2.36%   |
| 0x08600104 | 5         | 2.36%   |
| 0x806ea    | 4         | 1.89%   |
| 0x806c1    | 4         | 1.89%   |
| 0x0a50000c | 4         | 1.89%   |
| 0x08701021 | 4         | 1.89%   |
| 0xa0652    | 3         | 1.42%   |
| 0x906e9    | 3         | 1.42%   |
| 0x706e5    | 3         | 1.42%   |
| 0x406e3    | 3         | 1.42%   |
| 0x40651    | 3         | 1.42%   |
| 0x106e5    | 3         | 1.42%   |
| 0x10676    | 3         | 1.42%   |
| 0x0a50000d | 3         | 1.42%   |
| 0x08600106 | 3         | 1.42%   |
| 0x08108109 | 3         | 1.42%   |
| 0x010000c8 | 3         | 1.42%   |
| 0xf41      | 2         | 0.94%   |
| 0xa0655    | 2         | 0.94%   |
| 0x906ed    | 2         | 0.94%   |
| 0x6fd      | 2         | 0.94%   |
| 0x206d7    | 2         | 0.94%   |
| 0x106a5    | 2         | 0.94%   |
| 0x07030105 | 2         | 0.94%   |
| 0x010000b6 | 2         | 0.94%   |
| 0xf65      | 1         | 0.47%   |
| 0x906ec    | 1         | 0.47%   |
| 0x906a4    | 1         | 0.47%   |
| 0x906a3    | 1         | 0.47%   |
| 0x90675    | 1         | 0.47%   |
| 0x806e9    | 1         | 0.47%   |
| 0x706a1    | 1         | 0.47%   |
| 0x6fb      | 1         | 0.47%   |
| 0x6f6      | 1         | 0.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 27        | 12.86%  |
| Haswell          | 20        | 9.52%   |
| SandyBridge      | 18        | 8.57%   |
| Zen 2            | 17        | 8.1%    |
| Skylake          | 16        | 7.62%   |
| IvyBridge        | 15        | 7.14%   |
| Zen 3            | 9         | 4.29%   |
| Penryn           | 7         | 3.33%   |
| Nehalem          | 6         | 2.86%   |
| K10              | 6         | 2.86%   |
| Broadwell        | 6         | 2.86%   |
| Alderlake Hybrid | 6         | 2.86%   |
| Westmere         | 5         | 2.38%   |
| TigerLake        | 5         | 2.38%   |
| Core             | 5         | 2.38%   |
| CometLake        | 5         | 2.38%   |
| Zen+             | 4         | 1.9%    |
| Puma             | 4         | 1.9%    |
| IceLake          | 4         | 1.9%    |
| Piledriver       | 3         | 1.43%   |
| NetBurst         | 3         | 1.43%   |
| Excavator        | 3         | 1.43%   |
| Unknown          | 3         | 1.43%   |
| Zen              | 2         | 0.95%   |
| K8 Hammer        | 2         | 0.95%   |
| Goldmont plus    | 2         | 0.95%   |
| Goldmont         | 2         | 0.95%   |
| Bobcat           | 2         | 0.95%   |
| Steamroller      | 1         | 0.48%   |
| Silvermont       | 1         | 0.48%   |
| K10 Llano        | 1         | 0.48%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 111       | 44.94%  |
| Nvidia | 77        | 31.17%  |
| AMD    | 59        | 23.89%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 10        | 3.94%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 9         | 3.54%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 8         | 3.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 7         | 2.76%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 6         | 2.36%   |
| Intel HD Graphics 530                                                       | 6         | 2.36%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 6         | 2.36%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 5         | 1.97%   |
| Intel HD Graphics 5500                                                      | 5         | 1.97%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5         | 1.97%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 5         | 1.97%   |
| Intel UHD Graphics 620                                                      | 4         | 1.57%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 4         | 1.57%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 4         | 1.57%   |
| Intel HD Graphics 630                                                       | 4         | 1.57%   |
| Intel Core Processor Integrated Graphics Controller                         | 4         | 1.57%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 4         | 1.57%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4         | 1.57%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3         | 1.18%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3         | 1.18%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3         | 1.18%   |
| Intel Iris Plus Graphics G7                                                 | 3         | 1.18%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 3         | 1.18%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 3         | 1.18%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 3         | 1.18%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 2         | 0.79%   |
| Nvidia GT218 [GeForce 210]                                                  | 2         | 0.79%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 2         | 0.79%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2         | 0.79%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 2         | 0.79%   |
| Nvidia GK208BM [GeForce 920M]                                               | 2         | 0.79%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2         | 0.79%   |
| Nvidia GF108M [GeForce GT 525M]                                             | 2         | 0.79%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 2         | 0.79%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 2         | 0.79%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2         | 0.79%   |
| Intel HD Graphics 500                                                       | 2         | 0.79%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 2         | 0.79%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2         | 0.79%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                   | 2         | 0.79%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 78        | 37.14%  |
| 1 x AMD        | 46        | 21.9%   |
| 1 x Nvidia     | 45        | 21.43%  |
| Intel + Nvidia | 25        | 11.9%   |
| AMD + Nvidia   | 6         | 2.86%   |
| 2 x AMD        | 4         | 1.9%    |
| Intel + AMD    | 3         | 1.43%   |
| Other          | 1         | 0.48%   |
| 2 x Nvidia     | 1         | 0.48%   |
| 2 x Intel      | 1         | 0.48%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 172       | 81.52%  |
| Proprietary | 37        | 17.54%  |
| Unknown     | 2         | 0.95%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 92        | 43.6%   |
| 0.01-0.5   | 30        | 14.22%  |
| 1.01-2.0   | 27        | 12.8%   |
| 0.51-1.0   | 24        | 11.37%  |
| 3.01-4.0   | 15        | 7.11%   |
| 7.01-8.0   | 8         | 3.79%   |
| 5.01-6.0   | 7         | 3.32%   |
| 8.01-16.0  | 6         | 2.84%   |
| 2.01-3.0   | 1         | 0.47%   |
| 16.01-24.0 | 1         | 0.47%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 32        | 13.62%  |
| AU Optronics            | 23        | 9.79%   |
| LG Display              | 21        | 8.94%   |
| Goldstar                | 18        | 7.66%   |
| BOE                     | 17        | 7.23%   |
| Dell                    | 13        | 5.53%   |
| Chimei Innolux          | 13        | 5.53%   |
| Hewlett-Packard         | 12        | 5.11%   |
| Philips                 | 11        | 4.68%   |
| Acer                    | 11        | 4.68%   |
| Ancor Communications    | 8         | 3.4%    |
| Apple                   | 6         | 2.55%   |
| Lenovo                  | 4         | 1.7%    |
| Sharp                   | 3         | 1.28%   |
| BenQ                    | 3         | 1.28%   |
| ASUSTek Computer        | 3         | 1.28%   |
| AOC                     | 3         | 1.28%   |
| ONN                     | 2         | 0.85%   |
| Iiyama                  | 2         | 0.85%   |
| Hannspree               | 2         | 0.85%   |
| Fujitsu Siemens         | 2         | 0.85%   |
| Eizo                    | 2         | 0.85%   |
| Chi Mei Optoelectronics | 2         | 0.85%   |
| ViewSonic               | 1         | 0.43%   |
| VIE                     | 1         | 0.43%   |
| Unknown                 | 1         | 0.43%   |
| UGD                     | 1         | 0.43%   |
| TVT                     | 1         | 0.43%   |
| TCH                     | 1         | 0.43%   |
| Targa Visionary         | 1         | 0.43%   |
| Sony                    | 1         | 0.43%   |
| Seiki                   | 1         | 0.43%   |
| Onkyo                   | 1         | 0.43%   |
| NEC Computers           | 1         | 0.43%   |
| MSI                     | 1         | 0.43%   |
| Medion                  | 1         | 0.43%   |
| LG Philips              | 1         | 0.43%   |
| KTC                     | 1         | 0.43%   |
| HKC                     | 1         | 0.43%   |
| Hitachi                 | 1         | 0.43%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 2         | 0.81%   |
| ONN ONA18HO015 ONN0101 1920x1080 698x393mm 31.5-inch                  | 2         | 0.81%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch          | 2         | 0.81%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 0.81%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 2         | 0.81%   |
| Hannspree HF207 HSG18C5 1600x900 443x249mm 20.0-inch                  | 2         | 0.81%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2         | 0.81%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 2         | 0.81%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 2         | 0.81%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch       | 2         | 0.81%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                 | 2         | 0.81%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.81%   |
| AU Optronics LCD Monitor AUO229E 1920x1080 309x174mm 14.0-inch        | 2         | 0.81%   |
| Apple iMac APPAE11 3840x2160 597x336mm 27.0-inch                      | 2         | 0.81%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 2         | 0.81%   |
| ViewSonic VA2432-FHD VSCB639 1920x1080 527x296mm 23.8-inch            | 1         | 0.4%    |
| VIE LED MONITOR VIE2302 1920x1080 473x296mm 22.0-inch                 | 1         | 0.4%    |
| Unknown LCD Monitor SAMSUNG 5760x2160                                 | 1         | 0.4%    |
| UGD Artist 12 pro UGD1102 1920x1080 256x144mm 11.6-inch               | 1         | 0.4%    |
| TVT T910 TVT005E 1280x1024 376x301mm 19.0-inch                        | 1         | 0.4%    |
| TCH HDMI TCH5600 1920x1080 344x194mm 15.5-inch                        | 1         | 0.4%    |
| Targa Visionary LCD 24-1 Wide TARA240 1920x1080 521x293mm 23.5-inch   | 1         | 0.4%    |
| Sony TV *00 SNY8004 3840x2160 1218x685mm 55.0-inch                    | 1         | 0.4%    |
| Sharp LQ150P1JX51 SHP14B4 2496x1664 317x211mm 15.0-inch               | 1         | 0.4%    |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch               | 1         | 0.4%    |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.4%    |
| Seiki SE19HE01 SEK078A 1366x768 410x230mm 18.5-inch                   | 1         | 0.4%    |
| Samsung Electronics U32J59x SAM0F35 3840x2160 700x390mm 31.5-inch     | 1         | 0.4%    |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch     | 1         | 0.4%    |
| Samsung Electronics SyncMaster SAM059A 1920x1080 477x268mm 21.5-inch  | 1         | 0.4%    |
| Samsung Electronics SyncMaster SAM0484 1920x1080 520x320mm 24.0-inch  | 1         | 0.4%    |
| Samsung Electronics SyncMaster SAM0467 1920x1200 518x324mm 24.1-inch  | 1         | 0.4%    |
| Samsung Electronics SyncMaster SAM03E0 1440x900 410x257mm 19.1-inch   | 1         | 0.4%    |
| Samsung Electronics SyncMaster SAM02F3 1680x1050 474x296mm 22.0-inch  | 1         | 0.4%    |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch  | 1         | 0.4%    |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x257mm 19.1-inch   | 1         | 0.4%    |
| Samsung Electronics SyncMaster SAM01AB 1280x1024 312x234mm 15.4-inch  | 1         | 0.4%    |
| Samsung Electronics SyncMaster SAM010B 1280x1024 338x270mm 17.0-inch  | 1         | 0.4%    |
| Samsung Electronics SMS27A350H SAM07CE 1920x1080 598x336mm 27.0-inch  | 1         | 0.4%    |
| Samsung Electronics SMB2330HD SAM0710 1920x1080 510x290mm 23.1-inch   | 1         | 0.4%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 109       | 49.32%  |
| 1366x768 (WXGA)    | 33        | 14.93%  |
| 3840x2160 (4K)     | 20        | 9.05%   |
| 1280x1024 (SXGA)   | 11        | 4.98%   |
| 1680x1050 (WSXGA+) | 10        | 4.52%   |
| 1600x900 (HD+)     | 7         | 3.17%   |
| 1920x1200 (WUXGA)  | 6         | 2.71%   |
| 2560x1440 (QHD)    | 5         | 2.26%   |
| 1440x900 (WXGA+)   | 4         | 1.81%   |
| 1280x800 (WXGA)    | 3         | 1.36%   |
| 3440x1440          | 2         | 0.9%    |
| 1360x768           | 2         | 0.9%    |
| Unknown            | 2         | 0.9%    |
| 5760x2160          | 1         | 0.45%   |
| 3280x1080          | 1         | 0.45%   |
| 2880x1800          | 1         | 0.45%   |
| 2496x1664          | 1         | 0.45%   |
| 2160x1440          | 1         | 0.45%   |
| 1600x1200          | 1         | 0.45%   |
| 1400x1050          | 1         | 0.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 60        | 25.53%  |
| 27      | 21        | 8.94%   |
| 21      | 21        | 8.94%   |
| 24      | 19        | 8.09%   |
| 23      | 19        | 8.09%   |
| 17      | 15        | 6.38%   |
| 13      | 15        | 6.38%   |
| 14      | 10        | 4.26%   |
| 19      | 9         | 3.83%   |
| 22      | 8         | 3.4%    |
| 31      | 6         | 2.55%   |
| 18      | 6         | 2.55%   |
| 12      | 5         | 2.13%   |
| 20      | 4         | 1.7%    |
| 84      | 3         | 1.28%   |
| Unknown | 3         | 1.28%   |
| 65      | 1         | 0.43%   |
| 54      | 1         | 0.43%   |
| 52      | 1         | 0.43%   |
| 50      | 1         | 0.43%   |
| 43      | 1         | 0.43%   |
| 40      | 1         | 0.43%   |
| 34      | 1         | 0.43%   |
| 32      | 1         | 0.43%   |
| 26      | 1         | 0.43%   |
| 16      | 1         | 0.43%   |
| 11      | 1         | 0.43%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 81        | 35.37%  |
| 501-600     | 54        | 23.58%  |
| 401-500     | 42        | 18.34%  |
| 351-400     | 16        | 6.99%   |
| 201-300     | 14        | 6.11%   |
| 601-700     | 8         | 3.49%   |
| 1001-1500   | 4         | 1.75%   |
| 1501-2000   | 3         | 1.31%   |
| Unknown     | 3         | 1.31%   |
| 701-800     | 2         | 0.87%   |
| 801-900     | 1         | 0.44%   |
| 901-1000    | 1         | 0.44%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 163       | 76.89%  |
| 16/10   | 30        | 14.15%  |
| 5/4     | 10        | 4.72%   |
| 3/2     | 3         | 1.42%   |
| Unknown | 3         | 1.42%   |
| 4/3     | 2         | 0.94%   |
| 21/9    | 1         | 0.47%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 60        | 26.09%  |
| 201-250        | 52        | 22.61%  |
| 301-350        | 22        | 9.57%   |
| 81-90          | 19        | 8.26%   |
| 151-200        | 15        | 6.52%   |
| 141-150        | 13        | 5.65%   |
| 351-500        | 8         | 3.48%   |
| 251-300        | 8         | 3.48%   |
| More than 1000 | 7         | 3.04%   |
| 121-130        | 7         | 3.04%   |
| 71-80          | 6         | 2.61%   |
| 61-70          | 5         | 2.17%   |
| Unknown        | 3         | 1.3%    |
| 501-1000       | 2         | 0.87%   |
| 51-60          | 1         | 0.43%   |
| 131-140        | 1         | 0.43%   |
| 111-120        | 1         | 0.43%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 88        | 39.46%  |
| 101-120       | 56        | 25.11%  |
| 121-160       | 55        | 24.66%  |
| 161-240       | 17        | 7.62%   |
| Unknown       | 3         | 1.35%   |
| More than 240 | 2         | 0.9%    |
| 1-50          | 2         | 0.9%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 166       | 78.3%   |
| 2     | 43        | 20.28%  |
| 3     | 2         | 0.94%   |
| 0     | 1         | 0.47%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 116       | 36.02%  |
| Realtek Semiconductor             | 113       | 35.09%  |
| Qualcomm Atheros                  | 31        | 9.63%   |
| Broadcom                          | 16        | 4.97%   |
| MediaTek                          | 7         | 2.17%   |
| ASIX Electronics                  | 4         | 1.24%   |
| TP-Link                           | 3         | 0.93%   |
| Ralink                            | 3         | 0.93%   |
| Nvidia                            | 3         | 0.93%   |
| Broadcom Limited                  | 3         | 0.93%   |
| Ralink Technology                 | 2         | 0.62%   |
| Marvell Technology Group          | 2         | 0.62%   |
| Ericsson Business Mobile Networks | 2         | 0.62%   |
| DisplayLink                       | 2         | 0.62%   |
| Aquantia                          | 2         | 0.62%   |
| ZyDAS                             | 1         | 0.31%   |
| Xiaomi                            | 1         | 0.31%   |
| Wacom                             | 1         | 0.31%   |
| Qualcomm Atheros Communications   | 1         | 0.31%   |
| NetGear                           | 1         | 0.31%   |
| Motorola PCS                      | 1         | 0.31%   |
| Microsoft                         | 1         | 0.31%   |
| InterBiometrics                   | 1         | 0.31%   |
| Input Club                        | 1         | 0.31%   |
| ICS Advent                        | 1         | 0.31%   |
| Huawei Technologies               | 1         | 0.31%   |
| Hewlett-Packard                   | 1         | 0.31%   |
| Dell                              | 1         | 0.31%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 80        | 20.94%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 18        | 4.71%   |
| Intel Wireless 7265                                                           | 10        | 2.62%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 9         | 2.36%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 8         | 2.09%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 7         | 1.83%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 6         | 1.57%   |
| Intel Wireless 8265 / 8275                                                    | 6         | 1.57%   |
| Intel I211 Gigabit Network Connection                                         | 6         | 1.57%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 6         | 1.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 5         | 1.31%   |
| Intel Wireless 8260                                                           | 5         | 1.31%   |
| Intel Wi-Fi 6 AX201                                                           | 5         | 1.31%   |
| Intel Wi-Fi 6 AX200                                                           | 5         | 1.31%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                       | 5         | 1.31%   |
| Intel Ethernet Connection I217-LM                                             | 5         | 1.31%   |
| Realtek 802.11ac NIC                                                          | 4         | 1.05%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 4         | 1.05%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                       | 4         | 1.05%   |
| Intel Wireless 7260                                                           | 4         | 1.05%   |
| Intel Ethernet Controller I225-V                                              | 4         | 1.05%   |
| Intel Ethernet Connection (2) I219-V                                          | 4         | 1.05%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 3         | 0.79%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 3         | 0.79%   |
| Intel WiFi Link 5100                                                          | 3         | 0.79%   |
| Intel Ethernet Connection I217-V                                              | 3         | 0.79%   |
| Intel Centrino Ultimate-N 6300                                                | 3         | 0.79%   |
| Intel Alder Lake-P PCH CNVi WiFi                                              | 3         | 0.79%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                   | 3         | 0.79%   |
| Broadcom BCM4331 802.11a/b/g/n                                                | 3         | 0.79%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 3         | 0.79%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 2         | 0.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 2         | 0.52%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 2         | 0.52%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 2         | 0.52%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 2         | 0.52%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2         | 0.52%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 2         | 0.52%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 2         | 0.52%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 2         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 80        | 49.69%  |
| Realtek Semiconductor           | 27        | 16.77%  |
| Qualcomm Atheros                | 24        | 14.91%  |
| Broadcom                        | 10        | 6.21%   |
| MediaTek                        | 6         | 3.73%   |
| TP-Link                         | 3         | 1.86%   |
| Ralink                          | 3         | 1.86%   |
| Ralink Technology               | 2         | 1.24%   |
| ZyDAS                           | 1         | 0.62%   |
| Wacom                           | 1         | 0.62%   |
| Qualcomm Atheros Communications | 1         | 0.62%   |
| NetGear                         | 1         | 0.62%   |
| Microsoft                       | 1         | 0.62%   |
| Broadcom Limited                | 1         | 0.62%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                                           | 10        | 6.17%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 7         | 4.32%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 6         | 3.7%    |
| Intel Wireless 8265 / 8275                                                    | 6         | 3.7%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 6         | 3.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 5         | 3.09%   |
| Intel Wireless 8260                                                           | 5         | 3.09%   |
| Intel Wi-Fi 6 AX201                                                           | 5         | 3.09%   |
| Intel Wi-Fi 6 AX200                                                           | 5         | 3.09%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                       | 5         | 3.09%   |
| Realtek 802.11ac NIC                                                          | 4         | 2.47%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 4         | 2.47%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                       | 4         | 2.47%   |
| Intel Wireless 7260                                                           | 4         | 2.47%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 3         | 1.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 3         | 1.85%   |
| Intel WiFi Link 5100                                                          | 3         | 1.85%   |
| Intel Centrino Ultimate-N 6300                                                | 3         | 1.85%   |
| Intel Alder Lake-P PCH CNVi WiFi                                              | 3         | 1.85%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                   | 3         | 1.85%   |
| Broadcom BCM4331 802.11a/b/g/n                                                | 3         | 1.85%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 2         | 1.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 2         | 1.23%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 2         | 1.23%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 2         | 1.23%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2         | 1.23%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 2         | 1.23%   |
| Intel Wireless 3160                                                           | 2         | 1.23%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                     | 2         | 1.23%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                               | 2         | 1.23%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 2         | 1.23%   |
| Broadcom BCM43142 802.11b/g/n                                                 | 2         | 1.23%   |
| ZyDAS ZD1211B 802.11g                                                         | 1         | 0.62%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                                      | 1         | 0.62%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 1         | 0.62%   |
| TP-Link 802.11ac WLAN Adapter                                                 | 1         | 0.62%   |
| TP-Link 802.11ac NIC                                                          | 1         | 0.62%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                   | 1         | 0.62%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1         | 0.62%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 1         | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 98        | 47.12%  |
| Intel                    | 72        | 34.62%  |
| Broadcom                 | 10        | 4.81%   |
| Qualcomm Atheros         | 9         | 4.33%   |
| ASIX Electronics         | 4         | 1.92%   |
| Nvidia                   | 3         | 1.44%   |
| Marvell Technology Group | 2         | 0.96%   |
| DisplayLink              | 2         | 0.96%   |
| Broadcom Limited         | 2         | 0.96%   |
| Aquantia                 | 2         | 0.96%   |
| Xiaomi                   | 1         | 0.48%   |
| MediaTek                 | 1         | 0.48%   |
| ICS Advent               | 1         | 0.48%   |
| Hewlett-Packard          | 1         | 0.48%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 80        | 37.56%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 18        | 8.45%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 9         | 4.23%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 8         | 3.76%   |
| Intel I211 Gigabit Network Connection                                          | 6         | 2.82%   |
| Intel Ethernet Connection I217-LM                                              | 5         | 2.35%   |
| Intel Ethernet Controller I225-V                                               | 4         | 1.88%   |
| Intel Ethernet Connection (2) I219-V                                           | 4         | 1.88%   |
| Intel Ethernet Connection I217-V                                               | 3         | 1.41%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 3         | 1.41%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 2         | 0.94%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 2         | 0.94%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 2         | 0.94%   |
| Nvidia MCP77 Ethernet                                                          | 2         | 0.94%   |
| Intel Ethernet Connection I219-V                                               | 2         | 0.94%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 0.94%   |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 0.94%   |
| Intel Ethernet Connection (7) I219-LM                                          | 2         | 0.94%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2         | 0.94%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 0.94%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 0.94%   |
| Intel 82574L Gigabit Network Connection                                        | 2         | 0.94%   |
| Intel 82567LM Gigabit Network Connection                                       | 2         | 0.94%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                              | 2         | 0.94%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 2         | 0.94%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 2         | 0.94%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.47%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1         | 0.47%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.47%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 1         | 0.47%   |
| Realtek Killer E2600 GbE Controller                                            | 1         | 0.47%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.47%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.47%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.47%   |
| Nvidia MCP61 Ethernet                                                          | 1         | 0.47%   |
| MediaTek RMX3085                                                               | 1         | 0.47%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 0.47%   |
| Marvell Group 88E8052 PCI-E ASF Gigabit Ethernet Controller                    | 1         | 0.47%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                              | 1         | 0.47%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 0.47%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 189       | 53.54%  |
| WiFi     | 157       | 44.48%  |
| Modem    | 6         | 1.7%    |
| Unknown  | 1         | 0.28%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 115       | 50.22%  |
| Ethernet | 114       | 49.78%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 119       | 56.67%  |
| 1     | 84        | 40%     |
| 3     | 5         | 2.38%   |
| 0     | 2         | 0.95%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 160       | 75.47%  |
| Yes  | 52        | 24.53%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 62        | 50.41%  |
| Realtek Semiconductor           | 9         | 7.32%   |
| Qualcomm Atheros Communications | 9         | 7.32%   |
| Cambridge Silicon Radio         | 7         | 5.69%   |
| Apple                           | 7         | 5.69%   |
| Broadcom                        | 6         | 4.88%   |
| MediaTek                        | 4         | 3.25%   |
| ASUSTek Computer                | 4         | 3.25%   |
| IMC Networks                    | 3         | 2.44%   |
| Realtek                         | 2         | 1.63%   |
| Ralink Technology               | 2         | 1.63%   |
| Lite-On Technology              | 2         | 1.63%   |
| Hewlett-Packard                 | 2         | 1.63%   |
| Dell                            | 2         | 1.63%   |
| Ralink                          | 1         | 0.81%   |
| Foxconn International           | 1         | 0.81%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 18        | 14.63%  |
| Intel Bluetooth Device                              | 9         | 7.32%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 9         | 7.32%   |
| Intel AX201 Bluetooth                               | 9         | 7.32%   |
| Realtek Bluetooth Radio                             | 7         | 5.69%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7         | 5.69%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 5         | 4.07%   |
| Intel AX200 Bluetooth                               | 5         | 4.07%   |
| MediaTek Wireless_Device                            | 4         | 3.25%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 4         | 3.25%   |
| Apple Bluetooth USB Host Controller                 | 4         | 3.25%   |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 2.44%   |
| Intel AX211 Bluetooth                               | 3         | 2.44%   |
| Realtek Bluetooth Radio                             | 2         | 1.63%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 1.63%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 1.63%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 1.63%   |
| Intel AX210 Bluetooth                               | 2         | 1.63%   |
| IMC Networks Bluetooth Radio                        | 2         | 1.63%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2         | 1.63%   |
| Apple Bluetooth Host Controller                     | 2         | 1.63%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.81%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 0.81%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.81%   |
| Ralink CSR BS8510                                   | 1         | 0.81%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.81%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.81%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.81%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.81%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.81%   |
| IMC Networks Wireless_Device                        | 1         | 0.81%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 0.81%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.81%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.81%   |
| Dell Wireless 370 Bluetooth Mini-card               | 1         | 0.81%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.81%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 0.81%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 0.81%   |
| ASUS BT-270 Bluetooth Adapter                       | 1         | 0.81%   |
| ASUS BCM20702A0                                     | 1         | 0.81%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 148       | 42.41%  |
| AMD                                  | 66        | 18.91%  |
| Nvidia                               | 63        | 18.05%  |
| C-Media Electronics                  | 7         | 2.01%   |
| Texas Instruments                    | 5         | 1.43%   |
| Yamaha                               | 4         | 1.15%   |
| M-Audio                              | 4         | 1.15%   |
| Logitech                             | 3         | 0.86%   |
| JMTek                                | 3         | 0.86%   |
| Focusrite-Novation                   | 3         | 0.86%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.57%   |
| QinHeng Electronics                  | 2         | 0.57%   |
| PreSonus Audio Electronics           | 2         | 0.57%   |
| Mackie Designs                       | 2         | 0.57%   |
| Generalplus Technology               | 2         | 0.57%   |
| Creative Technology                  | 2         | 0.57%   |
| BEHRINGER International              | 2         | 0.57%   |
| ASUSTek Computer                     | 2         | 0.57%   |
| ZOOM                                 | 1         | 0.29%   |
| Yealink Network Technology           | 1         | 0.29%   |
| Xilinx                               | 1         | 0.29%   |
| Textech International                | 1         | 0.29%   |
| Tenx Technology                      | 1         | 0.29%   |
| TEAC                                 | 1         | 0.29%   |
| Studiologic                          | 1         | 0.29%   |
| SteelSeries ApS                      | 1         | 0.29%   |
| Samson Technologies                  | 1         | 0.29%   |
| Realtek Semiconductor                | 1         | 0.29%   |
| Plantronics                          | 1         | 0.29%   |
| MIDITECH                             | 1         | 0.29%   |
| Medeli Electronics                   | 1         | 0.29%   |
| Mark of the Unicorn                  | 1         | 0.29%   |
| Lenovo                               | 1         | 0.29%   |
| KTMicro                              | 1         | 0.29%   |
| Harman                               | 1         | 0.29%   |
| Focusrite                            | 1         | 0.29%   |
| Evolution Electronics                | 1         | 0.29%   |
| Ensoniq                              | 1         | 0.29%   |
| Dell                                 | 1         | 0.29%   |
| BR25                                 | 1         | 0.29%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                            | 22        | 5.38%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 16        | 3.91%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 15        | 3.67%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 14        | 3.42%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 14        | 3.42%   |
| Intel Cannon Lake PCH cAVS                                                        | 12        | 2.93%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 11        | 2.69%   |
| Intel Sunrise Point-LP HD Audio                                                   | 11        | 2.69%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 9         | 2.2%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 9         | 2.2%    |
| AMD Starship/Matisse HD Audio Controller                                          | 9         | 2.2%    |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 8         | 1.96%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 8         | 1.96%   |
| AMD FCH Azalia Controller                                                         | 8         | 1.96%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 6         | 1.47%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 6         | 1.47%   |
| Intel Broadwell-U Audio Controller                                                | 6         | 1.47%   |
| Intel 200 Series PCH HD Audio                                                     | 6         | 1.47%   |
| Nvidia GF108 High Definition Audio Controller                                     | 5         | 1.22%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 5         | 1.22%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 5         | 1.22%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 5         | 1.22%   |
| AMD Kabini HDMI/DP Audio                                                          | 5         | 1.22%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 5         | 1.22%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                         | 4         | 0.98%   |
| Intel Comet Lake PCH cAVS                                                         | 4         | 0.98%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                           | 4         | 0.98%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 4         | 0.98%   |
| Texas Instruments PCM2902 Audio Codec                                             | 3         | 0.73%   |
| Nvidia TU116 High Definition Audio Controller                                     | 3         | 0.73%   |
| Nvidia GT216 HDMI Audio Controller                                                | 3         | 0.73%   |
| Nvidia GP108 High Definition Audio Controller                                     | 3         | 0.73%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 3         | 0.73%   |
| Nvidia GP106 High Definition Audio Controller                                     | 3         | 0.73%   |
| Nvidia GP104 High Definition Audio Controller                                     | 3         | 0.73%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 3         | 0.73%   |
| Nvidia GF119 HDMI Audio Controller                                                | 3         | 0.73%   |
| Nvidia GA106 High Definition Audio Controller                                     | 3         | 0.73%   |
| Nvidia GA102 High Definition Audio Controller                                     | 3         | 0.73%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 3         | 0.73%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 57        | 22.44%  |
| SK hynix            | 52        | 20.47%  |
| Kingston            | 28        | 11.02%  |
| Micron Technology   | 23        | 9.06%   |
| Unknown             | 20        | 7.87%   |
| Crucial             | 16        | 6.3%    |
| Corsair             | 13        | 5.12%   |
| G.Skill             | 10        | 3.94%   |
| Patriot             | 6         | 2.36%   |
| Ramaxel Technology  | 5         | 1.97%   |
| Nanya Technology    | 3         | 1.18%   |
| A-DATA Technology   | 3         | 1.18%   |
| Timetec             | 2         | 0.79%   |
| Elpida              | 2         | 0.79%   |
| Wodposit            | 1         | 0.39%   |
| Unifosa             | 1         | 0.39%   |
| Transcend           | 1         | 0.39%   |
| Smart               | 1         | 0.39%   |
| S                   | 1         | 0.39%   |
| PNY                 | 1         | 0.39%   |
| OCZ                 | 1         | 0.39%   |
| M                   | 1         | 0.39%   |
| HBS                 | 1         | 0.39%   |
| Goldkey             | 1         | 0.39%   |
| Avant               | 1         | 0.39%   |
| Aeneon              | 1         | 0.39%   |
| 0194808980CE        | 1         | 0.39%   |
| Unknown             | 1         | 0.39%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 4         | 1.43%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s      | 4         | 1.43%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 3         | 1.08%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 3         | 1.08%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s    | 3         | 1.08%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s     | 3         | 1.08%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 3         | 1.08%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s       | 3         | 1.08%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3600MT/s        | 3         | 1.08%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s      | 3         | 1.08%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                   | 2         | 0.72%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                  | 2         | 0.72%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s              | 2         | 0.72%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s      | 2         | 0.72%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 2         | 0.72%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s    | 2         | 0.72%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s    | 2         | 0.72%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s               | 2         | 0.72%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s     | 2         | 0.72%   |
| Samsung RAM M471B5273DH0-CK0 4096MB SODIMM DDR3 1600MT/s  | 2         | 0.72%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s     | 2         | 0.72%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s     | 2         | 0.72%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s    | 2         | 0.72%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s       | 2         | 0.72%   |
| Patriot RAM 2400 C15 Series 16GB SODIMM DDR4 2667MT/s     | 2         | 0.72%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s       | 2         | 0.72%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s     | 2         | 0.72%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3400MT/s    | 2         | 0.72%   |
| Wodposit RAM WPBH26D408SWA-8G 8192MB SODIMM DDR4 2667MT/s | 1         | 0.36%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s            | 1         | 0.36%   |
| Unknown RAM Module 512MB DIMM DDR 533MT/s                 | 1         | 0.36%   |
| Unknown RAM Module 512MB DIMM DDR                         | 1         | 0.36%   |
| Unknown RAM Module 4GB DIMM SDRAM                         | 1         | 0.36%   |
| Unknown RAM Module 4GB DIMM DDR2 667MT/s                  | 1         | 0.36%   |
| Unknown RAM Module 4GB DIMM 400MT/s                       | 1         | 0.36%   |
| Unknown RAM Module 4096MB SODIMM LPDDR3 1600MT/s          | 1         | 0.36%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                   | 1         | 0.36%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                  | 1         | 0.36%   |
| Unknown RAM Module 2GB DIMM DDR2                          | 1         | 0.36%   |
| Unknown RAM Module 256MB DIMM DDR                         | 1         | 0.36%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 89        | 41.59%  |
| DDR3    | 89        | 41.59%  |
| DDR2    | 14        | 6.54%   |
| SDRAM   | 6         | 2.8%    |
| Unknown | 6         | 2.8%    |
| LPDDR4  | 3         | 1.4%    |
| DDR     | 3         | 1.4%    |
| LPDDR3  | 2         | 0.93%   |
| LPDDR5  | 1         | 0.47%   |
| DDR5    | 1         | 0.47%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 112       | 52.83%  |
| DIMM         | 84        | 39.62%  |
| Row Of Chips | 11        | 5.19%   |
| Unknown      | 2         | 0.94%   |
| RIMM         | 1         | 0.47%   |
| FB-DIMM      | 1         | 0.47%   |
| Chip         | 1         | 0.47%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 82        | 33.61%  |
| 4096  | 75        | 30.74%  |
| 16384 | 29        | 11.89%  |
| 2048  | 29        | 11.89%  |
| 32768 | 15        | 6.15%   |
| 1024  | 11        | 4.51%   |
| 512   | 2         | 0.82%   |
| 256   | 1         | 0.41%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 63        | 27.04%  |
| 3200    | 27        | 11.59%  |
| 2667    | 22        | 9.44%   |
| 1333    | 15        | 6.44%   |
| 2400    | 14        | 6.01%   |
| 2133    | 11        | 4.72%   |
| 3600    | 10        | 4.29%   |
| 1334    | 10        | 4.29%   |
| 667     | 8         | 3.43%   |
| 1866    | 5         | 2.15%   |
| 800     | 5         | 2.15%   |
| Unknown | 5         | 2.15%   |
| 1800    | 4         | 1.72%   |
| 1066    | 4         | 1.72%   |
| 4267    | 3         | 1.29%   |
| 4199    | 2         | 0.86%   |
| 3400    | 2         | 0.86%   |
| 3266    | 2         | 0.86%   |
| 2933    | 2         | 0.86%   |
| 1867    | 2         | 0.86%   |
| 1067    | 2         | 0.86%   |
| 533     | 2         | 0.86%   |
| 6400    | 1         | 0.43%   |
| 4802    | 1         | 0.43%   |
| 3866    | 1         | 0.43%   |
| 3500    | 1         | 0.43%   |
| 3466    | 1         | 0.43%   |
| 3000    | 1         | 0.43%   |
| 2934    | 1         | 0.43%   |
| 2800    | 1         | 0.43%   |
| 2666    | 1         | 0.43%   |
| 2472    | 1         | 0.43%   |
| 1639    | 1         | 0.43%   |
| 1632    | 1         | 0.43%   |
| 400     | 1         | 0.43%   |

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
| Chicony Electronics                    | 24        | 19.2%   |
| Realtek Semiconductor                  | 9         | 7.2%    |
| IMC Networks                           | 9         | 7.2%    |
| Logitech                               | 8         | 6.4%    |
| Microdia                               | 7         | 5.6%    |
| Suyin                                  | 6         | 4.8%    |
| Sunplus Innovation Technology          | 6         | 4.8%    |
| Bison Electronics                      | 6         | 4.8%    |
| Syntek                                 | 5         | 4%      |
| Quanta                                 | 5         | 4%      |
| Apple                                  | 5         | 4%      |
| Lite-On Technology                     | 3         | 2.4%    |
| Cheng Uei Precision Industry (Foxlink) | 3         | 2.4%    |
| Xiongmai                               | 2         | 1.6%    |
| Sonix Technology                       | 2         | 1.6%    |
| Samsung Electronics                    | 2         | 1.6%    |
| Philips (or NXP)                       | 2         | 1.6%    |
| Microsoft                              | 2         | 1.6%    |
| ViewSonic                              | 1         | 0.8%    |
| ViewQuest Technologies                 | 1         | 0.8%    |
| Trust                                  | 1         | 0.8%    |
| Sweex                                  | 1         | 0.8%    |
| Sunplus IT                             | 1         | 0.8%    |
| Silicon Motion                         | 1         | 0.8%    |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.8%    |
| SHENZHEN AONI ELECTRONIC               | 1         | 0.8%    |
| Ricoh                                  | 1         | 0.8%    |
| Razer USA                              | 1         | 0.8%    |
| MacroSilicon                           | 1         | 0.8%    |
| Luxvisions Innotech Limited            | 1         | 0.8%    |
| Jieli Technology                       | 1         | 0.8%    |
| Intel                                  | 1         | 0.8%    |
| Importek                               | 1         | 0.8%    |
| HRY                                    | 1         | 0.8%    |
| Dynex                                  | 1         | 0.8%    |
| Dell                                   | 1         | 0.8%    |
| Acer                                   | 1         | 0.8%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                         | 6         | 4.76%   |
| Syntek Integrated Camera                          | 5         | 3.97%   |
| IMC Networks Integrated Camera                    | 4         | 3.17%   |
| Realtek Lenovo EasyCamera                         | 3         | 2.38%   |
| IMC Networks USB2.0 HD UVC WebCam                 | 3         | 2.38%   |
| Chicony Integrated Camera [ThinkPad]              | 3         | 2.38%   |
| Chicony HD Webcam                                 | 3         | 2.38%   |
| Chicony HD User Facing                            | 3         | 2.38%   |
| Bison Integrated Camera                           | 3         | 2.38%   |
| Xiongmai web camera                               | 2         | 1.59%   |
| Suyin USB 2.0 Camera                              | 2         | 1.59%   |
| Suyin Asus Integrated Webcam                      | 2         | 1.59%   |
| Sunplus Integrated_Webcam_HD                      | 2         | 1.59%   |
| Sunplus HD WebCam                                 | 2         | 1.59%   |
| Sonix USB2.0 HD UVC WebCam                        | 2         | 1.59%   |
| Samsung Galaxy series, misc. (MTP mode)           | 2         | 1.59%   |
| Realtek Integrated_Webcam_HD                      | 2         | 1.59%   |
| Microdia Integrated_Webcam_HD                     | 2         | 1.59%   |
| Logitech Webcam C270                              | 2         | 1.59%   |
| Chicony HP HD Camera                              | 2         | 1.59%   |
| Apple FaceTime HD Camera (Built-in)               | 2         | 1.59%   |
| Apple FaceTime HD Camera                          | 2         | 1.59%   |
| ViewSonic PC Camera                               | 1         | 0.79%   |
| ViewQuest Ability GABB Webcam                     | 1         | 0.79%   |
| Trust AUKEY PC-LM1A Webcam                        | 1         | 0.79%   |
| Sweex WC060 Series HD Webcam                      | 1         | 0.79%   |
| Suyin HP Webcam                                   | 1         | 0.79%   |
| Suyin HP TrueVision HD Integrated Webcam          | 1         | 0.79%   |
| Sunplus IT AUKEY PC-LM1 USB Camera                | 1         | 0.79%   |
| Sunplus HD 720P webcam                            | 1         | 0.79%   |
| Sunplus Dell HD Webcam                            | 1         | 0.79%   |
| Silicon Motion WebCam SCB-1100N                   | 1         | 0.79%   |
| Shenzhen Kingcome Optoelectronic 720p HD Camera   | 1         | 0.79%   |
| SHENZHEN AONI ELECTRONIC NexiGo N930AF FHD Webcam | 1         | 0.79%   |
| Ricoh Sony Vaio Integrated Webcam                 | 1         | 0.79%   |
| Realtek VGA WebCam                                | 1         | 0.79%   |
| Realtek USB Camera                                | 1         | 0.79%   |
| Realtek HP Wide Vision HD Camera                  | 1         | 0.79%   |
| Realtek HP "Truevision HD" laptop camera          | 1         | 0.79%   |
| Razer USA Gaming Webcam [Kiyo]                    | 1         | 0.79%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 9         | 45%     |
| Shenzhen Goodix Technology | 4         | 20%     |
| Synaptics                  | 3         | 15%     |
| Samsung Electronics        | 1         | 5%      |
| LighTuning Technology      | 1         | 5%      |
| Focal-systems.Corp         | 1         | 5%      |
| AuthenTec                  | 1         | 5%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader       | 2         | 10%     |
| Validity Sensors VFS495 Fingerprint Reader        | 2         | 10%     |
| Validity Sensors VFS 5011 fingerprint sensor      | 2         | 10%     |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 2         | 10%     |
| Shenzhen Goodix  Fingerprint Device               | 2         | 10%     |
| Shenzhen Goodix Fingerprint Reader                | 2         | 10%     |
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 1         | 5%      |
| Validity Sensors VFS301 Fingerprint Reader        | 1         | 5%      |
| Validity Sensors Fingerprint scanner              | 1         | 5%      |
| Synaptics Fingerprint reader [HP G6]              | 1         | 5%      |
| Samsung Fingerprint Sensor Device - 730B          | 1         | 5%      |
| LighTuning ES603 Swipe Fingerprint Sensor         | 1         | 5%      |
| Focal-systems.Corp FT9201Fingerprint.             | 1         | 5%      |
| AuthenTec AES2501 Fingerprint Sensor              | 1         | 5%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


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

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


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

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 149       | 70.95%  |
| 1     | 53        | 25.24%  |
| 2     | 7         | 3.33%   |
| 3     | 1         | 0.48%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 20        | 30.3%   |
| Graphics card            | 12        | 18.18%  |
| Chipcard                 | 10        | 15.15%  |
| Net/wireless             | 9         | 13.64%  |
| Multimedia controller    | 4         | 6.06%   |
| Camera                   | 3         | 4.55%   |
| Sound                    | 2         | 3.03%   |
| Unassigned class         | 1         | 1.52%   |
| Storage                  | 1         | 1.52%   |
| Modem                    | 1         | 1.52%   |
| Communication controller | 1         | 1.52%   |
| Card reader              | 1         | 1.52%   |
| Bluetooth                | 1         | 1.52%   |

