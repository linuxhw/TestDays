Linux in Australia - Tested Hardware & Statistics
-------------------------------------------------

A project to collect tested hardware configurations for Linux in Australia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Australia/Desktop/README.md) and [notebooks](/Location/Australia/Notebook/README.md).

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

Total: 4937

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | 09M8Y8 A01                  | Desktop     | [17d5390549](https://linux-hardware.org/?probe=17d5390549) | Apr 01, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [7beef34820](https://linux-hardware.org/?probe=7beef34820) | Apr 01, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [8357ff8cf5](https://linux-hardware.org/?probe=8357ff8cf5) | Apr 01, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [89ca656f30](https://linux-hardware.org/?probe=89ca656f30) | Apr 01, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [2a881cc01e](https://linux-hardware.org/?probe=2a881cc01e) | Apr 01, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [2be0fa6524](https://linux-hardware.org/?probe=2be0fa6524) | Apr 01, 2023 |
| Lenovo        | ThinkStation D30 42234T7    | Desktop     | [47f6f4653b](https://linux-hardware.org/?probe=47f6f4653b) | Mar 31, 2023 |
| Unknown       | Unknown                     | Desktop     | [1f64d2db28](https://linux-hardware.org/?probe=1f64d2db28) | Mar 31, 2023 |
| ASRock        | FM2A55M-DGS                 | Desktop     | [3ab2e2c720](https://linux-hardware.org/?probe=3ab2e2c720) | Mar 31, 2023 |
| Gigabyte      | B85M-HD3                    | Desktop     | [3d24b75a10](https://linux-hardware.org/?probe=3d24b75a10) | Mar 31, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [05d42527df](https://linux-hardware.org/?probe=05d42527df) | Mar 31, 2023 |
| Dell          | 09M8Y8 A01                  | Desktop     | [2c13e40cd2](https://linux-hardware.org/?probe=2c13e40cd2) | Mar 30, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [92981c741d](https://linux-hardware.org/?probe=92981c741d) | Mar 30, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [af4901f141](https://linux-hardware.org/?probe=af4901f141) | Mar 30, 2023 |
| HP            | ProBook 450 G5              | Notebook    | [89dfecad7e](https://linux-hardware.org/?probe=89dfecad7e) | Mar 30, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [8d0c93e1a8](https://linux-hardware.org/?probe=8d0c93e1a8) | Mar 30, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [881f70cb12](https://linux-hardware.org/?probe=881f70cb12) | Mar 30, 2023 |
| Dell          | Precision 5550              | Notebook    | [c7244f1e31](https://linux-hardware.org/?probe=c7244f1e31) | Mar 30, 2023 |
| Dell          | G3 3590                     | Notebook    | [f61ce9bb82](https://linux-hardware.org/?probe=f61ce9bb82) | Mar 28, 2023 |
| Gigabyte      | H55M-USB3                   | Desktop     | [140b984b9f](https://linux-hardware.org/?probe=140b984b9f) | Mar 28, 2023 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [5064a5267e](https://linux-hardware.org/?probe=5064a5267e) | Mar 28, 2023 |
| MSI           | Delta 15 A5EFK              | Notebook    | [6f4e3ec28b](https://linux-hardware.org/?probe=6f4e3ec28b) | Mar 28, 2023 |
| MSI           | Delta 15 A5EFK              | Notebook    | [9dd1b67b2f](https://linux-hardware.org/?probe=9dd1b67b2f) | Mar 28, 2023 |
| Lenovo        | 0x36A017AA SDK0J40709 WI... | Desktop     | [562426633d](https://linux-hardware.org/?probe=562426633d) | Mar 28, 2023 |
| ASRock        | FM2A88X+ Killer             | Desktop     | [6180e562dd](https://linux-hardware.org/?probe=6180e562dd) | Mar 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [de6a63685a](https://linux-hardware.org/?probe=de6a63685a) | Mar 27, 2023 |
| Lenovo        | ThinkStation D30 42234T7    | Desktop     | [cfb8c9d396](https://linux-hardware.org/?probe=cfb8c9d396) | Mar 27, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [e67759f49b](https://linux-hardware.org/?probe=e67759f49b) | Mar 26, 2023 |
| HP            | 0B54h D                     | Desktop     | [540caaf04c](https://linux-hardware.org/?probe=540caaf04c) | Mar 26, 2023 |
| ASUSTek       | Maximus VIII HERO ALPHA     | Desktop     | [cc262bb41a](https://linux-hardware.org/?probe=cc262bb41a) | Mar 26, 2023 |
| ASRock        | AD525PV3                    | Desktop     | [84545fd0ea](https://linux-hardware.org/?probe=84545fd0ea) | Mar 25, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [8060aec150](https://linux-hardware.org/?probe=8060aec150) | Mar 25, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [5acd2b0492](https://linux-hardware.org/?probe=5acd2b0492) | Mar 25, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [5312ec3cc9](https://linux-hardware.org/?probe=5312ec3cc9) | Mar 25, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [1503a33123](https://linux-hardware.org/?probe=1503a33123) | Mar 24, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [9edd5002f0](https://linux-hardware.org/?probe=9edd5002f0) | Mar 24, 2023 |
| HP            | ProBook 470 G5              | Notebook    | [1672158957](https://linux-hardware.org/?probe=1672158957) | Mar 24, 2023 |
| HP            | ProBook 470 G5              | Notebook    | [383b333f72](https://linux-hardware.org/?probe=383b333f72) | Mar 24, 2023 |
| ReachingTe... | DreamQuest Pro 2022         | Mini pc     | [696a898cd2](https://linux-hardware.org/?probe=696a898cd2) | Mar 24, 2023 |
| ASRock        | AD525PV3                    | Desktop     | [0749ec7b44](https://linux-hardware.org/?probe=0749ec7b44) | Mar 23, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | Notebook    | [fc1c184c05](https://linux-hardware.org/?probe=fc1c184c05) | Mar 23, 2023 |
| AMI           | Intel                       | Desktop     | [5e7b21c227](https://linux-hardware.org/?probe=5e7b21c227) | Mar 23, 2023 |
| Acer          | ConceptD CN315-71P          | Notebook    | [14b71e7a26](https://linux-hardware.org/?probe=14b71e7a26) | Mar 22, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [10269c811b](https://linux-hardware.org/?probe=10269c811b) | Mar 22, 2023 |
| MSI           | MS-7142                     | Desktop     | [1cb67ac1ca](https://linux-hardware.org/?probe=1cb67ac1ca) | Mar 22, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [61025e6e8b](https://linux-hardware.org/?probe=61025e6e8b) | Mar 22, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [80d1a2d67d](https://linux-hardware.org/?probe=80d1a2d67d) | Mar 22, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [eb718edb23](https://linux-hardware.org/?probe=eb718edb23) | Mar 22, 2023 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [8c50d5ae87](https://linux-hardware.org/?probe=8c50d5ae87) | Mar 21, 2023 |
| Acer          | Spin SP314-54N              | Convertible | [4f2e83ab00](https://linux-hardware.org/?probe=4f2e83ab00) | Mar 21, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [a1e76aa5c1](https://linux-hardware.org/?probe=a1e76aa5c1) | Mar 21, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [16253cadcf](https://linux-hardware.org/?probe=16253cadcf) | Mar 21, 2023 |
| Dell          | Latitude E6520              | Notebook    | [857fdb4095](https://linux-hardware.org/?probe=857fdb4095) | Mar 21, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [c2191470c7](https://linux-hardware.org/?probe=c2191470c7) | Mar 21, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [6f98b39459](https://linux-hardware.org/?probe=6f98b39459) | Mar 21, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [c5c907b643](https://linux-hardware.org/?probe=c5c907b643) | Mar 21, 2023 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [ad4c43dd09](https://linux-hardware.org/?probe=ad4c43dd09) | Mar 21, 2023 |
| Apple         | Mac-F2208EC8                | Mini pc     | [4b47e3ed6c](https://linux-hardware.org/?probe=4b47e3ed6c) | Mar 20, 2023 |
| Gigabyte      | H610M H DDR4                | Desktop     | [b7cf9d91ee](https://linux-hardware.org/?probe=b7cf9d91ee) | Mar 20, 2023 |
| Acer          | Spin SP314-54N              | Convertible | [40d6f69489](https://linux-hardware.org/?probe=40d6f69489) | Mar 20, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [c63a27da32](https://linux-hardware.org/?probe=c63a27da32) | Mar 20, 2023 |
| ASUSTek       | Maximus Extreme             | Desktop     | [c6215ec2f3](https://linux-hardware.org/?probe=c6215ec2f3) | Mar 20, 2023 |
| ASUSTek       | PRIME B250M-K               | Desktop     | [99cb000a4e](https://linux-hardware.org/?probe=99cb000a4e) | Mar 19, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [67c8f562e5](https://linux-hardware.org/?probe=67c8f562e5) | Mar 18, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [dc411c9ce3](https://linux-hardware.org/?probe=dc411c9ce3) | Mar 18, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | Notebook    | [786fded1ce](https://linux-hardware.org/?probe=786fded1ce) | Mar 17, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [49bb337156](https://linux-hardware.org/?probe=49bb337156) | Mar 17, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [d762fe2bf3](https://linux-hardware.org/?probe=d762fe2bf3) | Mar 17, 2023 |
| Valve         | Jupiter                     | Notebook    | [8f51ab644e](https://linux-hardware.org/?probe=8f51ab644e) | Mar 17, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [b4483fd4e2](https://linux-hardware.org/?probe=b4483fd4e2) | Mar 16, 2023 |
| Dell          | G3 3590                     | Notebook    | [9ef42643d8](https://linux-hardware.org/?probe=9ef42643d8) | Mar 16, 2023 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [a4c449eef4](https://linux-hardware.org/?probe=a4c449eef4) | Mar 16, 2023 |
| HP            | ProBook 430 G8 Notebook ... | Notebook    | [ca6ab3c197](https://linux-hardware.org/?probe=ca6ab3c197) | Mar 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [684375b9a0](https://linux-hardware.org/?probe=684375b9a0) | Mar 16, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | Notebook    | [787dfaa7d4](https://linux-hardware.org/?probe=787dfaa7d4) | Mar 15, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [12e9972d5a](https://linux-hardware.org/?probe=12e9972d5a) | Mar 15, 2023 |
| Huanan        | X99-AD3 GAMING V2.0         | Desktop     | [0586633e29](https://linux-hardware.org/?probe=0586633e29) | Mar 15, 2023 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [b324afc6f8](https://linux-hardware.org/?probe=b324afc6f8) | Mar 14, 2023 |
| Intel         | DB85FL AAG89861-203         | Desktop     | [e17dae3447](https://linux-hardware.org/?probe=e17dae3447) | Mar 14, 2023 |
| Intel         | DB85FL AAG89861-203         | Desktop     | [f1004a32e1](https://linux-hardware.org/?probe=f1004a32e1) | Mar 14, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [59478f318e](https://linux-hardware.org/?probe=59478f318e) | Mar 14, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [954055245e](https://linux-hardware.org/?probe=954055245e) | Mar 14, 2023 |
| Dell          | Inspiron M5010              | Notebook    | [0a5d0c9169](https://linux-hardware.org/?probe=0a5d0c9169) | Mar 14, 2023 |
| QIYIDA        | X99-H9 V2.0                 | Desktop     | [0f440670f2](https://linux-hardware.org/?probe=0f440670f2) | Mar 14, 2023 |
| Acer          | Aspire E5-511               | Notebook    | [5343f73c67](https://linux-hardware.org/?probe=5343f73c67) | Mar 13, 2023 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [61af17e1cd](https://linux-hardware.org/?probe=61af17e1cd) | Mar 13, 2023 |
| Apple         | Mac-7BA5B2794B2CDB12 Mac... | Mini pc     | [cd75bab781](https://linux-hardware.org/?probe=cd75bab781) | Mar 13, 2023 |
| Fanless Mi... | Rev GMLR1                   | Mini pc     | [4ac1bccada](https://linux-hardware.org/?probe=4ac1bccada) | Mar 13, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | Notebook    | [b5d8bdc57d](https://linux-hardware.org/?probe=b5d8bdc57d) | Mar 12, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | Notebook    | [4525fa2931](https://linux-hardware.org/?probe=4525fa2931) | Mar 12, 2023 |
| Lenovo        | ThinkPad E590 20NBA000AU    | Notebook    | [47bfd44610](https://linux-hardware.org/?probe=47bfd44610) | Mar 12, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [e45386803e](https://linux-hardware.org/?probe=e45386803e) | Mar 12, 2023 |
| Gigabyte      | Z590I AORUS ULTRA           | Desktop     | [47ea9647d3](https://linux-hardware.org/?probe=47ea9647d3) | Mar 12, 2023 |
| Gigabyte      | X670E AORUS XTREME          | Desktop     | [83cb566647](https://linux-hardware.org/?probe=83cb566647) | Mar 12, 2023 |
| ASUSTek       | A88X-PLUS                   | Desktop     | [3624df5386](https://linux-hardware.org/?probe=3624df5386) | Mar 11, 2023 |
| Maibenben     | P748                        | Notebook    | [a44d1bb8e4](https://linux-hardware.org/?probe=a44d1bb8e4) | Mar 11, 2023 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [23b5dbe59d](https://linux-hardware.org/?probe=23b5dbe59d) | Mar 11, 2023 |
| ASRock        | 990FX Killer                | Desktop     | [23bd30e79e](https://linux-hardware.org/?probe=23bd30e79e) | Mar 11, 2023 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [46c1d399ac](https://linux-hardware.org/?probe=46c1d399ac) | Mar 11, 2023 |
| Gigabyte      | Z590 AORUS ELITE            | Desktop     | [790a51e99f](https://linux-hardware.org/?probe=790a51e99f) | Mar 11, 2023 |
| Acer          | Veriton X4640G V:1.1        | Desktop     | [dd3e15feee](https://linux-hardware.org/?probe=dd3e15feee) | Mar 10, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [35ab0f32c5](https://linux-hardware.org/?probe=35ab0f32c5) | Mar 10, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [9d14bee09f](https://linux-hardware.org/?probe=9d14bee09f) | Mar 10, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [e27d91ea6f](https://linux-hardware.org/?probe=e27d91ea6f) | Mar 09, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [790877da61](https://linux-hardware.org/?probe=790877da61) | Mar 09, 2023 |
| Lenovo        | ThinkPad L13 Yoga 20R6S1... | Convertible | [970e94ad07](https://linux-hardware.org/?probe=970e94ad07) | Mar 09, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [ded87de736](https://linux-hardware.org/?probe=ded87de736) | Mar 09, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [7413353e38](https://linux-hardware.org/?probe=7413353e38) | Mar 09, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [89647ee142](https://linux-hardware.org/?probe=89647ee142) | Mar 08, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [fd0eabacbf](https://linux-hardware.org/?probe=fd0eabacbf) | Mar 08, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [dfe7f75406](https://linux-hardware.org/?probe=dfe7f75406) | Mar 08, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [ffaa232ea2](https://linux-hardware.org/?probe=ffaa232ea2) | Mar 08, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [916862cd66](https://linux-hardware.org/?probe=916862cd66) | Mar 08, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | Notebook    | [54ad36532c](https://linux-hardware.org/?probe=54ad36532c) | Mar 07, 2023 |
| HP            | Stream Laptop 11-ah1XX      | Notebook    | [61e3840465](https://linux-hardware.org/?probe=61e3840465) | Mar 07, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [70eb1caef5](https://linux-hardware.org/?probe=70eb1caef5) | Mar 07, 2023 |
| HP            | Compaq Presario C700        | Notebook    | [fe1c136403](https://linux-hardware.org/?probe=fe1c136403) | Mar 06, 2023 |
| HP            | Compaq Presario C700        | Notebook    | [0b29805ec8](https://linux-hardware.org/?probe=0b29805ec8) | Mar 06, 2023 |
| HP            | ENVY 17                     | Notebook    | [ce2278a2e4](https://linux-hardware.org/?probe=ce2278a2e4) | Mar 05, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [dfc84acc1a](https://linux-hardware.org/?probe=dfc84acc1a) | Mar 05, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [3d1560d3d1](https://linux-hardware.org/?probe=3d1560d3d1) | Mar 05, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [7d1b3a73f9](https://linux-hardware.org/?probe=7d1b3a73f9) | Mar 05, 2023 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [9de6b65a45](https://linux-hardware.org/?probe=9de6b65a45) | Mar 04, 2023 |
| Google        | Ultima                      | Notebook    | [5e42f67839](https://linux-hardware.org/?probe=5e42f67839) | Mar 04, 2023 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [fca1ca2628](https://linux-hardware.org/?probe=fca1ca2628) | Mar 04, 2023 |
| SONIQ Digi... | Soniq 11.6inch Convertib... | Convertible | [e0b2fdc347](https://linux-hardware.org/?probe=e0b2fdc347) | Mar 04, 2023 |
| Valve         | Jupiter                     | Notebook    | [65a9e7ef52](https://linux-hardware.org/?probe=65a9e7ef52) | Mar 04, 2023 |
| Intel         | NUC12EDBi7 M27908-302       | Mini pc     | [bb51e864a7](https://linux-hardware.org/?probe=bb51e864a7) | Mar 03, 2023 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [3be3c8d79d](https://linux-hardware.org/?probe=3be3c8d79d) | Mar 03, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [906cb4b50a](https://linux-hardware.org/?probe=906cb4b50a) | Mar 03, 2023 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [f043beec18](https://linux-hardware.org/?probe=f043beec18) | Mar 03, 2023 |
| Dell          | 0KC9NP A00                  | Desktop     | [45397750b4](https://linux-hardware.org/?probe=45397750b4) | Mar 02, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [2173dea5df](https://linux-hardware.org/?probe=2173dea5df) | Mar 02, 2023 |
| Toshiba       | TECRA Z50-C                 | Notebook    | [c30ead38bd](https://linux-hardware.org/?probe=c30ead38bd) | Mar 02, 2023 |
| MSI           | PRO H610M-G DDR4            | Desktop     | [8ecbea06f8](https://linux-hardware.org/?probe=8ecbea06f8) | Mar 02, 2023 |
| Apple         | MacBookPro14,3              | Notebook    | [6f952b4c9b](https://linux-hardware.org/?probe=6f952b4c9b) | Mar 01, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [25c46b6f70](https://linux-hardware.org/?probe=25c46b6f70) | Mar 01, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [08346526f3](https://linux-hardware.org/?probe=08346526f3) | Mar 01, 2023 |
| Biostar       | B450MH                      | Desktop     | [aa05ee87d1](https://linux-hardware.org/?probe=aa05ee87d1) | Mar 01, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [131f94f213](https://linux-hardware.org/?probe=131f94f213) | Mar 01, 2023 |
| Intel Clie... | LAPRC510                    | Notebook    | [925c24b3db](https://linux-hardware.org/?probe=925c24b3db) | Feb 28, 2023 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [021853dafb](https://linux-hardware.org/?probe=021853dafb) | Feb 28, 2023 |
| Intel Clie... | LAPRC510                    | Notebook    | [6d9a8edb0c](https://linux-hardware.org/?probe=6d9a8edb0c) | Feb 28, 2023 |
| Dell          | 0XHGV1 A00                  | Desktop     | [75249be116](https://linux-hardware.org/?probe=75249be116) | Feb 27, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [816a4eb27e](https://linux-hardware.org/?probe=816a4eb27e) | Feb 26, 2023 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [b27fb5e204](https://linux-hardware.org/?probe=b27fb5e204) | Feb 26, 2023 |
| Pegatron      | 2ACB                        | Desktop     | [13355a7d07](https://linux-hardware.org/?probe=13355a7d07) | Feb 26, 2023 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [a2356a66ba](https://linux-hardware.org/?probe=a2356a66ba) | Feb 26, 2023 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [ce67684fdf](https://linux-hardware.org/?probe=ce67684fdf) | Feb 26, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [7f2823a756](https://linux-hardware.org/?probe=7f2823a756) | Feb 26, 2023 |
| HP            | 0AECh D                     | Desktop     | [5baf25e8af](https://linux-hardware.org/?probe=5baf25e8af) | Feb 26, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [0b1c4036b1](https://linux-hardware.org/?probe=0b1c4036b1) | Feb 26, 2023 |
| HP            | Notebook                    | Notebook    | [4a72575c17](https://linux-hardware.org/?probe=4a72575c17) | Feb 25, 2023 |
| Medion        | MAG Z390M MORTAR            | Desktop     | [e2445cf24c](https://linux-hardware.org/?probe=e2445cf24c) | Feb 25, 2023 |
| Toshiba       | Satellite C850              | Notebook    | [99d4efbb52](https://linux-hardware.org/?probe=99d4efbb52) | Feb 25, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [4a0d65f6b5](https://linux-hardware.org/?probe=4a0d65f6b5) | Feb 24, 2023 |
| Gigabyte      | Z77M-D3H-MVP                | Desktop     | [e27e1cd0e8](https://linux-hardware.org/?probe=e27e1cd0e8) | Feb 24, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [72e11db1c0](https://linux-hardware.org/?probe=72e11db1c0) | Feb 24, 2023 |
| MSI           | Vector GP66 12UEO           | Notebook    | [9b6bf9479e](https://linux-hardware.org/?probe=9b6bf9479e) | Feb 24, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [ea2663126f](https://linux-hardware.org/?probe=ea2663126f) | Feb 24, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [8a09d5e812](https://linux-hardware.org/?probe=8a09d5e812) | Feb 23, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [e386073c5d](https://linux-hardware.org/?probe=e386073c5d) | Feb 23, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [d65a9c975d](https://linux-hardware.org/?probe=d65a9c975d) | Feb 23, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | Notebook    | [fa9427d71f](https://linux-hardware.org/?probe=fa9427d71f) | Feb 22, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [2d36b57c9c](https://linux-hardware.org/?probe=2d36b57c9c) | Feb 22, 2023 |
| Lenovo        | ThinkPad X131e 3367AH5      | Notebook    | [3c1cec4c1c](https://linux-hardware.org/?probe=3c1cec4c1c) | Feb 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [8110c575e9](https://linux-hardware.org/?probe=8110c575e9) | Feb 22, 2023 |
| Acer          | TravelMate 8572T            | Notebook    | [20d7321f8f](https://linux-hardware.org/?probe=20d7321f8f) | Feb 21, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [e293e73518](https://linux-hardware.org/?probe=e293e73518) | Feb 21, 2023 |
| MSI           | B550 GAMING GEN3            | Desktop     | [d92a4239ee](https://linux-hardware.org/?probe=d92a4239ee) | Feb 21, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [edd5640ca7](https://linux-hardware.org/?probe=edd5640ca7) | Feb 21, 2023 |
| Dell          | Latitude 5430               | Notebook    | [69fd82c453](https://linux-hardware.org/?probe=69fd82c453) | Feb 21, 2023 |
| Acer          | Aspire X3950                | Desktop     | [f5b4a3baa3](https://linux-hardware.org/?probe=f5b4a3baa3) | Feb 20, 2023 |
| Dell          | Latitude E6430              | Notebook    | [42750c43b5](https://linux-hardware.org/?probe=42750c43b5) | Feb 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [2cc51656a5](https://linux-hardware.org/?probe=2cc51656a5) | Feb 20, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [f8a26128a4](https://linux-hardware.org/?probe=f8a26128a4) | Feb 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [d4663db4e0](https://linux-hardware.org/?probe=d4663db4e0) | Feb 19, 2023 |
| AZW           | GTi                         | Desktop     | [17bb698441](https://linux-hardware.org/?probe=17bb698441) | Feb 19, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [ca676dc566](https://linux-hardware.org/?probe=ca676dc566) | Feb 19, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [9b0ecbd3c7](https://linux-hardware.org/?probe=9b0ecbd3c7) | Feb 19, 2023 |
| Gigabyte      | Z590I AORUS ULTRA           | Desktop     | [9805ab5764](https://linux-hardware.org/?probe=9805ab5764) | Feb 19, 2023 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [aa49c18960](https://linux-hardware.org/?probe=aa49c18960) | Feb 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [0365a40dd4](https://linux-hardware.org/?probe=0365a40dd4) | Feb 18, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | Notebook    | [cc44156b99](https://linux-hardware.org/?probe=cc44156b99) | Feb 17, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | Notebook    | [bc234d0b32](https://linux-hardware.org/?probe=bc234d0b32) | Feb 17, 2023 |
| Toshiba       | Satellite P750              | Notebook    | [6f5f99b514](https://linux-hardware.org/?probe=6f5f99b514) | Feb 16, 2023 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [68f0415788](https://linux-hardware.org/?probe=68f0415788) | Feb 16, 2023 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [2560ba7644](https://linux-hardware.org/?probe=2560ba7644) | Feb 16, 2023 |
| Raspberry ... | Raspberry Pi Model B Plu... | Soc         | [65c778e356](https://linux-hardware.org/?probe=65c778e356) | Feb 16, 2023 |
| ASRock        | Z77 Extreme6                | Desktop     | [48328ab864](https://linux-hardware.org/?probe=48328ab864) | Feb 15, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [8f5697ea3a](https://linux-hardware.org/?probe=8f5697ea3a) | Feb 15, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [f12f20217b](https://linux-hardware.org/?probe=f12f20217b) | Feb 15, 2023 |
| ASUSTek       | V-P7H55E                    | Desktop     | [27ddce20a1](https://linux-hardware.org/?probe=27ddce20a1) | Feb 15, 2023 |
| Gigabyte      | H410M DS2V                  | Desktop     | [b2e8c15dc4](https://linux-hardware.org/?probe=b2e8c15dc4) | Feb 15, 2023 |
| Dell          | 09M8Y8 A01                  | Desktop     | [beabc46f67](https://linux-hardware.org/?probe=beabc46f67) | Feb 14, 2023 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [f298c1fc7e](https://linux-hardware.org/?probe=f298c1fc7e) | Feb 14, 2023 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [45cfd72091](https://linux-hardware.org/?probe=45cfd72091) | Feb 14, 2023 |
| Dell          | 09M8Y8 A01                  | Desktop     | [fb1ff4a6d9](https://linux-hardware.org/?probe=fb1ff4a6d9) | Feb 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [1a20fdd090](https://linux-hardware.org/?probe=1a20fdd090) | Feb 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [3384ced1ca](https://linux-hardware.org/?probe=3384ced1ca) | Feb 14, 2023 |
| MSI           | Vector GP66 12UEO           | Notebook    | [040bddeff8](https://linux-hardware.org/?probe=040bddeff8) | Feb 14, 2023 |
| Gigabyte      | Z68X-UD3H-B3                | Desktop     | [0ad0fe310f](https://linux-hardware.org/?probe=0ad0fe310f) | Feb 14, 2023 |
| HP            | Compaq nc6400 (RM741PA#A... | Notebook    | [d556bf453d](https://linux-hardware.org/?probe=d556bf453d) | Feb 13, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [b563d8f052](https://linux-hardware.org/?probe=b563d8f052) | Feb 13, 2023 |
| ASUSTek       | K45VS                       | Notebook    | [faf4fc0251](https://linux-hardware.org/?probe=faf4fc0251) | Feb 12, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [219157717b](https://linux-hardware.org/?probe=219157717b) | Feb 12, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [cdc63fb05e](https://linux-hardware.org/?probe=cdc63fb05e) | Feb 12, 2023 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [7fec987264](https://linux-hardware.org/?probe=7fec987264) | Feb 12, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [72b0ba099a](https://linux-hardware.org/?probe=72b0ba099a) | Feb 11, 2023 |
| Acer          | Aspire One 753              | Notebook    | [b3ef912b35](https://linux-hardware.org/?probe=b3ef912b35) | Feb 10, 2023 |
| Dell          | G15 5520                    | Notebook    | [121b06f3cc](https://linux-hardware.org/?probe=121b06f3cc) | Feb 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | Notebook    | [e3ea6ad8da](https://linux-hardware.org/?probe=e3ea6ad8da) | Feb 10, 2023 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [99dda6c06c](https://linux-hardware.org/?probe=99dda6c06c) | Feb 09, 2023 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [30363b3a5d](https://linux-hardware.org/?probe=30363b3a5d) | Feb 09, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [fff70a8d2c](https://linux-hardware.org/?probe=fff70a8d2c) | Feb 09, 2023 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | Notebook    | [b79b2f3f75](https://linux-hardware.org/?probe=b79b2f3f75) | Feb 09, 2023 |
| Intel         | LADPNVMO AAE76523-300       | Desktop     | [6ced92edc7](https://linux-hardware.org/?probe=6ced92edc7) | Feb 09, 2023 |
| ASUSTek       | ZenBook UX463FA_UX463FA     | Convertible | [e43aebc69d](https://linux-hardware.org/?probe=e43aebc69d) | Feb 08, 2023 |
| Dell          | G15 5520                    | Notebook    | [7f4d36cea1](https://linux-hardware.org/?probe=7f4d36cea1) | Feb 08, 2023 |
| ASUSTek       | P5Q3 DELUXE                 | Desktop     | [16c72d3532](https://linux-hardware.org/?probe=16c72d3532) | Feb 08, 2023 |
| Alienware     | m15 R7                      | Notebook    | [254ab40fcf](https://linux-hardware.org/?probe=254ab40fcf) | Feb 07, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [0f4be18646](https://linux-hardware.org/?probe=0f4be18646) | Feb 07, 2023 |
| HP            | 0AA0h                       | Desktop     | [921b7f0d0c](https://linux-hardware.org/?probe=921b7f0d0c) | Feb 07, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [4a647dd6b9](https://linux-hardware.org/?probe=4a647dd6b9) | Feb 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [8b26ec07a6](https://linux-hardware.org/?probe=8b26ec07a6) | Feb 07, 2023 |
| Acer          | Aspire E3-111               | Notebook    | [a7c14e51ff](https://linux-hardware.org/?probe=a7c14e51ff) | Feb 06, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [99d0ce5421](https://linux-hardware.org/?probe=99d0ce5421) | Feb 05, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [2f0810d441](https://linux-hardware.org/?probe=2f0810d441) | Feb 05, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [a0fc4f78ea](https://linux-hardware.org/?probe=a0fc4f78ea) | Feb 05, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [5a7ae4b151](https://linux-hardware.org/?probe=5a7ae4b151) | Feb 05, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [2b9cb5eea6](https://linux-hardware.org/?probe=2b9cb5eea6) | Feb 05, 2023 |
| Intel         | X99                         | Desktop     | [e8790caf8d](https://linux-hardware.org/?probe=e8790caf8d) | Feb 05, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [0eb4367fb4](https://linux-hardware.org/?probe=0eb4367fb4) | Feb 04, 2023 |
| ASUSTek       | X550LC                      | Notebook    | [f22682c35f](https://linux-hardware.org/?probe=f22682c35f) | Feb 04, 2023 |
| Toshiba       | Satellite P500              | Notebook    | [78ebd7c272](https://linux-hardware.org/?probe=78ebd7c272) | Feb 04, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [a17959ea9b](https://linux-hardware.org/?probe=a17959ea9b) | Feb 04, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [38625b9f02](https://linux-hardware.org/?probe=38625b9f02) | Feb 03, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [6ffe048ee2](https://linux-hardware.org/?probe=6ffe048ee2) | Feb 03, 2023 |
| Acer          | Aspire XC-603               | Desktop     | [fff64928e8](https://linux-hardware.org/?probe=fff64928e8) | Feb 03, 2023 |
| Acer          | Aspire XC-603               | Desktop     | [2cd1d2f51f](https://linux-hardware.org/?probe=2cd1d2f51f) | Feb 03, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [13bdc2b06c](https://linux-hardware.org/?probe=13bdc2b06c) | Feb 03, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [866e97ab12](https://linux-hardware.org/?probe=866e97ab12) | Feb 03, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [9cabffbc86](https://linux-hardware.org/?probe=9cabffbc86) | Feb 03, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [17b77b89e5](https://linux-hardware.org/?probe=17b77b89e5) | Feb 03, 2023 |
| Lenovo        | ThinkPad T420s 4173CTO      | Notebook    | [232ff7a382](https://linux-hardware.org/?probe=232ff7a382) | Feb 02, 2023 |
| HP            | 212B                        | Desktop     | [cb1e6fa666](https://linux-hardware.org/?probe=cb1e6fa666) | Feb 02, 2023 |
| HP            | 212B                        | Desktop     | [e3e8d72420](https://linux-hardware.org/?probe=e3e8d72420) | Feb 02, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [687b1ec2d7](https://linux-hardware.org/?probe=687b1ec2d7) | Feb 02, 2023 |
| Dell          | Latitude 7320 Detachable    | Tablet      | [7560429d05](https://linux-hardware.org/?probe=7560429d05) | Feb 02, 2023 |
| Gigabyte      | Z77M-D3H-MVP                | Desktop     | [9b2f47d039](https://linux-hardware.org/?probe=9b2f47d039) | Feb 02, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [c7b6222f08](https://linux-hardware.org/?probe=c7b6222f08) | Feb 02, 2023 |
| Dell          | Latitude E6520              | Notebook    | [548b13cd43](https://linux-hardware.org/?probe=548b13cd43) | Feb 02, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [465114aa14](https://linux-hardware.org/?probe=465114aa14) | Feb 01, 2023 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [b0697611f6](https://linux-hardware.org/?probe=b0697611f6) | Feb 01, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [99127d4bed](https://linux-hardware.org/?probe=99127d4bed) | Feb 01, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [b1c77eb9c7](https://linux-hardware.org/?probe=b1c77eb9c7) | Jan 31, 2023 |
| ASRock        | AD2700-ITX                  | Desktop     | [2f14c18867](https://linux-hardware.org/?probe=2f14c18867) | Jan 31, 2023 |
| Acer          | MCP73VE NVIDIA MCP73        | Desktop     | [840102fa91](https://linux-hardware.org/?probe=840102fa91) | Jan 31, 2023 |
| ASUSTek       | X550LC                      | Notebook    | [4c50999862](https://linux-hardware.org/?probe=4c50999862) | Jan 30, 2023 |
| ASUSTek       | X550LC                      | Notebook    | [41d606bbe8](https://linux-hardware.org/?probe=41d606bbe8) | Jan 30, 2023 |
| Dell          | 0D6H9T A00                  | Desktop     | [2c34aba28a](https://linux-hardware.org/?probe=2c34aba28a) | Jan 30, 2023 |
| Dell          | Inspiron 5770               | Notebook    | [b5612c2501](https://linux-hardware.org/?probe=b5612c2501) | Jan 29, 2023 |
| Dell          | Latitude 5400               | Notebook    | [80651273e4](https://linux-hardware.org/?probe=80651273e4) | Jan 29, 2023 |
| Dell          | Latitude 5400               | Notebook    | [eb97e73f08](https://linux-hardware.org/?probe=eb97e73f08) | Jan 29, 2023 |
| ASUSTek       | PRIME B560M-K               | Desktop     | [c74b6b90f0](https://linux-hardware.org/?probe=c74b6b90f0) | Jan 28, 2023 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [684748c9b4](https://linux-hardware.org/?probe=684748c9b4) | Jan 28, 2023 |
| MSI           | TRX40 PRO WIFI              | Desktop     | [d9508d5b22](https://linux-hardware.org/?probe=d9508d5b22) | Jan 27, 2023 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [06086e6112](https://linux-hardware.org/?probe=06086e6112) | Jan 27, 2023 |
| Apple         | MacBook8,1                  | Notebook    | [02cd28549c](https://linux-hardware.org/?probe=02cd28549c) | Jan 27, 2023 |
| ASRock        | AD2700-ITX                  | Desktop     | [7b711bee4f](https://linux-hardware.org/?probe=7b711bee4f) | Jan 26, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [4213c95d3d](https://linux-hardware.org/?probe=4213c95d3d) | Jan 26, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [b44aa465bc](https://linux-hardware.org/?probe=b44aa465bc) | Jan 26, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [fab7cead8c](https://linux-hardware.org/?probe=fab7cead8c) | Jan 26, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 D... | Notebook    | [d2a46bd14a](https://linux-hardware.org/?probe=d2a46bd14a) | Jan 26, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [b7759508d9](https://linux-hardware.org/?probe=b7759508d9) | Jan 26, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [72f2c3fddc](https://linux-hardware.org/?probe=72f2c3fddc) | Jan 26, 2023 |
| Panasonic     | FZ55-2                      | Notebook    | [dd9ddb12b6](https://linux-hardware.org/?probe=dd9ddb12b6) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [26abf66da5](https://linux-hardware.org/?probe=26abf66da5) | Jan 25, 2023 |
| Acer          | Aspire A315-22              | Notebook    | [7c048a8058](https://linux-hardware.org/?probe=7c048a8058) | Jan 24, 2023 |
| MeLE          | Rev GMLR1                   | Mini pc     | [1f294d6a67](https://linux-hardware.org/?probe=1f294d6a67) | Jan 24, 2023 |
| Pegatron      | 2AEE                        | Desktop     | [1c59133176](https://linux-hardware.org/?probe=1c59133176) | Jan 24, 2023 |
| ASUSTek       | PRIME Z690-A                | Desktop     | [ea5c2d01c2](https://linux-hardware.org/?probe=ea5c2d01c2) | Jan 24, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [c2226035ce](https://linux-hardware.org/?probe=c2226035ce) | Jan 24, 2023 |
| Dell          | 0X2MKR A00                  | All in one  | [5b29ed7213](https://linux-hardware.org/?probe=5b29ed7213) | Jan 23, 2023 |
| HP            | 8860 A                      | Desktop     | [ffb17b2c42](https://linux-hardware.org/?probe=ffb17b2c42) | Jan 23, 2023 |
| Alienware     | 15 R4                       | Notebook    | [8833335118](https://linux-hardware.org/?probe=8833335118) | Jan 23, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [447e624609](https://linux-hardware.org/?probe=447e624609) | Jan 22, 2023 |
| ASUSTek       | Z87-EXPERT                  | Desktop     | [852add0d4b](https://linux-hardware.org/?probe=852add0d4b) | Jan 22, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [223ab1f016](https://linux-hardware.org/?probe=223ab1f016) | Jan 22, 2023 |
| Lenovo        | ThinkPad X250 20CLS2JV01    | Notebook    | [932148f478](https://linux-hardware.org/?probe=932148f478) | Jan 21, 2023 |
| Intel         | NUC11ATBPE M49844-202       | Mini pc     | [74d7964357](https://linux-hardware.org/?probe=74d7964357) | Jan 21, 2023 |
| Dell          | XPS 9315                    | Notebook    | [9dfb19b7c1](https://linux-hardware.org/?probe=9dfb19b7c1) | Jan 21, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [46a3691da9](https://linux-hardware.org/?probe=46a3691da9) | Jan 21, 2023 |
| Dell          | Latitude 5300               | Notebook    | [e8c4218110](https://linux-hardware.org/?probe=e8c4218110) | Jan 21, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [bd601f83d3](https://linux-hardware.org/?probe=bd601f83d3) | Jan 21, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [28b4d041ad](https://linux-hardware.org/?probe=28b4d041ad) | Jan 20, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [1b41330a7e](https://linux-hardware.org/?probe=1b41330a7e) | Jan 20, 2023 |
| ASUSTek       | Z87-EXPERT                  | Desktop     | [ff72c387c7](https://linux-hardware.org/?probe=ff72c387c7) | Jan 20, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [ead0a07135](https://linux-hardware.org/?probe=ead0a07135) | Jan 20, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [1a80b30106](https://linux-hardware.org/?probe=1a80b30106) | Jan 20, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [03e73c44b7](https://linux-hardware.org/?probe=03e73c44b7) | Jan 20, 2023 |
| Apple         | MacBookPro14,3              | Notebook    | [82a49878eb](https://linux-hardware.org/?probe=82a49878eb) | Jan 19, 2023 |
| ASUSTek       | Z87-EXPERT                  | Desktop     | [91a963e420](https://linux-hardware.org/?probe=91a963e420) | Jan 19, 2023 |
| AZW           | SER V01                     | Mini pc     | [b209807db5](https://linux-hardware.org/?probe=b209807db5) | Jan 19, 2023 |
| ASUSTek       | PRIME Z690-A                | Desktop     | [ed9e94399a](https://linux-hardware.org/?probe=ed9e94399a) | Jan 18, 2023 |
| Lenovo        | 0B98401 WIN                 | Desktop     | [8d4e5b4499](https://linux-hardware.org/?probe=8d4e5b4499) | Jan 18, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [9a7659a260](https://linux-hardware.org/?probe=9a7659a260) | Jan 18, 2023 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [c7f31be903](https://linux-hardware.org/?probe=c7f31be903) | Jan 18, 2023 |
| Gigabyte      | B650M GAMING X AX           | Desktop     | [fb01eafa41](https://linux-hardware.org/?probe=fb01eafa41) | Jan 18, 2023 |
| Dell          | Precision 3561              | Notebook    | [9528d74be6](https://linux-hardware.org/?probe=9528d74be6) | Jan 18, 2023 |
| Dell          | Precision 3561              | Notebook    | [5f23addbde](https://linux-hardware.org/?probe=5f23addbde) | Jan 18, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [16be0552b2](https://linux-hardware.org/?probe=16be0552b2) | Jan 17, 2023 |
| Lenovo        | ThinkPad X230 2325CW1       | Notebook    | [44a8ae0b56](https://linux-hardware.org/?probe=44a8ae0b56) | Jan 17, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [d87fb3cf65](https://linux-hardware.org/?probe=d87fb3cf65) | Jan 17, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [564482477e](https://linux-hardware.org/?probe=564482477e) | Jan 17, 2023 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [0d7c3e0009](https://linux-hardware.org/?probe=0d7c3e0009) | Jan 17, 2023 |
| Dell          | 075CGM A00                  | Mini pc     | [5df3707c20](https://linux-hardware.org/?probe=5df3707c20) | Jan 17, 2023 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [a80f36a4eb](https://linux-hardware.org/?probe=a80f36a4eb) | Jan 16, 2023 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [f0b2886993](https://linux-hardware.org/?probe=f0b2886993) | Jan 15, 2023 |
| HP            | ProLiant DL380 G6           | Server      | [73b5a8c763](https://linux-hardware.org/?probe=73b5a8c763) | Jan 15, 2023 |
| Acer          | Aspire R3-131T              | Notebook    | [268413b274](https://linux-hardware.org/?probe=268413b274) | Jan 15, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [ab5933911d](https://linux-hardware.org/?probe=ab5933911d) | Jan 15, 2023 |
| Valve         | Jupiter                     | Notebook    | [8830efc64d](https://linux-hardware.org/?probe=8830efc64d) | Jan 15, 2023 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [6efb68b8da](https://linux-hardware.org/?probe=6efb68b8da) | Jan 14, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [dc3317fe82](https://linux-hardware.org/?probe=dc3317fe82) | Jan 14, 2023 |
| ASUSTek       | GL10DH                      | Desktop     | [c1f3c3b1c4](https://linux-hardware.org/?probe=c1f3c3b1c4) | Jan 14, 2023 |
| ASUSTek       | TUF Gaming B660M-E D4       | Desktop     | [79753b9bcd](https://linux-hardware.org/?probe=79753b9bcd) | Jan 14, 2023 |
| Pegatron      | 2ACB                        | Desktop     | [6a129c6fde](https://linux-hardware.org/?probe=6a129c6fde) | Jan 13, 2023 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [3837db6f8a](https://linux-hardware.org/?probe=3837db6f8a) | Jan 13, 2023 |
| ASUSTek       | Z170-DELUXE                 | Desktop     | [433bc4fddd](https://linux-hardware.org/?probe=433bc4fddd) | Jan 13, 2023 |
| Intel Clie... | LAPBC510                    | Notebook    | [493f0e9608](https://linux-hardware.org/?probe=493f0e9608) | Jan 13, 2023 |
| Dell          | Latitude 5300               | Notebook    | [148745c883](https://linux-hardware.org/?probe=148745c883) | Jan 13, 2023 |
| Intel Clie... | LAPBC510                    | Notebook    | [ac0b81bf2e](https://linux-hardware.org/?probe=ac0b81bf2e) | Jan 13, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [c6a710b940](https://linux-hardware.org/?probe=c6a710b940) | Jan 13, 2023 |
| ASUSTek       | Z87-EXPERT                  | Desktop     | [7c8a02d00a](https://linux-hardware.org/?probe=7c8a02d00a) | Jan 13, 2023 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [252041601b](https://linux-hardware.org/?probe=252041601b) | Jan 12, 2023 |
| Dell          | Inspiron 5770               | Notebook    | [7435d85aca](https://linux-hardware.org/?probe=7435d85aca) | Jan 12, 2023 |
| Dell          | XPS 17 9700                 | Notebook    | [09f6a754d6](https://linux-hardware.org/?probe=09f6a754d6) | Jan 12, 2023 |
| Dell          | 09KPNV A00                  | Desktop     | [1859af08ff](https://linux-hardware.org/?probe=1859af08ff) | Jan 11, 2023 |
| Acer          | Swift SF514-54T             | Notebook    | [98a18475e8](https://linux-hardware.org/?probe=98a18475e8) | Jan 11, 2023 |
| ASUSTek       | H87-PRO                     | Desktop     | [4ac36f25a9](https://linux-hardware.org/?probe=4ac36f25a9) | Jan 11, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [511306775e](https://linux-hardware.org/?probe=511306775e) | Jan 11, 2023 |
| Dell          | Inspiron 3543               | Notebook    | [c7c7419fd5](https://linux-hardware.org/?probe=c7c7419fd5) | Jan 10, 2023 |
| Gigabyte      | H97M-Gaming 3               | Desktop     | [22ee51c3f8](https://linux-hardware.org/?probe=22ee51c3f8) | Jan 10, 2023 |
| HP            | 2179                        | Desktop     | [ad75cc2104](https://linux-hardware.org/?probe=ad75cc2104) | Jan 10, 2023 |
| ReachingTe... | DreamQuest Pro 2022         | Mini pc     | [06eee6367f](https://linux-hardware.org/?probe=06eee6367f) | Jan 10, 2023 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [17dc10d7bb](https://linux-hardware.org/?probe=17dc10d7bb) | Jan 10, 2023 |
| Intel         | NUC10i7FNB K61360-306       | Mini pc     | [f03ae5d905](https://linux-hardware.org/?probe=f03ae5d905) | Jan 10, 2023 |
| Intel         | NUC10i7FNB K61360-306       | Mini pc     | [9645ad91cc](https://linux-hardware.org/?probe=9645ad91cc) | Jan 10, 2023 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [5656924057](https://linux-hardware.org/?probe=5656924057) | Jan 10, 2023 |
| SYWZ          | S210HA Series               | Desktop     | [0cabf3b51e](https://linux-hardware.org/?probe=0cabf3b51e) | Jan 09, 2023 |
| Lenovo        | ThinkPad T430s 2356AF9      | Notebook    | [eca34fb600](https://linux-hardware.org/?probe=eca34fb600) | Jan 09, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [29ac3deef8](https://linux-hardware.org/?probe=29ac3deef8) | Jan 09, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [95cfb68187](https://linux-hardware.org/?probe=95cfb68187) | Jan 09, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [e336a260d6](https://linux-hardware.org/?probe=e336a260d6) | Jan 09, 2023 |
| Gigabyte      | B560M DS3H AC               | Desktop     | [3b4f027444](https://linux-hardware.org/?probe=3b4f027444) | Jan 09, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [43cc06ef1d](https://linux-hardware.org/?probe=43cc06ef1d) | Jan 09, 2023 |
| Dell          | XPS 13 9333                 | Notebook    | [f291c4d057](https://linux-hardware.org/?probe=f291c4d057) | Jan 09, 2023 |
| MSI           | PRO B550M-P GEN3            | Desktop     | [5b62f9f024](https://linux-hardware.org/?probe=5b62f9f024) | Jan 09, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [1c4f7f2f2a](https://linux-hardware.org/?probe=1c4f7f2f2a) | Jan 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [36ed66f057](https://linux-hardware.org/?probe=36ed66f057) | Jan 08, 2023 |
| Dell          | Latitude 7280               | Notebook    | [931dcfb8be](https://linux-hardware.org/?probe=931dcfb8be) | Jan 08, 2023 |
| Dell          | Latitude E7450              | Notebook    | [635ef7be4a](https://linux-hardware.org/?probe=635ef7be4a) | Jan 08, 2023 |
| Lenovo        | ThinkPad W530 2463B87       | Notebook    | [5ac9828d4c](https://linux-hardware.org/?probe=5ac9828d4c) | Jan 08, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [b4c192526f](https://linux-hardware.org/?probe=b4c192526f) | Jan 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [8df8f7c51f](https://linux-hardware.org/?probe=8df8f7c51f) | Jan 07, 2023 |
| Acer          | Veriton N4640G              | Desktop     | [3392dd3c90](https://linux-hardware.org/?probe=3392dd3c90) | Jan 07, 2023 |
| Acer          | Predator G9-793             | Notebook    | [5256ec6943](https://linux-hardware.org/?probe=5256ec6943) | Jan 07, 2023 |
| Lenovo        | ThinkPad Helix 2nd 20CHS... | Tablet      | [e6190d3469](https://linux-hardware.org/?probe=e6190d3469) | Jan 07, 2023 |
| HP            | 212A                        | Desktop     | [21acb67653](https://linux-hardware.org/?probe=21acb67653) | Jan 06, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [67f40c78ec](https://linux-hardware.org/?probe=67f40c78ec) | Jan 06, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [58f2e834d8](https://linux-hardware.org/?probe=58f2e834d8) | Jan 06, 2023 |
| GPU Compan... | GWTN156-2BK                 | Notebook    | [263354b92e](https://linux-hardware.org/?probe=263354b92e) | Jan 06, 2023 |
| Dell          | Precision M4700             | Notebook    | [414d8c4701](https://linux-hardware.org/?probe=414d8c4701) | Jan 06, 2023 |
| HP            | 1905                        | Desktop     | [01fb70526d](https://linux-hardware.org/?probe=01fb70526d) | Jan 06, 2023 |
| GPU Compan... | GWTN156-2BK                 | Notebook    | [99bf8fff2f](https://linux-hardware.org/?probe=99bf8fff2f) | Jan 06, 2023 |
| GPU Compan... | GWTN156-2BK                 | Notebook    | [d9fa2355b0](https://linux-hardware.org/?probe=d9fa2355b0) | Jan 05, 2023 |
| HP            | 821D                        | Desktop     | [d859c928b8](https://linux-hardware.org/?probe=d859c928b8) | Jan 05, 2023 |
| ASRock        | H310M-HDV/M.2               | Desktop     | [cf98b88234](https://linux-hardware.org/?probe=cf98b88234) | Jan 05, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [88ea27e220](https://linux-hardware.org/?probe=88ea27e220) | Jan 04, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [02b3cbc8c6](https://linux-hardware.org/?probe=02b3cbc8c6) | Jan 04, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [ad776cdf84](https://linux-hardware.org/?probe=ad776cdf84) | Jan 04, 2023 |
| Dell          | 0RRXFP A00                  | All in one  | [38be4b535f](https://linux-hardware.org/?probe=38be4b535f) | Jan 04, 2023 |
| Intel         | NUC13SBBi9 M58736-302       | Mini pc     | [f30031a156](https://linux-hardware.org/?probe=f30031a156) | Jan 04, 2023 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [488e1f656c](https://linux-hardware.org/?probe=488e1f656c) | Jan 03, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [c2c723d7b2](https://linux-hardware.org/?probe=c2c723d7b2) | Jan 03, 2023 |
| Gigabyte      | X58A-UD7                    | Desktop     | [5b07c849cc](https://linux-hardware.org/?probe=5b07c849cc) | Jan 03, 2023 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [d0ac402ed9](https://linux-hardware.org/?probe=d0ac402ed9) | Jan 03, 2023 |
| HP            | Pavilion                    | Notebook    | [466e855af1](https://linux-hardware.org/?probe=466e855af1) | Jan 03, 2023 |
| Lenovo        | ThinkPad X260 20F5005NAU    | Notebook    | [3f68b8438c](https://linux-hardware.org/?probe=3f68b8438c) | Jan 02, 2023 |
| Intel         | NUC6i7KYB H90766-404        | Mini pc     | [961f0cc73a](https://linux-hardware.org/?probe=961f0cc73a) | Jan 02, 2023 |
| Gigabyte      | Z68X-UD3H-B3                | Desktop     | [1de40c1ae3](https://linux-hardware.org/?probe=1de40c1ae3) | Jan 02, 2023 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [752fe53b7c](https://linux-hardware.org/?probe=752fe53b7c) | Jan 01, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [13ae6c7e25](https://linux-hardware.org/?probe=13ae6c7e25) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [28f9b91b32](https://linux-hardware.org/?probe=28f9b91b32) | Jan 01, 2023 |
| HP            | EliteBook 2760p             | Notebook    | [91741e63eb](https://linux-hardware.org/?probe=91741e63eb) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [6b98637c82](https://linux-hardware.org/?probe=6b98637c82) | Jan 01, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJ00... | Convertible | [1e4997593d](https://linux-hardware.org/?probe=1e4997593d) | Jan 01, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJ00... | Convertible | [99d2f193c4](https://linux-hardware.org/?probe=99d2f193c4) | Jan 01, 2023 |
| ASUSTek       | H87-PRO                     | Desktop     | [f95906c714](https://linux-hardware.org/?probe=f95906c714) | Jan 01, 2023 |
| HP            | EliteBook 2760p             | Notebook    | [6ac462efda](https://linux-hardware.org/?probe=6ac462efda) | Jan 01, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [cf40d3f30c](https://linux-hardware.org/?probe=cf40d3f30c) | Dec 31, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [8b84042dc6](https://linux-hardware.org/?probe=8b84042dc6) | Dec 30, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [dae09ec15f](https://linux-hardware.org/?probe=dae09ec15f) | Dec 30, 2022 |
| Intel         | LADPNVMO AAE76523-300       | Desktop     | [4e6065532f](https://linux-hardware.org/?probe=4e6065532f) | Dec 30, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [cc31efb32d](https://linux-hardware.org/?probe=cc31efb32d) | Dec 30, 2022 |
| ASUSTek       | X555UJ                      | Notebook    | [f4ba8643aa](https://linux-hardware.org/?probe=f4ba8643aa) | Dec 30, 2022 |
| AMI           | F3C2                        | Notebook    | [ed7d4a2a13](https://linux-hardware.org/?probe=ed7d4a2a13) | Dec 30, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [716ba7f970](https://linux-hardware.org/?probe=716ba7f970) | Dec 29, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [7881f027ea](https://linux-hardware.org/?probe=7881f027ea) | Dec 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1cf63ef1ad](https://linux-hardware.org/?probe=1cf63ef1ad) | Dec 28, 2022 |
| HP            | 1905                        | Desktop     | [5c576316f8](https://linux-hardware.org/?probe=5c576316f8) | Dec 28, 2022 |
| ASUSTek       | Z87-C                       | Desktop     | [4929f6a6c9](https://linux-hardware.org/?probe=4929f6a6c9) | Dec 28, 2022 |
| Dell          | Inspiron 7586               | Convertible | [d670af270f](https://linux-hardware.org/?probe=d670af270f) | Dec 28, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [f58bb411b8](https://linux-hardware.org/?probe=f58bb411b8) | Dec 28, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | Notebook    | [d1f63174e4](https://linux-hardware.org/?probe=d1f63174e4) | Dec 28, 2022 |
| Lenovo        | ThinkPad X131e 33672K5      | Notebook    | [70d10e91fb](https://linux-hardware.org/?probe=70d10e91fb) | Dec 28, 2022 |
| MSI           | Z97 GAMING 3                | Desktop     | [7aab4546f6](https://linux-hardware.org/?probe=7aab4546f6) | Dec 28, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | Notebook    | [6eaa690ff2](https://linux-hardware.org/?probe=6eaa690ff2) | Dec 28, 2022 |
| Toshiba       | PORTEGE Z30-C               | Notebook    | [03dad182bb](https://linux-hardware.org/?probe=03dad182bb) | Dec 28, 2022 |
| MSI           | Raider GE77HX 12UGS         | Notebook    | [9f7185ccd7](https://linux-hardware.org/?probe=9f7185ccd7) | Dec 27, 2022 |
| ASRock        | AD2700-ITX                  | Desktop     | [d4fff49f31](https://linux-hardware.org/?probe=d4fff49f31) | Dec 27, 2022 |
| Lenovo        | ThinkStation D30 42234T7    | Desktop     | [6ad649ad46](https://linux-hardware.org/?probe=6ad649ad46) | Dec 26, 2022 |
| Lenovo        | ThinkStation D30 42234T7    | Desktop     | [6ac63aca4f](https://linux-hardware.org/?probe=6ac63aca4f) | Dec 25, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [8d9b11c617](https://linux-hardware.org/?probe=8d9b11c617) | Dec 25, 2022 |
| MSI           | GP62M 7REX                  | Notebook    | [f49c90b8dc](https://linux-hardware.org/?probe=f49c90b8dc) | Dec 25, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [82de75771e](https://linux-hardware.org/?probe=82de75771e) | Dec 25, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [b5eaa2b6aa](https://linux-hardware.org/?probe=b5eaa2b6aa) | Dec 25, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [b95d3d3c7a](https://linux-hardware.org/?probe=b95d3d3c7a) | Dec 25, 2022 |
| Dell          | Latitude E6520              | Notebook    | [33a51c934d](https://linux-hardware.org/?probe=33a51c934d) | Dec 25, 2022 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [10b9f48473](https://linux-hardware.org/?probe=10b9f48473) | Dec 25, 2022 |
| MSI           | GS60 6QE                    | Notebook    | [aa2f6b0f24](https://linux-hardware.org/?probe=aa2f6b0f24) | Dec 24, 2022 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [2a7ce79df8](https://linux-hardware.org/?probe=2a7ce79df8) | Dec 24, 2022 |
| Lenovo        | MIIX 510-12IKB 80XE         | Tablet      | [d88bd74acf](https://linux-hardware.org/?probe=d88bd74acf) | Dec 24, 2022 |
| Toshiba       | Satellite C50D-C            | Notebook    | [5f2debe594](https://linux-hardware.org/?probe=5f2debe594) | Dec 23, 2022 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [3073d2d4e1](https://linux-hardware.org/?probe=3073d2d4e1) | Dec 23, 2022 |
| Lenovo        | ThinkPad X260 20F5005NAU    | Notebook    | [5f75bb423d](https://linux-hardware.org/?probe=5f75bb423d) | Dec 23, 2022 |
| Lenovo        | ThinkPad X260 20F5005NAU    | Notebook    | [844f589d20](https://linux-hardware.org/?probe=844f589d20) | Dec 22, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [29e02a10bf](https://linux-hardware.org/?probe=29e02a10bf) | Dec 22, 2022 |
| MSI           | B450M MORTAR                | Desktop     | [2279954594](https://linux-hardware.org/?probe=2279954594) | Dec 22, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [4732443b9e](https://linux-hardware.org/?probe=4732443b9e) | Dec 22, 2022 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [36fbefc790](https://linux-hardware.org/?probe=36fbefc790) | Dec 22, 2022 |
| MSI           | B85M-E45                    | Desktop     | [b60edb092f](https://linux-hardware.org/?probe=b60edb092f) | Dec 21, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [354b048898](https://linux-hardware.org/?probe=354b048898) | Dec 21, 2022 |
| ASRock        | Z170 Pro4                   | Desktop     | [ca027f264a](https://linux-hardware.org/?probe=ca027f264a) | Dec 20, 2022 |
| HP            | Pavilion dv6                | Notebook    | [8b0f82599c](https://linux-hardware.org/?probe=8b0f82599c) | Dec 20, 2022 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [1fec8c22dc](https://linux-hardware.org/?probe=1fec8c22dc) | Dec 20, 2022 |
| Lenovo        | ThinkPad X1 Yoga Gen 6 2... | Convertible | [b8b3b4f2bd](https://linux-hardware.org/?probe=b8b3b4f2bd) | Dec 19, 2022 |
| Pegatron      | 2ACB                        | Desktop     | [f77ff3b9b5](https://linux-hardware.org/?probe=f77ff3b9b5) | Dec 19, 2022 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [d45689035c](https://linux-hardware.org/?probe=d45689035c) | Dec 19, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [2318fda45f](https://linux-hardware.org/?probe=2318fda45f) | Dec 19, 2022 |
| MSI           | Boston                      | Desktop     | [8587c9cf45](https://linux-hardware.org/?probe=8587c9cf45) | Dec 19, 2022 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [b0a4a9919c](https://linux-hardware.org/?probe=b0a4a9919c) | Dec 18, 2022 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [26ecfabc95](https://linux-hardware.org/?probe=26ecfabc95) | Dec 17, 2022 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [a17338c77a](https://linux-hardware.org/?probe=a17338c77a) | Dec 17, 2022 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [50ba321b50](https://linux-hardware.org/?probe=50ba321b50) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Yoga Gen 6 2... | Convertible | [d54bfbf8ff](https://linux-hardware.org/?probe=d54bfbf8ff) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Yoga Gen 6 2... | Convertible | [310076ab4f](https://linux-hardware.org/?probe=310076ab4f) | Dec 16, 2022 |
| ASUSTek       | X550LD                      | Notebook    | [2960bdb195](https://linux-hardware.org/?probe=2960bdb195) | Dec 16, 2022 |
| Intel         | NUC13SBBi9 M58736-302       | Mini pc     | [de15eb8246](https://linux-hardware.org/?probe=de15eb8246) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Yoga Gen 6 2... | Convertible | [aad215d28c](https://linux-hardware.org/?probe=aad215d28c) | Dec 15, 2022 |
| Lenovo        | ThinkPad X1 Yoga Gen 6 2... | Convertible | [0f506ff34d](https://linux-hardware.org/?probe=0f506ff34d) | Dec 15, 2022 |
| HP            | 212A                        | Desktop     | [c21bb6d20d](https://linux-hardware.org/?probe=c21bb6d20d) | Dec 14, 2022 |
| Apple         | MacBookPro14,2              | Notebook    | [702a622854](https://linux-hardware.org/?probe=702a622854) | Dec 14, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [b1386d66d5](https://linux-hardware.org/?probe=b1386d66d5) | Dec 13, 2022 |
| Kogan         | KAL11C250SB                 | Notebook    | [e7ad1c21ad](https://linux-hardware.org/?probe=e7ad1c21ad) | Dec 13, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [265ba7b252](https://linux-hardware.org/?probe=265ba7b252) | Dec 13, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [259f85d65b](https://linux-hardware.org/?probe=259f85d65b) | Dec 12, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [6c3fcfbb13](https://linux-hardware.org/?probe=6c3fcfbb13) | Dec 12, 2022 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [8111a18c7c](https://linux-hardware.org/?probe=8111a18c7c) | Dec 12, 2022 |
| Dell          | XPS L521X                   | Notebook    | [c69c906797](https://linux-hardware.org/?probe=c69c906797) | Dec 12, 2022 |
| ASUSTek       | K56CB                       | Notebook    | [94b056f1f4](https://linux-hardware.org/?probe=94b056f1f4) | Dec 12, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [4f1f6fde97](https://linux-hardware.org/?probe=4f1f6fde97) | Dec 10, 2022 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [b77b64cc48](https://linux-hardware.org/?probe=b77b64cc48) | Dec 09, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [26f5bfeb45](https://linux-hardware.org/?probe=26f5bfeb45) | Dec 09, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [e95599a479](https://linux-hardware.org/?probe=e95599a479) | Dec 09, 2022 |
| Gigabyte      | EP45-DS4P                   | Desktop     | [5acdccf7c0](https://linux-hardware.org/?probe=5acdccf7c0) | Dec 09, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [b0de030271](https://linux-hardware.org/?probe=b0de030271) | Dec 09, 2022 |
| Dell          | 0WPG9H A00                  | All in one  | [3a67010b28](https://linux-hardware.org/?probe=3a67010b28) | Dec 08, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [5e56097f25](https://linux-hardware.org/?probe=5e56097f25) | Dec 08, 2022 |
| MSI           | PRO B650-P WIFI             | Desktop     | [b74866314e](https://linux-hardware.org/?probe=b74866314e) | Dec 08, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [bede7701b9](https://linux-hardware.org/?probe=bede7701b9) | Dec 08, 2022 |
| HP            | 3395                        | All in one  | [daedb871f5](https://linux-hardware.org/?probe=daedb871f5) | Dec 08, 2022 |
| HP            | ProLiant DL380 Gen9         | Server      | [d368f224c8](https://linux-hardware.org/?probe=d368f224c8) | Dec 08, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [6f715ffe60](https://linux-hardware.org/?probe=6f715ffe60) | Dec 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [b5f311cc8f](https://linux-hardware.org/?probe=b5f311cc8f) | Dec 07, 2022 |
| Microsoft     | Surface Laptop 3            | Tablet      | [d1e2a097a9](https://linux-hardware.org/?probe=d1e2a097a9) | Dec 07, 2022 |
| Gigabyte      | D525TUD                     | Desktop     | [cfddc4ddef](https://linux-hardware.org/?probe=cfddc4ddef) | Dec 06, 2022 |
| Dell          | G15 5511                    | Notebook    | [999ed53283](https://linux-hardware.org/?probe=999ed53283) | Dec 05, 2022 |
| Apple         | MacBookPro15,1              | Notebook    | [36732e2602](https://linux-hardware.org/?probe=36732e2602) | Dec 05, 2022 |
| Dell          | Latitude 7390 2-in-1        | Convertible | [32594286ae](https://linux-hardware.org/?probe=32594286ae) | Dec 05, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | Notebook    | [c458ba13c3](https://linux-hardware.org/?probe=c458ba13c3) | Dec 05, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | Notebook    | [bd9f0dc967](https://linux-hardware.org/?probe=bd9f0dc967) | Dec 05, 2022 |
| Dell          | 0C2XKD A01                  | Desktop     | [e3d7eb48ec](https://linux-hardware.org/?probe=e3d7eb48ec) | Dec 05, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [dd012c9f92](https://linux-hardware.org/?probe=dd012c9f92) | Dec 04, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [fb96bd56ad](https://linux-hardware.org/?probe=fb96bd56ad) | Dec 04, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [cbb4692837](https://linux-hardware.org/?probe=cbb4692837) | Dec 04, 2022 |
| Unknown       | Unknown                     | Notebook    | [54c6593c53](https://linux-hardware.org/?probe=54c6593c53) | Dec 03, 2022 |
| ASRock        | Z68 Extreme4 Gen3           | Desktop     | [c2a68eb192](https://linux-hardware.org/?probe=c2a68eb192) | Dec 03, 2022 |
| Unknown       | Unknown                     | Notebook    | [7668b4d9a2](https://linux-hardware.org/?probe=7668b4d9a2) | Dec 03, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [af40c4e286](https://linux-hardware.org/?probe=af40c4e286) | Dec 03, 2022 |
| Acer          | ConceptD CN315-71P          | Notebook    | [370356b4a8](https://linux-hardware.org/?probe=370356b4a8) | Dec 02, 2022 |
| Acer          | ConceptD CN315-71P          | Notebook    | [bbdfc25e56](https://linux-hardware.org/?probe=bbdfc25e56) | Dec 02, 2022 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [7e188d7537](https://linux-hardware.org/?probe=7e188d7537) | Dec 02, 2022 |
| Intel Clie... | LAPBC510                    | Notebook    | [e903f5edea](https://linux-hardware.org/?probe=e903f5edea) | Dec 02, 2022 |
| Lenovo        | ThinkPad T420 4236GY3       | Notebook    | [63dd78fcec](https://linux-hardware.org/?probe=63dd78fcec) | Dec 02, 2022 |
| IBM           | 90Y4784                     | Server      | [a9289ca04c](https://linux-hardware.org/?probe=a9289ca04c) | Dec 02, 2022 |
| Dell          | 01V648 A02                  | Server      | [b8747a97b7](https://linux-hardware.org/?probe=b8747a97b7) | Dec 02, 2022 |
| Intel         | S1200RP G62251-405          | Server      | [28f4ceb8ee](https://linux-hardware.org/?probe=28f4ceb8ee) | Dec 02, 2022 |
| IBM           | 00MV214                     | Server      | [f2d1382390](https://linux-hardware.org/?probe=f2d1382390) | Dec 02, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [ca1fab4db1](https://linux-hardware.org/?probe=ca1fab4db1) | Dec 02, 2022 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [85f6854ce5](https://linux-hardware.org/?probe=85f6854ce5) | Dec 02, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [919c5d80c8](https://linux-hardware.org/?probe=919c5d80c8) | Dec 02, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [0949d0916c](https://linux-hardware.org/?probe=0949d0916c) | Dec 02, 2022 |
| Shuttle       | FS81                        | Desktop     | [6352050887](https://linux-hardware.org/?probe=6352050887) | Dec 02, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [2adab1a5b2](https://linux-hardware.org/?probe=2adab1a5b2) | Dec 02, 2022 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [e902390c9c](https://linux-hardware.org/?probe=e902390c9c) | Dec 02, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [f9ff6b9e31](https://linux-hardware.org/?probe=f9ff6b9e31) | Dec 02, 2022 |
| ASRock        | Z68 Extreme4 Gen3           | Desktop     | [717d165f0e](https://linux-hardware.org/?probe=717d165f0e) | Dec 02, 2022 |
| ASRock        | AD525PV3                    | Desktop     | [da83c87218](https://linux-hardware.org/?probe=da83c87218) | Dec 01, 2022 |
| ASRock        | Z68 Extreme4 Gen3           | Desktop     | [c14e2149eb](https://linux-hardware.org/?probe=c14e2149eb) | Dec 01, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [ba1e414d62](https://linux-hardware.org/?probe=ba1e414d62) | Nov 30, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [f4fa3a4e7f](https://linux-hardware.org/?probe=f4fa3a4e7f) | Nov 30, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [bc3188dd75](https://linux-hardware.org/?probe=bc3188dd75) | Nov 29, 2022 |
| AMI           | Intel                       | Notebook    | [3e2e312c6e](https://linux-hardware.org/?probe=3e2e312c6e) | Nov 29, 2022 |
| Razer         | Blade                       | Notebook    | [de6f0ebcad](https://linux-hardware.org/?probe=de6f0ebcad) | Nov 28, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [3433fd5db6](https://linux-hardware.org/?probe=3433fd5db6) | Nov 28, 2022 |
| MSI           | IONA                        | Desktop     | [255f7f8dc4](https://linux-hardware.org/?probe=255f7f8dc4) | Nov 28, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [ed4692d2a7](https://linux-hardware.org/?probe=ed4692d2a7) | Nov 28, 2022 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [ea6f1fc82e](https://linux-hardware.org/?probe=ea6f1fc82e) | Nov 28, 2022 |
| MSI           | IONA                        | Desktop     | [94841f2b61](https://linux-hardware.org/?probe=94841f2b61) | Nov 28, 2022 |
| ASUSTek       | M5A88-M                     | Desktop     | [f4b2035429](https://linux-hardware.org/?probe=f4b2035429) | Nov 28, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [f149afb5d1](https://linux-hardware.org/?probe=f149afb5d1) | Nov 28, 2022 |
| Intel Clie... | LAPBC510                    | Notebook    | [f58ff7b6fa](https://linux-hardware.org/?probe=f58ff7b6fa) | Nov 27, 2022 |
| Dell          | Latitude E7440              | Notebook    | [3709af0366](https://linux-hardware.org/?probe=3709af0366) | Nov 27, 2022 |
| Apple         | MacBookPro15,2              | Notebook    | [446ef54cb5](https://linux-hardware.org/?probe=446ef54cb5) | Nov 26, 2022 |
| Apple         | MacBookAir8,1               | Notebook    | [6656b4e315](https://linux-hardware.org/?probe=6656b4e315) | Nov 26, 2022 |
| Kogan         | KAL11C250SB                 | Notebook    | [9ca4f71bb9](https://linux-hardware.org/?probe=9ca4f71bb9) | Nov 26, 2022 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [2d8e324570](https://linux-hardware.org/?probe=2d8e324570) | Nov 26, 2022 |
| Razer         | Blade Pro                   | Notebook    | [dabfd64904](https://linux-hardware.org/?probe=dabfd64904) | Nov 25, 2022 |
| MSI           | GS60 6QE                    | Notebook    | [80d61ee685](https://linux-hardware.org/?probe=80d61ee685) | Nov 25, 2022 |
| HP            | 18E9                        | Desktop     | [dab5e242fd](https://linux-hardware.org/?probe=dab5e242fd) | Nov 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [16f086de33](https://linux-hardware.org/?probe=16f086de33) | Nov 25, 2022 |
| Dell          | Inspiron 7586               | Convertible | [91dcb3265a](https://linux-hardware.org/?probe=91dcb3265a) | Nov 24, 2022 |
| ASUSTek       | ROG ZENITH EXTREME ALPHA    | Desktop     | [1d224863f2](https://linux-hardware.org/?probe=1d224863f2) | Nov 24, 2022 |
| Acer          | Aspire R3-131T              | Notebook    | [5395a2556c](https://linux-hardware.org/?probe=5395a2556c) | Nov 24, 2022 |
| ASRock        | Z170 Pro4                   | Desktop     | [ac6ad8d54d](https://linux-hardware.org/?probe=ac6ad8d54d) | Nov 24, 2022 |
| Acer          | ConceptD CN315-71P          | Notebook    | [db3ccac179](https://linux-hardware.org/?probe=db3ccac179) | Nov 23, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [8ea3c120c6](https://linux-hardware.org/?probe=8ea3c120c6) | Nov 23, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [62c77a0e63](https://linux-hardware.org/?probe=62c77a0e63) | Nov 23, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [f396cc27ff](https://linux-hardware.org/?probe=f396cc27ff) | Nov 23, 2022 |
| Intel         | LADPNVMO AAE76523-300       | Desktop     | [db4e4c9c5b](https://linux-hardware.org/?probe=db4e4c9c5b) | Nov 22, 2022 |
| MSI           | IONA                        | Desktop     | [280083cfa1](https://linux-hardware.org/?probe=280083cfa1) | Nov 22, 2022 |
| MSI           | IONA                        | Desktop     | [39bcd0f2d8](https://linux-hardware.org/?probe=39bcd0f2d8) | Nov 22, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [06c02ff303](https://linux-hardware.org/?probe=06c02ff303) | Nov 21, 2022 |
| Acer          | TravelMate Spin B118-R      | Convertible | [16dc5dd369](https://linux-hardware.org/?probe=16dc5dd369) | Nov 20, 2022 |
| Lenovo        | ThinkPad X240 20AMA0LTAU    | Notebook    | [54ce03d1f1](https://linux-hardware.org/?probe=54ce03d1f1) | Nov 20, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [cb18ed6ab1](https://linux-hardware.org/?probe=cb18ed6ab1) | Nov 20, 2022 |
| Samsung       | RC410/RC510/RC710           | Notebook    | [06a337fda3](https://linux-hardware.org/?probe=06a337fda3) | Nov 20, 2022 |
| Samsung       | RC410/RC510/RC710           | Notebook    | [965d9d2f5c](https://linux-hardware.org/?probe=965d9d2f5c) | Nov 20, 2022 |
| HP            | 1495                        | Desktop     | [3ac774a6d6](https://linux-hardware.org/?probe=3ac774a6d6) | Nov 19, 2022 |
| HP            | 1495                        | Desktop     | [659062ad1d](https://linux-hardware.org/?probe=659062ad1d) | Nov 19, 2022 |
| MSI           | GP62M 7REX                  | Notebook    | [2125546b68](https://linux-hardware.org/?probe=2125546b68) | Nov 19, 2022 |
| MSI           | GP62M 7REX                  | Notebook    | [6ea684de8c](https://linux-hardware.org/?probe=6ea684de8c) | Nov 19, 2022 |
| ASRock        | AD2700-ITX                  | Desktop     | [806ac66c75](https://linux-hardware.org/?probe=806ac66c75) | Nov 19, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [587db1b08f](https://linux-hardware.org/?probe=587db1b08f) | Nov 19, 2022 |
| ASRock        | AD525PV3                    | Desktop     | [4bba69ecd9](https://linux-hardware.org/?probe=4bba69ecd9) | Nov 18, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [884474637c](https://linux-hardware.org/?probe=884474637c) | Nov 18, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [0b7bd42177](https://linux-hardware.org/?probe=0b7bd42177) | Nov 18, 2022 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [dbbfcd826c](https://linux-hardware.org/?probe=dbbfcd826c) | Nov 18, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | Notebook    | [2cb56b8c63](https://linux-hardware.org/?probe=2cb56b8c63) | Nov 17, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [e9eb63ca62](https://linux-hardware.org/?probe=e9eb63ca62) | Nov 17, 2022 |
| Dell          | 0D6H9T A01                  | Desktop     | [a50bca5670](https://linux-hardware.org/?probe=a50bca5670) | Nov 17, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [07d80f1783](https://linux-hardware.org/?probe=07d80f1783) | Nov 16, 2022 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [769e7a63d1](https://linux-hardware.org/?probe=769e7a63d1) | Nov 16, 2022 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [5e42accb39](https://linux-hardware.org/?probe=5e42accb39) | Nov 16, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [2d0fb1c5d1](https://linux-hardware.org/?probe=2d0fb1c5d1) | Nov 16, 2022 |
| AMI           | Intel                       | Notebook    | [ac36a02403](https://linux-hardware.org/?probe=ac36a02403) | Nov 16, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [22b0ad0cb0](https://linux-hardware.org/?probe=22b0ad0cb0) | Nov 15, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [66737bb1cc](https://linux-hardware.org/?probe=66737bb1cc) | Nov 15, 2022 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | Notebook    | [ccbda507a9](https://linux-hardware.org/?probe=ccbda507a9) | Nov 14, 2022 |
| Acer          | Aspire XC-840               | Desktop     | [fe8db55aac](https://linux-hardware.org/?probe=fe8db55aac) | Nov 14, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [fd017849be](https://linux-hardware.org/?probe=fd017849be) | Nov 13, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [97bfce0a04](https://linux-hardware.org/?probe=97bfce0a04) | Nov 13, 2022 |
| Lenovo        | ThinkCentre A70z 0401G6M    | Desktop     | [a84e5c2107](https://linux-hardware.org/?probe=a84e5c2107) | Nov 13, 2022 |
| ASUSTek       | X550CC                      | Notebook    | [d37b8f7bbd](https://linux-hardware.org/?probe=d37b8f7bbd) | Nov 13, 2022 |
| Dell          | Latitude 7210 2-in-1        | Tablet      | [acce4cc1af](https://linux-hardware.org/?probe=acce4cc1af) | Nov 13, 2022 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [67c110e0a7](https://linux-hardware.org/?probe=67c110e0a7) | Nov 13, 2022 |
| Acer          | ConceptD CN315-71P          | Notebook    | [2d3a3f4ac8](https://linux-hardware.org/?probe=2d3a3f4ac8) | Nov 13, 2022 |
| Intel         | LADPNVMO AAE76523-300       | Desktop     | [ea94d443c9](https://linux-hardware.org/?probe=ea94d443c9) | Nov 12, 2022 |
| ASUSTek       | PRIME A320M-E               | Desktop     | [2eacb090ee](https://linux-hardware.org/?probe=2eacb090ee) | Nov 12, 2022 |
| ASUSTek       | PRIME A320M-E               | Desktop     | [a35ca3673b](https://linux-hardware.org/?probe=a35ca3673b) | Nov 12, 2022 |
| ASRock        | B75M                        | Desktop     | [7da4910326](https://linux-hardware.org/?probe=7da4910326) | Nov 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [57368a1129](https://linux-hardware.org/?probe=57368a1129) | Nov 12, 2022 |
| Apple         | MacBook9,1                  | Notebook    | [755a70132f](https://linux-hardware.org/?probe=755a70132f) | Nov 12, 2022 |
| Apple         | MacBook9,1                  | Notebook    | [4371465097](https://linux-hardware.org/?probe=4371465097) | Nov 12, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [1d6ae45d45](https://linux-hardware.org/?probe=1d6ae45d45) | Nov 11, 2022 |
| MSI           | GS60 6QE                    | Notebook    | [a571dc503c](https://linux-hardware.org/?probe=a571dc503c) | Nov 11, 2022 |
| Toshiba       | TECRA A40-D                 | Notebook    | [ab2d9e2712](https://linux-hardware.org/?probe=ab2d9e2712) | Nov 11, 2022 |
| Acer          | Aspire A315-22              | Notebook    | [cde0b24cde](https://linux-hardware.org/?probe=cde0b24cde) | Nov 10, 2022 |
| ASRock        | Z68 Extreme3 Gen3           | Desktop     | [01cb4ff120](https://linux-hardware.org/?probe=01cb4ff120) | Nov 10, 2022 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [4ff6488cb2](https://linux-hardware.org/?probe=4ff6488cb2) | Nov 10, 2022 |
| Lenovo        | ThinkPad T420 4180PEM       | Notebook    | [ad4d7f338d](https://linux-hardware.org/?probe=ad4d7f338d) | Nov 09, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [3189f08179](https://linux-hardware.org/?probe=3189f08179) | Nov 09, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [a7de751ce8](https://linux-hardware.org/?probe=a7de751ce8) | Nov 09, 2022 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [dbf32417df](https://linux-hardware.org/?probe=dbf32417df) | Nov 09, 2022 |
| Lenovo        | ThinkCentre A70z 0401G6M    | Desktop     | [f2afc66464](https://linux-hardware.org/?probe=f2afc66464) | Nov 09, 2022 |
| ASRock        | B550 Steel Legend           | Desktop     | [8c775416b9](https://linux-hardware.org/?probe=8c775416b9) | Nov 08, 2022 |
| Microsoft     | Surface Laptop 2            | Tablet      | [43bf170205](https://linux-hardware.org/?probe=43bf170205) | Nov 08, 2022 |
| ASRock        | X570 Steel Legend           | Desktop     | [638b6a52ff](https://linux-hardware.org/?probe=638b6a52ff) | Nov 08, 2022 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [ee895bde1f](https://linux-hardware.org/?probe=ee895bde1f) | Nov 08, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [0e2747c7ab](https://linux-hardware.org/?probe=0e2747c7ab) | Nov 08, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [5f358af327](https://linux-hardware.org/?probe=5f358af327) | Nov 08, 2022 |
| MSI           | GS60 6QE                    | Notebook    | [c843b1ff5e](https://linux-hardware.org/?probe=c843b1ff5e) | Nov 08, 2022 |
| Dell          | 0DF42J A00                  | Desktop     | [67928f8921](https://linux-hardware.org/?probe=67928f8921) | Nov 07, 2022 |
| Microsoft     | Surface Laptop 2            | Tablet      | [27acb96a8f](https://linux-hardware.org/?probe=27acb96a8f) | Nov 07, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [a38da64b4f](https://linux-hardware.org/?probe=a38da64b4f) | Nov 07, 2022 |
| Gigabyte      | B660M D3H DDR4              | Desktop     | [64aed4564c](https://linux-hardware.org/?probe=64aed4564c) | Nov 07, 2022 |
| ASUSTek       | K53E                        | Notebook    | [07d6d01b99](https://linux-hardware.org/?probe=07d6d01b99) | Nov 06, 2022 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [7ea9f2df61](https://linux-hardware.org/?probe=7ea9f2df61) | Nov 06, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [dd757fb650](https://linux-hardware.org/?probe=dd757fb650) | Nov 06, 2022 |
| Dell          | Latitude E6430              | Notebook    | [fcd82d5966](https://linux-hardware.org/?probe=fcd82d5966) | Nov 06, 2022 |
| Toshiba       | Satellite L500              | Notebook    | [0d6bb9cde0](https://linux-hardware.org/?probe=0d6bb9cde0) | Nov 05, 2022 |
| Toshiba       | Satellite L500              | Notebook    | [3d7692d178](https://linux-hardware.org/?probe=3d7692d178) | Nov 05, 2022 |
| HP            | 3396                        | Desktop     | [d6867789ca](https://linux-hardware.org/?probe=d6867789ca) | Nov 04, 2022 |
| MSI           | Katana GF76 12UC            | Notebook    | [3cb05bdb95](https://linux-hardware.org/?probe=3cb05bdb95) | Nov 04, 2022 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [c39a19fa2f](https://linux-hardware.org/?probe=c39a19fa2f) | Nov 04, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [4be0967ca1](https://linux-hardware.org/?probe=4be0967ca1) | Nov 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [cc28dc5c8b](https://linux-hardware.org/?probe=cc28dc5c8b) | Nov 04, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [a8f3260004](https://linux-hardware.org/?probe=a8f3260004) | Nov 04, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [c4b2b4072b](https://linux-hardware.org/?probe=c4b2b4072b) | Nov 04, 2022 |
| Dell          | 0200DY A01                  | Desktop     | [a473b71b4e](https://linux-hardware.org/?probe=a473b71b4e) | Nov 03, 2022 |
| Gigabyte      | G41MT-D3                    | Desktop     | [921a646464](https://linux-hardware.org/?probe=921a646464) | Nov 03, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [80e0ccbf42](https://linux-hardware.org/?probe=80e0ccbf42) | Nov 03, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [e24f2a2f57](https://linux-hardware.org/?probe=e24f2a2f57) | Nov 03, 2022 |
| ASUSTek       | 1005HA                      | Notebook    | [1d386943d6](https://linux-hardware.org/?probe=1d386943d6) | Nov 02, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [9fef9a6a8a](https://linux-hardware.org/?probe=9fef9a6a8a) | Nov 02, 2022 |
| Cube          | i18-BL                      | Notebook    | [725100a829](https://linux-hardware.org/?probe=725100a829) | Nov 02, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | Notebook    | [fefe8e5d04](https://linux-hardware.org/?probe=fefe8e5d04) | Nov 01, 2022 |
| HP            | Notebook                    | Notebook    | [27d097b522](https://linux-hardware.org/?probe=27d097b522) | Nov 01, 2022 |
| Acer          | Aspire 3000                 | Notebook    | [02693e03ca](https://linux-hardware.org/?probe=02693e03ca) | Nov 01, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | Notebook    | [df949b6e10](https://linux-hardware.org/?probe=df949b6e10) | Nov 01, 2022 |
| ASUSTek       | X501A                       | Notebook    | [d5a34df414](https://linux-hardware.org/?probe=d5a34df414) | Nov 01, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [722ae37952](https://linux-hardware.org/?probe=722ae37952) | Nov 01, 2022 |
| ASUSTek       | B150M-V PLUS                | Desktop     | [a451844625](https://linux-hardware.org/?probe=a451844625) | Nov 01, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [a2a8473e4b](https://linux-hardware.org/?probe=a2a8473e4b) | Oct 31, 2022 |
| ASRock        | X670E Pro RS                | Desktop     | [5ebdf73c67](https://linux-hardware.org/?probe=5ebdf73c67) | Oct 31, 2022 |
| HP            | 8653 A                      | Desktop     | [9c19089f51](https://linux-hardware.org/?probe=9c19089f51) | Oct 29, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [1c5d979ba1](https://linux-hardware.org/?probe=1c5d979ba1) | Oct 29, 2022 |
| Dell          | 0478VN A00                  | Desktop     | [883100c74f](https://linux-hardware.org/?probe=883100c74f) | Oct 29, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [1d3ff229c6](https://linux-hardware.org/?probe=1d3ff229c6) | Oct 29, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [c3ea4065c4](https://linux-hardware.org/?probe=c3ea4065c4) | Oct 29, 2022 |
| Dell          | 0478VN A00                  | Desktop     | [629858e96c](https://linux-hardware.org/?probe=629858e96c) | Oct 29, 2022 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [af4751bfcf](https://linux-hardware.org/?probe=af4751bfcf) | Oct 28, 2022 |
| Gigabyte      | G41MT-D3                    | Desktop     | [2e4153161f](https://linux-hardware.org/?probe=2e4153161f) | Oct 28, 2022 |
| ASUSTek       | U50Vg                       | Notebook    | [5f2997ec95](https://linux-hardware.org/?probe=5f2997ec95) | Oct 28, 2022 |
| HP            | 829B                        | All in one  | [1f8f75d1c0](https://linux-hardware.org/?probe=1f8f75d1c0) | Oct 27, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [b096155d39](https://linux-hardware.org/?probe=b096155d39) | Oct 27, 2022 |
| HP            | 8653 A                      | Desktop     | [92b68870ca](https://linux-hardware.org/?probe=92b68870ca) | Oct 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [73d5bfb13a](https://linux-hardware.org/?probe=73d5bfb13a) | Oct 27, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [cca0d420fe](https://linux-hardware.org/?probe=cca0d420fe) | Oct 27, 2022 |
| HP            | G71                         | Notebook    | [3223e2fcc8](https://linux-hardware.org/?probe=3223e2fcc8) | Oct 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [7290786792](https://linux-hardware.org/?probe=7290786792) | Oct 26, 2022 |
| Microsoft     | Surface Pro                 | Tablet      | [df069d17c5](https://linux-hardware.org/?probe=df069d17c5) | Oct 26, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [54f6493d11](https://linux-hardware.org/?probe=54f6493d11) | Oct 26, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [3848afd2c8](https://linux-hardware.org/?probe=3848afd2c8) | Oct 26, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [6896f337ab](https://linux-hardware.org/?probe=6896f337ab) | Oct 25, 2022 |
| Gigabyte      | Z590I VISION D              | Desktop     | [be4c6573cd](https://linux-hardware.org/?probe=be4c6573cd) | Oct 25, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [82fb357322](https://linux-hardware.org/?probe=82fb357322) | Oct 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [4ffd604fea](https://linux-hardware.org/?probe=4ffd604fea) | Oct 25, 2022 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [23be2713d2](https://linux-hardware.org/?probe=23be2713d2) | Oct 24, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [6331b122dc](https://linux-hardware.org/?probe=6331b122dc) | Oct 24, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [6f72d6443c](https://linux-hardware.org/?probe=6f72d6443c) | Oct 23, 2022 |
| HP            | 0B40h                       | Desktop     | [981b4e9553](https://linux-hardware.org/?probe=981b4e9553) | Oct 23, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [edd13bcc76](https://linux-hardware.org/?probe=edd13bcc76) | Oct 23, 2022 |
| Notebook      | W650EH                      | Notebook    | [6bb1a8b1f1](https://linux-hardware.org/?probe=6bb1a8b1f1) | Oct 23, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII EXTRE... | Desktop     | [32cd9cd246](https://linux-hardware.org/?probe=32cd9cd246) | Oct 22, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [3e2bd05f56](https://linux-hardware.org/?probe=3e2bd05f56) | Oct 22, 2022 |
| Purism        | Librem 13 v2                | Notebook    | [5296ed1e19](https://linux-hardware.org/?probe=5296ed1e19) | Oct 21, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [cb901021a7](https://linux-hardware.org/?probe=cb901021a7) | Oct 21, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [63751816bc](https://linux-hardware.org/?probe=63751816bc) | Oct 21, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [1ab730c85c](https://linux-hardware.org/?probe=1ab730c85c) | Oct 21, 2022 |
| Gigabyte      | X570S AORUS ELITE           | Desktop     | [bc75d3cc30](https://linux-hardware.org/?probe=bc75d3cc30) | Oct 21, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [60d4787bb7](https://linux-hardware.org/?probe=60d4787bb7) | Oct 21, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [31d7e67080](https://linux-hardware.org/?probe=31d7e67080) | Oct 21, 2022 |
| Acer          | Aspire 5600                 | Notebook    | [202a7e570e](https://linux-hardware.org/?probe=202a7e570e) | Oct 20, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [502ae94f8f](https://linux-hardware.org/?probe=502ae94f8f) | Oct 20, 2022 |
| Lenovo        | ThinkPad T410 2522PT3       | Notebook    | [2cd92a7da8](https://linux-hardware.org/?probe=2cd92a7da8) | Oct 19, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [5086e64fed](https://linux-hardware.org/?probe=5086e64fed) | Oct 19, 2022 |
| Intel         | NUC11PABi5 K90634-302       | Mini pc     | [4c9eafcd7f](https://linux-hardware.org/?probe=4c9eafcd7f) | Oct 19, 2022 |
| Dell          | Inspiron M5010              | Notebook    | [026a7a8cd3](https://linux-hardware.org/?probe=026a7a8cd3) | Oct 18, 2022 |
| HP            | 2B21 A01                    | All in one  | [8a8935ed07](https://linux-hardware.org/?probe=8a8935ed07) | Oct 18, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [926d661756](https://linux-hardware.org/?probe=926d661756) | Oct 17, 2022 |
| HP            | G71                         | Notebook    | [46b6033e1e](https://linux-hardware.org/?probe=46b6033e1e) | Oct 17, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [50c44df4fb](https://linux-hardware.org/?probe=50c44df4fb) | Oct 17, 2022 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [f30aab43b6](https://linux-hardware.org/?probe=f30aab43b6) | Oct 16, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [d9928a4ee9](https://linux-hardware.org/?probe=d9928a4ee9) | Oct 16, 2022 |
| System76      | Galago Pro                  | Notebook    | [ec92c5a918](https://linux-hardware.org/?probe=ec92c5a918) | Oct 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [79eba98b95](https://linux-hardware.org/?probe=79eba98b95) | Oct 14, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [5f0c4b3acb](https://linux-hardware.org/?probe=5f0c4b3acb) | Oct 13, 2022 |
| Acer          | Aspire XC100A               | Desktop     | [6fade2c77f](https://linux-hardware.org/?probe=6fade2c77f) | Oct 13, 2022 |
| Apple         | MacBookPro15,2              | Notebook    | [705e4f406a](https://linux-hardware.org/?probe=705e4f406a) | Oct 13, 2022 |
| HP            | EliteBook 8540p             | Notebook    | [cd65876f22](https://linux-hardware.org/?probe=cd65876f22) | Oct 12, 2022 |
| HP            | 1497                        | Desktop     | [ff6d690da4](https://linux-hardware.org/?probe=ff6d690da4) | Oct 12, 2022 |
| Gigabyte      | X570S GAMING X              | Desktop     | [e966aea162](https://linux-hardware.org/?probe=e966aea162) | Oct 12, 2022 |
| Lenovo        | 3129 SDK0J40700 WIN 3258... | Desktop     | [1798dba7f1](https://linux-hardware.org/?probe=1798dba7f1) | Oct 12, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [4bc40092b2](https://linux-hardware.org/?probe=4bc40092b2) | Oct 11, 2022 |
| Apple         | MacBookPro15,2              | Notebook    | [56fc798c2e](https://linux-hardware.org/?probe=56fc798c2e) | Oct 11, 2022 |
| Dell          | 07WJF3 A00                  | Desktop     | [62f8858433](https://linux-hardware.org/?probe=62f8858433) | Oct 11, 2022 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [dde4a94108](https://linux-hardware.org/?probe=dde4a94108) | Oct 11, 2022 |
| Acer          | Aspire A315-22              | Notebook    | [07870a3cde](https://linux-hardware.org/?probe=07870a3cde) | Oct 11, 2022 |
| Gigabyte      | H410M DS2V                  | Desktop     | [bd9d9e10c7](https://linux-hardware.org/?probe=bd9d9e10c7) | Oct 11, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [1ae81569dd](https://linux-hardware.org/?probe=1ae81569dd) | Oct 11, 2022 |
| Dell          | Inspiron 16 5620            | Notebook    | [72151cd0e8](https://linux-hardware.org/?probe=72151cd0e8) | Oct 10, 2022 |
| Gigabyte      | P34V7                       | Notebook    | [c1423fce9e](https://linux-hardware.org/?probe=c1423fce9e) | Oct 10, 2022 |
| System76      | Galago Pro                  | Notebook    | [28e36afa26](https://linux-hardware.org/?probe=28e36afa26) | Oct 10, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [a7b96649da](https://linux-hardware.org/?probe=a7b96649da) | Oct 09, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [e26fca4929](https://linux-hardware.org/?probe=e26fca4929) | Oct 09, 2022 |
| Panasonic     | CF-19-8                     | Notebook    | [439e2c8122](https://linux-hardware.org/?probe=439e2c8122) | Oct 09, 2022 |
| Panasonic     | CF-19-8                     | Notebook    | [bc5820629b](https://linux-hardware.org/?probe=bc5820629b) | Oct 09, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [6b62586012](https://linux-hardware.org/?probe=6b62586012) | Oct 09, 2022 |
| MSI           | X399 SLI PLUS               | Desktop     | [027504f861](https://linux-hardware.org/?probe=027504f861) | Oct 08, 2022 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [2ad7a0c296](https://linux-hardware.org/?probe=2ad7a0c296) | Oct 08, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [e26911cff6](https://linux-hardware.org/?probe=e26911cff6) | Oct 08, 2022 |
| Shuttle       | FS81                        | Desktop     | [ba7c22e135](https://linux-hardware.org/?probe=ba7c22e135) | Oct 07, 2022 |
| Shuttle       | FS81                        | Desktop     | [63ec5c8971](https://linux-hardware.org/?probe=63ec5c8971) | Oct 07, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [e05dbad108](https://linux-hardware.org/?probe=e05dbad108) | Oct 07, 2022 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [9dc72dc357](https://linux-hardware.org/?probe=9dc72dc357) | Oct 07, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [3ea8d4d25e](https://linux-hardware.org/?probe=3ea8d4d25e) | Oct 06, 2022 |
| HP            | Presario V4000 (EQ608PA#... | Notebook    | [f462d80b2a](https://linux-hardware.org/?probe=f462d80b2a) | Oct 06, 2022 |
| Gigabyte      | Z270X-Gaming 5              | Desktop     | [9ad9a1c969](https://linux-hardware.org/?probe=9ad9a1c969) | Oct 06, 2022 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [2e57f97484](https://linux-hardware.org/?probe=2e57f97484) | Oct 06, 2022 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [9232451f1a](https://linux-hardware.org/?probe=9232451f1a) | Oct 06, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [b5cf733c51](https://linux-hardware.org/?probe=b5cf733c51) | Oct 06, 2022 |
| ASUSTek       | PRIME X299-DELUXE II        | Desktop     | [4f3856c8f0](https://linux-hardware.org/?probe=4f3856c8f0) | Oct 06, 2022 |
| MSI           | B450-A PRO                  | Desktop     | [5ff1f9c5c3](https://linux-hardware.org/?probe=5ff1f9c5c3) | Oct 05, 2022 |
| Lenovo        | ThinkStation S30 0569BE3    | Desktop     | [026d1ee25e](https://linux-hardware.org/?probe=026d1ee25e) | Oct 05, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [99f16967b2](https://linux-hardware.org/?probe=99f16967b2) | Oct 05, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [ca81117136](https://linux-hardware.org/?probe=ca81117136) | Oct 05, 2022 |
| Gigabyte      | AORUS 7 SB                  | Notebook    | [444224d1e0](https://linux-hardware.org/?probe=444224d1e0) | Oct 04, 2022 |
| Dell          | 0WF810                      | Desktop     | [dd24119965](https://linux-hardware.org/?probe=dd24119965) | Oct 04, 2022 |
| Acer          | TravelMate 8572T            | Notebook    | [6abaaf4aa6](https://linux-hardware.org/?probe=6abaaf4aa6) | Oct 03, 2022 |
| Gigabyte      | D525TUD                     | Desktop     | [47d31ff25c](https://linux-hardware.org/?probe=47d31ff25c) | Oct 03, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [a7e31149f2](https://linux-hardware.org/?probe=a7e31149f2) | Oct 02, 2022 |
| Dell          | 0XCR8D A00                  | Desktop     | [82e52ab722](https://linux-hardware.org/?probe=82e52ab722) | Oct 02, 2022 |
| Dell          | 0XCR8D A00                  | Desktop     | [a6db1f5075](https://linux-hardware.org/?probe=a6db1f5075) | Oct 02, 2022 |
| Dell          | Inspiron 15 7510            | Notebook    | [521636075a](https://linux-hardware.org/?probe=521636075a) | Oct 02, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [c555fbbf75](https://linux-hardware.org/?probe=c555fbbf75) | Oct 01, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [9c6340e585](https://linux-hardware.org/?probe=9c6340e585) | Oct 01, 2022 |
| Lenovo        | ThinkPad Yoga 260 20FE00... | Convertible | [4eaeb1d5ad](https://linux-hardware.org/?probe=4eaeb1d5ad) | Oct 01, 2022 |
| ASRock        | AD2700-ITX                  | Desktop     | [4275ef3653](https://linux-hardware.org/?probe=4275ef3653) | Oct 01, 2022 |
| MSI           | PRO X670-P WIFI             | Desktop     | [64299c7b4a](https://linux-hardware.org/?probe=64299c7b4a) | Oct 01, 2022 |
| Toshiba       | PORTEGE Z10t-A              | Notebook    | [1aa913c010](https://linux-hardware.org/?probe=1aa913c010) | Oct 01, 2022 |
| ASUSTek       | UX360UAK                    | Convertible | [4662cb1d99](https://linux-hardware.org/?probe=4662cb1d99) | Oct 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [025a55eab7](https://linux-hardware.org/?probe=025a55eab7) | Sep 30, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [875b1df312](https://linux-hardware.org/?probe=875b1df312) | Sep 30, 2022 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [3f01bbaa12](https://linux-hardware.org/?probe=3f01bbaa12) | Sep 30, 2022 |
| Acer          | TravelMate 8572T            | Notebook    | [927bf01e34](https://linux-hardware.org/?probe=927bf01e34) | Sep 30, 2022 |
| Gigabyte      | AORUS 17 YE5                | Notebook    | [54b271c3fd](https://linux-hardware.org/?probe=54b271c3fd) | Sep 30, 2022 |
| Lenovo        | Yoga 310-11IAP 80U2         | Convertible | [cc7ad91815](https://linux-hardware.org/?probe=cc7ad91815) | Sep 29, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [354a9c2bc2](https://linux-hardware.org/?probe=354a9c2bc2) | Sep 29, 2022 |
| Dell          | Inspiron 7347               | Notebook    | [ac3079df8c](https://linux-hardware.org/?probe=ac3079df8c) | Sep 29, 2022 |
| Dell          | Inspiron 7347               | Notebook    | [144cad649c](https://linux-hardware.org/?probe=144cad649c) | Sep 29, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [fbc4f29134](https://linux-hardware.org/?probe=fbc4f29134) | Sep 28, 2022 |
| HP            | EliteBook 8770w             | Notebook    | [e5ec559da4](https://linux-hardware.org/?probe=e5ec559da4) | Sep 28, 2022 |
| Dell          | Latitude E7450              | Notebook    | [daeb4afb69](https://linux-hardware.org/?probe=daeb4afb69) | Sep 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [76aac25208](https://linux-hardware.org/?probe=76aac25208) | Sep 28, 2022 |
| Acer          | Spin SP314-53               | Convertible | [ce95ade177](https://linux-hardware.org/?probe=ce95ade177) | Sep 27, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [565d46fb85](https://linux-hardware.org/?probe=565d46fb85) | Sep 27, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [2c69225287](https://linux-hardware.org/?probe=2c69225287) | Sep 27, 2022 |
| Gigabyte      | P34V7                       | Notebook    | [27b9651432](https://linux-hardware.org/?probe=27b9651432) | Sep 27, 2022 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [1b2f7b8972](https://linux-hardware.org/?probe=1b2f7b8972) | Sep 27, 2022 |
| ASUSTek       | TUF Gaming FX505DV          | Notebook    | [2154b531c9](https://linux-hardware.org/?probe=2154b531c9) | Sep 26, 2022 |
| System76      | Galago Pro                  | Notebook    | [6b2de473b7](https://linux-hardware.org/?probe=6b2de473b7) | Sep 26, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [dce9d30a10](https://linux-hardware.org/?probe=dce9d30a10) | Sep 26, 2022 |
| Gigabyte      | AORUS 7 SB                  | Notebook    | [3e8222ad7c](https://linux-hardware.org/?probe=3e8222ad7c) | Sep 26, 2022 |
| ASUSTek       | TUF Gaming FX505DV          | Notebook    | [6b3be4af70](https://linux-hardware.org/?probe=6b3be4af70) | Sep 26, 2022 |
| Dell          | G15 5511                    | Notebook    | [f960f38940](https://linux-hardware.org/?probe=f960f38940) | Sep 26, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [f61a736922](https://linux-hardware.org/?probe=f61a736922) | Sep 26, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [1ecfe379e7](https://linux-hardware.org/?probe=1ecfe379e7) | Sep 26, 2022 |
| Apple         | Mac-A369DDC4E67F1C45 iMa... | All in one  | [a96f37005a](https://linux-hardware.org/?probe=a96f37005a) | Sep 26, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | Notebook    | [6c0c9c0037](https://linux-hardware.org/?probe=6c0c9c0037) | Sep 25, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [479dfeae74](https://linux-hardware.org/?probe=479dfeae74) | Sep 25, 2022 |
| Lenovo        | Yoga 310-11IAP 80U2         | Convertible | [6c8a53f608](https://linux-hardware.org/?probe=6c8a53f608) | Sep 25, 2022 |
| MSI           | H170M PRO-VDH               | Desktop     | [f7254adff2](https://linux-hardware.org/?probe=f7254adff2) | Sep 25, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [93dd525100](https://linux-hardware.org/?probe=93dd525100) | Sep 25, 2022 |
| MSI           | MAG Z590 TORPEDO            | Desktop     | [cedbd8909f](https://linux-hardware.org/?probe=cedbd8909f) | Sep 25, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [66b5b65077](https://linux-hardware.org/?probe=66b5b65077) | Sep 25, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [05dc7a54c7](https://linux-hardware.org/?probe=05dc7a54c7) | Sep 25, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [a35dda8c10](https://linux-hardware.org/?probe=a35dda8c10) | Sep 25, 2022 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [33a0b663ea](https://linux-hardware.org/?probe=33a0b663ea) | Sep 25, 2022 |
| Lenovo        | Yoga 310-11IAP 80U2         | Convertible | [b598ecc4f8](https://linux-hardware.org/?probe=b598ecc4f8) | Sep 24, 2022 |
| HP            | Pavilion dv6                | Notebook    | [ae43d0bbce](https://linux-hardware.org/?probe=ae43d0bbce) | Sep 24, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [24b2810c64](https://linux-hardware.org/?probe=24b2810c64) | Sep 24, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [0299e4f7b1](https://linux-hardware.org/?probe=0299e4f7b1) | Sep 24, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [cad0f6f375](https://linux-hardware.org/?probe=cad0f6f375) | Sep 24, 2022 |
| MSI           | C236A WORKSTATION           | Desktop     | [67432a461e](https://linux-hardware.org/?probe=67432a461e) | Sep 24, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [91d179670c](https://linux-hardware.org/?probe=91d179670c) | Sep 23, 2022 |
| Acer          | TMP645-M                    | Notebook    | [83b27c389c](https://linux-hardware.org/?probe=83b27c389c) | Sep 23, 2022 |
| Dell          | 0KV62T A01                  | Desktop     | [d8d21241de](https://linux-hardware.org/?probe=d8d21241de) | Sep 23, 2022 |
| ASUSTek       | P6T                         | Desktop     | [612682c52d](https://linux-hardware.org/?probe=612682c52d) | Sep 23, 2022 |
| Dell          | Precision 7760              | Notebook    | [f47fe0314b](https://linux-hardware.org/?probe=f47fe0314b) | Sep 23, 2022 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [accc831d30](https://linux-hardware.org/?probe=accc831d30) | Sep 23, 2022 |
| Lenovo        | ThinkPad E595 20NFA000AU    | Notebook    | [a01352810a](https://linux-hardware.org/?probe=a01352810a) | Sep 22, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen2... | Notebook    | [87a3d977b1](https://linux-hardware.org/?probe=87a3d977b1) | Sep 22, 2022 |
| Dell          | 09M8Y8 A01                  | Desktop     | [aa3088ed0e](https://linux-hardware.org/?probe=aa3088ed0e) | Sep 22, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [d97b8fc0ed](https://linux-hardware.org/?probe=d97b8fc0ed) | Sep 21, 2022 |
| ASRock        | Z690 Pro RS                 | Desktop     | [787589762f](https://linux-hardware.org/?probe=787589762f) | Sep 21, 2022 |
| Shuttle       | FS81                        | Desktop     | [4c1fb942aa](https://linux-hardware.org/?probe=4c1fb942aa) | Sep 20, 2022 |
| ASRock        | HM55-HT                     | Desktop     | [64fff8f065](https://linux-hardware.org/?probe=64fff8f065) | Sep 20, 2022 |
| ASUSTek       | Z97-AR                      | Desktop     | [5cf4494f07](https://linux-hardware.org/?probe=5cf4494f07) | Sep 20, 2022 |
| ASRock        | H610M-HDV/M.2               | Desktop     | [02a5a10d7a](https://linux-hardware.org/?probe=02a5a10d7a) | Sep 20, 2022 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [7c7043ad0f](https://linux-hardware.org/?probe=7c7043ad0f) | Sep 19, 2022 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [48d71b12fc](https://linux-hardware.org/?probe=48d71b12fc) | Sep 19, 2022 |
| Apple         | MacBookPro10,2              | Notebook    | [ecc3b7e71d](https://linux-hardware.org/?probe=ecc3b7e71d) | Sep 19, 2022 |
| MSI           | Z370-A PRO                  | Desktop     | [43fbf9fec9](https://linux-hardware.org/?probe=43fbf9fec9) | Sep 19, 2022 |
| MSI           | Z370-A PRO                  | Desktop     | [850e17ede5](https://linux-hardware.org/?probe=850e17ede5) | Sep 19, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [6c63c03b9f](https://linux-hardware.org/?probe=6c63c03b9f) | Sep 19, 2022 |
| ASUSTek       | 1005HA                      | Notebook    | [3b5d6a5b1d](https://linux-hardware.org/?probe=3b5d6a5b1d) | Sep 18, 2022 |
| ASUSTek       | 1005HA                      | Notebook    | [3b1ce0471e](https://linux-hardware.org/?probe=3b1ce0471e) | Sep 18, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [126b3ed209](https://linux-hardware.org/?probe=126b3ed209) | Sep 14, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [08c270ce3d](https://linux-hardware.org/?probe=08c270ce3d) | Sep 14, 2022 |
| Lenovo        | V310-15ISK 80SY             | Notebook    | [fbd66d36f4](https://linux-hardware.org/?probe=fbd66d36f4) | Sep 14, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [03ba2808d7](https://linux-hardware.org/?probe=03ba2808d7) | Sep 13, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [6121dfd67d](https://linux-hardware.org/?probe=6121dfd67d) | Sep 13, 2022 |
| HP            | ENVY 15                     | Notebook    | [fdb07294df](https://linux-hardware.org/?probe=fdb07294df) | Sep 13, 2022 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [ebd7ab6202](https://linux-hardware.org/?probe=ebd7ab6202) | Sep 12, 2022 |
| Inventec      | C CLASS A01                 | Desktop     | [613f741235](https://linux-hardware.org/?probe=613f741235) | Sep 12, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [491242ea90](https://linux-hardware.org/?probe=491242ea90) | Sep 11, 2022 |
| Inventec      | C CLASS A01                 | Desktop     | [21ae14e7a0](https://linux-hardware.org/?probe=21ae14e7a0) | Sep 11, 2022 |
| Inventec      | C CLASS A01                 | Desktop     | [3ddd0d7aa0](https://linux-hardware.org/?probe=3ddd0d7aa0) | Sep 11, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [c3ceb9c38b](https://linux-hardware.org/?probe=c3ceb9c38b) | Sep 11, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [d477c1084d](https://linux-hardware.org/?probe=d477c1084d) | Sep 10, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [2cb423c8e7](https://linux-hardware.org/?probe=2cb423c8e7) | Sep 10, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [1e8c2730c9](https://linux-hardware.org/?probe=1e8c2730c9) | Sep 10, 2022 |
| Acer          | Aspire A315-22              | Notebook    | [82058771f7](https://linux-hardware.org/?probe=82058771f7) | Sep 09, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [3c454664b0](https://linux-hardware.org/?probe=3c454664b0) | Sep 09, 2022 |
| Dell          | Latitude E7470              | Notebook    | [4a2f647549](https://linux-hardware.org/?probe=4a2f647549) | Sep 08, 2022 |
| ASRock        | J5040-ITX                   | Desktop     | [e36022370b](https://linux-hardware.org/?probe=e36022370b) | Sep 08, 2022 |
| Acer          | Aspire A315-22              | Notebook    | [49d54ac5c5](https://linux-hardware.org/?probe=49d54ac5c5) | Sep 07, 2022 |
| ASUSTek       | X99-E WS/USB                | Desktop     | [56357e3cc7](https://linux-hardware.org/?probe=56357e3cc7) | Sep 07, 2022 |
| ASUSTek       | X99-E WS/USB                | Desktop     | [3432790e95](https://linux-hardware.org/?probe=3432790e95) | Sep 07, 2022 |
| ASUSTek       | Z97-AR                      | Desktop     | [01dbdc3b29](https://linux-hardware.org/?probe=01dbdc3b29) | Sep 06, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [c1ca471555](https://linux-hardware.org/?probe=c1ca471555) | Sep 06, 2022 |
| Gigabyte      | Z690 AERO G DDR4            | Desktop     | [ccd383a106](https://linux-hardware.org/?probe=ccd383a106) | Sep 05, 2022 |
| HP            | Pavilion dv6500             | Notebook    | [c37bace401](https://linux-hardware.org/?probe=c37bace401) | Sep 05, 2022 |
| Gigabyte      | AB350M-HD3-CF se1           | Desktop     | [0859dbdb1c](https://linux-hardware.org/?probe=0859dbdb1c) | Sep 04, 2022 |
| Dell          | 0D24M8 A01                  | Desktop     | [a746f6faa6](https://linux-hardware.org/?probe=a746f6faa6) | Sep 04, 2022 |
| HP            | 2AF3                        | Desktop     | [58eae39fe2](https://linux-hardware.org/?probe=58eae39fe2) | Sep 03, 2022 |
| Gigabyte      | Z590 AORUS ELITE AX         | Desktop     | [e03d937610](https://linux-hardware.org/?probe=e03d937610) | Sep 02, 2022 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [a1b5555512](https://linux-hardware.org/?probe=a1b5555512) | Sep 02, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [0a1de8a406](https://linux-hardware.org/?probe=0a1de8a406) | Sep 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [ac65980e25](https://linux-hardware.org/?probe=ac65980e25) | Sep 02, 2022 |
| ASUSTek       | PRIME B250M-PLUS            | Desktop     | [888ed47bbe](https://linux-hardware.org/?probe=888ed47bbe) | Sep 02, 2022 |
| Dell          | XPS 13 9350                 | Notebook    | [dc37712dfc](https://linux-hardware.org/?probe=dc37712dfc) | Sep 02, 2022 |
| Dell          | 0WPG9H A00                  | All in one  | [67aeed6eb1](https://linux-hardware.org/?probe=67aeed6eb1) | Sep 01, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [2cf98644bc](https://linux-hardware.org/?probe=2cf98644bc) | Sep 01, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [8ac8531142](https://linux-hardware.org/?probe=8ac8531142) | Sep 01, 2022 |
| Toshiba       | Satellite C850              | Notebook    | [6cf6d8fca8](https://linux-hardware.org/?probe=6cf6d8fca8) | Sep 01, 2022 |
| ASUSTek       | X550CC                      | Notebook    | [21f3eb8b1d](https://linux-hardware.org/?probe=21f3eb8b1d) | Sep 01, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [6e245e4c63](https://linux-hardware.org/?probe=6e245e4c63) | Sep 01, 2022 |
| HP            | Notebook                    | Notebook    | [ee135c3930](https://linux-hardware.org/?probe=ee135c3930) | Aug 31, 2022 |
| Toshiba       | Satellite C850              | Notebook    | [5d7cb36794](https://linux-hardware.org/?probe=5d7cb36794) | Aug 31, 2022 |
| Lenovo        | MAHOBAY                     | Desktop     | [53af4f5de7](https://linux-hardware.org/?probe=53af4f5de7) | Aug 30, 2022 |
| HP            | EliteBook 830 G6            | Notebook    | [897046248f](https://linux-hardware.org/?probe=897046248f) | Aug 30, 2022 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [ce25a77e25](https://linux-hardware.org/?probe=ce25a77e25) | Aug 29, 2022 |
| HP            | EW7-I7D22875GR1             | Notebook    | [307b75624e](https://linux-hardware.org/?probe=307b75624e) | Aug 29, 2022 |
| ASRock        | Z170 Pro4                   | Desktop     | [eaa574481f](https://linux-hardware.org/?probe=eaa574481f) | Aug 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [fd4ab67b77](https://linux-hardware.org/?probe=fd4ab67b77) | Aug 29, 2022 |
| Toshiba       | Satellite L850              | Notebook    | [fe1480794c](https://linux-hardware.org/?probe=fe1480794c) | Aug 29, 2022 |
| IT Channel... | NH5xAx                      | Notebook    | [66573b4b48](https://linux-hardware.org/?probe=66573b4b48) | Aug 28, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [a0f47aaaa7](https://linux-hardware.org/?probe=a0f47aaaa7) | Aug 28, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [459c7c1eee](https://linux-hardware.org/?probe=459c7c1eee) | Aug 27, 2022 |
| ASUSTek       | Z170-K                      | Desktop     | [137641269c](https://linux-hardware.org/?probe=137641269c) | Aug 27, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [f30320f76e](https://linux-hardware.org/?probe=f30320f76e) | Aug 27, 2022 |
| Acer          | Aspire V5-531               | Notebook    | [75b841b0b8](https://linux-hardware.org/?probe=75b841b0b8) | Aug 26, 2022 |
| HP            | Laptop 15-da1xxx            | Notebook    | [51e23209a4](https://linux-hardware.org/?probe=51e23209a4) | Aug 26, 2022 |
| Dell          | Latitude 5300               | Notebook    | [f336b3aeaf](https://linux-hardware.org/?probe=f336b3aeaf) | Aug 26, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [f37ee1975e](https://linux-hardware.org/?probe=f37ee1975e) | Aug 26, 2022 |
| Lenovo        | Yoga S940-14IWL 81Q7        | Notebook    | [416e5db831](https://linux-hardware.org/?probe=416e5db831) | Aug 26, 2022 |
| Lenovo        | 1046 NO DPK                 | Desktop     | [e21e07827d](https://linux-hardware.org/?probe=e21e07827d) | Aug 26, 2022 |
| Acer          | Aspire V5-531               | Notebook    | [4ae228e219](https://linux-hardware.org/?probe=4ae228e219) | Aug 25, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [2388b95ce9](https://linux-hardware.org/?probe=2388b95ce9) | Aug 25, 2022 |
| ASUSTek       | Z97-AR                      | Desktop     | [a766ce2d5a](https://linux-hardware.org/?probe=a766ce2d5a) | Aug 24, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [fda9abd530](https://linux-hardware.org/?probe=fda9abd530) | Aug 24, 2022 |
| HP            | 1905                        | Desktop     | [6693a2b3c7](https://linux-hardware.org/?probe=6693a2b3c7) | Aug 24, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [18102e8a9a](https://linux-hardware.org/?probe=18102e8a9a) | Aug 24, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [738a69419b](https://linux-hardware.org/?probe=738a69419b) | Aug 24, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [d609bf3253](https://linux-hardware.org/?probe=d609bf3253) | Aug 24, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [7dae220687](https://linux-hardware.org/?probe=7dae220687) | Aug 23, 2022 |
| Alienware     | 15 R4                       | Notebook    | [f53260e0c2](https://linux-hardware.org/?probe=f53260e0c2) | Aug 23, 2022 |
| Dell          | Inspiron 5770               | Notebook    | [49314a1dfe](https://linux-hardware.org/?probe=49314a1dfe) | Aug 23, 2022 |
| Apple         | MacBook9,1                  | Notebook    | [a6726b8439](https://linux-hardware.org/?probe=a6726b8439) | Aug 22, 2022 |
| Apple         | MacBook9,1                  | Notebook    | [aff9259c2c](https://linux-hardware.org/?probe=aff9259c2c) | Aug 22, 2022 |
| Samsung       | 550P5C/550P7C               | Notebook    | [75f94f8fa5](https://linux-hardware.org/?probe=75f94f8fa5) | Aug 21, 2022 |
| ASRock        | AD2700-ITX                  | Desktop     | [4be47e3738](https://linux-hardware.org/?probe=4be47e3738) | Aug 21, 2022 |
| Samsung       | 550P5C/550P7C               | Notebook    | [c369daf6b0](https://linux-hardware.org/?probe=c369daf6b0) | Aug 21, 2022 |
| ASRock        | Z77 Extreme6                | Desktop     | [660091e5bb](https://linux-hardware.org/?probe=660091e5bb) | Aug 20, 2022 |
| Google        | Teemo                       | Desktop     | [4cc9295e6d](https://linux-hardware.org/?probe=4cc9295e6d) | Aug 20, 2022 |
| ASUSTek       | ROG Flow Z13 GZ301ZE_GZ3... | Tablet      | [7a8fee05aa](https://linux-hardware.org/?probe=7a8fee05aa) | Aug 20, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [c9738d69e9](https://linux-hardware.org/?probe=c9738d69e9) | Aug 20, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [9bfc03d98e](https://linux-hardware.org/?probe=9bfc03d98e) | Aug 20, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [ed2076bba5](https://linux-hardware.org/?probe=ed2076bba5) | Aug 20, 2022 |
| ASUSTek       | X756UAK                     | Notebook    | [6db3b2a7bc](https://linux-hardware.org/?probe=6db3b2a7bc) | Aug 20, 2022 |
| Dell          | G3 3779                     | Notebook    | [a2b721ca15](https://linux-hardware.org/?probe=a2b721ca15) | Aug 19, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [9e6a3e80b4](https://linux-hardware.org/?probe=9e6a3e80b4) | Aug 19, 2022 |
| Dell          | Inspiron M5010              | Notebook    | [266f9fc41d](https://linux-hardware.org/?probe=266f9fc41d) | Aug 19, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [e500790878](https://linux-hardware.org/?probe=e500790878) | Aug 18, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [1e4e125d11](https://linux-hardware.org/?probe=1e4e125d11) | Aug 17, 2022 |
| Lenovo        | ThinkPad T480s 20L70044A... | Notebook    | [f90559618b](https://linux-hardware.org/?probe=f90559618b) | Aug 17, 2022 |
| ASUSTek       | P8B75-M LX                  | Desktop     | [1efeb7be2c](https://linux-hardware.org/?probe=1efeb7be2c) | Aug 17, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [26f646cca0](https://linux-hardware.org/?probe=26f646cca0) | Aug 17, 2022 |
| Gigabyte      | D525TUD                     | Desktop     | [125fdc6af1](https://linux-hardware.org/?probe=125fdc6af1) | Aug 17, 2022 |
| Dell          | 0WPG9H A00                  | All in one  | [87ba9f4be1](https://linux-hardware.org/?probe=87ba9f4be1) | Aug 17, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [98b5311ef6](https://linux-hardware.org/?probe=98b5311ef6) | Aug 17, 2022 |
| Gigabyte      | D525TUD                     | Desktop     | [e68748c0f1](https://linux-hardware.org/?probe=e68748c0f1) | Aug 16, 2022 |
| Gigabyte      | B660M DS3H AX DDR4          | Desktop     | [171a797c22](https://linux-hardware.org/?probe=171a797c22) | Aug 16, 2022 |
| Gigabyte      | B660M DS3H AX DDR4          | Desktop     | [f882fcbe3a](https://linux-hardware.org/?probe=f882fcbe3a) | Aug 16, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [8072e15459](https://linux-hardware.org/?probe=8072e15459) | Aug 15, 2022 |
| Lenovo        | ThinkPad X131e 33672K5      | Notebook    | [e32eeecfaa](https://linux-hardware.org/?probe=e32eeecfaa) | Aug 15, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [20d9ba44b5](https://linux-hardware.org/?probe=20d9ba44b5) | Aug 15, 2022 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [be0b70efdb](https://linux-hardware.org/?probe=be0b70efdb) | Aug 15, 2022 |
| MSI           | H61M-P20                    | Desktop     | [9adc2fa427](https://linux-hardware.org/?probe=9adc2fa427) | Aug 15, 2022 |
| HP            | 1493                        | Desktop     | [e5d0f16bbc](https://linux-hardware.org/?probe=e5d0f16bbc) | Aug 14, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [2c210a5825](https://linux-hardware.org/?probe=2c210a5825) | Aug 14, 2022 |
| Microsoft     | Surface Pro 6               | Tablet      | [dc9013cc44](https://linux-hardware.org/?probe=dc9013cc44) | Aug 14, 2022 |
| ASRock        | AB350 Gaming K4             | Desktop     | [8a6141848a](https://linux-hardware.org/?probe=8a6141848a) | Aug 13, 2022 |
| Toshiba       | Satellite L500              | Notebook    | [0d58c17039](https://linux-hardware.org/?probe=0d58c17039) | Aug 13, 2022 |
| MSI           | H61M-P20                    | Desktop     | [acc2520058](https://linux-hardware.org/?probe=acc2520058) | Aug 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [26c131aca1](https://linux-hardware.org/?probe=26c131aca1) | Aug 13, 2022 |
| Gigabyte      | EP35C-DS3R                  | Desktop     | [762d78160d](https://linux-hardware.org/?probe=762d78160d) | Aug 12, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | Notebook    | [662f0801b7](https://linux-hardware.org/?probe=662f0801b7) | Aug 12, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [166edbd7db](https://linux-hardware.org/?probe=166edbd7db) | Aug 12, 2022 |
| Dell          | Latitude 6430U              | Notebook    | [d21ca8c2e6](https://linux-hardware.org/?probe=d21ca8c2e6) | Aug 11, 2022 |
| Gigabyte      | Z87M-D3HP                   | Desktop     | [b6612680e2](https://linux-hardware.org/?probe=b6612680e2) | Aug 11, 2022 |
| ASRock        | X58 Extreme3                | Desktop     | [81f68d4fc7](https://linux-hardware.org/?probe=81f68d4fc7) | Aug 10, 2022 |
| Unknown       | Unknown                     | Desktop     | [dc354e0b4f](https://linux-hardware.org/?probe=dc354e0b4f) | Aug 10, 2022 |
| ASUSTek       | TUF B360-PRO GAMING         | Desktop     | [62d813423e](https://linux-hardware.org/?probe=62d813423e) | Aug 10, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [e74a95c4d9](https://linux-hardware.org/?probe=e74a95c4d9) | Aug 09, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [42d32cdfda](https://linux-hardware.org/?probe=42d32cdfda) | Aug 09, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [7f1e38b57b](https://linux-hardware.org/?probe=7f1e38b57b) | Aug 07, 2022 |
| HP            | 2B21 A01                    | All in one  | [aba1a53f52](https://linux-hardware.org/?probe=aba1a53f52) | Aug 07, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [6a73917b78](https://linux-hardware.org/?probe=6a73917b78) | Aug 07, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [db3d9f24c6](https://linux-hardware.org/?probe=db3d9f24c6) | Aug 07, 2022 |
| ASUSTek       | ET2701I-W8                  | Desktop     | [5f9c4b50db](https://linux-hardware.org/?probe=5f9c4b50db) | Aug 07, 2022 |
| Unknown       | Unknown                     | Soc         | [9efd347024](https://linux-hardware.org/?probe=9efd347024) | Aug 06, 2022 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [fd6cf872ae](https://linux-hardware.org/?probe=fd6cf872ae) | Aug 06, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [1798c25088](https://linux-hardware.org/?probe=1798c25088) | Aug 05, 2022 |
| HP            | ProBook 430 G5              | Notebook    | [72a09e7b69](https://linux-hardware.org/?probe=72a09e7b69) | Aug 05, 2022 |
| Lenovo        | XiaoXinPro 16 ARH7 82SN     | Notebook    | [abaec227ae](https://linux-hardware.org/?probe=abaec227ae) | Aug 05, 2022 |
| Lenovo        | XiaoXinPro 16 ARH7 82SN     | Notebook    | [a1effa04c3](https://linux-hardware.org/?probe=a1effa04c3) | Aug 05, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [209cd4bc66](https://linux-hardware.org/?probe=209cd4bc66) | Aug 05, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [caa404d4c6](https://linux-hardware.org/?probe=caa404d4c6) | Aug 05, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [8b737740c3](https://linux-hardware.org/?probe=8b737740c3) | Aug 05, 2022 |
| Gigabyte      | H61M-D2-B3                  | Desktop     | [e477bf9f83](https://linux-hardware.org/?probe=e477bf9f83) | Aug 05, 2022 |
| Acer          | Aspire A515-55              | Notebook    | [3ef0714d78](https://linux-hardware.org/?probe=3ef0714d78) | Aug 04, 2022 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [360447806b](https://linux-hardware.org/?probe=360447806b) | Aug 04, 2022 |
| Dell          | 06WXJT A02                  | Server      | [424b1059df](https://linux-hardware.org/?probe=424b1059df) | Aug 03, 2022 |
| Toshiba       | Satellite Pro L670          | Notebook    | [302749341d](https://linux-hardware.org/?probe=302749341d) | Aug 03, 2022 |
| Lenovo        | 3102                        | Desktop     | [73e0fee2bc](https://linux-hardware.org/?probe=73e0fee2bc) | Aug 03, 2022 |
| Dell          | 06WXJT A07                  | Server      | [e0b1ede266](https://linux-hardware.org/?probe=e0b1ede266) | Aug 03, 2022 |
| Dell          | 06WXJT A02                  | Server      | [fcf7baab04](https://linux-hardware.org/?probe=fcf7baab04) | Aug 03, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [713884d2c8](https://linux-hardware.org/?probe=713884d2c8) | Aug 03, 2022 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [b81c8578b9](https://linux-hardware.org/?probe=b81c8578b9) | Aug 03, 2022 |
| Dell          | XPS 9320                    | Notebook    | [9b24b29553](https://linux-hardware.org/?probe=9b24b29553) | Aug 03, 2022 |
| HP            | ProLiant DL380p Gen8        | Server      | [63553d673b](https://linux-hardware.org/?probe=63553d673b) | Aug 03, 2022 |
| Toshiba       | Satellite Pro L670          | Notebook    | [e6189ba78c](https://linux-hardware.org/?probe=e6189ba78c) | Aug 02, 2022 |
| Hardkernel    | ODROID-C4                   | Soc         | [85ed0f33f0](https://linux-hardware.org/?probe=85ed0f33f0) | Aug 02, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IHU5 8... | Notebook    | [a67d881d6f](https://linux-hardware.org/?probe=a67d881d6f) | Aug 02, 2022 |
| HP            | EliteBook 2570p             | Notebook    | [b352b7e051](https://linux-hardware.org/?probe=b352b7e051) | Aug 02, 2022 |
| Fanless Mi... | Rev GMLR1                   | Mini pc     | [2de5d5cf8a](https://linux-hardware.org/?probe=2de5d5cf8a) | Aug 02, 2022 |
| Apple         | MacBook9,1                  | Notebook    | [77687a9bac](https://linux-hardware.org/?probe=77687a9bac) | Aug 02, 2022 |
| ASRock        | X370 Gaming-ITX/ac          | Desktop     | [6127d6e7a3](https://linux-hardware.org/?probe=6127d6e7a3) | Aug 02, 2022 |
| ASRock        | Z390 Extreme4               | Desktop     | [9983a0cc64](https://linux-hardware.org/?probe=9983a0cc64) | Aug 02, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [dcccfd1beb](https://linux-hardware.org/?probe=dcccfd1beb) | Aug 01, 2022 |
| QIYIDA        | X99-H9 V2.0                 | Desktop     | [e1fa8ab12b](https://linux-hardware.org/?probe=e1fa8ab12b) | Aug 01, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [370b872aa5](https://linux-hardware.org/?probe=370b872aa5) | Aug 01, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [81c46b891f](https://linux-hardware.org/?probe=81c46b891f) | Aug 01, 2022 |
| ASUSTek       | P7P55D-E PRO                | Desktop     | [d58be7b6d1](https://linux-hardware.org/?probe=d58be7b6d1) | Aug 01, 2022 |
| Unknown       | Unknown                     | Soc         | [9ebddaa953](https://linux-hardware.org/?probe=9ebddaa953) | Jul 31, 2022 |
| ASRock        | Z170 Pro4                   | Desktop     | [e8dba6ab7e](https://linux-hardware.org/?probe=e8dba6ab7e) | Jul 31, 2022 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [f6a106d6df](https://linux-hardware.org/?probe=f6a106d6df) | Jul 31, 2022 |
| Intel         | NUC7i5BNB J31144-302        | Mini pc     | [638275ad97](https://linux-hardware.org/?probe=638275ad97) | Jul 31, 2022 |
| HP            | 82F2                        | Desktop     | [0c2d091c2e](https://linux-hardware.org/?probe=0c2d091c2e) | Jul 31, 2022 |
| Acer          | ConceptD CN315-71P          | Notebook    | [c7ed484a1f](https://linux-hardware.org/?probe=c7ed484a1f) | Jul 30, 2022 |
| Dell          | Inspiron M5010              | Notebook    | [bd4cf45b33](https://linux-hardware.org/?probe=bd4cf45b33) | Jul 30, 2022 |
| Intel         | NUC6i5SYB H81131-505        | Mini pc     | [51695dd3ea](https://linux-hardware.org/?probe=51695dd3ea) | Jul 29, 2022 |
| Intel         | NUC6i5SYB H81131-505        | Mini pc     | [2381ee35c0](https://linux-hardware.org/?probe=2381ee35c0) | Jul 29, 2022 |
| ASRock        | Z170 Pro4                   | Desktop     | [73c8bc2ae1](https://linux-hardware.org/?probe=73c8bc2ae1) | Jul 28, 2022 |
| Lenovo        | 3717 SDK0R32862 WIN 3258... | Desktop     | [757ba0f252](https://linux-hardware.org/?probe=757ba0f252) | Jul 28, 2022 |
| Gigabyte      | B450M H                     | Desktop     | [1357e3b3d3](https://linux-hardware.org/?probe=1357e3b3d3) | Jul 28, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [e42501aacb](https://linux-hardware.org/?probe=e42501aacb) | Jul 28, 2022 |
| ASUSTek       | X555YA                      | Notebook    | [ddd00fbeea](https://linux-hardware.org/?probe=ddd00fbeea) | Jul 28, 2022 |
| Unknown       | HX90                        | Desktop     | [1594710372](https://linux-hardware.org/?probe=1594710372) | Jul 28, 2022 |
| Dell          | Latitude E7250              | Notebook    | [26a8591f1d](https://linux-hardware.org/?probe=26a8591f1d) | Jul 27, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [761563e485](https://linux-hardware.org/?probe=761563e485) | Jul 27, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [5e7b9f2b14](https://linux-hardware.org/?probe=5e7b9f2b14) | Jul 26, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [331a99ef9a](https://linux-hardware.org/?probe=331a99ef9a) | Jul 26, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [1f3433b9e1](https://linux-hardware.org/?probe=1f3433b9e1) | Jul 26, 2022 |
| ASRock        | Z170 Pro4                   | Desktop     | [876c60188f](https://linux-hardware.org/?probe=876c60188f) | Jul 26, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [050aa57cb4](https://linux-hardware.org/?probe=050aa57cb4) | Jul 26, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Australia/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 430       | 13.09%  |
| Ubuntu 18.04       | 173       | 5.27%   |
| Ubuntu 22.04       | 112       | 3.41%   |
| Debian 11          | 87        | 2.65%   |
| Pop!_OS 22.04      | 75        | 2.28%   |
| OpenMandriva 4.3   | 73        | 2.22%   |
| KDE neon 20.04     | 70        | 2.13%   |
| Linux Mint 20.3    | 68        | 2.07%   |
| Fedora 36          | 65        | 1.98%   |
| Pop!_OS 21.04      | 64        | 1.95%   |
| Zorin 16           | 62        | 1.89%   |
| Arch Rolling       | 59        | 1.8%    |
| OpenMandriva 4.2   | 56        | 1.7%    |
| Pop!_OS 20.04      | 51        | 1.55%   |
| Pop!_OS 20.10      | 48        | 1.46%   |
| Linux Mint 20.2    | 47        | 1.43%   |
| Ubuntu 21.10       | 46        | 1.4%    |
| Fedora 37          | 44        | 1.34%   |
| Arch               | 44        | 1.34%   |
| Linux Mint 20.1    | 42        | 1.28%   |
| Fedora 35          | 42        | 1.28%   |
| Ubuntu 19.04       | 41        | 1.25%   |
| Manjaro            | 41        | 1.25%   |
| Fedora 33          | 41        | 1.25%   |
| Ubuntu 20.10       | 39        | 1.19%   |
| Fedora 34          | 38        | 1.16%   |
| Ubuntu 21.04       | 37        | 1.13%   |
| Ubuntu 19.10       | 37        | 1.13%   |
| Linux Mint 19.3    | 35        | 1.07%   |
| ArcoLinux Rolling  | 33        | 1%      |
| Linux Mint 20      | 32        | 0.97%   |
| OpenMandriva 23.01 | 31        | 0.94%   |
| Pop!_OS 21.10      | 30        | 0.91%   |
| Xubuntu 20.04      | 29        | 0.88%   |
| Xubuntu 18.04      | 29        | 0.88%   |
| Fedora 32          | 29        | 0.88%   |
| Ubuntu 22.10       | 28        | 0.85%   |
| Linux Mint 21.1    | 28        | 0.85%   |
| Ubuntu 18.10       | 26        | 0.79%   |
| Linux Mint 21      | 26        | 0.79%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 927       | 30.17%  |
| Linux Mint    | 288       | 9.37%   |
| Pop!_OS       | 255       | 8.3%    |
| Fedora        | 232       | 7.55%   |
| OpenMandriva  | 186       | 6.05%   |
| Debian        | 139       | 4.52%   |
| Arch          | 102       | 3.32%   |
| Zorin         | 95        | 3.09%   |
| Manjaro       | 92        | 2.99%   |
| KDE neon      | 89        | 2.9%    |
| Xubuntu       | 80        | 2.6%    |
| Kubuntu       | 67        | 2.18%   |
| Gentoo        | 34        | 1.11%   |
| Elementary    | 34        | 1.11%   |
| ArcoLinux     | 34        | 1.11%   |
| ROSA          | 29        | 0.94%   |
| Kali          | 27        | 0.88%   |
| Ubuntu MATE   | 26        | 0.85%   |
| openSUSE      | 25        | 0.81%   |
| Clear Linux   | 24        | 0.78%   |
| ClearOS       | 23        | 0.75%   |
| Lubuntu       | 19        | 0.62%   |
| BlackPanther  | 18        | 0.59%   |
| Endless       | 17        | 0.55%   |
| EndeavourOS   | 17        | 0.55%   |
| Ubuntu Unity  | 14        | 0.46%   |
| MX            | 13        | 0.42%   |
| LMDE          | 13        | 0.42%   |
| CentOS        | 11        | 0.36%   |
| SteamOS       | 10        | 0.33%   |
| Parrot        | 10        | 0.33%   |
| Ubuntu Budgie | 9         | 0.29%   |
| Raspbian      | 9         | 0.29%   |
| Feren OS      | 8         | 0.26%   |
| LinuxFX       | 7         | 0.23%   |
| Rocky Linux   | 6         | 0.2%    |
| Reborn OS     | 6         | 0.2%    |
| Solus         | 5         | 0.16%   |
| Manjaro-ARM   | 5         | 0.16%   |
| Garuda Linux  | 5         | 0.16%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 70        | 1.84%   |
| 5.4.0-42-generic         | 64        | 1.68%   |
| 5.10.14-desktop-1omv4002 | 52        | 1.36%   |
| 5.4.0-40-generic         | 30        | 0.79%   |
| 5.11.0-7620-generic      | 30        | 0.79%   |
| 6.1.1-desktop-1omv2290   | 29        | 0.76%   |
| 5.4.0-58-generic         | 29        | 0.76%   |
| 5.15.0-56-generic        | 28        | 0.73%   |
| 5.4.0-48-generic         | 27        | 0.71%   |
| 5.4.0-26-generic         | 24        | 0.63%   |
| 5.3.0-46-generic         | 24        | 0.63%   |
| 5.15.0-52-generic        | 24        | 0.63%   |
| 5.4.0-52-generic         | 23        | 0.6%    |
| 5.11.0-37-generic        | 23        | 0.6%    |
| 5.4.0-29-generic         | 22        | 0.58%   |
| 5.3.0-40-generic         | 22        | 0.58%   |
| 5.3.0-28-generic         | 22        | 0.58%   |
| 5.15.0-58-generic        | 22        | 0.58%   |
| 5.17.5-76051705-generic  | 21        | 0.55%   |
| 5.15.0-48-generic        | 21        | 0.55%   |
| 5.11.0-27-generic        | 20        | 0.52%   |
| 5.4.0-7634-generic       | 19        | 0.5%    |
| 5.15.0-46-generic        | 19        | 0.5%    |
| 5.4.0-47-generic         | 18        | 0.47%   |
| 5.4.0-74-generic         | 17        | 0.45%   |
| 5.13.0-7620-generic      | 17        | 0.45%   |
| 5.8.0-7630-generic       | 16        | 0.42%   |
| 5.8.0-44-generic         | 16        | 0.42%   |
| 5.4.0-91-generic         | 16        | 0.42%   |
| 5.4.0-65-generic         | 16        | 0.42%   |
| 5.13.0-40-generic        | 16        | 0.42%   |
| 4.15.0-99-generic        | 16        | 0.42%   |
| 6.0.12-76060006-generic  | 15        | 0.39%   |
| 5.8.0-7642-generic       | 15        | 0.39%   |
| 5.8.0-63-generic         | 15        | 0.39%   |
| 5.4.0-66-generic         | 15        | 0.39%   |
| 5.4.0-54-generic         | 15        | 0.39%   |
| 5.15.0-43-generic        | 15        | 0.39%   |
| 5.15.0-41-generic        | 15        | 0.39%   |
| 5.8.0-55-generic         | 14        | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 560       | 15.95%  |
| 5.15.0  | 243       | 6.92%   |
| 5.11.0  | 228       | 6.49%   |
| 5.13.0  | 189       | 5.38%   |
| 5.8.0   | 181       | 5.15%   |
| 4.15.0  | 161       | 4.58%   |
| 5.3.0   | 128       | 3.64%   |
| 5.10.0  | 88        | 2.51%   |
| 5.0.0   | 86        | 2.45%   |
| 5.19.0  | 74        | 2.11%   |
| 5.16.7  | 71        | 2.02%   |
| 4.18.0  | 62        | 1.77%   |
| 5.10.14 | 52        | 1.48%   |
| 6.1.1   | 36        | 1.03%   |
| 4.19.0  | 35        | 1%      |
| 5.17.5  | 31        | 0.88%   |
| 3.10.0  | 30        | 0.85%   |
| 6.0.12  | 21        | 0.6%    |
| 6.0.0   | 16        | 0.46%   |
| 5.18.0  | 14        | 0.4%    |
| 5.16.11 | 14        | 0.4%    |
| 5.18.10 | 13        | 0.37%   |
| 5.16.0  | 13        | 0.37%   |
| 4.4.0   | 13        | 0.37%   |
| 6.0.7   | 12        | 0.34%   |
| 5.14.0  | 12        | 0.34%   |
| 5.17.0  | 11        | 0.31%   |
| 4.18.16 | 11        | 0.31%   |
| 6.0.6   | 10        | 0.28%   |
| 5.9.16  | 10        | 0.28%   |
| 5.6.14  | 10        | 0.28%   |
| 5.18.12 | 10        | 0.28%   |
| 5.15.11 | 10        | 0.28%   |
| 5.13.13 | 10        | 0.28%   |
| 5.11.12 | 10        | 0.28%   |
| 4.9.60  | 10        | 0.28%   |
| 5.19.16 | 9         | 0.26%   |
| 5.16.19 | 9         | 0.26%   |
| 5.13.12 | 9         | 0.26%   |
| 5.12.4  | 9         | 0.26%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 611       | 17.91%  |
| 5.15    | 344       | 10.08%  |
| 5.11    | 267       | 7.83%   |
| 5.13    | 235       | 6.89%   |
| 5.8     | 228       | 6.68%   |
| 5.10    | 202       | 5.92%   |
| 4.15    | 161       | 4.72%   |
| 5.16    | 153       | 4.48%   |
| 5.3     | 143       | 4.19%   |
| 5.19    | 123       | 3.6%    |
| 6.0     | 99        | 2.9%    |
| 6.1     | 96        | 2.81%   |
| 5.0     | 95        | 2.78%   |
| 5.17    | 83        | 2.43%   |
| 5.18    | 79        | 2.32%   |
| 4.18    | 75        | 2.2%    |
| 5.12    | 46        | 1.35%   |
| 5.6     | 45        | 1.32%   |
| 4.19    | 45        | 1.32%   |
| 5.14    | 44        | 1.29%   |
| 5.9     | 38        | 1.11%   |
| 4.9     | 30        | 0.88%   |
| 3.10    | 30        | 0.88%   |
| 6.2     | 26        | 0.76%   |
| 5.5     | 26        | 0.76%   |
| 5.7     | 25        | 0.73%   |
| 5.2     | 17        | 0.5%    |
| 4.4     | 14        | 0.41%   |
| 5.1     | 9         | 0.26%   |
| 4.1     | 4         | 0.12%   |
| 4.20    | 3         | 0.09%   |
| 4.14    | 3         | 0.09%   |
| 4.13    | 3         | 0.09%   |
| 3.16    | 2         | 0.06%   |
| 5       | 1         | 0.03%   |
| 4.8     | 1         | 0.03%   |
| 4.17    | 1         | 0.03%   |
| 4.16    | 1         | 0.03%   |
| 4.11    | 1         | 0.03%   |
| 4.10    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 2829      | 96.78%  |
| i686    | 48        | 1.64%   |
| aarch64 | 28        | 0.96%   |
| armv7l  | 12        | 0.41%   |
| riscv64 | 2         | 0.07%   |
| i586    | 2         | 0.07%   |
| armv6l  | 1         | 0.03%   |
| Unknown | 1         | 0.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 1344      | 43.41%  |
| KDE5             | 477       | 15.41%  |
| Unknown          | 382       | 12.34%  |
| X-Cinnamon       | 240       | 7.75%   |
| XFCE             | 214       | 6.91%   |
| KDE              | 100       | 3.23%   |
| MATE             | 94        | 3.04%   |
| Cinnamon         | 56        | 1.81%   |
| Pantheon         | 32        | 1.03%   |
| LXQt             | 22        | 0.71%   |
| Unity            | 19        | 0.61%   |
| LXDE             | 18        | 0.58%   |
| KDE4             | 18        | 0.58%   |
| Budgie           | 17        | 0.55%   |
| i3               | 15        | 0.48%   |
| Deepin           | 7         | 0.23%   |
| awesome          | 7         | 0.23%   |
| Openbox          | 6         | 0.19%   |
| GNOME Classic    | 5         | 0.16%   |
| GNOME Flashback  | 4         | 0.13%   |
| xmonad           | 3         | 0.1%    |
| qtile            | 2         | 0.06%   |
| DWM              | 2         | 0.06%   |
| Trinity          | 1         | 0.03%   |
| sway             | 1         | 0.03%   |
| pop              | 1         | 0.03%   |
| Phosh:GNOME      | 1         | 0.03%   |
| lightdm-xsession | 1         | 0.03%   |
| LeftWM           | 1         | 0.03%   |
| icewm            | 1         | 0.03%   |
| Hyprland         | 1         | 0.03%   |
| GNUstep          | 1         | 0.03%   |
| dusk             | 1         | 0.03%   |
| BunsenLabs       | 1         | 0.03%   |
| bspwm            | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 2344      | 77.33%  |
| Wayland | 399       | 13.16%  |
| Unknown | 174       | 5.74%   |
| Tty     | 113       | 3.73%   |
| Web     | 1         | 0.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1659      | 54.46%  |
| SDDM    | 411       | 13.49%  |
| GDM     | 324       | 10.64%  |
| LightDM | 290       | 9.52%   |
| GDM3    | 242       | 7.94%   |
| TDM     | 85        | 2.79%   |
| KDM     | 17        | 0.56%   |
| SLiM    | 6         | 0.2%    |
| LXDM    | 5         | 0.16%   |
| XDM     | 4         | 0.13%   |
| Ly      | 2         | 0.07%   |
| GREETD  | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang         | Computers | Percent |
|--------------|-----------|---------|
| en_AU        | 2131      | 70.52%  |
| en_US        | 438       | 14.49%  |
| Unknown      | 321       | 10.62%  |
| C            | 70        | 2.32%   |
| en_GB        | 41        | 1.36%   |
| C.UTF8       | 6         | 0.2%    |
| de_DE        | 3         | 0.1%    |
| zh_CN        | 2         | 0.07%   |
| en_CA        | 2         | 0.07%   |
| ru_RU        | 1         | 0.03%   |
| POSIX        | 1         | 0.03%   |
| it_IT        | 1         | 0.03%   |
| fr_FR        | 1         | 0.03%   |
| es_ES        | 1         | 0.03%   |
| en_IN        | 1         | 0.03%   |
| en_GB.UTF-12 | 1         | 0.03%   |
| en_AU.UFT-8  | 1         | 0.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 1543      | 51.55%  |
| EFI  | 1450      | 48.45%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 2265      | 75.45%  |
| Btrfs   | 266       | 8.86%   |
| Overlay | 218       | 7.26%   |
| Unknown | 100       | 3.33%   |
| Xfs     | 80        | 2.66%   |
| Zfs     | 44        | 1.47%   |
| Ext2    | 10        | 0.33%   |
| Tmpfs   | 5         | 0.17%   |
| Ext3    | 5         | 0.17%   |
| XXXXXXX | 4         | 0.13%   |
| F2fs    | 3         | 0.1%    |
| Jfs     | 1         | 0.03%   |
| Aufs    | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1716      | 57.14%  |
| GPT     | 989       | 32.93%  |
| MBR     | 298       | 9.92%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2516      | 84.09%  |
| Yes       | 476       | 15.91%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2200      | 73.63%  |
| Yes       | 788       | 26.37%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 425       | 14.57%  |
| Hewlett-Packard         | 382       | 13.1%   |
| Dell                    | 375       | 12.86%  |
| Gigabyte Technology     | 355       | 12.17%  |
| Lenovo                  | 308       | 10.56%  |
| MSI                     | 188       | 6.44%   |
| Acer                    | 145       | 4.97%   |
| Apple                   | 131       | 4.49%   |
| ASRock                  | 112       | 3.84%   |
| Toshiba                 | 94        | 3.22%   |
| Intel                   | 85        | 2.91%   |
| Microsoft               | 30        | 1.03%   |
| Raspberry Pi Foundation | 28        | 0.96%   |
| Alienware               | 20        | 0.69%   |
| Unknown                 | 18        | 0.62%   |
| Samsung Electronics     | 14        | 0.48%   |
| AMI                     | 11        | 0.38%   |
| Sony                    | 10        | 0.34%   |
| Pegatron                | 10        | 0.34%   |
| Notebook                | 10        | 0.34%   |
| Timi                    | 8         | 0.27%   |
| Medion                  | 8         | 0.27%   |
| Panasonic               | 7         | 0.24%   |
| IT Channel Pty          | 7         | 0.24%   |
| HUAWEI                  | 7         | 0.24%   |
| Google                  | 7         | 0.24%   |
| Razer                   | 6         | 0.21%   |
| Metabox                 | 6         | 0.21%   |
| IBM                     | 6         | 0.21%   |
| Supermicro              | 5         | 0.17%   |
| Pine Microsystems       | 5         | 0.17%   |
| Kogan                   | 5         | 0.17%   |
| ECS                     | 5         | 0.17%   |
| System76                | 4         | 0.14%   |
| Shuttle                 | 4         | 0.14%   |
| Intel Client Systems    | 4         | 0.14%   |
| Hardkernel              | 4         | 0.14%   |
| Fanless Mini PC         | 4         | 0.14%   |
| Valve                   | 3         | 0.1%    |
| ReachingTech            | 3         | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| ASUS All Series              | 31        | 1.06%   |
| Dell OptiPlex 9020           | 24        | 0.82%   |
| Unknown                      | 22        | 0.75%   |
| HP Pavilion dv6              | 14        | 0.48%   |
| MSI MS-7B89                  | 11        | 0.38%   |
| HP Pavilion g6               | 11        | 0.38%   |
| RPi Raspberry Pi             | 10        | 0.34%   |
| HP Notebook                  | 10        | 0.34%   |
| Gigabyte 970A-D3P            | 10        | 0.34%   |
| Apple iMac12,2               | 9         | 0.31%   |
| MSI MS-7C37                  | 8         | 0.27%   |
| MSI MS-7817                  | 8         | 0.27%   |
| HP Pavilion 15               | 8         | 0.27%   |
| Dell OptiPlex 780            | 8         | 0.27%   |
| Gigabyte X58A-UD3R           | 7         | 0.24%   |
| Dell XPS 15 9570             | 7         | 0.24%   |
| Apple MacBookPro9,2          | 7         | 0.24%   |
| Apple MacBookPro10,1         | 7         | 0.24%   |
| MSI MS-7C94                  | 6         | 0.21%   |
| MSI MS-7C84                  | 6         | 0.21%   |
| MSI MS-7C02                  | 6         | 0.21%   |
| Gigabyte B75M-D3H            | 6         | 0.21%   |
| Dell OptiPlex 9010           | 6         | 0.21%   |
| Apple MacBookPro8,1          | 6         | 0.21%   |
| Apple MacBookAir7,2          | 6         | 0.21%   |
| Acer ConceptD CN315-71P      | 6         | 0.21%   |
| Toshiba Satellite P750       | 5         | 0.17%   |
| MSI MS-7B86                  | 5         | 0.17%   |
| Microsoft Surface Laptop 3   | 5         | 0.17%   |
| HP Compaq 8200 Elite SFF PC  | 5         | 0.17%   |
| Gigabyte X570 AORUS PRO WIFI | 5         | 0.17%   |
| Gigabyte GA-870A-UD3         | 5         | 0.17%   |
| Gigabyte B85M-HD3            | 5         | 0.17%   |
| Gigabyte B450 AORUS PRO      | 5         | 0.17%   |
| Dell XPS 15 9560             | 5         | 0.17%   |
| Dell XPS 13 9360             | 5         | 0.17%   |
| Dell OptiPlex 990            | 5         | 0.17%   |
| Dell OptiPlex 3010           | 5         | 0.17%   |
| Dell Latitude E7450          | 5         | 0.17%   |
| ASUS TUF Gaming B550M-PLUS   | 5         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 144       | 4.94%   |
| Acer Aspire         | 97        | 3.33%   |
| Dell OptiPlex       | 87        | 2.98%   |
| HP Pavilion         | 77        | 2.64%   |
| Toshiba Satellite   | 75        | 2.57%   |
| Dell Latitude       | 75        | 2.57%   |
| Dell Inspiron       | 73        | 2.5%    |
| ASUS PRIME          | 62        | 2.13%   |
| Dell XPS            | 61        | 2.09%   |
| ASUS ROG            | 54        | 1.85%   |
| HP EliteBook        | 48        | 1.65%   |
| HP Compaq           | 41        | 1.41%   |
| Lenovo IdeaPad      | 39        | 1.34%   |
| Dell Precision      | 38        | 1.3%    |
| Lenovo Yoga         | 31        | 1.06%   |
| Lenovo ThinkCentre  | 31        | 1.06%   |
| ASUS All            | 31        | 1.06%   |
| Microsoft Surface   | 30        | 1.03%   |
| HP ProBook          | 30        | 1.03%   |
| ASUS TUF            | 29        | 0.99%   |
| RPi Raspberry       | 28        | 0.96%   |
| HP Laptop           | 22        | 0.75%   |
| Gigabyte X570       | 22        | 0.75%   |
| Unknown             | 22        | 0.75%   |
| HP ENVY             | 20        | 0.69%   |
| Gigabyte B450       | 17        | 0.58%   |
| Dell Vostro         | 14        | 0.48%   |
| ASUS ZenBook        | 13        | 0.45%   |
| HP Spectre          | 12        | 0.41%   |
| Gigabyte B450M      | 12        | 0.41%   |
| MSI MS-7B89         | 11        | 0.38%   |
| HP ProDesk          | 11        | 0.38%   |
| ASUS VivoBook       | 11        | 0.38%   |
| Apple iMac12        | 11        | 0.38%   |
| Acer Swift          | 11        | 0.38%   |
| Lenovo ThinkStation | 10        | 0.34%   |
| Lenovo IdeaPadFlex  | 10        | 0.34%   |
| HP Notebook         | 10        | 0.34%   |
| Gigabyte 970A-D3P   | 10        | 0.34%   |
| Apple MacBookPro10  | 10        | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 283       | 9.7%    |
| 2018    | 273       | 9.36%   |
| 2020    | 258       | 8.84%   |
| 2012    | 237       | 8.12%   |
| 2013    | 218       | 7.47%   |
| 2011    | 214       | 7.34%   |
| 2017    | 202       | 6.92%   |
| 2014    | 180       | 6.17%   |
| 2021    | 169       | 5.79%   |
| 2016    | 168       | 5.76%   |
| 2010    | 148       | 5.07%   |
| 2015    | 145       | 4.97%   |
| 2009    | 112       | 3.84%   |
| 2008    | 110       | 3.77%   |
| 2022    | 73        | 2.5%    |
| 2007    | 52        | 1.78%   |
| Unknown | 41        | 1.41%   |
| 2006    | 19        | 0.65%   |
| 2005    | 11        | 0.38%   |
| 2004    | 2         | 0.07%   |
| 2003    | 1         | 0.03%   |
| 2002    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 1311      | 44.94%  |
| Notebook       | 1244      | 42.65%  |
| Convertible    | 100       | 3.43%   |
| Mini pc        | 75        | 2.57%   |
| All in one     | 74        | 2.54%   |
| Tablet         | 47        | 1.61%   |
| System on chip | 35        | 1.2%    |
| Server         | 26        | 0.89%   |
| Phone          | 3         | 0.1%    |
| Stick pc       | 2         | 0.07%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 2701      | 92%     |
| Enabled  | 235       | 8%      |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2905      | 99.59%  |
| Yes  | 12        | 0.41%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 732       | 24.49%  |
| 4.01-8.0        | 607       | 20.31%  |
| 8.01-16.0       | 504       | 16.86%  |
| 3.01-4.0        | 471       | 15.76%  |
| 32.01-64.0      | 376       | 12.58%  |
| 64.01-256.0     | 105       | 3.51%   |
| 1.01-2.0        | 98        | 3.28%   |
| 24.01-32.0      | 52        | 1.74%   |
| 2.01-3.0        | 19        | 0.64%   |
| 0.51-1.0        | 13        | 0.43%   |
| 0.01-0.5        | 7         | 0.23%   |
| More than 256.0 | 4         | 0.13%   |
| Unknown         | 1         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 1125      | 33.51%  |
| 2.01-3.0    | 848       | 25.26%  |
| 4.01-8.0    | 475       | 14.15%  |
| 3.01-4.0    | 433       | 12.9%   |
| 0.51-1.0    | 219       | 6.52%   |
| 8.01-16.0   | 163       | 4.86%   |
| 0.01-0.5    | 48        | 1.43%   |
| 16.01-24.0  | 26        | 0.77%   |
| 24.01-32.0  | 10        | 0.3%    |
| 32.01-64.0  | 3         | 0.09%   |
| 64.01-256.0 | 3         | 0.09%   |
| 0           | 2         | 0.06%   |
| Unknown     | 2         | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1635      | 53.17%  |
| 2       | 748       | 24.33%  |
| 3       | 296       | 9.63%   |
| 4       | 179       | 5.82%   |
| 5       | 81        | 2.63%   |
| 6       | 45        | 1.46%   |
| 0       | 34        | 1.11%   |
| 7       | 22        | 0.72%   |
| 8       | 16        | 0.52%   |
| 9       | 8         | 0.26%   |
| 10      | 4         | 0.13%   |
| 13      | 3         | 0.1%    |
| 36      | 1         | 0.03%   |
| 14      | 1         | 0.03%   |
| 11      | 1         | 0.03%   |
| Unknown | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1764      | 59.76%  |
| Yes       | 1188      | 40.24%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2537      | 86.79%  |
| No        | 386       | 13.21%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2164      | 73.31%  |
| No        | 788       | 26.69%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1681      | 56.66%  |
| No        | 1286      | 43.34%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| Australia | 2917      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Sydney         | 814       | 25.93%  |
| Melbourne      | 604       | 19.24%  |
| Brisbane       | 448       | 14.27%  |
| Perth          | 269       | 8.57%   |
| Adelaide       | 187       | 5.96%   |
| Canberra       | 69        | 2.2%    |
| Wahroonga      | 39        | 1.24%   |
| Hobart         | 29        | 0.92%   |
| Launceston     | 23        | 0.73%   |
| Alexandria     | 20        | 0.64%   |
| Surry Hills    | 17        | 0.54%   |
| Gold Coast     | 13        | 0.41%   |
| Lane Cove      | 12        | 0.38%   |
| Geelong        | 12        | 0.38%   |
| Newcastle      | 11        | 0.35%   |
| Mitcham        | 11        | 0.35%   |
| Central Coast  | 11        | 0.35%   |
| Woolloongabba  | 10        | 0.32%   |
| Southport      | 9         | 0.29%   |
| Richmond       | 9         | 0.29%   |
| Brighton       | 9         | 0.29%   |
| Traralgon      | 8         | 0.25%   |
| Wollongong     | 7         | 0.22%   |
| Townsville     | 7         | 0.22%   |
| Parramatta     | 7         | 0.22%   |
| North Sydney   | 7         | 0.22%   |
| Mandurah       | 7         | 0.22%   |
| Artarmon       | 7         | 0.22%   |
| West End       | 6         | 0.19%   |
| Point Cook     | 6         | 0.19%   |
| Mount Waverley | 6         | 0.19%   |
| Macquarie Park | 6         | 0.19%   |
| Sunshine Coast | 5         | 0.16%   |
| Spring Field   | 5         | 0.16%   |
| Ringwood East  | 5         | 0.16%   |
| Northcote      | 5         | 0.16%   |
| Mascot         | 5         | 0.16%   |
| Hawthorn       | 5         | 0.16%   |
| Geraldton      | 5         | 0.16%   |
| Doncaster      | 5         | 0.16%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 832       | 1505   | 18.41%  |
| Seagate                   | 758       | 1427   | 16.77%  |
| WDC                       | 701       | 1342   | 15.51%  |
| Toshiba                   | 243       | 343    | 5.38%   |
| Crucial                   | 238       | 358    | 5.27%   |
| Kingston                  | 207       | 266    | 4.58%   |
| Unknown                   | 175       | 260    | 3.87%   |
| SanDisk                   | 174       | 231    | 3.85%   |
| Intel                     | 169       | 304    | 3.74%   |
| Hitachi                   | 141       | 223    | 3.12%   |
| SK hynix                  | 89        | 108    | 1.97%   |
| Apple                     | 75        | 102    | 1.66%   |
| HGST                      | 67        | 97     | 1.48%   |
| Micron Technology         | 59        | 77     | 1.31%   |
| Micron/Crucial Technology | 44        | 63     | 0.97%   |
| Phison                    | 36        | 55     | 0.8%    |
| OCZ                       | 34        | 50     | 0.75%   |
| SPCC                      | 30        | 38     | 0.66%   |
| KIOXIA                    | 29        | 31     | 0.64%   |
| A-DATA Technology         | 27        | 37     | 0.6%    |
| Corsair                   | 20        | 34     | 0.44%   |
| LITEON                    | 19        | 27     | 0.42%   |
| JMicron Technology        | 19        | 22     | 0.42%   |
| LITEONIT                  | 17        | 22     | 0.38%   |
| Phison Electronics        | 16        | 20     | 0.35%   |
| Fujitsu                   | 16        | 20     | 0.35%   |
| KingSpec                  | 15        | 34     | 0.33%   |
| Transcend                 | 13        | 20     | 0.29%   |
| Patriot                   | 13        | 20     | 0.29%   |
| Unknown                   | 13        | 14     | 0.29%   |
| ASMT                      | 12        | 19     | 0.27%   |
| LaCie                     | 11        | 18     | 0.24%   |
| Gigabyte Technology       | 11        | 14     | 0.24%   |
| China                     | 11        | 13     | 0.24%   |
| Maxtor                    | 9         | 12     | 0.2%    |
| Silicon Motion            | 8         | 19     | 0.18%   |
| Realtek Semiconductor     | 8         | 11     | 0.18%   |
| Hewlett-Packard           | 8         | 12     | 0.18%   |
| XPG                       | 7         | 8      | 0.15%   |
| TO Exter                  | 7         | 7      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB                           | 55        | 1.05%   |
| Samsung SSD 850 EVO 250GB                           | 43        | 0.82%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 37        | 0.71%   |
| Unknown MMC Card  32GB                              | 36        | 0.69%   |
| Seagate ST1000DM010-2EP102 1TB                      | 33        | 0.63%   |
| Seagate Expansion Desk 8TB                          | 33        | 0.63%   |
| Seagate ST500DM002-1BD142 500GB                     | 32        | 0.61%   |
| Samsung SSD 850 EVO 500GB                           | 32        | 0.61%   |
| Samsung NVMe SSD Drive 1TB                          | 32        | 0.61%   |
| Crucial CT240BX500SSD1 240GB                        | 32        | 0.61%   |
| Unknown MMC Card  64GB                              | 31        | 0.59%   |
| Seagate ST2000DM008-2FR102 2TB                      | 29        | 0.56%   |
| Seagate Expansion+ 2TB                              | 29        | 0.56%   |
| Seagate ST4000DM004-2CV104 4TB                      | 28        | 0.54%   |
| Samsung NVMe SSD Drive 512GB                        | 28        | 0.54%   |
| Samsung NVMe SSD Drive 500GB                        | 28        | 0.54%   |
| Crucial CT500MX500SSD1 500GB                        | 28        | 0.54%   |
| Seagate ST2000DM001-1ER164 2TB                      | 27        | 0.52%   |
| Samsung SSD 860 EVO 1TB                             | 27        | 0.52%   |
| Kingston SA400S37240G 240GB SSD                     | 26        | 0.5%    |
| Seagate ST2000DM001-1CH164 2TB                      | 25        | 0.48%   |
| Crucial CT480BX500SSD1 480GB                        | 25        | 0.48%   |
| Crucial CT1000MX500SSD1 1TB                         | 24        | 0.46%   |
| Seagate ST3500418AS 500GB                           | 23        | 0.44%   |
| Toshiba MQ01ABD100 1TB                              | 22        | 0.42%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 22        | 0.42%   |
| Kingston SV300S37A120G 120GB SSD                    | 22        | 0.42%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 21        | 0.4%    |
| Kingston SA400S37120G 120GB SSD                     | 21        | 0.4%    |
| WDC WD20EARX-00PASB0 2TB                            | 20        | 0.38%   |
| Seagate ST2000DM006-2DM164 2TB                      | 20        | 0.38%   |
| Samsung SSD 860 QVO 1TB                             | 20        | 0.38%   |
| Seagate ST31000528AS 1TB                            | 19        | 0.36%   |
| Seagate ST2000DL003-9VT166 2TB                      | 19        | 0.36%   |
| Seagate ST1000LM035-1RK172 1TB                      | 19        | 0.36%   |
| Samsung SSD 970 EVO Plus 500GB                      | 19        | 0.36%   |
| Kingston SA400S37480G 480GB SSD                     | 19        | 0.36%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 18        | 0.34%   |
| Unknown SD/MMC/MS PRO 64GB                          | 18        | 0.34%   |
| Seagate ST1000DM003-1ER162 1TB                      | 18        | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 743       | 1383   | 39.35%  |
| WDC                 | 574       | 1116   | 30.4%   |
| Toshiba             | 167       | 248    | 8.85%   |
| Hitachi             | 141       | 223    | 7.47%   |
| Samsung Electronics | 91        | 220    | 4.82%   |
| HGST                | 65        | 95     | 3.44%   |
| Unknown             | 20        | 31     | 1.06%   |
| Apple               | 20        | 25     | 1.06%   |
| Fujitsu             | 15        | 19     | 0.79%   |
| ASMT                | 11        | 18     | 0.58%   |
| Maxtor              | 9         | 12     | 0.48%   |
| LaCie               | 9         | 15     | 0.48%   |
| USB                 | 3         | 4      | 0.16%   |
| Hewlett-Packard     | 3         | 4      | 0.16%   |
| T-CREATE            | 2         | 2      | 0.11%   |
| SABRENT             | 2         | 2      | 0.11%   |
| KESU                | 2         | 2      | 0.11%   |
| HGST HUS            | 2         | 2      | 0.11%   |
| USB3.0              | 1         | 2      | 0.05%   |
| QNAP                | 1         | 2      | 0.05%   |
| MaxDigital          | 1         | 1      | 0.05%   |
| IET                 | 1         | 1      | 0.05%   |
| IBM/Hitachi         | 1         | 1      | 0.05%   |
| HPE                 | 1         | 1      | 0.05%   |
| Hajaan              | 1         | 1      | 0.05%   |
| DAS                 | 1         | 1      | 0.05%   |
| AAPL                | 1         | 1      | 0.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 464       | 773    | 30.63%  |
| Crucial             | 204       | 314    | 13.47%  |
| Kingston            | 151       | 194    | 9.97%   |
| WDC                 | 116       | 155    | 7.66%   |
| SanDisk             | 113       | 143    | 7.46%   |
| Intel               | 84        | 171    | 5.54%   |
| Apple               | 39        | 44     | 2.57%   |
| OCZ                 | 34        | 50     | 2.24%   |
| SK hynix            | 29        | 35     | 1.91%   |
| SPCC                | 27        | 33     | 1.78%   |
| Toshiba             | 25        | 33     | 1.65%   |
| Micron Technology   | 24        | 27     | 1.58%   |
| LITEONIT            | 17        | 22     | 1.12%   |
| LITEON              | 17        | 25     | 1.12%   |
| A-DATA Technology   | 16        | 22     | 1.06%   |
| KingSpec            | 14        | 33     | 0.92%   |
| Transcend           | 13        | 20     | 0.86%   |
| Patriot             | 13        | 20     | 0.86%   |
| Corsair             | 13        | 27     | 0.86%   |
| Seagate             | 12        | 19     | 0.79%   |
| JMicron Technology  | 11        | 12     | 0.73%   |
| China               | 11        | 13     | 0.73%   |
| TO Exter            | 7         | 7      | 0.46%   |
| OWC                 | 6         | 14     | 0.4%    |
| Gigabyte Technology | 6         | 6      | 0.4%    |
| Plextor             | 5         | 17     | 0.33%   |
| Team                | 3         | 4      | 0.2%    |
| Lexar               | 3         | 3      | 0.2%    |
| KingFast            | 3         | 3      | 0.2%    |
| Vaseky              | 2         | 6      | 0.13%   |
| NGFF                | 2         | 2      | 0.13%   |
| Hajaan              | 2         | 2      | 0.13%   |
| FORESEE             | 2         | 2      | 0.13%   |
| XPG                 | 1         | 1      | 0.07%   |
| Unknown             | 1         | 1      | 0.07%   |
| SATA3 12            | 1         | 1      | 0.07%   |
| SAMSWEET            | 1         | 1      | 0.07%   |
| Radeon              | 1         | 1      | 0.07%   |
| PNY                 | 1         | 1      | 0.07%   |
| OCZ-VERTEX3         | 1         | 1      | 0.07%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1530      | 3432   | 38.3%   |
| SSD     | 1307      | 2285   | 32.72%  |
| NVMe    | 942       | 1455   | 23.58%  |
| MMC     | 152       | 216    | 3.8%    |
| Unknown | 64        | 91     | 1.6%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2209      | 5403   | 62.21%  |
| NVMe | 942       | 1450   | 26.53%  |
| SAS  | 248       | 410    | 6.98%   |
| MMC  | 152       | 216    | 4.28%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 1600      | 3022   | 51.5%   |
| 0.51-1.0        | 809       | 1419   | 26.04%  |
| 1.01-2.0        | 383       | 675    | 12.33%  |
| 4.01-10.0       | 119       | 229    | 3.83%   |
| 3.01-4.0        | 112       | 231    | 3.6%    |
| 2.01-3.0        | 76        | 131    | 2.45%   |
| 10.01-20.0      | 6         | 8      | 0.19%   |
| More than 100.0 | 1         | 1      | 0.03%   |
| 0               | 1         | 1      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 710       | 22.49%  |
| 251-500        | 652       | 20.65%  |
| 501-1000       | 480       | 15.2%   |
| 1001-2000      | 287       | 9.09%   |
| 1-20           | 261       | 8.27%   |
| More than 3000 | 249       | 7.89%   |
| 51-100         | 216       | 6.84%   |
| 2001-3000      | 119       | 3.77%   |
| Unknown        | 92        | 2.91%   |
| 21-50          | 91        | 2.88%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1259      | 37.96%  |
| 21-50          | 533       | 16.07%  |
| 101-250        | 378       | 11.4%   |
| 51-100         | 331       | 9.98%   |
| 251-500        | 274       | 8.26%   |
| 501-1000       | 181       | 5.46%   |
| 1001-2000      | 118       | 3.56%   |
| More than 3000 | 101       | 3.04%   |
| Unknown        | 92        | 2.77%   |
| 2001-3000      | 48        | 1.45%   |
| 0              | 2         | 0.06%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Computers | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| Intel SSDSC2CT120A3 120GB               | 7         | 32     | 2.61%   |
| Seagate ST500DM002-1BD142 500GB         | 5         | 12     | 1.87%   |
| Seagate ST3500418AS 500GB               | 5         | 11     | 1.87%   |
| Hitachi HDS721010DLE630 1TB             | 5         | 7      | 1.87%   |
| Kingston SV300S37A120G 120GB SSD        | 4         | 4      | 1.49%   |
| WDC WD20EARX-00PASB0 2TB                | 3         | 3      | 1.12%   |
| Seagate ST9500325AS 500GB               | 3         | 3      | 1.12%   |
| Seagate ST2000DM001-9YN164 2TB          | 3         | 3      | 1.12%   |
| Seagate ST2000DM001-1CH164 2TB          | 3         | 3      | 1.12%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 3         | 4      | 1.12%   |
| Maxtor 6Y080L0 82GB                     | 3         | 5      | 1.12%   |
| Maxtor 6L200M0 208GB                    | 3         | 4      | 1.12%   |
| Kingston RBU-SNS8350DES3128GP 128GB SSD | 3         | 3      | 1.12%   |
| HGST HTS725050A7E630 500GB              | 3         | 3      | 1.12%   |
| Crucial CT525MX300SSD1 528GB            | 3         | 4      | 1.12%   |
| WDC WDS500G1X0E-00AFY0 500GB            | 2         | 2      | 0.75%   |
| WDC WD30EZRX-00DC0B0 3TB                | 2         | 2      | 0.75%   |
| WDC WD20EFRX-68EUZN0 2TB                | 2         | 3      | 0.75%   |
| WDC WD2002FAEX-007BA0 2TB               | 2         | 3      | 0.75%   |
| WDC WD1600AVVS-63L2B0 160GB             | 2         | 5      | 0.75%   |
| WDC WD10EZEX-60ZF5A0 1TB                | 2         | 2      | 0.75%   |
| WDC WD10EZEX-60WN4A0 1TB                | 2         | 3      | 0.75%   |
| WDC WD10EFRX-68FYTN0 1TB                | 2         | 2      | 0.75%   |
| WDC WD10EADS-11M2B1 1TB                 | 2         | 2      | 0.75%   |
| WDC WD1003FZEX-00K3CA0 1TB              | 2         | 3      | 0.75%   |
| Toshiba THNSNK128GCS8 SATA 128GB SSD    | 2         | 2      | 0.75%   |
| Toshiba MQ01ABF050 500GB                | 2         | 2      | 0.75%   |
| Seagate ST9320423AS 320GB               | 2         | 3      | 0.75%   |
| Seagate ST500LT012-9WS142 500GB         | 2         | 4      | 0.75%   |
| Seagate ST500LT012-1DG142 500GB         | 2         | 2      | 0.75%   |
| Seagate ST500LM021-1KJ152 500GB         | 2         | 2      | 0.75%   |
| Seagate ST3500413AS 500GB               | 2         | 2      | 0.75%   |
| Seagate ST31000528AS 1TB                | 2         | 2      | 0.75%   |
| Seagate ST31000333AS 1TB                | 2         | 4      | 0.75%   |
| Seagate ST2000DM001-1ER164 2TB          | 2         | 2      | 0.75%   |
| Seagate ST1000DX001-1CM162 1TB          | 2         | 2      | 0.75%   |
| Seagate ST1000DM010-2EP102 1TB          | 2         | 2      | 0.75%   |
| Seagate ST1000DM003-1ER162 1TB          | 2         | 6      | 0.75%   |
| Samsung Electronics HD501LJ 500GB       | 2         | 28     | 0.75%   |
| Samsung Electronics HD154UI 1TB         | 2         | 3      | 0.75%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                   | Computers | Drives | Percent |
|--------------------------|-----------|--------|---------|
| Seagate                  | 68        | 106    | 26.98%  |
| WDC                      | 52        | 90     | 20.63%  |
| Samsung Electronics      | 25        | 68     | 9.92%   |
| Intel                    | 19        | 56     | 7.54%   |
| Hitachi                  | 18        | 21     | 7.14%   |
| Toshiba                  | 11        | 15     | 4.37%   |
| Kingston                 | 11        | 11     | 4.37%   |
| HGST                     | 7         | 8      | 2.78%   |
| Maxtor                   | 6         | 9      | 2.38%   |
| Crucial                  | 6         | 7      | 2.38%   |
| Sandisk                  | 4         | 4      | 1.59%   |
| Fujitsu                  | 4         | 4      | 1.59%   |
| Corsair                  | 4         | 5      | 1.59%   |
| SK hynix                 | 2         | 2      | 0.79%   |
| Apple                    | 2         | 2      | 0.79%   |
| SPCC                     | 1         | 1      | 0.4%    |
| Realtek Semiconductor    | 1         | 2      | 0.4%    |
| OCZ                      | 1         | 1      | 0.4%    |
| Netac                    | 1         | 1      | 0.4%    |
| MaxDigital               | 1         | 1      | 0.4%    |
| KingSpec                 | 1         | 3      | 0.4%    |
| KingFast                 | 1         | 1      | 0.4%    |
| HPE                      | 1         | 1      | 0.4%    |
| Hewlett-Packard          | 1         | 2      | 0.4%    |
| Gigabyte Technology      | 1         | 1      | 0.4%    |
| Biwin Storage Technology | 1         | 1      | 0.4%    |
| ASMT                     | 1         | 1      | 0.4%    |
| A-DATA Technology        | 1         | 1      | 0.4%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 68        | 106    | 37.57%  |
| WDC                 | 51        | 87     | 28.18%  |
| Hitachi             | 18        | 21     | 9.94%   |
| Samsung Electronics | 13        | 55     | 7.18%   |
| Toshiba             | 9         | 13     | 4.97%   |
| HGST                | 7         | 8      | 3.87%   |
| Maxtor              | 6         | 9      | 3.31%   |
| Fujitsu             | 4         | 4      | 2.21%   |
| MaxDigital          | 1         | 1      | 0.55%   |
| HPE                 | 1         | 1      | 0.55%   |
| Hewlett-Packard     | 1         | 2      | 0.55%   |
| ASMT                | 1         | 1      | 0.55%   |
| Apple               | 1         | 1      | 0.55%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 163       | 309    | 69.66%  |
| SSD  | 60        | 101    | 25.64%  |
| NVMe | 11        | 15     | 4.7%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                       | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC WD3200AAJS-40RYA0 320GB | 1         | 1      | 50%     |
| Hitachi HDS721010DLE630 1TB | 1         | 6      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Hitachi | 1         | 6      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1893      | 4388   | 59.55%  |
| Works    | 1058      | 2659   | 33.28%  |
| Malfunc  | 226       | 425    | 7.11%   |
| Failed   | 2         | 7      | 0.06%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1934      | 50.56%  |
| AMD                              | 583       | 15.24%  |
| Samsung Electronics              | 391       | 10.22%  |
| SanDisk                          | 102       | 2.67%   |
| Marvell Technology Group         | 88        | 2.3%    |
| Micron/Crucial Technology        | 80        | 2.09%   |
| ASMedia Technology               | 78        | 2.04%   |
| JMicron Technology               | 69        | 1.8%    |
| Kingston Technology Company      | 64        | 1.67%   |
| Phison Electronics               | 63        | 1.65%   |
| SK hynix                         | 61        | 1.59%   |
| Toshiba America Info Systems     | 52        | 1.36%   |
| Micron Technology                | 36        | 0.94%   |
| KIOXIA                           | 28        | 0.73%   |
| Nvidia                           | 27        | 0.71%   |
| ADATA Technology                 | 19        | 0.5%    |
| LSI Logic / Symbios Logic        | 18        | 0.47%   |
| Silicon Motion                   | 17        | 0.44%   |
| Apple                            | 16        | 0.42%   |
| VIA Technologies                 | 11        | 0.29%   |
| Realtek Semiconductor            | 11        | 0.29%   |
| Broadcom / LSI                   | 10        | 0.26%   |
| Seagate Technology               | 9         | 0.24%   |
| Integrated Technology Express    | 8         | 0.21%   |
| Solid State Storage Technology   | 6         | 0.16%   |
| Silicon Image                    | 6         | 0.16%   |
| Hewlett-Packard                  | 6         | 0.16%   |
| Lite-On Technology               | 5         | 0.13%   |
| Union Memory (Shenzhen)          | 4         | 0.1%    |
| Adaptec                          | 4         | 0.1%    |
| ULi Electronics                  | 3         | 0.08%   |
| Silicon Integrated Systems [SiS] | 3         | 0.08%   |
| Lenovo                           | 3         | 0.08%   |
| 3ware                            | 3         | 0.08%   |
| Shenzhen Longsys Electronics     | 2         | 0.05%   |
| Biwin Storage Technology         | 2         | 0.05%   |
| Promise Technology               | 1         | 0.03%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.03%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 401       | 8.97%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 209       | 4.68%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 150       | 3.36%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 117       | 2.62%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 104       | 2.33%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 99        | 2.21%   |
| AMD 400 Series Chipset SATA Controller                                                  | 97        | 2.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 83        | 1.86%   |
| Intel SATA Controller [RAID mode]                                                       | 80        | 1.79%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 79        | 1.77%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 70        | 1.57%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 70        | 1.57%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 68        | 1.52%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 65        | 1.45%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 65        | 1.45%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 61        | 1.36%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 60        | 1.34%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 59        | 1.32%   |
| AMD 500 Series Chipset SATA Controller                                                  | 56        | 1.25%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 55        | 1.23%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 53        | 1.19%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 50        | 1.12%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 48        | 1.07%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 47        | 1.05%   |
| Samsung NVMe SSD Controller 980                                                         | 46        | 1.03%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 41        | 0.92%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 40        | 0.89%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 37        | 0.83%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 35        | 0.78%   |
| Micron NVMe Storage Controller                                                          | 34        | 0.76%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 34        | 0.76%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 34        | 0.76%   |
| Intel SSD 660P Series                                                                   | 33        | 0.74%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 33        | 0.74%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 32        | 0.72%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 32        | 0.72%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 32        | 0.72%   |
| Micron/Crucial NVMe Storage Controller                                                  | 31        | 0.69%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 30        | 0.67%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 29        | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2080      | 55.19%  |
| NVMe | 947       | 25.13%  |
| IDE  | 435       | 11.54%  |
| RAID | 279       | 7.4%    |
| SAS  | 20        | 0.53%   |
| SCSI | 8         | 0.21%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor        | Computers | Percent |
|---------------|-----------|---------|
| Intel         | 2208      | 75.69%  |
| AMD           | 665       | 22.8%   |
| ARM           | 41        | 1.41%   |
| sifive,u74-mc | 1         | 0.03%   |
| CentaurHauls  | 1         | 0.03%   |
| Unknown       | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor       | 39        | 1.33%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 33        | 1.13%   |
| Intel Core i7-2600 CPU @ 3.40GHz        | 33        | 1.13%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 29        | 0.99%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 28        | 0.96%   |
| ARM Processor                           | 28        | 0.96%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 27        | 0.92%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 27        | 0.92%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 24        | 0.82%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 24        | 0.82%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 24        | 0.82%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 23        | 0.79%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 23        | 0.79%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 23        | 0.79%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 22        | 0.75%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 22        | 0.75%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 22        | 0.75%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 22        | 0.75%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 21        | 0.72%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 21        | 0.72%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 19        | 0.65%   |
| AMD Ryzen 9 5950X 16-Core Processor     | 19        | 0.65%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 18        | 0.62%   |
| AMD Ryzen 5 2600 Six-Core Processor     | 18        | 0.62%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 17        | 0.58%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 17        | 0.58%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 17        | 0.58%   |
| Intel Core i7-4770 CPU @ 3.40GHz        | 17        | 0.58%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 17        | 0.58%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 16        | 0.55%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 15        | 0.51%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 15        | 0.51%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 14        | 0.48%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 14        | 0.48%   |
| Intel Core i7-6700 CPU @ 3.40GHz        | 13        | 0.44%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 13        | 0.44%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz      | 13        | 0.44%   |
| Intel Core i7-3770K CPU @ 3.50GHz       | 13        | 0.44%   |
| Intel Core i5-6500 CPU @ 3.20GHz        | 13        | 0.44%   |
| AMD Ryzen 7 1700 Eight-Core Processor   | 13        | 0.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 778       | 26.64%  |
| Intel Core i5           | 639       | 21.88%  |
| Other                   | 180       | 6.16%   |
| AMD Ryzen 5             | 169       | 5.79%   |
| AMD Ryzen 7             | 129       | 4.42%   |
| Intel Core i3           | 124       | 4.25%   |
| Intel Core 2 Duo        | 121       | 4.14%   |
| Intel Celeron           | 108       | 3.7%    |
| Intel Xeon              | 80        | 2.74%   |
| AMD Ryzen 9             | 67        | 2.29%   |
| Intel Pentium           | 46        | 1.58%   |
| AMD FX                  | 46        | 1.58%   |
| Intel Atom              | 32        | 1.1%    |
| AMD A6                  | 29        | 0.99%   |
| AMD A4                  | 25        | 0.86%   |
| AMD Ryzen 3             | 24        | 0.82%   |
| Intel Core 2 Quad       | 23        | 0.79%   |
| Intel Core 2            | 23        | 0.79%   |
| AMD A8                  | 20        | 0.68%   |
| Intel Core i9           | 18        | 0.62%   |
| Intel Pentium Dual-Core | 17        | 0.58%   |
| AMD E2                  | 15        | 0.51%   |
| AMD A10                 | 15        | 0.51%   |
| AMD Phenom II X4        | 14        | 0.48%   |
| ARM BCM                 | 11        | 0.38%   |
| AMD Ryzen Threadripper  | 11        | 0.38%   |
| AMD Phenom II X6        | 10        | 0.34%   |
| AMD Athlon              | 9         | 0.31%   |
| Intel Genuine           | 8         | 0.27%   |
| Intel Core m3           | 8         | 0.27%   |
| AMD Ryzen 7 PRO         | 8         | 0.27%   |
| AMD E1                  | 8         | 0.27%   |
| Intel Pentium D         | 7         | 0.24%   |
| Intel Pentium Dual      | 6         | 0.21%   |
| Intel Core M            | 6         | 0.21%   |
| Intel Pentium 4         | 5         | 0.17%   |
| AMD Phenom II X2        | 5         | 0.17%   |
| AMD E                   | 5         | 0.17%   |
| AMD Athlon II X4        | 5         | 0.17%   |
| AMD Athlon II X2        | 5         | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 1152      | 39.41%  |
| 2       | 977       | 33.42%  |
| 6       | 354       | 12.11%  |
| 8       | 217       | 7.42%   |
| 12      | 62        | 2.12%   |
| 1       | 57        | 1.95%   |
| 16      | 39        | 1.33%   |
| 3       | 19        | 0.65%   |
| 10      | 17        | 0.58%   |
| 14      | 10        | 0.34%   |
| 24      | 7         | 0.24%   |
| 32      | 4         | 0.14%   |
| Unknown | 4         | 0.14%   |
| 40      | 2         | 0.07%   |
| 128     | 1         | 0.03%   |
| 5       | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2869      | 98.32%  |
| 2       | 44        | 1.51%   |
| Unknown | 4         | 0.14%   |
| 4       | 1         | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1997      | 68.39%  |
| 1       | 915       | 31.34%  |
| Unknown | 4         | 0.14%   |
| 8       | 2         | 0.07%   |
| 4       | 2         | 0.07%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2830      | 96.69%  |
| Unknown        | 69        | 2.36%   |
| 32-bit         | 22        | 0.75%   |
| 64-bit         | 6         | 0.2%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 783       | 25.81%  |
| 0x206a7    | 172       | 5.67%   |
| 0x306a9    | 161       | 5.31%   |
| 0x306c3    | 137       | 4.52%   |
| 0x1067a    | 92        | 3.03%   |
| 0x906ea    | 81        | 2.67%   |
| 0x906e9    | 67        | 2.21%   |
| 0x506e3    | 66        | 2.18%   |
| 0x806e9    | 60        | 1.98%   |
| 0x406e3    | 57        | 1.88%   |
| 0x40651    | 56        | 1.85%   |
| 0x08701021 | 55        | 1.81%   |
| 0x806ea    | 54        | 1.78%   |
| 0x806ec    | 53        | 1.75%   |
| 0x806c1    | 51        | 1.68%   |
| 0x306d4    | 43        | 1.42%   |
| 0x20655    | 43        | 1.42%   |
| 0x08701013 | 34        | 1.12%   |
| 0x106e5    | 31        | 1.02%   |
| 0x0800820d | 30        | 0.99%   |
| 0x10676    | 28        | 0.92%   |
| 0x30678    | 26        | 0.86%   |
| 0x20652    | 24        | 0.79%   |
| 0x0a50000c | 23        | 0.76%   |
| 0xa0652    | 22        | 0.73%   |
| 0x706e5    | 22        | 0.73%   |
| 0x06000852 | 22        | 0.73%   |
| 0x106a5    | 21        | 0.69%   |
| 0x906ed    | 19        | 0.63%   |
| 0x06006705 | 19        | 0.63%   |
| 0x806eb    | 18        | 0.59%   |
| 0x0a201016 | 18        | 0.59%   |
| 0x08108109 | 18        | 0.59%   |
| 0x06001119 | 18        | 0.59%   |
| 0x010000c8 | 18        | 0.59%   |
| 0x6fb      | 17        | 0.56%   |
| 0x206c2    | 17        | 0.56%   |
| 0x6f6      | 16        | 0.53%   |
| 0x08001138 | 16        | 0.53%   |
| 0x6fd      | 15        | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 472       | 16.15%  |
| Haswell          | 288       | 9.85%   |
| SandyBridge      | 223       | 7.63%   |
| IvyBridge        | 221       | 7.56%   |
| Skylake          | 171       | 5.85%   |
| Zen 2            | 156       | 5.34%   |
| Penryn           | 140       | 4.79%   |
| Westmere         | 106       | 3.63%   |
| Zen 3            | 105       | 3.59%   |
| Unknown          | 99        | 3.39%   |
| Zen+             | 74        | 2.53%   |
| CometLake        | 68        | 2.33%   |
| Core             | 67        | 2.29%   |
| Zen              | 64        | 2.19%   |
| Silvermont       | 63        | 2.16%   |
| Nehalem          | 63        | 2.16%   |
| TigerLake        | 62        | 2.12%   |
| Broadwell        | 60        | 2.05%   |
| Piledriver       | 56        | 1.92%   |
| K10              | 51        | 1.74%   |
| IceLake          | 50        | 1.71%   |
| Excavator        | 38        | 1.3%    |
| Goldmont plus    | 32        | 1.09%   |
| Alderlake Hybrid | 29        | 0.99%   |
| Puma             | 21        | 0.72%   |
| Goldmont         | 20        | 0.68%   |
| Bonnell          | 16        | 0.55%   |
| Steamroller      | 15        | 0.51%   |
| NetBurst         | 14        | 0.48%   |
| Jaguar           | 13        | 0.44%   |
| Bulldozer        | 13        | 0.44%   |
| P6               | 12        | 0.41%   |
| K8 Hammer        | 12        | 0.41%   |
| K10 Llano        | 12        | 0.41%   |
| Bobcat           | 9         | 0.31%   |
| Tremont          | 6         | 0.21%   |
| K8 & K10 hybrid  | 2         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1547      | 45.31%  |
| Nvidia                           | 1063      | 31.14%  |
| AMD                              | 774       | 22.67%  |
| Matrox Electronics Systems       | 19        | 0.56%   |
| VIA Technologies                 | 4         | 0.12%   |
| Silicon Integrated Systems [SiS] | 3         | 0.09%   |
| Neomagic                         | 2         | 0.06%   |
| ASPEED Technology                | 2         | 0.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 151       | 4.29%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 99        | 2.81%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 82        | 2.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 74        | 2.1%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 72        | 2.04%   |
| Intel UHD Graphics 620                                                                   | 68        | 1.93%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 68        | 1.93%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 67        | 1.9%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 58        | 1.65%   |
| Intel HD Graphics 620                                                                    | 57        | 1.62%   |
| Intel Core Processor Integrated Graphics Controller                                      | 53        | 1.5%    |
| Intel HD Graphics 530                                                                    | 50        | 1.42%   |
| Intel HD Graphics 630                                                                    | 44        | 1.25%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 44        | 1.25%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 43        | 1.22%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 43        | 1.22%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 40        | 1.14%   |
| Intel HD Graphics 5500                                                                   | 34        | 0.97%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 34        | 0.97%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 34        | 0.97%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 34        | 0.97%   |
| AMD Renoir                                                                               | 33        | 0.94%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 33        | 0.94%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 29        | 0.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 29        | 0.82%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 29        | 0.82%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 28        | 0.79%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 28        | 0.79%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 27        | 0.77%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 26        | 0.74%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 24        | 0.68%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 23        | 0.65%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 23        | 0.65%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 23        | 0.65%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 21        | 0.6%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 20        | 0.57%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 19        | 0.54%   |
| Intel Iris Plus Graphics G7                                                              | 19        | 0.54%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 18        | 0.51%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 17        | 0.48%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1077      | 36.43%  |
| 1 x Nvidia               | 665       | 22.5%   |
| 1 x AMD                  | 613       | 20.74%  |
| Intel + Nvidia           | 348       | 11.77%  |
| Intel + AMD              | 68        | 2.3%    |
| 2 x AMD                  | 54        | 1.83%   |
| Other                    | 43        | 1.45%   |
| AMD + Nvidia             | 41        | 1.39%   |
| 1 x Matrox               | 16        | 0.54%   |
| 2 x Nvidia               | 10        | 0.34%   |
| 1 x VIA                  | 4         | 0.14%   |
| 1 x SiS                  | 3         | 0.1%    |
| Nvidia + Matrox          | 3         | 0.1%    |
| Intel + AMD + 1 x Nvidia | 3         | 0.1%    |
| 2 x Intel                | 2         | 0.07%   |
| Nvidia + ASPEED          | 2         | 0.07%   |
| 1 x Neomagic             | 2         | 0.07%   |
| Intel + 2 x Nvidia       | 1         | 0.03%   |
| Intel + 2 x AMD          | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2246      | 75.02%  |
| Proprietary | 597       | 19.94%  |
| Unknown     | 151       | 5.04%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1577      | 52.15%  |
| 1.01-2.0   | 383       | 12.67%  |
| 0.01-0.5   | 268       | 8.86%   |
| 0.51-1.0   | 237       | 7.84%   |
| 3.01-4.0   | 223       | 7.37%   |
| 7.01-8.0   | 178       | 5.89%   |
| 5.01-6.0   | 73        | 2.41%   |
| 8.01-16.0  | 46        | 1.52%   |
| 2.01-3.0   | 28        | 0.93%   |
| 16.01-24.0 | 8         | 0.26%   |
| 4.01-5.0   | 2         | 0.07%   |
| 32.01-64.0 | 1         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 406       | 12.34%  |
| AU Optronics            | 318       | 9.66%   |
| Dell                    | 253       | 7.69%   |
| LG Display              | 235       | 7.14%   |
| Chimei Innolux          | 186       | 5.65%   |
| Acer                    | 159       | 4.83%   |
| BOE                     | 147       | 4.47%   |
| Goldstar                | 139       | 4.22%   |
| Hewlett-Packard         | 135       | 4.1%    |
| BenQ                    | 131       | 3.98%   |
| Apple                   | 117       | 3.56%   |
| Philips                 | 106       | 3.22%   |
| Ancor Communications    | 94        | 2.86%   |
| AOC                     | 87        | 2.64%   |
| Sharp                   | 78        | 2.37%   |
| ViewSonic               | 66        | 2.01%   |
| Lenovo                  | 66        | 2.01%   |
| Unknown                 | 56        | 1.7%    |
| Chi Mei Optoelectronics | 43        | 1.31%   |
| ASUSTek Computer        | 36        | 1.09%   |
| Sony                    | 33        | 1%      |
| ___                     | 28        | 0.85%   |
| Panasonic               | 25        | 0.76%   |
| LG Electronics          | 25        | 0.76%   |
| Kogan                   | 23        | 0.7%    |
| PANDA                   | 20        | 0.61%   |
| GKK                     | 17        | 0.52%   |
| Toshiba                 | 15        | 0.46%   |
| Hitachi                 | 13        | 0.4%    |
| Unknown (XXX)           | 11        | 0.33%   |
| SAC                     | 11        | 0.33%   |
| MSI                     | 10        | 0.3%    |
| Gigabyte Technology     | 10        | 0.3%    |
| TCL                     | 8         | 0.24%   |
| Eizo                    | 8         | 0.24%   |
| CVT                     | 8         | 0.24%   |
| MStar                   | 7         | 0.21%   |
| MiTAC                   | 7         | 0.21%   |
| InfoVision              | 7         | 0.21%   |
| eMachines               | 7         | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM01D3 1440x900 408x225mm 18.3-inch      | 21        | 0.61%   |
| ___ LCDTV16 ___0101 1360x768                                             | 19        | 0.55%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 17        | 0.49%   |
| ViewSonic VA2226w-3 VSC2051 1680x1050 490x290mm 22.4-inch                | 12        | 0.35%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 11        | 0.32%   |
| Panasonic VVX16T029D00 MEI96A2 2880x1620 344x193mm 15.5-inch             | 11        | 0.32%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 11        | 0.32%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 11        | 0.32%   |
| ___ LCD TV ___9000 1360x768                                              | 10        | 0.29%   |
| Unknown LCDTV16 0101 1920x1080 1600x900mm 72.3-inch                      | 10        | 0.29%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                  | 10        | 0.29%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 9         | 0.26%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                        | 9         | 0.26%   |
| BenQ G2420HD BNQ7840 1920x1080 531x299mm 24.0-inch                       | 9         | 0.26%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 9         | 0.26%   |
| Unknown (XXX) Beyond TV XXX2851 1920x1080 1209x680mm 54.6-inch           | 8         | 0.23%   |
| Samsung Electronics LCD Monitor SAM2C35 1024x768 280x210mm 13.8-inch     | 8         | 0.23%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 8         | 0.23%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 8         | 0.23%   |
| Apple iMac APPA007 2560x1440 597x336mm 27.0-inch                         | 8         | 0.23%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch        | 7         | 0.2%    |
| SAC LED MONITOR SAC952D 1920x1080 443x249mm 20.0-inch                    | 7         | 0.2%    |
| LG Display LCD Monitor LGD0555 2736x1824 260x173mm 12.3-inch             | 7         | 0.2%    |
| CVT CVTE TV CVT0003 1360x768 575x323mm 26.0-inch                         | 7         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 7         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 7         | 0.2%    |
| Chimei Innolux LCD Monitor CMN1514 1920x1080 344x193mm 15.5-inch         | 7         | 0.2%    |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                     | 7         | 0.2%    |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                          | 7         | 0.2%    |
| Ancor Communications MW221 ACI22B1 1680x1050 473x296mm 22.0-inch         | 7         | 0.2%    |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                       | 6         | 0.17%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 6         | 0.17%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                  | 6         | 0.17%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 6         | 0.17%   |
| Kogan KAMN34FXQULA KGN3400 3440x1440 797x334mm 34.0-inch                 | 6         | 0.17%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 6         | 0.17%   |
| eMachines E190HQV EMA0212 1366x768 409x230mm 18.5-inch                   | 6         | 0.17%   |
| Dell S2721DGF DEL41D9 2560x1440 597x336mm 27.0-inch                      | 6         | 0.17%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 6         | 0.17%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 6         | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1336      | 42.63%  |
| 1366x768 (WXGA)    | 456       | 14.55%  |
| 3840x2160 (4K)     | 272       | 8.68%   |
| 2560x1440 (QHD)    | 171       | 5.46%   |
| 1680x1050 (WSXGA+) | 118       | 3.77%   |
| 1280x1024 (SXGA)   | 108       | 3.45%   |
| 1440x900 (WXGA+)   | 91        | 2.9%    |
| 1920x1200 (WUXGA)  | 87        | 2.78%   |
| 1600x900 (HD+)     | 69        | 2.2%    |
| 1280x800 (WXGA)    | 58        | 1.85%   |
| Unknown            | 52        | 1.66%   |
| 3440x1440          | 41        | 1.31%   |
| 2560x1600          | 25        | 0.8%    |
| 3840x1080          | 24        | 0.77%   |
| 1360x768           | 20        | 0.64%   |
| 2560x1080          | 19        | 0.61%   |
| 2880x1800          | 16        | 0.51%   |
| 3840x2400          | 15        | 0.48%   |
| 2736x1824          | 10        | 0.32%   |
| 3200x1800 (QHD+)   | 9         | 0.29%   |
| 1920x540           | 9         | 0.29%   |
| 1280x768           | 9         | 0.29%   |
| 2160x1440          | 7         | 0.22%   |
| 1920x1280          | 7         | 0.22%   |
| 1280x720 (HD)      | 7         | 0.22%   |
| 2256x1504          | 6         | 0.19%   |
| 1024x768 (XGA)     | 6         | 0.19%   |
| 1024x600           | 6         | 0.19%   |
| 3840x1600          | 5         | 0.16%   |
| 5760x2160          | 4         | 0.13%   |
| 5120x1440          | 4         | 0.13%   |
| 4480x1440          | 4         | 0.13%   |
| 3600x1080          | 4         | 0.13%   |
| 3072x1920          | 4         | 0.13%   |
| 2240x1400          | 4         | 0.13%   |
| 1600x1200          | 4         | 0.13%   |
| 800x1280           | 3         | 0.1%    |
| 3200x1080          | 3         | 0.1%    |
| 2288x1287          | 3         | 0.1%    |
| 7680x2160          | 2         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 613       | 18.71%  |
| 27      | 328       | 10.01%  |
| 13      | 271       | 8.27%   |
| 24      | 268       | 8.18%   |
| 23      | 241       | 7.36%   |
| Unknown | 212       | 6.47%   |
| 21      | 183       | 5.59%   |
| 14      | 182       | 5.56%   |
| 17      | 127       | 3.88%   |
| 19      | 125       | 3.82%   |
| 31      | 110       | 3.36%   |
| 22      | 85        | 2.59%   |
| 12      | 61        | 1.86%   |
| 34      | 53        | 1.62%   |
| 72      | 49        | 1.5%    |
| 20      | 47        | 1.43%   |
| 11      | 46        | 1.4%    |
| 18      | 35        | 1.07%   |
| 84      | 26        | 0.79%   |
| 26      | 20        | 0.61%   |
| 54      | 19        | 0.58%   |
| 32      | 18        | 0.55%   |
| 16      | 15        | 0.46%   |
| 52      | 14        | 0.43%   |
| 40      | 14        | 0.43%   |
| 48      | 12        | 0.37%   |
| 42      | 9         | 0.27%   |
| 25      | 9         | 0.27%   |
| 37      | 8         | 0.24%   |
| 29      | 8         | 0.24%   |
| 10      | 8         | 0.24%   |
| 35      | 7         | 0.21%   |
| 55      | 6         | 0.18%   |
| 46      | 5         | 0.15%   |
| 63      | 4         | 0.12%   |
| 36      | 4         | 0.12%   |
| 49      | 3         | 0.09%   |
| 30      | 3         | 0.09%   |
| 28      | 3         | 0.09%   |
| 7       | 3         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 908       | 28.39%  |
| 501-600        | 757       | 23.67%  |
| 401-500        | 384       | 12.01%  |
| 201-300        | 290       | 9.07%   |
| Unknown        | 212       | 6.63%   |
| 351-400        | 203       | 6.35%   |
| 601-700        | 170       | 5.32%   |
| 1501-2000      | 79        | 2.47%   |
| 701-800        | 73        | 2.28%   |
| 1001-1500      | 72        | 2.25%   |
| 801-900        | 32        | 1%      |
| 901-1000       | 11        | 0.34%   |
| 1-100          | 3         | 0.09%   |
| More than 2000 | 2         | 0.06%   |
| 101-200        | 2         | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2082      | 71.42%  |
| 16/10   | 396       | 13.58%  |
| Unknown | 179       | 6.14%   |
| 5/4     | 94        | 3.22%   |
| 21/9    | 66        | 2.26%   |
| 3/2     | 42        | 1.44%   |
| 4/3     | 27        | 0.93%   |
| 32/9    | 12        | 0.41%   |
| 6/5     | 10        | 0.34%   |
| 0.67    | 3         | 0.1%    |
| 1.00    | 2         | 0.07%   |
| 3.40    | 1         | 0.03%   |
| 0.62    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 635       | 19.66%  |
| 101-110        | 612       | 18.95%  |
| 301-350        | 342       | 10.59%  |
| 81-90          | 319       | 9.88%   |
| 151-200        | 214       | 6.63%   |
| Unknown        | 212       | 6.56%   |
| 351-500        | 193       | 5.98%   |
| 71-80          | 136       | 4.21%   |
| More than 1000 | 134       | 4.15%   |
| 251-300        | 95        | 2.94%   |
| 121-130        | 90        | 2.79%   |
| 501-1000       | 56        | 1.73%   |
| 61-70          | 50        | 1.55%   |
| 51-60          | 48        | 1.49%   |
| 141-150        | 46        | 1.42%   |
| 111-120        | 15        | 0.46%   |
| 131-140        | 10        | 0.31%   |
| 91-100         | 10        | 0.31%   |
| 41-50          | 8         | 0.25%   |
| 1-40           | 5         | 0.15%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1141      | 36.77%  |
| 101-120       | 715       | 23.04%  |
| 121-160       | 624       | 20.11%  |
| Unknown       | 212       | 6.83%   |
| 161-240       | 198       | 6.38%   |
| More than 240 | 108       | 3.48%   |
| 1-50          | 105       | 3.38%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 2309      | 75.73%  |
| 2     | 518       | 16.99%  |
| 0     | 151       | 4.95%   |
| 3     | 63        | 2.07%   |
| 4     | 8         | 0.26%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1514      | 33.71%  |
| Realtek Semiconductor           | 1485      | 33.07%  |
| Qualcomm Atheros                | 465       | 10.35%  |
| Broadcom                        | 303       | 6.75%   |
| Broadcom Limited                | 67        | 1.49%   |
| Ralink                          | 57        | 1.27%   |
| Marvell Technology Group        | 57        | 1.27%   |
| Ralink Technology               | 46        | 1.02%   |
| TP-Link                         | 40        | 0.89%   |
| Samsung Electronics             | 31        | 0.69%   |
| MediaTek                        | 30        | 0.67%   |
| NetGear                         | 23        | 0.51%   |
| DisplayLink                     | 23        | 0.51%   |
| Sierra Wireless                 | 20        | 0.45%   |
| Nvidia                          | 19        | 0.42%   |
| Huawei Technologies             | 19        | 0.42%   |
| D-Link                          | 19        | 0.42%   |
| Aquantia                        | 19        | 0.42%   |
| Edimax Technology               | 17        | 0.38%   |
| D-Link System                   | 17        | 0.38%   |
| Dell                            | 15        | 0.33%   |
| Microsoft                       | 14        | 0.31%   |
| ZTE WCDMA Technologies MSM      | 13        | 0.29%   |
| ASIX Electronics                | 13        | 0.29%   |
| Apple                           | 12        | 0.27%   |
| Motorola PCS                    | 10        | 0.22%   |
| Lenovo                          | 10        | 0.22%   |
| ASUSTek Computer                | 10        | 0.22%   |
| OPPO Electronics                | 8         | 0.18%   |
| Google                          | 8         | 0.18%   |
| VIA Technologies                | 7         | 0.16%   |
| Hewlett-Packard                 | 7         | 0.16%   |
| Qualcomm Atheros Communications | 6         | 0.13%   |
| ICS Advent                      | 6         | 0.13%   |
| Qualcomm                        | 5         | 0.11%   |
| Mellanox Technologies           | 5         | 0.11%   |
| Arduino SA                      | 5         | 0.11%   |
| Standard Microsystems           | 4         | 0.09%   |
| Microchip Technology            | 4         | 0.09%   |
| JMicron Technology              | 4         | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1010      | 19.15%  |
| Intel Wi-Fi 6 AX200                                               | 152       | 2.88%   |
| Intel I211 Gigabit Network Connection                             | 120       | 2.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 120       | 2.27%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 119       | 2.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 106       | 2.01%   |
| Intel Wireless 8265 / 8275                                        | 80        | 1.52%   |
| Realtek RTL8125 2.5GbE Controller                                 | 77        | 1.46%   |
| Intel Wireless 8260                                               | 69        | 1.31%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 62        | 1.18%   |
| Intel Ethernet Connection (2) I219-V                              | 59        | 1.12%   |
| Intel Wireless 7265                                               | 57        | 1.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 54        | 1.02%   |
| Intel Wireless 7260                                               | 52        | 0.99%   |
| Intel Ethernet Connection I217-LM                                 | 52        | 0.99%   |
| Intel Wi-Fi 6 AX201                                               | 50        | 0.95%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 49        | 0.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 47        | 0.89%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 44        | 0.83%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 43        | 0.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 42        | 0.8%    |
| Intel Wireless 3165                                               | 42        | 0.8%    |
| Intel Ethernet Controller I225-V                                  | 42        | 0.8%    |
| Intel Ethernet Connection (7) I219-V                              | 41        | 0.78%   |
| Intel Wireless-AC 9260                                            | 39        | 0.74%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 38        | 0.72%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 37        | 0.7%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 37        | 0.7%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 37        | 0.7%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 35        | 0.66%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 34        | 0.64%   |
| Intel Centrino Ultimate-N 6300                                    | 32        | 0.61%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 31        | 0.59%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 31        | 0.59%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 29        | 0.55%   |
| Intel Ethernet Connection (2) I219-LM                             | 28        | 0.53%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 28        | 0.53%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 28        | 0.53%   |
| Realtek 802.11ac NIC                                              | 27        | 0.51%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 27        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1060      | 45.91%  |
| Qualcomm Atheros                | 347       | 15.03%  |
| Realtek Semiconductor           | 328       | 14.21%  |
| Broadcom                        | 205       | 8.88%   |
| Ralink                          | 57        | 2.47%   |
| Broadcom Limited                | 47        | 2.04%   |
| Ralink Technology               | 46        | 1.99%   |
| TP-Link                         | 38        | 1.65%   |
| MediaTek                        | 26        | 1.13%   |
| NetGear                         | 22        | 0.95%   |
| Sierra Wireless                 | 20        | 0.87%   |
| Marvell Technology Group        | 19        | 0.82%   |
| Edimax Technology               | 17        | 0.74%   |
| D-Link System                   | 12        | 0.52%   |
| D-Link                          | 11        | 0.48%   |
| Microsoft                       | 10        | 0.43%   |
| ASUSTek Computer                | 10        | 0.43%   |
| Dell                            | 8         | 0.35%   |
| Qualcomm Atheros Communications | 6         | 0.26%   |
| BUFFALO                         | 3         | 0.13%   |
| Belkin Components               | 3         | 0.13%   |
| Wacom                           | 2         | 0.09%   |
| Qualcomm                        | 2         | 0.09%   |
| Linksys                         | 2         | 0.09%   |
| AVM                             | 2         | 0.09%   |
| Xiaomi                          | 1         | 0.04%   |
| Wilocity                        | 1         | 0.04%   |
| Toshiba                         | 1         | 0.04%   |
| IMC Networks                    | 1         | 0.04%   |
| Hewlett-Packard                 | 1         | 0.04%   |
| AboCom Systems                  | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 152       | 6.55%   |
| Intel Wireless 8265 / 8275                                     | 80        | 3.45%   |
| Intel Wireless 8260                                            | 69        | 2.97%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 62        | 2.67%   |
| Intel Wireless 7265                                            | 57        | 2.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 54        | 2.33%   |
| Intel Wireless 7260                                            | 52        | 2.24%   |
| Intel Wi-Fi 6 AX201                                            | 50        | 2.15%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 49        | 2.11%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 47        | 2.02%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 44        | 1.89%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 43        | 1.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 42        | 1.81%   |
| Intel Wireless 3165                                            | 42        | 1.81%   |
| Intel Wireless-AC 9260                                         | 39        | 1.68%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 38        | 1.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 37        | 1.59%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 37        | 1.59%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 37        | 1.59%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 35        | 1.51%   |
| Intel Centrino Ultimate-N 6300                                 | 32        | 1.38%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 31        | 1.34%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 31        | 1.34%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 28        | 1.21%   |
| Realtek 802.11ac NIC                                           | 27        | 1.16%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 27        | 1.16%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 25        | 1.08%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 24        | 1.03%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 23        | 0.99%   |
| Intel Wireless 3160                                            | 21        | 0.9%    |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 20        | 0.86%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 20        | 0.86%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 20        | 0.86%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 19        | 0.82%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 19        | 0.82%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless              | 18        | 0.78%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 17        | 0.73%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 17        | 0.73%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 17        | 0.73%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 16        | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1322      | 47.18%  |
| Intel                            | 855       | 30.51%  |
| Qualcomm Atheros                 | 169       | 6.03%   |
| Broadcom                         | 152       | 5.42%   |
| Marvell Technology Group         | 38        | 1.36%   |
| Samsung Electronics              | 31        | 1.11%   |
| DisplayLink                      | 23        | 0.82%   |
| Broadcom Limited                 | 20        | 0.71%   |
| Nvidia                           | 19        | 0.68%   |
| Aquantia                         | 19        | 0.68%   |
| Huawei Technologies              | 14        | 0.5%    |
| ZTE WCDMA Technologies MSM       | 13        | 0.46%   |
| ASIX Electronics                 | 13        | 0.46%   |
| Apple                            | 12        | 0.43%   |
| Lenovo                           | 10        | 0.36%   |
| OPPO Electronics                 | 8         | 0.29%   |
| Google                           | 8         | 0.29%   |
| D-Link                           | 8         | 0.29%   |
| VIA Technologies                 | 7         | 0.25%   |
| Motorola PCS                     | 6         | 0.21%   |
| ICS Advent                       | 6         | 0.21%   |
| D-Link System                    | 5         | 0.18%   |
| Standard Microsystems            | 4         | 0.14%   |
| Microchip Technology             | 4         | 0.14%   |
| JMicron Technology               | 4         | 0.14%   |
| Microsoft                        | 3         | 0.11%   |
| MediaTek                         | 3         | 0.11%   |
| IBM                              | 3         | 0.11%   |
| Xiaomi                           | 2         | 0.07%   |
| Silicon Integrated Systems [SiS] | 2         | 0.07%   |
| Qualcomm                         | 2         | 0.07%   |
| QLogic                           | 2         | 0.07%   |
| NetGear                          | 2         | 0.07%   |
| Mellanox Technologies            | 2         | 0.07%   |
| Hewlett-Packard                  | 2         | 0.07%   |
| Dell                             | 2         | 0.07%   |
| vivo                             | 1         | 0.04%   |
| TP-Link                          | 1         | 0.04%   |
| T & A Mobile Phones              | 1         | 0.04%   |
| HMD Global                       | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1010      | 34.89%  |
| Intel I211 Gigabit Network Connection                             | 120       | 4.15%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 120       | 4.15%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 119       | 4.11%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 106       | 3.66%   |
| Realtek RTL8125 2.5GbE Controller                                 | 77        | 2.66%   |
| Intel Ethernet Connection (2) I219-V                              | 59        | 2.04%   |
| Intel Ethernet Connection I217-LM                                 | 52        | 1.8%    |
| Intel Ethernet Controller I225-V                                  | 42        | 1.45%   |
| Intel Ethernet Connection (7) I219-V                              | 41        | 1.42%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 34        | 1.17%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 29        | 1%      |
| Intel Ethernet Connection (2) I219-LM                             | 28        | 0.97%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 28        | 0.97%   |
| Intel Ethernet Connection I219-LM                                 | 27        | 0.93%   |
| Intel 82579V Gigabit Network Connection                           | 26        | 0.9%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 24        | 0.83%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 22        | 0.76%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 22        | 0.76%   |
| Intel Ethernet Connection I217-V                                  | 21        | 0.73%   |
| Intel 82577LM Gigabit Network Connection                          | 19        | 0.66%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 19        | 0.66%   |
| Intel I210 Gigabit Network Connection                             | 18        | 0.62%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 17        | 0.59%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 17        | 0.59%   |
| Intel Ethernet Connection (4) I219-LM                             | 17        | 0.59%   |
| Intel 82574L Gigabit Network Connection                           | 17        | 0.59%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 17        | 0.59%   |
| Intel Ethernet Connection (2) I218-V                              | 16        | 0.55%   |
| Intel Ethernet Connection (4) I219-V                              | 15        | 0.52%   |
| Intel Ethernet Connection I219-V                                  | 12        | 0.41%   |
| Intel Ethernet Connection (3) I218-LM                             | 12        | 0.41%   |
| Intel Ethernet Connection (10) I219-V                             | 12        | 0.41%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 11        | 0.38%   |
| Intel Ethernet Connection I218-LM                                 | 11        | 0.38%   |
| Intel Ethernet Connection (6) I219-V                              | 11        | 0.38%   |
| Intel 82578DM Gigabit Network Connection                          | 11        | 0.38%   |
| Intel 82546EB Gigabit Ethernet Controller (Copper)                | 11        | 0.38%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 11        | 0.38%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 10        | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2527      | 53.3%   |
| WiFi     | 2157      | 45.5%   |
| Modem    | 44        | 0.93%   |
| Unknown  | 13        | 0.27%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1627      | 53.79%  |
| Ethernet | 1398      | 46.21%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1538      | 52.19%  |
| 1     | 1192      | 40.45%  |
| 3     | 112       | 3.8%    |
| 0     | 73        | 2.48%   |
| 4     | 20        | 0.68%   |
| 5     | 8         | 0.27%   |
| 6     | 3         | 0.1%    |
| 8     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2610      | 87.79%  |
| Yes  | 363       | 12.21%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 863       | 50.38%  |
| Broadcom                        | 119       | 6.95%   |
| Apple                           | 117       | 6.83%   |
| Cambridge Silicon Radio         | 110       | 6.42%   |
| Realtek Semiconductor           | 107       | 6.25%   |
| Qualcomm Atheros Communications | 107       | 6.25%   |
| Lite-On Technology              | 45        | 2.63%   |
| IMC Networks                    | 43        | 2.51%   |
| Foxconn / Hon Hai               | 37        | 2.16%   |
| Toshiba                         | 36        | 2.1%    |
| ASUSTek Computer                | 24        | 1.4%    |
| Hewlett-Packard                 | 18        | 1.05%   |
| Marvell Semiconductor           | 17        | 0.99%   |
| Ralink                          | 16        | 0.93%   |
| Dell                            | 16        | 0.93%   |
| MediaTek                        | 6         | 0.35%   |
| Alps Electric                   | 6         | 0.35%   |
| Realtek                         | 5         | 0.29%   |
| Edimax Technology               | 5         | 0.29%   |
| USI                             | 3         | 0.18%   |
| TP-Link                         | 3         | 0.18%   |
| Ralink Technology               | 3         | 0.18%   |
| Integrated System Solution      | 2         | 0.12%   |
| Belkin Components               | 2         | 0.12%   |
| Opticis                         | 1         | 0.06%   |
| Logitech                        | 1         | 0.06%   |
| Creative Technology             | 1         | 0.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 305       | 17.78%  |
| Intel AX201 Bluetooth                               | 153       | 8.92%   |
| Intel AX200 Bluetooth                               | 147       | 8.57%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 110       | 6.41%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 96        | 5.6%    |
| Realtek Bluetooth Radio                             | 58        | 3.38%   |
| Apple Bluetooth Host Controller                     | 52        | 3.03%   |
| Qualcomm Atheros  Bluetooth Device                  | 44        | 2.57%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 44        | 2.57%   |
| Intel Wireless-AC 3168 Bluetooth                    | 43        | 2.51%   |
| Realtek  Bluetooth 4.2 Adapter                      | 36        | 2.1%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 35        | 2.04%   |
| Apple Bluetooth USB Host Controller                 | 32        | 1.87%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 28        | 1.63%   |
| Intel AX210 Bluetooth                               | 27        | 1.57%   |
| Intel Bluetooth Device                              | 24        | 1.4%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 22        | 1.28%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 21        | 1.22%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 19        | 1.11%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 17        | 0.99%   |
| Ralink RT3290 Bluetooth                             | 16        | 0.93%   |
| Broadcom BCM2045B (BDC-2.1)                         | 16        | 0.93%   |
| IMC Networks Bluetooth Radio                        | 15        | 0.87%   |
| Marvell Bluetooth and Wireless LAN Composite        | 14        | 0.82%   |
| Lite-On Bluetooth Device                            | 13        | 0.76%   |
| Foxconn / Hon Hai Bluetooth Device                  | 13        | 0.76%   |
| Toshiba Bluetooth Device                            | 12        | 0.7%    |
| Lite-On Atheros AR3012 Bluetooth                    | 12        | 0.7%    |
| Apple Bluetooth HCI                                 | 12        | 0.7%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 11        | 0.64%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 10        | 0.58%   |
| HP Broadcom 2070 Bluetooth Combo                    | 10        | 0.58%   |
| Broadcom HP Portable Bumble Bee                     | 10        | 0.58%   |
| Toshiba Integrated Bluetooth HCI                    | 8         | 0.47%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 8         | 0.47%   |
| Foxconn / Hon Hai Wireless_Device                   | 8         | 0.47%   |
| Broadcom HP Portable SoftSailing                    | 8         | 0.47%   |
| IMC Networks Bluetooth Device                       | 7         | 0.41%   |
| Dell BCM20702A0 Bluetooth Module                    | 7         | 0.41%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 7         | 0.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 2107      | 49.09%  |
| AMD                                  | 875       | 20.39%  |
| Nvidia                               | 800       | 18.64%  |
| C-Media Electronics                  | 57        | 1.33%   |
| Logitech                             | 51        | 1.19%   |
| Creative Labs                        | 29        | 0.68%   |
| Realtek Semiconductor                | 24        | 0.56%   |
| Texas Instruments                    | 19        | 0.44%   |
| Kingston Technology                  | 18        | 0.42%   |
| Creative Technology                  | 16        | 0.37%   |
| Razer USA                            | 15        | 0.35%   |
| GN Netcom                            | 14        | 0.33%   |
| Generalplus Technology               | 14        | 0.33%   |
| Apple                                | 14        | 0.33%   |
| Plantronics                          | 13        | 0.3%    |
| RODE Microphones                     | 11        | 0.26%   |
| Lenovo                               | 8         | 0.19%   |
| JMTek                                | 8         | 0.19%   |
| Corsair                              | 8         | 0.19%   |
| Blue Microphones                     | 8         | 0.19%   |
| VIA Technologies                     | 7         | 0.16%   |
| SteelSeries ApS                      | 7         | 0.16%   |
| Dell                                 | 7         | 0.16%   |
| Astro Gaming                         | 7         | 0.16%   |
| M-Audio                              | 6         | 0.14%   |
| Hewlett-Packard                      | 6         | 0.14%   |
| Cambridge Silicon Radio              | 6         | 0.14%   |
| Thesycon Systemsoftware & Consulting | 5         | 0.12%   |
| OPPO Electronics                     | 5         | 0.12%   |
| Microsoft                            | 5         | 0.12%   |
| Micro Star International             | 5         | 0.12%   |
| Focusrite-Novation                   | 5         | 0.12%   |
| ASUSTek Computer                     | 5         | 0.12%   |
| Sennheiser Communications            | 4         | 0.09%   |
| Samson Technologies                  | 4         | 0.09%   |
| PreSonus Audio Electronics           | 4         | 0.09%   |
| Giga-Byte Technology                 | 4         | 0.09%   |
| DSEA A/S                             | 4         | 0.09%   |
| Chicony Electronics                  | 4         | 0.09%   |
| Audio-Technica                       | 4         | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 219       | 4.38%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 213       | 4.26%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 201       | 4.02%   |
| AMD Starship/Matisse HD Audio Controller                                   | 182       | 3.64%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 171       | 3.42%   |
| AMD Family 17h/19h HD Audio Controller                                     | 155       | 3.1%    |
| Intel Cannon Lake PCH cAVS                                                 | 124       | 2.48%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 121       | 2.42%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 118       | 2.36%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 95        | 1.9%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 90        | 1.8%    |
| AMD FCH Azalia Controller                                                  | 86        | 1.72%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 83        | 1.66%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 76        | 1.52%   |
| Intel 8 Series HD Audio Controller                                         | 74        | 1.48%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 74        | 1.48%   |
| Intel Haswell-ULT HD Audio Controller                                      | 73        | 1.46%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 71        | 1.42%   |
| Intel 200 Series PCH HD Audio                                              | 69        | 1.38%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 63        | 1.26%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 61        | 1.22%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 58        | 1.16%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 56        | 1.12%   |
| Nvidia TU116 High Definition Audio Controller                              | 54        | 1.08%   |
| Nvidia GP107GL High Definition Audio Controller                            | 52        | 1.04%   |
| Intel Broadwell-U Audio Controller                                         | 52        | 1.04%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 51        | 1.02%   |
| Nvidia GP104 High Definition Audio Controller                              | 50        | 1%      |
| Intel Comet Lake PCH-LP cAVS                                               | 48        | 0.96%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 48        | 0.96%   |
| Nvidia TU106 High Definition Audio Controller                              | 46        | 0.92%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 46        | 0.92%   |
| Intel Comet Lake PCH cAVS                                                  | 45        | 0.9%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 44        | 0.88%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 42        | 0.84%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 41        | 0.82%   |
| Nvidia GF108 High Definition Audio Controller                              | 40        | 0.8%    |
| AMD Kabini HDMI/DP Audio                                                   | 40        | 0.8%    |
| Nvidia GK107 HDMI Audio Controller                                         | 38        | 0.76%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 38        | 0.76%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 329       | 20.61%  |
| SK hynix            | 272       | 17.04%  |
| Kingston            | 180       | 11.28%  |
| Micron Technology   | 161       | 10.09%  |
| Corsair             | 147       | 9.21%   |
| Unknown             | 131       | 8.21%   |
| Crucial             | 102       | 6.39%   |
| G.Skill             | 88        | 5.51%   |
| Team                | 27        | 1.69%   |
| Nanya Technology    | 23        | 1.44%   |
| Elpida              | 23        | 1.44%   |
| Ramaxel Technology  | 15        | 0.94%   |
| Patriot             | 15        | 0.94%   |
| A-DATA Technology   | 13        | 0.81%   |
| Transcend           | 9         | 0.56%   |
| Apacer              | 9         | 0.56%   |
| Unknown             | 6         | 0.38%   |
| Unknown (ABCD)      | 4         | 0.25%   |
| Strontium           | 4         | 0.25%   |
| Silicon Power       | 4         | 0.25%   |
| Neo Forza           | 4         | 0.25%   |
| GeIL                | 4         | 0.25%   |
| Toshiba             | 2         | 0.13%   |
| Smart               | 2         | 0.13%   |
| pqi                 | 2         | 0.13%   |
| Hewlett-Packard     | 2         | 0.13%   |
| Avant               | 2         | 0.13%   |
| Unknown (0x89AD)    | 1         | 0.06%   |
| Unknown (0x873E)    | 1         | 0.06%   |
| Unknown (0x0562)    | 1         | 0.06%   |
| Undefi              | 1         | 0.06%   |
| Qimonda             | 1         | 0.06%   |
| Princeton           | 1         | 0.06%   |
| PNY                 | 1         | 0.06%   |
| Netlist             | 1         | 0.06%   |
| Innodisk            | 1         | 0.06%   |
| GSkill              | 1         | 0.06%   |
| Goldenmars          | 1         | 0.06%   |
| Golden Empire       | 1         | 0.06%   |
| GIGA-BYTE           | 1         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s         | 18        | 1.04%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s         | 15        | 0.87%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s         | 14        | 0.81%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s         | 12        | 0.7%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s         | 11        | 0.64%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s         | 11        | 0.64%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s        | 10        | 0.58%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s        | 10        | 0.58%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s         | 10        | 0.58%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s        | 10        | 0.58%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s        | 9         | 0.52%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s         | 9         | 0.52%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                       | 8         | 0.46%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 8         | 0.46%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s         | 8         | 0.46%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s | 8         | 0.46%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                        | 7         | 0.41%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 7         | 0.41%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s       | 7         | 0.41%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 7         | 0.41%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s         | 7         | 0.41%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s         | 7         | 0.41%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s         | 7         | 0.41%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s         | 7         | 0.41%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s          | 7         | 0.41%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s          | 6         | 0.35%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 6         | 0.35%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s        | 6         | 0.35%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s        | 6         | 0.35%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s        | 6         | 0.35%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s         | 6         | 0.35%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s         | 6         | 0.35%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s          | 6         | 0.35%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s         | 6         | 0.35%   |
| Unknown                                                       | 6         | 0.35%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                          | 5         | 0.29%   |
| Unknown RAM Module 2GB DIMM 800MT/s                           | 5         | 0.29%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                          | 5         | 0.29%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s         | 5         | 0.29%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s        | 5         | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 657       | 46.73%  |
| DDR3    | 473       | 33.64%  |
| LPDDR3  | 66        | 4.69%   |
| Unknown | 63        | 4.48%   |
| DDR2    | 53        | 3.77%   |
| LPDDR4  | 42        | 2.99%   |
| SDRAM   | 18        | 1.28%   |
| DDR5    | 14        | 1%      |
| DDR     | 10        | 0.71%   |
| LPDDR5  | 8         | 0.57%   |
| DRAM    | 2         | 0.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 676       | 48.22%  |
| DIMM         | 600       | 42.8%   |
| Row Of Chips | 113       | 8.06%   |
| Chip         | 9         | 0.64%   |
| FB-DIMM      | 2         | 0.14%   |
| Unknown      | 2         | 0.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 584       | 39.19%  |
| 4096  | 390       | 26.17%  |
| 16384 | 241       | 16.17%  |
| 2048  | 177       | 11.88%  |
| 32768 | 54        | 3.62%   |
| 1024  | 33        | 2.21%   |
| 512   | 8         | 0.54%   |
| 65536 | 2         | 0.13%   |
| 256   | 1         | 0.07%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 317       | 20.76%  |
| 2667    | 211       | 13.82%  |
| 3200    | 171       | 11.2%   |
| 1333    | 122       | 7.99%   |
| 2133    | 97        | 6.35%   |
| 2400    | 92        | 6.02%   |
| 3600    | 57        | 3.73%   |
| 1334    | 45        | 2.95%   |
| 800     | 44        | 2.88%   |
| 1867    | 37        | 2.42%   |
| 667     | 33        | 2.16%   |
| 4267    | 23        | 1.51%   |
| 3400    | 23        | 1.51%   |
| 1067    | 21        | 1.38%   |
| 3000    | 18        | 1.18%   |
| Unknown | 18        | 1.18%   |
| 3466    | 17        | 1.11%   |
| 4800    | 16        | 1.05%   |
| 1866    | 14        | 0.92%   |
| 1066    | 14        | 0.92%   |
| 3266    | 11        | 0.72%   |
| 2933    | 10        | 0.65%   |
| 6400    | 8         | 0.52%   |
| 3733    | 8         | 0.52%   |
| 8400    | 7         | 0.46%   |
| 2800    | 7         | 0.46%   |
| 2666    | 7         | 0.46%   |
| 3866    | 6         | 0.39%   |
| 3800    | 5         | 0.33%   |
| 3100    | 5         | 0.33%   |
| 2048    | 5         | 0.33%   |
| 400     | 5         | 0.33%   |
| 4266    | 4         | 0.26%   |
| 3500    | 4         | 0.26%   |
| 533     | 4         | 0.26%   |
| 4199    | 3         | 0.2%    |
| 4133    | 3         | 0.2%    |
| 4000    | 3         | 0.2%    |
| 2733    | 3         | 0.2%    |
| 1800    | 3         | 0.2%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Brother Industries     | 32        | 27.59%  |
| Hewlett-Packard        | 27        | 23.28%  |
| Canon                  | 21        | 18.1%   |
| Fuji Xerox             | 7         | 6.03%   |
| Seiko Epson            | 6         | 5.17%   |
| Samsung Electronics    | 6         | 5.17%   |
| Prolific Technology    | 6         | 5.17%   |
| Lexmark International  | 2         | 1.72%   |
| Kyocera                | 2         | 1.72%   |
| Dymo-CoStar            | 2         | 1.72%   |
| Zebra                  | 1         | 0.86%   |
| Xerox                  | 1         | 0.86%   |
| Ricoh                  | 1         | 0.86%   |
| Custom Engineering SPA | 1         | 0.86%   |
| BIXOLON                | 1         | 0.86%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| HP DeskJet 2600 series                       | 8         | 6.78%   |
| Prolific PL2305 Parallel Port                | 6         | 5.08%   |
| Brother HL-2130 series                       | 5         | 4.24%   |
| HP DeskJet 2130 series                       | 4         | 3.39%   |
| Brother HL-1110 series                       | 4         | 3.39%   |
| HP ENVY 5000 series                          | 3         | 2.54%   |
| Fuji Xerox DocuPrint CM215 fw                | 3         | 2.54%   |
| Canon TS3100 series                          | 3         | 2.54%   |
| HP OfficeJet 5200 series                     | 2         | 1.69%   |
| HP DeskJet F2100 Printer series              | 2         | 1.69%   |
| HP DeskJet 3630 series                       | 2         | 1.69%   |
| Canon TR8500 series                          | 2         | 1.69%   |
| Canon PIXMA MX920 Series                     | 2         | 1.69%   |
| Canon PIXMA MG2500 Series                    | 2         | 1.69%   |
| Canon MG5600 series                          | 2         | 1.69%   |
| Brother MFC-L8690CDW series                  | 2         | 1.69%   |
| Brother MFC-1810                             | 2         | 1.69%   |
| Brother HL-L3230CDW series                   | 2         | 1.69%   |
| Brother HL-L2305 series                      | 2         | 1.69%   |
| Zebra ZTC LP2844-Z-200dpi                    | 1         | 0.85%   |
| Xerox Phaser 8400N                           | 1         | 0.85%   |
| Seiko Epson XP-4100 Series                   | 1         | 0.85%   |
| Seiko Epson XP-243 245 247 Series            | 1         | 0.85%   |
| Seiko Epson WF-5190 Series                   | 1         | 0.85%   |
| Seiko Epson Thermal Receipt Printer [TM-T20] | 1         | 0.85%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1         | 0.85%   |
| Seiko Epson ET-2820 Series                   | 1         | 0.85%   |
| Samsung ML-2010P Mono Laser Printer          | 1         | 0.85%   |
| Samsung ML-1865                              | 1         | 0.85%   |
| Samsung ML-1640 Series Laser Printer         | 1         | 0.85%   |
| Samsung ML-1450                              | 1         | 0.85%   |
| Samsung M267x 287x Series                    | 1         | 0.85%   |
| Samsung M2020 Series                         | 1         | 0.85%   |
| Ricoh Printer                                | 1         | 0.85%   |
| Lexmark International E260dn                 | 1         | 0.85%   |
| Lexmark International CX410de                | 1         | 0.85%   |
| Kyocera FS-1100                              | 1         | 0.85%   |
| Kyocera ECOSYS P5021cdn                      | 1         | 0.85%   |
| HP LaserJet Professional P 1102w             | 1         | 0.85%   |
| HP ENVY Photo 7100 series                    | 1         | 0.85%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Canon            | 10        | 58.82%  |
| Seiko Epson      | 4         | 23.53%  |
| Syscan           | 1         | 5.88%   |
| Salix Technology | 1         | 5.88%   |
| Mustek Systems   | 1         | 5.88%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Canon CanoScan LIDE 25                                  | 2         | 11.76%  |
| Canon CanoScan LiDE 210                                 | 2         | 11.76%  |
| Syscan TravelScan 460/464                               | 1         | 5.88%   |
| Seiko Epson Scanner                                     | 1         | 5.88%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]             | 1         | 5.88%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1         | 5.88%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]       | 1         | 5.88%   |
| Salix USB Scanner.                                      | 1         | 5.88%   |
| Mustek Systems BearPaw 2448 TA Plus                     | 1         | 5.88%   |
| Canon CanoScan N670U/N676U/LiDE 20                      | 1         | 5.88%   |
| Canon CanoScan N1240U/LiDE 30                           | 1         | 5.88%   |
| Canon CanoScan LiDE 220                                 | 1         | 5.88%   |
| Canon CanoScan LiDE 200                                 | 1         | 5.88%   |
| Canon CanoScan LiDE 110                                 | 1         | 5.88%   |
| Canon CanoScan 1220U                                    | 1         | 5.88%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 351       | 21.76%  |
| Logitech                               | 155       | 9.61%   |
| Microdia                               | 133       | 8.25%   |
| Realtek Semiconductor                  | 125       | 7.75%   |
| Apple                                  | 116       | 7.19%   |
| IMC Networks                           | 106       | 6.57%   |
| Sunplus Innovation Technology          | 104       | 6.45%   |
| Acer                                   | 81        | 5.02%   |
| Quanta                                 | 59        | 3.66%   |
| Cheng Uei Precision Industry (Foxlink) | 52        | 3.22%   |
| Suyin                                  | 51        | 3.16%   |
| Microsoft                              | 42        | 2.6%    |
| Lite-On Technology                     | 26        | 1.61%   |
| Syntek                                 | 22        | 1.36%   |
| Samsung Electronics                    | 22        | 1.36%   |
| Luxvisions Innotech Limited            | 15        | 0.93%   |
| Silicon Motion                         | 11        | 0.68%   |
| Importek                               | 10        | 0.62%   |
| Ricoh                                  | 9         | 0.56%   |
| Lenovo                                 | 9         | 0.56%   |
| Alcor Micro                            | 9         | 0.56%   |
| Razer USA                              | 7         | 0.43%   |
| Primax Electronics                     | 7         | 0.43%   |
| GEMBIRD                                | 7         | 0.43%   |
| Generalplus Technology                 | 6         | 0.37%   |
| OPPO Electronics                       | 5         | 0.31%   |
| LG Electronics                         | 5         | 0.31%   |
| Z-Star Microelectronics                | 4         | 0.25%   |
| OmniVision Technologies                | 4         | 0.25%   |
| Magic Control Technology               | 4         | 0.25%   |
| Genesys Logic                          | 4         | 0.25%   |
| DigiTech                               | 4         | 0.25%   |
| Cubeternet                             | 4         | 0.25%   |
| Bison Electronics                      | 4         | 0.25%   |
| Sonix Technology                       | 3         | 0.19%   |
| ALi                                    | 3         | 0.19%   |
| webcam                                 | 2         | 0.12%   |
| USB Camera                             | 2         | 0.12%   |
| SunplusIT                              | 2         | 0.12%   |
| Intel                                  | 2         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 65        | 3.95%   |
| Chicony Integrated Camera                               | 59        | 3.58%   |
| Realtek Integrated_Webcam_HD                            | 39        | 2.37%   |
| Apple FaceTime HD Camera (Built-in)                     | 39        | 2.37%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                         | 30        | 1.82%   |
| IMC Networks Integrated Camera                          | 29        | 1.76%   |
| Chicony HD Webcam                                       | 28        | 1.7%    |
| Apple Built-in iSight                                   | 27        | 1.64%   |
| Sunplus Integrated_Webcam_HD                            | 25        | 1.52%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 25        | 1.52%   |
| Chicony TOSHIBA Web Camera - HD                         | 25        | 1.52%   |
| Acer Integrated Camera                                  | 24        | 1.46%   |
| Samsung Galaxy A5 (MTP)                                 | 22        | 1.34%   |
| Logitech Webcam C270                                    | 21        | 1.28%   |
| Logitech HD Pro Webcam C920                             | 21        | 1.28%   |
| Chicony HP TrueVision HD Camera                         | 17        | 1.03%   |
| Syntek Integrated Camera                                | 15        | 0.91%   |
| Chicony USB 2.0 Camera                                  | 14        | 0.85%   |
| Chicony HP HD Camera                                    | 14        | 0.85%   |
| Sunplus HD WebCam                                       | 13        | 0.79%   |
| Quanta HD User Facing                                   | 13        | 0.79%   |
| Chicony HP Truevision HD                                | 13        | 0.79%   |
| Chicony HD User Facing                                  | 13        | 0.79%   |
| Apple FaceTime HD Camera                                | 13        | 0.79%   |
| Realtek USB Camera                                      | 12        | 0.73%   |
| Logitech C922 Pro Stream Webcam                         | 12        | 0.73%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 12        | 0.73%   |
| Acer EasyCamera                                         | 12        | 0.73%   |
| Microsoft LifeCam HD-3000                               | 11        | 0.67%   |
| Logitech Webcam C930e                                   | 11        | 0.67%   |
| Lite-On Integrated Camera                               | 11        | 0.67%   |
| Chicony USB2.0 Camera                                   | 11        | 0.67%   |
| Logitech Webcam C170                                    | 10        | 0.61%   |
| Chicony CNF9055 Toshiba Webcam                          | 10        | 0.61%   |
| Suyin HP Truevision HD                                  | 9         | 0.55%   |
| Quanta HP TrueVision HD Camera                          | 9         | 0.55%   |
| Microdia Integrated Webcam                              | 9         | 0.55%   |
| Logitech StreamCam                                      | 9         | 0.55%   |
| Logitech HD Webcam C615                                 | 9         | 0.55%   |
| Chicony EasyCamera                                      | 9         | 0.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 119       | 39.8%   |
| Synaptics                  | 76        | 25.42%  |
| Shenzhen Goodix Technology | 35        | 11.71%  |
| LighTuning Technology      | 20        | 6.69%   |
| AuthenTec                  | 15        | 5.02%   |
| Upek                       | 14        | 4.68%   |
| Elan Microelectronics      | 13        | 4.35%   |
| STMicroelectronics         | 6         | 2.01%   |
| Focal-systems.Corp         | 1         | 0.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 22        | 7.36%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 19        | 6.35%   |
| Shenzhen Goodix Fingerprint Reader                                         | 15        | 5.02%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 14        | 4.68%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 13        | 4.35%   |
| Validity Sensors Synaptics WBDI                                            | 11        | 3.68%   |
| Validity Sensors VFS491                                                    | 10        | 3.34%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 10        | 3.34%   |
| Synaptics  WBDI                                                            | 10        | 3.34%   |
| Shenzhen Goodix  Fingerprint Device                                        | 10        | 3.34%   |
| Shenzhen Goodix FingerPrint                                                | 10        | 3.34%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 9         | 3.01%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 9         | 3.01%   |
| Synaptics WBDI                                                             | 9         | 3.01%   |
| Validity Sensors Fingerprint scanner                                       | 8         | 2.68%   |
| Synaptics UWP WBDI                                                         | 8         | 2.68%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 2.68%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 7         | 2.34%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 7         | 2.34%   |
| Elan ELAN:Fingerprint                                                      | 7         | 2.34%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 2.01%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 2.01%   |
| Validity Sensors VFS Fingerprint sensor                                    | 6         | 2.01%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 2.01%   |
| Elan ELAN:ARM-M4                                                           | 6         | 2.01%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 1.67%   |
| Synaptics WBDI Device                                                      | 5         | 1.67%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 5         | 1.67%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 1.67%   |
| AuthenTec AES1600                                                          | 4         | 1.34%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 1%      |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 1%      |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 3         | 1%      |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 3         | 1%      |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 1%      |
| AuthenTec Fingerprint Sensor                                               | 3         | 1%      |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 2         | 0.67%   |
| AuthenTec AES2810                                                          | 2         | 0.67%   |
| Synaptics UWP WBDI Device                                                  | 1         | 0.33%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 33        | 60%     |
| Alcor Micro           | 12        | 21.82%  |
| Upek                  | 4         | 7.27%   |
| Lenovo                | 3         | 5.45%   |
| O2 Micro              | 2         | 3.64%   |
| Advanced Card Systems | 1         | 1.82%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 16        | 29.09%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 12        | 21.82%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 10.91%  |
| Broadcom 58200                                                               | 6         | 10.91%  |
| Broadcom 5880                                                                | 5         | 9.09%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 7.27%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 5.45%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 3.64%   |
| Advanced Card Systems ACR122U                                                | 1         | 1.82%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2120      | 69.9%   |
| 1     | 747       | 24.63%  |
| 2     | 128       | 4.22%   |
| 3     | 26        | 0.86%   |
| 4     | 10        | 0.33%   |
| 7     | 1         | 0.03%   |
| 5     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 298       | 28.06%  |
| Graphics card            | 250       | 23.54%  |
| Net/wireless             | 154       | 14.5%   |
| Multimedia controller    | 66        | 6.21%   |
| Chipcard                 | 50        | 4.71%   |
| Communication controller | 49        | 4.61%   |
| Camera                   | 36        | 3.39%   |
| Bluetooth                | 34        | 3.2%    |
| Unassigned class         | 29        | 2.73%   |
| Net/ethernet             | 20        | 1.88%   |
| Sound                    | 19        | 1.79%   |
| Storage                  | 12        | 1.13%   |
| Network                  | 9         | 0.85%   |
| Modem                    | 9         | 0.85%   |
| Dvb card                 | 8         | 0.75%   |
| Card reader              | 7         | 0.66%   |
| Storage/raid             | 3         | 0.28%   |
| Video                    | 2         | 0.19%   |
| Storage/ata              | 2         | 0.19%   |
| Unclassified device      | 1         | 0.09%   |
| Tv card                  | 1         | 0.09%   |
| Storage/nvme             | 1         | 0.09%   |
| Storage/ide              | 1         | 0.09%   |
| Firewire controller      | 1         | 0.09%   |

