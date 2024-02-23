Linux in Colombia - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Colombia.

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

Total: 1123

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | Bravo 17 A4DDR              | [bbf603e6e6](https://linux-hardware.org/?probe=bbf603e6e6) | Jan 30, 2024 |
| Acer          | Aspire E1-470               | [732a523ea8](https://linux-hardware.org/?probe=732a523ea8) | Jan 28, 2024 |
| Notebook      | N150CU                      | [fc98de3ad4](https://linux-hardware.org/?probe=fc98de3ad4) | Jan 28, 2024 |
| Dell          | Inspiron 5570               | [0fce3dbe59](https://linux-hardware.org/?probe=0fce3dbe59) | Jan 27, 2024 |
| HP            | ProBook 440 G7              | [47b3929229](https://linux-hardware.org/?probe=47b3929229) | Jan 25, 2024 |
| Lenovo        | IdeaPad 3-15ALC6 82KU       | [c91921bbe1](https://linux-hardware.org/?probe=c91921bbe1) | Jan 24, 2024 |
| Dell          | Inspiron 5570               | [7c453fba6f](https://linux-hardware.org/?probe=7c453fba6f) | Jan 23, 2024 |
| Apple         | MacBookPro9,2               | [a8557f8a49](https://linux-hardware.org/?probe=a8557f8a49) | Jan 17, 2024 |
| Acer          | TravelMate P214-53          | [dbe5ed82b8](https://linux-hardware.org/?probe=dbe5ed82b8) | Jan 16, 2024 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [24da300af6](https://linux-hardware.org/?probe=24da300af6) | Jan 16, 2024 |
| HP            | ProBook 445 G7              | [a9499322c3](https://linux-hardware.org/?probe=a9499322c3) | Jan 15, 2024 |
| Lenovo        | ThinkPad T430 2347AF3       | [c52851e59b](https://linux-hardware.org/?probe=c52851e59b) | Jan 15, 2024 |
| COIN COMPU... | LUM580                      | [e9f6bacb29](https://linux-hardware.org/?probe=e9f6bacb29) | Jan 15, 2024 |
| Dell          | XPS 13 9370                 | [74e153aeed](https://linux-hardware.org/?probe=74e153aeed) | Jan 11, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [be9bd3885e](https://linux-hardware.org/?probe=be9bd3885e) | Jan 11, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [54e682c32b](https://linux-hardware.org/?probe=54e682c32b) | Jan 10, 2024 |
| Lenovo        | IdeaPad Slim 3 15AMN8 82... | [9a12d1146d](https://linux-hardware.org/?probe=9a12d1146d) | Jan 09, 2024 |
| HP            | Laptop 15-db0xxx            | [5de015033e](https://linux-hardware.org/?probe=5de015033e) | Jan 08, 2024 |
| HP            | Laptop 15-db0xxx            | [f9da9135c7](https://linux-hardware.org/?probe=f9da9135c7) | Jan 08, 2024 |
| Lenovo        | IdeaPad 3 14IAU7 82RJ       | [9b3ba608ee](https://linux-hardware.org/?probe=9b3ba608ee) | Jan 06, 2024 |
| HP            | Presario CQ45               | [8a0a9f1dc0](https://linux-hardware.org/?probe=8a0a9f1dc0) | Jan 04, 2024 |
| HP            | Victus by Laptop 16-d0xx... | [442c8e3a83](https://linux-hardware.org/?probe=442c8e3a83) | Jan 03, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [61c1444cfc](https://linux-hardware.org/?probe=61c1444cfc) | Dec 29, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [4ba914628d](https://linux-hardware.org/?probe=4ba914628d) | Dec 29, 2023 |
| COIN COMPU... | LUM580                      | [6a8246b500](https://linux-hardware.org/?probe=6a8246b500) | Dec 28, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [8250429628](https://linux-hardware.org/?probe=8250429628) | Dec 28, 2023 |
| Lenovo        | ThinkPad T510 43492RU       | [87b76140e0](https://linux-hardware.org/?probe=87b76140e0) | Dec 28, 2023 |
| Lenovo        | ThinkPad T510 43492RU       | [d3f51b650d](https://linux-hardware.org/?probe=d3f51b650d) | Dec 27, 2023 |
| Toshiba       | Satellite Pro L450          | [8da0c619f3](https://linux-hardware.org/?probe=8da0c619f3) | Dec 24, 2023 |
| Apple         | MacBookPro9,2               | [41256541b5](https://linux-hardware.org/?probe=41256541b5) | Dec 21, 2023 |
| Dell          | Latitude E7270              | [4574a46c78](https://linux-hardware.org/?probe=4574a46c78) | Dec 21, 2023 |
| HP            | EliteBook 840 G6            | [5266cee35b](https://linux-hardware.org/?probe=5266cee35b) | Dec 21, 2023 |
| Dell          | Latitude E5450              | [6d4e378f53](https://linux-hardware.org/?probe=6d4e378f53) | Dec 20, 2023 |
| HUAWEI        | BOHB-WAX9                   | [7b4cd22d8d](https://linux-hardware.org/?probe=7b4cd22d8d) | Dec 20, 2023 |
| Dell          | Latitude E5450              | [627a81b211](https://linux-hardware.org/?probe=627a81b211) | Dec 19, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [2d2f0f8de2](https://linux-hardware.org/?probe=2d2f0f8de2) | Dec 19, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [4e18aeb53f](https://linux-hardware.org/?probe=4e18aeb53f) | Dec 18, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [756283ec58](https://linux-hardware.org/?probe=756283ec58) | Dec 12, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [c258c213e6](https://linux-hardware.org/?probe=c258c213e6) | Dec 12, 2023 |
| HP            | ProBook 450 G3              | [06651b08d9](https://linux-hardware.org/?probe=06651b08d9) | Dec 11, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [ccd16e5c8d](https://linux-hardware.org/?probe=ccd16e5c8d) | Dec 11, 2023 |
| Sony          | SVE11115ELW                 | [68fa8c6081](https://linux-hardware.org/?probe=68fa8c6081) | Dec 10, 2023 |
| Sony          | SVE11115ELW                 | [567787c7d3](https://linux-hardware.org/?probe=567787c7d3) | Dec 10, 2023 |
| HP            | G42                         | [f23e6ffe56](https://linux-hardware.org/?probe=f23e6ffe56) | Dec 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [cf8f25ba97](https://linux-hardware.org/?probe=cf8f25ba97) | Dec 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [673016ba0f](https://linux-hardware.org/?probe=673016ba0f) | Dec 07, 2023 |
| Notebook      | P15SM-A/SM1-A               | [f7c8033eef](https://linux-hardware.org/?probe=f7c8033eef) | Dec 06, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [fc51759095](https://linux-hardware.org/?probe=fc51759095) | Dec 06, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [1cfd81f715](https://linux-hardware.org/?probe=1cfd81f715) | Dec 05, 2023 |
| Lenovo        | G40-30 80FY                 | [219f784b96](https://linux-hardware.org/?probe=219f784b96) | Dec 04, 2023 |
| Acer          | Aspire E1-470               | [507314cc1f](https://linux-hardware.org/?probe=507314cc1f) | Dec 04, 2023 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [218e5c18f3](https://linux-hardware.org/?probe=218e5c18f3) | Dec 04, 2023 |
| Sony          | SVP13215PLS                 | [6c360dc427](https://linux-hardware.org/?probe=6c360dc427) | Dec 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [7b5d061328](https://linux-hardware.org/?probe=7b5d061328) | Dec 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [1729d2c4c1](https://linux-hardware.org/?probe=1729d2c4c1) | Dec 02, 2023 |
| Acer          | Aspire A314-22              | [d91455d676](https://linux-hardware.org/?probe=d91455d676) | Nov 30, 2023 |
| Acer          | Nitro AN515-55              | [6865be0fd7](https://linux-hardware.org/?probe=6865be0fd7) | Nov 29, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [5aee774fa3](https://linux-hardware.org/?probe=5aee774fa3) | Nov 27, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [8378baf644](https://linux-hardware.org/?probe=8378baf644) | Nov 26, 2023 |
| ASUSTek       | Vivobook Go E1504GAB_E15... | [d733fc5f50](https://linux-hardware.org/?probe=d733fc5f50) | Nov 24, 2023 |
| ASUSTek       | Vivobook Go E1504GAB_E15... | [17fd894479](https://linux-hardware.org/?probe=17fd894479) | Nov 24, 2023 |
| Dell          | Latitude 3410               | [db53da231e](https://linux-hardware.org/?probe=db53da231e) | Nov 22, 2023 |
| HP            | ProBook 440 G7              | [b3b8fff6bb](https://linux-hardware.org/?probe=b3b8fff6bb) | Nov 19, 2023 |
| Acer          | Aspire 4750                 | [1e7be1c070](https://linux-hardware.org/?probe=1e7be1c070) | Nov 18, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [2af4aec091](https://linux-hardware.org/?probe=2af4aec091) | Nov 17, 2023 |
| Dell          | Inspiron 5421               | [e8f49a554a](https://linux-hardware.org/?probe=e8f49a554a) | Nov 16, 2023 |
| Dell          | Inspiron 5421               | [5e6d967f4d](https://linux-hardware.org/?probe=5e6d967f4d) | Nov 16, 2023 |
| Toshiba       | NB205                       | [a3f0bef4d4](https://linux-hardware.org/?probe=a3f0bef4d4) | Nov 15, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [6806c7c828](https://linux-hardware.org/?probe=6806c7c828) | Nov 15, 2023 |
| Lenovo        | G40-70 20369                | [c103e79147](https://linux-hardware.org/?probe=c103e79147) | Nov 14, 2023 |
| Toshiba       | Satellite A665D             | [eed03ef68f](https://linux-hardware.org/?probe=eed03ef68f) | Nov 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [4a32a91914](https://linux-hardware.org/?probe=4a32a91914) | Nov 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [5fdbcfb950](https://linux-hardware.org/?probe=5fdbcfb950) | Nov 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [6185a29334](https://linux-hardware.org/?probe=6185a29334) | Nov 09, 2023 |
| HP            | Laptop 15-ef2xxx            | [b0d207b140](https://linux-hardware.org/?probe=b0d207b140) | Nov 07, 2023 |
| Lenovo        | IdeaPad S400u 20213         | [5ddd610c2d](https://linux-hardware.org/?probe=5ddd610c2d) | Nov 06, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [b3e37dd334](https://linux-hardware.org/?probe=b3e37dd334) | Nov 06, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [f5a032555f](https://linux-hardware.org/?probe=f5a032555f) | Nov 06, 2023 |
| Lenovo        | ThinkPad Edge E431 62771... | [8d789a3937](https://linux-hardware.org/?probe=8d789a3937) | Nov 06, 2023 |
| Dell          | Latitude 3410               | [4ffdc962bf](https://linux-hardware.org/?probe=4ffdc962bf) | Nov 01, 2023 |
| Notebook      | N150CU                      | [a345496524](https://linux-hardware.org/?probe=a345496524) | Nov 01, 2023 |
| HUAWEI        | WRTD-WXX9                   | [ec6be29d3e](https://linux-hardware.org/?probe=ec6be29d3e) | Oct 29, 2023 |
| Notebook      | N150CU                      | [12347d42c1](https://linux-hardware.org/?probe=12347d42c1) | Oct 28, 2023 |
| Dell          | Inspiron 14-3467            | [ea07cbb7c4](https://linux-hardware.org/?probe=ea07cbb7c4) | Oct 24, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [de15a66a8b](https://linux-hardware.org/?probe=de15a66a8b) | Oct 22, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [037cfc67ae](https://linux-hardware.org/?probe=037cfc67ae) | Oct 22, 2023 |
| ASUSTek       | N552VW                      | [dd755eb3a0](https://linux-hardware.org/?probe=dd755eb3a0) | Oct 22, 2023 |
| ASUSTek       | N552VW                      | [c511cce283](https://linux-hardware.org/?probe=c511cce283) | Oct 22, 2023 |
| MSI           | Alpha 17 B5EEK              | [125e76df80](https://linux-hardware.org/?probe=125e76df80) | Oct 20, 2023 |
| MSI           | Alpha 17 B5EEK              | [3a5c553fcb](https://linux-hardware.org/?probe=3a5c553fcb) | Oct 20, 2023 |
| Apple         | MacBookPro9,2               | [01c73b9338](https://linux-hardware.org/?probe=01c73b9338) | Oct 18, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [8b92e44d64](https://linux-hardware.org/?probe=8b92e44d64) | Oct 17, 2023 |
| Apple         | MacBookPro9,2               | [4b5b669131](https://linux-hardware.org/?probe=4b5b669131) | Oct 12, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [cc8062e568](https://linux-hardware.org/?probe=cc8062e568) | Oct 12, 2023 |
| Lenovo        | G40-45 80E1                 | [d773c4faf0](https://linux-hardware.org/?probe=d773c4faf0) | Oct 09, 2023 |
| Lenovo        | G400 20235                  | [4f9d192833](https://linux-hardware.org/?probe=4f9d192833) | Oct 06, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [f10db8b926](https://linux-hardware.org/?probe=f10db8b926) | Oct 04, 2023 |
| HP            | Laptop 14-cf2xxx            | [4c6c3c41b3](https://linux-hardware.org/?probe=4c6c3c41b3) | Oct 03, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [380e23e27d](https://linux-hardware.org/?probe=380e23e27d) | Oct 03, 2023 |
| Lenovo        | ThinkPad E495 20NES07V00    | [935dc10f6b](https://linux-hardware.org/?probe=935dc10f6b) | Sep 30, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [c1a605af33](https://linux-hardware.org/?probe=c1a605af33) | Sep 29, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [6275e5c1d4](https://linux-hardware.org/?probe=6275e5c1d4) | Sep 29, 2023 |
| ASUSTek       | X441NA                      | [e44f45e8d6](https://linux-hardware.org/?probe=e44f45e8d6) | Sep 28, 2023 |
| Acer          | Predator G3-571             | [f301a514ad](https://linux-hardware.org/?probe=f301a514ad) | Sep 27, 2023 |
| Acer          | Predator G3-571             | [06b0300670](https://linux-hardware.org/?probe=06b0300670) | Sep 27, 2023 |
| Lenovo        | ThinkPad T430 2347H6U       | [7fc871cd5e](https://linux-hardware.org/?probe=7fc871cd5e) | Sep 26, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [73d2dae51c](https://linux-hardware.org/?probe=73d2dae51c) | Sep 26, 2023 |
| ASUSTek       | X550DP                      | [a743f84823](https://linux-hardware.org/?probe=a743f84823) | Sep 24, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [0531db8cb8](https://linux-hardware.org/?probe=0531db8cb8) | Sep 24, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [01b1c1acdb](https://linux-hardware.org/?probe=01b1c1acdb) | Sep 24, 2023 |
| ASUSTek       | X555LJ                      | [2edb781d68](https://linux-hardware.org/?probe=2edb781d68) | Sep 22, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [a9cfc8946d](https://linux-hardware.org/?probe=a9cfc8946d) | Sep 21, 2023 |
| Dell          | Vostro 1310                 | [bc0c23c23c](https://linux-hardware.org/?probe=bc0c23c23c) | Sep 21, 2023 |
| Lenovo        | G400 20235                  | [bd7a7a6f22](https://linux-hardware.org/?probe=bd7a7a6f22) | Sep 17, 2023 |
| Lenovo        | G400 20235                  | [c8ecd1e0c9](https://linux-hardware.org/?probe=c8ecd1e0c9) | Sep 17, 2023 |
| Apple         | MacBookPro5,5               | [bd4081fcfc](https://linux-hardware.org/?probe=bd4081fcfc) | Sep 17, 2023 |
| Dell          | System XPS L502X            | [d3154f94d7](https://linux-hardware.org/?probe=d3154f94d7) | Sep 17, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [8934a85f1f](https://linux-hardware.org/?probe=8934a85f1f) | Sep 16, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | [7050f11f50](https://linux-hardware.org/?probe=7050f11f50) | Sep 13, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [0317b3bcf6](https://linux-hardware.org/?probe=0317b3bcf6) | Sep 13, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [37f8406bab](https://linux-hardware.org/?probe=37f8406bab) | Sep 13, 2023 |
| Lenovo        | E41-55 82FJ                 | [20b3dd0858](https://linux-hardware.org/?probe=20b3dd0858) | Sep 13, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | [0893eb24cb](https://linux-hardware.org/?probe=0893eb24cb) | Sep 13, 2023 |
| HP            | 240 14 inch G9 Notebook ... | [23652eaf70](https://linux-hardware.org/?probe=23652eaf70) | Sep 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [d4178bc91c](https://linux-hardware.org/?probe=d4178bc91c) | Sep 11, 2023 |
| Toshiba       | Satellite M645              | [40c02e9bc9](https://linux-hardware.org/?probe=40c02e9bc9) | Sep 10, 2023 |
| Lenovo        | ThinkPad X220 42872WS       | [9bd18b41ed](https://linux-hardware.org/?probe=9bd18b41ed) | Sep 09, 2023 |
| Acer          | Nitro AN515-55              | [3f247b15c6](https://linux-hardware.org/?probe=3f247b15c6) | Sep 09, 2023 |
| Dell          | Inspiron 1545               | [95d13f26f0](https://linux-hardware.org/?probe=95d13f26f0) | Sep 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [4e30077177](https://linux-hardware.org/?probe=4e30077177) | Sep 08, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [d5430e9279](https://linux-hardware.org/?probe=d5430e9279) | Sep 08, 2023 |
| Sony          | SVE14A25CLW                 | [9646f55c7d](https://linux-hardware.org/?probe=9646f55c7d) | Sep 08, 2023 |
| Sony          | SVE14A25CLW                 | [3f8a5dcaaf](https://linux-hardware.org/?probe=3f8a5dcaaf) | Sep 08, 2023 |
| HUAWEI        | BOHB-WAX9                   | [5d575aeb4f](https://linux-hardware.org/?probe=5d575aeb4f) | Sep 06, 2023 |
| Lenovo        | ThinkPad T430 2349MPS       | [183e5c528c](https://linux-hardware.org/?probe=183e5c528c) | Sep 03, 2023 |
| HP            | Pavilion Notebook           | [3143c94134](https://linux-hardware.org/?probe=3143c94134) | Sep 02, 2023 |
| HP            | 245 G7 Notebook PC          | [bb268c3828](https://linux-hardware.org/?probe=bb268c3828) | Sep 02, 2023 |
| Dell          | Latitude 5430               | [7a9eb9995d](https://linux-hardware.org/?probe=7a9eb9995d) | Sep 02, 2023 |
| HP            | Compaq Presario C700        | [c0030f3b3b](https://linux-hardware.org/?probe=c0030f3b3b) | Sep 01, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [24ad5e2b06](https://linux-hardware.org/?probe=24ad5e2b06) | Aug 31, 2023 |
| Lenovo        | G40-70 20369                | [f3cef329f6](https://linux-hardware.org/?probe=f3cef329f6) | Aug 30, 2023 |
| HP            | Compaq Presario C700        | [bc78db6077](https://linux-hardware.org/?probe=bc78db6077) | Aug 29, 2023 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | [de34a44939](https://linux-hardware.org/?probe=de34a44939) | Aug 29, 2023 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | [776efe803f](https://linux-hardware.org/?probe=776efe803f) | Aug 29, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [78d168c88e](https://linux-hardware.org/?probe=78d168c88e) | Aug 29, 2023 |
| Lenovo        | IdeaPad 1 14IAU7 82QC       | [90e0cad295](https://linux-hardware.org/?probe=90e0cad295) | Aug 28, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | [9fcb646019](https://linux-hardware.org/?probe=9fcb646019) | Aug 27, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | [9ce11e1efa](https://linux-hardware.org/?probe=9ce11e1efa) | Aug 27, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [657c08f61f](https://linux-hardware.org/?probe=657c08f61f) | Aug 27, 2023 |
| Acer          | Aspire A715-72G             | [cbbaecabb1](https://linux-hardware.org/?probe=cbbaecabb1) | Aug 26, 2023 |
| Apple         | MacBookPro13,2              | [b910d52198](https://linux-hardware.org/?probe=b910d52198) | Aug 26, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [2a05992a61](https://linux-hardware.org/?probe=2a05992a61) | Aug 21, 2023 |
| HP            | Laptop 15-bs0xx             | [5f2a27253a](https://linux-hardware.org/?probe=5f2a27253a) | Aug 21, 2023 |
| HP            | Laptop 15-bs0xx             | [5e76f9bfc3](https://linux-hardware.org/?probe=5e76f9bfc3) | Aug 21, 2023 |
| Apple         | MacBookPro9,2               | [4006007a76](https://linux-hardware.org/?probe=4006007a76) | Aug 20, 2023 |
| ASUSTek       | X450CC                      | [21750fb927](https://linux-hardware.org/?probe=21750fb927) | Aug 19, 2023 |
| HP            | Pavilion Notebook           | [ed75b0702f](https://linux-hardware.org/?probe=ed75b0702f) | Aug 19, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [3a916bde7d](https://linux-hardware.org/?probe=3a916bde7d) | Aug 16, 2023 |
| ASUSTek       | ZenBook Pro Duo UX582ZM_... | [b3f31fbc53](https://linux-hardware.org/?probe=b3f31fbc53) | Aug 16, 2023 |
| Lenovo        | IdeaPadFlex 10 20324        | [8b4200849d](https://linux-hardware.org/?probe=8b4200849d) | Aug 15, 2023 |
| Lenovo        | IdeaPad 1 14ALC7 82R3       | [0766dc4b96](https://linux-hardware.org/?probe=0766dc4b96) | Aug 13, 2023 |
| Lenovo        | IdeaPad 1 14ALC7 82R3       | [6480e1b649](https://linux-hardware.org/?probe=6480e1b649) | Aug 13, 2023 |
| Dell          | G15 5510                    | [3cfac2d234](https://linux-hardware.org/?probe=3cfac2d234) | Aug 12, 2023 |
| Lenovo        | V310-14ISK 80SX             | [edd47d65b6](https://linux-hardware.org/?probe=edd47d65b6) | Aug 12, 2023 |
| Acer          | Aspire V5-471P              | [cbd4a63b2e](https://linux-hardware.org/?probe=cbd4a63b2e) | Aug 10, 2023 |
| Dell          | Precision 5530              | [3b10bebb7d](https://linux-hardware.org/?probe=3b10bebb7d) | Aug 10, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [03a4763a96](https://linux-hardware.org/?probe=03a4763a96) | Aug 08, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [87ee840e89](https://linux-hardware.org/?probe=87ee840e89) | Aug 07, 2023 |
| HP            | Laptop 15-db0xxx            | [5889bc8dc7](https://linux-hardware.org/?probe=5889bc8dc7) | Aug 06, 2023 |
| COMPUMAX C... | MOBIL                       | [60293c1ac3](https://linux-hardware.org/?probe=60293c1ac3) | Aug 06, 2023 |
| Acer          | Aspire A715-72G             | [4afe306798](https://linux-hardware.org/?probe=4afe306798) | Aug 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [364aa911cf](https://linux-hardware.org/?probe=364aa911cf) | Aug 05, 2023 |
| Acer          | Aspire A715-72G             | [d0bad7993f](https://linux-hardware.org/?probe=d0bad7993f) | Aug 02, 2023 |
| Dell          | Inspiron 15 3511            | [3ea3ff2535](https://linux-hardware.org/?probe=3ea3ff2535) | Jul 31, 2023 |
| MSI           | Katana 17 B13VFK            | [8bc597da6e](https://linux-hardware.org/?probe=8bc597da6e) | Jul 29, 2023 |
| Dell          | Inspiron 13 5310            | [5f44d0b1d8](https://linux-hardware.org/?probe=5f44d0b1d8) | Jul 26, 2023 |
| Lenovo        | ThinkPad T460 20FMS15W07    | [6a77133959](https://linux-hardware.org/?probe=6a77133959) | Jul 25, 2023 |
| Google        | Treeya                      | [808e203694](https://linux-hardware.org/?probe=808e203694) | Jul 24, 2023 |
| Google        | Treeya                      | [db2b782253](https://linux-hardware.org/?probe=db2b782253) | Jul 24, 2023 |
| MSI           | Modern 15 A5M               | [1763ff7356](https://linux-hardware.org/?probe=1763ff7356) | Jul 18, 2023 |
| HP            | Laptop 14-cf2xxx            | [04dce054f4](https://linux-hardware.org/?probe=04dce054f4) | Jul 17, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [ef2395800e](https://linux-hardware.org/?probe=ef2395800e) | Jul 16, 2023 |
| Acer          | Nitro AN515-55              | [c9a21bf55e](https://linux-hardware.org/?probe=c9a21bf55e) | Jul 14, 2023 |
| HP            | 245 G8                      | [07eefc20b0](https://linux-hardware.org/?probe=07eefc20b0) | Jul 13, 2023 |
| Apple         | MacBookPro9,2               | [34fe8ff1ad](https://linux-hardware.org/?probe=34fe8ff1ad) | Jul 13, 2023 |
| Apple         | MacBookPro9,2               | [a3d301a82a](https://linux-hardware.org/?probe=a3d301a82a) | Jul 13, 2023 |
| Dell          | Vostro 3400                 | [93d94feca6](https://linux-hardware.org/?probe=93d94feca6) | Jul 11, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [eccd385af4](https://linux-hardware.org/?probe=eccd385af4) | Jul 11, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [9cc59dffca](https://linux-hardware.org/?probe=9cc59dffca) | Jul 11, 2023 |
| Compumax C... | ONIX-CEL-0001               | [bd1c8f9529](https://linux-hardware.org/?probe=bd1c8f9529) | Jul 11, 2023 |
| HP            | Notebook                    | [9242935b2b](https://linux-hardware.org/?probe=9242935b2b) | Jul 10, 2023 |
| Apple         | MacBookPro12,1              | [75dc3bfda0](https://linux-hardware.org/?probe=75dc3bfda0) | Jul 04, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | [2f5812cb86](https://linux-hardware.org/?probe=2f5812cb86) | Jul 01, 2023 |
| HP            | Laptop 15-ef2xxx            | [d0ea6a2d9d](https://linux-hardware.org/?probe=d0ea6a2d9d) | Jun 30, 2023 |
| Dell          | Latitude E5450              | [e0826ab83a](https://linux-hardware.org/?probe=e0826ab83a) | Jun 30, 2023 |
| Acer          | Aspire A314-22              | [ef54ec3027](https://linux-hardware.org/?probe=ef54ec3027) | Jun 30, 2023 |
| PCsmart       | PCSGOB14p-C                 | [a45977461f](https://linux-hardware.org/?probe=a45977461f) | Jun 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [b47fa47ef7](https://linux-hardware.org/?probe=b47fa47ef7) | Jun 23, 2023 |
| HP            | Laptop 15-da0xxx            | [71f5fde47b](https://linux-hardware.org/?probe=71f5fde47b) | Jun 23, 2023 |
| Dell          | Vostro 1400                 | [7b5011ff7c](https://linux-hardware.org/?probe=7b5011ff7c) | Jun 22, 2023 |
| Dell          | Vostro 1400                 | [c41c17d657](https://linux-hardware.org/?probe=c41c17d657) | Jun 22, 2023 |
| Apple         | MacBookPro9,2               | [544b40258b](https://linux-hardware.org/?probe=544b40258b) | Jun 21, 2023 |
| Acer          | Aspire A314-22              | [676efbb266](https://linux-hardware.org/?probe=676efbb266) | Jun 18, 2023 |
| Compumax C... | ONIX-CEL-0001               | [2fb2088533](https://linux-hardware.org/?probe=2fb2088533) | Jun 17, 2023 |
| Toshiba       | Satellite L45-B             | [4cc6199522](https://linux-hardware.org/?probe=4cc6199522) | Jun 15, 2023 |
| ASUSTek       | GL552VW                     | [f3b0b03ace](https://linux-hardware.org/?probe=f3b0b03ace) | Jun 12, 2023 |
| Apple         | MacBookPro9,2               | [29d4909dd4](https://linux-hardware.org/?probe=29d4909dd4) | Jun 12, 2023 |
| HUAWEI        | KLVL-WXX9                   | [235239b42b](https://linux-hardware.org/?probe=235239b42b) | Jun 11, 2023 |
| Apple         | MacBookAir5,1               | [53ba4689ae](https://linux-hardware.org/?probe=53ba4689ae) | Jun 10, 2023 |
| Apple         | MacBookAir5,1               | [58f4272bee](https://linux-hardware.org/?probe=58f4272bee) | Jun 10, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [2f0f8eb596](https://linux-hardware.org/?probe=2f0f8eb596) | Jun 09, 2023 |
| Apple         | MacBookPro9,2               | [baf92c8b36](https://linux-hardware.org/?probe=baf92c8b36) | Jun 08, 2023 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | [42eab3e3af](https://linux-hardware.org/?probe=42eab3e3af) | Jun 08, 2023 |
| HP            | ZBook 15 G2                 | [ac292cca00](https://linux-hardware.org/?probe=ac292cca00) | Jun 08, 2023 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | [5c63c42a5c](https://linux-hardware.org/?probe=5c63c42a5c) | Jun 04, 2023 |
| Apple         | MacBookPro14,2              | [8f73724b8a](https://linux-hardware.org/?probe=8f73724b8a) | Jun 02, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [3de415ea72](https://linux-hardware.org/?probe=3de415ea72) | Jun 01, 2023 |
| Acer          | Aspire A315-59              | [3f08f70d3a](https://linux-hardware.org/?probe=3f08f70d3a) | May 31, 2023 |
| ASUSTek       | X550LD                      | [e091c09373](https://linux-hardware.org/?probe=e091c09373) | May 29, 2023 |
| Compumax C... | ONIX-CEL-0001               | [2f5d8e6789](https://linux-hardware.org/?probe=2f5d8e6789) | May 26, 2023 |
| Acer          | Aspire A314-22              | [776f5c2411](https://linux-hardware.org/?probe=776f5c2411) | May 25, 2023 |
| Acer          | Aspire A314-22              | [e2110ab5da](https://linux-hardware.org/?probe=e2110ab5da) | May 25, 2023 |
| ASUSTek       | X450CC                      | [ca431e5e80](https://linux-hardware.org/?probe=ca431e5e80) | May 24, 2023 |
| Lenovo        | IdeaPadFlex 10 20324        | [ac4be1ce4d](https://linux-hardware.org/?probe=ac4be1ce4d) | May 11, 2023 |
| Toshiba       | Satellite C55-C             | [1f5654331d](https://linux-hardware.org/?probe=1f5654331d) | May 09, 2023 |
| HP            | Laptop 15-ef2xxx            | [96c2411d79](https://linux-hardware.org/?probe=96c2411d79) | May 08, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | [6e28d6fd76](https://linux-hardware.org/?probe=6e28d6fd76) | May 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [fe61386871](https://linux-hardware.org/?probe=fe61386871) | May 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [764f38bb65](https://linux-hardware.org/?probe=764f38bb65) | May 05, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [a00f293aa7](https://linux-hardware.org/?probe=a00f293aa7) | May 04, 2023 |
| HP            | Laptop 15-ef2xxx            | [d29dae3c91](https://linux-hardware.org/?probe=d29dae3c91) | May 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [e8ce8c11c0](https://linux-hardware.org/?probe=e8ce8c11c0) | May 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [dca12f3f6a](https://linux-hardware.org/?probe=dca12f3f6a) | Apr 29, 2023 |
| Toshiba       | Satellite C45-A             | [7720195dfe](https://linux-hardware.org/?probe=7720195dfe) | Apr 24, 2023 |
| Lenovo        | ThinkBook 14-IML 20RV       | [32546113c8](https://linux-hardware.org/?probe=32546113c8) | Apr 24, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [18fc5f09ed](https://linux-hardware.org/?probe=18fc5f09ed) | Apr 23, 2023 |
| Acer          | Nitro AN515-52              | [e3dc4788e7](https://linux-hardware.org/?probe=e3dc4788e7) | Apr 22, 2023 |
| HP            | ProBook 440 G7              | [50408f04cb](https://linux-hardware.org/?probe=50408f04cb) | Apr 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [901b3d11dc](https://linux-hardware.org/?probe=901b3d11dc) | Apr 20, 2023 |
| HP            | G42                         | [dd87e935d0](https://linux-hardware.org/?probe=dd87e935d0) | Apr 20, 2023 |
| Lenovo        | G40-30 80FY                 | [923b3fd46b](https://linux-hardware.org/?probe=923b3fd46b) | Apr 19, 2023 |
| Lenovo        | ThinkBook 14-IML 20RV       | [d532f6fdbd](https://linux-hardware.org/?probe=d532f6fdbd) | Apr 16, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [7852e88a19](https://linux-hardware.org/?probe=7852e88a19) | Apr 11, 2023 |
| Apple         | MacBookPro14,2              | [1bc09aed8a](https://linux-hardware.org/?probe=1bc09aed8a) | Apr 10, 2023 |
| HUAWEI        | WRTD-WXX9                   | [d478080e54](https://linux-hardware.org/?probe=d478080e54) | Apr 09, 2023 |
| HP            | Laptop 14-dk1xxx            | [5d39494c01](https://linux-hardware.org/?probe=5d39494c01) | Apr 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [1a6e63f6b2](https://linux-hardware.org/?probe=1a6e63f6b2) | Apr 08, 2023 |
| HUAWEI        | KLVL-WXX9                   | [441d7f391e](https://linux-hardware.org/?probe=441d7f391e) | Apr 08, 2023 |
| Notebook      | NP5x_NP6x_NP7xRNJ_RNH       | [29f00590fb](https://linux-hardware.org/?probe=29f00590fb) | Apr 05, 2023 |
| Compumax C... | ONIX-CEL-0001               | [b3e9bc2fb0](https://linux-hardware.org/?probe=b3e9bc2fb0) | Apr 04, 2023 |
| Apple         | MacBookAir5,2               | [cb94d3ff68](https://linux-hardware.org/?probe=cb94d3ff68) | Apr 04, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [9f33f20fc4](https://linux-hardware.org/?probe=9f33f20fc4) | Apr 04, 2023 |
| PCSMART S.... | PNTGOB11CPE                 | [874d355cc4](https://linux-hardware.org/?probe=874d355cc4) | Apr 02, 2023 |
| Toshiba       | Satellite L45-B             | [6d4878cdbf](https://linux-hardware.org/?probe=6d4878cdbf) | Apr 01, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [03da618edb](https://linux-hardware.org/?probe=03da618edb) | Mar 31, 2023 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [1dc323a9e9](https://linux-hardware.org/?probe=1dc323a9e9) | Mar 30, 2023 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | [117d507724](https://linux-hardware.org/?probe=117d507724) | Mar 24, 2023 |
| Lenovo        | IdeaPad Yoga 13 20175       | [56d564423e](https://linux-hardware.org/?probe=56d564423e) | Mar 24, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [e14a63a1e4](https://linux-hardware.org/?probe=e14a63a1e4) | Mar 24, 2023 |
| Apple         | MacBookPro12,1              | [c6f835ae33](https://linux-hardware.org/?probe=c6f835ae33) | Mar 16, 2023 |
| Toshiba       | Satellite L735              | [0c5b1ebe0a](https://linux-hardware.org/?probe=0c5b1ebe0a) | Mar 11, 2023 |
| Toshiba       | Satellite L735              | [5371ec61c1](https://linux-hardware.org/?probe=5371ec61c1) | Mar 11, 2023 |
| Apple         | MacBookPro11,3              | [bccc889328](https://linux-hardware.org/?probe=bccc889328) | Mar 10, 2023 |
| Lenovo        | ThinkPad X201 36806V4       | [1921dc6d6b](https://linux-hardware.org/?probe=1921dc6d6b) | Mar 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [4cb7f38354](https://linux-hardware.org/?probe=4cb7f38354) | Mar 05, 2023 |
| HP            | G42                         | [7dee433139](https://linux-hardware.org/?probe=7dee433139) | Mar 05, 2023 |
| Apple         | MacBookPro5,5               | [e20478d60e](https://linux-hardware.org/?probe=e20478d60e) | Feb 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [39f48414bc](https://linux-hardware.org/?probe=39f48414bc) | Feb 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [cc447f6c07](https://linux-hardware.org/?probe=cc447f6c07) | Feb 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [66c33604c4](https://linux-hardware.org/?probe=66c33604c4) | Feb 17, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | [4e0e31fd72](https://linux-hardware.org/?probe=4e0e31fd72) | Feb 17, 2023 |
| Lenovo        | IdeaPad Z585 20152          | [e03f8ffaf1](https://linux-hardware.org/?probe=e03f8ffaf1) | Feb 17, 2023 |
| Lenovo        | IdeaPad Z585 20152          | [bc95a7befb](https://linux-hardware.org/?probe=bc95a7befb) | Feb 15, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | [28db1ad82e](https://linux-hardware.org/?probe=28db1ad82e) | Feb 14, 2023 |
| Dell          | Latitude 3410               | [7ccc73c7bf](https://linux-hardware.org/?probe=7ccc73c7bf) | Feb 13, 2023 |
| Dell          | Latitude 3410               | [374ddffec8](https://linux-hardware.org/?probe=374ddffec8) | Feb 13, 2023 |
| Dell          | Inspiron 1420               | [77c6839e06](https://linux-hardware.org/?probe=77c6839e06) | Feb 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [3c8717baf4](https://linux-hardware.org/?probe=3c8717baf4) | Feb 12, 2023 |
| ASUSTek       | X455YA                      | [ba987663d8](https://linux-hardware.org/?probe=ba987663d8) | Feb 09, 2023 |
| HP            | 450                         | [26d3505372](https://linux-hardware.org/?probe=26d3505372) | Feb 06, 2023 |
| HP            | Pavilion 10 TS              | [522345a482](https://linux-hardware.org/?probe=522345a482) | Feb 05, 2023 |
| PCsmart       | PCSGOB14p-C                 | [9cf7aff807](https://linux-hardware.org/?probe=9cf7aff807) | Feb 05, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [42d855f568](https://linux-hardware.org/?probe=42d855f568) | Feb 04, 2023 |
| HP            | 240 G8 Notebook PC          | [00a3607d18](https://linux-hardware.org/?probe=00a3607d18) | Jan 30, 2023 |
| HP            | Pavilion dv6                | [ce950f0a28](https://linux-hardware.org/?probe=ce950f0a28) | Jan 28, 2023 |
| Acer          | Aspire V5-431               | [abf4a51513](https://linux-hardware.org/?probe=abf4a51513) | Jan 24, 2023 |
| Acer          | Aspire V5-431               | [3da8ac521c](https://linux-hardware.org/?probe=3da8ac521c) | Jan 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [364a07a435](https://linux-hardware.org/?probe=364a07a435) | Jan 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [546a896e7f](https://linux-hardware.org/?probe=546a896e7f) | Jan 22, 2023 |
| Lenovo        | IdeaPad Z400 20201          | [9e49dc44eb](https://linux-hardware.org/?probe=9e49dc44eb) | Jan 21, 2023 |
| Dell          | Inspiron 3442               | [bb63f70764](https://linux-hardware.org/?probe=bb63f70764) | Jan 21, 2023 |
| Dell          | Inspiron 3442               | [5973a7db86](https://linux-hardware.org/?probe=5973a7db86) | Jan 21, 2023 |
| HP            | 1000                        | [62ee01ee38](https://linux-hardware.org/?probe=62ee01ee38) | Jan 20, 2023 |
| Toshiba       | QOSMIO X505                 | [8b6dfa9517](https://linux-hardware.org/?probe=8b6dfa9517) | Jan 18, 2023 |
| Acer          | Nitro AN515-54              | [4a997fa99d](https://linux-hardware.org/?probe=4a997fa99d) | Jan 17, 2023 |
| Lenovo        | G450 2949                   | [f9141ba069](https://linux-hardware.org/?probe=f9141ba069) | Jan 17, 2023 |
| Lenovo        | G450 2949                   | [923765c4aa](https://linux-hardware.org/?probe=923765c4aa) | Jan 17, 2023 |
| Dell          | Vostro 3405                 | [b769a91b4f](https://linux-hardware.org/?probe=b769a91b4f) | Jan 17, 2023 |
| ASUSTek       | ZenBook UX434FAC_UX434FA    | [0ece2f508b](https://linux-hardware.org/?probe=0ece2f508b) | Jan 14, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [b6c21b8d35](https://linux-hardware.org/?probe=b6c21b8d35) | Jan 14, 2023 |
| Dell          | Inspiron 11 - 3147          | [7193100d05](https://linux-hardware.org/?probe=7193100d05) | Jan 14, 2023 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [923d70951e](https://linux-hardware.org/?probe=923d70951e) | Jan 14, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [e275cc7891](https://linux-hardware.org/?probe=e275cc7891) | Jan 13, 2023 |
| HP            | Laptop 15-gw0xxx            | [d534567752](https://linux-hardware.org/?probe=d534567752) | Jan 12, 2023 |
| Lenovo        | ThinkPad T430 2349MPS       | [c04ba99a13](https://linux-hardware.org/?probe=c04ba99a13) | Jan 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [3b767cfcef](https://linux-hardware.org/?probe=3b767cfcef) | Jan 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [ac7ae437c8](https://linux-hardware.org/?probe=ac7ae437c8) | Jan 10, 2023 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [7e32892067](https://linux-hardware.org/?probe=7e32892067) | Jan 09, 2023 |
| Dell          | System XPS L502X            | [7d053f0ab1](https://linux-hardware.org/?probe=7d053f0ab1) | Jan 09, 2023 |
| HP            | Pavilion dv2000 (RX554LA... | [2f9ff5256a](https://linux-hardware.org/?probe=2f9ff5256a) | Jan 08, 2023 |
| HP            | Pavilion dv2000 (RX554LA... | [b952438f2c](https://linux-hardware.org/?probe=b952438f2c) | Jan 08, 2023 |
| Dell          | Inspiron N4010              | [5f1d6f0533](https://linux-hardware.org/?probe=5f1d6f0533) | Jan 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [dc2a0809aa](https://linux-hardware.org/?probe=dc2a0809aa) | Jan 07, 2023 |
| Acer          | Aspire 4750                 | [f871c26332](https://linux-hardware.org/?probe=f871c26332) | Jan 01, 2023 |
| Acer          | Nitro AN515-55              | [79f628b951](https://linux-hardware.org/?probe=79f628b951) | Dec 29, 2022 |
| HP            | ProBook 430 G1              | [217bb0ea0f](https://linux-hardware.org/?probe=217bb0ea0f) | Dec 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [b30bf77d27](https://linux-hardware.org/?probe=b30bf77d27) | Dec 19, 2022 |
| HP            | 2000                        | [bcbeb17a60](https://linux-hardware.org/?probe=bcbeb17a60) | Dec 15, 2022 |
| HP            | Laptop 14-fq1xxx            | [2da9ae7906](https://linux-hardware.org/?probe=2da9ae7906) | Dec 14, 2022 |
| HP            | Laptop 14-fq1xxx            | [ed92313ebc](https://linux-hardware.org/?probe=ed92313ebc) | Dec 13, 2022 |
| Notebook      | NL40_50ZU                   | [8e0e4867f8](https://linux-hardware.org/?probe=8e0e4867f8) | Dec 13, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | [660fe07867](https://linux-hardware.org/?probe=660fe07867) | Dec 07, 2022 |
| HP            | Laptop 14-cm1xxx            | [6fbbd3608f](https://linux-hardware.org/?probe=6fbbd3608f) | Dec 06, 2022 |
| HP            | Laptop 14-fq1xxx            | [4f93d8895e](https://linux-hardware.org/?probe=4f93d8895e) | Dec 06, 2022 |
| HP            | 245 G7                      | [57ed16df1f](https://linux-hardware.org/?probe=57ed16df1f) | Dec 05, 2022 |
| HP            | ProBook 6450b               | [f602f6c0bc](https://linux-hardware.org/?probe=f602f6c0bc) | Dec 05, 2022 |
| HP            | ProBook 6450b               | [de39c86a4c](https://linux-hardware.org/?probe=de39c86a4c) | Dec 05, 2022 |
| HUAWEI        | WRTD-WXX9                   | [9b0de50c65](https://linux-hardware.org/?probe=9b0de50c65) | Dec 04, 2022 |
| Lenovo        | IdeaPad U400 09932JU        | [cb5d9871d0](https://linux-hardware.org/?probe=cb5d9871d0) | Nov 22, 2022 |
| ASUSTek       | X442UA                      | [781e1c13ac](https://linux-hardware.org/?probe=781e1c13ac) | Nov 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [b3473a1862](https://linux-hardware.org/?probe=b3473a1862) | Nov 13, 2022 |
| Acer          | Aspire E5-571               | [4577f6db37](https://linux-hardware.org/?probe=4577f6db37) | Nov 10, 2022 |
| ASUSTek       | T100TA                      | [962ca3ceb5](https://linux-hardware.org/?probe=962ca3ceb5) | Nov 06, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | [2d78dbce09](https://linux-hardware.org/?probe=2d78dbce09) | Nov 03, 2022 |
| HP            | G72                         | [08a732911d](https://linux-hardware.org/?probe=08a732911d) | Oct 31, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | [150c8ac0ac](https://linux-hardware.org/?probe=150c8ac0ac) | Oct 30, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [7daabab955](https://linux-hardware.org/?probe=7daabab955) | Oct 27, 2022 |
| ASUSTek       | T100TA                      | [947259d1f6](https://linux-hardware.org/?probe=947259d1f6) | Oct 26, 2022 |
| HP            | ProBook 430 G3              | [1ca42d6148](https://linux-hardware.org/?probe=1ca42d6148) | Oct 21, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [aca44a3eab](https://linux-hardware.org/?probe=aca44a3eab) | Oct 20, 2022 |
| HP            | 245 G7                      | [9ec088c343](https://linux-hardware.org/?probe=9ec088c343) | Oct 19, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [ff6d42a3ef](https://linux-hardware.org/?probe=ff6d42a3ef) | Oct 17, 2022 |
| HP            | Laptop 15-ef2xxx            | [d8372069b0](https://linux-hardware.org/?probe=d8372069b0) | Oct 16, 2022 |
| Dell          | Inspiron N4010              | [742bc1f2eb](https://linux-hardware.org/?probe=742bc1f2eb) | Oct 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [a318dbfcc9](https://linux-hardware.org/?probe=a318dbfcc9) | Oct 15, 2022 |
| HP            | Pavilion dv6000 (RG266UA... | [1601ca9a83](https://linux-hardware.org/?probe=1601ca9a83) | Oct 14, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | [f785339c71](https://linux-hardware.org/?probe=f785339c71) | Oct 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [4ca8fc6d34](https://linux-hardware.org/?probe=4ca8fc6d34) | Oct 11, 2022 |
| HP            | Pavilion g4                 | [19fe60b14c](https://linux-hardware.org/?probe=19fe60b14c) | Oct 07, 2022 |
| Lanix         | Neuron V                    | [6bd3c14cc9](https://linux-hardware.org/?probe=6bd3c14cc9) | Oct 03, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [45557ec6e6](https://linux-hardware.org/?probe=45557ec6e6) | Oct 03, 2022 |
| HP            | 245 G7 Notebook PC          | [7b92fcd976](https://linux-hardware.org/?probe=7b92fcd976) | Oct 02, 2022 |
| HP            | 245 G7 Notebook PC          | [de8eb62c07](https://linux-hardware.org/?probe=de8eb62c07) | Oct 02, 2022 |
| HP            | EliteBook 840 G3            | [ddf1904011](https://linux-hardware.org/?probe=ddf1904011) | Oct 01, 2022 |
| HP            | Pavilion 10 TS              | [28003748e6](https://linux-hardware.org/?probe=28003748e6) | Sep 27, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [56e06deea2](https://linux-hardware.org/?probe=56e06deea2) | Sep 26, 2022 |
| HP            | Pavilion 10 TS              | [1186e5b5d8](https://linux-hardware.org/?probe=1186e5b5d8) | Sep 23, 2022 |
| Dell          | XPS 15 9550                 | [acf36b1555](https://linux-hardware.org/?probe=acf36b1555) | Sep 20, 2022 |
| Acer          | Aspire V3-471               | [b04cc2ea05](https://linux-hardware.org/?probe=b04cc2ea05) | Sep 20, 2022 |
| ASUSTek       | X455LAB                     | [4a71131e80](https://linux-hardware.org/?probe=4a71131e80) | Sep 19, 2022 |
| ASUSTek       | X455LAB                     | [f7c5412964](https://linux-hardware.org/?probe=f7c5412964) | Sep 19, 2022 |
| ASUSTek       | X441NA                      | [282f984233](https://linux-hardware.org/?probe=282f984233) | Sep 19, 2022 |
| Dell          | Latitude E5420              | [7416dc3fb1](https://linux-hardware.org/?probe=7416dc3fb1) | Sep 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [a26e1ad502](https://linux-hardware.org/?probe=a26e1ad502) | Sep 15, 2022 |
| HP            | 240 G7 Notebook PC          | [09f7be676c](https://linux-hardware.org/?probe=09f7be676c) | Sep 15, 2022 |
| ASUSTek       | X405UA                      | [3b098addea](https://linux-hardware.org/?probe=3b098addea) | Sep 14, 2022 |
| MSI           | PS63 Modern 8RD             | [8fa2ea42ed](https://linux-hardware.org/?probe=8fa2ea42ed) | Sep 14, 2022 |
| HP            | Notebook                    | [2984aef090](https://linux-hardware.org/?probe=2984aef090) | Sep 11, 2022 |
| Dell          | Precision 3510              | [4337a8e018](https://linux-hardware.org/?probe=4337a8e018) | Sep 11, 2022 |
| Acer          | Aspire V3-472P              | [632117c524](https://linux-hardware.org/?probe=632117c524) | Sep 10, 2022 |
| Toshiba       | Satellite L635              | [6d0bbfb576](https://linux-hardware.org/?probe=6d0bbfb576) | Sep 07, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [cc43cdda9a](https://linux-hardware.org/?probe=cc43cdda9a) | Sep 04, 2022 |
| ASUSTek       | X455LJ                      | [b635e1c2ba](https://linux-hardware.org/?probe=b635e1c2ba) | Sep 01, 2022 |
| HP            | Laptop 14-fq1xxx            | [8ea91d6b4b](https://linux-hardware.org/?probe=8ea91d6b4b) | Aug 30, 2022 |
| Compumax C... | ONIX-CEL-0001               | [272ca2c7b7](https://linux-hardware.org/?probe=272ca2c7b7) | Aug 27, 2022 |
| ASUSTek       | X455LD                      | [5351e31366](https://linux-hardware.org/?probe=5351e31366) | Aug 26, 2022 |
| HP            | ENVY 15                     | [db06c354d4](https://linux-hardware.org/?probe=db06c354d4) | Aug 26, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [5028378988](https://linux-hardware.org/?probe=5028378988) | Aug 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [d64f8a64fa](https://linux-hardware.org/?probe=d64f8a64fa) | Aug 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [bb928725a6](https://linux-hardware.org/?probe=bb928725a6) | Aug 23, 2022 |
| Dell          | XPS 15 9550                 | [8ab7fcb6ff](https://linux-hardware.org/?probe=8ab7fcb6ff) | Aug 21, 2022 |
| HP            | 240 G7 Notebook PC          | [24849a5c23](https://linux-hardware.org/?probe=24849a5c23) | Aug 15, 2022 |
| ASUSTek       | X550DP                      | [ce42b65252](https://linux-hardware.org/?probe=ce42b65252) | Aug 13, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [298cf4b527](https://linux-hardware.org/?probe=298cf4b527) | Aug 13, 2022 |
| HP            | 240 G7 Notebook PC          | [9321e2df1a](https://linux-hardware.org/?probe=9321e2df1a) | Aug 13, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | [e71b330285](https://linux-hardware.org/?probe=e71b330285) | Aug 13, 2022 |
| ASUSTek       | X455LJ                      | [f90572b8e2](https://linux-hardware.org/?probe=f90572b8e2) | Aug 11, 2022 |
| HUAWEI        | BOHB-WAX9                   | [fcc8ebfb00](https://linux-hardware.org/?probe=fcc8ebfb00) | Aug 04, 2022 |
| HUAWEI        | BOHB-WAX9                   | [6d65ac3351](https://linux-hardware.org/?probe=6d65ac3351) | Aug 02, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X51... | [bdc243bf9f](https://linux-hardware.org/?probe=bdc243bf9f) | Jul 31, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X51... | [41a0eba80f](https://linux-hardware.org/?probe=41a0eba80f) | Jul 31, 2022 |
| Sony          | VPCEG33FL                   | [6d371d6c32](https://linux-hardware.org/?probe=6d371d6c32) | Jul 31, 2022 |
| HP            | 245 G6                      | [ae4b0ce17e](https://linux-hardware.org/?probe=ae4b0ce17e) | Jul 28, 2022 |
| Sony          | VPCEG33FL                   | [886dfc7777](https://linux-hardware.org/?probe=886dfc7777) | Jul 27, 2022 |
| HUAWEI        | HVY-WXX9                    | [c2fc2235eb](https://linux-hardware.org/?probe=c2fc2235eb) | Jul 27, 2022 |
| HUAWEI        | HVY-WXX9                    | [f18835e5a1](https://linux-hardware.org/?probe=f18835e5a1) | Jul 27, 2022 |
| Lenovo        | G410 20237                  | [c23a040e55](https://linux-hardware.org/?probe=c23a040e55) | Jul 25, 2022 |
| Sony          | VPCEG33FL                   | [8767e87e9e](https://linux-hardware.org/?probe=8767e87e9e) | Jul 24, 2022 |
| ASUSTek       | X455LJ                      | [49af56cbe0](https://linux-hardware.org/?probe=49af56cbe0) | Jul 24, 2022 |
| HP            | Victus by Laptop 16-d0xx... | [acdc35979c](https://linux-hardware.org/?probe=acdc35979c) | Jul 23, 2022 |
| ASUSTek       | N53SV                       | [635f096b70](https://linux-hardware.org/?probe=635f096b70) | Jul 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [9863a7ed67](https://linux-hardware.org/?probe=9863a7ed67) | Jul 20, 2022 |
| Unknown       | Unknown                     | [12ef7e83a2](https://linux-hardware.org/?probe=12ef7e83a2) | Jul 20, 2022 |
| Sony          | VPCEH37FJ                   | [1cc39f5c15](https://linux-hardware.org/?probe=1cc39f5c15) | Jul 19, 2022 |
| Toshiba       | Satellite M645              | [0149367a4e](https://linux-hardware.org/?probe=0149367a4e) | Jul 12, 2022 |
| ASUSTek       | N53SV                       | [2af75f4744](https://linux-hardware.org/?probe=2af75f4744) | Jul 12, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | [ebbc4ebc1d](https://linux-hardware.org/?probe=ebbc4ebc1d) | Jul 11, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | [d200cc6f06](https://linux-hardware.org/?probe=d200cc6f06) | Jul 11, 2022 |
| HP            | Laptop 15-dy1xxx            | [36b1a0480d](https://linux-hardware.org/?probe=36b1a0480d) | Jul 10, 2022 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | [c7c8a9031c](https://linux-hardware.org/?probe=c7c8a9031c) | Jul 05, 2022 |
| Dell          | Latitude E7450              | [34913911ca](https://linux-hardware.org/?probe=34913911ca) | Jul 05, 2022 |
| Dell          | Latitude E7450              | [60e633e563](https://linux-hardware.org/?probe=60e633e563) | Jul 04, 2022 |
| Sony          | VPCEH37FJ                   | [509fe56362](https://linux-hardware.org/?probe=509fe56362) | Jul 01, 2022 |
| HP            | Pavilion g4                 | [3626d9afe4](https://linux-hardware.org/?probe=3626d9afe4) | Jul 01, 2022 |
| HP            | ProBook 445 G8 Notebook ... | [35ca7c4868](https://linux-hardware.org/?probe=35ca7c4868) | Jun 30, 2022 |
| Lenovo        | Z40-75 80DW                 | [1fc3b34132](https://linux-hardware.org/?probe=1fc3b34132) | Jun 27, 2022 |
| HP            | ProBook 440 G7              | [3bbbcaea72](https://linux-hardware.org/?probe=3bbbcaea72) | Jun 20, 2022 |
| HUAWEI        | WRTD-WXX9                   | [15d402e40c](https://linux-hardware.org/?probe=15d402e40c) | Jun 18, 2022 |
| HUAWEI        | KLVL-WXX9                   | [a71adbf68f](https://linux-hardware.org/?probe=a71adbf68f) | Jun 18, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | [27d9d9e55e](https://linux-hardware.org/?probe=27d9d9e55e) | Jun 16, 2022 |
| Acer          | AO722                       | [29c2adc56d](https://linux-hardware.org/?probe=29c2adc56d) | Jun 13, 2022 |
| HP            | Laptop 14-cm1xxx            | [269af04437](https://linux-hardware.org/?probe=269af04437) | Jun 13, 2022 |
| Dell          | Vostro 3560                 | [170031499c](https://linux-hardware.org/?probe=170031499c) | Jun 12, 2022 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | [5e7659e141](https://linux-hardware.org/?probe=5e7659e141) | Jun 11, 2022 |
| HP            | Laptop 14-cm1xxx            | [77e3d238c1](https://linux-hardware.org/?probe=77e3d238c1) | Jun 10, 2022 |
| Dell          | Vostro 3560                 | [0664b57ae1](https://linux-hardware.org/?probe=0664b57ae1) | Jun 09, 2022 |
| HP            | ProBook 440 G2              | [47ef7a04b9](https://linux-hardware.org/?probe=47ef7a04b9) | Jun 06, 2022 |
| HP            | Laptop 15-db0xxx            | [e5998cb70e](https://linux-hardware.org/?probe=e5998cb70e) | Jun 05, 2022 |
| Sony          | VGN-CS240T                  | [b25cbd1a6b](https://linux-hardware.org/?probe=b25cbd1a6b) | Jun 03, 2022 |
| Lenovo        | IdeaPad Yoga 13 20175       | [b7e4b7a2ec](https://linux-hardware.org/?probe=b7e4b7a2ec) | Jun 03, 2022 |
| Acer          | AOD260                      | [f5c031faa5](https://linux-hardware.org/?probe=f5c031faa5) | Jun 02, 2022 |
| ASUSTek       | ROG Strix G713IH_G713IH     | [883f055fb1](https://linux-hardware.org/?probe=883f055fb1) | May 30, 2022 |
| ASUSTek       | ROG Strix G713IH_G713IH     | [e475b560cf](https://linux-hardware.org/?probe=e475b560cf) | May 30, 2022 |
| MSI           | GE60 2PE                    | [1e15d749ee](https://linux-hardware.org/?probe=1e15d749ee) | May 30, 2022 |
| Lenovo        | ThinkPad Edge E430 32543... | [dc9d61a80b](https://linux-hardware.org/?probe=dc9d61a80b) | May 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [33de40a2e1](https://linux-hardware.org/?probe=33de40a2e1) | May 29, 2022 |
| MSI           | GE60 2PE                    | [84d5af4ebe](https://linux-hardware.org/?probe=84d5af4ebe) | May 29, 2022 |
| MSI           | GE60 2PE                    | [c8d325a744](https://linux-hardware.org/?probe=c8d325a744) | May 29, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | [159819d677](https://linux-hardware.org/?probe=159819d677) | May 26, 2022 |
| Dell          | Latitude E5410              | [fcb77d9c00](https://linux-hardware.org/?probe=fcb77d9c00) | May 26, 2022 |
| Acer          | Aspire E5-411               | [7c3a3077ff](https://linux-hardware.org/?probe=7c3a3077ff) | May 24, 2022 |
| HP            | Laptop 15-da2xxx            | [7dd1f5b528](https://linux-hardware.org/?probe=7dd1f5b528) | May 23, 2022 |
| HP            | ProBook 450 G1              | [0097404cab](https://linux-hardware.org/?probe=0097404cab) | May 23, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV    | [50a0ed5e81](https://linux-hardware.org/?probe=50a0ed5e81) | May 22, 2022 |
| HP            | Laptop 14-dk1xxx            | [f05080d3fd](https://linux-hardware.org/?probe=f05080d3fd) | May 22, 2022 |
| Toshiba       | Satellite C55-C             | [46f7672c43](https://linux-hardware.org/?probe=46f7672c43) | May 22, 2022 |
| Toshiba       | Satellite C55-C             | [6f6a96c1cb](https://linux-hardware.org/?probe=6f6a96c1cb) | May 22, 2022 |
| Timi          | A35S                        | [8278281113](https://linux-hardware.org/?probe=8278281113) | May 20, 2022 |
| Acer          | Aspire A314-22              | [b476e4fd95](https://linux-hardware.org/?probe=b476e4fd95) | May 20, 2022 |
| Dell          | Inspiron 3459               | [b36df0b4df](https://linux-hardware.org/?probe=b36df0b4df) | May 17, 2022 |
| MSI           | Katana GF76 12UE            | [460e78b93a](https://linux-hardware.org/?probe=460e78b93a) | May 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [f7d3a9220c](https://linux-hardware.org/?probe=f7d3a9220c) | May 13, 2022 |
| Lenovo        | V14-IGL 82C2                | [0d1e1d71ee](https://linux-hardware.org/?probe=0d1e1d71ee) | May 08, 2022 |
| Lenovo        | V14-IGL 82C2                | [3ad9fd00c2](https://linux-hardware.org/?probe=3ad9fd00c2) | May 08, 2022 |
| HP            | Compaq 6530b (WA484LA#AB... | [13cda8fea2](https://linux-hardware.org/?probe=13cda8fea2) | May 08, 2022 |
| ASUSTek       | K53Z                        | [0d68cb4fdd](https://linux-hardware.org/?probe=0d68cb4fdd) | May 04, 2022 |
| Toshiba       | Satellite L735              | [cb523c0933](https://linux-hardware.org/?probe=cb523c0933) | May 02, 2022 |
| Lenovo        | G450 2949                   | [8a97581747](https://linux-hardware.org/?probe=8a97581747) | May 02, 2022 |
| Dell          | Vostro 1510                 | [3b071a4b76](https://linux-hardware.org/?probe=3b071a4b76) | Apr 29, 2022 |
| Dell          | Vostro 1510                 | [483727ec47](https://linux-hardware.org/?probe=483727ec47) | Apr 29, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [8a8d7b120a](https://linux-hardware.org/?probe=8a8d7b120a) | Apr 24, 2022 |
| Acer          | Aspire A515-51              | [9f8f3a2eb5](https://linux-hardware.org/?probe=9f8f3a2eb5) | Apr 23, 2022 |
| Acer          | Aspire A515-51              | [738850499d](https://linux-hardware.org/?probe=738850499d) | Apr 23, 2022 |
| Acer          | Aspire A515-51              | [fd8cacef33](https://linux-hardware.org/?probe=fd8cacef33) | Apr 23, 2022 |
| Lenovo        | Z40-70 20366                | [c77a5735b7](https://linux-hardware.org/?probe=c77a5735b7) | Apr 20, 2022 |
| MSI           | Creator 15 A10SFS           | [42b2140343](https://linux-hardware.org/?probe=42b2140343) | Apr 15, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [1877553731](https://linux-hardware.org/?probe=1877553731) | Apr 15, 2022 |
| HP            | ProBook 4430s               | [79e30d321b](https://linux-hardware.org/?probe=79e30d321b) | Apr 15, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | [4a159b7cd8](https://linux-hardware.org/?probe=4a159b7cd8) | Apr 14, 2022 |
| Acer          | Aspire 4740                 | [d401412daa](https://linux-hardware.org/?probe=d401412daa) | Apr 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [ab7173f335](https://linux-hardware.org/?probe=ab7173f335) | Apr 10, 2022 |
| Lenovo        | ThinkPad X220 4291AN3       | [848b7902d8](https://linux-hardware.org/?probe=848b7902d8) | Apr 10, 2022 |
| ASUSTek       | X541SA                      | [1d7a301fe2](https://linux-hardware.org/?probe=1d7a301fe2) | Apr 08, 2022 |
| Toshiba       | Satellite L735              | [b7873249a4](https://linux-hardware.org/?probe=b7873249a4) | Apr 07, 2022 |
| Toshiba       | Satellite P755              | [b3601d9299](https://linux-hardware.org/?probe=b3601d9299) | Apr 05, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [38036fe92b](https://linux-hardware.org/?probe=38036fe92b) | Apr 05, 2022 |
| HP            | ProBook 430 G3              | [8623b2ac51](https://linux-hardware.org/?probe=8623b2ac51) | Mar 30, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [0e93a8600c](https://linux-hardware.org/?probe=0e93a8600c) | Mar 27, 2022 |
| Dell          | Vostro 1500                 | [dc0e34cb10](https://linux-hardware.org/?probe=dc0e34cb10) | Mar 26, 2022 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [5b371c14a6](https://linux-hardware.org/?probe=5b371c14a6) | Mar 25, 2022 |
| Acer          | Aspire 3690                 | [76139c48e8](https://linux-hardware.org/?probe=76139c48e8) | Mar 25, 2022 |
| Acer          | Aspire 4738                 | [c809b67c9e](https://linux-hardware.org/?probe=c809b67c9e) | Mar 23, 2022 |
| HP            | Pavilion 10 TS              | [e149d7ed93](https://linux-hardware.org/?probe=e149d7ed93) | Mar 23, 2022 |
| Dell          | Latitude E5420              | [b15d85a6e9](https://linux-hardware.org/?probe=b15d85a6e9) | Mar 22, 2022 |
| Toshiba       | Satellite P755              | [f8d12d8ab9](https://linux-hardware.org/?probe=f8d12d8ab9) | Mar 22, 2022 |
| HP            | 550                         | [91f443bb06](https://linux-hardware.org/?probe=91f443bb06) | Mar 18, 2022 |
| HP            | 550                         | [8acaec9ff1](https://linux-hardware.org/?probe=8acaec9ff1) | Mar 18, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [8c94df31c1](https://linux-hardware.org/?probe=8c94df31c1) | Mar 16, 2022 |
| Lenovo        | N22 80S6                    | [279ca719c8](https://linux-hardware.org/?probe=279ca719c8) | Mar 16, 2022 |
| HP            | Laptop 15-da0xxx            | [51409532cc](https://linux-hardware.org/?probe=51409532cc) | Mar 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [1b91ffaa87](https://linux-hardware.org/?probe=1b91ffaa87) | Mar 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [21dfbc138d](https://linux-hardware.org/?probe=21dfbc138d) | Mar 13, 2022 |
| Lenovo        | ThinkPad T430 2347AF3       | [8fa4355200](https://linux-hardware.org/?probe=8fa4355200) | Mar 08, 2022 |
| MSI           | Alpha 17 B5EEK              | [3298d34369](https://linux-hardware.org/?probe=3298d34369) | Mar 07, 2022 |
| Lenovo        | ThinkPad X201 3680DQ1       | [b1a7b4593a](https://linux-hardware.org/?probe=b1a7b4593a) | Mar 07, 2022 |
| MSI           | Alpha 17 B5EEK              | [1e54d4f165](https://linux-hardware.org/?probe=1e54d4f165) | Mar 06, 2022 |
| Lenovo        | ThinkPad X201 3680DQ1       | [f10cf42ebf](https://linux-hardware.org/?probe=f10cf42ebf) | Mar 06, 2022 |
| Apple         | MacBookAir3,1               | [b887ed3aa2](https://linux-hardware.org/?probe=b887ed3aa2) | Mar 06, 2022 |
| Apple         | MacBookAir3,1               | [07cade8a02](https://linux-hardware.org/?probe=07cade8a02) | Mar 06, 2022 |
| HP            | 245 G3                      | [879094e00f](https://linux-hardware.org/?probe=879094e00f) | Mar 02, 2022 |
| ASUSTek       | K43E                        | [484fd9a41a](https://linux-hardware.org/?probe=484fd9a41a) | Feb 27, 2022 |
| Dell          | Latitude 5179               | [b28766add3](https://linux-hardware.org/?probe=b28766add3) | Feb 18, 2022 |
| Lenovo        | ThinkPad X240 20AMA4V500    | [e6a94741de](https://linux-hardware.org/?probe=e6a94741de) | Feb 17, 2022 |
| Acer          | Swift SF314-56              | [a6c7102b14](https://linux-hardware.org/?probe=a6c7102b14) | Feb 14, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [e783775e08](https://linux-hardware.org/?probe=e783775e08) | Feb 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [8bcb36b8c7](https://linux-hardware.org/?probe=8bcb36b8c7) | Feb 09, 2022 |
| ASUSTek       | UX305FA                     | [ce2c94c97c](https://linux-hardware.org/?probe=ce2c94c97c) | Feb 07, 2022 |
| Sony          | VGN-FW170J                  | [edead40b0d](https://linux-hardware.org/?probe=edead40b0d) | Feb 07, 2022 |
| Framework     | Laptop                      | [55d5b56564](https://linux-hardware.org/?probe=55d5b56564) | Feb 07, 2022 |
| HP            | ProBook 440 G5              | [5f6a923aa2](https://linux-hardware.org/?probe=5f6a923aa2) | Feb 05, 2022 |
| HP            | ProBook 440 G5              | [6ff30e8299](https://linux-hardware.org/?probe=6ff30e8299) | Feb 05, 2022 |
| HP            | 240 G7                      | [48bc3b139b](https://linux-hardware.org/?probe=48bc3b139b) | Feb 03, 2022 |
| Lenovo        | ThinkPad X240 20AMA2AN00    | [3d321c7afd](https://linux-hardware.org/?probe=3d321c7afd) | Jan 28, 2022 |
| Lenovo        | ThinkPad X240 20AMA2AN00    | [dd9909e9f4](https://linux-hardware.org/?probe=dd9909e9f4) | Jan 28, 2022 |
| MSI           | GF75 Thin 10SER             | [2e94cc2b4c](https://linux-hardware.org/?probe=2e94cc2b4c) | Jan 22, 2022 |
| MSI           | GE72 2QE                    | [cbd609290e](https://linux-hardware.org/?probe=cbd609290e) | Jan 21, 2022 |
| MSI           | GE72 2QE                    | [72843af2fc](https://linux-hardware.org/?probe=72843af2fc) | Jan 14, 2022 |
| Acer          | Aspire V5-121               | [fb3b510c66](https://linux-hardware.org/?probe=fb3b510c66) | Jan 06, 2022 |
| Acer          | Aspire V5-121               | [be57155d1f](https://linux-hardware.org/?probe=be57155d1f) | Jan 06, 2022 |
| HP            | ProBook 450 G1              | [3a0d2d3754](https://linux-hardware.org/?probe=3a0d2d3754) | Jan 05, 2022 |
| HP            | ProBook 450 G1              | [4516e6113b](https://linux-hardware.org/?probe=4516e6113b) | Jan 05, 2022 |
| MSI           | PS63 Modern 8RD             | [1cd435c54f](https://linux-hardware.org/?probe=1cd435c54f) | Jan 04, 2022 |
| Dell          | XPS 13 7390                 | [36a412db42](https://linux-hardware.org/?probe=36a412db42) | Dec 29, 2021 |
| Acer          | Nitro AN515-44              | [8fba60c1a8](https://linux-hardware.org/?probe=8fba60c1a8) | Dec 28, 2021 |
| Lenovo        | Legion 5 17ARH05H 82GN      | [9e022a2288](https://linux-hardware.org/?probe=9e022a2288) | Dec 26, 2021 |
| Lenovo        | Legion 5 17ARH05H 82GN      | [8ff8fb5efd](https://linux-hardware.org/?probe=8ff8fb5efd) | Dec 26, 2021 |
| ASUSTek       | ZenBook UX325JA_UX325JA     | [c9cffe7310](https://linux-hardware.org/?probe=c9cffe7310) | Dec 24, 2021 |
| HP            | Laptop 15-da0xxx            | [2b3ad3643a](https://linux-hardware.org/?probe=2b3ad3643a) | Dec 14, 2021 |
| HUAWEI        | BOHB-WAX9                   | [b3f7681477](https://linux-hardware.org/?probe=b3f7681477) | Dec 06, 2021 |
| HP            | ProBook 6450b               | [df1987d444](https://linux-hardware.org/?probe=df1987d444) | Dec 04, 2021 |
| HP            | 14                          | [d7cb66a845](https://linux-hardware.org/?probe=d7cb66a845) | Nov 28, 2021 |
| Dell          | Vostro 3400                 | [d8946eaf3c](https://linux-hardware.org/?probe=d8946eaf3c) | Nov 28, 2021 |
| Lenovo        | G40-45 80E1                 | [b3cdb202fc](https://linux-hardware.org/?probe=b3cdb202fc) | Nov 28, 2021 |
| ASUSTek       | X455LJ                      | [018d5bcbac](https://linux-hardware.org/?probe=018d5bcbac) | Nov 27, 2021 |
| HP            | Compaq CQ45                 | [7d66f3183b](https://linux-hardware.org/?probe=7d66f3183b) | Nov 24, 2021 |
| HP            | ProBook 440 G1              | [6159b4aa5a](https://linux-hardware.org/?probe=6159b4aa5a) | Nov 20, 2021 |
| HP            | ProBook 440 G1              | [42d0889355](https://linux-hardware.org/?probe=42d0889355) | Nov 20, 2021 |
| ASUSTek       | X441NA                      | [da21de67fb](https://linux-hardware.org/?probe=da21de67fb) | Nov 18, 2021 |
| HP            | Pavilion dv9700             | [2d4636d0ee](https://linux-hardware.org/?probe=2d4636d0ee) | Nov 17, 2021 |
| HP            | Pavilion dv9700             | [e5da3884b4](https://linux-hardware.org/?probe=e5da3884b4) | Nov 17, 2021 |
| ASUSTek       | X550ZE                      | [b98c646c47](https://linux-hardware.org/?probe=b98c646c47) | Nov 16, 2021 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [18152a84af](https://linux-hardware.org/?probe=18152a84af) | Nov 13, 2021 |
| Lenovo        | ThinkPad T495 20NKS0QN0V    | [ceab02dda1](https://linux-hardware.org/?probe=ceab02dda1) | Nov 07, 2021 |
| Dell          | Latitude 7490               | [43eeb8d632](https://linux-hardware.org/?probe=43eeb8d632) | Nov 06, 2021 |
| Dell          | Latitude 7490               | [209cc4c51e](https://linux-hardware.org/?probe=209cc4c51e) | Nov 06, 2021 |
| HP            | Pavilion dv4                | [7e9733638c](https://linux-hardware.org/?probe=7e9733638c) | Nov 04, 2021 |
| ASUSTek       | X550ZE                      | [dcd63f8987](https://linux-hardware.org/?probe=dcd63f8987) | Oct 31, 2021 |
| Dell          | Inspiron 5515               | [809fe8da11](https://linux-hardware.org/?probe=809fe8da11) | Oct 30, 2021 |
| Acer          | Nitro AN515-52              | [7f70de1771](https://linux-hardware.org/?probe=7f70de1771) | Oct 26, 2021 |
| Acer          | Nitro AN515-52              | [6777af6e6a](https://linux-hardware.org/?probe=6777af6e6a) | Oct 26, 2021 |
| Lenovo        | G40-45 80E1                 | [61b1e7901a](https://linux-hardware.org/?probe=61b1e7901a) | Oct 17, 2021 |
| Acer          | Aspire E1-522               | [dc7a02c862](https://linux-hardware.org/?probe=dc7a02c862) | Oct 15, 2021 |
| HP            | 240 G3                      | [a083502110](https://linux-hardware.org/?probe=a083502110) | Oct 11, 2021 |
| HP            | 240 G3                      | [1772f88ed6](https://linux-hardware.org/?probe=1772f88ed6) | Oct 11, 2021 |
| Toshiba       | Satellite C45-A             | [ee28fa6dfb](https://linux-hardware.org/?probe=ee28fa6dfb) | Oct 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [b2a9183e6d](https://linux-hardware.org/?probe=b2a9183e6d) | Oct 09, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [330659159b](https://linux-hardware.org/?probe=330659159b) | Oct 07, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [14d286f67e](https://linux-hardware.org/?probe=14d286f67e) | Oct 07, 2021 |
| Acer          | Aspire E3-111               | [45a0e8618a](https://linux-hardware.org/?probe=45a0e8618a) | Sep 28, 2021 |
| Acer          | Aspire E3-111               | [f0100402ec](https://linux-hardware.org/?probe=f0100402ec) | Sep 28, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [a451fc441b](https://linux-hardware.org/?probe=a451fc441b) | Sep 27, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [643c70dec0](https://linux-hardware.org/?probe=643c70dec0) | Sep 27, 2021 |
| ASUSTek       | K53SD                       | [0f6a772a44](https://linux-hardware.org/?probe=0f6a772a44) | Sep 25, 2021 |
| Dell          | XPS 15 9550                 | [6e9f3c8012](https://linux-hardware.org/?probe=6e9f3c8012) | Sep 22, 2021 |
| HP            | ProBook 450 G1              | [e6fbfad3de](https://linux-hardware.org/?probe=e6fbfad3de) | Sep 16, 2021 |
| Gateway       | NV47H                       | [8cef362c2e](https://linux-hardware.org/?probe=8cef362c2e) | Sep 15, 2021 |
| Gateway       | NV47H                       | [0ad04889c5](https://linux-hardware.org/?probe=0ad04889c5) | Sep 15, 2021 |
| Dell          | Latitude E7270              | [479b6d4aa9](https://linux-hardware.org/?probe=479b6d4aa9) | Sep 14, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [2300be2f19](https://linux-hardware.org/?probe=2300be2f19) | Sep 13, 2021 |
| HP            | 2000                        | [7d8cd719a2](https://linux-hardware.org/?probe=7d8cd719a2) | Sep 09, 2021 |
| Dell          | Inspiron 1110               | [890d9d9d24](https://linux-hardware.org/?probe=890d9d9d24) | Sep 08, 2021 |
| Dell          | Inspiron 1110               | [e299761316](https://linux-hardware.org/?probe=e299761316) | Sep 08, 2021 |
| ASUSTek       | X555QA                      | [043083e9e8](https://linux-hardware.org/?probe=043083e9e8) | Sep 04, 2021 |
| ASUSTek       | X555QG                      | [badf1b0736](https://linux-hardware.org/?probe=badf1b0736) | Aug 30, 2021 |
| Unknown       | Unknown                     | [33a8107059](https://linux-hardware.org/?probe=33a8107059) | Aug 28, 2021 |
| Unknown       | Unknown                     | [fe2ba9da7c](https://linux-hardware.org/?probe=fe2ba9da7c) | Aug 28, 2021 |
| HP            | EliteBook 840 G6            | [08c766b957](https://linux-hardware.org/?probe=08c766b957) | Aug 26, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [7e6a9f0430](https://linux-hardware.org/?probe=7e6a9f0430) | Aug 25, 2021 |
| HP            | 14                          | [6d84790759](https://linux-hardware.org/?probe=6d84790759) | Aug 23, 2021 |
| Fujitsu Si... | AMILO PRO V3515             | [e7f145f52b](https://linux-hardware.org/?probe=e7f145f52b) | Aug 21, 2021 |
| Apple         | MacBook4,1                  | [ad6e3e064f](https://linux-hardware.org/?probe=ad6e3e064f) | Aug 21, 2021 |
| Apple         | MacBook4,1                  | [9a5653e44d](https://linux-hardware.org/?probe=9a5653e44d) | Aug 21, 2021 |
| Timi          | A35S                        | [1f0e95ee1d](https://linux-hardware.org/?probe=1f0e95ee1d) | Aug 17, 2021 |
| ASUSTek       | X441SA                      | [f23d4d50be](https://linux-hardware.org/?probe=f23d4d50be) | Aug 16, 2021 |
| ASUSTek       | K53SD                       | [865c697e6a](https://linux-hardware.org/?probe=865c697e6a) | Aug 13, 2021 |
| Dell          | Precision 3551              | [da8459ac73](https://linux-hardware.org/?probe=da8459ac73) | Aug 10, 2021 |
| Dell          | Precision 3551              | [aeeeb63990](https://linux-hardware.org/?probe=aeeeb63990) | Aug 10, 2021 |
| Dell          | Latitude D630               | [ceb9ca591f](https://linux-hardware.org/?probe=ceb9ca591f) | Aug 05, 2021 |
| Dell          | XPS 13 9310                 | [20eabf2484](https://linux-hardware.org/?probe=20eabf2484) | Aug 02, 2021 |
| MSI           | MS-16GF                     | [ba0b532d35](https://linux-hardware.org/?probe=ba0b532d35) | Aug 01, 2021 |
| ASUSTek       | K46CM                       | [a627b4644e](https://linux-hardware.org/?probe=a627b4644e) | Jul 30, 2021 |
| ASUSTek       | K46CM                       | [ac14ce7f86](https://linux-hardware.org/?probe=ac14ce7f86) | Jul 30, 2021 |
| Lenovo        | ThinkPad X220 4293B43       | [7accb85da9](https://linux-hardware.org/?probe=7accb85da9) | Jul 30, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | [efc844205b](https://linux-hardware.org/?probe=efc844205b) | Jul 27, 2021 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [2ce8f90f70](https://linux-hardware.org/?probe=2ce8f90f70) | Jul 26, 2021 |
| Acer          | Aspire A515-41G             | [a34056020d](https://linux-hardware.org/?probe=a34056020d) | Jul 25, 2021 |
| Lenovo        | G40-45 80E1                 | [fef67a0fc3](https://linux-hardware.org/?probe=fef67a0fc3) | Jul 24, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | [4a458edcf6](https://linux-hardware.org/?probe=4a458edcf6) | Jul 24, 2021 |
| HP            | Presario CQ42               | [fa65f13c3b](https://linux-hardware.org/?probe=fa65f13c3b) | Jul 23, 2021 |
| Dell          | Inspiron 3493               | [df4bedc1fd](https://linux-hardware.org/?probe=df4bedc1fd) | Jul 21, 2021 |
| HP            | Laptop 15-db0xxx            | [9182648939](https://linux-hardware.org/?probe=9182648939) | Jul 19, 2021 |
| Acer          | TravelMate P2410-G2-M       | [7088129430](https://linux-hardware.org/?probe=7088129430) | Jul 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [36b0d241cd](https://linux-hardware.org/?probe=36b0d241cd) | Jul 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [3c938f74fd](https://linux-hardware.org/?probe=3c938f74fd) | Jul 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [3508d853ae](https://linux-hardware.org/?probe=3508d853ae) | Jul 09, 2021 |
| ASUSTek       | K401UQ                      | [9f9a853e03](https://linux-hardware.org/?probe=9f9a853e03) | Jul 05, 2021 |
| Lenovo        | ThinkPad T460s 20FAA0860... | [850c33e5c3](https://linux-hardware.org/?probe=850c33e5c3) | Jul 04, 2021 |
| ASUSTek       | G73Jw                       | [b1d6609434](https://linux-hardware.org/?probe=b1d6609434) | Jul 03, 2021 |
| Lenovo        | ThinkPad W510 4391BY8       | [12d0ff5c27](https://linux-hardware.org/?probe=12d0ff5c27) | Jul 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [bc19b4b3bf](https://linux-hardware.org/?probe=bc19b4b3bf) | Jul 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [c1442501a0](https://linux-hardware.org/?probe=c1442501a0) | Jul 03, 2021 |
| Dell          | Latitude E6430              | [ce6bc6552c](https://linux-hardware.org/?probe=ce6bc6552c) | Jun 29, 2021 |
| Dell          | Latitude 7414               | [5557aada9a](https://linux-hardware.org/?probe=5557aada9a) | Jun 28, 2021 |
| ASUSTek       | X441UA                      | [3574e8459f](https://linux-hardware.org/?probe=3574e8459f) | Jun 25, 2021 |
| HP            | Pavilion 10 TS              | [1759d8d1f8](https://linux-hardware.org/?probe=1759d8d1f8) | Jun 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [b845fbd6b0](https://linux-hardware.org/?probe=b845fbd6b0) | Jun 20, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [3eb01e93e5](https://linux-hardware.org/?probe=3eb01e93e5) | Jun 16, 2021 |
| Acer          | A315-41G                    | [c3b9603724](https://linux-hardware.org/?probe=c3b9603724) | Jun 15, 2021 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [bd7d3a3b09](https://linux-hardware.org/?probe=bd7d3a3b09) | Jun 11, 2021 |
| Acer          | Aspire E5-471               | [f15409e7cc](https://linux-hardware.org/?probe=f15409e7cc) | Jun 10, 2021 |
| Dell          | Vostro 3400                 | [2e841a4dc4](https://linux-hardware.org/?probe=2e841a4dc4) | Jun 09, 2021 |
| HP            | ProBook 440 G3              | [a5547e4146](https://linux-hardware.org/?probe=a5547e4146) | Jun 08, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [d15f22008c](https://linux-hardware.org/?probe=d15f22008c) | Jun 08, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [82dff2688d](https://linux-hardware.org/?probe=82dff2688d) | Jun 07, 2021 |
| HP            | Pavilion 10 TS              | [ad461cbf3e](https://linux-hardware.org/?probe=ad461cbf3e) | Jun 07, 2021 |
| HP            | 245 G6                      | [a3594ab925](https://linux-hardware.org/?probe=a3594ab925) | Jun 03, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [c72d3fa57d](https://linux-hardware.org/?probe=c72d3fa57d) | Jun 02, 2021 |
| Acer          | Aspire 4750                 | [499479904d](https://linux-hardware.org/?probe=499479904d) | May 27, 2021 |
| ASUSTek       | UX430UAR                    | [9f332f4fec](https://linux-hardware.org/?probe=9f332f4fec) | May 25, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [55abc8169d](https://linux-hardware.org/?probe=55abc8169d) | May 24, 2021 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [f367112b19](https://linux-hardware.org/?probe=f367112b19) | May 22, 2021 |
| HP            | Notebook                    | [1ce5457d13](https://linux-hardware.org/?probe=1ce5457d13) | May 21, 2021 |
| HP            | Notebook                    | [42756549fb](https://linux-hardware.org/?probe=42756549fb) | May 21, 2021 |
| Toshiba       | Satellite C850-B797         | [834d15c08c](https://linux-hardware.org/?probe=834d15c08c) | May 16, 2021 |
| Toshiba       | Satellite C850-B797         | [0ece4b9e9e](https://linux-hardware.org/?probe=0ece4b9e9e) | May 16, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [00a8ed533c](https://linux-hardware.org/?probe=00a8ed533c) | May 15, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [14b8295348](https://linux-hardware.org/?probe=14b8295348) | May 15, 2021 |
| Apple         | MacBookAir7,2               | [df405076a1](https://linux-hardware.org/?probe=df405076a1) | May 14, 2021 |
| Toshiba       | Satellite C850-B797         | [1355c6e459](https://linux-hardware.org/?probe=1355c6e459) | May 13, 2021 |
| Lenovo        | ThinkPad T420 42363Y5       | [5a93fb1b0b](https://linux-hardware.org/?probe=5a93fb1b0b) | May 07, 2021 |
| Dell          | Inspiron 3480               | [5ad427cffb](https://linux-hardware.org/?probe=5ad427cffb) | May 04, 2021 |
| Dell          | XPS 15 9550                 | [30b952e127](https://linux-hardware.org/?probe=30b952e127) | May 02, 2021 |
| Notebook      | N150CU                      | [e62762a731](https://linux-hardware.org/?probe=e62762a731) | Apr 14, 2021 |
| Lenovo        | ThinkPad X260 20F5A0HB00    | [9163ce31dc](https://linux-hardware.org/?probe=9163ce31dc) | Apr 14, 2021 |
| Lenovo        | G40-45 80E1                 | [1263e938c8](https://linux-hardware.org/?probe=1263e938c8) | Apr 13, 2021 |
| Lenovo        | G40-45 80E1                 | [5fada7c64a](https://linux-hardware.org/?probe=5fada7c64a) | Apr 13, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [cdf6743f68](https://linux-hardware.org/?probe=cdf6743f68) | Apr 08, 2021 |
| Lenovo        | V330-14IKB 81B0             | [729cbf17a4](https://linux-hardware.org/?probe=729cbf17a4) | Apr 07, 2021 |
| Lenovo        | ThinkPad X230 2325BG3       | [90f6078b02](https://linux-hardware.org/?probe=90f6078b02) | Apr 04, 2021 |
| ASUSTek       | X555DG                      | [334a8d4184](https://linux-hardware.org/?probe=334a8d4184) | Apr 04, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [2af0a44c72](https://linux-hardware.org/?probe=2af0a44c72) | Apr 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [2c67d604ff](https://linux-hardware.org/?probe=2c67d604ff) | Mar 28, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [01ab712b94](https://linux-hardware.org/?probe=01ab712b94) | Mar 22, 2021 |
| ASUSTek       | N53SM                       | [87e7b3b248](https://linux-hardware.org/?probe=87e7b3b248) | Mar 22, 2021 |
| Toshiba       | Satellite U505              | [1d422767e1](https://linux-hardware.org/?probe=1d422767e1) | Mar 20, 2021 |
| Toshiba       | Satellite U505              | [ccb5c756ee](https://linux-hardware.org/?probe=ccb5c756ee) | Mar 20, 2021 |
| Acer          | AOD255                      | [2e5b228a04](https://linux-hardware.org/?probe=2e5b228a04) | Mar 17, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [843d061b78](https://linux-hardware.org/?probe=843d061b78) | Mar 15, 2021 |
| HP            | Laptop 14-cm1xxx            | [87cabd058e](https://linux-hardware.org/?probe=87cabd058e) | Mar 13, 2021 |
| HP            | 245 G7 Notebook PC          | [8cb18a4f6c](https://linux-hardware.org/?probe=8cb18a4f6c) | Mar 11, 2021 |
| HP            | 245 G7 Notebook PC          | [a6e9e8ea5e](https://linux-hardware.org/?probe=a6e9e8ea5e) | Mar 11, 2021 |
| Acer          | AOD255                      | [f3a5b4b0e4](https://linux-hardware.org/?probe=f3a5b4b0e4) | Mar 06, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [d9708c63f5](https://linux-hardware.org/?probe=d9708c63f5) | Mar 04, 2021 |
| Dell          | Precision 3551              | [d75a598209](https://linux-hardware.org/?probe=d75a598209) | Mar 03, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [bc879be58b](https://linux-hardware.org/?probe=bc879be58b) | Mar 03, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [27b7f94851](https://linux-hardware.org/?probe=27b7f94851) | Mar 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [935f9c5571](https://linux-hardware.org/?probe=935f9c5571) | Mar 03, 2021 |
| HP            | Pavilion 10 TS              | [5998c38555](https://linux-hardware.org/?probe=5998c38555) | Feb 26, 2021 |
| Dell          | Latitude E6220              | [1c0ab9fab1](https://linux-hardware.org/?probe=1c0ab9fab1) | Feb 23, 2021 |
| Dell          | Latitude E6220              | [19e1a4a1d6](https://linux-hardware.org/?probe=19e1a4a1d6) | Feb 23, 2021 |
| Dell          | Inspiron 3493               | [684245175e](https://linux-hardware.org/?probe=684245175e) | Feb 20, 2021 |
| Acer          | TravelMate P449-G2-M        | [7581904d41](https://linux-hardware.org/?probe=7581904d41) | Feb 20, 2021 |
| Apple         | MacBookPro15,1              | [a148b9034a](https://linux-hardware.org/?probe=a148b9034a) | Feb 19, 2021 |
| HP            | ProBook 440 G7              | [f6830c6ac2](https://linux-hardware.org/?probe=f6830c6ac2) | Feb 18, 2021 |
| Lenovo        | IdeaPad 520S-14IKB 80X2     | [ecddf05f3e](https://linux-hardware.org/?probe=ecddf05f3e) | Feb 16, 2021 |
| BAKED         | P7xxDM2(-G)                 | [824169b9f7](https://linux-hardware.org/?probe=824169b9f7) | Feb 16, 2021 |
| HP            | ProBook 440 G2              | [8be5048c51](https://linux-hardware.org/?probe=8be5048c51) | Feb 15, 2021 |
| Lenovo        | IdeaPad 520S-14IKB 80X2     | [8da12e7518](https://linux-hardware.org/?probe=8da12e7518) | Feb 14, 2021 |
| Inspur        | M11JB R2.0/R1.1             | [5e5731f2b0](https://linux-hardware.org/?probe=5e5731f2b0) | Feb 13, 2021 |
| Inspur        | M11JB R2.0/R1.1             | [90847dec81](https://linux-hardware.org/?probe=90847dec81) | Feb 12, 2021 |
| HP            | Notebook                    | [5224b13971](https://linux-hardware.org/?probe=5224b13971) | Feb 08, 2021 |
| Dell          | Inspiron 7586               | [7e6463f517](https://linux-hardware.org/?probe=7e6463f517) | Feb 05, 2021 |
| ASUSTek       | X505BA                      | [8059f98337](https://linux-hardware.org/?probe=8059f98337) | Feb 03, 2021 |
| HP            | Presario CQ43               | [13eb02bc61](https://linux-hardware.org/?probe=13eb02bc61) | Feb 02, 2021 |
| HP            | Presario CQ43               | [a6d1b8df1e](https://linux-hardware.org/?probe=a6d1b8df1e) | Feb 02, 2021 |
| Notebook      | N150CU                      | [7753afd04f](https://linux-hardware.org/?probe=7753afd04f) | Jan 29, 2021 |
| Lenovo        | ThinkPad L430 2466EC5       | [8f5111df1d](https://linux-hardware.org/?probe=8f5111df1d) | Jan 28, 2021 |
| Acer          | Aspire E5-575G              | [eac34165b9](https://linux-hardware.org/?probe=eac34165b9) | Jan 27, 2021 |
| HP            | Laptop 15-db0xxx            | [ab91702ac3](https://linux-hardware.org/?probe=ab91702ac3) | Jan 26, 2021 |
| GreatWall     | K41                         | [ddf99d904e](https://linux-hardware.org/?probe=ddf99d904e) | Jan 25, 2021 |
| ASUSTek       | X555LN                      | [e649cc1304](https://linux-hardware.org/?probe=e649cc1304) | Jan 24, 2021 |
| ASUSTek       | X441UVK                     | [c73eaa8a8f](https://linux-hardware.org/?probe=c73eaa8a8f) | Jan 21, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [0ca25f14fb](https://linux-hardware.org/?probe=0ca25f14fb) | Jan 21, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [419800f72d](https://linux-hardware.org/?probe=419800f72d) | Jan 21, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [844d185dae](https://linux-hardware.org/?probe=844d185dae) | Jan 21, 2021 |
| Dell          | XPS 15 9550                 | [91a85ad436](https://linux-hardware.org/?probe=91a85ad436) | Jan 20, 2021 |
| Lenovo        | IdeaPad S340-14IWL 81N7     | [62de1cd91f](https://linux-hardware.org/?probe=62de1cd91f) | Jan 16, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [edcaecc674](https://linux-hardware.org/?probe=edcaecc674) | Jan 14, 2021 |
| ASUSTek       | K46CM                       | [e5d77ec648](https://linux-hardware.org/?probe=e5d77ec648) | Jan 14, 2021 |
| Dell          | Precision 3551              | [c6524a92a4](https://linux-hardware.org/?probe=c6524a92a4) | Jan 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [6d637febe2](https://linux-hardware.org/?probe=6d637febe2) | Jan 10, 2021 |
| ASUSTek       | X455LJ                      | [05b3190864](https://linux-hardware.org/?probe=05b3190864) | Jan 08, 2021 |
| Lenovo        | Y720-15IKB 80VR             | [0d58fd33df](https://linux-hardware.org/?probe=0d58fd33df) | Jan 07, 2021 |
| Lenovo        | Y720-15IKB 80VR             | [d1947d8c18](https://linux-hardware.org/?probe=d1947d8c18) | Jan 07, 2021 |
| Dell          | System XPS L502X            | [6548d3214b](https://linux-hardware.org/?probe=6548d3214b) | Jan 06, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [4e9f49422a](https://linux-hardware.org/?probe=4e9f49422a) | Jan 04, 2021 |
| BAKED         | P7xxDM2(-G)                 | [c4206ecc26](https://linux-hardware.org/?probe=c4206ecc26) | Jan 04, 2021 |
| Lenovo        | B41-35 80LD                 | [f995163ff4](https://linux-hardware.org/?probe=f995163ff4) | Jan 04, 2021 |
| Lenovo        | B41-35 80LD                 | [2758658d90](https://linux-hardware.org/?probe=2758658d90) | Jan 04, 2021 |
| ASUSTek       | X555QG                      | [801defb54c](https://linux-hardware.org/?probe=801defb54c) | Jan 02, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [6b7c6db0c5](https://linux-hardware.org/?probe=6b7c6db0c5) | Dec 30, 2020 |
| Lenovo        | IdeaPad S340-14API 81NB     | [10b0b04256](https://linux-hardware.org/?probe=10b0b04256) | Dec 30, 2020 |
| Notebook      | NB50TJ1_TK1                 | [10d64eecc5](https://linux-hardware.org/?probe=10d64eecc5) | Dec 30, 2020 |
| HP            | Laptop 14-cm1xxx            | [e850bec31a](https://linux-hardware.org/?probe=e850bec31a) | Dec 29, 2020 |
| Acer          | Aspire E5-575G              | [3c4ea54770](https://linux-hardware.org/?probe=3c4ea54770) | Dec 26, 2020 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [d61f2aa238](https://linux-hardware.org/?probe=d61f2aa238) | Dec 26, 2020 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [bca2708dcd](https://linux-hardware.org/?probe=bca2708dcd) | Dec 25, 2020 |
| ASUSTek       | X450CP                      | [1d2d82e5ee](https://linux-hardware.org/?probe=1d2d82e5ee) | Dec 22, 2020 |
| Apple         | MacBookPro11,1              | [e395d72cbb](https://linux-hardware.org/?probe=e395d72cbb) | Dec 21, 2020 |
| HP            | Pavilion dv4                | [0f86ea7cab](https://linux-hardware.org/?probe=0f86ea7cab) | Dec 20, 2020 |
| HP            | ProBook 440 G3              | [ad30a7ae38](https://linux-hardware.org/?probe=ad30a7ae38) | Dec 20, 2020 |
| Notebook      | NB50TJ1_TK1                 | [c23ae5c475](https://linux-hardware.org/?probe=c23ae5c475) | Dec 19, 2020 |
| Lenovo        | IdeaPad Y550P 3241          | [2475252354](https://linux-hardware.org/?probe=2475252354) | Dec 19, 2020 |
| Lenovo        | IdeaPad Y550P 3241          | [a08f4cf4e5](https://linux-hardware.org/?probe=a08f4cf4e5) | Dec 19, 2020 |
| ASUSTek       | X555QG                      | [263df4fa91](https://linux-hardware.org/?probe=263df4fa91) | Dec 19, 2020 |
| HP            | Laptop 15-da0xxx            | [73fa61c233](https://linux-hardware.org/?probe=73fa61c233) | Dec 15, 2020 |
| Lenovo        | IdeaPad Y410P 20216         | [dd0d449586](https://linux-hardware.org/?probe=dd0d449586) | Dec 14, 2020 |
| Notebook      | NB50TJ1_TK1                 | [246d659f60](https://linux-hardware.org/?probe=246d659f60) | Dec 11, 2020 |
| HP            | Laptop 15-da0xxx            | [fb4783aeba](https://linux-hardware.org/?probe=fb4783aeba) | Dec 10, 2020 |
| Lenovo        | Yoga 700-11ISK 80QE         | [1a353b9226](https://linux-hardware.org/?probe=1a353b9226) | Dec 08, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [3962cbfb58](https://linux-hardware.org/?probe=3962cbfb58) | Dec 05, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [3d5a1c07e6](https://linux-hardware.org/?probe=3d5a1c07e6) | Dec 05, 2020 |
| Lenovo        | IdeaPad S145-14API 81UV     | [02fb63a36f](https://linux-hardware.org/?probe=02fb63a36f) | Dec 04, 2020 |
| ASUSTek       | X555QG                      | [841208193d](https://linux-hardware.org/?probe=841208193d) | Dec 03, 2020 |
| ASUSTek       | K46CM                       | [490bae951e](https://linux-hardware.org/?probe=490bae951e) | Dec 01, 2020 |
| Lenovo        | G470 20078                  | [b0564c0e50](https://linux-hardware.org/?probe=b0564c0e50) | Dec 01, 2020 |
| ASUSTek       | X555QG                      | [e90cdb39ef](https://linux-hardware.org/?probe=e90cdb39ef) | Nov 30, 2020 |
| Lenovo        | IdeaPad U510 20191          | [895b641220](https://linux-hardware.org/?probe=895b641220) | Nov 30, 2020 |
| MSI           | PS63 Modern 8RC             | [0a4b399149](https://linux-hardware.org/?probe=0a4b399149) | Nov 26, 2020 |
| Notebook      | NB50TJ1_TK1                 | [0c9f7ea289](https://linux-hardware.org/?probe=0c9f7ea289) | Nov 26, 2020 |
| Notebook      | NB50TJ1_TK1                 | [a5f5b59788](https://linux-hardware.org/?probe=a5f5b59788) | Nov 26, 2020 |
| HP            | Laptop 15-db0xxx            | [503b8f9701](https://linux-hardware.org/?probe=503b8f9701) | Nov 25, 2020 |
| ASUSTek       | X441NA                      | [61a5d6947b](https://linux-hardware.org/?probe=61a5d6947b) | Nov 25, 2020 |
| Unknown       | Unknown                     | [73dc6959d6](https://linux-hardware.org/?probe=73dc6959d6) | Nov 23, 2020 |
| Unknown       | Unknown                     | [b0c0ef90cd](https://linux-hardware.org/?probe=b0c0ef90cd) | Nov 23, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [a997f8c186](https://linux-hardware.org/?probe=a997f8c186) | Nov 22, 2020 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [e24dba10a2](https://linux-hardware.org/?probe=e24dba10a2) | Nov 22, 2020 |
| ASUSTek       | X441NA                      | [e301cabf95](https://linux-hardware.org/?probe=e301cabf95) | Nov 21, 2020 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | [5021095fd1](https://linux-hardware.org/?probe=5021095fd1) | Nov 19, 2020 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | [e5e8cfd574](https://linux-hardware.org/?probe=e5e8cfd574) | Nov 19, 2020 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | [026fdce11f](https://linux-hardware.org/?probe=026fdce11f) | Nov 13, 2020 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | [b3752255e5](https://linux-hardware.org/?probe=b3752255e5) | Nov 13, 2020 |
| HP            | ProBook 6450b               | [74c2b345b8](https://linux-hardware.org/?probe=74c2b345b8) | Nov 05, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [5efbf0cf43](https://linux-hardware.org/?probe=5efbf0cf43) | Nov 05, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [3f9b54f16c](https://linux-hardware.org/?probe=3f9b54f16c) | Nov 05, 2020 |
| Lenovo        | G450 2949                   | [f9bb66b7a2](https://linux-hardware.org/?probe=f9bb66b7a2) | Nov 03, 2020 |
| ASUSTek       | X411UQ                      | [f3e110826b](https://linux-hardware.org/?probe=f3e110826b) | Nov 01, 2020 |
| ASUSTek       | X411UQ                      | [9786cce501](https://linux-hardware.org/?probe=9786cce501) | Nov 01, 2020 |
| Lenovo        | Z50-70 20354                | [b252d0ad02](https://linux-hardware.org/?probe=b252d0ad02) | Oct 31, 2020 |
| Dell          | XPS 15 9550                 | [f08f791eaf](https://linux-hardware.org/?probe=f08f791eaf) | Oct 28, 2020 |
| Dell          | XPS 15 9550                 | [dcd8f2aa99](https://linux-hardware.org/?probe=dcd8f2aa99) | Oct 27, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [cafb41376f](https://linux-hardware.org/?probe=cafb41376f) | Oct 26, 2020 |
| HP            | Laptop 15-db0xxx            | [fa89c085cf](https://linux-hardware.org/?probe=fa89c085cf) | Oct 25, 2020 |
| Acer          | Aspire 4730Z                | [7157a6069b](https://linux-hardware.org/?probe=7157a6069b) | Oct 21, 2020 |
| Acer          | Aspire 4730Z                | [fb18c13ac7](https://linux-hardware.org/?probe=fb18c13ac7) | Oct 21, 2020 |
| Lenovo        | IdeaPad S340-14API 81NB     | [89c3fe76c0](https://linux-hardware.org/?probe=89c3fe76c0) | Oct 18, 2020 |
| Lenovo        | IdeaPad S340-14API 81NB     | [0a4d06561e](https://linux-hardware.org/?probe=0a4d06561e) | Oct 18, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [8fb2a0621d](https://linux-hardware.org/?probe=8fb2a0621d) | Oct 12, 2020 |
| Lenovo        | G40-45 80E1                 | [eefc7c92b2](https://linux-hardware.org/?probe=eefc7c92b2) | Oct 11, 2020 |
| Dell          | Latitude E7270              | [cff6ba0c00](https://linux-hardware.org/?probe=cff6ba0c00) | Oct 11, 2020 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [e04a055ab8](https://linux-hardware.org/?probe=e04a055ab8) | Oct 11, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [c376c39381](https://linux-hardware.org/?probe=c376c39381) | Oct 07, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [4e2c32a972](https://linux-hardware.org/?probe=4e2c32a972) | Oct 07, 2020 |
| Dell          | Inspiron 3480               | [243905bcf2](https://linux-hardware.org/?probe=243905bcf2) | Oct 06, 2020 |
| HP            | Laptop 15-db0xxx            | [eaeba54519](https://linux-hardware.org/?probe=eaeba54519) | Oct 05, 2020 |
| MPS Mayori... | COIN ST800EDU               | [11e4ae4bfe](https://linux-hardware.org/?probe=11e4ae4bfe) | Oct 03, 2020 |
| MPS Mayori... | COIN ST800EDU               | [38a7d9f974](https://linux-hardware.org/?probe=38a7d9f974) | Oct 03, 2020 |
| HP            | Laptop 15-db0xxx            | [eb0e17a039](https://linux-hardware.org/?probe=eb0e17a039) | Oct 01, 2020 |
| HP            | Laptop 15-db0xxx            | [e0afc29d83](https://linux-hardware.org/?probe=e0afc29d83) | Oct 01, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [4ff7a5528c](https://linux-hardware.org/?probe=4ff7a5528c) | Sep 29, 2020 |
| HP            | EliteBook 8440p             | [21ecdf1804](https://linux-hardware.org/?probe=21ecdf1804) | Sep 28, 2020 |
| HP            | Pavilion 10 TS              | [393e09d070](https://linux-hardware.org/?probe=393e09d070) | Sep 28, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [7ec7b7dbb0](https://linux-hardware.org/?probe=7ec7b7dbb0) | Sep 27, 2020 |
| Dell          | Inspiron 3493               | [be76b68bff](https://linux-hardware.org/?probe=be76b68bff) | Sep 25, 2020 |
| HP            | Notebook                    | [97099ba5b3](https://linux-hardware.org/?probe=97099ba5b3) | Sep 23, 2020 |
| Lenovo        | IdeaPad S145-14IGM 81MW     | [4b3f7c31cc](https://linux-hardware.org/?probe=4b3f7c31cc) | Sep 21, 2020 |
| Lenovo        | IdeaPad S145-14IGM 81MW     | [bf2a498d90](https://linux-hardware.org/?probe=bf2a498d90) | Sep 21, 2020 |
| ASUSTek       | X441UVK                     | [4be17c95ab](https://linux-hardware.org/?probe=4be17c95ab) | Sep 18, 2020 |
| Dell          | Latitude E7270              | [76c31048e9](https://linux-hardware.org/?probe=76c31048e9) | Sep 14, 2020 |
| Toshiba       | Satellite U505              | [20507a8670](https://linux-hardware.org/?probe=20507a8670) | Sep 14, 2020 |
| Dell          | Studio 1558                 | [bfa6ee72ad](https://linux-hardware.org/?probe=bfa6ee72ad) | Sep 11, 2020 |
| Dell          | Studio 1558                 | [09283ede94](https://linux-hardware.org/?probe=09283ede94) | Sep 11, 2020 |
| Acer          | TravelMate 5744             | [cd7e3646ff](https://linux-hardware.org/?probe=cd7e3646ff) | Sep 09, 2020 |
| HP            | EliteBook 840 G5            | [0a16cda83f](https://linux-hardware.org/?probe=0a16cda83f) | Sep 08, 2020 |
| Dell          | Inspiron N5040              | [7d81a97615](https://linux-hardware.org/?probe=7d81a97615) | Sep 07, 2020 |
| Dell          | Inspiron 5570               | [c184b08cc3](https://linux-hardware.org/?probe=c184b08cc3) | Sep 06, 2020 |
| Acer          | Aspire E5-575G              | [71698fa8ea](https://linux-hardware.org/?probe=71698fa8ea) | Sep 05, 2020 |
| Acer          | Aspire 7741                 | [e5914ee358](https://linux-hardware.org/?probe=e5914ee358) | Sep 05, 2020 |
| Dell          | Inspiron 3493               | [11adb16243](https://linux-hardware.org/?probe=11adb16243) | Sep 03, 2020 |
| ASUSTek       | X442UA                      | [cad592ae29](https://linux-hardware.org/?probe=cad592ae29) | Aug 31, 2020 |
| ASUSTek       | X442UA                      | [7697815bb5](https://linux-hardware.org/?probe=7697815bb5) | Aug 31, 2020 |
| HP            | EliteBook 840 G5            | [c020f92165](https://linux-hardware.org/?probe=c020f92165) | Aug 30, 2020 |
| HP            | ProBook 440 G3              | [1e65e31e23](https://linux-hardware.org/?probe=1e65e31e23) | Aug 30, 2020 |
| Samsung       | R430/R480/R440              | [c37003dbfc](https://linux-hardware.org/?probe=c37003dbfc) | Aug 30, 2020 |
| Lenovo        | IdeaPad Z480                | [c1fe24f51b](https://linux-hardware.org/?probe=c1fe24f51b) | Aug 28, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [eb0990afbe](https://linux-hardware.org/?probe=eb0990afbe) | Aug 23, 2020 |
| Lenovo        | IdeaPad Z480                | [f43e5244bc](https://linux-hardware.org/?probe=f43e5244bc) | Aug 23, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [7b4fcb3693](https://linux-hardware.org/?probe=7b4fcb3693) | Aug 21, 2020 |
| Lenovo        | IdeaPad S540-14IWL 81ND     | [27987ebfb1](https://linux-hardware.org/?probe=27987ebfb1) | Aug 17, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [2151fb7ccb](https://linux-hardware.org/?probe=2151fb7ccb) | Aug 15, 2020 |
| Acer          | AOD255                      | [627daa28b5](https://linux-hardware.org/?probe=627daa28b5) | Aug 11, 2020 |
| HP            | Laptop 14-cm1xxx            | [95f6d41901](https://linux-hardware.org/?probe=95f6d41901) | Aug 07, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [c958c50dad](https://linux-hardware.org/?probe=c958c50dad) | Aug 07, 2020 |
| HP            | ENVY 15                     | [d2fab519a5](https://linux-hardware.org/?probe=d2fab519a5) | Aug 04, 2020 |
| Toshiba       | Satellite L645              | [2f81e753a6](https://linux-hardware.org/?probe=2f81e753a6) | Jul 31, 2020 |
| HP            | 245 G6                      | [eb51696edd](https://linux-hardware.org/?probe=eb51696edd) | Jul 29, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [1b4b43f382](https://linux-hardware.org/?probe=1b4b43f382) | Jul 29, 2020 |
| HP            | G42                         | [80828bd820](https://linux-hardware.org/?probe=80828bd820) | Jul 29, 2020 |
| HP            | Laptop 15-db0xxx            | [0928c9c524](https://linux-hardware.org/?probe=0928c9c524) | Jul 27, 2020 |
| HP            | Compaq CQ45                 | [26022f582b](https://linux-hardware.org/?probe=26022f582b) | Jul 26, 2020 |
| HP            | Compaq CQ45                 | [74cad2f13e](https://linux-hardware.org/?probe=74cad2f13e) | Jul 26, 2020 |
| HP            | Laptop 15-db0xxx            | [75928e5332](https://linux-hardware.org/?probe=75928e5332) | Jul 25, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [b4f52ba1be](https://linux-hardware.org/?probe=b4f52ba1be) | Jul 25, 2020 |
| Lenovo        | IdeaPad Z480                | [17ecc94bc0](https://linux-hardware.org/?probe=17ecc94bc0) | Jul 24, 2020 |
| Toshiba       | Satellite M505              | [518faca568](https://linux-hardware.org/?probe=518faca568) | Jul 21, 2020 |
| Toshiba       | Satellite S75-A             | [a2fc5378af](https://linux-hardware.org/?probe=a2fc5378af) | Jul 21, 2020 |
| Toshiba       | Satellite M505              | [64f79b1c45](https://linux-hardware.org/?probe=64f79b1c45) | Jul 21, 2020 |
| Dell          | Latitude E7270              | [3240f0ae94](https://linux-hardware.org/?probe=3240f0ae94) | Jul 20, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [1839ba41d3](https://linux-hardware.org/?probe=1839ba41d3) | Jul 19, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [f179e69271](https://linux-hardware.org/?probe=f179e69271) | Jul 19, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [543185b30a](https://linux-hardware.org/?probe=543185b30a) | Jul 18, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [e66cd74e47](https://linux-hardware.org/?probe=e66cd74e47) | Jul 18, 2020 |
| ASUSTek       | X456UA                      | [0bc503ae0b](https://linux-hardware.org/?probe=0bc503ae0b) | Jul 16, 2020 |
| HP            | Laptop 15-db0xxx            | [8a858d88d0](https://linux-hardware.org/?probe=8a858d88d0) | Jul 15, 2020 |
| HP            | Laptop 15-db0xxx            | [260563b336](https://linux-hardware.org/?probe=260563b336) | Jul 15, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [38242e89d2](https://linux-hardware.org/?probe=38242e89d2) | Jul 12, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [c4e21ddab2](https://linux-hardware.org/?probe=c4e21ddab2) | Jul 12, 2020 |
| ASUSTek       | X456UA                      | [6b61996456](https://linux-hardware.org/?probe=6b61996456) | Jul 12, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [858cd73913](https://linux-hardware.org/?probe=858cd73913) | Jul 11, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [fc5d45e94a](https://linux-hardware.org/?probe=fc5d45e94a) | Jul 10, 2020 |
| HP            | Compaq 6730s                | [e128a9542c](https://linux-hardware.org/?probe=e128a9542c) | Jul 04, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [dd5e302721](https://linux-hardware.org/?probe=dd5e302721) | Jul 03, 2020 |
| ASUSTek       | K46CM                       | [5260584205](https://linux-hardware.org/?probe=5260584205) | Jun 30, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [0999108dfb](https://linux-hardware.org/?probe=0999108dfb) | Jun 29, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [aba4b6462f](https://linux-hardware.org/?probe=aba4b6462f) | Jun 27, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [a54dfa2b8b](https://linux-hardware.org/?probe=a54dfa2b8b) | Jun 27, 2020 |
| Dell          | XPS 15 9550                 | [fae71e18b2](https://linux-hardware.org/?probe=fae71e18b2) | Jun 25, 2020 |
| Apple         | MacBookPro5,5               | [7e4c8ea12c](https://linux-hardware.org/?probe=7e4c8ea12c) | Jun 25, 2020 |
| Apple         | MacBookPro5,5               | [5e921d68ff](https://linux-hardware.org/?probe=5e921d68ff) | Jun 25, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | [7e8026e797](https://linux-hardware.org/?probe=7e8026e797) | Jun 22, 2020 |
| Toshiba       | PORTEGE Z30-B               | [29f9ac42d8](https://linux-hardware.org/?probe=29f9ac42d8) | Jun 21, 2020 |
| Unknown       | Unknown                     | [73cda410f2](https://linux-hardware.org/?probe=73cda410f2) | Jun 19, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [a7d7f2f4f3](https://linux-hardware.org/?probe=a7d7f2f4f3) | Jun 18, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [d194146ff8](https://linux-hardware.org/?probe=d194146ff8) | Jun 18, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [5b4fdab686](https://linux-hardware.org/?probe=5b4fdab686) | Jun 18, 2020 |
| Dell          | Inspiron N4010              | [a1ae232e58](https://linux-hardware.org/?probe=a1ae232e58) | Jun 13, 2020 |
| Acer          | Aspire 5532                 | [ce8deb0caa](https://linux-hardware.org/?probe=ce8deb0caa) | Jun 12, 2020 |
| Acer          | Aspire 5532                 | [cc0f65e016](https://linux-hardware.org/?probe=cc0f65e016) | Jun 12, 2020 |
| Gateway       | M-6319                      | [5b3e8b9ef1](https://linux-hardware.org/?probe=5b3e8b9ef1) | Jun 10, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [52c8b6876e](https://linux-hardware.org/?probe=52c8b6876e) | Jun 08, 2020 |
| ASUSTek       | T100TA                      | [aad1de590c](https://linux-hardware.org/?probe=aad1de590c) | Jun 07, 2020 |
| Acer          | Aspire E1-421               | [81073e838e](https://linux-hardware.org/?probe=81073e838e) | Jun 05, 2020 |
| ASUSTek       | X455LJ                      | [e7901f9d16](https://linux-hardware.org/?probe=e7901f9d16) | Jun 05, 2020 |
| Sony          | VGN-NR310FH                 | [c774d0a51a](https://linux-hardware.org/?probe=c774d0a51a) | Jun 05, 2020 |
| ASUSTek       | X555LJ                      | [9585e46a59](https://linux-hardware.org/?probe=9585e46a59) | Jun 04, 2020 |
| Lenovo        | ThinkPad T430u 86143HU      | [5a3bf0a8f5](https://linux-hardware.org/?probe=5a3bf0a8f5) | Jun 03, 2020 |
| ASUSTek       | X555LJ                      | [d45d40decd](https://linux-hardware.org/?probe=d45d40decd) | Jun 03, 2020 |
| ASUSTek       | K46CM                       | [994e39c619](https://linux-hardware.org/?probe=994e39c619) | Jun 02, 2020 |
| Apple         | MacBook5,1                  | [841614c2d1](https://linux-hardware.org/?probe=841614c2d1) | Jun 01, 2020 |
| Apple         | MacBook5,1                  | [8126e4dea3](https://linux-hardware.org/?probe=8126e4dea3) | Jun 01, 2020 |
| Acer          | Aspire E1-421               | [618908f152](https://linux-hardware.org/?probe=618908f152) | May 27, 2020 |
| ASUSTek       | X411UQ                      | [a3e9e016a6](https://linux-hardware.org/?probe=a3e9e016a6) | May 27, 2020 |
| Lenovo        | ThinkPad A475 20KMS0NG00    | [4572fa1657](https://linux-hardware.org/?probe=4572fa1657) | May 27, 2020 |
| Dell          | Inspiron 5521               | [169492fdd8](https://linux-hardware.org/?probe=169492fdd8) | May 26, 2020 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [871784f430](https://linux-hardware.org/?probe=871784f430) | May 26, 2020 |
| HP            | 430                         | [54ba3df0c8](https://linux-hardware.org/?probe=54ba3df0c8) | May 24, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [c4c76cecbd](https://linux-hardware.org/?probe=c4c76cecbd) | May 23, 2020 |
| HP            | Laptop 14-bw0xx             | [c9c485db32](https://linux-hardware.org/?probe=c9c485db32) | May 22, 2020 |
| Sony          | SVF14A15CLB                 | [7fb2e1bda0](https://linux-hardware.org/?probe=7fb2e1bda0) | May 20, 2020 |
| Samsung       | 535U3C                      | [b3983a1b17](https://linux-hardware.org/?probe=b3983a1b17) | May 20, 2020 |
| Dell          | Inspiron 1420               | [1269d54a19](https://linux-hardware.org/?probe=1269d54a19) | May 20, 2020 |
| Dell          | Inspiron N4010              | [fe9c89b85a](https://linux-hardware.org/?probe=fe9c89b85a) | May 17, 2020 |
| Lenovo        | G40-80 80E4                 | [70a6d29aa3](https://linux-hardware.org/?probe=70a6d29aa3) | May 15, 2020 |
| Samsung       | 535U3C                      | [fe2d93033d](https://linux-hardware.org/?probe=fe2d93033d) | May 13, 2020 |
| Lenovo        | V330-14IKB 81B0             | [5ed9a929ec](https://linux-hardware.org/?probe=5ed9a929ec) | May 10, 2020 |
| Sony          | SVE14121CLP                 | [df7e4c2b9f](https://linux-hardware.org/?probe=df7e4c2b9f) | May 09, 2020 |
| Lenovo        | IdeaPad S540-14API 81NH     | [69942e79bd](https://linux-hardware.org/?probe=69942e79bd) | May 02, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [91627f8ac4](https://linux-hardware.org/?probe=91627f8ac4) | Apr 29, 2020 |
| Toshiba       | Satellite L515              | [c411228b1a](https://linux-hardware.org/?probe=c411228b1a) | Apr 28, 2020 |
| Inspur        | M11JB R2.0/R1.1             | [7f92b47ef4](https://linux-hardware.org/?probe=7f92b47ef4) | Apr 27, 2020 |
| HP            | Pavilion dv6                | [163dac19b3](https://linux-hardware.org/?probe=163dac19b3) | Apr 26, 2020 |
| HP            | Pavilion dv6                | [13cb9e8a90](https://linux-hardware.org/?probe=13cb9e8a90) | Apr 26, 2020 |
| Lenovo        | Z50-70 20354                | [f429ce4848](https://linux-hardware.org/?probe=f429ce4848) | Apr 22, 2020 |
| Dell          | G5 5587                     | [dd4521b554](https://linux-hardware.org/?probe=dd4521b554) | Apr 21, 2020 |
| HP            | Laptop 14-bs0xx             | [e5243ea838](https://linux-hardware.org/?probe=e5243ea838) | Apr 21, 2020 |
| HP            | Pavilion g4                 | [7e9785b653](https://linux-hardware.org/?probe=7e9785b653) | Apr 18, 2020 |
| ASUSTek       | X453SA                      | [ce1bd3affc](https://linux-hardware.org/?probe=ce1bd3affc) | Apr 18, 2020 |
| ASUSTek       | N46VB                       | [d27bf3c005](https://linux-hardware.org/?probe=d27bf3c005) | Apr 18, 2020 |
| HP            | Pavilion g4                 | [3c6a4199c7](https://linux-hardware.org/?probe=3c6a4199c7) | Apr 18, 2020 |
| ASUSTek       | N46VB                       | [5d25f725c9](https://linux-hardware.org/?probe=5d25f725c9) | Apr 18, 2020 |
| ASUSTek       | N46VB                       | [eae7b8a990](https://linux-hardware.org/?probe=eae7b8a990) | Apr 17, 2020 |
| ASUSTek       | N46VB                       | [ab1938abc6](https://linux-hardware.org/?probe=ab1938abc6) | Apr 17, 2020 |
| Acer          | Aspire V5-471               | [6540209d65](https://linux-hardware.org/?probe=6540209d65) | Apr 16, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | [010fdcb7ab](https://linux-hardware.org/?probe=010fdcb7ab) | Apr 16, 2020 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [8eae2753ce](https://linux-hardware.org/?probe=8eae2753ce) | Apr 16, 2020 |
| HP            | Laptop 15-db0xxx            | [6ec2d663e5](https://linux-hardware.org/?probe=6ec2d663e5) | Apr 15, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | [a4b76d231e](https://linux-hardware.org/?probe=a4b76d231e) | Apr 15, 2020 |
| Acer          | Aspire A515-51              | [cb760929c4](https://linux-hardware.org/?probe=cb760929c4) | Apr 14, 2020 |
| Samsung       | 530U4E/540U4E               | [33747354e3](https://linux-hardware.org/?probe=33747354e3) | Apr 13, 2020 |
| Samsung       | 530U4E/540U4E               | [06fa247c32](https://linux-hardware.org/?probe=06fa247c32) | Apr 13, 2020 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | [25e23d0bf7](https://linux-hardware.org/?probe=25e23d0bf7) | Apr 13, 2020 |
| Lenovo        | ThinkPad E460 20ETA05Y00    | [823afb58b0](https://linux-hardware.org/?probe=823afb58b0) | Apr 12, 2020 |
| Lenovo        | ThinkPad E460 20ETA05Y00    | [90b23eb96e](https://linux-hardware.org/?probe=90b23eb96e) | Apr 12, 2020 |
| Dell          | System Inspiron 5420        | [f74d698b46](https://linux-hardware.org/?probe=f74d698b46) | Apr 11, 2020 |
| Toshiba       | Satellite A505              | [f7f3c03ad9](https://linux-hardware.org/?probe=f7f3c03ad9) | Apr 10, 2020 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [0248492e22](https://linux-hardware.org/?probe=0248492e22) | Apr 08, 2020 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [b19f7181b4](https://linux-hardware.org/?probe=b19f7181b4) | Apr 08, 2020 |
| HP            | Laptop 15-db0xxx            | [c4c866db0d](https://linux-hardware.org/?probe=c4c866db0d) | Apr 04, 2020 |
| HP            | Laptop 15-db0xxx            | [0bb263546b](https://linux-hardware.org/?probe=0bb263546b) | Apr 04, 2020 |
| ASUSTek       | X540YA                      | [2bfdde7714](https://linux-hardware.org/?probe=2bfdde7714) | Apr 03, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [f9921167fc](https://linux-hardware.org/?probe=f9921167fc) | Apr 02, 2020 |
| HP            | Mini 311-1100               | [d4918f7f3c](https://linux-hardware.org/?probe=d4918f7f3c) | Mar 27, 2020 |
| ASUSTek       | X455LD                      | [ec6c4486ca](https://linux-hardware.org/?probe=ec6c4486ca) | Mar 26, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | [60f3879e96](https://linux-hardware.org/?probe=60f3879e96) | Mar 25, 2020 |
| Acer          | Aspire 4750                 | [4757577c86](https://linux-hardware.org/?probe=4757577c86) | Mar 23, 2020 |
| ASUSTek       | K52JT                       | [38330a61d2](https://linux-hardware.org/?probe=38330a61d2) | Mar 23, 2020 |
| Lenovo        | ThinkPad T480 20L6S0VE00    | [4d090cecde](https://linux-hardware.org/?probe=4d090cecde) | Mar 22, 2020 |
| Toshiba       | Satellite C645              | [38d4ca1005](https://linux-hardware.org/?probe=38d4ca1005) | Mar 20, 2020 |
| HP            | Compaq Presario F700        | [912c22a4fd](https://linux-hardware.org/?probe=912c22a4fd) | Mar 20, 2020 |
| HP            | Compaq Presario F700        | [3a11fa91b5](https://linux-hardware.org/?probe=3a11fa91b5) | Mar 20, 2020 |
| HP            | ProBook 440 G6              | [d42c9c08ee](https://linux-hardware.org/?probe=d42c9c08ee) | Mar 19, 2020 |
| Apple         | MacBookPro8,3               | [1279383fb8](https://linux-hardware.org/?probe=1279383fb8) | Mar 17, 2020 |
| ASUSTek       | X505BP                      | [11da78a649](https://linux-hardware.org/?probe=11da78a649) | Mar 16, 2020 |
| Google        | Pantheon                    | [20acb09771](https://linux-hardware.org/?probe=20acb09771) | Mar 09, 2020 |
| Sony          | VGN-SR51MF_S                | [8783bf4fe5](https://linux-hardware.org/?probe=8783bf4fe5) | Mar 09, 2020 |
| HP            | Laptop 15-db0xxx            | [def3aa7871](https://linux-hardware.org/?probe=def3aa7871) | Mar 07, 2020 |
| ASUSTek       | X555QG                      | [6dccf0159e](https://linux-hardware.org/?probe=6dccf0159e) | Mar 07, 2020 |
| ASUSTek       | X555QG                      | [6ec6d9847c](https://linux-hardware.org/?probe=6ec6d9847c) | Mar 07, 2020 |
| ASUSTek       | X555QG                      | [e5c1b0bdce](https://linux-hardware.org/?probe=e5c1b0bdce) | Mar 07, 2020 |
| Lenovo        | IdeaPad Z470                | [20a4bdc803](https://linux-hardware.org/?probe=20a4bdc803) | Mar 05, 2020 |
| Lenovo        | IdeaPad Z470                | [b4898d9e36](https://linux-hardware.org/?probe=b4898d9e36) | Mar 05, 2020 |
| ASUSTek       | X505BP                      | [88ec1bf424](https://linux-hardware.org/?probe=88ec1bf424) | Feb 29, 2020 |
| Toshiba       | Satellite L305              | [fd8dfe766e](https://linux-hardware.org/?probe=fd8dfe766e) | Feb 24, 2020 |
| Toshiba       | Satellite L305              | [96c28903af](https://linux-hardware.org/?probe=96c28903af) | Feb 24, 2020 |
| HP            | Pavilion 10 TS              | [1ee504b68f](https://linux-hardware.org/?probe=1ee504b68f) | Feb 24, 2020 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | [c74cb1d856](https://linux-hardware.org/?probe=c74cb1d856) | Feb 22, 2020 |
| HP            | Laptop 14-bp0xx             | [303f2ada85](https://linux-hardware.org/?probe=303f2ada85) | Feb 19, 2020 |
| Lenovo        | ThinkPad SL500 27468XU      | [968045d52d](https://linux-hardware.org/?probe=968045d52d) | Feb 19, 2020 |
| HP            | Pavilion 10 TS              | [ed95aa0537](https://linux-hardware.org/?probe=ed95aa0537) | Feb 16, 2020 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | [d0276ea845](https://linux-hardware.org/?probe=d0276ea845) | Feb 14, 2020 |
| Acer          | Aspire A315-51              | [1d69448de6](https://linux-hardware.org/?probe=1d69448de6) | Feb 09, 2020 |
| Acer          | Aspire A315-51              | [6d4ecdb510](https://linux-hardware.org/?probe=6d4ecdb510) | Feb 09, 2020 |
| Lenovo        | ThinkPad SL500 27468XU      | [30b395a14f](https://linux-hardware.org/?probe=30b395a14f) | Feb 08, 2020 |
| Dell          | Vostro 3400                 | [7ad384214e](https://linux-hardware.org/?probe=7ad384214e) | Feb 06, 2020 |
| Apple         | MacBookPro11,1              | [b3a11d5f5d](https://linux-hardware.org/?probe=b3a11d5f5d) | Jan 20, 2020 |
| Unknown       | Unknown                     | [25f6d11655](https://linux-hardware.org/?probe=25f6d11655) | Jan 11, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [94b406a65f](https://linux-hardware.org/?probe=94b406a65f) | Jan 09, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [cf5b83db0d](https://linux-hardware.org/?probe=cf5b83db0d) | Jan 08, 2020 |
| ASUSTek       | X550ZE                      | [e06f76becf](https://linux-hardware.org/?probe=e06f76becf) | Jan 08, 2020 |
| HP            | Laptop 14-bp0xx             | [30389049c2](https://linux-hardware.org/?probe=30389049c2) | Jan 07, 2020 |
| ASUSTek       | X555YI                      | [06421a5c44](https://linux-hardware.org/?probe=06421a5c44) | Jan 05, 2020 |
| HP            | Laptop 15-db0xxx            | [db9c0c83ce](https://linux-hardware.org/?probe=db9c0c83ce) | Jan 03, 2020 |
| HP            | Laptop 14-bs0xx             | [854604bdad](https://linux-hardware.org/?probe=854604bdad) | Dec 31, 2019 |
| Dell          | Inspiron 5423               | [ed50d52b54](https://linux-hardware.org/?probe=ed50d52b54) | Dec 28, 2019 |
| Dell          | Inspiron 5423               | [5b5632e40c](https://linux-hardware.org/?probe=5b5632e40c) | Dec 28, 2019 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [b6846dfd95](https://linux-hardware.org/?probe=b6846dfd95) | Dec 28, 2019 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [75a94cfe2f](https://linux-hardware.org/?probe=75a94cfe2f) | Dec 28, 2019 |
| Dell          | Inspiron 5748               | [17ed1f4194](https://linux-hardware.org/?probe=17ed1f4194) | Dec 22, 2019 |
| HP            | Laptop 14-bp0xx             | [c99b71d804](https://linux-hardware.org/?probe=c99b71d804) | Dec 18, 2019 |
| Lenovo        | G40-45 80E1                 | [b1f6e07d2b](https://linux-hardware.org/?probe=b1f6e07d2b) | Dec 09, 2019 |
| HP            | Pavilion 10 TS              | [fbe754b72c](https://linux-hardware.org/?probe=fbe754b72c) | Nov 29, 2019 |
| Lenovo        | Flex 2-14D 20376            | [d78bbdfa2a](https://linux-hardware.org/?probe=d78bbdfa2a) | Nov 18, 2019 |
| Lenovo        | Flex 2-14D 20376            | [7e957006e4](https://linux-hardware.org/?probe=7e957006e4) | Nov 18, 2019 |
| HP            | Laptop 15-da0xxx            | [cb6e592c0d](https://linux-hardware.org/?probe=cb6e592c0d) | Nov 18, 2019 |
| ASUSTek       | 1005HA                      | [bd953e0701](https://linux-hardware.org/?probe=bd953e0701) | Nov 17, 2019 |
| ASUSTek       | X550DP                      | [9515caaefa](https://linux-hardware.org/?probe=9515caaefa) | Nov 17, 2019 |
| Lenovo        | IdeaPad 330S-14AST 81F8     | [4e2ba6330f](https://linux-hardware.org/?probe=4e2ba6330f) | Nov 09, 2019 |
| Lenovo        | ThinkPad E460 20EUA00900    | [a549aed5b4](https://linux-hardware.org/?probe=a549aed5b4) | Nov 08, 2019 |
| HP            | Laptop 14-bs0xx             | [36570780b5](https://linux-hardware.org/?probe=36570780b5) | Oct 30, 2019 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [5d4e6e95f1](https://linux-hardware.org/?probe=5d4e6e95f1) | Oct 30, 2019 |
| Dell          | XPS 15 9550                 | [7323abf391](https://linux-hardware.org/?probe=7323abf391) | Oct 29, 2019 |
| HP            | Laptop 14-bs0xx             | [4270a9638b](https://linux-hardware.org/?probe=4270a9638b) | Oct 29, 2019 |
| Dell          | XPS 15 9550                 | [c70f66f439](https://linux-hardware.org/?probe=c70f66f439) | Oct 29, 2019 |
| HP            | Laptop 15-db0xxx            | [666b6342e0](https://linux-hardware.org/?probe=666b6342e0) | Oct 29, 2019 |
| HP            | Laptop 15-db0xxx            | [36c76546e9](https://linux-hardware.org/?probe=36c76546e9) | Oct 29, 2019 |
| Lenovo        | IdeaPad 330S-14AST 81F8     | [3469bcd886](https://linux-hardware.org/?probe=3469bcd886) | Oct 28, 2019 |
| HP            | Laptop 14-bp0xx             | [2e6a129f3e](https://linux-hardware.org/?probe=2e6a129f3e) | Oct 24, 2019 |
| VIT           | P2412                       | [2604d0b890](https://linux-hardware.org/?probe=2604d0b890) | Oct 15, 2019 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [6206eb1a2f](https://linux-hardware.org/?probe=6206eb1a2f) | Oct 11, 2019 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [9a54660b4f](https://linux-hardware.org/?probe=9a54660b4f) | Oct 11, 2019 |
| Toshiba       | NB 105                      | [07f2ac3953](https://linux-hardware.org/?probe=07f2ac3953) | Oct 08, 2019 |
| Toshiba       | NB 105                      | [56d1fb0551](https://linux-hardware.org/?probe=56d1fb0551) | Oct 08, 2019 |
| ASUSTek       | X505BP                      | [147a0012a9](https://linux-hardware.org/?probe=147a0012a9) | Oct 08, 2019 |
| HP            | Pavilion 10 TS              | [f1d915aa56](https://linux-hardware.org/?probe=f1d915aa56) | Oct 06, 2019 |
| Acer          | Aspire E3-111               | [cb12dc0dcd](https://linux-hardware.org/?probe=cb12dc0dcd) | Sep 18, 2019 |
| Chuwi         | LapBook Plus                | [2cc2dc7812](https://linux-hardware.org/?probe=2cc2dc7812) | Sep 15, 2019 |
| Samsung       | 535U3C                      | [3605b4bcc2](https://linux-hardware.org/?probe=3605b4bcc2) | Sep 15, 2019 |
| Fujitsu       | LIFEBOOK T734               | [38a59cafac](https://linux-hardware.org/?probe=38a59cafac) | Sep 07, 2019 |
| Acer          | Aspire E1-571               | [f7809cd921](https://linux-hardware.org/?probe=f7809cd921) | Sep 06, 2019 |
| HP            | 240 G4 Notebook PC          | [c29c743021](https://linux-hardware.org/?probe=c29c743021) | Sep 06, 2019 |
| HP            | Laptop 15-db0xxx            | [47661b90c1](https://linux-hardware.org/?probe=47661b90c1) | Aug 31, 2019 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Colombia/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 89        | 10.87%  |
| Ubuntu 18.04       | 68        | 8.3%    |
| Ubuntu 22.04       | 59        | 7.2%    |
| OpenMandriva 4.3   | 23        | 2.81%   |
| Fedora 38          | 23        | 2.81%   |
| Debian 11          | 16        | 1.95%   |
| Zorin 16           | 14        | 1.71%   |
| Arch Rolling       | 14        | 1.71%   |
| Linux Mint 21.1    | 12        | 1.47%   |
| Ubuntu 19.04       | 11        | 1.34%   |
| OpenMandriva 4.2   | 11        | 1.34%   |
| KDE neon 20.04     | 11        | 1.34%   |
| OpenMandriva 23.01 | 10        | 1.22%   |
| Linux Mint 20.3    | 10        | 1.22%   |
| Arch               | 10        | 1.22%   |
| Pop!_OS 22.04      | 9         | 1.1%    |
| Manjaro            | 9         | 1.1%    |
| Linux Mint 21.2    | 9         | 1.1%    |
| Fedora 39          | 9         | 1.1%    |
| OpenMandriva 23.03 | 8         | 0.98%   |
| Fedora 34          | 8         | 0.98%   |
| Debian 12          | 8         | 0.98%   |
| Zorin 15           | 7         | 0.85%   |
| Ubuntu 20.10       | 7         | 0.85%   |
| Ubuntu 19.10       | 7         | 0.85%   |
| ROSA R10           | 7         | 0.85%   |
| Linux Mint 20.1    | 7         | 0.85%   |
| Linux Mint 19.3    | 7         | 0.85%   |
| Fedora 36          | 7         | 0.85%   |
| Pop!_OS 20.04      | 6         | 0.73%   |
| OpenMandriva 23.08 | 6         | 0.73%   |
| KDE neon 22.04     | 6         | 0.73%   |
| Debian 10          | 6         | 0.73%   |
| Ubuntu 23.04       | 5         | 0.61%   |
| Ubuntu 21.04       | 5         | 0.61%   |
| Linux Mint 20.2    | 5         | 0.61%   |
| Linux Mint 20      | 5         | 0.61%   |
| Kubuntu 20.04      | 5         | 0.61%   |
| Fedora 37          | 5         | 0.61%   |
| Fedora 33          | 5         | 0.61%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 253       | 32.69%  |
| Fedora        | 64        | 8.27%   |
| Endless       | 64        | 8.27%   |
| Linux Mint    | 63        | 8.14%   |
| OpenMandriva  | 57        | 7.36%   |
| Debian        | 36        | 4.65%   |
| Manjaro       | 25        | 3.23%   |
| Arch          | 24        | 3.1%    |
| Pop!_OS       | 22        | 2.84%   |
| Zorin         | 21        | 2.71%   |
| KDE neon      | 18        | 2.33%   |
| ROSA          | 15        | 1.94%   |
| Kubuntu       | 14        | 1.81%   |
| Xubuntu       | 12        | 1.55%   |
| Kali          | 9         | 1.16%   |
| Elementary    | 8         | 1.03%   |
| ArcoLinux     | 7         | 0.9%    |
| openSUSE      | 6         | 0.78%   |
| Lubuntu       | 6         | 0.78%   |
| Ubuntu Unity  | 5         | 0.65%   |
| Garuda Linux  | 4         | 0.52%   |
| EndeavourOS   | 4         | 0.52%   |
| Ubuntu Budgie | 3         | 0.39%   |
| Nobara        | 3         | 0.39%   |
| MX            | 3         | 0.39%   |
| Clear Linux   | 3         | 0.39%   |
| RHEL          | 2         | 0.26%   |
| Parrot        | 2         | 0.26%   |
| Lilidog       | 2         | 0.26%   |
| Artix         | 2         | 0.26%   |
| Xero          | 1         | 0.13%   |
| Void Linux    | 1         | 0.13%   |
| UbuntuDDE     | 1         | 0.13%   |
| Ubuntu MATE   | 1         | 0.13%   |
| Sparky        | 1         | 0.13%   |
| Reborn OS     | 1         | 0.13%   |
| NixOS         | 1         | 0.13%   |
| Mageia        | 1         | 0.13%   |
| LinuxFX       | 1         | 0.13%   |
| Linux Lite    | 1         | 0.13%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 23        | 2.65%   |
| 5.4.0-42-generic         | 19        | 2.19%   |
| 5.8.0-14-generic         | 12        | 1.38%   |
| 5.4.0-19-generic         | 11        | 1.27%   |
| 5.10.14-desktop-1omv4002 | 11        | 1.27%   |
| 6.1.1-desktop-1omv2290   | 10        | 1.15%   |
| 5.4.0-58-generic         | 10        | 1.15%   |
| 6.2.6-desktop-1omv2390   | 8         | 0.92%   |
| 5.3.0-46-generic         | 7         | 0.81%   |
| 5.15.0-47-generic        | 7         | 0.81%   |
| 5.11.0-35-generic        | 7         | 0.81%   |
| 6.2.0-26-generic         | 6         | 0.69%   |
| 5.4.0-48-generic         | 6         | 0.69%   |
| 5.3.0-28-generic         | 6         | 0.69%   |
| 5.15.0-88-generic        | 6         | 0.69%   |
| 5.15.0-48-generic        | 6         | 0.69%   |
| 4.18.0-25-generic        | 6         | 0.69%   |
| 4.18.0-15-generic        | 6         | 0.69%   |
| 6.4.11-desktop-1omv2390  | 5         | 0.58%   |
| 5.8.0-43-generic         | 5         | 0.58%   |
| 5.4.0-31-generic         | 5         | 0.58%   |
| 5.3.0-40-generic         | 5         | 0.58%   |
| 5.19.0-46-generic        | 5         | 0.58%   |
| 5.15.0-58-generic        | 5         | 0.58%   |
| 5.15.0-50-generic        | 5         | 0.58%   |
| 5.13.0-40-generic        | 5         | 0.58%   |
| 5.0.0-37-generic         | 5         | 0.58%   |
| 5.0.0-25-generic         | 5         | 0.58%   |
| 6.4.14-200.fc38.x86_64   | 4         | 0.46%   |
| 6.2.0-37-generic         | 4         | 0.46%   |
| 6.1.0-13-amd64           | 4         | 0.46%   |
| 5.8.0-59-generic         | 4         | 0.46%   |
| 5.8.0-44-generic         | 4         | 0.46%   |
| 5.4.0-65-generic         | 4         | 0.46%   |
| 5.4.0-64-generic         | 4         | 0.46%   |
| 5.4.0-54-generic         | 4         | 0.46%   |
| 5.4.0-37-generic         | 4         | 0.46%   |
| 5.4.0-26-generic         | 4         | 0.46%   |
| 5.15.0-91-generic        | 4         | 0.46%   |
| 5.15.0-76-generic        | 4         | 0.46%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 119       | 14.15%  |
| 5.15.0  | 81        | 9.63%   |
| 4.15.0  | 44        | 5.23%   |
| 5.8.0   | 41        | 4.88%   |
| 5.3.0   | 39        | 4.64%   |
| 5.11.0  | 34        | 4.04%   |
| 5.0.0   | 33        | 3.92%   |
| 6.2.0   | 27        | 3.21%   |
| 4.18.0  | 27        | 3.21%   |
| 5.13.0  | 26        | 3.09%   |
| 5.16.7  | 23        | 2.73%   |
| 5.19.0  | 19        | 2.26%   |
| 5.10.0  | 18        | 2.14%   |
| 6.1.0   | 13        | 1.55%   |
| 6.5.0   | 11        | 1.31%   |
| 5.10.14 | 11        | 1.31%   |
| 6.1.1   | 10        | 1.19%   |
| 6.2.6   | 8         | 0.95%   |
| 4.19.0  | 6         | 0.71%   |
| 6.4.11  | 5         | 0.59%   |
| 4.9.60  | 5         | 0.59%   |
| 6.6.2   | 4         | 0.48%   |
| 6.5.6   | 4         | 0.48%   |
| 6.5.5   | 4         | 0.48%   |
| 6.4.14  | 4         | 0.48%   |
| 5.14.0  | 4         | 0.48%   |
| 4.13.0  | 4         | 0.48%   |
| 6.5.7   | 3         | 0.36%   |
| 6.4.8   | 3         | 0.36%   |
| 6.3.5   | 3         | 0.36%   |
| 6.2.9   | 3         | 0.36%   |
| 6.2.11  | 3         | 0.36%   |
| 6.1.5   | 3         | 0.36%   |
| 5.9.16  | 3         | 0.36%   |
| 5.18.10 | 3         | 0.36%   |
| 5.1.0   | 3         | 0.36%   |
| 4.9.0   | 3         | 0.36%   |
| 4.4.0   | 3         | 0.36%   |
| 6.6.9   | 2         | 0.24%   |
| 6.6.6   | 2         | 0.24%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 123       | 14.82%  |
| 5.15    | 91        | 10.96%  |
| 5.8     | 45        | 5.42%   |
| 6.2     | 44        | 5.3%    |
| 4.15    | 44        | 5.3%    |
| 5.3     | 43        | 5.18%   |
| 5.10    | 42        | 5.06%   |
| 5.11    | 39        | 4.7%    |
| 6.1     | 37        | 4.46%   |
| 5.13    | 36        | 4.34%   |
| 5.0     | 34        | 4.1%    |
| 6.5     | 29        | 3.49%   |
| 4.18    | 28        | 3.37%   |
| 5.16    | 26        | 3.13%   |
| 5.19    | 24        | 2.89%   |
| 6.4     | 23        | 2.77%   |
| 4.9     | 12        | 1.45%   |
| 6.6     | 11        | 1.33%   |
| 5.6     | 10        | 1.2%    |
| 6.3     | 9         | 1.08%   |
| 6.0     | 9         | 1.08%   |
| 5.18    | 9         | 1.08%   |
| 5.17    | 9         | 1.08%   |
| 5.9     | 8         | 0.96%   |
| 5.14    | 7         | 0.84%   |
| 4.19    | 7         | 0.84%   |
| 5.7     | 6         | 0.72%   |
| 5.5     | 4         | 0.48%   |
| 5.12    | 4         | 0.48%   |
| 4.13    | 4         | 0.48%   |
| 5.1     | 3         | 0.36%   |
| 4.4     | 3         | 0.36%   |
| 6.7     | 1         | 0.12%   |
| 5.2     | 1         | 0.12%   |
| 4.20    | 1         | 0.12%   |
| 4.14    | 1         | 0.12%   |
| 4.12    | 1         | 0.12%   |
| 4.10    | 1         | 0.12%   |
| 4.1     | 1         | 0.12%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 726       | 97.84%  |
| i686   | 16        | 2.16%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 383       | 49.68%  |
| KDE5             | 119       | 15.43%  |
| Unknown          | 95        | 12.32%  |
| XFCE             | 54        | 7%      |
| X-Cinnamon       | 42        | 5.45%   |
| KDE              | 18        | 2.33%   |
| MATE             | 10        | 1.3%    |
| Pantheon         | 8         | 1.04%   |
| KDE4             | 8         | 1.04%   |
| Budgie           | 6         | 0.78%   |
| Unity            | 5         | 0.65%   |
| LXQt             | 5         | 0.65%   |
| Cinnamon         | 5         | 0.65%   |
| LXDE             | 3         | 0.39%   |
| lightdm-xsession | 2         | 0.26%   |
| Deepin           | 2         | 0.26%   |
| bspwm            | 2         | 0.26%   |
| ICEWM            | 1         | 0.13%   |
| GNOME Classic    | 1         | 0.13%   |
| dwm              | 1         | 0.13%   |
| awesome          | 1         | 0.13%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 541       | 70.72%  |
| Wayland | 153       | 20%     |
| Unknown | 67        | 8.76%   |
| Tty     | 4         | 0.52%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 415       | 54.18%  |
| SDDM    | 101       | 13.19%  |
| GDM3    | 97        | 12.66%  |
| LightDM | 65        | 8.49%   |
| GDM     | 65        | 8.49%   |
| TDM     | 14        | 1.83%   |
| KDM     | 8         | 1.04%   |
| LXDM    | 1         | 0.13%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Notebooks | Percent |
|------------|-----------|---------|
| es_CO      | 356       | 46.48%  |
| en_US      | 209       | 27.28%  |
| Unknown    | 101       | 13.19%  |
| es_ES      | 48        | 6.27%   |
| es_MX      | 24        | 3.13%   |
| en_GB      | 4         | 0.52%   |
| C          | 4         | 0.52%   |
| es_PE      | 3         | 0.39%   |
| es_VE      | 2         | 0.26%   |
| es_EC      | 2         | 0.26%   |
| pt_PT      | 1         | 0.13%   |
| pl_PL      | 1         | 0.13%   |
| it_IT      | 1         | 0.13%   |
| fr_FR      | 1         | 0.13%   |
| es_US      | 1         | 0.13%   |
| es_ES.UTF8 | 1         | 0.13%   |
| es_DO      | 1         | 0.13%   |
| es_CO.UTF8 | 1         | 0.13%   |
| es_CL      | 1         | 0.13%   |
| es_AR      | 1         | 0.13%   |
| en_AU      | 1         | 0.13%   |
| en         | 1         | 0.13%   |
| de_DE      | 1         | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 435       | 57.24%  |
| BIOS | 325       | 42.76%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 567       | 74.02%  |
| Btrfs   | 71        | 9.27%   |
| Overlay | 52        | 6.79%   |
| Unknown | 38        | 4.96%   |
| Tmpfs   | 20        | 2.61%   |
| Xfs     | 12        | 1.57%   |
| Zfs     | 4         | 0.52%   |
| F2fs    | 1         | 0.13%   |
| Ext2    | 1         | 0.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 444       | 58.73%  |
| GPT     | 245       | 32.41%  |
| MBR     | 67        | 8.86%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 672       | 88.77%  |
| Yes       | 85        | 11.23%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 526       | 69.58%  |
| Yes       | 230       | 30.42%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| ASUSTek Computer             | 168       | 22.64%  |
| Hewlett-Packard              | 159       | 21.43%  |
| Lenovo                       | 148       | 19.95%  |
| Dell                         | 71        | 9.57%   |
| Acer                         | 64        | 8.63%   |
| Toshiba                      | 29        | 3.91%   |
| Apple                        | 19        | 2.56%   |
| Samsung Electronics          | 13        | 1.75%   |
| Sony                         | 12        | 1.62%   |
| MSI                          | 12        | 1.62%   |
| HUAWEI                       | 12        | 1.62%   |
| Notebook                     | 5         | 0.67%   |
| Compumax Computer            | 5         | 0.67%   |
| Unknown                      | 4         | 0.54%   |
| PCSMART                      | 3         | 0.4%    |
| Google                       | 2         | 0.27%   |
| Gateway                      | 2         | 0.27%   |
| VIT                          | 1         | 0.13%   |
| Timi                         | 1         | 0.13%   |
| PCSMART S.A.S.               | 1         | 0.13%   |
| MPS Mayorista de Colombia SA | 1         | 0.13%   |
| Lanix                        | 1         | 0.13%   |
| Inspur                       | 1         | 0.13%   |
| GreatWall                    | 1         | 0.13%   |
| Fujitsu Siemens              | 1         | 0.13%   |
| Fujitsu                      | 1         | 0.13%   |
| Framework                    | 1         | 0.13%   |
| COMPUMAX COMPUTER S.A.S.     | 1         | 0.13%   |
| COIN COMPUTERS               | 1         | 0.13%   |
| Chuwi                        | 1         | 0.13%   |
| BAKED                        | 1         | 0.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| HP Laptop 15-db0xxx                     | 12        | 1.62%   |
| Lenovo IdeaPad 320-15ABR 80XS           | 6         | 0.81%   |
| HP Pavilion Gaming Laptop 15-cx0xxx     | 6         | 0.81%   |
| HP Notebook                             | 6         | 0.81%   |
| Samsung 300E4C/300E5C/300E7C            | 5         | 0.67%   |
| HP Laptop 14-cm1xxx                     | 5         | 0.67%   |
| HP Laptop 14-bs0xx                      | 5         | 0.67%   |
| Compumax ONIX-CEL-0001                  | 5         | 0.67%   |
| ASUS VivoBook_ASUS Laptop X505ZA_X505ZA | 5         | 0.67%   |
| Acer Aspire 4750                        | 5         | 0.67%   |
| Unknown                                 | 5         | 0.67%   |
| Lenovo IdeaPad S340-14API 81NB          | 4         | 0.54%   |
| Lenovo IdeaPad 110-14IBR 80T6           | 4         | 0.54%   |
| Lenovo G40-45 80E1                      | 4         | 0.54%   |
| HP ProBook 440 G7                       | 4         | 0.54%   |
| HP Laptop 15-ef2xxx                     | 4         | 0.54%   |
| HP Laptop 15-da0xxx                     | 4         | 0.54%   |
| HP 245 G6                               | 4         | 0.54%   |
| HP 14                                   | 4         | 0.54%   |
| Dell XPS 15 9550                        | 4         | 0.54%   |
| Dell Vostro 3400                        | 4         | 0.54%   |
| ASUS ZenBook UX431DA_UM431DA            | 4         | 0.54%   |
| ASUS X455LJ                             | 4         | 0.54%   |
| ASUS VivoBook_ASUSLaptop X512FB_X512FB  | 4         | 0.54%   |
| ASUS VivoBook_ASUSLaptop X415JA_X415JA  | 4         | 0.54%   |
| Acer Nitro AN515-55                     | 4         | 0.54%   |
| Lenovo IdeaPad 5 14ALC05 82LM           | 3         | 0.4%    |
| Lenovo IdeaPad 3 15ALC6 82KU            | 3         | 0.4%    |
| Lenovo G40-80 80E4                      | 3         | 0.4%    |
| HUAWEI NBLB-WAX9N                       | 3         | 0.4%    |
| HUAWEI BOHB-WAX9                        | 3         | 0.4%    |
| HP ProBook 450 G1                       | 3         | 0.4%    |
| HP Pavilion Notebook                    | 3         | 0.4%    |
| HP G42                                  | 3         | 0.4%    |
| HP ENVY 15                              | 3         | 0.4%    |
| HP 245 G7 Notebook PC                   | 3         | 0.4%    |
| Dell Inspiron N4010                     | 3         | 0.4%    |
| Dell Inspiron 1420                      | 3         | 0.4%    |
| ASUS X555QG                             | 3         | 0.4%    |
| ASUS X550DP                             | 3         | 0.4%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| ASUS VivoBook          | 74        | 9.97%   |
| Lenovo IdeaPad         | 64        | 8.63%   |
| HP Laptop              | 43        | 5.8%    |
| Acer Aspire            | 43        | 5.8%    |
| Lenovo ThinkPad        | 42        | 5.66%   |
| HP Pavilion            | 30        | 4.04%   |
| Dell Inspiron          | 28        | 3.77%   |
| Toshiba Satellite      | 24        | 3.23%   |
| HP ProBook             | 22        | 2.96%   |
| Dell Latitude          | 16        | 2.16%   |
| HP 245                 | 11        | 1.48%   |
| Dell Vostro            | 10        | 1.35%   |
| ASUS ZenBook           | 10        | 1.35%   |
| Acer Nitro             | 9         | 1.21%   |
| HP EliteBook           | 7         | 0.94%   |
| HP Compaq              | 7         | 0.94%   |
| Dell XPS               | 7         | 0.94%   |
| HP Notebook            | 6         | 0.81%   |
| HP 240                 | 6         | 0.81%   |
| ASUS TUF               | 6         | 0.81%   |
| Samsung 300E4C         | 5         | 0.67%   |
| Compumax ONIX-CEL-0001 | 5         | 0.67%   |
| Unknown                | 5         | 0.67%   |
| Lenovo ThinkBook       | 4         | 0.54%   |
| Lenovo G40-45          | 4         | 0.54%   |
| HP Presario            | 4         | 0.54%   |
| HP 14                  | 4         | 0.54%   |
| Dell Precision         | 4         | 0.54%   |
| ASUS X455LJ            | 4         | 0.54%   |
| ASUS ROG               | 4         | 0.54%   |
| Acer TravelMate        | 4         | 0.54%   |
| Lenovo Legion          | 3         | 0.4%    |
| Lenovo IdeaPadFlex     | 3         | 0.4%    |
| Lenovo G40-80          | 3         | 0.4%    |
| HUAWEI NBLB-WAX9N      | 3         | 0.4%    |
| HUAWEI BOHB-WAX9       | 3         | 0.4%    |
| HP G42                 | 3         | 0.4%    |
| HP ENVY                | 3         | 0.4%    |
| Dell System            | 3         | 0.4%    |
| ASUS X555QG            | 3         | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 90        | 12.13%  |
| 2018 | 70        | 9.43%   |
| 2017 | 68        | 9.16%   |
| 2020 | 67        | 9.03%   |
| 2021 | 59        | 7.95%   |
| 2012 | 51        | 6.87%   |
| 2014 | 50        | 6.74%   |
| 2015 | 46        | 6.2%    |
| 2013 | 45        | 6.06%   |
| 2010 | 43        | 5.8%    |
| 2011 | 41        | 5.53%   |
| 2016 | 29        | 3.91%   |
| 2009 | 27        | 3.64%   |
| 2008 | 20        | 2.7%    |
| 2022 | 13        | 1.75%   |
| 2007 | 12        | 1.62%   |
| 2023 | 8         | 1.08%   |
| 2006 | 3         | 0.4%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 742       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 655       | 87.8%   |
| Enabled  | 91        | 12.2%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 740       | 99.73%  |
| Yes  | 2         | 0.27%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 257       | 34.18%  |
| 3.01-4.0    | 192       | 25.53%  |
| 8.01-16.0   | 139       | 18.48%  |
| 16.01-24.0  | 76        | 10.11%  |
| 1.01-2.0    | 30        | 3.99%   |
| 2.01-3.0    | 23        | 3.06%   |
| 32.01-64.0  | 20        | 2.66%   |
| 24.01-32.0  | 8         | 1.06%   |
| 0.51-1.0    | 6         | 0.8%    |
| 64.01-256.0 | 1         | 0.13%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 267       | 32.76%  |
| 2.01-3.0   | 253       | 31.04%  |
| 3.01-4.0   | 119       | 14.6%   |
| 4.01-8.0   | 104       | 12.76%  |
| 0.51-1.0   | 44        | 5.4%    |
| 8.01-16.0  | 25        | 3.07%   |
| 0.01-0.5   | 2         | 0.25%   |
| 24.01-32.0 | 1         | 0.12%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 606       | 80.59%  |
| 2      | 134       | 17.82%  |
| 3      | 10        | 1.33%   |
| 4      | 2         | 0.27%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 503       | 67.52%  |
| Yes       | 242       | 32.48%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 582       | 78.12%  |
| No        | 163       | 21.88%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 737       | 99.19%  |
| No        | 6         | 0.81%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 605       | 81.21%  |
| No        | 140       | 18.79%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Notebooks | Percent |
|----------|-----------|---------|
| Colombia | 742       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Bogotá          | 299       | 38.09%  |
| Medellín        | 106       | 13.5%   |
| Santiago de Cali | 68        | 8.66%   |
| Barranquilla     | 38        | 4.84%   |
| Bucaramanga      | 28        | 3.57%   |
| Pereira          | 24        | 3.06%   |
| Cartagena        | 20        | 2.55%   |
| Manizales        | 15        | 1.91%   |
| Villavicencio    | 10        | 1.27%   |
| Popayán         | 10        | 1.27%   |
| Ibague           | 8         | 1.02%   |
| Envigado         | 8         | 1.02%   |
| Cúcuta          | 8         | 1.02%   |
| Tunja            | 7         | 0.89%   |
| Fusagasuga       | 7         | 0.89%   |
| Santa Marta      | 6         | 0.76%   |
| Neiva            | 6         | 0.76%   |
| Armenia          | 6         | 0.76%   |
| Montería        | 5         | 0.64%   |
| Bello            | 5         | 0.64%   |
| Yopal            | 4         | 0.51%   |
| Pasto            | 4         | 0.51%   |
| Madrid           | 4         | 0.51%   |
| Chia             | 4         | 0.51%   |
| Valledupar       | 3         | 0.38%   |
| Sincelejo        | 3         | 0.38%   |
| Rionegro         | 3         | 0.38%   |
| Lorica           | 3         | 0.38%   |
| Floridablanca    | 3         | 0.38%   |
| Sogamoso         | 2         | 0.25%   |
| Soacha           | 2         | 0.25%   |
| Sabaneta         | 2         | 0.25%   |
| Puerto Boyacá   | 2         | 0.25%   |
| Palmira          | 2         | 0.25%   |
| Mosquera         | 2         | 0.25%   |
| Los Patios       | 2         | 0.25%   |
| La Estrella      | 2         | 0.25%   |
| Itaguei          | 2         | 0.25%   |
| Ipiales          | 2         | 0.25%   |
| Funza            | 2         | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 152       | 191    | 17.23%  |
| Toshiba                     | 115       | 135    | 13.04%  |
| WDC                         | 108       | 130    | 12.24%  |
| Samsung Electronics         | 60        | 73     | 6.8%    |
| Kingston                    | 58        | 71     | 6.58%   |
| SanDisk                     | 52        | 64     | 5.9%    |
| Crucial                     | 41        | 47     | 4.65%   |
| HGST                        | 36        | 45     | 4.08%   |
| A-DATA Technology           | 31        | 36     | 3.51%   |
| Intel                       | 29        | 33     | 3.29%   |
| SK hynix                    | 25        | 30     | 2.83%   |
| Unknown                     | 24        | 25     | 2.72%   |
| Hitachi                     | 24        | 28     | 2.72%   |
| Micron Technology           | 19        | 20     | 2.15%   |
| China                       | 12        | 12     | 1.36%   |
| Apple                       | 12        | 19     | 1.36%   |
| Realtek Semiconductor       | 8         | 9      | 0.91%   |
| KIOXIA                      | 7         | 8      | 0.79%   |
| Silicon Motion              | 6         | 10     | 0.68%   |
| JMicron Technology          | 5         | 5      | 0.57%   |
| Fujitsu                     | 5         | 5      | 0.57%   |
| Phison                      | 4         | 6      | 0.45%   |
| Kingston Technology Company | 4         | 7      | 0.45%   |
| Micron/Crucial Technology   | 3         | 3      | 0.34%   |
| LITEONIT                    | 3         | 3      | 0.34%   |
| Lexar                       | 3         | 3      | 0.34%   |
| Hewlett-Packard             | 3         | 4      | 0.34%   |
| Gigabyte Technology         | 3         | 3      | 0.34%   |
| Union Memory                | 2         | 2      | 0.23%   |
| SPCC                        | 2         | 6      | 0.23%   |
| Netac                       | 2         | 2      | 0.23%   |
| LITEON                      | 2         | 3      | 0.23%   |
| Zheino                      | 1         | 1      | 0.11%   |
| XrayDisk                    | 1         | 1      | 0.11%   |
| XPG                         | 1         | 1      | 0.11%   |
| USB3.0                      | 1         | 1      | 0.11%   |
| Union Memory (Shenzhen)     | 1         | 1      | 0.11%   |
| Transcend                   | 1         | 1      | 0.11%   |
| SSSTC                       | 1         | 1      | 0.11%   |
| SSK                         | 1         | 1      | 0.11%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB         | 45        | 5.02%   |
| Toshiba MQ04ABF100 1TB                 | 38        | 4.24%   |
| Toshiba MQ01ABF050 500GB               | 22        | 2.45%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 22        | 2.45%   |
| Toshiba MQ01ABD100 1TB                 | 19        | 2.12%   |
| Seagate ST500LT012-1DG142 500GB        | 14        | 1.56%   |
| Kingston SA400S37240G 240GB SSD        | 13        | 1.45%   |
| Crucial CT240BX500SSD1 240GB           | 11        | 1.23%   |
| WDC WD10SPZX-60Z10T0 1TB               | 9         | 1%      |
| Intel SSDPEKNU512GZ 512GB              | 9         | 1%      |
| HGST HTS541010A9E680 1TB               | 9         | 1%      |
| Crucial CT1000BX500SSD1 1TB            | 9         | 1%      |
| Seagate ST500LT012-9WS142 500GB        | 8         | 0.89%   |
| Seagate ST2000LM007-1R8174 2TB         | 8         | 0.89%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB   | 8         | 0.89%   |
| HGST HTS541010B7E610 1TB               | 8         | 0.89%   |
| WDC WD10SPZX-24Z10 1TB                 | 7         | 0.78%   |
| SanDisk NVMe SSD Drive 512GB           | 7         | 0.78%   |
| Kingston SA400S37480G 480GB SSD        | 7         | 0.78%   |
| HGST HTS545050A7E680 500GB             | 7         | 0.78%   |
| SanDisk NVMe SSD Drive 256GB           | 6         | 0.67%   |
| A-DATA SU650 120GB SSD                 | 6         | 0.67%   |
| WDC WD10JPCX-24UE4T0 1TB               | 5         | 0.56%   |
| Unknown MMC Card  64GB                 | 5         | 0.56%   |
| Seagate ST9500325AS 500GB              | 5         | 0.56%   |
| Seagate ST500LM030-1RK17D 500GB        | 5         | 0.56%   |
| SanDisk NVMe SSD Drive 1TB             | 5         | 0.56%   |
| Kingston SA400S37120G 120GB SSD        | 5         | 0.56%   |
| Intel NVMe SSD Drive 512GB             | 5         | 0.56%   |
| Crucial CT500MX500SSD1 500GB           | 5         | 0.56%   |
| Crucial CT480BX500SSD1 480GB           | 5         | 0.56%   |
| A-DATA SU630 480GB SSD                 | 5         | 0.56%   |
| WDC WD5000LPZX-22Z10T0 500GB           | 4         | 0.45%   |
| WDC WD1600BEVT-75ZCT2 160GB            | 4         | 0.45%   |
| Unknown MMC Card  32GB                 | 4         | 0.45%   |
| SK hynix NVMe SSD Drive 256GB          | 4         | 0.45%   |
| Seagate ST9500420AS 500GB              | 4         | 0.45%   |
| Seagate ST750LM022 HN-M750MBB 752GB    | 4         | 0.45%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB | 4         | 0.45%   |
| JMicron Generic 8GB                    | 4         | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 152       | 189    | 35.1%   |
| Toshiba             | 109       | 127    | 25.17%  |
| WDC                 | 90        | 110    | 20.79%  |
| HGST                | 36        | 45     | 8.31%   |
| Hitachi             | 24        | 28     | 5.54%   |
| Samsung Electronics | 6         | 6      | 1.39%   |
| Fujitsu             | 5         | 5      | 1.15%   |
| JMicron Technology  | 4         | 4      | 0.92%   |
| Apple               | 3         | 6      | 0.69%   |
| Unknown             | 2         | 2      | 0.46%   |
| Phison              | 1         | 2      | 0.23%   |
| Inateck             | 1         | 1      | 0.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 45        | 54     | 21.53%  |
| Crucial             | 34        | 40     | 16.27%  |
| A-DATA Technology   | 27        | 32     | 12.92%  |
| Samsung Electronics | 23        | 27     | 11%     |
| SanDisk             | 16        | 17     | 7.66%   |
| China               | 11        | 11     | 5.26%   |
| Apple               | 6         | 6      | 2.87%   |
| Toshiba             | 5         | 6      | 2.39%   |
| Intel               | 5         | 6      | 2.39%   |
| Micron Technology   | 4         | 4      | 1.91%   |
| WDC                 | 3         | 3      | 1.44%   |
| SK hynix            | 3         | 6      | 1.44%   |
| LITEONIT            | 3         | 3      | 1.44%   |
| Lexar               | 3         | 3      | 1.44%   |
| Gigabyte Technology | 3         | 3      | 1.44%   |
| SPCC                | 2         | 6      | 0.96%   |
| LITEON              | 2         | 3      | 0.96%   |
| Zheino              | 1         | 1      | 0.48%   |
| XrayDisk            | 1         | 1      | 0.48%   |
| USB3.0              | 1         | 1      | 0.48%   |
| Transcend           | 1         | 1      | 0.48%   |
| Seagate             | 1         | 2      | 0.48%   |
| SATAFIRM            | 1         | 1      | 0.48%   |
| PNY                 | 1         | 1      | 0.48%   |
| Patriot             | 1         | 1      | 0.48%   |
| Netac               | 1         | 1      | 0.48%   |
| KingSpec            | 1         | 1      | 0.48%   |
| HS-SSD-C100         | 1         | 1      | 0.48%   |
| Hised               | 1         | 2      | 0.48%   |
| Hewlett-Packard     | 1         | 1      | 0.48%   |
| DTECHCO             | 1         | 1      | 0.48%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 422       | 525    | 49.41%  |
| NVMe    | 202       | 260    | 23.65%  |
| SSD     | 201       | 246    | 23.54%  |
| MMC     | 22        | 23     | 2.58%   |
| Unknown | 7         | 8      | 0.82%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 570       | 760    | 70.02%  |
| NVMe | 202       | 258    | 24.82%  |
| MMC  | 22        | 23     | 2.7%    |
| SAS  | 20        | 21     | 2.46%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 362       | 466    | 59.25%  |
| 0.51-1.0   | 237       | 285    | 38.79%  |
| 1.01-2.0   | 11        | 18     | 1.8%    |
| 0          | 1         | 2      | 0.16%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 228       | 29.16%  |
| 101-250        | 210       | 26.85%  |
| 501-1000       | 153       | 19.57%  |
| 1-20           | 58        | 7.42%   |
| 51-100         | 46        | 5.88%   |
| 21-50          | 35        | 4.48%   |
| 1001-2000      | 33        | 4.22%   |
| More than 3000 | 7         | 0.9%    |
| Unknown        | 7         | 0.9%    |
| 2001-3000      | 5         | 0.64%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 332       | 40.74%  |
| 21-50     | 182       | 22.33%  |
| 101-250   | 113       | 13.87%  |
| 51-100    | 94        | 11.53%  |
| 251-500   | 50        | 6.13%   |
| 501-1000  | 33        | 4.05%   |
| Unknown   | 7         | 0.86%   |
| 1001-2000 | 4         | 0.49%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB             | 4         | 4      | 6.45%   |
| A-DATA Technology SU630 480GB SSD              | 3         | 4      | 4.84%   |
| Seagate ST9500420AS 500GB                      | 2         | 2      | 3.23%   |
| Seagate ST9500325AS 500GB                      | 2         | 2      | 3.23%   |
| Seagate ST9320423AS 320GB                      | 2         | 2      | 3.23%   |
| Seagate ST500LT012-9WS142 500GB                | 2         | 2      | 3.23%   |
| WDC WD5000BPVT-22HXZT3 500GB                   | 1         | 1      | 1.61%   |
| WDC WD5000BEVT-22A0RT0 500GB                   | 1         | 1      | 1.61%   |
| WDC WD3200BPVT-24JJ5T0 320GB                   | 1         | 1      | 1.61%   |
| WDC WD3200BEKT-60F3T1 320GB                    | 1         | 1      | 1.61%   |
| WDC WD1600BEVT-22A23T0 160GB                   | 1         | 1      | 1.61%   |
| WDC WD1600BEKT-60V5T1 160GB                    | 1         | 1      | 1.61%   |
| WDC WD10SPZX-60Z10T1 1TB                       | 1         | 1      | 1.61%   |
| WDC WD10SPCX-24HWST1 1TB                       | 1         | 1      | 1.61%   |
| Toshiba MQ04ABF100 1TB                         | 1         | 2      | 1.61%   |
| Toshiba MQ01ABF050 500GB                       | 1         | 1      | 1.61%   |
| Toshiba MQ01ABD100 1TB                         | 1         | 1      | 1.61%   |
| Toshiba MK7559GSXP 752GB                       | 1         | 1      | 1.61%   |
| Toshiba MK5076GSX 500GB                        | 1         | 1      | 1.61%   |
| Toshiba MK5065GSXN 500GB                       | 1         | 1      | 1.61%   |
| Toshiba MK3263GSX 320GB                        | 1         | 1      | 1.61%   |
| Toshiba HDWL110 1TB                            | 1         | 1      | 1.61%   |
| SK hynix BC711 HFM256GD3JX013N 256GB           | 1         | 1      | 1.61%   |
| Seagate ST9320325AS 320GB                      | 1         | 1      | 1.61%   |
| Seagate ST750LM022 HN-M750MBB 752GB            | 1         | 1      | 1.61%   |
| Seagate ST500LX012-1LM162-SSHD 500GB           | 1         | 1      | 1.61%   |
| Seagate ST500LT012-1DG142 500GB                | 1         | 1      | 1.61%   |
| Seagate ST500LM021-1KJ152 500GB                | 1         | 1      | 1.61%   |
| Seagate ST320LT007-9ZV142 320GB                | 1         | 1      | 1.61%   |
| Seagate ST320LM001 HN-M320MBB 320GB            | 1         | 1      | 1.61%   |
| Seagate ST1000LM035-1RK172 1TB                 | 1         | 1      | 1.61%   |
| SanDisk SDSSDX240GG25 240GB                    | 1         | 1      | 1.61%   |
| Samsung Electronics SSD PM810 2.5 7mm 128GB    | 1         | 1      | 1.61%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 1.61%   |
| Intel SSDSC2BW240A4 240GB                      | 1         | 2      | 1.61%   |
| Intel SSDSC2BF180A4L 180GB                     | 1         | 1      | 1.61%   |
| Inateck ASM1153E 240GB                         | 1         | 1      | 1.61%   |
| Hitachi HTS725032A9A364 320GB                  | 1         | 1      | 1.61%   |
| Hitachi HTS721080G9SA00 80GB                   | 1         | 1      | 1.61%   |
| Hitachi HTS545050B9A300 500GB                  | 1         | 1      | 1.61%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 20        | 20     | 32.26%  |
| WDC                 | 8         | 8      | 12.9%   |
| Toshiba             | 8         | 9      | 12.9%   |
| Hitachi             | 7         | 11     | 11.29%  |
| HGST                | 5         | 5      | 8.06%   |
| A-DATA Technology   | 4         | 5      | 6.45%   |
| Intel               | 2         | 3      | 3.23%   |
| Crucial             | 2         | 2      | 3.23%   |
| SK hynix            | 1         | 1      | 1.61%   |
| SanDisk             | 1         | 1      | 1.61%   |
| Samsung Electronics | 1         | 1      | 1.61%   |
| Micron Technology   | 1         | 1      | 1.61%   |
| Inateck             | 1         | 1      | 1.61%   |
| DTECHCO             | 1         | 1      | 1.61%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 20        | 20     | 40.82%  |
| WDC     | 8         | 8      | 16.33%  |
| Toshiba | 8         | 9      | 16.33%  |
| Hitachi | 7         | 11     | 14.29%  |
| HGST    | 5         | 5      | 10.2%   |
| Inateck | 1         | 1      | 2.04%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 47        | 54     | 78.33%  |
| SSD  | 11        | 13     | 18.33%  |
| NVMe | 2         | 2      | 3.33%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Crucial CT500P2SSD8 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Crucial | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 492       | 700    | 63.4%   |
| Works    | 223       | 292    | 28.74%  |
| Malfunc  | 60        | 69     | 7.73%   |
| Failed   | 1         | 1      | 0.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 504       | 57.86%  |
| AMD                                  | 165       | 18.94%  |
| SanDisk                              | 48        | 5.51%   |
| Samsung Electronics                  | 32        | 3.67%   |
| SK hynix                             | 22        | 2.53%   |
| Micron Technology                    | 16        | 1.84%   |
| Kingston Technology Company          | 16        | 1.84%   |
| Realtek Semiconductor                | 11        | 1.26%   |
| Nvidia                               | 10        | 1.15%   |
| Micron/Crucial Technology            | 8         | 0.92%   |
| Silicon Motion                       | 7         | 0.8%    |
| KIOXIA                               | 7         | 0.8%    |
| Union Memory (Shenzhen)              | 5         | 0.57%   |
| Phison Electronics                   | 5         | 0.57%   |
| Apple                                | 3         | 0.34%   |
| ADATA Technology                     | 3         | 0.34%   |
| VIA Technologies                     | 2         | 0.23%   |
| Toshiba America Info Systems         | 2         | 0.23%   |
| Marvell Technology Group             | 2         | 0.23%   |
| Solid State Storage Technology       | 1         | 0.11%   |
| Ramaxel Technology(Shenzhen) Limited | 1         | 0.11%   |
| Biwin Storage Technology             | 1         | 0.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 153       | 16.45%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 63        | 6.77%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 59        | 6.34%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 52        | 5.59%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 35        | 3.76%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 26        | 2.8%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 20        | 2.15%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 20        | 2.15%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 19        | 2.04%   |
| Intel Volume Management Device NVMe RAID Controller                              | 19        | 2.04%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 18        | 1.94%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 17        | 1.83%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 17        | 1.83%   |
| Intel Comet Lake SATA AHCI Controller                                            | 16        | 1.72%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 14        | 1.51%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 14        | 1.51%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 13        | 1.4%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 13        | 1.4%    |
| Intel SSD 670p Series [Keystone Harbor]                                          | 12        | 1.29%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 12        | 1.29%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 12        | 1.29%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 12        | 1.29%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 12        | 1.29%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 11        | 1.18%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 11        | 1.18%   |
| Intel Tiger Lake-LP SATA Controller                                              | 10        | 1.08%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 10        | 1.08%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 9         | 0.97%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 7         | 0.75%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                                | 7         | 0.75%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 7         | 0.75%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 6         | 0.65%   |
| Intel SSD 660P Series                                                            | 6         | 0.65%   |
| Intel Alder Lake-P SATA AHCI Controller                                          | 6         | 0.65%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 6         | 0.65%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 5         | 0.54%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                            | 5         | 0.54%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 5         | 0.54%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 5         | 0.54%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 5         | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 590       | 65.27%  |
| NVMe | 201       | 22.23%  |
| RAID | 73        | 8.08%   |
| IDE  | 40        | 4.42%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 538       | 72.51%  |
| AMD    | 204       | 27.49%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 28        | 3.77%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 15        | 2.02%   |
| AMD A12-9720P RADEON R7, 12 COMPUTE CORES 4C+8G | 13        | 1.75%   |
| Intel Core i5-8300H CPU @ 2.30GHz               | 12        | 1.62%   |
| Intel Celeron CPU N3060 @ 1.60GHz               | 12        | 1.62%   |
| Intel Core i5-8265U CPU @ 1.60GHz               | 11        | 1.48%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 11        | 1.48%   |
| AMD Ryzen 5 5500U with Radeon Graphics          | 11        | 1.48%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 10        | 1.35%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 10        | 1.35%   |
| Intel Celeron N4000 CPU @ 1.10GHz               | 10        | 1.35%   |
| Intel Celeron N4020 CPU @ 1.10GHz               | 9         | 1.21%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 9         | 1.21%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G    | 9         | 1.21%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 8         | 1.08%   |
| Intel Core i7-10510U CPU @ 1.80GHz              | 8         | 1.08%   |
| Intel Core i5-3210M CPU @ 2.50GHz               | 8         | 1.08%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz              | 8         | 1.08%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx   | 8         | 1.08%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz              | 7         | 0.94%   |
| Intel Core i7-4510U CPU @ 2.00GHz               | 7         | 0.94%   |
| Intel Core i5-4210U CPU @ 1.70GHz               | 7         | 0.94%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz              | 7         | 0.94%   |
| Intel Core i3-6006U CPU @ 2.00GHz               | 7         | 0.94%   |
| AMD Ryzen 7 5700U with Radeon Graphics          | 7         | 0.94%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx   | 7         | 0.94%   |
| Intel Core i5-3337U CPU @ 1.80GHz               | 6         | 0.81%   |
| Intel Core i5-10210U CPU @ 1.60GHz              | 6         | 0.81%   |
| Intel Core i3-5005U CPU @ 2.00GHz               | 6         | 0.81%   |
| Intel Core i3-10110U CPU @ 2.10GHz              | 6         | 0.81%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 6         | 0.81%   |
| AMD Ryzen 7 4800H with Radeon Graphics          | 6         | 0.81%   |
| Intel Core i7-6500U CPU @ 2.50GHz               | 5         | 0.67%   |
| Intel Core i7-5500U CPU @ 2.40GHz               | 5         | 0.67%   |
| Intel Core i7-2670QM CPU @ 2.20GHz              | 5         | 0.67%   |
| Intel Core i5-6300U CPU @ 2.40GHz               | 5         | 0.67%   |
| Intel Core i5-3230M CPU @ 2.60GHz               | 5         | 0.67%   |
| Intel Core i5-2430M CPU @ 2.40GHz               | 5         | 0.67%   |
| Intel Core i3-4005U CPU @ 1.70GHz               | 5         | 0.67%   |
| Intel Core i3-3110M CPU @ 2.40GHz               | 5         | 0.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 173       | 23.32%  |
| Intel Core i7                  | 118       | 15.9%   |
| Intel Core i3                  | 84        | 11.32%  |
| AMD Ryzen 5                    | 59        | 7.95%   |
| Other                          | 57        | 7.68%   |
| Intel Celeron                  | 57        | 7.68%   |
| Intel Core 2 Duo               | 21        | 2.83%   |
| AMD Ryzen 3                    | 21        | 2.83%   |
| AMD Ryzen 7                    | 20        | 2.7%    |
| Intel Atom                     | 17        | 2.29%   |
| AMD A12                        | 13        | 1.75%   |
| AMD A10                        | 12        | 1.62%   |
| AMD E1                         | 10        | 1.35%   |
| Intel Pentium                  | 9         | 1.21%   |
| AMD A8                         | 7         | 0.94%   |
| Intel Pentium Dual-Core        | 6         | 0.81%   |
| Intel Pentium Dual             | 6         | 0.81%   |
| AMD Ryzen 7 PRO                | 6         | 0.81%   |
| AMD A6                         | 6         | 0.81%   |
| AMD E2                         | 5         | 0.67%   |
| AMD E                          | 5         | 0.67%   |
| AMD A4                         | 5         | 0.67%   |
| AMD Athlon                     | 4         | 0.54%   |
| AMD Turion 64 X2 Mobile        | 3         | 0.4%    |
| AMD Ryzen 9                    | 3         | 0.4%    |
| Intel Genuine                  | 2         | 0.27%   |
| Intel Core m5                  | 2         | 0.27%   |
| Intel Celeron M                | 2         | 0.27%   |
| Intel Core M                   | 1         | 0.13%   |
| Intel Core 2                   | 1         | 0.13%   |
| AMD V120                       | 1         | 0.13%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.13%   |
| AMD Phenom II                  | 1         | 0.13%   |
| AMD Mobile Sempron             | 1         | 0.13%   |
| AMD C-70                       | 1         | 0.13%   |
| AMD C-60                       | 1         | 0.13%   |
| AMD Athlon II Neo              | 1         | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 422       | 56.8%   |
| 4       | 226       | 30.42%  |
| 6       | 31        | 4.17%   |
| 8       | 29        | 3.9%    |
| 1       | 24        | 3.23%   |
| 14      | 4         | 0.54%   |
| 12      | 3         | 0.4%    |
| 10      | 3         | 0.4%    |
| Unknown | 1         | 0.13%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 742       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 550       | 74.02%  |
| 1       | 190       | 25.57%  |
| 8       | 2         | 0.27%   |
| Unknown | 1         | 0.13%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 705       | 94.38%  |
| Unknown        | 31        | 4.15%   |
| 64-bit         | 6         | 0.8%    |
| 32-bit         | 5         | 0.67%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 196       | 25.52%  |
| 0x306a9    | 43        | 5.6%    |
| 0x206a7    | 38        | 4.95%   |
| 0x806ec    | 27        | 3.52%   |
| 0x806ea    | 27        | 3.52%   |
| 0x406e3    | 25        | 3.26%   |
| 0x08108109 | 25        | 3.26%   |
| 0x40651    | 21        | 2.73%   |
| 0x306d4    | 19        | 2.47%   |
| 0x06006705 | 19        | 2.47%   |
| 0x806c1    | 16        | 2.08%   |
| 0x08608103 | 16        | 2.08%   |
| 0x20655    | 15        | 1.95%   |
| 0x906ea    | 14        | 1.82%   |
| 0x08108102 | 14        | 1.82%   |
| 0x706e5    | 13        | 1.69%   |
| 0x306c3    | 13        | 1.69%   |
| 0x806e9    | 12        | 1.56%   |
| 0x406c4    | 12        | 1.56%   |
| 0x6fd      | 11        | 1.43%   |
| 0x1067a    | 11        | 1.43%   |
| 0x05000119 | 10        | 1.3%    |
| 0x706a1    | 9         | 1.17%   |
| 0x06006118 | 9         | 1.17%   |
| 0x806eb    | 8         | 1.04%   |
| 0x0a50000c | 8         | 1.04%   |
| 0x0600611a | 8         | 1.04%   |
| 0xa0652    | 6         | 0.78%   |
| 0x706a8    | 6         | 0.78%   |
| 0x506e3    | 6         | 0.78%   |
| 0x30678    | 6         | 0.78%   |
| 0x106ca    | 6         | 0.78%   |
| 0x08600106 | 6         | 0.78%   |
| 0x08101007 | 6         | 0.78%   |
| 0x20652    | 5         | 0.65%   |
| 0x106c2    | 5         | 0.65%   |
| 0x0810100b | 5         | 0.65%   |
| 0x07030105 | 5         | 0.65%   |
| 0x06001119 | 5         | 0.65%   |
| 0x106e5    | 4         | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 118       | 15.9%   |
| IvyBridge        | 54        | 7.28%   |
| Zen+             | 51        | 6.87%   |
| SandyBridge      | 49        | 6.6%    |
| Haswell          | 47        | 6.33%   |
| Excavator        | 44        | 5.93%   |
| Skylake          | 41        | 5.53%   |
| Silvermont       | 30        | 4.04%   |
| Westmere         | 28        | 3.77%   |
| TigerLake        | 25        | 3.37%   |
| Unknown          | 25        | 3.37%   |
| Broadwell        | 22        | 2.96%   |
| Core             | 21        | 2.83%   |
| Goldmont plus    | 20        | 2.7%    |
| Penryn           | 19        | 2.56%   |
| IceLake          | 19        | 2.56%   |
| Zen              | 16        | 2.16%   |
| Zen 2            | 15        | 2.02%   |
| Bonnell          | 12        | 1.62%   |
| Bobcat           | 11        | 1.48%   |
| Alderlake Hybrid | 11        | 1.48%   |
| Zen 3            | 10        | 1.35%   |
| Puma             | 10        | 1.35%   |
| CometLake        | 10        | 1.35%   |
| Piledriver       | 6         | 0.81%   |
| K8 Hammer        | 5         | 0.67%   |
| Jaguar           | 5         | 0.67%   |
| Nehalem          | 4         | 0.54%   |
| Goldmont         | 4         | 0.54%   |
| Steamroller      | 3         | 0.4%    |
| K10              | 3         | 0.4%    |
| P6               | 1         | 0.13%   |
| K8 & K10 hybrid  | 1         | 0.13%   |
| K10 Llano        | 1         | 0.13%   |
| Gracemont        | 1         | 0.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 516       | 57.72%  |
| AMD              | 218       | 24.38%  |
| Nvidia           | 158       | 17.67%  |
| VIA Technologies | 2         | 0.22%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 54        | 5.69%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 53        | 5.58%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 47        | 4.95%   |
| Intel UHD Graphics 620                                                                   | 28        | 2.95%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 28        | 2.95%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 27        | 2.85%   |
| Intel Core Processor Integrated Graphics Controller                                      | 26        | 2.74%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 24        | 2.53%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 23        | 2.42%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 21        | 2.21%   |
| AMD Lucienne                                                                             | 21        | 2.21%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 20        | 2.11%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 20        | 2.11%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 20        | 2.11%   |
| Intel HD Graphics 620                                                                    | 19        | 2%      |
| Intel HD Graphics 5500                                                                   | 19        | 2%      |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 19        | 2%      |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 17        | 1.79%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 16        | 1.69%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 16        | 1.69%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 15        | 1.58%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 15        | 1.58%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 15        | 1.58%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 15        | 1.58%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 13        | 1.37%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 12        | 1.26%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 12        | 1.26%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 12        | 1.26%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 9         | 0.95%   |
| Intel HD Graphics 530                                                                    | 9         | 0.95%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 9         | 0.95%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 9         | 0.95%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 8         | 0.84%   |
| Nvidia GM108M [GeForce MX110]                                                            | 7         | 0.74%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 7         | 0.74%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 7         | 0.74%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 7         | 0.74%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 7         | 0.74%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520/610 Mobile]                         | 7         | 0.74%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 6         | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 372       | 50.07%  |
| 1 x AMD        | 157       | 21.13%  |
| Intel + Nvidia | 127       | 17.09%  |
| 2 x AMD        | 36        | 4.85%   |
| 1 x Nvidia     | 21        | 2.83%   |
| Intel + AMD    | 15        | 2.02%   |
| AMD + Nvidia   | 10        | 1.35%   |
| 2 x Intel      | 3         | 0.4%    |
| 1 x VIA        | 2         | 0.27%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 653       | 87.18%  |
| Proprietary | 69        | 9.21%   |
| Unknown     | 27        | 3.6%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 462       | 61.11%  |
| 1.01-2.0   | 108       | 14.29%  |
| 0.01-0.5   | 107       | 14.15%  |
| 3.01-4.0   | 36        | 4.76%   |
| 0.51-1.0   | 34        | 4.5%    |
| 5.01-6.0   | 4         | 0.53%   |
| 7.01-8.0   | 2         | 0.26%   |
| 8.01-16.0  | 2         | 0.26%   |
| 2.01-3.0   | 1         | 0.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 190       | 22.81%  |
| AU Optronics            | 137       | 16.45%  |
| BOE                     | 130       | 15.61%  |
| Samsung Electronics     | 102       | 12.24%  |
| LG Display              | 84        | 10.08%  |
| Goldstar                | 26        | 3.12%   |
| PANDA                   | 22        | 2.64%   |
| Apple                   | 20        | 2.4%    |
| Chi Mei Optoelectronics | 15        | 1.8%    |
| Dell                    | 14        | 1.68%   |
| Sharp                   | 11        | 1.32%   |
| Hewlett-Packard         | 9         | 1.08%   |
| InfoVision              | 7         | 0.84%   |
| LG Philips              | 6         | 0.72%   |
| Lenovo                  | 6         | 0.72%   |
| Sony                    | 5         | 0.6%    |
| InnoLux Display         | 5         | 0.6%    |
| Acer                    | 5         | 0.6%    |
| AOC                     | 4         | 0.48%   |
| HKC                     | 3         | 0.36%   |
| HannStar                | 3         | 0.36%   |
| CS_                     | 3         | 0.36%   |
| CSO                     | 3         | 0.36%   |
| ViewSonic               | 2         | 0.24%   |
| MSI                     | 2         | 0.24%   |
| BenQ                    | 2         | 0.24%   |
| Toshiba                 | 1         | 0.12%   |
| STA                     | 1         | 0.12%   |
| SLD                     | 1         | 0.12%   |
| Sceptre Tech            | 1         | 0.12%   |
| SANYO                   | 1         | 0.12%   |
| RGT                     | 1         | 0.12%   |
| Panasonic               | 1         | 0.12%   |
| LTM                     | 1         | 0.12%   |
| KTC                     | 1         | 0.12%   |
| KDC                     | 1         | 0.12%   |
| HUAWEI                  | 1         | 0.12%   |
| HannStar Display        | 1         | 0.12%   |
| eMachines               | 1         | 0.12%   |
| ELD                     | 1         | 0.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 18        | 2.15%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 17        | 2.03%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 13        | 1.55%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 11        | 1.31%   |
| AU Optronics LCD Monitor AUO723C 1366x768 309x173mm 13.9-inch         | 11        | 1.31%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 10        | 1.19%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch       | 10        | 1.19%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch         | 10        | 1.19%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 9         | 1.07%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                  | 9         | 1.07%   |
| AU Optronics LCD Monitor AUO323C 1366x768 309x173mm 13.9-inch         | 7         | 0.83%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 6         | 0.72%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch       | 6         | 0.72%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                  | 6         | 0.72%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 5         | 0.6%    |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch | 5         | 0.6%    |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch               | 5         | 0.6%    |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 5         | 0.6%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 5         | 0.6%    |
| Chimei Innolux LCD Monitor CMN1491 1366x768 309x174mm 14.0-inch       | 5         | 0.6%    |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch       | 5         | 0.6%    |
| Chimei Innolux LCD Monitor CMN1476 1366x768 309x174mm 14.0-inch       | 5         | 0.6%    |
| BOE LCD Monitor BOE07AA 1366x768 344x194mm 15.5-inch                  | 5         | 0.6%    |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                  | 5         | 0.6%    |
| BOE LCD Monitor BOE05BA 1366x768 309x173mm 13.9-inch                  | 5         | 0.6%    |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 5         | 0.6%    |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 4         | 0.48%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 4         | 0.48%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch               | 4         | 0.48%   |
| LG Display LCD Monitor LGD0455 1366x768 310x174mm 14.0-inch           | 4         | 0.48%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 4         | 0.48%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 4         | 0.48%   |
| Chimei Innolux LCD Monitor CMN1487 1366x768 309x173mm 13.9-inch       | 4         | 0.48%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch       | 4         | 0.48%   |
| BOE LCD Monitor BOE07F7 1920x1080 309x174mm 14.0-inch                 | 4         | 0.48%   |
| BOE LCD Monitor BOE07A1 1920x1080 344x193mm 15.5-inch                 | 4         | 0.48%   |
| BOE LCD Monitor BOE0704 1366x768 344x194mm 15.5-inch                  | 4         | 0.48%   |
| BOE LCD Monitor BOE0644 1366x768 309x173mm 13.9-inch                  | 4         | 0.48%   |
| AU Optronics LCD Monitor AUO978F 1920x1080 382x215mm 17.3-inch        | 4         | 0.48%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch         | 4         | 0.48%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 432       | 54.48%  |
| 1920x1080 (FHD)    | 219       | 27.62%  |
| 1280x800 (WXGA)    | 26        | 3.28%   |
| 1600x900 (HD+)     | 25        | 3.15%   |
| 3840x2160 (4K)     | 24        | 3.03%   |
| 1440x900 (WXGA+)   | 13        | 1.64%   |
| 1024x600           | 8         | 1.01%   |
| 2880x1800          | 7         | 0.88%   |
| 1280x1024 (SXGA)   | 6         | 0.76%   |
| 2560x1600          | 5         | 0.63%   |
| 1920x1200 (WUXGA)  | 5         | 0.63%   |
| 2560x1440 (QHD)    | 4         | 0.5%    |
| 3456x2160          | 3         | 0.38%   |
| 2160x1440          | 3         | 0.38%   |
| 1360x768           | 3         | 0.38%   |
| 3440x1440          | 2         | 0.25%   |
| 2560x1080          | 2         | 0.25%   |
| 3840x1100          | 1         | 0.13%   |
| 3840x1080          | 1         | 0.13%   |
| 2256x1504          | 1         | 0.13%   |
| 1680x945           | 1         | 0.13%   |
| 1680x1050 (WSXGA+) | 1         | 0.13%   |
| 1024x768 (XGA)     | 1         | 0.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 264       | 31.5%   |
| 13      | 197       | 23.51%  |
| 14      | 174       | 20.76%  |
| 17      | 28        | 3.34%   |
| 21      | 26        | 3.1%    |
| 23      | 19        | 2.27%   |
| 24      | 16        | 1.91%   |
| 11      | 15        | 1.79%   |
| 12      | 14        | 1.67%   |
| 10      | 10        | 1.19%   |
| 27      | 9         | 1.07%   |
| 54      | 8         | 0.95%   |
| 19      | 8         | 0.95%   |
| 18      | 8         | 0.95%   |
| 31      | 6         | 0.72%   |
| 20      | 5         | 0.6%    |
| 84      | 4         | 0.48%   |
| 72      | 4         | 0.48%   |
| 34      | 4         | 0.48%   |
| Unknown | 4         | 0.48%   |
| 40      | 3         | 0.36%   |
| 16      | 3         | 0.36%   |
| 8       | 2         | 0.24%   |
| 86      | 1         | 0.12%   |
| 63      | 1         | 0.12%   |
| 61      | 1         | 0.12%   |
| 48      | 1         | 0.12%   |
| 43      | 1         | 0.12%   |
| 26      | 1         | 0.12%   |
| 22      | 1         | 0.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 594       | 71.65%  |
| 201-300     | 75        | 9.05%   |
| 401-500     | 48        | 5.79%   |
| 501-600     | 39        | 4.7%    |
| 351-400     | 28        | 3.38%   |
| 1001-1500   | 12        | 1.45%   |
| 601-700     | 11        | 1.33%   |
| 1501-2000   | 8         | 0.97%   |
| 701-800     | 4         | 0.48%   |
| Unknown     | 4         | 0.48%   |
| 801-900     | 3         | 0.36%   |
| 101-200     | 2         | 0.24%   |
| 901-1000    | 1         | 0.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 653       | 88.24%  |
| 16/10   | 66        | 8.92%   |
| 5/4     | 6         | 0.81%   |
| 3/2     | 6         | 0.81%   |
| 21/9    | 4         | 0.54%   |
| 4/3     | 1         | 0.14%   |
| 32/9    | 1         | 0.14%   |
| 3.40    | 1         | 0.14%   |
| 0.56    | 1         | 0.14%   |
| Unknown | 1         | 0.14%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 348       | 41.68%  |
| 101-110        | 265       | 31.74%  |
| 201-250        | 50        | 5.99%   |
| 71-80          | 20        | 2.4%    |
| More than 1000 | 19        | 2.28%   |
| 121-130        | 18        | 2.16%   |
| 51-60          | 16        | 1.92%   |
| 151-200        | 16        | 1.92%   |
| 61-70          | 14        | 1.68%   |
| 141-150        | 14        | 1.68%   |
| 351-500        | 10        | 1.2%    |
| 41-50          | 10        | 1.2%    |
| 301-350        | 10        | 1.2%    |
| 251-300        | 8         | 0.96%   |
| 501-1000       | 5         | 0.6%    |
| 131-140        | 4         | 0.48%   |
| Unknown        | 4         | 0.48%   |
| 1-40           | 2         | 0.24%   |
| 111-120        | 1         | 0.12%   |
| 91-100         | 1         | 0.12%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 435       | 53.31%  |
| 121-160       | 210       | 25.74%  |
| 51-100        | 109       | 13.36%  |
| 161-240       | 22        | 2.7%    |
| More than 240 | 20        | 2.45%   |
| 1-50          | 16        | 1.96%   |
| Unknown       | 4         | 0.49%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 605       | 78.98%  |
| 2     | 131       | 17.1%   |
| 0     | 24        | 3.13%   |
| 3     | 5         | 0.65%   |
| 4     | 1         | 0.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 491       | 42.29%  |
| Intel                           | 254       | 21.88%  |
| Qualcomm Atheros                | 195       | 16.8%   |
| Broadcom                        | 78        | 6.72%   |
| Broadcom Limited                | 25        | 2.15%   |
| MediaTek                        | 17        | 1.46%   |
| Ralink                          | 16        | 1.38%   |
| TP-Link                         | 12        | 1.03%   |
| Marvell Technology Group        | 10        | 0.86%   |
| Samsung Electronics             | 9         | 0.78%   |
| Nvidia                          | 9         | 0.78%   |
| Ralink Technology               | 6         | 0.52%   |
| Qualcomm Atheros Communications | 6         | 0.52%   |
| ASIX Electronics                | 5         | 0.43%   |
| Xiaomi                          | 4         | 0.34%   |
| Huawei Technologies             | 4         | 0.34%   |
| VIA Technologies                | 2         | 0.17%   |
| Qualcomm                        | 2         | 0.17%   |
| DisplayLink                     | 2         | 0.17%   |
| D-Link System                   | 2         | 0.17%   |
| T & A Mobile Phones             | 1         | 0.09%   |
| STMicroelectronics              | 1         | 0.09%   |
| Quanta                          | 1         | 0.09%   |
| Prolific Technology             | 1         | 0.09%   |
| OPPO Electronics                | 1         | 0.09%   |
| Motorola PCS                    | 1         | 0.09%   |
| Mercucys                        | 1         | 0.09%   |
| Lenovo                          | 1         | 0.09%   |
| JMicron Technology              | 1         | 0.09%   |
| Google                          | 1         | 0.09%   |
| Dell                            | 1         | 0.09%   |
| 3Com                            | 1         | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 296       | 21.34%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 98        | 7.07%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 50        | 3.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 47        | 3.39%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 40        | 2.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 33        | 2.38%   |
| Intel Wireless 8265 / 8275                                              | 29        | 2.09%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 27        | 1.95%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 26        | 1.87%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 25        | 1.8%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 20        | 1.44%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 19        | 1.37%   |
| Intel Wi-Fi 6 AX201                                                     | 19        | 1.37%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 17        | 1.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 17        | 1.23%   |
| Intel Wi-Fi 6 AX200                                                     | 16        | 1.15%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 16        | 1.15%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 15        | 1.08%   |
| Broadcom BCM43142 802.11b/g/n                                           | 15        | 1.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 14        | 1.01%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 13        | 0.94%   |
| Intel Wireless 7260                                                     | 13        | 0.94%   |
| Intel Wireless 8260                                                     | 12        | 0.87%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 11        | 0.79%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 10        | 0.72%   |
| Intel Centrino Wireless-N 2230                                          | 10        | 0.72%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 9         | 0.65%   |
| Intel Ethernet Connection I219-LM                                       | 9         | 0.65%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 9         | 0.65%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 8         | 0.58%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 8         | 0.58%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 8         | 0.58%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 8         | 0.58%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 8         | 0.58%   |
| Intel Wireless 7265                                                     | 8         | 0.58%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 8         | 0.58%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 8         | 0.58%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 7         | 0.5%    |
| Realtek RTL8188EE Wireless Network Adapter                              | 7         | 0.5%    |
| Realtek 802.11ac NIC                                                    | 7         | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 248       | 32.04%  |
| Realtek Semiconductor           | 209       | 27%     |
| Qualcomm Atheros                | 173       | 22.35%  |
| Broadcom                        | 62        | 8.01%   |
| Broadcom Limited                | 19        | 2.45%   |
| Ralink                          | 16        | 2.07%   |
| MediaTek                        | 16        | 2.07%   |
| TP-Link                         | 12        | 1.55%   |
| Ralink Technology               | 6         | 0.78%   |
| Qualcomm Atheros Communications | 6         | 0.78%   |
| D-Link System                   | 2         | 0.26%   |
| Qualcomm                        | 1         | 0.13%   |
| Mercucys                        | 1         | 0.13%   |
| Marvell Technology Group        | 1         | 0.13%   |
| Dell                            | 1         | 0.13%   |
| 3Com                            | 1         | 0.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 50        | 6.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 47        | 6.05%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 40        | 5.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 33        | 4.25%   |
| Intel Wireless 8265 / 8275                                              | 29        | 3.73%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 27        | 3.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 26        | 3.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 25        | 3.22%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 19        | 2.45%   |
| Intel Wi-Fi 6 AX201                                                     | 19        | 2.45%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 17        | 2.19%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 17        | 2.19%   |
| Intel Wi-Fi 6 AX200                                                     | 16        | 2.06%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 16        | 2.06%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 15        | 1.93%   |
| Broadcom BCM43142 802.11b/g/n                                           | 15        | 1.93%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 14        | 1.8%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 13        | 1.67%   |
| Intel Wireless 7260                                                     | 13        | 1.67%   |
| Intel Wireless 8260                                                     | 12        | 1.54%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 10        | 1.29%   |
| Intel Centrino Wireless-N 2230                                          | 10        | 1.29%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 9         | 1.16%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 9         | 1.16%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 8         | 1.03%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 8         | 1.03%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 8         | 1.03%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 8         | 1.03%   |
| Intel Wireless 7265                                                     | 8         | 1.03%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 8         | 1.03%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 8         | 1.03%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 7         | 0.9%    |
| Realtek 802.11ac NIC                                                    | 7         | 0.9%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 7         | 0.9%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 0.9%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 7         | 0.9%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 6         | 0.77%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 6         | 0.77%   |
| Broadcom Limited BCM43142 802.11b/g/n                                   | 6         | 0.77%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 5         | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 427       | 70.58%  |
| Intel                    | 57        | 9.42%   |
| Qualcomm Atheros         | 40        | 6.61%   |
| Broadcom                 | 23        | 3.8%    |
| Samsung Electronics      | 9         | 1.49%   |
| Nvidia                   | 9         | 1.49%   |
| Marvell Technology Group | 9         | 1.49%   |
| Broadcom Limited         | 6         | 0.99%   |
| ASIX Electronics         | 5         | 0.83%   |
| Xiaomi                   | 4         | 0.66%   |
| Huawei Technologies      | 4         | 0.66%   |
| VIA Technologies         | 2         | 0.33%   |
| DisplayLink              | 2         | 0.33%   |
| T & A Mobile Phones      | 1         | 0.17%   |
| Quanta                   | 1         | 0.17%   |
| Qualcomm                 | 1         | 0.17%   |
| Prolific Technology      | 1         | 0.17%   |
| OPPO Electronics         | 1         | 0.17%   |
| MediaTek                 | 1         | 0.17%   |
| Lenovo                   | 1         | 0.17%   |
| JMicron Technology       | 1         | 0.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 296       | 48.76%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 98        | 16.14%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 20        | 3.29%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 11        | 1.81%   |
| Intel Ethernet Connection I219-LM                                      | 9         | 1.48%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 8         | 1.32%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 7         | 1.15%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 7         | 1.15%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 7         | 1.15%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 6         | 0.99%   |
| Intel 82577LM Gigabit Network Connection                               | 6         | 0.99%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 6         | 0.99%   |
| Realtek Killer E2600 GbE Controller                                    | 5         | 0.82%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 5         | 0.82%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 5         | 0.82%   |
| Nvidia MCP79 Ethernet                                                  | 5         | 0.82%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 5         | 0.82%   |
| Intel Ethernet Connection I219-V                                       | 5         | 0.82%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 4         | 0.66%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 4         | 0.66%   |
| Intel Ethernet Connection (3) I218-LM                                  | 4         | 0.66%   |
| Huawei STG-LX1                                                         | 4         | 0.66%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 3         | 0.49%   |
| Intel Ethernet Connection I218-LM                                      | 3         | 0.49%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 3         | 0.49%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                | 3         | 0.49%   |
| ASIX AX88179 Gigabit Ethernet                                          | 3         | 0.49%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 2         | 0.33%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 2         | 0.33%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 2         | 0.33%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 2         | 0.33%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 2         | 0.33%   |
| Nvidia MCP67 Ethernet                                                  | 2         | 0.33%   |
| Nvidia MCP51 Ethernet Controller                                       | 2         | 0.33%   |
| Intel Ethernet Connection I217-LM                                      | 2         | 0.33%   |
| Intel Ethernet Connection (4) I219-V                                   | 2         | 0.33%   |
| Intel Ethernet Connection (10) I219-V                                  | 2         | 0.33%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 2         | 0.33%   |
| ASIX AX88772B                                                          | 2         | 0.33%   |
| T & A Mobile Phones TCL 30 XE 5G                                       | 1         | 0.16%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 736       | 55.76%  |
| Ethernet | 581       | 44.02%  |
| Unknown  | 2         | 0.15%   |
| Modem    | 1         | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 596       | 74.78%  |
| Ethernet | 200       | 25.09%  |
| Unknown  | 1         | 0.13%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 536       | 72.14%  |
| 1     | 200       | 26.92%  |
| 0     | 6         | 0.81%   |
| 3     | 1         | 0.13%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 667       | 88.58%  |
| Yes  | 86        | 11.42%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 205       | 33.66%  |
| Realtek Semiconductor           | 121       | 19.87%  |
| IMC Networks                    | 77        | 12.64%  |
| Qualcomm Atheros Communications | 61        | 10.02%  |
| Lite-On Technology              | 37        | 6.08%   |
| Broadcom                        | 23        | 3.78%   |
| Foxconn / Hon Hai               | 16        | 2.63%   |
| Apple                           | 16        | 2.63%   |
| Ralink                          | 10        | 1.64%   |
| Cambridge Silicon Radio         | 9         | 1.48%   |
| Hewlett-Packard                 | 8         | 1.31%   |
| Toshiba                         | 7         | 1.15%   |
| Realtek                         | 5         | 0.82%   |
| Foxconn International           | 5         | 0.82%   |
| Dell                            | 3         | 0.49%   |
| Alps Electric                   | 3         | 0.49%   |
| MediaTek                        | 2         | 0.33%   |
| ASUSTek Computer                | 1         | 0.16%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 73        | 11.99%  |
| Realtek Bluetooth Radio                             | 57        | 9.36%   |
| Realtek  Bluetooth 4.2 Adapter                      | 53        | 8.7%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 46        | 7.55%   |
| Intel AX201 Bluetooth                               | 40        | 6.57%   |
| IMC Networks Bluetooth Radio                        | 38        | 6.24%   |
| Qualcomm Atheros  Bluetooth Device                  | 29        | 4.76%   |
| IMC Networks Bluetooth Device                       | 22        | 3.61%   |
| Intel AX200 Bluetooth                               | 16        | 2.63%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 13        | 2.13%   |
| Intel Bluetooth Device                              | 12        | 1.97%   |
| IMC Networks Wireless_Device                        | 11        | 1.81%   |
| Ralink RT3290 Bluetooth                             | 10        | 1.64%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 10        | 1.64%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 10        | 1.64%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 9         | 1.48%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 9         | 1.48%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 8         | 1.31%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 8         | 1.31%   |
| Apple Bluetooth Host Controller                     | 8         | 1.31%   |
| Lite-On Bluetooth Device                            | 7         | 1.15%   |
| Lite-On Atheros AR3012 Bluetooth                    | 6         | 0.99%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 5         | 0.82%   |
| Realtek RTL8723B Bluetooth                          | 5         | 0.82%   |
| Realtek Bluetooth Radio                             | 5         | 0.82%   |
| Foxconn International BCM43142A0 Bluetooth module   | 5         | 0.82%   |
| Foxconn / Hon Hai Bluetooth Device                  | 5         | 0.82%   |
| Broadcom BCM2045B (BDC-2.1)                         | 5         | 0.82%   |
| Apple Bluetooth USB Host Controller                 | 5         | 0.82%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4         | 0.66%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 4         | 0.66%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 4         | 0.66%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 4         | 0.66%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 4         | 0.66%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 0.49%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 0.49%   |
| Broadcom BCM20702A0                                 | 3         | 0.49%   |
| Alps Electric BCM2046 Bluetooth Device              | 3         | 0.49%   |
| Toshiba Bluetooth Device                            | 2         | 0.33%   |
| Toshiba BCM43142A0                                  | 2         | 0.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 524       | 62.38%  |
| AMD                       | 205       | 24.4%   |
| Nvidia                    | 75        | 8.93%   |
| Logitech                  | 6         | 0.71%   |
| C-Media Electronics       | 5         | 0.6%    |
| Realtek Semiconductor     | 4         | 0.48%   |
| Generalplus Technology    | 3         | 0.36%   |
| VIA Technologies          | 2         | 0.24%   |
| Texas Instruments         | 2         | 0.24%   |
| Plantronics               | 2         | 0.24%   |
| JMTek                     | 2         | 0.24%   |
| Corsair                   | 2         | 0.24%   |
| Sennheiser Communications | 1         | 0.12%   |
| Microsoft                 | 1         | 0.12%   |
| KTMicro                   | 1         | 0.12%   |
| Conexant Systems          | 1         | 0.12%   |
| BEHRINGER International   | 1         | 0.12%   |
| ASUSTek Computer          | 1         | 0.12%   |
| Astro Gaming              | 1         | 0.12%   |
| Apple                     | 1         | 0.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 112       | 10.21%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 81        | 7.38%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 66        | 6.02%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 65        | 5.93%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 43        | 3.92%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 40        | 3.65%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 37        | 3.37%   |
| AMD Kabini HDMI/DP Audio                                                                          | 35        | 3.19%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 32        | 2.92%   |
| AMD FCH Azalia Controller                                                                         | 31        | 2.83%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 28        | 2.55%   |
| Intel 8 Series HD Audio Controller                                                                | 27        | 2.46%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 25        | 2.28%   |
| AMD High Definition Audio Controller                                                              | 24        | 2.19%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 23        | 2.1%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 22        | 2.01%   |
| Intel Broadwell-U Audio Controller                                                                | 22        | 2.01%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 21        | 1.91%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 20        | 1.82%   |
| Intel Cannon Lake PCH cAVS                                                                        | 20        | 1.82%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 19        | 1.73%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 18        | 1.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 17        | 1.55%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 17        | 1.55%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 14        | 1.28%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 14        | 1.28%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 13        | 1.19%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 13        | 1.19%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 12        | 1.09%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 12        | 1.09%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 11        | 1%      |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 10        | 0.91%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 10        | 0.91%   |
| Intel Comet Lake PCH cAVS                                                                         | 9         | 0.82%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 8         | 0.73%   |
| AMD Wrestler HDMI Audio                                                                           | 7         | 0.64%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 6         | 0.55%   |
| AMD Trinity HDMI Audio Controller                                                                 | 6         | 0.55%   |
| Nvidia MCP79 High Definition Audio                                                                | 5         | 0.46%   |
| Realtek Semiconductor USB Audio                                                                   | 4         | 0.36%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 130       | 29.48%  |
| SK hynix            | 100       | 22.68%  |
| Micron Technology   | 69        | 15.65%  |
| Kingston            | 35        | 7.94%   |
| A-DATA Technology   | 22        | 4.99%   |
| Unknown             | 18        | 4.08%   |
| Ramaxel Technology  | 12        | 2.72%   |
| Crucial             | 11        | 2.49%   |
| Nanya Technology    | 6         | 1.36%   |
| Elpida              | 6         | 1.36%   |
| Avant               | 4         | 0.91%   |
| Unknown (ABCD)      | 3         | 0.68%   |
| PNY                 | 3         | 0.68%   |
| Apacer              | 3         | 0.68%   |
| Patriot             | 2         | 0.45%   |
| Hikvision           | 2         | 0.45%   |
| Unknown             | 2         | 0.45%   |
| Unknown (08AE)      | 1         | 0.23%   |
| Toshiba             | 1         | 0.23%   |
| Team                | 1         | 0.23%   |
| Qumo                | 1         | 0.23%   |
| Qimonda             | 1         | 0.23%   |
| PUSKILL             | 1         | 0.23%   |
| Kllisre             | 1         | 0.23%   |
| Hewlett-Packard     | 1         | 0.23%   |
| Goldkey             | 1         | 0.23%   |
| Gold Key            | 1         | 0.23%   |
| ChangXin Memory     | 1         | 0.23%   |
| Centon              | 1         | 0.23%   |
| ASint Technology    | 1         | 0.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 10        | 2.17%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 9         | 1.96%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 7         | 1.52%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 7         | 1.52%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 7         | 1.52%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 7         | 1.52%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 6         | 1.3%    |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 5         | 1.09%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 5         | 1.09%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 5         | 1.09%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 5         | 1.09%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s              | 4         | 0.87%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 4         | 0.87%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 4         | 0.87%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 4         | 0.87%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 4         | 0.87%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 4         | 0.87%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 4         | 0.87%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 4         | 0.87%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 4         | 0.87%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 4         | 0.87%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 3200MT/s               | 4         | 0.87%   |
| Samsung RAM K4A8G165WC-BCTD 4GB SODIMM DDR4 2667MT/s                | 4         | 0.87%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s               | 4         | 0.87%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 3         | 0.65%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 3         | 0.65%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 3         | 0.65%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 3         | 0.65%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s              | 3         | 0.65%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s              | 3         | 0.65%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s            | 3         | 0.65%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 3         | 0.65%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 3         | 0.65%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s                | 3         | 0.65%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 3200MT/s               | 3         | 0.65%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 3         | 0.65%   |
| Kingston RAM 99U5428-018.A00LF 8192MB SODIMM DDR3 1600MT/s          | 3         | 0.65%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                         | 2         | 0.43%   |
| Unknown RAM Module 2GB SODIMM DDR2                                  | 2         | 0.43%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 176       | 50.72%  |
| DDR3   | 122       | 35.16%  |
| LPDDR4 | 15        | 4.32%   |
| DDR2   | 13        | 3.75%   |
| SDRAM  | 7         | 2.02%   |
| LPDDR3 | 7         | 2.02%   |
| LPDDR5 | 4         | 1.15%   |
| DDR5   | 2         | 0.58%   |
| DRAM   | 1         | 0.29%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 318       | 92.44%  |
| Row Of Chips | 25        | 7.27%   |
| DIMM         | 1         | 0.29%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 153       | 38.06%  |
| 8192  | 141       | 35.07%  |
| 16384 | 45        | 11.19%  |
| 2048  | 44        | 10.95%  |
| 1024  | 12        | 2.99%   |
| 32768 | 6         | 1.49%   |
| 512   | 1         | 0.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 91        | 23.82%  |
| 1600    | 87        | 22.77%  |
| 3200    | 74        | 19.37%  |
| 2400    | 22        | 5.76%   |
| 1334    | 22        | 5.76%   |
| 2133    | 14        | 3.66%   |
| 1333    | 10        | 2.62%   |
| 3266    | 9         | 2.36%   |
| Unknown | 7         | 1.83%   |
| 1067    | 6         | 1.57%   |
| 4267    | 5         | 1.31%   |
| 4199    | 5         | 1.31%   |
| 1066    | 5         | 1.31%   |
| 6400    | 4         | 1.05%   |
| 667     | 4         | 1.05%   |
| 800     | 3         | 0.79%   |
| 4800    | 2         | 0.52%   |
| 1776    | 2         | 0.52%   |
| 975     | 2         | 0.52%   |
| 533     | 2         | 0.52%   |
| 8400    | 1         | 0.26%   |
| 5600    | 1         | 0.26%   |
| 4266    | 1         | 0.26%   |
| 3733    | 1         | 0.26%   |
| 2048    | 1         | 0.26%   |
| 1867    | 1         | 0.26%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Seiko Epson         | 4         | 66.67%  |
| Samsung Electronics | 1         | 16.67%  |
| Hewlett-Packard     | 1         | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Seiko Epson L360 Series          | 1         | 16.67%  |
| Seiko Epson L3110 Series         | 1         | 16.67%  |
| Seiko Epson L210 Series          | 1         | 16.67%  |
| Seiko Epson L120 Series          | 1         | 16.67%  |
| Samsung M2020 Series             | 1         | 16.67%  |
| HP LaserJet Professional P 1102w | 1         | 16.67%  |

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
| Chicony Electronics                    | 145       | 20.66%  |
| IMC Networks                           | 137       | 19.52%  |
| Realtek Semiconductor                  | 54        | 7.69%   |
| Cheng Uei Precision Industry (Foxlink) | 49        | 6.98%   |
| Quanta                                 | 45        | 6.41%   |
| Microdia                               | 45        | 6.41%   |
| Bison Electronics                      | 35        | 4.99%   |
| Sunplus Innovation Technology          | 31        | 4.42%   |
| Lite-On Technology                     | 22        | 3.13%   |
| Syntek                                 | 17        | 2.42%   |
| Silicon Motion                         | 16        | 2.28%   |
| Acer                                   | 16        | 2.28%   |
| Suyin                                  | 13        | 1.85%   |
| Apple                                  | 12        | 1.71%   |
| Ricoh                                  | 7         | 1%      |
| Y Media                                | 5         | 0.71%   |
| Luxvisions Innotech Limited            | 5         | 0.71%   |
| Logitech                               | 5         | 0.71%   |
| Alcor Micro                            | 5         | 0.71%   |
| Sonix Technology                       | 4         | 0.57%   |
| OmniVision Technologies                | 4         | 0.57%   |
| Lenovo                                 | 4         | 0.57%   |
| Importek                               | 4         | 0.57%   |
| ALi                                    | 4         | 0.57%   |
| Z-Star Microelectronics                | 3         | 0.43%   |
| Sunplus Technology                     | 2         | 0.28%   |
| Samsung Electronics                    | 2         | 0.28%   |
| ShineTech                              | 1         | 0.14%   |
| Primax Electronics                     | 1         | 0.14%   |
| Pixart Imaging                         | 1         | 0.14%   |
| Nebraska Furniture Mart                | 1         | 0.14%   |
| KYE Systems (Mouse Systems)            | 1         | 0.14%   |
| Huawei Technologies                    | 1         | 0.14%   |
| Genesys Logic                          | 1         | 0.14%   |
| Foxconn / Hon Hai                      | 1         | 0.14%   |
| Cubeternet                             | 1         | 0.14%   |
| Arkmicro Technologies                  | 1         | 0.14%   |
| Alcorlink                              | 1         | 0.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                                         | 51        | 7.26%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 38        | 5.41%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 20        | 2.85%   |
| Microdia Integrated_Webcam_HD                                              | 18        | 2.56%   |
| Chicony Integrated Camera                                                  | 18        | 2.56%   |
| IMC Networks Integrated Camera                                             | 16        | 2.28%   |
| Chicony HP TrueVision HD Camera                                            | 13        | 1.85%   |
| Bison Integrated Camera                                                    | 12        | 1.71%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 11        | 1.57%   |
| Sunplus Integrated_Webcam_HD                                               | 10        | 1.42%   |
| Chicony Lenovo EasyCamera                                                  | 10        | 1.42%   |
| Syntek Integrated Camera                                                   | 9         | 1.28%   |
| Realtek USB Camera                                                         | 9         | 1.28%   |
| Realtek Integrated_Webcam_HD                                               | 9         | 1.28%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                           | 9         | 1.28%   |
| Quanta HD User Facing                                                      | 8         | 1.14%   |
| Chicony HP Webcam                                                          | 8         | 1.14%   |
| Chicony HD WebCam                                                          | 8         | 1.14%   |
| Lite-On HP Webcam                                                          | 7         | 1%      |
| Quanta HD Webcam                                                           | 6         | 0.85%   |
| Microdia Lenovo EasyCamera                                                 | 6         | 0.85%   |
| IMC Networks VGA UVC WebCam                                                | 6         | 0.85%   |
| Chicony EasyCamera                                                         | 6         | 0.85%   |
| Y Media USB Camera                                                         | 5         | 0.71%   |
| Realtek Lenovo EasyCamera                                                  | 5         | 0.71%   |
| Realtek Asus laptop camera                                                 | 5         | 0.71%   |
| Quanta HP Webcam                                                           | 5         | 0.71%   |
| Lite-On Integrated Camera                                                  | 5         | 0.71%   |
| Lite-On HP HD Camera                                                       | 5         | 0.71%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 5         | 0.71%   |
| Bison Lenovo EasyCamera                                                    | 5         | 0.71%   |
| Bison EasyCamera                                                           | 5         | 0.71%   |
| Syntek Lenovo EasyCamera                                                   | 4         | 0.57%   |
| Syntek EasyCamera                                                          | 4         | 0.57%   |
| Suyin 1.3M HD WebCam                                                       | 4         | 0.57%   |
| Sunplus HD WebCam                                                          | 4         | 0.57%   |
| Realtek USB2.0 VGA UVC WebCam                                              | 4         | 0.57%   |
| Realtek HP Truevision HD                                                   | 4         | 0.57%   |
| Realtek HD WebCam                                                          | 4         | 0.57%   |
| Quanta VGA WebCam                                                          | 4         | 0.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 30        | 31.91%  |
| Elan Microelectronics      | 19        | 20.21%  |
| Synaptics                  | 17        | 18.09%  |
| Shenzhen Goodix Technology | 16        | 17.02%  |
| Upek                       | 6         | 6.38%   |
| LighTuning Technology      | 3         | 3.19%   |
| AuthenTec                  | 2         | 2.13%   |
| STMicroelectronics         | 1         | 1.06%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Elan ELAN:Fingerprint                                                      | 16        | 17.02%  |
| Shenzhen Goodix  FingerPrint Device                                        | 13        | 13.83%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 6         | 6.38%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 6         | 6.38%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 5         | 5.32%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 5         | 5.32%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 4.26%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 3.19%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 3         | 3.19%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 3.19%   |
| Elan ELAN:ARM-M4                                                           | 3         | 3.19%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 2.13%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 2.13%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 2.13%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 2.13%   |
| Synaptics  WBDI                                                            | 2         | 2.13%   |
| Synaptics Fingerprint reader [HP G6]                                       | 2         | 2.13%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 2.13%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.06%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 1.06%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 1.06%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 1.06%   |
| Synaptics WBDI Device                                                      | 1         | 1.06%   |
| Synaptics WBDI                                                             | 1         | 1.06%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 1.06%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 1.06%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 1.06%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 1.06%   |
| AuthenTec AES2810                                                          | 1         | 1.06%   |
| AuthenTec AES1600                                                          | 1         | 1.06%   |
| Unknown                                                                    | 1         | 1.06%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 8         | 42.11%  |
| Upek                  | 4         | 21.05%  |
| O2 Micro              | 2         | 10.53%  |
| Lenovo                | 2         | 10.53%  |
| Alcor Micro           | 2         | 10.53%  |
| Gemalto (was Gemplus) | 1         | 5.26%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Broadcom 5880                                              | 5         | 26.32%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 4         | 21.05%  |
| Lenovo Integrated Smart Card Reader                        | 2         | 10.53%  |
| Broadcom BCM5880 Secure Applications Processor             | 2         | 10.53%  |
| Alcor Micro AU9540 Smartcard Reader                        | 2         | 10.53%  |
| O2 Micro Oz776 SmartCard Reader                            | 1         | 5.26%   |
| O2 Micro OZ776 CCID Smartcard Reader                       | 1         | 5.26%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer     | 1         | 5.26%   |
| Broadcom 58200                                             | 1         | 5.26%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 470       | 61.92%  |
| 1     | 243       | 32.02%  |
| 2     | 44        | 5.8%    |
| 7     | 1         | 0.13%   |
| 6     | 1         | 0.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 94        | 28.57%  |
| Graphics card            | 68        | 20.67%  |
| Net/wireless             | 60        | 18.24%  |
| Multimedia controller    | 29        | 8.81%   |
| Chipcard                 | 19        | 5.78%   |
| Bluetooth                | 18        | 5.47%   |
| Camera                   | 15        | 4.56%   |
| Communication controller | 8         | 2.43%   |
| Storage                  | 5         | 1.52%   |
| Sound                    | 4         | 1.22%   |
| Card reader              | 4         | 1.22%   |
| Net/ethernet             | 3         | 0.91%   |
| Flash memory             | 1         | 0.3%    |
| Firewire controller      | 1         | 0.3%    |

