Linux in Japan - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Japan.

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

Total: 624

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Hampoo        | C3W6_AP108_4GB Reserved     | [93d3e41339](https://linux-hardware.org/?probe=93d3e41339) | Oct 01, 2022 |
| Dell          | Inspiron 11-3162            | [8cd15b2f0c](https://linux-hardware.org/?probe=8cd15b2f0c) | Sep 30, 2022 |
| NEC Comput... | PC-VRL21FB6S3R7             | [2001e2e28e](https://linux-hardware.org/?probe=2001e2e28e) | Sep 30, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [d1b6a74f84](https://linux-hardware.org/?probe=d1b6a74f84) | Sep 29, 2022 |
| Toshiba       | dynabook T653/46JR          | [9a613eaf66](https://linux-hardware.org/?probe=9a613eaf66) | Sep 28, 2022 |
| Fujitsu       | FMVA1200G                   | [e91d3af852](https://linux-hardware.org/?probe=e91d3af852) | Sep 27, 2022 |
| Toshiba       | dynabook T653/46JR          | [ee93820bdf](https://linux-hardware.org/?probe=ee93820bdf) | Sep 21, 2022 |
| NEC Comput... | PC-VK26MXZCE                | [db8f5e4181](https://linux-hardware.org/?probe=db8f5e4181) | Sep 18, 2022 |
| Toshiba       | dynabook T653/46JR          | [7f9cf09305](https://linux-hardware.org/?probe=7f9cf09305) | Sep 17, 2022 |
| EPSON DIRE... | Endeavor NJ3100E            | [47cb342ecf](https://linux-hardware.org/?probe=47cb342ecf) | Sep 16, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [9497f1e17f](https://linux-hardware.org/?probe=9497f1e17f) | Sep 16, 2022 |
| System76      | Lemur Pro                   | [d6682a260a](https://linux-hardware.org/?probe=d6682a260a) | Sep 14, 2022 |
| Dell          | Latitude 7420               | [211c7ab44c](https://linux-hardware.org/?probe=211c7ab44c) | Sep 12, 2022 |
| HUAWEI        | MACHD-WXX9                  | [ba1f911067](https://linux-hardware.org/?probe=ba1f911067) | Sep 10, 2022 |
| Notebook      | NV4XMB,ME,MZ                | [0efc3cb183](https://linux-hardware.org/?probe=0efc3cb183) | Sep 07, 2022 |
| HP            | ZHAN 66 Pro A 14 G3         | [c34e343671](https://linux-hardware.org/?probe=c34e343671) | Sep 05, 2022 |
| Panasonic     | CFSV9-1                     | [c21f59dee9](https://linux-hardware.org/?probe=c21f59dee9) | Sep 04, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [a0b2975bf7](https://linux-hardware.org/?probe=a0b2975bf7) | Sep 04, 2022 |
| Toshiba       | dynabook T653/46JR          | [adfeeb4193](https://linux-hardware.org/?probe=adfeeb4193) | Sep 04, 2022 |
| Toshiba       | dynabook T653/46JR          | [b97366daa0](https://linux-hardware.org/?probe=b97366daa0) | Aug 27, 2022 |
| MSI           | GE70 0NC/GE70 0ND           | [a7c9d17455](https://linux-hardware.org/?probe=a7c9d17455) | Aug 25, 2022 |
| Acer          | Aspire 5740                 | [5652f2c73d](https://linux-hardware.org/?probe=5652f2c73d) | Aug 24, 2022 |
| Fujitsu       | FMVA42CW                    | [f50babde6a](https://linux-hardware.org/?probe=f50babde6a) | Aug 23, 2022 |
| Toshiba       | dynabook T653/46JR          | [decfecaa20](https://linux-hardware.org/?probe=decfecaa20) | Aug 18, 2022 |
| MSI           | Delta 15 A5EFK              | [4b165c8f79](https://linux-hardware.org/?probe=4b165c8f79) | Aug 17, 2022 |
| Toshiba       | dynabook T75/RW             | [ff35aa835d](https://linux-hardware.org/?probe=ff35aa835d) | Aug 15, 2022 |
| HP            | EliteBook 845 14 inch G9... | [4e05ac232c](https://linux-hardware.org/?probe=4e05ac232c) | Aug 15, 2022 |
| System76      | Oryx Pro                    | [87b38f5a99](https://linux-hardware.org/?probe=87b38f5a99) | Aug 12, 2022 |
| Dell          | XPS 15 9500                 | [d8486d3371](https://linux-hardware.org/?probe=d8486d3371) | Aug 07, 2022 |
| Toshiba       | dynabook R732/G             | [82ef8736b3](https://linux-hardware.org/?probe=82ef8736b3) | Aug 07, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [7151e1746a](https://linux-hardware.org/?probe=7151e1746a) | Aug 05, 2022 |
| Toshiba       | dynabook T653/46JR          | [ea8bb6486b](https://linux-hardware.org/?probe=ea8bb6486b) | Jul 30, 2022 |
| Toshiba       | dynabook B350/22A           | [7a5344db19](https://linux-hardware.org/?probe=7a5344db19) | Jul 28, 2022 |
| Toshiba       | dynabook R734/K             | [a5e7d4c919](https://linux-hardware.org/?probe=a5e7d4c919) | Jul 26, 2022 |
| NEC Comput... | U2                          | [22314f4475](https://linux-hardware.org/?probe=22314f4475) | Jul 25, 2022 |
| Dell          | Latitude 7320               | [83301910d0](https://linux-hardware.org/?probe=83301910d0) | Jul 25, 2022 |
| Apple         | MacBookAir9,1               | [cf4d815653](https://linux-hardware.org/?probe=cf4d815653) | Jul 24, 2022 |
| Alienware     | m17                         | [e14db26b9b](https://linux-hardware.org/?probe=e14db26b9b) | Jul 23, 2022 |
| NEC Comput... | PC-VJ24LLZCB                | [9b0955cfe2](https://linux-hardware.org/?probe=9b0955cfe2) | Jul 23, 2022 |
| Apple         | MacBookPro9,2               | [2ba1ac3ec9](https://linux-hardware.org/?probe=2ba1ac3ec9) | Jul 23, 2022 |
| MouseCompu... | L140MU                      | [5206d679a2](https://linux-hardware.org/?probe=5206d679a2) | Jul 22, 2022 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [8505a7d575](https://linux-hardware.org/?probe=8505a7d575) | Jul 21, 2022 |
| Panasonic     | CF-S10EYADR                 | [1990cd2a08](https://linux-hardware.org/?probe=1990cd2a08) | Jul 13, 2022 |
| Apple         | MacBookPro15,1              | [42d81e0803](https://linux-hardware.org/?probe=42d81e0803) | Jul 13, 2022 |
| Lenovo        | G575 4383                   | [8bd6296a3e](https://linux-hardware.org/?probe=8bd6296a3e) | Jul 12, 2022 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [de4d640168](https://linux-hardware.org/?probe=de4d640168) | Jul 10, 2022 |
| Apple         | MacBookPro14,1              | [aad648ac8d](https://linux-hardware.org/?probe=aad648ac8d) | Jul 02, 2022 |
| ASUSTek       | ROG Strix G733ZX_G733ZX     | [fc3e083086](https://linux-hardware.org/?probe=fc3e083086) | Jun 26, 2022 |
| Panasonic     | CFSV9-1                     | [4b7dd23ccd](https://linux-hardware.org/?probe=4b7dd23ccd) | Jun 20, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [fcbbdaf844](https://linux-hardware.org/?probe=fcbbdaf844) | Jun 18, 2022 |
| ASUSTek       | T100HAN                     | [20105d0e64](https://linux-hardware.org/?probe=20105d0e64) | Jun 16, 2022 |
| Dell          | XPS 15 9520                 | [03140c6f93](https://linux-hardware.org/?probe=03140c6f93) | Jun 15, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [cbf5603095](https://linux-hardware.org/?probe=cbf5603095) | Jun 13, 2022 |
| Dell          | XPS 15 9500                 | [197482fd83](https://linux-hardware.org/?probe=197482fd83) | Jun 13, 2022 |
| ASUSTek       | T100HAN                     | [9a5b9400a1](https://linux-hardware.org/?probe=9a5b9400a1) | Jun 12, 2022 |
| Sony          | VGN-Z71JB                   | [95a370d4e4](https://linux-hardware.org/?probe=95a370d4e4) | Jun 08, 2022 |
| Alienware     | 13 R3                       | [1431b0b659](https://linux-hardware.org/?probe=1431b0b659) | Jun 06, 2022 |
| Dell          | XPS 15 9500                 | [00e3c7f3c6](https://linux-hardware.org/?probe=00e3c7f3c6) | Jun 03, 2022 |
| Acer          | Aspire 5740                 | [db6d025d69](https://linux-hardware.org/?probe=db6d025d69) | Jun 01, 2022 |
| MSI           | Delta 15 A5EFK              | [1679888c2c](https://linux-hardware.org/?probe=1679888c2c) | May 29, 2022 |
| ASUSTek       | 900                         | [e50c30c38d](https://linux-hardware.org/?probe=e50c30c38d) | May 28, 2022 |
| ASUSTek       | 900                         | [dfd6af657c](https://linux-hardware.org/?probe=dfd6af657c) | May 28, 2022 |
| Gateway       | NV57H                       | [75c484ec74](https://linux-hardware.org/?probe=75c484ec74) | May 26, 2022 |
| Acer          | Aspire 5740                 | [2c541b20f6](https://linux-hardware.org/?probe=2c541b20f6) | May 26, 2022 |
| MouseCompu... | B5-R5RENASW11               | [35eae81eca](https://linux-hardware.org/?probe=35eae81eca) | May 25, 2022 |
| Dell          | XPS 15 9500                 | [4f2f7e71db](https://linux-hardware.org/?probe=4f2f7e71db) | May 24, 2022 |
| ASUSTek       | 900                         | [082b51aa29](https://linux-hardware.org/?probe=082b51aa29) | May 21, 2022 |
| HP            | ProBook 430 G7              | [04a6359630](https://linux-hardware.org/?probe=04a6359630) | May 21, 2022 |
| Lenovo        | G550 2958                   | [af5cc85e39](https://linux-hardware.org/?probe=af5cc85e39) | May 20, 2022 |
| Lenovo        | ThinkPad T410 2516CTO       | [e4150ff93b](https://linux-hardware.org/?probe=e4150ff93b) | May 19, 2022 |
| Dell          | XPS 15 9500                 | [671279f960](https://linux-hardware.org/?probe=671279f960) | May 18, 2022 |
| TUXEDO        | P95_HR                      | [05d8136964](https://linux-hardware.org/?probe=05d8136964) | May 15, 2022 |
| Dell          | Inspiron 11-3162            | [d1e811474c](https://linux-hardware.org/?probe=d1e811474c) | May 15, 2022 |
| Lenovo        | ThinkPad X200s 74664SJ      | [65728fda7a](https://linux-hardware.org/?probe=65728fda7a) | May 14, 2022 |
| Alienware     | 17                          | [b9be04342c](https://linux-hardware.org/?probe=b9be04342c) | May 13, 2022 |
| Toshiba       | PORTEGE Z930                | [fff817aea6](https://linux-hardware.org/?probe=fff817aea6) | May 10, 2022 |
| Thirdwave     | DX-T7                       | [b90ec1bf3a](https://linux-hardware.org/?probe=b90ec1bf3a) | May 10, 2022 |
| Fujitsu       | FMVNTCAKB                   | [66083f4e27](https://linux-hardware.org/?probe=66083f4e27) | May 09, 2022 |
| HP            | EliteBook 840 G3            | [ac1853274e](https://linux-hardware.org/?probe=ac1853274e) | May 08, 2022 |
| ASUSTek       | 900                         | [a4dc643c13](https://linux-hardware.org/?probe=a4dc643c13) | May 08, 2022 |
| ASUSTek       | 900                         | [6cbd0391b3](https://linux-hardware.org/?probe=6cbd0391b3) | May 07, 2022 |
| Toshiba       | dynabook R731/37EK          | [10ed6c8741](https://linux-hardware.org/?probe=10ed6c8741) | May 06, 2022 |
| Acer          | Aspire 5740                 | [e754b48e71](https://linux-hardware.org/?probe=e754b48e71) | May 06, 2022 |
| ASUSTek       | 900                         | [70b70a4392](https://linux-hardware.org/?probe=70b70a4392) | May 03, 2022 |
| Acer          | Aspire 5740                 | [6e1a9ce167](https://linux-hardware.org/?probe=6e1a9ce167) | May 01, 2022 |
| Acer          | Aspire 5740                 | [f9e5dd9719](https://linux-hardware.org/?probe=f9e5dd9719) | May 01, 2022 |
| Dell          | Inspiron 15-3565            | [a26578c0fc](https://linux-hardware.org/?probe=a26578c0fc) | Apr 30, 2022 |
| Dell          | Inspiron 15-3565            | [66d159169f](https://linux-hardware.org/?probe=66d159169f) | Apr 28, 2022 |
| Purism        | Librem 15 v3                | [d2a13c9d0a](https://linux-hardware.org/?probe=d2a13c9d0a) | Apr 27, 2022 |
| MouseCompu... | NH55Dx                      | [0a397dd5e7](https://linux-hardware.org/?probe=0a397dd5e7) | Apr 25, 2022 |
| ASUSTek       | ROG Strix G731GT_G731GT     | [9edf97b766](https://linux-hardware.org/?probe=9edf97b766) | Apr 24, 2022 |
| Panasonic     | CF-S10EYADR                 | [efd3e5ce84](https://linux-hardware.org/?probe=efd3e5ce84) | Apr 18, 2022 |
| TUXEDO        | P95_HR                      | [a3996b5033](https://linux-hardware.org/?probe=a3996b5033) | Apr 16, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [c6f1d1b99b](https://linux-hardware.org/?probe=c6f1d1b99b) | Apr 16, 2022 |
| Thirdwave     | DX-T7                       | [b03707283b](https://linux-hardware.org/?probe=b03707283b) | Apr 16, 2022 |
| Dell          | Vostro 2520                 | [fd8d5ab56a](https://linux-hardware.org/?probe=fd8d5ab56a) | Apr 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [29c02b0294](https://linux-hardware.org/?probe=29c02b0294) | Apr 12, 2022 |
| Acer          | Swift SF314-54              | [c40cfcc7fe](https://linux-hardware.org/?probe=c40cfcc7fe) | Apr 12, 2022 |
| MSI           | GP76 Leopard 11UG           | [aebd373a66](https://linux-hardware.org/?probe=aebd373a66) | Apr 12, 2022 |
| ASUSTek       | 1000H                       | [725f548eab](https://linux-hardware.org/?probe=725f548eab) | Apr 09, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | [5a344e20d6](https://linux-hardware.org/?probe=5a344e20d6) | Apr 06, 2022 |
| Toshiba       | dynabook R73/BN             | [af1ad57286](https://linux-hardware.org/?probe=af1ad57286) | Apr 06, 2022 |
| Lenovo        | ThinkPad X61s 7667DB2       | [34ae68d221](https://linux-hardware.org/?probe=34ae68d221) | Apr 05, 2022 |
| Lenovo        | ThinkPad X230 2306CTO       | [188a7794dd](https://linux-hardware.org/?probe=188a7794dd) | Apr 04, 2022 |
| TUXEDO        | P95_HR                      | [41cd5e79c8](https://linux-hardware.org/?probe=41cd5e79c8) | Apr 03, 2022 |
| MouseCompu... | MB-J370                     | [2c72ea9b17](https://linux-hardware.org/?probe=2c72ea9b17) | Apr 02, 2022 |
| ASUSTek       | ROG Strix G733ZX_G733ZX     | [d17d5e5310](https://linux-hardware.org/?probe=d17d5e5310) | Apr 01, 2022 |
| ASUSTek       | ROG Strix G733ZX_G733ZX     | [04f5858a30](https://linux-hardware.org/?probe=04f5858a30) | Apr 01, 2022 |
| Apple         | MacBookPro15,1              | [0fe3cba205](https://linux-hardware.org/?probe=0fe3cba205) | Mar 23, 2022 |
| System76      | Lemur Pro                   | [cd847b5e6a](https://linux-hardware.org/?probe=cd847b5e6a) | Mar 23, 2022 |
| Apple         | MacBookPro5,5               | [0e17f0194f](https://linux-hardware.org/?probe=0e17f0194f) | Mar 22, 2022 |
| Fujitsu       | FMVA05003                   | [d61a791168](https://linux-hardware.org/?probe=d61a791168) | Mar 19, 2022 |
| HP            | EliteBook 830 G6            | [46f513206b](https://linux-hardware.org/?probe=46f513206b) | Mar 18, 2022 |
| Dell          | G3 3500                     | [9ca3e10f43](https://linux-hardware.org/?probe=9ca3e10f43) | Mar 14, 2022 |
| R.W.C         | RM-A107-SR                  | [ab4bef6a90](https://linux-hardware.org/?probe=ab4bef6a90) | Mar 13, 2022 |
| Dell          | Latitude E5470              | [7fcd9d2c98](https://linux-hardware.org/?probe=7fcd9d2c98) | Mar 11, 2022 |
| Acer          | Aspire 4750                 | [0659469dbe](https://linux-hardware.org/?probe=0659469dbe) | Mar 09, 2022 |
| Toshiba       | dynabook RX3 SN240Y/3HD     | [2f2d99c83f](https://linux-hardware.org/?probe=2f2d99c83f) | Mar 03, 2022 |
| Toshiba       | dynabook RX3 SN240Y/3HD     | [0d0a2bab7a](https://linux-hardware.org/?probe=0d0a2bab7a) | Mar 03, 2022 |
| HP            | Notebook                    | [c8cd62d913](https://linux-hardware.org/?probe=c8cd62d913) | Feb 28, 2022 |
| Fujitsu       | FMVA05007                   | [21c7863329](https://linux-hardware.org/?probe=21c7863329) | Feb 27, 2022 |
| Fujitsu       | FMVA33LB2                   | [2dc30249b7](https://linux-hardware.org/?probe=2dc30249b7) | Feb 26, 2022 |
| Lenovo        | ThinkPad X220 4290LG4       | [bfb13999b0](https://linux-hardware.org/?probe=bfb13999b0) | Feb 26, 2022 |
| Fujitsu       | FMVA42CW                    | [ec10edeb39](https://linux-hardware.org/?probe=ec10edeb39) | Feb 22, 2022 |
| Panasonic     | CFSV9-1                     | [fa3b39bca1](https://linux-hardware.org/?probe=fa3b39bca1) | Feb 21, 2022 |
| Dell          | Vostro 3405                 | [f869338cb0](https://linux-hardware.org/?probe=f869338cb0) | Feb 20, 2022 |
| Apple         | MacBookAir3,2               | [2e812a8de9](https://linux-hardware.org/?probe=2e812a8de9) | Feb 17, 2022 |
| Fujitsu       | FARQ02010                   | [04fbabcfd2](https://linux-hardware.org/?probe=04fbabcfd2) | Feb 15, 2022 |
| Toshiba       | dynabook QOSMIO V65/86LY... | [681aa0b345](https://linux-hardware.org/?probe=681aa0b345) | Feb 13, 2022 |
| Lenovo        | G570 4334                   | [f5cef9fe9b](https://linux-hardware.org/?probe=f5cef9fe9b) | Feb 13, 2022 |
| ASUSTek       | U24A                        | [47e8fc096a](https://linux-hardware.org/?probe=47e8fc096a) | Feb 10, 2022 |
| Dell          | XPS L401X                   | [1db7a71e79](https://linux-hardware.org/?probe=1db7a71e79) | Feb 09, 2022 |
| Lenovo        | ThinkPad X61 76753BJ        | [76a7934681](https://linux-hardware.org/?probe=76a7934681) | Feb 09, 2022 |
| Lenovo        | G505 20240                  | [ed806edbbb](https://linux-hardware.org/?probe=ed806edbbb) | Feb 09, 2022 |
| Lenovo        | ThinkPad X240 20ALCTO1WW    | [1620a85467](https://linux-hardware.org/?probe=1620a85467) | Feb 08, 2022 |
| ASUSTek       | X541SA                      | [afafec99f9](https://linux-hardware.org/?probe=afafec99f9) | Feb 08, 2022 |
| Toshiba       | dynabook Satellite B453/... | [279ff9b0f0](https://linux-hardware.org/?probe=279ff9b0f0) | Feb 08, 2022 |
| ASUSTek       | S101                        | [a850549e73](https://linux-hardware.org/?probe=a850549e73) | Feb 04, 2022 |
| ASUSTek       | U24A                        | [c49e4b9513](https://linux-hardware.org/?probe=c49e4b9513) | Jan 31, 2022 |
| AMI           | Intel                       | [33011a4745](https://linux-hardware.org/?probe=33011a4745) | Jan 31, 2022 |
| AMI           | Intel                       | [f749123fdd](https://linux-hardware.org/?probe=f749123fdd) | Jan 31, 2022 |
| ASUSTek       | U24A                        | [cc19cff1a9](https://linux-hardware.org/?probe=cc19cff1a9) | Jan 30, 2022 |
| Fujitsu       | FMVA42CW                    | [ee9b2f44e9](https://linux-hardware.org/?probe=ee9b2f44e9) | Jan 29, 2022 |
| ASUSTek       | UX303LA                     | [b5e498daf0](https://linux-hardware.org/?probe=b5e498daf0) | Jan 28, 2022 |
| Acer          | Aspire V3-571               | [3d4087dc2a](https://linux-hardware.org/?probe=3d4087dc2a) | Jan 28, 2022 |
| Razer         | Blade Stealth               | [6a4fbb1374](https://linux-hardware.org/?probe=6a4fbb1374) | Jan 27, 2022 |
| Fujitsu       | FMVA42CW                    | [4ba92ab5ea](https://linux-hardware.org/?probe=4ba92ab5ea) | Jan 23, 2022 |
| Dell          | Latitude 3540               | [28339307b2](https://linux-hardware.org/?probe=28339307b2) | Jan 21, 2022 |
| ASUSTek       | 1000H                       | [f88ac2dd3e](https://linux-hardware.org/?probe=f88ac2dd3e) | Jan 19, 2022 |
| ASUSTek       | 1000H                       | [6c56c2c8b3](https://linux-hardware.org/?probe=6c56c2c8b3) | Jan 19, 2022 |
| KOUZIRO       | KOUZIRONB                   | [56b639daeb](https://linux-hardware.org/?probe=56b639daeb) | Jan 14, 2022 |
| Dynabook      | P1-C7MP-BL                  | [268f94787e](https://linux-hardware.org/?probe=268f94787e) | Jan 14, 2022 |
| Lenovo        | ThinkPad X61 76753BJ        | [8f0b1342b0](https://linux-hardware.org/?probe=8f0b1342b0) | Jan 10, 2022 |
| Lenovo        | ThinkPad X61 76753BJ        | [73ff2bcb33](https://linux-hardware.org/?probe=73ff2bcb33) | Jan 10, 2022 |
| Acer          | Predator PH315-53           | [7f928f794b](https://linux-hardware.org/?probe=7f928f794b) | Jan 04, 2022 |
| NEC Comput... | PC-LL550RG                  | [43435578b7](https://linux-hardware.org/?probe=43435578b7) | Jan 04, 2022 |
| Dell          | Inspiron 5557               | [53d769eaf7](https://linux-hardware.org/?probe=53d769eaf7) | Dec 31, 2021 |
| System76      | Lemur Pro                   | [287aa601fe](https://linux-hardware.org/?probe=287aa601fe) | Dec 29, 2021 |
| Toshiba       | dynabook RX3 SN240Y/3HD     | [0b20db823c](https://linux-hardware.org/?probe=0b20db823c) | Dec 29, 2021 |
| Dell          | Latitude 12 Rugged Table... | [13cc8e2abf](https://linux-hardware.org/?probe=13cc8e2abf) | Dec 25, 2021 |
| MSI           | Delta 15 A5EFK              | [68010a3af5](https://linux-hardware.org/?probe=68010a3af5) | Dec 23, 2021 |
| MSI           | Delta 15 A5EFK              | [2d4a0a1823](https://linux-hardware.org/?probe=2d4a0a1823) | Dec 23, 2021 |
| ASUSTek       | ASUS EXPERTBOOK B9450FA_... | [ded54cb08c](https://linux-hardware.org/?probe=ded54cb08c) | Dec 19, 2021 |
| Dell          | Inspiron 13 5310            | [bdad2f1618](https://linux-hardware.org/?probe=bdad2f1618) | Dec 14, 2021 |
| ASUSTek       | X510UQ                      | [1b14f17a6e](https://linux-hardware.org/?probe=1b14f17a6e) | Dec 11, 2021 |
| Apple         | MacBookPro12,1              | [a6e257304d](https://linux-hardware.org/?probe=a6e257304d) | Dec 05, 2021 |
| Toshiba       | dynabook Satellite B552/... | [b3c78d548b](https://linux-hardware.org/?probe=b3c78d548b) | Dec 03, 2021 |
| Apple         | MacBookPro13,2              | [d5c66e036d](https://linux-hardware.org/?probe=d5c66e036d) | Dec 02, 2021 |
| Notebook      | N13_N140ZU                  | [d63f7874c8](https://linux-hardware.org/?probe=d63f7874c8) | Nov 29, 2021 |
| Dell          | G3 3779                     | [cd6dace549](https://linux-hardware.org/?probe=cd6dace549) | Nov 26, 2021 |
| Notebook      | N13_N140ZU                  | [dca6d021bb](https://linux-hardware.org/?probe=dca6d021bb) | Nov 23, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [fdb480d5f4](https://linux-hardware.org/?probe=fdb480d5f4) | Nov 12, 2021 |
| Lenovo        | G580 26897JJ                | [dc2120663a](https://linux-hardware.org/?probe=dc2120663a) | Nov 10, 2021 |
| Dell          | Inspiron M5110              | [4a6d42444c](https://linux-hardware.org/?probe=4a6d42444c) | Nov 10, 2021 |
| System76      | Lemur Pro                   | [92a5e9c183](https://linux-hardware.org/?probe=92a5e9c183) | Nov 09, 2021 |
| Dell          | Inspiron 16 7610            | [34e330ff50](https://linux-hardware.org/?probe=34e330ff50) | Nov 07, 2021 |
| Toshiba       | dynabook QOSMIO V65/86LY... | [0193f0b7a0](https://linux-hardware.org/?probe=0193f0b7a0) | Nov 06, 2021 |
| Timi          | RedmiBook Pro 14S           | [470204d924](https://linux-hardware.org/?probe=470204d924) | Nov 03, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | [f7309ef31a](https://linux-hardware.org/?probe=f7309ef31a) | Oct 30, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | [26adc81160](https://linux-hardware.org/?probe=26adc81160) | Oct 30, 2021 |
| Toshiba       | PORTEGE Z20t-C              | [ed1722174a](https://linux-hardware.org/?probe=ed1722174a) | Oct 27, 2021 |
| Dell          | G5 5500                     | [cf10cd5b99](https://linux-hardware.org/?probe=cf10cd5b99) | Oct 25, 2021 |
| Dell          | XPS 13 9350                 | [1f26867986](https://linux-hardware.org/?probe=1f26867986) | Oct 25, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [6aa4ae0da5](https://linux-hardware.org/?probe=6aa4ae0da5) | Oct 23, 2021 |
| HP            | ProBook 6550b               | [4db59c8489](https://linux-hardware.org/?probe=4db59c8489) | Oct 23, 2021 |
| Dell          | G3 3779                     | [a84248c5d5](https://linux-hardware.org/?probe=a84248c5d5) | Oct 21, 2021 |
| Jumper        | Ezbook X3                   | [fe510b821a](https://linux-hardware.org/?probe=fe510b821a) | Oct 17, 2021 |
| UNITCOM       | W55xEU                      | [ced300109d](https://linux-hardware.org/?probe=ced300109d) | Oct 15, 2021 |
| NEC Comput... | PC-LL550VG6R                | [5879ce1d61](https://linux-hardware.org/?probe=5879ce1d61) | Oct 13, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [f2690f5ec4](https://linux-hardware.org/?probe=f2690f5ec4) | Oct 13, 2021 |
| Toshiba       | dynabook R634/K             | [f0e385cbfb](https://linux-hardware.org/?probe=f0e385cbfb) | Oct 08, 2021 |
| Acer          | Nitro AN515-45              | [6918b927d0](https://linux-hardware.org/?probe=6918b927d0) | Oct 07, 2021 |
| Dell          | XPS 13 9380                 | [0b768f6fac](https://linux-hardware.org/?probe=0b768f6fac) | Oct 04, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [1c920ce007](https://linux-hardware.org/?probe=1c920ce007) | Oct 03, 2021 |
| Fujitsu       | U9311                       | [a76f2fbbe3](https://linux-hardware.org/?probe=a76f2fbbe3) | Sep 30, 2021 |
| Panasonic     | CFSV9-2                     | [05b8edc925](https://linux-hardware.org/?probe=05b8edc925) | Sep 29, 2021 |
| NEC Comput... | PC-GN15B79AA                | [a1046b626e](https://linux-hardware.org/?probe=a1046b626e) | Sep 23, 2021 |
| NEC Comput... | PC-GN15B79AA                | [a1b9f1dc30](https://linux-hardware.org/?probe=a1b9f1dc30) | Sep 23, 2021 |
| Toshiba       | dynabook QOSMIO V65/86LY... | [b0289ef67d](https://linux-hardware.org/?probe=b0289ef67d) | Sep 22, 2021 |
| Apple         | MacBook7,1                  | [5164ba24f6](https://linux-hardware.org/?probe=5164ba24f6) | Sep 21, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [5dabdbd945](https://linux-hardware.org/?probe=5dabdbd945) | Sep 19, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [6f52a2ebed](https://linux-hardware.org/?probe=6f52a2ebed) | Sep 18, 2021 |
| Apple         | MacBookPro5,5               | [d7ee29aac3](https://linux-hardware.org/?probe=d7ee29aac3) | Sep 15, 2021 |
| Panasonic     | CF-S10EYTDR                 | [a90d037dcf](https://linux-hardware.org/?probe=a90d037dcf) | Sep 10, 2021 |
| ASUSTek       | G551JM                      | [9f323164cd](https://linux-hardware.org/?probe=9f323164cd) | Sep 09, 2021 |
| Lenovo        | ThinkPad X201 3249CTO       | [7b3432fcf6](https://linux-hardware.org/?probe=7b3432fcf6) | Sep 08, 2021 |
| ASUSTek       | ZenBook UX425IA_U4700IA     | [fa970f7a80](https://linux-hardware.org/?probe=fa970f7a80) | Sep 08, 2021 |
| TUXEDO        | P95_HR                      | [f5d32061ec](https://linux-hardware.org/?probe=f5d32061ec) | Sep 08, 2021 |
| Toshiba       | dynabook T55/PW             | [1ce1b25ad5](https://linux-hardware.org/?probe=1ce1b25ad5) | Sep 04, 2021 |
| Lenovo        | ThinkPad X230 2306A44       | [8f97e284a7](https://linux-hardware.org/?probe=8f97e284a7) | Sep 03, 2021 |
| Toshiba       | dynabook R73/A              | [deb0351e19](https://linux-hardware.org/?probe=deb0351e19) | Sep 03, 2021 |
| Acer          | Aspire V5-571G              | [919b7c1304](https://linux-hardware.org/?probe=919b7c1304) | Sep 01, 2021 |
| Acer          | Aspire V5-471               | [469dc0f2ef](https://linux-hardware.org/?probe=469dc0f2ef) | Aug 31, 2021 |
| Acer          | Aspire V5-471               | [47f44e561f](https://linux-hardware.org/?probe=47f44e561f) | Aug 31, 2021 |
| Lenovo        | ThinkPad X201 3249CTO       | [0a9bdb4827](https://linux-hardware.org/?probe=0a9bdb4827) | Aug 27, 2021 |
| Apple         | MacBookPro11,5              | [814f16635c](https://linux-hardware.org/?probe=814f16635c) | Aug 22, 2021 |
| Sony          | VGN-S55B_S                  | [f8237269e1](https://linux-hardware.org/?probe=f8237269e1) | Aug 22, 2021 |
| HP            | Laptop 15s-eq1xxx           | [90446b95e6](https://linux-hardware.org/?probe=90446b95e6) | Aug 21, 2021 |
| HP            | ProBook 6470b               | [4d338e7f16](https://linux-hardware.org/?probe=4d338e7f16) | Aug 15, 2021 |
| Acer          | Aspire A315-42              | [4a54197130](https://linux-hardware.org/?probe=4a54197130) | Aug 15, 2021 |
| Lenovo        | ThinkPad X201 3249CTO       | [9b9cd9a995](https://linux-hardware.org/?probe=9b9cd9a995) | Aug 10, 2021 |
| HP            | EliteBook Folio 1020 G1 ... | [32e6ec699f](https://linux-hardware.org/?probe=32e6ec699f) | Aug 09, 2021 |
| HP            | EliteBook Folio 1020 G1 ... | [7facd0568b](https://linux-hardware.org/?probe=7facd0568b) | Aug 09, 2021 |
| Lenovo        | ThinkPad X250 20CLS8E700    | [467f177df6](https://linux-hardware.org/?probe=467f177df6) | Aug 09, 2021 |
| NEC Comput... | PC-GN246W3A5                | [dfc05750e3](https://linux-hardware.org/?probe=dfc05750e3) | Aug 09, 2021 |
| Panasonic     | CF-S10EYTDR                 | [b965812f09](https://linux-hardware.org/?probe=b965812f09) | Aug 06, 2021 |
| Lenovo        | ThinkPad L520 5016NU7       | [101a0ca1b3](https://linux-hardware.org/?probe=101a0ca1b3) | Aug 01, 2021 |
| Lenovo        | ThinkPad L520 5016NU7       | [08fe25ec71](https://linux-hardware.org/?probe=08fe25ec71) | Aug 01, 2021 |
| HP            | Pavilion Laptop 13-an0xx... | [ff5bee5ff8](https://linux-hardware.org/?probe=ff5bee5ff8) | Aug 01, 2021 |
| Chuwi         | GemiBook Pro                | [a4ecebc31b](https://linux-hardware.org/?probe=a4ecebc31b) | Jul 27, 2021 |
| Chuwi         | GemiBook Pro                | [63b014e84e](https://linux-hardware.org/?probe=63b014e84e) | Jul 26, 2021 |
| Chuwi         | GemiBook Pro                | [478d06f2df](https://linux-hardware.org/?probe=478d06f2df) | Jul 26, 2021 |
| Acer          | Nitro AN515-45              | [fbf1f240f4](https://linux-hardware.org/?probe=fbf1f240f4) | Jul 24, 2021 |
| Fujitsu       | FMVS03004                   | [0182178989](https://linux-hardware.org/?probe=0182178989) | Jul 24, 2021 |
| HP            | 14                          | [29af89c91b](https://linux-hardware.org/?probe=29af89c91b) | Jul 23, 2021 |
| HP            | 14                          | [345be169ae](https://linux-hardware.org/?probe=345be169ae) | Jul 20, 2021 |
| Fujitsu       | FMVS54CD1                   | [7e6aa1f514](https://linux-hardware.org/?probe=7e6aa1f514) | Jul 18, 2021 |
| Dell          | Inspiron N5110              | [80b10e8187](https://linux-hardware.org/?probe=80b10e8187) | Jul 18, 2021 |
| Fujitsu       | FMVS54CD1                   | [ad9e144c6a](https://linux-hardware.org/?probe=ad9e144c6a) | Jul 15, 2021 |
| Dell          | Latitude E5510              | [2ab8a16c55](https://linux-hardware.org/?probe=2ab8a16c55) | Jul 12, 2021 |
| Toshiba       | dynabook T954/89L           | [176e4906db](https://linux-hardware.org/?probe=176e4906db) | Jul 12, 2021 |
| Dell          | Inspiron 1526               | [515fc96089](https://linux-hardware.org/?probe=515fc96089) | Jul 11, 2021 |
| Lenovo        | ThinkPad X61s 7667DB2       | [c0af3fd295](https://linux-hardware.org/?probe=c0af3fd295) | Jul 05, 2021 |
| Google        | Helios                      | [644f9f9062](https://linux-hardware.org/?probe=644f9f9062) | Jul 02, 2021 |
| Dell          | XPS 15 9500                 | [db7536f5a7](https://linux-hardware.org/?probe=db7536f5a7) | Jun 29, 2021 |
| Dell          | Inspiron 5583               | [a1f0396c8e](https://linux-hardware.org/?probe=a1f0396c8e) | Jun 29, 2021 |
| Lenovo        | ThinkPad X61s 7667DB2       | [32d294ba2a](https://linux-hardware.org/?probe=32d294ba2a) | Jun 23, 2021 |
| Toshiba       | dynabook T954/89L           | [c4b1b8aabb](https://linux-hardware.org/?probe=c4b1b8aabb) | Jun 21, 2021 |
| Toshiba       | dynabook T954/89L           | [b6a5d80f8a](https://linux-hardware.org/?probe=b6a5d80f8a) | Jun 21, 2021 |
| Lenovo        | S10-3                       | [eb48df4717](https://linux-hardware.org/?probe=eb48df4717) | Jun 20, 2021 |
| HP            | Pavilion Laptop 13-an0xx... | [2da9390d91](https://linux-hardware.org/?probe=2da9390d91) | Jun 11, 2021 |
| HP            | Pavilion Laptop 13-an0xx... | [c33921449f](https://linux-hardware.org/?probe=c33921449f) | Jun 10, 2021 |
| Toshiba       | dynabook R73/BN             | [c9cdf2bc57](https://linux-hardware.org/?probe=c9cdf2bc57) | Jun 06, 2021 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [0860242147](https://linux-hardware.org/?probe=0860242147) | Jun 04, 2021 |
| Biostar       | B350GTN                     | [6ba7f458da](https://linux-hardware.org/?probe=6ba7f458da) | Jun 01, 2021 |
| Lenovo        | ThinkPad T420s 4170CTO      | [74057c8385](https://linux-hardware.org/?probe=74057c8385) | May 30, 2021 |
| Lenovo        | S10-3                       | [8dfadf5edb](https://linux-hardware.org/?probe=8dfadf5edb) | May 27, 2021 |
| NEC Comput... | PC-LL730TG                  | [e4172892e9](https://linux-hardware.org/?probe=e4172892e9) | May 26, 2021 |
| Notebook      | N13_N140ZU                  | [4d1d4e61c3](https://linux-hardware.org/?probe=4d1d4e61c3) | May 25, 2021 |
| NEC Comput... | PC-VK22TGGCN                | [b6a2893c7e](https://linux-hardware.org/?probe=b6a2893c7e) | May 25, 2021 |
| Dell          | Latitude E6420              | [4ef6253092](https://linux-hardware.org/?probe=4ef6253092) | May 22, 2021 |
| Dell          | XPS 13 9360                 | [4ea4747cbf](https://linux-hardware.org/?probe=4ea4747cbf) | May 18, 2021 |
| Lenovo        | IdeaPad 300-15IBR 80M3      | [5d215fafdd](https://linux-hardware.org/?probe=5d215fafdd) | May 15, 2021 |
| Lenovo        | IdeaPad 300-15IBR 80M3      | [fdc8841fca](https://linux-hardware.org/?probe=fdc8841fca) | May 14, 2021 |
| Fujitsu       | FMVWE3AB11                  | [6c767dc0df](https://linux-hardware.org/?probe=6c767dc0df) | May 13, 2021 |
| Fujitsu       | FMVWE3AB11                  | [5ed8fb5a9f](https://linux-hardware.org/?probe=5ed8fb5a9f) | May 13, 2021 |
| Lenovo        | ThinkPad X230 2330A17       | [02280704ba](https://linux-hardware.org/?probe=02280704ba) | May 11, 2021 |
| Dell          | Inspiron 1545               | [c796c57372](https://linux-hardware.org/?probe=c796c57372) | May 10, 2021 |
| Fujitsu       | FMVWE3AB11                  | [e7238c107c](https://linux-hardware.org/?probe=e7238c107c) | May 09, 2021 |
| Fujitsu       | FMVNF40UK                   | [8648b42278](https://linux-hardware.org/?probe=8648b42278) | May 09, 2021 |
| MouseCompu... | W150ERQ                     | [1ccfec5c8f](https://linux-hardware.org/?probe=1ccfec5c8f) | May 07, 2021 |
| Dell          | XPS 13 9360                 | [f001bddea6](https://linux-hardware.org/?probe=f001bddea6) | May 04, 2021 |
| Fujitsu       | FMVWE3AB11                  | [65dce9cf99](https://linux-hardware.org/?probe=65dce9cf99) | May 03, 2021 |
| Dynabook      | P1-T6NP-EG                  | [887c9157d0](https://linux-hardware.org/?probe=887c9157d0) | May 03, 2021 |
| Toshiba       | dynabook Satellite J61 1... | [0b4c4a93f1](https://linux-hardware.org/?probe=0b4c4a93f1) | Apr 29, 2021 |
| Maibenben     | S431                        | [a4db49a83f](https://linux-hardware.org/?probe=a4db49a83f) | Apr 29, 2021 |
| NEC Comput... | PC-VY25AACZ9                | [dc22e810b4](https://linux-hardware.org/?probe=dc22e810b4) | Apr 29, 2021 |
| KOUZIRO       | KOUZIRONB                   | [c64bf46d8b](https://linux-hardware.org/?probe=c64bf46d8b) | Apr 24, 2021 |
| HP            | Laptop 15-db0xxx            | [7a4d236e06](https://linux-hardware.org/?probe=7a4d236e06) | Apr 24, 2021 |
| Dell          | XPS 13 9360                 | [dae1fdda5f](https://linux-hardware.org/?probe=dae1fdda5f) | Apr 23, 2021 |
| Lenovo        | ThinkBook 15p 20V3          | [fff82cb538](https://linux-hardware.org/?probe=fff82cb538) | Apr 22, 2021 |
| ASUSTek       | ZenBook UX331FA_UX331FA     | [d8340c053a](https://linux-hardware.org/?probe=d8340c053a) | Apr 22, 2021 |
| Lenovo        | ThinkPad T430s 23533KJ      | [39aa120e47](https://linux-hardware.org/?probe=39aa120e47) | Apr 21, 2021 |
| TUXEDO        | P95_HR                      | [4afc76cdbe](https://linux-hardware.org/?probe=4afc76cdbe) | Apr 17, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [3ee0cc7c18](https://linux-hardware.org/?probe=3ee0cc7c18) | Apr 13, 2021 |
| Dell          | Precision M4800             | [7a2924ab2a](https://linux-hardware.org/?probe=7a2924ab2a) | Apr 13, 2021 |
| HP            | Pavilion dv4                | [c5ed691eb7](https://linux-hardware.org/?probe=c5ed691eb7) | Apr 13, 2021 |
| KOUZIRO       | KOUZIRONB                   | [18adf344fe](https://linux-hardware.org/?probe=18adf344fe) | Apr 11, 2021 |
| NEC Comput... | PC-VY25AACZ9                | [24f7a90612](https://linux-hardware.org/?probe=24f7a90612) | Apr 10, 2021 |
| Dell          | Inspiron N5110              | [122641cd7e](https://linux-hardware.org/?probe=122641cd7e) | Apr 08, 2021 |
| NEC Comput... | PC-VK25TXZCE                | [e6acc84298](https://linux-hardware.org/?probe=e6acc84298) | Apr 07, 2021 |
| Toshiba       | dynabook BX/33M             | [06580ff422](https://linux-hardware.org/?probe=06580ff422) | Apr 06, 2021 |
| Lenovo        | ThinkPad X230 23245Y1       | [83430b3adf](https://linux-hardware.org/?probe=83430b3adf) | Apr 06, 2021 |
| Dynabook      | P1-T6NP-EG                  | [3f0b2d7c1d](https://linux-hardware.org/?probe=3f0b2d7c1d) | Apr 05, 2021 |
| Toshiba       | dynabook CX/48F             | [d32bf9dced](https://linux-hardware.org/?probe=d32bf9dced) | Apr 02, 2021 |
| ASUSTek       | ROG Strix G712LV_G712LV     | [a82050e3ae](https://linux-hardware.org/?probe=a82050e3ae) | Apr 01, 2021 |
| Toshiba       | dynabook Satellite B552/... | [0a547ba59a](https://linux-hardware.org/?probe=0a547ba59a) | Mar 31, 2021 |
| Dell          | Latitude E6320              | [2c01829c5b](https://linux-hardware.org/?probe=2c01829c5b) | Mar 28, 2021 |
| Dell          | G3 3500                     | [83f2a24875](https://linux-hardware.org/?probe=83f2a24875) | Mar 27, 2021 |
| ASUSTek       | ROG Strix G712LV_G712LV     | [22b865b40a](https://linux-hardware.org/?probe=22b865b40a) | Mar 26, 2021 |
| ASUSTek       | ROG Strix G712LV_G712LV     | [43c49d259d](https://linux-hardware.org/?probe=43c49d259d) | Mar 26, 2021 |
| HP            | G60                         | [a97ca105eb](https://linux-hardware.org/?probe=a97ca105eb) | Mar 25, 2021 |
| HP            | G60                         | [e8cc7247c7](https://linux-hardware.org/?probe=e8cc7247c7) | Mar 23, 2021 |
| TUXEDO        | P95_HR                      | [22b092fe80](https://linux-hardware.org/?probe=22b092fe80) | Mar 23, 2021 |
| Unknown       | Unknown                     | [a4b57558c3](https://linux-hardware.org/?probe=a4b57558c3) | Mar 22, 2021 |
| HP            | ProBook 430 G7              | [fbf317133b](https://linux-hardware.org/?probe=fbf317133b) | Mar 21, 2021 |
| Toshiba       | dynabook Satellite B552/... | [56a39af725](https://linux-hardware.org/?probe=56a39af725) | Mar 20, 2021 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [2d9b9381bd](https://linux-hardware.org/?probe=2d9b9381bd) | Mar 16, 2021 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [aac20e8dce](https://linux-hardware.org/?probe=aac20e8dce) | Mar 15, 2021 |
| Fujitsu       | FMVA05007                   | [707f6a3ea5](https://linux-hardware.org/?probe=707f6a3ea5) | Mar 14, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20T3C... | [7cda624782](https://linux-hardware.org/?probe=7cda624782) | Mar 12, 2021 |
| Dynabook      | GCX83/PLE                   | [2ef2ac3448](https://linux-hardware.org/?probe=2ef2ac3448) | Mar 12, 2021 |
| Fujitsu       | FMVS54EB                    | [f01ca3644f](https://linux-hardware.org/?probe=f01ca3644f) | Mar 11, 2021 |
| Dell          | Inspiron N5110              | [3feff6616d](https://linux-hardware.org/?probe=3feff6616d) | Mar 07, 2021 |
| Dell          | Latitude 7280               | [64e390d0d6](https://linux-hardware.org/?probe=64e390d0d6) | Mar 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [24088afc25](https://linux-hardware.org/?probe=24088afc25) | Mar 06, 2021 |
| Timi          | RedmiBook 16                | [7139d19a98](https://linux-hardware.org/?probe=7139d19a98) | Mar 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [e840817785](https://linux-hardware.org/?probe=e840817785) | Mar 03, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [5f5d47e737](https://linux-hardware.org/?probe=5f5d47e737) | Feb 26, 2021 |
| Lenovo        | Yoga 3 14 80JH              | [b1a878b7d0](https://linux-hardware.org/?probe=b1a878b7d0) | Feb 26, 2021 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | [55b2402c28](https://linux-hardware.org/?probe=55b2402c28) | Feb 25, 2021 |
| Apple         | MacBookPro9,2               | [3e009dec2f](https://linux-hardware.org/?probe=3e009dec2f) | Feb 23, 2021 |
| NEC Comput... | PC-LL750FS6R                | [2708ba9972](https://linux-hardware.org/?probe=2708ba9972) | Feb 23, 2021 |
| NEC Comput... | PC-VY22GXZ7A                | [fa1eb2a97a](https://linux-hardware.org/?probe=fa1eb2a97a) | Feb 23, 2021 |
| NEC Comput... | PC-VY22GXZ7A                | [cf754cecc4](https://linux-hardware.org/?probe=cf754cecc4) | Feb 23, 2021 |
| Toshiba       | dynabook Satellite TXW/6... | [51128d9716](https://linux-hardware.org/?probe=51128d9716) | Feb 19, 2021 |
| Toshiba       | dynabook EX/35KWH           | [c52a95f06c](https://linux-hardware.org/?probe=c52a95f06c) | Feb 18, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | [e8e114704d](https://linux-hardware.org/?probe=e8e114704d) | Feb 16, 2021 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | [977e293baa](https://linux-hardware.org/?probe=977e293baa) | Feb 16, 2021 |
| Fujitsu       | FMVNFB40J                   | [8a3d6bcc89](https://linux-hardware.org/?probe=8a3d6bcc89) | Feb 15, 2021 |
| Fujitsu       | FMVA05002                   | [a758e3201d](https://linux-hardware.org/?probe=a758e3201d) | Feb 14, 2021 |
| Lenovo        | ThinkPad T61 7659D92        | [8d9f56460d](https://linux-hardware.org/?probe=8d9f56460d) | Feb 13, 2021 |
| Fujitsu       | FMVA56GBX                   | [bdc337bd04](https://linux-hardware.org/?probe=bdc337bd04) | Feb 13, 2021 |
| HP            | Pavilion g6                 | [a45a89930f](https://linux-hardware.org/?probe=a45a89930f) | Feb 13, 2021 |
| Fujitsu       | FMVA05002                   | [db95456803](https://linux-hardware.org/?probe=db95456803) | Feb 12, 2021 |
| Panasonic     | CF-SX3EDHCS                 | [3f7a156241](https://linux-hardware.org/?probe=3f7a156241) | Feb 11, 2021 |
| NEC Comput... | PC-VK19SGZDF                | [624a2eee47](https://linux-hardware.org/?probe=624a2eee47) | Feb 10, 2021 |
| NEC Comput... | PC-VY12FBHEW                | [e507fdbcf5](https://linux-hardware.org/?probe=e507fdbcf5) | Feb 08, 2021 |
| NEC Comput... | PC-VY12FBHEW                | [c65bc992c6](https://linux-hardware.org/?probe=c65bc992c6) | Feb 08, 2021 |
| Unknown       | Unknown                     | [0c6628ea31](https://linux-hardware.org/?probe=0c6628ea31) | Jan 23, 2021 |
| NEC Comput... | PC-LL750SG6R                | [7c9081a73a](https://linux-hardware.org/?probe=7c9081a73a) | Jan 16, 2021 |
| Sony          | VGN-TZ73B                   | [735d00e026](https://linux-hardware.org/?probe=735d00e026) | Jan 13, 2021 |
| Sony          | VGN-TZ73B                   | [5df5433a1c](https://linux-hardware.org/?probe=5df5433a1c) | Jan 13, 2021 |
| Hampoo        | C3W6_AP108_4GB Reserved     | [1d6691dffe](https://linux-hardware.org/?probe=1d6691dffe) | Jan 12, 2021 |
| Hampoo        | C3W6_AP108_4GB Reserved     | [d033697e79](https://linux-hardware.org/?probe=d033697e79) | Jan 12, 2021 |
| Hampoo        | C3W6_AP108_4GB Reserved     | [6173e9c6e9](https://linux-hardware.org/?probe=6173e9c6e9) | Jan 12, 2021 |
| UNITCOM       | W55xEU                      | [8c2793a502](https://linux-hardware.org/?probe=8c2793a502) | Jan 10, 2021 |
| UNITCOM       | W55xEU                      | [44b1f16e92](https://linux-hardware.org/?probe=44b1f16e92) | Jan 10, 2021 |
| HUAWEI        | MRC-WX0                     | [f650998a3d](https://linux-hardware.org/?probe=f650998a3d) | Jan 02, 2021 |
| Fujitsu       | FMVLCE50B                   | [03569af3cb](https://linux-hardware.org/?probe=03569af3cb) | Dec 31, 2020 |
| MSI           | Modern 14 B4MW              | [ec110ae347](https://linux-hardware.org/?probe=ec110ae347) | Dec 28, 2020 |
| Lenovo        | ThinkPad X250 20CLA3TPJP    | [fbc4b89320](https://linux-hardware.org/?probe=fbc4b89320) | Dec 28, 2020 |
| Dell          | Inspiron 5490               | [25dadb6466](https://linux-hardware.org/?probe=25dadb6466) | Dec 26, 2020 |
| Dell          | Inspiron 5490               | [72bfd374e3](https://linux-hardware.org/?probe=72bfd374e3) | Dec 26, 2020 |
| Lenovo        | ThinkPad X230 23069FJ       | [84b2b1cba7](https://linux-hardware.org/?probe=84b2b1cba7) | Dec 26, 2020 |
| Thirdwave     | Diginnos PC                 | [4573bf9eeb](https://linux-hardware.org/?probe=4573bf9eeb) | Dec 25, 2020 |
| Toshiba       | dynabook Satellite TXW/6... | [f4fe782260](https://linux-hardware.org/?probe=f4fe782260) | Dec 25, 2020 |
| Lenovo        | ThinkPad X220 Tablet 429... | [fcc97d1fdb](https://linux-hardware.org/?probe=fcc97d1fdb) | Dec 25, 2020 |
| Toshiba       | dynabook Satellite TXW/6... | [21e571b40f](https://linux-hardware.org/?probe=21e571b40f) | Dec 25, 2020 |
| Dynabook      | P1-T6NP-EG                  | [9f6b496aaf](https://linux-hardware.org/?probe=9f6b496aaf) | Dec 25, 2020 |
| Fujitsu       | FMVNFA50                    | [27b2b3f4de](https://linux-hardware.org/?probe=27b2b3f4de) | Dec 22, 2020 |
| Dell          | Inspiron 13-5378            | [d236c778e1](https://linux-hardware.org/?probe=d236c778e1) | Dec 21, 2020 |
| Lenovo        | ThinkPad T490s 20NYS7K90... | [6a74695399](https://linux-hardware.org/?probe=6a74695399) | Dec 21, 2020 |
| Lenovo        | ThinkPad T60 1951CJ4        | [15c45c1a66](https://linux-hardware.org/?probe=15c45c1a66) | Dec 20, 2020 |
| Lenovo        | ThinkPad T60 1951CJ4        | [0f67c598b9](https://linux-hardware.org/?probe=0f67c598b9) | Dec 20, 2020 |
| Dell          | Latitude E6230              | [c0f67befa0](https://linux-hardware.org/?probe=c0f67befa0) | Dec 18, 2020 |
| Dell          | Latitude E6230              | [9dd587de7a](https://linux-hardware.org/?probe=9dd587de7a) | Dec 18, 2020 |
| Dell          | Inspiron 13-5378            | [52b0b77ef7](https://linux-hardware.org/?probe=52b0b77ef7) | Dec 17, 2020 |
| NEC Comput... | PC-LL750SG6R                | [867c1b37b1](https://linux-hardware.org/?probe=867c1b37b1) | Dec 14, 2020 |
| Dell          | Inspiron 5370               | [9cf5fbfe60](https://linux-hardware.org/?probe=9cf5fbfe60) | Dec 09, 2020 |
| Toshiba       | dynabook Satellite B552/... | [575c848b52](https://linux-hardware.org/?probe=575c848b52) | Dec 07, 2020 |
| Toshiba       | dynabook Satellite B552/... | [58cf889053](https://linux-hardware.org/?probe=58cf889053) | Dec 07, 2020 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [1190e2392c](https://linux-hardware.org/?probe=1190e2392c) | Dec 02, 2020 |
| HP            | G7000                       | [9596f449f8](https://linux-hardware.org/?probe=9596f449f8) | Nov 30, 2020 |
| HP            | G7000                       | [ae575e12ab](https://linux-hardware.org/?probe=ae575e12ab) | Nov 30, 2020 |
| Lenovo        | ThinkPad X230 23069FJ       | [e8e9e6770b](https://linux-hardware.org/?probe=e8e9e6770b) | Nov 29, 2020 |
| SLIMBOOK      | PROX14-AMD                  | [5fd1f62125](https://linux-hardware.org/?probe=5fd1f62125) | Nov 21, 2020 |
| SLIMBOOK      | PROX14-AMD                  | [593013a504](https://linux-hardware.org/?probe=593013a504) | Nov 20, 2020 |
| Lenovo        | ThinkPad T460 20FMS0QM00    | [f34c508c5a](https://linux-hardware.org/?probe=f34c508c5a) | Nov 19, 2020 |
| SLIMBOOK      | PROX14-AMD                  | [8d4468ec71](https://linux-hardware.org/?probe=8d4468ec71) | Nov 16, 2020 |
| Lenovo        | ThinkPad T460 20FMS0QM00    | [f827ecc142](https://linux-hardware.org/?probe=f827ecc142) | Nov 16, 2020 |
| SLIMBOOK      | PROX14-AMD                  | [adbf017e43](https://linux-hardware.org/?probe=adbf017e43) | Nov 13, 2020 |
| SLIMBOOK      | PROX14-AMD                  | [3d8a88a6dd](https://linux-hardware.org/?probe=3d8a88a6dd) | Nov 08, 2020 |
| SLIMBOOK      | PROX14-AMD                  | [d746af6cfd](https://linux-hardware.org/?probe=d746af6cfd) | Nov 07, 2020 |
| MouseCompu... | N252JU                      | [32a742ccd5](https://linux-hardware.org/?probe=32a742ccd5) | Nov 07, 2020 |
| MouseCompu... | N252JU                      | [497c61e3d1](https://linux-hardware.org/?probe=497c61e3d1) | Nov 07, 2020 |
| Panasonic     | CF-SX1GDHYS                 | [e8f3a6867e](https://linux-hardware.org/?probe=e8f3a6867e) | Nov 06, 2020 |
| Fujitsu       | FMVNF70W                    | [aedfc24e7e](https://linux-hardware.org/?probe=aedfc24e7e) | Nov 05, 2020 |
| Fujitsu       | FMVNF70W                    | [6039056d5c](https://linux-hardware.org/?probe=6039056d5c) | Nov 05, 2020 |
| Apple         | MacBookAir6,1               | [102aa409db](https://linux-hardware.org/?probe=102aa409db) | Nov 03, 2020 |
| MSI           | GS66 Stealth 10SF           | [c885924d12](https://linux-hardware.org/?probe=c885924d12) | Nov 02, 2020 |
| Lenovo        | ThinkPad X250 20CLA3TPJP    | [51449a174d](https://linux-hardware.org/?probe=51449a174d) | Nov 01, 2020 |
| HUAWEI        | MRC-WX0                     | [57608acdc4](https://linux-hardware.org/?probe=57608acdc4) | Oct 31, 2020 |
| Dell          | Vostro 2520                 | [196d3c6a8d](https://linux-hardware.org/?probe=196d3c6a8d) | Oct 30, 2020 |
| HP            | ENVY 15                     | [7e0fd3abbc](https://linux-hardware.org/?probe=7e0fd3abbc) | Oct 28, 2020 |
| Lenovo        | ThinkPad X230 2325SSF       | [d4b681e245](https://linux-hardware.org/?probe=d4b681e245) | Oct 28, 2020 |
| Dell          | Vostro 2520                 | [b660b39908](https://linux-hardware.org/?probe=b660b39908) | Oct 25, 2020 |
| HP            | ProBook 4525s               | [157a86205d](https://linux-hardware.org/?probe=157a86205d) | Oct 24, 2020 |
| Unknown       | Unknown                     | [046bfed81f](https://linux-hardware.org/?probe=046bfed81f) | Oct 23, 2020 |
| Sony          | VPCEB49FJ                   | [a7b30aea08](https://linux-hardware.org/?probe=a7b30aea08) | Oct 21, 2020 |
| EPSON DIRE... | Endeavor NJ7000E            | [fd0992fec0](https://linux-hardware.org/?probe=fd0992fec0) | Oct 21, 2020 |
| MouseCompu... | NG-N-i5730                  | [7748ae5522](https://linux-hardware.org/?probe=7748ae5522) | Oct 19, 2020 |
| ASUSTek       | E200HA                      | [01f02e3868](https://linux-hardware.org/?probe=01f02e3868) | Oct 19, 2020 |
| Fujitsu       | FMVNF70W                    | [af9ba22806](https://linux-hardware.org/?probe=af9ba22806) | Oct 17, 2020 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | [d7c4496b69](https://linux-hardware.org/?probe=d7c4496b69) | Oct 17, 2020 |
| HP            | ProBook 4525s               | [67efc6e80a](https://linux-hardware.org/?probe=67efc6e80a) | Oct 16, 2020 |
| UNITCOM       | W35_37ET                    | [13ddafa560](https://linux-hardware.org/?probe=13ddafa560) | Oct 16, 2020 |
| NEC Comput... | PC-LL750F26C                | [7b9dc13b94](https://linux-hardware.org/?probe=7b9dc13b94) | Oct 10, 2020 |
| NEC Comput... | PC-LL750F26C                | [eb148db6e7](https://linux-hardware.org/?probe=eb148db6e7) | Oct 09, 2020 |
| Sony          | VPCS129FJ                   | [ababc3caff](https://linux-hardware.org/?probe=ababc3caff) | Oct 07, 2020 |
| Lenovo        | ThinkPad X230 2325SSF       | [e4b06fc3af](https://linux-hardware.org/?probe=e4b06fc3af) | Oct 07, 2020 |
| HP            | ENVY 15                     | [096683ec03](https://linux-hardware.org/?probe=096683ec03) | Oct 06, 2020 |
| Fujitsu       | FMVWW11W                    | [e1a03b47aa](https://linux-hardware.org/?probe=e1a03b47aa) | Oct 06, 2020 |
| Lenovo        | ThinkPad X61 76753BJ        | [ebe29c2e8c](https://linux-hardware.org/?probe=ebe29c2e8c) | Oct 06, 2020 |
| Lenovo        | ThinkPad X61 76753BJ        | [4c90a49a16](https://linux-hardware.org/?probe=4c90a49a16) | Oct 05, 2020 |
| HP            | ProBook 6560b               | [4f60a7aca9](https://linux-hardware.org/?probe=4f60a7aca9) | Oct 05, 2020 |
| Lenovo        | ThinkPad X61 76753BJ        | [117567ed8a](https://linux-hardware.org/?probe=117567ed8a) | Oct 02, 2020 |
| Lenovo        | ThinkPad X61 76753BJ        | [c1729c7402](https://linux-hardware.org/?probe=c1729c7402) | Oct 02, 2020 |
| HUAWEI        | BOHK-WAX9X                  | [51fb8f3cad](https://linux-hardware.org/?probe=51fb8f3cad) | Oct 02, 2020 |
| Lenovo        | M4450 20302                 | [0614174763](https://linux-hardware.org/?probe=0614174763) | Sep 29, 2020 |
| Samsung       | 905S3G/906S3G/915S3G/930... | [2ebce35736](https://linux-hardware.org/?probe=2ebce35736) | Sep 29, 2020 |
| ASUSTek       | VivoBook E14 E402YA_E402... | [84913584dc](https://linux-hardware.org/?probe=84913584dc) | Sep 27, 2020 |
| Sharp         | PC-WE/WT Series             | [91e9663e3a](https://linux-hardware.org/?probe=91e9663e3a) | Sep 22, 2020 |
| HP            | ProBook 6550b               | [58aeb4c973](https://linux-hardware.org/?probe=58aeb4c973) | Sep 19, 2020 |
| Lenovo        | ThinkPad X230 2325SSF       | [087fa4f531](https://linux-hardware.org/?probe=087fa4f531) | Sep 17, 2020 |
| HP            | ProBook 6570b               | [db08cfd499](https://linux-hardware.org/?probe=db08cfd499) | Sep 17, 2020 |
| Lenovo        | ThinkPad X200s 74664SJ      | [d58a689a0b](https://linux-hardware.org/?probe=d58a689a0b) | Sep 13, 2020 |
| Sony          | VGN-NW50JB                  | [f5115778c1](https://linux-hardware.org/?probe=f5115778c1) | Sep 11, 2020 |
| HP            | EliteBook 820 G2            | [37e43e92e5](https://linux-hardware.org/?probe=37e43e92e5) | Sep 07, 2020 |
| HP            | ENVY Notebook               | [4da75a6d49](https://linux-hardware.org/?probe=4da75a6d49) | Sep 07, 2020 |
| Toshiba       | dynabook T554/56KW          | [03f3e6b816](https://linux-hardware.org/?probe=03f3e6b816) | Sep 04, 2020 |
| Samsung       | 940X3G/930X3G               | [d63abb12ee](https://linux-hardware.org/?probe=d63abb12ee) | Sep 03, 2020 |
| Toshiba       | dynabook SS MX/25AE         | [8d195475bf](https://linux-hardware.org/?probe=8d195475bf) | Sep 02, 2020 |
| Fujitsu       | FMVNF70W                    | [b782fe1564](https://linux-hardware.org/?probe=b782fe1564) | Aug 31, 2020 |
| Fujitsu       | FMVNF70W                    | [7451d691b9](https://linux-hardware.org/?probe=7451d691b9) | Aug 31, 2020 |
| Lenovo        | ThinkPad X200s 74664SJ      | [efd7cd5751](https://linux-hardware.org/?probe=efd7cd5751) | Aug 29, 2020 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [a2c94f7fdd](https://linux-hardware.org/?probe=a2c94f7fdd) | Aug 29, 2020 |
| Acer          | Aspire V3-571               | [8b32c068dc](https://linux-hardware.org/?probe=8b32c068dc) | Aug 24, 2020 |
| UNITCOM       | W35_37ET                    | [221322a11d](https://linux-hardware.org/?probe=221322a11d) | Aug 18, 2020 |
| Lenovo        | G500 20236                  | [28aacac404](https://linux-hardware.org/?probe=28aacac404) | Aug 16, 2020 |
| Fujitsu       | FMVNF70W                    | [ea2752e5b3](https://linux-hardware.org/?probe=ea2752e5b3) | Aug 14, 2020 |
| Sony          | SVE14A18FJW                 | [0868a90d93](https://linux-hardware.org/?probe=0868a90d93) | Aug 11, 2020 |
| Sony          | SVE14A18FJW                 | [dcd00b5fdc](https://linux-hardware.org/?probe=dcd00b5fdc) | Aug 11, 2020 |
| Lenovo        | ThinkPad T400 6475F99       | [83366b7e92](https://linux-hardware.org/?probe=83366b7e92) | Aug 10, 2020 |
| Dell          | XPS 15 9570                 | [7b17868903](https://linux-hardware.org/?probe=7b17868903) | Aug 07, 2020 |
| Lenovo        | ThinkPad T430s 2352CTO      | [1ae67d880c](https://linux-hardware.org/?probe=1ae67d880c) | Aug 02, 2020 |
| Thirdwave     | Diginnos PC                 | [edad55d12d](https://linux-hardware.org/?probe=edad55d12d) | Aug 02, 2020 |
| Thirdwave     | Diginnos PC                 | [e1fd71a4b1](https://linux-hardware.org/?probe=e1fd71a4b1) | Aug 02, 2020 |
| Panasonic     | CF-N9LYDKDS                 | [8f3337d6ad](https://linux-hardware.org/?probe=8f3337d6ad) | Jul 31, 2020 |
| Fujitsu       | FMVU2400AD                  | [3353544fa3](https://linux-hardware.org/?probe=3353544fa3) | Jul 31, 2020 |
| HP            | ProBook 430 G3              | [7d3e5091ef](https://linux-hardware.org/?probe=7d3e5091ef) | Jul 29, 2020 |
| Sony          | VGN-S55B_S                  | [2643feee17](https://linux-hardware.org/?probe=2643feee17) | Jul 24, 2020 |
| Toshiba       | dynabook T554/56KW          | [a6edb6db3c](https://linux-hardware.org/?probe=a6edb6db3c) | Jul 23, 2020 |
| Lenovo        | ThinkPad E520 1143RD9       | [8947a114a1](https://linux-hardware.org/?probe=8947a114a1) | Jul 20, 2020 |
| NEC Comput... | PC-GN246W3A5                | [b95df976ea](https://linux-hardware.org/?probe=b95df976ea) | Jul 19, 2020 |
| Fujitsu       | FMVA705BW                   | [0985e32752](https://linux-hardware.org/?probe=0985e32752) | Jul 18, 2020 |
| Toshiba       | dynabook EX/66MRD           | [e3a6da6bcc](https://linux-hardware.org/?probe=e3a6da6bcc) | Jul 16, 2020 |
| ASUSTek       | TUF Gaming FA506IU_TUF50... | [51c975b932](https://linux-hardware.org/?probe=51c975b932) | Jul 12, 2020 |
| NEC Comput... | PC-VJ19SGHDWLTF             | [b99df50393](https://linux-hardware.org/?probe=b99df50393) | Jul 12, 2020 |
| Acer          | Aspire 3810T                | [bc217e9435](https://linux-hardware.org/?probe=bc217e9435) | Jul 12, 2020 |
| Acer          | Aspire 3810T                | [9b2e49ccd8](https://linux-hardware.org/?probe=9b2e49ccd8) | Jul 12, 2020 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [7cf0424b3b](https://linux-hardware.org/?probe=7cf0424b3b) | Jul 10, 2020 |
| Lenovo        | ThinkPad T450 20BUS0G500    | [439f2ff831](https://linux-hardware.org/?probe=439f2ff831) | Jul 07, 2020 |
| Lenovo        | ThinkPad T450 20BUS0G500    | [770f2f3b0b](https://linux-hardware.org/?probe=770f2f3b0b) | Jul 07, 2020 |
| HP            | ProBook 470 G1              | [7e2ba71d87](https://linux-hardware.org/?probe=7e2ba71d87) | Jul 06, 2020 |
| Fujitsu       | FMVNF70W                    | [5b28cc735f](https://linux-hardware.org/?probe=5b28cc735f) | Jul 02, 2020 |
| Fujitsu       | FMVNF70W                    | [28307d3d6c](https://linux-hardware.org/?probe=28307d3d6c) | Jul 02, 2020 |
| ASUSTek       | K53SK                       | [2003676ccf](https://linux-hardware.org/?probe=2003676ccf) | Jul 01, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [6457099b06](https://linux-hardware.org/?probe=6457099b06) | Jun 27, 2020 |
| Apple         | MacBookPro11,1              | [8754b0ae46](https://linux-hardware.org/?probe=8754b0ae46) | Jun 27, 2020 |
| MSI           | GS63 7RE                    | [31dfc658d7](https://linux-hardware.org/?probe=31dfc658d7) | Jun 26, 2020 |
| Apple         | MacBookPro11,1              | [2a32b846c5](https://linux-hardware.org/?probe=2a32b846c5) | Jun 24, 2020 |
| Lenovo        | ThinkPad T500 208843J       | [a12d551827](https://linux-hardware.org/?probe=a12d551827) | Jun 21, 2020 |
| Sony          | VGN-S55B_S                  | [1943134c38](https://linux-hardware.org/?probe=1943134c38) | Jun 21, 2020 |
| Lenovo        | IdeaPad U300s 1080          | [dca0b5baa2](https://linux-hardware.org/?probe=dca0b5baa2) | Jun 21, 2020 |
| Lenovo        | IdeaPad U300s 1080          | [198cec29f3](https://linux-hardware.org/?probe=198cec29f3) | Jun 21, 2020 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [acbdac722c](https://linux-hardware.org/?probe=acbdac722c) | Jun 19, 2020 |
| Dell          | Inspiron 15-3565            | [696dea86af](https://linux-hardware.org/?probe=696dea86af) | Jun 15, 2020 |
| Apple         | MacBookPro16,1              | [8b4c1f4506](https://linux-hardware.org/?probe=8b4c1f4506) | Jun 15, 2020 |
| Apple         | MacBookPro9,2               | [5cedae8b83](https://linux-hardware.org/?probe=5cedae8b83) | Jun 12, 2020 |
| Gateway       | NE56R                       | [45934f9b2c](https://linux-hardware.org/?probe=45934f9b2c) | Jun 12, 2020 |
| ASUSTek       | K53SK                       | [ec6ff61a8c](https://linux-hardware.org/?probe=ec6ff61a8c) | Jun 12, 2020 |
| Fujitsu       | FMVNFG60TC                  | [b6bad717fa](https://linux-hardware.org/?probe=b6bad717fa) | Jun 10, 2020 |
| Fujitsu       | FMVNFG60TC                  | [1b3a040711](https://linux-hardware.org/?probe=1b3a040711) | Jun 10, 2020 |
| Fujitsu       | FMVA77JW                    | [ce5b1dbbcb](https://linux-hardware.org/?probe=ce5b1dbbcb) | Jun 10, 2020 |
| Dell          | Inspiron 15-3565            | [91540b6b55](https://linux-hardware.org/?probe=91540b6b55) | Jun 10, 2020 |
| Lenovo        | ThinkPad X230 232425J       | [2ebe6149b7](https://linux-hardware.org/?probe=2ebe6149b7) | Jun 06, 2020 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [c4d2595650](https://linux-hardware.org/?probe=c4d2595650) | Jun 04, 2020 |
| HUAWEI        | HN-WX9X                     | [7c56c01092](https://linux-hardware.org/?probe=7c56c01092) | May 30, 2020 |
| Dell          | Inspiron 7590               | [18895b4469](https://linux-hardware.org/?probe=18895b4469) | May 27, 2020 |
| Panasonic     | CF-195W1ACS                 | [5ee3c1d71e](https://linux-hardware.org/?probe=5ee3c1d71e) | May 27, 2020 |
| Dell          | Inspiron 7590               | [e219e1df90](https://linux-hardware.org/?probe=e219e1df90) | May 25, 2020 |
| Dell          | Inspiron 7590               | [46683fd696](https://linux-hardware.org/?probe=46683fd696) | May 25, 2020 |
| Dell          | Inspiron 7590               | [208561b660](https://linux-hardware.org/?probe=208561b660) | May 25, 2020 |
| Lenovo        | Z51-70 80K6                 | [7b25fce04c](https://linux-hardware.org/?probe=7b25fce04c) | May 24, 2020 |
| Acer          | Aspire 8940G                | [186821b722](https://linux-hardware.org/?probe=186821b722) | May 23, 2020 |
| Unknown       | Unknown                     | [d163d86dcb](https://linux-hardware.org/?probe=d163d86dcb) | May 19, 2020 |
| Toshiba       | dynabook T45/VRS            | [ddae801625](https://linux-hardware.org/?probe=ddae801625) | May 18, 2020 |
| Toshiba       | dynabook T45/VRS            | [efafbf544b](https://linux-hardware.org/?probe=efafbf544b) | May 18, 2020 |
| Panasonic     | CFSX4-1L                    | [54b56291de](https://linux-hardware.org/?probe=54b56291de) | May 18, 2020 |
| HP            | ProBook 6560b               | [72808d19a6](https://linux-hardware.org/?probe=72808d19a6) | May 15, 2020 |
| HP            | ProBook 6560b               | [f88ec1bc1d](https://linux-hardware.org/?probe=f88ec1bc1d) | May 15, 2020 |
| Lenovo        | G570 4334                   | [54ff12939f](https://linux-hardware.org/?probe=54ff12939f) | May 11, 2020 |
| Toshiba       | dynabook CX/45J             | [98a1bae5fd](https://linux-hardware.org/?probe=98a1bae5fd) | May 06, 2020 |
| HP            | Pavilion dv4                | [ea93ee2d08](https://linux-hardware.org/?probe=ea93ee2d08) | May 06, 2020 |
| Apple         | MacBookPro9,2               | [593c0984df](https://linux-hardware.org/?probe=593c0984df) | May 05, 2020 |
| Apple         | MacBookPro9,2               | [02d47ceb31](https://linux-hardware.org/?probe=02d47ceb31) | May 05, 2020 |
| Gateway       | NE56R                       | [6d4a0dd1b6](https://linux-hardware.org/?probe=6d4a0dd1b6) | May 04, 2020 |
| Gateway       | NE56R                       | [2910284c56](https://linux-hardware.org/?probe=2910284c56) | May 03, 2020 |
| Notebook      | N15_17RF                    | [3ec814dabd](https://linux-hardware.org/?probe=3ec814dabd) | May 01, 2020 |
| Toshiba       | dynabook Satellite B551/... | [b0ec3775c4](https://linux-hardware.org/?probe=b0ec3775c4) | Apr 29, 2020 |
| Lenovo        | ThinkPad Edge E130 3358C... | [2bc6ee441e](https://linux-hardware.org/?probe=2bc6ee441e) | Apr 29, 2020 |
| HP            | EliteBook 2570p             | [8481b529ee](https://linux-hardware.org/?probe=8481b529ee) | Apr 28, 2020 |
| HP            | Pavilion dv7                | [12f72e240a](https://linux-hardware.org/?probe=12f72e240a) | Apr 28, 2020 |
| Toshiba       | dynabook BX/571KW           | [9ba95d923c](https://linux-hardware.org/?probe=9ba95d923c) | Apr 22, 2020 |
| ASUSTek       | X45U                        | [0ce069357c](https://linux-hardware.org/?probe=0ce069357c) | Apr 18, 2020 |
| Acer          | Aspire A515-43              | [4eda844896](https://linux-hardware.org/?probe=4eda844896) | Apr 15, 2020 |
| Toshiba       | dynabook BX/571KW           | [b8dba9c83d](https://linux-hardware.org/?probe=b8dba9c83d) | Apr 13, 2020 |
| Intel         | CAPELL VALLEY CRB           | [2d21b4d154](https://linux-hardware.org/?probe=2d21b4d154) | Apr 12, 2020 |
| Dell          | Inspiron 3541               | [a1569c7977](https://linux-hardware.org/?probe=a1569c7977) | Apr 09, 2020 |
| Dell          | Inspiron 3541               | [6c900e8ddf](https://linux-hardware.org/?probe=6c900e8ddf) | Apr 09, 2020 |
| NEC Comput... | PC-LL550KG6GN               | [bc1a12a76f](https://linux-hardware.org/?probe=bc1a12a76f) | Mar 26, 2020 |
| Fujitsu       | FARQ06012Z                  | [6d19311f7e](https://linux-hardware.org/?probe=6d19311f7e) | Mar 23, 2020 |
| Lenovo        | ThinkPad T500 208843J       | [f221fcd053](https://linux-hardware.org/?probe=f221fcd053) | Mar 19, 2020 |
| Dell          | Inspiron 1545               | [cd22cce33d](https://linux-hardware.org/?probe=cd22cce33d) | Mar 12, 2020 |
| Dell          | Inspiron 1545               | [1cd8601a1e](https://linux-hardware.org/?probe=1cd8601a1e) | Mar 12, 2020 |
| HP            | ProBook 4320s               | [92478c20d5](https://linux-hardware.org/?probe=92478c20d5) | Mar 11, 2020 |
| Acer          | Aspire V3-571               | [82955eaaa3](https://linux-hardware.org/?probe=82955eaaa3) | Mar 10, 2020 |
| HP            | ProBook 4320s               | [96b40c5d0e](https://linux-hardware.org/?probe=96b40c5d0e) | Mar 05, 2020 |
| Acer          | Aspire V3-571               | [218d6c9bea](https://linux-hardware.org/?probe=218d6c9bea) | Mar 04, 2020 |
| HP            | Pavilion dv4                | [1e248b227a](https://linux-hardware.org/?probe=1e248b227a) | Feb 24, 2020 |
| Dell          | Inspiron 7380               | [2f37de4f3d](https://linux-hardware.org/?probe=2f37de4f3d) | Feb 23, 2020 |
| Dell          | Inspiron 7380               | [82f783a4d6](https://linux-hardware.org/?probe=82f783a4d6) | Feb 23, 2020 |
| ASUSTek       | 1005HA                      | [f668a6c2b8](https://linux-hardware.org/?probe=f668a6c2b8) | Feb 23, 2020 |
| Dell          | Inspiron 7380               | [a82beef9a1](https://linux-hardware.org/?probe=a82beef9a1) | Feb 23, 2020 |
| ASUSTek       | UX301LAA                    | [e994e96768](https://linux-hardware.org/?probe=e994e96768) | Feb 21, 2020 |
| ASUSTek       | UX301LAA                    | [4babc87322](https://linux-hardware.org/?probe=4babc87322) | Feb 21, 2020 |
| ASUSTek       | UX301LAA                    | [da5b70c7c6](https://linux-hardware.org/?probe=da5b70c7c6) | Feb 21, 2020 |
| HP            | Pavilion dv4                | [45555d85c3](https://linux-hardware.org/?probe=45555d85c3) | Feb 20, 2020 |
| Toshiba       | dynabook EX/55LWH           | [8da363dbd2](https://linux-hardware.org/?probe=8da363dbd2) | Feb 20, 2020 |
| HP            | ENVY Laptop 13-ah0xxx       | [d19eb25691](https://linux-hardware.org/?probe=d19eb25691) | Feb 15, 2020 |
| NEC Comput... | PC-VY25AACZ9                | [87e4d3dd9a](https://linux-hardware.org/?probe=87e4d3dd9a) | Feb 14, 2020 |
| Sharp         | PC-WE/WT Series             | [6d4ad9101d](https://linux-hardware.org/?probe=6d4ad9101d) | Feb 11, 2020 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [1ca6b6f436](https://linux-hardware.org/?probe=1ca6b6f436) | Jan 20, 2020 |
| Dell          | Inspiron 5485               | [fe8b986757](https://linux-hardware.org/?probe=fe8b986757) | Jan 19, 2020 |
| Dell          | XPS 13 7390                 | [b7f175312b](https://linux-hardware.org/?probe=b7f175312b) | Jan 15, 2020 |
| Dell          | XPS 13 7390                 | [430e5271de](https://linux-hardware.org/?probe=430e5271de) | Jan 15, 2020 |
| Toshiba       | dynabook CX/47H             | [f9cf94b130](https://linux-hardware.org/?probe=f9cf94b130) | Jan 14, 2020 |
| Toshiba       | dynabook CX/47H             | [15ce1a1178](https://linux-hardware.org/?probe=15ce1a1178) | Jan 14, 2020 |
| MSI           | GF72 8RE                    | [11ba6c28b8](https://linux-hardware.org/?probe=11ba6c28b8) | Jan 13, 2020 |
| Lenovo        | ThinkPad X395 20NLCTO1WW    | [1a78f67963](https://linux-hardware.org/?probe=1a78f67963) | Jan 05, 2020 |
| Lenovo        | ThinkPad X395 20NLCTO1WW    | [d8e43b34cc](https://linux-hardware.org/?probe=d8e43b34cc) | Jan 01, 2020 |
| Sony          | SVP1121A1J                  | [588b4f5ea9](https://linux-hardware.org/?probe=588b4f5ea9) | Dec 31, 2019 |
| Fujitsu       | FMVNFB40J                   | [0bfe715962](https://linux-hardware.org/?probe=0bfe715962) | Dec 30, 2019 |
| Dell          | Inspiron MM061              | [ab555162c8](https://linux-hardware.org/?probe=ab555162c8) | Dec 22, 2019 |
| NEC Comput... | PC-VY25AACZ9                | [67db0cd3e1](https://linux-hardware.org/?probe=67db0cd3e1) | Dec 12, 2019 |
| HP            | ProBook 6570b               | [567e5e5444](https://linux-hardware.org/?probe=567e5e5444) | Dec 06, 2019 |
| HP            | ProBook 6570b               | [12e166c17a](https://linux-hardware.org/?probe=12e166c17a) | Dec 06, 2019 |
| HP            | ProBook 4310s               | [d67761b5c2](https://linux-hardware.org/?probe=d67761b5c2) | Dec 04, 2019 |
| Novastar      | KL55                        | [277007d50c](https://linux-hardware.org/?probe=277007d50c) | Dec 03, 2019 |
| Novastar      | KL55                        | [d390f7576c](https://linux-hardware.org/?probe=d390f7576c) | Nov 20, 2019 |
| Novastar      | KL55                        | [9d09caf5c5](https://linux-hardware.org/?probe=9d09caf5c5) | Nov 19, 2019 |
| Novastar      | KL55                        | [3a8b42421b](https://linux-hardware.org/?probe=3a8b42421b) | Nov 18, 2019 |
| Novastar      | KL55                        | [e293c143c1](https://linux-hardware.org/?probe=e293c143c1) | Nov 18, 2019 |
| ASUSTek       | E203NA                      | [103ca8741c](https://linux-hardware.org/?probe=103ca8741c) | Nov 03, 2019 |
| HP            | ProBook 4530s               | [d6f9cecdc5](https://linux-hardware.org/?probe=d6f9cecdc5) | Nov 03, 2019 |
| Clevo         | W240HU/W250HUQ              | [c38e15b8e9](https://linux-hardware.org/?probe=c38e15b8e9) | Oct 15, 2019 |
| ASUSTek       | E203NA                      | [1e18143757](https://linux-hardware.org/?probe=1e18143757) | Oct 07, 2019 |
| ASUSTek       | X200MA                      | [d41d8e1f91](https://linux-hardware.org/?probe=d41d8e1f91) | Oct 07, 2019 |
| HASEE Comp... | P65xRP                      | [343291949a](https://linux-hardware.org/?probe=343291949a) | Oct 03, 2019 |
| Panasonic     | CF-J10YYBHR                 | [e00043a374](https://linux-hardware.org/?probe=e00043a374) | Sep 27, 2019 |
| Dell          | Inspiron 15-3565            | [6ebeac4bcd](https://linux-hardware.org/?probe=6ebeac4bcd) | Sep 27, 2019 |
| Dell          | Inspiron 15-3565            | [55ae5ff063](https://linux-hardware.org/?probe=55ae5ff063) | Sep 25, 2019 |
| Dell          | Inspiron 15-3565            | [90d49c8abd](https://linux-hardware.org/?probe=90d49c8abd) | Sep 25, 2019 |
| Lenovo        | G570 4334                   | [eefedc7e75](https://linux-hardware.org/?probe=eefedc7e75) | Sep 06, 2019 |
| Lenovo        | G570 4334                   | [66750ab32f](https://linux-hardware.org/?probe=66750ab32f) | Sep 04, 2019 |
| Lenovo        | G570 4334                   | [4a4a5fe410](https://linux-hardware.org/?probe=4a4a5fe410) | Sep 04, 2019 |
| ASUSTek       | X200MA                      | [aec3d01ee9](https://linux-hardware.org/?probe=aec3d01ee9) | Aug 28, 2019 |
| ASUSTek       | E203NA                      | [187729d926](https://linux-hardware.org/?probe=187729d926) | Aug 27, 2019 |
| Panasonic     | CF-J10YYBHR                 | [0005e1a411](https://linux-hardware.org/?probe=0005e1a411) | Aug 21, 2019 |
| ASUSTek       | E203NA                      | [eb4b2d2e3e](https://linux-hardware.org/?probe=eb4b2d2e3e) | Aug 15, 2019 |
| Dell          | Latitude E6500              | [cb9f268650](https://linux-hardware.org/?probe=cb9f268650) | Aug 12, 2019 |
| Fujitsu       | FMVNC6BE3                   | [24f8a2b045](https://linux-hardware.org/?probe=24f8a2b045) | Aug 10, 2019 |
| Fujitsu       | FMVNC6BE3                   | [b2a7c69d92](https://linux-hardware.org/?probe=b2a7c69d92) | Jul 25, 2019 |
| Lenovo        | ThinkPad X121e 30456FJ      | [974cf0c5c6](https://linux-hardware.org/?probe=974cf0c5c6) | Jul 24, 2019 |
| Dell          | Inspiron 15-3552            | [ce847df44a](https://linux-hardware.org/?probe=ce847df44a) | Jul 21, 2019 |
| HP            | Compaq 6720s                | [48ee31d6e9](https://linux-hardware.org/?probe=48ee31d6e9) | Jul 16, 2019 |
| Dell          | Latitude E6320              | [a45c07429f](https://linux-hardware.org/?probe=a45c07429f) | Jun 24, 2019 |
| Toshiba       | dynabook Satellite B552/... | [5d0ae356dd](https://linux-hardware.org/?probe=5d0ae356dd) | Jun 17, 2019 |
| SLIMBOOK      | PRO                         | [741aadd99e](https://linux-hardware.org/?probe=741aadd99e) | Jun 12, 2019 |
| Alienware     | 17 R5                       | [8b270d4228](https://linux-hardware.org/?probe=8b270d4228) | May 30, 2019 |
| Lenovo        | ThinkPad Edge E530 32599... | [23f78cf853](https://linux-hardware.org/?probe=23f78cf853) | May 28, 2019 |
| Acer          | Swift SF314-54              | [e682a05a1f](https://linux-hardware.org/?probe=e682a05a1f) | May 27, 2019 |
| Acer          | Swift SF314-54              | [167c038742](https://linux-hardware.org/?probe=167c038742) | May 27, 2019 |
| Fujitsu       | FMVWW11W                    | [2462f0f0bb](https://linux-hardware.org/?probe=2462f0f0bb) | May 25, 2019 |
| Toshiba       | Satellite A135              | [bc24647b76](https://linux-hardware.org/?probe=bc24647b76) | May 18, 2019 |
| Toshiba       | Satellite A135              | [fa5218ef36](https://linux-hardware.org/?probe=fa5218ef36) | May 16, 2019 |
| Apple         | MacBookPro9,2               | [e4d60349c2](https://linux-hardware.org/?probe=e4d60349c2) | May 01, 2019 |
| Lenovo        | 41872PU                     | [61cd8222cf](https://linux-hardware.org/?probe=61cd8222cf) | Apr 15, 2019 |
| Apple         | MacBookPro9,2               | [0c238b6751](https://linux-hardware.org/?probe=0c238b6751) | Apr 07, 2019 |
| Dell          | Inspiron 1210               | [7d4473a4a5](https://linux-hardware.org/?probe=7d4473a4a5) | Apr 07, 2019 |
| Dell          | G7 7588                     | [d38fee8e21](https://linux-hardware.org/?probe=d38fee8e21) | Mar 29, 2019 |
| HP            | Mini 5103                   | [266d78e723](https://linux-hardware.org/?probe=266d78e723) | Mar 25, 2019 |
| HP            | Laptop 15-db0xxx            | [c5c58d8655](https://linux-hardware.org/?probe=c5c58d8655) | Mar 23, 2019 |
| HP            | Laptop 15-db0xxx            | [c4d37bac1a](https://linux-hardware.org/?probe=c4d37bac1a) | Mar 17, 2019 |
| HP            | Laptop 15-db0xxx            | [3159028860](https://linux-hardware.org/?probe=3159028860) | Mar 17, 2019 |
| Teclast       | F6 Pro                      | [afaad4db96](https://linux-hardware.org/?probe=afaad4db96) | Mar 15, 2019 |
| Lenovo        | ThinkPad SL410 2842CTO      | [f577d3875e](https://linux-hardware.org/?probe=f577d3875e) | Mar 04, 2019 |
| NEC Comput... | PC-LL750RG                  | [f3208d8466](https://linux-hardware.org/?probe=f3208d8466) | Mar 03, 2019 |
| Dell          | Latitude E6320              | [04f301dc20](https://linux-hardware.org/?probe=04f301dc20) | Feb 27, 2019 |
| Panasonic     | CF-S9JWECPS                 | [fd3dd464f1](https://linux-hardware.org/?probe=fd3dd464f1) | Feb 11, 2019 |
| Lenovo        | ThinkPad E450c 20EHA00NC... | [deac2364d1](https://linux-hardware.org/?probe=deac2364d1) | Jan 30, 2019 |
| Fujitsu       | FMVU93B3BZ                  | [974550aea3](https://linux-hardware.org/?probe=974550aea3) | Jan 30, 2019 |
| Lenovo        | ThinkPad E450c 20EHA00NC... | [1629601591](https://linux-hardware.org/?probe=1629601591) | Jan 30, 2019 |
| Acer          | TravelMate 5730             | [3f204613cc](https://linux-hardware.org/?probe=3f204613cc) | Jan 13, 2019 |
| Fujitsu       | FMVNE4N1E                   | [8e2c99692b](https://linux-hardware.org/?probe=8e2c99692b) | Dec 29, 2018 |
| HP            | Notebook                    | [b73435f113](https://linux-hardware.org/?probe=b73435f113) | Dec 24, 2018 |
| HP            | Notebook                    | [5f943855ce](https://linux-hardware.org/?probe=5f943855ce) | Dec 24, 2018 |
| NEC Comput... | PC-LL550LG1K                | [004a3c19de](https://linux-hardware.org/?probe=004a3c19de) | Dec 09, 2018 |
| NEC Comput... | PC-LL550LG1K                | [80d5cca3f0](https://linux-hardware.org/?probe=80d5cca3f0) | Dec 09, 2018 |
| Sony          | VGN-FT31B                   | [7f0bb0cc92](https://linux-hardware.org/?probe=7f0bb0cc92) | Dec 06, 2018 |
| Sony          | VGN-N50HB                   | [8938dd9a9e](https://linux-hardware.org/?probe=8938dd9a9e) | Nov 11, 2018 |
| ASUSTek       | X551MA                      | [5806ab1f9f](https://linux-hardware.org/?probe=5806ab1f9f) | Oct 24, 2018 |
| Dell          | Latitude E6500              | [d3c051f562](https://linux-hardware.org/?probe=d3c051f562) | Feb 26, 2018 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Japan/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 86        | 19.72%  |
| Ubuntu 18.04        | 46        | 10.55%  |
| OpenMandriva 4.3    | 21        | 4.82%   |
| OpenMandriva 4.2    | 18        | 4.13%   |
| Debian 11           | 11        | 2.52%   |
| BlackPanther 18.1   | 11        | 2.52%   |
| Arch                | 11        | 2.52%   |
| OpenMandriva 4.90   | 10        | 2.29%   |
| Ubuntu 22.04        | 9         | 2.06%   |
| Zorin 16            | 8         | 1.83%   |
| Xubuntu 20.04       | 8         | 1.83%   |
| Zorin 15            | 7         | 1.61%   |
| Xubuntu 18.04       | 7         | 1.61%   |
| Ubuntu 21.04        | 7         | 1.61%   |
| Pop!_OS 20.10       | 7         | 1.61%   |
| Manjaro             | 7         | 1.61%   |
| Linux Mint 19.3     | 7         | 1.61%   |
| Arch Rolling        | 7         | 1.61%   |
| Fedora 35           | 6         | 1.38%   |
| Ubuntu 19.10        | 5         | 1.15%   |
| Fedora 36           | 5         | 1.15%   |
| Fedora 32           | 5         | 1.15%   |
| Ubuntu Unity 16.04  | 4         | 0.92%   |
| Ubuntu 21.10        | 4         | 0.92%   |
| Ubuntu 20.10        | 4         | 0.92%   |
| Ubuntu 19.04        | 4         | 0.92%   |
| Ubuntu 16.04        | 4         | 0.92%   |
| OpenMandriva 4.50   | 4         | 0.92%   |
| Linux Mint 20.2     | 4         | 0.92%   |
| Ubuntu Unity 18.04  | 3         | 0.69%   |
| Pop!_OS 21.04       | 3         | 0.69%   |
| Peppermint 10       | 3         | 0.69%   |
| Linux Mint 20.3     | 3         | 0.69%   |
| KDE neon 20.04      | 3         | 0.69%   |
| Guix                | 3         | 0.69%   |
| Gentoo 2.7          | 3         | 0.69%   |
| ArcoLinux Rolling   | 3         | 0.69%   |
| Ubuntu Budgie 20.04 | 2         | 0.46%   |
| Slackware 15.0      | 2         | 0.46%   |
| ROSA R10            | 2         | 0.46%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 167       | 39.29%  |
| OpenMandriva  | 52        | 12.24%  |
| Fedora        | 21        | 4.94%   |
| Linux Mint    | 19        | 4.47%   |
| Arch          | 18        | 4.24%   |
| Xubuntu       | 16        | 3.76%   |
| Debian        | 16        | 3.76%   |
| Zorin         | 15        | 3.53%   |
| Pop!_OS       | 15        | 3.53%   |
| Manjaro       | 12        | 2.82%   |
| BlackPanther  | 11        | 2.59%   |
| Ubuntu Unity  | 7         | 1.65%   |
| Gentoo        | 5         | 1.18%   |
| Kubuntu       | 4         | 0.94%   |
| Slackware     | 3         | 0.71%   |
| ROSA          | 3         | 0.71%   |
| Peppermint    | 3         | 0.71%   |
| KDE neon      | 3         | 0.71%   |
| Guix          | 3         | 0.71%   |
| Deepin        | 3         | 0.71%   |
| ArcoLinux     | 3         | 0.71%   |
| Ubuntu Budgie | 2         | 0.47%   |
| RHEL          | 2         | 0.47%   |
| Lubuntu       | 2         | 0.47%   |
| LMDE          | 2         | 0.47%   |
| Kali          | 2         | 0.47%   |
| Endless       | 2         | 0.47%   |
| Elementary    | 2         | 0.47%   |
| CentOS        | 2         | 0.47%   |
| antiX         | 2         | 0.47%   |
| SystemRescue  | 1         | 0.24%   |
| SteamOS       | 1         | 0.24%   |
| Sparky        | 1         | 0.24%   |
| Solus         | 1         | 0.24%   |
| Plamo         | 1         | 0.24%   |
| openSUSE      | 1         | 0.24%   |
| Garuda Linux  | 1         | 0.24%   |
| Feren OS      | 1         | 0.24%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 20        | 4.1%    |
| 5.10.14-desktop-1omv4002 | 17        | 3.48%   |
| 5.4.0-42-generic         | 13        | 2.66%   |
| 5.4.0-52-generic         | 11        | 2.25%   |
| 5.4.0-58-generic         | 8         | 1.64%   |
| 4.18.16-desktop-1bP      | 8         | 1.64%   |
| 5.4.0-48-generic         | 7         | 1.43%   |
| 5.8.0-48-generic         | 6         | 1.23%   |
| 5.0.0-37-generic         | 6         | 1.23%   |
| 5.8.0-7642-generic       | 5         | 1.02%   |
| 5.8.0-43-generic         | 5         | 1.02%   |
| 5.3.0-40-generic         | 5         | 1.02%   |
| 5.19.1-desktop-1omv4090  | 5         | 1.02%   |
| 5.13.0-27-generic        | 5         | 1.02%   |
| 5.8.0-50-generic         | 4         | 0.82%   |
| 5.6.14-desktop-2bP       | 4         | 0.82%   |
| 5.4.0-40-generic         | 4         | 0.82%   |
| 5.12.4-desktop-1omv4050  | 4         | 0.82%   |
| 5.11.0-37-generic        | 4         | 0.82%   |
| 5.11.0-27-generic        | 4         | 0.82%   |
| 4.18.0-25-generic        | 4         | 0.82%   |
| 5.8.0-45-generic         | 3         | 0.61%   |
| 5.4.0-73-generic         | 3         | 0.61%   |
| 5.4.0-65-generic         | 3         | 0.61%   |
| 5.4.0-51-generic         | 3         | 0.61%   |
| 5.4.0-47-generic         | 3         | 0.61%   |
| 5.4.0-39-generic         | 3         | 0.61%   |
| 5.4.0-31-generic         | 3         | 0.61%   |
| 5.4.0-28-generic         | 3         | 0.61%   |
| 5.3.0-28-generic         | 3         | 0.61%   |
| 5.18.12-desktop-3omv4090 | 3         | 0.61%   |
| 5.16.11-76051611-generic | 3         | 0.61%   |
| 5.13.0-41-generic        | 3         | 0.61%   |
| 5.11.0-40-generic        | 3         | 0.61%   |
| 5.11.0-38-generic        | 3         | 0.61%   |
| 5.11.0-25-generic        | 3         | 0.61%   |
| 5.10.0-13-amd64          | 3         | 0.61%   |
| 5.0.0-25-generic         | 3         | 0.61%   |
| 5.0.0-15-generic         | 3         | 0.61%   |
| 4.15.0-55-generic        | 3         | 0.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 91        | 19.65%  |
| 4.15.0  | 36        | 7.78%   |
| 5.8.0   | 34        | 7.34%   |
| 5.11.0  | 27        | 5.83%   |
| 5.13.0  | 24        | 5.18%   |
| 5.16.7  | 21        | 4.54%   |
| 5.3.0   | 20        | 4.32%   |
| 5.10.14 | 17        | 3.67%   |
| 5.0.0   | 17        | 3.67%   |
| 5.10.0  | 13        | 2.81%   |
| 5.15.0  | 9         | 1.94%   |
| 4.18.0  | 9         | 1.94%   |
| 4.18.16 | 8         | 1.73%   |
| 5.19.1  | 6         | 1.3%    |
| 4.4.0   | 5         | 1.08%   |
| 5.6.14  | 4         | 0.86%   |
| 5.16.11 | 4         | 0.86%   |
| 5.12.4  | 4         | 0.86%   |
| 4.19.0  | 4         | 0.86%   |
| 5.8.13  | 3         | 0.65%   |
| 5.19.8  | 3         | 0.65%   |
| 5.19.11 | 3         | 0.65%   |
| 5.18.12 | 3         | 0.65%   |
| 5.18.0  | 3         | 0.65%   |
| 5.14.0  | 3         | 0.65%   |
| 5.9.0   | 2         | 0.43%   |
| 5.19.0  | 2         | 0.43%   |
| 5.18.5  | 2         | 0.43%   |
| 5.18.13 | 2         | 0.43%   |
| 5.16.18 | 2         | 0.43%   |
| 5.15.10 | 2         | 0.43%   |
| 5.14.10 | 2         | 0.43%   |
| 5.13.19 | 2         | 0.43%   |
| 4.9.60  | 2         | 0.43%   |
| 5.9.16  | 1         | 0.22%   |
| 5.9.12  | 1         | 0.22%   |
| 5.8.9   | 1         | 0.22%   |
| 5.8.4   | 1         | 0.22%   |
| 5.8.18  | 1         | 0.22%   |
| 5.8.16  | 1         | 0.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 98        | 21.26%  |
| 5.8     | 41        | 8.89%   |
| 5.10    | 38        | 8.24%   |
| 4.15    | 36        | 7.81%   |
| 5.16    | 32        | 6.94%   |
| 5.13    | 31        | 6.72%   |
| 5.11    | 30        | 6.51%   |
| 5.3     | 20        | 4.34%   |
| 5.0     | 18        | 3.9%    |
| 5.19    | 17        | 3.69%   |
| 5.15    | 17        | 3.69%   |
| 4.18    | 17        | 3.69%   |
| 5.18    | 15        | 3.25%   |
| 5.14    | 9         | 1.95%   |
| 5.6     | 8         | 1.74%   |
| 5.12    | 8         | 1.74%   |
| 5.17    | 5         | 1.08%   |
| 4.4     | 5         | 1.08%   |
| 4.19    | 5         | 1.08%   |
| 5.9     | 4         | 0.87%   |
| 4.9     | 4         | 0.87%   |
| 5.7     | 2         | 0.43%   |
| 3.10    | 1         | 0.22%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 390       | 93.75%  |
| i686   | 26        | 6.25%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 184       | 43.6%   |
| KDE5       | 83        | 19.67%  |
| Unknown    | 54        | 12.8%   |
| XFCE       | 40        | 9.48%   |
| X-Cinnamon | 12        | 2.84%   |
| MATE       | 8         | 1.9%    |
| Unity      | 7         | 1.66%   |
| LXDE       | 6         | 1.42%   |
| KDE        | 6         | 1.42%   |
| Deepin     | 3         | 0.71%   |
| Cinnamon   | 3         | 0.71%   |
| Budgie     | 3         | 0.71%   |
| sway       | 2         | 0.47%   |
| Pantheon   | 2         | 0.47%   |
| icewm      | 2         | 0.47%   |
| awesome    | 2         | 0.47%   |
| XSession   | 1         | 0.24%   |
| xmonad     | 1         | 0.24%   |
| LXQt       | 1         | 0.24%   |
| KDE4       | 1         | 0.24%   |
| i3         | 1         | 0.24%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 342       | 80.85%  |
| Wayland | 48        | 11.35%  |
| Unknown | 27        | 6.38%   |
| Tty     | 6         | 1.42%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 223       | 52.1%   |
| SDDM    | 82        | 19.16%  |
| GDM     | 52        | 12.15%  |
| GDM3    | 27        | 6.31%   |
| LightDM | 25        | 5.84%   |
| TDM     | 14        | 3.27%   |
| XDM     | 3         | 0.7%    |
| LXDM    | 1         | 0.23%   |
| KDM     | 1         | 0.23%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| ja_JP   | 165       | 38.55%  |
| en_US   | 151       | 35.28%  |
| Unknown | 61        | 14.25%  |
| pt_BR   | 11        | 2.57%   |
| en_GB   | 11        | 2.57%   |
| zh_CN   | 7         | 1.64%   |
| C       | 5         | 1.17%   |
| zh_TW   | 2         | 0.47%   |
| ru_RU   | 2         | 0.47%   |
| fr_FR   | 2         | 0.47%   |
| sv_SE   | 1         | 0.23%   |
| sk_SK   | 1         | 0.23%   |
| pl_PL   | 1         | 0.23%   |
| nb_NO   | 1         | 0.23%   |
| fi_FI   | 1         | 0.23%   |
| es_GT   | 1         | 0.23%   |
| es_ES   | 1         | 0.23%   |
| en_SG   | 1         | 0.23%   |
| en_PH   | 1         | 0.23%   |
| en_NL   | 1         | 0.23%   |
| en_AU   | 1         | 0.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 213       | 50.59%  |
| EFI  | 208       | 49.41%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 326       | 77.62%  |
| Overlay | 43        | 10.24%  |
| Btrfs   | 33        | 7.86%   |
| Unknown | 9         | 2.14%   |
| Xfs     | 4         | 0.95%   |
| Zfs     | 3         | 0.71%   |
| Ntfs    | 1         | 0.24%   |
| F2fs    | 1         | 0.24%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 238       | 55.74%  |
| GPT     | 141       | 33.02%  |
| MBR     | 48        | 11.24%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 340       | 79.81%  |
| Yes       | 86        | 20.19%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 314       | 74.94%  |
| Yes       | 105       | 25.06%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 75        | 18.03%  |
| Dell                | 52        | 12.5%   |
| Toshiba             | 43        | 10.34%  |
| Hewlett-Packard     | 40        | 9.62%   |
| ASUSTek Computer    | 31        | 7.45%   |
| Fujitsu             | 28        | 6.73%   |
| NEC Computers       | 22        | 5.29%   |
| Apple               | 18        | 4.33%   |
| Acer                | 15        | 3.61%   |
| Panasonic           | 12        | 2.88%   |
| Sony                | 10        | 2.4%    |
| MouseComputer       | 7         | 1.68%   |
| MSI                 | 5         | 1.2%    |
| Novastar            | 4         | 0.96%   |
| HUAWEI              | 4         | 0.96%   |
| Alienware           | 4         | 0.96%   |
| Unknown             | 4         | 0.96%   |
| System76            | 3         | 0.72%   |
| Notebook            | 3         | 0.72%   |
| Gateway             | 3         | 0.72%   |
| Dynabook            | 3         | 0.72%   |
| UNITCOM             | 2         | 0.48%   |
| Timi                | 2         | 0.48%   |
| Thirdwave           | 2         | 0.48%   |
| SLIMBOOK            | 2         | 0.48%   |
| Samsung Electronics | 2         | 0.48%   |
| Hampoo              | 2         | 0.48%   |
| EPSON DIRECT        | 2         | 0.48%   |
| TUXEDO              | 1         | 0.24%   |
| Teclast             | 1         | 0.24%   |
| Sharp               | 1         | 0.24%   |
| Razer               | 1         | 0.24%   |
| R.W.C               | 1         | 0.24%   |
| Purism              | 1         | 0.24%   |
| Maibenben           | 1         | 0.24%   |
| KOUZIRO             | 1         | 0.24%   |
| Jumper              | 1         | 0.24%   |
| Intel               | 1         | 0.24%   |
| HASEE Computer      | 1         | 0.24%   |
| Google              | 1         | 0.24%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Toshiba dynabook T653/46JR        | 7         | 1.68%   |
| Toshiba dynabook Satellite B552/G | 5         | 1.2%    |
| Novastar KL55                     | 4         | 0.96%   |
| Apple MacBookPro9,2               | 4         | 0.96%   |
| Unknown                           | 4         | 0.96%   |
| Lenovo G570 4334                  | 3         | 0.72%   |
| Toshiba dynabook R73/BN           | 2         | 0.48%   |
| System76 Lemur Pro                | 2         | 0.48%   |
| Panasonic CF-S10EYADR             | 2         | 0.48%   |
| Lenovo ThinkPad X230 2325SSF      | 2         | 0.48%   |
| HP ProBook 6570b                  | 2         | 0.48%   |
| HP ProBook 6560b                  | 2         | 0.48%   |
| HP ProBook 6550b                  | 2         | 0.48%   |
| HP Pavilion dv4                   | 2         | 0.48%   |
| HP Notebook                       | 2         | 0.48%   |
| HP Laptop 15-db0xxx               | 2         | 0.48%   |
| Hampoo C3W6_AP108_4GB             | 2         | 0.48%   |
| Gateway NE56R                     | 2         | 0.48%   |
| Dell XPS 15 9500                  | 2         | 0.48%   |
| Dell XPS 13 9360                  | 2         | 0.48%   |
| Dell Latitude E6320               | 2         | 0.48%   |
| Dell Inspiron 1545                | 2         | 0.48%   |
| Dell Inspiron 11-3162             | 2         | 0.48%   |
| Dell G3 3500                      | 2         | 0.48%   |
| ASUS ROG Strix G733ZX_G733ZX      | 2         | 0.48%   |
| Apple MacBookPro5,5               | 2         | 0.48%   |
| Apple MacBookPro15,1              | 2         | 0.48%   |
| Acer Swift SF314-54               | 2         | 0.48%   |
| Acer Aspire V3-571                | 2         | 0.48%   |
| UNITCOM W55xEU                    | 1         | 0.24%   |
| UNITCOM W35_37ET                  | 1         | 0.24%   |
| TUXEDO P95_HR                     | 1         | 0.24%   |
| Toshiba Satellite A135            | 1         | 0.24%   |
| Toshiba PORTEGE Z930              | 1         | 0.24%   |
| Toshiba PORTEGE Z20t-C            | 1         | 0.24%   |
| Toshiba dynabook T954/89L         | 1         | 0.24%   |
| Toshiba dynabook T75/RW           | 1         | 0.24%   |
| Toshiba dynabook T554/56KW        | 1         | 0.24%   |
| Toshiba dynabook T55/PW           | 1         | 0.24%   |
| Toshiba dynabook T45/VRS          | 1         | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 52        | 12.5%   |
| Toshiba dynabook      | 40        | 9.62%   |
| Dell Inspiron         | 22        | 5.29%   |
| HP ProBook            | 14        | 3.37%   |
| Dell Latitude         | 12        | 2.88%   |
| Dell XPS              | 10        | 2.4%    |
| Acer Aspire           | 10        | 2.4%    |
| HP Pavilion           | 7         | 1.68%   |
| Lenovo ThinkBook      | 5         | 1.2%    |
| HP EliteBook          | 5         | 1.2%    |
| ASUS VivoBook         | 5         | 1.2%    |
| ASUS ROG              | 5         | 1.2%    |
| Novastar KL55         | 4         | 0.96%   |
| Lenovo IdeaPad        | 4         | 0.96%   |
| Apple MacBookPro9     | 4         | 0.96%   |
| Unknown               | 4         | 0.96%   |
| Lenovo G570           | 3         | 0.72%   |
| HP Laptop             | 3         | 0.72%   |
| HP ENVY               | 3         | 0.72%   |
| Dell G3               | 3         | 0.72%   |
| Toshiba PORTEGE       | 2         | 0.48%   |
| Timi RedmiBook        | 2         | 0.48%   |
| System76 Lemur        | 2         | 0.48%   |
| Panasonic CF-S10EYADR | 2         | 0.48%   |
| HP Notebook           | 2         | 0.48%   |
| Hampoo C3W6           | 2         | 0.48%   |
| Gateway NE56R         | 2         | 0.48%   |
| EPSON DIRECT Endeavor | 2         | 0.48%   |
| Dell Vostro           | 2         | 0.48%   |
| ASUS ZenBook          | 2         | 0.48%   |
| ASUS TUF              | 2         | 0.48%   |
| Apple MacBookPro5     | 2         | 0.48%   |
| Apple MacBookPro15    | 2         | 0.48%   |
| Apple MacBookPro11    | 2         | 0.48%   |
| Alienware 17          | 2         | 0.48%   |
| Acer Swift            | 2         | 0.48%   |
| UNITCOM W55xEU        | 1         | 0.24%   |
| UNITCOM W35           | 1         | 0.24%   |
| TUXEDO P95            | 1         | 0.24%   |
| Toshiba Satellite     | 1         | 0.24%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2012    | 50        | 12.02%  |
| 2018    | 39        | 9.38%   |
| 2020    | 38        | 9.13%   |
| 2011    | 36        | 8.65%   |
| 2019    | 35        | 8.41%   |
| 2021    | 28        | 6.73%   |
| 2010    | 26        | 6.25%   |
| 2009    | 24        | 5.77%   |
| 2016    | 23        | 5.53%   |
| 2013    | 23        | 5.53%   |
| 2015    | 21        | 5.05%   |
| 2008    | 19        | 4.57%   |
| 2014    | 14        | 3.37%   |
| 2007    | 14        | 3.37%   |
| 2017    | 13        | 3.13%   |
| 2006    | 6         | 1.44%   |
| 2022    | 5         | 1.2%    |
| 2005    | 1         | 0.24%   |
| Unknown | 1         | 0.24%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 416       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 378       | 89.57%  |
| Enabled  | 44        | 10.43%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 411       | 98.8%   |
| Yes  | 5         | 1.2%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 114       | 27.27%  |
| 3.01-4.0    | 107       | 25.6%   |
| 8.01-16.0   | 62        | 14.83%  |
| 16.01-24.0  | 54        | 12.92%  |
| 1.01-2.0    | 29        | 6.94%   |
| 32.01-64.0  | 24        | 5.74%   |
| 2.01-3.0    | 9         | 2.15%   |
| 24.01-32.0  | 7         | 1.67%   |
| 64.01-256.0 | 7         | 1.67%   |
| 0.51-1.0    | 5         | 1.2%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 186       | 41.06%  |
| 2.01-3.0   | 104       | 22.96%  |
| 0.51-1.0   | 59        | 13.02%  |
| 3.01-4.0   | 42        | 9.27%   |
| 4.01-8.0   | 39        | 8.61%   |
| 8.01-16.0  | 12        | 2.65%   |
| 0.01-0.5   | 10        | 2.21%   |
| 16.01-24.0 | 1         | 0.22%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 314       | 73.88%  |
| 2      | 101       | 23.76%  |
| 0      | 6         | 1.41%   |
| 3      | 4         | 0.94%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 241       | 57.79%  |
| Yes       | 176       | 42.21%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 341       | 81.97%  |
| No        | 75        | 18.03%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 402       | 96.63%  |
| No        | 14        | 3.37%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 265       | 63.25%  |
| No        | 154       | 36.75%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Japan   | 416       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City        | Notebooks | Percent |
|-------------|-----------|---------|
| Tokyo       | 41        | 9.17%   |
| Yokohama    | 26        | 5.82%   |
| Osaka       | 24        | 5.37%   |
| Minato-ku   | 13        | 2.91%   |
| Saitama     | 11        | 2.46%   |
| Shinjuku    | 10        | 2.24%   |
| Shibuya     | 10        | 2.24%   |
| Setagaya-ku | 9         | 2.01%   |
| Nagoya      | 9         | 2.01%   |
| Chiyoda     | 9         | 2.01%   |
| Honcho      | 8         | 1.79%   |
| Shinagawa   | 7         | 1.57%   |
| Sapporo     | 7         | 1.57%   |
| Kyoto       | 7         | 1.57%   |
| Niigata     | 6         | 1.34%   |
| Adachi      | 6         | 1.34%   |
| Kobe        | 5         | 1.12%   |
| Ichikawa    | 5         | 1.12%   |
| Ōtsu       | 4         | 0.89%   |
| Kitakyushu  | 4         | 0.89%   |
| Hiratsuka   | 4         | 0.89%   |
| Himeji      | 4         | 0.89%   |
| Bunkyo-ku   | 4         | 0.89%   |
| Utsunomiya  | 3         | 0.67%   |
| Shizuoka    | 3         | 0.67%   |
| Nagasaki    | 3         | 0.67%   |
| Morioka     | 3         | 0.67%   |
| Mito        | 3         | 0.67%   |
| Matsudo     | 3         | 0.67%   |
| Koto        | 3         | 0.67%   |
| Kodaira     | 3         | 0.67%   |
| Kawaguchi   | 3         | 0.67%   |
| Karasawa    | 3         | 0.67%   |
| Kagoshima   | 3         | 0.67%   |
| Inagi-shi   | 3         | 0.67%   |
| Hitachi     | 3         | 0.67%   |
| Chiba       | 3         | 0.67%   |
| Yamaguchi   | 2         | 0.45%   |
| Yamagata    | 2         | 0.45%   |
| Tsubame     | 2         | 0.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 64        | 87     | 12.93%  |
| Toshiba                   | 60        | 67     | 12.12%  |
| WDC                       | 51        | 60     | 10.3%   |
| Seagate                   | 38        | 47     | 7.68%   |
| Unknown                   | 34        | 45     | 6.87%   |
| SanDisk                   | 27        | 32     | 5.45%   |
| Crucial                   | 26        | 32     | 5.25%   |
| Hitachi                   | 21        | 22     | 4.24%   |
| Kingston                  | 17        | 19     | 3.43%   |
| SK hynix                  | 16        | 16     | 3.23%   |
| Micron Technology         | 11        | 18     | 2.22%   |
| Intel                     | 11        | 12     | 2.22%   |
| Apple                     | 11        | 12     | 2.22%   |
| HGST                      | 9         | 10     | 1.82%   |
| A-DATA Technology         | 9         | 11     | 1.82%   |
| SPCC                      | 7         | 10     | 1.41%   |
| KIOXIA                    | 7         | 9      | 1.41%   |
| Fujitsu                   | 7         | 8      | 1.41%   |
| Transcend                 | 5         | 7      | 1.01%   |
| SUNEAST                   | 5         | 6      | 1.01%   |
| Zheino                    | 4         | 5      | 0.81%   |
| Plextor                   | 4         | 6      | 0.81%   |
| China                     | 3         | 4      | 0.61%   |
| Unknown                   | 3         | 3      | 0.61%   |
| Team                      | 2         | 3      | 0.4%    |
| Silicon Motion            | 2         | 2      | 0.4%    |
| Ramaxel Technology        | 2         | 2      | 0.4%    |
| QC-FT-D                   | 2         | 2      | 0.4%    |
| Phison                    | 2         | 2      | 0.4%    |
| Patriot                   | 2         | 3      | 0.4%    |
| OCZ                       | 2         | 2      | 0.4%    |
| Micron/Crucial Technology | 2         | 2      | 0.4%    |
| KIOXIA-EXCERIA            | 2         | 3      | 0.4%    |
| Hewlett-Packard           | 2         | 2      | 0.4%    |
| Green House               | 2         | 4      | 0.4%    |
| Apacer                    | 2         | 4      | 0.4%    |
| Teclast                   | 1         | 1      | 0.2%    |
| TCSUNBOW                  | 1         | 1      | 0.2%    |
| PNY                       | 1         | 1      | 0.2%    |
| Oyen                      | 1         | 1      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Unknown MMC Card  64GB               | 8         | 1.56%   |
| Crucial CT500MX500SSD1 500GB         | 8         | 1.56%   |
| Toshiba MQ01ABD075 752GB             | 7         | 1.36%   |
| Unknown MMC Card  128GB              | 5         | 0.97%   |
| Seagate ST1000LM035-1RK172 1TB       | 5         | 0.97%   |
| Samsung NVMe SSD Drive 256GB         | 5         | 0.97%   |
| Toshiba MQ01ABF050 500GB             | 4         | 0.78%   |
| Toshiba MQ01ABD100 1TB               | 4         | 0.78%   |
| Samsung NVMe SSD Drive 1TB           | 4         | 0.78%   |
| Kingston RBUSNS4180S3256GJ 256GB SSD | 4         | 0.78%   |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 3         | 0.58%   |
| Unknown SD/MMC/MS PRO 2GB            | 3         | 0.58%   |
| Unknown NVMe SSD Drive 512GB         | 3         | 0.58%   |
| Unknown MMC Card  32GB               | 3         | 0.58%   |
| Unknown ASP550SS7-240GM-MI-B 240GB   | 3         | 0.58%   |
| Toshiba MQ01ABD100H 1TB              | 3         | 0.58%   |
| Seagate ST9500325AS 500GB            | 3         | 0.58%   |
| Seagate ST500LT012-1DG142 500GB      | 3         | 0.58%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 3         | 0.58%   |
| SanDisk NVMe SSD Drive 256GB         | 3         | 0.58%   |
| SanDisk Extreme SSD 500GB            | 3         | 0.58%   |
| Samsung SSD 860 QVO 1TB              | 3         | 0.58%   |
| Kingston OM8PCP3512F-AB 512GB        | 3         | 0.58%   |
| Intel NVMe SSD Drive 512GB           | 3         | 0.58%   |
| Crucial CT250MX500SSD1 250GB         | 3         | 0.58%   |
| Apple NVMe SSD Drive 256GB           | 3         | 0.58%   |
| Unknown                              | 3         | 0.58%   |
| WDC WDS100T2B0A-00SM50 1TB SSD       | 2         | 0.39%   |
| WDC WD5000LPVX-08V0TT5 500GB         | 2         | 0.39%   |
| WDC WD2500BPVT-26JJ5T0 250GB         | 2         | 0.39%   |
| WDC WD2500BEKT-60PVMT0 250GB         | 2         | 0.39%   |
| WDC WD10SPZX-22Z10T0 1TB             | 2         | 0.39%   |
| WDC WD10JPVX-22JC3T0 1TB             | 2         | 0.39%   |
| Toshiba THNSNJ128GCSU 128GB SSD      | 2         | 0.39%   |
| Toshiba THNSN9480GESG 480GB SSD      | 2         | 0.39%   |
| Toshiba NVMe SSD Drive 512GB         | 2         | 0.39%   |
| Toshiba MQ04ABF100 1TB               | 2         | 0.39%   |
| Toshiba MQ01ABF032 320GB             | 2         | 0.39%   |
| Toshiba MQ01ABD050 500GB             | 2         | 0.39%   |
| Toshiba MK7575GSX 752GB              | 2         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 47        | 51     | 29.01%  |
| Seagate             | 37        | 46     | 22.84%  |
| WDC                 | 34        | 39     | 20.99%  |
| Hitachi             | 20        | 21     | 12.35%  |
| HGST                | 9         | 10     | 5.56%   |
| Fujitsu             | 7         | 8      | 4.32%   |
| Unknown             | 3         | 3      | 1.85%   |
| QC-FT-D             | 2         | 2      | 1.23%   |
| Samsung Electronics | 1         | 3      | 0.62%   |
| MARSHAL             | 1         | 2      | 0.62%   |
| Apple               | 1         | 1      | 0.62%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 29        | 40     | 16.02%  |
| Crucial             | 25        | 31     | 13.81%  |
| SanDisk             | 16        | 20     | 8.84%   |
| WDC                 | 12        | 14     | 6.63%   |
| Kingston            | 11        | 12     | 6.08%   |
| A-DATA Technology   | 9         | 11     | 4.97%   |
| Toshiba             | 7         | 8      | 3.87%   |
| SPCC                | 6         | 9      | 3.31%   |
| Transcend           | 5         | 7      | 2.76%   |
| SUNEAST             | 5         | 6      | 2.76%   |
| Intel               | 5         | 5      | 2.76%   |
| Apple               | 5         | 5      | 2.76%   |
| Plextor             | 4         | 6      | 2.21%   |
| Micron Technology   | 3         | 5      | 1.66%   |
| China               | 3         | 4      | 1.66%   |
| Zheino              | 2         | 2      | 1.1%    |
| Unknown             | 2         | 2      | 1.1%    |
| Team                | 2         | 3      | 1.1%    |
| Patriot             | 2         | 3      | 1.1%    |
| OCZ                 | 2         | 2      | 1.1%    |
| KIOXIA-EXCERIA      | 2         | 3      | 1.1%    |
| Green House         | 2         | 4      | 1.1%    |
| Apacer              | 2         | 4      | 1.1%    |
| Teclast             | 1         | 1      | 0.55%   |
| TCSUNBOW            | 1         | 1      | 0.55%   |
| SK hynix            | 1         | 1      | 0.55%   |
| Seagate             | 1         | 1      | 0.55%   |
| Ramaxel Technology  | 1         | 1      | 0.55%   |
| PNY                 | 1         | 1      | 0.55%   |
| OASDX               | 1         | 2      | 0.55%   |
| Netac               | 1         | 1      | 0.55%   |
| LITEON              | 1         | 2      | 0.55%   |
| Intenso             | 1         | 1      | 0.55%   |
| Hitachi             | 1         | 1      | 0.55%   |
| Hewlett-Packard     | 1         | 1      | 0.55%   |
| FATTYDOVE           | 1         | 1      | 0.55%   |
| Colorful            | 1         | 1      | 0.55%   |
| BUFFALO             | 1         | 1      | 0.55%   |
| Biostar             | 1         | 1      | 0.55%   |
| ASUS-PHISON         | 1         | 1      | 0.55%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 169       | 228    | 36.11%  |
| HDD     | 155       | 186    | 33.12%  |
| NVMe    | 107       | 140    | 22.86%  |
| MMC     | 26        | 38     | 5.56%   |
| Unknown | 11        | 11     | 2.35%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 305       | 407    | 66.89%  |
| NVMe | 107       | 139    | 23.46%  |
| MMC  | 26        | 38     | 5.7%    |
| SAS  | 18        | 19     | 3.95%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 248       | 320    | 77.26%  |
| 0.51-1.0   | 66        | 85     | 20.56%  |
| 1.01-2.0   | 7         | 9      | 2.18%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 153       | 35.25%  |
| 251-500        | 79        | 18.2%   |
| 501-1000       | 55        | 12.67%  |
| 51-100         | 38        | 8.76%   |
| 1-20           | 37        | 8.53%   |
| 21-50          | 25        | 5.76%   |
| Unknown        | 18        | 4.15%   |
| 1001-2000      | 17        | 3.92%   |
| 2001-3000      | 9         | 2.07%   |
| More than 3000 | 3         | 0.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 227       | 50.44%  |
| 21-50     | 87        | 19.33%  |
| 101-250   | 36        | 8%      |
| 51-100    | 32        | 7.11%   |
| 251-500   | 30        | 6.67%   |
| Unknown   | 18        | 4%      |
| 501-1000  | 13        | 2.89%   |
| 1001-2000 | 5         | 1.11%   |
| 2001-3000 | 2         | 0.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                     | Notebooks | Drives | Percent |
|-------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD075 752GB                  | 7         | 7      | 25.93%  |
| Seagate ST9500325AS 500GB                 | 2         | 2      | 7.41%   |
| Seagate ST9160314AS 160GB                 | 2         | 2      | 7.41%   |
| Toshiba MK5055GSX 500GB                   | 1         | 1      | 3.7%    |
| Toshiba MK1255GSX H 120GB                 | 1         | 1      | 3.7%    |
| Seagate ST500LT012-1DG142 500GB           | 1         | 1      | 3.7%    |
| Seagate ST1000LM035-1RK172 1TB            | 1         | 1      | 3.7%    |
| SanDisk SSD PLUS 1000GB                   | 1         | 2      | 3.7%    |
| SanDisk SSD P4 32GB                       | 1         | 1      | 3.7%    |
| Samsung Electronics HM641JI 640GB         | 1         | 2      | 3.7%    |
| MARSHAL MAL2020SA 80 20GB                 | 1         | 1      | 3.7%    |
| LITEON CV8-8E128-HP 128GB SSD             | 1         | 2      | 3.7%    |
| Hitachi HTS723232A7A364 320GB             | 1         | 1      | 3.7%    |
| Hitachi HTS545050B9A300 500GB             | 1         | 1      | 3.7%    |
| Hitachi HTS545025B9SA02 250GB             | 1         | 1      | 3.7%    |
| HGST HTS545050A7E380 500GB                | 1         | 1      | 3.7%    |
| HGST HTS541075A9E680 752GB                | 1         | 1      | 3.7%    |
| Crucial C300-CTFDDAC064MAG 64GB SSD       | 1         | 2      | 3.7%    |
| A-DATA Technology AXM21S3-24GM-B 24GB SSD | 1         | 1      | 3.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 9         | 9      | 33.33%  |
| Seagate             | 6         | 6      | 22.22%  |
| Hitachi             | 3         | 3      | 11.11%  |
| SanDisk             | 2         | 3      | 7.41%   |
| HGST                | 2         | 2      | 7.41%   |
| Samsung Electronics | 1         | 2      | 3.7%    |
| MARSHAL             | 1         | 1      | 3.7%    |
| LITEON              | 1         | 2      | 3.7%    |
| Crucial             | 1         | 2      | 3.7%    |
| A-DATA Technology   | 1         | 1      | 3.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 9         | 9      | 40.91%  |
| Seagate             | 6         | 6      | 27.27%  |
| Hitachi             | 3         | 3      | 13.64%  |
| HGST                | 2         | 2      | 9.09%   |
| Samsung Electronics | 1         | 2      | 4.55%   |
| MARSHAL             | 1         | 1      | 4.55%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 22        | 23     | 81.48%  |
| SSD  | 5         | 8      | 18.52%  |

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

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 256       | 365    | 58.72%  |
| Works    | 154       | 207    | 35.32%  |
| Malfunc  | 26        | 31     | 5.96%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 306       | 65.67%  |
| AMD                          | 44        | 9.44%   |
| Samsung Electronics          | 39        | 8.37%   |
| SK hynix                     | 16        | 3.43%   |
| SanDisk                      | 14        | 3%      |
| Micron Technology            | 8         | 1.72%   |
| KIOXIA                       | 7         | 1.5%    |
| Toshiba America Info Systems | 6         | 1.29%   |
| Kingston Technology Company  | 6         | 1.29%   |
| Silicon Motion               | 5         | 1.07%   |
| Apple                        | 5         | 1.07%   |
| Nvidia                       | 4         | 0.86%   |
| Phison Electronics           | 2         | 0.43%   |
| Micron/Crucial Technology    | 2         | 0.43%   |
| ADATA Technology             | 1         | 0.21%   |
| Unknown                      | 1         | 0.21%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 59        | 11.64%  |
| AMD FCH SATA Controller [AHCI mode]                                                    | 34        | 6.71%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 33        | 6.51%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 29        | 5.72%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 22        | 4.34%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 18        | 3.55%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 17        | 3.35%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 16        | 3.16%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 13        | 2.56%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 11        | 2.17%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 10        | 1.97%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 10        | 1.97%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 9         | 1.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 9         | 1.78%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 9         | 1.78%   |
| Samsung NVMe SSD Controller 980                                                        | 8         | 1.58%   |
| Micron Non-Volatile memory controller                                                  | 8         | 1.58%   |
| KIOXIA NVMe SSD Controller BG4                                                         | 7         | 1.38%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 7         | 1.38%   |
| SK hynix Gold P31 SSD                                                                  | 6         | 1.18%   |
| SanDisk Non-Volatile memory controller                                                 | 6         | 1.18%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 6         | 1.18%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 6         | 1.18%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 5         | 0.99%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 5         | 0.99%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 5         | 0.99%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 5         | 0.99%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 5         | 0.99%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 4         | 0.79%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 4         | 0.79%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 4         | 0.79%   |
| Intel SSD 660P Series                                                                  | 4         | 0.79%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 4         | 0.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 4         | 0.79%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 4         | 0.79%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 4         | 0.79%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 4         | 0.79%   |
| Apple ANS2 NVMe Controller                                                             | 4         | 0.79%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 3         | 0.59%   |
| SK hynix Non-Volatile memory controller                                                | 3         | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 309       | 63.98%  |
| NVMe | 108       | 22.36%  |
| IDE  | 46        | 9.52%   |
| RAID | 20        | 4.14%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 360       | 86.54%  |
| AMD    | 56        | 13.46%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-3320M CPU @ 2.60GHz             | 11        | 2.64%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 8         | 1.92%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 8         | 1.92%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 7         | 1.68%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 7         | 1.68%   |
| Intel Celeron CPU 847 @ 1.10GHz               | 7         | 1.68%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 6         | 1.44%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 6         | 1.44%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 6         | 1.44%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 6         | 1.44%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 6         | 1.44%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 5         | 1.2%    |
| Intel Core i7-3520M CPU @ 2.90GHz             | 5         | 1.2%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 5         | 1.2%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 5         | 1.2%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 5         | 1.2%    |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 5         | 1.2%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 0.96%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 0.96%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 4         | 0.96%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 4         | 0.96%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 4         | 0.96%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 4         | 0.96%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 4         | 0.96%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 4         | 0.96%   |
| Intel Core 2 CPU T7200 @ 2.00GHz              | 4         | 0.96%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 4         | 0.96%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 4         | 0.96%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 0.96%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 0.96%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 0.72%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 3         | 0.72%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 0.72%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 3         | 0.72%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 3         | 0.72%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 3         | 0.72%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 3         | 0.72%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 3         | 0.72%   |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 3         | 0.72%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz          | 3         | 0.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 122       | 29.33%  |
| Intel Core i7           | 81        | 19.47%  |
| Intel Celeron           | 42        | 10.1%   |
| Intel Core 2 Duo        | 30        | 7.21%   |
| Intel Core i3           | 27        | 6.49%   |
| Other                   | 17        | 4.09%   |
| Intel Atom              | 14        | 3.37%   |
| AMD Ryzen 5             | 14        | 3.37%   |
| AMD Ryzen 7             | 10        | 2.4%    |
| Intel Core 2            | 7         | 1.68%   |
| Intel Celeron M         | 4         | 0.96%   |
| Intel Pentium           | 3         | 0.72%   |
| Intel Celeron Dual-Core | 3         | 0.72%   |
| AMD Ryzen 7 PRO         | 3         | 0.72%   |
| AMD Ryzen 3             | 3         | 0.72%   |
| AMD Athlon              | 3         | 0.72%   |
| AMD A6                  | 3         | 0.72%   |
| Intel Pentium M         | 2         | 0.48%   |
| Intel Genuine           | 2         | 0.48%   |
| Intel Core M            | 2         | 0.48%   |
| Intel Core i9           | 2         | 0.48%   |
| AMD Ryzen 9             | 2         | 0.48%   |
| AMD Ryzen 5 PRO         | 2         | 0.48%   |
| AMD Mobile Sempron      | 2         | 0.48%   |
| AMD E2                  | 2         | 0.48%   |
| AMD E1                  | 2         | 0.48%   |
| Intel Pentium Dual-Core | 1         | 0.24%   |
| Intel Core m5           | 1         | 0.24%   |
| Intel Core m3           | 1         | 0.24%   |
| AMD V120                | 1         | 0.24%   |
| AMD Turion 64 X2 Mobile | 1         | 0.24%   |
| AMD Sempron             | 1         | 0.24%   |
| AMD Quad-Core           | 1         | 0.24%   |
| AMD E                   | 1         | 0.24%   |
| AMD C-60                | 1         | 0.24%   |
| AMD Athlon X2           | 1         | 0.24%   |
| AMD Athlon 64 X2        | 1         | 0.24%   |
| AMD A8                  | 1         | 0.24%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 254       | 61.06%  |
| 4      | 91        | 21.88%  |
| 6      | 28        | 6.73%   |
| 1      | 20        | 4.81%   |
| 8      | 19        | 4.57%   |
| 14     | 4         | 0.96%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 416       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 289       | 69.47%  |
| 1      | 127       | 30.53%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 397       | 95.43%  |
| 32-bit         | 13        | 3.13%   |
| Unknown        | 6         | 1.44%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 68        | 16.04%  |
| 0x306a9    | 44        | 10.38%  |
| 0x206a7    | 42        | 9.91%   |
| 0x1067a    | 20        | 4.72%   |
| 0x306d4    | 18        | 4.25%   |
| 0x806ec    | 16        | 3.77%   |
| 0x20655    | 15        | 3.54%   |
| 0x806e9    | 12        | 2.83%   |
| 0x40651    | 11        | 2.59%   |
| 0xa0652    | 9         | 2.12%   |
| 0x306c3    | 9         | 2.12%   |
| 0x10676    | 9         | 2.12%   |
| 0x806ea    | 8         | 1.89%   |
| 0x20652    | 8         | 1.89%   |
| 0x806c1    | 7         | 1.65%   |
| 0x406e3    | 7         | 1.65%   |
| 0x0a50000c | 7         | 1.65%   |
| 0x906ea    | 6         | 1.42%   |
| 0x806eb    | 6         | 1.42%   |
| 0x6f6      | 6         | 1.42%   |
| 0x406c4    | 6         | 1.42%   |
| 0x106c2    | 6         | 1.42%   |
| 0x08108102 | 6         | 1.42%   |
| 0x506c9    | 5         | 1.18%   |
| 0x08600106 | 5         | 1.18%   |
| 0x906a3    | 4         | 0.94%   |
| 0x406c3    | 4         | 0.94%   |
| 0x08108109 | 4         | 0.94%   |
| 0x906e9    | 3         | 0.71%   |
| 0x6fd      | 3         | 0.71%   |
| 0x6e8      | 3         | 0.71%   |
| 0x6d8      | 3         | 0.71%   |
| 0x506e3    | 3         | 0.71%   |
| 0x08608103 | 3         | 0.71%   |
| 0x806d1    | 2         | 0.47%   |
| 0x706e5    | 2         | 0.47%   |
| 0x30678    | 2         | 0.47%   |
| 0x106ca    | 2         | 0.47%   |
| 0x0810100b | 2         | 0.47%   |
| 0x07030106 | 2         | 0.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 67        | 16.11%  |
| SandyBridge      | 50        | 12.02%  |
| IvyBridge        | 48        | 11.54%  |
| Penryn           | 32        | 7.69%   |
| Westmere         | 25        | 6.01%   |
| Haswell          | 22        | 5.29%   |
| Broadwell        | 20        | 4.81%   |
| Skylake          | 15        | 3.61%   |
| Silvermont       | 15        | 3.61%   |
| Core             | 13        | 3.13%   |
| Zen+             | 12        | 2.88%   |
| CometLake        | 12        | 2.88%   |
| Zen 2            | 11        | 2.64%   |
| TigerLake        | 10        | 2.4%    |
| Zen 3            | 8         | 1.92%   |
| Bonnell          | 8         | 1.92%   |
| P6               | 7         | 1.68%   |
| Goldmont         | 5         | 1.2%    |
| Zen              | 4         | 0.96%   |
| K8 Hammer        | 4         | 0.96%   |
| IceLake          | 4         | 0.96%   |
| Alderlake Hybrid | 4         | 0.96%   |
| Puma             | 3         | 0.72%   |
| Jaguar           | 3         | 0.72%   |
| Unknown          | 3         | 0.72%   |
| K8 & K10 hybrid  | 2         | 0.48%   |
| Goldmont plus    | 2         | 0.48%   |
| Bobcat           | 2         | 0.48%   |
| Piledriver       | 1         | 0.24%   |
| Nehalem          | 1         | 0.24%   |
| K10 Llano        | 1         | 0.24%   |
| K10              | 1         | 0.24%   |
| Excavator        | 1         | 0.24%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 346       | 72.54%  |
| AMD    | 69        | 14.47%  |
| Nvidia | 62        | 13%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 49        | 9.74%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 48        | 9.54%   |
| Intel Core Processor Integrated Graphics Controller                                      | 25        | 4.97%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 24        | 4.77%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 15        | 2.98%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 14        | 2.78%   |
| Intel HD Graphics 5500                                                                   | 14        | 2.78%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 13        | 2.58%   |
| Intel UHD Graphics 620                                                                   | 12        | 2.39%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 12        | 2.39%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 12        | 2.39%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 11        | 2.19%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 10        | 1.99%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 10        | 1.99%   |
| Intel HD Graphics 620                                                                    | 10        | 1.99%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 10        | 1.99%   |
| AMD Renoir                                                                               | 10        | 1.99%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 9         | 1.79%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 9         | 1.79%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 8         | 1.59%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 8         | 1.59%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 8         | 1.59%   |
| AMD Cezanne                                                                              | 7         | 1.39%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 5         | 0.99%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 5         | 0.99%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 5         | 0.99%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 5         | 0.99%   |
| Intel HD Graphics 500                                                                    | 5         | 0.99%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 0.8%    |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 4         | 0.8%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 3         | 0.6%    |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 3         | 0.6%    |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 3         | 0.6%    |
| Intel HD Graphics 630                                                                    | 3         | 0.6%    |
| Intel HD Graphics 530                                                                    | 3         | 0.6%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 0.6%    |
| AMD RS690M [Radeon Xpress 1200/1250/1270]                                                | 3         | 0.6%    |
| AMD Lucienne                                                                             | 3         | 0.6%    |
| Nvidia MCP89 [GeForce 320M]                                                              | 2         | 0.4%    |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.4%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 289       | 69.3%   |
| 1 x AMD        | 52        | 12.47%  |
| Intel + Nvidia | 45        | 10.79%  |
| 1 x Nvidia     | 12        | 2.88%   |
| Intel + AMD    | 9         | 2.16%   |
| AMD + Nvidia   | 5         | 1.2%    |
| 2 x AMD        | 3         | 0.72%   |
| Other          | 1         | 0.24%   |
| 2 x Intel      | 1         | 0.24%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 373       | 89.45%  |
| Proprietary | 34        | 8.15%   |
| Unknown     | 10        | 2.4%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 297       | 70.05%  |
| 0.01-0.5   | 46        | 10.85%  |
| 1.01-2.0   | 42        | 9.91%   |
| 3.01-4.0   | 14        | 3.3%    |
| 0.51-1.0   | 12        | 2.83%   |
| 5.01-6.0   | 6         | 1.42%   |
| 7.01-8.0   | 5         | 1.18%   |
| 8.01-16.0  | 2         | 0.47%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 82        | 20.1%   |
| AU Optronics            | 74        | 18.14%  |
| Chimei Innolux          | 39        | 9.56%   |
| Samsung Electronics     | 38        | 9.31%   |
| Sharp                   | 27        | 6.62%   |
| BOE                     | 26        | 6.37%   |
| Chi Mei Optoelectronics | 16        | 3.92%   |
| Apple                   | 16        | 3.92%   |
| Lenovo                  | 13        | 3.19%   |
| PANDA                   | 8         | 1.96%   |
| Goldstar                | 8         | 1.96%   |
| Dell                    | 8         | 1.96%   |
| NOV                     | 4         | 0.98%   |
| Philips                 | 3         | 0.74%   |
| Panasonic               | 3         | 0.74%   |
| LG Philips              | 3         | 0.74%   |
| IOD                     | 3         | 0.74%   |
| Hewlett-Packard         | 3         | 0.74%   |
| CSO                     | 3         | 0.74%   |
| CPT                     | 3         | 0.74%   |
| Ancor Communications    | 3         | 0.74%   |
| Toshiba                 | 2         | 0.49%   |
| InfoVision              | 2         | 0.49%   |
| Iiyama                  | 2         | 0.49%   |
| ASUSTek Computer        | 2         | 0.49%   |
| AOC                     | 2         | 0.49%   |
| Acer                    | 2         | 0.49%   |
| Yamaha                  | 1         | 0.25%   |
| Sony                    | 1         | 0.25%   |
| Quanta Display          | 1         | 0.25%   |
| Orion                   | 1         | 0.25%   |
| OOO                     | 1         | 0.25%   |
| Mitsubishi              | 1         | 0.25%   |
| InnoLux Display         | 1         | 0.25%   |
| IBM                     | 1         | 0.25%   |
| Hitachi                 | 1         | 0.25%   |
| HannStar                | 1         | 0.25%   |
| Green House             | 1         | 0.25%   |
| Eizo                    | 1         | 0.25%   |
| BenQ                    | 1         | 0.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 7         | 1.71%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 6         | 1.46%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 5         | 1.22%   |
| NOV NOVA HD CARD NOV0405 1920x1080 459x296mm 21.5-inch                   | 4         | 0.98%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 4         | 0.98%   |
| LG Display LCD Monitor LGD02CB 1366x768 344x194mm 15.5-inch              | 4         | 0.98%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 4         | 0.98%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 3         | 0.73%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 3         | 0.73%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 3         | 0.73%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 3         | 0.73%   |
| Sharp LQ133T1JW22 SHP1422 2560x1440 294x165mm 13.3-inch                  | 2         | 0.49%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch                  | 2         | 0.49%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 2         | 0.49%   |
| Sharp HDMI SHP0FDB 1360x768 820x460mm 37.0-inch                          | 2         | 0.49%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 340x190mm 15.3-inch     | 2         | 0.49%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch     | 2         | 0.49%   |
| Samsung Electronics LCD Monitor SEC5033 1280x800 331x207mm 15.4-inch     | 2         | 0.49%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch    | 2         | 0.49%   |
| Samsung Electronics LCD Monitor SDC424A 3200x1800 293x165mm 13.2-inch    | 2         | 0.49%   |
| PANDA LCD Monitor NCP0054 1920x1080 344x194mm 15.5-inch                  | 2         | 0.49%   |
| LG Display LCD Monitor LGD6302 1366x768 344x194mm 15.5-inch              | 2         | 0.49%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 2         | 0.49%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch             | 2         | 0.49%   |
| LG Display LCD Monitor LGD033B 1366x768 344x194mm 15.5-inch              | 2         | 0.49%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 2         | 0.49%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch              | 2         | 0.49%   |
| LG Display LCD Monitor LGD01E9 1920x1080 345x194mm 15.6-inch             | 2         | 0.49%   |
| LG Display LCD Monitor LGD01DA 1366x768 294x166mm 13.3-inch              | 2         | 0.49%   |
| LG Display LCD Monitor LGD0171 1366x768 344x194mm 15.5-inch              | 2         | 0.49%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x194mm 15.5-inch                  | 2         | 0.49%   |
| Lenovo LCD Monitor LEN4033 1440x900 303x190mm 14.1-inch                  | 2         | 0.49%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 2         | 0.49%   |
| Lenovo LCD Monitor LEN4000 1024x768 246x184mm 12.1-inch                  | 2         | 0.49%   |
| Hewlett-Packard 27f 4k HPN363B 3840x2160 597x336mm 27.0-inch             | 2         | 0.49%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                  | 2         | 0.49%   |
| Goldstar 32inch FHD GSM76F5 1920x1080 698x392mm 31.5-inch                | 2         | 0.49%   |
| CPT LCD Monitor COR17DB 1600x900 293x164mm 13.2-inch                     | 2         | 0.49%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch         | 2         | 0.49%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch         | 2         | 0.49%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 145       | 36.34%  |
| 1366x768 (WXGA)    | 139       | 34.84%  |
| 1280x800 (WXGA)    | 24        | 6.02%   |
| 3840x2160 (4K)     | 20        | 5.01%   |
| 1600x900 (HD+)     | 11        | 2.76%   |
| 2560x1440 (QHD)    | 9         | 2.26%   |
| 1440x900 (WXGA+)   | 7         | 1.75%   |
| 2880x1800          | 5         | 1.25%   |
| 2560x1600          | 5         | 1.25%   |
| 1920x1200 (WUXGA)  | 5         | 1.25%   |
| 3840x2400          | 3         | 0.75%   |
| 3200x1800 (QHD+)   | 3         | 0.75%   |
| 1920x540           | 3         | 0.75%   |
| 1024x600           | 3         | 0.75%   |
| 3072x1920          | 2         | 0.5%    |
| 2560x1080          | 2         | 0.5%    |
| 2160x1440          | 2         | 0.5%    |
| 1360x768           | 2         | 0.5%    |
| 1280x1024 (SXGA)   | 2         | 0.5%    |
| 3456x2160          | 1         | 0.25%   |
| 3000x2000          | 1         | 0.25%   |
| 2240x1400          | 1         | 0.25%   |
| 1680x1050 (WSXGA+) | 1         | 0.25%   |
| 1400x1050          | 1         | 0.25%   |
| 1024x768 (XGA)     | 1         | 0.25%   |
| 1024x576           | 1         | 0.25%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 159       | 38.78%  |
| 13      | 85        | 20.73%  |
| 14      | 35        | 8.54%   |
| 12      | 26        | 6.34%   |
| 17      | 18        | 4.39%   |
| 21      | 12        | 2.93%   |
| 11      | 12        | 2.93%   |
| 23      | 11        | 2.68%   |
| 27      | 8         | 1.95%   |
| 31      | 7         | 1.71%   |
| 24      | 7         | 1.71%   |
| 10      | 6         | 1.46%   |
| 72      | 4         | 0.98%   |
| 18      | 4         | 0.98%   |
| 37      | 3         | 0.73%   |
| 16      | 3         | 0.73%   |
| Unknown | 3         | 0.73%   |
| 34      | 2         | 0.49%   |
| 32      | 2         | 0.49%   |
| 84      | 1         | 0.24%   |
| 52      | 1         | 0.24%   |
| 19      | 1         | 0.24%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 212       | 51.96%  |
| 201-300     | 108       | 26.47%  |
| 501-600     | 25        | 6.13%   |
| 351-400     | 23        | 5.64%   |
| 401-500     | 17        | 4.17%   |
| 601-700     | 7         | 1.72%   |
| 1501-2000   | 5         | 1.23%   |
| 701-800     | 4         | 0.98%   |
| 801-900     | 3         | 0.74%   |
| Unknown     | 3         | 0.74%   |
| 1001-1500   | 1         | 0.25%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 304       | 81.72%  |
| 16/10   | 55        | 14.78%  |
| 3/2     | 5         | 1.34%   |
| 5/4     | 2         | 0.54%   |
| 21/9    | 2         | 0.54%   |
| Unknown | 2         | 0.54%   |
| 4/3     | 1         | 0.27%   |
| 32/9    | 1         | 0.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 159       | 38.78%  |
| 81-90          | 63        | 15.37%  |
| 71-80          | 56        | 13.66%  |
| 201-250        | 27        | 6.59%   |
| 61-70          | 26        | 6.34%   |
| 121-130        | 14        | 3.41%   |
| 51-60          | 12        | 2.93%   |
| 351-500        | 11        | 2.68%   |
| 301-350        | 8         | 1.95%   |
| More than 1000 | 6         | 1.46%   |
| 41-50          | 6         | 1.46%   |
| 141-150        | 5         | 1.22%   |
| 151-200        | 4         | 0.98%   |
| 111-120        | 3         | 0.73%   |
| 501-1000       | 3         | 0.73%   |
| Unknown        | 3         | 0.73%   |
| 131-140        | 2         | 0.49%   |
| 251-300        | 1         | 0.24%   |
| 91-100         | 1         | 0.24%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 127       | 31.51%  |
| 101-120       | 112       | 27.79%  |
| 51-100        | 78        | 19.35%  |
| 161-240       | 56        | 13.9%   |
| More than 240 | 20        | 4.96%   |
| 1-50          | 7         | 1.74%   |
| Unknown       | 3         | 0.74%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 359       | 85.68%  |
| 2     | 46        | 10.98%  |
| 0     | 12        | 2.86%   |
| 3     | 2         | 0.48%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 230       | 35.77%  |
| Realtek Semiconductor           | 169       | 26.28%  |
| Qualcomm Atheros                | 104       | 16.17%  |
| Broadcom                        | 60        | 9.33%   |
| Marvell Technology Group        | 16        | 2.49%   |
| Broadcom Limited                | 12        | 1.87%   |
| ASIX Electronics                | 8         | 1.24%   |
| Ralink                          | 6         | 0.93%   |
| MediaTek                        | 5         | 0.78%   |
| BUFFALO                         | 5         | 0.78%   |
| Huawei Technologies             | 4         | 0.62%   |
| Nvidia                          | 3         | 0.47%   |
| Apple                           | 3         | 0.47%   |
| TP-Link                         | 2         | 0.31%   |
| Ralink Technology               | 2         | 0.31%   |
| PLANEX                          | 2         | 0.31%   |
| Lenovo                          | 2         | 0.31%   |
| D-Link                          | 2         | 0.31%   |
| Xiaomi                          | 1         | 0.16%   |
| Samsung Electronics             | 1         | 0.16%   |
| Qualcomm Atheros Communications | 1         | 0.16%   |
| NEC Computers                   | 1         | 0.16%   |
| JMicron Technology              | 1         | 0.16%   |
| Google                          | 1         | 0.16%   |
| Dell                            | 1         | 0.16%   |
| Aquantia                        | 1         | 0.16%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 97        | 12.29%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 27        | 3.42%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 25        | 3.17%   |
| Intel Wireless 7265                                                     | 17        | 2.15%   |
| Intel Wi-Fi 6 AX200                                                     | 16        | 2.03%   |
| Intel 82579V Gigabit Network Connection                                 | 16        | 2.03%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 15        | 1.9%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 13        | 1.65%   |
| Intel Wireless 8265 / 8275                                              | 12        | 1.52%   |
| Intel Wireless 7260                                                     | 12        | 1.52%   |
| Intel Wireless 3165                                                     | 11        | 1.39%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 10        | 1.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 10        | 1.27%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 10        | 1.27%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 9         | 1.14%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 9         | 1.14%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 9         | 1.14%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 9         | 1.14%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 9         | 1.14%   |
| Intel Wi-Fi 6 AX201                                                     | 9         | 1.14%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 9         | 1.14%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                    | 9         | 1.14%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 9         | 1.14%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 8         | 1.01%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 8         | 1.01%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 8         | 1.01%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 0.89%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 7         | 0.89%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 7         | 0.89%   |
| Intel Wireless 3160                                                     | 7         | 0.89%   |
| Intel WiMAX Connection 2400m                                            | 7         | 0.89%   |
| Intel WiFi Link 5100                                                    | 7         | 0.89%   |
| Intel Ethernet Connection (3) I218-LM                                   | 7         | 0.89%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 0.76%   |
| Intel Wireless-AC 9260                                                  | 6         | 0.76%   |
| Intel Wireless 8260                                                     | 6         | 0.76%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 6         | 0.76%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 6         | 0.76%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 6         | 0.76%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 6         | 0.76%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 202       | 48.44%  |
| Qualcomm Atheros                | 82        | 19.66%  |
| Realtek Semiconductor           | 57        | 13.67%  |
| Broadcom                        | 40        | 9.59%   |
| Broadcom Limited                | 10        | 2.4%    |
| Ralink                          | 6         | 1.44%   |
| MediaTek                        | 5         | 1.2%    |
| BUFFALO                         | 5         | 1.2%    |
| TP-Link                         | 2         | 0.48%   |
| Ralink Technology               | 2         | 0.48%   |
| PLANEX                          | 2         | 0.48%   |
| D-Link                          | 2         | 0.48%   |
| Qualcomm Atheros Communications | 1         | 0.24%   |
| Dell                            | 1         | 0.24%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                                     | 17        | 4.06%   |
| Intel Wi-Fi 6 AX200                                                     | 16        | 3.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 15        | 3.58%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 13        | 3.1%    |
| Intel Wireless 8265 / 8275                                              | 12        | 2.86%   |
| Intel Wireless 7260                                                     | 12        | 2.86%   |
| Intel Wireless 3165                                                     | 11        | 2.63%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 10        | 2.39%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 10        | 2.39%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 9         | 2.15%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 9         | 2.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 9         | 2.15%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 9         | 2.15%   |
| Intel Wi-Fi 6 AX201                                                     | 9         | 2.15%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 9         | 2.15%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                    | 9         | 2.15%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 9         | 2.15%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 8         | 1.91%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 8         | 1.91%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 8         | 1.91%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 1.67%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 7         | 1.67%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 7         | 1.67%   |
| Intel Wireless 3160                                                     | 7         | 1.67%   |
| Intel WiFi Link 5100                                                    | 7         | 1.67%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 1.43%   |
| Intel Wireless-AC 9260                                                  | 6         | 1.43%   |
| Intel Wireless 8260                                                     | 6         | 1.43%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 6         | 1.43%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 6         | 1.43%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 6         | 1.43%   |
| Realtek 802.11ac NIC                                                    | 5         | 1.19%   |
| Intel Centrino Advanced-N 6235                                          | 5         | 1.19%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 4         | 0.95%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 0.95%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 4         | 0.95%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 4         | 0.95%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 4         | 0.95%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 0.95%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 4         | 0.95%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 140       | 39.11%  |
| Intel                    | 114       | 31.84%  |
| Qualcomm Atheros         | 34        | 9.5%    |
| Broadcom                 | 27        | 7.54%   |
| Marvell Technology Group | 16        | 4.47%   |
| ASIX Electronics         | 8         | 2.23%   |
| Huawei Technologies      | 4         | 1.12%   |
| Nvidia                   | 3         | 0.84%   |
| Apple                    | 3         | 0.84%   |
| Lenovo                   | 2         | 0.56%   |
| Broadcom Limited         | 2         | 0.56%   |
| Xiaomi                   | 1         | 0.28%   |
| Samsung Electronics      | 1         | 0.28%   |
| JMicron Technology       | 1         | 0.28%   |
| Google                   | 1         | 0.28%   |
| Aquantia                 | 1         | 0.28%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 97        | 26.43%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 27        | 7.36%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 25        | 6.81%   |
| Intel 82579V Gigabit Network Connection                                        | 16        | 4.36%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 10        | 2.72%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 9         | 2.45%   |
| Intel WiMAX Connection 2400m                                                   | 7         | 1.91%   |
| Intel Ethernet Connection (3) I218-LM                                          | 7         | 1.91%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 6         | 1.63%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 6         | 1.63%   |
| Intel Ethernet Connection (4) I219-V                                           | 5         | 1.36%   |
| Intel Ethernet Connection (10) I219-V                                          | 5         | 1.36%   |
| Intel 82577LC Gigabit Network Connection                                       | 5         | 1.36%   |
| Intel 82567LM Gigabit Network Connection                                       | 5         | 1.36%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 5         | 1.36%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 4         | 1.09%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 4         | 1.09%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 4         | 1.09%   |
| Intel I211 Gigabit Network Connection                                          | 4         | 1.09%   |
| Intel 82577LM Gigabit Network Connection                                       | 4         | 1.09%   |
| Huawei E353/E3131                                                              | 4         | 1.09%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 4         | 1.09%   |
| Realtek RTL8125 2.5GbE Controller                                              | 3         | 0.82%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 3         | 0.82%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 3         | 0.82%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 3         | 0.82%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller                          | 3         | 0.82%   |
| Intel Ethernet Connection I219-LM                                              | 3         | 0.82%   |
| Intel Ethernet Connection (6) I219-V                                           | 3         | 0.82%   |
| Intel Ethernet Connection (6) I219-LM                                          | 3         | 0.82%   |
| Intel 82566MM Gigabit Network Connection                                       | 3         | 0.82%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 3         | 0.82%   |
| Apple iBridge                                                                  | 3         | 0.82%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 2         | 0.54%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 0.54%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 2         | 0.54%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 2         | 0.54%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 2         | 0.54%   |
| Nvidia MCP79 Ethernet                                                          | 2         | 0.54%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.54%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 403       | 53.95%  |
| Ethernet | 341       | 45.65%  |
| Unknown  | 2         | 0.27%   |
| Modem    | 1         | 0.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 312       | 71.72%  |
| Ethernet | 123       | 28.28%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 308       | 74.04%  |
| 1     | 98        | 23.56%  |
| 0     | 7         | 1.68%   |
| 3     | 3         | 0.72%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 348       | 80.74%  |
| Yes  | 83        | 19.26%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 134       | 50.38%  |
| Broadcom                        | 24        | 9.02%   |
| Realtek Semiconductor           | 18        | 6.77%   |
| Qualcomm Atheros Communications | 17        | 6.39%   |
| IMC Networks                    | 13        | 4.89%   |
| Cambridge Silicon Radio         | 13        | 4.89%   |
| Apple                           | 12        | 4.51%   |
| Foxconn / Hon Hai               | 7         | 2.63%   |
| Fujitsu                         | 5         | 1.88%   |
| Alps Electric                   | 5         | 1.88%   |
| Realtek                         | 3         | 1.13%   |
| Lite-On Technology              | 3         | 1.13%   |
| ASUSTek Computer                | 3         | 1.13%   |
| Toshiba                         | 2         | 0.75%   |
| Ralink                          | 2         | 0.75%   |
| Ralink Technology               | 1         | 0.38%   |
| Opticis                         | 1         | 0.38%   |
| Hewlett-Packard                 | 1         | 0.38%   |
| Dell                            | 1         | 0.38%   |
| Askey Computer                  | 1         | 0.38%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 62        | 23.31%  |
| Intel AX201 Bluetooth                               | 26        | 9.77%   |
| Intel AX200 Bluetooth                               | 16        | 6.02%   |
| Realtek Bluetooth Radio                             | 14        | 5.26%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 13        | 4.89%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 13        | 4.89%   |
| Qualcomm Atheros  Bluetooth Device                  | 8         | 3.01%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 7         | 2.63%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 6         | 2.26%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 6         | 2.26%   |
| IMC Networks Bluetooth Radio                        | 6         | 2.26%   |
| Apple Bluetooth USB Host Controller                 | 6         | 2.26%   |
| Apple Bluetooth Host Controller                     | 6         | 2.26%   |
| Intel AX210 Bluetooth                               | 4         | 1.5%    |
| IMC Networks Bluetooth Device                       | 4         | 1.5%    |
| Fujitsu Bluetooth Device                            | 4         | 1.5%    |
| Realtek Bluetooth Radio                             | 3         | 1.13%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 1.13%   |
| Intel Bluetooth Device                              | 3         | 1.13%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 3         | 1.13%   |
| ASUS Broadcom Bluetooth 2.1                         | 3         | 1.13%   |
| Toshiba Atheros AR3012 Bluetooth                    | 2         | 0.75%   |
| Realtek RTL8723B Bluetooth                          | 2         | 0.75%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 0.75%   |
| Ralink RT3290 Bluetooth                             | 2         | 0.75%   |
| IMC Networks Wireless_Device                        | 2         | 0.75%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 0.75%   |
| Foxconn / Hon Hai BCM20702A0                        | 2         | 0.75%   |
| Broadcom HP Portable SoftSailing                    | 2         | 0.75%   |
| Broadcom BCM20702A0                                 | 2         | 0.75%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 0.75%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 2         | 0.75%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 0.75%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)     | 2         | 0.75%   |
| Alps Electric BCM2046 Bluetooth Device              | 2         | 0.75%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.38%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.38%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.38%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.38%   |
| Opticis Bluetooth Radio                             | 1         | 0.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 345       | 73.72%  |
| AMD                               | 64        | 13.68%  |
| Nvidia                            | 38        | 8.12%   |
| Apple                             | 4         | 0.85%   |
| C-Media Electronics               | 3         | 0.64%   |
| Lenovo                            | 2         | 0.43%   |
| Elitegroup Computer Systems (ECS) | 2         | 0.43%   |
| Creative Technology               | 2         | 0.43%   |
| Realtek Semiconductor             | 1         | 0.21%   |
| M2Tech                            | 1         | 0.21%   |
| JMTek                             | 1         | 0.21%   |
| JAVS                              | 1         | 0.21%   |
| iCreate Technologies              | 1         | 0.21%   |
| Corsair                           | 1         | 0.21%   |
| CMX Systems                       | 1         | 0.21%   |
| Cambridge Silicon Radio           | 1         | 0.21%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 62        | 11.17%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 37        | 6.67%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 37        | 6.67%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 36        | 6.49%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 26        | 4.68%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 24        | 4.32%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 20        | 3.6%    |
| Intel Broadwell-U Audio Controller                                                                | 20        | 3.6%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 19        | 3.42%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 18        | 3.24%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 14        | 2.52%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 14        | 2.52%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 13        | 2.34%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 11        | 1.98%   |
| Intel Comet Lake PCH cAVS                                                                         | 11        | 1.98%   |
| Intel 8 Series HD Audio Controller                                                                | 11        | 1.98%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 10        | 1.8%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 10        | 1.8%    |
| Intel Cannon Lake PCH cAVS                                                                        | 9         | 1.62%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 9         | 1.62%   |
| AMD FCH Azalia Controller                                                                         | 9         | 1.62%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 8         | 1.44%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 8         | 1.44%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 7         | 1.26%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 6         | 1.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6         | 1.08%   |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 1.08%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 5         | 0.9%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 4         | 0.72%   |
| Apple Audio Device                                                                                | 4         | 0.72%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 0.54%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 0.54%   |
| Nvidia Audio device                                                                               | 3         | 0.54%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 0.54%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 0.54%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 0.54%   |
| Nvidia MCP89 High Definition Audio                                                                | 2         | 0.36%   |
| Nvidia MCP79 High Definition Audio                                                                | 2         | 0.36%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.36%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 2         | 0.36%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 71        | 29.58%  |
| SK hynix            | 48        | 20%     |
| Micron Technology   | 31        | 12.92%  |
| Unknown             | 26        | 10.83%  |
| Kingston            | 10        | 4.17%   |
| Crucial             | 8         | 3.33%   |
| Elpida              | 7         | 2.92%   |
| A-DATA Technology   | 6         | 2.5%    |
| Nanya Technology    | 5         | 2.08%   |
| SanMax              | 4         | 1.67%   |
| Ramaxel Technology  | 4         | 1.67%   |
| Unknown (ABCD)      | 3         | 1.25%   |
| Team                | 2         | 0.83%   |
| Silicon Power       | 2         | 0.83%   |
| Corsair             | 2         | 0.83%   |
| Unknown             | 2         | 0.83%   |
| Toshiba             | 1         | 0.42%   |
| Neo Forza           | 1         | 0.42%   |
| Goldkey             | 1         | 0.42%   |
| G.Skill             | 1         | 0.42%   |
| EUDAR               | 1         | 0.42%   |
| Essencore           | 1         | 0.42%   |
| ChangXin Memory     | 1         | 0.42%   |
| CFD                 | 1         | 0.42%   |
| ASint Technology    | 1         | 0.42%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s           | 8         | 3.14%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s          | 5         | 1.96%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s          | 4         | 1.57%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s           | 4         | 1.57%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s           | 4         | 1.57%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s           | 4         | 1.57%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s           | 4         | 1.57%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                   | 3         | 1.18%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB DIMM DDR3 2133MT/s | 2         | 0.78%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s       | 2         | 0.78%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s          | 2         | 0.78%   |
| SK hynix RAM HMT325S6CFR8C-PB 2048MB SODIMM DDR3 1600MT/s       | 2         | 0.78%   |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1067MT/s          | 2         | 0.78%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s          | 2         | 0.78%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s           | 2         | 0.78%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s           | 2         | 0.78%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s           | 2         | 0.78%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s           | 2         | 0.78%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s          | 2         | 0.78%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s          | 2         | 0.78%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s        | 2         | 0.78%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s           | 2         | 0.78%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s    | 2         | 0.78%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s        | 2         | 0.78%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s            | 2         | 0.78%   |
| Micron RAM 4KTF51264HZ-1G6A1A 4GB SODIMM DDR3 1600MT/s          | 2         | 0.78%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8192MB SODIMM DDR4 2667MT/s         | 2         | 0.78%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s           | 2         | 0.78%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB SODIMM DDR4 3200MT/s         | 2         | 0.78%   |
| Kingston RAM CBD24D4S7S8ME-8 8GB SODIMM DDR4 2400MT/s           | 2         | 0.78%   |
| Elpida RAM EBJ40UG8EFU0-GN-F 4GB SODIMM DDR3 1600MT/s           | 2         | 0.78%   |
| Unknown                                                         | 2         | 0.78%   |
| Unknown RAM Module 8192MB SODIMM DDR4 3200MT/s                  | 1         | 0.39%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                  | 1         | 0.39%   |
| Unknown RAM Module 8192MB Row Of Chips LPDDR4 4267MT/s          | 1         | 0.39%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                     | 1         | 0.39%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                     | 1         | 0.39%   |
| Unknown RAM Module 4GB SODIMM DDR2 667MT/s                      | 1         | 0.39%   |
| Unknown RAM Module 4GB SODIMM 1066MT/s                          | 1         | 0.39%   |
| Unknown RAM Module 4GB LPDDR3 2133MT/s                          | 1         | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 82        | 39.42%  |
| DDR4    | 75        | 36.06%  |
| LPDDR3  | 15        | 7.21%   |
| DDR2    | 15        | 7.21%   |
| LPDDR4  | 9         | 4.33%   |
| SDRAM   | 5         | 2.4%    |
| Unknown | 4         | 1.92%   |
| DDR5    | 2         | 0.96%   |
| DDR     | 1         | 0.48%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 183       | 87.98%  |
| Row Of Chips | 17        | 8.17%   |
| Unknown      | 5         | 2.4%    |
| DIMM         | 2         | 0.96%   |
| Chip         | 1         | 0.48%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 79        | 35.59%  |
| 8192  | 64        | 28.83%  |
| 2048  | 38        | 17.12%  |
| 16384 | 24        | 10.81%  |
| 1024  | 11        | 4.95%   |
| 32768 | 5         | 2.25%   |
| 256   | 1         | 0.45%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 60        | 27.27%  |
| 3200    | 34        | 15.45%  |
| 2667    | 32        | 14.55%  |
| 2400    | 15        | 6.82%   |
| 1334    | 13        | 5.91%   |
| 2133    | 10        | 4.55%   |
| 1067    | 10        | 4.55%   |
| 1333    | 6         | 2.73%   |
| 667     | 5         | 2.27%   |
| 4199    | 4         | 1.82%   |
| 1867    | 4         | 1.82%   |
| 1066    | 4         | 1.82%   |
| Unknown | 4         | 1.82%   |
| 4800    | 2         | 0.91%   |
| 4267    | 2         | 0.91%   |
| 3733    | 2         | 0.91%   |
| 3266    | 2         | 0.91%   |
| 1866    | 2         | 0.91%   |
| 975     | 2         | 0.91%   |
| 400     | 2         | 0.91%   |
| 4266    | 1         | 0.45%   |
| 533     | 1         | 0.45%   |
| 333     | 1         | 0.45%   |
| 266     | 1         | 0.45%   |
| 100     | 1         | 0.45%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Seiko Epson         | 1         | 33.33%  |
| Samsung Electronics | 1         | 33.33%  |
| Brother Industries  | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Notebooks | Percent |
|----------------------------|-----------|---------|
| Seiko Epson WF-2010 Series | 1         | 33.33%  |
| Samsung SCX-3200 Series    | 1         | 33.33%  |
| Brother HL-2130 series     | 1         | 33.33%  |

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
| Chicony Electronics                    | 71        | 26.2%   |
| Acer                                   | 28        | 10.33%  |
| Microdia                               | 27        | 9.96%   |
| IMC Networks                           | 26        | 9.59%   |
| Sunplus Innovation Technology          | 23        | 8.49%   |
| Realtek Semiconductor                  | 16        | 5.9%    |
| Apple                                  | 12        | 4.43%   |
| Cheng Uei Precision Industry (Foxlink) | 11        | 4.06%   |
| Quanta                                 | 10        | 3.69%   |
| Suyin                                  | 8         | 2.95%   |
| Alcor Micro                            | 6         | 2.21%   |
| Silicon Motion                         | 4         | 1.48%   |
| Syntek                                 | 3         | 1.11%   |
| Ricoh                                  | 3         | 1.11%   |
| Lite-On Technology                     | 3         | 1.11%   |
| Samsung Electronics                    | 2         | 0.74%   |
| Luxvisions Innotech Limited            | 2         | 0.74%   |
| Lenovo                                 | 2         | 0.74%   |
| Importek                               | 2         | 0.74%   |
| Genesys Logic                          | 2         | 0.74%   |
| Z-Star Microelectronics                | 1         | 0.37%   |
| Primax Electronics                     | 1         | 0.37%   |
| Omnivision                             | 1         | 0.37%   |
| Oculus VR                              | 1         | 0.37%   |
| Logitech                               | 1         | 0.37%   |
| Intel                                  | 1         | 0.37%   |
| Etron Technology                       | 1         | 0.37%   |
| Cubeternet                             | 1         | 0.37%   |
| BUFFALO                                | 1         | 0.37%   |
| 2M UVC CAMERA                          | 1         | 0.37%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 14        | 5.15%   |
| Chicony FJ Camera                                       | 11        | 4.04%   |
| IMC Networks Integrated Camera                          | 10        | 3.68%   |
| Chicony Integrated Camera                               | 9         | 3.31%   |
| Realtek Integrated_Webcam_HD                            | 8         | 2.94%   |
| Chicony USB2.0 Camera                                   | 8         | 2.94%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 5         | 1.84%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 5         | 1.84%   |
| Chicony TOSHIBA Web Camera - HD                         | 5         | 1.84%   |
| Sunplus HD WebCam                                       | 4         | 1.47%   |
| Chicony HD WebCam                                       | 4         | 1.47%   |
| Apple FaceTime HD Camera                                | 4         | 1.47%   |
| Acer USB HD Webcam                                      | 4         | 1.47%   |
| Acer BisonCam, NB Pro                                   | 4         | 1.47%   |
| Sunplus Integrated_Webcam_HD                            | 3         | 1.1%    |
| Sunplus Integrated_Webcam_FHD                           | 3         | 1.1%    |
| Quanta HD User Facing                                   | 3         | 1.1%    |
| Microdia Integrated Webcam HD                           | 3         | 1.1%    |
| Lite-On Integrated Camera                               | 3         | 1.1%    |
| Chicony USB 2.0 Camera                                  | 3         | 1.1%    |
| Chicony Lenovo EasyCamera                               | 3         | 1.1%    |
| Chicony HP HD Camera                                    | 3         | 1.1%    |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 3         | 1.1%    |
| Apple FaceTime HD Camera (Built-in)                     | 3         | 1.1%    |
| Apple Built-in iSight                                   | 3         | 1.1%    |
| Acer Integrated Camera                                  | 3         | 1.1%    |
| Acer HD Webcam                                          | 3         | 1.1%    |
| Acer BisonCam,NB Pro                                    | 3         | 1.1%    |
| Syntek Integrated Camera                                | 2         | 0.74%   |
| Suyin NEC HD WebCam                                     | 2         | 0.74%   |
| Sunplus Dell HD Webcam                                  | 2         | 0.74%   |
| Sunplus ASUS USB2.0 Webcam                              | 2         | 0.74%   |
| Samsung Galaxy A5 (MTP)                                 | 2         | 0.74%   |
| Realtek USB2.0 VGA UVC WebCam                           | 2         | 0.74%   |
| Realtek Lenovo EasyCamera                               | 2         | 0.74%   |
| Microdia Webcam Vitade AF                               | 2         | 0.74%   |
| Microdia USB 2.0 Camera                                 | 2         | 0.74%   |
| Microdia Integrated Webcam                              | 2         | 0.74%   |
| Chicony TOSHIBA Web Camera - FHD                        | 2         | 0.74%   |
| Chicony Lenovo Integrated Camera (0.3MP)                | 2         | 0.74%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 23        | 29.49%  |
| AuthenTec                  | 13        | 16.67%  |
| Shenzhen Goodix Technology | 12        | 15.38%  |
| Synaptics                  | 11        | 14.1%   |
| Upek                       | 6         | 7.69%   |
| LighTuning Technology      | 5         | 6.41%   |
| STMicroelectronics         | 4         | 5.13%   |
| Elan Microelectronics      | 3         | 3.85%   |
| Focal-systems.Corp         | 1         | 1.28%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 8         | 10.26%  |
| Validity Sensors VFS495 Fingerprint Reader             | 5         | 6.41%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 5         | 6.41%   |
| Shenzhen Goodix  FingerPrint Device                    | 5         | 6.41%   |
| Shenzhen Goodix Fingerprint Reader                     | 5         | 6.41%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 4         | 5.13%   |
| Validity Sensors Swipe Fingerprint Sensor              | 4         | 5.13%   |
| STMicroelectronics Fingerprint Reader                  | 4         | 5.13%   |
| AuthenTec Fingerprint Sensor                           | 4         | 5.13%   |
| Validity Sensors VFS471 Fingerprint Reader             | 3         | 3.85%   |
| AuthenTec AES2810                                      | 3         | 3.85%   |
| AuthenTec AES1600                                      | 3         | 3.85%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor      | 2         | 2.56%   |
| Validity Sensors VFS491                                | 2         | 2.56%   |
| Shenzhen Goodix FingerPrint                            | 2         | 2.56%   |
| LighTuning ES603 Swipe Fingerprint Sensor              | 2         | 2.56%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 2         | 2.56%   |
| Elan ELAN:Fingerprint                                  | 2         | 2.56%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 2         | 2.56%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 1.28%   |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 1.28%   |
| Validity Sensors VFS301 Fingerprint Reader             | 1         | 1.28%   |
| Upek TCS5B Fingerprint sensor                          | 1         | 1.28%   |
| Synaptics WBDI Device                                  | 1         | 1.28%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 1.28%   |
| LighTuning Fingerprint Reader                          | 1         | 1.28%   |
| Focal-systems.Corp FT9201Fingerprint.                  | 1         | 1.28%   |
| Elan ELAN:ARM-M4                                       | 1         | 1.28%   |
| AuthenTec AES2660 Fingerprint Sensor                   | 1         | 1.28%   |
| Unknown                                                | 1         | 1.28%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 8         | 38.1%   |
| Upek        | 7         | 33.33%  |
| O2 Micro    | 3         | 14.29%  |
| Alcor Micro | 3         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 7         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 19.05%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 14.29%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 14.29%  |
| Broadcom 58200                                                               | 2         | 9.52%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 4.76%   |
| Broadcom 5880                                                                | 1         | 4.76%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 259       | 61.23%  |
| 1     | 135       | 31.91%  |
| 2     | 23        | 5.44%   |
| 3     | 4         | 0.95%   |
| 6     | 2         | 0.47%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 76        | 38%     |
| Graphics card            | 28        | 14%     |
| Chipcard                 | 20        | 10%     |
| Net/wireless             | 19        | 9.5%    |
| Multimedia controller    | 17        | 8.5%    |
| Storage                  | 11        | 5.5%    |
| Communication controller | 8         | 4%      |
| Bluetooth                | 6         | 3%      |
| Camera                   | 4         | 2%      |
| Sound                    | 3         | 1.5%    |
| Storage/ata              | 2         | 1%      |
| Net/ethernet             | 2         | 1%      |
| Modem                    | 2         | 1%      |
| Tv card                  | 1         | 0.5%    |
| Network                  | 1         | 0.5%    |

