Fedora 37 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Fedora 37.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Fedora_37/Desktop/README.md) and [notebooks](/Dist/Fedora_37/Notebook/README.md).

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

Total: 2751

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASRock        | FM2A88X Extreme6+           | Desktop     | [be8b69e1b4](https://linux-hardware.org/?probe=be8b69e1b4) | May 01, 2023 |
| Intel         | CHERRYVIEW D1 PLATFORM      | Notebook    | [6c58138c35](https://linux-hardware.org/?probe=6c58138c35) | May 01, 2023 |
| ASUSTek       | X555QG                      | Notebook    | [5263b174b2](https://linux-hardware.org/?probe=5263b174b2) | Apr 30, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [c33288abe2](https://linux-hardware.org/?probe=c33288abe2) | Apr 30, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [c262e81ab9](https://linux-hardware.org/?probe=c262e81ab9) | Apr 30, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [c6591b0852](https://linux-hardware.org/?probe=c6591b0852) | Apr 29, 2023 |
| Intel         | CHERRYVIEW D1 PLATFORM      | Notebook    | [edf1d60e46](https://linux-hardware.org/?probe=edf1d60e46) | Apr 29, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [80ea529a18](https://linux-hardware.org/?probe=80ea529a18) | Apr 29, 2023 |
| MSI           | Modern 14 B11MOU            | Notebook    | [6b3fcf3fcc](https://linux-hardware.org/?probe=6b3fcf3fcc) | Apr 29, 2023 |
| ASUSTek       | X555QG                      | Notebook    | [b33f41d3c3](https://linux-hardware.org/?probe=b33f41d3c3) | Apr 28, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [e0ef7894af](https://linux-hardware.org/?probe=e0ef7894af) | Apr 28, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [8a3c1cbc1c](https://linux-hardware.org/?probe=8a3c1cbc1c) | Apr 28, 2023 |
| Lenovo        | ThinkPad L13 Yoga 20R6S1... | Convertible | [c01483e50f](https://linux-hardware.org/?probe=c01483e50f) | Apr 28, 2023 |
| Lenovo        | ThinkPad X230 2325O32       | Notebook    | [b38ef1a717](https://linux-hardware.org/?probe=b38ef1a717) | Apr 27, 2023 |
| Lenovo        | ThinkPad T420 4177QKU       | Notebook    | [cbabefb1fa](https://linux-hardware.org/?probe=cbabefb1fa) | Apr 27, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [853016bfe3](https://linux-hardware.org/?probe=853016bfe3) | Apr 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | Notebook    | [3a6e27c6ce](https://linux-hardware.org/?probe=3a6e27c6ce) | Apr 26, 2023 |
| Gigabyte      | EX58-EXTREME                | Desktop     | [3b263c29fc](https://linux-hardware.org/?probe=3b263c29fc) | Apr 26, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [909ad37ab0](https://linux-hardware.org/?probe=909ad37ab0) | Apr 26, 2023 |
| MSI           | Creator 15 A10SGS           | Notebook    | [1b364e385a](https://linux-hardware.org/?probe=1b364e385a) | Apr 26, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [cc994920bf](https://linux-hardware.org/?probe=cc994920bf) | Apr 25, 2023 |
| HP            | 0AECh D                     | Desktop     | [c9e99b3f8c](https://linux-hardware.org/?probe=c9e99b3f8c) | Apr 25, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [c0d8e6e6b5](https://linux-hardware.org/?probe=c0d8e6e6b5) | Apr 25, 2023 |
| Lenovo        | 1037 SDK0Q40104 WIN 3305... | Server      | [1d6082efe8](https://linux-hardware.org/?probe=1d6082efe8) | Apr 25, 2023 |
| Lenovo        | 1037 SDK0Q40104 WIN 3305... | Server      | [d86639089a](https://linux-hardware.org/?probe=d86639089a) | Apr 25, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [373372bf75](https://linux-hardware.org/?probe=373372bf75) | Apr 25, 2023 |
| Lenovo        | V130-15IKB 81HN             | Notebook    | [1b26b3f89b](https://linux-hardware.org/?probe=1b26b3f89b) | Apr 24, 2023 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [2f3390afca](https://linux-hardware.org/?probe=2f3390afca) | Apr 24, 2023 |
| Gigabyte      | X570S I AORUS PRO AX        | Desktop     | [9c37fa5192](https://linux-hardware.org/?probe=9c37fa5192) | Apr 24, 2023 |
| Gigabyte      | F2A88X-UP4                  | Desktop     | [06859fe586](https://linux-hardware.org/?probe=06859fe586) | Apr 23, 2023 |
| Notebook      | NLxxPUx                     | Notebook    | [3648be5b0f](https://linux-hardware.org/?probe=3648be5b0f) | Apr 23, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | Notebook    | [a8644a5b03](https://linux-hardware.org/?probe=a8644a5b03) | Apr 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [0e798db6a8](https://linux-hardware.org/?probe=0e798db6a8) | Apr 23, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [f51db9e4de](https://linux-hardware.org/?probe=f51db9e4de) | Apr 23, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [3c0a66f0fc](https://linux-hardware.org/?probe=3c0a66f0fc) | Apr 22, 2023 |
| MSI           | Z370M MORTAR                | Desktop     | [9ed0395d2c](https://linux-hardware.org/?probe=9ed0395d2c) | Apr 22, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [80312ab34c](https://linux-hardware.org/?probe=80312ab34c) | Apr 22, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [b7f138b04c](https://linux-hardware.org/?probe=b7f138b04c) | Apr 20, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [81334f294e](https://linux-hardware.org/?probe=81334f294e) | Apr 20, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [cebfbef6d8](https://linux-hardware.org/?probe=cebfbef6d8) | Apr 20, 2023 |
| Dell          | G15 5510                    | Notebook    | [724945ee92](https://linux-hardware.org/?probe=724945ee92) | Apr 20, 2023 |
| Gigabyte      | Z270XP-SLI-CF               | Desktop     | [1383ab9981](https://linux-hardware.org/?probe=1383ab9981) | Apr 20, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHS... | Notebook    | [59d7ef5ddd](https://linux-hardware.org/?probe=59d7ef5ddd) | Apr 20, 2023 |
| Toshiba       | Satellite L515              | Notebook    | [5262a186b5](https://linux-hardware.org/?probe=5262a186b5) | Apr 20, 2023 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [990cf467d8](https://linux-hardware.org/?probe=990cf467d8) | Apr 19, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [4fbb42afa0](https://linux-hardware.org/?probe=4fbb42afa0) | Apr 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [85700f4804](https://linux-hardware.org/?probe=85700f4804) | Apr 19, 2023 |
| Dell          | Precision 5540              | Notebook    | [66b58fad6c](https://linux-hardware.org/?probe=66b58fad6c) | Apr 19, 2023 |
| Dell          | Precision 5540              | Notebook    | [e114fb911c](https://linux-hardware.org/?probe=e114fb911c) | Apr 19, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [2a80be40e3](https://linux-hardware.org/?probe=2a80be40e3) | Apr 19, 2023 |
| HP            | Pavilion 17                 | Notebook    | [66df49c906](https://linux-hardware.org/?probe=66df49c906) | Apr 19, 2023 |
| Intel         | X79M-S                      | Desktop     | [0c51f5a0e0](https://linux-hardware.org/?probe=0c51f5a0e0) | Apr 19, 2023 |
| Alienware     | 0K9TKY A00                  | Desktop     | [22582f8d3e](https://linux-hardware.org/?probe=22582f8d3e) | Apr 19, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [1a5add814c](https://linux-hardware.org/?probe=1a5add814c) | Apr 18, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [67a6474ece](https://linux-hardware.org/?probe=67a6474ece) | Apr 18, 2023 |
| Fujitsu       | LIFEBOOK U7510              | Notebook    | [21605e555f](https://linux-hardware.org/?probe=21605e555f) | Apr 18, 2023 |
| MSI           | Z170A GAMING PRO CARBON     | Desktop     | [cf13c3781c](https://linux-hardware.org/?probe=cf13c3781c) | Apr 18, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [7fcc7d1b34](https://linux-hardware.org/?probe=7fcc7d1b34) | Apr 18, 2023 |
| ASRock        | Z170 Gaming K4              | Desktop     | [cbd09f0f67](https://linux-hardware.org/?probe=cbd09f0f67) | Apr 18, 2023 |
| Lenovo        | ThinkPad Edge 031946U       | Notebook    | [f9d813509a](https://linux-hardware.org/?probe=f9d813509a) | Apr 18, 2023 |
| Dell          | 0XHYJF A00                  | All in one  | [9348834e54](https://linux-hardware.org/?probe=9348834e54) | Apr 18, 2023 |
| Dell          | 0XHYJF A00                  | All in one  | [c8804b1836](https://linux-hardware.org/?probe=c8804b1836) | Apr 18, 2023 |
| Lenovo        | ThinkPad P52 20MAS11D00     | Notebook    | [c2227e5f29](https://linux-hardware.org/?probe=c2227e5f29) | Apr 18, 2023 |
| Lenovo        | Unknown                     | Notebook    | [99a0c76ea9](https://linux-hardware.org/?probe=99a0c76ea9) | Apr 18, 2023 |
| Lenovo        | ThinkPad P52 20MAS11D00     | Notebook    | [f56edbb1d1](https://linux-hardware.org/?probe=f56edbb1d1) | Apr 18, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [7b3a68ca48](https://linux-hardware.org/?probe=7b3a68ca48) | Apr 18, 2023 |
| Intel         | DZ68DB AAG27985-105         | Desktop     | [aa030a4054](https://linux-hardware.org/?probe=aa030a4054) | Apr 18, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [90c4ba9f6e](https://linux-hardware.org/?probe=90c4ba9f6e) | Apr 17, 2023 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [bbe3e437d6](https://linux-hardware.org/?probe=bbe3e437d6) | Apr 17, 2023 |
| Lenovo        | Unknown                     | Notebook    | [653cf225b8](https://linux-hardware.org/?probe=653cf225b8) | Apr 17, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [4b953003cc](https://linux-hardware.org/?probe=4b953003cc) | Apr 17, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [07a49303af](https://linux-hardware.org/?probe=07a49303af) | Apr 17, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [f8a45caf43](https://linux-hardware.org/?probe=f8a45caf43) | Apr 17, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [7ca92cfada](https://linux-hardware.org/?probe=7ca92cfada) | Apr 17, 2023 |
| HP            | Pavilion 17                 | Notebook    | [a09113d5ab](https://linux-hardware.org/?probe=a09113d5ab) | Apr 17, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [a6a81342e7](https://linux-hardware.org/?probe=a6a81342e7) | Apr 17, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [3d14cefd78](https://linux-hardware.org/?probe=3d14cefd78) | Apr 17, 2023 |
| MSI           | H310M PRO-VD PLUS           | Desktop     | [bff38bc725](https://linux-hardware.org/?probe=bff38bc725) | Apr 16, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [fd256ca124](https://linux-hardware.org/?probe=fd256ca124) | Apr 16, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [2092251807](https://linux-hardware.org/?probe=2092251807) | Apr 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [c8513ddcf3](https://linux-hardware.org/?probe=c8513ddcf3) | Apr 16, 2023 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [1fa07cd218](https://linux-hardware.org/?probe=1fa07cd218) | Apr 16, 2023 |
| HP            | 15-dc1018ur                 | Notebook    | [7df35a90ad](https://linux-hardware.org/?probe=7df35a90ad) | Apr 16, 2023 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [c228cbe8e1](https://linux-hardware.org/?probe=c228cbe8e1) | Apr 16, 2023 |
| Framework     | Laptop                      | Notebook    | [c03bcdf19a](https://linux-hardware.org/?probe=c03bcdf19a) | Apr 16, 2023 |
| Gigabyte      | B85-HD3                     | Desktop     | [25e7d545ae](https://linux-hardware.org/?probe=25e7d545ae) | Apr 16, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [afc478cf27](https://linux-hardware.org/?probe=afc478cf27) | Apr 16, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [19b858e5f8](https://linux-hardware.org/?probe=19b858e5f8) | Apr 16, 2023 |
| ASRock        | A520M-HVS                   | Desktop     | [a0d799e140](https://linux-hardware.org/?probe=a0d799e140) | Apr 16, 2023 |
| Sony          | VPCCA1S1E                   | Notebook    | [05ab5df066](https://linux-hardware.org/?probe=05ab5df066) | Apr 16, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [73c46e2901](https://linux-hardware.org/?probe=73c46e2901) | Apr 15, 2023 |
| Google        | Dragonair                   | Notebook    | [be10ee5035](https://linux-hardware.org/?probe=be10ee5035) | Apr 15, 2023 |
| Sony          | VPCCA1S1E                   | Notebook    | [30625007d9](https://linux-hardware.org/?probe=30625007d9) | Apr 15, 2023 |
| Google        | Dragonair                   | Notebook    | [cb2aa57d07](https://linux-hardware.org/?probe=cb2aa57d07) | Apr 15, 2023 |
| HP            | 212B                        | Desktop     | [c8f86eb8a4](https://linux-hardware.org/?probe=c8f86eb8a4) | Apr 15, 2023 |
| Acer          | Aspire A114-33              | Notebook    | [53c9fe0b8d](https://linux-hardware.org/?probe=53c9fe0b8d) | Apr 15, 2023 |
| Acer          | Aspire A114-33              | Notebook    | [99f95937d4](https://linux-hardware.org/?probe=99f95937d4) | Apr 15, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [c649f1b898](https://linux-hardware.org/?probe=c649f1b898) | Apr 15, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [37eee19e22](https://linux-hardware.org/?probe=37eee19e22) | Apr 15, 2023 |
| Lenovo        | ThinkCentre M58p 7220A72    | Desktop     | [2be395131f](https://linux-hardware.org/?probe=2be395131f) | Apr 15, 2023 |
| HONOR         | HYM-WXX                     | Notebook    | [109b28f217](https://linux-hardware.org/?probe=109b28f217) | Apr 15, 2023 |
| Lenovo        | ThinkCentre M58p 7220A72    | Desktop     | [0ca4b7045e](https://linux-hardware.org/?probe=0ca4b7045e) | Apr 15, 2023 |
| ASUSTek       | TUF Gaming X570-PRO WIFI... | Desktop     | [2e601ecae8](https://linux-hardware.org/?probe=2e601ecae8) | Apr 15, 2023 |
| Panasonic     | CF-C2CCEZXCM                | Notebook    | [361573ef78](https://linux-hardware.org/?probe=361573ef78) | Apr 14, 2023 |
| Dell          | Inspiron 7460               | Notebook    | [ae861b54cd](https://linux-hardware.org/?probe=ae861b54cd) | Apr 14, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [b60b4dbb07](https://linux-hardware.org/?probe=b60b4dbb07) | Apr 14, 2023 |
| Dell          | Precision 5560              | Notebook    | [b6d20ef4bf](https://linux-hardware.org/?probe=b6d20ef4bf) | Apr 14, 2023 |
| Dell          | Precision 5560              | Notebook    | [b76f840bd9](https://linux-hardware.org/?probe=b76f840bd9) | Apr 14, 2023 |
| MSI           | H310M PRO-VD PLUS           | Desktop     | [9f6209111c](https://linux-hardware.org/?probe=9f6209111c) | Apr 14, 2023 |
| Toshiba       | PORTEGE X20W-E              | Convertible | [40894d0141](https://linux-hardware.org/?probe=40894d0141) | Apr 14, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [ec08193576](https://linux-hardware.org/?probe=ec08193576) | Apr 14, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d4f384271e](https://linux-hardware.org/?probe=d4f384271e) | Apr 14, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [c7ca0e9fd1](https://linux-hardware.org/?probe=c7ca0e9fd1) | Apr 14, 2023 |
| Toshiba       | PORTEGE X20W-E              | Convertible | [d2c04327fb](https://linux-hardware.org/?probe=d2c04327fb) | Apr 14, 2023 |
| HP            | ZBook 15                    | Notebook    | [c5397a7fbb](https://linux-hardware.org/?probe=c5397a7fbb) | Apr 14, 2023 |
| Gigabyte      | B560M H                     | Desktop     | [c59729f9d2](https://linux-hardware.org/?probe=c59729f9d2) | Apr 14, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [f02a5fef82](https://linux-hardware.org/?probe=f02a5fef82) | Apr 14, 2023 |
| Lenovo        | Legion 5 15IAH7 82RC        | Notebook    | [9cb53e6d6f](https://linux-hardware.org/?probe=9cb53e6d6f) | Apr 13, 2023 |
| HP            | ZBook 15                    | Notebook    | [aaaa838a8f](https://linux-hardware.org/?probe=aaaa838a8f) | Apr 13, 2023 |
| 3Logic Gro... | Graviton N15i-K2            | Notebook    | [7b75b7b08e](https://linux-hardware.org/?probe=7b75b7b08e) | Apr 13, 2023 |
| Dell          | Inspiron 5515               | Notebook    | [e7306b2521](https://linux-hardware.org/?probe=e7306b2521) | Apr 13, 2023 |
| Lenovo        | ThinkPad T490 20N2000NRT    | Notebook    | [ea97cd752d](https://linux-hardware.org/?probe=ea97cd752d) | Apr 13, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [2d321f3134](https://linux-hardware.org/?probe=2d321f3134) | Apr 13, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [1d6ace19a5](https://linux-hardware.org/?probe=1d6ace19a5) | Apr 13, 2023 |
| Dell          | Inspiron 5482               | Convertible | [2d1dbac3cf](https://linux-hardware.org/?probe=2d1dbac3cf) | Apr 13, 2023 |
| Lenovo        | Yoga 6 13ABR8 83B2          | Convertible | [817e4bb939](https://linux-hardware.org/?probe=817e4bb939) | Apr 13, 2023 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [29d92f085a](https://linux-hardware.org/?probe=29d92f085a) | Apr 12, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [77384847ef](https://linux-hardware.org/?probe=77384847ef) | Apr 12, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [ada19dbe5c](https://linux-hardware.org/?probe=ada19dbe5c) | Apr 12, 2023 |
| MSI           | MS-7388                     | Desktop     | [d7f892b3e2](https://linux-hardware.org/?probe=d7f892b3e2) | Apr 12, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [6182cca953](https://linux-hardware.org/?probe=6182cca953) | Apr 12, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [66924704d2](https://linux-hardware.org/?probe=66924704d2) | Apr 12, 2023 |
| Intel         | NUC8BEB J72692-304          | Mini pc     | [19c864f074](https://linux-hardware.org/?probe=19c864f074) | Apr 12, 2023 |
| Lenovo        | IdeaPad Slim 9 14ITL5 82... | Notebook    | [16a7a866f1](https://linux-hardware.org/?probe=16a7a866f1) | Apr 12, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [10da0191c4](https://linux-hardware.org/?probe=10da0191c4) | Apr 11, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [c279e7b8fe](https://linux-hardware.org/?probe=c279e7b8fe) | Apr 11, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [5662df110d](https://linux-hardware.org/?probe=5662df110d) | Apr 11, 2023 |
| Dell          | 0J3C2F A00                  | Desktop     | [12f634cf42](https://linux-hardware.org/?probe=12f634cf42) | Apr 11, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [da86532b55](https://linux-hardware.org/?probe=da86532b55) | Apr 11, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [e8645a51dc](https://linux-hardware.org/?probe=e8645a51dc) | Apr 11, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [3792cccd19](https://linux-hardware.org/?probe=3792cccd19) | Apr 11, 2023 |
| Notebook      | NH55RGQ                     | Notebook    | [7fc1310fc2](https://linux-hardware.org/?probe=7fc1310fc2) | Apr 11, 2023 |
| HP            | 225E                        | Desktop     | [46f665e085](https://linux-hardware.org/?probe=46f665e085) | Apr 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [3c1e7c6f4a](https://linux-hardware.org/?probe=3c1e7c6f4a) | Apr 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [9d3c5ea28d](https://linux-hardware.org/?probe=9d3c5ea28d) | Apr 11, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [ac983c99b9](https://linux-hardware.org/?probe=ac983c99b9) | Apr 10, 2023 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [6e4aea5587](https://linux-hardware.org/?probe=6e4aea5587) | Apr 10, 2023 |
| Lenovo        | ThinkPad L13 Yoga 20R6S1... | Convertible | [8ca7e7c5ad](https://linux-hardware.org/?probe=8ca7e7c5ad) | Apr 10, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [6fe9dfd9a6](https://linux-hardware.org/?probe=6fe9dfd9a6) | Apr 10, 2023 |
| ECS           | H61H2-M12                   | Desktop     | [f3e8f5eb22](https://linux-hardware.org/?probe=f3e8f5eb22) | Apr 10, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [11ecb91fec](https://linux-hardware.org/?probe=11ecb91fec) | Apr 09, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [621eb9522f](https://linux-hardware.org/?probe=621eb9522f) | Apr 09, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [87f9a72b18](https://linux-hardware.org/?probe=87f9a72b18) | Apr 09, 2023 |
| ASUSTek       | P552LA                      | Notebook    | [803ac095e7](https://linux-hardware.org/?probe=803ac095e7) | Apr 08, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [a334fb8e82](https://linux-hardware.org/?probe=a334fb8e82) | Apr 08, 2023 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [c06058447c](https://linux-hardware.org/?probe=c06058447c) | Apr 08, 2023 |
| Samsung       | Galaxy Book 12              | Tablet      | [d866c03132](https://linux-hardware.org/?probe=d866c03132) | Apr 08, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [f65d106f65](https://linux-hardware.org/?probe=f65d106f65) | Apr 08, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [5605228f3b](https://linux-hardware.org/?probe=5605228f3b) | Apr 08, 2023 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [e34683f5f0](https://linux-hardware.org/?probe=e34683f5f0) | Apr 07, 2023 |
| ASUSTek       | X553MA                      | Notebook    | [0a307c8c2b](https://linux-hardware.org/?probe=0a307c8c2b) | Apr 07, 2023 |
| HP            | Pavilion dv7                | Notebook    | [3a159264b1](https://linux-hardware.org/?probe=3a159264b1) | Apr 07, 2023 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [8c1127cfab](https://linux-hardware.org/?probe=8c1127cfab) | Apr 07, 2023 |
| Dell          | Latitude 7490               | Notebook    | [01957ea955](https://linux-hardware.org/?probe=01957ea955) | Apr 07, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [8d68ef79c3](https://linux-hardware.org/?probe=8d68ef79c3) | Apr 06, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [e9281d0364](https://linux-hardware.org/?probe=e9281d0364) | Apr 06, 2023 |
| Clevo         | M815P                       | Notebook    | [e5194b9fea](https://linux-hardware.org/?probe=e5194b9fea) | Apr 06, 2023 |
| Dell          | XPS 9320                    | Notebook    | [ff14e0074a](https://linux-hardware.org/?probe=ff14e0074a) | Apr 06, 2023 |
| MSI           | Katana 17 B12VGK            | Notebook    | [0f8f9e8ba8](https://linux-hardware.org/?probe=0f8f9e8ba8) | Apr 06, 2023 |
| Samsung       | 760XDA                      | Notebook    | [625178fa5a](https://linux-hardware.org/?probe=625178fa5a) | Apr 06, 2023 |
| NEC Comput... | PC-VK27MCZCK                | Notebook    | [e9572ebd2e](https://linux-hardware.org/?probe=e9572ebd2e) | Apr 06, 2023 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [320195c782](https://linux-hardware.org/?probe=320195c782) | Apr 06, 2023 |
| MSI           | Delta 15 A5EFK              | Notebook    | [d3066bb3d4](https://linux-hardware.org/?probe=d3066bb3d4) | Apr 06, 2023 |
| ASUSTek       | GL552VW                     | Notebook    | [ab450c0ddd](https://linux-hardware.org/?probe=ab450c0ddd) | Apr 06, 2023 |
| HP            | OMEN by Laptop 16-b1xxx     | Notebook    | [d741226152](https://linux-hardware.org/?probe=d741226152) | Apr 06, 2023 |
| Dell          | Latitude E7470              | Notebook    | [64721a0d8a](https://linux-hardware.org/?probe=64721a0d8a) | Apr 05, 2023 |
| ASUSTek       | T100TAF                     | Notebook    | [fed8f42482](https://linux-hardware.org/?probe=fed8f42482) | Apr 05, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [a64c365f62](https://linux-hardware.org/?probe=a64c365f62) | Apr 05, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [86291f499e](https://linux-hardware.org/?probe=86291f499e) | Apr 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [f98b9efce7](https://linux-hardware.org/?probe=f98b9efce7) | Apr 05, 2023 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [7e5be74f0b](https://linux-hardware.org/?probe=7e5be74f0b) | Apr 05, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [b469666726](https://linux-hardware.org/?probe=b469666726) | Apr 05, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [3a70dc24db](https://linux-hardware.org/?probe=3a70dc24db) | Apr 05, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [4710939159](https://linux-hardware.org/?probe=4710939159) | Apr 05, 2023 |
| HP            | 1495                        | Desktop     | [c0665ecb23](https://linux-hardware.org/?probe=c0665ecb23) | Apr 04, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [4c46d2ae80](https://linux-hardware.org/?probe=4c46d2ae80) | Apr 04, 2023 |
| ASUSTek       | X550JK                      | Notebook    | [b75b9b9fa2](https://linux-hardware.org/?probe=b75b9b9fa2) | Apr 04, 2023 |
| HP            | Notebook                    | Notebook    | [935131a649](https://linux-hardware.org/?probe=935131a649) | Apr 04, 2023 |
| HP            | Notebook                    | Notebook    | [f35bee3b90](https://linux-hardware.org/?probe=f35bee3b90) | Apr 04, 2023 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [316e31eae5](https://linux-hardware.org/?probe=316e31eae5) | Apr 04, 2023 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [088a09317e](https://linux-hardware.org/?probe=088a09317e) | Apr 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [c2240b20c2](https://linux-hardware.org/?probe=c2240b20c2) | Apr 04, 2023 |
| Notebook      | L140PU                      | Notebook    | [628319771e](https://linux-hardware.org/?probe=628319771e) | Apr 04, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [f801258fa5](https://linux-hardware.org/?probe=f801258fa5) | Apr 04, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [ddbd47af34](https://linux-hardware.org/?probe=ddbd47af34) | Apr 04, 2023 |
| Itautec       | ST 4265 ST-4265 Padrao 0... | Desktop     | [26e8d46d94](https://linux-hardware.org/?probe=26e8d46d94) | Apr 03, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [84c709f5f9](https://linux-hardware.org/?probe=84c709f5f9) | Apr 03, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [95a98c59b1](https://linux-hardware.org/?probe=95a98c59b1) | Apr 03, 2023 |
| Fanless Mi... | Rev GMLR1                   | Mini pc     | [58eae7ff4e](https://linux-hardware.org/?probe=58eae7ff4e) | Apr 03, 2023 |
| Fujitsu       | LIFEBOOK U747               | Notebook    | [868448ea4b](https://linux-hardware.org/?probe=868448ea4b) | Apr 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [e6a732e9b0](https://linux-hardware.org/?probe=e6a732e9b0) | Apr 03, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [0b97a5a77a](https://linux-hardware.org/?probe=0b97a5a77a) | Apr 03, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [e65532d978](https://linux-hardware.org/?probe=e65532d978) | Apr 03, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [ada2cb6e08](https://linux-hardware.org/?probe=ada2cb6e08) | Apr 02, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [a761c8f978](https://linux-hardware.org/?probe=a761c8f978) | Apr 02, 2023 |
| Toshiba       | Satellite C55-B             | Notebook    | [da341e3be8](https://linux-hardware.org/?probe=da341e3be8) | Apr 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [f995b3a81f](https://linux-hardware.org/?probe=f995b3a81f) | Apr 02, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [65cee818b6](https://linux-hardware.org/?probe=65cee818b6) | Apr 02, 2023 |
| Samsung       | 550P5C/550P7C               | Notebook    | [8e6191f4bb](https://linux-hardware.org/?probe=8e6191f4bb) | Apr 02, 2023 |
| Medion        | MS-7728                     | Desktop     | [83f7f01bde](https://linux-hardware.org/?probe=83f7f01bde) | Apr 02, 2023 |
| ilife         | S806                        | Notebook    | [d089301e66](https://linux-hardware.org/?probe=d089301e66) | Apr 02, 2023 |
| Lenovo        | ThinkPad E14 20RAS0D800     | Notebook    | [ea2f5b484f](https://linux-hardware.org/?probe=ea2f5b484f) | Apr 02, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [60e80d51ab](https://linux-hardware.org/?probe=60e80d51ab) | Apr 02, 2023 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [71f34e6ebc](https://linux-hardware.org/?probe=71f34e6ebc) | Apr 02, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [30e0bd8317](https://linux-hardware.org/?probe=30e0bd8317) | Apr 02, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [f3b1797500](https://linux-hardware.org/?probe=f3b1797500) | Apr 02, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [94df0605ae](https://linux-hardware.org/?probe=94df0605ae) | Apr 02, 2023 |
| Lenovo        | ThinkPad A485 20MUCTO1WW    | Notebook    | [f64cf6a2ae](https://linux-hardware.org/?probe=f64cf6a2ae) | Apr 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [9148a1d487](https://linux-hardware.org/?probe=9148a1d487) | Apr 02, 2023 |
| HP            | Snappy                      | Notebook    | [993161a4c7](https://linux-hardware.org/?probe=993161a4c7) | Apr 02, 2023 |
| Chuwi         | LarkBox Pro                 | Mini pc     | [237eb0712d](https://linux-hardware.org/?probe=237eb0712d) | Apr 02, 2023 |
| ASRock        | J3160DC-ITX                 | Desktop     | [7735423853](https://linux-hardware.org/?probe=7735423853) | Apr 02, 2023 |
| BYTENUC       | AZ51                        | Mini pc     | [d75fba5311](https://linux-hardware.org/?probe=d75fba5311) | Apr 02, 2023 |
| ilife         | S806                        | Notebook    | [3a3ccd7c55](https://linux-hardware.org/?probe=3a3ccd7c55) | Apr 02, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [dabe76e4ca](https://linux-hardware.org/?probe=dabe76e4ca) | Apr 01, 2023 |
| Lenovo        | 30FD NOK                    | Mini pc     | [f355bab53f](https://linux-hardware.org/?probe=f355bab53f) | Apr 01, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [f278e6aad0](https://linux-hardware.org/?probe=f278e6aad0) | Apr 01, 2023 |
| HP            | ProBook 6475b               | Notebook    | [680348d948](https://linux-hardware.org/?probe=680348d948) | Apr 01, 2023 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [30d25bdb17](https://linux-hardware.org/?probe=30d25bdb17) | Apr 01, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [b4a624599e](https://linux-hardware.org/?probe=b4a624599e) | Apr 01, 2023 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [f0d73d9284](https://linux-hardware.org/?probe=f0d73d9284) | Apr 01, 2023 |
| ASUSTek       | T100TA                      | Notebook    | [5be9a0230e](https://linux-hardware.org/?probe=5be9a0230e) | Apr 01, 2023 |
| MSI           | MAG B660M MORTAR WIFI DD... | Desktop     | [c512f4cdd9](https://linux-hardware.org/?probe=c512f4cdd9) | Apr 01, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [79d44a9e66](https://linux-hardware.org/?probe=79d44a9e66) | Apr 01, 2023 |
| MSI           | MAG B660M MORTAR WIFI DD... | Desktop     | [e615755655](https://linux-hardware.org/?probe=e615755655) | Apr 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [4a9aebc7f0](https://linux-hardware.org/?probe=4a9aebc7f0) | Apr 01, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [acfff71638](https://linux-hardware.org/?probe=acfff71638) | Mar 31, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [36fab57ba7](https://linux-hardware.org/?probe=36fab57ba7) | Mar 31, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [5800e3859c](https://linux-hardware.org/?probe=5800e3859c) | Mar 31, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | Notebook    | [c76f4f4354](https://linux-hardware.org/?probe=c76f4f4354) | Mar 31, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | Notebook    | [3a74487ae8](https://linux-hardware.org/?probe=3a74487ae8) | Mar 31, 2023 |
| Toshiba       | Satellite U940              | Notebook    | [277dba9c1f](https://linux-hardware.org/?probe=277dba9c1f) | Mar 31, 2023 |
| Gigabyte      | Z270P-D3-CF                 | Desktop     | [8ce3dc1981](https://linux-hardware.org/?probe=8ce3dc1981) | Mar 31, 2023 |
| Toshiba       | Satellite U940              | Notebook    | [8a5046cad7](https://linux-hardware.org/?probe=8a5046cad7) | Mar 31, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS1... | Convertible | [bb2f5a2276](https://linux-hardware.org/?probe=bb2f5a2276) | Mar 31, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [4693b65922](https://linux-hardware.org/?probe=4693b65922) | Mar 31, 2023 |
| MSI           | GS66 Stealth 10SF           | Notebook    | [a2589dd6f5](https://linux-hardware.org/?probe=a2589dd6f5) | Mar 31, 2023 |
| Google        | Cave                        | Notebook    | [8bd24407be](https://linux-hardware.org/?probe=8bd24407be) | Mar 31, 2023 |
| ASUSTek       | TUF B365M-PLUS GAMING       | Desktop     | [8d4ef602e5](https://linux-hardware.org/?probe=8d4ef602e5) | Mar 31, 2023 |
| Dell          | 0PP150 A00                  | Desktop     | [fdc879a486](https://linux-hardware.org/?probe=fdc879a486) | Mar 31, 2023 |
| Dell          | Latitude D620               | Notebook    | [801ede47a2](https://linux-hardware.org/?probe=801ede47a2) | Mar 31, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [fcb2279eb0](https://linux-hardware.org/?probe=fcb2279eb0) | Mar 31, 2023 |
| Acer          | Swift SFA16-41              | Notebook    | [e110fbb7d6](https://linux-hardware.org/?probe=e110fbb7d6) | Mar 31, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [1417777bbc](https://linux-hardware.org/?probe=1417777bbc) | Mar 30, 2023 |
| Gigabyte      | Z170XP-SLI-CF               | Desktop     | [70efcb81e9](https://linux-hardware.org/?probe=70efcb81e9) | Mar 30, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [2ac52b4538](https://linux-hardware.org/?probe=2ac52b4538) | Mar 30, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [5b087b11f5](https://linux-hardware.org/?probe=5b087b11f5) | Mar 30, 2023 |
| Dell          | Precision 5510              | Notebook    | [4bbf7f5ef2](https://linux-hardware.org/?probe=4bbf7f5ef2) | Mar 30, 2023 |
| AIR           | CX30500                     | Notebook    | [2ea4d0ec83](https://linux-hardware.org/?probe=2ea4d0ec83) | Mar 30, 2023 |
| Lenovo        | ThinkPad T470s 20HGS23V0... | Notebook    | [6af08c4bfe](https://linux-hardware.org/?probe=6af08c4bfe) | Mar 30, 2023 |
| Lenovo        | ThinkPad T470s 20HGS23V0... | Notebook    | [6f0d3fd82b](https://linux-hardware.org/?probe=6f0d3fd82b) | Mar 30, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [ab31f6f63d](https://linux-hardware.org/?probe=ab31f6f63d) | Mar 30, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [5cf96e41e0](https://linux-hardware.org/?probe=5cf96e41e0) | Mar 30, 2023 |
| Dell          | G15 5515                    | Notebook    | [7bb6311632](https://linux-hardware.org/?probe=7bb6311632) | Mar 30, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [881f70cb12](https://linux-hardware.org/?probe=881f70cb12) | Mar 30, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [bc798d371a](https://linux-hardware.org/?probe=bc798d371a) | Mar 30, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [159d154fca](https://linux-hardware.org/?probe=159d154fca) | Mar 30, 2023 |
| System76      | Thelio Mira thelio-mira-... | Desktop     | [4915a172bd](https://linux-hardware.org/?probe=4915a172bd) | Mar 29, 2023 |
| Dell          | Latitude 5580               | Notebook    | [84157deda8](https://linux-hardware.org/?probe=84157deda8) | Mar 29, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [2eb96be1ee](https://linux-hardware.org/?probe=2eb96be1ee) | Mar 29, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [6023df2b8b](https://linux-hardware.org/?probe=6023df2b8b) | Mar 29, 2023 |
| Dell          | Latitude 5420               | Notebook    | [aee5c648e7](https://linux-hardware.org/?probe=aee5c648e7) | Mar 29, 2023 |
| Dell          | Latitude 7430               | Notebook    | [3f3b04c185](https://linux-hardware.org/?probe=3f3b04c185) | Mar 29, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [2f6655b77c](https://linux-hardware.org/?probe=2f6655b77c) | Mar 29, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [bf2f7820cd](https://linux-hardware.org/?probe=bf2f7820cd) | Mar 29, 2023 |
| Notebook      | L140CU                      | Notebook    | [e24f4b285d](https://linux-hardware.org/?probe=e24f4b285d) | Mar 29, 2023 |
| Gigabyte      | Z270P-D3-CF                 | Desktop     | [a091222ad4](https://linux-hardware.org/?probe=a091222ad4) | Mar 29, 2023 |
| Notebook      | L140CU                      | Notebook    | [b1b0a5fc03](https://linux-hardware.org/?probe=b1b0a5fc03) | Mar 29, 2023 |
| Acer          | Veriton N4630G              | Desktop     | [fab3140b7b](https://linux-hardware.org/?probe=fab3140b7b) | Mar 29, 2023 |
| ASUSTek       | Zenbook UX5401ZA_UX5401Z... | Notebook    | [c8f2b78c09](https://linux-hardware.org/?probe=c8f2b78c09) | Mar 29, 2023 |
| Clevo         | M815P                       | Notebook    | [ac4eae2a0b](https://linux-hardware.org/?probe=ac4eae2a0b) | Mar 29, 2023 |
| Gigabyte      | P55-UD6-C                   | Desktop     | [7c56c30e23](https://linux-hardware.org/?probe=7c56c30e23) | Mar 29, 2023 |
| HP            | Pavilion g7                 | Notebook    | [5b1e547f92](https://linux-hardware.org/?probe=5b1e547f92) | Mar 29, 2023 |
| Gigabyte      | P55-UD6-C                   | Desktop     | [010ed7a818](https://linux-hardware.org/?probe=010ed7a818) | Mar 29, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [ccb2d60f5c](https://linux-hardware.org/?probe=ccb2d60f5c) | Mar 29, 2023 |
| HP            | Pavilion g7                 | Notebook    | [ce74564fd9](https://linux-hardware.org/?probe=ce74564fd9) | Mar 28, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [5520b0fc5f](https://linux-hardware.org/?probe=5520b0fc5f) | Mar 28, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | Notebook    | [67789fc0d1](https://linux-hardware.org/?probe=67789fc0d1) | Mar 28, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [042e72aea5](https://linux-hardware.org/?probe=042e72aea5) | Mar 28, 2023 |
| MSI           | B450M MORTAR                | Desktop     | [7febdf82c0](https://linux-hardware.org/?probe=7febdf82c0) | Mar 28, 2023 |
| Lenovo        | ThinkPad T470p 20J7S0QK0... | Notebook    | [7f5fb11940](https://linux-hardware.org/?probe=7f5fb11940) | Mar 28, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [151a527b35](https://linux-hardware.org/?probe=151a527b35) | Mar 28, 2023 |
| ASUSTek       | TX201LA                     | Notebook    | [27c77d0b6c](https://linux-hardware.org/?probe=27c77d0b6c) | Mar 28, 2023 |
| ASUSTek       | ROG Flow Z13 GZ301ZC_GZ3... | Tablet      | [e5644591de](https://linux-hardware.org/?probe=e5644591de) | Mar 28, 2023 |
| ASUSTek       | TP410UA                     | Convertible | [b74b7f7d31](https://linux-hardware.org/?probe=b74b7f7d31) | Mar 28, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [4b0ae8033f](https://linux-hardware.org/?probe=4b0ae8033f) | Mar 28, 2023 |
| Lenovo        | ThinkPad T495 20NJ000XGE    | Notebook    | [70715024f2](https://linux-hardware.org/?probe=70715024f2) | Mar 28, 2023 |
| Intel         | NUC11PABi7 K90104-305       | Mini pc     | [35510eaf63](https://linux-hardware.org/?probe=35510eaf63) | Mar 28, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [999219f420](https://linux-hardware.org/?probe=999219f420) | Mar 28, 2023 |
| Lenovo        | ThinkServer TS130           | Desktop     | [2a36fc5043](https://linux-hardware.org/?probe=2a36fc5043) | Mar 28, 2023 |
| Dell          | 08HPGT A01                  | Desktop     | [451ccd93f2](https://linux-hardware.org/?probe=451ccd93f2) | Mar 27, 2023 |
| Dell          | 08HPGT A01                  | Desktop     | [e38a63e793](https://linux-hardware.org/?probe=e38a63e793) | Mar 27, 2023 |
| Huanan        | X99-F8D V2.6                | Desktop     | [65f96586ec](https://linux-hardware.org/?probe=65f96586ec) | Mar 27, 2023 |
| HP            | Compaq 6720s                | Notebook    | [9998cb9bfb](https://linux-hardware.org/?probe=9998cb9bfb) | Mar 27, 2023 |
| HP            | 250 G1                      | Notebook    | [75cf798dde](https://linux-hardware.org/?probe=75cf798dde) | Mar 27, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [fc1af1a499](https://linux-hardware.org/?probe=fc1af1a499) | Mar 27, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [ccc0edffff](https://linux-hardware.org/?probe=ccc0edffff) | Mar 27, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [14380327b0](https://linux-hardware.org/?probe=14380327b0) | Mar 27, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [3173dc99b6](https://linux-hardware.org/?probe=3173dc99b6) | Mar 27, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [79dc82b50b](https://linux-hardware.org/?probe=79dc82b50b) | Mar 27, 2023 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [23ee1856bc](https://linux-hardware.org/?probe=23ee1856bc) | Mar 27, 2023 |
| Dell          | Latitude E5250              | Notebook    | [7d9e678484](https://linux-hardware.org/?probe=7d9e678484) | Mar 27, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [6b00de6bed](https://linux-hardware.org/?probe=6b00de6bed) | Mar 27, 2023 |
| Alienware     | 17 R4                       | Notebook    | [4a61d300b5](https://linux-hardware.org/?probe=4a61d300b5) | Mar 27, 2023 |
| Acer          | Predator PT515-51           | Notebook    | [2ac6541cf1](https://linux-hardware.org/?probe=2ac6541cf1) | Mar 27, 2023 |
| Dell          | Latitude 7280               | Notebook    | [409cf549eb](https://linux-hardware.org/?probe=409cf549eb) | Mar 27, 2023 |
| Dell          | 07PR60 A01                  | Desktop     | [f312d049e0](https://linux-hardware.org/?probe=f312d049e0) | Mar 27, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [e069fb2622](https://linux-hardware.org/?probe=e069fb2622) | Mar 26, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [0ab4054ab9](https://linux-hardware.org/?probe=0ab4054ab9) | Mar 26, 2023 |
| Dell          | G15 5515                    | Notebook    | [3af5157823](https://linux-hardware.org/?probe=3af5157823) | Mar 26, 2023 |
| Acer          | Veriton M2631 V:1.0         | Desktop     | [4a4f12631a](https://linux-hardware.org/?probe=4a4f12631a) | Mar 26, 2023 |
| Chuwi         | HeroBook Air                | Notebook    | [836112a53f](https://linux-hardware.org/?probe=836112a53f) | Mar 26, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [250e0a99d1](https://linux-hardware.org/?probe=250e0a99d1) | Mar 26, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [36d5ba7071](https://linux-hardware.org/?probe=36d5ba7071) | Mar 26, 2023 |
| MSI           | X79A-GD45 Plus              | Desktop     | [0a5446e862](https://linux-hardware.org/?probe=0a5446e862) | Mar 26, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [a607ac616d](https://linux-hardware.org/?probe=a607ac616d) | Mar 26, 2023 |
| Dell          | Latitude 7410               | Convertible | [59c5a72671](https://linux-hardware.org/?probe=59c5a72671) | Mar 26, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [3711318620](https://linux-hardware.org/?probe=3711318620) | Mar 26, 2023 |
| BESSTAR Te... | F6BFC                       | Desktop     | [881c531ee5](https://linux-hardware.org/?probe=881c531ee5) | Mar 25, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [2163c72a12](https://linux-hardware.org/?probe=2163c72a12) | Mar 25, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [95b0768bfc](https://linux-hardware.org/?probe=95b0768bfc) | Mar 25, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [a999580cf7](https://linux-hardware.org/?probe=a999580cf7) | Mar 25, 2023 |
| MSI           | 2AE0                        | Desktop     | [43a4a75176](https://linux-hardware.org/?probe=43a4a75176) | Mar 25, 2023 |
| Lenovo        | SHARKBAY No DPK             | Desktop     | [2941abc936](https://linux-hardware.org/?probe=2941abc936) | Mar 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [31788e7103](https://linux-hardware.org/?probe=31788e7103) | Mar 25, 2023 |
| ASRock        | AD525PV3                    | Desktop     | [84545fd0ea](https://linux-hardware.org/?probe=84545fd0ea) | Mar 25, 2023 |
| Dell          | Latitude E6230              | Notebook    | [1a248bdc33](https://linux-hardware.org/?probe=1a248bdc33) | Mar 25, 2023 |
| Lenovo        | G580 2189                   | Notebook    | [edba6da5b6](https://linux-hardware.org/?probe=edba6da5b6) | Mar 25, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [505777b9b6](https://linux-hardware.org/?probe=505777b9b6) | Mar 25, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [ae09be520b](https://linux-hardware.org/?probe=ae09be520b) | Mar 25, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [5acd2b0492](https://linux-hardware.org/?probe=5acd2b0492) | Mar 25, 2023 |
| HP            | OMEN by Laptop 16-b1xxx     | Notebook    | [0096d3d3b1](https://linux-hardware.org/?probe=0096d3d3b1) | Mar 25, 2023 |
| ASUSTek       | GL503VS                     | Notebook    | [8e066fcf6e](https://linux-hardware.org/?probe=8e066fcf6e) | Mar 25, 2023 |
| Samsung       | 950QED                      | Convertible | [14fa80f70c](https://linux-hardware.org/?probe=14fa80f70c) | Mar 25, 2023 |
| MSI           | Summit E16FlipEvo A11MT     | Notebook    | [62839dd4ac](https://linux-hardware.org/?probe=62839dd4ac) | Mar 24, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [24784bc54d](https://linux-hardware.org/?probe=24784bc54d) | Mar 24, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [c2255f36b2](https://linux-hardware.org/?probe=c2255f36b2) | Mar 24, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | Notebook    | [cbb1418cfa](https://linux-hardware.org/?probe=cbb1418cfa) | Mar 24, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [518cef7fe4](https://linux-hardware.org/?probe=518cef7fe4) | Mar 24, 2023 |
| Acer          | Aspire E5-574               | Notebook    | [51a085fb56](https://linux-hardware.org/?probe=51a085fb56) | Mar 24, 2023 |
| Dell          | G15 5515                    | Notebook    | [3510cdb4cf](https://linux-hardware.org/?probe=3510cdb4cf) | Mar 24, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [cce19de050](https://linux-hardware.org/?probe=cce19de050) | Mar 24, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [1503a33123](https://linux-hardware.org/?probe=1503a33123) | Mar 24, 2023 |
| Dell          | Precision 3551              | Notebook    | [bc979e320b](https://linux-hardware.org/?probe=bc979e320b) | Mar 24, 2023 |
| Dell          | Precision 3551              | Notebook    | [0509bee16a](https://linux-hardware.org/?probe=0509bee16a) | Mar 24, 2023 |
| ASUSTek       | ZenBook UX433FN_BX433FN     | Notebook    | [d8e67b032e](https://linux-hardware.org/?probe=d8e67b032e) | Mar 24, 2023 |
| MSI           | Modern 14 B4MW              | Notebook    | [c81d9f3b07](https://linux-hardware.org/?probe=c81d9f3b07) | Mar 24, 2023 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [88900a37b9](https://linux-hardware.org/?probe=88900a37b9) | Mar 24, 2023 |
| ASRock        | X670E Pro RS                | Desktop     | [8437e47a82](https://linux-hardware.org/?probe=8437e47a82) | Mar 24, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [b2cdf1deb7](https://linux-hardware.org/?probe=b2cdf1deb7) | Mar 24, 2023 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [56d564423e](https://linux-hardware.org/?probe=56d564423e) | Mar 24, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [ca7d9a9342](https://linux-hardware.org/?probe=ca7d9a9342) | Mar 24, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [3769ec9ab5](https://linux-hardware.org/?probe=3769ec9ab5) | Mar 24, 2023 |
| Dell          | Latitude 5580               | Notebook    | [d4ad4c55a6](https://linux-hardware.org/?probe=d4ad4c55a6) | Mar 24, 2023 |
| Itautec       | ST 4265                     | Desktop     | [4671d7c30e](https://linux-hardware.org/?probe=4671d7c30e) | Mar 23, 2023 |
| Dell          | Latitude 5285               | Notebook    | [a8114ded15](https://linux-hardware.org/?probe=a8114ded15) | Mar 23, 2023 |
| HP            | 250 G4                      | Notebook    | [e0ff721413](https://linux-hardware.org/?probe=e0ff721413) | Mar 23, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [4731315325](https://linux-hardware.org/?probe=4731315325) | Mar 23, 2023 |
| Dell          | Latitude 5285               | Notebook    | [baa8f358cf](https://linux-hardware.org/?probe=baa8f358cf) | Mar 23, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [aeb25bc22b](https://linux-hardware.org/?probe=aeb25bc22b) | Mar 23, 2023 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [7ed577df49](https://linux-hardware.org/?probe=7ed577df49) | Mar 23, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [50931f533e](https://linux-hardware.org/?probe=50931f533e) | Mar 23, 2023 |
| ASUSTek       | PRIME Z590M-PLUS            | Desktop     | [0027308e3d](https://linux-hardware.org/?probe=0027308e3d) | Mar 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [2d44e8f5c2](https://linux-hardware.org/?probe=2d44e8f5c2) | Mar 23, 2023 |
| Dell          | Latitude 5480               | Notebook    | [ff60b91842](https://linux-hardware.org/?probe=ff60b91842) | Mar 23, 2023 |
| Acer          | Aspire E3-112               | Notebook    | [721e804a03](https://linux-hardware.org/?probe=721e804a03) | Mar 23, 2023 |
| ASRock        | X79 Extreme6                | Desktop     | [1287699f09](https://linux-hardware.org/?probe=1287699f09) | Mar 23, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [950e4b69e8](https://linux-hardware.org/?probe=950e4b69e8) | Mar 23, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [bf24fe6112](https://linux-hardware.org/?probe=bf24fe6112) | Mar 23, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d32ee19009](https://linux-hardware.org/?probe=d32ee19009) | Mar 23, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [457915fe10](https://linux-hardware.org/?probe=457915fe10) | Mar 23, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [69e58cde56](https://linux-hardware.org/?probe=69e58cde56) | Mar 23, 2023 |
| Lenovo        | SDK0F82993 WIN              | Desktop     | [fbff3ec47c](https://linux-hardware.org/?probe=fbff3ec47c) | Mar 23, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [1159055040](https://linux-hardware.org/?probe=1159055040) | Mar 23, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [aad036448d](https://linux-hardware.org/?probe=aad036448d) | Mar 23, 2023 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [299072c37e](https://linux-hardware.org/?probe=299072c37e) | Mar 22, 2023 |
| Lenovo        | ThinkPad L380 20M6S3Q000    | Notebook    | [aab8aada0e](https://linux-hardware.org/?probe=aab8aada0e) | Mar 22, 2023 |
| Lenovo        | Legion 5 82B5               | Notebook    | [5298c41263](https://linux-hardware.org/?probe=5298c41263) | Mar 22, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [7b899e790a](https://linux-hardware.org/?probe=7b899e790a) | Mar 22, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [2be6f0d943](https://linux-hardware.org/?probe=2be6f0d943) | Mar 22, 2023 |
| Apple         | MacBookPro11,5              | Notebook    | [ac5768cd3f](https://linux-hardware.org/?probe=ac5768cd3f) | Mar 22, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [ea18262536](https://linux-hardware.org/?probe=ea18262536) | Mar 22, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [e973d0294d](https://linux-hardware.org/?probe=e973d0294d) | Mar 22, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [386f37d114](https://linux-hardware.org/?probe=386f37d114) | Mar 22, 2023 |
| Samsung       | 550XDA                      | Notebook    | [b145c438d7](https://linux-hardware.org/?probe=b145c438d7) | Mar 22, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [4ee498d9fc](https://linux-hardware.org/?probe=4ee498d9fc) | Mar 22, 2023 |
| MSI           | GF63 Thin 11SC              | Notebook    | [a63c9ded60](https://linux-hardware.org/?probe=a63c9ded60) | Mar 22, 2023 |
| MSI           | GF63 Thin 11SC              | Notebook    | [cc5ca6f040](https://linux-hardware.org/?probe=cc5ca6f040) | Mar 22, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [5207701ff8](https://linux-hardware.org/?probe=5207701ff8) | Mar 22, 2023 |
| Lenovo        | Legion 5 82B5               | Notebook    | [8dfc670e24](https://linux-hardware.org/?probe=8dfc670e24) | Mar 22, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [23e4353a34](https://linux-hardware.org/?probe=23e4353a34) | Mar 22, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [aede16096d](https://linux-hardware.org/?probe=aede16096d) | Mar 22, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [61025e6e8b](https://linux-hardware.org/?probe=61025e6e8b) | Mar 22, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [80d1a2d67d](https://linux-hardware.org/?probe=80d1a2d67d) | Mar 22, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [eb718edb23](https://linux-hardware.org/?probe=eb718edb23) | Mar 22, 2023 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [825332bfce](https://linux-hardware.org/?probe=825332bfce) | Mar 21, 2023 |
| Lenovo        | B50-10 80QR                 | Notebook    | [134bf99094](https://linux-hardware.org/?probe=134bf99094) | Mar 21, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [b4d5442d02](https://linux-hardware.org/?probe=b4d5442d02) | Mar 21, 2023 |
| NZXT          | N7 B550                     | Desktop     | [8ca9bc3db9](https://linux-hardware.org/?probe=8ca9bc3db9) | Mar 21, 2023 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [6d96576431](https://linux-hardware.org/?probe=6d96576431) | Mar 21, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [dbbcf4a29a](https://linux-hardware.org/?probe=dbbcf4a29a) | Mar 21, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [ec2390af74](https://linux-hardware.org/?probe=ec2390af74) | Mar 21, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [a9c58c1f47](https://linux-hardware.org/?probe=a9c58c1f47) | Mar 21, 2023 |
| Dell          | Vostro 14-5480              | Notebook    | [ee892df403](https://linux-hardware.org/?probe=ee892df403) | Mar 21, 2023 |
| Shuttle       | SH570                       | Desktop     | [3ef2bf52b7](https://linux-hardware.org/?probe=3ef2bf52b7) | Mar 21, 2023 |
| Notebook      | W51XTU                      | Notebook    | [de60f3fcba](https://linux-hardware.org/?probe=de60f3fcba) | Mar 21, 2023 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [57663c8d60](https://linux-hardware.org/?probe=57663c8d60) | Mar 21, 2023 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [f5cbd1977f](https://linux-hardware.org/?probe=f5cbd1977f) | Mar 20, 2023 |
| Hampoo        | Cherry Trail CR Hampoo_r... | Notebook    | [e7eb855568](https://linux-hardware.org/?probe=e7eb855568) | Mar 20, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [3298f3c951](https://linux-hardware.org/?probe=3298f3c951) | Mar 20, 2023 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [1686ba2df4](https://linux-hardware.org/?probe=1686ba2df4) | Mar 20, 2023 |
| Lenovo        | ThinkPad T480s 20L8002WM... | Notebook    | [762762da77](https://linux-hardware.org/?probe=762762da77) | Mar 20, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [cb21d30b9e](https://linux-hardware.org/?probe=cb21d30b9e) | Mar 20, 2023 |
| MSI           | PRO Z790-P WIFI             | Desktop     | [038bd3a32b](https://linux-hardware.org/?probe=038bd3a32b) | Mar 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [7fb78c1c79](https://linux-hardware.org/?probe=7fb78c1c79) | Mar 20, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [e3e0efa236](https://linux-hardware.org/?probe=e3e0efa236) | Mar 20, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [4483bfa54d](https://linux-hardware.org/?probe=4483bfa54d) | Mar 20, 2023 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [1840c57073](https://linux-hardware.org/?probe=1840c57073) | Mar 20, 2023 |
| Win elemen... | M600                        | Desktop     | [eb40c2a7fc](https://linux-hardware.org/?probe=eb40c2a7fc) | Mar 20, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [c63a27da32](https://linux-hardware.org/?probe=c63a27da32) | Mar 20, 2023 |
| ASRock        | H81M-HG4 R4.0               | Desktop     | [ef87ac1a64](https://linux-hardware.org/?probe=ef87ac1a64) | Mar 20, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [53a3d14aa0](https://linux-hardware.org/?probe=53a3d14aa0) | Mar 20, 2023 |
| Microsoft     | Surface Laptop 2            | Tablet      | [58900f0caa](https://linux-hardware.org/?probe=58900f0caa) | Mar 19, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [cb27b0fbaf](https://linux-hardware.org/?probe=cb27b0fbaf) | Mar 19, 2023 |
| Dell          | 0YXT71 A00                  | Desktop     | [7a4669a603](https://linux-hardware.org/?probe=7a4669a603) | Mar 19, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [4ad2d5c249](https://linux-hardware.org/?probe=4ad2d5c249) | Mar 19, 2023 |
| Prestigio     | PSB141C01BFH                | Notebook    | [9190e0a0e7](https://linux-hardware.org/?probe=9190e0a0e7) | Mar 19, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [4223bbbf7e](https://linux-hardware.org/?probe=4223bbbf7e) | Mar 19, 2023 |
| Avell High... | B.ON                        | Notebook    | [b215c2fd75](https://linux-hardware.org/?probe=b215c2fd75) | Mar 19, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [5033dda127](https://linux-hardware.org/?probe=5033dda127) | Mar 19, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D60... | Notebook    | [63b182c7d6](https://linux-hardware.org/?probe=63b182c7d6) | Mar 19, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [93ff9f0891](https://linux-hardware.org/?probe=93ff9f0891) | Mar 19, 2023 |
| Toshiba       | Satellite C75D-B            | Notebook    | [1ff56ed31f](https://linux-hardware.org/?probe=1ff56ed31f) | Mar 19, 2023 |
| HP            | G62                         | Notebook    | [2cb4092da0](https://linux-hardware.org/?probe=2cb4092da0) | Mar 19, 2023 |
| HP            | G62                         | Notebook    | [76d7e36f21](https://linux-hardware.org/?probe=76d7e36f21) | Mar 19, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [dca0487261](https://linux-hardware.org/?probe=dca0487261) | Mar 19, 2023 |
| HONOR         | GLO-FX6P                    | Notebook    | [0fb3ebc365](https://linux-hardware.org/?probe=0fb3ebc365) | Mar 19, 2023 |
| ASUSTek       | PRIME Z690-P                | Desktop     | [923aa59ad5](https://linux-hardware.org/?probe=923aa59ad5) | Mar 19, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [88b7883383](https://linux-hardware.org/?probe=88b7883383) | Mar 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [cbad8c5f1e](https://linux-hardware.org/?probe=cbad8c5f1e) | Mar 18, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [b63ad62fc2](https://linux-hardware.org/?probe=b63ad62fc2) | Mar 18, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [783a968012](https://linux-hardware.org/?probe=783a968012) | Mar 18, 2023 |
| MSI           | B365M PRO-VDH               | Desktop     | [3332cb54e5](https://linux-hardware.org/?probe=3332cb54e5) | Mar 18, 2023 |
| Acer          | Aspire A315-54              | Notebook    | [49b005770d](https://linux-hardware.org/?probe=49b005770d) | Mar 18, 2023 |
| Acer          | Aspire A315-54              | Notebook    | [6af556d727](https://linux-hardware.org/?probe=6af556d727) | Mar 18, 2023 |
| Dell          | Vostro 5471                 | Notebook    | [3b0eb35766](https://linux-hardware.org/?probe=3b0eb35766) | Mar 18, 2023 |
| Dell          | Vostro 5471                 | Notebook    | [7743b2a5a9](https://linux-hardware.org/?probe=7743b2a5a9) | Mar 18, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [501c72715a](https://linux-hardware.org/?probe=501c72715a) | Mar 18, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [280e67175b](https://linux-hardware.org/?probe=280e67175b) | Mar 18, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [def0907a23](https://linux-hardware.org/?probe=def0907a23) | Mar 18, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [674c4a159e](https://linux-hardware.org/?probe=674c4a159e) | Mar 18, 2023 |
| ASUSTek       | X750JN                      | Notebook    | [7dd8257bc8](https://linux-hardware.org/?probe=7dd8257bc8) | Mar 18, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [bd119c8898](https://linux-hardware.org/?probe=bd119c8898) | Mar 17, 2023 |
| MSI           | GF65 Thin 10UE              | Notebook    | [8d2db4b0fe](https://linux-hardware.org/?probe=8d2db4b0fe) | Mar 17, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [f219a6e14a](https://linux-hardware.org/?probe=f219a6e14a) | Mar 17, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [35505ab2bf](https://linux-hardware.org/?probe=35505ab2bf) | Mar 17, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [261bcbfc32](https://linux-hardware.org/?probe=261bcbfc32) | Mar 17, 2023 |
| ASUSTek       | X750JN                      | Notebook    | [7ee3dac323](https://linux-hardware.org/?probe=7ee3dac323) | Mar 17, 2023 |
| ASUSTek       | M2N-E SLI                   | Desktop     | [bf5b0c4406](https://linux-hardware.org/?probe=bf5b0c4406) | Mar 17, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [d79a6ae160](https://linux-hardware.org/?probe=d79a6ae160) | Mar 17, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [691f338c53](https://linux-hardware.org/?probe=691f338c53) | Mar 17, 2023 |
| ASUSTek       | X555LB                      | Notebook    | [a00be2eabe](https://linux-hardware.org/?probe=a00be2eabe) | Mar 17, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [4d82c078c8](https://linux-hardware.org/?probe=4d82c078c8) | Mar 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [2ab659150c](https://linux-hardware.org/?probe=2ab659150c) | Mar 16, 2023 |
| HONOR         | BMH-WCX9                    | Notebook    | [47a9ec2aa1](https://linux-hardware.org/?probe=47a9ec2aa1) | Mar 16, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [03123126d0](https://linux-hardware.org/?probe=03123126d0) | Mar 16, 2023 |
| HP            | EliteBook 850 G2            | Notebook    | [f2b9853f35](https://linux-hardware.org/?probe=f2b9853f35) | Mar 16, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [b4483fd4e2](https://linux-hardware.org/?probe=b4483fd4e2) | Mar 16, 2023 |
| Lenovo        | ThinkPad T540p 20BFS1N00... | Notebook    | [03b210c1f8](https://linux-hardware.org/?probe=03b210c1f8) | Mar 16, 2023 |
| Dell          | Latitude D620               | Notebook    | [1731735e10](https://linux-hardware.org/?probe=1731735e10) | Mar 16, 2023 |
| LG Electro... | 15Z980-G.BH72P1             | Notebook    | [0bba01d850](https://linux-hardware.org/?probe=0bba01d850) | Mar 16, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [5667e8416e](https://linux-hardware.org/?probe=5667e8416e) | Mar 16, 2023 |
| Dell          | Latitude E5470              | Notebook    | [cc4f08349d](https://linux-hardware.org/?probe=cc4f08349d) | Mar 16, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [5bf235f5d3](https://linux-hardware.org/?probe=5bf235f5d3) | Mar 16, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [6023b7ce1d](https://linux-hardware.org/?probe=6023b7ce1d) | Mar 16, 2023 |
| Lenovo        | 32E6 SDK0T76530 WIN 3556... | Desktop     | [69cb363858](https://linux-hardware.org/?probe=69cb363858) | Mar 16, 2023 |
| Lenovo        | 32E6 SDK0T76530 WIN 3556... | Desktop     | [c9e4cb7c2e](https://linux-hardware.org/?probe=c9e4cb7c2e) | Mar 16, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [f48398a1e2](https://linux-hardware.org/?probe=f48398a1e2) | Mar 16, 2023 |
| Unknown       | V00                         | Mini pc     | [3a2e981385](https://linux-hardware.org/?probe=3a2e981385) | Mar 16, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [679da48c41](https://linux-hardware.org/?probe=679da48c41) | Mar 16, 2023 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [b72b91fd00](https://linux-hardware.org/?probe=b72b91fd00) | Mar 16, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [907581c9cc](https://linux-hardware.org/?probe=907581c9cc) | Mar 16, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [897879b2c7](https://linux-hardware.org/?probe=897879b2c7) | Mar 16, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [bf303c0c16](https://linux-hardware.org/?probe=bf303c0c16) | Mar 16, 2023 |
| Intel         | NUC5i5RYB H40999-502        | Mini pc     | [8f1af30bba](https://linux-hardware.org/?probe=8f1af30bba) | Mar 15, 2023 |
| MSI           | H81M-P33                    | Desktop     | [cb3d11f591](https://linux-hardware.org/?probe=cb3d11f591) | Mar 15, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0AF00    | Notebook    | [fe02ac3290](https://linux-hardware.org/?probe=fe02ac3290) | Mar 15, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [db96098c80](https://linux-hardware.org/?probe=db96098c80) | Mar 15, 2023 |
| MSI           | B450M MORTAR                | Desktop     | [14a4314e39](https://linux-hardware.org/?probe=14a4314e39) | Mar 15, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [d19eaf791f](https://linux-hardware.org/?probe=d19eaf791f) | Mar 15, 2023 |
| Dell          | Latitude 7430               | Notebook    | [58024877c3](https://linux-hardware.org/?probe=58024877c3) | Mar 15, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | Notebook    | [1e802bfcd0](https://linux-hardware.org/?probe=1e802bfcd0) | Mar 15, 2023 |
| Dell          | Latitude 5530               | Notebook    | [aac966a8af](https://linux-hardware.org/?probe=aac966a8af) | Mar 15, 2023 |
| Dell          | Latitude 7390               | Notebook    | [7cc6b3a278](https://linux-hardware.org/?probe=7cc6b3a278) | Mar 15, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [a519acdd2e](https://linux-hardware.org/?probe=a519acdd2e) | Mar 15, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [96f3739077](https://linux-hardware.org/?probe=96f3739077) | Mar 15, 2023 |
| HP            | 245 G8 Notebook PC          | Notebook    | [6c73c46184](https://linux-hardware.org/?probe=6c73c46184) | Mar 15, 2023 |
| ASUSTek       | X550MD                      | Notebook    | [2cd5ae8a43](https://linux-hardware.org/?probe=2cd5ae8a43) | Mar 15, 2023 |
| Toshiba       | Satellite P55t-B            | Notebook    | [7bd981d445](https://linux-hardware.org/?probe=7bd981d445) | Mar 15, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [fb73add0f6](https://linux-hardware.org/?probe=fb73add0f6) | Mar 14, 2023 |
| Dell          | Inspiron 7375               | Notebook    | [430599b2da](https://linux-hardware.org/?probe=430599b2da) | Mar 14, 2023 |
| Lenovo        | ThinkPad T490 20N3S3UL00    | Notebook    | [a9db94aee2](https://linux-hardware.org/?probe=a9db94aee2) | Mar 14, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [e6fd051ae8](https://linux-hardware.org/?probe=e6fd051ae8) | Mar 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [112d979fc6](https://linux-hardware.org/?probe=112d979fc6) | Mar 14, 2023 |
| MSI           | MS-AEA11                    | All in one  | [b1afba007b](https://linux-hardware.org/?probe=b1afba007b) | Mar 14, 2023 |
| Exo           | Smart XS1                   | Notebook    | [e1e04684eb](https://linux-hardware.org/?probe=e1e04684eb) | Mar 14, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [933110cc30](https://linux-hardware.org/?probe=933110cc30) | Mar 14, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [800c597040](https://linux-hardware.org/?probe=800c597040) | Mar 14, 2023 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [b324afc6f8](https://linux-hardware.org/?probe=b324afc6f8) | Mar 14, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | Notebook    | [d23ddde885](https://linux-hardware.org/?probe=d23ddde885) | Mar 14, 2023 |
| ASRock        | H170M Pro4                  | Desktop     | [c34ef2441a](https://linux-hardware.org/?probe=c34ef2441a) | Mar 14, 2023 |
| Intel         | W2600CR G21602-308          | Server      | [96cda648c2](https://linux-hardware.org/?probe=96cda648c2) | Mar 14, 2023 |
| Dell          | 0C96W1 A03                  | Desktop     | [171959ac44](https://linux-hardware.org/?probe=171959ac44) | Mar 14, 2023 |
| Dell          | 0C96W1 A03                  | Desktop     | [9456c9ff8e](https://linux-hardware.org/?probe=9456c9ff8e) | Mar 14, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [eac2f2ae40](https://linux-hardware.org/?probe=eac2f2ae40) | Mar 14, 2023 |
| System76      | Gazelle                     | Notebook    | [d45f36e46f](https://linux-hardware.org/?probe=d45f36e46f) | Mar 14, 2023 |
| MSI           | Katana GF76 11UD            | Notebook    | [37edbdcce5](https://linux-hardware.org/?probe=37edbdcce5) | Mar 14, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D60... | Notebook    | [2c2920d462](https://linux-hardware.org/?probe=2c2920d462) | Mar 14, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [d422d0d291](https://linux-hardware.org/?probe=d422d0d291) | Mar 14, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | Notebook    | [e6792912bf](https://linux-hardware.org/?probe=e6792912bf) | Mar 14, 2023 |
| MSI           | Stealth GS77 12UHS          | Notebook    | [fe00606a03](https://linux-hardware.org/?probe=fe00606a03) | Mar 14, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [59d2c50a02](https://linux-hardware.org/?probe=59d2c50a02) | Mar 14, 2023 |
| ASUSTek       | Rampage V EXTREME           | Desktop     | [e186537a7e](https://linux-hardware.org/?probe=e186537a7e) | Mar 14, 2023 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [532c5768ad](https://linux-hardware.org/?probe=532c5768ad) | Mar 14, 2023 |
| Toshiba       | Satellite L40               | Notebook    | [bfc73429bb](https://linux-hardware.org/?probe=bfc73429bb) | Mar 13, 2023 |
| HP            | Pro x2 612 G2               | Tablet      | [6ecc8f0bad](https://linux-hardware.org/?probe=6ecc8f0bad) | Mar 13, 2023 |
| Dell          | Inspiron 13 5320            | Notebook    | [efbe50cd5c](https://linux-hardware.org/?probe=efbe50cd5c) | Mar 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [c59a00db09](https://linux-hardware.org/?probe=c59a00db09) | Mar 13, 2023 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [ca456dde7d](https://linux-hardware.org/?probe=ca456dde7d) | Mar 13, 2023 |
| HP            | Pro x2 612 G2               | Tablet      | [13f42eb616](https://linux-hardware.org/?probe=13f42eb616) | Mar 13, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [70de894994](https://linux-hardware.org/?probe=70de894994) | Mar 13, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [815dfc26ec](https://linux-hardware.org/?probe=815dfc26ec) | Mar 13, 2023 |
| Samsung       | 300E5M/300E5L               | Notebook    | [8567b21f41](https://linux-hardware.org/?probe=8567b21f41) | Mar 13, 2023 |
| MSI           | PRO B550M-VC WIFI           | Desktop     | [c3a62d14b3](https://linux-hardware.org/?probe=c3a62d14b3) | Mar 13, 2023 |
| Gigabyte      | B650 AORUS PRO AX           | Desktop     | [e245557641](https://linux-hardware.org/?probe=e245557641) | Mar 13, 2023 |
| Gigabyte      | 990FXA-UD5 R5               | Desktop     | [532bf1dca2](https://linux-hardware.org/?probe=532bf1dca2) | Mar 13, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [74452c1274](https://linux-hardware.org/?probe=74452c1274) | Mar 13, 2023 |
| Acer          | Aspire R7-371T              | Notebook    | [b6aef449b6](https://linux-hardware.org/?probe=b6aef449b6) | Mar 13, 2023 |
| Lenovo        | Yoga 6-13ALC7 82UD          | Convertible | [6e3643ecb4](https://linux-hardware.org/?probe=6e3643ecb4) | Mar 13, 2023 |
| Lenovo        | IdeaPad U300s 20111         | Notebook    | [aaaee5fcf5](https://linux-hardware.org/?probe=aaaee5fcf5) | Mar 12, 2023 |
| Lenovo        | IdeaPad U300s 20111         | Notebook    | [3f3945f7e3](https://linux-hardware.org/?probe=3f3945f7e3) | Mar 12, 2023 |
| TECNO         | MEGABOOK T1                 | Notebook    | [000c3e4761](https://linux-hardware.org/?probe=000c3e4761) | Mar 12, 2023 |
| Acer          | One S1003                   | Tablet      | [89fff0b13a](https://linux-hardware.org/?probe=89fff0b13a) | Mar 12, 2023 |
| Dell          | Inspiron 5565               | Notebook    | [9415690de2](https://linux-hardware.org/?probe=9415690de2) | Mar 12, 2023 |
| Insyde        | BayTrail                    | Notebook    | [8d0337a8ee](https://linux-hardware.org/?probe=8d0337a8ee) | Mar 12, 2023 |
| Lenovo        | ThinkPad E590 20NBA000AU    | Notebook    | [47bfd44610](https://linux-hardware.org/?probe=47bfd44610) | Mar 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [5c45eb6864](https://linux-hardware.org/?probe=5c45eb6864) | Mar 12, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [1875fd875d](https://linux-hardware.org/?probe=1875fd875d) | Mar 12, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [28769bd85b](https://linux-hardware.org/?probe=28769bd85b) | Mar 12, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [e45386803e](https://linux-hardware.org/?probe=e45386803e) | Mar 12, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f70aee3bd6](https://linux-hardware.org/?probe=f70aee3bd6) | Mar 12, 2023 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [03c104f5f3](https://linux-hardware.org/?probe=03c104f5f3) | Mar 12, 2023 |
| Dell          | Vostro 14-5480              | Notebook    | [3ea64e75d4](https://linux-hardware.org/?probe=3ea64e75d4) | Mar 12, 2023 |
| ASUSTek       | PRIME Z690-P                | Desktop     | [76054930ac](https://linux-hardware.org/?probe=76054930ac) | Mar 12, 2023 |
| ASUSTek       | PRIME Z690-P                | Desktop     | [a925c8a320](https://linux-hardware.org/?probe=a925c8a320) | Mar 12, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [5434188010](https://linux-hardware.org/?probe=5434188010) | Mar 12, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | Notebook    | [8a8b88087b](https://linux-hardware.org/?probe=8a8b88087b) | Mar 12, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [07ebf171d6](https://linux-hardware.org/?probe=07ebf171d6) | Mar 12, 2023 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [d2b4cffe84](https://linux-hardware.org/?probe=d2b4cffe84) | Mar 11, 2023 |
| ASUSTek       | H170-PRO                    | Desktop     | [c3e0b5bc1d](https://linux-hardware.org/?probe=c3e0b5bc1d) | Mar 11, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [b7a4968bcd](https://linux-hardware.org/?probe=b7a4968bcd) | Mar 11, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | Notebook    | [8aff6217a5](https://linux-hardware.org/?probe=8aff6217a5) | Mar 11, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [599f8de7ba](https://linux-hardware.org/?probe=599f8de7ba) | Mar 11, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | Notebook    | [2a0539c2b1](https://linux-hardware.org/?probe=2a0539c2b1) | Mar 11, 2023 |
| Gigabyte      | Z170X-UD3 Ultra-CF          | Desktop     | [fa2be7de30](https://linux-hardware.org/?probe=fa2be7de30) | Mar 11, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | Notebook    | [5d69c96eca](https://linux-hardware.org/?probe=5d69c96eca) | Mar 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [7e7927f2dd](https://linux-hardware.org/?probe=7e7927f2dd) | Mar 11, 2023 |
| BESSTAR Te... | X300                        | Notebook    | [3f12a2f32e](https://linux-hardware.org/?probe=3f12a2f32e) | Mar 11, 2023 |
| BESSTAR Te... | X300                        | Notebook    | [a6ba9c1545](https://linux-hardware.org/?probe=a6ba9c1545) | Mar 11, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [1d552cfca2](https://linux-hardware.org/?probe=1d552cfca2) | Mar 11, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [d674283cb0](https://linux-hardware.org/?probe=d674283cb0) | Mar 11, 2023 |
| HP            | EliteBook x360 830 G6       | Convertible | [fd29c0dc4e](https://linux-hardware.org/?probe=fd29c0dc4e) | Mar 11, 2023 |
| Proline       | V146SH                      | Notebook    | [460deab2ea](https://linux-hardware.org/?probe=460deab2ea) | Mar 11, 2023 |
| Dell          | XPS 13 9300                 | Notebook    | [d3b7f2f978](https://linux-hardware.org/?probe=d3b7f2f978) | Mar 11, 2023 |
| ASUSTek       | G752VL                      | Notebook    | [4a4ea6f987](https://linux-hardware.org/?probe=4a4ea6f987) | Mar 11, 2023 |
| Acer          | Veriton X4620G v1.0         | Desktop     | [fc27bc474e](https://linux-hardware.org/?probe=fc27bc474e) | Mar 11, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [0f9de03c50](https://linux-hardware.org/?probe=0f9de03c50) | Mar 11, 2023 |
| Fujitsu       | LIFEBOOK U759               | Notebook    | [01025c7c43](https://linux-hardware.org/?probe=01025c7c43) | Mar 11, 2023 |
| MSI           | X370 XPOWER GAMING TITAN... | Desktop     | [abebd8a5c2](https://linux-hardware.org/?probe=abebd8a5c2) | Mar 11, 2023 |
| ASUSTek       | ZenBook 13 UX331UAL         | Notebook    | [9b38c9668e](https://linux-hardware.org/?probe=9b38c9668e) | Mar 10, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [037f2e4a2d](https://linux-hardware.org/?probe=037f2e4a2d) | Mar 10, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [f9cf8b06f6](https://linux-hardware.org/?probe=f9cf8b06f6) | Mar 10, 2023 |
| Lenovo        | ThinkPad T460 20LPS3K002    | Notebook    | [c375b36f4a](https://linux-hardware.org/?probe=c375b36f4a) | Mar 10, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [80ecfacebf](https://linux-hardware.org/?probe=80ecfacebf) | Mar 10, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [e9af5c4cb2](https://linux-hardware.org/?probe=e9af5c4cb2) | Mar 10, 2023 |
| Unknown       | Unknown                     | Notebook    | [cd382356be](https://linux-hardware.org/?probe=cd382356be) | Mar 10, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | Desktop     | [ca937e17a7](https://linux-hardware.org/?probe=ca937e17a7) | Mar 10, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [d35d11c64e](https://linux-hardware.org/?probe=d35d11c64e) | Mar 09, 2023 |
| Lenovo        | 3190 SDK0J40697 WIN 3305... | Mini pc     | [56b4f8a1a9](https://linux-hardware.org/?probe=56b4f8a1a9) | Mar 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [d35772b8bc](https://linux-hardware.org/?probe=d35772b8bc) | Mar 09, 2023 |
| HP            | Notebook                    | Notebook    | [b5ee32f085](https://linux-hardware.org/?probe=b5ee32f085) | Mar 09, 2023 |
| Lenovo        | ThinkPad T440p 20AWS0XX0... | Notebook    | [780937bb9f](https://linux-hardware.org/?probe=780937bb9f) | Mar 09, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [e27d91ea6f](https://linux-hardware.org/?probe=e27d91ea6f) | Mar 09, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [790877da61](https://linux-hardware.org/?probe=790877da61) | Mar 09, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [d7129009b0](https://linux-hardware.org/?probe=d7129009b0) | Mar 09, 2023 |
| Lenovo        | ThinkPad L13 Yoga 20R6S1... | Convertible | [970e94ad07](https://linux-hardware.org/?probe=970e94ad07) | Mar 09, 2023 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | Notebook    | [e4164a80cd](https://linux-hardware.org/?probe=e4164a80cd) | Mar 09, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [c50daaf3b9](https://linux-hardware.org/?probe=c50daaf3b9) | Mar 09, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [5535b412ed](https://linux-hardware.org/?probe=5535b412ed) | Mar 09, 2023 |
| Dell          | Inspiron 7375               | Notebook    | [2dbb99bbb2](https://linux-hardware.org/?probe=2dbb99bbb2) | Mar 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [2664be8926](https://linux-hardware.org/?probe=2664be8926) | Mar 09, 2023 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [9cd2cf85c7](https://linux-hardware.org/?probe=9cd2cf85c7) | Mar 09, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | Notebook    | [dc915e443d](https://linux-hardware.org/?probe=dc915e443d) | Mar 09, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [97698bd9a9](https://linux-hardware.org/?probe=97698bd9a9) | Mar 09, 2023 |
| Google        | Cave                        | Notebook    | [37d6d413b7](https://linux-hardware.org/?probe=37d6d413b7) | Mar 09, 2023 |
| Intel         | NUC5i5RYB H40999-502        | Mini pc     | [7d6aa1edeb](https://linux-hardware.org/?probe=7d6aa1edeb) | Mar 08, 2023 |
| Dell          | Inspiron 3505               | Notebook    | [5ffa875792](https://linux-hardware.org/?probe=5ffa875792) | Mar 08, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b349a8eedd](https://linux-hardware.org/?probe=b349a8eedd) | Mar 08, 2023 |
| Intel         | ArcherCity                  | Server      | [3ddb00da94](https://linux-hardware.org/?probe=3ddb00da94) | Mar 08, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [ac772ea51f](https://linux-hardware.org/?probe=ac772ea51f) | Mar 08, 2023 |
| Lenovo        | ThinkPad X12 Detachable ... | Tablet      | [89adccae04](https://linux-hardware.org/?probe=89adccae04) | Mar 08, 2023 |
| Lenovo        | ThinkPad T450s 20BX0013G... | Notebook    | [11cf435bfe](https://linux-hardware.org/?probe=11cf435bfe) | Mar 08, 2023 |
| ASRock        | Z370M Pro4                  | Desktop     | [c4bb8436ac](https://linux-hardware.org/?probe=c4bb8436ac) | Mar 08, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [f4de2d1a2a](https://linux-hardware.org/?probe=f4de2d1a2a) | Mar 08, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [a3a369de93](https://linux-hardware.org/?probe=a3a369de93) | Mar 08, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [439ea07bc5](https://linux-hardware.org/?probe=439ea07bc5) | Mar 08, 2023 |
| MSI           | MAG B460M MORTAR            | Desktop     | [233700c52d](https://linux-hardware.org/?probe=233700c52d) | Mar 08, 2023 |
| Dell          | Inspiron 14 5420            | Notebook    | [cb6ec54195](https://linux-hardware.org/?probe=cb6ec54195) | Mar 08, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [dfe7f75406](https://linux-hardware.org/?probe=dfe7f75406) | Mar 08, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [ffaa232ea2](https://linux-hardware.org/?probe=ffaa232ea2) | Mar 08, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [916862cd66](https://linux-hardware.org/?probe=916862cd66) | Mar 08, 2023 |
| Dell          | Latitude 5400               | Notebook    | [3d2504745e](https://linux-hardware.org/?probe=3d2504745e) | Mar 08, 2023 |
| HP            | ProBook 440 G7              | Notebook    | [7f4678dcf1](https://linux-hardware.org/?probe=7f4678dcf1) | Mar 07, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [62800640af](https://linux-hardware.org/?probe=62800640af) | Mar 07, 2023 |
| Dell          | Latitude 5300 2-in-1        | Convertible | [5a706c6543](https://linux-hardware.org/?probe=5a706c6543) | Mar 07, 2023 |
| AZW           | GTR V02                     | Desktop     | [030dde937b](https://linux-hardware.org/?probe=030dde937b) | Mar 07, 2023 |
| Dell          | Latitude 7290               | Notebook    | [38f12088b2](https://linux-hardware.org/?probe=38f12088b2) | Mar 07, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [1aaf3d1b9f](https://linux-hardware.org/?probe=1aaf3d1b9f) | Mar 07, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [e88ffa7e1d](https://linux-hardware.org/?probe=e88ffa7e1d) | Mar 07, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [bac7bd817d](https://linux-hardware.org/?probe=bac7bd817d) | Mar 07, 2023 |
| Acer          | One S1001                   | Notebook    | [b43d7f0a84](https://linux-hardware.org/?probe=b43d7f0a84) | Mar 06, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [5750b514a0](https://linux-hardware.org/?probe=5750b514a0) | Mar 06, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [1209c224e1](https://linux-hardware.org/?probe=1209c224e1) | Mar 06, 2023 |
| Microsoft     | Surface Laptop Go 2         | Tablet      | [f5a1ceaa74](https://linux-hardware.org/?probe=f5a1ceaa74) | Mar 06, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [6735fc94ae](https://linux-hardware.org/?probe=6735fc94ae) | Mar 06, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [3fb642aac7](https://linux-hardware.org/?probe=3fb642aac7) | Mar 06, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [798d6e74da](https://linux-hardware.org/?probe=798d6e74da) | Mar 06, 2023 |
| MSI           | MAG B460M MORTAR            | Desktop     | [de44275a2c](https://linux-hardware.org/?probe=de44275a2c) | Mar 06, 2023 |
| HP            | ProLiant DL380p Gen8        | Server      | [c36bf90efb](https://linux-hardware.org/?probe=c36bf90efb) | Mar 06, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X6... | Notebook    | [bd9c4997b0](https://linux-hardware.org/?probe=bd9c4997b0) | Mar 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [98a2c9f264](https://linux-hardware.org/?probe=98a2c9f264) | Mar 06, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [4e05d0a0e9](https://linux-hardware.org/?probe=4e05d0a0e9) | Mar 06, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [4b6c93e678](https://linux-hardware.org/?probe=4b6c93e678) | Mar 06, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [0fca5ee94e](https://linux-hardware.org/?probe=0fca5ee94e) | Mar 06, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [d256faa9fc](https://linux-hardware.org/?probe=d256faa9fc) | Mar 06, 2023 |
| Dell          | 0RY007                      | Desktop     | [1aff8f499e](https://linux-hardware.org/?probe=1aff8f499e) | Mar 06, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [d725cc57f0](https://linux-hardware.org/?probe=d725cc57f0) | Mar 06, 2023 |
| Dell          | Inspiron 15 3525            | Notebook    | [cc3e080ded](https://linux-hardware.org/?probe=cc3e080ded) | Mar 06, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [14eb2d295d](https://linux-hardware.org/?probe=14eb2d295d) | Mar 06, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [e6421e9301](https://linux-hardware.org/?probe=e6421e9301) | Mar 06, 2023 |
| Huanan        | X99-TF                      | Desktop     | [99a3729e53](https://linux-hardware.org/?probe=99a3729e53) | Mar 05, 2023 |
| MSI           | B550M PRO                   | Desktop     | [6d904e2413](https://linux-hardware.org/?probe=6d904e2413) | Mar 05, 2023 |
| Dell          | Inspiron 3593               | Notebook    | [f33f04396c](https://linux-hardware.org/?probe=f33f04396c) | Mar 05, 2023 |
| HP            | 2B05                        | Desktop     | [deb075440f](https://linux-hardware.org/?probe=deb075440f) | Mar 05, 2023 |
| Acer          | Aspire A515-57T             | Notebook    | [ebd1e9103e](https://linux-hardware.org/?probe=ebd1e9103e) | Mar 05, 2023 |
| HP            | 2B05                        | Desktop     | [f21bd9cc58](https://linux-hardware.org/?probe=f21bd9cc58) | Mar 05, 2023 |
| ASUSTek       | P8P67 DELUXE                | Desktop     | [31e4b3ada8](https://linux-hardware.org/?probe=31e4b3ada8) | Mar 05, 2023 |
| Google        | Lillipup                    | Notebook    | [6c7cf4cd9e](https://linux-hardware.org/?probe=6c7cf4cd9e) | Mar 05, 2023 |
| Lenovo        | ThinkPad T15p Gen 1 20TN... | Notebook    | [0811163639](https://linux-hardware.org/?probe=0811163639) | Mar 05, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [dfc84acc1a](https://linux-hardware.org/?probe=dfc84acc1a) | Mar 05, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [42469e8f5d](https://linux-hardware.org/?probe=42469e8f5d) | Mar 05, 2023 |
| Gigabyte      | Z87X-UD3H-CF                | Desktop     | [f0b9f4e39f](https://linux-hardware.org/?probe=f0b9f4e39f) | Mar 05, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [d42a19d17b](https://linux-hardware.org/?probe=d42a19d17b) | Mar 05, 2023 |
| ASRock        | B560M-ITX/ac                | Desktop     | [0bbfe90659](https://linux-hardware.org/?probe=0bbfe90659) | Mar 05, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [eeb75c7723](https://linux-hardware.org/?probe=eeb75c7723) | Mar 05, 2023 |
| Dell          | Latitude 5410               | Notebook    | [6f55e8bbfe](https://linux-hardware.org/?probe=6f55e8bbfe) | Mar 05, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [e61f05b7f6](https://linux-hardware.org/?probe=e61f05b7f6) | Mar 05, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U4S... | Notebook    | [fb996384c6](https://linux-hardware.org/?probe=fb996384c6) | Mar 05, 2023 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [79e06d188d](https://linux-hardware.org/?probe=79e06d188d) | Mar 04, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [925e02d1dc](https://linux-hardware.org/?probe=925e02d1dc) | Mar 04, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [e2ad6f0e57](https://linux-hardware.org/?probe=e2ad6f0e57) | Mar 04, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [7d9acf8639](https://linux-hardware.org/?probe=7d9acf8639) | Mar 04, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [a28f5eeec0](https://linux-hardware.org/?probe=a28f5eeec0) | Mar 04, 2023 |
| Toshiba       | Satellite L40               | Notebook    | [bd108fcfba](https://linux-hardware.org/?probe=bd108fcfba) | Mar 04, 2023 |
| ASRock        | X470 Taichi                 | Desktop     | [59392dfa37](https://linux-hardware.org/?probe=59392dfa37) | Mar 04, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [6f7115f084](https://linux-hardware.org/?probe=6f7115f084) | Mar 04, 2023 |
| ASUSTek       | ROG Flow X16 GV601RM_GV6... | Convertible | [d24552db45](https://linux-hardware.org/?probe=d24552db45) | Mar 04, 2023 |
| MSI           | B350 TOMAHAWK ARCTIC        | Desktop     | [06063736c6](https://linux-hardware.org/?probe=06063736c6) | Mar 04, 2023 |
| Purism        | Librem 14                   | Notebook    | [fbae41cbd5](https://linux-hardware.org/?probe=fbae41cbd5) | Mar 04, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [b4110d0e0b](https://linux-hardware.org/?probe=b4110d0e0b) | Mar 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [bd5e51c339](https://linux-hardware.org/?probe=bd5e51c339) | Mar 04, 2023 |
| Toshiba       | Satellite L40               | Notebook    | [e3f1423c39](https://linux-hardware.org/?probe=e3f1423c39) | Mar 04, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | Notebook    | [1bcec582e3](https://linux-hardware.org/?probe=1bcec582e3) | Mar 03, 2023 |
| MSI           | MAG B460M MORTAR WIFI       | Desktop     | [4b9b04ef26](https://linux-hardware.org/?probe=4b9b04ef26) | Mar 03, 2023 |
| MSI           | MAG B460M MORTAR WIFI       | Desktop     | [b6535fad6b](https://linux-hardware.org/?probe=b6535fad6b) | Mar 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [1ee7b087a8](https://linux-hardware.org/?probe=1ee7b087a8) | Mar 03, 2023 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [196e49402d](https://linux-hardware.org/?probe=196e49402d) | Mar 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [4b20311834](https://linux-hardware.org/?probe=4b20311834) | Mar 03, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [cd6c75d08e](https://linux-hardware.org/?probe=cd6c75d08e) | Mar 03, 2023 |
| Chuwi         | HeroBook Air                | Notebook    | [43248e0ae9](https://linux-hardware.org/?probe=43248e0ae9) | Mar 03, 2023 |
| Toshiba       | Satellite L515              | Notebook    | [daf95cc1e5](https://linux-hardware.org/?probe=daf95cc1e5) | Mar 03, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [7efed287ee](https://linux-hardware.org/?probe=7efed287ee) | Mar 03, 2023 |
| MSI           | GS63VR 6RF                  | Notebook    | [dd60a9c73b](https://linux-hardware.org/?probe=dd60a9c73b) | Mar 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [5906e1b848](https://linux-hardware.org/?probe=5906e1b848) | Mar 03, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [c4c7ebf544](https://linux-hardware.org/?probe=c4c7ebf544) | Mar 03, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [191bd6ec28](https://linux-hardware.org/?probe=191bd6ec28) | Mar 03, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [391c255a97](https://linux-hardware.org/?probe=391c255a97) | Mar 03, 2023 |
| ASUSTek       | TUF Gaming B660M-E D4       | Desktop     | [277d16fb2a](https://linux-hardware.org/?probe=277d16fb2a) | Mar 02, 2023 |
| Microsoft     | Surface Go 3                | Tablet      | [86ec7ef027](https://linux-hardware.org/?probe=86ec7ef027) | Mar 02, 2023 |
| ASUSTek       | Maximus VII RANGER          | Desktop     | [3934b91be7](https://linux-hardware.org/?probe=3934b91be7) | Mar 02, 2023 |
| ASUSTek       | ROG Flow X13 GV301RE_GV3... | Convertible | [886538fe37](https://linux-hardware.org/?probe=886538fe37) | Mar 02, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [8ef1c9b71d](https://linux-hardware.org/?probe=8ef1c9b71d) | Mar 02, 2023 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [e5b411431c](https://linux-hardware.org/?probe=e5b411431c) | Mar 02, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [22c9e146ee](https://linux-hardware.org/?probe=22c9e146ee) | Mar 02, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [6b7925d129](https://linux-hardware.org/?probe=6b7925d129) | Mar 02, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [e699d6bb6e](https://linux-hardware.org/?probe=e699d6bb6e) | Mar 02, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [883911a8df](https://linux-hardware.org/?probe=883911a8df) | Mar 02, 2023 |
| AZW           | SEi                         | Desktop     | [eb876ab2f4](https://linux-hardware.org/?probe=eb876ab2f4) | Mar 02, 2023 |
| AZW           | SEi                         | Desktop     | [7184a124c7](https://linux-hardware.org/?probe=7184a124c7) | Mar 02, 2023 |
| Dell          | 0KRC95 A02                  | Desktop     | [3bb7b686ec](https://linux-hardware.org/?probe=3bb7b686ec) | Mar 02, 2023 |
| HP            | 255 G3                      | Notebook    | [78c4cd0a9c](https://linux-hardware.org/?probe=78c4cd0a9c) | Mar 01, 2023 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | Desktop     | [420e6e6325](https://linux-hardware.org/?probe=420e6e6325) | Mar 01, 2023 |
| Lenovo        | Yoga 920-13IKB 80Y7         | Convertible | [43deb753b9](https://linux-hardware.org/?probe=43deb753b9) | Mar 01, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [50520b2cf0](https://linux-hardware.org/?probe=50520b2cf0) | Mar 01, 2023 |
| Gigabyte      | B365M GAMING HD             | Desktop     | [1b3d15d8f6](https://linux-hardware.org/?probe=1b3d15d8f6) | Mar 01, 2023 |
| Gigabyte      | B365M GAMING HD             | Desktop     | [0485a3d508](https://linux-hardware.org/?probe=0485a3d508) | Mar 01, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [9d6539b8f6](https://linux-hardware.org/?probe=9d6539b8f6) | Mar 01, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [588ac214ef](https://linux-hardware.org/?probe=588ac214ef) | Mar 01, 2023 |
| HP            | 834F                        | Desktop     | [96631603b3](https://linux-hardware.org/?probe=96631603b3) | Mar 01, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [8c878d99a1](https://linux-hardware.org/?probe=8c878d99a1) | Mar 01, 2023 |
| ASUSTek       | ROG Flow X13 GV301RE_GV3... | Convertible | [915d5fcb1d](https://linux-hardware.org/?probe=915d5fcb1d) | Mar 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [9ba7cfbdeb](https://linux-hardware.org/?probe=9ba7cfbdeb) | Mar 01, 2023 |
| Lenovo        | ThinkBook 15 G4 ABA 21DL    | Notebook    | [94809b7bc2](https://linux-hardware.org/?probe=94809b7bc2) | Mar 01, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [4d1bdc90ea](https://linux-hardware.org/?probe=4d1bdc90ea) | Mar 01, 2023 |
| MSI           | A320M GRENADE               | Desktop     | [1a5ffd0fc4](https://linux-hardware.org/?probe=1a5ffd0fc4) | Mar 01, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [6a99428156](https://linux-hardware.org/?probe=6a99428156) | Mar 01, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [3db8300147](https://linux-hardware.org/?probe=3db8300147) | Mar 01, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [1c09e468d0](https://linux-hardware.org/?probe=1c09e468d0) | Mar 01, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [713781f44e](https://linux-hardware.org/?probe=713781f44e) | Mar 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [833b6835b6](https://linux-hardware.org/?probe=833b6835b6) | Mar 01, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [165c0356a5](https://linux-hardware.org/?probe=165c0356a5) | Mar 01, 2023 |
| Dell          | 0KRC95 A02                  | Desktop     | [5cf1539621](https://linux-hardware.org/?probe=5cf1539621) | Mar 01, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [22d51a725f](https://linux-hardware.org/?probe=22d51a725f) | Feb 28, 2023 |
| Dell          | Latitude E7270              | Notebook    | [2718026d03](https://linux-hardware.org/?probe=2718026d03) | Feb 28, 2023 |
| TECNO         | MEGABOOK T1                 | Notebook    | [3b70c27ca4](https://linux-hardware.org/?probe=3b70c27ca4) | Feb 28, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [48c5c743c9](https://linux-hardware.org/?probe=48c5c743c9) | Feb 28, 2023 |
| ASRock        | H61M-VS                     | Desktop     | [04d5b9593e](https://linux-hardware.org/?probe=04d5b9593e) | Feb 28, 2023 |
| HUAWEI        | MRC-WX0                     | Notebook    | [e2776f99bf](https://linux-hardware.org/?probe=e2776f99bf) | Feb 28, 2023 |
| HP            | ProBook 635 Aero G8 Note... | Notebook    | [93ee76f198](https://linux-hardware.org/?probe=93ee76f198) | Feb 28, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [9a897f5d7c](https://linux-hardware.org/?probe=9a897f5d7c) | Feb 28, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | Notebook    | [b5a4a1809f](https://linux-hardware.org/?probe=b5a4a1809f) | Feb 28, 2023 |
| TECNO         | MEGABOOK T1                 | Notebook    | [3d003c6d17](https://linux-hardware.org/?probe=3d003c6d17) | Feb 28, 2023 |
| ASUSTek       | ROG Strix G712LW_G712LW     | Notebook    | [ed67c567d2](https://linux-hardware.org/?probe=ed67c567d2) | Feb 28, 2023 |
| Standard      | Unknown                     | Notebook    | [63732ac2da](https://linux-hardware.org/?probe=63732ac2da) | Feb 28, 2023 |
| HP            | 158A                        | Desktop     | [64f3590183](https://linux-hardware.org/?probe=64f3590183) | Feb 28, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [1b5fd0df61](https://linux-hardware.org/?probe=1b5fd0df61) | Feb 28, 2023 |
| Dell          | Precision 5570              | Notebook    | [7e8d7c37cb](https://linux-hardware.org/?probe=7e8d7c37cb) | Feb 28, 2023 |
| Fujitsu       | D3224-P1 S26361-D3224-P1    | Desktop     | [53649a9546](https://linux-hardware.org/?probe=53649a9546) | Feb 28, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [c829e9e0b8](https://linux-hardware.org/?probe=c829e9e0b8) | Feb 27, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [45403acec9](https://linux-hardware.org/?probe=45403acec9) | Feb 27, 2023 |
| HUAWEI        | MACHR-WX9                   | Notebook    | [b1ef7c7ea1](https://linux-hardware.org/?probe=b1ef7c7ea1) | Feb 27, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [43602775cd](https://linux-hardware.org/?probe=43602775cd) | Feb 27, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [1c1dc86eb1](https://linux-hardware.org/?probe=1c1dc86eb1) | Feb 27, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [ed251c6cfe](https://linux-hardware.org/?probe=ed251c6cfe) | Feb 27, 2023 |
| ASUSTek       | PRIME Q270M-C               | Desktop     | [3a9683fbb7](https://linux-hardware.org/?probe=3a9683fbb7) | Feb 27, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [dd5ce2c6db](https://linux-hardware.org/?probe=dd5ce2c6db) | Feb 27, 2023 |
| Toshiba       | Satellite P870              | Notebook    | [6d9216b866](https://linux-hardware.org/?probe=6d9216b866) | Feb 27, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [11aeca0c24](https://linux-hardware.org/?probe=11aeca0c24) | Feb 27, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [4c96506f38](https://linux-hardware.org/?probe=4c96506f38) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [d7e55bb97e](https://linux-hardware.org/?probe=d7e55bb97e) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [091e4e3188](https://linux-hardware.org/?probe=091e4e3188) | Feb 27, 2023 |
| Gigabyte      | Z490 VISION D               | Desktop     | [cbea73a793](https://linux-hardware.org/?probe=cbea73a793) | Feb 27, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [058ecdce01](https://linux-hardware.org/?probe=058ecdce01) | Feb 27, 2023 |
| ASUSTek       | ROG Flow X13 GV301RE_GV3... | Convertible | [7f7bdeae7c](https://linux-hardware.org/?probe=7f7bdeae7c) | Feb 27, 2023 |
| Gigabyte      | Z490 VISION D               | Desktop     | [3e9f2feeaa](https://linux-hardware.org/?probe=3e9f2feeaa) | Feb 27, 2023 |
| Gigabyte      | Z170MX-Gaming 5             | Desktop     | [1f0e9197f9](https://linux-hardware.org/?probe=1f0e9197f9) | Feb 26, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [a121d0545a](https://linux-hardware.org/?probe=a121d0545a) | Feb 26, 2023 |
| Lenovo        | ThinkPad X395 20NL0006US    | Notebook    | [9030fac261](https://linux-hardware.org/?probe=9030fac261) | Feb 26, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c56cf68cef](https://linux-hardware.org/?probe=c56cf68cef) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [fe8735a027](https://linux-hardware.org/?probe=fe8735a027) | Feb 26, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [85ed1d43c7](https://linux-hardware.org/?probe=85ed1d43c7) | Feb 26, 2023 |
| HP            | Notebook                    | Notebook    | [ab0dddc914](https://linux-hardware.org/?probe=ab0dddc914) | Feb 26, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [6b712e555f](https://linux-hardware.org/?probe=6b712e555f) | Feb 26, 2023 |
| Dell          | Vostro 3578                 | Notebook    | [da6968c8ac](https://linux-hardware.org/?probe=da6968c8ac) | Feb 26, 2023 |
| Gigabyte      | H510M S2                    | Desktop     | [24ea8468ca](https://linux-hardware.org/?probe=24ea8468ca) | Feb 26, 2023 |
| Samsung       | 370E4K                      | Notebook    | [7b769eb33e](https://linux-hardware.org/?probe=7b769eb33e) | Feb 26, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [c026a25fb2](https://linux-hardware.org/?probe=c026a25fb2) | Feb 26, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [af6a897a26](https://linux-hardware.org/?probe=af6a897a26) | Feb 26, 2023 |
| Timi          | TM1612                      | Notebook    | [eb4a3f330e](https://linux-hardware.org/?probe=eb4a3f330e) | Feb 26, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [d3b6621252](https://linux-hardware.org/?probe=d3b6621252) | Feb 26, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [f589c3687b](https://linux-hardware.org/?probe=f589c3687b) | Feb 26, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [d610badec8](https://linux-hardware.org/?probe=d610badec8) | Feb 26, 2023 |
| Lenovo        | ThinkPad T61 6464A13        | Notebook    | [e981803528](https://linux-hardware.org/?probe=e981803528) | Feb 26, 2023 |
| Standard      | Unknown                     | Notebook    | [9d002e0593](https://linux-hardware.org/?probe=9d002e0593) | Feb 26, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [c204192a4b](https://linux-hardware.org/?probe=c204192a4b) | Feb 26, 2023 |
| Lenovo        | Legion 5 82B5               | Notebook    | [8db23a7237](https://linux-hardware.org/?probe=8db23a7237) | Feb 25, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [bd2c3ecd74](https://linux-hardware.org/?probe=bd2c3ecd74) | Feb 25, 2023 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [d6805fb81b](https://linux-hardware.org/?probe=d6805fb81b) | Feb 25, 2023 |
| Lenovo        | ThinkPad T480 20L5S03600    | Notebook    | [5c9736ab0c](https://linux-hardware.org/?probe=5c9736ab0c) | Feb 25, 2023 |
| Dell          | Vostro 14-5459              | Notebook    | [1f96898a48](https://linux-hardware.org/?probe=1f96898a48) | Feb 25, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [420520e3ab](https://linux-hardware.org/?probe=420520e3ab) | Feb 25, 2023 |
| Dell          | Latitude E6420              | Notebook    | [7ae4fe9340](https://linux-hardware.org/?probe=7ae4fe9340) | Feb 25, 2023 |
| Dell          | Latitude 5511               | Notebook    | [4402838fb3](https://linux-hardware.org/?probe=4402838fb3) | Feb 25, 2023 |
| Google        | Voxel                       | Notebook    | [ce917fe8ec](https://linux-hardware.org/?probe=ce917fe8ec) | Feb 25, 2023 |
| Google        | Voxel                       | Notebook    | [93ea143f69](https://linux-hardware.org/?probe=93ea143f69) | Feb 25, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [be0b15660e](https://linux-hardware.org/?probe=be0b15660e) | Feb 25, 2023 |
| HUAWEI        | MACH-WX9                    | Notebook    | [52924074db](https://linux-hardware.org/?probe=52924074db) | Feb 25, 2023 |
| Dell          | 0W2F8G A01                  | Desktop     | [1d0d54843b](https://linux-hardware.org/?probe=1d0d54843b) | Feb 25, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [87c5af58f5](https://linux-hardware.org/?probe=87c5af58f5) | Feb 25, 2023 |
| Dell          | Precision 5520              | Notebook    | [c41014658b](https://linux-hardware.org/?probe=c41014658b) | Feb 25, 2023 |
| Dell          | System XPS L321X            | Notebook    | [4de5ba1c80](https://linux-hardware.org/?probe=4de5ba1c80) | Feb 25, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [1c1e5c991f](https://linux-hardware.org/?probe=1c1e5c991f) | Feb 25, 2023 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [3575d2e78d](https://linux-hardware.org/?probe=3575d2e78d) | Feb 25, 2023 |
| Gigabyte      | H310M S2 x.x                | Desktop     | [27fa5a62b6](https://linux-hardware.org/?probe=27fa5a62b6) | Feb 24, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [9cbbaaf012](https://linux-hardware.org/?probe=9cbbaaf012) | Feb 24, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [4a0d65f6b5](https://linux-hardware.org/?probe=4a0d65f6b5) | Feb 24, 2023 |
| MSI           | B350M PRO-VDH               | Desktop     | [748d109cb3](https://linux-hardware.org/?probe=748d109cb3) | Feb 24, 2023 |
| HP            | 84EF 01100                  | All in one  | [d69b1aab65](https://linux-hardware.org/?probe=d69b1aab65) | Feb 24, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [f8f1005d73](https://linux-hardware.org/?probe=f8f1005d73) | Feb 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [787270bc9e](https://linux-hardware.org/?probe=787270bc9e) | Feb 24, 2023 |
| Lenovo        | Yoga Pro 14s IAH7 82TK      | Notebook    | [ade006d016](https://linux-hardware.org/?probe=ade006d016) | Feb 24, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | Desktop     | [5d901ddc4e](https://linux-hardware.org/?probe=5d901ddc4e) | Feb 24, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [362c88435e](https://linux-hardware.org/?probe=362c88435e) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [2bbce041f5](https://linux-hardware.org/?probe=2bbce041f5) | Feb 24, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [2312252934](https://linux-hardware.org/?probe=2312252934) | Feb 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [f7063f868f](https://linux-hardware.org/?probe=f7063f868f) | Feb 24, 2023 |
| HP            | 245 G8 Notebook PC          | Notebook    | [7686bcd76d](https://linux-hardware.org/?probe=7686bcd76d) | Feb 24, 2023 |
| Dell          | Inspiron 13-7359            | Notebook    | [7858955f02](https://linux-hardware.org/?probe=7858955f02) | Feb 24, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [1fb6ff6899](https://linux-hardware.org/?probe=1fb6ff6899) | Feb 24, 2023 |
| Toshiba       | Satellite L515              | Notebook    | [969c2042b9](https://linux-hardware.org/?probe=969c2042b9) | Feb 24, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [6e57f3a472](https://linux-hardware.org/?probe=6e57f3a472) | Feb 24, 2023 |
| MSI           | Z170A PC MATE               | Desktop     | [5ee58b9271](https://linux-hardware.org/?probe=5ee58b9271) | Feb 24, 2023 |
| Dell          | G5 5587                     | Notebook    | [1f43871064](https://linux-hardware.org/?probe=1f43871064) | Feb 24, 2023 |
| MSI           | Z87M GAMING                 | Desktop     | [0603accd89](https://linux-hardware.org/?probe=0603accd89) | Feb 24, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [acdea94715](https://linux-hardware.org/?probe=acdea94715) | Feb 23, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | Notebook    | [f92ac89547](https://linux-hardware.org/?probe=f92ac89547) | Feb 23, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [4b0436b55d](https://linux-hardware.org/?probe=4b0436b55d) | Feb 23, 2023 |
| Gateway       | SX2185                      | Desktop     | [32ab171e53](https://linux-hardware.org/?probe=32ab171e53) | Feb 23, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [193a97dfb1](https://linux-hardware.org/?probe=193a97dfb1) | Feb 23, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [a4c4313238](https://linux-hardware.org/?probe=a4c4313238) | Feb 23, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [bb2bef71e0](https://linux-hardware.org/?probe=bb2bef71e0) | Feb 23, 2023 |
| Lenovo        | ThinkPad X230 2325CS6       | Notebook    | [ed9501bbcb](https://linux-hardware.org/?probe=ed9501bbcb) | Feb 23, 2023 |
| Dell          | Inspiron 13-7359            | Notebook    | [39d95063c3](https://linux-hardware.org/?probe=39d95063c3) | Feb 23, 2023 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [0f251d6bbf](https://linux-hardware.org/?probe=0f251d6bbf) | Feb 23, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [eade3920d9](https://linux-hardware.org/?probe=eade3920d9) | Feb 23, 2023 |
| ASUSTek       | P5L-MX                      | Desktop     | [cc19e49d3c](https://linux-hardware.org/?probe=cc19e49d3c) | Feb 23, 2023 |
| ASUSTek       | K56CA                       | Notebook    | [d8475e4c48](https://linux-hardware.org/?probe=d8475e4c48) | Feb 23, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [e23562af05](https://linux-hardware.org/?probe=e23562af05) | Feb 23, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [b82d73c832](https://linux-hardware.org/?probe=b82d73c832) | Feb 22, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [becb5b0ba1](https://linux-hardware.org/?probe=becb5b0ba1) | Feb 22, 2023 |
| CyberPower... | Tracer IV GM5MQ8W           | Notebook    | [284e8a4fb1](https://linux-hardware.org/?probe=284e8a4fb1) | Feb 22, 2023 |
| ASUSTek       | P5L-MX                      | Desktop     | [9eb9ca3cfb](https://linux-hardware.org/?probe=9eb9ca3cfb) | Feb 22, 2023 |
| Dell          | Latitude E5570              | Notebook    | [338538c1c9](https://linux-hardware.org/?probe=338538c1c9) | Feb 22, 2023 |
| Gigabyte      | G5 KD                       | Notebook    | [65c50530c8](https://linux-hardware.org/?probe=65c50530c8) | Feb 22, 2023 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [7d3442e2a7](https://linux-hardware.org/?probe=7d3442e2a7) | Feb 22, 2023 |
| Alienware     | x14                         | Notebook    | [0b32a33625](https://linux-hardware.org/?probe=0b32a33625) | Feb 22, 2023 |
| Alienware     | x14                         | Notebook    | [04094754b6](https://linux-hardware.org/?probe=04094754b6) | Feb 22, 2023 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [3e5166108a](https://linux-hardware.org/?probe=3e5166108a) | Feb 22, 2023 |
| Acer          | Veriton N4630G              | Desktop     | [eb6a551e75](https://linux-hardware.org/?probe=eb6a551e75) | Feb 22, 2023 |
| HP            | Notebook                    | Notebook    | [f6d3ba25ba](https://linux-hardware.org/?probe=f6d3ba25ba) | Feb 22, 2023 |
| Samsung       | 767XCL                      | Notebook    | [3fb09fb626](https://linux-hardware.org/?probe=3fb09fb626) | Feb 22, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [aaad317fe4](https://linux-hardware.org/?probe=aaad317fe4) | Feb 22, 2023 |
| Dell          | Latitude 5491               | Notebook    | [fd68ba9595](https://linux-hardware.org/?probe=fd68ba9595) | Feb 21, 2023 |
| ASRockRack    | X470D4U                     | Desktop     | [162a5279bc](https://linux-hardware.org/?probe=162a5279bc) | Feb 21, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [a459216464](https://linux-hardware.org/?probe=a459216464) | Feb 21, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [7ead9488ae](https://linux-hardware.org/?probe=7ead9488ae) | Feb 21, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [b9117f0c6f](https://linux-hardware.org/?probe=b9117f0c6f) | Feb 21, 2023 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | Notebook    | [c0733771d5](https://linux-hardware.org/?probe=c0733771d5) | Feb 21, 2023 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | Notebook    | [039bb422e0](https://linux-hardware.org/?probe=039bb422e0) | Feb 21, 2023 |
| Acer          | Aspire SW3-013              | Notebook    | [f0111df214](https://linux-hardware.org/?probe=f0111df214) | Feb 21, 2023 |
| Alienware     | 15 R2                       | Notebook    | [96aa09ae59](https://linux-hardware.org/?probe=96aa09ae59) | Feb 21, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [bf037f7503](https://linux-hardware.org/?probe=bf037f7503) | Feb 21, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [67ba988b20](https://linux-hardware.org/?probe=67ba988b20) | Feb 21, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [d1f67d5e08](https://linux-hardware.org/?probe=d1f67d5e08) | Feb 21, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [edd5640ca7](https://linux-hardware.org/?probe=edd5640ca7) | Feb 21, 2023 |
| MSI           | H410M PRO-VH                | Desktop     | [669d124e33](https://linux-hardware.org/?probe=669d124e33) | Feb 21, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [9989903f85](https://linux-hardware.org/?probe=9989903f85) | Feb 21, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [2b329d108f](https://linux-hardware.org/?probe=2b329d108f) | Feb 21, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [53737369e8](https://linux-hardware.org/?probe=53737369e8) | Feb 21, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | Notebook    | [b8c4b41baf](https://linux-hardware.org/?probe=b8c4b41baf) | Feb 21, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [a3ed8101b1](https://linux-hardware.org/?probe=a3ed8101b1) | Feb 20, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [f6c80ff7a9](https://linux-hardware.org/?probe=f6c80ff7a9) | Feb 20, 2023 |
| Fujitsu       | LIFEBOOK E559               | Notebook    | [5e4c3607c7](https://linux-hardware.org/?probe=5e4c3607c7) | Feb 20, 2023 |
| Fujitsu       | LIFEBOOK A357               | Notebook    | [a813f73ea2](https://linux-hardware.org/?probe=a813f73ea2) | Feb 20, 2023 |
| MSI           | Bravo 15 B5ED               | Notebook    | [a0b7f1b5f8](https://linux-hardware.org/?probe=a0b7f1b5f8) | Feb 20, 2023 |
| Lenovo        | ThinkPad T530 239265U       | Notebook    | [9f60ca6bf5](https://linux-hardware.org/?probe=9f60ca6bf5) | Feb 20, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [542077cc42](https://linux-hardware.org/?probe=542077cc42) | Feb 20, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [8fd85f724b](https://linux-hardware.org/?probe=8fd85f724b) | Feb 20, 2023 |
| Microsoft     | Surface Go                  | Tablet      | [6f456ca669](https://linux-hardware.org/?probe=6f456ca669) | Feb 20, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [057dcdc86b](https://linux-hardware.org/?probe=057dcdc86b) | Feb 20, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [d8abf7361b](https://linux-hardware.org/?probe=d8abf7361b) | Feb 20, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [89eb85b36f](https://linux-hardware.org/?probe=89eb85b36f) | Feb 19, 2023 |
| Lenovo        | ThinkCentre M58 8910B4U     | Desktop     | [03c8e6d135](https://linux-hardware.org/?probe=03c8e6d135) | Feb 19, 2023 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [422b14d8d7](https://linux-hardware.org/?probe=422b14d8d7) | Feb 19, 2023 |
| Chuwi         | HeroBook Air                | Notebook    | [c669fff700](https://linux-hardware.org/?probe=c669fff700) | Feb 19, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [7432db815e](https://linux-hardware.org/?probe=7432db815e) | Feb 19, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [aaee9da394](https://linux-hardware.org/?probe=aaee9da394) | Feb 19, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [2af589c6e9](https://linux-hardware.org/?probe=2af589c6e9) | Feb 19, 2023 |
| ASRock        | X670E Pro RS                | Desktop     | [906d11e2a3](https://linux-hardware.org/?probe=906d11e2a3) | Feb 19, 2023 |
| GEO           | GeoFlex 340                 | Convertible | [f347582e5c](https://linux-hardware.org/?probe=f347582e5c) | Feb 19, 2023 |
| Samsung       | 930QED                      | Convertible | [f72fed80df](https://linux-hardware.org/?probe=f72fed80df) | Feb 19, 2023 |
| ASUSTek       | ROG Strix G733ZW_G733ZW     | Notebook    | [72f074b930](https://linux-hardware.org/?probe=72f074b930) | Feb 19, 2023 |
| ASUSTek       | ROG Strix G733ZW_G733ZW     | Notebook    | [c6d06c27c7](https://linux-hardware.org/?probe=c6d06c27c7) | Feb 19, 2023 |
| Dell          | Latitude E6430              | Notebook    | [23c0ff9281](https://linux-hardware.org/?probe=23c0ff9281) | Feb 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [b1d168b6ce](https://linux-hardware.org/?probe=b1d168b6ce) | Feb 19, 2023 |
| Dell          | Latitude E6430              | Notebook    | [d97087b55f](https://linux-hardware.org/?probe=d97087b55f) | Feb 19, 2023 |
| Lenovo        | ThinkPad E555 20DH000TUK    | Notebook    | [b2d5c9de8b](https://linux-hardware.org/?probe=b2d5c9de8b) | Feb 19, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [42099690a6](https://linux-hardware.org/?probe=42099690a6) | Feb 19, 2023 |
| Standard      | Unknown                     | Notebook    | [149bdc4e40](https://linux-hardware.org/?probe=149bdc4e40) | Feb 19, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [9b0ecbd3c7](https://linux-hardware.org/?probe=9b0ecbd3c7) | Feb 19, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | Notebook    | [ee24b75c39](https://linux-hardware.org/?probe=ee24b75c39) | Feb 19, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [6eda9f2592](https://linux-hardware.org/?probe=6eda9f2592) | Feb 19, 2023 |
| Dell          | Precision M4500             | Notebook    | [b0d8bf3c56](https://linux-hardware.org/?probe=b0d8bf3c56) | Feb 19, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [5cade7cfc3](https://linux-hardware.org/?probe=5cade7cfc3) | Feb 19, 2023 |
| ASUSTek       | P5Q SE2                     | Desktop     | [37b0d0609f](https://linux-hardware.org/?probe=37b0d0609f) | Feb 18, 2023 |
| Google        | Kled                        | Notebook    | [788d726509](https://linux-hardware.org/?probe=788d726509) | Feb 18, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [9b53b2b842](https://linux-hardware.org/?probe=9b53b2b842) | Feb 18, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [cdfcc639d3](https://linux-hardware.org/?probe=cdfcc639d3) | Feb 18, 2023 |
| Lenovo        | ThinkPad T530 2429F27       | Notebook    | [b835147a32](https://linux-hardware.org/?probe=b835147a32) | Feb 18, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | Notebook    | [fb2cbe3576](https://linux-hardware.org/?probe=fb2cbe3576) | Feb 18, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [a424b3aa47](https://linux-hardware.org/?probe=a424b3aa47) | Feb 18, 2023 |
| ASRock        | H110 Pro BTC+               | Desktop     | [bce117c4dc](https://linux-hardware.org/?probe=bce117c4dc) | Feb 18, 2023 |
| MSI           | Z170A KRAIT GAMING          | Desktop     | [27dcbbe1d7](https://linux-hardware.org/?probe=27dcbbe1d7) | Feb 18, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [831d4806fb](https://linux-hardware.org/?probe=831d4806fb) | Feb 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [e7988c5ab6](https://linux-hardware.org/?probe=e7988c5ab6) | Feb 18, 2023 |
| MSI           | H410M PRO-VH                | Desktop     | [ccc1cbf2fa](https://linux-hardware.org/?probe=ccc1cbf2fa) | Feb 18, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [f14a791491](https://linux-hardware.org/?probe=f14a791491) | Feb 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | Notebook    | [6d2b283e83](https://linux-hardware.org/?probe=6d2b283e83) | Feb 18, 2023 |
| Dell          | Precision 5560              | Notebook    | [24e5de4a3d](https://linux-hardware.org/?probe=24e5de4a3d) | Feb 18, 2023 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | Desktop     | [5fe0f2c1fe](https://linux-hardware.org/?probe=5fe0f2c1fe) | Feb 18, 2023 |
| Samsung       | 730QDA                      | Convertible | [902b86cb84](https://linux-hardware.org/?probe=902b86cb84) | Feb 18, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [c4a1fe4a4f](https://linux-hardware.org/?probe=c4a1fe4a4f) | Feb 17, 2023 |
| Lenovo        | ThinkPad T490 20N2001YUS    | Notebook    | [53ef9ffad8](https://linux-hardware.org/?probe=53ef9ffad8) | Feb 17, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [f9fb638882](https://linux-hardware.org/?probe=f9fb638882) | Feb 17, 2023 |
| Dell          | Latitude 5491               | Notebook    | [8a3298cdff](https://linux-hardware.org/?probe=8a3298cdff) | Feb 17, 2023 |
| ASUSTek       | PRIME Z690M-PLUS D4         | Desktop     | [750c0f6337](https://linux-hardware.org/?probe=750c0f6337) | Feb 17, 2023 |
| Hardkernel    | ODROID-N2                   | Soc         | [9a8138252f](https://linux-hardware.org/?probe=9a8138252f) | Feb 17, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [e4483255db](https://linux-hardware.org/?probe=e4483255db) | Feb 17, 2023 |
| ASRock        | X470 Taichi                 | Desktop     | [71685845fe](https://linux-hardware.org/?probe=71685845fe) | Feb 17, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [8c3926e125](https://linux-hardware.org/?probe=8c3926e125) | Feb 17, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [09aefeb3d6](https://linux-hardware.org/?probe=09aefeb3d6) | Feb 17, 2023 |
| Dell          | Inspiron 5566               | Notebook    | [502adcba49](https://linux-hardware.org/?probe=502adcba49) | Feb 17, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [8e3bad7795](https://linux-hardware.org/?probe=8e3bad7795) | Feb 17, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | Notebook    | [cc44156b99](https://linux-hardware.org/?probe=cc44156b99) | Feb 17, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | Notebook    | [bc234d0b32](https://linux-hardware.org/?probe=bc234d0b32) | Feb 17, 2023 |
| HP            | ENVY Laptop 17-ch2xxx       | Notebook    | [c1abb80cb1](https://linux-hardware.org/?probe=c1abb80cb1) | Feb 17, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [add68ac711](https://linux-hardware.org/?probe=add68ac711) | Feb 16, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [a19a7a2edd](https://linux-hardware.org/?probe=a19a7a2edd) | Feb 16, 2023 |
| Lenovo        | ZIWB2                       | Notebook    | [8ade075157](https://linux-hardware.org/?probe=8ade075157) | Feb 16, 2023 |
| HP            | 245 G8 Notebook PC          | Notebook    | [c48e458030](https://linux-hardware.org/?probe=c48e458030) | Feb 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [4657fc266d](https://linux-hardware.org/?probe=4657fc266d) | Feb 16, 2023 |
| ASUSTek       | EX-H310M-V3 R2.0            | Desktop     | [d42c40dd2e](https://linux-hardware.org/?probe=d42c40dd2e) | Feb 16, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [218e0f7ad6](https://linux-hardware.org/?probe=218e0f7ad6) | Feb 16, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [71778cedf9](https://linux-hardware.org/?probe=71778cedf9) | Feb 16, 2023 |
| Samsung       | 940XFG                      | Notebook    | [56f236f8ab](https://linux-hardware.org/?probe=56f236f8ab) | Feb 16, 2023 |
| Dell          | Latitude 7390 2-in-1        | Convertible | [66dbe64897](https://linux-hardware.org/?probe=66dbe64897) | Feb 16, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [ddc2c7ec7a](https://linux-hardware.org/?probe=ddc2c7ec7a) | Feb 16, 2023 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | Notebook    | [5a3b0950b3](https://linux-hardware.org/?probe=5a3b0950b3) | Feb 16, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [f4e8b0e952](https://linux-hardware.org/?probe=f4e8b0e952) | Feb 16, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [09301690c5](https://linux-hardware.org/?probe=09301690c5) | Feb 15, 2023 |
| ASUSTek       | P8Z77-V PRO/THUNDERBOLT     | Desktop     | [a370fca217](https://linux-hardware.org/?probe=a370fca217) | Feb 15, 2023 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [ca54397755](https://linux-hardware.org/?probe=ca54397755) | Feb 15, 2023 |
| HP            | Notebook                    | Notebook    | [9fe647f9a1](https://linux-hardware.org/?probe=9fe647f9a1) | Feb 15, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [36f57d56f8](https://linux-hardware.org/?probe=36f57d56f8) | Feb 15, 2023 |
| HP            | Notebook                    | Notebook    | [c4516fb37a](https://linux-hardware.org/?probe=c4516fb37a) | Feb 15, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [7fd55795a0](https://linux-hardware.org/?probe=7fd55795a0) | Feb 15, 2023 |
| Lenovo        | ThinkPad P50 20EQS64N09     | Notebook    | [72fad631b7](https://linux-hardware.org/?probe=72fad631b7) | Feb 15, 2023 |
| ASUSTek       | PN53                        | Mini pc     | [73f7fb3f85](https://linux-hardware.org/?probe=73f7fb3f85) | Feb 15, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [70885f1dfd](https://linux-hardware.org/?probe=70885f1dfd) | Feb 15, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [92a9452070](https://linux-hardware.org/?probe=92a9452070) | Feb 15, 2023 |
| MSI           | FM2-A75MA-E35               | Desktop     | [a7f2ca398d](https://linux-hardware.org/?probe=a7f2ca398d) | Feb 15, 2023 |
| Dell          | Inspiron 7375               | Notebook    | [3916d619ed](https://linux-hardware.org/?probe=3916d619ed) | Feb 15, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [1ca19c3d1d](https://linux-hardware.org/?probe=1ca19c3d1d) | Feb 14, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [7d8c3e7e48](https://linux-hardware.org/?probe=7d8c3e7e48) | Feb 14, 2023 |
| ASUSTek       | UL30A                       | Notebook    | [90114a4fe4](https://linux-hardware.org/?probe=90114a4fe4) | Feb 14, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [390686f5f6](https://linux-hardware.org/?probe=390686f5f6) | Feb 14, 2023 |
| HP            | ProBook 440 G7              | Notebook    | [bc4811db07](https://linux-hardware.org/?probe=bc4811db07) | Feb 14, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [cbcadcf80a](https://linux-hardware.org/?probe=cbcadcf80a) | Feb 14, 2023 |
| Dell          | Latitude E7270              | Notebook    | [03199b7612](https://linux-hardware.org/?probe=03199b7612) | Feb 14, 2023 |
| Lenovo        | IdeaPad 520S-14IKB 81BL     | Notebook    | [008d06fbf8](https://linux-hardware.org/?probe=008d06fbf8) | Feb 14, 2023 |
| Timi          | Xiaomi NoteBook Pro         | Notebook    | [561e1a6160](https://linux-hardware.org/?probe=561e1a6160) | Feb 14, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [e718a6af67](https://linux-hardware.org/?probe=e718a6af67) | Feb 14, 2023 |
| Dell          | Latitude 7430               | Notebook    | [82dcb0a8a2](https://linux-hardware.org/?probe=82dcb0a8a2) | Feb 14, 2023 |
| Dell          | G3 3579                     | Notebook    | [35c8b69b8c](https://linux-hardware.org/?probe=35c8b69b8c) | Feb 14, 2023 |
| ASRock        | X370 Gaming X               | Desktop     | [2b9a026876](https://linux-hardware.org/?probe=2b9a026876) | Feb 14, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [2f78b0c253](https://linux-hardware.org/?probe=2f78b0c253) | Feb 14, 2023 |
| HP            | 8714                        | Desktop     | [19a66b5101](https://linux-hardware.org/?probe=19a66b5101) | Feb 14, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [43dff5bee7](https://linux-hardware.org/?probe=43dff5bee7) | Feb 14, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [10c8101c9b](https://linux-hardware.org/?probe=10c8101c9b) | Feb 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [ac71e5b8ef](https://linux-hardware.org/?probe=ac71e5b8ef) | Feb 14, 2023 |
| Dell          | Inspiron 14 5420            | Notebook    | [45862fde09](https://linux-hardware.org/?probe=45862fde09) | Feb 13, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | Notebook    | [1f0e965483](https://linux-hardware.org/?probe=1f0e965483) | Feb 13, 2023 |
| Dell          | Inspiron 14 5420            | Notebook    | [8153aeb3fb](https://linux-hardware.org/?probe=8153aeb3fb) | Feb 13, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [01319ac289](https://linux-hardware.org/?probe=01319ac289) | Feb 13, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [7e81f35584](https://linux-hardware.org/?probe=7e81f35584) | Feb 13, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [f701208fd4](https://linux-hardware.org/?probe=f701208fd4) | Feb 13, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | Notebook    | [3b7765dfcc](https://linux-hardware.org/?probe=3b7765dfcc) | Feb 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [6add161dbe](https://linux-hardware.org/?probe=6add161dbe) | Feb 13, 2023 |
| Dell          | Latitude 5511               | Notebook    | [161095d97a](https://linux-hardware.org/?probe=161095d97a) | Feb 13, 2023 |
| MSI           | X99A SLI PLUS               | Desktop     | [98447ce3dd](https://linux-hardware.org/?probe=98447ce3dd) | Feb 13, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | Notebook    | [7e90fe56d1](https://linux-hardware.org/?probe=7e90fe56d1) | Feb 13, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora_37/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Computers | Percent |
|-------------------------|-----------|---------|
| 6.0.7-301.fc37.x86_64   | 135       | 6.41%   |
| 6.0.15-300.fc37.x86_64  | 131       | 6.22%   |
| 6.0.12-300.fc37.x86_64  | 107       | 5.08%   |
| 6.1.14-200.fc37.x86_64  | 97        | 4.6%    |
| 6.1.18-200.fc37.x86_64  | 88        | 4.18%   |
| 6.0.9-300.fc37.x86_64   | 86        | 4.08%   |
| 6.0.8-300.fc37.x86_64   | 85        | 4.03%   |
| 6.1.7-200.fc37.x86_64   | 79        | 3.75%   |
| 6.0.11-300.fc37.x86_64  | 70        | 3.32%   |
| 6.2.8-200.fc37.x86_64   | 69        | 3.27%   |
| 6.1.8-200.fc37.x86_64   | 69        | 3.27%   |
| 6.1.11-200.fc37.x86_64  | 67        | 3.18%   |
| 6.2.7-200.fc37.x86_64   | 65        | 3.08%   |
| 6.1.9-200.fc37.x86_64   | 64        | 3.04%   |
| 6.1.6-200.fc37.x86_64   | 64        | 3.04%   |
| 6.0.10-300.fc37.x86_64  | 62        | 2.94%   |
| 6.2.9-200.fc37.x86_64   | 56        | 2.66%   |
| 6.1.13-200.fc37.x86_64  | 56        | 2.66%   |
| 6.1.15-200.fc37.x86_64  | 51        | 2.42%   |
| 6.1.10-200.fc37.x86_64  | 49        | 2.33%   |
| 6.0.18-300.fc37.x86_64  | 49        | 2.33%   |
| 6.0.16-300.fc37.x86_64  | 40        | 1.9%    |
| 5.19.16-301.fc37.x86_64 | 39        | 1.85%   |
| 6.1.5-200.fc37.x86_64   | 35        | 1.66%   |
| 6.0.17-300.fc37.x86_64  | 29        | 1.38%   |
| 6.2.10-200.fc37.x86_64  | 28        | 1.33%   |
| 6.0.14-300.fc37.x86_64  | 28        | 1.33%   |
| 6.1.12-200.fc37.x86_64  | 27        | 1.28%   |
| 6.0.13-300.fc37.x86_64  | 22        | 1.04%   |
| 5.19.13-300.fc37.x86_64 | 18        | 0.85%   |
| 5.19.8-300.fc37.x86_64  | 15        | 0.71%   |
| 5.19.9-300.fc37.x86_64  | 14        | 0.66%   |
| 5.19.7-300.fc37.x86_64  | 14        | 0.66%   |
| 6.2.11-200.fc37.x86_64  | 10        | 0.47%   |
| 6.2.12-200.fc37.x86_64  | 9         | 0.43%   |
| 6.0.6-300.fc37.x86_64   | 9         | 0.43%   |
| 5.19.15-301.fc37.x86_64 | 9         | 0.43%   |
| 5.19.14-300.fc37.x86_64 | 8         | 0.38%   |
| 5.19.12-300.fc37.x86_64 | 7         | 0.33%   |
| 5.19.10-300.fc37.x86_64 | 7         | 0.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.0.7   | 137       | 6.5%    |
| 6.0.15  | 134       | 6.36%   |
| 6.0.12  | 109       | 5.17%   |
| 6.1.14  | 100       | 4.75%   |
| 6.0.9   | 93        | 4.41%   |
| 6.1.18  | 91        | 4.32%   |
| 6.0.8   | 89        | 4.22%   |
| 6.1.7   | 79        | 3.75%   |
| 6.1.11  | 72        | 3.42%   |
| 6.1.8   | 71        | 3.37%   |
| 6.0.11  | 71        | 3.37%   |
| 6.2.8   | 70        | 3.32%   |
| 6.2.7   | 67        | 3.18%   |
| 6.1.9   | 65        | 3.08%   |
| 6.0.10  | 65        | 3.08%   |
| 6.1.6   | 64        | 3.04%   |
| 6.2.9   | 57        | 2.71%   |
| 6.1.13  | 56        | 2.66%   |
| 6.1.15  | 51        | 2.42%   |
| 6.1.10  | 51        | 2.42%   |
| 6.0.18  | 49        | 2.33%   |
| 5.19.16 | 47        | 2.23%   |
| 6.0.16  | 42        | 1.99%   |
| 6.1.5   | 36        | 1.71%   |
| 6.2.10  | 30        | 1.42%   |
| 6.1.12  | 30        | 1.42%   |
| 6.0.17  | 30        | 1.42%   |
| 6.0.14  | 28        | 1.33%   |
| 6.0.13  | 23        | 1.09%   |
| 5.19.13 | 19        | 0.9%    |
| 5.19.8  | 16        | 0.76%   |
| 5.19.9  | 14        | 0.66%   |
| 5.19.7  | 14        | 0.66%   |
| 5.19.15 | 11        | 0.52%   |
| 6.2.11  | 10        | 0.47%   |
| 6.2.12  | 9         | 0.43%   |
| 6.1.0   | 9         | 0.43%   |
| 6.0.6   | 9         | 0.43%   |
| 5.19.14 | 9         | 0.43%   |
| 5.19.12 | 9         | 0.43%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.0     | 849       | 42.13%  |
| 6.1     | 739       | 36.67%  |
| 6.2     | 252       | 12.51%  |
| 5.19    | 156       | 7.74%   |
| 5.18    | 5         | 0.25%   |
| 6.3     | 4         | 0.2%    |
| 5.17    | 4         | 0.2%    |
| 5.15    | 2         | 0.1%    |
| 5.8     | 1         | 0.05%   |
| 5.16    | 1         | 0.05%   |
| 5.10    | 1         | 0.05%   |
| 5.0     | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1897      | 99.63%  |
| aarch64 | 7         | 0.37%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| GNOME                        | 1408      | 73.6%   |
| KDE5                         | 323       | 16.88%  |
| Unknown                      | 47        | 2.46%   |
| XFCE                         | 36        | 1.88%   |
| X-Cinnamon                   | 22        | 1.15%   |
| MATE                         | 18        | 0.94%   |
| Cinnamon                     | 14        | 0.73%   |
| i3                           | 12        | 0.63%   |
| sway                         | 6         | 0.31%   |
| LXQt                         | 5         | 0.26%   |
| GNOME Classic                | 5         | 0.26%   |
| LXDE                         | 4         | 0.21%   |
| qtile                        | 2         | 0.1%    |
| KDE                          | 2         | 0.1%    |
| GNOME-Classic                | 2         | 0.1%    |
| bspwm                        | 2         | 0.1%    |
| xmonad                       | 1         | 0.05%   |
| xinit-compat                 | 1         | 0.05%   |
| Phosh:GNOME                  | 1         | 0.05%   |
| custom                       | 1         | 0.05%   |
| ${XDG_CURRENT_DESKTOP:-sway} | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 1395      | 72.47%  |
| X11     | 471       | 24.47%  |
| Tty     | 31        | 1.61%   |
| Unknown | 28        | 1.45%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 974       | 50.73%  |
| GDM     | 669       | 34.84%  |
| SDDM    | 169       | 8.8%    |
| LightDM | 103       | 5.36%   |
| LXDM    | 4         | 0.21%   |
| GREETD  | 1         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1011      | 52.85%  |
| en_GB   | 140       | 7.32%   |
| ru_RU   | 119       | 6.22%   |
| de_DE   | 85        | 4.44%   |
| pt_BR   | 83        | 4.34%   |
| fr_FR   | 55        | 2.88%   |
| it_IT   | 49        | 2.56%   |
| en_CA   | 41        | 2.14%   |
| en_AU   | 41        | 2.14%   |
| es_ES   | 33        | 1.73%   |
| pl_PL   | 29        | 1.52%   |
| en_IN   | 25        | 1.31%   |
| es_MX   | 14        | 0.73%   |
| tr_TR   | 12        | 0.63%   |
| es_CL   | 12        | 0.63%   |
| zh_CN   | 10        | 0.52%   |
| C       | 9         | 0.47%   |
| de_AT   | 8         | 0.42%   |
| cs_CZ   | 8         | 0.42%   |
| Unknown | 8         | 0.42%   |
| es_AR   | 7         | 0.37%   |
| en_IE   | 7         | 0.37%   |
| nl_NL   | 6         | 0.31%   |
| hu_HU   | 6         | 0.31%   |
| en_NZ   | 6         | 0.31%   |
| sv_SE   | 5         | 0.26%   |
| fi_FI   | 5         | 0.26%   |
| en_ZA   | 5         | 0.26%   |
| de_CH   | 5         | 0.26%   |
| zh_TW   | 4         | 0.21%   |
| es_CO   | 4         | 0.21%   |
| en_IL   | 4         | 0.21%   |
| en_DK   | 4         | 0.21%   |
| pt_PT   | 3         | 0.16%   |
| ko_KR   | 3         | 0.16%   |
| es_PE   | 3         | 0.16%   |
| en_PH   | 3         | 0.16%   |
| ca_ES   | 3         | 0.16%   |
| vi_VN   | 2         | 0.1%    |
| nb_NO   | 2         | 0.1%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1587      | 82.87%  |
| BIOS | 328       | 17.13%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 1545      | 80.97%  |
| Ext4    | 313       | 16.4%   |
| Xfs     | 43        | 2.25%   |
| Overlay | 5         | 0.26%   |
| F2fs    | 2         | 0.1%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 933       | 48.64%  |
| GPT     | 923       | 48.12%  |
| MBR     | 62        | 3.23%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1717      | 89.66%  |
| Yes       | 198       | 10.34%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1538      | 80.44%  |
| Yes       | 374       | 19.56%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 379       | 19.91%  |
| ASUSTek Computer    | 341       | 17.91%  |
| Dell                | 235       | 12.34%  |
| Hewlett-Packard     | 229       | 12.03%  |
| MSI                 | 135       | 7.09%   |
| Gigabyte Technology | 97        | 5.09%   |
| Acer                | 88        | 4.62%   |
| ASRock              | 56        | 2.94%   |
| HUAWEI              | 42        | 2.21%   |
| Intel               | 28        | 1.47%   |
| Apple               | 27        | 1.42%   |
| Samsung Electronics | 21        | 1.1%    |
| Toshiba             | 15        | 0.79%   |
| Microsoft           | 15        | 0.79%   |
| Google              | 14        | 0.74%   |
| Timi                | 13        | 0.68%   |
| TUXEDO              | 8         | 0.42%   |
| Fujitsu             | 8         | 0.42%   |
| Unknown             | 8         | 0.42%   |
| Notebook            | 7         | 0.37%   |
| HONOR               | 7         | 0.37%   |
| Alienware           | 6         | 0.32%   |
| System76            | 5         | 0.26%   |
| Pegatron            | 5         | 0.26%   |
| GPD                 | 5         | 0.26%   |
| Framework           | 5         | 0.26%   |
| Schenker            | 4         | 0.21%   |
| Huanan              | 4         | 0.21%   |
| Chuwi               | 4         | 0.21%   |
| AZW                 | 4         | 0.21%   |
| Sony                | 3         | 0.16%   |
| Positivo            | 3         | 0.16%   |
| LG Electronics      | 3         | 0.16%   |
| Itautec             | 3         | 0.16%   |
| Dynabook            | 3         | 0.16%   |
| BESSTAR Tech        | 3         | 0.16%   |
| TECNO               | 2         | 0.11%   |
| Supermicro          | 2         | 0.11%   |
| Standard            | 2         | 0.11%   |
| SLIMBOOK            | 2         | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| ASUS All Series                             | 17        | 0.89%   |
| Unknown                                     | 12        | 0.63%   |
| Dell OptiPlex 7010                          | 7         | 0.37%   |
| ASUS TUF Gaming X570-PLUS                   | 7         | 0.37%   |
| HUAWEI CREM-WXX9                            | 6         | 0.32%   |
| MSI MS-7C37                                 | 5         | 0.26%   |
| Lenovo ThinkPad X1 Carbon Gen 10 21CBCTO1WW | 5         | 0.26%   |
| Lenovo ThinkBook 15 G3 ACL 21A4             | 5         | 0.26%   |
| HP Notebook                                 | 5         | 0.26%   |
| Dell XPS 13 7390                            | 5         | 0.26%   |
| ASUS TUF Gaming B550M-PLUS                  | 5         | 0.26%   |
| MSI MS-7C84                                 | 4         | 0.21%   |
| MSI MS-7C56                                 | 4         | 0.21%   |
| MSI MS-7C02                                 | 4         | 0.21%   |
| MSI MS-7B89                                 | 4         | 0.21%   |
| MSI MS-7A38                                 | 4         | 0.21%   |
| MSI Modern 14 B11MOU                        | 4         | 0.21%   |
| Lenovo IdeaPadFlex 5 14ARE05 81X2           | 4         | 0.21%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5            | 4         | 0.21%   |
| Lenovo IdeaPad 330-15IKB 81DE               | 4         | 0.21%   |
| HUAWEI MACH-WX9                             | 4         | 0.21%   |
| HUAWEI HVY-WXX9                             | 4         | 0.21%   |
| HP OMEN by Laptop 16-c0xxx                  | 4         | 0.21%   |
| HP ENVY x360 Convertible 13-ay0xxx          | 4         | 0.21%   |
| Dell XPS 13 9310                            | 4         | 0.21%   |
| Dell Latitude 5420                          | 4         | 0.21%   |
| Dell Inspiron 5566                          | 4         | 0.21%   |
| ASUS VivoBook_ASUSLaptop X515EA_X515EA      | 4         | 0.21%   |
| ASUS ROG STRIX B450-F GAMING                | 4         | 0.21%   |
| ASUS ProArt Z690-CREATOR WIFI               | 4         | 0.21%   |
| ASUS ProArt X670E-CREATOR WIFI              | 4         | 0.21%   |
| ASUS PRIME B450M-A II                       | 4         | 0.21%   |
| Acer Nitro AN515-54                         | 4         | 0.21%   |
| MSI MS-7C94                                 | 3         | 0.16%   |
| MSI MS-7C91                                 | 3         | 0.16%   |
| MSI MS-7C52                                 | 3         | 0.16%   |
| Microsoft Surface Laptop 3                  | 3         | 0.16%   |
| Microsoft Surface Go 3                      | 3         | 0.16%   |
| Lenovo Yoga 9 14IAP7 82LU                   | 3         | 0.16%   |
| Lenovo Legion 5 15ACH6H 82JU                | 3         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 206       | 10.82%  |
| Dell Latitude      | 67        | 3.52%   |
| Dell Inspiron      | 67        | 3.52%   |
| ASUS ROG           | 65        | 3.41%   |
| Lenovo IdeaPad     | 61        | 3.2%    |
| Acer Aspire        | 47        | 2.47%   |
| ASUS PRIME         | 44        | 2.31%   |
| HP Pavilion        | 43        | 2.26%   |
| ASUS VivoBook      | 41        | 2.15%   |
| Dell XPS           | 38        | 2%      |
| HP EliteBook       | 35        | 1.84%   |
| ASUS TUF           | 35        | 1.84%   |
| Lenovo ThinkBook   | 29        | 1.52%   |
| HP Laptop          | 27        | 1.42%   |
| HP ENVY            | 25        | 1.31%   |
| Lenovo Yoga        | 23        | 1.21%   |
| Dell OptiPlex      | 23        | 1.21%   |
| ASUS ASUS          | 23        | 1.21%   |
| HP ProBook         | 21        | 1.1%    |
| ASUS ZenBook       | 21        | 1.1%    |
| Dell Precision     | 17        | 0.89%   |
| ASUS All           | 17        | 0.89%   |
| Lenovo Legion      | 16        | 0.84%   |
| Acer Nitro         | 16        | 0.84%   |
| Microsoft Surface  | 15        | 0.79%   |
| Toshiba Satellite  | 13        | 0.68%   |
| Lenovo ThinkCentre | 12        | 0.63%   |
| Unknown            | 12        | 0.63%   |
| Dell Vostro        | 11        | 0.58%   |
| HP ZBook           | 10        | 0.53%   |
| MSI Modern         | 9         | 0.47%   |
| HP OMEN            | 9         | 0.47%   |
| ASUS ProArt        | 8         | 0.42%   |
| Gigabyte X570      | 7         | 0.37%   |
| Acer Predator      | 7         | 0.37%   |
| Lenovo IdeaPadFlex | 6         | 0.32%   |
| HUAWEI CREM-WXX9   | 6         | 0.32%   |
| HP Compaq          | 6         | 0.32%   |
| HP 250             | 6         | 0.32%   |
| Gigabyte B550      | 6         | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 306       | 16.07%  |
| 2022    | 278       | 14.6%   |
| 2020    | 277       | 14.55%  |
| 2019    | 217       | 11.4%   |
| 2018    | 189       | 9.93%   |
| 2017    | 134       | 7.04%   |
| 2012    | 80        | 4.2%    |
| 2013    | 77        | 4.04%   |
| 2015    | 73        | 3.83%   |
| 2014    | 72        | 3.78%   |
| 2016    | 64        | 3.36%   |
| 2011    | 43        | 2.26%   |
| 2010    | 33        | 1.73%   |
| 2008    | 20        | 1.05%   |
| 2009    | 15        | 0.79%   |
| 2023    | 11        | 0.58%   |
| 2006    | 6         | 0.32%   |
| 2007    | 5         | 0.26%   |
| Unknown | 4         | 0.21%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1150      | 60.4%   |
| Desktop        | 565       | 29.67%  |
| Convertible    | 107       | 5.62%   |
| Tablet         | 30        | 1.58%   |
| Mini pc        | 27        | 1.42%   |
| All in one     | 12        | 0.63%   |
| Server         | 7         | 0.37%   |
| System on chip | 6         | 0.32%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1477      | 77.01%  |
| Enabled  | 441       | 22.99%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1886      | 99.05%  |
| Yes  | 18        | 0.95%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 487       | 25.47%  |
| 4.01-8.0        | 399       | 20.87%  |
| 8.01-16.0       | 377       | 19.72%  |
| 32.01-64.0      | 323       | 16.89%  |
| 3.01-4.0        | 135       | 7.06%   |
| 64.01-256.0     | 86        | 4.5%    |
| 24.01-32.0      | 72        | 3.77%   |
| 1.01-2.0        | 26        | 1.36%   |
| 2.01-3.0        | 4         | 0.21%   |
| More than 256.0 | 3         | 0.16%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 695       | 34.32%  |
| 3.01-4.0   | 455       | 22.47%  |
| 2.01-3.0   | 452       | 22.32%  |
| 8.01-16.0  | 182       | 8.99%   |
| 1.01-2.0   | 176       | 8.69%   |
| 0.51-1.0   | 30        | 1.48%   |
| 16.01-24.0 | 21        | 1.04%   |
| 24.01-32.0 | 6         | 0.3%    |
| 32.01-64.0 | 5         | 0.25%   |
| 0.01-0.5   | 3         | 0.15%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1164      | 60.59%  |
| 2      | 464       | 24.15%  |
| 3      | 148       | 7.7%    |
| 4      | 71        | 3.7%    |
| 5      | 33        | 1.72%   |
| 6      | 14        | 0.73%   |
| 0      | 11        | 0.57%   |
| 7      | 5         | 0.26%   |
| 9      | 3         | 0.16%   |
| 8      | 3         | 0.16%   |
| 18     | 1         | 0.05%   |
| 17     | 1         | 0.05%   |
| 15     | 1         | 0.05%   |
| 12     | 1         | 0.05%   |
| 10     | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1581      | 82.95%  |
| Yes       | 325       | 17.05%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1414      | 74.15%  |
| No        | 493       | 25.85%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1588      | 83.23%  |
| No        | 320       | 16.77%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1450      | 75.76%  |
| No        | 464       | 24.24%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 338       | 17.67%  |
| Germany      | 154       | 8.05%   |
| Russia       | 139       | 7.27%   |
| Brazil       | 121       | 6.33%   |
| Italy        | 96        | 5.02%   |
| France       | 67        | 3.5%    |
| Poland       | 66        | 3.45%   |
| UK           | 63        | 3.29%   |
| Canada       | 61        | 3.19%   |
| India        | 58        | 3.03%   |
| Spain        | 49        | 2.56%   |
| Australia    | 49        | 2.56%   |
| Netherlands  | 48        | 2.51%   |
| Turkey       | 35        | 1.83%   |
| Austria      | 32        | 1.67%   |
| Sweden       | 29        | 1.52%   |
| Mexico       | 23        | 1.2%    |
| Switzerland  | 21        | 1.1%    |
| Czechia      | 20        | 1.05%   |
| Hungary      | 15        | 0.78%   |
| Portugal     | 14        | 0.73%   |
| Indonesia    | 14        | 0.73%   |
| Belgium      | 14        | 0.73%   |
| Argentina    | 14        | 0.73%   |
| Taiwan       | 13        | 0.68%   |
| Finland      | 13        | 0.68%   |
| Chile        | 13        | 0.68%   |
| Vietnam      | 12        | 0.63%   |
| Romania      | 12        | 0.63%   |
| Norway       | 12        | 0.63%   |
| Israel       | 12        | 0.63%   |
| Thailand     | 11        | 0.58%   |
| Japan        | 10        | 0.52%   |
| Colombia     | 10        | 0.52%   |
| South Africa | 9         | 0.47%   |
| New Zealand  | 9         | 0.47%   |
| Ireland      | 9         | 0.47%   |
| Hong Kong    | 9         | 0.47%   |
| Greece       | 9         | 0.47%   |
| Denmark      | 9         | 0.47%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 39        | 1.98%   |
| Sydney            | 19        | 0.96%   |
| Berlin            | 19        | 0.96%   |
| Vienna            | 17        | 0.86%   |
| St Petersburg     | 16        | 0.81%   |
| Sao Paulo         | 15        | 0.76%   |
| Warsaw            | 14        | 0.71%   |
| Madrid            | 14        | 0.71%   |
| London            | 14        | 0.71%   |
| Istanbul          | 13        | 0.66%   |
| Melbourne         | 11        | 0.56%   |
| Frankfurt am Main | 11        | 0.56%   |
| Milan             | 10        | 0.51%   |
| Wroclaw           | 9         | 0.46%   |
| Delft             | 9         | 0.46%   |
| Budapest          | 9         | 0.46%   |
| Bengaluru         | 9         | 0.46%   |
| Amsterdam         | 9         | 0.46%   |
| Prague            | 8         | 0.41%   |
| Paris             | 8         | 0.41%   |
| Montreal          | 8         | 0.41%   |
| Helsinki          | 8         | 0.41%   |
| Zurich            | 7         | 0.36%   |
| Porto Alegre      | 7         | 0.36%   |
| Palmas            | 7         | 0.36%   |
| New York          | 7         | 0.36%   |
| New Taipei        | 7         | 0.36%   |
| Munich            | 7         | 0.36%   |
| Milano            | 7         | 0.36%   |
| Ho Chi Minh City  | 7         | 0.36%   |
| Bangkok           | 7         | 0.36%   |
| Yekaterinburg     | 6         | 0.3%    |
| Seattle           | 6         | 0.3%    |
| Riga              | 6         | 0.3%    |
| Portland          | 6         | 0.3%    |
| Novosibirsk       | 6         | 0.3%    |
| Jakarta           | 6         | 0.3%    |
| Izmir             | 6         | 0.3%    |
| Chennai           | 6         | 0.3%    |
| Central           | 6         | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 619       | 839    | 22.04%  |
| WDC                         | 316       | 473    | 11.25%  |
| Seagate                     | 245       | 320    | 8.73%   |
| Sandisk                     | 206       | 254    | 7.34%   |
| Kingston                    | 162       | 195    | 5.77%   |
| Toshiba                     | 136       | 162    | 4.84%   |
| SK hynix                    | 131       | 143    | 4.67%   |
| Crucial                     | 121       | 149    | 4.31%   |
| Unknown                     | 96        | 118    | 3.42%   |
| Intel                       | 94        | 116    | 3.35%   |
| Micron Technology           | 82        | 96     | 2.92%   |
| KIOXIA                      | 52        | 62     | 1.85%   |
| Phison Electronics          | 40        | 47     | 1.42%   |
| HGST                        | 36        | 52     | 1.28%   |
| A-DATA Technology           | 30        | 31     | 1.07%   |
| Micron/Crucial Technology   | 27        | 31     | 0.96%   |
| Hitachi                     | 26        | 33     | 0.93%   |
| China                       | 23        | 30     | 0.82%   |
| Kingston Technology Company | 16        | 17     | 0.57%   |
| Apple                       | 16        | 25     | 0.57%   |
| ADATA Technology            | 15        | 17     | 0.53%   |
| PNY                         | 14        | 16     | 0.5%    |
| Silicon Motion              | 13        | 14     | 0.46%   |
| LITEON                      | 13        | 13     | 0.46%   |
| SPCC                        | 12        | 15     | 0.43%   |
| Phison                      | 12        | 12     | 0.43%   |
| Corsair                     | 12        | 16     | 0.43%   |
| Realtek Semiconductor       | 11        | 11     | 0.39%   |
| Apacer                      | 11        | 16     | 0.39%   |
| Netac                       | 10        | 14     | 0.36%   |
| Unknown                     | 10        | 12     | 0.36%   |
| JMicron Technology          | 8         | 11     | 0.28%   |
| UMIS                        | 7         | 7      | 0.25%   |
| Intenso                     | 7         | 8      | 0.25%   |
| Transcend                   | 6         | 6      | 0.21%   |
| Lexar                       | 6         | 7      | 0.21%   |
| Gigabyte Technology         | 6         | 7      | 0.21%   |
| Patriot                     | 5         | 5      | 0.18%   |
| Lite-On Technology          | 5         | 5      | 0.18%   |
| Lenovo                      | 5         | 5      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB   | 107       | 3.5%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 51        | 1.67%   |
| Kingston SA400S37240G 240GB SSD                     | 32        | 1.05%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB    | 25        | 0.82%   |
| Crucial CT1000MX500SSD1 1TB                         | 23        | 0.75%   |
| Seagate ST2000DM008-2FR102 2TB                      | 22        | 0.72%   |
| Samsung SSD 850 EVO 250GB                           | 21        | 0.69%   |
| Toshiba MQ04ABF100 1TB                              | 20        | 0.65%   |
| Seagate ST1000LM035-1RK172 970GB                    | 20        | 0.65%   |
| Kingston SA400S37480G 480GB SSD                     | 20        | 0.65%   |
| Samsung SSD 860 EVO 500GB                           | 19        | 0.62%   |
| Kingston SA400S37120G 120GB SSD                     | 19        | 0.62%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                 | 18        | 0.59%   |
| Sandisk WD Blue SN550 NVMe SSD 1024GB               | 17        | 0.56%   |
| Samsung SSD 870 EVO 500GB                           | 17        | 0.56%   |
| Intel SSDPEKNU512GZ 512GB                           | 17        | 0.56%   |
| Intel SSD 660P Series 512GB                         | 16        | 0.52%   |
| Crucial CT240BX500SSD1 240GB                        | 16        | 0.52%   |
| Unknown MMC Card  32GB                              | 15        | 0.49%   |
| Samsung SSD 980 PRO 1TB                             | 15        | 0.49%   |
| Samsung SSD 860 EVO 250GB                           | 15        | 0.49%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 500GB | 15        | 0.49%   |
| Phison E12 NVMe Controller 512GB                    | 15        | 0.49%   |
| Seagate ST500DM002-1BD142 500GB                     | 14        | 0.46%   |
| Seagate ST1000DM010-2EP102 1TB                      | 14        | 0.46%   |
| Samsung SSD 970 EVO Plus 500GB                      | 14        | 0.46%   |
| Samsung SSD 850 EVO 500GB                           | 14        | 0.46%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 512GB     | 13        | 0.43%   |
| Samsung SSD 980 1TB                                 | 13        | 0.43%   |
| Unknown MMC Card  64GB                              | 12        | 0.39%   |
| Unknown MMC Card  128GB                             | 12        | 0.39%   |
| Samsung SSD 870 EVO 1TB                             | 12        | 0.39%   |
| Samsung SSD 860 EVO 1TB                             | 12        | 0.39%   |
| HGST HTS721010A9E630 1TB                            | 12        | 0.39%   |
| Crucial CT500MX500SSD1 500GB                        | 12        | 0.39%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 11        | 0.36%   |
| Samsung SSD 970 EVO Plus 2TB                        | 11        | 0.36%   |
| Phison PS5013 E13 NVMe Controller 500GB             | 11        | 0.36%   |
| Phison E16 PCIe4 NVMe Controller 500GB              | 11        | 0.36%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 10        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 241       | 314    | 38.13%  |
| WDC                 | 202       | 321    | 31.96%  |
| Toshiba             | 92        | 106    | 14.56%  |
| HGST                | 36        | 52     | 5.7%    |
| Hitachi             | 26        | 33     | 4.11%   |
| Samsung Electronics | 13        | 18     | 2.06%   |
| Unknown             | 6         | 8      | 0.95%   |
| JMicron Technology  | 3         | 6      | 0.47%   |
| Maxtor              | 2         | 2      | 0.32%   |
| Intenso             | 2         | 2      | 0.32%   |
| USB3.0              | 1         | 1      | 0.16%   |
| Inateck             | 1         | 4      | 0.16%   |
| IET                 | 1         | 1      | 0.16%   |
| HGST HTS            | 1         | 1      | 0.16%   |
| Hewlett-Packard     | 1         | 12     | 0.16%   |
| Fujitsu             | 1         | 1      | 0.16%   |
| External            | 1         | 1      | 0.16%   |
| ASMT                | 1         | 2      | 0.16%   |
| Apple               | 1         | 1      | 0.16%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 201       | 269    | 25.03%  |
| Kingston            | 111       | 129    | 13.82%  |
| Crucial             | 105       | 129    | 13.08%  |
| SanDisk             | 65        | 71     | 8.09%   |
| WDC                 | 55        | 66     | 6.85%   |
| China               | 23        | 30     | 2.86%   |
| SK hynix            | 19        | 19     | 2.37%   |
| A-DATA Technology   | 17        | 17     | 2.12%   |
| Micron Technology   | 15        | 17     | 1.87%   |
| Intel               | 15        | 18     | 1.87%   |
| PNY                 | 13        | 15     | 1.62%   |
| Toshiba             | 12        | 14     | 1.49%   |
| LITEON              | 11        | 11     | 1.37%   |
| Apple               | 10        | 11     | 1.25%   |
| Apacer              | 9         | 13     | 1.12%   |
| Corsair             | 8         | 10     | 1%      |
| SPCC                | 7         | 9      | 0.87%   |
| Netac               | 7         | 10     | 0.87%   |
| Patriot             | 5         | 5      | 0.62%   |
| Lexar               | 5         | 6      | 0.62%   |
| Intenso             | 5         | 5      | 0.62%   |
| Gigabyte Technology | 5         | 6      | 0.62%   |
| Transcend           | 4         | 4      | 0.5%    |
| KingSpec            | 4         | 5      | 0.5%    |
| GOODRAM             | 4         | 8      | 0.5%    |
| Team                | 3         | 4      | 0.37%   |
| Plextor             | 3         | 3      | 0.37%   |
| Mushkin             | 3         | 3      | 0.37%   |
| LITEONIT            | 3         | 3      | 0.37%   |
| ASMT                | 3         | 3      | 0.37%   |
| Unknown             | 2         | 2      | 0.25%   |
| Teclast             | 2         | 3      | 0.25%   |
| OCZ                 | 2         | 2      | 0.25%   |
| LT                  | 2         | 2      | 0.25%   |
| KIOXIA-EXCERIA      | 2         | 2      | 0.25%   |
| KingFast            | 2         | 2      | 0.25%   |
| KingDian            | 2         | 2      | 0.25%   |
| HS-SSD-C100         | 2         | 2      | 0.25%   |
| FORESEE             | 2         | 2      | 0.25%   |
| Unknown             | 2         | 2      | 0.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 1206      | 1579   | 47%     |
| SSD     | 704       | 971    | 27.44%  |
| HDD     | 527       | 886    | 20.54%  |
| MMC     | 90        | 106    | 3.51%   |
| Unknown | 39        | 45     | 1.52%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 1201      | 1569   | 51.24%  |
| SATA | 958       | 1787   | 40.87%  |
| SAS  | 95        | 125    | 4.05%   |
| MMC  | 90        | 106    | 3.84%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 659       | 916    | 50.42%  |
| 0.51-1.0   | 408       | 565    | 31.22%  |
| 1.01-2.0   | 133       | 176    | 10.18%  |
| 3.01-4.0   | 46        | 71     | 3.52%   |
| 4.01-10.0  | 30        | 53     | 2.3%    |
| 2.01-3.0   | 26        | 52     | 1.99%   |
| 10.01-20.0 | 5         | 24     | 0.38%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 410       | 21.22%  |
| 251-500        | 355       | 18.37%  |
| 1001-2000      | 288       | 14.91%  |
| 101-250        | 219       | 11.34%  |
| 1-20           | 209       | 10.82%  |
| Unknown        | 155       | 8.02%   |
| More than 3000 | 134       | 6.94%   |
| 2001-3000      | 82        | 4.24%   |
| 51-100         | 48        | 2.48%   |
| 21-50          | 32        | 1.66%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 521       | 26.25%  |
| 21-50          | 303       | 15.26%  |
| 101-250        | 268       | 13.5%   |
| 51-100         | 221       | 11.13%  |
| 251-500        | 193       | 9.72%   |
| 501-1000       | 178       | 8.97%   |
| Unknown        | 155       | 7.81%   |
| 1001-2000      | 86        | 4.33%   |
| More than 3000 | 33        | 1.66%   |
| 2001-3000      | 27        | 1.36%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 870 EVO 1TB   | 4         | 4      | 3.05%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD      | 2         | 2      | 1.53%   |
| WDC WD5000AAKX-603CA0 500GB           | 2         | 2      | 1.53%   |
| WDC WD10EZEX-00BN5A0 1TB              | 2         | 2      | 1.53%   |
| Seagate ST500LT012-1DG142 500GB       | 2         | 2      | 1.53%   |
| Seagate ST500DM002-1BD142 500GB       | 2         | 2      | 1.53%   |
| Seagate ST3500418AS 500GB             | 2         | 2      | 1.53%   |
| Seagate ST31000524AS 1TB              | 2         | 2      | 1.53%   |
| Samsung Electronics SSD 980 1TB       | 2         | 2      | 1.53%   |
| Samsung Electronics SSD 870 EVO 500GB | 2         | 3      | 1.53%   |
| Intel SSDSC2CT120A3 120GB             | 2         | 5      | 1.53%   |
| HGST HTS721010A9E630 1TB              | 2         | 2      | 1.53%   |
| Crucial CT275MX300SSD1 275GB          | 2         | 2      | 1.53%   |
| WDC WDS480G2G0A-00JH30 480GB SSD      | 1         | 1      | 0.76%   |
| WDC WD50EFRX-68MYMN1 5TB              | 1         | 4      | 0.76%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 1         | 1      | 0.76%   |
| WDC WD5000AVVS-63H0B1 500GB           | 1         | 1      | 0.76%   |
| WDC WD5000AAKX-60U6AA0 500GB          | 1         | 1      | 0.76%   |
| WDC WD5000AAKX-00ERMA0 500GB          | 1         | 1      | 0.76%   |
| WDC WD40PURZ-85AKKY0 4TB              | 1         | 1      | 0.76%   |
| WDC WD40EZRZ-00WN9B0 4TB              | 1         | 1      | 0.76%   |
| WDC WD3200BPVT-80JJ5T0 320GB          | 1         | 1      | 0.76%   |
| WDC WD3200AAKS-00V1A0 320GB           | 1         | 1      | 0.76%   |
| WDC WD3200AAKS-00UU3A0 320GB          | 1         | 1      | 0.76%   |
| WDC WD30EFRX-68AX9N0 3TB              | 1         | 1      | 0.76%   |
| WDC WD2500BEVT-80A23T0 250GB          | 1         | 1      | 0.76%   |
| WDC WD2500AAKX-753CA1 250GB           | 1         | 1      | 0.76%   |
| WDC WD20EZRX-22D8PB0 2TB              | 1         | 1      | 0.76%   |
| WDC WD20EZRX-00D8PB0 2TB              | 1         | 1      | 0.76%   |
| WDC WD15EARS-00MVWB0 1TB              | 1         | 1      | 0.76%   |
| WDC WD140EDFZ-11A0VA0 14TB            | 1         | 2      | 0.76%   |
| WDC WD10JPVX-60JC3T1 1TB              | 1         | 1      | 0.76%   |
| WDC WD10EZEX-60WN4A0 1TB              | 1         | 2      | 0.76%   |
| WDC WD10EZEX-08WN4A0 1TB              | 1         | 1      | 0.76%   |
| WDC WD10EZEX-00WN4A0 1TB              | 1         | 1      | 0.76%   |
| WDC WD10EFRX-68FYTN0 1TB              | 1         | 1      | 0.76%   |
| WDC WD10EADS-00L5B1 1TB               | 1         | 1      | 0.76%   |
| WDC WD1002FAEX-00Y9A0 1TB             | 1         | 1      | 0.76%   |
| Toshiba MQ01ABD075 752GB              | 1         | 1      | 0.76%   |
| Toshiba MQ01ABD050 500GB              | 1         | 1      | 0.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 35        | 46     | 28%     |
| WDC                 | 29        | 36     | 23.2%   |
| Samsung Electronics | 15        | 22     | 12%     |
| Toshiba             | 8         | 8      | 6.4%    |
| Crucial             | 6         | 6      | 4.8%    |
| SK hynix            | 5         | 5      | 4%      |
| HGST                | 4         | 4      | 3.2%    |
| SanDisk             | 3         | 3      | 2.4%    |
| Micron Technology   | 3         | 3      | 2.4%    |
| Kingston            | 3         | 3      | 2.4%    |
| Intel               | 3         | 6      | 2.4%    |
| Hitachi             | 2         | 2      | 1.6%    |
| Corsair             | 2         | 2      | 1.6%    |
| SPCC                | 1         | 1      | 0.8%    |
| Maxtor              | 1         | 1      | 0.8%    |
| HGST HTS            | 1         | 1      | 0.8%    |
| Apple               | 1         | 1      | 0.8%    |
| AMD                 | 1         | 2      | 0.8%    |
| A-DATA Technology   | 1         | 1      | 0.8%    |
| Unknown             | 1         | 1      | 0.8%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 35        | 46     | 42.68%  |
| WDC                 | 26        | 33     | 31.71%  |
| Toshiba             | 7         | 7      | 8.54%   |
| Samsung Electronics | 6         | 11     | 7.32%   |
| HGST                | 4         | 4      | 4.88%   |
| Hitachi             | 2         | 2      | 2.44%   |
| Maxtor              | 1         | 1      | 1.22%   |
| HGST HTS            | 1         | 1      | 1.22%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 76        | 105    | 63.87%  |
| SSD  | 36        | 42     | 30.25%  |
| NVMe | 7         | 7      | 5.88%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| SPCC M.2 PCIe SSD 2TB                            | 1         | 1      | 25%     |
| Seagate ST31000528AS 1TB                         | 1         | 2      | 25%     |
| Samsung Electronics SSD 980 1TB                  | 1         | 1      | 25%     |
| Samsung Electronics MZNTY128HDHP-00000 128GB SSD | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 2      | 50%     |
| SPCC                | 1         | 1      | 25%     |
| Seagate             | 1         | 2      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1088      | 2006   | 52.64%  |
| Works    | 862       | 1422   | 41.7%   |
| Malfunc  | 113       | 154    | 5.47%   |
| Failed   | 4         | 5      | 0.19%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 989       | 36.82%  |
| Samsung Electronics            | 449       | 16.72%  |
| AMD                            | 393       | 14.63%  |
| SanDisk                        | 214       | 7.97%   |
| SK hynix                       | 112       | 4.17%   |
| Kingston Technology Company    | 72        | 2.68%   |
| Micron Technology              | 68        | 2.53%   |
| Phison Electronics             | 61        | 2.27%   |
| KIOXIA                         | 47        | 1.75%   |
| Micron/Crucial Technology      | 41        | 1.53%   |
| Toshiba America Info Systems   | 40        | 1.49%   |
| ASMedia Technology             | 39        | 1.45%   |
| ADATA Technology               | 28        | 1.04%   |
| Silicon Motion                 | 19        | 0.71%   |
| Marvell Technology Group       | 18        | 0.67%   |
| Realtek Semiconductor          | 14        | 0.52%   |
| Union Memory (Shenzhen)        | 10        | 0.37%   |
| MAXIO Technology (Hangzhou)    | 8         | 0.3%    |
| Shenzhen Longsys Electronics   | 7         | 0.26%   |
| Lite-On Technology             | 7         | 0.26%   |
| Solid State Storage Technology | 6         | 0.22%   |
| Nvidia                         | 6         | 0.22%   |
| JMicron Technology             | 6         | 0.22%   |
| Yangtze Memory Technologies    | 4         | 0.15%   |
| Lenovo                         | 4         | 0.15%   |
| Broadcom / LSI                 | 4         | 0.15%   |
| LSI Logic / Symbios Logic      | 3         | 0.11%   |
| Biwin Storage Technology       | 3         | 0.11%   |
| Apple                          | 3         | 0.11%   |
| VIA Technologies               | 2         | 0.07%   |
| Netac Technology               | 2         | 0.07%   |
| ULi Electronics                | 1         | 0.04%   |
| Transcend                      | 1         | 0.04%   |
| Solidigm                       | 1         | 0.04%   |
| Silicon Image                  | 1         | 0.04%   |
| Seagate Technology             | 1         | 0.04%   |
| Hewlett-Packard                | 1         | 0.04%   |
| Adaptec                        | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 286       | 9.78%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 193       | 6.6%    |
| Intel Volume Management Device NVMe RAID Controller                            | 119       | 4.07%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 112       | 3.83%   |
| Samsung NVMe SSD Controller 980                                                | 106       | 3.62%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 106       | 3.62%   |
| Micron NVMe Storage Controller                                                 | 66        | 2.26%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 63        | 2.15%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 60        | 2.05%   |
| AMD 400 Series Chipset SATA Controller                                         | 57        | 1.95%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 53        | 1.81%   |
| AMD 500 Series Chipset SATA Controller                                         | 53        | 1.81%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 45        | 1.54%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 45        | 1.54%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 41        | 1.4%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 39        | 1.33%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 37        | 1.26%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 34        | 1.16%   |
| Intel Tiger Lake-LP SATA Controller                                            | 33        | 1.13%   |
| Kingston Company Company Non-Volatile memory controller                        | 32        | 1.09%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 32        | 1.09%   |
| Intel Comet Lake SATA AHCI Controller                                          | 31        | 1.06%   |
| SanDisk Non-Volatile memory controller                                         | 30        | 1.03%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 30        | 1.03%   |
| Intel Non-Volatile memory controller                                           | 28        | 0.96%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 28        | 0.96%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 27        | 0.92%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 27        | 0.92%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 27        | 0.92%   |
| Phison E12 NVMe Controller                                                     | 26        | 0.89%   |
| Intel SSD 660P Series                                                          | 25        | 0.85%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 24        | 0.82%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 24        | 0.82%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 24        | 0.82%   |
| Intel SATA Controller [RAID mode]                                              | 22        | 0.75%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 22        | 0.75%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 21        | 0.72%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 21        | 0.72%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 20        | 0.68%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 20        | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 1194      | 45.01%  |
| SATA | 1154      | 43.5%   |
| RAID | 218       | 8.22%   |
| IDE  | 75        | 2.83%   |
| SAS  | 10        | 0.38%   |
| SCSI | 2         | 0.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 1303      | 68.43%  |
| AMD     | 594       | 31.2%   |
| ARM     | 6         | 0.32%   |
| Unknown | 1         | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 53        | 2.78%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 34        | 1.79%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 25        | 1.31%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 24        | 1.26%   |
| AMD Ryzen 5 3600 6-Core Processor             | 24        | 1.26%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 23        | 1.21%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 23        | 1.21%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 23        | 1.21%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 22        | 1.16%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 22        | 1.16%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 21        | 1.1%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 20        | 1.05%   |
| Intel 12th Gen Core i7-12700H                 | 20        | 1.05%   |
| Intel 12th Gen Core i7-1260P                  | 20        | 1.05%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 19        | 1%      |
| AMD Ryzen 5 5600G with Radeon Graphics        | 18        | 0.95%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 17        | 0.89%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 16        | 0.84%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 16        | 0.84%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 15        | 0.79%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 15        | 0.79%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 14        | 0.74%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 14        | 0.74%   |
| Intel 12th Gen Core i7-1255U                  | 14        | 0.74%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 13        | 0.68%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 13        | 0.68%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 13        | 0.68%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 12        | 0.63%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 12        | 0.63%   |
| Intel 12th Gen Core i5-1235U                  | 12        | 0.63%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 12        | 0.63%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 12        | 0.63%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 12        | 0.63%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 12        | 0.63%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 12        | 0.63%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 12        | 0.63%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 12        | 0.63%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 12        | 0.63%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 11        | 0.58%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 11        | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 359       | 18.86%  |
| Intel Core i5           | 351       | 18.43%  |
| Other                   | 333       | 17.49%  |
| AMD Ryzen 5             | 205       | 10.77%  |
| AMD Ryzen 7             | 172       | 9.03%   |
| Intel Core i3           | 88        | 4.62%   |
| AMD Ryzen 9             | 74        | 3.89%   |
| Intel Celeron           | 40        | 2.1%    |
| Intel Xeon              | 36        | 1.89%   |
| AMD Ryzen 7 PRO         | 29        | 1.52%   |
| Intel Atom              | 24        | 1.26%   |
| AMD Ryzen 3             | 23        | 1.21%   |
| Intel Core 2 Duo        | 19        | 1%      |
| Intel Pentium           | 18        | 0.95%   |
| AMD Ryzen 5 PRO         | 18        | 0.95%   |
| Intel Core i9           | 12        | 0.63%   |
| AMD FX                  | 12        | 0.63%   |
| AMD A6                  | 10        | 0.53%   |
| AMD A4                  | 8         | 0.42%   |
| AMD A10                 | 8         | 0.42%   |
| Intel Core 2 Quad       | 7         | 0.37%   |
| Intel Pentium Dual-Core | 6         | 0.32%   |
| AMD A8                  | 6         | 0.32%   |
| Intel Pentium Silver    | 4         | 0.21%   |
| AMD Ryzen Threadripper  | 4         | 0.21%   |
| AMD A12                 | 4         | 0.21%   |
| Intel Core m3           | 3         | 0.16%   |
| AMD Phenom II X6        | 3         | 0.16%   |
| Intel Pentium Gold      | 2         | 0.11%   |
| Intel Pentium Dual      | 2         | 0.11%   |
| Intel Genuine           | 2         | 0.11%   |
| Intel Core 2            | 2         | 0.11%   |
| AMD PRO A10             | 2         | 0.11%   |
| AMD Phenom II X4        | 2         | 0.11%   |
| AMD Phenom II X2        | 2         | 0.11%   |
| AMD Athlon 64 X2        | 2         | 0.11%   |
| Intel Xeon Silver       | 1         | 0.05%   |
| Intel Xeon Platinum     | 1         | 0.05%   |
| Intel Core m7           | 1         | 0.05%   |
| Intel Core m5           | 1         | 0.05%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 675       | 35.45%  |
| 2       | 416       | 21.85%  |
| 6       | 304       | 15.97%  |
| 8       | 284       | 14.92%  |
| 12      | 85        | 4.46%   |
| 10      | 41        | 2.15%   |
| 14      | 39        | 2.05%   |
| 16      | 38        | 2%      |
| 24      | 5         | 0.26%   |
| 3       | 5         | 0.26%   |
| 1       | 5         | 0.26%   |
| Unknown | 2         | 0.11%   |
| 96      | 1         | 0.05%   |
| 36      | 1         | 0.05%   |
| 32      | 1         | 0.05%   |
| 20      | 1         | 0.05%   |
| 5       | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1888      | 99.16%  |
| 2       | 14        | 0.74%   |
| Unknown | 2         | 0.11%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1615      | 84.78%  |
| 1       | 288       | 15.12%  |
| Unknown | 2         | 0.1%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1899      | 99.74%  |
| 64-bit         | 5         | 0.26%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 263       | 13.57%  |
| 0x806c1    | 106       | 5.47%   |
| 0x0a50000c | 84        | 4.33%   |
| 0x806ec    | 75        | 3.87%   |
| 0x306a9    | 75        | 3.87%   |
| 0x806ea    | 73        | 3.77%   |
| 0x906a3    | 71        | 3.66%   |
| 0x906ea    | 61        | 3.15%   |
| 0x08701021 | 51        | 2.63%   |
| 0x306c3    | 48        | 2.48%   |
| 0x806e9    | 45        | 2.32%   |
| 0x506e3    | 43        | 2.22%   |
| 0x406e3    | 43        | 2.22%   |
| 0x08600106 | 41        | 2.12%   |
| 0x206a7    | 37        | 1.91%   |
| 0x08608103 | 37        | 1.91%   |
| 0x0a50000d | 34        | 1.75%   |
| 0xa0652    | 31        | 1.6%    |
| 0x306d4    | 29        | 1.5%    |
| 0x906e9    | 28        | 1.44%   |
| 0x08108109 | 28        | 1.44%   |
| 0x906a4    | 27        | 1.39%   |
| 0x0a404102 | 27        | 1.39%   |
| 0x806d1    | 24        | 1.24%   |
| 0x90672    | 22        | 1.14%   |
| 0x706e5    | 21        | 1.08%   |
| 0x40651    | 20        | 1.03%   |
| 0x0a601203 | 19        | 0.98%   |
| 0x1067a    | 18        | 0.93%   |
| 0x0a201016 | 18        | 0.93%   |
| 0x806eb    | 17        | 0.88%   |
| 0x0a20120a | 17        | 0.88%   |
| 0x906ed    | 16        | 0.83%   |
| 0x08600104 | 16        | 0.83%   |
| 0x30678    | 15        | 0.77%   |
| 0x0a404101 | 14        | 0.72%   |
| 0x806c2    | 13        | 0.67%   |
| 0x706a8    | 13        | 0.67%   |
| 0x0810100b | 13        | 0.67%   |
| 0x08701013 | 12        | 0.62%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 382       | 20.06%  |
| Zen 3            | 188       | 9.87%   |
| Alderlake Hybrid | 150       | 7.88%   |
| Zen 2            | 136       | 7.14%   |
| Unknown          | 136       | 7.14%   |
| TigerLake        | 134       | 7.04%   |
| Skylake          | 103       | 5.41%   |
| IvyBridge        | 92        | 4.83%   |
| Haswell          | 91        | 4.78%   |
| CometLake        | 60        | 3.15%   |
| SandyBridge      | 57        | 2.99%   |
| Icelake          | 57        | 2.99%   |
| Zen+             | 49        | 2.57%   |
| Silvermont       | 38        | 2%      |
| Zen              | 36        | 1.89%   |
| Broadwell        | 34        | 1.79%   |
| Penryn           | 26        | 1.37%   |
| Excavator        | 18        | 0.95%   |
| Piledriver       | 17        | 0.89%   |
| Westmere         | 16        | 0.84%   |
| Goldmont plus    | 15        | 0.79%   |
| Core             | 13        | 0.68%   |
| K10              | 9         | 0.47%   |
| Tremont          | 7         | 0.37%   |
| Nehalem          | 7         | 0.37%   |
| Steamroller      | 6         | 0.32%   |
| Goldmont         | 6         | 0.32%   |
| Bonnell          | 5         | 0.26%   |
| Jaguar           | 4         | 0.21%   |
| Puma             | 3         | 0.16%   |
| Bulldozer        | 3         | 0.16%   |
| K8 Hammer        | 2         | 0.11%   |
| K10 Llano        | 2         | 0.11%   |
| K8 & K10 hybrid  | 1         | 0.05%   |
| Bobcat           | 1         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 1063      | 45.72%  |
| Nvidia                     | 630       | 27.1%   |
| AMD                        | 625       | 26.88%  |
| ASPEED Technology          | 6         | 0.26%   |
| Matrox Electronics Systems | 1         | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 116       | 4.86%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 101       | 4.23%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 80        | 3.35%   |
| Intel UHD Graphics 620                                                                   | 74        | 3.1%    |
| AMD Renoir                                                                               | 67        | 2.81%   |
| Intel HD Graphics 620                                                                    | 54        | 2.26%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 53        | 2.22%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 53        | 2.22%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 50        | 2.1%    |
| AMD Lucienne                                                                             | 48        | 2.01%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 47        | 1.97%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 47        | 1.97%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 44        | 1.84%   |
| AMD Rembrandt [Radeon 680M]                                                              | 44        | 1.84%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 35        | 1.47%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 34        | 1.42%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 33        | 1.38%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 31        | 1.3%    |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 30        | 1.26%   |
| Intel HD Graphics 5500                                                                   | 28        | 1.17%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 28        | 1.17%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                            | 28        | 1.17%   |
| Intel HD Graphics 630                                                                    | 26        | 1.09%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 24        | 1.01%   |
| Intel HD Graphics 530                                                                    | 24        | 1.01%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 24        | 1.01%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 23        | 0.96%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 23        | 0.96%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 23        | 0.96%   |
| AMD Raphael                                                                              | 23        | 0.96%   |
| AMD Barcelo                                                                              | 23        | 0.96%   |
| Nvidia GP108M [GeForce MX150]                                                            | 17        | 0.71%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 17        | 0.71%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 16        | 0.67%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 15        | 0.63%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 15        | 0.63%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 14        | 0.59%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 14        | 0.59%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 14        | 0.59%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 13        | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 704       | 36.94%  |
| 1 x AMD                  | 480       | 25.18%  |
| Intel + Nvidia           | 306       | 16.05%  |
| 1 x Nvidia               | 247       | 12.96%  |
| AMD + Nvidia             | 68        | 3.57%   |
| 2 x AMD                  | 43        | 2.26%   |
| Intel + AMD              | 31        | 1.63%   |
| 2 x Intel                | 8         | 0.42%   |
| Other                    | 7         | 0.37%   |
| 1 x ASPEED               | 3         | 0.16%   |
| 2 x Nvidia               | 2         | 0.1%    |
| 3 x AMD                  | 1         | 0.05%   |
| 2 x Nvidia + 1 x ASPEED  | 1         | 0.05%   |
| Nvidia + ASPEED          | 1         | 0.05%   |
| 1 x Matrox               | 1         | 0.05%   |
| Intel + 2 x Nvidia       | 1         | 0.05%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.05%   |
| AMD + ASPEED             | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1515      | 79.07%  |
| Proprietary | 346       | 18.06%  |
| Unknown     | 55        | 2.87%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1007      | 52.2%   |
| 0.01-0.5   | 222       | 11.51%  |
| 1.01-2.0   | 185       | 9.59%   |
| 3.01-4.0   | 142       | 7.36%   |
| 7.01-8.0   | 141       | 7.31%   |
| 0.51-1.0   | 107       | 5.55%   |
| 8.01-16.0  | 56        | 2.9%    |
| 5.01-6.0   | 51        | 2.64%   |
| 2.01-3.0   | 11        | 0.57%   |
| 16.01-24.0 | 7         | 0.36%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 272       | 12.25%  |
| BOE                     | 271       | 12.21%  |
| Chimei Innolux          | 226       | 10.18%  |
| Samsung Electronics     | 202       | 9.1%    |
| LG Display              | 172       | 7.75%   |
| Dell                    | 157       | 7.07%   |
| Goldstar                | 120       | 5.41%   |
| Hewlett-Packard         | 71        | 3.2%    |
| AOC                     | 66        | 2.97%   |
| Sharp                   | 62        | 2.79%   |
| Acer                    | 60        | 2.7%    |
| BenQ                    | 48        | 2.16%   |
| Lenovo                  | 47        | 2.12%   |
| Philips                 | 34        | 1.53%   |
| ASUSTek Computer        | 33        | 1.49%   |
| CSO                     | 29        | 1.31%   |
| Ancor Communications    | 29        | 1.31%   |
| PANDA                   | 28        | 1.26%   |
| Apple                   | 22        | 0.99%   |
| InfoVision              | 20        | 0.9%    |
| ViewSonic               | 18        | 0.81%   |
| Iiyama                  | 16        | 0.72%   |
| MSI                     | 12        | 0.54%   |
| Gigabyte Technology     | 12        | 0.54%   |
| Sony                    | 10        | 0.45%   |
| Sceptre Tech            | 10        | 0.45%   |
| Mi                      | 10        | 0.45%   |
| Chi Mei Optoelectronics | 9         | 0.41%   |
| TMX                     | 7         | 0.32%   |
| Panasonic               | 7         | 0.32%   |
| JDI                     | 7         | 0.32%   |
| Eizo                    | 7         | 0.32%   |
| Unknown                 | 6         | 0.27%   |
| Toshiba                 | 6         | 0.27%   |
| NEC Computers           | 6         | 0.27%   |
| Vizio                   | 5         | 0.23%   |
| LG Philips              | 5         | 0.23%   |
| Pixio                   | 4         | 0.18%   |
| HUAWEI                  | 4         | 0.18%   |
| HannStar                | 4         | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 17        | 0.74%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 15        | 0.65%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 15        | 0.65%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 14        | 0.61%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 14        | 0.61%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 11        | 0.48%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                      | 11        | 0.48%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 9         | 0.39%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 9         | 0.39%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 9         | 0.39%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 8         | 0.35%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 8         | 0.35%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                 | 8         | 0.35%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 8         | 0.35%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 7         | 0.31%   |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch      | 7         | 0.31%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 7         | 0.31%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 7         | 0.31%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 6         | 0.26%   |
| Hewlett-Packard 24fw HPN3545 1920x1080 527x296mm 23.8-inch            | 6         | 0.26%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 6         | 0.26%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 6         | 0.26%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 6         | 0.26%   |
| BOE LCD Monitor BOE092F 2520x1680 338x226mm 16.0-inch                 | 6         | 0.26%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                 | 6         | 0.26%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch        | 6         | 0.26%   |
| AOC 24P2W1DG5 AOC2402 1920x1080 527x296mm 23.8-inch                   | 6         | 0.26%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 5         | 0.22%   |
| Samsung Electronics LCD Monitor SDC416D 2880x1800 312x195mm 14.5-inch | 5         | 0.22%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 5         | 0.22%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 5         | 0.22%   |
| Lenovo LEN L28u-30 LEN65FA 3840x2160 621x341mm 27.9-inch              | 5         | 0.22%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 5         | 0.22%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 5         | 0.22%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 5         | 0.22%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch      | 5         | 0.22%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch      | 5         | 0.22%   |
| BOE LCD Monitor BOE08A8 1920x1080 344x194mm 15.5-inch                 | 5         | 0.22%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                 | 5         | 0.22%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 5         | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1026      | 49.3%   |
| 1366x768 (WXGA)    | 201       | 9.66%   |
| 3840x2160 (4K)     | 181       | 8.7%    |
| 2560x1440 (QHD)    | 172       | 8.27%   |
| 1920x1200 (WUXGA)  | 74        | 3.56%   |
| 3440x1440          | 58        | 2.79%   |
| 1600x900 (HD+)     | 54        | 2.59%   |
| 2560x1600          | 52        | 2.5%    |
| 2880x1800          | 30        | 1.44%   |
| 1280x1024 (SXGA)   | 27        | 1.3%    |
| 2560x1080          | 23        | 1.11%   |
| 1680x1050 (WSXGA+) | 21        | 1.01%   |
| 1440x900 (WXGA+)   | 18        | 0.86%   |
| 3840x2400          | 17        | 0.82%   |
| 1280x800 (WXGA)    | 13        | 0.62%   |
| 2160x1440          | 10        | 0.48%   |
| 2256x1504          | 9         | 0.43%   |
| 3840x1080          | 8         | 0.38%   |
| 3000x2000          | 8         | 0.38%   |
| 1920x1280          | 8         | 0.38%   |
| 2736x1824          | 7         | 0.34%   |
| 1360x768           | 7         | 0.34%   |
| 2520x1680          | 6         | 0.29%   |
| 2288x1287          | 5         | 0.24%   |
| 1600x1200          | 5         | 0.24%   |
| 3456x2160          | 4         | 0.19%   |
| Unknown            | 4         | 0.19%   |
| 3200x2000          | 3         | 0.14%   |
| 3072x1920          | 3         | 0.14%   |
| 3200x1800 (QHD+)   | 2         | 0.1%    |
| 2880x1620          | 2         | 0.1%    |
| 2240x1400          | 2         | 0.1%    |
| 2160x1350          | 2         | 0.1%    |
| 1920x540           | 2         | 0.1%    |
| 1024x768 (XGA)     | 2         | 0.1%    |
| 800x1280           | 1         | 0.05%   |
| 4160x1440          | 1         | 0.05%   |
| 3840x1600          | 1         | 0.05%   |
| 3200x1080          | 1         | 0.05%   |
| 3120x1600          | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 559       | 25.02%  |
| 13      | 269       | 12.04%  |
| 27      | 229       | 10.25%  |
| 14      | 215       | 9.62%   |
| 24      | 167       | 7.48%   |
| 23      | 129       | 5.77%   |
| 21      | 77        | 3.45%   |
| 17      | 69        | 3.09%   |
| 31      | 68        | 3.04%   |
| 34      | 66        | 2.95%   |
| 16      | 62        | 2.78%   |
| 12      | 43        | 1.92%   |
| 19      | 28        | 1.25%   |
| Unknown | 27        | 1.21%   |
| 20      | 24        | 1.07%   |
| 18      | 24        | 1.07%   |
| 25      | 17        | 0.76%   |
| 22      | 15        | 0.67%   |
| 11      | 15        | 0.67%   |
| 40      | 13        | 0.58%   |
| 32      | 13        | 0.58%   |
| 84      | 12        | 0.54%   |
| 26      | 11        | 0.49%   |
| 48      | 10        | 0.45%   |
| 29      | 7         | 0.31%   |
| 72      | 6         | 0.27%   |
| 54      | 6         | 0.27%   |
| 28      | 6         | 0.27%   |
| 142     | 5         | 0.22%   |
| 35      | 5         | 0.22%   |
| 10      | 5         | 0.22%   |
| 43      | 4         | 0.18%   |
| 39      | 4         | 0.18%   |
| 69      | 3         | 0.13%   |
| 42      | 3         | 0.13%   |
| 36      | 3         | 0.13%   |
| 65      | 2         | 0.09%   |
| 52      | 2         | 0.09%   |
| 38      | 2         | 0.09%   |
| 33      | 2         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 944       | 43.3%   |
| 501-600        | 487       | 22.34%  |
| 201-300        | 208       | 9.54%   |
| 401-500        | 149       | 6.83%   |
| 601-700        | 100       | 4.59%   |
| 351-400        | 97        | 4.45%   |
| 701-800        | 83        | 3.81%   |
| Unknown        | 27        | 1.24%   |
| 801-900        | 23        | 1.06%   |
| 1001-1500      | 23        | 1.06%   |
| 1501-2000      | 22        | 1.01%   |
| 901-1000       | 11        | 0.5%    |
| More than 2000 | 5         | 0.23%   |
| 1-100          | 1         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1492      | 77.03%  |
| 16/10   | 245       | 12.65%  |
| 21/9    | 78        | 4.03%   |
| 3/2     | 52        | 2.68%   |
| 5/4     | 22        | 1.14%   |
| 4/3     | 17        | 0.88%   |
| Unknown | 15        | 0.77%   |
| 32/9    | 7         | 0.36%   |
| 1.00    | 5         | 0.26%   |
| 3.33    | 1         | 0.05%   |
| 1.96    | 1         | 0.05%   |
| 0.89    | 1         | 0.05%   |
| 0.67    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 567       | 25.59%  |
| 81-90          | 361       | 16.29%  |
| 201-250        | 301       | 13.58%  |
| 301-350        | 237       | 10.69%  |
| 351-500        | 161       | 7.27%   |
| 71-80          | 124       | 5.6%    |
| 151-200        | 80        | 3.61%   |
| 251-300        | 73        | 3.29%   |
| 121-130        | 60        | 2.71%   |
| 111-120        | 52        | 2.35%   |
| More than 1000 | 41        | 1.85%   |
| 501-1000       | 40        | 1.81%   |
| 61-70          | 34        | 1.53%   |
| Unknown        | 27        | 1.22%   |
| 141-150        | 24        | 1.08%   |
| 51-60          | 18        | 0.81%   |
| 91-100         | 10        | 0.45%   |
| 131-140        | 3         | 0.14%   |
| 41-50          | 2         | 0.09%   |
| 1-40           | 1         | 0.05%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 742       | 34.75%  |
| 51-100        | 554       | 25.95%  |
| 101-120       | 401       | 18.78%  |
| 161-240       | 275       | 12.88%  |
| More than 240 | 102       | 4.78%   |
| 1-50          | 34        | 1.59%   |
| Unknown       | 27        | 1.26%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1418      | 73.36%  |
| 2     | 389       | 20.12%  |
| 0     | 70        | 3.62%   |
| 3     | 49        | 2.53%   |
| 4     | 6         | 0.31%   |
| 5     | 1         | 0.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 1134      | 40.97%  |
| Realtek Semiconductor                  | 963       | 34.79%  |
| Qualcomm Atheros                       | 182       | 6.58%   |
| MediaTek                               | 131       | 4.73%   |
| Broadcom                               | 83        | 3%      |
| TP-Link                                | 30        | 1.08%   |
| Qualcomm                               | 19        | 0.69%   |
| Lenovo                                 | 19        | 0.69%   |
| Ralink                                 | 15        | 0.54%   |
| ASIX Electronics                       | 14        | 0.51%   |
| Samsung Electronics                    | 13        | 0.47%   |
| Ralink Technology                      | 13        | 0.47%   |
| Sierra Wireless                        | 12        | 0.43%   |
| Broadcom Limited                       | 12        | 0.43%   |
| Aquantia                               | 12        | 0.43%   |
| Xiaomi                                 | 11        | 0.4%    |
| Microsoft                              | 9         | 0.33%   |
| Marvell Technology Group               | 8         | 0.29%   |
| Hewlett-Packard                        | 8         | 0.29%   |
| Dell                                   | 8         | 0.29%   |
| Google                                 | 7         | 0.25%   |
| D-Link                                 | 7         | 0.25%   |
| DisplayLink                            | 5         | 0.18%   |
| Nvidia                                 | 4         | 0.14%   |
| ASUSTek Computer                       | 4         | 0.14%   |
| OPPO Electronics                       | 3         | 0.11%   |
| Mellanox Technologies                  | 3         | 0.11%   |
| Huawei Technologies                    | 3         | 0.11%   |
| Fibocom                                | 3         | 0.11%   |
| Ericsson Business Mobile Networks      | 3         | 0.11%   |
| Qualcomm Atheros Communications        | 2         | 0.07%   |
| NetGear                                | 2         | 0.07%   |
| Linksys                                | 2         | 0.07%   |
| InterBiometrics                        | 2         | 0.07%   |
| Arduino SA                             | 2         | 0.07%   |
| Apple                                  | 2         | 0.07%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.04%   |
| Zoom Telephonics                       | 1         | 0.04%   |
| T & A Mobile Phones                    | 1         | 0.04%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 603       | 18.52%  |
| Intel Wi-Fi 6 AX200                                               | 150       | 4.61%   |
| Intel Wi-Fi 6 AX201                                               | 112       | 3.44%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 99        | 3.04%   |
| Intel Wireless 8265 / 8275                                        | 89        | 2.73%   |
| Realtek RTL8125 2.5GbE Controller                                 | 84        | 2.58%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 77        | 2.36%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 71        | 2.18%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 67        | 2.06%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 66        | 2.03%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 52        | 1.6%    |
| Intel I211 Gigabit Network Connection                             | 47        | 1.44%   |
| Intel Ethernet Controller I225-V                                  | 47        | 1.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 45        | 1.38%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 44        | 1.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 38        | 1.17%   |
| Intel Wireless 8260                                               | 38        | 1.17%   |
| Intel Wireless 7265                                               | 38        | 1.17%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 37        | 1.14%   |
| Intel Ethernet Connection (2) I219-V                              | 35        | 1.07%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 34        | 1.04%   |
| Intel Ethernet Connection (4) I219-LM                             | 34        | 1.04%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 34        | 1.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 32        | 0.98%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 32        | 0.98%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 32        | 0.98%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 28        | 0.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 27        | 0.83%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 26        | 0.8%    |
| Intel Wireless-AC 9260                                            | 25        | 0.77%   |
| Intel Wireless 7260                                               | 25        | 0.77%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 22        | 0.68%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 20        | 0.61%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 19        | 0.58%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 19        | 0.58%   |
| Intel Ethernet Connection I219-LM                                 | 18        | 0.55%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 16        | 0.49%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 16        | 0.49%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 15        | 0.46%   |
| Intel Ethernet Connection (7) I219-V                              | 15        | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 944       | 56.9%   |
| Realtek Semiconductor                 | 248       | 14.95%  |
| Qualcomm Atheros                      | 145       | 8.74%   |
| MediaTek                              | 130       | 7.84%   |
| Broadcom                              | 57        | 3.44%   |
| TP-Link                               | 27        | 1.63%   |
| Ralink                                | 15        | 0.9%    |
| Qualcomm                              | 15        | 0.9%    |
| Ralink Technology                     | 13        | 0.78%   |
| Broadcom Limited                      | 12        | 0.72%   |
| Sierra Wireless                       | 10        | 0.6%    |
| Microsoft                             | 8         | 0.48%   |
| Dell                                  | 7         | 0.42%   |
| Marvell Technology Group              | 4         | 0.24%   |
| Hewlett-Packard                       | 4         | 0.24%   |
| D-Link                                | 4         | 0.24%   |
| ASUSTek Computer                      | 4         | 0.24%   |
| Fibocom                               | 3         | 0.18%   |
| Qualcomm Atheros Communications       | 2         | 0.12%   |
| NetGear                               | 2         | 0.12%   |
| Linksys                               | 1         | 0.06%   |
| IMC Networks                          | 1         | 0.06%   |
| D-Link System                         | 1         | 0.06%   |
| AboCom Systems                        | 1         | 0.06%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 150       | 9.02%   |
| Intel Wi-Fi 6 AX201                                            | 112       | 6.73%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 99        | 5.95%   |
| Intel Wireless 8265 / 8275                                     | 89        | 5.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 71        | 4.27%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 67        | 4.03%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 52        | 3.13%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 44        | 2.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 38        | 2.29%   |
| Intel Wireless 8260                                            | 38        | 2.29%   |
| Intel Wireless 7265                                            | 38        | 2.29%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 37        | 2.22%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 34        | 2.04%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 34        | 2.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 32        | 1.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 32        | 1.92%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 32        | 1.92%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 28        | 1.68%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 27        | 1.62%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 26        | 1.56%   |
| Intel Wireless-AC 9260                                         | 25        | 1.5%    |
| Intel Wireless 7260                                            | 25        | 1.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 22        | 1.32%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 20        | 1.2%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 19        | 1.14%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 19        | 1.14%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 16        | 0.96%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 16        | 0.96%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 15        | 0.9%    |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 14        | 0.84%   |
| Intel Wireless 3165                                            | 14        | 0.84%   |
| Broadcom BCM43142 802.11b/g/n                                  | 12        | 0.72%   |
| Intel Centrino Ultimate-N 6300                                 | 11        | 0.66%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 9         | 0.54%   |
| Realtek 802.11ac NIC                                           | 9         | 0.54%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 9         | 0.54%   |
| Intel Wireless 3160                                            | 9         | 0.54%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 9         | 0.54%   |
| Sierra Wireless EM7455                                         | 8         | 0.48%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 8         | 0.48%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 840       | 54.97%  |
| Intel                                  | 485       | 31.74%  |
| Qualcomm Atheros                       | 45        | 2.95%   |
| Broadcom                               | 39        | 2.55%   |
| Lenovo                                 | 18        | 1.18%   |
| ASIX Electronics                       | 14        | 0.92%   |
| Samsung Electronics                    | 12        | 0.79%   |
| Aquantia                               | 12        | 0.79%   |
| Xiaomi                                 | 11        | 0.72%   |
| Google                                 | 7         | 0.46%   |
| DisplayLink                            | 5         | 0.33%   |
| Qualcomm                               | 4         | 0.26%   |
| Nvidia                                 | 4         | 0.26%   |
| Marvell Technology Group               | 4         | 0.26%   |
| TP-Link                                | 3         | 0.2%    |
| OPPO Electronics                       | 3         | 0.2%    |
| Mellanox Technologies                  | 3         | 0.2%    |
| D-Link                                 | 3         | 0.2%    |
| Sierra Wireless                        | 2         | 0.13%   |
| Apple                                  | 2         | 0.13%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.07%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.07%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.07%   |
| Motorola PCS                           | 1         | 0.07%   |
| Microsoft                              | 1         | 0.07%   |
| MediaTek                               | 1         | 0.07%   |
| Linksys                                | 1         | 0.07%   |
| JMicron Technology                     | 1         | 0.07%   |
| ICS Advent                             | 1         | 0.07%   |
| Huawei Technologies                    | 1         | 0.07%   |
| Hewlett-Packard                        | 1         | 0.07%   |
| American Megatrends                    | 1         | 0.07%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 603       | 38.41%  |
| Realtek RTL8125 2.5GbE Controller                                   | 84        | 5.35%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 77        | 4.9%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 66        | 4.2%    |
| Intel I211 Gigabit Network Connection                               | 47        | 2.99%   |
| Intel Ethernet Controller I225-V                                    | 47        | 2.99%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 45        | 2.87%   |
| Intel Ethernet Connection (2) I219-V                                | 35        | 2.23%   |
| Intel Ethernet Connection (4) I219-LM                               | 34        | 2.17%   |
| Intel Ethernet Connection I219-LM                                   | 18        | 1.15%   |
| Intel Ethernet Connection (7) I219-V                                | 15        | 0.96%   |
| Intel Ethernet Connection (4) I219-V                                | 14        | 0.89%   |
| Intel Ethernet Connection (10) I219-V                               | 14        | 0.89%   |
| Intel Ethernet Connection I217-LM                                   | 13        | 0.83%   |
| Intel Ethernet Connection (2) I219-LM                               | 13        | 0.83%   |
| Intel Ethernet Connection (16) I219-V                               | 13        | 0.83%   |
| ASIX AX88179 Gigabit Ethernet                                       | 13        | 0.83%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 12        | 0.76%   |
| Intel Ethernet Connection (6) I219-V                                | 12        | 0.76%   |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 11        | 0.7%    |
| Realtek RTL8152 Fast Ethernet Adapter                               | 11        | 0.7%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller           | 11        | 0.7%    |
| Intel Ethernet Connection (13) I219-V                               | 11        | 0.7%    |
| Intel Ethernet Connection I218-LM                                   | 10        | 0.64%   |
| Intel Ethernet Connection (7) I219-LM                               | 10        | 0.64%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                    | 9         | 0.57%   |
| Intel Ethernet Connection (3) I218-LM                               | 9         | 0.57%   |
| Intel 82579V Gigabit Network Connection                             | 9         | 0.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 8         | 0.51%   |
| Lenovo ThinkPad TBT 3 Dock                                          | 8         | 0.51%   |
| Intel Ethernet Connection (6) I219-LM                               | 8         | 0.51%   |
| Intel Ethernet Connection (2) I218-V                                | 8         | 0.51%   |
| Intel 82574L Gigabit Network Connection                             | 8         | 0.51%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 8         | 0.51%   |
| Realtek Killer E3000 2.5GbE Controller                              | 7         | 0.45%   |
| Intel Ethernet Connection I217-V                                    | 7         | 0.45%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller           | 6         | 0.38%   |
| Intel I210 Gigabit Network Connection                               | 6         | 0.38%   |
| Intel Ethernet Connection I219-V                                    | 6         | 0.38%   |
| Intel Ethernet Connection (11) I219-LM                              | 6         | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1586      | 52.5%   |
| Ethernet | 1412      | 46.74%  |
| Modem    | 18        | 0.6%    |
| Unknown  | 5         | 0.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1302      | 65.36%  |
| Ethernet | 690       | 34.64%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 950       | 49.76%  |
| 1     | 855       | 44.79%  |
| 3     | 62        | 3.25%   |
| 0     | 30        | 1.57%   |
| 4     | 9         | 0.47%   |
| 5     | 2         | 0.1%    |
| 9     | 1         | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1405      | 73.25%  |
| Yes  | 513       | 26.75%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 843       | 57.66%  |
| Realtek Semiconductor           | 148       | 10.12%  |
| Foxconn / Hon Hai               | 72        | 4.92%   |
| Qualcomm Atheros Communications | 65        | 4.45%   |
| IMC Networks                    | 63        | 4.31%   |
| Cambridge Silicon Radio         | 59        | 4.04%   |
| Lite-On Technology              | 42        | 2.87%   |
| Broadcom                        | 35        | 2.39%   |
| MediaTek                        | 26        | 1.78%   |
| Apple                           | 25        | 1.71%   |
| Realtek                         | 18        | 1.23%   |
| TP-Link                         | 15        | 1.03%   |
| ASUSTek Computer                | 11        | 0.75%   |
| Toshiba                         | 5         | 0.34%   |
| Dell                            | 5         | 0.34%   |
| USI                             | 4         | 0.27%   |
| Opticis                         | 4         | 0.27%   |
| Marvell Semiconductor           | 4         | 0.27%   |
| Hewlett-Packard                 | 4         | 0.27%   |
| Belkin Components               | 3         | 0.21%   |
| Ralink                          | 2         | 0.14%   |
| Edimax Technology               | 2         | 0.14%   |
| Smart Modular Technologies      | 1         | 0.07%   |
| SINO WEALTH                     | 1         | 0.07%   |
| Integrated System Solution      | 1         | 0.07%   |
| HTC (High Tech Computer)        | 1         | 0.07%   |
| Dynex                           | 1         | 0.07%   |
| Corsair                         | 1         | 0.07%   |
| Chicony Electronics             | 1         | 0.07%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 208       | 14.21%  |
| Intel Bluetooth wireless interface                  | 188       | 12.84%  |
| Intel AX200 Bluetooth                               | 144       | 9.84%   |
| Realtek Bluetooth Radio                             | 122       | 8.33%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 118       | 8.06%   |
| Intel Bluetooth Device                              | 79        | 5.4%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 59        | 4.03%   |
| Qualcomm Atheros  Bluetooth Device                  | 53        | 3.62%   |
| Intel AX210 Bluetooth                               | 51        | 3.48%   |
| Foxconn / Hon Hai Wireless_Device                   | 49        | 3.35%   |
| IMC Networks Wireless_Device                        | 32        | 2.19%   |
| MediaTek Wireless_Device                            | 26        | 1.78%   |
| Intel Wireless-AC 3168 Bluetooth                    | 25        | 1.71%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 21        | 1.43%   |
| Realtek  Bluetooth 4.2 Adapter                      | 18        | 1.23%   |
| Realtek 802.11ac WLAN Adapter                       | 18        | 1.23%   |
| IMC Networks Bluetooth Radio                        | 18        | 1.23%   |
| TP-Link UB500 Adapter                               | 15        | 1.02%   |
| Apple Bluetooth Host Controller                     | 14        | 0.96%   |
| Lite-On Bluetooth Device                            | 13        | 0.89%   |
| Foxconn / Hon Hai Bluetooth Device                  | 13        | 0.89%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 11        | 0.75%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 10        | 0.68%   |
| Lite-On Wireless_Device                             | 9         | 0.61%   |
| IMC Networks Bluetooth Device                       | 9         | 0.61%   |
| Apple Bluetooth USB Host Controller                 | 9         | 0.61%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 8         | 0.55%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 6         | 0.41%   |
| Foxconn / Hon Hai MediaTek MT7921 Bluetooth         | 5         | 0.34%   |
| ASUS ASUS USB-BT500                                 | 5         | 0.34%   |
| USI Bluetooth Device                                | 4         | 0.27%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 4         | 0.27%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 4         | 0.27%   |
| Opticis Bluetooth Radio                             | 4         | 0.27%   |
| Marvell Bluetooth and Wireless LAN Composite        | 4         | 0.27%   |
| Lite-On Bluetooth Radio                             | 4         | 0.27%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 3         | 0.2%    |
| Realtek RTL8821A Bluetooth                          | 3         | 0.2%    |
| Qualcomm Atheros AR9462 Bluetooth                   | 3         | 0.2%    |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 3         | 0.2%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1264      | 45.4%   |
| AMD                                  | 672       | 24.14%  |
| Nvidia                               | 444       | 15.95%  |
| C-Media Electronics                  | 45        | 1.62%   |
| Logitech                             | 33        | 1.19%   |
| Lenovo                               | 19        | 0.68%   |
| JMTek                                | 17        | 0.61%   |
| Razer USA                            | 16        | 0.57%   |
| ASUSTek Computer                     | 16        | 0.57%   |
| Kingston Technology                  | 15        | 0.54%   |
| GN Netcom                            | 15        | 0.54%   |
| Creative Labs                        | 15        | 0.54%   |
| Realtek Semiconductor                | 14        | 0.5%    |
| Plantronics                          | 12        | 0.43%   |
| SteelSeries ApS                      | 10        | 0.36%   |
| Generalplus Technology               | 10        | 0.36%   |
| Focusrite-Novation                   | 10        | 0.36%   |
| Corsair                              | 9         | 0.32%   |
| Texas Instruments                    | 8         | 0.29%   |
| Hewlett-Packard                      | 7         | 0.25%   |
| Creative Technology                  | 7         | 0.25%   |
| Samson Technologies                  | 6         | 0.22%   |
| RODE Microphones                     | 5         | 0.18%   |
| Dell                                 | 5         | 0.18%   |
| Blue Microphones                     | 5         | 0.18%   |
| VIA Technologies                     | 4         | 0.14%   |
| Sony                                 | 4         | 0.14%   |
| Samsung Electronics                  | 4         | 0.14%   |
| Micro Star International             | 4         | 0.14%   |
| XMOS                                 | 3         | 0.11%   |
| Thesycon Systemsoftware & Consulting | 3         | 0.11%   |
| M-Audio                              | 3         | 0.11%   |
| Giga-Byte Technology                 | 3         | 0.11%   |
| FiiO Electronics Technology          | 3         | 0.11%   |
| Cambridge Silicon Radio              | 3         | 0.11%   |
| Asahi Kasei Microsystems             | 3         | 0.11%   |
| Apple                                | 3         | 0.11%   |
| Yamaha                               | 2         | 0.07%   |
| Trust                                | 2         | 0.07%   |
| Schiit Audio                         | 2         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 363       | 10.74%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 232       | 6.86%   |
| Intel Sunrise Point-LP HD Audio                                            | 189       | 5.59%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 133       | 3.93%   |
| AMD Starship/Matisse HD Audio Controller                                   | 122       | 3.61%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 118       | 3.49%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 87        | 2.57%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 85        | 2.51%   |
| Intel Cannon Lake PCH cAVS                                                 | 72        | 2.13%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 66        | 1.95%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 60        | 1.78%   |
| Intel Comet Lake PCH-LP cAVS                                               | 58        | 1.72%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 55        | 1.63%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 51        | 1.51%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 50        | 1.48%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 50        | 1.48%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 47        | 1.39%   |
| Nvidia GA106 High Definition Audio Controller                              | 44        | 1.3%    |
| Intel Comet Lake PCH cAVS                                                  | 44        | 1.3%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 39        | 1.15%   |
| Nvidia GP107GL High Definition Audio Controller                            | 35        | 1.04%   |
| Nvidia GA104 High Definition Audio Controller                              | 34        | 1.01%   |
| Intel 200 Series PCH HD Audio                                              | 34        | 1.01%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 32        | 0.95%   |
| Nvidia TU106 High Definition Audio Controller                              | 31        | 0.92%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 31        | 0.92%   |
| Intel Broadwell-U Audio Controller                                         | 31        | 0.92%   |
| Intel Alder Lake-S HD Audio Controller                                     | 31        | 0.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 29        | 0.86%   |
| Nvidia Audio device                                                        | 27        | 0.8%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 27        | 0.8%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 25        | 0.74%   |
| Nvidia GP106 High Definition Audio Controller                              | 24        | 0.71%   |
| Intel Haswell-ULT HD Audio Controller                                      | 23        | 0.68%   |
| Intel 8 Series HD Audio Controller                                         | 23        | 0.68%   |
| AMD FCH Azalia Controller                                                  | 23        | 0.68%   |
| Nvidia TU116 High Definition Audio Controller                              | 21        | 0.62%   |
| Nvidia GP104 High Definition Audio Controller                              | 21        | 0.62%   |
| Intel CM238 HD Audio Controller                                            | 21        | 0.62%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 19        | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 281       | 24.89%  |
| SK hynix            | 209       | 18.51%  |
| Micron Technology   | 141       | 12.49%  |
| Kingston            | 103       | 9.12%   |
| Crucial             | 67        | 5.93%   |
| Corsair             | 58        | 5.14%   |
| G.Skill             | 56        | 4.96%   |
| Unknown             | 52        | 4.61%   |
| A-DATA Technology   | 28        | 2.48%   |
| Ramaxel Technology  | 18        | 1.59%   |
| Team                | 13        | 1.15%   |
| Unknown             | 11        | 0.97%   |
| Smart               | 9         | 0.8%    |
| Patriot             | 9         | 0.8%    |
| Elpida              | 8         | 0.71%   |
| Unknown (ABCD)      | 6         | 0.53%   |
| Nanya Technology    | 5         | 0.44%   |
| Transcend           | 4         | 0.35%   |
| AMD                 | 4         | 0.35%   |
| Avant               | 3         | 0.27%   |
| Apacer              | 3         | 0.27%   |
| Unifosa             | 2         | 0.18%   |
| Smart Brazil        | 2         | 0.18%   |
| PUSKILL             | 2         | 0.18%   |
| PNY                 | 2         | 0.18%   |
| Hewlett-Packard     | 2         | 0.18%   |
| GOODRAM             | 2         | 0.18%   |
| Goldkey             | 2         | 0.18%   |
| Gold Key            | 2         | 0.18%   |
| GeIL                | 2         | 0.18%   |
| Wodposit            | 1         | 0.09%   |
| Wilk                | 1         | 0.09%   |
| V-Color             | 1         | 0.09%   |
| Unknown (F288)      | 1         | 0.09%   |
| Unknown (0x0C97)    | 1         | 0.09%   |
| Unknown (0x0B5E)    | 1         | 0.09%   |
| Timetec             | 1         | 0.09%   |
| Teikon              | 1         | 0.09%   |
| Silicon Power       | 1         | 0.09%   |
| Qumo                | 1         | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 18        | 1.51%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 14        | 1.17%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 14        | 1.17%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 13        | 1.09%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 13        | 1.09%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 12        | 1.01%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 12        | 1.01%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 11        | 0.92%   |
| Unknown                                                          | 11        | 0.92%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 9         | 0.76%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 9         | 0.76%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 4GB Row Of Chips LPDDR5 6400MT/s | 8         | 0.67%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 7         | 0.59%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 7         | 0.59%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 7         | 0.59%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 6         | 0.5%    |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 6         | 0.5%    |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s              | 6         | 0.5%    |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 5         | 0.42%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 5         | 0.42%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 5         | 0.42%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 5         | 0.42%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 0.42%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 5         | 0.42%   |
| Samsung RAM K3LKBKB@BM-MGCP 2GB Row Of Chips LPDDR5 6400MT/s     | 5         | 0.42%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 5         | 0.42%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 5         | 0.42%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s             | 5         | 0.42%   |
| Corsair RAM CMK16GX4M2B3000C15 8192MB DIMM DDR4 3200MT/s         | 5         | 0.42%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 4         | 0.34%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 0.34%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.34%   |
| SK hynix RAM HMAB2GS6CMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 4         | 0.34%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s          | 4         | 0.34%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 4         | 0.34%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 4         | 0.34%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 0.34%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.34%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 4         | 0.34%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 4         | 0.34%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 592       | 60.84%  |
| DDR3    | 163       | 16.75%  |
| LPDDR4  | 58        | 5.96%   |
| DDR5    | 49        | 5.04%   |
| LPDDR5  | 44        | 4.52%   |
| LPDDR3  | 37        | 3.8%    |
| DDR2    | 17        | 1.75%   |
| Unknown | 8         | 0.82%   |
| SDRAM   | 4         | 0.41%   |
| DDR     | 1         | 0.1%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 556       | 56.5%   |
| DIMM         | 248       | 25.2%   |
| Row Of Chips | 167       | 16.97%  |
| Unknown      | 7         | 0.71%   |
| Chip         | 4         | 0.41%   |
| FB-DIMM      | 2         | 0.2%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 484       | 46.76%  |
| 16384 | 205       | 19.81%  |
| 4096  | 202       | 19.52%  |
| 2048  | 72        | 6.96%   |
| 32768 | 60        | 5.8%    |
| 1024  | 11        | 1.06%   |
| 32767 | 1         | 0.1%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 302       | 29.12%  |
| 2667    | 159       | 15.33%  |
| 1600    | 109       | 10.51%  |
| 2400    | 65        | 6.27%   |
| 2133    | 52        | 5.01%   |
| 6400    | 44        | 4.24%   |
| 4800    | 36        | 3.47%   |
| 1333    | 35        | 3.38%   |
| 3600    | 31        | 2.99%   |
| 4267    | 28        | 2.7%    |
| 1867    | 22        | 2.12%   |
| 4266    | 11        | 1.06%   |
| 3466    | 11        | 1.06%   |
| 800     | 10        | 0.96%   |
| 3733    | 9         | 0.87%   |
| 3866    | 8         | 0.77%   |
| 3266    | 8         | 0.77%   |
| 667     | 7         | 0.68%   |
| 5200    | 6         | 0.58%   |
| 3000    | 6         | 0.58%   |
| 2666    | 6         | 0.58%   |
| 1866    | 5         | 0.48%   |
| 1334    | 5         | 0.48%   |
| 8400    | 4         | 0.39%   |
| 3800    | 4         | 0.39%   |
| 1800    | 4         | 0.39%   |
| 1066    | 4         | 0.39%   |
| 6000    | 3         | 0.29%   |
| 3666    | 3         | 0.29%   |
| 3400    | 3         | 0.29%   |
| Unknown | 3         | 0.29%   |
| 5600    | 2         | 0.19%   |
| 3333    | 2         | 0.19%   |
| 2933    | 2         | 0.19%   |
| 2800    | 2         | 0.19%   |
| 1067    | 2         | 0.19%   |
| 933     | 2         | 0.19%   |
| 533     | 2         | 0.19%   |
| 400     | 2         | 0.19%   |
| 333     | 2         | 0.19%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 8         | 28.57%  |
| Brother Industries    | 7         | 25%     |
| Seiko Epson           | 4         | 14.29%  |
| Samsung Electronics   | 4         | 14.29%  |
| Canon                 | 2         | 7.14%   |
| Prolific Technology   | 1         | 3.57%   |
| MiiiW                 | 1         | 3.57%   |
| Lexmark International | 1         | 3.57%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Seiko Epson WP-4020 Series    | 1         | 3.57%   |
| Seiko Epson WF-2860 Series    | 1         | 3.57%   |
| Seiko Epson Printer           | 1         | 3.57%   |
| Seiko Epson L300 Series       | 1         | 3.57%   |
| Samsung SCX-4623 Series       | 1         | 3.57%   |
| Samsung SCX-4300 Series       | 1         | 3.57%   |
| Samsung ML-2855 Series        | 1         | 3.57%   |
| Samsung M2070 Series          | 1         | 3.57%   |
| Prolific PL2305 Parallel Port | 1         | 3.57%   |
| MiiiW MW USB Receiver         | 1         | 3.57%   |
| Lexmark International B2236dw | 1         | 3.57%   |
| HP Officejet 2620 series      | 1         | 3.57%   |
| HP LaserJet P2055 series      | 1         | 3.57%   |
| HP LaserJet 1012              | 1         | 3.57%   |
| HP LaserJet 1010              | 1         | 3.57%   |
| HP ENVY Photo 7800 series     | 1         | 3.57%   |
| HP DeskJet F300 series        | 1         | 3.57%   |
| HP DeskJet 5650c              | 1         | 3.57%   |
| HP DeskJet 3630 series        | 1         | 3.57%   |
| Canon TS5100 series           | 1         | 3.57%   |
| Canon LiDE 400                | 1         | 3.57%   |
| Brother MFC-7460DN            | 1         | 3.57%   |
| Brother HL-L2350DW series     | 1         | 3.57%   |
| Brother HL-L2320D series      | 1         | 3.57%   |
| Brother HL-L2300D series      | 1         | 3.57%   |
| Brother HL-2030 Laser Printer | 1         | 3.57%   |
| Brother DCP-L2510D series     | 1         | 3.57%   |
| Brother DCP-1600              | 1         | 3.57%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 5         | 62.5%   |
| Canon       | 3         | 37.5%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Seiko Epson GT-X770 [Perfection V500]                    | 2         | 25%     |
| Seiko Epson GT-6600U [Perfection 610]                    | 2         | 25%     |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 12.5%   |
| Canon CanoScan N670U/N676U/LiDE 20                       | 1         | 12.5%   |
| Canon CanoScan LiDE 210                                  | 1         | 12.5%   |
| Canon CanoScan LiDE 100                                  | 1         | 12.5%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 299       | 22.13%  |
| IMC Networks                           | 170       | 12.58%  |
| Microdia                               | 128       | 9.47%   |
| Logitech                               | 101       | 7.48%   |
| Quanta                                 | 100       | 7.4%    |
| Realtek Semiconductor                  | 68        | 5.03%   |
| Sunplus Innovation Technology          | 59        | 4.37%   |
| Bison Electronics                      | 57        | 4.22%   |
| Acer                                   | 47        | 3.48%   |
| Cheng Uei Precision Industry (Foxlink) | 41        | 3.03%   |
| Luxvisions Innotech Limited            | 40        | 2.96%   |
| Syntek                                 | 37        | 2.74%   |
| Apple                                  | 24        | 1.78%   |
| Lite-On Technology                     | 23        | 1.7%    |
| Sonix Technology                       | 21        | 1.55%   |
| Microsoft                              | 15        | 1.11%   |
| Silicon Motion                         | 11        | 0.81%   |
| Samsung Electronics                    | 10        | 0.74%   |
| Suyin                                  | 9         | 0.67%   |
| SunplusIT                              | 7         | 0.52%   |
| KYE Systems (Mouse Systems)            | 5         | 0.37%   |
| AVerMedia Technologies                 | 5         | 0.37%   |
| Alcor Micro                            | 5         | 0.37%   |
| Tripath Technology                     | 4         | 0.3%    |
| MacroSilicon                           | 4         | 0.3%    |
| WaveRider Communications               | 3         | 0.22%   |
| Primax Electronics                     | 3         | 0.22%   |
| LG Electronics                         | 3         | 0.22%   |
| Generalplus Technology                 | 3         | 0.22%   |
| ARC International                      | 3         | 0.22%   |
| Trust                                  | 2         | 0.15%   |
| Shenzhen Kingcome Optoelectronic       | 2         | 0.15%   |
| Ricoh                                  | 2         | 0.15%   |
| Lenovo                                 | 2         | 0.15%   |
| kingcome                               | 2         | 0.15%   |
| Importek                               | 2         | 0.15%   |
| icSpring                               | 2         | 0.15%   |
| Hewlett-Packard                        | 2         | 0.15%   |
| Cubeternet                             | 2         | 0.15%   |
| A4Tech                                 | 2         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 105       | 7.71%   |
| Microdia Integrated_Webcam_HD                       | 68        | 5%      |
| IMC Networks USB2.0 HD UVC WebCam                   | 56        | 4.11%   |
| IMC Networks Integrated Camera                      | 51        | 3.75%   |
| Realtek Integrated_Webcam_HD                        | 36        | 2.65%   |
| Chicony HD WebCam                                   | 27        | 1.98%   |
| Syntek Integrated Camera                            | 26        | 1.91%   |
| Acer Integrated Camera                              | 26        | 1.91%   |
| Quanta HD User Facing                               | 21        | 1.54%   |
| Sunplus Integrated_Webcam_HD                        | 20        | 1.47%   |
| Logitech HD Pro Webcam C920                         | 19        | 1.4%    |
| IMC Networks HD Camera                              | 19        | 1.4%    |
| Microdia Integrated_Webcam_FHD                      | 17        | 1.25%   |
| Logitech Webcam C270                                | 16        | 1.18%   |
| Quanta HP Wide Vision HD Camera                     | 15        | 1.1%    |
| Chicony HP Wide Vision HD Camera                    | 15        | 1.1%    |
| Bison Integrated Camera                             | 14        | 1.03%   |
| Sonix USB2.0 HD UVC WebCam                          | 13        | 0.96%   |
| Quanta HP HD Camera                                 | 13        | 0.96%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 12        | 0.88%   |
| Chicony USB2.0 Camera                               | 12        | 0.88%   |
| Luxvisions Innotech Limited Integrated RGB Camera   | 11        | 0.81%   |
| Logitech C922 Pro Stream Webcam                     | 11        | 0.81%   |
| Chicony Integrated Camera (1280x720@30)             | 11        | 0.81%   |
| Chicony HP Truevision HD camera                     | 11        | 0.81%   |
| Samsung Galaxy series, misc. (MTP mode)             | 10        | 0.73%   |
| Lite-On Integrated Camera                           | 10        | 0.73%   |
| Chicony HP HD Camera                                | 10        | 0.73%   |
| Bison SunplusIT Integrated Camera                   | 10        | 0.73%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 10        | 0.73%   |
| Luxvisions Innotech Limited Integrated Camera       | 9         | 0.66%   |
| Logitech HD Webcam C525                             | 9         | 0.66%   |
| Chicony USB2.0 VGA UVC WebCam                       | 9         | 0.66%   |
| Chicony HD User Facing                              | 9         | 0.66%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera    | 9         | 0.66%   |
| Bison HD Webcam                                     | 9         | 0.66%   |
| Quanta HP TrueVision HD Camera                      | 8         | 0.59%   |
| IMC Networks ov9734_azurewave_camera                | 8         | 0.59%   |
| Chicony EasyCamera                                  | 8         | 0.59%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 8         | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 128       | 41.29%  |
| Shenzhen Goodix Technology         | 74        | 23.87%  |
| Validity Sensors                   | 64        | 20.65%  |
| Elan Microelectronics              | 22        | 7.1%    |
| LighTuning Technology              | 7         | 2.26%   |
| AuthenTec                          | 5         | 1.61%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 0.97%   |
| Upek                               | 2         | 0.65%   |
| Samsung Electronics                | 2         | 0.65%   |
| STMicroelectronics                 | 1         | 0.32%   |
| Microsoft                          | 1         | 0.32%   |
| DigitalPersona                     | 1         | 0.32%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 55        | 17.74%  |
| Shenzhen Goodix  Fingerprint Device                                        | 55        | 17.74%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 15        | 4.84%   |
| Validity Sensors Synaptics WBDI                                            | 13        | 4.19%   |
| Elan ELAN:ARM-M4                                                           | 13        | 4.19%   |
| Shenzhen Goodix Fingerprint Reader                                         | 12        | 3.87%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 11        | 3.55%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 10        | 3.23%   |
| Synaptics  WBDI                                                            | 10        | 3.23%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 10        | 3.23%   |
| Synaptics WBDI                                                             | 8         | 2.58%   |
| Synaptics UWP WBDI                                                         | 8         | 2.58%   |
| Elan ELAN:Fingerprint                                                      | 8         | 2.58%   |
| Synaptics UWP WBDI Device                                                  | 7         | 2.26%   |
| Shenzhen Goodix FingerPrint                                                | 7         | 2.26%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 1.94%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 6         | 1.94%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 5         | 1.61%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 5         | 1.61%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 5         | 1.61%   |
| Validity Sensors VFS491                                                    | 3         | 0.97%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 3         | 0.97%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 0.97%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 0.97%   |
| AuthenTec AES1600                                                          | 3         | 0.97%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 0.65%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.65%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 0.65%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 2         | 0.65%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 0.65%   |
| LighTuning Fingerprint Sensor                                              | 2         | 0.65%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 0.65%   |
| AuthenTec AES2810                                                          | 2         | 0.65%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.32%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.32%   |
| Synaptics WBDI Device                                                      | 1         | 0.32%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.32%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.32%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 0.32%   |
| Samsung Fingerprint Device                                                 | 1         | 0.32%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Alcor Micro              | 47        | 41.96%  |
| Broadcom                 | 46        | 41.07%  |
| Upek                     | 6         | 5.36%   |
| Lenovo                   | 3         | 2.68%   |
| Gemalto (was Gemplus)    | 3         | 2.68%   |
| O2 Micro                 | 2         | 1.79%   |
| Yubico.com               | 1         | 0.89%   |
| Reiner SCT Kartensysteme | 1         | 0.89%   |
| Realtek Semiconductor    | 1         | 0.89%   |
| Purism, SPC              | 1         | 0.89%   |
| Aktiv                    | 1         | 0.89%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 47        | 41.96%  |
| Broadcom 58200                                                               | 19        | 16.96%  |
| Broadcom 5880                                                                | 18        | 16.07%  |
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 6.25%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 6         | 5.36%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 2.68%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 2.68%   |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 1.79%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 1.79%   |
| Yubico.com Yubikey 4 U2F+CCID                                                | 1         | 0.89%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.89%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.89%   |
| Purism, SPC Librem Key                                                       | 1         | 0.89%   |
| Aktiv Rutoken lite                                                           | 1         | 0.89%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1281      | 66.48%  |
| 1     | 536       | 27.82%  |
| 2     | 80        | 4.15%   |
| 3     | 13        | 0.67%   |
| 4     | 7         | 0.36%   |
| 5     | 5         | 0.26%   |
| 7     | 4         | 0.21%   |
| 8     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 307       | 39.26%  |
| Graphics card            | 186       | 23.79%  |
| Multimedia controller    | 85        | 10.87%  |
| Net/wireless             | 57        | 7.29%   |
| Camera                   | 36        | 4.6%    |
| Chipcard                 | 23        | 2.94%   |
| Sound                    | 22        | 2.81%   |
| Communication controller | 14        | 1.79%   |
| Bluetooth                | 12        | 1.53%   |
| Unassigned class         | 11        | 1.41%   |
| Card reader              | 11        | 1.41%   |
| Net/ethernet             | 6         | 0.77%   |
| Network                  | 4         | 0.51%   |
| Storage/raid             | 3         | 0.38%   |
| Storage                  | 3         | 0.38%   |
| Modem                    | 1         | 0.13%   |
| Firewire controller      | 1         | 0.13%   |

