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

Total: 468

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | V570 1066EDG                | [8e2439c590](https://linux-hardware.org/?probe=8e2439c590) | Oct 01, 2022 |
| Dell          | Precision M4800             | [d4142adadc](https://linux-hardware.org/?probe=d4142adadc) | Sep 29, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | [d06b40ddf1](https://linux-hardware.org/?probe=d06b40ddf1) | Sep 29, 2022 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | [9fbedd972e](https://linux-hardware.org/?probe=9fbedd972e) | Sep 24, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X1S... | [6e943a4d35](https://linux-hardware.org/?probe=6e943a4d35) | Sep 23, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [641ad27b06](https://linux-hardware.org/?probe=641ad27b06) | Sep 22, 2022 |
| HP            | ProBook 6560b               | [743f401352](https://linux-hardware.org/?probe=743f401352) | Sep 20, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [d0d43b3cc5](https://linux-hardware.org/?probe=d0d43b3cc5) | Sep 14, 2022 |
| Dell          | Inspiron N5050              | [131f5046db](https://linux-hardware.org/?probe=131f5046db) | Sep 11, 2022 |
| Apple         | MacBookPro8,2               | [a30032ef92](https://linux-hardware.org/?probe=a30032ef92) | Sep 11, 2022 |
| Apple         | MacBookPro8,2               | [0645f03606](https://linux-hardware.org/?probe=0645f03606) | Sep 11, 2022 |
| LG Electro... | 17Z990-R.AAS8U1             | [2df5aeabed](https://linux-hardware.org/?probe=2df5aeabed) | Sep 08, 2022 |
| Dell          | Inspiron 3593               | [fd6ab0c9e5](https://linux-hardware.org/?probe=fd6ab0c9e5) | Sep 07, 2022 |
| ASUSTek       | Zenbook UX5400EA_UX5400E... | [6ce8accfb1](https://linux-hardware.org/?probe=6ce8accfb1) | Sep 04, 2022 |
| Apple         | MacBookPro5,1               | [beec88b95c](https://linux-hardware.org/?probe=beec88b95c) | Sep 04, 2022 |
| Apple         | MacBookPro5,1               | [e9c17c2743](https://linux-hardware.org/?probe=e9c17c2743) | Sep 02, 2022 |
| Apple         | MacBookPro5,1               | [4c90105342](https://linux-hardware.org/?probe=4c90105342) | Sep 01, 2022 |
| Apple         | MacBookPro5,1               | [468eeca88b](https://linux-hardware.org/?probe=468eeca88b) | Aug 30, 2022 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | [e3c7cd81e8](https://linux-hardware.org/?probe=e3c7cd81e8) | Aug 27, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [f945f778b2](https://linux-hardware.org/?probe=f945f778b2) | Aug 26, 2022 |
| Apple         | MacBookPro5,1               | [6efab17b42](https://linux-hardware.org/?probe=6efab17b42) | Aug 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X531... | [255a1cdf9a](https://linux-hardware.org/?probe=255a1cdf9a) | Aug 24, 2022 |
| ASUSTek       | X542BA                      | [7e86736ebc](https://linux-hardware.org/?probe=7e86736ebc) | Aug 21, 2022 |
| ASUSTek       | K54C                        | [e10b52270f](https://linux-hardware.org/?probe=e10b52270f) | Aug 17, 2022 |
| Dell          | Inspiron 3521               | [ebf974be3e](https://linux-hardware.org/?probe=ebf974be3e) | Aug 13, 2022 |
| Dell          | Inspiron 3521               | [6dd71dbcf3](https://linux-hardware.org/?probe=6dd71dbcf3) | Aug 12, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [fa9cdcd977](https://linux-hardware.org/?probe=fa9cdcd977) | Aug 12, 2022 |
| Apple         | MacBookPro5,1               | [ab09f2f44b](https://linux-hardware.org/?probe=ab09f2f44b) | Aug 11, 2022 |
| Sony          | VPCZ12M9E                   | [75f1c2f156](https://linux-hardware.org/?probe=75f1c2f156) | Aug 02, 2022 |
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
| Ubuntu 20.04                 | 42        | 12.1%   |
| Ubuntu 18.04                 | 29        | 8.36%   |
| OpenMandriva 4.3             | 10        | 2.88%   |
| Zorin 15                     | 9         | 2.59%   |
| BlackPanther 18.1            | 9         | 2.59%   |
| ROSA R11                     | 8         | 2.31%   |
| Arch                         | 8         | 2.31%   |
| Ubuntu 22.04                 | 7         | 2.02%   |
| Ubuntu 19.10                 | 7         | 2.02%   |
| Linux Mint 19.3              | 7         | 2.02%   |
| OpenMandriva 4.2             | 6         | 1.73%   |
| Linux Mint 20.3              | 6         | 1.73%   |
| Ubuntu 21.10                 | 5         | 1.44%   |
| Ubuntu 18.10                 | 5         | 1.44%   |
| ROSA R10                     | 5         | 1.44%   |
| KDE neon 20.04               | 5         | 1.44%   |
| ROSA R11.1                   | 4         | 1.15%   |
| Pop!_OS 22.04                | 4         | 1.15%   |
| Pop!_OS 21.04                | 4         | 1.15%   |
| Fedora 34                    | 4         | 1.15%   |
| Zorin 16                     | 3         | 0.86%   |
| Xubuntu 20.04                | 3         | 0.86%   |
| Ubuntu 21.04                 | 3         | 0.86%   |
| Ubuntu 19.04                 | 3         | 0.86%   |
| ROSA R9                      | 3         | 0.86%   |
| ROSA 12.2                    | 3         | 0.86%   |
| openSUSE Tumbleweed-XXXXXXXX | 3         | 0.86%   |
| Manjaro                      | 3         | 0.86%   |
| Linux Mint 20.2              | 3         | 0.86%   |
| Linux Mint 20.1              | 3         | 0.86%   |
| KDE neon 18.04               | 3         | 0.86%   |
| Fedora 35                    | 3         | 0.86%   |
| Fedora 30                    | 3         | 0.86%   |
| Endless 3.9.4                | 3         | 0.86%   |
| Endless 3.9.0                | 3         | 0.86%   |
| Endless 3.5.4                | 3         | 0.86%   |
| ArcoLinux Rolling            | 3         | 0.86%   |
| Arch Rolling                 | 3         | 0.86%   |
| Xubuntu 18.04                | 2         | 0.58%   |
| Ubuntu 20.10                 | 2         | 0.58%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 104       | 32.5%   |
| Endless       | 30        | 9.38%   |
| ROSA          | 22        | 6.88%   |
| Linux Mint    | 22        | 6.88%   |
| OpenMandriva  | 16        | 5%      |
| Zorin         | 13        | 4.06%   |
| Pop!_OS       | 13        | 4.06%   |
| Fedora        | 13        | 4.06%   |
| Manjaro       | 12        | 3.75%   |
| Arch          | 11        | 3.44%   |
| BlackPanther  | 10        | 3.13%   |
| KDE neon      | 8         | 2.5%    |
| Xubuntu       | 6         | 1.88%   |
| Kubuntu       | 5         | 1.56%   |
| Kali          | 5         | 1.56%   |
| openSUSE      | 4         | 1.25%   |
| Lubuntu       | 3         | 0.94%   |
| ArcoLinux     | 3         | 0.94%   |
| Ubuntu MATE   | 2         | 0.63%   |
| MX            | 2         | 0.63%   |
| EndeavourOS   | 2         | 0.63%   |
| Elementary    | 2         | 0.63%   |
| UbuntuDDE     | 1         | 0.31%   |
| Ubuntu Unity  | 1         | 0.31%   |
| Ubuntu Budgie | 1         | 0.31%   |
| Slackware     | 1         | 0.31%   |
| Peppermint    | 1         | 0.31%   |
| GNOME OS      | 1         | 0.31%   |
| Generic       | 1         | 0.31%   |
| Garuda Linux  | 1         | 0.31%   |
| Devuan        | 1         | 0.31%   |
| Deepin        | 1         | 0.31%   |
| Debian        | 1         | 0.31%   |
| Clear Linux   | 1         | 0.31%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Notebooks | Percent |
|------------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003            | 10        | 2.72%   |
| 4.18.16-desktop-1bP                | 7         | 1.91%   |
| 5.8.0-14-generic                   | 6         | 1.63%   |
| 5.3.0-40-generic                   | 6         | 1.63%   |
| 5.10.14-desktop-1omv4002           | 6         | 1.63%   |
| 4.18.0-15-generic                  | 6         | 1.63%   |
| 5.15.0-48-generic                  | 5         | 1.36%   |
| 5.11.0-27-generic                  | 5         | 1.36%   |
| 5.4.0-47-generic                   | 4         | 1.09%   |
| 5.4.0-42-generic                   | 4         | 1.09%   |
| 5.3.0-23-generic                   | 4         | 1.09%   |
| 5.15.0-46-generic                  | 4         | 1.09%   |
| 4.18.0-25-generic                  | 4         | 1.09%   |
| 4.18.0-12-generic                  | 4         | 1.09%   |
| 4.15.0-15-generic                  | 4         | 1.09%   |
| 5.4.0-58-generic                   | 3         | 0.82%   |
| 5.4.0-52-generic                   | 3         | 0.82%   |
| 5.4.0-48-generic                   | 3         | 0.82%   |
| 5.4.0-19-generic                   | 3         | 0.82%   |
| 5.3.0-51-generic                   | 3         | 0.82%   |
| 5.3.0-29-generic                   | 3         | 0.82%   |
| 5.3.0-28-generic                   | 3         | 0.82%   |
| 5.15.0-40-generic                  | 3         | 0.82%   |
| 5.13.0-30-generic                  | 3         | 0.82%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 3         | 0.82%   |
| 5.0.0-31-generic                   | 3         | 0.82%   |
| 4.9.20-nrj-desktop-1rosa-x86_64    | 3         | 0.82%   |
| 4.18.0-10-generic                  | 3         | 0.82%   |
| 4.15.0-desktop-45.1rosa-x86_64     | 3         | 0.82%   |
| 5.8.11-1-MANJARO                   | 2         | 0.54%   |
| 5.8.0-55-generic                   | 2         | 0.54%   |
| 5.8.0-48-generic                   | 2         | 0.54%   |
| 5.8.0-33-generic                   | 2         | 0.54%   |
| 5.6.14-desktop-2bP                 | 2         | 0.54%   |
| 5.4.0-94-generic                   | 2         | 0.54%   |
| 5.4.0-88-generic                   | 2         | 0.54%   |
| 5.4.0-74-generic                   | 2         | 0.54%   |
| 5.4.0-73-generic                   | 2         | 0.54%   |
| 5.4.0-70-generic                   | 2         | 0.54%   |
| 5.4.0-66-generic                   | 2         | 0.54%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 54        | 15.47%  |
| 4.15.0  | 29        | 8.31%   |
| 5.3.0   | 27        | 7.74%   |
| 5.11.0  | 21        | 6.02%   |
| 4.18.0  | 21        | 6.02%   |
| 5.8.0   | 20        | 5.73%   |
| 5.13.0  | 17        | 4.87%   |
| 5.0.0   | 17        | 4.87%   |
| 5.15.0  | 16        | 4.58%   |
| 5.16.7  | 10        | 2.87%   |
| 4.18.16 | 7         | 2.01%   |
| 5.10.14 | 6         | 1.72%   |
| 5.10.0  | 6         | 1.72%   |
| 4.9.20  | 4         | 1.15%   |
| 5.8.11  | 3         | 0.86%   |
| 5.10.74 | 3         | 0.86%   |
| 5.6.14  | 2         | 0.57%   |
| 5.19.7  | 2         | 0.57%   |
| 5.18.10 | 2         | 0.57%   |
| 5.17.0  | 2         | 0.57%   |
| 5.16.0  | 2         | 0.57%   |
| 5.15.11 | 2         | 0.57%   |
| 5.12.9  | 2         | 0.57%   |
| 4.9.76  | 2         | 0.57%   |
| 4.13.0  | 2         | 0.57%   |
| 5.9.8   | 1         | 0.29%   |
| 5.9.12  | 1         | 0.29%   |
| 5.8.13  | 1         | 0.29%   |
| 5.7.9   | 1         | 0.29%   |
| 5.7.10  | 1         | 0.29%   |
| 5.6.8   | 1         | 0.29%   |
| 5.6.3   | 1         | 0.29%   |
| 5.6.11  | 1         | 0.29%   |
| 5.5.7   | 1         | 0.29%   |
| 5.4.88  | 1         | 0.29%   |
| 5.4.83  | 1         | 0.29%   |
| 5.4.75  | 1         | 0.29%   |
| 5.4.6   | 1         | 0.29%   |
| 5.4.40  | 1         | 0.29%   |
| 5.4.32  | 1         | 0.29%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 63        | 18.26%  |
| 4.15    | 29        | 8.41%   |
| 5.3     | 28        | 8.12%   |
| 4.18    | 28        | 8.12%   |
| 5.11    | 27        | 7.83%   |
| 5.8     | 24        | 6.96%   |
| 5.15    | 24        | 6.96%   |
| 5.10    | 20        | 5.8%    |
| 5.13    | 19        | 5.51%   |
| 5.0     | 19        | 5.51%   |
| 5.16    | 14        | 4.06%   |
| 4.9     | 11        | 3.19%   |
| 5.19    | 5         | 1.45%   |
| 5.18    | 5         | 1.45%   |
| 5.12    | 5         | 1.45%   |
| 5.6     | 4         | 1.16%   |
| 5.17    | 3         | 0.87%   |
| 5.9     | 2         | 0.58%   |
| 5.7     | 2         | 0.58%   |
| 5.1     | 2         | 0.58%   |
| 4.19    | 2         | 0.58%   |
| 4.13    | 2         | 0.58%   |
| 4.1     | 2         | 0.58%   |
| 5.5     | 1         | 0.29%   |
| 5.14    | 1         | 0.29%   |
| 4.17    | 1         | 0.29%   |
| 4.12    | 1         | 0.29%   |
| 4.10    | 1         | 0.29%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 294       | 95.45%  |
| i686   | 14        | 4.55%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 127       | 38.96%  |
| Unknown         | 55        | 16.87%  |
| KDE5            | 53        | 16.26%  |
| XFCE            | 28        | 8.59%   |
| X-Cinnamon      | 16        | 4.91%   |
| KDE4            | 11        | 3.37%   |
| KDE             | 6         | 1.84%   |
| Cinnamon        | 6         | 1.84%   |
| MATE            | 5         | 1.53%   |
| LXQt            | 4         | 1.23%   |
| i3              | 4         | 1.23%   |
| qtile           | 2         | 0.61%   |
| Pantheon        | 2         | 0.61%   |
| Deepin          | 2         | 0.61%   |
| Unity           | 1         | 0.31%   |
| LXDE            | 1         | 0.31%   |
| GNOME Flashback | 1         | 0.31%   |
| DWM             | 1         | 0.31%   |
| Budgie          | 1         | 0.31%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 257       | 80.82%  |
| Unknown | 31        | 9.75%   |
| Wayland | 25        | 7.86%   |
| Tty     | 5         | 1.57%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 172       | 53.92%  |
| SDDM    | 50        | 15.67%  |
| GDM     | 31        | 9.72%   |
| LightDM | 25        | 7.84%   |
| GDM3    | 18        | 5.64%   |
| KDM     | 12        | 3.76%   |
| TDM     | 9         | 2.82%   |
| XDM     | 1         | 0.31%   |
| Ly      | 1         | 0.31%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| en_US       | 205       | 62.88%  |
| Unknown     | 75        | 23.01%  |
| sr_RS       | 17        | 5.21%   |
| sr_RS@latin | 11        | 3.37%   |
| en_GB       | 8         | 2.45%   |
| C           | 4         | 1.23%   |
| hu_HU       | 2         | 0.61%   |
| ru_RU       | 1         | 0.31%   |
| en_IE       | 1         | 0.31%   |
| en_AU       | 1         | 0.31%   |
| de_DE       | 1         | 0.31%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 171       | 54.29%  |
| BIOS | 144       | 45.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 252       | 78.75%  |
| Overlay | 29        | 9.06%   |
| Unknown | 26        | 8.13%   |
| Btrfs   | 11        | 3.44%   |
| Zfs     | 1         | 0.31%   |
| Tmpfs   | 1         | 0.31%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 180       | 56.96%  |
| GPT     | 88        | 27.85%  |
| MBR     | 48        | 15.19%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 274       | 88.1%   |
| Yes       | 37        | 11.9%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 233       | 74.68%  |
| Yes       | 79        | 25.32%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 78        | 25.41%  |
| Hewlett-Packard     | 53        | 17.26%  |
| ASUSTek Computer    | 48        | 15.64%  |
| Dell                | 44        | 14.33%  |
| Acer                | 32        | 10.42%  |
| Toshiba             | 13        | 4.23%   |
| Fujitsu Siemens     | 6         | 1.95%   |
| Apple               | 6         | 1.95%   |
| MSI                 | 5         | 1.63%   |
| Sony                | 4         | 1.3%    |
| Fujitsu             | 3         | 0.98%   |
| Samsung Electronics | 2         | 0.65%   |
| Medion              | 2         | 0.65%   |
| LG Electronics      | 2         | 0.65%   |
| TWC                 | 1         | 0.33%   |
| Timi                | 1         | 0.33%   |
| Razer               | 1         | 0.33%   |
| Packard Bell        | 1         | 0.33%   |
| IBM                 | 1         | 0.33%   |
| HUAWEI              | 1         | 0.33%   |
| Gigabyte Technology | 1         | 0.33%   |
| eMachines           | 1         | 0.33%   |
| BenQ                | 1         | 0.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Acer Aspire A315-31                        | 6         | 1.95%   |
| Lenovo V330-15IKB 81AX                     | 4         | 1.3%    |
| HP Notebook                                | 4         | 1.3%    |
| Lenovo IdeaPad 330-15IKB 81DE              | 3         | 0.98%   |
| Lenovo IdeaPad 3 15IIL05 81WE              | 3         | 0.98%   |
| Dell Inspiron 3593                         | 3         | 0.98%   |
| ASUS X541NA                                | 3         | 0.98%   |
| Unknown                                    | 3         | 0.98%   |
| MSI CR500                                  | 2         | 0.65%   |
| Lenovo Legion Y530-15ICH 81FV              | 2         | 0.65%   |
| Lenovo IdeaPad S540-14API 81NH             | 2         | 0.65%   |
| Lenovo IdeaPad L340-15API 81LW             | 2         | 0.65%   |
| Lenovo IdeaPad 5 14ARE05 81YM              | 2         | 0.65%   |
| Lenovo IdeaPad 5 14ALC05 82LM              | 2         | 0.65%   |
| Lenovo IdeaPad 110-15IBR 80T7              | 2         | 0.65%   |
| Lenovo G500 20236                          | 2         | 0.65%   |
| HP Pavilion Notebook                       | 2         | 0.65%   |
| HP Laptop 15-ra0xx                         | 2         | 0.65%   |
| HP Laptop 15-db1xxx                        | 2         | 0.65%   |
| HP Laptop 15-db0xxx                        | 2         | 0.65%   |
| HP G62                                     | 2         | 0.65%   |
| HP 250 G5 Notebook PC                      | 2         | 0.65%   |
| Fujitsu Siemens AMILO Li3710               | 2         | 0.65%   |
| Dell Vostro 3500                           | 2         | 0.65%   |
| Dell Latitude E5470                        | 2         | 0.65%   |
| Dell Latitude 7490                         | 2         | 0.65%   |
| Dell Inspiron 3542                         | 2         | 0.65%   |
| Dell Inspiron 3537                         | 2         | 0.65%   |
| ASUS X55A                                  | 2         | 0.65%   |
| ASUS X541NC                                | 2         | 0.65%   |
| ASUS VivoBook_ASUSLaptop X580GD_N580GD     | 2         | 0.65%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_X543MA | 2         | 0.65%   |
| ASUS K54C                                  | 2         | 0.65%   |
| Apple MacBookPro8,1                        | 2         | 0.65%   |
| Acer Aspire A315-51                        | 2         | 0.65%   |
| Toshiba TECRA Z50-A                        | 1         | 0.33%   |
| Toshiba Satellite Pro L650                 | 1         | 0.33%   |
| Toshiba Satellite L755                     | 1         | 0.33%   |
| Toshiba Satellite L20                      | 1         | 0.33%   |
| Toshiba Satellite C870-17H                 | 1         | 0.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo IdeaPad        | 29        | 9.45%   |
| Acer Aspire           | 28        | 9.12%   |
| Lenovo ThinkPad       | 24        | 7.82%   |
| Dell Inspiron         | 23        | 7.49%   |
| ASUS VivoBook         | 15        | 4.89%   |
| HP Laptop             | 13        | 4.23%   |
| Toshiba Satellite     | 11        | 3.58%   |
| Dell Latitude         | 11        | 3.58%   |
| HP ProBook            | 9         | 2.93%   |
| HP Pavilion           | 6         | 1.95%   |
| Lenovo Legion         | 5         | 1.63%   |
| HP EliteBook          | 5         | 1.63%   |
| HP 250                | 5         | 1.63%   |
| Fujitsu Siemens AMILO | 5         | 1.63%   |
| Lenovo V330-15IKB     | 4         | 1.3%    |
| HP Notebook           | 4         | 1.3%    |
| Dell Vostro           | 4         | 1.3%    |
| HP Compaq             | 3         | 0.98%   |
| Fujitsu LIFEBOOK      | 3         | 0.98%   |
| Dell Precision        | 3         | 0.98%   |
| ASUS ZenBook          | 3         | 0.98%   |
| ASUS X541NA           | 3         | 0.98%   |
| Apple MacBookPro8     | 3         | 0.98%   |
| Unknown               | 3         | 0.98%   |
| MSI CR500             | 2         | 0.65%   |
| Lenovo G500           | 2         | 0.65%   |
| HP G62                | 2         | 0.65%   |
| ASUS X55A             | 2         | 0.65%   |
| ASUS X541NC           | 2         | 0.65%   |
| ASUS TUF              | 2         | 0.65%   |
| ASUS K54C             | 2         | 0.65%   |
| Acer Nitro            | 2         | 0.65%   |
| Toshiba TECRA         | 1         | 0.33%   |
| Toshiba QOSMIO        | 1         | 0.33%   |
| Timi TM1613           | 1         | 0.33%   |
| Sony VPCZ21X9E        | 1         | 0.33%   |
| Sony VPCZ12M9E        | 1         | 0.33%   |
| Sony VPCEE23FX        | 1         | 0.33%   |
| Sony VGN-FE31Z        | 1         | 0.33%   |
| Samsung N250P         | 1         | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 39        | 12.7%   |
| 2011 | 29        | 9.45%   |
| 2019 | 28        | 9.12%   |
| 2017 | 28        | 9.12%   |
| 2020 | 27        | 8.79%   |
| 2016 | 24        | 7.82%   |
| 2013 | 22        | 7.17%   |
| 2012 | 19        | 6.19%   |
| 2010 | 17        | 5.54%   |
| 2014 | 14        | 4.56%   |
| 2008 | 13        | 4.23%   |
| 2015 | 12        | 3.91%   |
| 2021 | 9         | 2.93%   |
| 2009 | 8         | 2.61%   |
| 2007 | 7         | 2.28%   |
| 2006 | 6         | 1.95%   |
| 2022 | 3         | 0.98%   |
| 2005 | 2         | 0.65%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 307       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 284       | 91.03%  |
| Enabled  | 28        | 8.97%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 307       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 99        | 31.63%  |
| 4.01-8.0   | 81        | 25.88%  |
| 8.01-16.0  | 49        | 15.65%  |
| 16.01-24.0 | 43        | 13.74%  |
| 1.01-2.0   | 18        | 5.75%   |
| 2.01-3.0   | 10        | 3.19%   |
| 32.01-64.0 | 8         | 2.56%   |
| 24.01-32.0 | 4         | 1.28%   |
| 0.51-1.0   | 1         | 0.32%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 129       | 37.61%  |
| 2.01-3.0  | 79        | 23.03%  |
| 0.51-1.0  | 48        | 13.99%  |
| 3.01-4.0  | 41        | 11.95%  |
| 4.01-8.0  | 34        | 9.91%   |
| 8.01-16.0 | 11        | 3.21%   |
| 0.01-0.5  | 1         | 0.29%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 239       | 75.87%  |
| 2      | 63        | 20%     |
| 0      | 7         | 2.22%   |
| 3      | 6         | 1.9%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 173       | 55.81%  |
| Yes       | 137       | 44.19%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 269       | 87.62%  |
| No        | 38        | 12.38%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 307       | 99.68%  |
| No        | 1         | 0.32%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 249       | 80.32%  |
| No        | 61        | 19.68%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Serbia  | 307       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Belgrade      | 201       | 61.66%  |
| Novi Sad      | 33        | 10.12%  |
| Niš          | 19        | 5.83%   |
| Pančevo      | 4         | 1.23%   |
| Novi Belgrade | 4         | 1.23%   |
| Leskovac      | 4         | 1.23%   |
| Zrenjanin     | 3         | 0.92%   |
| Subotica      | 3         | 0.92%   |
| Senta         | 3         | 0.92%   |
| Savski Venac  | 3         | 0.92%   |
| Lozovik       | 3         | 0.92%   |
| Kovin         | 3         | 0.92%   |
| Varvarin      | 2         | 0.61%   |
| Novi Karlovci | 2         | 0.61%   |
| Kragujevac    | 2         | 0.61%   |
| Jagodina      | 2         | 0.61%   |
| Branicevo     | 2         | 0.61%   |
| Becej         | 2         | 0.61%   |
| Backa Topola  | 2         | 0.61%   |
| Valjevo       | 1         | 0.31%   |
| Užice        | 1         | 0.31%   |
| UÅ¾ice      | 1         | 0.31%   |
| Trstenik      | 1         | 0.31%   |
| Stara Pazova  | 1         | 0.31%   |
| Sabac         | 1         | 0.31%   |
| Ruma          | 1         | 0.31%   |
| Ripanj        | 1         | 0.31%   |
| Pukovac       | 1         | 0.31%   |
| Požarevac    | 1         | 0.31%   |
| Novi Knezevac | 1         | 0.31%   |
| New Belgrade  | 1         | 0.31%   |
| Mladenovac    | 1         | 0.31%   |
| Lazarevac     | 1         | 0.31%   |
| Kruševac     | 1         | 0.31%   |
| Kraljevo      | 1         | 0.31%   |
| Guca          | 1         | 0.31%   |
| Grocka        | 1         | 0.31%   |
| Cuprija       | 1         | 0.31%   |
| Cibukovac     | 1         | 0.31%   |
| Čačak       | 1         | 0.31%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| WDC                     | 50        | 72     | 14.01%  |
| Seagate                 | 50        | 58     | 14.01%  |
| Toshiba                 | 46        | 58     | 12.89%  |
| Samsung Electronics     | 41        | 52     | 11.48%  |
| Kingston                | 24        | 28     | 6.72%   |
| Hitachi                 | 18        | 18     | 5.04%   |
| SK hynix                | 17        | 21     | 4.76%   |
| Intel                   | 14        | 23     | 3.92%   |
| SanDisk                 | 12        | 18     | 3.36%   |
| Unknown                 | 11        | 12     | 3.08%   |
| Patriot                 | 10        | 12     | 2.8%    |
| Micron Technology       | 8         | 8      | 2.24%   |
| HGST                    | 8         | 17     | 2.24%   |
| SPCC                    | 5         | 6      | 1.4%    |
| Fujitsu                 | 5         | 5      | 1.4%    |
| Gigabyte Technology     | 4         | 4      | 1.12%   |
| A-DATA Technology       | 4         | 4      | 1.12%   |
| Transcend               | 3         | 3      | 0.84%   |
| KIOXIA                  | 3         | 3      | 0.84%   |
| GeIL                    | 3         | 3      | 0.84%   |
| Union Memory            | 2         | 2      | 0.56%   |
| Phison                  | 2         | 3      | 0.56%   |
| LITEON                  | 2         | 3      | 0.56%   |
| Crucial                 | 2         | 2      | 0.56%   |
| Biostar                 | 2         | 2      | 0.56%   |
| Verbatim                | 1         | 1      | 0.28%   |
| Union Memory (Shenzhen) | 1         | 1      | 0.28%   |
| SSSTC                   | 1         | 1      | 0.28%   |
| Realtek Semiconductor   | 1         | 4      | 0.28%   |
| PNY                     | 1         | 1      | 0.28%   |
| Netac                   | 1         | 1      | 0.28%   |
| JMicron Technology      | 1         | 1      | 0.28%   |
| IBM/Hitachi             | 1         | 1      | 0.28%   |
| HUAWEI                  | 1         | 1      | 0.28%   |
| AMD                     | 1         | 1      | 0.28%   |
| Unknown                 | 1         | 1      | 0.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB          | 17        | 4.71%   |
| Toshiba MQ01ABF050 500GB                | 12        | 3.32%   |
| Seagate ST500LT012-1DG142 500GB         | 8         | 2.22%   |
| Kingston SA400S37240G 240GB SSD         | 6         | 1.66%   |
| Toshiba MQ01ABD100 1TB                  | 5         | 1.39%   |
| Seagate ST500LT012-9WS142 500GB         | 5         | 1.39%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 5         | 1.39%   |
| Samsung NVMe SSD Drive 256GB            | 5         | 1.39%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB    | 4         | 1.11%   |
| Toshiba MQ04ABF100 1TB                  | 4         | 1.11%   |
| Kingston SA400S37120G 120GB SSD         | 4         | 1.11%   |
| WDC WD5000LPCX-24VHAT0 500GB            | 3         | 0.83%   |
| SK hynix NVMe SSD Drive 256GB           | 3         | 0.83%   |
| SanDisk NVMe SSD Drive 256GB            | 3         | 0.83%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD     | 3         | 0.83%   |
| Kingston SA400S37480G 480GB SSD         | 3         | 0.83%   |
| Kingston RBUSC180DS37256GJ 256GB SSD    | 3         | 0.83%   |
| Hitachi HTS545050A7E380 500GB           | 3         | 0.83%   |
| GeIL R3_128GB                           | 3         | 0.83%   |
| WDC WD5000LPVX-75V0TT0 500GB            | 2         | 0.55%   |
| WDC WD5000LPCX-80VHAT1 500GB            | 2         | 0.55%   |
| WDC WD3200BEVT-22ZCT0 320GB             | 2         | 0.55%   |
| WDC WD3200BEVT-22A23T0 320GB            | 2         | 0.55%   |
| WDC WD2500BEVS-22UST0 250GB             | 2         | 0.55%   |
| WDC WD1200BEVS-22UST0 120GB             | 2         | 0.55%   |
| WDC WD10SPZX-24Z10 1TB                  | 2         | 0.55%   |
| WDC WD10SPZX-21Z10T0 1TB                | 2         | 0.55%   |
| WDC PC SN530 SDBPNPZ-256G-1002 256GB    | 2         | 0.55%   |
| Unknown MMC Card  32GB                  | 2         | 0.55%   |
| Union Memory UMIS RPJTJ512MEE1OWX 512GB | 2         | 0.55%   |
| Toshiba NVMe SSD Drive 512GB            | 2         | 0.55%   |
| Toshiba NVMe SSD Drive 256GB            | 2         | 0.55%   |
| Toshiba MQ01ABD050 500GB                | 2         | 0.55%   |
| Toshiba MK1637GSX 160GB                 | 2         | 0.55%   |
| SPCC Solid State Disk 120GB             | 2         | 0.55%   |
| SK hynix HFS128G32TNF-N3A0A 128GB SSD   | 2         | 0.55%   |
| Seagate ST9500325AS 500GB               | 2         | 0.55%   |
| SanDisk SD9SN8W256G1014 256GB SSD       | 2         | 0.55%   |
| SanDisk NVMe SSD Drive 512GB            | 2         | 0.55%   |
| Samsung SSD 860 EVO M.2 500GB           | 2         | 0.55%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 50        | 58     | 30.86%  |
| WDC                 | 40        | 61     | 24.69%  |
| Toshiba             | 38        | 47     | 23.46%  |
| Hitachi             | 18        | 18     | 11.11%  |
| HGST                | 8         | 17     | 4.94%   |
| Fujitsu             | 5         | 5      | 3.09%   |
| Unknown             | 1         | 1      | 0.62%   |
| Samsung Electronics | 1         | 2      | 0.62%   |
| IBM/Hitachi         | 1         | 1      | 0.62%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 23        | 28     | 22.12%  |
| Kingston            | 21        | 24     | 20.19%  |
| Patriot             | 10        | 12     | 9.62%   |
| SanDisk             | 6         | 10     | 5.77%   |
| SPCC                | 5         | 6      | 4.81%   |
| Micron Technology   | 5         | 5      | 4.81%   |
| Toshiba             | 4         | 5      | 3.85%   |
| Intel               | 4         | 5      | 3.85%   |
| Transcend           | 3         | 3      | 2.88%   |
| SK hynix            | 3         | 3      | 2.88%   |
| GeIL                | 3         | 3      | 2.88%   |
| A-DATA Technology   | 3         | 3      | 2.88%   |
| LITEON              | 2         | 3      | 1.92%   |
| Gigabyte Technology | 2         | 2      | 1.92%   |
| Crucial             | 2         | 2      | 1.92%   |
| Biostar             | 2         | 2      | 1.92%   |
| WDC                 | 1         | 2      | 0.96%   |
| Verbatim            | 1         | 1      | 0.96%   |
| SSSTC               | 1         | 1      | 0.96%   |
| PNY                 | 1         | 1      | 0.96%   |
| Netac               | 1         | 1      | 0.96%   |
| AMD                 | 1         | 1      | 0.96%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 162       | 210    | 46.55%  |
| SSD     | 96        | 123    | 27.59%  |
| NVMe    | 79        | 106    | 22.7%   |
| MMC     | 10        | 11     | 2.87%   |
| Unknown | 1         | 1      | 0.29%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 234       | 330    | 71.56%  |
| NVMe | 78        | 105    | 23.85%  |
| MMC  | 10        | 11     | 3.06%   |
| SAS  | 5         | 5      | 1.53%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 185       | 235    | 73.12%  |
| 0.51-1.0   | 65        | 93     | 25.69%  |
| 1.01-2.0   | 3         | 5      | 1.19%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 96        | 29%     |
| 251-500        | 93        | 28.1%   |
| 501-1000       | 41        | 12.39%  |
| 1-20           | 28        | 8.46%   |
| 51-100         | 26        | 7.85%   |
| 21-50          | 20        | 6.04%   |
| Unknown        | 14        | 4.23%   |
| 1001-2000      | 7         | 2.11%   |
| 2001-3000      | 5         | 1.51%   |
| More than 3000 | 1         | 0.3%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 143       | 41.94%  |
| 21-50     | 63        | 18.48%  |
| 101-250   | 44        | 12.9%   |
| 51-100    | 44        | 12.9%   |
| 251-500   | 22        | 6.45%   |
| Unknown   | 14        | 4.11%   |
| 501-1000  | 8         | 2.35%   |
| 1001-2000 | 3         | 0.88%   |

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
| Fujitsu MHW2160BH PL 152GB              | 1         | 1      | 4.35%   |

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
| Detected | 187       | 292    | 58.62%  |
| Works    | 109       | 129    | 34.17%  |
| Malfunc  | 23        | 30     | 7.21%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 237       | 66.2%   |
| AMD                          | 38        | 10.61%  |
| Samsung Electronics          | 22        | 6.15%   |
| SanDisk                      | 15        | 4.19%   |
| SK hynix                     | 14        | 3.91%   |
| Nvidia                       | 5         | 1.4%    |
| Toshiba America Info Systems | 4         | 1.12%   |
| Phison Electronics           | 4         | 1.12%   |
| KIOXIA                       | 4         | 1.12%   |
| Union Memory (Shenzhen)      | 3         | 0.84%   |
| Micron Technology            | 3         | 0.84%   |
| Kingston Technology Company  | 3         | 0.84%   |
| VIA Technologies             | 1         | 0.28%   |
| Silicon Image                | 1         | 0.28%   |
| Realtek Semiconductor        | 1         | 0.28%   |
| JMicron Technology           | 1         | 0.28%   |
| ASMedia Technology           | 1         | 0.28%   |
| ADATA Technology             | 1         | 0.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 30        | 7.67%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 29        | 7.42%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 25        | 6.39%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 22        | 5.63%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 19        | 4.86%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 13        | 3.32%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 9         | 2.3%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 9         | 2.3%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 9         | 2.3%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 8         | 2.05%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 8         | 2.05%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 8         | 2.05%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 8         | 2.05%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 8         | 2.05%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 8         | 2.05%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 7         | 1.79%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 7         | 1.79%   |
| SK hynix BC511                                                                   | 6         | 1.53%   |
| SanDisk Non-Volatile memory controller                                           | 6         | 1.53%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 6         | 1.53%   |
| Samsung NVMe SSD Controller 980                                                  | 6         | 1.53%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 6         | 1.53%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 6         | 1.53%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 6         | 1.53%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 5         | 1.28%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 5         | 1.28%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 4         | 1.02%   |
| Nvidia MCP79 AHCI Controller                                                     | 4         | 1.02%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 4         | 1.02%   |
| Intel Volume Management Device NVMe RAID Controller                              | 4         | 1.02%   |
| Intel Tiger Lake-LP SATA Controller                                              | 4         | 1.02%   |
| Intel SSD 660P Series                                                            | 4         | 1.02%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 4         | 1.02%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 4         | 1.02%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 4         | 1.02%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 3         | 0.77%   |
| SK hynix Non-Volatile memory controller                                          | 3         | 0.77%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 3         | 0.77%   |
| Micron Non-Volatile memory controller                                            | 3         | 0.77%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3         | 0.77%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 243       | 63.95%  |
| NVMe | 82        | 21.58%  |
| IDE  | 29        | 7.63%   |
| RAID | 26        | 6.84%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 258       | 84.04%  |
| AMD    | 49        | 15.96%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 8         | 2.61%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 6         | 1.95%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 6         | 1.95%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 5         | 1.63%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 1.63%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 1.63%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 5         | 1.63%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 5         | 1.63%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 5         | 1.63%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 5         | 1.63%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 4         | 1.3%    |
| Intel Celeron CPU N3060 @ 1.60GHz             | 4         | 1.3%    |
| Intel Celeron CPU 1000M @ 1.80GHz             | 4         | 1.3%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 4         | 1.3%    |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 4         | 1.3%    |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 4         | 1.3%    |
| Intel Pentium M processor 1.86GHz             | 3         | 0.98%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 3         | 0.98%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 0.98%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 3         | 0.98%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 3         | 0.98%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 3         | 0.98%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 0.98%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 3         | 0.98%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 3         | 0.98%   |
| Intel Core 2 CPU T5600 @ 1.83GHz              | 3         | 0.98%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 3         | 0.98%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 3         | 0.98%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 2         | 0.65%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 2         | 0.65%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 2         | 0.65%   |
| Intel Pentium CPU B950 @ 2.10GHz              | 2         | 0.65%   |
| Intel Pentium CPU 4417U @ 2.30GHz             | 2         | 0.65%   |
| Intel Pentium CPU 3825U @ 1.90GHz             | 2         | 0.65%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 2         | 0.65%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 2         | 0.65%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 2         | 0.65%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 0.65%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 0.65%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 0.65%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 61        | 19.87%  |
| Intel Core i5           | 60        | 19.54%  |
| Intel Core i3           | 33        | 10.75%  |
| Intel Celeron           | 31        | 10.1%   |
| Intel Pentium           | 26        | 8.47%   |
| AMD Ryzen 5             | 18        | 5.86%   |
| Intel Core 2 Duo        | 13        | 4.23%   |
| Other                   | 10        | 3.26%   |
| AMD Ryzen 7             | 9         | 2.93%   |
| Intel Atom              | 7         | 2.28%   |
| Intel Core 2            | 4         | 1.3%    |
| Intel Pentium M         | 3         | 0.98%   |
| Intel Pentium Dual      | 3         | 0.98%   |
| AMD Ryzen 3             | 3         | 0.98%   |
| AMD A8                  | 3         | 0.98%   |
| Intel Pentium Silver    | 2         | 0.65%   |
| Intel Pentium Dual-Core | 2         | 0.65%   |
| Intel Genuine           | 2         | 0.65%   |
| AMD Athlon X2           | 2         | 0.65%   |
| AMD Athlon II Dual-Core | 2         | 0.65%   |
| AMD Athlon II           | 2         | 0.65%   |
| AMD A4                  | 2         | 0.65%   |
| Intel Pentium Gold      | 1         | 0.33%   |
| Intel Core Duo          | 1         | 0.33%   |
| Intel Celeron M         | 1         | 0.33%   |
| AMD V120                | 1         | 0.33%   |
| AMD Turion 64 X2 Mobile | 1         | 0.33%   |
| AMD Phenom II           | 1         | 0.33%   |
| AMD E2                  | 1         | 0.33%   |
| AMD E1                  | 1         | 0.33%   |
| AMD A6                  | 1         | 0.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 163       | 53.09%  |
| 4      | 108       | 35.18%  |
| 6      | 16        | 5.21%   |
| 1      | 14        | 4.56%   |
| 8      | 5         | 1.63%   |
| 14     | 1         | 0.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 307       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 198       | 64.5%   |
| 1      | 109       | 35.5%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 288       | 93.51%  |
| Unknown        | 11        | 3.57%   |
| 32-bit         | 9         | 2.92%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 46        | 14.38%  |
| 0x206a7    | 30        | 9.38%   |
| 0x806ea    | 16        | 5%      |
| 0x306a9    | 16        | 5%      |
| 0x406e3    | 14        | 4.38%   |
| 0x506c9    | 12        | 3.75%   |
| 0x906ea    | 10        | 3.13%   |
| 0x706e5    | 10        | 3.13%   |
| 0x806e9    | 8         | 2.5%    |
| 0x306d4    | 8         | 2.5%    |
| 0x6fd      | 7         | 2.19%   |
| 0x40651    | 7         | 2.19%   |
| 0x08108102 | 7         | 2.19%   |
| 0x906e9    | 6         | 1.88%   |
| 0x806ec    | 6         | 1.88%   |
| 0x806eb    | 6         | 1.88%   |
| 0x806c1    | 6         | 1.88%   |
| 0x406c4    | 6         | 1.88%   |
| 0x306c3    | 6         | 1.88%   |
| 0x08108109 | 6         | 1.88%   |
| 0x506e3    | 5         | 1.56%   |
| 0x30678    | 5         | 1.56%   |
| 0x10676    | 5         | 1.56%   |
| 0xa0652    | 4         | 1.25%   |
| 0x20655    | 4         | 1.25%   |
| 0x1067a    | 4         | 1.25%   |
| 0x08608103 | 4         | 1.25%   |
| 0x706a8    | 3         | 0.94%   |
| 0x706a1    | 3         | 0.94%   |
| 0x6d8      | 3         | 0.94%   |
| 0x30673    | 3         | 0.94%   |
| 0x106ca    | 3         | 0.94%   |
| 0x0810100b | 3         | 0.94%   |
| 0x6ec      | 2         | 0.63%   |
| 0x6e8      | 2         | 0.63%   |
| 0x406c3    | 2         | 0.63%   |
| 0x20652    | 2         | 0.63%   |
| 0x106c2    | 2         | 0.63%   |
| 0x08600104 | 2         | 0.63%   |
| 0x08101007 | 2         | 0.63%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 55        | 17.92%  |
| SandyBridge      | 34        | 11.07%  |
| Skylake          | 20        | 6.51%   |
| Haswell          | 18        | 5.86%   |
| Silvermont       | 17        | 5.54%   |
| IvyBridge        | 17        | 5.54%   |
| Core             | 14        | 4.56%   |
| Zen+             | 13        | 4.23%   |
| Goldmont         | 13        | 4.23%   |
| IceLake          | 11        | 3.58%   |
| Westmere         | 10        | 3.26%   |
| Penryn           | 9         | 2.93%   |
| Broadwell        | 9         | 2.93%   |
| TigerLake        | 8         | 2.61%   |
| Zen              | 7         | 2.28%   |
| P6               | 7         | 2.28%   |
| K10              | 6         | 1.95%   |
| Goldmont plus    | 6         | 1.95%   |
| Zen 2            | 5         | 1.63%   |
| Bonnell          | 5         | 1.63%   |
| Unknown          | 5         | 1.63%   |
| CometLake        | 4         | 1.3%    |
| Puma             | 3         | 0.98%   |
| Excavator        | 3         | 0.98%   |
| Piledriver       | 2         | 0.65%   |
| K8 & K10 hybrid  | 2         | 0.65%   |
| Zen 3            | 1         | 0.33%   |
| K8 Hammer        | 1         | 0.33%   |
| Jaguar           | 1         | 0.33%   |
| Alderlake Hybrid | 1         | 0.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 234       | 58.06%  |
| Nvidia           | 86        | 21.34%  |
| AMD              | 82        | 20.35%  |
| VIA Technologies | 1         | 0.25%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 31        | 7.4%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 17        | 4.06%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 14        | 3.34%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 14        | 3.34%   |
| Intel UHD Graphics 620                                                                   | 12        | 2.86%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 12        | 2.86%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 11        | 2.63%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 10        | 2.39%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 9         | 2.15%   |
| Intel HD Graphics 620                                                                    | 9         | 2.15%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9         | 2.15%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 9         | 2.15%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 9         | 2.15%   |
| Intel HD Graphics 500                                                                    | 8         | 1.91%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 1.91%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 8         | 1.91%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 7         | 1.67%   |
| Intel HD Graphics 5500                                                                   | 7         | 1.67%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 1.67%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 1.43%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 6         | 1.43%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 6         | 1.43%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 1.19%   |
| Intel HD Graphics 630                                                                    | 5         | 1.19%   |
| Intel HD Graphics 530                                                                    | 5         | 1.19%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 5         | 1.19%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 5         | 1.19%   |
| AMD Renoir                                                                               | 5         | 1.19%   |
| AMD Lucienne                                                                             | 5         | 1.19%   |
| Nvidia GP108M [GeForce MX230]                                                            | 4         | 0.95%   |
| Nvidia GP108M [GeForce MX150]                                                            | 4         | 0.95%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 4         | 0.95%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 0.95%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 0.95%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.72%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 0.72%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 0.72%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 3         | 0.72%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 0.72%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 145       | 46.93%  |
| Intel + Nvidia | 67        | 21.68%  |
| 1 x AMD        | 47        | 15.21%  |
| Intel + AMD    | 24        | 7.77%   |
| 1 x Nvidia     | 13        | 4.21%   |
| 2 x AMD        | 6         | 1.94%   |
| AMD + Nvidia   | 5         | 1.62%   |
| 2 x Nvidia     | 1         | 0.32%   |
| 1 x VIA        | 1         | 0.32%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 265       | 84.94%  |
| Proprietary | 37        | 11.86%  |
| Unknown     | 10        | 3.21%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 177       | 55.84%  |
| 1.01-2.0   | 58        | 18.3%   |
| 0.01-0.5   | 41        | 12.93%  |
| 3.01-4.0   | 25        | 7.89%   |
| 0.51-1.0   | 16        | 5.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 74        | 21.26%  |
| LG Display              | 54        | 15.52%  |
| BOE                     | 51        | 14.66%  |
| Chimei Innolux          | 44        | 12.64%  |
| Samsung Electronics     | 34        | 9.77%   |
| Dell                    | 10        | 2.87%   |
| Lenovo                  | 9         | 2.59%   |
| Chi Mei Optoelectronics | 8         | 2.3%    |
| PANDA                   | 7         | 2.01%   |
| Apple                   | 6         | 1.72%   |
| Philips                 | 5         | 1.44%   |
| LG Philips              | 5         | 1.44%   |
| Hewlett-Packard         | 5         | 1.44%   |
| Sony                    | 4         | 1.15%   |
| Sharp                   | 4         | 1.15%   |
| CPT                     | 4         | 1.15%   |
| InfoVision              | 3         | 0.86%   |
| Goldstar                | 3         | 0.86%   |
| BenQ                    | 3         | 0.86%   |
| Unknown                 | 2         | 0.57%   |
| Toshiba                 | 2         | 0.57%   |
| ViewSonic               | 1         | 0.29%   |
| SKY                     | 1         | 0.29%   |
| Seiko/Epson             | 1         | 0.29%   |
| LPL                     | 1         | 0.29%   |
| InnoLux Display         | 1         | 0.29%   |
| Iiyama                  | 1         | 0.29%   |
| Hitachi                 | 1         | 0.29%   |
| HannStar                | 1         | 0.29%   |
| ASUSTek Computer        | 1         | 0.29%   |
| AOC                     | 1         | 0.29%   |
| Ancor Communications    | 1         | 0.29%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 16        | 4.55%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 8         | 2.27%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 8         | 2.27%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 6         | 1.7%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 5         | 1.42%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 5         | 1.42%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 4         | 1.14%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 4         | 1.14%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 4         | 1.14%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch            | 3         | 0.85%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 3         | 0.85%   |
| Dell P2417H DELA0DC 1920x1080 527x296mm 23.8-inch                        | 3         | 0.85%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 3         | 0.85%   |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch         | 3         | 0.85%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 3         | 0.85%   |
| BOE LCD Monitor BOE07A3 1920x1080 344x193mm 15.5-inch                    | 3         | 0.85%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 3         | 0.85%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 3         | 0.85%   |
| Sony LCD SNY06FA 1600x900 291x164mm 13.2-inch                            | 2         | 0.57%   |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch     | 2         | 0.57%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch     | 2         | 0.57%   |
| Samsung Electronics LCD Monitor SDC4154 2880x1800 302x189mm 14.0-inch    | 2         | 0.57%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch    | 2         | 0.57%   |
| PANDA LCD Monitor NCP006E 1920x1080 344x194mm 15.5-inch                  | 2         | 0.57%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 2         | 0.57%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch             | 2         | 0.57%   |
| LG Display LCD Monitor LGD0519 1920x1080 344x194mm 15.5-inch             | 2         | 0.57%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 2         | 0.57%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch              | 2         | 0.57%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 2         | 0.57%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 2         | 0.57%   |
| Lenovo L24q-10 LEN65CF 2560x1440 527x296mm 23.8-inch                     | 2         | 0.57%   |
| Dell U2412M DELA079 1920x1200 518x324mm 24.1-inch                        | 2         | 0.57%   |
| CPT LCD Monitor CPT14BF 1366x768 344x193mm 15.5-inch                     | 2         | 0.57%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch         | 2         | 0.57%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 2         | 0.57%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch          | 2         | 0.57%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 2         | 0.57%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 0.57%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 2         | 0.57%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 151       | 46.18%  |
| 1366x768 (WXGA)    | 115       | 35.17%  |
| 1280x800 (WXGA)    | 13        | 3.98%   |
| 1600x900 (HD+)     | 8         | 2.45%   |
| 1440x900 (WXGA+)   | 5         | 1.53%   |
| 3840x2160 (4K)     | 4         | 1.22%   |
| 2560x1440 (QHD)    | 4         | 1.22%   |
| 1360x768           | 4         | 1.22%   |
| 1920x1200 (WUXGA)  | 3         | 0.92%   |
| 1680x1050 (WSXGA+) | 3         | 0.92%   |
| 1024x600           | 3         | 0.92%   |
| 2880x1800          | 2         | 0.61%   |
| 1280x1024 (SXGA)   | 2         | 0.61%   |
| 1024x768 (XGA)     | 2         | 0.61%   |
| Unknown            | 2         | 0.61%   |
| 3360x1200          | 1         | 0.31%   |
| 3280x1080          | 1         | 0.31%   |
| 2560x1600          | 1         | 0.31%   |
| 1920x540           | 1         | 0.31%   |
| 1680x945           | 1         | 0.31%   |
| 1400x1050          | 1         | 0.31%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 208       | 59.94%  |
| 13      | 28        | 8.07%   |
| 14      | 21        | 6.05%   |
| 17      | 20        | 5.76%   |
| 24      | 14        | 4.03%   |
| 23      | 10        | 2.88%   |
| 21      | 7         | 2.02%   |
| Unknown | 6         | 1.73%   |
| 27      | 5         | 1.44%   |
| 12      | 5         | 1.44%   |
| 11      | 5         | 1.44%   |
| 72      | 3         | 0.86%   |
| 31      | 3         | 0.86%   |
| 10      | 2         | 0.58%   |
| 84      | 1         | 0.29%   |
| 54      | 1         | 0.29%   |
| 46      | 1         | 0.29%   |
| 40      | 1         | 0.29%   |
| 32      | 1         | 0.29%   |
| 26      | 1         | 0.29%   |
| 20      | 1         | 0.29%   |
| 19      | 1         | 0.29%   |
| 18      | 1         | 0.29%   |
| 8       | 1         | 0.29%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 244       | 70.32%  |
| 501-600     | 30        | 8.65%   |
| 351-400     | 23        | 6.63%   |
| 201-300     | 22        | 6.34%   |
| 401-500     | 10        | 2.88%   |
| Unknown     | 6         | 1.73%   |
| 1501-2000   | 4         | 1.15%   |
| 601-700     | 3         | 0.86%   |
| 1001-1500   | 2         | 0.58%   |
| 801-900     | 1         | 0.29%   |
| 701-800     | 1         | 0.29%   |
| 101-200     | 1         | 0.29%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 272       | 89.18%  |
| 16/10   | 24        | 7.87%   |
| 4/3     | 4         | 1.31%   |
| Unknown | 3         | 0.98%   |
| 5/4     | 1         | 0.33%   |
| 3/2     | 1         | 0.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 208       | 59.77%  |
| 81-90          | 41        | 11.78%  |
| 201-250        | 28        | 8.05%   |
| 121-130        | 19        | 5.46%   |
| 71-80          | 8         | 2.3%    |
| 301-350        | 6         | 1.72%   |
| Unknown        | 6         | 1.72%   |
| More than 1000 | 5         | 1.44%   |
| 51-60          | 5         | 1.44%   |
| 61-70          | 4         | 1.15%   |
| 351-500        | 4         | 1.15%   |
| 251-300        | 3         | 0.86%   |
| 151-200        | 3         | 0.86%   |
| 41-50          | 2         | 0.57%   |
| 501-1000       | 2         | 0.57%   |
| 1-40           | 1         | 0.29%   |
| 141-150        | 1         | 0.29%   |
| 131-140        | 1         | 0.29%   |
| 91-100         | 1         | 0.29%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 145       | 43.15%  |
| 101-120       | 119       | 35.42%  |
| 51-100        | 52        | 15.48%  |
| 161-240       | 7         | 2.08%   |
| Unknown       | 6         | 1.79%   |
| 1-50          | 4         | 1.19%   |
| More than 240 | 3         | 0.89%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 254       | 80.63%  |
| 2     | 49        | 15.56%  |
| 0     | 7         | 2.22%   |
| 3     | 5         | 1.59%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 183       | 35.95%  |
| Intel                             | 133       | 26.13%  |
| Qualcomm Atheros                  | 98        | 19.25%  |
| Broadcom                          | 37        | 7.27%   |
| Ralink                            | 9         | 1.77%   |
| Broadcom Limited                  | 8         | 1.57%   |
| Nvidia                            | 5         | 0.98%   |
| Marvell Technology Group          | 5         | 0.98%   |
| Ralink Technology                 | 4         | 0.79%   |
| Dell                              | 4         | 0.79%   |
| MediaTek                          | 3         | 0.59%   |
| Huawei Technologies               | 3         | 0.59%   |
| Ericsson Business Mobile Networks | 3         | 0.59%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.39%   |
| Sierra Wireless                   | 2         | 0.39%   |
| Qualcomm Atheros Communications   | 2         | 0.39%   |
| VIA Technologies                  | 1         | 0.2%    |
| TP-Link                           | 1         | 0.2%    |
| Linksys                           | 1         | 0.2%    |
| JMicron Technology                | 1         | 0.2%    |
| IMC Networks                      | 1         | 0.2%    |
| D-Link                            | 1         | 0.2%    |
| Arduino SA                        | 1         | 0.2%    |
| Apple                             | 1         | 0.2%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 105       | 17.36%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 56        | 9.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 28        | 4.63%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 18        | 2.98%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 17        | 2.81%   |
| Intel Wireless 8265 / 8275                                              | 16        | 2.64%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 11        | 1.82%   |
| Broadcom BCM43142 802.11b/g/n                                           | 11        | 1.82%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 10        | 1.65%   |
| Intel Wireless 8260                                                     | 10        | 1.65%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 9         | 1.49%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 8         | 1.32%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 7         | 1.16%   |
| Intel Wireless 7260                                                     | 7         | 1.16%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 7         | 1.16%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 7         | 1.16%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 1.16%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 7         | 1.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 0.99%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 6         | 0.99%   |
| Intel Wireless 3165                                                     | 6         | 0.99%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 6         | 0.99%   |
| Intel Ethernet Connection (4) I219-LM                                   | 6         | 0.99%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 5         | 0.83%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 5         | 0.83%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 0.83%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 0.83%   |
| Intel Ethernet Connection I219-LM                                       | 5         | 0.83%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 4         | 0.66%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 4         | 0.66%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 4         | 0.66%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 4         | 0.66%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 4         | 0.66%   |
| Nvidia MCP79 Ethernet                                                   | 4         | 0.66%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 0.66%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 0.66%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 0.66%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 4         | 0.66%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 3         | 0.5%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 126       | 39.25%  |
| Qualcomm Atheros                  | 85        | 26.48%  |
| Realtek Semiconductor             | 51        | 15.89%  |
| Broadcom                          | 29        | 9.03%   |
| Ralink                            | 9         | 2.8%    |
| Ralink Technology                 | 4         | 1.25%   |
| MediaTek                          | 3         | 0.93%   |
| Dell                              | 3         | 0.93%   |
| Sierra Wireless                   | 2         | 0.62%   |
| Qualcomm Atheros Communications   | 2         | 0.62%   |
| Broadcom Limited                  | 2         | 0.62%   |
| TP-Link                           | 1         | 0.31%   |
| Linksys                           | 1         | 0.31%   |
| IMC Networks                      | 1         | 0.31%   |
| Ericsson Business Mobile Networks | 1         | 0.31%   |
| D-Link                            | 1         | 0.31%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 28        | 8.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 18        | 5.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 17        | 5.28%   |
| Intel Wireless 8265 / 8275                                              | 16        | 4.97%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 11        | 3.42%   |
| Broadcom BCM43142 802.11b/g/n                                           | 11        | 3.42%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 10        | 3.11%   |
| Intel Wireless 8260                                                     | 10        | 3.11%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 9         | 2.8%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 8         | 2.48%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 7         | 2.17%   |
| Intel Wireless 7260                                                     | 7         | 2.17%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 7         | 2.17%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 7         | 2.17%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 2.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 1.86%   |
| Intel Wireless 3165                                                     | 6         | 1.86%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 6         | 1.86%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 5         | 1.55%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 5         | 1.55%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 1.55%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 1.55%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.24%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 4         | 1.24%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 4         | 1.24%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 4         | 1.24%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 1.24%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 1.24%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 1.24%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 0.93%   |
| Intel Wireless 3160                                                     | 3         | 0.93%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 0.93%   |
| Intel Centrino Wireless-N 2230                                          | 3         | 0.93%   |
| Intel Centrino Ultimate-N 6300                                          | 3         | 0.93%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 0.93%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                                    | 3         | 0.93%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 3         | 0.93%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 3         | 0.93%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 0.62%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 2         | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 166       | 61.03%  |
| Intel                      | 50        | 18.38%  |
| Qualcomm Atheros           | 22        | 8.09%   |
| Broadcom                   | 12        | 4.41%   |
| Broadcom Limited           | 6         | 2.21%   |
| Nvidia                     | 5         | 1.84%   |
| Marvell Technology Group   | 5         | 1.84%   |
| ZTE WCDMA Technologies MSM | 2         | 0.74%   |
| VIA Technologies           | 1         | 0.37%   |
| JMicron Technology         | 1         | 0.37%   |
| Huawei Technologies        | 1         | 0.37%   |
| Apple                      | 1         | 0.37%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 105       | 38.18%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 56        | 20.36%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 2.55%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 6         | 2.18%   |
| Intel Ethernet Connection (4) I219-LM                             | 6         | 2.18%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 1.82%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 4         | 1.45%   |
| Nvidia MCP79 Ethernet                                             | 4         | 1.45%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 4         | 1.45%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 1.09%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 1.09%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.09%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 1.09%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 1.09%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 1.09%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 0.73%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.73%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 2         | 0.73%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.73%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.73%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.73%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 0.73%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 0.73%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 0.73%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 0.73%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 2         | 0.73%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 2         | 0.73%   |
| ZTE WCDMA MSM ZTE WCDMA MSM                                       | 1         | 0.36%   |
| ZTE WCDMA MSM ZTE                                                 | 1         | 0.36%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.36%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.36%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.36%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.36%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.36%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.36%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.36%   |
| Nvidia MCP67 Ethernet                                             | 1         | 0.36%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.36%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.36%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 307       | 52.57%  |
| Ethernet | 269       | 46.06%  |
| Modem    | 8         | 1.37%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 256       | 77.58%  |
| Ethernet | 74        | 22.42%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 261       | 84.74%  |
| 1     | 47        | 15.26%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 304       | 98.7%   |
| Yes  | 4         | 1.3%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 89        | 35.74%  |
| Realtek Semiconductor           | 38        | 15.26%  |
| Qualcomm Atheros Communications | 31        | 12.45%  |
| Lite-On Technology              | 21        | 8.43%   |
| IMC Networks                    | 16        | 6.43%   |
| Broadcom                        | 13        | 5.22%   |
| Foxconn / Hon Hai               | 8         | 3.21%   |
| Toshiba                         | 6         | 2.41%   |
| Apple                           | 6         | 2.41%   |
| Hewlett-Packard                 | 4         | 1.61%   |
| Ralink                          | 3         | 1.2%    |
| Foxconn International           | 3         | 1.2%    |
| Dell                            | 3         | 1.2%    |
| USI                             | 2         | 0.8%    |
| Ralink Technology               | 2         | 0.8%    |
| Cambridge Silicon Radio         | 2         | 0.8%    |
| Askey Computer                  | 1         | 0.4%    |
| Alps Electric                   | 1         | 0.4%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 44        | 17.67%  |
| Realtek Bluetooth Radio                             | 23        | 9.24%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 21        | 8.43%   |
| Qualcomm Atheros  Bluetooth Device                  | 17        | 6.83%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 12        | 4.82%   |
| Realtek  Bluetooth 4.2 Adapter                      | 11        | 4.42%   |
| Intel AX201 Bluetooth                               | 8         | 3.21%   |
| IMC Networks Bluetooth Radio                        | 7         | 2.81%   |
| Lite-On Bluetooth Device                            | 5         | 2.01%   |
| Intel AX200 Bluetooth                               | 5         | 2.01%   |
| Apple Bluetooth Host Controller                     | 5         | 2.01%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 4         | 1.61%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 4         | 1.61%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 1.61%   |
| Ralink RT3290 Bluetooth                             | 3         | 1.2%    |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 1.2%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 3         | 1.2%    |
| IMC Networks Bluetooth Device                       | 3         | 1.2%    |
| Foxconn International BCM43142A0 Bluetooth module   | 3         | 1.2%    |
| Foxconn / Hon Hai Bluetooth Device                  | 3         | 1.2%    |
| Dell DW375 Bluetooth Module                         | 3         | 1.2%    |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 3         | 1.2%    |
| USI Bluetooth Module BCM92070                       | 2         | 0.8%    |
| Toshiba Bluetooth Device                            | 2         | 0.8%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 2         | 0.8%    |
| Realtek RTL8723B Bluetooth                          | 2         | 0.8%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 0.8%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 0.8%    |
| Qualcomm Atheros AR3012 Bluetooth                   | 2         | 0.8%    |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.8%    |
| IMC Networks Wireless_Device                        | 2         | 0.8%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 0.8%    |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 0.8%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 0.8%    |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 2         | 0.8%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 0.8%    |
| Broadcom BCM43142 Bluetooth 4.0                     | 2         | 0.8%    |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 2         | 0.8%    |
| Toshiba RT Bluetooth Radio                          | 1         | 0.4%    |
| Toshiba Integrated Bluetooth (Taiyo Yuden)          | 1         | 0.4%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 251       | 71.1%   |
| AMD                 | 54        | 15.3%   |
| Nvidia              | 40        | 11.33%  |
| GN Netcom           | 2         | 0.57%   |
| VIA Technologies    | 1         | 0.28%   |
| Native Instruments  | 1         | 0.28%   |
| Kingston Technology | 1         | 0.28%   |
| Hewlett-Packard     | 1         | 0.28%   |
| Focusrite-Novation  | 1         | 0.28%   |
| Apple               | 1         | 0.28%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 39        | 9.22%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 31        | 7.33%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 28        | 6.62%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 23        | 5.44%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 19        | 4.49%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 13        | 3.07%   |
| Intel Cannon Lake PCH cAVS                                                                        | 12        | 2.84%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 11        | 2.6%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 11        | 2.6%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 10        | 2.36%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 10        | 2.36%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 9         | 2.13%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 2.13%   |
| Intel Broadwell-U Audio Controller                                                                | 9         | 2.13%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 9         | 2.13%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 9         | 2.13%   |
| Intel 8 Series HD Audio Controller                                                                | 9         | 2.13%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 9         | 2.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 8         | 1.89%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 8         | 1.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 8         | 1.89%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 8         | 1.89%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 8         | 1.89%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 7         | 1.65%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 6         | 1.42%   |
| Intel CM238 HD Audio Controller                                                                   | 6         | 1.42%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 1.42%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 6         | 1.42%   |
| AMD FCH Azalia Controller                                                                         | 6         | 1.42%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 1.18%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 5         | 1.18%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.18%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 5         | 1.18%   |
| Nvidia MCP79 High Definition Audio                                                                | 4         | 0.95%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 0.95%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 0.95%   |
| AMD High Definition Audio Controller                                                              | 3         | 0.71%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 0.71%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 2         | 0.47%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 2         | 0.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 49        | 24.62%  |
| SK hynix            | 47        | 23.62%  |
| Micron Technology   | 31        | 15.58%  |
| Kingston            | 26        | 13.07%  |
| Unknown             | 15        | 7.54%   |
| Ramaxel Technology  | 9         | 4.52%   |
| Transcend           | 7         | 3.52%   |
| Patriot             | 3         | 1.51%   |
| Crucial             | 2         | 1.01%   |
| Corsair             | 2         | 1.01%   |
| A-DATA Technology   | 2         | 1.01%   |
| SHARETRONIC         | 1         | 0.5%    |
| PNY                 | 1         | 0.5%    |
| Nanya Technology    | 1         | 0.5%    |
| Elpida              | 1         | 0.5%    |
| Apacer              | 1         | 0.5%    |
| 48spaces            | 1         | 0.5%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s       | 5         | 2.3%    |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s        | 5         | 2.3%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s      | 4         | 1.84%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s      | 4         | 1.84%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s      | 4         | 1.84%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s       | 4         | 1.84%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s       | 4         | 1.84%   |
| Micron RAM 4ATF51264HZ-2G6E! 4GB SODIMM DDR4 2400MT/s       | 4         | 1.84%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 3         | 1.38%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s      | 3         | 1.38%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s       | 3         | 1.38%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s       | 3         | 1.38%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s       | 3         | 1.38%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8192MB SODIMM DDR4 2667MT/s     | 3         | 1.38%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB SODIMM DDR4 3200MT/s     | 3         | 1.38%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s     | 3         | 1.38%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                  | 2         | 0.92%   |
| Unknown RAM Module 1024MB SODIMM DDR                        | 2         | 0.92%   |
| Transcend RAM JM3200HSG-8G 8192MB SODIMM DDR4 2667MT/s      | 2         | 0.92%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM SDRAM 2048MT/s     | 2         | 0.92%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s      | 2         | 0.92%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s      | 2         | 0.92%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s      | 2         | 0.92%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s   | 2         | 0.92%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s      | 2         | 0.92%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s       | 2         | 0.92%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s       | 2         | 0.92%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s       | 2         | 0.92%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 2         | 0.92%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s       | 2         | 0.92%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s       | 2         | 0.92%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s | 2         | 0.92%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s       | 2         | 0.92%   |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s     | 2         | 0.92%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                 | 1         | 0.46%   |
| Unknown RAM Module 8192MB SODIMM DDR4 3200MT/s              | 1         | 0.46%   |
| Unknown RAM Module 4GB SODIMM DDR3                          | 1         | 0.46%   |
| Unknown RAM Module 2GB SODIMM DDR2                          | 1         | 0.46%   |
| Unknown RAM Module 2GB SODIMM                               | 1         | 0.46%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s               | 1         | 0.46%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 76        | 48.41%  |
| DDR3    | 54        | 34.39%  |
| DDR2    | 11        | 7.01%   |
| SDRAM   | 5         | 3.18%   |
| LPDDR4  | 5         | 3.18%   |
| DDR     | 2         | 1.27%   |
| Unknown | 2         | 1.27%   |
| LPDDR5  | 1         | 0.64%   |
| LPDDR3  | 1         | 0.64%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 148       | 93.67%  |
| Row Of Chips | 9         | 5.7%    |
| Chip         | 1         | 0.63%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 62        | 35.84%  |
| 4096  | 60        | 34.68%  |
| 2048  | 30        | 17.34%  |
| 16384 | 10        | 5.78%   |
| 1024  | 9         | 5.2%    |
| 32768 | 1         | 0.58%   |
| 512   | 1         | 0.58%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 41        | 23.03%  |
| 1600    | 40        | 22.47%  |
| 3200    | 29        | 16.29%  |
| 2400    | 16        | 8.99%   |
| 1334    | 10        | 5.62%   |
| 667     | 6         | 3.37%   |
| Unknown | 6         | 3.37%   |
| 2133    | 5         | 2.81%   |
| 1333    | 4         | 2.25%   |
| 1067    | 4         | 2.25%   |
| 3266    | 3         | 1.69%   |
| 2048    | 3         | 1.69%   |
| 4199    | 2         | 1.12%   |
| 975     | 2         | 1.12%   |
| 800     | 2         | 1.12%   |
| 533     | 2         | 1.12%   |
| 6400    | 1         | 0.56%   |
| 4267    | 1         | 0.56%   |
| 1066    | 1         | 0.56%   |

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
| Canon LBP6030w/6018w                  | 1         | 11.11%  |
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
| Chicony Electronics                    | 78        | 27.66%  |
| IMC Networks                           | 42        | 14.89%  |
| Realtek Semiconductor                  | 25        | 8.87%   |
| Microdia                               | 20        | 7.09%   |
| Quanta                                 | 17        | 6.03%   |
| Acer                                   | 17        | 6.03%   |
| Suyin                                  | 15        | 5.32%   |
| Sunplus Innovation Technology          | 14        | 4.96%   |
| Cheng Uei Precision Industry (Foxlink) | 14        | 4.96%   |
| Syntek                                 | 11        | 3.9%    |
| Lite-On Technology                     | 7         | 2.48%   |
| Apple                                  | 6         | 2.13%   |
| Importek                               | 3         | 1.06%   |
| Silicon Motion                         | 2         | 0.71%   |
| Luxvisions Innotech Limited            | 2         | 0.71%   |
| Alcor Micro                            | 2         | 0.71%   |
| Samsung Electronics                    | 1         | 0.35%   |
| Ricoh                                  | 1         | 0.35%   |
| OmniVision Technologies                | 1         | 0.35%   |
| Logitech                               | 1         | 0.35%   |
| Lenovo                                 | 1         | 0.35%   |
| KYE Systems (Mouse Systems)            | 1         | 0.35%   |
| DigiTech                               | 1         | 0.35%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                             | 19        | 6.71%   |
| Chicony Integrated Camera                                      | 16        | 5.65%   |
| Realtek Integrated_Webcam_HD                                   | 9         | 3.18%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 9         | 3.18%   |
| Syntek Integrated Camera                                       | 8         | 2.83%   |
| Microdia Integrated_Webcam_HD                                  | 7         | 2.47%   |
| Sunplus Integrated_Webcam_HD                                   | 6         | 2.12%   |
| Acer Integrated Camera                                         | 6         | 2.12%   |
| Quanta VGA WebCam                                              | 5         | 1.77%   |
| Quanta HD WebCam                                               | 5         | 1.77%   |
| IMC Networks Integrated Camera                                 | 5         | 1.77%   |
| Chicony TOSHIBA Web Camera - HD                                | 5         | 1.77%   |
| Chicony Integrated Camera (1280x720@30)                        | 5         | 1.77%   |
| Chicony EasyCamera                                             | 5         | 1.77%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                       | 4         | 1.41%   |
| Realtek USB Camera                                             | 4         | 1.41%   |
| Realtek Lenovo EasyCamera                                      | 4         | 1.41%   |
| Chicony VGA Webcam                                             | 4         | 1.41%   |
| Chicony HP Webcam                                              | 4         | 1.41%   |
| Chicony HD WebCam                                              | 4         | 1.41%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 4         | 1.41%   |
| Syntek EasyCamera                                              | 3         | 1.06%   |
| Realtek Integrated Webcam HD                                   | 3         | 1.06%   |
| Quanta HP TrueVision HD Camera                                 | 3         | 1.06%   |
| Microdia Integrated Webcam                                     | 3         | 1.06%   |
| IMC Networks EasyCamera                                        | 3         | 1.06%   |
| Chicony USB 2.0 Camera                                         | 3         | 1.06%   |
| Chicony HD User Facing                                         | 3         | 1.06%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 3         | 1.06%   |
| Apple FaceTime HD Camera                                       | 3         | 1.06%   |
| Acer Lenovo EasyCamera                                         | 3         | 1.06%   |
| Acer BisonCam, NB Pro                                          | 3         | 1.06%   |
| Suyin Acer CrystalEye Webcam                                   | 2         | 0.71%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)    | 2         | 0.71%   |
| Sunplus HP Wide Vision HD                                      | 2         | 0.71%   |
| Sunplus ASUS USB2.0 Webcam                                     | 2         | 0.71%   |
| Microdia HP Webcam                                             | 2         | 0.71%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 2         | 0.71%   |
| Lite-On Integrated Camera                                      | 2         | 0.71%   |
| Lite-On HP TrueVision HD Camera                                | 2         | 0.71%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 20        | 40%     |
| Synaptics                  | 9         | 18%     |
| Shenzhen Goodix Technology | 8         | 16%     |
| AuthenTec                  | 5         | 10%     |
| Upek                       | 3         | 6%      |
| LighTuning Technology      | 2         | 4%      |
| Elan Microelectronics      | 2         | 4%      |
| STMicroelectronics         | 1         | 2%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 7         | 14%     |
| Validity Sensors VFS495 Fingerprint Reader                                 | 5         | 10%     |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 8%      |
| Synaptics  WBDI                                                            | 4         | 8%      |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 4         | 8%      |
| AuthenTec AES2501 Fingerprint Sensor                                       | 3         | 6%      |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 4%      |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 4%      |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 4%      |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 4%      |
| Elan ELAN:Fingerprint                                                      | 2         | 4%      |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 2%      |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 2%      |
| Validity Sensors Synaptics WBDI                                            | 1         | 2%      |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2%      |
| Validity Sensors Fingerprint scanner                                       | 1         | 2%      |
| Upek TCS5B Fingerprint sensor                                              | 1         | 2%      |
| STMicroelectronics Fingerprint Reader                                      | 1         | 2%      |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 2%      |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 2%      |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 2%      |
| AuthenTec AES2810                                                          | 1         | 2%      |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 2%      |
| Unknown                                                                    | 1         | 2%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 9         | 42.86%  |
| Alcor Micro           | 6         | 28.57%  |
| OmniKey               | 2         | 9.52%   |
| O2 Micro              | 2         | 9.52%   |
| Lenovo                | 1         | 4.76%   |
| Gemalto (was Gemplus) | 1         | 4.76%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader               | 6         | 28.57%  |
| Broadcom BCM5880 Secure Applications Processor    | 4         | 19.05%  |
| Broadcom 5880                                     | 4         | 19.05%  |
| O2 Micro OZ776 CCID Smartcard Reader              | 2         | 9.52%   |
| OmniKey CardMan 4321                              | 1         | 4.76%   |
| OmniKey 3x21 Smart Card Reader                    | 1         | 4.76%   |
| Lenovo Integrated Smart Card Reader               | 1         | 4.76%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 1         | 4.76%   |
| Broadcom 58200                                    | 1         | 4.76%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 204       | 63.75%  |
| 1     | 88        | 27.5%   |
| 2     | 23        | 7.19%   |
| 4     | 2         | 0.63%   |
| 3     | 2         | 0.63%   |
| 8     | 1         | 0.31%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 50        | 34.48%  |
| Graphics card            | 32        | 22.07%  |
| Chipcard                 | 20        | 13.79%  |
| Net/wireless             | 16        | 11.03%  |
| Bluetooth                | 6         | 4.14%   |
| Multimedia controller    | 5         | 3.45%   |
| Communication controller | 5         | 3.45%   |
| Camera                   | 3         | 2.07%   |
| Sound                    | 2         | 1.38%   |
| Net/ethernet             | 2         | 1.38%   |
| Card reader              | 2         | 1.38%   |
| Storage                  | 1         | 0.69%   |
| Modem                    | 1         | 0.69%   |

