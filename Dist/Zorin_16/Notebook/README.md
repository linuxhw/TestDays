Zorin 16 - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------

A project to collect tested hardware configurations for Zorin 16.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Apple         | MacBookPro8,1               | [70e86eb89a](https://linux-hardware.org/?probe=70e86eb89a) | Jan 31, 2022 |
| Sony          | SVF15213CBW                 | [cf01ca64c3](https://linux-hardware.org/?probe=cf01ca64c3) | Jan 31, 2022 |
| Sony          | SVF15213CBW                 | [17015b4fbe](https://linux-hardware.org/?probe=17015b4fbe) | Jan 30, 2022 |
| Dell          | Latitude E5420              | [89a74ff338](https://linux-hardware.org/?probe=89a74ff338) | Jan 29, 2022 |
| HP            | Pavilion dv7                | [504e2036d3](https://linux-hardware.org/?probe=504e2036d3) | Jan 29, 2022 |
| Dell          | Latitude E6220              | [808db5a1c8](https://linux-hardware.org/?probe=808db5a1c8) | Jan 29, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [95423d6649](https://linux-hardware.org/?probe=95423d6649) | Jan 28, 2022 |
| ASUSTek       | TAICHI21                    | [ccc3361d04](https://linux-hardware.org/?probe=ccc3361d04) | Jan 28, 2022 |
| Apple         | MacBookPro6,2               | [0143cbef50](https://linux-hardware.org/?probe=0143cbef50) | Jan 28, 2022 |
| ASUSTek       | TAICHI21                    | [6b9b9f727e](https://linux-hardware.org/?probe=6b9b9f727e) | Jan 28, 2022 |
| Jumper        | EZbook                      | [4fa449c0ce](https://linux-hardware.org/?probe=4fa449c0ce) | Jan 27, 2022 |
| Acer          | Aspire 5552                 | [ef57c29f8c](https://linux-hardware.org/?probe=ef57c29f8c) | Jan 27, 2022 |
| HP            | Pavilion dv7                | [927e580b5a](https://linux-hardware.org/?probe=927e580b5a) | Jan 26, 2022 |
| ASUSTek       | ROG Strix G513QR            | [fb81914651](https://linux-hardware.org/?probe=fb81914651) | Jan 26, 2022 |
| Lenovo        | ThinkPad X61 7673C44        | [ab461bd99e](https://linux-hardware.org/?probe=ab461bd99e) | Jan 26, 2022 |
| HP            | Pavilion dv7                | [c639bc4c98](https://linux-hardware.org/?probe=c639bc4c98) | Jan 25, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | [7078a1a373](https://linux-hardware.org/?probe=7078a1a373) | Jan 25, 2022 |
| Acer          | Aspire V3-571               | [ed5c6cf88d](https://linux-hardware.org/?probe=ed5c6cf88d) | Jan 24, 2022 |
| Lenovo        | ThinkPad T410s 292494G      | [cd8aef64e1](https://linux-hardware.org/?probe=cd8aef64e1) | Jan 24, 2022 |
| Toshiba       | Satellite C660              | [b3aec22953](https://linux-hardware.org/?probe=b3aec22953) | Jan 24, 2022 |
| ASUSTek       | ROG Strix G513QR            | [a31fd268eb](https://linux-hardware.org/?probe=a31fd268eb) | Jan 24, 2022 |
| ASUSTek       | X550CC                      | [5fa0a123f4](https://linux-hardware.org/?probe=5fa0a123f4) | Jan 24, 2022 |
| Dell          | Latitude E6420              | [1cf74dd114](https://linux-hardware.org/?probe=1cf74dd114) | Jan 23, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [06eb5b9d8d](https://linux-hardware.org/?probe=06eb5b9d8d) | Jan 23, 2022 |
| Toshiba       | TECRA A9                    | [7ba32a721d](https://linux-hardware.org/?probe=7ba32a721d) | Jan 23, 2022 |
| Acer          | NC-E1-572-54208G            | [02d40169ec](https://linux-hardware.org/?probe=02d40169ec) | Jan 23, 2022 |
| Clevo         | W24/250CU                   | [64c6f06849](https://linux-hardware.org/?probe=64c6f06849) | Jan 22, 2022 |
| ASUSTek       | T100TAS                     | [a37b7c51fd](https://linux-hardware.org/?probe=a37b7c51fd) | Jan 22, 2022 |
| HP            | Laptop 14q-cs0xxx           | [ec9061dcb1](https://linux-hardware.org/?probe=ec9061dcb1) | Jan 22, 2022 |
| Lenovo        | G780 20138                  | [4b5e81151e](https://linux-hardware.org/?probe=4b5e81151e) | Jan 22, 2022 |
| ASUSTek       | E200HA                      | [0d0222d2e9](https://linux-hardware.org/?probe=0d0222d2e9) | Jan 21, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [4c95ae549f](https://linux-hardware.org/?probe=4c95ae549f) | Jan 21, 2022 |
| Dell          | Latitude E5470              | [df22d71530](https://linux-hardware.org/?probe=df22d71530) | Jan 21, 2022 |
| HP            | EliteBook 820 G3            | [81cbc7d48a](https://linux-hardware.org/?probe=81cbc7d48a) | Jan 21, 2022 |
| HP            | EliteBook 820 G3            | [c56fbf1529](https://linux-hardware.org/?probe=c56fbf1529) | Jan 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [c996d7e988](https://linux-hardware.org/?probe=c996d7e988) | Jan 20, 2022 |
| HP            | Notebook                    | [25a9e6d8a1](https://linux-hardware.org/?probe=25a9e6d8a1) | Jan 20, 2022 |
| ASUSTek       | X540YA                      | [99ff6cb58a](https://linux-hardware.org/?probe=99ff6cb58a) | Jan 20, 2022 |
| HP            | Pavilion dv7                | [e22a47facd](https://linux-hardware.org/?probe=e22a47facd) | Jan 20, 2022 |
| Acer          | Aspire V5-571PG             | [19c732cd05](https://linux-hardware.org/?probe=19c732cd05) | Jan 20, 2022 |
| Multilaser    | UB32X                       | [bd6f4152df](https://linux-hardware.org/?probe=bd6f4152df) | Jan 20, 2022 |
| ASUSTek       | GL552VW                     | [4544642750](https://linux-hardware.org/?probe=4544642750) | Jan 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [81be3d94a3](https://linux-hardware.org/?probe=81be3d94a3) | Jan 18, 2022 |
| Acer          | Aspire ES1-531              | [d089029f6c](https://linux-hardware.org/?probe=d089029f6c) | Jan 18, 2022 |
| ASUSTek       | K93SV                       | [30f5830a2d](https://linux-hardware.org/?probe=30f5830a2d) | Jan 18, 2022 |
| ASUSTek       | T100TAS                     | [86df8cdba1](https://linux-hardware.org/?probe=86df8cdba1) | Jan 18, 2022 |
| Acer          | Predator G9-792             | [06a6edfaae](https://linux-hardware.org/?probe=06a6edfaae) | Jan 17, 2022 |
| HP            | 15                          | [4dde4c5c0e](https://linux-hardware.org/?probe=4dde4c5c0e) | Jan 17, 2022 |
| Google        | Ultima                      | [d942b9081b](https://linux-hardware.org/?probe=d942b9081b) | Jan 16, 2022 |
| HP            | 250 G4                      | [4de0cf1eb0](https://linux-hardware.org/?probe=4de0cf1eb0) | Jan 16, 2022 |
| Lenovo        | ThinkPad T460s 20FAS09Y0... | [339ea299c8](https://linux-hardware.org/?probe=339ea299c8) | Jan 16, 2022 |
| Acer          | Aspire A315-53              | [4bcdec655f](https://linux-hardware.org/?probe=4bcdec655f) | Jan 16, 2022 |
| Lenovo        | ThinkPad X230 2325WR3       | [decbecce89](https://linux-hardware.org/?probe=decbecce89) | Jan 16, 2022 |
| HP            | ProBook 445 G7              | [04e666772c](https://linux-hardware.org/?probe=04e666772c) | Jan 15, 2022 |
| HP            | OMEN by Laptop 15-dc1xxx    | [7136b51cd1](https://linux-hardware.org/?probe=7136b51cd1) | Jan 15, 2022 |
| Acer          | Aspire 5552                 | [5d3b462042](https://linux-hardware.org/?probe=5d3b462042) | Jan 14, 2022 |
| Lenovo        | ThinkPad T410s 292494G      | [df5d687786](https://linux-hardware.org/?probe=df5d687786) | Jan 14, 2022 |
| ASUSTek       | K52JT                       | [8545fedf93](https://linux-hardware.org/?probe=8545fedf93) | Jan 14, 2022 |
| ASUSTek       | X550CC                      | [0607e7f57e](https://linux-hardware.org/?probe=0607e7f57e) | Jan 14, 2022 |
| HP            | ProBook 640 G1              | [6261e290d6](https://linux-hardware.org/?probe=6261e290d6) | Jan 13, 2022 |
| ASUSTek       | GL552VW                     | [de99d855c5](https://linux-hardware.org/?probe=de99d855c5) | Jan 13, 2022 |
| Dell          | XPS 15 9510                 | [edb752adea](https://linux-hardware.org/?probe=edb752adea) | Jan 13, 2022 |
| ASUSTek       | K54C                        | [048477ec85](https://linux-hardware.org/?probe=048477ec85) | Jan 13, 2022 |
| ASUSTek       | TUF Gaming FX505DT_TUF50... | [b694d6fa5f](https://linux-hardware.org/?probe=b694d6fa5f) | Jan 13, 2022 |
| ASUSTek       | TUF Gaming FX505DT_TUF50... | [0f2222fc06](https://linux-hardware.org/?probe=0f2222fc06) | Jan 13, 2022 |
| Dell          | XPS 15 9510                 | [eb7e68d366](https://linux-hardware.org/?probe=eb7e68d366) | Jan 13, 2022 |
| Razer         | Blade Stealth               | [3e3430ddeb](https://linux-hardware.org/?probe=3e3430ddeb) | Jan 13, 2022 |
| Acer          | Aspire E5-774G              | [bd6fa29ee0](https://linux-hardware.org/?probe=bd6fa29ee0) | Jan 13, 2022 |
| Toshiba       | Satellite C660              | [a4b1346944](https://linux-hardware.org/?probe=a4b1346944) | Jan 13, 2022 |
| Mediacom      | GTZS                        | [ad6de0b39b](https://linux-hardware.org/?probe=ad6de0b39b) | Jan 12, 2022 |
| HP            | Laptop 15-dy2xxx            | [086b27dc7a](https://linux-hardware.org/?probe=086b27dc7a) | Jan 12, 2022 |
| HP            | Laptop 15-dy2xxx            | [c7e776c4f2](https://linux-hardware.org/?probe=c7e776c4f2) | Jan 12, 2022 |
| HP            | Laptop 15-dy2xxx            | [c16f448f2e](https://linux-hardware.org/?probe=c16f448f2e) | Jan 12, 2022 |
| HP            | Pavilion g6                 | [e14f742bb9](https://linux-hardware.org/?probe=e14f742bb9) | Jan 12, 2022 |
| HP            | Pavilion g6                 | [62f049acf1](https://linux-hardware.org/?probe=62f049acf1) | Jan 12, 2022 |
| ASUSTek       | X542BA                      | [d5180ebfbc](https://linux-hardware.org/?probe=d5180ebfbc) | Jan 12, 2022 |
| Lenovo        | G500 20236                  | [2e7bd2b772](https://linux-hardware.org/?probe=2e7bd2b772) | Jan 12, 2022 |
| Acer          | Predator G9-792             | [870f7b6ea5](https://linux-hardware.org/?probe=870f7b6ea5) | Jan 11, 2022 |
| Acer          | Predator G9-792             | [908edac358](https://linux-hardware.org/?probe=908edac358) | Jan 11, 2022 |
| Dell          | Vostro 1500                 | [d81572b40f](https://linux-hardware.org/?probe=d81572b40f) | Jan 11, 2022 |
| Lenovo        | IdeaPad 330-17ICH 81FL      | [4013d5dc28](https://linux-hardware.org/?probe=4013d5dc28) | Jan 11, 2022 |
| Lenovo        | IdeaPad Yoga 13 20175       | [3cd5068430](https://linux-hardware.org/?probe=3cd5068430) | Jan 10, 2022 |
| HP            | ProBook 6450b               | [73b06fa964](https://linux-hardware.org/?probe=73b06fa964) | Jan 10, 2022 |
| Lenovo        | V14-IIL 82C4                | [8fd207e668](https://linux-hardware.org/?probe=8fd207e668) | Jan 10, 2022 |
| Dell          | Latitude E6510              | [df2d1f8aa1](https://linux-hardware.org/?probe=df2d1f8aa1) | Jan 09, 2022 |
| HP            | Pavilion 15                 | [95f3d87b66](https://linux-hardware.org/?probe=95f3d87b66) | Jan 09, 2022 |
| HP            | Compaq 8510p                | [94c5350957](https://linux-hardware.org/?probe=94c5350957) | Jan 09, 2022 |
| ASUSTek       | K52JT                       | [c5d880e138](https://linux-hardware.org/?probe=c5d880e138) | Jan 09, 2022 |
| Unknown       | SCHNEIDER                   | [03b1f6dfed](https://linux-hardware.org/?probe=03b1f6dfed) | Jan 09, 2022 |
| ASUSTek       | GL552VW                     | [69a4959007](https://linux-hardware.org/?probe=69a4959007) | Jan 09, 2022 |
| ASUSTek       | X553MA                      | [cdf5230fdb](https://linux-hardware.org/?probe=cdf5230fdb) | Jan 09, 2022 |
| Samsung       | R59P/R60P/R61P              | [dd061ae267](https://linux-hardware.org/?probe=dd061ae267) | Jan 08, 2022 |
| HP            | Laptop 15s-du2xxx           | [e6c704567e](https://linux-hardware.org/?probe=e6c704567e) | Jan 08, 2022 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [95c067b96e](https://linux-hardware.org/?probe=95c067b96e) | Jan 07, 2022 |
| MSI           | GE75 Raider 8SF             | [23aab4b14f](https://linux-hardware.org/?probe=23aab4b14f) | Jan 06, 2022 |
| ASUSTek       | X542BP                      | [1f13c19485](https://linux-hardware.org/?probe=1f13c19485) | Jan 06, 2022 |
| Toshiba       | Satellite A200              | [613096a5ad](https://linux-hardware.org/?probe=613096a5ad) | Jan 06, 2022 |
| HP            | Laptop 15s-dr0xxx           | [be60e498db](https://linux-hardware.org/?probe=be60e498db) | Jan 06, 2022 |
| HP            | ProBook 4510s               | [cb983f7833](https://linux-hardware.org/?probe=cb983f7833) | Jan 06, 2022 |
| Dell          | Inspiron M5030              | [1715a3e584](https://linux-hardware.org/?probe=1715a3e584) | Jan 06, 2022 |
| Lenovo        | ThinkPad X250 20CLS03Y00    | [64d6a48fd3](https://linux-hardware.org/?probe=64d6a48fd3) | Jan 06, 2022 |
| Acer          | Aspire 7741                 | [2f03831c23](https://linux-hardware.org/?probe=2f03831c23) | Jan 05, 2022 |
| Acer          | E1-510                      | [f5a0998e25](https://linux-hardware.org/?probe=f5a0998e25) | Jan 05, 2022 |
| ASUSTek       | X555QG                      | [a10e6b5ec0](https://linux-hardware.org/?probe=a10e6b5ec0) | Jan 04, 2022 |
| Acer          | Aspire 6930G                | [929cea53e3](https://linux-hardware.org/?probe=929cea53e3) | Jan 04, 2022 |
| Dell          | Inspiron 1750               | [827adb411f](https://linux-hardware.org/?probe=827adb411f) | Jan 04, 2022 |
| Lenovo        | G50-70 20351                | [04b904c594](https://linux-hardware.org/?probe=04b904c594) | Jan 04, 2022 |
| NEC Comput... | PC-LL550RG                  | [43435578b7](https://linux-hardware.org/?probe=43435578b7) | Jan 04, 2022 |
| Toshiba       | TECRA A9                    | [783735cff8](https://linux-hardware.org/?probe=783735cff8) | Jan 04, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [9f6ca62b59](https://linux-hardware.org/?probe=9f6ca62b59) | Jan 04, 2022 |
| ASUSTek       | X555QG                      | [9062bc4b1d](https://linux-hardware.org/?probe=9062bc4b1d) | Jan 03, 2022 |
| Dell          | Inspiron 13-5378            | [8d019441d1](https://linux-hardware.org/?probe=8d019441d1) | Jan 03, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [22a9d41db0](https://linux-hardware.org/?probe=22a9d41db0) | Jan 02, 2022 |
| Dell          | Latitude E7440              | [9df6480d3e](https://linux-hardware.org/?probe=9df6480d3e) | Jan 02, 2022 |
| Toshiba       | Satellite C870-1C2          | [1d759e7171](https://linux-hardware.org/?probe=1d759e7171) | Jan 02, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [6100abe0e1](https://linux-hardware.org/?probe=6100abe0e1) | Jan 02, 2022 |
| Dell          | Latitude E7440              | [60b74121ad](https://linux-hardware.org/?probe=60b74121ad) | Jan 02, 2022 |
| Lenovo        | ThinkPad T490 20N3S6US00    | [087fbff7d6](https://linux-hardware.org/?probe=087fbff7d6) | Jan 02, 2022 |
| Dell          | Inspiron 5770               | [0e81199f2c](https://linux-hardware.org/?probe=0e81199f2c) | Jan 02, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [367ef74be3](https://linux-hardware.org/?probe=367ef74be3) | Jan 01, 2022 |
| Lenovo        | V14-IIL 82C4                | [7dcf51eb69](https://linux-hardware.org/?probe=7dcf51eb69) | Jan 01, 2022 |
| Lenovo        | ThinkPad T490 20N3S6US00    | [f748f15a80](https://linux-hardware.org/?probe=f748f15a80) | Jan 01, 2022 |
| Jumper        | EZbook                      | [aed28b71f9](https://linux-hardware.org/?probe=aed28b71f9) | Jan 01, 2022 |
| MSI           | EX705                       | [a969bd4369](https://linux-hardware.org/?probe=a969bd4369) | Dec 31, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [0bfa74fa9f](https://linux-hardware.org/?probe=0bfa74fa9f) | Dec 31, 2021 |
| HP            | EliteBook Folio 9470m       | [90d57a20ee](https://linux-hardware.org/?probe=90d57a20ee) | Dec 31, 2021 |
| HP            | EliteBook Folio 9470m       | [4db624e8a0](https://linux-hardware.org/?probe=4db624e8a0) | Dec 31, 2021 |
| HP            | EliteBook Folio 9470m       | [b79e118712](https://linux-hardware.org/?probe=b79e118712) | Dec 31, 2021 |
| MSI           | GE-700                      | [9ccf434539](https://linux-hardware.org/?probe=9ccf434539) | Dec 31, 2021 |
| MSI           | GE-700                      | [dd9998069e](https://linux-hardware.org/?probe=dd9998069e) | Dec 31, 2021 |
| Toshiba       | Satellite L300              | [fc547136cc](https://linux-hardware.org/?probe=fc547136cc) | Dec 31, 2021 |
| ASUSTek       | GL552VW                     | [42fd7ed22b](https://linux-hardware.org/?probe=42fd7ed22b) | Dec 31, 2021 |
| HP            | Pavilion dv5                | [7017ea359e](https://linux-hardware.org/?probe=7017ea359e) | Dec 31, 2021 |
| Acer          | Aspire 1810TZ               | [0b7bd5c1fa](https://linux-hardware.org/?probe=0b7bd5c1fa) | Dec 30, 2021 |
| MSI           | GT70 2OC/2OD                | [baefd0bda3](https://linux-hardware.org/?probe=baefd0bda3) | Dec 30, 2021 |
| Dell          | XPS 13 9370                 | [f20a77fa7e](https://linux-hardware.org/?probe=f20a77fa7e) | Dec 29, 2021 |
| Packard Be... | EasyNote TK85               | [cef3f4f826](https://linux-hardware.org/?probe=cef3f4f826) | Dec 28, 2021 |
| HP            | ProBook 4730s               | [08cca0b4b5](https://linux-hardware.org/?probe=08cca0b4b5) | Dec 28, 2021 |
| Lenovo        | ThinkPad L540 20AV0031MB    | [5abe6c6347](https://linux-hardware.org/?probe=5abe6c6347) | Dec 28, 2021 |
| ASUSTek       | X302LA                      | [3c747e6bb0](https://linux-hardware.org/?probe=3c747e6bb0) | Dec 28, 2021 |
| Dell          | Latitude 7490               | [044b1ea3d3](https://linux-hardware.org/?probe=044b1ea3d3) | Dec 28, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | [55b2c93259](https://linux-hardware.org/?probe=55b2c93259) | Dec 28, 2021 |
| Lenovo        | ThinkPad X201 Tablet 311... | [82c3a0ea01](https://linux-hardware.org/?probe=82c3a0ea01) | Dec 28, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [fa2df1f6f0](https://linux-hardware.org/?probe=fa2df1f6f0) | Dec 27, 2021 |
| MSI           | GT70 2OC/2OD                | [8445e5b6fe](https://linux-hardware.org/?probe=8445e5b6fe) | Dec 27, 2021 |
| Lenovo        | V14-IIL 82C4                | [b525e5f8c0](https://linux-hardware.org/?probe=b525e5f8c0) | Dec 27, 2021 |
| MSI           | GT70 2OC/2OD                | [624f5a11a8](https://linux-hardware.org/?probe=624f5a11a8) | Dec 27, 2021 |
| HP            | EliteBook 2760p             | [1cd129ee35](https://linux-hardware.org/?probe=1cd129ee35) | Dec 27, 2021 |
| HP            | EliteBook 2760p             | [f2deb9ec59](https://linux-hardware.org/?probe=f2deb9ec59) | Dec 27, 2021 |
| Dell          | Inspiron 3583               | [adcf14bf31](https://linux-hardware.org/?probe=adcf14bf31) | Dec 27, 2021 |
| Acer          | Aspire M5-481T              | [2515a869a5](https://linux-hardware.org/?probe=2515a869a5) | Dec 26, 2021 |
| Acer          | Aspire M5-481T              | [1ef9b940b2](https://linux-hardware.org/?probe=1ef9b940b2) | Dec 26, 2021 |
| Fusion5       | FWIN232_PLUS                | [ce10f25e8c](https://linux-hardware.org/?probe=ce10f25e8c) | Dec 25, 2021 |
| Dell          | Latitude 12 Rugged Table... | [13cc8e2abf](https://linux-hardware.org/?probe=13cc8e2abf) | Dec 25, 2021 |
| ASUSTek       | M50Vm                       | [bc36782a82](https://linux-hardware.org/?probe=bc36782a82) | Dec 25, 2021 |
| HP            | Pavilion dv7                | [67230f9226](https://linux-hardware.org/?probe=67230f9226) | Dec 25, 2021 |
| Dell          | Latitude 3440               | [e80fdcee0c](https://linux-hardware.org/?probe=e80fdcee0c) | Dec 25, 2021 |
| Toshiba       | TECRA S11                   | [b846fd9c93](https://linux-hardware.org/?probe=b846fd9c93) | Dec 24, 2021 |
| Dell          | Latitude 3540               | [7e7f291d68](https://linux-hardware.org/?probe=7e7f291d68) | Dec 24, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | [3415419b6b](https://linux-hardware.org/?probe=3415419b6b) | Dec 23, 2021 |
| Acer          | Aspire E1-531               | [d1d6054fc3](https://linux-hardware.org/?probe=d1d6054fc3) | Dec 22, 2021 |
| HP            | Pavilion dv7                | [5823ca14b0](https://linux-hardware.org/?probe=5823ca14b0) | Dec 22, 2021 |
| ASUSTek       | K53E                        | [0a089d38c0](https://linux-hardware.org/?probe=0a089d38c0) | Dec 21, 2021 |
| Sony          | VGN-FW21E                   | [0c58cd8d69](https://linux-hardware.org/?probe=0c58cd8d69) | Dec 20, 2021 |
| Sony          | VPCF23M1E                   | [a7e83ee775](https://linux-hardware.org/?probe=a7e83ee775) | Dec 20, 2021 |
| Sony          | VPCF23M1E                   | [f10ab27170](https://linux-hardware.org/?probe=f10ab27170) | Dec 20, 2021 |
| HP            | EliteBook 2570p             | [462b93b05b](https://linux-hardware.org/?probe=462b93b05b) | Dec 20, 2021 |
| Digibras      | NH4CU03                     | [517425552d](https://linux-hardware.org/?probe=517425552d) | Dec 19, 2021 |
| Sony          | VGN-FW21E                   | [d90a22e7b0](https://linux-hardware.org/?probe=d90a22e7b0) | Dec 19, 2021 |
| Acer          | Aspire V3-571               | [5189bf7726](https://linux-hardware.org/?probe=5189bf7726) | Dec 19, 2021 |
| ASUSTek       | X751LD                      | [2013d9d5d8](https://linux-hardware.org/?probe=2013d9d5d8) | Dec 19, 2021 |
| ASUSTek       | X751LD                      | [67286f0d11](https://linux-hardware.org/?probe=67286f0d11) | Dec 19, 2021 |
| Packard Be... | EasyNote TE11BZ             | [24fef50189](https://linux-hardware.org/?probe=24fef50189) | Dec 19, 2021 |
| HP            | EliteBook 8440p             | [0dc23e59a4](https://linux-hardware.org/?probe=0dc23e59a4) | Dec 19, 2021 |
| HP            | EliteBook 8440p             | [6eab2c603a](https://linux-hardware.org/?probe=6eab2c603a) | Dec 19, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [897b589a83](https://linux-hardware.org/?probe=897b589a83) | Dec 19, 2021 |
| ASUSTek       | K53SD                       | [68a3cbb84c](https://linux-hardware.org/?probe=68a3cbb84c) | Dec 18, 2021 |
| HP            | Laptop 15-db1xxx            | [20f9c7a4ef](https://linux-hardware.org/?probe=20f9c7a4ef) | Dec 18, 2021 |
| Toshiba       | Satellite C660              | [6f860db242](https://linux-hardware.org/?probe=6f860db242) | Dec 18, 2021 |
| Dell          | Latitude E6500              | [5a29db9bdf](https://linux-hardware.org/?probe=5a29db9bdf) | Dec 18, 2021 |
| Lenovo        | ThinkPad X230 2325SYU       | [3b01a9e8eb](https://linux-hardware.org/?probe=3b01a9e8eb) | Dec 18, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [dda5e17a21](https://linux-hardware.org/?probe=dda5e17a21) | Dec 17, 2021 |
| Toshiba       | TECRA A9                    | [53cba6b9d1](https://linux-hardware.org/?probe=53cba6b9d1) | Dec 16, 2021 |
| Login Info... | LOG-MB47II7                 | [58eb588f8b](https://linux-hardware.org/?probe=58eb588f8b) | Dec 16, 2021 |
| Login Info... | LOG-MB47II7                 | [84cabc70f7](https://linux-hardware.org/?probe=84cabc70f7) | Dec 16, 2021 |
| Compaq        | Presario 21                 | [86e7a85db3](https://linux-hardware.org/?probe=86e7a85db3) | Dec 16, 2021 |
| Toshiba       | QOSMIO X770                 | [c8c9ab4cf8](https://linux-hardware.org/?probe=c8c9ab4cf8) | Dec 16, 2021 |
| HP            | ZBook 17 G5                 | [761a2419e5](https://linux-hardware.org/?probe=761a2419e5) | Dec 16, 2021 |
| RCA           | WT9503W004                  | [c858eb3cbc](https://linux-hardware.org/?probe=c858eb3cbc) | Dec 15, 2021 |
| Dell          | Latitude E6400              | [dc0d35221e](https://linux-hardware.org/?probe=dc0d35221e) | Dec 15, 2021 |
| HP            | EliteBook 8730w             | [e35ce8395b](https://linux-hardware.org/?probe=e35ce8395b) | Dec 15, 2021 |
| HP            | ProBook 450 G3              | [d197761676](https://linux-hardware.org/?probe=d197761676) | Dec 15, 2021 |
| Google        | Squawks                     | [e75aa07dad](https://linux-hardware.org/?probe=e75aa07dad) | Dec 15, 2021 |
| Acer          | Aspire V3-571               | [071a8f0709](https://linux-hardware.org/?probe=071a8f0709) | Dec 15, 2021 |
| Dell          | Inspiron 3501               | [6cf66f6290](https://linux-hardware.org/?probe=6cf66f6290) | Dec 15, 2021 |
| Lenovo        | G580 20150                  | [6ff1581ca6](https://linux-hardware.org/?probe=6ff1581ca6) | Dec 14, 2021 |
| Acer          | AOD255                      | [08a007120e](https://linux-hardware.org/?probe=08a007120e) | Dec 14, 2021 |
| HP            | EliteBook Folio 9480m       | [11eea57427](https://linux-hardware.org/?probe=11eea57427) | Dec 14, 2021 |
| Toshiba       | Satellite L655              | [0db50aad32](https://linux-hardware.org/?probe=0db50aad32) | Dec 14, 2021 |
| Digibras      | NH4CU03                     | [97b0f21219](https://linux-hardware.org/?probe=97b0f21219) | Dec 14, 2021 |
| MSI           | PS42 Modern 8RC             | [2686d73cb8](https://linux-hardware.org/?probe=2686d73cb8) | Dec 13, 2021 |
| Lenovo        | ThinkPad X270 20HN0043AD    | [24160af893](https://linux-hardware.org/?probe=24160af893) | Dec 13, 2021 |
| Google        | Squawks                     | [31cb595893](https://linux-hardware.org/?probe=31cb595893) | Dec 13, 2021 |
| Digibras      | NH4CU03                     | [5ffb383677](https://linux-hardware.org/?probe=5ffb383677) | Dec 13, 2021 |
| Acer          | Aspire V3-571               | [54680bac44](https://linux-hardware.org/?probe=54680bac44) | Dec 12, 2021 |
| Dell          | Precision M4600             | [32034c26c7](https://linux-hardware.org/?probe=32034c26c7) | Dec 12, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [d364ff0c44](https://linux-hardware.org/?probe=d364ff0c44) | Dec 12, 2021 |
| HP            | ProBook 450 G3              | [54846cdc88](https://linux-hardware.org/?probe=54846cdc88) | Dec 12, 2021 |
| Dell          | Latitude E5410              | [8b6bc5cf8e](https://linux-hardware.org/?probe=8b6bc5cf8e) | Dec 12, 2021 |
| Apple         | MacBook4,1                  | [7bf355c3c1](https://linux-hardware.org/?probe=7bf355c3c1) | Dec 12, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [807bd77769](https://linux-hardware.org/?probe=807bd77769) | Dec 12, 2021 |
| Positivo      | CHT14B                      | [6ebdfd7b1f](https://linux-hardware.org/?probe=6ebdfd7b1f) | Dec 12, 2021 |
| Acer          | Aspire 4830T                | [554d2d7ce0](https://linux-hardware.org/?probe=554d2d7ce0) | Dec 12, 2021 |
| Acer          | Aspire 4830T                | [cbf04f6efb](https://linux-hardware.org/?probe=cbf04f6efb) | Dec 12, 2021 |
| Dell          | Precision M4600             | [f3f7be37a2](https://linux-hardware.org/?probe=f3f7be37a2) | Dec 12, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [0fb07d458a](https://linux-hardware.org/?probe=0fb07d458a) | Dec 12, 2021 |
| Acer          | Aspire A517-52              | [a51b1f9eb7](https://linux-hardware.org/?probe=a51b1f9eb7) | Dec 11, 2021 |
| Acer          | Aspire A517-52              | [bbf5c7ea28](https://linux-hardware.org/?probe=bbf5c7ea28) | Dec 11, 2021 |
| Dell          | Latitude E5400              | [2444de97e0](https://linux-hardware.org/?probe=2444de97e0) | Dec 11, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [a5528e8f98](https://linux-hardware.org/?probe=a5528e8f98) | Dec 11, 2021 |
| Chuwi         | GemiBook Pro                | [493d55cb16](https://linux-hardware.org/?probe=493d55cb16) | Dec 11, 2021 |
| TCL Commun... | 8085                        | [3d795ceee0](https://linux-hardware.org/?probe=3d795ceee0) | Dec 11, 2021 |
| Dell          | Latitude E5400              | [212020992c](https://linux-hardware.org/?probe=212020992c) | Dec 11, 2021 |
| HP            | Pavilion dv3                | [484e48a117](https://linux-hardware.org/?probe=484e48a117) | Dec 11, 2021 |
| HP            | 15 Notebook PC              | [3be4065d87](https://linux-hardware.org/?probe=3be4065d87) | Dec 10, 2021 |
| HP            | 15 Notebook PC              | [c06d1d8915](https://linux-hardware.org/?probe=c06d1d8915) | Dec 10, 2021 |
| Dell          | Latitude E7440              | [ff067012c5](https://linux-hardware.org/?probe=ff067012c5) | Dec 09, 2021 |
| Samsung       | N150P/N210P/N220P           | [eed2dcde15](https://linux-hardware.org/?probe=eed2dcde15) | Dec 09, 2021 |
| Apple         | MacBook4,1                  | [cfa6005bc4](https://linux-hardware.org/?probe=cfa6005bc4) | Dec 09, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [dc07419c59](https://linux-hardware.org/?probe=dc07419c59) | Dec 08, 2021 |
| Dell          | Latitude E5400              | [a4fa2f67d3](https://linux-hardware.org/?probe=a4fa2f67d3) | Dec 08, 2021 |
| Lenovo        | ThinkPad T400 741722U       | [2739940ec1](https://linux-hardware.org/?probe=2739940ec1) | Dec 08, 2021 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | [c31f062314](https://linux-hardware.org/?probe=c31f062314) | Dec 07, 2021 |
| HP            | HDX 16                      | [cf114f9094](https://linux-hardware.org/?probe=cf114f9094) | Dec 07, 2021 |
| Unknown       | Unknown                     | [9e9e0598b6](https://linux-hardware.org/?probe=9e9e0598b6) | Dec 07, 2021 |
| HP            | Stream Laptop 14-cb1XX      | [4853c251a8](https://linux-hardware.org/?probe=4853c251a8) | Dec 07, 2021 |
| Apple         | MacBookPro8,1               | [85d594af54](https://linux-hardware.org/?probe=85d594af54) | Dec 07, 2021 |
| Razer         | Blade 15 Base Model (Ear... | [9c64eb115e](https://linux-hardware.org/?probe=9c64eb115e) | Dec 07, 2021 |
| Lenovo        | ThinkPad T400 741722U       | [2933ad8c69](https://linux-hardware.org/?probe=2933ad8c69) | Dec 07, 2021 |
| Dell          | Inspiron 5748               | [77f278682e](https://linux-hardware.org/?probe=77f278682e) | Dec 06, 2021 |
| Apple         | MacBookPro11,1              | [f454c30e46](https://linux-hardware.org/?probe=f454c30e46) | Dec 05, 2021 |
| Acer          | Aspire V3-571G              | [3acb23e27c](https://linux-hardware.org/?probe=3acb23e27c) | Dec 05, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [fc540c3951](https://linux-hardware.org/?probe=fc540c3951) | Dec 05, 2021 |
| Dell          | Inspiron 5770               | [c8a717a1c9](https://linux-hardware.org/?probe=c8a717a1c9) | Dec 05, 2021 |
| ASUSTek       | X553MA                      | [958551b7eb](https://linux-hardware.org/?probe=958551b7eb) | Dec 05, 2021 |
| Sony          | SVF1532Z1EB                 | [d65626b69d](https://linux-hardware.org/?probe=d65626b69d) | Dec 04, 2021 |
| ASUSTek       | X553MA                      | [78414b8bc4](https://linux-hardware.org/?probe=78414b8bc4) | Dec 04, 2021 |
| Lenovo        | G700                        | [2b7a430fcd](https://linux-hardware.org/?probe=2b7a430fcd) | Dec 04, 2021 |
| Toshiba       | Satellite C660              | [4d64247a8a](https://linux-hardware.org/?probe=4d64247a8a) | Dec 04, 2021 |
| ASUSTek       | K53TK                       | [043ef58552](https://linux-hardware.org/?probe=043ef58552) | Dec 03, 2021 |
| HUAWEI        | KLVL-WXX9                   | [6c468accc0](https://linux-hardware.org/?probe=6c468accc0) | Dec 03, 2021 |
| HUAWEI        | KLVL-WXX9                   | [ee27adb248](https://linux-hardware.org/?probe=ee27adb248) | Dec 03, 2021 |
| Acer          | Aspire A315-58G             | [48e3c0e6c7](https://linux-hardware.org/?probe=48e3c0e6c7) | Dec 03, 2021 |
| HP            | OMEN Notebook               | [5b8b235c98](https://linux-hardware.org/?probe=5b8b235c98) | Dec 03, 2021 |
| Samsung       | 700T                        | [efe2d4bd92](https://linux-hardware.org/?probe=efe2d4bd92) | Dec 03, 2021 |
| Dell          | Latitude E6530              | [fe6dbdef48](https://linux-hardware.org/?probe=fe6dbdef48) | Dec 03, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [29ff3edb05](https://linux-hardware.org/?probe=29ff3edb05) | Dec 03, 2021 |
| Toshiba       | Satellite L655              | [0e3a82aad6](https://linux-hardware.org/?probe=0e3a82aad6) | Dec 03, 2021 |
| HUAWEI        | KLVL-WXX9                   | [c806323840](https://linux-hardware.org/?probe=c806323840) | Dec 03, 2021 |
| Dell          | Latitude 7280               | [8baf21a38d](https://linux-hardware.org/?probe=8baf21a38d) | Dec 02, 2021 |
| HUAWEI        | KLVL-WXX9                   | [57b4dae376](https://linux-hardware.org/?probe=57b4dae376) | Dec 02, 2021 |
| HP            | 15                          | [8d1ef12e0e](https://linux-hardware.org/?probe=8d1ef12e0e) | Dec 02, 2021 |
| HP            | ProBook 450 G3              | [ca49dc0eee](https://linux-hardware.org/?probe=ca49dc0eee) | Dec 02, 2021 |
| HP            | 15                          | [b374916ca6](https://linux-hardware.org/?probe=b374916ca6) | Dec 02, 2021 |
| Toshiba       | Satellite L55-B             | [0bc52401f0](https://linux-hardware.org/?probe=0bc52401f0) | Dec 02, 2021 |
| mPTech        | ARC 11.6 128GB HD           | [cb2302b704](https://linux-hardware.org/?probe=cb2302b704) | Dec 02, 2021 |
| mPTech        | ARC 11.6 128GB HD           | [f580be444b](https://linux-hardware.org/?probe=f580be444b) | Dec 02, 2021 |
| mPTech        | ARC 11.6 128GB HD           | [e2fbd06e2a](https://linux-hardware.org/?probe=e2fbd06e2a) | Dec 02, 2021 |
| TUXEDO        | Pulse 14 Gen1               | [c7eeb775f9](https://linux-hardware.org/?probe=c7eeb775f9) | Dec 02, 2021 |
| HP            | 15                          | [cb278b1a6b](https://linux-hardware.org/?probe=cb278b1a6b) | Dec 02, 2021 |
| Dell          | Latitude E5570              | [d7beab52f4](https://linux-hardware.org/?probe=d7beab52f4) | Dec 02, 2021 |
| Avell High... | B.ON                        | [a7513f22ee](https://linux-hardware.org/?probe=a7513f22ee) | Dec 02, 2021 |
| Primux        | 15R5A                       | [3aef7d25e8](https://linux-hardware.org/?probe=3aef7d25e8) | Dec 01, 2021 |
| ASUSTek       | X751LAB                     | [4383b601f4](https://linux-hardware.org/?probe=4383b601f4) | Nov 30, 2021 |
| MSI           | GF63 Thin 10SC              | [5f908f227a](https://linux-hardware.org/?probe=5f908f227a) | Nov 30, 2021 |
| HP            | EliteBook 8440p             | [cecc697189](https://linux-hardware.org/?probe=cecc697189) | Nov 30, 2021 |
| Dell          | Inspiron 15-3567            | [3a2bf12582](https://linux-hardware.org/?probe=3a2bf12582) | Nov 29, 2021 |
| ASUSTek       | TUF Gaming FX705GM_FX705... | [7184635417](https://linux-hardware.org/?probe=7184635417) | Nov 29, 2021 |
| Dell          | Latitude 7275               | [bf808d506c](https://linux-hardware.org/?probe=bf808d506c) | Nov 29, 2021 |
| Chuwi         | GemiBook                    | [911b855817](https://linux-hardware.org/?probe=911b855817) | Nov 28, 2021 |
| Chuwi         | GemiBook                    | [b8f87029fa](https://linux-hardware.org/?probe=b8f87029fa) | Nov 28, 2021 |
| Dell          | Latitude E5420              | [9f504b4e6b](https://linux-hardware.org/?probe=9f504b4e6b) | Nov 28, 2021 |
| ASUSTek       | P453UJ                      | [056cba6efd](https://linux-hardware.org/?probe=056cba6efd) | Nov 28, 2021 |
| ASUSTek       | X455LJ                      | [018d5bcbac](https://linux-hardware.org/?probe=018d5bcbac) | Nov 27, 2021 |
| Acer          | Aspire 4830T                | [205025f3c7](https://linux-hardware.org/?probe=205025f3c7) | Nov 27, 2021 |
| Acer          | Aspire A315-42              | [a0483c5539](https://linux-hardware.org/?probe=a0483c5539) | Nov 27, 2021 |
| Toshiba       | Satellite L500              | [24645f6ab5](https://linux-hardware.org/?probe=24645f6ab5) | Nov 26, 2021 |
| ASUSTek       | Zephyrus M GU502GW_GU502... | [25e2834604](https://linux-hardware.org/?probe=25e2834604) | Nov 25, 2021 |
| Acer          | Aspire 4830T                | [757863f7de](https://linux-hardware.org/?probe=757863f7de) | Nov 25, 2021 |
| Notebook      | NH50_70RA                   | [baa1c5d2ca](https://linux-hardware.org/?probe=baa1c5d2ca) | Nov 24, 2021 |
| HP            | Elite x2 1012 G1            | [5e2d2a574d](https://linux-hardware.org/?probe=5e2d2a574d) | Nov 24, 2021 |
| Lenovo        | Flex 2-14 20404             | [74894434bb](https://linux-hardware.org/?probe=74894434bb) | Nov 24, 2021 |
| ASUSTek       | GL552VW                     | [77929060f7](https://linux-hardware.org/?probe=77929060f7) | Nov 24, 2021 |
| Sony          | SVE1713Y1EB                 | [755b7b85f5](https://linux-hardware.org/?probe=755b7b85f5) | Nov 24, 2021 |
| HP            | EliteBook 8460p             | [ca30b13118](https://linux-hardware.org/?probe=ca30b13118) | Nov 24, 2021 |
| HP            | EliteBook 8570p             | [6c08986736](https://linux-hardware.org/?probe=6c08986736) | Nov 24, 2021 |
| Acer          | Okinawa                     | [2953f32ed9](https://linux-hardware.org/?probe=2953f32ed9) | Nov 23, 2021 |
| HP            | Pavilion 17                 | [315037ddfd](https://linux-hardware.org/?probe=315037ddfd) | Nov 23, 2021 |
| Sony          | VPCSA3N9E                   | [33a3597313](https://linux-hardware.org/?probe=33a3597313) | Nov 23, 2021 |
| Sony          | VPCSA3N9E                   | [c1bf05d67a](https://linux-hardware.org/?probe=c1bf05d67a) | Nov 23, 2021 |
| ASUSTek       | GL552VW                     | [59670a3933](https://linux-hardware.org/?probe=59670a3933) | Nov 23, 2021 |
| Lenovo        | IdeaPad Yoga 13 20175       | [56ff76e064](https://linux-hardware.org/?probe=56ff76e064) | Nov 23, 2021 |
| ASUSTek       | G750JX                      | [f503f26e28](https://linux-hardware.org/?probe=f503f26e28) | Nov 23, 2021 |
| HP            | Pavilion dv7                | [fa2ac7c179](https://linux-hardware.org/?probe=fa2ac7c179) | Nov 23, 2021 |
| Lenovo        | G580 20150                  | [baade6ba54](https://linux-hardware.org/?probe=baade6ba54) | Nov 22, 2021 |
| Lenovo        | G580 20150                  | [b7718027af](https://linux-hardware.org/?probe=b7718027af) | Nov 22, 2021 |
| HP            | 15                          | [1753404669](https://linux-hardware.org/?probe=1753404669) | Nov 22, 2021 |
| HP            | Notebook                    | [9e9ce14e95](https://linux-hardware.org/?probe=9e9ce14e95) | Nov 22, 2021 |
| ASUSTek       | X751SA                      | [d19fd8c59f](https://linux-hardware.org/?probe=d19fd8c59f) | Nov 22, 2021 |
| Toshiba       | Satellite L500              | [30bfdcb5ff](https://linux-hardware.org/?probe=30bfdcb5ff) | Nov 22, 2021 |
| HP            | ENVY TS 15                  | [ca6e82745c](https://linux-hardware.org/?probe=ca6e82745c) | Nov 22, 2021 |
| Fujitsu Si... | AMILO Pa 1510               | [9f731acb7e](https://linux-hardware.org/?probe=9f731acb7e) | Nov 22, 2021 |
| HP            | 15                          | [bca58eb5e0](https://linux-hardware.org/?probe=bca58eb5e0) | Nov 22, 2021 |
| Apple         | MacBookPro5,3               | [5a4e91eace](https://linux-hardware.org/?probe=5a4e91eace) | Nov 22, 2021 |
| ASUSTek       | U56E                        | [2b347f1923](https://linux-hardware.org/?probe=2b347f1923) | Nov 22, 2021 |
| Lenovo        | G560 0679                   | [15348ebbf9](https://linux-hardware.org/?probe=15348ebbf9) | Nov 22, 2021 |
| HP            | Pavilion 15                 | [0f1442bb2c](https://linux-hardware.org/?probe=0f1442bb2c) | Nov 22, 2021 |
| Toshiba       | PORTEGE R705                | [47688cd36a](https://linux-hardware.org/?probe=47688cd36a) | Nov 21, 2021 |
| Toshiba       | Satellite U300              | [827ec6ed62](https://linux-hardware.org/?probe=827ec6ed62) | Nov 21, 2021 |
| HP            | Pavilion dv7                | [7c745f9e5a](https://linux-hardware.org/?probe=7c745f9e5a) | Nov 21, 2021 |
| HP            | ENVY Notebook               | [09767edae3](https://linux-hardware.org/?probe=09767edae3) | Nov 21, 2021 |
| Dell          | Latitude E6440              | [babff23db6](https://linux-hardware.org/?probe=babff23db6) | Nov 21, 2021 |
| Dell          | G7 7700                     | [730daa1080](https://linux-hardware.org/?probe=730daa1080) | Nov 21, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6505        | [c99c5700f6](https://linux-hardware.org/?probe=c99c5700f6) | Nov 20, 2021 |
| HP            | Pavilion Notebook           | [ca1ccc6e65](https://linux-hardware.org/?probe=ca1ccc6e65) | Nov 20, 2021 |
| ASUSTek       | K53U                        | [12136b1cbd](https://linux-hardware.org/?probe=12136b1cbd) | Nov 20, 2021 |
| HP            | Pavilion 15                 | [687ecf1c58](https://linux-hardware.org/?probe=687ecf1c58) | Nov 20, 2021 |
| Sony          | SVE1713D1EW                 | [20d3ee7401](https://linux-hardware.org/?probe=20d3ee7401) | Nov 20, 2021 |
| ASUSTek       | K53U                        | [5a5b8c420f](https://linux-hardware.org/?probe=5a5b8c420f) | Nov 20, 2021 |
| Dell          | Latitude E7440              | [89fdff42c1](https://linux-hardware.org/?probe=89fdff42c1) | Nov 20, 2021 |
| Dell          | Precision M6700             | [a8bf3915fb](https://linux-hardware.org/?probe=a8bf3915fb) | Nov 20, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | [7ddd35d3e8](https://linux-hardware.org/?probe=7ddd35d3e8) | Nov 20, 2021 |
| Sony          | SVE1713Y1EB                 | [4a77a751d9](https://linux-hardware.org/?probe=4a77a751d9) | Nov 20, 2021 |
| Toshiba       | Satellite C50D-B            | [6c92d7fef6](https://linux-hardware.org/?probe=6c92d7fef6) | Nov 19, 2021 |
| Dell          | Latitude E5550              | [2f52aa274c](https://linux-hardware.org/?probe=2f52aa274c) | Nov 19, 2021 |
| LG Electro... | S460-G.BG31P1               | [96d8266022](https://linux-hardware.org/?probe=96d8266022) | Nov 19, 2021 |
| Sony          | SVE1713D1EW                 | [cf21ed12bc](https://linux-hardware.org/?probe=cf21ed12bc) | Nov 18, 2021 |
| Lenovo        | ThinkPad X260 20F5S1GW1Q    | [3b8a61e460](https://linux-hardware.org/?probe=3b8a61e460) | Nov 18, 2021 |
| Google        | Lars                        | [c346746b7e](https://linux-hardware.org/?probe=c346746b7e) | Nov 18, 2021 |
| Dell          | Latitude 5590               | [8bef1790bd](https://linux-hardware.org/?probe=8bef1790bd) | Nov 18, 2021 |
| Toshiba       | Satellite C870-1C2          | [e3e16a0c1f](https://linux-hardware.org/?probe=e3e16a0c1f) | Nov 17, 2021 |
| Acer          | TravelMate 6292             | [2cec3b7547](https://linux-hardware.org/?probe=2cec3b7547) | Nov 17, 2021 |
| HP            | ENVY m7 Notebook            | [4b101cc132](https://linux-hardware.org/?probe=4b101cc132) | Nov 17, 2021 |
| HP            | Stream Notebook PC 14       | [31499aa79d](https://linux-hardware.org/?probe=31499aa79d) | Nov 17, 2021 |
| HP            | Stream Notebook PC 14       | [8c30001e99](https://linux-hardware.org/?probe=8c30001e99) | Nov 17, 2021 |
| Dell          | Precision M6700             | [fb4051d1de](https://linux-hardware.org/?probe=fb4051d1de) | Nov 17, 2021 |
| Lenovo        | ThinkPad T430 23445PU       | [e5fe64db56](https://linux-hardware.org/?probe=e5fe64db56) | Nov 16, 2021 |
| Toshiba       | Satellite C655D             | [cd8abc5170](https://linux-hardware.org/?probe=cd8abc5170) | Nov 16, 2021 |
| HP            | Compaq 8710p (GC102EA#AB... | [bfef77542f](https://linux-hardware.org/?probe=bfef77542f) | Nov 15, 2021 |
| Samsung       | 900X3C/900X3D/900X4C/900... | [76b69deb69](https://linux-hardware.org/?probe=76b69deb69) | Nov 14, 2021 |
| ASUSTek       | Vivobook_ASUSLaptop M350... | [3a3f503917](https://linux-hardware.org/?probe=3a3f503917) | Nov 14, 2021 |
| HP            | Notebook                    | [226dc7dc39](https://linux-hardware.org/?probe=226dc7dc39) | Nov 12, 2021 |
| HP            | Notebook                    | [c03f407f50](https://linux-hardware.org/?probe=c03f407f50) | Nov 12, 2021 |
| HP            | Notebook                    | [a2bae8d4b8](https://linux-hardware.org/?probe=a2bae8d4b8) | Nov 12, 2021 |
| HP            | Notebook                    | [87dec3cf7c](https://linux-hardware.org/?probe=87dec3cf7c) | Nov 12, 2021 |
| HP            | EliteBook 2560p             | [e3997c3bcb](https://linux-hardware.org/?probe=e3997c3bcb) | Nov 12, 2021 |
| Dell          | Inspiron 15-3567            | [e8879e98df](https://linux-hardware.org/?probe=e8879e98df) | Nov 12, 2021 |
| Google        | Kindred                     | [0046ef8942](https://linux-hardware.org/?probe=0046ef8942) | Nov 12, 2021 |
| Google        | Kindred                     | [9d72c8972c](https://linux-hardware.org/?probe=9d72c8972c) | Nov 12, 2021 |
| Acer          | Aspire 4830T                | [9ae2c69b2a](https://linux-hardware.org/?probe=9ae2c69b2a) | Nov 12, 2021 |
| Dell          | Precision M6700             | [9bf18c23c6](https://linux-hardware.org/?probe=9bf18c23c6) | Nov 12, 2021 |
| Notebook      | N85_N87HCHNHZ               | [32988fae95](https://linux-hardware.org/?probe=32988fae95) | Nov 11, 2021 |
| Lenovo        | IdeaPad 300-17ISK 80QH      | [c948868090](https://linux-hardware.org/?probe=c948868090) | Nov 11, 2021 |
| Dell          | Inspiron 1750               | [6ffff20ec8](https://linux-hardware.org/?probe=6ffff20ec8) | Nov 11, 2021 |
| Sony          | SVF14211CLB                 | [7c0dacdd54](https://linux-hardware.org/?probe=7c0dacdd54) | Nov 10, 2021 |
| HUAWEI        | BOHB-WAX9                   | [3b1f90f3ab](https://linux-hardware.org/?probe=3b1f90f3ab) | Nov 10, 2021 |
| HUAWEI        | BOHB-WAX9                   | [3858faa240](https://linux-hardware.org/?probe=3858faa240) | Nov 10, 2021 |
| Sony          | SVF14211CLB                 | [fdfd650fcc](https://linux-hardware.org/?probe=fdfd650fcc) | Nov 10, 2021 |
| Lenovo        | IdeaPad Yoga 13 20175       | [94da614270](https://linux-hardware.org/?probe=94da614270) | Nov 10, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6505        | [72dd15e9c5](https://linux-hardware.org/?probe=72dd15e9c5) | Nov 10, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [0d017f9835](https://linux-hardware.org/?probe=0d017f9835) | Nov 10, 2021 |
| ASUSTek       | U46E                        | [d52a43c7fd](https://linux-hardware.org/?probe=d52a43c7fd) | Nov 10, 2021 |
| Dell          | Latitude 3440               | [eb76b9d1cf](https://linux-hardware.org/?probe=eb76b9d1cf) | Nov 09, 2021 |
| HP            | Pavilion dv6                | [605479abf7](https://linux-hardware.org/?probe=605479abf7) | Nov 08, 2021 |
| HP            | Pavilion dv6                | [b7a410c2e6](https://linux-hardware.org/?probe=b7a410c2e6) | Nov 08, 2021 |
| MSI           | GF63 Thin 9SC               | [d85e7a0ad3](https://linux-hardware.org/?probe=d85e7a0ad3) | Nov 07, 2021 |
| Dell          | Latitude E5420              | [b53c6bd6d2](https://linux-hardware.org/?probe=b53c6bd6d2) | Nov 07, 2021 |
| Acer          | Swift SF314-56G             | [bf298c7d2d](https://linux-hardware.org/?probe=bf298c7d2d) | Nov 07, 2021 |
| Lenovo        | IdeaPad 300-17ISK 80QH      | [520a472266](https://linux-hardware.org/?probe=520a472266) | Nov 07, 2021 |
| HP            | Compaq 8510p                | [ddecc261a1](https://linux-hardware.org/?probe=ddecc261a1) | Nov 07, 2021 |
| HP            | Compaq 8510p                | [c2434c1c08](https://linux-hardware.org/?probe=c2434c1c08) | Nov 07, 2021 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [a0d13572a5](https://linux-hardware.org/?probe=a0d13572a5) | Nov 06, 2021 |
| HP            | Laptop 15-bw0xx             | [746f64d20b](https://linux-hardware.org/?probe=746f64d20b) | Nov 06, 2021 |
| HP            | Laptop 15-bw0xx             | [245941966f](https://linux-hardware.org/?probe=245941966f) | Nov 06, 2021 |
| Sony          | SVE1713D1EW                 | [64fd6b328f](https://linux-hardware.org/?probe=64fd6b328f) | Nov 06, 2021 |
| Sony          | SVE1713D1EW                 | [45609f28be](https://linux-hardware.org/?probe=45609f28be) | Nov 06, 2021 |
| HP            | Compaq 6710b (KE121ET#AB... | [5d577f71a4](https://linux-hardware.org/?probe=5d577f71a4) | Nov 06, 2021 |
| HP            | Compaq 6710b (KE121ET#AB... | [c37780e9ad](https://linux-hardware.org/?probe=c37780e9ad) | Nov 06, 2021 |
| ASUSTek       | K53TA                       | [e924b214bc](https://linux-hardware.org/?probe=e924b214bc) | Nov 06, 2021 |
| Acer          | Aspire ES1-521              | [5ef4af5924](https://linux-hardware.org/?probe=5ef4af5924) | Nov 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [73b5ea9e0b](https://linux-hardware.org/?probe=73b5ea9e0b) | Nov 06, 2021 |
| HP            | ProBook 450 G4              | [a96a96d455](https://linux-hardware.org/?probe=a96a96d455) | Nov 05, 2021 |
| ASUSTek       | K45A                        | [f9bc7efe7b](https://linux-hardware.org/?probe=f9bc7efe7b) | Nov 05, 2021 |
| ASUSTek       | K45A                        | [096deec12d](https://linux-hardware.org/?probe=096deec12d) | Nov 05, 2021 |
| Sony          | VPCEG23EL                   | [cc967c03fb](https://linux-hardware.org/?probe=cc967c03fb) | Nov 05, 2021 |
| Acer          | Swift SF314-54              | [b506625dc2](https://linux-hardware.org/?probe=b506625dc2) | Nov 05, 2021 |
| ASUSTek       | X751NV                      | [ecf08805fe](https://linux-hardware.org/?probe=ecf08805fe) | Nov 03, 2021 |
| Dell          | Precision M6700             | [1865ed7cca](https://linux-hardware.org/?probe=1865ed7cca) | Nov 03, 2021 |
| Dell          | Latitude 5490               | [c5c1f555f1](https://linux-hardware.org/?probe=c5c1f555f1) | Nov 03, 2021 |
| HP            | Compaq 8710p (GC102EA#AB... | [9e7a883a59](https://linux-hardware.org/?probe=9e7a883a59) | Nov 03, 2021 |
| HP            | Notebook                    | [ee3bc3deef](https://linux-hardware.org/?probe=ee3bc3deef) | Nov 02, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [3acc230d6a](https://linux-hardware.org/?probe=3acc230d6a) | Nov 02, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [c88adaac6e](https://linux-hardware.org/?probe=c88adaac6e) | Nov 02, 2021 |
| Lenovo        | ThinkPad T430 2349ED5       | [0697993e7c](https://linux-hardware.org/?probe=0697993e7c) | Nov 02, 2021 |
| Lenovo        | IdeaPad Z580                | [0f9c8eb860](https://linux-hardware.org/?probe=0f9c8eb860) | Nov 02, 2021 |
| Toshiba       | Satellite C870-1C2          | [7e5a2d91f8](https://linux-hardware.org/?probe=7e5a2d91f8) | Nov 02, 2021 |
| HP            | ProBook 440 G4              | [695b9a4e0c](https://linux-hardware.org/?probe=695b9a4e0c) | Nov 01, 2021 |
| HP            | ProBook 440 G4              | [4bba4734e8](https://linux-hardware.org/?probe=4bba4734e8) | Nov 01, 2021 |
| Dell          | XPS 15 9510                 | [9ad082f18e](https://linux-hardware.org/?probe=9ad082f18e) | Nov 01, 2021 |
| ASUSTek       | K52Jc                       | [dfb687f14d](https://linux-hardware.org/?probe=dfb687f14d) | Nov 01, 2021 |
| HP            | 255 G8 Notebook PC          | [600b7b9957](https://linux-hardware.org/?probe=600b7b9957) | Nov 01, 2021 |
| Acer          | Aspire E1-522               | [56b475a93d](https://linux-hardware.org/?probe=56b475a93d) | Nov 01, 2021 |
| Toshiba       | Satellite Pro T110          | [3ae7a19459](https://linux-hardware.org/?probe=3ae7a19459) | Oct 31, 2021 |
| ASUSTek       | N61Ja                       | [e3fc4e0622](https://linux-hardware.org/?probe=e3fc4e0622) | Oct 31, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [83d642714b](https://linux-hardware.org/?probe=83d642714b) | Oct 31, 2021 |
| Apple         | MacBookPro11,2              | [eabb3946ad](https://linux-hardware.org/?probe=eabb3946ad) | Oct 31, 2021 |
| ASUSTek       | N61Ja                       | [3861fce83e](https://linux-hardware.org/?probe=3861fce83e) | Oct 31, 2021 |
| Apple         | MacBookPro11,2              | [2388e68622](https://linux-hardware.org/?probe=2388e68622) | Oct 31, 2021 |
| Dell          | Inspiron 7720               | [9f298535a5](https://linux-hardware.org/?probe=9f298535a5) | Oct 31, 2021 |
| HP            | 255 G8 Notebook PC          | [cb9c15cf6f](https://linux-hardware.org/?probe=cb9c15cf6f) | Oct 30, 2021 |
| Dell          | Latitude E6500              | [e475348b1e](https://linux-hardware.org/?probe=e475348b1e) | Oct 30, 2021 |
| MECER         | Z140C+Home                  | [2fbf6f153b](https://linux-hardware.org/?probe=2fbf6f153b) | Oct 30, 2021 |
| HP            | Pavilion Notebook           | [85a55f5c3c](https://linux-hardware.org/?probe=85a55f5c3c) | Oct 30, 2021 |
| Lenovo        | IdeaPad Z580                | [16ebdc4388](https://linux-hardware.org/?probe=16ebdc4388) | Oct 30, 2021 |
| Lenovo        | IdeaPad Z580                | [6260be6de5](https://linux-hardware.org/?probe=6260be6de5) | Oct 30, 2021 |
| HP            | Pavilion Laptop 14-dv0xx... | [af0a995721](https://linux-hardware.org/?probe=af0a995721) | Oct 30, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [88286c36e9](https://linux-hardware.org/?probe=88286c36e9) | Oct 29, 2021 |
| Acer          | Aspire A315-21              | [f5f4e2457b](https://linux-hardware.org/?probe=f5f4e2457b) | Oct 29, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [c74557d180](https://linux-hardware.org/?probe=c74557d180) | Oct 29, 2021 |
| Acer          | Aspire A315-21              | [35b5fcb787](https://linux-hardware.org/?probe=35b5fcb787) | Oct 28, 2021 |
| ASUSTek       | N71Jv                       | [29e3747e17](https://linux-hardware.org/?probe=29e3747e17) | Oct 28, 2021 |
| ASUSTek       | X750JB                      | [90fd9f38fc](https://linux-hardware.org/?probe=90fd9f38fc) | Oct 27, 2021 |
| Lenovo        | G570 4334                   | [cc07ebf9b6](https://linux-hardware.org/?probe=cc07ebf9b6) | Oct 27, 2021 |
| HP            | EliteBook 8440p             | [f527983cc9](https://linux-hardware.org/?probe=f527983cc9) | Oct 27, 2021 |
| Toshiba       | PORTEGE Z20t-C              | [ed1722174a](https://linux-hardware.org/?probe=ed1722174a) | Oct 27, 2021 |
| Lenovo        | Legion Y920-17IKB Laptop... | [830d4c9d9d](https://linux-hardware.org/?probe=830d4c9d9d) | Oct 26, 2021 |
| Acer          | Aspire 5737Z                | [9bbf3befab](https://linux-hardware.org/?probe=9bbf3befab) | Oct 26, 2021 |
| Lenovo        | ThinkPad T520 4242W4F       | [4104e265ea](https://linux-hardware.org/?probe=4104e265ea) | Oct 26, 2021 |
| Notebook      | W94_95_97SU2,SUY,-C,-T      | [3da20846f5](https://linux-hardware.org/?probe=3da20846f5) | Oct 26, 2021 |
| Notebook      | W94_95_97SU2,SUY,-C,-T      | [2d19155e7f](https://linux-hardware.org/?probe=2d19155e7f) | Oct 26, 2021 |
| Fujitsu       | LIFEBOOK AH530              | [ed4e9d1a03](https://linux-hardware.org/?probe=ed4e9d1a03) | Oct 26, 2021 |
| Fujitsu       | LIFEBOOK AH530              | [f5b1e904b7](https://linux-hardware.org/?probe=f5b1e904b7) | Oct 26, 2021 |
| HP            | ProBook 445 G7              | [87b3274937](https://linux-hardware.org/?probe=87b3274937) | Oct 26, 2021 |
| HP            | Stream Notebook PC 11       | [c240a088a9](https://linux-hardware.org/?probe=c240a088a9) | Oct 26, 2021 |
| HP            | ENVY m7 Notebook            | [235fa5cacd](https://linux-hardware.org/?probe=235fa5cacd) | Oct 25, 2021 |
| Dell          | Latitude E6430              | [fa4d12994d](https://linux-hardware.org/?probe=fa4d12994d) | Oct 25, 2021 |
| Schenker      | VIA 15 Pro                  | [7242436545](https://linux-hardware.org/?probe=7242436545) | Oct 24, 2021 |
| Toshiba       | Satellite C70-B             | [a17b7c3888](https://linux-hardware.org/?probe=a17b7c3888) | Oct 24, 2021 |
| Thomson       | N17C512                     | [20abb09d3a](https://linux-hardware.org/?probe=20abb09d3a) | Oct 24, 2021 |
| Notebook      | X170SM                      | [2054d0dee6](https://linux-hardware.org/?probe=2054d0dee6) | Oct 24, 2021 |
| Notebook      | X170SM                      | [f704af17a3](https://linux-hardware.org/?probe=f704af17a3) | Oct 24, 2021 |
| Dell          | Latitude D630               | [1cfebe8169](https://linux-hardware.org/?probe=1cfebe8169) | Oct 23, 2021 |
| Dell          | Latitude E6410              | [f4cdc942dc](https://linux-hardware.org/?probe=f4cdc942dc) | Oct 23, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [fe4aa7e54d](https://linux-hardware.org/?probe=fe4aa7e54d) | Oct 23, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [db85bd77fc](https://linux-hardware.org/?probe=db85bd77fc) | Oct 23, 2021 |
| HP            | ProBook 6550b               | [4db59c8489](https://linux-hardware.org/?probe=4db59c8489) | Oct 23, 2021 |
| Acer          | Aspire ES1-521              | [c6582bba7d](https://linux-hardware.org/?probe=c6582bba7d) | Oct 23, 2021 |
| Acer          | Aspire ES1-521              | [248ab157b8](https://linux-hardware.org/?probe=248ab157b8) | Oct 23, 2021 |
| HP            | Notebook                    | [11013f1334](https://linux-hardware.org/?probe=11013f1334) | Oct 22, 2021 |
| Google        | Kindred                     | [675265477a](https://linux-hardware.org/?probe=675265477a) | Oct 22, 2021 |
| HP            | 255 G4 Notebook PC          | [e7e49e8cc0](https://linux-hardware.org/?probe=e7e49e8cc0) | Oct 22, 2021 |
| Dell          | Latitude E7470              | [061c5e449c](https://linux-hardware.org/?probe=061c5e449c) | Oct 22, 2021 |
| MSI           | Modern 14 B10MW             | [ae43e74753](https://linux-hardware.org/?probe=ae43e74753) | Oct 21, 2021 |
| HP            | Compaq 8710p (GC102EA#AB... | [8668abcc62](https://linux-hardware.org/?probe=8668abcc62) | Oct 21, 2021 |
| HP            | Compaq 8710p (GC102EA#AB... | [18cf55aa72](https://linux-hardware.org/?probe=18cf55aa72) | Oct 21, 2021 |
| Toshiba       | Satellite L755              | [985ff9ba03](https://linux-hardware.org/?probe=985ff9ba03) | Oct 21, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [63c9d05f24](https://linux-hardware.org/?probe=63c9d05f24) | Oct 20, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [85036968bb](https://linux-hardware.org/?probe=85036968bb) | Oct 20, 2021 |
| Lenovo        | ThinkPad T460s 20FAS3F30... | [6d2d97674c](https://linux-hardware.org/?probe=6d2d97674c) | Oct 19, 2021 |
| Lenovo        | ThinkPad T460s 20FAS3F30... | [facdd98487](https://linux-hardware.org/?probe=facdd98487) | Oct 19, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [961f066acf](https://linux-hardware.org/?probe=961f066acf) | Oct 19, 2021 |
| Dell          | Latitude E7470              | [fdc6203a6e](https://linux-hardware.org/?probe=fdc6203a6e) | Oct 18, 2021 |
| Dell          | Latitude E6420              | [027441e6d4](https://linux-hardware.org/?probe=027441e6d4) | Oct 18, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [6210b749a1](https://linux-hardware.org/?probe=6210b749a1) | Oct 18, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [dbf1e020b0](https://linux-hardware.org/?probe=dbf1e020b0) | Oct 18, 2021 |
| Dell          | Inspiron 3521               | [2ffe8489e1](https://linux-hardware.org/?probe=2ffe8489e1) | Oct 18, 2021 |
| Toshiba       | Satellite C870-1C2          | [076883700d](https://linux-hardware.org/?probe=076883700d) | Oct 17, 2021 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [10f8e5f5cf](https://linux-hardware.org/?probe=10f8e5f5cf) | Oct 17, 2021 |
| Acer          | Aspire R3-131T              | [014464c088](https://linux-hardware.org/?probe=014464c088) | Oct 17, 2021 |
| Fujitsu       | LIFEBOOK AH530              | [15ce74dcd6](https://linux-hardware.org/?probe=15ce74dcd6) | Oct 17, 2021 |
| Fujitsu       | LIFEBOOK AH530              | [97c3495c65](https://linux-hardware.org/?probe=97c3495c65) | Oct 17, 2021 |
| Unknown       | CherryTrail                 | [01d095b201](https://linux-hardware.org/?probe=01d095b201) | Oct 17, 2021 |
| Acer          | Aspire E5-571               | [76090a2652](https://linux-hardware.org/?probe=76090a2652) | Oct 16, 2021 |
| HP            | Stream Laptop 14-ax0XX      | [ff6de8e062](https://linux-hardware.org/?probe=ff6de8e062) | Oct 16, 2021 |
| Lenovo        | G50-70 20351                | [d0d0d99be6](https://linux-hardware.org/?probe=d0d0d99be6) | Oct 16, 2021 |
| Lenovo        | Flex 2-14 20404             | [ef609865b5](https://linux-hardware.org/?probe=ef609865b5) | Oct 16, 2021 |
| Lenovo        | Flex 2-14 20404             | [4fc5c2f99f](https://linux-hardware.org/?probe=4fc5c2f99f) | Oct 16, 2021 |
| Dell          | Latitude E7440              | [cfe53904bc](https://linux-hardware.org/?probe=cfe53904bc) | Oct 16, 2021 |
| Unknown       | Unknown                     | [3233e1293c](https://linux-hardware.org/?probe=3233e1293c) | Oct 15, 2021 |
| Acer          | Aspire E5-576G              | [6f17f5d2c0](https://linux-hardware.org/?probe=6f17f5d2c0) | Oct 15, 2021 |
| HP            | Pavilion dv7                | [2d35a2ee5d](https://linux-hardware.org/?probe=2d35a2ee5d) | Oct 15, 2021 |
| HP            | ENVY m7 Notebook            | [f0af05f6f9](https://linux-hardware.org/?probe=f0af05f6f9) | Oct 15, 2021 |
| Unknown       | Unknown                     | [ddc6d80716](https://linux-hardware.org/?probe=ddc6d80716) | Oct 15, 2021 |
| Toshiba       | Satellite L755              | [fdaa2dd77e](https://linux-hardware.org/?probe=fdaa2dd77e) | Oct 14, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [6edbff3019](https://linux-hardware.org/?probe=6edbff3019) | Oct 14, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [3f90ae6d67](https://linux-hardware.org/?probe=3f90ae6d67) | Oct 14, 2021 |
| Dell          | Latitude E6420              | [14b08ab14d](https://linux-hardware.org/?probe=14b08ab14d) | Oct 14, 2021 |
| ASUSTek       | GL702VI                     | [c342d6fdc1](https://linux-hardware.org/?probe=c342d6fdc1) | Oct 14, 2021 |
| HP            | 15                          | [5534f9e3fc](https://linux-hardware.org/?probe=5534f9e3fc) | Oct 14, 2021 |
| Acer          | Swift SF314-59              | [2cd9b13bb1](https://linux-hardware.org/?probe=2cd9b13bb1) | Oct 14, 2021 |
| HP            | 15                          | [bfc196e22b](https://linux-hardware.org/?probe=bfc196e22b) | Oct 13, 2021 |
| ASUSTek       | X501A1                      | [0494cb6f11](https://linux-hardware.org/?probe=0494cb6f11) | Oct 13, 2021 |
| HP            | Notebook                    | [58c6628ba2](https://linux-hardware.org/?probe=58c6628ba2) | Oct 12, 2021 |
| HP            | Notebook                    | [f3f5e6256d](https://linux-hardware.org/?probe=f3f5e6256d) | Oct 12, 2021 |
| Dell          | Inspiron 5721               | [a13d0383b6](https://linux-hardware.org/?probe=a13d0383b6) | Oct 12, 2021 |
| Dell          | Inspiron 5721               | [686377ccd0](https://linux-hardware.org/?probe=686377ccd0) | Oct 12, 2021 |
| HP            | EliteBook 840 G1            | [9bb8ba744e](https://linux-hardware.org/?probe=9bb8ba744e) | Oct 12, 2021 |
| Apple         | MacBookPro8,1               | [01a3f25bec](https://linux-hardware.org/?probe=01a3f25bec) | Oct 12, 2021 |
| Apple         | MacBookPro8,1               | [d8de6fc953](https://linux-hardware.org/?probe=d8de6fc953) | Oct 12, 2021 |
| Giani Limi... | ENY1158M                    | [1f9a85e980](https://linux-hardware.org/?probe=1f9a85e980) | Oct 11, 2021 |
| Giani Limi... | ENY1158M                    | [4516242881](https://linux-hardware.org/?probe=4516242881) | Oct 11, 2021 |
| Lenovo        | ThinkPad X220 4286CTO       | [471414140c](https://linux-hardware.org/?probe=471414140c) | Oct 11, 2021 |
| Unknown       | Z3735F-T02 V1.2             | [6ef4e9edf6](https://linux-hardware.org/?probe=6ef4e9edf6) | Oct 11, 2021 |
| Dell          | Inspiron 3537               | [9614492711](https://linux-hardware.org/?probe=9614492711) | Oct 11, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [f5147cd609](https://linux-hardware.org/?probe=f5147cd609) | Oct 10, 2021 |
| Lenovo        | Y520-15IKBM 80YY            | [fc28e4f7f8](https://linux-hardware.org/?probe=fc28e4f7f8) | Oct 10, 2021 |
| HP            | x2 210                      | [ccf01919ab](https://linux-hardware.org/?probe=ccf01919ab) | Oct 09, 2021 |
| HP            | x2 210                      | [a35274c0a7](https://linux-hardware.org/?probe=a35274c0a7) | Oct 09, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | [e1a73cbf10](https://linux-hardware.org/?probe=e1a73cbf10) | Oct 09, 2021 |
| Samsung       | 700Z3C/700Z5C               | [007ba2bac1](https://linux-hardware.org/?probe=007ba2bac1) | Oct 09, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | [63e608b4af](https://linux-hardware.org/?probe=63e608b4af) | Oct 09, 2021 |
| Acer          | Aspire E5-571               | [e988105956](https://linux-hardware.org/?probe=e988105956) | Oct 09, 2021 |
| ASUSTek       | X555YA                      | [7bbcc6c5af](https://linux-hardware.org/?probe=7bbcc6c5af) | Oct 09, 2021 |
| HP            | Laptop 17z-cp000            | [db7c1566db](https://linux-hardware.org/?probe=db7c1566db) | Oct 09, 2021 |
| HP            | ENVY dv6                    | [21a3477c3d](https://linux-hardware.org/?probe=21a3477c3d) | Oct 08, 2021 |
| MSI           | GE66 Raider 10UH            | [43c72c2ff3](https://linux-hardware.org/?probe=43c72c2ff3) | Oct 08, 2021 |
| HP            | Unknown                     | [c65be179d9](https://linux-hardware.org/?probe=c65be179d9) | Oct 08, 2021 |
| Acer          | TravelMate P259-MG          | [c62543cf86](https://linux-hardware.org/?probe=c62543cf86) | Oct 07, 2021 |
| HP            | Laptop 15s-fq1xxx           | [b81ab61049](https://linux-hardware.org/?probe=b81ab61049) | Oct 07, 2021 |
| HP            | Pavilion dv7                | [e139664dbf](https://linux-hardware.org/?probe=e139664dbf) | Oct 07, 2021 |
| Lenovo        | Z50-75 80EC                 | [2550a17ad0](https://linux-hardware.org/?probe=2550a17ad0) | Oct 07, 2021 |
| Star Labs     | LabTop                      | [711f2b9e6d](https://linux-hardware.org/?probe=711f2b9e6d) | Oct 07, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [ae113c0df0](https://linux-hardware.org/?probe=ae113c0df0) | Oct 06, 2021 |
| Dell          | Latitude E5400              | [6878f58676](https://linux-hardware.org/?probe=6878f58676) | Oct 06, 2021 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [a87e581c64](https://linux-hardware.org/?probe=a87e581c64) | Oct 06, 2021 |
| Dell          | Latitude E5400              | [b69897eca3](https://linux-hardware.org/?probe=b69897eca3) | Oct 06, 2021 |
| Dell          | Latitude E5530 non-vPro     | [afe8fca994](https://linux-hardware.org/?probe=afe8fca994) | Oct 06, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [dc9074514c](https://linux-hardware.org/?probe=dc9074514c) | Oct 06, 2021 |
| ASUSTek       | X550LB                      | [d96d114426](https://linux-hardware.org/?probe=d96d114426) | Oct 06, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [6717c35dc9](https://linux-hardware.org/?probe=6717c35dc9) | Oct 05, 2021 |
| Dell          | Inspiron 3542               | [f67c2f8d32](https://linux-hardware.org/?probe=f67c2f8d32) | Oct 05, 2021 |
| Acer          | Aspire V5-471               | [6a5bc4355e](https://linux-hardware.org/?probe=6a5bc4355e) | Oct 05, 2021 |
| HP            | Notebook                    | [88b07c9f57](https://linux-hardware.org/?probe=88b07c9f57) | Oct 05, 2021 |
| HP            | Notebook                    | [28c9b584b1](https://linux-hardware.org/?probe=28c9b584b1) | Oct 05, 2021 |
| Dell          | Inspiron 3521               | [9e18ebff31](https://linux-hardware.org/?probe=9e18ebff31) | Oct 05, 2021 |
| Lenovo        | ThinkPad L470 20J5A00FLM    | [ccc6db1c41](https://linux-hardware.org/?probe=ccc6db1c41) | Oct 05, 2021 |
| Lenovo        | ThinkPad L470 20J5A00FLM    | [55ec005acb](https://linux-hardware.org/?probe=55ec005acb) | Oct 05, 2021 |
| Acer          | Aspire V5-471               | [4b9f0ceb64](https://linux-hardware.org/?probe=4b9f0ceb64) | Oct 05, 2021 |
| HP            | ProBook 430 G1              | [01109c5fde](https://linux-hardware.org/?probe=01109c5fde) | Oct 04, 2021 |
| Toshiba       | Satellite C70-B             | [2d4b467fdc](https://linux-hardware.org/?probe=2d4b467fdc) | Oct 04, 2021 |
| Dell          | Latitude E5570              | [bfc3702626](https://linux-hardware.org/?probe=bfc3702626) | Oct 04, 2021 |
| HP            | EliteBook 8440p             | [0890806446](https://linux-hardware.org/?probe=0890806446) | Oct 04, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | [6d94d45cf0](https://linux-hardware.org/?probe=6d94d45cf0) | Oct 04, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | [ab6b537db8](https://linux-hardware.org/?probe=ab6b537db8) | Oct 04, 2021 |
| HP            | Notebook                    | [c405133048](https://linux-hardware.org/?probe=c405133048) | Oct 03, 2021 |
| Dell          | Latitude 7390               | [50080eb85e](https://linux-hardware.org/?probe=50080eb85e) | Oct 03, 2021 |
| HP            | Pavilion Laptop 15-cs3xx... | [a2ee189c63](https://linux-hardware.org/?probe=a2ee189c63) | Oct 03, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [a4f833babc](https://linux-hardware.org/?probe=a4f833babc) | Oct 03, 2021 |
| HP            | Pavilion dv7                | [30875abc8f](https://linux-hardware.org/?probe=30875abc8f) | Oct 03, 2021 |
| Dell          | Inspiron 7773               | [2713f21dd7](https://linux-hardware.org/?probe=2713f21dd7) | Oct 03, 2021 |
| Dell          | Latitude E5400              | [ffc2d5a399](https://linux-hardware.org/?probe=ffc2d5a399) | Oct 03, 2021 |
| Toshiba       | Satellite L455D             | [9413906eaa](https://linux-hardware.org/?probe=9413906eaa) | Oct 03, 2021 |
| Dell          | Inspiron 3542               | [e3247b14fa](https://linux-hardware.org/?probe=e3247b14fa) | Oct 02, 2021 |
| Dell          | Latitude E5400              | [529e29fb9d](https://linux-hardware.org/?probe=529e29fb9d) | Oct 02, 2021 |
| Toshiba       | Satellite Pro T110          | [3bd8210e7e](https://linux-hardware.org/?probe=3bd8210e7e) | Oct 01, 2021 |
| HP            | Laptop 15-bw0xx             | [642e96374e](https://linux-hardware.org/?probe=642e96374e) | Oct 01, 2021 |
| Dell          | Latitude E6520              | [e1bf1df5ae](https://linux-hardware.org/?probe=e1bf1df5ae) | Oct 01, 2021 |
| Unknown       | Unknown                     | [f92fca6d48](https://linux-hardware.org/?probe=f92fca6d48) | Oct 01, 2021 |
| Acer          | Nitro AN515-44              | [a7a50b0dbf](https://linux-hardware.org/?probe=a7a50b0dbf) | Oct 01, 2021 |
| HP            | Pavilion dv7                | [590a48aff9](https://linux-hardware.org/?probe=590a48aff9) | Sep 30, 2021 |
| Apple         | MacBook5,2                  | [359171629f](https://linux-hardware.org/?probe=359171629f) | Sep 30, 2021 |
| Apple         | MacBook5,2                  | [4e125287e4](https://linux-hardware.org/?probe=4e125287e4) | Sep 30, 2021 |
| HP            | EliteBook 830 G5            | [d0c34db7d4](https://linux-hardware.org/?probe=d0c34db7d4) | Sep 29, 2021 |
| HP            | ENVY 15                     | [4b949c1a1b](https://linux-hardware.org/?probe=4b949c1a1b) | Sep 29, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [3688fae067](https://linux-hardware.org/?probe=3688fae067) | Sep 29, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [3befe3f6e3](https://linux-hardware.org/?probe=3befe3f6e3) | Sep 29, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | [c5f4555ed5](https://linux-hardware.org/?probe=c5f4555ed5) | Sep 29, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [fb88fc18f4](https://linux-hardware.org/?probe=fb88fc18f4) | Sep 29, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | [cc9cc9e925](https://linux-hardware.org/?probe=cc9cc9e925) | Sep 28, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | [6cf7de2b6b](https://linux-hardware.org/?probe=6cf7de2b6b) | Sep 28, 2021 |
| HP            | Pavilion dv7                | [7e0b76f736](https://linux-hardware.org/?probe=7e0b76f736) | Sep 28, 2021 |
| Acer          | Aspire 4830T                | [d36367eb22](https://linux-hardware.org/?probe=d36367eb22) | Sep 28, 2021 |
| Acer          | Aspire A315-56              | [3fc47b2c92](https://linux-hardware.org/?probe=3fc47b2c92) | Sep 27, 2021 |
| Acer          | Aspire ES1-512              | [d573d0691e](https://linux-hardware.org/?probe=d573d0691e) | Sep 27, 2021 |
| Acer          | Aspire ES1-512              | [f322cce11b](https://linux-hardware.org/?probe=f322cce11b) | Sep 27, 2021 |
| Acer          | Aspire ES1-512              | [6aa9666f2c](https://linux-hardware.org/?probe=6aa9666f2c) | Sep 27, 2021 |
| Dell          | Latitude E5570              | [b4f22d5062](https://linux-hardware.org/?probe=b4f22d5062) | Sep 27, 2021 |
| Dell          | Latitude E5570              | [42c88d1bb8](https://linux-hardware.org/?probe=42c88d1bb8) | Sep 27, 2021 |
| Toshiba       | PORTEGE R700                | [b7b8adedee](https://linux-hardware.org/?probe=b7b8adedee) | Sep 27, 2021 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [00b95678dd](https://linux-hardware.org/?probe=00b95678dd) | Sep 27, 2021 |
| ASUSTek       | X405UA                      | [3a78f7edf5](https://linux-hardware.org/?probe=3a78f7edf5) | Sep 26, 2021 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [a49a61fb7d](https://linux-hardware.org/?probe=a49a61fb7d) | Sep 26, 2021 |
| Lenovo        | ThinkPad T520 4242W19       | [0bbb8d9004](https://linux-hardware.org/?probe=0bbb8d9004) | Sep 26, 2021 |
| Acer          | Aspire 5738                 | [3a72e534d3](https://linux-hardware.org/?probe=3a72e534d3) | Sep 26, 2021 |
| Acer          | Aspire V3-571G              | [8bc152aa27](https://linux-hardware.org/?probe=8bc152aa27) | Sep 25, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | [9267f59e81](https://linux-hardware.org/?probe=9267f59e81) | Sep 25, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | [5404d5874a](https://linux-hardware.org/?probe=5404d5874a) | Sep 25, 2021 |
| Apple         | MacBook3,1                  | [67212f51d0](https://linux-hardware.org/?probe=67212f51d0) | Sep 25, 2021 |
| Dell          | Latitude E6220              | [08e1d2f464](https://linux-hardware.org/?probe=08e1d2f464) | Sep 25, 2021 |
| Acer          | Aspire V3-571G              | [9d3daebd14](https://linux-hardware.org/?probe=9d3daebd14) | Sep 25, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [6b6f1c017d](https://linux-hardware.org/?probe=6b6f1c017d) | Sep 24, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [953ed13df8](https://linux-hardware.org/?probe=953ed13df8) | Sep 24, 2021 |
| Toshiba       | PORTEGE Z30-A               | [a65f8af3ac](https://linux-hardware.org/?probe=a65f8af3ac) | Sep 24, 2021 |
| Apple         | MacBookPro14,1              | [2d0d6ceff3](https://linux-hardware.org/?probe=2d0d6ceff3) | Sep 24, 2021 |
| KOGAN         | KAL11C250SB                 | [b76a44f6d5](https://linux-hardware.org/?probe=b76a44f6d5) | Sep 24, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [1af2027db5](https://linux-hardware.org/?probe=1af2027db5) | Sep 24, 2021 |
| Dell          | Latitude E6430              | [5e66bde0c9](https://linux-hardware.org/?probe=5e66bde0c9) | Sep 24, 2021 |
| ASUSTek       | E403NA                      | [382c1a7b47](https://linux-hardware.org/?probe=382c1a7b47) | Sep 24, 2021 |
| HP            | Presario V6000 (GM018UA#... | [944d6af89a](https://linux-hardware.org/?probe=944d6af89a) | Sep 23, 2021 |
| MSI           | Modern 15 A11M              | [fe99af6254](https://linux-hardware.org/?probe=fe99af6254) | Sep 23, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | [25d01e8fc6](https://linux-hardware.org/?probe=25d01e8fc6) | Sep 23, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [4d2aa790e0](https://linux-hardware.org/?probe=4d2aa790e0) | Sep 23, 2021 |
| Apple         | MacBookPro9,2               | [effa7b0365](https://linux-hardware.org/?probe=effa7b0365) | Sep 22, 2021 |
| HP            | Notebook                    | [91d439a6a4](https://linux-hardware.org/?probe=91d439a6a4) | Sep 22, 2021 |
| Dynabook      | PORTEGE A30-E               | [93fd738472](https://linux-hardware.org/?probe=93fd738472) | Sep 21, 2021 |
| Dynabook      | PORTEGE A30-E               | [0ec5acd020](https://linux-hardware.org/?probe=0ec5acd020) | Sep 21, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [a43f2dc4bf](https://linux-hardware.org/?probe=a43f2dc4bf) | Sep 21, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [069c0cafd0](https://linux-hardware.org/?probe=069c0cafd0) | Sep 21, 2021 |
| Toshiba       | Satellite L755              | [10baeecbf5](https://linux-hardware.org/?probe=10baeecbf5) | Sep 21, 2021 |
| Acer          | Aspire ES1-572              | [36c622eabc](https://linux-hardware.org/?probe=36c622eabc) | Sep 21, 2021 |
| Acer          | Aspire ES1-572              | [0ce8da0fe0](https://linux-hardware.org/?probe=0ce8da0fe0) | Sep 21, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [699803b74c](https://linux-hardware.org/?probe=699803b74c) | Sep 21, 2021 |
| UNOWHY        | Y13G011S4EI                 | [70511c9675](https://linux-hardware.org/?probe=70511c9675) | Sep 21, 2021 |
| Lenovo        | G580                        | [d7e35103d9](https://linux-hardware.org/?probe=d7e35103d9) | Sep 20, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [91055c07be](https://linux-hardware.org/?probe=91055c07be) | Sep 20, 2021 |
| LG Electro... | C400-G.BC22P1               | [ae16407ef3](https://linux-hardware.org/?probe=ae16407ef3) | Sep 20, 2021 |
| Acer          | Aspire E1-532               | [b0407bdd1c](https://linux-hardware.org/?probe=b0407bdd1c) | Sep 20, 2021 |
| Acer          | Aspire 5738                 | [01bb66e2a1](https://linux-hardware.org/?probe=01bb66e2a1) | Sep 20, 2021 |
| TianBei       | TB-H7                       | [06300b96a7](https://linux-hardware.org/?probe=06300b96a7) | Sep 19, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | [d80cdfb094](https://linux-hardware.org/?probe=d80cdfb094) | Sep 19, 2021 |
| Toshiba       | Satellite C870-1C2          | [6129e531d9](https://linux-hardware.org/?probe=6129e531d9) | Sep 19, 2021 |
| Apple         | MacBookPro9,2               | [37f34b16c5](https://linux-hardware.org/?probe=37f34b16c5) | Sep 19, 2021 |
| Acer          | Aspire 4352                 | [3a9aedb538](https://linux-hardware.org/?probe=3a9aedb538) | Sep 19, 2021 |
| ASUSTek       | U31F                        | [908a7184ae](https://linux-hardware.org/?probe=908a7184ae) | Sep 19, 2021 |
| Dell          | XPS 13 9350                 | [4dda7e9a7e](https://linux-hardware.org/?probe=4dda7e9a7e) | Sep 18, 2021 |
| ASUSTek       | U31F                        | [7cf4ac39de](https://linux-hardware.org/?probe=7cf4ac39de) | Sep 18, 2021 |
| Dell          | System XPS L321X            | [2345076968](https://linux-hardware.org/?probe=2345076968) | Sep 18, 2021 |
| Dell          | Latitude E6430              | [2d96c4a645](https://linux-hardware.org/?probe=2d96c4a645) | Sep 17, 2021 |
| Dell          | Vostro 15-3568              | [42d68963c6](https://linux-hardware.org/?probe=42d68963c6) | Sep 17, 2021 |
| Dell          | Vostro 15-3568              | [50f90e7684](https://linux-hardware.org/?probe=50f90e7684) | Sep 17, 2021 |
| Lenovo        | ThinkPad T520 42435GG       | [73a4cd0692](https://linux-hardware.org/?probe=73a4cd0692) | Sep 17, 2021 |
| HP            | Unknown                     | [b0b3846ace](https://linux-hardware.org/?probe=b0b3846ace) | Sep 17, 2021 |
| Lenovo        | ThinkPad T520 42435GG       | [518209a322](https://linux-hardware.org/?probe=518209a322) | Sep 17, 2021 |
| Dell          | Latitude E5470              | [9a036a26a4](https://linux-hardware.org/?probe=9a036a26a4) | Sep 17, 2021 |
| HP            | Notebook                    | [6b2785c2e0](https://linux-hardware.org/?probe=6b2785c2e0) | Sep 17, 2021 |
| Dell          | Latitude E5500              | [286c99863b](https://linux-hardware.org/?probe=286c99863b) | Sep 16, 2021 |
| HP            | 245 G5 Notebook PC          | [ece740cf39](https://linux-hardware.org/?probe=ece740cf39) | Sep 16, 2021 |
| Lenovo        | ThinkPad P50 20EN001EUS     | [04ba56c326](https://linux-hardware.org/?probe=04ba56c326) | Sep 16, 2021 |
| Toshiba       | Satellite L755              | [142e3e40c2](https://linux-hardware.org/?probe=142e3e40c2) | Sep 16, 2021 |
| Toshiba       | Satellite C75D-B            | [152dd3680d](https://linux-hardware.org/?probe=152dd3680d) | Sep 16, 2021 |
| Jumper        | EZpad .A002                 | [c62d842a68](https://linux-hardware.org/?probe=c62d842a68) | Sep 16, 2021 |
| Lenovo        | ThinkPad P50 20EN001EUS     | [6d381b570b](https://linux-hardware.org/?probe=6d381b570b) | Sep 15, 2021 |
| HP            | 255 G4 Notebook PC          | [c8a384ed00](https://linux-hardware.org/?probe=c8a384ed00) | Sep 15, 2021 |
| HP            | EliteBook 840 G5            | [68305a2ede](https://linux-hardware.org/?probe=68305a2ede) | Sep 15, 2021 |
| Dell          | Latitude E7440              | [803cfd7e73](https://linux-hardware.org/?probe=803cfd7e73) | Sep 15, 2021 |
| Dell          | Latitude E6520              | [1bd8b6a82f](https://linux-hardware.org/?probe=1bd8b6a82f) | Sep 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [983922cfbf](https://linux-hardware.org/?probe=983922cfbf) | Sep 15, 2021 |
| Acer          | Aspire 5733Z                | [6cfdfd04c6](https://linux-hardware.org/?probe=6cfdfd04c6) | Sep 14, 2021 |
| HP            | Notebook                    | [d6825ad86c](https://linux-hardware.org/?probe=d6825ad86c) | Sep 14, 2021 |
| Lenovo        | G50-80 80E5                 | [ef850713da](https://linux-hardware.org/?probe=ef850713da) | Sep 14, 2021 |
| Sony          | VGN-SR5                     | [199ae9a9dd](https://linux-hardware.org/?probe=199ae9a9dd) | Sep 14, 2021 |
| Dell          | Latitude E5470              | [032f256bab](https://linux-hardware.org/?probe=032f256bab) | Sep 14, 2021 |
| Sony          | VPCF215FX                   | [173d8636d4](https://linux-hardware.org/?probe=173d8636d4) | Sep 14, 2021 |
| HP            | EliteBook Folio 9470m       | [b054524aac](https://linux-hardware.org/?probe=b054524aac) | Sep 14, 2021 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | [29d5b02719](https://linux-hardware.org/?probe=29d5b02719) | Sep 13, 2021 |
| HP            | Pavilion Notebook           | [864dde8a99](https://linux-hardware.org/?probe=864dde8a99) | Sep 13, 2021 |
| Toshiba       | Satellite C870-1C2          | [3818ff8f07](https://linux-hardware.org/?probe=3818ff8f07) | Sep 12, 2021 |
| HP            | Victus by HP Laptop 16-e... | [6a980ac620](https://linux-hardware.org/?probe=6a980ac620) | Sep 12, 2021 |
| Dell          | Latitude E6430              | [aff84b5ec1](https://linux-hardware.org/?probe=aff84b5ec1) | Sep 12, 2021 |
| Google        | Kindred                     | [c9ee8560b8](https://linux-hardware.org/?probe=c9ee8560b8) | Sep 12, 2021 |
| Dell          | XPS M1330                   | [404d33775d](https://linux-hardware.org/?probe=404d33775d) | Sep 12, 2021 |
| Dell          | Latitude E5500              | [1e20247950](https://linux-hardware.org/?probe=1e20247950) | Sep 12, 2021 |
| Dell          | XPS M1330                   | [3dcddbd59e](https://linux-hardware.org/?probe=3dcddbd59e) | Sep 11, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b565f4eee3](https://linux-hardware.org/?probe=b565f4eee3) | Sep 11, 2021 |
| HP            | Laptop 15-dy1xxx            | [728e0facd6](https://linux-hardware.org/?probe=728e0facd6) | Sep 11, 2021 |
| Acer          | Aspire 4830T                | [4e69ac73e4](https://linux-hardware.org/?probe=4e69ac73e4) | Sep 11, 2021 |
| ASUSTek       | N55SF                       | [33fd6d8c8f](https://linux-hardware.org/?probe=33fd6d8c8f) | Sep 11, 2021 |
| ASUSTek       | N55SF                       | [fa33f94b27](https://linux-hardware.org/?probe=fa33f94b27) | Sep 11, 2021 |
| MSI           | GE75 Raider 8RF             | [350527f093](https://linux-hardware.org/?probe=350527f093) | Sep 10, 2021 |
| Toshiba       | Satellite Pro L450D         | [a15c916899](https://linux-hardware.org/?probe=a15c916899) | Sep 10, 2021 |
| Toshiba       | Satellite C850-1CP          | [8cec9884a8](https://linux-hardware.org/?probe=8cec9884a8) | Sep 10, 2021 |
| Unknown       | Unknown                     | [bbf81cb33e](https://linux-hardware.org/?probe=bbf81cb33e) | Sep 10, 2021 |
| Dell          | Latitude E5470              | [f6d8fa5367](https://linux-hardware.org/?probe=f6d8fa5367) | Sep 10, 2021 |
| Dell          | Latitude E5470              | [87b52d41c7](https://linux-hardware.org/?probe=87b52d41c7) | Sep 10, 2021 |
| HP            | Notebook                    | [24690d1b8b](https://linux-hardware.org/?probe=24690d1b8b) | Sep 09, 2021 |
| Dell          | Vostro 3580                 | [38098784dd](https://linux-hardware.org/?probe=38098784dd) | Sep 09, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [53c03e65ce](https://linux-hardware.org/?probe=53c03e65ce) | Sep 09, 2021 |
| HP            | 255 G7 Notebook PC          | [6ab68f26ba](https://linux-hardware.org/?probe=6ab68f26ba) | Sep 09, 2021 |
| Dell          | Vostro 3580                 | [e480169372](https://linux-hardware.org/?probe=e480169372) | Sep 09, 2021 |
| HP            | ENVY Laptop 13-ah0xxx       | [c06b09d9c4](https://linux-hardware.org/?probe=c06b09d9c4) | Sep 09, 2021 |
| HP            | ENVY Laptop 13-ah0xxx       | [87e79937c9](https://linux-hardware.org/?probe=87e79937c9) | Sep 09, 2021 |
| Lenovo        | IdeaPad 310 Touch-15IKB ... | [ccb4dc3d9a](https://linux-hardware.org/?probe=ccb4dc3d9a) | Sep 09, 2021 |
| Toshiba       | Satellite C75D-B            | [0f52ac751b](https://linux-hardware.org/?probe=0f52ac751b) | Sep 08, 2021 |
| Toshiba       | Satellite C75D-B            | [97b34f8c7f](https://linux-hardware.org/?probe=97b34f8c7f) | Sep 08, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [8404b1fc92](https://linux-hardware.org/?probe=8404b1fc92) | Sep 08, 2021 |
| Lenovo        | ThinkPad E14 20RAS1Q800     | [a4d93ee5d2](https://linux-hardware.org/?probe=a4d93ee5d2) | Sep 08, 2021 |
| HP            | EliteBook 8560p             | [6bff88fb9e](https://linux-hardware.org/?probe=6bff88fb9e) | Sep 08, 2021 |
| Sony          | VGN-SR5                     | [7f93c9c366](https://linux-hardware.org/?probe=7f93c9c366) | Sep 08, 2021 |
| MSI           | GS75 Stealth 10SF           | [3fc588a18d](https://linux-hardware.org/?probe=3fc588a18d) | Sep 08, 2021 |
| MSI           | GS75 Stealth 10SF           | [fd38e5bf9d](https://linux-hardware.org/?probe=fd38e5bf9d) | Sep 08, 2021 |
| HP            | EliteBook 840 G3            | [22d88098a9](https://linux-hardware.org/?probe=22d88098a9) | Sep 08, 2021 |
| Toshiba       | Satellite C75D-B            | [be8d4bd453](https://linux-hardware.org/?probe=be8d4bd453) | Sep 08, 2021 |
| Toshiba       | Satellite C75D-B            | [47317abce2](https://linux-hardware.org/?probe=47317abce2) | Sep 08, 2021 |
| HP            | ENVY Sleekbook 4 PC         | [e8f88bd1b2](https://linux-hardware.org/?probe=e8f88bd1b2) | Sep 08, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [98874d48b2](https://linux-hardware.org/?probe=98874d48b2) | Sep 07, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [f872b42a74](https://linux-hardware.org/?probe=f872b42a74) | Sep 07, 2021 |
| Acer          | V5-171                      | [8068be142e](https://linux-hardware.org/?probe=8068be142e) | Sep 07, 2021 |
| HP            | Notebook                    | [62a2618cde](https://linux-hardware.org/?probe=62a2618cde) | Sep 07, 2021 |
| Toshiba       | Satellite L755              | [92d22f65bf](https://linux-hardware.org/?probe=92d22f65bf) | Sep 07, 2021 |
| Samsung       | 550P5C/550P7C               | [a2a7c20bf7](https://linux-hardware.org/?probe=a2a7c20bf7) | Sep 07, 2021 |
| Dell          | Precision 3520              | [15e6e2c91d](https://linux-hardware.org/?probe=15e6e2c91d) | Sep 07, 2021 |
| Dell          | Precision 5550              | [8ae36d685d](https://linux-hardware.org/?probe=8ae36d685d) | Sep 07, 2021 |
| Dell          | Latitude E5430 non-vPro     | [368f488133](https://linux-hardware.org/?probe=368f488133) | Sep 07, 2021 |
| MSI           | GL62 7RDX                   | [be53fd4c86](https://linux-hardware.org/?probe=be53fd4c86) | Sep 07, 2021 |
| ASUSTek       | ASUS Gaming FX570UD         | [3eaf057f6f](https://linux-hardware.org/?probe=3eaf057f6f) | Sep 07, 2021 |
| Acer          | Swift SF114-34              | [8a66ec8e37](https://linux-hardware.org/?probe=8a66ec8e37) | Sep 07, 2021 |
| Lenovo        | B50-30 20382                | [f91b1f41fc](https://linux-hardware.org/?probe=f91b1f41fc) | Sep 06, 2021 |
| HP            | Pavilion dv5                | [27607d962e](https://linux-hardware.org/?probe=27607d962e) | Sep 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [d1af312696](https://linux-hardware.org/?probe=d1af312696) | Sep 06, 2021 |
| Acer          | Aspire V3-571G              | [46499caf7a](https://linux-hardware.org/?probe=46499caf7a) | Sep 05, 2021 |
| Sony          | VPCS135FX                   | [55c2fa54ae](https://linux-hardware.org/?probe=55c2fa54ae) | Sep 05, 2021 |
| Apple         | MacBook3,1                  | [1473909011](https://linux-hardware.org/?probe=1473909011) | Sep 05, 2021 |
| Lenovo        | G505s 20255                 | [263eeefef0](https://linux-hardware.org/?probe=263eeefef0) | Sep 04, 2021 |
| Lenovo        | G505s 20255                 | [8cd745db58](https://linux-hardware.org/?probe=8cd745db58) | Sep 04, 2021 |
| HP            | ProBook 6450b               | [960930d457](https://linux-hardware.org/?probe=960930d457) | Sep 04, 2021 |
| HP            | ProBook 6450b               | [98041e0acd](https://linux-hardware.org/?probe=98041e0acd) | Sep 04, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [303c36ac93](https://linux-hardware.org/?probe=303c36ac93) | Sep 03, 2021 |
| HP            | 255 G3                      | [bd1a8b58da](https://linux-hardware.org/?probe=bd1a8b58da) | Sep 03, 2021 |
| HP            | 255 G3                      | [b5f1c73339](https://linux-hardware.org/?probe=b5f1c73339) | Sep 03, 2021 |
| Acer          | Aspire A315-31              | [f07f0d19ca](https://linux-hardware.org/?probe=f07f0d19ca) | Sep 03, 2021 |
| HP            | EliteBook 840 G1            | [980716e0a8](https://linux-hardware.org/?probe=980716e0a8) | Sep 03, 2021 |
| ASUSTek       | GR8                         | [eb4fb4e1f2](https://linux-hardware.org/?probe=eb4fb4e1f2) | Sep 03, 2021 |
| Lenovo        | ThinkPad W520 4284AW3       | [6647a6a4b4](https://linux-hardware.org/?probe=6647a6a4b4) | Sep 03, 2021 |
| Acer          | Aspire R3-131T              | [62485c81e9](https://linux-hardware.org/?probe=62485c81e9) | Sep 02, 2021 |
| Acer          | Aspire E5-521G              | [d1aa71f003](https://linux-hardware.org/?probe=d1aa71f003) | Sep 02, 2021 |
| Acer          | Aspire 4830T                | [52441614fe](https://linux-hardware.org/?probe=52441614fe) | Sep 02, 2021 |
| Acer          | Aspire E1-522               | [8cd8899bae](https://linux-hardware.org/?probe=8cd8899bae) | Sep 02, 2021 |
| Toshiba       | Satellite C850D-11C         | [51748f289f](https://linux-hardware.org/?probe=51748f289f) | Sep 01, 2021 |
| HP            | ENVY 15                     | [d2bb5f165e](https://linux-hardware.org/?probe=d2bb5f165e) | Sep 01, 2021 |
| ASUSTek       | X405UA                      | [9bf230ee3f](https://linux-hardware.org/?probe=9bf230ee3f) | Aug 31, 2021 |
| Insyde        | i101c                       | [de0a5f2925](https://linux-hardware.org/?probe=de0a5f2925) | Aug 31, 2021 |
| HP            | EliteBook 840 G1            | [8439784c2b](https://linux-hardware.org/?probe=8439784c2b) | Aug 31, 2021 |
| HP            | Pavilion 15                 | [13ae124697](https://linux-hardware.org/?probe=13ae124697) | Aug 31, 2021 |
| ASUSTek       | K73SV                       | [e7c8d68b00](https://linux-hardware.org/?probe=e7c8d68b00) | Aug 31, 2021 |
| Dell          | XPS 15 9560                 | [fe38c67cd2](https://linux-hardware.org/?probe=fe38c67cd2) | Aug 30, 2021 |
| Acer          | Aspire E1-522               | [80412fd612](https://linux-hardware.org/?probe=80412fd612) | Aug 30, 2021 |
| Acer          | Aspire E1-522               | [f2542100bc](https://linux-hardware.org/?probe=f2542100bc) | Aug 30, 2021 |
| Lenovo        | B50-70 80EU                 | [9507d559fc](https://linux-hardware.org/?probe=9507d559fc) | Aug 30, 2021 |
| Apple         | MacBookPro11,1              | [1dbc26a990](https://linux-hardware.org/?probe=1dbc26a990) | Aug 29, 2021 |
| Packard Be... | DOT S                       | [0231531196](https://linux-hardware.org/?probe=0231531196) | Aug 29, 2021 |
| Packard Be... | DOT S                       | [4f0a335506](https://linux-hardware.org/?probe=4f0a335506) | Aug 29, 2021 |
| Lenovo        | ThinkPad T520 4242W4F       | [150dd830ac](https://linux-hardware.org/?probe=150dd830ac) | Aug 29, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [e63b8b96dd](https://linux-hardware.org/?probe=e63b8b96dd) | Aug 29, 2021 |
| Acer          | Aspire 5100                 | [2b16fed8a1](https://linux-hardware.org/?probe=2b16fed8a1) | Aug 28, 2021 |
| Toshiba       | Satellite S75Dt-A           | [c3e9c3d13b](https://linux-hardware.org/?probe=c3e9c3d13b) | Aug 28, 2021 |
| Acer          | Aspire A515-51              | [6acb0f573a](https://linux-hardware.org/?probe=6acb0f573a) | Aug 28, 2021 |
| ASUSTek       | K56CA                       | [90d571608f](https://linux-hardware.org/?probe=90d571608f) | Aug 28, 2021 |
| Dell          | Inspiron 5566               | [2c2761e770](https://linux-hardware.org/?probe=2c2761e770) | Aug 27, 2021 |
| Dell          | XPS 13 9310                 | [08009ad892](https://linux-hardware.org/?probe=08009ad892) | Aug 26, 2021 |
| Acer          | AO722                       | [e303d0c046](https://linux-hardware.org/?probe=e303d0c046) | Aug 25, 2021 |
| Lenovo        | IdeaPad Z510 20287          | [2199b6e642](https://linux-hardware.org/?probe=2199b6e642) | Aug 25, 2021 |
| Dell          | Inspiron 7520               | [1798e6404c](https://linux-hardware.org/?probe=1798e6404c) | Aug 25, 2021 |
| Unknown       | Unknown                     | [e18bc8fe09](https://linux-hardware.org/?probe=e18bc8fe09) | Aug 25, 2021 |
| Acer          | Aspire ES1-512              | [48b43bd242](https://linux-hardware.org/?probe=48b43bd242) | Aug 25, 2021 |
| Unknown       | Unknown                     | [e576736426](https://linux-hardware.org/?probe=e576736426) | Aug 25, 2021 |
| TianBei       | TB-H7                       | [455dce9834](https://linux-hardware.org/?probe=455dce9834) | Aug 25, 2021 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [a64e3a0513](https://linux-hardware.org/?probe=a64e3a0513) | Aug 25, 2021 |
| LG Electro... | S460-G.BG31P1               | [99df59aebd](https://linux-hardware.org/?probe=99df59aebd) | Aug 24, 2021 |
| HP            | ENVY Sleekbook 4 PC         | [3d58cb6ce0](https://linux-hardware.org/?probe=3d58cb6ce0) | Aug 24, 2021 |
| Acer          | Aspire 7715Z                | [4de4de1a31](https://linux-hardware.org/?probe=4de4de1a31) | Aug 24, 2021 |
| Lenovo        | G50-30 80G0                 | [27cdfce14b](https://linux-hardware.org/?probe=27cdfce14b) | Aug 24, 2021 |
| LG Electro... | A410-K.BE47P1               | [bfc75c9c3d](https://linux-hardware.org/?probe=bfc75c9c3d) | Aug 24, 2021 |
| Acer          | Aspire 8940G                | [24ff3cf596](https://linux-hardware.org/?probe=24ff3cf596) | Aug 23, 2021 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [b0830bd154](https://linux-hardware.org/?probe=b0830bd154) | Aug 23, 2021 |
| Dell          | Inspiron 5566               | [c56758deca](https://linux-hardware.org/?probe=c56758deca) | Aug 23, 2021 |
| Dell          | Inspiron 5566               | [eaef6e8392](https://linux-hardware.org/?probe=eaef6e8392) | Aug 23, 2021 |
| Dell          | Precision M4800             | [9766c85e7d](https://linux-hardware.org/?probe=9766c85e7d) | Aug 23, 2021 |
| Dell          | Precision M4800             | [cd3dbe3a32](https://linux-hardware.org/?probe=cd3dbe3a32) | Aug 23, 2021 |
| Unknown       | Unknown                     | [b1587c998f](https://linux-hardware.org/?probe=b1587c998f) | Aug 23, 2021 |
| TianBei       | TB-H7                       | [2d1b3b2756](https://linux-hardware.org/?probe=2d1b3b2756) | Aug 23, 2021 |
| ASUSTek       | X550LD                      | [04365cbbbf](https://linux-hardware.org/?probe=04365cbbbf) | Aug 22, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1CH0... | [43f252f22a](https://linux-hardware.org/?probe=43f252f22a) | Aug 22, 2021 |
| Apple         | MacBookPro11,5              | [814f16635c](https://linux-hardware.org/?probe=814f16635c) | Aug 22, 2021 |
| HP            | ProBook 450 G2              | [99f47f1645](https://linux-hardware.org/?probe=99f47f1645) | Aug 21, 2021 |
| Lenovo        | IdeaPad S540-14API 81NH     | [7b1954838a](https://linux-hardware.org/?probe=7b1954838a) | Aug 21, 2021 |
| HP            | Notebook                    | [2586dc3a41](https://linux-hardware.org/?probe=2586dc3a41) | Aug 21, 2021 |
| Lenovo        | G50-30 80G0                 | [afbefeb6d3](https://linux-hardware.org/?probe=afbefeb6d3) | Aug 21, 2021 |
| Lenovo        | ThinkPad X131e 3371AL2      | [1963322393](https://linux-hardware.org/?probe=1963322393) | Aug 21, 2021 |
| ASUSTek       | GR8                         | [88416da5e8](https://linux-hardware.org/?probe=88416da5e8) | Aug 21, 2021 |
| Apple         | MacBook4,1                  | [ad6e3e064f](https://linux-hardware.org/?probe=ad6e3e064f) | Aug 21, 2021 |
| Apple         | MacBook4,1                  | [9a5653e44d](https://linux-hardware.org/?probe=9a5653e44d) | Aug 21, 2021 |
| Sony          | VGN-SR5                     | [3bbd8b33f0](https://linux-hardware.org/?probe=3bbd8b33f0) | Aug 20, 2021 |
| HP            | ENVY 14                     | [34f9505762](https://linux-hardware.org/?probe=34f9505762) | Aug 20, 2021 |
| Lenovo        | G50-70 20351                | [40249b1ea8](https://linux-hardware.org/?probe=40249b1ea8) | Aug 20, 2021 |
| HP            | ENVY Sleekbook 4 PC         | [231e17454e](https://linux-hardware.org/?probe=231e17454e) | Aug 19, 2021 |
| Dell          | Inspiron N5040              | [0554d06022](https://linux-hardware.org/?probe=0554d06022) | Aug 19, 2021 |
| LG Electro... | 17U70N-R.AAS7U1             | [fd3572c46a](https://linux-hardware.org/?probe=fd3572c46a) | Aug 19, 2021 |
| Acer          | Nitro AN515-55              | [3a47dca146](https://linux-hardware.org/?probe=3a47dca146) | Aug 18, 2021 |
| HP            | ProBook 450 G2              | [a3e170c339](https://linux-hardware.org/?probe=a3e170c339) | Aug 17, 2021 |
| Acer          | Swift SF114-34              | [0a37eed9e8](https://linux-hardware.org/?probe=0a37eed9e8) | Aug 15, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [fcfd1e5ba9](https://linux-hardware.org/?probe=fcfd1e5ba9) | Aug 15, 2021 |
| HP            | ProBook 430 G6              | [c5467376e9](https://linux-hardware.org/?probe=c5467376e9) | Aug 13, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [9718804b4a](https://linux-hardware.org/?probe=9718804b4a) | Aug 12, 2021 |
| HP            | ProBook 450 G2              | [67956ca49e](https://linux-hardware.org/?probe=67956ca49e) | Aug 10, 2021 |
| Acer          | Aspire E1-571               | [146f910c76](https://linux-hardware.org/?probe=146f910c76) | Aug 09, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [c7a0820fe0](https://linux-hardware.org/?probe=c7a0820fe0) | Aug 09, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [950d41dbb8](https://linux-hardware.org/?probe=950d41dbb8) | Aug 09, 2021 |
| Dell          | Inspiron 7537               | [7a35ed5eb1](https://linux-hardware.org/?probe=7a35ed5eb1) | Aug 03, 2021 |
| Dell          | Inspiron 7537               | [3c865e72d1](https://linux-hardware.org/?probe=3c865e72d1) | Aug 03, 2021 |
| Acer          | Aspire E5-551G              | [519515ce84](https://linux-hardware.org/?probe=519515ce84) | Jul 15, 2021 |
| Dell          | XPS L501X                   | [a3d8e737a5](https://linux-hardware.org/?probe=a3d8e737a5) | Jul 08, 2021 |
| Dell          | G3 3579                     | [92a8136dc4](https://linux-hardware.org/?probe=92a8136dc4) | Jul 03, 2021 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [1196d6821c](https://linux-hardware.org/?probe=1196d6821c) | Jul 02, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [d63c7755ee](https://linux-hardware.org/?probe=d63c7755ee) | Jun 29, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [369a214905](https://linux-hardware.org/?probe=369a214905) | Jun 25, 2021 |
| Dell          | Inspiron 3576               | [849d571ef0](https://linux-hardware.org/?probe=849d571ef0) | Jun 24, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [9957b51bea](https://linux-hardware.org/?probe=9957b51bea) | Jun 24, 2021 |
| Dell          | Inspiron 3582               | [e2cd9a9c36](https://linux-hardware.org/?probe=e2cd9a9c36) | Jun 20, 2021 |
| Dell          | XPS 13 9370                 | [9e3a58b257](https://linux-hardware.org/?probe=9e3a58b257) | Jun 12, 2021 |
| Dell          | XPS 13 9370                 | [2aa1efb008](https://linux-hardware.org/?probe=2aa1efb008) | Jun 12, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [01cf29ba72](https://linux-hardware.org/?probe=01cf29ba72) | Jun 10, 2021 |
| HP            | 15                          | [f2132922af](https://linux-hardware.org/?probe=f2132922af) | Jun 08, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [a1dd6df8e7](https://linux-hardware.org/?probe=a1dd6df8e7) | Jun 07, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [957048adbb](https://linux-hardware.org/?probe=957048adbb) | Jun 06, 2021 |
| Dell          | Inspiron 3582               | [229600e417](https://linux-hardware.org/?probe=229600e417) | Jun 06, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [719041c9d4](https://linux-hardware.org/?probe=719041c9d4) | Jun 04, 2021 |
| HP            | ProBook 650 G2              | [bb92ab2244](https://linux-hardware.org/?probe=bb92ab2244) | May 30, 2021 |
| HP            | Unknown                     | [e6e060ca51](https://linux-hardware.org/?probe=e6e060ca51) | May 29, 2021 |
| HP            | Unknown                     | [324d49aba6](https://linux-hardware.org/?probe=324d49aba6) | May 29, 2021 |
| Razer         | Book 13 - RZ09-0357         | [c1cc1fcf2e](https://linux-hardware.org/?probe=c1cc1fcf2e) | May 27, 2021 |
| Dell          | Vostro 5490                 | [9d8401675e](https://linux-hardware.org/?probe=9d8401675e) | May 18, 2021 |
| Dell          | Vostro 5490                 | [3f02204090](https://linux-hardware.org/?probe=3f02204090) | May 18, 2021 |
| Acer          | Swift SF313-51              | [2b27dc30ac](https://linux-hardware.org/?probe=2b27dc30ac) | May 17, 2021 |
| ASUSTek       | X406UAR                     | [5c50159b19](https://linux-hardware.org/?probe=5c50159b19) | May 16, 2021 |
| ASUSTek       | X406UAR                     | [e3be0eaa69](https://linux-hardware.org/?probe=e3be0eaa69) | May 16, 2021 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [b71b291af5](https://linux-hardware.org/?probe=b71b291af5) | May 10, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [157ae0cc83](https://linux-hardware.org/?probe=157ae0cc83) | May 02, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [12081d4e79](https://linux-hardware.org/?probe=12081d4e79) | Apr 25, 2021 |
| Lenovo        | IdeaPad Y570 0862           | [94d22e7673](https://linux-hardware.org/?probe=94d22e7673) | Apr 23, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Notebooks | Percent |
|-----------------------------|-----------|---------|
| 5.11.0-27-generic           | 92        | 15.13%  |
| 5.11.0-38-generic           | 83        | 13.65%  |
| 5.11.0-37-generic           | 72        | 11.84%  |
| 5.11.0-40-generic           | 64        | 10.53%  |
| 5.11.0-43-generic           | 58        | 9.54%   |
| 5.11.0-41-generic           | 58        | 9.54%   |
| 5.11.0-34-generic           | 57        | 9.38%   |
| 5.11.0-46-generic           | 25        | 4.11%   |
| 5.11.0-36-generic           | 22        | 3.62%   |
| 5.13.0-27-generic           | 20        | 3.29%   |
| 5.11.0-44-generic           | 17        | 2.8%    |
| 5.11.0-25-generic           | 9         | 1.48%   |
| 5.8.0-53-generic            | 6         | 0.99%   |
| 5.8.0-59-generic            | 5         | 0.82%   |
| 5.8.0-55-generic            | 5         | 0.82%   |
| 5.8.0-50-generic            | 4         | 0.66%   |
| 5.8.0-63-generic            | 1         | 0.16%   |
| 5.8.0-49-generic            | 1         | 0.16%   |
| 5.16.0-051600rc8-lowlatency | 1         | 0.16%   |
| 5.16.0-051600rc4-generic    | 1         | 0.16%   |
| 5.15.0-8.1-liquorix-amd64   | 1         | 0.16%   |
| 5.14.0-15.1-liquorix-amd64  | 1         | 0.16%   |
| 5.13.18-xanmod1             | 1         | 0.16%   |
| 5.13.0-25-generic           | 1         | 0.16%   |
| 5.13.0-1020-oem             | 1         | 0.16%   |
| 5.10.0-1052-oem             | 1         | 0.16%   |
| 5.10.0-1044-oem             | 1         | 0.16%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11.0  | 522       | 91.1%   |
| 5.8.0   | 22        | 3.84%   |
| 5.13.0  | 22        | 3.84%   |
| 5.16.0  | 2         | 0.35%   |
| 5.10.0  | 2         | 0.35%   |
| 5.15.0  | 1         | 0.17%   |
| 5.14.0  | 1         | 0.17%   |
| 5.13.18 | 1         | 0.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11    | 522       | 91.1%   |
| 5.13    | 23        | 4.01%   |
| 5.8     | 22        | 3.84%   |
| 5.16    | 2         | 0.35%   |
| 5.10    | 2         | 0.35%   |
| 5.15    | 1         | 0.17%   |
| 5.14    | 1         | 0.17%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 566       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 536       | 94.37%  |
| XFCE       | 26        | 4.58%   |
| Unknown    | 4         | 0.7%    |
| X-Cinnamon | 1         | 0.18%   |
| KDE        | 1         | 0.18%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 557       | 98.06%  |
| Wayland | 9         | 1.58%   |
| Unknown | 2         | 0.35%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 440       | 77.33%  |
| GDM3    | 65        | 11.42%  |
| GDM     | 58        | 10.19%  |
| LightDM | 5         | 0.88%   |
| SDDM    | 1         | 0.18%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 218       | 38.45%  |
| de_DE | 55        | 9.7%    |
| en_GB | 45        | 7.94%   |
| pt_BR | 29        | 5.11%   |
| en_IN | 23        | 4.06%   |
| es_ES | 20        | 3.53%   |
| en_CA | 18        | 3.17%   |
| pl_PL | 14        | 2.47%   |
| fr_FR | 14        | 2.47%   |
| it_IT | 12        | 2.12%   |
| nl_NL | 11        | 1.94%   |
| es_MX | 11        | 1.94%   |
| en_AU | 9         | 1.59%   |
| ru_RU | 7         | 1.23%   |
| pt_PT | 7         | 1.23%   |
| es_CL | 7         | 1.23%   |
| cs_CZ | 7         | 1.23%   |
| fr_BE | 6         | 1.06%   |
| en_ZA | 6         | 1.06%   |
| sv_SE | 4         | 0.71%   |
| en_NZ | 4         | 0.71%   |
| hu_HU | 3         | 0.53%   |
| de_CH | 3         | 0.53%   |
| de_AT | 3         | 0.53%   |
| ru_UA | 2         | 0.35%   |
| nl_BE | 2         | 0.35%   |
| nb_NO | 2         | 0.35%   |
| ja_JP | 2         | 0.35%   |
| hr_HR | 2         | 0.35%   |
| bg_BG | 2         | 0.35%   |
| tr_TR | 1         | 0.18%   |
| sl_SI | 1         | 0.18%   |
| sk_SK | 1         | 0.18%   |
| ro_RO | 1         | 0.18%   |
| fr_CA | 1         | 0.18%   |
| fi_FI | 1         | 0.18%   |
| es_UY | 1         | 0.18%   |
| es_PE | 1         | 0.18%   |
| es_PA | 1         | 0.18%   |
| es_EC | 1         | 0.18%   |
| es_CR | 1         | 0.18%   |
| es_AR | 1         | 0.18%   |
| en_SG | 1         | 0.18%   |
| en_PH | 1         | 0.18%   |
| en_IL | 1         | 0.18%   |
| el_GR | 1         | 0.18%   |
| da_DK | 1         | 0.18%   |
| C     | 1         | 0.18%   |
| ar_EG | 1         | 0.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 350       | 61.3%   |
| BIOS | 221       | 38.7%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 535       | 94.52%  |
| Zfs     | 10        | 1.77%   |
| Overlay | 9         | 1.59%   |
| Btrfs   | 9         | 1.59%   |
| Xfs     | 2         | 0.35%   |
| Ext2    | 1         | 0.18%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 508       | 89.12%  |
| GPT     | 57        | 10%     |
| MBR     | 5         | 0.88%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 555       | 97.88%  |
| Yes       | 12        | 2.12%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 511       | 89.81%  |
| Yes       | 58        | 10.19%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 115       | 20.32%  |
| Dell                   | 90        | 15.9%   |
| Lenovo                 | 87        | 15.37%  |
| ASUSTek Computer       | 75        | 13.25%  |
| Acer                   | 58        | 10.25%  |
| Toshiba                | 26        | 4.59%   |
| Apple                  | 15        | 2.65%   |
| MSI                    | 13        | 2.3%    |
| Sony                   | 11        | 1.94%   |
| Samsung Electronics    | 9         | 1.59%   |
| Unknown                | 9         | 1.59%   |
| Google                 | 5         | 0.88%   |
| Notebook               | 4         | 0.71%   |
| LG Electronics         | 4         | 0.71%   |
| Razer                  | 3         | 0.53%   |
| Packard Bell           | 3         | 0.53%   |
| Jumper                 | 3         | 0.53%   |
| HUAWEI                 | 3         | 0.53%   |
| TUXEDO                 | 2         | 0.35%   |
| Fujitsu Siemens        | 2         | 0.35%   |
| Fujitsu                | 2         | 0.35%   |
| Digibras               | 2         | 0.35%   |
| Chuwi                  | 2         | 0.35%   |
| UNOWHY                 | 1         | 0.18%   |
| TianBei                | 1         | 0.18%   |
| Thomson                | 1         | 0.18%   |
| TCL Communication      | 1         | 0.18%   |
| Star Labs              | 1         | 0.18%   |
| Schenker               | 1         | 0.18%   |
| RCA                    | 1         | 0.18%   |
| Primux                 | 1         | 0.18%   |
| Positivo               | 1         | 0.18%   |
| NEC Computers          | 1         | 0.18%   |
| Multilaser             | 1         | 0.18%   |
| mPTech                 | 1         | 0.18%   |
| Mediacom               | 1         | 0.18%   |
| MECER                  | 1         | 0.18%   |
| Login Informatica      | 1         | 0.18%   |
| KOGAN                  | 1         | 0.18%   |
| Insyde                 | 1         | 0.18%   |
| Giani Limited          | 1         | 0.18%   |
| Fusion5                | 1         | 0.18%   |
| Dynabook               | 1         | 0.18%   |
| Compaq                 | 1         | 0.18%   |
| Clevo                  | 1         | 0.18%   |
| Avell High Performance | 1         | 0.18%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Unknown                         | 11        | 1.94%   |
| HP Notebook                     | 8         | 1.41%   |
| HP 15                           | 6         | 1.06%   |
| HP Pavilion 15                  | 4         | 0.71%   |
| Dell Latitude E7440             | 4         | 0.71%   |
| Lenovo IdeaPad S340-14API 81NB  | 3         | 0.53%   |
| HP Pavilion Notebook            | 3         | 0.53%   |
| HP OMEN by Laptop 15-dc1xxx     | 3         | 0.53%   |
| Dell Latitude E6420             | 3         | 0.53%   |
| Apple MacBookPro8,1             | 3         | 0.53%   |
| Lenovo Yoga 3 Pro-1370 80HE     | 2         | 0.35%   |
| Lenovo IdeaPad Yoga 13 20175    | 2         | 0.35%   |
| Lenovo IdeaPad S145-15API 81V7  | 2         | 0.35%   |
| Lenovo IdeaPad Flex-14API 81SS  | 2         | 0.35%   |
| Lenovo IdeaPad 3 15IIL05 81WE   | 2         | 0.35%   |
| Lenovo G50-70 20351             | 2         | 0.35%   |
| Jumper EZbook                   | 2         | 0.35%   |
| HP ProBook 6450b                | 2         | 0.35%   |
| HP Pavilion dv7                 | 2         | 0.35%   |
| HP Pavilion dv5                 | 2         | 0.35%   |
| HP Laptop 15-bw0xx              | 2         | 0.35%   |
| HP ENVY Sleekbook 4 PC          | 2         | 0.35%   |
| HP EliteBook Folio 9470m        | 2         | 0.35%   |
| HP EliteBook 8440p              | 2         | 0.35%   |
| HP EliteBook 840 G1             | 2         | 0.35%   |
| HP Compaq 8510p                 | 2         | 0.35%   |
| Google Kindred                  | 2         | 0.35%   |
| Digibras NH4CU03                | 2         | 0.35%   |
| Dell XPS 15 9510                | 2         | 0.35%   |
| Dell Precision M4600            | 2         | 0.35%   |
| Dell Latitude E7470             | 2         | 0.35%   |
| Dell Latitude E6520             | 2         | 0.35%   |
| Dell Latitude E6430             | 2         | 0.35%   |
| Dell Latitude E5570             | 2         | 0.35%   |
| Dell Latitude E5470             | 2         | 0.35%   |
| Dell Latitude 3440              | 2         | 0.35%   |
| Dell Inspiron 5770              | 2         | 0.35%   |
| Dell Inspiron 5566              | 2         | 0.35%   |
| Dell Inspiron 3542              | 2         | 0.35%   |
| Dell Inspiron 1750              | 2         | 0.35%   |
| Dell Inspiron 15-3567           | 2         | 0.35%   |
| Dell Inspiron 15 7000 Gaming    | 2         | 0.35%   |
| ASUS X553MA                     | 2         | 0.35%   |
| ASUS X405UA                     | 2         | 0.35%   |
| Apple MacBookPro11,1            | 2         | 0.35%   |
| Apple MacBook4,1                | 2         | 0.35%   |
| Acer Aspire V3-571G             | 2         | 0.35%   |
| Acer Aspire V3-571              | 2         | 0.35%   |
| Acer Aspire ES1-512             | 2         | 0.35%   |
| Acer Aspire E1-522              | 2         | 0.35%   |
| UNOWHY Y13G011S4EI              | 1         | 0.18%   |
| TUXEDO Pulse 14 Gen1            | 1         | 0.18%   |
| TUXEDO InfinityBook Pro 14 Gen6 | 1         | 0.18%   |
| Toshiba TECRA S11               | 1         | 0.18%   |
| Toshiba TECRA A9                | 1         | 0.18%   |
| Toshiba Satellite U300          | 1         | 0.18%   |
| Toshiba Satellite S75Dt-A       | 1         | 0.18%   |
| Toshiba Satellite Pro T110      | 1         | 0.18%   |
| Toshiba Satellite Pro L450D     | 1         | 0.18%   |
| Toshiba Satellite L755          | 1         | 0.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Dell Latitude          | 42        | 7.42%   |
| Acer Aspire            | 42        | 7.42%   |
| Lenovo ThinkPad        | 36        | 6.36%   |
| Dell Inspiron          | 27        | 4.77%   |
| Lenovo IdeaPad         | 26        | 4.59%   |
| HP Pavilion            | 23        | 4.06%   |
| Toshiba Satellite      | 19        | 3.36%   |
| HP EliteBook           | 18        | 3.18%   |
| HP ProBook             | 14        | 2.47%   |
| ASUS VivoBook          | 12        | 2.12%   |
| Unknown                | 11        | 1.94%   |
| HP Laptop              | 10        | 1.77%   |
| HP ENVY                | 9         | 1.59%   |
| HP Notebook            | 8         | 1.41%   |
| Dell XPS               | 8         | 1.41%   |
| HP 15                  | 7         | 1.24%   |
| Dell Precision         | 6         | 1.06%   |
| Acer Swift             | 5         | 0.88%   |
| Toshiba PORTEGE        | 4         | 0.71%   |
| HP Stream              | 4         | 0.71%   |
| HP OMEN                | 4         | 0.71%   |
| HP Compaq              | 4         | 0.71%   |
| HP 255                 | 4         | 0.71%   |
| Dell Vostro            | 4         | 0.71%   |
| ASUS ASUS              | 4         | 0.71%   |
| Apple MacBookPro11     | 4         | 0.71%   |
| ASUS ZenBook           | 3         | 0.53%   |
| ASUS TUF               | 3         | 0.53%   |
| ASUS ROG               | 3         | 0.53%   |
| Apple MacBookPro8      | 3         | 0.53%   |
| Toshiba TECRA          | 2         | 0.35%   |
| Razer Blade            | 2         | 0.35%   |
| Packard Bell EasyNote  | 2         | 0.35%   |
| MSI Modern             | 2         | 0.35%   |
| MSI GF63               | 2         | 0.35%   |
| MSI GE75               | 2         | 0.35%   |
| Lenovo Yoga            | 2         | 0.35%   |
| Lenovo ThinkBook       | 2         | 0.35%   |
| Lenovo Legion          | 2         | 0.35%   |
| Lenovo G580            | 2         | 0.35%   |
| Lenovo G50-70          | 2         | 0.35%   |
| Jumper EZbook          | 2         | 0.35%   |
| Google Kindred         | 2         | 0.35%   |
| Fujitsu LIFEBOOK       | 2         | 0.35%   |
| Digibras NH4CU03       | 2         | 0.35%   |
| Chuwi GemiBook         | 2         | 0.35%   |
| ASUS X553MA            | 2         | 0.35%   |
| ASUS X405UA            | 2         | 0.35%   |
| Apple MacBook4         | 2         | 0.35%   |
| Acer TravelMate        | 2         | 0.35%   |
| Acer Nitro             | 2         | 0.35%   |
| UNOWHY Y13G011S4EI     | 1         | 0.18%   |
| TUXEDO Pulse           | 1         | 0.18%   |
| TUXEDO InfinityBook    | 1         | 0.18%   |
| Toshiba QOSMIO         | 1         | 0.18%   |
| TianBei TB-H7          | 1         | 0.18%   |
| Thomson N17C512        | 1         | 0.18%   |
| TCL Communication 8085 | 1         | 0.18%   |
| Star Labs LabTop       | 1         | 0.18%   |
| Sony VPCSA3N9E         | 1         | 0.18%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2012 | 59        | 10.42%  |
| 2011 | 54        | 9.54%   |
| 2020 | 50        | 8.83%   |
| 2013 | 47        | 8.3%    |
| 2019 | 45        | 7.95%   |
| 2017 | 45        | 7.95%   |
| 2014 | 43        | 7.6%    |
| 2021 | 39        | 6.89%   |
| 2016 | 37        | 6.54%   |
| 2018 | 34        | 6.01%   |
| 2010 | 32        | 5.65%   |
| 2008 | 26        | 4.59%   |
| 2015 | 25        | 4.42%   |
| 2009 | 15        | 2.65%   |
| 2007 | 13        | 2.3%    |
| 2006 | 2         | 0.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 566       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 484       | 84.91%  |
| Enabled  | 86        | 15.09%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 560       | 98.94%  |
| Yes  | 6         | 1.06%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 203       | 35.87%  |
| 3.01-4.0    | 149       | 26.33%  |
| 8.01-16.0   | 81        | 14.31%  |
| 16.01-24.0  | 66        | 11.66%  |
| 1.01-2.0    | 28        | 4.95%   |
| 32.01-64.0  | 23        | 4.06%   |
| 2.01-3.0    | 8         | 1.41%   |
| 64.01-256.0 | 6         | 1.06%   |
| 24.01-32.0  | 1         | 0.18%   |
| 0.51-1.0    | 1         | 0.18%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 265       | 44.17%  |
| 2.01-3.0   | 193       | 32.17%  |
| 3.01-4.0   | 77        | 12.83%  |
| 4.01-8.0   | 51        | 8.5%    |
| 0.51-1.0   | 8         | 1.33%   |
| 8.01-16.0  | 4         | 0.67%   |
| 24.01-32.0 | 2         | 0.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 428       | 75.22%  |
| 2      | 123       | 21.62%  |
| 3      | 13        | 2.28%   |
| 4      | 4         | 0.7%    |
| 0      | 1         | 0.18%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 316       | 55.63%  |
| Yes       | 252       | 44.37%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 467       | 82.51%  |
| No        | 99        | 17.49%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 548       | 96.82%  |
| No        | 18        | 3.18%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 424       | 74.65%  |
| No        | 144       | 25.35%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 118       | 20.81%  |
| Germany      | 62        | 10.93%  |
| Brazil       | 37        | 6.53%   |
| UK           | 34        | 6%      |
| Spain        | 25        | 4.41%   |
| India        | 24        | 4.23%   |
| Canada       | 19        | 3.35%   |
| Netherlands  | 16        | 2.82%   |
| Mexico       | 14        | 2.47%   |
| Italy        | 14        | 2.47%   |
| France       | 14        | 2.47%   |
| Poland       | 11        | 1.94%   |
| Austria      | 11        | 1.94%   |
| Belgium      | 10        | 1.76%   |
| South Africa | 9         | 1.59%   |
| Australia    | 9         | 1.59%   |
| Sweden       | 7         | 1.23%   |
| Czechia      | 7         | 1.23%   |
| Chile        | 7         | 1.23%   |
| Switzerland  | 6         | 1.06%   |
| Russia       | 6         | 1.06%   |
| Portugal     | 6         | 1.06%   |
| Norway       | 5         | 0.88%   |
| Japan        | 5         | 0.88%   |
| Hungary      | 5         | 0.88%   |
| Turkey       | 4         | 0.71%   |
| Romania      | 4         | 0.71%   |
| New Zealand  | 4         | 0.71%   |
| Indonesia    | 4         | 0.71%   |
| Bulgaria     | 4         | 0.71%   |
| Ukraine      | 3         | 0.53%   |
| Saudi Arabia | 3         | 0.53%   |
| Morocco      | 3         | 0.53%   |
| Finland      | 3         | 0.53%   |
| Vietnam      | 2         | 0.35%   |
| Singapore    | 2         | 0.35%   |
| Philippines  | 2         | 0.35%   |
| Moldova      | 2         | 0.35%   |
| Malaysia     | 2         | 0.35%   |
| Kenya        | 2         | 0.35%   |
| Israel       | 2         | 0.35%   |
| Ireland      | 2         | 0.35%   |
| Greece       | 2         | 0.35%   |
| Croatia      | 2         | 0.35%   |
| Colombia     | 2         | 0.35%   |
| Bangladesh   | 2         | 0.35%   |
| Argentina    | 2         | 0.35%   |
| Venezuela    | 1         | 0.18%   |
| Uruguay      | 1         | 0.18%   |
| Thailand     | 1         | 0.18%   |
| Tanzania     | 1         | 0.18%   |
| Slovenia     | 1         | 0.18%   |
| Slovakia     | 1         | 0.18%   |
| Qatar        | 1         | 0.18%   |
| Puerto Rico  | 1         | 0.18%   |
| Paraguay     | 1         | 0.18%   |
| Panama       | 1         | 0.18%   |
| Palestine    | 1         | 0.18%   |
| Pakistan     | 1         | 0.18%   |
| Nigeria      | 1         | 0.18%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Vienna           | 7         | 1.22%   |
| Amsterdam        | 5         | 0.87%   |
| Bernissart       | 4         | 0.7%    |
| Berlin           | 4         | 0.7%    |
| Warsaw           | 3         | 0.52%   |
| Sydney           | 3         | 0.52%   |
| S??o Lu?­s       | 3         | 0.52%   |
| Rome             | 3         | 0.52%   |
| Perth            | 3         | 0.52%   |
| New York         | 3         | 0.52%   |
| Madrid           | 3         | 0.52%   |
| London           | 3         | 0.52%   |
| Johannesburg     | 3         | 0.52%   |
| Glasgow          | 3         | 0.52%   |
| Chicago          | 3         | 0.52%   |
| Brussels         | 3         | 0.52%   |
| Blue Springs     | 3         | 0.52%   |
| Barcelona        | 3         | 0.52%   |
| Zagreb           | 2         | 0.35%   |
| Washington       | 2         | 0.35%   |
| Vicenza          | 2         | 0.35%   |
| Valencia         | 2         | 0.35%   |
| Taboao da Serra  | 2         | 0.35%   |
| Stuttgart        | 2         | 0.35%   |
| Stockholm        | 2         | 0.35%   |
| Smyrna           | 2         | 0.35%   |
| Seattle          | 2         | 0.35%   |
| S??o Paulo       | 2         | 0.35%   |
| Santiago         | 2         | 0.35%   |
| San Francisco    | 2         | 0.35%   |
| Red Deer         | 2         | 0.35%   |
| Recife           | 2         | 0.35%   |
| Pucking          | 2         | 0.35%   |
| Providence       | 2         | 0.35%   |
| Paris            | 2         | 0.35%   |
| Nairobi          | 2         | 0.35%   |
| Munich           | 2         | 0.35%   |
| Moscow           | 2         | 0.35%   |
| Morrow           | 2         | 0.35%   |
| Montreal         | 2         | 0.35%   |
| Mexico City      | 2         | 0.35%   |
| Melbourne        | 2         | 0.35%   |
| Maca?©           | 2         | 0.35%   |
| Hyderabad        | 2         | 0.35%   |
| Herzberg am Harz | 2         | 0.35%   |
| Helsinki         | 2         | 0.35%   |
| Hamburg          | 2         | 0.35%   |
| Freising         | 2         | 0.35%   |
| Ernakulam        | 2         | 0.35%   |
| Ecatepec         | 2         | 0.35%   |
| Dortmund         | 2         | 0.35%   |
| Delhi            | 2         | 0.35%   |
| Dallas           | 2         | 0.35%   |
| Colorado Springs | 2         | 0.35%   |
| Chennai          | 2         | 0.35%   |
| Charleston       | 2         | 0.35%   |
| Cape Town        | 2         | 0.35%   |
| Budapest         | 2         | 0.35%   |
| Birmingham       | 2         | 0.35%   |
| Bengaluru        | 2         | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 109       | 130    | 16.24%  |
| Seagate                     | 88        | 100    | 13.11%  |
| WDC                         | 69        | 79     | 10.28%  |
| Toshiba                     | 63        | 64     | 9.39%   |
| Sandisk                     | 53        | 60     | 7.9%    |
| Unknown                     | 47        | 56     | 7%      |
| Kingston                    | 30        | 36     | 4.47%   |
| Crucial                     | 28        | 33     | 4.17%   |
| Hitachi                     | 18        | 23     | 2.68%   |
| HGST                        | 18        | 23     | 2.68%   |
| SK Hynix                    | 15        | 21     | 2.24%   |
| Intel                       | 15        | 16     | 2.24%   |
| Micron Technology           | 14        | 15     | 2.09%   |
| A-DATA Technology           | 12        | 13     | 1.79%   |
| Intenso                     | 7         | 7      | 1.04%   |
| KIOXIA                      | 6         | 6      | 0.89%   |
| Apple                       | 6         | 7      | 0.89%   |
| Fujitsu                     | 5         | 6      | 0.75%   |
| SPCC                        | 4         | 5      | 0.6%    |
| PNY                         | 4         | 5      | 0.6%    |
| LITEONIT                    | 4         | 5      | 0.6%    |
| Transcend                   | 3         | 3      | 0.45%   |
| Netac                       | 3         | 3      | 0.45%   |
| GOODRAM                     | 3         | 3      | 0.45%   |
| Team                        | 2         | 2      | 0.3%    |
| SABRENT                     | 2         | 3      | 0.3%    |
| Phison                      | 2         | 3      | 0.3%    |
| Patriot                     | 2         | 2      | 0.3%    |
| OCZ                         | 2         | 2      | 0.3%    |
| LITEON                      | 2         | 2      | 0.3%    |
| Lite-On                     | 2         | 3      | 0.3%    |
| KingSpec                    | 2         | 2      | 0.3%    |
| JMicron                     | 2         | 3      | 0.3%    |
| Hewlett-Packard             | 2         | 2      | 0.3%    |
| China                       | 2         | 3      | 0.3%    |
| BHT                         | 2         | 2      | 0.3%    |
| Unknown                     | 2         | 2      | 0.3%    |
| Yangtze Memory Technologies | 1         | 1      | 0.15%   |
| Verbatim                    | 1         | 1      | 0.15%   |
| Vaseky                      | 1         | 2      | 0.15%   |
| TO Exter                    | 1         | 1      | 0.15%   |
| Teclast                     | 1         | 1      | 0.15%   |
| T-FORCE                     | 1         | 1      | 0.15%   |
| Star                        | 1         | 1      | 0.15%   |
| Space ke                    | 1         | 1      | 0.15%   |
| Realtek Semiconductor       | 1         | 1      | 0.15%   |
| PLEXTOR                     | 1         | 1      | 0.15%   |
| OSCOO                       | 1         | 1      | 0.15%   |
| MidasForce                  | 1         | 1      | 0.15%   |
| Micron/Crucial Technology   | 1         | 1      | 0.15%   |
| LS                          | 1         | 1      | 0.15%   |
| KIOXIA-EXCERIA              | 1         | 1      | 0.15%   |
| KESU                        | 1         | 1      | 0.15%   |
| HS-SSD-E100                 | 1         | 1      | 0.15%   |
| FORESEE                     | 1         | 1      | 0.15%   |
| E535N                       | 1         | 1      | 0.15%   |
| BUFFALO                     | 1         | 1      | 0.15%   |
| ASMT                        | 1         | 1      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Unknown MMC Card  32GB               | 19        | 2.73%   |
| Unknown MMC Card  64GB               | 13        | 1.87%   |
| Seagate ST1000LM035-1RK172 1TB       | 13        | 1.87%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 12        | 1.72%   |
| Sandisk NVMe SSD Drive 256GB         | 12        | 1.72%   |
| Samsung NVMe SSD Drive 512GB         | 11        | 1.58%   |
| Toshiba MQ04ABF100 1TB               | 9         | 1.29%   |
| Samsung NVMe SSD Drive 256GB         | 9         | 1.29%   |
| Kingston SA400S37240G 240GB SSD      | 9         | 1.29%   |
| Unknown MMC Card  128GB              | 7         | 1%      |
| Toshiba MQ01ABF050 500GB             | 7         | 1%      |
| Toshiba MQ01ABD100 1TB               | 7         | 1%      |
| Sandisk NVMe SSD Drive 512GB         | 7         | 1%      |
| Seagate ST9500325AS 500GB            | 6         | 0.86%   |
| Kingston SA400S37120G 120GB SSD      | 6         | 0.86%   |
| Crucial CT240BX500SSD1 240GB         | 6         | 0.86%   |
| Samsung SSD 860 EVO 500GB            | 5         | 0.72%   |
| Samsung SSD 850 EVO 500GB            | 5         | 0.72%   |
| Kingston SA400S37480G 480GB SSD      | 5         | 0.72%   |
| HGST HTS721010A9E630 1TB             | 5         | 0.72%   |
| Crucial CT500MX500SSD1 500GB         | 5         | 0.72%   |
| WDC WD10JPVX-22JC3T0 1TB             | 4         | 0.57%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 4         | 0.57%   |
| Seagate ST2000LM007-1R8174 2TB       | 4         | 0.57%   |
| Samsung SSD 860 EVO 250GB            | 4         | 0.57%   |
| Samsung SSD 860 EVO 1TB              | 4         | 0.57%   |
| Samsung NVMe SSD Drive 500GB         | 4         | 0.57%   |
| Micron NVMe SSD Drive 512GB          | 4         | 0.57%   |
| Intel NVMe SSD Drive 1024GB          | 4         | 0.57%   |
| HGST HTS725050A7E630 500GB           | 4         | 0.57%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 3         | 0.43%   |
| Unknown SD/MMC/MS PRO 128GB          | 3         | 0.43%   |
| Toshiba MK2555GSX 250GB              | 3         | 0.43%   |
| Toshiba MK2552GSX 250GB              | 3         | 0.43%   |
| SK Hynix NVMe SSD Drive 512GB        | 3         | 0.43%   |
| SK Hynix NVMe SSD Drive 256GB        | 3         | 0.43%   |
| Seagate ST500LT012-9WS142 500GB      | 3         | 0.43%   |
| Seagate ST500LT012-1DG142 500GB      | 3         | 0.43%   |
| Seagate ST1000LM049-2GH172 1TB       | 3         | 0.43%   |
| SanDisk X400 M.2 2280 256GB SSD      | 3         | 0.43%   |
| Sandisk NVMe SSD Drive 1TB           | 3         | 0.43%   |
| Samsung SSD 850 EVO 250GB            | 3         | 0.43%   |
| Samsung SSD 840 EVO 250GB            | 3         | 0.43%   |
| Samsung NVMe SSD Drive 2TB           | 3         | 0.43%   |
| Samsung NVMe SSD Drive 1TB           | 3         | 0.43%   |
| PNY CS900 120GB SSD                  | 3         | 0.43%   |
| KIOXIA NVMe SSD Drive 512GB          | 3         | 0.43%   |
| Intel NVMe SSD Drive 512GB           | 3         | 0.43%   |
| Hitachi HTS547575A9E384 752GB        | 3         | 0.43%   |
| HGST HTS541010A9E680 1TB             | 3         | 0.43%   |
| Crucial CT480BX500SSD1 480GB         | 3         | 0.43%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 2         | 0.29%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 2         | 0.29%   |
| WDC WD5000LPVT-22G33T0 500GB         | 2         | 0.29%   |
| WDC WD5000LPLX-60ZNTT1 500GB         | 2         | 0.29%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 2         | 0.29%   |
| WDC WD10SPZX-60Z10T0 1TB             | 2         | 0.29%   |
| WDC WD10SPZX-24Z10 1TB               | 2         | 0.29%   |
| WDC WD10JPVX-60JC3T0 1TB             | 2         | 0.29%   |
| WDC PC SN520 SDAPNUW-512G-1006 512GB | 2         | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 87        | 98     | 37.02%  |
| WDC                 | 49        | 53     | 20.85%  |
| Toshiba             | 46        | 47     | 19.57%  |
| Hitachi             | 18        | 23     | 7.66%   |
| HGST                | 18        | 23     | 7.66%   |
| Samsung Electronics | 5         | 5      | 2.13%   |
| Fujitsu             | 5         | 6      | 2.13%   |
| Unknown             | 3         | 3      | 1.28%   |
| TO Exter            | 1         | 1      | 0.43%   |
| KESU                | 1         | 1      | 0.43%   |
| Intenso             | 1         | 1      | 0.43%   |
| Apple               | 1         | 1      | 0.43%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 66        | 73     | 25.38%  |
| Crucial             | 28        | 32     | 10.77%  |
| SanDisk             | 27        | 32     | 10.38%  |
| Kingston            | 27        | 33     | 10.38%  |
| WDC                 | 14        | 18     | 5.38%   |
| Toshiba             | 11        | 11     | 4.23%   |
| A-DATA Technology   | 8         | 9      | 3.08%   |
| SK Hynix            | 7         | 7      | 2.69%   |
| Micron Technology   | 7         | 8      | 2.69%   |
| Intenso             | 6         | 6      | 2.31%   |
| Intel               | 5         | 5      | 1.92%   |
| SPCC                | 4         | 5      | 1.54%   |
| PNY                 | 4         | 5      | 1.54%   |
| LITEONIT            | 4         | 5      | 1.54%   |
| Apple               | 4         | 4      | 1.54%   |
| Transcend           | 3         | 3      | 1.15%   |
| Netac               | 3         | 3      | 1.15%   |
| GOODRAM             | 3         | 3      | 1.15%   |
| Team                | 2         | 2      | 0.77%   |
| SABRENT             | 2         | 3      | 0.77%   |
| Patriot             | 2         | 2      | 0.77%   |
| OCZ                 | 2         | 2      | 0.77%   |
| LITEON              | 2         | 2      | 0.77%   |
| KingSpec            | 2         | 2      | 0.77%   |
| Hewlett-Packard     | 2         | 2      | 0.77%   |
| China               | 2         | 3      | 0.77%   |
| BHT                 | 2         | 2      | 0.77%   |
| Verbatim            | 1         | 1      | 0.38%   |
| Teclast             | 1         | 1      | 0.38%   |
| Star                | 1         | 1      | 0.38%   |
| PLEXTOR             | 1         | 1      | 0.38%   |
| OSCOO               | 1         | 1      | 0.38%   |
| MidasForce          | 1         | 1      | 0.38%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.38%   |
| HS-SSD-E100         | 1         | 1      | 0.38%   |
| FORESEE             | 1         | 1      | 0.38%   |
| BUFFALO             | 1         | 1      | 0.38%   |
| ASMT                | 1         | 1      | 0.38%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 246       | 293    | 37.9%   |
| HDD     | 230       | 262    | 35.44%  |
| NVMe    | 119       | 152    | 18.34%  |
| MMC     | 46        | 55     | 7.09%   |
| Unknown | 8         | 10     | 1.23%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 445       | 543    | 70.86%  |
| NVMe | 118       | 150    | 18.79%  |
| MMC  | 46        | 55     | 7.32%   |
| SAS  | 19        | 24     | 3.03%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 323       | 380    | 68.72%  |
| 0.51-1.0   | 134       | 158    | 28.51%  |
| 1.01-2.0   | 11        | 13     | 2.34%   |
| 3.01-4.0   | 1         | 3      | 0.21%   |
| 4.01-10.0  | 1         | 1      | 0.21%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 209       | 36.6%   |
| 251-500        | 156       | 27.32%  |
| 501-1000       | 80        | 14.01%  |
| 51-100         | 49        | 8.58%   |
| 21-50          | 30        | 5.25%   |
| 1001-2000      | 17        | 2.98%   |
| 1-20           | 12        | 2.1%    |
| Unknown        | 8         | 1.4%    |
| 2001-3000      | 6         | 1.05%   |
| More than 3000 | 4         | 0.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 277       | 47.27%  |
| 21-50          | 160       | 27.3%   |
| 51-100         | 55        | 9.39%   |
| 101-250        | 48        | 8.19%   |
| 251-500        | 22        | 3.75%   |
| 501-1000       | 13        | 2.22%   |
| Unknown        | 8         | 1.37%   |
| More than 3000 | 2         | 0.34%   |
| 2001-3000      | 1         | 0.17%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Toshiba MQ02ABD100H 1TB            | 2         | 2      | 20%     |
| WDC WD10SPZX-75Z10T2 1TB           | 1         | 1      | 10%     |
| WDC WD10JPVX-22JC3T0 1TB           | 1         | 1      | 10%     |
| Seagate ST9500420AS 500GB          | 1         | 1      | 10%     |
| Seagate ST9200420ASG 200GB         | 1         | 1      | 10%     |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 10%     |
| HGST HTS725050A7E630 500GB         | 1         | 1      | 10%     |
| HGST HTS545050A7E680 500GB         | 1         | 1      | 10%     |
| Hewlett-Packard SSD S600 240GB     | 1         | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor          | Notebooks | Drives | Percent |
|-----------------|-----------|--------|---------|
| Seagate         | 3         | 3      | 30%     |
| WDC             | 2         | 2      | 20%     |
| Toshiba         | 2         | 2      | 20%     |
| HGST            | 2         | 2      | 20%     |
| Hewlett-Packard | 1         | 1      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 33.33%  |
| WDC     | 2         | 2      | 22.22%  |
| Toshiba | 2         | 2      | 22.22%  |
| HGST    | 2         | 2      | 22.22%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 9      | 90%     |
| SSD  | 1         | 1      | 10%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                 | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| SanDisk SSD i100 24GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SanDisk | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 506       | 689    | 87.54%  |
| Works    | 61        | 72     | 10.55%  |
| Malfunc  | 10        | 10     | 1.73%   |
| Failed   | 1         | 1      | 0.17%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 423       | 67.57%  |
| AMD                              | 75        | 11.98%  |
| Samsung Electronics              | 46        | 7.35%   |
| Sandisk                          | 29        | 4.63%   |
| SK Hynix                         | 8         | 1.28%   |
| Micron Technology                | 7         | 1.12%   |
| KIOXIA                           | 7         | 1.12%   |
| Toshiba America Info Systems     | 5         | 0.8%    |
| ADATA Technology                 | 4         | 0.64%   |
| Nvidia                           | 3         | 0.48%   |
| Kingston Technology Company      | 3         | 0.48%   |
| Realtek Semiconductor            | 2         | 0.32%   |
| Phison Electronics               | 2         | 0.32%   |
| Micron/Crucial Technology        | 2         | 0.32%   |
| Marvell Technology Group         | 2         | 0.32%   |
| Lite-On Technology               | 2         | 0.32%   |
| ASMedia Technology               | 2         | 0.32%   |
| Yangtze Memory Technologies      | 1         | 0.16%   |
| VIA Technologies                 | 1         | 0.16%   |
| Silicon Integrated Systems [SiS] | 1         | 0.16%   |
| Apple                            | 1         | 0.16%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 62        | 9.21%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 55        | 8.17%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 50        | 7.43%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 43        | 6.39%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 40        | 5.94%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 32        | 4.75%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 22        | 3.27%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 21        | 3.12%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 20        | 2.97%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 17        | 2.53%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 16        | 2.38%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 15        | 2.23%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 12        | 1.78%   |
| Samsung NVMe SSD Controller 980                                                  | 11        | 1.63%   |
| Intel Volume Management Device NVMe RAID Controller                              | 11        | 1.63%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 11        | 1.63%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 11        | 1.63%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 9         | 1.34%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 9         | 1.34%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 8         | 1.19%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 8         | 1.19%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 8         | 1.19%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 8         | 1.19%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 7         | 1.04%   |
| Micron Non-Volatile memory controller                                            | 7         | 1.04%   |
| KIOXIA Non-Volatile memory controller                                            | 7         | 1.04%   |
| Intel SSD 660P Series                                                            | 7         | 1.04%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 7         | 1.04%   |
| Intel Comet Lake SATA AHCI Controller                                            | 7         | 1.04%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 7         | 1.04%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 6         | 0.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 6         | 0.89%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 5         | 0.74%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 4         | 0.59%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 4         | 0.59%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 4         | 0.59%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 4         | 0.59%   |
| Sandisk Non-Volatile memory controller                                           | 3         | 0.45%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 0.45%   |
| Nvidia MCP79 AHCI Controller                                                     | 3         | 0.45%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3         | 0.45%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 3         | 0.45%   |
| AMD FCH IDE Controller                                                           | 3         | 0.45%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 2         | 0.3%    |
| SK Hynix Gold P31 SSD                                                            | 2         | 0.3%    |
| SK Hynix BC511                                                                   | 2         | 0.3%    |
| Sandisk PC SN520 NVMe SSD                                                        | 2         | 0.3%    |
| Samsung NVMe SSD Controller SM951/PM951                                          | 2         | 0.3%    |
| Samsung Apple PCIe SSD                                                           | 2         | 0.3%    |
| Realtek Realtek Non-Volatile memory controller                                   | 2         | 0.3%    |
| Marvell Group 88SS9183 PCIe SSD Controller                                       | 2         | 0.3%    |
| Lite-On Non-Volatile memory controller                                           | 2         | 0.3%    |
| Intel SATA Controller [RAID mode]                                                | 2         | 0.3%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 0.3%    |
| Intel Mobile PM965/GM965 PT IDER Controller                                      | 2         | 0.3%    |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]    | 2         | 0.3%    |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile       | 2         | 0.3%    |
| ASMedia ASM1062 Serial ATA Controller                                            | 2         | 0.3%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 2         | 0.3%    |
| AMD IXP SB4x0 IDE Controller                                                     | 2         | 0.3%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 435       | 66.92%  |
| NVMe | 118       | 18.15%  |
| RAID | 58        | 8.92%   |
| IDE  | 39        | 6%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 475       | 83.92%  |
| AMD    | 91        | 16.08%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 11        | 1.94%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 10        | 1.77%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 10        | 1.77%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 9         | 1.59%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 8         | 1.41%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 8         | 1.41%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 7         | 1.24%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 7         | 1.24%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 7         | 1.24%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 6         | 1.06%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 6         | 1.06%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 6         | 1.06%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 6         | 1.06%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 6         | 1.06%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 6         | 1.06%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 6         | 1.06%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 5         | 0.88%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 5         | 0.88%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 5         | 0.88%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 5         | 0.88%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 5         | 0.88%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 5         | 0.88%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 0.71%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 4         | 0.71%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 4         | 0.71%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 4         | 0.71%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 4         | 0.71%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 4         | 0.71%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 4         | 0.71%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 4         | 0.71%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 4         | 0.71%   |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 4         | 0.71%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 4         | 0.71%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 4         | 0.71%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 4         | 0.71%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 4         | 0.71%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 4         | 0.71%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 4         | 0.71%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 4         | 0.71%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 4         | 0.71%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 3         | 0.53%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 3         | 0.53%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 3         | 0.53%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 0.53%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 0.53%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 3         | 0.53%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 3         | 0.53%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 3         | 0.53%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 3         | 0.53%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 3         | 0.53%   |
| Intel Core i7 CPU Q 740 @ 1.73GHz             | 3         | 0.53%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 3         | 0.53%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 3         | 0.53%   |
| Intel Core i5-4310U CPU @ 2.00GHz             | 3         | 0.53%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 3         | 0.53%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 0.53%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 3         | 0.53%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 3         | 0.53%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 3         | 0.53%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 3         | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5                        | 155       | 27.39%  |
| Intel Core i7                        | 110       | 19.43%  |
| Intel Core i3                        | 58        | 10.25%  |
| Intel Celeron                        | 37        | 6.54%   |
| Intel Core 2 Duo                     | 34        | 6.01%   |
| Intel Pentium                        | 26        | 4.59%   |
| Other                                | 22        | 3.89%   |
| AMD Ryzen 5                          | 21        | 3.71%   |
| Intel Atom                           | 17        | 3%      |
| AMD Ryzen 7                          | 12        | 2.12%   |
| AMD A6                               | 11        | 1.94%   |
| AMD A10                              | 8         | 1.41%   |
| AMD E1                               | 5         | 0.88%   |
| Intel Pentium Dual                   | 4         | 0.71%   |
| AMD Ryzen 3                          | 4         | 0.71%   |
| AMD E                                | 4         | 0.71%   |
| AMD A8                               | 4         | 0.71%   |
| Intel Core m5                        | 3         | 0.53%   |
| AMD A4                               | 3         | 0.53%   |
| Intel Pentium Silver                 | 2         | 0.35%   |
| Intel Pentium Dual-Core              | 2         | 0.35%   |
| Intel Core M                         | 2         | 0.35%   |
| Intel Celeron Dual-Core              | 2         | 0.35%   |
| AMD Turion X2 Ultra Dual-Core Mobile | 2         | 0.35%   |
| AMD FX                               | 2         | 0.35%   |
| AMD E2                               | 2         | 0.35%   |
| Intel Xeon                           | 1         | 0.18%   |
| Intel Genuine                        | 1         | 0.18%   |
| Intel Core i9                        | 1         | 0.18%   |
| Intel Celeron M                      | 1         | 0.18%   |
| AMD Turion 64 X2 Mobile              | 1         | 0.18%   |
| AMD Turion 64 Mobile                 | 1         | 0.18%   |
| AMD Sempron                          | 1         | 0.18%   |
| AMD Ryzen 9                          | 1         | 0.18%   |
| AMD Ryzen 7 PRO                      | 1         | 0.18%   |
| AMD Phenom II                        | 1         | 0.18%   |
| AMD C-60                             | 1         | 0.18%   |
| AMD Athlon X2                        | 1         | 0.18%   |
| AMD Athlon II                        | 1         | 0.18%   |
| AMD Athlon                           | 1         | 0.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 338       | 59.72%  |
| 4      | 183       | 32.33%  |
| 6      | 21        | 3.71%   |
| 8      | 16        | 2.83%   |
| 1      | 6         | 1.06%   |
| 10     | 1         | 0.18%   |
| 3      | 1         | 0.18%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 566       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 396       | 69.96%  |
| 1      | 170       | 30.04%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 566       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 55        | 9.63%   |
| 0x306a9    | 50        | 8.76%   |
| Unknown    | 35        | 6.13%   |
| 0x40651    | 33        | 5.78%   |
| 0x406e3    | 25        | 4.38%   |
| 0x806ea    | 23        | 4.03%   |
| 0x20655    | 20        | 3.5%    |
| 0x1067a    | 18        | 3.15%   |
| 0x806ec    | 17        | 2.98%   |
| 0x306d4    | 17        | 2.98%   |
| 0x806e9    | 15        | 2.63%   |
| 0x806c1    | 15        | 2.63%   |
| 0x30678    | 13        | 2.28%   |
| 0x406c4    | 12        | 2.1%    |
| 0x906ea    | 11        | 1.93%   |
| 0x706e5    | 11        | 1.93%   |
| 0x306c3    | 11        | 1.93%   |
| 0x08108102 | 11        | 1.93%   |
| 0x506c9    | 10        | 1.75%   |
| 0x20652    | 10        | 1.75%   |
| 0x906e9    | 9         | 1.58%   |
| 0x6fd      | 9         | 1.58%   |
| 0x10676    | 9         | 1.58%   |
| 0x07030105 | 9         | 1.58%   |
| 0x08108109 | 8         | 1.4%    |
| 0x706a8    | 7         | 1.23%   |
| 0x406c3    | 7         | 1.23%   |
| 0xa0652    | 6         | 1.05%   |
| 0x08600106 | 6         | 1.05%   |
| 0x05000119 | 6         | 1.05%   |
| 0x6fb      | 5         | 0.88%   |
| 0x806eb    | 4         | 0.7%    |
| 0x506e3    | 4         | 0.7%    |
| 0x106e5    | 4         | 0.7%    |
| 0x07030106 | 4         | 0.7%    |
| 0x06006704 | 4         | 0.7%    |
| 0x806d1    | 3         | 0.53%   |
| 0x08608103 | 3         | 0.53%   |
| 0x08600104 | 3         | 0.53%   |
| 0x08600103 | 3         | 0.53%   |
| 0x06006705 | 3         | 0.53%   |
| 0x0600611a | 3         | 0.53%   |
| 0x06003106 | 3         | 0.53%   |
| 0x03000027 | 3         | 0.53%   |
| 0x02000057 | 3         | 0.53%   |
| 0x706a1    | 2         | 0.35%   |
| 0x6fa      | 2         | 0.35%   |
| 0x40661    | 2         | 0.35%   |
| 0x30661    | 2         | 0.35%   |
| 0x106ca    | 2         | 0.35%   |
| 0x0a50000c | 2         | 0.35%   |
| 0x0700010f | 2         | 0.35%   |
| 0x06001119 | 2         | 0.35%   |
| 0x010000c8 | 2         | 0.35%   |
| 0xa0655    | 1         | 0.18%   |
| 0x906ed    | 1         | 0.18%   |
| 0x906c0    | 1         | 0.18%   |
| 0x6f6      | 1         | 0.18%   |
| 0x506ca    | 1         | 0.18%   |
| 0x30673    | 1         | 0.18%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 90        | 15.9%   |
| SandyBridge     | 57        | 10.07%  |
| IvyBridge       | 52        | 9.19%   |
| Haswell         | 50        | 8.83%   |
| Silvermont      | 34        | 6.01%   |
| Westmere        | 31        | 5.48%   |
| Skylake         | 31        | 5.48%   |
| Penryn          | 27        | 4.77%   |
| Zen+            | 20        | 3.53%   |
| Core            | 18        | 3.18%   |
| Broadwell       | 17        | 3%      |
| TigerLake       | 16        | 2.83%   |
| Puma            | 14        | 2.47%   |
| IceLake         | 14        | 2.47%   |
| Zen 2           | 12        | 2.12%   |
| Goldmont        | 11        | 1.94%   |
| Excavator       | 11        | 1.94%   |
| Goldmont plus   | 9         | 1.59%   |
| CometLake       | 8         | 1.41%   |
| Bobcat          | 6         | 1.06%   |
| Nehalem         | 5         | 0.88%   |
| Zen 3           | 4         | 0.71%   |
| K8 & K10 hybrid | 4         | 0.71%   |
| Bonnell         | 4         | 0.71%   |
| Unknown         | 4         | 0.71%   |
| Steamroller     | 3         | 0.53%   |
| Piledriver      | 3         | 0.53%   |
| K10 Llano       | 3         | 0.53%   |
| Jaguar          | 3         | 0.53%   |
| K8 Hammer       | 2         | 0.35%   |
| K10             | 2         | 0.35%   |
| Tremont         | 1         | 0.18%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 428       | 62.94%  |
| Nvidia                           | 130       | 19.12%  |
| AMD                              | 121       | 17.79%  |
| Silicon Integrated Systems [SiS] | 1         | 0.15%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 52        | 7.37%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 49        | 6.94%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 36        | 5.1%    |
| Intel Core Processor Integrated Graphics Controller                                      | 27        | 3.82%   |
| Intel UHD Graphics 620                                                                   | 24        | 3.4%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 22        | 3.12%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 20        | 2.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 19        | 2.69%   |
| Intel HD Graphics 620                                                                    | 16        | 2.27%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 15        | 2.12%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 13        | 1.84%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 13        | 1.84%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 12        | 1.7%    |
| Intel HD Graphics 5500                                                                   | 12        | 1.7%    |
| AMD Renoir                                                                               | 12        | 1.7%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 11        | 1.56%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 11        | 1.56%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 10        | 1.42%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 10        | 1.42%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 9         | 1.27%   |
| Intel HD Graphics 630                                                                    | 9         | 1.27%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 9         | 1.27%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 9         | 1.27%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 9         | 1.27%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 8         | 1.13%   |
| Intel HD Graphics 500                                                                    | 8         | 1.13%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 8         | 1.13%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 7         | 0.99%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 7         | 0.99%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 7         | 0.99%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 6         | 0.85%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 6         | 0.85%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 5         | 0.71%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 4         | 0.57%   |
| Intel HD Graphics 530                                                                    | 4         | 0.57%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 4         | 0.57%   |
| AMD Lucienne                                                                             | 4         | 0.57%   |
| Nvidia TU117M                                                                            | 3         | 0.42%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 3         | 0.42%   |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 0.42%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 3         | 0.42%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 3         | 0.42%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 3         | 0.42%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 0.42%   |
| Intel Tiger Lake UHD Graphics                                                            | 3         | 0.42%   |
| Intel HD Graphics 5300                                                                   | 3         | 0.42%   |
| Intel HD Graphics 515                                                                    | 3         | 0.42%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 3         | 0.42%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 0.42%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 3         | 0.42%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 3         | 0.42%   |
| AMD RS780M [Mobility Radeon HD 3200]                                                     | 3         | 0.42%   |
| AMD Mullins [Radeon R2 Graphics]                                                         | 3         | 0.42%   |
| AMD Cezanne                                                                              | 3         | 0.42%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                                  | 2         | 0.28%   |
| Nvidia GT218M [NVS 3100M]                                                                | 2         | 0.28%   |
| Nvidia GT218M [GeForce 310M]                                                             | 2         | 0.28%   |
| Nvidia GP108M [GeForce MX250]                                                            | 2         | 0.28%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.28%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 2         | 0.28%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 324       | 57.24%  |
| Intel + Nvidia | 88        | 15.55%  |
| 1 x AMD        | 82        | 14.49%  |
| 1 x Nvidia     | 31        | 5.48%   |
| Intel + AMD    | 16        | 2.83%   |
| 2 x AMD        | 13        | 2.3%    |
| AMD + Nvidia   | 10        | 1.77%   |
| 2 x Nvidia     | 1         | 0.18%   |
| 1 x SiS        | 1         | 0.18%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 487       | 86.04%  |
| Proprietary | 71        | 12.54%  |
| Unknown     | 8         | 1.41%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 370       | 64.57%  |
| 0.01-0.5   | 64        | 11.17%  |
| 1.01-2.0   | 56        | 9.77%   |
| 0.51-1.0   | 43        | 7.5%    |
| 3.01-4.0   | 20        | 3.49%   |
| 5.01-6.0   | 9         | 1.57%   |
| 7.01-8.0   | 8         | 1.4%    |
| 2.01-3.0   | 2         | 0.35%   |
| 8.01-16.0  | 1         | 0.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 116       | 19.4%   |
| Chimei Innolux          | 95        | 15.89%  |
| LG Display              | 84        | 14.05%  |
| Samsung Electronics     | 74        | 12.37%  |
| BOE                     | 72        | 12.04%  |
| Chi Mei Optoelectronics | 23        | 3.85%   |
| Sharp                   | 15        | 2.51%   |
| Apple                   | 15        | 2.51%   |
| PANDA                   | 12        | 2.01%   |
| Lenovo                  | 11        | 1.84%   |
| Dell                    | 11        | 1.84%   |
| LG Philips              | 8         | 1.34%   |
| Goldstar                | 7         | 1.17%   |
| LGD                     | 5         | 0.84%   |
| Acer                    | 4         | 0.67%   |
| Vizio                   | 3         | 0.5%    |
| Hewlett-Packard         | 3         | 0.5%    |
| CPT                     | 3         | 0.5%    |
| BenQ                    | 3         | 0.5%    |
| AOC                     | 3         | 0.5%    |
| Sony                    | 2         | 0.33%   |
| Philips                 | 2         | 0.33%   |
| InfoVision              | 2         | 0.33%   |
| Iiyama                  | 2         | 0.33%   |
| HannStar                | 2         | 0.33%   |
| BOE Technology Group    | 2         | 0.33%   |
| VIE                     | 1         | 0.17%   |
| Unknown                 | 1         | 0.17%   |
| SLD                     | 1         | 0.17%   |
| Sceptre Tech            | 1         | 0.17%   |
| Sanyo                   | 1         | 0.17%   |
| Panasonic               | 1         | 0.17%   |
| MStar                   | 1         | 0.17%   |
| KDC                     | 1         | 0.17%   |
| KDB                     | 1         | 0.17%   |
| ITE                     | 1         | 0.17%   |
| InnoLux Display         | 1         | 0.17%   |
| HIC                     | 1         | 0.17%   |
| Gateway                 | 1         | 0.17%   |
| Fujitsu Siemens         | 1         | 0.17%   |
| ELD                     | 1         | 0.17%   |
| Eizo                    | 1         | 0.17%   |
| Belinea                 | 1         | 0.17%   |
| Ancor Communications    | 1         | 0.17%   |
| Unknown                 | 1         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 6         | 1%      |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 6         | 1%      |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 6         | 1%      |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 5         | 0.83%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 5         | 0.83%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 5         | 0.83%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 4         | 0.66%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 4         | 0.66%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch          | 4         | 0.66%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 4         | 0.66%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x193mm 15.5-inch          | 4         | 0.66%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 4         | 0.66%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 4         | 0.66%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 4         | 0.66%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 4         | 0.66%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 4         | 0.66%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 344x194mm 15.5-inch     | 3         | 0.5%    |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x194mm 15.5-inch     | 3         | 0.5%    |
| PANDA LCD Monitor NCP0036 1920x1080 340x190mm 15.3-inch                  | 3         | 0.5%    |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 3         | 0.5%    |
| Chimei Innolux LCD Monitor CMN1734 1600x900 382x214mm 17.2-inch          | 3         | 0.5%    |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 3         | 0.5%    |
| Chi Mei Optoelectronics LCD Monitor CMO1590 1366x768 344x194mm 15.5-inch | 3         | 0.5%    |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 3         | 0.5%    |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 3         | 0.5%    |
| BOE LCD Monitor BOE0653 1920x1080 309x173mm 13.9-inch                    | 3         | 0.5%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 3         | 0.5%    |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 3         | 0.5%    |
| AU Optronics LCD Monitor AUO113D 1920x1080 309x173mm 13.9-inch           | 3         | 0.5%    |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 3         | 0.5%    |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 3         | 0.5%    |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                  | 2         | 0.33%   |
| Samsung Electronics LCD Monitor SEC504B 1600x900 382x215mm 17.3-inch     | 2         | 0.33%   |
| Samsung Electronics LCD Monitor SEC3959 1366x768 344x194mm 15.5-inch     | 2         | 0.33%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 2         | 0.33%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch     | 2         | 0.33%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 293x165mm 13.2-inch    | 2         | 0.33%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch     | 2         | 0.33%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 2         | 0.33%   |
| Samsung Electronics LCD Monitor SDC484E 1600x900 309x174mm 14.0-inch     | 2         | 0.33%   |
| Samsung Electronics LCD Monitor SDC4651 1366x768 344x194mm 15.5-inch     | 2         | 0.33%   |
| Samsung Electronics LCD Monitor SDC434A 3200x1800 293x165mm 13.2-inch    | 2         | 0.33%   |
| LGD LCD Monitor 1920x1080                                                | 2         | 0.33%   |
| LG Philips LP154WX4-TLC8 LPL0120 1280x800 331x207mm 15.4-inch            | 2         | 0.33%   |
| LG Display LCD Monitor LGD0493 1366x768 344x194mm 15.5-inch              | 2         | 0.33%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch              | 2         | 0.33%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch              | 2         | 0.33%   |
| LG Display LCD Monitor LGD0360 1600x900 294x166mm 13.3-inch              | 2         | 0.33%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch              | 2         | 0.33%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 2         | 0.33%   |
| LG Display LCD Monitor LGD0212 1366x768 309x174mm 14.0-inch              | 2         | 0.33%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                 | 2         | 0.33%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch                  | 2         | 0.33%   |
| Dell P2419H DELD0DA 1920x1080 530x300mm 24.0-inch                        | 2         | 0.33%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch         | 2         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15CC 1366x768 344x193mm 15.5-inch          | 2         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 2         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch          | 2         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15BD 1366x768 344x193mm 15.5-inch          | 2         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15B8 1366x768 344x194mm 15.5-inch          | 2         | 0.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 236       | 40.34%  |
| 1920x1080 (FHD)    | 193       | 32.99%  |
| 1600x900 (HD+)     | 48        | 8.21%   |
| 1280x800 (WXGA)    | 29        | 4.96%   |
| 3840x2160 (4K)     | 14        | 2.39%   |
| 1440x900 (WXGA+)   | 9         | 1.54%   |
| Unknown            | 6         | 1.03%   |
| 2560x1440 (QHD)    | 5         | 0.85%   |
| 2560x1600          | 4         | 0.68%   |
| 1680x1050 (WSXGA+) | 4         | 0.68%   |
| 3840x2400          | 3         | 0.51%   |
| 3200x1800 (QHD+)   | 3         | 0.51%   |
| 2880x1800          | 3         | 0.51%   |
| 2256x1504          | 3         | 0.51%   |
| 2160x1440          | 3         | 0.51%   |
| 1920x1200 (WUXGA)  | 3         | 0.51%   |
| 1280x1024 (SXGA)   | 3         | 0.51%   |
| 1024x600           | 3         | 0.51%   |
| 5760x1080          | 2         | 0.34%   |
| 1360x768           | 2         | 0.34%   |
| 4480x1600          | 1         | 0.17%   |
| 3840x1200          | 1         | 0.17%   |
| 3840x1080          | 1         | 0.17%   |
| 3600x1080          | 1         | 0.17%   |
| 2560x1080          | 1         | 0.17%   |
| 1920x540           | 1         | 0.17%   |
| 1920x515           | 1         | 0.17%   |
| 1920x1280          | 1         | 0.17%   |
| 1680x945           | 1         | 0.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 248       | 41.82%  |
| 13      | 96        | 16.19%  |
| 14      | 67        | 11.3%   |
| 17      | 58        | 9.78%   |
| 12      | 22        | 3.71%   |
| Unknown | 17        | 2.87%   |
| 11      | 14        | 2.36%   |
| 24      | 12        | 2.02%   |
| 27      | 8         | 1.35%   |
| 18      | 7         | 1.18%   |
| 23      | 6         | 1.01%   |
| 21      | 5         | 0.84%   |
| 20      | 4         | 0.67%   |
| 10      | 4         | 0.67%   |
| 31      | 3         | 0.51%   |
| 16      | 3         | 0.51%   |
| 72      | 2         | 0.34%   |
| 25      | 2         | 0.34%   |
| 19      | 2         | 0.34%   |
| 84      | 1         | 0.17%   |
| 74      | 1         | 0.17%   |
| 64      | 1         | 0.17%   |
| 54      | 1         | 0.17%   |
| 52      | 1         | 0.17%   |
| 49      | 1         | 0.17%   |
| 48      | 1         | 0.17%   |
| 47      | 1         | 0.17%   |
| 46      | 1         | 0.17%   |
| 40      | 1         | 0.17%   |
| 37      | 1         | 0.17%   |
| 34      | 1         | 0.17%   |
| 32      | 1         | 0.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 358       | 60.47%  |
| 201-300     | 87        | 14.7%   |
| 351-400     | 66        | 11.15%  |
| 501-600     | 27        | 4.56%   |
| 401-500     | 18        | 3.04%   |
| Unknown     | 17        | 2.87%   |
| 1001-1500   | 7         | 1.18%   |
| 601-700     | 4         | 0.68%   |
| 1501-2000   | 4         | 0.68%   |
| 801-900     | 2         | 0.34%   |
| 701-800     | 2         | 0.34%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 467       | 85.37%  |
| 16/10   | 53        | 9.69%   |
| Unknown | 13        | 2.38%   |
| 3/2     | 8         | 1.46%   |
| 5/4     | 3         | 0.55%   |
| 4/3     | 1         | 0.18%   |
| 3.73    | 1         | 0.18%   |
| 21/9    | 1         | 0.18%   |

Monitor Area
------------

Area in inchÂ²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inchÂ² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 249       | 41.92%  |
| 81-90          | 128       | 21.55%  |
| 121-130        | 48        | 8.08%   |
| 71-80          | 35        | 5.89%   |
| 201-250        | 22        | 3.7%    |
| 61-70          | 21        | 3.54%   |
| Unknown        | 17        | 2.86%   |
| 51-60          | 14        | 2.36%   |
| More than 1000 | 9         | 1.52%   |
| 141-150        | 9         | 1.52%   |
| 301-350        | 8         | 1.35%   |
| 151-200        | 8         | 1.35%   |
| 131-140        | 7         | 1.18%   |
| 351-500        | 5         | 0.84%   |
| 41-50          | 4         | 0.67%   |
| 501-1000       | 4         | 0.67%   |
| 251-300        | 2         | 0.34%   |
| 111-120        | 2         | 0.34%   |
| 91-100         | 2         | 0.34%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 253       | 42.95%  |
| 121-160       | 185       | 31.41%  |
| 51-100        | 81        | 13.75%  |
| 161-240       | 31        | 5.26%   |
| Unknown       | 17        | 2.89%   |
| More than 240 | 12        | 2.04%   |
| 1-50          | 10        | 1.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 494       | 86.82%  |
| 2     | 66        | 11.6%   |
| 0     | 7         | 1.23%   |
| 3     | 2         | 0.35%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 295       | 32.35%  |
| Intel                             | 261       | 28.62%  |
| Qualcomm Atheros                  | 155       | 17%     |
| Broadcom                          | 74        | 8.11%   |
| Broadcom Limited                  | 25        | 2.74%   |
| Marvell Technology Group          | 10        | 1.1%    |
| Ralink                            | 9         | 0.99%   |
| Dell                              | 9         | 0.99%   |
| ASIX Electronics                  | 9         | 0.99%   |
| Xiaomi                            | 7         | 0.77%   |
| Ralink Technology                 | 6         | 0.66%   |
| DisplayLink                       | 5         | 0.55%   |
| TP-Link                           | 4         | 0.44%   |
| Huawei Technologies               | 4         | 0.44%   |
| Hewlett-Packard                   | 4         | 0.44%   |
| Samsung Electronics               | 3         | 0.33%   |
| MediaTek                          | 3         | 0.33%   |
| JMicron Technology                | 3         | 0.33%   |
| T & A Mobile Phones               | 2         | 0.22%   |
| Sierra Wireless                   | 2         | 0.22%   |
| Qualcomm                          | 2         | 0.22%   |
| Nvidia                            | 2         | 0.22%   |
| Ericsson Business Mobile Networks | 2         | 0.22%   |
| D-Link System                     | 2         | 0.22%   |
| ZyXEL Communications              | 1         | 0.11%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.11%   |
| Qualcomm Atheros Communications   | 1         | 0.11%   |
| OPPO Electronics                  | 1         | 0.11%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.11%   |
| Novatel Wireless                  | 1         | 0.11%   |
| NetGear                           | 1         | 0.11%   |
| Motorola PCS                      | 1         | 0.11%   |
| Motorola BCS                      | 1         | 0.11%   |
| Linksys                           | 1         | 0.11%   |
| Lenovo                            | 1         | 0.11%   |
| ICS Advent                        | 1         | 0.11%   |
| Exar                              | 1         | 0.11%   |
| Edimax Technology                 | 1         | 0.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 170       | 15.68%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 70        | 6.46%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 37        | 3.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 30        | 2.77%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 23        | 2.12%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 21        | 1.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 20        | 1.85%   |
| Intel Wireless 7260                                                     | 19        | 1.75%   |
| Broadcom BCM43142 802.11b/g/n                                           | 19        | 1.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 18        | 1.66%   |
| Intel Wireless 8260                                                     | 18        | 1.66%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 17        | 1.57%   |
| Intel Wireless 8265 / 8275                                              | 17        | 1.57%   |
| Intel Wireless 7265                                                     | 16        | 1.48%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 13        | 1.2%    |
| Intel Wireless 3165                                                     | 13        | 1.2%    |
| Intel Wi-Fi 6 AX201                                                     | 13        | 1.2%    |
| Intel Wi-Fi 6 AX200                                                     | 13        | 1.2%    |
| Intel Ethernet Connection I219-LM                                       | 12        | 1.11%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 11        | 1.01%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 11        | 1.01%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 11        | 1.01%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 10        | 0.92%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 10        | 0.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 9         | 0.83%   |
| Intel WiFi Link 5100                                                    | 9         | 0.83%   |
| Intel Centrino Ultimate-N 6300                                          | 9         | 0.83%   |
| Intel 82577LM Gigabit Network Connection                                | 9         | 0.83%   |
| ASIX AX88179 Gigabit Ethernet                                           | 9         | 0.83%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 8         | 0.74%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 8         | 0.74%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 8         | 0.74%   |
| Intel Centrino Advanced-N 6200                                          | 8         | 0.74%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 8         | 0.74%   |
| Intel Ethernet Connection I218-LM                                       | 7         | 0.65%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 7         | 0.65%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 6         | 0.55%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 6         | 0.55%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 6         | 0.55%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 6         | 0.55%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 0.55%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 6         | 0.55%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 6         | 0.55%   |
| Intel Centrino Advanced-N 6235                                          | 6         | 0.55%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 5         | 0.46%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 5         | 0.46%   |
| Intel Centrino Wireless-N 2230                                          | 5         | 0.46%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 4         | 0.37%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 4         | 0.37%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 4         | 0.37%   |
| Realtek 802.11ac NIC                                                    | 4         | 0.37%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 4         | 0.37%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 4         | 0.37%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 4         | 0.37%   |
| Intel Wireless 3160                                                     | 4         | 0.37%   |
| Intel Ethernet Connection I217-LM                                       | 4         | 0.37%   |
| Intel Ethernet Connection (4) I219-V                                    | 4         | 0.37%   |
| Intel Ethernet Connection (4) I219-LM                                   | 4         | 0.37%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 0.37%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 4         | 0.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 246       | 42.71%  |
| Qualcomm Atheros                | 130       | 22.57%  |
| Realtek Semiconductor           | 93        | 16.15%  |
| Broadcom                        | 56        | 9.72%   |
| Broadcom Limited                | 16        | 2.78%   |
| Ralink                          | 9         | 1.56%   |
| Ralink Technology               | 6         | 1.04%   |
| Dell                            | 5         | 0.87%   |
| TP-Link                         | 2         | 0.35%   |
| Sierra Wireless                 | 2         | 0.35%   |
| MEDIATEK                        | 2         | 0.35%   |
| D-Link System                   | 2         | 0.35%   |
| ZyXEL Communications            | 1         | 0.17%   |
| Qualcomm Atheros Communications | 1         | 0.17%   |
| Qualcomm                        | 1         | 0.17%   |
| NetGear                         | 1         | 0.17%   |
| Linksys                         | 1         | 0.17%   |
| Hewlett-Packard                 | 1         | 0.17%   |
| Edimax Technology               | 1         | 0.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 37        | 6.37%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 23        | 3.96%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 21        | 3.61%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 20        | 3.44%   |
| Intel Wireless 7260                                                     | 19        | 3.27%   |
| Broadcom BCM43142 802.11b/g/n                                           | 19        | 3.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 18        | 3.1%    |
| Intel Wireless 8260                                                     | 18        | 3.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 17        | 2.93%   |
| Intel Wireless 8265 / 8275                                              | 17        | 2.93%   |
| Intel Wireless 7265                                                     | 16        | 2.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 13        | 2.24%   |
| Intel Wireless 3165                                                     | 13        | 2.24%   |
| Intel Wi-Fi 6 AX201                                                     | 13        | 2.24%   |
| Intel Wi-Fi 6 AX200                                                     | 13        | 2.24%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 11        | 1.89%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 10        | 1.72%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 10        | 1.72%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 9         | 1.55%   |
| Intel WiFi Link 5100                                                    | 9         | 1.55%   |
| Intel Centrino Ultimate-N 6300                                          | 9         | 1.55%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 8         | 1.38%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 8         | 1.38%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 8         | 1.38%   |
| Intel Centrino Advanced-N 6200                                          | 8         | 1.38%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 7         | 1.2%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 6         | 1.03%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 6         | 1.03%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 6         | 1.03%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 1.03%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 6         | 1.03%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 6         | 1.03%   |
| Intel Centrino Advanced-N 6235                                          | 6         | 1.03%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 5         | 0.86%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 5         | 0.86%   |
| Intel Centrino Wireless-N 2230                                          | 5         | 0.86%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 4         | 0.69%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 4         | 0.69%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 4         | 0.69%   |
| Realtek 802.11ac NIC                                                    | 4         | 0.69%   |
| Intel Wireless 3160                                                     | 4         | 0.69%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 0.69%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 4         | 0.69%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 4         | 0.69%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 4         | 0.69%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 4         | 0.69%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 3         | 0.52%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 3         | 0.52%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 3         | 0.52%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 3         | 0.52%   |
| Intel Ultimate N WiFi Link 5300                                         | 3         | 0.52%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 0.52%   |
| Dell Hub of E-Port Replicator                                           | 3         | 0.52%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter              | 3         | 0.52%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter             | 3         | 0.52%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 3         | 0.52%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 3         | 0.52%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 3         | 0.52%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 3         | 0.52%   |
| Realtek RTL8723AU 802.11n WLAN Adapter                                  | 2         | 0.34%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 257       | 52.66%  |
| Intel                            | 100       | 20.49%  |
| Qualcomm Atheros                 | 40        | 8.2%    |
| Broadcom                         | 26        | 5.33%   |
| Marvell Technology Group         | 10        | 2.05%   |
| Broadcom Limited                 | 10        | 2.05%   |
| ASIX Electronics                 | 9         | 1.84%   |
| Xiaomi                           | 7         | 1.43%   |
| DisplayLink                      | 5         | 1.02%   |
| Samsung Electronics              | 3         | 0.61%   |
| JMicron Technology               | 3         | 0.61%   |
| Huawei Technologies              | 3         | 0.61%   |
| TP-Link                          | 2         | 0.41%   |
| Nvidia                           | 2         | 0.41%   |
| Silicon Integrated Systems [SiS] | 1         | 0.2%    |
| Qualcomm                         | 1         | 0.2%    |
| OPPO Electronics                 | 1         | 0.2%    |
| OnePlus Technology (Shenzhen)    | 1         | 0.2%    |
| Novatel Wireless                 | 1         | 0.2%    |
| Motorola PCS                     | 1         | 0.2%    |
| Motorola BCS                     | 1         | 0.2%    |
| MediaTek                         | 1         | 0.2%    |
| Lenovo                           | 1         | 0.2%    |
| ICS Advent                       | 1         | 0.2%    |
| Hewlett-Packard                  | 1         | 0.2%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 170       | 34.62%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 70        | 14.26%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 30        | 6.11%   |
| Intel Ethernet Connection I219-LM                                 | 12        | 2.44%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 11        | 2.24%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 11        | 2.24%   |
| Intel 82577LM Gigabit Network Connection                          | 9         | 1.83%   |
| ASIX AX88179 Gigabit Ethernet                                     | 9         | 1.83%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 8         | 1.63%   |
| Intel Ethernet Connection I218-LM                                 | 7         | 1.43%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 6         | 1.22%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 4         | 0.81%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 4         | 0.81%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 4         | 0.81%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 0.81%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 0.81%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 0.81%   |
| Intel 82566MM Gigabit Network Connection                          | 4         | 0.81%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 0.81%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 0.61%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 0.61%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 3         | 0.61%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 0.61%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 3         | 0.61%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 0.61%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 3         | 0.61%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 3         | 0.61%   |
| Intel Ethernet Connection I219-V                                  | 3         | 0.61%   |
| Intel 82577LC Gigabit Network Connection                          | 3         | 0.61%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 0.61%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3         | 0.61%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 2         | 0.41%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.41%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.41%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.41%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.41%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 2         | 0.41%   |
| Intel Ethernet controller                                         | 2         | 0.41%   |
| Intel Ethernet Connection I218-V                                  | 2         | 0.41%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.41%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.41%   |
| Huawei E353/E3131                                                 | 2         | 0.41%   |
| DisplayLink USB3.0 5K Graphic Docking                             | 2         | 0.41%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                 | 2         | 0.41%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2         | 0.41%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 2         | 0.41%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 2         | 0.41%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 2         | 0.41%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.2%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.2%    |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.2%    |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.2%    |
| Qualcomm SDM636-QRD _SN:494F4540                                  | 1         | 0.2%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.2%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.2%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.2%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.2%    |
| OPPO RMX3381                                                      | 1         | 0.2%    |
| OnePlus (Shenzhen) EB2103                                         | 1         | 0.2%    |
| Novatel Wireless MiFi 7730L                                       | 1         | 0.2%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 548       | 53.41%  |
| Ethernet | 466       | 45.42%  |
| Modem    | 10        | 0.97%   |
| Unknown  | 2         | 0.19%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 525       | 55.67%  |
| Ethernet | 416       | 44.11%  |
| Modem    | 1         | 0.11%   |
| Unknown  | 1         | 0.11%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 426       | 75.27%  |
| 1     | 117       | 20.67%  |
| 0     | 19        | 3.36%   |
| 3     | 4         | 0.71%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 404       | 70.88%  |
| Yes  | 166       | 29.12%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 174       | 40.47%  |
| Qualcomm Atheros Communications | 50        | 11.63%  |
| Realtek Semiconductor           | 47        | 10.93%  |
| Broadcom                        | 29        | 6.74%   |
| Lite-On Technology              | 22        | 5.12%   |
| Foxconn / Hon Hai               | 21        | 4.88%   |
| IMC Networks                    | 20        | 4.65%   |
| Apple                           | 13        | 3.02%   |
| Dell                            | 12        | 2.79%   |
| Toshiba                         | 8         | 1.86%   |
| Hewlett-Packard                 | 7         | 1.63%   |
| Ralink                          | 6         | 1.4%    |
| Cambridge Silicon Radio         | 6         | 1.4%    |
| Foxconn International           | 4         | 0.93%   |
| ASUSTek Computer                | 3         | 0.7%    |
| Realtek                         | 2         | 0.47%   |
| Integrated System Solution      | 2         | 0.47%   |
| Alps Electric                   | 2         | 0.47%   |
| MediaTek                        | 1         | 0.23%   |
| Askey Computer                  | 1         | 0.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                                                              | 94        | 21.86%  |
| Intel Bluetooth wireless interface                                                  | 32        | 7.44%   |
| Realtek Bluetooth Radio                                                             | 28        | 6.51%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 26        | 6.05%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 24        | 5.58%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 12        | 2.79%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 12        | 2.79%   |
| IMC Networks Bluetooth Device                                                       | 9         | 2.09%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 8         | 1.86%   |
| Apple Bluetooth Host Controller                                                     | 8         | 1.86%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 7         | 1.63%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 7         | 1.63%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 7         | 1.63%   |
| IMC Networks Bluetooth Radio                                                        | 7         | 1.63%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 7         | 1.63%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 7         | 1.63%   |
| Ralink RT3290 Bluetooth                                                             | 6         | 1.4%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 6         | 1.4%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 6         | 1.4%    |
| Broadcom BCM2045B (BDC-2.1)                                                         | 6         | 1.4%    |
| HP Broadcom 2070 Bluetooth Combo                                                    | 5         | 1.16%   |
| Dell DW375 Bluetooth Module                                                         | 5         | 1.16%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 5         | 1.16%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 4         | 0.93%   |
| Lite-On Bluetooth Device                                                            | 4         | 0.93%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 4         | 0.93%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 4         | 0.93%   |
| Realtek RTL8723B Bluetooth                                                          | 3         | 0.7%    |
| Intel AX210 Bluetooth                                                               | 3         | 0.7%    |
| Foxconn / Hon Hai BCM43142A0                                                        | 3         | 0.7%    |
| Foxconn / Hon Hai BCM20702A0                                                        | 3         | 0.7%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 3         | 0.7%    |
| Apple Bluetooth HCI                                                                 | 3         | 0.7%    |
| Toshiba Integrated Bluetooth HCI                                                    | 2         | 0.47%   |
| Toshiba BCM43142A0                                                                  | 2         | 0.47%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 2         | 0.47%   |
| Realtek Bluetooth Radio                                                             | 2         | 0.47%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 0.47%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                               | 2         | 0.47%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 2         | 0.47%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 0.47%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 2         | 0.47%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 2         | 0.47%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 2         | 0.47%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 2         | 0.47%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 2         | 0.47%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.23%   |
| Toshiba BRCM Bluetooth Controller BCM2070                                           | 1         | 0.23%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.23%   |
| Toshiba Askey for                                                                   | 1         | 0.23%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.23%   |
| Realtek CSR BS8510                                                                  | 1         | 0.23%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.23%   |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 1         | 0.23%   |
| MediaTek MT7630e Bluetooth Adapter                                                  | 1         | 0.23%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.23%   |
| Lite-On Bluetooth Radio                                                             | 1         | 0.23%   |
| Lite-On BCM43142A0                                                                  | 1         | 0.23%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 0.23%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.23%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 457       | 69.56%  |
| AMD                                  | 107       | 16.29%  |
| Nvidia                               | 77        | 11.72%  |
| SteelSeries ApS                      | 2         | 0.3%    |
| Realtek Semiconductor                | 2         | 0.3%    |
| Thesycon Systemsoftware & Consulting | 1         | 0.15%   |
| Tenx Technology                      | 1         | 0.15%   |
| Silicon Integrated Systems [SiS]     | 1         | 0.15%   |
| Sennheiser Communications            | 1         | 0.15%   |
| Razer USA                            | 1         | 0.15%   |
| Lenovo                               | 1         | 0.15%   |
| GN Netcom                            | 1         | 0.15%   |
| Generalplus Technology               | 1         | 0.15%   |
| Focusrite-Novation                   | 1         | 0.15%   |
| Creative Technology                  | 1         | 0.15%   |
| Corsair                              | 1         | 0.15%   |
| C-Media Electronics                  | 1         | 0.15%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 71        | 8.91%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 64        | 8.03%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 45        | 5.65%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 39        | 4.89%   |
| Intel 8 Series HD Audio Controller                                                                | 36        | 4.52%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 36        | 4.52%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 33        | 4.14%   |
| AMD FCH Azalia Controller                                                                         | 29        | 3.64%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 21        | 2.63%   |
| AMD Kabini HDMI/DP Audio                                                                          | 21        | 2.63%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 17        | 2.13%   |
| Intel Broadwell-U Audio Controller                                                                | 17        | 2.13%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 17        | 2.13%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 17        | 2.13%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 17        | 2.13%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 16        | 2.01%   |
| Intel Cannon Lake PCH cAVS                                                                        | 14        | 1.76%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 14        | 1.76%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 13        | 1.63%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 12        | 1.51%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 12        | 1.51%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 11        | 1.38%   |
| Intel CM238 HD Audio Controller                                                                   | 11        | 1.38%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 11        | 1.38%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 11        | 1.38%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 10        | 1.25%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 9         | 1.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 9         | 1.13%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 9         | 1.13%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 9         | 1.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 9         | 1.13%   |
| Intel Comet Lake PCH cAVS                                                                         | 8         | 1%      |
| AMD High Definition Audio Controller                                                              | 7         | 0.88%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 6         | 0.75%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 5         | 0.63%   |
| Nvidia High Definition Audio Controller                                                           | 5         | 0.63%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 0.63%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 0.63%   |
| AMD Wrestler HDMI Audio                                                                           | 5         | 0.63%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 4         | 0.5%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 0.5%    |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 0.38%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 3         | 0.38%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 3         | 0.38%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 0.38%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 0.38%   |
| Nvidia Audio device                                                                               | 3         | 0.38%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 0.38%   |
| AMD Trinity HDMI Audio Controller                                                                 | 3         | 0.38%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                                            | 3         | 0.38%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 3         | 0.38%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 3         | 0.38%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 3         | 0.38%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.25%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 2         | 0.25%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 2         | 0.25%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 2         | 0.25%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 0.25%   |
| AMD RV630 HDMI Audio [Radeon HD 2600 PRO/XT / HD 3610]                                            | 2         | 0.25%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                                              | 2         | 0.25%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 31        | 26.27%  |
| Samsung Electronics | 29        | 24.58%  |
| Micron Technology   | 18        | 15.25%  |
| Unknown             | 8         | 6.78%   |
| Kingston            | 7         | 5.93%   |
| A-DATA Technology   | 5         | 4.24%   |
| Unknown (ABCD)      | 4         | 3.39%   |
| Nanya Technology    | 3         | 2.54%   |
| Ramaxel Technology  | 2         | 1.69%   |
| Crucial             | 2         | 1.69%   |
| TIMETEC             | 1         | 0.85%   |
| Teikon              | 1         | 0.85%   |
| Team                | 1         | 0.85%   |
| Strontium           | 1         | 0.85%   |
| Puskill             | 1         | 0.85%   |
| Patriot             | 1         | 0.85%   |
| ELPIDA              | 1         | 0.85%   |
| AXIOM               | 1         | 0.85%   |
| Avant               | 1         | 0.85%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 4         | 3.23%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 3.23%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR3 2400MT/s | 3         | 2.42%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 3         | 2.42%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 3         | 2.42%   |
| Kingston RAM ACR16D3LS1KFG/4G 4096MB SODIMM DDR3 1600MT/s        | 3         | 2.42%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 2         | 1.61%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 2         | 1.61%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 2         | 1.61%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 2         | 1.61%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 1.61%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.61%   |
| Samsung RAM M471A5244BB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 2         | 1.61%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 2         | 1.61%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 2         | 1.61%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 2         | 1.61%   |
| A-DATA RAM AE4S240038G17-BHYA 8192MB SODIMM DDR4 2400MT/s        | 2         | 1.61%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                      | 1         | 0.81%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2667MT/s                   | 1         | 0.81%   |
| Unknown RAM Module 4096MB Chip DDR4 2133MT/s                     | 1         | 0.81%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.81%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 1         | 0.81%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM LPDDR4 2400MT/s   | 1         | 0.81%   |
| TIMETEC RAM SD3-1600 8GB SODIMM DDR3 1600MT/s                    | 1         | 0.81%   |
| Teikon RAM TMT351S6EFR8A-PBHJ 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.81%   |
| Team RAM TEAMGROUP-SD4-2400 8GB SODIMM DDR4 2667MT/s             | 1         | 0.81%   |
| Strontium RAM SRT4G86S1-P9H 4GB SODIMM DDR3 1600MT/s             | 1         | 0.81%   |
| SK Hynix RAM Module 4096MB SODIMM LPDDR3 1867MT/s                | 1         | 0.81%   |
| SK Hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.81%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.81%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.81%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.81%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.81%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.81%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2048MB SODIMM DDR3 1334MT/s        | 1         | 0.81%   |
| SK Hynix RAM HMT112S6BFR6C-G7 1024MB SODIMM DDR3 1067MT/s        | 1         | 0.81%   |
| SK Hynix RAM HMP351S6AFR8C-S6 4096MB SODIMM DDR2 800MT/s         | 1         | 0.81%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.81%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s        | 1         | 0.81%   |
| SK Hynix RAM HMA82GS6JJR8N-VK 16384MB SODIMM DDR4 2667MT/s       | 1         | 0.81%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.81%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 1         | 0.81%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.81%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s        | 1         | 0.81%   |
| SK Hynix RAM HCNNNCPMBLHR-NEE 2GB Row Of Chips LPDDR4 4267MT/s   | 1         | 0.81%   |
| Samsung RAM UBE3D4AA-MGCR 8GB Row Of Chips LPDDR4 4267MT/s       | 1         | 0.81%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                   | 1         | 0.81%   |
| Samsung RAM Module 4096MB SODIMM LPDDR3 1600MT/s                 | 1         | 0.81%   |
| Samsung RAM M471B5773EB0-CK0 2048MB SODIMM DDR3 1600MT/s         | 1         | 0.81%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 1         | 0.81%   |
| Samsung RAM M471B5674BM0-CK0 2GB SODIMM DDR3 1600MT/s            | 1         | 0.81%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 4199MT/s            | 1         | 0.81%   |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s         | 1         | 0.81%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.81%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.81%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.81%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s            | 1         | 0.81%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 0.81%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 0.81%   |
| Samsung RAM M471A5143EB0-CPB 4096MB SODIMM DDR4 2133MT/s         | 1         | 0.81%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 46        | 45.54%  |
| DDR3   | 35        | 34.65%  |
| LPDDR4 | 8         | 7.92%   |
| LPDDR3 | 6         | 5.94%   |
| SDRAM  | 3         | 2.97%   |
| DDR2   | 3         | 2.97%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 89        | 89%     |
| Row Of Chips | 9         | 9%      |
| DIMM         | 1         | 1%      |
| Chip         | 1         | 1%      |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 51        | 44.35%  |
| 8192  | 38        | 33.04%  |
| 16384 | 12        | 10.43%  |
| 2048  | 12        | 10.43%  |
| 1024  | 2         | 1.74%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 26        | 23.85%  |
| 2667    | 25        | 22.94%  |
| 3200    | 13        | 11.93%  |
| 2400    | 10        | 9.17%   |
| 1334    | 6         | 5.5%    |
| 2133    | 5         | 4.59%   |
| 3266    | 4         | 3.67%   |
| Unknown | 4         | 3.67%   |
| 4267    | 3         | 2.75%   |
| 1333    | 3         | 2.75%   |
| 800     | 3         | 2.75%   |
| 4199    | 2         | 1.83%   |
| 1867    | 2         | 1.83%   |
| 2048    | 1         | 0.92%   |
| 1067    | 1         | 0.92%   |
| 667     | 1         | 0.92%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 3         | 50%     |
| Canon           | 2         | 33.33%  |
| Seiko Epson     | 1         | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                     | Notebooks | Percent |
|---------------------------|-----------|---------|
| Seiko Epson L3110 Series  | 1         | 16.67%  |
| HP LaserJet 1200          | 1         | 16.67%  |
| HP ENVY Photo 6200 series | 1         | 16.67%  |
| HP DeskJet 1110 series    | 1         | 16.67%  |
| Canon TS3100 series       | 1         | 16.67%  |
| Canon PIXMA MG3000 series | 1         | 16.67%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 50%     |
| Canon       | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X750 [Perfection 4490 Photo] | 1         | 50%     |
| Canon CanoScan LiDE 90                      | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 127       | 25.97%  |
| Realtek Semiconductor                  | 58        | 11.86%  |
| IMC Networks                           | 52        | 10.63%  |
| Microdia                               | 37        | 7.57%   |
| Sunplus Innovation Technology          | 26        | 5.32%   |
| Cheng Uei Precision Industry (Foxlink) | 26        | 5.32%   |
| Acer                                   | 26        | 5.32%   |
| Suyin                                  | 20        | 4.09%   |
| Quanta                                 | 20        | 4.09%   |
| Syntek                                 | 18        | 3.68%   |
| Apple                                  | 10        | 2.04%   |
| Ricoh                                  | 9         | 1.84%   |
| Alcor Micro                            | 9         | 1.84%   |
| Lite-On Technology                     | 8         | 1.64%   |
| Silicon Motion                         | 7         | 1.43%   |
| Luxvisions Innotech Limited            | 5         | 1.02%   |
| Samsung Electronics                    | 4         | 0.82%   |
| Z-Star Microelectronics                | 2         | 0.41%   |
| Sunplus Technology                     | 2         | 0.41%   |
| Primax Electronics                     | 2         | 0.41%   |
| Logitech                               | 2         | 0.41%   |
| ALi                                    | 2         | 0.41%   |
| YGTek                                  | 1         | 0.2%    |
| Y Media                                | 1         | 0.2%    |
| USB2.0 Webcamera                       | 1         | 0.2%    |
| Pixart Imaging                         | 1         | 0.2%    |
| Panasonic (Matsushita)                 | 1         | 0.2%    |
| OmniVision Technologies                | 1         | 0.2%    |
| Microsoft                              | 1         | 0.2%    |
| LG Electronics                         | 1         | 0.2%    |
| Lenovo                                 | 1         | 0.2%    |
| KYE Systems (Mouse Systems)            | 1         | 0.2%    |
| Importek                               | 1         | 0.2%    |
| Huawei Technologies                    | 1         | 0.2%    |
| Genesys Logic                          | 1         | 0.2%    |
| Generalplus Technology                 | 1         | 0.2%    |
| GEMBIRD                                | 1         | 0.2%    |
| DigiTech                               | 1         | 0.2%    |
| Denron                                 | 1         | 0.2%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony HD WebCam                                              | 16        | 3.27%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 15        | 3.06%   |
| Microdia Integrated_Webcam_HD                                  | 14        | 2.86%   |
| Realtek Integrated_Webcam_HD                                   | 12        | 2.45%   |
| Realtek USB Camera                                             | 11        | 2.24%   |
| Chicony Integrated Camera                                      | 10        | 2.04%   |
| Microdia Integrated Webcam                                     | 9         | 1.84%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 9         | 1.84%   |
| Acer Integrated Camera                                         | 9         | 1.84%   |
| Syntek Integrated Camera                                       | 8         | 1.63%   |
| IMC Networks Integrated Camera                                 | 8         | 1.63%   |
| Chicony TOSHIBA Web Camera - HD                                | 8         | 1.63%   |
| Chicony HP Truevision HD                                       | 7         | 1.43%   |
| Realtek Integrated Webcam                                      | 6         | 1.22%   |
| Quanta VGA WebCam                                              | 6         | 1.22%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 6         | 1.22%   |
| Syntek Lenovo EasyCamera                                       | 5         | 1.02%   |
| Sunplus Integrated_Webcam_HD                                   | 5         | 1.02%   |
| Sunplus HD WebCam                                              | 5         | 1.02%   |
| Quanta HD User Facing                                          | 5         | 1.02%   |
| Chicony VGA Webcam                                             | 5         | 1.02%   |
| Chicony USB 2.0 Camera                                         | 5         | 1.02%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 5         | 1.02%   |
| Suyin HP TrueVision HD                                         | 4         | 0.82%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                       | 4         | 0.82%   |
| Samsung Galaxy A5 (MTP)                                        | 4         | 0.82%   |
| Realtek Lenovo EasyCamera                                      | 4         | 0.82%   |
| Realtek Integrated Webcam HD                                   | 4         | 0.82%   |
| Microdia Webcam Vitade AF                                      | 4         | 0.82%   |
| Chicony Lenovo Integrated Camera (0.3MP)                       | 4         | 0.82%   |
| Chicony Lenovo EasyCamera                                      | 4         | 0.82%   |
| Chicony HP Webcam                                              | 4         | 0.82%   |
| Chicony HP Truevision HD camera                                | 4         | 0.82%   |
| Apple FaceTime HD Camera                                       | 4         | 0.82%   |
| Alcor Micro USB 2.0 Web Camera                                 | 4         | 0.82%   |
| Alcor Micro Asus Integrated Webcam                             | 4         | 0.82%   |
| Acer Lenovo EasyCamera                                         | 4         | 0.82%   |
| Suyin Laptop_Integrated_Webcam_HD                              | 3         | 0.61%   |
| Ricoh USB2.0 Camera                                            | 3         | 0.61%   |
| Ricoh Laptop_Integrated_Webcam_FHD                             | 3         | 0.61%   |
| Realtek HP Truevision HD integrated webcam                     | 3         | 0.61%   |
| Quanta HP Wide Vision HD Camera                                | 3         | 0.61%   |
| Quanta HP TrueVision HD Camera                                 | 3         | 0.61%   |
| Lite-On HP HD Camera                                           | 3         | 0.61%   |
| IMC Networks USB Camera                                        | 3         | 0.61%   |
| Chicony USB2.0 HD UVC WebCam                                   | 3         | 0.61%   |
| Chicony USB2.0 Camera                                          | 3         | 0.61%   |
| Chicony HP HD Webcam [Fixed]                                   | 3         | 0.61%   |
| Chicony HP HD Camera                                           | 3         | 0.61%   |
| Chicony HD User Facing                                         | 3         | 0.61%   |
| Chicony EasyCamera                                             | 3         | 0.61%   |
| Chicony CNFA078                                                | 3         | 0.61%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                  | 3         | 0.61%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 3         | 0.61%   |
| Apple iPhone 5/5C/5S/6/SE                                      | 3         | 0.61%   |
| Acer Lenovo Integrated Webcam                                  | 3         | 0.61%   |
| Acer HD Webcam                                                 | 3         | 0.61%   |
| Syntek EasyCamera                                              | 2         | 0.41%   |
| Suyin Acer/Lenovo Webcam [CN0316]                              | 2         | 0.41%   |
| Sunplus Asus Webcam                                            | 2         | 0.41%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 42        | 48.84%  |
| Upek                       | 11        | 12.79%  |
| Shenzhen Goodix Technology | 11        | 12.79%  |
| AuthenTec                  | 9         | 10.47%  |
| Synaptics                  | 5         | 5.81%   |
| LighTuning Technology      | 4         | 4.65%   |
| STMicroelectronics         | 3         | 3.49%   |
| Focal-systems.Corp         | 1         | 1.16%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 10        | 11.63%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 9         | 10.47%  |
| Shenzhen Goodix  FingerPrint Device                                        | 6         | 6.98%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 5.81%   |
| Validity Sensors VFS491                                                    | 4         | 4.65%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 4.65%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 3.49%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 3.49%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 3.49%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 3.49%   |
| STMicroelectronics Fingerprint Reader                                      | 3         | 3.49%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 3.49%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 3.49%   |
| Unknown                                                                    | 3         | 3.49%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 2.33%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 2.33%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 2.33%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 2.33%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 2.33%   |
| AuthenTec AES2810                                                          | 2         | 2.33%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 2.33%   |
| AuthenTec AES1600                                                          | 2         | 2.33%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 1.16%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.16%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 1.16%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 1.16%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 1.16%   |
| LighTuning Fingerprint Reader                                              | 1         | 1.16%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 1.16%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 1.16%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 28        | 58.33%  |
| Alcor Micro                       | 7         | 14.58%  |
| O2 Micro                          | 4         | 8.33%   |
| Yubico.com                        | 2         | 4.17%   |
| Upek                              | 2         | 4.17%   |
| Lenovo                            | 2         | 4.17%   |
| VASCO Data Security International | 1         | 2.08%   |
| SCM Microsystems                  | 1         | 2.08%   |
| OmniKey                           | 1         | 2.08%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 10        | 20.83%  |
| Broadcom BCM5880 Secure Applications Processor                               | 9         | 18.75%  |
| Broadcom 5880                                                                | 8         | 16.67%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 7         | 14.58%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 8.33%   |
| Yubico.com Yubikey 4 U2F+CCID                                                | 2         | 4.17%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 4.17%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 4.17%   |
| VASCO Data Security International DIGIPASS 870                               | 1         | 2.08%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 2.08%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 2.08%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 2.08%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 378       | 65.97%  |
| 1     | 145       | 25.31%  |
| 2     | 46        | 8.03%   |
| 3     | 4         | 0.7%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 85        | 34.98%  |
| Chipcard                 | 41        | 16.87%  |
| Graphics card            | 39        | 16.05%  |
| Multimedia controller    | 26        | 10.7%   |
| Net/wireless             | 24        | 9.88%   |
| Storage                  | 11        | 4.53%   |
| Bluetooth                | 8         | 3.29%   |
| Flash memory             | 2         | 0.82%   |
| Storage/ide              | 1         | 0.41%   |
| Sound                    | 1         | 0.41%   |
| Network                  | 1         | 0.41%   |
| Net/ethernet             | 1         | 0.41%   |
| Dvb card                 | 1         | 0.41%   |
| Communication controller | 1         | 0.41%   |
| Camera                   | 1         | 0.41%   |

