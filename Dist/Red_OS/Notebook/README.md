Red OS - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Red OS.

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

Total: 287

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | B590 20206                  | [c118a5bc12](https://linux-hardware.org/?probe=c118a5bc12) | Dec 26, 2024 |
| Lenovo        | B590 20206                  | [04580fdd68](https://linux-hardware.org/?probe=04580fdd68) | Dec 26, 2024 |
| Lenovo        | IdeaPad L340-15API 81LW     | [d2b53b04f1](https://linux-hardware.org/?probe=d2b53b04f1) | Dec 24, 2024 |
| HUAWEI        | BoDE-WXX9                   | [e172af52db](https://linux-hardware.org/?probe=e172af52db) | Dec 18, 2024 |
| HUAWEI        | BOM-WXX9                    | [bdfe4e0a02](https://linux-hardware.org/?probe=bdfe4e0a02) | Dec 17, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [a1a92c896a](https://linux-hardware.org/?probe=a1a92c896a) | Dec 16, 2024 |
| Dell          | Precision M4700             | [291ffb667e](https://linux-hardware.org/?probe=291ffb667e) | Dec 11, 2024 |
| HP            | EliteBook 855 G8 Noteboo... | [bcfc822291](https://linux-hardware.org/?probe=bcfc822291) | Dec 10, 2024 |
| Infinix       | INBOOK X3 Plus              | [bcb0b23532](https://linux-hardware.org/?probe=bcb0b23532) | Dec 09, 2024 |
| HP            | 625                         | [a5d254f381](https://linux-hardware.org/?probe=a5d254f381) | Dec 06, 2024 |
| HP            | 250 G8 Notebook PC          | [f97ac5efbf](https://linux-hardware.org/?probe=f97ac5efbf) | Nov 27, 2024 |
| Dell          | Precision M4700             | [554f31582e](https://linux-hardware.org/?probe=554f31582e) | Nov 27, 2024 |
| MSI           | MS-1738                     | [c78d18847a](https://linux-hardware.org/?probe=c78d18847a) | Nov 26, 2024 |
| HP            | ProBook 450 G2              | [46bffb65f4](https://linux-hardware.org/?probe=46bffb65f4) | Nov 26, 2024 |
| HP            | ProBook 450 G2              | [0e1b332ae9](https://linux-hardware.org/?probe=0e1b332ae9) | Nov 25, 2024 |
| HP            | ProBook 450 G2              | [db7205adc1](https://linux-hardware.org/?probe=db7205adc1) | Nov 22, 2024 |
| Unknown       | Unknown                     | [276273e5a4](https://linux-hardware.org/?probe=276273e5a4) | Nov 16, 2024 |
| Graviton      | 23-156P                     | [3b593a068c](https://linux-hardware.org/?probe=3b593a068c) | Nov 05, 2024 |
| Dell          | Inspiron 5770               | [ed13db6ca0](https://linux-hardware.org/?probe=ed13db6ca0) | Nov 05, 2024 |
| Graviton      | 23-156P                     | [2c150d69e6](https://linux-hardware.org/?probe=2c150d69e6) | Nov 05, 2024 |
| Dell          | Precision M4700             | [62d0c61c5b](https://linux-hardware.org/?probe=62d0c61c5b) | Oct 29, 2024 |
| TECNO Mobi... | MEGABOOK T15AA              | [9a28f9ea8b](https://linux-hardware.org/?probe=9a28f9ea8b) | Oct 22, 2024 |
| HUAWEI        | BOM-WXX9                    | [0a8ba0ea9c](https://linux-hardware.org/?probe=0a8ba0ea9c) | Oct 21, 2024 |
| Dell          | Precision M4700             | [4ba30ec7dc](https://linux-hardware.org/?probe=4ba30ec7dc) | Oct 17, 2024 |
| Lenovo        | IdeaPad Slim 5 16IMH9 83... | [c13d606d8d](https://linux-hardware.org/?probe=c13d606d8d) | Oct 14, 2024 |
| Lenovo        | IdeaPad Slim 5 16IMH9 83... | [7c056fd094](https://linux-hardware.org/?probe=7c056fd094) | Oct 14, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [5d06bad1c1](https://linux-hardware.org/?probe=5d06bad1c1) | Oct 11, 2024 |
| Irbis         | NB656                       | [f54d72ba00](https://linux-hardware.org/?probe=f54d72ba00) | Oct 10, 2024 |
| Getac         | S410G5                      | [98b2b79421](https://linux-hardware.org/?probe=98b2b79421) | Oct 10, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [1062107e62](https://linux-hardware.org/?probe=1062107e62) | Sep 28, 2024 |
| Chuwi         | GemiBook Plus               | [de869d366c](https://linux-hardware.org/?probe=de869d366c) | Sep 27, 2024 |
| Dell          | Precision M4700             | [ce3cda2d73](https://linux-hardware.org/?probe=ce3cda2d73) | Sep 20, 2024 |
| HUAWEI        | BOD-WXX9                    | [3bc442585a](https://linux-hardware.org/?probe=3bc442585a) | Sep 20, 2024 |
| HUAWEI        | BOD-WXX9                    | [d62388c6c7](https://linux-hardware.org/?probe=d62388c6c7) | Sep 20, 2024 |
| Dell          | Precision M4700             | [16e80ad11f](https://linux-hardware.org/?probe=16e80ad11f) | Sep 19, 2024 |
| HP            | EliteBook 840 G8 Noteboo... | [261aa65f79](https://linux-hardware.org/?probe=261aa65f79) | Sep 09, 2024 |
| HP            | Laptop 17-by2xxx            | [16058e97f2](https://linux-hardware.org/?probe=16058e97f2) | Sep 08, 2024 |
| HP            | ProBook 450 G2              | [d80c8abc21](https://linux-hardware.org/?probe=d80c8abc21) | Sep 04, 2024 |
| TECNO Mobi... | MEGABOOK T15AA              | [8f22df45e0](https://linux-hardware.org/?probe=8f22df45e0) | Sep 03, 2024 |
| Dell          | Precision M4700             | [9ac18fa798](https://linux-hardware.org/?probe=9ac18fa798) | Sep 03, 2024 |
| Dell          | Precision M4700             | [67120ae7b7](https://linux-hardware.org/?probe=67120ae7b7) | Sep 01, 2024 |
| HP            | ProBook 450 G2              | [1614032def](https://linux-hardware.org/?probe=1614032def) | Aug 30, 2024 |
| DEPO Compu... | DPH610S                     | [cae887ea79](https://linux-hardware.org/?probe=cae887ea79) | Aug 20, 2024 |
| Dell          | Precision M4700             | [e90b829dae](https://linux-hardware.org/?probe=e90b829dae) | Aug 02, 2024 |
| Acer          | Aspire 5742G                | [45def493cd](https://linux-hardware.org/?probe=45def493cd) | Jul 29, 2024 |
| ASUSTek       | N61Jv                       | [641730f2ac](https://linux-hardware.org/?probe=641730f2ac) | Jul 26, 2024 |
| HP            | ProBook 4720s               | [74fd9eee71](https://linux-hardware.org/?probe=74fd9eee71) | Jul 11, 2024 |
| Dell          | Precision M4700             | [d50c6cdb48](https://linux-hardware.org/?probe=d50c6cdb48) | Jul 08, 2024 |
| Dell          | Precision M4700             | [e65decbc74](https://linux-hardware.org/?probe=e65decbc74) | Jun 26, 2024 |
| Lenovo        | IdeaPad Z580                | [3c9898faa1](https://linux-hardware.org/?probe=3c9898faa1) | Jun 20, 2024 |
| Lenovo        | IdeaPad Z580                | [50ac519b75](https://linux-hardware.org/?probe=50ac519b75) | Jun 20, 2024 |
| Dell          | Precision M4700             | [ded8148269](https://linux-hardware.org/?probe=ded8148269) | Jun 20, 2024 |
| Acer          | Aspire A315-42G             | [f63af66df7](https://linux-hardware.org/?probe=f63af66df7) | Jun 17, 2024 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [21c00a1a7e](https://linux-hardware.org/?probe=21c00a1a7e) | Jun 09, 2024 |
| Lenovo        | G570 20079                  | [a55b57b2d9](https://linux-hardware.org/?probe=a55b57b2d9) | Jun 07, 2024 |
| Toshiba       | Satellite C650              | [b3c1dc0ded](https://linux-hardware.org/?probe=b3c1dc0ded) | May 22, 2024 |
| DEPO Compu... | DPH610S                     | [5c1b9da621](https://linux-hardware.org/?probe=5c1b9da621) | May 16, 2024 |
| Apple         | MacBookPro5,3               | [b8e92a4880](https://linux-hardware.org/?probe=b8e92a4880) | May 12, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [0d046abb98](https://linux-hardware.org/?probe=0d046abb98) | May 11, 2024 |
| Unknown       | Unknown                     | [3c4e207a92](https://linux-hardware.org/?probe=3c4e207a92) | May 09, 2024 |
| Dell          | Precision M4700             | [fa5aa96761](https://linux-hardware.org/?probe=fa5aa96761) | Apr 23, 2024 |
| MACHENIKE     | MACHCREATOR-16              | [03f369c46b](https://linux-hardware.org/?probe=03f369c46b) | Apr 15, 2024 |
| MACHENIKE     | L17A                        | [5bd336609a](https://linux-hardware.org/?probe=5bd336609a) | Apr 10, 2024 |
| Dell          | Precision M4700             | [14e5ad11ff](https://linux-hardware.org/?probe=14e5ad11ff) | Apr 08, 2024 |
| Unknown       | X133                        | [c85c7ccafc](https://linux-hardware.org/?probe=c85c7ccafc) | Apr 05, 2024 |
| Dell          | Precision M4700             | [667558cba6](https://linux-hardware.org/?probe=667558cba6) | Mar 20, 2024 |
| Fujitsu Si... | LIFEBOOK T5010              | [99e6ef98f0](https://linux-hardware.org/?probe=99e6ef98f0) | Mar 14, 2024 |
| Acer          | Extensa 215-33              | [efe3c07386](https://linux-hardware.org/?probe=efe3c07386) | Mar 04, 2024 |
| Acer          | Extensa 215-33              | [0b2c9b5116](https://linux-hardware.org/?probe=0b2c9b5116) | Mar 04, 2024 |
| HP            | EliteBook 2540p             | [f0aab0e0f6](https://linux-hardware.org/?probe=f0aab0e0f6) | Mar 02, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [de96f427a2](https://linux-hardware.org/?probe=de96f427a2) | Mar 02, 2024 |
| Dell          | Precision M4700             | [8e50df0d77](https://linux-hardware.org/?probe=8e50df0d77) | Mar 01, 2024 |
| Dell          | Inspiron 3537               | [e05c7c262b](https://linux-hardware.org/?probe=e05c7c262b) | Mar 01, 2024 |
| ASUSTek       | ROG Zephyrus S17 GX701LX... | [15a8eddc01](https://linux-hardware.org/?probe=15a8eddc01) | Feb 29, 2024 |
| Dell          | Inspiron 3537               | [e76d792669](https://linux-hardware.org/?probe=e76d792669) | Feb 29, 2024 |
| Lenovo        | IdeaPad 1 15IAU7 82QD       | [b6a4906cf3](https://linux-hardware.org/?probe=b6a4906cf3) | Feb 20, 2024 |
| Acer          | Aspire A315-24P             | [96c7b5b101](https://linux-hardware.org/?probe=96c7b5b101) | Feb 15, 2024 |
| Lenovo        | IdeaPad L340-15API 81LW     | [5299dd1826](https://linux-hardware.org/?probe=5299dd1826) | Feb 13, 2024 |
| Dell          | Precision M4700             | [02cfb33222](https://linux-hardware.org/?probe=02cfb33222) | Feb 13, 2024 |
| Infinix       | INBOOK X2 GEN11             | [f1d916474f](https://linux-hardware.org/?probe=f1d916474f) | Feb 12, 2024 |
| Infinix       | INBOOK X2 GEN11             | [43a65f4060](https://linux-hardware.org/?probe=43a65f4060) | Feb 12, 2024 |
| Lenovo        | IdeaPad L340-15API 81LW     | [db2cd07d84](https://linux-hardware.org/?probe=db2cd07d84) | Jan 26, 2024 |
| Lenovo        | IdeaPad L340-15API 81LW     | [ca9e77a64e](https://linux-hardware.org/?probe=ca9e77a64e) | Jan 19, 2024 |
| Acer          | Aspire A315-24P             | [abc7a5352b](https://linux-hardware.org/?probe=abc7a5352b) | Jan 14, 2024 |
| Acer          | Aspire A315-24P             | [166d3493a4](https://linux-hardware.org/?probe=166d3493a4) | Jan 14, 2024 |
| Lenovo        | IdeaPad L340-15API 81LW     | [04855eeea8](https://linux-hardware.org/?probe=04855eeea8) | Jan 09, 2024 |
| Acer          | Extensa 215-22              | [c2884d7a5d](https://linux-hardware.org/?probe=c2884d7a5d) | Jan 09, 2024 |
| Lenovo        | ThinkPad T61 6464WM6        | [a0b959c7c4](https://linux-hardware.org/?probe=a0b959c7c4) | Jan 05, 2024 |
| Lenovo        | ThinkPad T61 6464WM6        | [3cf7d0764e](https://linux-hardware.org/?probe=3cf7d0764e) | Jan 05, 2024 |
| Lenovo        | ThinkPad T430 23493V2       | [8cbff5c75a](https://linux-hardware.org/?probe=8cbff5c75a) | Jan 02, 2024 |
| KVADRA        | NAU LE15T                   | [b53fe7cc28](https://linux-hardware.org/?probe=b53fe7cc28) | Jan 02, 2024 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [c71368b0eb](https://linux-hardware.org/?probe=c71368b0eb) | Jan 01, 2024 |
| iRU           | 15ALC                       | [28f7177799](https://linux-hardware.org/?probe=28f7177799) | Dec 22, 2023 |
| Dell          | Precision M4700             | [3048d06ee6](https://linux-hardware.org/?probe=3048d06ee6) | Dec 21, 2023 |
| Lenovo        | V15 G1 IML 82NB             | [90d82dc1a1](https://linux-hardware.org/?probe=90d82dc1a1) | Dec 18, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [c4aead03a2](https://linux-hardware.org/?probe=c4aead03a2) | Dec 13, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [02763925e5](https://linux-hardware.org/?probe=02763925e5) | Dec 08, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [3b62534051](https://linux-hardware.org/?probe=3b62534051) | Nov 29, 2023 |
| Lenovo        | ThinkPad X230 23245C8       | [bf518076d5](https://linux-hardware.org/?probe=bf518076d5) | Nov 29, 2023 |
| Dell          | Vostro 3590                 | [8ca5eb4e42](https://linux-hardware.org/?probe=8ca5eb4e42) | Nov 27, 2023 |
| Lenovo        | ThinkPad T460s 20FAS1TQ0... | [5586688561](https://linux-hardware.org/?probe=5586688561) | Nov 21, 2023 |
| HP            | EliteBook 850 G1            | [7d7599e0d0](https://linux-hardware.org/?probe=7d7599e0d0) | Nov 21, 2023 |
| HUAWEI        | NDZ-WXX9                    | [95caa4b8a1](https://linux-hardware.org/?probe=95caa4b8a1) | Nov 21, 2023 |
| HUAWEI        | NDZ-WXX9                    | [0324427380](https://linux-hardware.org/?probe=0324427380) | Nov 21, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [9dbd54affc](https://linux-hardware.org/?probe=9dbd54affc) | Nov 14, 2023 |
| ASUSTek       | K53SC                       | [e86d8effd9](https://linux-hardware.org/?probe=e86d8effd9) | Nov 11, 2023 |
| Dell          | Precision M4700             | [ab52e67d9d](https://linux-hardware.org/?probe=ab52e67d9d) | Nov 01, 2023 |
| HP            | Pavilion dv6                | [d8a8dfefd7](https://linux-hardware.org/?probe=d8a8dfefd7) | Oct 24, 2023 |
| Dell          | Precision M4700             | [4d590a378f](https://linux-hardware.org/?probe=4d590a378f) | Oct 24, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [41dfd82cb6](https://linux-hardware.org/?probe=41dfd82cb6) | Oct 23, 2023 |
| HP            | Pavilion dv6                | [71c2062cbf](https://linux-hardware.org/?probe=71c2062cbf) | Oct 22, 2023 |
| Graviton      | Unknown                     | [69c721a100](https://linux-hardware.org/?probe=69c721a100) | Oct 10, 2023 |
| HP            | Laptop 15-bw0xx             | [4440996d7b](https://linux-hardware.org/?probe=4440996d7b) | Oct 07, 2023 |
| HP            | Laptop 15-bw0xx             | [7774477854](https://linux-hardware.org/?probe=7774477854) | Oct 07, 2023 |
| HUAWEI        | BDZ-WXX9                    | [a33a848e40](https://linux-hardware.org/?probe=a33a848e40) | Sep 26, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [b85adec006](https://linux-hardware.org/?probe=b85adec006) | Sep 25, 2023 |
| iRU           | 15ALC                       | [c5839fb7da](https://linux-hardware.org/?probe=c5839fb7da) | Sep 17, 2023 |
| iRU           | 15ALC                       | [87679b8dc1](https://linux-hardware.org/?probe=87679b8dc1) | Sep 17, 2023 |
| HP            | ProBook 6570b               | [baf81a81a2](https://linux-hardware.org/?probe=baf81a81a2) | Sep 13, 2023 |
| HP            | ProBook 6570b               | [90aaacf4af](https://linux-hardware.org/?probe=90aaacf4af) | Sep 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [006062545f](https://linux-hardware.org/?probe=006062545f) | Sep 13, 2023 |
| HP            | Laptop 15s-fq2xxx           | [2135954523](https://linux-hardware.org/?probe=2135954523) | Sep 04, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [7c560dfe57](https://linux-hardware.org/?probe=7c560dfe57) | Aug 31, 2023 |
| ICL           | S1511 G1R                   | [421df1df8d](https://linux-hardware.org/?probe=421df1df8d) | Aug 28, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [a3a1e805b2](https://linux-hardware.org/?probe=a3a1e805b2) | Aug 27, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [cfe21994b6](https://linux-hardware.org/?probe=cfe21994b6) | Aug 17, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [7d63566e0a](https://linux-hardware.org/?probe=7d63566e0a) | Aug 11, 2023 |
| Dell          | Precision M4700             | [95ac580b0d](https://linux-hardware.org/?probe=95ac580b0d) | Aug 08, 2023 |
| MSI           | Modern 14 C12M              | [aa352b05aa](https://linux-hardware.org/?probe=aa352b05aa) | Aug 03, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [8a2a5c6265](https://linux-hardware.org/?probe=8a2a5c6265) | Jul 30, 2023 |
| Dell          | Vostro 3400                 | [ee71316b5e](https://linux-hardware.org/?probe=ee71316b5e) | Jul 17, 2023 |
| Gigabyte      | G5 ME                       | [eaefa9c2c6](https://linux-hardware.org/?probe=eaefa9c2c6) | Jul 17, 2023 |
| Dell          | Precision M4700             | [7dc84c10b5](https://linux-hardware.org/?probe=7dc84c10b5) | Jul 11, 2023 |
| Dell          | Inspiron 3583               | [3f5ae451c0](https://linux-hardware.org/?probe=3f5ae451c0) | Jul 09, 2023 |
| Timi          | Redmi G 2022                | [30e96afcdd](https://linux-hardware.org/?probe=30e96afcdd) | Jul 08, 2023 |
| Timi          | Redmi G 2022                | [cd2b7e13ce](https://linux-hardware.org/?probe=cd2b7e13ce) | Jul 04, 2023 |
| ICL           | Si1407                      | [c4c9d43042](https://linux-hardware.org/?probe=c4c9d43042) | Jul 04, 2023 |
| Aquarius      | NS483                       | [dd5daf7f12](https://linux-hardware.org/?probe=dd5daf7f12) | Jun 18, 2023 |
| HP            | Laptop 15-bw0xx             | [a161ef52b4](https://linux-hardware.org/?probe=a161ef52b4) | Jun 18, 2023 |
| Lenovo        | G570 20079                  | [4843789a62](https://linux-hardware.org/?probe=4843789a62) | May 30, 2023 |
| Acer          | Aspire A315-58              | [59d36ef46d](https://linux-hardware.org/?probe=59d36ef46d) | May 22, 2023 |
| HP            | EliteBook 8440p             | [3ad250d762](https://linux-hardware.org/?probe=3ad250d762) | May 22, 2023 |
| MSI           | GL62 6QF                    | [6ae5c650f3](https://linux-hardware.org/?probe=6ae5c650f3) | May 14, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [3de097b441](https://linux-hardware.org/?probe=3de097b441) | May 12, 2023 |
| Dell          | Vostro 5391                 | [f5342b41ec](https://linux-hardware.org/?probe=f5342b41ec) | May 06, 2023 |
| Graviton      | N14I-T                      | [e82c8f00d8](https://linux-hardware.org/?probe=e82c8f00d8) | May 05, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [a61a9a88bc](https://linux-hardware.org/?probe=a61a9a88bc) | May 02, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [8f8a912636](https://linux-hardware.org/?probe=8f8a912636) | May 01, 2023 |
| HP            | Laptop 15-bw0xx             | [387eecc18e](https://linux-hardware.org/?probe=387eecc18e) | Apr 27, 2023 |
| HP            | ProBook 440 G8 Notebook ... | [40aaf19667](https://linux-hardware.org/?probe=40aaf19667) | Apr 21, 2023 |
| Unknown       | Unknown                     | [c959a62e36](https://linux-hardware.org/?probe=c959a62e36) | Apr 10, 2023 |
| HONOR         | BMH-WCX9                    | [2082d3c772](https://linux-hardware.org/?probe=2082d3c772) | Apr 08, 2023 |
| Unknown       | Unknown                     | [70ff15284b](https://linux-hardware.org/?probe=70ff15284b) | Apr 07, 2023 |
| Unknown       | Unknown                     | [9a068872f6](https://linux-hardware.org/?probe=9a068872f6) | Apr 06, 2023 |
| HP            | ProBook 4525s               | [164d8993b4](https://linux-hardware.org/?probe=164d8993b4) | Apr 04, 2023 |
| MSI           | Sword 15 A12UE              | [3389b32105](https://linux-hardware.org/?probe=3389b32105) | Apr 01, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [36b3103f3f](https://linux-hardware.org/?probe=36b3103f3f) | Mar 31, 2023 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [deb6990c19](https://linux-hardware.org/?probe=deb6990c19) | Mar 27, 2023 |
| HONOR         | NBR-WAX9                    | [ef91ef3645](https://linux-hardware.org/?probe=ef91ef3645) | Mar 27, 2023 |
| MSI           | Modern 15 B12M              | [eded7b36b1](https://linux-hardware.org/?probe=eded7b36b1) | Mar 27, 2023 |
| MSI           | Modern 15 B12M              | [9ee3ca41c8](https://linux-hardware.org/?probe=9ee3ca41c8) | Mar 27, 2023 |
| MSI           | Sword 15 A12UE              | [f4341a491a](https://linux-hardware.org/?probe=f4341a491a) | Mar 21, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [be9b767d92](https://linux-hardware.org/?probe=be9b767d92) | Mar 20, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [b473b68faf](https://linux-hardware.org/?probe=b473b68faf) | Mar 10, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [4a8589fbdf](https://linux-hardware.org/?probe=4a8589fbdf) | Mar 10, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [b116afe451](https://linux-hardware.org/?probe=b116afe451) | Feb 27, 2023 |
| Kraftway      | ACCORD                      | [8fe15f2f2b](https://linux-hardware.org/?probe=8fe15f2f2b) | Feb 22, 2023 |
| Lenovo        | B590 20208                  | [10e9491ee4](https://linux-hardware.org/?probe=10e9491ee4) | Feb 17, 2023 |
| Lenovo        | B590 20208                  | [a3b352975c](https://linux-hardware.org/?probe=a3b352975c) | Feb 17, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [4d9144193f](https://linux-hardware.org/?probe=4d9144193f) | Feb 17, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [9de0373acc](https://linux-hardware.org/?probe=9de0373acc) | Feb 16, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [09073fcfc8](https://linux-hardware.org/?probe=09073fcfc8) | Feb 10, 2023 |
| HP            | G62                         | [8bc9454fb1](https://linux-hardware.org/?probe=8bc9454fb1) | Feb 10, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [d3b63de821](https://linux-hardware.org/?probe=d3b63de821) | Feb 07, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [a2172caf56](https://linux-hardware.org/?probe=a2172caf56) | Feb 06, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [77faeb6b52](https://linux-hardware.org/?probe=77faeb6b52) | Feb 06, 2023 |
| HP            | Pavilion 15                 | [eb37d7677c](https://linux-hardware.org/?probe=eb37d7677c) | Feb 06, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [bb0481d7a8](https://linux-hardware.org/?probe=bb0481d7a8) | Feb 06, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [186aef8e0c](https://linux-hardware.org/?probe=186aef8e0c) | Jan 24, 2023 |
| Lenovo        | V130-15IKB 81HN             | [a74a5b3b7b](https://linux-hardware.org/?probe=a74a5b3b7b) | Jan 20, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [8472d89767](https://linux-hardware.org/?probe=8472d89767) | Jan 20, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [7d95709d81](https://linux-hardware.org/?probe=7d95709d81) | Jan 19, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [b6e4100bc6](https://linux-hardware.org/?probe=b6e4100bc6) | Jan 17, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [a05251fd39](https://linux-hardware.org/?probe=a05251fd39) | Dec 29, 2022 |
| 3Logic Gro... | Graviton N15i-K2            | [fe79eba13b](https://linux-hardware.org/?probe=fe79eba13b) | Dec 29, 2022 |
| HP            | Notebook                    | [10dfda9549](https://linux-hardware.org/?probe=10dfda9549) | Dec 24, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [4c1ad2ea2e](https://linux-hardware.org/?probe=4c1ad2ea2e) | Dec 18, 2022 |
| Kraftway      | ACCORD                      | [a199d930ff](https://linux-hardware.org/?probe=a199d930ff) | Dec 18, 2022 |
| Shanghai Z... | ZXE CRB                     | [20ce0a7f23](https://linux-hardware.org/?probe=20ce0a7f23) | Dec 16, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [6cedae9702](https://linux-hardware.org/?probe=6cedae9702) | Dec 10, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [311f47baef](https://linux-hardware.org/?probe=311f47baef) | Dec 09, 2022 |
| HP            | Laptop 15s-eq1xxx           | [79a0f9e73a](https://linux-hardware.org/?probe=79a0f9e73a) | Dec 08, 2022 |
| HP            | Laptop 15s-eq1xxx           | [c1cd524970](https://linux-hardware.org/?probe=c1cd524970) | Dec 08, 2022 |
| Aquarius      | NS685U R11                  | [c0dff8c525](https://linux-hardware.org/?probe=c0dff8c525) | Dec 08, 2022 |
| ICL           | RAYbook Si1512              | [b8c52ae5cb](https://linux-hardware.org/?probe=b8c52ae5cb) | Dec 06, 2022 |
| HP            | Laptop 15s-eq1xxx           | [0cd3371014](https://linux-hardware.org/?probe=0cd3371014) | Dec 05, 2022 |
| MSI           | Sword 15 A12UE              | [32df733b5e](https://linux-hardware.org/?probe=32df733b5e) | Dec 04, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [ddb1791ff6](https://linux-hardware.org/?probe=ddb1791ff6) | Nov 28, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [d9ae3d1795](https://linux-hardware.org/?probe=d9ae3d1795) | Nov 27, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [ff3d0a1ecf](https://linux-hardware.org/?probe=ff3d0a1ecf) | Nov 24, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [f86569d54b](https://linux-hardware.org/?probe=f86569d54b) | Nov 24, 2022 |
| HUAWEI        | NBD-WXX9                    | [a54f42b51e](https://linux-hardware.org/?probe=a54f42b51e) | Nov 18, 2022 |
| HUAWEI        | NBD-WXX9                    | [faa0deab8f](https://linux-hardware.org/?probe=faa0deab8f) | Nov 18, 2022 |
| Lenovo        | ThinkPad X220 4290RB3       | [37959973aa](https://linux-hardware.org/?probe=37959973aa) | Nov 11, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [3fd33e6782](https://linux-hardware.org/?probe=3fd33e6782) | Nov 09, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [dba14315ca](https://linux-hardware.org/?probe=dba14315ca) | Nov 03, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [d653658a53](https://linux-hardware.org/?probe=d653658a53) | Oct 28, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [b9ab6b9cf2](https://linux-hardware.org/?probe=b9ab6b9cf2) | Oct 28, 2022 |
| Acer          | Aspire A517-52              | [1ee47a3ab6](https://linux-hardware.org/?probe=1ee47a3ab6) | Oct 25, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [14537f243b](https://linux-hardware.org/?probe=14537f243b) | Oct 24, 2022 |
| THUNDEROBO... | 911AirD                     | [f471a1c9db](https://linux-hardware.org/?probe=f471a1c9db) | Oct 23, 2022 |
| Acer          | Aspire A517-52              | [7515d53b5d](https://linux-hardware.org/?probe=7515d53b5d) | Oct 21, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [3fc175d4a0](https://linux-hardware.org/?probe=3fc175d4a0) | Oct 20, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [fe184c8f5b](https://linux-hardware.org/?probe=fe184c8f5b) | Oct 19, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [0db79bc085](https://linux-hardware.org/?probe=0db79bc085) | Oct 19, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [1cdde90662](https://linux-hardware.org/?probe=1cdde90662) | Oct 13, 2022 |
| Acer          | Aspire 2920                 | [c588bacc95](https://linux-hardware.org/?probe=c588bacc95) | Oct 08, 2022 |
| Acer          | Aspire 2920                 | [34b41a4e67](https://linux-hardware.org/?probe=34b41a4e67) | Oct 08, 2022 |
| ASUSTek       | X540NV                      | [31e4464fea](https://linux-hardware.org/?probe=31e4464fea) | Oct 07, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [7f8e650618](https://linux-hardware.org/?probe=7f8e650618) | Oct 06, 2022 |
| Acer          | Aspire 2920                 | [538f7a6e26](https://linux-hardware.org/?probe=538f7a6e26) | Oct 05, 2022 |
| HP            | OMEN by Laptop              | [0a8238a876](https://linux-hardware.org/?probe=0a8238a876) | Oct 05, 2022 |
| THUNDEROBO... | 911AirD                     | [69a9650652](https://linux-hardware.org/?probe=69a9650652) | Oct 03, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [89b48cd98e](https://linux-hardware.org/?probe=89b48cd98e) | Oct 03, 2022 |
| Digma         | EVE 11 C408                 | [b5c7ac8ed3](https://linux-hardware.org/?probe=b5c7ac8ed3) | Sep 30, 2022 |
| THUNDEROBO... | 911AirD                     | [99f1b7e253](https://linux-hardware.org/?probe=99f1b7e253) | Sep 29, 2022 |
| ICL           | RAYbook Si1512              | [0b610b66a9](https://linux-hardware.org/?probe=0b610b66a9) | Sep 20, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [713797403a](https://linux-hardware.org/?probe=713797403a) | Sep 09, 2022 |
| IP3 Techno... | ACN30                       | [af9694cea8](https://linux-hardware.org/?probe=af9694cea8) | Sep 06, 2022 |
| IP3 Techno... | ACN30                       | [03f14a115d](https://linux-hardware.org/?probe=03f14a115d) | Sep 05, 2022 |
| MSI           | FX610                       | [a822818a58](https://linux-hardware.org/?probe=a822818a58) | Sep 03, 2022 |
| IP3 Techno... | ACN30                       | [e25ed534c0](https://linux-hardware.org/?probe=e25ed534c0) | Aug 18, 2022 |
| ICL           | RAYbook Si1512              | [a42c4dc65a](https://linux-hardware.org/?probe=a42c4dc65a) | Aug 09, 2022 |
| Digma         | EVE 15 P417 ES5063EW        | [a584c678b5](https://linux-hardware.org/?probe=a584c678b5) | Jul 27, 2022 |
| Digma         | EVE 15 C407 ES5054EW        | [4fd01756b2](https://linux-hardware.org/?probe=4fd01756b2) | Jul 27, 2022 |
| Digma         | EVE 15 C407 ES5054EW        | [008b02cc92](https://linux-hardware.org/?probe=008b02cc92) | Jul 26, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [413949a727](https://linux-hardware.org/?probe=413949a727) | Jul 25, 2022 |
| Lenovo        | V15-IWL 81YE                | [3bfcedd5c8](https://linux-hardware.org/?probe=3bfcedd5c8) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | [c49282206c](https://linux-hardware.org/?probe=c49282206c) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | [d598c4587d](https://linux-hardware.org/?probe=d598c4587d) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | [5b1e962751](https://linux-hardware.org/?probe=5b1e962751) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | [4e120b3b63](https://linux-hardware.org/?probe=4e120b3b63) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | [2d5bedf224](https://linux-hardware.org/?probe=2d5bedf224) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | [297ce5144e](https://linux-hardware.org/?probe=297ce5144e) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | [84b7cd1115](https://linux-hardware.org/?probe=84b7cd1115) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | [a92b6c5d73](https://linux-hardware.org/?probe=a92b6c5d73) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | [51ebd271c8](https://linux-hardware.org/?probe=51ebd271c8) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | [44ad7f7d47](https://linux-hardware.org/?probe=44ad7f7d47) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | [49068a26b5](https://linux-hardware.org/?probe=49068a26b5) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | [62ce596bf3](https://linux-hardware.org/?probe=62ce596bf3) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | [812db8ad6f](https://linux-hardware.org/?probe=812db8ad6f) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | [d4c2b5ffad](https://linux-hardware.org/?probe=d4c2b5ffad) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | [4c0179b60e](https://linux-hardware.org/?probe=4c0179b60e) | Jul 22, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [8601888983](https://linux-hardware.org/?probe=8601888983) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | [1d505390d6](https://linux-hardware.org/?probe=1d505390d6) | Jul 22, 2022 |
| HONOR         | NBR-WAX9                    | [5b3340311a](https://linux-hardware.org/?probe=5b3340311a) | Jul 20, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [154c254eac](https://linux-hardware.org/?probe=154c254eac) | Jul 19, 2022 |
| Gigabyte      | G5 GD                       | [60921a7ff6](https://linux-hardware.org/?probe=60921a7ff6) | Jul 19, 2022 |
| Gigabyte      | G5 GD                       | [c24f8b4ba6](https://linux-hardware.org/?probe=c24f8b4ba6) | Jul 19, 2022 |
| HONOR         | NBR-WAX9                    | [fe971bb8c3](https://linux-hardware.org/?probe=fe971bb8c3) | Jul 08, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [2835672840](https://linux-hardware.org/?probe=2835672840) | Jul 07, 2022 |
| Kraftway      | ACCORD                      | [24e49bc011](https://linux-hardware.org/?probe=24e49bc011) | Jun 27, 2022 |
| Kraftway      | ACCORD                      | [39e3c55e89](https://linux-hardware.org/?probe=39e3c55e89) | Jun 27, 2022 |
| Aquarius      | NS685U                      | [ecedc7cbb6](https://linux-hardware.org/?probe=ecedc7cbb6) | Jun 08, 2022 |
| ICL           | Unknown                     | [4dc89fc689](https://linux-hardware.org/?probe=4dc89fc689) | Jun 07, 2022 |
| mtech         | MTL1578                     | [bf25c26ea0](https://linux-hardware.org/?probe=bf25c26ea0) | May 11, 2022 |
| HUAWEI        | BOD-WXX9                    | [e2e025dd4f](https://linux-hardware.org/?probe=e2e025dd4f) | Apr 15, 2022 |
| Acer          | TravelMate P215-53          | [124fdb3b64](https://linux-hardware.org/?probe=124fdb3b64) | Apr 14, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [be41efbec8](https://linux-hardware.org/?probe=be41efbec8) | Apr 05, 2022 |
| Aquarius      | NS585 R32                   | [582389ca98](https://linux-hardware.org/?probe=582389ca98) | Mar 24, 2022 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | [56f9ebba91](https://linux-hardware.org/?probe=56f9ebba91) | Mar 22, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [e18b80073c](https://linux-hardware.org/?probe=e18b80073c) | Mar 21, 2022 |
| 3Logic Gro... | APM Graviton A15i-K2        | [e93bcf2f42](https://linux-hardware.org/?probe=e93bcf2f42) | Mar 09, 2022 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [227a2658d0](https://linux-hardware.org/?probe=227a2658d0) | Feb 15, 2022 |
| HP            | Laptop 15s-eq1xxx           | [7ed7e139d8](https://linux-hardware.org/?probe=7ed7e139d8) | Dec 20, 2021 |
| HP            | Laptop 15s-eq1xxx           | [55ab1c9ab8](https://linux-hardware.org/?probe=55ab1c9ab8) | Dec 20, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [5bb21d6bf6](https://linux-hardware.org/?probe=5bb21d6bf6) | Dec 13, 2021 |
| ICL           | RAYbook Si1514              | [9ddc61deba](https://linux-hardware.org/?probe=9ddc61deba) | Sep 13, 2021 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [4f59992d0f](https://linux-hardware.org/?probe=4f59992d0f) | Sep 11, 2021 |
| HP            | Laptop 15-dw3xxx            | [d8b35044ab](https://linux-hardware.org/?probe=d8b35044ab) | Jul 29, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [9b2c758081](https://linux-hardware.org/?probe=9b2c758081) | Jun 10, 2021 |
| ASUSTek       | X75VD                       | [95ea9551da](https://linux-hardware.org/?probe=95ea9551da) | Apr 05, 2021 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [916d4b225b](https://linux-hardware.org/?probe=916d4b225b) | Mar 30, 2021 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [ebfafc7409](https://linux-hardware.org/?probe=ebfafc7409) | Mar 26, 2021 |
| HUAWEI        | BOHL-WXX9                   | [cf5559d576](https://linux-hardware.org/?probe=cf5559d576) | Mar 26, 2021 |
| HP            | Pavilion g6                 | [1ca79b1950](https://linux-hardware.org/?probe=1ca79b1950) | Mar 26, 2021 |
| Pegatron      | A35                         | [9923a21e8c](https://linux-hardware.org/?probe=9923a21e8c) | Mar 04, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Red OS 7.3   | 62        | 33.7%   |
| Red OS 7.3.1 | 45        | 24.46%  |
| Red OS 7.3.2 | 41        | 22.28%  |
| Red OS 8.0   | 35        | 19.02%  |
| Red OS 7.2   | 1         | 0.54%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Red OS | 174       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Notebooks | Percent |
|----------------------------|-----------|---------|
| 5.15.10-1.el7.x86_64       | 25        | 12.82%  |
| 5.15.72-1.el7.3.x86_64     | 23        | 11.79%  |
| 6.1.52-1.el7.3.x86_64      | 20        | 10.26%  |
| 5.15.87-1.el7.3.x86_64     | 16        | 8.21%   |
| 6.6.6-1.red80.x86_64       | 14        | 7.18%   |
| 6.6.51-1.red80.x86_64      | 13        | 6.67%   |
| 5.15.35-4.el7.3.x86_64     | 10        | 5.13%   |
| 5.10.29-1.el7.x86_64       | 10        | 5.13%   |
| 6.6.34-1.red80.x86_64      | 7         | 3.59%   |
| 5.15.35-1.el7.3.x86_64     | 6         | 3.08%   |
| 5.15.125-1.el7.3.x86_64    | 5         | 2.56%   |
| 6.1.38-2.el7.3.x86_64      | 4         | 2.05%   |
| 6.1.20-2.el7.3.x86_64      | 4         | 2.05%   |
| 5.15.35-5.el7.3.x86_64     | 4         | 2.05%   |
| 6.6.26-1.red80.x86_64      | 3         | 1.54%   |
| 6.1.94-1.el7.3.x86_64      | 3         | 1.54%   |
| 6.1.44-1.el7.3.x86_64      | 3         | 1.54%   |
| 5.10.1-1.el7.x86_64        | 3         | 1.54%   |
| 6.1.110-1.el7.3.x86_64     | 2         | 1.03%   |
| 5.15.78-2.el7.3.x86_64     | 2         | 1.03%   |
| 5.15.131-1.el7.3.x86_64    | 2         | 1.03%   |
| 5.15.10-4.el7.x86_64       | 2         | 1.03%   |
| 5.10.29-3.el7.x86_64       | 2         | 1.03%   |
| 5.10.24-2.el7.x86_64       | 2         | 1.03%   |
| 6.8.0-rc5+                 | 1         | 0.51%   |
| 6.6.52-1.red80.x86_64-rt43 | 1         | 0.51%   |
| 6.1.52-1.red80.x86_64      | 1         | 0.51%   |
| 5.18.1-1.el7.x86_64        | 1         | 0.51%   |
| 5.15.120                   | 1         | 0.51%   |
| 5.15.10-3.el7.x86_64       | 1         | 0.51%   |
| 5.15.10-2.el7.x86_64       | 1         | 0.51%   |
| 5.13.15-1.el7.x86_64       | 1         | 0.51%   |
| 5.10.24-1.el7.x86_64       | 1         | 0.51%   |
| 4.19.79-1.el7.x86_64       | 1         | 0.51%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.15.10  | 29        | 14.95%  |
| 5.15.72  | 23        | 11.86%  |
| 6.1.52   | 21        | 10.82%  |
| 5.15.35  | 19        | 9.79%   |
| 5.15.87  | 16        | 8.25%   |
| 6.6.6    | 14        | 7.22%   |
| 6.6.51   | 13        | 6.7%    |
| 5.10.29  | 12        | 6.19%   |
| 6.6.34   | 7         | 3.61%   |
| 5.15.125 | 5         | 2.58%   |
| 6.1.38   | 4         | 2.06%   |
| 6.1.20   | 4         | 2.06%   |
| 6.6.26   | 3         | 1.55%   |
| 6.1.94   | 3         | 1.55%   |
| 6.1.44   | 3         | 1.55%   |
| 5.10.24  | 3         | 1.55%   |
| 5.10.1   | 3         | 1.55%   |
| 6.1.110  | 2         | 1.03%   |
| 5.15.78  | 2         | 1.03%   |
| 5.15.131 | 2         | 1.03%   |
| 6.8.0    | 1         | 0.52%   |
| 6.6.52   | 1         | 0.52%   |
| 5.18.1   | 1         | 0.52%   |
| 5.15.120 | 1         | 0.52%   |
| 5.13.15  | 1         | 0.52%   |
| 4.19.79  | 1         | 0.52%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 92        | 50.55%  |
| 6.1     | 35        | 19.23%  |
| 6.6     | 34        | 18.68%  |
| 5.10    | 17        | 9.34%   |
| 6.8     | 1         | 0.55%   |
| 5.18    | 1         | 0.55%   |
| 5.13    | 1         | 0.55%   |
| 4.19    | 1         | 0.55%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 174       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| MATE       | 138       | 77.97%  |
| Cinnamon   | 17        | 9.6%    |
| KDE5       | 11        | 6.21%   |
| X-Cinnamon | 8         | 4.52%   |
| GNOME      | 3         | 1.69%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 167       | 93.82%  |
| Wayland | 11        | 6.18%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GDM     | 153       | 86.44%  |
| SDDM    | 17        | 9.6%    |
| Unknown | 4         | 2.26%   |
| LightDM | 3         | 1.69%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| ru_RU   | 105       | 58.99%  |
| Unknown | 71        | 39.89%  |
| en_US   | 1         | 0.56%   |
| en_GB   | 1         | 0.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 145       | 82.86%  |
| BIOS | 30        | 17.14%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 171       | 97.71%  |
| Btrfs   | 2         | 1.14%   |
| Xfs     | 1         | 0.57%   |
| Overlay | 1         | 0.57%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 149       | 85.63%  |
| MBR     | 21        | 12.07%  |
| Unknown | 4         | 2.3%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 161       | 91.48%  |
| Yes       | 15        | 8.52%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 127       | 72.16%  |
| Yes       | 49        | 27.84%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 52        | 29.89%  |
| Hewlett-Packard                | 27        | 15.52%  |
| HUAWEI                         | 10        | 5.75%   |
| ASUSTek Computer               | 10        | 5.75%   |
| Acer                           | 10        | 5.75%   |
| ICL                            | 7         | 4.02%   |
| Dell                           | 7         | 4.02%   |
| MSI                            | 6         | 3.45%   |
| Aquarius                       | 4         | 2.3%    |
| Unknown                        | 4         | 2.3%    |
| Kraftway                       | 3         | 1.72%   |
| Graviton                       | 3         | 1.72%   |
| Digma                          | 3         | 1.72%   |
| MACHENIKE                      | 2         | 1.15%   |
| iRU                            | 2         | 1.15%   |
| IP3 Technology                 | 2         | 1.15%   |
| Infinix                        | 2         | 1.15%   |
| HONOR                          | 2         | 1.15%   |
| Gigabyte Technology            | 2         | 1.15%   |
| DEPO Computers                 | 2         | 1.15%   |
| 3Logic Group                   | 2         | 1.15%   |
| Toshiba                        | 1         | 0.57%   |
| Timi                           | 1         | 0.57%   |
| THUNDEROBOT                    | 1         | 0.57%   |
| TECNO Mobile Limited           | 1         | 0.57%   |
| Shanghai Zhaoxin Semiconductor | 1         | 0.57%   |
| Pegatron                       | 1         | 0.57%   |
| mtech                          | 1         | 0.57%   |
| KVADRA                         | 1         | 0.57%   |
| Getac                          | 1         | 0.57%   |
| Fujitsu Siemens                | 1         | 0.57%   |
| Chuwi                          | 1         | 0.57%   |
| Apple                          | 1         | 0.57%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Lenovo V15-IWL 81YE                  | 17        | 9.77%   |
| Unknown                              | 6         | 3.45%   |
| Lenovo ThinkBook 15 G3 ACL 21A4      | 3         | 1.72%   |
| Kraftway ACCORD                      | 3         | 1.72%   |
| ICL RAYbook Si1512                   | 3         | 1.72%   |
| HP Laptop 15s-eq1xxx                 | 3         | 1.72%   |
| Acer Aspire A315-24P                 | 3         | 1.72%   |
| Lenovo IdeaPad L340-15API 81LW       | 2         | 1.15%   |
| Lenovo G570 20079                    | 2         | 1.15%   |
| iRU 15ALC                            | 2         | 1.15%   |
| IP3 ACN30                            | 2         | 1.15%   |
| HUAWEI BOM-WXX9                      | 2         | 1.15%   |
| HUAWEI BOD-WXX9                      | 2         | 1.15%   |
| DEPO Computers DPH610S               | 2         | 1.15%   |
| Toshiba Satellite C650               | 1         | 0.57%   |
| Timi Redmi Book Pro 15 2022          | 1         | 0.57%   |
| THUNDEROBOT 911AirD                  | 1         | 0.57%   |
| TECNO Mobile Limited MEGABOOK T15AA  | 1         | 0.57%   |
| Shanghai Zhaoxin ZXE CRB             | 1         | 0.57%   |
| Pegatron A35                         | 1         | 0.57%   |
| mtech MTL1578                        | 1         | 0.57%   |
| MSI Sword 15 A12UE                   | 1         | 0.57%   |
| MSI MS-1738                          | 1         | 0.57%   |
| MSI Modern 15 B12M                   | 1         | 0.57%   |
| MSI Modern 14 C12M                   | 1         | 0.57%   |
| MSI GL62 6QF                         | 1         | 0.57%   |
| MSI FX610                            | 1         | 0.57%   |
| MACHENIKE MACHCREATOR-16             | 1         | 0.57%   |
| MACHENIKE L17A                       | 1         | 0.57%   |
| Lenovo V15 G2 ALC 82KD               | 1         | 0.57%   |
| Lenovo V15 G1 IML 82NB               | 1         | 0.57%   |
| Lenovo V130-15IKB 81HN               | 1         | 0.57%   |
| Lenovo ThinkPad X230 23245C8         | 1         | 0.57%   |
| Lenovo ThinkPad X220 4290RB3         | 1         | 0.57%   |
| Lenovo ThinkPad T61 6464WM6          | 1         | 0.57%   |
| Lenovo ThinkPad T460s 20FAS1TQ02     | 1         | 0.57%   |
| Lenovo ThinkPad T430 23493V2         | 1         | 0.57%   |
| Lenovo ThinkPad T14 Gen 3 21AJS2DE00 | 1         | 0.57%   |
| Lenovo ThinkPad T14 Gen 3 21AJS2DD00 | 1         | 0.57%   |
| Lenovo ThinkPad E15 Gen 4 21E6009UGP | 1         | 0.57%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Lenovo V15-IWL                | 17        | 9.77%   |
| Lenovo IdeaPad                | 13        | 7.47%   |
| Lenovo ThinkPad               | 9         | 5.17%   |
| HP Laptop                     | 7         | 4.02%   |
| Acer Aspire                   | 7         | 4.02%   |
| Lenovo ThinkBook              | 6         | 3.45%   |
| Unknown                       | 6         | 3.45%   |
| HP ProBook                    | 5         | 2.87%   |
| HP EliteBook                  | 5         | 2.87%   |
| ICL RAYbook                   | 4         | 2.3%    |
| HP Pavilion                   | 4         | 2.3%    |
| Kraftway ACCORD               | 3         | 1.72%   |
| Digma EVE                     | 3         | 1.72%   |
| Dell Vostro                   | 3         | 1.72%   |
| Dell Inspiron                 | 3         | 1.72%   |
| ASUS Vivobook                 | 3         | 1.72%   |
| MSI Modern                    | 2         | 1.15%   |
| Lenovo V15                    | 2         | 1.15%   |
| Lenovo G570                   | 2         | 1.15%   |
| Lenovo B590                   | 2         | 1.15%   |
| iRU 15ALC                     | 2         | 1.15%   |
| IP3 ACN30                     | 2         | 1.15%   |
| Infinix INBOOK                | 2         | 1.15%   |
| HUAWEI BOM-WXX9               | 2         | 1.15%   |
| HUAWEI BOD-WXX9               | 2         | 1.15%   |
| HP 250                        | 2         | 1.15%   |
| Gigabyte G5                   | 2         | 1.15%   |
| DEPO Computers DPH610S        | 2         | 1.15%   |
| Aquarius NS685U               | 2         | 1.15%   |
| Acer Extensa                  | 2         | 1.15%   |
| Toshiba Satellite             | 1         | 0.57%   |
| Timi Redmi                    | 1         | 0.57%   |
| THUNDEROBOT 911AirD           | 1         | 0.57%   |
| TECNO Mobile Limited MEGABOOK | 1         | 0.57%   |
| Shanghai Zhaoxin ZXE          | 1         | 0.57%   |
| Pegatron A35                  | 1         | 0.57%   |
| mtech MTL1578                 | 1         | 0.57%   |
| MSI Sword                     | 1         | 0.57%   |
| MSI MS-1738                   | 1         | 0.57%   |
| MSI GL62                      | 1         | 0.57%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 35        | 20.11%  |
| 2022 | 32        | 18.39%  |
| 2021 | 30        | 17.24%  |
| 2020 | 18        | 10.34%  |
| 2010 | 12        | 6.9%    |
| 2012 | 11        | 6.32%   |
| 2023 | 9         | 5.17%   |
| 2011 | 6         | 3.45%   |
| 2017 | 4         | 2.3%    |
| 2024 | 2         | 1.15%   |
| 2018 | 2         | 1.15%   |
| 2016 | 2         | 1.15%   |
| 2014 | 2         | 1.15%   |
| 2013 | 2         | 1.15%   |
| 2009 | 2         | 1.15%   |
| 2008 | 2         | 1.15%   |
| 2007 | 2         | 1.15%   |
| 2015 | 1         | 0.57%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 174       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 174       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 174       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 96        | 54.86%  |
| 16.01-24.0 | 25        | 14.29%  |
| 8.01-16.0  | 23        | 13.14%  |
| 3.01-4.0   | 19        | 10.86%  |
| 32.01-64.0 | 5         | 2.86%   |
| 2.01-3.0   | 5         | 2.86%   |
| 1.01-2.0   | 2         | 1.14%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 102       | 54.84%  |
| 2.01-3.0   | 48        | 25.81%  |
| 3.01-4.0   | 16        | 8.6%    |
| 4.01-8.0   | 9         | 4.84%   |
| 0.51-1.0   | 8         | 4.3%    |
| 8.01-16.0  | 2         | 1.08%   |
| 16.01-24.0 | 1         | 0.54%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 143       | 80.79%  |
| 2      | 26        | 14.69%  |
| 3      | 6         | 3.39%   |
| 4      | 1         | 0.56%   |
| 0      | 1         | 0.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 141       | 80.57%  |
| Yes       | 34        | 19.43%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 132       | 75.86%  |
| No        | 42        | 24.14%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 165       | 94.83%  |
| No        | 9         | 5.17%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 147       | 84.48%  |
| No        | 27        | 15.52%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Russia  | 171       | 98.28%  |
| Ukraine | 2         | 1.15%   |
| Germany | 1         | 0.57%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 44        | 24.44%  |
| Salekhard         | 22        | 12.22%  |
| Murom             | 17        | 9.44%   |
| St Petersburg     | 10        | 5.56%   |
| Perm              | 6         | 3.33%   |
| Yekaterinburg     | 5         | 2.78%   |
| Krasnodar         | 4         | 2.22%   |
| Yakutsk           | 3         | 1.67%   |
| Vladimir          | 3         | 1.67%   |
| Ryazan            | 3         | 1.67%   |
| Orenburg          | 3         | 1.67%   |
| Novy Urengoy      | 3         | 1.67%   |
| Saransk           | 2         | 1.11%   |
| Samara            | 2         | 1.11%   |
| Novosibirsk       | 2         | 1.11%   |
| Nizhniy Novgorod  | 2         | 1.11%   |
| Muromskiy         | 2         | 1.11%   |
| Kursk             | 2         | 1.11%   |
| Krasnoyarsk       | 2         | 1.11%   |
| Zima              | 1         | 0.56%   |
| Zelenogorsk       | 1         | 0.56%   |
| Zadonsk           | 1         | 0.56%   |
| Yuzhno-Sakhalinsk | 1         | 0.56%   |
| Yaroslavl         | 1         | 0.56%   |
| Voronezh          | 1         | 0.56%   |
| Volzhskiy         | 1         | 0.56%   |
| Volgograd         | 1         | 0.56%   |
| Vladivostok       | 1         | 0.56%   |
| Ulyanovsk         | 1         | 0.56%   |
| Tver              | 1         | 0.56%   |
| Tambov            | 1         | 0.56%   |
| Strezhevoy        | 1         | 0.56%   |
| Stavropol         | 1         | 0.56%   |
| Sobinka           | 1         | 0.56%   |
| Sevastopol        | 1         | 0.56%   |
| Saratov           | 1         | 0.56%   |
| Sarapul           | 1         | 0.56%   |
| Pyatigorsk        | 1         | 0.56%   |
| Pushkino          | 1         | 0.56%   |
| Omsk              | 1         | 0.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 35        | 53     | 16.75%  |
| WDC                            | 24        | 42     | 11.48%  |
| SK hynix                       | 16        | 18     | 7.66%   |
| Seagate                        | 13        | 16     | 6.22%   |
| A-DATA Technology              | 12        | 12     | 5.74%   |
| Unknown                        | 7         | 7      | 3.35%   |
| Silicon Motion                 | 7         | 7      | 3.35%   |
| Micron Technology              | 7         | 13     | 3.35%   |
| Toshiba                        | 6         | 33     | 2.87%   |
| SanDisk                        | 6         | 6      | 2.87%   |
| Kingston                       | 6         | 8      | 2.87%   |
| Foxline                        | 6         | 6      | 2.87%   |
| Phison                         | 5         | 5      | 2.39%   |
| Intel                          | 5         | 5      | 2.39%   |
| HGST                           | 5         | 5      | 2.39%   |
| YMTC                           | 4         | 4      | 1.91%   |
| FORESEE                        | 4         | 5      | 1.91%   |
| China                          | 4         | 15     | 1.91%   |
| KIOXIA                         | 3         | 3      | 1.44%   |
| Gigabyte Technology            | 3         | 3      | 1.44%   |
| UMIS                           | 2         | 2      | 0.96%   |
| Patriot                        | 2         | 2      | 0.96%   |
| Netac                          | 2         | 4      | 0.96%   |
| KingSpec                       | 2         | 5      | 0.96%   |
| JMicron Technology             | 2         | 2      | 0.96%   |
| Hitachi                        | 2         | 2      | 0.96%   |
| Crucial                        | 2         | 2      | 0.96%   |
| Unknown                        | 2         | 2      | 0.96%   |
| Transcend                      | 1         | 1      | 0.48%   |
| Thinkplus                      | 1         | 1      | 0.48%   |
| SSSTC                          | 1         | 1      | 0.48%   |
| SPCC Sol                       | 1         | 1      | 0.48%   |
| Solid State Storage Technology | 1         | 1      | 0.48%   |
| SM400                          | 1         | 1      | 0.48%   |
| Lenovo                         | 1         | 1      | 0.48%   |
| Kimtigo                        | 1         | 2      | 0.48%   |
| ITHOO                          | 1         | 1      | 0.48%   |
| HUAWEI                         | 1         | 1      | 0.48%   |
| Hikvision                      | 1         | 1      | 0.48%   |
| Fujitsu                        | 1         | 1      | 0.48%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Samsung MZALQ256HAJD-000L2 256GB       | 18        | 8.49%   |
| Foxline FLSSD256M80E13TCX5 256GB       | 5         | 2.36%   |
| Silicon Motion Wodposit NVMe SSD 256GB | 4         | 1.89%   |
| Seagate ST1000LM035-1RK172 1TB         | 4         | 1.89%   |
| SanDisk NVMe SSD Drive 512GB           | 3         | 1.42%   |
| Samsung MZALQ512HALU-000L2 512GB       | 3         | 1.42%   |
| YMTC PC005 512GB                       | 2         | 0.94%   |
| WDC WD10SPZX-24Z10 1TB                 | 2         | 0.94%   |
| WDC WD10SPZX-00Z10T0 1TB               | 2         | 0.94%   |
| WDC PC SN530 SDBPNPZ-512G-1114 512GB   | 2         | 0.94%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB   | 2         | 0.94%   |
| Unknown NVMe SSD Drive 512GB           | 2         | 0.94%   |
| Unknown 58K722  128GB                  | 2         | 0.94%   |
| Toshiba MQ01ABF050 500GB               | 2         | 0.94%   |
| SK hynix SKHynix_HFM256GD3HX015N 256GB | 2         | 0.94%   |
| SK hynix PC711 HFS512GDE9X073N 512GB   | 2         | 0.94%   |
| Silicon Motion PCIe-8 SSD 512GB        | 2         | 0.94%   |
| Seagate ST500LT012-1DG142 500GB        | 2         | 0.94%   |
| Samsung MZVL4512HBLU-00BTW 512GB       | 2         | 0.94%   |
| Samsung MZALQ256HBJD-00BL2 256GB       | 2         | 0.94%   |
| Micron 2450_MTFDKBA512TFK 512GB        | 2         | 0.94%   |
| Micron 2400_MTFDKBA512QFM 512GB        | 2         | 0.94%   |
| KIOXIA KBG40ZNS256G NVMe 256GB         | 2         | 0.94%   |
| Kingston SA400S37240G 240GB SSD        | 2         | 0.94%   |
| JMicron Generic 500GB                  | 2         | 0.94%   |
| Gigabyte GP-GSM2NE3256GNTD 256GB       | 2         | 0.94%   |
| FORESEE XP1000F512G 512GB              | 2         | 0.94%   |
| A-DATA SX6000PNP 512GB                 | 2         | 0.94%   |
| A-DATA SX6000LNP 256GB                 | 2         | 0.94%   |
| A-DATA SU650 240GB SSD                 | 2         | 0.94%   |
| Unknown                                | 2         | 0.94%   |
| YMTC PC300-512GB-B                     | 1         | 0.47%   |
| YMTC PC210-512GB-B                     | 1         | 0.47%   |
| WDC WDS500G2B0B-00YS70 500GB SSD       | 1         | 0.47%   |
| WDC WDS250G2B0A-00SM50 250GB SSD       | 1         | 0.47%   |
| WDC WDS240G3G0A-00BJG0 240GB SSD       | 1         | 0.47%   |
| WDC WD5000BPVT-55HXZT3 500GB           | 1         | 0.47%   |
| WDC WD3200BPVT-24ZEST0 320GB           | 1         | 0.47%   |
| WDC WD3200BPVT-24JJ5T0 320GB           | 1         | 0.47%   |
| WDC WD3200BEVT-60ZCT1 320GB            | 1         | 0.47%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Notebooks | Drives | Percent |
|--------------------|-----------|--------|---------|
| Seagate            | 13        | 16     | 33.33%  |
| WDC                | 11        | 29     | 28.21%  |
| HGST               | 5         | 5      | 12.82%  |
| Toshiba            | 4         | 30     | 10.26%  |
| JMicron Technology | 2         | 2      | 5.13%   |
| Hitachi            | 2         | 2      | 5.13%   |
| Unknown            | 1         | 1      | 2.56%   |
| Fujitsu            | 1         | 1      | 2.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 4      | 9.52%   |
| Samsung Electronics | 4         | 4      | 9.52%   |
| Kingston            | 4         | 6      | 9.52%   |
| China               | 4         | 15     | 9.52%   |
| A-DATA Technology   | 4         | 4      | 9.52%   |
| SanDisk             | 2         | 2      | 4.76%   |
| Patriot             | 2         | 2      | 4.76%   |
| Netac               | 2         | 4      | 4.76%   |
| KingSpec            | 2         | 5      | 4.76%   |
| Crucial             | 2         | 2      | 4.76%   |
| Transcend           | 1         | 1      | 2.38%   |
| Thinkplus           | 1         | 1      | 2.38%   |
| SPCC Sol            | 1         | 1      | 2.38%   |
| SM400               | 1         | 1      | 2.38%   |
| SK hynix            | 1         | 1      | 2.38%   |
| Micron Technology   | 1         | 1      | 2.38%   |
| Lenovo              | 1         | 1      | 2.38%   |
| Intel               | 1         | 1      | 2.38%   |
| FORESEE             | 1         | 1      | 2.38%   |
| Corsair             | 1         | 2      | 2.38%   |
| Apacer              | 1         | 2      | 2.38%   |
| Unknown             | 1         | 1      | 2.38%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 116       | 148    | 58%     |
| SSD     | 38        | 62     | 19%     |
| HDD     | 37        | 86     | 18.5%   |
| MMC     | 5         | 5      | 2.5%    |
| Unknown | 4         | 4      | 2%      |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 116       | 147    | 60.73%  |
| SATA | 63        | 143    | 32.98%  |
| SAS  | 7         | 10     | 3.66%   |
| MMC  | 5         | 5      | 2.62%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 53        | 93     | 74.65%  |
| 0.51-1.0   | 18        | 55     | 25.35%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 82        | 45.56%  |
| 251-500    | 52        | 28.89%  |
| 501-1000   | 18        | 10%     |
| 51-100     | 10        | 5.56%   |
| 1001-2000  | 8         | 4.44%   |
| 21-50      | 6         | 3.33%   |
| 1-20       | 4         | 2.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 121       | 65.76%  |
| 21-50     | 31        | 16.85%  |
| 101-250   | 11        | 5.98%   |
| 51-100    | 11        | 5.98%   |
| 501-1000  | 6         | 3.26%   |
| 251-500   | 3         | 1.63%   |
| 1001-2000 | 1         | 0.54%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD3200BPVT-24ZEST0 320GB        | 1         | 1      | 4.55%   |
| WDC WD3200BEVT-22A23T0 320GB        | 1         | 1      | 4.55%   |
| WDC WD10SPZX-24Z10 1TB              | 1         | 1      | 4.55%   |
| WDC WD Green M.2 2280 240GB         | 1         | 1      | 4.55%   |
| Toshiba MQ01ABF050 500GB            | 1         | 16     | 4.55%   |
| Toshiba MK5075GSX 500GB             | 1         | 10     | 4.55%   |
| Toshiba MK5059GSXP 500GB            | 1         | 1      | 4.55%   |
| Toshiba MK2565GSX 250GB             | 1         | 1      | 4.55%   |
| Seagate ST9500420AS 500GB           | 1         | 1      | 4.55%   |
| Seagate ST9500325AS 500GB           | 1         | 1      | 4.55%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 1      | 4.55%   |
| Seagate ST500LT012-9WS142 500GB     | 1         | 1      | 4.55%   |
| Seagate ST500LT012-1DG142 500GB     | 1         | 1      | 4.55%   |
| Seagate ST1000LM035-1RK172 1TB      | 1         | 1      | 4.55%   |
| Netac SSD 512GB                     | 1         | 3      | 4.55%   |
| Kingston SUV400S37120G 120GB SSD    | 1         | 1      | 4.55%   |
| Hitachi HTS725032A9A364 320GB       | 1         | 1      | 4.55%   |
| Hitachi HTS543232A7A384 320GB       | 1         | 1      | 4.55%   |
| HGST HTS721010A9E630 1TB            | 1         | 1      | 4.55%   |
| Fujitsu MJA2500BH FFS G1 500GB      | 1         | 1      | 4.55%   |
| A-DATA Technology SX6000NP 512GB    | 1         | 1      | 4.55%   |
| A-DATA Technology SU800 256GB SSD   | 1         | 1      | 4.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 6         | 6      | 28.57%  |
| WDC               | 4         | 4      | 19.05%  |
| Toshiba           | 3         | 28     | 14.29%  |
| Hitachi           | 2         | 2      | 9.52%   |
| A-DATA Technology | 2         | 2      | 9.52%   |
| Netac             | 1         | 3      | 4.76%   |
| Kingston          | 1         | 1      | 4.76%   |
| HGST              | 1         | 1      | 4.76%   |
| Fujitsu           | 1         | 1      | 4.76%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 6      | 37.5%   |
| WDC     | 3         | 3      | 18.75%  |
| Toshiba | 3         | 28     | 18.75%  |
| Hitachi | 2         | 2      | 12.5%   |
| HGST    | 1         | 1      | 6.25%   |
| Fujitsu | 1         | 1      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 16        | 41     | 76.19%  |
| SSD  | 4         | 6      | 19.05%  |
| NVMe | 1         | 1      | 4.76%   |

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
| Works    | 148       | 227    | 78.31%  |
| Malfunc  | 21        | 48     | 11.11%  |
| Detected | 20        | 30     | 10.58%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 113       | 45.38%  |
| Samsung Electronics            | 30        | 12.05%  |
| AMD                            | 20        | 8.03%   |
| SK hynix                       | 15        | 6.02%   |
| Phison Electronics             | 14        | 5.62%   |
| SanDisk                        | 12        | 4.82%   |
| Silicon Motion                 | 7         | 2.81%   |
| Micron Technology              | 6         | 2.41%   |
| ADATA Technology               | 6         | 2.41%   |
| Yangtze Memory Technologies    | 4         | 1.61%   |
| Shenzhen Longsys Electronics   | 3         | 1.2%    |
| MAXIO Technology (Hangzhou)    | 3         | 1.2%    |
| KIOXIA                         | 3         | 1.2%    |
| Union Memory (Shenzhen)        | 2         | 0.8%    |
| Toshiba America Info Systems   | 2         | 0.8%    |
| Solid State Storage Technology | 2         | 0.8%    |
| Realtek Semiconductor          | 2         | 0.8%    |
| Kingston Technology Company    | 2         | 0.8%    |
| Zhaoxin                        | 1         | 0.4%    |
| ShenZhen TIGO Semiconductor    | 1         | 0.4%    |
| Nvidia                         | 1         | 0.4%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                                              | Notebooks | Percent |
|--------------------------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                                                  | 30        | 11.41%  |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                                                        | 26        | 9.89%   |
| AMD FCH SATA Controller [AHCI mode]                                                                                | 16        | 6.08%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                                                | 11        | 4.18%   |
| Intel Volume Management Device NVMe RAID Controller                                                                | 10        | 3.8%    |
| Intel Tiger Lake-LP SATA Controller                                                                                | 10        | 3.8%    |
| Intel Alder Lake-P SATA AHCI Controller                                                                            | 8         | 3.04%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                                                   | 8         | 3.04%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                                               | 7         | 2.66%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)                                          | 6         | 2.28%   |
| Intel Comet Lake SATA AHCI Controller                                                                              | 6         | 2.28%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                                                       | 5         | 1.9%    |
| SK hynix BC511 NVMe SSD                                                                                            | 4         | 1.52%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                                                  | 4         | 1.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller                                       | 4         | 1.52%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                                                     | 4         | 1.52%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                                                  | 4         | 1.52%   |
| SK hynix BC901 NVMe Solid State Drive (DRAM-less)                                                                  | 3         | 1.14%   |
| Silicon Motion Non-Volatile memory controller                                                                      | 3         | 1.14%   |
| Shenzhen Longsys FORESEE XP1000 / Lexar Professional CFexpress Type B Gold series, NM620 PCIe NVME SSD (DRAM-less) | 3         | 1.14%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                                            | 3         | 1.14%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                                                        | 3         | 1.14%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                                           | 3         | 1.14%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                                                         | 3         | 1.14%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                                                 | 3         | 1.14%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                                              | 3         | 1.14%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                                           | 3         | 1.14%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                                                     | 3         | 1.14%   |
| ADATA XPG GAMMIXS1 1L, XPG GAMMIX S5, LEGEND 710 / 740, SWORDFISH NVMe SSD (DRAM-less)                             | 3         | 1.14%   |
| Yangtze Memory PC005 NVMe SSD                                                                                      | 2         | 0.76%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                                               | 2         | 0.76%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                                                      | 2         | 0.76%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                                                      | 2         | 0.76%   |
| Phison E16 PCIe4 NVMe Controller                                                                                   | 2         | 0.76%   |
| Micron 2400 NVMe SSD (DRAM-less)                                                                                   | 2         | 0.76%   |
| Kingston Company NV1 NVMe SSD [SM2263XT] (DRAM-less)                                                               | 2         | 0.76%   |
| Intel Tiger Lake SATA AHCI Controller                                                                              | 2         | 0.76%   |
| Intel SSD 660P Series                                                                                              | 2         | 0.76%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                                                 | 2         | 0.76%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                                              | 2         | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 124       | 47.88%  |
| NVMe | 116       | 44.79%  |
| RAID | 13        | 5.02%   |
| IDE  | 6         | 2.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 132       | 75.86%  |
| AMD          | 41        | 23.56%  |
| CentaurHauls | 1         | 0.57%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8265U CPU @ 1.60GHz             | 18        | 10.29%  |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 10        | 5.71%   |
| Intel Core i5-8279U CPU @ 2.40GHz             | 6         | 3.43%   |
| Intel Core i5-8259U CPU @ 2.30GHz             | 5         | 2.86%   |
| Intel 12th Gen Core i5-1235U                  | 5         | 2.86%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 5         | 2.86%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 2.29%   |
| AMD Ryzen 3 5300U with Radeon Graphics        | 4         | 2.29%   |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 3         | 1.71%   |
| Intel 12th Gen Core i5-12500H                 | 3         | 1.71%   |
| AMD Ryzen 5 7520U with Radeon Graphics        | 3         | 1.71%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 3         | 1.71%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 3         | 1.71%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.71%   |
| AMD Ryzen 3 5400U with Radeon Graphics        | 3         | 1.71%   |
| AMD Ryzen 3 4300U with Radeon Graphics        | 3         | 1.71%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 1.14%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 1.14%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 1.14%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 1.14%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 2         | 1.14%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 2         | 1.14%   |
| Intel 12th Gen Core i7-12700H                 | 2         | 1.14%   |
| Intel 12th Gen Core i7-1255U                  | 2         | 1.14%   |
| Intel 12th Gen Core i3-1215U                  | 2         | 1.14%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.14%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 1.14%   |
| Intel Pentium Gold 7505 @ 2.00GHz             | 1         | 0.57%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 1         | 0.57%   |
| Intel Pentium CPU J3710 @ 1.60GHz             | 1         | 0.57%   |
| Intel Pentium CPU 6405U @ 2.40GHz             | 1         | 0.57%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 1         | 0.57%   |
| Intel N100                                    | 1         | 0.57%   |
| Intel Core Ultra 7 155H                       | 1         | 0.57%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 0.57%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 0.57%   |
| Intel Core i7-3840QM CPU @ 2.80GHz            | 1         | 0.57%   |
| Intel Core i7-3740QM CPU @ 2.70GHz            | 1         | 0.57%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 1         | 0.57%   |
| Intel Core i7 CPU L 640 @ 2.13GHz             | 1         | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 51        | 29.31%  |
| Other                          | 44        | 25.29%  |
| Intel Core i3                  | 16        | 9.2%    |
| AMD Ryzen 5                    | 15        | 8.62%   |
| AMD Ryzen 3                    | 13        | 7.47%   |
| AMD Ryzen 7                    | 6         | 3.45%   |
| Intel Core i7                  | 5         | 2.87%   |
| Intel Celeron                  | 5         | 2.87%   |
| Intel Pentium                  | 4         | 2.3%    |
| Intel Core 2 Duo               | 4         | 2.3%    |
| AMD Phenom II                  | 2         | 1.15%   |
| Intel Pentium Gold             | 1         | 0.57%   |
| Intel Core                     | 1         | 0.57%   |
| Intel Celeron Dual-Core        | 1         | 0.57%   |
| Intel Atom                     | 1         | 0.57%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.57%   |
| AMD Turion II                  | 1         | 0.57%   |
| AMD Ryzen 9                    | 1         | 0.57%   |
| AMD Ryzen 5 PRO                | 1         | 0.57%   |
| AMD A4                         | 1         | 0.57%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 83        | 47.7%   |
| 2      | 50        | 28.74%  |
| 6      | 14        | 8.05%   |
| 8      | 9         | 5.17%   |
| 12     | 7         | 4.02%   |
| 10     | 7         | 4.02%   |
| 14     | 2         | 1.15%   |
| 16     | 1         | 0.57%   |
| 3      | 1         | 0.57%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 174       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 144       | 82.76%  |
| 1      | 30        | 17.24%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 174       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 26        | 14.69%  |
| 0x806ec    | 24        | 13.56%  |
| 0x806c1    | 15        | 8.47%   |
| 0x806ea    | 12        | 6.78%   |
| 0x08608103 | 9         | 5.08%   |
| 0x906a3    | 8         | 4.52%   |
| 0x906a4    | 7         | 3.95%   |
| 0x306a9    | 6         | 3.39%   |
| 0x206a7    | 6         | 3.39%   |
| 0x08600106 | 5         | 2.82%   |
| 0x40651    | 4         | 2.26%   |
| 0x0a50000c | 4         | 2.26%   |
| 0x08108102 | 4         | 2.26%   |
| 0x08a00006 | 3         | 1.69%   |
| 0xb06e0    | 2         | 1.13%   |
| 0x906ea    | 2         | 1.13%   |
| 0x806d1    | 2         | 1.13%   |
| 0x806c2    | 2         | 1.13%   |
| 0x506e3    | 2         | 1.13%   |
| 0x506ca    | 2         | 1.13%   |
| 0x20652    | 2         | 1.13%   |
| 0x0a50000d | 2         | 1.13%   |
| 0x08600104 | 2         | 1.13%   |
| 0x08108109 | 2         | 1.13%   |
| 0x010000c8 | 2         | 1.13%   |
| 0xa0660    | 1         | 0.56%   |
| 0x906eb    | 1         | 0.56%   |
| 0x906e9    | 1         | 0.56%   |
| 0x90675    | 1         | 0.56%   |
| 0x90672    | 1         | 0.56%   |
| 0x706e5    | 1         | 0.56%   |
| 0x6fa      | 1         | 0.56%   |
| 0x506c9    | 1         | 0.56%   |
| 0x406e3    | 1         | 0.56%   |
| 0x406c4    | 1         | 0.56%   |
| 0x20655    | 1         | 0.56%   |
| 0x1067a    | 1         | 0.56%   |
| 0x10676    | 1         | 0.56%   |
| 0x0a704101 | 1         | 0.56%   |
| 0x0a50000f | 1         | 0.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KabyLake          | 43        | 24.71%  |
| TigerLake         | 21        | 12.07%  |
| Alderlake Hybrid  | 20        | 11.49%  |
| Unknown           | 17        | 9.77%   |
| Zen 2             | 7         | 4.02%   |
| Westmere          | 7         | 4.02%   |
| SandyBridge       | 7         | 4.02%   |
| IvyBridge         | 7         | 4.02%   |
| Zen+              | 6         | 3.45%   |
| Zen 3             | 6         | 3.45%   |
| Haswell           | 5         | 2.87%   |
| Penryn            | 4         | 2.3%    |
| Skylake           | 3         | 1.72%   |
| K10               | 3         | 1.72%   |
| IceLake           | 3         | 1.72%   |
| Goldmont          | 3         | 1.72%   |
| Gracemont         | 2         | 1.15%   |
| CometLake         | 2         | 1.15%   |
| Zen               | 1         | 0.57%   |
| Silvermont        | 1         | 0.57%   |
| Meteorlake Hybrid | 1         | 0.57%   |
| K8 & K10 hybrid   | 1         | 0.57%   |
| Goldmont plus     | 1         | 0.57%   |
| Excavator         | 1         | 0.57%   |
| Core              | 1         | 0.57%   |
| Bonnell           | 1         | 0.57%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 127       | 61.06%  |
| AMD     | 49        | 23.56%  |
| Nvidia  | 31        | 14.9%   |
| Zhaoxin | 1         | 0.48%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 19        | 8.88%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 14        | 6.54%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                              | 11        | 5.14%   |
| AMD Lucienne                                                                  | 9         | 4.21%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                     | 7         | 3.27%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 7         | 3.27%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 7         | 3.27%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                   | 7         | 3.27%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                   | 6         | 2.8%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 6         | 2.8%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 6         | 2.8%    |
| Intel Haswell-ULT Integrated Graphics Controller                              | 5         | 2.34%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 5         | 2.34%   |
| Intel Core Processor Integrated Graphics Controller                           | 4         | 1.87%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                     | 4         | 1.87%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                  | 4         | 1.87%   |
| AMD Mendocino                                                                 | 4         | 1.87%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 3         | 1.4%    |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                       | 3         | 1.4%    |
| Intel Alder Lake-P Integrated Graphics Controller                             | 3         | 1.4%    |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                             | 2         | 0.93%   |
| Intel UHD Graphics 620                                                        | 2         | 0.93%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 2         | 0.93%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 2         | 0.93%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 2         | 0.93%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 2         | 0.93%   |
| Intel HD Graphics 530                                                         | 2         | 0.93%   |
| Intel HD Graphics 500                                                         | 2         | 0.93%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 2         | 0.93%   |
| Intel Alder Lake-UP3 GT1 [UHD Graphics]                                       | 2         | 0.93%   |
| Intel Alder Lake-N [UHD Graphics]                                             | 2         | 0.93%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 2         | 0.93%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                     | 2         | 0.93%   |
| AMD Rembrandt [Radeon 680M]                                                   | 2         | 0.93%   |
| Zhaoxin KX-6000 C-960 GPU                                                     | 1         | 0.47%   |
| Nvidia TU117M [GeForce MX550]                                                 | 1         | 0.47%   |
| Nvidia TU104BM [GeForce RTX 2080 SUPER Mobile / Max-Q]                        | 1         | 0.47%   |
| Nvidia GT218M [NVS 3100M]                                                     | 1         | 0.47%   |
| Nvidia GT218M [GeForce 310M]                                                  | 1         | 0.47%   |
| Nvidia GT216M [GeForce GT 325M]                                               | 1         | 0.47%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 97        | 55.75%  |
| 1 x AMD        | 36        | 20.69%  |
| Intel + Nvidia | 24        | 13.79%  |
| Intel + AMD    | 6         | 3.45%   |
| AMD + Nvidia   | 4         | 2.3%    |
| 2 x AMD        | 3         | 1.72%   |
| 1 x Nvidia     | 2         | 1.15%   |
| 2 x Nvidia     | 1         | 0.57%   |
| 1 x Zhaoxin    | 1         | 0.57%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 156       | 88.14%  |
| Unknown     | 15        | 8.47%   |
| Proprietary | 6         | 3.39%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 111       | 62.01%  |
| 0.01-0.5   | 25        | 13.97%  |
| 1.01-2.0   | 24        | 13.41%  |
| 0.51-1.0   | 10        | 5.59%   |
| 3.01-4.0   | 8         | 4.47%   |
| 7.01-8.0   | 1         | 0.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 70        | 38.89%  |
| LG Display              | 26        | 14.44%  |
| Chimei Innolux          | 22        | 12.22%  |
| Samsung Electronics     | 12        | 6.67%   |
| AU Optronics            | 12        | 6.67%   |
| PANDA                   | 5         | 2.78%   |
| Philips                 | 4         | 2.22%   |
| CSO                     | 3         | 1.67%   |
| ViewSonic               | 2         | 1.11%   |
| TMX                     | 2         | 1.11%   |
| NLE                     | 2         | 1.11%   |
| Lenovo                  | 2         | 1.11%   |
| Acer                    | 2         | 1.11%   |
| Toshiba                 | 1         | 0.56%   |
| SKG                     | 1         | 0.56%   |
| Sharp                   | 1         | 0.56%   |
| RGT                     | 1         | 0.56%   |
| NEC Computers           | 1         | 0.56%   |
| KVT                     | 1         | 0.56%   |
| IPS                     | 1         | 0.56%   |
| Iiyama                  | 1         | 0.56%   |
| HUAWEI                  | 1         | 0.56%   |
| HannStar                | 1         | 0.56%   |
| Goldstar                | 1         | 0.56%   |
| Dell                    | 1         | 0.56%   |
| Chi Mei Optoelectronics | 1         | 0.56%   |
| Apple                   | 1         | 0.56%   |
| Ancor Communications    | 1         | 0.56%   |
| AGT                     | 1         | 0.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                  | 19        | 10.5%   |
| BOE LCD Monitor BOE09C5 1920x1080 341x192mm 15.4-inch                  | 9         | 4.97%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch       | 4         | 2.21%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                  | 4         | 2.21%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                  | 4         | 2.21%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch           | 3         | 1.66%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch            | 3         | 1.66%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 3         | 1.66%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch       | 3         | 1.66%   |
| BOE LCD Monitor BOE0936 1920x1080 344x194mm 15.5-inch                  | 3         | 1.66%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                  | 3         | 1.66%   |
| NLE Newline NLE0032 3840x2160 944x398mm 40.3-inch                      | 2         | 1.1%    |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch            | 2         | 1.1%    |
| LG Display LCD Monitor LGD02AC 1366x768 344x194mm 15.5-inch            | 2         | 1.1%    |
| BOE NV156FHM-N61 BOE07D0 1920x1080 344x193mm 15.5-inch                 | 2         | 1.1%    |
| BOE LCD Monitor BOE0A56 1920x1080 344x194mm 15.5-inch                  | 2         | 1.1%    |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                  | 2         | 1.1%    |
| BOE LCD Monitor BOE07CB 1920x1080 344x193mm 15.5-inch                  | 2         | 1.1%    |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                   | 2         | 1.1%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch         | 2         | 1.1%    |
| AU Optronics LCD Monitor AUO28ED 1920x1080 344x193mm 15.5-inch         | 2         | 1.1%    |
| ViewSonic VA2418-FHD VSCD739 1920x1080 527x296mm 23.8-inch             | 1         | 0.55%   |
| ViewSonic PJ VSC9B34 1920x1080                                         | 1         | 0.55%   |
| Toshiba LCD Monitor LCD58EB 1280x800 261x163mm 12.1-inch               | 1         | 0.55%   |
| TMX TL156VDXP01 TMX1560 1920x1080 344x194mm 15.5-inch                  | 1         | 0.55%   |
| TMX TL140VDXP04-0 TMX1398 1920x1080 309x174mm 14.0-inch                | 1         | 0.55%   |
| SKG 65 Monitor SKG6500 3840x2160 1430x800mm 64.5-inch                  | 1         | 0.55%   |
| Sharp LQ173M1JW03 SHP14DC 1920x1080 382x215mm 17.3-inch                | 1         | 0.55%   |
| Samsung Electronics S24C31x SAM7311 1920x1080 527x296mm 23.8-inch      | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch   | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x174mm 14.0-inch   | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 340x190mm 15.3-inch   | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch   | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC3151 1366x768 344x194mm 15.5-inch   | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC314F 1600x900 382x215mm 17.3-inch   | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch   | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SDC4851 1366x768 344x194mm 15.5-inch   | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SAM71B4 3840x2160 1110x620mm 50.1-inch | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1110x620mm 50.1-inch | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SAM090B 1920x1080 700x390mm 31.5-inch  | 1         | 0.55%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 119       | 70.83%  |
| 1366x768 (WXGA)    | 24        | 14.29%  |
| 3840x2160 (4K)     | 6         | 3.57%   |
| 1600x900 (HD+)     | 6         | 3.57%   |
| 1280x800 (WXGA)    | 3         | 1.79%   |
| 1680x1050 (WSXGA+) | 2         | 1.19%   |
| 3200x2000          | 1         | 0.6%    |
| 2560x1600          | 1         | 0.6%    |
| 2560x1440 (QHD)    | 1         | 0.6%    |
| 2560x1080          | 1         | 0.6%    |
| 2240x1400          | 1         | 0.6%    |
| 1920x1200 (WUXGA)  | 1         | 0.6%    |
| 1440x900 (WXGA+)   | 1         | 0.6%    |
| 1280x1024 (SXGA)   | 1         | 0.6%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 116       | 65.17%  |
| 14      | 10        | 5.62%   |
| 17      | 9         | 5.06%   |
| 21      | 8         | 4.49%   |
| 13      | 7         | 3.93%   |
| 24      | 4         | 2.25%   |
| 12      | 4         | 2.25%   |
| 16      | 3         | 1.69%   |
| 84      | 2         | 1.12%   |
| 40      | 2         | 1.12%   |
| 34      | 2         | 1.12%   |
| 27      | 2         | 1.12%   |
| 64      | 1         | 0.56%   |
| 55      | 1         | 0.56%   |
| 54      | 1         | 0.56%   |
| 23      | 1         | 0.56%   |
| 22      | 1         | 0.56%   |
| 20      | 1         | 0.56%   |
| 19      | 1         | 0.56%   |
| 11      | 1         | 0.56%   |
| Unknown | 1         | 0.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 133       | 74.72%  |
| 351-400     | 12        | 6.74%   |
| 401-500     | 10        | 5.62%   |
| 501-600     | 7         | 3.93%   |
| 201-300     | 6         | 3.37%   |
| 1001-1500   | 3         | 1.69%   |
| 701-800     | 2         | 1.12%   |
| 1501-2000   | 2         | 1.12%   |
| 901-1000    | 2         | 1.12%   |
| Unknown     | 1         | 0.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 148       | 90.8%   |
| 16/10 | 10        | 6.13%   |
| 21/9  | 4         | 2.45%   |
| 5/4   | 1         | 0.61%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 117       | 65.73%  |
| 81-90          | 16        | 8.99%   |
| 201-250        | 14        | 7.87%   |
| 121-130        | 8         | 4.49%   |
| More than 1000 | 5         | 2.81%   |
| 61-70          | 4         | 2.25%   |
| 351-500        | 2         | 1.12%   |
| 301-350        | 2         | 1.12%   |
| 151-200        | 2         | 1.12%   |
| 111-120        | 2         | 1.12%   |
| 501-1000       | 2         | 1.12%   |
| 71-80          | 1         | 0.56%   |
| 51-60          | 1         | 0.56%   |
| 131-140        | 1         | 0.56%   |
| Unknown        | 1         | 0.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 115       | 65.71%  |
| 101-120       | 37        | 21.14%  |
| 51-100        | 14        | 8%      |
| 161-240       | 5         | 2.86%   |
| 1-50          | 2         | 1.14%   |
| More than 240 | 1         | 0.57%   |
| Unknown       | 1         | 0.57%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 137       | 77.84%  |
| 0     | 19        | 10.8%   |
| 2     | 18        | 10.23%  |
| 3     | 2         | 1.14%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 118       | 42.45%  |
| Intel                 | 83        | 29.86%  |
| Qualcomm Atheros      | 19        | 6.83%   |
| Broadcom              | 16        | 5.76%   |
| Xiaomi                | 12        | 4.32%   |
| MediaTek              | 9         | 3.24%   |
| OPPO Electronics      | 3         | 1.08%   |
| Xilinx                | 2         | 0.72%   |
| TP-Link               | 2         | 0.72%   |
| Samsung Electronics   | 2         | 0.72%   |
| Ralink                | 2         | 0.72%   |
| Mercucys              | 2         | 0.72%   |
| Huawei Technologies   | 2         | 0.72%   |
| Ralink Technology     | 1         | 0.36%   |
| Qualcomm              | 1         | 0.36%   |
| OKB SAPR              | 1         | 0.36%   |
| Nvidia                | 1         | 0.36%   |
| Broadcom Limited      | 1         | 0.36%   |
| ASIX Electronics      | 1         | 0.36%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 60        | 18.29%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 29        | 8.84%   |
| Intel Wi-Fi 6 AX201                                                    | 16        | 4.88%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 15        | 4.57%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 12        | 3.66%   |
| Intel Wireless 7265                                                    | 12        | 3.66%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 10        | 3.05%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 10        | 3.05%   |
| Intel Ethernet Connection (6) I219-V                                   | 8         | 2.44%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 7         | 2.13%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 7         | 2.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 7         | 2.13%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 5         | 1.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 5         | 1.52%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                      | 4         | 1.22%   |
| Intel Wireless 3165                                                    | 4         | 1.22%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 4         | 1.22%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 4         | 1.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4         | 1.22%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                      | 4         | 1.22%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 3         | 0.91%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 3         | 0.91%   |
| OPPO OnePlus Nord 4                                                    | 3         | 0.91%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 3         | 0.91%   |
| Broadcom BCM43142 802.11b/g/n                                          | 3         | 0.91%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 3         | 0.91%   |
| Xilinx Network controller                                              | 2         | 0.61%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 0.61%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 2         | 0.61%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                             | 2         | 0.61%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 2         | 0.61%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 2         | 0.61%   |
| Mercucys 802.11n NIC                                                   | 2         | 0.61%   |
| Intel Wi-Fi 6 AX200                                                    | 2         | 0.61%   |
| Intel Ethernet Controller I225-V                                       | 2         | 0.61%   |
| Intel Ethernet Connection (16) I219-V                                  | 2         | 0.61%   |
| Intel Ethernet Connection (16) I219-LM                                 | 2         | 0.61%   |
| Intel Ethernet Connection (13) I219-V                                  | 2         | 0.61%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 2         | 0.61%   |
| Intel CNVi: Wi-Fi                                                      | 2         | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 73        | 42.2%   |
| Realtek Semiconductor | 55        | 31.79%  |
| Qualcomm Atheros      | 15        | 8.67%   |
| Broadcom              | 14        | 8.09%   |
| MediaTek              | 7         | 4.05%   |
| TP-Link               | 2         | 1.16%   |
| Ralink                | 2         | 1.16%   |
| Mercucys              | 2         | 1.16%   |
| Ralink Technology     | 1         | 0.58%   |
| Qualcomm              | 1         | 0.58%   |
| Broadcom Limited      | 1         | 0.58%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 29        | 16.57%  |
| Intel Wi-Fi 6 AX201                                            | 16        | 9.14%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 15        | 8.57%   |
| Intel Wireless 7265                                            | 12        | 6.86%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 7         | 4%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 7         | 4%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 2.86%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 4         | 2.29%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter              | 4         | 2.29%   |
| Intel Wireless 3165                                            | 4         | 2.29%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 4         | 2.29%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 4         | 2.29%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 4         | 2.29%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 3         | 1.71%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 3         | 1.71%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 3         | 1.71%   |
| Broadcom BCM43142 802.11b/g/n                                  | 3         | 1.71%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 1.71%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 2         | 1.14%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 2         | 1.14%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 2         | 1.14%   |
| Mercucys 802.11n NIC                                           | 2         | 1.14%   |
| Intel Wi-Fi 6 AX200                                            | 2         | 1.14%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 2         | 1.14%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 1.14%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 2         | 1.14%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 2         | 1.14%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 1         | 0.57%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 0.57%   |
| TP-Link 802.11n NIC                                            | 1         | 0.57%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.57%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1         | 0.57%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1         | 0.57%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter        | 1         | 0.57%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.57%   |
| Realtek 802.11n WLAN Adapter                                   | 1         | 0.57%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 0.57%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 1         | 0.57%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 0.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 0.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 86        | 58.11%  |
| Intel                 | 31        | 20.95%  |
| Xiaomi                | 12        | 8.11%   |
| Qualcomm Atheros      | 6         | 4.05%   |
| OPPO Electronics      | 3         | 2.03%   |
| Samsung Electronics   | 2         | 1.35%   |
| MediaTek              | 2         | 1.35%   |
| Broadcom              | 2         | 1.35%   |
| OKB SAPR              | 1         | 0.68%   |
| Nvidia                | 1         | 0.68%   |
| Huawei Technologies   | 1         | 0.68%   |
| ASIX Electronics      | 1         | 0.68%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 60        | 40%     |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 12        | 8%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 10        | 6.67%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 10        | 6.67%   |
| Intel Ethernet Connection (6) I219-V                                   | 8         | 5.33%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 7         | 4.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4         | 2.67%   |
| OPPO OnePlus Nord 4                                                    | 3         | 2%      |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 1.33%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 2         | 1.33%   |
| Intel Ethernet Controller I225-V                                       | 2         | 1.33%   |
| Intel Ethernet Connection (16) I219-V                                  | 2         | 1.33%   |
| Intel Ethernet Connection (16) I219-LM                                 | 2         | 1.33%   |
| Intel Ethernet Connection (13) I219-V                                  | 2         | 1.33%   |
| Intel CNVi: Wi-Fi                                                      | 2         | 1.33%   |
| Intel 82577LM Gigabit Network Connection                               | 2         | 1.33%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 1         | 0.67%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 0.67%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 0.67%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 1         | 0.67%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1         | 0.67%   |
| OKB SAPR Ethernet controller                                           | 1         | 0.67%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 0.67%   |
| MediaTek TANK2                                                         | 1         | 0.67%   |
| MediaTek Infinix SMART 5                                               | 1         | 0.67%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 0.67%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 0.67%   |
| Intel Ethernet Connection (7) I219-V                                   | 1         | 0.67%   |
| Intel Ethernet Connection (23) I219-LM                                 | 1         | 0.67%   |
| Intel 82579V Gigabit Network Connection                                | 1         | 0.67%   |
| Intel 82567LM Gigabit Network Connection                               | 1         | 0.67%   |
| Intel 82566MM Gigabit Network Connection                               | 1         | 0.67%   |
| Huawei FOA-LX9                                                         | 1         | 0.67%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                 | 1         | 0.67%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 1         | 0.67%   |
| ASIX AX88179 Gigabit Ethernet                                          | 1         | 0.67%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 165       | 54.82%  |
| Ethernet | 133       | 44.19%  |
| Unknown  | 2         | 0.66%   |
| Modem    | 1         | 0.33%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 99        | 56.9%   |
| Ethernet | 75        | 43.1%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 101       | 58.05%  |
| 1     | 69        | 39.66%  |
| 0     | 3         | 1.72%   |
| 3     | 1         | 0.57%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 161       | 90.96%  |
| Yes  | 16        | 9.04%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 64        | 43.54%  |
| Realtek Semiconductor           | 40        | 27.21%  |
| Broadcom                        | 9         | 6.12%   |
| Qualcomm Atheros Communications | 7         | 4.76%   |
| IMC Networks                    | 7         | 4.76%   |
| Realtek                         | 4         | 2.72%   |
| Foxconn / Hon Hai               | 4         | 2.72%   |
| Hewlett-Packard                 | 3         | 2.04%   |
| Ralink                          | 2         | 1.36%   |
| Lite-On Technology              | 2         | 1.36%   |
| Taiyo Yuden                     | 1         | 0.68%   |
| Opticis                         | 1         | 0.68%   |
| Foxconn International           | 1         | 0.68%   |
| ASUSTek Computer                | 1         | 0.68%   |
| Apple                           | 1         | 0.68%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                           | 31        | 21.09%  |
| Intel AX201 Bluetooth                             | 26        | 17.69%  |
| Intel Bluetooth wireless interface                | 18        | 12.24%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 13        | 8.84%   |
| Realtek  Bluetooth 4.2 Adapter                    | 6         | 4.08%   |
| Realtek Bluetooth Radio                           | 4         | 2.72%   |
| Qualcomm Atheros  Bluetooth Device                | 4         | 2.72%   |
| Intel AX211 Bluetooth                             | 4         | 2.72%   |
| IMC Networks Wireless_Device                      | 4         | 2.72%   |
| Realtek 802.11ac WLAN Adapter                     | 3         | 2.04%   |
| IMC Networks Bluetooth Radio                      | 3         | 2.04%   |
| HP Broadcom 2070 Bluetooth Combo                  | 3         | 2.04%   |
| Ralink RT3290 Bluetooth                           | 2         | 1.36%   |
| Qualcomm Atheros AR3011 Bluetooth                 | 2         | 1.36%   |
| Intel AX200 Bluetooth                             | 2         | 1.36%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter      | 2         | 1.36%   |
| Taiyo Yuden Bluetooth Device                      | 1         | 0.68%   |
| Qualcomm Atheros AR9462 Bluetooth                 | 1         | 0.68%   |
| Opticis Bluetooth Radio                           | 1         | 0.68%   |
| Lite-On Wireless_Device                           | 1         | 0.68%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 1         | 0.68%   |
| Intel AX210 Bluetooth                             | 1         | 0.68%   |
| Foxconn International BCM43142A0 Bluetooth module | 1         | 0.68%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth     | 1         | 0.68%   |
| Foxconn / Hon Hai Bluetooth Device                | 1         | 0.68%   |
| Broadcom HP Portable Valentine                    | 1         | 0.68%   |
| Broadcom HP Portable SoftSailing                  | 1         | 0.68%   |
| Broadcom HP Portable Bumble Bee                   | 1         | 0.68%   |
| Broadcom BCM43142A0 Bluetooth 4.0                 | 1         | 0.68%   |
| Broadcom BCM20702A0 Bluetooth                     | 1         | 0.68%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]        | 1         | 0.68%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR              | 1         | 0.68%   |
| Broadcom BCM2045B (BDC-2.1)                       | 1         | 0.68%   |
| Broadcom BCM2045 Bluetooth                        | 1         | 0.68%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter             | 1         | 0.68%   |
| Apple Bluetooth USB Host Controller               | 1         | 0.68%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 131       | 65.5%   |
| AMD                    | 44        | 22%     |
| Nvidia                 | 18        | 9%      |
| Zhaoxin                | 1         | 0.5%    |
| MosArt Semiconductor   | 1         | 0.5%    |
| Lenovo                 | 1         | 0.5%    |
| JMTek                  | 1         | 0.5%    |
| GN Netcom              | 1         | 0.5%    |
| Generalplus Technology | 1         | 0.5%    |
| C-Media Electronics    | 1         | 0.5%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                     | Notebooks | Percent |
|-------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                                | 34        | 14.05%  |
| Intel Cannon Point-LP High Definition Audio Controller                                    | 30        | 12.4%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                               | 21        | 8.68%   |
| AMD Renoir Radeon High Definition Audio Controller                                        | 21        | 8.68%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                   | 17        | 7.02%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                       | 10        | 4.13%   |
| Intel Comet Lake PCH-LP cAVS                                                              | 7         | 2.89%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                  | 7         | 2.89%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                     | 6         | 2.48%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                       | 6         | 2.48%   |
| Intel Haswell-ULT HD Audio Controller                                                     | 5         | 2.07%   |
| Intel 8 Series HD Audio Controller                                                        | 5         | 2.07%   |
| Intel Sunrise Point-LP HD Audio                                                           | 4         | 1.65%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                | 4         | 1.65%   |
| AMD SBx00 Azalia (Intel HDA)                                                              | 4         | 1.65%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                            | 3         | 1.24%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                         | 3         | 1.24%   |
| Intel Cannon Lake PCH cAVS                                                                | 3         | 1.24%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                    | 3         | 1.24%   |
| Nvidia High Definition Audio Controller                                                   | 2         | 0.83%   |
| Nvidia GP107GL High Definition Audio Controller                                           | 2         | 0.83%   |
| Nvidia GF108 High Definition Audio Controller                                             | 2         | 0.83%   |
| Nvidia GA106 High Definition Audio Controller                                             | 2         | 0.83%   |
| Intel Tiger Lake-H HD Audio Controller                                                    | 2         | 0.83%   |
| Intel Alder Lake-S HD Audio Controller                                                    | 2         | 0.83%   |
| Intel Alder Lake-N PCH High Definition Audio Controller                                   | 2         | 0.83%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                            | 2         | 0.83%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                            | 2         | 0.83%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                           | 2         | 0.83%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                          | 2         | 0.83%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                              | 2         | 0.83%   |
| Zhaoxin ZX-E High Definition Audio Controller                                             | 1         | 0.41%   |
| Zhaoxin ZX-100/KX-5000/KX-6000/KX-6000G/KH-40000/KX-7000 High Definition Audio Controller | 1         | 0.41%   |
| Nvidia TU104 HD Audio Controller                                                          | 1         | 0.41%   |
| Nvidia MCP79 High Definition Audio                                                        | 1         | 0.41%   |
| Nvidia GT216 HDMI Audio Controller                                                        | 1         | 0.41%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                             | 1         | 0.41%   |
| Nvidia GA107 High Definition Audio Controller                                             | 1         | 0.41%   |
| Nvidia AD107 High Definition Audio Controller                                             | 1         | 0.41%   |
| Nvidia AD106M High Definition Audio Controller                                            | 1         | 0.41%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 69        | 35.75%  |
| SK hynix                                | 33        | 17.1%   |
| Micron Technology                       | 23        | 11.92%  |
| Kingston                                | 10        | 5.18%   |
| Foxline                                 | 10        | 5.18%   |
| Crucial                                 | 9         | 4.66%   |
| Unknown                                 | 7         | 3.63%   |
| Ramaxel Technology                      | 4         | 2.07%   |
| Unknown (ABCD)                          | 3         | 1.55%   |
| Silicon Power Computer & Communications | 2         | 1.04%   |
| Patriot                                 | 2         | 1.04%   |
| Elpida                                  | 2         | 1.04%   |
| ChangXin Memory                         | 2         | 1.04%   |
| A-DATA Technology                       | 2         | 1.04%   |
| Unknown                                 | 2         | 1.04%   |
| Unknown (8C8F)                          | 1         | 0.52%   |
| Unknown (0x7FFF)                        | 1         | 0.52%   |
| Silicon Power                           | 1         | 0.52%   |
| SHARETRONIC                             | 1         | 0.52%   |
| Qumo                                    | 1         | 0.52%   |
| Netac                                   | 1         | 0.52%   |
| Nanya Technology                        | 1         | 0.52%   |
| King Tiger                              | 1         | 0.52%   |
| Kimtigo Semiconductor (HK) Limited      | 1         | 0.52%   |
| Hikvision                               | 1         | 0.52%   |
| DEPO Computers                          | 1         | 0.52%   |
| ASint Technology                        | 1         | 0.52%   |
| <Invalid>                               | 1         | 0.52%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 17        | 8.33%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 5         | 2.45%   |
| Samsung RAM M471A5244CB0-CWE 4096MB Row Of Chips DDR4 3200MT/s   | 4         | 1.96%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 1.96%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 4         | 1.96%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 3         | 1.47%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 3         | 1.47%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 4GB SODIMM LPDDR5 6400MT/s       | 3         | 1.47%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 3         | 1.47%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.47%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 1.47%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.47%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.47%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 3         | 1.47%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 3         | 1.47%   |
| Foxline RAM FL3200D4S22-8G 8GB SODIMM DDR4 3200MT/s              | 3         | 1.47%   |
| Foxline RAM FL2666D4S19-8G 8GB SODIMM DDR4 2667MT/s              | 3         | 1.47%   |
| Foxline RAM FL2400D4S17S-8G 8GB SODIMM DDR4 2400MT/s             | 3         | 1.47%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 0.98%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.98%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 0.98%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 2         | 0.98%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 0.98%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 0.98%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 2         | 0.98%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.98%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.98%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 0.98%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s | 2         | 0.98%   |
| Silicon Power & RAM Module 8GB SODIMM DDR4 3200MT/s              | 2         | 0.98%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 2         | 0.98%   |
| Micron RAM Module 8GB SODIMM DDR4 3200MT/s                       | 2         | 0.98%   |
| Micron RAM 8ATF2G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 2         | 0.98%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.98%   |
| Crucial RAM CT8G4SFS832A.M8FR 8GB SODIMM DDR4 3200MT/s           | 2         | 0.98%   |
| Crucial RAM CT8G4SFS832A.C8FN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.98%   |
| ChangXin Memory RAM DB4ABAM-MK 1GB Row Of Chips LPDDR4 3733MT/s  | 2         | 0.98%   |
| A-DATA RAM Module 8GB SODIMM DDR4 3200MT/s                       | 2         | 0.98%   |
| Unknown                                                          | 2         | 0.98%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                      | 1         | 0.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 113       | 67.26%  |
| DDR3    | 29        | 17.26%  |
| LPDDR4  | 9         | 5.36%   |
| LPDDR5  | 8         | 4.76%   |
| DDR5    | 3         | 1.79%   |
| DDR2    | 3         | 1.79%   |
| Unknown | 2         | 1.19%   |
| LPDDR3  | 1         | 0.6%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 145       | 82.39%  |
| Row Of Chips | 29        | 16.48%  |
| DIMM         | 1         | 0.57%   |
| Chip         | 1         | 0.57%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 93        | 50.54%  |
| 4096  | 48        | 26.09%  |
| 2048  | 18        | 9.78%   |
| 16384 | 17        | 9.24%   |
| 1024  | 7         | 3.8%    |
| 32768 | 1         | 0.54%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 66        | 37.29%  |
| 2667  | 41        | 23.16%  |
| 1600  | 17        | 9.6%    |
| 2400  | 11        | 6.21%   |
| 6400  | 6         | 3.39%   |
| 1334  | 6         | 3.39%   |
| 1333  | 4         | 2.26%   |
| 4267  | 3         | 1.69%   |
| 3266  | 3         | 1.69%   |
| 1067  | 3         | 1.69%   |
| 667   | 3         | 1.69%   |
| 4800  | 2         | 1.13%   |
| 3733  | 2         | 1.13%   |
| 2133  | 2         | 1.13%   |
| 7500  | 1         | 0.56%   |
| 5600  | 1         | 0.56%   |
| 5500  | 1         | 0.56%   |
| 2666  | 1         | 0.56%   |
| 1866  | 1         | 0.56%   |
| 1066  | 1         | 0.56%   |
| 975   | 1         | 0.56%   |
| 533   | 1         | 0.56%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Kyocera | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Notebooks | Percent |
|------------------------|-----------|---------|
| Kyocera ECOSYS M2135dn | 1         | 100%    |

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
| Chicony Electronics                    | 33        | 19.88%  |
| Syntek                                 | 22        | 13.25%  |
| IMC Networks                           | 22        | 13.25%  |
| Quanta                                 | 14        | 8.43%   |
| Bison Electronics                      | 13        | 7.83%   |
| Microdia                               | 8         | 4.82%   |
| Sunplus Innovation Technology          | 7         | 4.22%   |
| Luxvisions Innotech Limited            | 6         | 3.61%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 3.61%   |
| Realtek Semiconductor                  | 5         | 3.01%   |
| Acer                                   | 5         | 3.01%   |
| SunplusIT                              | 4         | 2.41%   |
| Sonix Technology                       | 4         | 2.41%   |
| Z-Star Microelectronics                | 2         | 1.2%    |
| USB Camera CS                          | 2         | 1.2%    |
| Suyin                                  | 2         | 1.2%    |
| Apple                                  | 2         | 1.2%    |
| Primax Electronics                     | 1         | 0.6%    |
| JMicron Technology                     | 1         | 0.6%    |
| Importek                               | 1         | 0.6%    |
| icSpring                               | 1         | 0.6%    |
| GEMBIRD                                | 1         | 0.6%    |
| BTF-240516-XH                          | 1         | 0.6%    |
| ALi                                    | 1         | 0.6%    |
| Alcor Micro                            | 1         | 0.6%    |
| Unknown                                | 1         | 0.6%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                            | 21        | 12.65%  |
| Chicony USB2.0 FHD UVC WebCam                       | 11        | 6.63%   |
| IMC Networks Integrated Camera                      | 7         | 4.22%   |
| Chicony Integrated Camera                           | 6         | 3.61%   |
| IMC Networks HD Camera                              | 5         | 3.01%   |
| IMC Networks ov9734_azurewave_camera                | 4         | 2.41%   |
| Sunplus DICOTA 4K                                   | 3         | 1.81%   |
| Quanta HP Webcam                                    | 3         | 1.81%   |
| Microdia Webcam Vitade AF                           | 3         | 1.81%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 3         | 1.81%   |
| Chicony ACER HD User Facing                         | 3         | 1.81%   |
| Bison Lenovo Integrated Webcam                      | 3         | 1.81%   |
| Bison Integrated Camera                             | 3         | 1.81%   |
| Acer Integrated Camera                              | 3         | 1.81%   |
| USB Camera CS USB Camera CS                         | 2         | 1.2%    |
| SunplusIT USB Camera                                | 2         | 1.2%    |
| Sonix USB 2.0 Camera                                | 2         | 1.2%    |
| Realtek Integrated_Webcam_HD                        | 2         | 1.2%    |
| Quanta ov9734_techfront_camera                      | 2         | 1.2%    |
| Quanta HP TrueVision HD Camera                      | 2         | 1.2%    |
| Microdia USB 2.0 Camera                             | 2         | 1.2%    |
| Luxvisions Innotech Limited Integrated Camera       | 2         | 1.2%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 2         | 1.2%    |
| Luxvisions Innotech Limited HP HD Camera            | 2         | 1.2%    |
| Chicony HP Webcam [2 MP Macro]                      | 2         | 1.2%    |
| Chicony HD User Facing                              | 2         | 1.2%    |
| Chicony Chicony USB2.0 Camera                       | 2         | 1.2%    |
| Cheng Uei Precision Industry (Foxlink) Webcam       | 2         | 1.2%    |
| Bison HD Webcam                                     | 2         | 1.2%    |
| Bison BisonCam,NB Pro                               | 2         | 1.2%    |
| Acer BisonCam,NB Pro                                | 2         | 1.2%    |
| Z-Star Venus USB2.0 Camera                          | 1         | 0.6%    |
| Z-Star Sirius USB2.0 Camera                         | 1         | 0.6%    |
| Syntek Lenovo EasyCamera                            | 1         | 0.6%    |
| Suyin HP Truevision HD                              | 1         | 0.6%    |
| Suyin Acer CrystalEye Webcam                        | 1         | 0.6%    |
| SunplusIT XiaoMi USB 2.0 Webcam                     | 1         | 0.6%    |
| SunplusIT HD Webcam                                 | 1         | 0.6%    |
| Sunplus Lenovo EasyCamera                           | 1         | 0.6%    |
| Sunplus Integrated_Webcam_HD                        | 1         | 0.6%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 13        | 54.17%  |
| Validity Sensors           | 5         | 20.83%  |
| Synaptics                  | 4         | 16.67%  |
| Elan Microelectronics      | 1         | 4.17%   |
| AuthenTec                  | 1         | 4.17%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                       | 13        | 54.17%  |
| Validity Sensors VFS495 Fingerprint Reader                | 2         | 8.33%   |
| Validity Sensors VFS451 Fingerprint Reader                | 2         | 8.33%   |
| Synaptics UWP WBDI Device                                 | 2         | 8.33%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor         | 1         | 4.17%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 4.17%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 4.17%   |
| Elan ELAN:Fingerprint                                     | 1         | 4.17%   |
| AuthenTec AES2550 Fingerprint Sensor                      | 1         | 4.17%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Upek   | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 109       | 61.58%  |
| 1     | 51        | 28.81%  |
| 2     | 15        | 8.47%   |
| 4     | 1         | 0.56%   |
| 3     | 1         | 0.56%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 24        | 28.57%  |
| Fingerprint reader    | 24        | 28.57%  |
| Net/wireless          | 20        | 23.81%  |
| Bluetooth             | 5         | 5.95%   |
| Multimedia controller | 3         | 3.57%   |
| Network               | 2         | 2.38%   |
| Camera                | 2         | 2.38%   |
| Storage               | 1         | 1.19%   |
| Sound                 | 1         | 1.19%   |
| Net/ethernet          | 1         | 1.19%   |
| Chipcard              | 1         | 1.19%   |

