Linux in Turkey - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Turkey.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Turkey/Desktop/README.md) and [notebooks](/Location/Turkey/Notebook/README.md).

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

Total: 4687

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [a6b7bccaea](https://linux-hardware.org/?probe=a6b7bccaea) | Jan 03, 2026 |
| Pegatron      | IPXSB-H61                   | Desktop     | [b74f15758f](https://linux-hardware.org/?probe=b74f15758f) | Jan 02, 2026 |
| Casper        | NIRVANA NB X600             | Notebook    | [daa2265e30](https://linux-hardware.org/?probe=daa2265e30) | Jan 02, 2026 |
| Casper        | NIRVANA NB X600             | Notebook    | [49ebf42228](https://linux-hardware.org/?probe=49ebf42228) | Jan 02, 2026 |
| Monster       | ABRA A5 V15.2               | Notebook    | [f8a69dc929](https://linux-hardware.org/?probe=f8a69dc929) | Jan 01, 2026 |
| Acer          | TravelMate P215-41-G2       | Notebook    | [359426ffd0](https://linux-hardware.org/?probe=359426ffd0) | Dec 31, 2025 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [c86fe255b1](https://linux-hardware.org/?probe=c86fe255b1) | Dec 30, 2025 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [7e060dcd5a](https://linux-hardware.org/?probe=7e060dcd5a) | Dec 30, 2025 |
| Gigabyte      | Z890 UD WIFI6E              | Desktop     | [aa428980b6](https://linux-hardware.org/?probe=aa428980b6) | Dec 29, 2025 |
| Gigabyte      | Z890 UD WIFI6E              | Desktop     | [cb52130f00](https://linux-hardware.org/?probe=cb52130f00) | Dec 29, 2025 |
| Casper        | W7x0S                       | Notebook    | [317a6fe3a1](https://linux-hardware.org/?probe=317a6fe3a1) | Dec 28, 2025 |
| Dell          | Latitude 3550               | Notebook    | [4b4d1cfb08](https://linux-hardware.org/?probe=4b4d1cfb08) | Dec 28, 2025 |
| HUAWEI        | MDF-XX                      | Notebook    | [d168addfd2](https://linux-hardware.org/?probe=d168addfd2) | Dec 28, 2025 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [bb43d15909](https://linux-hardware.org/?probe=bb43d15909) | Dec 28, 2025 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | Notebook    | [6564838a80](https://linux-hardware.org/?probe=6564838a80) | Dec 28, 2025 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | Notebook    | [2f55a24131](https://linux-hardware.org/?probe=2f55a24131) | Dec 28, 2025 |
| Lenovo        | LOQ 15IRX10 83JE            | Notebook    | [4f87fa6e25](https://linux-hardware.org/?probe=4f87fa6e25) | Dec 27, 2025 |
| ASUSTek       | ASUS EXPERTBOOK PM3406CK... | Notebook    | [71b5f3b05b](https://linux-hardware.org/?probe=71b5f3b05b) | Dec 26, 2025 |
| Lenovo        | Yoga Pro 7 14ASP10 83LX     | Notebook    | [b0fca89a45](https://linux-hardware.org/?probe=b0fca89a45) | Dec 26, 2025 |
| ASUSTek       | ASUS TUF Gaming A16 FA60... | Notebook    | [5a928c58ee](https://linux-hardware.org/?probe=5a928c58ee) | Dec 25, 2025 |
| ASUSTek       | A68HM-K                     | Desktop     | [2f468260eb](https://linux-hardware.org/?probe=2f468260eb) | Dec 25, 2025 |
| ASUSTek       | A68HM-K                     | Desktop     | [ba70f7cac4](https://linux-hardware.org/?probe=ba70f7cac4) | Dec 25, 2025 |
| HP            | 250 G4                      | Notebook    | [2ccbefe156](https://linux-hardware.org/?probe=2ccbefe156) | Dec 25, 2025 |
| Monster       | HUMA H4 V6.1                | Notebook    | [cb037977c7](https://linux-hardware.org/?probe=cb037977c7) | Dec 25, 2025 |
| Samsung       | 270E5G/270E5U               | Notebook    | [a4cd4e3d1a](https://linux-hardware.org/?probe=a4cd4e3d1a) | Dec 25, 2025 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [ac87958f10](https://linux-hardware.org/?probe=ac87958f10) | Dec 24, 2025 |
| ASUSTek       | H81M-K                      | Desktop     | [12d3387460](https://linux-hardware.org/?probe=12d3387460) | Dec 23, 2025 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [168ac048d3](https://linux-hardware.org/?probe=168ac048d3) | Dec 23, 2025 |
| Apple         | MacBookPro10,1              | Notebook    | [6d535dd1b0](https://linux-hardware.org/?probe=6d535dd1b0) | Dec 23, 2025 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [de326c5caf](https://linux-hardware.org/?probe=de326c5caf) | Dec 23, 2025 |
| Dell          | Latitude 7450               | Notebook    | [3fd0c9e8d3](https://linux-hardware.org/?probe=3fd0c9e8d3) | Dec 22, 2025 |
| Monster       | HUMA H4 V6.1                | Notebook    | [c90f16dfa8](https://linux-hardware.org/?probe=c90f16dfa8) | Dec 22, 2025 |
| Casper        | W7x0S                       | Notebook    | [2620e4e75d](https://linux-hardware.org/?probe=2620e4e75d) | Dec 21, 2025 |
| Monster       | HUMA H4 V6.1                | Notebook    | [a98517af0d](https://linux-hardware.org/?probe=a98517af0d) | Dec 21, 2025 |
| Monster       | HUMA H4 V6.1                | Notebook    | [a1c122c47d](https://linux-hardware.org/?probe=a1c122c47d) | Dec 21, 2025 |
| Lenovo        | LOQ 15IRX10 83JE            | Notebook    | [9b4fe801c6](https://linux-hardware.org/?probe=9b4fe801c6) | Dec 21, 2025 |
| MSI           | MPG X870E CARBON WIFI       | Desktop     | [c13534a1ba](https://linux-hardware.org/?probe=c13534a1ba) | Dec 21, 2025 |
| Dell          | Latitude 3550               | Notebook    | [2ecdf935a3](https://linux-hardware.org/?probe=2ecdf935a3) | Dec 20, 2025 |
| MSI           | Katana A17 AI B8VG          | Notebook    | [ef94950fbf](https://linux-hardware.org/?probe=ef94950fbf) | Dec 20, 2025 |
| HUAWEI        | BoDE-WXX9                   | Notebook    | [285b36fe1e](https://linux-hardware.org/?probe=285b36fe1e) | Dec 19, 2025 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [b8962f11a1](https://linux-hardware.org/?probe=b8962f11a1) | Dec 18, 2025 |
| HP            | ENVY 15                     | Notebook    | [9094712b4b](https://linux-hardware.org/?probe=9094712b4b) | Dec 18, 2025 |
| Unknown       | Unknown                     | Desktop     | [c3b4bd0aae](https://linux-hardware.org/?probe=c3b4bd0aae) | Dec 16, 2025 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [761d364cfa](https://linux-hardware.org/?probe=761d364cfa) | Dec 16, 2025 |
| HUAWEI        | BoDE-WXX9                   | Notebook    | [07a72eed95](https://linux-hardware.org/?probe=07a72eed95) | Dec 15, 2025 |
| Toshiba       | Satellite C855-2DG          | Notebook    | [87346741d9](https://linux-hardware.org/?probe=87346741d9) | Dec 15, 2025 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d3177a072d](https://linux-hardware.org/?probe=d3177a072d) | Dec 15, 2025 |
| WARP          | B760M4 V1.0                 | Desktop     | [63bf3c119d](https://linux-hardware.org/?probe=63bf3c119d) | Dec 14, 2025 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [ed2a3a7661](https://linux-hardware.org/?probe=ed2a3a7661) | Dec 14, 2025 |
| HP            | 250 G7 Notebook PC          | Notebook    | [e14569c913](https://linux-hardware.org/?probe=e14569c913) | Dec 14, 2025 |
| Toshiba       | Satellite C855-2DG          | Notebook    | [7444bc0e10](https://linux-hardware.org/?probe=7444bc0e10) | Dec 14, 2025 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [284b0c2ca7](https://linux-hardware.org/?probe=284b0c2ca7) | Dec 13, 2025 |
| ASUSTek       | ROG CROSSHAIR X870E APEX    | Desktop     | [35a247d46f](https://linux-hardware.org/?probe=35a247d46f) | Dec 13, 2025 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [def577103c](https://linux-hardware.org/?probe=def577103c) | Dec 13, 2025 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [6f10a7450a](https://linux-hardware.org/?probe=6f10a7450a) | Dec 13, 2025 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [43a6680793](https://linux-hardware.org/?probe=43a6680793) | Dec 12, 2025 |
| ASUSTek       | N56VZ                       | Notebook    | [34a4e6d6c7](https://linux-hardware.org/?probe=34a4e6d6c7) | Dec 12, 2025 |
| Lenovo        | G510 20238                  | Notebook    | [fcb2f0a6b9](https://linux-hardware.org/?probe=fcb2f0a6b9) | Dec 12, 2025 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [cc41f83b1d](https://linux-hardware.org/?probe=cc41f83b1d) | Dec 11, 2025 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [d5ee061b23](https://linux-hardware.org/?probe=d5ee061b23) | Dec 11, 2025 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | Notebook    | [0d70029e5b](https://linux-hardware.org/?probe=0d70029e5b) | Dec 11, 2025 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | Notebook    | [241dee0789](https://linux-hardware.org/?probe=241dee0789) | Dec 11, 2025 |
| Lenovo        | ThinkPad E595 20NF001PTX    | Notebook    | [35d1ab8e1c](https://linux-hardware.org/?probe=35d1ab8e1c) | Dec 10, 2025 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [bee1c3c934](https://linux-hardware.org/?probe=bee1c3c934) | Dec 09, 2025 |
| Acer          | Predator PH317-56           | Notebook    | [9c4725b2fd](https://linux-hardware.org/?probe=9c4725b2fd) | Dec 09, 2025 |
| HP            | 250 G3                      | Notebook    | [3e59baf9a9](https://linux-hardware.org/?probe=3e59baf9a9) | Dec 08, 2025 |
| Gigabyte      | B450M S2H V2                | Desktop     | [64f4291aae](https://linux-hardware.org/?probe=64f4291aae) | Dec 08, 2025 |
| Gigabyte      | B450M S2H V2                | Desktop     | [50f50152c7](https://linux-hardware.org/?probe=50f50152c7) | Dec 08, 2025 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [9568b1e3c9](https://linux-hardware.org/?probe=9568b1e3c9) | Dec 07, 2025 |
| AZW           | U59                         | Desktop     | [99f466d0b7](https://linux-hardware.org/?probe=99f466d0b7) | Dec 06, 2025 |
| AZW           | U59                         | Desktop     | [4ef9dea155](https://linux-hardware.org/?probe=4ef9dea155) | Dec 06, 2025 |
| Dell          | Inspiron N5110              | Notebook    | [23ba15400b](https://linux-hardware.org/?probe=23ba15400b) | Dec 06, 2025 |
| Unknown       | Orange Pi 5 Plus            | Soc         | [8943c22496](https://linux-hardware.org/?probe=8943c22496) | Dec 04, 2025 |
| Intel         | B75                         | Desktop     | [b20bad20e5](https://linux-hardware.org/?probe=b20bad20e5) | Dec 03, 2025 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [db073efbc3](https://linux-hardware.org/?probe=db073efbc3) | Dec 03, 2025 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [9891612ab5](https://linux-hardware.org/?probe=9891612ab5) | Dec 03, 2025 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [76b3d9a6bf](https://linux-hardware.org/?probe=76b3d9a6bf) | Dec 01, 2025 |
| ASUSTek       | ASUS Zenbook S 14 UX5406... | Notebook    | [926c6ce3d3](https://linux-hardware.org/?probe=926c6ce3d3) | Nov 30, 2025 |
| Gigabyte      | H61M-DS2                    | Desktop     | [1afca82b53](https://linux-hardware.org/?probe=1afca82b53) | Nov 30, 2025 |
| Lenovo        | ThinkPad T480 20L6S68A00    | Notebook    | [815e16d0f4](https://linux-hardware.org/?probe=815e16d0f4) | Nov 29, 2025 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [3fe3c09aae](https://linux-hardware.org/?probe=3fe3c09aae) | Nov 29, 2025 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [fad293215c](https://linux-hardware.org/?probe=fad293215c) | Nov 29, 2025 |
| Intel         | B75                         | Desktop     | [fd8b49791f](https://linux-hardware.org/?probe=fd8b49791f) | Nov 28, 2025 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | Notebook    | [58994b27fa](https://linux-hardware.org/?probe=58994b27fa) | Nov 28, 2025 |
| HP            | Elite x360 1040 14 inch ... | Convertible | [08f8a15e00](https://linux-hardware.org/?probe=08f8a15e00) | Nov 26, 2025 |
| MSI           | MPG X670E CARBON WIFI       | Desktop     | [34f45751b7](https://linux-hardware.org/?probe=34f45751b7) | Nov 26, 2025 |
| HP            | Elite x360 1040 14 inch ... | Convertible | [4537a18845](https://linux-hardware.org/?probe=4537a18845) | Nov 25, 2025 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [c8619158bc](https://linux-hardware.org/?probe=c8619158bc) | Nov 25, 2025 |
| HUAWEI        | MCLF-XX                     | Notebook    | [b537f11b88](https://linux-hardware.org/?probe=b537f11b88) | Nov 25, 2025 |
| Fujitsu Si... | ESPRIMO Mobile X9525        | Notebook    | [4b285ea085](https://linux-hardware.org/?probe=4b285ea085) | Nov 21, 2025 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [8505185098](https://linux-hardware.org/?probe=8505185098) | Nov 20, 2025 |
| Dell          | 0GY6Y8 A00                  | Desktop     | [db0c888acb](https://linux-hardware.org/?probe=db0c888acb) | Nov 18, 2025 |
| HP            | Pavilion 15                 | Notebook    | [b424018971](https://linux-hardware.org/?probe=b424018971) | Nov 16, 2025 |
| Casper        | EXCALIBUR G770              | Notebook    | [1028580712](https://linux-hardware.org/?probe=1028580712) | Nov 16, 2025 |
| HP            | Pavilion 15                 | Notebook    | [8a02861e2a](https://linux-hardware.org/?probe=8a02861e2a) | Nov 15, 2025 |
| Gigabyte      | M68MT-S2                    | Desktop     | [1fae0e73bc](https://linux-hardware.org/?probe=1fae0e73bc) | Nov 15, 2025 |
| Dell          | Precision 5570              | Notebook    | [55489cae0e](https://linux-hardware.org/?probe=55489cae0e) | Nov 15, 2025 |
| Lenovo        | 3743 SDK0J40688 WIN 3424... | Desktop     | [3ba50616f7](https://linux-hardware.org/?probe=3ba50616f7) | Nov 13, 2025 |
| ASUSTek       | ROG Maximus Z790 DARK HE... | Desktop     | [1b851a8c36](https://linux-hardware.org/?probe=1b851a8c36) | Nov 13, 2025 |
| MSI           | A520M-A PRO                 | Desktop     | [6b8105b72e](https://linux-hardware.org/?probe=6b8105b72e) | Nov 12, 2025 |
| LG Electro... | A520-P.AC7BT                | Notebook    | [b9bc2c8178](https://linux-hardware.org/?probe=b9bc2c8178) | Nov 12, 2025 |
| HP            | Notebook                    | Notebook    | [5a6b659895](https://linux-hardware.org/?probe=5a6b659895) | Nov 12, 2025 |
| MSI           | PRO X870-P WIFI             | Desktop     | [c13271aa49](https://linux-hardware.org/?probe=c13271aa49) | Nov 11, 2025 |
| HP            | Pavilion g6                 | Notebook    | [0281bfbf1c](https://linux-hardware.org/?probe=0281bfbf1c) | Nov 10, 2025 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [6e9a3fa78d](https://linux-hardware.org/?probe=6e9a3fa78d) | Nov 10, 2025 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [55d2d7d4b7](https://linux-hardware.org/?probe=55d2d7d4b7) | Nov 09, 2025 |
| Lenovo        | ThinkPad P50 20EN0037MD     | Notebook    | [28cb2e4b58](https://linux-hardware.org/?probe=28cb2e4b58) | Nov 09, 2025 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [00704df137](https://linux-hardware.org/?probe=00704df137) | Nov 09, 2025 |
| ASUSTek       | B450M-DRAGON                | Desktop     | [015dd4c7ea](https://linux-hardware.org/?probe=015dd4c7ea) | Nov 08, 2025 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [30224f4acb](https://linux-hardware.org/?probe=30224f4acb) | Nov 08, 2025 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [d0aa1759d4](https://linux-hardware.org/?probe=d0aa1759d4) | Nov 07, 2025 |
| ASUSTek       | TUF Gaming B650M-E          | Desktop     | [63a5cd4df6](https://linux-hardware.org/?probe=63a5cd4df6) | Nov 04, 2025 |
| Lenovo        | ThinkPad P15v Gen 1 20TR... | Notebook    | [11ab6815a0](https://linux-hardware.org/?probe=11ab6815a0) | Nov 04, 2025 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [a8a5786fef](https://linux-hardware.org/?probe=a8a5786fef) | Nov 04, 2025 |
| MSI           | B650 GAMING PLUS WIFI       | Desktop     | [6e33b16d50](https://linux-hardware.org/?probe=6e33b16d50) | Nov 03, 2025 |
| ASUSTek       | B450M-DRAGON                | Desktop     | [64cbbe42f6](https://linux-hardware.org/?probe=64cbbe42f6) | Nov 02, 2025 |
| Dell          | G15 5530                    | Notebook    | [4e6329ed18](https://linux-hardware.org/?probe=4e6329ed18) | Nov 01, 2025 |
| Dell          | G15 5530                    | Notebook    | [1d6f535394](https://linux-hardware.org/?probe=1d6f535394) | Nov 01, 2025 |
| VESTEL BIL... | VESTEL ONX                  | Notebook    | [85dc49cdd3](https://linux-hardware.org/?probe=85dc49cdd3) | Oct 30, 2025 |
| HP            | 8184 X4                     | Desktop     | [ba2825643f](https://linux-hardware.org/?probe=ba2825643f) | Oct 30, 2025 |
| Monster       | TULPAR T5 V19.1             | Notebook    | [a403518955](https://linux-hardware.org/?probe=a403518955) | Oct 30, 2025 |
| MSI           | Z170A GAMING M7             | Desktop     | [e714225729](https://linux-hardware.org/?probe=e714225729) | Oct 30, 2025 |
| Sony          | SVE14A2V2ES                 | Notebook    | [f1d3408cfc](https://linux-hardware.org/?probe=f1d3408cfc) | Oct 29, 2025 |
| HP            | Pavilion 15                 | Notebook    | [106435ba94](https://linux-hardware.org/?probe=106435ba94) | Oct 29, 2025 |
| Foxconn       | G31MXP FAB:1.1              | Desktop     | [5a51f7c824](https://linux-hardware.org/?probe=5a51f7c824) | Oct 28, 2025 |
| HP            | Pavilion 15                 | Notebook    | [7896c356a1](https://linux-hardware.org/?probe=7896c356a1) | Oct 27, 2025 |
| HUAWEI        | MCLG-XX                     | Notebook    | [c327bb66d8](https://linux-hardware.org/?probe=c327bb66d8) | Oct 27, 2025 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | Notebook    | [0525de2b6d](https://linux-hardware.org/?probe=0525de2b6d) | Oct 27, 2025 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [6fefcfe95a](https://linux-hardware.org/?probe=6fefcfe95a) | Oct 26, 2025 |
| MSI           | Vector 16 HX AI A2XWIG      | Notebook    | [a321264046](https://linux-hardware.org/?probe=a321264046) | Oct 25, 2025 |
| ASUSTek       | TUF Gaming X870-PLUS WIF... | Desktop     | [600e34ee6e](https://linux-hardware.org/?probe=600e34ee6e) | Oct 25, 2025 |
| MSI           | GE60 2OC\2OD\2OE            | Notebook    | [008a330907](https://linux-hardware.org/?probe=008a330907) | Oct 25, 2025 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [81e1973822](https://linux-hardware.org/?probe=81e1973822) | Oct 23, 2025 |
| Dell          | Vostro 3520                 | Notebook    | [e76365aff5](https://linux-hardware.org/?probe=e76365aff5) | Oct 22, 2025 |
| Monster       | TULPAR T5 V19.1             | Notebook    | [d8ad089bb7](https://linux-hardware.org/?probe=d8ad089bb7) | Oct 22, 2025 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [2de86de8ee](https://linux-hardware.org/?probe=2de86de8ee) | Oct 20, 2025 |
| Dell          | G3 3579                     | Notebook    | [1c432f4bf1](https://linux-hardware.org/?probe=1c432f4bf1) | Oct 20, 2025 |
| Acer          | Aspire E3-112               | Notebook    | [fe81c2c1bd](https://linux-hardware.org/?probe=fe81c2c1bd) | Oct 19, 2025 |
| MSI           | PRO B760-P WIFI DDR4        | Desktop     | [e5244bf2be](https://linux-hardware.org/?probe=e5244bf2be) | Oct 19, 2025 |
| Toshiba       | Satellite L850-1MV          | Notebook    | [f5218bcd80](https://linux-hardware.org/?probe=f5218bcd80) | Oct 18, 2025 |
| Intel         | NUC5i3RYB H41000-507        | Mini pc     | [b0bc345d93](https://linux-hardware.org/?probe=b0bc345d93) | Oct 17, 2025 |
| Sony          | VPCEH1S8E                   | Notebook    | [2d15fc0425](https://linux-hardware.org/?probe=2d15fc0425) | Oct 16, 2025 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [51037f46a9](https://linux-hardware.org/?probe=51037f46a9) | Oct 16, 2025 |
| Intel         | B75                         | Desktop     | [e95a1459f4](https://linux-hardware.org/?probe=e95a1459f4) | Oct 16, 2025 |
| Lenovo        | Yoga Pro 7 14ASP10 83LX     | Notebook    | [38abf2e41e](https://linux-hardware.org/?probe=38abf2e41e) | Oct 16, 2025 |
| Shenzhen M... | F8BAC                       | Mini pc     | [71f81ca2da](https://linux-hardware.org/?probe=71f81ca2da) | Oct 15, 2025 |
| Lenovo        | V15 G3 ABA 82TV             | Notebook    | [2c1ab01db5](https://linux-hardware.org/?probe=2c1ab01db5) | Oct 14, 2025 |
| HUAWEI        | CREFG-XX                    | Notebook    | [dd5c33568c](https://linux-hardware.org/?probe=dd5c33568c) | Oct 14, 2025 |
| Lenovo        | Yoga 7 14ARP8 82YM          | Convertible | [243a81a78c](https://linux-hardware.org/?probe=243a81a78c) | Oct 14, 2025 |
| Acer          | Nitro ANV16-41              | Notebook    | [8e5d993c1a](https://linux-hardware.org/?probe=8e5d993c1a) | Oct 14, 2025 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [16d3dda677](https://linux-hardware.org/?probe=16d3dda677) | Oct 13, 2025 |
| Sony          | VPCEA4S1E                   | Notebook    | [5d67640699](https://linux-hardware.org/?probe=5d67640699) | Oct 13, 2025 |
| HP            | ProBook 450 G5              | Notebook    | [41f59ca3b5](https://linux-hardware.org/?probe=41f59ca3b5) | Oct 13, 2025 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | Notebook    | [adfcf0d964](https://linux-hardware.org/?probe=adfcf0d964) | Oct 13, 2025 |
| Apple         | MacBookPro16,4              | Notebook    | [e4d9808330](https://linux-hardware.org/?probe=e4d9808330) | Oct 13, 2025 |
| HP            | ProBook 450 G5              | Notebook    | [fede03ea91](https://linux-hardware.org/?probe=fede03ea91) | Oct 13, 2025 |
| Dell          | 0V8WGR A00                  | Desktop     | [336e9e3c34](https://linux-hardware.org/?probe=336e9e3c34) | Oct 13, 2025 |
| ASUSTek       | K55VJ                       | Notebook    | [9b4715bc1c](https://linux-hardware.org/?probe=9b4715bc1c) | Oct 12, 2025 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [d1bfd27a79](https://linux-hardware.org/?probe=d1bfd27a79) | Oct 12, 2025 |
| HP            | Laptop 15-rb0xx             | Notebook    | [1807375132](https://linux-hardware.org/?probe=1807375132) | Oct 12, 2025 |
| Acer          | Nitro AN515-46              | Notebook    | [663733afcd](https://linux-hardware.org/?probe=663733afcd) | Oct 10, 2025 |
| Acer          | Nitro AN515-46              | Notebook    | [624b2c6637](https://linux-hardware.org/?probe=624b2c6637) | Oct 10, 2025 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | Notebook    | [40eda935f0](https://linux-hardware.org/?probe=40eda935f0) | Oct 09, 2025 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [9d12f5c210](https://linux-hardware.org/?probe=9d12f5c210) | Oct 09, 2025 |
| Lenovo        | IdeaPad Slim 3 15IRH10 8... | Notebook    | [3603f1f114](https://linux-hardware.org/?probe=3603f1f114) | Oct 08, 2025 |
| Intel         | H61                         | Desktop     | [e15cad6b4a](https://linux-hardware.org/?probe=e15cad6b4a) | Oct 04, 2025 |
| ASUSTek       | ProArt X870E-CREATOR WIF... | Desktop     | [8d2e865029](https://linux-hardware.org/?probe=8d2e865029) | Oct 04, 2025 |
| Intel         | H61                         | Desktop     | [3e3e1d5f74](https://linux-hardware.org/?probe=3e3e1d5f74) | Oct 04, 2025 |
| Dell          | Inspiron N5050              | Notebook    | [f51e031414](https://linux-hardware.org/?probe=f51e031414) | Oct 02, 2025 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [770374ac2c](https://linux-hardware.org/?probe=770374ac2c) | Oct 02, 2025 |
| ASUSTek       | Rampage IV FORMULA          | Desktop     | [e689d4b4e3](https://linux-hardware.org/?probe=e689d4b4e3) | Oct 02, 2025 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [aca5b3734f](https://linux-hardware.org/?probe=aca5b3734f) | Oct 01, 2025 |
| ASUSTek       | Z170-K                      | Desktop     | [9a00a78e8f](https://linux-hardware.org/?probe=9a00a78e8f) | Sep 29, 2025 |
| HUAWEI        | FLMH-XX                     | Notebook    | [9b29d1bcd7](https://linux-hardware.org/?probe=9b29d1bcd7) | Sep 27, 2025 |
| ASUSTek       | Z170-K                      | Desktop     | [06aca2d165](https://linux-hardware.org/?probe=06aca2d165) | Sep 27, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [cc6c12e680](https://linux-hardware.org/?probe=cc6c12e680) | Sep 27, 2025 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [a980b1c4a6](https://linux-hardware.org/?probe=a980b1c4a6) | Sep 27, 2025 |
| Acer          | Aspire AL14-51M             | Notebook    | [37f6827eab](https://linux-hardware.org/?probe=37f6827eab) | Sep 26, 2025 |
| Acer          | Acadia V1.45                | Notebook    | [cec9b79f6c](https://linux-hardware.org/?probe=cec9b79f6c) | Sep 26, 2025 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [b7cf02f3de](https://linux-hardware.org/?probe=b7cf02f3de) | Sep 25, 2025 |
| Lenovo        | V15 G4 AMN 82YU             | Notebook    | [6d7ef4bf2d](https://linux-hardware.org/?probe=6d7ef4bf2d) | Sep 24, 2025 |
| MSI           | PRO B650M-B                 | Desktop     | [f37bf4f660](https://linux-hardware.org/?probe=f37bf4f660) | Sep 24, 2025 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [77e0a49b4f](https://linux-hardware.org/?probe=77e0a49b4f) | Sep 24, 2025 |
| MSI           | Thin 15 B12UC               | Notebook    | [412e271e74](https://linux-hardware.org/?probe=412e271e74) | Sep 23, 2025 |
| ASUSTek       | ASUS Vivobook S 14 M5406... | Notebook    | [321d8fe11c](https://linux-hardware.org/?probe=321d8fe11c) | Sep 23, 2025 |
| HUAWEI        | MCLG-XX                     | Notebook    | [a9a25af9e0](https://linux-hardware.org/?probe=a9a25af9e0) | Sep 23, 2025 |
| Lenovo        | ThinkPad X9-14 Gen 1 21Q... | Notebook    | [767d5934b4](https://linux-hardware.org/?probe=767d5934b4) | Sep 22, 2025 |
| Lenovo        | ThinkPad X240 20AMS06D00    | Notebook    | [4d295c406d](https://linux-hardware.org/?probe=4d295c406d) | Sep 21, 2025 |
| Lenovo        | Y40-70 20347                | Notebook    | [baa83ee739](https://linux-hardware.org/?probe=baa83ee739) | Sep 20, 2025 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c7ac433443](https://linux-hardware.org/?probe=c7ac433443) | Sep 20, 2025 |
| ASUSTek       | ProArt X870E-CREATOR WIF... | Desktop     | [828a1545b5](https://linux-hardware.org/?probe=828a1545b5) | Sep 19, 2025 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [009e556b82](https://linux-hardware.org/?probe=009e556b82) | Sep 18, 2025 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [c916f49110](https://linux-hardware.org/?probe=c916f49110) | Sep 17, 2025 |
| MSI           | X570-A PRO                  | Desktop     | [bc8f9fc518](https://linux-hardware.org/?probe=bc8f9fc518) | Sep 16, 2025 |
| ASUSTek       | N56VZ                       | Notebook    | [1e12b4eed0](https://linux-hardware.org/?probe=1e12b4eed0) | Sep 15, 2025 |
| Huanan        | X99-F8 GAMING V5.0          | Desktop     | [7d9306ea2d](https://linux-hardware.org/?probe=7d9306ea2d) | Sep 15, 2025 |
| ASUSTek       | N53SV                       | Notebook    | [6d74ad5490](https://linux-hardware.org/?probe=6d74ad5490) | Sep 15, 2025 |
| ASUSTek       | N53SV                       | Notebook    | [c7fcaf20f3](https://linux-hardware.org/?probe=c7fcaf20f3) | Sep 15, 2025 |
| Lenovo        | Legion Pro 7 16IRX8H 82W... | Notebook    | [2fd78c9a78](https://linux-hardware.org/?probe=2fd78c9a78) | Sep 14, 2025 |
| HUAWEI        | BoDE-WXX9                   | Notebook    | [5558317979](https://linux-hardware.org/?probe=5558317979) | Sep 13, 2025 |
| Lenovo        | Legion Pro 7 16IRX8H 82W... | Notebook    | [8fe0a60c8a](https://linux-hardware.org/?probe=8fe0a60c8a) | Sep 13, 2025 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [d54882b7b8](https://linux-hardware.org/?probe=d54882b7b8) | Sep 12, 2025 |
| HP            | Laptop 15-ra0xx             | Notebook    | [dafc1db1d5](https://linux-hardware.org/?probe=dafc1db1d5) | Sep 11, 2025 |
| HP            | Laptop 15-ra0xx             | Notebook    | [f8c04c11f6](https://linux-hardware.org/?probe=f8c04c11f6) | Sep 11, 2025 |
| Acer          | Nitro AN515-52              | Notebook    | [48b16c7e7e](https://linux-hardware.org/?probe=48b16c7e7e) | Sep 10, 2025 |
| Dell          | Inspiron 14 7430 2-in-1     | Convertible | [b305d5d857](https://linux-hardware.org/?probe=b305d5d857) | Sep 10, 2025 |
| Unknown       | MT6785V/CC                  | Soc         | [eacdf7a5b3](https://linux-hardware.org/?probe=eacdf7a5b3) | Sep 09, 2025 |
| Valve         | Jupiter                     | Notebook    | [b1f2a0ec85](https://linux-hardware.org/?probe=b1f2a0ec85) | Sep 09, 2025 |
| HP            | Laptop 15-ra0xx             | Notebook    | [a7f6c2d584](https://linux-hardware.org/?probe=a7f6c2d584) | Sep 08, 2025 |
| Intel         | B75                         | Desktop     | [c56e05a0cb](https://linux-hardware.org/?probe=c56e05a0cb) | Sep 08, 2025 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [2268691e76](https://linux-hardware.org/?probe=2268691e76) | Sep 08, 2025 |
| Apple         | Mac-F221BEC8                | Desktop     | [dc8749ea1a](https://linux-hardware.org/?probe=dc8749ea1a) | Sep 06, 2025 |
| Apple         | Mac-F221BEC8                | Desktop     | [24da95c103](https://linux-hardware.org/?probe=24da95c103) | Sep 06, 2025 |
| Vestel        | V TAB 1041                  | Tablet      | [a7365213cc](https://linux-hardware.org/?probe=a7365213cc) | Sep 06, 2025 |
| Vestel        | V TAB 1041                  | Tablet      | [9e4d409ed0](https://linux-hardware.org/?probe=9e4d409ed0) | Sep 06, 2025 |
| Apple         | Mac-F221BEC8                | Desktop     | [d2333eb609](https://linux-hardware.org/?probe=d2333eb609) | Sep 06, 2025 |
| Apple         | Mac-F221BEC8                | Desktop     | [c79fc37b25](https://linux-hardware.org/?probe=c79fc37b25) | Sep 06, 2025 |
| Acer          | Aspire V3-571G              | Notebook    | [5763a22570](https://linux-hardware.org/?probe=5763a22570) | Sep 06, 2025 |
| Acer          | Aspire A715-42G             | Notebook    | [90ee240b66](https://linux-hardware.org/?probe=90ee240b66) | Sep 05, 2025 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9ff204113f](https://linux-hardware.org/?probe=9ff204113f) | Sep 04, 2025 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [a8775b4cb8](https://linux-hardware.org/?probe=a8775b4cb8) | Sep 03, 2025 |
| Gigabyte      | P43T-ES3G                   | Desktop     | [f1db8ceb48](https://linux-hardware.org/?probe=f1db8ceb48) | Sep 03, 2025 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [d71e51d684](https://linux-hardware.org/?probe=d71e51d684) | Sep 03, 2025 |
| HP            | EliteBook 2560p             | Notebook    | [23ad372c3e](https://linux-hardware.org/?probe=23ad372c3e) | Sep 03, 2025 |
| Biostar       | TB250-BTC                   | Desktop     | [2617fff756](https://linux-hardware.org/?probe=2617fff756) | Sep 02, 2025 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [98fcf3a06e](https://linux-hardware.org/?probe=98fcf3a06e) | Sep 02, 2025 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [ca71aa02d3](https://linux-hardware.org/?probe=ca71aa02d3) | Sep 02, 2025 |
| GEEKOM        | A5                          | Desktop     | [12e93a6e5f](https://linux-hardware.org/?probe=12e93a6e5f) | Sep 02, 2025 |
| MB            | Q470E-HD                    | Desktop     | [1c12da4fcc](https://linux-hardware.org/?probe=1c12da4fcc) | Aug 31, 2025 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [088f6d5f49](https://linux-hardware.org/?probe=088f6d5f49) | Aug 29, 2025 |
| Lenovo        | ThinkPad E14 Gen 5 21JLS... | Notebook    | [8988036fbd](https://linux-hardware.org/?probe=8988036fbd) | Aug 28, 2025 |
| Valve         | Jupiter                     | Notebook    | [32db0d6158](https://linux-hardware.org/?probe=32db0d6158) | Aug 28, 2025 |
| ASUSTek       | ROG STRIX Z790-F GAMING ... | Desktop     | [ebad708480](https://linux-hardware.org/?probe=ebad708480) | Aug 28, 2025 |
| Colorful T... | BATTLE-AX B450M-HD V14      | Desktop     | [be96fc9817](https://linux-hardware.org/?probe=be96fc9817) | Aug 28, 2025 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [7dd7552859](https://linux-hardware.org/?probe=7dd7552859) | Aug 27, 2025 |
| ASRock        | B450M Pro4                  | Desktop     | [68560c20d5](https://linux-hardware.org/?probe=68560c20d5) | Aug 27, 2025 |
| IBM           | M97IP SIT                   | Desktop     | [417fcf3ec5](https://linux-hardware.org/?probe=417fcf3ec5) | Aug 25, 2025 |
| Dell          | G3 3579                     | Notebook    | [4d6d62ace4](https://linux-hardware.org/?probe=4d6d62ace4) | Aug 25, 2025 |
| Dell          | G3 3579                     | Notebook    | [c4ed4fde8f](https://linux-hardware.org/?probe=c4ed4fde8f) | Aug 25, 2025 |
| ASUSTek       | ZenBook UX334FLC_UX334FL    | Notebook    | [c43264f446](https://linux-hardware.org/?probe=c43264f446) | Aug 24, 2025 |
| Dell          | Vostro 3700                 | Notebook    | [68fd9153a9](https://linux-hardware.org/?probe=68fd9153a9) | Aug 24, 2025 |
| Gigabyte      | B450M S2H V2                | Desktop     | [bfe622530d](https://linux-hardware.org/?probe=bfe622530d) | Aug 24, 2025 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | Notebook    | [6489963d6c](https://linux-hardware.org/?probe=6489963d6c) | Aug 23, 2025 |
| MSI           | X670E GAMING PLUS WIFI      | Desktop     | [f389e0b3ad](https://linux-hardware.org/?probe=f389e0b3ad) | Aug 23, 2025 |
| Pegatron      | IPMIP                       | Desktop     | [7936f2c936](https://linux-hardware.org/?probe=7936f2c936) | Aug 23, 2025 |
| Lenovo        | LOQ 15IAX9 83GS             | Notebook    | [5b3e3aa4a0](https://linux-hardware.org/?probe=5b3e3aa4a0) | Aug 23, 2025 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [32d03ca75c](https://linux-hardware.org/?probe=32d03ca75c) | Aug 23, 2025 |
| Monster       | ABRA A7 V11.4               | Notebook    | [848ac0dde1](https://linux-hardware.org/?probe=848ac0dde1) | Aug 22, 2025 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [c1ec7c1d76](https://linux-hardware.org/?probe=c1ec7c1d76) | Aug 22, 2025 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [31feb992ec](https://linux-hardware.org/?probe=31feb992ec) | Aug 22, 2025 |
| MSI           | B450M-A PRO MAX             | Desktop     | [c1b735894a](https://linux-hardware.org/?probe=c1b735894a) | Aug 22, 2025 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [1e5d4a9269](https://linux-hardware.org/?probe=1e5d4a9269) | Aug 22, 2025 |
| Lenovo        | LOQ 15APH8 82XT             | Notebook    | [39d744cdf9](https://linux-hardware.org/?probe=39d744cdf9) | Aug 20, 2025 |
| Lenovo        | LOQ 15APH8 82XT             | Notebook    | [ddf3a1afcc](https://linux-hardware.org/?probe=ddf3a1afcc) | Aug 20, 2025 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | Notebook    | [d0816a94d1](https://linux-hardware.org/?probe=d0816a94d1) | Aug 20, 2025 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | Notebook    | [69b194d78f](https://linux-hardware.org/?probe=69b194d78f) | Aug 20, 2025 |
| Monster       | TULPAR T6 V3.2              | Notebook    | [fd985079cf](https://linux-hardware.org/?probe=fd985079cf) | Aug 20, 2025 |
| Gigabyte      | P55-UD4                     | Desktop     | [32c448069a](https://linux-hardware.org/?probe=32c448069a) | Aug 19, 2025 |
| Gigabyte      | P55-UD4                     | Desktop     | [6a8f231b70](https://linux-hardware.org/?probe=6a8f231b70) | Aug 19, 2025 |
| MSI           | B450M-A PRO MAX             | Desktop     | [5e6b0782a5](https://linux-hardware.org/?probe=5e6b0782a5) | Aug 18, 2025 |
| MSI           | B650M PROJECT ZERO          | Desktop     | [b95c45ba32](https://linux-hardware.org/?probe=b95c45ba32) | Aug 18, 2025 |
| HUAWEI        | FLMH-XX                     | Notebook    | [4e96f40051](https://linux-hardware.org/?probe=4e96f40051) | Aug 17, 2025 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [783baa3d24](https://linux-hardware.org/?probe=783baa3d24) | Aug 17, 2025 |
| Dell          | Latitude 3550               | Notebook    | [327c576656](https://linux-hardware.org/?probe=327c576656) | Aug 17, 2025 |
| MSI           | MAG X870E TOMAHAWK WIFI     | Desktop     | [9e2a480cbd](https://linux-hardware.org/?probe=9e2a480cbd) | Aug 17, 2025 |
| MSI           | MAG X870E TOMAHAWK WIFI     | Desktop     | [2dcfe31538](https://linux-hardware.org/?probe=2dcfe31538) | Aug 17, 2025 |
| Dell          | Latitude 3550               | Notebook    | [dfb09ed5b4](https://linux-hardware.org/?probe=dfb09ed5b4) | Aug 15, 2025 |
| Lenovo        | ThinkPad E14 Gen 5 21JLS... | Notebook    | [1029208516](https://linux-hardware.org/?probe=1029208516) | Aug 15, 2025 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [7a029bec96](https://linux-hardware.org/?probe=7a029bec96) | Aug 14, 2025 |
| Unknown       | Marble based on Qualcomm... | Soc         | [42cf0d307c](https://linux-hardware.org/?probe=42cf0d307c) | Aug 14, 2025 |
| Unknown       | Marble based on Qualcomm... | Soc         | [7f2456a8d1](https://linux-hardware.org/?probe=7f2456a8d1) | Aug 14, 2025 |
| Acer          | Aspire A315-59G             | Notebook    | [48d9443c46](https://linux-hardware.org/?probe=48d9443c46) | Aug 13, 2025 |
| Gigabyte      | GA-MA790XT-UD4P             | Desktop     | [ec16a7bee9](https://linux-hardware.org/?probe=ec16a7bee9) | Aug 11, 2025 |
| Lenovo        | Legion Pro 7 16IAX10H 83... | Notebook    | [e6f42877ea](https://linux-hardware.org/?probe=e6f42877ea) | Aug 10, 2025 |
| Acer          | Aspire 6930G                | Notebook    | [f8585c40b2](https://linux-hardware.org/?probe=f8585c40b2) | Aug 10, 2025 |
| HP            | Pavilion g6                 | Notebook    | [dbc0417730](https://linux-hardware.org/?probe=dbc0417730) | Aug 10, 2025 |
| ASUSTek       | Z97-AR                      | Desktop     | [9f2cce0f15](https://linux-hardware.org/?probe=9f2cce0f15) | Aug 09, 2025 |
| Packard Be... | EasyNote TE69KB             | Notebook    | [1c25c5be01](https://linux-hardware.org/?probe=1c25c5be01) | Aug 08, 2025 |
| HP            | EliteBook 8460p             | Notebook    | [bf32030e39](https://linux-hardware.org/?probe=bf32030e39) | Aug 08, 2025 |
| Dell          | Latitude 3550               | Notebook    | [54b25dd468](https://linux-hardware.org/?probe=54b25dd468) | Aug 07, 2025 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [a13b9660b9](https://linux-hardware.org/?probe=a13b9660b9) | Aug 07, 2025 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [7c61895b58](https://linux-hardware.org/?probe=7c61895b58) | Aug 07, 2025 |
| HP            | 0AECh D                     | Desktop     | [717c788ce8](https://linux-hardware.org/?probe=717c788ce8) | Aug 07, 2025 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [86c7998cee](https://linux-hardware.org/?probe=86c7998cee) | Aug 07, 2025 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [b73b1b1ca1](https://linux-hardware.org/?probe=b73b1b1ca1) | Aug 06, 2025 |
| HP            | 8ACE                        | All in one  | [fa58dc124d](https://linux-hardware.org/?probe=fa58dc124d) | Aug 06, 2025 |
| ASUSTek       | TUF Gaming A620M-PLUS       | Desktop     | [8b150a2a76](https://linux-hardware.org/?probe=8b150a2a76) | Aug 04, 2025 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [123e894aae](https://linux-hardware.org/?probe=123e894aae) | Aug 04, 2025 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [78e2f65453](https://linux-hardware.org/?probe=78e2f65453) | Aug 04, 2025 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | Notebook    | [7a2f9368ee](https://linux-hardware.org/?probe=7a2f9368ee) | Aug 03, 2025 |
| HUAWEI        | MCLF-XX                     | Notebook    | [30715fe958](https://linux-hardware.org/?probe=30715fe958) | Aug 03, 2025 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [8307e6bffe](https://linux-hardware.org/?probe=8307e6bffe) | Aug 02, 2025 |
| HP            | Pavilion g6                 | Notebook    | [d86ad94a91](https://linux-hardware.org/?probe=d86ad94a91) | Aug 01, 2025 |
| ASUSTek       | TUF Gaming B850-PLUS WIF... | Desktop     | [fe2a915673](https://linux-hardware.org/?probe=fe2a915673) | Aug 01, 2025 |
| Dell          | Inspiron 3542               | Notebook    | [f53d472b4d](https://linux-hardware.org/?probe=f53d472b4d) | Jul 31, 2025 |
| HP            | ProBook 4540s               | Notebook    | [ff1d644d77](https://linux-hardware.org/?probe=ff1d644d77) | Jul 31, 2025 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [4489d2cfd8](https://linux-hardware.org/?probe=4489d2cfd8) | Jul 30, 2025 |
| Lenovo        | ThinkPad P16v Gen 1 21FD... | Notebook    | [8dd9ec5849](https://linux-hardware.org/?probe=8dd9ec5849) | Jul 30, 2025 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [ccd25e612b](https://linux-hardware.org/?probe=ccd25e612b) | Jul 28, 2025 |
| Casper        | EXCALIBUR G770              | Notebook    | [d48c4692bd](https://linux-hardware.org/?probe=d48c4692bd) | Jul 28, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [25a4bc4daa](https://linux-hardware.org/?probe=25a4bc4daa) | Jul 27, 2025 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [ba9b040f5b](https://linux-hardware.org/?probe=ba9b040f5b) | Jul 27, 2025 |
| MSI           | PRO H610M-E DDR4            | Desktop     | [8e389b3125](https://linux-hardware.org/?probe=8e389b3125) | Jul 23, 2025 |
| Acer          | Swift SF314-43              | Notebook    | [9220e3d599](https://linux-hardware.org/?probe=9220e3d599) | Jul 21, 2025 |
| Casper        | NIRVANA NB F500             | Notebook    | [75ea803ab3](https://linux-hardware.org/?probe=75ea803ab3) | Jul 21, 2025 |
| Casper        | NIRVANA NB F500             | Notebook    | [7d0398ec28](https://linux-hardware.org/?probe=7d0398ec28) | Jul 21, 2025 |
| Gigabyte      | H610M H DDR4                | Desktop     | [fea0e04b12](https://linux-hardware.org/?probe=fea0e04b12) | Jul 21, 2025 |
| Gigabyte      | H610M H DDR4                | Desktop     | [12c0e8c11e](https://linux-hardware.org/?probe=12c0e8c11e) | Jul 21, 2025 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [c6261f13d2](https://linux-hardware.org/?probe=c6261f13d2) | Jul 20, 2025 |
| Lenovo        | Yoga 7 2-in-1 14AKP10 83... | Convertible | [a39a487099](https://linux-hardware.org/?probe=a39a487099) | Jul 20, 2025 |
| Samsung       | Galaxy E7                   | Notebook    | [82f6f4d999](https://linux-hardware.org/?probe=82f6f4d999) | Jul 19, 2025 |
| Lenovo        | ThinkPad E580 20KTS0TF00    | Notebook    | [466812d8c4](https://linux-hardware.org/?probe=466812d8c4) | Jul 19, 2025 |
| Samsung       | Galaxy E7                   | Notebook    | [8b5170252f](https://linux-hardware.org/?probe=8b5170252f) | Jul 19, 2025 |
| Intel         | B75                         | Desktop     | [907ec82992](https://linux-hardware.org/?probe=907ec82992) | Jul 19, 2025 |
| MSI           | Cyborg 15 A13VF             | Notebook    | [3d8c425bf3](https://linux-hardware.org/?probe=3d8c425bf3) | Jul 18, 2025 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [dd28fb514f](https://linux-hardware.org/?probe=dd28fb514f) | Jul 18, 2025 |
| Lenovo        | ThinkPad T15 Gen 2i 20W5... | Notebook    | [68d6d7fa91](https://linux-hardware.org/?probe=68d6d7fa91) | Jul 18, 2025 |
| Monster       | ABRA A7 V11.1               | Notebook    | [051af9ef06](https://linux-hardware.org/?probe=051af9ef06) | Jul 18, 2025 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [be6a9aebf2](https://linux-hardware.org/?probe=be6a9aebf2) | Jul 17, 2025 |
| HUAWEI        | BoDE-WXX9                   | Notebook    | [a85969d276](https://linux-hardware.org/?probe=a85969d276) | Jul 17, 2025 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [8d150e17c5](https://linux-hardware.org/?probe=8d150e17c5) | Jul 16, 2025 |
| MSI           | MEG Z490 UNIFY              | Desktop     | [b492fa7bb9](https://linux-hardware.org/?probe=b492fa7bb9) | Jul 15, 2025 |
| Lenovo        | Yoga 7 2-in-1 14AKP10 83... | Convertible | [ba395dd6dc](https://linux-hardware.org/?probe=ba395dd6dc) | Jul 15, 2025 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | Notebook    | [46c8a419cc](https://linux-hardware.org/?probe=46c8a419cc) | Jul 15, 2025 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | Notebook    | [a7234c1ad4](https://linux-hardware.org/?probe=a7234c1ad4) | Jul 15, 2025 |
| ASUSTek       | ROG Zephyrus G16 GA605WI... | Notebook    | [e5fda08e3a](https://linux-hardware.org/?probe=e5fda08e3a) | Jul 15, 2025 |
| Acer          | Aspire A514-52G             | Notebook    | [dd1e58abdb](https://linux-hardware.org/?probe=dd1e58abdb) | Jul 14, 2025 |
| Toshiba       | TEM130NE                    | Desktop     | [d60b748b8c](https://linux-hardware.org/?probe=d60b748b8c) | Jul 14, 2025 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [4236407aad](https://linux-hardware.org/?probe=4236407aad) | Jul 13, 2025 |
| Casper        | EXCALIBUR G911              | Notebook    | [b7cd8912cb](https://linux-hardware.org/?probe=b7cd8912cb) | Jul 13, 2025 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [019fd9c7a4](https://linux-hardware.org/?probe=019fd9c7a4) | Jul 13, 2025 |
| ARCELIK       | GNB-1588-B1-i5              | Notebook    | [709f449e12](https://linux-hardware.org/?probe=709f449e12) | Jul 13, 2025 |
| MSI           | Titan GT77HX 13VI           | Notebook    | [25bfaf6439](https://linux-hardware.org/?probe=25bfaf6439) | Jul 13, 2025 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [951d597814](https://linux-hardware.org/?probe=951d597814) | Jul 13, 2025 |
| HP            | Pavilion g6                 | Notebook    | [dd8d822e2a](https://linux-hardware.org/?probe=dd8d822e2a) | Jul 12, 2025 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [d63d61be20](https://linux-hardware.org/?probe=d63d61be20) | Jul 12, 2025 |
| ASRock        | A520M-HVS                   | Desktop     | [137d65bc97](https://linux-hardware.org/?probe=137d65bc97) | Jul 12, 2025 |
| Toshiba       | Satellite L70-B             | Notebook    | [b783ae60b2](https://linux-hardware.org/?probe=b783ae60b2) | Jul 11, 2025 |
| Acer          | Aspire ES1-533              | Notebook    | [7a0fe4e115](https://linux-hardware.org/?probe=7a0fe4e115) | Jul 11, 2025 |
| Lenovo        | ThinkPad E580 20KTS0TF00    | Notebook    | [88daaafa2c](https://linux-hardware.org/?probe=88daaafa2c) | Jul 11, 2025 |
| Dell          | 0V8WGR A00                  | Desktop     | [15378f365c](https://linux-hardware.org/?probe=15378f365c) | Jul 11, 2025 |
| HP            | Pavilion g6                 | Notebook    | [60870620e8](https://linux-hardware.org/?probe=60870620e8) | Jul 11, 2025 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [f4409ac4b6](https://linux-hardware.org/?probe=f4409ac4b6) | Jul 09, 2025 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [5064d95840](https://linux-hardware.org/?probe=5064d95840) | Jul 09, 2025 |
| Gigabyte      | A520M K                     | Desktop     | [22b9bba19d](https://linux-hardware.org/?probe=22b9bba19d) | Jul 09, 2025 |
| Lenovo        | ThinkPad E580 20KTS0TF00    | Notebook    | [f467f63508](https://linux-hardware.org/?probe=f467f63508) | Jul 09, 2025 |
| Monster       | ABRA A5 V13.2               | Notebook    | [de1d6de389](https://linux-hardware.org/?probe=de1d6de389) | Jul 09, 2025 |
| MSI           | B350M PRO-VD PLUS           | Desktop     | [69099dcd30](https://linux-hardware.org/?probe=69099dcd30) | Jul 08, 2025 |
| HUAWEI        | HKD-WXX                     | Notebook    | [a6328b3d4a](https://linux-hardware.org/?probe=a6328b3d4a) | Jul 07, 2025 |
| Lenovo        | LOQ 15ARP9 83JC             | Notebook    | [5c26d81542](https://linux-hardware.org/?probe=5c26d81542) | Jul 07, 2025 |
| HP            | 8061                        | Desktop     | [3bb8f78e3f](https://linux-hardware.org/?probe=3bb8f78e3f) | Jul 07, 2025 |
| MSI           | GF65 Thin 10SDR             | Notebook    | [7e45436acd](https://linux-hardware.org/?probe=7e45436acd) | Jul 06, 2025 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | Notebook    | [7d2d3b45d8](https://linux-hardware.org/?probe=7d2d3b45d8) | Jul 06, 2025 |
| GAME GARAJ    | SLAYER R9T                  | Notebook    | [d1e4091dc0](https://linux-hardware.org/?probe=d1e4091dc0) | Jul 03, 2025 |
| HUAWEI        | MCLF-XX                     | Notebook    | [791ead94bb](https://linux-hardware.org/?probe=791ead94bb) | Jul 02, 2025 |
| Gigabyte      | A520M H                     | Desktop     | [da37b8514f](https://linux-hardware.org/?probe=da37b8514f) | Jul 02, 2025 |
| Gigabyte      | GA-MA790XT-UD4P             | Desktop     | [dfe8ea0e46](https://linux-hardware.org/?probe=dfe8ea0e46) | Jul 01, 2025 |
| Monster       | ABRA A5 V12.1               | Notebook    | [60a8ef7f79](https://linux-hardware.org/?probe=60a8ef7f79) | Jul 01, 2025 |
| Casper        | NIRVANA DESKTOP             | Desktop     | [a50879b70b](https://linux-hardware.org/?probe=a50879b70b) | Jun 30, 2025 |
| ASUSTek       | ROG Maximus Z790 DARK HE... | Desktop     | [2fb1af7089](https://linux-hardware.org/?probe=2fb1af7089) | Jun 30, 2025 |
| Lenovo        | ThinkPad E595 20NF001PTX    | Notebook    | [66ac47b979](https://linux-hardware.org/?probe=66ac47b979) | Jun 30, 2025 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [fcb33f597d](https://linux-hardware.org/?probe=fcb33f597d) | Jun 30, 2025 |
| Unknown       | Marble based on Qualcomm... | Soc         | [f0afe838fb](https://linux-hardware.org/?probe=f0afe838fb) | Jun 30, 2025 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e21ebe2d2c](https://linux-hardware.org/?probe=e21ebe2d2c) | Jun 29, 2025 |
| Lenovo        | ThinkPad T14s Gen 6 21QX... | Notebook    | [6e07556619](https://linux-hardware.org/?probe=6e07556619) | Jun 29, 2025 |
| Intel         | H61                         | Desktop     | [82c5b68116](https://linux-hardware.org/?probe=82c5b68116) | Jun 29, 2025 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d2ecd40334](https://linux-hardware.org/?probe=d2ecd40334) | Jun 29, 2025 |
| Casper        | NIRVANA NB S500 SILVER      | Notebook    | [e5590f3a43](https://linux-hardware.org/?probe=e5590f3a43) | Jun 29, 2025 |
| HUAWEI        | MCLF-XX                     | Notebook    | [9d92482fcf](https://linux-hardware.org/?probe=9d92482fcf) | Jun 28, 2025 |
| Casper        | NIRVANA N310                | Notebook    | [88f74e79a0](https://linux-hardware.org/?probe=88f74e79a0) | Jun 26, 2025 |
| Casper        | NIRVANA NB S500 SILVER      | Notebook    | [74467fcac4](https://linux-hardware.org/?probe=74467fcac4) | Jun 26, 2025 |
| ASUSTek       | K55VJ                       | Notebook    | [85f2bbb828](https://linux-hardware.org/?probe=85f2bbb828) | Jun 25, 2025 |
| Acer          | Swift SF314-43              | Notebook    | [6b2ecffc79](https://linux-hardware.org/?probe=6b2ecffc79) | Jun 23, 2025 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [3e440fc3d7](https://linux-hardware.org/?probe=3e440fc3d7) | Jun 23, 2025 |
| HUAWEI        | HN-WX9X                     | Notebook    | [64236be0dd](https://linux-hardware.org/?probe=64236be0dd) | Jun 23, 2025 |
| ASUSTek       | X550LC                      | Notebook    | [d0170c2403](https://linux-hardware.org/?probe=d0170c2403) | Jun 22, 2025 |
| Google        | Pujjo                       | Notebook    | [95a036afce](https://linux-hardware.org/?probe=95a036afce) | Jun 22, 2025 |
| Dell          | 0XHGV1 A00                  | Desktop     | [54b06c7373](https://linux-hardware.org/?probe=54b06c7373) | Jun 21, 2025 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [7478fc66cc](https://linux-hardware.org/?probe=7478fc66cc) | Jun 20, 2025 |
| Monster       | TULPAR T5 V23.2             | Notebook    | [9a4e30b1f6](https://linux-hardware.org/?probe=9a4e30b1f6) | Jun 20, 2025 |
| Sony          | VPCEH1S8E                   | Notebook    | [ea19134f6e](https://linux-hardware.org/?probe=ea19134f6e) | Jun 19, 2025 |
| HP            | EliteBook 840 G6            | Notebook    | [874e4215ed](https://linux-hardware.org/?probe=874e4215ed) | Jun 19, 2025 |
| Acer          | Aspire V3-571G              | Notebook    | [3748684271](https://linux-hardware.org/?probe=3748684271) | Jun 19, 2025 |
| MSI           | Pulse 16 AI C1VFKG          | Notebook    | [bd0d3ad6fe](https://linux-hardware.org/?probe=bd0d3ad6fe) | Jun 18, 2025 |
| Intel         | H61                         | Desktop     | [f0fd715ee9](https://linux-hardware.org/?probe=f0fd715ee9) | Jun 18, 2025 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [c6a728b131](https://linux-hardware.org/?probe=c6a728b131) | Jun 17, 2025 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [0534b30874](https://linux-hardware.org/?probe=0534b30874) | Jun 16, 2025 |
| ASUSTek       | TP300LD                     | Notebook    | [77a1a67283](https://linux-hardware.org/?probe=77a1a67283) | Jun 15, 2025 |
| ASUSTek       | X541UV                      | Notebook    | [5b96592d37](https://linux-hardware.org/?probe=5b96592d37) | Jun 15, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [86a62d4e6e](https://linux-hardware.org/?probe=86a62d4e6e) | Jun 13, 2025 |
| HP            | Pavilion g6                 | Notebook    | [585539a98d](https://linux-hardware.org/?probe=585539a98d) | Jun 13, 2025 |
| ASUSTek       | ROG Maximus Z790 DARK HE... | Desktop     | [d8438e1d22](https://linux-hardware.org/?probe=d8438e1d22) | Jun 12, 2025 |
| Dell          | Vostro 3520                 | Notebook    | [b39316f007](https://linux-hardware.org/?probe=b39316f007) | Jun 11, 2025 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [d6edf0c3b7](https://linux-hardware.org/?probe=d6edf0c3b7) | Jun 11, 2025 |
| Lenovo        | Legion Go S 8ARP1 83L3      | Tablet      | [df13732959](https://linux-hardware.org/?probe=df13732959) | Jun 11, 2025 |
| Microsoft     | Surface Book                | Tablet      | [a122e4a3f6](https://linux-hardware.org/?probe=a122e4a3f6) | Jun 10, 2025 |
| Lenovo        | IdeaPad Y550 20017          | Notebook    | [be65265c86](https://linux-hardware.org/?probe=be65265c86) | Jun 10, 2025 |
| Toshiba       | Satellite L50-B             | Notebook    | [0b63f677e2](https://linux-hardware.org/?probe=0b63f677e2) | Jun 07, 2025 |
| Toshiba       | Satellite L50-B             | Notebook    | [77b7ae146e](https://linux-hardware.org/?probe=77b7ae146e) | Jun 07, 2025 |
| ASUSTek       | X542BP                      | Notebook    | [2d0e3d5d3b](https://linux-hardware.org/?probe=2d0e3d5d3b) | Jun 05, 2025 |
| ARCELIK       | GNB-1588-B1-i5              | Notebook    | [1a62b6d03c](https://linux-hardware.org/?probe=1a62b6d03c) | Jun 05, 2025 |
| Sony          | VPCEH1S8E                   | Notebook    | [ab140b5a60](https://linux-hardware.org/?probe=ab140b5a60) | Jun 05, 2025 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [b06e73acf7](https://linux-hardware.org/?probe=b06e73acf7) | Jun 05, 2025 |
| Monster       | TULPAR T7                   | Notebook    | [00ec735d9d](https://linux-hardware.org/?probe=00ec735d9d) | Jun 04, 2025 |
| Apple         | MacBookPro11,1              | Notebook    | [53ac9ab67c](https://linux-hardware.org/?probe=53ac9ab67c) | Jun 04, 2025 |
| MSI           | PRO H610M-E                 | Desktop     | [dc9519213c](https://linux-hardware.org/?probe=dc9519213c) | Jun 03, 2025 |
| ASRock        | Z590M Phantom Gaming 4      | Desktop     | [06cd1e5007](https://linux-hardware.org/?probe=06cd1e5007) | Jun 02, 2025 |
| HP            | Pavilion g6                 | Notebook    | [21a4945fa5](https://linux-hardware.org/?probe=21a4945fa5) | Jun 02, 2025 |
| ASUSTek       | D520MT_D520SF_D320MT        | Desktop     | [8130f151f8](https://linux-hardware.org/?probe=8130f151f8) | Jun 02, 2025 |
| Dell          | Inspiron 14 5401            | Notebook    | [b587eb2c25](https://linux-hardware.org/?probe=b587eb2c25) | Jun 02, 2025 |
| ASRock        | B450M Steel Legend          | Desktop     | [9a75216e21](https://linux-hardware.org/?probe=9a75216e21) | Jun 01, 2025 |
| Apple         | MacBookPro11,1              | Notebook    | [fbcd2dfff6](https://linux-hardware.org/?probe=fbcd2dfff6) | May 31, 2025 |
| ASUSTek       | D520MT_D520SF_D320MT        | Desktop     | [ff74b49f76](https://linux-hardware.org/?probe=ff74b49f76) | May 31, 2025 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [63e3eafb34](https://linux-hardware.org/?probe=63e3eafb34) | May 30, 2025 |
| Monster       | ABRA A5 V13.2               | Notebook    | [5ff0188598](https://linux-hardware.org/?probe=5ff0188598) | May 28, 2025 |
| Lenovo        | Sunrise 1000 20443          | Notebook    | [023dbbdd9f](https://linux-hardware.org/?probe=023dbbdd9f) | May 28, 2025 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [d1e3c519d5](https://linux-hardware.org/?probe=d1e3c519d5) | May 28, 2025 |
| Lenovo        | 3780 No DPK                 | All in one  | [a62b04f648](https://linux-hardware.org/?probe=a62b04f648) | May 26, 2025 |
| Casper        | NIRVANA NB C500             | Notebook    | [eb0677862d](https://linux-hardware.org/?probe=eb0677862d) | May 25, 2025 |
| Lenovo        | ThinkPad T480 20L6S68A00    | Notebook    | [95533caccc](https://linux-hardware.org/?probe=95533caccc) | May 24, 2025 |
| Gigabyte      | M68MT-S2                    | Desktop     | [01b494cfab](https://linux-hardware.org/?probe=01b494cfab) | May 23, 2025 |
| Acer          | Nitro AN515-42              | Notebook    | [02c7fbb736](https://linux-hardware.org/?probe=02c7fbb736) | May 23, 2025 |
| Toshiba       | Satellite L50-A-1CX         | Notebook    | [cdb379186f](https://linux-hardware.org/?probe=cdb379186f) | May 21, 2025 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [5d95e1a0b4](https://linux-hardware.org/?probe=5d95e1a0b4) | May 20, 2025 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [37c39bcb5f](https://linux-hardware.org/?probe=37c39bcb5f) | May 20, 2025 |
| Monster       | ABRA A5 V17.4               | Notebook    | [2b06711967](https://linux-hardware.org/?probe=2b06711967) | May 20, 2025 |
| Monster       | ABRA A5 V16.7               | Notebook    | [c19a1406c5](https://linux-hardware.org/?probe=c19a1406c5) | May 19, 2025 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [6b2964291e](https://linux-hardware.org/?probe=6b2964291e) | May 19, 2025 |
| Gigabyte      | H610M H V2                  | Desktop     | [e4ea3b5d5a](https://linux-hardware.org/?probe=e4ea3b5d5a) | May 19, 2025 |
| HUAWEI        | BoDE-WXX9                   | Notebook    | [486e389318](https://linux-hardware.org/?probe=486e389318) | May 19, 2025 |
| Gigabyte      | X99-Gaming 7 WIFI           | Desktop     | [c2ae8ce925](https://linux-hardware.org/?probe=c2ae8ce925) | May 19, 2025 |
| MSI           | H410M PRO-VH                | Desktop     | [1437123bd2](https://linux-hardware.org/?probe=1437123bd2) | May 18, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [43e457c12d](https://linux-hardware.org/?probe=43e457c12d) | May 18, 2025 |
| HUAWEI        | BoDE-WXX9                   | Notebook    | [20a26e11ee](https://linux-hardware.org/?probe=20a26e11ee) | May 17, 2025 |
| Gigabyte      | H61M-DS2H                   | Desktop     | [fc5f7f027c](https://linux-hardware.org/?probe=fc5f7f027c) | May 17, 2025 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [3573b94fb8](https://linux-hardware.org/?probe=3573b94fb8) | May 17, 2025 |
| MSI           | MAG X870 TOMAHAWK WIFI      | Desktop     | [a805c2f174](https://linux-hardware.org/?probe=a805c2f174) | May 16, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | Notebook    | [4f05bce3d3](https://linux-hardware.org/?probe=4f05bce3d3) | May 16, 2025 |
| Monster       | ABRA A5 V9.1                | Notebook    | [c993cde3c1](https://linux-hardware.org/?probe=c993cde3c1) | May 16, 2025 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [1238ee7d4f](https://linux-hardware.org/?probe=1238ee7d4f) | May 15, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [34eb80d0a8](https://linux-hardware.org/?probe=34eb80d0a8) | May 15, 2025 |
| ASUSTek       | ROG Strix G614JZ_G614JZ     | Notebook    | [2695b61f8f](https://linux-hardware.org/?probe=2695b61f8f) | May 11, 2025 |
| Lenovo        | LOQ 15IAX9 83GS             | Notebook    | [58e8905792](https://linux-hardware.org/?probe=58e8905792) | May 11, 2025 |
| ASUSTek       | N53SV                       | Notebook    | [344d2b1b0a](https://linux-hardware.org/?probe=344d2b1b0a) | May 10, 2025 |
| HP            | Elite x2 G4                 | Tablet      | [58ab241df2](https://linux-hardware.org/?probe=58ab241df2) | May 10, 2025 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [9247aa720e](https://linux-hardware.org/?probe=9247aa720e) | May 10, 2025 |
| Monster       | ABRA A5 V15.6               | Notebook    | [58b66cd31f](https://linux-hardware.org/?probe=58b66cd31f) | May 10, 2025 |
| Biostar       | B550MH                      | Desktop     | [8410d40379](https://linux-hardware.org/?probe=8410d40379) | May 10, 2025 |
| Microsoft     | Surface Book 2              | Tablet      | [9dd7871ded](https://linux-hardware.org/?probe=9dd7871ded) | May 10, 2025 |
| HP            | Pavilion g6                 | Notebook    | [ec70a9c4c9](https://linux-hardware.org/?probe=ec70a9c4c9) | May 10, 2025 |
| HP            | Pavilion g6                 | Notebook    | [680ec113ca](https://linux-hardware.org/?probe=680ec113ca) | May 10, 2025 |
| HP            | ZBook 15 G3                 | Notebook    | [a2a2de15fd](https://linux-hardware.org/?probe=a2a2de15fd) | May 09, 2025 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [0fbbf4a950](https://linux-hardware.org/?probe=0fbbf4a950) | May 08, 2025 |
| ASUSTek       | D520MT_D520SF_D320MT        | Desktop     | [ccdf156a1b](https://linux-hardware.org/?probe=ccdf156a1b) | May 08, 2025 |
| MSI           | Z790 GAMING PLUS WIFI       | Desktop     | [ba7d88f9c4](https://linux-hardware.org/?probe=ba7d88f9c4) | May 08, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [50c3fd7115](https://linux-hardware.org/?probe=50c3fd7115) | May 08, 2025 |
| Monster       | ABRA A5 V15.6               | Notebook    | [6010c21044](https://linux-hardware.org/?probe=6010c21044) | May 07, 2025 |
| MSI           | PS63 Modern 8RC             | Notebook    | [8f7af522c4](https://linux-hardware.org/?probe=8f7af522c4) | May 07, 2025 |
| Gigabyte      | H610M H DDR4                | Desktop     | [d494e36786](https://linux-hardware.org/?probe=d494e36786) | May 07, 2025 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [c421211645](https://linux-hardware.org/?probe=c421211645) | May 06, 2025 |
| MSI           | B760M GAMING PLUS WIFI      | Desktop     | [f42d470765](https://linux-hardware.org/?probe=f42d470765) | May 06, 2025 |
| Monster       | TULPAR T6 V3.2              | Notebook    | [bb9041588e](https://linux-hardware.org/?probe=bb9041588e) | May 06, 2025 |
| Lenovo        | ThinkPad T480s 20L8S2X20... | Notebook    | [5f63f89811](https://linux-hardware.org/?probe=5f63f89811) | May 05, 2025 |
| Google        | Bobba                       | Notebook    | [d4466ec7db](https://linux-hardware.org/?probe=d4466ec7db) | May 05, 2025 |
| Lenovo        | IdeaPad Pro 5 14APH8 83A... | Notebook    | [4bb4e55c59](https://linux-hardware.org/?probe=4bb4e55c59) | May 04, 2025 |
| Lenovo        | Legion 5 15IAH7H 82RB       | Notebook    | [67270e2b73](https://linux-hardware.org/?probe=67270e2b73) | May 04, 2025 |
| Lenovo        | ThinkPad E580 20KTS0TF00    | Notebook    | [f5060e6c11](https://linux-hardware.org/?probe=f5060e6c11) | May 03, 2025 |
| Monster       | HUMA H4 V6.1                | Notebook    | [266b3c3c1c](https://linux-hardware.org/?probe=266b3c3c1c) | May 03, 2025 |
| Gigabyte      | H610M H DDR4                | Desktop     | [0b7c43f368](https://linux-hardware.org/?probe=0b7c43f368) | May 01, 2025 |
| Lenovo        | G580                        | Notebook    | [316170d5c3](https://linux-hardware.org/?probe=316170d5c3) | May 01, 2025 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | Notebook    | [feb01bf39b](https://linux-hardware.org/?probe=feb01bf39b) | May 01, 2025 |
| Intel         | B75                         | Desktop     | [ea4c550813](https://linux-hardware.org/?probe=ea4c550813) | Apr 30, 2025 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [5eeed879e0](https://linux-hardware.org/?probe=5eeed879e0) | Apr 30, 2025 |
| MSI           | Vector GP76 12UH            | Notebook    | [75657623d4](https://linux-hardware.org/?probe=75657623d4) | Apr 29, 2025 |
| Monster       | ABRA A5 V20.4               | Notebook    | [5a7837e4ee](https://linux-hardware.org/?probe=5a7837e4ee) | Apr 29, 2025 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e36f55c46d](https://linux-hardware.org/?probe=e36f55c46d) | Apr 29, 2025 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [cd181f13f2](https://linux-hardware.org/?probe=cd181f13f2) | Apr 29, 2025 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [188be3f562](https://linux-hardware.org/?probe=188be3f562) | Apr 27, 2025 |
| ASUSTek       | GL753VD                     | Notebook    | [d7f92b7fd9](https://linux-hardware.org/?probe=d7f92b7fd9) | Apr 27, 2025 |
| Samsung       | Galaxy TabPro S             | Tablet      | [6bc0114f80](https://linux-hardware.org/?probe=6bc0114f80) | Apr 27, 2025 |
| Lenovo        | V14 G2 ALC 82KC             | Notebook    | [79ed7c1999](https://linux-hardware.org/?probe=79ed7c1999) | Apr 26, 2025 |
| Dell          | Inspiron 5559               | Notebook    | [a2bb7efdc2](https://linux-hardware.org/?probe=a2bb7efdc2) | Apr 26, 2025 |
| Dell          | Inspiron 3542               | Notebook    | [6046a456dd](https://linux-hardware.org/?probe=6046a456dd) | Apr 26, 2025 |
| Dell          | Inspiron 3542               | Notebook    | [01d79c5e6c](https://linux-hardware.org/?probe=01d79c5e6c) | Apr 26, 2025 |
| Acer          | Aspire 5740                 | Notebook    | [4eab6f4d47](https://linux-hardware.org/?probe=4eab6f4d47) | Apr 25, 2025 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [0463f3c711](https://linux-hardware.org/?probe=0463f3c711) | Apr 25, 2025 |
| HP            | 82F2 A01                    | Desktop     | [5850370be3](https://linux-hardware.org/?probe=5850370be3) | Apr 24, 2025 |
| Casper        | NIRVANA NB X600             | Notebook    | [e72a48f9a2](https://linux-hardware.org/?probe=e72a48f9a2) | Apr 24, 2025 |
| Acer          | Veriton S2680G              | Desktop     | [626097c00c](https://linux-hardware.org/?probe=626097c00c) | Apr 24, 2025 |
| MSI           | CR61 2M/CX61 2OC/CX61 2O... | Notebook    | [e35884e3ff](https://linux-hardware.org/?probe=e35884e3ff) | Apr 24, 2025 |
| Intel         | H61                         | Desktop     | [637bffd512](https://linux-hardware.org/?probe=637bffd512) | Apr 23, 2025 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [7d73362ce4](https://linux-hardware.org/?probe=7d73362ce4) | Apr 23, 2025 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [d65b5ba036](https://linux-hardware.org/?probe=d65b5ba036) | Apr 20, 2025 |
| Gigabyte      | AORUS 15 BKF                | Notebook    | [82dc4059ce](https://linux-hardware.org/?probe=82dc4059ce) | Apr 19, 2025 |
| Gigabyte      | AORUS 15 BKF                | Notebook    | [f9f1923e20](https://linux-hardware.org/?probe=f9f1923e20) | Apr 19, 2025 |
| Lenovo        | IdeaPad Z580                | Notebook    | [b5e43394a2](https://linux-hardware.org/?probe=b5e43394a2) | Apr 19, 2025 |
| Dell          | Vostro 3520                 | Notebook    | [8353888722](https://linux-hardware.org/?probe=8353888722) | Apr 16, 2025 |
| Hometech      | Alfa 470C                   | Notebook    | [bbd183408e](https://linux-hardware.org/?probe=bbd183408e) | Apr 16, 2025 |
| MSI           | B760M GAMING PLUS WIFI      | Desktop     | [a467551015](https://linux-hardware.org/?probe=a467551015) | Apr 16, 2025 |
| Apple         | MacBookPro16,1              | Notebook    | [bdddaf43d6](https://linux-hardware.org/?probe=bdddaf43d6) | Apr 15, 2025 |
| HP            | 83F3                        | Desktop     | [eeab0e374d](https://linux-hardware.org/?probe=eeab0e374d) | Apr 15, 2025 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [769baab401](https://linux-hardware.org/?probe=769baab401) | Apr 14, 2025 |
| ASUSTek       | X55A                        | Notebook    | [a1ae4152d6](https://linux-hardware.org/?probe=a1ae4152d6) | Apr 14, 2025 |
| ASUSTek       | X55A                        | Notebook    | [501a52b727](https://linux-hardware.org/?probe=501a52b727) | Apr 14, 2025 |
| Lenovo        | ThinkBook 16p Gen 4 21J8    | Notebook    | [4990e73b63](https://linux-hardware.org/?probe=4990e73b63) | Apr 14, 2025 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | Desktop     | [89c5c0cb65](https://linux-hardware.org/?probe=89c5c0cb65) | Apr 13, 2025 |
| Lenovo        | LOQ 15APH8 82XT             | Notebook    | [d31eea6a5f](https://linux-hardware.org/?probe=d31eea6a5f) | Apr 13, 2025 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [f6497fe826](https://linux-hardware.org/?probe=f6497fe826) | Apr 13, 2025 |
| Lenovo        | Legion 5 15ARH7 82RE        | Notebook    | [2f120b8144](https://linux-hardware.org/?probe=2f120b8144) | Apr 13, 2025 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [e4a293e128](https://linux-hardware.org/?probe=e4a293e128) | Apr 13, 2025 |
| Acer          | AO722                       | Notebook    | [f2577310d9](https://linux-hardware.org/?probe=f2577310d9) | Apr 13, 2025 |
| Casper        | EXCALIBUR G870              | Notebook    | [71e1788685](https://linux-hardware.org/?probe=71e1788685) | Apr 13, 2025 |
| MSI           | H310M PRO-VD PLUS           | Desktop     | [0ac1790bdc](https://linux-hardware.org/?probe=0ac1790bdc) | Apr 12, 2025 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [4f1f85c174](https://linux-hardware.org/?probe=4f1f85c174) | Apr 12, 2025 |
| Lenovo        | ThinkPad E580 20KTS0TF00    | Notebook    | [3ca5b62bbd](https://linux-hardware.org/?probe=3ca5b62bbd) | Apr 11, 2025 |
| Acer          | Aspire E5-521G              | Notebook    | [968f0e7768](https://linux-hardware.org/?probe=968f0e7768) | Apr 11, 2025 |
| Acer          | Aspire E5-521G              | Notebook    | [0297695447](https://linux-hardware.org/?probe=0297695447) | Apr 11, 2025 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [38696db46c](https://linux-hardware.org/?probe=38696db46c) | Apr 11, 2025 |
| Lenovo        | ThinkPad T14s Gen 4 21F6... | Notebook    | [b38a806d15](https://linux-hardware.org/?probe=b38a806d15) | Apr 10, 2025 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [b174d4a297](https://linux-hardware.org/?probe=b174d4a297) | Apr 10, 2025 |
| HP            | Pavilion g6                 | Notebook    | [9f6a375abf](https://linux-hardware.org/?probe=9f6a375abf) | Apr 10, 2025 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [050788358c](https://linux-hardware.org/?probe=050788358c) | Apr 09, 2025 |
| HP            | Elite x2 G4                 | Tablet      | [b5042ef7a5](https://linux-hardware.org/?probe=b5042ef7a5) | Apr 09, 2025 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [f5f0a7dac2](https://linux-hardware.org/?probe=f5f0a7dac2) | Apr 09, 2025 |
| ASUSTek       | D320MT-K                    | Desktop     | [00fa5036d1](https://linux-hardware.org/?probe=00fa5036d1) | Apr 09, 2025 |
| MSI           | H410M-A PRO                 | Desktop     | [7d45a27213](https://linux-hardware.org/?probe=7d45a27213) | Apr 09, 2025 |
| MSI           | H410M-A PRO                 | Desktop     | [f298ba7a98](https://linux-hardware.org/?probe=f298ba7a98) | Apr 09, 2025 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [1d2cc38e52](https://linux-hardware.org/?probe=1d2cc38e52) | Apr 08, 2025 |
| HUAWEI        | HKFG-XX                     | Notebook    | [0aae7e0f06](https://linux-hardware.org/?probe=0aae7e0f06) | Apr 08, 2025 |
| Lenovo        | ThinkPad T430 2349PT4       | Notebook    | [b2d049baa1](https://linux-hardware.org/?probe=b2d049baa1) | Apr 08, 2025 |
| Biostar       | B650MP-E PRO                | Desktop     | [8ddbcd032f](https://linux-hardware.org/?probe=8ddbcd032f) | Apr 08, 2025 |
| MSI           | Z77A-G43                    | Desktop     | [6252e17a39](https://linux-hardware.org/?probe=6252e17a39) | Apr 07, 2025 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [3cd0b9ace8](https://linux-hardware.org/?probe=3cd0b9ace8) | Apr 06, 2025 |
| Gigabyte      | H610M H DDR4                | Desktop     | [2b3b533b69](https://linux-hardware.org/?probe=2b3b533b69) | Apr 05, 2025 |
| Casper        | MB50IA1                     | Notebook    | [fe2ab9abfc](https://linux-hardware.org/?probe=fe2ab9abfc) | Apr 05, 2025 |
| Acer          | Aspire A315-41G             | Notebook    | [6eda7175e8](https://linux-hardware.org/?probe=6eda7175e8) | Apr 05, 2025 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [782656062a](https://linux-hardware.org/?probe=782656062a) | Apr 03, 2025 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [acafa217ba](https://linux-hardware.org/?probe=acafa217ba) | Apr 03, 2025 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [2d71b7d16d](https://linux-hardware.org/?probe=2d71b7d16d) | Apr 03, 2025 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [842244f717](https://linux-hardware.org/?probe=842244f717) | Apr 02, 2025 |
| Lenovo        | LOQ 15APH8 82XT             | Notebook    | [1ebf3948c8](https://linux-hardware.org/?probe=1ebf3948c8) | Apr 02, 2025 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [19eed49ba8](https://linux-hardware.org/?probe=19eed49ba8) | Apr 02, 2025 |
| Dell          | Inspiron 13-5378            | Notebook    | [1fbcdd2db0](https://linux-hardware.org/?probe=1fbcdd2db0) | Apr 01, 2025 |
| HP            | Laptop 15-bs0xx             | Notebook    | [b89a480461](https://linux-hardware.org/?probe=b89a480461) | Apr 01, 2025 |
| Intel         | DH67BL AAG10189-208         | Desktop     | [3f7d4c5f81](https://linux-hardware.org/?probe=3f7d4c5f81) | Mar 31, 2025 |
| Pegatron      | IPXSB-H61                   | Desktop     | [c78332ddb1](https://linux-hardware.org/?probe=c78332ddb1) | Mar 31, 2025 |
| ARCELIK       | GNB-1588-B1-i5              | Notebook    | [74f367c701](https://linux-hardware.org/?probe=74f367c701) | Mar 30, 2025 |
| ASUSTek       | X550LC                      | Notebook    | [5cac79c673](https://linux-hardware.org/?probe=5cac79c673) | Mar 30, 2025 |
| ASUSTek       | X510UNR                     | Notebook    | [c9a50e1f5a](https://linux-hardware.org/?probe=c9a50e1f5a) | Mar 30, 2025 |
| ARCELIK       | GNB-1588-B1-i5              | Notebook    | [1b19775501](https://linux-hardware.org/?probe=1b19775501) | Mar 30, 2025 |
| ASUSTek       | K501UX                      | Notebook    | [1d308a03fd](https://linux-hardware.org/?probe=1d308a03fd) | Mar 30, 2025 |
| ASUSTek       | K501UX                      | Notebook    | [444796679b](https://linux-hardware.org/?probe=444796679b) | Mar 29, 2025 |
| Unknown       | Unknown                     | Desktop     | [125fd5297f](https://linux-hardware.org/?probe=125fd5297f) | Mar 29, 2025 |
| ARCELIK       | GNB-1588-B1-i5              | Notebook    | [c52da7acdb](https://linux-hardware.org/?probe=c52da7acdb) | Mar 29, 2025 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [9195d41e65](https://linux-hardware.org/?probe=9195d41e65) | Mar 29, 2025 |
| Monster       | ABRA A7 V10.1               | Notebook    | [d1c2063d73](https://linux-hardware.org/?probe=d1c2063d73) | Mar 29, 2025 |
| ASRock        | X670E Taichi                | Desktop     | [f87695ba72](https://linux-hardware.org/?probe=f87695ba72) | Mar 29, 2025 |
| HP            | 250 G5 Notebook PC          | Notebook    | [4d3f359ef4](https://linux-hardware.org/?probe=4d3f359ef4) | Mar 28, 2025 |
| Gigabyte      | B650M S2H                   | Desktop     | [d610395bb7](https://linux-hardware.org/?probe=d610395bb7) | Mar 28, 2025 |
| Lenovo        | LOQ 15IAX9 83GS             | Notebook    | [2ba04d571f](https://linux-hardware.org/?probe=2ba04d571f) | Mar 27, 2025 |
| Casper        | EXCALIBUR G870              | Notebook    | [1e2573d1cb](https://linux-hardware.org/?probe=1e2573d1cb) | Mar 27, 2025 |
| Monster       | ABRA A7 V10.1               | Notebook    | [d027243c91](https://linux-hardware.org/?probe=d027243c91) | Mar 27, 2025 |
| ARCELIK       | GNB-1588-B1-i5              | Notebook    | [199851ca5a](https://linux-hardware.org/?probe=199851ca5a) | Mar 27, 2025 |
| Samsung       | 370R4E/370R4V/370R5E/357... | Notebook    | [87adfa4979](https://linux-hardware.org/?probe=87adfa4979) | Mar 24, 2025 |
| ASUSTek       | K46CB                       | Notebook    | [0a773409e8](https://linux-hardware.org/?probe=0a773409e8) | Mar 24, 2025 |
| Lenovo        | ThinkPad P15v Gen 1 20TR... | Notebook    | [6be3f1f990](https://linux-hardware.org/?probe=6be3f1f990) | Mar 24, 2025 |
| Lenovo        | ThinkPad P15v Gen 1 20TR... | Notebook    | [bb83286b03](https://linux-hardware.org/?probe=bb83286b03) | Mar 24, 2025 |
| Acer          | Calpella                    | Notebook    | [e194a16f22](https://linux-hardware.org/?probe=e194a16f22) | Mar 23, 2025 |
| Lenovo        | ThinkPad E580 20KTS0TF00    | Notebook    | [96fc1950df](https://linux-hardware.org/?probe=96fc1950df) | Mar 23, 2025 |
| Lenovo        | ThinkPad E580 20KTS0TF00    | Notebook    | [b7820d12f4](https://linux-hardware.org/?probe=b7820d12f4) | Mar 23, 2025 |
| MSI           | PRO B760M-P                 | Desktop     | [c3864b5ed5](https://linux-hardware.org/?probe=c3864b5ed5) | Mar 20, 2025 |
| Unknown       | Unknown                     | Desktop     | [3ebcac7a95](https://linux-hardware.org/?probe=3ebcac7a95) | Mar 20, 2025 |
| Casper        | EXCALIBUR G870              | Notebook    | [1f733b1c53](https://linux-hardware.org/?probe=1f733b1c53) | Mar 20, 2025 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [1bf529b490](https://linux-hardware.org/?probe=1bf529b490) | Mar 19, 2025 |
| ASUSTek       | ROG Flow X13 GV301RC_GV3... | Convertible | [d5cb85a6e0](https://linux-hardware.org/?probe=d5cb85a6e0) | Mar 19, 2025 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [381ae3007d](https://linux-hardware.org/?probe=381ae3007d) | Mar 18, 2025 |
| Lenovo        | ThinkPad T430 2349PT4       | Notebook    | [99b95960c7](https://linux-hardware.org/?probe=99b95960c7) | Mar 18, 2025 |
| Dell          | Inspiron N5010              | Notebook    | [7d060d7f7f](https://linux-hardware.org/?probe=7d060d7f7f) | Mar 18, 2025 |
| Acer          | Nitro ANV15-41              | Notebook    | [782f625c46](https://linux-hardware.org/?probe=782f625c46) | Mar 17, 2025 |
| Toshiba       | Satellite C55-A-1K6         | Notebook    | [4d818ed2ce](https://linux-hardware.org/?probe=4d818ed2ce) | Mar 16, 2025 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [c769d20325](https://linux-hardware.org/?probe=c769d20325) | Mar 16, 2025 |
| Lenovo        | ThinkPad T480 20L6S68A00    | Notebook    | [f0340dd822](https://linux-hardware.org/?probe=f0340dd822) | Mar 16, 2025 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [b1fb071067](https://linux-hardware.org/?probe=b1fb071067) | Mar 15, 2025 |
| HP            | Pavilion g6                 | Notebook    | [b162609d91](https://linux-hardware.org/?probe=b162609d91) | Mar 15, 2025 |
| HP            | Elite x2 G4                 | Tablet      | [56cc28fa4c](https://linux-hardware.org/?probe=56cc28fa4c) | Mar 15, 2025 |
| Acer          | Ferrari One 200             | Notebook    | [9aeee2a283](https://linux-hardware.org/?probe=9aeee2a283) | Mar 14, 2025 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [1b6e810647](https://linux-hardware.org/?probe=1b6e810647) | Mar 13, 2025 |
| MSI           | GF65 Thin 10UE              | Notebook    | [c6ddb69393](https://linux-hardware.org/?probe=c6ddb69393) | Mar 13, 2025 |
| ASUSTek       | H81M-K                      | Desktop     | [b32cd64476](https://linux-hardware.org/?probe=b32cd64476) | Mar 13, 2025 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [706ff1cd50](https://linux-hardware.org/?probe=706ff1cd50) | Mar 13, 2025 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [3004dec8b2](https://linux-hardware.org/?probe=3004dec8b2) | Mar 12, 2025 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [731bb59cef](https://linux-hardware.org/?probe=731bb59cef) | Mar 11, 2025 |
| Lenovo        | ThinkPad T480 20L6S0WY00    | Notebook    | [a2f152c028](https://linux-hardware.org/?probe=a2f152c028) | Mar 10, 2025 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [e42a199558](https://linux-hardware.org/?probe=e42a199558) | Mar 10, 2025 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [cfddadf155](https://linux-hardware.org/?probe=cfddadf155) | Mar 10, 2025 |
| Apple         | Mac-F2268DC8                | All in one  | [c694177185](https://linux-hardware.org/?probe=c694177185) | Mar 09, 2025 |
| Casper        | NIRVANA NOTEBOOK            | Notebook    | [8e7a779f73](https://linux-hardware.org/?probe=8e7a779f73) | Mar 09, 2025 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [538f730a90](https://linux-hardware.org/?probe=538f730a90) | Mar 09, 2025 |
| Dell          | Inspiron 3593               | Notebook    | [100c1a44fc](https://linux-hardware.org/?probe=100c1a44fc) | Mar 09, 2025 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Notebook    | [9e9d239d38](https://linux-hardware.org/?probe=9e9d239d38) | Mar 09, 2025 |
| Gigabyte      | Z87X-UD5H-CF                | Desktop     | [d47459e306](https://linux-hardware.org/?probe=d47459e306) | Mar 08, 2025 |
| Lenovo        | 375C No DPK                 | All in one  | [27e9cb5651](https://linux-hardware.org/?probe=27e9cb5651) | Mar 08, 2025 |
| Gigabyte      | B85M-HD3                    | Desktop     | [22203d9e7d](https://linux-hardware.org/?probe=22203d9e7d) | Mar 08, 2025 |
| Lenovo        | ThinkPad E580 20KTS0TF00    | Notebook    | [26a3e369f8](https://linux-hardware.org/?probe=26a3e369f8) | Mar 07, 2025 |
| Gigabyte      | B75M-D2V                    | Desktop     | [349e0d09bb](https://linux-hardware.org/?probe=349e0d09bb) | Mar 07, 2025 |
| ASUSTek       | P8Z77-V DELUXE              | Desktop     | [892c60d831](https://linux-hardware.org/?probe=892c60d831) | Mar 07, 2025 |
| HP            | OMEN by Laptop              | Notebook    | [62ec362c9e](https://linux-hardware.org/?probe=62ec362c9e) | Mar 07, 2025 |
| HP            | OMEN by Laptop              | Notebook    | [88e4bd362c](https://linux-hardware.org/?probe=88e4bd362c) | Mar 07, 2025 |
| HP            | Elite x2 G4                 | Tablet      | [b1351bf5fe](https://linux-hardware.org/?probe=b1351bf5fe) | Mar 06, 2025 |
| MAINBRD       | OPS62A-SHB                  | Desktop     | [5ec6af15b8](https://linux-hardware.org/?probe=5ec6af15b8) | Mar 06, 2025 |
| ASUSTek       | ROG Zephyrus G16 GU603ZU... | Notebook    | [43c30dd25c](https://linux-hardware.org/?probe=43c30dd25c) | Mar 06, 2025 |
| ASUSTek       | ProArt X870E-CREATOR WIF... | Desktop     | [6d487c988f](https://linux-hardware.org/?probe=6d487c988f) | Mar 05, 2025 |
| GMKtec        | NucBox K11                  | Desktop     | [5903756b61](https://linux-hardware.org/?probe=5903756b61) | Mar 05, 2025 |
| Lenovo        | ThinkBook 16p Gen 4 21J8    | Notebook    | [9e079d6752](https://linux-hardware.org/?probe=9e079d6752) | Mar 05, 2025 |
| Lenovo        | ThinkBook 16p Gen 4 21J8    | Notebook    | [11e5772582](https://linux-hardware.org/?probe=11e5772582) | Mar 05, 2025 |
| MSI           | B450M-A PRO MAX             | Desktop     | [8134eb75ab](https://linux-hardware.org/?probe=8134eb75ab) | Mar 05, 2025 |
| ASUSTek       | TUF Gaming X870-PLUS WIF... | Desktop     | [5bbdad4c70](https://linux-hardware.org/?probe=5bbdad4c70) | Mar 05, 2025 |
| HUAWEI        | FLMH-XX                     | Notebook    | [3646772545](https://linux-hardware.org/?probe=3646772545) | Mar 04, 2025 |
| Lenovo        | ThinkBook 16p Gen 4 21J8    | Notebook    | [3dfc7c3829](https://linux-hardware.org/?probe=3dfc7c3829) | Mar 03, 2025 |
| ASUSTek       | ROG Maximus Z790 DARK HE... | Desktop     | [87214358f3](https://linux-hardware.org/?probe=87214358f3) | Mar 03, 2025 |
| HUAWEI        | CREFG-XX                    | Notebook    | [92139ed270](https://linux-hardware.org/?probe=92139ed270) | Mar 02, 2025 |
| Lenovo        | 375C No DPK                 | All in one  | [d945d6ce78](https://linux-hardware.org/?probe=d945d6ce78) | Mar 02, 2025 |
| Intel         | SHARKBAY                    | Desktop     | [819813c871](https://linux-hardware.org/?probe=819813c871) | Mar 02, 2025 |
| MSI           | B650 GAMING PLUS WIFI       | Desktop     | [d71aaad27a](https://linux-hardware.org/?probe=d71aaad27a) | Mar 02, 2025 |
| Casper        | EXCALIBUR G770              | Notebook    | [7b24d2d82e](https://linux-hardware.org/?probe=7b24d2d82e) | Mar 02, 2025 |
| Casper        | EXCALIBUR G770              | Notebook    | [537ad250d2](https://linux-hardware.org/?probe=537ad250d2) | Mar 02, 2025 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [8202d0cfc3](https://linux-hardware.org/?probe=8202d0cfc3) | Mar 02, 2025 |
| Casper        | EXCALIBUR G770              | Notebook    | [a06c479d70](https://linux-hardware.org/?probe=a06c479d70) | Mar 02, 2025 |
| Intel         | SHARKBAY                    | Desktop     | [722d11e47d](https://linux-hardware.org/?probe=722d11e47d) | Mar 02, 2025 |
| ASUSTek       | TUF Gaming B760M-PLUS D4    | Desktop     | [e58ca983be](https://linux-hardware.org/?probe=e58ca983be) | Mar 02, 2025 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [4af11729c4](https://linux-hardware.org/?probe=4af11729c4) | Mar 01, 2025 |
| MSI           | MAG X870 TOMAHAWK WIFI      | Desktop     | [a56069a713](https://linux-hardware.org/?probe=a56069a713) | Mar 01, 2025 |
| Gigabyte      | X79-UD3                     | Desktop     | [16937e6517](https://linux-hardware.org/?probe=16937e6517) | Feb 28, 2025 |
| ASUSTek       | ROG Maximus XI EXTREME      | Desktop     | [611564e25c](https://linux-hardware.org/?probe=611564e25c) | Feb 28, 2025 |
| MSI           | B650 GAMING PLUS WIFI       | Desktop     | [ea67c70d16](https://linux-hardware.org/?probe=ea67c70d16) | Feb 27, 2025 |
| HP            | Pavilion g6                 | Notebook    | [76a4ff1b4f](https://linux-hardware.org/?probe=76a4ff1b4f) | Feb 27, 2025 |
| Apple         | MacBookPro8,1               | Notebook    | [13e97ec200](https://linux-hardware.org/?probe=13e97ec200) | Feb 27, 2025 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | Notebook    | [50cb965e43](https://linux-hardware.org/?probe=50cb965e43) | Feb 27, 2025 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [f810c98a11](https://linux-hardware.org/?probe=f810c98a11) | Feb 26, 2025 |
| Valve         | Jupiter                     | Notebook    | [80f77d6f3b](https://linux-hardware.org/?probe=80f77d6f3b) | Feb 26, 2025 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [7f6f8c8f46](https://linux-hardware.org/?probe=7f6f8c8f46) | Feb 25, 2025 |
| Apple         | MacBookAir6,2               | Notebook    | [0b89ed35c9](https://linux-hardware.org/?probe=0b89ed35c9) | Feb 25, 2025 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [ce37f11300](https://linux-hardware.org/?probe=ce37f11300) | Feb 25, 2025 |
| ASUSTek       | TUF Gaming B760M-PLUS D4    | Desktop     | [21dd2b0a9b](https://linux-hardware.org/?probe=21dd2b0a9b) | Feb 24, 2025 |
| Apple         | MacBookPro8,1               | Notebook    | [5555382fbe](https://linux-hardware.org/?probe=5555382fbe) | Feb 24, 2025 |
| ASUSTek       | X550CL                      | Notebook    | [3755503132](https://linux-hardware.org/?probe=3755503132) | Feb 24, 2025 |
| HUAWEI        | FLMH-XX                     | Notebook    | [4f4992c88d](https://linux-hardware.org/?probe=4f4992c88d) | Feb 23, 2025 |
| ASUSTek       | X550LC                      | Notebook    | [f72cbfee1d](https://linux-hardware.org/?probe=f72cbfee1d) | Feb 23, 2025 |
| Onda TLC      | Oliver Book A1              | Tablet      | [ba565faa60](https://linux-hardware.org/?probe=ba565faa60) | Feb 23, 2025 |
| ASUSTek       | X550LC                      | Notebook    | [4982c6c8d6](https://linux-hardware.org/?probe=4982c6c8d6) | Feb 22, 2025 |
| MSI           | PRO Z890-P WIFI             | Desktop     | [5bd893af26](https://linux-hardware.org/?probe=5bd893af26) | Feb 22, 2025 |
| Lenovo        | ThinkPad X220 4291HV9       | Notebook    | [5471d58b55](https://linux-hardware.org/?probe=5471d58b55) | Feb 22, 2025 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [5f404da84d](https://linux-hardware.org/?probe=5f404da84d) | Feb 21, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [931b879597](https://linux-hardware.org/?probe=931b879597) | Feb 21, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [04577f1532](https://linux-hardware.org/?probe=04577f1532) | Feb 21, 2025 |
| Monster       | ABRA A5 V15.8               | Notebook    | [a3f9dc7b6c](https://linux-hardware.org/?probe=a3f9dc7b6c) | Feb 21, 2025 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [fdd6a55c90](https://linux-hardware.org/?probe=fdd6a55c90) | Feb 21, 2025 |
| Gigabyte      | GA-MA790XT-UD4P             | Desktop     | [fbb8a2ae6c](https://linux-hardware.org/?probe=fbb8a2ae6c) | Feb 20, 2025 |
| Lenovo        | ThinkPad E16 Gen 1 21JT0... | Notebook    | [f865637c55](https://linux-hardware.org/?probe=f865637c55) | Feb 20, 2025 |
| MSI           | PRO Z690-A WIFI             | Desktop     | [d7ecdd4d9a](https://linux-hardware.org/?probe=d7ecdd4d9a) | Feb 20, 2025 |
| ASRock        | X670E Steel Legend          | Desktop     | [c18d9c30eb](https://linux-hardware.org/?probe=c18d9c30eb) | Feb 20, 2025 |
| Lenovo        | V570c HuronRiver Platfor... | Notebook    | [7a71ad4ed0](https://linux-hardware.org/?probe=7a71ad4ed0) | Feb 20, 2025 |
| Unknown       | G41 Series V01              | Desktop     | [a1a54ded71](https://linux-hardware.org/?probe=a1a54ded71) | Feb 19, 2025 |
| Lenovo        | ThinkPad X220 4291HV9       | Notebook    | [a04a616b98](https://linux-hardware.org/?probe=a04a616b98) | Feb 19, 2025 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [951c55f19d](https://linux-hardware.org/?probe=951c55f19d) | Feb 18, 2025 |
| Unknown       | Marble based on Qualcomm... | Phone       | [be7e8b834b](https://linux-hardware.org/?probe=be7e8b834b) | Feb 18, 2025 |
| Acer          | AO722                       | Notebook    | [c5a1201b22](https://linux-hardware.org/?probe=c5a1201b22) | Feb 18, 2025 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [7b4a110d8e](https://linux-hardware.org/?probe=7b4a110d8e) | Feb 17, 2025 |
| ASUSTek       | EX-A320M-GAMING             | Desktop     | [fcd6374c7b](https://linux-hardware.org/?probe=fcd6374c7b) | Feb 17, 2025 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [8a1197d5c9](https://linux-hardware.org/?probe=8a1197d5c9) | Feb 17, 2025 |
| ASRock        | 970A-G                      | Desktop     | [434da8ebf1](https://linux-hardware.org/?probe=434da8ebf1) | Feb 16, 2025 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [0e6b3571c3](https://linux-hardware.org/?probe=0e6b3571c3) | Feb 15, 2025 |
| Casper        | NIRVANA NOTEBOOK            | Notebook    | [f3203136f7](https://linux-hardware.org/?probe=f3203136f7) | Feb 15, 2025 |
| HP            | 250 G3                      | Notebook    | [e1d978a448](https://linux-hardware.org/?probe=e1d978a448) | Feb 14, 2025 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [905c3ed126](https://linux-hardware.org/?probe=905c3ed126) | Feb 14, 2025 |
| Hometech      | Alfa 620C                   | Notebook    | [ad4cd357d1](https://linux-hardware.org/?probe=ad4cd357d1) | Feb 14, 2025 |
| Hometech      | Alfa 620C                   | Notebook    | [38c1364e8f](https://linux-hardware.org/?probe=38c1364e8f) | Feb 14, 2025 |
| Apple         | MacBookAir7,2               | Notebook    | [f635824b33](https://linux-hardware.org/?probe=f635824b33) | Feb 13, 2025 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [3f586d5a5d](https://linux-hardware.org/?probe=3f586d5a5d) | Feb 12, 2025 |
| Apple         | Mac-F2218FC8                | All in one  | [f4e676e80e](https://linux-hardware.org/?probe=f4e676e80e) | Feb 11, 2025 |
| ASUSTek       | M52AD_M12AD                 | Desktop     | [cd7b3c2640](https://linux-hardware.org/?probe=cd7b3c2640) | Feb 10, 2025 |
| Dell          | G15 5520                    | Notebook    | [ec11d45482](https://linux-hardware.org/?probe=ec11d45482) | Feb 10, 2025 |
| Apple         | Mac-F2218FC8                | All in one  | [f77c51d639](https://linux-hardware.org/?probe=f77c51d639) | Feb 10, 2025 |
| Lenovo        | IdeaPad Y550 20017          | Notebook    | [2b0beedcb0](https://linux-hardware.org/?probe=2b0beedcb0) | Feb 10, 2025 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [eddfd0cd23](https://linux-hardware.org/?probe=eddfd0cd23) | Feb 09, 2025 |
| RuggedPC      | RuggedBookJ87               | Tablet      | [5bf067ffce](https://linux-hardware.org/?probe=5bf067ffce) | Feb 09, 2025 |
| Monster       | ABRA A7 V12.2               | Notebook    | [a0e7f30790](https://linux-hardware.org/?probe=a0e7f30790) | Feb 09, 2025 |
| ASUSTek       | X555LB                      | Notebook    | [29f18ad997](https://linux-hardware.org/?probe=29f18ad997) | Feb 09, 2025 |
| Gigabyte      | Z170M-D3H-CF                | Desktop     | [34f4ae5f88](https://linux-hardware.org/?probe=34f4ae5f88) | Feb 08, 2025 |
| HUAWEI        | VGHH-XX                     | Notebook    | [800d04cd49](https://linux-hardware.org/?probe=800d04cd49) | Feb 08, 2025 |
| HUAWEI        | VGHH-XX                     | Notebook    | [837fcffb87](https://linux-hardware.org/?probe=837fcffb87) | Feb 07, 2025 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [1f6e233f27](https://linux-hardware.org/?probe=1f6e233f27) | Feb 07, 2025 |
| Acer          | Aspire 5755G                | Notebook    | [99ea4fe230](https://linux-hardware.org/?probe=99ea4fe230) | Feb 06, 2025 |
| Samsung       | R520/R522/R620              | Notebook    | [1c6b4e83d9](https://linux-hardware.org/?probe=1c6b4e83d9) | Feb 06, 2025 |
| MSI           | B450M-A PRO MAX             | Desktop     | [c18ee18ea4](https://linux-hardware.org/?probe=c18ee18ea4) | Feb 06, 2025 |
| ASUSTek       | H61M-K                      | Desktop     | [8cad886eca](https://linux-hardware.org/?probe=8cad886eca) | Feb 06, 2025 |
| ASUSTek       | N61Vn                       | Notebook    | [2487e567df](https://linux-hardware.org/?probe=2487e567df) | Feb 05, 2025 |
| Acer          | Nitro AN515-45              | Notebook    | [b31af9a956](https://linux-hardware.org/?probe=b31af9a956) | Feb 05, 2025 |
| Monster       | ABRA A5 V16.7               | Notebook    | [26edb951fe](https://linux-hardware.org/?probe=26edb951fe) | Feb 04, 2025 |
| Gigabyte      | A620M H                     | Desktop     | [8f87c491ff](https://linux-hardware.org/?probe=8f87c491ff) | Feb 04, 2025 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [d3bcfe59e7](https://linux-hardware.org/?probe=d3bcfe59e7) | Feb 02, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [40bdcb3757](https://linux-hardware.org/?probe=40bdcb3757) | Feb 02, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [d4447bb3a3](https://linux-hardware.org/?probe=d4447bb3a3) | Feb 02, 2025 |
| Lenovo        | Y50-70 20378                | Notebook    | [c664e6cafa](https://linux-hardware.org/?probe=c664e6cafa) | Feb 01, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [a520ee300b](https://linux-hardware.org/?probe=a520ee300b) | Feb 01, 2025 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [f12eccf445](https://linux-hardware.org/?probe=f12eccf445) | Jan 31, 2025 |
| Acer          | Aspire VN7-791G             | Notebook    | [c0d1a1ba04](https://linux-hardware.org/?probe=c0d1a1ba04) | Jan 31, 2025 |
| Lenovo        | ThinkPad X260 20F5S16B00    | Notebook    | [7363aa9d73](https://linux-hardware.org/?probe=7363aa9d73) | Jan 31, 2025 |
| Lenovo        | ThinkPad T480 20L6S68A00    | Notebook    | [68a4aae115](https://linux-hardware.org/?probe=68a4aae115) | Jan 30, 2025 |
| HUAWEI        | BoDE-WXX9                   | Notebook    | [aa9c1c8ee0](https://linux-hardware.org/?probe=aa9c1c8ee0) | Jan 30, 2025 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [976cc66d10](https://linux-hardware.org/?probe=976cc66d10) | Jan 29, 2025 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [715f207111](https://linux-hardware.org/?probe=715f207111) | Jan 28, 2025 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [be1c363e10](https://linux-hardware.org/?probe=be1c363e10) | Jan 28, 2025 |
| Gigabyte      | H97M-D3H                    | Desktop     | [036578e935](https://linux-hardware.org/?probe=036578e935) | Jan 28, 2025 |
| Lenovo        | ThinkPad X260 20F5S16B00    | Notebook    | [373531f46c](https://linux-hardware.org/?probe=373531f46c) | Jan 28, 2025 |
| ASUSTek       | ROG Zephyrus G16 GU603ZU... | Notebook    | [c12dc27099](https://linux-hardware.org/?probe=c12dc27099) | Jan 28, 2025 |
| MSI           | B550-A PRO                  | Desktop     | [2f543471d8](https://linux-hardware.org/?probe=2f543471d8) | Jan 27, 2025 |
| Lenovo        | ThinkPad T480 20L6S68A00    | Notebook    | [7295603105](https://linux-hardware.org/?probe=7295603105) | Jan 27, 2025 |
| Lenovo        | V15 G4 AMN 82YU             | Notebook    | [389dbca48e](https://linux-hardware.org/?probe=389dbca48e) | Jan 27, 2025 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [ded7a5ced8](https://linux-hardware.org/?probe=ded7a5ced8) | Jan 27, 2025 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [33f36708c5](https://linux-hardware.org/?probe=33f36708c5) | Jan 26, 2025 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | Notebook    | [0ef3c28441](https://linux-hardware.org/?probe=0ef3c28441) | Jan 25, 2025 |
| Lenovo        | ThinkPad T480 20L6S68A00    | Notebook    | [0c50e7e1f6](https://linux-hardware.org/?probe=0c50e7e1f6) | Jan 25, 2025 |
| Lenovo        | LOQ 15AHP9 83DX             | Notebook    | [bcccc1b212](https://linux-hardware.org/?probe=bcccc1b212) | Jan 25, 2025 |
| Casper        | EXCALIBUR G770              | Notebook    | [ae65306323](https://linux-hardware.org/?probe=ae65306323) | Jan 25, 2025 |
| Lenovo        | ThinkPad X1 Tablet Gen 3... | Tablet      | [a427baa9c0](https://linux-hardware.org/?probe=a427baa9c0) | Jan 24, 2025 |
| Apple         | MacBookPro8,2               | Notebook    | [81558eb009](https://linux-hardware.org/?probe=81558eb009) | Jan 23, 2025 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2cf6e5fe6a](https://linux-hardware.org/?probe=2cf6e5fe6a) | Jan 23, 2025 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [f31c9c868b](https://linux-hardware.org/?probe=f31c9c868b) | Jan 20, 2025 |
| HUAWEI        | FLMH-XX                     | Notebook    | [1e3b69453f](https://linux-hardware.org/?probe=1e3b69453f) | Jan 18, 2025 |
| HUAWEI        | FLMH-XX                     | Notebook    | [e3157a5acc](https://linux-hardware.org/?probe=e3157a5acc) | Jan 18, 2025 |
| Acer          | Nitro AN16-41               | Notebook    | [1f5e5feecf](https://linux-hardware.org/?probe=1f5e5feecf) | Jan 18, 2025 |
| Acer          | Nitro AN16-41               | Notebook    | [4a6f90151d](https://linux-hardware.org/?probe=4a6f90151d) | Jan 18, 2025 |
| MSI           | MPG X670E CARBON WIFI       | Desktop     | [0143964e95](https://linux-hardware.org/?probe=0143964e95) | Jan 18, 2025 |
| Chatreey      | AC1-DP                      | Desktop     | [f14df3e83a](https://linux-hardware.org/?probe=f14df3e83a) | Jan 17, 2025 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [4796c5f829](https://linux-hardware.org/?probe=4796c5f829) | Jan 17, 2025 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [178a924ec9](https://linux-hardware.org/?probe=178a924ec9) | Jan 17, 2025 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [b0bbf473ef](https://linux-hardware.org/?probe=b0bbf473ef) | Jan 16, 2025 |
| Gigabyte      | Z87X-UD5H-CF                | Desktop     | [5724971c17](https://linux-hardware.org/?probe=5724971c17) | Jan 15, 2025 |
| Gigabyte      | Z87X-UD5H-CF                | Desktop     | [ae47dc0b12](https://linux-hardware.org/?probe=ae47dc0b12) | Jan 15, 2025 |
| Apple         | MacBookPro8,1               | Notebook    | [88ec79f700](https://linux-hardware.org/?probe=88ec79f700) | Jan 15, 2025 |
| Lenovo        | ThinkPad E580 20KTS0TF00    | Notebook    | [b95f6420e0](https://linux-hardware.org/?probe=b95f6420e0) | Jan 14, 2025 |
| Apple         | MacBookPro8,1               | Notebook    | [81751d437c](https://linux-hardware.org/?probe=81751d437c) | Jan 14, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [11cc273c03](https://linux-hardware.org/?probe=11cc273c03) | Jan 14, 2025 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [ff909bbac5](https://linux-hardware.org/?probe=ff909bbac5) | Jan 13, 2025 |
| ASUSTek       | N56VZ                       | Notebook    | [166da4b0da](https://linux-hardware.org/?probe=166da4b0da) | Jan 13, 2025 |
| Dell          | Latitude E6320              | Notebook    | [9978ca794a](https://linux-hardware.org/?probe=9978ca794a) | Jan 13, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [d32ffbf564](https://linux-hardware.org/?probe=d32ffbf564) | Jan 12, 2025 |
| ASUSTek       | ROG Zephyrus G16 GU603ZU... | Notebook    | [bb11d216fc](https://linux-hardware.org/?probe=bb11d216fc) | Jan 12, 2025 |
| Phoenix/Si... | W760SUN                     | Notebook    | [dcc968ec3d](https://linux-hardware.org/?probe=dcc968ec3d) | Jan 12, 2025 |
| Phoenix/Si... | W760SUN                     | Notebook    | [6078aaffbc](https://linux-hardware.org/?probe=6078aaffbc) | Jan 12, 2025 |
| Casper        | EXCALIBUR G900              | Notebook    | [b15f0f6877](https://linux-hardware.org/?probe=b15f0f6877) | Jan 11, 2025 |
| Chatreey      | AC1-DP                      | Desktop     | [68a2c044bd](https://linux-hardware.org/?probe=68a2c044bd) | Jan 11, 2025 |
| MSI           | Unknown                     | Notebook    | [680e38dd59](https://linux-hardware.org/?probe=680e38dd59) | Jan 09, 2025 |
| Dell          | Latitude 7440               | Convertible | [ddab5c09eb](https://linux-hardware.org/?probe=ddab5c09eb) | Jan 06, 2025 |
| Dell          | Latitude 7440               | Convertible | [120544533c](https://linux-hardware.org/?probe=120544533c) | Jan 06, 2025 |
| MSI           | A520M-A PRO                 | Desktop     | [17c782de89](https://linux-hardware.org/?probe=17c782de89) | Jan 05, 2025 |
| Packard Be... | EasyNote TJ65               | Notebook    | [ef9f9ac2c6](https://linux-hardware.org/?probe=ef9f9ac2c6) | Jan 05, 2025 |
| Gigabyte      | A520M K                     | Desktop     | [b725853875](https://linux-hardware.org/?probe=b725853875) | Jan 05, 2025 |
| Lenovo        | ThinkPad E580 20KTS0TF00    | Notebook    | [220c6d82f3](https://linux-hardware.org/?probe=220c6d82f3) | Jan 05, 2025 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [5ef06b7cbe](https://linux-hardware.org/?probe=5ef06b7cbe) | Jan 04, 2025 |
| MSI           | B450-A PRO MAX              | Desktop     | [c9cf4100bb](https://linux-hardware.org/?probe=c9cf4100bb) | Jan 04, 2025 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [cf7d50fae1](https://linux-hardware.org/?probe=cf7d50fae1) | Jan 04, 2025 |
| ASUSTek       | X75VC                       | Notebook    | [5acc8324b3](https://linux-hardware.org/?probe=5acc8324b3) | Jan 04, 2025 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [062f7792dc](https://linux-hardware.org/?probe=062f7792dc) | Jan 03, 2025 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [a671d43d86](https://linux-hardware.org/?probe=a671d43d86) | Jan 03, 2025 |
| Casper        | EXCALIBUR G770              | Notebook    | [1f3dee2cf2](https://linux-hardware.org/?probe=1f3dee2cf2) | Jan 02, 2025 |
| Unknown       | X99-D3                      | Desktop     | [d79cb549a8](https://linux-hardware.org/?probe=d79cb549a8) | Jan 01, 2025 |
| Samsung       | Galaxy E7                   | Notebook    | [cc5d3b18cd](https://linux-hardware.org/?probe=cc5d3b18cd) | Jan 01, 2025 |
| Samsung       | Galaxy E7                   | Notebook    | [379cf72f84](https://linux-hardware.org/?probe=379cf72f84) | Jan 01, 2025 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [17c5dac30c](https://linux-hardware.org/?probe=17c5dac30c) | Jan 01, 2025 |
| Apple         | MacBookPro12,1              | Notebook    | [1340d405bf](https://linux-hardware.org/?probe=1340d405bf) | Jan 01, 2025 |
| Lenovo        | ThinkPad X1 Carbon 34484... | Notebook    | [3fc4858681](https://linux-hardware.org/?probe=3fc4858681) | Jan 01, 2025 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [d825d2369b](https://linux-hardware.org/?probe=d825d2369b) | Dec 31, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [9dd96b42dd](https://linux-hardware.org/?probe=9dd96b42dd) | Dec 31, 2024 |
| Lenovo        | ThinkPad E580 20KTS0TF00    | Notebook    | [3ca3276427](https://linux-hardware.org/?probe=3ca3276427) | Dec 29, 2024 |
| Clevo         | W240HU/W250HUQ              | Notebook    | [fa4538a983](https://linux-hardware.org/?probe=fa4538a983) | Dec 29, 2024 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [94c62e3b8b](https://linux-hardware.org/?probe=94c62e3b8b) | Dec 29, 2024 |
| ASUSTek       | ZenBook UX334FLC_UX334FL    | Notebook    | [648c9b7e5f](https://linux-hardware.org/?probe=648c9b7e5f) | Dec 28, 2024 |
| Lenovo        | ThinkBook 16 G6 IRL 21KH    | Notebook    | [caa200d745](https://linux-hardware.org/?probe=caa200d745) | Dec 28, 2024 |
| Toshiba       | Satellite P300              | Notebook    | [3174fc3f7e](https://linux-hardware.org/?probe=3174fc3f7e) | Dec 27, 2024 |
| Monster       | ABRA A5 V17.3               | Notebook    | [8ac82ca045](https://linux-hardware.org/?probe=8ac82ca045) | Dec 27, 2024 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [9f0e63713d](https://linux-hardware.org/?probe=9f0e63713d) | Dec 27, 2024 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [dadb3385a3](https://linux-hardware.org/?probe=dadb3385a3) | Dec 26, 2024 |
| Acer          | Aspire VN7-791G             | Notebook    | [89b69495ff](https://linux-hardware.org/?probe=89b69495ff) | Dec 26, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [43e4a1a3d5](https://linux-hardware.org/?probe=43e4a1a3d5) | Dec 26, 2024 |
| MSI           | PRO B760-P WIFI DDR4        | Desktop     | [d7ca54538f](https://linux-hardware.org/?probe=d7ca54538f) | Dec 26, 2024 |
| MSI           | Katana A17 AI B8VE          | Notebook    | [06e816e082](https://linux-hardware.org/?probe=06e816e082) | Dec 26, 2024 |
| Lenovo        | V15 G3 ABA 82TV             | Notebook    | [75b2764000](https://linux-hardware.org/?probe=75b2764000) | Dec 25, 2024 |
| Monster       | ABRA A7 V11.2               | Notebook    | [762b2b2071](https://linux-hardware.org/?probe=762b2b2071) | Dec 25, 2024 |
| Clevo         | W240HU/W250HUQ              | Notebook    | [a2f67a9324](https://linux-hardware.org/?probe=a2f67a9324) | Dec 25, 2024 |
| Clevo         | W240HU/W250HUQ              | Notebook    | [a81e88cd1b](https://linux-hardware.org/?probe=a81e88cd1b) | Dec 25, 2024 |
| Apple         | Mac-F2268DC8                | All in one  | [e82b0c22fb](https://linux-hardware.org/?probe=e82b0c22fb) | Dec 24, 2024 |
| Clevo         | W240HU/W250HUQ              | Notebook    | [7f63df74a6](https://linux-hardware.org/?probe=7f63df74a6) | Dec 24, 2024 |
| Dell          | G15 5530                    | Notebook    | [69f5776150](https://linux-hardware.org/?probe=69f5776150) | Dec 23, 2024 |
| Dell          | 0PRR48 A01                  | Desktop     | [282281a510](https://linux-hardware.org/?probe=282281a510) | Dec 23, 2024 |
| HUAWEI        | MCLF-XX                     | Notebook    | [e97a651e78](https://linux-hardware.org/?probe=e97a651e78) | Dec 23, 2024 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [683eb64afb](https://linux-hardware.org/?probe=683eb64afb) | Dec 23, 2024 |
| Acer          | Aspire ES1-571              | Notebook    | [cb4b9da83f](https://linux-hardware.org/?probe=cb4b9da83f) | Dec 22, 2024 |
| Acer          | Aspire ES1-571              | Notebook    | [48537b040b](https://linux-hardware.org/?probe=48537b040b) | Dec 22, 2024 |
| Dell          | Precision 7560              | Notebook    | [0181667d44](https://linux-hardware.org/?probe=0181667d44) | Dec 22, 2024 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [6e1325a330](https://linux-hardware.org/?probe=6e1325a330) | Dec 22, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [b800e65be6](https://linux-hardware.org/?probe=b800e65be6) | Dec 22, 2024 |
| MSI           | PRO B760-P WIFI DDR4        | Desktop     | [22cf181ba7](https://linux-hardware.org/?probe=22cf181ba7) | Dec 22, 2024 |
| ECS           | A55F-M3                     | Desktop     | [1d2df44dd7](https://linux-hardware.org/?probe=1d2df44dd7) | Dec 21, 2024 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [2bc9b23a42](https://linux-hardware.org/?probe=2bc9b23a42) | Dec 21, 2024 |
| Dell          | Latitude 7490               | Notebook    | [31661d6299](https://linux-hardware.org/?probe=31661d6299) | Dec 21, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [7acc8a5af8](https://linux-hardware.org/?probe=7acc8a5af8) | Dec 21, 2024 |
| Acer          | Aspire A315-59              | Notebook    | [f43ee3c3f3](https://linux-hardware.org/?probe=f43ee3c3f3) | Dec 20, 2024 |
| Dell          | Inspiron 5559               | Notebook    | [6946e661db](https://linux-hardware.org/?probe=6946e661db) | Dec 20, 2024 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | Notebook    | [06253e3ba7](https://linux-hardware.org/?probe=06253e3ba7) | Dec 19, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [f33a71984f](https://linux-hardware.org/?probe=f33a71984f) | Dec 19, 2024 |
| Samsung       | 905S3G/906S3G/915S3G        | Notebook    | [a31e7950da](https://linux-hardware.org/?probe=a31e7950da) | Dec 19, 2024 |
| Gigabyte      | B75M-D3V                    | Desktop     | [b49a48d194](https://linux-hardware.org/?probe=b49a48d194) | Dec 18, 2024 |
| Acer          | Aspire F5-573G              | Notebook    | [aa3a93dbc4](https://linux-hardware.org/?probe=aa3a93dbc4) | Dec 18, 2024 |
| Samsung       | 905S3G/906S3G/915S3G        | Notebook    | [8bdebb5383](https://linux-hardware.org/?probe=8bdebb5383) | Dec 17, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [ebc832d177](https://linux-hardware.org/?probe=ebc832d177) | Dec 16, 2024 |
| Unknown       | Marble based on Qualcomm... | Phone       | [7ffb0504d4](https://linux-hardware.org/?probe=7ffb0504d4) | Dec 16, 2024 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [a785db7994](https://linux-hardware.org/?probe=a785db7994) | Dec 15, 2024 |
| Lenovo        | LOQ 15IRH8 82XV             | Notebook    | [288edef8e9](https://linux-hardware.org/?probe=288edef8e9) | Dec 14, 2024 |
| ASUSTek       | K54HR                       | Notebook    | [b839a0b9cf](https://linux-hardware.org/?probe=b839a0b9cf) | Dec 14, 2024 |
| ASUSTek       | K54HR                       | Notebook    | [9d14a14655](https://linux-hardware.org/?probe=9d14a14655) | Dec 14, 2024 |
| Packard Be... | DOT S                       | Notebook    | [60865a1411](https://linux-hardware.org/?probe=60865a1411) | Dec 14, 2024 |
| Lenovo        | ThinkPad E580 20KTS0TF00    | Notebook    | [3b4adb5d69](https://linux-hardware.org/?probe=3b4adb5d69) | Dec 13, 2024 |
| HP            | 255 G8 Notebook PC          | Notebook    | [47a16bb755](https://linux-hardware.org/?probe=47a16bb755) | Dec 13, 2024 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [6ade667db2](https://linux-hardware.org/?probe=6ade667db2) | Dec 13, 2024 |
| ASUSTek       | TUF Gaming Z690-PLUS        | Desktop     | [d46d8a8dc1](https://linux-hardware.org/?probe=d46d8a8dc1) | Dec 13, 2024 |
| ASUSTek       | K53U                        | Notebook    | [0a501b8d76](https://linux-hardware.org/?probe=0a501b8d76) | Dec 12, 2024 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | Notebook    | [0913e12416](https://linux-hardware.org/?probe=0913e12416) | Dec 12, 2024 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [e5be77487d](https://linux-hardware.org/?probe=e5be77487d) | Dec 11, 2024 |
| Lenovo        | ThinkPad T480 20L6S68A00    | Notebook    | [562b867ec6](https://linux-hardware.org/?probe=562b867ec6) | Dec 11, 2024 |
| Lenovo        | ThinkPad P15v Gen 1 20TR... | Notebook    | [d050dbd2b8](https://linux-hardware.org/?probe=d050dbd2b8) | Dec 10, 2024 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | Notebook    | [88623ffcc4](https://linux-hardware.org/?probe=88623ffcc4) | Dec 10, 2024 |
| Foxconn       | 2A8C                        | Desktop     | [797e1376e3](https://linux-hardware.org/?probe=797e1376e3) | Dec 09, 2024 |
| Foxconn       | 2A8C                        | Desktop     | [27417acd19](https://linux-hardware.org/?probe=27417acd19) | Dec 09, 2024 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | Notebook    | [d0b421c346](https://linux-hardware.org/?probe=d0b421c346) | Dec 08, 2024 |
| HP            | ENVY Laptop 13-ba1xxx       | Notebook    | [01bb9bade5](https://linux-hardware.org/?probe=01bb9bade5) | Dec 08, 2024 |
| GPU Compan... | Reeder C19 Laptop           | Notebook    | [7e2382c556](https://linux-hardware.org/?probe=7e2382c556) | Dec 08, 2024 |
| GPU Compan... | Reeder C19 Laptop           | Notebook    | [fbef13b359](https://linux-hardware.org/?probe=fbef13b359) | Dec 08, 2024 |
| Dell          | Inspiron 3543               | Notebook    | [39ace45f52](https://linux-hardware.org/?probe=39ace45f52) | Dec 07, 2024 |
| Intel         | Unknown                     | Desktop     | [423e3be5d1](https://linux-hardware.org/?probe=423e3be5d1) | Dec 07, 2024 |
| ASUSTek       | TUF Gaming A620-PRO WIFI    | Desktop     | [19aa855f4d](https://linux-hardware.org/?probe=19aa855f4d) | Dec 07, 2024 |
| Gigabyte      | M68MT-S2                    | Desktop     | [2bad0fcf88](https://linux-hardware.org/?probe=2bad0fcf88) | Dec 06, 2024 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [79f63e6159](https://linux-hardware.org/?probe=79f63e6159) | Dec 06, 2024 |
| Gigabyte      | B550M DS3H                  | Desktop     | [512fa78824](https://linux-hardware.org/?probe=512fa78824) | Dec 05, 2024 |
| Gigabyte      | B550M DS3H                  | Desktop     | [dd555e8925](https://linux-hardware.org/?probe=dd555e8925) | Dec 05, 2024 |
| Monster       | TULPAR T7 V20.8             | Notebook    | [e7cc7b7cff](https://linux-hardware.org/?probe=e7cc7b7cff) | Dec 05, 2024 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [010553b978](https://linux-hardware.org/?probe=010553b978) | Dec 03, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [ba7f5c098d](https://linux-hardware.org/?probe=ba7f5c098d) | Dec 03, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [7934b3b43f](https://linux-hardware.org/?probe=7934b3b43f) | Dec 02, 2024 |
| MSI           | B760M GAMING PLUS WIFI      | Desktop     | [8ec6dab60d](https://linux-hardware.org/?probe=8ec6dab60d) | Dec 02, 2024 |
| HUAWEI        | FLMH-XX                     | Notebook    | [6ba9f9d750](https://linux-hardware.org/?probe=6ba9f9d750) | Dec 01, 2024 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [ce23ae6c58](https://linux-hardware.org/?probe=ce23ae6c58) | Dec 01, 2024 |
| Lenovo        | ThinkPad T420 4236QE0       | Notebook    | [a54ec09f06](https://linux-hardware.org/?probe=a54ec09f06) | Dec 01, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [327fdb0e6a](https://linux-hardware.org/?probe=327fdb0e6a) | Nov 30, 2024 |
| Toshiba       | Satellite L650              | Notebook    | [46de3b0fa4](https://linux-hardware.org/?probe=46de3b0fa4) | Nov 28, 2024 |
| Lenovo        | LOQ 15IRH8 82XV             | Notebook    | [3ab6a03116](https://linux-hardware.org/?probe=3ab6a03116) | Nov 27, 2024 |
| HP            | 245 G8 Notebook PC          | Notebook    | [ab39483aa3](https://linux-hardware.org/?probe=ab39483aa3) | Nov 27, 2024 |
| Biostar       | B650MP-E PRO                | Desktop     | [89dfe41b02](https://linux-hardware.org/?probe=89dfe41b02) | Nov 26, 2024 |
| Dell          | Inspiron MM061              | Notebook    | [b0e7029133](https://linux-hardware.org/?probe=b0e7029133) | Nov 24, 2024 |
| Lenovo        | G550 20023                  | Notebook    | [1feabb54b9](https://linux-hardware.org/?probe=1feabb54b9) | Nov 23, 2024 |
| ASUSTek       | TP410UR                     | Convertible | [67e9fe630a](https://linux-hardware.org/?probe=67e9fe630a) | Nov 23, 2024 |
| Monster       | TULPAR T7 V19.3             | Notebook    | [a1fed284f5](https://linux-hardware.org/?probe=a1fed284f5) | Nov 21, 2024 |
| ASUSTek       | 1215N                       | Notebook    | [b7baad3524](https://linux-hardware.org/?probe=b7baad3524) | Nov 20, 2024 |
| Lenovo        | G510 20238                  | Notebook    | [3150f49961](https://linux-hardware.org/?probe=3150f49961) | Nov 19, 2024 |
| Dell          | 0HHV7N A00                  | Desktop     | [c9996cd0d1](https://linux-hardware.org/?probe=c9996cd0d1) | Nov 19, 2024 |
| Lenovo        | Unknown                     | Convertible | [098af926f6](https://linux-hardware.org/?probe=098af926f6) | Nov 18, 2024 |
| Dell          | Inspiron 3542               | Notebook    | [21d296d057](https://linux-hardware.org/?probe=21d296d057) | Nov 17, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [42db53d080](https://linux-hardware.org/?probe=42db53d080) | Nov 17, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [2ce961a6cc](https://linux-hardware.org/?probe=2ce961a6cc) | Nov 17, 2024 |
| ASUSTek       | ROG CROSSHAIR VI HERO       | Desktop     | [f641f8c43b](https://linux-hardware.org/?probe=f641f8c43b) | Nov 16, 2024 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [2d1f399be3](https://linux-hardware.org/?probe=2d1f399be3) | Nov 16, 2024 |
| Lenovo        | ThinkPad E580 20KTS0TF00    | Notebook    | [e31ae6a9c2](https://linux-hardware.org/?probe=e31ae6a9c2) | Nov 15, 2024 |
| Acer          | Aspire A315-510P            | Notebook    | [d408ed76f5](https://linux-hardware.org/?probe=d408ed76f5) | Nov 15, 2024 |
| Lenovo        | ThinkPad T420 4236QE0       | Notebook    | [655fe70c91](https://linux-hardware.org/?probe=655fe70c91) | Nov 15, 2024 |
| ASUSTek       | PRIME B650M-A               | Desktop     | [7f5a27aa31](https://linux-hardware.org/?probe=7f5a27aa31) | Nov 15, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [7938b1e23f](https://linux-hardware.org/?probe=7938b1e23f) | Nov 15, 2024 |
| Lenovo        | ThinkPad E14 Gen 5 21JK0... | Notebook    | [7b5c860bd2](https://linux-hardware.org/?probe=7b5c860bd2) | Nov 15, 2024 |
| ECS           | H81H3-M7                    | Desktop     | [58029deefd](https://linux-hardware.org/?probe=58029deefd) | Nov 14, 2024 |
| Lenovo        | 80TV                        | Notebook    | [040e0f4702](https://linux-hardware.org/?probe=040e0f4702) | Nov 14, 2024 |
| Gigabyte      | A520M K V2                  | Desktop     | [3ad379757e](https://linux-hardware.org/?probe=3ad379757e) | Nov 14, 2024 |
| ECS           | H81H3-M7                    | Desktop     | [d17f318daf](https://linux-hardware.org/?probe=d17f318daf) | Nov 13, 2024 |
| HUAWEI        | FLMH-XX                     | Notebook    | [3472dd9d1b](https://linux-hardware.org/?probe=3472dd9d1b) | Nov 13, 2024 |
| Lenovo        | Yoga Slim 6 14APU8 82X3     | Notebook    | [c9ce1b5431](https://linux-hardware.org/?probe=c9ce1b5431) | Nov 12, 2024 |
| Casper        | NIRVANA DESKTOP             | Desktop     | [e2bdc33005](https://linux-hardware.org/?probe=e2bdc33005) | Nov 12, 2024 |
| Lenovo        | G510 20238                  | Notebook    | [83400b4b16](https://linux-hardware.org/?probe=83400b4b16) | Nov 12, 2024 |
| Lenovo        | ThinkPad T480 20L6S68A00    | Notebook    | [5dd8147a6b](https://linux-hardware.org/?probe=5dd8147a6b) | Nov 12, 2024 |
| Pegatron      | IPXSB-H61                   | Desktop     | [f1c9282a4e](https://linux-hardware.org/?probe=f1c9282a4e) | Nov 11, 2024 |
| Lenovo        | V15 G3 IAP 82TT             | Notebook    | [7695a66d9d](https://linux-hardware.org/?probe=7695a66d9d) | Nov 10, 2024 |
| HP            | Laptop 15-bw0xx             | Notebook    | [df8fc5ffa1](https://linux-hardware.org/?probe=df8fc5ffa1) | Nov 10, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [7bba50e3f8](https://linux-hardware.org/?probe=7bba50e3f8) | Nov 10, 2024 |
| Lenovo        | ThinkPad E580 20KTS0TF00    | Notebook    | [c8e4e4682f](https://linux-hardware.org/?probe=c8e4e4682f) | Nov 10, 2024 |
| Google        | Sasuke                      | Notebook    | [753719e3df](https://linux-hardware.org/?probe=753719e3df) | Nov 10, 2024 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [67ea5c25e9](https://linux-hardware.org/?probe=67ea5c25e9) | Nov 09, 2024 |
| Casper        | NIRVANA DESKTOP             | Desktop     | [c11bfcf401](https://linux-hardware.org/?probe=c11bfcf401) | Nov 09, 2024 |
| Dell          | Inspiron 3542               | Notebook    | [8268a446ea](https://linux-hardware.org/?probe=8268a446ea) | Nov 09, 2024 |
| Acer          | AO722                       | Notebook    | [4f5bec46c5](https://linux-hardware.org/?probe=4f5bec46c5) | Nov 09, 2024 |
| Dell          | Venue 10 Pro 5056           | Notebook    | [ae2d574cf1](https://linux-hardware.org/?probe=ae2d574cf1) | Nov 08, 2024 |
| HP            | 240 G8                      | Notebook    | [690c75feed](https://linux-hardware.org/?probe=690c75feed) | Nov 08, 2024 |
| ASUSTek       | X555LNB                     | Notebook    | [779d09dbb2](https://linux-hardware.org/?probe=779d09dbb2) | Nov 08, 2024 |
| HP            | 240 G8                      | Notebook    | [7144a2acc7](https://linux-hardware.org/?probe=7144a2acc7) | Nov 07, 2024 |
| Dell          | Latitude 7490               | Notebook    | [40a7d96d8f](https://linux-hardware.org/?probe=40a7d96d8f) | Nov 06, 2024 |
| Acer          | Aspire A315-58              | Notebook    | [921e1620e2](https://linux-hardware.org/?probe=921e1620e2) | Nov 05, 2024 |
| ASUSTek       | N56VZ                       | Notebook    | [b9d0972185](https://linux-hardware.org/?probe=b9d0972185) | Nov 05, 2024 |
| Pegatron      | A15                         | Notebook    | [537f5599a8](https://linux-hardware.org/?probe=537f5599a8) | Nov 04, 2024 |
| Toshiba       | Satellite C850-1G2          | Notebook    | [1a8e3e84b5](https://linux-hardware.org/?probe=1a8e3e84b5) | Nov 04, 2024 |
| Acer          | Veriton S2680G              | Desktop     | [54d0a278b8](https://linux-hardware.org/?probe=54d0a278b8) | Nov 04, 2024 |
| Casper        | C17B                        | Desktop     | [5d63a37717](https://linux-hardware.org/?probe=5d63a37717) | Nov 04, 2024 |
| MSI           | P55M-SD40                   | Desktop     | [dfcb4597a5](https://linux-hardware.org/?probe=dfcb4597a5) | Nov 04, 2024 |
| Gigabyte      | P35-DS3R                    | Desktop     | [29cf823892](https://linux-hardware.org/?probe=29cf823892) | Nov 03, 2024 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [89e824991d](https://linux-hardware.org/?probe=89e824991d) | Nov 03, 2024 |
| ASUSTek       | ROG STRIX Z790-A GAMING ... | Desktop     | [3e6a954b64](https://linux-hardware.org/?probe=3e6a954b64) | Nov 02, 2024 |
| Lenovo        | 36FE SDK0T31540 WIN 3273... | All in one  | [135ba52d4b](https://linux-hardware.org/?probe=135ba52d4b) | Nov 01, 2024 |
| HP            | EliteBook 830 G5            | Notebook    | [2bbad052d1](https://linux-hardware.org/?probe=2bbad052d1) | Nov 01, 2024 |
| HPE           | ProLiant DL380 Gen10        | Server      | [41511af19a](https://linux-hardware.org/?probe=41511af19a) | Nov 01, 2024 |
| HP            | ZBook Power 15.6 inch G1... | Notebook    | [d69a41ab4c](https://linux-hardware.org/?probe=d69a41ab4c) | Nov 01, 2024 |
| HPE           | ProLiant DL380 Gen10        | Server      | [ed0e72c67e](https://linux-hardware.org/?probe=ed0e72c67e) | Oct 31, 2024 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [08f5e3b392](https://linux-hardware.org/?probe=08f5e3b392) | Oct 31, 2024 |
| ASUSTek       | A55BM-E                     | Desktop     | [3f7b67ed7e](https://linux-hardware.org/?probe=3f7b67ed7e) | Oct 31, 2024 |
| HP            | Laptop 15-bw0xx             | Notebook    | [55ef342a18](https://linux-hardware.org/?probe=55ef342a18) | Oct 31, 2024 |
| Biostar       | A320MH                      | Desktop     | [407ce72b40](https://linux-hardware.org/?probe=407ce72b40) | Oct 30, 2024 |
| Biostar       | A320MH                      | Desktop     | [11e942817c](https://linux-hardware.org/?probe=11e942817c) | Oct 29, 2024 |
| Lenovo        | V15 G3 IAP 82TT             | Notebook    | [bdb953f731](https://linux-hardware.org/?probe=bdb953f731) | Oct 29, 2024 |
| Gigabyte      | H61M-DS2                    | Desktop     | [689b826b4c](https://linux-hardware.org/?probe=689b826b4c) | Oct 29, 2024 |
| Dell          | G15 5530                    | Notebook    | [6941a99e57](https://linux-hardware.org/?probe=6941a99e57) | Oct 29, 2024 |
| Sony          | SVE1513B1EW                 | Notebook    | [adafaaffe0](https://linux-hardware.org/?probe=adafaaffe0) | Oct 28, 2024 |
| Lenovo        | ThinkBook 14 G6 IRL 21KG    | Notebook    | [45037f9589](https://linux-hardware.org/?probe=45037f9589) | Oct 28, 2024 |
| Dell          | Latitude 7490               | Notebook    | [6e6ac56fcc](https://linux-hardware.org/?probe=6e6ac56fcc) | Oct 27, 2024 |
| Gigabyte      | Z87X-UD5H-CF                | Desktop     | [4f099e9c59](https://linux-hardware.org/?probe=4f099e9c59) | Oct 27, 2024 |
| ECS           | G41T-M7                     | Desktop     | [a894aac1a8](https://linux-hardware.org/?probe=a894aac1a8) | Oct 26, 2024 |
| ASUSTek       | N56VZ                       | Notebook    | [5a2ccfc817](https://linux-hardware.org/?probe=5a2ccfc817) | Oct 25, 2024 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [13b8c0c21b](https://linux-hardware.org/?probe=13b8c0c21b) | Oct 25, 2024 |
| Acer          | Aspire A315-44P             | Notebook    | [934542a907](https://linux-hardware.org/?probe=934542a907) | Oct 24, 2024 |
| HP            | Victus by Gaming Laptop     | Notebook    | [bc8d8cff4f](https://linux-hardware.org/?probe=bc8d8cff4f) | Oct 24, 2024 |
| HP            | Victus by Gaming Laptop     | Notebook    | [47a2646ba5](https://linux-hardware.org/?probe=47a2646ba5) | Oct 24, 2024 |
| Clevo         | W7x0S                       | Notebook    | [b11743728f](https://linux-hardware.org/?probe=b11743728f) | Oct 23, 2024 |
| Monster       | ABRA A5 V16.7               | Notebook    | [f8efab3cd8](https://linux-hardware.org/?probe=f8efab3cd8) | Oct 21, 2024 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [8cf9a787be](https://linux-hardware.org/?probe=8cf9a787be) | Oct 21, 2024 |
| Sony          | SVD11223CXB                 | Notebook    | [6b3e7fa3c6](https://linux-hardware.org/?probe=6b3e7fa3c6) | Oct 20, 2024 |
| Gigabyte      | M68MT-S2                    | Desktop     | [7fc2990d42](https://linux-hardware.org/?probe=7fc2990d42) | Oct 20, 2024 |
| ASRock        | B650M-HDV/M.2               | Desktop     | [be17e54973](https://linux-hardware.org/?probe=be17e54973) | Oct 19, 2024 |
| Monster       | ABRA A7 V13.2               | Notebook    | [407b879b51](https://linux-hardware.org/?probe=407b879b51) | Oct 18, 2024 |
| ASRock        | A620M-HDV/M.2               | Desktop     | [9554d9dad6](https://linux-hardware.org/?probe=9554d9dad6) | Oct 18, 2024 |
| Gigabyte      | B450M S2H                   | Desktop     | [876b2c0c0d](https://linux-hardware.org/?probe=876b2c0c0d) | Oct 18, 2024 |
| ASUSTek       | N56VZ                       | Notebook    | [c544ccf331](https://linux-hardware.org/?probe=c544ccf331) | Oct 18, 2024 |
| ASUSTek       | K54HR                       | Notebook    | [fc05d76312](https://linux-hardware.org/?probe=fc05d76312) | Oct 16, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [fc1933d5c8](https://linux-hardware.org/?probe=fc1933d5c8) | Oct 16, 2024 |
| Lenovo        | V15 G3 ABA 82TV             | Notebook    | [3c4ca188ae](https://linux-hardware.org/?probe=3c4ca188ae) | Oct 16, 2024 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [11e13e67c7](https://linux-hardware.org/?probe=11e13e67c7) | Oct 15, 2024 |
| Unknown       | Marble based on Qualcomm... | Phone       | [e97763ab29](https://linux-hardware.org/?probe=e97763ab29) | Oct 14, 2024 |
| Unknown       | Marble based on Qualcomm... | Soc         | [848397f66d](https://linux-hardware.org/?probe=848397f66d) | Oct 14, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [25b6c78476](https://linux-hardware.org/?probe=25b6c78476) | Oct 14, 2024 |
| Unknown       | Marble based on Qualcomm... | Phone       | [f8555eb0a0](https://linux-hardware.org/?probe=f8555eb0a0) | Oct 13, 2024 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [18f5e5c8e6](https://linux-hardware.org/?probe=18f5e5c8e6) | Oct 13, 2024 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [10e167a65f](https://linux-hardware.org/?probe=10e167a65f) | Oct 12, 2024 |
| Dell          | Latitude 7490               | Notebook    | [5059be1beb](https://linux-hardware.org/?probe=5059be1beb) | Oct 12, 2024 |
| Lenovo        | ThinkPad T490s 20NX000EM... | Notebook    | [f7d0f24b04](https://linux-hardware.org/?probe=f7d0f24b04) | Oct 12, 2024 |
| Samsung       | 700T1C                      | Notebook    | [4b23ed4627](https://linux-hardware.org/?probe=4b23ed4627) | Oct 12, 2024 |
| Lenovo        | ThinkPad E580 20KTS0TF00    | Notebook    | [bc5a916f1a](https://linux-hardware.org/?probe=bc5a916f1a) | Oct 11, 2024 |
| MECHREVO      | WUJIE14 PRO                 | Notebook    | [8ae202abaa](https://linux-hardware.org/?probe=8ae202abaa) | Oct 11, 2024 |
| HUAWEI        | FLMH-XX                     | Notebook    | [b05f724fb4](https://linux-hardware.org/?probe=b05f724fb4) | Oct 11, 2024 |
| HUAWEI        | FLMH-XX                     | Notebook    | [1467f8690d](https://linux-hardware.org/?probe=1467f8690d) | Oct 11, 2024 |
| Lenovo        | LOQ 15APH8 82XT             | Notebook    | [c5b7de1f56](https://linux-hardware.org/?probe=c5b7de1f56) | Oct 10, 2024 |
| Lenovo        | ThinkPad T490s 20NX000EM... | Notebook    | [879ee1edbe](https://linux-hardware.org/?probe=879ee1edbe) | Oct 10, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [ca76f0b98d](https://linux-hardware.org/?probe=ca76f0b98d) | Oct 08, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [e79581cb5f](https://linux-hardware.org/?probe=e79581cb5f) | Oct 08, 2024 |
| Lenovo        | V15 G3 ABA 82TV             | Notebook    | [bf025aaa26](https://linux-hardware.org/?probe=bf025aaa26) | Oct 08, 2024 |
| Acer          | Aspire A315-58              | Notebook    | [55f15d5c81](https://linux-hardware.org/?probe=55f15d5c81) | Oct 07, 2024 |
| ASUSTek       | PRIME H310M-F R2.0          | Desktop     | [1b09e0c3c0](https://linux-hardware.org/?probe=1b09e0c3c0) | Oct 06, 2024 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [1e2e268764](https://linux-hardware.org/?probe=1e2e268764) | Oct 06, 2024 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [728d0f4561](https://linux-hardware.org/?probe=728d0f4561) | Oct 06, 2024 |
| HP            | Pavilion Notebook           | Notebook    | [81c79a5d56](https://linux-hardware.org/?probe=81c79a5d56) | Oct 06, 2024 |
| ASUSTek       | ROG Maximus Z790 DARK HE... | Desktop     | [997be25415](https://linux-hardware.org/?probe=997be25415) | Oct 06, 2024 |
| ARCELIK       | 1M7-GNB1595B6I7             | Notebook    | [cbf522f76a](https://linux-hardware.org/?probe=cbf522f76a) | Oct 05, 2024 |
| Lenovo        | ThinkPad T420 4236QE0       | Notebook    | [0c7aff3c04](https://linux-hardware.org/?probe=0c7aff3c04) | Oct 05, 2024 |
| MSI           | GV62 8RD                    | Notebook    | [35758c0597](https://linux-hardware.org/?probe=35758c0597) | Oct 05, 2024 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [b4b87eb67a](https://linux-hardware.org/?probe=b4b87eb67a) | Oct 05, 2024 |
| ASUSTek       | H81-PLUS                    | Desktop     | [716c393a81](https://linux-hardware.org/?probe=716c393a81) | Oct 04, 2024 |
| HUAWEI        | RLEF-XX                     | Notebook    | [468a95b0cc](https://linux-hardware.org/?probe=468a95b0cc) | Oct 04, 2024 |
| ASUSTek       | ROG Zephyrus G16 GU603ZU... | Notebook    | [12400a6356](https://linux-hardware.org/?probe=12400a6356) | Oct 04, 2024 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [651d2afc77](https://linux-hardware.org/?probe=651d2afc77) | Oct 03, 2024 |
| Lenovo        | Legion Pro 7 16IRX8H 82W... | Notebook    | [1f0d3132f6](https://linux-hardware.org/?probe=1f0d3132f6) | Oct 03, 2024 |
| ASUSTek       | ROG Strix G513RW_G513RW     | Notebook    | [c661e02463](https://linux-hardware.org/?probe=c661e02463) | Oct 02, 2024 |
| ASUSTek       | UX32LN                      | Notebook    | [4b3007f4c6](https://linux-hardware.org/?probe=4b3007f4c6) | Oct 01, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop TP36... | Convertible | [21f5f58e09](https://linux-hardware.org/?probe=21f5f58e09) | Oct 01, 2024 |
| Lenovo        | 3168 NOK                    | Desktop     | [dfb948690a](https://linux-hardware.org/?probe=dfb948690a) | Oct 01, 2024 |
| Lenovo        | 3168 NOK                    | Desktop     | [8e499e7fc8](https://linux-hardware.org/?probe=8e499e7fc8) | Oct 01, 2024 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [db46a7d985](https://linux-hardware.org/?probe=db46a7d985) | Sep 30, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [9195644a46](https://linux-hardware.org/?probe=9195644a46) | Sep 30, 2024 |
| HP            | ZBook Power 15.6 inch G1... | Notebook    | [9bf2277f20](https://linux-hardware.org/?probe=9bf2277f20) | Sep 29, 2024 |
| HP            | OMEN by Laptop 17-cb1xxx    | Notebook    | [f2cbe1fb13](https://linux-hardware.org/?probe=f2cbe1fb13) | Sep 29, 2024 |
| Dell          | XPS 13 9360                 | Notebook    | [4559019bac](https://linux-hardware.org/?probe=4559019bac) | Sep 28, 2024 |
| Lenovo        | ThinkPad X13 Yoga Gen 1 ... | Convertible | [d59e554ef6](https://linux-hardware.org/?probe=d59e554ef6) | Sep 28, 2024 |
| Insyde        | i101c                       | Notebook    | [7dd9fb58f1](https://linux-hardware.org/?probe=7dd9fb58f1) | Sep 27, 2024 |
| Casper        | NIRVANA                     | Notebook    | [7fec4c1d6a](https://linux-hardware.org/?probe=7fec4c1d6a) | Sep 26, 2024 |
| ASUSTek       | ROG STRIX Z790-H GAMING ... | Desktop     | [d819589690](https://linux-hardware.org/?probe=d819589690) | Sep 26, 2024 |
| Lenovo        | ThinkPad P17 Gen 1 20SN0... | Notebook    | [ed2e8ae8ee](https://linux-hardware.org/?probe=ed2e8ae8ee) | Sep 24, 2024 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [db86b2783d](https://linux-hardware.org/?probe=db86b2783d) | Sep 23, 2024 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [2761cb9d0a](https://linux-hardware.org/?probe=2761cb9d0a) | Sep 23, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [37ebfb4233](https://linux-hardware.org/?probe=37ebfb4233) | Sep 23, 2024 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [5872050527](https://linux-hardware.org/?probe=5872050527) | Sep 23, 2024 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Turkey/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 249       | 7.24%   |
| Ubuntu 22.04                 | 211       | 6.13%   |
| Arch Rolling                 | 174       | 5.06%   |
| Ubuntu 18.04                 | 171       | 4.97%   |
| Ubuntu 24.04                 | 117       | 3.4%    |
| Zorin 17                     | 67        | 1.95%   |
| Debian 12                    | 65        | 1.89%   |
| ArcoLinux Rolling            | 62        | 1.8%    |
| Pop!_OS 22.04                | 57        | 1.66%   |
| Fedora 40                    | 50        | 1.45%   |
| OpenMandriva 4.3             | 47        | 1.37%   |
| EndeavourOS Rolling          | 44        | 1.28%   |
| Fedora 42                    | 43        | 1.25%   |
| Fedora 39                    | 43        | 1.25%   |
| Fedora 38                    | 43        | 1.25%   |
| Linux Mint 22.1              | 41        | 1.19%   |
| Debian 11                    | 41        | 1.19%   |
| Zorin 16                     | 39        | 1.13%   |
| Fedora 41                    | 39        | 1.13%   |
| Manjaro                      | 36        | 1.05%   |
| Fedora 37                    | 35        | 1.02%   |
| Fedora 36                    | 34        | 0.99%   |
| Arch                         | 33        | 0.96%   |
| OpenMandriva 24.12           | 31        | 0.9%    |
| Linux Mint 21.3              | 31        | 0.9%    |
| OpenMandriva 23.08           | 30        | 0.87%   |
| Linux Mint 21.2              | 30        | 0.87%   |
| openSUSE Tumbleweed-XXXXXXXX | 28        | 0.81%   |
| Linux Mint 21.1              | 26        | 0.76%   |
| Fedora 33                    | 26        | 0.76%   |
| Ubuntu 23.10                 | 25        | 0.73%   |
| KDE neon 20.04               | 25        | 0.73%   |
| Linux Mint 20.3              | 24        | 0.7%    |
| Fedora 35                    | 22        | 0.64%   |
| OpenMandriva 23.01           | 21        | 0.61%   |
| Linux Mint 22.2              | 20        | 0.58%   |
| Linux Mint 22                | 19        | 0.55%   |
| Linux Mint 20.1              | 19        | 0.55%   |
| Ubuntu 23.04                 | 18        | 0.52%   |
| Ubuntu 21.10                 | 18        | 0.52%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 884       | 26.98%  |
| Fedora       | 334       | 10.2%   |
| Linux Mint   | 273       | 8.33%   |
| OpenMandriva | 226       | 6.9%    |
| Arch         | 204       | 6.23%   |
| Debian       | 147       | 4.49%   |
| Zorin        | 130       | 3.97%   |
| Pardus       | 97        | 2.96%   |
| Pop!_OS      | 95        | 2.9%    |
| Manjaro      | 82        | 2.5%    |
| ArcoLinux    | 66        | 2.01%   |
| Kubuntu      | 57        | 1.74%   |
| KDE neon     | 55        | 1.68%   |
| EndeavourOS  | 45        | 1.37%   |
| Kali         | 44        | 1.34%   |
| Elementary   | 39        | 1.19%   |
| ROSA         | 37        | 1.13%   |
| openSUSE     | 37        | 1.13%   |
| Xubuntu      | 27        | 0.82%   |
| Endless      | 27        | 0.82%   |
| Lubuntu      | 26        | 0.79%   |
| Garuda Linux | 22        | 0.67%   |
| Gentoo       | 21        | 0.64%   |
| CachyOS      | 21        | 0.64%   |
| Ubuntu MATE  | 20        | 0.61%   |
| Ubuntu Unity | 19        | 0.58%   |
| LMDE         | 16        | 0.49%   |
| Bazzite      | 14        | 0.43%   |
| Xero         | 13        | 0.4%    |
| MX           | 13        | 0.4%    |
| PostmarketOS | 12        | 0.37%   |
| Nobara       | 11        | 0.34%   |
| Clear Linux  | 10        | 0.31%   |
| Artix        | 10        | 0.31%   |
| Void Linux   | 8         | 0.24%   |
| TUXEDO OS    | 8         | 0.24%   |
| SteamOS      | 8         | 0.24%   |
| NixOS        | 8         | 0.24%   |
| Alpine       | 7         | 0.21%   |
| Deepin       | 6         | 0.18%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 45        | 1.21%   |
| 6.14.2-desktop-3omv2590  | 38        | 1.02%   |
| 6.12.1-desktop-1omv2490  | 30        | 0.8%    |
| 6.4.11-desktop-1omv2390  | 28        | 0.75%   |
| 6.8.0-45-generic         | 25        | 0.67%   |
| 5.4.0-42-generic         | 25        | 0.67%   |
| 6.8.0-48-generic         | 23        | 0.62%   |
| 5.4.0-58-generic         | 22        | 0.59%   |
| 6.1.1-desktop-1omv2290   | 21        | 0.56%   |
| 5.15.0-56-generic        | 21        | 0.56%   |
| 6.2.0-26-generic         | 20        | 0.54%   |
| 5.15.0-58-generic        | 20        | 0.54%   |
| 6.8.0-52-generic         | 19        | 0.51%   |
| 6.14.0-37-generic        | 18        | 0.48%   |
| 6.8.0-31-generic         | 17        | 0.46%   |
| 6.6.2-desktop-1omv2390   | 16        | 0.43%   |
| 6.8.0-51-generic         | 15        | 0.4%    |
| 6.8.0-41-generic         | 15        | 0.4%    |
| 5.0.0-37-generic         | 15        | 0.4%    |
| 6.8.0-57-generic         | 14        | 0.38%   |
| 6.1.0-17-amd64           | 14        | 0.38%   |
| 5.4.0-48-generic         | 14        | 0.38%   |
| 5.4.0-26-generic         | 14        | 0.38%   |
| 5.15.0-52-generic        | 14        | 0.38%   |
| 4.18.0-15-generic        | 14        | 0.38%   |
| 6.9.3-76060903-generic   | 13        | 0.35%   |
| 5.3.0-40-generic         | 13        | 0.35%   |
| 5.15.0-48-generic        | 13        | 0.35%   |
| 5.15.0-43-generic        | 13        | 0.35%   |
| 5.10.0-21-amd64          | 13        | 0.35%   |
| 6.5.0-35-generic         | 12        | 0.32%   |
| 5.19.0-32-generic        | 12        | 0.32%   |
| 5.10.14-desktop-1omv4002 | 12        | 0.32%   |
| 6.8.0-49-generic         | 11        | 0.29%   |
| 6.5.0-28-generic         | 11        | 0.29%   |
| 6.5.0-26-generic         | 11        | 0.29%   |
| 6.5.0-14-generic         | 11        | 0.29%   |
| 6.2.0-32-generic         | 11        | 0.29%   |
| 6.14.0-29-generic        | 11        | 0.29%   |
| 5.8.0-43-generic         | 11        | 0.29%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 290       | 8.05%   |
| 5.15.0  | 260       | 7.22%   |
| 6.8.0   | 229       | 6.36%   |
| 6.1.0   | 119       | 3.3%    |
| 6.5.0   | 108       | 3%      |
| 5.10.0  | 99        | 2.75%   |
| 5.8.0   | 95        | 2.64%   |
| 6.2.0   | 92        | 2.55%   |
| 4.15.0  | 90        | 2.5%    |
| 6.14.0  | 85        | 2.36%   |
| 5.11.0  | 85        | 2.36%   |
| 5.13.0  | 77        | 2.14%   |
| 5.3.0   | 65        | 1.81%   |
| 5.19.0  | 59        | 1.64%   |
| 5.0.0   | 57        | 1.58%   |
| 6.11.0  | 47        | 1.31%   |
| 5.16.7  | 47        | 1.31%   |
| 4.18.0  | 46        | 1.28%   |
| 6.14.2  | 42        | 1.17%   |
| 6.12.1  | 34        | 0.94%   |
| 6.4.11  | 32        | 0.89%   |
| 4.19.0  | 30        | 0.83%   |
| 6.1.1   | 25        | 0.69%   |
| 6.6.2   | 19        | 0.53%   |
| 6.2.6   | 19        | 0.53%   |
| 6.9.3   | 18        | 0.5%    |
| 6.8.5   | 16        | 0.44%   |
| 6.12.10 | 16        | 0.44%   |
| 6.10.6  | 16        | 0.44%   |
| 6.4.12  | 15        | 0.42%   |
| 6.13.5  | 15        | 0.42%   |
| 5.10.14 | 13        | 0.36%   |
| 6.8.11  | 11        | 0.31%   |
| 6.4.6   | 11        | 0.31%   |
| 6.12.9  | 11        | 0.31%   |
| 6.0.12  | 11        | 0.31%   |
| 6.8.9   | 10        | 0.28%   |
| 6.5.6   | 10        | 0.28%   |
| 6.14.6  | 10        | 0.28%   |
| 6.11.5  | 10        | 0.28%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 323       | 9.16%   |
| 5.4     | 307       | 8.7%    |
| 6.8     | 287       | 8.13%   |
| 6.1     | 200       | 5.67%   |
| 6.14    | 158       | 4.48%   |
| 6.5     | 156       | 4.42%   |
| 5.10    | 154       | 4.37%   |
| 6.2     | 152       | 4.31%   |
| 5.11    | 116       | 3.29%   |
| 5.8     | 112       | 3.17%   |
| 6.12    | 108       | 3.06%   |
| 6.4     | 97        | 2.75%   |
| 6.6     | 91        | 2.58%   |
| 4.15    | 90        | 2.55%   |
| 5.13    | 89        | 2.52%   |
| 6.11    | 87        | 2.47%   |
| 5.19    | 82        | 2.32%   |
| 5.16    | 81        | 2.3%    |
| 5.3     | 76        | 2.15%   |
| 5.0     | 59        | 1.67%   |
| 6.9     | 55        | 1.56%   |
| 6.10    | 51        | 1.45%   |
| 6.0     | 49        | 1.39%   |
| 4.18    | 49        | 1.39%   |
| 6.17    | 41        | 1.16%   |
| 6.15    | 41        | 1.16%   |
| 6.13    | 40        | 1.13%   |
| 6.3     | 37        | 1.05%   |
| 6.7     | 36        | 1.02%   |
| 5.18    | 36        | 1.02%   |
| 6.16    | 33        | 0.94%   |
| 4.19    | 33        | 0.94%   |
| 5.17    | 31        | 0.88%   |
| 5.9     | 29        | 0.82%   |
| 5.14    | 23        | 0.65%   |
| 4.9     | 23        | 0.65%   |
| 5.6     | 17        | 0.48%   |
| 5.7     | 16        | 0.45%   |
| 5.12    | 16        | 0.45%   |
| 6.18    | 12        | 0.34%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 2991      | 96.86%  |
| i686    | 55        | 1.78%   |
| aarch64 | 30        | 0.97%   |
| armv7l  | 12        | 0.39%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 1442      | 43.91%  |
| KDE5             | 415       | 12.64%  |
| XFCE             | 291       | 8.86%   |
| Unknown          | 276       | 8.4%    |
| KDE6             | 241       | 7.34%   |
| X-Cinnamon       | 213       | 6.49%   |
| MATE             | 60        | 1.83%   |
| KDE              | 53        | 1.61%   |
| LXQt             | 42        | 1.28%   |
| Pantheon         | 39        | 1.19%   |
| Cinnamon         | 27        | 0.82%   |
| Hyprland         | 25        | 0.76%   |
| i3               | 24        | 0.73%   |
| KDE4             | 23        | 0.7%    |
| Unity            | 19        | 0.58%   |
| sway             | 15        | 0.46%   |
| LXDE             | 13        | 0.4%    |
| Deepin           | 11        | 0.33%   |
| GNOME Classic    | 6         | 0.18%   |
| Budgie           | 6         | 0.18%   |
| niri             | 5         | 0.15%   |
| Trinity          | 4         | 0.12%   |
| openbox          | 4         | 0.12%   |
| DWM              | 4         | 0.12%   |
| COSMIC           | 3         | 0.09%   |
| bspwm            | 3         | 0.09%   |
| xmonad           | 2         | 0.06%   |
| Phosh:GNOME      | 2         | 0.06%   |
| LXDE-pi-wayfire  | 2         | 0.06%   |
| labwc:wlroots    | 2         | 0.06%   |
| fluxbox          | 2         | 0.06%   |
| qtile            | 1         | 0.03%   |
| Lingmo           | 1         | 0.03%   |
| lightdm-xsession | 1         | 0.03%   |
| ICEWM            | 1         | 0.03%   |
| GNOME Flashback  | 1         | 0.03%   |
| Endless:GNOME    | 1         | 0.03%   |
| default          | 1         | 0.03%   |
| DDE              | 1         | 0.03%   |
| BunsenLabs       | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 2014      | 62.41%  |
| Wayland | 1026      | 31.79%  |
| Unknown | 119       | 3.69%   |
| Tty     | 68        | 2.11%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 1400      | 43.06%  |
| SDDM           | 560       | 17.23%  |
| GDM3           | 497       | 15.29%  |
| LightDM        | 365       | 11.23%  |
| GDM            | 335       | 10.3%   |
| TDM            | 62        | 1.91%   |
| KDM            | 17        | 0.52%   |
| LY-DM          | 4         | 0.12%   |
| XDM            | 2         | 0.06%   |
| SLiM           | 2         | 0.06%   |
| Ly             | 2         | 0.06%   |
| LXDM           | 2         | 0.06%   |
| COSMIC-GREETER | 2         | 0.06%   |
| PLASMALOGIN    | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 1402      | 44.41%  |
| tr_TR       | 1309      | 41.46%  |
| Unknown     | 206       | 6.53%   |
| en_GB       | 92        | 2.91%   |
| C           | 65        | 2.06%   |
| ru_RU       | 22        | 0.7%    |
| de_DE       | 15        | 0.48%   |
| POSIX       | 4         | 0.13%   |
| en_CA       | 4         | 0.13%   |
| ar_EG       | 4         | 0.13%   |
| tr_CY       | 3         | 0.1%    |
| en_US.UTF8  | 3         | 0.1%    |
| C.UTF8      | 3         | 0.1%    |
| zh_CN       | 2         | 0.06%   |
| fr_FR       | 2         | 0.06%   |
| en_IE       | 2         | 0.06%   |
| en_DK       | 2         | 0.06%   |
| tr_TR.UTF8  | 1         | 0.03%   |
| tr_TR.utf-8 | 1         | 0.03%   |
| ru_UA       | 1         | 0.03%   |
| nl_BE       | 1         | 0.03%   |
| it_IT       | 1         | 0.03%   |
| fa_IR       | 1         | 0.03%   |
| es_ES       | 1         | 0.03%   |
| en_US-UTF-8 | 1         | 0.03%   |
| en_NZ       | 1         | 0.03%   |
| en_IN       | 1         | 0.03%   |
| en_GB.UTF8  | 1         | 0.03%   |
| en_AU       | 1         | 0.03%   |
| en_AG       | 1         | 0.03%   |
| en_150      | 1         | 0.03%   |
| el_GR       | 1         | 0.03%   |
| de_AT       | 1         | 0.03%   |
| az_AZ       | 1         | 0.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1681      | 53.06%  |
| BIOS | 1487      | 46.94%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 2129      | 66.16%  |
| Btrfs   | 538       | 16.72%  |
| Overlay | 212       | 6.59%   |
| Tmpfs   | 205       | 6.37%   |
| Unknown | 61        | 1.9%    |
| Xfs     | 31        | 0.96%   |
| Zfs     | 15        | 0.47%   |
| Ext2    | 15        | 0.47%   |
| F2fs    | 6         | 0.19%   |
| Ext3    | 4         | 0.12%   |
| Aufs    | 2         | 0.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 1515      | 47.64%  |
| Unknown | 1422      | 44.72%  |
| MBR     | 243       | 7.64%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2719      | 86.24%  |
| Yes       | 434       | 13.76%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2165      | 68.19%  |
| Yes       | 1010      | 31.81%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 551       | 17.85%  |
| Lenovo                  | 491       | 15.91%  |
| Hewlett-Packard         | 406       | 13.15%  |
| MSI                     | 220       | 7.13%   |
| Dell                    | 212       | 6.87%   |
| Acer                    | 175       | 5.67%   |
| Gigabyte Technology     | 154       | 4.99%   |
| Monster                 | 104       | 3.37%   |
| HUAWEI                  | 104       | 3.37%   |
| Casper                  | 74        | 2.4%    |
| Toshiba                 | 73        | 2.36%   |
| Apple                   | 72        | 2.33%   |
| Samsung Electronics     | 49        | 1.59%   |
| Sony                    | 41        | 1.33%   |
| Unknown                 | 40        | 1.3%    |
| Intel                   | 33        | 1.07%   |
| ASRock                  | 27        | 0.87%   |
| Packard Bell            | 24        | 0.78%   |
| Pegatron                | 22        | 0.71%   |
| Google                  | 18        | 0.58%   |
| Hometech                | 13        | 0.42%   |
| Foxconn                 | 13        | 0.42%   |
| Clevo                   | 13        | 0.42%   |
| ECS                     | 10        | 0.32%   |
| Raspberry Pi Foundation | 8         | 0.26%   |
| Fujitsu Siemens         | 8         | 0.26%   |
| Biostar                 | 8         | 0.26%   |
| ARCELIK                 | 8         | 0.26%   |
| Valve                   | 6         | 0.19%   |
| Fujitsu                 | 6         | 0.19%   |
| Vestel                  | 5         | 0.16%   |
| Microsoft               | 5         | 0.16%   |
| Huanan                  | 5         | 0.16%   |
| Notebook                | 4         | 0.13%   |
| Insyde                  | 4         | 0.13%   |
| HONOR                   | 4         | 0.13%   |
| AMI                     | 4         | 0.13%   |
| Alienware               | 4         | 0.13%   |
| LG Electronics          | 3         | 0.1%    |
| Technopc                | 2         | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown                              | 54        | 1.75%   |
| HP Pavilion g6                       | 27        | 0.87%   |
| ASUS All Series                      | 17        | 0.55%   |
| HP Victus by Gaming Laptop 16-s0xxx  | 15        | 0.49%   |
| Casper EXCALIBUR G770                | 15        | 0.49%   |
| Casper NIRVANA NOTEBOOK              | 14        | 0.45%   |
| HUAWEI BOD-WXX9                      | 11        | 0.36%   |
| HP Pavilion dv6                      | 11        | 0.36%   |
| HUAWEI BOM-WXX9                      | 10        | 0.32%   |
| HP Victus by Gaming Laptop 15-fa1xxx | 10        | 0.32%   |
| HP Pavilion 15                       | 10        | 0.32%   |
| HP Notebook                          | 10        | 0.32%   |
| Gigabyte B450M S2H                   | 10        | 0.32%   |
| Lenovo IdeaPad 3 15ITL6 82H8         | 9         | 0.29%   |
| HUAWEI HVY-WXX9                      | 8         | 0.26%   |
| Dell Inspiron 3542                   | 8         | 0.26%   |
| ASUS PRIME B450M-K II                | 8         | 0.26%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2  | 7         | 0.23%   |
| HUAWEI KLVL-WXX9                     | 7         | 0.23%   |
| HUAWEI FLMH-XX                       | 7         | 0.23%   |
| HUAWEI BoDE-WXX9                     | 7         | 0.23%   |
| HP Victus by Gaming Laptop 16-r0xxx  | 7         | 0.23%   |
| HP Pavilion Notebook                 | 7         | 0.23%   |
| HP 250 G3                            | 7         | 0.23%   |
| HP 15                                | 7         | 0.23%   |
| Gigabyte A320M-S2H                   | 7         | 0.23%   |
| ASUS X555UB                          | 7         | 0.23%   |
| ASUS X550VX                          | 7         | 0.23%   |
| ASUS PRIME B550M-K                   | 7         | 0.23%   |
| Acer Aspire 5750G                    | 7         | 0.23%   |
| Packard Bell EasyNote TJ65           | 6         | 0.19%   |
| MSI MS-7C52                          | 6         | 0.19%   |
| MSI MS-7C02                          | 6         | 0.19%   |
| MSI MS-7817                          | 6         | 0.19%   |
| Lenovo V15 G2 ALC 82KD               | 6         | 0.19%   |
| Intel H55                            | 6         | 0.19%   |
| HUAWEI NBLK-WAX9X                    | 6         | 0.19%   |
| HP Victus by Laptop 16-e0xxx         | 6         | 0.19%   |
| Gigabyte G31M-ES2L                   | 6         | 0.19%   |
| Dell Inspiron MM061                  | 6         | 0.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 163       | 5.28%   |
| Lenovo IdeaPad        | 117       | 3.79%   |
| Acer Aspire           | 102       | 3.3%    |
| HP Pavilion           | 97        | 3.14%   |
| Dell Inspiron         | 84        | 2.72%   |
| Toshiba Satellite     | 68        | 2.2%    |
| ASUS PRIME            | 61        | 1.98%   |
| Monster ABRA          | 59        | 1.91%   |
| ASUS ROG              | 57        | 1.85%   |
| HP Victus             | 54        | 1.75%   |
| Unknown               | 54        | 1.75%   |
| ASUS VivoBook         | 46        | 1.49%   |
| ASUS TUF              | 44        | 1.43%   |
| HP Laptop             | 43        | 1.39%   |
| Dell Latitude         | 41        | 1.33%   |
| Casper NIRVANA        | 36        | 1.17%   |
| ASUS ASUS             | 34        | 1.1%    |
| HP EliteBook          | 33        | 1.07%   |
| HP ProBook            | 31        | 1%      |
| Monster TULPAR        | 29        | 0.94%   |
| Acer Nitro            | 29        | 0.94%   |
| Casper EXCALIBUR      | 25        | 0.81%   |
| Lenovo Yoga           | 24        | 0.78%   |
| HP 250                | 24        | 0.78%   |
| Dell Vostro           | 24        | 0.78%   |
| Lenovo ThinkBook      | 23        | 0.75%   |
| Packard Bell EasyNote | 22        | 0.71%   |
| Lenovo Legion         | 22        | 0.71%   |
| Gigabyte B450M        | 18        | 0.58%   |
| Dell Precision        | 17        | 0.55%   |
| ASUS All              | 17        | 0.55%   |
| Monster HUMA          | 15        | 0.49%   |
| Lenovo V15            | 15        | 0.49%   |
| Lenovo LOQ            | 15        | 0.49%   |
| Acer Swift            | 15        | 0.49%   |
| HP Compaq             | 14        | 0.45%   |
| HP ENVY               | 13        | 0.42%   |
| ASUS ZenBook          | 13        | 0.42%   |
| Lenovo ThinkCentre    | 12        | 0.39%   |
| HP OMEN               | 12        | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 327       | 10.59%  |
| 2019    | 254       | 8.23%   |
| 2021    | 236       | 7.64%   |
| 2018    | 233       | 7.55%   |
| 2012    | 189       | 6.12%   |
| 2022    | 187       | 6.06%   |
| 2017    | 185       | 5.99%   |
| 2011    | 184       | 5.96%   |
| 2023    | 178       | 5.77%   |
| 2013    | 172       | 5.57%   |
| 2014    | 153       | 4.96%   |
| 2010    | 138       | 4.47%   |
| 2016    | 134       | 4.34%   |
| 2015    | 130       | 4.21%   |
| 2009    | 94        | 3.05%   |
| 2024    | 82        | 2.66%   |
| 2008    | 72        | 2.33%   |
| Unknown | 42        | 1.36%   |
| 2007    | 39        | 1.26%   |
| 2006    | 27        | 0.87%   |
| 2025    | 22        | 0.71%   |
| 2005    | 7         | 0.23%   |
| 2004    | 1         | 0.03%   |
| 2003    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2148      | 69.58%  |
| Desktop        | 783       | 25.36%  |
| Convertible    | 43        | 1.39%   |
| All in one     | 36        | 1.17%   |
| Tablet         | 25        | 0.81%   |
| System on chip | 24        | 0.78%   |
| Mini pc        | 17        | 0.55%   |
| Server         | 6         | 0.19%   |
| Phone          | 5         | 0.16%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 2886      | 92.35%  |
| Enabled  | 239       | 7.65%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3078      | 99.71%  |
| Yes  | 9         | 0.29%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 760       | 24.18%  |
| 16.01-24.0      | 664       | 21.13%  |
| 8.01-16.0       | 613       | 19.5%   |
| 3.01-4.0        | 458       | 14.57%  |
| 32.01-64.0      | 286       | 9.1%    |
| 1.01-2.0        | 137       | 4.36%   |
| 64.01-256.0     | 82        | 2.61%   |
| 24.01-32.0      | 78        | 2.48%   |
| 2.01-3.0        | 47        | 1.5%    |
| 0.51-1.0        | 16        | 0.51%   |
| More than 256.0 | 2         | 0.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 912       | 26.38%  |
| 2.01-3.0   | 889       | 25.72%  |
| 4.01-8.0   | 685       | 19.81%  |
| 3.01-4.0   | 591       | 17.1%   |
| 8.01-16.0  | 161       | 4.66%   |
| 0.51-1.0   | 157       | 4.54%   |
| 0.01-0.5   | 34        | 0.98%   |
| 16.01-24.0 | 16        | 0.46%   |
| 32.01-64.0 | 6         | 0.17%   |
| 24.01-32.0 | 5         | 0.14%   |
| Unknown    | 1         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1998      | 63.15%  |
| 2      | 845       | 26.71%  |
| 3      | 196       | 6.19%   |
| 4      | 66        | 2.09%   |
| 5      | 27        | 0.85%   |
| 0      | 17        | 0.54%   |
| 7      | 8         | 0.25%   |
| 6      | 7         | 0.22%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2303      | 74%     |
| Yes       | 809       | 26%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2613      | 84.32%  |
| No        | 486       | 15.68%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2503      | 80.79%  |
| No        | 595       | 19.21%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2201      | 70.52%  |
| No        | 920       | 29.48%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Turkey  | 3087      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Istanbul            | 1160      | 35.2%   |
| Ankara              | 450       | 13.66%  |
| Izmir               | 287       | 8.71%   |
| Bursa               | 147       | 4.46%   |
| Antalya             | 135       | 4.1%    |
| Adana               | 59        | 1.79%   |
| Kosekoy             | 49        | 1.49%   |
| Konya               | 47        | 1.43%   |
| Kayseri             | 40        | 1.21%   |
| Mersin              | 37        | 1.12%   |
| Gaziantep           | 37        | 1.12%   |
| Samsun              | 31        | 0.94%   |
| Balıkesir          | 30        | 0.91%   |
| Denizli             | 29        | 0.88%   |
| Aydin               | 27        | 0.82%   |
| Tekirdağ           | 26        | 0.79%   |
| İzmit              | 24        | 0.73%   |
| Mugla               | 22        | 0.67%   |
| Magnesia ad Sipylum | 20        | 0.61%   |
| Antakya             | 20        | 0.61%   |
| Adapazarı          | 20        | 0.61%   |
| Eskişehir          | 19        | 0.58%   |
| Trabzon             | 17        | 0.52%   |
| Şişli             | 16        | 0.49%   |
| Erzurum             | 15        | 0.46%   |
| Osmaniye            | 14        | 0.42%   |
| Zonguldak           | 11        | 0.33%   |
| Malatya             | 11        | 0.33%   |
| Kütahya            | 11        | 0.33%   |
| Çanakkale          | 11        | 0.33%   |
| Alanya              | 11        | 0.33%   |
| Ordu                | 10        | 0.3%    |
| Kırklareli         | 10        | 0.3%    |
| Kartal              | 10        | 0.3%    |
| Kahramanmaraş      | 10        | 0.3%    |
| Isparta             | 10        | 0.3%    |
| Batman              | 10        | 0.3%    |
| Atasehir            | 10        | 0.3%    |
| Yalova              | 9         | 0.27%   |
| Diyarbakır         | 9         | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 679       | 997    | 15.56%  |
| Seagate                     | 493       | 640    | 11.3%   |
| WDC                         | 475       | 679    | 10.89%  |
| SanDisk                     | 422       | 545    | 9.67%   |
| Toshiba                     | 296       | 354    | 6.78%   |
| Kingston                    | 231       | 311    | 5.29%   |
| Unknown                     | 162       | 203    | 3.71%   |
| SK hynix                    | 130       | 173    | 2.98%   |
| Micron Technology           | 128       | 154    | 2.93%   |
| Crucial                     | 83        | 100    | 1.9%    |
| Intel                       | 80        | 101    | 1.83%   |
| HGST                        | 79        | 94     | 1.81%   |
| Hitachi                     | 77        | 87     | 1.76%   |
| China                       | 77        | 89     | 1.76%   |
| KIOXIA                      | 75        | 92     | 1.72%   |
| A-DATA Technology           | 57        | 69     | 1.31%   |
| Kingston Technology Company | 51        | 65     | 1.17%   |
| Phison Electronics          | 47        | 54     | 1.08%   |
| KIOXIA-EXCERIA              | 46        | 52     | 1.05%   |
| Micron/Crucial Technology   | 42        | 57     | 0.96%   |
| Apple                       | 40        | 51     | 0.92%   |
| Silicon Motion              | 37        | 42     | 0.85%   |
| Phison                      | 31        | 32     | 0.71%   |
| Corsair                     | 29        | 39     | 0.66%   |
| HS-SSD-C100                 | 25        | 29     | 0.57%   |
| Unknown                     | 19        | 20     | 0.44%   |
| OCZ                         | 17        | 19     | 0.39%   |
| JAMESDONKEY                 | 17        | 18     | 0.39%   |
| Fujitsu                     | 16        | 16     | 0.37%   |
| Lexar                       | 15        | 21     | 0.34%   |
| JMicron Technology          | 15        | 15     | 0.34%   |
| ADATA Technology            | 15        | 22     | 0.34%   |
| Team                        | 14        | 14     | 0.32%   |
| Netac                       | 13        | 15     | 0.3%    |
| Intenso                     | 13        | 15     | 0.3%    |
| Gigabyte Technology         | 12        | 24     | 0.28%   |
| UMIS                        | 10        | 12     | 0.23%   |
| TwinMOS                     | 10        | 11     | 0.23%   |
| Transcend                   | 10        | 10     | 0.23%   |
| Realtek Semiconductor       | 10        | 11     | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 66        | 1.42%   |
| SanDisk SSD PLUS 240GB                             | 60        | 1.29%   |
| Seagate ST1000LM035-1RK172 1TB                     | 55        | 1.18%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 48        | 1.03%   |
| HGST HTS721010A9E630 1TB                           | 40        | 0.86%   |
| Unknown MMC Card  32GB                             | 34        | 0.73%   |
| Toshiba MQ01ABD100 1TB                             | 31        | 0.67%   |
| Samsung SSD 860 EVO 250GB                          | 31        | 0.67%   |
| Toshiba MQ01ABF050 500GB                           | 28        | 0.6%    |
| Sandisk WD Blue SN550 NVMe SSD 1024GB              | 28        | 0.6%    |
| Toshiba MQ04ABF100 1TB                             | 26        | 0.56%   |
| Seagate ST500DM002-1BD142 500GB                    | 26        | 0.56%   |
| Micron/Crucial P2 NVMe PCIe SSD 2TB                | 25        | 0.54%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 24        | 0.52%   |
| KIOXIA NVMe SSD 1TB                                | 23        | 0.49%   |
| Seagate ST1000DM010-2EP102 1TB                     | 22        | 0.47%   |
| Seagate ST500LT012-1DG142 500GB                    | 20        | 0.43%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 19        | 0.41%   |
| SanDisk NVMe SSD Drive 512GB                       | 19        | 0.41%   |
| Kingston SV300S37A120G 120GB SSD                   | 19        | 0.41%   |
| Kingston SA400S37240G 240GB SSD                    | 19        | 0.41%   |
| Unknown                                            | 19        | 0.41%   |
| WDC WD10EZEX-08WN4A0 1TB                           | 18        | 0.39%   |
| Unknown MMC Card  128GB                            | 18        | 0.39%   |
| SanDisk SSD PLUS 120GB                             | 18        | 0.39%   |
| Samsung SSD 870 EVO 500GB                          | 18        | 0.39%   |
| Samsung SSD 860 EVO 500GB                          | 18        | 0.39%   |
| Samsung NVMe SSD Drive 256GB                       | 18        | 0.39%   |
| Kingston Company SNV2S1000G 1TB                    | 18        | 0.39%   |
| Kingston SA400S37120G 120GB SSD                    | 18        | 0.39%   |
| Seagate ST9500325AS 500GB                          | 17        | 0.37%   |
| Seagate ST2000DM008-2FR102 2TB                     | 17        | 0.37%   |
| Seagate ST1000LM049-2GH172 1TB                     | 17        | 0.37%   |
| Samsung MZVLQ512HBLU-00B00 512GB                   | 17        | 0.37%   |
| Unknown MMC Card  64GB                             | 16        | 0.34%   |
| Toshiba MQ01ABD075 752GB                           | 16        | 0.34%   |
| SanDisk SSD PLUS 480GB                             | 16        | 0.34%   |
| KIOXIA-EXCERIA SATA SSD 480GB                      | 16        | 0.34%   |
| Silicon Motion PCIe-8 SSD 512GB                    | 15        | 0.32%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB   | 15        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives  | Percent |
|---------------------|-----------|---------|---------|
| Seagate             | 484       | 624     | 34.97%  |
| WDC                 | 373       | 545     | 26.95%  |
| Toshiba             | 219       | 252     | 15.82%  |
| Samsung Electronics | 97        | 128     | 7.01%   |
| HGST                | 79        | 94      | 5.71%   |
| Hitachi             | 77        | 87      | 5.56%   |
| Fujitsu             | 16        | 16      | 1.16%   |
| Unknown             | 11        | 15      | 0.79%   |
| Maxtor              | 6         | 6       | 0.43%   |
| Apple               | 6         | 10      | 0.43%   |
| JMicron Technology  | 5         | 5       | 0.36%   |
| USB3.0              | 2         | 2       | 0.14%   |
| Intenso             | 2         | 3       | 0.14%   |
| TO Exter            | 1         | 3       | 0.07%   |
| Initio              | 1         | Unknown | 0.07%   |
| HPE                 | 1         | 1       | 0.07%   |
| External            | 1         | 1       | 0.07%   |
| ExcelStor           | 1         | 1       | 0.07%   |
| China               | 1         | 1       | 0.07%   |
| 128MB               | 1         | 1       | 0.07%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 233       | 306    | 18.26%  |
| Samsung Electronics | 214       | 296    | 16.77%  |
| Kingston            | 160       | 216    | 12.54%  |
| China               | 70        | 78     | 5.49%   |
| WDC                 | 69        | 87     | 5.41%   |
| Crucial             | 50        | 64     | 3.92%   |
| A-DATA Technology   | 43        | 53     | 3.37%   |
| KIOXIA-EXCERIA      | 36        | 41     | 2.82%   |
| Toshiba             | 35        | 38     | 2.74%   |
| Micron Technology   | 24        | 29     | 1.88%   |
| Corsair             | 23        | 27     | 1.8%    |
| Apple               | 22        | 24     | 1.72%   |
| SK hynix            | 19        | 23     | 1.49%   |
| OCZ                 | 17        | 19     | 1.33%   |
| JAMESDONKEY         | 15        | 16     | 1.18%   |
| Netac               | 13        | 15     | 1.02%   |
| Lexar               | 13        | 19     | 1.02%   |
| Intel               | 13        | 20     | 1.02%   |
| HS-SSD-C100         | 12        | 16     | 0.94%   |
| Team                | 10        | 10     | 0.78%   |
| Intenso             | 10        | 11     | 0.78%   |
| Pioneer             | 9         | 25     | 0.71%   |
| LITEON              | 9         | 10     | 0.71%   |
| HI-LEVEL            | 9         | 11     | 0.71%   |
| TwinMOS             | 8         | 9      | 0.63%   |
| KingSpec            | 8         | 8      | 0.63%   |
| Hewlett-Packard     | 8         | 9      | 0.63%   |
| Gigabyte Technology | 8         | 19     | 0.63%   |
| Transcend           | 7         | 7      | 0.55%   |
| Seagate             | 7         | 8      | 0.55%   |
| EZCOOL              | 6         | 7      | 0.47%   |
| SPCC                | 5         | 5      | 0.39%   |
| LITEONIT            | 5         | 6      | 0.39%   |
| HS-SSD-E100         | 5         | 9      | 0.39%   |
| Unknown             | 5         | 5      | 0.39%   |
| PNY                 | 4         | 5      | 0.31%   |
| Patriot             | 4         | 5      | 0.31%   |
| KingFast            | 4         | 8      | 0.31%   |
| Apacer              | 4         | 4      | 0.31%   |
| Turbox              | 3         | 3      | 0.24%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 1373      | 1986   | 34.58%  |
| HDD     | 1234      | 1795   | 31.08%  |
| SSD     | 1145      | 1638   | 28.84%  |
| MMC     | 143       | 181    | 3.6%    |
| Unknown | 75        | 113    | 1.89%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1954      | 3386   | 54.63%  |
| NVMe | 1372      | 1981   | 38.36%  |
| MMC  | 143       | 181    | 4%      |
| SAS  | 108       | 165    | 3.02%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1505      | 2281   | 64.07%  |
| 0.51-1.0   | 662       | 875    | 28.18%  |
| 1.01-2.0   | 111       | 167    | 4.73%   |
| 3.01-4.0   | 38        | 57     | 1.62%   |
| 4.01-10.0  | 16        | 21     | 0.68%   |
| 2.01-3.0   | 13        | 23     | 0.55%   |
| 10.01-20.0 | 2         | 5      | 0.09%   |
| 0          | 2         | 4      | 0.09%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 918       | 27.53%  |
| 251-500        | 741       | 22.23%  |
| 501-1000       | 497       | 14.91%  |
| 1001-2000      | 267       | 8.01%   |
| 51-100         | 245       | 7.35%   |
| 1-20           | 225       | 6.75%   |
| 21-50          | 163       | 4.89%   |
| More than 3000 | 116       | 3.48%   |
| 2001-3000      | 100       | 3%      |
| Unknown        | 62        | 1.86%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1257      | 36.51%  |
| 21-50          | 698       | 20.27%  |
| 101-250        | 431       | 12.52%  |
| 51-100         | 410       | 11.91%  |
| 251-500        | 249       | 7.23%   |
| 501-1000       | 183       | 5.32%   |
| 1001-2000      | 91        | 2.64%   |
| Unknown        | 62        | 1.8%    |
| More than 3000 | 32        | 0.93%   |
| 2001-3000      | 27        | 0.78%   |
| 0              | 3         | 0.09%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 10        | 11     | 3.13%   |
| SanDisk SSD PLUS 240GB                | 8         | 9      | 2.5%    |
| Seagate ST500LT012-1DG142 500GB       | 6         | 10     | 1.88%   |
| Seagate ST1000LM035-1RK172 1TB        | 6         | 6      | 1.88%   |
| HGST HTS721010A9E630 1TB              | 6         | 7      | 1.88%   |
| Toshiba MQ01ABD100 1TB                | 5         | 5      | 1.56%   |
| Seagate ST9500325AS 500GB             | 5         | 7      | 1.56%   |
| Kingston SV300S37A120G 120GB SSD      | 5         | 6      | 1.56%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 4         | 5      | 1.25%   |
| Toshiba MQ01ABD075 752GB              | 4         | 4      | 1.25%   |
| Toshiba MQ01ABD050 500GB              | 4         | 6      | 1.25%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 4         | 4      | 1.25%   |
| Seagate ST1000LM014-SSHD-8GB          | 4         | 4      | 1.25%   |
| Seagate ST1000DM003-1SB102 1TB        | 4         | 5      | 1.25%   |
| Samsung Electronics SSD 870 EVO 500GB | 4         | 6      | 1.25%   |
| HGST HTS545050A7E680 500GB            | 4         | 4      | 1.25%   |
| WDC WD10JPVX-22JC3T0 1TB              | 3         | 3      | 0.94%   |
| Toshiba MQ01ABF050 500GB              | 3         | 4      | 0.94%   |
| Toshiba MK3252GSX 320GB               | 3         | 3      | 0.94%   |
| Toshiba DT01ACA050 500GB              | 3         | 3      | 0.94%   |
| Seagate ST9320325AS 320GB             | 3         | 3      | 0.94%   |
| Seagate ST500LT012-9WS142 500GB       | 3         | 3      | 0.94%   |
| Seagate ST2000DM008-2FR102 2TB        | 3         | 4      | 0.94%   |
| Seagate ST1000DM003-1CH162 1TB        | 3         | 4      | 0.94%   |
| Samsung Electronics HD161HJ 160GB     | 3         | 3      | 0.94%   |
| Kingston SUV400S37240G 240GB SSD      | 3         | 3      | 0.94%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 2         | 2      | 0.63%   |
| WDC WD3200BPVT-22JJ5T0 320GB          | 2         | 2      | 0.63%   |
| WDC WD10JPVX-75JC3T0 1TB              | 2         | 2      | 0.63%   |
| WDC WD10EZEX-08WN4A0 1TB              | 2         | 5      | 0.63%   |
| WDC WD10EZEX-08M2NA0 1TB              | 2         | 2      | 0.63%   |
| Toshiba MQ04ABF100 1TB                | 2         | 2      | 0.63%   |
| Toshiba MQ02ABD100H 1TB               | 2         | 4      | 0.63%   |
| Seagate ST9160821AS 160GB             | 2         | 2      | 0.63%   |
| Seagate ST3500630AS 500GB             | 2         | 2      | 0.63%   |
| Seagate ST3500418AS 500GB             | 2         | 4      | 0.63%   |
| Seagate ST320LT012-9WS14C 320GB       | 2         | 2      | 0.63%   |
| Seagate ST1000LM049-2GH172 1TB        | 2         | 2      | 0.63%   |
| SanDisk SDSSDX120GG25 120GB           | 2         | 2      | 0.63%   |
| SanDisk SDSSDA120G 120GB              | 2         | 2      | 0.63%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 80        | 100    | 25.72%  |
| WDC                 | 51        | 62     | 16.4%   |
| Toshiba             | 36        | 41     | 11.58%  |
| Samsung Electronics | 25        | 31     | 8.04%   |
| Hitachi             | 24        | 24     | 7.72%   |
| SanDisk             | 18        | 22     | 5.79%   |
| Kingston            | 14        | 15     | 4.5%    |
| HGST                | 14        | 15     | 4.5%    |
| A-DATA Technology   | 10        | 10     | 3.22%   |
| Fujitsu             | 5         | 5      | 1.61%   |
| SK hynix            | 4         | 5      | 1.29%   |
| Maxtor              | 3         | 3      | 0.96%   |
| Crucial             | 3         | 3      | 0.96%   |
| China               | 3         | 3      | 0.96%   |
| OCZ                 | 2         | 3      | 0.64%   |
| JMicron Technology  | 2         | 2      | 0.64%   |
| Indilinx            | 2         | 4      | 0.64%   |
| 2.5"                | 2         | 2      | 0.64%   |
| SSD-S400            | 1         | 1      | 0.32%   |
| Pioneer             | 1         | 1      | 0.32%   |
| Micron Technology   | 1         | 1      | 0.32%   |
| LITEONIT            | 1         | 2      | 0.32%   |
| LITEON              | 1         | 1      | 0.32%   |
| Lenovo              | 1         | 1      | 0.32%   |
| JD                  | 1         | 1      | 0.32%   |
| Intenso             | 1         | 1      | 0.32%   |
| Intel               | 1         | 1      | 0.32%   |
| HS-SSD-C100         | 1         | 1      | 0.32%   |
| Corsair             | 1         | 2      | 0.32%   |
| C-S12               | 1         | 1      | 0.32%   |
| Apple               | 1         | 2      | 0.32%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 80        | 100    | 35.87%  |
| WDC                 | 44        | 54     | 19.73%  |
| Toshiba             | 36        | 41     | 16.14%  |
| Hitachi             | 24        | 24     | 10.76%  |
| Samsung Electronics | 16        | 20     | 7.17%   |
| HGST                | 14        | 15     | 6.28%   |
| Fujitsu             | 5         | 5      | 2.24%   |
| Maxtor              | 3         | 3      | 1.35%   |
| Apple               | 1         | 2      | 0.45%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 209       | 264    | 70.37%  |
| SSD     | 76        | 90     | 25.59%  |
| NVMe    | 10        | 10     | 3.37%   |
| Unknown | 2         | 2      | 0.67%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| HGST HTS545050A7E680 500GB          | 2         | 2      | 28.57%  |
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 1      | 14.29%  |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1         | 1      | 14.29%  |
| Samsung Electronics HM160HI 160GB   | 1         | 1      | 14.29%  |
| Samsung Electronics HD322GJ 320GB   | 1         | 1      | 14.29%  |
| Crucial CT500P2SSD8 500GB           | 1         | 1      | 14.29%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2         | 2      | 28.57%  |
| Samsung Electronics | 2         | 2      | 28.57%  |
| HGST                | 2         | 2      | 28.57%  |
| Crucial             | 1         | 1      | 14.29%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1809      | 3191   | 53.57%  |
| Works    | 1273      | 2149   | 37.7%   |
| Malfunc  | 288       | 366    | 8.53%   |
| Failed   | 7         | 7      | 0.21%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 1878      | 47.17%  |
| AMD                                     | 515       | 12.94%  |
| Samsung Electronics                     | 420       | 10.55%  |
| SanDisk                                 | 216       | 5.43%   |
| Kingston Technology Company             | 119       | 2.99%   |
| SK hynix                                | 109       | 2.74%   |
| Micron Technology                       | 109       | 2.74%   |
| KIOXIA                                  | 91        | 2.29%   |
| Phison Electronics                      | 90        | 2.26%   |
| Micron/Crucial Technology               | 68        | 1.71%   |
| Silicon Motion                          | 47        | 1.18%   |
| Toshiba America Info Systems            | 35        | 0.88%   |
| ASMedia Technology                      | 31        | 0.78%   |
| ADATA Technology                        | 28        | 0.7%    |
| Nvidia                                  | 27        | 0.68%   |
| Marvell Technology Group                | 27        | 0.68%   |
| Union Memory (Shenzhen)                 | 23        | 0.58%   |
| JMicron Technology                      | 22        | 0.55%   |
| Solidigm                                | 19        | 0.48%   |
| Silicon Integrated Systems [SiS]        | 16        | 0.4%    |
| MAXIO Technology (Hangzhou)             | 16        | 0.4%    |
| Realtek Semiconductor                   | 15        | 0.38%   |
| Apple                                   | 11        | 0.28%   |
| Yangtze Memory Technologies             | 8         | 0.2%    |
| Seagate Technology                      | 5         | 0.13%   |
| VIA Technologies                        | 4         | 0.1%    |
| Solid State Storage Technology          | 4         | 0.1%    |
| Shenzhen Longsys Electronics            | 3         | 0.08%   |
| LSI Logic / Symbios Logic               | 3         | 0.08%   |
| Lite-On Technology                      | 3         | 0.08%   |
| Innodisk                                | 3         | 0.08%   |
| Adaptec                                 | 3         | 0.08%   |
| Transcend                               | 2         | 0.05%   |
| Lenovo                                  | 2         | 0.05%   |
| Biwin Storage Technology                | 2         | 0.05%   |
| ULi Electronics                         | 1         | 0.03%   |
| Shenzhen Unionmemory Information System | 1         | 0.03%   |
| Shenzhen Shichuangyi Electronics        | 1         | 0.03%   |
| Promise Technology                      | 1         | 0.03%   |
| OCZ Technology Group                    | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 312       | 7.03%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 152       | 3.42%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 150       | 3.38%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 142       | 3.2%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 119       | 2.68%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 115       | 2.59%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 103       | 2.32%   |
| AMD 400 Series Chipset SATA Controller                                         | 83        | 1.87%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 82        | 1.85%   |
| Intel Volume Management Device NVMe RAID Controller                            | 76        | 1.71%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 73        | 1.64%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 69        | 1.55%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 66        | 1.49%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 64        | 1.44%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 61        | 1.37%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 59        | 1.33%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 54        | 1.22%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 53        | 1.19%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 52        | 1.17%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 49        | 1.1%    |
| AMD 600 Series Chipset SATA Controller                                         | 49        | 1.1%    |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 47        | 1.06%   |
| Intel Comet Lake SATA AHCI Controller                                          | 46        | 1.04%   |
| Intel Tiger Lake-LP SATA Controller                                            | 43        | 0.97%   |
| AMD 500 Series Chipset SATA Controller                                         | 43        | 0.97%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 42        | 0.95%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 40        | 0.9%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 39        | 0.88%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 37        | 0.83%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 37        | 0.83%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 35        | 0.79%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 34        | 0.77%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 34        | 0.77%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 33        | 0.74%   |
| KIOXIA NVMe SSD                                                                | 33        | 0.74%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 32        | 0.72%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 29        | 0.65%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 28        | 0.63%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 27        | 0.61%   |
| Intel SSD 660P Series                                                          | 27        | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2072      | 52.35%  |
| NVMe | 1374      | 34.71%  |
| IDE  | 295       | 7.45%   |
| RAID | 212       | 5.36%   |
| SCSI | 4         | 0.1%    |
| SAS  | 1         | 0.03%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 2256      | 73.08%  |
| AMD          | 787       | 25.49%  |
| ARM          | 41        | 1.33%   |
| CentaurHauls | 2         | 0.06%   |
| Qualcomm     | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 56        | 1.81%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 50        | 1.62%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 41        | 1.33%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 35        | 1.13%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 30        | 0.97%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 30        | 0.97%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 29        | 0.94%   |
| ARM Processor                                 | 29        | 0.94%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 29        | 0.94%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 29        | 0.94%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 27        | 0.87%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 27        | 0.87%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 26        | 0.84%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 26        | 0.84%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 25        | 0.81%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 24        | 0.78%   |
| Intel 12th Gen Core i7-12700H                 | 24        | 0.78%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 23        | 0.74%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 23        | 0.74%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 23        | 0.74%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 22        | 0.71%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 22        | 0.71%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 22        | 0.71%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 21        | 0.68%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 21        | 0.68%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 21        | 0.68%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 20        | 0.65%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 20        | 0.65%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 19        | 0.61%   |
| Intel 12th Gen Core i5-12450H                 | 19        | 0.61%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 19        | 0.61%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 18        | 0.58%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 18        | 0.58%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 18        | 0.58%   |
| AMD Ryzen 5 3600 6-Core Processor             | 17        | 0.55%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 16        | 0.52%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 16        | 0.52%   |
| Intel 13th Gen Core i5-13500H                 | 16        | 0.52%   |
| Intel 12th Gen Core i5-1235U                  | 16        | 0.52%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 15        | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 644       | 20.83%  |
| Intel Core i7           | 549       | 17.76%  |
| Other                   | 439       | 14.2%   |
| AMD Ryzen 5             | 279       | 9.02%   |
| AMD Ryzen 7             | 207       | 6.69%   |
| Intel Core i3           | 189       | 6.11%   |
| Intel Celeron           | 105       | 3.4%    |
| Intel Core 2 Duo        | 96        | 3.1%    |
| Intel Atom              | 53        | 1.71%   |
| Intel Pentium           | 52        | 1.68%   |
| AMD Ryzen 9             | 45        | 1.46%   |
| AMD Ryzen 3             | 44        | 1.42%   |
| Intel Xeon              | 35        | 1.13%   |
| Intel Pentium Dual-Core | 30        | 0.97%   |
| AMD FX                  | 28        | 0.91%   |
| Intel Core 2 Quad       | 25        | 0.81%   |
| AMD A8                  | 25        | 0.81%   |
| Intel Core              | 23        | 0.74%   |
| AMD A10                 | 21        | 0.68%   |
| Intel Pentium Dual      | 19        | 0.61%   |
| Intel Core i9           | 18        | 0.58%   |
| Intel Core 2            | 17        | 0.55%   |
| AMD Ryzen 5 PRO         | 11        | 0.36%   |
| AMD Phenom II X4        | 10        | 0.32%   |
| AMD Ryzen 7 PRO         | 9         | 0.29%   |
| AMD A6                  | 9         | 0.29%   |
| AMD A4                  | 9         | 0.29%   |
| Intel Pentium Silver    | 7         | 0.23%   |
| AMD Athlon II X2        | 6         | 0.19%   |
| AMD Athlon              | 6         | 0.19%   |
| Intel Genuine           | 5         | 0.16%   |
| AMD C-60                | 5         | 0.16%   |
| AMD Athlon 64 X2        | 5         | 0.16%   |
| Intel Pentium 4         | 4         | 0.13%   |
| AMD E2                  | 4         | 0.13%   |
| AMD Athlon II X3        | 4         | 0.13%   |
| AMD A12                 | 4         | 0.13%   |
| Intel Pentium M         | 3         | 0.1%    |
| AMD Phenom II X6        | 3         | 0.1%    |
| AMD Phenom              | 3         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1065      | 34.43%  |
| 4       | 992       | 32.07%  |
| 6       | 411       | 13.29%  |
| 8       | 311       | 10.05%  |
| 14      | 65        | 2.1%    |
| 12      | 62        | 2%      |
| 10      | 62        | 2%      |
| 1       | 46        | 1.49%   |
| 16      | 33        | 1.07%   |
| 24      | 18        | 0.58%   |
| 3       | 16        | 0.52%   |
| 20      | 5         | 0.16%   |
| Unknown | 5         | 0.16%   |
| 64      | 1         | 0.03%   |
| 36      | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3072      | 99.51%  |
| 2       | 11        | 0.36%   |
| Unknown | 4         | 0.13%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2299      | 74.35%  |
| 1       | 785       | 25.39%  |
| Unknown | 5         | 0.16%   |
| 8       | 2         | 0.06%   |
| 4       | 1         | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3028      | 97.96%  |
| Unknown        | 44        | 1.42%   |
| 32-bit         | 17        | 0.55%   |
| 64-bit         | 2         | 0.06%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1628      | 50.75%  |
| 0x306a9    | 106       | 3.3%    |
| 0x206a7    | 105       | 3.27%   |
| 0x306c3    | 68        | 2.12%   |
| 0x1067a    | 57        | 1.78%   |
| 0x906e9    | 52        | 1.62%   |
| 0x40651    | 46        | 1.43%   |
| 0x806ea    | 43        | 1.34%   |
| 0x906ea    | 41        | 1.28%   |
| 0x806e9    | 39        | 1.22%   |
| 0x806c1    | 39        | 1.22%   |
| 0xa0652    | 37        | 1.15%   |
| 0x806ec    | 37        | 1.15%   |
| 0x306d4    | 36        | 1.12%   |
| 0x506e3    | 35        | 1.09%   |
| 0x20655    | 34        | 1.06%   |
| 0x406e3    | 33        | 1.03%   |
| 0x08108109 | 29        | 0.9%    |
| 0x6fd      | 28        | 0.87%   |
| 0x08608103 | 27        | 0.84%   |
| 0x08600106 | 27        | 0.84%   |
| 0x30678    | 23        | 0.72%   |
| 0x0a50000d | 22        | 0.69%   |
| 0x0a50000c | 22        | 0.69%   |
| 0x08108102 | 22        | 0.69%   |
| 0x706e5    | 21        | 0.65%   |
| 0x406c4    | 20        | 0.62%   |
| 0x20652    | 19        | 0.59%   |
| 0x10676    | 19        | 0.59%   |
| 0x906a3    | 18        | 0.56%   |
| 0x506c9    | 16        | 0.5%    |
| 0x08701021 | 16        | 0.5%    |
| 0x806d1    | 15        | 0.47%   |
| 0x06000852 | 15        | 0.47%   |
| 0x0800820d | 14        | 0.44%   |
| 0x906a4    | 12        | 0.37%   |
| 0x06006705 | 12        | 0.37%   |
| 0x6fb      | 11        | 0.34%   |
| 0x010000c8 | 11        | 0.34%   |
| 0x406c3    | 10        | 0.31%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KabyLake          | 432       | 13.91%  |
| Unknown           | 352       | 11.34%  |
| Haswell           | 209       | 6.73%   |
| IvyBridge         | 201       | 6.47%   |
| SandyBridge       | 188       | 6.05%   |
| Zen 3             | 141       | 4.54%   |
| Alderlake Hybrid  | 137       | 4.41%   |
| Zen 2             | 131       | 4.22%   |
| Penryn            | 130       | 4.19%   |
| Skylake           | 123       | 3.96%   |
| CometLake         | 113       | 3.64%   |
| TigerLake         | 109       | 3.51%   |
| Zen+              | 107       | 3.45%   |
| Westmere          | 92        | 2.96%   |
| Silvermont        | 82        | 2.64%   |
| Icelake           | 80        | 2.58%   |
| Core              | 69        | 2.22%   |
| Broadwell         | 62        | 2%      |
| Zen               | 51        | 1.64%   |
| Piledriver        | 43        | 1.38%   |
| K10               | 34        | 1.1%    |
| Goldmont plus     | 29        | 0.93%   |
| Excavator         | 29        | 0.93%   |
| Goldmont          | 24        | 0.77%   |
| Puma              | 22        | 0.71%   |
| Bonnell           | 18        | 0.58%   |
| Nehalem           | 15        | 0.48%   |
| Bobcat            | 12        | 0.39%   |
| Meteorlake Hybrid | 11        | 0.35%   |
| K8 Hammer         | 11        | 0.35%   |
| P6                | 8         | 0.26%   |
| Steamroller       | 7         | 0.23%   |
| K10 Llano         | 7         | 0.23%   |
| NetBurst          | 6         | 0.19%   |
| Lunarlake Hybrid  | 6         | 0.19%   |
| Tremont           | 4         | 0.13%   |
| Bulldozer         | 4         | 0.13%   |
| Jaguar            | 3         | 0.1%    |
| Gracemont         | 2         | 0.06%   |
| K6                | 1         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1801      | 43.94%  |
| Nvidia                           | 1259      | 30.71%  |
| AMD                              | 1018      | 24.84%  |
| Silicon Integrated Systems [SiS] | 13        | 0.32%   |
| VIA Technologies                 | 3         | 0.07%   |
| Matrox Electronics Systems       | 3         | 0.07%   |
| ASPEED Technology                | 2         | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 143       | 3.36%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 135       | 3.17%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 103       | 2.42%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 81        | 1.9%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 76        | 1.79%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 74        | 1.74%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 72        | 1.69%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 72        | 1.69%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 69        | 1.62%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 67        | 1.57%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 63        | 1.48%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 60        | 1.41%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 54        | 1.27%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 52        | 1.22%   |
| AMD Lucienne                                                                             | 52        | 1.22%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 49        | 1.15%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 46        | 1.08%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 45        | 1.06%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 44        | 1.03%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 44        | 1.03%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 43        | 1.01%   |
| Intel Kaby Lake-H GT2 [HD Graphics 630]                                                  | 42        | 0.99%   |
| Intel Core Processor Integrated Graphics Controller                                      | 42        | 0.99%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 42        | 0.99%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 41        | 0.96%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 41        | 0.96%   |
| Nvidia AD107M [GeForce RTX 4050 Max-Q / Mobile]                                          | 40        | 0.94%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 39        | 0.92%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 39        | 0.92%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                                          | 37        | 0.87%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 37        | 0.87%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 35        | 0.82%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 35        | 0.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 35        | 0.82%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 32        | 0.75%   |
| AMD Rembrandt [Radeon 680M]                                                              | 32        | 0.75%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 30        | 0.71%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 28        | 0.66%   |
| Intel Skylake-H GT2 [HD Graphics 530]                                                    | 28        | 0.66%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 27        | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 880       | 28.29%  |
| Intel + Nvidia  | 722       | 23.21%  |
| 1 x AMD         | 609       | 19.58%  |
| 1 x Nvidia      | 406       | 13.05%  |
| Intel + AMD     | 167       | 5.37%   |
| AMD + Nvidia    | 133       | 4.28%   |
| 2 x AMD         | 113       | 3.63%   |
| Other           | 47        | 1.51%   |
| 1 x SiS         | 13        | 0.42%   |
| 2 x Intel       | 9         | 0.29%   |
| 2 x Nvidia      | 3         | 0.1%    |
| 1 x VIA         | 3         | 0.1%    |
| 1 x Matrox      | 3         | 0.1%    |
| 1 x ASPEED      | 2         | 0.06%   |
| Intel + 2 x AMD | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2372      | 75.21%  |
| Proprietary | 573       | 18.17%  |
| Unknown     | 209       | 6.63%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1866      | 58.42%  |
| 1.01-2.0   | 360       | 11.27%  |
| 0.01-0.5   | 292       | 9.14%   |
| 3.01-4.0   | 231       | 7.23%   |
| 0.51-1.0   | 223       | 6.98%   |
| 7.01-8.0   | 81        | 2.54%   |
| 5.01-6.0   | 73        | 2.29%   |
| 8.01-16.0  | 45        | 1.41%   |
| 2.01-3.0   | 15        | 0.47%   |
| 16.01-24.0 | 6         | 0.19%   |
| 4.01-5.0   | 1         | 0.03%   |
| 24.01-32.0 | 1         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 462       | 14.02%  |
| AU Optronics            | 437       | 13.26%  |
| Chimei Innolux          | 353       | 10.71%  |
| Samsung Electronics     | 346       | 10.5%   |
| LG Display              | 345       | 10.47%  |
| Goldstar                | 117       | 3.55%   |
| Philips                 | 92        | 2.79%   |
| Dell                    | 80        | 2.43%   |
| Apple                   | 68        | 2.06%   |
| Lenovo                  | 67        | 2.03%   |
| Hewlett-Packard         | 64        | 1.94%   |
| ASUSTek Computer        | 64        | 1.94%   |
| Acer                    | 63        | 1.91%   |
| Ancor Communications    | 62        | 1.88%   |
| AOC                     | 57        | 1.73%   |
| Chi Mei Optoelectronics | 56        | 1.7%    |
| ViewSonic               | 55        | 1.67%   |
| PANDA                   | 50        | 1.52%   |
| MSI                     | 38        | 1.15%   |
| Sharp                   | 29        | 0.88%   |
| BenQ                    | 27        | 0.82%   |
| Unknown                 | 16        | 0.49%   |
| Vestel Elektronik       | 15        | 0.46%   |
| InfoVision              | 15        | 0.46%   |
| LG Philips              | 14        | 0.42%   |
| CSO                     | 13        | 0.39%   |
| Sony                    | 11        | 0.33%   |
| HKC                     | 10        | 0.3%    |
| CPT                     | 10        | 0.3%    |
| SAC                     | 9         | 0.27%   |
| Beko                    | 9         | 0.27%   |
| TMX                     | 8         | 0.24%   |
| LG Electronics          | 8         | 0.24%   |
| Fujitsu Siemens         | 8         | 0.24%   |
| SANYO                   | 7         | 0.21%   |
| EDO                     | 7         | 0.21%   |
| AGO                     | 7         | 0.21%   |
| VIE                     | 6         | 0.18%   |
| Valve                   | 6         | 0.18%   |
| Mi                      | 6         | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 36        | 1.07%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 32        | 0.95%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 27        | 0.8%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 27        | 0.8%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 26        | 0.77%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 24        | 0.71%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 24        | 0.71%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 20        | 0.59%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 19        | 0.56%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 19        | 0.56%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 19        | 0.56%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 15        | 0.45%   |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 880x500mm 39.8-inch     | 14        | 0.42%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 14        | 0.42%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 14        | 0.42%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 13        | 0.39%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 13        | 0.39%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch           | 13        | 0.39%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 11        | 0.33%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 11        | 0.33%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 11        | 0.33%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 10        | 0.3%    |
| BOE LCD Monitor BOE0B9F 1920x1080 355x200mm 16.0-inch                    | 10        | 0.3%    |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 10        | 0.3%    |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch            | 10        | 0.3%    |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 10        | 0.3%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 9         | 0.27%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 9         | 0.27%   |
| BOE LCD Monitor BOE08D5 1920x1080 344x194mm 15.5-inch                    | 9         | 0.27%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                    | 9         | 0.27%   |
| BOE LCD Monitor BOE07CB 1920x1080 344x193mm 15.5-inch                    | 9         | 0.27%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 9         | 0.27%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 8         | 0.24%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch                  | 8         | 0.24%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 8         | 0.24%   |
| LG Display LCD Monitor LGD02AC 1366x768 344x194mm 15.5-inch              | 8         | 0.24%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch              | 8         | 0.24%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 8         | 0.24%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 8         | 0.24%   |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                    | 8         | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1520      | 48.8%   |
| 1366x768 (WXGA)    | 707       | 22.7%   |
| 3840x2160 (4K)     | 135       | 4.33%   |
| 2560x1440 (QHD)    | 130       | 4.17%   |
| 1920x1200 (WUXGA)  | 84        | 2.7%    |
| 1600x900 (HD+)     | 64        | 2.05%   |
| 1440x900 (WXGA+)   | 59        | 1.89%   |
| 1280x800 (WXGA)    | 54        | 1.73%   |
| 1280x1024 (SXGA)   | 46        | 1.48%   |
| 2560x1600          | 39        | 1.25%   |
| Unknown            | 36        | 1.16%   |
| 1680x1050 (WSXGA+) | 34        | 1.09%   |
| 2880x1800          | 28        | 0.9%    |
| 2560x1080          | 20        | 0.64%   |
| 2160x1440          | 20        | 0.64%   |
| 3440x1440          | 16        | 0.51%   |
| 1360x768           | 14        | 0.45%   |
| 1024x600           | 12        | 0.39%   |
| 3840x1080          | 11        | 0.35%   |
| 2288x1287          | 8         | 0.26%   |
| 2520x1680          | 7         | 0.22%   |
| 800x1280           | 6         | 0.19%   |
| 1920x540           | 6         | 0.19%   |
| 1024x768 (XGA)     | 6         | 0.19%   |
| 3200x1800 (QHD+)   | 5         | 0.16%   |
| 3000x2120          | 4         | 0.13%   |
| 3072x1920          | 3         | 0.1%    |
| 2944x1840          | 3         | 0.1%    |
| 2880x1620          | 3         | 0.1%    |
| 1680x945           | 3         | 0.1%    |
| 4480x1440          | 2         | 0.06%   |
| 3840x2400          | 2         | 0.06%   |
| 3240x2160          | 2         | 0.06%   |
| 3200x2000          | 2         | 0.06%   |
| 3000x2000          | 2         | 0.06%   |
| 2880x1920          | 2         | 0.06%   |
| 800x600            | 1         | 0.03%   |
| 7920x1440          | 1         | 0.03%   |
| 6000x1440          | 1         | 0.03%   |
| 5760x2160          | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1282      | 38.94%  |
| 13      | 256       | 7.78%   |
| 27      | 193       | 5.86%   |
| 23      | 187       | 5.68%   |
| 14      | 181       | 5.5%    |
| 21      | 162       | 4.92%   |
| 24      | 160       | 4.86%   |
| 17      | 136       | 4.13%   |
| 16      | 119       | 3.61%   |
| Unknown | 100       | 3.04%   |
| 18      | 74        | 2.25%   |
| 31      | 61        | 1.85%   |
| 19      | 49        | 1.49%   |
| 12      | 40        | 1.22%   |
| 11      | 40        | 1.22%   |
| 20      | 35        | 1.06%   |
| 34      | 27        | 0.82%   |
| 22      | 23        | 0.7%    |
| 84      | 20        | 0.61%   |
| 10      | 19        | 0.58%   |
| 72      | 15        | 0.46%   |
| 26      | 13        | 0.39%   |
| 32      | 11        | 0.33%   |
| 142     | 7         | 0.21%   |
| 63      | 7         | 0.21%   |
| 54      | 6         | 0.18%   |
| 43      | 6         | 0.18%   |
| 40      | 6         | 0.18%   |
| 28      | 6         | 0.18%   |
| 7       | 6         | 0.18%   |
| 46      | 5         | 0.15%   |
| 67      | 4         | 0.12%   |
| 57      | 4         | 0.12%   |
| 52      | 4         | 0.12%   |
| 86      | 3         | 0.09%   |
| 48      | 3         | 0.09%   |
| 33      | 3         | 0.09%   |
| 29      | 3         | 0.09%   |
| 65      | 2         | 0.06%   |
| 60      | 2         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1640      | 50.37%  |
| 501-600        | 500       | 15.36%  |
| 401-500        | 337       | 10.35%  |
| 201-300        | 244       | 7.49%   |
| 351-400        | 193       | 5.93%   |
| Unknown        | 100       | 3.07%   |
| 601-700        | 92        | 2.83%   |
| 701-800        | 46        | 1.41%   |
| 1001-1500      | 40        | 1.23%   |
| 1501-2000      | 35        | 1.07%   |
| 901-1000       | 8         | 0.25%   |
| More than 2000 | 7         | 0.21%   |
| 801-900        | 7         | 0.21%   |
| 1-100          | 6         | 0.18%   |
| 101-200        | 1         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2393      | 81.15%  |
| 16/10   | 308       | 10.44%  |
| Unknown | 84        | 2.85%   |
| 3/2     | 45        | 1.53%   |
| 5/4     | 38        | 1.29%   |
| 21/9    | 30        | 1.02%   |
| 4/3     | 23        | 0.78%   |
| 1.00    | 7         | 0.24%   |
| 32/9    | 6         | 0.2%    |
| 0.67    | 5         | 0.17%   |
| 0.45    | 4         | 0.14%   |
| 0.56    | 3         | 0.1%    |
| 6/5     | 2         | 0.07%   |
| 0.62    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1320      | 40.38%  |
| 201-250        | 437       | 13.37%  |
| 81-90          | 329       | 10.06%  |
| 301-350        | 203       | 6.21%   |
| 151-200        | 132       | 4.04%   |
| 351-500        | 110       | 3.36%   |
| 71-80          | 109       | 3.33%   |
| 121-130        | 109       | 3.33%   |
| Unknown        | 100       | 3.06%   |
| 141-150        | 91        | 2.78%   |
| More than 1000 | 76        | 2.32%   |
| 111-120        | 69        | 2.11%   |
| 251-300        | 41        | 1.25%   |
| 51-60          | 40        | 1.22%   |
| 61-70          | 31        | 0.95%   |
| 501-1000       | 26        | 0.8%    |
| 41-50          | 19        | 0.58%   |
| 91-100         | 14        | 0.43%   |
| 1-40           | 7         | 0.21%   |
| 131-140        | 6         | 0.18%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 1111      | 34.68%  |
| 51-100        | 845       | 26.37%  |
| 101-120       | 813       | 25.37%  |
| 161-240       | 227       | 7.08%   |
| Unknown       | 100       | 3.12%   |
| 1-50          | 58        | 1.81%   |
| More than 240 | 50        | 1.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 2546      | 80.29%  |
| 2     | 450       | 14.19%  |
| 0     | 146       | 4.6%    |
| 3     | 28        | 0.88%   |
| 4     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2031      | 42.14%  |
| Intel                                  | 1252      | 25.98%  |
| Qualcomm Atheros                       | 510       | 10.58%  |
| Broadcom                               | 251       | 5.21%   |
| MediaTek                               | 164       | 3.4%    |
| Ralink Technology                      | 86        | 1.78%   |
| Broadcom Limited                       | 51        | 1.06%   |
| Ralink                                 | 48        | 1%      |
| Marvell Technology Group               | 42        | 0.87%   |
| TP-Link                                | 40        | 0.83%   |
| ASUSTek Computer                       | 35        | 0.73%   |
| Samsung Electronics                    | 32        | 0.66%   |
| Xiaomi                                 | 27        | 0.56%   |
| Qualcomm Atheros Communications        | 26        | 0.54%   |
| Nvidia                                 | 24        | 0.5%    |
| Silicon Integrated Systems [SiS]       | 17        | 0.35%   |
| ASIX Electronics                       | 17        | 0.35%   |
| Shenzhen Goodix Technology             | 14        | 0.29%   |
| Qualcomm                               | 11        | 0.23%   |
| Huawei Technologies                    | 9         | 0.19%   |
| Aquantia                               | 9         | 0.19%   |
| ZyXEL Communications                   | 8         | 0.17%   |
| JMicron Technology                     | 7         | 0.15%   |
| Ericsson Business Mobile Networks      | 7         | 0.15%   |
| Apple                                  | 7         | 0.15%   |
| ICS Advent                             | 6         | 0.12%   |
| Edimax Technology                      | 6         | 0.12%   |
| Dell                                   | 5         | 0.1%    |
| Qualcomm Technologies                  | 4         | 0.08%   |
| Microchip Technology                   | 4         | 0.08%   |
| Lenovo                                 | 4         | 0.08%   |
| AirTies Wireless Networks              | 4         | 0.08%   |
| Suzhou Motorcomm Electronic Technology | 3         | 0.06%   |
| Sierra Wireless                        | 3         | 0.06%   |
| Raspberry Pi                           | 3         | 0.06%   |
| QinHeng Electronics                    | 3         | 0.06%   |
| Fibocom                                | 3         | 0.06%   |
| Attansic Technology                    | 3         | 0.06%   |
| U-Blox                                 | 2         | 0.04%   |
| Tenda                                  | 2         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 1390      | 25.19%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 249       | 4.51%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 114       | 2.07%   |
| Realtek RTL8125 2.5GbE Controller                                      | 100       | 1.81%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 95        | 1.72%   |
| Intel Wi-Fi 6 AX200                                                    | 94        | 1.7%    |
| Intel Wi-Fi 6 AX201                                                    | 88        | 1.6%    |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]   | 84        | 1.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 80        | 1.45%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 77        | 1.4%    |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 76        | 1.38%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 68        | 1.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 66        | 1.2%    |
| Intel Wireless 7265                                                    | 61        | 1.11%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 61        | 1.11%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 60        | 1.09%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 58        | 1.05%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 53        | 0.96%   |
| Intel Wireless 8265 / 8275                                             | 51        | 0.92%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 50        | 0.91%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 47        | 0.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 45        | 0.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 42        | 0.76%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 41        | 0.74%   |
| Broadcom BCM43142 802.11b/g/n                                          | 40        | 0.73%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 39        | 0.71%   |
| Ralink MT7601U Wireless Adapter                                        | 38        | 0.69%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 37        | 0.67%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 37        | 0.67%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 36        | 0.65%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 32        | 0.58%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 32        | 0.58%   |
| Intel Wireless 3165                                                    | 30        | 0.54%   |
| Intel Wireless 3160                                                    | 30        | 0.54%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 29        | 0.53%   |
| Intel Wireless 7260                                                    | 29        | 0.53%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 28        | 0.51%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 27        | 0.49%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 27        | 0.49%   |
| Intel Ethernet Connection (2) I219-V                                   | 26        | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1052      | 39.71%  |
| Realtek Semiconductor            | 544       | 20.54%  |
| Qualcomm Atheros                 | 391       | 14.76%  |
| Broadcom                         | 192       | 7.25%   |
| MediaTek                         | 146       | 5.51%   |
| Ralink Technology                | 86        | 3.25%   |
| Ralink                           | 48        | 1.81%   |
| Broadcom Limited                 | 38        | 1.43%   |
| TP-Link                          | 37        | 1.4%    |
| ASUSTek Computer                 | 35        | 1.32%   |
| Qualcomm Atheros Communications  | 26        | 0.98%   |
| ZyXEL Communications             | 8         | 0.3%    |
| Qualcomm                         | 6         | 0.23%   |
| Marvell Technology Group         | 6         | 0.23%   |
| Edimax Technology                | 6         | 0.23%   |
| Dell                             | 4         | 0.15%   |
| AirTies Wireless Networks        | 4         | 0.15%   |
| Sierra Wireless                  | 3         | 0.11%   |
| Fibocom                          | 3         | 0.11%   |
| Tenda                            | 2         | 0.08%   |
| Mercucys                         | 2         | 0.08%   |
| Accton Technology                | 2         | 0.08%   |
| Wilocity                         | 1         | 0.04%   |
| Silicon Integrated Systems [SiS] | 1         | 0.04%   |
| Qcom                             | 1         | 0.04%   |
| NetGear                          | 1         | 0.04%   |
| Microsoft                        | 1         | 0.04%   |
| Linksys                          | 1         | 0.04%   |
| IMC Networks                     | 1         | 0.04%   |
| Belkin Components                | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 114       | 4.29%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 95        | 3.57%   |
| Intel Wi-Fi 6 AX200                                                  | 94        | 3.54%   |
| Intel Wi-Fi 6 AX201                                                  | 88        | 3.31%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330] | 84        | 3.16%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 80        | 3.01%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 77        | 2.9%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 68        | 2.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 66        | 2.48%   |
| Intel Wireless 7265                                                  | 61        | 2.29%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 61        | 2.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 60        | 2.26%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 58        | 2.18%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 53        | 1.99%   |
| Intel Wireless 8265 / 8275                                           | 51        | 1.92%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 48        | 1.81%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 45        | 1.69%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 43        | 1.62%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 42        | 1.58%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 41        | 1.54%   |
| Broadcom BCM43142 802.11b/g/n                                        | 40        | 1.5%    |
| Ralink MT7601U Wireless Adapter                                      | 38        | 1.43%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 38        | 1.43%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 37        | 1.39%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 37        | 1.39%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 32        | 1.2%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 32        | 1.2%    |
| Intel Wireless 3165                                                  | 30        | 1.13%   |
| Intel Wireless 3160                                                  | 30        | 1.13%   |
| Intel Wireless 7260                                                  | 29        | 1.09%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 28        | 1.05%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 27        | 1.02%   |
| Intel Wireless 8260                                                  | 23        | 0.87%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                      | 21        | 0.79%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 21        | 0.79%   |
| Realtek RTL8723DE Wireless Network Adapter                           | 20        | 0.75%   |
| Intel 700 Series Chipset CNVi WiFi                                   | 20        | 0.75%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 19        | 0.71%   |
| Qualcomm Atheros AR9271 802.11n                                      | 19        | 0.71%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 18        | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1838      | 66.62%  |
| Intel                                  | 381       | 13.81%  |
| Qualcomm Atheros                       | 176       | 6.38%   |
| Broadcom                               | 102       | 3.7%    |
| Marvell Technology Group               | 36        | 1.3%    |
| Samsung Electronics                    | 32        | 1.16%   |
| Xiaomi                                 | 27        | 0.98%   |
| Nvidia                                 | 23        | 0.83%   |
| ASIX Electronics                       | 17        | 0.62%   |
| Silicon Integrated Systems [SiS]       | 16        | 0.58%   |
| MediaTek                               | 15        | 0.54%   |
| Broadcom Limited                       | 13        | 0.47%   |
| Aquantia                               | 9         | 0.33%   |
| Huawei Technologies                    | 8         | 0.29%   |
| JMicron Technology                     | 7         | 0.25%   |
| Apple                                  | 7         | 0.25%   |
| ICS Advent                             | 6         | 0.22%   |
| Qualcomm                               | 5         | 0.18%   |
| Qualcomm Technologies                  | 4         | 0.14%   |
| Microchip Technology                   | 4         | 0.14%   |
| TP-Link                                | 3         | 0.11%   |
| Suzhou Motorcomm Electronic Technology | 3         | 0.11%   |
| Raspberry Pi                           | 3         | 0.11%   |
| Lenovo                                 | 3         | 0.11%   |
| Attansic Technology                    | 3         | 0.11%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.07%   |
| OPPO Electronics                       | 2         | 0.07%   |
| Motorola PCS                           | 2         | 0.07%   |
| VIA Technologies                       | 1         | 0.04%   |
| ULi Electronics                        | 1         | 0.04%   |
| T & A Mobile Phones                    | 1         | 0.04%   |
| QinHeng Electronics                    | 1         | 0.04%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.04%   |
| Mellanox Technologies                  | 1         | 0.04%   |
| LSI                                    | 1         | 0.04%   |
| Insyde Software                        | 1         | 0.04%   |
| HTC (High Tech Computer)               | 1         | 0.04%   |
| Google                                 | 1         | 0.04%   |
| DisplayLink                            | 1         | 0.04%   |
| Davicom Semiconductor                  | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 1390      | 49.43%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 249       | 8.85%   |
| Realtek RTL8125 2.5GbE Controller                                      | 100       | 3.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 39        | 1.39%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 36        | 1.28%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 33        | 1.17%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 29        | 1.03%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 27        | 0.96%   |
| Intel Ethernet Connection (2) I219-V                                   | 26        | 0.92%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 24        | 0.85%   |
| Realtek Killer E2600 GbE Controller                                    | 21        | 0.75%   |
| Intel I211 Gigabit Network Connection                                  | 21        | 0.75%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 19        | 0.68%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 18        | 0.64%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 17        | 0.6%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 17        | 0.6%    |
| Intel Ethernet Connection (4) I219-LM                                  | 17        | 0.6%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 16        | 0.57%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 16        | 0.57%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 16        | 0.57%   |
| Intel 82579V Gigabit Network Connection                                | 15        | 0.53%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 14        | 0.5%    |
| Intel Ethernet Controller I225-V                                       | 14        | 0.5%    |
| ASIX AX88179 Gigabit Ethernet                                          | 14        | 0.5%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 13        | 0.46%   |
| Intel Ethernet Connection I217-LM                                      | 13        | 0.46%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 12        | 0.43%   |
| Intel Ethernet Connection (3) I218-LM                                  | 12        | 0.43%   |
| Intel Ethernet Connection I217-V                                       | 11        | 0.39%   |
| Intel Ethernet Connection (14) I219-V                                  | 11        | 0.39%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                        | 11        | 0.39%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 10        | 0.36%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 10        | 0.36%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 10        | 0.36%   |
| Intel Ethernet Connection (11) I219-V                                  | 10        | 0.36%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 10        | 0.36%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 9         | 0.32%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 9         | 0.32%   |
| Nvidia MCP61 Ethernet                                                  | 9         | 0.32%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 9         | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2605      | 50.54%  |
| WiFi     | 2503      | 48.56%  |
| Modem    | 37        | 0.72%   |
| Unknown  | 9         | 0.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2051      | 65.42%  |
| Ethernet | 1084      | 34.58%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1852      | 59.84%  |
| 1     | 1112      | 35.93%  |
| 0     | 82        | 2.65%   |
| 3     | 40        | 1.29%   |
| 4     | 5         | 0.16%   |
| 5     | 2         | 0.06%   |
| 16    | 1         | 0.03%   |
| 7     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2980      | 96.01%  |
| Yes  | 124       | 3.99%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 946       | 42.48%  |
| Realtek Semiconductor           | 269       | 12.08%  |
| IMC Networks                    | 205       | 9.21%   |
| Qualcomm Atheros Communications | 143       | 6.42%   |
| Foxconn / Hon Hai               | 105       | 4.71%   |
| Cambridge Silicon Radio         | 100       | 4.49%   |
| Lite-On Technology              | 78        | 3.5%    |
| Broadcom                        | 75        | 3.37%   |
| Apple                           | 56        | 2.51%   |
| Realtek                         | 41        | 1.84%   |
| Toshiba                         | 32        | 1.44%   |
| Ralink                          | 32        | 1.44%   |
| ASUSTek Computer                | 32        | 1.44%   |
| MediaTek                        | 23        | 1.03%   |
| TP-Link                         | 22        | 0.99%   |
| Dell                            | 21        | 0.94%   |
| Hewlett-Packard                 | 16        | 0.72%   |
| Foxconn International           | 6         | 0.27%   |
| Marvell Semiconductor           | 5         | 0.22%   |
| Ralink Technology               | 4         | 0.18%   |
| Integrated System Solution      | 3         | 0.13%   |
| Alps Electric                   | 3         | 0.13%   |
| Unknown                         | 2         | 0.09%   |
| USI                             | 1         | 0.04%   |
| Quectel Wireless Solutions      | 1         | 0.04%   |
| Qcom                            | 1         | 0.04%   |
| Mercucys                        | 1         | 0.04%   |
| Logitech                        | 1         | 0.04%   |
| HTC (High Tech Computer)        | 1         | 0.04%   |
| Edimax Technology               | 1         | 0.04%   |
| Actions                         | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 264       | 11.84%  |
| Intel Bluetooth wireless interface                  | 247       | 11.08%  |
| Realtek Bluetooth Radio                             | 192       | 8.61%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 145       | 6.51%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 100       | 4.49%   |
| Intel AX200 Bluetooth                               | 92        | 4.13%   |
| Intel Bluetooth Device                              | 89        | 3.99%   |
| IMC Networks Wireless_Device                        | 70        | 3.14%   |
| Qualcomm Atheros  Bluetooth Device                  | 63        | 2.83%   |
| IMC Networks Bluetooth Radio                        | 62        | 2.78%   |
| Realtek  Bluetooth 4.2 Adapter                      | 44        | 1.97%   |
| Realtek Bluetooth Radio                             | 41        | 1.84%   |
| Intel Wireless-AC 3168 Bluetooth                    | 35        | 1.57%   |
| Apple Bluetooth Host Controller                     | 33        | 1.48%   |
| Ralink RT3290 Bluetooth                             | 32        | 1.44%   |
| Foxconn / Hon Hai Wireless_Device                   | 28        | 1.26%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 27        | 1.21%   |
| IMC Networks Bluetooth Device                       | 25        | 1.12%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 24        | 1.08%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 23        | 1.03%   |
| TP-Link TP-T@- UB500 Adapter                        | 22        | 0.99%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 21        | 0.94%   |
| MediaTek Wireless_Device                            | 21        | 0.94%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 21        | 0.94%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 20        | 0.9%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 19        | 0.85%   |
| Lite-On Bluetooth Device                            | 18        | 0.81%   |
| Intel AX210 Bluetooth                               | 18        | 0.81%   |
| Lite-On Wireless_Device                             | 16        | 0.72%   |
| Foxconn / Hon Hai Bluetooth Device                  | 16        | 0.72%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 15        | 0.67%   |
| Apple Bluetooth USB Host Controller                 | 15        | 0.67%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 13        | 0.58%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 13        | 0.58%   |
| IMC Networks Bluetooth                              | 13        | 0.58%   |
| IMC Networks Bluetooth USB Host Controller          | 12        | 0.54%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 12        | 0.54%   |
| Realtek RTL8723B Bluetooth                          | 10        | 0.45%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 9         | 0.4%    |
| Broadcom BCM43142 Bluetooth 4.0                     | 9         | 0.4%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 2178      | 50.38%  |
| AMD                                  | 979       | 22.65%  |
| Nvidia                               | 836       | 19.34%  |
| C-Media Electronics                  | 37        | 0.86%   |
| SteelSeries ApS                      | 20        | 0.46%   |
| Barco Display Systems                | 18        | 0.42%   |
| Silicon Integrated Systems [SiS]     | 16        | 0.37%   |
| Logitech                             | 16        | 0.37%   |
| ASUSTek Computer                     | 16        | 0.37%   |
| Generalplus Technology               | 15        | 0.35%   |
| Kingston Technology                  | 13        | 0.3%    |
| JMTek                                | 13        | 0.3%    |
| Micro Star International             | 11        | 0.25%   |
| Texas Instruments                    | 9         | 0.21%   |
| Creative Labs                        | 9         | 0.21%   |
| Apple                                | 9         | 0.21%   |
| Tenx Technology                      | 8         | 0.19%   |
| Hewlett-Packard                      | 7         | 0.16%   |
| GN Netcom                            | 7         | 0.16%   |
| Realtek Semiconductor                | 6         | 0.14%   |
| VIA Technologies                     | 5         | 0.12%   |
| Razer USA                            | 5         | 0.12%   |
| Creative Technology                  | 5         | 0.12%   |
| Corsair                              | 5         | 0.12%   |
| Sony                                 | 4         | 0.09%   |
| Focusrite-Novation                   | 4         | 0.09%   |
| Yamaha                               | 3         | 0.07%   |
| Trust                                | 3         | 0.07%   |
| Thesycon Systemsoftware & Consulting | 3         | 0.07%   |
| M-Audio                              | 3         | 0.07%   |
| KTMicro                              | 3         | 0.07%   |
| Earth Computer Technologies          | 3         | 0.07%   |
| DSEA A/S                             | 3         | 0.07%   |
| RODE Microphones                     | 2         | 0.05%   |
| Plantronics                          | 2         | 0.05%   |
| LG Electronics                       | 2         | 0.05%   |
| Lenovo                               | 2         | 0.05%   |
| JBL                                  | 2         | 0.05%   |
| GYROCOM C&C                          | 2         | 0.05%   |
| Elite Silicon                        | 2         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                              | 443       | 8.57%   |
| Intel Sunrise Point-LP HD Audio                                            | 211       | 4.08%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 206       | 3.98%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 191       | 3.69%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 186       | 3.6%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 111       | 2.15%   |
| AMD Radeon High Definition Audio Controller                                | 110       | 2.13%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 109       | 2.11%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 97        | 1.88%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 95        | 1.84%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 93        | 1.8%    |
| Intel Comet Lake PCH cAVS                                                  | 93        | 1.8%    |
| Intel Cannon Lake PCH cAVS                                                 | 89        | 1.72%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 87        | 1.68%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 84        | 1.62%   |
| Intel Haswell-ULT HD Audio Controller                                      | 82        | 1.59%   |
| Intel 8 Series HD Audio Controller                                         | 82        | 1.59%   |
| AMD Starship/Matisse HD Audio Controller                                   | 81        | 1.57%   |
| Nvidia AD107 High Definition Audio Controller                              | 80        | 1.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 79        | 1.53%   |
| Nvidia GF108 High Definition Audio Controller                              | 73        | 1.41%   |
| Nvidia GP107GL High Definition Audio Controller                            | 71        | 1.37%   |
| Nvidia GA107 High Definition Audio Controller                              | 70        | 1.35%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 68        | 1.32%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 67        | 1.3%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 66        | 1.28%   |
| AMD FCH Azalia Controller                                                  | 60        | 1.16%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 59        | 1.14%   |
| Intel Broadwell-U Audio Controller                                         | 59        | 1.14%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 57        | 1.1%    |
| Intel Raptor Lake-P/U/H cAVS                                               | 56        | 1.08%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 56        | 1.08%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 54        | 1.04%   |
| Nvidia TU116 High Definition Audio Controller                              | 53        | 1.03%   |
| Intel Comet Lake PCH-LP cAVS                                               | 50        | 0.97%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 48        | 0.93%   |
| Nvidia GA106 High Definition Audio Controller                              | 46        | 0.89%   |
| Intel CM238 HD Audio Controller                                            | 45        | 0.87%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 45        | 0.87%   |
| Intel 200 Series PCH HD Audio                                              | 41        | 0.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 519       | 25.89%  |
| SK hynix            | 326       | 16.26%  |
| Kingston            | 269       | 13.42%  |
| Micron Technology   | 207       | 10.32%  |
| Unknown             | 158       | 7.88%   |
| Crucial             | 116       | 5.79%   |
| G.Skill             | 72        | 3.59%   |
| Corsair             | 64        | 3.19%   |
| A-DATA Technology   | 49        | 2.44%   |
| Unknown             | 41        | 2.04%   |
| Ramaxel Technology  | 31        | 1.55%   |
| Nanya Technology    | 26        | 1.3%    |
| Elpida              | 19        | 0.95%   |
| Team                | 14        | 0.7%    |
| Unknown (ABCD)      | 10        | 0.5%    |
| Transcend           | 9         | 0.45%   |
| Apacer              | 8         | 0.4%    |
| Goldkey             | 7         | 0.35%   |
| Timetec             | 6         | 0.3%    |
| Neo Forza           | 5         | 0.25%   |
| Hikvision           | 5         | 0.25%   |
| ChangXin Memory     | 4         | 0.2%    |
| Avant               | 3         | 0.15%   |
| Patriot             | 2         | 0.1%    |
| Kllisre             | 2         | 0.1%    |
| Gold Key            | 2         | 0.1%    |
| ff                  | 2         | 0.1%    |
| ASint Technology    | 2         | 0.1%    |
| AMD                 | 2         | 0.1%    |
| 4ea5                | 2         | 0.1%    |
| 48spaces            | 2         | 0.1%    |
| Wilk                | 1         | 0.05%   |
| Unknown (F288)      | 1         | 0.05%   |
| Unknown (0x4509)    | 1         | 0.05%   |
| Unknown (0x29E)     | 1         | 0.05%   |
| Unknown (0B38)      | 1         | 0.05%   |
| Unknown (07FB)      | 1         | 0.05%   |
| Unifosa             | 1         | 0.05%   |
| Silicon Power       | 1         | 0.05%   |
| Shenzhen Longsys    | 1         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Unknown                                                      | 41        | 1.91%   |
| Samsung RAM M471A1G44AB0-CWE 8GiB SODIMM DDR4 3200MT/s       | 31        | 1.45%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s        | 23        | 1.07%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s        | 21        | 0.98%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 19        | 0.89%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s        | 19        | 0.89%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s       | 18        | 0.84%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 18        | 0.84%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s        | 18        | 0.84%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s  | 15        | 0.7%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s  | 14        | 0.65%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s | 13        | 0.61%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 13        | 0.61%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 8400MT/s        | 13        | 0.61%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s         | 13        | 0.61%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s       | 12        | 0.56%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s        | 12        | 0.56%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s      | 12        | 0.56%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s        | 11        | 0.51%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s        | 11        | 0.51%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                 | 10        | 0.47%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 10        | 0.47%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 10        | 0.47%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 10        | 0.47%   |
| Samsung RAM M425R1GB4BB0-CWMOD 8GB SODIMM DDR5 5600MT/s      | 10        | 0.47%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s         | 10        | 0.47%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s        | 10        | 0.47%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 9         | 0.42%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s       | 9         | 0.42%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s       | 9         | 0.42%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 9         | 0.42%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s        | 9         | 0.42%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s       | 9         | 0.42%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 9         | 0.42%   |
| Unknown RAM Module 4GB SODIMM DDR3                           | 8         | 0.37%   |
| Samsung RAM U6E3S4AA-MGCR 1GB Row Of Chips LPDDR4 4267MT/s   | 8         | 0.37%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s       | 8         | 0.37%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s         | 8         | 0.37%   |
| Unknown RAM Module 4GB DIMM SDRAM                            | 7         | 0.33%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s       | 7         | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 865       | 50.7%   |
| DDR3    | 441       | 25.85%  |
| DDR5    | 119       | 6.98%   |
| LPDDR4  | 62        | 3.63%   |
| SDRAM   | 48        | 2.81%   |
| LPDDR5  | 45        | 2.64%   |
| DDR2    | 42        | 2.46%   |
| Unknown | 40        | 2.34%   |
| LPDDR3  | 30        | 1.76%   |
| DDR     | 9         | 0.53%   |
| DRAM    | 4         | 0.23%   |
| EEPROM  | 1         | 0.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1135      | 66.96%  |
| DIMM         | 378       | 22.3%   |
| Row Of Chips | 172       | 10.15%  |
| Unknown      | 6         | 0.35%   |
| Chip         | 3         | 0.18%   |
| RIMM         | 1         | 0.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 8192    | 758       | 39.94%  |
| 4096    | 464       | 24.45%  |
| 16384   | 316       | 16.65%  |
| 2048    | 187       | 9.85%   |
| 32768   | 109       | 5.74%   |
| 1024    | 48        | 2.53%   |
| 512     | 5         | 0.26%   |
| 49152   | 3         | 0.16%   |
| 1536    | 2         | 0.11%   |
| 65536   | 1         | 0.05%   |
| 24576   | 1         | 0.05%   |
| 6144    | 1         | 0.05%   |
| 256     | 1         | 0.05%   |
| 1       | 1         | 0.05%   |
| Unknown | 1         | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 447       | 24.27%  |
| 1600    | 297       | 16.12%  |
| 2667    | 241       | 13.08%  |
| 2400    | 111       | 6.03%   |
| 1333    | 72        | 3.91%   |
| 2133    | 64        | 3.47%   |
| Unknown | 50        | 2.71%   |
| 3600    | 49        | 2.66%   |
| 5600    | 48        | 2.61%   |
| 1334    | 48        | 2.61%   |
| 4800    | 43        | 2.33%   |
| 667     | 32        | 1.74%   |
| 6400    | 31        | 1.68%   |
| 1867    | 24        | 1.3%    |
| 4267    | 23        | 1.25%   |
| 800     | 23        | 1.25%   |
| 4199    | 21        | 1.14%   |
| 1067    | 21        | 1.14%   |
| 8400    | 19        | 1.03%   |
| 3733    | 12        | 0.65%   |
| 3400    | 10        | 0.54%   |
| 6000    | 9         | 0.49%   |
| 4266    | 9         | 0.49%   |
| 4000    | 9         | 0.49%   |
| 8533    | 8         | 0.43%   |
| 3466    | 7         | 0.38%   |
| 3266    | 7         | 0.38%   |
| 3000    | 7         | 0.38%   |
| 1866    | 7         | 0.38%   |
| 7500    | 6         | 0.33%   |
| 6200    | 6         | 0.33%   |
| 1066    | 6         | 0.33%   |
| 3066    | 5         | 0.27%   |
| 2048    | 5         | 0.27%   |
| 400     | 5         | 0.27%   |
| 8000    | 4         | 0.22%   |
| 7467    | 4         | 0.22%   |
| 3800    | 4         | 0.22%   |
| 2933    | 4         | 0.22%   |
| 2666    | 4         | 0.22%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 22        | 35.48%  |
| Canon                  | 15        | 24.19%  |
| Seiko Epson            | 8         | 12.9%   |
| Zebra                  | 4         | 6.45%   |
| Samsung Electronics    | 4         | 6.45%   |
| Brother Industries     | 3         | 4.84%   |
| Oki Data               | 2         | 3.23%   |
| XiaoMi                 | 1         | 1.61%   |
| Xerox                  | 1         | 1.61%   |
| TSC Auto ID Technology | 1         | 1.61%   |
| QinHeng Electronics    | 1         | 1.61%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Zebra TLP2844                        | 3         | 4.76%   |
| HP Officejet 4500 G510g-m            | 3         | 4.76%   |
| HP HP LaserJet M101-M106             | 3         | 4.76%   |
| Canon E410 series                    | 3         | 4.76%   |
| Seiko Epson L3110 Series             | 2         | 3.17%   |
| Seiko Epson ET-2710 Series           | 2         | 3.17%   |
| Samsung M2020 Series                 | 2         | 3.17%   |
| HP LaserJet P2055 series             | 2         | 3.17%   |
| HP LaserJet P1102                    | 2         | 3.17%   |
| HP LaserJet 1020                     | 2         | 3.17%   |
| HP LaserJet 1010                     | 2         | 3.17%   |
| Canon LBP6030/6030B/6018L            | 2         | 3.17%   |
| Canon CAPT USB Device                | 2         | 3.17%   |
| Zebra Zebra GC420d Label Printer     | 1         | 1.59%   |
| XiaoMi MIIIW MECH-KBPro              | 1         | 1.59%   |
| Xerox Phaser 3160                    | 1         | 1.59%   |
| TSC Auto ID Printer                  | 1         | 1.59%   |
| Seiko Epson L405 Series              | 1         | 1.59%   |
| Seiko Epson L380 Series              | 1         | 1.59%   |
| Seiko Epson L210 Series              | 1         | 1.59%   |
| Seiko Epson FX-2190IIN               | 1         | 1.59%   |
| Samsung ML-216x Series Laser Printer | 1         | 1.59%   |
| Samsung CLP-325 Color Laser Printer  | 1         | 1.59%   |
| QinHeng CH340S                       | 1         | 1.59%   |
| Oki Data Oki_ML3320                  | 1         | 1.59%   |
| Oki Data Oki Printer                 | 1         | 1.59%   |
| HP Smart Tank 610 series             | 1         | 1.59%   |
| HP Smart Tank 510 series             | 1         | 1.59%   |
| HP LaserJet P1005                    | 1         | 1.59%   |
| HP DeskJet Plus 4100 series          | 1         | 1.59%   |
| HP DeskJet F2100 Printer series      | 1         | 1.59%   |
| HP DeskJet 3830 series               | 1         | 1.59%   |
| HP DeskJet 2600 series               | 1         | 1.59%   |
| HP DeskJet 2130 series               | 1         | 1.59%   |
| HP Deskjet 1050 J410                 | 1         | 1.59%   |
| Canon PIXMA MX340                    | 1         | 1.59%   |
| Canon PIXMA MG3000 series            | 1         | 1.59%   |
| Canon LBP6000                        | 1         | 1.59%   |
| Canon imageRUNNER1133 series         | 1         | 1.59%   |
| Canon G3020 series                   | 1         | 1.59%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Canon          | 2         | 66.67%  |
| Mustek Systems | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Canon CanoScan LiDE 210            | 2         | 66.67%  |
| Mustek Systems ScanExpress 1200 UB | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 484       | 22.55%  |
| IMC Networks                           | 240       | 11.18%  |
| Bison Electronics                      | 186       | 8.67%   |
| Quanta                                 | 171       | 7.97%   |
| Realtek Semiconductor                  | 160       | 7.46%   |
| Microdia                               | 115       | 5.36%   |
| Cheng Uei Precision Industry (Foxlink) | 90        | 4.19%   |
| Sunplus Innovation Technology          | 78        | 3.63%   |
| Luxvisions Innotech Limited            | 72        | 3.36%   |
| Syntek                                 | 69        | 3.22%   |
| Apple                                  | 51        | 2.38%   |
| Suyin                                  | 49        | 2.28%   |
| Logitech                               | 37        | 1.72%   |
| Sonix Technology                       | 34        | 1.58%   |
| Silicon Motion                         | 34        | 1.58%   |
| Alcor Micro                            | 29        | 1.35%   |
| Lite-On Technology                     | 28        | 1.3%    |
| Z-Star Microelectronics                | 22        | 1.03%   |
| Acer                                   | 18        | 0.84%   |
| Samsung Electronics                    | 15        | 0.7%    |
| ShineTech                              | 13        | 0.61%   |
| Ricoh                                  | 12        | 0.56%   |
| Importek                               | 10        | 0.47%   |
| ALi                                    | 10        | 0.47%   |
| kingcome                               | 8         | 0.37%   |
| Sunwingroup                            | 6         | 0.28%   |
| SenseTek                               | 6         | 0.28%   |
| SunplusIT                              | 4         | 0.19%   |
| Shine-optics                           | 4         | 0.19%   |
| Novatek Microelectronics               | 4         | 0.19%   |
| Microsoft                              | 4         | 0.19%   |
| MacroSilicon                           | 4         | 0.19%   |
| Lenovo                                 | 4         | 0.19%   |
| HYGD-221208-J                          | 4         | 0.19%   |
| Genesys Logic                          | 4         | 0.19%   |
| Foxconn / Hon Hai                      | 4         | 0.19%   |
| Sunplus IT                             | 3         | 0.14%   |
| LG Electronics                         | 3         | 0.14%   |
| Jieli Technology                       | 3         | 0.14%   |
| Generalplus Technology                 | 3         | 0.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 79        | 3.66%   |
| Chicony HD Webcam                                    | 66        | 3.06%   |
| IMC Networks Integrated Camera                       | 62        | 2.87%   |
| Microdia Integrated_Webcam_HD                        | 53        | 2.46%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 52        | 2.41%   |
| Bison Integrated Camera                              | 48        | 2.22%   |
| Syntek Integrated Camera                             | 43        | 1.99%   |
| Realtek Integrated_Webcam_HD                         | 37        | 1.71%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 33        | 1.53%   |
| IMC Networks HD Camera                               | 28        | 1.3%    |
| Chicony USB2.0 VGA UVC WebCam                        | 25        | 1.16%   |
| Bison HD Webcam                                      | 25        | 1.16%   |
| Sonix USB2.0 HD UVC WebCam                           | 22        | 1.02%   |
| Quanta USB HD Webcam                                 | 20        | 0.93%   |
| Chicony USB2.0 HD UVC WebCam                         | 20        | 0.93%   |
| Bison Lenovo EasyCamera                              | 20        | 0.93%   |
| Quanta HD User Facing                                | 19        | 0.88%   |
| Luxvisions Innotech Limited Integrated Camera        | 19        | 0.88%   |
| Chicony HP HD Camera                                 | 19        | 0.88%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 18        | 0.83%   |
| Chicony TOSHIBA Web Camera - HD                      | 18        | 0.83%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                      | 18        | 0.83%   |
| IMC Networks ov9734_azurewave_camera                 | 17        | 0.79%   |
| Chicony HD User Facing                               | 17        | 0.79%   |
| Quanta HP Wide Vision HD Camera                      | 16        | 0.74%   |
| Quanta HP TrueVision HD Camera                       | 16        | 0.74%   |
| Chicony Chicony USB2.0 Camera                        | 16        | 0.74%   |
| Bison SunplusIT Integrated Camera                    | 16        | 0.74%   |
| Sunplus Integrated_Webcam_HD                         | 15        | 0.7%    |
| Samsung Galaxy series, misc. (MTP mode)              | 15        | 0.7%    |
| Chicony HP Wide Vision HD Camera                     | 15        | 0.7%    |
| Bison BisonCam,NB Pro                                | 15        | 0.7%    |
| Realtek USB2.0 VGA UVC WebCam                        | 14        | 0.65%   |
| Quanta HD Webcam                                     | 14        | 0.65%   |
| Chicony EasyCamera                                   | 14        | 0.65%   |
| Sunplus Asus Webcam                                  | 13        | 0.6%    |
| Realtek USB Camera                                   | 13        | 0.6%    |
| Quanta ov9734_techfront_camera                       | 13        | 0.6%    |
| Quanta ACER HD User Facing                           | 13        | 0.6%    |
| Bison BisonCam, NB Pro                               | 13        | 0.6%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Shenzhen Goodix Technology         | 109       | 39.35%  |
| Synaptics                          | 69        | 24.91%  |
| Validity Sensors                   | 48        | 17.33%  |
| LighTuning Technology              | 19        | 6.86%   |
| AuthenTec                          | 13        | 4.69%   |
| Upek                               | 10        | 3.61%   |
| Elan Microelectronics              | 6         | 2.17%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.72%   |
| DigitalPersona                     | 1         | 0.36%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 86        | 31.05%  |
| Shenzhen Goodix Fingerprint Reader                                         | 22        | 7.94%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 18        | 6.5%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 14        | 5.05%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 10        | 3.61%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 10        | 3.61%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 9         | 3.25%   |
| Synaptics  WBDI                                                            | 8         | 2.89%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 8         | 2.89%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 7         | 2.53%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 6         | 2.17%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 6         | 2.17%   |
| Validity Sensors Fingerprint scanner                                       | 6         | 2.17%   |
| Synaptics WBDI                                                             | 5         | 1.81%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 5         | 1.81%   |
| Synaptics UWP WBDI                                                         | 4         | 1.44%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 1.44%   |
| Synaptics Fingerprint reader [HP G6]                                       | 4         | 1.44%   |
| AuthenTec AES2810                                                          | 4         | 1.44%   |
| Validity Sensors VFS491                                                    | 3         | 1.08%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 1.08%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 1.08%   |
| Elan ELAN:Fingerprint                                                      | 3         | 1.08%   |
| Elan ELAN:ARM-M4                                                           | 3         | 1.08%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 3         | 1.08%   |
| AuthenTec AES1600                                                          | 3         | 1.08%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 0.72%   |
| Synaptics Prometheus Fingerprint Reader                                    | 2         | 0.72%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 2         | 0.72%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 0.72%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.36%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.36%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.36%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.36%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 0.36%   |
| Synaptics UWP WBDI Device                                                  | 1         | 0.36%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.36%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.36%   |
| DigitalPersona Fingerprint Reader                                          | 1         | 0.36%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.36%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 26        | 35.62%  |
| Alcor Micro               | 25        | 34.25%  |
| Advanced Card Systems     | 8         | 10.96%  |
| Upek                      | 4         | 5.48%   |
| O2 Micro                  | 4         | 5.48%   |
| Lenovo                    | 3         | 4.11%   |
| Gemalto (was Gemplus)     | 2         | 2.74%   |
| SANHO Digital Electronics | 1         | 1.37%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 25        | 33.78%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 9         | 12.16%  |
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 8.11%   |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard)  | 5         | 6.76%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 5         | 6.76%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 5.41%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 5.41%   |
| Advanced Card Systems ACR39U                                                 | 4         | 5.41%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 4.05%   |
| Broadcom 5880                                                                | 3         | 4.05%   |
| Broadcom 58200                                                               | 3         | 4.05%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 2         | 2.7%    |
| SANHO Digital Electronics ATR19                                              | 1         | 1.35%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2197      | 69.13%  |
| 1     | 794       | 24.98%  |
| 2     | 157       | 4.94%   |
| 3     | 18        | 0.57%   |
| 4     | 7         | 0.22%   |
| 6     | 2         | 0.06%   |
| 5     | 2         | 0.06%   |
| 9     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 370       | 31.9%   |
| Fingerprint reader       | 276       | 23.79%  |
| Net/wireless             | 103       | 8.88%   |
| Multimedia controller    | 92        | 7.93%   |
| Camera                   | 68        | 5.86%   |
| Chipcard                 | 58        | 5%      |
| Bluetooth                | 51        | 4.4%    |
| Communication controller | 47        | 4.05%   |
| Net/ethernet             | 24        | 2.07%   |
| Sound                    | 21        | 1.81%   |
| Network                  | 13        | 1.12%   |
| Unassigned class         | 10        | 0.86%   |
| Storage                  | 10        | 0.86%   |
| Card reader              | 7         | 0.6%    |
| Storage/raid             | 3         | 0.26%   |
| Storage/ata              | 2         | 0.17%   |
| Flash memory             | 2         | 0.17%   |
| Wireless                 | 1         | 0.09%   |
| Storage/ide              | 1         | 0.09%   |
| Modem                    | 1         | 0.09%   |

