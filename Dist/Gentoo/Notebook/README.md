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

Total: 859

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Dell          | Latitude D420               | [162b346743](https://linux-hardware.org/?probe=162b346743) | Jul 02, 2022 |
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
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [1be8c71a37](https://linux-hardware.org/?probe=1be8c71a37) | May 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [6e43e1d4f1](https://linux-hardware.org/?probe=6e43e1d4f1) | May 30, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [2669150033](https://linux-hardware.org/?probe=2669150033) | May 29, 2022 |
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
| TUXEDO        | InfinityBook Pro 14 Gen6    | [e0ae9fa252](https://linux-hardware.org/?probe=e0ae9fa252) | Mar 24, 2022 |
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
| HP            | OMEN by Laptop 15-dc1xxx    | [7c883d58c6](https://linux-hardware.org/?probe=7c883d58c6) | Apr 10, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [7e5120fd67](https://linux-hardware.org/?probe=7e5120fd67) | Apr 06, 2021 |
| Dell          | Latitude X1                 | [a35f6c0969](https://linux-hardware.org/?probe=a35f6c0969) | Apr 05, 2021 |
| Dell          | Latitude 5480               | [a61529e37c](https://linux-hardware.org/?probe=a61529e37c) | Apr 03, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | [66d76dda01](https://linux-hardware.org/?probe=66d76dda01) | Apr 03, 2021 |
| Dell          | Latitude X1                 | [1e053513e0](https://linux-hardware.org/?probe=1e053513e0) | Apr 03, 2021 |
| MSI           | GE62 6QD                    | [d76949a11c](https://linux-hardware.org/?probe=d76949a11c) | Apr 01, 2021 |
| ASUSTek       | N501VW                      | [46863f1f90](https://linux-hardware.org/?probe=46863f1f90) | Mar 24, 2021 |
| HP            | ProBook 430 G7              | [fbf317133b](https://linux-hardware.org/?probe=fbf317133b) | Mar 21, 2021 |
| ASUSTek       | 1000H                       | [eda3ceb029](https://linux-hardware.org/?probe=eda3ceb029) | Mar 18, 2021 |
| Dell          | XPS 13 9380                 | [a8f5a8232e](https://linux-hardware.org/?probe=a8f5a8232e) | Mar 17, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [65f8817baf](https://linux-hardware.org/?probe=65f8817baf) | Mar 17, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | [b96252ab8f](https://linux-hardware.org/?probe=b96252ab8f) | Mar 15, 2021 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [aac20e8dce](https://linux-hardware.org/?probe=aac20e8dce) | Mar 15, 2021 |
| Lenovo        | ThinkPad T470s 20HFCTO1W... | [6c33ce2e79](https://linux-hardware.org/?probe=6c33ce2e79) | Mar 14, 2021 |
| Dell          | Inspiron 3537               | [66ce284547](https://linux-hardware.org/?probe=66ce284547) | Mar 14, 2021 |
| HP            | Laptop 15-bs1xx             | [bd1886f540](https://linux-hardware.org/?probe=bd1886f540) | Mar 14, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [14d6107700](https://linux-hardware.org/?probe=14d6107700) | Mar 13, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [3043c4c8ed](https://linux-hardware.org/?probe=3043c4c8ed) | Mar 13, 2021 |
| HP            | ZBook Power G7 Mobile Wo... | [edbe4b927f](https://linux-hardware.org/?probe=edbe4b927f) | Mar 12, 2021 |
| HP            | Laptop 15s-eq0xxx           | [ed79695034](https://linux-hardware.org/?probe=ed79695034) | Mar 12, 2021 |
| Dell          | Inspiron 3537               | [f85fc12bff](https://linux-hardware.org/?probe=f85fc12bff) | Mar 09, 2021 |
| Dell          | Latitude 5410               | [f7ff0d1881](https://linux-hardware.org/?probe=f7ff0d1881) | Mar 07, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [461b5d7b4b](https://linux-hardware.org/?probe=461b5d7b4b) | Mar 06, 2021 |
| Dell          | Latitude 5410               | [2f64a4536e](https://linux-hardware.org/?probe=2f64a4536e) | Mar 06, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [50a76385ba](https://linux-hardware.org/?probe=50a76385ba) | Mar 05, 2021 |
| Dell          | XPS 13 9310                 | [ebc962c6c8](https://linux-hardware.org/?probe=ebc962c6c8) | Mar 05, 2021 |
| Dell          | XPS 13 9310                 | [d7384efac7](https://linux-hardware.org/?probe=d7384efac7) | Mar 05, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [eb357781c5](https://linux-hardware.org/?probe=eb357781c5) | Mar 04, 2021 |
| HP            | Pavilion Notebook           | [18e2e1ba5d](https://linux-hardware.org/?probe=18e2e1ba5d) | Mar 04, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [ff0e82cc06](https://linux-hardware.org/?probe=ff0e82cc06) | Mar 03, 2021 |
| HP            | ProBook 450 G5              | [f343af14eb](https://linux-hardware.org/?probe=f343af14eb) | Mar 03, 2021 |
| Toshiba       | NB100                       | [7876cca0bb](https://linux-hardware.org/?probe=7876cca0bb) | Mar 03, 2021 |
| HP            | ProBook 450 G5              | [0cf52b6b45](https://linux-hardware.org/?probe=0cf52b6b45) | Mar 03, 2021 |
| ASUSTek       | ASUSPRO P2540FAC_P2540FA    | [723ba4e443](https://linux-hardware.org/?probe=723ba4e443) | Feb 28, 2021 |
| Lenovo        | ThinkPad X220 4286CTO       | [f9cf2ced7e](https://linux-hardware.org/?probe=f9cf2ced7e) | Feb 28, 2021 |
| Dell          | G3 3500                     | [784b943c30](https://linux-hardware.org/?probe=784b943c30) | Feb 28, 2021 |
| Lenovo        | Yoga Slim 7 14IIL05 82A1    | [f2ce82aade](https://linux-hardware.org/?probe=f2ce82aade) | Feb 27, 2021 |
| Lenovo        | Yoga Slim 7 14IIL05 82A1    | [83b0002691](https://linux-hardware.org/?probe=83b0002691) | Feb 27, 2021 |
| Lenovo        | ThinkPad P53 20QN001JUS     | [b8542f3302](https://linux-hardware.org/?probe=b8542f3302) | Feb 27, 2021 |
| Lenovo        | ThinkBook 14s-IWL 20RM      | [922d2a406f](https://linux-hardware.org/?probe=922d2a406f) | Feb 26, 2021 |
| Acer          | Nitro AN515-52              | [99ee0e5718](https://linux-hardware.org/?probe=99ee0e5718) | Feb 24, 2021 |
| Acer          | Nitro AN515-52              | [89497c0f27](https://linux-hardware.org/?probe=89497c0f27) | Feb 23, 2021 |
| TUXEDO        | Unknown                     | [ad91e37e92](https://linux-hardware.org/?probe=ad91e37e92) | Feb 22, 2021 |
| HP            | Pavilion Notebook           | [e6ea03de75](https://linux-hardware.org/?probe=e6ea03de75) | Feb 21, 2021 |
| HP            | EliteBook 820 G3            | [e9e3b904a9](https://linux-hardware.org/?probe=e9e3b904a9) | Feb 19, 2021 |
| HP            | ProBook 450 G5              | [757c263c73](https://linux-hardware.org/?probe=757c263c73) | Feb 17, 2021 |
| ASUSTek       | G2SV                        | [2dcd0e4e69](https://linux-hardware.org/?probe=2dcd0e4e69) | Feb 15, 2021 |
| ASUSTek       | G2SV                        | [5b8e446be1](https://linux-hardware.org/?probe=5b8e446be1) | Feb 15, 2021 |
| TUXEDO        | Unknown                     | [c1b424bc28](https://linux-hardware.org/?probe=c1b424bc28) | Feb 15, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [418d6ee98e](https://linux-hardware.org/?probe=418d6ee98e) | Feb 13, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [d2a976e336](https://linux-hardware.org/?probe=d2a976e336) | Feb 13, 2021 |
| HP            | OMEN by Laptop              | [d20f245092](https://linux-hardware.org/?probe=d20f245092) | Feb 13, 2021 |
| Acer          | Nitro AN515-53              | [66e023417c](https://linux-hardware.org/?probe=66e023417c) | Feb 13, 2021 |
| Lenovo        | ThinkPad T450 20BUS0370P    | [de910b3b6f](https://linux-hardware.org/?probe=de910b3b6f) | Feb 11, 2021 |
| HP            | EliteBook 820 G3            | [0dcb414448](https://linux-hardware.org/?probe=0dcb414448) | Feb 10, 2021 |
| Lenovo        | ThinkPad X390 20Q0CTO1WW    | [c77ec688d3](https://linux-hardware.org/?probe=c77ec688d3) | Feb 08, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | [d45ff60cd3](https://linux-hardware.org/?probe=d45ff60cd3) | Feb 08, 2021 |
| Lenovo        | ThinkPad X250 20CLS2B000    | [49814ed1ce](https://linux-hardware.org/?probe=49814ed1ce) | Feb 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [d538017b75](https://linux-hardware.org/?probe=d538017b75) | Feb 04, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [1df927bea6](https://linux-hardware.org/?probe=1df927bea6) | Feb 03, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [39c3dd1edd](https://linux-hardware.org/?probe=39c3dd1edd) | Feb 02, 2021 |
| Dell          | XPS 13 9370                 | [8e541c3c46](https://linux-hardware.org/?probe=8e541c3c46) | Feb 01, 2021 |
| HP            | Unknown                     | [437cd35d62](https://linux-hardware.org/?probe=437cd35d62) | Jan 28, 2021 |
| Chuwi         | UBook Pro                   | [d82fb9fdaf](https://linux-hardware.org/?probe=d82fb9fdaf) | Jan 26, 2021 |
| Google        | Peppy                       | [0b7e4ccb8e](https://linux-hardware.org/?probe=0b7e4ccb8e) | Jan 26, 2021 |
| HP            | Unknown                     | [db1b52d959](https://linux-hardware.org/?probe=db1b52d959) | Jan 19, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [88cf2bc0f5](https://linux-hardware.org/?probe=88cf2bc0f5) | Jan 15, 2021 |
| Lenovo        | Unknown                     | [38c41d5178](https://linux-hardware.org/?probe=38c41d5178) | Jan 13, 2021 |
| IT Channel... | PA70ES                      | [f5671ea0b0](https://linux-hardware.org/?probe=f5671ea0b0) | Jan 11, 2021 |
| ASUSTek       | X555LJ                      | [1b20a57823](https://linux-hardware.org/?probe=1b20a57823) | Jan 10, 2021 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [77af1025e7](https://linux-hardware.org/?probe=77af1025e7) | Jan 08, 2021 |
| HP            | Pavilion dm1                | [db518ed539](https://linux-hardware.org/?probe=db518ed539) | Jan 08, 2021 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [ae395b2f7a](https://linux-hardware.org/?probe=ae395b2f7a) | Jan 06, 2021 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [f3d55068a4](https://linux-hardware.org/?probe=f3d55068a4) | Jan 06, 2021 |
| ASUSTek       | A7V                         | [79a40b4127](https://linux-hardware.org/?probe=79a40b4127) | Jan 06, 2021 |
| Lenovo        | ThinkPad T480 20L5000WUS    | [d6cb8dec76](https://linux-hardware.org/?probe=d6cb8dec76) | Jan 05, 2021 |
| HP            | ZBook 15 G4                 | [46ee3cd25c](https://linux-hardware.org/?probe=46ee3cd25c) | Jan 04, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [367d882a57](https://linux-hardware.org/?probe=367d882a57) | Jan 04, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [39cec3e63e](https://linux-hardware.org/?probe=39cec3e63e) | Jan 03, 2021 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | [4460990877](https://linux-hardware.org/?probe=4460990877) | Jan 02, 2021 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | [3f3cc6b9d6](https://linux-hardware.org/?probe=3f3cc6b9d6) | Jan 02, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [96374442c4](https://linux-hardware.org/?probe=96374442c4) | Jan 02, 2021 |
| Unknown       | Unknown                     | [1eb453e2b1](https://linux-hardware.org/?probe=1eb453e2b1) | Jan 02, 2021 |
| Unknown       | Unknown                     | [fee86bed02](https://linux-hardware.org/?probe=fee86bed02) | Dec 31, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [61ce6be19c](https://linux-hardware.org/?probe=61ce6be19c) | Dec 29, 2020 |
| HP            | Pavilion Notebook           | [4301611dfb](https://linux-hardware.org/?probe=4301611dfb) | Dec 28, 2020 |
| Dell          | XPS 13 9380                 | [021a0a73f4](https://linux-hardware.org/?probe=021a0a73f4) | Dec 27, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [8a19941ffe](https://linux-hardware.org/?probe=8a19941ffe) | Dec 26, 2020 |
| ASUSTek       | X550ZE                      | [8cf715c40b](https://linux-hardware.org/?probe=8cf715c40b) | Dec 23, 2020 |
| ASUSTek       | X550ZE                      | [e3e9f32f6d](https://linux-hardware.org/?probe=e3e9f32f6d) | Dec 23, 2020 |
| Toshiba       | NB100                       | [01daa00e87](https://linux-hardware.org/?probe=01daa00e87) | Dec 19, 2020 |
| Unknown       | Unknown                     | [bf1f9d4982](https://linux-hardware.org/?probe=bf1f9d4982) | Dec 17, 2020 |
| Unknown       | Unknown                     | [5f4a9f2dc3](https://linux-hardware.org/?probe=5f4a9f2dc3) | Dec 17, 2020 |
| Dell          | Latitude 7390               | [30de38003f](https://linux-hardware.org/?probe=30de38003f) | Dec 16, 2020 |
| Acer          | Swift SF314-42              | [6e2749f503](https://linux-hardware.org/?probe=6e2749f503) | Dec 16, 2020 |
| HP            | Laptop 15-bs0xx             | [6b216f692c](https://linux-hardware.org/?probe=6b216f692c) | Dec 15, 2020 |
| Dell          | XPS 15 7590                 | [4312c9878e](https://linux-hardware.org/?probe=4312c9878e) | Dec 14, 2020 |
| Lenovo        | ThinkPad X201 3249CTO       | [a4e14d24c6](https://linux-hardware.org/?probe=a4e14d24c6) | Dec 13, 2020 |
| Lenovo        | ThinkPad P52s 20LBS0FF00    | [4826998fda](https://linux-hardware.org/?probe=4826998fda) | Dec 12, 2020 |
| HP            | ProBook 430 G5              | [c9a8c10a8f](https://linux-hardware.org/?probe=c9a8c10a8f) | Dec 10, 2020 |
| Samsung       | RC530/RC730                 | [69c8fa5fee](https://linux-hardware.org/?probe=69c8fa5fee) | Dec 09, 2020 |
| MSI           | GF63 Thin 9SC               | [5a23e8cfc4](https://linux-hardware.org/?probe=5a23e8cfc4) | Dec 06, 2020 |
| Dell          | XPS 13 9370                 | [bd8f5aa7df](https://linux-hardware.org/?probe=bd8f5aa7df) | Dec 05, 2020 |
| HP            | Pavilion Notebook           | [193e7f8bf4](https://linux-hardware.org/?probe=193e7f8bf4) | Dec 01, 2020 |
| Toshiba       | NB100                       | [73e92718a9](https://linux-hardware.org/?probe=73e92718a9) | Dec 01, 2020 |
| HP            | Unknown                     | [6ecc666f9f](https://linux-hardware.org/?probe=6ecc666f9f) | Dec 01, 2020 |
| Lenovo        | ThinkPad P50 20EQS30D00     | [356758a7d8](https://linux-hardware.org/?probe=356758a7d8) | Nov 30, 2020 |
| Dell          | XPS 13 9370                 | [60ec1448d4](https://linux-hardware.org/?probe=60ec1448d4) | Nov 29, 2020 |
| Dell          | Latitude E5500              | [079101f502](https://linux-hardware.org/?probe=079101f502) | Nov 29, 2020 |
| Dell          | XPS 15 9570                 | [613707835e](https://linux-hardware.org/?probe=613707835e) | Nov 24, 2020 |
| HUAWEI        | BOHK-WAX9X                  | [23418fe6cc](https://linux-hardware.org/?probe=23418fe6cc) | Nov 19, 2020 |
| HP            | OMEN by Laptop 17-cb0xxx    | [43f7b0ed5e](https://linux-hardware.org/?probe=43f7b0ed5e) | Nov 16, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [49a0bab061](https://linux-hardware.org/?probe=49a0bab061) | Nov 15, 2020 |
| Lenovo        | Yoga 2 13 20344             | [5d53e48607](https://linux-hardware.org/?probe=5d53e48607) | Nov 15, 2020 |
| Lenovo        | Yoga 2 13 20344             | [a3a3bd1c26](https://linux-hardware.org/?probe=a3a3bd1c26) | Nov 14, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [a175dbabc2](https://linux-hardware.org/?probe=a175dbabc2) | Nov 12, 2020 |
| Dell          | Latitude 5490               | [894bd38b38](https://linux-hardware.org/?probe=894bd38b38) | Nov 11, 2020 |
| Timi          | Mi Laptop Pro 15            | [28c7cf4458](https://linux-hardware.org/?probe=28c7cf4458) | Nov 11, 2020 |
| Timi          | Mi Laptop Pro 15            | [b4fbf1f2e6](https://linux-hardware.org/?probe=b4fbf1f2e6) | Nov 11, 2020 |
| HP            | EliteBook 820 G4            | [13e0c5e646](https://linux-hardware.org/?probe=13e0c5e646) | Nov 10, 2020 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [3a052bbb91](https://linux-hardware.org/?probe=3a052bbb91) | Nov 09, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [53efc559ad](https://linux-hardware.org/?probe=53efc559ad) | Nov 08, 2020 |
| Dell          | XPS 13 9360                 | [a6cf5e7036](https://linux-hardware.org/?probe=a6cf5e7036) | Nov 07, 2020 |
| Dell          | Latitude 7410               | [af066ad306](https://linux-hardware.org/?probe=af066ad306) | Nov 04, 2020 |
| Acer          | Nitro AN715-51              | [8cb76bb2f8](https://linux-hardware.org/?probe=8cb76bb2f8) | Nov 03, 2020 |
| Acer          | Nitro AN715-51              | [485080dff0](https://linux-hardware.org/?probe=485080dff0) | Nov 03, 2020 |
| Dell          | G3 3500                     | [fb7c201de0](https://linux-hardware.org/?probe=fb7c201de0) | Nov 01, 2020 |
| Acer          | Aspire E5-771G              | [9d967e969d](https://linux-hardware.org/?probe=9d967e969d) | Nov 01, 2020 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | [ec44c959a4](https://linux-hardware.org/?probe=ec44c959a4) | Nov 01, 2020 |
| Lenovo        | Legion R7000P2020H 82GR     | [907de62181](https://linux-hardware.org/?probe=907de62181) | Oct 31, 2020 |
| Lenovo        | B51-80 80LM                 | [c40197b546](https://linux-hardware.org/?probe=c40197b546) | Oct 27, 2020 |
| Sony          | VPCSC41FM                   | [a7607a7b93](https://linux-hardware.org/?probe=a7607a7b93) | Oct 26, 2020 |
| HP            | Laptop 14-cf0xxx            | [5ae192d7e1](https://linux-hardware.org/?probe=5ae192d7e1) | Oct 26, 2020 |
| Lenovo        | ThinkPad X13 Gen 1 20UFC... | [ef90a9df54](https://linux-hardware.org/?probe=ef90a9df54) | Oct 25, 2020 |
| Lenovo        | ThinkPad P53 20QN001JUS     | [c15ef33580](https://linux-hardware.org/?probe=c15ef33580) | Oct 25, 2020 |
| Acer          | Aspire E5-571G              | [b52fb33c4d](https://linux-hardware.org/?probe=b52fb33c4d) | Oct 25, 2020 |
| HP            | Pavilion g7                 | [585d199b71](https://linux-hardware.org/?probe=585d199b71) | Oct 25, 2020 |
| HP            | Laptop 14-cf0xxx            | [8999670eb2](https://linux-hardware.org/?probe=8999670eb2) | Oct 25, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [447a3a003d](https://linux-hardware.org/?probe=447a3a003d) | Oct 25, 2020 |
| HP            | ProBook 430 G5              | [f8f15c63ad](https://linux-hardware.org/?probe=f8f15c63ad) | Oct 25, 2020 |
| HP            | ProBook 430 G5              | [b3df3d26f0](https://linux-hardware.org/?probe=b3df3d26f0) | Oct 24, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [f0cf2671f2](https://linux-hardware.org/?probe=f0cf2671f2) | Oct 24, 2020 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | [77849f8db0](https://linux-hardware.org/?probe=77849f8db0) | Oct 23, 2020 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | [77d6dd66e2](https://linux-hardware.org/?probe=77d6dd66e2) | Oct 23, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [30cef457c4](https://linux-hardware.org/?probe=30cef457c4) | Oct 19, 2020 |
| HP            | ProBook 455 G7              | [70aaf58443](https://linux-hardware.org/?probe=70aaf58443) | Oct 19, 2020 |
| HP            | Pavilion dv7                | [65917ebd9d](https://linux-hardware.org/?probe=65917ebd9d) | Oct 18, 2020 |
| Dell          | XPS 15 7590                 | [daa70ce737](https://linux-hardware.org/?probe=daa70ce737) | Oct 17, 2020 |
| HP            | EliteBook 820 G4            | [ea2fe3b4dc](https://linux-hardware.org/?probe=ea2fe3b4dc) | Oct 15, 2020 |
| Lenovo        | ThinkPad T470s 20HGS0W10... | [64c3cf228e](https://linux-hardware.org/?probe=64c3cf228e) | Oct 14, 2020 |
| Dell          | Latitude E7270              | [efcbc76194](https://linux-hardware.org/?probe=efcbc76194) | Oct 12, 2020 |
| Dell          | Latitude E7270              | [6199eaf93c](https://linux-hardware.org/?probe=6199eaf93c) | Oct 12, 2020 |
| Dell          | Latitude E7270              | [c04da65193](https://linux-hardware.org/?probe=c04da65193) | Oct 11, 2020 |
| Fujitsu       | LIFEBOOK P770               | [48fc4ff4db](https://linux-hardware.org/?probe=48fc4ff4db) | Oct 10, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [5cd90973fc](https://linux-hardware.org/?probe=5cd90973fc) | Oct 04, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [9c5d15be62](https://linux-hardware.org/?probe=9c5d15be62) | Oct 04, 2020 |
| Dell          | G5 5587                     | [c99b5f8c72](https://linux-hardware.org/?probe=c99b5f8c72) | Oct 02, 2020 |
| ASUSTek       | X555LJ                      | [bd5306ec57](https://linux-hardware.org/?probe=bd5306ec57) | Oct 01, 2020 |
| HP            | Pavilion Notebook           | [85a733886a](https://linux-hardware.org/?probe=85a733886a) | Sep 29, 2020 |
| Dell          | G3 3500                     | [23b58bcd77](https://linux-hardware.org/?probe=23b58bcd77) | Sep 25, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [96d1d6229b](https://linux-hardware.org/?probe=96d1d6229b) | Sep 23, 2020 |
| HP            | Pavilion ZV6100 (EE984EA... | [951fafbea0](https://linux-hardware.org/?probe=951fafbea0) | Sep 19, 2020 |
| HP            | Pavilion ZV6100 (EE984EA... | [e638fa0818](https://linux-hardware.org/?probe=e638fa0818) | Sep 19, 2020 |
| HP            | Pavilion Notebook           | [a1e9bd74fd](https://linux-hardware.org/?probe=a1e9bd74fd) | Sep 17, 2020 |
| Lenovo        | Unknown                     | [5107d64dc0](https://linux-hardware.org/?probe=5107d64dc0) | Sep 16, 2020 |
| HP            | ProBook 450 G5              | [9d3b97061b](https://linux-hardware.org/?probe=9d3b97061b) | Sep 15, 2020 |
| HP            | ProBook 450 G5              | [4d67605a9a](https://linux-hardware.org/?probe=4d67605a9a) | Sep 14, 2020 |
| Dell          | G3 3500                     | [73839e86fc](https://linux-hardware.org/?probe=73839e86fc) | Sep 14, 2020 |
| PC Special... | GK7NP5R                     | [2ba7289378](https://linux-hardware.org/?probe=2ba7289378) | Sep 11, 2020 |
| Dell          | Latitude 5501               | [bceeec9520](https://linux-hardware.org/?probe=bceeec9520) | Sep 10, 2020 |
| Dell          | Latitude 5501               | [0df822dc02](https://linux-hardware.org/?probe=0df822dc02) | Sep 09, 2020 |
| Lenovo        | ThinkPad X220 429029G       | [2e86679c2f](https://linux-hardware.org/?probe=2e86679c2f) | Sep 05, 2020 |
| Apple         | MacBookPro12,1              | [0f915dee52](https://linux-hardware.org/?probe=0f915dee52) | Sep 03, 2020 |
| Lenovo        | Legion 5P 15IMH05H 82AW     | [294fd98c3f](https://linux-hardware.org/?probe=294fd98c3f) | Sep 01, 2020 |
| HUAWEI        | HLY-WX9XX                   | [51bcf816e6](https://linux-hardware.org/?probe=51bcf816e6) | Sep 01, 2020 |
| Apple         | MacBookPro12,1              | [08ca1bc0c6](https://linux-hardware.org/?probe=08ca1bc0c6) | Aug 31, 2020 |
| HP            | Pavilion 11 x360 PC         | [2857ef3b7b](https://linux-hardware.org/?probe=2857ef3b7b) | Aug 30, 2020 |
| Dell          | Latitude 5401               | [fdb1d25e99](https://linux-hardware.org/?probe=fdb1d25e99) | Aug 27, 2020 |
| ASUSTek       | GL552VW                     | [9462a9e9ec](https://linux-hardware.org/?probe=9462a9e9ec) | Aug 26, 2020 |
| ASUSTek       | GL552VW                     | [1e5df72d90](https://linux-hardware.org/?probe=1e5df72d90) | Aug 25, 2020 |
| Lenovo        | ThinkPad P53 20QN001JUS     | [63d74a10a6](https://linux-hardware.org/?probe=63d74a10a6) | Aug 25, 2020 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [5590d3f68a](https://linux-hardware.org/?probe=5590d3f68a) | Aug 25, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [744c56e875](https://linux-hardware.org/?probe=744c56e875) | Aug 25, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [a0960a7256](https://linux-hardware.org/?probe=a0960a7256) | Aug 25, 2020 |
| Dell          | XPS 15 7590                 | [1ecbfe31cc](https://linux-hardware.org/?probe=1ecbfe31cc) | Aug 23, 2020 |
| Dell          | Latitude E6530              | [d475ab6b1f](https://linux-hardware.org/?probe=d475ab6b1f) | Aug 23, 2020 |
| Dell          | Latitude E6530              | [25f98c006e](https://linux-hardware.org/?probe=25f98c006e) | Aug 23, 2020 |
| Dell          | Latitude E6530              | [c2d9b7b8f9](https://linux-hardware.org/?probe=c2d9b7b8f9) | Aug 23, 2020 |
| Lenovo        | ThinkPad E495 20NECTO1WW    | [7c299b5384](https://linux-hardware.org/?probe=7c299b5384) | Aug 23, 2020 |
| Lenovo        | ThinkPad E495 20NECTO1WW    | [19586f3d92](https://linux-hardware.org/?probe=19586f3d92) | Aug 23, 2020 |
| Lenovo        | ThinkPad P53 20QN001JUS     | [d5c4efd016](https://linux-hardware.org/?probe=d5c4efd016) | Aug 23, 2020 |
| Lenovo        | Legion 5P 15IMH05H 82AW     | [c82c12e968](https://linux-hardware.org/?probe=c82c12e968) | Aug 22, 2020 |
| Notebook      | N141CU                      | [9c7c4fff3e](https://linux-hardware.org/?probe=9c7c4fff3e) | Aug 22, 2020 |
| Wortmann      | TERRA_MOBILE_1590S          | [ade9df5306](https://linux-hardware.org/?probe=ade9df5306) | Aug 21, 2020 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [8f067e33b6](https://linux-hardware.org/?probe=8f067e33b6) | Aug 21, 2020 |
| Dell          | G3 3500                     | [093682c4c4](https://linux-hardware.org/?probe=093682c4c4) | Aug 20, 2020 |
| Lenovo        | G580 20150                  | [1e7c1ee27a](https://linux-hardware.org/?probe=1e7c1ee27a) | Aug 20, 2020 |
| Dell          | G3 3500                     | [c64b8a0e61](https://linux-hardware.org/?probe=c64b8a0e61) | Aug 20, 2020 |
| Lenovo        | ThinkPad T590 20N4001YPB    | [c6283736fd](https://linux-hardware.org/?probe=c6283736fd) | Aug 19, 2020 |
| HP            | Pavilion Notebook           | [2afa749d39](https://linux-hardware.org/?probe=2afa749d39) | Aug 19, 2020 |
| Lenovo        | Legion 5P 15IMH05H 82AW     | [fd339f3d69](https://linux-hardware.org/?probe=fd339f3d69) | Aug 17, 2020 |
| Lenovo        | Legion Y540-15IRH 81SX      | [19177595c8](https://linux-hardware.org/?probe=19177595c8) | Aug 16, 2020 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | [9d003ef2fe](https://linux-hardware.org/?probe=9d003ef2fe) | Aug 16, 2020 |
| Lenovo        | Legion Y540-15IRH 81SX      | [c7793f1daa](https://linux-hardware.org/?probe=c7793f1daa) | Aug 15, 2020 |
| Apple         | MacBookPro4,1               | [184e80bbc6](https://linux-hardware.org/?probe=184e80bbc6) | Aug 13, 2020 |
| Apple         | MacBookPro4,1               | [64593dd4a6](https://linux-hardware.org/?probe=64593dd4a6) | Aug 13, 2020 |
| Dell          | Inspiron 5755               | [89d1209c2c](https://linux-hardware.org/?probe=89d1209c2c) | Aug 12, 2020 |
| Notebook      | N141CU                      | [38cc94083d](https://linux-hardware.org/?probe=38cc94083d) | Aug 10, 2020 |
| Apple         | MacBookPro8,2               | [1dd9ee1d09](https://linux-hardware.org/?probe=1dd9ee1d09) | Aug 09, 2020 |
| Apple         | MacBookPro8,1               | [092f544ecc](https://linux-hardware.org/?probe=092f544ecc) | Aug 08, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [4fe8ac3a02](https://linux-hardware.org/?probe=4fe8ac3a02) | Aug 08, 2020 |
| Dell          | XPS 15 9570                 | [7b17868903](https://linux-hardware.org/?probe=7b17868903) | Aug 07, 2020 |
| Lenovo        | ThinkPad X270 20HN002UGE    | [c0b7a3c300](https://linux-hardware.org/?probe=c0b7a3c300) | Aug 07, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [a7ae8a6f78](https://linux-hardware.org/?probe=a7ae8a6f78) | Aug 07, 2020 |
| ASUSTek       | X406UAR                     | [97f52734c2](https://linux-hardware.org/?probe=97f52734c2) | Aug 06, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [d67ba67beb](https://linux-hardware.org/?probe=d67ba67beb) | Aug 05, 2020 |
| Lenovo        | Legion R7000 2020 82B6      | [b948b0ffe7](https://linux-hardware.org/?probe=b948b0ffe7) | Aug 03, 2020 |
| Lenovo        | Legion R7000 2020 82B6      | [0f826bb295](https://linux-hardware.org/?probe=0f826bb295) | Aug 03, 2020 |
| Apple         | MacBookPro5,1               | [c896b174a5](https://linux-hardware.org/?probe=c896b174a5) | Aug 03, 2020 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | [4c08ca19cf](https://linux-hardware.org/?probe=4c08ca19cf) | Jul 30, 2020 |
| Dell          | Latitude 5500               | [4e1eb098f2](https://linux-hardware.org/?probe=4e1eb098f2) | Jul 28, 2020 |
| Sony          | VPCSC41FM                   | [3a1470664d](https://linux-hardware.org/?probe=3a1470664d) | Jul 24, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [a235d0f3c3](https://linux-hardware.org/?probe=a235d0f3c3) | Jul 21, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [68c95d0921](https://linux-hardware.org/?probe=68c95d0921) | Jul 17, 2020 |
| Acer          | Nitro AN515-53              | [85bf9e9450](https://linux-hardware.org/?probe=85bf9e9450) | Jul 17, 2020 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | [43a917118a](https://linux-hardware.org/?probe=43a917118a) | Jul 14, 2020 |
| XMG           | C504                        | [a97e52282c](https://linux-hardware.org/?probe=a97e52282c) | Jul 13, 2020 |
| System76      | Lemur Pro                   | [ef0445b033](https://linux-hardware.org/?probe=ef0445b033) | Jul 09, 2020 |
| HP            | EliteBook 745 G6            | [b7f42e3bd9](https://linux-hardware.org/?probe=b7f42e3bd9) | Jul 06, 2020 |
| HP            | EliteBook 745 G6            | [d73fb2d895](https://linux-hardware.org/?probe=d73fb2d895) | Jul 05, 2020 |
| Lenovo        | ThinkPad A485 20MUCTO1WW    | [359f4615fa](https://linux-hardware.org/?probe=359f4615fa) | Jul 03, 2020 |
| Lenovo        | ThinkPad X100e 35089TU      | [6dccb35fcb](https://linux-hardware.org/?probe=6dccb35fcb) | Jul 03, 2020 |
| HP            | EliteBook 820 G4            | [9729dd440a](https://linux-hardware.org/?probe=9729dd440a) | Jul 03, 2020 |
| HP            | EliteBook 820 G4            | [26a392b2c1](https://linux-hardware.org/?probe=26a392b2c1) | Jul 03, 2020 |
| Samsung       | R530/R730/P530              | [e1539a8d98](https://linux-hardware.org/?probe=e1539a8d98) | Jul 01, 2020 |
| Dell          | Latitude 5491               | [f861e71f84](https://linux-hardware.org/?probe=f861e71f84) | Jun 28, 2020 |
| Acer          | Nitro AN515-53              | [64802f828b](https://linux-hardware.org/?probe=64802f828b) | Jun 27, 2020 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [71beca8605](https://linux-hardware.org/?probe=71beca8605) | Jun 25, 2020 |
| Lenovo        | Legion R7000 2020 82B6      | [723898cdec](https://linux-hardware.org/?probe=723898cdec) | Jun 20, 2020 |
| Lenovo        | G710 20252                  | [f83c73bef0](https://linux-hardware.org/?probe=f83c73bef0) | Jun 15, 2020 |
| Dell          | Latitude 5480               | [d0d56fbb1d](https://linux-hardware.org/?probe=d0d56fbb1d) | Jun 14, 2020 |
| Acer          | Nitro AN515-53              | [701ffbf49a](https://linux-hardware.org/?probe=701ffbf49a) | Jun 12, 2020 |
| Dell          | XPS 13 9360                 | [b4be1dd313](https://linux-hardware.org/?probe=b4be1dd313) | Jun 09, 2020 |
| Acer          | Swift SF315-51              | [e703cb72e3](https://linux-hardware.org/?probe=e703cb72e3) | Jun 08, 2020 |
| Dell          | XPS 15 9530                 | [b93caec229](https://linux-hardware.org/?probe=b93caec229) | Jun 07, 2020 |
| Lenovo        | ThinkPad X230 232425J       | [2ebe6149b7](https://linux-hardware.org/?probe=2ebe6149b7) | Jun 06, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [ca7ca5b14e](https://linux-hardware.org/?probe=ca7ca5b14e) | Jun 06, 2020 |
| Lenovo        | ThinkPad P52 20M9001LMC     | [2902bb9460](https://linux-hardware.org/?probe=2902bb9460) | Jun 06, 2020 |
| Lenovo        | ThinkPad P52 20M9001LMC     | [065bddf59b](https://linux-hardware.org/?probe=065bddf59b) | Jun 06, 2020 |
| Dell          | Latitude E5570              | [e7012f0658](https://linux-hardware.org/?probe=e7012f0658) | Jun 05, 2020 |
| Dell          | System XPS L702X            | [a993cb7099](https://linux-hardware.org/?probe=a993cb7099) | Jun 04, 2020 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | [b52ad09036](https://linux-hardware.org/?probe=b52ad09036) | Jun 04, 2020 |
| Dell          | XPS 13 9360                 | [e1d648a5f2](https://linux-hardware.org/?probe=e1d648a5f2) | Jun 04, 2020 |
| Lenovo        | ThinkPad L390 20NR001KRT    | [19809108e4](https://linux-hardware.org/?probe=19809108e4) | Jun 04, 2020 |
| Dell          | Inspiron 5577               | [b29e45343d](https://linux-hardware.org/?probe=b29e45343d) | Jun 04, 2020 |
| ASUSTek       | X555LJ                      | [8a0dab5948](https://linux-hardware.org/?probe=8a0dab5948) | Jun 03, 2020 |
| Apple         | MacBookPro12,1              | [a173aacb52](https://linux-hardware.org/?probe=a173aacb52) | Jun 03, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [d082b8d834](https://linux-hardware.org/?probe=d082b8d834) | Jun 03, 2020 |
| ASUSTek       | UX310UAR                    | [1b9a59e4ca](https://linux-hardware.org/?probe=1b9a59e4ca) | Jun 03, 2020 |
| ASUSTek       | UX410UAR                    | [d3b1cf2698](https://linux-hardware.org/?probe=d3b1cf2698) | Jun 03, 2020 |
| Apple         | MacBookPro12,1              | [3b583f9685](https://linux-hardware.org/?probe=3b583f9685) | Jun 03, 2020 |
| HP            | Pavilion ZV6100 (EE984EA... | [31a6aa1e70](https://linux-hardware.org/?probe=31a6aa1e70) | May 31, 2020 |
| Acer          | Aspire VN7-592G             | [aa51c338b2](https://linux-hardware.org/?probe=aa51c338b2) | May 26, 2020 |
| MSI           | GT63 Titan 8SG              | [85363c0652](https://linux-hardware.org/?probe=85363c0652) | May 25, 2020 |
| Acer          | Aspire V3-771               | [910279b054](https://linux-hardware.org/?probe=910279b054) | May 25, 2020 |
| Lenovo        | ThinkPad X250 20CM004ESC    | [793c164825](https://linux-hardware.org/?probe=793c164825) | May 25, 2020 |
| Chuwi         | LapBook Pro                 | [a37835c09e](https://linux-hardware.org/?probe=a37835c09e) | May 25, 2020 |
| Chuwi         | LapBook Pro                 | [017c1e4813](https://linux-hardware.org/?probe=017c1e4813) | May 24, 2020 |
| Chuwi         | LapBook Pro                 | [a4be681659](https://linux-hardware.org/?probe=a4be681659) | May 23, 2020 |
| Timi          | Mi Laptop Air 12.5          | [fea499e36a](https://linux-hardware.org/?probe=fea499e36a) | May 23, 2020 |
| HP            | Unknown                     | [f8fa416688](https://linux-hardware.org/?probe=f8fa416688) | May 22, 2020 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [72f3e05699](https://linux-hardware.org/?probe=72f3e05699) | May 22, 2020 |
| Dell          | Latitude E6440              | [cb23d3096c](https://linux-hardware.org/?probe=cb23d3096c) | May 19, 2020 |
| Lenovo        | ThinkPad T490s 20NXCTO1W... | [25ed02b04a](https://linux-hardware.org/?probe=25ed02b04a) | May 19, 2020 |
| Dell          | Latitude E5540              | [8ea71ba2ae](https://linux-hardware.org/?probe=8ea71ba2ae) | May 19, 2020 |
| Unknown       | Unknown                     | [48a9c9544a](https://linux-hardware.org/?probe=48a9c9544a) | May 16, 2020 |
| Dell          | Latitude 3400               | [0787585d2e](https://linux-hardware.org/?probe=0787585d2e) | May 15, 2020 |
| Dell          | Latitude 3400               | [04b3381928](https://linux-hardware.org/?probe=04b3381928) | May 15, 2020 |
| Lenovo        | IdeaPad Z370                | [81a1579081](https://linux-hardware.org/?probe=81a1579081) | May 15, 2020 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [0efeb1e15a](https://linux-hardware.org/?probe=0efeb1e15a) | May 14, 2020 |
| Dell          | Latitude E6520              | [e275465d57](https://linux-hardware.org/?probe=e275465d57) | May 13, 2020 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [9e904a50ca](https://linux-hardware.org/?probe=9e904a50ca) | May 12, 2020 |
| Seco          | UDOO x86                    | [62ae920d77](https://linux-hardware.org/?probe=62ae920d77) | May 12, 2020 |
| Toshiba       | Satellite L50-A-16G         | [dea54eb8a1](https://linux-hardware.org/?probe=dea54eb8a1) | May 11, 2020 |
| Toshiba       | NB100                       | [3459eb4984](https://linux-hardware.org/?probe=3459eb4984) | May 11, 2020 |
| HP            | Unknown                     | [b52569877b](https://linux-hardware.org/?probe=b52569877b) | May 11, 2020 |
| HP            | Pavilion Notebook           | [57203b3010](https://linux-hardware.org/?probe=57203b3010) | May 11, 2020 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [748a1ea384](https://linux-hardware.org/?probe=748a1ea384) | May 11, 2020 |
| ASUSTek       | E402NA                      | [bc0fa6176d](https://linux-hardware.org/?probe=bc0fa6176d) | May 11, 2020 |
| Lenovo        | ThinkPad 20F6CTO1WW         | [b2649601d3](https://linux-hardware.org/?probe=b2649601d3) | May 10, 2020 |
| Unknown       | Unknown                     | [7740c04b4b](https://linux-hardware.org/?probe=7740c04b4b) | May 08, 2020 |
| ASUSTek       | Zephyrus M GU502GV_GU502... | [e0968088b3](https://linux-hardware.org/?probe=e0968088b3) | May 08, 2020 |
| Apple         | MacBookPro8,2               | [9602f32094](https://linux-hardware.org/?probe=9602f32094) | May 03, 2020 |
| Unknown       | Unknown                     | [97f8a22d28](https://linux-hardware.org/?probe=97f8a22d28) | May 03, 2020 |
| Lenovo        | ThinkPad L450 20DTS01R00    | [be25ab70cb](https://linux-hardware.org/?probe=be25ab70cb) | May 01, 2020 |
| HUAWEI        | BOHK-WAX9X                  | [729a079629](https://linux-hardware.org/?probe=729a079629) | Apr 28, 2020 |
| HUAWEI        | BOHK-WAX9X                  | [6e5f544240](https://linux-hardware.org/?probe=6e5f544240) | Apr 28, 2020 |
| Unknown       | Unknown                     | [eb36ed044f](https://linux-hardware.org/?probe=eb36ed044f) | Apr 26, 2020 |
| Dell          | Latitude E6420              | [f33530c32a](https://linux-hardware.org/?probe=f33530c32a) | Apr 26, 2020 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | [bf47e6f662](https://linux-hardware.org/?probe=bf47e6f662) | Apr 26, 2020 |
| Dell          | Latitude 7390               | [59c245d756](https://linux-hardware.org/?probe=59c245d756) | Apr 20, 2020 |
| Dell          | Latitude 7390               | [c91eb58962](https://linux-hardware.org/?probe=c91eb58962) | Apr 20, 2020 |
| Dell          | Latitude E5470              | [568a079f29](https://linux-hardware.org/?probe=568a079f29) | Apr 17, 2020 |
| Dell          | Latitude E7440              | [037a28c347](https://linux-hardware.org/?probe=037a28c347) | Apr 17, 2020 |
| Dell          | Latitude E5470              | [c2b554cdcf](https://linux-hardware.org/?probe=c2b554cdcf) | Apr 15, 2020 |
| HP            | x360 310 G1 PC              | [9751d299ad](https://linux-hardware.org/?probe=9751d299ad) | Apr 15, 2020 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | [c80d705080](https://linux-hardware.org/?probe=c80d705080) | Apr 12, 2020 |
| Dell          | Inspiron 7520               | [31c3181139](https://linux-hardware.org/?probe=31c3181139) | Apr 12, 2020 |
| Lenovo        | G570 20079                  | [af1e15f9d1](https://linux-hardware.org/?probe=af1e15f9d1) | Apr 11, 2020 |
| Lenovo        | XiaoXinPro-13IML 2019 81... | [ca529580d5](https://linux-hardware.org/?probe=ca529580d5) | Apr 10, 2020 |
| Acer          | Aspire V3-331               | [3556b592c2](https://linux-hardware.org/?probe=3556b592c2) | Apr 09, 2020 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | [89ce2a3948](https://linux-hardware.org/?probe=89ce2a3948) | Apr 05, 2020 |
| Dell          | Precision M4600             | [b88c9f527c](https://linux-hardware.org/?probe=b88c9f527c) | Apr 03, 2020 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | [de1b814a88](https://linux-hardware.org/?probe=de1b814a88) | Apr 02, 2020 |
| HP            | ProBook 4510s               | [26fb60e010](https://linux-hardware.org/?probe=26fb60e010) | Apr 01, 2020 |
| Acer          | Aspire VN7-571G             | [259bfff741](https://linux-hardware.org/?probe=259bfff741) | Mar 29, 2020 |
| Lenovo        | ThinkPad 20F6CTO1WW         | [6bc7d86b9c](https://linux-hardware.org/?probe=6bc7d86b9c) | Mar 28, 2020 |
| HP            | OMEN by Laptop              | [e7e39b1152](https://linux-hardware.org/?probe=e7e39b1152) | Mar 22, 2020 |
| HP            | OMEN by Laptop 17-cb0xxx    | [a42a77029d](https://linux-hardware.org/?probe=a42a77029d) | Mar 18, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [c3d3d42413](https://linux-hardware.org/?probe=c3d3d42413) | Mar 05, 2020 |
| Lenovo        | ThinkPad Z61m 945038U       | [e5c5ce1445](https://linux-hardware.org/?probe=e5c5ce1445) | Mar 01, 2020 |
| Dell          | XPS 15 7590                 | [fba41b433f](https://linux-hardware.org/?probe=fba41b433f) | Feb 27, 2020 |
| Acer          | Aspire V3-331               | [98986faf06](https://linux-hardware.org/?probe=98986faf06) | Feb 21, 2020 |
| Acer          | Aspire V3-331               | [400111ccfc](https://linux-hardware.org/?probe=400111ccfc) | Feb 21, 2020 |
| ASUSTek       | UX301LAA                    | [e994e96768](https://linux-hardware.org/?probe=e994e96768) | Feb 21, 2020 |
| ASUSTek       | UX301LAA                    | [4babc87322](https://linux-hardware.org/?probe=4babc87322) | Feb 21, 2020 |
| ASUSTek       | UX301LAA                    | [da5b70c7c6](https://linux-hardware.org/?probe=da5b70c7c6) | Feb 21, 2020 |
| MSI           | GT73EVR 7RF                 | [99e70d86e2](https://linux-hardware.org/?probe=99e70d86e2) | Feb 18, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [d140409c65](https://linux-hardware.org/?probe=d140409c65) | Feb 18, 2020 |
| Acer          | Aspire V3-331               | [68e659c87d](https://linux-hardware.org/?probe=68e659c87d) | Feb 16, 2020 |
| HUAWEI        | HLY-WX9XX                   | [28fbda9ecd](https://linux-hardware.org/?probe=28fbda9ecd) | Feb 11, 2020 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [80f496eacd](https://linux-hardware.org/?probe=80f496eacd) | Feb 11, 2020 |
| Acer          | Aspire V3-331               | [1ed27701ea](https://linux-hardware.org/?probe=1ed27701ea) | Feb 10, 2020 |
| LG Electro... | 17Z990-R.AAS8U1             | [5fe84895f2](https://linux-hardware.org/?probe=5fe84895f2) | Feb 10, 2020 |
| LG Electro... | 17Z990-R.AAS8U1             | [bf08aa9738](https://linux-hardware.org/?probe=bf08aa9738) | Feb 10, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [dbdccc5696](https://linux-hardware.org/?probe=dbdccc5696) | Feb 06, 2020 |
| Acer          | Aspire V3-331               | [f970ff6696](https://linux-hardware.org/?probe=f970ff6696) | Feb 05, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [759e13afc4](https://linux-hardware.org/?probe=759e13afc4) | Feb 02, 2020 |
| Lenovo        | ThinkPad L580 20LXS5PE0V    | [423ca04065](https://linux-hardware.org/?probe=423ca04065) | Jan 30, 2020 |
| Lenovo        | ThinkPad L580 20LXS5PE0V    | [e4e856b6f2](https://linux-hardware.org/?probe=e4e856b6f2) | Jan 30, 2020 |
| Lenovo        | ThinkPad T460s 20FAS03K0... | [d5fbd58f8b](https://linux-hardware.org/?probe=d5fbd58f8b) | Jan 27, 2020 |
| Lenovo        | ThinkPad T460s 20FAS03K0... | [88338e7031](https://linux-hardware.org/?probe=88338e7031) | Jan 27, 2020 |
| HP            | Pavilion dv7                | [119a35f980](https://linux-hardware.org/?probe=119a35f980) | Jan 26, 2020 |
| Lenovo        | Y50-70 20378                | [39a9917502](https://linux-hardware.org/?probe=39a9917502) | Jan 24, 2020 |
| MSI           | GE62 6QD                    | [54574b77f2](https://linux-hardware.org/?probe=54574b77f2) | Jan 24, 2020 |
| Lenovo        | Y50-70 20378                | [c34eecb4fb](https://linux-hardware.org/?probe=c34eecb4fb) | Jan 24, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [32f19ab04d](https://linux-hardware.org/?probe=32f19ab04d) | Jan 23, 2020 |
| HP            | ZBook 15 G2                 | [2b62bc6c8a](https://linux-hardware.org/?probe=2b62bc6c8a) | Jan 19, 2020 |
| HP            | ZBook 15 G2                 | [191021f74e](https://linux-hardware.org/?probe=191021f74e) | Jan 19, 2020 |
| Lenovo        | ThinkPad T450s 20BWS3F00... | [cf32529cfe](https://linux-hardware.org/?probe=cf32529cfe) | Jan 09, 2020 |
| Lenovo        | ThinkPad 20QJ001GMX         | [e720c77930](https://linux-hardware.org/?probe=e720c77930) | Jan 09, 2020 |
| Medion        | P6669 MD60147               | [b857f2b82d](https://linux-hardware.org/?probe=b857f2b82d) | Jan 07, 2020 |
| Lenovo        | ThinkPad T490s 20NX007AG... | [12b5e06a49](https://linux-hardware.org/?probe=12b5e06a49) | Jan 04, 2020 |
| Acer          | Aspire A315-42              | [96d84c0576](https://linux-hardware.org/?probe=96d84c0576) | Dec 22, 2019 |
| Acer          | Aspire A315-42              | [e36036a3d5](https://linux-hardware.org/?probe=e36036a3d5) | Dec 21, 2019 |
| Acer          | Aspire A315-42              | [f16e75f852](https://linux-hardware.org/?probe=f16e75f852) | Dec 14, 2019 |
| HP            | EliteBook 840 G6            | [6b2396c6ac](https://linux-hardware.org/?probe=6b2396c6ac) | Dec 08, 2019 |
| Dell          | G3 3779                     | [716cb93844](https://linux-hardware.org/?probe=716cb93844) | Dec 06, 2019 |
| Dell          | Latitude 7390               | [714656669c](https://linux-hardware.org/?probe=714656669c) | Dec 02, 2019 |
| HP            | ZBook 15                    | [196dfe92a3](https://linux-hardware.org/?probe=196dfe92a3) | Nov 27, 2019 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [be40a37ea8](https://linux-hardware.org/?probe=be40a37ea8) | Nov 24, 2019 |
| Acer          | Aspire V5-431               | [6a087dd575](https://linux-hardware.org/?probe=6a087dd575) | Nov 24, 2019 |
| Dell          | Latitude 7280               | [d18e59c26a](https://linux-hardware.org/?probe=d18e59c26a) | Nov 23, 2019 |
| Dell          | Latitude 7280               | [53190bc040](https://linux-hardware.org/?probe=53190bc040) | Nov 23, 2019 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [3200b20576](https://linux-hardware.org/?probe=3200b20576) | Nov 16, 2019 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [b7089462b3](https://linux-hardware.org/?probe=b7089462b3) | Nov 16, 2019 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [ec55fd6791](https://linux-hardware.org/?probe=ec55fd6791) | Oct 06, 2019 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [e46079e2f8](https://linux-hardware.org/?probe=e46079e2f8) | Oct 06, 2019 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [e1dfe6707d](https://linux-hardware.org/?probe=e1dfe6707d) | Oct 06, 2019 |
| Acer          | Aspire E5-511               | [af59a812bc](https://linux-hardware.org/?probe=af59a812bc) | Sep 29, 2019 |
| HP            | Pavilion ZV6100 (EE984EA... | [215d2a28a4](https://linux-hardware.org/?probe=215d2a28a4) | Aug 15, 2019 |
| Dell          | Latitude 7390               | [d360b45394](https://linux-hardware.org/?probe=d360b45394) | Aug 15, 2019 |
| HP            | Pavilion ZV6100 (EE984EA... | [e643de7d13](https://linux-hardware.org/?probe=e643de7d13) | Aug 15, 2019 |
| Timi          | Mi Laptop Air 12.5          | [8d36fc215c](https://linux-hardware.org/?probe=8d36fc215c) | Aug 14, 2019 |
| Lenovo        | ThinkPad T440s 20AQ0066M... | [54b33d56bb](https://linux-hardware.org/?probe=54b33d56bb) | Aug 14, 2019 |
| Dell          | Latitude E6430              | [4e38982788](https://linux-hardware.org/?probe=4e38982788) | Aug 13, 2019 |
| Dell          | Latitude 7390               | [05cdc89a9d](https://linux-hardware.org/?probe=05cdc89a9d) | Aug 12, 2019 |
| Dell          | Latitude E6430              | [1369716caa](https://linux-hardware.org/?probe=1369716caa) | Aug 12, 2019 |
| Dell          | Latitude E6430              | [e90e03524b](https://linux-hardware.org/?probe=e90e03524b) | Aug 12, 2019 |
| Lenovo        | ThinkPad L450 20DTS01R00    | [65e73516b5](https://linux-hardware.org/?probe=65e73516b5) | Aug 03, 2019 |
| Lenovo        | ThinkPad L450 20DTS01R00    | [7b994d2ec2](https://linux-hardware.org/?probe=7b994d2ec2) | Jul 31, 2019 |
| Apple         | MacBookPro1,1               | [46f4e56e3f](https://linux-hardware.org/?probe=46f4e56e3f) | Jul 21, 2019 |
| Apple         | MacBookPro8,2               | [88b8816bfe](https://linux-hardware.org/?probe=88b8816bfe) | Jul 11, 2019 |
| Lenovo        | ThinkPad L450 20DTS01R00    | [8556fe8940](https://linux-hardware.org/?probe=8556fe8940) | Jul 11, 2019 |
| Apple         | MacBookPro8,2               | [3d2225e709](https://linux-hardware.org/?probe=3d2225e709) | Jul 11, 2019 |
| Dell          | Latitude E7250              | [64dc3ace03](https://linux-hardware.org/?probe=64dc3ace03) | Jun 17, 2019 |
| Dell          | Latitude E7250              | [02b9759d77](https://linux-hardware.org/?probe=02b9759d77) | Jun 16, 2019 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [31a261423c](https://linux-hardware.org/?probe=31a261423c) | Jun 11, 2019 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [6a667c9ba7](https://linux-hardware.org/?probe=6a667c9ba7) | Jun 11, 2019 |
| Dell          | Inspiron 7520               | [744af8e456](https://linux-hardware.org/?probe=744af8e456) | Jun 10, 2019 |
| Dell          | Inspiron 7520               | [9ed6957c8b](https://linux-hardware.org/?probe=9ed6957c8b) | Jun 07, 2019 |
| HP            | OMEN by Laptop 15-dc0xxx    | [06ee78ee4d](https://linux-hardware.org/?probe=06ee78ee4d) | Apr 26, 2019 |
| HP            | ProBook 4510s               | [b1ed13a854](https://linux-hardware.org/?probe=b1ed13a854) | Mar 29, 2019 |
| Dell          | Latitude E7250              | [0ee5638d26](https://linux-hardware.org/?probe=0ee5638d26) | Mar 29, 2019 |
| Positivo      | WCBT1013                    | [e6f1ac9248](https://linux-hardware.org/?probe=e6f1ac9248) | Mar 27, 2019 |
| Dell          | Latitude E7250              | [fcd5b5c6f3](https://linux-hardware.org/?probe=fcd5b5c6f3) | Mar 23, 2019 |
| Dell          | Latitude E7250              | [61982fcb92](https://linux-hardware.org/?probe=61982fcb92) | Mar 19, 2019 |
| Dell          | Latitude E7250              | [3c8e2e4aba](https://linux-hardware.org/?probe=3c8e2e4aba) | Mar 19, 2019 |
| Dell          | Latitude E7250              | [ae7e990d2c](https://linux-hardware.org/?probe=ae7e990d2c) | Mar 19, 2019 |
| HP            | OMEN by Laptop              | [7bd53b3ffb](https://linux-hardware.org/?probe=7bd53b3ffb) | Nov 28, 2018 |
| ASUSTek       | Strix 17 GL703GE            | [9a4db5d6fd](https://linux-hardware.org/?probe=9a4db5d6fd) | Nov 14, 2018 |
| ASUSTek       | Strix 17 GL703GE            | [93a71f7e7f](https://linux-hardware.org/?probe=93a71f7e7f) | Nov 14, 2018 |
| Lenovo        | ThinkPad X230 23252UU       | [cefd5e879b](https://linux-hardware.org/?probe=cefd5e879b) | Nov 08, 2018 |
| ASUSTek       | K55VJ                       | [f23b5bf0da](https://linux-hardware.org/?probe=f23b5bf0da) | Nov 01, 2018 |
| Medion        | X783X                       | [852662bdf3](https://linux-hardware.org/?probe=852662bdf3) | Oct 31, 2018 |
| Lenovo        | ThinkPad X1 Carbon 3460B... | [b7014678b5](https://linux-hardware.org/?probe=b7014678b5) | Oct 30, 2018 |
| Lenovo        | ThinkPad T480 20L6S01W00    | [6f9dca6953](https://linux-hardware.org/?probe=6f9dca6953) | Oct 29, 2018 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [4438a85b31](https://linux-hardware.org/?probe=4438a85b31) | Oct 26, 2018 |
| ASUSTek       | N73SM                       | [a5a0da657b](https://linux-hardware.org/?probe=a5a0da657b) | Oct 11, 2018 |
| Positivo      | Unknown                     | [d826611187](https://linux-hardware.org/?probe=d826611187) | Sep 24, 2018 |
| HP            | OMEN by Laptop 17-an0xx     | [142d7492c2](https://linux-hardware.org/?probe=142d7492c2) | Sep 16, 2018 |
| HP            | OMEN by Laptop 17-an0xx     | [65292e94a4](https://linux-hardware.org/?probe=65292e94a4) | Sep 16, 2018 |
| Dell          | XPS 13 9370                 | [424d23c5fe](https://linux-hardware.org/?probe=424d23c5fe) | Sep 01, 2018 |
| Dell          | XPS 13 9370                 | [f4ea533636](https://linux-hardware.org/?probe=f4ea533636) | Sep 01, 2018 |
| Acer          | Aspire SW3-016              | [425d589d65](https://linux-hardware.org/?probe=425d589d65) | Apr 01, 2018 |
| Samsung       | R425/R525                   | [eeb54d2d46](https://linux-hardware.org/?probe=eeb54d2d46) | Oct 04, 2017 |
| Samsung       | R425/R525                   | [140a1aad88](https://linux-hardware.org/?probe=140a1aad88) | Oct 04, 2017 |
| Lenovo        | B50-30 20382                | [b4e99f70a9](https://linux-hardware.org/?probe=b4e99f70a9) | Sep 28, 2017 |
| MSI           | GE72 6QF                    | [1c47bc90e4](https://linux-hardware.org/?probe=1c47bc90e4) | Dec 18, 2016 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [25576a8571](https://linux-hardware.org/?probe=25576a8571) | Jul 16, 2016 |
| Samsung       | NC10                        | [3ad0ff0e13](https://linux-hardware.org/?probe=3ad0ff0e13) | Jul 12, 2016 |
| MSI           | GS60 6QC                    | [404f145917](https://linux-hardware.org/?probe=404f145917) | May 18, 2016 |
| Samsung       | NC10                        | [6da4c3c370](https://linux-hardware.org/?probe=6da4c3c370) | Mar 06, 2016 |
| ASUSTek       | N501VW                      | [5b1076ea3c](https://linux-hardware.org/?probe=5b1076ea3c) | Mar 02, 2016 |
| HP            | EliteBook 2540p             | [bd135661d2](https://linux-hardware.org/?probe=bd135661d2) | Feb 11, 2016 |
| HP            | EliteBook 2540p             | [f25f73d78c](https://linux-hardware.org/?probe=f25f73d78c) | Feb 11, 2016 |
| Acer          | Aspire E5-522               | [76013f1c62](https://linux-hardware.org/?probe=76013f1c62) | Feb 04, 2016 |
| Lenovo        | G570 20079                  | [2239d316e8](https://linux-hardware.org/?probe=2239d316e8) | Nov 26, 2015 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Gentoo 2.7     | 243       | 45.08%  |
| Gentoo 2.6     | 198       | 36.73%  |
| Gentoo 2.8     | 76        | 14.1%   |
| Gentoo         | 6         | 1.11%   |
| Gentoo 2.4.1   | 5         | 0.93%   |
| Gentoo 2.3     | 4         | 0.74%   |
| Gentoo 2.2     | 4         | 0.74%   |
| Gentoo Pelikan | 1         | 0.19%   |
| Gentoo 2.1     | 1         | 0.19%   |
| Gentoo 1       | 1         | 0.19%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Gentoo | 491       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.27-gentoo           | 16        | 2.54%   |
| 5.10.61-gentoo           | 13        | 2.07%   |
| 5.4.38-gentoo            | 11        | 1.75%   |
| 5.4.80-gentoo-r1         | 9         | 1.43%   |
| 5.4.48-gentoo            | 9         | 1.43%   |
| 5.15.32-gentoo-r1        | 9         | 1.43%   |
| 5.10.76-gentoo-r1        | 8         | 1.27%   |
| 5.10.76-gentoo-r1-x86_64 | 7         | 1.11%   |
| 5.10.52-gentoo           | 6         | 0.95%   |
| 5.10.27-gentoo-x86_64    | 6         | 0.95%   |
| 5.4.97-gentoo            | 5         | 0.79%   |
| 5.4.60-gentoo            | 5         | 0.79%   |
| 5.4.28-gentoo            | 5         | 0.79%   |
| 5.15.32-gentoo-r1-x86_64 | 5         | 0.79%   |
| 5.8.0-gentoo-r1          | 4         | 0.64%   |
| 5.4.97-gentoo-x86_64     | 4         | 0.64%   |
| 5.4.48-gentoo-x86_64     | 4         | 0.64%   |
| 5.10.61-gentoo-x86_64    | 4         | 0.64%   |
| 4.19.97-gentoo           | 4         | 0.64%   |
| 4.14.65-gentoo           | 4         | 0.64%   |
| 5.4.66-gentoo            | 3         | 0.48%   |
| 5.4.38-gentoo-x86_64     | 3         | 0.48%   |
| 5.17.3-gentoo            | 3         | 0.48%   |
| 5.17.1-gentoo-r1         | 3         | 0.48%   |
| 5.15.5-gentoo            | 3         | 0.48%   |
| 5.15.26-gentoo-x86_64    | 3         | 0.48%   |
| 5.15.26-gentoo           | 3         | 0.48%   |
| 5.15.23-gentoo-x86_64    | 3         | 0.48%   |
| 5.15.16-gentoo           | 3         | 0.48%   |
| 5.15.13-gentoo           | 3         | 0.48%   |
| 5.15.10-gentoo-x86_64    | 3         | 0.48%   |
| 5.14.9-gentoo-x86_64     | 3         | 0.48%   |
| 5.11.2-gentoo            | 3         | 0.48%   |
| 5.10.4-gentoo-x86_64     | 3         | 0.48%   |
| 5.10.33-gentoo-dist      | 3         | 0.48%   |
| 4.19.97-gentoo-x86_64    | 3         | 0.48%   |
| 4.19.86-gentoo           | 3         | 0.48%   |
| 4.19.72-gentoo           | 3         | 0.48%   |
| 4.19.57-gentoo           | 3         | 0.48%   |
| 5.9.8-gentoo             | 2         | 0.32%   |
| 5.9.2-gentoo             | 2         | 0.32%   |
| 5.8.5-gentoo             | 2         | 0.32%   |
| 5.8.16-gentoo            | 2         | 0.32%   |
| 5.7.7-gentoo-x86_64      | 2         | 0.32%   |
| 5.7.4-gentoo             | 2         | 0.32%   |
| 5.7.0-gentoo             | 2         | 0.32%   |
| 5.6.15-gentoo            | 2         | 0.32%   |
| 5.6.15                   | 2         | 0.32%   |
| 5.4.92-gentoo-x86_64     | 2         | 0.32%   |
| 5.4.92-gentoo            | 2         | 0.32%   |
| 5.4.72-gentoo-x86_64     | 2         | 0.32%   |
| 5.4.72-gentoo            | 2         | 0.32%   |
| 5.4.72                   | 2         | 0.32%   |
| 5.4.66-gentoo-x86_64     | 2         | 0.32%   |
| 5.4.1-gentoo             | 2         | 0.32%   |
| 5.18.7-gentoo            | 2         | 0.32%   |
| 5.18.4-gentoo            | 2         | 0.32%   |
| 5.18.1-gentoo-r2         | 2         | 0.32%   |
| 5.16.0-gentoo-x86_64     | 2         | 0.32%   |
| 5.15.7-gentoo            | 2         | 0.32%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.27 | 25        | 3.99%   |
| 5.4.48  | 20        | 3.19%   |
| 5.10.76 | 20        | 3.19%   |
| 5.10.61 | 18        | 2.87%   |
| 5.15.32 | 17        | 2.71%   |
| 5.4.38  | 16        | 2.55%   |
| 5.4.97  | 11        | 1.75%   |
| 5.4.80  | 11        | 1.75%   |
| 5.4.28  | 11        | 1.75%   |
| 5.10.52 | 10        | 1.59%   |
| 5.15.11 | 9         | 1.44%   |
| 4.19.97 | 8         | 1.28%   |
| 5.4.72  | 7         | 1.12%   |
| 5.4.60  | 7         | 1.12%   |
| 5.17.1  | 7         | 1.12%   |
| 5.16.0  | 7         | 1.12%   |
| 5.4.66  | 6         | 0.96%   |
| 5.15.26 | 6         | 0.96%   |
| 5.15.23 | 6         | 0.96%   |
| 5.15.10 | 6         | 0.96%   |
| 5.8.0   | 5         | 0.8%    |
| 5.15.52 | 5         | 0.8%    |
| 5.15.5  | 5         | 0.8%    |
| 5.15.41 | 5         | 0.8%    |
| 5.15.13 | 5         | 0.8%    |
| 5.14.9  | 5         | 0.8%    |
| 5.11.0  | 5         | 0.8%    |
| 5.10.4  | 5         | 0.8%    |
| 4.19.57 | 5         | 0.8%    |
| 5.9.1   | 4         | 0.64%   |
| 5.9.0   | 4         | 0.64%   |
| 5.6.15  | 4         | 0.64%   |
| 5.4.92  | 4         | 0.64%   |
| 5.18.1  | 4         | 0.64%   |
| 5.16.10 | 4         | 0.64%   |
| 5.12.4  | 4         | 0.64%   |
| 5.11.2  | 4         | 0.64%   |
| 4.19.72 | 4         | 0.64%   |
| 4.14.65 | 4         | 0.64%   |
| 5.9.8   | 3         | 0.48%   |
| 5.9.11  | 3         | 0.48%   |
| 5.8.5   | 3         | 0.48%   |
| 5.8.16  | 3         | 0.48%   |
| 5.7.4   | 3         | 0.48%   |
| 5.4.1   | 3         | 0.48%   |
| 5.17.9  | 3         | 0.48%   |
| 5.17.5  | 3         | 0.48%   |
| 5.17.3  | 3         | 0.48%   |
| 5.15.16 | 3         | 0.48%   |
| 5.15.12 | 3         | 0.48%   |
| 5.15.1  | 3         | 0.48%   |
| 5.14.8  | 3         | 0.48%   |
| 5.14.1  | 3         | 0.48%   |
| 5.13.12 | 3         | 0.48%   |
| 5.12.0  | 3         | 0.48%   |
| 5.10.74 | 3         | 0.48%   |
| 5.10.33 | 3         | 0.48%   |
| 5.10.15 | 3         | 0.48%   |
| 5.10.13 | 3         | 0.48%   |
| 4.19.86 | 3         | 0.48%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 107       | 18.29%  |
| 5.4     | 102       | 17.44%  |
| 5.15    | 78        | 13.33%  |
| 4.19    | 33        | 5.64%   |
| 5.17    | 25        | 4.27%   |
| 5.9     | 23        | 3.93%   |
| 5.16    | 23        | 3.93%   |
| 5.6     | 22        | 3.76%   |
| 5.14    | 21        | 3.59%   |
| 5.8     | 19        | 3.25%   |
| 5.11    | 19        | 3.25%   |
| 5.18    | 17        | 2.91%   |
| 5.12    | 17        | 2.91%   |
| 5.7     | 16        | 2.74%   |
| 5.13    | 13        | 2.22%   |
| 4.14    | 8         | 1.37%   |
| 5.5     | 7         | 1.2%    |
| 5.3     | 5         | 0.85%   |
| 5.1     | 5         | 0.85%   |
| 4.4     | 5         | 0.85%   |
| 5.2     | 3         | 0.51%   |
| 4.9     | 3         | 0.51%   |
| 4.18    | 3         | 0.51%   |
| 5.0     | 2         | 0.34%   |
| 4.6     | 2         | 0.34%   |
| 4.12    | 2         | 0.34%   |
| 5.19    | 1         | 0.17%   |
| 4.5     | 1         | 0.17%   |
| 4.20    | 1         | 0.17%   |
| 4.10    | 1         | 0.17%   |
| 4.1     | 1         | 0.17%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 475       | 96.74%  |
| i686   | 13        | 2.65%   |
| ppc    | 3         | 0.61%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 245       | 46.85%  |
| KDE5           | 88        | 16.83%  |
| GNOME          | 67        | 12.81%  |
| XFCE           | 40        | 7.65%   |
| KDE            | 24        | 4.59%   |
| MATE           | 13        | 2.49%   |
| DWM            | 7         | 1.34%   |
| sway           | 6         | 1.15%   |
| LXQt           | 5         | 0.96%   |
| LXDE           | 5         | 0.96%   |
| Xsession       | 4         | 0.76%   |
| openbox        | 3         | 0.57%   |
| X-Cinnamon     | 2         | 0.38%   |
| Cinnamon       | 2         | 0.38%   |
| awesome        | 2         | 0.38%   |
| xmonad         | 1         | 0.19%   |
| qt5ct          | 1         | 0.19%   |
| LeftWM         | 1         | 0.19%   |
| i3-with-shmlog | 1         | 0.19%   |
| i3             | 1         | 0.19%   |
| GNOME Classic  | 1         | 0.19%   |
| fvwm           | 1         | 0.19%   |
| fluxbox        | 1         | 0.19%   |
| Enlightenment  | 1         | 0.19%   |
| bspwm          | 1         | 0.19%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 312       | 59.66%  |
| Unknown | 79        | 15.11%  |
| Tty     | 70        | 13.38%  |
| Wayland | 62        | 11.85%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 266       | 51.55%  |
| SDDM    | 121       | 23.45%  |
| LightDM | 54        | 10.47%  |
| GDM     | 50        | 9.69%   |
| XDM     | 10        | 1.94%   |
| SLiM    | 8         | 1.55%   |
| LXDM    | 2         | 0.39%   |
| GREETD  | 2         | 0.39%   |
| TDM     | 1         | 0.19%   |
| KDM     | 1         | 0.19%   |
| GDM3    | 1         | 0.19%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang                 | Notebooks | Percent |
|----------------------|-----------|---------|
| en_US                | 202       | 38.85%  |
| Unknown              | 92        | 17.69%  |
| C.UTF8               | 35        | 6.73%   |
| en_GB                | 29        | 5.58%   |
| de_DE                | 29        | 5.58%   |
| ru_RU                | 21        | 4.04%   |
| fr_FR                | 12        | 2.31%   |
| it_IT                | 9         | 1.73%   |
| C                    | 8         | 1.54%   |
| es_ES                | 7         | 1.35%   |
| en_AU                | 7         | 1.35%   |
| zh_CN                | 6         | 1.15%   |
| POSIX                | 5         | 0.96%   |
| en_CA                | 5         | 0.96%   |
| el_GR                | 5         | 0.96%   |
| pl_PL                | 4         | 0.77%   |
| pt_BR                | 3         | 0.58%   |
| nl_NL                | 3         | 0.58%   |
| cs_CZ                | 3         | 0.58%   |
| uk_UA                | 2         | 0.38%   |
| nl_BE                | 2         | 0.38%   |
| ja_JP                | 2         | 0.38%   |
| fr_CA                | 2         | 0.38%   |
| es_CL                | 2         | 0.38%   |
| es_AR                | 2         | 0.38%   |
| en_ZA                | 2         | 0.38%   |
| en_US.UTF8           | 2         | 0.38%   |
| en_MX                | 2         | 0.38%   |
| zh_TW                | 1         | 0.19%   |
| tr_TR.UTF8           | 1         | 0.19%   |
| tr_TR                | 1         | 0.19%   |
| sv_SE                | 1         | 0.19%   |
| ru_UA                | 1         | 0.19%   |
| lt_LT                | 1         | 0.19%   |
| ko_KR                | 1         | 0.19%   |
| fr_BE                | 1         | 0.19%   |
| es_MX                | 1         | 0.19%   |
| en_US@euro           | 1         | 0.19%   |
| en_NZ                | 1         | 0.19%   |
| en_IE                | 1         | 0.19%   |
| en_FR                | 1         | 0.19%   |
| de_DE.UTF8           | 1         | 0.19%   |
| de_DE.iso885915@euro | 1         | 0.19%   |
| de_CH                | 1         | 0.19%   |
| ca_ES                | 1         | 0.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 382       | 75.94%  |
| BIOS | 121       | 24.06%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 304       | 60.92%  |
| Btrfs    | 115       | 23.05%  |
| Unknown  | 23        | 4.61%   |
| Xfs      | 20        | 4.01%   |
| F2fs     | 14        | 2.81%   |
| Zfs      | 13        | 2.61%   |
| XXXXXXX  | 2         | 0.4%    |
| Reiserfs | 2         | 0.4%    |
| Ext3     | 2         | 0.4%    |
| Overlay  | 1         | 0.2%    |
| Jfs      | 1         | 0.2%    |
| Ext2     | 1         | 0.2%    |
| Bcachefs | 1         | 0.2%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 416       | 83.53%  |
| MBR     | 49        | 9.84%   |
| Unknown | 33        | 6.63%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 369       | 73.21%  |
| Yes       | 135       | 26.79%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 346       | 68.65%  |
| Yes       | 158       | 31.35%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 146       | 29.74%  |
| Dell                | 93        | 18.94%  |
| Hewlett-Packard     | 70        | 14.26%  |
| ASUSTek Computer    | 52        | 10.59%  |
| Acer                | 26        | 5.3%    |
| MSI                 | 14        | 2.85%   |
| Apple               | 14        | 2.85%   |
| Timi                | 9         | 1.83%   |
| HUAWEI              | 8         | 1.63%   |
| TUXEDO              | 7         | 1.43%   |
| Samsung Electronics | 7         | 1.43%   |
| Toshiba             | 6         | 1.22%   |
| Razer               | 4         | 0.81%   |
| Unknown             | 4         | 0.81%   |
| System76            | 2         | 0.41%   |
| Positivo            | 2         | 0.41%   |
| Notebook            | 2         | 0.41%   |
| Medion              | 2         | 0.41%   |
| IBM                 | 2         | 0.41%   |
| Fujitsu             | 2         | 0.41%   |
| Framework           | 2         | 0.41%   |
| Chuwi               | 2         | 0.41%   |
| XMG                 | 1         | 0.2%    |
| Wortmann AG         | 1         | 0.2%    |
| Sony                | 1         | 0.2%    |
| SIEMENS             | 1         | 0.2%    |
| Seco                | 1         | 0.2%    |
| Schenker            | 1         | 0.2%    |
| Purism              | 1         | 0.2%    |
| PC Specialist       | 1         | 0.2%    |
| MOTILE              | 1         | 0.2%    |
| LG Electronics      | 1         | 0.2%    |
| Jumper              | 1         | 0.2%    |
| IT Channel Pty      | 1         | 0.2%    |
| Google              | 1         | 0.2%    |
| BANGHO              | 1         | 0.2%    |
| AVITA               | 1         | 0.2%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Unknown                              | 11        | 2.24%   |
| Dell XPS 15 9570                     | 5         | 1.02%   |
| HP Pavilion Notebook                 | 4         | 0.81%   |
| HP OMEN by Laptop                    | 4         | 0.81%   |
| Dell XPS 17 9710                     | 4         | 0.81%   |
| Dell XPS 13 9310                     | 4         | 0.81%   |
| Lenovo ThinkPad T14 Gen 1 20UD0013GE | 3         | 0.61%   |
| Lenovo Legion Y530-15ICH 81FV        | 3         | 0.61%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ     | 3         | 0.61%   |
| HP Pavilion Gaming Laptop 15-ec1xxx  | 3         | 0.61%   |
| Dell XPS 15 7590                     | 3         | 0.61%   |
| Dell XPS 13 9370                     | 3         | 0.61%   |
| Dell XPS 13 9360                     | 3         | 0.61%   |
| Dell Latitude E7440                  | 3         | 0.61%   |
| Dell Latitude 7390                   | 3         | 0.61%   |
| Toshiba NB100                        | 2         | 0.41%   |
| Timi RedmiBook 13 R                  | 2         | 0.41%   |
| MSI GS63VR 6RF                       | 2         | 0.41%   |
| Lenovo ThinkPad T480 20L5CTO1WW      | 2         | 0.41%   |
| Lenovo Legion Y540-15IRH 81SX        | 2         | 0.41%   |
| Lenovo Legion R7000 2020 82B6        | 2         | 0.41%   |
| HUAWEI BOHK-WAX9X                    | 2         | 0.41%   |
| HP ProBook 455 G7                    | 2         | 0.41%   |
| HP Pavilion dv7                      | 2         | 0.41%   |
| HP Laptop 15s-eq0xxx                 | 2         | 0.41%   |
| HP EliteBook 855 G7 Notebook PC      | 2         | 0.41%   |
| Framework Laptop                     | 2         | 0.41%   |
| Dell XPS 13 9380                     | 2         | 0.41%   |
| Dell Precision 7560                  | 2         | 0.41%   |
| Dell Latitude E6530                  | 2         | 0.41%   |
| Dell Latitude E6430                  | 2         | 0.41%   |
| Dell Latitude 5480                   | 2         | 0.41%   |
| Dell Inspiron 5577                   | 2         | 0.41%   |
| Dell Inspiron 15 5510                | 2         | 0.41%   |
| Dell G3 3500                         | 2         | 0.41%   |
| ASUS X550ZA                          | 2         | 0.41%   |
| ASUS ROG Strix G513QY_G513QY         | 2         | 0.41%   |
| ASUS N501VW                          | 2         | 0.41%   |
| Apple MacBookPro8,2                  | 2         | 0.41%   |
| Apple MacBookPro11,3                 | 2         | 0.41%   |
| Acer Nitro AN515-53                  | 2         | 0.41%   |
| Acer Aspire V3-331                   | 2         | 0.41%   |
| Acer Aspire A315-42                  | 2         | 0.41%   |
| XMG C504                             | 1         | 0.2%    |
| Wortmann AG TERRA_MOBILE_1590S       | 1         | 0.2%    |
| TUXEDO Pulse 15 Gen1                 | 1         | 0.2%    |
| TUXEDO Polaris AMD Gen3 (CZN)        | 1         | 0.2%    |
| TUXEDO N24_25BU                      | 1         | 0.2%    |
| TUXEDO InfinityBook Pro 14 Gen6      | 1         | 0.2%    |
| TUXEDO Book_XA1510                   | 1         | 0.2%    |
| TUXEDO Book XC1711                   | 1         | 0.2%    |
| Toshiba Satellite L50-C              | 1         | 0.2%    |
| Toshiba Satellite L50-A-16G          | 1         | 0.2%    |
| Toshiba Satellite C850D-118          | 1         | 0.2%    |
| Toshiba Satellite A200               | 1         | 0.2%    |
| Timi RedmiBook Pro 15S               | 1         | 0.2%    |
| Timi RedmiBook Air 13                | 1         | 0.2%    |
| Timi RedmiBook 13                    | 1         | 0.2%    |
| Timi Mi Laptop Pro 15 2020           | 1         | 0.2%    |
| Timi Mi Laptop Pro 15                | 1         | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 84        | 17.11%  |
| Dell Latitude       | 35        | 7.13%   |
| Dell XPS            | 29        | 5.91%   |
| Lenovo Legion       | 22        | 4.48%   |
| Lenovo IdeaPad      | 19        | 3.87%   |
| HP Pavilion         | 17        | 3.46%   |
| Acer Aspire         | 17        | 3.46%   |
| Dell Inspiron       | 14        | 2.85%   |
| HP EliteBook        | 12        | 2.44%   |
| Unknown             | 11        | 2.24%   |
| HP OMEN             | 10        | 2.04%   |
| HP ProBook          | 9         | 1.83%   |
| HP Laptop           | 9         | 1.83%   |
| ASUS ROG            | 9         | 1.83%   |
| Dell Precision      | 7         | 1.43%   |
| ASUS ZenBook        | 7         | 1.43%   |
| Timi RedmiBook      | 5         | 1.02%   |
| Lenovo Yoga         | 5         | 1.02%   |
| HP ZBook            | 5         | 1.02%   |
| ASUS VivoBook       | 5         | 1.02%   |
| Acer Nitro          | 5         | 1.02%   |
| Toshiba Satellite   | 4         | 0.81%   |
| Razer Blade         | 4         | 0.81%   |
| Apple MacBookPro8   | 4         | 0.81%   |
| Timi Mi             | 3         | 0.61%   |
| Lenovo ThinkBook    | 3         | 0.61%   |
| Dell G3             | 3         | 0.61%   |
| Acer Swift          | 3         | 0.61%   |
| TUXEDO Book         | 2         | 0.41%   |
| Toshiba NB100       | 2         | 0.41%   |
| MSI GS63VR          | 2         | 0.41%   |
| MSI GF63            | 2         | 0.41%   |
| IBM ThinkPad        | 2         | 0.41%   |
| HUAWEI BOHK-WAX9X   | 2         | 0.41%   |
| HP 255              | 2         | 0.41%   |
| Fujitsu LIFEBOOK    | 2         | 0.41%   |
| Framework Laptop    | 2         | 0.41%   |
| Dell Vostro         | 2         | 0.41%   |
| Dell G5             | 2         | 0.41%   |
| ASUS X550ZA         | 2         | 0.41%   |
| ASUS TUF            | 2         | 0.41%   |
| ASUS N501VW         | 2         | 0.41%   |
| ASUS ASUS           | 2         | 0.41%   |
| Apple MacBookPro11  | 2         | 0.41%   |
| XMG C504            | 1         | 0.2%    |
| Wortmann AG TERRA   | 1         | 0.2%    |
| TUXEDO Pulse        | 1         | 0.2%    |
| TUXEDO Polaris      | 1         | 0.2%    |
| TUXEDO N24          | 1         | 0.2%    |
| TUXEDO InfinityBook | 1         | 0.2%    |
| Timi A35            | 1         | 0.2%    |
| System76 Lemur      | 1         | 0.2%    |
| System76 Gazelle    | 1         | 0.2%    |
| Sony VPCSC41FM      | 1         | 0.2%    |
| SIEMENS SIMATIC     | 1         | 0.2%    |
| Seco UDOO           | 1         | 0.2%    |
| Schenker XMG        | 1         | 0.2%    |
| Samsung RC530       | 1         | 0.2%    |
| Samsung R530        | 1         | 0.2%    |
| Samsung R425        | 1         | 0.2%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 90        | 18.33%  |
| 2019    | 83        | 16.9%   |
| 2018    | 58        | 11.81%  |
| 2021    | 56        | 11.41%  |
| 2017    | 30        | 6.11%   |
| 2014    | 30        | 6.11%   |
| 2016    | 24        | 4.89%   |
| 2015    | 24        | 4.89%   |
| 2012    | 21        | 4.28%   |
| 2011    | 20        | 4.07%   |
| 2013    | 13        | 2.65%   |
| 2010    | 11        | 2.24%   |
| 2008    | 11        | 2.24%   |
| 2009    | 4         | 0.81%   |
| 2006    | 4         | 0.81%   |
| Unknown | 4         | 0.81%   |
| 2007    | 3         | 0.61%   |
| 2022    | 2         | 0.41%   |
| 2005    | 2         | 0.41%   |
| 2004    | 1         | 0.2%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 491       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 480       | 97.36%  |
| Enabled  | 13        | 2.64%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 486       | 98.98%  |
| Yes  | 5         | 1.02%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 125       | 24.9%   |
| 8.01-16.0   | 113       | 22.51%  |
| 4.01-8.0    | 100       | 19.92%  |
| 32.01-64.0  | 71        | 14.14%  |
| 3.01-4.0    | 34        | 6.77%   |
| 64.01-256.0 | 17        | 3.39%   |
| 24.01-32.0  | 14        | 2.79%   |
| 1.01-2.0    | 13        | 2.59%   |
| 2.01-3.0    | 9         | 1.79%   |
| 0.51-1.0    | 5         | 1%      |
| 0.01-0.5    | 1         | 0.2%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 149       | 25.96%  |
| 2.01-3.0   | 96        | 16.72%  |
| 4.01-8.0   | 95        | 16.55%  |
| 3.01-4.0   | 72        | 12.54%  |
| 0.51-1.0   | 58        | 10.1%   |
| 0.01-0.5   | 56        | 9.76%   |
| 8.01-16.0  | 44        | 7.67%   |
| 16.01-24.0 | 3         | 0.52%   |
| 24.01-32.0 | 1         | 0.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 342       | 67.59%  |
| 2      | 139       | 27.47%  |
| 3      | 17        | 3.36%   |
| 0      | 6         | 1.19%   |
| 4      | 2         | 0.4%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 416       | 83.7%   |
| Yes       | 81        | 16.3%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 387       | 77.87%  |
| No        | 110       | 22.13%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 486       | 98.98%  |
| No        | 5         | 1.02%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 429       | 86.49%  |
| No        | 67        | 13.51%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 87        | 17.54%  |
| Germany      | 68        | 13.71%  |
| Russia       | 44        | 8.87%   |
| France       | 25        | 5.04%   |
| UK           | 22        | 4.44%   |
| China        | 21        | 4.23%   |
| Italy        | 16        | 3.23%   |
| Poland       | 15        | 3.02%   |
| Netherlands  | 15        | 3.02%   |
| Canada       | 15        | 3.02%   |
| Spain        | 13        | 2.62%   |
| Czechia      | 12        | 2.42%   |
| Ukraine      | 11        | 2.22%   |
| Sweden       | 9         | 1.81%   |
| Turkey       | 8         | 1.61%   |
| Greece       | 8         | 1.61%   |
| Australia    | 8         | 1.61%   |
| Switzerland  | 6         | 1.21%   |
| Finland      | 6         | 1.21%   |
| Brazil       | 6         | 1.21%   |
| Belgium      | 6         | 1.21%   |
| Japan        | 5         | 1.01%   |
| India        | 5         | 1.01%   |
| Belarus      | 5         | 1.01%   |
| Romania      | 4         | 0.81%   |
| Norway       | 4         | 0.81%   |
| Mexico       | 4         | 0.81%   |
| Hong Kong    | 4         | 0.81%   |
| Austria      | 4         | 0.81%   |
| South Africa | 3         | 0.6%    |
| Portugal     | 3         | 0.6%    |
| Argentina    | 3         | 0.6%    |
| Vietnam      | 2         | 0.4%    |
| Taiwan       | 2         | 0.4%    |
| Slovenia     | 2         | 0.4%    |
| Slovakia     | 2         | 0.4%    |
| Singapore    | 2         | 0.4%    |
| New Zealand  | 2         | 0.4%    |
| Iran         | 2         | 0.4%    |
| Indonesia    | 2         | 0.4%    |
| Hungary      | 2         | 0.4%    |
| Chile        | 2         | 0.4%    |
| Uruguay      | 1         | 0.2%    |
| Tunisia      | 1         | 0.2%    |
| Syria        | 1         | 0.2%    |
| South Korea  | 1         | 0.2%    |
| Saudi Arabia | 1         | 0.2%    |
| Philippines  | 1         | 0.2%    |
| Nepal        | 1         | 0.2%    |
| Lithuania    | 1         | 0.2%    |
| Kazakhstan   | 1         | 0.2%    |
| Croatia      | 1         | 0.2%    |
| Bulgaria     | 1         | 0.2%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Berlin            | 19        | 3.54%   |
| Moscow            | 17        | 3.17%   |
| St Petersburg     | 8         | 1.49%   |
| Athens            | 8         | 1.49%   |
| Kyiv              | 6         | 1.12%   |
| Warsaw            | 5         | 0.93%   |
| Prague            | 5         | 0.93%   |
| Paris             | 5         | 0.93%   |
| Munich            | 5         | 0.93%   |
| Minsk             | 5         | 0.93%   |
| Guangzhou         | 5         | 0.93%   |
| Amsterdam         | 5         | 0.93%   |
| Sydney            | 4         | 0.74%   |
| Istanbul          | 4         | 0.74%   |
| Beijing           | 4         | 0.74%   |
| Wuelfrath         | 3         | 0.56%   |
| Shenzhen          | 3         | 0.56%   |
| San Jose          | 3         | 0.56%   |
| Milan             | 3         | 0.56%   |
| Melbourne         | 3         | 0.56%   |
| Manitowoc         | 3         | 0.56%   |
| Los Angeles       | 3         | 0.56%   |
| London            | 3         | 0.56%   |
| Helsinki          | 3         | 0.56%   |
| Frankfurt am Main | 3         | 0.56%   |
| Düsseldorf       | 3         | 0.56%   |
| Chongqing         | 3         | 0.56%   |
| Cape Town         | 3         | 0.56%   |
| Woolwich          | 2         | 0.37%   |
| Winnipeg          | 2         | 0.37%   |
| West Orange       | 2         | 0.37%   |
| Weatherford       | 2         | 0.37%   |
| Vleuten           | 2         | 0.37%   |
| Vladivostok       | 2         | 0.37%   |
| Vienna            | 2         | 0.37%   |
| Vancouver         | 2         | 0.37%   |
| Utrecht           | 2         | 0.37%   |
| Tromsø           | 2         | 0.37%   |
| Tehran            | 2         | 0.37%   |
| Stockholm         | 2         | 0.37%   |
| Sterling          | 2         | 0.37%   |
| Smolensk          | 2         | 0.37%   |
| Singapore         | 2         | 0.37%   |
| San Francisco     | 2         | 0.37%   |
| Saltillo          | 2         | 0.37%   |
| Rome              | 2         | 0.37%   |
| Rolling Meadows   | 2         | 0.37%   |
| Rochester         | 2         | 0.37%   |
| Rennes            | 2         | 0.37%   |
| Perm              | 2         | 0.37%   |
| Omsk              | 2         | 0.37%   |
| Obertshausen      | 2         | 0.37%   |
| New York          | 2         | 0.37%   |
| Mountain Home     | 2         | 0.37%   |
| Marseille         | 2         | 0.37%   |
| Madrid            | 2         | 0.37%   |
| Ljubljana         | 2         | 0.37%   |
| Leipzig           | 2         | 0.37%   |
| Hoboken           | 2         | 0.37%   |
| Hamburg           | 2         | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 154       | 243    | 24.18%  |
| WDC                            | 97        | 130    | 15.23%  |
| Seagate                        | 48        | 63     | 7.54%   |
| SK hynix                       | 47        | 56     | 7.38%   |
| Intel                          | 42        | 64     | 6.59%   |
| Toshiba                        | 41        | 46     | 6.44%   |
| Unknown                        | 26        | 34     | 4.08%   |
| SanDisk                        | 26        | 35     | 4.08%   |
| HGST                           | 24        | 25     | 3.77%   |
| Kingston                       | 23        | 30     | 3.61%   |
| Micron Technology              | 18        | 21     | 2.83%   |
| Crucial                        | 11        | 13     | 1.73%   |
| KIOXIA                         | 9         | 12     | 1.41%   |
| Hitachi                        | 9         | 9      | 1.41%   |
| Apple                          | 6         | 8      | 0.94%   |
| A-DATA Technology              | 5         | 11     | 0.78%   |
| LITEON                         | 4         | 7      | 0.63%   |
| Fujitsu                        | 4         | 6      | 0.63%   |
| Phison                         | 3         | 3      | 0.47%   |
| OCZ                            | 3         | 6      | 0.47%   |
| Lenovo                         | 3         | 5      | 0.47%   |
| China                          | 3         | 5      | 0.47%   |
| Transcend                      | 2         | 5      | 0.31%   |
| Plextor                        | 2         | 2      | 0.31%   |
| Netac                          | 2         | 2      | 0.31%   |
| MyDigitalSSD                   | 2         | 2      | 0.31%   |
| LITEONIT                       | 2         | 3      | 0.31%   |
| KIOXIA-EXCERIA                 | 2         | 5      | 0.31%   |
| XrayDisk                       | 1         | 1      | 0.16%   |
| XPG                            | 1         | 1      | 0.16%   |
| T-FORCE                        | 1         | 1      | 0.16%   |
| SPCC                           | 1         | 1      | 0.16%   |
| Solid State Storage Technology | 1         | 1      | 0.16%   |
| ShanDianZhe                    | 1         | 2      | 0.16%   |
| RevuAhn                        | 1         | 1      | 0.16%   |
| OSCOO                          | 1         | 1      | 0.16%   |
| Mushkin                        | 1         | 1      | 0.16%   |
| Lite-On                        | 1         | 1      | 0.16%   |
| Linux                          | 1         | 1      | 0.16%   |
| Kingmax                        | 1         | 1      | 0.16%   |
| KingDian                       | 1         | 1      | 0.16%   |
| IBM/Hitachi                    | 1         | 1      | 0.16%   |
| Hoodisk                        | 1         | 1      | 0.16%   |
| Faspeed                        | 1         | 1      | 0.16%   |
| e2e4                           | 1         | 1      | 0.16%   |
| BIWIN                          | 1         | 1      | 0.16%   |
| ASUS-PHISON                    | 1         | 2      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| HGST HTS721010A9E630 1TB               | 15        | 2.22%   |
| Intel SSDPEKNW010T8 1TB                | 10        | 1.48%   |
| Samsung SSD 850 EVO 250GB              | 8         | 1.19%   |
| Samsung MZVLB512HBJQ-000L2 512GB       | 8         | 1.19%   |
| Seagate ST1000LM049-2GH172 1TB         | 6         | 0.89%   |
| Seagate ST1000LM035-1RK172 1TB         | 6         | 0.89%   |
| Samsung SSD 970 EVO Plus 500GB         | 6         | 0.89%   |
| Unknown MMC Card  16GB                 | 5         | 0.74%   |
| Samsung SSD 980 PRO 2TB                | 5         | 0.74%   |
| Samsung SSD 860 EVO 500GB              | 5         | 0.74%   |
| Samsung NVMe SSD Drive 512GB           | 5         | 0.74%   |
| Intel SSDPEKNU512GZ 512GB              | 5         | 0.74%   |
| WDC WDS500G2B0B-00YS70 500GB SSD       | 4         | 0.59%   |
| WDC WDS100T2B0C-00PXH0 1TB             | 4         | 0.59%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB     | 4         | 0.59%   |
| Toshiba MQ04ABF100 1TB                 | 4         | 0.59%   |
| Toshiba MQ01ABD100 1TB                 | 4         | 0.59%   |
| Toshiba KXG50ZNV512G NVMe 512GB        | 4         | 0.59%   |
| SK hynix PC711 NVMe 1TB                | 4         | 0.59%   |
| Seagate ST2000LX001-1RG174 2TB         | 4         | 0.59%   |
| Seagate ST1000LM048-2E7172 1TB         | 4         | 0.59%   |
| Samsung SSD 970 EVO Plus 250GB         | 4         | 0.59%   |
| Samsung SSD 860 EVO 1TB                | 4         | 0.59%   |
| Samsung MZVLB512HBJQ-000L7 512GB       | 4         | 0.59%   |
| Samsung MZVLB512HAJQ-00000 512GB       | 4         | 0.59%   |
| Samsung MZALQ512HALU-000L2 512GB       | 4         | 0.59%   |
| Kingston SA400S37480G 480GB SSD        | 4         | 0.59%   |
| Kingston SA400S37240G 240GB SSD        | 4         | 0.59%   |
| Intel SSDPEKKF256G8L 256GB             | 4         | 0.59%   |
| HGST HTS541010A9E680 1TB               | 4         | 0.59%   |
| WDC WDS100T2B0A-00SM50 1TB SSD         | 3         | 0.44%   |
| WDC WD16 00BB-55GUA0 160GB             | 3         | 0.44%   |
| WDC WD10JPVX-22JC3T0 1TB               | 3         | 0.44%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB   | 3         | 0.44%   |
| SK hynix SKHynix_HFS512GDE9X084N 512GB | 3         | 0.44%   |
| SK hynix SKHynix_HFS001TDE9X084N 1TB   | 3         | 0.44%   |
| SK hynix SC311 SATA 256GB SSD          | 3         | 0.44%   |
| SK hynix PC711 NVMe 512GB              | 3         | 0.44%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 3         | 0.44%   |
| SanDisk SDSSDA240G 240GB               | 3         | 0.44%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD    | 3         | 0.44%   |
| Samsung SSD 980 1TB                    | 3         | 0.44%   |
| Samsung SSD 970 PRO 512GB              | 3         | 0.44%   |
| Samsung SSD 970 PRO 1TB                | 3         | 0.44%   |
| Samsung SSD 970 EVO Plus 1TB           | 3         | 0.44%   |
| Samsung SSD 870 EVO 1TB                | 3         | 0.44%   |
| Samsung SSD 860 QVO 1TB                | 3         | 0.44%   |
| Samsung SSD 850 EVO 1TB                | 3         | 0.44%   |
| Samsung SSD 840 EVO 500GB              | 3         | 0.44%   |
| Samsung Portable SSD T5 500GB          | 3         | 0.44%   |
| Samsung MZVLB512HAJQ-000L7 512GB       | 3         | 0.44%   |
| KIOXIA KBG40ZNV512G 512GB              | 3         | 0.44%   |
| KIOXIA KBG40ZNS256G NVMe 256GB         | 3         | 0.44%   |
| Intel SSDPEKNW512G8 512GB              | 3         | 0.44%   |
| Crucial CT500MX500SSD1 500GB           | 3         | 0.44%   |
| WDC WDS500G3X0C-00SJG0 500GB           | 2         | 0.3%    |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 2         | 0.3%    |
| WDC WD5000LPVX-22V0TT0 500GB           | 2         | 0.3%    |
| WDC WD10SPZX-24Z10 1TB                 | 2         | 0.3%    |
| WDC WD10JPVX-75JC3T0 1TB               | 2         | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 46        | 61     | 32.86%  |
| WDC                 | 37        | 43     | 26.43%  |
| HGST                | 24        | 25     | 17.14%  |
| Toshiba             | 18        | 20     | 12.86%  |
| Hitachi             | 9         | 9      | 6.43%   |
| Fujitsu             | 4         | 6      | 2.86%   |
| Samsung Electronics | 1         | 2      | 0.71%   |
| IBM/Hitachi         | 1         | 1      | 0.71%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 65        | 95     | 32.18%  |
| SanDisk             | 21        | 30     | 10.4%   |
| WDC                 | 13        | 22     | 6.44%   |
| Kingston            | 13        | 20     | 6.44%   |
| SK hynix            | 12        | 13     | 5.94%   |
| Intel               | 12        | 12     | 5.94%   |
| Crucial             | 9         | 11     | 4.46%   |
| Micron Technology   | 8         | 10     | 3.96%   |
| Toshiba             | 6         | 7      | 2.97%   |
| A-DATA Technology   | 5         | 11     | 2.48%   |
| Apple               | 4         | 5      | 1.98%   |
| OCZ                 | 3         | 6      | 1.49%   |
| China               | 3         | 5      | 1.49%   |
| Transcend           | 2         | 5      | 0.99%   |
| Plextor             | 2         | 2      | 0.99%   |
| Netac               | 2         | 2      | 0.99%   |
| MyDigitalSSD        | 2         | 2      | 0.99%   |
| LITEONIT            | 2         | 3      | 0.99%   |
| XrayDisk            | 1         | 1      | 0.5%    |
| SPCC                | 1         | 1      | 0.5%    |
| ShanDianZhe         | 1         | 2      | 0.5%    |
| Seagate             | 1         | 1      | 0.5%    |
| RevuAhn             | 1         | 1      | 0.5%    |
| Phison              | 1         | 1      | 0.5%    |
| Mushkin             | 1         | 1      | 0.5%    |
| LITEON              | 1         | 2      | 0.5%    |
| Lite-On             | 1         | 1      | 0.5%    |
| Linux               | 1         | 1      | 0.5%    |
| Lenovo              | 1         | 2      | 0.5%    |
| Kingmax             | 1         | 1      | 0.5%    |
| KingDian            | 1         | 1      | 0.5%    |
| Hoodisk             | 1         | 1      | 0.5%    |
| Faspeed             | 1         | 1      | 0.5%    |
| e2e4                | 1         | 1      | 0.5%    |
| BIWIN               | 1         | 1      | 0.5%    |
| ASUS-PHISON         | 1         | 2      | 0.5%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 264       | 386    | 43.35%  |
| SSD     | 184       | 283    | 30.21%  |
| HDD     | 133       | 167    | 21.84%  |
| MMC     | 26        | 32     | 4.27%   |
| Unknown | 2         | 4      | 0.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 274       | 438    | 47.57%  |
| NVMe | 264       | 386    | 45.83%  |
| MMC  | 26        | 32     | 4.51%   |
| SAS  | 12        | 16     | 2.08%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 188       | 284    | 59.31%  |
| 0.51-1.0   | 115       | 145    | 36.28%  |
| 1.01-2.0   | 13        | 20     | 4.1%    |
| 4.01-10.0  | 1         | 1      | 0.32%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 140       | 26.62%  |
| 101-250        | 120       | 22.81%  |
| 501-1000       | 94        | 17.87%  |
| 1001-2000      | 52        | 9.89%   |
| 51-100         | 33        | 6.27%   |
| 1-20           | 30        | 5.7%    |
| Unknown        | 27        | 5.13%   |
| 21-50          | 13        | 2.47%   |
| More than 3000 | 9         | 1.71%   |
| 2001-3000      | 8         | 1.52%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 138       | 24.6%   |
| 21-50          | 98        | 17.47%  |
| 101-250        | 89        | 15.86%  |
| 251-500        | 80        | 14.26%  |
| 51-100         | 68        | 12.12%  |
| 501-1000       | 41        | 7.31%   |
| Unknown        | 27        | 4.81%   |
| 1001-2000      | 15        | 2.67%   |
| 2001-3000      | 3         | 0.53%   |
| More than 3000 | 2         | 0.36%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                     | Notebooks | Drives | Percent |
|-------------------------------------------|-----------|--------|---------|
| HGST HTS721010A9E630 1TB                  | 4         | 5      | 7.55%   |
| SK hynix HFS256G39TND-N210A 256GB SSD     | 2         | 2      | 3.77%   |
| Seagate ST2000LX001-1RG174 2TB            | 2         | 2      | 3.77%   |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 2         | 3      | 3.77%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD       | 2         | 2      | 3.77%   |
| Samsung Electronics SSD 850 EVO 1TB       | 2         | 2      | 3.77%   |
| WDC WD10SPZX-24Z10T0 1TB                  | 1         | 1      | 1.89%   |
| WDC WD10JPVX-75JC3T0 1TB                  | 1         | 1      | 1.89%   |
| WDC WD10EZEX-08M2NA0 1TB                  | 1         | 2      | 1.89%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD  | 1         | 1      | 1.89%   |
| Toshiba MQ01ABF050 500GB                  | 1         | 1      | 1.89%   |
| Toshiba MK6008GAH 64GB                    | 1         | 2      | 1.89%   |
| Toshiba MK4026GAX 40GB                    | 1         | 1      | 1.89%   |
| Toshiba MK1629GSG 160GB                   | 1         | 1      | 1.89%   |
| SK hynix SH920 mSATA 256GB SSD            | 1         | 1      | 1.89%   |
| SK hynix SC210 mSATA 128GB SSD            | 1         | 1      | 1.89%   |
| Seagate ST9750420AS 752GB                 | 1         | 1      | 1.89%   |
| Seagate ST9100824AS 100GB                 | 1         | 1      | 1.89%   |
| Seagate ST320LT007-9ZV142 320GB           | 1         | 1      | 1.89%   |
| Seagate ST1000LM049-2GH172 1TB            | 1         | 1      | 1.89%   |
| Seagate ST1000LM035-1RK172 1TB            | 1         | 2      | 1.89%   |
| Seagate ST1000LM014-1EJ164 1TB            | 1         | 1      | 1.89%   |
| SanDisk SSD PLUS 480GB                    | 1         | 1      | 1.89%   |
| SanDisk SD9SN8W 128GB SSD                 | 1         | 1      | 1.89%   |
| SanDisk SD7SB2Q512G1001 512GB SSD         | 1         | 1      | 1.89%   |
| Samsung Electronics SSD SM841 mSATA 512GB | 1         | 1      | 1.89%   |
| Samsung Electronics SSD 870 EVO 2TB       | 1         | 1      | 1.89%   |
| Samsung Electronics HM160HC 160GB         | 1         | 1      | 1.89%   |
| LITEON CV8-8E128-HP 128GB SSD             | 1         | 2      | 1.89%   |
| Kingston RBU-SNS8350DES3128GP 128GB SSD   | 1         | 1      | 1.89%   |
| Intel SSDSCKKF256G8H 256GB                | 1         | 1      | 1.89%   |
| Intel SSDSC2BW480A4 480GB                 | 1         | 1      | 1.89%   |
| Intel SSDSC2BW180A3L 180GB                | 1         | 1      | 1.89%   |
| Intel SSDPEKKF256G8L 256GB                | 1         | 1      | 1.89%   |
| IBM/Hitachi IC25N080ATMR04-0 80GB         | 1         | 1      | 1.89%   |
| Hitachi HTS723225L9SA62 250GB             | 1         | 1      | 1.89%   |
| Hitachi HTS547550A9E384 500GB             | 1         | 1      | 1.89%   |
| Hitachi HTS545050B9A300 500GB             | 1         | 1      | 1.89%   |
| Hitachi HTS542525K9A300 250GB             | 1         | 1      | 1.89%   |
| HGST HTS725050A7E635 OPAL 500GB           | 1         | 1      | 1.89%   |
| HGST HTS541010B7E610 1TB                  | 1         | 1      | 1.89%   |
| Fujitsu MHZ2160BJ G2 160GB                | 1         | 1      | 1.89%   |
| Fujitsu MHT2080AH 80GB                    | 1         | 1      | 1.89%   |
| Crucial CT1000P1SSD8 1TB                  | 1         | 1      | 1.89%   |
| A-DATA Technology SP550 240GB SSD         | 1         | 1      | 1.89%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 12     | 19.23%  |
| HGST                | 6         | 7      | 11.54%  |
| Toshiba             | 5         | 6      | 9.62%   |
| Samsung Electronics | 5         | 5      | 9.62%   |
| SK hynix            | 4         | 4      | 7.69%   |
| SanDisk             | 4         | 5      | 7.69%   |
| Intel               | 4         | 4      | 7.69%   |
| Hitachi             | 4         | 4      | 7.69%   |
| WDC                 | 3         | 4      | 5.77%   |
| Fujitsu             | 2         | 2      | 3.85%   |
| LITEON              | 1         | 2      | 1.92%   |
| Kingston            | 1         | 1      | 1.92%   |
| IBM/Hitachi         | 1         | 1      | 1.92%   |
| Crucial             | 1         | 1      | 1.92%   |
| A-DATA Technology   | 1         | 1      | 1.92%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 12     | 32.26%  |
| HGST                | 6         | 7      | 19.35%  |
| Toshiba             | 4         | 5      | 12.9%   |
| Hitachi             | 4         | 4      | 12.9%   |
| WDC                 | 3         | 4      | 9.68%   |
| Fujitsu             | 2         | 2      | 6.45%   |
| Samsung Electronics | 1         | 1      | 3.23%   |
| IBM/Hitachi         | 1         | 1      | 3.23%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 31        | 36     | 59.62%  |
| SSD  | 19        | 21     | 36.54%  |
| NVMe | 2         | 2      | 3.85%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                            | Notebooks | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| Toshiba THNSN5512GPUK NVMe 512GB | 1         | 1      | 50%     |
| Hitachi HTS721010G9SA00 100GB    | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 50%     |
| Hitachi | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 415       | 704    | 76.57%  |
| Detected | 74        | 107    | 13.65%  |
| Malfunc  | 51        | 59     | 9.41%   |
| Failed   | 2         | 2      | 0.37%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 304       | 48.18%  |
| Samsung Electronics            | 105       | 16.64%  |
| AMD                            | 65        | 10.3%   |
| SanDisk                        | 52        | 8.24%   |
| SK hynix                       | 35        | 5.55%   |
| Toshiba America Info Systems   | 20        | 3.17%   |
| Micron Technology              | 10        | 1.58%   |
| KIOXIA                         | 10        | 1.58%   |
| Kingston Technology Company    | 10        | 1.58%   |
| Phison Electronics             | 3         | 0.48%   |
| Lite-On Technology             | 3         | 0.48%   |
| Nvidia                         | 2         | 0.32%   |
| Micron/Crucial Technology      | 2         | 0.32%   |
| Lenovo                         | 2         | 0.32%   |
| Apple                          | 2         | 0.32%   |
| Union Memory (Shenzhen)        | 1         | 0.16%   |
| Solid State Storage Technology | 1         | 0.16%   |
| Silicon Motion                 | 1         | 0.16%   |
| Seagate Technology             | 1         | 0.16%   |
| JMicron Technology             | 1         | 0.16%   |
| ADATA Technology               | 1         | 0.16%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 65        | 9.82%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 60        | 9.06%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 39        | 5.89%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 34        | 5.14%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 26        | 3.93%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 22        | 3.32%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 21        | 3.17%   |
| SK hynix Gold P31 SSD                                                            | 19        | 2.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 19        | 2.87%   |
| Intel SSD 660P Series                                                            | 15        | 2.27%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 15        | 2.27%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 14        | 2.11%   |
| Samsung NVMe SSD Controller 980                                                  | 14        | 2.11%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 14        | 2.11%   |
| Intel Volume Management Device NVMe RAID Controller                              | 13        | 1.96%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 11        | 1.66%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 11        | 1.66%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 10        | 1.51%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 10        | 1.51%   |
| Micron Non-Volatile memory controller                                            | 10        | 1.51%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 9         | 1.36%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 9         | 1.36%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 8         | 1.21%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 7         | 1.06%   |
| Intel Comet Lake SATA AHCI Controller                                            | 7         | 1.06%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 7         | 1.06%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 7         | 1.06%   |
| SK hynix Non-Volatile memory controller                                          | 6         | 0.91%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 6         | 0.91%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 6         | 0.91%   |
| SanDisk Non-Volatile memory controller                                           | 6         | 0.91%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 6         | 0.91%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 6         | 0.91%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 6         | 0.91%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 6         | 0.91%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 6         | 0.91%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 5         | 0.76%   |
| Intel Non-Volatile memory controller                                             | 5         | 0.76%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 4         | 0.6%    |
| Kingston Company Company Non-Volatile memory controller                          | 4         | 0.6%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 4         | 0.6%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 4         | 0.6%    |
| SK hynix PC401 NVMe Solid State Drive 256GB                                      | 3         | 0.45%   |
| SanDisk PC SN520 NVMe SSD                                                        | 3         | 0.45%   |
| Lite-On Non-Volatile memory controller                                           | 3         | 0.45%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 3         | 0.45%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 3         | 0.45%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3         | 0.45%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                             | 2         | 0.3%    |
| Toshiba America Info Systems NVMe Controller                                     | 2         | 0.3%    |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 2         | 0.3%    |
| Samsung NVMe SSD Controller SM951/PM951                                          | 2         | 0.3%    |
| Samsung Apple PCIe SSD                                                           | 2         | 0.3%    |
| Phison E12 NVMe Controller                                                       | 2         | 0.3%    |
| Lenovo Non-Volatile memory controller                                            | 2         | 0.3%    |
| KIOXIA NVMe SSD                                                                  | 2         | 0.3%    |
| Kingston Company A2000 NVMe SSD                                                  | 2         | 0.3%    |
| Intel Tiger Lake-LP SATA Controller                                              | 2         | 0.3%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 0.3%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 2         | 0.3%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 302       | 47.48%  |
| NVMe | 269       | 42.3%   |
| RAID | 38        | 5.97%   |
| IDE  | 27        | 4.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 374       | 76.17%  |
| AMD          | 114       | 23.22%  |
| PowerBook5,6 | 1         | 0.2%    |
| PowerBook5,4 | 1         | 0.2%    |
| PowerBook3,4 | 1         | 0.2%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz             | 18        | 3.67%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 18        | 3.67%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 14        | 2.85%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 13        | 2.65%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 12        | 2.44%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 12        | 2.44%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 11        | 2.24%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 11        | 2.24%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 10        | 2.04%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 9         | 1.83%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 9         | 1.83%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 9         | 1.83%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 8         | 1.63%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 8         | 1.63%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 7         | 1.43%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 6         | 1.22%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 6         | 1.22%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 6         | 1.22%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 6         | 1.22%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 6         | 1.22%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 5         | 1.02%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 5         | 1.02%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 5         | 1.02%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 5         | 1.02%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 5         | 1.02%   |
| Intel Core i9-9880H CPU @ 2.30GHz             | 4         | 0.81%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 4         | 0.81%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 4         | 0.81%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 0.81%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 4         | 0.81%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 0.81%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 4         | 0.81%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 0.81%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 4         | 0.81%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 0.81%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 4         | 0.81%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 3         | 0.61%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 0.61%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 3         | 0.61%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 3         | 0.61%   |
| Intel Core i5-4310U CPU @ 2.00GHz             | 3         | 0.61%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 0.61%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 3         | 0.61%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 3         | 0.61%   |
| AMD Ryzen 5 PRO 4650U with Radeon Graphics    | 3         | 0.61%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 2         | 0.41%   |
| Intel Pentium 3556U @ 1.70GHz                 | 2         | 0.41%   |
| Intel Core m3-8100Y CPU @ 1.10GHz             | 2         | 0.41%   |
| Intel Core i9-10980HK CPU @ 2.40GHz           | 2         | 0.41%   |
| Intel Core i9-10885H CPU @ 2.40GHz            | 2         | 0.41%   |
| Intel Core i7-9850H CPU @ 2.60GHz             | 2         | 0.41%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 2         | 0.41%   |
| Intel Core i7-7820HK CPU @ 2.90GHz            | 2         | 0.41%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 0.41%   |
| Intel Core i7-4900MQ CPU @ 2.80GHz            | 2         | 0.41%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz            | 2         | 0.41%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 2         | 0.41%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 2         | 0.41%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 2         | 0.41%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 0.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 172       | 35.03%  |
| Intel Core i5           | 100       | 20.37%  |
| AMD Ryzen 7             | 46        | 9.37%   |
| Other                   | 38        | 7.74%   |
| AMD Ryzen 5             | 20        | 4.07%   |
| AMD Ryzen 7 PRO         | 17        | 3.46%   |
| Intel Core 2 Duo        | 11        | 2.24%   |
| Intel Celeron           | 11        | 2.24%   |
| Intel Core i9           | 9         | 1.83%   |
| Intel Atom              | 9         | 1.83%   |
| AMD Ryzen 9             | 7         | 1.43%   |
| Intel Pentium           | 6         | 1.22%   |
| Intel Core i3           | 6         | 1.22%   |
| AMD Ryzen 3             | 5         | 1.02%   |
| AMD A6                  | 5         | 1.02%   |
| Intel Pentium M         | 4         | 0.81%   |
| Intel Core m3           | 3         | 0.61%   |
| AMD Ryzen 5 PRO         | 3         | 0.61%   |
| AMD A8                  | 3         | 0.61%   |
| Intel Xeon              | 2         | 0.41%   |
| Intel Genuine           | 2         | 0.41%   |
| Intel Pentium Silver    | 1         | 0.2%    |
| Intel Core Duo          | 1         | 0.2%    |
| Intel Core 2            | 1         | 0.2%    |
| Intel Celeron M         | 1         | 0.2%    |
| AMD Turion II Dual-Core | 1         | 0.2%    |
| AMD E1                  | 1         | 0.2%    |
| AMD E                   | 1         | 0.2%    |
| AMD Athlon Neo X2       | 1         | 0.2%    |
| AMD Athlon 64           | 1         | 0.2%    |
| AMD Athlon              | 1         | 0.2%    |
| AMD A12                 | 1         | 0.2%    |
| AMD A10                 | 1         | 0.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 4       | 202       | 41.14%  |
| 2       | 129       | 26.27%  |
| 8       | 80        | 16.29%  |
| 6       | 61        | 12.42%  |
| 1       | 15        | 3.05%   |
| Unknown | 2         | 0.41%   |
| 14      | 1         | 0.2%    |
| 12      | 1         | 0.2%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 489       | 99.59%  |
| Unknown | 2         | 0.41%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 412       | 83.91%  |
| 1       | 77        | 15.68%  |
| Unknown | 2         | 0.41%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 473       | 96.33%  |
| 32-bit         | 15        | 3.05%   |
| Unknown        | 3         | 0.61%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 64        | 12.62%  |
| 0x906ea    | 42        | 8.28%   |
| 0x806ea    | 29        | 5.72%   |
| 0x806ec    | 26        | 5.13%   |
| 0x0a50000c | 22        | 4.34%   |
| 0x206a7    | 20        | 3.94%   |
| 0x08600106 | 19        | 3.75%   |
| 0x806c1    | 17        | 3.35%   |
| 0x506e3    | 17        | 3.35%   |
| 0x806e9    | 16        | 3.16%   |
| 0x306a9    | 16        | 3.16%   |
| 0xa0652    | 15        | 2.96%   |
| 0x40651    | 15        | 2.96%   |
| 0x906e9    | 12        | 2.37%   |
| 0x806d1    | 12        | 2.37%   |
| 0x08108109 | 12        | 2.37%   |
| 0x406e3    | 11        | 2.17%   |
| 0x306d4    | 11        | 2.17%   |
| 0x306c3    | 11        | 2.17%   |
| 0x08600103 | 11        | 2.17%   |
| 0x906ed    | 9         | 1.78%   |
| 0x08108102 | 9         | 1.78%   |
| 0x30678    | 8         | 1.58%   |
| 0x08600104 | 6         | 1.18%   |
| 0x806eb    | 5         | 0.99%   |
| 0x08608103 | 5         | 0.99%   |
| 0x706e5    | 4         | 0.79%   |
| 0x6d8      | 4         | 0.79%   |
| 0x706a1    | 3         | 0.59%   |
| 0x6fb      | 3         | 0.59%   |
| 0x106c2    | 3         | 0.59%   |
| 0x1067a    | 3         | 0.59%   |
| 0x10676    | 3         | 0.59%   |
| 0x06003106 | 3         | 0.59%   |
| 0x806c2    | 2         | 0.39%   |
| 0x6fd      | 2         | 0.39%   |
| 0x6e8      | 2         | 0.39%   |
| 0x406c4    | 2         | 0.39%   |
| 0x40661    | 2         | 0.39%   |
| 0x20655    | 2         | 0.39%   |
| 0x0a50000b | 2         | 0.39%   |
| 0x08600102 | 2         | 0.39%   |
| 0x0810100b | 2         | 0.39%   |
| 0xa0671    | 1         | 0.2%    |
| 0xa0660    | 1         | 0.2%    |
| 0x906a3    | 1         | 0.2%    |
| 0x706a8    | 1         | 0.2%    |
| 0x6f6      | 1         | 0.2%    |
| 0x6ec      | 1         | 0.2%    |
| 0x6d6      | 1         | 0.2%    |
| 0x406c3    | 1         | 0.2%    |
| 0x20652    | 1         | 0.2%    |
| 0x106ca    | 1         | 0.2%    |
| 0x0a404101 | 1         | 0.2%    |
| 0x08701013 | 1         | 0.2%    |
| 0x08608102 | 1         | 0.2%    |
| 0x08101007 | 1         | 0.2%    |
| 0x08001105 | 1         | 0.2%    |
| 0x07030105 | 1         | 0.2%    |
| 0x0700010b | 1         | 0.2%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 160       | 32.45%  |
| Zen 2            | 42        | 8.52%   |
| Skylake          | 30        | 6.09%   |
| Haswell          | 29        | 5.88%   |
| Zen 3            | 24        | 4.87%   |
| Zen+             | 22        | 4.46%   |
| SandyBridge      | 22        | 4.46%   |
| TigerLake        | 21        | 4.26%   |
| IvyBridge        | 17        | 3.45%   |
| Icelake          | 17        | 3.45%   |
| CometLake        | 16        | 3.25%   |
| Unknown          | 15        | 3.04%   |
| Broadwell        | 12        | 2.43%   |
| Silvermont       | 11        | 2.23%   |
| P6               | 8         | 1.62%   |
| Westmere         | 6         | 1.22%   |
| Penryn           | 6         | 1.22%   |
| Core             | 6         | 1.22%   |
| Bonnell          | 5         | 1.01%   |
| Zen              | 4         | 0.81%   |
| Goldmont plus    | 4         | 0.81%   |
| Steamroller      | 3         | 0.61%   |
| Puma             | 2         | 0.41%   |
| K8 Hammer        | 2         | 0.41%   |
| K10 Llano        | 2         | 0.41%   |
| Excavator        | 2         | 0.41%   |
| Bobcat           | 2         | 0.41%   |
| Jaguar           | 1         | 0.2%    |
| Goldmont         | 1         | 0.2%    |
| Alderlake Hybrid | 1         | 0.2%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 338       | 51.06%  |
| Nvidia | 197       | 29.76%  |
| AMD    | 127       | 19.18%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 48        | 7.05%   |
| AMD Renoir                                                                               | 38        | 5.58%   |
| Intel UHD Graphics 620                                                                   | 34        | 4.99%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 22        | 3.23%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 22        | 3.23%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 21        | 3.08%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 21        | 3.08%   |
| AMD Cezanne                                                                              | 19        | 2.79%   |
| Intel HD Graphics 530                                                                    | 18        | 2.64%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 16        | 2.35%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 16        | 2.35%   |
| Intel HD Graphics 620                                                                    | 15        | 2.2%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 14        | 2.06%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 13        | 1.91%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 12        | 1.76%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 12        | 1.76%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 11        | 1.62%   |
| Intel HD Graphics 5500                                                                   | 11        | 1.62%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 11        | 1.62%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 10        | 1.47%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 10        | 1.47%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 10        | 1.47%   |
| Intel HD Graphics 630                                                                    | 9         | 1.32%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 8         | 1.17%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 8         | 1.17%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 1.17%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 7         | 1.03%   |
| Nvidia GP108M [GeForce MX150]                                                            | 7         | 1.03%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 7         | 1.03%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 6         | 0.88%   |
| Nvidia TU117M                                                                            | 6         | 0.88%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 6         | 0.88%   |
| AMD Lucienne                                                                             | 6         | 0.88%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 5         | 0.73%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 0.59%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 4         | 0.59%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 0.59%   |
| Nvidia GP108M [GeForce MX250]                                                            | 3         | 0.44%   |
| Nvidia GP104BM [GeForce GTX 1080 Mobile]                                                 | 3         | 0.44%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 3         | 0.44%   |
| Nvidia GM107GLM [Quadro M2000M]                                                          | 3         | 0.44%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 3         | 0.44%   |
| Intel UHD Graphics 615                                                                   | 3         | 0.44%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 0.44%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 0.44%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 0.44%   |
| Intel Iris Plus Graphics G7                                                              | 3         | 0.44%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 0.44%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 0.44%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 0.44%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 3         | 0.44%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 0.44%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                                     | 3         | 0.44%   |
| Nvidia TU117M [GeForce MX450]                                                            | 2         | 0.29%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 2         | 0.29%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 2         | 0.29%   |
| Nvidia TU104GLM [Quadro RTX 4000 Mobile / Max-Q]                                         | 2         | 0.29%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                                 | 2         | 0.29%   |
| Nvidia GM204M [GeForce GTX 970M]                                                         | 2         | 0.29%   |
| Nvidia GM108M [GeForce MX130]                                                            | 2         | 0.29%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 181       | 36.64%  |
| Intel + Nvidia | 141       | 28.54%  |
| 1 x AMD        | 90        | 18.22%  |
| 1 x Nvidia     | 41        | 8.3%    |
| AMD + Nvidia   | 16        | 3.24%   |
| Intel + AMD    | 13        | 2.63%   |
| 2 x AMD        | 9         | 1.82%   |
| 2 x Intel      | 2         | 0.4%    |
| 2 x Nvidia     | 1         | 0.2%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 385       | 75.94%  |
| Proprietary | 106       | 20.91%  |
| Unknown     | 16        | 3.16%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 285       | 56.44%  |
| 0.01-0.5   | 72        | 14.26%  |
| 1.01-2.0   | 52        | 10.3%   |
| 3.01-4.0   | 41        | 8.12%   |
| 0.51-1.0   | 18        | 3.56%   |
| 5.01-6.0   | 17        | 3.37%   |
| 7.01-8.0   | 12        | 2.38%   |
| 8.01-16.0  | 5         | 0.99%   |
| 2.01-3.0   | 3         | 0.59%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 104       | 17.42%  |
| LG Display              | 84        | 14.07%  |
| BOE                     | 82        | 13.74%  |
| Chimei Innolux          | 69        | 11.56%  |
| Samsung Electronics     | 49        | 8.21%   |
| Sharp                   | 37        | 6.2%    |
| Dell                    | 32        | 5.36%   |
| Apple                   | 17        | 2.85%   |
| Chi Mei Optoelectronics | 13        | 2.18%   |
| Lenovo                  | 10        | 1.68%   |
| Hewlett-Packard         | 8         | 1.34%   |
| Goldstar                | 8         | 1.34%   |
| CSO                     | 8         | 1.34%   |
| PANDA                   | 6         | 1.01%   |
| InfoVision              | 6         | 1.01%   |
| AOC                     | 6         | 1.01%   |
| BenQ                    | 5         | 0.84%   |
| Ancor Communications    | 5         | 0.84%   |
| Philips                 | 4         | 0.67%   |
| Iiyama                  | 4         | 0.67%   |
| Acer                    | 4         | 0.67%   |
| ViewSonic               | 3         | 0.5%    |
| Eizo                    | 3         | 0.5%    |
| ASUSTek Computer        | 3         | 0.5%    |
| Sony                    | 2         | 0.34%   |
| MSI                     | 2         | 0.34%   |
| LGD                     | 2         | 0.34%   |
| LG Philips              | 2         | 0.34%   |
| HannStar                | 2         | 0.34%   |
| Gigabyte Technology     | 2         | 0.34%   |
| Fujitsu Siemens         | 2         | 0.34%   |
| CMN                     | 2         | 0.34%   |
| Xiaomi                  | 1         | 0.17%   |
| WST                     | 1         | 0.17%   |
| Unknown                 | 1         | 0.17%   |
| Toshiba                 | 1         | 0.17%   |
| TMX                     | 1         | 0.17%   |
| RTK                     | 1         | 0.17%   |
| QBell                   | 1         | 0.17%   |
| Mi                      | 1         | 0.17%   |
| IBM                     | 1         | 0.17%   |
| Gateway                 | 1         | 0.17%   |
| CPT                     | 1         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 8         | 1.32%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 6         | 0.99%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 6         | 0.99%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 6         | 0.99%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 5         | 0.83%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch        | 4         | 0.66%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 3         | 0.5%    |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch               | 3         | 0.5%    |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 3         | 0.5%    |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 3         | 0.5%    |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch               | 3         | 0.5%    |
| Samsung Electronics LCD Monitor SEC3245 1280x800 331x207mm 15.4-inch  | 3         | 0.5%    |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 3         | 0.5%    |
| LG Display LCD Monitor LGD0608 1920x1080 309x174mm 14.0-inch          | 3         | 0.5%    |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 3         | 0.5%    |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 3         | 0.5%    |
| Dell U2715H DELD066 2560x1440 597x336mm 27.0-inch                     | 3         | 0.5%    |
| Dell U2414H DELA0A3 1920x1080 527x296mm 23.8-inch                     | 3         | 0.5%    |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 3         | 0.5%    |
| BOE LCD Monitor BOE0898 1920x1080 294x165mm 13.3-inch                 | 3         | 0.5%    |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 3         | 0.5%    |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                 | 3         | 0.5%    |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch        | 3         | 0.5%    |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch        | 3         | 0.5%    |
| AU Optronics LCD Monitor AUO2336 2560x1440 309x174mm 14.0-inch        | 3         | 0.5%    |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 3         | 0.5%    |
| Apple Color LCD APP9C20 1280x854 321x214mm 15.2-inch                  | 3         | 0.5%    |
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch               | 2         | 0.33%   |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch               | 2         | 0.33%   |
| Sharp LCD Monitor SHP14D6 3840x2400 366x229mm 17.0-inch               | 2         | 0.33%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 2         | 0.33%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch               | 2         | 0.33%   |
| Samsung Electronics U28E570 SAM0D71 3840x2160 608x345mm 27.5-inch     | 2         | 0.33%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch | 2         | 0.33%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 2         | 0.33%   |
| Samsung Electronics LCD Monitor SAM0B7C 1920x1080 480x270mm 21.7-inch | 2         | 0.33%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch     | 2         | 0.33%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 2         | 0.33%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch               | 2         | 0.33%   |
| LGD LCD Monitor 1920x1080                                             | 2         | 0.33%   |
| LG Display LCD Monitor LGD06E0 1920x1080 344x194mm 15.5-inch          | 2         | 0.33%   |
| LG Display LCD Monitor LGD0657 1920x1080 344x194mm 15.5-inch          | 2         | 0.33%   |
| LG Display LCD Monitor LGD062C 1920x1080 309x174mm 14.0-inch          | 2         | 0.33%   |
| LG Display LCD Monitor LGD054F 1920x1080 344x194mm 15.5-inch          | 2         | 0.33%   |
| LG Display LCD Monitor LGD045D 1366x768 344x194mm 15.5-inch           | 2         | 0.33%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch          | 2         | 0.33%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 2         | 0.33%   |
| Hewlett-Packard 24w HPN3431 1920x1080 527x296mm 23.8-inch             | 2         | 0.33%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch              | 2         | 0.33%   |
| Gigabyte Technology G34WQC GBT3400 3440x1440 800x330mm 34.1-inch      | 2         | 0.33%   |
| Fujitsu Siemens P24W-6 IPS FUS07EA 1920x1200 518x324mm 24.1-inch      | 2         | 0.33%   |
| Dell U2715H DELD065 2560x1440 600x340mm 27.2-inch                     | 2         | 0.33%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                     | 2         | 0.33%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 2         | 0.33%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch      | 2         | 0.33%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch      | 2         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 2         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 2         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15CC 1366x768 344x193mm 15.5-inch       | 2         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch       | 2         | 0.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 301       | 54.04%  |
| 1366x768 (WXGA)    | 66        | 11.85%  |
| 3840x2160 (4K)     | 31        | 5.57%   |
| 2560x1440 (QHD)    | 29        | 5.21%   |
| 1600x900 (HD+)     | 18        | 3.23%   |
| 2560x1600          | 12        | 2.15%   |
| 1920x1200 (WUXGA)  | 12        | 2.15%   |
| 3840x2400          | 11        | 1.97%   |
| 1440x900 (WXGA+)   | 10        | 1.8%    |
| 1280x800 (WXGA)    | 9         | 1.62%   |
| 1680x1050 (WSXGA+) | 8         | 1.44%   |
| 3440x1440          | 7         | 1.26%   |
| 1024x600           | 5         | 0.9%    |
| 2880x1800          | 4         | 0.72%   |
| 1280x1024 (SXGA)   | 4         | 0.72%   |
| 3200x1800 (QHD+)   | 3         | 0.54%   |
| 1280x854           | 3         | 0.54%   |
| 3840x1080          | 2         | 0.36%   |
| 2256x1504          | 2         | 0.36%   |
| 2160x1440          | 2         | 0.36%   |
| 2048x1152          | 2         | 0.36%   |
| Unknown            | 2         | 0.36%   |
| 5040x1080          | 1         | 0.18%   |
| 3840x1200          | 1         | 0.18%   |
| 3840x1100          | 1         | 0.18%   |
| 3456x2160          | 1         | 0.18%   |
| 3200x2000          | 1         | 0.18%   |
| 3072x1920          | 1         | 0.18%   |
| 2520x1680          | 1         | 0.18%   |
| 2304x1440          | 1         | 0.18%   |
| 2288x1287          | 1         | 0.18%   |
| 2240x1400          | 1         | 0.18%   |
| 1920x1280          | 1         | 0.18%   |
| 1600x1200          | 1         | 0.18%   |
| 1400x1050          | 1         | 0.18%   |
| 1280x768           | 1         | 0.18%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 221       | 37.39%  |
| 13      | 90        | 15.23%  |
| 14      | 64        | 10.83%  |
| 17      | 39        | 6.6%    |
| 27      | 33        | 5.58%   |
| 24      | 25        | 4.23%   |
| 12      | 25        | 4.23%   |
| 23      | 17        | 2.88%   |
| 16      | 10        | 1.69%   |
| 11      | 10        | 1.69%   |
| 34      | 7         | 1.18%   |
| 21      | 7         | 1.18%   |
| Unknown | 7         | 1.18%   |
| 19      | 5         | 0.85%   |
| 22      | 4         | 0.68%   |
| 31      | 3         | 0.51%   |
| 25      | 3         | 0.51%   |
| 18      | 3         | 0.51%   |
| 10      | 3         | 0.51%   |
| 40      | 2         | 0.34%   |
| 8       | 2         | 0.34%   |
| 142     | 1         | 0.17%   |
| 75      | 1         | 0.17%   |
| 72      | 1         | 0.17%   |
| 65      | 1         | 0.17%   |
| 54      | 1         | 0.17%   |
| 49      | 1         | 0.17%   |
| 43      | 1         | 0.17%   |
| 37      | 1         | 0.17%   |
| 29      | 1         | 0.17%   |
| 26      | 1         | 0.17%   |
| 20      | 1         | 0.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 334       | 57.09%  |
| 201-300        | 84        | 14.36%  |
| 501-600        | 72        | 12.31%  |
| 351-400        | 43        | 7.35%   |
| 401-500        | 19        | 3.25%   |
| 701-800        | 7         | 1.2%    |
| 601-700        | 7         | 1.2%    |
| Unknown        | 7         | 1.2%    |
| 1001-1500      | 4         | 0.68%   |
| 801-900        | 3         | 0.51%   |
| 1501-2000      | 2         | 0.34%   |
| 101-200        | 2         | 0.34%   |
| More than 2000 | 1         | 0.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 412       | 79.69%  |
| 16/10   | 69        | 13.35%  |
| 3/2     | 13        | 2.51%   |
| 21/9    | 7         | 1.35%   |
| Unknown | 6         | 1.16%   |
| 5/4     | 3         | 0.58%   |
| 4/3     | 3         | 0.58%   |
| 32/9    | 1         | 0.19%   |
| 3.40    | 1         | 0.19%   |
| 3.20    | 1         | 0.19%   |
| 1.00    | 1         | 0.19%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 219       | 36.93%  |
| 81-90          | 111       | 18.72%  |
| 71-80          | 43        | 7.25%   |
| 201-250        | 40        | 6.75%   |
| 301-350        | 34        | 5.73%   |
| 121-130        | 34        | 5.73%   |
| 61-70          | 23        | 3.88%   |
| 251-300        | 14        | 2.36%   |
| 111-120        | 12        | 2.02%   |
| 51-60          | 11        | 1.85%   |
| 351-500        | 11        | 1.85%   |
| 151-200        | 7         | 1.18%   |
| Unknown        | 7         | 1.18%   |
| More than 1000 | 5         | 0.84%   |
| 501-1000       | 5         | 0.84%   |
| 141-150        | 4         | 0.67%   |
| 131-140        | 4         | 0.67%   |
| 91-100         | 4         | 0.67%   |
| 41-50          | 3         | 0.51%   |
| 1-40           | 2         | 0.34%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 285       | 49.05%  |
| 101-120       | 92        | 15.83%  |
| 51-100        | 86        | 14.8%   |
| 161-240       | 69        | 11.88%  |
| More than 240 | 38        | 6.54%   |
| Unknown       | 7         | 1.2%    |
| 1-50          | 4         | 0.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 388       | 75.34%  |
| 2     | 97        | 18.83%  |
| 0     | 16        | 3.11%   |
| 3     | 14        | 2.72%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 328       | 42.65%  |
| Realtek Semiconductor             | 232       | 30.17%  |
| Qualcomm Atheros                  | 81        | 10.53%  |
| Broadcom                          | 27        | 3.51%   |
| Lenovo                            | 11        | 1.43%   |
| MediaTek                          | 10        | 1.3%    |
| Marvell Technology Group          | 8         | 1.04%   |
| Dell                              | 7         | 0.91%   |
| ASIX Electronics                  | 7         | 0.91%   |
| Ericsson Business Mobile Networks | 5         | 0.65%   |
| Apple                             | 5         | 0.65%   |
| Sierra Wireless                   | 4         | 0.52%   |
| Samsung Electronics               | 4         | 0.52%   |
| Fibocom                           | 4         | 0.52%   |
| Broadcom Limited                  | 4         | 0.52%   |
| TP-Link                           | 3         | 0.39%   |
| Qualcomm Atheros Communications   | 3         | 0.39%   |
| Qualcomm                          | 3         | 0.39%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.26%   |
| Xiaomi                            | 2         | 0.26%   |
| Ralink Technology                 | 2         | 0.26%   |
| Ralink                            | 2         | 0.26%   |
| D-Link System                     | 2         | 0.26%   |
| Shenzhen Goodix Technology        | 1         | 0.13%   |
| Prusa                             | 1         | 0.13%   |
| Nvidia                            | 1         | 0.13%   |
| NetGear                           | 1         | 0.13%   |
| Microsoft                         | 1         | 0.13%   |
| JMicron Technology                | 1         | 0.13%   |
| ICS Advent                        | 1         | 0.13%   |
| Huawei Technologies               | 1         | 0.13%   |
| Google                            | 1         | 0.13%   |
| D-Link                            | 1         | 0.13%   |
| BUFFALO                           | 1         | 0.13%   |
| Aquantia                          | 1         | 0.13%   |
| AMD                               | 1         | 0.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 168       | 17.87%  |
| Intel Wi-Fi 6 AX200                                                     | 59        | 6.28%   |
| Intel Wireless 8265 / 8275                                              | 41        | 4.36%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 32        | 3.4%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 24        | 2.55%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 19        | 2.02%   |
| Intel Wireless 7265                                                     | 19        | 2.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 18        | 1.91%   |
| Intel Wi-Fi 6 AX201                                                     | 17        | 1.81%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 17        | 1.81%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 16        | 1.7%    |
| Intel Wireless 7260                                                     | 15        | 1.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 15        | 1.6%    |
| Intel Ethernet Connection (4) I219-LM                                   | 14        | 1.49%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 14        | 1.49%   |
| Intel Wireless 8260                                                     | 13        | 1.38%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 13        | 1.38%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 13        | 1.38%   |
| Intel Wireless 3165                                                     | 12        | 1.28%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 11        | 1.17%   |
| Intel Ethernet Connection (4) I219-V                                    | 11        | 1.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 10        | 1.06%   |
| Intel Ethernet Connection (6) I219-V                                    | 9         | 0.96%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 8         | 0.85%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller               | 8         | 0.85%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 8         | 0.85%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 8         | 0.85%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 8         | 0.85%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 7         | 0.74%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 0.74%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 7         | 0.74%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 7         | 0.74%   |
| Intel Ethernet Connection I218-LM                                       | 7         | 0.74%   |
| Intel Ethernet Connection (2) I219-LM                                   | 7         | 0.74%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 6         | 0.64%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 0.64%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 0.64%   |
| Intel Ethernet Connection (7) I219-LM                                   | 6         | 0.64%   |
| Intel Wireless-AC 9260                                                  | 5         | 0.53%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 0.53%   |
| Intel Ethernet Connection (3) I218-LM                                   | 5         | 0.53%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 4         | 0.43%   |
| Lenovo ThinkPad TBT 3 Dock                                              | 4         | 0.43%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 0.43%   |
| Intel Ethernet Connection I219-LM                                       | 4         | 0.43%   |
| Intel 82577LM Gigabit Network Connection                                | 4         | 0.43%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                       | 4         | 0.43%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 4         | 0.43%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 0.43%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 0.32%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 0.32%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 0.32%   |
| Qualcomm QCA6390 Wireless Network Adapter                               | 3         | 0.32%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller               | 3         | 0.32%   |
| Lenovo USB-C Dock Ethernet                                              | 3         | 0.32%   |
| Intel Wireless 3160                                                     | 3         | 0.32%   |
| Intel I210 Gigabit Network Connection                                   | 3         | 0.32%   |
| Intel Ethernet Connection I217-LM                                       | 3         | 0.32%   |
| Intel Ethernet Connection (7) I219-V                                    | 3         | 0.32%   |
| Intel Ethernet Connection (14) I219-LM                                  | 3         | 0.32%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 320       | 62.75%  |
| Qualcomm Atheros                | 65        | 12.75%  |
| Realtek Semiconductor           | 61        | 11.96%  |
| Broadcom                        | 24        | 4.71%   |
| MediaTek                        | 9         | 1.76%   |
| Dell                            | 5         | 0.98%   |
| Sierra Wireless                 | 4         | 0.78%   |
| Qualcomm Atheros Communications | 3         | 0.59%   |
| Qualcomm                        | 3         | 0.59%   |
| Fibocom                         | 3         | 0.59%   |
| TP-Link                         | 2         | 0.39%   |
| Ralink Technology               | 2         | 0.39%   |
| Ralink                          | 2         | 0.39%   |
| D-Link System                   | 2         | 0.39%   |
| NetGear                         | 1         | 0.2%    |
| Microsoft                       | 1         | 0.2%    |
| D-Link                          | 1         | 0.2%    |
| BUFFALO                         | 1         | 0.2%    |
| Broadcom Limited                | 1         | 0.2%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 59        | 11.52%  |
| Intel Wireless 8265 / 8275                                              | 41        | 8.01%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 32        | 6.25%   |
| Intel Wireless 7265                                                     | 19        | 3.71%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 18        | 3.52%   |
| Intel Wi-Fi 6 AX201                                                     | 17        | 3.32%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 17        | 3.32%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 16        | 3.13%   |
| Intel Wireless 7260                                                     | 15        | 2.93%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 14        | 2.73%   |
| Intel Wireless 8260                                                     | 13        | 2.54%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 13        | 2.54%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 13        | 2.54%   |
| Intel Wireless 3165                                                     | 12        | 2.34%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 11        | 2.15%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 10        | 1.95%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 8         | 1.56%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 8         | 1.56%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 8         | 1.56%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 8         | 1.56%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 7         | 1.37%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 1.37%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 7         | 1.37%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 7         | 1.37%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 6         | 1.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 1.17%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 1.17%   |
| Intel Wireless-AC 9260                                                  | 5         | 0.98%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 0.98%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 0.78%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 4         | 0.78%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 0.78%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 0.59%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 0.59%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 0.59%   |
| Qualcomm QCA6390 Wireless Network Adapter                               | 3         | 0.59%   |
| Intel Wireless 3160                                                     | 3         | 0.59%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 0.59%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 0.59%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 0.59%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                       | 3         | 0.59%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 3         | 0.59%   |
| Sierra Wireless EM7455                                                  | 2         | 0.39%   |
| Sierra Wireless EM7345 4G LTE                                           | 2         | 0.39%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 0.39%   |
| Qualcomm Atheros AR9271 802.11n                                         | 2         | 0.39%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 2         | 0.39%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 2         | 0.39%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 0.39%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 0.39%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 2         | 0.39%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 0.39%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 0.39%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                                    | 2         | 0.39%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 0.39%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 2         | 0.39%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 0.39%   |
| Broadcom BCM4306 802.11b/g Wireless LAN Controller                      | 2         | 0.39%   |
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                                 | 1         | 0.2%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 1         | 0.2%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 213       | 52.21%  |
| Intel                      | 113       | 27.7%   |
| Qualcomm Atheros           | 23        | 5.64%   |
| Lenovo                     | 11        | 2.7%    |
| Broadcom                   | 10        | 2.45%   |
| Marvell Technology Group   | 8         | 1.96%   |
| ASIX Electronics           | 7         | 1.72%   |
| Apple                      | 5         | 1.23%   |
| Samsung Electronics        | 3         | 0.74%   |
| Broadcom Limited           | 3         | 0.74%   |
| ZTE WCDMA Technologies MSM | 2         | 0.49%   |
| Xiaomi                     | 2         | 0.49%   |
| TP-Link                    | 1         | 0.25%   |
| Nvidia                     | 1         | 0.25%   |
| JMicron Technology         | 1         | 0.25%   |
| ICS Advent                 | 1         | 0.25%   |
| Huawei Technologies        | 1         | 0.25%   |
| Google                     | 1         | 0.25%   |
| Fibocom                    | 1         | 0.25%   |
| Aquantia                   | 1         | 0.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 168       | 40.78%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 24        | 5.83%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 19        | 4.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 15        | 3.64%   |
| Intel Ethernet Connection (4) I219-LM                                          | 14        | 3.4%    |
| Intel Ethernet Connection (4) I219-V                                           | 11        | 2.67%   |
| Intel Ethernet Connection (6) I219-V                                           | 9         | 2.18%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 8         | 1.94%   |
| Intel Ethernet Connection I218-LM                                              | 7         | 1.7%    |
| Intel Ethernet Connection (2) I219-LM                                          | 7         | 1.7%    |
| Intel Ethernet Connection (7) I219-LM                                          | 6         | 1.46%   |
| Intel Ethernet Connection (3) I218-LM                                          | 5         | 1.21%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 4         | 0.97%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 4         | 0.97%   |
| Intel Ethernet Connection I219-LM                                              | 4         | 0.97%   |
| Intel 82577LM Gigabit Network Connection                                       | 4         | 0.97%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 4         | 0.97%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 3         | 0.73%   |
| Lenovo USB-C Dock Ethernet                                                     | 3         | 0.73%   |
| Intel I210 Gigabit Network Connection                                          | 3         | 0.73%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 0.73%   |
| Intel Ethernet Connection (7) I219-V                                           | 3         | 0.73%   |
| Intel Ethernet Connection (14) I219-LM                                         | 3         | 0.73%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 2         | 0.49%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2         | 0.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 2         | 0.49%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 0.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2         | 0.49%   |
| Lenovo Thinkpad LAN                                                            | 2         | 0.49%   |
| Intel Ethernet Connection I219-V                                               | 2         | 0.49%   |
| Intel Ethernet Connection (5) I219-V                                           | 2         | 0.49%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2         | 0.49%   |
| Intel Ethernet Connection (14) I219-V                                          | 2         | 0.49%   |
| Intel Ethernet Connection (13) I219-LM                                         | 2         | 0.49%   |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 0.49%   |
| Intel Ethernet Connection (10) I219-LM                                         | 2         | 0.49%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express                 | 2         | 0.49%   |
| ASIX AX88772B Fast Ethernet Controller                                         | 2         | 0.49%   |
| ASIX AX88772B                                                                  | 2         | 0.49%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 0.49%   |
| Apple UniNorth 2 GMAC (Sun GEM)                                                | 2         | 0.49%   |
| ZTE WCDMA MSM ZTE MSM                                                          | 1         | 0.24%   |
| ZTE WCDMA MSM Z6201V                                                           | 1         | 0.24%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 0.24%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.24%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.24%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1         | 0.24%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.24%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.24%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                     | 1         | 0.24%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                  | 1         | 0.24%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.24%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.24%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.24%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1         | 0.24%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.24%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.24%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                        | 1         | 0.24%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 0.24%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                        | 1         | 0.24%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 486       | 54.67%  |
| Ethernet | 387       | 43.53%  |
| Modem    | 15        | 1.69%   |
| Unknown  | 1         | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 391       | 72.01%  |
| Ethernet | 152       | 27.99%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 335       | 68.09%  |
| 1     | 143       | 29.07%  |
| 3     | 12        | 2.44%   |
| 0     | 2         | 0.41%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 449       | 88.91%  |
| Yes  | 56        | 11.09%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 273       | 63.49%  |
| Realtek Semiconductor           | 38        | 8.84%   |
| Qualcomm Atheros Communications | 20        | 4.65%   |
| Lite-On Technology              | 16        | 3.72%   |
| Apple                           | 14        | 3.26%   |
| IMC Networks                    | 13        | 3.02%   |
| Foxconn / Hon Hai               | 11        | 2.56%   |
| Broadcom                        | 10        | 2.33%   |
| Dell                            | 7         | 1.63%   |
| Realtek                         | 6         | 1.4%    |
| Cambridge Silicon Radio         | 6         | 1.4%    |
| Hewlett-Packard                 | 4         | 0.93%   |
| Toshiba                         | 3         | 0.7%    |
| ASUSTek Computer                | 3         | 0.7%    |
| Foxconn International           | 2         | 0.47%   |
| Ralink Technology               | 1         | 0.23%   |
| Opticis                         | 1         | 0.23%   |
| Chicony Electronics             | 1         | 0.23%   |
| Askey Computer                  | 1         | 0.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 98        | 22.79%  |
| Intel AX200 Bluetooth                                                               | 58        | 13.49%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 54        | 12.56%  |
| Intel AX201 Bluetooth                                                               | 43        | 10%     |
| Realtek Bluetooth Radio                                                             | 20        | 4.65%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 13        | 3.02%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 9         | 2.09%   |
| Apple Bluetooth Host Controller                                                     | 9         | 2.09%   |
| Intel AX210 Bluetooth                                                               | 8         | 1.86%   |
| Intel Bluetooth Device                                                              | 7         | 1.63%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 7         | 1.63%   |
| Realtek Bluetooth Radio                                                             | 6         | 1.4%    |
| Lite-On Atheros AR3012 Bluetooth                                                    | 6         | 1.4%    |
| IMC Networks Wireless_Device                                                        | 6         | 1.4%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 6         | 1.4%    |
| Realtek RTL8723B Bluetooth                                                          | 5         | 1.16%   |
| Lite-On Bluetooth Device                                                            | 5         | 1.16%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 4         | 0.93%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 4         | 0.93%   |
| IMC Networks Bluetooth Radio                                                        | 4         | 0.93%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 0.7%    |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 3         | 0.7%    |
| IMC Networks Bluetooth Device                                                       | 3         | 0.7%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 3         | 0.7%    |
| Dell DW375 Bluetooth Module                                                         | 3         | 0.7%    |
| Dell BCM20702A0 Bluetooth Module                                                    | 3         | 0.7%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 3         | 0.7%    |
| Apple Bluetooth HCI                                                                 | 3         | 0.7%    |
| Toshiba Integrated Bluetooth (Taiyo Yuden)                                          | 2         | 0.47%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 2         | 0.47%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 0.47%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 2         | 0.47%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 2         | 0.47%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 2         | 0.47%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 2         | 0.47%   |
| ASUS Broadcom Bluetooth 2.1                                                         | 2         | 0.47%   |
| Apple Bluetooth USB Host Controller                                                 | 2         | 0.47%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.23%   |
| Ralink CSR BS8510                                                                   | 1         | 0.23%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.23%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 0.23%   |
| Opticis Bluetooth Radio                                                             | 1         | 0.23%   |
| Lite-On Bluetooth Radio                                                             | 1         | 0.23%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.23%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.23%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 0.23%   |
| Dell Wireless 350 Bluetooth                                                         | 1         | 0.23%   |
| Chicony Bluetooth (RTL8723BE)                                                       | 1         | 0.23%   |
| Broadcom HP Portable SoftSailing                                                    | 1         | 0.23%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.23%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 0.23%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                                               | 1         | 0.23%   |
| Askey Bluetooth Device                                                              | 1         | 0.23%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 368       | 55.01%  |
| AMD                                  | 118       | 17.64%  |
| Nvidia                               | 117       | 17.49%  |
| Lenovo                               | 11        | 1.64%   |
| Realtek Semiconductor                | 7         | 1.05%   |
| C-Media Electronics                  | 6         | 0.9%    |
| Plantronics                          | 4         | 0.6%    |
| Logitech                             | 3         | 0.45%   |
| Dell                                 | 3         | 0.45%   |
| Blue Microphones                     | 3         | 0.45%   |
| Razer USA                            | 2         | 0.3%    |
| No brand                             | 2         | 0.3%    |
| Kingston Technology                  | 2         | 0.3%    |
| GYROCOM C&C                          | 2         | 0.3%    |
| Creative Technology                  | 2         | 0.3%    |
| Thesycon Systemsoftware & Consulting | 1         | 0.15%   |
| Texas Instruments                    | 1         | 0.15%   |
| Tdlasunnic                           | 1         | 0.15%   |
| SteelSeries ApS                      | 1         | 0.15%   |
| Samson Technologies                  | 1         | 0.15%   |
| RODE Microphones                     | 1         | 0.15%   |
| LG Electronics                       | 1         | 0.15%   |
| JMTek                                | 1         | 0.15%   |
| iCreate Technologies                 | 1         | 0.15%   |
| Hewlett-Packard                      | 1         | 0.15%   |
| GN Netcom                            | 1         | 0.15%   |
| FiiO Electronics Technology          | 1         | 0.15%   |
| Behringer.......                     | 1         | 0.15%   |
| AVer Information                     | 1         | 0.15%   |
| AudioQuest                           | 1         | 0.15%   |
| ATOLL Electronique                   | 1         | 0.15%   |
| Apple                                | 1         | 0.15%   |
| ACTIONS                              | 1         | 0.15%   |
| A4Tech                               | 1         | 0.15%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 97        | 12.03%  |
| Intel Sunrise Point-LP HD Audio                                            | 66        | 8.19%   |
| Intel Cannon Lake PCH cAVS                                                 | 57        | 7.07%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 55        | 6.82%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 24        | 2.98%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 24        | 2.98%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 21        | 2.61%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 21        | 2.61%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 21        | 2.61%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 18        | 2.23%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 17        | 2.11%   |
| Intel Haswell-ULT HD Audio Controller                                      | 16        | 1.99%   |
| Intel 8 Series HD Audio Controller                                         | 16        | 1.99%   |
| Intel Comet Lake PCH cAVS                                                  | 15        | 1.86%   |
| Intel CM238 HD Audio Controller                                            | 15        | 1.86%   |
| Intel Comet Lake PCH-LP cAVS                                               | 14        | 1.74%   |
| Nvidia TU106 High Definition Audio Controller                              | 13        | 1.61%   |
| Nvidia GP107GL High Definition Audio Controller                            | 13        | 1.61%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 13        | 1.61%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 13        | 1.61%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 12        | 1.49%   |
| Intel Broadwell-U Audio Controller                                         | 12        | 1.49%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 10        | 1.24%   |
| Nvidia GP106 High Definition Audio Controller                              | 9         | 1.12%   |
| AMD FCH Azalia Controller                                                  | 9         | 1.12%   |
| Nvidia TU116 High Definition Audio Controller                              | 8         | 0.99%   |
| Nvidia GA106 High Definition Audio Controller                              | 8         | 0.99%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 8         | 0.99%   |
| Realtek Semiconductor USB Audio                                            | 7         | 0.87%   |
| Nvidia TU104 HD Audio Controller                                           | 7         | 0.87%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 7         | 0.87%   |
| Nvidia GP104 High Definition Audio Controller                              | 6         | 0.74%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 6         | 0.74%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6         | 0.74%   |
| Nvidia GA104 High Definition Audio Controller                              | 5         | 0.62%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 5         | 0.62%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 5         | 0.62%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 4         | 0.5%    |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                               | 4         | 0.5%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 0.5%    |
| AMD Navi 10 HDMI Audio                                                     | 4         | 0.5%    |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 0.5%    |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 0.37%   |
| Nvidia Audio device                                                        | 3         | 0.37%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                  | 3         | 0.37%   |
| Lenovo ThinkPad Dock USB Audio                                             | 3         | 0.37%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 0.37%   |
| Dell AC511 Sound Bar                                                       | 3         | 0.37%   |
| Blue Microphones Yeti Stereo Microphone                                    | 3         | 0.37%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3         | 0.37%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 3         | 0.37%   |
| Razer USA Razer Kraken X USB                                               | 2         | 0.25%   |
| Plantronics Blackwire 5220 Series                                          | 2         | 0.25%   |
| Nvidia High Definition Audio Controller                                    | 2         | 0.25%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 0.25%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2         | 0.25%   |
| No brand CalDigit Thunderbolt 3 Audio                                      | 2         | 0.25%   |
| Logitech G935 Gaming Headset                                               | 2         | 0.25%   |
| Kingston Technology HyperX 7.1 Audio                                       | 2         | 0.25%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller | 2         | 0.25%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 180       | 32.14%  |
| SK hynix                     | 127       | 22.68%  |
| Micron Technology            | 77        | 13.75%  |
| Kingston                     | 42        | 7.5%    |
| Unknown                      | 31        | 5.54%   |
| Crucial                      | 30        | 5.36%   |
| Ramaxel Technology           | 13        | 2.32%   |
| A-DATA Technology            | 9         | 1.61%   |
| Corsair                      | 8         | 1.43%   |
| Elpida                       | 7         | 1.25%   |
| Transcend                    | 5         | 0.89%   |
| G.Skill                      | 5         | 0.89%   |
| Team                         | 4         | 0.71%   |
| Nanya Technology             | 4         | 0.71%   |
| Goodram                      | 4         | 0.71%   |
| Patriot                      | 3         | 0.54%   |
| Unknown (ABCD)               | 2         | 0.36%   |
| Unknown (0x5D00000000000000) | 1         | 0.18%   |
| Timetec                      | 1         | 0.18%   |
| Teikon                       | 1         | 0.18%   |
| Saikano                      | 1         | 0.18%   |
| Magnum Tech                  | 1         | 0.18%   |
| Goldkey                      | 1         | 0.18%   |
| AMD                          | 1         | 0.18%   |
| 48spaces                     | 1         | 0.18%   |
| Unknown                      | 1         | 0.18%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s        | 9         | 1.53%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s         | 9         | 1.53%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s      | 9         | 1.53%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s          | 9         | 1.53%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s         | 8         | 1.36%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s         | 8         | 1.36%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s         | 8         | 1.36%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s        | 7         | 1.19%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s       | 7         | 1.19%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s     | 7         | 1.19%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s      | 7         | 1.19%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s        | 7         | 1.19%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s        | 7         | 1.19%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s        | 6         | 1.02%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s        | 6         | 1.02%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s   | 6         | 1.02%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s          | 6         | 1.02%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 5         | 0.85%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s        | 5         | 0.85%   |
| Samsung RAM M471A1K43EB1-CWE 8192MB SODIMM DDR4 3200MT/s      | 5         | 0.85%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s         | 5         | 0.85%   |
| Samsung RAM M471A1K43DB1-CTD 8192MB SODIMM DDR4 2667MT/s      | 5         | 0.85%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s         | 5         | 0.85%   |
| Unknown RAM Module 1GB SODIMM DDR                             | 4         | 0.68%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s        | 4         | 0.68%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 4         | 0.68%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s        | 4         | 0.68%   |
| Samsung RAM M471A2K43CB1-CRC 16384MB SODIMM DDR4 2667MT/s     | 4         | 0.68%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s         | 4         | 0.68%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s         | 4         | 0.68%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s | 4         | 0.68%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16384MB SODIMM DDR4 3200MT/s      | 4         | 0.68%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s        | 4         | 0.68%   |
| Kingston RAM 9905744-066.A00G 32GB SODIMM DDR4 3200MT/s       | 4         | 0.68%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2400MT/s               | 3         | 0.51%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s        | 3         | 0.51%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s       | 3         | 0.51%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s  | 3         | 0.51%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s        | 3         | 0.51%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 3         | 0.51%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s         | 3         | 0.51%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s         | 3         | 0.51%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s         | 3         | 0.51%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s         | 3         | 0.51%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s         | 3         | 0.51%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s        | 3         | 0.51%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s        | 3         | 0.51%   |
| Samsung RAM M471A1K43BB1-CTD 8192MB SODIMM DDR4 2667MT/s      | 3         | 0.51%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s     | 3         | 0.51%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s          | 3         | 0.51%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s         | 3         | 0.51%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s    | 3         | 0.51%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s         | 3         | 0.51%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                | 2         | 0.34%   |
| Team RAM TEAMGROUP-SD4-2400 16GB SODIMM DDR4 8400MT/s         | 2         | 0.34%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2667MT/s                  | 2         | 0.34%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                  | 2         | 0.34%   |
| SK hynix RAM Module 4GB SODIMM DDR4 2400MT/s                  | 2         | 0.34%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s         | 2         | 0.34%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s         | 2         | 0.34%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 295       | 62.5%   |
| DDR3    | 111       | 23.52%  |
| LPDDR4  | 20        | 4.24%   |
| LPDDR3  | 17        | 3.6%    |
| DDR2    | 14        | 2.97%   |
| DDR     | 6         | 1.27%   |
| SDRAM   | 5         | 1.06%   |
| Unknown | 3         | 0.64%   |
| DRAM    | 1         | 0.21%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 424       | 89.45%  |
| Row Of Chips | 43        | 9.07%   |
| Chip         | 5         | 1.05%   |
| DIMM         | 2         | 0.42%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 227       | 44.34%  |
| 4096  | 105       | 20.51%  |
| 16384 | 100       | 19.53%  |
| 2048  | 36        | 7.03%   |
| 32768 | 24        | 4.69%   |
| 1024  | 15        | 2.93%   |
| 512   | 3         | 0.59%   |
| 256   | 2         | 0.39%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 147       | 28.43%  |
| 3200    | 110       | 21.28%  |
| 1600    | 80        | 15.47%  |
| 2400    | 40        | 7.74%   |
| 2133    | 31        | 6%      |
| 1333    | 15        | 2.9%    |
| 1334    | 11        | 2.13%   |
| 667     | 11        | 2.13%   |
| Unknown | 10        | 1.93%   |
| 4267    | 9         | 1.74%   |
| 1867    | 8         | 1.55%   |
| 3266    | 7         | 1.35%   |
| 8400    | 6         | 1.16%   |
| 1067    | 5         | 0.97%   |
| 800     | 5         | 0.97%   |
| 4800    | 4         | 0.77%   |
| 4266    | 3         | 0.58%   |
| 2933    | 3         | 0.58%   |
| 533     | 3         | 0.58%   |
| 3733    | 2         | 0.39%   |
| 3000    | 2         | 0.39%   |
| 400     | 2         | 0.39%   |
| 4199    | 1         | 0.19%   |
| 1639    | 1         | 0.19%   |
| 1066    | 1         | 0.19%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 3         | 33.33%  |
| Seiko Epson         | 2         | 22.22%  |
| Xiaomi              | 1         | 11.11%  |
| Samsung Electronics | 1         | 11.11%  |
| Konica Minolta      | 1         | 11.11%  |
| Canon               | 1         | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Xiaomi MiMouse 2                     | 1         | 11.11%  |
| Seiko Epson WF-2510 Series           | 1         | 11.11%  |
| Seiko Epson AL-M310DN                | 1         | 11.11%  |
| Samsung CLP-325 Color Laser Printer  | 1         | 11.11%  |
| Konica Minolta magicolor 1680MF scan | 1         | 11.11%  |
| HP Deskjet D1500 series              | 1         | 11.11%  |
| HP DeskJet 5440                      | 1         | 11.11%  |
| HP DeskJet 3630 series               | 1         | 11.11%  |
| Canon LiDE 300                       | 1         | 11.11%  |

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
| Chicony Electronics                    | 115       | 26.5%   |
| IMC Networks                           | 59        | 13.59%  |
| Microdia                               | 40        | 9.22%   |
| Realtek Semiconductor                  | 37        | 8.53%   |
| Acer                                   | 36        | 8.29%   |
| Sunplus Innovation Technology          | 26        | 5.99%   |
| Lite-On Technology                     | 17        | 3.92%   |
| Quanta                                 | 16        | 3.69%   |
| Cheng Uei Precision Industry (Foxlink) | 16        | 3.69%   |
| Syntek                                 | 11        | 2.53%   |
| Logitech                               | 10        | 2.3%    |
| Apple                                  | 9         | 2.07%   |
| Luxvisions Innotech Limited            | 7         | 1.61%   |
| Samsung Electronics                    | 4         | 0.92%   |
| Z-Star Microelectronics                | 3         | 0.69%   |
| DigiTech                               | 3         | 0.69%   |
| Suyin                                  | 2         | 0.46%   |
| Silicon Motion                         | 2         | 0.46%   |
| Microsoft                              | 2         | 0.46%   |
| LG Electronics                         | 2         | 0.46%   |
| DJJHNA29IE70D3                         | 2         | 0.46%   |
| Alcor Micro                            | 2         | 0.46%   |
| USB3.0 HD Audio Capture                | 1         | 0.23%   |
| ShineTech                              | 1         | 0.23%   |
| Ricoh                                  | 1         | 0.23%   |
| Razer USA                              | 1         | 0.23%   |
| Omnivision                             | 1         | 0.23%   |
| Lenovo                                 | 1         | 0.23%   |
| Intel                                  | 1         | 0.23%   |
| Holitech                               | 1         | 0.23%   |
| Hewlett-Packard                        | 1         | 0.23%   |
| Google                                 | 1         | 0.23%   |
| Genesys Logic                          | 1         | 0.23%   |
| AVer Information                       | 1         | 0.23%   |
| Aveo Technology                        | 1         | 0.23%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 36        | 8.2%    |
| Microdia Integrated_Webcam_HD                        | 27        | 6.15%   |
| IMC Networks Integrated Camera                       | 26        | 5.92%   |
| Realtek Integrated_Webcam_HD                         | 18        | 4.1%    |
| Acer Integrated Camera                               | 14        | 3.19%   |
| Chicony HD Webcam                                    | 13        | 2.96%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 12        | 2.73%   |
| Sunplus Integrated_Webcam_HD                         | 11        | 2.51%   |
| Chicony HP HD Camera                                 | 8         | 1.82%   |
| Lite-On Integrated Camera                            | 7         | 1.59%   |
| Syntek Integrated Camera                             | 6         | 1.37%   |
| Chicony USB2.0 Camera                                | 6         | 1.37%   |
| Sunplus HD WebCam                                    | 5         | 1.14%   |
| Chicony Integrated Camera (1280x720@30)              | 5         | 1.14%   |
| Samsung Galaxy A5 (MTP)                              | 4         | 0.91%   |
| Quanta HP Wide Vision HD Camera                      | 4         | 0.91%   |
| Microdia Integrated Webcam                           | 4         | 0.91%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 4         | 0.91%   |
| Logitech HD Pro Webcam C920                          | 4         | 0.91%   |
| IMC Networks USB2.0 HD IR UVC WebCam                 | 4         | 0.91%   |
| IMC Networks ov9734_azurewave_camera                 | 4         | 0.91%   |
| Chicony Lenovo EasyCamera                            | 4         | 0.91%   |
| Chicony HD User Facing                               | 4         | 0.91%   |
| Chicony EasyCamera                                   | 4         | 0.91%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera  | 4         | 0.91%   |
| Apple FaceTime HD Camera                             | 4         | 0.91%   |
| Acer SunplusIT Integrated Camera                     | 4         | 0.91%   |
| Acer BisonCam, NB Pro                                | 4         | 0.91%   |
| Syntek Lenovo EasyCamera                             | 3         | 0.68%   |
| Sunplus HP Wide Vision HD                            | 3         | 0.68%   |
| Realtek USB2.0 HD UVC WebCam                         | 3         | 0.68%   |
| Realtek Integrated Webcam HD                         | 3         | 0.68%   |
| Realtek Integrated Webcam                            | 3         | 0.68%   |
| Quanta HD User Facing                                | 3         | 0.68%   |
| Microdia Laptop_Integrated_Webcam_HD                 | 3         | 0.68%   |
| Lite-On TOSHIBA Web Camera - HD                      | 3         | 0.68%   |
| Lite-On HP Wide Vision HD Camera                     | 3         | 0.68%   |
| Chicony USB2.0 HD UVC WebCam                         | 3         | 0.68%   |
| Chicony USB 2.0 Camera                               | 3         | 0.68%   |
| Chicony ThinkPad T490 Webcam                         | 3         | 0.68%   |
| Apple Built-in iSight                                | 3         | 0.68%   |
| Acer HD Webcam                                       | 3         | 0.68%   |
| Suyin HP TrueVision HD                               | 2         | 0.46%   |
| Sunplus Laptop_Integrated_Webcam_FHD                 | 2         | 0.46%   |
| Sunplus Dell E5570 integrated webcam                 | 2         | 0.46%   |
| Realtek USB Camera                                   | 2         | 0.46%   |
| Realtek Integrated Webcam_HD                         | 2         | 0.46%   |
| Quanta VGA WebCam                                    | 2         | 0.46%   |
| Quanta HP HD Camera                                  | 2         | 0.46%   |
| Quanta HD Webcam                                     | 2         | 0.46%   |
| Microdia Integrated Webcam HD                        | 2         | 0.46%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 2         | 0.46%   |
| Logitech Webcam C310                                 | 2         | 0.46%   |
| Lite-On HP HD Camera                                 | 2         | 0.46%   |
| IMC Networks VGA UVC WebCam                          | 2         | 0.46%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 2         | 0.46%   |
| IMC Networks USB Camera                              | 2         | 0.46%   |
| IMC Networks Integrated RGB Camera                   | 2         | 0.46%   |
| DJJHNA29IE70D3 HP HD Camera                          | 2         | 0.46%   |
| DigiTech USB 2.0 PC Camera                           | 2         | 0.46%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 46        | 46.46%  |
| Validity Sensors           | 22        | 22.22%  |
| Shenzhen Goodix Technology | 15        | 15.15%  |
| Elan Microelectronics      | 6         | 6.06%   |
| AuthenTec                  | 4         | 4.04%   |
| STMicroelectronics         | 3         | 3.03%   |
| LighTuning Technology      | 2         | 2.02%   |
| Upek                       | 1         | 1.01%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 21        | 21.21%  |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 13        | 13.13%  |
| Validity Sensors VFS495 Fingerprint Reader                 | 6         | 6.06%   |
| Shenzhen Goodix  Fingerprint Device                        | 6         | 6.06%   |
| Unknown                                                    | 6         | 6.06%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 5         | 5.05%   |
| Validity Sensors Synaptics WBDI                            | 5         | 5.05%   |
| Shenzhen Goodix FingerPrint                                | 5         | 5.05%   |
| Elan ELAN:Fingerprint                                      | 5         | 5.05%   |
| Shenzhen Goodix Fingerprint Reader                         | 4         | 4.04%   |
| Validity Sensors VFS5011 Fingerprint Reader                | 3         | 3.03%   |
| STMicroelectronics Fingerprint Reader                      | 3         | 3.03%   |
| Validity Sensors Fingerprint scanner                       | 2         | 2.02%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 2.02%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 2         | 2.02%   |
| AuthenTec AES2501 Fingerprint Sensor                       | 2         | 2.02%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 1         | 1.01%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 1         | 1.01%   |
| Synaptics WBDI Device                                      | 1         | 1.01%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 1         | 1.01%   |
| LighTuning ES603 Swipe Fingerprint Sensor                  | 1         | 1.01%   |
| LighTuning EgisTec Touch Fingerprint Sensor                | 1         | 1.01%   |
| Elan ELAN:ARM-M4                                           | 1         | 1.01%   |
| AuthenTec Fingerprint Sensor                               | 1         | 1.01%   |
| AuthenTec AES2550 Fingerprint Sensor                       | 1         | 1.01%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 32        | 45.07%  |
| Broadcom              | 28        | 39.44%  |
| Upek                  | 4         | 5.63%   |
| O2 Micro              | 3         | 4.23%   |
| Yubico.com            | 1         | 1.41%   |
| Purism, SPC           | 1         | 1.41%   |
| Microchip Technology  | 1         | 1.41%   |
| Gemalto (was Gemplus) | 1         | 1.41%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 32        | 45.07%  |
| Broadcom 5880                                                                | 10        | 14.08%  |
| Broadcom 58200                                                               | 8         | 11.27%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 8.45%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 5.63%   |
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 5.63%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 2.82%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 1.41%   |
| Purism, SPC Librem Key                                                       | 1         | 1.41%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.41%   |
| Microchip Technology SMSC USX101x Reader                                     | 1         | 1.41%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 1.41%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 184       | 33.33%  |
| 1     | 146       | 26.45%  |
| 2     | 87        | 15.76%  |
| 3     | 64        | 11.59%  |
| 4     | 41        | 7.43%   |
| 5     | 19        | 3.44%   |
| 6     | 9         | 1.63%   |
| 8     | 1         | 0.18%   |
| 7     | 1         | 0.18%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 130       | 16.58%  |
| Camera                   | 109       | 13.9%   |
| Bluetooth                | 105       | 13.39%  |
| Fingerprint reader       | 99        | 12.63%  |
| Graphics card            | 79        | 10.08%  |
| Chipcard                 | 59        | 7.53%   |
| Card reader              | 56        | 7.14%   |
| Multimedia controller    | 42        | 5.36%   |
| Net/wireless             | 39        | 4.97%   |
| Modem                    | 12        | 1.53%   |
| Sound                    | 10        | 1.28%   |
| Net/ethernet             | 10        | 1.28%   |
| Network                  | 8         | 1.02%   |
| Storage/ata              | 6         | 0.77%   |
| Storage                  | 5         | 0.64%   |
| Storage/ide              | 4         | 0.51%   |
| Firewire controller      | 4         | 0.51%   |
| Tv card                  | 2         | 0.26%   |
| Dvb card                 | 2         | 0.26%   |
| Wireless                 | 1         | 0.13%   |
| Storage/raid             | 1         | 0.13%   |
| Storage/nvme             | 1         | 0.13%   |

