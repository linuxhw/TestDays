Pop!_OS 22.04 - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for Pop!_OS 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 751

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | XPS 13 9305                 | [1746053c5b](https://linux-hardware.org/?probe=1746053c5b) | Sep 01, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [46e67b2b16](https://linux-hardware.org/?probe=46e67b2b16) | Sep 01, 2022 |
| Dell          | G3 3590                     | [cbe6c26276](https://linux-hardware.org/?probe=cbe6c26276) | Sep 01, 2022 |
| ASUSTek       | N552VW                      | [99d4a9be86](https://linux-hardware.org/?probe=99d4a9be86) | Sep 01, 2022 |
| Dell          | Precision 5530              | [298ce27830](https://linux-hardware.org/?probe=298ce27830) | Sep 01, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1200... | [55073b08dc](https://linux-hardware.org/?probe=55073b08dc) | Sep 01, 2022 |
| Lenovo        | Z50-70 20354                | [8ac8531142](https://linux-hardware.org/?probe=8ac8531142) | Sep 01, 2022 |
| Toshiba       | Satellite C850              | [6cf6d8fca8](https://linux-hardware.org/?probe=6cf6d8fca8) | Sep 01, 2022 |
| Apple         | MacBookAir9,1               | [51c4002c97](https://linux-hardware.org/?probe=51c4002c97) | Sep 01, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [d96b24b7f3](https://linux-hardware.org/?probe=d96b24b7f3) | Sep 01, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [67eb62450a](https://linux-hardware.org/?probe=67eb62450a) | Sep 01, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [838e09c9cf](https://linux-hardware.org/?probe=838e09c9cf) | Sep 01, 2022 |
| Lenovo        | Z50-70 20354                | [6e245e4c63](https://linux-hardware.org/?probe=6e245e4c63) | Sep 01, 2022 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | [d6e9455a63](https://linux-hardware.org/?probe=d6e9455a63) | Aug 31, 2022 |
| Dell          | Inspiron 13-7378            | [42666a5460](https://linux-hardware.org/?probe=42666a5460) | Aug 31, 2022 |
| Toshiba       | Satellite C850              | [d9505cea0a](https://linux-hardware.org/?probe=d9505cea0a) | Aug 31, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | [6eeadaf886](https://linux-hardware.org/?probe=6eeadaf886) | Aug 31, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | [56e8f54a3e](https://linux-hardware.org/?probe=56e8f54a3e) | Aug 31, 2022 |
| Acer          | Aspire E1-571               | [4db54180a8](https://linux-hardware.org/?probe=4db54180a8) | Aug 31, 2022 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [6d04d534fa](https://linux-hardware.org/?probe=6d04d534fa) | Aug 31, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [988032b933](https://linux-hardware.org/?probe=988032b933) | Aug 31, 2022 |
| Toshiba       | Satellite C850              | [5d7cb36794](https://linux-hardware.org/?probe=5d7cb36794) | Aug 31, 2022 |
| Dell          | Inspiron 3493               | [dc23941a16](https://linux-hardware.org/?probe=dc23941a16) | Aug 31, 2022 |
| ASUSTek       | G75VX                       | [e249508d61](https://linux-hardware.org/?probe=e249508d61) | Aug 30, 2022 |
| Lenovo        | V330 81AX                   | [1457fc2903](https://linux-hardware.org/?probe=1457fc2903) | Aug 30, 2022 |
| Dell          | XPS 9320                    | [7fe70d3907](https://linux-hardware.org/?probe=7fe70d3907) | Aug 30, 2022 |
| Lenovo        | V330 81AX                   | [0699372547](https://linux-hardware.org/?probe=0699372547) | Aug 30, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [e5545fc36a](https://linux-hardware.org/?probe=e5545fc36a) | Aug 30, 2022 |
| Toshiba       | Satellite C845              | [58d3152512](https://linux-hardware.org/?probe=58d3152512) | Aug 29, 2022 |
| ASUSTek       | N550JV                      | [059ab7e21e](https://linux-hardware.org/?probe=059ab7e21e) | Aug 29, 2022 |
| HP            | EliteBook 8570w             | [907d5f36e6](https://linux-hardware.org/?probe=907d5f36e6) | Aug 29, 2022 |
| ASUSTek       | ROG Strix G513RW_G513RW     | [aa5f4a0207](https://linux-hardware.org/?probe=aa5f4a0207) | Aug 29, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [065da8ca1e](https://linux-hardware.org/?probe=065da8ca1e) | Aug 29, 2022 |
| Apple         | MacBook5,2                  | [780e5cbb44](https://linux-hardware.org/?probe=780e5cbb44) | Aug 28, 2022 |
| Dell          | XPS 13 9305                 | [d8bd3d6fc6](https://linux-hardware.org/?probe=d8bd3d6fc6) | Aug 28, 2022 |
| Lenovo        | ThinkPad W520 4270CTO       | [c4be3fe1b6](https://linux-hardware.org/?probe=c4be3fe1b6) | Aug 28, 2022 |
| Lenovo        | ThinkPad W520 4270CTO       | [568802fb43](https://linux-hardware.org/?probe=568802fb43) | Aug 28, 2022 |
| HP            | ENVY dv7                    | [cbd3824347](https://linux-hardware.org/?probe=cbd3824347) | Aug 28, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [2e085a419b](https://linux-hardware.org/?probe=2e085a419b) | Aug 27, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [c47cd7c7ed](https://linux-hardware.org/?probe=c47cd7c7ed) | Aug 27, 2022 |
| ASUSTek       | X556UQK                     | [262ff7d08a](https://linux-hardware.org/?probe=262ff7d08a) | Aug 27, 2022 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | [e3c7cd81e8](https://linux-hardware.org/?probe=e3c7cd81e8) | Aug 27, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [1746f3874c](https://linux-hardware.org/?probe=1746f3874c) | Aug 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [1c75cbf917](https://linux-hardware.org/?probe=1c75cbf917) | Aug 27, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [7f2e793766](https://linux-hardware.org/?probe=7f2e793766) | Aug 27, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [8aeb1b057b](https://linux-hardware.org/?probe=8aeb1b057b) | Aug 27, 2022 |
| Dell          | XPS 9315                    | [6ab1d7417d](https://linux-hardware.org/?probe=6ab1d7417d) | Aug 27, 2022 |
| Apple         | MacBook4,1                  | [fdb7c715b3](https://linux-hardware.org/?probe=fdb7c715b3) | Aug 26, 2022 |
| Panasonic     | FZ55-1                      | [a45848f10f](https://linux-hardware.org/?probe=a45848f10f) | Aug 26, 2022 |
| Acer          | Aspire A515-45              | [88467a99ae](https://linux-hardware.org/?probe=88467a99ae) | Aug 26, 2022 |
| Dell          | Precision M4600             | [de9a03d9be](https://linux-hardware.org/?probe=de9a03d9be) | Aug 26, 2022 |
| HP            | Laptop 15-da1xxx            | [51e23209a4](https://linux-hardware.org/?probe=51e23209a4) | Aug 26, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | [8aa6fdef16](https://linux-hardware.org/?probe=8aa6fdef16) | Aug 26, 2022 |
| Panasonic     | FZ55-1                      | [0ec106ca31](https://linux-hardware.org/?probe=0ec106ca31) | Aug 26, 2022 |
| Dell          | Precision M4600             | [83c727c6db](https://linux-hardware.org/?probe=83c727c6db) | Aug 26, 2022 |
| ASUSTek       | X540LJ                      | [edac754e93](https://linux-hardware.org/?probe=edac754e93) | Aug 25, 2022 |
| Acer          | Swift SFX14-41G             | [8d1cad5e52](https://linux-hardware.org/?probe=8d1cad5e52) | Aug 25, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [945109f9f8](https://linux-hardware.org/?probe=945109f9f8) | Aug 25, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 Ub 82KU    | [5237518074](https://linux-hardware.org/?probe=5237518074) | Aug 25, 2022 |
| HONOR         | NBR-WAX9                    | [7e2c842043](https://linux-hardware.org/?probe=7e2c842043) | Aug 25, 2022 |
| HUAWEI        | KPL-W0X                     | [b502ab922f](https://linux-hardware.org/?probe=b502ab922f) | Aug 25, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [b008775e13](https://linux-hardware.org/?probe=b008775e13) | Aug 24, 2022 |
| HP            | Dev One Notebook PC         | [4263165650](https://linux-hardware.org/?probe=4263165650) | Aug 24, 2022 |
| MSI           | Prestige 15 A10SC           | [35ffc8d54b](https://linux-hardware.org/?probe=35ffc8d54b) | Aug 23, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [6cb194ca87](https://linux-hardware.org/?probe=6cb194ca87) | Aug 23, 2022 |
| Acer          | Aspire V3-772G              | [92b070c9be](https://linux-hardware.org/?probe=92b070c9be) | Aug 23, 2022 |
| Positivo      | W942SV_SV1                  | [24ad2b387d](https://linux-hardware.org/?probe=24ad2b387d) | Aug 23, 2022 |
| ASUSTek       | X556UQK                     | [62dbb0625f](https://linux-hardware.org/?probe=62dbb0625f) | Aug 23, 2022 |
| ASUSTek       | X556UQK                     | [e5442dd2d4](https://linux-hardware.org/?probe=e5442dd2d4) | Aug 23, 2022 |
| MSI           | PS63 Modern 8RC             | [33a1092c01](https://linux-hardware.org/?probe=33a1092c01) | Aug 22, 2022 |
| Dell          | XPS 15 9520                 | [33ff4e4962](https://linux-hardware.org/?probe=33ff4e4962) | Aug 22, 2022 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [b41e95cd1b](https://linux-hardware.org/?probe=b41e95cd1b) | Aug 22, 2022 |
| Acer          | Swift SFX14-41G             | [959dda5404](https://linux-hardware.org/?probe=959dda5404) | Aug 22, 2022 |
| Apple         | MacBookPro6,1               | [52a1f16ef3](https://linux-hardware.org/?probe=52a1f16ef3) | Aug 22, 2022 |
| Apple         | MacBookPro6,1               | [ae19610f33](https://linux-hardware.org/?probe=ae19610f33) | Aug 21, 2022 |
| Acer          | Swift SFX14-41G             | [3de1fd7f2c](https://linux-hardware.org/?probe=3de1fd7f2c) | Aug 21, 2022 |
| System76      | Oryx Pro                    | [7c763e43c6](https://linux-hardware.org/?probe=7c763e43c6) | Aug 21, 2022 |
| Dell          | Inspiron 5547               | [f67221bd42](https://linux-hardware.org/?probe=f67221bd42) | Aug 21, 2022 |
| Acer          | Aspire 5740                 | [19158f2e35](https://linux-hardware.org/?probe=19158f2e35) | Aug 21, 2022 |
| HP            | ENVY TS m6 Sleekbook        | [314250b1d7](https://linux-hardware.org/?probe=314250b1d7) | Aug 21, 2022 |
| MSI           | Katana GF76 11UD            | [256a057752](https://linux-hardware.org/?probe=256a057752) | Aug 21, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | [9c31fff4b2](https://linux-hardware.org/?probe=9c31fff4b2) | Aug 20, 2022 |
| Dell          | Vostro 15 3515              | [3f12b83029](https://linux-hardware.org/?probe=3f12b83029) | Aug 20, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [0cef35b44a](https://linux-hardware.org/?probe=0cef35b44a) | Aug 20, 2022 |
| MSI           | GF63 Thin 10UC              | [b04f79d93a](https://linux-hardware.org/?probe=b04f79d93a) | Aug 20, 2022 |
| ASUSTek       | GL703VD                     | [54f9d46a7d](https://linux-hardware.org/?probe=54f9d46a7d) | Aug 19, 2022 |
| Gateway       | NV55C                       | [37dc8b6dd5](https://linux-hardware.org/?probe=37dc8b6dd5) | Aug 19, 2022 |
| Gateway       | NV55C                       | [377412b832](https://linux-hardware.org/?probe=377412b832) | Aug 18, 2022 |
| System76      | Oryx Pro                    | [1583fbab76](https://linux-hardware.org/?probe=1583fbab76) | Aug 18, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [0887012e66](https://linux-hardware.org/?probe=0887012e66) | Aug 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [5967f639c3](https://linux-hardware.org/?probe=5967f639c3) | Aug 16, 2022 |
| Acer          | Aspire A515-43              | [bec0e1fbd6](https://linux-hardware.org/?probe=bec0e1fbd6) | Aug 16, 2022 |
| Apple         | MacBookPro13,3              | [6cf76ee482](https://linux-hardware.org/?probe=6cf76ee482) | Aug 15, 2022 |
| Acer          | Aspire ES1-512              | [cb59c4a321](https://linux-hardware.org/?probe=cb59c4a321) | Aug 15, 2022 |
| Acer          | Aspire ES1-512              | [496f0834ae](https://linux-hardware.org/?probe=496f0834ae) | Aug 15, 2022 |
| ASUSTek       | UX310UQ                     | [f058aa0bf2](https://linux-hardware.org/?probe=f058aa0bf2) | Aug 15, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [332459de48](https://linux-hardware.org/?probe=332459de48) | Aug 15, 2022 |
| System76      | Oryx Pro                    | [b2c1b403b8](https://linux-hardware.org/?probe=b2c1b403b8) | Aug 14, 2022 |
| Acer          | Aspire 4752                 | [9854c38629](https://linux-hardware.org/?probe=9854c38629) | Aug 14, 2022 |
| MSI           | GF63 Thin 11UD              | [82bfe63c71](https://linux-hardware.org/?probe=82bfe63c71) | Aug 14, 2022 |
| MSI           | Prestige 15 A10SC           | [58d3be66c0](https://linux-hardware.org/?probe=58d3be66c0) | Aug 14, 2022 |
| Dell          | Latitude E7470              | [1c49732e63](https://linux-hardware.org/?probe=1c49732e63) | Aug 14, 2022 |
| Apple         | MacBookAir3,2               | [0756ed833b](https://linux-hardware.org/?probe=0756ed833b) | Aug 14, 2022 |
| Apple         | MacBookAir6,2               | [2c210a5825](https://linux-hardware.org/?probe=2c210a5825) | Aug 14, 2022 |
| Dell          | Inspiron 3521               | [ebf974be3e](https://linux-hardware.org/?probe=ebf974be3e) | Aug 13, 2022 |
| ASUSTek       | G74Sx                       | [309312e25d](https://linux-hardware.org/?probe=309312e25d) | Aug 13, 2022 |
| Dell          | Inspiron 3521               | [6dd71dbcf3](https://linux-hardware.org/?probe=6dd71dbcf3) | Aug 12, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [fa9cdcd977](https://linux-hardware.org/?probe=fa9cdcd977) | Aug 12, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [da7cc3fcb6](https://linux-hardware.org/?probe=da7cc3fcb6) | Aug 12, 2022 |
| HP            | EliteBook 840 G3            | [d7735b3387](https://linux-hardware.org/?probe=d7735b3387) | Aug 12, 2022 |
| Dell          | Inspiron N5110              | [74624820da](https://linux-hardware.org/?probe=74624820da) | Aug 12, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [5e0a6f08b1](https://linux-hardware.org/?probe=5e0a6f08b1) | Aug 12, 2022 |
| Dell          | Inspiron 13-7378            | [097cd944e0](https://linux-hardware.org/?probe=097cd944e0) | Aug 12, 2022 |
| HP            | Laptop 15-db1xxx            | [0644c9f46c](https://linux-hardware.org/?probe=0644c9f46c) | Aug 12, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | [688ae71abc](https://linux-hardware.org/?probe=688ae71abc) | Aug 12, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | [31a967ba05](https://linux-hardware.org/?probe=31a967ba05) | Aug 12, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | [ff6370169f](https://linux-hardware.org/?probe=ff6370169f) | Aug 11, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [fe91d8cdd3](https://linux-hardware.org/?probe=fe91d8cdd3) | Aug 11, 2022 |
| Dell          | XPS 9320                    | [bdb29b0481](https://linux-hardware.org/?probe=bdb29b0481) | Aug 11, 2022 |
| ASUSTek       | X455LJ                      | [f90572b8e2](https://linux-hardware.org/?probe=f90572b8e2) | Aug 11, 2022 |
| Lenovo        | ThinkPad T450s 20BWS1RT0... | [b2f479d0b0](https://linux-hardware.org/?probe=b2f479d0b0) | Aug 11, 2022 |
| HP            | ENVY TS m6 Sleekbook        | [1f0a966a58](https://linux-hardware.org/?probe=1f0a966a58) | Aug 11, 2022 |
| Dell          | XPS 9320                    | [1d0ef5711d](https://linux-hardware.org/?probe=1d0ef5711d) | Aug 11, 2022 |
| Acer          | Aspire 4736Z                | [16cf1afc2a](https://linux-hardware.org/?probe=16cf1afc2a) | Aug 11, 2022 |
| Dell          | Inspiron 13-7378            | [637b0f0905](https://linux-hardware.org/?probe=637b0f0905) | Aug 11, 2022 |
| System76      | Galago UltraPro             | [8c38c1dac4](https://linux-hardware.org/?probe=8c38c1dac4) | Aug 11, 2022 |
| Dell          | Latitude 3330               | [e1f58ad934](https://linux-hardware.org/?probe=e1f58ad934) | Aug 10, 2022 |
| Dell          | Latitude 3330               | [24c9c3fe68](https://linux-hardware.org/?probe=24c9c3fe68) | Aug 10, 2022 |
| Dell          | Inspiron 13-7378            | [4093a81a8d](https://linux-hardware.org/?probe=4093a81a8d) | Aug 10, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | [84453db535](https://linux-hardware.org/?probe=84453db535) | Aug 10, 2022 |
| ASUSTek       | K55A                        | [fb75627e6c](https://linux-hardware.org/?probe=fb75627e6c) | Aug 10, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | [87e84c988f](https://linux-hardware.org/?probe=87e84c988f) | Aug 10, 2022 |
| Fujitsu       | LIFEBOOK UH552              | [cbcfa4fc6e](https://linux-hardware.org/?probe=cbcfa4fc6e) | Aug 10, 2022 |
| Apple         | MacBookPro15,4              | [494f3495c8](https://linux-hardware.org/?probe=494f3495c8) | Aug 10, 2022 |
| Apple         | MacBookPro16,2              | [c0813b6c4e](https://linux-hardware.org/?probe=c0813b6c4e) | Aug 10, 2022 |
| Apple         | MacBookPro16,2              | [d93b98ed98](https://linux-hardware.org/?probe=d93b98ed98) | Aug 10, 2022 |
| GPU Compan... | GWTC116-2                   | [fa15ec0e79](https://linux-hardware.org/?probe=fa15ec0e79) | Aug 09, 2022 |
| MSI           | Creator Z16 Hiroshi F A1... | [6ca46e8126](https://linux-hardware.org/?probe=6ca46e8126) | Aug 09, 2022 |
| MSI           | Creator Z16 Hiroshi F A1... | [ad3cfbb4c9](https://linux-hardware.org/?probe=ad3cfbb4c9) | Aug 09, 2022 |
| HUAWEI        | NBD-WXX9                    | [6f0c6f7474](https://linux-hardware.org/?probe=6f0c6f7474) | Aug 09, 2022 |
| System76      | Gazelle                     | [a251ef0ac1](https://linux-hardware.org/?probe=a251ef0ac1) | Aug 08, 2022 |
| MSI           | GF63 Thin 11UD              | [29d3bf5483](https://linux-hardware.org/?probe=29d3bf5483) | Aug 08, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [10d18cd30b](https://linux-hardware.org/?probe=10d18cd30b) | Aug 08, 2022 |
| HP            | Laptop 14s-dk0xxx           | [49ab4e0197](https://linux-hardware.org/?probe=49ab4e0197) | Aug 08, 2022 |
| Dell          | XPS 13 7390                 | [15c1c667af](https://linux-hardware.org/?probe=15c1c667af) | Aug 08, 2022 |
| MSI           | GF63 Thin 11UD              | [d8a5d82c22](https://linux-hardware.org/?probe=d8a5d82c22) | Aug 08, 2022 |
| HP            | Laptop 15-db1xxx            | [9e849a1708](https://linux-hardware.org/?probe=9e849a1708) | Aug 07, 2022 |
| MSI           | GF63 Thin 11UD              | [53e660f72b](https://linux-hardware.org/?probe=53e660f72b) | Aug 07, 2022 |
| MSI           | GF63 Thin 11UD              | [67e1664484](https://linux-hardware.org/?probe=67e1664484) | Aug 07, 2022 |
| MSI           | GF63 Thin 11UD              | [ecb313e10d](https://linux-hardware.org/?probe=ecb313e10d) | Aug 07, 2022 |
| GPU Compan... | GWTN141-10                  | [c7a19f9e04](https://linux-hardware.org/?probe=c7a19f9e04) | Aug 07, 2022 |
| Avell High... | B.ON                        | [d16f62f2b9](https://linux-hardware.org/?probe=d16f62f2b9) | Aug 07, 2022 |
| HP            | Pavilion g7                 | [ecd57742f3](https://linux-hardware.org/?probe=ecd57742f3) | Aug 07, 2022 |
| Apple         | MacBookPro11,5              | [221e16bfb1](https://linux-hardware.org/?probe=221e16bfb1) | Aug 07, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [7e5a0c0004](https://linux-hardware.org/?probe=7e5a0c0004) | Aug 06, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [80794c55e8](https://linux-hardware.org/?probe=80794c55e8) | Aug 06, 2022 |
| GPU Compan... | GWTN141-10                  | [8a3db7da17](https://linux-hardware.org/?probe=8a3db7da17) | Aug 06, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [a711d41e0d](https://linux-hardware.org/?probe=a711d41e0d) | Aug 05, 2022 |
| Dell          | Inspiron 3480               | [637d2f9f41](https://linux-hardware.org/?probe=637d2f9f41) | Aug 05, 2022 |
| Lenovo        | XiaoXinPro 16 ARH7 82SN     | [abaec227ae](https://linux-hardware.org/?probe=abaec227ae) | Aug 05, 2022 |
| Lenovo        | XiaoXinPro 16 ARH7 82SN     | [a1effa04c3](https://linux-hardware.org/?probe=a1effa04c3) | Aug 05, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CH0... | [e4d16e5adf](https://linux-hardware.org/?probe=e4d16e5adf) | Aug 05, 2022 |
| Dell          | Inspiron 3583               | [508f6ab592](https://linux-hardware.org/?probe=508f6ab592) | Aug 04, 2022 |
| ASUSTek       | ROG Strix G713RS_G713RS     | [707ab083b3](https://linux-hardware.org/?probe=707ab083b3) | Aug 04, 2022 |
| HP            | ProBook 645 G1              | [0183d60d2c](https://linux-hardware.org/?probe=0183d60d2c) | Aug 04, 2022 |
| Lenovo        | V15-IIL 82C5                | [cc2c2e7ceb](https://linux-hardware.org/?probe=cc2c2e7ceb) | Aug 04, 2022 |
| Lenovo        | ThinkPad E470c 20H3A000C... | [047888752c](https://linux-hardware.org/?probe=047888752c) | Aug 04, 2022 |
| Lenovo        | V15-IIL 82C5                | [e0153e91b7](https://linux-hardware.org/?probe=e0153e91b7) | Aug 04, 2022 |
| Lenovo        | IdeaPad U410                | [048c78d129](https://linux-hardware.org/?probe=048c78d129) | Aug 04, 2022 |
| ASUSTek       | G550JK                      | [e73f25c149](https://linux-hardware.org/?probe=e73f25c149) | Aug 03, 2022 |
| Lenovo        | ThinkPad L590 20Q7001HGE    | [3549ef85b6](https://linux-hardware.org/?probe=3549ef85b6) | Aug 03, 2022 |
| Dell          | XPS 15 9520                 | [385e290982](https://linux-hardware.org/?probe=385e290982) | Aug 03, 2022 |
| Dell          | XPS 15 9520                 | [c7789bc8ca](https://linux-hardware.org/?probe=c7789bc8ca) | Aug 03, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [85f64b5fa5](https://linux-hardware.org/?probe=85f64b5fa5) | Aug 03, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | [06da05d12b](https://linux-hardware.org/?probe=06da05d12b) | Aug 03, 2022 |
| MSI           | GF63 Thin 11UD              | [bf4a2c0e11](https://linux-hardware.org/?probe=bf4a2c0e11) | Aug 03, 2022 |
| MSI           | GF63 Thin 11UD              | [f31ac48621](https://linux-hardware.org/?probe=f31ac48621) | Aug 03, 2022 |
| Dell          | Inspiron N5040              | [2da4d2a843](https://linux-hardware.org/?probe=2da4d2a843) | Aug 03, 2022 |
| MSI           | GF63 Thin 11UD              | [2e6cf4c0bd](https://linux-hardware.org/?probe=2e6cf4c0bd) | Aug 02, 2022 |
| Acer          | Aspire A115-32              | [d7eb24100d](https://linux-hardware.org/?probe=d7eb24100d) | Aug 02, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [ed743724e7](https://linux-hardware.org/?probe=ed743724e7) | Aug 02, 2022 |
| Lenovo        | Legion 5 15ITH6H 82JH       | [0b8452087a](https://linux-hardware.org/?probe=0b8452087a) | Aug 02, 2022 |
| Dell          | Latitude 5520               | [0406990128](https://linux-hardware.org/?probe=0406990128) | Aug 01, 2022 |
| Notebook      | NV4XMB,ME,MZ                | [7b369e1cdf](https://linux-hardware.org/?probe=7b369e1cdf) | Aug 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [4e2361dd88](https://linux-hardware.org/?probe=4e2361dd88) | Aug 01, 2022 |
| GPU Compan... | GWTN141-10                  | [d73365fe3e](https://linux-hardware.org/?probe=d73365fe3e) | Jul 31, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X51... | [bdc243bf9f](https://linux-hardware.org/?probe=bdc243bf9f) | Jul 31, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X51... | [41a0eba80f](https://linux-hardware.org/?probe=41a0eba80f) | Jul 31, 2022 |
| HP            | Pavilion 17                 | [b2c0846cf5](https://linux-hardware.org/?probe=b2c0846cf5) | Jul 31, 2022 |
| Acer          | Swift SF314-51              | [f9a61fd8ad](https://linux-hardware.org/?probe=f9a61fd8ad) | Jul 31, 2022 |
| Acer          | Swift SF314-43              | [36659d2410](https://linux-hardware.org/?probe=36659d2410) | Jul 30, 2022 |
| Toshiba       | Satellite C75D-C            | [f4a9c3bc7f](https://linux-hardware.org/?probe=f4a9c3bc7f) | Jul 30, 2022 |
| Toshiba       | Satellite C75D-C            | [f017593574](https://linux-hardware.org/?probe=f017593574) | Jul 30, 2022 |
| Dell          | Vostro 15 3515              | [74b9e88d97](https://linux-hardware.org/?probe=74b9e88d97) | Jul 30, 2022 |
| Intel Clie... | LAPKC71F                    | [0783ac445f](https://linux-hardware.org/?probe=0783ac445f) | Jul 30, 2022 |
| Lenovo        | ThinkPad P53 20QN003TUS     | [bf8e504209](https://linux-hardware.org/?probe=bf8e504209) | Jul 30, 2022 |
| PC Special... | NS50MU                      | [b5dd220296](https://linux-hardware.org/?probe=b5dd220296) | Jul 29, 2022 |
| Positivo      | C4128E-S                    | [a06c799159](https://linux-hardware.org/?probe=a06c799159) | Jul 29, 2022 |
| Lenovo        | ThinkPad P53 20QN003TUS     | [cf54e60bf1](https://linux-hardware.org/?probe=cf54e60bf1) | Jul 29, 2022 |
| GPU Compan... | GWTN141-10                  | [e392f0348d](https://linux-hardware.org/?probe=e392f0348d) | Jul 29, 2022 |
| GPU Compan... | GWTN141-10                  | [dea75365be](https://linux-hardware.org/?probe=dea75365be) | Jul 29, 2022 |
| HP            | Pavilion 13 x360 PC         | [a5220ea2c0](https://linux-hardware.org/?probe=a5220ea2c0) | Jul 28, 2022 |
| Dell          | Inspiron 3542               | [d0ff2340b1](https://linux-hardware.org/?probe=d0ff2340b1) | Jul 28, 2022 |
| Sony          | VPCEG27FM                   | [b8c840d19a](https://linux-hardware.org/?probe=b8c840d19a) | Jul 28, 2022 |
| MSI           | Modern 15 A5M               | [c6643cb779](https://linux-hardware.org/?probe=c6643cb779) | Jul 28, 2022 |
| MSI           | GF63 Thin 11UD              | [7c25b2c2c7](https://linux-hardware.org/?probe=7c25b2c2c7) | Jul 28, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [be9941b639](https://linux-hardware.org/?probe=be9941b639) | Jul 28, 2022 |
| MSI           | GF63 Thin 11UD              | [97bbabec13](https://linux-hardware.org/?probe=97bbabec13) | Jul 28, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | [c884d7548c](https://linux-hardware.org/?probe=c884d7548c) | Jul 28, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [56faf89859](https://linux-hardware.org/?probe=56faf89859) | Jul 28, 2022 |
| MSI           | Prestige 15 A10SC           | [0fe8633425](https://linux-hardware.org/?probe=0fe8633425) | Jul 27, 2022 |
| MSI           | Prestige 15 A10SC           | [36001f3112](https://linux-hardware.org/?probe=36001f3112) | Jul 27, 2022 |
| Dell          | Vostro 5470                 | [82192dcb1d](https://linux-hardware.org/?probe=82192dcb1d) | Jul 27, 2022 |
| Apple         | MacBookAir7,2               | [a33f728c24](https://linux-hardware.org/?probe=a33f728c24) | Jul 27, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | [8e76bb6095](https://linux-hardware.org/?probe=8e76bb6095) | Jul 27, 2022 |
| HP            | Pavilion dv6                | [577c3ce56c](https://linux-hardware.org/?probe=577c3ce56c) | Jul 27, 2022 |
| Sony          | VPCF11M1E                   | [97a18303ee](https://linux-hardware.org/?probe=97a18303ee) | Jul 26, 2022 |
| MSI           | GF63 Thin 11UD              | [ce18b4e9ab](https://linux-hardware.org/?probe=ce18b4e9ab) | Jul 26, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [04ae47501b](https://linux-hardware.org/?probe=04ae47501b) | Jul 26, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [7005989783](https://linux-hardware.org/?probe=7005989783) | Jul 26, 2022 |
| Acer          | Ferrari One 200             | [023ff9a691](https://linux-hardware.org/?probe=023ff9a691) | Jul 25, 2022 |
| Acer          | Ferrari One 200             | [447f8a06ea](https://linux-hardware.org/?probe=447f8a06ea) | Jul 25, 2022 |
| System76      | Lemur Pro                   | [c6269208fe](https://linux-hardware.org/?probe=c6269208fe) | Jul 25, 2022 |
| Acer          | Nitro AN515-42              | [8c5e11fe0e](https://linux-hardware.org/?probe=8c5e11fe0e) | Jul 25, 2022 |
| Dynabook      | Satellite Pro C50D-B        | [bd7ef0af73](https://linux-hardware.org/?probe=bd7ef0af73) | Jul 25, 2022 |
| GPU Compan... | GWTC116-2                   | [ac0f2b51c0](https://linux-hardware.org/?probe=ac0f2b51c0) | Jul 25, 2022 |
| MSI           | GF63 Thin 11UD              | [03bb89eced](https://linux-hardware.org/?probe=03bb89eced) | Jul 24, 2022 |
| Lenovo        | E41-25 81FS                 | [51b984566a](https://linux-hardware.org/?probe=51b984566a) | Jul 24, 2022 |
| Acer          | Aspire V3-551G              | [970f226406](https://linux-hardware.org/?probe=970f226406) | Jul 24, 2022 |
| MSI           | GF63 Thin 11UD              | [d41e7515af](https://linux-hardware.org/?probe=d41e7515af) | Jul 24, 2022 |
| MSI           | GF63 Thin 11UD              | [fdada0c3a6](https://linux-hardware.org/?probe=fdada0c3a6) | Jul 24, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [c1515e724a](https://linux-hardware.org/?probe=c1515e724a) | Jul 24, 2022 |
| Timi          | Redmi Book Pro 15 2022      | [147556bf0a](https://linux-hardware.org/?probe=147556bf0a) | Jul 23, 2022 |
| Apple         | MacBookPro12,1              | [752155f862](https://linux-hardware.org/?probe=752155f862) | Jul 23, 2022 |
| Apple         | MacBookPro8,2               | [e31685e3ae](https://linux-hardware.org/?probe=e31685e3ae) | Jul 23, 2022 |
| Apple         | MacBookAir7,2               | [a86b33bdc2](https://linux-hardware.org/?probe=a86b33bdc2) | Jul 22, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [f9e9de55c0](https://linux-hardware.org/?probe=f9e9de55c0) | Jul 22, 2022 |
| Dell          | Vostro 5470                 | [95c9916b84](https://linux-hardware.org/?probe=95c9916b84) | Jul 22, 2022 |
| ASUSTek       | K52Dr                       | [efd71c663d](https://linux-hardware.org/?probe=efd71c663d) | Jul 22, 2022 |
| ASUSTek       | K93SM                       | [add292129b](https://linux-hardware.org/?probe=add292129b) | Jul 22, 2022 |
| Samsung       | 760XDA                      | [c3e04193b8](https://linux-hardware.org/?probe=c3e04193b8) | Jul 22, 2022 |
| GPU Compan... | GWTC116-2                   | [4763ba77ba](https://linux-hardware.org/?probe=4763ba77ba) | Jul 22, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [da25f9d9b4](https://linux-hardware.org/?probe=da25f9d9b4) | Jul 22, 2022 |
| HP            | ProBook 450 G3              | [c35f07bb03](https://linux-hardware.org/?probe=c35f07bb03) | Jul 21, 2022 |
| HP            | ProBook 450 G3              | [a1cab26fa9](https://linux-hardware.org/?probe=a1cab26fa9) | Jul 21, 2022 |
| Lenovo        | ThinkPad P52 20MAS1R100     | [7a01b8819c](https://linux-hardware.org/?probe=7a01b8819c) | Jul 21, 2022 |
| Notebook      | NV4XMB,ME,MZ                | [f965008c98](https://linux-hardware.org/?probe=f965008c98) | Jul 21, 2022 |
| Toshiba       | BLB                         | [997a7c93d7](https://linux-hardware.org/?probe=997a7c93d7) | Jul 21, 2022 |
| Dell          | Vostro 5470                 | [e73fa302e0](https://linux-hardware.org/?probe=e73fa302e0) | Jul 21, 2022 |
| HP            | ZBook Firefly 14 G7 Mobi... | [ed3f7b7f50](https://linux-hardware.org/?probe=ed3f7b7f50) | Jul 21, 2022 |
| Dell          | Vostro 5470                 | [c6dcb4ffa6](https://linux-hardware.org/?probe=c6dcb4ffa6) | Jul 21, 2022 |
| Apple         | MacBookPro9,2               | [add1e46d7e](https://linux-hardware.org/?probe=add1e46d7e) | Jul 20, 2022 |
| Acer          | Aspire V3-551G              | [f5675c45dc](https://linux-hardware.org/?probe=f5675c45dc) | Jul 20, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YES... | [48e2fa9544](https://linux-hardware.org/?probe=48e2fa9544) | Jul 19, 2022 |
| ASUSTek       | K52Dr                       | [31471e3583](https://linux-hardware.org/?probe=31471e3583) | Jul 19, 2022 |
| Apple         | MacBookPro5,1               | [8a81341ecd](https://linux-hardware.org/?probe=8a81341ecd) | Jul 18, 2022 |
| Dell          | Latitude D430               | [22c020a070](https://linux-hardware.org/?probe=22c020a070) | Jul 18, 2022 |
| HP            | Laptop 14-bw0xx             | [df814add04](https://linux-hardware.org/?probe=df814add04) | Jul 18, 2022 |
| Acer          | Aspire V3-551G              | [2baa51bbc9](https://linux-hardware.org/?probe=2baa51bbc9) | Jul 18, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [b903541b55](https://linux-hardware.org/?probe=b903541b55) | Jul 18, 2022 |
| ASUSTek       | X555LAB                     | [8ae373a79c](https://linux-hardware.org/?probe=8ae373a79c) | Jul 17, 2022 |
| Acer          | Aspire 5520                 | [a471c15853](https://linux-hardware.org/?probe=a471c15853) | Jul 17, 2022 |
| ASUSTek       | K53SJ                       | [515f269efc](https://linux-hardware.org/?probe=515f269efc) | Jul 17, 2022 |
| Gigabyte      | Blade Pro                   | [3c2576e897](https://linux-hardware.org/?probe=3c2576e897) | Jul 16, 2022 |
| MSI           | GS75 Stealth 9SG            | [8707f3e800](https://linux-hardware.org/?probe=8707f3e800) | Jul 16, 2022 |
| Alienware     | 15 R2                       | [8a6bd6054f](https://linux-hardware.org/?probe=8a6bd6054f) | Jul 16, 2022 |
| MSI           | Katana GF76 11UD            | [61b03607fa](https://linux-hardware.org/?probe=61b03607fa) | Jul 15, 2022 |
| Dell          | Precision M4600             | [96f8364d87](https://linux-hardware.org/?probe=96f8364d87) | Jul 15, 2022 |
| HUAWEI        | MACH-WX9                    | [76035ea427](https://linux-hardware.org/?probe=76035ea427) | Jul 15, 2022 |
| HP            | Laptop 17z-ca200            | [1159e9b888](https://linux-hardware.org/?probe=1159e9b888) | Jul 15, 2022 |
| System76      | Pangolin                    | [690b7b5984](https://linux-hardware.org/?probe=690b7b5984) | Jul 15, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [1dac03f80a](https://linux-hardware.org/?probe=1dac03f80a) | Jul 15, 2022 |
| ASUSTek       | X555LAB                     | [5c5b387f6c](https://linux-hardware.org/?probe=5c5b387f6c) | Jul 14, 2022 |
| Dell          | XPS 15 9520                 | [271277c36b](https://linux-hardware.org/?probe=271277c36b) | Jul 14, 2022 |
| Lenovo        | ThinkPad X230 2325YHU       | [4720a42a7f](https://linux-hardware.org/?probe=4720a42a7f) | Jul 14, 2022 |
| HP            | Laptop 14-fq0xxx            | [c21113bf90](https://linux-hardware.org/?probe=c21113bf90) | Jul 14, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [285e41f0aa](https://linux-hardware.org/?probe=285e41f0aa) | Jul 14, 2022 |
| Samsung       | 950XED                      | [b7f59889a0](https://linux-hardware.org/?probe=b7f59889a0) | Jul 14, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [27f79db974](https://linux-hardware.org/?probe=27f79db974) | Jul 13, 2022 |
| MSI           | GF63 Thin 11UD              | [b4cf81df26](https://linux-hardware.org/?probe=b4cf81df26) | Jul 13, 2022 |
| Lenovo        | Legion Y540-17IRH 81UJ      | [b70dfefc75](https://linux-hardware.org/?probe=b70dfefc75) | Jul 13, 2022 |
| MSI           | GF63 Thin 11UD              | [7107c7c2eb](https://linux-hardware.org/?probe=7107c7c2eb) | Jul 13, 2022 |
| Dell          | Latitude 3500               | [f42f32c17f](https://linux-hardware.org/?probe=f42f32c17f) | Jul 12, 2022 |
| HP            | EliteBook 8570w             | [495c5afa4b](https://linux-hardware.org/?probe=495c5afa4b) | Jul 12, 2022 |
| Apple         | MacBookPro10,2              | [facbace782](https://linux-hardware.org/?probe=facbace782) | Jul 12, 2022 |
| Apple         | MacBookPro10,2              | [9cc1538196](https://linux-hardware.org/?probe=9cc1538196) | Jul 12, 2022 |
| ASUSTek       | K53SJ                       | [f3ead95b28](https://linux-hardware.org/?probe=f3ead95b28) | Jul 12, 2022 |
| GPU Compan... | GWTN141-10                  | [0ce04e7b03](https://linux-hardware.org/?probe=0ce04e7b03) | Jul 12, 2022 |
| Apple         | MacBookPro7,1               | [821459e114](https://linux-hardware.org/?probe=821459e114) | Jul 12, 2022 |
| Dell          | Vostro 5470                 | [aedb7a18da](https://linux-hardware.org/?probe=aedb7a18da) | Jul 11, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [34c2c24b3b](https://linux-hardware.org/?probe=34c2c24b3b) | Jul 11, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | [ebbc4ebc1d](https://linux-hardware.org/?probe=ebbc4ebc1d) | Jul 11, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | [d200cc6f06](https://linux-hardware.org/?probe=d200cc6f06) | Jul 11, 2022 |
| Lenovo        | 14w 81MQ0013AU              | [a93743a911](https://linux-hardware.org/?probe=a93743a911) | Jul 11, 2022 |
| ASUSTek       | K53SJ                       | [1a9d6df3b5](https://linux-hardware.org/?probe=1a9d6df3b5) | Jul 11, 2022 |
| Dell          | Latitude E5440              | [2b94e70ac9](https://linux-hardware.org/?probe=2b94e70ac9) | Jul 11, 2022 |
| Dell          | Inspiron 1750               | [c39e03e656](https://linux-hardware.org/?probe=c39e03e656) | Jul 10, 2022 |
| MSI           | Katana GF76 11UG            | [8f152d3669](https://linux-hardware.org/?probe=8f152d3669) | Jul 10, 2022 |
| Dell          | Inspiron 1750               | [a885fd8b41](https://linux-hardware.org/?probe=a885fd8b41) | Jul 10, 2022 |
| Medion        | Erazer P6661 MD60303        | [35fbb2c055](https://linux-hardware.org/?probe=35fbb2c055) | Jul 10, 2022 |
| Apple         | MacBookPro11,3              | [9b65b57a57](https://linux-hardware.org/?probe=9b65b57a57) | Jul 10, 2022 |
| Acer          | Aspire A515-52              | [9dc5c32b9f](https://linux-hardware.org/?probe=9dc5c32b9f) | Jul 09, 2022 |
| Lenovo        | ThinkPad T480s 20L8S2330... | [4718003bb5](https://linux-hardware.org/?probe=4718003bb5) | Jul 09, 2022 |
| Dell          | Latitude E7450              | [d0c3f69765](https://linux-hardware.org/?probe=d0c3f69765) | Jul 09, 2022 |
| MSI           | MS-16G4                     | [53f40f3420](https://linux-hardware.org/?probe=53f40f3420) | Jul 09, 2022 |
| Dell          | Vostro 15 3515              | [38e90a5b4d](https://linux-hardware.org/?probe=38e90a5b4d) | Jul 08, 2022 |
| Apple         | MacBookPro9,2               | [663a6c9413](https://linux-hardware.org/?probe=663a6c9413) | Jul 08, 2022 |
| ASUSTek       | G751JT                      | [92eb60a700](https://linux-hardware.org/?probe=92eb60a700) | Jul 08, 2022 |
| Panasonic     | CF-C2AQAZXLM                | [be9cf3127a](https://linux-hardware.org/?probe=be9cf3127a) | Jul 08, 2022 |
| ASUSTek       | K53SJ                       | [f9d5ea94ec](https://linux-hardware.org/?probe=f9d5ea94ec) | Jul 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | [e34a9c3166](https://linux-hardware.org/?probe=e34a9c3166) | Jul 08, 2022 |
| ASUSTek       | X55CR                       | [9e40e3f8ad](https://linux-hardware.org/?probe=9e40e3f8ad) | Jul 08, 2022 |
| HUAWEI        | MACH-WX9                    | [486d051b71](https://linux-hardware.org/?probe=486d051b71) | Jul 08, 2022 |
| Dell          | Vostro 5625                 | [b2fde3bdef](https://linux-hardware.org/?probe=b2fde3bdef) | Jul 07, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | [3b7528beab](https://linux-hardware.org/?probe=3b7528beab) | Jul 07, 2022 |
| System76      | Lemur Pro                   | [bdc2ddb608](https://linux-hardware.org/?probe=bdc2ddb608) | Jul 07, 2022 |
| Toshiba       | Satellite L650              | [76de8069a0](https://linux-hardware.org/?probe=76de8069a0) | Jul 07, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [861d7b3714](https://linux-hardware.org/?probe=861d7b3714) | Jul 07, 2022 |
| Acer          | Nitro AN515-53              | [d31c5d1c11](https://linux-hardware.org/?probe=d31c5d1c11) | Jul 06, 2022 |
| Acer          | Nitro AN515-53              | [0304267499](https://linux-hardware.org/?probe=0304267499) | Jul 06, 2022 |
| Pegatron      | H36FF                       | [87eac99d1b](https://linux-hardware.org/?probe=87eac99d1b) | Jul 06, 2022 |
| Acer          | Aspire E3-112M              | [6de763aad6](https://linux-hardware.org/?probe=6de763aad6) | Jul 06, 2022 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | [a9d516466a](https://linux-hardware.org/?probe=a9d516466a) | Jul 06, 2022 |
| ASUSTek       | K50ID                       | [a194cebb73](https://linux-hardware.org/?probe=a194cebb73) | Jul 06, 2022 |
| ASUSTek       | K50ID                       | [90ccec43bf](https://linux-hardware.org/?probe=90ccec43bf) | Jul 06, 2022 |
| HP            | EliteBook 745 G2            | [21b712ca64](https://linux-hardware.org/?probe=21b712ca64) | Jul 05, 2022 |
| MSI           | Katana GF76 11UD            | [ece534d446](https://linux-hardware.org/?probe=ece534d446) | Jul 05, 2022 |
| MSI           | Katana GF76 11UD            | [1c52419886](https://linux-hardware.org/?probe=1c52419886) | Jul 05, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [b4732a4bda](https://linux-hardware.org/?probe=b4732a4bda) | Jul 05, 2022 |
| Dell          | Precision M4700             | [48cbbf8dd2](https://linux-hardware.org/?probe=48cbbf8dd2) | Jul 05, 2022 |
| Dell          | Latitude 7280               | [b7ed5b72a9](https://linux-hardware.org/?probe=b7ed5b72a9) | Jul 05, 2022 |
| HP            | ProBook 640 G1              | [2f88b6162e](https://linux-hardware.org/?probe=2f88b6162e) | Jul 05, 2022 |
| HP            | Pavilion 15                 | [abbd7fd848](https://linux-hardware.org/?probe=abbd7fd848) | Jul 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [a673b1557d](https://linux-hardware.org/?probe=a673b1557d) | Jul 05, 2022 |
| Toshiba       | Satellite C650D             | [23da2ae018](https://linux-hardware.org/?probe=23da2ae018) | Jul 04, 2022 |
| Apple         | MacBookPro10,2              | [40d0cb89c5](https://linux-hardware.org/?probe=40d0cb89c5) | Jul 04, 2022 |
| Acer          | Aspire E1-572G              | [6f24a453bf](https://linux-hardware.org/?probe=6f24a453bf) | Jul 04, 2022 |
| Lenovo        | ThinkPad T440p 20AN009CU... | [67d4a66421](https://linux-hardware.org/?probe=67d4a66421) | Jul 04, 2022 |
| ASUSTek       | X541UJ                      | [d3f8e6dee5](https://linux-hardware.org/?probe=d3f8e6dee5) | Jul 04, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [903fedb0aa](https://linux-hardware.org/?probe=903fedb0aa) | Jul 03, 2022 |
| Notebook      | P65xHP                      | [2b81391bb4](https://linux-hardware.org/?probe=2b81391bb4) | Jul 03, 2022 |
| MSI           | MPG B550 GAMING CARBON W... | [80c5bb3483](https://linux-hardware.org/?probe=80c5bb3483) | Jul 03, 2022 |
| Acer          | Aspire A515-51G             | [98ef915ec8](https://linux-hardware.org/?probe=98ef915ec8) | Jul 03, 2022 |
| Acer          | Aspire E5-473G              | [11b488a036](https://linux-hardware.org/?probe=11b488a036) | Jul 03, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [8999ce3eca](https://linux-hardware.org/?probe=8999ce3eca) | Jul 03, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [6e6839a1d0](https://linux-hardware.org/?probe=6e6839a1d0) | Jul 03, 2022 |
| ASUSTek       | G751JT                      | [f437b1ee99](https://linux-hardware.org/?probe=f437b1ee99) | Jul 03, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [a8c5e48dc8](https://linux-hardware.org/?probe=a8c5e48dc8) | Jul 03, 2022 |
| Dell          | Latitude E6420              | [ede3298bf4](https://linux-hardware.org/?probe=ede3298bf4) | Jul 02, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [fdb841889e](https://linux-hardware.org/?probe=fdb841889e) | Jul 02, 2022 |
| ASUSTek       | TUF Gaming FX705DD_FX705... | [048a900062](https://linux-hardware.org/?probe=048a900062) | Jul 02, 2022 |
| Lenovo        | Y720-15IKB 80VR             | [516b60430c](https://linux-hardware.org/?probe=516b60430c) | Jul 02, 2022 |
| Lenovo        | Y720-15IKB 80VR             | [c70a95cfc1](https://linux-hardware.org/?probe=c70a95cfc1) | Jul 02, 2022 |
| Apple         | MacBookPro9,2               | [4f6364d861](https://linux-hardware.org/?probe=4f6364d861) | Jul 02, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [eef50332e8](https://linux-hardware.org/?probe=eef50332e8) | Jul 02, 2022 |
| Dell          | Precision 7510              | [4831b50f9a](https://linux-hardware.org/?probe=4831b50f9a) | Jul 02, 2022 |
| MSI           | GF63 Thin 11UD              | [7847c0275c](https://linux-hardware.org/?probe=7847c0275c) | Jul 02, 2022 |
| MSI           | GF63 Thin 11UD              | [6b1e1133e4](https://linux-hardware.org/?probe=6b1e1133e4) | Jul 01, 2022 |
| Dell          | Precision M4600             | [ea07b9e45f](https://linux-hardware.org/?probe=ea07b9e45f) | Jul 01, 2022 |
| Dell          | Precision M4600             | [535d6029bc](https://linux-hardware.org/?probe=535d6029bc) | Jul 01, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [10ff366630](https://linux-hardware.org/?probe=10ff366630) | Jul 01, 2022 |
| Samsung       | 930XED                      | [56a04fa69d](https://linux-hardware.org/?probe=56a04fa69d) | Jul 01, 2022 |
| ASUSTek       | S550CA                      | [8ed63bbdfd](https://linux-hardware.org/?probe=8ed63bbdfd) | Jul 01, 2022 |
| Dell          | Precision 5530              | [d6dc0ecd91](https://linux-hardware.org/?probe=d6dc0ecd91) | Jul 01, 2022 |
| Dell          | Precision 5550              | [0ddb8905e5](https://linux-hardware.org/?probe=0ddb8905e5) | Jul 01, 2022 |
| MSI           | GF63 Thin 11UD              | [63508059d3](https://linux-hardware.org/?probe=63508059d3) | Jul 01, 2022 |
| MSI           | GF63 Thin 11UD              | [b7aef43e9e](https://linux-hardware.org/?probe=b7aef43e9e) | Jul 01, 2022 |
| MSI           | GF63 Thin 11UD              | [325fec2ac6](https://linux-hardware.org/?probe=325fec2ac6) | Jul 01, 2022 |
| HP            | Pavilion 15                 | [e35e3b2e52](https://linux-hardware.org/?probe=e35e3b2e52) | Jul 01, 2022 |
| Dell          | Precision 7510              | [c82cc3cb0f](https://linux-hardware.org/?probe=c82cc3cb0f) | Jul 01, 2022 |
| Dell          | Inspiron 5547               | [c2a91cc81e](https://linux-hardware.org/?probe=c2a91cc81e) | Jul 01, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [ccb50bd0f4](https://linux-hardware.org/?probe=ccb50bd0f4) | Jun 30, 2022 |
| Apple         | MacBookAir7,2               | [ab31abf1d5](https://linux-hardware.org/?probe=ab31abf1d5) | Jun 30, 2022 |
| HP            | Pavilion 15                 | [f76f8dff7a](https://linux-hardware.org/?probe=f76f8dff7a) | Jun 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [6095915fb5](https://linux-hardware.org/?probe=6095915fb5) | Jun 30, 2022 |
| HP            | ProBook 445 G8 Notebook ... | [35ca7c4868](https://linux-hardware.org/?probe=35ca7c4868) | Jun 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [1f66ba5535](https://linux-hardware.org/?probe=1f66ba5535) | Jun 30, 2022 |
| Notebook      | P7xxDM3(-G)                 | [6abdc9b40d](https://linux-hardware.org/?probe=6abdc9b40d) | Jun 29, 2022 |
| Dell          | Latitude E5470              | [2440e59a5a](https://linux-hardware.org/?probe=2440e59a5a) | Jun 29, 2022 |
| Dell          | Inspiron 7460               | [c5e8b7f098](https://linux-hardware.org/?probe=c5e8b7f098) | Jun 29, 2022 |
| Eluktronic... | MECH-15 G3                  | [d307b13800](https://linux-hardware.org/?probe=d307b13800) | Jun 28, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [c14a32dd6b](https://linux-hardware.org/?probe=c14a32dd6b) | Jun 28, 2022 |
| ASUSTek       | S550CA                      | [93807824df](https://linux-hardware.org/?probe=93807824df) | Jun 28, 2022 |
| ASUSTek       | ROG Strix G512LW_G512LW     | [843cbccc63](https://linux-hardware.org/?probe=843cbccc63) | Jun 27, 2022 |
| HP            | Pavilion Notebook           | [8e17cfd388](https://linux-hardware.org/?probe=8e17cfd388) | Jun 26, 2022 |
| HP            | EliteBook 820 G2            | [e568c96372](https://linux-hardware.org/?probe=e568c96372) | Jun 25, 2022 |
| Lenovo        | ThinkPad X230 23331R5       | [c6589e02c4](https://linux-hardware.org/?probe=c6589e02c4) | Jun 25, 2022 |
| Dell          | Vostro 3460                 | [90c701411f](https://linux-hardware.org/?probe=90c701411f) | Jun 25, 2022 |
| Dell          | Vostro 3460                 | [fb02c13e80](https://linux-hardware.org/?probe=fb02c13e80) | Jun 25, 2022 |
| HUAWEI        | MACHC-WAX9                  | [00089c4dbe](https://linux-hardware.org/?probe=00089c4dbe) | Jun 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [490c1074fe](https://linux-hardware.org/?probe=490c1074fe) | Jun 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [51d3a22bf6](https://linux-hardware.org/?probe=51d3a22bf6) | Jun 25, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [289b09bf25](https://linux-hardware.org/?probe=289b09bf25) | Jun 24, 2022 |
| System76      | Darter Pro                  | [db7f217878](https://linux-hardware.org/?probe=db7f217878) | Jun 24, 2022 |
| HP            | EliteBook 745 G2            | [fe87d16f84](https://linux-hardware.org/?probe=fe87d16f84) | Jun 24, 2022 |
| Dell          | Latitude E7470              | [c2a22e5a3d](https://linux-hardware.org/?probe=c2a22e5a3d) | Jun 24, 2022 |
| Dell          | Latitude E7470              | [962571591a](https://linux-hardware.org/?probe=962571591a) | Jun 24, 2022 |
| Alienware     | 14                          | [8846f2e474](https://linux-hardware.org/?probe=8846f2e474) | Jun 24, 2022 |
| Toshiba       | Satellite S50-A             | [c2e7c1b26d](https://linux-hardware.org/?probe=c2e7c1b26d) | Jun 24, 2022 |
| ASUSTek       | S550CA                      | [c7c236e5a1](https://linux-hardware.org/?probe=c7c236e5a1) | Jun 23, 2022 |
| Acer          | Swift SF314-54              | [47420af7dc](https://linux-hardware.org/?probe=47420af7dc) | Jun 23, 2022 |
| Dell          | Vostro 5470                 | [592f0a2f63](https://linux-hardware.org/?probe=592f0a2f63) | Jun 23, 2022 |
| Dell          | Precision 5520              | [2216faa750](https://linux-hardware.org/?probe=2216faa750) | Jun 22, 2022 |
| Dell          | Inspiron 7560               | [a65b832b57](https://linux-hardware.org/?probe=a65b832b57) | Jun 22, 2022 |
| Lenovo        | V14-IIL 82C4                | [c288025720](https://linux-hardware.org/?probe=c288025720) | Jun 21, 2022 |
| HP            | Dev One Notebook PC         | [3086580cf5](https://linux-hardware.org/?probe=3086580cf5) | Jun 21, 2022 |
| HP            | Dev One Notebook PC         | [0bc7456f92](https://linux-hardware.org/?probe=0bc7456f92) | Jun 21, 2022 |
| Dell          | Latitude E7240              | [1c76f3cdf4](https://linux-hardware.org/?probe=1c76f3cdf4) | Jun 21, 2022 |
| Quanta        | TWC                         | [6a466d7eac](https://linux-hardware.org/?probe=6a466d7eac) | Jun 21, 2022 |
| Dell          | Latitude E7240              | [2974c5fa7c](https://linux-hardware.org/?probe=2974c5fa7c) | Jun 21, 2022 |
| Dell          | XPS 15 9570                 | [c6c4eda2cb](https://linux-hardware.org/?probe=c6c4eda2cb) | Jun 21, 2022 |
| System76      | Lemur Pro                   | [0350f8d8f7](https://linux-hardware.org/?probe=0350f8d8f7) | Jun 21, 2022 |
| HP            | ProBook 440 G7              | [3bbbcaea72](https://linux-hardware.org/?probe=3bbbcaea72) | Jun 20, 2022 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | [faa0749731](https://linux-hardware.org/?probe=faa0749731) | Jun 20, 2022 |
| Acer          | Iconia                      | [2d1f1a2c32](https://linux-hardware.org/?probe=2d1f1a2c32) | Jun 20, 2022 |
| MSI           | Pulse GL66 12UEK            | [9bffffd652](https://linux-hardware.org/?probe=9bffffd652) | Jun 20, 2022 |
| MSI           | Pulse GL66 12UEK            | [a8d859700b](https://linux-hardware.org/?probe=a8d859700b) | Jun 20, 2022 |
| HP            | ZBook 15 G3                 | [8c6f371222](https://linux-hardware.org/?probe=8c6f371222) | Jun 19, 2022 |
| ASUSTek       | N550JV                      | [d1d647724c](https://linux-hardware.org/?probe=d1d647724c) | Jun 19, 2022 |
| Apple         | MacBookPro11,1              | [b88b88ba84](https://linux-hardware.org/?probe=b88b88ba84) | Jun 19, 2022 |
| Apple         | MacBookPro11,1              | [ec132b0ba5](https://linux-hardware.org/?probe=ec132b0ba5) | Jun 19, 2022 |
| Dell          | Inspiron 5537               | [2b31dedd45](https://linux-hardware.org/?probe=2b31dedd45) | Jun 19, 2022 |
| HP            | 15 Notebook PC              | [b3efe3d4b5](https://linux-hardware.org/?probe=b3efe3d4b5) | Jun 19, 2022 |
| Apple         | MacBookPro11,5              | [b04866cc36](https://linux-hardware.org/?probe=b04866cc36) | Jun 19, 2022 |
| Apple         | MacBook5,1                  | [e601e834f2](https://linux-hardware.org/?probe=e601e834f2) | Jun 18, 2022 |
| Lenovo        | ThinkPad X240 20AMS75900    | [47b7f42708](https://linux-hardware.org/?probe=47b7f42708) | Jun 18, 2022 |
| Lenovo        | ThinkPad X240 20AMS75900    | [e0eb6f7475](https://linux-hardware.org/?probe=e0eb6f7475) | Jun 18, 2022 |
| Dell          | XPS 13 7390                 | [6d1dcb879d](https://linux-hardware.org/?probe=6d1dcb879d) | Jun 18, 2022 |
| Apple         | MacBookPro7,1               | [41eb5a7de2](https://linux-hardware.org/?probe=41eb5a7de2) | Jun 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [cb268bf1ab](https://linux-hardware.org/?probe=cb268bf1ab) | Jun 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [ed83fdd673](https://linux-hardware.org/?probe=ed83fdd673) | Jun 18, 2022 |
| Lenovo        | ThinkPad T450 20BUS1110E    | [77dd393da8](https://linux-hardware.org/?probe=77dd393da8) | Jun 18, 2022 |
| Apple         | MacBookPro7,1               | [d542c2f694](https://linux-hardware.org/?probe=d542c2f694) | Jun 18, 2022 |
| Dell          | Latitude E7240              | [2ed64f08f3](https://linux-hardware.org/?probe=2ed64f08f3) | Jun 17, 2022 |
| Dell          | Latitude E7240              | [31340542c2](https://linux-hardware.org/?probe=31340542c2) | Jun 17, 2022 |
| HP            | Unknown                     | [4c4cdf6526](https://linux-hardware.org/?probe=4c4cdf6526) | Jun 17, 2022 |
| Apple         | MacBookAir7,2               | [13d72fd6f0](https://linux-hardware.org/?probe=13d72fd6f0) | Jun 17, 2022 |
| Dell          | Latitude E7240              | [08efb8dcc5](https://linux-hardware.org/?probe=08efb8dcc5) | Jun 17, 2022 |
| Schenker      | VIA 15 Pro                  | [1d1727713f](https://linux-hardware.org/?probe=1d1727713f) | Jun 17, 2022 |
| HP            | EliteBook 8560p             | [8f60c0fb25](https://linux-hardware.org/?probe=8f60c0fb25) | Jun 17, 2022 |
| Dell          | Precision 5540              | [6d3f2c188b](https://linux-hardware.org/?probe=6d3f2c188b) | Jun 17, 2022 |
| Acer          | Aspire E5-574G              | [23c2dd37fe](https://linux-hardware.org/?probe=23c2dd37fe) | Jun 17, 2022 |
| Dell          | Latitude E7240              | [b6978a823c](https://linux-hardware.org/?probe=b6978a823c) | Jun 17, 2022 |
| Acer          | Aspire 4741                 | [9f25816784](https://linux-hardware.org/?probe=9f25816784) | Jun 16, 2022 |
| Dell          | Inspiron 3442               | [10304caa6b](https://linux-hardware.org/?probe=10304caa6b) | Jun 16, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [b136496151](https://linux-hardware.org/?probe=b136496151) | Jun 16, 2022 |
| System76      | Oryx Pro                    | [4daa6c7d77](https://linux-hardware.org/?probe=4daa6c7d77) | Jun 16, 2022 |
| Dell          | Latitude E6540              | [93f049609f](https://linux-hardware.org/?probe=93f049609f) | Jun 16, 2022 |
| System76      | Galago Pro                  | [440ba53ef9](https://linux-hardware.org/?probe=440ba53ef9) | Jun 16, 2022 |
| Apple         | MacBookPro8,1               | [145a1e77fc](https://linux-hardware.org/?probe=145a1e77fc) | Jun 16, 2022 |
| Dell          | Inspiron 7520               | [d6e4d7642d](https://linux-hardware.org/?probe=d6e4d7642d) | Jun 16, 2022 |
| Lenovo        | Legion 7 15IMH05 81YT       | [cc1947a21b](https://linux-hardware.org/?probe=cc1947a21b) | Jun 15, 2022 |
| Acer          | Aspire E5-575G              | [aa390f3eaa](https://linux-hardware.org/?probe=aa390f3eaa) | Jun 15, 2022 |
| Sony          | SVF15A1M2ES                 | [bdcd4a90fc](https://linux-hardware.org/?probe=bdcd4a90fc) | Jun 15, 2022 |
| Dell          | Latitude E6540              | [03fb6fa23c](https://linux-hardware.org/?probe=03fb6fa23c) | Jun 15, 2022 |
| Dell          | Precision 5550              | [f5f815ceed](https://linux-hardware.org/?probe=f5f815ceed) | Jun 14, 2022 |
| Acer          | Swift SF314-54              | [06bccc3696](https://linux-hardware.org/?probe=06bccc3696) | Jun 14, 2022 |
| Dell          | Precision 7720              | [8b4da2326e](https://linux-hardware.org/?probe=8b4da2326e) | Jun 14, 2022 |
| Dell          | Precision 7720              | [bf25929cec](https://linux-hardware.org/?probe=bf25929cec) | Jun 14, 2022 |
| Dell          | Latitude E6540              | [44b876534d](https://linux-hardware.org/?probe=44b876534d) | Jun 14, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [f4ef35b902](https://linux-hardware.org/?probe=f4ef35b902) | Jun 14, 2022 |
| Dell          | Inspiron 7737               | [6fa74e19b1](https://linux-hardware.org/?probe=6fa74e19b1) | Jun 13, 2022 |
| Notebook      | P65_P67SE                   | [590b7204da](https://linux-hardware.org/?probe=590b7204da) | Jun 13, 2022 |
| HP            | EliteBook 820 G2            | [45ca271974](https://linux-hardware.org/?probe=45ca271974) | Jun 13, 2022 |
| Lenovo        | B40-80 80F6                 | [7449f0f8d2](https://linux-hardware.org/?probe=7449f0f8d2) | Jun 13, 2022 |
| ASUSTek       | K70IJ                       | [2eb24f0195](https://linux-hardware.org/?probe=2eb24f0195) | Jun 13, 2022 |
| ASUSTek       | K70IJ                       | [110ff08266](https://linux-hardware.org/?probe=110ff08266) | Jun 13, 2022 |
| Apple         | MacBookPro11,1              | [7222fb776a](https://linux-hardware.org/?probe=7222fb776a) | Jun 13, 2022 |
| Dell          | Latitude E6540              | [91e07b8f2d](https://linux-hardware.org/?probe=91e07b8f2d) | Jun 12, 2022 |
| ASUSTek       | UX430UQ                     | [9754c7394d](https://linux-hardware.org/?probe=9754c7394d) | Jun 12, 2022 |
| Dell          | System XPS L702X            | [b79115e065](https://linux-hardware.org/?probe=b79115e065) | Jun 12, 2022 |
| MSI           | Alpha 17 A4DEK              | [42171e02bb](https://linux-hardware.org/?probe=42171e02bb) | Jun 11, 2022 |
| HP            | EliteBook 820 G2            | [0a0828f262](https://linux-hardware.org/?probe=0a0828f262) | Jun 11, 2022 |
| ASUSTek       | GL552VW                     | [8ed24a5d98](https://linux-hardware.org/?probe=8ed24a5d98) | Jun 11, 2022 |
| Dell          | Inspiron 7520               | [4916232f15](https://linux-hardware.org/?probe=4916232f15) | Jun 11, 2022 |
| Acer          | Aspire 4349                 | [7c8c3427a9](https://linux-hardware.org/?probe=7c8c3427a9) | Jun 11, 2022 |
| HP            | ProBook 455 G3              | [bac60198a3](https://linux-hardware.org/?probe=bac60198a3) | Jun 10, 2022 |
| ASUSTek       | K50IJ                       | [c8bac63870](https://linux-hardware.org/?probe=c8bac63870) | Jun 10, 2022 |
| Dell          | Latitude E7270              | [8d8f0db52c](https://linux-hardware.org/?probe=8d8f0db52c) | Jun 10, 2022 |
| ASUSTek       | K50IJ                       | [addb86fcb0](https://linux-hardware.org/?probe=addb86fcb0) | Jun 10, 2022 |
| ASUSTek       | Unknown                     | [1cc4adfa36](https://linux-hardware.org/?probe=1cc4adfa36) | Jun 09, 2022 |
| HP            | Elite x2 1012 G1            | [ad03ec2516](https://linux-hardware.org/?probe=ad03ec2516) | Jun 09, 2022 |
| Dell          | Inspiron 7520               | [ebbea30b2b](https://linux-hardware.org/?probe=ebbea30b2b) | Jun 09, 2022 |
| Dell          | G7 7790                     | [58cfc35862](https://linux-hardware.org/?probe=58cfc35862) | Jun 09, 2022 |
| Dell          | G7 7790                     | [495cfbb6f3](https://linux-hardware.org/?probe=495cfbb6f3) | Jun 09, 2022 |
| ASUSTek       | S550CA                      | [c87c7a989a](https://linux-hardware.org/?probe=c87c7a989a) | Jun 09, 2022 |
| ASUSTek       | S550CA                      | [9ba4a449c6](https://linux-hardware.org/?probe=9ba4a449c6) | Jun 09, 2022 |
| System76      | Oryx Pro                    | [bf9c9467d3](https://linux-hardware.org/?probe=bf9c9467d3) | Jun 08, 2022 |
| System76      | Oryx Pro                    | [2f96b6b08d](https://linux-hardware.org/?probe=2f96b6b08d) | Jun 08, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [5c2fedfca8](https://linux-hardware.org/?probe=5c2fedfca8) | Jun 08, 2022 |
| Dell          | Vostro 5402                 | [ebf8dce138](https://linux-hardware.org/?probe=ebf8dce138) | Jun 07, 2022 |
| Dell          | Inspiron 5537               | [7bb51064db](https://linux-hardware.org/?probe=7bb51064db) | Jun 07, 2022 |
| Dell          | Precision M4800             | [2607169dfe](https://linux-hardware.org/?probe=2607169dfe) | Jun 06, 2022 |
| Lenovo        | ThinkPad Edge E531 6885C... | [d98f987b46](https://linux-hardware.org/?probe=d98f987b46) | Jun 06, 2022 |
| Framework     | Laptop                      | [ed8e682778](https://linux-hardware.org/?probe=ed8e682778) | Jun 06, 2022 |
| Samsung       | 760XDA                      | [46350b515c](https://linux-hardware.org/?probe=46350b515c) | Jun 06, 2022 |
| MSI           | GS75 Stealth 9SF            | [9d18e7094e](https://linux-hardware.org/?probe=9d18e7094e) | Jun 05, 2022 |
| ASUSTek       | X556URK                     | [d6da70c8bd](https://linux-hardware.org/?probe=d6da70c8bd) | Jun 05, 2022 |
| Lenovo        | ThinkPad T450 20BVA02TCD    | [1485986503](https://linux-hardware.org/?probe=1485986503) | Jun 05, 2022 |
| Lenovo        | ThinkPad T450 20BVA02TCD    | [2f60fd04bf](https://linux-hardware.org/?probe=2f60fd04bf) | Jun 05, 2022 |
| Acer          | Aspire A715-75G             | [d8a8c3c8b4](https://linux-hardware.org/?probe=d8a8c3c8b4) | Jun 05, 2022 |
| Lenovo        | ThinkPad Edge E531 6885C... | [1b09ad54c8](https://linux-hardware.org/?probe=1b09ad54c8) | Jun 05, 2022 |
| Dell          | Inspiron 3502               | [afa1c5cd74](https://linux-hardware.org/?probe=afa1c5cd74) | Jun 04, 2022 |
| Timi          | RedmiBook Pro 14S           | [f729442cad](https://linux-hardware.org/?probe=f729442cad) | Jun 04, 2022 |
| Dell          | Precision M4800             | [3bd843466c](https://linux-hardware.org/?probe=3bd843466c) | Jun 04, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [0b2aab3dc7](https://linux-hardware.org/?probe=0b2aab3dc7) | Jun 04, 2022 |
| Lenovo        | G470 20078                  | [44e0643923](https://linux-hardware.org/?probe=44e0643923) | Jun 03, 2022 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | [27301ce2e8](https://linux-hardware.org/?probe=27301ce2e8) | Jun 03, 2022 |
| Samsung       | 900X3C/900X3D/900X3E/900... | [54fb76191c](https://linux-hardware.org/?probe=54fb76191c) | Jun 03, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [605cbc489f](https://linux-hardware.org/?probe=605cbc489f) | Jun 03, 2022 |
| Acer          | Aspire A515-43              | [a8c04eea72](https://linux-hardware.org/?probe=a8c04eea72) | Jun 03, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [562348dd07](https://linux-hardware.org/?probe=562348dd07) | Jun 03, 2022 |
| Toshiba       | Satellite L850-1D5          | [c8a260ef80](https://linux-hardware.org/?probe=c8a260ef80) | Jun 03, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [f1f4aec562](https://linux-hardware.org/?probe=f1f4aec562) | Jun 02, 2022 |
| ASUSTek       | N53SV                       | [d793b451f6](https://linux-hardware.org/?probe=d793b451f6) | Jun 02, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [9299688b01](https://linux-hardware.org/?probe=9299688b01) | Jun 02, 2022 |
| Dell          | Latitude E7470              | [f9a9090c54](https://linux-hardware.org/?probe=f9a9090c54) | Jun 02, 2022 |
| Dell          | Latitude 7390               | [0c7c9778aa](https://linux-hardware.org/?probe=0c7c9778aa) | Jun 02, 2022 |
| Dell          | Latitude E6540              | [de2e1727bc](https://linux-hardware.org/?probe=de2e1727bc) | Jun 01, 2022 |
| Lenovo        | ThinkPad P17 Gen 1 20SQS... | [491a4105d8](https://linux-hardware.org/?probe=491a4105d8) | Jun 01, 2022 |
| Dell          | Latitude E7240              | [e3c9cca7e1](https://linux-hardware.org/?probe=e3c9cca7e1) | Jun 01, 2022 |
| Acer          | Aspire ES1-572              | [6f6e6c038a](https://linux-hardware.org/?probe=6f6e6c038a) | Jun 01, 2022 |
| Lenovo        | ThinkPad T410 2537HN3       | [e373330c8b](https://linux-hardware.org/?probe=e373330c8b) | Jun 01, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 D... | [57f540db26](https://linux-hardware.org/?probe=57f540db26) | Jun 01, 2022 |
| Dell          | Inspiron 13 5310            | [70eccb19d4](https://linux-hardware.org/?probe=70eccb19d4) | Jun 01, 2022 |
| Dell          | Inspiron 5537               | [506d3fb361](https://linux-hardware.org/?probe=506d3fb361) | Jun 01, 2022 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [d0dbd3d75e](https://linux-hardware.org/?probe=d0dbd3d75e) | Jun 01, 2022 |
| Dell          | G7 7700                     | [25e22bc243](https://linux-hardware.org/?probe=25e22bc243) | May 31, 2022 |
| Lenovo        | V14-IIL 82C4                | [871738fea2](https://linux-hardware.org/?probe=871738fea2) | May 31, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [ed28d49715](https://linux-hardware.org/?probe=ed28d49715) | May 30, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [ce6b717155](https://linux-hardware.org/?probe=ce6b717155) | May 30, 2022 |
| HP            | Laptop 14-dq2xxx            | [14f581788f](https://linux-hardware.org/?probe=14f581788f) | May 30, 2022 |
| Acer          | Aspire A515-45              | [72b7fc79d4](https://linux-hardware.org/?probe=72b7fc79d4) | May 29, 2022 |
| Dell          | Vostro V130                 | [abefbba5b8](https://linux-hardware.org/?probe=abefbba5b8) | May 29, 2022 |
| Apple         | MacBookPro9,1               | [6fe2c4a416](https://linux-hardware.org/?probe=6fe2c4a416) | May 29, 2022 |
| MSI           | GF63 Thin 10SCXR            | [0d556408f3](https://linux-hardware.org/?probe=0d556408f3) | May 29, 2022 |
| HP            | OMEN by Laptop 15z-en100    | [35e3478a5d](https://linux-hardware.org/?probe=35e3478a5d) | May 28, 2022 |
| Medion        | X6816                       | [6d7996894c](https://linux-hardware.org/?probe=6d7996894c) | May 28, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [7ae101b473](https://linux-hardware.org/?probe=7ae101b473) | May 28, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [469ed3f68b](https://linux-hardware.org/?probe=469ed3f68b) | May 28, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [96bc0699c3](https://linux-hardware.org/?probe=96bc0699c3) | May 28, 2022 |
| Dell          | Inspiron 5566               | [88c420d481](https://linux-hardware.org/?probe=88c420d481) | May 28, 2022 |
| Toshiba       | IS 1413G                    | [c7a5f5eef3](https://linux-hardware.org/?probe=c7a5f5eef3) | May 28, 2022 |
| Acer          | Nitro AN515-42              | [a2f2dc2eee](https://linux-hardware.org/?probe=a2f2dc2eee) | May 27, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [65bccd9c04](https://linux-hardware.org/?probe=65bccd9c04) | May 27, 2022 |
| Dell          | Vostro 5402                 | [323fc36eb6](https://linux-hardware.org/?probe=323fc36eb6) | May 27, 2022 |
| Toshiba       | QOSMIO X770                 | [8f7d0ba9f9](https://linux-hardware.org/?probe=8f7d0ba9f9) | May 27, 2022 |
| Dell          | Precision 5530              | [2ecf3390bf](https://linux-hardware.org/?probe=2ecf3390bf) | May 27, 2022 |
| Acer          | Aspire A315-57G             | [d0400f8d02](https://linux-hardware.org/?probe=d0400f8d02) | May 26, 2022 |
| Fujitsu       | CELSIUS H730                | [6f0b24d450](https://linux-hardware.org/?probe=6f0b24d450) | May 26, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [ab2cd65153](https://linux-hardware.org/?probe=ab2cd65153) | May 26, 2022 |
| Dell          | Inspiron 3721               | [d4af21adb8](https://linux-hardware.org/?probe=d4af21adb8) | May 25, 2022 |
| A-DATA Tec... | XENIA 15                    | [1d7941d921](https://linux-hardware.org/?probe=1d7941d921) | May 25, 2022 |
| Lenovo        | ThinkPad X220 4286CTO       | [4c0d37687e](https://linux-hardware.org/?probe=4c0d37687e) | May 25, 2022 |
| Toshiba       | Satellite P850              | [9ec49310ff](https://linux-hardware.org/?probe=9ec49310ff) | May 25, 2022 |
| Apple         | MacBookPro14,3              | [ca090207b8](https://linux-hardware.org/?probe=ca090207b8) | May 25, 2022 |
| Monster       | TULPAR T5 V14.1             | [647e502881](https://linux-hardware.org/?probe=647e502881) | May 25, 2022 |
| Monster       | TULPAR T5 V14.1             | [0db0bd7aa8](https://linux-hardware.org/?probe=0db0bd7aa8) | May 25, 2022 |
| ASUSTek       | G551JM                      | [3db2e28ef2](https://linux-hardware.org/?probe=3db2e28ef2) | May 24, 2022 |
| Toshiba       | IS 1413G                    | [a34eaa3e4a](https://linux-hardware.org/?probe=a34eaa3e4a) | May 24, 2022 |
| Dell          | Precision 5550              | [6b17026494](https://linux-hardware.org/?probe=6b17026494) | May 24, 2022 |
| Toshiba       | IS 1413G                    | [e6e080d6e0](https://linux-hardware.org/?probe=e6e080d6e0) | May 24, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [a59234d081](https://linux-hardware.org/?probe=a59234d081) | May 24, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [bf692d5408](https://linux-hardware.org/?probe=bf692d5408) | May 23, 2022 |
| Acer          | Swift SF314-54              | [39f85b46d7](https://linux-hardware.org/?probe=39f85b46d7) | May 23, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [f2e32c336d](https://linux-hardware.org/?probe=f2e32c336d) | May 23, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [7fa4ca7312](https://linux-hardware.org/?probe=7fa4ca7312) | May 23, 2022 |
| Acer          | TravelMate 7750G            | [3ff0c1c7f2](https://linux-hardware.org/?probe=3ff0c1c7f2) | May 23, 2022 |
| Acer          | TravelMate 7750G            | [80bfe5a0c6](https://linux-hardware.org/?probe=80bfe5a0c6) | May 23, 2022 |
| Apple         | MacBookPro11,1              | [1d4f3a60c0](https://linux-hardware.org/?probe=1d4f3a60c0) | May 23, 2022 |
| ASUSTek       | X505BA                      | [685c1f7378](https://linux-hardware.org/?probe=685c1f7378) | May 22, 2022 |
| Lenovo        | ThinkPad T480 20L5S00F00    | [7a1f70c8aa](https://linux-hardware.org/?probe=7a1f70c8aa) | May 22, 2022 |
| Dell          | G3 3500                     | [49f86cc226](https://linux-hardware.org/?probe=49f86cc226) | May 22, 2022 |
| Google        | Lulu                        | [e7a0842114](https://linux-hardware.org/?probe=e7a0842114) | May 21, 2022 |
| MSI           | Modern 14 A10M              | [97a0996658](https://linux-hardware.org/?probe=97a0996658) | May 21, 2022 |
| HP            | Pavilion Notebook           | [1cd571d585](https://linux-hardware.org/?probe=1cd571d585) | May 21, 2022 |
| ASUSTek       | X510UR                      | [40b1695a67](https://linux-hardware.org/?probe=40b1695a67) | May 21, 2022 |
| ASUSTek       | X510UR                      | [e7cea85f09](https://linux-hardware.org/?probe=e7cea85f09) | May 21, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [bc911a9c04](https://linux-hardware.org/?probe=bc911a9c04) | May 21, 2022 |
| PC Special... | NP5x_NP6x_NP7xPNK_PNH_PN... | [e002072665](https://linux-hardware.org/?probe=e002072665) | May 21, 2022 |
| HP            | EliteBook 8570w             | [3f21c66d5c](https://linux-hardware.org/?probe=3f21c66d5c) | May 20, 2022 |
| Lenovo        | G40-30 80FY                 | [4280810a31](https://linux-hardware.org/?probe=4280810a31) | May 20, 2022 |
| System76      | Oryx Pro                    | [d705be052a](https://linux-hardware.org/?probe=d705be052a) | May 20, 2022 |
| Dell          | Inspiron 5555               | [35c2610913](https://linux-hardware.org/?probe=35c2610913) | May 20, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [2320338e52](https://linux-hardware.org/?probe=2320338e52) | May 19, 2022 |
| Dell          | XPS 15 9570                 | [ba19473e18](https://linux-hardware.org/?probe=ba19473e18) | May 19, 2022 |
| Gigabyte      | AERO 15 KC                  | [5ebc19bd4c](https://linux-hardware.org/?probe=5ebc19bd4c) | May 18, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [c9a82e1be0](https://linux-hardware.org/?probe=c9a82e1be0) | May 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [8ef2235464](https://linux-hardware.org/?probe=8ef2235464) | May 17, 2022 |
| System76      | Oryx Pro                    | [b68edfe15c](https://linux-hardware.org/?probe=b68edfe15c) | May 17, 2022 |
| Samsung       | 550XCJ/550XCR               | [5bc959890b](https://linux-hardware.org/?probe=5bc959890b) | May 17, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [e4bf8d23b8](https://linux-hardware.org/?probe=e4bf8d23b8) | May 17, 2022 |
| HUAWEI        | HN-WX9X                     | [f5ade437dc](https://linux-hardware.org/?probe=f5ade437dc) | May 17, 2022 |
| HP            | Laptop 14-dk1xxx            | [77a8cae8a0](https://linux-hardware.org/?probe=77a8cae8a0) | May 17, 2022 |
| ASUSTek       | G73Jh                       | [2d96e5ecba](https://linux-hardware.org/?probe=2d96e5ecba) | May 17, 2022 |
| Toshiba       | Satellite L50D-C            | [f06e254906](https://linux-hardware.org/?probe=f06e254906) | May 17, 2022 |
| Alienware     | 18                          | [7aa82b2786](https://linux-hardware.org/?probe=7aa82b2786) | May 17, 2022 |
| Acer          | Aspire 7560G                | [d3d9aa988f](https://linux-hardware.org/?probe=d3d9aa988f) | May 16, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [eb5345a5c6](https://linux-hardware.org/?probe=eb5345a5c6) | May 16, 2022 |
| Google        | Lulu                        | [c402204a03](https://linux-hardware.org/?probe=c402204a03) | May 16, 2022 |
| Fujitsu       | LIFEBOOK T5010              | [e0aab70a85](https://linux-hardware.org/?probe=e0aab70a85) | May 16, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [3a369eed6d](https://linux-hardware.org/?probe=3a369eed6d) | May 16, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [a8fffad424](https://linux-hardware.org/?probe=a8fffad424) | May 16, 2022 |
| Apple         | MacBookPro16,2              | [ceb6a7e5a3](https://linux-hardware.org/?probe=ceb6a7e5a3) | May 16, 2022 |
| Apple         | MacBookPro16,2              | [5c4ebc223f](https://linux-hardware.org/?probe=5c4ebc223f) | May 16, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | [3ecda9477c](https://linux-hardware.org/?probe=3ecda9477c) | May 16, 2022 |
| Apple         | MacBookPro14,1              | [2d4d81086f](https://linux-hardware.org/?probe=2d4d81086f) | May 15, 2022 |
| Acer          | TravelMate P249-G2-MG       | [e6f35b116a](https://linux-hardware.org/?probe=e6f35b116a) | May 15, 2022 |
| Dell          | Vostro 5471                 | [62e934492d](https://linux-hardware.org/?probe=62e934492d) | May 15, 2022 |
| Dell          | XPS 15 9510                 | [653725bdde](https://linux-hardware.org/?probe=653725bdde) | May 15, 2022 |
| Dell          | XPS 15 9560                 | [04f0e074cb](https://linux-hardware.org/?probe=04f0e074cb) | May 14, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [7a2fd723d6](https://linux-hardware.org/?probe=7a2fd723d6) | May 14, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [98db0dde2a](https://linux-hardware.org/?probe=98db0dde2a) | May 13, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [66e43801f0](https://linux-hardware.org/?probe=66e43801f0) | May 13, 2022 |
| Google        | Lulu                        | [8d7f1657d0](https://linux-hardware.org/?probe=8d7f1657d0) | May 13, 2022 |
| Acer          | Swift SF314-54              | [a31c36956a](https://linux-hardware.org/?probe=a31c36956a) | May 13, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [30bb58501e](https://linux-hardware.org/?probe=30bb58501e) | May 13, 2022 |
| Apple         | MacBookPro5,2               | [0a3017f333](https://linux-hardware.org/?probe=0a3017f333) | May 13, 2022 |
| Acer          | Nitro AN515-44              | [fe8e3837f4](https://linux-hardware.org/?probe=fe8e3837f4) | May 12, 2022 |
| System76      | Pangolin                    | [0f05fa93a8](https://linux-hardware.org/?probe=0f05fa93a8) | May 12, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [ea75711bf8](https://linux-hardware.org/?probe=ea75711bf8) | May 12, 2022 |
| Apple         | MacBookAir7,2               | [114ef2756f](https://linux-hardware.org/?probe=114ef2756f) | May 12, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [915b95cae4](https://linux-hardware.org/?probe=915b95cae4) | May 11, 2022 |
| Google        | Cyan                        | [cec3bd0a88](https://linux-hardware.org/?probe=cec3bd0a88) | May 11, 2022 |
| HP            | ZBook Studio G7 Mobile W... | [4f25a82453](https://linux-hardware.org/?probe=4f25a82453) | May 11, 2022 |
| Apple         | MacBook5,2                  | [0913ac4c8e](https://linux-hardware.org/?probe=0913ac4c8e) | May 11, 2022 |
| System76      | Pangolin                    | [da80a33b86](https://linux-hardware.org/?probe=da80a33b86) | May 11, 2022 |
| Dell          | G15 5511                    | [17b75bcced](https://linux-hardware.org/?probe=17b75bcced) | May 10, 2022 |
| Dell          | XPS 13 9305                 | [0066686d1d](https://linux-hardware.org/?probe=0066686d1d) | May 10, 2022 |
| Dell          | XPS 13 9310                 | [cae0934838](https://linux-hardware.org/?probe=cae0934838) | May 10, 2022 |
| HP            | EliteBook 2730p             | [d4c5b7824d](https://linux-hardware.org/?probe=d4c5b7824d) | May 10, 2022 |
| HP            | 15 Notebook PC              | [d88f833b65](https://linux-hardware.org/?probe=d88f833b65) | May 10, 2022 |
| HP            | EliteBook 8570w             | [840087bbed](https://linux-hardware.org/?probe=840087bbed) | May 09, 2022 |
| HP            | EliteBook 8570w             | [d9779b1c50](https://linux-hardware.org/?probe=d9779b1c50) | May 09, 2022 |
| HP            | Laptop 15-dy1xxx            | [fd022c446e](https://linux-hardware.org/?probe=fd022c446e) | May 09, 2022 |
| TUXEDO        | Unknown                     | [20f46751c2](https://linux-hardware.org/?probe=20f46751c2) | May 08, 2022 |
| TUXEDO        | Unknown                     | [c1df33620d](https://linux-hardware.org/?probe=c1df33620d) | May 08, 2022 |
| MSI           | Modern 15 A10RAS            | [3e844bb07a](https://linux-hardware.org/?probe=3e844bb07a) | May 08, 2022 |
| Lenovo        | ThinkPad T480 20L6S8H100    | [5eefaba8d3](https://linux-hardware.org/?probe=5eefaba8d3) | May 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [dcdc07525d](https://linux-hardware.org/?probe=dcdc07525d) | May 08, 2022 |
| Apple         | MacBookAir6,2               | [1e1f4caa54](https://linux-hardware.org/?probe=1e1f4caa54) | May 08, 2022 |
| Samsung       | 800G5M/800G5W               | [057ea02fdb](https://linux-hardware.org/?probe=057ea02fdb) | May 08, 2022 |
| Lenovo        | ThinkPad T480 20L6S8H100    | [892d07e5cf](https://linux-hardware.org/?probe=892d07e5cf) | May 08, 2022 |
| Lenovo        | Legion 5 17ITH6H 82JM       | [451c9ea765](https://linux-hardware.org/?probe=451c9ea765) | May 08, 2022 |
| ASUSTek       | E200HA                      | [ba413ad853](https://linux-hardware.org/?probe=ba413ad853) | May 08, 2022 |
| MSI           | GS63 7RD                    | [eff12e3973](https://linux-hardware.org/?probe=eff12e3973) | May 08, 2022 |
| HP            | Pavilion 15                 | [a18593bb5b](https://linux-hardware.org/?probe=a18593bb5b) | May 07, 2022 |
| Google        | Lulu                        | [18ecc4a6e7](https://linux-hardware.org/?probe=18ecc4a6e7) | May 07, 2022 |
| Acer          | Aspire E1-570               | [53ddeaa413](https://linux-hardware.org/?probe=53ddeaa413) | May 07, 2022 |
| ASUSTek       | E200HA                      | [6fc7c6f086](https://linux-hardware.org/?probe=6fc7c6f086) | May 07, 2022 |
| Google        | Peppy                       | [03dc670128](https://linux-hardware.org/?probe=03dc670128) | May 06, 2022 |
| HP            | ProBook 450 G4              | [1332984f5d](https://linux-hardware.org/?probe=1332984f5d) | May 06, 2022 |
| Lenovo        | ThinkPad Twist 33472YU      | [710c086b29](https://linux-hardware.org/?probe=710c086b29) | May 06, 2022 |
| Lenovo        | ThinkPad Twist 33472YU      | [76fb8bb966](https://linux-hardware.org/?probe=76fb8bb966) | May 06, 2022 |
| Dell          | XPS 13 9300                 | [080b4f2667](https://linux-hardware.org/?probe=080b4f2667) | May 06, 2022 |
| Lenovo        | G50-80 80E5                 | [8ecadc1bad](https://linux-hardware.org/?probe=8ecadc1bad) | May 05, 2022 |
| HP            | Pavilion Notebook           | [af36cfb1a8](https://linux-hardware.org/?probe=af36cfb1a8) | May 05, 2022 |
| Acer          | Aspire V5-431               | [04db0db85f](https://linux-hardware.org/?probe=04db0db85f) | May 05, 2022 |
| Razer         | Blade 14 - RZ09-0370        | [fa323515aa](https://linux-hardware.org/?probe=fa323515aa) | May 05, 2022 |
| Dell          | Inspiron 1750               | [1c70ba9e33](https://linux-hardware.org/?probe=1c70ba9e33) | May 05, 2022 |
| Dell          | Latitude E5440              | [a505dc0b3c](https://linux-hardware.org/?probe=a505dc0b3c) | May 05, 2022 |
| ASUSTek       | GL552VX                     | [d153ef27fa](https://linux-hardware.org/?probe=d153ef27fa) | May 04, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [a9f5b77476](https://linux-hardware.org/?probe=a9f5b77476) | May 04, 2022 |
| Acer          | Aspire A515-45              | [e5f3e5b086](https://linux-hardware.org/?probe=e5f3e5b086) | May 04, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [8bfd6ecc71](https://linux-hardware.org/?probe=8bfd6ecc71) | May 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [720d11c11f](https://linux-hardware.org/?probe=720d11c11f) | May 04, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [5a8fc607c4](https://linux-hardware.org/?probe=5a8fc607c4) | May 04, 2022 |
| Dell          | Inspiron 3583               | [f5e954ea5e](https://linux-hardware.org/?probe=f5e954ea5e) | May 04, 2022 |
| HP            | Pavilion 13 x360 PC         | [5de9e1d61f](https://linux-hardware.org/?probe=5de9e1d61f) | May 04, 2022 |
| ASUSTek       | X540SAA                     | [9943699a6b](https://linux-hardware.org/?probe=9943699a6b) | May 04, 2022 |
| Acer          | Aspire F5-573G              | [2136362d58](https://linux-hardware.org/?probe=2136362d58) | May 03, 2022 |
| HP            | Laptop 17-ca3xxx            | [373f22a70f](https://linux-hardware.org/?probe=373f22a70f) | May 03, 2022 |
| HP            | Laptop 17-ca3xxx            | [91a367d874](https://linux-hardware.org/?probe=91a367d874) | May 03, 2022 |
| Apple         | MacBookAir6,2               | [0f8065fda6](https://linux-hardware.org/?probe=0f8065fda6) | May 03, 2022 |
| ASUSTek       | GL552JX                     | [c91f42212d](https://linux-hardware.org/?probe=c91f42212d) | May 03, 2022 |
| ASUSTek       | ROG Strix G713RC_G713RC     | [2ce25fb058](https://linux-hardware.org/?probe=2ce25fb058) | May 03, 2022 |
| Dell          | Inspiron 3583               | [c47758f125](https://linux-hardware.org/?probe=c47758f125) | May 03, 2022 |
| Lenovo        | IdeaPad Slim 7 14ITL05 8... | [4b44c67cde](https://linux-hardware.org/?probe=4b44c67cde) | May 02, 2022 |
| Toshiba       | PORTEGE R830                | [8daebf6110](https://linux-hardware.org/?probe=8daebf6110) | May 02, 2022 |
| Dell          | Latitude E6440              | [d2ab063048](https://linux-hardware.org/?probe=d2ab063048) | May 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [58ff4a1984](https://linux-hardware.org/?probe=58ff4a1984) | May 02, 2022 |
| Toshiba       | Satellite L755              | [6c38249bc4](https://linux-hardware.org/?probe=6c38249bc4) | May 02, 2022 |
| Framework     | Laptop                      | [0d35134041](https://linux-hardware.org/?probe=0d35134041) | May 02, 2022 |
| Acer          | Aspire A515-45              | [8cf5364699](https://linux-hardware.org/?probe=8cf5364699) | May 02, 2022 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [02872ac9a8](https://linux-hardware.org/?probe=02872ac9a8) | May 02, 2022 |
| MSI           | GS65 Stealth 8SG            | [05f80b3e70](https://linux-hardware.org/?probe=05f80b3e70) | May 02, 2022 |
| System76      | Oryx Pro                    | [96251b761b](https://linux-hardware.org/?probe=96251b761b) | May 02, 2022 |
| Acer          | Aspire V5-573P              | [b64d1453d5](https://linux-hardware.org/?probe=b64d1453d5) | May 02, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [332445f774](https://linux-hardware.org/?probe=332445f774) | May 02, 2022 |
| MSI           | GP76 Leopard 11UG           | [dcea7cd8c0](https://linux-hardware.org/?probe=dcea7cd8c0) | May 02, 2022 |
| Dell          | Latitude E5570              | [372feb146c](https://linux-hardware.org/?probe=372feb146c) | May 02, 2022 |
| Apple         | MacBookPro12,1              | [5f68858e66](https://linux-hardware.org/?probe=5f68858e66) | May 01, 2022 |
| Acer          | Aspire 7750G                | [abd7ed0c5c](https://linux-hardware.org/?probe=abd7ed0c5c) | May 01, 2022 |
| LG Electro... | P430-G.BC41P1               | [527905ca3b](https://linux-hardware.org/?probe=527905ca3b) | May 01, 2022 |
| Apple         | MacBookPro4,1               | [be68c0201a](https://linux-hardware.org/?probe=be68c0201a) | May 01, 2022 |
| Apple         | MacBookPro7,1               | [ac3f2c5c61](https://linux-hardware.org/?probe=ac3f2c5c61) | May 01, 2022 |
| Apple         | MacBookPro4,1               | [83a8bbb313](https://linux-hardware.org/?probe=83a8bbb313) | May 01, 2022 |
| Lenovo        | Legion 7 16ITHg6 82K6       | [48afcac3f0](https://linux-hardware.org/?probe=48afcac3f0) | May 01, 2022 |
| HP            | EliteBook 8440p             | [89a959efc4](https://linux-hardware.org/?probe=89a959efc4) | May 01, 2022 |
| HP            | ProBook 455 G7              | [88fcea9210](https://linux-hardware.org/?probe=88fcea9210) | Apr 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [48d3759522](https://linux-hardware.org/?probe=48d3759522) | Apr 30, 2022 |
| Toshiba       | Satellite L10W-B-101        | [8383d306f3](https://linux-hardware.org/?probe=8383d306f3) | Apr 30, 2022 |
| Dell          | XPS 13 9343                 | [b48ccc106e](https://linux-hardware.org/?probe=b48ccc106e) | Apr 30, 2022 |
| Toshiba       | IS 1413G                    | [8074a86bc7](https://linux-hardware.org/?probe=8074a86bc7) | Apr 30, 2022 |
| Dell          | XPS 15 9510                 | [b92517268e](https://linux-hardware.org/?probe=b92517268e) | Apr 30, 2022 |
| ASUSTek       | G55VW                       | [6bd8a1b04a](https://linux-hardware.org/?probe=6bd8a1b04a) | Apr 29, 2022 |
| Dell          | Inspiron 3542               | [19f5e16bce](https://linux-hardware.org/?probe=19f5e16bce) | Apr 29, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [61bb949815](https://linux-hardware.org/?probe=61bb949815) | Apr 29, 2022 |
| Dell          | G5 5500                     | [c6064853ad](https://linux-hardware.org/?probe=c6064853ad) | Apr 29, 2022 |
| Lenovo        | ThinkPad T480 20L50004UK    | [34015c4874](https://linux-hardware.org/?probe=34015c4874) | Apr 29, 2022 |
| ASUSTek       | X540SAA                     | [6c8e397ca3](https://linux-hardware.org/?probe=6c8e397ca3) | Apr 29, 2022 |
| System76      | Oryx Pro                    | [cf999d4581](https://linux-hardware.org/?probe=cf999d4581) | Apr 29, 2022 |
| Dell          | Inspiron 5547               | [a5d8e73a23](https://linux-hardware.org/?probe=a5d8e73a23) | Apr 28, 2022 |
| Dell          | Inspiron 5547               | [be4ab0fd27](https://linux-hardware.org/?probe=be4ab0fd27) | Apr 28, 2022 |
| Toshiba       | IS 1413G                    | [995f77010e](https://linux-hardware.org/?probe=995f77010e) | Apr 28, 2022 |
| Toshiba       | IS 1413G                    | [e2293170b3](https://linux-hardware.org/?probe=e2293170b3) | Apr 28, 2022 |
| Lenovo        | ThinkPad T431s 20ACS03P0... | [3c0878aee3](https://linux-hardware.org/?probe=3c0878aee3) | Apr 28, 2022 |
| System76      | Oryx Pro                    | [ae46ece731](https://linux-hardware.org/?probe=ae46ece731) | Apr 28, 2022 |
| HP            | Pavilion 15                 | [fee7e96d70](https://linux-hardware.org/?probe=fee7e96d70) | Apr 28, 2022 |
| Toshiba       | IS 1413G                    | [a63dc69025](https://linux-hardware.org/?probe=a63dc69025) | Apr 28, 2022 |
| Apple         | MacBookPro10,2              | [2d79aab0aa](https://linux-hardware.org/?probe=2d79aab0aa) | Apr 28, 2022 |
| ASUSTek       | K40IN                       | [ab6a95da52](https://linux-hardware.org/?probe=ab6a95da52) | Apr 28, 2022 |
| HP            | Pavilion 13 x360 PC         | [d48ed77abc](https://linux-hardware.org/?probe=d48ed77abc) | Apr 28, 2022 |
| Dell          | Inspiron 5566               | [695d362d8f](https://linux-hardware.org/?probe=695d362d8f) | Apr 27, 2022 |
| ASUSTek       | FX503VM                     | [c227966510](https://linux-hardware.org/?probe=c227966510) | Apr 27, 2022 |
| ASUSTek       | FX503VM                     | [1275aa643d](https://linux-hardware.org/?probe=1275aa643d) | Apr 27, 2022 |
| HP            | ENVY Laptop 14-eb0xxx       | [495a74c914](https://linux-hardware.org/?probe=495a74c914) | Apr 27, 2022 |
| Dell          | XPS 13 9310                 | [d394f4e0d9](https://linux-hardware.org/?probe=d394f4e0d9) | Apr 27, 2022 |
| HUAWEI        | HVY-WXX9                    | [824ccc1317](https://linux-hardware.org/?probe=824ccc1317) | Apr 27, 2022 |
| HP            | Pavilion 13 x360 PC         | [3e5933fe0d](https://linux-hardware.org/?probe=3e5933fe0d) | Apr 27, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [e51ff27a5a](https://linux-hardware.org/?probe=e51ff27a5a) | Apr 27, 2022 |
| Dell          | Vostro 15 3515              | [7c99d7d4c5](https://linux-hardware.org/?probe=7c99d7d4c5) | Apr 27, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [863612cc05](https://linux-hardware.org/?probe=863612cc05) | Apr 27, 2022 |
| Purism        | Librem 15 v3                | [d2a13c9d0a](https://linux-hardware.org/?probe=d2a13c9d0a) | Apr 27, 2022 |
| Toshiba       | Satellite C55t-C            | [1fe2032839](https://linux-hardware.org/?probe=1fe2032839) | Apr 27, 2022 |
| Toshiba       | Satellite C55t-C            | [cabf0c7464](https://linux-hardware.org/?probe=cabf0c7464) | Apr 27, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [b7ac79ff8f](https://linux-hardware.org/?probe=b7ac79ff8f) | Apr 27, 2022 |
| MSI           | GS66 Stealth 10UG           | [77b699045a](https://linux-hardware.org/?probe=77b699045a) | Apr 27, 2022 |
| Acer          | Aspire E1-570               | [1621e22812](https://linux-hardware.org/?probe=1621e22812) | Apr 26, 2022 |
| Acer          | Swift SF316-51              | [fe42983639](https://linux-hardware.org/?probe=fe42983639) | Apr 26, 2022 |
| Acer          | TravelMate P249-G2-MG       | [2e0bd790c6](https://linux-hardware.org/?probe=2e0bd790c6) | Apr 26, 2022 |
| Dell          | Inspiron 3442               | [d4b7580074](https://linux-hardware.org/?probe=d4b7580074) | Apr 26, 2022 |
| Dell          | Inspiron 3442               | [d994ff2a13](https://linux-hardware.org/?probe=d994ff2a13) | Apr 26, 2022 |
| Unknown       | Unknown                     | [885f468161](https://linux-hardware.org/?probe=885f468161) | Apr 26, 2022 |
| ASUSTek       | X555LF                      | [0aa3a88c0c](https://linux-hardware.org/?probe=0aa3a88c0c) | Apr 25, 2022 |
| Dell          | XPS 13 9360                 | [ffb9cf10be](https://linux-hardware.org/?probe=ffb9cf10be) | Apr 20, 2022 |
| Dell          | XPS 13 9360                 | [f174d4ced7](https://linux-hardware.org/?probe=f174d4ced7) | Apr 20, 2022 |
| Toshiba       | IS 1413G                    | [1b3267b605](https://linux-hardware.org/?probe=1b3267b605) | Apr 18, 2022 |
| Dell          | Latitude 5590               | [ade3f33fb9](https://linux-hardware.org/?probe=ade3f33fb9) | Apr 16, 2022 |
| Dell          | Latitude 5590               | [1638db9ad7](https://linux-hardware.org/?probe=1638db9ad7) | Apr 13, 2022 |
| Dell          | Latitude E7270              | [79cc908dcc](https://linux-hardware.org/?probe=79cc908dcc) | Apr 08, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                              | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| 5.17.5-76051705-generic              | 221       | 38.84%  |
| 5.18.10-76051810-generic             | 106       | 18.63%  |
| 5.17.15-76051715-generic             | 102       | 17.93%  |
| 5.16.19-76051619-generic             | 70        | 12.3%   |
| 5.19.0-76051900-generic              | 52        | 9.14%   |
| 5.17.5-051705-generic                | 2         | 0.35%   |
| 5.16.15-76051615-generic             | 2         | 0.35%   |
| 6.0.0-060000rc1daily20220820-generic | 1         | 0.18%   |
| 5.19.3-051903-generic                | 1         | 0.18%   |
| 5.19.0-rc1+                          | 1         | 0.18%   |
| 5.18.6-xanmod1                       | 1         | 0.18%   |
| 5.18.4-xanmod1                       | 1         | 0.18%   |
| 5.18.16-xanmod1                      | 1         | 0.18%   |
| 5.18.0-051800rc1-generic             | 1         | 0.18%   |
| 5.17.7-051707-generic                | 1         | 0.18%   |
| 5.17.6-051706-generic                | 1         | 0.18%   |
| 5.17.5-tkg-bmq                       | 1         | 0.18%   |
| 5.17.2-xanmod1                       | 1         | 0.18%   |
| 5.17.0-051700-generic                | 1         | 0.18%   |
| 5.16.11-76051611-generic             | 1         | 0.18%   |
| 5.15.0-46-generic                    | 1         | 0.18%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.17.5  | 224       | 39.37%  |
| 5.18.10 | 106       | 18.63%  |
| 5.17.15 | 102       | 17.93%  |
| 5.16.19 | 70        | 12.3%   |
| 5.19.0  | 53        | 9.31%   |
| 5.16.15 | 2         | 0.35%   |
| 6.0.0   | 1         | 0.18%   |
| 5.19.3  | 1         | 0.18%   |
| 5.18.6  | 1         | 0.18%   |
| 5.18.4  | 1         | 0.18%   |
| 5.18.16 | 1         | 0.18%   |
| 5.18.0  | 1         | 0.18%   |
| 5.17.7  | 1         | 0.18%   |
| 5.17.6  | 1         | 0.18%   |
| 5.17.2  | 1         | 0.18%   |
| 5.17.0  | 1         | 0.18%   |
| 5.16.11 | 1         | 0.18%   |
| 5.15.0  | 1         | 0.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.17    | 324       | 57.55%  |
| 5.18    | 110       | 19.54%  |
| 5.16    | 73        | 12.97%  |
| 5.19    | 54        | 9.59%   |
| 6.0     | 1         | 0.18%   |
| 5.15    | 1         | 0.18%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 549       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 533       | 96.73%  |
| KDE5            | 7         | 1.27%   |
| Unknown         | 5         | 0.91%   |
| X-Cinnamon      | 2         | 0.36%   |
| GNOME Flashback | 2         | 0.36%   |
| XFCE            | 1         | 0.18%   |
| LXQt            | 1         | 0.18%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 523       | 94.92%  |
| Wayland | 23        | 4.17%   |
| Unknown | 4         | 0.73%   |
| Tty     | 1         | 0.18%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 425       | 77.13%  |
| GDM3    | 124       | 22.5%   |
| GDM     | 2         | 0.36%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 337       | 61.16%  |
| pt_BR   | 34        | 6.17%   |
| en_GB   | 34        | 6.17%   |
| de_DE   | 22        | 3.99%   |
| en_AU   | 18        | 3.27%   |
| fr_FR   | 12        | 2.18%   |
| it_IT   | 9         | 1.63%   |
| C       | 9         | 1.63%   |
| es_ES   | 7         | 1.27%   |
| en_CA   | 7         | 1.27%   |
| ru_RU   | 6         | 1.09%   |
| pl_PL   | 6         | 1.09%   |
| sv_SE   | 5         | 0.91%   |
| pt_PT   | 3         | 0.54%   |
| nb_NO   | 3         | 0.54%   |
| es_MX   | 3         | 0.54%   |
| es_CO   | 3         | 0.54%   |
| en_NZ   | 3         | 0.54%   |
| en_IN   | 3         | 0.54%   |
| de_CH   | 3         | 0.54%   |
| Unknown | 3         | 0.54%   |
| fr_CA   | 2         | 0.36%   |
| es_AR   | 2         | 0.36%   |
| en_ZA   | 2         | 0.36%   |
| en_IE   | 2         | 0.36%   |
| sr_RS   | 1         | 0.18%   |
| ro_RO   | 1         | 0.18%   |
| hr_HR   | 1         | 0.18%   |
| fr_CH   | 1         | 0.18%   |
| fr_BE   | 1         | 0.18%   |
| fi_FI   | 1         | 0.18%   |
| es_UY   | 1         | 0.18%   |
| es_GT   | 1         | 0.18%   |
| es_CL   | 1         | 0.18%   |
| en_SG   | 1         | 0.18%   |
| en_PH   | 1         | 0.18%   |
| en_DK   | 1         | 0.18%   |
| de_AT   | 1         | 0.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 430       | 78.04%  |
| EFI  | 121       | 21.96%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 525       | 95.63%  |
| Btrfs   | 18        | 3.28%   |
| Overlay | 5         | 0.91%   |
| Xfs     | 1         | 0.18%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 421       | 76.27%  |
| GPT     | 122       | 22.1%   |
| MBR     | 9         | 1.63%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 535       | 97.45%  |
| Yes       | 14        | 2.55%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 507       | 92.18%  |
| Yes       | 43        | 7.82%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 105       | 19.13%  |
| Dell                   | 98        | 17.85%  |
| ASUSTek Computer       | 73        | 13.3%   |
| Hewlett-Packard        | 62        | 11.29%  |
| Acer                   | 45        | 8.2%    |
| Apple                  | 40        | 7.29%   |
| MSI                    | 24        | 4.37%   |
| System76               | 17        | 3.1%    |
| Toshiba                | 15        | 2.73%   |
| Samsung Electronics    | 11        | 2%      |
| HUAWEI                 | 8         | 1.46%   |
| GPU Company            | 5         | 0.91%   |
| Notebook               | 4         | 0.73%   |
| Google                 | 4         | 0.73%   |
| Sony                   | 3         | 0.55%   |
| Alienware              | 3         | 0.55%   |
| Timi                   | 2         | 0.36%   |
| PC Specialist          | 2         | 0.36%   |
| Panasonic              | 2         | 0.36%   |
| Medion                 | 2         | 0.36%   |
| Gigabyte Technology    | 2         | 0.36%   |
| Fujitsu                | 2         | 0.36%   |
| Framework              | 2         | 0.36%   |
| TUXEDO                 | 1         | 0.18%   |
| Semp Toshiba           | 1         | 0.18%   |
| Schenker               | 1         | 0.18%   |
| Razer                  | 1         | 0.18%   |
| Quanta                 | 1         | 0.18%   |
| Purism                 | 1         | 0.18%   |
| Positivo               | 1         | 0.18%   |
| Pegatron               | 1         | 0.18%   |
| Monster                | 1         | 0.18%   |
| LG Electronics         | 1         | 0.18%   |
| Intel Client Systems   | 1         | 0.18%   |
| HONOR                  | 1         | 0.18%   |
| Gateway                | 1         | 0.18%   |
| Eluktronics            | 1         | 0.18%   |
| Dynabook               | 1         | 0.18%   |
| Avell High Performance | 1         | 0.18%   |
| A-DATA Technology      | 1         | 0.18%   |
| Unknown                | 1         | 0.18%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| System76 Oryx Pro                     | 8         | 1.46%   |
| Apple MacBookAir7,2                   | 5         | 0.91%   |
| Lenovo IdeaPad S145-15API 81V7        | 4         | 0.73%   |
| Unknown                               | 4         | 0.73%   |
| System76 Lemur Pro                    | 3         | 0.55%   |
| MSI Prestige 15 A10SC                 | 3         | 0.55%   |
| HP Pavilion Notebook                  | 3         | 0.55%   |
| HP OMEN Laptop 15-en0xxx              | 3         | 0.55%   |
| GPU Company GWTC116-2                 | 3         | 0.55%   |
| Dell XPS 15 9520                      | 3         | 0.55%   |
| Dell XPS 13 9305                      | 3         | 0.55%   |
| Dell Latitude E7240                   | 3         | 0.55%   |
| Apple MacBookPro7,1                   | 3         | 0.55%   |
| Apple MacBookAir6,2                   | 3         | 0.55%   |
| Acer Aspire A515-45                   | 3         | 0.55%   |
| System76 Pangolin                     | 2         | 0.36%   |
| Samsung 760XDA                        | 2         | 0.36%   |
| MSI Katana GF76 11UD                  | 2         | 0.36%   |
| MSI GF63 Thin 11UD                    | 2         | 0.36%   |
| Lenovo V14-IIL 82C4                   | 2         | 0.36%   |
| Lenovo ThinkPad E14 Gen 4 21ECS00000  | 2         | 0.36%   |
| Lenovo Legion 5 15IMH05H 81Y6         | 2         | 0.36%   |
| Lenovo Legion 5 15ACH6 82JW           | 2         | 0.36%   |
| Lenovo IdeaPad 5 Pro 16ARH7 82SN      | 2         | 0.36%   |
| HP Pavilion 15                        | 2         | 0.36%   |
| HP Pavilion 13 x360 PC                | 2         | 0.36%   |
| HP EliteBook 8570w                    | 2         | 0.36%   |
| HP EliteBook 855 G8 Notebook PC       | 2         | 0.36%   |
| HP EliteBook 745 G2                   | 2         | 0.36%   |
| HP Dev One Notebook PC                | 2         | 0.36%   |
| HP 15 Notebook PC                     | 2         | 0.36%   |
| GPU Company GWTN141-10                | 2         | 0.36%   |
| Google Lulu                           | 2         | 0.36%   |
| Framework Laptop                      | 2         | 0.36%   |
| Dell XPS 9320                         | 2         | 0.36%   |
| Dell XPS 15 9570                      | 2         | 0.36%   |
| Dell XPS 15 9510                      | 2         | 0.36%   |
| Dell XPS 13 9310                      | 2         | 0.36%   |
| Dell XPS 13 7390                      | 2         | 0.36%   |
| Dell Vostro 5470                      | 2         | 0.36%   |
| Dell Vostro 5402                      | 2         | 0.36%   |
| Dell Vostro 15 3515                   | 2         | 0.36%   |
| Dell Precision M4800                  | 2         | 0.36%   |
| Dell Precision M4600                  | 2         | 0.36%   |
| Dell Latitude E7470                   | 2         | 0.36%   |
| Dell Latitude E7270                   | 2         | 0.36%   |
| Dell Latitude E6540                   | 2         | 0.36%   |
| Dell Inspiron 5566                    | 2         | 0.36%   |
| Dell Inspiron 5547                    | 2         | 0.36%   |
| Dell Inspiron 3542                    | 2         | 0.36%   |
| Dell Inspiron 3442                    | 2         | 0.36%   |
| Dell Inspiron 1750                    | 2         | 0.36%   |
| ASUS Zenbook UX5401ZAS_UX5401ZAS      | 2         | 0.36%   |
| ASUS X556UQK                          | 2         | 0.36%   |
| ASUS ROG Zephyrus G14 GA401IV_GA401IV | 2         | 0.36%   |
| ASUS N550JV                           | 2         | 0.36%   |
| Apple MacBookPro9,2                   | 2         | 0.36%   |
| Apple MacBookPro16,2                  | 2         | 0.36%   |
| Apple MacBookPro12,1                  | 2         | 0.36%   |
| Apple MacBookPro11,5                  | 2         | 0.36%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 45        | 8.2%    |
| Acer Aspire            | 31        | 5.65%   |
| Lenovo IdeaPad         | 28        | 5.1%    |
| Dell Inspiron          | 27        | 4.92%   |
| Dell Latitude          | 22        | 4.01%   |
| Dell XPS               | 21        | 3.83%   |
| ASUS ROG               | 15        | 2.73%   |
| Lenovo Legion          | 13        | 2.37%   |
| HP Pavilion            | 13        | 2.37%   |
| Toshiba Satellite      | 12        | 2.19%   |
| HP EliteBook           | 11        | 2%      |
| Dell Precision         | 11        | 2%      |
| HP Laptop              | 10        | 1.82%   |
| Dell Vostro            | 10        | 1.82%   |
| HP ProBook             | 9         | 1.64%   |
| System76 Oryx          | 8         | 1.46%   |
| ASUS VivoBook          | 7         | 1.28%   |
| HP OMEN                | 6         | 1.09%   |
| ASUS Zenbook           | 6         | 1.09%   |
| Acer Swift             | 6         | 1.09%   |
| Apple MacBookPro11     | 5         | 0.91%   |
| Apple MacBookAir7      | 5         | 0.91%   |
| MSI GF63               | 4         | 0.73%   |
| Lenovo ThinkBook       | 4         | 0.73%   |
| ASUS ASUS              | 4         | 0.73%   |
| Acer Nitro             | 4         | 0.73%   |
| Unknown                | 4         | 0.73%   |
| System76 Lemur         | 3         | 0.55%   |
| MSI Prestige           | 3         | 0.55%   |
| MSI Modern             | 3         | 0.55%   |
| MSI Katana             | 3         | 0.55%   |
| HP ZBook               | 3         | 0.55%   |
| HP ENVY                | 3         | 0.55%   |
| GPU Company GWTC116-2  | 3         | 0.55%   |
| Apple MacBookPro9      | 3         | 0.55%   |
| Apple MacBookPro7      | 3         | 0.55%   |
| Apple MacBookAir6      | 3         | 0.55%   |
| Apple MacBook5         | 3         | 0.55%   |
| System76 Pangolin      | 2         | 0.36%   |
| System76 Galago        | 2         | 0.36%   |
| Samsung 760XDA         | 2         | 0.36%   |
| MSI GS75               | 2         | 0.36%   |
| Lenovo Yoga            | 2         | 0.36%   |
| Lenovo V14-IIL         | 2         | 0.36%   |
| HP Dev                 | 2         | 0.36%   |
| HP 15                  | 2         | 0.36%   |
| GPU Company GWTN141-10 | 2         | 0.36%   |
| Google Lulu            | 2         | 0.36%   |
| Framework Laptop       | 2         | 0.36%   |
| Dell G7                | 2         | 0.36%   |
| Dell G3                | 2         | 0.36%   |
| ASUS X556UQK           | 2         | 0.36%   |
| ASUS N550JV            | 2         | 0.36%   |
| Apple MacBookPro8      | 2         | 0.36%   |
| Apple MacBookPro16     | 2         | 0.36%   |
| Apple MacBookPro14     | 2         | 0.36%   |
| Apple MacBookPro12     | 2         | 0.36%   |
| Apple MacBookPro10     | 2         | 0.36%   |
| Acer TravelMate        | 2         | 0.36%   |
| Toshiba QOSMIO         | 1         | 0.18%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 91        | 16.58%  |
| 2020 | 69        | 12.57%  |
| 2019 | 50        | 9.11%   |
| 2018 | 42        | 7.65%   |
| 2013 | 41        | 7.47%   |
| 2022 | 38        | 6.92%   |
| 2016 | 35        | 6.38%   |
| 2015 | 34        | 6.19%   |
| 2012 | 30        | 5.46%   |
| 2011 | 28        | 5.1%    |
| 2014 | 27        | 4.92%   |
| 2017 | 25        | 4.55%   |
| 2010 | 17        | 3.1%    |
| 2009 | 17        | 3.1%    |
| 2008 | 3         | 0.55%   |
| 2007 | 2         | 0.36%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 549       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 549       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 533       | 97.09%  |
| Yes  | 16        | 2.91%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 152       | 27.69%  |
| 16.01-24.0  | 137       | 24.95%  |
| 8.01-16.0   | 113       | 20.58%  |
| 3.01-4.0    | 75        | 13.66%  |
| 32.01-64.0  | 49        | 8.93%   |
| 64.01-256.0 | 15        | 2.73%   |
| 24.01-32.0  | 4         | 0.73%   |
| 1.01-2.0    | 3         | 0.55%   |
| 2.01-3.0    | 1         | 0.18%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 211       | 37.15%  |
| 3.01-4.0   | 127       | 22.36%  |
| 4.01-8.0   | 118       | 20.77%  |
| 1.01-2.0   | 84        | 14.79%  |
| 8.01-16.0  | 25        | 4.4%    |
| 16.01-24.0 | 3         | 0.53%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 398       | 72.23%  |
| 2      | 134       | 24.32%  |
| 3      | 17        | 3.09%   |
| 7      | 1         | 0.18%   |
| 0      | 1         | 0.18%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 413       | 75.23%  |
| Yes       | 136       | 24.77%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 424       | 76.95%  |
| No        | 127       | 23.05%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 548       | 99.82%  |
| No        | 1         | 0.18%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 469       | 85.12%  |
| No        | 82        | 14.88%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country               | Notebooks | Percent |
|-----------------------|-----------|---------|
| USA                   | 155       | 28.13%  |
| Brazil                | 55        | 9.98%   |
| Germany               | 38        | 6.9%    |
| India                 | 24        | 4.36%   |
| Australia             | 22        | 3.99%   |
| Canada                | 21        | 3.81%   |
| UK                    | 19        | 3.45%   |
| France                | 15        | 2.72%   |
| Russia                | 12        | 2.18%   |
| Italy                 | 11        | 2%      |
| Sweden                | 9         | 1.63%   |
| Norway                | 9         | 1.63%   |
| Mexico                | 8         | 1.45%   |
| Switzerland           | 7         | 1.27%   |
| Poland                | 7         | 1.27%   |
| Netherlands           | 7         | 1.27%   |
| Spain                 | 6         | 1.09%   |
| Romania               | 6         | 1.09%   |
| New Zealand           | 6         | 1.09%   |
| Greece                | 6         | 1.09%   |
| Belgium               | 6         | 1.09%   |
| Argentina             | 6         | 1.09%   |
| Philippines           | 5         | 0.91%   |
| Colombia              | 5         | 0.91%   |
| Turkey                | 4         | 0.73%   |
| Finland               | 4         | 0.73%   |
| Vietnam               | 3         | 0.54%   |
| Thailand              | 3         | 0.54%   |
| Serbia                | 3         | 0.54%   |
| Morocco               | 3         | 0.54%   |
| Ireland               | 3         | 0.54%   |
| Hungary               | 3         | 0.54%   |
| Egypt                 | 3         | 0.54%   |
| Bulgaria              | 3         | 0.54%   |
| Austria               | 3         | 0.54%   |
| Venezuela             | 2         | 0.36%   |
| Tunisia               | 2         | 0.36%   |
| South Africa          | 2         | 0.36%   |
| Singapore             | 2         | 0.36%   |
| Saudi Arabia          | 2         | 0.36%   |
| Portugal              | 2         | 0.36%   |
| Peru                  | 2         | 0.36%   |
| Panama                | 2         | 0.36%   |
| Malaysia              | 2         | 0.36%   |
| Iraq                  | 2         | 0.36%   |
| Hong Kong             | 2         | 0.36%   |
| Georgia               | 2         | 0.36%   |
| Czechia               | 2         | 0.36%   |
| Croatia               | 2         | 0.36%   |
| Chile                 | 2         | 0.36%   |
| Bangladesh            | 2         | 0.36%   |
| Uzbekistan            | 1         | 0.18%   |
| Uruguay               | 1         | 0.18%   |
| Slovenia              | 1         | 0.18%   |
| Slovakia              | 1         | 0.18%   |
| Republic of the Congo | 1         | 0.18%   |
| Pakistan              | 1         | 0.18%   |
| Maldives              | 1         | 0.18%   |
| Lithuania             | 1         | 0.18%   |
| Latvia                | 1         | 0.18%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Brisbane         | 7         | 1.25%   |
| Oslo             | 6         | 1.07%   |
| Melbourne        | 6         | 1.07%   |
| Rio de Janeiro   | 5         | 0.89%   |
| Mumbai           | 5         | 0.89%   |
| Zurich           | 4         | 0.72%   |
| Sydney           | 4         | 0.72%   |
| Stockholm        | 4         | 0.72%   |
| Sao Paulo        | 4         | 0.72%   |
| Munich           | 4         | 0.72%   |
| Bucharest        | 4         | 0.72%   |
| Berlin           | 4         | 0.72%   |
| Warsaw           | 3         | 0.54%   |
| Ribeirao Preto   | 3         | 0.54%   |
| Mannheim         | 3         | 0.54%   |
| Istanbul         | 3         | 0.54%   |
| Helsinki         | 3         | 0.54%   |
| Durham           | 3         | 0.54%   |
| Calgary          | 3         | 0.54%   |
| Budapest         | 3         | 0.54%   |
| Bengaluru        | 3         | 0.54%   |
| Auckland         | 3         | 0.54%   |
| Vienna           | 2         | 0.36%   |
| Victoria         | 2         | 0.36%   |
| Vancouver        | 2         | 0.36%   |
| Turin            | 2         | 0.36%   |
| Tunis            | 2         | 0.36%   |
| Toronto          | 2         | 0.36%   |
| Tallahassee      | 2         | 0.36%   |
| St Petersburg    | 2         | 0.36%   |
| Spokane          | 2         | 0.36%   |
| Sofia            | 2         | 0.36%   |
| Singapore        | 2         | 0.36%   |
| Seattle          | 2         | 0.36%   |
| San Jose         | 2         | 0.36%   |
| San Diego        | 2         | 0.36%   |
| San Antonio      | 2         | 0.36%   |
| Riverview        | 2         | 0.36%   |
| Quezon City      | 2         | 0.36%   |
| Poznan           | 2         | 0.36%   |
| Portland         | 2         | 0.36%   |
| Paris            | 2         | 0.36%   |
| Panama City      | 2         | 0.36%   |
| Ottawa           | 2         | 0.36%   |
| Nynaeshamn       | 2         | 0.36%   |
| Moscow           | 2         | 0.36%   |
| Minneapolis      | 2         | 0.36%   |
| Mendoza          | 2         | 0.36%   |
| Manaus           | 2         | 0.36%   |
| Madrid           | 2         | 0.36%   |
| Lynnwood         | 2         | 0.36%   |
| London           | 2         | 0.36%   |
| Lansing          | 2         | 0.36%   |
| Kelowna          | 2         | 0.36%   |
| Itatiba          | 2         | 0.36%   |
| Ho Chi Minh City | 2         | 0.36%   |
| Heraklion        | 2         | 0.36%   |
| Guwahati         | 2         | 0.36%   |
| Ghent            | 2         | 0.36%   |
| Gatineau         | 2         | 0.36%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 128       | 146    | 18.36%  |
| WDC                            | 62        | 67     | 8.9%    |
| SanDisk                        | 57        | 66     | 8.18%   |
| Seagate                        | 51        | 58     | 7.32%   |
| Kingston                       | 45        | 52     | 6.46%   |
| Toshiba                        | 42        | 49     | 6.03%   |
| SK hynix                       | 40        | 42     | 5.74%   |
| Crucial                        | 23        | 23     | 3.3%    |
| Apple                          | 22        | 24     | 3.16%   |
| Unknown                        | 21        | 23     | 3.01%   |
| HGST                           | 20        | 20     | 2.87%   |
| Micron Technology              | 19        | 21     | 2.73%   |
| Intel                          | 18        | 19     | 2.58%   |
| Phison                         | 16        | 17     | 2.3%    |
| Hitachi                        | 10        | 11     | 1.43%   |
| A-DATA Technology              | 8         | 9      | 1.15%   |
| PNY                            | 7         | 8      | 1%      |
| Silicon Motion                 | 6         | 6      | 0.86%   |
| Micron/Crucial Technology      | 5         | 5      | 0.72%   |
| LITEONIT                       | 5         | 5      | 0.72%   |
| LITEON                         | 5         | 5      | 0.72%   |
| KIOXIA                         | 5         | 5      | 0.72%   |
| KingSpec                       | 5         | 5      | 0.72%   |
| ADATA Technology               | 5         | 5      | 0.72%   |
| Union Memory (Shenzhen)        | 4         | 6      | 0.57%   |
| Intenso                        | 4         | 4      | 0.57%   |
| Team                           | 3         | 3      | 0.43%   |
| Solid State Storage Technology | 3         | 3      | 0.43%   |
| MyDigitalSSD                   | 3         | 3      | 0.43%   |
| China                          | 3         | 3      | 0.43%   |
| Unknown                        | 3         | 4      | 0.43%   |
| W800S                          | 2         | 4      | 0.29%   |
| SSSTC                          | 2         | 2      | 0.29%   |
| SPCC                           | 2         | 2      | 0.29%   |
| MAXIO Technology (Hangzhou)    | 2         | 2      | 0.29%   |
| Lexar                          | 2         | 2      | 0.29%   |
| Fujitsu                        | 2         | 2      | 0.29%   |
| Apacer                         | 2         | 4      | 0.29%   |
| YMTC                           | 1         | 1      | 0.14%   |
| USB3.0                         | 1         | 1      | 0.14%   |
| UMIS                           | 1         | 1      | 0.14%   |
| TwinMOS                        | 1         | 1      | 0.14%   |
| TrekStor                       | 1         | 1      | 0.14%   |
| Transcend                      | 1         | 1      | 0.14%   |
| Teutons                        | 1         | 1      | 0.14%   |
| T-FORCE                        | 1         | 1      | 0.14%   |
| Shenzhen Longsys Electronics   | 1         | 1      | 0.14%   |
| SATAFIRM                       | 1         | 1      | 0.14%   |
| ROG                            | 1         | 1      | 0.14%   |
| Ramaxel Technology             | 1         | 1      | 0.14%   |
| Radeon                         | 1         | 1      | 0.14%   |
| PUSKILL                        | 1         | 1      | 0.14%   |
| PNY USB                        | 1         | 1      | 0.14%   |
| Patriot                        | 1         | 1      | 0.14%   |
| OWC                            | 1         | 1      | 0.14%   |
| OEM                            | 1         | 1      | 0.14%   |
| Netac                          | 1         | 1      | 0.14%   |
| Lite-On                        | 1         | 1      | 0.14%   |
| Leven                          | 1         | 1      | 0.14%   |
| KingFast                       | 1         | 2      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 512GB            | 14        | 1.95%   |
| Kingston SA400S37240G 240GB SSD         | 14        | 1.95%   |
| SanDisk NVMe SSD Drive 1TB              | 10        | 1.39%   |
| SK hynix NVMe SSD Drive 512GB           | 9         | 1.25%   |
| SK hynix NVMe SSD Drive 1024GB          | 8         | 1.11%   |
| SanDisk NVMe SSD Drive 256GB            | 8         | 1.11%   |
| Samsung NVMe SSD Drive 2TB              | 8         | 1.11%   |
| Samsung NVMe SSD Drive 256GB            | 8         | 1.11%   |
| HGST HTS721010A9E630 1TB                | 8         | 1.11%   |
| SanDisk NVMe SSD Drive 512GB            | 7         | 0.97%   |
| Samsung SM963 2.5" NVMe PCIe SSD 1024GB | 7         | 0.97%   |
| Samsung NVMe SSD Drive 1TB              | 7         | 0.97%   |
| Kingston NVMe SSD Drive 512GB           | 7         | 0.97%   |
| Toshiba MQ04ABF100 1TB                  | 6         | 0.83%   |
| Seagate ST1000LM035-1RK172 1TB          | 6         | 0.83%   |
| Samsung NVMe SSD Drive 500GB            | 6         | 0.83%   |
| Kingston SA400S37120G 120GB SSD         | 6         | 0.83%   |
| WDC WD10SPZX-24Z10 1TB                  | 5         | 0.7%    |
| Toshiba MQ01ABD100 1TB                  | 5         | 0.7%    |
| Samsung SSD 850 EVO 500GB               | 5         | 0.7%    |
| Intel NVMe SSD Drive 512GB              | 5         | 0.7%    |
| Crucial CT240BX500SSD1 240GB            | 5         | 0.7%    |
| Toshiba MQ01ACF050 500GB                | 4         | 0.56%   |
| SK hynix NVMe SSD Drive 256GB           | 4         | 0.56%   |
| Seagate ST2000LM007-1R8174 2TB          | 4         | 0.56%   |
| Seagate ST1000LM049-2GH172 1TB          | 4         | 0.56%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 4         | 0.56%   |
| SanDisk NVMe SSD Drive 1024GB           | 4         | 0.56%   |
| Samsung SSD 970 EVO Plus 1TB            | 4         | 0.56%   |
| Samsung SSD 860 QVO 1TB                 | 4         | 0.56%   |
| Micron NVMe SSD Drive 512GB             | 4         | 0.56%   |
| Kingston SA400S37480G 480GB SSD         | 4         | 0.56%   |
| Crucial CT1000MX500SSD1 1TB             | 4         | 0.56%   |
| Apple SSD SM0512G 500GB                 | 4         | 0.56%   |
| Apple SSD SM0128G 121GB                 | 4         | 0.56%   |
| ADATA NVMe SSD Drive 256GB              | 4         | 0.56%   |
| Unknown SD/MMC/MS PRO 128GB             | 3         | 0.42%   |
| Unknown MMC Card  64GB                  | 3         | 0.42%   |
| Unknown MMC Card  32GB                  | 3         | 0.42%   |
| Unknown MMC Card  128GB                 | 3         | 0.42%   |
| Toshiba MQ01ABD075 752GB                | 3         | 0.42%   |
| Seagate ST9320325AS 320GB               | 3         | 0.42%   |
| Seagate ST2000LX001-1RG174 2TB          | 3         | 0.42%   |
| Seagate ST1000LM014-1EJ164 1TB          | 3         | 0.42%   |
| SanDisk NVMe SSD Drive 500GB            | 3         | 0.42%   |
| Samsung SSD 860 EVO M.2 500GB           | 3         | 0.42%   |
| Samsung NVMe SSD Drive 250GB            | 3         | 0.42%   |
| Samsung MZALQ512HBLU-00BL2 512GB        | 3         | 0.42%   |
| PNY ELITE PSSD 480GB                    | 3         | 0.42%   |
| PNY CS900 240GB SSD                     | 3         | 0.42%   |
| Phison NVMe SSD Drive 256GB             | 3         | 0.42%   |
| Micron NVMe SSD Drive 1024GB            | 3         | 0.42%   |
| Kingston OM8PCP3512F-AI1 512GB          | 3         | 0.42%   |
| Intel NVMe SSD Drive 256GB              | 3         | 0.42%   |
| Intel NVMe SSD Drive 1024GB             | 3         | 0.42%   |
| HGST HTS725050A7E630 500GB              | 3         | 0.42%   |
| HGST HTS541010A9E680 1TB                | 3         | 0.42%   |
| Unknown                                 | 3         | 0.42%   |
| WDC WD5000LPVX-75V0TT0 500GB            | 2         | 0.28%   |
| WDC WD5000LPCX-60VHAT0 500GB            | 2         | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 49        | 56     | 30.06%  |
| WDC                 | 40        | 45     | 24.54%  |
| Toshiba             | 30        | 34     | 18.4%   |
| HGST                | 20        | 20     | 12.27%  |
| Hitachi             | 10        | 11     | 6.13%   |
| Unknown             | 3         | 3      | 1.84%   |
| Samsung Electronics | 3         | 3      | 1.84%   |
| Fujitsu             | 2         | 2      | 1.23%   |
| USB3.0              | 1         | 1      | 0.61%   |
| SATAFIRM            | 1         | 1      | 0.61%   |
| Intenso             | 1         | 1      | 0.61%   |
| HGST HDN            | 1         | 1      | 0.61%   |
| Asm                 | 1         | 1      | 0.61%   |
| Apple               | 1         | 1      | 0.61%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 44        | 45     | 20.28%  |
| Kingston            | 31        | 32     | 14.29%  |
| SanDisk             | 26        | 29     | 11.98%  |
| Crucial             | 18        | 18     | 8.29%   |
| Apple               | 16        | 17     | 7.37%   |
| WDC                 | 8         | 8      | 3.69%   |
| PNY                 | 7         | 8      | 3.23%   |
| LITEONIT            | 5         | 5      | 2.3%    |
| LITEON              | 5         | 5      | 2.3%    |
| KingSpec            | 5         | 5      | 2.3%    |
| SK hynix            | 4         | 4      | 1.84%   |
| A-DATA Technology   | 4         | 5      | 1.84%   |
| Toshiba             | 3         | 3      | 1.38%   |
| MyDigitalSSD        | 3         | 3      | 1.38%   |
| Micron Technology   | 3         | 3      | 1.38%   |
| China               | 3         | 3      | 1.38%   |
| SPCC                | 2         | 2      | 0.92%   |
| Intenso             | 2         | 2      | 0.92%   |
| Intel               | 2         | 2      | 0.92%   |
| Apacer              | 2         | 4      | 0.92%   |
| W800S               | 1         | 1      | 0.46%   |
| TwinMOS             | 1         | 1      | 0.46%   |
| TrekStor            | 1         | 1      | 0.46%   |
| Transcend           | 1         | 1      | 0.46%   |
| Teutons             | 1         | 1      | 0.46%   |
| Ramaxel Technology  | 1         | 1      | 0.46%   |
| Radeon              | 1         | 1      | 0.46%   |
| PUSKILL             | 1         | 1      | 0.46%   |
| PNY USB             | 1         | 1      | 0.46%   |
| Phison              | 1         | 1      | 0.46%   |
| Patriot             | 1         | 1      | 0.46%   |
| OWC                 | 1         | 1      | 0.46%   |
| Lexar               | 1         | 1      | 0.46%   |
| Leven               | 1         | 1      | 0.46%   |
| KingFast            | 1         | 1      | 0.46%   |
| KingDian            | 1         | 1      | 0.46%   |
| KINGBANK            | 1         | 1      | 0.46%   |
| Inland              | 1         | 1      | 0.46%   |
| HS-SSD-C100         | 1         | 1      | 0.46%   |
| Hikvision           | 1         | 1      | 0.46%   |
| GOODRAM             | 1         | 1      | 0.46%   |
| BHT                 | 1         | 1      | 0.46%   |
| AFOX                | 1         | 1      | 0.46%   |
| Aarvex              | 1         | 1      | 0.46%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 263       | 331    | 40.46%  |
| SSD     | 201       | 227    | 30.92%  |
| HDD     | 158       | 180    | 24.31%  |
| MMC     | 19        | 21     | 2.92%   |
| Unknown | 9         | 12     | 1.38%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 320       | 394    | 51.2%   |
| NVMe | 263       | 330    | 42.08%  |
| SAS  | 23        | 26     | 3.68%   |
| MMC  | 19        | 21     | 3.04%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 230       | 269    | 65.53%  |
| 0.51-1.0   | 105       | 118    | 29.91%  |
| 1.01-2.0   | 13        | 15     | 3.7%    |
| 3.01-4.0   | 2         | 4      | 0.57%   |
| 4.01-10.0  | 1         | 1      | 0.28%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 191       | 34.54%  |
| 251-500        | 157       | 28.39%  |
| 501-1000       | 111       | 20.07%  |
| 1001-2000      | 33        | 5.97%   |
| 51-100         | 19        | 3.44%   |
| 21-50          | 14        | 2.53%   |
| 2001-3000      | 9         | 1.63%   |
| More than 3000 | 8         | 1.45%   |
| 1-20           | 8         | 1.45%   |
| Unknown        | 3         | 0.54%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 205       | 36.28%  |
| 21-50          | 144       | 25.49%  |
| 101-250        | 78        | 13.81%  |
| 51-100         | 67        | 11.86%  |
| 251-500        | 40        | 7.08%   |
| 501-1000       | 22        | 3.89%   |
| 1001-2000      | 5         | 0.88%   |
| Unknown        | 3         | 0.53%   |
| More than 3000 | 1         | 0.18%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Toshiba MQ01ACF050 500GB              | 1         | 1      | 7.69%   |
| Team TM8FP4004T 4TB                   | 1         | 1      | 7.69%   |
| SK hynix PC711 HFS001TDE9X073N 1TB    | 1         | 1      | 7.69%   |
| Seagate ST9320325AS 320GB             | 1         | 1      | 7.69%   |
| Seagate ST500LM030-2E717D 500GB       | 1         | 1      | 7.69%   |
| Seagate ST1000LX015-1U7172 1TB        | 1         | 1      | 7.69%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1         | 1      | 7.69%   |
| Samsung Electronics SSD 850 EVO 500GB | 1         | 1      | 7.69%   |
| Lexar 1TB SSD                         | 1         | 1      | 7.69%   |
| Leven JAJS600M256C 256GB              | 1         | 1      | 7.69%   |
| Hitachi HTS545050A7E380 500GB         | 1         | 2      | 7.69%   |
| HGST HTS725050A7E630 500GB            | 1         | 1      | 7.69%   |
| HGST HTS721010A9E630 1TB              | 1         | 1      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 4      | 30.77%  |
| HGST                | 2         | 2      | 15.38%  |
| Toshiba             | 1         | 1      | 7.69%   |
| Team                | 1         | 1      | 7.69%   |
| SK hynix            | 1         | 1      | 7.69%   |
| Samsung Electronics | 1         | 1      | 7.69%   |
| Lexar               | 1         | 1      | 7.69%   |
| Leven               | 1         | 1      | 7.69%   |
| Hitachi             | 1         | 2      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 50%     |
| HGST    | 2         | 2      | 25%     |
| Toshiba | 1         | 1      | 12.5%   |
| Hitachi | 1         | 2      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 9      | 61.54%  |
| NVMe | 3         | 3      | 23.08%  |
| SSD  | 2         | 2      | 15.38%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Samsung Electronics HM321HI 320GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 431       | 587    | 74.18%  |
| Works    | 136       | 169    | 23.41%  |
| Malfunc  | 13        | 14     | 2.24%   |
| Failed   | 1         | 1      | 0.17%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 334       | 47.04%  |
| Samsung Electronics            | 94        | 13.24%  |
| AMD                            | 79        | 11.13%  |
| SanDisk                        | 43        | 6.06%   |
| SK hynix                       | 36        | 5.07%   |
| Phison Electronics             | 16        | 2.25%   |
| Micron Technology              | 15        | 2.11%   |
| Kingston Technology Company    | 13        | 1.83%   |
| Nvidia                         | 11        | 1.55%   |
| Toshiba America Info Systems   | 10        | 1.41%   |
| Micron/Crucial Technology      | 9         | 1.27%   |
| Silicon Motion                 | 8         | 1.13%   |
| ADATA Technology               | 8         | 1.13%   |
| Union Memory (Shenzhen)        | 5         | 0.7%    |
| Solid State Storage Technology | 5         | 0.7%    |
| KIOXIA                         | 5         | 0.7%    |
| Apple                          | 5         | 0.7%    |
| Shenzhen Longsys Electronics   | 3         | 0.42%   |
| Marvell Technology Group       | 3         | 0.42%   |
| Realtek Semiconductor          | 2         | 0.28%   |
| MAXIO Technology (Hangzhou)    | 2         | 0.28%   |
| Yangtze Memory Technologies    | 1         | 0.14%   |
| Unknown                        | 1         | 0.14%   |
| Seagate Technology             | 1         | 0.14%   |
| Lite-On Technology             | 1         | 0.14%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 75        | 10.15%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 40        | 5.41%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 36        | 4.87%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 32        | 4.33%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 32        | 4.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 26        | 3.52%   |
| Intel Volume Management Device NVMe RAID Controller                              | 22        | 2.98%   |
| SK hynix Gold P31 SSD                                                            | 21        | 2.84%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 20        | 2.71%   |
| Samsung NVMe SSD Controller 980                                                  | 19        | 2.57%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 17        | 2.3%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 17        | 2.3%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 16        | 2.17%   |
| Micron Non-Volatile memory controller                                            | 15        | 2.03%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 15        | 2.03%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 15        | 2.03%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 14        | 1.89%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 12        | 1.62%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 10        | 1.35%   |
| SK hynix Non-Volatile memory controller                                          | 9         | 1.22%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 9         | 1.22%   |
| SanDisk Non-Volatile memory controller                                           | 9         | 1.22%   |
| Samsung Electronics SATA controller                                              | 9         | 1.22%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 9         | 1.22%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 8         | 1.08%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 8         | 1.08%   |
| Phison E12 NVMe Controller                                                       | 8         | 1.08%   |
| Kingston Company Company Non-Volatile memory controller                          | 8         | 1.08%   |
| Intel SSD 660P Series                                                            | 8         | 1.08%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 7         | 0.95%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 7         | 0.95%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 7         | 0.95%   |
| ADATA Non-Volatile memory controller                                             | 7         | 0.95%   |
| Intel Tiger Lake-LP SATA Controller                                              | 6         | 0.81%   |
| Intel Comet Lake SATA AHCI Controller                                            | 6         | 0.81%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 5         | 0.68%   |
| Solid State Storage Non-Volatile memory controller                               | 5         | 0.68%   |
| Nvidia MCP79 AHCI Controller                                                     | 5         | 0.68%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 5         | 0.68%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 5         | 0.68%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 5         | 0.68%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 4         | 0.54%   |
| Phison PS5013 E13 NVMe Controller                                                | 4         | 0.54%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                         | 4         | 0.54%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 4         | 0.54%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 4         | 0.54%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 4         | 0.54%   |
| Apple ANS2 NVMe Controller                                                       | 4         | 0.54%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 3         | 0.41%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 3         | 0.41%   |
| SK hynix BC511                                                                   | 3         | 0.41%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 3         | 0.41%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 3         | 0.41%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 3         | 0.41%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 0.41%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3         | 0.41%   |
| Union Memory (Shenzhen) AM630 PCIe 4.0 x4 NVMe SSD Controller                    | 2         | 0.27%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 2         | 0.27%   |
| Shenzhen Longsys Electronics Non-Volatile memory controller                      | 2         | 0.27%   |
| SanDisk WD Blue SN570 NVMe SSD                                                   | 2         | 0.27%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 366       | 52.14%  |
| NVMe | 262       | 37.32%  |
| RAID | 56        | 7.98%   |
| IDE  | 18        | 2.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 420       | 76.5%   |
| AMD    | 129       | 23.5%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 19        | 3.46%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 13        | 2.37%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 9         | 1.64%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 9         | 1.64%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 9         | 1.64%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 8         | 1.46%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 7         | 1.28%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 7         | 1.28%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 7         | 1.28%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 6         | 1.09%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 6         | 1.09%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 6         | 1.09%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 6         | 1.09%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 6         | 1.09%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 6         | 1.09%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 6         | 1.09%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 6         | 1.09%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 6         | 1.09%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 6         | 1.09%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 5         | 0.91%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 5         | 0.91%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 5         | 0.91%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 5         | 0.91%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 5         | 0.91%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 5         | 0.91%   |
| Intel 12th Gen Core i7-12700H                 | 5         | 0.91%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 5         | 0.91%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 5         | 0.91%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 4         | 0.73%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 4         | 0.73%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 4         | 0.73%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 4         | 0.73%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 4         | 0.73%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 4         | 0.73%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 4         | 0.73%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 4         | 0.73%   |
| AMD Ryzen 7 PRO 5850U with Radeon Graphics    | 4         | 0.73%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 4         | 0.73%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 3         | 0.55%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 3         | 0.55%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 3         | 0.55%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 3         | 0.55%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 3         | 0.55%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 3         | 0.55%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 3         | 0.55%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 3         | 0.55%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 3         | 0.55%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 3         | 0.55%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 0.55%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 3         | 0.55%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 3         | 0.55%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 3         | 0.55%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 3         | 0.55%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 3         | 0.55%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 0.55%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 3         | 0.55%   |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz          | 3         | 0.55%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 3         | 0.55%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 3         | 0.55%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 3         | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 147       | 26.78%  |
| Intel Core i5           | 120       | 21.86%  |
| Other                   | 67        | 12.2%   |
| AMD Ryzen 7             | 40        | 7.29%   |
| Intel Core i3           | 36        | 6.56%   |
| AMD Ryzen 5             | 31        | 5.65%   |
| Intel Core 2 Duo        | 18        | 3.28%   |
| Intel Celeron           | 15        | 2.73%   |
| AMD Ryzen 9             | 11        | 2%      |
| Intel Pentium           | 8         | 1.46%   |
| AMD Ryzen 7 PRO         | 7         | 1.28%   |
| AMD Ryzen 3             | 7         | 1.28%   |
| AMD A6                  | 7         | 1.28%   |
| AMD A10                 | 7         | 1.28%   |
| AMD A8                  | 6         | 1.09%   |
| Intel Core i9           | 4         | 0.73%   |
| Intel Pentium Dual-Core | 3         | 0.55%   |
| AMD Ryzen 5 PRO         | 2         | 0.36%   |
| AMD Athlon              | 2         | 0.36%   |
| Intel Xeon              | 1         | 0.18%   |
| Intel Pentium Gold      | 1         | 0.18%   |
| Intel Core m3           | 1         | 0.18%   |
| Intel Atom              | 1         | 0.18%   |
| AMD Turion 64 X2 Mobile | 1         | 0.18%   |
| AMD Phenom II           | 1         | 0.18%   |
| AMD E2                  | 1         | 0.18%   |
| AMD E                   | 1         | 0.18%   |
| AMD Athlon X2           | 1         | 0.18%   |
| AMD A4                  | 1         | 0.18%   |
| AMD A12                 | 1         | 0.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 216       | 39.34%  |
| 4      | 181       | 32.97%  |
| 8      | 83        | 15.12%  |
| 6      | 54        | 9.84%   |
| 14     | 9         | 1.64%   |
| 12     | 3         | 0.55%   |
| 1      | 2         | 0.36%   |
| 10     | 1         | 0.18%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 549       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 474       | 86.34%  |
| 1      | 75        | 13.66%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 549       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 410       | 74.14%  |
| 0x0a50000c | 12        | 2.17%   |
| 0x806d1    | 11        | 1.99%   |
| 0x806c1    | 11        | 1.99%   |
| 0x806ec    | 8         | 1.45%   |
| 0xa0652    | 7         | 1.27%   |
| 0x806ea    | 7         | 1.27%   |
| 0x306a9    | 7         | 1.27%   |
| 0x0a404101 | 6         | 1.08%   |
| 0x906ea    | 5         | 0.9%    |
| 0x906a3    | 5         | 0.9%    |
| 0x806e9    | 4         | 0.72%   |
| 0x706e5    | 4         | 0.72%   |
| 0x506e3    | 4         | 0.72%   |
| 0x406e3    | 4         | 0.72%   |
| 0x40651    | 4         | 0.72%   |
| 0x306c3    | 4         | 0.72%   |
| 0x08608103 | 4         | 0.72%   |
| 0x08600106 | 4         | 0.72%   |
| 0x306d4    | 3         | 0.54%   |
| 0x08600104 | 3         | 0.54%   |
| 0x08600103 | 3         | 0.54%   |
| 0x08108109 | 3         | 0.54%   |
| 0xa0660    | 2         | 0.36%   |
| 0x906e9    | 2         | 0.36%   |
| 0x806eb    | 2         | 0.36%   |
| 0x806c2    | 2         | 0.36%   |
| 0x1067a    | 2         | 0.36%   |
| 0x0810100b | 2         | 0.36%   |
| 0x906c0    | 1         | 0.18%   |
| 0x906a4    | 1         | 0.18%   |
| 0x706a8    | 1         | 0.18%   |
| 0x30678    | 1         | 0.18%   |
| 0x206a7    | 1         | 0.18%   |
| 0x08108102 | 1         | 0.18%   |
| 0x07030105 | 1         | 0.18%   |
| 0x06006705 | 1         | 0.18%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 93        | 16.91%  |
| Haswell          | 53        | 9.64%   |
| Unknown          | 48        | 8.73%   |
| SandyBridge      | 34        | 6.18%   |
| Zen 3            | 33        | 6%      |
| IvyBridge        | 33        | 6%      |
| TigerLake        | 30        | 5.45%   |
| Skylake          | 30        | 5.45%   |
| CometLake        | 25        | 4.55%   |
| Broadwell        | 24        | 4.36%   |
| Icelake          | 23        | 4.18%   |
| Penryn           | 20        | 3.64%   |
| Zen+             | 19        | 3.45%   |
| Zen 2            | 18        | 3.27%   |
| Westmere         | 13        | 2.36%   |
| Silvermont       | 8         | 1.45%   |
| Puma             | 7         | 1.27%   |
| Excavator        | 7         | 1.27%   |
| Piledriver       | 5         | 0.91%   |
| Alderlake Hybrid | 5         | 0.91%   |
| Zen              | 4         | 0.73%   |
| K10 Llano        | 4         | 0.73%   |
| Goldmont plus    | 4         | 0.73%   |
| Steamroller      | 2         | 0.36%   |
| K8 Hammer        | 2         | 0.36%   |
| Tremont          | 1         | 0.18%   |
| Nehalem          | 1         | 0.18%   |
| K10              | 1         | 0.18%   |
| Goldmont         | 1         | 0.18%   |
| Core             | 1         | 0.18%   |
| Bobcat           | 1         | 0.18%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 378       | 51.99%  |
| Nvidia | 202       | 27.79%  |
| AMD    | 147       | 20.22%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 29        | 3.91%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 29        | 3.91%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 28        | 3.77%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 28        | 3.77%   |
| AMD Cezanne                                                                              | 26        | 3.5%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 19        | 2.56%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 19        | 2.56%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 19        | 2.56%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 18        | 2.43%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 18        | 2.43%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 18        | 2.43%   |
| AMD Renoir                                                                               | 18        | 2.43%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 17        | 2.29%   |
| Intel HD Graphics 5500                                                                   | 17        | 2.29%   |
| Intel UHD Graphics 620                                                                   | 16        | 2.16%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 15        | 2.02%   |
| Intel HD Graphics 620                                                                    | 15        | 2.02%   |
| AMD Lucienne                                                                             | 15        | 2.02%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 14        | 1.89%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 12        | 1.62%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 11        | 1.48%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 11        | 1.48%   |
| AMD Rembrandt [Radeon 680M]                                                              | 11        | 1.48%   |
| Intel HD Graphics 630                                                                    | 10        | 1.35%   |
| Intel Core Processor Integrated Graphics Controller                                      | 10        | 1.35%   |
| Intel HD Graphics 530                                                                    | 9         | 1.21%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 8         | 1.08%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 8         | 1.08%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 8         | 1.08%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 8         | 1.08%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 7         | 0.94%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 6         | 0.81%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 6         | 0.81%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 5         | 0.67%   |
| Nvidia TU117M                                                                            | 5         | 0.67%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 5         | 0.67%   |
| Intel HD Graphics 6000                                                                   | 5         | 0.67%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 0.67%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 0.54%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 4         | 0.54%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 4         | 0.54%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 4         | 0.54%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 4         | 0.54%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 0.54%   |
| Intel Comet Lake UHD Graphics                                                            | 4         | 0.54%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 4         | 0.54%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 0.54%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 4         | 0.54%   |
| AMD Barcelo                                                                              | 4         | 0.54%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 4         | 0.54%   |
| Nvidia GP108M [GeForce MX330]                                                            | 3         | 0.4%    |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 0.4%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 0.4%    |
| Nvidia GM108M [GeForce 940M]                                                             | 3         | 0.4%    |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 3         | 0.4%    |
| Nvidia GK208M [GeForce GT 740M]                                                          | 3         | 0.4%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 0.4%    |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                                 | 3         | 0.4%    |
| Intel Iris Plus Graphics G7                                                              | 3         | 0.4%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 0.4%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 236       | 42.83%  |
| Intel + Nvidia | 130       | 23.59%  |
| 1 x AMD        | 89        | 16.15%  |
| 1 x Nvidia     | 37        | 6.72%   |
| AMD + Nvidia   | 33        | 5.99%   |
| Intel + AMD    | 13        | 2.36%   |
| 2 x AMD        | 12        | 2.18%   |
| 2 x Nvidia     | 1         | 0.18%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 383       | 69.26%  |
| Proprietary | 161       | 29.11%  |
| Unknown     | 9         | 1.63%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 470       | 84.84%  |
| 1.01-2.0   | 18        | 3.25%   |
| 0.01-0.5   | 18        | 3.25%   |
| 3.01-4.0   | 17        | 3.07%   |
| 7.01-8.0   | 15        | 2.71%   |
| 5.01-6.0   | 9         | 1.62%   |
| 0.51-1.0   | 3         | 0.54%   |
| 2.01-3.0   | 2         | 0.36%   |
| 8.01-16.0  | 2         | 0.36%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 126       | 19.53%  |
| BOE                     | 105       | 16.28%  |
| LG Display              | 89        | 13.8%   |
| Chimei Innolux          | 88        | 13.64%  |
| Samsung Electronics     | 52        | 8.06%   |
| Apple                   | 36        | 5.58%   |
| Dell                    | 24        | 3.72%   |
| Sharp                   | 22        | 3.41%   |
| Goldstar                | 17        | 2.64%   |
| PANDA                   | 14        | 2.17%   |
| Lenovo                  | 7         | 1.09%   |
| Acer                    | 7         | 1.09%   |
| AOC                     | 6         | 0.93%   |
| InfoVision              | 5         | 0.78%   |
| CSO                     | 5         | 0.78%   |
| ASUSTek Computer        | 4         | 0.62%   |
| TMX                     | 3         | 0.47%   |
| Philips                 | 3         | 0.47%   |
| Hewlett-Packard         | 3         | 0.47%   |
| Chi Mei Optoelectronics | 3         | 0.47%   |
| Vizio                   | 2         | 0.31%   |
| TCL                     | 2         | 0.31%   |
| JDI                     | 2         | 0.31%   |
| Iiyama                  | 2         | 0.31%   |
| ViewSonic               | 1         | 0.16%   |
| Vestel Elektronik       | 1         | 0.16%   |
| Unknown                 | 1         | 0.16%   |
| Toshiba                 | 1         | 0.16%   |
| STA                     | 1         | 0.16%   |
| Sony                    | 1         | 0.16%   |
| SGT                     | 1         | 0.16%   |
| Sceptre Tech            | 1         | 0.16%   |
| ONN                     | 1         | 0.16%   |
| MSI                     | 1         | 0.16%   |
| LG Electronics          | 1         | 0.16%   |
| KDC                     | 1         | 0.16%   |
| JXC                     | 1         | 0.16%   |
| Hitachi                 | 1         | 0.16%   |
| Gigabyte Technology     | 1         | 0.16%   |
| Eizo                    | 1         | 0.16%   |
| BenQ                    | 1         | 0.16%   |
| Unknown                 | 1         | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 7         | 1.07%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 6         | 0.92%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 6         | 0.92%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 6         | 0.92%   |
| BOE LCD Monitor BOE08DF 1920x1080 344x194mm 15.5-inch                 | 5         | 0.77%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 5         | 0.77%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                  | 5         | 0.77%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch  | 4         | 0.61%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 4         | 0.61%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 4         | 0.61%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 4         | 0.61%   |
| Chimei Innolux LCD Monitor CMN1408 1920x1080 309x173mm 13.9-inch      | 4         | 0.61%   |
| AU Optronics LCD Monitor AUO978F 1920x1080 382x215mm 17.3-inch        | 4         | 0.61%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch        | 4         | 0.61%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch         | 4         | 0.61%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 3         | 0.46%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 3         | 0.46%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 3         | 0.46%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 3         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 3         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 3         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch       | 3         | 0.46%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 3         | 0.46%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 3         | 0.46%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                 | 3         | 0.46%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 3         | 0.46%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                  | 3         | 0.46%   |
| AU Optronics LCD Monitor AUO82ED 1920x1080 344x193mm 15.5-inch        | 3         | 0.46%   |
| AU Optronics LCD Monitor AUO80ED 1920x1080 340x190mm 15.3-inch        | 3         | 0.46%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch         | 3         | 0.46%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch        | 3         | 0.46%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch         | 3         | 0.46%   |
| AU Optronics LCD Monitor AUO312C 1366x768 293x164mm 13.2-inch         | 3         | 0.46%   |
| TMX TL156MDMP11-0 TMX1560 3200x2000 336x210mm 15.6-inch               | 2         | 0.31%   |
| Sharp LCD Monitor SHP1547 1920x1200 288x180mm 13.4-inch               | 2         | 0.31%   |
| Sharp LCD Monitor SHP1516 3840x2400 336x210mm 15.6-inch               | 2         | 0.31%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 2         | 0.31%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 2         | 0.31%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch               | 2         | 0.31%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch | 2         | 0.31%   |
| Samsung Electronics LCD Monitor SDC834D 1920x1080 293x165mm 13.2-inch | 2         | 0.31%   |
| Samsung Electronics LCD Monitor SDC4154 2880x1800 302x189mm 14.0-inch | 2         | 0.31%   |
| Samsung Electronics LCD Monitor SDC414D 3456x2160 336x210mm 15.6-inch | 2         | 0.31%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch | 2         | 0.31%   |
| PANDA LCD Monitor NCP002B 1920x1080 309x174mm 14.0-inch               | 2         | 0.31%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch          | 2         | 0.31%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 2         | 0.31%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 2         | 0.31%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch           | 2         | 0.31%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch           | 2         | 0.31%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 2         | 0.31%   |
| LG Display LCD Monitor LGD0365 1600x900 382x215mm 17.3-inch           | 2         | 0.31%   |
| LG Display LCD Monitor LGD02D9 1920x1080 344x194mm 15.5-inch          | 2         | 0.31%   |
| JDI LCD Monitor JDI422A 3000x2000 293x196mm 13.9-inch                 | 2         | 0.31%   |
| InfoVision LCD Monitor IVO8C78 1920x1080 309x174mm 14.0-inch          | 2         | 0.31%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 2         | 0.31%   |
| Dell P2317H DEL40F4 1920x1080 509x286mm 23.0-inch                     | 2         | 0.31%   |
| CSO LCD Monitor CSO1615 2560x1600 344x215mm 16.0-inch                 | 2         | 0.31%   |
| Chimei Innolux LCD Monitor CMN15E5 1920x1080 344x193mm 15.5-inch      | 2         | 0.31%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 2         | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 283       | 46.02%  |
| 1366x768 (WXGA)    | 147       | 23.9%   |
| 1600x900 (HD+)     | 31        | 5.04%   |
| 2560x1440 (QHD)    | 23        | 3.74%   |
| 3840x2160 (4K)     | 21        | 3.41%   |
| 2560x1600          | 20        | 3.25%   |
| 1920x1200 (WUXGA)  | 17        | 2.76%   |
| 1440x900 (WXGA+)   | 14        | 2.28%   |
| 1280x800 (WXGA)    | 11        | 1.79%   |
| 2880x1800          | 10        | 1.63%   |
| 3440x1440          | 7         | 1.14%   |
| 3840x2400          | 4         | 0.65%   |
| 2560x1080          | 4         | 0.65%   |
| 3456x2160          | 2         | 0.33%   |
| 3200x2000          | 2         | 0.33%   |
| 3000x2000          | 2         | 0.33%   |
| 2256x1504          | 2         | 0.33%   |
| 1920x540           | 2         | 0.33%   |
| 1280x1024 (SXGA)   | 2         | 0.33%   |
| 3840x1200          | 1         | 0.16%   |
| 3840x1100          | 1         | 0.16%   |
| 3840x1080          | 1         | 0.16%   |
| 3200x1800 (QHD+)   | 1         | 0.16%   |
| 2160x1440          | 1         | 0.16%   |
| 1920x1280          | 1         | 0.16%   |
| 1680x1050 (WSXGA+) | 1         | 0.16%   |
| 1360x768           | 1         | 0.16%   |
| 1280x720 (HD)      | 1         | 0.16%   |
| 1280x1080          | 1         | 0.16%   |
| Unknown            | 1         | 0.16%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 262       | 40.75%  |
| 13      | 119       | 18.51%  |
| 14      | 68        | 10.58%  |
| 17      | 49        | 7.62%   |
| 27      | 20        | 3.11%   |
| 24      | 16        | 2.49%   |
| 12      | 16        | 2.49%   |
| 16      | 15        | 2.33%   |
| 23      | 12        | 1.87%   |
| 31      | 10        | 1.56%   |
| 34      | 8         | 1.24%   |
| 21      | 8         | 1.24%   |
| 11      | 8         | 1.24%   |
| 32      | 4         | 0.62%   |
| 20      | 3         | 0.47%   |
| 19      | 3         | 0.47%   |
| 18      | 3         | 0.47%   |
| Unknown | 3         | 0.47%   |
| 84      | 2         | 0.31%   |
| 54      | 2         | 0.31%   |
| 35      | 2         | 0.31%   |
| 28      | 2         | 0.31%   |
| 22      | 2         | 0.31%   |
| 72      | 1         | 0.16%   |
| 49      | 1         | 0.16%   |
| 48      | 1         | 0.16%   |
| 43      | 1         | 0.16%   |
| 37      | 1         | 0.16%   |
| 29      | 1         | 0.16%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 397       | 61.93%  |
| 201-300     | 84        | 13.1%   |
| 351-400     | 56        | 8.74%   |
| 501-600     | 44        | 6.86%   |
| 601-700     | 17        | 2.65%   |
| 401-500     | 17        | 2.65%   |
| 701-800     | 12        | 1.87%   |
| 1001-1500   | 5         | 0.78%   |
| 801-900     | 3         | 0.47%   |
| 1501-2000   | 3         | 0.47%   |
| Unknown     | 3         | 0.47%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 468       | 81.25%  |
| 16/10   | 84        | 14.58%  |
| 21/9    | 11        | 1.91%   |
| 3/2     | 7         | 1.22%   |
| 5/4     | 2         | 0.35%   |
| 32/9    | 1         | 0.17%   |
| 3.40    | 1         | 0.17%   |
| 3.20    | 1         | 0.17%   |
| Unknown | 1         | 0.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 263       | 40.97%  |
| 81-90          | 144       | 22.43%  |
| 121-130        | 48        | 7.48%   |
| 71-80          | 42        | 6.54%   |
| 201-250        | 29        | 4.52%   |
| 351-500        | 25        | 3.89%   |
| 301-350        | 20        | 3.12%   |
| 61-70          | 15        | 2.34%   |
| 111-120        | 13        | 2.02%   |
| 151-200        | 10        | 1.56%   |
| 51-60          | 9         | 1.4%    |
| 251-300        | 7         | 1.09%   |
| More than 1000 | 6         | 0.93%   |
| 141-150        | 3         | 0.47%   |
| 501-1000       | 3         | 0.47%   |
| Unknown        | 3         | 0.47%   |
| 131-140        | 1         | 0.16%   |
| 91-100         | 1         | 0.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 289       | 45.3%   |
| 101-120       | 175       | 27.43%  |
| 51-100        | 78        | 12.23%  |
| 161-240       | 62        | 9.72%   |
| More than 240 | 26        | 4.08%   |
| 1-50          | 5         | 0.78%   |
| Unknown       | 3         | 0.47%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 441       | 79.75%  |
| 2     | 89        | 16.09%  |
| 3     | 13        | 2.35%   |
| 0     | 10        | 1.81%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 307       | 34.61%  |
| Intel                                 | 269       | 30.33%  |
| Qualcomm Atheros                      | 128       | 14.43%  |
| Broadcom                              | 56        | 6.31%   |
| MediaTek                              | 30        | 3.38%   |
| Broadcom Limited                      | 24        | 2.71%   |
| TP-Link                               | 9         | 1.01%   |
| Samsung Electronics                   | 8         | 0.9%    |
| ASIX Electronics                      | 7         | 0.79%   |
| Ralink                                | 5         | 0.56%   |
| Nvidia                                | 5         | 0.56%   |
| Marvell Technology Group              | 5         | 0.56%   |
| Dell                                  | 5         | 0.56%   |
| NetGear                               | 3         | 0.34%   |
| DisplayLink                           | 3         | 0.34%   |
| Ralink Technology                     | 2         | 0.23%   |
| OPPO Electronics                      | 2         | 0.23%   |
| Hewlett-Packard                       | 2         | 0.23%   |
| ASUSTek Computer                      | 2         | 0.23%   |
| Apple                                 | 2         | 0.23%   |
| Xiaomi                                | 1         | 0.11%   |
| U-Blox                                | 1         | 0.11%   |
| Sierra Wireless                       | 1         | 0.11%   |
| Realtek                               | 1         | 0.11%   |
| Qualcomm                              | 1         | 0.11%   |
| OnePlus Technology (Shenzhen)         | 1         | 0.11%   |
| Motorola PCS                          | 1         | 0.11%   |
| Lenovo                                | 1         | 0.11%   |
| JMicron Technology                    | 1         | 0.11%   |
| Huawei Technologies                   | 1         | 0.11%   |
| Fibocom                               | 1         | 0.11%   |
| Ericsson Business Mobile Networks     | 1         | 0.11%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 202       | 19.4%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 37        | 3.55%   |
| Intel Wi-Fi 6 AX200                                               | 33        | 3.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 26        | 2.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 25        | 2.4%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 22        | 2.11%   |
| Intel Wireless 8265 / 8275                                        | 20        | 1.92%   |
| Intel Wi-Fi 6 AX201                                               | 20        | 1.92%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 20        | 1.92%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 19        | 1.83%   |
| Intel Wireless 7260                                               | 19        | 1.83%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 18        | 1.73%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 18        | 1.73%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 16        | 1.54%   |
| Intel Wireless 7265                                               | 16        | 1.54%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 16        | 1.54%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 15        | 1.44%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 13        | 1.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 12        | 1.15%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 12        | 1.15%   |
| Intel Wireless 8260                                               | 12        | 1.15%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 11        | 1.06%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 11        | 1.06%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 10        | 0.96%   |
| Broadcom BCM43142 802.11b/g/n                                     | 10        | 0.96%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 9         | 0.86%   |
| Intel Ethernet Connection I217-LM                                 | 9         | 0.86%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 8         | 0.77%   |
| Intel Ethernet Connection I219-LM                                 | 8         | 0.77%   |
| Intel Centrino Advanced-N 6235                                    | 8         | 0.77%   |
| Realtek RTL8125 2.5GbE Controller                                 | 7         | 0.67%   |
| Realtek Realtek Network controller                                | 7         | 0.67%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 7         | 0.67%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 7         | 0.67%   |
| Intel Wireless-AC 9260                                            | 7         | 0.67%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 7         | 0.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 7         | 0.67%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 7         | 0.67%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 7         | 0.67%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 6         | 0.58%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 6         | 0.58%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 6         | 0.58%   |
| MediaTek WLAN controller                                          | 6         | 0.58%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 6         | 0.58%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 6         | 0.58%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 6         | 0.58%   |
| ASIX AX88179 Gigabit Ethernet                                     | 6         | 0.58%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 5         | 0.48%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 0.48%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 0.48%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 0.48%   |
| Intel Centrino Ultimate-N 6300                                    | 5         | 0.48%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 5         | 0.48%   |
| Realtek 802.11n WLAN Adapter                                      | 4         | 0.38%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 4         | 0.38%   |
| Nvidia MCP79 Ethernet                                             | 4         | 0.38%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 4         | 0.38%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 4         | 0.38%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter        | 4         | 0.38%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 3         | 0.29%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 260       | 44.83%  |
| Qualcomm Atheros                      | 112       | 19.31%  |
| Realtek Semiconductor                 | 80        | 13.79%  |
| Broadcom                              | 47        | 8.1%    |
| MediaTek                              | 29        | 5%      |
| Broadcom Limited                      | 23        | 3.97%   |
| TP-Link                               | 8         | 1.38%   |
| Ralink                                | 5         | 0.86%   |
| Dell                                  | 5         | 0.86%   |
| NetGear                               | 3         | 0.52%   |
| Ralink Technology                     | 2         | 0.34%   |
| Sierra Wireless                       | 1         | 0.17%   |
| Realtek                               | 1         | 0.17%   |
| Qualcomm                              | 1         | 0.17%   |
| Fibocom                               | 1         | 0.17%   |
| ASUSTek Computer                      | 1         | 0.17%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 33        | 5.62%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 26        | 4.43%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 22        | 3.75%   |
| Intel Wireless 8265 / 8275                                     | 20        | 3.41%   |
| Intel Wi-Fi 6 AX201                                            | 20        | 3.41%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 20        | 3.41%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 19        | 3.24%   |
| Intel Wireless 7260                                            | 19        | 3.24%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 18        | 3.07%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 18        | 3.07%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 16        | 2.73%   |
| Intel Wireless 7265                                            | 16        | 2.73%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 15        | 2.56%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 13        | 2.21%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 12        | 2.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 12        | 2.04%   |
| Intel Wireless 8260                                            | 12        | 2.04%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 11        | 1.87%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 11        | 1.87%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 10        | 1.7%    |
| Broadcom BCM43142 802.11b/g/n                                  | 10        | 1.7%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 9         | 1.53%   |
| Intel Centrino Advanced-N 6235                                 | 8         | 1.36%   |
| Realtek Realtek Network controller                             | 7         | 1.19%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 7         | 1.19%   |
| Intel Wireless-AC 9260                                         | 7         | 1.19%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 7         | 1.19%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 7         | 1.19%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 7         | 1.19%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 7         | 1.19%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 6         | 1.02%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 6         | 1.02%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 6         | 1.02%   |
| MediaTek WLAN controller                                       | 6         | 1.02%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 6         | 1.02%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 6         | 1.02%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 6         | 1.02%   |
| Intel Centrino Ultimate-N 6300                                 | 5         | 0.85%   |
| Realtek 802.11n WLAN Adapter                                   | 4         | 0.68%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 4         | 0.68%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter     | 4         | 0.68%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 3         | 0.51%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 3         | 0.51%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 3         | 0.51%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 3         | 0.51%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 3         | 0.51%   |
| Dell Hub of E-Port Replicator                                  | 3         | 0.51%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 3         | 0.51%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 3         | 0.51%   |
| TP-Link TL-WN722N v2                                           | 2         | 0.34%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 2         | 0.34%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 0.34%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter            | 2         | 0.34%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 2         | 0.34%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 2         | 0.34%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 2         | 0.34%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 2         | 0.34%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 0.34%   |
| Realtek 802.11ac NIC                                           | 2         | 0.34%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 2         | 0.34%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 273       | 61.63%  |
| Intel                         | 77        | 17.38%  |
| Qualcomm Atheros              | 30        | 6.77%   |
| Broadcom                      | 21        | 4.74%   |
| Samsung Electronics           | 8         | 1.81%   |
| ASIX Electronics              | 7         | 1.58%   |
| Nvidia                        | 5         | 1.13%   |
| Marvell Technology Group      | 5         | 1.13%   |
| DisplayLink                   | 3         | 0.68%   |
| OPPO Electronics              | 2         | 0.45%   |
| Apple                         | 2         | 0.45%   |
| Xiaomi                        | 1         | 0.23%   |
| TP-Link                       | 1         | 0.23%   |
| OnePlus Technology (Shenzhen) | 1         | 0.23%   |
| Motorola PCS                  | 1         | 0.23%   |
| Lenovo                        | 1         | 0.23%   |
| JMicron Technology            | 1         | 0.23%   |
| Huawei Technologies           | 1         | 0.23%   |
| Hewlett-Packard               | 1         | 0.23%   |
| Broadcom Limited              | 1         | 0.23%   |
| ASUSTek Computer              | 1         | 0.23%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 202       | 45.09%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 37        | 8.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 25        | 5.58%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 16        | 3.57%   |
| Intel Ethernet Connection I217-LM                                 | 9         | 2.01%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 8         | 1.79%   |
| Intel Ethernet Connection I219-LM                                 | 8         | 1.79%   |
| Realtek RTL8125 2.5GbE Controller                                 | 7         | 1.56%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 7         | 1.56%   |
| ASIX AX88179 Gigabit Ethernet                                     | 6         | 1.34%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 5         | 1.12%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 1.12%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 1.12%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 1.12%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 5         | 1.12%   |
| Nvidia MCP79 Ethernet                                             | 4         | 0.89%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 4         | 0.89%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 4         | 0.89%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 0.67%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 0.67%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.67%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 0.67%   |
| Intel Ethernet Controller I225-V                                  | 3         | 0.67%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.67%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3         | 0.67%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.45%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 2         | 0.45%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.45%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.45%   |
| OPPO 9R                                                           | 2         | 0.45%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 0.45%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 0.45%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.45%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.45%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 0.45%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 0.45%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.45%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 0.45%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.45%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 0.45%   |
| DisplayLink Dell Universal Dock D6000                             | 2         | 0.45%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 2         | 0.45%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 0.45%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.22%   |
| TP-Link USB 10/100 LAN                                            | 1         | 0.22%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.22%   |
| Realtek Realtek Ethernet controller                               | 1         | 0.22%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.22%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.22%   |
| OnePlus (Shenzhen) OnePlus                                        | 1         | 0.22%   |
| Nvidia MCP67 Ethernet                                             | 1         | 0.22%   |
| Motorola PCS Moto E (4) Plus                                      | 1         | 0.22%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.22%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 0.22%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.22%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.22%   |
| Intel Ethernet controller                                         | 1         | 0.22%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.22%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 0.22%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 0.22%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 549       | 56.19%  |
| Ethernet | 422       | 43.19%  |
| Modem    | 4         | 0.41%   |
| Unknown  | 2         | 0.2%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 453       | 79.06%  |
| Ethernet | 120       | 20.94%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 388       | 70.67%  |
| 1     | 155       | 28.23%  |
| 0     | 4         | 0.73%   |
| 3     | 2         | 0.36%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 385       | 69.75%  |
| Yes  | 167       | 30.25%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 226       | 48.19%  |
| Qualcomm Atheros Communications | 50        | 10.66%  |
| Realtek Semiconductor           | 37        | 7.89%   |
| IMC Networks                    | 36        | 7.68%   |
| Apple                           | 36        | 7.68%   |
| Lite-On Technology              | 22        | 4.69%   |
| Broadcom                        | 20        | 4.26%   |
| Foxconn / Hon Hai               | 18        | 3.84%   |
| Toshiba                         | 4         | 0.85%   |
| Dell                            | 4         | 0.85%   |
| Realtek                         | 3         | 0.64%   |
| Hewlett-Packard                 | 3         | 0.64%   |
| Ralink                          | 2         | 0.43%   |
| Opticis                         | 2         | 0.43%   |
| Cambridge Silicon Radio         | 2         | 0.43%   |
| USI                             | 1         | 0.21%   |
| Ralink Technology               | 1         | 0.21%   |
| Foxconn International           | 1         | 0.21%   |
| ASUSTek Computer                | 1         | 0.21%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 68        | 14.5%   |
| Intel AX201 Bluetooth                               | 61        | 13.01%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 32        | 6.82%   |
| Intel AX200 Bluetooth                               | 31        | 6.61%   |
| Realtek Bluetooth Radio                             | 28        | 5.97%   |
| Qualcomm Atheros  Bluetooth Device                  | 27        | 5.76%   |
| Apple Bluetooth USB Host Controller                 | 16        | 3.41%   |
| Apple Bluetooth Host Controller                     | 16        | 3.41%   |
| IMC Networks Wireless_Device                        | 15        | 3.2%    |
| IMC Networks Bluetooth Device                       | 11        | 2.35%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 9         | 1.92%   |
| Intel Bluetooth Device                              | 9         | 1.92%   |
| Realtek  Bluetooth 4.2 Adapter                      | 8         | 1.71%   |
| Foxconn / Hon Hai Wireless_Device                   | 8         | 1.71%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 7         | 1.49%   |
| Intel AX210 Bluetooth                               | 7         | 1.49%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 6         | 1.28%   |
| Foxconn / Hon Hai Bluetooth Device                  | 6         | 1.28%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 5         | 1.07%   |
| Lite-On Wireless_Device                             | 5         | 1.07%   |
| Lite-On Bluetooth Device                            | 5         | 1.07%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 5         | 1.07%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 4         | 0.85%   |
| Lite-On Atheros AR3012 Bluetooth                    | 4         | 0.85%   |
| Realtek Bluetooth Radio                             | 3         | 0.64%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 0.64%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 3         | 0.64%   |
| IMC Networks Bluetooth Radio                        | 3         | 0.64%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 3         | 0.64%   |
| Broadcom BCM20702A0                                 | 3         | 0.64%   |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 0.64%   |
| Ralink RT3290 Bluetooth                             | 2         | 0.43%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 2         | 0.43%   |
| Opticis Bluetooth Radio                             | 2         | 0.43%   |
| Lite-On Qualcomm Atheros Bluetooth                  | 2         | 0.43%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 2         | 0.43%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 0.43%   |
| IMC Networks Bluetooth USB Host Controller          | 2         | 0.43%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 0.43%   |
| Dell DW375 Bluetooth Module                         | 2         | 0.43%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 0.43%   |
| Broadcom HP Portable Bumble Bee                     | 2         | 0.43%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 2         | 0.43%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2         | 0.43%   |
| Broadcom BCM20702A0 Bluetooth                       | 2         | 0.43%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 0.43%   |
| Apple Bluetooth HCI                                 | 2         | 0.43%   |
| USI Bluetooth Device                                | 1         | 0.21%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.21%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.21%   |
| Toshiba Bluetooth Radio                             | 1         | 0.21%   |
| Toshiba BCM43142A0                                  | 1         | 0.21%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.21%   |
| Ralink CSR BS8510                                   | 1         | 0.21%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.21%   |
| Lite-On Bluetooth Radio                             | 1         | 0.21%   |
| Lite-On BCM43142A0                                  | 1         | 0.21%   |
| Lite-On Atheros Bluetooth                           | 1         | 0.21%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.21%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.21%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 409       | 57.04%  |
| AMD                                  | 138       | 19.25%  |
| Nvidia                               | 123       | 17.15%  |
| C-Media Electronics                  | 5         | 0.7%    |
| GN Netcom                            | 4         | 0.56%   |
| Apple                                | 4         | 0.56%   |
| Texas Instruments                    | 3         | 0.42%   |
| Sony                                 | 3         | 0.42%   |
| Lenovo                               | 3         | 0.42%   |
| SteelSeries ApS                      | 2         | 0.28%   |
| Sennheiser Communications            | 2         | 0.28%   |
| Logitech                             | 2         | 0.28%   |
| Kingston Technology                  | 2         | 0.28%   |
| Hewlett-Packard                      | 2         | 0.28%   |
| Focusrite-Novation                   | 2         | 0.28%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.14%   |
| TerraTec Electronic                  | 1         | 0.14%   |
| Realtek Semiconductor                | 1         | 0.14%   |
| Razer USA                            | 1         | 0.14%   |
| Plantronics                          | 1         | 0.14%   |
| No brand                             | 1         | 0.14%   |
| Midiplus                             | 1         | 0.14%   |
| JMTek                                | 1         | 0.14%   |
| iConnectivity                        | 1         | 0.14%   |
| Generalplus Technology               | 1         | 0.14%   |
| Audio-Technica                       | 1         | 0.14%   |
| Astro Gaming                         | 1         | 0.14%   |
| Antlion Audio                        | 1         | 0.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 98        | 10.94%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 52        | 5.8%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 50        | 5.58%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 39        | 4.35%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 30        | 3.35%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 28        | 3.13%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 28        | 3.13%   |
| Intel 8 Series HD Audio Controller                                                                | 27        | 3.01%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 25        | 2.79%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 24        | 2.68%   |
| Intel Broadwell-U Audio Controller                                                                | 24        | 2.68%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 23        | 2.57%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 22        | 2.46%   |
| Intel Comet Lake PCH cAVS                                                                         | 21        | 2.34%   |
| Intel Cannon Lake PCH cAVS                                                                        | 20        | 2.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 18        | 2.01%   |
| AMD FCH Azalia Controller                                                                         | 18        | 2.01%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 17        | 1.9%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 16        | 1.79%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 15        | 1.67%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 14        | 1.56%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 14        | 1.56%   |
| Intel CM238 HD Audio Controller                                                                   | 13        | 1.45%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 12        | 1.34%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 12        | 1.34%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 12        | 1.34%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 11        | 1.23%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 10        | 1.12%   |
| AMD Kabini HDMI/DP Audio                                                                          | 10        | 1.12%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 8         | 0.89%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 8         | 0.89%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 7         | 0.78%   |
| Nvidia Audio device                                                                               | 7         | 0.78%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 7         | 0.78%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 6         | 0.67%   |
| Nvidia MCP79 High Definition Audio                                                                | 6         | 0.67%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 6         | 0.67%   |
| Nvidia TU104 HD Audio Controller                                                                  | 5         | 0.56%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 5         | 0.56%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 0.56%   |
| AMD Trinity HDMI Audio Controller                                                                 | 5         | 0.56%   |
| Nvidia MCP89 High Definition Audio                                                                | 4         | 0.45%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 4         | 0.45%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 4         | 0.45%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 0.45%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 4         | 0.45%   |
| Apple Audio Device                                                                                | 4         | 0.45%   |
| AMD High Definition Audio Controller                                                              | 4         | 0.45%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 4         | 0.45%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 0.33%   |
| Intel Audio device                                                                                | 3         | 0.33%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 0.33%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 2         | 0.22%   |
| Sony DualSense wireless controller (PS5)                                                          | 2         | 0.22%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 0.22%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 2         | 0.22%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 2         | 0.22%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 2         | 0.22%   |
| Intel Crystal Well HD Audio Controller                                                            | 2         | 0.22%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.22%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 56        | 32%     |
| SK hynix            | 41        | 23.43%  |
| Micron Technology   | 27        | 15.43%  |
| Kingston            | 8         | 4.57%   |
| Crucial             | 6         | 3.43%   |
| Smart               | 5         | 2.86%   |
| Unknown             | 4         | 2.29%   |
| Unknown             | 4         | 2.29%   |
| Neo Forza           | 3         | 1.71%   |
| Ramaxel Technology  | 2         | 1.14%   |
| PNY                 | 2         | 1.14%   |
| GSkill              | 2         | 1.14%   |
| Avant               | 2         | 1.14%   |
| A-DATA Technology   | 2         | 1.14%   |
| Unknown (ABCD)      | 1         | 0.57%   |
| Unknown (8A02)      | 1         | 0.57%   |
| Timetec             | 1         | 0.57%   |
| Teikon              | 1         | 0.57%   |
| Smart Brazil        | 1         | 0.57%   |
| Nanya Technology    | 1         | 0.57%   |
| Goldkey             | 1         | 0.57%   |
| Gold Key            | 1         | 0.57%   |
| G.Skill             | 1         | 0.57%   |
| Elpida              | 1         | 0.57%   |
| Corsair             | 1         | 0.57%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 6         | 3.26%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 5         | 2.72%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 5         | 2.72%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 4         | 2.17%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s              | 4         | 2.17%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s              | 4         | 2.17%   |
| Unknown                                                             | 4         | 2.17%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 3         | 1.63%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 3         | 1.63%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 3         | 1.63%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 3         | 1.63%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                | 3         | 1.63%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s                 | 2         | 1.09%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 1.09%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 2         | 1.09%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s    | 2         | 1.09%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 1.09%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s         | 2         | 1.09%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 2         | 1.09%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 2         | 1.09%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 2         | 1.09%   |
| Samsung RAM M471A2G43AB2-CWE 16384MB SODIMM DDR4 3200MT/s           | 2         | 1.09%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 1.09%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 2         | 1.09%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2400MT/s               | 2         | 1.09%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM 4800MT/s                  | 2         | 1.09%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s        | 2         | 1.09%   |
| Neo Forza RAM NMSO416E82-3200E 16GB SODIMM DDR4 3200MT/s            | 2         | 1.09%   |
| Micron RAM MT62F1G32D4DR-031 WT 4GB Row Of Chips 6400MT/s           | 2         | 1.09%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 2         | 1.09%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s                 | 1         | 0.54%   |
| Unknown RAM Module 16GB Row Of Chips LPDDR4 4267MT/s                | 1         | 0.54%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 1         | 0.54%   |
| Unknown (8A02) RAM 8G2400MHz 8GB SODIMM DDR4 2667MT/s               | 1         | 0.54%   |
| Timetec RAM 32NUS2R8-32G 32GB SODIMM DDR4 3200MT/s                  | 1         | 0.54%   |
| Teikon RAM TMT251S6CFR8C-PBHC 4GB SODIMM DDR3 1600MT/s              | 1         | 0.54%   |
| Smart RAM SMS4WEC8C1K0446FCG 8GB SODIMM DDR4 3200MT/s               | 1         | 0.54%   |
| Smart RAM SH5641G8FJ8NWRNSQG 8GB SODIMM DDR3 1600MT/s               | 1         | 0.54%   |
| Smart RAM SG564568FG8NWKFSQR 2GB SODIMM DDR2 800MT/s                | 1         | 0.54%   |
| Smart RAM SG564568FG8NWKF-Z1 2GB SODIMM DDR2 800MT/s                | 1         | 0.54%   |
| Smart RAM SF4641G8CKHIWDFSEG 8GB SODIMM DDR4 2133MT/s               | 1         | 0.54%   |
| Smart Brazil RAM SMS4WEC3C0K0446SCG 4GB SODIMM DDR4 3200MT/s        | 1         | 0.54%   |
| Smart Brazil RAM Module 4GB Row Of Chips DDR4 3200MT/s              | 1         | 0.54%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                        | 1         | 0.54%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                        | 1         | 0.54%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                       | 1         | 0.54%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 0.54%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 0.54%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.54%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 1         | 0.54%   |
| SK hynix RAM HMCG88MEBSA092N 32GB SODIMM 4800MT/s                   | 1         | 0.54%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM 4800MT/s                   | 1         | 0.54%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s             | 1         | 0.54%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s        | 1         | 0.54%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB Row Of Chips DDR4 3200MT/s     | 1         | 0.54%   |
| SK hynix RAM HMA851S6JJR6N-VK 4096MB SODIMM DDR4 2667MT/s           | 1         | 0.54%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 1         | 0.54%   |
| SK hynix RAM HMA851S6CJR6N-VK 4096MB Row Of Chips DDR4 2667MT/s     | 1         | 0.54%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s              | 1         | 0.54%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s              | 1         | 0.54%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 95        | 62.5%   |
| DDR3    | 22        | 14.47%  |
| LPDDR4  | 12        | 7.89%   |
| LPDDR3  | 6         | 3.95%   |
| Unknown | 6         | 3.95%   |
| LPDDR5  | 4         | 2.63%   |
| SDRAM   | 3         | 1.97%   |
| DDR5    | 2         | 1.32%   |
| DDR2    | 2         | 1.32%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 123       | 79.87%  |
| Row Of Chips | 30        | 19.48%  |
| Chip         | 1         | 0.65%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 78        | 48.75%  |
| 4096  | 40        | 25%     |
| 16384 | 22        | 13.75%  |
| 32768 | 10        | 6.25%   |
| 2048  | 10        | 6.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 56        | 34.78%  |
| 2667  | 31        | 19.25%  |
| 1600  | 16        | 9.94%   |
| 2400  | 9         | 5.59%   |
| 2133  | 9         | 5.59%   |
| 4800  | 6         | 3.73%   |
| 4267  | 6         | 3.73%   |
| 6400  | 5         | 3.11%   |
| 8400  | 4         | 2.48%   |
| 1867  | 3         | 1.86%   |
| 1333  | 3         | 1.86%   |
| 4266  | 2         | 1.24%   |
| 3733  | 2         | 1.24%   |
| 3266  | 2         | 1.24%   |
| 2048  | 2         | 1.24%   |
| 1334  | 2         | 1.24%   |
| 800   | 2         | 1.24%   |
| 4199  | 1         | 0.62%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Notebooks | Percent |
|---------------------------------|-----------|---------|
| HP Ink Tank Wireless 410 series | 1         | 100%    |

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
| Chicony Electronics                    | 117       | 23.54%  |
| Acer                                   | 63        | 12.68%  |
| Microdia                               | 53        | 10.66%  |
| IMC Networks                           | 49        | 9.86%   |
| Realtek Semiconductor                  | 44        | 8.85%   |
| Sunplus Innovation Technology          | 25        | 5.03%   |
| Quanta                                 | 24        | 4.83%   |
| Apple                                  | 22        | 4.43%   |
| Suyin                                  | 15        | 3.02%   |
| Cheng Uei Precision Industry (Foxlink) | 15        | 3.02%   |
| Syntek                                 | 12        | 2.41%   |
| Lite-On Technology                     | 8         | 1.61%   |
| SunplusIT                              | 6         | 1.21%   |
| Silicon Motion                         | 6         | 1.21%   |
| Luxvisions Innotech Limited            | 6         | 1.21%   |
| Logitech                               | 5         | 1.01%   |
| Samsung Electronics                    | 4         | 0.8%    |
| Sonix Technology                       | 3         | 0.6%    |
| Microsoft                              | 3         | 0.6%    |
| Alcor Micro                            | 3         | 0.6%    |
| Z-Star Microelectronics                | 2         | 0.4%    |
| Razer USA                              | 2         | 0.4%    |
| Primax Electronics                     | 2         | 0.4%    |
| Generalplus Technology                 | 2         | 0.4%    |
| SJ-180517-N                            | 1         | 0.2%    |
| Ricoh                                  | 1         | 0.2%    |
| Oculus VR                              | 1         | 0.2%    |
| LG Electronics                         | 1         | 0.2%    |
| KYE Systems (Mouse Systems)            | 1         | 0.2%    |
| Importek                               | 1         | 0.2%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                       | 26        | 5.21%   |
| Chicony Integrated Camera                           | 24        | 4.81%   |
| Realtek Integrated_Webcam_HD                        | 20        | 4.01%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 16        | 3.21%   |
| Acer Integrated Camera                              | 14        | 2.81%   |
| Chicony HD WebCam                                   | 13        | 2.61%   |
| IMC Networks Integrated Camera                      | 12        | 2.4%    |
| Acer BisonCam,NB Pro                                | 12        | 2.4%    |
| Syntek Integrated Camera                            | 11        | 2.2%    |
| Acer HD Webcam                                      | 11        | 2.2%    |
| Chicony USB2.0 VGA UVC WebCam                       | 8         | 1.6%    |
| Quanta HD User Facing                               | 7         | 1.4%    |
| Microdia Integrated Webcam                          | 7         | 1.4%    |
| Sunplus Integrated_Webcam_HD                        | 6         | 1.2%    |
| Quanta HP HD Camera                                 | 6         | 1.2%    |
| Chicony TOSHIBA Web Camera - HD                     | 6         | 1.2%    |
| Apple iPhone 5/5C/5S/6/SE                           | 6         | 1.2%    |
| Apple FaceTime HD Camera                            | 6         | 1.2%    |
| Apple Built-in iSight                               | 6         | 1.2%    |
| Chicony USB2.0 Camera                               | 5         | 1%      |
| Chicony HD User Facing                              | 5         | 1%      |
| Suyin HP Truevision HD                              | 4         | 0.8%    |
| Suyin 1.3M HD WebCam                                | 4         | 0.8%    |
| Samsung Galaxy series, misc. (MTP mode)             | 4         | 0.8%    |
| IMC Networks USB2.0 UVC HD Webcam                   | 4         | 0.8%    |
| Chicony USB 2.0 Camera                              | 4         | 0.8%    |
| Chicony Integrated Camera (1280x720@30)             | 4         | 0.8%    |
| Sunplus HD WebCam                                   | 3         | 0.6%    |
| Sonix USB2.0 HD UVC WebCam                          | 3         | 0.6%    |
| Realtek USB2.0 HD UVC WebCam                        | 3         | 0.6%    |
| Realtek USB Camera                                  | 3         | 0.6%    |
| Quanta HD Webcam                                    | 3         | 0.6%    |
| Microdia USB 2.0 Camera                             | 3         | 0.6%    |
| Microdia Laptop_Integrated_Webcam_HD                | 3         | 0.6%    |
| Lite-On Integrated Camera                           | 3         | 0.6%    |
| IMC Networks USB2.0 VGA UVC WebCam                  | 3         | 0.6%    |
| Chicony USB2.0 HD UVC WebCam                        | 3         | 0.6%    |
| Chicony ThinkPad T490 Webcam                        | 3         | 0.6%    |
| Chicony Lenovo Integrated Camera (0.3MP)            | 3         | 0.6%    |
| Chicony HP Wide Vision HD Camera                    | 3         | 0.6%    |
| Chicony HP TrueVision HD Camera                     | 3         | 0.6%    |
| Chicony HP HD Webcam                                | 3         | 0.6%    |
| Chicony HP HD Camera                                | 3         | 0.6%    |
| Chicony EasyCamera                                  | 3         | 0.6%    |
| Chicony 2.0M UVC Webcam / CNF7129                   | 3         | 0.6%    |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 3         | 0.6%    |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 3         | 0.6%    |
| Cheng Uei Precision Industry (Foxlink) HD Camera    | 3         | 0.6%    |
| Apple FaceTime HD Camera (Built-in)                 | 3         | 0.6%    |
| Acer USB HD Webcam                                  | 3         | 0.6%    |
| Acer SunplusIT Integrated Camera                    | 3         | 0.6%    |
| Acer SunplusIT INC. Integrated Camera               | 3         | 0.6%    |
| Acer Lenovo EasyCamera                              | 3         | 0.6%    |
| Acer Integrated RGB Camera                          | 3         | 0.6%    |
| Acer EasyCamera                                     | 3         | 0.6%    |
| Suyin Integrated_Webcam_HD                          | 2         | 0.4%    |
| SunplusIT 720p HD Camera                            | 2         | 0.4%    |
| SunplusIT 1080p FHD Camera                          | 2         | 0.4%    |
| Sunplus Laptop_Integrated_Webcam_FHD                | 2         | 0.4%    |
| Sunplus Laptop Integrated Webcam FHD                | 2         | 0.4%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 32        | 36.78%  |
| Validity Sensors           | 21        | 24.14%  |
| Shenzhen Goodix Technology | 20        | 22.99%  |
| LighTuning Technology      | 5         | 5.75%   |
| Upek                       | 3         | 3.45%   |
| HOLTEK                     | 2         | 2.3%    |
| Elan Microelectronics      | 2         | 2.3%    |
| AuthenTec                  | 2         | 2.3%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                       | 12        | 13.79%  |
| Unknown                                                   | 10        | 11.49%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 9         | 10.34%  |
| Validity Sensors VFS495 Fingerprint Reader                | 6         | 6.9%    |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 5         | 5.75%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 4         | 4.6%    |
| Shenzhen Goodix Fingerprint Reader                        | 4         | 4.6%    |
| Shenzhen Goodix FingerPrint                               | 4         | 4.6%    |
| Validity Sensors VFS5011 Fingerprint Reader               | 3         | 3.45%   |
| Validity Sensors VFS 5011 fingerprint sensor              | 3         | 3.45%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor    | 3         | 3.45%   |
| Synaptics WBDI Device                                     | 3         | 3.45%   |
| LighTuning ES603 Swipe Fingerprint Sensor                 | 3         | 3.45%   |
| Validity Sensors VFS491                                   | 2         | 2.3%    |
| Validity Sensors Synaptics WBDI                           | 2         | 2.3%    |
| Validity Sensors Fingerprint scanner                      | 2         | 2.3%    |
| LighTuning EgisTec Touch Fingerprint Sensor               | 2         | 2.3%    |
| HOLTEK FocalTech Fingerprint Device                       | 2         | 2.3%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor         | 1         | 1.15%   |
| Validity Sensors VFS471 Fingerprint Reader                | 1         | 1.15%   |
| Validity Sensors Swipe Fingerprint Sensor                 | 1         | 1.15%   |
| Synaptics  WBDI                                           | 1         | 1.15%   |
| Elan ELAN:Fingerprint                                     | 1         | 1.15%   |
| Elan ELAN:ARM-M4                                          | 1         | 1.15%   |
| AuthenTec AES2810                                         | 1         | 1.15%   |
| AuthenTec AES2550 Fingerprint Sensor                      | 1         | 1.15%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 18        | 54.55%  |
| Alcor Micro | 9         | 27.27%  |
| O2 Micro    | 3         | 9.09%   |
| Upek        | 2         | 6.06%   |
| Lenovo      | 1         | 3.03%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 9         | 27.27%  |
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 21.21%  |
| Broadcom 5880                                                                | 7         | 21.21%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 9.09%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 6.06%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 6.06%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 3.03%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 3.03%   |
| Broadcom 58200                                                               | 1         | 3.03%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 323       | 58.2%   |
| 1     | 180       | 32.43%  |
| 2     | 42        | 7.57%   |
| 3     | 9         | 1.62%   |
| 4     | 1         | 0.18%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 81        | 28.62%  |
| Multimedia controller    | 50        | 17.67%  |
| Net/wireless             | 40        | 14.13%  |
| Chipcard                 | 32        | 11.31%  |
| Bluetooth                | 27        | 9.54%   |
| Graphics card            | 25        | 8.83%   |
| Sound                    | 5         | 1.77%   |
| Camera                   | 5         | 1.77%   |
| Net/ethernet             | 4         | 1.41%   |
| Storage                  | 3         | 1.06%   |
| Network                  | 3         | 1.06%   |
| Storage/ide              | 2         | 0.71%   |
| Modem                    | 2         | 0.71%   |
| Communication controller | 2         | 0.71%   |
| Card reader              | 2         | 0.71%   |

