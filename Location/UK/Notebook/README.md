Linux in UK - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------

A project to collect tested hardware configurations for Linux in UK.

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

Total: 5285

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | EliteBook 8470p             | [f75b4a9457](https://linux-hardware.org/?probe=f75b4a9457) | May 01, 2023 |
| Toshiba       | EQUIUM P200                 | [812a164a8a](https://linux-hardware.org/?probe=812a164a8a) | Apr 30, 2023 |
| Lenovo        | ThinkPad X230 2325V1K       | [d630569df9](https://linux-hardware.org/?probe=d630569df9) | Apr 30, 2023 |
| Lenovo        | ThinkPad L480 20LTS1NK27    | [dff6f75899](https://linux-hardware.org/?probe=dff6f75899) | Apr 30, 2023 |
| Lenovo        | ThinkPad E580 20KS001JUK    | [da5f050510](https://linux-hardware.org/?probe=da5f050510) | Apr 29, 2023 |
| Lenovo        | ThinkPad E580 20KS001JUK    | [1e65b46a12](https://linux-hardware.org/?probe=1e65b46a12) | Apr 29, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [f2ad30321e](https://linux-hardware.org/?probe=f2ad30321e) | Apr 29, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [58bb30861d](https://linux-hardware.org/?probe=58bb30861d) | Apr 29, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [e70d66b3ba](https://linux-hardware.org/?probe=e70d66b3ba) | Apr 29, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [d364cb5ac7](https://linux-hardware.org/?probe=d364cb5ac7) | Apr 28, 2023 |
| HP            | ENVY Notebook               | [89e8149d6e](https://linux-hardware.org/?probe=89e8149d6e) | Apr 28, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [2dc65d8f07](https://linux-hardware.org/?probe=2dc65d8f07) | Apr 28, 2023 |
| Dell          | XPS 13 9350                 | [9d6905e35d](https://linux-hardware.org/?probe=9d6905e35d) | Apr 28, 2023 |
| Lenovo        | ThinkPad L480 20LTS1NK27    | [6569669912](https://linux-hardware.org/?probe=6569669912) | Apr 28, 2023 |
| Dell          | Latitude E7450              | [6afa2ff009](https://linux-hardware.org/?probe=6afa2ff009) | Apr 28, 2023 |
| Valve         | Jupiter                     | [0958caf898](https://linux-hardware.org/?probe=0958caf898) | Apr 27, 2023 |
| Lenovo        | Legion 7-16-ITHg6 82K6      | [2baf2cbc85](https://linux-hardware.org/?probe=2baf2cbc85) | Apr 27, 2023 |
| Lenovo        | ThinkPad X230 2325O32       | [b38ef1a717](https://linux-hardware.org/?probe=b38ef1a717) | Apr 27, 2023 |
| Acer          | Nitro AN515-57              | [d2ed10f8b1](https://linux-hardware.org/?probe=d2ed10f8b1) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [6704ecd3d3](https://linux-hardware.org/?probe=6704ecd3d3) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [4e8b00c534](https://linux-hardware.org/?probe=4e8b00c534) | Apr 27, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | [e35780d356](https://linux-hardware.org/?probe=e35780d356) | Apr 26, 2023 |
| Acer          | Aspire A514-54              | [19ca73662f](https://linux-hardware.org/?probe=19ca73662f) | Apr 25, 2023 |
| Google        | Sasuke                      | [7615a1b1e5](https://linux-hardware.org/?probe=7615a1b1e5) | Apr 25, 2023 |
| Dell          | XPS 13 9380                 | [290a99fee9](https://linux-hardware.org/?probe=290a99fee9) | Apr 25, 2023 |
| HP            | ProBook 640 G1              | [9306db1f90](https://linux-hardware.org/?probe=9306db1f90) | Apr 25, 2023 |
| Dell          | Latitude XT2                | [62df7dc069](https://linux-hardware.org/?probe=62df7dc069) | Apr 24, 2023 |
| Dell          | Inspiron 5565               | [6622474d4b](https://linux-hardware.org/?probe=6622474d4b) | Apr 24, 2023 |
| Apple         | MacBookPro5,5               | [de825a326c](https://linux-hardware.org/?probe=de825a326c) | Apr 24, 2023 |
| Acer          | Aspire A317-53              | [c47ec3530e](https://linux-hardware.org/?probe=c47ec3530e) | Apr 24, 2023 |
| HP            | Stream Notebook PC 13       | [455c6b5e28](https://linux-hardware.org/?probe=455c6b5e28) | Apr 23, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | [982ca9079d](https://linux-hardware.org/?probe=982ca9079d) | Apr 23, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [25e942e55c](https://linux-hardware.org/?probe=25e942e55c) | Apr 22, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C3C... | [b37a4411c5](https://linux-hardware.org/?probe=b37a4411c5) | Apr 22, 2023 |
| TUXEDO        | Pulse 15 Gen2               | [fd2ad16b59](https://linux-hardware.org/?probe=fd2ad16b59) | Apr 22, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [936e6fc768](https://linux-hardware.org/?probe=936e6fc768) | Apr 22, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [e0763f0f69](https://linux-hardware.org/?probe=e0763f0f69) | Apr 22, 2023 |
| Lenovo        | Legion 7 15IMH05 81YT       | [2727f5c463](https://linux-hardware.org/?probe=2727f5c463) | Apr 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [a02462f614](https://linux-hardware.org/?probe=a02462f614) | Apr 21, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [dfbfce9d2e](https://linux-hardware.org/?probe=dfbfce9d2e) | Apr 21, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [66f95f2851](https://linux-hardware.org/?probe=66f95f2851) | Apr 21, 2023 |
| Google        | Swanky                      | [92156daf53](https://linux-hardware.org/?probe=92156daf53) | Apr 21, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [2afe988f2e](https://linux-hardware.org/?probe=2afe988f2e) | Apr 20, 2023 |
| LG Electro... | 17Z90P-K.AA78A1             | [f8f6ec2123](https://linux-hardware.org/?probe=f8f6ec2123) | Apr 20, 2023 |
| ASUSTek       | X550CA                      | [cb5f73ff63](https://linux-hardware.org/?probe=cb5f73ff63) | Apr 20, 2023 |
| Lenovo        | ThinkPad T530 24292DG       | [1ba852f185](https://linux-hardware.org/?probe=1ba852f185) | Apr 20, 2023 |
| Dell          | Inspiron 1545               | [68a7470480](https://linux-hardware.org/?probe=68a7470480) | Apr 19, 2023 |
| HP            | ProBook 4540s               | [1bf512ee24](https://linux-hardware.org/?probe=1bf512ee24) | Apr 19, 2023 |
| Toshiba       | Satellite Pro C850-1HE      | [48d3d92f3d](https://linux-hardware.org/?probe=48d3d92f3d) | Apr 19, 2023 |
| Dell          | Vostro 5471                 | [5cbbc95995](https://linux-hardware.org/?probe=5cbbc95995) | Apr 19, 2023 |
| Dell          | G5 5590                     | [c7334114be](https://linux-hardware.org/?probe=c7334114be) | Apr 18, 2023 |
| Dell          | Inspiron 7559               | [9c66c608f3](https://linux-hardware.org/?probe=9c66c608f3) | Apr 18, 2023 |
| HP            | Laptop 15-da1xxx            | [c7a5aadd85](https://linux-hardware.org/?probe=c7a5aadd85) | Apr 18, 2023 |
| LG Electro... | 17Z90Q-K.AA78A1             | [594a7fa16b](https://linux-hardware.org/?probe=594a7fa16b) | Apr 18, 2023 |
| Sony          | SVF1521Q1EW                 | [4be523b9a9](https://linux-hardware.org/?probe=4be523b9a9) | Apr 18, 2023 |
| ASUSTek       | X550LD                      | [5c07d2203c](https://linux-hardware.org/?probe=5c07d2203c) | Apr 17, 2023 |
| Sony          | SVE1711C5E                  | [e4fbd8fca9](https://linux-hardware.org/?probe=e4fbd8fca9) | Apr 17, 2023 |
| Dell          | XPS 17 9700                 | [3ad1ee8197](https://linux-hardware.org/?probe=3ad1ee8197) | Apr 16, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [2092251807](https://linux-hardware.org/?probe=2092251807) | Apr 16, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [9b05d61f11](https://linux-hardware.org/?probe=9b05d61f11) | Apr 16, 2023 |
| HP            | ProBook 450 G1              | [000e6c6702](https://linux-hardware.org/?probe=000e6c6702) | Apr 16, 2023 |
| HONOR         | BBR-WAX9                    | [a56688fd70](https://linux-hardware.org/?probe=a56688fd70) | Apr 16, 2023 |
| HONOR         | BBR-WAX9                    | [798405022f](https://linux-hardware.org/?probe=798405022f) | Apr 16, 2023 |
| HP            | 250 G4 Notebook PC          | [08036de728](https://linux-hardware.org/?probe=08036de728) | Apr 15, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [2e860ef402](https://linux-hardware.org/?probe=2e860ef402) | Apr 15, 2023 |
| Acer          | Aspire A317-53              | [11b817e884](https://linux-hardware.org/?probe=11b817e884) | Apr 15, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [aedbc43074](https://linux-hardware.org/?probe=aedbc43074) | Apr 15, 2023 |
| HP            | Pavilion g6                 | [a918284993](https://linux-hardware.org/?probe=a918284993) | Apr 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [19fc60d2a5](https://linux-hardware.org/?probe=19fc60d2a5) | Apr 14, 2023 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | [f5940f5ed5](https://linux-hardware.org/?probe=f5940f5ed5) | Apr 14, 2023 |
| Dell          | XPS 15 7590                 | [f3248c9bca](https://linux-hardware.org/?probe=f3248c9bca) | Apr 14, 2023 |
| Clevo         | W760T/M740T/M760T           | [0dfaa8f0e8](https://linux-hardware.org/?probe=0dfaa8f0e8) | Apr 14, 2023 |
| Unknown       | Unknown                     | [7bd7802e04](https://linux-hardware.org/?probe=7bd7802e04) | Apr 14, 2023 |
| HUAWEI        | MRG-WXX                     | [56c255e5f0](https://linux-hardware.org/?probe=56c255e5f0) | Apr 14, 2023 |
| Lenovo        | Flex 2-14 20404             | [c76a516113](https://linux-hardware.org/?probe=c76a516113) | Apr 14, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [bd9c1c1e6d](https://linux-hardware.org/?probe=bd9c1c1e6d) | Apr 14, 2023 |
| HP            | Notebook                    | [79541411b2](https://linux-hardware.org/?probe=79541411b2) | Apr 14, 2023 |
| Unknown       | Unknown                     | [cfe1766d1a](https://linux-hardware.org/?probe=cfe1766d1a) | Apr 13, 2023 |
| Unknown       | Unknown                     | [7ff7c0642f](https://linux-hardware.org/?probe=7ff7c0642f) | Apr 13, 2023 |
| Acer          | Aspire A315-51              | [c3962286cb](https://linux-hardware.org/?probe=c3962286cb) | Apr 13, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | [abf6dd7200](https://linux-hardware.org/?probe=abf6dd7200) | Apr 13, 2023 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [aa571700ad](https://linux-hardware.org/?probe=aa571700ad) | Apr 13, 2023 |
| Lenovo        | ThinkPad T530 24292DG       | [9ac01d9237](https://linux-hardware.org/?probe=9ac01d9237) | Apr 13, 2023 |
| Apple         | MacBookPro5,5               | [401c4d8143](https://linux-hardware.org/?probe=401c4d8143) | Apr 12, 2023 |
| Sony          | SVE1711C5E                  | [07c6f843fb](https://linux-hardware.org/?probe=07c6f843fb) | Apr 12, 2023 |
| Toshiba       | Satellite C660              | [551fabbc17](https://linux-hardware.org/?probe=551fabbc17) | Apr 12, 2023 |
| Dell          | XPS 13 9305                 | [48b143cc2f](https://linux-hardware.org/?probe=48b143cc2f) | Apr 12, 2023 |
| Google        | Gnawty                      | [ddb0fea339](https://linux-hardware.org/?probe=ddb0fea339) | Apr 12, 2023 |
| Dell          | Latitude E5450              | [f98cdf4da0](https://linux-hardware.org/?probe=f98cdf4da0) | Apr 11, 2023 |
| Dell          | Latitude E5450              | [7bf04cdb7d](https://linux-hardware.org/?probe=7bf04cdb7d) | Apr 11, 2023 |
| MSI           | Stealth 14Studio A13VF      | [8297ce2712](https://linux-hardware.org/?probe=8297ce2712) | Apr 11, 2023 |
| MSI           | Stealth 14Studio A13VF      | [e3fc8c8f43](https://linux-hardware.org/?probe=e3fc8c8f43) | Apr 11, 2023 |
| Gigabyte      | MMLP3AP-00                  | [6fd82ceaec](https://linux-hardware.org/?probe=6fd82ceaec) | Apr 09, 2023 |
| lapbook       | S15 PRO                     | [5a039fc6fb](https://linux-hardware.org/?probe=5a039fc6fb) | Apr 09, 2023 |
| Lenovo        | ThinkPad T61 7661WQQ        | [8def87668b](https://linux-hardware.org/?probe=8def87668b) | Apr 09, 2023 |
| HP            | EliteBook 2560p             | [bc5cbcd2cb](https://linux-hardware.org/?probe=bc5cbcd2cb) | Apr 09, 2023 |
| Lenovo        | ThinkPad T480 20L50000UK    | [9f2644807d](https://linux-hardware.org/?probe=9f2644807d) | Apr 09, 2023 |
| Dell          | Inspiron 7570               | [2bac711aba](https://linux-hardware.org/?probe=2bac711aba) | Apr 09, 2023 |
| Acer          | Aspire A317-53              | [7dc7e5e5c3](https://linux-hardware.org/?probe=7dc7e5e5c3) | Apr 09, 2023 |
| Acer          | Aspire A317-53              | [b1c4404d58](https://linux-hardware.org/?probe=b1c4404d58) | Apr 09, 2023 |
| Google        | Ampton                      | [e3945d7727](https://linux-hardware.org/?probe=e3945d7727) | Apr 08, 2023 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [14a3d5f4be](https://linux-hardware.org/?probe=14a3d5f4be) | Apr 08, 2023 |
| Lenovo        | ThinkPad P51 W10DG 20MNS... | [5cf4615347](https://linux-hardware.org/?probe=5cf4615347) | Apr 08, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [aab830c5dd](https://linux-hardware.org/?probe=aab830c5dd) | Apr 07, 2023 |
| Google        | Bluebird                    | [6ab22238ac](https://linux-hardware.org/?probe=6ab22238ac) | Apr 07, 2023 |
| Apple         | MacBookPro13,3              | [77c6d48d6b](https://linux-hardware.org/?probe=77c6d48d6b) | Apr 06, 2023 |
| HP            | Laptop 15-db0xxx            | [e05bffcc8a](https://linux-hardware.org/?probe=e05bffcc8a) | Apr 06, 2023 |
| Apple         | MacBookPro14,1              | [e2b1578d42](https://linux-hardware.org/?probe=e2b1578d42) | Apr 06, 2023 |
| Apple         | MacBookPro14,1              | [2cd7831b58](https://linux-hardware.org/?probe=2cd7831b58) | Apr 06, 2023 |
| Google        | Bard                        | [cc1d159d0c](https://linux-hardware.org/?probe=cc1d159d0c) | Apr 05, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [8bf7c8a569](https://linux-hardware.org/?probe=8bf7c8a569) | Apr 05, 2023 |
| Dell          | Latitude E5550              | [5527315153](https://linux-hardware.org/?probe=5527315153) | Apr 05, 2023 |
| Dell          | Latitude 5320               | [5549de9c5c](https://linux-hardware.org/?probe=5549de9c5c) | Apr 05, 2023 |
| Dell          | Latitude 5320               | [69e3bad969](https://linux-hardware.org/?probe=69e3bad969) | Apr 05, 2023 |
| Dell          | Latitude 5480               | [40ec4e3ec9](https://linux-hardware.org/?probe=40ec4e3ec9) | Apr 04, 2023 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [4e7cae1fde](https://linux-hardware.org/?probe=4e7cae1fde) | Apr 04, 2023 |
| Lenovo        | IdeaPad 330S-15AST 81F9     | [d79463ea93](https://linux-hardware.org/?probe=d79463ea93) | Apr 04, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [1af0b7675b](https://linux-hardware.org/?probe=1af0b7675b) | Apr 04, 2023 |
| Dell          | Studio 1558                 | [e9b75d657d](https://linux-hardware.org/?probe=e9b75d657d) | Apr 04, 2023 |
| Lenovo        | Brazos                      | [6415cb26c2](https://linux-hardware.org/?probe=6415cb26c2) | Apr 03, 2023 |
| Toshiba       | Satellite C650              | [190547d5cd](https://linux-hardware.org/?probe=190547d5cd) | Apr 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [d7f3280e60](https://linux-hardware.org/?probe=d7f3280e60) | Apr 03, 2023 |
| Advent        | Roma                        | [e1bd64e5b5](https://linux-hardware.org/?probe=e1bd64e5b5) | Apr 03, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [65cee818b6](https://linux-hardware.org/?probe=65cee818b6) | Apr 02, 2023 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [36c7cf7a43](https://linux-hardware.org/?probe=36c7cf7a43) | Apr 02, 2023 |
| Lenovo        | ThinkPad P51 W10DG 20MNS... | [c7791aac7c](https://linux-hardware.org/?probe=c7791aac7c) | Apr 02, 2023 |
| Lenovo        | ThinkPad T460p 20FXS08N0... | [ffcf174547](https://linux-hardware.org/?probe=ffcf174547) | Apr 02, 2023 |
| Lenovo        | Legion 5P 15ARH05H 82GU     | [3ec9fed32b](https://linux-hardware.org/?probe=3ec9fed32b) | Apr 02, 2023 |
| Apple         | MacBook4,1                  | [dda3791c20](https://linux-hardware.org/?probe=dda3791c20) | Apr 01, 2023 |
| Eii           | WSA116                      | [00bf1c190b](https://linux-hardware.org/?probe=00bf1c190b) | Apr 01, 2023 |
| ASUSTek       | U6Sg                        | [4fc2057b02](https://linux-hardware.org/?probe=4fc2057b02) | Apr 01, 2023 |
| ASUSTek       | U6Sg                        | [c97f807bb0](https://linux-hardware.org/?probe=c97f807bb0) | Apr 01, 2023 |
| HP            | Notebook                    | [348d80772f](https://linux-hardware.org/?probe=348d80772f) | Apr 01, 2023 |
| Acer          | Aspire A715-41G             | [cea0d2797d](https://linux-hardware.org/?probe=cea0d2797d) | Apr 01, 2023 |
| Samsung       | R530/R730/R540              | [714ed0f007](https://linux-hardware.org/?probe=714ed0f007) | Apr 01, 2023 |
| Acer          | Nitro AN517-54              | [82d28ac7c0](https://linux-hardware.org/?probe=82d28ac7c0) | Apr 01, 2023 |
| Valve         | Jupiter                     | [2628ea9d8e](https://linux-hardware.org/?probe=2628ea9d8e) | Apr 01, 2023 |
| Novatech      | NL40_50CU                   | [caaa544589](https://linux-hardware.org/?probe=caaa544589) | Apr 01, 2023 |
| Valve         | Jupiter                     | [d5e7a881e6](https://linux-hardware.org/?probe=d5e7a881e6) | Mar 31, 2023 |
| Valve         | Jupiter                     | [5b3718d617](https://linux-hardware.org/?probe=5b3718d617) | Mar 31, 2023 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | [fe51f2c62f](https://linux-hardware.org/?probe=fe51f2c62f) | Mar 31, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [31d333ecc9](https://linux-hardware.org/?probe=31d333ecc9) | Mar 30, 2023 |
| PC Special... | P65_67RSRP                  | [889f3e8521](https://linux-hardware.org/?probe=889f3e8521) | Mar 30, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [492d575f31](https://linux-hardware.org/?probe=492d575f31) | Mar 30, 2023 |
| Lenovo        | ThinkPad T400 6475J92       | [1d3c812668](https://linux-hardware.org/?probe=1d3c812668) | Mar 30, 2023 |
| OEGStone      | W54_55SU1,SUW               | [a771622660](https://linux-hardware.org/?probe=a771622660) | Mar 29, 2023 |
| OEGStone      | W54_55SU1,SUW               | [1e0c5a90c9](https://linux-hardware.org/?probe=1e0c5a90c9) | Mar 29, 2023 |
| HP            | Laptop 14-bs0xx             | [53504486d2](https://linux-hardware.org/?probe=53504486d2) | Mar 29, 2023 |
| HP            | Laptop 15s-fq4xxx           | [029fa06a9a](https://linux-hardware.org/?probe=029fa06a9a) | Mar 29, 2023 |
| Dell          | Inspiron 5767               | [1c80487906](https://linux-hardware.org/?probe=1c80487906) | Mar 29, 2023 |
| Dell          | Latitude 7430               | [3f3b04c185](https://linux-hardware.org/?probe=3f3b04c185) | Mar 29, 2023 |
| Lenovo        | ThinkPad T460p 20HYSJKDO... | [1d24c2743f](https://linux-hardware.org/?probe=1d24c2743f) | Mar 29, 2023 |
| Valve         | Jupiter                     | [a63f5d9198](https://linux-hardware.org/?probe=a63f5d9198) | Mar 28, 2023 |
| Dell          | Inspiron 15-3567            | [d2b4780094](https://linux-hardware.org/?probe=d2b4780094) | Mar 28, 2023 |
| Dell          | Inspiron N5110              | [2b09d1f769](https://linux-hardware.org/?probe=2b09d1f769) | Mar 28, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [f511f8bcb1](https://linux-hardware.org/?probe=f511f8bcb1) | Mar 28, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | [384f58a6b1](https://linux-hardware.org/?probe=384f58a6b1) | Mar 27, 2023 |
| Dell          | Latitude 7280               | [409cf549eb](https://linux-hardware.org/?probe=409cf549eb) | Mar 27, 2023 |
| Dell          | XPS 15 7590                 | [aeec5e2588](https://linux-hardware.org/?probe=aeec5e2588) | Mar 26, 2023 |
| LG Electro... | 17Z90P-K.AA78A1             | [22e7978cc8](https://linux-hardware.org/?probe=22e7978cc8) | Mar 26, 2023 |
| LG Electro... | 17Z90P-K.AA78A1             | [f889f2ddf5](https://linux-hardware.org/?probe=f889f2ddf5) | Mar 26, 2023 |
| Dell          | Inspiron N5110              | [8fde777c54](https://linux-hardware.org/?probe=8fde777c54) | Mar 26, 2023 |
| Acer          | Nitro AN515-55              | [36d5ba7071](https://linux-hardware.org/?probe=36d5ba7071) | Mar 26, 2023 |
| LG Electro... | 16Z90Q-K.AA78A1             | [009542d035](https://linux-hardware.org/?probe=009542d035) | Mar 26, 2023 |
| HP            | Spectre Laptop 13-af0xx     | [6fdc683220](https://linux-hardware.org/?probe=6fdc683220) | Mar 25, 2023 |
| Samsung       | R530/R730/R540              | [7e37be5b8c](https://linux-hardware.org/?probe=7e37be5b8c) | Mar 25, 2023 |
| HP            | Pavilion Laptop 14-ce3xx... | [1ea635d2a0](https://linux-hardware.org/?probe=1ea635d2a0) | Mar 25, 2023 |
| HP            | Stream Notebook             | [b1ae4b8667](https://linux-hardware.org/?probe=b1ae4b8667) | Mar 25, 2023 |
| Dell          | Latitude E6420              | [2613e5a6ef](https://linux-hardware.org/?probe=2613e5a6ef) | Mar 25, 2023 |
| HUAWEI        | NBD-WXX9                    | [7eb3d40bd8](https://linux-hardware.org/?probe=7eb3d40bd8) | Mar 25, 2023 |
| Apple         | MacBook4,1                  | [7ade2b1d1a](https://linux-hardware.org/?probe=7ade2b1d1a) | Mar 24, 2023 |
| Dell          | Precision 3510              | [2ea0671f5d](https://linux-hardware.org/?probe=2ea0671f5d) | Mar 24, 2023 |
| ASUSTek       | ROG Strix G513IE_G513IE     | [bc6baa37ef](https://linux-hardware.org/?probe=bc6baa37ef) | Mar 24, 2023 |
| HP            | Pavilion 15                 | [32a0c3ec32](https://linux-hardware.org/?probe=32a0c3ec32) | Mar 23, 2023 |
| Notebook      | W510LU                      | [076125acc3](https://linux-hardware.org/?probe=076125acc3) | Mar 23, 2023 |
| Sony          | SVF1521Q1EW                 | [10d078d9e2](https://linux-hardware.org/?probe=10d078d9e2) | Mar 22, 2023 |
| Valve         | Jupiter                     | [8fc3d21cf8](https://linux-hardware.org/?probe=8fc3d21cf8) | Mar 22, 2023 |
| Dell          | XPS 13 9380                 | [9bfb72d26a](https://linux-hardware.org/?probe=9bfb72d26a) | Mar 21, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | [1400f9afc9](https://linux-hardware.org/?probe=1400f9afc9) | Mar 20, 2023 |
| HP            | ProBook 645 G4              | [9c3ac61461](https://linux-hardware.org/?probe=9c3ac61461) | Mar 20, 2023 |
| HP            | ProBook 645 G4              | [10431e8027](https://linux-hardware.org/?probe=10431e8027) | Mar 20, 2023 |
| HP            | ZBook Power 15.6 inch G9... | [2ef051fd19](https://linux-hardware.org/?probe=2ef051fd19) | Mar 20, 2023 |
| Fujitsu Si... | AMILO Xi 3670               | [bb018988d6](https://linux-hardware.org/?probe=bb018988d6) | Mar 20, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [c9c86f1e79](https://linux-hardware.org/?probe=c9c86f1e79) | Mar 20, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [29a6e93a49](https://linux-hardware.org/?probe=29a6e93a49) | Mar 20, 2023 |
| Valve         | Jupiter                     | [8b7918d34b](https://linux-hardware.org/?probe=8b7918d34b) | Mar 20, 2023 |
| Sony          | VPCEH3N6E                   | [9de8a9a50a](https://linux-hardware.org/?probe=9de8a9a50a) | Mar 20, 2023 |
| Notebook      | PCx0Dx                      | [cd5adbbfc0](https://linux-hardware.org/?probe=cd5adbbfc0) | Mar 19, 2023 |
| Notebook      | N150ZU                      | [4b7d1e249f](https://linux-hardware.org/?probe=4b7d1e249f) | Mar 19, 2023 |
| Notebook      | PCx0Dx                      | [63a8165aff](https://linux-hardware.org/?probe=63a8165aff) | Mar 19, 2023 |
| Lenovo        | ThinkPad E560 20EV0010UK    | [f60325ef42](https://linux-hardware.org/?probe=f60325ef42) | Mar 19, 2023 |
| Dell          | Inspiron 15 7510            | [f7aebbae36](https://linux-hardware.org/?probe=f7aebbae36) | Mar 18, 2023 |
| Unknown       | Unknown                     | [e10e576833](https://linux-hardware.org/?probe=e10e576833) | Mar 18, 2023 |
| Unknown       | Unknown                     | [a791424f94](https://linux-hardware.org/?probe=a791424f94) | Mar 18, 2023 |
| Lenovo        | ThinkPad T410 2522AC1       | [49df72f291](https://linux-hardware.org/?probe=49df72f291) | Mar 18, 2023 |
| Lenovo        | ThinkPad T410 2522AC1       | [1f939ee045](https://linux-hardware.org/?probe=1f939ee045) | Mar 18, 2023 |
| Lenovo        | ThinkPad T410 2522AC1       | [5e6e5276e3](https://linux-hardware.org/?probe=5e6e5276e3) | Mar 18, 2023 |
| Sony          | VPCEH3N6E                   | [9c677b7a7b](https://linux-hardware.org/?probe=9c677b7a7b) | Mar 18, 2023 |
| Sony          | VPCEH3N6E                   | [703cc66d3e](https://linux-hardware.org/?probe=703cc66d3e) | Mar 18, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [d58b6cfe61](https://linux-hardware.org/?probe=d58b6cfe61) | Mar 18, 2023 |
| Dell          | Latitude 3410               | [8c71ef60d0](https://linux-hardware.org/?probe=8c71ef60d0) | Mar 18, 2023 |
| Lenovo        | V580c 20160                 | [b7f2837ccd](https://linux-hardware.org/?probe=b7f2837ccd) | Mar 17, 2023 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [274f959cfc](https://linux-hardware.org/?probe=274f959cfc) | Mar 17, 2023 |
| Dell          | Inspiron 3542               | [63dba9dd56](https://linux-hardware.org/?probe=63dba9dd56) | Mar 17, 2023 |
| ASUSTek       | X555LAB                     | [18bf88d413](https://linux-hardware.org/?probe=18bf88d413) | Mar 17, 2023 |
| Lenovo        | Yoga S740-14IIL 81RS        | [e4eb6f31af](https://linux-hardware.org/?probe=e4eb6f31af) | Mar 17, 2023 |
| Toshiba       | Satellite Pro C50-A-1E2     | [a1adc8641d](https://linux-hardware.org/?probe=a1adc8641d) | Mar 17, 2023 |
| Toshiba       | Satellite Pro C50-A-1E2     | [a0eea87e02](https://linux-hardware.org/?probe=a0eea87e02) | Mar 17, 2023 |
| Toshiba       | Satellite L50-C             | [2193d33376](https://linux-hardware.org/?probe=2193d33376) | Mar 16, 2023 |
| Sony          | SVF1521Q1EW                 | [8ab2befd31](https://linux-hardware.org/?probe=8ab2befd31) | Mar 16, 2023 |
| Google        | Babymega                    | [beead110bb](https://linux-hardware.org/?probe=beead110bb) | Mar 16, 2023 |
| Google        | Babymega                    | [0a45acf149](https://linux-hardware.org/?probe=0a45acf149) | Mar 16, 2023 |
| PC Special... | P65_67RSRP                  | [71a45943c1](https://linux-hardware.org/?probe=71a45943c1) | Mar 16, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [907581c9cc](https://linux-hardware.org/?probe=907581c9cc) | Mar 16, 2023 |
| HP            | Laptop 15-da0xxx            | [ccd15bcfae](https://linux-hardware.org/?probe=ccd15bcfae) | Mar 15, 2023 |
| Lenovo        | ThinkPad E560 20EV0010UK    | [c6c5f88e4b](https://linux-hardware.org/?probe=c6c5f88e4b) | Mar 15, 2023 |
| Lenovo        | ThinkPad E560 20EV0010UK    | [3c632e35c3](https://linux-hardware.org/?probe=3c632e35c3) | Mar 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [fbbcc2d2c5](https://linux-hardware.org/?probe=fbbcc2d2c5) | Mar 15, 2023 |
| Toshiba       | QOSMIO X70-A                | [f85336fbca](https://linux-hardware.org/?probe=f85336fbca) | Mar 15, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [0ee987e184](https://linux-hardware.org/?probe=0ee987e184) | Mar 15, 2023 |
| Timi          | RedmiBook 14                | [ff5feda02c](https://linux-hardware.org/?probe=ff5feda02c) | Mar 14, 2023 |
| Lenovo        | ThinkPad X240 20AMS1FW00    | [0b9501dcc9](https://linux-hardware.org/?probe=0b9501dcc9) | Mar 14, 2023 |
| HP            | ProBook 645 G4              | [e2f98f4fd2](https://linux-hardware.org/?probe=e2f98f4fd2) | Mar 14, 2023 |
| TUXEDO        | Aura 15 Gen1                | [9331f6026e](https://linux-hardware.org/?probe=9331f6026e) | Mar 14, 2023 |
| TUXEDO        | InfinityBook S 15 Gen6      | [7e90a81e0b](https://linux-hardware.org/?probe=7e90a81e0b) | Mar 14, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [d23ddde885](https://linux-hardware.org/?probe=d23ddde885) | Mar 14, 2023 |
| Valve         | Jupiter                     | [1ad8d706ff](https://linux-hardware.org/?probe=1ad8d706ff) | Mar 14, 2023 |
| ASUSTek       | X551CA                      | [08924a17f9](https://linux-hardware.org/?probe=08924a17f9) | Mar 14, 2023 |
| ASUSTek       | X551CA                      | [ba5c82bc14](https://linux-hardware.org/?probe=ba5c82bc14) | Mar 14, 2023 |
| Lenovo        | ThinkPad SL 2746N8G         | [2124288941](https://linux-hardware.org/?probe=2124288941) | Mar 13, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [007f595264](https://linux-hardware.org/?probe=007f595264) | Mar 13, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [fdb6080ba5](https://linux-hardware.org/?probe=fdb6080ba5) | Mar 13, 2023 |
| Lenovo        | Legion 5 15IAH7H 82RB       | [9841e70d67](https://linux-hardware.org/?probe=9841e70d67) | Mar 13, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [4c890ba150](https://linux-hardware.org/?probe=4c890ba150) | Mar 13, 2023 |
| HP            | Pavilion 15                 | [d5eb709e13](https://linux-hardware.org/?probe=d5eb709e13) | Mar 12, 2023 |
| OEGStone      | W240EU/W250EUQ/W270EUQ      | [45ea3c4094](https://linux-hardware.org/?probe=45ea3c4094) | Mar 12, 2023 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [d777dadd73](https://linux-hardware.org/?probe=d777dadd73) | Mar 12, 2023 |
| HP            | Laptop 14-ck0xxx            | [2be528d875](https://linux-hardware.org/?probe=2be528d875) | Mar 12, 2023 |
| Novatech      | 15.6 nSpire Laptop          | [f5814aa2e6](https://linux-hardware.org/?probe=f5814aa2e6) | Mar 12, 2023 |
| Acer          | Aspire 5920                 | [f6c972404c](https://linux-hardware.org/?probe=f6c972404c) | Mar 12, 2023 |
| Dell          | Latitude E6530              | [50a26c019d](https://linux-hardware.org/?probe=50a26c019d) | Mar 11, 2023 |
| Google        | Ampton                      | [641b7d64fc](https://linux-hardware.org/?probe=641b7d64fc) | Mar 10, 2023 |
| Dell          | Inspiron 1750               | [354cdf8592](https://linux-hardware.org/?probe=354cdf8592) | Mar 10, 2023 |
| Valve         | Jupiter                     | [d4cc4ff572](https://linux-hardware.org/?probe=d4cc4ff572) | Mar 10, 2023 |
| Acer          | Aspire V3-772               | [661125aac2](https://linux-hardware.org/?probe=661125aac2) | Mar 10, 2023 |
| Unknown       | Unknown                     | [cd382356be](https://linux-hardware.org/?probe=cd382356be) | Mar 10, 2023 |
| HP            | ProBook 430 G4              | [9c3d2e652a](https://linux-hardware.org/?probe=9c3d2e652a) | Mar 09, 2023 |
| HP            | Laptop 14-cm0xxx            | [d35d11c64e](https://linux-hardware.org/?probe=d35d11c64e) | Mar 09, 2023 |
| Dell          | Latitude 7285               | [dfc4961010](https://linux-hardware.org/?probe=dfc4961010) | Mar 09, 2023 |
| Lenovo        | ThinkPad E15 20RD0011UK     | [026c39773a](https://linux-hardware.org/?probe=026c39773a) | Mar 09, 2023 |
| HP            | Pavilion TS 15              | [5c0b7a773e](https://linux-hardware.org/?probe=5c0b7a773e) | Mar 09, 2023 |
| Dell          | XPS 15 9530                 | [d7129009b0](https://linux-hardware.org/?probe=d7129009b0) | Mar 09, 2023 |
| Google        | Cave                        | [37d6d413b7](https://linux-hardware.org/?probe=37d6d413b7) | Mar 09, 2023 |
| Razer         | Blade 15 Advanced Model ... | [46fa9eab7d](https://linux-hardware.org/?probe=46fa9eab7d) | Mar 08, 2023 |
| Entroware     | Apollo                      | [d1576010b3](https://linux-hardware.org/?probe=d1576010b3) | Mar 08, 2023 |
| Valve         | Jupiter                     | [1851a5388e](https://linux-hardware.org/?probe=1851a5388e) | Mar 08, 2023 |
| Acer          | Swift SFX14-51G             | [54d0c16597](https://linux-hardware.org/?probe=54d0c16597) | Mar 07, 2023 |
| Packard Be... | EasyNote TM82               | [33de288525](https://linux-hardware.org/?probe=33de288525) | Mar 07, 2023 |
| HUAWEI        | KLVD-WXX9                   | [1209c224e1](https://linux-hardware.org/?probe=1209c224e1) | Mar 06, 2023 |
| HONOR         | HYM-WXX                     | [f9f277d226](https://linux-hardware.org/?probe=f9f277d226) | Mar 06, 2023 |
| Acer          | Predator PH315-55           | [8465c0241c](https://linux-hardware.org/?probe=8465c0241c) | Mar 06, 2023 |
| Valve         | Jupiter                     | [f6c973a00f](https://linux-hardware.org/?probe=f6c973a00f) | Mar 06, 2023 |
| Dell          | Inspiron 15 3525            | [cc3e080ded](https://linux-hardware.org/?probe=cc3e080ded) | Mar 06, 2023 |
| Valve         | Jupiter                     | [73eb839f5b](https://linux-hardware.org/?probe=73eb839f5b) | Mar 06, 2023 |
| Alienware     | Area-51m R2                 | [5726561947](https://linux-hardware.org/?probe=5726561947) | Mar 06, 2023 |
| Lenovo        | ThinkPad T470s 20HF0000U... | [f6863db7ca](https://linux-hardware.org/?probe=f6863db7ca) | Mar 05, 2023 |
| ASUSTek       | ROG Strix G731GU_G731GU     | [c777bd0be1](https://linux-hardware.org/?probe=c777bd0be1) | Mar 05, 2023 |
| Toshiba       | Satellite C660              | [d1ada89fd6](https://linux-hardware.org/?probe=d1ada89fd6) | Mar 04, 2023 |
| MSI           | GS70 2QE                    | [3c8e62e276](https://linux-hardware.org/?probe=3c8e62e276) | Mar 04, 2023 |
| Acer          | Aspire A515-47              | [3b1c7f5e26](https://linux-hardware.org/?probe=3b1c7f5e26) | Mar 04, 2023 |
| MSI           | GS70 2QE                    | [5c059744df](https://linux-hardware.org/?probe=5c059744df) | Mar 04, 2023 |
| Lenovo        | ThinkPad T470s 20HF0000U... | [89de1a18fe](https://linux-hardware.org/?probe=89de1a18fe) | Mar 04, 2023 |
| Lenovo        | ThinkPad T420 4236Q23       | [2aa5383e7e](https://linux-hardware.org/?probe=2aa5383e7e) | Mar 04, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | [3e484b7bac](https://linux-hardware.org/?probe=3e484b7bac) | Mar 04, 2023 |
| Dell          | XPS 17 9700                 | [8a4cc5192e](https://linux-hardware.org/?probe=8a4cc5192e) | Mar 04, 2023 |
| Apple         | MacBookPro9,1               | [6553b59bfe](https://linux-hardware.org/?probe=6553b59bfe) | Mar 03, 2023 |
| Dell          | XPS 15 9560                 | [11572533c2](https://linux-hardware.org/?probe=11572533c2) | Mar 03, 2023 |
| Sony          | SVF1521Q1EW                 | [3c74542aad](https://linux-hardware.org/?probe=3c74542aad) | Mar 02, 2023 |
| Sony          | SVF1521Q1EW                 | [7b7db7c319](https://linux-hardware.org/?probe=7b7db7c319) | Mar 02, 2023 |
| Samsung       | 3570R/370R/470R/450R/510... | [2629f1915d](https://linux-hardware.org/?probe=2629f1915d) | Mar 02, 2023 |
| Dell          | Latitude E6410              | [3b99fd709e](https://linux-hardware.org/?probe=3b99fd709e) | Mar 02, 2023 |
| Valve         | Jupiter                     | [83cbea47d9](https://linux-hardware.org/?probe=83cbea47d9) | Mar 02, 2023 |
| Acer          | Aspire A315-32              | [5203ce8a41](https://linux-hardware.org/?probe=5203ce8a41) | Mar 02, 2023 |
| HUAWEI        | NBD-WXX9                    | [9036fa2ef1](https://linux-hardware.org/?probe=9036fa2ef1) | Mar 02, 2023 |
| Dell          | Latitude E7250              | [970d46cc83](https://linux-hardware.org/?probe=970d46cc83) | Mar 01, 2023 |
| HUAWEI        | KLVD-WXX9                   | [8c878d99a1](https://linux-hardware.org/?probe=8c878d99a1) | Mar 01, 2023 |
| Acer          | Predator PH517-61           | [2d1ec6c994](https://linux-hardware.org/?probe=2d1ec6c994) | Mar 01, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [eca37862f3](https://linux-hardware.org/?probe=eca37862f3) | Mar 01, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [1025a9748f](https://linux-hardware.org/?probe=1025a9748f) | Mar 01, 2023 |
| Acer          | Aspire 5733                 | [b1744130eb](https://linux-hardware.org/?probe=b1744130eb) | Mar 01, 2023 |
| MSI           | Summit E14Evo A12M          | [ad389112d3](https://linux-hardware.org/?probe=ad389112d3) | Mar 01, 2023 |
| Alienware     | 15 R2                       | [f242145858](https://linux-hardware.org/?probe=f242145858) | Feb 28, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [c698fc199a](https://linux-hardware.org/?probe=c698fc199a) | Feb 28, 2023 |
| Acer          | Aspire V3-371               | [bbc0d58ef1](https://linux-hardware.org/?probe=bbc0d58ef1) | Feb 28, 2023 |
| Dell          | Latitude D630               | [5175558c99](https://linux-hardware.org/?probe=5175558c99) | Feb 28, 2023 |
| Dell          | Latitude E6440              | [80131cd2a4](https://linux-hardware.org/?probe=80131cd2a4) | Feb 28, 2023 |
| AZW           | SEi                         | [6d0814dc9f](https://linux-hardware.org/?probe=6d0814dc9f) | Feb 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [003aa3d3e9](https://linux-hardware.org/?probe=003aa3d3e9) | Feb 27, 2023 |
| Panasonic     | CF-31WEUEEBE                | [40782ba0a7](https://linux-hardware.org/?probe=40782ba0a7) | Feb 26, 2023 |
| HP            | Pavilion g6                 | [556c1057a8](https://linux-hardware.org/?probe=556c1057a8) | Feb 26, 2023 |
| Dell          | Inspiron 3542               | [64f304d41e](https://linux-hardware.org/?probe=64f304d41e) | Feb 25, 2023 |
| HP            | G62                         | [871207750c](https://linux-hardware.org/?probe=871207750c) | Feb 25, 2023 |
| Lenovo        | IdeaPad 305-15IBD 80NJ      | [42b9d60137](https://linux-hardware.org/?probe=42b9d60137) | Feb 25, 2023 |
| Dell          | Latitude E6440              | [a4139e4774](https://linux-hardware.org/?probe=a4139e4774) | Feb 25, 2023 |
| MSI           | Modern 14 B10MW             | [4f9e90413b](https://linux-hardware.org/?probe=4f9e90413b) | Feb 25, 2023 |
| Lenovo        | IdeaPad Z580                | [cf2ff6c04b](https://linux-hardware.org/?probe=cf2ff6c04b) | Feb 24, 2023 |
| HP            | Pavilion g6                 | [5cde621e0a](https://linux-hardware.org/?probe=5cde621e0a) | Feb 24, 2023 |
| Valve         | Jupiter                     | [df96e94417](https://linux-hardware.org/?probe=df96e94417) | Feb 24, 2023 |
| Toshiba       | Satellite C850-1GF          | [f568855409](https://linux-hardware.org/?probe=f568855409) | Feb 24, 2023 |
| Valve         | Jupiter                     | [8679998ec0](https://linux-hardware.org/?probe=8679998ec0) | Feb 23, 2023 |
| PC Special... | PD5x_7xPNP_PNN_PNT          | [cd71ec0b21](https://linux-hardware.org/?probe=cd71ec0b21) | Feb 23, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [f92ac89547](https://linux-hardware.org/?probe=f92ac89547) | Feb 23, 2023 |
| Lenovo        | V15-ADA 82C7                | [d19ee09dd3](https://linux-hardware.org/?probe=d19ee09dd3) | Feb 23, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | [2c74210fed](https://linux-hardware.org/?probe=2c74210fed) | Feb 23, 2023 |
| Dell          | Inspiron 5565               | [d88dce11ff](https://linux-hardware.org/?probe=d88dce11ff) | Feb 22, 2023 |
| Lenovo        | ThinkPad X230 2325EJ0       | [3a2c22e22b](https://linux-hardware.org/?probe=3a2c22e22b) | Feb 22, 2023 |
| Lenovo        | ThinkPad T430s 23551M9      | [91b6a109b4](https://linux-hardware.org/?probe=91b6a109b4) | Feb 22, 2023 |
| Lenovo        | ThinkPad X230 2325EJ0       | [06c8604990](https://linux-hardware.org/?probe=06c8604990) | Feb 22, 2023 |
| Apple         | MacBookPro14,1              | [f7f94aa827](https://linux-hardware.org/?probe=f7f94aa827) | Feb 22, 2023 |
| Google        | Droid                       | [e576f650b7](https://linux-hardware.org/?probe=e576f650b7) | Feb 22, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | [c51d4ef82a](https://linux-hardware.org/?probe=c51d4ef82a) | Feb 20, 2023 |
| HP            | Laptop 14s-fq0xxx           | [0bc03f3b39](https://linux-hardware.org/?probe=0bc03f3b39) | Feb 20, 2023 |
| Dell          | XPS 13 7390                 | [542077cc42](https://linux-hardware.org/?probe=542077cc42) | Feb 20, 2023 |
| Lenovo        | ThinkPad T440p 20AWS38H0... | [c79a8f48f9](https://linux-hardware.org/?probe=c79a8f48f9) | Feb 20, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [63de5bef96](https://linux-hardware.org/?probe=63de5bef96) | Feb 20, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | [2ccbfb422e](https://linux-hardware.org/?probe=2ccbfb422e) | Feb 20, 2023 |
| HUAWEI        | MateBook X                  | [cae415dee6](https://linux-hardware.org/?probe=cae415dee6) | Feb 20, 2023 |
| HUAWEI        | MateBook X                  | [6fed527c1b](https://linux-hardware.org/?probe=6fed527c1b) | Feb 20, 2023 |
| HP            | Pavilion g6                 | [f3552f5183](https://linux-hardware.org/?probe=f3552f5183) | Feb 19, 2023 |
| Lenovo        | ThinkPad E555 20DH000TUK    | [b2d5c9de8b](https://linux-hardware.org/?probe=b2d5c9de8b) | Feb 19, 2023 |
| HP            | 250 G6 Notebook PC          | [c32182253e](https://linux-hardware.org/?probe=c32182253e) | Feb 19, 2023 |
| ASUSTek       | ROG Strix G731GU_G731GU     | [03952a6c01](https://linux-hardware.org/?probe=03952a6c01) | Feb 18, 2023 |
| Apple         | MacBookPro5,5               | [595103a203](https://linux-hardware.org/?probe=595103a203) | Feb 18, 2023 |
| PC Special... | NJ50_70CU                   | [68dd853397](https://linux-hardware.org/?probe=68dd853397) | Feb 17, 2023 |
| Lenovo        | IdeaPad 5 14IAL7 82SD       | [cd5e470881](https://linux-hardware.org/?probe=cd5e470881) | Feb 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [0cd82bf0c0](https://linux-hardware.org/?probe=0cd82bf0c0) | Feb 17, 2023 |
| Dell          | Latitude E5450              | [cd7e5d61f2](https://linux-hardware.org/?probe=cd7e5d61f2) | Feb 17, 2023 |
| Dell          | Latitude E6410              | [58d4c40618](https://linux-hardware.org/?probe=58d4c40618) | Feb 17, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [3042108dae](https://linux-hardware.org/?probe=3042108dae) | Feb 16, 2023 |
| Sony          | SVF1521Q1EW                 | [62503d2494](https://linux-hardware.org/?probe=62503d2494) | Feb 16, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [cec962a8f4](https://linux-hardware.org/?probe=cec962a8f4) | Feb 16, 2023 |
| HP            | Stream Notebook PC 14       | [ba59b583d2](https://linux-hardware.org/?probe=ba59b583d2) | Feb 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [043e92c2ee](https://linux-hardware.org/?probe=043e92c2ee) | Feb 15, 2023 |
| Apple         | MacBookPro10,2              | [178ef8e028](https://linux-hardware.org/?probe=178ef8e028) | Feb 15, 2023 |
| HP            | Notebook                    | [88703a5913](https://linux-hardware.org/?probe=88703a5913) | Feb 15, 2023 |
| Apple         | MacBookPro10,2              | [6650047151](https://linux-hardware.org/?probe=6650047151) | Feb 15, 2023 |
| Linx          | LINX1010B                   | [5ca377461f](https://linux-hardware.org/?probe=5ca377461f) | Feb 14, 2023 |
| Unknown       | T3 MRD                      | [df134a8199](https://linux-hardware.org/?probe=df134a8199) | Feb 14, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | [e9faf4ce80](https://linux-hardware.org/?probe=e9faf4ce80) | Feb 14, 2023 |
| Valve         | Jupiter                     | [e362a7551c](https://linux-hardware.org/?probe=e362a7551c) | Feb 14, 2023 |
| Acer          | TravelMate P215-52          | [b4ac56b67d](https://linux-hardware.org/?probe=b4ac56b67d) | Feb 13, 2023 |
| Dell          | XPS 15 9520                 | [1263022267](https://linux-hardware.org/?probe=1263022267) | Feb 13, 2023 |
| Apple         | MacBook4,1                  | [dfb5b14f25](https://linux-hardware.org/?probe=dfb5b14f25) | Feb 13, 2023 |
| Dell          | Latitude E6530              | [c79c336ef7](https://linux-hardware.org/?probe=c79c336ef7) | Feb 13, 2023 |
| Acer          | Aspire 5349                 | [8407710a28](https://linux-hardware.org/?probe=8407710a28) | Feb 12, 2023 |
| HUAWEI        | NBD-WXX9                    | [c8caa92db3](https://linux-hardware.org/?probe=c8caa92db3) | Feb 11, 2023 |
| Toshiba       | Satellite Pro C850-10N      | [d45ac3e79c](https://linux-hardware.org/?probe=d45ac3e79c) | Feb 11, 2023 |
| ASUSTek       | ROG Strix G512LI_G512LI     | [6c8760114a](https://linux-hardware.org/?probe=6c8760114a) | Feb 11, 2023 |
| Acer          | Swift SF314-43              | [60fed002e2](https://linux-hardware.org/?probe=60fed002e2) | Feb 11, 2023 |
| Acer          | TravelMate P253             | [8947050124](https://linux-hardware.org/?probe=8947050124) | Feb 11, 2023 |
| Acer          | Aspire 5742G                | [ddde9bf34e](https://linux-hardware.org/?probe=ddde9bf34e) | Feb 10, 2023 |
| Dell          | Precision M4700             | [74f62c6131](https://linux-hardware.org/?probe=74f62c6131) | Feb 10, 2023 |
| Dell          | Precision M4700             | [797b766595](https://linux-hardware.org/?probe=797b766595) | Feb 10, 2023 |
| ASUSTek       | GL552VW                     | [c9ed530a00](https://linux-hardware.org/?probe=c9ed530a00) | Feb 10, 2023 |
| Novatech      | NL40_50CU                   | [cca307c7db](https://linux-hardware.org/?probe=cca307c7db) | Feb 10, 2023 |
| Lenovo        | ThinkPad T450 20BUA0PNUK    | [8837c33007](https://linux-hardware.org/?probe=8837c33007) | Feb 09, 2023 |
| HP            | EliteBook Folio 1040 G3     | [3209372a9d](https://linux-hardware.org/?probe=3209372a9d) | Feb 09, 2023 |
| Dell          | Latitude 5511               | [05e11b64d6](https://linux-hardware.org/?probe=05e11b64d6) | Feb 09, 2023 |
| Lenovo        | ThinkPad L560 20F2S0DA00    | [c9dd7aae2e](https://linux-hardware.org/?probe=c9dd7aae2e) | Feb 08, 2023 |
| Dell          | Latitude E6330              | [291e0fd64f](https://linux-hardware.org/?probe=291e0fd64f) | Feb 08, 2023 |
| Lenovo        | V14 G2 ALC 82KC             | [a1c831925b](https://linux-hardware.org/?probe=a1c831925b) | Feb 08, 2023 |
| Lenovo        | V14 G2 ALC 82KC             | [86c4416049](https://linux-hardware.org/?probe=86c4416049) | Feb 08, 2023 |
| HP            | EliteBook Folio 1040 G3     | [fa77bac136](https://linux-hardware.org/?probe=fa77bac136) | Feb 08, 2023 |
| HP            | EliteBook 745 G2            | [35cb1bce53](https://linux-hardware.org/?probe=35cb1bce53) | Feb 08, 2023 |
| HP            | Laptop 14-cm0xxx            | [5dfc3e2280](https://linux-hardware.org/?probe=5dfc3e2280) | Feb 08, 2023 |
| Lenovo        | ThinkPad X280 20KEA0VCUK    | [e39c3cefa0](https://linux-hardware.org/?probe=e39c3cefa0) | Feb 08, 2023 |
| HP            | EliteBook 745 G2            | [ce120b023c](https://linux-hardware.org/?probe=ce120b023c) | Feb 08, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [e32b918f95](https://linux-hardware.org/?probe=e32b918f95) | Feb 07, 2023 |
| HUAWEI        | NBD-WXX9                    | [2bb967f6b3](https://linux-hardware.org/?probe=2bb967f6b3) | Feb 07, 2023 |
| Dell          | Latitude 5330               | [30cd96be4d](https://linux-hardware.org/?probe=30cd96be4d) | Feb 07, 2023 |
| Lenovo        | ThinkPad T430 2349UXH       | [aea2246107](https://linux-hardware.org/?probe=aea2246107) | Feb 06, 2023 |
| Lenovo        | ThinkPad T430 2349UXH       | [24d1d2fa52](https://linux-hardware.org/?probe=24d1d2fa52) | Feb 06, 2023 |
| Google        | Samus                       | [0817ec0be1](https://linux-hardware.org/?probe=0817ec0be1) | Feb 06, 2023 |
| Acer          | Aspire E5-571               | [a50f302f00](https://linux-hardware.org/?probe=a50f302f00) | Feb 06, 2023 |
| Acer          | TravelMate P253             | [050d7b5d68](https://linux-hardware.org/?probe=050d7b5d68) | Feb 06, 2023 |
| Lenovo        | ThinkPad T420 4236KU9       | [f536be92d0](https://linux-hardware.org/?probe=f536be92d0) | Feb 06, 2023 |
| Dell          | Inspiron 5593               | [6c09a62b19](https://linux-hardware.org/?probe=6c09a62b19) | Feb 06, 2023 |
| HP            | EliteBook Folio 1040 G3     | [67d2b1fd55](https://linux-hardware.org/?probe=67d2b1fd55) | Feb 05, 2023 |
| HP            | Notebook                    | [0ad701667d](https://linux-hardware.org/?probe=0ad701667d) | Feb 05, 2023 |
| HP            | Notebook                    | [37f601798c](https://linux-hardware.org/?probe=37f601798c) | Feb 05, 2023 |
| Apple         | MacBookPro13,1              | [76cf23841d](https://linux-hardware.org/?probe=76cf23841d) | Feb 05, 2023 |
| Acer          | Aspire ES1-531              | [4d2872e685](https://linux-hardware.org/?probe=4d2872e685) | Feb 04, 2023 |
| GEO           | GeoBook 240                 | [861adcda52](https://linux-hardware.org/?probe=861adcda52) | Feb 04, 2023 |
| Lenovo        | ThinkPad X240 20AMS1FW00    | [cee7b3fa93](https://linux-hardware.org/?probe=cee7b3fa93) | Feb 04, 2023 |
| GEO           | GeoBook 140                 | [a91fdaa5da](https://linux-hardware.org/?probe=a91fdaa5da) | Feb 04, 2023 |
| Lenovo        | ThinkPad X280 20KEA0VCUK    | [48d07b6859](https://linux-hardware.org/?probe=48d07b6859) | Feb 04, 2023 |
| Dell          | XPS 13 9380                 | [495ff876cf](https://linux-hardware.org/?probe=495ff876cf) | Feb 03, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C7C... | [e23aca8e4b](https://linux-hardware.org/?probe=e23aca8e4b) | Feb 03, 2023 |
| Star Labs     | StarBook                    | [98ad1bcab4](https://linux-hardware.org/?probe=98ad1bcab4) | Feb 03, 2023 |
| Star Labs     | StarBook                    | [5fe174bdd1](https://linux-hardware.org/?probe=5fe174bdd1) | Feb 03, 2023 |
| MSI           | GS66 Stealth 10SF           | [1d3a68b4a0](https://linux-hardware.org/?probe=1d3a68b4a0) | Feb 03, 2023 |
| Lenovo        | B50-30 80ES                 | [3fb480c029](https://linux-hardware.org/?probe=3fb480c029) | Feb 03, 2023 |
| Dell          | Latitude 5420               | [019540839e](https://linux-hardware.org/?probe=019540839e) | Feb 03, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [f544702336](https://linux-hardware.org/?probe=f544702336) | Feb 03, 2023 |
| HP            | Laptop 15-da0xxx            | [21227757d0](https://linux-hardware.org/?probe=21227757d0) | Feb 02, 2023 |
| Toshiba       | Satellite L50D-B            | [457faa2485](https://linux-hardware.org/?probe=457faa2485) | Feb 02, 2023 |
| Notebook      | NL5xNU                      | [8bec95eb42](https://linux-hardware.org/?probe=8bec95eb42) | Feb 02, 2023 |
| Alienware     | M14xR2                      | [d7e3d61744](https://linux-hardware.org/?probe=d7e3d61744) | Feb 02, 2023 |
| Acer          | Aspire 5349                 | [edf1e65f78](https://linux-hardware.org/?probe=edf1e65f78) | Feb 02, 2023 |
| Acer          | Aspire one 1-132            | [d66a972aa9](https://linux-hardware.org/?probe=d66a972aa9) | Feb 02, 2023 |
| Lenovo        | ThinkPad T470s 20HF0000U... | [d7a5b537d9](https://linux-hardware.org/?probe=d7a5b537d9) | Feb 01, 2023 |
| HP            | Sona                        | [36a3d72172](https://linux-hardware.org/?probe=36a3d72172) | Jan 31, 2023 |
| Lenovo        | Yoga 3 14 80JH              | [6c66b66a78](https://linux-hardware.org/?probe=6c66b66a78) | Jan 30, 2023 |
| Valve         | Jupiter                     | [9568a6f43d](https://linux-hardware.org/?probe=9568a6f43d) | Jan 30, 2023 |
| Acer          | Aspire A515-52              | [51fa3ff577](https://linux-hardware.org/?probe=51fa3ff577) | Jan 30, 2023 |
| HP            | Laptop 14-cm0xxx            | [9b93652159](https://linux-hardware.org/?probe=9b93652159) | Jan 29, 2023 |
| Valve         | Jupiter                     | [91ef57c9e5](https://linux-hardware.org/?probe=91ef57c9e5) | Jan 29, 2023 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | [3912652a13](https://linux-hardware.org/?probe=3912652a13) | Jan 29, 2023 |
| Razer         | Blade 15 (2022) - RZ09-0... | [41d33a9029](https://linux-hardware.org/?probe=41d33a9029) | Jan 29, 2023 |
| Dell          | Latitude E6530              | [87bca9f2a4](https://linux-hardware.org/?probe=87bca9f2a4) | Jan 29, 2023 |
| HP            | ENVY Laptop 17-cg0xxx       | [ed1ce46901](https://linux-hardware.org/?probe=ed1ce46901) | Jan 28, 2023 |
| Dell          | Inspiron 14-3452            | [baf61affa2](https://linux-hardware.org/?probe=baf61affa2) | Jan 28, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [c4877a8bc3](https://linux-hardware.org/?probe=c4877a8bc3) | Jan 28, 2023 |
| Apple         | MacBookAir7,2               | [b5f0169944](https://linux-hardware.org/?probe=b5f0169944) | Jan 28, 2023 |
| HP            | ENVY Laptop 17-cg0xxx       | [ab3f84f96b](https://linux-hardware.org/?probe=ab3f84f96b) | Jan 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [0245809d6a](https://linux-hardware.org/?probe=0245809d6a) | Jan 28, 2023 |
| Notebook      | P17SM-A                     | [609a89ca14](https://linux-hardware.org/?probe=609a89ca14) | Jan 27, 2023 |
| HP            | EliteBook 8530w             | [f395c475c9](https://linux-hardware.org/?probe=f395c475c9) | Jan 27, 2023 |
| Lenovo        | ThinkPad T530 24292DG       | [e171a529b9](https://linux-hardware.org/?probe=e171a529b9) | Jan 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [5f1e1e4d00](https://linux-hardware.org/?probe=5f1e1e4d00) | Jan 27, 2023 |
| Dell          | Inspiron 15 3521            | [41f89081ff](https://linux-hardware.org/?probe=41f89081ff) | Jan 26, 2023 |
| Acer          | Aspire ES1-411              | [110767fd86](https://linux-hardware.org/?probe=110767fd86) | Jan 26, 2023 |
| MSI           | Katana GF66 11UE            | [aead8d4d18](https://linux-hardware.org/?probe=aead8d4d18) | Jan 26, 2023 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | [de8222900d](https://linux-hardware.org/?probe=de8222900d) | Jan 26, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20C0S0Q... | [cdd3eb5723](https://linux-hardware.org/?probe=cdd3eb5723) | Jan 26, 2023 |
| Notebook      | P17SM-A                     | [6ed204eca5](https://linux-hardware.org/?probe=6ed204eca5) | Jan 26, 2023 |
| Google        | Careena                     | [75ca1a25dd](https://linux-hardware.org/?probe=75ca1a25dd) | Jan 26, 2023 |
| Lenovo        | Yoga 2 11 20332             | [6faa58b4a1](https://linux-hardware.org/?probe=6faa58b4a1) | Jan 26, 2023 |
| Lenovo        | Yoga 2 11 20332             | [f437e45107](https://linux-hardware.org/?probe=f437e45107) | Jan 26, 2023 |
| Lenovo        | Yoga 2 11 20332             | [9dfb8ac7b0](https://linux-hardware.org/?probe=9dfb8ac7b0) | Jan 25, 2023 |
| OEGStone      | C4100/C5100                 | [4365b7b231](https://linux-hardware.org/?probe=4365b7b231) | Jan 25, 2023 |
| Dell          | Latitude 5520               | [662284824b](https://linux-hardware.org/?probe=662284824b) | Jan 24, 2023 |
| HP            | EliteBook 745 G2            | [0d073c35f4](https://linux-hardware.org/?probe=0d073c35f4) | Jan 24, 2023 |
| Toshiba       | Satellite Pro C660          | [3ffb5ed458](https://linux-hardware.org/?probe=3ffb5ed458) | Jan 24, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | [97ca64cad1](https://linux-hardware.org/?probe=97ca64cad1) | Jan 23, 2023 |
| Lenovo        | ThinkPad X260 20F5S28R00    | [4f83721cab](https://linux-hardware.org/?probe=4f83721cab) | Jan 23, 2023 |
| Lenovo        | ThinkPad X260 20F5S28R00    | [9e12a145fd](https://linux-hardware.org/?probe=9e12a145fd) | Jan 23, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [e9124adb70](https://linux-hardware.org/?probe=e9124adb70) | Jan 23, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | [e1eeca8eab](https://linux-hardware.org/?probe=e1eeca8eab) | Jan 23, 2023 |
| Lenovo        | Z51-70 80K6                 | [f0cce92dd4](https://linux-hardware.org/?probe=f0cce92dd4) | Jan 23, 2023 |
| Lenovo        | Flex 2-15D 20377            | [e4a2f02d89](https://linux-hardware.org/?probe=e4a2f02d89) | Jan 23, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [37f26b2f10](https://linux-hardware.org/?probe=37f26b2f10) | Jan 23, 2023 |
| Sony          | SVF1521Q1EW                 | [1e8cceb35b](https://linux-hardware.org/?probe=1e8cceb35b) | Jan 23, 2023 |
| Dell          | Precision M6800             | [a6beff01de](https://linux-hardware.org/?probe=a6beff01de) | Jan 22, 2023 |
| Lenovo        | ThinkPad L380 20M50013UK    | [0729d0a10f](https://linux-hardware.org/?probe=0729d0a10f) | Jan 22, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [d971cd0912](https://linux-hardware.org/?probe=d971cd0912) | Jan 21, 2023 |
| Razer x La... | TensorBook (late 2021)      | [9062d4274f](https://linux-hardware.org/?probe=9062d4274f) | Jan 21, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [fe4b24bf26](https://linux-hardware.org/?probe=fe4b24bf26) | Jan 21, 2023 |
| Dell          | XPS 13 7390                 | [97b14c6835](https://linux-hardware.org/?probe=97b14c6835) | Jan 20, 2023 |
| Sony          | SVE1513B4E                  | [cbd9f98f30](https://linux-hardware.org/?probe=cbd9f98f30) | Jan 20, 2023 |
| HP            | Unknown                     | [b82faadc9d](https://linux-hardware.org/?probe=b82faadc9d) | Jan 19, 2023 |
| Dell          | XPS 13 7390                 | [01f3a78934](https://linux-hardware.org/?probe=01f3a78934) | Jan 19, 2023 |
| Dell          | XPS 15 9570                 | [ebd319efff](https://linux-hardware.org/?probe=ebd319efff) | Jan 19, 2023 |
| Apple         | MacBook8,1                  | [17e254a9ec](https://linux-hardware.org/?probe=17e254a9ec) | Jan 19, 2023 |
| PC Special... | Elimina Iv 17               | [72e46e7bad](https://linux-hardware.org/?probe=72e46e7bad) | Jan 18, 2023 |
| Toshiba       | Satellite L70-C-12H         | [aa6340dd48](https://linux-hardware.org/?probe=aa6340dd48) | Jan 18, 2023 |
| Novatech      | NL40_50CU                   | [395dab7c43](https://linux-hardware.org/?probe=395dab7c43) | Jan 18, 2023 |
| Dell          | Inspiron N5110              | [bf606ed50a](https://linux-hardware.org/?probe=bf606ed50a) | Jan 18, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [4b8096c4d2](https://linux-hardware.org/?probe=4b8096c4d2) | Jan 18, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [6d93895cac](https://linux-hardware.org/?probe=6d93895cac) | Jan 18, 2023 |
| Toshiba       | Satellite Pro C50-A-1E6     | [0306622813](https://linux-hardware.org/?probe=0306622813) | Jan 18, 2023 |
| Packard Be... | EasyNote TM82               | [49ae8de234](https://linux-hardware.org/?probe=49ae8de234) | Jan 18, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [03c7a9b8a1](https://linux-hardware.org/?probe=03c7a9b8a1) | Jan 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [84edd23a21](https://linux-hardware.org/?probe=84edd23a21) | Jan 18, 2023 |
| Dell          | Latitude E5440              | [eb945eac4e](https://linux-hardware.org/?probe=eb945eac4e) | Jan 18, 2023 |
| Notebook      | PCx0Dx                      | [658ed38b10](https://linux-hardware.org/?probe=658ed38b10) | Jan 17, 2023 |
| Notebook      | PCx0Dx                      | [44f839ccbd](https://linux-hardware.org/?probe=44f839ccbd) | Jan 17, 2023 |
| Toshiba       | Satellite C660              | [5012a7ccfc](https://linux-hardware.org/?probe=5012a7ccfc) | Jan 17, 2023 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [d05225350d](https://linux-hardware.org/?probe=d05225350d) | Jan 17, 2023 |
| Unknown       | Unknown                     | [aea2d1af0a](https://linux-hardware.org/?probe=aea2d1af0a) | Jan 17, 2023 |
| Apple         | MacBookPro7,1               | [6445b08ce9](https://linux-hardware.org/?probe=6445b08ce9) | Jan 17, 2023 |
| Apple         | MacBookPro7,1               | [5ff11074e0](https://linux-hardware.org/?probe=5ff11074e0) | Jan 17, 2023 |
| HP            | Laptop 15-dw3xxx            | [ccce363b13](https://linux-hardware.org/?probe=ccce363b13) | Jan 17, 2023 |
| Valve         | Jupiter                     | [a75cdaa463](https://linux-hardware.org/?probe=a75cdaa463) | Jan 16, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [b1581dd523](https://linux-hardware.org/?probe=b1581dd523) | Jan 16, 2023 |
| PC Special... | P65_P67RGRERA               | [39b18604bf](https://linux-hardware.org/?probe=39b18604bf) | Jan 16, 2023 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | [31cf03aadd](https://linux-hardware.org/?probe=31cf03aadd) | Jan 15, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [cb84c73399](https://linux-hardware.org/?probe=cb84c73399) | Jan 15, 2023 |
| Sony          | VGN-NW26M                   | [3660b874bc](https://linux-hardware.org/?probe=3660b874bc) | Jan 15, 2023 |
| Sony          | VGN-NW26M                   | [5b62bf0146](https://linux-hardware.org/?probe=5b62bf0146) | Jan 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [dca583bf2e](https://linux-hardware.org/?probe=dca583bf2e) | Jan 15, 2023 |
| Toshiba       | Satellite Pro C50-A-1E6     | [9ec7c970da](https://linux-hardware.org/?probe=9ec7c970da) | Jan 15, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [38d732c237](https://linux-hardware.org/?probe=38d732c237) | Jan 15, 2023 |
| HP            | ZBook Firefly 14 inch G9... | [ca73cb526c](https://linux-hardware.org/?probe=ca73cb526c) | Jan 15, 2023 |
| Dell          | Inspiron N5110              | [20625ce99d](https://linux-hardware.org/?probe=20625ce99d) | Jan 14, 2023 |
| HP            | Pavilion g6                 | [7d44980bca](https://linux-hardware.org/?probe=7d44980bca) | Jan 14, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [d113da489f](https://linux-hardware.org/?probe=d113da489f) | Jan 14, 2023 |
| Dell          | Inspiron 15 7510            | [67f4d14824](https://linux-hardware.org/?probe=67f4d14824) | Jan 14, 2023 |
| Valve         | Jupiter                     | [4d74819919](https://linux-hardware.org/?probe=4d74819919) | Jan 14, 2023 |
| HP            | Presario F500 (GF795EA#A... | [588148e349](https://linux-hardware.org/?probe=588148e349) | Jan 14, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [da829cbbc7](https://linux-hardware.org/?probe=da829cbbc7) | Jan 14, 2023 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [e4e7a1d245](https://linux-hardware.org/?probe=e4e7a1d245) | Jan 14, 2023 |
| HP            | Pavilion g6                 | [7672e1178a](https://linux-hardware.org/?probe=7672e1178a) | Jan 14, 2023 |
| PC Special... | P65_67RSRP                  | [c7baf1a126](https://linux-hardware.org/?probe=c7baf1a126) | Jan 14, 2023 |
| Alienware     | 17 R3                       | [d4cf3c4f4d](https://linux-hardware.org/?probe=d4cf3c4f4d) | Jan 14, 2023 |
| Dell          | Vostro 3549                 | [b6970533c4](https://linux-hardware.org/?probe=b6970533c4) | Jan 13, 2023 |
| Valve         | Jupiter                     | [41e26fa7a1](https://linux-hardware.org/?probe=41e26fa7a1) | Jan 13, 2023 |
| Sony          | VPCEH3N6E                   | [15129f4c39](https://linux-hardware.org/?probe=15129f4c39) | Jan 12, 2023 |
| Lenovo        | ThinkPad T460 20FMS2BM00    | [afefa18c04](https://linux-hardware.org/?probe=afefa18c04) | Jan 12, 2023 |
| Lenovo        | ThinkPad T430 2347B85       | [01fce134df](https://linux-hardware.org/?probe=01fce134df) | Jan 12, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [ee7b0c337b](https://linux-hardware.org/?probe=ee7b0c337b) | Jan 12, 2023 |
| Google        | Link                        | [f73704d47a](https://linux-hardware.org/?probe=f73704d47a) | Jan 12, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [c3b6b8b400](https://linux-hardware.org/?probe=c3b6b8b400) | Jan 12, 2023 |
| Dell          | Latitude 3420               | [53b3f46e20](https://linux-hardware.org/?probe=53b3f46e20) | Jan 12, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [606cb1231b](https://linux-hardware.org/?probe=606cb1231b) | Jan 12, 2023 |
| Sony          | VPCEH3N6E                   | [c10a0ccff5](https://linux-hardware.org/?probe=c10a0ccff5) | Jan 12, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [566725e667](https://linux-hardware.org/?probe=566725e667) | Jan 12, 2023 |
| Lenovo        | ThinkPad W510 439123G       | [4fd1a4a217](https://linux-hardware.org/?probe=4fd1a4a217) | Jan 11, 2023 |
| Toshiba       | Satellite P50-C             | [1da161195b](https://linux-hardware.org/?probe=1da161195b) | Jan 11, 2023 |
| HP            | EliteBook 840 G4            | [680b0adb7b](https://linux-hardware.org/?probe=680b0adb7b) | Jan 11, 2023 |
| Razer         | Blade 17 (2022) - RZ09-0... | [a25c10f2dd](https://linux-hardware.org/?probe=a25c10f2dd) | Jan 11, 2023 |
| Acer          | Swift SF314-52              | [2dc4c5a4d8](https://linux-hardware.org/?probe=2dc4c5a4d8) | Jan 10, 2023 |
| HP            | ProBook 645 G2              | [1298e3efb0](https://linux-hardware.org/?probe=1298e3efb0) | Jan 10, 2023 |
| Google        | Sparky360                   | [68e8848fba](https://linux-hardware.org/?probe=68e8848fba) | Jan 10, 2023 |
| Razer x La... | TensorBook (late 2021)      | [d798473e75](https://linux-hardware.org/?probe=d798473e75) | Jan 09, 2023 |
| Acer          | Aspire 5732Z                | [f1edf0ce01](https://linux-hardware.org/?probe=f1edf0ce01) | Jan 09, 2023 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [e86a06caea](https://linux-hardware.org/?probe=e86a06caea) | Jan 09, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [ab227bc376](https://linux-hardware.org/?probe=ab227bc376) | Jan 09, 2023 |
| Dell          | XPS 15 9510                 | [ff6d324723](https://linux-hardware.org/?probe=ff6d324723) | Jan 08, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [652db107e8](https://linux-hardware.org/?probe=652db107e8) | Jan 08, 2023 |
| Toshiba       | Satellite Pro L450D         | [a2a9c2e730](https://linux-hardware.org/?probe=a2a9c2e730) | Jan 08, 2023 |
| Gateway       | MX8716B                     | [b8b9890719](https://linux-hardware.org/?probe=b8b9890719) | Jan 08, 2023 |
| Toshiba       | Satellite C660              | [c7fc660dd7](https://linux-hardware.org/?probe=c7fc660dd7) | Jan 08, 2023 |
| Dell          | Latitude E6400              | [9f15bde3f6](https://linux-hardware.org/?probe=9f15bde3f6) | Jan 08, 2023 |
| Dell          | Latitude 5290               | [1cd20e22fc](https://linux-hardware.org/?probe=1cd20e22fc) | Jan 07, 2023 |
| HP            | EliteBook 6930p             | [9a59c21db0](https://linux-hardware.org/?probe=9a59c21db0) | Jan 07, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [1239be31f9](https://linux-hardware.org/?probe=1239be31f9) | Jan 07, 2023 |
| Valve         | Jupiter                     | [17c9c6288e](https://linux-hardware.org/?probe=17c9c6288e) | Jan 07, 2023 |
| Lenovo        | ThinkPad X131e 33711Q7      | [3336313cae](https://linux-hardware.org/?probe=3336313cae) | Jan 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [cf94b53a8b](https://linux-hardware.org/?probe=cf94b53a8b) | Jan 05, 2023 |
| Lenovo        | ThinkPad X131e 33711Q7      | [7e0f8a38bf](https://linux-hardware.org/?probe=7e0f8a38bf) | Jan 04, 2023 |
| Lenovo        | Z51-70 80K6                 | [19a3a4f1c3](https://linux-hardware.org/?probe=19a3a4f1c3) | Jan 04, 2023 |
| Lenovo        | Z51-70 80K6                 | [c1a3bf015a](https://linux-hardware.org/?probe=c1a3bf015a) | Jan 04, 2023 |
| Sony          | VPCEH3N6E                   | [5253826cac](https://linux-hardware.org/?probe=5253826cac) | Jan 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [d83005eb10](https://linux-hardware.org/?probe=d83005eb10) | Jan 03, 2023 |
| ASUSTek       | X102BA                      | [5ccb37c1d7](https://linux-hardware.org/?probe=5ccb37c1d7) | Jan 03, 2023 |
| ASUSTek       | X102BA                      | [bd49b43116](https://linux-hardware.org/?probe=bd49b43116) | Jan 03, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [aa875f1083](https://linux-hardware.org/?probe=aa875f1083) | Jan 02, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [9ed57548b6](https://linux-hardware.org/?probe=9ed57548b6) | Jan 02, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [90603e4ab3](https://linux-hardware.org/?probe=90603e4ab3) | Jan 02, 2023 |
| Valve         | Jupiter                     | [ae42b505d4](https://linux-hardware.org/?probe=ae42b505d4) | Jan 02, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [7ff55c14b4](https://linux-hardware.org/?probe=7ff55c14b4) | Jan 02, 2023 |
| Acer          | Aspire A315-31              | [4a79c65764](https://linux-hardware.org/?probe=4a79c65764) | Jan 02, 2023 |
| Toshiba       | Satellite C850-1GL          | [6326869c9e](https://linux-hardware.org/?probe=6326869c9e) | Jan 02, 2023 |
| Valve         | Jupiter                     | [72a2446cd3](https://linux-hardware.org/?probe=72a2446cd3) | Jan 02, 2023 |
| Advent        | Modena M201 Blue            | [abaae97a6f](https://linux-hardware.org/?probe=abaae97a6f) | Jan 01, 2023 |
| Dell          | Inspiron 5580               | [c6a044c898](https://linux-hardware.org/?probe=c6a044c898) | Jan 01, 2023 |
| Toshiba       | EQUIUM A100                 | [424904034a](https://linux-hardware.org/?probe=424904034a) | Jan 01, 2023 |
| Dell          | Latitude E7270              | [09f72d101d](https://linux-hardware.org/?probe=09f72d101d) | Jan 01, 2023 |
| Toshiba       | Satellite C50-B             | [b1007671e3](https://linux-hardware.org/?probe=b1007671e3) | Jan 01, 2023 |
| Packard Be... | EasyNote TM97               | [fad44d67ab](https://linux-hardware.org/?probe=fad44d67ab) | Jan 01, 2023 |
| Valve         | Jupiter                     | [10366e2627](https://linux-hardware.org/?probe=10366e2627) | Jan 01, 2023 |
| Valve         | Jupiter                     | [c0fb48bccb](https://linux-hardware.org/?probe=c0fb48bccb) | Dec 31, 2022 |
| Lenovo        | ThinkPad P16s Gen 1 21BT... | [b68fa80860](https://linux-hardware.org/?probe=b68fa80860) | Dec 31, 2022 |
| Lenovo        | Yoga 2 13 20344             | [39c9c8aaea](https://linux-hardware.org/?probe=39c9c8aaea) | Dec 31, 2022 |
| Dell          | Latitude E5440              | [9578ad1ea3](https://linux-hardware.org/?probe=9578ad1ea3) | Dec 31, 2022 |
| Valve         | Jupiter                     | [294144217a](https://linux-hardware.org/?probe=294144217a) | Dec 30, 2022 |
| Lenovo        | ThinkPad T480 20L50000UK    | [5043868e71](https://linux-hardware.org/?probe=5043868e71) | Dec 30, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | [465d2da36b](https://linux-hardware.org/?probe=465d2da36b) | Dec 30, 2022 |
| HP            | ZBook Studio G5             | [6d0b6881ac](https://linux-hardware.org/?probe=6d0b6881ac) | Dec 30, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | [7a685e175c](https://linux-hardware.org/?probe=7a685e175c) | Dec 30, 2022 |
| Toshiba       | Satellite C850-1GL          | [f6f61f1841](https://linux-hardware.org/?probe=f6f61f1841) | Dec 30, 2022 |
| Toshiba       | Satellite C850-1GL          | [796edd73f6](https://linux-hardware.org/?probe=796edd73f6) | Dec 30, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [e7a5c8704b](https://linux-hardware.org/?probe=e7a5c8704b) | Dec 30, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [fa210be351](https://linux-hardware.org/?probe=fa210be351) | Dec 30, 2022 |
| MSI           | Stealth GS66 12UGS          | [da812c8fa2](https://linux-hardware.org/?probe=da812c8fa2) | Dec 30, 2022 |
| Apple         | MacBookAir9,1               | [d560c94d76](https://linux-hardware.org/?probe=d560c94d76) | Dec 30, 2022 |
| Dell          | Inspiron N5110              | [08682d735c](https://linux-hardware.org/?probe=08682d735c) | Dec 30, 2022 |
| Acer          | Swift SF314-57G             | [9d71d087d8](https://linux-hardware.org/?probe=9d71d087d8) | Dec 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [23d1e04f4c](https://linux-hardware.org/?probe=23d1e04f4c) | Dec 29, 2022 |
| Lenovo        | Z50-70 20354                | [7b8f5e4379](https://linux-hardware.org/?probe=7b8f5e4379) | Dec 29, 2022 |
| Samsung       | NB30/N146                   | [7f9b976789](https://linux-hardware.org/?probe=7f9b976789) | Dec 29, 2022 |
| Lenovo        | ThinkPad T480 20L50000UK    | [f5cbe897b8](https://linux-hardware.org/?probe=f5cbe897b8) | Dec 29, 2022 |
| Unknown       | Unknown                     | [0c7bea2d0f](https://linux-hardware.org/?probe=0c7bea2d0f) | Dec 29, 2022 |
| PC Special... | PCX0DX                      | [0a33ad889c](https://linux-hardware.org/?probe=0a33ad889c) | Dec 28, 2022 |
| Lenovo        | ThinkPad T480 20L50000UK    | [41f77d037b](https://linux-hardware.org/?probe=41f77d037b) | Dec 28, 2022 |
| Alienware     | M11x R2                     | [a0da72bec0](https://linux-hardware.org/?probe=a0da72bec0) | Dec 28, 2022 |
| Lenovo        | ThinkPad X230 23252S4       | [667dcc287e](https://linux-hardware.org/?probe=667dcc287e) | Dec 28, 2022 |
| Toshiba       | Satellite C50-B             | [31241c1f30](https://linux-hardware.org/?probe=31241c1f30) | Dec 28, 2022 |
| Acer          | Swift SFX14-51G             | [16c5f2a610](https://linux-hardware.org/?probe=16c5f2a610) | Dec 27, 2022 |
| Valve         | Jupiter                     | [db0586ef7b](https://linux-hardware.org/?probe=db0586ef7b) | Dec 27, 2022 |
| Acer          | Predator PH317-56           | [b74460d91c](https://linux-hardware.org/?probe=b74460d91c) | Dec 27, 2022 |
| Valve         | Jupiter                     | [a1ab930dc6](https://linux-hardware.org/?probe=a1ab930dc6) | Dec 27, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [7a3513a2e1](https://linux-hardware.org/?probe=7a3513a2e1) | Dec 27, 2022 |
| HP            | Pavilion dv6                | [d759125511](https://linux-hardware.org/?probe=d759125511) | Dec 26, 2022 |
| Valve         | Jupiter                     | [1c516dc209](https://linux-hardware.org/?probe=1c516dc209) | Dec 26, 2022 |
| HP            | ENVY Notebook               | [8c7d592182](https://linux-hardware.org/?probe=8c7d592182) | Dec 26, 2022 |
| Acer          | Aspire ES1-533              | [3b5fa6d85a](https://linux-hardware.org/?probe=3b5fa6d85a) | Dec 26, 2022 |
| Star Labs     | StarLite                    | [0d27e6f7ee](https://linux-hardware.org/?probe=0d27e6f7ee) | Dec 25, 2022 |
| Lenovo        | ThinkPad T450 20BUS3GN01    | [e88a11d2bb](https://linux-hardware.org/?probe=e88a11d2bb) | Dec 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [0413176ecc](https://linux-hardware.org/?probe=0413176ecc) | Dec 25, 2022 |
| Lenovo        | ThinkPad T510 4313CTO       | [a3db191efa](https://linux-hardware.org/?probe=a3db191efa) | Dec 24, 2022 |
| Lenovo        | ThinkPad SL 2746N8G         | [f540a3a892](https://linux-hardware.org/?probe=f540a3a892) | Dec 23, 2022 |
| Toshiba       | Satellite Pro C50-A-1MX     | [78487975ce](https://linux-hardware.org/?probe=78487975ce) | Dec 23, 2022 |
| Acer          | Swift SF314-57G             | [53678dec76](https://linux-hardware.org/?probe=53678dec76) | Dec 22, 2022 |
| Lenovo        | ThinkPad P52 20MAS25B1X     | [f82f15da88](https://linux-hardware.org/?probe=f82f15da88) | Dec 22, 2022 |
| Dell          | Latitude E5430 non-vPro     | [cc88046606](https://linux-hardware.org/?probe=cc88046606) | Dec 22, 2022 |
| Acer          | Aspire V5-571               | [b4de144f3e](https://linux-hardware.org/?probe=b4de144f3e) | Dec 22, 2022 |
| System76      | Lemur Pro                   | [ed549bfe74](https://linux-hardware.org/?probe=ed549bfe74) | Dec 21, 2022 |
| System76      | Lemur Pro                   | [30be17e71c](https://linux-hardware.org/?probe=30be17e71c) | Dec 21, 2022 |
| Apple         | MacBook5,1                  | [d565332e52](https://linux-hardware.org/?probe=d565332e52) | Dec 21, 2022 |
| Acer          | Aspire 5735                 | [d2850b2e08](https://linux-hardware.org/?probe=d2850b2e08) | Dec 21, 2022 |
| Apple         | MacBookPro7,1               | [dbb80c6a3c](https://linux-hardware.org/?probe=dbb80c6a3c) | Dec 21, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [422faa5041](https://linux-hardware.org/?probe=422faa5041) | Dec 20, 2022 |
| RM Educati... | RM                          | [758b521362](https://linux-hardware.org/?probe=758b521362) | Dec 20, 2022 |
| Dell          | XPS 15 9510                 | [870c784f85](https://linux-hardware.org/?probe=870c784f85) | Dec 20, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | [1b0b5a798f](https://linux-hardware.org/?probe=1b0b5a798f) | Dec 20, 2022 |
| Dell          | XPS 15 9560                 | [1f1c0123c7](https://linux-hardware.org/?probe=1f1c0123c7) | Dec 19, 2022 |
| Toshiba       | EQUIUM A300D                | [ffde5ccef4](https://linux-hardware.org/?probe=ffde5ccef4) | Dec 19, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | [0644973fc3](https://linux-hardware.org/?probe=0644973fc3) | Dec 19, 2022 |
| HP            | 620                         | [c5ed6ae3bf](https://linux-hardware.org/?probe=c5ed6ae3bf) | Dec 19, 2022 |
| HP            | ENVY Laptop 15-ep0xxx       | [6c6dcce3d8](https://linux-hardware.org/?probe=6c6dcce3d8) | Dec 18, 2022 |
| Dell          | Studio XPS 1645             | [e1c0f5a53b](https://linux-hardware.org/?probe=e1c0f5a53b) | Dec 18, 2022 |
| Dell          | Studio XPS 1645             | [2c26ce45b7](https://linux-hardware.org/?probe=2c26ce45b7) | Dec 18, 2022 |
| MSI           | Delta 15 A5EFK              | [c793cb6f38](https://linux-hardware.org/?probe=c793cb6f38) | Dec 18, 2022 |
| Acer          | Aspire ES1-531              | [28dc03a1bc](https://linux-hardware.org/?probe=28dc03a1bc) | Dec 18, 2022 |
| Fusion5       | C60Bv2-128GB                | [7cc701c4de](https://linux-hardware.org/?probe=7cc701c4de) | Dec 17, 2022 |
| Valve         | Jupiter                     | [5fee494e26](https://linux-hardware.org/?probe=5fee494e26) | Dec 17, 2022 |
| Valve         | Jupiter                     | [d47eae36fe](https://linux-hardware.org/?probe=d47eae36fe) | Dec 17, 2022 |
| Lenovo        | ThinkPad X230 23255NG       | [5cc0ff812b](https://linux-hardware.org/?probe=5cc0ff812b) | Dec 16, 2022 |
| Lenovo        | ThinkPad X230 23255NG       | [062a6ed428](https://linux-hardware.org/?probe=062a6ed428) | Dec 16, 2022 |
| HP            | Pavilion g6                 | [d1bfb26644](https://linux-hardware.org/?probe=d1bfb26644) | Dec 16, 2022 |
| Lenovo        | ThinkPad T430 2344BZU       | [a69be3386b](https://linux-hardware.org/?probe=a69be3386b) | Dec 16, 2022 |
| Valve         | Jupiter                     | [bb07a9abda](https://linux-hardware.org/?probe=bb07a9abda) | Dec 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [06bbbb04a9](https://linux-hardware.org/?probe=06bbbb04a9) | Dec 15, 2022 |
| Acer          | Aspire ES1-512              | [302ea6f1dd](https://linux-hardware.org/?probe=302ea6f1dd) | Dec 14, 2022 |
| HP            | 355 G2                      | [c826d17369](https://linux-hardware.org/?probe=c826d17369) | Dec 14, 2022 |
| HP            | 355 G2                      | [f785946641](https://linux-hardware.org/?probe=f785946641) | Dec 14, 2022 |
| Valve         | Jupiter                     | [9330717977](https://linux-hardware.org/?probe=9330717977) | Dec 14, 2022 |
| Star Labs     | StarBook                    | [719a73ae26](https://linux-hardware.org/?probe=719a73ae26) | Dec 13, 2022 |
| HP            | ProBook 440 G7              | [ca2ba2d622](https://linux-hardware.org/?probe=ca2ba2d622) | Dec 13, 2022 |
| Lenovo        | ThinkPad T400 647419G       | [a73b681605](https://linux-hardware.org/?probe=a73b681605) | Dec 13, 2022 |
| Apple         | MacBookPro13,3              | [10b29f88c5](https://linux-hardware.org/?probe=10b29f88c5) | Dec 12, 2022 |
| MSI           | Prestige 14 A11SC           | [7fa118f812](https://linux-hardware.org/?probe=7fa118f812) | Dec 11, 2022 |
| Star Labs     | StarLite                    | [0d83c191fa](https://linux-hardware.org/?probe=0d83c191fa) | Dec 10, 2022 |
| Acer          | Aspire V5-573               | [1d88db5ee2](https://linux-hardware.org/?probe=1d88db5ee2) | Dec 10, 2022 |
| HP            | ProBook 6570b               | [073546a981](https://linux-hardware.org/?probe=073546a981) | Dec 10, 2022 |
| Star Labs     | StarLite                    | [4446ba1d6a](https://linux-hardware.org/?probe=4446ba1d6a) | Dec 10, 2022 |
| Toshiba       | Satellite C855-1W4          | [19149f22c5](https://linux-hardware.org/?probe=19149f22c5) | Dec 09, 2022 |
| Dell          | Latitude 7390               | [79812ceedd](https://linux-hardware.org/?probe=79812ceedd) | Dec 09, 2022 |
| Lenovo        | ThinkPad L560 20F2S0DA00    | [e8fe4392be](https://linux-hardware.org/?probe=e8fe4392be) | Dec 09, 2022 |
| Lenovo        | ThinkPad L560 20F2S0DA00    | [cf32d7158c](https://linux-hardware.org/?probe=cf32d7158c) | Dec 09, 2022 |
| Lenovo        | Z70-80 80FG                 | [492071e526](https://linux-hardware.org/?probe=492071e526) | Dec 09, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1200... | [8ce314db56](https://linux-hardware.org/?probe=8ce314db56) | Dec 08, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1200... | [858f06f0e5](https://linux-hardware.org/?probe=858f06f0e5) | Dec 08, 2022 |
| Google        | Nami                        | [9861d341a7](https://linux-hardware.org/?probe=9861d341a7) | Dec 08, 2022 |
| MSI           | Alpha 15 A4DEK              | [d2a30990d9](https://linux-hardware.org/?probe=d2a30990d9) | Dec 08, 2022 |
| LG Electro... | 16Z90P-K.AA78A1             | [1646f1763d](https://linux-hardware.org/?probe=1646f1763d) | Dec 08, 2022 |
| ASUSTek       | N55SF                       | [cfb7b0f7ad](https://linux-hardware.org/?probe=cfb7b0f7ad) | Dec 07, 2022 |
| Acer          | Aspire A515-45              | [7eebb7f601](https://linux-hardware.org/?probe=7eebb7f601) | Dec 07, 2022 |
| Valve         | Jupiter                     | [9fc6ea26bb](https://linux-hardware.org/?probe=9fc6ea26bb) | Dec 07, 2022 |
| Valve         | Jupiter                     | [70cd36710e](https://linux-hardware.org/?probe=70cd36710e) | Dec 06, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1200... | [05f4b7d7cf](https://linux-hardware.org/?probe=05f4b7d7cf) | Dec 06, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [02130c9bbb](https://linux-hardware.org/?probe=02130c9bbb) | Dec 06, 2022 |
| HP            | EliteBook 2560p             | [bbe22c0ea7](https://linux-hardware.org/?probe=bbe22c0ea7) | Dec 06, 2022 |
| Valve         | Jupiter                     | [69e8f9815d](https://linux-hardware.org/?probe=69e8f9815d) | Dec 05, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1200... | [6f0ceb7a46](https://linux-hardware.org/?probe=6f0ceb7a46) | Dec 05, 2022 |
| Dell          | Latitude E5400              | [ab5b64fe8a](https://linux-hardware.org/?probe=ab5b64fe8a) | Dec 05, 2022 |
| Google        | Chell                       | [3ffe532315](https://linux-hardware.org/?probe=3ffe532315) | Dec 05, 2022 |
| HP            | EliteBook 2560p             | [21462d212f](https://linux-hardware.org/?probe=21462d212f) | Dec 05, 2022 |
| Dell          | XPS 13 9343                 | [476763a913](https://linux-hardware.org/?probe=476763a913) | Dec 05, 2022 |
| Dell          | Inspiron 5570               | [d9009fc1f5](https://linux-hardware.org/?probe=d9009fc1f5) | Dec 05, 2022 |
| Dell          | Latitude 7490               | [e75a902d11](https://linux-hardware.org/?probe=e75a902d11) | Dec 05, 2022 |
| Valve         | Jupiter                     | [13c990586f](https://linux-hardware.org/?probe=13c990586f) | Dec 05, 2022 |
| Lenovo        | ThinkPad T450 20BUS00700    | [141e7e9992](https://linux-hardware.org/?probe=141e7e9992) | Dec 04, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [f5be4eb37d](https://linux-hardware.org/?probe=f5be4eb37d) | Dec 04, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [6c74973e99](https://linux-hardware.org/?probe=6c74973e99) | Dec 04, 2022 |
| HP            | Notebook                    | [610cea9ebc](https://linux-hardware.org/?probe=610cea9ebc) | Dec 04, 2022 |
| Star Labs     | StarLite                    | [d4cf1b0cd0](https://linux-hardware.org/?probe=d4cf1b0cd0) | Dec 03, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21E3C... | [c99bd4ef76](https://linux-hardware.org/?probe=c99bd4ef76) | Dec 03, 2022 |
| Dell          | Latitude 5591               | [f5735acca7](https://linux-hardware.org/?probe=f5735acca7) | Dec 02, 2022 |
| Dell          | Latitude E5570              | [4db5cd2ef4](https://linux-hardware.org/?probe=4db5cd2ef4) | Dec 01, 2022 |
| Dell          | XPS 13 9310                 | [aadf1c39a0](https://linux-hardware.org/?probe=aadf1c39a0) | Dec 01, 2022 |
| Dell          | Latitude E5520              | [92a4c9b5ef](https://linux-hardware.org/?probe=92a4c9b5ef) | Nov 30, 2022 |
| HP            | ElitePad 1000 G2            | [0b05465735](https://linux-hardware.org/?probe=0b05465735) | Nov 30, 2022 |
| Dell          | Inspiron N5010              | [687aa83749](https://linux-hardware.org/?probe=687aa83749) | Nov 30, 2022 |
| Dell          | XPS 15 9500                 | [f9215967d3](https://linux-hardware.org/?probe=f9215967d3) | Nov 30, 2022 |
| Dell          | Inspiron 5570               | [9e4bdbc81d](https://linux-hardware.org/?probe=9e4bdbc81d) | Nov 29, 2022 |
| Dell          | Inspiron 5570               | [399346217e](https://linux-hardware.org/?probe=399346217e) | Nov 29, 2022 |
| HP            | Laptop 14s-fq0xxx           | [e71c023456](https://linux-hardware.org/?probe=e71c023456) | Nov 29, 2022 |
| Valve         | Jupiter                     | [0f40429822](https://linux-hardware.org/?probe=0f40429822) | Nov 29, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [e0bdd2fbd2](https://linux-hardware.org/?probe=e0bdd2fbd2) | Nov 29, 2022 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [d258962c35](https://linux-hardware.org/?probe=d258962c35) | Nov 28, 2022 |
| Timi          | TM1613                      | [37036a425d](https://linux-hardware.org/?probe=37036a425d) | Nov 28, 2022 |
| Dell          | XPS 15 7590                 | [8072eb50aa](https://linux-hardware.org/?probe=8072eb50aa) | Nov 28, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [68e68e1e01](https://linux-hardware.org/?probe=68e68e1e01) | Nov 28, 2022 |
| Lenovo        | ThinkPad E490 20N8000RUK    | [6816e8f5ca](https://linux-hardware.org/?probe=6816e8f5ca) | Nov 27, 2022 |
| Lenovo        | ThinkPad E490 20N8000RUK    | [06c690a0e1](https://linux-hardware.org/?probe=06c690a0e1) | Nov 27, 2022 |
| Apple         | MacBookPro6,2               | [409c3edc19](https://linux-hardware.org/?probe=409c3edc19) | Nov 27, 2022 |
| Dell          | XPS 15 7590                 | [18b1ecf4fd](https://linux-hardware.org/?probe=18b1ecf4fd) | Nov 27, 2022 |
| MSI           | GL62 7QF                    | [abd74be332](https://linux-hardware.org/?probe=abd74be332) | Nov 27, 2022 |
| Valve         | Jupiter                     | [1d12c5839a](https://linux-hardware.org/?probe=1d12c5839a) | Nov 27, 2022 |
| Dell          | Inspiron 1545               | [07df50a08c](https://linux-hardware.org/?probe=07df50a08c) | Nov 27, 2022 |
| Toshiba       | Satellite C50D-B            | [c9feb7eed2](https://linux-hardware.org/?probe=c9feb7eed2) | Nov 26, 2022 |
| Lenovo        | V145-15AST 81MT             | [759ad3eb43](https://linux-hardware.org/?probe=759ad3eb43) | Nov 26, 2022 |
| Valve         | Jupiter                     | [0a172d85fd](https://linux-hardware.org/?probe=0a172d85fd) | Nov 26, 2022 |
| Lenovo        | ThinkPad L13 20R3000FUK     | [c3ff5b014d](https://linux-hardware.org/?probe=c3ff5b014d) | Nov 26, 2022 |
| Toshiba       | Satellite C50D-B            | [92d54fef2b](https://linux-hardware.org/?probe=92d54fef2b) | Nov 25, 2022 |
| Acer          | Aspire ES1-512              | [85c0936ee0](https://linux-hardware.org/?probe=85c0936ee0) | Nov 25, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [0a9d327f59](https://linux-hardware.org/?probe=0a9d327f59) | Nov 25, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [869a5a808f](https://linux-hardware.org/?probe=869a5a808f) | Nov 25, 2022 |
| Acer          | Aspire A315-41              | [4408f2ceff](https://linux-hardware.org/?probe=4408f2ceff) | Nov 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [770e9d413e](https://linux-hardware.org/?probe=770e9d413e) | Nov 24, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [dce6415c9e](https://linux-hardware.org/?probe=dce6415c9e) | Nov 23, 2022 |
| HP            | EliteBook 2560p             | [4c27c5511f](https://linux-hardware.org/?probe=4c27c5511f) | Nov 23, 2022 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [0168e30f4f](https://linux-hardware.org/?probe=0168e30f4f) | Nov 23, 2022 |
| Apple         | MacBookPro12,1              | [063ffbb0e8](https://linux-hardware.org/?probe=063ffbb0e8) | Nov 23, 2022 |
| HP            | EliteBook 8530w             | [0c1d6d2201](https://linux-hardware.org/?probe=0c1d6d2201) | Nov 22, 2022 |
| Toshiba       | Satellite L750              | [b2e96ee4b2](https://linux-hardware.org/?probe=b2e96ee4b2) | Nov 21, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [16859cf0ca](https://linux-hardware.org/?probe=16859cf0ca) | Nov 21, 2022 |
| Alienware     | M17xR3                      | [d472e55685](https://linux-hardware.org/?probe=d472e55685) | Nov 20, 2022 |
| HP            | ENVY Laptop 13-ba1xxx       | [4a270e871f](https://linux-hardware.org/?probe=4a270e871f) | Nov 20, 2022 |
| Medion        | BEAST X25                   | [fddb326ca2](https://linux-hardware.org/?probe=fddb326ca2) | Nov 19, 2022 |
| Toshiba       | Satellite L50D-B            | [68d1c8a80a](https://linux-hardware.org/?probe=68d1c8a80a) | Nov 19, 2022 |
| ASUSTek       | K55A                        | [d09b309d4d](https://linux-hardware.org/?probe=d09b309d4d) | Nov 19, 2022 |
| Valve         | Jupiter                     | [afdcde154a](https://linux-hardware.org/?probe=afdcde154a) | Nov 18, 2022 |
| HP            | ProBook 450 G6              | [ceac47decc](https://linux-hardware.org/?probe=ceac47decc) | Nov 18, 2022 |
| HP            | EliteBook 840 G6            | [1faf8e38b4](https://linux-hardware.org/?probe=1faf8e38b4) | Nov 18, 2022 |
| HP            | ProBook 450 G6              | [5abeec1752](https://linux-hardware.org/?probe=5abeec1752) | Nov 18, 2022 |
| Lenovo        | ThinkPad T480 20L50004UK    | [8f4df3bbda](https://linux-hardware.org/?probe=8f4df3bbda) | Nov 18, 2022 |
| HP            | EliteBook 8470p             | [f324f5bc16](https://linux-hardware.org/?probe=f324f5bc16) | Nov 18, 2022 |
| Acer          | Aspire 6930G                | [05ad62f97d](https://linux-hardware.org/?probe=05ad62f97d) | Nov 17, 2022 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | [cc20cc9828](https://linux-hardware.org/?probe=cc20cc9828) | Nov 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [545eb5e46c](https://linux-hardware.org/?probe=545eb5e46c) | Nov 16, 2022 |
| Dell          | Latitude 5410               | [dd9eb324db](https://linux-hardware.org/?probe=dd9eb324db) | Nov 16, 2022 |
| Dell          | Vostro 3590                 | [67ffc3ab77](https://linux-hardware.org/?probe=67ffc3ab77) | Nov 16, 2022 |
| Razer x La... | TensorBook (late 2021)      | [b7fff356a7](https://linux-hardware.org/?probe=b7fff356a7) | Nov 16, 2022 |
| Toshiba       | Satellite Pro U500          | [064a36a5bb](https://linux-hardware.org/?probe=064a36a5bb) | Nov 16, 2022 |
| Dixonsxp      | F71IX1                      | [816c618ae7](https://linux-hardware.org/?probe=816c618ae7) | Nov 15, 2022 |
| OEGStone      | NOTCHA-322                  | [a5f28e095e](https://linux-hardware.org/?probe=a5f28e095e) | Nov 15, 2022 |
| Dell          | Inspiron 7501               | [15cd1d588f](https://linux-hardware.org/?probe=15cd1d588f) | Nov 15, 2022 |
| Dell          | Latitude E6320              | [a4767dfe35](https://linux-hardware.org/?probe=a4767dfe35) | Nov 14, 2022 |
| Toshiba       | Satellite L50D-B            | [6c53b0c32d](https://linux-hardware.org/?probe=6c53b0c32d) | Nov 14, 2022 |
| HP            | Pavilion dv6                | [fe166a1906](https://linux-hardware.org/?probe=fe166a1906) | Nov 14, 2022 |
| Acer          | Extensa 2530                | [ac83b4e3e9](https://linux-hardware.org/?probe=ac83b4e3e9) | Nov 14, 2022 |
| Dell          | Latitude D630               | [3a15603bd6](https://linux-hardware.org/?probe=3a15603bd6) | Nov 13, 2022 |
| HP            | EliteBook 6930p             | [4b6c28bf91](https://linux-hardware.org/?probe=4b6c28bf91) | Nov 13, 2022 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | [62cbc0b03d](https://linux-hardware.org/?probe=62cbc0b03d) | Nov 13, 2022 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | [305242c389](https://linux-hardware.org/?probe=305242c389) | Nov 13, 2022 |
| HP            | Presario CQ58               | [7a2e365b72](https://linux-hardware.org/?probe=7a2e365b72) | Nov 13, 2022 |
| Valve         | Jupiter                     | [5c1a39b012](https://linux-hardware.org/?probe=5c1a39b012) | Nov 13, 2022 |
| Lenovo        | IdeaPadFlex 14 20308        | [04a42845bf](https://linux-hardware.org/?probe=04a42845bf) | Nov 12, 2022 |
| Lenovo        | ThinkPad X260 20F5S28R00    | [ac107ff6e8](https://linux-hardware.org/?probe=ac107ff6e8) | Nov 12, 2022 |
| HP            | ProBook 455 G2              | [1a5d0a1618](https://linux-hardware.org/?probe=1a5d0a1618) | Nov 12, 2022 |
| System76      | Oryx Pro                    | [5439d56b25](https://linux-hardware.org/?probe=5439d56b25) | Nov 12, 2022 |
| Fujitsu       | STYLISTIC Q572              | [afd0e0efc4](https://linux-hardware.org/?probe=afd0e0efc4) | Nov 12, 2022 |
| Dell          | Latitude D630               | [3e964fdd59](https://linux-hardware.org/?probe=3e964fdd59) | Nov 12, 2022 |
| HP            | Laptop 15s-fq1xxx           | [eb5ece0bb3](https://linux-hardware.org/?probe=eb5ece0bb3) | Nov 12, 2022 |
| Valve         | Jupiter                     | [54bca16c61](https://linux-hardware.org/?probe=54bca16c61) | Nov 11, 2022 |
| HP            | EliteBook 840 G3            | [161b81845e](https://linux-hardware.org/?probe=161b81845e) | Nov 11, 2022 |
| Dell          | XPS 15 7590                 | [d05d4d5371](https://linux-hardware.org/?probe=d05d4d5371) | Nov 10, 2022 |
| Valve         | Jupiter                     | [6227fbbebb](https://linux-hardware.org/?probe=6227fbbebb) | Nov 10, 2022 |
| Valve         | Jupiter                     | [340ef95fd9](https://linux-hardware.org/?probe=340ef95fd9) | Nov 08, 2022 |
| Valve         | Jupiter                     | [5673f6f505](https://linux-hardware.org/?probe=5673f6f505) | Nov 08, 2022 |
| Valve         | Jupiter                     | [1991a35643](https://linux-hardware.org/?probe=1991a35643) | Nov 08, 2022 |
| Linx          | LINX1010B                   | [fa6d1ebd57](https://linux-hardware.org/?probe=fa6d1ebd57) | Nov 07, 2022 |
| HP            | Pavilion dv5000 (EU087EA... | [185c483599](https://linux-hardware.org/?probe=185c483599) | Nov 07, 2022 |
| Entroware     | Hybris                      | [bf5c8bcbaf](https://linux-hardware.org/?probe=bf5c8bcbaf) | Nov 07, 2022 |
| Notebook      | PA70ES                      | [7254b24693](https://linux-hardware.org/?probe=7254b24693) | Nov 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [0c0bde7c74](https://linux-hardware.org/?probe=0c0bde7c74) | Nov 06, 2022 |
| HP            | Pavilion dv5000 (EU087EA... | [d763771ba6](https://linux-hardware.org/?probe=d763771ba6) | Nov 06, 2022 |
| Dell          | Inspiron 1525               | [f28061e4da](https://linux-hardware.org/?probe=f28061e4da) | Nov 06, 2022 |
| HP            | 250 G7 Notebook PC          | [d29197ed66](https://linux-hardware.org/?probe=d29197ed66) | Nov 06, 2022 |
| Dell          | G7 7700                     | [ba3a89822a](https://linux-hardware.org/?probe=ba3a89822a) | Nov 06, 2022 |
| HP            | ENVY Laptop 13-aq0xxx       | [340f509c6b](https://linux-hardware.org/?probe=340f509c6b) | Nov 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [256002ea80](https://linux-hardware.org/?probe=256002ea80) | Nov 06, 2022 |
| Valve         | Jupiter                     | [df94c19aa6](https://linux-hardware.org/?probe=df94c19aa6) | Nov 06, 2022 |
| Valve         | Jupiter                     | [55420be889](https://linux-hardware.org/?probe=55420be889) | Nov 05, 2022 |
| HP            | Pavilion g7                 | [4ad4ed4c47](https://linux-hardware.org/?probe=4ad4ed4c47) | Nov 05, 2022 |
| Acer          | Acadia V1.45                | [654585bbaf](https://linux-hardware.org/?probe=654585bbaf) | Nov 05, 2022 |
| HP            | 250 G7 Notebook PC          | [e5684c9b19](https://linux-hardware.org/?probe=e5684c9b19) | Nov 05, 2022 |
| Acer          | TravelMate B118-M           | [8b7e60aef0](https://linux-hardware.org/?probe=8b7e60aef0) | Nov 05, 2022 |
| Samsung       | 700T1C                      | [c561c328b3](https://linux-hardware.org/?probe=c561c328b3) | Nov 05, 2022 |
| Lenovo        | ThinkPad L520 78596CG       | [094f09bcf8](https://linux-hardware.org/?probe=094f09bcf8) | Nov 04, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [f0be03da28](https://linux-hardware.org/?probe=f0be03da28) | Nov 04, 2022 |
| GEO           | GEOBOOK 2E                  | [2a802edc5a](https://linux-hardware.org/?probe=2a802edc5a) | Nov 04, 2022 |
| GEO           | GEOBOOK 2E                  | [80e1206b6d](https://linux-hardware.org/?probe=80e1206b6d) | Nov 04, 2022 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [a43927efff](https://linux-hardware.org/?probe=a43927efff) | Nov 03, 2022 |
| Dell          | Inspiron 7501               | [3eae1f74ca](https://linux-hardware.org/?probe=3eae1f74ca) | Nov 03, 2022 |
| Samsung       | 400B2B/400B2B               | [a909b4b203](https://linux-hardware.org/?probe=a909b4b203) | Nov 03, 2022 |
| Star Labs     | StarBook                    | [1cfe5c0920](https://linux-hardware.org/?probe=1cfe5c0920) | Nov 02, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [c693004e08](https://linux-hardware.org/?probe=c693004e08) | Nov 02, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [ebe8179d26](https://linux-hardware.org/?probe=ebe8179d26) | Nov 02, 2022 |
| Dell          | Inspiron 15-3567            | [a9b57edf35](https://linux-hardware.org/?probe=a9b57edf35) | Nov 02, 2022 |
| Dell          | Inspiron 15 3511            | [5786a01590](https://linux-hardware.org/?probe=5786a01590) | Nov 02, 2022 |
| Acer          | Aspire A315-54              | [1421a5a4e9](https://linux-hardware.org/?probe=1421a5a4e9) | Nov 02, 2022 |
| PC Special... | Elimina Iv 15               | [f462ba9c43](https://linux-hardware.org/?probe=f462ba9c43) | Nov 02, 2022 |
| ASUSTek       | P52F                        | [a83cb4c35d](https://linux-hardware.org/?probe=a83cb4c35d) | Nov 01, 2022 |
| Packard Be... | EasyNote TK85               | [a233571587](https://linux-hardware.org/?probe=a233571587) | Oct 31, 2022 |
| ASUSTek       | G75VW                       | [6f1d41a85c](https://linux-hardware.org/?probe=6f1d41a85c) | Oct 31, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | [92e9764aa0](https://linux-hardware.org/?probe=92e9764aa0) | Oct 31, 2022 |
| Acer          | Swift SF314-512             | [d6bf187cc9](https://linux-hardware.org/?probe=d6bf187cc9) | Oct 31, 2022 |
| MSI           | Modern 14 B10MW             | [cf2b620a60](https://linux-hardware.org/?probe=cf2b620a60) | Oct 31, 2022 |
| Valve         | Jupiter                     | [38d0d0e32a](https://linux-hardware.org/?probe=38d0d0e32a) | Oct 31, 2022 |
| Apple         | MacBookPro5,5               | [00e1f1f754](https://linux-hardware.org/?probe=00e1f1f754) | Oct 31, 2022 |
| Acer          | Swift SFX14-51G             | [6812d7cf22](https://linux-hardware.org/?probe=6812d7cf22) | Oct 30, 2022 |
| HP            | Pavilion 15                 | [f1eac2c0c3](https://linux-hardware.org/?probe=f1eac2c0c3) | Oct 30, 2022 |
| Lenovo        | ThinkPad T480 20L6S82F0C    | [c06d6a27f5](https://linux-hardware.org/?probe=c06d6a27f5) | Oct 30, 2022 |
| Lenovo        | ThinkPad L560 20F2S0DA00    | [bf8945db85](https://linux-hardware.org/?probe=bf8945db85) | Oct 30, 2022 |
| GEO           | GeoBook3                    | [133a4460f6](https://linux-hardware.org/?probe=133a4460f6) | Oct 29, 2022 |
| Toshiba       | Satellite C660              | [242fa16882](https://linux-hardware.org/?probe=242fa16882) | Oct 29, 2022 |
| Dell          | Latitude E6530              | [cdd3b5ce40](https://linux-hardware.org/?probe=cdd3b5ce40) | Oct 28, 2022 |
| Valve         | Jupiter                     | [127bd00558](https://linux-hardware.org/?probe=127bd00558) | Oct 28, 2022 |
| Tactus        | GeoBook 110                 | [aad56b27f0](https://linux-hardware.org/?probe=aad56b27f0) | Oct 28, 2022 |
| Dell          | XPS 13 9305                 | [20bf043d6f](https://linux-hardware.org/?probe=20bf043d6f) | Oct 28, 2022 |
| Valve         | Jupiter                     | [7cc988201b](https://linux-hardware.org/?probe=7cc988201b) | Oct 28, 2022 |
| HP            | ENVY Laptop 13-ba0xxx       | [920b0eaa44](https://linux-hardware.org/?probe=920b0eaa44) | Oct 27, 2022 |
| Novatech      | NLx0MU                      | [41c5d984a0](https://linux-hardware.org/?probe=41c5d984a0) | Oct 27, 2022 |
| HP            | G62                         | [c9ba156401](https://linux-hardware.org/?probe=c9ba156401) | Oct 27, 2022 |
| Toshiba       | Satellite C660              | [80c2aeb241](https://linux-hardware.org/?probe=80c2aeb241) | Oct 26, 2022 |
| HP            | Setzer                      | [a1039409cd](https://linux-hardware.org/?probe=a1039409cd) | Oct 26, 2022 |
| HP            | Setzer                      | [3945fea013](https://linux-hardware.org/?probe=3945fea013) | Oct 25, 2022 |
| Valve         | Jupiter                     | [dc86de125e](https://linux-hardware.org/?probe=dc86de125e) | Oct 25, 2022 |
| Toshiba       | Satellite C50D-A-133        | [c1ba737ccc](https://linux-hardware.org/?probe=c1ba737ccc) | Oct 25, 2022 |
| Valve         | Jupiter                     | [c12839567e](https://linux-hardware.org/?probe=c12839567e) | Oct 25, 2022 |
| Dell          | Inspiron 1525               | [742bf13a9f](https://linux-hardware.org/?probe=742bf13a9f) | Oct 25, 2022 |
| Lenovo        | V15-IIL 82C5                | [a56ad41b2f](https://linux-hardware.org/?probe=a56ad41b2f) | Oct 25, 2022 |
| Dell          | Inspiron 16 7610            | [47a3e2b5f6](https://linux-hardware.org/?probe=47a3e2b5f6) | Oct 24, 2022 |
| Lenovo        | ThinkPad T520 4243PN7       | [fdca71510b](https://linux-hardware.org/?probe=fdca71510b) | Oct 24, 2022 |
| AMI           | Unknown                     | [337d94fb96](https://linux-hardware.org/?probe=337d94fb96) | Oct 23, 2022 |
| HP            | OMEN by Laptop 17-ck0xxx    | [34f4204ae8](https://linux-hardware.org/?probe=34f4204ae8) | Oct 23, 2022 |
| GEO           | GeoBook 140                 | [e97f8024f4](https://linux-hardware.org/?probe=e97f8024f4) | Oct 22, 2022 |
| GEO           | GeoBook 140                 | [bbbe5e0fca](https://linux-hardware.org/?probe=bbbe5e0fca) | Oct 22, 2022 |
| Samsung       | R519/R719                   | [da6668197e](https://linux-hardware.org/?probe=da6668197e) | Oct 22, 2022 |
| HP            | OMEN by Laptop 17-ck0xxx    | [0ed2f15c34](https://linux-hardware.org/?probe=0ed2f15c34) | Oct 21, 2022 |
| Razer x La... | TensorBook (late 2021)      | [27cae45787](https://linux-hardware.org/?probe=27cae45787) | Oct 20, 2022 |
| Acer          | Aspire S3                   | [a24603a142](https://linux-hardware.org/?probe=a24603a142) | Oct 20, 2022 |
| Dell          | XPS 13 9300                 | [ec9a97a15d](https://linux-hardware.org/?probe=ec9a97a15d) | Oct 20, 2022 |
| Toshiba       | Satellite C660              | [3632c8a48d](https://linux-hardware.org/?probe=3632c8a48d) | Oct 20, 2022 |
| Valve         | Jupiter                     | [a314a908eb](https://linux-hardware.org/?probe=a314a908eb) | Oct 20, 2022 |
| Razer x La... | TensorBook (late 2021)      | [fef9e26716](https://linux-hardware.org/?probe=fef9e26716) | Oct 20, 2022 |
| Valve         | Jupiter                     | [3fada6964f](https://linux-hardware.org/?probe=3fada6964f) | Oct 19, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [56089b3625](https://linux-hardware.org/?probe=56089b3625) | Oct 19, 2022 |
| Acer          | Aspire V5-132P              | [420ad7ac8c](https://linux-hardware.org/?probe=420ad7ac8c) | Oct 19, 2022 |
| Lenovo        | G580 2689H2G                | [1d81a2fb3b](https://linux-hardware.org/?probe=1d81a2fb3b) | Oct 18, 2022 |
| Acer          | Aspire 6930G                | [d65e0cfe7a](https://linux-hardware.org/?probe=d65e0cfe7a) | Oct 18, 2022 |
| GEO           | GeoBook 120                 | [fe063a61a7](https://linux-hardware.org/?probe=fe063a61a7) | Oct 17, 2022 |
| HP            | ZBook 15                    | [6926e1a3c0](https://linux-hardware.org/?probe=6926e1a3c0) | Oct 17, 2022 |
| Valve         | Jupiter                     | [992d2b539a](https://linux-hardware.org/?probe=992d2b539a) | Oct 17, 2022 |
| Samsung       | 700T1C                      | [b0b2e6712c](https://linux-hardware.org/?probe=b0b2e6712c) | Oct 15, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [ee67e90b5f](https://linux-hardware.org/?probe=ee67e90b5f) | Oct 15, 2022 |
| Valve         | Jupiter                     | [022a7cab63](https://linux-hardware.org/?probe=022a7cab63) | Oct 15, 2022 |
| Valve         | Jupiter                     | [bd47ebea62](https://linux-hardware.org/?probe=bd47ebea62) | Oct 15, 2022 |
| Valve         | Jupiter                     | [627b9225cb](https://linux-hardware.org/?probe=627b9225cb) | Oct 15, 2022 |
| HP            | Presario C300 (RM500EA#A... | [c35d7b0ee3](https://linux-hardware.org/?probe=c35d7b0ee3) | Oct 14, 2022 |
| Dell          | Precision M4800             | [aa9a1680fd](https://linux-hardware.org/?probe=aa9a1680fd) | Oct 14, 2022 |
| Lenovo        | V110-15AST 80TD             | [9d4b6fafb6](https://linux-hardware.org/?probe=9d4b6fafb6) | Oct 12, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [cbc3888844](https://linux-hardware.org/?probe=cbc3888844) | Oct 12, 2022 |
| Lenovo        | Z50-75 80EC                 | [7dbdbc1de9](https://linux-hardware.org/?probe=7dbdbc1de9) | Oct 12, 2022 |
| Dell          | Latitude E5470              | [eee260b733](https://linux-hardware.org/?probe=eee260b733) | Oct 12, 2022 |
| Dell          | Latitude E5470              | [3bbb87ee1b](https://linux-hardware.org/?probe=3bbb87ee1b) | Oct 12, 2022 |
| Lenovo        | ThinkPad T420 4236TL7       | [8a639f4457](https://linux-hardware.org/?probe=8a639f4457) | Oct 10, 2022 |
| Valve         | Jupiter                     | [c06c56de15](https://linux-hardware.org/?probe=c06c56de15) | Oct 10, 2022 |
| Lenovo        | Yoga 3 14 80JH              | [5e65bc0e8a](https://linux-hardware.org/?probe=5e65bc0e8a) | Oct 10, 2022 |
| Dell          | XPS 13 9380                 | [5d882bd47f](https://linux-hardware.org/?probe=5d882bd47f) | Oct 09, 2022 |
| Acer          | Acadia V1.45                | [c33c96e412](https://linux-hardware.org/?probe=c33c96e412) | Oct 09, 2022 |
| Packard Be... | EasyNote TM82               | [8e3ecfd03d](https://linux-hardware.org/?probe=8e3ecfd03d) | Oct 08, 2022 |
| Fujitsu       | LIFEBOOK U904               | [b4a8655f31](https://linux-hardware.org/?probe=b4a8655f31) | Oct 08, 2022 |
| Dell          | Latitude 5411               | [4bb05d639f](https://linux-hardware.org/?probe=4bb05d639f) | Oct 08, 2022 |
| HP            | ProBook 640 G3              | [03112f2830](https://linux-hardware.org/?probe=03112f2830) | Oct 08, 2022 |
| Lenovo        | V155-15API 81V5             | [c08e4bed15](https://linux-hardware.org/?probe=c08e4bed15) | Oct 07, 2022 |
| Dell          | Latitude 7480               | [ad29ce89eb](https://linux-hardware.org/?probe=ad29ce89eb) | Oct 06, 2022 |
| Lenovo        | IdeaPad S510p 20298         | [20fb15fcbf](https://linux-hardware.org/?probe=20fb15fcbf) | Oct 06, 2022 |
| Valve         | Jupiter                     | [28900801aa](https://linux-hardware.org/?probe=28900801aa) | Oct 06, 2022 |
| Valve         | Jupiter                     | [64f5b28613](https://linux-hardware.org/?probe=64f5b28613) | Oct 06, 2022 |
| Lenovo        | G510 20238                  | [700e1adbbb](https://linux-hardware.org/?probe=700e1adbbb) | Oct 05, 2022 |
| Lenovo        | ThinkPad Twist 20C41A3      | [3da96ac399](https://linux-hardware.org/?probe=3da96ac399) | Oct 04, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [790114327c](https://linux-hardware.org/?probe=790114327c) | Oct 04, 2022 |
| Acer          | Aspire ES1-523              | [a80da55e0c](https://linux-hardware.org/?probe=a80da55e0c) | Oct 04, 2022 |
| Acer          | Extensa 2530                | [684b31b41d](https://linux-hardware.org/?probe=684b31b41d) | Oct 03, 2022 |
| Dell          | Inspiron N5040              | [8ccfb39433](https://linux-hardware.org/?probe=8ccfb39433) | Oct 03, 2022 |
| Lenovo        | Flex 2-14 20404             | [b3a9474c83](https://linux-hardware.org/?probe=b3a9474c83) | Oct 03, 2022 |
| Apple         | MacBookPro11,3              | [cdcd2cf0e6](https://linux-hardware.org/?probe=cdcd2cf0e6) | Oct 02, 2022 |
| eMachines     | E525                        | [1467bc71f7](https://linux-hardware.org/?probe=1467bc71f7) | Oct 02, 2022 |
| Dell          | Inspiron 1545               | [ba72c7ee42](https://linux-hardware.org/?probe=ba72c7ee42) | Oct 01, 2022 |
| Lenovo        | 3000 N200 0769B4G           | [947f124efc](https://linux-hardware.org/?probe=947f124efc) | Oct 01, 2022 |
| HP            | Notebook                    | [fec2594d37](https://linux-hardware.org/?probe=fec2594d37) | Oct 01, 2022 |
| Valve         | Jupiter                     | [12f0d9358a](https://linux-hardware.org/?probe=12f0d9358a) | Oct 01, 2022 |
| Apple         | MacBookPro16,2              | [8eaded9cb5](https://linux-hardware.org/?probe=8eaded9cb5) | Oct 01, 2022 |
| Sony          | VPCYB3V1E                   | [de50c8a304](https://linux-hardware.org/?probe=de50c8a304) | Oct 01, 2022 |
| Acer          | Swift SF314-43              | [cfd0c22e29](https://linux-hardware.org/?probe=cfd0c22e29) | Sep 30, 2022 |
| Valve         | Jupiter                     | [dab0a00c02](https://linux-hardware.org/?probe=dab0a00c02) | Sep 30, 2022 |
| Valve         | Jupiter                     | [e9737fcadf](https://linux-hardware.org/?probe=e9737fcadf) | Sep 30, 2022 |
| HP            | EliteBook 8570p             | [cc4740fa37](https://linux-hardware.org/?probe=cc4740fa37) | Sep 30, 2022 |
| Dell          | XPS 13 7390                 | [c4ccdf9992](https://linux-hardware.org/?probe=c4ccdf9992) | Sep 30, 2022 |
| Dell          | Latitude 7430               | [2151370437](https://linux-hardware.org/?probe=2151370437) | Sep 29, 2022 |
| HP            | Compaq 6720s                | [ddb5163310](https://linux-hardware.org/?probe=ddb5163310) | Sep 29, 2022 |
| Dell          | Inspiron 1564               | [d9dd05aa12](https://linux-hardware.org/?probe=d9dd05aa12) | Sep 29, 2022 |
| Dell          | XPS 13 9360                 | [6f1ecca2f0](https://linux-hardware.org/?probe=6f1ecca2f0) | Sep 28, 2022 |
| Lenovo        | G570 4334                   | [7b96f1db41](https://linux-hardware.org/?probe=7b96f1db41) | Sep 28, 2022 |
| MSI           | GT72S 6QE                   | [7ec3a25453](https://linux-hardware.org/?probe=7ec3a25453) | Sep 26, 2022 |
| Packard Be... | EasyNote TS44HR             | [4005a32539](https://linux-hardware.org/?probe=4005a32539) | Sep 26, 2022 |
| Timi          | RedmiBook Pro 15S           | [533cc3b3ae](https://linux-hardware.org/?probe=533cc3b3ae) | Sep 26, 2022 |
| Valve         | Jupiter                     | [c3305d9bff](https://linux-hardware.org/?probe=c3305d9bff) | Sep 26, 2022 |
| Jumper        | EZbook                      | [1af58cd7e7](https://linux-hardware.org/?probe=1af58cd7e7) | Sep 25, 2022 |
| Dell          | XPS 15 9510                 | [1ccf6c5c41](https://linux-hardware.org/?probe=1ccf6c5c41) | Sep 25, 2022 |
| Acer          | Aspire A315-51              | [21121aa007](https://linux-hardware.org/?probe=21121aa007) | Sep 25, 2022 |
| Lenovo        | ThinkPad SL500 27464DG      | [6c2b4ce4b1](https://linux-hardware.org/?probe=6c2b4ce4b1) | Sep 25, 2022 |
| Dell          | Inspiron 15 5510            | [cfda1aa63a](https://linux-hardware.org/?probe=cfda1aa63a) | Sep 25, 2022 |
| Lenovo        | ThinkPad T430 23476Y7       | [8488ad9e53](https://linux-hardware.org/?probe=8488ad9e53) | Sep 24, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [bdc8453efc](https://linux-hardware.org/?probe=bdc8453efc) | Sep 24, 2022 |
| Acer          | Swift SF315-52              | [b9e88a43d8](https://linux-hardware.org/?probe=b9e88a43d8) | Sep 24, 2022 |
| Lenovo        | ThinkPad T440s 20ARA0YL0... | [93eedc638b](https://linux-hardware.org/?probe=93eedc638b) | Sep 24, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [2082a8668b](https://linux-hardware.org/?probe=2082a8668b) | Sep 24, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [dc3a97d467](https://linux-hardware.org/?probe=dc3a97d467) | Sep 23, 2022 |
| Dell          | Inspiron 15 5510            | [02787c733c](https://linux-hardware.org/?probe=02787c733c) | Sep 23, 2022 |
| ASUSTek       | N750JV                      | [f69fe7dacf](https://linux-hardware.org/?probe=f69fe7dacf) | Sep 23, 2022 |
| Dell          | Inspiron 15 5510            | [fe7ae61ecd](https://linux-hardware.org/?probe=fe7ae61ecd) | Sep 23, 2022 |
| Dell          | Latitude E6330              | [5f1a272734](https://linux-hardware.org/?probe=5f1a272734) | Sep 23, 2022 |
| Dell          | Latitude 5411               | [018a9c569a](https://linux-hardware.org/?probe=018a9c569a) | Sep 23, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [605e97df5c](https://linux-hardware.org/?probe=605e97df5c) | Sep 22, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [94e6332c62](https://linux-hardware.org/?probe=94e6332c62) | Sep 22, 2022 |
| HP            | Laptop 15-bw0xx             | [c4915d8dd2](https://linux-hardware.org/?probe=c4915d8dd2) | Sep 22, 2022 |
| MSI           | GL73 8RD                    | [f197efe030](https://linux-hardware.org/?probe=f197efe030) | Sep 22, 2022 |
| MSI           | GL73 8RD                    | [0534ef55fc](https://linux-hardware.org/?probe=0534ef55fc) | Sep 22, 2022 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [03428c1a17](https://linux-hardware.org/?probe=03428c1a17) | Sep 21, 2022 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [c859bf5e24](https://linux-hardware.org/?probe=c859bf5e24) | Sep 21, 2022 |
| Valve         | Jupiter                     | [721ede2e11](https://linux-hardware.org/?probe=721ede2e11) | Sep 20, 2022 |
| Dell          | Inspiron 5570               | [16d661b4e5](https://linux-hardware.org/?probe=16d661b4e5) | Sep 20, 2022 |
| TUXEDO        | InfinityBook Pro 14 v4      | [20c7b9dcf9](https://linux-hardware.org/?probe=20c7b9dcf9) | Sep 20, 2022 |
| Lenovo        | E50-80 80J2                 | [a399d96de2](https://linux-hardware.org/?probe=a399d96de2) | Sep 20, 2022 |
| Valve         | Jupiter                     | [e60653a4c7](https://linux-hardware.org/?probe=e60653a4c7) | Sep 20, 2022 |
| Lenovo        | Legion 5-15ACH6H 82JU       | [1f48647e32](https://linux-hardware.org/?probe=1f48647e32) | Sep 20, 2022 |
| HP            | ProBook 450 G2              | [73c35ad64a](https://linux-hardware.org/?probe=73c35ad64a) | Sep 20, 2022 |
| HONOR         | NMH-WCX9                    | [dd2687098a](https://linux-hardware.org/?probe=dd2687098a) | Sep 19, 2022 |
| Razer         | Blade 15 Base Model (Ear... | [6b6ad790c5](https://linux-hardware.org/?probe=6b6ad790c5) | Sep 19, 2022 |
| Lenovo        | Yoga 3 14 80JH              | [7b17bd93c0](https://linux-hardware.org/?probe=7b17bd93c0) | Sep 19, 2022 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [9417681a63](https://linux-hardware.org/?probe=9417681a63) | Sep 19, 2022 |
| HONOR         | NMH-WCX9                    | [060f3bd895](https://linux-hardware.org/?probe=060f3bd895) | Sep 19, 2022 |
| Panasonic     | CF-53JAWZYDE                | [f8b1ca10d1](https://linux-hardware.org/?probe=f8b1ca10d1) | Sep 19, 2022 |
| Lenovo        | E50-80 80J2                 | [1a538a3132](https://linux-hardware.org/?probe=1a538a3132) | Sep 18, 2022 |
| Dell          | Studio 1737                 | [7218731367](https://linux-hardware.org/?probe=7218731367) | Sep 18, 2022 |
| ASUSTek       | X510UQ                      | [eb619ed1c5](https://linux-hardware.org/?probe=eb619ed1c5) | Sep 18, 2022 |
| Dell          | Precision 5530              | [8fc00af945](https://linux-hardware.org/?probe=8fc00af945) | Sep 18, 2022 |
| Unknown       | Unknown                     | [1e27521b13](https://linux-hardware.org/?probe=1e27521b13) | Sep 17, 2022 |
| Acer          | Aspire V3-571               | [3f20a5e69d](https://linux-hardware.org/?probe=3f20a5e69d) | Sep 17, 2022 |
| Dell          | Latitude 7390               | [64c9b13553](https://linux-hardware.org/?probe=64c9b13553) | Sep 17, 2022 |
| HUAWEI        | BOM-WXX9                    | [0c3d62f1c9](https://linux-hardware.org/?probe=0c3d62f1c9) | Sep 17, 2022 |
| Valve         | Jupiter                     | [c4dd2bf91f](https://linux-hardware.org/?probe=c4dd2bf91f) | Sep 17, 2022 |
| HP            | 255 G5 Notebook PC          | [6d8f7ffe97](https://linux-hardware.org/?probe=6d8f7ffe97) | Sep 17, 2022 |
| HP            | Laptop 15-da0xxx            | [6341f27d68](https://linux-hardware.org/?probe=6341f27d68) | Sep 16, 2022 |
| Apple         | MacBook6,1                  | [93b43e5bb5](https://linux-hardware.org/?probe=93b43e5bb5) | Sep 16, 2022 |
| Acidanther... | iMac19,2                    | [94b79ac6e5](https://linux-hardware.org/?probe=94b79ac6e5) | Sep 16, 2022 |
| HP            | ProBook 4340s               | [acca12f9d4](https://linux-hardware.org/?probe=acca12f9d4) | Sep 16, 2022 |
| Valve         | Jupiter                     | [9adc000021](https://linux-hardware.org/?probe=9adc000021) | Sep 15, 2022 |
| Dell          | Latitude 7490               | [ce54bcd741](https://linux-hardware.org/?probe=ce54bcd741) | Sep 15, 2022 |
| Lenovo        | ThinkPad T530 2429F33       | [790a0f2a25](https://linux-hardware.org/?probe=790a0f2a25) | Sep 14, 2022 |
| Lenovo        | Z70-80 80FG                 | [93cb353340](https://linux-hardware.org/?probe=93cb353340) | Sep 14, 2022 |
| HP            | Laptop 15-da0xxx            | [82140783de](https://linux-hardware.org/?probe=82140783de) | Sep 14, 2022 |
| Dell          | Latitude E7250              | [80a2e50cfc](https://linux-hardware.org/?probe=80a2e50cfc) | Sep 14, 2022 |
| Dell          | XPS 15 9510                 | [44be9b9134](https://linux-hardware.org/?probe=44be9b9134) | Sep 13, 2022 |
| HP            | EliteBook 850 G6            | [b284db5ac4](https://linux-hardware.org/?probe=b284db5ac4) | Sep 13, 2022 |
| Lenovo        | Flex 2-14 20404             | [a27c60fbde](https://linux-hardware.org/?probe=a27c60fbde) | Sep 13, 2022 |
| Dell          | Inspiron 3542               | [2c5a122ce9](https://linux-hardware.org/?probe=2c5a122ce9) | Sep 12, 2022 |
| Dell          | Inspiron 3542               | [ef3098c81a](https://linux-hardware.org/?probe=ef3098c81a) | Sep 12, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [4a54854cd7](https://linux-hardware.org/?probe=4a54854cd7) | Sep 12, 2022 |
| Entroware     | Orion                       | [d96888edf9](https://linux-hardware.org/?probe=d96888edf9) | Sep 12, 2022 |
| Entroware     | Orion                       | [c06e53ad80](https://linux-hardware.org/?probe=c06e53ad80) | Sep 12, 2022 |
| Dell          | Inspiron 3537               | [afd2b6555e](https://linux-hardware.org/?probe=afd2b6555e) | Sep 12, 2022 |
| Dell          | XPS 13 9350                 | [e137564f6b](https://linux-hardware.org/?probe=e137564f6b) | Sep 12, 2022 |
| Acer          | Aspire E5-576G              | [ee2635dbc8](https://linux-hardware.org/?probe=ee2635dbc8) | Sep 11, 2022 |
| HP            | Pavilion 15                 | [1e6331a36b](https://linux-hardware.org/?probe=1e6331a36b) | Sep 11, 2022 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [576eec419f](https://linux-hardware.org/?probe=576eec419f) | Sep 10, 2022 |
| Tactus        | GeoBook 110                 | [d13211f478](https://linux-hardware.org/?probe=d13211f478) | Sep 09, 2022 |
| Dell          | Inspiron 1720               | [27de3ede0c](https://linux-hardware.org/?probe=27de3ede0c) | Sep 09, 2022 |
| Star Labs     | Lite                        | [c08b209f09](https://linux-hardware.org/?probe=c08b209f09) | Sep 09, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [f5c538e2c7](https://linux-hardware.org/?probe=f5c538e2c7) | Sep 09, 2022 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [7c3cdfba24](https://linux-hardware.org/?probe=7c3cdfba24) | Sep 08, 2022 |
| ASUSTek       | UX430UAR                    | [478d0564a6](https://linux-hardware.org/?probe=478d0564a6) | Sep 08, 2022 |
| Dell          | Precision 5770              | [41e44b27f4](https://linux-hardware.org/?probe=41e44b27f4) | Sep 08, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [14f91e3a08](https://linux-hardware.org/?probe=14f91e3a08) | Sep 07, 2022 |
| Lenovo        | ThinkPad T470s 20HGA039U... | [43c002ad40](https://linux-hardware.org/?probe=43c002ad40) | Sep 07, 2022 |
| Toshiba       | Satellite NB10t-A-101       | [b824e1e3d5](https://linux-hardware.org/?probe=b824e1e3d5) | Sep 06, 2022 |
| Toshiba       | Satellite A660              | [8a76871325](https://linux-hardware.org/?probe=8a76871325) | Sep 06, 2022 |
| Acer          | Aspire A515-44G             | [a4f8e52425](https://linux-hardware.org/?probe=a4f8e52425) | Sep 06, 2022 |
| Acer          | Aspire A515-44G             | [0daca2662d](https://linux-hardware.org/?probe=0daca2662d) | Sep 06, 2022 |
| HP            | ZBook Firefly 15.6 inch ... | [40d6a47565](https://linux-hardware.org/?probe=40d6a47565) | Sep 05, 2022 |
| Dell          | Vostro 7620                 | [a75fed8b3f](https://linux-hardware.org/?probe=a75fed8b3f) | Sep 05, 2022 |
| Dell          | Vostro 7620                 | [cd613ebcd2](https://linux-hardware.org/?probe=cd613ebcd2) | Sep 05, 2022 |
| Clevo         | P65_P67SE                   | [9a38027b73](https://linux-hardware.org/?probe=9a38027b73) | Sep 05, 2022 |
| HP            | OMEN by Laptop 17-cb1xxx    | [f0a6826f9d](https://linux-hardware.org/?probe=f0a6826f9d) | Sep 05, 2022 |
| Valve         | Jupiter                     | [04c7e44198](https://linux-hardware.org/?probe=04c7e44198) | Sep 05, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [4641fe397a](https://linux-hardware.org/?probe=4641fe397a) | Sep 05, 2022 |
| Acer          | Aspire V5-552               | [031439a681](https://linux-hardware.org/?probe=031439a681) | Sep 04, 2022 |
| Dell          | Inspiron 5558               | [2d4eeaf028](https://linux-hardware.org/?probe=2d4eeaf028) | Sep 03, 2022 |
| Lenovo        | Legion 5 15IAH7H 82RB       | [1822ab5853](https://linux-hardware.org/?probe=1822ab5853) | Sep 02, 2022 |
| Lenovo        | Legion 5 15IAH7H 82RB       | [2c5c9d2233](https://linux-hardware.org/?probe=2c5c9d2233) | Sep 02, 2022 |
| Dell          | Precision 5530              | [0151d15e28](https://linux-hardware.org/?probe=0151d15e28) | Sep 02, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [a15c233224](https://linux-hardware.org/?probe=a15c233224) | Sep 02, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [9cabeefea8](https://linux-hardware.org/?probe=9cabeefea8) | Sep 01, 2022 |
| ASUSTek       | N552VW                      | [99d4a9be86](https://linux-hardware.org/?probe=99d4a9be86) | Sep 01, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/UK/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 546       | 14.28%  |
| Ubuntu 18.04       | 277       | 7.24%   |
| Ubuntu 22.04       | 184       | 4.81%   |
| Zorin 16           | 98        | 2.56%   |
| OpenMandriva 4.3   | 83        | 2.17%   |
| Debian 11          | 71        | 1.86%   |
| Linux Mint 19.3    | 68        | 1.78%   |
| Pop!_OS 22.04      | 66        | 1.73%   |
| Ubuntu 19.04       | 62        | 1.62%   |
| OpenMandriva 4.2   | 60        | 1.57%   |
| Arch Rolling       | 57        | 1.49%   |
| Linux Mint 20.3    | 56        | 1.46%   |
| Pop!_OS 20.04      | 55        | 1.44%   |
| Manjaro            | 55        | 1.44%   |
| Linux Mint 20.2    | 54        | 1.41%   |
| Arch               | 54        | 1.41%   |
| Ubuntu 20.10       | 53        | 1.39%   |
| Zorin 15           | 51        | 1.33%   |
| Ubuntu 21.10       | 51        | 1.33%   |
| KDE neon 20.04     | 51        | 1.33%   |
| Linux Mint 20.1    | 50        | 1.31%   |
| Ubuntu 19.10       | 49        | 1.28%   |
| Pop!_OS 21.04      | 45        | 1.18%   |
| Ubuntu 21.04       | 44        | 1.15%   |
| OpenMandriva 23.01 | 43        | 1.12%   |
| Xubuntu 20.04      | 39        | 1.02%   |
| ArcoLinux Rolling  | 37        | 0.97%   |
| Linux Mint 20      | 36        | 0.94%   |
| Pop!_OS 20.10      | 34        | 0.89%   |
| Linux Mint 21.1    | 34        | 0.89%   |
| Pop!_OS 21.10      | 33        | 0.86%   |
| Fedora 35          | 33        | 0.86%   |
| Fedora 34          | 33        | 0.86%   |
| Fedora 37          | 32        | 0.84%   |
| Ubuntu 18.10       | 31        | 0.81%   |
| Fedora 36          | 31        | 0.81%   |
| Fedora 32          | 28        | 0.73%   |
| Fedora 31          | 28        | 0.73%   |
| OpenMandriva 23.03 | 27        | 0.71%   |
| Linux Mint 21      | 27        | 0.71%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1286      | 35.23%  |
| Linux Mint    | 332       | 9.1%    |
| OpenMandriva  | 227       | 6.22%   |
| Pop!_OS       | 218       | 5.97%   |
| Fedora        | 213       | 5.84%   |
| Zorin         | 157       | 4.3%    |
| Manjaro       | 124       | 3.4%    |
| Arch          | 109       | 2.99%   |
| Debian        | 108       | 2.96%   |
| Xubuntu       | 81        | 2.22%   |
| Kubuntu       | 75        | 2.05%   |
| SteamOS       | 71        | 1.95%   |
| KDE neon      | 65        | 1.78%   |
| Elementary    | 44        | 1.21%   |
| ArcoLinux     | 41        | 1.12%   |
| ROSA          | 36        | 0.99%   |
| Lubuntu       | 35        | 0.96%   |
| Ubuntu MATE   | 32        | 0.88%   |
| Endless       | 28        | 0.77%   |
| Ubuntu Unity  | 27        | 0.74%   |
| openSUSE      | 27        | 0.74%   |
| BlackPanther  | 27        | 0.74%   |
| Kali          | 26        | 0.71%   |
| Gentoo        | 25        | 0.68%   |
| LMDE          | 18        | 0.49%   |
| Clear Linux   | 18        | 0.49%   |
| EndeavourOS   | 17        | 0.47%   |
| Ubuntu Budgie | 15        | 0.41%   |
| MX            | 15        | 0.41%   |
| Garuda Linux  | 15        | 0.41%   |
| Parrot        | 14        | 0.38%   |
| Peppermint    | 12        | 0.33%   |
| CentOS        | 10        | 0.27%   |
| RHEL          | 6         | 0.16%   |
| PureOS        | 5         | 0.14%   |
| Nobara        | 5         | 0.14%   |
| NixOS         | 5         | 0.14%   |
| Artix         | 5         | 0.14%   |
| Alpine        | 5         | 0.14%   |
| Q4OS          | 4         | 0.11%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 78        | 1.85%   |
| 5.4.0-42-generic         | 77        | 1.83%   |
| 5.10.14-desktop-1omv4002 | 57        | 1.35%   |
| 5.15.0-56-generic        | 43        | 1.02%   |
| 5.4.0-48-generic         | 40        | 0.95%   |
| 5.4.0-52-generic         | 39        | 0.93%   |
| 5.15.0-52-generic        | 38        | 0.9%    |
| 6.1.1-desktop-1omv2290   | 37        | 0.88%   |
| 5.15.0-58-generic        | 37        | 0.88%   |
| 5.4.0-29-generic         | 35        | 0.83%   |
| 5.3.0-40-generic         | 35        | 0.83%   |
| 5.11.0-27-generic        | 34        | 0.81%   |
| 5.4.0-26-generic         | 33        | 0.78%   |
| 5.3.0-28-generic         | 33        | 0.78%   |
| 5.15.0-46-generic        | 33        | 0.78%   |
| 5.4.0-58-generic         | 30        | 0.71%   |
| 5.4.0-40-generic         | 29        | 0.69%   |
| 5.0.0-32-generic         | 29        | 0.69%   |
| 5.11.0-38-generic        | 28        | 0.66%   |
| 6.2.6-desktop-1omv2390   | 27        | 0.64%   |
| 5.8.0-43-generic         | 25        | 0.59%   |
| 5.3.0-42-generic         | 25        | 0.59%   |
| 5.19.0-35-generic        | 25        | 0.59%   |
| 5.4.0-91-generic         | 24        | 0.57%   |
| 5.11.0-37-generic        | 24        | 0.57%   |
| 5.11.0-25-generic        | 24        | 0.57%   |
| 5.4.0-65-generic         | 23        | 0.55%   |
| 5.13.0-valve36-1-neptune | 23        | 0.55%   |
| 5.4.0-7634-generic       | 22        | 0.52%   |
| 5.4.0-33-generic         | 22        | 0.52%   |
| 5.13.0-7614-generic      | 22        | 0.52%   |
| 5.13.0-28-generic        | 22        | 0.52%   |
| 5.0.0-37-generic         | 22        | 0.52%   |
| 5.8.0-50-generic         | 21        | 0.5%    |
| 5.8.0-44-generic         | 21        | 0.5%    |
| 5.4.0-56-generic         | 21        | 0.5%    |
| 5.4.0-54-generic         | 21        | 0.5%    |
| 5.3.0-46-generic         | 21        | 0.5%    |
| 5.15.0-41-generic        | 20        | 0.47%   |
| 4.18.16-desktop-1bP      | 20        | 0.47%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 728       | 18.55%  |
| 5.15.0  | 342       | 8.72%   |
| 5.13.0  | 253       | 6.45%   |
| 5.11.0  | 242       | 6.17%   |
| 5.8.0   | 232       | 5.91%   |
| 5.3.0   | 204       | 5.2%    |
| 4.15.0  | 200       | 5.1%    |
| 5.0.0   | 137       | 3.49%   |
| 5.19.0  | 94        | 2.4%    |
| 5.10.0  | 94        | 2.4%    |
| 4.18.0  | 92        | 2.34%   |
| 5.16.7  | 78        | 1.99%   |
| 5.10.14 | 57        | 1.45%   |
| 6.1.1   | 38        | 0.97%   |
| 6.2.6   | 36        | 0.92%   |
| 4.19.0  | 30        | 0.76%   |
| 4.18.16 | 21        | 0.54%   |
| 5.17.5  | 16        | 0.41%   |
| 6.0.6   | 15        | 0.38%   |
| 5.14.0  | 15        | 0.38%   |
| 6.0.0   | 14        | 0.36%   |
| 4.9.60  | 12        | 0.31%   |
| 6.2.0   | 11        | 0.28%   |
| 6.1.0   | 11        | 0.28%   |
| 6.0.12  | 11        | 0.28%   |
| 5.17.1  | 11        | 0.28%   |
| 5.16.0  | 11        | 0.28%   |
| 5.9.16  | 10        | 0.25%   |
| 5.15.12 | 10        | 0.25%   |
| 4.4.0   | 10        | 0.25%   |
| 5.18.10 | 9         | 0.23%   |
| 5.9.0   | 8         | 0.2%    |
| 5.16.15 | 8         | 0.2%    |
| 5.16.11 | 8         | 0.2%    |
| 5.13.8  | 8         | 0.2%    |
| 5.12.13 | 8         | 0.2%    |
| 6.1.9   | 7         | 0.18%   |
| 6.1.4   | 7         | 0.18%   |
| 6.1.12  | 7         | 0.18%   |
| 6.0.10  | 7         | 0.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 764       | 19.65%  |
| 5.15    | 429       | 11.03%  |
| 5.13    | 293       | 7.53%   |
| 5.8     | 277       | 7.12%   |
| 5.11    | 265       | 6.81%   |
| 5.3     | 227       | 5.84%   |
| 4.15    | 201       | 5.17%   |
| 5.10    | 199       | 5.12%   |
| 5.16    | 144       | 3.7%    |
| 5.0     | 144       | 3.7%    |
| 5.19    | 135       | 3.47%   |
| 4.18    | 115       | 2.96%   |
| 6.1     | 99        | 2.55%   |
| 6.2     | 80        | 2.06%   |
| 6.0     | 74        | 1.9%    |
| 5.17    | 57        | 1.47%   |
| 5.14    | 49        | 1.26%   |
| 5.9     | 46        | 1.18%   |
| 4.19    | 46        | 1.18%   |
| 5.12    | 42        | 1.08%   |
| 5.6     | 37        | 0.95%   |
| 4.9     | 33        | 0.85%   |
| 5.18    | 32        | 0.82%   |
| 5.7     | 30        | 0.77%   |
| 5.5     | 19        | 0.49%   |
| 5.2     | 11        | 0.28%   |
| 4.4     | 11        | 0.28%   |
| 5.1     | 8         | 0.21%   |
| 4.20    | 3         | 0.08%   |
| 4.16    | 3         | 0.08%   |
| 4.14    | 3         | 0.08%   |
| 3.10    | 3         | 0.08%   |
| 4.8     | 2         | 0.05%   |
| 4.12    | 2         | 0.05%   |
| 4.1     | 2         | 0.05%   |
| 4.6     | 1         | 0.03%   |
| 4.17    | 1         | 0.03%   |
| 4.13    | 1         | 0.03%   |
| 3.13    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 3410      | 96.85%  |
| i686    | 110       | 3.12%   |
| aarch64 | 1         | 0.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 1667      | 45.35%  |
| KDE5             | 596       | 16.21%  |
| Unknown          | 411       | 11.18%  |
| X-Cinnamon       | 272       | 7.4%    |
| XFCE             | 263       | 7.15%   |
| MATE             | 97        | 2.64%   |
| KDE              | 85        | 2.31%   |
| Pantheon         | 41        | 1.12%   |
| Cinnamon         | 38        | 1.03%   |
| LXQt             | 33        | 0.9%    |
| Unity            | 28        | 0.76%   |
| LXDE             | 26        | 0.71%   |
| Budgie           | 22        | 0.6%    |
| i3               | 20        | 0.54%   |
| GNOME Flashback  | 15        | 0.41%   |
| KDE4             | 14        | 0.38%   |
| sway             | 7         | 0.19%   |
| qtile            | 6         | 0.16%   |
| GNOME Classic    | 6         | 0.16%   |
| awesome          | 5         | 0.14%   |
| trinity          | 3         | 0.08%   |
| openbox          | 3         | 0.08%   |
| Deepin           | 3         | 0.08%   |
| bspwm            | 3         | 0.08%   |
| xmonad           | 2         | 0.05%   |
| i3-with-shmlog   | 2         | 0.05%   |
| DWM              | 2         | 0.05%   |
| mwm              | 1         | 0.03%   |
| lightdm-xsession | 1         | 0.03%   |
| GNUstep          | 1         | 0.03%   |
| Enlightenment    | 1         | 0.03%   |
| Cutefish         | 1         | 0.03%   |
| BunsenLabs       | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2828      | 78.38%  |
| Wayland | 518       | 14.36%  |
| Unknown | 224       | 6.21%   |
| Tty     | 38        | 1.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1978      | 54.01%  |
| SDDM    | 486       | 13.27%  |
| GDM     | 414       | 11.31%  |
| GDM3    | 345       | 9.42%   |
| LightDM | 305       | 8.33%   |
| TDM     | 101       | 2.76%   |
| KDM     | 15        | 0.41%   |
| XDM     | 5         | 0.14%   |
| LXDM    | 5         | 0.14%   |
| Ly      | 4         | 0.11%   |
| SLiM    | 1         | 0.03%   |
| NODM    | 1         | 0.03%   |
| GREETD  | 1         | 0.03%   |
| CDM     | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang           | Notebooks | Percent |
|----------------|-----------|---------|
| en_GB          | 2574      | 71.34%  |
| en_US          | 450       | 12.47%  |
| Unknown        | 406       | 11.25%  |
| C              | 45        | 1.25%   |
| pl_PL          | 37        | 1.03%   |
| fr_FR          | 9         | 0.25%   |
| de_DE          | 9         | 0.25%   |
| it_IT          | 7         | 0.19%   |
| ru_RU          | 6         | 0.17%   |
| POSIX          | 6         | 0.17%   |
| en_CA          | 6         | 0.17%   |
| en_AU          | 6         | 0.17%   |
| es_ES          | 5         | 0.14%   |
| en_IN          | 5         | 0.14%   |
| en_IE          | 5         | 0.14%   |
| cs_CZ          | 5         | 0.14%   |
| zh_CN          | 3         | 0.08%   |
| ro_RO          | 3         | 0.08%   |
| hu_HU          | 3         | 0.08%   |
| sk_SK          | 2         | 0.06%   |
| pt_PT          | 2         | 0.06%   |
| pt_BR          | 2         | 0.06%   |
| uk_UA          | 1         | 0.03%   |
| tr_TR          | 1         | 0.03%   |
| nl_BE          | 1         | 0.03%   |
| en_IL          | 1         | 0.03%   |
| en_HK          | 1         | 0.03%   |
| en_GG          | 1         | 0.03%   |
| en_GB.utf-8    | 1         | 0.03%   |
| en_GB.iso88591 | 1         | 0.03%   |
| en_AG          | 1         | 0.03%   |
| da_DK          | 1         | 0.03%   |
| C.UTF8         | 1         | 0.03%   |
| bg_BG          | 1         | 0.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 1839      | 51.21%  |
| BIOS | 1752      | 48.79%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 2820      | 78.18%  |
| Btrfs   | 326       | 9.04%   |
| Overlay | 252       | 6.99%   |
| Unknown | 112       | 3.11%   |
| Xfs     | 42        | 1.16%   |
| Zfs     | 28        | 0.78%   |
| Ext2    | 9         | 0.25%   |
| Tmpfs   | 8         | 0.22%   |
| F2fs    | 6         | 0.17%   |
| Ext3    | 3         | 0.08%   |
| Aufs    | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 2094      | 58.04%  |
| GPT     | 1193      | 33.07%  |
| MBR     | 321       | 8.9%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3201      | 89.41%  |
| Yes       | 379       | 10.59%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2690      | 75.33%  |
| Yes       | 881       | 24.67%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell                | 690       | 19.61%  |
| Lenovo              | 677       | 19.24%  |
| Hewlett-Packard     | 580       | 16.48%  |
| Acer                | 263       | 7.47%   |
| ASUSTek Computer    | 248       | 7.05%   |
| Toshiba             | 162       | 4.6%    |
| Apple               | 106       | 3.01%   |
| Valve               | 74        | 2.1%    |
| Samsung Electronics | 73        | 2.07%   |
| Sony                | 57        | 1.62%   |
| MSI                 | 55        | 1.56%   |
| PC Specialist       | 42        | 1.19%   |
| HUAWEI              | 42        | 1.19%   |
| Google              | 39        | 1.11%   |
| Notebook            | 30        | 0.85%   |
| Unknown             | 26        | 0.74%   |
| Star Labs           | 19        | 0.54%   |
| Razer               | 19        | 0.54%   |
| Fujitsu             | 19        | 0.54%   |
| Packard Bell        | 17        | 0.48%   |
| Alienware           | 17        | 0.48%   |
| Dixonsxp            | 14        | 0.4%    |
| TUXEDO              | 13        | 0.37%   |
| Fujitsu Siemens     | 13        | 0.37%   |
| Entroware           | 13        | 0.37%   |
| GEO                 | 11        | 0.31%   |
| Clevo               | 11        | 0.31%   |
| LG Electronics      | 10        | 0.28%   |
| Linx                | 9         | 0.26%   |
| Advent              | 9         | 0.26%   |
| Jumper              | 8         | 0.23%   |
| Gigabyte Technology | 8         | 0.23%   |
| Panasonic           | 7         | 0.2%    |
| OEGStone            | 7         | 0.2%    |
| Intel               | 7         | 0.2%    |
| Timi                | 6         | 0.17%   |
| Medion              | 6         | 0.17%   |
| eMachines           | 6         | 0.17%   |
| Novatech            | 5         | 0.14%   |
| HONOR               | 5         | 0.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Valve Jupiter             | 74        | 2.1%    |
| Unknown                   | 47        | 1.34%   |
| HP Pavilion g6            | 24        | 0.68%   |
| HP Pavilion 15            | 19        | 0.54%   |
| HP Notebook               | 18        | 0.51%   |
| Dell XPS 15 7590          | 16        | 0.45%   |
| HP Pavilion Notebook      | 15        | 0.43%   |
| Dell Inspiron 1545        | 15        | 0.43%   |
| Dell XPS 15 9560          | 13        | 0.37%   |
| Dell XPS 13 9380          | 13        | 0.37%   |
| Dell XPS 13 9370          | 13        | 0.37%   |
| Dell XPS 15 9570          | 12        | 0.34%   |
| Dell XPS 13 9360          | 12        | 0.34%   |
| Dell Latitude E6400       | 12        | 0.34%   |
| Toshiba Satellite C660    | 11        | 0.31%   |
| Lenovo V145-15AST 81MT    | 11        | 0.31%   |
| Dell XPS 13 7390          | 11        | 0.31%   |
| Dell Latitude E6410       | 11        | 0.31%   |
| Dell XPS 15 9510          | 10        | 0.28%   |
| Dell Latitude E7450       | 10        | 0.28%   |
| Dell Latitude E7240       | 10        | 0.28%   |
| Apple MacBookPro9,2       | 10        | 0.28%   |
| Acer Aspire ES1-531       | 10        | 0.28%   |
| Lenovo Z50-75 80EC        | 9         | 0.26%   |
| HP Pavilion dv6           | 9         | 0.26%   |
| HP Laptop 15-da0xxx       | 9         | 0.26%   |
| HP Laptop 15-bw0xx        | 9         | 0.26%   |
| HP 15                     | 9         | 0.26%   |
| Dell XPS 13 9310          | 9         | 0.26%   |
| Apple MacBookPro5,5       | 9         | 0.26%   |
| Apple MacBookPro12,1      | 9         | 0.26%   |
| Dell XPS 15 9550          | 8         | 0.23%   |
| Dell XPS 13 9305          | 8         | 0.23%   |
| Dell Latitude E7440       | 8         | 0.23%   |
| Star Labs LabTop          | 7         | 0.2%    |
| Linx LINX1010B            | 7         | 0.2%    |
| HUAWEI NBLK-WAX9X         | 7         | 0.2%    |
| HP Stream Laptop 14-ax0XX | 7         | 0.2%    |
| HP Laptop 15-db0xxx       | 7         | 0.2%    |
| HP ENVY Notebook          | 7         | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 378       | 10.74%  |
| Dell Latitude         | 239       | 6.79%   |
| Acer Aspire           | 190       | 5.4%    |
| Dell Inspiron         | 181       | 5.14%   |
| Dell XPS              | 159       | 4.52%   |
| Toshiba Satellite     | 142       | 4.04%   |
| Lenovo IdeaPad        | 132       | 3.75%   |
| HP Pavilion           | 131       | 3.72%   |
| HP EliteBook          | 97        | 2.76%   |
| Valve Jupiter         | 74        | 2.1%    |
| HP ProBook            | 60        | 1.71%   |
| HP Laptop             | 60        | 1.71%   |
| ASUS VivoBook         | 52        | 1.48%   |
| Unknown               | 47        | 1.34%   |
| Dell Precision        | 43        | 1.22%   |
| HP ENVY               | 32        | 0.91%   |
| HP Compaq             | 29        | 0.82%   |
| HP Stream             | 26        | 0.74%   |
| Acer Swift            | 24        | 0.68%   |
| ASUS ZenBook          | 23        | 0.65%   |
| Lenovo Legion         | 22        | 0.63%   |
| Dell Vostro           | 22        | 0.63%   |
| ASUS ROG              | 21        | 0.6%    |
| Razer Blade           | 19        | 0.54%   |
| Lenovo Yoga           | 19        | 0.54%   |
| Lenovo ThinkBook      | 19        | 0.54%   |
| HP ZBook              | 18        | 0.51%   |
| HP Notebook           | 18        | 0.51%   |
| HP Presario           | 17        | 0.48%   |
| Packard Bell EasyNote | 16        | 0.45%   |
| Fujitsu LIFEBOOK      | 16        | 0.45%   |
| Acer Nitro            | 16        | 0.45%   |
| HP 255                | 15        | 0.43%   |
| ASUS ASUS             | 15        | 0.43%   |
| HP OMEN               | 13        | 0.37%   |
| Apple MacBookPro9     | 13        | 0.37%   |
| Dell System           | 12        | 0.34%   |
| Lenovo V145-15AST     | 11        | 0.31%   |
| ASUS TUF              | 11        | 0.31%   |
| Apple MacBookPro5     | 11        | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2018    | 317       | 9.01%   |
| 2019    | 301       | 8.55%   |
| 2020    | 289       | 8.21%   |
| 2012    | 269       | 7.64%   |
| 2013    | 255       | 7.25%   |
| 2011    | 239       | 6.79%   |
| 2021    | 232       | 6.59%   |
| 2017    | 224       | 6.37%   |
| 2015    | 219       | 6.22%   |
| 2016    | 206       | 5.85%   |
| 2014    | 194       | 5.51%   |
| 2010    | 176       | 5%      |
| 2008    | 157       | 4.46%   |
| 2022    | 152       | 4.32%   |
| 2009    | 135       | 3.84%   |
| 2007    | 88        | 2.5%    |
| 2006    | 38        | 1.08%   |
| 2023    | 12        | 0.34%   |
| 2005    | 7         | 0.2%    |
| Unknown | 7         | 0.2%    |
| 2003    | 1         | 0.03%   |
| 2002    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 3519      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 3156      | 88.83%  |
| Enabled  | 397       | 11.17%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3459      | 98.29%  |
| Yes  | 60        | 1.71%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1019      | 28.53%  |
| 3.01-4.0    | 728       | 20.38%  |
| 16.01-24.0  | 650       | 18.2%   |
| 8.01-16.0   | 583       | 16.32%  |
| 32.01-64.0  | 212       | 5.94%   |
| 1.01-2.0    | 206       | 5.77%   |
| 2.01-3.0    | 83        | 2.32%   |
| 64.01-256.0 | 32        | 0.9%    |
| 0.51-1.0    | 30        | 0.84%   |
| 24.01-32.0  | 28        | 0.78%   |
| 0.01-0.5    | 1         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1508      | 38.8%   |
| 2.01-3.0   | 967       | 24.88%  |
| 4.01-8.0   | 512       | 13.17%  |
| 3.01-4.0   | 472       | 12.14%  |
| 0.51-1.0   | 258       | 6.64%   |
| 8.01-16.0  | 116       | 2.98%   |
| 0.01-0.5   | 35        | 0.9%    |
| 16.01-24.0 | 12        | 0.31%   |
| 24.01-32.0 | 5         | 0.13%   |
| 32.01-64.0 | 1         | 0.03%   |
| Unknown    | 1         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2611      | 72.61%  |
| 2      | 825       | 22.94%  |
| 3      | 95        | 2.64%   |
| 0      | 36        | 1%      |
| 4      | 20        | 0.56%   |
| 7      | 3         | 0.08%   |
| 5      | 3         | 0.08%   |
| 9      | 1         | 0.03%   |
| 8      | 1         | 0.03%   |
| 6      | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2235      | 63.14%  |
| Yes       | 1305      | 36.86%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2726      | 77.25%  |
| No        | 803       | 22.75%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3466      | 98.44%  |
| No        | 55        | 1.56%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2730      | 76.79%  |
| No        | 825       | 23.21%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| UK      | 3519      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| London              | 268       | 6.94%   |
| Birmingham          | 71        | 1.84%   |
| Manchester          | 69        | 1.79%   |
| Glasgow             | 64        | 1.66%   |
| Edinburgh           | 56        | 1.45%   |
| Bristol             | 50        | 1.3%    |
| Nottingham          | 45        | 1.17%   |
| Sheffield           | 44        | 1.14%   |
| Liverpool           | 44        | 1.14%   |
| Leeds               | 41        | 1.06%   |
| Islington           | 36        | 0.93%   |
| Reading             | 34        | 0.88%   |
| Norwich             | 34        | 0.88%   |
| Cambridge           | 32        | 0.83%   |
| Coventry            | 29        | 0.75%   |
| Aberdeen            | 27        | 0.7%    |
| Oxford              | 26        | 0.67%   |
| Milton Keynes       | 26        | 0.67%   |
| Southampton         | 25        | 0.65%   |
| Leicester           | 25        | 0.65%   |
| Croydon             | 23        | 0.6%    |
| Cardiff             | 23        | 0.6%    |
| Brighton            | 21        | 0.54%   |
| Wolverhampton       | 20        | 0.52%   |
| Plymouth            | 20        | 0.52%   |
| Kensington          | 20        | 0.52%   |
| Harrow              | 20        | 0.52%   |
| Bolton              | 20        | 0.52%   |
| York                | 19        | 0.49%   |
| Walsall             | 19        | 0.49%   |
| Gloucester          | 19        | 0.49%   |
| Chesterfield        | 19        | 0.49%   |
| Wigan               | 18        | 0.47%   |
| Swindon             | 18        | 0.47%   |
| Derby               | 18        | 0.47%   |
| Bradford            | 18        | 0.47%   |
| Peterborough        | 17        | 0.44%   |
| Newcastle upon Tyne | 17        | 0.44%   |
| Belfast             | 17        | 0.44%   |
| Bromley             | 16        | 0.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 678       | 903    | 15.76%  |
| WDC                         | 439       | 557    | 10.2%   |
| Seagate                     | 437       | 598    | 10.16%  |
| Toshiba                     | 384       | 469    | 8.93%   |
| Unknown                     | 378       | 495    | 8.79%   |
| Sandisk                     | 260       | 320    | 6.04%   |
| Crucial                     | 188       | 254    | 4.37%   |
| SK hynix                    | 169       | 197    | 3.93%   |
| Hitachi                     | 163       | 193    | 3.79%   |
| Kingston                    | 160       | 200    | 3.72%   |
| Intel                       | 122       | 145    | 2.84%   |
| HGST                        | 115       | 166    | 2.67%   |
| Micron Technology           | 82        | 99     | 1.91%   |
| Apple                       | 49        | 64     | 1.14%   |
| Phison                      | 43        | 50     | 1%      |
| KIOXIA                      | 41        | 47     | 0.95%   |
| China                       | 40        | 53     | 0.93%   |
| A-DATA Technology           | 35        | 41     | 0.81%   |
| LITEON                      | 33        | 39     | 0.77%   |
| PNY                         | 30        | 35     | 0.7%    |
| Phison Electronics          | 28        | 29     | 0.65%   |
| Fujitsu                     | 28        | 35     | 0.65%   |
| Transcend                   | 26        | 33     | 0.6%    |
| Unknown                     | 24        | 27     | 0.56%   |
| LITEONIT                    | 21        | 26     | 0.49%   |
| Silicon Motion              | 20        | 24     | 0.46%   |
| Micron/Crucial Technology   | 16        | 17     | 0.37%   |
| Integral                    | 13        | 14     | 0.3%    |
| OCZ                         | 12        | 13     | 0.28%   |
| Kingston Technology Company | 12        | 12     | 0.28%   |
| O2 Micro                    | 11        | 11     | 0.26%   |
| Lenovo                      | 10        | 11     | 0.23%   |
| Corsair                     | 9         | 13     | 0.21%   |
| Team                        | 8         | 9      | 0.19%   |
| SPCC                        | 8         | 13     | 0.19%   |
| TCSUNBOW                    | 7         | 11     | 0.16%   |
| Star                        | 6         | 7      | 0.14%   |
| SABRENT                     | 6         | 6      | 0.14%   |
| JMicron Technology          | 6         | 10     | 0.14%   |
| Drevo                       | 6         | 9      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                  | 85        | 1.88%   |
| Seagate ST1000LM035-1RK172 970GB        | 56        | 1.24%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 51        | 1.13%   |
| Toshiba MQ01ABD100 1TB                  | 45        | 1%      |
| Unknown MMC Card  64GB                  | 43        | 0.95%   |
| Unknown MMC Card  128GB                 | 37        | 0.82%   |
| Samsung NVMe SSD Drive 512GB            | 37        | 0.82%   |
| Toshiba MQ01ABF050 500GB                | 31        | 0.69%   |
| Samsung NVMe SSD Drive 256GB            | 29        | 0.64%   |
| HGST HTS721010A9E630 1TB                | 29        | 0.64%   |
| HGST HTS541010A9E680 1TB                | 29        | 0.64%   |
| Unknown MMC Card  16GB                  | 28        | 0.62%   |
| Toshiba NVMe SSD Drive 256GB            | 25        | 0.55%   |
| Samsung SSD 850 EVO 500GB               | 25        | 0.55%   |
| Crucial CT500MX500SSD1 500GB            | 25        | 0.55%   |
| Unknown                                 | 24        | 0.53%   |
| Samsung SSD 860 EVO 500GB               | 23        | 0.51%   |
| Kingston SA400S37240G 240GB SSD         | 23        | 0.51%   |
| Unknown MMC Card  512GB                 | 22        | 0.49%   |
| SanDisk NVMe SSD Drive 512GB            | 21        | 0.47%   |
| Samsung SSD 850 EVO 250GB               | 21        | 0.47%   |
| Phison PS5013 E13 NVMe Controller 500GB | 21        | 0.47%   |
| Seagate ST2000LM003 HN-M201RAD 2TB      | 20        | 0.44%   |
| Samsung SSD 970 EVO Plus 1TB            | 20        | 0.44%   |
| Samsung NVMe SSD Drive 1024GB           | 20        | 0.44%   |
| Kingston SA400S37120G 120GB SSD         | 20        | 0.44%   |
| Crucial CT1000MX500SSD1 1TB             | 20        | 0.44%   |
| Unknown SD/MMC/MS PRO 249GB             | 19        | 0.42%   |
| Seagate ST9500325AS 500GB               | 19        | 0.42%   |
| Toshiba MQ04ABF100 1TB                  | 18        | 0.4%    |
| SK hynix NVMe SSD Drive 512GB           | 18        | 0.4%    |
| Crucial CT250MX500SSD1 250GB            | 18        | 0.4%    |
| Crucial CT240BX500SSD1 240GB            | 18        | 0.4%    |
| Toshiba NVMe SSD Drive 512GB            | 17        | 0.38%   |
| Seagate ST500LT012-1DG142 500GB         | 17        | 0.38%   |
| Samsung NVMe SSD Drive 1TB              | 17        | 0.38%   |
| SanDisk NVMe SSD Drive 256GB            | 16        | 0.35%   |
| WDC WDS500G2B0A-00SM50 500GB SSD        | 15        | 0.33%   |
| Seagate Expansion 4TB                   | 14        | 0.31%   |
| Samsung NVMe SSD Drive 500GB            | 14        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 424       | 578    | 32.05%  |
| WDC                 | 261       | 330    | 19.73%  |
| Toshiba             | 250       | 298    | 18.9%   |
| Hitachi             | 163       | 193    | 12.32%  |
| HGST                | 115       | 166    | 8.69%   |
| Samsung Electronics | 42        | 47     | 3.17%   |
| Fujitsu             | 28        | 35     | 2.12%   |
| Unknown             | 19        | 22     | 1.44%   |
| Apple               | 7         | 7      | 0.53%   |
| JMicron Technology  | 3         | 7      | 0.23%   |
| IBM/Hitachi         | 2         | 2      | 0.15%   |
| ASMT                | 2         | 25     | 0.15%   |
| USB3.0              | 1         | 1      | 0.08%   |
| PHD 3.0             | 1         | 1      | 0.08%   |
| Maxone              | 1         | 1      | 0.08%   |
| LaCie               | 1         | 1      | 0.08%   |
| Intenso             | 1         | 1      | 0.08%   |
| HGST HTS            | 1         | 1      | 0.08%   |
| ASMedia             | 1         | 1      | 0.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 304       | 416    | 22.11%  |
| Crucial             | 172       | 235    | 12.51%  |
| SanDisk             | 161       | 192    | 11.71%  |
| Kingston            | 123       | 150    | 8.95%   |
| WDC                 | 79        | 111    | 5.75%   |
| Intel               | 48        | 52     | 3.49%   |
| Micron Technology   | 39        | 47     | 2.84%   |
| China               | 38        | 50     | 2.76%   |
| SK hynix            | 35        | 45     | 2.55%   |
| Toshiba             | 33        | 43     | 2.4%    |
| LITEON              | 31        | 37     | 2.25%   |
| PNY                 | 29        | 33     | 2.11%   |
| Apple               | 29        | 38     | 2.11%   |
| Transcend           | 26        | 33     | 1.89%   |
| A-DATA Technology   | 26        | 31     | 1.89%   |
| LITEONIT            | 21        | 26     | 1.53%   |
| Integral            | 13        | 14     | 0.95%   |
| OCZ                 | 12        | 13     | 0.87%   |
| Seagate             | 8         | 8      | 0.58%   |
| Unknown             | 7         | 7      | 0.51%   |
| Team                | 7         | 8      | 0.51%   |
| SPCC                | 7         | 12     | 0.51%   |
| TCSUNBOW            | 6         | 10     | 0.44%   |
| Star                | 6         | 7      | 0.44%   |
| Drevo               | 6         | 9      | 0.44%   |
| Corsair             | 6         | 10     | 0.44%   |
| BHT                 | 6         | 9      | 0.44%   |
| Patriot             | 5         | 10     | 0.36%   |
| Netac               | 5         | 7      | 0.36%   |
| Lexar               | 4         | 5      | 0.29%   |
| ZTC                 | 3         | 6      | 0.22%   |
| Zheino              | 3         | 5      | 0.22%   |
| Vaseky              | 3         | 4      | 0.22%   |
| TO Exter            | 3         | 3      | 0.22%   |
| ORTIAL              | 3         | 3      | 0.22%   |
| NGFF                | 3         | 3      | 0.22%   |
| Maxtor              | 3         | 3      | 0.22%   |
| KIOXIA-EXCERIA      | 3         | 3      | 0.22%   |
| KingDian            | 3         | 6      | 0.22%   |
| BIWIN               | 3         | 3      | 0.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1280      | 1717   | 31.38%  |
| SSD     | 1259      | 1771   | 30.87%  |
| NVMe    | 1119      | 1459   | 27.43%  |
| MMC     | 378       | 494    | 9.27%   |
| Unknown | 43        | 53     | 1.05%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2338      | 3357   | 59.06%  |
| NVMe | 1113      | 1446   | 28.11%  |
| MMC  | 378       | 494    | 9.55%   |
| SAS  | 130       | 197    | 3.28%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1764      | 2393   | 69.04%  |
| 0.51-1.0   | 666       | 927    | 26.07%  |
| 1.01-2.0   | 90        | 119    | 3.52%   |
| 3.01-4.0   | 16        | 20     | 0.63%   |
| 4.01-10.0  | 16        | 21     | 0.63%   |
| 10.01-20.0 | 2         | 7      | 0.08%   |
| 2.01-3.0   | 1         | 1      | 0.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1127      | 30.43%  |
| 251-500        | 845       | 22.82%  |
| 501-1000       | 540       | 14.58%  |
| 1-20           | 287       | 7.75%   |
| 51-100         | 274       | 7.4%    |
| 21-50          | 230       | 6.21%   |
| 1001-2000      | 191       | 5.16%   |
| Unknown        | 100       | 2.7%    |
| More than 3000 | 61        | 1.65%   |
| 2001-3000      | 48        | 1.3%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1674      | 43.63%  |
| 21-50          | 701       | 18.27%  |
| 101-250        | 483       | 12.59%  |
| 51-100         | 433       | 11.28%  |
| 251-500        | 246       | 6.41%   |
| 501-1000       | 119       | 3.1%    |
| Unknown        | 100       | 2.61%   |
| 1001-2000      | 53        | 1.38%   |
| 2001-3000      | 14        | 0.36%   |
| More than 3000 | 13        | 0.34%   |
| 0              | 1         | 0.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 970GB               | 6         | 6      | 3.43%   |
| HGST HTS725050A7E630 500GB                     | 6         | 9      | 3.43%   |
| Seagate ST9500325AS 500GB                      | 5         | 9      | 2.86%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 4         | 5      | 2.29%   |
| Hitachi HTS547575A9E384 752GB                  | 4         | 6      | 2.29%   |
| Toshiba MK1656GSY 160GB                        | 3         | 3      | 1.71%   |
| Seagate ST500LM021-1KJ152 500GB                | 3         | 3      | 1.71%   |
| HGST HTS541010A9E680 1TB                       | 3         | 3      | 1.71%   |
| WDC WD2500BEVT-80A23T0 250GB                   | 2         | 4      | 1.14%   |
| Toshiba MK3256GSY 320GB                        | 2         | 3      | 1.14%   |
| Seagate ST500LT012-9WS142 500GB                | 2         | 2      | 1.14%   |
| Seagate ST1000LM014-SSHD-8GB                   | 2         | 3      | 1.14%   |
| Seagate ST1000LM014-1EJ164 1TB                 | 2         | 2      | 1.14%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 2         | 2      | 1.14%   |
| LITEON CS1-SP32-11 M.2 2242 32GB SSD           | 2         | 2      | 1.14%   |
| Intel SSDSC2BF180A5L 180GB                     | 2         | 2      | 1.14%   |
| Hitachi HTS547564A9E384 640GB                  | 2         | 2      | 1.14%   |
| Hitachi HTS545032B9A302 320GB                  | 2         | 3      | 1.14%   |
| Hitachi HTS545032B9A300 320GB                  | 2         | 2      | 1.14%   |
| Hitachi HTS545025B9A300 250GB                  | 2         | 2      | 1.14%   |
| Hitachi HTS543216L9A300 160GB                  | 2         | 2      | 1.14%   |
| Hitachi HTS542512K9SA00 120GB                  | 2         | 2      | 1.14%   |
| HGST HTS721010A9E630 1TB                       | 2         | 2      | 1.14%   |
| Drevo X1 SSD 120GB                             | 2         | 2      | 1.14%   |
| Crucial CT525MX300SSD4 528GB                   | 2         | 2      | 1.14%   |
| Zheino CHN mSATA02M 256 256GB SSD              | 1         | 2      | 0.57%   |
| WDC WD5000BPVT-55HXZT3 500GB                   | 1         | 1      | 0.57%   |
| WDC WD5000BEVT-75A0RT0 500GB                   | 1         | 1      | 0.57%   |
| WDC WD5000BEVT-60A0RT0 500GB                   | 1         | 2      | 0.57%   |
| WDC WD5000BEVT-35A0RT0 500GB                   | 1         | 1      | 0.57%   |
| WDC WD3200LPCX-24C6HT0 320GB                   | 1         | 1      | 0.57%   |
| WDC WD3200BEKT-75PVMT0 320GB                   | 1         | 1      | 0.57%   |
| WDC WD2500BEVT-75A23T0 250GB                   | 1         | 1      | 0.57%   |
| WDC WD2500BEVT-60A23T0 250GB                   | 1         | 1      | 0.57%   |
| WDC WD2500BEKT-60PVMT0 250GB                   | 1         | 1      | 0.57%   |
| WDC PC SN520 SDAPMUW-512G-1001 512GB           | 1         | 1      | 0.57%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD           | 1         | 1      | 0.57%   |
| Toshiba MQ01ABD100 1TB                         | 1         | 1      | 0.57%   |
| Toshiba MK6475GSX 640GB                        | 1         | 1      | 0.57%   |
| Toshiba MK5065GSXN 500GB                       | 1         | 1      | 0.57%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 46        | 53     | 26.44%  |
| Hitachi             | 28        | 31     | 16.09%  |
| Toshiba             | 21        | 22     | 12.07%  |
| HGST                | 15        | 18     | 8.62%   |
| WDC                 | 11        | 15     | 6.32%   |
| Crucial             | 10        | 10     | 5.75%   |
| Samsung Electronics | 9         | 9      | 5.17%   |
| Intel               | 6         | 6      | 3.45%   |
| SanDisk             | 4         | 4      | 2.3%    |
| Fujitsu             | 4         | 4      | 2.3%    |
| Micron Technology   | 3         | 3      | 1.72%   |
| LITEON              | 3         | 3      | 1.72%   |
| Kingston            | 3         | 3      | 1.72%   |
| Drevo               | 2         | 2      | 1.15%   |
| A-DATA Technology   | 2         | 2      | 1.15%   |
| Zheino              | 1         | 2      | 0.57%   |
| Team                | 1         | 1      | 0.57%   |
| SK hynix            | 1         | 1      | 0.57%   |
| OCZ                 | 1         | 1      | 0.57%   |
| Corsair             | 1         | 1      | 0.57%   |
| China               | 1         | 1      | 0.57%   |
| 2-Power             | 1         | 1      | 0.57%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 46        | 53     | 36.22%  |
| Hitachi             | 28        | 31     | 22.05%  |
| Toshiba             | 20        | 21     | 15.75%  |
| HGST                | 15        | 18     | 11.81%  |
| WDC                 | 10        | 14     | 7.87%   |
| Samsung Electronics | 4         | 4      | 3.15%   |
| Fujitsu             | 4         | 4      | 3.15%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 126       | 145    | 72.83%  |
| SSD  | 44        | 45     | 25.43%  |
| NVMe | 3         | 3      | 1.73%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                            | Notebooks | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| Toshiba THNSN5512GPUK NVMe 512GB | 1         | 2      | 50%     |
| Toshiba MQ01ABD100 1TB           | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 2         | 3      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2335      | 3705   | 63.26%  |
| Works    | 1184      | 1593   | 32.08%  |
| Malfunc  | 170       | 193    | 4.61%   |
| Failed   | 2         | 3      | 0.05%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2399      | 59.63%  |
| AMD                              | 411       | 10.22%  |
| Samsung Electronics              | 384       | 9.55%   |
| SanDisk                          | 186       | 4.62%   |
| SK hynix                         | 130       | 3.23%   |
| Toshiba America Info Systems     | 108       | 2.68%   |
| Phison Electronics               | 79        | 1.96%   |
| Kingston Technology Company      | 49        | 1.22%   |
| Micron Technology                | 45        | 1.12%   |
| KIOXIA                           | 40        | 0.99%   |
| Nvidia                           | 36        | 0.89%   |
| Micron/Crucial Technology        | 30        | 0.75%   |
| Silicon Motion                   | 22        | 0.55%   |
| ADATA Technology                 | 13        | 0.32%   |
| Silicon Integrated Systems [SiS] | 12        | 0.3%    |
| O2 Micro                         | 11        | 0.27%   |
| Apple                            | 11        | 0.27%   |
| Lenovo                           | 9         | 0.22%   |
| Solid State Storage Technology   | 8         | 0.2%    |
| Union Memory (Shenzhen)          | 5         | 0.12%   |
| Marvell Technology Group         | 5         | 0.12%   |
| Lite-On Technology               | 5         | 0.12%   |
| VIA Technologies                 | 4         | 0.1%    |
| Yangtze Memory Technologies      | 3         | 0.07%   |
| Shenzhen Longsys Electronics     | 3         | 0.07%   |
| JMicron Technology               | 3         | 0.07%   |
| Realtek Semiconductor            | 2         | 0.05%   |
| ASMedia Technology               | 2         | 0.05%   |
| Silicon Image                    | 1         | 0.02%   |
| Seagate Technology               | 1         | 0.02%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.02%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.02%   |
| INNOGRIT                         | 1         | 0.02%   |
| Enmotus                          | 1         | 0.02%   |
| Biwin Storage Technology         | 1         | 0.02%   |
| Unknown                          | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 345       | 7.98%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 274       | 6.34%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 232       | 5.37%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 226       | 5.23%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 182       | 4.21%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 176       | 4.07%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 159       | 3.68%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 117       | 2.71%   |
| Intel Volume Management Device NVMe RAID Controller                              | 109       | 2.52%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 109       | 2.52%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 101       | 2.34%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 84        | 1.94%   |
| Samsung NVMe SSD Controller 980                                                  | 73        | 1.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 71        | 1.64%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 70        | 1.62%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 69        | 1.6%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 68        | 1.57%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 60        | 1.39%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 49        | 1.13%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 48        | 1.11%   |
| Intel Comet Lake SATA AHCI Controller                                            | 48        | 1.11%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 46        | 1.06%   |
| Micron NVMe Storage Controller                                                   | 45        | 1.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 45        | 1.04%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 45        | 1.04%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 44        | 1.02%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 42        | 0.97%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 41        | 0.95%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 41        | 0.95%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 40        | 0.93%   |
| Phison PS5013 E13 NVMe Controller                                                | 40        | 0.93%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 39        | 0.9%    |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 38        | 0.88%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 35        | 0.81%   |
| SK hynix Non-Volatile memory controller                                          | 33        | 0.76%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 33        | 0.76%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 33        | 0.76%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 30        | 0.69%   |
| Intel Tiger Lake-LP SATA Controller                                              | 28        | 0.65%   |
| Intel SSD 660P Series                                                            | 27        | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 2374      | 57.37%  |
| NVMe | 1126      | 27.21%  |
| RAID | 349       | 8.43%   |
| IDE  | 289       | 6.98%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 2912      | 82.75%  |
| AMD    | 606       | 17.22%  |
| ARM    | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Custom APU 0405                           | 74        | 2.1%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 53        | 1.51%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 50        | 1.42%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 49        | 1.39%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 44        | 1.25%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 43        | 1.22%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 41        | 1.16%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 41        | 1.16%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 41        | 1.16%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 38        | 1.08%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 38        | 1.08%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 37        | 1.05%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 36        | 1.02%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 36        | 1.02%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 36        | 1.02%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 36        | 1.02%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 35        | 0.99%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 35        | 0.99%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 34        | 0.97%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 32        | 0.91%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 28        | 0.8%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 28        | 0.8%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 28        | 0.8%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 27        | 0.77%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 26        | 0.74%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 26        | 0.74%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 26        | 0.74%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 26        | 0.74%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 24        | 0.68%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 23        | 0.65%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 22        | 0.62%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 21        | 0.6%    |
| Intel Core i5-3230M CPU @ 2.60GHz             | 20        | 0.57%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 20        | 0.57%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 20        | 0.57%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 19        | 0.54%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 19        | 0.54%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 19        | 0.54%   |
| AMD A6-9225 RADEON R4, 5 COMPUTE CORES 2C+3G  | 19        | 0.54%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 18        | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 842       | 23.91%  |
| Intel Core i7           | 781       | 22.18%  |
| Other                   | 314       | 8.92%   |
| Intel Celeron           | 250       | 7.1%    |
| Intel Core i3           | 240       | 6.82%   |
| Intel Core 2 Duo        | 189       | 5.37%   |
| Intel Pentium           | 102       | 2.9%    |
| AMD Ryzen 7             | 94        | 2.67%   |
| AMD Ryzen 5             | 92        | 2.61%   |
| Intel Atom              | 70        | 1.99%   |
| AMD A6                  | 57        | 1.62%   |
| AMD A8                  | 39        | 1.11%   |
| Intel Pentium Dual-Core | 36        | 1.02%   |
| Intel Core 2            | 30        | 0.85%   |
| AMD Ryzen 3             | 30        | 0.85%   |
| Intel Pentium Dual      | 27        | 0.77%   |
| Intel Genuine           | 23        | 0.65%   |
| AMD A4                  | 23        | 0.65%   |
| Intel Celeron Dual-Core | 20        | 0.57%   |
| AMD Ryzen 9             | 19        | 0.54%   |
| AMD E1                  | 19        | 0.54%   |
| Intel Core i9           | 18        | 0.51%   |
| AMD A10                 | 17        | 0.48%   |
| AMD E                   | 16        | 0.45%   |
| Intel Celeron M         | 14        | 0.4%    |
| Intel Pentium Silver    | 13        | 0.37%   |
| AMD E2                  | 13        | 0.37%   |
| Intel Pentium M         | 9         | 0.26%   |
| AMD Turion 64 X2 Mobile | 8         | 0.23%   |
| AMD Athlon              | 8         | 0.23%   |
| AMD Ryzen 7 PRO         | 7         | 0.2%    |
| AMD FX                  | 7         | 0.2%    |
| AMD Athlon X2           | 7         | 0.2%    |
| AMD Athlon II           | 7         | 0.2%    |
| AMD Turion 64 Mobile    | 6         | 0.17%   |
| Intel Core M            | 5         | 0.14%   |
| AMD Phenom II           | 5         | 0.14%   |
| Intel Pentium Gold      | 4         | 0.11%   |
| Intel Core m3           | 4         | 0.11%   |
| Intel Core 2 Extreme    | 4         | 0.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1934      | 54.94%  |
| 4      | 1080      | 30.68%  |
| 6      | 194       | 5.51%   |
| 8      | 161       | 4.57%   |
| 1      | 99        | 2.81%   |
| 14     | 24        | 0.68%   |
| 12     | 15        | 0.43%   |
| 10     | 11        | 0.31%   |
| 3      | 2         | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3518      | 99.97%  |
| 2      | 1         | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 2459      | 69.86%  |
| 1      | 1061      | 30.14%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3418      | 96.8%   |
| Unknown        | 58        | 1.64%   |
| 32-bit         | 55        | 1.56%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 881       | 24.18%  |
| 0x306a9    | 224       | 6.15%   |
| 0x206a7    | 201       | 5.52%   |
| 0x1067a    | 150       | 4.12%   |
| 0x806ec    | 114       | 3.13%   |
| 0x806ea    | 114       | 3.13%   |
| 0x40651    | 110       | 3.02%   |
| 0x406e3    | 102       | 2.8%    |
| 0x806e9    | 99        | 2.72%   |
| 0x306d4    | 98        | 2.69%   |
| 0x20655    | 94        | 2.58%   |
| 0x806c1    | 88        | 2.42%   |
| 0x906ea    | 84        | 2.31%   |
| 0x6fd      | 66        | 1.81%   |
| 0x306c3    | 63        | 1.73%   |
| 0x406c4    | 62        | 1.7%    |
| 0x30678    | 60        | 1.65%   |
| 0xa0652    | 48        | 1.32%   |
| 0x906e9    | 45        | 1.24%   |
| 0x506e3    | 42        | 1.15%   |
| 0x506c9    | 42        | 1.15%   |
| 0x06006705 | 40        | 1.1%    |
| 0x706e5    | 36        | 0.99%   |
| 0x08108109 | 35        | 0.96%   |
| 0x08108102 | 34        | 0.93%   |
| 0x406c3    | 33        | 0.91%   |
| 0x20652    | 30        | 0.82%   |
| 0x0a50000c | 30        | 0.82%   |
| 0x07030105 | 30        | 0.82%   |
| 0x10676    | 29        | 0.8%    |
| 0x906a3    | 28        | 0.77%   |
| 0x806d1    | 28        | 0.77%   |
| 0x706a1    | 28        | 0.77%   |
| 0x6f6      | 24        | 0.66%   |
| 0x06006704 | 22        | 0.6%    |
| 0x806eb    | 21        | 0.58%   |
| 0x05000119 | 20        | 0.55%   |
| 0x08600106 | 19        | 0.52%   |
| 0x08600104 | 18        | 0.49%   |
| 0x906ed    | 16        | 0.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 635       | 18.03%  |
| IvyBridge        | 271       | 7.69%   |
| SandyBridge      | 246       | 6.98%   |
| Haswell          | 241       | 6.84%   |
| Penryn           | 203       | 5.76%   |
| Silvermont       | 188       | 5.34%   |
| Skylake          | 179       | 5.08%   |
| Westmere         | 151       | 4.29%   |
| Core             | 142       | 4.03%   |
| Unknown          | 137       | 3.89%   |
| Broadwell        | 129       | 3.66%   |
| TigerLake        | 126       | 3.58%   |
| Zen+             | 85        | 2.41%   |
| Excavator        | 80        | 2.27%   |
| Icelake          | 76        | 2.16%   |
| CometLake        | 72        | 2.04%   |
| Zen 2            | 64        | 1.82%   |
| Goldmont plus    | 55        | 1.56%   |
| Puma             | 51        | 1.45%   |
| Goldmont         | 49        | 1.39%   |
| Zen 3            | 41        | 1.16%   |
| P6               | 39        | 1.11%   |
| Alderlake Hybrid | 39        | 1.11%   |
| Zen              | 35        | 0.99%   |
| Bobcat           | 34        | 0.97%   |
| Bonnell          | 27        | 0.77%   |
| K10              | 21        | 0.6%    |
| Piledriver       | 20        | 0.57%   |
| K8 Hammer        | 19        | 0.54%   |
| Jaguar           | 18        | 0.51%   |
| Steamroller      | 14        | 0.4%    |
| K8 & K10 hybrid  | 12        | 0.34%   |
| Nehalem          | 11        | 0.31%   |
| K10 Llano        | 6         | 0.17%   |
| Tremont          | 4         | 0.11%   |
| NetBurst         | 2         | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2673      | 63.39%  |
| Nvidia                           | 806       | 19.11%  |
| AMD                              | 721       | 17.1%   |
| Silicon Integrated Systems [SiS] | 12        | 0.28%   |
| VIA Technologies                 | 4         | 0.09%   |
| ATI Technologies                 | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 256       | 5.88%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 234       | 5.37%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 162       | 3.72%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 139       | 3.19%   |
| Intel UHD Graphics 620                                                                   | 129       | 2.96%   |
| Intel Core Processor Integrated Graphics Controller                                      | 125       | 2.87%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 122       | 2.8%    |
| Intel HD Graphics 620                                                                    | 111       | 2.55%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 110       | 2.52%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 108       | 2.48%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 108       | 2.48%   |
| Intel HD Graphics 5500                                                                   | 100       | 2.3%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 91        | 2.09%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 90        | 2.07%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 89        | 2.04%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 80        | 1.84%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 80        | 1.84%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 74        | 1.7%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 67        | 1.54%   |
| AMD Renoir                                                                               | 59        | 1.35%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 58        | 1.33%   |
| Intel HD Graphics 630                                                                    | 55        | 1.26%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 53        | 1.22%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 53        | 1.22%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 52        | 1.19%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 45        | 1.03%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 42        | 0.96%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 41        | 0.94%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 40        | 0.92%   |
| Intel HD Graphics 530                                                                    | 40        | 0.92%   |
| Intel HD Graphics 500                                                                    | 40        | 0.92%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 39        | 0.9%    |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 35        | 0.8%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 33        | 0.76%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 32        | 0.73%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 30        | 0.69%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 30        | 0.69%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 29        | 0.67%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 28        | 0.64%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 26        | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 2019      | 57.16%  |
| Intel + Nvidia           | 570       | 16.14%  |
| 1 x AMD                  | 569       | 16.11%  |
| 1 x Nvidia               | 182       | 5.15%   |
| Intel + AMD              | 71        | 2.01%   |
| AMD + Nvidia             | 50        | 1.42%   |
| 2 x AMD                  | 30        | 0.85%   |
| 2 x Intel                | 14        | 0.4%    |
| 1 x SiS                  | 12        | 0.34%   |
| Other                    | 7         | 0.2%    |
| 1 x VIA                  | 4         | 0.11%   |
| 2 x Nvidia               | 2         | 0.06%   |
| Intel + 2 x Nvidia       | 1         | 0.03%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 3061      | 85.91%  |
| Proprietary | 422       | 11.84%  |
| Unknown     | 80        | 2.25%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2472      | 68.53%  |
| 0.01-0.5   | 419       | 11.62%  |
| 1.01-2.0   | 296       | 8.21%   |
| 3.01-4.0   | 168       | 4.66%   |
| 0.51-1.0   | 145       | 4.02%   |
| 5.01-6.0   | 58        | 1.61%   |
| 7.01-8.0   | 33        | 0.91%   |
| 2.01-3.0   | 9         | 0.25%   |
| 8.01-16.0  | 7         | 0.19%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 736       | 19.33%  |
| LG Display              | 595       | 15.63%  |
| Chimei Innolux          | 458       | 12.03%  |
| BOE                     | 422       | 11.08%  |
| Samsung Electronics     | 407       | 10.69%  |
| Sharp                   | 182       | 4.78%   |
| Apple                   | 109       | 2.86%   |
| Dell                    | 90        | 2.36%   |
| Lenovo                  | 77        | 2.02%   |
| Chi Mei Optoelectronics | 76        | 2%      |
| PANDA                   | 59        | 1.55%   |
| Goldstar                | 54        | 1.42%   |
| LG Philips              | 46        | 1.21%   |
| Hewlett-Packard         | 39        | 1.02%   |
| Acer                    | 36        | 0.95%   |
| Valve                   | 29        | 0.76%   |
| InfoVision              | 29        | 0.76%   |
| BenQ                    | 27        | 0.71%   |
| Analogix                | 26        | 0.68%   |
| Iiyama                  | 25        | 0.66%   |
| AOC                     | 25        | 0.66%   |
| Philips                 | 21        | 0.55%   |
| Ancor Communications    | 18        | 0.47%   |
| CSO                     | 17        | 0.45%   |
| Panasonic               | 16        | 0.42%   |
| Sony                    | 14        | 0.37%   |
| ViewSonic               | 13        | 0.34%   |
| Toshiba                 | 13        | 0.34%   |
| LGD                     | 13        | 0.34%   |
| InnoLux Display         | 12        | 0.32%   |
| HannStar                | 10        | 0.26%   |
| Vestel Elektronik       | 7         | 0.18%   |
| CPT                     | 7         | 0.18%   |
| Quanta Display          | 6         | 0.16%   |
| ASUSTek Computer        | 6         | 0.16%   |
| Seiko/Epson             | 5         | 0.13%   |
| Unknown                 | 4         | 0.11%   |
| TMX                     | 4         | 0.11%   |
| NEC Computers           | 4         | 0.11%   |
| Nvidia                  | 3         | 0.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 42        | 1.09%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 31        | 0.81%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 30        | 0.78%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 30        | 0.78%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 29        | 0.76%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 28        | 0.73%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 27        | 0.7%    |
| Analogix ANX7530 U ANX7539 800x1280                                      | 26        | 0.68%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 24        | 0.62%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 21        | 0.55%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 18        | 0.47%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 17        | 0.44%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 16        | 0.42%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 15        | 0.39%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 15        | 0.39%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 14        | 0.36%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch            | 14        | 0.36%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch                  | 13        | 0.34%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 13        | 0.34%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 13        | 0.34%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch           | 13        | 0.34%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 13        | 0.34%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch                  | 12        | 0.31%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 12        | 0.31%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                  | 11        | 0.29%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 11        | 0.29%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch              | 11        | 0.29%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 11        | 0.29%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch            | 11        | 0.29%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 11        | 0.29%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                  | 10        | 0.26%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 10        | 0.26%   |
| Samsung Electronics LCD Monitor SDCA029 2560x1440 294x165mm 13.3-inch    | 10        | 0.26%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 10        | 0.26%   |
| LG Display LCD Monitor LGD0250 1366x768 345x194mm 15.6-inch              | 10        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 10        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 10        | 0.26%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 10        | 0.26%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 10        | 0.26%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 10        | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1373      | 37.69%  |
| 1366x768 (WXGA)    | 1159      | 31.81%  |
| 1280x800 (WXGA)    | 197       | 5.41%   |
| 3840x2160 (4K)     | 158       | 4.34%   |
| 1600x900 (HD+)     | 142       | 3.9%    |
| 2560x1440 (QHD)    | 104       | 2.85%   |
| 1440x900 (WXGA+)   | 76        | 2.09%   |
| 1920x1200 (WUXGA)  | 62        | 1.7%    |
| 800x1280           | 53        | 1.45%   |
| 2560x1600          | 43        | 1.18%   |
| 1680x1050 (WSXGA+) | 30        | 0.82%   |
| 3840x2400          | 28        | 0.77%   |
| 2880x1800          | 24        | 0.66%   |
| 3440x1440          | 22        | 0.6%    |
| 3200x1800 (QHD+)   | 21        | 0.58%   |
| 1280x1024 (SXGA)   | 18        | 0.49%   |
| 1024x600           | 17        | 0.47%   |
| 2160x1440          | 13        | 0.36%   |
| 2560x1080          | 11        | 0.3%    |
| Unknown            | 10        | 0.27%   |
| 1360x768           | 8         | 0.22%   |
| 3072x1920          | 6         | 0.16%   |
| 1024x768 (XGA)     | 6         | 0.16%   |
| 2256x1504          | 5         | 0.14%   |
| 1920x540           | 5         | 0.14%   |
| 1680x945           | 5         | 0.14%   |
| 3456x2160          | 4         | 0.11%   |
| 2560x1700          | 4         | 0.11%   |
| 3840x1080          | 3         | 0.08%   |
| 2880x1920          | 3         | 0.08%   |
| 1280x768           | 3         | 0.08%   |
| 3000x2000          | 2         | 0.05%   |
| 2520x1680          | 2         | 0.05%   |
| 2240x1400          | 2         | 0.05%   |
| 2160x1350          | 2         | 0.05%   |
| 1920x1280          | 2         | 0.05%   |
| 1360x765           | 2         | 0.05%   |
| 8960x2160          | 1         | 0.03%   |
| 800x480            | 1         | 0.03%   |
| 7680x1080          | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1568      | 41.32%  |
| 13      | 613       | 16.15%  |
| 14      | 376       | 9.91%   |
| 17      | 242       | 6.38%   |
| 12      | 172       | 4.53%   |
| 11      | 108       | 2.85%   |
| 27      | 98        | 2.58%   |
| Unknown | 83        | 2.19%   |
| 24      | 80        | 2.11%   |
| 21      | 67        | 1.77%   |
| 23      | 64        | 1.69%   |
| 31      | 36        | 0.95%   |
| 16      | 32        | 0.84%   |
| 34      | 29        | 0.76%   |
| 7       | 29        | 0.76%   |
| 18      | 28        | 0.74%   |
| 10      | 26        | 0.69%   |
| 84      | 19        | 0.5%    |
| 19      | 16        | 0.42%   |
| 25      | 14        | 0.37%   |
| 22      | 12        | 0.32%   |
| 72      | 9         | 0.24%   |
| 26      | 8         | 0.21%   |
| 54      | 7         | 0.18%   |
| 40      | 7         | 0.18%   |
| 48      | 6         | 0.16%   |
| 20      | 6         | 0.16%   |
| 8       | 6         | 0.16%   |
| 65      | 4         | 0.11%   |
| 50      | 3         | 0.08%   |
| 35      | 3         | 0.08%   |
| 33      | 3         | 0.08%   |
| 32      | 3         | 0.08%   |
| 28      | 3         | 0.08%   |
| 49      | 2         | 0.05%   |
| 46      | 2         | 0.05%   |
| 142     | 1         | 0.03%   |
| 99      | 1         | 0.03%   |
| 86      | 1         | 0.03%   |
| 75      | 1         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 2176      | 57.55%  |
| 201-300        | 663       | 17.54%  |
| 351-400        | 308       | 8.15%   |
| 501-600        | 246       | 6.51%   |
| 401-500        | 115       | 3.04%   |
| Unknown        | 83        | 2.2%    |
| 601-700        | 48        | 1.27%   |
| 701-800        | 35        | 0.93%   |
| 1501-2000      | 30        | 0.79%   |
| 1-100          | 29        | 0.77%   |
| 1001-1500      | 26        | 0.69%   |
| 801-900        | 12        | 0.32%   |
| 101-200        | 6         | 0.16%   |
| More than 2000 | 2         | 0.05%   |
| 901-1000       | 2         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 2793      | 80.75%  |
| 16/10   | 448       | 12.95%  |
| Unknown | 52        | 1.5%    |
| 3/2     | 41        | 1.19%   |
| 21/9    | 34        | 0.98%   |
| 0.67    | 29        | 0.84%   |
| 0.62    | 27        | 0.78%   |
| 5/4     | 13        | 0.38%   |
| 4/3     | 13        | 0.38%   |
| 6/5     | 3         | 0.09%   |
| 32/9    | 3         | 0.09%   |
| 1.00    | 2         | 0.06%   |
| 3.40    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1567      | 41.32%  |
| 81-90          | 689       | 18.17%  |
| 71-80          | 298       | 7.86%   |
| 121-130        | 200       | 5.27%   |
| 201-250        | 186       | 4.91%   |
| 61-70          | 165       | 4.35%   |
| 51-60          | 110       | 2.9%    |
| 301-350        | 104       | 2.74%   |
| Unknown        | 83        | 2.19%   |
| 351-500        | 76        | 2%      |
| More than 1000 | 53        | 1.4%    |
| 131-140        | 41        | 1.08%   |
| 251-300        | 38        | 1%      |
| 151-200        | 37        | 0.98%   |
| 1-40           | 35        | 0.92%   |
| 111-120        | 29        | 0.76%   |
| 141-150        | 28        | 0.74%   |
| 41-50          | 25        | 0.66%   |
| 501-1000       | 16        | 0.42%   |
| 91-100         | 12        | 0.32%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1416      | 37.79%  |
| 101-120       | 1159      | 30.93%  |
| 51-100        | 525       | 14.01%  |
| 161-240       | 359       | 9.58%   |
| More than 240 | 161       | 4.3%    |
| Unknown       | 83        | 2.22%   |
| 1-50          | 44        | 1.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 3011      | 84.13%  |
| 2     | 445       | 12.43%  |
| 0     | 78        | 2.18%   |
| 3     | 40        | 1.12%   |
| 4     | 4         | 0.11%   |
| 5     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1913      | 34.9%   |
| Realtek Semiconductor             | 1682      | 30.68%  |
| Qualcomm Atheros                  | 758       | 13.83%  |
| Broadcom                          | 411       | 7.5%    |
| Broadcom Limited                  | 94        | 1.71%   |
| Marvell Technology Group          | 87        | 1.59%   |
| Ralink Technology                 | 44        | 0.8%    |
| Ralink                            | 43        | 0.78%   |
| MediaTek                          | 43        | 0.78%   |
| TP-Link                           | 41        | 0.75%   |
| Ericsson Business Mobile Networks | 38        | 0.69%   |
| Dell                              | 31        | 0.57%   |
| Nvidia                            | 26        | 0.47%   |
| ASIX Electronics                  | 25        | 0.46%   |
| Lenovo                            | 22        | 0.4%    |
| DisplayLink                       | 22        | 0.4%    |
| Hewlett-Packard                   | 18        | 0.33%   |
| Qualcomm                          | 17        | 0.31%   |
| Samsung Electronics               | 16        | 0.29%   |
| Huawei Technologies               | 12        | 0.22%   |
| Silicon Integrated Systems [SiS]  | 11        | 0.2%    |
| Sierra Wireless                   | 11        | 0.2%    |
| JMicron Technology                | 11        | 0.2%    |
| NetGear                           | 7         | 0.13%   |
| Edimax Technology                 | 7         | 0.13%   |
| Qualcomm Atheros Communications   | 6         | 0.11%   |
| OnePlus Technology (Shenzhen)     | 5         | 0.09%   |
| Micro Star International          | 5         | 0.09%   |
| ICS Advent                        | 5         | 0.09%   |
| Google                            | 5         | 0.09%   |
| Belkin Components                 | 5         | 0.09%   |
| Attansic Technology               | 5         | 0.09%   |
| ASUSTek Computer                  | 5         | 0.09%   |
| VIA Technologies                  | 4         | 0.07%   |
| Apple                             | 4         | 0.07%   |
| Xiaomi                            | 3         | 0.05%   |
| Motorola PCS                      | 3         | 0.05%   |
| Fibocom                           | 3         | 0.05%   |
| AMD                               | 3         | 0.05%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 892       | 13.44%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 372       | 5.6%    |
| Intel Wi-Fi 6 AX200                                                     | 170       | 2.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 157       | 2.36%   |
| Intel Wireless 8265 / 8275                                              | 144       | 2.17%   |
| Intel Wireless 7265                                                     | 137       | 2.06%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 130       | 1.96%   |
| Intel Wireless 7260                                                     | 129       | 1.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 127       | 1.91%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 126       | 1.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 124       | 1.87%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 115       | 1.73%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 105       | 1.58%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 104       | 1.57%   |
| Intel Wireless 8260                                                     | 89        | 1.34%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 85        | 1.28%   |
| Intel Wi-Fi 6 AX201                                                     | 84        | 1.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 81        | 1.22%   |
| Intel Wireless 3165                                                     | 73        | 1.1%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 69        | 1.04%   |
| Intel 82577LM Gigabit Network Connection                                | 63        | 0.95%   |
| Broadcom BCM43142 802.11b/g/n                                           | 62        | 0.93%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 61        | 0.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 60        | 0.9%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 60        | 0.9%    |
| Intel Ethernet Connection I218-LM                                       | 56        | 0.84%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 55        | 0.83%   |
| Intel Ethernet Connection (4) I219-LM                                   | 53        | 0.8%    |
| Intel Wireless 3160                                                     | 48        | 0.72%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 48        | 0.72%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 45        | 0.68%   |
| Intel Wireless-AC 9260                                                  | 45        | 0.68%   |
| Intel WiFi Link 5100                                                    | 45        | 0.68%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 44        | 0.66%   |
| Intel Centrino Ultimate-N 6300                                          | 43        | 0.65%   |
| Intel Ethernet Connection (3) I218-LM                                   | 41        | 0.62%   |
| Intel Centrino Advanced-N 6200                                          | 40        | 0.6%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 39        | 0.59%   |
| Intel Centrino Advanced-N 6235                                          | 39        | 0.59%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 39        | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1830      | 49.82%  |
| Qualcomm Atheros                | 662       | 18.02%  |
| Realtek Semiconductor           | 552       | 15.03%  |
| Broadcom                        | 312       | 8.49%   |
| Broadcom Limited                | 73        | 1.99%   |
| Ralink Technology               | 44        | 1.2%    |
| Ralink                          | 43        | 1.17%   |
| MediaTek                        | 38        | 1.03%   |
| TP-Link                         | 35        | 0.95%   |
| Dell                            | 17        | 0.46%   |
| Qualcomm                        | 8         | 0.22%   |
| Sierra Wireless                 | 7         | 0.19%   |
| NetGear                         | 7         | 0.19%   |
| Edimax Technology               | 7         | 0.19%   |
| Qualcomm Atheros Communications | 6         | 0.16%   |
| Micro Star International        | 5         | 0.14%   |
| Belkin Components               | 5         | 0.14%   |
| ASUSTek Computer                | 4         | 0.11%   |
| Fibocom                         | 3         | 0.08%   |
| Wacom                           | 2         | 0.05%   |
| Hewlett-Packard                 | 2         | 0.05%   |
| ZyDAS                           | 1         | 0.03%   |
| Senao                           | 1         | 0.03%   |
| Microsoft                       | 1         | 0.03%   |
| Marvell Technology Group        | 1         | 0.03%   |
| Linksys                         | 1         | 0.03%   |
| InProComm                       | 1         | 0.03%   |
| Fujitsu Siemens Computers       | 1         | 0.03%   |
| D-Link                          | 1         | 0.03%   |
| Askey Computer                  | 1         | 0.03%   |
| Apple                           | 1         | 0.03%   |
| 3Com                            | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 170       | 4.6%    |
| Intel Wireless 8265 / 8275                                              | 144       | 3.9%    |
| Intel Wireless 7265                                                     | 137       | 3.71%   |
| Intel Wireless 7260                                                     | 129       | 3.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 127       | 3.44%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 126       | 3.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 124       | 3.36%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 115       | 3.11%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 105       | 2.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 104       | 2.82%   |
| Intel Wireless 8260                                                     | 89        | 2.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 85        | 2.3%    |
| Intel Wi-Fi 6 AX201                                                     | 84        | 2.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 81        | 2.19%   |
| Intel Wireless 3165                                                     | 73        | 1.98%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 69        | 1.87%   |
| Broadcom BCM43142 802.11b/g/n                                           | 62        | 1.68%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 61        | 1.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 60        | 1.62%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 60        | 1.62%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 55        | 1.49%   |
| Intel Wireless 3160                                                     | 48        | 1.3%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 48        | 1.3%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 45        | 1.22%   |
| Intel Wireless-AC 9260                                                  | 45        | 1.22%   |
| Intel WiFi Link 5100                                                    | 45        | 1.22%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 44        | 1.19%   |
| Intel Centrino Ultimate-N 6300                                          | 43        | 1.16%   |
| Intel Centrino Advanced-N 6200                                          | 40        | 1.08%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 39        | 1.06%   |
| Intel Centrino Advanced-N 6235                                          | 39        | 1.06%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 39        | 1.06%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 37        | 1%      |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 33        | 0.89%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 32        | 0.87%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 31        | 0.84%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 29        | 0.79%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 28        | 0.76%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 28        | 0.76%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 27        | 0.73%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1451      | 51.47%  |
| Intel                            | 706       | 25.04%  |
| Qualcomm Atheros                 | 180       | 6.39%   |
| Broadcom                         | 163       | 5.78%   |
| Marvell Technology Group         | 86        | 3.05%   |
| Nvidia                           | 26        | 0.92%   |
| ASIX Electronics                 | 25        | 0.89%   |
| Broadcom Limited                 | 24        | 0.85%   |
| DisplayLink                      | 22        | 0.78%   |
| Lenovo                           | 21        | 0.74%   |
| Samsung Electronics              | 11        | 0.39%   |
| JMicron Technology               | 11        | 0.39%   |
| Silicon Integrated Systems [SiS] | 10        | 0.35%   |
| Huawei Technologies              | 10        | 0.35%   |
| Qualcomm                         | 9         | 0.32%   |
| TP-Link                          | 6         | 0.21%   |
| OnePlus Technology (Shenzhen)    | 5         | 0.18%   |
| ICS Advent                       | 5         | 0.18%   |
| Google                           | 5         | 0.18%   |
| Attansic Technology              | 5         | 0.18%   |
| VIA Technologies                 | 4         | 0.14%   |
| Sierra Wireless                  | 4         | 0.14%   |
| MediaTek                         | 4         | 0.14%   |
| Hewlett-Packard                  | 4         | 0.14%   |
| Xiaomi                           | 3         | 0.11%   |
| Motorola PCS                     | 3         | 0.11%   |
| Apple                            | 3         | 0.11%   |
| ZTE WCDMA Technologies MSM       | 2         | 0.07%   |
| OPPO Electronics                 | 2         | 0.07%   |
| Microchip Technology             | 2         | 0.07%   |
| HTC (High Tech Computer)         | 2         | 0.07%   |
| T & A Mobile Phones              | 1         | 0.04%   |
| Research In Motion               | 1         | 0.04%   |
| Linksys                          | 1         | 0.04%   |
| ASUSTek Computer                 | 1         | 0.04%   |
| Aquantia                         | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 892       | 31.34%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 372       | 13.07%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 157       | 5.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 130       | 4.57%   |
| Intel 82577LM Gigabit Network Connection                          | 63        | 2.21%   |
| Intel Ethernet Connection I218-LM                                 | 56        | 1.97%   |
| Intel Ethernet Connection (4) I219-LM                             | 53        | 1.86%   |
| Intel Ethernet Connection (3) I218-LM                             | 41        | 1.44%   |
| Intel Ethernet Connection I219-LM                                 | 37        | 1.3%    |
| Intel 82567LM Gigabit Network Connection                          | 36        | 1.26%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 35        | 1.23%   |
| Intel Ethernet Connection I217-LM                                 | 34        | 1.19%   |
| Intel Ethernet Connection (4) I219-V                              | 30        | 1.05%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 27        | 0.95%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 25        | 0.88%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 23        | 0.81%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 22        | 0.77%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 22        | 0.77%   |
| ASIX AX88179 Gigabit Ethernet                                     | 22        | 0.77%   |
| Intel Ethernet Connection I219-V                                  | 19        | 0.67%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 17        | 0.6%    |
| Intel Ethernet Connection (7) I219-LM                             | 17        | 0.6%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 16        | 0.56%   |
| Nvidia MCP79 Ethernet                                             | 16        | 0.56%   |
| Intel Ethernet Connection (2) I219-LM                             | 16        | 0.56%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 15        | 0.53%   |
| Intel Ethernet Connection (6) I219-V                              | 15        | 0.53%   |
| Intel 82566MM Gigabit Network Connection                          | 14        | 0.49%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 14        | 0.49%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 13        | 0.46%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 13        | 0.46%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 13        | 0.46%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 13        | 0.46%   |
| Realtek Killer E3000 2.5GbE Controller                            | 12        | 0.42%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 12        | 0.42%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 12        | 0.42%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 11        | 0.39%   |
| Realtek RTL8125 2.5GbE Controller                                 | 11        | 0.39%   |
| Intel 82579V Gigabit Network Connection                           | 11        | 0.39%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 11        | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3465      | 55.12%  |
| Ethernet | 2722      | 43.3%   |
| Modem    | 94        | 1.5%    |
| Unknown  | 5         | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2973      | 80.68%  |
| Ethernet | 711       | 19.29%  |
| Modem    | 1         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2477      | 70.31%  |
| 1     | 975       | 27.68%  |
| 0     | 56        | 1.59%   |
| 3     | 14        | 0.4%    |
| 4     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3141      | 87.81%  |
| Yes  | 436       | 12.19%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1334      | 48.37%  |
| Qualcomm Atheros Communications | 250       | 9.06%   |
| Realtek Semiconductor           | 221       | 8.01%   |
| Broadcom                        | 192       | 6.96%   |
| IMC Networks                    | 161       | 5.84%   |
| Foxconn / Hon Hai               | 94        | 3.41%   |
| Apple                           | 94        | 3.41%   |
| Lite-On Technology              | 90        | 3.26%   |
| Dell                            | 71        | 2.57%   |
| Cambridge Silicon Radio         | 64        | 2.32%   |
| Toshiba                         | 52        | 1.89%   |
| Hewlett-Packard                 | 39        | 1.41%   |
| Realtek                         | 21        | 0.76%   |
| Alps Electric                   | 18        | 0.65%   |
| Foxconn International           | 14        | 0.51%   |
| Ralink                          | 9         | 0.33%   |
| ASUSTek Computer                | 8         | 0.29%   |
| Ralink Technology               | 6         | 0.22%   |
| Askey Computer                  | 6         | 0.22%   |
| Taiyo Yuden                     | 4         | 0.15%   |
| Belkin Components               | 4         | 0.15%   |
| USI                             | 1         | 0.04%   |
| Sitecom Europe                  | 1         | 0.04%   |
| Integrated System Solution      | 1         | 0.04%   |
| Fujitsu                         | 1         | 0.04%   |
| Edimax Technology               | 1         | 0.04%   |
| Unknown                         | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 583       | 21.13%  |
| Intel AX201 Bluetooth                               | 224       | 8.12%   |
| Intel AX200 Bluetooth                               | 166       | 6.02%   |
| Qualcomm Atheros  Bluetooth Device                  | 155       | 5.62%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 141       | 5.11%   |
| Realtek Bluetooth Radio                             | 126       | 4.57%   |
| IMC Networks Bluetooth Radio                        | 103       | 3.73%   |
| Realtek  Bluetooth 4.2 Adapter                      | 67        | 2.43%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 64        | 2.32%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 59        | 2.14%   |
| Apple Bluetooth Host Controller                     | 59        | 2.14%   |
| Foxconn / Hon Hai Bluetooth Device                  | 51        | 1.85%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 50        | 1.81%   |
| Broadcom BCM2045B (BDC-2.1)                         | 40        | 1.45%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 37        | 1.34%   |
| Intel Wireless-AC 3168 Bluetooth                    | 37        | 1.34%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 36        | 1.3%    |
| Intel Bluetooth Device                              | 31        | 1.12%   |
| Intel AX210 Bluetooth                               | 30        | 1.09%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 29        | 1.05%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 27        | 0.98%   |
| Dell DW375 Bluetooth Module                         | 26        | 0.94%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 25        | 0.91%   |
| Apple Bluetooth USB Host Controller                 | 25        | 0.91%   |
| IMC Networks Bluetooth Device                       | 22        | 0.8%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 20        | 0.72%   |
| Lite-On Bluetooth Device                            | 19        | 0.69%   |
| IMC Networks Wireless_Device                        | 19        | 0.69%   |
| Dell BCM20702A0 Bluetooth Module                    | 19        | 0.69%   |
| Realtek 802.11ac WLAN Adapter                       | 18        | 0.65%   |
| Lite-On Atheros AR3012 Bluetooth                    | 18        | 0.65%   |
| Toshiba Bluetooth Device                            | 15        | 0.54%   |
| HP Broadcom 2070 Bluetooth Combo                    | 15        | 0.54%   |
| Foxconn International BCM43142A0 Bluetooth module   | 14        | 0.51%   |
| Broadcom HP Portable SoftSailing                    | 14        | 0.51%   |
| Realtek RTL8723B Bluetooth                          | 13        | 0.47%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 12        | 0.43%   |
| Broadcom BCM2045 Bluetooth                          | 12        | 0.43%   |
| Toshiba Atheros AR3012 Bluetooth                    | 11        | 0.4%    |
| Realtek RTL8821A Bluetooth                          | 9         | 0.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2830      | 67.85%  |
| AMD                              | 655       | 15.7%   |
| Nvidia                           | 432       | 10.36%  |
| C-Media Electronics              | 31        | 0.74%   |
| Realtek Semiconductor            | 24        | 0.58%   |
| GN Netcom                        | 17        | 0.41%   |
| Lenovo                           | 16        | 0.38%   |
| Plantronics                      | 15        | 0.36%   |
| Texas Instruments                | 13        | 0.31%   |
| Silicon Integrated Systems [SiS] | 12        | 0.29%   |
| JMTek                            | 9         | 0.22%   |
| Apple                            | 9         | 0.22%   |
| Creative Technology              | 8         | 0.19%   |
| Logitech                         | 6         | 0.14%   |
| Corsair                          | 5         | 0.12%   |
| Conexant Systems                 | 5         | 0.12%   |
| ASUSTek Computer                 | 5         | 0.12%   |
| VIA Technologies                 | 4         | 0.1%    |
| Hewlett-Packard                  | 4         | 0.1%    |
| Generalplus Technology           | 4         | 0.1%    |
| Focusrite-Novation               | 4         | 0.1%    |
| Blue Microphones                 | 4         | 0.1%    |
| Yamaha                           | 3         | 0.07%   |
| XMOS                             | 3         | 0.07%   |
| SteelSeries ApS                  | 3         | 0.07%   |
| Sony                             | 3         | 0.07%   |
| Sennheiser Communications        | 3         | 0.07%   |
| RODE Microphones                 | 3         | 0.07%   |
| Dell                             | 3         | 0.07%   |
| Samsung Electronics              | 2         | 0.05%   |
| PreSonus Audio Electronics       | 2         | 0.05%   |
| M-Audio                          | 2         | 0.05%   |
| Kingston Technology              | 2         | 0.05%   |
| GYROCOM C&C                      | 2         | 0.05%   |
| Google                           | 2         | 0.05%   |
| AudioQuest                       | 2         | 0.05%   |
| AKAI Professional M.I.           | 2         | 0.05%   |
| Trust                            | 1         | 0.02%   |
| Toshiba                          | 1         | 0.02%   |
| Tenx Technology                  | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 386       | 7.72%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 316       | 6.32%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 250       | 5%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 199       | 3.98%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 196       | 3.92%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 162       | 3.24%   |
| Intel 8 Series HD Audio Controller                                                                | 141       | 2.82%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 140       | 2.8%    |
| Intel Cannon Lake PCH cAVS                                                                        | 135       | 2.7%    |
| Intel Broadwell-U Audio Controller                                                                | 129       | 2.58%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 126       | 2.52%   |
| AMD FCH Azalia Controller                                                                         | 125       | 2.5%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 124       | 2.48%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 111       | 2.22%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 106       | 2.12%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 101       | 2.02%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 96        | 1.92%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 87        | 1.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 85        | 1.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 84        | 1.68%   |
| AMD Kabini HDMI/DP Audio                                                                          | 82        | 1.64%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 81        | 1.62%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 79        | 1.58%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 77        | 1.54%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 75        | 1.5%    |
| AMD High Definition Audio Controller                                                              | 67        | 1.34%   |
| Intel Comet Lake PCH cAVS                                                                         | 66        | 1.32%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 62        | 1.24%   |
| Intel CM238 HD Audio Controller                                                                   | 61        | 1.22%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 56        | 1.12%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 55        | 1.1%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 50        | 1%      |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 49        | 0.98%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 47        | 0.94%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 47        | 0.94%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 42        | 0.84%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 41        | 0.82%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 38        | 0.76%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 35        | 0.7%    |
| Nvidia GA104 High Definition Audio Controller                                                     | 33        | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 547       | 27.36%  |
| SK hynix            | 481       | 24.06%  |
| Micron Technology   | 261       | 13.06%  |
| Crucial             | 163       | 8.15%   |
| Unknown             | 145       | 7.25%   |
| Kingston            | 134       | 6.7%    |
| Corsair             | 46        | 2.3%    |
| Ramaxel Technology  | 44        | 2.2%    |
| Elpida              | 33        | 1.65%   |
| Nanya Technology    | 31        | 1.55%   |
| A-DATA Technology   | 21        | 1.05%   |
| Unknown (ABCD)      | 16        | 0.8%    |
| Unknown             | 9         | 0.45%   |
| Toshiba             | 6         | 0.3%    |
| Qimonda             | 5         | 0.25%   |
| GSkill              | 4         | 0.2%    |
| GOODRAM             | 4         | 0.2%    |
| Transcend           | 3         | 0.15%   |
| Patriot             | 3         | 0.15%   |
| Essencore           | 3         | 0.15%   |
| ASint Technology    | 3         | 0.15%   |
| Apacer              | 3         | 0.15%   |
| 4ea5                | 3         | 0.15%   |
| Timetec             | 2         | 0.1%    |
| Neo Forza           | 2         | 0.1%    |
| Innodisk            | 2         | 0.1%    |
| G.Skill             | 2         | 0.1%    |
| ff                  | 2         | 0.1%    |
| A Force             | 2         | 0.1%    |
| V-Color             | 1         | 0.05%   |
| Unknown (F301)      | 1         | 0.05%   |
| Unknown (CB83)      | 1         | 0.05%   |
| Unknown (0B38)      | 1         | 0.05%   |
| Team                | 1         | 0.05%   |
| Smart               | 1         | 0.05%   |
| SHARETRONIC         | 1         | 0.05%   |
| OnBoard             | 1         | 0.05%   |
| Miron               | 1         | 0.05%   |
| Memox               | 1         | 0.05%   |
| Lexar               | 1         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 42        | 1.97%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 32        | 1.5%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 25        | 1.17%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 25        | 1.17%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 24        | 1.13%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 23        | 1.08%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 21        | 0.99%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 21        | 0.99%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 20        | 0.94%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 19        | 0.89%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 18        | 0.85%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 18        | 0.85%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 17        | 0.8%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 17        | 0.8%    |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 16        | 0.75%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 16        | 0.75%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 15        | 0.7%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 14        | 0.66%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 14        | 0.66%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 14        | 0.66%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 13        | 0.61%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 13        | 0.61%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 12        | 0.56%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 12        | 0.56%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s          | 12        | 0.56%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 11        | 0.52%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 11        | 0.52%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 11        | 0.52%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 10        | 0.47%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 10        | 0.47%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 10        | 0.47%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 10        | 0.47%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 10        | 0.47%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 10        | 0.47%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 9         | 0.42%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 9         | 0.42%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 9         | 0.42%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 9         | 0.42%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 9         | 0.42%   |
| Unknown                                                          | 9         | 0.42%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 756       | 44%     |
| DDR3    | 576       | 33.53%  |
| DDR2    | 97        | 5.65%   |
| LPDDR4  | 94        | 5.47%   |
| LPDDR3  | 89        | 5.18%   |
| SDRAM   | 50        | 2.91%   |
| DDR5    | 19        | 1.11%   |
| Unknown | 12        | 0.7%    |
| LPDDR5  | 9         | 0.52%   |
| DRAM    | 8         | 0.47%   |
| DDR     | 8         | 0.47%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1477      | 86.53%  |
| Row Of Chips | 182       | 10.66%  |
| Unknown      | 22        | 1.29%   |
| Chip         | 18        | 1.05%   |
| DIMM         | 8         | 0.47%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 709       | 38%     |
| 4096  | 562       | 30.12%  |
| 2048  | 247       | 13.24%  |
| 16384 | 223       | 11.95%  |
| 1024  | 74        | 3.97%   |
| 32768 | 40        | 2.14%   |
| 512   | 10        | 0.54%   |
| 256   | 1         | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 414       | 22.44%  |
| 2667    | 378       | 20.49%  |
| 3200    | 259       | 14.04%  |
| 2400    | 137       | 7.43%   |
| 2133    | 102       | 5.53%   |
| 1334    | 83        | 4.5%    |
| 1333    | 61        | 3.31%   |
| 667     | 49        | 2.66%   |
| 1867    | 44        | 2.38%   |
| 4267    | 40        | 2.17%   |
| Unknown | 40        | 2.17%   |
| 1067    | 33        | 1.79%   |
| 800     | 25        | 1.36%   |
| 4199    | 23        | 1.25%   |
| 3266    | 23        | 1.25%   |
| 2048    | 20        | 1.08%   |
| 4800    | 19        | 1.03%   |
| 1066    | 15        | 0.81%   |
| 4266    | 12        | 0.65%   |
| 975     | 11        | 0.6%    |
| 6400    | 9         | 0.49%   |
| 533     | 9         | 0.49%   |
| 1866    | 8         | 0.43%   |
| 8400    | 5         | 0.27%   |
| 3733    | 5         | 0.27%   |
| 3000    | 3         | 0.16%   |
| 1639    | 3         | 0.16%   |
| 400     | 3         | 0.16%   |
| 1776    | 2         | 0.11%   |
| 933     | 2         | 0.11%   |
| 333     | 2         | 0.11%   |
| 5600    | 1         | 0.05%   |
| 2933    | 1         | 0.05%   |
| 1777    | 1         | 0.05%   |
| 1596    | 1         | 0.05%   |
| 1200    | 1         | 0.05%   |
| 666     | 1         | 0.05%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Canon                 | 8         | 29.63%  |
| Hewlett-Packard       | 6         | 22.22%  |
| Samsung Electronics   | 3         | 11.11%  |
| Lexmark International | 3         | 11.11%  |
| Prolific Technology   | 2         | 7.41%   |
| Brother Industries    | 2         | 7.41%   |
| STMicroelectronics    | 1         | 3.7%    |
| Seiko Epson           | 1         | 3.7%    |
| Kyocera               | 1         | 3.7%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port                             | 2         | 7.14%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 3.57%   |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F    | 1         | 3.57%   |
| Samsung CLX-6260 Series                                   | 1         | 3.57%   |
| Samsung CLP-300 Series                                    | 1         | 3.57%   |
| Samsung C43x Series                                       | 1         | 3.57%   |
| Lexmark International MS610de                             | 1         | 3.57%   |
| Lexmark International C544                                | 1         | 3.57%   |
| Lexmark International 640 Series                          | 1         | 3.57%   |
| Kyocera FS-1041                                           | 1         | 3.57%   |
| HP Officejet 4630 series                                  | 1         | 3.57%   |
| HP LaserJet P2015 series                                  | 1         | 3.57%   |
| HP LaserJet 1010                                          | 1         | 3.57%   |
| HP ENVY Photo 6200 series                                 | 1         | 3.57%   |
| HP ENVY 4520 series                                       | 1         | 3.57%   |
| HP Deskjet 2540 series                                    | 1         | 3.57%   |
| Canon SELPHY CP400                                        | 1         | 3.57%   |
| Canon PIXMA MX490 Series                                  | 1         | 3.57%   |
| Canon PIXMA MG3600 Series                                 | 1         | 3.57%   |
| Canon PIXMA MG2500 Series                                 | 1         | 3.57%   |
| Canon MF4360-4390                                         | 1         | 3.57%   |
| Canon LiDE 400                                            | 1         | 3.57%   |
| Canon LiDE 300                                            | 1         | 3.57%   |
| Canon iX6500 series                                       | 1         | 3.57%   |
| Canon iP4800 series                                       | 1         | 3.57%   |
| Brother PT-9500PC                                         | 1         | 3.57%   |
| Brother DCP-L3510CDW                                      | 1         | 3.57%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 5         | 62.5%   |
| Seiko Epson     | 2         | 25%     |
| Hewlett-Packard | 1         | 12.5%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                     | 2         | 25%     |
| Seiko Epson Scanner                         | 1         | 12.5%   |
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1         | 12.5%   |
| HP ScanJet 5300c/5370c                      | 1         | 12.5%   |
| Canon CanoScan LiDE 600F                    | 1         | 12.5%   |
| Canon CanoScan LiDE 220                     | 1         | 12.5%   |
| Canon CanoScan LiDE 200                     | 1         | 12.5%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 774       | 25.53%  |
| Microdia                               | 350       | 11.54%  |
| IMC Networks                           | 265       | 8.74%   |
| Realtek Semiconductor                  | 259       | 8.54%   |
| Sunplus Innovation Technology          | 166       | 5.47%   |
| Cheng Uei Precision Industry (Foxlink) | 123       | 4.06%   |
| Quanta                                 | 119       | 3.92%   |
| Bison Electronics                      | 118       | 3.89%   |
| Suyin                                  | 106       | 3.5%    |
| Acer                                   | 104       | 3.43%   |
| Lite-On Technology                     | 82        | 2.7%    |
| Apple                                  | 76        | 2.51%   |
| Syntek                                 | 64        | 2.11%   |
| Silicon Motion                         | 58        | 1.91%   |
| Alcor Micro                            | 48        | 1.58%   |
| Ricoh                                  | 43        | 1.42%   |
| Logitech                               | 43        | 1.42%   |
| Lenovo                                 | 33        | 1.09%   |
| Luxvisions Innotech Limited            | 28        | 0.92%   |
| Samsung Electronics                    | 18        | 0.59%   |
| Z-Star Microelectronics                | 14        | 0.46%   |
| ALi                                    | 13        | 0.43%   |
| Primax Electronics                     | 12        | 0.4%    |
| Sonix Technology                       | 10        | 0.33%   |
| Microsoft                              | 10        | 0.33%   |
| Importek                               | 6         | 0.2%    |
| Generalplus Technology                 | 6         | 0.2%    |
| DigiTech                               | 6         | 0.2%    |
| SunplusIT                              | 5         | 0.16%   |
| Sunplus Technology                     | 5         | 0.16%   |
| OmniVision Technologies                | 5         | 0.16%   |
| Intel                                  | 5         | 0.16%   |
| Shenzhen Kingcome Optoelectronic       | 4         | 0.13%   |
| ARC International                      | 4         | 0.13%   |
| MacroSilicon                           | 3         | 0.1%    |
| Google                                 | 3         | 0.1%    |
| Genesys Logic                          | 3         | 0.1%    |
| GEMBIRD                                | 3         | 0.1%    |
| Foxconn / Hon Hai                      | 3         | 0.1%    |
| Y Media                                | 2         | 0.07%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 173       | 5.67%   |
| Chicony Integrated Camera                               | 133       | 4.36%   |
| Realtek Integrated_Webcam_HD                            | 86        | 2.82%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 75        | 2.46%   |
| IMC Networks Integrated Camera                          | 71        | 2.33%   |
| Chicony HD Webcam                                       | 68        | 2.23%   |
| Sunplus Integrated_Webcam_HD                            | 56        | 1.84%   |
| Chicony TOSHIBA Web Camera - HD                         | 48        | 1.57%   |
| Chicony USB2.0 Camera                                   | 38        | 1.25%   |
| Microdia Integrated Webcam                              | 37        | 1.21%   |
| Lite-On Integrated Camera                               | 30        | 0.98%   |
| Chicony HP TrueVision HD Camera                         | 29        | 0.95%   |
| Apple Built-in iSight                                   | 29        | 0.95%   |
| Chicony USB 2.0 Camera                                  | 27        | 0.89%   |
| Bison BisonCam,NB Pro                                   | 26        | 0.85%   |
| Chicony HP HD Camera                                    | 25        | 0.82%   |
| Chicony VGA WebCam                                      | 24        | 0.79%   |
| Chicony HP Truevision HD                                | 24        | 0.79%   |
| Bison Integrated Camera                                 | 24        | 0.79%   |
| Realtek USB Camera                                      | 23        | 0.75%   |
| Quanta HD User Facing                                   | 23        | 0.75%   |
| Chicony EasyCamera                                      | 23        | 0.75%   |
| Bison SunplusIT Integrated Camera                       | 23        | 0.75%   |
| Syntek Lenovo EasyCamera                                | 22        | 0.72%   |
| Syntek Integrated Camera                                | 22        | 0.72%   |
| Apple FaceTime HD Camera                                | 22        | 0.72%   |
| Chicony Integrated Camera (1280x720@30)                 | 20        | 0.66%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 19        | 0.62%   |
| Chicony CNF9055 Toshiba Webcam                          | 19        | 0.62%   |
| Alcor Micro SHUNCCM2MP                                  | 19        | 0.62%   |
| Samsung Galaxy series, misc. (MTP mode)                 | 18        | 0.59%   |
| Chicony HP Wide Vision HD Camera                        | 18        | 0.59%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 18        | 0.59%   |
| Suyin HP TrueVision HD                                  | 17        | 0.56%   |
| Lenovo Integrated Webcam [R5U877]                       | 17        | 0.56%   |
| Chicony Lenovo Integrated Camera (0.3MP)                | 17        | 0.56%   |
| Chicony HD User Facing                                  | 17        | 0.56%   |
| Cheng Uei Precision Industry (Foxlink) Webcam           | 17        | 0.56%   |
| Acer Integrated Camera                                  | 17        | 0.56%   |
| Realtek Integrated Webcam HD                            | 16        | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 193       | 32.71%  |
| Synaptics                          | 140       | 23.73%  |
| Shenzhen Goodix Technology         | 99        | 16.78%  |
| Upek                               | 47        | 7.97%   |
| AuthenTec                          | 47        | 7.97%   |
| LighTuning Technology              | 28        | 4.75%   |
| Elan Microelectronics              | 19        | 3.22%   |
| STMicroelectronics                 | 13        | 2.2%    |
| Samsung Electronics                | 2         | 0.34%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.17%   |
| Focal-systems.Corp                 | 1         | 0.17%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 56        | 9.49%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 46        | 7.8%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 41        | 6.95%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 35        | 5.93%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 33        | 5.59%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 23        | 3.9%    |
| Shenzhen Goodix FingerPrint                                                | 23        | 3.9%    |
| Shenzhen Goodix Fingerprint Reader                                         | 20        | 3.39%   |
| Validity Sensors Synaptics WBDI                                            | 19        | 3.22%   |
| Validity Sensors VFS491                                                    | 16        | 2.71%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 15        | 2.54%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 14        | 2.37%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 13        | 2.2%    |
| Synaptics UWP WBDI                                                         | 13        | 2.2%    |
| STMicroelectronics Fingerprint Reader                                      | 13        | 2.2%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 12        | 2.03%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 12        | 2.03%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 12        | 2.03%   |
| Elan ELAN:Fingerprint                                                      | 12        | 2.03%   |
| AuthenTec AES2810                                                          | 11        | 1.86%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 10        | 1.69%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 10        | 1.69%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 10        | 1.69%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 9         | 1.53%   |
| Unknown                                                                    | 9         | 1.53%   |
| Synaptics WBDI Device                                                      | 8         | 1.36%   |
| Synaptics  WBDI                                                            | 8         | 1.36%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 8         | 1.36%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 8         | 1.36%   |
| Elan ELAN:ARM-M4                                                           | 7         | 1.19%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 1.19%   |
| AuthenTec AES1600                                                          | 6         | 1.02%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 5         | 0.85%   |
| Synaptics UWP WBDI Device                                                  | 5         | 0.85%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 5         | 0.85%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 4         | 0.68%   |
| Validity Sensors Fingerprint scanner                                       | 4         | 0.68%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 4         | 0.68%   |
| Synaptics WBDI                                                             | 4         | 0.68%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 4         | 0.68%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 164       | 53.77%  |
| Alcor Micro           | 64        | 20.98%  |
| Upek                  | 24        | 7.87%   |
| Lenovo                | 22        | 7.21%   |
| O2 Micro              | 21        | 6.89%   |
| Gemalto (was Gemplus) | 4         | 1.31%   |
| SCM Microsystems      | 3         | 0.98%   |
| Purism, SPC           | 1         | 0.33%   |
| Clay Logic            | 1         | 0.33%   |
| Chicony Electronics   | 1         | 0.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 67        | 21.97%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 63        | 20.66%  |
| Broadcom 5880                                                                | 41        | 13.44%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 31        | 10.16%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 24        | 7.87%   |
| Broadcom 58200                                                               | 23        | 7.54%   |
| Lenovo Integrated Smart Card Reader                                          | 21        | 6.89%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 16        | 5.25%   |
| O2 Micro Oz776 SmartCard Reader                                              | 5         | 1.64%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.98%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 0.66%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.66%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 0.33%   |
| Purism, SPC Librem Key                                                       | 1         | 0.33%   |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.33%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.33%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.33%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.33%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 2260      | 62.76%  |
| 1     | 1039      | 28.85%  |
| 2     | 257       | 7.14%   |
| 3     | 34        | 0.94%   |
| 4     | 5         | 0.14%   |
| 5     | 3         | 0.08%   |
| 8     | 1         | 0.03%   |
| 7     | 1         | 0.03%   |
| 6     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 573       | 34.56%  |
| Graphics card            | 293       | 17.67%  |
| Chipcard                 | 280       | 16.89%  |
| Net/wireless             | 191       | 11.52%  |
| Multimedia controller    | 86        | 5.19%   |
| Communication controller | 40        | 2.41%   |
| Storage                  | 36        | 2.17%   |
| Bluetooth                | 35        | 2.11%   |
| Camera                   | 31        | 1.87%   |
| Sound                    | 18        | 1.09%   |
| Card reader              | 18        | 1.09%   |
| Net/ethernet             | 16        | 0.97%   |
| Modem                    | 15        | 0.9%    |
| Flash memory             | 8         | 0.48%   |
| Network                  | 7         | 0.42%   |
| Firewire controller      | 4         | 0.24%   |
| Storage/nvme             | 3         | 0.18%   |
| Unassigned class         | 2         | 0.12%   |
| Storage/ide              | 2         | 0.12%   |

