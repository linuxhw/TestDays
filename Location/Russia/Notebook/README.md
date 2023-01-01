Linux in Russia - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Russia.

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

Total: 16871

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [322cf5484d](https://linux-hardware.org/?probe=322cf5484d) | Dec 31, 2022 |
| ASUSTek       | X540YA                      | [37ef421251](https://linux-hardware.org/?probe=37ef421251) | Dec 31, 2022 |
| Lenovo        | G780 20138                  | [896aeb4e20](https://linux-hardware.org/?probe=896aeb4e20) | Dec 31, 2022 |
| Dell          | Inspiron 15-3552            | [e8b804ddd5](https://linux-hardware.org/?probe=e8b804ddd5) | Dec 31, 2022 |
| Valve         | Jupiter                     | [61cb7375d1](https://linux-hardware.org/?probe=61cb7375d1) | Dec 31, 2022 |
| Samsung       | 300V3A/300V4A/300V5A        | [14b589709d](https://linux-hardware.org/?probe=14b589709d) | Dec 31, 2022 |
| MACHENIKE     | MACHCREATOR-16              | [f7ed4a6609](https://linux-hardware.org/?probe=f7ed4a6609) | Dec 30, 2022 |
| Timi          | A35S                        | [c62c9ae956](https://linux-hardware.org/?probe=c62c9ae956) | Dec 30, 2022 |
| HP            | Pavilion g6                 | [6f29ccd86e](https://linux-hardware.org/?probe=6f29ccd86e) | Dec 30, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [5b5e0e4535](https://linux-hardware.org/?probe=5b5e0e4535) | Dec 30, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [5710b93654](https://linux-hardware.org/?probe=5710b93654) | Dec 30, 2022 |
| Dell          | Inspiron 5490               | [c8a80649d2](https://linux-hardware.org/?probe=c8a80649d2) | Dec 30, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [2d63537d23](https://linux-hardware.org/?probe=2d63537d23) | Dec 30, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [41da11b027](https://linux-hardware.org/?probe=41da11b027) | Dec 30, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [954fdfcd25](https://linux-hardware.org/?probe=954fdfcd25) | Dec 30, 2022 |
| Unknown       | Unknown                     | [b74128543f](https://linux-hardware.org/?probe=b74128543f) | Dec 29, 2022 |
| HP            | ProBook 430 G8 Notebook ... | [3f4178001d](https://linux-hardware.org/?probe=3f4178001d) | Dec 29, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | [6c836dde26](https://linux-hardware.org/?probe=6c836dde26) | Dec 29, 2022 |
| MACHCREATO... | AB                          | [52a6beb872](https://linux-hardware.org/?probe=52a6beb872) | Dec 29, 2022 |
| Timi          | RedmiBook Pro 15S           | [42640b7b6e](https://linux-hardware.org/?probe=42640b7b6e) | Dec 29, 2022 |
| Timi          | RedmiBook Pro 15S           | [16c240a462](https://linux-hardware.org/?probe=16c240a462) | Dec 29, 2022 |
| Prestigio     | PSB141C04CGH                | [591f91b689](https://linux-hardware.org/?probe=591f91b689) | Dec 29, 2022 |
| MACHENIKE     | MACHCREATOR-16              | [3c627bc707](https://linux-hardware.org/?probe=3c627bc707) | Dec 29, 2022 |
| MACHENIKE     | MACHCREATOR-16              | [b246257695](https://linux-hardware.org/?probe=b246257695) | Dec 29, 2022 |
| HUAWEI        | BOM-WXX9                    | [fb1d454bc2](https://linux-hardware.org/?probe=fb1d454bc2) | Dec 29, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [83acd419e0](https://linux-hardware.org/?probe=83acd419e0) | Dec 29, 2022 |
| HUAWEI        | BOM-WXX9                    | [62010fe267](https://linux-hardware.org/?probe=62010fe267) | Dec 29, 2022 |
| ASUSTek       | N551JM                      | [932615a484](https://linux-hardware.org/?probe=932615a484) | Dec 29, 2022 |
| ASUSTek       | K40IN                       | [1b4a2d0604](https://linux-hardware.org/?probe=1b4a2d0604) | Dec 29, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [a05251fd39](https://linux-hardware.org/?probe=a05251fd39) | Dec 29, 2022 |
| HP            | EliteBook Folio 1040 G3     | [6aad572cd5](https://linux-hardware.org/?probe=6aad572cd5) | Dec 29, 2022 |
| 3Logic Gro... | Graviton N15i-K2            | [fe79eba13b](https://linux-hardware.org/?probe=fe79eba13b) | Dec 29, 2022 |
| Aquarius      | NS685U R11                  | [d99ae12a0c](https://linux-hardware.org/?probe=d99ae12a0c) | Dec 29, 2022 |
| Lenovo        | V560                        | [f937de4c61](https://linux-hardware.org/?probe=f937de4c61) | Dec 28, 2022 |
| Dell          | Inspiron 5490               | [457c2ae4ae](https://linux-hardware.org/?probe=457c2ae4ae) | Dec 28, 2022 |
| Lenovo        | V14-IIL 82C4                | [221e9b9fd6](https://linux-hardware.org/?probe=221e9b9fd6) | Dec 28, 2022 |
| Dell          | Inspiron 5490               | [fdfd0f21c7](https://linux-hardware.org/?probe=fdfd0f21c7) | Dec 28, 2022 |
| Clevo         | NL41MU2                     | [6aaaf2e570](https://linux-hardware.org/?probe=6aaaf2e570) | Dec 28, 2022 |
| Lenovo        | IdeaPad L3 15ITL6 82HL      | [0852995abb](https://linux-hardware.org/?probe=0852995abb) | Dec 28, 2022 |
| DEPO Compu... | DPC156                      | [b49fe3beb3](https://linux-hardware.org/?probe=b49fe3beb3) | Dec 28, 2022 |
| HUAWEI        | HLYL-WXX9                   | [790b3dcdde](https://linux-hardware.org/?probe=790b3dcdde) | Dec 28, 2022 |
| Lenovo        | ThinkPad T430 23448AG       | [00ba06cfd1](https://linux-hardware.org/?probe=00ba06cfd1) | Dec 28, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e36e85614e](https://linux-hardware.org/?probe=e36e85614e) | Dec 28, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [b62b4d2134](https://linux-hardware.org/?probe=b62b4d2134) | Dec 27, 2022 |
| MSI           | GL63 8RC                    | [0b973e252f](https://linux-hardware.org/?probe=0b973e252f) | Dec 27, 2022 |
| Toshiba       | Satellite U300              | [88861461c8](https://linux-hardware.org/?probe=88861461c8) | Dec 27, 2022 |
| Lenovo        | ThinkPad T430 23448AG       | [a570034bbc](https://linux-hardware.org/?probe=a570034bbc) | Dec 27, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [942fbb1ccb](https://linux-hardware.org/?probe=942fbb1ccb) | Dec 27, 2022 |
| HP            | Compaq Presario CQ50        | [802e160a5a](https://linux-hardware.org/?probe=802e160a5a) | Dec 27, 2022 |
| Lenovo        | V14-IIL 82C4                | [2b7f53c989](https://linux-hardware.org/?probe=2b7f53c989) | Dec 27, 2022 |
| HP            | Laptop 15s-eq2xxx           | [155c738d10](https://linux-hardware.org/?probe=155c738d10) | Dec 27, 2022 |
| ASUSTek       | K43E                        | [530e44f9c6](https://linux-hardware.org/?probe=530e44f9c6) | Dec 27, 2022 |
| Unknown       | Unknown                     | [6aa557fb75](https://linux-hardware.org/?probe=6aa557fb75) | Dec 27, 2022 |
| 3Logic Gro... | Graviton N15i-K2            | [4d7e3586e2](https://linux-hardware.org/?probe=4d7e3586e2) | Dec 27, 2022 |
| MACHENIKE     | Machcreator-16              | [682c068af0](https://linux-hardware.org/?probe=682c068af0) | Dec 27, 2022 |
| Clevo         | NL41MU2                     | [0c71831ff4](https://linux-hardware.org/?probe=0c71831ff4) | Dec 27, 2022 |
| Clevo         | NL41MU2                     | [50c31f6b47](https://linux-hardware.org/?probe=50c31f6b47) | Dec 27, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [292ef79b8a](https://linux-hardware.org/?probe=292ef79b8a) | Dec 27, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [cedce58f23](https://linux-hardware.org/?probe=cedce58f23) | Dec 27, 2022 |
| HONOR         | BMH-WCX9                    | [815525e6d2](https://linux-hardware.org/?probe=815525e6d2) | Dec 27, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [0e063e5fd5](https://linux-hardware.org/?probe=0e063e5fd5) | Dec 27, 2022 |
| Gigabyte      | i1520N                      | [4f94938d1b](https://linux-hardware.org/?probe=4f94938d1b) | Dec 27, 2022 |
| MSI           | Modern 14 B4MW              | [17bd139f0c](https://linux-hardware.org/?probe=17bd139f0c) | Dec 26, 2022 |
| Digma         | CITI E401 ET4007EW          | [252a51f201](https://linux-hardware.org/?probe=252a51f201) | Dec 26, 2022 |
| Timi          | A18R                        | [83f858038d](https://linux-hardware.org/?probe=83f858038d) | Dec 26, 2022 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [0a5cad12c2](https://linux-hardware.org/?probe=0a5cad12c2) | Dec 26, 2022 |
| ASUSTek       | N56VZ                       | [1ba62f0fab](https://linux-hardware.org/?probe=1ba62f0fab) | Dec 26, 2022 |
| Dell          | G5 5590                     | [43fbc3b36d](https://linux-hardware.org/?probe=43fbc3b36d) | Dec 26, 2022 |
| Clevo         | NL41MU2                     | [190bb1537d](https://linux-hardware.org/?probe=190bb1537d) | Dec 26, 2022 |
| Clevo         | NL41MU2                     | [0574ad6c44](https://linux-hardware.org/?probe=0574ad6c44) | Dec 26, 2022 |
| HUAWEI        | NBD-WXX9                    | [713b103493](https://linux-hardware.org/?probe=713b103493) | Dec 25, 2022 |
| HP            | 470 G8 Notebook PC          | [6d77c48324](https://linux-hardware.org/?probe=6d77c48324) | Dec 25, 2022 |
| Acer          | Acadia V1.45                | [2d98a8cef2](https://linux-hardware.org/?probe=2d98a8cef2) | Dec 25, 2022 |
| Unknown       | Unknown                     | [8f4d031a78](https://linux-hardware.org/?probe=8f4d031a78) | Dec 25, 2022 |
| LTD Delovo... | 15Y                         | [286aa3fb96](https://linux-hardware.org/?probe=286aa3fb96) | Dec 25, 2022 |
| Pegatron      | C15B                        | [f838b3f22c](https://linux-hardware.org/?probe=f838b3f22c) | Dec 25, 2022 |
| HUAWEI        | HVY-WXX9                    | [649291f277](https://linux-hardware.org/?probe=649291f277) | Dec 25, 2022 |
| Acer          | Nitro AN515-52              | [1571f74238](https://linux-hardware.org/?probe=1571f74238) | Dec 25, 2022 |
| Unknown       | Unknown                     | [1e55cad727](https://linux-hardware.org/?probe=1e55cad727) | Dec 25, 2022 |
| ASUSTek       | X551CAP                     | [3442037418](https://linux-hardware.org/?probe=3442037418) | Dec 25, 2022 |
| ASUSTek       | M51Tr                       | [dffa412a98](https://linux-hardware.org/?probe=dffa412a98) | Dec 25, 2022 |
| Dell          | Inspiron 5490               | [ea09a6daa8](https://linux-hardware.org/?probe=ea09a6daa8) | Dec 25, 2022 |
| Dell          | Inspiron 5490               | [45737153e4](https://linux-hardware.org/?probe=45737153e4) | Dec 25, 2022 |
| HP            | Laptop 15-bw0xx             | [3bf8001e85](https://linux-hardware.org/?probe=3bf8001e85) | Dec 24, 2022 |
| Dell          | G7 7790                     | [da767d5fd4](https://linux-hardware.org/?probe=da767d5fd4) | Dec 24, 2022 |
| HP            | Laptop 15-bw0xx             | [8a5bfa5e66](https://linux-hardware.org/?probe=8a5bfa5e66) | Dec 24, 2022 |
| Acer          | Aspire V3-551G              | [6adf185edf](https://linux-hardware.org/?probe=6adf185edf) | Dec 24, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [8c835888d6](https://linux-hardware.org/?probe=8c835888d6) | Dec 24, 2022 |
| HP            | EliteBook Folio 1040 G3     | [7b8e9fe353](https://linux-hardware.org/?probe=7b8e9fe353) | Dec 24, 2022 |
| Acer          | Aspire A315-21G             | [435933801a](https://linux-hardware.org/?probe=435933801a) | Dec 24, 2022 |
| HP            | Notebook                    | [10dfda9549](https://linux-hardware.org/?probe=10dfda9549) | Dec 24, 2022 |
| Toshiba       | Satellite C55-A             | [02a3f1cf18](https://linux-hardware.org/?probe=02a3f1cf18) | Dec 24, 2022 |
| Acer          | Aspire VX5-591G             | [f2e0369ba1](https://linux-hardware.org/?probe=f2e0369ba1) | Dec 24, 2022 |
| Dell          | Vostro 5490                 | [f694fa24c8](https://linux-hardware.org/?probe=f694fa24c8) | Dec 23, 2022 |
| Lenovo        | G505s 20255                 | [2a0fc9ecc3](https://linux-hardware.org/?probe=2a0fc9ecc3) | Dec 23, 2022 |
| Intel         | ChiefRiver                  | [a23ea2e43e](https://linux-hardware.org/?probe=a23ea2e43e) | Dec 23, 2022 |
| Clevo         | NL41MU2                     | [f9b6dc975b](https://linux-hardware.org/?probe=f9b6dc975b) | Dec 23, 2022 |
| Unknown       | Unknown                     | [5e4cb87810](https://linux-hardware.org/?probe=5e4cb87810) | Dec 23, 2022 |
| HP            | Laptop 15-db0xxx            | [3e269dcad0](https://linux-hardware.org/?probe=3e269dcad0) | Dec 23, 2022 |
| Dell          | Inspiron 5490               | [1c424b5f55](https://linux-hardware.org/?probe=1c424b5f55) | Dec 23, 2022 |
| HP            | Laptop 15-db0xxx            | [27f289cf57](https://linux-hardware.org/?probe=27f289cf57) | Dec 23, 2022 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [5ce0dacccf](https://linux-hardware.org/?probe=5ce0dacccf) | Dec 23, 2022 |
| Unknown       | Unknown                     | [c9637c2acf](https://linux-hardware.org/?probe=c9637c2acf) | Dec 22, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [451f22ab12](https://linux-hardware.org/?probe=451f22ab12) | Dec 22, 2022 |
| ASUSTek       | M51Vr                       | [ffc48a52ea](https://linux-hardware.org/?probe=ffc48a52ea) | Dec 22, 2022 |
| Lenovo        | B570e HuronRiver Platfor... | [672c320794](https://linux-hardware.org/?probe=672c320794) | Dec 22, 2022 |
| HP            | G62                         | [00b47da7dc](https://linux-hardware.org/?probe=00b47da7dc) | Dec 22, 2022 |
| Lenovo        | G700 20251                  | [1a8f388366](https://linux-hardware.org/?probe=1a8f388366) | Dec 22, 2022 |
| Toshiba       | Satellite A300              | [8981102ebe](https://linux-hardware.org/?probe=8981102ebe) | Dec 22, 2022 |
| HP            | ProBook 440 G4              | [c93f96de9e](https://linux-hardware.org/?probe=c93f96de9e) | Dec 22, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [677cb5b0b3](https://linux-hardware.org/?probe=677cb5b0b3) | Dec 22, 2022 |
| HP            | ProBook 440 G6              | [ad317dc4fd](https://linux-hardware.org/?probe=ad317dc4fd) | Dec 22, 2022 |
| Lenovo        | ThinkPad E490 20N80019RT    | [87746a4f6c](https://linux-hardware.org/?probe=87746a4f6c) | Dec 22, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [5f132c928b](https://linux-hardware.org/?probe=5f132c928b) | Dec 22, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [95b8e650ce](https://linux-hardware.org/?probe=95b8e650ce) | Dec 21, 2022 |
| Lenovo        | G700 20251                  | [afac6a5bfa](https://linux-hardware.org/?probe=afac6a5bfa) | Dec 21, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [5262e622da](https://linux-hardware.org/?probe=5262e622da) | Dec 21, 2022 |
| MSI           | Alpha 15 B5EEK              | [d6e55e247a](https://linux-hardware.org/?probe=d6e55e247a) | Dec 21, 2022 |
| HP            | EliteBook Folio 1040 G3     | [3d89cf5c71](https://linux-hardware.org/?probe=3d89cf5c71) | Dec 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [cc485cc076](https://linux-hardware.org/?probe=cc485cc076) | Dec 21, 2022 |
| eMachines     | E525                        | [8368666118](https://linux-hardware.org/?probe=8368666118) | Dec 21, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [127d74a6ea](https://linux-hardware.org/?probe=127d74a6ea) | Dec 21, 2022 |
| ASUSTek       | X555SJ                      | [c580c82fe2](https://linux-hardware.org/?probe=c580c82fe2) | Dec 21, 2022 |
| Lenovo        | ThinkPad E15 20RD0011RT     | [1f1c718c61](https://linux-hardware.org/?probe=1f1c718c61) | Dec 21, 2022 |
| Lenovo        | G700 20251                  | [ba8b12c87e](https://linux-hardware.org/?probe=ba8b12c87e) | Dec 21, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [c56023ff15](https://linux-hardware.org/?probe=c56023ff15) | Dec 21, 2022 |
| Lenovo        | IdeaPad 310-15IAP 80TT      | [7fe5232b14](https://linux-hardware.org/?probe=7fe5232b14) | Dec 20, 2022 |
| Lenovo        | ThinkPad E15 20RD0011RT     | [bbfea042cd](https://linux-hardware.org/?probe=bbfea042cd) | Dec 20, 2022 |
| ASUSTek       | X550VC                      | [5d5f66f67a](https://linux-hardware.org/?probe=5d5f66f67a) | Dec 20, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | [a7364cab6e](https://linux-hardware.org/?probe=a7364cab6e) | Dec 20, 2022 |
| ASUSTek       | Zenbook UX5400EA_UX5400E... | [011d3e746d](https://linux-hardware.org/?probe=011d3e746d) | Dec 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [593cdd8cf6](https://linux-hardware.org/?probe=593cdd8cf6) | Dec 19, 2022 |
| MSI           | CreatorPro Z17 A12UKST      | [6b97aacdf0](https://linux-hardware.org/?probe=6b97aacdf0) | Dec 19, 2022 |
| Dell          | Latitude 7320               | [25546304f0](https://linux-hardware.org/?probe=25546304f0) | Dec 19, 2022 |
| Dell          | Latitude 7320               | [ad474d946a](https://linux-hardware.org/?probe=ad474d946a) | Dec 19, 2022 |
| HUAWEI        | HVY-WXX9                    | [ebf2594631](https://linux-hardware.org/?probe=ebf2594631) | Dec 19, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [714d2a6dea](https://linux-hardware.org/?probe=714d2a6dea) | Dec 19, 2022 |
| Irbis         | NB264                       | [4bb5935a41](https://linux-hardware.org/?probe=4bb5935a41) | Dec 19, 2022 |
| Irbis         | NB264                       | [1209e6c899](https://linux-hardware.org/?probe=1209e6c899) | Dec 19, 2022 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [a5a207a46d](https://linux-hardware.org/?probe=a5a207a46d) | Dec 19, 2022 |
| Timi          | RedmiBook Pro 15S           | [6a2ea2cc50](https://linux-hardware.org/?probe=6a2ea2cc50) | Dec 18, 2022 |
| Timi          | RedmiBook Pro 15S           | [a1ccdb589e](https://linux-hardware.org/?probe=a1ccdb589e) | Dec 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [4c1ad2ea2e](https://linux-hardware.org/?probe=4c1ad2ea2e) | Dec 18, 2022 |
| MSI           | X460/X460DX                 | [6fff37a8a5](https://linux-hardware.org/?probe=6fff37a8a5) | Dec 18, 2022 |
| MSI           | X460/X460DX                 | [71ca32ac12](https://linux-hardware.org/?probe=71ca32ac12) | Dec 18, 2022 |
| Acer          | Nitro AN515-56              | [cac9892365](https://linux-hardware.org/?probe=cac9892365) | Dec 18, 2022 |
| Kraftway      | ACCORD                      | [34360d84a8](https://linux-hardware.org/?probe=34360d84a8) | Dec 18, 2022 |
| eMachines     | E525                        | [2a0aeb50bf](https://linux-hardware.org/?probe=2a0aeb50bf) | Dec 18, 2022 |
| Pegatron      | C15B                        | [865b882e8a](https://linux-hardware.org/?probe=865b882e8a) | Dec 18, 2022 |
| Kraftway      | ACCORD                      | [a199d930ff](https://linux-hardware.org/?probe=a199d930ff) | Dec 18, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [23b255ed61](https://linux-hardware.org/?probe=23b255ed61) | Dec 18, 2022 |
| Acer          | AO533                       | [1639951fe5](https://linux-hardware.org/?probe=1639951fe5) | Dec 18, 2022 |
| ASUSTek       | K55A                        | [6129e825d9](https://linux-hardware.org/?probe=6129e825d9) | Dec 18, 2022 |
| ASUSTek       | 1201N                       | [214a7002b9](https://linux-hardware.org/?probe=214a7002b9) | Dec 18, 2022 |
| Dell          | Inspiron 15-3552            | [0dc1961e62](https://linux-hardware.org/?probe=0dc1961e62) | Dec 18, 2022 |
| Aquarius      | Pro, Std, Elt Series        | [59b7fca136](https://linux-hardware.org/?probe=59b7fca136) | Dec 18, 2022 |
| HP            | Pavilion g7                 | [6a1a042504](https://linux-hardware.org/?probe=6a1a042504) | Dec 18, 2022 |
| ASUSTek       | X555UJ                      | [94a9979dd8](https://linux-hardware.org/?probe=94a9979dd8) | Dec 18, 2022 |
| HP            | Pavilion g7                 | [465a08d81a](https://linux-hardware.org/?probe=465a08d81a) | Dec 18, 2022 |
| ASUSTek       | N551JM                      | [e02ba85a63](https://linux-hardware.org/?probe=e02ba85a63) | Dec 18, 2022 |
| Lenovo        | G580 20157                  | [c6cce8ff6d](https://linux-hardware.org/?probe=c6cce8ff6d) | Dec 18, 2022 |
| Dell          | Inspiron 1525               | [216bedab36](https://linux-hardware.org/?probe=216bedab36) | Dec 18, 2022 |
| Prestigio     | PSB141C04CGH                | [60f02a4cb4](https://linux-hardware.org/?probe=60f02a4cb4) | Dec 17, 2022 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [f047451b08](https://linux-hardware.org/?probe=f047451b08) | Dec 17, 2022 |
| ICL           | RAYbook Si1511              | [9994b3ec08](https://linux-hardware.org/?probe=9994b3ec08) | Dec 17, 2022 |
| Gigabyte      | G5 KE                       | [9ff3d65e35](https://linux-hardware.org/?probe=9ff3d65e35) | Dec 17, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [1fe7ad453e](https://linux-hardware.org/?probe=1fe7ad453e) | Dec 17, 2022 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [c04b0805ad](https://linux-hardware.org/?probe=c04b0805ad) | Dec 17, 2022 |
| GPD           | G1619-04                    | [0859fa80c8](https://linux-hardware.org/?probe=0859fa80c8) | Dec 17, 2022 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [645e7245d4](https://linux-hardware.org/?probe=645e7245d4) | Dec 17, 2022 |
| Acer          | Aspire ES1-521              | [4f4f04579a](https://linux-hardware.org/?probe=4f4f04579a) | Dec 17, 2022 |
| Maibenben     | MaiBook M                   | [a216b90cac](https://linux-hardware.org/?probe=a216b90cac) | Dec 17, 2022 |
| Apple         | MacBook4,1                  | [26bb5af1a4](https://linux-hardware.org/?probe=26bb5af1a4) | Dec 16, 2022 |
| Lenovo        | ThinkPad X200s 7466A17      | [1831439f56](https://linux-hardware.org/?probe=1831439f56) | Dec 16, 2022 |
| ASUSTek       | X550CC                      | [045064bd18](https://linux-hardware.org/?probe=045064bd18) | Dec 16, 2022 |
| Acer          | Aspire V5-571G              | [575a61802b](https://linux-hardware.org/?probe=575a61802b) | Dec 16, 2022 |
| 3Logic Gro... | Graviton N15i               | [9d85f624db](https://linux-hardware.org/?probe=9d85f624db) | Dec 16, 2022 |
| Dell          | Vostro 5590                 | [3735674d3f](https://linux-hardware.org/?probe=3735674d3f) | Dec 16, 2022 |
| 3Logic Gro... | Graviton N15i-K2            | [a04f7471b9](https://linux-hardware.org/?probe=a04f7471b9) | Dec 16, 2022 |
| Lenovo        | ThinkPad L430 246429G       | [acb9efe70f](https://linux-hardware.org/?probe=acb9efe70f) | Dec 16, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [66d31fc2c8](https://linux-hardware.org/?probe=66d31fc2c8) | Dec 16, 2022 |
| Shanghai Z... | ZXE CRB                     | [20ce0a7f23](https://linux-hardware.org/?probe=20ce0a7f23) | Dec 16, 2022 |
| HUAWEI        | NBM-WXX9                    | [a9f5b0866f](https://linux-hardware.org/?probe=a9f5b0866f) | Dec 16, 2022 |
| HUAWEI        | KLVL-WXXW                   | [302dc680df](https://linux-hardware.org/?probe=302dc680df) | Dec 16, 2022 |
| HUAWEI        | KLVL-WXXW                   | [d289646ec3](https://linux-hardware.org/?probe=d289646ec3) | Dec 16, 2022 |
| Machcreato... | 14                          | [8b69842953](https://linux-hardware.org/?probe=8b69842953) | Dec 15, 2022 |
| Lenovo        | B590 20206                  | [b2b98c19da](https://linux-hardware.org/?probe=b2b98c19da) | Dec 15, 2022 |
| Irbis         | NB264                       | [14764ec4e5](https://linux-hardware.org/?probe=14764ec4e5) | Dec 15, 2022 |
| HUAWEI        | BOM-WXX9                    | [ca39e55353](https://linux-hardware.org/?probe=ca39e55353) | Dec 15, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [b8cc280665](https://linux-hardware.org/?probe=b8cc280665) | Dec 15, 2022 |
| ASUSTek       | K40IJ                       | [191b6ded65](https://linux-hardware.org/?probe=191b6ded65) | Dec 15, 2022 |
| Unknown       | Unknown                     | [24bebac773](https://linux-hardware.org/?probe=24bebac773) | Dec 15, 2022 |
| Lenovo        | G700 20251                  | [f72bd71975](https://linux-hardware.org/?probe=f72bd71975) | Dec 15, 2022 |
| HUAWEI        | KLVL-WXXW                   | [1dd0f2a71f](https://linux-hardware.org/?probe=1dd0f2a71f) | Dec 15, 2022 |
| Unknown       | Unknown                     | [643cb41a84](https://linux-hardware.org/?probe=643cb41a84) | Dec 15, 2022 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [e6b439e36e](https://linux-hardware.org/?probe=e6b439e36e) | Dec 15, 2022 |
| Dell          | Inspiron 5370               | [dd8f3feae5](https://linux-hardware.org/?probe=dd8f3feae5) | Dec 15, 2022 |
| Lenovo        | B50-70 20384                | [82edcc6c08](https://linux-hardware.org/?probe=82edcc6c08) | Dec 15, 2022 |
| Irbis         | NB264                       | [d137aad605](https://linux-hardware.org/?probe=d137aad605) | Dec 14, 2022 |
| Digma         | EVE 11 C421Y ES1067EW       | [458afe13df](https://linux-hardware.org/?probe=458afe13df) | Dec 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [c84a4ee6f2](https://linux-hardware.org/?probe=c84a4ee6f2) | Dec 14, 2022 |
| ECS           | CMPC                        | [53d853228f](https://linux-hardware.org/?probe=53d853228f) | Dec 14, 2022 |
| ASUSTek       | F7Z                         | [3c42714822](https://linux-hardware.org/?probe=3c42714822) | Dec 14, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [7040d4353c](https://linux-hardware.org/?probe=7040d4353c) | Dec 14, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | [d8d72f23e6](https://linux-hardware.org/?probe=d8d72f23e6) | Dec 14, 2022 |
| ASUSTek       | N73SV                       | [7b729a3a7c](https://linux-hardware.org/?probe=7b729a3a7c) | Dec 14, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [1457c2669d](https://linux-hardware.org/?probe=1457c2669d) | Dec 13, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [c476fb8f49](https://linux-hardware.org/?probe=c476fb8f49) | Dec 13, 2022 |
| Dell          | Inspiron 1525               | [5a88d1f0e3](https://linux-hardware.org/?probe=5a88d1f0e3) | Dec 13, 2022 |
| Acer          | Aspire 5720                 | [5940b07034](https://linux-hardware.org/?probe=5940b07034) | Dec 13, 2022 |
| Pegatron      | C17A                        | [adde308568](https://linux-hardware.org/?probe=adde308568) | Dec 13, 2022 |
| ASUSTek       | N73SV                       | [c696bac1dd](https://linux-hardware.org/?probe=c696bac1dd) | Dec 13, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [5d00840ad3](https://linux-hardware.org/?probe=5d00840ad3) | Dec 13, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [b479704ea5](https://linux-hardware.org/?probe=b479704ea5) | Dec 13, 2022 |
| Samsung       | 305V4A/305V5A/3415VA        | [d01e578aa0](https://linux-hardware.org/?probe=d01e578aa0) | Dec 13, 2022 |
| Sony          | VPCEJ1L1R                   | [25ab3e0119](https://linux-hardware.org/?probe=25ab3e0119) | Dec 13, 2022 |
| Valve         | Jupiter                     | [008a4d9a91](https://linux-hardware.org/?probe=008a4d9a91) | Dec 13, 2022 |
| MSI           | GF65 Thin 10UE              | [ff4ab808c0](https://linux-hardware.org/?probe=ff4ab808c0) | Dec 13, 2022 |
| Clevo         | M7x0K                       | [08ce94ab11](https://linux-hardware.org/?probe=08ce94ab11) | Dec 13, 2022 |
| GPD           | G1619-04                    | [d263576c0f](https://linux-hardware.org/?probe=d263576c0f) | Dec 12, 2022 |
| Lenovo        | V14-IIL 82C4                | [8c4853dba7](https://linux-hardware.org/?probe=8c4853dba7) | Dec 12, 2022 |
| Lenovo        | ThinkPad T440s 20AQ004EU... | [8d04dfe3a5](https://linux-hardware.org/?probe=8d04dfe3a5) | Dec 12, 2022 |
| Timi          | TM1701                      | [ab22ee1055](https://linux-hardware.org/?probe=ab22ee1055) | Dec 12, 2022 |
| Lenovo        | ThinkPad T460 20FMS1GR17    | [2d90485ea0](https://linux-hardware.org/?probe=2d90485ea0) | Dec 12, 2022 |
| Sony          | SVE1111M1RW                 | [bc29721da9](https://linux-hardware.org/?probe=bc29721da9) | Dec 12, 2022 |
| Acer          | Aspire 5740                 | [5b35ba45a3](https://linux-hardware.org/?probe=5b35ba45a3) | Dec 12, 2022 |
| Lenovo        | IdeaPad Z580                | [4784b53f14](https://linux-hardware.org/?probe=4784b53f14) | Dec 12, 2022 |
| Acer          | Aspire A515-44              | [965817e5f0](https://linux-hardware.org/?probe=965817e5f0) | Dec 11, 2022 |
| Acer          | Aspire A315-42G             | [1d93c8b401](https://linux-hardware.org/?probe=1d93c8b401) | Dec 11, 2022 |
| Toshiba       | Satellite A300              | [211e44e5d2](https://linux-hardware.org/?probe=211e44e5d2) | Dec 11, 2022 |
| Sony          | VPCEB3D4R                   | [5f85b7c516](https://linux-hardware.org/?probe=5f85b7c516) | Dec 11, 2022 |
| Lenovo        | G770 20089                  | [f6f1441538](https://linux-hardware.org/?probe=f6f1441538) | Dec 11, 2022 |
| MSI           | Modern 14 B11MOU            | [ec8ac9bbd7](https://linux-hardware.org/?probe=ec8ac9bbd7) | Dec 11, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | [c90a3cb8c2](https://linux-hardware.org/?probe=c90a3cb8c2) | Dec 11, 2022 |
| Acer          | Aspire E5-571G              | [5ddea1e0e0](https://linux-hardware.org/?probe=5ddea1e0e0) | Dec 11, 2022 |
| ASUSTek       | UL30A                       | [f24e02511f](https://linux-hardware.org/?probe=f24e02511f) | Dec 11, 2022 |
| Notebook      | WA50SRQ                     | [da74211ac6](https://linux-hardware.org/?probe=da74211ac6) | Dec 11, 2022 |
| Lenovo        | G700 20251                  | [0400a58c53](https://linux-hardware.org/?probe=0400a58c53) | Dec 11, 2022 |
| HP            | Laptop 15-bw0xx             | [5f885c41a0](https://linux-hardware.org/?probe=5f885c41a0) | Dec 11, 2022 |
| Samsung       | SQ45/Q70C/P200              | [4a96589cf5](https://linux-hardware.org/?probe=4a96589cf5) | Dec 11, 2022 |
| ASUSTek       | N75SF                       | [4d1916b6ca](https://linux-hardware.org/?probe=4d1916b6ca) | Dec 11, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [b56d83f25b](https://linux-hardware.org/?probe=b56d83f25b) | Dec 10, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [6cedae9702](https://linux-hardware.org/?probe=6cedae9702) | Dec 10, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [bb4615bd96](https://linux-hardware.org/?probe=bb4615bd96) | Dec 10, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [92d1403bdf](https://linux-hardware.org/?probe=92d1403bdf) | Dec 10, 2022 |
| Samsung       | RC530/RC730                 | [4b7783525a](https://linux-hardware.org/?probe=4b7783525a) | Dec 10, 2022 |
| Acer          | Aspire E1-571G              | [344383d85d](https://linux-hardware.org/?probe=344383d85d) | Dec 10, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [fa13871cf9](https://linux-hardware.org/?probe=fa13871cf9) | Dec 10, 2022 |
| Lenovo        | V15-IGL 82C3                | [ec71643183](https://linux-hardware.org/?probe=ec71643183) | Dec 09, 2022 |
| Lenovo        | V15-IGL 82C3                | [aa2fd0b3bc](https://linux-hardware.org/?probe=aa2fd0b3bc) | Dec 09, 2022 |
| Pegatron      | C17A                        | [2437a88730](https://linux-hardware.org/?probe=2437a88730) | Dec 09, 2022 |
| MSI           | Modern 15 B12M              | [b5f43a3075](https://linux-hardware.org/?probe=b5f43a3075) | Dec 09, 2022 |
| HP            | Laptop 14s-dq1xxx           | [6af7fadd72](https://linux-hardware.org/?probe=6af7fadd72) | Dec 09, 2022 |
| HP            | Laptop 14s-dq1xxx           | [7e1510d6c6](https://linux-hardware.org/?probe=7e1510d6c6) | Dec 09, 2022 |
| MSI           | GP66 Leopard 11UG           | [daffbd93fb](https://linux-hardware.org/?probe=daffbd93fb) | Dec 09, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [311f47baef](https://linux-hardware.org/?probe=311f47baef) | Dec 09, 2022 |
| Gigabyte      | AORUS 15G KC                | [91e987df99](https://linux-hardware.org/?probe=91e987df99) | Dec 09, 2022 |
| ASUSTek       | UX310UQK                    | [c4a573e93c](https://linux-hardware.org/?probe=c4a573e93c) | Dec 08, 2022 |
| Acer          | Aspire F5-571G              | [dedd56f0fe](https://linux-hardware.org/?probe=dedd56f0fe) | Dec 08, 2022 |
| Lenovo        | B590 20206                  | [969ca94bb7](https://linux-hardware.org/?probe=969ca94bb7) | Dec 08, 2022 |
| Timi          | Redmi Book Pro 14 2022      | [e7813eb1b3](https://linux-hardware.org/?probe=e7813eb1b3) | Dec 08, 2022 |
| ASUSTek       | K42F                        | [ee90271b2d](https://linux-hardware.org/?probe=ee90271b2d) | Dec 08, 2022 |
| ASUSTek       | N750JV                      | [e06c6025f3](https://linux-hardware.org/?probe=e06c6025f3) | Dec 08, 2022 |
| Dell          | Vostro 14 5410              | [af22c1db61](https://linux-hardware.org/?probe=af22c1db61) | Dec 08, 2022 |
| Apple         | MacBookAir6,2               | [65bc0e828c](https://linux-hardware.org/?probe=65bc0e828c) | Dec 08, 2022 |
| HP            | Laptop 15s-eq1xxx           | [79a0f9e73a](https://linux-hardware.org/?probe=79a0f9e73a) | Dec 08, 2022 |
| Packard Be... | DOT S                       | [753f17a658](https://linux-hardware.org/?probe=753f17a658) | Dec 08, 2022 |
| Acer          | Aspire A315-34              | [85794e606c](https://linux-hardware.org/?probe=85794e606c) | Dec 08, 2022 |
| MSI           | Modern 14 B11MOU            | [426e23829e](https://linux-hardware.org/?probe=426e23829e) | Dec 08, 2022 |
| HP            | Laptop 15s-eq1xxx           | [c1cd524970](https://linux-hardware.org/?probe=c1cd524970) | Dec 08, 2022 |
| Dell          | Inspiron 3721               | [3bfc5892fe](https://linux-hardware.org/?probe=3bfc5892fe) | Dec 08, 2022 |
| Apple         | MacBook7,1                  | [317fdfd70b](https://linux-hardware.org/?probe=317fdfd70b) | Dec 08, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [c6d0984a2c](https://linux-hardware.org/?probe=c6d0984a2c) | Dec 08, 2022 |
| ASUSTek       | U24E                        | [e8bdc6be97](https://linux-hardware.org/?probe=e8bdc6be97) | Dec 08, 2022 |
| Aquarius      | NS685U R11                  | [c0dff8c525](https://linux-hardware.org/?probe=c0dff8c525) | Dec 08, 2022 |
| MSI           | Modern 14 B11MOU            | [49e70cf65f](https://linux-hardware.org/?probe=49e70cf65f) | Dec 07, 2022 |
| Dell          | Inspiron 3137               | [2f74d45567](https://linux-hardware.org/?probe=2f74d45567) | Dec 07, 2022 |
| Unknown       | Y116                        | [204f1465c7](https://linux-hardware.org/?probe=204f1465c7) | Dec 07, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [cd83a085ba](https://linux-hardware.org/?probe=cd83a085ba) | Dec 07, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [fd694a5ddd](https://linux-hardware.org/?probe=fd694a5ddd) | Dec 07, 2022 |
| HP            | ENVY 17                     | [a19d90a89f](https://linux-hardware.org/?probe=a19d90a89f) | Dec 07, 2022 |
| HP            | EliteBook 8540p             | [1c0ff5bf47](https://linux-hardware.org/?probe=1c0ff5bf47) | Dec 07, 2022 |
| HP            | EliteBook 8540p             | [9cf475f84e](https://linux-hardware.org/?probe=9cf475f84e) | Dec 07, 2022 |
| Pegatron      | C17A                        | [5fc3c61389](https://linux-hardware.org/?probe=5fc3c61389) | Dec 07, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [619fd919a1](https://linux-hardware.org/?probe=619fd919a1) | Dec 07, 2022 |
| ASUSTek       | K53SV                       | [a745b1ead9](https://linux-hardware.org/?probe=a745b1ead9) | Dec 07, 2022 |
| Clevo         | P150HMx                     | [f1500b1665](https://linux-hardware.org/?probe=f1500b1665) | Dec 06, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [ceae9dc7d5](https://linux-hardware.org/?probe=ceae9dc7d5) | Dec 06, 2022 |
| Acer          | Extensa 5220                | [30ca0c3efa](https://linux-hardware.org/?probe=30ca0c3efa) | Dec 06, 2022 |
| HONOR         | BBR-WAX9                    | [d7d701ca15](https://linux-hardware.org/?probe=d7d701ca15) | Dec 06, 2022 |
| Lenovo        | G700 20251                  | [0613a1c41e](https://linux-hardware.org/?probe=0613a1c41e) | Dec 06, 2022 |
| MSI           | Pulse GL66 12UEK            | [ea01a2005e](https://linux-hardware.org/?probe=ea01a2005e) | Dec 06, 2022 |
| HP            | Laptop 17-ak0xx             | [9fb5c9d094](https://linux-hardware.org/?probe=9fb5c9d094) | Dec 06, 2022 |
| HP            | ENVY 17                     | [569f7b0e9f](https://linux-hardware.org/?probe=569f7b0e9f) | Dec 06, 2022 |
| HP            | Pavilion 15                 | [eb3caff76e](https://linux-hardware.org/?probe=eb3caff76e) | Dec 06, 2022 |
| ICL           | RAYbook Si1512              | [b8c52ae5cb](https://linux-hardware.org/?probe=b8c52ae5cb) | Dec 06, 2022 |
| HP            | ProBook 440 G5              | [7f9c0a0974](https://linux-hardware.org/?probe=7f9c0a0974) | Dec 06, 2022 |
| MSI           | Pulse GL66 12UEK            | [4438c9636c](https://linux-hardware.org/?probe=4438c9636c) | Dec 06, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [12e33b1925](https://linux-hardware.org/?probe=12e33b1925) | Dec 06, 2022 |
| HP            | ProBook 650 G1              | [d080bb3fe0](https://linux-hardware.org/?probe=d080bb3fe0) | Dec 05, 2022 |
| HP            | ProBook 650 G1              | [8e3bfa4f20](https://linux-hardware.org/?probe=8e3bfa4f20) | Dec 05, 2022 |
| Gigabyte      | U24                         | [dbe62c503d](https://linux-hardware.org/?probe=dbe62c503d) | Dec 05, 2022 |
| Apple         | MacBookPro9,2               | [5827ea2fa5](https://linux-hardware.org/?probe=5827ea2fa5) | Dec 05, 2022 |
| HONOR         | BOHK-WAX9X                  | [543eb800d7](https://linux-hardware.org/?probe=543eb800d7) | Dec 05, 2022 |
| Apple         | MacBookPro9,2               | [7f8dcdb666](https://linux-hardware.org/?probe=7f8dcdb666) | Dec 05, 2022 |
| HP            | Laptop 15s-eq1xxx           | [0cd3371014](https://linux-hardware.org/?probe=0cd3371014) | Dec 05, 2022 |
| Dell          | Inspiron 3521               | [44f8fe348a](https://linux-hardware.org/?probe=44f8fe348a) | Dec 05, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [d512bff9cc](https://linux-hardware.org/?probe=d512bff9cc) | Dec 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [fef748b3f4](https://linux-hardware.org/?probe=fef748b3f4) | Dec 04, 2022 |
| MSI           | Sword 15 A12UE              | [32df733b5e](https://linux-hardware.org/?probe=32df733b5e) | Dec 04, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [90db11aeba](https://linux-hardware.org/?probe=90db11aeba) | Dec 04, 2022 |
| Lenovo        | ThinkPad L420 7854RP1       | [3216e34b2e](https://linux-hardware.org/?probe=3216e34b2e) | Dec 04, 2022 |
| ASUSTek       | P43E                        | [c21502af00](https://linux-hardware.org/?probe=c21502af00) | Dec 04, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [3ee55cc441](https://linux-hardware.org/?probe=3ee55cc441) | Dec 04, 2022 |
| Acer          | Nitro AN515-43              | [f18907cee0](https://linux-hardware.org/?probe=f18907cee0) | Dec 04, 2022 |
| ASUSTek       | K42F                        | [05ddce411d](https://linux-hardware.org/?probe=05ddce411d) | Dec 04, 2022 |
| HP            | ProBook 440 G5              | [a8e17ad39c](https://linux-hardware.org/?probe=a8e17ad39c) | Dec 04, 2022 |
| ASUSTek       | X550CC                      | [be693e121b](https://linux-hardware.org/?probe=be693e121b) | Dec 04, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [c795306dd2](https://linux-hardware.org/?probe=c795306dd2) | Dec 03, 2022 |
| HP            | ProBook 430 G2              | [a66be8f003](https://linux-hardware.org/?probe=a66be8f003) | Dec 03, 2022 |
| Pegatron      | A15W8                       | [f33c1aea21](https://linux-hardware.org/?probe=f33c1aea21) | Dec 03, 2022 |
| Unknown       | Unknown                     | [40917baf56](https://linux-hardware.org/?probe=40917baf56) | Dec 03, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [91bffab1ae](https://linux-hardware.org/?probe=91bffab1ae) | Dec 03, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [795327c2b7](https://linux-hardware.org/?probe=795327c2b7) | Dec 03, 2022 |
| HONOR         | NMH-WCX9                    | [3f107d24d1](https://linux-hardware.org/?probe=3f107d24d1) | Dec 03, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [6cb73d5a1c](https://linux-hardware.org/?probe=6cb73d5a1c) | Dec 03, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | [77651c30c5](https://linux-hardware.org/?probe=77651c30c5) | Dec 03, 2022 |
| ASUSTek       | X541UJ                      | [898b49da7f](https://linux-hardware.org/?probe=898b49da7f) | Dec 03, 2022 |
| ASUSTek       | N750JV                      | [0fc50d63c4](https://linux-hardware.org/?probe=0fc50d63c4) | Dec 02, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [e16c372c9c](https://linux-hardware.org/?probe=e16c372c9c) | Dec 02, 2022 |
| ASUSTek       | X550CL                      | [8a2aad437e](https://linux-hardware.org/?probe=8a2aad437e) | Dec 02, 2022 |
| Lenovo        | B590 20208                  | [367c0f8907](https://linux-hardware.org/?probe=367c0f8907) | Dec 02, 2022 |
| MSI           | GE72 6QC                    | [8411668d4d](https://linux-hardware.org/?probe=8411668d4d) | Dec 02, 2022 |
| Acer          | Aspire 5951G                | [0b1e900a8c](https://linux-hardware.org/?probe=0b1e900a8c) | Dec 02, 2022 |
| Aquarius      | NS585                       | [bbd3bd3ca6](https://linux-hardware.org/?probe=bbd3bd3ca6) | Dec 02, 2022 |
| HP            | 635                         | [cf79165440](https://linux-hardware.org/?probe=cf79165440) | Dec 02, 2022 |
| Aquarius      | NS585                       | [50222418e5](https://linux-hardware.org/?probe=50222418e5) | Dec 02, 2022 |
| Aquarius      | NS585                       | [d55d40681f](https://linux-hardware.org/?probe=d55d40681f) | Dec 02, 2022 |
| Aquarius      | NS585                       | [9013a1cce6](https://linux-hardware.org/?probe=9013a1cce6) | Dec 02, 2022 |
| Acer          | Aspire V5-572G              | [638e9873a7](https://linux-hardware.org/?probe=638e9873a7) | Dec 02, 2022 |
| Acer          | Aspire V5-572G              | [711acef394](https://linux-hardware.org/?probe=711acef394) | Dec 02, 2022 |
| Unknown       | Y116                        | [5686455162](https://linux-hardware.org/?probe=5686455162) | Dec 02, 2022 |
| Unknown       | Y116                        | [5050c40509](https://linux-hardware.org/?probe=5050c40509) | Dec 02, 2022 |
| Acer          | Swift SF314-510G            | [b66322960d](https://linux-hardware.org/?probe=b66322960d) | Dec 02, 2022 |
| Samsung       | R410                        | [7c2a18f2cc](https://linux-hardware.org/?probe=7c2a18f2cc) | Dec 01, 2022 |
| Acer          | Aspire V3-571G              | [bbb0c707bb](https://linux-hardware.org/?probe=bbb0c707bb) | Dec 01, 2022 |
| Acer          | Aspire V3-771               | [38dfcb79d5](https://linux-hardware.org/?probe=38dfcb79d5) | Dec 01, 2022 |
| Acer          | Aspire 3830TG               | [8bb246cbaa](https://linux-hardware.org/?probe=8bb246cbaa) | Dec 01, 2022 |
| Lenovo        | ThinkPad T440p 20AN0079M... | [79261239c1](https://linux-hardware.org/?probe=79261239c1) | Dec 01, 2022 |
| Acer          | Aspire 3830TG               | [46bcb20e26](https://linux-hardware.org/?probe=46bcb20e26) | Dec 01, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [d57de89542](https://linux-hardware.org/?probe=d57de89542) | Dec 01, 2022 |
| Acer          | Aspire E1-570G              | [b41442c5a1](https://linux-hardware.org/?probe=b41442c5a1) | Dec 01, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [a8156db955](https://linux-hardware.org/?probe=a8156db955) | Dec 01, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [0128a48982](https://linux-hardware.org/?probe=0128a48982) | Dec 01, 2022 |
| Acer          | Aspire 5336                 | [65be105c02](https://linux-hardware.org/?probe=65be105c02) | Dec 01, 2022 |
| Unknown       | Unknown                     | [dceef2a9d5](https://linux-hardware.org/?probe=dceef2a9d5) | Dec 01, 2022 |
| Dell          | Vostro 3578                 | [89161c2dee](https://linux-hardware.org/?probe=89161c2dee) | Dec 01, 2022 |
| Lenovo        | B450 1S1680033610187        | [e33670a27b](https://linux-hardware.org/?probe=e33670a27b) | Nov 30, 2022 |
| Acer          | Aspire A315-21              | [7c3a371165](https://linux-hardware.org/?probe=7c3a371165) | Nov 30, 2022 |
| HP            | 255 G4                      | [33b2fb7f31](https://linux-hardware.org/?probe=33b2fb7f31) | Nov 30, 2022 |
| Acer          | Aspire A315-21              | [5f14327a56](https://linux-hardware.org/?probe=5f14327a56) | Nov 30, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [5f53eff4a6](https://linux-hardware.org/?probe=5f53eff4a6) | Nov 30, 2022 |
| MSI           | GE72 6QC                    | [ba4847397e](https://linux-hardware.org/?probe=ba4847397e) | Nov 30, 2022 |
| Pegatron      | C15B                        | [defacd8748](https://linux-hardware.org/?probe=defacd8748) | Nov 30, 2022 |
| Pegatron      | C15B                        | [92271ab582](https://linux-hardware.org/?probe=92271ab582) | Nov 30, 2022 |
| Unknown       | Unknown                     | [9964cb6fe2](https://linux-hardware.org/?probe=9964cb6fe2) | Nov 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [65c3211b0a](https://linux-hardware.org/?probe=65c3211b0a) | Nov 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [2a8dbc14ef](https://linux-hardware.org/?probe=2a8dbc14ef) | Nov 30, 2022 |
| HUAWEI        | CREM-WXX9                   | [33f7ac03f4](https://linux-hardware.org/?probe=33f7ac03f4) | Nov 30, 2022 |
| Haier         | A1420EM                     | [6f18b3c1ce](https://linux-hardware.org/?probe=6f18b3c1ce) | Nov 30, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [b245f9da58](https://linux-hardware.org/?probe=b245f9da58) | Nov 30, 2022 |
| Dell          | Inspiron 3558               | [481755baa3](https://linux-hardware.org/?probe=481755baa3) | Nov 30, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [aadb9ff1d4](https://linux-hardware.org/?probe=aadb9ff1d4) | Nov 30, 2022 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [f5f86becf7](https://linux-hardware.org/?probe=f5f86becf7) | Nov 30, 2022 |
| Samsung       | R560                        | [936ae4b775](https://linux-hardware.org/?probe=936ae4b775) | Nov 29, 2022 |
| Lenovo        | B590 20206                  | [5bec8860f3](https://linux-hardware.org/?probe=5bec8860f3) | Nov 29, 2022 |
| Apple         | MacBookPro12,1              | [f03f3a9325](https://linux-hardware.org/?probe=f03f3a9325) | Nov 29, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [9f473cbdeb](https://linux-hardware.org/?probe=9f473cbdeb) | Nov 29, 2022 |
| HP            | ProBook 440 G5              | [45097ff070](https://linux-hardware.org/?probe=45097ff070) | Nov 29, 2022 |
| Dell          | XPS 15 9500                 | [9c87ab493e](https://linux-hardware.org/?probe=9c87ab493e) | Nov 29, 2022 |
| Lenovo        | G565 20071                  | [659a9a89b9](https://linux-hardware.org/?probe=659a9a89b9) | Nov 28, 2022 |
| Timi          | TM1701                      | [64ee057496](https://linux-hardware.org/?probe=64ee057496) | Nov 28, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [a3c2004787](https://linux-hardware.org/?probe=a3c2004787) | Nov 28, 2022 |
| Acer          | Aspire ES1-522              | [114c1d0914](https://linux-hardware.org/?probe=114c1d0914) | Nov 28, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [4fbe923ad2](https://linux-hardware.org/?probe=4fbe923ad2) | Nov 28, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [e117f07f42](https://linux-hardware.org/?probe=e117f07f42) | Nov 28, 2022 |
| ASUSTek       | GL752VW                     | [edc0678b85](https://linux-hardware.org/?probe=edc0678b85) | Nov 28, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [ddb1791ff6](https://linux-hardware.org/?probe=ddb1791ff6) | Nov 28, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [901fa6e871](https://linux-hardware.org/?probe=901fa6e871) | Nov 28, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IV... | [86f58e68b6](https://linux-hardware.org/?probe=86f58e68b6) | Nov 28, 2022 |
| Lenovo        | ThinkPad L540 20AVA07BJP    | [cfc9d5c8a2](https://linux-hardware.org/?probe=cfc9d5c8a2) | Nov 27, 2022 |
| HUAWEI        | RLEF-XX                     | [bb5c736032](https://linux-hardware.org/?probe=bb5c736032) | Nov 27, 2022 |
| Quanta        | JW6H                        | [12c85e1c14](https://linux-hardware.org/?probe=12c85e1c14) | Nov 27, 2022 |
| HUAWEI        | KLVL-WXXW                   | [7e65f428cc](https://linux-hardware.org/?probe=7e65f428cc) | Nov 27, 2022 |
| HP            | ENVY 17                     | [4a784f4642](https://linux-hardware.org/?probe=4a784f4642) | Nov 27, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [d9ae3d1795](https://linux-hardware.org/?probe=d9ae3d1795) | Nov 27, 2022 |
| Unknown       | Unknown                     | [9e16a80342](https://linux-hardware.org/?probe=9e16a80342) | Nov 27, 2022 |
| HP            | Notebook                    | [4ff28b891c](https://linux-hardware.org/?probe=4ff28b891c) | Nov 27, 2022 |
| HP            | Pavilion g6                 | [c5f8f3f82b](https://linux-hardware.org/?probe=c5f8f3f82b) | Nov 26, 2022 |
| Acer          | TravelMate 4200             | [14b60c4afa](https://linux-hardware.org/?probe=14b60c4afa) | Nov 26, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [74fcf5cb22](https://linux-hardware.org/?probe=74fcf5cb22) | Nov 26, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [a4dbfc0da9](https://linux-hardware.org/?probe=a4dbfc0da9) | Nov 26, 2022 |
| Acer          | Aspire 5733Z                | [7fc415db1f](https://linux-hardware.org/?probe=7fc415db1f) | Nov 26, 2022 |
| Sony          | VGN-P31ZRK_G                | [3c0c707fd4](https://linux-hardware.org/?probe=3c0c707fd4) | Nov 26, 2022 |
| Chuwi         | CoreBook X                  | [f0e76c8866](https://linux-hardware.org/?probe=f0e76c8866) | Nov 26, 2022 |
| HP            | Laptop 14s-dq1xxx           | [9b3a058fda](https://linux-hardware.org/?probe=9b3a058fda) | Nov 26, 2022 |
| MACHENIKE     | MACHCREATOR-16              | [15d49eb71a](https://linux-hardware.org/?probe=15d49eb71a) | Nov 26, 2022 |
| Lenovo        | Legion R9000P ARH7H 82RG    | [0e3f081937](https://linux-hardware.org/?probe=0e3f081937) | Nov 26, 2022 |
| HUAWEI        | MRGF-XX                     | [f60090b407](https://linux-hardware.org/?probe=f60090b407) | Nov 26, 2022 |
| HP            | Notebook                    | [6a8992e3ee](https://linux-hardware.org/?probe=6a8992e3ee) | Nov 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [52da79e88f](https://linux-hardware.org/?probe=52da79e88f) | Nov 25, 2022 |
| Acer          | Aspire E1-570G              | [9c2f530d6a](https://linux-hardware.org/?probe=9c2f530d6a) | Nov 25, 2022 |
| Insyde        | CherryTrail                 | [f7728857e6](https://linux-hardware.org/?probe=f7728857e6) | Nov 25, 2022 |
| HP            | Pavilion g7                 | [9b84cb2362](https://linux-hardware.org/?probe=9b84cb2362) | Nov 25, 2022 |
| ASUSTek       | GL752VW                     | [2dfd7f3926](https://linux-hardware.org/?probe=2dfd7f3926) | Nov 25, 2022 |
| DEPO Compu... | DPC156                      | [9607de1a9c](https://linux-hardware.org/?probe=9607de1a9c) | Nov 25, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [4a758bfcc8](https://linux-hardware.org/?probe=4a758bfcc8) | Nov 25, 2022 |
| Lenovo        | IdeaPad Y580 20132          | [41fc6614f7](https://linux-hardware.org/?probe=41fc6614f7) | Nov 25, 2022 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | [0bb72a6a2a](https://linux-hardware.org/?probe=0bb72a6a2a) | Nov 25, 2022 |
| HUAWEI        | KLVD-WXX9                   | [04b855bde5](https://linux-hardware.org/?probe=04b855bde5) | Nov 25, 2022 |
| Apple         | MacBookPro9,2               | [44b8a68c63](https://linux-hardware.org/?probe=44b8a68c63) | Nov 24, 2022 |
| Lenovo        | B590 20208                  | [9f49ff06cf](https://linux-hardware.org/?probe=9f49ff06cf) | Nov 24, 2022 |
| MSI           | GE72 6QC                    | [07084dd8f9](https://linux-hardware.org/?probe=07084dd8f9) | Nov 24, 2022 |
| Clevo         | NL41MU2                     | [0736d8a48f](https://linux-hardware.org/?probe=0736d8a48f) | Nov 24, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [600e3f0f09](https://linux-hardware.org/?probe=600e3f0f09) | Nov 24, 2022 |
| Panasonic     | CF-C2CH2CBMG                | [cf87bdba01](https://linux-hardware.org/?probe=cf87bdba01) | Nov 24, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [ff3d0a1ecf](https://linux-hardware.org/?probe=ff3d0a1ecf) | Nov 24, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [f86569d54b](https://linux-hardware.org/?probe=f86569d54b) | Nov 24, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [299634697d](https://linux-hardware.org/?probe=299634697d) | Nov 24, 2022 |
| Unknown       | Unknown                     | [9b50d75b30](https://linux-hardware.org/?probe=9b50d75b30) | Nov 24, 2022 |
| Aquarius      | NS685U R11                  | [866e6d043c](https://linux-hardware.org/?probe=866e6d043c) | Nov 24, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | [a31935f117](https://linux-hardware.org/?probe=a31935f117) | Nov 24, 2022 |
| Aquarius      | NS585                       | [d54530cbcb](https://linux-hardware.org/?probe=d54530cbcb) | Nov 24, 2022 |
| Aquarius      | NS585                       | [64d9bcbcde](https://linux-hardware.org/?probe=64d9bcbcde) | Nov 24, 2022 |
| Aquarius      | NS685U R11                  | [0a9856bad0](https://linux-hardware.org/?probe=0a9856bad0) | Nov 24, 2022 |
| HUAWEI        | KLVD-WXX9                   | [97b1b927ba](https://linux-hardware.org/?probe=97b1b927ba) | Nov 23, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [66fca8e108](https://linux-hardware.org/?probe=66fca8e108) | Nov 23, 2022 |
| ASUSTek       | A9T                         | [9ce7b8b3e1](https://linux-hardware.org/?probe=9ce7b8b3e1) | Nov 23, 2022 |
| HP            | Notebook                    | [f81a524d22](https://linux-hardware.org/?probe=f81a524d22) | Nov 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | [028a796420](https://linux-hardware.org/?probe=028a796420) | Nov 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | [c48ab2a2d5](https://linux-hardware.org/?probe=c48ab2a2d5) | Nov 23, 2022 |
| HP            | Laptop 15-dw3xxx            | [fbf991818d](https://linux-hardware.org/?probe=fbf991818d) | Nov 23, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [2485671def](https://linux-hardware.org/?probe=2485671def) | Nov 23, 2022 |
| Toshiba       | Satellite U300              | [f24a55abbf](https://linux-hardware.org/?probe=f24a55abbf) | Nov 23, 2022 |
| MSI           | MS-N051                     | [efb37aedbe](https://linux-hardware.org/?probe=efb37aedbe) | Nov 22, 2022 |
| Timi          | TM1701                      | [3d9c04ccd6](https://linux-hardware.org/?probe=3d9c04ccd6) | Nov 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [ab91a099a5](https://linux-hardware.org/?probe=ab91a099a5) | Nov 22, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [149f57ad9c](https://linux-hardware.org/?probe=149f57ad9c) | Nov 22, 2022 |
| Acer          | Aspire V3-771               | [c0a3895ac4](https://linux-hardware.org/?probe=c0a3895ac4) | Nov 22, 2022 |
| Sony          | VGN-TZ3RXN_B                | [5986f007c8](https://linux-hardware.org/?probe=5986f007c8) | Nov 22, 2022 |
| Unknown       | Wiren Board rev. 7.3.1 (... | [1f9ccab914](https://linux-hardware.org/?probe=1f9ccab914) | Nov 22, 2022 |
| Acer          | Extensa 4220                | [af778b2ec9](https://linux-hardware.org/?probe=af778b2ec9) | Nov 22, 2022 |
| Acer          | Extensa 4220                | [04187e0d6e](https://linux-hardware.org/?probe=04187e0d6e) | Nov 22, 2022 |
| HP            | Pavilion Sleekbook 15       | [add4f71bc0](https://linux-hardware.org/?probe=add4f71bc0) | Nov 22, 2022 |
| Dell          | Studio 1558                 | [ef9a6b217c](https://linux-hardware.org/?probe=ef9a6b217c) | Nov 22, 2022 |
| HP            | ENVY 6                      | [feb348843e](https://linux-hardware.org/?probe=feb348843e) | Nov 22, 2022 |
| Notebook      | W65_67SF                    | [91f6aa0bfb](https://linux-hardware.org/?probe=91f6aa0bfb) | Nov 22, 2022 |
| Acer          | Predator PH315-55           | [f411f75743](https://linux-hardware.org/?probe=f411f75743) | Nov 22, 2022 |
| Acer          | Aspire 5940                 | [33325564e7](https://linux-hardware.org/?probe=33325564e7) | Nov 22, 2022 |
| Samsung       | SR70S/SR71S                 | [27c34cd9df](https://linux-hardware.org/?probe=27c34cd9df) | Nov 22, 2022 |
| Samsung       | SR70S/SR71S                 | [2e1f6c73da](https://linux-hardware.org/?probe=2e1f6c73da) | Nov 22, 2022 |
| ASUSTek       | K53SD                       | [c127a0db71](https://linux-hardware.org/?probe=c127a0db71) | Nov 21, 2022 |
| Acer          | TravelMate 5760             | [54c460334e](https://linux-hardware.org/?probe=54c460334e) | Nov 21, 2022 |
| HP            | 8540w                       | [3712bfe3cb](https://linux-hardware.org/?probe=3712bfe3cb) | Nov 21, 2022 |
| ASUSTek       | S3N                         | [e4c4a500b8](https://linux-hardware.org/?probe=e4c4a500b8) | Nov 21, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [b58bad1779](https://linux-hardware.org/?probe=b58bad1779) | Nov 21, 2022 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | [ed6bb8845a](https://linux-hardware.org/?probe=ed6bb8845a) | Nov 21, 2022 |
| Acer          | Extensa 2519                | [1ab63c7353](https://linux-hardware.org/?probe=1ab63c7353) | Nov 21, 2022 |
| Lenovo        | B590 20206                  | [7d8faca25a](https://linux-hardware.org/?probe=7d8faca25a) | Nov 21, 2022 |
| Lenovo        | G50-30 80G0                 | [be4f638bc7](https://linux-hardware.org/?probe=be4f638bc7) | Nov 21, 2022 |
| Lenovo        | Legion 5 17IMH05H 81Y8      | [b74040cd21](https://linux-hardware.org/?probe=b74040cd21) | Nov 21, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [60c1698203](https://linux-hardware.org/?probe=60c1698203) | Nov 21, 2022 |
| HP            | Pavilion Laptop 14-ce2xx... | [0e9d717db2](https://linux-hardware.org/?probe=0e9d717db2) | Nov 21, 2022 |
| HUAWEI        | CREM-WXX9                   | [9630927dc1](https://linux-hardware.org/?probe=9630927dc1) | Nov 20, 2022 |
| HP            | Notebook                    | [c8bac5b72d](https://linux-hardware.org/?probe=c8bac5b72d) | Nov 20, 2022 |
| Acer          | Extensa 2519                | [fc5526a30f](https://linux-hardware.org/?probe=fc5526a30f) | Nov 20, 2022 |
| Acer          | Extensa 2519                | [5ae619eb32](https://linux-hardware.org/?probe=5ae619eb32) | Nov 20, 2022 |
| Acer          | Extensa 2540                | [2cd32708f2](https://linux-hardware.org/?probe=2cd32708f2) | Nov 20, 2022 |
| HP            | Compaq nx9020 (PG641ES#A... | [ba63296d55](https://linux-hardware.org/?probe=ba63296d55) | Nov 20, 2022 |
| Irbis         | NB254                       | [ffa6638fe9](https://linux-hardware.org/?probe=ffa6638fe9) | Nov 20, 2022 |
| ASUSTek       | X550CC                      | [a2eae9195c](https://linux-hardware.org/?probe=a2eae9195c) | Nov 20, 2022 |
| Lenovo        | G560 20042                  | [e2ea91a4ca](https://linux-hardware.org/?probe=e2ea91a4ca) | Nov 20, 2022 |
| ASUSTek       | F5VL                        | [05614f05b7](https://linux-hardware.org/?probe=05614f05b7) | Nov 20, 2022 |
| ASUSTek       | F5VL                        | [a95f905ff3](https://linux-hardware.org/?probe=a95f905ff3) | Nov 20, 2022 |
| Acer          | Aspire E5-771G              | [5099a55836](https://linux-hardware.org/?probe=5099a55836) | Nov 20, 2022 |
| HUAWEI        | KLVL-WXXW                   | [206a1fe0c7](https://linux-hardware.org/?probe=206a1fe0c7) | Nov 20, 2022 |
| HUAWEI        | KLVL-WXXW                   | [9208bbd2b8](https://linux-hardware.org/?probe=9208bbd2b8) | Nov 20, 2022 |
| Chuwi         | LarkBook                    | [bef3087526](https://linux-hardware.org/?probe=bef3087526) | Nov 20, 2022 |
| Pegatron      | A15                         | [dea0a0c81e](https://linux-hardware.org/?probe=dea0a0c81e) | Nov 20, 2022 |
| Acer          | Aspire 5750G                | [8b000b014f](https://linux-hardware.org/?probe=8b000b014f) | Nov 20, 2022 |
| HUAWEI        | NBD-WXX9                    | [bd18dfe05f](https://linux-hardware.org/?probe=bd18dfe05f) | Nov 20, 2022 |
| Irbis         | NB121                       | [32a784f767](https://linux-hardware.org/?probe=32a784f767) | Nov 20, 2022 |
| HUAWEI        | CREM-WXX9                   | [f9b8181279](https://linux-hardware.org/?probe=f9b8181279) | Nov 19, 2022 |
| Acer          | Aspire A515-44G             | [51035e77a1](https://linux-hardware.org/?probe=51035e77a1) | Nov 19, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [5605c0fd97](https://linux-hardware.org/?probe=5605c0fd97) | Nov 19, 2022 |
| Aquarius      | NS585                       | [a0bc8d3f44](https://linux-hardware.org/?probe=a0bc8d3f44) | Nov 19, 2022 |
| Acer          | Aspire ES1-533              | [8c080caac2](https://linux-hardware.org/?probe=8c080caac2) | Nov 19, 2022 |
| Digma         | EVE 15 C423 ES5069EW        | [9737dae1ac](https://linux-hardware.org/?probe=9737dae1ac) | Nov 19, 2022 |
| ASUSTek       | K53SD                       | [7620fe2bdd](https://linux-hardware.org/?probe=7620fe2bdd) | Nov 19, 2022 |
| ALLDOCUBE     | i1405S                      | [551bc2b1e6](https://linux-hardware.org/?probe=551bc2b1e6) | Nov 19, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [87d8a1ee6b](https://linux-hardware.org/?probe=87d8a1ee6b) | Nov 19, 2022 |
| ASUSTek       | M80TA                       | [d2427d8942](https://linux-hardware.org/?probe=d2427d8942) | Nov 18, 2022 |
| Dell          | Inspiron 1525               | [3e09380a65](https://linux-hardware.org/?probe=3e09380a65) | Nov 18, 2022 |
| Dell          | Inspiron 3793               | [fb5878b057](https://linux-hardware.org/?probe=fb5878b057) | Nov 18, 2022 |
| Haier         | U1520HD                     | [7a9c0df4f1](https://linux-hardware.org/?probe=7a9c0df4f1) | Nov 18, 2022 |
| HUAWEI        | NBD-WXX9                    | [a54f42b51e](https://linux-hardware.org/?probe=a54f42b51e) | Nov 18, 2022 |
| Digma         | EVE 15 C423 ES5069EW        | [57cd27008a](https://linux-hardware.org/?probe=57cd27008a) | Nov 18, 2022 |
| HUAWEI        | NBD-WXX9                    | [faa0deab8f](https://linux-hardware.org/?probe=faa0deab8f) | Nov 18, 2022 |
| HUAWEI        | BOD-WXX9                    | [9984093912](https://linux-hardware.org/?probe=9984093912) | Nov 18, 2022 |
| Lenovo        | B475 Sabine                 | [5be5a7cd5f](https://linux-hardware.org/?probe=5be5a7cd5f) | Nov 17, 2022 |
| ASUSTek       | K54HR                       | [ba95174feb](https://linux-hardware.org/?probe=ba95174feb) | Nov 17, 2022 |
| Acer          | Aspire V3-371               | [b184d85960](https://linux-hardware.org/?probe=b184d85960) | Nov 17, 2022 |
| Dell          | Inspiron N5010              | [8a94d169c5](https://linux-hardware.org/?probe=8a94d169c5) | Nov 17, 2022 |
| Dell          | Inspiron N5010              | [fbe52d681e](https://linux-hardware.org/?probe=fbe52d681e) | Nov 17, 2022 |
| Acer          | Aspire ES1-511              | [0754a5633d](https://linux-hardware.org/?probe=0754a5633d) | Nov 16, 2022 |
| Timi          | TM1701                      | [e77b655bb8](https://linux-hardware.org/?probe=e77b655bb8) | Nov 16, 2022 |
| ASUSTek       | X507UA                      | [9a2fe77bac](https://linux-hardware.org/?probe=9a2fe77bac) | Nov 16, 2022 |
| Unknown       | Unknown                     | [f3222cf843](https://linux-hardware.org/?probe=f3222cf843) | Nov 16, 2022 |
| Unknown       | Unknown                     | [9217d900c4](https://linux-hardware.org/?probe=9217d900c4) | Nov 16, 2022 |
| HUAWEI        | NBD-WXX9                    | [72ebef559b](https://linux-hardware.org/?probe=72ebef559b) | Nov 16, 2022 |
| Unknown       | Unknown                     | [a86465b0f3](https://linux-hardware.org/?probe=a86465b0f3) | Nov 16, 2022 |
| ALLDOCUBE     | i1405S                      | [f35dc553a2](https://linux-hardware.org/?probe=f35dc553a2) | Nov 16, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [f8eb11ba08](https://linux-hardware.org/?probe=f8eb11ba08) | Nov 15, 2022 |
| Lenovo        | V14 G2 ALC 82KC             | [cf10680f5f](https://linux-hardware.org/?probe=cf10680f5f) | Nov 15, 2022 |
| Lenovo        | G50-30 80G0                 | [b870eb1d72](https://linux-hardware.org/?probe=b870eb1d72) | Nov 15, 2022 |
| Dell          | Inspiron 5558               | [0674cb5916](https://linux-hardware.org/?probe=0674cb5916) | Nov 15, 2022 |
| HONOR         | HYM-WXX                     | [5cf42c99ef](https://linux-hardware.org/?probe=5cf42c99ef) | Nov 15, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [b59bffff0b](https://linux-hardware.org/?probe=b59bffff0b) | Nov 15, 2022 |
| Kraftway      | ACCORD                      | [7021cedadf](https://linux-hardware.org/?probe=7021cedadf) | Nov 15, 2022 |
| HONOR         | HYM-WXX                     | [a6812ad12e](https://linux-hardware.org/?probe=a6812ad12e) | Nov 15, 2022 |
| Samsung       | NC210/NC110                 | [31ebbfaf58](https://linux-hardware.org/?probe=31ebbfaf58) | Nov 15, 2022 |
| MSI           | Katana GF76 11SC            | [1b11541cd7](https://linux-hardware.org/?probe=1b11541cd7) | Nov 15, 2022 |
| Toshiba       | Satellite A300D             | [c5dc216e31](https://linux-hardware.org/?probe=c5dc216e31) | Nov 15, 2022 |
| Toshiba       | Satellite A300D             | [21952b8d66](https://linux-hardware.org/?probe=21952b8d66) | Nov 15, 2022 |
| HP            | Mini 110-3700               | [4e9f54f23c](https://linux-hardware.org/?probe=4e9f54f23c) | Nov 15, 2022 |
| Acer          | Aspire ES1-512              | [5802f0db59](https://linux-hardware.org/?probe=5802f0db59) | Nov 15, 2022 |
| HP            | Mini 110-3700               | [8ca62a1880](https://linux-hardware.org/?probe=8ca62a1880) | Nov 15, 2022 |
| MSI           | Modern 15 B11M              | [0ae136622d](https://linux-hardware.org/?probe=0ae136622d) | Nov 14, 2022 |
| ASUSTek       | N53SV                       | [f42473e3f6](https://linux-hardware.org/?probe=f42473e3f6) | Nov 14, 2022 |
| ASUSTek       | X502CA                      | [b47b397c38](https://linux-hardware.org/?probe=b47b397c38) | Nov 14, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [100714ed23](https://linux-hardware.org/?probe=100714ed23) | Nov 14, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [e6ef3b56eb](https://linux-hardware.org/?probe=e6ef3b56eb) | Nov 14, 2022 |
| HP            | ENVY m6                     | [4397c54e20](https://linux-hardware.org/?probe=4397c54e20) | Nov 14, 2022 |
| ASUSTek       | K42DY                       | [f7a61f85d9](https://linux-hardware.org/?probe=f7a61f85d9) | Nov 14, 2022 |
| Lenovo        | G550 20023                  | [80be7e8e25](https://linux-hardware.org/?probe=80be7e8e25) | Nov 14, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [1de723e880](https://linux-hardware.org/?probe=1de723e880) | Nov 14, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [233791ab06](https://linux-hardware.org/?probe=233791ab06) | Nov 14, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [34a5f361bd](https://linux-hardware.org/?probe=34a5f361bd) | Nov 14, 2022 |
| Fujitsu       | LIFEBOOK U938               | [428ad6215c](https://linux-hardware.org/?probe=428ad6215c) | Nov 14, 2022 |
| MSI           | GT72 2QD                    | [cbd0b88f5f](https://linux-hardware.org/?probe=cbd0b88f5f) | Nov 14, 2022 |
| MSI           | GT72 2QD                    | [0e9a1a51a5](https://linux-hardware.org/?probe=0e9a1a51a5) | Nov 14, 2022 |
| ASUSTek       | N50Vc                       | [36b3155007](https://linux-hardware.org/?probe=36b3155007) | Nov 13, 2022 |
| ASUSTek       | K53SM                       | [297194e8e4](https://linux-hardware.org/?probe=297194e8e4) | Nov 13, 2022 |
| Chuwi         | LarkBook                    | [8c33c61e14](https://linux-hardware.org/?probe=8c33c61e14) | Nov 13, 2022 |
| HUAWEI        | MACHD-WXX9                  | [91e169c039](https://linux-hardware.org/?probe=91e169c039) | Nov 13, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [6e9bc709d9](https://linux-hardware.org/?probe=6e9bc709d9) | Nov 13, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [49162725d5](https://linux-hardware.org/?probe=49162725d5) | Nov 13, 2022 |
| Sony          | SVE1512H1RW                 | [032fdf5260](https://linux-hardware.org/?probe=032fdf5260) | Nov 13, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [e8e7b815c4](https://linux-hardware.org/?probe=e8e7b815c4) | Nov 13, 2022 |
| Lenovo        | B590 20208                  | [af898e0d66](https://linux-hardware.org/?probe=af898e0d66) | Nov 13, 2022 |
| Acer          | Aspire 5720Z                | [264c30fac3](https://linux-hardware.org/?probe=264c30fac3) | Nov 13, 2022 |
| Acer          | Aspire 5720Z                | [6e596d88da](https://linux-hardware.org/?probe=6e596d88da) | Nov 12, 2022 |
| HONOR         | BOD-WXX9                    | [ca8b207b30](https://linux-hardware.org/?probe=ca8b207b30) | Nov 12, 2022 |
| Dell          | Inspiron 3521               | [10482f151a](https://linux-hardware.org/?probe=10482f151a) | Nov 12, 2022 |
| Dell          | Inspiron 3521               | [5f20ed2dd2](https://linux-hardware.org/?probe=5f20ed2dd2) | Nov 12, 2022 |
| Acer          | Aspire 3830TG               | [2ce4863890](https://linux-hardware.org/?probe=2ce4863890) | Nov 12, 2022 |
| HP            | Compaq nc6120 (PY507EA#A... | [a4c594d8db](https://linux-hardware.org/?probe=a4c594d8db) | Nov 12, 2022 |
| Gigabyte      | G5 KE                       | [aefbee04fd](https://linux-hardware.org/?probe=aefbee04fd) | Nov 12, 2022 |
| Acer          | Acadia V1.45                | [c6a91498cc](https://linux-hardware.org/?probe=c6a91498cc) | Nov 12, 2022 |
| Samsung       | R425D/R525D                 | [85d17374e7](https://linux-hardware.org/?probe=85d17374e7) | Nov 12, 2022 |
| Acer          | Swift SF314-43              | [1243c9795a](https://linux-hardware.org/?probe=1243c9795a) | Nov 12, 2022 |
| ASUSTek       | K53BR                       | [15838034f5](https://linux-hardware.org/?probe=15838034f5) | Nov 12, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [4838271135](https://linux-hardware.org/?probe=4838271135) | Nov 11, 2022 |
| Acer          | Acadia V1.19                | [f43450e9d4](https://linux-hardware.org/?probe=f43450e9d4) | Nov 11, 2022 |
| Lenovo        | ThinkPad X220 4290RB3       | [37959973aa](https://linux-hardware.org/?probe=37959973aa) | Nov 11, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [cbd9e440a6](https://linux-hardware.org/?probe=cbd9e440a6) | Nov 11, 2022 |
| Acer          | Aspire E5-573               | [b8b0c9fae3](https://linux-hardware.org/?probe=b8b0c9fae3) | Nov 11, 2022 |
| NCA Group     | iRU_Notebook                | [6d22b3942e](https://linux-hardware.org/?probe=6d22b3942e) | Nov 11, 2022 |
| Gigabyte      | U24                         | [c0bf41df22](https://linux-hardware.org/?probe=c0bf41df22) | Nov 11, 2022 |
| Clevo         | NL41MU2                     | [65226dd80a](https://linux-hardware.org/?probe=65226dd80a) | Nov 11, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [68e5509696](https://linux-hardware.org/?probe=68e5509696) | Nov 11, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [1681f97433](https://linux-hardware.org/?probe=1681f97433) | Nov 11, 2022 |
| Clevo         | NL41MU2                     | [a25dd1174c](https://linux-hardware.org/?probe=a25dd1174c) | Nov 11, 2022 |
| Samsung       | R519/R719                   | [31260d4616](https://linux-hardware.org/?probe=31260d4616) | Nov 11, 2022 |
| HUAWEI        | BOD-WXX9                    | [2e79d44f43](https://linux-hardware.org/?probe=2e79d44f43) | Nov 11, 2022 |
| ASUSTek       | K50IE                       | [4bd91fccfa](https://linux-hardware.org/?probe=4bd91fccfa) | Nov 11, 2022 |
| Sony          | VPCEH3J1R                   | [4944a2e287](https://linux-hardware.org/?probe=4944a2e287) | Nov 11, 2022 |
| HP            | Pavilion g6                 | [fc422ba1a4](https://linux-hardware.org/?probe=fc422ba1a4) | Nov 11, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [7827dd0f86](https://linux-hardware.org/?probe=7827dd0f86) | Nov 11, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [64d896b971](https://linux-hardware.org/?probe=64d896b971) | Nov 11, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [139c944b07](https://linux-hardware.org/?probe=139c944b07) | Nov 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [f56dc1af6b](https://linux-hardware.org/?probe=f56dc1af6b) | Nov 10, 2022 |
| Acer          | Aspire V5-572G              | [bd537cc78c](https://linux-hardware.org/?probe=bd537cc78c) | Nov 10, 2022 |
| Sony          | VPCS11V9R                   | [a0b4bf7869](https://linux-hardware.org/?probe=a0b4bf7869) | Nov 10, 2022 |
| Lenovo        | G50-30 80G0                 | [1e0c308a85](https://linux-hardware.org/?probe=1e0c308a85) | Nov 10, 2022 |
| Acer          | TravelMate 6292             | [c7dcad2d0f](https://linux-hardware.org/?probe=c7dcad2d0f) | Nov 10, 2022 |
| HP            | Pavilion g6                 | [e2a0a47587](https://linux-hardware.org/?probe=e2a0a47587) | Nov 10, 2022 |
| ASUSTek       | K50IE                       | [5176f404f1](https://linux-hardware.org/?probe=5176f404f1) | Nov 10, 2022 |
| Valve         | Jupiter                     | [34582d82a1](https://linux-hardware.org/?probe=34582d82a1) | Nov 10, 2022 |
| ASUSTek       | G50VT                       | [57f7e69b18](https://linux-hardware.org/?probe=57f7e69b18) | Nov 10, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | [26989a0d39](https://linux-hardware.org/?probe=26989a0d39) | Nov 10, 2022 |
| HP            | Laptop 14s-dq3xxx           | [2da4055f76](https://linux-hardware.org/?probe=2da4055f76) | Nov 09, 2022 |
| ASUSTek       | K501UB                      | [c0f4434ec3](https://linux-hardware.org/?probe=c0f4434ec3) | Nov 09, 2022 |
| Lenovo        | E31-70 80KX                 | [61343c5ca1](https://linux-hardware.org/?probe=61343c5ca1) | Nov 09, 2022 |
| MSI           | Katana GF76 11SC            | [7e2ff6fc67](https://linux-hardware.org/?probe=7e2ff6fc67) | Nov 09, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [3fd33e6782](https://linux-hardware.org/?probe=3fd33e6782) | Nov 09, 2022 |
| ASUSTek       | X507UB                      | [2790049313](https://linux-hardware.org/?probe=2790049313) | Nov 09, 2022 |
| Timi          | RedmiBook Pro 15S           | [02b3508a99](https://linux-hardware.org/?probe=02b3508a99) | Nov 09, 2022 |
| MSI           | GE70 2PL                    | [d09e002aa8](https://linux-hardware.org/?probe=d09e002aa8) | Nov 09, 2022 |
| Infinix       | INBOOK X2                   | [d342b7930f](https://linux-hardware.org/?probe=d342b7930f) | Nov 09, 2022 |
| ASUSTek       | X550CC                      | [46dd8a0416](https://linux-hardware.org/?probe=46dd8a0416) | Nov 08, 2022 |
| ASUSTek       | U24E                        | [a51fe3226f](https://linux-hardware.org/?probe=a51fe3226f) | Nov 08, 2022 |
| MSI           | GE70 2PL                    | [8752dacd05](https://linux-hardware.org/?probe=8752dacd05) | Nov 08, 2022 |
| Acer          | Nitro AN517-52              | [3a2bb9e1e9](https://linux-hardware.org/?probe=3a2bb9e1e9) | Nov 08, 2022 |
| Acer          | Aspire E5-573G              | [b6a1f08748](https://linux-hardware.org/?probe=b6a1f08748) | Nov 08, 2022 |
| Aquarius      | NS585                       | [9b20fcc4b8](https://linux-hardware.org/?probe=9b20fcc4b8) | Nov 08, 2022 |
| HP            | EliteBook 2540p             | [515cdf3f6c](https://linux-hardware.org/?probe=515cdf3f6c) | Nov 08, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [ba8145934d](https://linux-hardware.org/?probe=ba8145934d) | Nov 07, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [95b5d8b8ca](https://linux-hardware.org/?probe=95b5d8b8ca) | Nov 07, 2022 |
| Gigabyte      | U24                         | [a9d03e590b](https://linux-hardware.org/?probe=a9d03e590b) | Nov 07, 2022 |
| Acer          | Aspire A315-41              | [df6426eef5](https://linux-hardware.org/?probe=df6426eef5) | Nov 07, 2022 |
| Acer          | Aspire A315-41              | [bae4adcff9](https://linux-hardware.org/?probe=bae4adcff9) | Nov 07, 2022 |
| Toshiba       | Satellite C660              | [5e972fdb95](https://linux-hardware.org/?probe=5e972fdb95) | Nov 07, 2022 |
| HP            | Pavilion g6                 | [9992a08641](https://linux-hardware.org/?probe=9992a08641) | Nov 07, 2022 |
| Toshiba       | Satellite C660              | [e75f44efd0](https://linux-hardware.org/?probe=e75f44efd0) | Nov 07, 2022 |
| eMachines     | eM350                       | [ac6dda5ddb](https://linux-hardware.org/?probe=ac6dda5ddb) | Nov 07, 2022 |
| Acer          | Aspire VN7-591G             | [541d3bfeca](https://linux-hardware.org/?probe=541d3bfeca) | Nov 07, 2022 |
| Sony          | VPCZ13S9R                   | [9a0f47ed25](https://linux-hardware.org/?probe=9a0f47ed25) | Nov 07, 2022 |
| HP            | ProBook 430 G5              | [e362ce5bdf](https://linux-hardware.org/?probe=e362ce5bdf) | Nov 07, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [614a486442](https://linux-hardware.org/?probe=614a486442) | Nov 07, 2022 |
| Acer          | TravelMate 5760             | [f645b36a78](https://linux-hardware.org/?probe=f645b36a78) | Nov 07, 2022 |
| Dell          | G3 3579                     | [b793526167](https://linux-hardware.org/?probe=b793526167) | Nov 06, 2022 |
| Lenovo        | ThinkPad T440p 20AN0033R... | [7ca892ad44](https://linux-hardware.org/?probe=7ca892ad44) | Nov 06, 2022 |
| Lenovo        | IdeaPad S145-15API 81UT     | [db56889368](https://linux-hardware.org/?probe=db56889368) | Nov 06, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [d238949b9f](https://linux-hardware.org/?probe=d238949b9f) | Nov 06, 2022 |
| Lenovo        | IdeaPad 3 17ADA05 81W2      | [05ac02550e](https://linux-hardware.org/?probe=05ac02550e) | Nov 06, 2022 |
| DNS           | W9x0LU                      | [2ebfe190c5](https://linux-hardware.org/?probe=2ebfe190c5) | Nov 06, 2022 |
| Samsung       | R510/P510                   | [4921b97206](https://linux-hardware.org/?probe=4921b97206) | Nov 06, 2022 |
| Packard Be... | EasyNote TS11HR             | [19304dd869](https://linux-hardware.org/?probe=19304dd869) | Nov 06, 2022 |
| Acer          | Aspire A317-52              | [e9ed162010](https://linux-hardware.org/?probe=e9ed162010) | Nov 06, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y3A... | [d53e6cef83](https://linux-hardware.org/?probe=d53e6cef83) | Nov 06, 2022 |
| Toshiba       | Satellite L550              | [3b95d22100](https://linux-hardware.org/?probe=3b95d22100) | Nov 06, 2022 |
| Dell          | Studio 1558                 | [8b5cb100a8](https://linux-hardware.org/?probe=8b5cb100a8) | Nov 05, 2022 |
| Acer          | Nitro AN515-42              | [a89bc09dca](https://linux-hardware.org/?probe=a89bc09dca) | Nov 05, 2022 |
| Lenovo        | V14-ADA 82C6                | [92be197f2d](https://linux-hardware.org/?probe=92be197f2d) | Nov 05, 2022 |
| ASUSTek       | N76VB                       | [c46794ba60](https://linux-hardware.org/?probe=c46794ba60) | Nov 05, 2022 |
| Fujitsu Si... | AMILO Pro V3205             | [7a03ef6ae1](https://linux-hardware.org/?probe=7a03ef6ae1) | Nov 05, 2022 |
| Dell          | Inspiron N5110              | [698596bd58](https://linux-hardware.org/?probe=698596bd58) | Nov 05, 2022 |
| HP            | Pavilion dv7                | [d17019e1f7](https://linux-hardware.org/?probe=d17019e1f7) | Nov 05, 2022 |
| Apple         | MacBookPro5,5               | [cc051268d8](https://linux-hardware.org/?probe=cc051268d8) | Nov 05, 2022 |
| ASUSTek       | N56VJ                       | [1685737249](https://linux-hardware.org/?probe=1685737249) | Nov 05, 2022 |
| Pretech       | EVE 1801 3G ES1049EG        | [19205fc20b](https://linux-hardware.org/?probe=19205fc20b) | Nov 04, 2022 |
| ASUSTek       | F5N                         | [f1efa34bf8](https://linux-hardware.org/?probe=f1efa34bf8) | Nov 04, 2022 |
| ASUSTek       | X75VD                       | [60e91d212e](https://linux-hardware.org/?probe=60e91d212e) | Nov 04, 2022 |
| Lenovo        | B590 20206                  | [6807b6b584](https://linux-hardware.org/?probe=6807b6b584) | Nov 04, 2022 |
| Lenovo        | B590 20206                  | [d0267472d6](https://linux-hardware.org/?probe=d0267472d6) | Nov 04, 2022 |
| Lenovo        | G500 20236                  | [82213a5471](https://linux-hardware.org/?probe=82213a5471) | Nov 04, 2022 |
| ASUSTek       | F5N                         | [8e3878fe4d](https://linux-hardware.org/?probe=8e3878fe4d) | Nov 04, 2022 |
| ASUSTek       | F5N                         | [f95b9890f6](https://linux-hardware.org/?probe=f95b9890f6) | Nov 04, 2022 |
| HUAWEI        | HKD-WXX                     | [7a8f33b5bf](https://linux-hardware.org/?probe=7a8f33b5bf) | Nov 04, 2022 |
| HUAWEI        | BOM-WXX9                    | [d78a7bd1a3](https://linux-hardware.org/?probe=d78a7bd1a3) | Nov 04, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [505b2c2b5d](https://linux-hardware.org/?probe=505b2c2b5d) | Nov 04, 2022 |
| Fujitsu       | LIFEBOOK A512               | [8732711bf0](https://linux-hardware.org/?probe=8732711bf0) | Nov 04, 2022 |
| Packard Be... | EasyNote LX                 | [41070f6bfe](https://linux-hardware.org/?probe=41070f6bfe) | Nov 04, 2022 |
| ASUSTek       | U24E                        | [6303641e69](https://linux-hardware.org/?probe=6303641e69) | Nov 04, 2022 |
| Sony          | VPCEA1S1R                   | [9dfb83587b](https://linux-hardware.org/?probe=9dfb83587b) | Nov 04, 2022 |
| Dell          | Inspiron 3501               | [b487c53dfd](https://linux-hardware.org/?probe=b487c53dfd) | Nov 04, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [f8685beefa](https://linux-hardware.org/?probe=f8685beefa) | Nov 04, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [d7c44d9e94](https://linux-hardware.org/?probe=d7c44d9e94) | Nov 04, 2022 |
| Lenovo        | G580 20157                  | [16cd4b28ce](https://linux-hardware.org/?probe=16cd4b28ce) | Nov 04, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [52a97560d7](https://linux-hardware.org/?probe=52a97560d7) | Nov 03, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [dba14315ca](https://linux-hardware.org/?probe=dba14315ca) | Nov 03, 2022 |
| ASUSTek       | 1215B                       | [eeff579fe6](https://linux-hardware.org/?probe=eeff579fe6) | Nov 03, 2022 |
| ASUSTek       | 1215B                       | [3cc2c5ad48](https://linux-hardware.org/?probe=3cc2c5ad48) | Nov 03, 2022 |
| ASUSTek       | T100TAM                     | [d409557d4b](https://linux-hardware.org/?probe=d409557d4b) | Nov 03, 2022 |
| Valve         | Jupiter                     | [1757bc1f5a](https://linux-hardware.org/?probe=1757bc1f5a) | Nov 03, 2022 |
| Lenovo        | ThinkPad L13 Gen 2 20VH0... | [de1cd69b53](https://linux-hardware.org/?probe=de1cd69b53) | Nov 02, 2022 |
| HP            | ENVY m6                     | [9043724da5](https://linux-hardware.org/?probe=9043724da5) | Nov 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [28d7daff10](https://linux-hardware.org/?probe=28d7daff10) | Nov 02, 2022 |
| Acer          | Nitro AN515-54              | [710ab678b2](https://linux-hardware.org/?probe=710ab678b2) | Nov 02, 2022 |
| Acer          | Aspire A515-54G             | [519fa92199](https://linux-hardware.org/?probe=519fa92199) | Nov 02, 2022 |
| ASUSTek       | 1215B                       | [21694405a9](https://linux-hardware.org/?probe=21694405a9) | Nov 02, 2022 |
| Digma         | EVE 11 C422 ES1068EW        | [f5177de131](https://linux-hardware.org/?probe=f5177de131) | Nov 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [6f89789444](https://linux-hardware.org/?probe=6f89789444) | Nov 02, 2022 |
| ASUSTek       | N53Jg                       | [8e4782c668](https://linux-hardware.org/?probe=8e4782c668) | Nov 01, 2022 |
| Toshiba       | Satellite C660              | [44c6e56cd9](https://linux-hardware.org/?probe=44c6e56cd9) | Nov 01, 2022 |
| Toshiba       | Satellite L755              | [dc3d60731e](https://linux-hardware.org/?probe=dc3d60731e) | Nov 01, 2022 |
| HP            | Laptop 14s-fq0xxx           | [fe23529093](https://linux-hardware.org/?probe=fe23529093) | Nov 01, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [7603f28400](https://linux-hardware.org/?probe=7603f28400) | Nov 01, 2022 |
| Lenovo        | V14-ADA 82C6                | [a54d6876b6](https://linux-hardware.org/?probe=a54d6876b6) | Nov 01, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [406aae2f66](https://linux-hardware.org/?probe=406aae2f66) | Nov 01, 2022 |
| Apple         | MacBookPro8,1               | [da912b99f4](https://linux-hardware.org/?probe=da912b99f4) | Nov 01, 2022 |
| Samsung       | RV410/RV510/S3510/E3510     | [566d83485b](https://linux-hardware.org/?probe=566d83485b) | Oct 31, 2022 |
| HUAWEI        | BOHB-WAX9                   | [274a3383db](https://linux-hardware.org/?probe=274a3383db) | Oct 31, 2022 |
| Acer          | Aspire 5733                 | [bcc1836178](https://linux-hardware.org/?probe=bcc1836178) | Oct 31, 2022 |
| ASUSTek       | K43SJ                       | [778e6caf06](https://linux-hardware.org/?probe=778e6caf06) | Oct 31, 2022 |
| ASUSTek       | X541UVK                     | [15bdbbf952](https://linux-hardware.org/?probe=15bdbbf952) | Oct 31, 2022 |
| Sony          | VGN-AR71MR                  | [4ecd695b12](https://linux-hardware.org/?probe=4ecd695b12) | Oct 31, 2022 |
| ASUSTek       | T100TAM                     | [a2a70b919d](https://linux-hardware.org/?probe=a2a70b919d) | Oct 31, 2022 |
| Aquarius      | NS585                       | [e4b4e0456d](https://linux-hardware.org/?probe=e4b4e0456d) | Oct 31, 2022 |
| Samsung       | RV410/RV510/S3510/E3510     | [073ba962ff](https://linux-hardware.org/?probe=073ba962ff) | Oct 31, 2022 |
| HP            | Laptop 14s-dq3xxx           | [674ced10f2](https://linux-hardware.org/?probe=674ced10f2) | Oct 31, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [a872c9888a](https://linux-hardware.org/?probe=a872c9888a) | Oct 30, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [45f670d99f](https://linux-hardware.org/?probe=45f670d99f) | Oct 30, 2022 |
| MSI           | Sword 15 A11UE              | [c039d4321b](https://linux-hardware.org/?probe=c039d4321b) | Oct 30, 2022 |
| MSI           | Stealth GS77 12UHS          | [8a1d96274e](https://linux-hardware.org/?probe=8a1d96274e) | Oct 30, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [f60d156dd3](https://linux-hardware.org/?probe=f60d156dd3) | Oct 30, 2022 |
| Chuwi         | LarkBook                    | [3ff2ff69ce](https://linux-hardware.org/?probe=3ff2ff69ce) | Oct 30, 2022 |
| HUAWEI        | HLY-WX9XX                   | [4208d513b4](https://linux-hardware.org/?probe=4208d513b4) | Oct 30, 2022 |
| Prestigio     | PSB133S01ZFP                | [e10becbd35](https://linux-hardware.org/?probe=e10becbd35) | Oct 30, 2022 |
| HP            | Pavilion g6                 | [666a829545](https://linux-hardware.org/?probe=666a829545) | Oct 30, 2022 |
| Aquarius      | Cmp NS765                   | [5e519edbee](https://linux-hardware.org/?probe=5e519edbee) | Oct 30, 2022 |
| HIPER         | WORKBOOK                    | [0a3eb12b15](https://linux-hardware.org/?probe=0a3eb12b15) | Oct 30, 2022 |
| Acer          | Nitro AN515-42              | [763e5e0492](https://linux-hardware.org/?probe=763e5e0492) | Oct 29, 2022 |
| Dell          | Vostro 5490                 | [057163f0e4](https://linux-hardware.org/?probe=057163f0e4) | Oct 29, 2022 |
| HP            | Laptop 15-dw3xxx            | [0c281b6b5e](https://linux-hardware.org/?probe=0c281b6b5e) | Oct 29, 2022 |
| ASUSTek       | ZenBook 13 UX310UFR         | [11b52c3e1f](https://linux-hardware.org/?probe=11b52c3e1f) | Oct 29, 2022 |
| Acer          | Nitro AN515-52              | [38570237ac](https://linux-hardware.org/?probe=38570237ac) | Oct 29, 2022 |
| Acer          | Nitro AN515-52              | [5551d222b2](https://linux-hardware.org/?probe=5551d222b2) | Oct 29, 2022 |
| HP            | Laptop 15s-eq2xxx           | [dbd930e552](https://linux-hardware.org/?probe=dbd930e552) | Oct 29, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [d152b0a56c](https://linux-hardware.org/?probe=d152b0a56c) | Oct 29, 2022 |
| HP            | Pavilion dv6                | [6618a8e6ed](https://linux-hardware.org/?probe=6618a8e6ed) | Oct 29, 2022 |
| ASUSTek       | X550DP                      | [b0a52fe296](https://linux-hardware.org/?probe=b0a52fe296) | Oct 29, 2022 |
| Samsung       | 300V3A/300V4A/300V5A        | [4acb2d0863](https://linux-hardware.org/?probe=4acb2d0863) | Oct 29, 2022 |
| ASUSTek       | K50C                        | [af80714f09](https://linux-hardware.org/?probe=af80714f09) | Oct 29, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [0a24d1491a](https://linux-hardware.org/?probe=0a24d1491a) | Oct 29, 2022 |
| ASUSTek       | X541UV                      | [cef88d9d62](https://linux-hardware.org/?probe=cef88d9d62) | Oct 29, 2022 |
| ASUSTek       | K50C                        | [ca606469d8](https://linux-hardware.org/?probe=ca606469d8) | Oct 29, 2022 |
| Toshiba       | Satellite L755              | [0fa70f29d4](https://linux-hardware.org/?probe=0fa70f29d4) | Oct 28, 2022 |
| Prestigio     | PSB141S01                   | [646d3fd287](https://linux-hardware.org/?probe=646d3fd287) | Oct 28, 2022 |
| Lenovo        | B560                        | [f8676b0e49](https://linux-hardware.org/?probe=f8676b0e49) | Oct 28, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [d653658a53](https://linux-hardware.org/?probe=d653658a53) | Oct 28, 2022 |
| ASUSTek       | F3Ka                        | [06235844a1](https://linux-hardware.org/?probe=06235844a1) | Oct 28, 2022 |
| HUAWEI        | BOM-WXX9                    | [203ac0880d](https://linux-hardware.org/?probe=203ac0880d) | Oct 28, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [b9ab6b9cf2](https://linux-hardware.org/?probe=b9ab6b9cf2) | Oct 28, 2022 |
| Dell          | Inspiron 3542               | [a3a24a81fa](https://linux-hardware.org/?probe=a3a24a81fa) | Oct 28, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [6b57390808](https://linux-hardware.org/?probe=6b57390808) | Oct 28, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [26311f56d7](https://linux-hardware.org/?probe=26311f56d7) | Oct 28, 2022 |
| Acer          | Aspire A715-75G             | [78b0c55e62](https://linux-hardware.org/?probe=78b0c55e62) | Oct 28, 2022 |
| MSI           | GP66 Leopard 11UG           | [aec6edc8a0](https://linux-hardware.org/?probe=aec6edc8a0) | Oct 28, 2022 |
| Lenovo        | B560                        | [73a6da1bdc](https://linux-hardware.org/?probe=73a6da1bdc) | Oct 28, 2022 |
| Sony          | VPCCB3S1R                   | [ee5b1465a1](https://linux-hardware.org/?probe=ee5b1465a1) | Oct 28, 2022 |
| Unknown       | Unknown                     | [c867c45a75](https://linux-hardware.org/?probe=c867c45a75) | Oct 28, 2022 |
| Unknown       | Unknown                     | [967c2c956d](https://linux-hardware.org/?probe=967c2c956d) | Oct 27, 2022 |
| Dell          | Vostro 5490                 | [ac6587adbb](https://linux-hardware.org/?probe=ac6587adbb) | Oct 27, 2022 |
| Acer          | Aspire E5-573G              | [6f926eed65](https://linux-hardware.org/?probe=6f926eed65) | Oct 27, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [a44f774778](https://linux-hardware.org/?probe=a44f774778) | Oct 27, 2022 |
| HP            | Laptop 14s-fq0xxx           | [377893cdc6](https://linux-hardware.org/?probe=377893cdc6) | Oct 27, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [b9c616b406](https://linux-hardware.org/?probe=b9c616b406) | Oct 27, 2022 |
| ASUSTek       | N56VZ                       | [399d92f9e0](https://linux-hardware.org/?probe=399d92f9e0) | Oct 27, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [9bb0c7d3b0](https://linux-hardware.org/?probe=9bb0c7d3b0) | Oct 26, 2022 |
| Acer          | Nitro AN515-54              | [89180ba46b](https://linux-hardware.org/?probe=89180ba46b) | Oct 26, 2022 |
| HUAWEI        | CREM-WXX9                   | [1c1356d6d5](https://linux-hardware.org/?probe=1c1356d6d5) | Oct 26, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [70ea39404e](https://linux-hardware.org/?probe=70ea39404e) | Oct 26, 2022 |
| HP            | EliteBook 840 G4            | [73ee5ace17](https://linux-hardware.org/?probe=73ee5ace17) | Oct 26, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [ffa2d93859](https://linux-hardware.org/?probe=ffa2d93859) | Oct 26, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [642cfbc2d7](https://linux-hardware.org/?probe=642cfbc2d7) | Oct 26, 2022 |
| HP            | Laptop 15s-fq2xxx           | [a7a7e4b82c](https://linux-hardware.org/?probe=a7a7e4b82c) | Oct 26, 2022 |
| HP            | Pavilion dv7                | [1b53255010](https://linux-hardware.org/?probe=1b53255010) | Oct 25, 2022 |
| HP            | Laptop 14s-dq2xxx           | [6af4891e58](https://linux-hardware.org/?probe=6af4891e58) | Oct 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [09eec214ae](https://linux-hardware.org/?probe=09eec214ae) | Oct 25, 2022 |
| Lenovo        | ThinkPad T490 20N2001YUS    | [61b5a3092b](https://linux-hardware.org/?probe=61b5a3092b) | Oct 25, 2022 |
| Apple         | MacBookPro11,4              | [29dd6b053b](https://linux-hardware.org/?probe=29dd6b053b) | Oct 25, 2022 |
| Acer          | Aspire A517-52              | [1ee47a3ab6](https://linux-hardware.org/?probe=1ee47a3ab6) | Oct 25, 2022 |
| Toshiba       | Satellite C660              | [b9d0cd845c](https://linux-hardware.org/?probe=b9d0cd845c) | Oct 25, 2022 |
| Toshiba       | Satellite C660              | [36faa336cf](https://linux-hardware.org/?probe=36faa336cf) | Oct 25, 2022 |
| HP            | Laptop 17-ak0xx             | [09e77bbc9a](https://linux-hardware.org/?probe=09e77bbc9a) | Oct 25, 2022 |
| HUAWEI        | HVY-WXX9                    | [60c3fde90a](https://linux-hardware.org/?probe=60c3fde90a) | Oct 25, 2022 |
| Lenovo        | B560                        | [82125c56a3](https://linux-hardware.org/?probe=82125c56a3) | Oct 24, 2022 |
| HP            | Laptop 17-ak0xx             | [88796bbb2b](https://linux-hardware.org/?probe=88796bbb2b) | Oct 24, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [9115752bd4](https://linux-hardware.org/?probe=9115752bd4) | Oct 24, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [f426a7b690](https://linux-hardware.org/?probe=f426a7b690) | Oct 24, 2022 |
| ASUSTek       | A7U                         | [867f26dde1](https://linux-hardware.org/?probe=867f26dde1) | Oct 24, 2022 |
| HONOR         | BBR-WAX9                    | [bc30c6555a](https://linux-hardware.org/?probe=bc30c6555a) | Oct 24, 2022 |
| HONOR         | BBR-WAX9                    | [667d235a8f](https://linux-hardware.org/?probe=667d235a8f) | Oct 24, 2022 |
| HP            | Laptop 15-bw0xx             | [cdd4d21000](https://linux-hardware.org/?probe=cdd4d21000) | Oct 24, 2022 |
| Dell          | XPS L412Z                   | [92d8a4b47a](https://linux-hardware.org/?probe=92d8a4b47a) | Oct 24, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [14537f243b](https://linux-hardware.org/?probe=14537f243b) | Oct 24, 2022 |
| MSI           | GE60 2PC                    | [e4378edb2b](https://linux-hardware.org/?probe=e4378edb2b) | Oct 24, 2022 |
| Sony          | SVE1513U1RW                 | [019c35087a](https://linux-hardware.org/?probe=019c35087a) | Oct 24, 2022 |
| MSI           | GE60 2PC                    | [930a153301](https://linux-hardware.org/?probe=930a153301) | Oct 24, 2022 |
| ASUSTek       | N56DY                       | [2d308224ee](https://linux-hardware.org/?probe=2d308224ee) | Oct 23, 2022 |
| ASUSTek       | N56DY                       | [d0caa49d24](https://linux-hardware.org/?probe=d0caa49d24) | Oct 23, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [d690b09eab](https://linux-hardware.org/?probe=d690b09eab) | Oct 23, 2022 |
| HUAWEI        | NBD-WXX9                    | [c6c2d4cab0](https://linux-hardware.org/?probe=c6c2d4cab0) | Oct 23, 2022 |
| HP            | Pavilion g6                 | [1c355f37b9](https://linux-hardware.org/?probe=1c355f37b9) | Oct 23, 2022 |
| THUNDEROBO... | 911AirD                     | [f471a1c9db](https://linux-hardware.org/?probe=f471a1c9db) | Oct 23, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [38c71fbd5e](https://linux-hardware.org/?probe=38c71fbd5e) | Oct 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [cda3087aaf](https://linux-hardware.org/?probe=cda3087aaf) | Oct 23, 2022 |
| Chuwi         | CoreBook X                  | [bc31018b26](https://linux-hardware.org/?probe=bc31018b26) | Oct 23, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [e2e9f1a6e7](https://linux-hardware.org/?probe=e2e9f1a6e7) | Oct 23, 2022 |
| ASUSTek       | W7S                         | [5797f4be95](https://linux-hardware.org/?probe=5797f4be95) | Oct 23, 2022 |
| HP            | Pavilion dv7                | [acaa8b9309](https://linux-hardware.org/?probe=acaa8b9309) | Oct 23, 2022 |
| Lenovo        | G505s 20255                 | [cff2326042](https://linux-hardware.org/?probe=cff2326042) | Oct 23, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [e0face3bcb](https://linux-hardware.org/?probe=e0face3bcb) | Oct 22, 2022 |
| Lenovo        | Legion Y730-17ICH 81HG      | [c9a85159dd](https://linux-hardware.org/?probe=c9a85159dd) | Oct 22, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [bfb6c03047](https://linux-hardware.org/?probe=bfb6c03047) | Oct 22, 2022 |
| HP            | Pavilion dv7                | [ede1ff6d62](https://linux-hardware.org/?probe=ede1ff6d62) | Oct 22, 2022 |
| Lenovo        | Legion Y730-17ICH 81HG      | [15a66ac64c](https://linux-hardware.org/?probe=15a66ac64c) | Oct 22, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [eb7a276b51](https://linux-hardware.org/?probe=eb7a276b51) | Oct 22, 2022 |
| Shanghai Z... | ZXE CRB                     | [166b646956](https://linux-hardware.org/?probe=166b646956) | Oct 22, 2022 |
| Acer          | Aspire E1-571G              | [3440b5765d](https://linux-hardware.org/?probe=3440b5765d) | Oct 21, 2022 |
| 3Logic Gro... | APM Graviton                | [0dd152f1d6](https://linux-hardware.org/?probe=0dd152f1d6) | Oct 21, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [a8c892608e](https://linux-hardware.org/?probe=a8c892608e) | Oct 21, 2022 |
| Acer          | Aspire A715-41G             | [afb2836a23](https://linux-hardware.org/?probe=afb2836a23) | Oct 21, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [6c8562fa45](https://linux-hardware.org/?probe=6c8562fa45) | Oct 21, 2022 |
| HP            | Pavilion Notebook           | [2900a3fd5d](https://linux-hardware.org/?probe=2900a3fd5d) | Oct 21, 2022 |
| Sony          | VPCEB1S1R                   | [1e64f5427a](https://linux-hardware.org/?probe=1e64f5427a) | Oct 21, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [3b8452c3c6](https://linux-hardware.org/?probe=3b8452c3c6) | Oct 21, 2022 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [123b6fc51a](https://linux-hardware.org/?probe=123b6fc51a) | Oct 21, 2022 |
| Aquarius      | NS585                       | [c953c5090c](https://linux-hardware.org/?probe=c953c5090c) | Oct 21, 2022 |
| Acer          | Aspire A517-52              | [7515d53b5d](https://linux-hardware.org/?probe=7515d53b5d) | Oct 21, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [a5d65724fa](https://linux-hardware.org/?probe=a5d65724fa) | Oct 21, 2022 |
| Lenovo        | B560                        | [3a61700f49](https://linux-hardware.org/?probe=3a61700f49) | Oct 20, 2022 |
| Aquarius      | NS585                       | [a134ed693c](https://linux-hardware.org/?probe=a134ed693c) | Oct 20, 2022 |
| Sony          | VPCEL3S1R                   | [5c37559c2d](https://linux-hardware.org/?probe=5c37559c2d) | Oct 20, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [3fc175d4a0](https://linux-hardware.org/?probe=3fc175d4a0) | Oct 20, 2022 |
| ASUSTek       | K43SJ                       | [4c27c4945c](https://linux-hardware.org/?probe=4c27c4945c) | Oct 20, 2022 |
| Acer          | Aspire E5-575G              | [66cfe85e96](https://linux-hardware.org/?probe=66cfe85e96) | Oct 20, 2022 |
| Dell          | Inspiron 5584               | [79ec522ef8](https://linux-hardware.org/?probe=79ec522ef8) | Oct 20, 2022 |
| HP            | Pavilion dm4                | [d96f382cc2](https://linux-hardware.org/?probe=d96f382cc2) | Oct 19, 2022 |
| HP            | Pavilion dm4                | [171745a6e8](https://linux-hardware.org/?probe=171745a6e8) | Oct 19, 2022 |
| Dell          | Inspiron 5584               | [4dac48ea7f](https://linux-hardware.org/?probe=4dac48ea7f) | Oct 19, 2022 |
| Toshiba       | Satellite A300              | [ce897bc567](https://linux-hardware.org/?probe=ce897bc567) | Oct 19, 2022 |
| ASUSTek       | X555LF                      | [76a0525b50](https://linux-hardware.org/?probe=76a0525b50) | Oct 19, 2022 |
| HP            | Pavilion g6                 | [8744b669fe](https://linux-hardware.org/?probe=8744b669fe) | Oct 19, 2022 |
| Dell          | Precision 7760              | [a5ab2793ae](https://linux-hardware.org/?probe=a5ab2793ae) | Oct 19, 2022 |
| HP            | ENVY Sleekbook 6            | [a197375e26](https://linux-hardware.org/?probe=a197375e26) | Oct 19, 2022 |
| Pegatron      | A17                         | [14f7d2a90d](https://linux-hardware.org/?probe=14f7d2a90d) | Oct 19, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [fe184c8f5b](https://linux-hardware.org/?probe=fe184c8f5b) | Oct 19, 2022 |
| HUAWEI        | NDZ-WXX9                    | [85574757af](https://linux-hardware.org/?probe=85574757af) | Oct 19, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [0db79bc085](https://linux-hardware.org/?probe=0db79bc085) | Oct 19, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [d6d2256d26](https://linux-hardware.org/?probe=d6d2256d26) | Oct 19, 2022 |
| Dell          | XPS L412Z                   | [eb1b1f7950](https://linux-hardware.org/?probe=eb1b1f7950) | Oct 19, 2022 |
| Haier         | A1420EM                     | [62ce3535b2](https://linux-hardware.org/?probe=62ce3535b2) | Oct 19, 2022 |
| Haier         | A1420EM                     | [a50bc27e31](https://linux-hardware.org/?probe=a50bc27e31) | Oct 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [3c2bd41b69](https://linux-hardware.org/?probe=3c2bd41b69) | Oct 19, 2022 |
| HP            | Pavilion Notebook           | [0d145a7293](https://linux-hardware.org/?probe=0d145a7293) | Oct 19, 2022 |
| HUAWEI        | NBM-WXX9                    | [fec0dd03d5](https://linux-hardware.org/?probe=fec0dd03d5) | Oct 18, 2022 |
| Dell          | Vostro 15 5510              | [b397c3fd26](https://linux-hardware.org/?probe=b397c3fd26) | Oct 18, 2022 |
| eMachines     | E525                        | [6b500273c6](https://linux-hardware.org/?probe=6b500273c6) | Oct 18, 2022 |
| Lenovo        | G565 20071                  | [52758e9b4b](https://linux-hardware.org/?probe=52758e9b4b) | Oct 18, 2022 |
| Lenovo        | B570e HuronRiver Platfor... | [b8a2cca654](https://linux-hardware.org/?probe=b8a2cca654) | Oct 18, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [aaa41de825](https://linux-hardware.org/?probe=aaa41de825) | Oct 18, 2022 |
| Maibenben     | ZiMai Z5                    | [96d25004be](https://linux-hardware.org/?probe=96d25004be) | Oct 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [484cb84d6b](https://linux-hardware.org/?probe=484cb84d6b) | Oct 18, 2022 |
| Lenovo        | V310-15IKB 80T3             | [c56ac0436c](https://linux-hardware.org/?probe=c56ac0436c) | Oct 18, 2022 |
| Lenovo        | B560                        | [717af973da](https://linux-hardware.org/?probe=717af973da) | Oct 18, 2022 |
| DEPO Compu... | DPC156                      | [4820b94a4a](https://linux-hardware.org/?probe=4820b94a4a) | Oct 18, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [469118097a](https://linux-hardware.org/?probe=469118097a) | Oct 18, 2022 |
| Acer          | Aspire E5-573               | [baf225a894](https://linux-hardware.org/?probe=baf225a894) | Oct 17, 2022 |
| Lenovo        | G480                        | [55e0ad0e82](https://linux-hardware.org/?probe=55e0ad0e82) | Oct 17, 2022 |
| Dell          | 500                         | [91b78b800a](https://linux-hardware.org/?probe=91b78b800a) | Oct 17, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [0a8148f3b5](https://linux-hardware.org/?probe=0a8148f3b5) | Oct 17, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [7f9219a85f](https://linux-hardware.org/?probe=7f9219a85f) | Oct 17, 2022 |
| Acer          | Aspire 5740                 | [83bb80a8d4](https://linux-hardware.org/?probe=83bb80a8d4) | Oct 17, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [73145a883c](https://linux-hardware.org/?probe=73145a883c) | Oct 17, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [678415db20](https://linux-hardware.org/?probe=678415db20) | Oct 17, 2022 |
| Maibenben     | MaiBook M                   | [ca20ade584](https://linux-hardware.org/?probe=ca20ade584) | Oct 16, 2022 |
| HONOR         | NBR-WAX9                    | [3862d6fc41](https://linux-hardware.org/?probe=3862d6fc41) | Oct 16, 2022 |
| Lenovo        | B580 20144                  | [3de13d5e45](https://linux-hardware.org/?probe=3de13d5e45) | Oct 16, 2022 |
| HP            | Notebook                    | [f88b853298](https://linux-hardware.org/?probe=f88b853298) | Oct 16, 2022 |
| Samsung       | RV413/RV513                 | [22d5794b5d](https://linux-hardware.org/?probe=22d5794b5d) | Oct 16, 2022 |
| Sony          | SVE1512H1RW                 | [bdc28748b2](https://linux-hardware.org/?probe=bdc28748b2) | Oct 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [7782926601](https://linux-hardware.org/?probe=7782926601) | Oct 16, 2022 |
| Valve         | Jupiter                     | [dde3144879](https://linux-hardware.org/?probe=dde3144879) | Oct 16, 2022 |
| Thomson       | NEO14A-4WH128               | [daa7836c39](https://linux-hardware.org/?probe=daa7836c39) | Oct 16, 2022 |
| MSI           | Sword 15 A11UE              | [514b1ab74d](https://linux-hardware.org/?probe=514b1ab74d) | Oct 16, 2022 |
| Pegatron      | A15                         | [25bf0fe850](https://linux-hardware.org/?probe=25bf0fe850) | Oct 15, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [e1bc46388d](https://linux-hardware.org/?probe=e1bc46388d) | Oct 14, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [f7b75c7dff](https://linux-hardware.org/?probe=f7b75c7dff) | Oct 14, 2022 |
| Acer          | Aspire E5-511               | [823f951e7a](https://linux-hardware.org/?probe=823f951e7a) | Oct 14, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | [2356263af1](https://linux-hardware.org/?probe=2356263af1) | Oct 14, 2022 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [abbb3295c8](https://linux-hardware.org/?probe=abbb3295c8) | Oct 14, 2022 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [f19e981e03](https://linux-hardware.org/?probe=f19e981e03) | Oct 14, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [9f4368b685](https://linux-hardware.org/?probe=9f4368b685) | Oct 14, 2022 |
| eMachines     | E525                        | [a2c8a5cadb](https://linux-hardware.org/?probe=a2c8a5cadb) | Oct 14, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [dbd2328d0f](https://linux-hardware.org/?probe=dbd2328d0f) | Oct 14, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [3a8bdfb3f5](https://linux-hardware.org/?probe=3a8bdfb3f5) | Oct 14, 2022 |
| ASUSTek       | X502CA                      | [1243c07d09](https://linux-hardware.org/?probe=1243c07d09) | Oct 13, 2022 |
| ASUSTek       | X502CA                      | [064718ff22](https://linux-hardware.org/?probe=064718ff22) | Oct 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [144c6cf207](https://linux-hardware.org/?probe=144c6cf207) | Oct 13, 2022 |
| HP            | Laptop 15s-eq2xxx           | [9e4ddfc113](https://linux-hardware.org/?probe=9e4ddfc113) | Oct 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [61c8063781](https://linux-hardware.org/?probe=61c8063781) | Oct 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [9b0a923899](https://linux-hardware.org/?probe=9b0a923899) | Oct 13, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [1cdde90662](https://linux-hardware.org/?probe=1cdde90662) | Oct 13, 2022 |
| ASUSTek       | K55N                        | [8a7b8b14f3](https://linux-hardware.org/?probe=8a7b8b14f3) | Oct 13, 2022 |
| Acer          | Aspire E1-571G              | [75b10196e0](https://linux-hardware.org/?probe=75b10196e0) | Oct 13, 2022 |
| Dell          | Latitude 5300               | [30d4b7fb75](https://linux-hardware.org/?probe=30d4b7fb75) | Oct 13, 2022 |
| Acer          | Aspire 5742G                | [b9da06eb9c](https://linux-hardware.org/?probe=b9da06eb9c) | Oct 13, 2022 |
| Irbis         | NB121                       | [04f312f46b](https://linux-hardware.org/?probe=04f312f46b) | Oct 13, 2022 |
| Irbis         | NB121                       | [ff99468633](https://linux-hardware.org/?probe=ff99468633) | Oct 13, 2022 |
| Lenovo        | G50-30 80G0                 | [f3bdfee67a](https://linux-hardware.org/?probe=f3bdfee67a) | Oct 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [adfbedf6ef](https://linux-hardware.org/?probe=adfbedf6ef) | Oct 12, 2022 |
| Acer          | Aspire A715-71G             | [2b0752150c](https://linux-hardware.org/?probe=2b0752150c) | Oct 12, 2022 |
| Apple         | MacBookAir7,2               | [8b4c66e10a](https://linux-hardware.org/?probe=8b4c66e10a) | Oct 11, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [fd73da4fee](https://linux-hardware.org/?probe=fd73da4fee) | Oct 11, 2022 |
| Lenovo        | ThinkPad S1 Yoga 20CDA00... | [7bc7561ab1](https://linux-hardware.org/?probe=7bc7561ab1) | Oct 11, 2022 |
| HUAWEI        | HVY-WXX9                    | [10ab944320](https://linux-hardware.org/?probe=10ab944320) | Oct 11, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [5caff1861e](https://linux-hardware.org/?probe=5caff1861e) | Oct 10, 2022 |
| Aquarius      | NS685U R11                  | [ce27c5e6f7](https://linux-hardware.org/?probe=ce27c5e6f7) | Oct 10, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [efabc0c1ba](https://linux-hardware.org/?probe=efabc0c1ba) | Oct 09, 2022 |
| Dell          | Inspiron 3520               | [12650c819a](https://linux-hardware.org/?probe=12650c819a) | Oct 09, 2022 |
| Lenovo        | G50-70 20351                | [300cc7d78f](https://linux-hardware.org/?probe=300cc7d78f) | Oct 09, 2022 |
| MSI           | GF63 Thin 9RCX              | [b8e1d8da2a](https://linux-hardware.org/?probe=b8e1d8da2a) | Oct 09, 2022 |
| Acer          | Aspire 5742G                | [d7c3182832](https://linux-hardware.org/?probe=d7c3182832) | Oct 08, 2022 |
| MSI           | GF63 Thin 9RCX              | [64bcf40d38](https://linux-hardware.org/?probe=64bcf40d38) | Oct 08, 2022 |
| HP            | Pavilion g6                 | [1c2fd7400d](https://linux-hardware.org/?probe=1c2fd7400d) | Oct 08, 2022 |
| HP            | EliteBook 6930p             | [6f175167b8](https://linux-hardware.org/?probe=6f175167b8) | Oct 08, 2022 |
| ASUSTek       | X550CL                      | [4afa1df235](https://linux-hardware.org/?probe=4afa1df235) | Oct 08, 2022 |
| Acer          | Aspire 2920                 | [c588bacc95](https://linux-hardware.org/?probe=c588bacc95) | Oct 08, 2022 |
| Acer          | Aspire 2920                 | [34b41a4e67](https://linux-hardware.org/?probe=34b41a4e67) | Oct 08, 2022 |
| ASUSTek       | X550CL                      | [d0584d3672](https://linux-hardware.org/?probe=d0584d3672) | Oct 08, 2022 |
| HONOR         | NBR-WAX9                    | [2f0c3ba507](https://linux-hardware.org/?probe=2f0c3ba507) | Oct 08, 2022 |
| Acer          | Nitro AN515-54              | [dc5782e5a2](https://linux-hardware.org/?probe=dc5782e5a2) | Oct 08, 2022 |
| Dell          | Vostro 15 7510              | [b9ab199135](https://linux-hardware.org/?probe=b9ab199135) | Oct 07, 2022 |
| ASUSTek       | X540NV                      | [31e4464fea](https://linux-hardware.org/?probe=31e4464fea) | Oct 07, 2022 |
| Clevo         | W210CUQ                     | [d698b7fe27](https://linux-hardware.org/?probe=d698b7fe27) | Oct 07, 2022 |
| MSI           | CX62 6QD                    | [cf52082ecb](https://linux-hardware.org/?probe=cf52082ecb) | Oct 07, 2022 |
| HP            | ProBook 450 G6              | [646d9b09b3](https://linux-hardware.org/?probe=646d9b09b3) | Oct 07, 2022 |
| System76      | Galago Pro                  | [5922699347](https://linux-hardware.org/?probe=5922699347) | Oct 07, 2022 |
| HUAWEI        | HLY-WX9XX                   | [af5d214080](https://linux-hardware.org/?probe=af5d214080) | Oct 06, 2022 |
| Sony          | VPCSB1V9R                   | [c19abb47cc](https://linux-hardware.org/?probe=c19abb47cc) | Oct 06, 2022 |
| HP            | Pavilion dv7                | [13e60be2de](https://linux-hardware.org/?probe=13e60be2de) | Oct 06, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [f7bb87986f](https://linux-hardware.org/?probe=f7bb87986f) | Oct 06, 2022 |
| Acer          | Extensa 4220                | [10e3973e91](https://linux-hardware.org/?probe=10e3973e91) | Oct 06, 2022 |
| HP            | ProBook 4310s               | [ac57665927](https://linux-hardware.org/?probe=ac57665927) | Oct 06, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [7f8e650618](https://linux-hardware.org/?probe=7f8e650618) | Oct 06, 2022 |
| HP            | Notebook                    | [49ab3eec39](https://linux-hardware.org/?probe=49ab3eec39) | Oct 06, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [75a7a7f691](https://linux-hardware.org/?probe=75a7a7f691) | Oct 05, 2022 |
| Acer          | Aspire 2920                 | [538f7a6e26](https://linux-hardware.org/?probe=538f7a6e26) | Oct 05, 2022 |
| MSI           | Modern 15 A5M               | [035a9bb7fa](https://linux-hardware.org/?probe=035a9bb7fa) | Oct 05, 2022 |
| HUAWEI        | NBD-WXX9                    | [2513dfd51e](https://linux-hardware.org/?probe=2513dfd51e) | Oct 05, 2022 |
| HP            | OMEN by Laptop              | [0a8238a876](https://linux-hardware.org/?probe=0a8238a876) | Oct 05, 2022 |
| Samsung       | NC110P/NC108P/NC111P        | [33b573e4a1](https://linux-hardware.org/?probe=33b573e4a1) | Oct 04, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [cc9d8d4d30](https://linux-hardware.org/?probe=cc9d8d4d30) | Oct 04, 2022 |
| ASUSTek       | X101CH                      | [c90b38a699](https://linux-hardware.org/?probe=c90b38a699) | Oct 04, 2022 |
| Clevo         | P150HMx                     | [48c8941ee9](https://linux-hardware.org/?probe=48c8941ee9) | Oct 04, 2022 |
| HP            | Pavilion Laptop 13-an1xx... | [9d9b963cd4](https://linux-hardware.org/?probe=9d9b963cd4) | Oct 04, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [ed4fe6487a](https://linux-hardware.org/?probe=ed4fe6487a) | Oct 04, 2022 |
| Valve         | Jupiter                     | [70f65d68fc](https://linux-hardware.org/?probe=70f65d68fc) | Oct 04, 2022 |
| HP            | ProBook 4530s               | [8be2220d0f](https://linux-hardware.org/?probe=8be2220d0f) | Oct 04, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [a174e09687](https://linux-hardware.org/?probe=a174e09687) | Oct 04, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [e31e511d7b](https://linux-hardware.org/?probe=e31e511d7b) | Oct 04, 2022 |
| Lenovo        | Legion Y-540-17IRH-PG0 8... | [3dbbfc44f6](https://linux-hardware.org/?probe=3dbbfc44f6) | Oct 04, 2022 |
| Dell          | Inspiron 3521               | [50615f4621](https://linux-hardware.org/?probe=50615f4621) | Oct 04, 2022 |
| ASUSTek       | K43SJ                       | [826d1c0dc8](https://linux-hardware.org/?probe=826d1c0dc8) | Oct 04, 2022 |
| Samsung       | R530/R730/R540              | [82629aeacd](https://linux-hardware.org/?probe=82629aeacd) | Oct 04, 2022 |
| Lenovo        | ThinkPad T420 4236WS7       | [e42a5888c7](https://linux-hardware.org/?probe=e42a5888c7) | Oct 04, 2022 |
| Acer          | Nitro AN515-52              | [9a69b6dc4a](https://linux-hardware.org/?probe=9a69b6dc4a) | Oct 03, 2022 |
| Sony          | VPCF12Z1R                   | [6d7cd0d51d](https://linux-hardware.org/?probe=6d7cd0d51d) | Oct 03, 2022 |
| THUNDEROBO... | 911AirD                     | [69a9650652](https://linux-hardware.org/?probe=69a9650652) | Oct 03, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [f8224dfb59](https://linux-hardware.org/?probe=f8224dfb59) | Oct 03, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [89b48cd98e](https://linux-hardware.org/?probe=89b48cd98e) | Oct 03, 2022 |
| Lenovo        | ThinkPad T490s 20NYS4HL1... | [7f5e71e099](https://linux-hardware.org/?probe=7f5e71e099) | Oct 02, 2022 |
| Lenovo        | ThinkPad T490s 20NYS4HL1... | [8b81fb7c67](https://linux-hardware.org/?probe=8b81fb7c67) | Oct 02, 2022 |
| HP            | Pavilion dv7                | [219524e854](https://linux-hardware.org/?probe=219524e854) | Oct 02, 2022 |
| Dell          | XPS 15 9500                 | [001bcba320](https://linux-hardware.org/?probe=001bcba320) | Oct 02, 2022 |
| BenQ          | Joybook S32                 | [ba2b78c3e4](https://linux-hardware.org/?probe=ba2b78c3e4) | Oct 02, 2022 |
| HP            | Pavilion g7                 | [458c7b0f65](https://linux-hardware.org/?probe=458c7b0f65) | Oct 02, 2022 |
| Acer          | Aspire A315-42G             | [84345ea89c](https://linux-hardware.org/?probe=84345ea89c) | Oct 02, 2022 |
| Lenovo        | G550 20023                  | [68961f954b](https://linux-hardware.org/?probe=68961f954b) | Oct 02, 2022 |
| HUAWEI        | BOM-WXX9                    | [e6e51bcb84](https://linux-hardware.org/?probe=e6e51bcb84) | Oct 02, 2022 |
| ASUSTek       | K53SM                       | [49967682a7](https://linux-hardware.org/?probe=49967682a7) | Oct 02, 2022 |
| Dell          | Inspiron 3520               | [5fdeec4922](https://linux-hardware.org/?probe=5fdeec4922) | Oct 02, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | [c086a688f1](https://linux-hardware.org/?probe=c086a688f1) | Oct 02, 2022 |
| Quanta        | TWC                         | [423f504621](https://linux-hardware.org/?probe=423f504621) | Oct 02, 2022 |
| Acer          | AOA150                      | [b8780da9ef](https://linux-hardware.org/?probe=b8780da9ef) | Oct 02, 2022 |
| Dell          | 500                         | [83c01aa11f](https://linux-hardware.org/?probe=83c01aa11f) | Oct 01, 2022 |
| Acer          | Aspire A715-41G             | [1a473e9809](https://linux-hardware.org/?probe=1a473e9809) | Oct 01, 2022 |
| HUAWEI        | HN-WX9X                     | [4168f641b5](https://linux-hardware.org/?probe=4168f641b5) | Oct 01, 2022 |
| HP            | 650                         | [162893e9ad](https://linux-hardware.org/?probe=162893e9ad) | Oct 01, 2022 |
| Lenovo        | G770 20089                  | [e06e588d62](https://linux-hardware.org/?probe=e06e588d62) | Oct 01, 2022 |
| ASUSTek       | F5V                         | [463cd15493](https://linux-hardware.org/?probe=463cd15493) | Oct 01, 2022 |
| Dell          | Inspiron 5737               | [14113affa1](https://linux-hardware.org/?probe=14113affa1) | Oct 01, 2022 |
| Dell          | Inspiron 5737               | [6893292144](https://linux-hardware.org/?probe=6893292144) | Oct 01, 2022 |
| Acer          | Aspire 5750G                | [8e87575f75](https://linux-hardware.org/?probe=8e87575f75) | Oct 01, 2022 |
| Acer          | Aspire A315-55G             | [77605e313d](https://linux-hardware.org/?probe=77605e313d) | Oct 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [d5407763a0](https://linux-hardware.org/?probe=d5407763a0) | Sep 30, 2022 |
| GPD           | G1621-02                    | [6ae9fc596e](https://linux-hardware.org/?probe=6ae9fc596e) | Sep 30, 2022 |
| Irbis         | NB121                       | [a2eb8c8af1](https://linux-hardware.org/?probe=a2eb8c8af1) | Sep 30, 2022 |
| Acer          | Extensa 4220                | [c35a0a579a](https://linux-hardware.org/?probe=c35a0a579a) | Sep 30, 2022 |
| Irbis         | NB121                       | [90a0ae1cf9](https://linux-hardware.org/?probe=90a0ae1cf9) | Sep 30, 2022 |
| Lenovo        | G460 20041                  | [130c0489f9](https://linux-hardware.org/?probe=130c0489f9) | Sep 30, 2022 |
| Digma         | EVE 11 C408                 | [b5c7ac8ed3](https://linux-hardware.org/?probe=b5c7ac8ed3) | Sep 30, 2022 |
| HP            | Pavilion dv7                | [4d54db9389](https://linux-hardware.org/?probe=4d54db9389) | Sep 30, 2022 |
| Acer          | Aspire A514-54              | [b8b0da1194](https://linux-hardware.org/?probe=b8b0da1194) | Sep 30, 2022 |
| Lenovo        | IdeaPad S145-15API 81UT     | [9ccd242ca4](https://linux-hardware.org/?probe=9ccd242ca4) | Sep 30, 2022 |
| Lenovo        | G580 20150                  | [d057161e9d](https://linux-hardware.org/?probe=d057161e9d) | Sep 30, 2022 |
| Lenovo        | ThinkPad L380 20M5SSIN11    | [0cad79b1f7](https://linux-hardware.org/?probe=0cad79b1f7) | Sep 30, 2022 |
| Irbis         | NB61 WS001                  | [3fda78e356](https://linux-hardware.org/?probe=3fda78e356) | Sep 29, 2022 |
| THUNDEROBO... | 911AirD                     | [99f1b7e253](https://linux-hardware.org/?probe=99f1b7e253) | Sep 29, 2022 |
| Acer          | Aspire 5741G                | [837c4599cc](https://linux-hardware.org/?probe=837c4599cc) | Sep 29, 2022 |
| Dell          | Latitude 3410               | [0f7ad40255](https://linux-hardware.org/?probe=0f7ad40255) | Sep 29, 2022 |
| Lenovo        | Legion 5 17ACH6 82K0        | [18afdc2116](https://linux-hardware.org/?probe=18afdc2116) | Sep 29, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [f2f9ccf12b](https://linux-hardware.org/?probe=f2f9ccf12b) | Sep 29, 2022 |
| HP            | Laptop 15-db0xxx            | [8f42666f03](https://linux-hardware.org/?probe=8f42666f03) | Sep 29, 2022 |
| Acer          | AOD257                      | [87b7501836](https://linux-hardware.org/?probe=87b7501836) | Sep 29, 2022 |
| Fujitsu       | LIFEBOOK P771               | [7325511d27](https://linux-hardware.org/?probe=7325511d27) | Sep 29, 2022 |
| ASUSTek       | N53SV                       | [6652e85ddd](https://linux-hardware.org/?probe=6652e85ddd) | Sep 29, 2022 |
| HUAWEI        | KLVD-WXX9                   | [72d80e02c9](https://linux-hardware.org/?probe=72d80e02c9) | Sep 29, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Russia/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| ROSA R10         | 1493      | 11.96%  |
| ROSA R11         | 1441      | 11.55%  |
| ROSA R8.1        | 1042      | 8.35%   |
| ROSA R8          | 919       | 7.36%   |
| ROSA R9          | 845       | 6.77%   |
| ROSA 12.2        | 762       | 6.11%   |
| ROSA R11.1       | 761       | 6.1%    |
| Ubuntu 20.04     | 470       | 3.77%   |
| Ubuntu 18.04     | 254       | 2.04%   |
| Debian 11        | 235       | 1.88%   |
| ROSA 12.3        | 164       | 1.31%   |
| OpenMandriva 4.2 | 158       | 1.27%   |
| Ubuntu 22.04     | 123       | 0.99%   |
| ROSA 12.1        | 110       | 0.88%   |
| KDE neon 20.04   | 104       | 0.83%   |
| Arch             | 98        | 0.79%   |
| OpenMandriva 4.3 | 90        | 0.72%   |
| Fedora 36        | 90        | 0.72%   |
| Arch Rolling     | 85        | 0.68%   |
| Linux Mint 19.3  | 83        | 0.67%   |
| Manjaro          | 77        | 0.62%   |
| Fedora 35        | 70        | 0.56%   |
| Linux Mint 20.1  | 68        | 0.54%   |
| Linux Mint 20.3  | 66        | 0.53%   |
| Debian 10        | 60        | 0.48%   |
| Linux Mint 19.1  | 59        | 0.47%   |
| Linux Mint 18.3  | 59        | 0.47%   |
| Kubuntu 20.04    | 59        | 0.47%   |
| Linux Mint 20    | 56        | 0.45%   |
| Fedora 34        | 56        | 0.45%   |
| Linux Mint 19.2  | 55        | 0.44%   |
| Kometa P10       | 54        | 0.43%   |
| Ubuntu 21.10     | 52        | 0.42%   |
| Linux Mint 20.2  | 48        | 0.38%   |
| Xubuntu 18.04    | 46        | 0.37%   |
| Ubuntu 19.10     | 46        | 0.37%   |
| Red OS 7.3.1     | 44        | 0.35%   |
| Linux Mint 21    | 44        | 0.35%   |
| Linux Mint 19    | 43        | 0.34%   |
| Xubuntu 20.04    | 42        | 0.34%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| ROSA          | 6554      | 58.87%  |
| Ubuntu        | 1074      | 9.65%   |
| Linux Mint    | 567       | 5.09%   |
| Fedora        | 333       | 2.99%   |
| Debian        | 330       | 2.96%   |
| Manjaro       | 306       | 2.75%   |
| OpenMandriva  | 274       | 2.46%   |
| Endless       | 211       | 1.9%    |
| Arch          | 175       | 1.57%   |
| ALT Linux     | 172       | 1.54%   |
| Kubuntu       | 133       | 1.19%   |
| KDE neon      | 123       | 1.1%    |
| Xubuntu       | 112       | 1.01%   |
| Pop!_OS       | 79        | 0.71%   |
| Red OS        | 69        | 0.62%   |
| Gentoo        | 51        | 0.46%   |
| Elementary    | 50        | 0.45%   |
| RED           | 46        | 0.41%   |
| Kali          | 46        | 0.41%   |
| openSUSE      | 40        | 0.36%   |
| Lubuntu       | 35        | 0.31%   |
| Zorin         | 32        | 0.29%   |
| LMDE          | 31        | 0.28%   |
| Clear Linux   | 30        | 0.27%   |
| Ubuntu MATE   | 29        | 0.26%   |
| Ubuntu Unity  | 24        | 0.22%   |
| ArcoLinux     | 18        | 0.16%   |
| CentOS        | 13        | 0.12%   |
| Ubuntu Budgie | 12        | 0.11%   |
| Artix         | 12        | 0.11%   |
| RELS          | 10        | 0.09%   |
| Parrot        | 10        | 0.09%   |
| Astra Linux   | 10        | 0.09%   |
| MX            | 9         | 0.08%   |
| EndeavourOS   | 8         | 0.07%   |
| Calculate     | 8         | 0.07%   |
| Void Linux    | 7         | 0.06%   |
| SteamOS       | 6         | 0.05%   |
| Devuan        | 6         | 0.05%   |
| BlackPanther  | 6         | 0.05%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| 5.10.74-generic-2rosa2021.1-x86_64  | 642       | 4.78%   |
| 4.9.60-nrj-desktop-1rosa-x86_64     | 620       | 4.62%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 619       | 4.61%   |
| 4.9.20-nrj-desktop-1rosa-x86_64     | 585       | 4.36%   |
| 4.1.34-nrj-desktop-2rosa-x86_64     | 349       | 2.6%    |
| 4.9.9-nrj-desktop-1rosa-x86_64      | 278       | 2.07%   |
| 4.9.124-nrj-desktop-1rosa-x86_64    | 275       | 2.05%   |
| 4.1.25-nrj-desktop-1rosa-x86_64     | 236       | 1.76%   |
| 4.1.38-nrj-desktop-2rosa-x86_64     | 218       | 1.62%   |
| 4.9.60-nrj-desktop-1rosa-i586       | 200       | 1.49%   |
| 4.9.76-nrj-desktop-1rosa-x86_64     | 175       | 1.3%    |
| 4.9.41-nrj-desktop-1rosa-x86_64     | 175       | 1.3%    |
| 4.9.20-nrj-desktop-1rosa-i586       | 174       | 1.3%    |
| 4.15.0-desktop-45.1rosa-i586        | 172       | 1.28%   |
| 4.15.0-desktop-68.5rosa-x86_64      | 169       | 1.26%   |
| 5.10.14-desktop-1omv4002            | 153       | 1.14%   |
| 4.9.155-nrj-desktop-1rosa-x86_64    | 147       | 1.1%    |
| 5.10.118-generic-2rosa2021.1-x86_64 | 146       | 1.09%   |
| 4.1.34-nrj-desktop-2rosa-i586       | 146       | 1.09%   |
| 5.4.32-generic-2rosa-x86_64         | 144       | 1.07%   |
| 4.15.0-desktop-47.2rosa-x86_64      | 138       | 1.03%   |
| 4.15.0-desktop-122.124.1rosa-x86_64 | 134       | 1%      |
| 5.4.83-generic-2rosa-x86_64         | 128       | 0.95%   |
| 5.10.0-7-amd64                      | 110       | 0.82%   |
| 4.15.0-desktop-94.1rosa-x86_64      | 107       | 0.8%    |
| 4.1.38-nrj-desktop-2rosa-i586       | 106       | 0.79%   |
| 4.9.95-nrj-desktop-2rosa-x86_64     | 96        | 0.72%   |
| 4.9.9-nrj-desktop-1rosa-i586        | 96        | 0.72%   |
| 4.1.25-nrj-desktop-1rosa-i586       | 90        | 0.67%   |
| 5.16.7-desktop-1omv4003             | 83        | 0.62%   |
| 4.9.124-nrj-desktop-1rosa-i586      | 78        | 0.58%   |
| 5.4.0-42-generic                    | 71        | 0.53%   |
| 4.15.0-desktop-60.7rosa-x86_64      | 69        | 0.51%   |
| 4.9.111-nrj-desktop-2rosa-x86_64    | 59        | 0.44%   |
| 5.4.32-generic-2rosa-i586           | 58        | 0.43%   |
| 4.9.41-nrj-desktop-1rosa-i586       | 58        | 0.43%   |
| 4.1.38-nrj-desktop-1rosa-x86_64     | 56        | 0.42%   |
| 4.9.155-nrj-desktop-1rosa-i586      | 54        | 0.4%    |
| 5.15.75-generic-1rosa2021.1-x86_64  | 52        | 0.39%   |
| 4.9.76-nrj-desktop-1rosa-i586       | 52        | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 4.15.0   | 1881      | 14.49%  |
| 4.9.60   | 820       | 6.32%   |
| 4.9.20   | 762       | 5.87%   |
| 5.4.0    | 699       | 5.39%   |
| 5.10.74  | 673       | 5.18%   |
| 4.1.34   | 497       | 3.83%   |
| 4.1.38   | 394       | 3.04%   |
| 4.9.9    | 374       | 2.88%   |
| 4.9.124  | 357       | 2.75%   |
| 4.1.25   | 327       | 2.52%   |
| 5.10.0   | 278       | 2.14%   |
| 5.15.0   | 269       | 2.07%   |
| 5.3.0    | 251       | 1.93%   |
| 4.9.41   | 235       | 1.81%   |
| 4.9.76   | 230       | 1.77%   |
| 5.11.0   | 207       | 1.59%   |
| 4.9.155  | 207       | 1.59%   |
| 5.4.32   | 202       | 1.56%   |
| 5.8.0    | 201       | 1.55%   |
| 5.13.0   | 182       | 1.4%    |
| 5.4.83   | 170       | 1.31%   |
| 5.0.0    | 170       | 1.31%   |
| 5.10.14  | 156       | 1.2%    |
| 5.10.118 | 153       | 1.18%   |
| 4.9.95   | 124       | 0.96%   |
| 4.18.0   | 95        | 0.73%   |
| 4.13.0   | 93        | 0.72%   |
| 5.16.7   | 85        | 0.65%   |
| 4.9.111  | 81        | 0.62%   |
| 4.19.0   | 72        | 0.55%   |
| 5.15.75  | 64        | 0.49%   |
| 4.9.87   | 58        | 0.45%   |
| 4.9.14   | 44        | 0.34%   |
| 5.10.71  | 41        | 0.32%   |
| 5.17.11  | 37        | 0.29%   |
| 4.1.15   | 37        | 0.29%   |
| 5.10.102 | 36        | 0.28%   |
| 5.15.79  | 33        | 0.25%   |
| 5.15.32  | 33        | 0.25%   |
| 5.15.10  | 32        | 0.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.9     | 2896      | 23.72%  |
| 4.15    | 1896      | 15.53%  |
| 5.10    | 1493      | 12.23%  |
| 5.4     | 1202      | 9.85%   |
| 4.1     | 1200      | 9.83%   |
| 5.15    | 644       | 5.28%   |
| 5.3     | 291       | 2.38%   |
| 5.11    | 273       | 2.24%   |
| 5.8     | 261       | 2.14%   |
| 5.13    | 242       | 1.98%   |
| 5.0     | 178       | 1.46%   |
| 5.16    | 154       | 1.26%   |
| 5.17    | 121       | 0.99%   |
| 5.18    | 116       | 0.95%   |
| 4.19    | 112       | 0.92%   |
| 4.18    | 110       | 0.9%    |
| 4.13    | 109       | 0.89%   |
| 6.0     | 94        | 0.77%   |
| 5.6     | 88        | 0.72%   |
| 5.19    | 88        | 0.72%   |
| 5.14    | 87        | 0.71%   |
| 5.9     | 69        | 0.57%   |
| 4.4     | 50        | 0.41%   |
| 4.16    | 50        | 0.41%   |
| 5.7     | 49        | 0.4%    |
| 5.12    | 48        | 0.39%   |
| 5.5     | 41        | 0.34%   |
| 4.8     | 37        | 0.3%    |
| 4.10    | 35        | 0.29%   |
| 3.14    | 20        | 0.16%   |
| 4.14    | 19        | 0.16%   |
| 5.2     | 18        | 0.15%   |
| 3.10    | 16        | 0.13%   |
| 4.17    | 14        | 0.11%   |
| 4.12    | 13        | 0.11%   |
| 6.1     | 12        | 0.1%    |
| 5.1     | 12        | 0.1%    |
| 4.11    | 12        | 0.1%    |
| 4.7     | 9         | 0.07%   |
| 3.16    | 7         | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 9356      | 85.09%  |
| i686    | 1635      | 14.87%  |
| armv7l  | 3         | 0.03%   |
| ppc     | 1         | 0.01%   |
| aarch64 | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| KDE4               | 4139      | 35.6%   |
| KDE5               | 2867      | 24.66%  |
| GNOME              | 2004      | 17.24%  |
| Unknown            | 673       | 5.79%   |
| XFCE               | 441       | 3.79%   |
| LXQt               | 367       | 3.16%   |
| MATE               | 294       | 2.53%   |
| Cinnamon           | 246       | 2.12%   |
| X-Cinnamon         | 217       | 1.87%   |
| KDE                | 164       | 1.41%   |
| Pantheon           | 47        | 0.4%    |
| i3                 | 32        | 0.28%   |
| LXDE               | 27        | 0.23%   |
| Unity              | 24        | 0.21%   |
| Budgie             | 20        | 0.17%   |
| GNOME Flashback    | 15        | 0.13%   |
| sway               | 10        | 0.09%   |
| fly                | 7         | 0.06%   |
| Deepin             | 5         | 0.04%   |
| Openbox            | 3         | 0.03%   |
| icewm              | 3         | 0.03%   |
| GNOME Classic      | 3         | 0.03%   |
| awesome            | 3         | 0.03%   |
| Trinity            | 2         | 0.02%   |
| fluxbox            | 2         | 0.02%   |
| DWM                | 2         | 0.02%   |
| xmonad             | 1         | 0.01%   |
| qtile              | 1         | 0.01%   |
| pantheon-non-gnome | 1         | 0.01%   |
| none+i3            | 1         | 0.01%   |
| Lumina             | 1         | 0.01%   |
| Lubuntu            | 1         | 0.01%   |
| lightdm-xsession   | 1         | 0.01%   |
| Enlightenment      | 1         | 0.01%   |
| bspwm              | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 9212      | 82.77%  |
| Wayland | 1460      | 13.12%  |
| Unknown | 384       | 3.45%   |
| Tty     | 72        | 0.65%   |
| Web     | 1         | 0.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| KDM     | 4158      | 35.91%  |
| SDDM    | 2990      | 25.82%  |
| Unknown | 1933      | 16.7%   |
| GDM     | 1256      | 10.85%  |
| LightDM | 507       | 4.38%   |
| TDM     | 432       | 3.73%   |
| GDM3    | 247       | 2.13%   |
| MDM     | 21        | 0.18%   |
| XDM     | 15        | 0.13%   |
| SLiM    | 7         | 0.06%   |
| NODM    | 3         | 0.03%   |
| FLY-DM  | 3         | 0.03%   |
| Ly      | 2         | 0.02%   |
| LXDM    | 2         | 0.02%   |
| GREETD  | 2         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| Unknown     | 5793      | 51.29%  |
| ru_RU       | 4262      | 37.74%  |
| en_US       | 1062      | 9.4%    |
| C           | 62        | 0.55%   |
| en_GB       | 48        | 0.43%   |
| ru_RU.UTF_8 | 19        | 0.17%   |
| ru_UA       | 8         | 0.07%   |
| zh_CN       | 4         | 0.04%   |
| C.UTF8      | 4         | 0.04%   |
| POSIX       | 3         | 0.03%   |
| en_CA       | 3         | 0.03%   |
| en_AG       | 3         | 0.03%   |
| uk_UA       | 2         | 0.02%   |
| tr_TR       | 2         | 0.02%   |
| es_ES       | 2         | 0.02%   |
| de_DE       | 2         | 0.02%   |
| cv_RU       | 2         | 0.02%   |
| ba_RU       | 2         | 0.02%   |
| tt_RU       | 1         | 0.01%   |
| ru_RU.UTF8  | 1         | 0.01%   |
| pt_BR       | 1         | 0.01%   |
| myv_RU      | 1         | 0.01%   |
| ja_JP       | 1         | 0.01%   |
| it_IT       | 1         | 0.01%   |
| fr_FR       | 1         | 0.01%   |
| en_NZ       | 1         | 0.01%   |
| en_GB.utf-8 | 1         | 0.01%   |
| en_AU       | 1         | 0.01%   |
| en-US       | 1         | 0.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 6536      | 58.99%  |
| EFI  | 4543      | 41.01%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 6722      | 58.48%  |
| Unknown  | 3579      | 31.14%  |
| Btrfs    | 581       | 5.05%   |
| Overlay  | 455       | 3.96%   |
| Xfs      | 55        | 0.48%   |
| Zfs      | 23        | 0.2%    |
| Ext3     | 21        | 0.18%   |
| Ext2     | 20        | 0.17%   |
| Aufs     | 16        | 0.14%   |
| F2fs     | 9         | 0.08%   |
| Tmpfs    | 4         | 0.03%   |
| Rootfs   | 3         | 0.03%   |
| Reiserfs | 3         | 0.03%   |
| XXXXXXX  | 1         | 0.01%   |
| XXXXX    | 1         | 0.01%   |
| Ufs      | 1         | 0.01%   |
| Jfs      | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| MBR     | 4399      | 38.35%  |
| GPT     | 3696      | 32.22%  |
| Unknown | 3376      | 29.43%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 9943      | 89.05%  |
| Yes       | 1223      | 10.95%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 8211      | 72.73%  |
| Yes       | 3078      | 27.27%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 1990      | 18.31%  |
| ASUSTek Computer    | 1950      | 17.94%  |
| Hewlett-Packard     | 1603      | 14.75%  |
| Acer                | 1530      | 14.08%  |
| Dell                | 787       | 7.24%   |
| Samsung Electronics | 630       | 5.8%    |
| Toshiba             | 278       | 2.56%   |
| MSI                 | 266       | 2.45%   |
| Sony                | 253       | 2.33%   |
| Packard Bell        | 170       | 1.56%   |
| HUAWEI              | 156       | 1.44%   |
| eMachines           | 108       | 0.99%   |
| Apple               | 84        | 0.77%   |
| Unknown             | 80        | 0.74%   |
| Clevo               | 74        | 0.68%   |
| Aquarius            | 71        | 0.65%   |
| Notebook            | 70        | 0.64%   |
| Timi                | 67        | 0.62%   |
| Pegatron            | 58        | 0.53%   |
| Fujitsu Siemens     | 42        | 0.39%   |
| Digma               | 39        | 0.36%   |
| DNS                 | 38        | 0.35%   |
| Fujitsu             | 35        | 0.32%   |
| Intel               | 33        | 0.3%    |
| Irbis               | 28        | 0.26%   |
| DEXP                | 28        | 0.26%   |
| Quanta              | 27        | 0.25%   |
| HONOR               | 26        | 0.24%   |
| Prestigio           | 25        | 0.23%   |
| ICL                 | 21        | 0.19%   |
| Gigabyte Technology | 16        | 0.15%   |
| Maibenben           | 15        | 0.14%   |
| Chuwi               | 15        | 0.14%   |
| Insyde              | 13        | 0.12%   |
| 3Logic Group        | 12        | 0.11%   |
| Haier               | 11        | 0.1%    |
| Panasonic           | 10        | 0.09%   |
| Infomash            | 10        | 0.09%   |
| LG Electronics      | 9         | 0.08%   |
| DEPO Computers      | 9         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 147       | 1.35%   |
| HP Pavilion g6                             | 122       | 1.12%   |
| HP Notebook                                | 77        | 0.71%   |
| HP Pavilion dv6                            | 74        | 0.68%   |
| HP Laptop 15-bw0xx                         | 74        | 0.68%   |
| Acer Aspire V3-571G                        | 57        | 0.52%   |
| Lenovo G570 20079                          | 52        | 0.48%   |
| Aquarius NS585                             | 46        | 0.42%   |
| Lenovo B570e HuronRiver Platform           | 42        | 0.39%   |
| HP Pavilion dv7                            | 40        | 0.37%   |
| Lenovo B590 20206                          | 39        | 0.36%   |
| Packard Bell EasyNote TE11HC               | 38        | 0.35%   |
| Lenovo G50-45 80E3                         | 36        | 0.33%   |
| HP Pavilion 15                             | 36        | 0.33%   |
| Lenovo B590 20208                          | 34        | 0.31%   |
| HUAWEI NBLK-WAX9X                          | 34        | 0.31%   |
| Lenovo G500 20236                          | 32        | 0.29%   |
| Lenovo G50-30 80G0                         | 32        | 0.29%   |
| HP Pavilion g7                             | 32        | 0.29%   |
| Toshiba Satellite C660                     | 31        | 0.29%   |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B | 31        | 0.29%   |
| ASUS VivoBook 15_ASUS Laptop X540BA        | 31        | 0.29%   |
| Lenovo G580 20150                          | 29        | 0.27%   |
| Lenovo B560                                | 29        | 0.27%   |
| Dell Inspiron N5110                        | 29        | 0.27%   |
| Acer Aspire 5750G                          | 29        | 0.27%   |
| Lenovo G580 20157                          | 28        | 0.26%   |
| Acer Aspire E1-571G                        | 28        | 0.26%   |
| Samsung 355V4C/356V4C/3445VC/3545VC        | 27        | 0.25%   |
| ASUS K50IJ                                 | 27        | 0.25%   |
| Acer Aspire 5742G                          | 27        | 0.25%   |
| ASUS X550CC                                | 26        | 0.24%   |
| Samsung 300E4C/300E5C/300E7C               | 25        | 0.23%   |
| Dell Inspiron 3521                         | 25        | 0.23%   |
| Lenovo IdeaPad 110-15ACL 80TJ              | 24        | 0.22%   |
| ASUS X101CH                                | 24        | 0.22%   |
| Lenovo G505s 20255                         | 23        | 0.21%   |
| HP 15                                      | 23        | 0.21%   |
| Dell Inspiron 3542                         | 23        | 0.21%   |
| ASUS X550CL                                | 23        | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 1044      | 9.6%    |
| Lenovo IdeaPad        | 589       | 5.42%   |
| HP Pavilion           | 474       | 4.36%   |
| Lenovo ThinkPad       | 414       | 3.81%   |
| Dell Inspiron         | 395       | 3.63%   |
| HP Laptop             | 276       | 2.54%   |
| ASUS VivoBook         | 268       | 2.47%   |
| Toshiba Satellite     | 258       | 2.37%   |
| HP ProBook            | 232       | 2.13%   |
| Dell Latitude         | 155       | 1.43%   |
| Packard Bell EasyNote | 149       | 1.37%   |
| Unknown               | 147       | 1.35%   |
| Acer Extensa          | 143       | 1.32%   |
| Dell Vostro           | 105       | 0.97%   |
| HP Compaq             | 96        | 0.88%   |
| Acer TravelMate       | 87        | 0.8%    |
| HP Notebook           | 78        | 0.72%   |
| HP EliteBook          | 77        | 0.71%   |
| Lenovo G580           | 76        | 0.7%    |
| Lenovo B590           | 73        | 0.67%   |
| Lenovo ThinkBook      | 57        | 0.52%   |
| Lenovo G570           | 53        | 0.49%   |
| HP 250                | 52        | 0.48%   |
| Acer Nitro            | 49        | 0.45%   |
| Acer Swift            | 47        | 0.43%   |
| Aquarius NS585        | 46        | 0.42%   |
| HP ENVY               | 44        | 0.4%    |
| Samsung 355V4C        | 42        | 0.39%   |
| Samsung 300V3A        | 42        | 0.39%   |
| Lenovo B570e          | 42        | 0.39%   |
| Dell XPS              | 42        | 0.39%   |
| Lenovo Legion         | 39        | 0.36%   |
| Notebook W65          | 38        | 0.35%   |
| Lenovo G50-45         | 38        | 0.35%   |
| ASUS ZenBook          | 35        | 0.32%   |
| HUAWEI NBLK-WAX9X     | 34        | 0.31%   |
| Fujitsu LIFEBOOK      | 34        | 0.31%   |
| ASUS ROG              | 34        | 0.31%   |
| HP Mini               | 33        | 0.3%    |
| ASUS TUF              | 33        | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 1414      | 13.01%  |
| 2012    | 1298      | 11.94%  |
| 2010    | 958       | 8.81%   |
| 2013    | 806       | 7.41%   |
| 2019    | 712       | 6.55%   |
| 2018    | 637       | 5.86%   |
| 2017    | 611       | 5.62%   |
| 2009    | 587       | 5.4%    |
| 2008    | 582       | 5.35%   |
| 2020    | 547       | 5.03%   |
| 2014    | 538       | 4.95%   |
| 2015    | 481       | 4.43%   |
| 2016    | 476       | 4.38%   |
| 2021    | 438       | 4.03%   |
| 2007    | 425       | 3.91%   |
| 2006    | 187       | 1.72%   |
| 2022    | 99        | 0.91%   |
| 2005    | 50        | 0.46%   |
| Unknown | 12        | 0.11%   |
| 2004    | 10        | 0.09%   |
| 2003    | 1         | 0.01%   |
| 2001    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 10870     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 10464     | 95.75%  |
| Enabled  | 464       | 4.25%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 10854     | 99.85%  |
| Yes  | 16        | 0.15%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 3293      | 29.49%  |
| 4.01-8.0    | 3005      | 26.91%  |
| 8.01-16.0   | 1452      | 13%     |
| 1.01-2.0    | 1394      | 12.48%  |
| 16.01-24.0  | 764       | 6.84%   |
| 2.01-3.0    | 755       | 6.76%   |
| 0.51-1.0    | 254       | 2.27%   |
| 32.01-64.0  | 172       | 1.54%   |
| 24.01-32.0  | 47        | 0.42%   |
| 64.01-256.0 | 15        | 0.13%   |
| 0.01-0.5    | 12        | 0.11%   |
| Unknown     | 3         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 4772      | 38.94%  |
| 0.51-1.0   | 3838      | 31.32%  |
| 2.01-3.0   | 1716      | 14%     |
| 3.01-4.0   | 754       | 6.15%   |
| 4.01-8.0   | 706       | 5.76%   |
| 0.01-0.5   | 281       | 2.29%   |
| 8.01-16.0  | 159       | 1.3%    |
| 16.01-24.0 | 12        | 0.1%    |
| Unknown    | 8         | 0.07%   |
| 24.01-32.0 | 7         | 0.06%   |
| 32.01-64.0 | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 8638      | 77.26%  |
| 2       | 2215      | 19.81%  |
| 3       | 230       | 2.06%   |
| 0       | 80        | 0.72%   |
| 4       | 11        | 0.1%    |
| 5       | 5         | 0.04%   |
| Unknown | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 5712      | 51.88%  |
| Yes       | 5297      | 48.12%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 9492      | 87.19%  |
| No        | 1395      | 12.81%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 10663     | 97.98%  |
| No        | 220       | 2.02%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 7640      | 69.25%  |
| No        | 3393      | 30.75%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Russia  | 10870     | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Moscow           | 2344      | 20.03%  |
| St Petersburg    | 1042      | 8.91%   |
| Novosibirsk      | 358       | 3.06%   |
| Krasnodar        | 353       | 3.02%   |
| Pecherskoye      | 337       | 2.88%   |
| Yekaterinburg    | 312       | 2.67%   |
| Voronezh         | 308       | 2.63%   |
| Nizhniy Novgorod | 225       | 1.92%   |
| Samara           | 211       | 1.8%    |
| Perm             | 197       | 1.68%   |
| Chelyabinsk      | 190       | 1.62%   |
| Rostov-on-Don    | 184       | 1.57%   |
| Kazan’         | 147       | 1.26%   |
| Krasnoyarsk      | 138       | 1.18%   |
| Saratov          | 128       | 1.09%   |
| Ufa              | 124       | 1.06%   |
| Omsk             | 106       | 0.91%   |
| Khabarovsk       | 102       | 0.87%   |
| Tyumen           | 95        | 0.81%   |
| Barnaul          | 94        | 0.8%    |
| Volgograd        | 93        | 0.79%   |
| Vladivostok      | 89        | 0.76%   |
| Kaliningrad      | 83        | 0.71%   |
| Irkutsk          | 83        | 0.71%   |
| Yaroslavl        | 82        | 0.7%    |
| Stavropol        | 78        | 0.67%   |
| Kirov            | 72        | 0.62%   |
| Tula             | 68        | 0.58%   |
| Kemerovo         | 66        | 0.56%   |
| Ryazan           | 63        | 0.54%   |
| Belgorod         | 63        | 0.54%   |
| Ulyanovsk        | 62        | 0.53%   |
| Tver             | 60        | 0.51%   |
| Tomsk            | 60        | 0.51%   |
| Surgut           | 60        | 0.51%   |
| Penza            | 55        | 0.47%   |
| Ivanovo          | 54        | 0.46%   |
| Novokuznetsk     | 51        | 0.44%   |
| Izhevsk          | 51        | 0.44%   |
| Astrakhan        | 50        | 0.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2475      | 3294   | 18.63%  |
| Seagate             | 2125      | 2775   | 15.99%  |
| Toshiba             | 1349      | 1716   | 10.15%  |
| Samsung Electronics | 1197      | 1601   | 9.01%   |
| Hitachi             | 925       | 1202   | 6.96%   |
| Kingston            | 664       | 814    | 5%      |
| Unknown             | 542       | 692    | 4.08%   |
| HGST                | 534       | 742    | 4.02%   |
| SanDisk             | 395       | 514    | 2.97%   |
| SK hynix            | 326       | 416    | 2.45%   |
| Intel               | 280       | 359    | 2.11%   |
| A-DATA Technology   | 231       | 358    | 1.74%   |
| China               | 191       | 245    | 1.44%   |
| Micron Technology   | 136       | 170    | 1.02%   |
| Fujitsu             | 133       | 161    | 1%      |
| SPCC                | 108       | 151    | 0.81%   |
| Crucial             | 104       | 127    | 0.78%   |
| OCZ                 | 86        | 102    | 0.65%   |
| Smartbuy            | 85        | 98     | 0.64%   |
| Apacer              | 80        | 92     | 0.6%    |
| KingSpec            | 78        | 97     | 0.59%   |
| Plextor             | 77        | 99     | 0.58%   |
| KIOXIA              | 75        | 88     | 0.56%   |
| Transcend           | 74        | 97     | 0.56%   |
| HUAWEI              | 69        | 77     | 0.52%   |
| Phison              | 47        | 53     | 0.35%   |
| AMD                 | 41        | 47     | 0.31%   |
| Apple               | 40        | 51     | 0.3%    |
| Patriot             | 37        | 42     | 0.28%   |
| KingDian            | 31        | 43     | 0.23%   |
| GOODRAM             | 31        | 34     | 0.23%   |
| Netac               | 30        | 40     | 0.23%   |
| Corsair             | 30        | 37     | 0.23%   |
| Silicon Motion      | 27        | 34     | 0.2%    |
| JMicron Technology  | 26        | 27     | 0.2%    |
| Unknown             | 26        | 29     | 0.2%    |
| LITEON              | 25        | 31     | 0.19%   |
| Gigabyte Technology | 25        | 29     | 0.19%   |
| LITEONIT            | 20        | 34     | 0.15%   |
| Foxline             | 20        | 20     | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB               | 247       | 1.82%   |
| Seagate ST500LT012-1DG142 500GB        | 247       | 1.82%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 239       | 1.76%   |
| Seagate ST9500325AS 500GB              | 200       | 1.47%   |
| Seagate ST1000LM035-1RK172 1TB         | 160       | 1.18%   |
| Seagate ST9320325AS 320GB              | 156       | 1.15%   |
| HGST HTS545050A7E680 500GB             | 145       | 1.07%   |
| Toshiba MQ01ABD100 1TB                 | 123       | 0.9%    |
| Toshiba MQ04ABF100 1TB                 | 106       | 0.78%   |
| Hitachi HTS543232A7A384 320GB          | 103       | 0.76%   |
| Seagate ST500LT012-9WS142 500GB        | 97        | 0.71%   |
| Seagate ST9250315AS 250GB              | 89        | 0.65%   |
| Seagate ST500LM012 HN-M500MBB 500GB    | 88        | 0.65%   |
| WDC WD5000LPVX-22V0TT0 500GB           | 87        | 0.64%   |
| Seagate ST320LT020-9YG142 320GB        | 87        | 0.64%   |
| HGST HTS545050A7E380 500GB             | 86        | 0.63%   |
| HGST HTS541010A9E680 1TB               | 83        | 0.61%   |
| Kingston SA400S37120G 120GB SSD        | 82        | 0.6%    |
| Hitachi HTS547550A9E384 500GB          | 82        | 0.6%    |
| Hitachi HTS545025B9A300 250GB          | 82        | 0.6%    |
| Kingston SA400S37240G 240GB SSD        | 81        | 0.6%    |
| WDC WD3200BPVT-22JJ5T0 320GB           | 77        | 0.57%   |
| HGST HTS721010A9E630 1TB               | 77        | 0.57%   |
| Hitachi HTS547575A9E384 752GB          | 74        | 0.54%   |
| WDC WD10JPVX-22JC3T0 1TB               | 72        | 0.53%   |
| WDC WD5000LPCX-21VHAT0 500GB           | 68        | 0.5%    |
| Kingston SV300S37A120G 120GB SSD       | 67        | 0.49%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 64        | 0.47%   |
| WDC WD5000LPCX-24VHAT0 500GB           | 64        | 0.47%   |
| Toshiba MQ01ABD075 752GB               | 59        | 0.43%   |
| Toshiba MQ01ABD050 500GB               | 56        | 0.41%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 55        | 0.4%    |
| Samsung HM321HI 320GB                  | 54        | 0.4%    |
| WDC WDS120G2G0A-00JH30 120GB SSD       | 53        | 0.39%   |
| WDC WD1600BEVT-22ZCT0 160GB            | 52        | 0.38%   |
| Hitachi HTS545050A7E380 500GB          | 51        | 0.37%   |
| Samsung NVMe SSD Drive 512GB           | 49        | 0.36%   |
| Hitachi HTS545032B9A300 320GB          | 49        | 0.36%   |
| HGST HTS725050A7E630 500GB             | 49        | 0.36%   |
| A-DATA SU800 512GB SSD                 | 49        | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2114      | 2758   | 29.17%  |
| WDC                 | 2082      | 2787   | 28.73%  |
| Toshiba             | 1195      | 1521   | 16.49%  |
| Hitachi             | 925       | 1202   | 12.76%  |
| HGST                | 534       | 742    | 7.37%   |
| Samsung Electronics | 223       | 269    | 3.08%   |
| Fujitsu             | 132       | 160    | 1.82%   |
| Unknown             | 18        | 24     | 0.25%   |
| IBM/Hitachi         | 6         | 6      | 0.08%   |
| Apple               | 4         | 4      | 0.06%   |
| KESU                | 2         | 2      | 0.03%   |
| HGST HTS            | 2         | 2      | 0.03%   |
| ZALMAN              | 1         | 1      | 0.01%   |
| WD MediaMax         | 1         | 2      | 0.01%   |
| SILICONMOTION       | 1         | 1      | 0.01%   |
| QNAP                | 1         | 2      | 0.01%   |
| PHD 3.0             | 1         | 1      | 0.01%   |
| OEM                 | 1         | 2      | 0.01%   |
| MARSHAL             | 1         | 1      | 0.01%   |
| IBM                 | 1         | 1      | 0.01%   |
| CLOVER              | 1         | 1      | 0.01%   |
| Unknown             | 1         | 1      | 0.01%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 530       | 650    | 15.31%  |
| Samsung Electronics | 515       | 686    | 14.88%  |
| SanDisk             | 252       | 339    | 7.28%   |
| WDC                 | 240       | 279    | 6.93%   |
| A-DATA Technology   | 202       | 323    | 5.84%   |
| China               | 191       | 245    | 5.52%   |
| SPCC                | 106       | 149    | 3.06%   |
| Intel               | 104       | 135    | 3%      |
| Crucial             | 101       | 124    | 2.92%   |
| OCZ                 | 86        | 102    | 2.48%   |
| Smartbuy            | 83        | 96     | 2.4%    |
| KingSpec            | 78        | 97     | 2.25%   |
| Plextor             | 77        | 99     | 2.22%   |
| SK hynix            | 75        | 94     | 2.17%   |
| Transcend           | 71        | 92     | 2.05%   |
| Apacer              | 71        | 82     | 2.05%   |
| Toshiba             | 66        | 84     | 1.91%   |
| Micron Technology   | 56        | 81     | 1.62%   |
| AMD                 | 39        | 44     | 1.13%   |
| Patriot             | 37        | 42     | 1.07%   |
| GOODRAM             | 31        | 34     | 0.9%    |
| KingDian            | 30        | 42     | 0.87%   |
| Apple               | 30        | 36     | 0.87%   |
| Corsair             | 28        | 35     | 0.81%   |
| Netac               | 24        | 32     | 0.69%   |
| LITEON              | 21        | 27     | 0.61%   |
| LITEONIT            | 20        | 34     | 0.58%   |
| JMicron Technology  | 16        | 17     | 0.46%   |
| Londisk             | 13        | 16     | 0.38%   |
| Kingmax             | 12        | 24     | 0.35%   |
| Gigabyte Technology | 12        | 14     | 0.35%   |
| XrayDisk            | 11        | 14     | 0.32%   |
| KingFast            | 10        | 12     | 0.29%   |
| Unknown             | 10        | 12     | 0.29%   |
| Zheino              | 9         | 11     | 0.26%   |
| TO Exter            | 9         | 9      | 0.26%   |
| Hewlett-Packard     | 8         | 12     | 0.23%   |
| Foxline             | 6         | 6      | 0.17%   |
| FORESEE             | 6         | 6      | 0.17%   |
| BIWIN               | 6         | 6      | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 6978      | 9490   | 54.76%  |
| SSD     | 3247      | 4451   | 25.48%  |
| NVMe    | 1793      | 2385   | 14.07%  |
| MMC     | 552       | 720    | 4.33%   |
| Unknown | 174       | 189    | 1.37%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 9127      | 13797  | 77.62%  |
| NVMe | 1785      | 2371   | 15.18%  |
| MMC  | 552       | 720    | 4.69%   |
| SAS  | 295       | 347    | 2.51%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 7570      | 10854  | 77.44%  |
| 0.51-1.0   | 2093      | 2935   | 21.41%  |
| 1.01-2.0   | 74        | 94     | 0.76%   |
| 3.01-4.0   | 29        | 47     | 0.3%    |
| 4.01-10.0  | 6         | 7      | 0.06%   |
| 20.01-50.0 | 1         | 2      | 0.01%   |
| 2.01-3.0   | 1         | 1      | 0.01%   |
| 0          | 1         | 1      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 3500      | 29.46%  |
| 251-500        | 3108      | 26.16%  |
| 1-20           | 1337      | 11.25%  |
| 501-1000       | 1256      | 10.57%  |
| 51-100         | 1094      | 9.21%   |
| 21-50          | 868       | 7.31%   |
| 1001-2000      | 374       | 3.15%   |
| Unknown        | 239       | 2.01%   |
| 2001-3000      | 74        | 0.62%   |
| More than 3000 | 31        | 0.26%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 7027      | 57.86%  |
| 21-50          | 1619      | 13.33%  |
| 101-250        | 1158      | 9.54%   |
| 51-100         | 1088      | 8.96%   |
| 251-500        | 631       | 5.2%    |
| 501-1000       | 282       | 2.32%   |
| Unknown        | 239       | 1.97%   |
| 1001-2000      | 78        | 0.64%   |
| 2001-3000      | 12        | 0.1%    |
| More than 3000 | 9         | 0.07%   |
| 0              | 1         | 0.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB           | 135       | 185    | 4.69%   |
| Seagate ST500LT012-9WS142 500GB     | 89        | 107    | 3.09%   |
| Seagate ST9320325AS 320GB           | 86        | 110    | 2.99%   |
| HGST HTS545050A7E680 500GB          | 73        | 107    | 2.54%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 69        | 83     | 2.4%    |
| Seagate ST500LT012-1DG142 500GB     | 64        | 77     | 2.22%   |
| Seagate ST9250315AS 250GB           | 61        | 77     | 2.12%   |
| Seagate ST320LT020-9YG142 320GB     | 52        | 77     | 1.81%   |
| HGST HTS545050A7E380 500GB          | 44        | 70     | 1.53%   |
| Hitachi HTS545025B9A300 250GB       | 42        | 50     | 1.46%   |
| Hitachi HTS543232A7A384 320GB       | 40        | 46     | 1.39%   |
| Seagate ST320LT012-9WS14C 320GB     | 38        | 51     | 1.32%   |
| Hitachi HTS547550A9E384 500GB       | 35        | 48     | 1.22%   |
| Hitachi HTS547575A9E384 752GB       | 34        | 47     | 1.18%   |
| Toshiba MQ01ABD050 500GB            | 29        | 36     | 1.01%   |
| Hitachi HTS541612J9SA00 120GB       | 28        | 37     | 0.97%   |
| Toshiba MQ01ABF050 500GB            | 27        | 34     | 0.94%   |
| Toshiba MK3265GSX 320GB             | 24        | 30     | 0.83%   |
| Hitachi HTS541680J9SA00 80GB        | 24        | 28     | 0.83%   |
| Seagate ST9500420AS 500GB           | 23        | 36     | 0.8%    |
| HGST HTS541010A9E680 1TB            | 23        | 36     | 0.8%    |
| Seagate ST500LM012 HN-M500MBB 500GB | 22        | 26     | 0.76%   |
| Samsung Electronics HM160HI 160GB   | 22        | 24     | 0.76%   |
| Hitachi HTS545050A7E380 500GB       | 21        | 31     | 0.73%   |
| Hitachi HTS545032B9A300 320GB       | 21        | 27     | 0.73%   |
| Toshiba MQ01ABD100 1TB              | 19        | 26     | 0.66%   |
| Hitachi HTS545050B9A300 500GB       | 19        | 25     | 0.66%   |
| Hitachi HTS542512K9SA00 120GB       | 18        | 23     | 0.63%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 17        | 18     | 0.59%   |
| WDC WD3200BPVT-22ZEST0 320GB        | 17        | 23     | 0.59%   |
| Samsung Electronics HM321HI 320GB   | 16        | 21     | 0.56%   |
| Hitachi HTS542516K9SA00 160GB       | 16        | 26     | 0.56%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 15        | 18     | 0.52%   |
| WDC WD2500BEVT-22A23T0 250GB        | 15        | 18     | 0.52%   |
| Toshiba MQ01ABD075 752GB            | 15        | 20     | 0.52%   |
| Toshiba MK3259GSXP 320GB            | 15        | 25     | 0.52%   |
| Seagate ST9160821AS 160GB           | 15        | 17     | 0.52%   |
| Samsung Electronics HM250HI 250GB   | 15        | 17     | 0.52%   |
| Hitachi HTS542525K9SA00 250GB       | 15        | 20     | 0.52%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD | 14        | 15     | 0.49%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 870       | 1112   | 30.4%   |
| Hitachi             | 502       | 634    | 17.54%  |
| WDC                 | 457       | 599    | 15.97%  |
| Toshiba             | 415       | 531    | 14.5%   |
| HGST                | 178       | 265    | 6.22%   |
| Samsung Electronics | 113       | 133    | 3.95%   |
| Kingston            | 44        | 54     | 1.54%   |
| SanDisk             | 40        | 49     | 1.4%    |
| Fujitsu             | 40        | 56     | 1.4%    |
| SK hynix            | 21        | 28     | 0.73%   |
| A-DATA Technology   | 19        | 25     | 0.66%   |
| Intel               | 18        | 29     | 0.63%   |
| OCZ                 | 15        | 15     | 0.52%   |
| China               | 12        | 17     | 0.42%   |
| KingSpec            | 11        | 12     | 0.38%   |
| SPCC                | 10        | 11     | 0.35%   |
| Crucial             | 10        | 13     | 0.35%   |
| LITEON              | 9         | 10     | 0.31%   |
| Micron Technology   | 8         | 14     | 0.28%   |
| Corsair             | 8         | 8      | 0.28%   |
| Plextor             | 6         | 8      | 0.21%   |
| LITEONIT            | 6         | 12     | 0.21%   |
| IBM/Hitachi         | 5         | 5      | 0.17%   |
| AMD                 | 5         | 7      | 0.17%   |
| Smartbuy            | 3         | 3      | 0.1%    |
| Kingmax             | 3         | 3      | 0.1%    |
| KingDian            | 3         | 6      | 0.1%    |
| Apple               | 3         | 3      | 0.1%    |
| Transcend           | 2         | 2      | 0.07%   |
| Team                | 2         | 2      | 0.07%   |
| SSSTC               | 2         | 2      | 0.07%   |
| OCZ-VERTEX3         | 2         | 2      | 0.07%   |
| Mushkin             | 2         | 2      | 0.07%   |
| Zheino              | 1         | 1      | 0.03%   |
| XrayDisk            | 1         | 1      | 0.03%   |
| Unknown             | 1         | 1      | 0.03%   |
| SemsoTai            | 1         | 1      | 0.03%   |
| SandForce           | 1         | 1      | 0.03%   |
| Netac               | 1         | 2      | 0.03%   |
| MD300               | 1         | 1      | 0.03%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 870       | 1112   | 34.18%  |
| Hitachi             | 502       | 634    | 19.72%  |
| WDC                 | 438       | 580    | 17.21%  |
| Toshiba             | 412       | 528    | 16.19%  |
| HGST                | 178       | 265    | 6.99%   |
| Samsung Electronics | 98        | 118    | 3.85%   |
| Fujitsu             | 40        | 56     | 1.57%   |
| IBM/Hitachi         | 5         | 5      | 0.2%    |
| MARSHAL             | 1         | 1      | 0.04%   |
| HGST HTS            | 1         | 1      | 0.04%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 2514      | 3300   | 88.83%  |
| SSD  | 304       | 380    | 10.74%  |
| NVMe | 12        | 14     | 0.42%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD1600BEVT-22ZCT0 160GB        | 4         | 5      | 4.35%   |
| Seagate ST9500325AS 500GB          | 4         | 4      | 4.35%   |
| Samsung Electronics HM321HI 320GB  | 4         | 5      | 4.35%   |
| HGST HTS721010A9E630 1TB           | 4         | 5      | 4.35%   |
| Toshiba MK3265GSX 320GB            | 3         | 3      | 3.26%   |
| Seagate ST9320325AS 320GB          | 3         | 3      | 3.26%   |
| HGST HTS545050A7E680 500GB         | 3         | 3      | 3.26%   |
| WDC WD3200BEVT-22ZCT0 320GB        | 2         | 2      | 2.17%   |
| WDC WD1600BEVS-22RST0 160GB        | 2         | 2      | 2.17%   |
| Toshiba MQ01ABD050 500GB           | 2         | 2      | 2.17%   |
| Toshiba MK6465GSX 640GB            | 2         | 2      | 2.17%   |
| Toshiba MK3259GSXP 320GB           | 2         | 2      | 2.17%   |
| Seagate ST500LT012-1DG142 500GB    | 2         | 2      | 2.17%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2         | 2      | 2.17%   |
| Samsung Electronics HM160HI 160GB  | 2         | 2      | 2.17%   |
| Hitachi HTS547550A9E384 500GB      | 2         | 2      | 2.17%   |
| Hitachi HTS543225A7A384 250GB      | 2         | 3      | 2.17%   |
| HGST HTS541010A9E680 1TB           | 2         | 2      | 2.17%   |
| WDC WD800BEVS-22RST0 80GB          | 1         | 1      | 1.09%   |
| WDC WD7500BPVT-22HXZT3 752GB       | 1         | 1      | 1.09%   |
| WDC WD7500BPVT-22HXZT1 752GB       | 1         | 1      | 1.09%   |
| WDC WD5000M22K-24Z1LT0-SSHD-16GB   | 1         | 1      | 1.09%   |
| WDC WD5000LPCX-24VHAT0 500GB       | 1         | 1      | 1.09%   |
| WDC WD5000BPVT-80HXZT1 500GB       | 1         | 1      | 1.09%   |
| WDC WD5000BPVT-24HXZT3 500GB       | 1         | 1      | 1.09%   |
| WDC WD5000BEVT-35ZAT0 500GB        | 1         | 1      | 1.09%   |
| WDC WD5000BEVT-22A0RT0 500GB       | 1         | 1      | 1.09%   |
| WDC WD3200BPVT-80ZEST0 320GB       | 1         | 1      | 1.09%   |
| WDC WD3200BPVT-22JJ5T0 320GB       | 1         | 1      | 1.09%   |
| WDC WD3200BEVS-0 320GB             | 1         | 1      | 1.09%   |
| WDC WD2500LPCX-24C6HT0 250GB       | 1         | 1      | 1.09%   |
| WDC WD2500BEVT-24A23T0 250GB       | 1         | 1      | 1.09%   |
| WDC WD2500BEVT-22ZCT0 250GB        | 1         | 1      | 1.09%   |
| WDC WD1600BEVT-75ZCT2 160GB        | 1         | 1      | 1.09%   |
| WDC WD1200BEVS-07LAT0 120GB        | 1         | 1      | 1.09%   |
| WDC WD10JPVX-22JC3T0 1TB           | 1         | 1      | 1.09%   |
| Toshiba MK8037GSX 80GB             | 1         | 1      | 1.09%   |
| Toshiba MK8025GAL 80GB             | 1         | 2      | 1.09%   |
| Toshiba MK7575GSX 752GB            | 1         | 2      | 1.09%   |
| Toshiba MK5065GSXN 500GB           | 1         | 1      | 1.09%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 26        | 27     | 28.26%  |
| Toshiba             | 16        | 18     | 17.39%  |
| Seagate             | 16        | 18     | 17.39%  |
| Samsung Electronics | 14        | 15     | 15.22%  |
| HGST                | 11        | 13     | 11.96%  |
| Hitachi             | 7         | 9      | 7.61%   |
| Fujitsu             | 1         | 1      | 1.09%   |
| Apple               | 1         | 2      | 1.09%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 6451      | 9643   | 53.91%  |
| Malfunc  | 2793      | 3694   | 23.34%  |
| Detected | 2629      | 3794   | 21.97%  |
| Failed   | 92        | 103    | 0.77%   |
| Limited  | 1         | 1      | 0.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 7859      | 66.3%   |
| AMD                              | 2014      | 16.99%  |
| Samsung Electronics              | 504       | 4.25%   |
| SanDisk                          | 276       | 2.33%   |
| SK hynix                         | 238       | 2.01%   |
| Kingston Technology Company      | 137       | 1.16%   |
| Nvidia                           | 117       | 0.99%   |
| Toshiba America Info Systems     | 93        | 0.78%   |
| Phison Electronics               | 93        | 0.78%   |
| KIOXIA                           | 85        | 0.72%   |
| Micron Technology                | 80        | 0.67%   |
| Silicon Integrated Systems [SiS] | 74        | 0.62%   |
| Union Memory (Shenzhen)          | 53        | 0.45%   |
| Silicon Motion                   | 39        | 0.33%   |
| Solid State Storage Technology   | 32        | 0.27%   |
| JMicron Technology               | 32        | 0.27%   |
| ADATA Technology                 | 26        | 0.22%   |
| Realtek Semiconductor            | 21        | 0.18%   |
| VIA Technologies                 | 12        | 0.1%    |
| INNOGRIT                         | 9         | 0.08%   |
| Shenzhen Longsys Electronics     | 8         | 0.07%   |
| Lite-On Technology               | 7         | 0.06%   |
| Lenovo                           | 6         | 0.05%   |
| Micron/Crucial Technology        | 5         | 0.04%   |
| ASMedia Technology               | 5         | 0.04%   |
| Apple                            | 5         | 0.04%   |
| Yangtze Memory Technologies      | 4         | 0.03%   |
| Netac Technology                 | 3         | 0.03%   |
| MAXIO Technology (Hangzhou)      | 3         | 0.03%   |
| Marvell Technology Group         | 3         | 0.03%   |
| Zhaoxin                          | 2         | 0.02%   |
| Silicon Image                    | 2         | 0.02%   |
| Seagate Technology               | 2         | 0.02%   |
| Unknown                          | 2         | 0.02%   |
| ULi Electronics                  | 1         | 0.01%   |
| Transcend                        | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 1366      | 10.4%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 1278      | 9.73%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 886       | 6.75%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 622       | 4.74%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 502       | 3.82%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 491       | 3.74%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 413       | 3.14%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 386       | 2.94%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 360       | 2.74%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 301       | 2.29%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 300       | 2.28%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 289       | 2.2%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 237       | 1.8%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 233       | 1.77%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 229       | 1.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 193       | 1.47%   |
| Samsung NVMe SSD Controller 980                                                  | 190       | 1.45%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 168       | 1.28%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 164       | 1.25%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 162       | 1.23%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 139       | 1.06%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 134       | 1.02%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 117       | 0.89%   |
| Intel Comet Lake SATA AHCI Controller                                            | 112       | 0.85%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 111       | 0.85%   |
| AMD SB600 Non-Raid-5 SATA                                                        | 111       | 0.85%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 108       | 0.82%   |
| AMD SB600 IDE                                                                    | 108       | 0.82%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 104       | 0.79%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 103       | 0.78%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 100       | 0.76%   |
| Intel Volume Management Device NVMe RAID Controller                              | 95        | 0.72%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 88        | 0.67%   |
| Intel SSD 660P Series                                                            | 86        | 0.65%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 86        | 0.65%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 86        | 0.65%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 83        | 0.63%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 83        | 0.63%   |
| Micron Non-Volatile memory controller                                            | 80        | 0.61%   |
| Intel Tiger Lake-LP SATA Controller                                              | 80        | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 8837      | 70.36%  |
| NVMe | 1807      | 14.39%  |
| IDE  | 1512      | 12.04%  |
| RAID | 404       | 3.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 8525      | 78.41%  |
| AMD          | 2336      | 21.49%  |
| CentaurHauls | 5         | 0.05%   |
| ARM          | 3         | 0.03%   |
| Unknown      | 2         | 0.02%   |
| PowerBook5,6 | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-3210M CPU @ 2.50GHz             | 153       | 1.4%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 139       | 1.27%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 138       | 1.27%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 138       | 1.27%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 124       | 1.14%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 122       | 1.12%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 122       | 1.12%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 112       | 1.03%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 106       | 0.97%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 105       | 0.96%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 99        | 0.91%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 97        | 0.89%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 95        | 0.87%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 94        | 0.86%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 94        | 0.86%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 93        | 0.85%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 92        | 0.84%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 91        | 0.83%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 88        | 0.81%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 85        | 0.78%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 85        | 0.78%   |
| AMD E-450 APU with Radeon HD Graphics         | 85        | 0.78%   |
| Intel Atom CPU N455 @ 1.66GHz                 | 80        | 0.73%   |
| Intel Atom CPU N2600 @ 1.60GHz                | 78        | 0.72%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 76        | 0.7%    |
| Intel Core i3-5005U CPU @ 2.00GHz             | 75        | 0.69%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 74        | 0.68%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 71        | 0.65%   |
| Intel Core i3-3120M CPU @ 2.50GHz             | 71        | 0.65%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 70        | 0.64%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 66        | 0.61%   |
| AMD A10-4600M APU with Radeon HD Graphics     | 66        | 0.61%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 65        | 0.6%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 63        | 0.58%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 61        | 0.56%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 60        | 0.55%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 59        | 0.54%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 59        | 0.54%   |
| Intel Atom CPU N570 @ 1.66GHz                 | 59        | 0.54%   |
| Intel Core i3 CPU M 350 @ 2.27GHz             | 58        | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 2080      | 19.08%  |
| Intel Core i3                  | 1440      | 13.21%  |
| Intel Core i7                  | 1067      | 9.79%   |
| Intel Celeron                  | 817       | 7.5%    |
| Intel Pentium                  | 793       | 7.28%   |
| Intel Atom                     | 684       | 6.28%   |
| Intel Core 2 Duo               | 602       | 5.52%   |
| AMD Ryzen 5                    | 383       | 3.51%   |
| Other                          | 313       | 2.87%   |
| AMD A6                         | 236       | 2.17%   |
| Intel Pentium Dual-Core        | 195       | 1.79%   |
| AMD Ryzen 7                    | 177       | 1.62%   |
| AMD A8                         | 162       | 1.49%   |
| AMD A4                         | 156       | 1.43%   |
| AMD E                          | 146       | 1.34%   |
| AMD A10                        | 146       | 1.34%   |
| AMD E1                         | 113       | 1.04%   |
| AMD Ryzen 3                    | 109       | 1%      |
| Intel Genuine                  | 99        | 0.91%   |
| Intel Pentium Dual             | 97        | 0.89%   |
| AMD E2                         | 95        | 0.87%   |
| Intel Core 2                   | 92        | 0.84%   |
| Intel Celeron M                | 72        | 0.66%   |
| AMD Phenom II                  | 69        | 0.63%   |
| Intel Celeron Dual-Core        | 67        | 0.61%   |
| AMD Turion 64 X2 Mobile        | 67        | 0.61%   |
| Intel Pentium Silver           | 61        | 0.56%   |
| Intel Pentium M                | 53        | 0.49%   |
| AMD Athlon                     | 40        | 0.37%   |
| AMD C-60                       | 36        | 0.33%   |
| AMD Athlon II                  | 33        | 0.3%    |
| AMD Athlon X2                  | 26        | 0.24%   |
| AMD Turion II Dual-Core        | 25        | 0.23%   |
| AMD Athlon 64 X2               | 25        | 0.23%   |
| AMD Turion X2 Dual-Core Mobile | 23        | 0.21%   |
| AMD C-50                       | 20        | 0.18%   |
| Intel Core Duo                 | 19        | 0.17%   |
| AMD Athlon II Dual-Core        | 18        | 0.17%   |
| AMD Ryzen 7 PRO                | 17        | 0.16%   |
| AMD Turion II                  | 16        | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 6748      | 61.66%  |
| 4       | 2631      | 24.04%  |
| 1       | 676       | 6.18%   |
| 6       | 355       | 3.24%   |
| Unknown | 287       | 2.62%   |
| 8       | 204       | 1.86%   |
| 3       | 24        | 0.22%   |
| 14      | 10        | 0.09%   |
| 12      | 5         | 0.05%   |
| 10      | 2         | 0.02%   |
| 192     | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 10856     | 99.81%  |
| Unknown | 15        | 0.14%   |
| 2       | 4         | 0.04%   |
| 4       | 2         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 6139      | 55.99%  |
| 1       | 4537      | 41.38%  |
| Unknown | 287       | 2.62%   |
| 4       | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 10397     | 95.49%  |
| 32-bit         | 363       | 3.33%   |
| Unknown        | 126       | 1.16%   |
| 64-bit         | 2         | 0.02%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 1249      | 11.26%  |
| 0x306a9    | 1014      | 9.14%   |
| Unknown    | 954       | 8.6%    |
| 0x1067a    | 454       | 4.09%   |
| 0x20655    | 441       | 3.98%   |
| 0x6fd      | 331       | 2.98%   |
| 0x106ca    | 297       | 2.68%   |
| 0x40651    | 290       | 2.61%   |
| 0x806ec    | 278       | 2.51%   |
| 0x30678    | 263       | 2.37%   |
| 0x806ea    | 262       | 2.36%   |
| 0x306c3    | 233       | 2.1%    |
| 0x406e3    | 230       | 2.07%   |
| 0x806e9    | 208       | 1.88%   |
| 0x906ea    | 182       | 1.64%   |
| 0x06001119 | 173       | 1.56%   |
| 0x806c1    | 170       | 1.53%   |
| 0x05000119 | 168       | 1.51%   |
| 0x406c4    | 167       | 1.51%   |
| 0x306d4    | 166       | 1.5%    |
| 0x10676    | 155       | 1.4%    |
| 0x08108109 | 153       | 1.38%   |
| 0x07030105 | 150       | 1.35%   |
| 0x20652    | 142       | 1.28%   |
| 0x03000027 | 139       | 1.25%   |
| 0x06006705 | 135       | 1.22%   |
| 0x010000c8 | 129       | 1.16%   |
| 0x30661    | 120       | 1.08%   |
| 0x08108102 | 114       | 1.03%   |
| 0x106c2    | 112       | 1.01%   |
| 0x406c3    | 107       | 0.96%   |
| 0x10661    | 102       | 0.92%   |
| 0x506c9    | 93        | 0.84%   |
| 0x706a1    | 83        | 0.75%   |
| 0x08600106 | 78        | 0.7%    |
| 0x706e5    | 77        | 0.69%   |
| 0x6e8      | 77        | 0.69%   |
| 0x906e9    | 74        | 0.67%   |
| 0x6f6      | 74        | 0.67%   |
| 0x0a50000c | 72        | 0.65%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| SandyBridge      | 1305      | 11.98%  |
| KabyLake         | 1252      | 11.49%  |
| IvyBridge        | 1062      | 9.75%   |
| Penryn           | 619       | 5.68%   |
| Core             | 616       | 5.65%   |
| Westmere         | 606       | 5.56%   |
| Silvermont       | 590       | 5.41%   |
| Haswell          | 570       | 5.23%   |
| Bonnell          | 510       | 4.68%   |
| Skylake          | 295       | 2.71%   |
| Zen+             | 281       | 2.58%   |
| Excavator        | 261       | 2.4%    |
| Bobcat           | 248       | 2.28%   |
| Unknown          | 230       | 2.11%   |
| TigerLake        | 204       | 1.87%   |
| Piledriver       | 198       | 1.82%   |
| Zen 2            | 195       | 1.79%   |
| Puma             | 194       | 1.78%   |
| K10              | 186       | 1.71%   |
| Broadwell        | 182       | 1.67%   |
| P6               | 174       | 1.6%    |
| K10 Llano        | 156       | 1.43%   |
| K8 Hammer        | 143       | 1.31%   |
| Goldmont plus    | 141       | 1.29%   |
| IceLake          | 108       | 0.99%   |
| Goldmont         | 108       | 0.99%   |
| Zen 3            | 95        | 0.87%   |
| Jaguar           | 87        | 0.8%    |
| CometLake        | 75        | 0.69%   |
| K8 & K10 hybrid  | 68        | 0.62%   |
| Zen              | 67        | 0.61%   |
| Nehalem          | 23        | 0.21%   |
| Steamroller      | 15        | 0.14%   |
| Alderlake Hybrid | 15        | 0.14%   |
| Tremont          | 12        | 0.11%   |
| NetBurst         | 5         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 7302      | 52.11%  |
| AMD                              | 3443      | 24.57%  |
| Nvidia                           | 3222      | 22.99%  |
| Silicon Integrated Systems [SiS] | 33        | 0.24%   |
| VIA Technologies                 | 9         | 0.06%   |
| Zhaoxin                          | 2         | 0.01%   |
| ATI Technologies                 | 2         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1170      | 7.78%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1032      | 6.86%   |
| Intel Core Processor Integrated Graphics Controller                                      | 331       | 2.2%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 326       | 2.17%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 313       | 2.08%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 309       | 2.06%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 299       | 1.99%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 297       | 1.98%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 291       | 1.94%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 290       | 1.93%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 238       | 1.58%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 230       | 1.53%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 230       | 1.53%   |
| Intel UHD Graphics 620                                                                   | 229       | 1.52%   |
| Intel HD Graphics 620                                                                    | 221       | 1.47%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 212       | 1.41%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 210       | 1.4%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 201       | 1.34%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 201       | 1.34%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 200       | 1.33%   |
| AMD Renoir                                                                               | 194       | 1.29%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 192       | 1.28%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 186       | 1.24%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 163       | 1.08%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 162       | 1.08%   |
| Intel HD Graphics 5500                                                                   | 150       | 1%      |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 150       | 1%      |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 146       | 0.97%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 133       | 0.88%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 121       | 0.8%    |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 120       | 0.8%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 109       | 0.72%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 105       | 0.7%    |
| AMD Lucienne                                                                             | 105       | 0.7%    |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 104       | 0.69%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 103       | 0.69%   |
| Nvidia GM108M [GeForce 840M]                                                             | 102       | 0.68%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                        | 100       | 0.67%   |
| Nvidia GT218M [GeForce 310M]                                                             | 98        | 0.65%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 91        | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 4303      | 39.45%  |
| Intel + Nvidia     | 2462      | 22.57%  |
| 1 x AMD            | 2189      | 20.07%  |
| 1 x Nvidia         | 626       | 5.74%   |
| 2 x AMD            | 577       | 5.29%   |
| Intel + AMD        | 547       | 5.01%   |
| AMD + Nvidia       | 136       | 1.25%   |
| 1 x SiS            | 33        | 0.3%    |
| Other              | 14        | 0.13%   |
| 1 x VIA            | 9         | 0.08%   |
| 2 x Intel          | 6         | 0.06%   |
| 2 x Nvidia         | 3         | 0.03%   |
| 1 x Zhaoxin        | 2         | 0.02%   |
| Intel + 2 x Nvidia | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 9634      | 86.7%   |
| Proprietary | 947       | 8.52%   |
| Unknown     | 531       | 4.78%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 3706      | 32.7%   |
| 1.01-2.0   | 3236      | 28.55%  |
| 0.01-0.5   | 2757      | 24.33%  |
| 0.51-1.0   | 871       | 7.69%   |
| 3.01-4.0   | 663       | 5.85%   |
| 5.01-6.0   | 58        | 0.51%   |
| 7.01-8.0   | 20        | 0.18%   |
| 2.01-3.0   | 19        | 0.17%   |
| 8.01-16.0  | 3         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 2392      | 21.61%  |
| LG Display              | 1735      | 15.67%  |
| Samsung Electronics     | 1514      | 13.68%  |
| Chimei Innolux          | 1272      | 11.49%  |
| BOE                     | 1227      | 11.09%  |
| Chi Mei Optoelectronics | 770       | 6.96%   |
| LG Philips              | 217       | 1.96%   |
| Lenovo                  | 183       | 1.65%   |
| HannStar                | 170       | 1.54%   |
| PANDA                   | 125       | 1.13%   |
| Goldstar                | 118       | 1.07%   |
| CPT                     | 114       | 1.03%   |
| Dell                    | 111       | 1%      |
| InfoVision              | 108       | 0.98%   |
| BenQ                    | 96        | 0.87%   |
| Sharp                   | 90        | 0.81%   |
| Apple                   | 90        | 0.81%   |
| Acer                    | 79        | 0.71%   |
| Philips                 | 63        | 0.57%   |
| Sony                    | 57        | 0.51%   |
| AOC                     | 54        | 0.49%   |
| Ancor Communications    | 44        | 0.4%    |
| Hewlett-Packard         | 42        | 0.38%   |
| ViewSonic               | 39        | 0.35%   |
| InnoLux Display         | 30        | 0.27%   |
| Iiyama                  | 30        | 0.27%   |
| Quanta Display          | 26        | 0.23%   |
| CSO                     | 25        | 0.23%   |
| NEC Computers           | 24        | 0.22%   |
| Toshiba                 | 23        | 0.21%   |
| TMX                     | 13        | 0.12%   |
| Nvidia                  | 11        | 0.1%    |
| Unknown                 | 10        | 0.09%   |
| Panasonic               | 10        | 0.09%   |
| S2-Tek                  | 8         | 0.07%   |
| MiTAC                   | 7         | 0.06%   |
| GDH                     | 7         | 0.06%   |
| ASUSTek Computer        | 7         | 0.06%   |
| Mi                      | 6         | 0.05%   |
| JDI                     | 6         | 0.05%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 224       | 2.01%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 191       | 1.71%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 161       | 1.44%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 152       | 1.36%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 146       | 1.31%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 103       | 0.92%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch      | 99        | 0.89%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 95        | 0.85%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch             | 91        | 0.82%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                      | 86        | 0.77%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 85        | 0.76%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 83        | 0.74%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                  | 74        | 0.66%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch             | 71        | 0.64%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch  | 69        | 0.62%   |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch             | 69        | 0.62%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch      | 67        | 0.6%    |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch               | 66        | 0.59%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch          | 64        | 0.57%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch            | 64        | 0.57%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch             | 63        | 0.57%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 62        | 0.56%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x193mm 15.5-inch                   | 61        | 0.55%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch             | 58        | 0.52%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                     | 57        | 0.51%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 56        | 0.5%    |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                     | 54        | 0.48%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch  | 50        | 0.45%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch             | 50        | 0.45%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch             | 50        | 0.45%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch           | 49        | 0.44%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch               | 48        | 0.43%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch               | 48        | 0.43%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch           | 47        | 0.42%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 45        | 0.4%    |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                     | 42        | 0.38%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch               | 41        | 0.37%   |
| LG Display LCD Monitor LGD01E8 1366x768 344x194mm 15.5-inch               | 41        | 0.37%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch             | 41        | 0.37%   |
| Chi Mei Optoelectronics LCD Monitor CMO1526 1280x800 331x207mm 15.4-inch  | 40        | 0.36%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 4663      | 43.21%  |
| 1920x1080 (FHD)    | 3211      | 29.75%  |
| 1280x800 (WXGA)    | 747       | 6.92%   |
| 1600x900 (HD+)     | 741       | 6.87%   |
| 1024x600           | 371       | 3.44%   |
| 1440x900 (WXGA+)   | 168       | 1.56%   |
| 3840x2160 (4K)     | 146       | 1.35%   |
| 1280x1024 (SXGA)   | 118       | 1.09%   |
| 1920x1200 (WUXGA)  | 111       | 1.03%   |
| 2560x1440 (QHD)    | 92        | 0.85%   |
| 1680x1050 (WSXGA+) | 83        | 0.77%   |
| 2160x1440          | 39        | 0.36%   |
| 2560x1600          | 37        | 0.34%   |
| 1024x768 (XGA)     | 35        | 0.32%   |
| 2880x1800          | 21        | 0.19%   |
| 1360x768           | 18        | 0.17%   |
| 1280x720 (HD)      | 17        | 0.16%   |
| 2560x1080          | 16        | 0.15%   |
| 2288x1287          | 15        | 0.14%   |
| 1680x945           | 14        | 0.13%   |
| 3440x1440          | 13        | 0.12%   |
| 3000x2000          | 10        | 0.09%   |
| 3200x2000          | 9         | 0.08%   |
| 2520x1680          | 9         | 0.08%   |
| 1400x1050          | 9         | 0.08%   |
| 3840x2400          | 7         | 0.06%   |
| 3200x1800 (QHD+)   | 7         | 0.06%   |
| 1600x1200          | 7         | 0.06%   |
| 800x1280           | 6         | 0.06%   |
| Unknown            | 6         | 0.06%   |
| 3456x2160          | 5         | 0.05%   |
| 2240x1400          | 5         | 0.05%   |
| 1920x540           | 5         | 0.05%   |
| 2256x1504          | 4         | 0.04%   |
| 1024x576           | 4         | 0.04%   |
| 2736x1824          | 3         | 0.03%   |
| 1280x768           | 2         | 0.02%   |
| 1152x864           | 2         | 0.02%   |
| 7040x1440          | 1         | 0.01%   |
| 4480x1440          | 1         | 0.01%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 6366      | 57.55%  |
| 17      | 1004      | 9.08%   |
| 13      | 893       | 8.07%   |
| 14      | 823       | 7.44%   |
| 10      | 375       | 3.39%   |
| 11      | 228       | 2.06%   |
| 12      | 195       | 1.76%   |
| 24      | 179       | 1.62%   |
| 23      | 155       | 1.4%    |
| 21      | 137       | 1.24%   |
| 27      | 126       | 1.14%   |
| 19      | 89        | 0.8%    |
| 16      | 80        | 0.72%   |
| 18      | 79        | 0.71%   |
| Unknown | 49        | 0.44%   |
| 20      | 34        | 0.31%   |
| 22      | 30        | 0.27%   |
| 34      | 29        | 0.26%   |
| 31      | 29        | 0.26%   |
| 8       | 23        | 0.21%   |
| 32      | 17        | 0.15%   |
| 54      | 15        | 0.14%   |
| 52      | 15        | 0.14%   |
| 26      | 12        | 0.11%   |
| 42      | 9         | 0.08%   |
| 84      | 8         | 0.07%   |
| 40      | 8         | 0.07%   |
| 72      | 7         | 0.06%   |
| 142     | 6         | 0.05%   |
| 48      | 4         | 0.04%   |
| 46      | 4         | 0.04%   |
| 28      | 4         | 0.04%   |
| 25      | 4         | 0.04%   |
| 36      | 3         | 0.03%   |
| 9       | 3         | 0.03%   |
| 65      | 2         | 0.02%   |
| 50      | 2         | 0.02%   |
| 37      | 2         | 0.02%   |
| 29      | 2         | 0.02%   |
| 7       | 2         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 7494      | 68.11%  |
| 201-300        | 1294      | 11.76%  |
| 351-400        | 1199      | 10.9%   |
| 501-600        | 456       | 4.14%   |
| 401-500        | 305       | 2.77%   |
| 701-800        | 50        | 0.45%   |
| Unknown        | 49        | 0.45%   |
| 1001-1500      | 45        | 0.41%   |
| 601-700        | 40        | 0.36%   |
| 101-200        | 23        | 0.21%   |
| 1501-2000      | 16        | 0.15%   |
| 901-1000       | 12        | 0.11%   |
| 801-900        | 10        | 0.09%   |
| More than 2000 | 7         | 0.06%   |
| 1-100          | 2         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 8918      | 85.34%  |
| 16/10   | 1198      | 11.46%  |
| 5/4     | 102       | 0.98%   |
| 3/2     | 89        | 0.85%   |
| 4/3     | 70        | 0.67%   |
| 21/9    | 33        | 0.32%   |
| Unknown | 21        | 0.2%    |
| 1.00    | 6         | 0.06%   |
| 6/5     | 5         | 0.05%   |
| 0.62    | 4         | 0.04%   |
| 0.67    | 2         | 0.02%   |
| 3.73    | 1         | 0.01%   |
| 1.96    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 6354      | 57.45%  |
| 81-90          | 1306      | 11.81%  |
| 121-130        | 777       | 7.03%   |
| 201-250        | 420       | 3.8%    |
| 71-80          | 399       | 3.61%   |
| 41-50          | 378       | 3.42%   |
| 51-60          | 228       | 2.06%   |
| 131-140        | 185       | 1.67%   |
| 61-70          | 180       | 1.63%   |
| 151-200        | 159       | 1.44%   |
| 301-350        | 134       | 1.21%   |
| 141-150        | 116       | 1.05%   |
| 91-100         | 86        | 0.78%   |
| 351-500        | 82        | 0.74%   |
| More than 1000 | 63        | 0.57%   |
| 251-300        | 53        | 0.48%   |
| Unknown        | 49        | 0.44%   |
| 111-120        | 38        | 0.34%   |
| 501-1000       | 28        | 0.25%   |
| 1-40           | 25        | 0.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 5076      | 46.48%  |
| 121-160       | 3222      | 29.5%   |
| 51-100        | 2054      | 18.81%  |
| 161-240       | 346       | 3.17%   |
| More than 240 | 106       | 0.97%   |
| 1-50          | 69        | 0.63%   |
| Unknown       | 49        | 0.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 9839      | 88.96%  |
| 2     | 873       | 7.89%   |
| 0     | 310       | 2.8%    |
| 3     | 38        | 0.34%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 6348      | 34.55%  |
| Qualcomm Atheros                       | 4538      | 24.7%   |
| Intel                                  | 3160      | 17.2%   |
| Broadcom                               | 1759      | 9.57%   |
| Marvell Technology Group               | 458       | 2.49%   |
| Broadcom Limited                       | 417       | 2.27%   |
| Ralink                                 | 334       | 1.82%   |
| Huawei Technologies                    | 209       | 1.14%   |
| MediaTek                               | 148       | 0.81%   |
| JMicron Technology                     | 111       | 0.6%    |
| Attansic Technology                    | 105       | 0.57%   |
| TP-Link                                | 74        | 0.4%    |
| Ralink Technology                      | 70        | 0.38%   |
| Nvidia                                 | 65        | 0.35%   |
| Xiaomi                                 | 61        | 0.33%   |
| Silicon Integrated Systems [SiS]       | 47        | 0.26%   |
| Samsung Electronics                    | 40        | 0.22%   |
| ZTE WCDMA Technologies MSM             | 33        | 0.18%   |
| D-Link                                 | 31        | 0.17%   |
| ASUSTek Computer                       | 27        | 0.15%   |
| Qualcomm                               | 26        | 0.14%   |
| Ericsson Business Mobile Networks      | 24        | 0.13%   |
| Hewlett-Packard                        | 22        | 0.12%   |
| Qualcomm Atheros Communications        | 20        | 0.11%   |
| Gemtek                                 | 20        | 0.11%   |
| Sierra Wireless                        | 19        | 0.1%    |
| ASIX Electronics                       | 17        | 0.09%   |
| Dell                                   | 16        | 0.09%   |
| Vimtron Electronics                    | 12        | 0.07%   |
| Lenovo                                 | 12        | 0.07%   |
| Fibocom                                | 12        | 0.07%   |
| VIA Technologies                       | 8         | 0.04%   |
| HTC (High Tech Computer)               | 7         | 0.04%   |
| HMD Global                             | 7         | 0.04%   |
| T & A Mobile Phones                    | 6         | 0.03%   |
| Sony Ericsson Mobile Communications AB | 6         | 0.03%   |
| D-Link System                          | 6         | 0.03%   |
| Apple                                  | 6         | 0.03%   |
| NTmore                                 | 5         | 0.03%   |
| ICS Advent                             | 4         | 0.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 3810      | 17.98%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 1577      | 7.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1323      | 6.24%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 741       | 3.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 581       | 2.74%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 549       | 2.59%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 462       | 2.18%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 391       | 1.84%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 332       | 1.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 304       | 1.43%   |
| Broadcom BCM43142 802.11b/g/n                                           | 292       | 1.38%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 268       | 1.26%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 259       | 1.22%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 258       | 1.22%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 229       | 1.08%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 196       | 0.92%   |
| Intel Wireless 8265 / 8275                                              | 193       | 0.91%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 188       | 0.89%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 181       | 0.85%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 179       | 0.84%   |
| Intel Wi-Fi 6 AX200                                                     | 169       | 0.8%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 167       | 0.79%   |
| Intel Wireless 7265                                                     | 162       | 0.76%   |
| Intel Wi-Fi 6 AX201                                                     | 158       | 0.75%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 155       | 0.73%   |
| Intel WiFi Link 5100                                                    | 145       | 0.68%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 138       | 0.65%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 136       | 0.64%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 135       | 0.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 129       | 0.61%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 128       | 0.6%    |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 127       | 0.6%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 124       | 0.59%   |
| Intel Wireless 3165                                                     | 122       | 0.58%   |
| Intel Centrino Wireless-N 130                                           | 120       | 0.57%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 118       | 0.56%   |
| Intel Wireless 7260                                                     | 117       | 0.55%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 117       | 0.55%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 116       | 0.55%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 113       | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros                | 3910      | 35.63%  |
| Intel                           | 3040      | 27.7%   |
| Realtek Semiconductor           | 1837      | 16.74%  |
| Broadcom                        | 1259      | 11.47%  |
| Ralink                          | 334       | 3.04%   |
| Broadcom Limited                | 222       | 2.02%   |
| MediaTek                        | 113       | 1.03%   |
| Ralink Technology               | 70        | 0.64%   |
| TP-Link                         | 49        | 0.45%   |
| ASUSTek Computer                | 25        | 0.23%   |
| Qualcomm Atheros Communications | 20        | 0.18%   |
| Sierra Wireless                 | 19        | 0.17%   |
| D-Link                          | 16        | 0.15%   |
| Fibocom                         | 12        | 0.11%   |
| Dell                            | 9         | 0.08%   |
| D-Link System                   | 6         | 0.05%   |
| Qualcomm                        | 4         | 0.04%   |
| Tenda                           | 3         | 0.03%   |
| Micro Star International        | 3         | 0.03%   |
| Mercucys                        | 3         | 0.03%   |
| Hewlett-Packard                 | 3         | 0.03%   |
| Edimax Technology               | 3         | 0.03%   |
| Xiaomi                          | 2         | 0.02%   |
| Fujitsu Siemens Computers       | 2         | 0.02%   |
| ZyXEL Communications            | 1         | 0.01%   |
| Wacom                           | 1         | 0.01%   |
| Quectel Wireless Solutions      | 1         | 0.01%   |
| Qcom                            | 1         | 0.01%   |
| NetGear                         | 1         | 0.01%   |
| Microsoft                       | 1         | 0.01%   |
| Linksys                         | 1         | 0.01%   |
| ASUSTek Computer (wrong ID)     | 1         | 0.01%   |
| Askey Computer                  | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1323      | 12.01%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 741       | 6.73%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 581       | 5.28%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 549       | 4.98%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 462       | 4.19%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 391       | 3.55%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 332       | 3.01%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 304       | 2.76%   |
| Broadcom BCM43142 802.11b/g/n                                           | 292       | 2.65%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 268       | 2.43%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 259       | 2.35%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 196       | 1.78%   |
| Intel Wireless 8265 / 8275                                              | 193       | 1.75%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 181       | 1.64%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 179       | 1.63%   |
| Intel Wi-Fi 6 AX200                                                     | 169       | 1.53%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 167       | 1.52%   |
| Intel Wireless 7265                                                     | 162       | 1.47%   |
| Intel Wi-Fi 6 AX201                                                     | 158       | 1.43%   |
| Intel WiFi Link 5100                                                    | 145       | 1.32%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 136       | 1.23%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 135       | 1.23%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 127       | 1.15%   |
| Intel Wireless 3165                                                     | 122       | 1.11%   |
| Intel Centrino Wireless-N 130                                           | 120       | 1.09%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 118       | 1.07%   |
| Intel Wireless 7260                                                     | 117       | 1.06%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 117       | 1.06%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 99        | 0.9%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 98        | 0.89%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 96        | 0.87%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 87        | 0.79%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 84        | 0.76%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 82        | 0.74%   |
| Intel Centrino Wireless-N 2230                                          | 81        | 0.74%   |
| Intel WiMAX/WiFi Link 5150                                              | 78        | 0.71%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 76        | 0.69%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 73        | 0.66%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 73        | 0.66%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 68        | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 5664      | 57.36%  |
| Qualcomm Atheros                       | 1334      | 13.51%  |
| Intel                                  | 782       | 7.92%   |
| Broadcom                               | 664       | 6.72%   |
| Marvell Technology Group               | 458       | 4.64%   |
| Broadcom Limited                       | 204       | 2.07%   |
| JMicron Technology                     | 111       | 1.12%   |
| Attansic Technology                    | 105       | 1.06%   |
| Nvidia                                 | 64        | 0.65%   |
| Huawei Technologies                    | 64        | 0.65%   |
| Xiaomi                                 | 59        | 0.6%    |
| Silicon Integrated Systems [SiS]       | 46        | 0.47%   |
| Samsung Electronics                    | 40        | 0.41%   |
| ZTE WCDMA Technologies MSM             | 33        | 0.33%   |
| MediaTek                               | 33        | 0.33%   |
| TP-Link                                | 25        | 0.25%   |
| Qualcomm                               | 22        | 0.22%   |
| Gemtek                                 | 20        | 0.2%    |
| ASIX Electronics                       | 17        | 0.17%   |
| D-Link                                 | 15        | 0.15%   |
| Vimtron Electronics                    | 12        | 0.12%   |
| Lenovo                                 | 12        | 0.12%   |
| VIA Technologies                       | 8         | 0.08%   |
| HTC (High Tech Computer)               | 7         | 0.07%   |
| HMD Global                             | 7         | 0.07%   |
| Hewlett-Packard                        | 7         | 0.07%   |
| Apple                                  | 6         | 0.06%   |
| Sony Ericsson Mobile Communications AB | 5         | 0.05%   |
| NTmore                                 | 5         | 0.05%   |
| T & A Mobile Phones                    | 4         | 0.04%   |
| ICS Advent                             | 4         | 0.04%   |
| GCT Semiconductor                      | 4         | 0.04%   |
| DisplayLink                            | 4         | 0.04%   |
| Android                                | 4         | 0.04%   |
| OPPO Electronics                       | 3         | 0.03%   |
| LG Electronics                         | 3         | 0.03%   |
| ASUSTek Computer                       | 3         | 0.03%   |
| Spreadtrum Communications              | 2         | 0.02%   |
| Motorola PCS                           | 2         | 0.02%   |
| Google                                 | 2         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 3810      | 38.45%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 1577      | 15.91%  |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 258       | 2.6%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 229       | 2.31%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 188       | 1.9%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 155       | 1.56%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 138       | 1.39%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 129       | 1.3%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 128       | 1.29%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 124       | 1.25%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 116       | 1.17%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 113       | 1.14%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 106       | 1.07%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 105       | 1.06%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 101       | 1.02%   |
| Intel WiMAX Connection 2400m                                                   | 93        | 0.94%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 92        | 0.93%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 80        | 0.81%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 77        | 0.78%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 76        | 0.77%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 74        | 0.75%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 66        | 0.67%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 59        | 0.6%    |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 57        | 0.58%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 53        | 0.53%   |
| Intel Ethernet Connection (6) I219-V                                           | 52        | 0.52%   |
| Intel 82577LM Gigabit Network Connection                                       | 49        | 0.49%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 48        | 0.48%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 46        | 0.46%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 45        | 0.45%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 44        | 0.44%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 43        | 0.43%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 42        | 0.42%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 40        | 0.4%    |
| Intel Ethernet Connection (4) I219-V                                           | 38        | 0.38%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 35        | 0.35%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 35        | 0.35%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 34        | 0.34%   |
| Intel Ethernet Connection (13) I219-V                                          | 33        | 0.33%   |
| Intel Ethernet Connection (10) I219-V                                          | 32        | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 10659     | 52.27%  |
| Ethernet | 9465      | 46.42%  |
| Modem    | 257       | 1.26%   |
| Unknown  | 10        | 0.05%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 8734      | 77.73%  |
| Ethernet | 2499      | 22.24%  |
| Modem    | 4         | 0.04%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 9073      | 83.31%  |
| 1     | 1587      | 14.57%  |
| 0     | 214       | 1.97%   |
| 3     | 16        | 0.15%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 10727     | 98.3%   |
| Yes  | 185       | 1.7%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1986      | 25.73%  |
| Qualcomm Atheros Communications | 1133      | 14.68%  |
| Realtek Semiconductor           | 991       | 12.84%  |
| IMC Networks                    | 623       | 8.07%   |
| Broadcom                        | 590       | 7.64%   |
| Lite-On Technology              | 569       | 7.37%   |
| Foxconn / Hon Hai               | 480       | 6.22%   |
| Ralink                          | 181       | 2.34%   |
| ASUSTek Computer                | 174       | 2.25%   |
| Foxconn International           | 143       | 1.85%   |
| Toshiba                         | 140       | 1.81%   |
| Realtek                         | 115       | 1.49%   |
| Cambridge Silicon Radio         | 114       | 1.48%   |
| Hewlett-Packard                 | 113       | 1.46%   |
| Dell                            | 107       | 1.39%   |
| Apple                           | 79        | 1.02%   |
| Alps Electric                   | 61        | 0.79%   |
| Ralink Technology               | 37        | 0.48%   |
| Chicony Electronics             | 23        | 0.3%    |
| MediaTek                        | 19        | 0.25%   |
| Micro Star International        | 10        | 0.13%   |
| Askey Computer                  | 7         | 0.09%   |
| USI                             | 5         | 0.06%   |
| Opticis                         | 5         | 0.06%   |
| Taiyo Yuden                     | 4         | 0.05%   |
| Integrated System Solution      | 3         | 0.04%   |
| Samsung Electronics             | 2         | 0.03%   |
| Qcom                            | 2         | 0.03%   |
| TP-Link                         | 1         | 0.01%   |
| Syntek                          | 1         | 0.01%   |
| Fujitsu                         | 1         | 0.01%   |
| Unknown                         | 1         | 0.01%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 684       | 8.85%   |
| Realtek Bluetooth Radio                                                             | 539       | 6.98%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 396       | 5.13%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 344       | 4.45%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 333       | 4.31%   |
| Intel AX201 Bluetooth                                                               | 296       | 3.83%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 258       | 3.34%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 239       | 3.09%   |
| IMC Networks Bluetooth Radio                                                        | 183       | 2.37%   |
| Ralink RT3290 Bluetooth                                                             | 181       | 2.34%   |
| Intel AX200 Bluetooth                                                               | 169       | 2.19%   |
| IMC Networks Bluetooth Device                                                       | 156       | 2.02%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 155       | 2.01%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 148       | 1.92%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 146       | 1.89%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 145       | 1.88%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 142       | 1.84%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 141       | 1.83%   |
| Lite-On Bluetooth Device                                                            | 135       | 1.75%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 126       | 1.63%   |
| Realtek Bluetooth Radio                                                             | 115       | 1.49%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 114       | 1.48%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 104       | 1.35%   |
| Realtek RTL8723B Bluetooth                                                          | 100       | 1.29%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 100       | 1.29%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 95        | 1.23%   |
| Broadcom BCM2045 Bluetooth                                                          | 77        | 1%      |
| Qualcomm Atheros Bluetooth                                                          | 71        | 0.92%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 65        | 0.84%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 60        | 0.78%   |
| Broadcom HP Portable Valentine                                                      | 60        | 0.78%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                                               | 57        | 0.74%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 54        | 0.7%    |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 53        | 0.69%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 52        | 0.67%   |
| ASUS BT-253 Bluetooth Adapter                                                       | 52        | 0.67%   |
| Toshiba Integrated Bluetooth HCI                                                    | 51        | 0.66%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 51        | 0.66%   |
| ASUS BT-270 Bluetooth Adapter                                                       | 50        | 0.65%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 47        | 0.61%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 8162      | 66.24%  |
| AMD                                          | 2791      | 22.65%  |
| Nvidia                                       | 1010      | 8.2%    |
| Silicon Integrated Systems [SiS]             | 74        | 0.6%    |
| C-Media Electronics                          | 54        | 0.44%   |
| Logitech                                     | 20        | 0.16%   |
| Creative Technology                          | 19        | 0.15%   |
| Realtek Semiconductor                        | 15        | 0.12%   |
| JMTek                                        | 13        | 0.11%   |
| VIA Technologies                             | 12        | 0.1%    |
| Texas Instruments                            | 10        | 0.08%   |
| Plantronics                                  | 10        | 0.08%   |
| Lenovo                                       | 8         | 0.06%   |
| Generalplus Technology                       | 8         | 0.06%   |
| Samson Technologies                          | 6         | 0.05%   |
| SteelSeries ApS                              | 5         | 0.04%   |
| GN Netcom                                    | 5         | 0.04%   |
| A4Tech                                       | 5         | 0.04%   |
| Yamaha                                       | 4         | 0.03%   |
| Thesycon Systemsoftware & Consulting         | 4         | 0.03%   |
| Focusrite-Novation                           | 4         | 0.03%   |
| ASUSTek Computer                             | 4         | 0.03%   |
| Razer USA                                    | 3         | 0.02%   |
| GYROCOM C&C                                  | 3         | 0.02%   |
| DSEA A/S                                     | 3         | 0.02%   |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 0.02%   |
| Zhaoxin                                      | 2         | 0.02%   |
| XMOS                                         | 2         | 0.02%   |
| SAVITECH                                     | 2         | 0.02%   |
| Samsung Electronics                          | 2         | 0.02%   |
| Roland                                       | 2         | 0.02%   |
| Promethean Limited                           | 2         | 0.02%   |
| Microsoft                                    | 2         | 0.02%   |
| Kingston Technology                          | 2         | 0.02%   |
| Hewlett-Packard                              | 2         | 0.02%   |
| Harman                                       | 2         | 0.02%   |
| ESI Audiotechnik                             | 2         | 0.02%   |
| Elite Silicon                                | 2         | 0.02%   |
| DigiTech                                     | 2         | 0.02%   |
| Conexant Systems                             | 2         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1407      | 9.32%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 954       | 6.32%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 761       | 5.04%   |
| AMD FCH Azalia Controller                                                                         | 716       | 4.74%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 708       | 4.69%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 694       | 4.6%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 627       | 4.15%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 569       | 3.77%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 561       | 3.72%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 407       | 2.7%    |
| AMD Kabini HDMI/DP Audio                                                                          | 341       | 2.26%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 337       | 2.23%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 327       | 2.17%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 314       | 2.08%   |
| Intel 8 Series HD Audio Controller                                                                | 314       | 2.08%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 263       | 1.74%   |
| Intel Cannon Lake PCH cAVS                                                                        | 260       | 1.72%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 258       | 1.71%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 242       | 1.6%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 241       | 1.6%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 233       | 1.54%   |
| AMD Wrestler HDMI Audio                                                                           | 213       | 1.41%   |
| AMD High Definition Audio Controller                                                              | 212       | 1.4%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 208       | 1.38%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 204       | 1.35%   |
| AMD Trinity HDMI Audio Controller                                                                 | 200       | 1.32%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 193       | 1.28%   |
| Intel Broadwell-U Audio Controller                                                                | 182       | 1.21%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 179       | 1.19%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 179       | 1.19%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 161       | 1.07%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 156       | 1.03%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 140       | 0.93%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 131       | 0.87%   |
| Nvidia High Definition Audio Controller                                                           | 129       | 0.85%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 108       | 0.72%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 100       | 0.66%   |
| Intel CM238 HD Audio Controller                                                                   | 86        | 0.57%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 85        | 0.56%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 84        | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Samsung Electronics   | 2551      | 23.15%  |
| SK hynix              | 2134      | 19.37%  |
| Unknown               | 1421      | 12.9%   |
| Kingston              | 1243      | 11.28%  |
| Micron Technology     | 881       | 8%      |
| Elpida                | 440       | 3.99%   |
| Nanya Technology      | 366       | 3.32%   |
| Ramaxel Technology    | 333       | 3.02%   |
| A-DATA Technology     | 297       | 2.7%    |
| Crucial               | 293       | 2.66%   |
| AMD                   | 124       | 1.13%   |
| ASint Technology      | 119       | 1.08%   |
| Corsair               | 88        | 0.8%    |
| Patriot               | 83        | 0.75%   |
| 48spaces              | 74        | 0.67%   |
| Goldkey               | 73        | 0.66%   |
| Unknown (ABCD)        | 69        | 0.63%   |
| SHARETRONIC           | 51        | 0.46%   |
| Foxline               | 36        | 0.33%   |
| Transcend             | 35        | 0.32%   |
| GOODRAM               | 29        | 0.26%   |
| Qimonda               | 28        | 0.25%   |
| Apacer                | 24        | 0.22%   |
| Unifosa               | 23        | 0.21%   |
| Kllisre               | 22        | 0.2%    |
| Unknown               | 19        | 0.17%   |
| Qumo                  | 17        | 0.15%   |
| Toshiba               | 15        | 0.14%   |
| Silicon Power         | 12        | 0.11%   |
| ACPI Digital          | 9         | 0.08%   |
| Kingmax Semiconductor | 7         | 0.06%   |
| Kingmax               | 7         | 0.06%   |
| ChangXin Memory       | 7         | 0.06%   |
| Unknown (08AE)        | 3         | 0.03%   |
| SGS/Thomson           | 3         | 0.03%   |
| MLLSE                 | 3         | 0.03%   |
| Infineon              | 3         | 0.03%   |
| Hexon                 | 3         | 0.03%   |
| Atermiter             | 3         | 0.03%   |
| ZIFEI                 | 2         | 0.02%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s                  | 214       | 1.79%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 145       | 1.21%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s                     | 140       | 1.17%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s                     | 131       | 1.1%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 128       | 1.07%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s                     | 127       | 1.06%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                             | 120       | 1%      |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s                     | 119       | 1%      |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 119       | 1%      |
| Unknown RAM Module 2048MB SODIMM DDR2                                     | 109       | 0.91%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 102       | 0.85%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 100       | 0.84%   |
| Unknown RAM Module 1024MB SODIMM DDR2                                     | 94        | 0.79%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 92        | 0.77%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                             | 87        | 0.73%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s                     | 86        | 0.72%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s                    | 85        | 0.71%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s                     | 85        | 0.71%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 84        | 0.7%    |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s                     | 77        | 0.64%   |
| A-DATA RAM AD73I1C1674EV 4GB SODIMM DDR3 1334MT/s                         | 76        | 0.64%   |
| 48spaces RAM 012345678901234567890123456789012345 2GB SODIMM DDR2 667MT/s | 73        | 0.61%   |
| Unknown RAM Module 4096MB SODIMM DDR3                                     | 71        | 0.59%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s                    | 66        | 0.55%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 62        | 0.52%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s                      | 62        | 0.52%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s          | 61        | 0.51%   |
| Samsung RAM M471B5773DH0-CK0 2048MB SODIMM DDR3 1600MT/s                  | 61        | 0.51%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s                             | 58        | 0.49%   |
| SK hynix RAM HMA851S6AFR6N-UH 2GB SODIMM LPDDR4 2667MT/s                  | 57        | 0.48%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s                     | 55        | 0.46%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s                    | 54        | 0.45%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                                    | 53        | 0.44%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s                    | 52        | 0.44%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s                     | 52        | 0.44%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s                     | 51        | 0.43%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s                     | 50        | 0.42%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s                    | 49        | 0.41%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s                    | 49        | 0.41%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s                     | 48        | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 4945      | 53.56%  |
| DDR4    | 2120      | 22.96%  |
| DDR2    | 1052      | 11.39%  |
| SDRAM   | 494       | 5.35%   |
| LPDDR4  | 193       | 2.09%   |
| Unknown | 127       | 1.38%   |
| DDR     | 123       | 1.33%   |
| DRAM    | 96        | 1.04%   |
| LPDDR3  | 75        | 0.81%   |
| LPDDR5  | 5         | 0.05%   |
| DDR5    | 2         | 0.02%   |
| SRAM    | 1         | 0.01%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 8611      | 95.37%  |
| Row Of Chips | 306       | 3.39%   |
| DIMM         | 83        | 0.92%   |
| Chip         | 21        | 0.23%   |
| Unknown      | 8         | 0.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Notebooks | Percent |
|---------|-----------|---------|
| 4096    | 4158      | 39.28%  |
| 2048    | 3002      | 28.36%  |
| 8192    | 1942      | 18.35%  |
| 1024    | 977       | 9.23%   |
| 16384   | 326       | 3.08%   |
| 512     | 130       | 1.23%   |
| 32768   | 29        | 0.27%   |
| 256     | 14        | 0.13%   |
| Unknown | 5         | 0.05%   |
| 1536    | 2         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 2948      | 28.63%  |
| 1334    | 1273      | 12.36%  |
| 2667    | 1104      | 10.72%  |
| 1333    | 811       | 7.88%   |
| 3200    | 651       | 6.32%   |
| 667     | 642       | 6.24%   |
| Unknown | 613       | 5.95%   |
| 2400    | 480       | 4.66%   |
| 4199    | 274       | 2.66%   |
| 800     | 245       | 2.38%   |
| 1067    | 237       | 2.3%    |
| 2133    | 224       | 2.18%   |
| 533     | 145       | 1.41%   |
| 3266    | 127       | 1.23%   |
| 2048    | 99        | 0.96%   |
| 1066    | 98        | 0.95%   |
| 975     | 61        | 0.59%   |
| 1867    | 53        | 0.51%   |
| 333     | 42        | 0.41%   |
| 400     | 26        | 0.25%   |
| 4267    | 22        | 0.21%   |
| 1639    | 20        | 0.19%   |
| 1866    | 18        | 0.17%   |
| 8400    | 15        | 0.15%   |
| 4266    | 12        | 0.12%   |
| 3733    | 12        | 0.12%   |
| 2933    | 8         | 0.08%   |
| 6400    | 5         | 0.05%   |
| 4800    | 5         | 0.05%   |
| 65535   | 3         | 0.03%   |
| 2666    | 3         | 0.03%   |
| 1776    | 3         | 0.03%   |
| 266     | 3         | 0.03%   |
| 200     | 3         | 0.03%   |
| 1       | 3         | 0.03%   |
| 2800    | 2         | 0.02%   |
| 2267    | 2         | 0.02%   |
| 100     | 2         | 0.02%   |
| 888     | 1         | 0.01%   |
| 166     | 1         | 0.01%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 55        | 27.36%  |
| Canon                  | 38        | 18.91%  |
| Samsung Electronics    | 34        | 16.92%  |
| Seiko Epson            | 20        | 9.95%   |
| Brother Industries     | 16        | 7.96%   |
| Panasonic (Matsushita) | 12        | 5.97%   |
| Xerox                  | 9         | 4.48%   |
| Ricoh                  | 6         | 2.99%   |
| Pantum                 | 5         | 2.49%   |
| Kyocera                | 2         | 1%      |
| Xiaomi                 | 1         | 0.5%    |
| Prolific Technology    | 1         | 0.5%    |
| NXP Semiconductors     | 1         | 0.5%    |
| Lexmark International  | 1         | 0.5%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| HP LaserJet 1020                                             | 9         | 4.46%   |
| Samsung SCX-4200 series                                      | 6         | 2.97%   |
| Panasonic (Matsushita) KX-MB1500RU                           | 6         | 2.97%   |
| Samsung SCX-3200 Series                                      | 5         | 2.48%   |
| Panasonic (Matsushita) KX-MB2030 Multifunction Laser Printer | 5         | 2.48%   |
| Xerox B205                                                   | 4         | 1.98%   |
| Samsung SCX-3400 Series                                      | 4         | 1.98%   |
| Samsung ML-1210 Printer                                      | 4         | 1.98%   |
| Samsung M2020 Series                                         | 4         | 1.98%   |
| HP LaserJet P1102                                            | 4         | 1.98%   |
| HP LaserJet 1200                                             | 4         | 1.98%   |
| Canon PIXMA MG2500 Series                                    | 4         | 1.98%   |
| Brother HL-1110 series                                       | 4         | 1.98%   |
| Seiko Epson L210 Series                                      | 3         | 1.49%   |
| Seiko Epson L200 Series                                      | 3         | 1.49%   |
| HP LaserJet 1018                                             | 3         | 1.49%   |
| Canon MF4010 series                                          | 3         | 1.49%   |
| Canon LBP7010C/7018C                                         | 3         | 1.49%   |
| Canon LBP3010/LBP3018/LBP3050                                | 3         | 1.49%   |
| Canon LaserShot LBP-1120 Printer                             | 3         | 1.49%   |
| Canon G1000 series                                           | 3         | 1.49%   |
| Xerox Phaser 3020                                            | 2         | 0.99%   |
| Seiko Epson USB2.0 Printer (Hi-speed)                        | 2         | 0.99%   |
| Seiko Epson Printer                                          | 2         | 0.99%   |
| Seiko Epson L120 Series                                      | 2         | 0.99%   |
| Samsung ML-1865                                              | 2         | 0.99%   |
| Samsung ML-1640 Series Laser Printer                         | 2         | 0.99%   |
| Samsung M2070 Series                                         | 2         | 0.99%   |
| Ricoh SP 150SUw                                              | 2         | 0.99%   |
| Pantum M6500 series                                          | 2         | 0.99%   |
| HP LaserJet Professional P1102w                              | 2         | 0.99%   |
| HP LaserJet 1320                                             | 2         | 0.99%   |
| HP DeskJet 5440                                              | 2         | 0.99%   |
| HP DeskJet 4530 series                                       | 2         | 0.99%   |
| HP DeskJet 2300 series                                       | 2         | 0.99%   |
| HP DeskJet 2130 series                                       | 2         | 0.99%   |
| Canon LBP6020                                                | 2         | 0.99%   |
| Canon LBP6000                                                | 2         | 0.99%   |
| Canon iP2700 series                                          | 2         | 0.99%   |
| Canon iP1900 series                                          | 2         | 0.99%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Seiko Epson                 | 14        | 35%     |
| Canon                       | 10        | 25%     |
| Hewlett-Packard             | 6         | 15%     |
| Mustek Systems              | 4         | 10%     |
| Ultima Electronics          | 2         | 5%      |
| KYE Systems (Mouse Systems) | 2         | 5%      |
| Acer Peripherals (now BenQ) | 2         | 5%      |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 5         | 12.5%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 2         | 5%      |
| Seiko Epson GT-F670 [Perfection V200 Photo]                                           | 2         | 5%      |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 2         | 5%      |
| Mustek Systems BearPaw 1200 TA/CS                                                     | 2         | 5%      |
| HP ScanJet 3770                                                                       | 2         | 5%      |
| HP Scanjet 200                                                                        | 2         | 5%      |
| Canon CanoScan LIDE 25                                                                | 2         | 5%      |
| Canon CanoScan LiDE 120                                                               | 2         | 5%      |
| Canon CanoScan LiDE 110                                                               | 2         | 5%      |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]                                           | 1         | 2.5%    |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 1         | 2.5%    |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 1         | 2.5%    |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                   | 1         | 2.5%    |
| Seiko Epson GT-7400U [Perfection 1270]                                                | 1         | 2.5%    |
| Mustek Systems BearPaw 2448 CU Pro                                                    | 1         | 2.5%    |
| Mustek Systems BearPaw 2400 TA Plus                                                   | 1         | 2.5%    |
| KYE Systems (Mouse Systems) ColorPage-Vivid4                                          | 1         | 2.5%    |
| KYE Systems (Mouse Systems) ColorPage-Vivid 1200 XE                                   | 1         | 2.5%    |
| HP ScanJet G4010                                                                      | 1         | 2.5%    |
| HP ScanJet 2400c                                                                      | 1         | 2.5%    |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 1         | 2.5%    |
| Canon CanoScan LiDE 70                                                                | 1         | 2.5%    |
| Canon CanoScan LiDE 220                                                               | 1         | 2.5%    |
| Canon CanoScan 4400F                                                                  | 1         | 2.5%    |
| Acer Peripherals (now BenQ) Benq 5150/5250                                            | 1         | 2.5%    |
| Acer Peripherals (now BenQ) Benq 5000                                                 | 1         | 2.5%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 2468      | 25.85%  |
| IMC Networks                           | 1158      | 12.13%  |
| Acer                                   | 895       | 9.37%   |
| Realtek Semiconductor                  | 671       | 7.03%   |
| Suyin                                  | 608       | 6.37%   |
| Microdia                               | 492       | 5.15%   |
| Sunplus Innovation Technology          | 434       | 4.54%   |
| Silicon Motion                         | 389       | 4.07%   |
| Quanta                                 | 363       | 3.8%    |
| Cheng Uei Precision Industry (Foxlink) | 353       | 3.7%    |
| Syntek                                 | 301       | 3.15%   |
| Alcor Micro                            | 275       | 2.88%   |
| Z-Star Microelectronics                | 154       | 1.61%   |
| Ricoh                                  | 113       | 1.18%   |
| Lite-On Technology                     | 113       | 1.18%   |
| ALi                                    | 100       | 1.05%   |
| Apple                                  | 96        | 1.01%   |
| DigiTech                               | 81        | 0.85%   |
| Luxvisions Innotech Limited            | 76        | 0.8%    |
| Logitech                               | 58        | 0.61%   |
| Lenovo                                 | 38        | 0.4%    |
| Samsung Electronics                    | 33        | 0.35%   |
| Primax Electronics                     | 31        | 0.32%   |
| Sonix Technology                       | 22        | 0.23%   |
| Importek                               | 21        | 0.22%   |
| Sunplus Technology                     | 17        | 0.18%   |
| Unknown                                | 15        | 0.16%   |
| Y Media                                | 14        | 0.15%   |
| USB Camera                             | 14        | 0.15%   |
| OmniVision Technologies                | 14        | 0.15%   |
| GEMBIRD                                | 12        | 0.13%   |
| Image Processor                        | 9         | 0.09%   |
| Genesys Logic                          | 8         | 0.08%   |
| USB Camera CS                          | 7         | 0.07%   |
| SunplusIT                              | 7         | 0.07%   |
| Pixart Imaging                         | 7         | 0.07%   |
| Nebraska Furniture Mart                | 6         | 0.06%   |
| Microsoft                              | 5         | 0.05%   |
| KYE Systems (Mouse Systems)            | 5         | 0.05%   |
| DJJHFA1BIF5595                         | 5         | 0.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony HD WebCam                                | 272       | 2.84%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 232       | 2.43%   |
| Chicony Integrated Camera                        | 221       | 2.31%   |
| Chicony Lenovo EasyCamera                        | 212       | 2.22%   |
| Acer Lenovo Integrated Webcam                    | 191       | 2%      |
| IMC Networks USB2.0 HD UVC WebCam                | 160       | 1.67%   |
| Acer BisonCam, NB Pro                            | 144       | 1.51%   |
| Acer Lenovo EasyCamera                           | 143       | 1.5%    |
| Sunplus HD WebCam                                | 142       | 1.48%   |
| Microdia Integrated_Webcam_HD                    | 142       | 1.48%   |
| IMC Networks UVC VGA Webcam                      | 136       | 1.42%   |
| IMC Networks Integrated Camera                   | 131       | 1.37%   |
| Chicony USB2.0 HD UVC WebCam                     | 126       | 1.32%   |
| Chicony USB 2.0 Camera                           | 113       | 1.18%   |
| Realtek Integrated_Webcam_HD                     | 107       | 1.12%   |
| Acer Integrated Camera                           | 103       | 1.08%   |
| Chicony HP Webcam                                | 100       | 1.05%   |
| Realtek Lenovo EasyCamera                        | 94        | 0.98%   |
| Realtek USB Camera                               | 92        | 0.96%   |
| Chicony VGA Webcam                               | 92        | 0.96%   |
| Quanta VGA WebCam                                | 88        | 0.92%   |
| Alcor Micro Asus Integrated Webcam               | 86        | 0.9%    |
| Chicony USB2.0 VGA UVC WebCam                    | 84        | 0.88%   |
| Silicon Motion WebCam SC-0311139N                | 81        | 0.85%   |
| Syntek Lenovo EasyCamera                         | 78        | 0.82%   |
| Syntek Integrated Camera                         | 78        | 0.82%   |
| IMC Networks Integrated Webcam                   | 76        | 0.79%   |
| Suyin Acer/HP Integrated Webcam [CN0314]         | 74        | 0.77%   |
| DigiTech USB 2.0 PC Camera                       | 73        | 0.76%   |
| Chicony 2.0M UVC Webcam / CNF7129                | 73        | 0.76%   |
| Chicony HP Truevision HD                         | 70        | 0.73%   |
| ALi Gateway Webcam                               | 68        | 0.71%   |
| Alcor Micro USB 2.0 Camera                       | 64        | 0.67%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 63        | 0.66%   |
| IMC Networks HD Camera                           | 62        | 0.65%   |
| Sunplus Integrated_Webcam_HD                     | 61        | 0.64%   |
| Chicony EasyCamera                               | 61        | 0.64%   |
| Silicon Motion WebCam SCB-1100N                  | 60        | 0.63%   |
| Acer EasyCamera                                  | 59        | 0.62%   |
| Realtek Acer 640 x 480 laptop camera             | 57        | 0.6%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 413       | 34.02%  |
| Shenzhen Goodix Technology | 201       | 16.56%  |
| Synaptics                  | 163       | 13.43%  |
| AuthenTec                  | 127       | 10.46%  |
| Upek                       | 107       | 8.81%   |
| LighTuning Technology      | 86        | 7.08%   |
| Elan Microelectronics      | 77        | 6.34%   |
| STMicroelectronics         | 32        | 2.64%   |
| Focal-systems.Corp         | 7         | 0.58%   |
| Samsung Electronics        | 1         | 0.08%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 158       | 13.01%  |
| Validity Sensors Fingerprint scanner                                       | 95        | 7.83%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 89        | 7.33%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 86        | 7.08%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 72        | 5.93%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 53        | 4.37%   |
| Elan ELAN:Fingerprint                                                      | 52        | 4.28%   |
| LighTuning Fingerprint Reader                                              | 40        | 3.29%   |
| AuthenTec AES1600                                                          | 39        | 3.21%   |
| Shenzhen Goodix Fingerprint Reader                                         | 37        | 3.05%   |
| STMicroelectronics Fingerprint Reader                                      | 32        | 2.64%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 31        | 2.55%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 29        | 2.39%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 29        | 2.39%   |
| AuthenTec AES2810                                                          | 27        | 2.22%   |
| Validity Sensors VFS491                                                    | 25        | 2.06%   |
| Unknown                                                                    | 25        | 2.06%   |
| Elan ELAN:ARM-M4                                                           | 23        | 1.89%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 21        | 1.73%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 21        | 1.73%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 20        | 1.65%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 19        | 1.57%   |
| Upek TCS5B Fingerprint sensor                                              | 18        | 1.48%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 18        | 1.48%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 17        | 1.4%    |
| AuthenTec AES1660 Fingerprint Sensor                                       | 17        | 1.4%    |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 14        | 1.15%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 14        | 1.15%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 12        | 0.99%   |
| Validity Sensors Synaptics WBDI                                            | 12        | 0.99%   |
| Synaptics  WBDI                                                            | 10        | 0.82%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 8         | 0.66%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 8         | 0.66%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 8         | 0.66%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 7         | 0.58%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 7         | 0.58%   |
| Shenzhen Goodix FingerPrint                                                | 6         | 0.49%   |
| AuthenTec Fingerprint Sensor                                               | 5         | 0.41%   |
| Validity Sensors VFS Fingerprint sensor                                    | 4         | 0.33%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 3         | 0.25%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 90        | 37.04%  |
| Broadcom                  | 78        | 32.1%   |
| Upek                      | 23        | 9.47%   |
| O2 Micro                  | 21        | 8.64%   |
| Lenovo                    | 16        | 6.58%   |
| Gemalto (was Gemplus)     | 4         | 1.65%   |
| Yubico.com                | 3         | 1.23%   |
| Aladdin Knowledge Systems | 3         | 1.23%   |
| Aktiv                     | 3         | 1.23%   |
| Microchip Technology      | 1         | 0.41%   |
| Aladdin R.D.              | 1         | 0.41%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 88        | 36.21%  |
| Broadcom BCM5880 Secure Applications Processor                               | 33        | 13.58%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 23        | 9.47%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 18        | 7.41%   |
| Broadcom 5880                                                                | 17        | 7%      |
| Lenovo Integrated Smart Card Reader                                          | 16        | 6.58%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 14        | 5.76%   |
| Broadcom 58200                                                               | 14        | 5.76%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 3         | 1.23%   |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 1.23%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 1.23%   |
| Aladdin Knowledge Systems Token JC                                           | 3         | 1.23%   |
| Aktiv Rutoken lite                                                           | 3         | 1.23%   |
| Microchip Technology SMSC USX101x Reader                                     | 1         | 0.41%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.41%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.41%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.41%   |
| Aladdin R.D. JaCarta                                                         | 1         | 0.41%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 7659      | 67.72%  |
| 1     | 2890      | 25.55%  |
| 2     | 640       | 5.66%   |
| 3     | 100       | 0.88%   |
| 4     | 15        | 0.13%   |
| 5     | 4         | 0.04%   |
| 6     | 2         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 1525      | 36.43%  |
| Fingerprint reader       | 1209      | 28.88%  |
| Net/wireless             | 397       | 9.48%   |
| Bluetooth                | 243       | 5.81%   |
| Chipcard                 | 218       | 5.21%   |
| Multimedia controller    | 206       | 4.92%   |
| Camera                   | 103       | 2.46%   |
| Communication controller | 77        | 1.84%   |
| Flash memory             | 59        | 1.41%   |
| Storage                  | 58        | 1.39%   |
| Card reader              | 27        | 0.65%   |
| Sound                    | 18        | 0.43%   |
| Net/ethernet             | 16        | 0.38%   |
| Modem                    | 13        | 0.31%   |
| Dvb card                 | 5         | 0.12%   |
| Network                  | 4         | 0.1%    |
| Storage/ide              | 3         | 0.07%   |
| Firewire controller      | 2         | 0.05%   |
| Wireless                 | 1         | 0.02%   |
| Unclassified device      | 1         | 0.02%   |
| Storage/raid             | 1         | 0.02%   |

