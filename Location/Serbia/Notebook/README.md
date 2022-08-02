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

Total: 439

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Sony          | VPCEE23FX                   | [b4108910d3](https://linux-hardware.org/?probe=b4108910d3) | Jul 25, 2022 |
| Acer          | Nitro AN515-55              | [b121274e4f](https://linux-hardware.org/?probe=b121274e4f) | Jul 23, 2022 |
| Apple         | MacBookPro5,1               | [4bae560f04](https://linux-hardware.org/?probe=4bae560f04) | Jul 22, 2022 |
| Apple         | MacBookPro5,1               | [8a81341ecd](https://linux-hardware.org/?probe=8a81341ecd) | Jul 18, 2022 |
| HP            | Compaq nx7300 (RU373ES#A... | [3004f1d2b9](https://linux-hardware.org/?probe=3004f1d2b9) | Jul 16, 2022 |
| Gigabyte      | AERO 17 KC                  | [b6398b12e2](https://linux-hardware.org/?probe=b6398b12e2) | Jul 13, 2022 |
| Lenovo        | ThinkPad X280 20KES8D400    | [fdc339a6b0](https://linux-hardware.org/?probe=fdc339a6b0) | Jul 09, 2022 |
| Lenovo        | ThinkPad X280 20KES8D400    | [7d2b04b0ce](https://linux-hardware.org/?probe=7d2b04b0ce) | Jul 09, 2022 |
| Dell          | Vostro 15 3515              | [c6e9a42a66](https://linux-hardware.org/?probe=c6e9a42a66) | Jul 08, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [c01cf9f7fc](https://linux-hardware.org/?probe=c01cf9f7fc) | Jul 05, 2022 |
| HP            | 250 G4                      | [3d629889b2](https://linux-hardware.org/?probe=3d629889b2) | Jul 05, 2022 |
| HP            | 250 G4                      | [e19f8a8485](https://linux-hardware.org/?probe=e19f8a8485) | Jul 05, 2022 |
| Lenovo        | Legion 5 17ACH6 82K0        | [be7fd47ea1](https://linux-hardware.org/?probe=be7fd47ea1) | Jul 04, 2022 |
| Timi          | TM1613                      | [6d3f245289](https://linux-hardware.org/?probe=6d3f245289) | Jul 04, 2022 |
| Timi          | TM1613                      | [38d9919cfd](https://linux-hardware.org/?probe=38d9919cfd) | Jul 03, 2022 |
| Dell          | Inspiron 3593               | [5b091180ec](https://linux-hardware.org/?probe=5b091180ec) | Jun 28, 2022 |
| Lenovo        | ThinkPad T560 20FJS1KE00    | [f0cd91b4d2](https://linux-hardware.org/?probe=f0cd91b4d2) | Jun 21, 2022 |
| Lenovo        | Unknown                     | [cd2f32d91c](https://linux-hardware.org/?probe=cd2f32d91c) | Jun 16, 2022 |
| HP            | Pavilion Notebook           | [06c982ad14](https://linux-hardware.org/?probe=06c982ad14) | Jun 16, 2022 |
| Lenovo        | ThinkPad T60 2007FUG        | [2c1a306677](https://linux-hardware.org/?probe=2c1a306677) | Jun 16, 2022 |
| ASUSTek       | K55VD                       | [7fa5d36a45](https://linux-hardware.org/?probe=7fa5d36a45) | Jun 04, 2022 |
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
| Ubuntu 20.04                 | 41        | 12.62%  |
| Ubuntu 18.04                 | 29        | 8.92%   |
| OpenMandriva 4.3             | 10        | 3.08%   |
| Zorin 15                     | 9         | 2.77%   |
| BlackPanther 18.1            | 9         | 2.77%   |
| ROSA R11                     | 8         | 2.46%   |
| Ubuntu 19.10                 | 7         | 2.15%   |
| Linux Mint 19.3              | 7         | 2.15%   |
| Arch                         | 7         | 2.15%   |
| OpenMandriva 4.2             | 6         | 1.85%   |
| Ubuntu 22.04                 | 5         | 1.54%   |
| Ubuntu 21.10                 | 5         | 1.54%   |
| Ubuntu 18.10                 | 5         | 1.54%   |
| ROSA R10                     | 5         | 1.54%   |
| Linux Mint 20.3              | 5         | 1.54%   |
| KDE neon 20.04               | 5         | 1.54%   |
| ROSA R11.1                   | 4         | 1.23%   |
| Fedora 34                    | 4         | 1.23%   |
| Xubuntu 20.04                | 3         | 0.92%   |
| Ubuntu 21.04                 | 3         | 0.92%   |
| Ubuntu 19.04                 | 3         | 0.92%   |
| Ubuntu 16.04                 | 3         | 0.92%   |
| ROSA R9                      | 3         | 0.92%   |
| ROSA 12.2                    | 3         | 0.92%   |
| Pop!_OS 21.04                | 3         | 0.92%   |
| Manjaro                      | 3         | 0.92%   |
| Linux Mint 20.2              | 3         | 0.92%   |
| Linux Mint 20.1              | 3         | 0.92%   |
| KDE neon 18.04               | 3         | 0.92%   |
| Fedora 35                    | 3         | 0.92%   |
| Fedora 30                    | 3         | 0.92%   |
| Endless 3.9.4                | 3         | 0.92%   |
| Endless 3.9.0                | 3         | 0.92%   |
| Endless 3.5.4                | 3         | 0.92%   |
| ArcoLinux Rolling            | 3         | 0.92%   |
| Arch Rolling                 | 3         | 0.92%   |
| Xubuntu 18.04                | 2         | 0.62%   |
| ROSA R8.1                    | 2         | 0.62%   |
| Pop!_OS 20.10                | 2         | 0.62%   |
| Pop!_OS 20.04                | 2         | 0.62%   |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 0.62%   |
| MX 21                        | 2         | 0.62%   |
| Manjaro 18.1.5               | 2         | 0.62%   |
| Kubuntu 20.04                | 2         | 0.62%   |
| Fedora 33                    | 2         | 0.62%   |
| Fedora 32                    | 2         | 0.62%   |
| Endless 3.9.3                | 2         | 0.62%   |
| Endless 3.8.7                | 2         | 0.62%   |
| Endless 3.7.5                | 2         | 0.62%   |
| Endless 3.7.3                | 2         | 0.62%   |
| Endless 3.6.2                | 2         | 0.62%   |
| Endless 3.5.7                | 2         | 0.62%   |
| Endless 3.3.19-nexthw1       | 2         | 0.62%   |
| Zorin 12                     | 1         | 0.31%   |
| Xubuntu 21.10                | 1         | 0.31%   |
| UbuntuDDE 21.04              | 1         | 0.31%   |
| Ubuntu MATE 18.04            | 1         | 0.31%   |
| Ubuntu Budgie 20.10          | 1         | 0.31%   |
| Ubuntu 20.10                 | 1         | 0.31%   |
| Slackware 15.0               | 1         | 0.31%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 101       | 33.67%  |
| Endless       | 30        | 10%     |
| ROSA          | 22        | 7.33%   |
| Linux Mint    | 20        | 6.67%   |
| OpenMandriva  | 16        | 5.33%   |
| Fedora        | 13        | 4.33%   |
| Manjaro       | 12        | 4%      |
| Zorin         | 10        | 3.33%   |
| BlackPanther  | 10        | 3.33%   |
| Arch          | 10        | 3.33%   |
| Pop!_OS       | 8         | 2.67%   |
| KDE neon      | 8         | 2.67%   |
| Xubuntu       | 6         | 2%      |
| Kubuntu       | 5         | 1.67%   |
| openSUSE      | 3         | 1%      |
| Lubuntu       | 3         | 1%      |
| Kali          | 3         | 1%      |
| ArcoLinux     | 3         | 1%      |
| MX            | 2         | 0.67%   |
| Elementary    | 2         | 0.67%   |
| UbuntuDDE     | 1         | 0.33%   |
| Ubuntu MATE   | 1         | 0.33%   |
| Ubuntu Budgie | 1         | 0.33%   |
| Slackware     | 1         | 0.33%   |
| Peppermint    | 1         | 0.33%   |
| GNOME OS      | 1         | 0.33%   |
| Generic       | 1         | 0.33%   |
| Garuda Linux  | 1         | 0.33%   |
| EndeavourOS   | 1         | 0.33%   |
| Devuan        | 1         | 0.33%   |
| Deepin        | 1         | 0.33%   |
| Debian        | 1         | 0.33%   |
| Clear Linux   | 1         | 0.33%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Notebooks | Percent |
|------------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003            | 10        | 2.91%   |
| 4.18.16-desktop-1bP                | 7         | 2.03%   |
| 5.8.0-14-generic                   | 6         | 1.74%   |
| 5.3.0-40-generic                   | 6         | 1.74%   |
| 5.10.14-desktop-1omv4002           | 6         | 1.74%   |
| 4.18.0-15-generic                  | 6         | 1.74%   |
| 5.11.0-27-generic                  | 5         | 1.45%   |
| 5.4.0-47-generic                   | 4         | 1.16%   |
| 5.4.0-42-generic                   | 4         | 1.16%   |
| 5.3.0-23-generic                   | 4         | 1.16%   |
| 4.18.0-25-generic                  | 4         | 1.16%   |
| 4.18.0-12-generic                  | 4         | 1.16%   |
| 4.15.0-15-generic                  | 4         | 1.16%   |
| 5.4.0-58-generic                   | 3         | 0.87%   |
| 5.4.0-52-generic                   | 3         | 0.87%   |
| 5.4.0-48-generic                   | 3         | 0.87%   |
| 5.4.0-19-generic                   | 3         | 0.87%   |
| 5.3.0-51-generic                   | 3         | 0.87%   |
| 5.3.0-29-generic                   | 3         | 0.87%   |
| 5.3.0-28-generic                   | 3         | 0.87%   |
| 5.15.0-40-generic                  | 3         | 0.87%   |
| 5.13.0-30-generic                  | 3         | 0.87%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 3         | 0.87%   |
| 5.0.0-31-generic                   | 3         | 0.87%   |
| 4.9.20-nrj-desktop-1rosa-x86_64    | 3         | 0.87%   |
| 4.18.0-10-generic                  | 3         | 0.87%   |
| 4.15.0-desktop-45.1rosa-x86_64     | 3         | 0.87%   |
| 5.8.11-1-MANJARO                   | 2         | 0.58%   |
| 5.8.0-55-generic                   | 2         | 0.58%   |
| 5.8.0-48-generic                   | 2         | 0.58%   |
| 5.8.0-33-generic                   | 2         | 0.58%   |
| 5.6.14-desktop-2bP                 | 2         | 0.58%   |
| 5.4.0-94-generic                   | 2         | 0.58%   |
| 5.4.0-88-generic                   | 2         | 0.58%   |
| 5.4.0-74-generic                   | 2         | 0.58%   |
| 5.4.0-73-generic                   | 2         | 0.58%   |
| 5.4.0-70-generic                   | 2         | 0.58%   |
| 5.4.0-66-generic                   | 2         | 0.58%   |
| 5.4.0-54-generic                   | 2         | 0.58%   |
| 5.4.0-33-generic                   | 2         | 0.58%   |
| 5.4.0-31-generic                   | 2         | 0.58%   |
| 5.4.0-29-generic                   | 2         | 0.58%   |
| 5.4.0-122-generic                  | 2         | 0.58%   |
| 5.3.0-45-generic                   | 2         | 0.58%   |
| 5.3.0-24-generic                   | 2         | 0.58%   |
| 5.3.0-12-generic                   | 2         | 0.58%   |
| 5.13.0-40-generic                  | 2         | 0.58%   |
| 5.13.0-39-generic                  | 2         | 0.58%   |
| 5.13.0-27-generic                  | 2         | 0.58%   |
| 5.13.0-23-generic                  | 2         | 0.58%   |
| 5.11.0-7620-generic                | 2         | 0.58%   |
| 5.11.0-40-generic                  | 2         | 0.58%   |
| 5.11.0-38-generic                  | 2         | 0.58%   |
| 5.11.0-35-generic                  | 2         | 0.58%   |
| 5.11.0-34-generic                  | 2         | 0.58%   |
| 5.0.0-27-generic                   | 2         | 0.58%   |
| 5.0.0-25-generic                   | 2         | 0.58%   |
| 5.0.0-20-generic                   | 2         | 0.58%   |
| 5.0.0-15-generic                   | 2         | 0.58%   |
| 4.18.0-20-generic                  | 2         | 0.58%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 53        | 16.21%  |
| 4.15.0  | 29        | 8.87%   |
| 5.3.0   | 27        | 8.26%   |
| 5.11.0  | 21        | 6.42%   |
| 4.18.0  | 21        | 6.42%   |
| 5.8.0   | 19        | 5.81%   |
| 5.13.0  | 17        | 5.2%    |
| 5.0.0   | 17        | 5.2%    |
| 5.16.7  | 10        | 3.06%   |
| 4.18.16 | 7         | 2.14%   |
| 5.15.0  | 6         | 1.83%   |
| 5.10.14 | 6         | 1.83%   |
| 5.10.0  | 6         | 1.83%   |
| 4.9.20  | 4         | 1.22%   |
| 5.8.11  | 3         | 0.92%   |
| 5.10.74 | 3         | 0.92%   |
| 5.6.14  | 2         | 0.61%   |
| 5.17.0  | 2         | 0.61%   |
| 5.15.11 | 2         | 0.61%   |
| 5.12.9  | 2         | 0.61%   |
| 4.9.76  | 2         | 0.61%   |
| 4.13.0  | 2         | 0.61%   |
| 5.9.8   | 1         | 0.31%   |
| 5.9.12  | 1         | 0.31%   |
| 5.8.13  | 1         | 0.31%   |
| 5.7.9   | 1         | 0.31%   |
| 5.7.10  | 1         | 0.31%   |
| 5.6.8   | 1         | 0.31%   |
| 5.6.3   | 1         | 0.31%   |
| 5.6.11  | 1         | 0.31%   |
| 5.5.7   | 1         | 0.31%   |
| 5.4.88  | 1         | 0.31%   |
| 5.4.83  | 1         | 0.31%   |
| 5.4.75  | 1         | 0.31%   |
| 5.4.6   | 1         | 0.31%   |
| 5.4.40  | 1         | 0.31%   |
| 5.4.32  | 1         | 0.31%   |
| 5.4.31  | 1         | 0.31%   |
| 5.4.15  | 1         | 0.31%   |
| 5.4.12  | 1         | 0.31%   |
| 5.3.16  | 1         | 0.31%   |
| 5.18.9  | 1         | 0.31%   |
| 5.18.10 | 1         | 0.31%   |
| 5.17.4  | 1         | 0.31%   |
| 5.16.2  | 1         | 0.31%   |
| 5.16.17 | 1         | 0.31%   |
| 5.16.0  | 1         | 0.31%   |
| 5.15.8  | 1         | 0.31%   |
| 5.15.49 | 1         | 0.31%   |
| 5.15.41 | 1         | 0.31%   |
| 5.15.25 | 1         | 0.31%   |
| 5.15.21 | 1         | 0.31%   |
| 5.15.15 | 1         | 0.31%   |
| 5.14.11 | 1         | 0.31%   |
| 5.13.12 | 1         | 0.31%   |
| 5.13.11 | 1         | 0.31%   |
| 5.12.7  | 1         | 0.31%   |
| 5.12.4  | 1         | 0.31%   |
| 5.12.15 | 1         | 0.31%   |
| 5.12.14 | 1         | 0.31%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 62        | 19.2%   |
| 4.15    | 29        | 8.98%   |
| 5.3     | 28        | 8.67%   |
| 4.18    | 28        | 8.67%   |
| 5.11    | 27        | 8.36%   |
| 5.8     | 23        | 7.12%   |
| 5.10    | 20        | 6.19%   |
| 5.13    | 19        | 5.88%   |
| 5.0     | 19        | 5.88%   |
| 5.16    | 13        | 4.02%   |
| 5.15    | 13        | 4.02%   |
| 4.9     | 11        | 3.41%   |
| 5.12    | 5         | 1.55%   |
| 5.6     | 4         | 1.24%   |
| 5.17    | 3         | 0.93%   |
| 5.9     | 2         | 0.62%   |
| 5.7     | 2         | 0.62%   |
| 5.18    | 2         | 0.62%   |
| 5.1     | 2         | 0.62%   |
| 4.19    | 2         | 0.62%   |
| 4.13    | 2         | 0.62%   |
| 4.1     | 2         | 0.62%   |
| 5.5     | 1         | 0.31%   |
| 5.14    | 1         | 0.31%   |
| 4.17    | 1         | 0.31%   |
| 4.12    | 1         | 0.31%   |
| 4.10    | 1         | 0.31%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 274       | 95.14%  |
| i686   | 14        | 4.86%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 118       | 38.56%  |
| Unknown         | 53        | 17.32%  |
| KDE5            | 52        | 16.99%  |
| XFCE            | 23        | 7.52%   |
| X-Cinnamon      | 15        | 4.9%    |
| KDE4            | 11        | 3.59%   |
| KDE             | 6         | 1.96%   |
| Cinnamon        | 6         | 1.96%   |
| MATE            | 4         | 1.31%   |
| LXQt            | 4         | 1.31%   |
| i3              | 4         | 1.31%   |
| Pantheon        | 2         | 0.65%   |
| Deepin          | 2         | 0.65%   |
| Unity           | 1         | 0.33%   |
| qtile           | 1         | 0.33%   |
| LXDE            | 1         | 0.33%   |
| GNOME Flashback | 1         | 0.33%   |
| DWM             | 1         | 0.33%   |
| Budgie          | 1         | 0.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 241       | 80.87%  |
| Unknown | 30        | 10.07%  |
| Wayland | 22        | 7.38%   |
| Tty     | 5         | 1.68%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 165       | 55.18%  |
| SDDM    | 50        | 16.72%  |
| GDM     | 29        | 9.7%    |
| LightDM | 18        | 6.02%   |
| GDM3    | 14        | 4.68%   |
| KDM     | 12        | 4.01%   |
| TDM     | 9         | 3.01%   |
| XDM     | 1         | 0.33%   |
| Ly      | 1         | 0.33%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| en_US       | 194       | 63.4%   |
| Unknown     | 73        | 23.86%  |
| sr_RS       | 12        | 3.92%   |
| sr_RS@latin | 11        | 3.59%   |
| en_GB       | 7         | 2.29%   |
| C           | 4         | 1.31%   |
| hu_HU       | 2         | 0.65%   |
| ru_RU       | 1         | 0.33%   |
| en_IE       | 1         | 0.33%   |
| de_DE       | 1         | 0.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 160       | 54.24%  |
| BIOS | 135       | 45.76%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 233       | 77.67%  |
| Overlay | 29        | 9.67%   |
| Unknown | 26        | 8.67%   |
| Btrfs   | 10        | 3.33%   |
| Zfs     | 1         | 0.33%   |
| Tmpfs   | 1         | 0.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 173       | 58.45%  |
| GPT     | 79        | 26.69%  |
| MBR     | 44        | 14.86%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 258       | 88.66%  |
| Yes       | 33        | 11.34%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 215       | 73.63%  |
| Yes       | 77        | 26.37%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 71        | 24.74%  |
| Hewlett-Packard     | 52        | 18.12%  |
| ASUSTek Computer    | 43        | 14.98%  |
| Dell                | 40        | 13.94%  |
| Acer                | 32        | 11.15%  |
| Toshiba             | 13        | 4.53%   |
| Fujitsu Siemens     | 6         | 2.09%   |
| MSI                 | 5         | 1.74%   |
| Apple               | 5         | 1.74%   |
| Sony                | 3         | 1.05%   |
| Fujitsu             | 3         | 1.05%   |
| Samsung Electronics | 2         | 0.7%    |
| Medion              | 2         | 0.7%    |
| TWC                 | 1         | 0.35%   |
| Timi                | 1         | 0.35%   |
| Razer               | 1         | 0.35%   |
| Packard Bell        | 1         | 0.35%   |
| LG Electronics      | 1         | 0.35%   |
| IBM                 | 1         | 0.35%   |
| HUAWEI              | 1         | 0.35%   |
| Gigabyte Technology | 1         | 0.35%   |
| eMachines           | 1         | 0.35%   |
| BenQ                | 1         | 0.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                                                     | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Acer Aspire A315-31                                                                      | 6         | 2.09%   |
| Lenovo V330-15IKB 81AX                                                                   | 4         | 1.39%   |
| HP Notebook                                                                              | 4         | 1.39%   |
| Lenovo IdeaPad 330-15IKB 81DE                                                            | 3         | 1.05%   |
| ASUS X541NA                                                                              | 3         | 1.05%   |
| Unknown                                                                                  | 3         | 1.05%   |
| MSI CR500                                                                                | 2         | 0.7%    |
| Lenovo Legion Y530-15ICH 81FV                                                            | 2         | 0.7%    |
| Lenovo IdeaPad S540-14API 81NH                                                           | 2         | 0.7%    |
| Lenovo IdeaPad L340-15API 81LW                                                           | 2         | 0.7%    |
| Lenovo IdeaPad 5 14ARE05 81YM                                                            | 2         | 0.7%    |
| Lenovo IdeaPad 3 15IIL05 81WE                                                            | 2         | 0.7%    |
| Lenovo IdeaPad 110-15IBR 80T7                                                            | 2         | 0.7%    |
| Lenovo G500 20236                                                                        | 2         | 0.7%    |
| HP Pavilion Notebook                                                                     | 2         | 0.7%    |
| HP Laptop 15-ra0xx                                                                       | 2         | 0.7%    |
| HP Laptop 15-db1xxx                                                                      | 2         | 0.7%    |
| HP Laptop 15-db0xxx                                                                      | 2         | 0.7%    |
| HP G62                                                                                   | 2         | 0.7%    |
| HP 250 G5 Notebook PC                                                                    | 2         | 0.7%    |
| Fujitsu Siemens AMILO Li3710                                                             | 2         | 0.7%    |
| Dell Vostro 3500                                                                         | 2         | 0.7%    |
| Dell Latitude E5470                                                                      | 2         | 0.7%    |
| Dell Latitude 7490                                                                       | 2         | 0.7%    |
| Dell Inspiron 3593                                                                       | 2         | 0.7%    |
| Dell Inspiron 3542                                                                       | 2         | 0.7%    |
| Dell Inspiron 3537                                                                       | 2         | 0.7%    |
| ASUS X55A                                                                                | 2         | 0.7%    |
| ASUS X541NC                                                                              | 2         | 0.7%    |
| ASUS VivoBook_ASUSLaptop X580GD_N580GD                                                   | 2         | 0.7%    |
| ASUS VivoBook 15_ASUS Laptop X540MA_X543MA                                               | 2         | 0.7%    |
| Apple MacBookPro8,1                                                                      | 2         | 0.7%    |
| Acer Aspire A315-51                                                                      | 2         | 0.7%    |
| Toshiba TECRA Z50-A                                                                      | 1         | 0.35%   |
| Toshiba Satellite Pro L650                                                               | 1         | 0.35%   |
| Toshiba Satellite L755                                                                   | 1         | 0.35%   |
| Toshiba Satellite L20                                                                    | 1         | 0.35%   |
| Toshiba Satellite C870-17H                                                               | 1         | 0.35%   |
| Toshiba Satellite C850-1H6                                                               | 1         | 0.35%   |
| Toshiba Satellite C650                                                                   | 1         | 0.35%   |
| Toshiba Satellite C55-C                                                                  | 1         | 0.35%   |
| Toshiba Satellite C55-B                                                                  | 1         | 0.35%   |
| Toshiba Satellite C55-A                                                                  | 1         | 0.35%   |
| Toshiba Satellite C50-B                                                                  | 1         | 0.35%   |
| Toshiba Satellite C50-A-1G3                                                              | 1         | 0.35%   |
| Toshiba QOSMIO F50                                                                       | 1         | 0.35%   |
| Timi TM1613                                                                              | 1         | 0.35%   |
| Sony VPCZ21X9E                                                                           | 1         | 0.35%   |
| Sony VPCEE23FX                                                                           | 1         | 0.35%   |
| Sony VGN-FE31Z                                                                           | 1         | 0.35%   |
| Samsung N250P/N145P                                                                      | 1         | 0.35%   |
| Samsung 350V5C/350V5X/350V4C/350V4X/351V5C/351V5X/351V4C/351V4X/3540VC/3540VX/3440VC/344 | 1         | 0.35%   |
| Razer Blade                                                                              | 1         | 0.35%   |
| Packard Bell EasyNote TS11HR                                                             | 1         | 0.35%   |
| MSI MS-16Y1                                                                              | 1         | 0.35%   |
| MSI GT70 2PC                                                                             | 1         | 0.35%   |
| MSI CR610                                                                                | 1         | 0.35%   |
| Medion X781X/X782X                                                                       | 1         | 0.35%   |
| Medion P6812                                                                             | 1         | 0.35%   |
| LG LW70-JJKG                                                                             | 1         | 0.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 28        | 9.76%   |
| Lenovo IdeaPad        | 24        | 8.36%   |
| Lenovo ThinkPad       | 23        | 8.01%   |
| Dell Inspiron         | 20        | 6.97%   |
| ASUS VivoBook         | 14        | 4.88%   |
| HP Laptop             | 13        | 4.53%   |
| Toshiba Satellite     | 11        | 3.83%   |
| Dell Latitude         | 11        | 3.83%   |
| HP ProBook            | 8         | 2.79%   |
| HP Pavilion           | 6         | 2.09%   |
| Lenovo Legion         | 5         | 1.74%   |
| HP EliteBook          | 5         | 1.74%   |
| HP 250                | 5         | 1.74%   |
| Fujitsu Siemens AMILO | 5         | 1.74%   |
| Lenovo V330-15IKB     | 4         | 1.39%   |
| HP Notebook           | 4         | 1.39%   |
| Dell Vostro           | 4         | 1.39%   |
| HP Compaq             | 3         | 1.05%   |
| Fujitsu LIFEBOOK      | 3         | 1.05%   |
| ASUS X541NA           | 3         | 1.05%   |
| Unknown               | 3         | 1.05%   |
| MSI CR500             | 2         | 0.7%    |
| Lenovo G500           | 2         | 0.7%    |
| HP G62                | 2         | 0.7%    |
| Dell Precision        | 2         | 0.7%    |
| ASUS X55A             | 2         | 0.7%    |
| ASUS X541NC           | 2         | 0.7%    |
| ASUS TUF              | 2         | 0.7%    |
| Apple MacBookPro8     | 2         | 0.7%    |
| Acer Nitro            | 2         | 0.7%    |
| Toshiba TECRA         | 1         | 0.35%   |
| Toshiba QOSMIO        | 1         | 0.35%   |
| Timi TM1613           | 1         | 0.35%   |
| Sony VPCZ21X9E        | 1         | 0.35%   |
| Sony VPCEE23FX        | 1         | 0.35%   |
| Sony VGN-FE31Z        | 1         | 0.35%   |
| Samsung N250P         | 1         | 0.35%   |
| Samsung 350V5C        | 1         | 0.35%   |
| Razer Blade           | 1         | 0.35%   |
| Packard Bell EasyNote | 1         | 0.35%   |
| MSI MS-16Y1           | 1         | 0.35%   |
| MSI GT70              | 1         | 0.35%   |
| MSI CR610             | 1         | 0.35%   |
| Medion X781X          | 1         | 0.35%   |
| Medion P6812          | 1         | 0.35%   |
| LG LW70-JJKG          | 1         | 0.35%   |
| Lenovo Yoga           | 1         | 0.35%   |
| Lenovo V310-15ISK     | 1         | 0.35%   |
| Lenovo V15-ADA        | 1         | 0.35%   |
| Lenovo V130-14IGM     | 1         | 0.35%   |
| Lenovo V110-15AST     | 1         | 0.35%   |
| Lenovo ThinkBook      | 1         | 0.35%   |
| Lenovo G560           | 1         | 0.35%   |
| Lenovo G555           | 1         | 0.35%   |
| Lenovo G505           | 1         | 0.35%   |
| Lenovo G50-30         | 1         | 0.35%   |
| Lenovo B50-45         | 1         | 0.35%   |
| Lenovo 3000           | 1         | 0.35%   |
| IBM ThinkPad          | 1         | 0.35%   |
| HUAWEI NBLB-WAX9N     | 1         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 39        | 13.59%  |
| 2017 | 28        | 9.76%   |
| 2019 | 25        | 8.71%   |
| 2020 | 24        | 8.36%   |
| 2016 | 24        | 8.36%   |
| 2011 | 24        | 8.36%   |
| 2013 | 19        | 6.62%   |
| 2012 | 17        | 5.92%   |
| 2010 | 17        | 5.92%   |
| 2014 | 15        | 5.23%   |
| 2008 | 13        | 4.53%   |
| 2015 | 12        | 4.18%   |
| 2009 | 8         | 2.79%   |
| 2007 | 7         | 2.44%   |
| 2021 | 6         | 2.09%   |
| 2006 | 6         | 2.09%   |
| 2005 | 2         | 0.7%    |
| 2022 | 1         | 0.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 287       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 264       | 90.41%  |
| Enabled  | 28        | 9.59%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 287       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 93        | 31.74%  |
| 4.01-8.0   | 76        | 25.94%  |
| 8.01-16.0  | 48        | 16.38%  |
| 16.01-24.0 | 36        | 12.29%  |
| 1.01-2.0   | 18        | 6.14%   |
| 2.01-3.0   | 10        | 3.41%   |
| 32.01-64.0 | 8         | 2.73%   |
| 24.01-32.0 | 3         | 1.02%   |
| 0.51-1.0   | 1         | 0.34%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 122       | 37.89%  |
| 2.01-3.0  | 75        | 23.29%  |
| 0.51-1.0  | 48        | 14.91%  |
| 3.01-4.0  | 37        | 11.49%  |
| 4.01-8.0  | 31        | 9.63%   |
| 8.01-16.0 | 8         | 2.48%   |
| 0.01-0.5  | 1         | 0.31%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 224       | 75.93%  |
| 2      | 58        | 19.66%  |
| 0      | 7         | 2.37%   |
| 3      | 6         | 2.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 162       | 55.86%  |
| Yes       | 128       | 44.14%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 256       | 89.2%   |
| No        | 31        | 10.8%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 287       | 99.65%  |
| No        | 1         | 0.35%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 230       | 79.58%  |
| No        | 59        | 20.42%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Serbia  | 287       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Belgrade           | 188       | 61.44%  |
| Novi Sad           | 31        | 10.13%  |
| Niš               | 17        | 5.56%   |
| Novi Belgrade      | 4         | 1.31%   |
| Leskovac           | 4         | 1.31%   |
| Zrenjanin          | 3         | 0.98%   |
| Subotica           | 3         | 0.98%   |
| Senta              | 3         | 0.98%   |
| Savski Venac       | 3         | 0.98%   |
| Pančevo           | 3         | 0.98%   |
| Lozovik            | 3         | 0.98%   |
| Kovin              | 3         | 0.98%   |
| Varvarin           | 2         | 0.65%   |
| Novi Karlovci      | 2         | 0.65%   |
| Kragujevac         | 2         | 0.65%   |
| Jagodina           | 2         | 0.65%   |
| Branicevo          | 2         | 0.65%   |
| Becej              | 2         | 0.65%   |
| Backa Topola       | 2         | 0.65%   |
| Valjevo            | 1         | 0.33%   |
| Užice             | 1         | 0.33%   |
| UÅ¾ice           | 1         | 0.33%   |
| Trstenik           | 1         | 0.33%   |
| Stara Pazova       | 1         | 0.33%   |
| Sabac              | 1         | 0.33%   |
| Ruma               | 1         | 0.33%   |
| Ripanj             | 1         | 0.33%   |
| Pukovac            | 1         | 0.33%   |
| Požarevac         | 1         | 0.33%   |
| New Belgrade       | 1         | 0.33%   |
| Lazarevac          | 1         | 0.33%   |
| Kruševac          | 1         | 0.33%   |
| Kraljevo           | 1         | 0.33%   |
| Guca               | 1         | 0.33%   |
| Grocka             | 1         | 0.33%   |
| Cuprija            | 1         | 0.33%   |
| Cibukovac          | 1         | 0.33%   |
| Čačak            | 1         | 0.33%   |
| Bor                | 1         | 0.33%   |
| Boljevac           | 1         | 0.33%   |
| Beloinje           | 1         | 0.33%   |
| Basaid             | 1         | 0.33%   |
| Banatsko Novo Selo | 1         | 0.33%   |
| Backi Petrovac     | 1         | 0.33%   |
| Arangelovac        | 1         | 0.33%   |
| Aldinac            | 1         | 0.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Seagate                 | 47        | 55     | 14.07%  |
| WDC                     | 46        | 68     | 13.77%  |
| Toshiba                 | 43        | 53     | 12.87%  |
| Samsung Electronics     | 37        | 48     | 11.08%  |
| Kingston                | 24        | 26     | 7.19%   |
| Hitachi                 | 18        | 18     | 5.39%   |
| SK hynix                | 16        | 20     | 4.79%   |
| SanDisk                 | 12        | 18     | 3.59%   |
| Unknown                 | 11        | 12     | 3.29%   |
| Intel                   | 11        | 20     | 3.29%   |
| Patriot                 | 9         | 11     | 2.69%   |
| Micron Technology       | 8         | 8      | 2.4%    |
| HGST                    | 8         | 17     | 2.4%    |
| Fujitsu                 | 5         | 5      | 1.5%    |
| SPCC                    | 4         | 5      | 1.2%    |
| Transcend               | 3         | 3      | 0.9%    |
| KIOXIA                  | 3         | 3      | 0.9%    |
| Gigabyte Technology     | 3         | 3      | 0.9%    |
| GeIL                    | 3         | 3      | 0.9%    |
| A-DATA Technology       | 3         | 3      | 0.9%    |
| Union Memory            | 2         | 2      | 0.6%    |
| Phison                  | 2         | 3      | 0.6%    |
| LITEON                  | 2         | 3      | 0.6%    |
| Crucial                 | 2         | 2      | 0.6%    |
| Verbatim                | 1         | 1      | 0.3%    |
| Union Memory (Shenzhen) | 1         | 1      | 0.3%    |
| SSSTC                   | 1         | 1      | 0.3%    |
| Realtek Semiconductor   | 1         | 4      | 0.3%    |
| PNY                     | 1         | 1      | 0.3%    |
| Netac                   | 1         | 1      | 0.3%    |
| JMicron Technology      | 1         | 1      | 0.3%    |
| IBM/Hitachi             | 1         | 1      | 0.3%    |
| HUAWEI                  | 1         | 1      | 0.3%    |
| Biostar                 | 1         | 1      | 0.3%    |
| AMD                     | 1         | 1      | 0.3%    |
| Unknown                 | 1         | 1      | 0.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB          | 16        | 4.75%   |
| Toshiba MQ01ABF050 500GB                | 12        | 3.56%   |
| Seagate ST500LT012-1DG142 500GB         | 8         | 2.37%   |
| Kingston SA400S37240G 240GB SSD         | 6         | 1.78%   |
| Toshiba MQ01ABD100 1TB                  | 5         | 1.48%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 5         | 1.48%   |
| Toshiba MQ04ABF100 1TB                  | 4         | 1.19%   |
| Seagate ST500LT012-9WS142 500GB         | 4         | 1.19%   |
| Samsung NVMe SSD Drive 256GB            | 4         | 1.19%   |
| Kingston SA400S37120G 120GB SSD         | 4         | 1.19%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB    | 3         | 0.89%   |
| SK hynix NVMe SSD Drive 256GB           | 3         | 0.89%   |
| SanDisk NVMe SSD Drive 256GB            | 3         | 0.89%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD     | 3         | 0.89%   |
| Kingston SA400S37480G 480GB SSD         | 3         | 0.89%   |
| Kingston RBUSC180DS37256GJ 256GB SSD    | 3         | 0.89%   |
| Hitachi HTS545050A7E380 500GB           | 3         | 0.89%   |
| GeIL R3_128GB                           | 3         | 0.89%   |
| WDC WD5000LPVX-75V0TT0 500GB            | 2         | 0.59%   |
| WDC WD5000LPCX-80VHAT1 500GB            | 2         | 0.59%   |
| WDC WD5000LPCX-24VHAT0 500GB            | 2         | 0.59%   |
| WDC WD3200BEVT-22ZCT0 320GB             | 2         | 0.59%   |
| WDC WD3200BEVT-22A23T0 320GB            | 2         | 0.59%   |
| WDC WD2500BEVS-22UST0 250GB             | 2         | 0.59%   |
| WDC WD1200BEVS-22UST0 120GB             | 2         | 0.59%   |
| WDC WD10SPZX-24Z10 1TB                  | 2         | 0.59%   |
| WDC WD10SPZX-21Z10T0 1TB                | 2         | 0.59%   |
| WDC PC SN530 SDBPNPZ-256G-1002 256GB    | 2         | 0.59%   |
| Unknown MMC Card  32GB                  | 2         | 0.59%   |
| Union Memory UMIS RPJTJ512MEE1OWX 512GB | 2         | 0.59%   |
| Toshiba NVMe SSD Drive 512GB            | 2         | 0.59%   |
| Toshiba NVMe SSD Drive 256GB            | 2         | 0.59%   |
| Toshiba MQ01ABD050 500GB                | 2         | 0.59%   |
| Toshiba MK1637GSX 160GB                 | 2         | 0.59%   |
| SK hynix HFS128G32TNF-N3A0A 128GB SSD   | 2         | 0.59%   |
| Seagate ST9500325AS 500GB               | 2         | 0.59%   |
| SanDisk SD9SN8W256G1014 256GB SSD       | 2         | 0.59%   |
| SanDisk NVMe SSD Drive 512GB            | 2         | 0.59%   |
| Samsung SSD 860 EVO M.2 500GB           | 2         | 0.59%   |
| Samsung SSD 860 EVO 500GB               | 2         | 0.59%   |
| Samsung SSD 850 EVO 250GB               | 2         | 0.59%   |
| Samsung MZNLN128HAHQ-000H1 128GB SSD    | 2         | 0.59%   |
| Patriot Burst 240GB SSD                 | 2         | 0.59%   |
| Patriot Blast 240GB SSD                 | 2         | 0.59%   |
| KIOXIA KBG40ZNS512G NVMe 512GB          | 2         | 0.59%   |
| Intel NVMe SSD Drive 256GB              | 2         | 0.59%   |
| Hitachi HTS547575A9E384 752GB           | 2         | 0.59%   |
| Hitachi HTS545032B9A300 320GB           | 2         | 0.59%   |
| Hitachi HTS543216L9A300 160GB           | 2         | 0.59%   |
| HGST HTS721010A9E630 1TB                | 2         | 0.59%   |
| HGST HTS545050A7E680 500GB              | 2         | 0.59%   |
| Gigabyte GP-GSTFS31240GNTD 240GB        | 2         | 0.59%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD        | 1         | 0.3%    |
| WDC WD7500BPVX-60JC3T0 752GB            | 1         | 0.3%    |
| WDC WD7500BPKX-75HPJT0 752GB            | 1         | 0.3%    |
| WDC WD5000LPLX-00ZNTT0 500GB            | 1         | 0.3%    |
| WDC WD5000LPCX-75VHAT0 500GB            | 1         | 0.3%    |
| WDC WD5000LPCX-60VHAT0 500GB            | 1         | 0.3%    |
| WDC WD5000LPCX-21VHAT0 500GB            | 1         | 0.3%    |
| WDC WD5000BPKX-00HPJT0 500GB            | 1         | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 47        | 55     | 30.13%  |
| WDC                 | 38        | 59     | 24.36%  |
| Toshiba             | 37        | 46     | 23.72%  |
| Hitachi             | 18        | 18     | 11.54%  |
| HGST                | 8         | 17     | 5.13%   |
| Fujitsu             | 5         | 5      | 3.21%   |
| Unknown             | 1         | 1      | 0.64%   |
| Samsung Electronics | 1         | 2      | 0.64%   |
| IBM/Hitachi         | 1         | 1      | 0.64%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 22        | 27     | 22.92%  |
| Kingston            | 21        | 22     | 21.88%  |
| Patriot             | 9         | 11     | 9.38%   |
| SanDisk             | 6         | 10     | 6.25%   |
| Micron Technology   | 5         | 5      | 5.21%   |
| SPCC                | 4         | 5      | 4.17%   |
| Transcend           | 3         | 3      | 3.13%   |
| SK hynix            | 3         | 3      | 3.13%   |
| Intel               | 3         | 4      | 3.13%   |
| GeIL                | 3         | 3      | 3.13%   |
| Toshiba             | 2         | 2      | 2.08%   |
| LITEON              | 2         | 3      | 2.08%   |
| Gigabyte Technology | 2         | 2      | 2.08%   |
| Crucial             | 2         | 2      | 2.08%   |
| A-DATA Technology   | 2         | 2      | 2.08%   |
| WDC                 | 1         | 2      | 1.04%   |
| Verbatim            | 1         | 1      | 1.04%   |
| SSSTC               | 1         | 1      | 1.04%   |
| PNY                 | 1         | 1      | 1.04%   |
| Netac               | 1         | 1      | 1.04%   |
| Biostar             | 1         | 1      | 1.04%   |
| AMD                 | 1         | 1      | 1.04%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 156       | 204    | 47.71%  |
| SSD     | 90        | 112    | 27.52%  |
| NVMe    | 70        | 96     | 21.41%  |
| MMC     | 10        | 11     | 3.06%   |
| Unknown | 1         | 1      | 0.31%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 222       | 314    | 72.79%  |
| NVMe | 69        | 95     | 22.62%  |
| MMC  | 10        | 11     | 3.28%   |
| SAS  | 4         | 4      | 1.31%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 176       | 223    | 73.64%  |
| 0.51-1.0   | 61        | 89     | 25.52%  |
| 1.01-2.0   | 2         | 4      | 0.84%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 93        | 29.9%   |
| 251-500        | 85        | 27.33%  |
| 501-1000       | 38        | 12.22%  |
| 1-20           | 28        | 9%      |
| 51-100         | 25        | 8.04%   |
| 21-50          | 20        | 6.43%   |
| Unknown        | 12        | 3.86%   |
| 1001-2000      | 6         | 1.93%   |
| 2001-3000      | 3         | 0.96%   |
| More than 3000 | 1         | 0.32%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 137       | 42.81%  |
| 21-50     | 61        | 19.06%  |
| 101-250   | 41        | 12.81%  |
| 51-100    | 39        | 12.19%  |
| 251-500   | 20        | 6.25%   |
| Unknown   | 12        | 3.75%   |
| 501-1000  | 8         | 2.5%    |
| 1001-2000 | 2         | 0.63%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Notebooks | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABF050 500GB                | 2         | 2      | 8.7%    |
| WDC WD5000BEVT-24A0RT0 500GB            | 1         | 1      | 4.35%   |
| WDC WD3200BEVT-22ZCT0 320GB             | 1         | 1      | 4.35%   |
| Toshiba MQ01ABD032 320GB                | 1         | 1      | 4.35%   |
| Toshiba MK1637GSX 160GB                 | 1         | 1      | 4.35%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD | 1         | 1      | 4.35%   |
| SPCC Solid State DiskB27 32GB           | 1         | 1      | 4.35%   |
| Seagate ST980813AS 80GB                 | 1         | 1      | 4.35%   |
| Seagate ST9250827AS 250GB               | 1         | 1      | 4.35%   |
| Seagate ST9120822AS 120GB               | 1         | 1      | 4.35%   |
| Seagate ST750LM022 HN-M750MBB 752GB     | 1         | 1      | 4.35%   |
| Seagate ST500LT012-9WS142 500GB         | 1         | 1      | 4.35%   |
| Seagate ST500LT012-1DG142 500GB         | 1         | 2      | 4.35%   |
| Seagate ST1000LM035-1RK172 1TB          | 1         | 1      | 4.35%   |
| Samsung Electronics HM120JI 120GB       | 1         | 2      | 4.35%   |
| Hitachi HTS722080K9A300 80GB            | 1         | 1      | 4.35%   |
| Hitachi HTS545050A7E380 500GB           | 1         | 1      | 4.35%   |
| Hitachi HTS541612J9SA00 120GB           | 1         | 1      | 4.35%   |
| HGST HTS725050A7E630 500GB              | 1         | 5      | 4.35%   |
| HGST HTS721010A9E630 1TB                | 1         | 2      | 4.35%   |
| Fujitsu MHZ2160BH G1 160GB              | 1         | 1      | 4.35%   |
| Fujitsu MHW2160BH PL 160GB              | 1         | 1      | 4.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 8      | 30.43%  |
| Toshiba             | 5         | 5      | 21.74%  |
| Hitachi             | 3         | 3      | 13.04%  |
| WDC                 | 2         | 2      | 8.7%    |
| HGST                | 2         | 7      | 8.7%    |
| Fujitsu             | 2         | 2      | 8.7%    |
| SPCC                | 1         | 1      | 4.35%   |
| Samsung Electronics | 1         | 2      | 4.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 8      | 33.33%  |
| Toshiba             | 4         | 4      | 19.05%  |
| Hitachi             | 3         | 3      | 14.29%  |
| WDC                 | 2         | 2      | 9.52%   |
| HGST                | 2         | 7      | 9.52%   |
| Fujitsu             | 2         | 2      | 9.52%   |
| Samsung Electronics | 1         | 2      | 4.76%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 21        | 28     | 91.3%   |
| SSD  | 2         | 2      | 8.7%    |

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
| Detected | 178       | 280    | 59.73%  |
| Works    | 97        | 114    | 32.55%  |
| Malfunc  | 23        | 30     | 7.72%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 220       | 66.47%  |
| AMD                          | 36        | 10.88%  |
| Samsung Electronics          | 19        | 5.74%   |
| SK hynix                     | 13        | 3.93%   |
| SanDisk                      | 13        | 3.93%   |
| Nvidia                       | 5         | 1.51%   |
| Toshiba America Info Systems | 4         | 1.21%   |
| KIOXIA                       | 4         | 1.21%   |
| Union Memory (Shenzhen)      | 3         | 0.91%   |
| Phison Electronics           | 3         | 0.91%   |
| Micron Technology            | 3         | 0.91%   |
| Kingston Technology Company  | 3         | 0.91%   |
| VIA Technologies             | 1         | 0.3%    |
| Silicon Image                | 1         | 0.3%    |
| Realtek Semiconductor        | 1         | 0.3%    |
| JMicron Technology           | 1         | 0.3%    |
| ADATA Technology             | 1         | 0.3%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 29        | 8.08%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 28        | 7.8%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 21        | 5.85%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 20        | 5.57%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 17        | 4.74%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 13        | 3.62%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 9         | 2.51%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 9         | 2.51%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 8         | 2.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 8         | 2.23%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 8         | 2.23%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 8         | 2.23%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 8         | 2.23%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 8         | 2.23%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 7         | 1.95%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 7         | 1.95%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 7         | 1.95%   |
| SK hynix BC511                                                                   | 6         | 1.67%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 6         | 1.67%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 6         | 1.67%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 6         | 1.67%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 6         | 1.67%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 5         | 1.39%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 5         | 1.39%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 4         | 1.11%   |
| SanDisk Non-Volatile memory controller                                           | 4         | 1.11%   |
| Samsung NVMe SSD Controller 980                                                  | 4         | 1.11%   |
| Nvidia MCP79 AHCI Controller                                                     | 4         | 1.11%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 4         | 1.11%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 4         | 1.11%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 4         | 1.11%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 3         | 0.84%   |
| SK hynix Non-Volatile memory controller                                          | 3         | 0.84%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 3         | 0.84%   |
| Micron Non-Volatile memory controller                                            | 3         | 0.84%   |
| Intel SSD 660P Series                                                            | 3         | 0.84%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3         | 0.84%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 3         | 0.84%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 3         | 0.84%   |
| Toshiba America Info Systems NVMe Controller                                     | 2         | 0.56%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 2         | 0.56%   |
| SanDisk PC SN520 NVMe SSD                                                        | 2         | 0.56%   |
| Phison PS5013 E13 NVMe Controller                                                | 2         | 0.56%   |
| Intel Tiger Lake-LP SATA Controller                                              | 2         | 0.56%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 2         | 0.56%   |
| Intel SATA Controller [RAID mode]                                                | 2         | 0.56%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 0.56%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 0.56%   |
| Intel 82801FBM (ICH6M) SATA Controller                                           | 2         | 0.56%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 2         | 0.56%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 1         | 0.28%   |
| VIA VT8237A SATA 2-Port Controller                                               | 1         | 0.28%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 1         | 0.28%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 0.28%   |
| SK hynix Gold P31 SSD                                                            | 1         | 0.28%   |
| Silicon Image SiI 3531 [SATALink/SATARaid] Serial ATA Controller                 | 1         | 0.28%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 0.28%   |
| Realtek RTS5763DL NVMe SSD Controller                                            | 1         | 0.28%   |
| Phison E12 NVMe Controller                                                       | 1         | 0.28%   |
| Nvidia MCP79 SATA Controller                                                     | 1         | 0.28%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 229       | 65.43%  |
| NVMe | 73        | 20.86%  |
| IDE  | 28        | 8%      |
| RAID | 20        | 5.71%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 240       | 83.62%  |
| AMD    | 47        | 16.38%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 7         | 2.44%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 6         | 2.09%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 5         | 1.74%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 1.74%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 1.74%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 5         | 1.74%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 5         | 1.74%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 5         | 1.74%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 5         | 1.74%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 1.39%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 4         | 1.39%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 4         | 1.39%   |
| Intel Celeron CPU 1000M @ 1.80GHz             | 4         | 1.39%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 4         | 1.39%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 4         | 1.39%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 4         | 1.39%   |
| Intel Pentium M processor 1.86GHz             | 3         | 1.05%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 3         | 1.05%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 1.05%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 3         | 1.05%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 3         | 1.05%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 3         | 1.05%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 1.05%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 3         | 1.05%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 3         | 1.05%   |
| Intel Core 2 CPU T5600 @ 1.83GHz              | 3         | 1.05%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 3         | 1.05%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 2         | 0.7%    |
| Intel Pentium CPU N3540 @ 2.16GHz             | 2         | 0.7%    |
| Intel Pentium CPU B960 @ 2.20GHz              | 2         | 0.7%    |
| Intel Pentium CPU B950 @ 2.10GHz              | 2         | 0.7%    |
| Intel Pentium CPU 4417U @ 2.30GHz             | 2         | 0.7%    |
| Intel Pentium CPU 3825U @ 1.90GHz             | 2         | 0.7%    |
| Intel Core i7-8665U CPU @ 1.90GHz             | 2         | 0.7%    |
| Intel Core i7-8650U CPU @ 1.90GHz             | 2         | 0.7%    |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 2         | 0.7%    |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 0.7%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 0.7%    |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 0.7%    |
| Intel Core i7-4702MQ CPU @ 2.20GHz            | 2         | 0.7%    |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 2         | 0.7%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 0.7%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 0.7%    |
| Intel Core i5-7300U CPU @ 2.60GHz             | 2         | 0.7%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 0.7%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 0.7%    |
| Intel Core i5-2540M CPU @ 2.60GHz             | 2         | 0.7%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 0.7%    |
| Intel Core i5-10300H CPU @ 2.50GHz            | 2         | 0.7%    |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 2         | 0.7%    |
| Intel Core i3-8130U CPU @ 2.20GHz             | 2         | 0.7%    |
| Intel Core i3-4030U CPU @ 1.90GHz             | 2         | 0.7%    |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 0.7%    |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 2         | 0.7%    |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 2         | 0.7%    |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 2         | 0.7%    |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 2         | 0.7%    |
| Intel Celeron N4020 CPU @ 1.10GHz             | 2         | 0.7%    |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 0.7%    |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 0.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 56        | 19.51%  |
| Intel Core i5           | 54        | 18.82%  |
| Intel Core i3           | 31        | 10.8%   |
| Intel Celeron           | 30        | 10.45%  |
| Intel Pentium           | 26        | 9.06%   |
| AMD Ryzen 5             | 17        | 5.92%   |
| Intel Core 2 Duo        | 13        | 4.53%   |
| AMD Ryzen 7             | 9         | 3.14%   |
| Intel Atom              | 7         | 2.44%   |
| Other                   | 6         | 2.09%   |
| Intel Core 2            | 4         | 1.39%   |
| Intel Pentium M         | 3         | 1.05%   |
| Intel Pentium Dual      | 3         | 1.05%   |
| AMD Ryzen 3             | 3         | 1.05%   |
| AMD A8                  | 3         | 1.05%   |
| Intel Pentium Silver    | 2         | 0.7%    |
| Intel Pentium Dual-Core | 2         | 0.7%    |
| Intel Genuine           | 2         | 0.7%    |
| AMD Athlon X2           | 2         | 0.7%    |
| AMD Athlon II Dual-Core | 2         | 0.7%    |
| AMD Athlon II           | 2         | 0.7%    |
| AMD A4                  | 2         | 0.7%    |
| Intel Core Duo          | 1         | 0.35%   |
| Intel Celeron M         | 1         | 0.35%   |
| AMD V120                | 1         | 0.35%   |
| AMD Turion 64 X2 Mobile | 1         | 0.35%   |
| AMD Phenom II           | 1         | 0.35%   |
| AMD E2                  | 1         | 0.35%   |
| AMD E1                  | 1         | 0.35%   |
| AMD A6                  | 1         | 0.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 154       | 53.66%  |
| 4      | 99        | 34.49%  |
| 6      | 15        | 5.23%   |
| 1      | 14        | 4.88%   |
| 8      | 5         | 1.74%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 287       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 180       | 62.72%  |
| 1      | 107       | 37.28%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 268       | 93.06%  |
| Unknown        | 11        | 3.82%   |
| 32-bit         | 9         | 3.13%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 42        | 14%     |
| 0x206a7    | 26        | 8.67%   |
| 0x806ea    | 16        | 5.33%   |
| 0x406e3    | 14        | 4.67%   |
| 0x306a9    | 14        | 4.67%   |
| 0x506c9    | 12        | 4%      |
| 0x906ea    | 10        | 3.33%   |
| 0x806e9    | 8         | 2.67%   |
| 0x706e5    | 8         | 2.67%   |
| 0x306d4    | 8         | 2.67%   |
| 0x6fd      | 7         | 2.33%   |
| 0x40651    | 7         | 2.33%   |
| 0x08108102 | 7         | 2.33%   |
| 0x906e9    | 6         | 2%      |
| 0x806ec    | 6         | 2%      |
| 0x406c4    | 6         | 2%      |
| 0x08108109 | 6         | 2%      |
| 0x806c1    | 5         | 1.67%   |
| 0x506e3    | 5         | 1.67%   |
| 0x306c3    | 5         | 1.67%   |
| 0x30678    | 5         | 1.67%   |
| 0x10676    | 5         | 1.67%   |
| 0xa0652    | 4         | 1.33%   |
| 0x806eb    | 4         | 1.33%   |
| 0x1067a    | 4         | 1.33%   |
| 0x706a8    | 3         | 1%      |
| 0x706a1    | 3         | 1%      |
| 0x6d8      | 3         | 1%      |
| 0x30673    | 3         | 1%      |
| 0x20655    | 3         | 1%      |
| 0x106ca    | 3         | 1%      |
| 0x08608103 | 3         | 1%      |
| 0x0810100b | 3         | 1%      |
| 0x6ec      | 2         | 0.67%   |
| 0x6e8      | 2         | 0.67%   |
| 0x406c3    | 2         | 0.67%   |
| 0x20652    | 2         | 0.67%   |
| 0x106c2    | 2         | 0.67%   |
| 0x08600104 | 2         | 0.67%   |
| 0x08101007 | 2         | 0.67%   |
| 0x07030104 | 2         | 0.67%   |
| 0x06006704 | 2         | 0.67%   |
| 0x010000c8 | 2         | 0.67%   |
| 0x906ed    | 1         | 0.33%   |
| 0x6fb      | 1         | 0.33%   |
| 0x6fa      | 1         | 0.33%   |
| 0x6f6      | 1         | 0.33%   |
| 0x6f2      | 1         | 0.33%   |
| 0x0a50000c | 1         | 0.33%   |
| 0x08608102 | 1         | 0.33%   |
| 0x08600106 | 1         | 0.33%   |
| 0x08600102 | 1         | 0.33%   |
| 0x08200103 | 1         | 0.33%   |
| 0x07030105 | 1         | 0.33%   |
| 0x0700010f | 1         | 0.33%   |
| 0x06001119 | 1         | 0.33%   |
| 0x02000057 | 1         | 0.33%   |
| 0x02000032 | 1         | 0.33%   |
| 0x010000b6 | 1         | 0.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 53        | 18.47%  |
| SandyBridge     | 29        | 10.1%   |
| Skylake         | 20        | 6.97%   |
| Silvermont      | 17        | 5.92%   |
| Haswell         | 17        | 5.92%   |
| IvyBridge       | 15        | 5.23%   |
| Core            | 14        | 4.88%   |
| Zen+            | 13        | 4.53%   |
| Goldmont        | 13        | 4.53%   |
| Westmere        | 9         | 3.14%   |
| Penryn          | 9         | 3.14%   |
| Broadwell       | 9         | 3.14%   |
| IceLake         | 8         | 2.79%   |
| Zen             | 7         | 2.44%   |
| P6              | 7         | 2.44%   |
| K10             | 6         | 2.09%   |
| Goldmont plus   | 6         | 2.09%   |
| Zen 2           | 5         | 1.74%   |
| TigerLake       | 5         | 1.74%   |
| Bonnell         | 5         | 1.74%   |
| CometLake       | 4         | 1.39%   |
| Unknown         | 4         | 1.39%   |
| Puma            | 3         | 1.05%   |
| Piledriver      | 2         | 0.7%    |
| K8 & K10 hybrid | 2         | 0.7%    |
| Excavator       | 2         | 0.7%    |
| Zen 3           | 1         | 0.35%   |
| K8 Hammer       | 1         | 0.35%   |
| Jaguar          | 1         | 0.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 216       | 57.45%  |
| Nvidia           | 80        | 21.28%  |
| AMD              | 79        | 21.01%  |
| VIA Technologies | 1         | 0.27%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 26        | 6.63%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 15        | 3.83%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 14        | 3.57%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 14        | 3.57%   |
| Intel UHD Graphics 620                                                                   | 12        | 3.06%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 12        | 3.06%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 11        | 2.81%   |
| Intel HD Graphics 620                                                                    | 9         | 2.3%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9         | 2.3%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 9         | 2.3%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 8         | 2.04%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 8         | 2.04%   |
| Intel HD Graphics 500                                                                    | 8         | 2.04%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 2.04%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 8         | 2.04%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 8         | 2.04%   |
| Intel HD Graphics 5500                                                                   | 7         | 1.79%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 1.53%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 1.53%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 6         | 1.53%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 6         | 1.53%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 1.28%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 1.28%   |
| Intel HD Graphics 630                                                                    | 5         | 1.28%   |
| Intel HD Graphics 530                                                                    | 5         | 1.28%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 5         | 1.28%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 5         | 1.28%   |
| AMD Renoir                                                                               | 5         | 1.28%   |
| Nvidia GP108M [GeForce MX150]                                                            | 4         | 1.02%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 4         | 1.02%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 1.02%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 1.02%   |
| AMD Lucienne                                                                             | 4         | 1.02%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.77%   |
| Nvidia GP108M [GeForce MX230]                                                            | 3         | 0.77%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 0.77%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 0.77%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 0.77%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 0.77%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 0.77%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 3         | 0.77%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 3         | 0.77%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.51%   |
| Nvidia TU117M                                                                            | 2         | 0.51%   |
| Nvidia MCP79 [GeForce 8200M G]                                                           | 2         | 0.51%   |
| Nvidia GP108M [GeForce MX330]                                                            | 2         | 0.51%   |
| Nvidia GM108M [GeForce MX110]                                                            | 2         | 0.51%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 2         | 0.51%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 2         | 0.51%   |
| Nvidia GM107GLM [Quadro M2000M]                                                          | 2         | 0.51%   |
| Nvidia GK107M [GeForce 810M]                                                             | 2         | 0.51%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 2         | 0.51%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 2         | 0.51%   |
| Nvidia C79 [GeForce 9400M]                                                               | 2         | 0.51%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 2         | 0.51%   |
| Intel HD Graphics                                                                        | 2         | 0.51%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 0.51%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.51%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 2         | 0.51%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 134       | 46.37%  |
| Intel + Nvidia | 61        | 21.11%  |
| 1 x AMD        | 45        | 15.57%  |
| Intel + AMD    | 23        | 7.96%   |
| 1 x Nvidia     | 13        | 4.5%    |
| 2 x AMD        | 6         | 2.08%   |
| AMD + Nvidia   | 5         | 1.73%   |
| 2 x Nvidia     | 1         | 0.35%   |
| 1 x VIA        | 1         | 0.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 248       | 84.93%  |
| Proprietary | 34        | 11.64%  |
| Unknown     | 10        | 3.42%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 161       | 54.39%  |
| 1.01-2.0   | 58        | 19.59%  |
| 0.01-0.5   | 39        | 13.18%  |
| 3.01-4.0   | 25        | 8.45%   |
| 0.51-1.0   | 13        | 4.39%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 69        | 21.5%   |
| BOE                     | 49        | 15.26%  |
| LG Display              | 47        | 14.64%  |
| Chimei Innolux          | 43        | 13.4%   |
| Samsung Electronics     | 31        | 9.66%   |
| Lenovo                  | 9         | 2.8%    |
| Dell                    | 8         | 2.49%   |
| Chi Mei Optoelectronics | 8         | 2.49%   |
| PANDA                   | 7         | 2.18%   |
| Philips                 | 5         | 1.56%   |
| LG Philips              | 5         | 1.56%   |
| Hewlett-Packard         | 5         | 1.56%   |
| Apple                   | 5         | 1.56%   |
| Sharp                   | 4         | 1.25%   |
| CPT                     | 4         | 1.25%   |
| Sony                    | 3         | 0.93%   |
| InfoVision              | 3         | 0.93%   |
| BenQ                    | 3         | 0.93%   |
| Goldstar                | 2         | 0.62%   |
| ViewSonic               | 1         | 0.31%   |
| Unknown                 | 1         | 0.31%   |
| Toshiba                 | 1         | 0.31%   |
| SKY                     | 1         | 0.31%   |
| Seiko/Epson             | 1         | 0.31%   |
| LPL                     | 1         | 0.31%   |
| InnoLux Display         | 1         | 0.31%   |
| Iiyama                  | 1         | 0.31%   |
| HannStar                | 1         | 0.31%   |
| ASUSTek Computer        | 1         | 0.31%   |
| Ancor Communications    | 1         | 0.31%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 16        | 4.95%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 7         | 2.17%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 7         | 2.17%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 6         | 1.86%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 5         | 1.55%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 4         | 1.24%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 4         | 1.24%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 4         | 1.24%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch           | 4         | 1.24%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch            | 3         | 0.93%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 3         | 0.93%   |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch         | 3         | 0.93%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 3         | 0.93%   |
| BOE LCD Monitor BOE07A3 1920x1080 344x193mm 15.5-inch                    | 3         | 0.93%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 3         | 0.93%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 3         | 0.93%   |
| Samsung Electronics LCD Monitor SEC3046 1366x768 340x190mm 15.3-inch     | 2         | 0.62%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch     | 2         | 0.62%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch    | 2         | 0.62%   |
| PANDA LCD Monitor NCP006E 1920x1080 344x194mm 15.5-inch                  | 2         | 0.62%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 2         | 0.62%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch             | 2         | 0.62%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 2         | 0.62%   |
| LG Display LCD Monitor LGD0519 1920x1080 344x194mm 15.5-inch             | 2         | 0.62%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 2         | 0.62%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 2         | 0.62%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 2         | 0.62%   |
| Lenovo L24q-10 LEN65CF 2560x1440 527x296mm 23.8-inch                     | 2         | 0.62%   |
| Dell U2412M DELA079 1920x1200 518x324mm 24.1-inch                        | 2         | 0.62%   |
| Dell P2417H DELA0DC 1920x1080 530x300mm 24.0-inch                        | 2         | 0.62%   |
| CPT LCD Monitor CPT14BF 1366x768 344x193mm 15.5-inch                     | 2         | 0.62%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch         | 2         | 0.62%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 2         | 0.62%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch          | 2         | 0.62%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 2         | 0.62%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 0.62%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 2         | 0.62%   |
| BOE LCD Monitor BOE07CB 1920x1080 344x193mm 15.5-inch                    | 2         | 0.62%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 2         | 0.62%   |
| BOE LCD Monitor BOE06FB 1920x1080 344x194mm 15.5-inch                    | 2         | 0.62%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 2         | 0.62%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 2         | 0.62%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 2         | 0.62%   |
| AU Optronics LCD Monitor AUO312C 1366x768 293x164mm 13.2-inch            | 2         | 0.62%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 2         | 0.62%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 2         | 0.62%   |
| AU Optronics LCD Monitor AUO2074 1280x800 331x207mm 15.4-inch            | 2         | 0.62%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch           | 2         | 0.62%   |
| ViewSonic VX2370 SERIES VSC342C 1920x1080 509x286mm 23.0-inch            | 1         | 0.31%   |
| Unknown LCD Monitor SAMSUNG                                              | 1         | 0.31%   |
| Toshiba TV TSB0108 1920x1080 1594x900mm 72.1-inch                        | 1         | 0.31%   |
| Sony TV SNY5803 1360x768                                                 | 1         | 0.31%   |
| Sony TV SNY4402 1360x768                                                 | 1         | 0.31%   |
| Sony LCD Monitor SNY06FA 1600x900 310x170mm 13.9-inch                    | 1         | 0.31%   |
| SKY TV-monitor SKY0402 1920x1080 885x498mm 40.0-inch                     | 1         | 0.31%   |
| Sharp LQ173M1JW04 SHP14E1 1920x1080 382x215mm 17.3-inch                  | 1         | 0.31%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch                  | 1         | 0.31%   |
| Sharp LCD Monitor SHP143B 3840x2160 346x194mm 15.6-inch                  | 1         | 0.31%   |
| Sharp LCD Monitor SHP13B4 1024x768 304x228mm 15.0-inch                   | 1         | 0.31%   |
| Seiko/Epson LCD Monitor 3280x1080                                        | 1         | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 143       | 47.51%  |
| 1366x768 (WXGA)    | 108       | 35.88%  |
| 1280x800 (WXGA)    | 13        | 4.32%   |
| 1600x900 (HD+)     | 7         | 2.33%   |
| 2560x1440 (QHD)    | 4         | 1.33%   |
| 1440x900 (WXGA+)   | 4         | 1.33%   |
| 1360x768           | 4         | 1.33%   |
| 1920x1200 (WUXGA)  | 3         | 1%      |
| 1680x1050 (WSXGA+) | 3         | 1%      |
| 1024x600           | 3         | 1%      |
| 1024x768 (XGA)     | 2         | 0.66%   |
| 3840x2160 (4K)     | 1         | 0.33%   |
| 3280x1080          | 1         | 0.33%   |
| 1920x540           | 1         | 0.33%   |
| 1680x945           | 1         | 0.33%   |
| 1400x1050          | 1         | 0.33%   |
| 1280x1024 (SXGA)   | 1         | 0.33%   |
| Unknown            | 1         | 0.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 195       | 60.94%  |
| 13      | 28        | 8.75%   |
| 17      | 18        | 5.63%   |
| 14      | 17        | 5.31%   |
| 24      | 13        | 4.06%   |
| 23      | 9         | 2.81%   |
| 21      | 6         | 1.88%   |
| Unknown | 6         | 1.88%   |
| 27      | 5         | 1.56%   |
| 11      | 5         | 1.56%   |
| 12      | 4         | 1.25%   |
| 72      | 3         | 0.94%   |
| 31      | 2         | 0.63%   |
| 10      | 2         | 0.63%   |
| 46      | 1         | 0.31%   |
| 40      | 1         | 0.31%   |
| 32      | 1         | 0.31%   |
| 20      | 1         | 0.31%   |
| 19      | 1         | 0.31%   |
| 18      | 1         | 0.31%   |
| 8       | 1         | 0.31%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 228       | 71.25%  |
| 501-600     | 27        | 8.44%   |
| 201-300     | 21        | 6.56%   |
| 351-400     | 20        | 6.25%   |
| 401-500     | 9         | 2.81%   |
| Unknown     | 6         | 1.88%   |
| 1501-2000   | 3         | 0.94%   |
| 601-700     | 2         | 0.63%   |
| 801-900     | 1         | 0.31%   |
| 701-800     | 1         | 0.31%   |
| 101-200     | 1         | 0.31%   |
| 1001-1500   | 1         | 0.31%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 254       | 90.07%  |
| 16/10   | 20        | 7.09%   |
| 4/3     | 3         | 1.06%   |
| Unknown | 3         | 1.06%   |
| 5/4     | 1         | 0.35%   |
| 3/2     | 1         | 0.35%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 195       | 60.75%  |
| 81-90          | 37        | 11.53%  |
| 201-250        | 25        | 7.79%   |
| 121-130        | 17        | 5.3%    |
| 71-80          | 8         | 2.49%   |
| Unknown        | 6         | 1.87%   |
| 51-60          | 5         | 1.56%   |
| 301-350        | 5         | 1.56%   |
| More than 1000 | 3         | 0.93%   |
| 61-70          | 3         | 0.93%   |
| 351-500        | 3         | 0.93%   |
| 251-300        | 3         | 0.93%   |
| 151-200        | 3         | 0.93%   |
| 41-50          | 2         | 0.62%   |
| 501-1000       | 2         | 0.62%   |
| 1-40           | 1         | 0.31%   |
| 141-150        | 1         | 0.31%   |
| 131-140        | 1         | 0.31%   |
| 91-100         | 1         | 0.31%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 136       | 43.87%  |
| 101-120       | 111       | 35.81%  |
| 51-100        | 47        | 15.16%  |
| 161-240       | 6         | 1.94%   |
| Unknown       | 6         | 1.94%   |
| 1-50          | 3         | 0.97%   |
| More than 240 | 1         | 0.32%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 240       | 81.63%  |
| 2     | 43        | 14.63%  |
| 0     | 7         | 2.38%   |
| 3     | 4         | 1.36%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 175       | 36.53%  |
| Intel                             | 121       | 25.26%  |
| Qualcomm Atheros                  | 95        | 19.83%  |
| Broadcom                          | 34        | 7.1%    |
| Ralink                            | 8         | 1.67%   |
| Broadcom Limited                  | 7         | 1.46%   |
| Nvidia                            | 5         | 1.04%   |
| Marvell Technology Group          | 5         | 1.04%   |
| Ralink Technology                 | 4         | 0.84%   |
| Dell                              | 4         | 0.84%   |
| Huawei Technologies               | 3         | 0.63%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.42%   |
| Sierra Wireless                   | 2         | 0.42%   |
| Qualcomm Atheros Communications   | 2         | 0.42%   |
| MediaTek                          | 2         | 0.42%   |
| Ericsson Business Mobile Networks | 2         | 0.42%   |
| VIA Technologies                  | 1         | 0.21%   |
| TP-Link                           | 1         | 0.21%   |
| Linksys                           | 1         | 0.21%   |
| JMicron Technology                | 1         | 0.21%   |
| IMC Networks                      | 1         | 0.21%   |
| D-Link                            | 1         | 0.21%   |
| Arduino SA                        | 1         | 0.21%   |
| Apple                             | 1         | 0.21%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 102       | 17.89%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 53        | 9.3%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 26        | 4.56%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 18        | 3.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 17        | 2.98%   |
| Intel Wireless 8265 / 8275                                              | 15        | 2.63%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 11        | 1.93%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 10        | 1.75%   |
| Intel Wireless 8260                                                     | 10        | 1.75%   |
| Broadcom BCM43142 802.11b/g/n                                           | 10        | 1.75%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 8         | 1.4%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 8         | 1.4%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 1.23%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 6         | 1.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 1.05%   |
| Intel Wireless 7260                                                     | 6         | 1.05%   |
| Intel Wireless 3165                                                     | 6         | 1.05%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 6         | 1.05%   |
| Intel Ethernet Connection (4) I219-LM                                   | 6         | 1.05%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 6         | 1.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 6         | 1.05%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 5         | 0.88%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 5         | 0.88%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 5         | 0.88%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 0.88%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 0.88%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 5         | 0.88%   |
| Intel Ethernet Connection I219-LM                                       | 5         | 0.88%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 4         | 0.7%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 4         | 0.7%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 4         | 0.7%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 4         | 0.7%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 4         | 0.7%    |
| Nvidia MCP79 Ethernet                                                   | 4         | 0.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 0.7%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 4         | 0.7%    |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 3         | 0.53%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 0.53%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 3         | 0.53%   |
| Intel Wireless 3160                                                     | 3         | 0.53%   |
| Intel Ethernet Connection I218-LM                                       | 3         | 0.53%   |
| Intel Ethernet Connection (2) I219-LM                                   | 3         | 0.53%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 0.53%   |
| Intel Centrino Wireless-N 2230                                          | 3         | 0.53%   |
| Intel Centrino Ultimate-N 6300                                          | 3         | 0.53%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 0.53%   |
| Intel 82577LM Gigabit Network Connection                                | 3         | 0.53%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                                    | 3         | 0.53%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 3         | 0.53%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 0.35%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 2         | 0.35%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 2         | 0.35%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 2         | 0.35%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 2         | 0.35%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller               | 2         | 0.35%   |
| Qualcomm Atheros AR9271 802.11n                                         | 2         | 0.35%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 0.35%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                              | 2         | 0.35%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 2         | 0.35%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 0.35%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 115       | 38.46%  |
| Qualcomm Atheros                | 83        | 27.76%  |
| Realtek Semiconductor           | 49        | 16.39%  |
| Broadcom                        | 26        | 8.7%    |
| Ralink                          | 8         | 2.68%   |
| Ralink Technology               | 4         | 1.34%   |
| Dell                            | 3         | 1%      |
| Sierra Wireless                 | 2         | 0.67%   |
| Qualcomm Atheros Communications | 2         | 0.67%   |
| MediaTek                        | 2         | 0.67%   |
| TP-Link                         | 1         | 0.33%   |
| Linksys                         | 1         | 0.33%   |
| IMC Networks                    | 1         | 0.33%   |
| D-Link                          | 1         | 0.33%   |
| Broadcom Limited                | 1         | 0.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 26        | 8.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 18        | 6%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 17        | 5.67%   |
| Intel Wireless 8265 / 8275                                              | 15        | 5%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 11        | 3.67%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 10        | 3.33%   |
| Intel Wireless 8260                                                     | 10        | 3.33%   |
| Broadcom BCM43142 802.11b/g/n                                           | 10        | 3.33%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 8         | 2.67%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 8         | 2.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 2.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 6         | 2%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 2%      |
| Intel Wireless 7260                                                     | 6         | 2%      |
| Intel Wireless 3165                                                     | 6         | 2%      |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 6         | 2%      |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 6         | 2%      |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 5         | 1.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 5         | 1.67%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 1.67%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 1.67%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 5         | 1.67%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.33%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 4         | 1.33%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 4         | 1.33%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 4         | 1.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 1.33%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 1%      |
| Intel Wireless 3160                                                     | 3         | 1%      |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 1%      |
| Intel Centrino Wireless-N 2230                                          | 3         | 1%      |
| Intel Centrino Ultimate-N 6300                                          | 3         | 1%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 1%      |
| Dell DW5811e Snapdragonâ¢ X7 LTE                                    | 3         | 1%      |
| Broadcom BCM4311 802.11b/g WLAN                                         | 3         | 1%      |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 0.67%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 2         | 0.67%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 2         | 0.67%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 2         | 0.67%   |
| Qualcomm Atheros AR9271 802.11n                                         | 2         | 0.67%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 0.67%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 0.67%   |
| Intel Wireless 7265                                                     | 2         | 0.67%   |
| Intel WiFi Link 5100                                                    | 2         | 0.67%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 0.67%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 0.67%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 2         | 0.67%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 0.67%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 0.67%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 0.67%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 2         | 0.67%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 0.33%   |
| Sierra Wireless EM7455                                                  | 1         | 0.33%   |
| Sierra Wireless EM7355 Qualcomm Gobi 4G LTE/HSPA+/EVDO                  | 1         | 0.33%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.33%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 1         | 0.33%   |
| Ralink RT2070 Wireless Adapter                                          | 1         | 0.33%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 0.33%   |
| Ralink RT5390 [802.11 b/g/n 1T1R G-band PCI Express Single Chip]        | 1         | 0.33%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 1         | 0.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 160       | 61.78%  |
| Intel                      | 45        | 17.37%  |
| Qualcomm Atheros           | 21        | 8.11%   |
| Broadcom                   | 11        | 4.25%   |
| Broadcom Limited           | 6         | 2.32%   |
| Nvidia                     | 5         | 1.93%   |
| Marvell Technology Group   | 5         | 1.93%   |
| ZTE WCDMA Technologies MSM | 2         | 0.77%   |
| VIA Technologies           | 1         | 0.39%   |
| JMicron Technology         | 1         | 0.39%   |
| Huawei Technologies        | 1         | 0.39%   |
| Apple                      | 1         | 0.39%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 102       | 38.93%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 53        | 20.23%  |
| Intel Ethernet Connection (4) I219-LM                                | 6         | 2.29%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 6         | 2.29%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                        | 5         | 1.91%   |
| Intel Ethernet Connection I219-LM                                    | 5         | 1.91%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                               | 4         | 1.53%   |
| Nvidia MCP79 Ethernet                                                | 4         | 1.53%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                      | 4         | 1.53%   |
| Realtek RTL8152 Fast Ethernet Adapter                                | 3         | 1.15%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                             | 3         | 1.15%   |
| Intel Ethernet Connection I218-LM                                    | 3         | 1.15%   |
| Intel Ethernet Connection (2) I219-LM                                | 3         | 1.15%   |
| Intel 82577LM Gigabit Network Connection                             | 3         | 1.15%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 2         | 0.76%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller            | 2         | 0.76%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                           | 2         | 0.76%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                | 2         | 0.76%   |
| Intel Ethernet Connection I217-V                                     | 2         | 0.76%   |
| Intel Ethernet Connection (6) I219-LM                                | 2         | 0.76%   |
| Intel Ethernet Connection (5) I219-LM                                | 2         | 0.76%   |
| Intel Ethernet Connection (13) I219-V                                | 2         | 0.76%   |
| Intel 82567LM Gigabit Network Connection                             | 2         | 0.76%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                    | 2         | 0.76%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe              | 2         | 0.76%   |
| Broadcom BCM4401-B0 100Base-TX                                       | 2         | 0.76%   |
| ZTE WCDMA MSM ZTE MSM                                                | 1         | 0.38%   |
| ZTE WCDMA MSM Z6201V                                                 | 1         | 0.38%   |
| VIA VT6102/VT6103 [Rhine-II]                                         | 1         | 0.38%   |
| Realtek RTL8125 2.5GbE Controller                                    | 1         | 0.38%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                | 1         | 0.38%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                     | 1         | 0.38%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller            | 1         | 0.38%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                | 1         | 0.38%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet       | 1         | 0.38%   |
| Nvidia MCP67 Ethernet                                                | 1         | 0.38%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller              | 1         | 0.38%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller              | 1         | 0.38%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller              | 1         | 0.38%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                 | 1         | 0.38%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                 | 1         | 0.38%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                  | 1         | 0.38%   |
| Intel PRO/100 VE Network Connection                                  | 1         | 0.38%   |
| Intel Ethernet Connection I219-V                                     | 1         | 0.38%   |
| Intel Ethernet Connection I217-LM                                    | 1         | 0.38%   |
| Intel Ethernet Connection (7) I219-LM                                | 1         | 0.38%   |
| Intel Ethernet Connection (6) I219-V                                 | 1         | 0.38%   |
| Intel Ethernet Connection (4) I219-V                                 | 1         | 0.38%   |
| Intel 82573L Gigabit Ethernet Controller                             | 1         | 0.38%   |
| Intel 82566MM Gigabit Network Connection                             | 1         | 0.38%   |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller Mobile | 1         | 0.38%   |
| Huawei LYA-L09                                                       | 1         | 0.38%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                    | 1         | 0.38%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express             | 1         | 0.38%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                      | 1         | 0.38%   |
| Broadcom Limited NetXtreme BCM5788 Gigabit Ethernet                  | 1         | 0.38%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express          | 1         | 0.38%   |
| Broadcom Limited NetLink BCM57781 Gigabit Ethernet PCIe              | 1         | 0.38%   |
| Broadcom Limited BCM4401-B0 100Base-TX                               | 1         | 0.38%   |
| Apple Ethernet Adapter [A1277]                                       | 1         | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 287       | 52.09%  |
| Ethernet | 256       | 46.46%  |
| Modem    | 8         | 1.45%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 238       | 77.02%  |
| Ethernet | 71        | 22.98%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 248       | 86.11%  |
| 1     | 40        | 13.89%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 284       | 98.61%  |
| Yes  | 4         | 1.39%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 81        | 35.22%  |
| Realtek Semiconductor           | 37        | 16.09%  |
| Qualcomm Atheros Communications | 30        | 13.04%  |
| Lite-On Technology              | 21        | 9.13%   |
| IMC Networks                    | 14        | 6.09%   |
| Broadcom                        | 10        | 4.35%   |
| Toshiba                         | 6         | 2.61%   |
| Foxconn / Hon Hai               | 6         | 2.61%   |
| Apple                           | 5         | 2.17%   |
| Ralink                          | 3         | 1.3%    |
| Hewlett-Packard                 | 3         | 1.3%    |
| Foxconn International           | 3         | 1.3%    |
| Dell                            | 3         | 1.3%    |
| USI                             | 2         | 0.87%   |
| Ralink Technology               | 2         | 0.87%   |
| Cambridge Silicon Radio         | 2         | 0.87%   |
| Askey Computer                  | 1         | 0.43%   |
| Alps Electric                   | 1         | 0.43%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 42        | 18.26%  |
| Realtek Bluetooth Radio                             | 19        | 8.26%   |
| Qualcomm Atheros  Bluetooth Device                  | 18        | 7.83%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 18        | 7.83%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 12        | 5.22%   |
| Realtek  Bluetooth 4.2 Adapter                      | 11        | 4.78%   |
| IMC Networks Bluetooth Radio                        | 7         | 3.04%   |
| Lite-On Bluetooth Device                            | 5         | 2.17%   |
| Intel AX201 Bluetooth                               | 5         | 2.17%   |
| Intel AX200 Bluetooth                               | 5         | 2.17%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 4         | 1.74%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 4         | 1.74%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 1.74%   |
| Intel Bluetooth Device                              | 4         | 1.74%   |
| Apple Bluetooth Host Controller                     | 4         | 1.74%   |
| Realtek RTL8821A Bluetooth                          | 3         | 1.3%    |
| Ralink RT3290 Bluetooth                             | 3         | 1.3%    |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 1.3%    |
| Foxconn International BCM43142A0 Bluetooth module   | 3         | 1.3%    |
| Foxconn / Hon Hai Bluetooth Device                  | 3         | 1.3%    |
| Dell DW375 Bluetooth Module                         | 3         | 1.3%    |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 3         | 1.3%    |
| USI Bluetooth Module BCM92070                       | 2         | 0.87%   |
| Toshiba Bluetooth Device                            | 2         | 0.87%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 2         | 0.87%   |
| Realtek RTL8723B Bluetooth                          | 2         | 0.87%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 0.87%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 2         | 0.87%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.87%   |
| IMC Networks Bluetooth Device                       | 2         | 0.87%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 0.87%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 0.87%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 0.87%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 2         | 0.87%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.43%   |
| Toshiba Integrated Bluetooth (Taiyo Yuden)          | 1         | 0.43%   |
| Toshiba BCM43142A0                                  | 1         | 0.43%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.43%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.43%   |
| Ralink CSR BS8510                                   | 1         | 0.43%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.43%   |
| Lite-On Atheros Bluetooth                           | 1         | 0.43%   |
| IMC Networks Wireless_Device                        | 1         | 0.43%   |
| IMC Networks Internal Bluetooth                     | 1         | 0.43%   |
| IMC Networks Bluetooth                              | 1         | 0.43%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 0.43%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 0.43%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 1         | 0.43%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 0.43%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 0.43%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 0.43%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 0.43%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 1         | 0.43%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 0.43%   |
| Askey Bluetooth Device                              | 1         | 0.43%   |
| Apple Bluetooth HCI                                 | 1         | 0.43%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)     | 1         | 0.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 233       | 71.04%  |
| AMD                 | 51        | 15.55%  |
| Nvidia              | 37        | 11.28%  |
| GN Netcom           | 2         | 0.61%   |
| VIA Technologies    | 1         | 0.3%    |
| Native Instruments  | 1         | 0.3%    |
| Kingston Technology | 1         | 0.3%    |
| Hewlett-Packard     | 1         | 0.3%    |
| Focusrite-Novation  | 1         | 0.3%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 39        | 9.87%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 30        | 7.59%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 23        | 5.82%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 21        | 5.32%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 19        | 4.81%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 13        | 3.29%   |
| Intel Cannon Lake PCH cAVS                                                                        | 12        | 3.04%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 11        | 2.78%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 9         | 2.28%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 2.28%   |
| Intel Broadwell-U Audio Controller                                                                | 9         | 2.28%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 9         | 2.28%   |
| Intel 8 Series HD Audio Controller                                                                | 9         | 2.28%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 9         | 2.28%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 8         | 2.03%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 8         | 2.03%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 8         | 2.03%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 8         | 2.03%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 8         | 2.03%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 8         | 2.03%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 8         | 2.03%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 7         | 1.77%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 7         | 1.77%   |
| Intel CM238 HD Audio Controller                                                                   | 6         | 1.52%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 1.52%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 6         | 1.52%   |
| AMD FCH Azalia Controller                                                                         | 6         | 1.52%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 1.27%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 5         | 1.27%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 5         | 1.27%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 1.27%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.27%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 5         | 1.27%   |
| Nvidia MCP79 High Definition Audio                                                                | 4         | 1.01%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 1.01%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 1.01%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 2         | 0.51%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 2         | 0.51%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 0.51%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 2         | 0.51%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 0.51%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 0.51%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                                              | 2         | 0.51%   |
| AMD High Definition Audio Controller                                                              | 2         | 0.51%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 0.51%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 0.25%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.25%   |
| Nvidia MCP67 High Definition Audio                                                                | 1         | 0.25%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.25%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.25%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.25%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.25%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.25%   |
| Native Instruments Traktor Kontrol Z1                                                             | 1         | 0.25%   |
| Kingston Technology HyperX 7.1 Audio                                                              | 1         | 0.25%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 1         | 0.25%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller                        | 1         | 0.25%   |
| Hewlett-Packard USB Audio                                                                         | 1         | 0.25%   |
| GN Netcom Jabra Link 370                                                                          | 1         | 0.25%   |
| GN Netcom Jabra Evolve 75                                                                         | 1         | 0.25%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 44        | 24.31%  |
| SK hynix            | 43        | 23.76%  |
| Micron Technology   | 27        | 14.92%  |
| Kingston            | 25        | 13.81%  |
| Unknown             | 13        | 7.18%   |
| Ramaxel Technology  | 9         | 4.97%   |
| Transcend           | 6         | 3.31%   |
| Patriot             | 2         | 1.1%    |
| Crucial             | 2         | 1.1%    |
| Corsair             | 2         | 1.1%    |
| A-DATA Technology   | 2         | 1.1%    |
| SHARETRONIC         | 1         | 0.55%   |
| PNY                 | 1         | 0.55%   |
| Nanya Technology    | 1         | 0.55%   |
| Elpida              | 1         | 0.55%   |
| Apacer              | 1         | 0.55%   |
| 48spaces            | 1         | 0.55%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s          | 5         | 2.53%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s           | 5         | 2.53%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s         | 4         | 2.02%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s         | 4         | 2.02%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 4         | 2.02%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s          | 4         | 2.02%   |
| Micron RAM 4ATF51264HZ-2G6E! 4096MB SODIMM DDR4 2400MT/s       | 4         | 2.02%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s         | 3         | 1.52%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s         | 3         | 1.52%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s       | 3         | 1.52%   |
| Samsung RAM M471A1K43DB1-CTD 8192MB SODIMM DDR4 2667MT/s       | 3         | 1.52%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s           | 3         | 1.52%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s        | 3         | 1.52%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 2         | 1.01%   |
| Unknown RAM Module 1024MB SODIMM DDR                           | 2         | 1.01%   |
| Transcend RAM JM3200HSG-8G 8192MB SODIMM DDR4 2667MT/s         | 2         | 1.01%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM SDRAM 2048MT/s        | 2         | 1.01%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 2         | 1.01%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s         | 2         | 1.01%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s         | 2         | 1.01%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 2         | 1.01%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s      | 2         | 1.01%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s          | 2         | 1.01%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s          | 2         | 1.01%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s          | 2         | 1.01%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 2         | 1.01%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s          | 2         | 1.01%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s          | 2         | 1.01%   |
| Samsung RAM M471A5244CB0-CWE 4096MB Row Of Chips DDR4 3200MT/s | 2         | 1.01%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s       | 2         | 1.01%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s           | 2         | 1.01%   |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s        | 2         | 1.01%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                    | 1         | 0.51%   |
| Unknown RAM Module 8192MB SODIMM DDR4 3200MT/s                 | 1         | 0.51%   |
| Unknown RAM Module 4GB SODIMM DDR3                             | 1         | 0.51%   |
| Unknown RAM Module 2GB SODIMM DDR2                             | 1         | 0.51%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                  | 1         | 0.51%   |
| Unknown RAM Module 2048MB SODIMM DDR                           | 1         | 0.51%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                       | 1         | 0.51%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                     | 1         | 0.51%   |
| Unknown RAM Module 1GB SODIMM DDR2                             | 1         | 0.51%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                  | 1         | 0.51%   |
| Unknown RAM Module 1024MB SODIMM 800MT/s                       | 1         | 0.51%   |
| Transcend RAM Module 1024MB SODIMM DDR2 533MT/s                | 1         | 0.51%   |
| Transcend RAM JM2666HSH-4G 4GB SODIMM DDR4 2667MT/s            | 1         | 0.51%   |
| Transcend RAM JM2666HSD-4G 4GB SODIMM DDR4 2667MT/s            | 1         | 0.51%   |
| Transcend RAM JM2400HSB-8G 8GB SODIMM DDR4 2400MT/s            | 1         | 0.51%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2133MT/s                | 1         | 0.51%   |
| SK hynix RAM Module 512MB SODIMM DDR2 533MT/s                  | 1         | 0.51%   |
| SK hynix RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2400MT/s      | 1         | 0.51%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 800MT/s           | 1         | 0.51%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 0.51%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 0.51%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s         | 1         | 0.51%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 1         | 0.51%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 1         | 0.51%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1334MT/s      | 1         | 0.51%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s         | 1         | 0.51%   |
| SK hynix RAM HMT125S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s         | 1         | 0.51%   |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1067MT/s         | 1         | 0.51%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 69        | 48.59%  |
| DDR3    | 49        | 34.51%  |
| DDR2    | 11        | 7.75%   |
| SDRAM   | 5         | 3.52%   |
| LPDDR4  | 4         | 2.82%   |
| DDR     | 2         | 1.41%   |
| LPDDR3  | 1         | 0.7%    |
| Unknown | 1         | 0.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 136       | 95.77%  |
| Row Of Chips | 5         | 3.52%   |
| Chip         | 1         | 0.7%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 54        | 35.06%  |
| 8192  | 52        | 33.77%  |
| 2048  | 29        | 18.83%  |
| 1024  | 9         | 5.84%   |
| 16384 | 8         | 5.19%   |
| 32768 | 1         | 0.65%   |
| 512   | 1         | 0.65%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 37        | 22.84%  |
| 1600    | 37        | 22.84%  |
| 3200    | 25        | 15.43%  |
| 2400    | 15        | 9.26%   |
| 1334    | 9         | 5.56%   |
| 667     | 6         | 3.7%    |
| 2133    | 5         | 3.09%   |
| Unknown | 5         | 3.09%   |
| 1333    | 4         | 2.47%   |
| 1067    | 4         | 2.47%   |
| 3266    | 3         | 1.85%   |
| 2048    | 3         | 1.85%   |
| 4199    | 2         | 1.23%   |
| 975     | 2         | 1.23%   |
| 800     | 2         | 1.23%   |
| 533     | 2         | 1.23%   |
| 1066    | 1         | 0.62%   |

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
| Chicony Electronics                    | 74        | 28.24%  |
| IMC Networks                           | 37        | 14.12%  |
| Realtek Semiconductor                  | 23        | 8.78%   |
| Microdia                               | 19        | 7.25%   |
| Quanta                                 | 17        | 6.49%   |
| Acer                                   | 15        | 5.73%   |
| Suyin                                  | 14        | 5.34%   |
| Sunplus Innovation Technology          | 14        | 5.34%   |
| Cheng Uei Precision Industry (Foxlink) | 14        | 5.34%   |
| Syntek                                 | 8         | 3.05%   |
| Lite-On Technology                     | 7         | 2.67%   |
| Apple                                  | 5         | 1.91%   |
| Importek                               | 3         | 1.15%   |
| Silicon Motion                         | 2         | 0.76%   |
| Luxvisions Innotech Limited            | 2         | 0.76%   |
| Alcor Micro                            | 2         | 0.76%   |
| Samsung Electronics                    | 1         | 0.38%   |
| OmniVision Technologies                | 1         | 0.38%   |
| Logitech                               | 1         | 0.38%   |
| Lenovo                                 | 1         | 0.38%   |
| KYE Systems (Mouse Systems)            | 1         | 0.38%   |
| DigiTech                               | 1         | 0.38%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                             | 18        | 6.87%   |
| Chicony Integrated Camera                                      | 14        | 5.34%   |
| Realtek Integrated_Webcam_HD                                   | 8         | 3.05%   |
| Microdia Integrated_Webcam_HD                                  | 7         | 2.67%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 7         | 2.67%   |
| Sunplus Integrated_Webcam_HD                                   | 6         | 2.29%   |
| Syntek Integrated Camera                                       | 5         | 1.91%   |
| Quanta VGA WebCam                                              | 5         | 1.91%   |
| Quanta HD WebCam                                               | 5         | 1.91%   |
| IMC Networks Integrated Camera                                 | 5         | 1.91%   |
| Chicony TOSHIBA Web Camera - HD                                | 5         | 1.91%   |
| Chicony Integrated Camera (1280x720@30)                        | 5         | 1.91%   |
| Chicony EasyCamera                                             | 5         | 1.91%   |
| Acer Integrated Camera                                         | 5         | 1.91%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                       | 4         | 1.53%   |
| Realtek Lenovo EasyCamera                                      | 4         | 1.53%   |
| Chicony VGA Webcam                                             | 4         | 1.53%   |
| Chicony HP Webcam                                              | 4         | 1.53%   |
| Chicony HD WebCam                                              | 4         | 1.53%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 4         | 1.53%   |
| Syntek EasyCamera                                              | 3         | 1.15%   |
| Realtek Integrated Webcam HD                                   | 3         | 1.15%   |
| Quanta HP TrueVision HD Camera                                 | 3         | 1.15%   |
| IMC Networks EasyCamera                                        | 3         | 1.15%   |
| Chicony USB 2.0 Camera                                         | 3         | 1.15%   |
| Chicony HD User Facing                                         | 3         | 1.15%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 3         | 1.15%   |
| Acer BisonCam, NB Pro                                          | 3         | 1.15%   |
| Suyin Acer CrystalEye Webcam                                   | 2         | 0.76%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)    | 2         | 0.76%   |
| Sunplus HP Wide Vision HD                                      | 2         | 0.76%   |
| Sunplus ASUS USB2.0 Webcam                                     | 2         | 0.76%   |
| Realtek USB Camera                                             | 2         | 0.76%   |
| Realtek HP Webcam-101                                          | 2         | 0.76%   |
| Microdia Integrated Webcam                                     | 2         | 0.76%   |
| Microdia HP Webcam                                             | 2         | 0.76%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 2         | 0.76%   |
| Lite-On Integrated Camera                                      | 2         | 0.76%   |
| Lite-On HP TrueVision HD Camera                                | 2         | 0.76%   |
| Lite-On HP HD Webcam                                           | 2         | 0.76%   |
| Importek Laptop Integrated Webcam                              | 2         | 0.76%   |
| Chicony UVC 1.00 device HD UVC WebCam                          | 2         | 0.76%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 2         | 0.76%   |
| Chicony USB2.0 HD UVC WebCam                                   | 2         | 0.76%   |
| Chicony HP Truevision HD                                       | 2         | 0.76%   |
| Chicony HP HD Webcam                                           | 2         | 0.76%   |
| Chicony HP HD Camera                                           | 2         | 0.76%   |
| Chicony 1.3M HD WebCam                                         | 2         | 0.76%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                  | 2         | 0.76%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera            | 2         | 0.76%   |
| Apple FaceTime HD Camera                                       | 2         | 0.76%   |
| Apple Built-in iSight                                          | 2         | 0.76%   |
| Acer Lenovo Integrated Webcam                                  | 2         | 0.76%   |
| Acer Lenovo EasyCamera                                         | 2         | 0.76%   |
| Suyin USB 2.0 Camera                                           | 1         | 0.38%   |
| Suyin Integrated_Webcam_HD                                     | 1         | 0.38%   |
| Suyin HP webcam [dv6-1190en]                                   | 1         | 0.38%   |
| Suyin HP TrueVision HD Integrated Webcam                       | 1         | 0.38%   |
| Suyin HD Video WebCam                                          | 1         | 0.38%   |
| Suyin 1.3M HD WebCam                                           | 1         | 0.38%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 19        | 41.3%   |
| Synaptics                  | 9         | 19.57%  |
| Shenzhen Goodix Technology | 7         | 15.22%  |
| AuthenTec                  | 5         | 10.87%  |
| Upek                       | 2         | 4.35%   |
| Elan Microelectronics      | 2         | 4.35%   |
| STMicroelectronics         | 1         | 2.17%   |
| LighTuning Technology      | 1         | 2.17%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 6         | 13.04%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 5         | 10.87%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 8.7%    |
| Synaptics  WBDI                                                            | 4         | 8.7%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 4         | 8.7%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 3         | 6.52%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 4.35%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 4.35%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 4.35%   |
| Elan ELAN:Fingerprint                                                      | 2         | 4.35%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 2.17%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 2.17%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 2.17%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 2.17%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.17%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 2.17%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 2.17%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 2.17%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 2.17%   |
| AuthenTec AES2810                                                          | 1         | 2.17%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 2.17%   |
| Unknown                                                                    | 1         | 2.17%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 8         | 42.11%  |
| Alcor Micro           | 6         | 31.58%  |
| O2 Micro              | 2         | 10.53%  |
| OmniKey               | 1         | 5.26%   |
| Lenovo                | 1         | 5.26%   |
| Gemalto (was Gemplus) | 1         | 5.26%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader               | 6         | 31.58%  |
| Broadcom 5880                                     | 4         | 21.05%  |
| Broadcom BCM5880 Secure Applications Processor    | 3         | 15.79%  |
| O2 Micro OZ776 CCID Smartcard Reader              | 2         | 10.53%  |
| OmniKey 3x21 Smart Card Reader                    | 1         | 5.26%   |
| Lenovo Integrated Smart Card Reader               | 1         | 5.26%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 1         | 5.26%   |
| Broadcom 58200                                    | 1         | 5.26%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 192       | 64.43%  |
| 1     | 81        | 27.18%  |
| 2     | 20        | 6.71%   |
| 4     | 2         | 0.67%   |
| 3     | 2         | 0.67%   |
| 8     | 1         | 0.34%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 46        | 34.33%  |
| Graphics card            | 29        | 21.64%  |
| Chipcard                 | 18        | 13.43%  |
| Net/wireless             | 14        | 10.45%  |
| Bluetooth                | 6         | 4.48%   |
| Multimedia controller    | 5         | 3.73%   |
| Communication controller | 5         | 3.73%   |
| Camera                   | 3         | 2.24%   |
| Sound                    | 2         | 1.49%   |
| Net/ethernet             | 2         | 1.49%   |
| Card reader              | 2         | 1.49%   |
| Storage                  | 1         | 0.75%   |
| Modem                    | 1         | 0.75%   |

