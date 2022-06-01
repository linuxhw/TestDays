Linux in Serbia - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Serbia.

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

Total: 418

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | ProBook 470 G1              | [ef73457d51](https://linux-hardware.org/?probe=ef73457d51) | May 31, 2022 |
| Lenovo        | ThinkPad T490 20N2000LMZ    | [9ebff03a43](https://linux-hardware.org/?probe=9ebff03a43) | May 26, 2022 |
| Lenovo        | ThinkPad T490 20N2000LMZ    | [cc80808aea](https://linux-hardware.org/?probe=cc80808aea) | May 26, 2022 |
| Lenovo        | ThinkPad T61 6463Y3W        | [065aa2538b](https://linux-hardware.org/?probe=065aa2538b) | May 18, 2022 |
| HP            | Laptop 15-db1xxx            | [f6262ce7f2](https://linux-hardware.org/?probe=f6262ce7f2) | May 12, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [e90b6752ba](https://linux-hardware.org/?probe=e90b6752ba) | May 12, 2022 |
| HP            | ProBook 450 G2              | [2c2a15aab2](https://linux-hardware.org/?probe=2c2a15aab2) | May 12, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [d18df271fd](https://linux-hardware.org/?probe=d18df271fd) | May 09, 2022 |
| Medion        | X781X/X782X                 | [fbe630f91c](https://linux-hardware.org/?probe=fbe630f91c) | May 07, 2022 |
| Lenovo        | IdeaPad Z370                | [be37f3c962](https://linux-hardware.org/?probe=be37f3c962) | May 04, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [633bddd44b](https://linux-hardware.org/?probe=633bddd44b) | Apr 30, 2022 |
| Acer          | Nitro AN517-51              | [81d7fd8d2e](https://linux-hardware.org/?probe=81d7fd8d2e) | Apr 30, 2022 |
| Dell          | Latitude 7280               | [e64ba65609](https://linux-hardware.org/?probe=e64ba65609) | Apr 22, 2022 |
| Lenovo        | Unknown                     | [6e1760aed0](https://linux-hardware.org/?probe=6e1760aed0) | Apr 17, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | [b888c78ed6](https://linux-hardware.org/?probe=b888c78ed6) | Apr 12, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | [45dad76f04](https://linux-hardware.org/?probe=45dad76f04) | Apr 12, 2022 |
| HP            | Notebook                    | [4ffd4d11a5](https://linux-hardware.org/?probe=4ffd4d11a5) | Apr 09, 2022 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [0dbb9e7eb0](https://linux-hardware.org/?probe=0dbb9e7eb0) | Apr 09, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [950a436db3](https://linux-hardware.org/?probe=950a436db3) | Apr 06, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [906de71a65](https://linux-hardware.org/?probe=906de71a65) | Apr 02, 2022 |
| Lenovo        | V330-15IKB 81AX             | [8a881c75f4](https://linux-hardware.org/?probe=8a881c75f4) | Mar 29, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [5eb56f360e](https://linux-hardware.org/?probe=5eb56f360e) | Mar 29, 2022 |
| Fujitsu       | LIFEBOOK AH531              | [f92c8b77dc](https://linux-hardware.org/?probe=f92c8b77dc) | Mar 25, 2022 |
| Fujitsu Si... | AMILO Li3710                | [ab84e23108](https://linux-hardware.org/?probe=ab84e23108) | Mar 24, 2022 |
| Dell          | Inspiron 3542               | [6a8c31fa33](https://linux-hardware.org/?probe=6a8c31fa33) | Mar 21, 2022 |
| Apple         | MacBookPro8,1               | [f55145f34a](https://linux-hardware.org/?probe=f55145f34a) | Mar 16, 2022 |
| Toshiba       | Satellite C870-17H          | [0169bf05d7](https://linux-hardware.org/?probe=0169bf05d7) | Mar 10, 2022 |
| Fujitsu Si... | AMILO Li3710                | [7a4a682f45](https://linux-hardware.org/?probe=7a4a682f45) | Mar 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [2c44722344](https://linux-hardware.org/?probe=2c44722344) | Mar 03, 2022 |
| ASUSTek       | E200HA                      | [69ec87e43a](https://linux-hardware.org/?probe=69ec87e43a) | Mar 02, 2022 |
| HP            | Laptop 15s-fq0xxx           | [9acf95b26b](https://linux-hardware.org/?probe=9acf95b26b) | Feb 28, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [03a49e64cf](https://linux-hardware.org/?probe=03a49e64cf) | Feb 28, 2022 |
| Gigabyte      | AERO 17 KC                  | [08b488b969](https://linux-hardware.org/?probe=08b488b969) | Feb 27, 2022 |
| Dell          | Latitude 7490               | [003b6b4a95](https://linux-hardware.org/?probe=003b6b4a95) | Feb 21, 2022 |
| Dell          | Inspiron 3581               | [0ae0e53b53](https://linux-hardware.org/?probe=0ae0e53b53) | Feb 20, 2022 |
| HP            | Notebook                    | [a1f9f76ed0](https://linux-hardware.org/?probe=a1f9f76ed0) | Feb 19, 2022 |
| Toshiba       | Satellite C55-A             | [19133950aa](https://linux-hardware.org/?probe=19133950aa) | Feb 15, 2022 |
| ASUSTek       | X55A                        | [c6b17158ac](https://linux-hardware.org/?probe=c6b17158ac) | Feb 14, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X1S... | [4f80537faf](https://linux-hardware.org/?probe=4f80537faf) | Feb 06, 2022 |
| Toshiba       | Satellite C55-C             | [379d3b37b1](https://linux-hardware.org/?probe=379d3b37b1) | Feb 05, 2022 |
| BenQ          | Joybook Lite U121           | [28f254dd8d](https://linux-hardware.org/?probe=28f254dd8d) | Feb 02, 2022 |
| Dell          | Vostro 3500                 | [729abacd12](https://linux-hardware.org/?probe=729abacd12) | Feb 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [5e9f8a1c0d](https://linux-hardware.org/?probe=5e9f8a1c0d) | Jan 29, 2022 |
| Dell          | Latitude E6510              | [efc619cc61](https://linux-hardware.org/?probe=efc619cc61) | Jan 28, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [37ec4f5294](https://linux-hardware.org/?probe=37ec4f5294) | Jan 25, 2022 |
| ASUSTek       | E200HA                      | [2c53d21746](https://linux-hardware.org/?probe=2c53d21746) | Jan 22, 2022 |
| ASUSTek       | E200HA                      | [02be439ac8](https://linux-hardware.org/?probe=02be439ac8) | Jan 22, 2022 |
| HP            | EliteBook 1050 G1           | [1bb5cb826f](https://linux-hardware.org/?probe=1bb5cb826f) | Jan 19, 2022 |
| TWC           | Unknown                     | [85a8fd2cf1](https://linux-hardware.org/?probe=85a8fd2cf1) | Jan 18, 2022 |
| TWC           | Unknown                     | [d4cc69cea7](https://linux-hardware.org/?probe=d4cc69cea7) | Jan 16, 2022 |
| Fujitsu       | LIFEBOOK A3510              | [b673072fbb](https://linux-hardware.org/?probe=b673072fbb) | Jan 11, 2022 |
| Dell          | Vostro 5402                 | [f586d10ee6](https://linux-hardware.org/?probe=f586d10ee6) | Jan 05, 2022 |
| MSI           | GT70 2PC                    | [61a5023d6a](https://linux-hardware.org/?probe=61a5023d6a) | Jan 03, 2022 |
| Dell          | Latitude 7490               | [2d6469644a](https://linux-hardware.org/?probe=2d6469644a) | Jan 02, 2022 |
| Lenovo        | ThinkPad T490 20N3S6VU00    | [afb7fa66f5](https://linux-hardware.org/?probe=afb7fa66f5) | Dec 30, 2021 |
| Dell          | Latitude 7490               | [4e350048ed](https://linux-hardware.org/?probe=4e350048ed) | Dec 27, 2021 |
| Fujitsu Si... | AMILO Li3710                | [183a47572f](https://linux-hardware.org/?probe=183a47572f) | Dec 27, 2021 |
| ASUSTek       | X580VD                      | [fe350107e3](https://linux-hardware.org/?probe=fe350107e3) | Dec 25, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X540... | [74591e1700](https://linux-hardware.org/?probe=74591e1700) | Dec 12, 2021 |
| Toshiba       | Satellite Pro L650          | [fd40a9d639](https://linux-hardware.org/?probe=fd40a9d639) | Dec 07, 2021 |
| HP            | Laptop 15s-eq1xxx           | [a61a3df5f9](https://linux-hardware.org/?probe=a61a3df5f9) | Dec 04, 2021 |
| Dell          | Vostro 3500                 | [3df309c91c](https://linux-hardware.org/?probe=3df309c91c) | Dec 03, 2021 |
| Fujitsu Si... | AMILO Li3910                | [6f355c1c73](https://linux-hardware.org/?probe=6f355c1c73) | Dec 01, 2021 |
| HP            | Laptop 14-ck0xxx            | [60a074698a](https://linux-hardware.org/?probe=60a074698a) | Dec 01, 2021 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [440d34a6b0](https://linux-hardware.org/?probe=440d34a6b0) | Nov 28, 2021 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [bb7b625409](https://linux-hardware.org/?probe=bb7b625409) | Nov 28, 2021 |
| ASUSTek       | N53SN                       | [67d66feb3e](https://linux-hardware.org/?probe=67d66feb3e) | Nov 20, 2021 |
| Acer          | Aspire ES1-533              | [14a4c57e27](https://linux-hardware.org/?probe=14a4c57e27) | Nov 05, 2021 |
| Lenovo        | G500 20236                  | [7708d61566](https://linux-hardware.org/?probe=7708d61566) | Nov 05, 2021 |
| eMachines     | eME440                      | [1427ebffb0](https://linux-hardware.org/?probe=1427ebffb0) | Oct 29, 2021 |
| Lenovo        | ThinkPad T490 20N3S6VU00    | [f8024b89d4](https://linux-hardware.org/?probe=f8024b89d4) | Oct 28, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [d180cf6efc](https://linux-hardware.org/?probe=d180cf6efc) | Oct 23, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X1S... | [cb8bcc4d2d](https://linux-hardware.org/?probe=cb8bcc4d2d) | Oct 22, 2021 |
| Lenovo        | ThinkPad T490 20N3S6VU00    | [a99866abc1](https://linux-hardware.org/?probe=a99866abc1) | Oct 21, 2021 |
| HP            | EliteBook 840 G3            | [650c91f4db](https://linux-hardware.org/?probe=650c91f4db) | Oct 18, 2021 |
| HP            | EliteBook 840 G3            | [5e28e542c2](https://linux-hardware.org/?probe=5e28e542c2) | Oct 17, 2021 |
| Dell          | Inspiron 3520               | [7eafd054fc](https://linux-hardware.org/?probe=7eafd054fc) | Oct 17, 2021 |
| HP            | Laptop 15s-eq2xxx           | [2e7ac4731f](https://linux-hardware.org/?probe=2e7ac4731f) | Oct 16, 2021 |
| Lenovo        | G555 0873                   | [a38f52851a](https://linux-hardware.org/?probe=a38f52851a) | Oct 05, 2021 |
| ASUSTek       | 1005PE                      | [bd2044749b](https://linux-hardware.org/?probe=bd2044749b) | Sep 22, 2021 |
| Acer          | Aspire V3-571G              | [b9fcdffa50](https://linux-hardware.org/?probe=b9fcdffa50) | Sep 22, 2021 |
| ASUSTek       | 1005PE                      | [02ccb36302](https://linux-hardware.org/?probe=02ccb36302) | Sep 21, 2021 |
| ASUSTek       | 1005PE                      | [081e791398](https://linux-hardware.org/?probe=081e791398) | Sep 19, 2021 |
| Toshiba       | Satellite C55-B             | [59a0efda89](https://linux-hardware.org/?probe=59a0efda89) | Sep 18, 2021 |
| ASUSTek       | 1005PE                      | [a3adf0356c](https://linux-hardware.org/?probe=a3adf0356c) | Sep 18, 2021 |
| Acer          | Aspire V3-571G              | [cedbbde363](https://linux-hardware.org/?probe=cedbbde363) | Sep 13, 2021 |
| Lenovo        | G500 20236                  | [f77883b614](https://linux-hardware.org/?probe=f77883b614) | Sep 07, 2021 |
| HP            | ProBook 4730s               | [36834479ab](https://linux-hardware.org/?probe=36834479ab) | Sep 03, 2021 |
| Apple         | MacBookPro8,1               | [da332ba09e](https://linux-hardware.org/?probe=da332ba09e) | Sep 01, 2021 |
| Dell          | Inspiron 3537               | [cad80329d8](https://linux-hardware.org/?probe=cad80329d8) | Aug 31, 2021 |
| Lenovo        | G500 20236                  | [60f43f8815](https://linux-hardware.org/?probe=60f43f8815) | Aug 29, 2021 |
| Dell          | Inspiron 5593               | [ebac51e403](https://linux-hardware.org/?probe=ebac51e403) | Aug 28, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [62c96ffa5b](https://linux-hardware.org/?probe=62c96ffa5b) | Aug 25, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [516b9ff2ed](https://linux-hardware.org/?probe=516b9ff2ed) | Aug 25, 2021 |
| Dell          | Inspiron 7520               | [056e1c0825](https://linux-hardware.org/?probe=056e1c0825) | Aug 21, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [79051f2400](https://linux-hardware.org/?probe=79051f2400) | Aug 19, 2021 |
| HP            | EliteBook 840 G5            | [4c196e1abd](https://linux-hardware.org/?probe=4c196e1abd) | Aug 18, 2021 |
| HP            | G62                         | [b6eeeba9d1](https://linux-hardware.org/?probe=b6eeeba9d1) | Aug 15, 2021 |
| HP            | G62                         | [4adea9bed4](https://linux-hardware.org/?probe=4adea9bed4) | Aug 14, 2021 |
| HP            | Pavilion g6                 | [df95184640](https://linux-hardware.org/?probe=df95184640) | Aug 02, 2021 |
| HP            | Pavilion g6                 | [0e0aaaac98](https://linux-hardware.org/?probe=0e0aaaac98) | Aug 02, 2021 |
| Toshiba       | Satellite Pro L650          | [10e8624257](https://linux-hardware.org/?probe=10e8624257) | Jul 27, 2021 |
| Toshiba       | Satellite C55-B             | [c703c827c6](https://linux-hardware.org/?probe=c703c827c6) | Jul 21, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b44e9be41b](https://linux-hardware.org/?probe=b44e9be41b) | Jul 19, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [56faa89619](https://linux-hardware.org/?probe=56faa89619) | Jul 16, 2021 |
| Lenovo        | V330-15IKB 81AX             | [70128f07ea](https://linux-hardware.org/?probe=70128f07ea) | Jul 13, 2021 |
| HP            | Compaq nx7400 (RU429EA#A... | [ce0542775b](https://linux-hardware.org/?probe=ce0542775b) | Jun 22, 2021 |
| Lenovo        | ThinkPad X201 Tablet 298... | [d04705eaef](https://linux-hardware.org/?probe=d04705eaef) | Jun 20, 2021 |
| ASUSTek       | G551JK                      | [aace05a48f](https://linux-hardware.org/?probe=aace05a48f) | Jun 17, 2021 |
| ASUSTek       | G551JK                      | [2947ae8fc2](https://linux-hardware.org/?probe=2947ae8fc2) | Jun 17, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [80b26a6c37](https://linux-hardware.org/?probe=80b26a6c37) | Jun 16, 2021 |
| Dell          | Inspiron 15-3567            | [8487e42c1e](https://linux-hardware.org/?probe=8487e42c1e) | Jun 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [18fd922adc](https://linux-hardware.org/?probe=18fd922adc) | Jun 10, 2021 |
| Dell          | Latitude 5520               | [45b3e7c2af](https://linux-hardware.org/?probe=45b3e7c2af) | Jun 06, 2021 |
| Dell          | Vostro 5402                 | [ec4c7c0192](https://linux-hardware.org/?probe=ec4c7c0192) | Jun 04, 2021 |
| MSI           | CR500                       | [76d2d77034](https://linux-hardware.org/?probe=76d2d77034) | Jun 03, 2021 |
| MSI           | CR500                       | [93f6fd0ae4](https://linux-hardware.org/?probe=93f6fd0ae4) | Jun 02, 2021 |
| MSI           | CR500                       | [b1d00d1444](https://linux-hardware.org/?probe=b1d00d1444) | May 30, 2021 |
| HP            | Notebook                    | [f60121b761](https://linux-hardware.org/?probe=f60121b761) | May 30, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [f794ea73e4](https://linux-hardware.org/?probe=f794ea73e4) | May 28, 2021 |
| Apple         | MacBookPro1,1               | [cc14c7fa2e](https://linux-hardware.org/?probe=cc14c7fa2e) | May 16, 2021 |
| HP            | ProBook 4530s               | [3d5a77511e](https://linux-hardware.org/?probe=3d5a77511e) | May 12, 2021 |
| Dell          | Vostro 5402                 | [03aa94f52f](https://linux-hardware.org/?probe=03aa94f52f) | May 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [b57920ccda](https://linux-hardware.org/?probe=b57920ccda) | May 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [19bf5a98df](https://linux-hardware.org/?probe=19bf5a98df) | May 10, 2021 |
| ASUSTek       | K53E                        | [314e6bbbd2](https://linux-hardware.org/?probe=314e6bbbd2) | May 04, 2021 |
| ASUSTek       | K53E                        | [9a34eba18a](https://linux-hardware.org/?probe=9a34eba18a) | May 03, 2021 |
| Fujitsu Si... | AMILO Pi 2512               | [bc0294a996](https://linux-hardware.org/?probe=bc0294a996) | May 03, 2021 |
| HP            | EliteBook 2540p             | [506fb4d003](https://linux-hardware.org/?probe=506fb4d003) | May 02, 2021 |
| Lenovo        | ThinkPad T440s 20ARS3B00... | [fa546522c1](https://linux-hardware.org/?probe=fa546522c1) | May 02, 2021 |
| Medion        | P6812                       | [a45bd7fc22](https://linux-hardware.org/?probe=a45bd7fc22) | Apr 19, 2021 |
| Acer          | Aspire A315-31              | [2b821447d2](https://linux-hardware.org/?probe=2b821447d2) | Apr 14, 2021 |
| Acer          | Aspire A315-31              | [e7a7c4b64f](https://linux-hardware.org/?probe=e7a7c4b64f) | Apr 14, 2021 |
| Acer          | Aspire A315-23              | [c7a0c1bf24](https://linux-hardware.org/?probe=c7a0c1bf24) | Apr 13, 2021 |
| HP            | Pavilion 15                 | [88ca55e5af](https://linux-hardware.org/?probe=88ca55e5af) | Apr 08, 2021 |
| Acer          | Aspire A515-51G             | [97f260c7d5](https://linux-hardware.org/?probe=97f260c7d5) | Mar 31, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [084a69a05a](https://linux-hardware.org/?probe=084a69a05a) | Mar 30, 2021 |
| Dell          | G5 5587                     | [862386a9b4](https://linux-hardware.org/?probe=862386a9b4) | Mar 27, 2021 |
| HP            | Laptop 15-db1xxx            | [59fb434d97](https://linux-hardware.org/?probe=59fb434d97) | Mar 21, 2021 |
| HP            | Laptop 15-db1xxx            | [aab4f11f05](https://linux-hardware.org/?probe=aab4f11f05) | Mar 21, 2021 |
| Dell          | Inspiron 3542               | [517406f8b6](https://linux-hardware.org/?probe=517406f8b6) | Mar 21, 2021 |
| HP            | ZBook 15 G3                 | [4ab4d49018](https://linux-hardware.org/?probe=4ab4d49018) | Mar 17, 2021 |
| HP            | Laptop 15-da1xxx            | [ed4ddd6238](https://linux-hardware.org/?probe=ed4ddd6238) | Mar 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [640a0a3857](https://linux-hardware.org/?probe=640a0a3857) | Mar 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [66de852009](https://linux-hardware.org/?probe=66de852009) | Mar 11, 2021 |
| Acer          | Aspire 5742G                | [659f9d690c](https://linux-hardware.org/?probe=659f9d690c) | Mar 10, 2021 |
| Dell          | Latitude E6320              | [a69653a323](https://linux-hardware.org/?probe=a69653a323) | Mar 08, 2021 |
| Acer          | Aspire 5735                 | [cde827bd2e](https://linux-hardware.org/?probe=cde827bd2e) | Mar 07, 2021 |
| Acer          | Aspire 5735                 | [9730b9273d](https://linux-hardware.org/?probe=9730b9273d) | Mar 07, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [7d5313fdad](https://linux-hardware.org/?probe=7d5313fdad) | Mar 06, 2021 |
| Toshiba       | Satellite L20               | [875478a51a](https://linux-hardware.org/?probe=875478a51a) | Mar 06, 2021 |
| HP            | ProBook 650 G1              | [e21aaf16e3](https://linux-hardware.org/?probe=e21aaf16e3) | Mar 03, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | [a94321f4aa](https://linux-hardware.org/?probe=a94321f4aa) | Feb 27, 2021 |
| Dell          | Inspiron 7520               | [4611155200](https://linux-hardware.org/?probe=4611155200) | Feb 20, 2021 |
| HP            | ProBook 470 G3              | [12ef122267](https://linux-hardware.org/?probe=12ef122267) | Feb 19, 2021 |
| Dell          | Inspiron 3542               | [d77d8a8749](https://linux-hardware.org/?probe=d77d8a8749) | Feb 18, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [5843b21ecd](https://linux-hardware.org/?probe=5843b21ecd) | Feb 14, 2021 |
| HP            | ProBook 650 G1              | [2dcb1a408a](https://linux-hardware.org/?probe=2dcb1a408a) | Feb 13, 2021 |
| HP            | ProBook 650 G1              | [1d63d4f78d](https://linux-hardware.org/?probe=1d63d4f78d) | Feb 10, 2021 |
| Dell          | Latitude E5470              | [ac140ada48](https://linux-hardware.org/?probe=ac140ada48) | Feb 09, 2021 |
| Lenovo        | IdeaPad Y570 20091          | [e80a31db39](https://linux-hardware.org/?probe=e80a31db39) | Feb 03, 2021 |
| Dell          | Latitude E5470              | [72db68119a](https://linux-hardware.org/?probe=72db68119a) | Jan 27, 2021 |
| Dell          | Latitude E6430              | [b7f8906f0f](https://linux-hardware.org/?probe=b7f8906f0f) | Jan 27, 2021 |
| Lenovo        | IdeaPad Y570 20091          | [68fdde328b](https://linux-hardware.org/?probe=68fdde328b) | Jan 27, 2021 |
| HP            | EliteBook 8560p             | [875db98e08](https://linux-hardware.org/?probe=875db98e08) | Jan 23, 2021 |
| Acer          | Aspire 5736Z                | [6bb8df4de2](https://linux-hardware.org/?probe=6bb8df4de2) | Jan 21, 2021 |
| Lenovo        | Legion Y7000 2019 PG0 81... | [9f77ea6e17](https://linux-hardware.org/?probe=9f77ea6e17) | Jan 14, 2021 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [ab2decc440](https://linux-hardware.org/?probe=ab2decc440) | Jan 12, 2021 |
| Lenovo        | ThinkPad R400 2786W1L       | [5335da910d](https://linux-hardware.org/?probe=5335da910d) | Jan 10, 2021 |
| Lenovo        | ThinkPad R400 2786W1L       | [c7fbffcc09](https://linux-hardware.org/?probe=c7fbffcc09) | Jan 10, 2021 |
| Packard Be... | EasyNote TS11HR             | [ab603b2fe8](https://linux-hardware.org/?probe=ab603b2fe8) | Jan 06, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [7e0f5ef3ce](https://linux-hardware.org/?probe=7e0f5ef3ce) | Jan 04, 2021 |
| Toshiba       | Satellite C650              | [da33e577bf](https://linux-hardware.org/?probe=da33e577bf) | Jan 02, 2021 |
| Packard Be... | EasyNote TS11HR             | [343249d2da](https://linux-hardware.org/?probe=343249d2da) | Jan 02, 2021 |
| Toshiba       | Satellite C650              | [3ccf619144](https://linux-hardware.org/?probe=3ccf619144) | Dec 31, 2020 |
| ASUSTek       | X541NA                      | [ce08535027](https://linux-hardware.org/?probe=ce08535027) | Dec 25, 2020 |
| ASUSTek       | X541NA                      | [a026c30d04](https://linux-hardware.org/?probe=a026c30d04) | Dec 25, 2020 |
| HP            | Laptop 15-db0xxx            | [87ecbeb3f9](https://linux-hardware.org/?probe=87ecbeb3f9) | Dec 22, 2020 |
| Lenovo        | V330-15IKB 81AX             | [7bbfaa08a2](https://linux-hardware.org/?probe=7bbfaa08a2) | Dec 19, 2020 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [a3f26b77de](https://linux-hardware.org/?probe=a3f26b77de) | Dec 17, 2020 |
| Acer          | Aspire A315-31              | [3d19374493](https://linux-hardware.org/?probe=3d19374493) | Dec 17, 2020 |
| Dell          | XPS 13 9380                 | [1eae71a2dd](https://linux-hardware.org/?probe=1eae71a2dd) | Dec 14, 2020 |
| Acer          | Aspire A315-31              | [630a5fce15](https://linux-hardware.org/?probe=630a5fce15) | Dec 11, 2020 |
| Acer          | Aspire A715-75G             | [9c6b3be687](https://linux-hardware.org/?probe=9c6b3be687) | Dec 10, 2020 |
| Acer          | Aspire A717-71G             | [f355a859fe](https://linux-hardware.org/?probe=f355a859fe) | Dec 05, 2020 |
| Acer          | Aspire A717-71G             | [e0144299e5](https://linux-hardware.org/?probe=e0144299e5) | Dec 05, 2020 |
| Acer          | Aspire A715-75G             | [4d6f15896a](https://linux-hardware.org/?probe=4d6f15896a) | Dec 01, 2020 |
| Acer          | Aspire A715-75G             | [cea1efd2f4](https://linux-hardware.org/?probe=cea1efd2f4) | Dec 01, 2020 |
| Acer          | Aspire ES1-533              | [e20dc3c4e4](https://linux-hardware.org/?probe=e20dc3c4e4) | Nov 26, 2020 |
| Acer          | Aspire ES1-533              | [1ff481eb22](https://linux-hardware.org/?probe=1ff481eb22) | Nov 26, 2020 |
| Lenovo        | V15-ADA 82C7                | [c25d3746ee](https://linux-hardware.org/?probe=c25d3746ee) | Nov 24, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [b59cef94de](https://linux-hardware.org/?probe=b59cef94de) | Nov 22, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [cb540754ed](https://linux-hardware.org/?probe=cb540754ed) | Nov 22, 2020 |
| MSI           | CR610                       | [8e7bf69342](https://linux-hardware.org/?probe=8e7bf69342) | Nov 22, 2020 |
| MSI           | CR610                       | [ba50d62533](https://linux-hardware.org/?probe=ba50d62533) | Nov 22, 2020 |
| Dell          | Inspiron 3541               | [f10a3f7947](https://linux-hardware.org/?probe=f10a3f7947) | Nov 21, 2020 |
| Dell          | Inspiron 3541               | [28a2250b7c](https://linux-hardware.org/?probe=28a2250b7c) | Nov 21, 2020 |
| Lenovo        | V130-14IGM 81HM             | [e282aa9ff3](https://linux-hardware.org/?probe=e282aa9ff3) | Nov 20, 2020 |
| Lenovo        | V15-ADA 82C7                | [aa224b81ef](https://linux-hardware.org/?probe=aa224b81ef) | Nov 18, 2020 |
| HP            | Laptop 15-da0xxx            | [2cc03df5d0](https://linux-hardware.org/?probe=2cc03df5d0) | Nov 16, 2020 |
| HP            | Pavilion Notebook           | [c68070f9b3](https://linux-hardware.org/?probe=c68070f9b3) | Nov 10, 2020 |
| HP            | Pavilion Notebook           | [99e25d58ad](https://linux-hardware.org/?probe=99e25d58ad) | Nov 10, 2020 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [9555e785bb](https://linux-hardware.org/?probe=9555e785bb) | Nov 09, 2020 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [0de6c928a4](https://linux-hardware.org/?probe=0de6c928a4) | Nov 09, 2020 |
| Lenovo        | V130-14IGM 81HM             | [23fd9c7140](https://linux-hardware.org/?probe=23fd9c7140) | Nov 09, 2020 |
| Dell          | Inspiron 1720               | [d2018981ad](https://linux-hardware.org/?probe=d2018981ad) | Nov 05, 2020 |
| Lenovo        | V330-15IKB 81AX             | [c6872a9a60](https://linux-hardware.org/?probe=c6872a9a60) | Nov 03, 2020 |
| ASUSTek       | X541NA                      | [a3067761af](https://linux-hardware.org/?probe=a3067761af) | Oct 18, 2020 |
| ASUSTek       | X541NA                      | [baf94800b6](https://linux-hardware.org/?probe=baf94800b6) | Oct 18, 2020 |
| Lenovo        | 3000 N200 0769BNG           | [233a47535c](https://linux-hardware.org/?probe=233a47535c) | Oct 15, 2020 |
| ASUSTek       | TUF Gaming FA506II_FA506... | [9356879a60](https://linux-hardware.org/?probe=9356879a60) | Oct 13, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [4ccef20bb6](https://linux-hardware.org/?probe=4ccef20bb6) | Oct 13, 2020 |
| Lenovo        | 3000 N200 0769BNG           | [8ea03b6d29](https://linux-hardware.org/?probe=8ea03b6d29) | Oct 13, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [43c0586dbe](https://linux-hardware.org/?probe=43c0586dbe) | Oct 12, 2020 |
| Acer          | Aspire A315-31              | [00686fcd7b](https://linux-hardware.org/?probe=00686fcd7b) | Oct 12, 2020 |
| Dell          | Latitude E5470              | [a1ae53e261](https://linux-hardware.org/?probe=a1ae53e261) | Oct 06, 2020 |
| Acer          | Aspire A515-55              | [d88d774f7f](https://linux-hardware.org/?probe=d88d774f7f) | Oct 05, 2020 |
| Lenovo        | B50-45 20388                | [c25c3ef2d8](https://linux-hardware.org/?probe=c25c3ef2d8) | Oct 05, 2020 |
| Lenovo        | B50-45 20388                | [e3d174f961](https://linux-hardware.org/?probe=e3d174f961) | Oct 05, 2020 |
| Lenovo        | V330-15IKB 81AX             | [cb2c394f1a](https://linux-hardware.org/?probe=cb2c394f1a) | Oct 02, 2020 |
| HP            | Notebook                    | [9fcfc67d9c](https://linux-hardware.org/?probe=9fcfc67d9c) | Sep 29, 2020 |
| Lenovo        | V330-15IKB 81AX             | [1734ca75eb](https://linux-hardware.org/?probe=1734ca75eb) | Sep 29, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0KK0... | [d231920967](https://linux-hardware.org/?probe=d231920967) | Sep 28, 2020 |
| HP            | 355 G2                      | [07981744ab](https://linux-hardware.org/?probe=07981744ab) | Sep 27, 2020 |
| HP            | 355 G2                      | [08e4ab3c53](https://linux-hardware.org/?probe=08e4ab3c53) | Sep 26, 2020 |
| Lenovo        | V330-15IKB 81AX             | [a34c376304](https://linux-hardware.org/?probe=a34c376304) | Sep 18, 2020 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [20c5e9395d](https://linux-hardware.org/?probe=20c5e9395d) | Sep 16, 2020 |
| Toshiba       | QOSMIO F50                  | [b60fe2f9e5](https://linux-hardware.org/?probe=b60fe2f9e5) | Sep 16, 2020 |
| HP            | Laptop 17-by2xxx            | [d3fcaecf43](https://linux-hardware.org/?probe=d3fcaecf43) | Sep 12, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [eea494974a](https://linux-hardware.org/?probe=eea494974a) | Sep 11, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [00956078a0](https://linux-hardware.org/?probe=00956078a0) | Sep 03, 2020 |
| Acer          | AOA150                      | [d7397a31d7](https://linux-hardware.org/?probe=d7397a31d7) | Aug 31, 2020 |
| Dell          | Inspiron 3593               | [2c97a34461](https://linux-hardware.org/?probe=2c97a34461) | Aug 20, 2020 |
| HP            | 530 Notebook PC(GU327AA#... | [55d79e4d6a](https://linux-hardware.org/?probe=55d79e4d6a) | Aug 17, 2020 |
| HP            | 530 Notebook PC(GU327AA#... | [19b6cecfad](https://linux-hardware.org/?probe=19b6cecfad) | Aug 17, 2020 |
| Lenovo        | ThinkPad T480 20L6S43212    | [e408e4045b](https://linux-hardware.org/?probe=e408e4045b) | Aug 16, 2020 |
| Dell          | Inspiron 5577               | [f10ef91563](https://linux-hardware.org/?probe=f10ef91563) | Aug 06, 2020 |
| MSI           | CR500                       | [a347574891](https://linux-hardware.org/?probe=a347574891) | Aug 03, 2020 |
| MSI           | CR500                       | [21b1264f8c](https://linux-hardware.org/?probe=21b1264f8c) | Aug 03, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [a2dd413553](https://linux-hardware.org/?probe=a2dd413553) | Jul 26, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [e1073052d4](https://linux-hardware.org/?probe=e1073052d4) | Jul 26, 2020 |
| HP            | ProBook 450 G1              | [8db5efa1fc](https://linux-hardware.org/?probe=8db5efa1fc) | Jul 22, 2020 |
| Acer          | Aspire A315-42              | [b5aacd7b39](https://linux-hardware.org/?probe=b5aacd7b39) | Jul 12, 2020 |
| Acer          | Aspire A315-42              | [88afcfbe5b](https://linux-hardware.org/?probe=88afcfbe5b) | Jul 11, 2020 |
| Lenovo        | V110-15AST 80TD             | [6a86c949a2](https://linux-hardware.org/?probe=6a86c949a2) | Jul 10, 2020 |
| Acer          | Aspire A315-31              | [3ab4bed99e](https://linux-hardware.org/?probe=3ab4bed99e) | Jul 05, 2020 |
| Acer          | Aspire E1-531               | [7baad79bd7](https://linux-hardware.org/?probe=7baad79bd7) | Jul 04, 2020 |
| Lenovo        | V110-15AST 80TD             | [16211b52a1](https://linux-hardware.org/?probe=16211b52a1) | Jun 25, 2020 |
| Sony          | VPCZ21X9E                   | [72e4be4ea5](https://linux-hardware.org/?probe=72e4be4ea5) | Jun 12, 2020 |
| Sony          | VPCZ21X9E                   | [26affa7385](https://linux-hardware.org/?probe=26affa7385) | Jun 12, 2020 |
| Apple         | MacBook5,1                  | [099f5faf14](https://linux-hardware.org/?probe=099f5faf14) | Jun 02, 2020 |
| ASUSTek       | N550JX                      | [99693da42c](https://linux-hardware.org/?probe=99693da42c) | May 31, 2020 |
| Dell          | Inspiron 5559               | [3eee5b1f3d](https://linux-hardware.org/?probe=3eee5b1f3d) | May 31, 2020 |
| HP            | 250 G5 Notebook PC          | [1a72632c64](https://linux-hardware.org/?probe=1a72632c64) | May 27, 2020 |
| Lenovo        | V330-15IKB 81AX             | [c4087d6c6a](https://linux-hardware.org/?probe=c4087d6c6a) | May 21, 2020 |
| ASUSTek       | K50AB                       | [96ccf326a8](https://linux-hardware.org/?probe=96ccf326a8) | May 19, 2020 |
| Dell          | Inspiron N5010              | [f1e4f13c21](https://linux-hardware.org/?probe=f1e4f13c21) | May 18, 2020 |
| Lenovo        | V310-15ISK 80SY             | [a608769eb0](https://linux-hardware.org/?probe=a608769eb0) | May 15, 2020 |
| Lenovo        | ThinkPad T460 20FNS0KT00    | [92e676e189](https://linux-hardware.org/?probe=92e676e189) | May 15, 2020 |
| Lenovo        | ThinkPad T460 20FNS0KT00    | [b7fd9a70e0](https://linux-hardware.org/?probe=b7fd9a70e0) | May 15, 2020 |
| ASUSTek       | G551JK                      | [1d29493d79](https://linux-hardware.org/?probe=1d29493d79) | May 14, 2020 |
| ASUSTek       | G551JK                      | [2aa55f08d0](https://linux-hardware.org/?probe=2aa55f08d0) | May 14, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [03ba757adf](https://linux-hardware.org/?probe=03ba757adf) | May 13, 2020 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [dadd9d2790](https://linux-hardware.org/?probe=dadd9d2790) | May 12, 2020 |
| HP            | ZBook 15 G3                 | [3474070eb8](https://linux-hardware.org/?probe=3474070eb8) | May 10, 2020 |
| Lenovo        | G50-30 80G0                 | [4ac3289ec9](https://linux-hardware.org/?probe=4ac3289ec9) | May 09, 2020 |
| ASUSTek       | K54C                        | [3188c4843a](https://linux-hardware.org/?probe=3188c4843a) | May 08, 2020 |
| Dell          | Inspiron 5567               | [099e174bf4](https://linux-hardware.org/?probe=099e174bf4) | May 07, 2020 |
| Lenovo        | ThinkPad L470 20J5S4RS00    | [b646e36068](https://linux-hardware.org/?probe=b646e36068) | May 04, 2020 |
| Dell          | Inspiron 3537               | [a26c6f5812](https://linux-hardware.org/?probe=a26c6f5812) | Apr 21, 2020 |
| HP            | 250 G5 Notebook PC          | [01f3f0f185](https://linux-hardware.org/?probe=01f3f0f185) | Apr 14, 2020 |
| Lenovo        | ThinkPad E560 20EV003EMS    | [0b978ac786](https://linux-hardware.org/?probe=0b978ac786) | Apr 14, 2020 |
| HP            | ZBook 15 G3                 | [16ee557e51](https://linux-hardware.org/?probe=16ee557e51) | Apr 12, 2020 |
| HP            | Mini 110-3100               | [a32c0db8bb](https://linux-hardware.org/?probe=a32c0db8bb) | Apr 11, 2020 |
| Acer          | Aspire 7520G                | [d5bc992097](https://linux-hardware.org/?probe=d5bc992097) | Apr 04, 2020 |
| Toshiba       | TECRA Z50-A                 | [889a5aa1a6](https://linux-hardware.org/?probe=889a5aa1a6) | Apr 02, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [cb84e8c9af](https://linux-hardware.org/?probe=cb84e8c9af) | Mar 23, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [8670fa919e](https://linux-hardware.org/?probe=8670fa919e) | Mar 23, 2020 |
| ASUSTek       | X541NC                      | [63b197a2c0](https://linux-hardware.org/?probe=63b197a2c0) | Mar 21, 2020 |
| Fujitsu Si... | AMILO Li3710                | [11ebf93798](https://linux-hardware.org/?probe=11ebf93798) | Mar 18, 2020 |
| Lenovo        | Yoga 300-11IBR 80M1         | [b19ba42878](https://linux-hardware.org/?probe=b19ba42878) | Mar 17, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [334884c294](https://linux-hardware.org/?probe=334884c294) | Mar 10, 2020 |
| HP            | 250 G1                      | [7a7e2dfcee](https://linux-hardware.org/?probe=7a7e2dfcee) | Mar 10, 2020 |
| HP            | 250 G4                      | [d8b2caab0f](https://linux-hardware.org/?probe=d8b2caab0f) | Mar 08, 2020 |
| Acer          | Aspire A315-41              | [5870ecc433](https://linux-hardware.org/?probe=5870ecc433) | Mar 08, 2020 |
| Acer          | Aspire E3-112               | [62041aa7fa](https://linux-hardware.org/?probe=62041aa7fa) | Mar 08, 2020 |
| Lenovo        | ThinkPad T500 2056W2J       | [1923e28174](https://linux-hardware.org/?probe=1923e28174) | Mar 05, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [bda2f29230](https://linux-hardware.org/?probe=bda2f29230) | Feb 24, 2020 |
| Fujitsu       | LIFEBOOK AH530              | [5d93dd0911](https://linux-hardware.org/?probe=5d93dd0911) | Feb 20, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [eb55029938](https://linux-hardware.org/?probe=eb55029938) | Feb 18, 2020 |
| ASUSTek       | X551MA                      | [530fb26de2](https://linux-hardware.org/?probe=530fb26de2) | Feb 16, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [4d942fa22c](https://linux-hardware.org/?probe=4d942fa22c) | Feb 10, 2020 |
| ASUSTek       | X541UVK                     | [9e44db3513](https://linux-hardware.org/?probe=9e44db3513) | Feb 06, 2020 |
| Lenovo        | G505 20240                  | [3208a023bf](https://linux-hardware.org/?probe=3208a023bf) | Feb 04, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [91bdd7eccf](https://linux-hardware.org/?probe=91bdd7eccf) | Feb 01, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [a4a64dfa74](https://linux-hardware.org/?probe=a4a64dfa74) | Feb 01, 2020 |
| Acer          | Aspire E1-530               | [0e64af354b](https://linux-hardware.org/?probe=0e64af354b) | Jan 30, 2020 |
| Acer          | Swift SF314-56              | [303332d310](https://linux-hardware.org/?probe=303332d310) | Jan 29, 2020 |
| Toshiba       | Satellite C50-B             | [06c487df1d](https://linux-hardware.org/?probe=06c487df1d) | Jan 28, 2020 |
| Acer          | Aspire A315-31              | [b482e7ef86](https://linux-hardware.org/?probe=b482e7ef86) | Jan 25, 2020 |
| Lenovo        | ThinkPad T520 42406AG       | [7de4fdce8d](https://linux-hardware.org/?probe=7de4fdce8d) | Jan 23, 2020 |
| Lenovo        | V330-15IKB 81AX             | [b0d2c5611e](https://linux-hardware.org/?probe=b0d2c5611e) | Jan 22, 2020 |
| HP            | Compaq nc6320 (RU381ES#A... | [d3a7e386ae](https://linux-hardware.org/?probe=d3a7e386ae) | Jan 16, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [84bf577e7d](https://linux-hardware.org/?probe=84bf577e7d) | Jan 16, 2020 |
| Acer          | Aspire A315-31              | [36dcda44ba](https://linux-hardware.org/?probe=36dcda44ba) | Jan 15, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [cc4a9ba559](https://linux-hardware.org/?probe=cc4a9ba559) | Jan 15, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [72f2c4c12a](https://linux-hardware.org/?probe=72f2c4c12a) | Jan 15, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b5d63aec77](https://linux-hardware.org/?probe=b5d63aec77) | Jan 15, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [7d389b1fcb](https://linux-hardware.org/?probe=7d389b1fcb) | Jan 15, 2020 |
| Lenovo        | IdeaPad S540-14API 81NH     | [b2c0da1b44](https://linux-hardware.org/?probe=b2c0da1b44) | Jan 12, 2020 |
| HP            | ProBook 650 G1              | [224d2a830f](https://linux-hardware.org/?probe=224d2a830f) | Jan 08, 2020 |
| ASUSTek       | X55A                        | [3482727e9f](https://linux-hardware.org/?probe=3482727e9f) | Jan 03, 2020 |
| Lenovo        | ThinkPad P50 20EQS1AC00     | [0767220809](https://linux-hardware.org/?probe=0767220809) | Jan 03, 2020 |
| Dell          | Inspiron 3558               | [63be3850f8](https://linux-hardware.org/?probe=63be3850f8) | Dec 31, 2019 |
| Acer          | Aspire A315-51              | [fb858f1586](https://linux-hardware.org/?probe=fb858f1586) | Dec 30, 2019 |
| Acer          | Aspire A315-51              | [0dfa591b1c](https://linux-hardware.org/?probe=0dfa591b1c) | Dec 30, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [dfac3d950c](https://linux-hardware.org/?probe=dfac3d950c) | Dec 29, 2019 |
| Samsung       | N250P/N145P                 | [708195d4f1](https://linux-hardware.org/?probe=708195d4f1) | Dec 27, 2019 |
| Toshiba       | Satellite C850-1H6          | [a0ffb29c6c](https://linux-hardware.org/?probe=a0ffb29c6c) | Dec 18, 2019 |
| HP            | ProBook 640 G1              | [0813940da0](https://linux-hardware.org/?probe=0813940da0) | Dec 09, 2019 |
| Lenovo        | IdeaPad L340-15API 81LW     | [3193d44169](https://linux-hardware.org/?probe=3193d44169) | Dec 04, 2019 |
| ASUSTek       | X550MJ                      | [3fde87c7b4](https://linux-hardware.org/?probe=3fde87c7b4) | Dec 04, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [8a33af729e](https://linux-hardware.org/?probe=8a33af729e) | Dec 03, 2019 |
| Acer          | Aspire A315-51              | [77affe222c](https://linux-hardware.org/?probe=77affe222c) | Nov 16, 2019 |
| HP            | Notebook                    | [8df47391f9](https://linux-hardware.org/?probe=8df47391f9) | Nov 15, 2019 |
| Acer          | Aspire A315-31              | [3812d4729c](https://linux-hardware.org/?probe=3812d4729c) | Nov 14, 2019 |
| HP            | Notebook                    | [fe0316d8bb](https://linux-hardware.org/?probe=fe0316d8bb) | Nov 14, 2019 |
| Lenovo        | ThinkPad T420s 4174BB2      | [53037be14e](https://linux-hardware.org/?probe=53037be14e) | Nov 03, 2019 |
| Lenovo        | ThinkPad Edge E330 33544... | [c27afaa8d2](https://linux-hardware.org/?probe=c27afaa8d2) | Oct 20, 2019 |
| Acer          | Aspire 5350                 | [bfca910110](https://linux-hardware.org/?probe=bfca910110) | Oct 20, 2019 |
| Lenovo        | ThinkPad Edge E330 33544... | [0e391bc5f7](https://linux-hardware.org/?probe=0e391bc5f7) | Oct 20, 2019 |
| HP            | ProBook 650 G1              | [4886df0de1](https://linux-hardware.org/?probe=4886df0de1) | Oct 20, 2019 |
| Acer          | Aspire 5350                 | [6c1a1b4cd5](https://linux-hardware.org/?probe=6c1a1b4cd5) | Oct 19, 2019 |
| Dell          | Latitude 5580               | [e2d5fd3182](https://linux-hardware.org/?probe=e2d5fd3182) | Oct 18, 2019 |
| Dell          | Latitude 5580               | [fbb2c68803](https://linux-hardware.org/?probe=fbb2c68803) | Oct 18, 2019 |
| Dell          | Latitude 5580               | [4ba29dd71c](https://linux-hardware.org/?probe=4ba29dd71c) | Oct 18, 2019 |
| Acer          | Aspire A315-31              | [2ab608ac7e](https://linux-hardware.org/?probe=2ab608ac7e) | Oct 13, 2019 |
| HP            | Pavilion Notebook           | [dffd6ce6cb](https://linux-hardware.org/?probe=dffd6ce6cb) | Oct 13, 2019 |
| Lenovo        | IdeaPad S540-14API 81NH     | [d0671b5d7f](https://linux-hardware.org/?probe=d0671b5d7f) | Oct 12, 2019 |
| Acer          | Aspire A717-71G             | [4bad7bd17c](https://linux-hardware.org/?probe=4bad7bd17c) | Sep 21, 2019 |
| Lenovo        | ThinkPad T520 42406AG       | [3e835a3fea](https://linux-hardware.org/?probe=3e835a3fea) | Sep 15, 2019 |
| Razer         | Blade                       | [da397f901b](https://linux-hardware.org/?probe=da397f901b) | Sep 10, 2019 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [655aa5059b](https://linux-hardware.org/?probe=655aa5059b) | Sep 04, 2019 |
| HP            | Laptop 15-ra0xx             | [2e41137334](https://linux-hardware.org/?probe=2e41137334) | Sep 03, 2019 |
| HP            | Laptop 15-ra0xx             | [8aadf9c34a](https://linux-hardware.org/?probe=8aadf9c34a) | Sep 02, 2019 |
| HP            | Laptop 15-ra0xx             | [96e535cece](https://linux-hardware.org/?probe=96e535cece) | Sep 02, 2019 |
| Acer          | Aspire A315-31              | [9d8698e977](https://linux-hardware.org/?probe=9d8698e977) | Aug 28, 2019 |
| Acer          | Aspire A315-31              | [95dba17d9a](https://linux-hardware.org/?probe=95dba17d9a) | Aug 17, 2019 |
| Dell          | Precision 7730              | [b9281326d7](https://linux-hardware.org/?probe=b9281326d7) | Jul 25, 2019 |
| ASUSTek       | X201EP                      | [a1a1f1965a](https://linux-hardware.org/?probe=a1a1f1965a) | Jul 22, 2019 |
| Dell          | Latitude E5440              | [f40c3d18fb](https://linux-hardware.org/?probe=f40c3d18fb) | Jul 19, 2019 |
| Lenovo        | ThinkPad P51 20HHS04800     | [4013dc5bc1](https://linux-hardware.org/?probe=4013dc5bc1) | Jul 16, 2019 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [1613715663](https://linux-hardware.org/?probe=1613715663) | Jul 15, 2019 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [62ebee4d1f](https://linux-hardware.org/?probe=62ebee4d1f) | Jul 15, 2019 |
| ASUSTek       | X541NA                      | [5fdb751780](https://linux-hardware.org/?probe=5fdb751780) | Jul 11, 2019 |
| ASUSTek       | X541NA                      | [8676bfc466](https://linux-hardware.org/?probe=8676bfc466) | Jul 11, 2019 |
| HP            | Laptop 15-ra0xx             | [f28399b983](https://linux-hardware.org/?probe=f28399b983) | Jul 09, 2019 |
| Toshiba       | Satellite L755              | [e2413cea5d](https://linux-hardware.org/?probe=e2413cea5d) | Jul 06, 2019 |
| HP            | 250 G6 Notebook PC          | [7d8551e612](https://linux-hardware.org/?probe=7d8551e612) | Jun 29, 2019 |
| Lenovo        | G500 20236                  | [4faa6112c3](https://linux-hardware.org/?probe=4faa6112c3) | Jun 28, 2019 |
| HP            | Laptop 15-db0xxx            | [df6f074dbd](https://linux-hardware.org/?probe=df6f074dbd) | Jun 11, 2019 |
| IBM           | ThinkPad R52p 1847W5R       | [1dc1d8e6f2](https://linux-hardware.org/?probe=1dc1d8e6f2) | Jun 09, 2019 |
| HP            | Unknown                     | [cf3a7ad203](https://linux-hardware.org/?probe=cf3a7ad203) | Jun 05, 2019 |
| ASUSTek       | ZenBook Pro 15 UX550GDX_... | [f1a85fe5ba](https://linux-hardware.org/?probe=f1a85fe5ba) | Jun 05, 2019 |
| HP            | Pavilion Notebook           | [ad610739b6](https://linux-hardware.org/?probe=ad610739b6) | Jun 01, 2019 |
| HP            | Pavilion Notebook           | [476f3cfb4a](https://linux-hardware.org/?probe=476f3cfb4a) | May 26, 2019 |
| Acer          | Aspire A717-71G             | [882e32aaf7](https://linux-hardware.org/?probe=882e32aaf7) | May 21, 2019 |
| Dell          | Inspiron 5567               | [29fadee02e](https://linux-hardware.org/?probe=29fadee02e) | May 19, 2019 |
| Lenovo        | V330-15IKB 81AX             | [8f1cfe4955](https://linux-hardware.org/?probe=8f1cfe4955) | May 17, 2019 |
| HP            | 250 G1                      | [4550b3fdf6](https://linux-hardware.org/?probe=4550b3fdf6) | May 17, 2019 |
| HP            | 250 G1                      | [7dda48b144](https://linux-hardware.org/?probe=7dda48b144) | May 17, 2019 |
| ASUSTek       | X541SA                      | [dff8b29714](https://linux-hardware.org/?probe=dff8b29714) | May 10, 2019 |
| ASUSTek       | X541SA                      | [308cc99aee](https://linux-hardware.org/?probe=308cc99aee) | May 10, 2019 |
| ASUSTek       | X541SA                      | [f03f0840fb](https://linux-hardware.org/?probe=f03f0840fb) | May 10, 2019 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [8195906a99](https://linux-hardware.org/?probe=8195906a99) | May 06, 2019 |
| Acer          | Aspire E1-530               | [e5658355fa](https://linux-hardware.org/?probe=e5658355fa) | May 03, 2019 |
| LG Electro... | LW70-JJKG                   | [76f306de39](https://linux-hardware.org/?probe=76f306de39) | Apr 27, 2019 |
| Dell          | G3 3779                     | [8407de048a](https://linux-hardware.org/?probe=8407de048a) | Apr 26, 2019 |
| Acer          | Aspire A717-71G             | [7385402cb8](https://linux-hardware.org/?probe=7385402cb8) | Apr 25, 2019 |
| ASUSTek       | X541NC                      | [50aeeec380](https://linux-hardware.org/?probe=50aeeec380) | Apr 19, 2019 |
| ASUSTek       | X541NC                      | [5278c50f95](https://linux-hardware.org/?probe=5278c50f95) | Apr 13, 2019 |
| Fujitsu Si... | AMILO PRO V3515             | [1d96b8f60d](https://linux-hardware.org/?probe=1d96b8f60d) | Apr 11, 2019 |
| ASUSTek       | X541NA                      | [b94a9e24c1](https://linux-hardware.org/?probe=b94a9e24c1) | Apr 07, 2019 |
| Toshiba       | Satellite C870-17H          | [dc2ce35421](https://linux-hardware.org/?probe=dc2ce35421) | Apr 06, 2019 |
| Acer          | Aspire A717-71G             | [600ac82384](https://linux-hardware.org/?probe=600ac82384) | Mar 30, 2019 |
| Acer          | Aspire 6935                 | [d8a5d80999](https://linux-hardware.org/?probe=d8a5d80999) | Mar 23, 2019 |
| Dell          | Inspiron N5110              | [5137b5b274](https://linux-hardware.org/?probe=5137b5b274) | Mar 21, 2019 |
| HP            | Pavilion dv5                | [3f857e2920](https://linux-hardware.org/?probe=3f857e2920) | Mar 18, 2019 |
| ASUSTek       | X550MD                      | [4e37ad043d](https://linux-hardware.org/?probe=4e37ad043d) | Mar 14, 2019 |
| Sony          | VGN-FE31Z                   | [860dcaf74d](https://linux-hardware.org/?probe=860dcaf74d) | Feb 16, 2019 |
| Dell          | Precision M4600             | [6f6a52607b](https://linux-hardware.org/?probe=6f6a52607b) | Feb 14, 2019 |
| ASUSTek       | X540LA                      | [03ab6a3cd8](https://linux-hardware.org/?probe=03ab6a3cd8) | Feb 11, 2019 |
| Acer          | Aspire A315-21              | [b28972ad25](https://linux-hardware.org/?probe=b28972ad25) | Feb 10, 2019 |
| MSI           | MS-16Y1                     | [a676d0126f](https://linux-hardware.org/?probe=a676d0126f) | Feb 07, 2019 |
| ASUSTek       | X540LA                      | [a7cb02a6fb](https://linux-hardware.org/?probe=a7cb02a6fb) | Feb 02, 2019 |
| ASUSTek       | X540LA                      | [18752af5af](https://linux-hardware.org/?probe=18752af5af) | Jan 31, 2019 |
| ASUSTek       | X540LA                      | [dea612f99d](https://linux-hardware.org/?probe=dea612f99d) | Jan 31, 2019 |
| ASUSTek       | X541NA                      | [d66eb82eac](https://linux-hardware.org/?probe=d66eb82eac) | Jan 23, 2019 |
| ASUSTek       | K55DR                       | [13a17add51](https://linux-hardware.org/?probe=13a17add51) | Jan 22, 2019 |
| Acer          | Aspire ES1-532G             | [af17a54207](https://linux-hardware.org/?probe=af17a54207) | Jan 12, 2019 |
| ASUSTek       | X541NA                      | [53fba97f8a](https://linux-hardware.org/?probe=53fba97f8a) | Jan 04, 2019 |
| ASUSTek       | X541NA                      | [a0cb966487](https://linux-hardware.org/?probe=a0cb966487) | Jan 04, 2019 |
| Acer          | Aspire A717-71G             | [c3edad77d8](https://linux-hardware.org/?probe=c3edad77d8) | Dec 24, 2018 |
| Acer          | Aspire A315-21              | [9289091c83](https://linux-hardware.org/?probe=9289091c83) | Nov 28, 2018 |
| Acer          | Aspire A717-71G             | [3c22bb7c43](https://linux-hardware.org/?probe=3c22bb7c43) | Nov 04, 2018 |
| Acer          | Aspire A717-71G             | [65968eaade](https://linux-hardware.org/?probe=65968eaade) | Nov 01, 2018 |
| HP            | 15                          | [a6c00a0fde](https://linux-hardware.org/?probe=a6c00a0fde) | Jul 08, 2018 |
| HP            | 250 G5 Notebook PC          | [24f9e4ee20](https://linux-hardware.org/?probe=24f9e4ee20) | Jun 24, 2018 |
| HP            | Pavilion dv7                | [566fa1aed1](https://linux-hardware.org/?probe=566fa1aed1) | Feb 24, 2018 |
| HP            | ProBook 650 G1              | [b0a5c81710](https://linux-hardware.org/?probe=b0a5c81710) | Jan 24, 2018 |
| HP            | 250 G5 Notebook PC          | [c939de9629](https://linux-hardware.org/?probe=c939de9629) | Dec 17, 2017 |
| Toshiba       | Satellite C50-A-1G3         | [4d2b35494b](https://linux-hardware.org/?probe=4d2b35494b) | Dec 16, 2017 |
| HP            | 15                          | [93985df093](https://linux-hardware.org/?probe=93985df093) | Sep 26, 2017 |
| Dell          | Inspiron 7520               | [3b5516e47b](https://linux-hardware.org/?probe=3b5516e47b) | Aug 27, 2017 |
| Fujitsu Si... | ESPRIMO Mobile V5505        | [5ab0f522c2](https://linux-hardware.org/?probe=5ab0f522c2) | Aug 19, 2017 |
| Lenovo        | G560 20042                  | [6f5d9b39bb](https://linux-hardware.org/?probe=6f5d9b39bb) | May 09, 2017 |
| ASUSTek       | K55VD                       | [5fecb30529](https://linux-hardware.org/?probe=5fecb30529) | Jan 08, 2017 |
| ASUSTek       | K55VD                       | [f9af076683](https://linux-hardware.org/?probe=f9af076683) | Jan 07, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 41        | 13.31%  |
| Ubuntu 18.04                 | 28        | 9.09%   |
| Zorin 15                     | 9         | 2.92%   |
| BlackPanther 18.1            | 9         | 2.92%   |
| ROSA R11                     | 8         | 2.6%    |
| OpenMandriva 4.3             | 8         | 2.6%    |
| Ubuntu 19.10                 | 7         | 2.27%   |
| Arch                         | 7         | 2.27%   |
| OpenMandriva 4.2             | 6         | 1.95%   |
| Linux Mint 19.3              | 6         | 1.95%   |
| Ubuntu 21.10                 | 5         | 1.62%   |
| Ubuntu 18.10                 | 5         | 1.62%   |
| ROSA R10                     | 5         | 1.62%   |
| KDE neon 20.04               | 5         | 1.62%   |
| ROSA R11.1                   | 4         | 1.3%    |
| Linux Mint 20.3              | 4         | 1.3%    |
| Fedora 34                    | 4         | 1.3%    |
| Xubuntu 20.04                | 3         | 0.97%   |
| Ubuntu 21.04                 | 3         | 0.97%   |
| Ubuntu 19.04                 | 3         | 0.97%   |
| Ubuntu 16.04                 | 3         | 0.97%   |
| ROSA R9                      | 3         | 0.97%   |
| Pop!_OS 21.04                | 3         | 0.97%   |
| Manjaro                      | 3         | 0.97%   |
| Linux Mint 20.2              | 3         | 0.97%   |
| Linux Mint 20.1              | 3         | 0.97%   |
| KDE neon 18.04               | 3         | 0.97%   |
| Fedora 30                    | 3         | 0.97%   |
| Endless 3.9.4                | 3         | 0.97%   |
| Endless 3.9.0                | 3         | 0.97%   |
| Endless 3.5.4                | 3         | 0.97%   |
| ArcoLinux Rolling            | 3         | 0.97%   |
| Arch Rolling                 | 3         | 0.97%   |
| Xubuntu 18.04                | 2         | 0.65%   |
| Ubuntu 22.04                 | 2         | 0.65%   |
| ROSA R8.1                    | 2         | 0.65%   |
| Pop!_OS 20.10                | 2         | 0.65%   |
| Pop!_OS 20.04                | 2         | 0.65%   |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 0.65%   |
| Manjaro 18.1.5               | 2         | 0.65%   |
| Kubuntu 20.04                | 2         | 0.65%   |
| Fedora 35                    | 2         | 0.65%   |
| Fedora 33                    | 2         | 0.65%   |
| Fedora 32                    | 2         | 0.65%   |
| Endless 3.9.3                | 2         | 0.65%   |
| Endless 3.8.7                | 2         | 0.65%   |
| Endless 3.7.5                | 2         | 0.65%   |
| Endless 3.7.3                | 2         | 0.65%   |
| Endless 3.6.2                | 2         | 0.65%   |
| Endless 3.5.7                | 2         | 0.65%   |
| Endless 3.3.19-nexthw1       | 2         | 0.65%   |
| Zorin 12                     | 1         | 0.32%   |
| Xubuntu 21.10                | 1         | 0.32%   |
| UbuntuDDE 21.04              | 1         | 0.32%   |
| Ubuntu MATE 18.04            | 1         | 0.32%   |
| Ubuntu Budgie 20.10          | 1         | 0.32%   |
| Ubuntu 20.10                 | 1         | 0.32%   |
| Slackware 15.0               | 1         | 0.32%   |
| ROSA R8                      | 1         | 0.32%   |
| ROSA 12.2                    | 1         | 0.32%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 97        | 34.15%  |
| Endless       | 30        | 10.56%  |
| ROSA          | 21        | 7.39%   |
| Linux Mint    | 18        | 6.34%   |
| OpenMandriva  | 14        | 4.93%   |
| Fedora        | 11        | 3.87%   |
| Zorin         | 10        | 3.52%   |
| Manjaro       | 10        | 3.52%   |
| BlackPanther  | 10        | 3.52%   |
| Arch          | 10        | 3.52%   |
| Pop!_OS       | 8         | 2.82%   |
| KDE neon      | 8         | 2.82%   |
| Xubuntu       | 6         | 2.11%   |
| Kubuntu       | 5         | 1.76%   |
| openSUSE      | 3         | 1.06%   |
| Lubuntu       | 3         | 1.06%   |
| ArcoLinux     | 3         | 1.06%   |
| Kali          | 2         | 0.7%    |
| Elementary    | 2         | 0.7%    |
| UbuntuDDE     | 1         | 0.35%   |
| Ubuntu MATE   | 1         | 0.35%   |
| Ubuntu Budgie | 1         | 0.35%   |
| Slackware     | 1         | 0.35%   |
| Peppermint    | 1         | 0.35%   |
| MX            | 1         | 0.35%   |
| GNOME OS      | 1         | 0.35%   |
| Generic       | 1         | 0.35%   |
| Garuda Linux  | 1         | 0.35%   |
| EndeavourOS   | 1         | 0.35%   |
| Deepin        | 1         | 0.35%   |
| Debian        | 1         | 0.35%   |
| Clear Linux   | 1         | 0.35%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003         | 8         | 2.45%   |
| 4.18.16-desktop-1bP             | 7         | 2.14%   |
| 5.8.0-14-generic                | 6         | 1.83%   |
| 5.3.0-40-generic                | 6         | 1.83%   |
| 5.10.14-desktop-1omv4002        | 6         | 1.83%   |
| 4.18.0-15-generic               | 6         | 1.83%   |
| 5.11.0-27-generic               | 5         | 1.53%   |
| 5.4.0-47-generic                | 4         | 1.22%   |
| 5.4.0-42-generic                | 4         | 1.22%   |
| 5.3.0-23-generic                | 4         | 1.22%   |
| 4.18.0-25-generic               | 4         | 1.22%   |
| 4.18.0-12-generic               | 4         | 1.22%   |
| 4.15.0-15-generic               | 4         | 1.22%   |
| 5.4.0-58-generic                | 3         | 0.92%   |
| 5.4.0-52-generic                | 3         | 0.92%   |
| 5.4.0-48-generic                | 3         | 0.92%   |
| 5.4.0-19-generic                | 3         | 0.92%   |
| 5.3.0-51-generic                | 3         | 0.92%   |
| 5.3.0-29-generic                | 3         | 0.92%   |
| 5.3.0-28-generic                | 3         | 0.92%   |
| 5.13.0-30-generic               | 3         | 0.92%   |
| 5.0.0-31-generic                | 3         | 0.92%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 3         | 0.92%   |
| 4.18.0-10-generic               | 3         | 0.92%   |
| 4.15.0-desktop-45.1rosa-x86_64  | 3         | 0.92%   |
| 5.8.11-1-MANJARO                | 2         | 0.61%   |
| 5.8.0-55-generic                | 2         | 0.61%   |
| 5.8.0-48-generic                | 2         | 0.61%   |
| 5.8.0-33-generic                | 2         | 0.61%   |
| 5.6.14-desktop-2bP              | 2         | 0.61%   |
| 5.4.0-94-generic                | 2         | 0.61%   |
| 5.4.0-88-generic                | 2         | 0.61%   |
| 5.4.0-74-generic                | 2         | 0.61%   |
| 5.4.0-73-generic                | 2         | 0.61%   |
| 5.4.0-70-generic                | 2         | 0.61%   |
| 5.4.0-66-generic                | 2         | 0.61%   |
| 5.4.0-54-generic                | 2         | 0.61%   |
| 5.4.0-33-generic                | 2         | 0.61%   |
| 5.4.0-31-generic                | 2         | 0.61%   |
| 5.4.0-29-generic                | 2         | 0.61%   |
| 5.3.0-45-generic                | 2         | 0.61%   |
| 5.3.0-24-generic                | 2         | 0.61%   |
| 5.3.0-12-generic                | 2         | 0.61%   |
| 5.13.0-40-generic               | 2         | 0.61%   |
| 5.13.0-39-generic               | 2         | 0.61%   |
| 5.13.0-27-generic               | 2         | 0.61%   |
| 5.13.0-23-generic               | 2         | 0.61%   |
| 5.11.0-7620-generic             | 2         | 0.61%   |
| 5.11.0-40-generic               | 2         | 0.61%   |
| 5.11.0-38-generic               | 2         | 0.61%   |
| 5.11.0-35-generic               | 2         | 0.61%   |
| 5.11.0-34-generic               | 2         | 0.61%   |
| 5.0.0-27-generic                | 2         | 0.61%   |
| 5.0.0-25-generic                | 2         | 0.61%   |
| 5.0.0-20-generic                | 2         | 0.61%   |
| 5.0.0-15-generic                | 2         | 0.61%   |
| 4.18.0-20-generic               | 2         | 0.61%   |
| 4.18.0-17-generic               | 2         | 0.61%   |
| 4.15.0-desktop-45.1rosa-i586    | 2         | 0.61%   |
| 4.15.0-47-generic               | 2         | 0.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 50        | 16.13%  |
| 4.15.0  | 29        | 9.35%   |
| 5.3.0   | 27        | 8.71%   |
| 5.11.0  | 21        | 6.77%   |
| 4.18.0  | 21        | 6.77%   |
| 5.8.0   | 19        | 6.13%   |
| 5.13.0  | 17        | 5.48%   |
| 5.0.0   | 17        | 5.48%   |
| 5.16.7  | 8         | 2.58%   |
| 4.18.16 | 7         | 2.26%   |
| 5.10.14 | 6         | 1.94%   |
| 5.10.0  | 4         | 1.29%   |
| 4.9.20  | 4         | 1.29%   |
| 5.8.11  | 3         | 0.97%   |
| 5.15.0  | 3         | 0.97%   |
| 5.6.14  | 2         | 0.65%   |
| 5.15.11 | 2         | 0.65%   |
| 5.12.9  | 2         | 0.65%   |
| 4.9.76  | 2         | 0.65%   |
| 4.13.0  | 2         | 0.65%   |
| 5.9.8   | 1         | 0.32%   |
| 5.9.12  | 1         | 0.32%   |
| 5.8.13  | 1         | 0.32%   |
| 5.7.9   | 1         | 0.32%   |
| 5.7.10  | 1         | 0.32%   |
| 5.6.8   | 1         | 0.32%   |
| 5.6.3   | 1         | 0.32%   |
| 5.6.11  | 1         | 0.32%   |
| 5.5.7   | 1         | 0.32%   |
| 5.4.88  | 1         | 0.32%   |
| 5.4.83  | 1         | 0.32%   |
| 5.4.75  | 1         | 0.32%   |
| 5.4.6   | 1         | 0.32%   |
| 5.4.40  | 1         | 0.32%   |
| 5.4.32  | 1         | 0.32%   |
| 5.4.31  | 1         | 0.32%   |
| 5.4.15  | 1         | 0.32%   |
| 5.4.12  | 1         | 0.32%   |
| 5.3.16  | 1         | 0.32%   |
| 5.17.4  | 1         | 0.32%   |
| 5.17.0  | 1         | 0.32%   |
| 5.16.2  | 1         | 0.32%   |
| 5.16.17 | 1         | 0.32%   |
| 5.16.0  | 1         | 0.32%   |
| 5.15.8  | 1         | 0.32%   |
| 5.15.25 | 1         | 0.32%   |
| 5.15.21 | 1         | 0.32%   |
| 5.15.15 | 1         | 0.32%   |
| 5.14.11 | 1         | 0.32%   |
| 5.13.12 | 1         | 0.32%   |
| 5.13.11 | 1         | 0.32%   |
| 5.12.7  | 1         | 0.32%   |
| 5.12.4  | 1         | 0.32%   |
| 5.12.15 | 1         | 0.32%   |
| 5.12.14 | 1         | 0.32%   |
| 5.11.7  | 1         | 0.32%   |
| 5.11.6  | 1         | 0.32%   |
| 5.11.2  | 1         | 0.32%   |
| 5.11.18 | 1         | 0.32%   |
| 5.11.16 | 1         | 0.32%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 59        | 19.28%  |
| 4.15    | 29        | 9.48%   |
| 5.3     | 28        | 9.15%   |
| 4.18    | 28        | 9.15%   |
| 5.11    | 27        | 8.82%   |
| 5.8     | 23        | 7.52%   |
| 5.13    | 19        | 6.21%   |
| 5.0     | 19        | 6.21%   |
| 5.10    | 16        | 5.23%   |
| 5.16    | 11        | 3.59%   |
| 4.9     | 11        | 3.59%   |
| 5.15    | 8         | 2.61%   |
| 5.12    | 5         | 1.63%   |
| 5.6     | 4         | 1.31%   |
| 5.9     | 2         | 0.65%   |
| 5.7     | 2         | 0.65%   |
| 5.17    | 2         | 0.65%   |
| 5.1     | 2         | 0.65%   |
| 4.19    | 2         | 0.65%   |
| 4.13    | 2         | 0.65%   |
| 4.1     | 2         | 0.65%   |
| 5.5     | 1         | 0.33%   |
| 5.14    | 1         | 0.33%   |
| 4.17    | 1         | 0.33%   |
| 4.12    | 1         | 0.33%   |
| 4.10    | 1         | 0.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 263       | 95.29%  |
| i686   | 13        | 4.71%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 115       | 39.52%  |
| Unknown         | 51        | 17.53%  |
| KDE5            | 47        | 16.15%  |
| XFCE            | 20        | 6.87%   |
| X-Cinnamon      | 13        | 4.47%   |
| KDE4            | 11        | 3.78%   |
| KDE             | 6         | 2.06%   |
| Cinnamon        | 6         | 2.06%   |
| MATE            | 4         | 1.37%   |
| LXQt            | 4         | 1.37%   |
| i3              | 4         | 1.37%   |
| Pantheon        | 2         | 0.69%   |
| Deepin          | 2         | 0.69%   |
| Unity           | 1         | 0.34%   |
| qtile           | 1         | 0.34%   |
| LXDE            | 1         | 0.34%   |
| GNOME Flashback | 1         | 0.34%   |
| dwm             | 1         | 0.34%   |
| Budgie          | 1         | 0.34%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 230       | 80.99%  |
| Unknown | 29        | 10.21%  |
| Wayland | 20        | 7.04%   |
| Tty     | 5         | 1.76%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 163       | 57.39%  |
| SDDM    | 45        | 15.85%  |
| GDM     | 29        | 10.21%  |
| LightDM | 14        | 4.93%   |
| KDM     | 12        | 4.23%   |
| GDM3    | 10        | 3.52%   |
| TDM     | 9         | 3.17%   |
| XDM     | 1         | 0.35%   |
| Ly      | 1         | 0.35%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| en_US       | 183       | 62.89%  |
| Unknown     | 73        | 25.09%  |
| sr_RS@latin | 11        | 3.78%   |
| sr_RS       | 9         | 3.09%   |
| en_GB       | 7         | 2.41%   |
| C           | 4         | 1.37%   |
| hu_HU       | 2         | 0.69%   |
| ru_RU       | 1         | 0.34%   |
| de_DE       | 1         | 0.34%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 150       | 53.38%  |
| BIOS | 131       | 46.62%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 221       | 77.54%  |
| Overlay | 27        | 9.47%   |
| Unknown | 26        | 9.12%   |
| Btrfs   | 9         | 3.16%   |
| Zfs     | 1         | 0.35%   |
| Tmpfs   | 1         | 0.35%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 169       | 60.14%  |
| GPT     | 70        | 24.91%  |
| MBR     | 42        | 14.95%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 248       | 88.89%  |
| Yes       | 31        | 11.11%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 207       | 73.93%  |
| Yes       | 73        | 26.07%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 67        | 24.36%  |
| Hewlett-Packard     | 51        | 18.55%  |
| ASUSTek Computer    | 42        | 15.27%  |
| Dell                | 38        | 13.82%  |
| Acer                | 31        | 11.27%  |
| Toshiba             | 13        | 4.73%   |
| Fujitsu Siemens     | 6         | 2.18%   |
| MSI                 | 5         | 1.82%   |
| Apple               | 4         | 1.45%   |
| Fujitsu             | 3         | 1.09%   |
| Sony                | 2         | 0.73%   |
| Samsung Electronics | 2         | 0.73%   |
| Medion              | 2         | 0.73%   |
| TWC                 | 1         | 0.36%   |
| Razer               | 1         | 0.36%   |
| Packard Bell        | 1         | 0.36%   |
| LG Electronics      | 1         | 0.36%   |
| IBM                 | 1         | 0.36%   |
| HUAWEI              | 1         | 0.36%   |
| Gigabyte Technology | 1         | 0.36%   |
| eMachines           | 1         | 0.36%   |
| BenQ                | 1         | 0.36%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                                                     | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Acer Aspire A315-31                                                                      | 6         | 2.18%   |
| Lenovo V330-15IKB 81AX                                                                   | 4         | 1.45%   |
| HP Notebook                                                                              | 4         | 1.45%   |
| Lenovo IdeaPad 330-15IKB 81DE                                                            | 3         | 1.09%   |
| ASUS X541NA                                                                              | 3         | 1.09%   |
| Unknown                                                                                  | 3         | 1.09%   |
| MSI CR500                                                                                | 2         | 0.73%   |
| Lenovo Legion Y530-15ICH 81FV                                                            | 2         | 0.73%   |
| Lenovo IdeaPad S540-14API 81NH                                                           | 2         | 0.73%   |
| Lenovo IdeaPad L340-15API 81LW                                                           | 2         | 0.73%   |
| Lenovo IdeaPad 5 14ARE05 81YM                                                            | 2         | 0.73%   |
| Lenovo IdeaPad 3 15IIL05 81WE                                                            | 2         | 0.73%   |
| Lenovo IdeaPad 110-15IBR 80T7                                                            | 2         | 0.73%   |
| Lenovo G500 20236                                                                        | 2         | 0.73%   |
| HP Pavilion Notebook                                                                     | 2         | 0.73%   |
| HP Laptop 15-ra0xx                                                                       | 2         | 0.73%   |
| HP Laptop 15-db1xxx                                                                      | 2         | 0.73%   |
| HP Laptop 15-db0xxx                                                                      | 2         | 0.73%   |
| HP G62                                                                                   | 2         | 0.73%   |
| HP 250 G5 Notebook PC                                                                    | 2         | 0.73%   |
| Fujitsu Siemens AMILO Li3710                                                             | 2         | 0.73%   |
| Dell Vostro 3500                                                                         | 2         | 0.73%   |
| Dell Latitude E5470                                                                      | 2         | 0.73%   |
| Dell Latitude 7490                                                                       | 2         | 0.73%   |
| Dell Inspiron 3542                                                                       | 2         | 0.73%   |
| Dell Inspiron 3537                                                                       | 2         | 0.73%   |
| ASUS X55A                                                                                | 2         | 0.73%   |
| ASUS X541NC                                                                              | 2         | 0.73%   |
| ASUS VivoBook_ASUSLaptop X580GD_N580GD                                                   | 2         | 0.73%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_X543MA                                               | 2         | 0.73%   |
| Apple MacBookPro8,1                                                                      | 2         | 0.73%   |
| Acer Aspire A315-51                                                                      | 2         | 0.73%   |
| Toshiba TECRA Z50-A                                                                      | 1         | 0.36%   |
| Toshiba Satellite Pro L650                                                               | 1         | 0.36%   |
| Toshiba Satellite L755                                                                   | 1         | 0.36%   |
| Toshiba Satellite L20                                                                    | 1         | 0.36%   |
| Toshiba Satellite C870-17H                                                               | 1         | 0.36%   |
| Toshiba Satellite C850-1H6                                                               | 1         | 0.36%   |
| Toshiba Satellite C650                                                                   | 1         | 0.36%   |
| Toshiba Satellite C55-C                                                                  | 1         | 0.36%   |
| Toshiba Satellite C55-B                                                                  | 1         | 0.36%   |
| Toshiba Satellite C55-A                                                                  | 1         | 0.36%   |
| Toshiba Satellite C50-B                                                                  | 1         | 0.36%   |
| Toshiba Satellite C50-A-1G3                                                              | 1         | 0.36%   |
| Toshiba QOSMIO F50                                                                       | 1         | 0.36%   |
| Sony VPCZ21X9E                                                                           | 1         | 0.36%   |
| Sony VGN-FE31Z                                                                           | 1         | 0.36%   |
| Samsung N250P/N145P                                                                      | 1         | 0.36%   |
| Samsung 350V5C/350V5X/350V4C/350V4X/351V5C/351V5X/351V4C/351V4X/3540VC/3540VX/3440VC/344 | 1         | 0.36%   |
| Razer Blade                                                                              | 1         | 0.36%   |
| Packard Bell EasyNote TS11HR                                                             | 1         | 0.36%   |
| MSI MS-16Y1                                                                              | 1         | 0.36%   |
| MSI GT70 2PC                                                                             | 1         | 0.36%   |
| MSI CR610                                                                                | 1         | 0.36%   |
| Medion X781X/X782X                                                                       | 1         | 0.36%   |
| Medion P6812                                                                             | 1         | 0.36%   |
| LG LW70-JJKG                                                                             | 1         | 0.36%   |
| Lenovo Yoga 300-11IBR 80M1                                                               | 1         | 0.36%   |
| Lenovo V310-15ISK 80SY                                                                   | 1         | 0.36%   |
| Lenovo V15-ADA 82C7                                                                      | 1         | 0.36%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 28        | 10.18%  |
| Lenovo IdeaPad        | 24        | 8.73%   |
| Lenovo ThinkPad       | 20        | 7.27%   |
| Dell Inspiron         | 19        | 6.91%   |
| HP Laptop             | 13        | 4.73%   |
| ASUS VivoBook         | 13        | 4.73%   |
| Toshiba Satellite     | 11        | 4%      |
| Dell Latitude         | 11        | 4%      |
| HP ProBook            | 8         | 2.91%   |
| HP Pavilion           | 6         | 2.18%   |
| HP EliteBook          | 5         | 1.82%   |
| HP 250                | 5         | 1.82%   |
| Fujitsu Siemens AMILO | 5         | 1.82%   |
| Lenovo V330-15IKB     | 4         | 1.45%   |
| Lenovo Legion         | 4         | 1.45%   |
| HP Notebook           | 4         | 1.45%   |
| Fujitsu LIFEBOOK      | 3         | 1.09%   |
| Dell Vostro           | 3         | 1.09%   |
| ASUS X541NA           | 3         | 1.09%   |
| Unknown               | 3         | 1.09%   |
| MSI CR500             | 2         | 0.73%   |
| Lenovo G500           | 2         | 0.73%   |
| HP G62                | 2         | 0.73%   |
| HP Compaq             | 2         | 0.73%   |
| Dell Precision        | 2         | 0.73%   |
| ASUS X55A             | 2         | 0.73%   |
| ASUS X541NC           | 2         | 0.73%   |
| ASUS TUF              | 2         | 0.73%   |
| Apple MacBookPro8     | 2         | 0.73%   |
| Toshiba TECRA         | 1         | 0.36%   |
| Toshiba QOSMIO        | 1         | 0.36%   |
| Sony VPCZ21X9E        | 1         | 0.36%   |
| Sony VGN-FE31Z        | 1         | 0.36%   |
| Samsung N250P         | 1         | 0.36%   |
| Samsung 350V5C        | 1         | 0.36%   |
| Razer Blade           | 1         | 0.36%   |
| Packard Bell EasyNote | 1         | 0.36%   |
| MSI MS-16Y1           | 1         | 0.36%   |
| MSI GT70              | 1         | 0.36%   |
| MSI CR610             | 1         | 0.36%   |
| Medion X781X          | 1         | 0.36%   |
| Medion P6812          | 1         | 0.36%   |
| LG LW70-JJKG          | 1         | 0.36%   |
| Lenovo Yoga           | 1         | 0.36%   |
| Lenovo V310-15ISK     | 1         | 0.36%   |
| Lenovo V15-ADA        | 1         | 0.36%   |
| Lenovo V130-14IGM     | 1         | 0.36%   |
| Lenovo V110-15AST     | 1         | 0.36%   |
| Lenovo ThinkBook      | 1         | 0.36%   |
| Lenovo G560           | 1         | 0.36%   |
| Lenovo G555           | 1         | 0.36%   |
| Lenovo G505           | 1         | 0.36%   |
| Lenovo G50-30         | 1         | 0.36%   |
| Lenovo B50-45         | 1         | 0.36%   |
| Lenovo 3000           | 1         | 0.36%   |
| IBM ThinkPad          | 1         | 0.36%   |
| HUAWEI NBLB-WAX9N     | 1         | 0.36%   |
| HP ZBook              | 1         | 0.36%   |
| HP Mini               | 1         | 0.36%   |
| HP 530                | 1         | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 37        | 13.45%  |
| 2017 | 28        | 10.18%  |
| 2019 | 24        | 8.73%   |
| 2011 | 24        | 8.73%   |
| 2020 | 23        | 8.36%   |
| 2016 | 22        | 8%      |
| 2013 | 19        | 6.91%   |
| 2012 | 16        | 5.82%   |
| 2010 | 16        | 5.82%   |
| 2014 | 15        | 5.45%   |
| 2015 | 12        | 4.36%   |
| 2008 | 12        | 4.36%   |
| 2009 | 8         | 2.91%   |
| 2007 | 7         | 2.55%   |
| 2006 | 5         | 1.82%   |
| 2021 | 4         | 1.45%   |
| 2005 | 2         | 0.73%   |
| 2022 | 1         | 0.36%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 275       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 252       | 90.32%  |
| Enabled  | 27        | 9.68%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 275       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 91        | 32.5%   |
| 4.01-8.0   | 71        | 25.36%  |
| 8.01-16.0  | 47        | 16.79%  |
| 16.01-24.0 | 33        | 11.79%  |
| 1.01-2.0   | 16        | 5.71%   |
| 2.01-3.0   | 10        | 3.57%   |
| 32.01-64.0 | 8         | 2.86%   |
| 24.01-32.0 | 3         | 1.07%   |
| 0.51-1.0   | 1         | 0.36%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 117       | 38.11%  |
| 2.01-3.0  | 70        | 22.8%   |
| 0.51-1.0  | 46        | 14.98%  |
| 3.01-4.0  | 37        | 12.05%  |
| 4.01-8.0  | 29        | 9.45%   |
| 8.01-16.0 | 7         | 2.28%   |
| 0.01-0.5  | 1         | 0.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 215       | 76.24%  |
| 2      | 55        | 19.5%   |
| 3      | 6         | 2.13%   |
| 0      | 6         | 2.13%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 152       | 54.68%  |
| Yes       | 126       | 45.32%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 245       | 89.09%  |
| No        | 30        | 10.91%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 275       | 99.64%  |
| No        | 1         | 0.36%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 223       | 80.8%   |
| No        | 53        | 19.2%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Serbia  | 275       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Belgrade           | 180       | 61.43%  |
| Novi Sad           | 30        | 10.24%  |
| Niš               | 14        | 4.78%   |
| Novi Belgrade      | 4         | 1.37%   |
| Leskovac           | 4         | 1.37%   |
| Zrenjanin          | 3         | 1.02%   |
| Subotica           | 3         | 1.02%   |
| Senta              | 3         | 1.02%   |
| Savski Venac       | 3         | 1.02%   |
| Pančevo           | 3         | 1.02%   |
| Lozovik            | 3         | 1.02%   |
| Kovin              | 3         | 1.02%   |
| Varvarin           | 2         | 0.68%   |
| Novi Karlovci      | 2         | 0.68%   |
| Kragujevac         | 2         | 0.68%   |
| Branicevo          | 2         | 0.68%   |
| Becej              | 2         | 0.68%   |
| Backa Topola       | 2         | 0.68%   |
| Valjevo            | 1         | 0.34%   |
| Užice             | 1         | 0.34%   |
| UÅ¾ice           | 1         | 0.34%   |
| Trstenik           | 1         | 0.34%   |
| Stara Pazova       | 1         | 0.34%   |
| Sabac              | 1         | 0.34%   |
| Ruma               | 1         | 0.34%   |
| Ripanj             | 1         | 0.34%   |
| Pukovac            | 1         | 0.34%   |
| Požarevac         | 1         | 0.34%   |
| New Belgrade       | 1         | 0.34%   |
| Lazarevac          | 1         | 0.34%   |
| Kruševac          | 1         | 0.34%   |
| Kraljevo           | 1         | 0.34%   |
| Jagodina           | 1         | 0.34%   |
| Guca               | 1         | 0.34%   |
| Grocka             | 1         | 0.34%   |
| Cuprija            | 1         | 0.34%   |
| Cibukovac          | 1         | 0.34%   |
| Čačak            | 1         | 0.34%   |
| Bor                | 1         | 0.34%   |
| Boljevac           | 1         | 0.34%   |
| Beloinje           | 1         | 0.34%   |
| Basaid             | 1         | 0.34%   |
| Banatsko Novo Selo | 1         | 0.34%   |
| Backi Petrovac     | 1         | 0.34%   |
| Arangelovac        | 1         | 0.34%   |
| Aldinac            | 1         | 0.34%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| WDC                     | 45        | 65     | 14.06%  |
| Seagate                 | 44        | 51     | 13.75%  |
| Toshiba                 | 43        | 53     | 13.44%  |
| Samsung Electronics     | 33        | 44     | 10.31%  |
| Kingston                | 22        | 23     | 6.88%   |
| Hitachi                 | 18        | 18     | 5.63%   |
| SK Hynix                | 15        | 18     | 4.69%   |
| SanDisk                 | 12        | 18     | 3.75%   |
| Unknown                 | 11        | 12     | 3.44%   |
| Intel                   | 10        | 19     | 3.13%   |
| Patriot                 | 9         | 11     | 2.81%   |
| HGST                    | 8         | 15     | 2.5%    |
| Micron Technology       | 7         | 7      | 2.19%   |
| Fujitsu                 | 5         | 5      | 1.56%   |
| SPCC                    | 4         | 5      | 1.25%   |
| Transcend               | 3         | 3      | 0.94%   |
| KIOXIA                  | 3         | 3      | 0.94%   |
| Gigabyte Technology     | 3         | 3      | 0.94%   |
| GeIL                    | 3         | 3      | 0.94%   |
| A-DATA Technology       | 3         | 3      | 0.94%   |
| Union Memory            | 2         | 2      | 0.63%   |
| Phison                  | 2         | 2      | 0.63%   |
| LITEON                  | 2         | 3      | 0.63%   |
| Crucial                 | 2         | 2      | 0.63%   |
| Verbatim                | 1         | 1      | 0.31%   |
| Union Memory (Shenzhen) | 1         | 1      | 0.31%   |
| SSSTC                   | 1         | 1      | 0.31%   |
| Realtek Semiconductor   | 1         | 4      | 0.31%   |
| PNY                     | 1         | 1      | 0.31%   |
| Netac                   | 1         | 1      | 0.31%   |
| JMicron                 | 1         | 1      | 0.31%   |
| IBM/Hitachi             | 1         | 1      | 0.31%   |
| HUAWEI                  | 1         | 1      | 0.31%   |
| Biostar                 | 1         | 1      | 0.31%   |
| AMD                     | 1         | 1      | 0.31%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB          | 15        | 4.64%   |
| Toshiba MQ01ABF050 500GB                | 12        | 3.72%   |
| Seagate ST500LT012-1DG142 500GB         | 8         | 2.48%   |
| Toshiba MQ01ABD100 1TB                  | 5         | 1.55%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 5         | 1.55%   |
| Kingston SA400S37240G 240GB SSD         | 5         | 1.55%   |
| Toshiba MQ04ABF100 1TB                  | 4         | 1.24%   |
| Seagate ST500LT012-9WS142 500GB         | 4         | 1.24%   |
| Kingston SA400S37120G 120GB SSD         | 4         | 1.24%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB    | 3         | 0.93%   |
| SK Hynix NVMe SSD Drive 256GB           | 3         | 0.93%   |
| Sandisk NVMe SSD Drive 256GB            | 3         | 0.93%   |
| Samsung NVMe SSD Drive 256GB            | 3         | 0.93%   |
| Kingston SA400S37480G 480GB SSD         | 3         | 0.93%   |
| Kingston RBUSC180DS37256GJ 256GB SSD    | 3         | 0.93%   |
| Hitachi HTS545050A7E380 500GB           | 3         | 0.93%   |
| GeIL R3_128GB                           | 3         | 0.93%   |
| WDC WD5000LPVX-75V0TT0 500GB            | 2         | 0.62%   |
| WDC WD5000LPCX-80VHAT1 500GB            | 2         | 0.62%   |
| WDC WD5000LPCX-24VHAT0 500GB            | 2         | 0.62%   |
| WDC WD3200BEVT-22ZCT0 320GB             | 2         | 0.62%   |
| WDC WD3200BEVT-22A23T0 320GB            | 2         | 0.62%   |
| WDC WD2500BEVS-22UST0 250GB             | 2         | 0.62%   |
| WDC WD1200BEVS-22UST0 120GB             | 2         | 0.62%   |
| WDC WD10SPZX-24Z10 1TB                  | 2         | 0.62%   |
| WDC WD10SPZX-21Z10T0 1TB                | 2         | 0.62%   |
| WDC PC SN530 SDBPNPZ-256G-1002 256GB    | 2         | 0.62%   |
| Unknown MMC Card  32GB                  | 2         | 0.62%   |
| Union Memory UMIS RPJTJ512MEE1OWX 512GB | 2         | 0.62%   |
| Toshiba NVMe SSD Drive 512GB            | 2         | 0.62%   |
| Toshiba MQ01ABD050 500GB                | 2         | 0.62%   |
| Toshiba MK1637GSX 160GB                 | 2         | 0.62%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD     | 2         | 0.62%   |
| SK Hynix HFS128G32TNF-N3A0A 128GB SSD   | 2         | 0.62%   |
| Seagate ST9500325AS 500GB               | 2         | 0.62%   |
| SanDisk SD9SN8W256G1014 256GB SSD       | 2         | 0.62%   |
| Sandisk NVMe SSD Drive 512GB            | 2         | 0.62%   |
| Samsung SSD 860 EVO M.2 500GB           | 2         | 0.62%   |
| Samsung SSD 860 EVO 500GB               | 2         | 0.62%   |
| Samsung SSD 850 EVO 250GB               | 2         | 0.62%   |
| Samsung MZNLN128HAHQ-000H1 128GB SSD    | 2         | 0.62%   |
| Patriot Burst 240GB SSD                 | 2         | 0.62%   |
| Patriot Blast 240GB SSD                 | 2         | 0.62%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD     | 2         | 0.62%   |
| KIOXIA KBG40ZNS512G NVMe 512GB          | 2         | 0.62%   |
| Intel SSDPEKKW256G7 256GB               | 2         | 0.62%   |
| Hitachi HTS547575A9E384 752GB           | 2         | 0.62%   |
| Hitachi HTS545032B9A300 320GB           | 2         | 0.62%   |
| Hitachi HTS543216L9A300 160GB           | 2         | 0.62%   |
| HGST HTS721010A9E630 1TB                | 2         | 0.62%   |
| HGST HTS545050A7E680 500GB              | 2         | 0.62%   |
| Gigabyte GP-GSTFS31240GNTD 240GB        | 2         | 0.62%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD        | 1         | 0.31%   |
| WDC WD7500BPVX-60JC3T0 752GB            | 1         | 0.31%   |
| WDC WD7500BPKX-75HPJT0 752GB            | 1         | 0.31%   |
| WDC WD5000LPLX-00ZNTT0 500GB            | 1         | 0.31%   |
| WDC WD5000LPCX-75VHAT0 500GB            | 1         | 0.31%   |
| WDC WD5000LPCX-60VHAT0 500GB            | 1         | 0.31%   |
| WDC WD5000LPCX-21VHAT0 500GB            | 1         | 0.31%   |
| WDC WD5000BPKX-00HPJT0 500GB            | 1         | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 44        | 51     | 28.76%  |
| WDC                 | 38        | 58     | 24.84%  |
| Toshiba             | 37        | 46     | 24.18%  |
| Hitachi             | 18        | 18     | 11.76%  |
| HGST                | 8         | 15     | 5.23%   |
| Fujitsu             | 5         | 5      | 3.27%   |
| Unknown             | 1         | 1      | 0.65%   |
| Samsung Electronics | 1         | 2      | 0.65%   |
| IBM/Hitachi         | 1         | 1      | 0.65%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 21        | 26     | 22.58%  |
| Kingston            | 19        | 20     | 20.43%  |
| Patriot             | 9         | 11     | 9.68%   |
| SanDisk             | 6         | 10     | 6.45%   |
| SPCC                | 4         | 5      | 4.3%    |
| Micron Technology   | 4         | 4      | 4.3%    |
| Transcend           | 3         | 3      | 3.23%   |
| SK Hynix            | 3         | 3      | 3.23%   |
| Intel               | 3         | 4      | 3.23%   |
| GeIL                | 3         | 3      | 3.23%   |
| Toshiba             | 2         | 2      | 2.15%   |
| LITEON              | 2         | 3      | 2.15%   |
| Gigabyte Technology | 2         | 2      | 2.15%   |
| Crucial             | 2         | 2      | 2.15%   |
| A-DATA Technology   | 2         | 2      | 2.15%   |
| WDC                 | 1         | 1      | 1.08%   |
| Verbatim            | 1         | 1      | 1.08%   |
| SSSTC               | 1         | 1      | 1.08%   |
| PNY                 | 1         | 1      | 1.08%   |
| Netac               | 1         | 1      | 1.08%   |
| JMicron             | 1         | 1      | 1.08%   |
| Biostar             | 1         | 1      | 1.08%   |
| AMD                 | 1         | 1      | 1.08%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 153       | 197    | 49.04%  |
| SSD     | 86        | 108    | 27.56%  |
| NVMe    | 63        | 86     | 20.19%  |
| MMC     | 9         | 10     | 2.88%   |
| Unknown | 1         | 1      | 0.32%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 216       | 303    | 74.23%  |
| NVMe | 63        | 86     | 21.65%  |
| MMC  | 9         | 10     | 3.09%   |
| SAS  | 3         | 3      | 1.03%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 170       | 215    | 73.28%  |
| 0.51-1.0   | 60        | 86     | 25.86%  |
| 1.01-2.0   | 2         | 4      | 0.86%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 86        | 28.96%  |
| 251-500        | 84        | 28.28%  |
| 501-1000       | 36        | 12.12%  |
| 1-20           | 27        | 9.09%   |
| 51-100         | 24        | 8.08%   |
| 21-50          | 19        | 6.4%    |
| Unknown        | 12        | 4.04%   |
| 1001-2000      | 6         | 2.02%   |
| 2001-3000      | 2         | 0.67%   |
| More than 3000 | 1         | 0.34%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 133       | 43.61%  |
| 21-50     | 58        | 19.02%  |
| 51-100    | 37        | 12.13%  |
| 101-250   | 36        | 11.8%   |
| 251-500   | 20        | 6.56%   |
| Unknown   | 12        | 3.93%   |
| 501-1000  | 7         | 2.3%    |
| 1001-2000 | 2         | 0.66%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Notebooks | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABF050 500GB                | 2         | 2      | 9.52%   |
| WDC WD5000BEVT-24A0RT0 500GB            | 1         | 1      | 4.76%   |
| Toshiba MQ01ABD032 320GB                | 1         | 1      | 4.76%   |
| Toshiba MK1637GSX 160GB                 | 1         | 1      | 4.76%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD | 1         | 1      | 4.76%   |
| SPCC Solid State DiskB27 32GB           | 1         | 1      | 4.76%   |
| Seagate ST980813AS 80GB                 | 1         | 1      | 4.76%   |
| Seagate ST9250827AS 250GB               | 1         | 1      | 4.76%   |
| Seagate ST9120822AS 120GB               | 1         | 1      | 4.76%   |
| Seagate ST750LM022 HN-M750MBB 752GB     | 1         | 1      | 4.76%   |
| Seagate ST500LT012-9WS142 500GB         | 1         | 1      | 4.76%   |
| Seagate ST500LT012-1DG142 500GB         | 1         | 2      | 4.76%   |
| Samsung Electronics HM120JI 120GB       | 1         | 2      | 4.76%   |
| Hitachi HTS722080K9A300 80GB            | 1         | 1      | 4.76%   |
| Hitachi HTS545050A7E380 500GB           | 1         | 1      | 4.76%   |
| Hitachi HTS541612J9SA00 120GB           | 1         | 1      | 4.76%   |
| HGST HTS725050A7E630 500GB              | 1         | 5      | 4.76%   |
| HGST HTS721010A9E630 1TB                | 1         | 1      | 4.76%   |
| Fujitsu MHZ2160BH G1 160GB              | 1         | 1      | 4.76%   |
| Fujitsu MHW2160BH PL 160GB              | 1         | 1      | 4.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 7      | 28.57%  |
| Toshiba             | 5         | 5      | 23.81%  |
| Hitachi             | 3         | 3      | 14.29%  |
| HGST                | 2         | 6      | 9.52%   |
| Fujitsu             | 2         | 2      | 9.52%   |
| WDC                 | 1         | 1      | 4.76%   |
| SPCC                | 1         | 1      | 4.76%   |
| Samsung Electronics | 1         | 2      | 4.76%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 7      | 31.58%  |
| Toshiba             | 4         | 4      | 21.05%  |
| Hitachi             | 3         | 3      | 15.79%  |
| HGST                | 2         | 6      | 10.53%  |
| Fujitsu             | 2         | 2      | 10.53%  |
| WDC                 | 1         | 1      | 5.26%   |
| Samsung Electronics | 1         | 2      | 5.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 19        | 25     | 90.48%  |
| SSD  | 2         | 2      | 9.52%   |

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
| Detected | 172       | 272    | 60.99%  |
| Works    | 89        | 103    | 31.56%  |
| Malfunc  | 21        | 27     | 7.45%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 213       | 67.62%  |
| AMD                          | 33        | 10.48%  |
| Samsung Electronics          | 16        | 5.08%   |
| SK Hynix                     | 12        | 3.81%   |
| Sandisk                      | 12        | 3.81%   |
| Toshiba America Info Systems | 4         | 1.27%   |
| Nvidia                       | 4         | 1.27%   |
| KIOXIA                       | 4         | 1.27%   |
| Union Memory (Shenzhen)      | 3         | 0.95%   |
| Phison Electronics           | 3         | 0.95%   |
| Micron Technology            | 3         | 0.95%   |
| Kingston Technology Company  | 3         | 0.95%   |
| VIA Technologies             | 1         | 0.32%   |
| Silicon Image                | 1         | 0.32%   |
| Realtek Semiconductor        | 1         | 0.32%   |
| JMicron Technology           | 1         | 0.32%   |
| ADATA Technology             | 1         | 0.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 27        | 7.94%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 26        | 7.65%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 21        | 6.18%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 20        | 5.88%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 17        | 5%      |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 13        | 3.82%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 9         | 2.65%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 8         | 2.35%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 8         | 2.35%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 8         | 2.35%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 8         | 2.35%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 8         | 2.35%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 8         | 2.35%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 8         | 2.35%   |
| SK Hynix BC511                                                                   | 6         | 1.76%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 6         | 1.76%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 6         | 1.76%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 6         | 1.76%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 6         | 1.76%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 6         | 1.76%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 5         | 1.47%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 5         | 1.47%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 5         | 1.47%   |
| Sandisk Non-Volatile memory controller                                           | 4         | 1.18%   |
| KIOXIA Non-Volatile memory controller                                            | 4         | 1.18%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 4         | 1.18%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 4         | 1.18%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 3         | 0.88%   |
| SK Hynix Non-Volatile memory controller                                          | 3         | 0.88%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 3         | 0.88%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 3         | 0.88%   |
| Samsung NVMe SSD Controller 980                                                  | 3         | 0.88%   |
| Nvidia MCP79 AHCI Controller                                                     | 3         | 0.88%   |
| Micron Non-Volatile memory controller                                            | 3         | 0.88%   |
| Intel SSD 660P Series                                                            | 3         | 0.88%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3         | 0.88%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 3         | 0.88%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 3         | 0.88%   |
| Toshiba America Info Systems NVMe Controller                                     | 2         | 0.59%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 2         | 0.59%   |
| Sandisk PC SN520 NVMe SSD                                                        | 2         | 0.59%   |
| Phison PS5013 E13 NVMe Controller                                                | 2         | 0.59%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 2         | 0.59%   |
| Intel SATA Controller [RAID mode]                                                | 2         | 0.59%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 0.59%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 0.59%   |
| Intel 82801FBM (ICH6M) SATA Controller                                           | 2         | 0.59%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 2         | 0.59%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 1         | 0.29%   |
| VIA VT8237A SATA 2-Port Controller                                               | 1         | 0.29%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 1         | 0.29%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 0.29%   |
| Silicon Image SiI 3531 [SATALink/SATARaid] Serial ATA Controller                 | 1         | 0.29%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 0.29%   |
| Realtek RTS5763DL NVMe SSD Controller                                            | 1         | 0.29%   |
| Phison E12 NVMe Controller                                                       | 1         | 0.29%   |
| Nvidia MCP79 SATA Controller                                                     | 1         | 0.29%   |
| Nvidia MCP67 IDE Controller                                                      | 1         | 0.29%   |
| Nvidia MCP67 AHCI Controller                                                     | 1         | 0.29%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.29%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 219       | 66.16%  |
| NVMe | 67        | 20.24%  |
| IDE  | 25        | 7.55%   |
| RAID | 20        | 6.04%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 232       | 84.36%  |
| AMD    | 43        | 15.64%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz             | 6         | 2.18%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 6         | 2.18%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 5         | 1.82%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 1.82%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 1.82%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 5         | 1.82%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 5         | 1.82%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 5         | 1.82%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 5         | 1.82%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 1.45%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 4         | 1.45%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 4         | 1.45%   |
| Intel Celeron CPU 1000M @ 1.80GHz             | 4         | 1.45%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 4         | 1.45%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 4         | 1.45%   |
| Intel Pentium M processor 1.86GHz             | 3         | 1.09%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 3         | 1.09%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 1.09%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 3         | 1.09%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 3         | 1.09%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 3         | 1.09%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 3         | 1.09%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 3         | 1.09%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 3         | 1.09%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 2         | 0.73%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 2         | 0.73%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 2         | 0.73%   |
| Intel Pentium CPU B950 @ 2.10GHz              | 2         | 0.73%   |
| Intel Pentium CPU 4417U @ 2.30GHz             | 2         | 0.73%   |
| Intel Pentium CPU 3825U @ 1.90GHz             | 2         | 0.73%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 2         | 0.73%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 2         | 0.73%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 2         | 0.73%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 0.73%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 0.73%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 0.73%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 0.73%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz            | 2         | 0.73%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 2         | 0.73%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 0.73%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 0.73%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 2         | 0.73%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 0.73%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 0.73%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 0.73%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 2         | 0.73%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 0.73%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 2         | 0.73%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 2         | 0.73%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 2         | 0.73%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 0.73%   |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 2         | 0.73%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 2         | 0.73%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 2         | 0.73%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 2         | 0.73%   |
| Intel Core 2 CPU T5600 @ 1.83GHz              | 2         | 0.73%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 2         | 0.73%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 0.73%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 0.73%   |
| Intel Atom CPU N455 @ 1.66GHz                 | 2         | 0.73%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 55        | 20%     |
| Intel Core i5           | 50        | 18.18%  |
| Intel Core i3           | 31        | 11.27%  |
| Intel Celeron           | 30        | 10.91%  |
| Intel Pentium           | 26        | 9.45%   |
| AMD Ryzen 5             | 14        | 5.09%   |
| Intel Core 2 Duo        | 12        | 4.36%   |
| AMD Ryzen 7             | 9         | 3.27%   |
| Intel Atom              | 7         | 2.55%   |
| Other                   | 6         | 2.18%   |
| Intel Pentium M         | 3         | 1.09%   |
| Intel Pentium Dual      | 3         | 1.09%   |
| Intel Core 2            | 3         | 1.09%   |
| AMD Ryzen 3             | 3         | 1.09%   |
| AMD A8                  | 3         | 1.09%   |
| Intel Pentium Silver    | 2         | 0.73%   |
| Intel Pentium Dual-Core | 2         | 0.73%   |
| Intel Genuine           | 2         | 0.73%   |
| AMD Athlon X2           | 2         | 0.73%   |
| AMD Athlon II Dual-Core | 2         | 0.73%   |
| AMD A4                  | 2         | 0.73%   |
| Intel Celeron M         | 1         | 0.36%   |
| AMD V120                | 1         | 0.36%   |
| AMD Turion 64 X2 Mobile | 1         | 0.36%   |
| AMD Phenom II           | 1         | 0.36%   |
| AMD E2                  | 1         | 0.36%   |
| AMD E1                  | 1         | 0.36%   |
| AMD Athlon II           | 1         | 0.36%   |
| AMD A6                  | 1         | 0.36%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 149       | 54.18%  |
| 4      | 94        | 34.18%  |
| 6      | 14        | 5.09%   |
| 1      | 13        | 4.73%   |
| 8      | 5         | 1.82%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 275       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 172       | 62.55%  |
| 1      | 103       | 37.45%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 257       | 93.12%  |
| Unknown        | 11        | 3.99%   |
| 32-bit         | 8         | 2.9%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 42        | 14.63%  |
| 0x206a7    | 26        | 9.06%   |
| 0x806ea    | 15        | 5.23%   |
| 0x306a9    | 14        | 4.88%   |
| 0x506c9    | 12        | 4.18%   |
| 0x406e3    | 12        | 4.18%   |
| 0x906ea    | 10        | 3.48%   |
| 0x806e9    | 8         | 2.79%   |
| 0x306d4    | 8         | 2.79%   |
| 0x706e5    | 7         | 2.44%   |
| 0x6fd      | 7         | 2.44%   |
| 0x40651    | 7         | 2.44%   |
| 0x08108102 | 7         | 2.44%   |
| 0x906e9    | 6         | 2.09%   |
| 0x806ec    | 6         | 2.09%   |
| 0x406c4    | 6         | 2.09%   |
| 0x806c1    | 5         | 1.74%   |
| 0x506e3    | 5         | 1.74%   |
| 0x306c3    | 5         | 1.74%   |
| 0x30678    | 5         | 1.74%   |
| 0x10676    | 5         | 1.74%   |
| 0x08108109 | 5         | 1.74%   |
| 0x806eb    | 4         | 1.39%   |
| 0x706a8    | 3         | 1.05%   |
| 0x706a1    | 3         | 1.05%   |
| 0x6d8      | 3         | 1.05%   |
| 0x30673    | 3         | 1.05%   |
| 0x20655    | 3         | 1.05%   |
| 0x106ca    | 3         | 1.05%   |
| 0x1067a    | 3         | 1.05%   |
| 0x08608103 | 3         | 1.05%   |
| 0x0810100b | 3         | 1.05%   |
| 0xa0652    | 2         | 0.7%    |
| 0x6e8      | 2         | 0.7%    |
| 0x406c3    | 2         | 0.7%    |
| 0x20652    | 2         | 0.7%    |
| 0x106c2    | 2         | 0.7%    |
| 0x08600104 | 2         | 0.7%    |
| 0x07030104 | 2         | 0.7%    |
| 0x06006704 | 2         | 0.7%    |
| 0x010000c8 | 2         | 0.7%    |
| 0x906ed    | 1         | 0.35%   |
| 0x6fb      | 1         | 0.35%   |
| 0x6fa      | 1         | 0.35%   |
| 0x6f6      | 1         | 0.35%   |
| 0x6ec      | 1         | 0.35%   |
| 0x08608102 | 1         | 0.35%   |
| 0x08600106 | 1         | 0.35%   |
| 0x08600102 | 1         | 0.35%   |
| 0x08200103 | 1         | 0.35%   |
| 0x08101007 | 1         | 0.35%   |
| 0x07030105 | 1         | 0.35%   |
| 0x0700010f | 1         | 0.35%   |
| 0x06001119 | 1         | 0.35%   |
| 0x02000057 | 1         | 0.35%   |
| 0x02000032 | 1         | 0.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 52        | 18.91%  |
| SandyBridge     | 29        | 10.55%  |
| Skylake         | 18        | 6.55%   |
| Silvermont      | 17        | 6.18%   |
| Haswell         | 17        | 6.18%   |
| IvyBridge       | 15        | 5.45%   |
| Goldmont        | 13        | 4.73%   |
| Core            | 13        | 4.73%   |
| Zen+            | 12        | 4.36%   |
| Westmere        | 9         | 3.27%   |
| Broadwell       | 9         | 3.27%   |
| Penryn          | 8         | 2.91%   |
| IceLake         | 7         | 2.55%   |
| Zen             | 6         | 2.18%   |
| P6              | 6         | 2.18%   |
| Goldmont plus   | 6         | 2.18%   |
| Zen 2           | 5         | 1.82%   |
| TigerLake       | 5         | 1.82%   |
| K10             | 5         | 1.82%   |
| Bonnell         | 5         | 1.82%   |
| Unknown         | 4         | 1.45%   |
| Puma            | 3         | 1.09%   |
| CometLake       | 3         | 1.09%   |
| Piledriver      | 2         | 0.73%   |
| K8 & K10 hybrid | 2         | 0.73%   |
| Excavator       | 2         | 0.73%   |
| K8 Hammer       | 1         | 0.36%   |
| Jaguar          | 1         | 0.36%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 210       | 58.33%  |
| Nvidia           | 75        | 20.83%  |
| AMD              | 74        | 20.56%  |
| VIA Technologies | 1         | 0.28%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 26        | 6.95%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 15        | 4.01%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 13        | 3.48%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 12        | 3.21%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 12        | 3.21%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 11        | 2.94%   |
| Intel UHD Graphics 620                                                                   | 11        | 2.94%   |
| Intel HD Graphics 620                                                                    | 9         | 2.41%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9         | 2.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 9         | 2.41%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 8         | 2.14%   |
| Intel HD Graphics 500                                                                    | 8         | 2.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 2.14%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 8         | 2.14%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 8         | 2.14%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 7         | 1.87%   |
| Intel HD Graphics 5500                                                                   | 7         | 1.87%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 1.6%    |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 1.6%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 1.34%   |
| Intel HD Graphics 630                                                                    | 5         | 1.34%   |
| Intel HD Graphics 530                                                                    | 5         | 1.34%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 5         | 1.34%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 5         | 1.34%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 5         | 1.34%   |
| AMD Renoir                                                                               | 5         | 1.34%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 5         | 1.34%   |
| Nvidia GP108M [GeForce MX150]                                                            | 4         | 1.07%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 1.07%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 1.07%   |
| AMD Lucienne                                                                             | 4         | 1.07%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.8%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 0.8%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 0.8%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 0.8%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 0.8%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 3         | 0.8%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 0.8%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 0.8%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 3         | 0.8%    |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 3         | 0.8%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.53%   |
| Nvidia MCP79 [GeForce 8200M G]                                                           | 2         | 0.53%   |
| Nvidia GP108M [GeForce MX330]                                                            | 2         | 0.53%   |
| Nvidia GP108M [GeForce MX230]                                                            | 2         | 0.53%   |
| Nvidia GM108M [GeForce MX110]                                                            | 2         | 0.53%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 2         | 0.53%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 2         | 0.53%   |
| Nvidia GM107GLM [Quadro M2000M]                                                          | 2         | 0.53%   |
| Nvidia GK107M [GeForce 810M]                                                             | 2         | 0.53%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 2         | 0.53%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 2         | 0.53%   |
| Intel HD Graphics                                                                        | 2         | 0.53%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 0.53%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.53%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 2         | 0.53%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 0.53%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                        | 2         | 0.53%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 0.53%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                                         | 2         | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 131       | 47.29%  |
| Intel + Nvidia | 58        | 20.94%  |
| 1 x AMD        | 41        | 14.8%   |
| Intel + AMD    | 23        | 8.3%    |
| 1 x Nvidia     | 13        | 4.69%   |
| 2 x AMD        | 6         | 2.17%   |
| AMD + Nvidia   | 4         | 1.44%   |
| 1 x VIA        | 1         | 0.36%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 241       | 86.07%  |
| Proprietary | 29        | 10.36%  |
| Unknown     | 10        | 3.57%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 156       | 54.93%  |
| 1.01-2.0   | 56        | 19.72%  |
| 0.01-0.5   | 36        | 12.68%  |
| 3.01-4.0   | 24        | 8.45%   |
| 0.51-1.0   | 12        | 4.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 67        | 21.68%  |
| BOE                     | 47        | 15.21%  |
| LG Display              | 46        | 14.89%  |
| Chimei Innolux          | 41        | 13.27%  |
| Samsung Electronics     | 31        | 10.03%  |
| Lenovo                  | 8         | 2.59%   |
| Dell                    | 8         | 2.59%   |
| Chi Mei Optoelectronics | 8         | 2.59%   |
| PANDA                   | 6         | 1.94%   |
| Philips                 | 5         | 1.62%   |
| LG Philips              | 5         | 1.62%   |
| Hewlett-Packard         | 5         | 1.62%   |
| CPT                     | 4         | 1.29%   |
| Apple                   | 4         | 1.29%   |
| Sony                    | 3         | 0.97%   |
| Sharp                   | 3         | 0.97%   |
| BenQ                    | 3         | 0.97%   |
| InfoVision              | 2         | 0.65%   |
| Goldstar                | 2         | 0.65%   |
| ViewSonic               | 1         | 0.32%   |
| Unknown                 | 1         | 0.32%   |
| Toshiba                 | 1         | 0.32%   |
| SKY                     | 1         | 0.32%   |
| Seiko/Epson             | 1         | 0.32%   |
| LPL                     | 1         | 0.32%   |
| InnoLux Display         | 1         | 0.32%   |
| Iiyama                  | 1         | 0.32%   |
| HannStar                | 1         | 0.32%   |
| ASUSTek Computer        | 1         | 0.32%   |
| Ancor Communications    | 1         | 0.32%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 15        | 4.82%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 7         | 2.25%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 7         | 2.25%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 6         | 1.93%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 5         | 1.61%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 4         | 1.29%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 4         | 1.29%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 4         | 1.29%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 4         | 1.29%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch            | 3         | 0.96%   |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch         | 3         | 0.96%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 3         | 0.96%   |
| BOE LCD Monitor BOE07A3 1920x1080 344x193mm 15.5-inch                    | 3         | 0.96%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 3         | 0.96%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 3         | 0.96%   |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch     | 2         | 0.64%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch     | 2         | 0.64%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch    | 2         | 0.64%   |
| PANDA LCD Monitor NCP006E 1920x1080 344x194mm 15.5-inch                  | 2         | 0.64%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch             | 2         | 0.64%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 2         | 0.64%   |
| LG Display LCD Monitor LGD0519 1920x1080 344x194mm 15.5-inch             | 2         | 0.64%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 2         | 0.64%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 2         | 0.64%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 2         | 0.64%   |
| Lenovo L24q-10 LEN65CF 2560x1440 527x296mm 23.8-inch                     | 2         | 0.64%   |
| Dell U2412M DELA079 1920x1200 518x324mm 24.1-inch                        | 2         | 0.64%   |
| Dell P2417H DELA0DC 1920x1080 527x296mm 23.8-inch                        | 2         | 0.64%   |
| CPT LCD Monitor CPT14BF 1366x768 344x193mm 15.5-inch                     | 2         | 0.64%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch         | 2         | 0.64%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 2         | 0.64%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 340x190mm 15.3-inch          | 2         | 0.64%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 340x190mm 15.3-inch          | 2         | 0.64%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 2         | 0.64%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 0.64%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 2         | 0.64%   |
| BOE LCD Monitor BOE07CB 1920x1080 344x193mm 15.5-inch                    | 2         | 0.64%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 2         | 0.64%   |
| BOE LCD Monitor BOE06FB 1920x1080 344x194mm 15.5-inch                    | 2         | 0.64%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 2         | 0.64%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 2         | 0.64%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 2         | 0.64%   |
| AU Optronics LCD Monitor AUO312C 1366x768 293x164mm 13.2-inch            | 2         | 0.64%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 2         | 0.64%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 2         | 0.64%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch           | 2         | 0.64%   |
| ViewSonic VX2370 SERIES VSC342C 1920x1080 509x286mm 23.0-inch            | 1         | 0.32%   |
| Unknown LCD Monitor SAMSUNG                                              | 1         | 0.32%   |
| Toshiba TV TSB0108 1920x540                                              | 1         | 0.32%   |
| Sony TV SNY5803 1360x768                                                 | 1         | 0.32%   |
| Sony TV SNY4402 1360x768                                                 | 1         | 0.32%   |
| Sony Nvidia Defaul t Flat Panel SNY06FA 1600x900 360x200mm 16.2-inch     | 1         | 0.32%   |
| SKY TV-monitor SKY0402 1920x1080 885x498mm 40.0-inch                     | 1         | 0.32%   |
| Sharp LQ173M1JW04 SHP14E1 1920x1080 382x215mm 17.3-inch                  | 1         | 0.32%   |
| Sharp LCD Monitor SHP143B 3840x2160 350x190mm 15.7-inch                  | 1         | 0.32%   |
| Sharp LCD Monitor SHP13B4 1024x768 304x228mm 15.0-inch                   | 1         | 0.32%   |
| Seiko/Epson LCD Monitor 3280x1080                                        | 1         | 0.32%   |
| Samsung Electronics SyncMaster SAM0593 1920x1080 477x268mm 21.5-inch     | 1         | 0.32%   |
| Samsung Electronics S32D850 SAM0BCC 2560x1440 708x398mm 32.0-inch        | 1         | 0.32%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 521x293mm 23.5-inch        | 1         | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 135       | 46.71%  |
| 1366x768 (WXGA)    | 107       | 37.02%  |
| 1280x800 (WXGA)    | 12        | 4.15%   |
| 1600x900 (HD+)     | 7         | 2.42%   |
| 2560x1440 (QHD)    | 4         | 1.38%   |
| 1360x768           | 4         | 1.38%   |
| 1920x1200 (WUXGA)  | 3         | 1.04%   |
| 1680x1050 (WSXGA+) | 3         | 1.04%   |
| 1440x900 (WXGA+)   | 3         | 1.04%   |
| 1024x600           | 3         | 1.04%   |
| 1024x768 (XGA)     | 2         | 0.69%   |
| 3840x2160 (4K)     | 1         | 0.35%   |
| 3280x1080          | 1         | 0.35%   |
| 1920x540           | 1         | 0.35%   |
| 1680x945           | 1         | 0.35%   |
| 1280x1024 (SXGA)   | 1         | 0.35%   |
| Unknown            | 1         | 0.35%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 188       | 61.04%  |
| 13      | 27        | 8.77%   |
| 17      | 17        | 5.52%   |
| 14      | 16        | 5.19%   |
| 24      | 13        | 4.22%   |
| 23      | 9         | 2.92%   |
| 21      | 6         | 1.95%   |
| 27      | 5         | 1.62%   |
| 11      | 5         | 1.62%   |
| Unknown | 5         | 1.62%   |
| 72      | 3         | 0.97%   |
| 12      | 3         | 0.97%   |
| 31      | 2         | 0.65%   |
| 10      | 2         | 0.65%   |
| 46      | 1         | 0.32%   |
| 40      | 1         | 0.32%   |
| 32      | 1         | 0.32%   |
| 20      | 1         | 0.32%   |
| 19      | 1         | 0.32%   |
| 18      | 1         | 0.32%   |
| 8       | 1         | 0.32%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 221       | 71.75%  |
| 501-600     | 27        | 8.77%   |
| 351-400     | 19        | 6.17%   |
| 201-300     | 18        | 5.84%   |
| 401-500     | 9         | 2.92%   |
| Unknown     | 5         | 1.62%   |
| 1501-2000   | 3         | 0.97%   |
| 601-700     | 2         | 0.65%   |
| 801-900     | 1         | 0.32%   |
| 701-800     | 1         | 0.32%   |
| 101-200     | 1         | 0.32%   |
| 1001-1500   | 1         | 0.32%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 245       | 90.74%  |
| 16/10   | 19        | 7.04%   |
| 4/3     | 2         | 0.74%   |
| Unknown | 2         | 0.74%   |
| 5/4     | 1         | 0.37%   |
| 3/2     | 1         | 0.37%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 188       | 60.84%  |
| 81-90          | 37        | 11.97%  |
| 201-250        | 25        | 8.09%   |
| 121-130        | 16        | 5.18%   |
| 71-80          | 7         | 2.27%   |
| 51-60          | 5         | 1.62%   |
| 301-350        | 5         | 1.62%   |
| Unknown        | 5         | 1.62%   |
| More than 1000 | 3         | 0.97%   |
| 351-500        | 3         | 0.97%   |
| 251-300        | 3         | 0.97%   |
| 151-200        | 3         | 0.97%   |
| 61-70          | 2         | 0.65%   |
| 41-50          | 2         | 0.65%   |
| 501-1000       | 2         | 0.65%   |
| 1-40           | 1         | 0.32%   |
| 141-150        | 1         | 0.32%   |
| 131-140        | 1         | 0.32%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 129       | 43.29%  |
| 101-120       | 110       | 36.91%  |
| 51-100        | 46        | 15.44%  |
| Unknown       | 5         | 1.68%   |
| 161-240       | 4         | 1.34%   |
| 1-50          | 3         | 1.01%   |
| More than 240 | 1         | 0.34%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 229       | 81.21%  |
| 2     | 42        | 14.89%  |
| 0     | 7         | 2.48%   |
| 3     | 4         | 1.42%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 169       | 36.74%  |
| Intel                             | 115       | 25%     |
| Qualcomm Atheros                  | 93        | 20.22%  |
| Broadcom                          | 32        | 6.96%   |
| Ralink                            | 8         | 1.74%   |
| Broadcom Limited                  | 7         | 1.52%   |
| Marvell Technology Group          | 5         | 1.09%   |
| Ralink Technology                 | 4         | 0.87%   |
| Nvidia                            | 4         | 0.87%   |
| Dell                              | 4         | 0.87%   |
| Huawei Technologies               | 3         | 0.65%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.43%   |
| Sierra Wireless                   | 2         | 0.43%   |
| Qualcomm Atheros Communications   | 2         | 0.43%   |
| Ericsson Business Mobile Networks | 2         | 0.43%   |
| VIA Technologies                  | 1         | 0.22%   |
| TP-Link                           | 1         | 0.22%   |
| MEDIATEK                          | 1         | 0.22%   |
| Linksys                           | 1         | 0.22%   |
| JMicron Technology                | 1         | 0.22%   |
| IMC Networks                      | 1         | 0.22%   |
| D-Link                            | 1         | 0.22%   |
| Apple                             | 1         | 0.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 98        | 17.95%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 52        | 9.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 25        | 4.58%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 18        | 3.3%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 16        | 2.93%   |
| Intel Wireless 8265 / 8275                                              | 13        | 2.38%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 10        | 1.83%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 10        | 1.83%   |
| Broadcom BCM43142 802.11b/g/n                                           | 10        | 1.83%   |
| Intel Wireless 8260                                                     | 8         | 1.47%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 8         | 1.47%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 8         | 1.47%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 1.28%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 6         | 1.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 1.1%    |
| Intel Wireless 7260                                                     | 6         | 1.1%    |
| Intel Wireless 3165                                                     | 6         | 1.1%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 6         | 1.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 6         | 1.1%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 5         | 0.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 5         | 0.92%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 5         | 0.92%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 0.92%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 0.92%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 0.92%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 5         | 0.92%   |
| Intel Ethernet Connection (4) I219-LM                                   | 5         | 0.92%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 4         | 0.73%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 4         | 0.73%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 4         | 0.73%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 4         | 0.73%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 4         | 0.73%   |
| Intel Ethernet Connection I219-LM                                       | 4         | 0.73%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 0.73%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 4         | 0.73%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 3         | 0.55%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 0.55%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 3         | 0.55%   |
| Nvidia MCP79 Ethernet                                                   | 3         | 0.55%   |
| Intel Wireless 3160                                                     | 3         | 0.55%   |
| Intel Ethernet Connection I218-LM                                       | 3         | 0.55%   |
| Intel Ethernet Connection (2) I219-LM                                   | 3         | 0.55%   |
| Intel Centrino Wireless-N 2230                                          | 3         | 0.55%   |
| Intel Centrino Ultimate-N 6300                                          | 3         | 0.55%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 0.55%   |
| Intel 82577LM Gigabit Network Connection                                | 3         | 0.55%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                                    | 3         | 0.55%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 0.37%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 2         | 0.37%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 2         | 0.37%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 2         | 0.37%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 2         | 0.37%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller               | 2         | 0.37%   |
| Qualcomm Atheros AR9271 802.11n                                         | 2         | 0.37%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 0.37%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                              | 2         | 0.37%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 2         | 0.37%   |
| Intel Wireless 7265                                                     | 2         | 0.37%   |
| Intel WiFi Link 5100                                                    | 2         | 0.37%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 0.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 109       | 37.98%  |
| Qualcomm Atheros                | 81        | 28.22%  |
| Realtek Semiconductor           | 48        | 16.72%  |
| Broadcom                        | 24        | 8.36%   |
| Ralink                          | 8         | 2.79%   |
| Ralink Technology               | 4         | 1.39%   |
| Dell                            | 3         | 1.05%   |
| Sierra Wireless                 | 2         | 0.7%    |
| Qualcomm Atheros Communications | 2         | 0.7%    |
| TP-Link                         | 1         | 0.35%   |
| MEDIATEK                        | 1         | 0.35%   |
| Linksys                         | 1         | 0.35%   |
| IMC Networks                    | 1         | 0.35%   |
| D-Link                          | 1         | 0.35%   |
| Broadcom Limited                | 1         | 0.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 25        | 8.68%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 18        | 6.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 16        | 5.56%   |
| Intel Wireless 8265 / 8275                                                    | 13        | 4.51%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 10        | 3.47%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 10        | 3.47%   |
| Broadcom BCM43142 802.11b/g/n                                                 | 10        | 3.47%   |
| Intel Wireless 8260                                                           | 8         | 2.78%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                               | 8         | 2.78%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 8         | 2.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 7         | 2.43%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 6         | 2.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 6         | 2.08%   |
| Intel Wireless 7260                                                           | 6         | 2.08%   |
| Intel Wireless 3165                                                           | 6         | 2.08%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                      | 6         | 2.08%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 5         | 1.74%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 5         | 1.74%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 5         | 1.74%   |
| Intel Wi-Fi 6 AX200                                                           | 5         | 1.74%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 5         | 1.74%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                               | 5         | 1.74%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 4         | 1.39%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 4         | 1.39%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 4         | 1.39%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 4         | 1.39%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 4         | 1.39%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                     | 3         | 1.04%   |
| Intel Wireless 3160                                                           | 3         | 1.04%   |
| Intel Centrino Wireless-N 2230                                                | 3         | 1.04%   |
| Intel Centrino Ultimate-N 6300                                                | 3         | 1.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 3         | 1.04%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                                          | 3         | 1.04%   |
| Realtek RTL8723DE Wireless Network Adapter                                    | 2         | 0.69%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                               | 2         | 0.69%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                      | 2         | 0.69%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 2         | 0.69%   |
| Qualcomm Atheros AR9271 802.11n                                               | 2         | 0.69%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2         | 0.69%   |
| Intel Wireless 7265                                                           | 2         | 0.69%   |
| Intel WiFi Link 5100                                                          | 2         | 0.69%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                       | 2         | 0.69%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                 | 2         | 0.69%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 2         | 0.69%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                 | 2         | 0.69%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                  | 2         | 0.69%   |
| Intel Centrino Advanced-N 6200                                                | 2         | 0.69%   |
| Broadcom BCM4331 802.11a/b/g/n                                                | 2         | 0.69%   |
| Broadcom BCM4311 802.11b/g WLAN                                               | 2         | 0.69%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 1         | 0.35%   |
| Sierra Wireless EM7455                                                        | 1         | 0.35%   |
| Sierra Wireless EM7355 Qualcomm Gobi 4G LTE/HSPA+/EVDO                        | 1         | 0.35%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                      | 1         | 0.35%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                    | 1         | 0.35%   |
| Ralink RT2070 Wireless Adapter                                                | 1         | 0.35%   |
| Ralink MT7601U Wireless Adapter                                               | 1         | 0.35%   |
| Ralink RT5390 [802.11 b/g/n 1T1R G-band PCI Express Single Chip]              | 1         | 0.35%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                         | 1         | 0.35%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 0.35%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter                 | 1         | 0.35%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 154       | 62.1%   |
| Intel                      | 42        | 16.94%  |
| Qualcomm Atheros           | 21        | 8.47%   |
| Broadcom                   | 10        | 4.03%   |
| Broadcom Limited           | 6         | 2.42%   |
| Marvell Technology Group   | 5         | 2.02%   |
| Nvidia                     | 4         | 1.61%   |
| ZTE WCDMA Technologies MSM | 2         | 0.81%   |
| VIA Technologies           | 1         | 0.4%    |
| JMicron Technology         | 1         | 0.4%    |
| Huawei Technologies        | 1         | 0.4%    |
| Apple                      | 1         | 0.4%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 98        | 39.04%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 52        | 20.72%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 6         | 2.39%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                        | 5         | 1.99%   |
| Intel Ethernet Connection (4) I219-LM                                | 5         | 1.99%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                               | 4         | 1.59%   |
| Intel Ethernet Connection I219-LM                                    | 4         | 1.59%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                      | 4         | 1.59%   |
| Realtek RTL8152 Fast Ethernet Adapter                                | 3         | 1.2%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                             | 3         | 1.2%    |
| Nvidia MCP79 Ethernet                                                | 3         | 1.2%    |
| Intel Ethernet Connection I218-LM                                    | 3         | 1.2%    |
| Intel Ethernet Connection (2) I219-LM                                | 3         | 1.2%    |
| Intel 82577LM Gigabit Network Connection                             | 3         | 1.2%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 2         | 0.8%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller            | 2         | 0.8%    |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                           | 2         | 0.8%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                | 2         | 0.8%    |
| Intel Ethernet Connection I217-V                                     | 2         | 0.8%    |
| Intel Ethernet Connection (6) I219-LM                                | 2         | 0.8%    |
| Intel Ethernet Connection (5) I219-LM                                | 2         | 0.8%    |
| Intel Ethernet Connection (13) I219-V                                | 2         | 0.8%    |
| Intel 82567LM Gigabit Network Connection                             | 2         | 0.8%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                    | 2         | 0.8%    |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe              | 2         | 0.8%    |
| ZTE WCDMA MSM ZTE MSM                                                | 1         | 0.4%    |
| ZTE WCDMA MSM Z6201V                                                 | 1         | 0.4%    |
| VIA VT6102/VT6103 [Rhine-II]                                         | 1         | 0.4%    |
| Realtek RTL8125 2.5GbE Controller                                    | 1         | 0.4%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                | 1         | 0.4%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller            | 1         | 0.4%    |
| Qualcomm Atheros AR8162 Fast Ethernet                                | 1         | 0.4%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet       | 1         | 0.4%    |
| Nvidia MCP67 Ethernet                                                | 1         | 0.4%    |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller              | 1         | 0.4%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller              | 1         | 0.4%    |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller              | 1         | 0.4%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                 | 1         | 0.4%    |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                 | 1         | 0.4%    |
| JMicron JMC260 PCI Express Fast Ethernet Controller                  | 1         | 0.4%    |
| Intel PRO/100 VE Network Connection                                  | 1         | 0.4%    |
| Intel Ethernet Connection I219-V                                     | 1         | 0.4%    |
| Intel Ethernet Connection I217-LM                                    | 1         | 0.4%    |
| Intel Ethernet Connection (7) I219-LM                                | 1         | 0.4%    |
| Intel Ethernet Connection (6) I219-V                                 | 1         | 0.4%    |
| Intel Ethernet Connection (4) I219-V                                 | 1         | 0.4%    |
| Intel 82566MM Gigabit Network Connection                             | 1         | 0.4%    |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller Mobile | 1         | 0.4%    |
| Huawei MAR-LX1A                                                      | 1         | 0.4%    |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                    | 1         | 0.4%    |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express             | 1         | 0.4%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                      | 1         | 0.4%    |
| Broadcom Limited NetXtreme BCM5788 Gigabit Ethernet                  | 1         | 0.4%    |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express          | 1         | 0.4%    |
| Broadcom Limited NetLink BCM57781 Gigabit Ethernet PCIe              | 1         | 0.4%    |
| Broadcom Limited BCM4401-B0 100Base-TX                               | 1         | 0.4%    |
| Broadcom BCM4401-B0 100Base-TX                                       | 1         | 0.4%    |
| Apple Ethernet Adapter [A1277]                                       | 1         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 275       | 52.18%  |
| Ethernet | 245       | 46.49%  |
| Modem    | 7         | 1.33%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 229       | 77.36%  |
| Ethernet | 67        | 22.64%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 237       | 85.87%  |
| 1     | 39        | 14.13%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 272       | 98.55%  |
| Yes  | 4         | 1.45%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 78        | 34.98%  |
| Realtek Semiconductor           | 36        | 16.14%  |
| Qualcomm Atheros Communications | 29        | 13%     |
| Lite-On Technology              | 21        | 9.42%   |
| IMC Networks                    | 14        | 6.28%   |
| Broadcom                        | 10        | 4.48%   |
| Toshiba                         | 6         | 2.69%   |
| Foxconn / Hon Hai               | 5         | 2.24%   |
| Apple                           | 4         | 1.79%   |
| Ralink                          | 3         | 1.35%   |
| Hewlett-Packard                 | 3         | 1.35%   |
| Foxconn International           | 3         | 1.35%   |
| Dell                            | 3         | 1.35%   |
| USI                             | 2         | 0.9%    |
| Ralink Technology               | 2         | 0.9%    |
| Cambridge Silicon Radio         | 2         | 0.9%    |
| Askey Computer                  | 1         | 0.45%   |
| Alps Electric                   | 1         | 0.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 40        | 17.94%  |
| Realtek Bluetooth Radio                             | 20        | 8.97%   |
| Qualcomm Atheros  Bluetooth Device                  | 19        | 8.52%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 18        | 8.07%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 12        | 5.38%   |
| Realtek  Bluetooth 4.2 Adapter                      | 11        | 4.93%   |
| IMC Networks Bluetooth Radio                        | 7         | 3.14%   |
| Lite-On Bluetooth Device                            | 5         | 2.24%   |
| Intel AX200 Bluetooth                               | 5         | 2.24%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 4         | 1.79%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 1.79%   |
| Intel AX201 Bluetooth                               | 4         | 1.79%   |
| Ralink RT3290 Bluetooth                             | 3         | 1.35%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 1.35%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 3         | 1.35%   |
| Foxconn International BCM43142A0 Bluetooth module   | 3         | 1.35%   |
| Foxconn / Hon Hai Bluetooth Device                  | 3         | 1.35%   |
| Dell DW375 Bluetooth Module                         | 3         | 1.35%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 3         | 1.35%   |
| Apple Bluetooth Host Controller                     | 3         | 1.35%   |
| USI Bluetooth Module BCM92070                       | 2         | 0.9%    |
| Toshiba Bluetooth Device                            | 2         | 0.9%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 2         | 0.9%    |
| Realtek RTL8723B Bluetooth                          | 2         | 0.9%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 0.9%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 0.9%    |
| Qualcomm Atheros AR3012 Bluetooth                   | 2         | 0.9%    |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.9%    |
| IMC Networks Bluetooth Device                       | 2         | 0.9%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 0.9%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 0.9%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 0.9%    |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 2         | 0.9%    |
| Toshiba RT Bluetooth Radio                          | 1         | 0.45%   |
| Toshiba Integrated Bluetooth (Taiyo Yuden)          | 1         | 0.45%   |
| Toshiba BCM43142A0                                  | 1         | 0.45%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.45%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 0.45%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.45%   |
| Ralink CSR BS8510                                   | 1         | 0.45%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.45%   |
| Lite-On Atheros Bluetooth                           | 1         | 0.45%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.45%   |
| IMC Networks Wireless_Device                        | 1         | 0.45%   |
| IMC Networks Internal Bluetooth                     | 1         | 0.45%   |
| IMC Networks Bluetooth                              | 1         | 0.45%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 0.45%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 1         | 0.45%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 0.45%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 0.45%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 0.45%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 0.45%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 1         | 0.45%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 0.45%   |
| Askey Bluetooth Device                              | 1         | 0.45%   |
| Apple Bluetooth HCI                                 | 1         | 0.45%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)     | 1         | 0.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 226       | 71.97%  |
| AMD                 | 47        | 14.97%  |
| Nvidia              | 34        | 10.83%  |
| GN Netcom           | 2         | 0.64%   |
| VIA Technologies    | 1         | 0.32%   |
| Native Instruments  | 1         | 0.32%   |
| Kingston Technology | 1         | 0.32%   |
| Hewlett-Packard     | 1         | 0.32%   |
| Focusrite-Novation  | 1         | 0.32%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 36        | 9.52%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 27        | 7.14%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 23        | 6.08%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 21        | 5.56%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 17        | 4.5%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 13        | 3.44%   |
| Intel Cannon Lake PCH cAVS                                                                        | 12        | 3.17%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 9         | 2.38%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 9         | 2.38%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 2.38%   |
| Intel Broadwell-U Audio Controller                                                                | 9         | 2.38%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 9         | 2.38%   |
| Intel 8 Series HD Audio Controller                                                                | 9         | 2.38%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 9         | 2.38%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 8         | 2.12%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 8         | 2.12%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 8         | 2.12%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 8         | 2.12%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 8         | 2.12%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 7         | 1.85%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 7         | 1.85%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 7         | 1.85%   |
| Intel CM238 HD Audio Controller                                                                   | 6         | 1.59%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 1.59%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 6         | 1.59%   |
| AMD FCH Azalia Controller                                                                         | 6         | 1.59%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 1.32%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 1.32%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 5         | 1.32%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 5         | 1.32%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 1.32%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.32%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 4         | 1.06%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 1.06%   |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 0.79%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 0.79%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 2         | 0.53%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 2         | 0.53%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 0.53%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 2         | 0.53%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 0.53%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 0.53%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                                              | 2         | 0.53%   |
| AMD High Definition Audio Controller                                                              | 2         | 0.53%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 0.53%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 0.26%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.26%   |
| Nvidia MCP67 High Definition Audio                                                                | 1         | 0.26%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.26%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.26%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.26%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.26%   |
| Nvidia Audio device                                                                               | 1         | 0.26%   |
| Native Instruments Traktor Kontrol Z1                                                             | 1         | 0.26%   |
| Kingston Technology HyperX 7.1 Audio                                                              | 1         | 0.26%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 1         | 0.26%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller                        | 1         | 0.26%   |
| Hewlett-Packard USB Audio                                                                         | 1         | 0.26%   |
| GN Netcom Jabra Link 370                                                                          | 1         | 0.26%   |
| GN Netcom Jabra Evolve 75                                                                         | 1         | 0.26%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 41        | 24.4%   |
| Samsung Electronics | 40        | 23.81%  |
| Micron Technology   | 26        | 15.48%  |
| Kingston            | 24        | 14.29%  |
| Unknown             | 10        | 5.95%   |
| Ramaxel Technology  | 9         | 5.36%   |
| Transcend           | 6         | 3.57%   |
| Crucial             | 2         | 1.19%   |
| Corsair             | 2         | 1.19%   |
| SHARETRONIC         | 1         | 0.6%    |
| PNY                 | 1         | 0.6%    |
| Patriot             | 1         | 0.6%    |
| Nanya Technology    | 1         | 0.6%    |
| Elpida              | 1         | 0.6%    |
| Apacer              | 1         | 0.6%    |
| A-DATA Technology   | 1         | 0.6%    |
| 48spaces            | 1         | 0.6%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s      | 4         | 2.2%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s       | 4         | 2.2%    |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s        | 4         | 2.2%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s       | 4         | 2.2%    |
| Micron RAM 4ATF51264HZ-2G6E! 4GB SODIMM DDR4 2400MT/s       | 4         | 2.2%    |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s      | 3         | 1.65%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s       | 3         | 1.65%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s       | 3         | 1.65%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s       | 3         | 1.65%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s        | 3         | 1.65%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s     | 3         | 1.65%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                  | 2         | 1.1%    |
| Unknown RAM Module 1024MB SODIMM DDR                        | 2         | 1.1%    |
| Transcend RAM JM3200HSG-8G 8192MB SODIMM DDR4 2667MT/s      | 2         | 1.1%    |
| SK Hynix RAM HYMP125S64CP8-S6 2GB SODIMM SDRAM 2048MT/s     | 2         | 1.1%    |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 2         | 1.1%    |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s      | 2         | 1.1%    |
| SK Hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s      | 2         | 1.1%    |
| SK Hynix RAM HMA851S6JJR6N-VK 4096MB SODIMM DDR4 2667MT/s   | 2         | 1.1%    |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s      | 2         | 1.1%    |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 2         | 1.1%    |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s      | 2         | 1.1%    |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s       | 2         | 1.1%    |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s       | 2         | 1.1%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s       | 2         | 1.1%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 2         | 1.1%    |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s    | 2         | 1.1%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s       | 2         | 1.1%    |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s | 2         | 1.1%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s       | 2         | 1.1%    |
| Micron RAM 4ATS1G64HZ-2G6E1 8192MB SODIMM DDR4 2667MT/s     | 2         | 1.1%    |
| Unknown RAM Module 8192MB SODIMM DDR4 3200MT/s              | 1         | 0.55%   |
| Unknown RAM Module 2GB SODIMM DDR2                          | 1         | 0.55%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s               | 1         | 0.55%   |
| Unknown RAM Module 2048MB SODIMM DDR                        | 1         | 0.55%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                    | 1         | 0.55%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                  | 1         | 0.55%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s               | 1         | 0.55%   |
| Unknown RAM Module 1024MB SODIMM 800MT/s                    | 1         | 0.55%   |
| Transcend RAM Module 1024MB SODIMM DDR2 533MT/s             | 1         | 0.55%   |
| Transcend RAM JM2666HSH-4G 4GB SODIMM DDR4 2667MT/s         | 1         | 0.55%   |
| Transcend RAM JM2666HSD-4G 4GB SODIMM DDR4 2667MT/s         | 1         | 0.55%   |
| Transcend RAM JM2400HSB-8G 8GB SODIMM DDR4 2400MT/s         | 1         | 0.55%   |
| SK Hynix RAM Module 8192MB SODIMM DDR4 2133MT/s             | 1         | 0.55%   |
| SK Hynix RAM Module 512MB SODIMM DDR2 533MT/s               | 1         | 0.55%   |
| SK Hynix RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2400MT/s   | 1         | 0.55%   |
| SK Hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s        | 1         | 0.55%   |
| SK Hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 0.55%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 0.55%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s      | 1         | 0.55%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 1         | 0.55%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 1         | 0.55%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1334MT/s   | 1         | 0.55%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2048MB SODIMM DDR3 1333MT/s   | 1         | 0.55%   |
| SK Hynix RAM HMT125S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s      | 1         | 0.55%   |
| SK Hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1067MT/s      | 1         | 0.55%   |
| SK Hynix RAM HMAA7GS6CMR6N-XN 8GB SODIMM DDR4 3200MT/s      | 1         | 0.55%   |
| SK Hynix RAM HMAA1GS6CMR6N-XN 8GB SODIMM DDR4 3200MT/s      | 1         | 0.55%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s      | 1         | 0.55%   |
| SK Hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s      | 1         | 0.55%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 62        | 47.33%  |
| DDR3    | 46        | 35.11%  |
| DDR2    | 10        | 7.63%   |
| SDRAM   | 5         | 3.82%   |
| LPDDR4  | 4         | 3.05%   |
| DDR     | 2         | 1.53%   |
| LPDDR3  | 1         | 0.76%   |
| Unknown | 1         | 0.76%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 125       | 96.15%  |
| Row Of Chips | 5         | 3.85%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 51        | 36.17%  |
| 8192  | 45        | 31.91%  |
| 2048  | 28        | 19.86%  |
| 16384 | 8         | 5.67%   |
| 1024  | 8         | 5.67%   |
| 512   | 1         | 0.71%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 35        | 23.33%  |
| 1600    | 35        | 23.33%  |
| 3200    | 22        | 14.67%  |
| 2400    | 13        | 8.67%   |
| 1334    | 9         | 6%      |
| 667     | 6         | 4%      |
| 2133    | 4         | 2.67%   |
| 1333    | 4         | 2.67%   |
| 1067    | 4         | 2.67%   |
| 3266    | 3         | 2%      |
| 2048    | 3         | 2%      |
| Unknown | 3         | 2%      |
| 4199    | 2         | 1.33%   |
| 975     | 2         | 1.33%   |
| 800     | 2         | 1.33%   |
| 533     | 2         | 1.33%   |
| 1066    | 1         | 0.67%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 5         | 55.56%  |
| Canon                 | 2         | 22.22%  |
| Seiko Epson           | 1         | 11.11%  |
| Lexmark International | 1         | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| HP LaserJet 1018                      | 2         | 22.22%  |
| Seiko Epson L365 Series               | 1         | 11.11%  |
| Lexmark International Lexmark MS312dn | 1         | 11.11%  |
| HP LaserJet M14-M17                   | 1         | 11.11%  |
| HP LaserJet 1020                      | 1         | 11.11%  |
| HP DeskJet 845c                       | 1         | 11.11%  |
| Canon LBP6030/6030B/6018L             | 1         | 11.11%  |
| Canon iP7200 series                   | 1         | 11.11%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 4         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 110 | 2         | 50%     |
| Canon CanoScan LIDE 25  | 1         | 25%     |
| Canon CanoScan LiDE 210 | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 71        | 28.29%  |
| IMC Networks                           | 36        | 14.34%  |
| Realtek Semiconductor                  | 22        | 8.76%   |
| Microdia                               | 18        | 7.17%   |
| Quanta                                 | 15        | 5.98%   |
| Acer                                   | 15        | 5.98%   |
| Suyin                                  | 14        | 5.58%   |
| Sunplus Innovation Technology          | 14        | 5.58%   |
| Cheng Uei Precision Industry (Foxlink) | 14        | 5.58%   |
| Syntek                                 | 8         | 3.19%   |
| Lite-On Technology                     | 6         | 2.39%   |
| Apple                                  | 4         | 1.59%   |
| Importek                               | 3         | 1.2%    |
| Silicon Motion                         | 2         | 0.8%    |
| Luxvisions Innotech Limited            | 2         | 0.8%    |
| Alcor Micro                            | 2         | 0.8%    |
| Samsung Electronics                    | 1         | 0.4%    |
| OmniVision Technologies                | 1         | 0.4%    |
| Logitech                               | 1         | 0.4%    |
| Lenovo                                 | 1         | 0.4%    |
| DigiTech                               | 1         | 0.4%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                             | 17        | 6.77%   |
| Chicony Integrated Camera                                      | 12        | 4.78%   |
| Realtek Integrated_Webcam_HD                                   | 7         | 2.79%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 7         | 2.79%   |
| Sunplus Integrated_Webcam_HD                                   | 6         | 2.39%   |
| Microdia Integrated_Webcam_HD                                  | 6         | 2.39%   |
| Syntek Integrated Camera                                       | 5         | 1.99%   |
| Quanta VGA WebCam                                              | 5         | 1.99%   |
| Quanta HD WebCam                                               | 5         | 1.99%   |
| IMC Networks Integrated Camera                                 | 5         | 1.99%   |
| Chicony TOSHIBA Web Camera - HD                                | 5         | 1.99%   |
| Chicony Integrated Camera (1280x720@30)                        | 5         | 1.99%   |
| Chicony EasyCamera                                             | 5         | 1.99%   |
| Acer Integrated Camera                                         | 5         | 1.99%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                       | 4         | 1.59%   |
| Realtek Lenovo EasyCamera                                      | 4         | 1.59%   |
| Chicony VGA Webcam                                             | 4         | 1.59%   |
| Chicony HP Webcam                                              | 4         | 1.59%   |
| Chicony HD WebCam                                              | 4         | 1.59%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 4         | 1.59%   |
| Syntek EasyCamera                                              | 3         | 1.2%    |
| Realtek Integrated Webcam HD                                   | 3         | 1.2%    |
| Quanta HP TrueVision HD Camera                                 | 3         | 1.2%    |
| IMC Networks EasyCamera                                        | 3         | 1.2%    |
| Chicony USB 2.0 Camera                                         | 3         | 1.2%    |
| Chicony HD User Facing                                         | 3         | 1.2%    |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 3         | 1.2%    |
| Acer Lenovo EasyCamera                                         | 3         | 1.2%    |
| Acer BisonCam, NB Pro                                          | 3         | 1.2%    |
| Suyin Acer CrystalEye Webcam                                   | 2         | 0.8%    |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)    | 2         | 0.8%    |
| Sunplus HP Wide Vision HD                                      | 2         | 0.8%    |
| Sunplus Asus Webcam                                            | 2         | 0.8%    |
| Realtek USB2.0-Camera                                          | 2         | 0.8%    |
| Realtek USB Camera                                             | 2         | 0.8%    |
| Microdia Laptop_Integrated_Webcam_HD                           | 2         | 0.8%    |
| Microdia Integrated Webcam                                     | 2         | 0.8%    |
| Microdia HP Webcam                                             | 2         | 0.8%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 2         | 0.8%    |
| Lite-On HP TrueVision HD Camera                                | 2         | 0.8%    |
| Lite-On HP HD Webcam                                           | 2         | 0.8%    |
| Importek Laptop Integrated Webcam                              | 2         | 0.8%    |
| Chicony UVC 1.00 device HD UVC WebCam                          | 2         | 0.8%    |
| Chicony USB2.0 VGA UVC WebCam                                  | 2         | 0.8%    |
| Chicony USB2.0 HD UVC WebCam                                   | 2         | 0.8%    |
| Chicony HP Truevision HD                                       | 2         | 0.8%    |
| Chicony HP HD Webcam                                           | 2         | 0.8%    |
| Chicony HP HD Camera                                           | 2         | 0.8%    |
| Chicony 1.3M HD WebCam                                         | 2         | 0.8%    |
| Cheng Uei Precision Industry (Foxlink) Webcam                  | 2         | 0.8%    |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera            | 2         | 0.8%    |
| Apple FaceTime HD Camera                                       | 2         | 0.8%    |
| Suyin USB 2.0 Camera                                           | 1         | 0.4%    |
| Suyin Integrated_Webcam_HD                                     | 1         | 0.4%    |
| Suyin HP webcam [dv6-1190en]                                   | 1         | 0.4%    |
| Suyin HP TrueVision HD Integrated Webcam                       | 1         | 0.4%    |
| Suyin HD Video WebCam                                          | 1         | 0.4%    |
| Suyin 1.3M HD WebCam                                           | 1         | 0.4%    |
| Sunplus USB Camera                                             | 1         | 0.4%    |
| Sunplus Integrated Webcam                                      | 1         | 0.4%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 18        | 40.91%  |
| Synaptics                  | 9         | 20.45%  |
| Shenzhen Goodix Technology | 7         | 15.91%  |
| AuthenTec                  | 5         | 11.36%  |
| Upek                       | 2         | 4.55%   |
| Elan Microelectronics      | 2         | 4.55%   |
| LighTuning Technology      | 1         | 2.27%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 6         | 13.64%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 5         | 11.36%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 9.09%   |
| Synaptics  WBDI                                                            | 4         | 9.09%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 4         | 9.09%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 3         | 6.82%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 4.55%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 4.55%   |
| Elan ELAN:Fingerprint                                                      | 2         | 4.55%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 2.27%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 2.27%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 2.27%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 2.27%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 2.27%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.27%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 2.27%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 2.27%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 2.27%   |
| AuthenTec AES2810                                                          | 1         | 2.27%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 2.27%   |
| Unknown                                                                    | 1         | 2.27%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 8         | 47.06%  |
| Alcor Micro           | 4         | 23.53%  |
| O2 Micro              | 2         | 11.76%  |
| OmniKey               | 1         | 5.88%   |
| Lenovo                | 1         | 5.88%   |
| Gemalto (was Gemplus) | 1         | 5.88%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Broadcom 5880                                     | 4         | 23.53%  |
| Alcor Micro AU9540 Smartcard Reader               | 4         | 23.53%  |
| Broadcom BCM5880 Secure Applications Processor    | 3         | 17.65%  |
| O2 Micro OZ776 CCID Smartcard Reader              | 2         | 11.76%  |
| OmniKey 3x21 Smart Card Reader                    | 1         | 5.88%   |
| Lenovo Integrated Smart Card Reader               | 1         | 5.88%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 1         | 5.88%   |
| Broadcom 58200                                    | 1         | 5.88%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 185       | 64.91%  |
| 1     | 77        | 27.02%  |
| 2     | 18        | 6.32%   |
| 4     | 2         | 0.7%    |
| 3     | 2         | 0.7%    |
| 8     | 1         | 0.35%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 44        | 34.65%  |
| Graphics card            | 27        | 21.26%  |
| Chipcard                 | 16        | 12.6%   |
| Net/wireless             | 14        | 11.02%  |
| Bluetooth                | 6         | 4.72%   |
| Multimedia controller    | 5         | 3.94%   |
| Communication controller | 5         | 3.94%   |
| Sound                    | 2         | 1.57%   |
| Net/ethernet             | 2         | 1.57%   |
| Card reader              | 2         | 1.57%   |
| Camera                   | 2         | 1.57%   |
| Storage                  | 1         | 0.79%   |
| Modem                    | 1         | 0.79%   |

