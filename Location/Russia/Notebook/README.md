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

Total: 19951

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | EliteBook 8460p             | [cc6b66c576](https://linux-hardware.org/?probe=cc6b66c576) | Nov 06, 2023 |
| Aquarius      | NS585                       | [ddc8256647](https://linux-hardware.org/?probe=ddc8256647) | Nov 06, 2023 |
| Aquarius      | NS585                       | [2f4e49837d](https://linux-hardware.org/?probe=2f4e49837d) | Nov 06, 2023 |
| HP            | Laptop 15s-eq2xxx           | [b63a038c08](https://linux-hardware.org/?probe=b63a038c08) | Nov 06, 2023 |
| Aquarius      | NS585                       | [4fea63336a](https://linux-hardware.org/?probe=4fea63336a) | Nov 06, 2023 |
| HP            | Laptop 15-bw0xx             | [bd3e108e8a](https://linux-hardware.org/?probe=bd3e108e8a) | Nov 06, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [60ec029256](https://linux-hardware.org/?probe=60ec029256) | Nov 05, 2023 |
| ASUSTek       | X550WA                      | [8c15da796b](https://linux-hardware.org/?probe=8c15da796b) | Nov 05, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [cff5d02cde](https://linux-hardware.org/?probe=cff5d02cde) | Nov 05, 2023 |
| HP            | ProBook 440 G7              | [1d1311204e](https://linux-hardware.org/?probe=1d1311204e) | Nov 05, 2023 |
| HP            | ProBook 6545b               | [a81427fffa](https://linux-hardware.org/?probe=a81427fffa) | Nov 05, 2023 |
| HP            | Laptop 17t-by000            | [b23b606118](https://linux-hardware.org/?probe=b23b606118) | Nov 05, 2023 |
| Acer          | Aspire 5349                 | [b1ca6f597c](https://linux-hardware.org/?probe=b1ca6f597c) | Nov 05, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [f782cf5541](https://linux-hardware.org/?probe=f782cf5541) | Nov 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [a3a6205085](https://linux-hardware.org/?probe=a3a6205085) | Nov 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [1d56b84bdd](https://linux-hardware.org/?probe=1d56b84bdd) | Nov 05, 2023 |
| Acer          | Aspire E1-571G              | [fac63c4d5c](https://linux-hardware.org/?probe=fac63c4d5c) | Nov 05, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [5541e01522](https://linux-hardware.org/?probe=5541e01522) | Nov 05, 2023 |
| Acer          | Aspire 5100                 | [62b63704e9](https://linux-hardware.org/?probe=62b63704e9) | Nov 04, 2023 |
| Acer          | Aspire 5100                 | [c4d628cb50](https://linux-hardware.org/?probe=c4d628cb50) | Nov 04, 2023 |
| Acer          | TravelMate B118-M           | [051346666e](https://linux-hardware.org/?probe=051346666e) | Nov 04, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [2084300c18](https://linux-hardware.org/?probe=2084300c18) | Nov 04, 2023 |
| Acer          | Aspire E5-573G              | [c74051abb7](https://linux-hardware.org/?probe=c74051abb7) | Nov 04, 2023 |
| Acer          | TravelMate P215-54          | [5688b7940d](https://linux-hardware.org/?probe=5688b7940d) | Nov 04, 2023 |
| HP            | Laptop 15s-eq2xxx           | [6fcd2a768b](https://linux-hardware.org/?probe=6fcd2a768b) | Nov 04, 2023 |
| MSI           | Bravo 15 C7VE               | [5db0e7314a](https://linux-hardware.org/?probe=5db0e7314a) | Nov 04, 2023 |
| Acer          | TravelMate P215-54          | [f051dc617c](https://linux-hardware.org/?probe=f051dc617c) | Nov 04, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [157f4d1006](https://linux-hardware.org/?probe=157f4d1006) | Nov 04, 2023 |
| Dell          | Inspiron M5110              | [20e338fb21](https://linux-hardware.org/?probe=20e338fb21) | Nov 04, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [86d2394935](https://linux-hardware.org/?probe=86d2394935) | Nov 03, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [85a38e7906](https://linux-hardware.org/?probe=85a38e7906) | Nov 03, 2023 |
| Unknown       | Unknown                     | [d27cd12013](https://linux-hardware.org/?probe=d27cd12013) | Nov 03, 2023 |
| DEXP          | Aquilon C14                 | [b91d7803a2](https://linux-hardware.org/?probe=b91d7803a2) | Nov 03, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [ded1d73643](https://linux-hardware.org/?probe=ded1d73643) | Nov 03, 2023 |
| Timi          | A35S                        | [d62fbb6f83](https://linux-hardware.org/?probe=d62fbb6f83) | Nov 03, 2023 |
| HONOR         | NMH-WDX9                    | [11e32e2482](https://linux-hardware.org/?probe=11e32e2482) | Nov 03, 2023 |
| HUAWEI        | BOM-WXX9                    | [bc3b3daf33](https://linux-hardware.org/?probe=bc3b3daf33) | Nov 03, 2023 |
| Apple         | MacBookAir7,1               | [50cb167f37](https://linux-hardware.org/?probe=50cb167f37) | Nov 03, 2023 |
| Lenovo        | G580                        | [d137c3bc30](https://linux-hardware.org/?probe=d137c3bc30) | Nov 02, 2023 |
| HP            | Laptop 15-bw0xx             | [589f0a0dfb](https://linux-hardware.org/?probe=589f0a0dfb) | Nov 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | [f1b74562ae](https://linux-hardware.org/?probe=f1b74562ae) | Nov 02, 2023 |
| KVADRA        | U15W                        | [1c1f562cf5](https://linux-hardware.org/?probe=1c1f562cf5) | Nov 02, 2023 |
| Digma         | Pro Fortis M DN15P5-8CXN... | [7bb9e8e743](https://linux-hardware.org/?probe=7bb9e8e743) | Nov 02, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [10b531fcd1](https://linux-hardware.org/?probe=10b531fcd1) | Nov 02, 2023 |
| Acer          | TravelMate P259-MG          | [ba3faece8c](https://linux-hardware.org/?probe=ba3faece8c) | Nov 01, 2023 |
| HP            | Laptop 15s-eq1xxx           | [075049b538](https://linux-hardware.org/?probe=075049b538) | Nov 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | [0a7341e5e0](https://linux-hardware.org/?probe=0a7341e5e0) | Nov 01, 2023 |
| ASUSTek       | X553SA                      | [0eba32de41](https://linux-hardware.org/?probe=0eba32de41) | Nov 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [a2a8295797](https://linux-hardware.org/?probe=a2a8295797) | Nov 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [0d49a75fe1](https://linux-hardware.org/?probe=0d49a75fe1) | Nov 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [cbe947aefc](https://linux-hardware.org/?probe=cbe947aefc) | Nov 01, 2023 |
| Samsung       | P29/28/26                   | [15d449da5d](https://linux-hardware.org/?probe=15d449da5d) | Nov 01, 2023 |
| Dell          | Precision M4700             | [ab52e67d9d](https://linux-hardware.org/?probe=ab52e67d9d) | Nov 01, 2023 |
| ANCOMP        | Learnmate A15-501           | [da0c777960](https://linux-hardware.org/?probe=da0c777960) | Nov 01, 2023 |
| Dell          | G15 5510                    | [60ea93226d](https://linux-hardware.org/?probe=60ea93226d) | Nov 01, 2023 |
| MSI           | Prestige 14Evo A12M         | [98e32e98bf](https://linux-hardware.org/?probe=98e32e98bf) | Oct 31, 2023 |
| Dell          | Inspiron N5050              | [2ec8097b67](https://linux-hardware.org/?probe=2ec8097b67) | Oct 31, 2023 |
| Lenovo        | Legion Pro 7 16IRX8 82WR    | [f6929f0d98](https://linux-hardware.org/?probe=f6929f0d98) | Oct 31, 2023 |
| HONOR         | BMH-WDX9                    | [a1962fef8a](https://linux-hardware.org/?probe=a1962fef8a) | Oct 31, 2023 |
| Acer          | Extensa 215-22              | [5fd05270e7](https://linux-hardware.org/?probe=5fd05270e7) | Oct 31, 2023 |
| Lenovo        | Legion Pro 7 16IRX8 82WR    | [794c56fb64](https://linux-hardware.org/?probe=794c56fb64) | Oct 31, 2023 |
| Lenovo        | ThinkPad X260 VB6R77903H    | [c4baf8a67b](https://linux-hardware.org/?probe=c4baf8a67b) | Oct 30, 2023 |
| Dell          | Latitude 7320               | [efc40122bf](https://linux-hardware.org/?probe=efc40122bf) | Oct 30, 2023 |
| THUNDEROBO... | 911AirD                     | [698adeeba7](https://linux-hardware.org/?probe=698adeeba7) | Oct 30, 2023 |
| Apple         | MacBookAir6,2               | [b1a709477b](https://linux-hardware.org/?probe=b1a709477b) | Oct 30, 2023 |
| TECNO         | MEGABOOK T1                 | [2bab6515f4](https://linux-hardware.org/?probe=2bab6515f4) | Oct 30, 2023 |
| Valve         | Jupiter                     | [7eda72383a](https://linux-hardware.org/?probe=7eda72383a) | Oct 30, 2023 |
| Acer          | Extensa 2520G               | [bcc4e567f3](https://linux-hardware.org/?probe=bcc4e567f3) | Oct 30, 2023 |
| ASUSTek       | N61Vn                       | [d8ee34cdbc](https://linux-hardware.org/?probe=d8ee34cdbc) | Oct 30, 2023 |
| Sony          | SVE1511B1RB                 | [74651497a9](https://linux-hardware.org/?probe=74651497a9) | Oct 30, 2023 |
| Apple         | MacBookAir6,2               | [afd23e164c](https://linux-hardware.org/?probe=afd23e164c) | Oct 30, 2023 |
| HP            | Laptop 15-dy2xxx            | [f39cf8f2f8](https://linux-hardware.org/?probe=f39cf8f2f8) | Oct 30, 2023 |
| ASUSTek       | N53SV                       | [8d853d0cb4](https://linux-hardware.org/?probe=8d853d0cb4) | Oct 30, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [de3f77c938](https://linux-hardware.org/?probe=de3f77c938) | Oct 30, 2023 |
| ASUSTek       | X540YA                      | [082e5b7e0b](https://linux-hardware.org/?probe=082e5b7e0b) | Oct 29, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [8ddd5fdfba](https://linux-hardware.org/?probe=8ddd5fdfba) | Oct 29, 2023 |
| HUAWEI        | BOM-WXX9                    | [3a547e1959](https://linux-hardware.org/?probe=3a547e1959) | Oct 29, 2023 |
| eMachines     | Rhine V1.45                 | [dc1b87d14a](https://linux-hardware.org/?probe=dc1b87d14a) | Oct 29, 2023 |
| ASUSTek       | K84L                        | [e6d103b3e4](https://linux-hardware.org/?probe=e6d103b3e4) | Oct 29, 2023 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | [300d56f39e](https://linux-hardware.org/?probe=300d56f39e) | Oct 29, 2023 |
| Acer          | Extensa 5220                | [d9fbe1bc8a](https://linux-hardware.org/?probe=d9fbe1bc8a) | Oct 29, 2023 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | [29a362f501](https://linux-hardware.org/?probe=29a362f501) | Oct 29, 2023 |
| Clevo         | W150HRM                     | [ef386d81b5](https://linux-hardware.org/?probe=ef386d81b5) | Oct 29, 2023 |
| HP            | Pavilion Notebook           | [c76c1fe34a](https://linux-hardware.org/?probe=c76c1fe34a) | Oct 29, 2023 |
| Lenovo        | G780                        | [ffb91c2552](https://linux-hardware.org/?probe=ffb91c2552) | Oct 29, 2023 |
| Lenovo        | G780                        | [86a631f874](https://linux-hardware.org/?probe=86a631f874) | Oct 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [a123ac023f](https://linux-hardware.org/?probe=a123ac023f) | Oct 29, 2023 |
| Valve         | Jupiter                     | [935baa5e6a](https://linux-hardware.org/?probe=935baa5e6a) | Oct 29, 2023 |
| HUAWEI        | BOM-WXX9                    | [57c7ce8322](https://linux-hardware.org/?probe=57c7ce8322) | Oct 28, 2023 |
| Toshiba       | Satellite L755              | [6f0566d95a](https://linux-hardware.org/?probe=6f0566d95a) | Oct 28, 2023 |
| HP            | Laptop 15-bw0xx             | [63c6987bfa](https://linux-hardware.org/?probe=63c6987bfa) | Oct 28, 2023 |
| Maibenben     | MaiBook X series            | [63e0cb487a](https://linux-hardware.org/?probe=63e0cb487a) | Oct 28, 2023 |
| HP            | Pavilion dv6                | [cb8ef15ece](https://linux-hardware.org/?probe=cb8ef15ece) | Oct 28, 2023 |
| HP            | Pavilion dv6                | [88a3365d2c](https://linux-hardware.org/?probe=88a3365d2c) | Oct 28, 2023 |
| ICL           | RAYbook Si1512              | [a17fa22636](https://linux-hardware.org/?probe=a17fa22636) | Oct 28, 2023 |
| HUAWEI        | CREM-WXX9                   | [217aaa00da](https://linux-hardware.org/?probe=217aaa00da) | Oct 28, 2023 |
| Sony          | VPCEB1S1R                   | [bb50d8e6f3](https://linux-hardware.org/?probe=bb50d8e6f3) | Oct 28, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [9c28038bcb](https://linux-hardware.org/?probe=9c28038bcb) | Oct 28, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [f7556d51ff](https://linux-hardware.org/?probe=f7556d51ff) | Oct 28, 2023 |
| HONOR         | BOD-WXX9                    | [6de8b3afda](https://linux-hardware.org/?probe=6de8b3afda) | Oct 27, 2023 |
| ASUSTek       | X75VC                       | [be944959dc](https://linux-hardware.org/?probe=be944959dc) | Oct 27, 2023 |
| HP            | Laptop 15s-fq5xxx           | [72d2f9d210](https://linux-hardware.org/?probe=72d2f9d210) | Oct 27, 2023 |
| HP            | Notebook                    | [efb9814479](https://linux-hardware.org/?probe=efb9814479) | Oct 27, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [67b966e75c](https://linux-hardware.org/?probe=67b966e75c) | Oct 27, 2023 |
| ASUSTek       | N56VZ                       | [bfe478311d](https://linux-hardware.org/?probe=bfe478311d) | Oct 26, 2023 |
| Acer          | Nitro AN515-57              | [3b669afc38](https://linux-hardware.org/?probe=3b669afc38) | Oct 26, 2023 |
| HP            | Laptop 14s-fq1xxx           | [e8158c3275](https://linux-hardware.org/?probe=e8158c3275) | Oct 26, 2023 |
| HP            | Laptop 14s-fq1xxx           | [ae3bbe4ecf](https://linux-hardware.org/?probe=ae3bbe4ecf) | Oct 26, 2023 |
| Unknown       | Unknown                     | [d246d98312](https://linux-hardware.org/?probe=d246d98312) | Oct 26, 2023 |
| Valve         | Jupiter                     | [8eebce7a7b](https://linux-hardware.org/?probe=8eebce7a7b) | Oct 26, 2023 |
| Unknown       | X133                        | [c653721c37](https://linux-hardware.org/?probe=c653721c37) | Oct 26, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [47e99a1356](https://linux-hardware.org/?probe=47e99a1356) | Oct 26, 2023 |
| Maibenben     | MaiBook M                   | [ccee3b60c7](https://linux-hardware.org/?probe=ccee3b60c7) | Oct 26, 2023 |
| HP            | ProBook 4730s               | [935df70e31](https://linux-hardware.org/?probe=935df70e31) | Oct 26, 2023 |
| Toshiba       | Satellite C660D             | [8dc1c1d768](https://linux-hardware.org/?probe=8dc1c1d768) | Oct 26, 2023 |
| ANCOMP        | Learnmate A15-501           | [832eeb008b](https://linux-hardware.org/?probe=832eeb008b) | Oct 26, 2023 |
| HP            | 650                         | [0625bd022d](https://linux-hardware.org/?probe=0625bd022d) | Oct 26, 2023 |
| Sony          | VGN-SR19VRN                 | [b6137146d6](https://linux-hardware.org/?probe=b6137146d6) | Oct 26, 2023 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [cc3370083d](https://linux-hardware.org/?probe=cc3370083d) | Oct 26, 2023 |
| HP            | Pavilion dv6700             | [4e65db3924](https://linux-hardware.org/?probe=4e65db3924) | Oct 26, 2023 |
| HP            | Pavilion g7                 | [5f67a1eab5](https://linux-hardware.org/?probe=5f67a1eab5) | Oct 26, 2023 |
| ASUSTek       | G56JR                       | [9dd84ffe04](https://linux-hardware.org/?probe=9dd84ffe04) | Oct 26, 2023 |
| HP            | Pavilion g7                 | [4699d107df](https://linux-hardware.org/?probe=4699d107df) | Oct 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [a17a8b4360](https://linux-hardware.org/?probe=a17a8b4360) | Oct 25, 2023 |
| HUAWEI        | NBD-WXX9                    | [4eb93d233a](https://linux-hardware.org/?probe=4eb93d233a) | Oct 25, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [c09c90cd1f](https://linux-hardware.org/?probe=c09c90cd1f) | Oct 25, 2023 |
| Acer          | Aspire 7520                 | [e5636cc92b](https://linux-hardware.org/?probe=e5636cc92b) | Oct 25, 2023 |
| eMachines     | Rhine V1.45                 | [7b3fd7da03](https://linux-hardware.org/?probe=7b3fd7da03) | Oct 25, 2023 |
| Samsung       | R780                        | [c54b18ab4a](https://linux-hardware.org/?probe=c54b18ab4a) | Oct 25, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | [556cd62b51](https://linux-hardware.org/?probe=556cd62b51) | Oct 25, 2023 |
| Acer          | Ferrari 3200                | [52f9e06bf9](https://linux-hardware.org/?probe=52f9e06bf9) | Oct 25, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | [c764389042](https://linux-hardware.org/?probe=c764389042) | Oct 25, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [f8f7f85d08](https://linux-hardware.org/?probe=f8f7f85d08) | Oct 25, 2023 |
| Maibenben     | MaiBook P series            | [227638ee70](https://linux-hardware.org/?probe=227638ee70) | Oct 25, 2023 |
| Acer          | Extensa 2520G               | [d0e546f6d6](https://linux-hardware.org/?probe=d0e546f6d6) | Oct 25, 2023 |
| Acer          | Aspire 5541                 | [df4f0f3912](https://linux-hardware.org/?probe=df4f0f3912) | Oct 25, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [51e187d4e6](https://linux-hardware.org/?probe=51e187d4e6) | Oct 25, 2023 |
| Acer          | Aspire 7750G                | [673c675bc6](https://linux-hardware.org/?probe=673c675bc6) | Oct 25, 2023 |
| Lenovo        | V580c 20160                 | [178fe3a497](https://linux-hardware.org/?probe=178fe3a497) | Oct 25, 2023 |
| Lenovo        | Unknown                     | [1139846802](https://linux-hardware.org/?probe=1139846802) | Oct 25, 2023 |
| HONOR         | NMH-WDX9                    | [3a0782c335](https://linux-hardware.org/?probe=3a0782c335) | Oct 25, 2023 |
| Acer          | Extensa 2520G               | [1b58a52442](https://linux-hardware.org/?probe=1b58a52442) | Oct 25, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [118822d39f](https://linux-hardware.org/?probe=118822d39f) | Oct 25, 2023 |
| MSI           | Katana GF76 11SC            | [b1a5449e72](https://linux-hardware.org/?probe=b1a5449e72) | Oct 25, 2023 |
| HP            | Pavilion dv6700             | [5e143a92d1](https://linux-hardware.org/?probe=5e143a92d1) | Oct 25, 2023 |
| HP            | Pavilion dv6                | [d8a8dfefd7](https://linux-hardware.org/?probe=d8a8dfefd7) | Oct 24, 2023 |
| HP            | EliteBook 845 14 inch G1... | [ba2a49fbef](https://linux-hardware.org/?probe=ba2a49fbef) | Oct 24, 2023 |
| Irbis         | NB264                       | [ac65f72c50](https://linux-hardware.org/?probe=ac65f72c50) | Oct 24, 2023 |
| ASUSTek       | X75VC                       | [9e53bba398](https://linux-hardware.org/?probe=9e53bba398) | Oct 24, 2023 |
| Lenovo        | ThinkPad L520 5017BK4       | [77037e51b0](https://linux-hardware.org/?probe=77037e51b0) | Oct 24, 2023 |
| Dell          | Precision M4700             | [4d590a378f](https://linux-hardware.org/?probe=4d590a378f) | Oct 24, 2023 |
| Apple         | MacBookPro14,3              | [b706665251](https://linux-hardware.org/?probe=b706665251) | Oct 23, 2023 |
| ASUSTek       | ROG Strix G533QM_G533QM     | [a4c0d7be24](https://linux-hardware.org/?probe=a4c0d7be24) | Oct 23, 2023 |
| Packard Be... | EasyNote ENLG81BA           | [a9cb75e4fa](https://linux-hardware.org/?probe=a9cb75e4fa) | Oct 23, 2023 |
| Lenovo        | G500 20236                  | [3effd4e3d3](https://linux-hardware.org/?probe=3effd4e3d3) | Oct 23, 2023 |
| ASUSTek       | N73SV                       | [6be1f80f91](https://linux-hardware.org/?probe=6be1f80f91) | Oct 23, 2023 |
| Intel Clie... | LAPAC71H                    | [257d890bfb](https://linux-hardware.org/?probe=257d890bfb) | Oct 23, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [41dfd82cb6](https://linux-hardware.org/?probe=41dfd82cb6) | Oct 23, 2023 |
| ASUSTek       | UX310UAK                    | [96f3614a9c](https://linux-hardware.org/?probe=96f3614a9c) | Oct 23, 2023 |
| Acer          | Aspire 5734Z                | [cf4468ed0d](https://linux-hardware.org/?probe=cf4468ed0d) | Oct 23, 2023 |
| Aquarius      | NS585                       | [3c793ad14b](https://linux-hardware.org/?probe=3c793ad14b) | Oct 23, 2023 |
| Aquarius      | NS585                       | [9e7366fb3a](https://linux-hardware.org/?probe=9e7366fb3a) | Oct 23, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [c2450de2bb](https://linux-hardware.org/?probe=c2450de2bb) | Oct 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [06d21bfdb4](https://linux-hardware.org/?probe=06d21bfdb4) | Oct 23, 2023 |
| Lenovo        | ThinkPad L13 20R30005RT     | [23a9651432](https://linux-hardware.org/?probe=23a9651432) | Oct 22, 2023 |
| Samsung       | N100                        | [449f1837f5](https://linux-hardware.org/?probe=449f1837f5) | Oct 22, 2023 |
| Sony          | VGN-NS11ER_S                | [ece59481cb](https://linux-hardware.org/?probe=ece59481cb) | Oct 22, 2023 |
| HP            | Pavilion dv6                | [71c2062cbf](https://linux-hardware.org/?probe=71c2062cbf) | Oct 22, 2023 |
| Lenovo        | G50-30 80G0                 | [2a00efe761](https://linux-hardware.org/?probe=2a00efe761) | Oct 22, 2023 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [2ee834d08a](https://linux-hardware.org/?probe=2ee834d08a) | Oct 22, 2023 |
| HUAWEI        | BOD-WXX9                    | [102c170156](https://linux-hardware.org/?probe=102c170156) | Oct 22, 2023 |
| Unknown       | Unknown                     | [1e239308b1](https://linux-hardware.org/?probe=1e239308b1) | Oct 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [d1026594ae](https://linux-hardware.org/?probe=d1026594ae) | Oct 21, 2023 |
| Unknown       | Unknown                     | [125d0eedc8](https://linux-hardware.org/?probe=125d0eedc8) | Oct 21, 2023 |
| Valve         | Jupiter                     | [d93782448d](https://linux-hardware.org/?probe=d93782448d) | Oct 21, 2023 |
| Unknown       | X133                        | [a9f1936d1e](https://linux-hardware.org/?probe=a9f1936d1e) | Oct 21, 2023 |
| HP            | Notebook                    | [3bf9870d4a](https://linux-hardware.org/?probe=3bf9870d4a) | Oct 21, 2023 |
| Samsung       | N100                        | [80cf7b4a53](https://linux-hardware.org/?probe=80cf7b4a53) | Oct 21, 2023 |
| HP            | Laptop 15s-fq5xxx           | [9610ec84cb](https://linux-hardware.org/?probe=9610ec84cb) | Oct 21, 2023 |
| Acer          | Ferrari 3200                | [01ef021946](https://linux-hardware.org/?probe=01ef021946) | Oct 21, 2023 |
| Lenovo        | ThinkPad T470 20HES06G00    | [334419d1b5](https://linux-hardware.org/?probe=334419d1b5) | Oct 21, 2023 |
| Getac         | S410                        | [7bfd9704f3](https://linux-hardware.org/?probe=7bfd9704f3) | Oct 21, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [5e57624ceb](https://linux-hardware.org/?probe=5e57624ceb) | Oct 21, 2023 |
| Valve         | Jupiter                     | [69762a50c8](https://linux-hardware.org/?probe=69762a50c8) | Oct 21, 2023 |
| Packard Be... | EasyNote TE11HC             | [dc33bae348](https://linux-hardware.org/?probe=dc33bae348) | Oct 21, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [f30ccc13f5](https://linux-hardware.org/?probe=f30ccc13f5) | Oct 21, 2023 |
| realme        | RMNBXXXX                    | [cd819e512d](https://linux-hardware.org/?probe=cd819e512d) | Oct 20, 2023 |
| realme        | RMNBXXXX                    | [7cff25c875](https://linux-hardware.org/?probe=7cff25c875) | Oct 20, 2023 |
| HUAWEI        | HKD-WXX                     | [73735cfb57](https://linux-hardware.org/?probe=73735cfb57) | Oct 20, 2023 |
| Lenovo        | V15-IIL 82C5                | [50f6d4cb01](https://linux-hardware.org/?probe=50f6d4cb01) | Oct 20, 2023 |
| MACHENIKE     | MACHCREATOR-16              | [91f29a5a63](https://linux-hardware.org/?probe=91f29a5a63) | Oct 20, 2023 |
| Dell          | Vostro 14 5410              | [4cb4e5aab9](https://linux-hardware.org/?probe=4cb4e5aab9) | Oct 20, 2023 |
| Lenovo        | G505s 20255                 | [71bfa98c37](https://linux-hardware.org/?probe=71bfa98c37) | Oct 20, 2023 |
| HP            | Notebook                    | [4d0eddbb92](https://linux-hardware.org/?probe=4d0eddbb92) | Oct 20, 2023 |
| Jumper        | Ezbook X3                   | [54ebd459be](https://linux-hardware.org/?probe=54ebd459be) | Oct 20, 2023 |
| Acer          | Aspire E5-523G              | [12b93b3f48](https://linux-hardware.org/?probe=12b93b3f48) | Oct 20, 2023 |
| ASUSTek       | F3JA                        | [6a96b7e347](https://linux-hardware.org/?probe=6a96b7e347) | Oct 20, 2023 |
| Chuwi         | GemiBook XPro               | [2a34fef14c](https://linux-hardware.org/?probe=2a34fef14c) | Oct 19, 2023 |
| Chuwi         | GemiBook XPro               | [6526948818](https://linux-hardware.org/?probe=6526948818) | Oct 19, 2023 |
| Lenovo        | ThinkPad T60 1952W2Q        | [4493954de6](https://linux-hardware.org/?probe=4493954de6) | Oct 19, 2023 |
| TECNO         | MEGABOOK T1                 | [c6b98c8602](https://linux-hardware.org/?probe=c6b98c8602) | Oct 19, 2023 |
| Acer          | AOD270                      | [b8c4966af7](https://linux-hardware.org/?probe=b8c4966af7) | Oct 19, 2023 |
| realme        | RMNBXXXX                    | [55266c03b1](https://linux-hardware.org/?probe=55266c03b1) | Oct 19, 2023 |
| Lenovo        | IdeaPad Y550P 20035         | [899b4e9638](https://linux-hardware.org/?probe=899b4e9638) | Oct 19, 2023 |
| Dell          | Inspiron 15-3565            | [d60190dd5f](https://linux-hardware.org/?probe=d60190dd5f) | Oct 19, 2023 |
| Acer          | Aspire E5-523G              | [240879310d](https://linux-hardware.org/?probe=240879310d) | Oct 19, 2023 |
| Dell          | Inspiron 5558               | [5a4436b191](https://linux-hardware.org/?probe=5a4436b191) | Oct 19, 2023 |
| Acer          | Aspire A315-34              | [1ec00092e6](https://linux-hardware.org/?probe=1ec00092e6) | Oct 19, 2023 |
| Lenovo        | Legion R7000P APH8 82Y9     | [cd80438b02](https://linux-hardware.org/?probe=cd80438b02) | Oct 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [94cd063a64](https://linux-hardware.org/?probe=94cd063a64) | Oct 19, 2023 |
| HP            | 255 G4                      | [0290beac3f](https://linux-hardware.org/?probe=0290beac3f) | Oct 19, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [81bfadb2d9](https://linux-hardware.org/?probe=81bfadb2d9) | Oct 18, 2023 |
| Acer          | TravelMate 4150             | [26bf6dbfcf](https://linux-hardware.org/?probe=26bf6dbfcf) | Oct 18, 2023 |
| Acer          | Aspire 5742G                | [75801ac8e5](https://linux-hardware.org/?probe=75801ac8e5) | Oct 18, 2023 |
| Lenovo        | Legion R7000P APH8 82Y9     | [9c6fb34bab](https://linux-hardware.org/?probe=9c6fb34bab) | Oct 18, 2023 |
| Timi          | Redmi Book Pro 14 2022      | [1984a8305d](https://linux-hardware.org/?probe=1984a8305d) | Oct 18, 2023 |
| HONOR         | HYM-WXX                     | [84da562e08](https://linux-hardware.org/?probe=84da562e08) | Oct 18, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [c3a168bb6e](https://linux-hardware.org/?probe=c3a168bb6e) | Oct 18, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [1054b32ffc](https://linux-hardware.org/?probe=1054b32ffc) | Oct 18, 2023 |
| MSI           | Modern 14 C12M              | [fd48069806](https://linux-hardware.org/?probe=fd48069806) | Oct 18, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | [2079534fd9](https://linux-hardware.org/?probe=2079534fd9) | Oct 18, 2023 |
| Maibenben     | Perfectum Series            | [be169368b9](https://linux-hardware.org/?probe=be169368b9) | Oct 18, 2023 |
| Toshiba       | Satellite A200              | [afc5127b45](https://linux-hardware.org/?probe=afc5127b45) | Oct 18, 2023 |
| ASUSTek       | K53SC                       | [5e5a88b3e2](https://linux-hardware.org/?probe=5e5a88b3e2) | Oct 18, 2023 |
| HUAWEI        | BOD-WXX9                    | [b6bc7ed678](https://linux-hardware.org/?probe=b6bc7ed678) | Oct 17, 2023 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | [4d69a046ff](https://linux-hardware.org/?probe=4d69a046ff) | Oct 17, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | [0f6a579d4f](https://linux-hardware.org/?probe=0f6a579d4f) | Oct 17, 2023 |
| Lenovo        | ThinkPad T510 43142PU       | [84b97792e2](https://linux-hardware.org/?probe=84b97792e2) | Oct 17, 2023 |
| Acer          | Nitro AN515-57              | [2651ff0eba](https://linux-hardware.org/?probe=2651ff0eba) | Oct 17, 2023 |
| Chuwi         | CoreBook XPro               | [02ab9e7a40](https://linux-hardware.org/?probe=02ab9e7a40) | Oct 17, 2023 |
| MSI           | Modern 14 C12M              | [35fe973fad](https://linux-hardware.org/?probe=35fe973fad) | Oct 17, 2023 |
| HUAWEI        | RLEF-XX                     | [4a5c5417b7](https://linux-hardware.org/?probe=4a5c5417b7) | Oct 17, 2023 |
| Clevo         | NL41MU2                     | [001109b89b](https://linux-hardware.org/?probe=001109b89b) | Oct 17, 2023 |
| Clevo         | NL41MU2                     | [da3768d9f4](https://linux-hardware.org/?probe=da3768d9f4) | Oct 17, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [6f1f662d3a](https://linux-hardware.org/?probe=6f1f662d3a) | Oct 17, 2023 |
| MSI           | GT62VR 7RE                  | [612f43c2ae](https://linux-hardware.org/?probe=612f43c2ae) | Oct 17, 2023 |
| Valve         | Jupiter                     | [54604c764b](https://linux-hardware.org/?probe=54604c764b) | Oct 16, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | [322171fcdd](https://linux-hardware.org/?probe=322171fcdd) | Oct 16, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [3c327fc90c](https://linux-hardware.org/?probe=3c327fc90c) | Oct 16, 2023 |
| MSI           | VR610                       | [3cac0bd8c9](https://linux-hardware.org/?probe=3cac0bd8c9) | Oct 16, 2023 |
| Fujitsu Si... | AMILO Pro Edition V3405     | [ba0ead0d37](https://linux-hardware.org/?probe=ba0ead0d37) | Oct 16, 2023 |
| Apple         | MacBookPro8,1               | [abfce57204](https://linux-hardware.org/?probe=abfce57204) | Oct 16, 2023 |
| HUAWEI        | HVY-WXX9                    | [57e0cf4149](https://linux-hardware.org/?probe=57e0cf4149) | Oct 16, 2023 |
| Dell          | Vostro 14 5410              | [219d504a89](https://linux-hardware.org/?probe=219d504a89) | Oct 16, 2023 |
| Clevo         | NL41MU2                     | [9e4818431f](https://linux-hardware.org/?probe=9e4818431f) | Oct 16, 2023 |
| Dell          | Latitude E5470              | [0c6b7d2953](https://linux-hardware.org/?probe=0c6b7d2953) | Oct 16, 2023 |
| HP            | EliteBook 845 14 inch G1... | [5ee2d06317](https://linux-hardware.org/?probe=5ee2d06317) | Oct 15, 2023 |
| HUAWEI        | BOM-WXX9                    | [ea047f0b15](https://linux-hardware.org/?probe=ea047f0b15) | Oct 15, 2023 |
| MSI           | Prestige 14Evo A12M         | [9bcdff9506](https://linux-hardware.org/?probe=9bcdff9506) | Oct 15, 2023 |
| HP            | Victus by Gaming Laptop ... | [6570860ebd](https://linux-hardware.org/?probe=6570860ebd) | Oct 15, 2023 |
| HONOR         | HYM-WXX                     | [eaff1b458a](https://linux-hardware.org/?probe=eaff1b458a) | Oct 15, 2023 |
| ASUSTek       | N56VV                       | [657664de04](https://linux-hardware.org/?probe=657664de04) | Oct 15, 2023 |
| Acer          | TravelMate B118-M           | [0d185effc4](https://linux-hardware.org/?probe=0d185effc4) | Oct 15, 2023 |
| eMachines     | Rhine V1.43                 | [1ec836f915](https://linux-hardware.org/?probe=1ec836f915) | Oct 15, 2023 |
| MSI           | Katana GF76 12UC            | [28c2984d39](https://linux-hardware.org/?probe=28c2984d39) | Oct 15, 2023 |
| Dell          | Inspiron 3576               | [28b33e764d](https://linux-hardware.org/?probe=28b33e764d) | Oct 15, 2023 |
| HP            | Laptop 15-ra0xx             | [7d7ff23b31](https://linux-hardware.org/?probe=7d7ff23b31) | Oct 15, 2023 |
| HP            | ProBook 4535s               | [0eb08faa29](https://linux-hardware.org/?probe=0eb08faa29) | Oct 15, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [60cf13a0ce](https://linux-hardware.org/?probe=60cf13a0ce) | Oct 15, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [5aac34fb6e](https://linux-hardware.org/?probe=5aac34fb6e) | Oct 15, 2023 |
| ASUSTek       | F3Sr                        | [b7568466f9](https://linux-hardware.org/?probe=b7568466f9) | Oct 14, 2023 |
| Unknown       | Unknown                     | [02fda3f9f3](https://linux-hardware.org/?probe=02fda3f9f3) | Oct 14, 2023 |
| Unknown       | Unknown                     | [8448bccd6f](https://linux-hardware.org/?probe=8448bccd6f) | Oct 14, 2023 |
| Apple         | MacBook8,1                  | [edb8f551bf](https://linux-hardware.org/?probe=edb8f551bf) | Oct 14, 2023 |
| ASUSTek       | F50GX                       | [4665f359b9](https://linux-hardware.org/?probe=4665f359b9) | Oct 14, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [ab093317ba](https://linux-hardware.org/?probe=ab093317ba) | Oct 14, 2023 |
| Maibenben     | MaiBook X series            | [901cc6bd8a](https://linux-hardware.org/?probe=901cc6bd8a) | Oct 14, 2023 |
| HP            | Notebook                    | [20fd24630c](https://linux-hardware.org/?probe=20fd24630c) | Oct 14, 2023 |
| Dell          | Latitude 7390               | [12de4c5026](https://linux-hardware.org/?probe=12de4c5026) | Oct 14, 2023 |
| HP            | Laptop 15s-eq2xxx           | [50698ed07c](https://linux-hardware.org/?probe=50698ed07c) | Oct 14, 2023 |
| Apple         | MacBook8,1                  | [1a8e527488](https://linux-hardware.org/?probe=1a8e527488) | Oct 13, 2023 |
| Valve         | Jupiter                     | [594ab95469](https://linux-hardware.org/?probe=594ab95469) | Oct 13, 2023 |
| Acer          | Aspire A515-52G             | [e347245de9](https://linux-hardware.org/?probe=e347245de9) | Oct 13, 2023 |
| Acer          | Nitro AN515-57              | [22e91a6509](https://linux-hardware.org/?probe=22e91a6509) | Oct 13, 2023 |
| Clevo         | NL41MU2                     | [366bab6858](https://linux-hardware.org/?probe=366bab6858) | Oct 13, 2023 |
| Acer          | TravelMate 3040             | [8fe8316945](https://linux-hardware.org/?probe=8fe8316945) | Oct 13, 2023 |
| HP            | 635                         | [a44c783f17](https://linux-hardware.org/?probe=a44c783f17) | Oct 13, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [4d434ee41b](https://linux-hardware.org/?probe=4d434ee41b) | Oct 12, 2023 |
| Clevo         | NL41MU2                     | [b44ced08df](https://linux-hardware.org/?probe=b44ced08df) | Oct 12, 2023 |
| Acer          | Predator PH315-54           | [541e679856](https://linux-hardware.org/?probe=541e679856) | Oct 12, 2023 |
| ANCOMP        | Learnmate A15-501           | [6994a91e07](https://linux-hardware.org/?probe=6994a91e07) | Oct 12, 2023 |
| ANCOMP        | Learnmate A15-501           | [2d6b73a209](https://linux-hardware.org/?probe=2d6b73a209) | Oct 12, 2023 |
| Dell          | G3 3500                     | [1f975cc52a](https://linux-hardware.org/?probe=1f975cc52a) | Oct 12, 2023 |
| MSI           | GT72S 6QE                   | [9a2d87eb4c](https://linux-hardware.org/?probe=9a2d87eb4c) | Oct 12, 2023 |
| MSI           | GT72S 6QE                   | [4927bfc263](https://linux-hardware.org/?probe=4927bfc263) | Oct 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [de934434ec](https://linux-hardware.org/?probe=de934434ec) | Oct 11, 2023 |
| HP            | ProBook 4540s               | [c3be7c74a0](https://linux-hardware.org/?probe=c3be7c74a0) | Oct 11, 2023 |
| HUAWEI        | BOM-WXX9                    | [e9e1455443](https://linux-hardware.org/?probe=e9e1455443) | Oct 11, 2023 |
| Intel Clie... | LAPAC71H                    | [a27690b885](https://linux-hardware.org/?probe=a27690b885) | Oct 11, 2023 |
| HUAWEI        | BOM-WXX9                    | [a52015e7d5](https://linux-hardware.org/?probe=a52015e7d5) | Oct 11, 2023 |
| ASUSTek       | T100TAM                     | [b809251676](https://linux-hardware.org/?probe=b809251676) | Oct 11, 2023 |
| Lenovo        | 3000 G530 4151/200          | [093b1381d7](https://linux-hardware.org/?probe=093b1381d7) | Oct 11, 2023 |
| Acer          | AOD270                      | [f42863f60d](https://linux-hardware.org/?probe=f42863f60d) | Oct 11, 2023 |
| Prestigio     | Visconte Quad 3GK           | [5ffdb7e479](https://linux-hardware.org/?probe=5ffdb7e479) | Oct 11, 2023 |
| HONOR         | HYM-WXX                     | [d8ab8c960a](https://linux-hardware.org/?probe=d8ab8c960a) | Oct 10, 2023 |
| Dell          | Inspiron 3521               | [290872884b](https://linux-hardware.org/?probe=290872884b) | Oct 10, 2023 |
| ASUSTek       | K40IJ                       | [67ca367ad2](https://linux-hardware.org/?probe=67ca367ad2) | Oct 10, 2023 |
| Graviton      | Unknown                     | [69c721a100](https://linux-hardware.org/?probe=69c721a100) | Oct 10, 2023 |
| Acer          | Aspire A315-22              | [837bcf58d1](https://linux-hardware.org/?probe=837bcf58d1) | Oct 10, 2023 |
| Lenovo        | ThinkPad T510 43142PU       | [fb8a2b5bf1](https://linux-hardware.org/?probe=fb8a2b5bf1) | Oct 10, 2023 |
| Unknown       | Unknown                     | [52694348d2](https://linux-hardware.org/?probe=52694348d2) | Oct 10, 2023 |
| Dell          | Inspiron 5570               | [2de48e2d74](https://linux-hardware.org/?probe=2de48e2d74) | Oct 09, 2023 |
| HUAWEI        | HN-WX9X                     | [3bb1bed686](https://linux-hardware.org/?probe=3bb1bed686) | Oct 09, 2023 |
| HUAWEI        | KLVF-XX                     | [29789b465a](https://linux-hardware.org/?probe=29789b465a) | Oct 09, 2023 |
| Lenovo        | IdeaPad 530S-15IKB 81EV     | [8d074caf6b](https://linux-hardware.org/?probe=8d074caf6b) | Oct 09, 2023 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | [7f32c31118](https://linux-hardware.org/?probe=7f32c31118) | Oct 09, 2023 |
| Dell          | XPS 13 9310                 | [fc920f0b70](https://linux-hardware.org/?probe=fc920f0b70) | Oct 09, 2023 |
| Acer          | Swift SF114-34              | [1b92216526](https://linux-hardware.org/?probe=1b92216526) | Oct 09, 2023 |
| HP            | ProBook 4545s               | [bc5404508f](https://linux-hardware.org/?probe=bc5404508f) | Oct 09, 2023 |
| Acer          | Aspire A315-42              | [c0e071789f](https://linux-hardware.org/?probe=c0e071789f) | Oct 09, 2023 |
| MSI           | U210/U210 Light             | [14ee9aa051](https://linux-hardware.org/?probe=14ee9aa051) | Oct 09, 2023 |
| HUAWEI        | HN-WX9X                     | [a46f5ac57a](https://linux-hardware.org/?probe=a46f5ac57a) | Oct 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | [e6ba7d9115](https://linux-hardware.org/?probe=e6ba7d9115) | Oct 08, 2023 |
| HUAWEI        | KLVL-WXXW                   | [e2b2cc796b](https://linux-hardware.org/?probe=e2b2cc796b) | Oct 08, 2023 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | [af06968ae1](https://linux-hardware.org/?probe=af06968ae1) | Oct 08, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [0cc35c9eaf](https://linux-hardware.org/?probe=0cc35c9eaf) | Oct 08, 2023 |
| MSI           | Alpha 15 B5EEK              | [8af576f99e](https://linux-hardware.org/?probe=8af576f99e) | Oct 08, 2023 |
| MSI           | U210/U210 Light             | [29ff1c90ca](https://linux-hardware.org/?probe=29ff1c90ca) | Oct 08, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [effcb33ac6](https://linux-hardware.org/?probe=effcb33ac6) | Oct 08, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [f007d5f436](https://linux-hardware.org/?probe=f007d5f436) | Oct 08, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [ee2df4d880](https://linux-hardware.org/?probe=ee2df4d880) | Oct 08, 2023 |
| ASUSTek       | N56VZ                       | [1fd7b27414](https://linux-hardware.org/?probe=1fd7b27414) | Oct 07, 2023 |
| HUAWEI        | HLYL-WXX9                   | [89674f77b2](https://linux-hardware.org/?probe=89674f77b2) | Oct 07, 2023 |
| Timi          | A35S                        | [58494c03cf](https://linux-hardware.org/?probe=58494c03cf) | Oct 07, 2023 |
| HP            | Laptop 15-bw0xx             | [4440996d7b](https://linux-hardware.org/?probe=4440996d7b) | Oct 07, 2023 |
| HP            | Laptop 15-bw0xx             | [7774477854](https://linux-hardware.org/?probe=7774477854) | Oct 07, 2023 |
| HUAWEI        | BOM-WXX9                    | [f473a0a186](https://linux-hardware.org/?probe=f473a0a186) | Oct 07, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | [bad231ff7d](https://linux-hardware.org/?probe=bad231ff7d) | Oct 07, 2023 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [3c17b94cc2](https://linux-hardware.org/?probe=3c17b94cc2) | Oct 07, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | [eac5ec9d19](https://linux-hardware.org/?probe=eac5ec9d19) | Oct 07, 2023 |
| HP            | ProBook 445 G7              | [2107094375](https://linux-hardware.org/?probe=2107094375) | Oct 07, 2023 |
| Acer          | Aspire A515-52G             | [653d2049d2](https://linux-hardware.org/?probe=653d2049d2) | Oct 07, 2023 |
| ROMBICA       | myBook Eclipse              | [d56fec4995](https://linux-hardware.org/?probe=d56fec4995) | Oct 07, 2023 |
| Fujitsu       | LIFEBOOK T731               | [aa4a0a63b6](https://linux-hardware.org/?probe=aa4a0a63b6) | Oct 07, 2023 |
| Apple         | MacBookPro8,1               | [fba1eebca4](https://linux-hardware.org/?probe=fba1eebca4) | Oct 07, 2023 |
| HUAWEI        | HKD-WXX                     | [20886a702a](https://linux-hardware.org/?probe=20886a702a) | Oct 07, 2023 |
| Valve         | Jupiter                     | [7372c13af4](https://linux-hardware.org/?probe=7372c13af4) | Oct 07, 2023 |
| HP            | Laptop 15-rb0xx             | [a52cde95dc](https://linux-hardware.org/?probe=a52cde95dc) | Oct 06, 2023 |
| Timi          | A35S                        | [8d2f6ffa19](https://linux-hardware.org/?probe=8d2f6ffa19) | Oct 06, 2023 |
| Dell          | Vostro 5490                 | [041f3f9d7a](https://linux-hardware.org/?probe=041f3f9d7a) | Oct 06, 2023 |
| Apple         | MacBookPro8,1               | [1f095979f4](https://linux-hardware.org/?probe=1f095979f4) | Oct 06, 2023 |
| Lenovo        | Legion 5 15ARH7H 82RD       | [4703f4b16b](https://linux-hardware.org/?probe=4703f4b16b) | Oct 06, 2023 |
| HUAWEI        | KPL-W0X                     | [0a4d13a8f8](https://linux-hardware.org/?probe=0a4d13a8f8) | Oct 06, 2023 |
| ASUSTek       | G50V                        | [90f92902b1](https://linux-hardware.org/?probe=90f92902b1) | Oct 06, 2023 |
| Kraftway      | ACCORD                      | [b8d5508724](https://linux-hardware.org/?probe=b8d5508724) | Oct 06, 2023 |
| Acer          | Aspire A317-53              | [696bb7d513](https://linux-hardware.org/?probe=696bb7d513) | Oct 05, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [7b88a62033](https://linux-hardware.org/?probe=7b88a62033) | Oct 05, 2023 |
| HP            | ProBook 640 G5              | [0f174cb973](https://linux-hardware.org/?probe=0f174cb973) | Oct 05, 2023 |
| HP            | ProBook 430 G3              | [ba41311f99](https://linux-hardware.org/?probe=ba41311f99) | Oct 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [26c88c2851](https://linux-hardware.org/?probe=26c88c2851) | Oct 05, 2023 |
| Fujitsu Si... | AMILO Pro Edition V3405     | [b566dd24ff](https://linux-hardware.org/?probe=b566dd24ff) | Oct 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [24abe90441](https://linux-hardware.org/?probe=24abe90441) | Oct 04, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [6256ecb2a2](https://linux-hardware.org/?probe=6256ecb2a2) | Oct 04, 2023 |
| ASUSTek       | GL703VD                     | [cfa1d9861b](https://linux-hardware.org/?probe=cfa1d9861b) | Oct 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [b47c0e8e2d](https://linux-hardware.org/?probe=b47c0e8e2d) | Oct 04, 2023 |
| MSI           | Modern 15 B12M              | [1bbe75aa56](https://linux-hardware.org/?probe=1bbe75aa56) | Oct 04, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | [61278c0720](https://linux-hardware.org/?probe=61278c0720) | Oct 04, 2023 |
| HUAWEI        | RLEF-XX                     | [06499eec7c](https://linux-hardware.org/?probe=06499eec7c) | Oct 04, 2023 |
| F-PLUS EQU... | Unknown                     | [104a5f30e4](https://linux-hardware.org/?probe=104a5f30e4) | Oct 04, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [90cb02d71d](https://linux-hardware.org/?probe=90cb02d71d) | Oct 04, 2023 |
| F-PLUS EQU... | FNB-156-P1                  | [aa9a99ccb5](https://linux-hardware.org/?probe=aa9a99ccb5) | Oct 04, 2023 |
| F-PLUS EQU... | FNB-156-P1                  | [200217831d](https://linux-hardware.org/?probe=200217831d) | Oct 04, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [deb34982fa](https://linux-hardware.org/?probe=deb34982fa) | Oct 04, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [2acaa4ddbc](https://linux-hardware.org/?probe=2acaa4ddbc) | Oct 04, 2023 |
| Acer          | Swift SF314-511             | [86cd22fdcd](https://linux-hardware.org/?probe=86cd22fdcd) | Oct 04, 2023 |
| HUAWEI        | CREM-WXX9                   | [e218a8410c](https://linux-hardware.org/?probe=e218a8410c) | Oct 04, 2023 |
| HP            | 250 G8 Notebook PC          | [46b3fb73b0](https://linux-hardware.org/?probe=46b3fb73b0) | Oct 04, 2023 |
| ASUSTek       | ROG Strix G713RM_G713RM     | [01886580a1](https://linux-hardware.org/?probe=01886580a1) | Oct 03, 2023 |
| Lenovo        | G700                        | [7090569f96](https://linux-hardware.org/?probe=7090569f96) | Oct 03, 2023 |
| Acer          | Swift SF314-43              | [b451657ad6](https://linux-hardware.org/?probe=b451657ad6) | Oct 03, 2023 |
| Lenovo        | G70-70 80HW                 | [c63d12108b](https://linux-hardware.org/?probe=c63d12108b) | Oct 03, 2023 |
| MSI           | GS43VR 7RE                  | [cf9a5a8be9](https://linux-hardware.org/?probe=cf9a5a8be9) | Oct 03, 2023 |
| Dell          | System Inspiron 17 7000 ... | [4a237f21f8](https://linux-hardware.org/?probe=4a237f21f8) | Oct 03, 2023 |
| ASUSTek       | X551CAP                     | [37d7bd14c7](https://linux-hardware.org/?probe=37d7bd14c7) | Oct 03, 2023 |
| HIPER         | WORKBOOK                    | [902f508256](https://linux-hardware.org/?probe=902f508256) | Oct 03, 2023 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [5a882153d9](https://linux-hardware.org/?probe=5a882153d9) | Oct 03, 2023 |
| ASUSTek       | G50V                        | [a6edae3eff](https://linux-hardware.org/?probe=a6edae3eff) | Oct 03, 2023 |
| HP            | Laptop 15s-eq2xxx           | [3f7231bda4](https://linux-hardware.org/?probe=3f7231bda4) | Oct 03, 2023 |
| Getac         | X500G3                      | [919772eed0](https://linux-hardware.org/?probe=919772eed0) | Oct 02, 2023 |
| ASUSTek       | X550CL                      | [fc47e59598](https://linux-hardware.org/?probe=fc47e59598) | Oct 02, 2023 |
| Toshiba       | Satellite A200              | [6a3308fba2](https://linux-hardware.org/?probe=6a3308fba2) | Oct 02, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | [cc181da4e1](https://linux-hardware.org/?probe=cc181da4e1) | Oct 02, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | [f35e389d78](https://linux-hardware.org/?probe=f35e389d78) | Oct 02, 2023 |
| MSI           | Katana GF76 12UC            | [3939c14096](https://linux-hardware.org/?probe=3939c14096) | Oct 02, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [0aa82776f5](https://linux-hardware.org/?probe=0aa82776f5) | Oct 01, 2023 |
| HP            | Laptop 15-dw3xxx            | [6443df8957](https://linux-hardware.org/?probe=6443df8957) | Oct 01, 2023 |
| Valve         | Jupiter                     | [bb4a397154](https://linux-hardware.org/?probe=bb4a397154) | Oct 01, 2023 |
| Dell          | Vostro 5402                 | [2718461962](https://linux-hardware.org/?probe=2718461962) | Oct 01, 2023 |
| MSI           | GE70 0NC/GE70 0ND/GE70K ... | [0939610428](https://linux-hardware.org/?probe=0939610428) | Oct 01, 2023 |
| Digma         | EVE 11 C421Y ES1067EW       | [2a54b2d3e1](https://linux-hardware.org/?probe=2a54b2d3e1) | Oct 01, 2023 |
| Packard Be... | EasyNote ENLG81BA           | [c10a5eef39](https://linux-hardware.org/?probe=c10a5eef39) | Oct 01, 2023 |
| Acer          | Aspire A315-58              | [bbab99a4f7](https://linux-hardware.org/?probe=bbab99a4f7) | Sep 30, 2023 |
| Lenovo        | G505s 20255                 | [58a1c6e106](https://linux-hardware.org/?probe=58a1c6e106) | Sep 30, 2023 |
| Infinix       | INBOOK X3                   | [6b5c2647c2](https://linux-hardware.org/?probe=6b5c2647c2) | Sep 30, 2023 |
| Lenovo        | ThinkPad X260 VB6R77903H    | [e7dad368d2](https://linux-hardware.org/?probe=e7dad368d2) | Sep 30, 2023 |
| Lenovo        | ThinkPad X260 VB6R77903H    | [de3079ae33](https://linux-hardware.org/?probe=de3079ae33) | Sep 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [b3959728d3](https://linux-hardware.org/?probe=b3959728d3) | Sep 30, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [73b5907f17](https://linux-hardware.org/?probe=73b5907f17) | Sep 30, 2023 |
| Fujitsu Si... | AMILO Pro Edition V3405     | [4814760ac1](https://linux-hardware.org/?probe=4814760ac1) | Sep 30, 2023 |
| Dell          | Inspiron N5110              | [e796baf50f](https://linux-hardware.org/?probe=e796baf50f) | Sep 30, 2023 |
| Intel Clie... | LAPBC710                    | [3a29dfa2e3](https://linux-hardware.org/?probe=3a29dfa2e3) | Sep 30, 2023 |
| Acer          | Aspire 5560                 | [252d19e4f5](https://linux-hardware.org/?probe=252d19e4f5) | Sep 30, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1402CBA... | [91873a529a](https://linux-hardware.org/?probe=91873a529a) | Sep 30, 2023 |
| Dell          | Inspiron 15 3525            | [b46d569d14](https://linux-hardware.org/?probe=b46d569d14) | Sep 30, 2023 |
| Dell          | Inspiron 15 3525            | [fb52caaee9](https://linux-hardware.org/?probe=fb52caaee9) | Sep 30, 2023 |
| TECNO         | MEGABOOK T1                 | [9bba77e02b](https://linux-hardware.org/?probe=9bba77e02b) | Sep 30, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [527c8192a9](https://linux-hardware.org/?probe=527c8192a9) | Sep 30, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [96e037afc8](https://linux-hardware.org/?probe=96e037afc8) | Sep 29, 2023 |
| Dell          | Inspiron 5558               | [f94587a692](https://linux-hardware.org/?probe=f94587a692) | Sep 29, 2023 |
| Lenovo        | G70-70 80HW                 | [4e22db020f](https://linux-hardware.org/?probe=4e22db020f) | Sep 29, 2023 |
| F-PLUS EQU... | FNB-156-P1                  | [cceaaac2d3](https://linux-hardware.org/?probe=cceaaac2d3) | Sep 29, 2023 |
| HP            | ProBook 430 G3              | [5a73271bfd](https://linux-hardware.org/?probe=5a73271bfd) | Sep 29, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [b9f67caef4](https://linux-hardware.org/?probe=b9f67caef4) | Sep 29, 2023 |
| Lenovo        | G70-70 80HW                 | [5ef0f97836](https://linux-hardware.org/?probe=5ef0f97836) | Sep 29, 2023 |
| Valve         | Jupiter                     | [acc0ad7283](https://linux-hardware.org/?probe=acc0ad7283) | Sep 28, 2023 |
| Lenovo        | ThinkPad E490 20N8000SRT    | [274b3b5210](https://linux-hardware.org/?probe=274b3b5210) | Sep 28, 2023 |
| ROMBICA       | myBook Eclipse              | [004e1dc4fd](https://linux-hardware.org/?probe=004e1dc4fd) | Sep 28, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [4cef8be854](https://linux-hardware.org/?probe=4cef8be854) | Sep 28, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [39fd38bc98](https://linux-hardware.org/?probe=39fd38bc98) | Sep 28, 2023 |
| Lenovo        | ThinkPad T510 43142PU       | [30bd29e170](https://linux-hardware.org/?probe=30bd29e170) | Sep 28, 2023 |
| F-PLUS EQU... | FNB-156-P1                  | [fb8fd7617c](https://linux-hardware.org/?probe=fb8fd7617c) | Sep 28, 2023 |
| Infinix       | INBOOK X2 GEN11             | [2ac0204275](https://linux-hardware.org/?probe=2ac0204275) | Sep 28, 2023 |
| HP            | ProBook 430 G5              | [9e68b6e2be](https://linux-hardware.org/?probe=9e68b6e2be) | Sep 28, 2023 |
| Lenovo        | ThinkPad X250 20CMS0A200    | [54f848d222](https://linux-hardware.org/?probe=54f848d222) | Sep 28, 2023 |
| ASUSTek       | K50IJ                       | [8556633dad](https://linux-hardware.org/?probe=8556633dad) | Sep 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [1317c1f1a9](https://linux-hardware.org/?probe=1317c1f1a9) | Sep 27, 2023 |
| Lenovo        | XiaoXinPro 16 APH8 83AR     | [9ad96a3803](https://linux-hardware.org/?probe=9ad96a3803) | Sep 27, 2023 |
| MSI           | Bravo 15 C7VE               | [844b7f2a1c](https://linux-hardware.org/?probe=844b7f2a1c) | Sep 27, 2023 |
| ASUSTek       | N550JV                      | [ac27d821ae](https://linux-hardware.org/?probe=ac27d821ae) | Sep 27, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [278578e488](https://linux-hardware.org/?probe=278578e488) | Sep 27, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [6f4a404e89](https://linux-hardware.org/?probe=6f4a404e89) | Sep 27, 2023 |
| Chuwi         | GemiBook Pro                | [4ea2bab759](https://linux-hardware.org/?probe=4ea2bab759) | Sep 27, 2023 |
| HUAWEI        | RLEF-XX                     | [156140f867](https://linux-hardware.org/?probe=156140f867) | Sep 27, 2023 |
| Dell          | Latitude 5420               | [4f890f283a](https://linux-hardware.org/?probe=4f890f283a) | Sep 26, 2023 |
| HP            | Laptop 14s-dq2xxx           | [cf522515d7](https://linux-hardware.org/?probe=cf522515d7) | Sep 26, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [243f89703d](https://linux-hardware.org/?probe=243f89703d) | Sep 26, 2023 |
| HUAWEI        | BDZ-WXX9                    | [a33a848e40](https://linux-hardware.org/?probe=a33a848e40) | Sep 26, 2023 |
| Aquarius      | NS585                       | [ce1c1d6e56](https://linux-hardware.org/?probe=ce1c1d6e56) | Sep 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [cf4a15af9e](https://linux-hardware.org/?probe=cf4a15af9e) | Sep 26, 2023 |
| Acer          | Aspire 5750ZG               | [b8e46e5780](https://linux-hardware.org/?probe=b8e46e5780) | Sep 26, 2023 |
| Lenovo        | IdeaPad Y510                | [caec91aae7](https://linux-hardware.org/?probe=caec91aae7) | Sep 26, 2023 |
| Acer          | TravelMate 5744             | [2e69d317ef](https://linux-hardware.org/?probe=2e69d317ef) | Sep 26, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [6a3291f6bf](https://linux-hardware.org/?probe=6a3291f6bf) | Sep 25, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [981e7e8ec5](https://linux-hardware.org/?probe=981e7e8ec5) | Sep 25, 2023 |
| HUAWEI        | BOM-WXX9                    | [8d4ba0b939](https://linux-hardware.org/?probe=8d4ba0b939) | Sep 25, 2023 |
| Dell          | Inspiron 5558               | [dbf4dfe481](https://linux-hardware.org/?probe=dbf4dfe481) | Sep 25, 2023 |
| Lenovo        | IdeaPad 3 17ALC6 82KV       | [1ce8f959f1](https://linux-hardware.org/?probe=1ce8f959f1) | Sep 25, 2023 |
| Aquarius      | NS585                       | [e901467e39](https://linux-hardware.org/?probe=e901467e39) | Sep 25, 2023 |
| HUAWEI        | BOM-WXX9                    | [ed52653514](https://linux-hardware.org/?probe=ed52653514) | Sep 25, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [b85adec006](https://linux-hardware.org/?probe=b85adec006) | Sep 25, 2023 |
| MSI           | Bravo 15 C7VF               | [ab0a5a435f](https://linux-hardware.org/?probe=ab0a5a435f) | Sep 25, 2023 |
| Acer          | Aspire V3-571G              | [6b5dcea023](https://linux-hardware.org/?probe=6b5dcea023) | Sep 25, 2023 |
| Samsung       | N250P                       | [7eb858a64d](https://linux-hardware.org/?probe=7eb858a64d) | Sep 25, 2023 |
| Toshiba       | dynabook Satellite B350/... | [2b241af774](https://linux-hardware.org/?probe=2b241af774) | Sep 25, 2023 |
| Acer          | Aspire 3610                 | [021d48bbdb](https://linux-hardware.org/?probe=021d48bbdb) | Sep 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [811f1951fc](https://linux-hardware.org/?probe=811f1951fc) | Sep 25, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [2695ee345d](https://linux-hardware.org/?probe=2695ee345d) | Sep 24, 2023 |
| Acer          | Aspire A715-42G             | [868a5abe75](https://linux-hardware.org/?probe=868a5abe75) | Sep 24, 2023 |
| Acer          | TravelMate P259-MG          | [26ca7317b2](https://linux-hardware.org/?probe=26ca7317b2) | Sep 24, 2023 |
| Acer          | Aspire ES1-520              | [c2b98b035f](https://linux-hardware.org/?probe=c2b98b035f) | Sep 24, 2023 |
| HUAWEI        | KLVL-WXXW                   | [f2a543d0dd](https://linux-hardware.org/?probe=f2a543d0dd) | Sep 24, 2023 |
| Lenovo        | G580 20150                  | [f55e42a884](https://linux-hardware.org/?probe=f55e42a884) | Sep 24, 2023 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [30d9462d2d](https://linux-hardware.org/?probe=30d9462d2d) | Sep 24, 2023 |
| Unknown       | X133                        | [eca7c95360](https://linux-hardware.org/?probe=eca7c95360) | Sep 24, 2023 |
| Apple         | MacBookPro11,1              | [0f396f4227](https://linux-hardware.org/?probe=0f396f4227) | Sep 24, 2023 |
| HUAWEI        | NBD-WXX9                    | [f728eb13bd](https://linux-hardware.org/?probe=f728eb13bd) | Sep 24, 2023 |
| HP            | Laptop 15s-eq2xxx           | [092bb813b4](https://linux-hardware.org/?probe=092bb813b4) | Sep 24, 2023 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [2814a495de](https://linux-hardware.org/?probe=2814a495de) | Sep 24, 2023 |
| Sony          | VGN-FW11LR                  | [81921a2f1d](https://linux-hardware.org/?probe=81921a2f1d) | Sep 24, 2023 |
| Timi          | TM1701                      | [0e127afa68](https://linux-hardware.org/?probe=0e127afa68) | Sep 24, 2023 |
| Acer          | Aspire 5520                 | [5bcc67211c](https://linux-hardware.org/?probe=5bcc67211c) | Sep 24, 2023 |
| Unknown       | Unknown                     | [b6f7bc9bd2](https://linux-hardware.org/?probe=b6f7bc9bd2) | Sep 24, 2023 |
| HP            | ProBook 450 G1              | [90069ca278](https://linux-hardware.org/?probe=90069ca278) | Sep 23, 2023 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [1809080d01](https://linux-hardware.org/?probe=1809080d01) | Sep 23, 2023 |
| Lenovo        | ThinkPad Edge E430c 3365... | [74351c4243](https://linux-hardware.org/?probe=74351c4243) | Sep 23, 2023 |
| Acer          | AOHAPPY2                    | [b9937354f2](https://linux-hardware.org/?probe=b9937354f2) | Sep 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X321... | [d62c6d340f](https://linux-hardware.org/?probe=d62c6d340f) | Sep 22, 2023 |
| Acer          | Aspire 5520                 | [8329086779](https://linux-hardware.org/?probe=8329086779) | Sep 22, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [c14178c7fa](https://linux-hardware.org/?probe=c14178c7fa) | Sep 22, 2023 |
| Samsung       | R505                        | [8aef37cda9](https://linux-hardware.org/?probe=8aef37cda9) | Sep 22, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [900334906e](https://linux-hardware.org/?probe=900334906e) | Sep 22, 2023 |
| MSI           | GF65 Thin 9SEXR             | [9fbc54dcb7](https://linux-hardware.org/?probe=9fbc54dcb7) | Sep 22, 2023 |
| Dell          | Latitude 5420               | [d9c1c1537f](https://linux-hardware.org/?probe=d9c1c1537f) | Sep 22, 2023 |
| HP            | Laptop 14s-fq0xxx           | [3f7ef99bf3](https://linux-hardware.org/?probe=3f7ef99bf3) | Sep 22, 2023 |
| Valve         | Jupiter                     | [b0abd58408](https://linux-hardware.org/?probe=b0abd58408) | Sep 22, 2023 |
| ASUSTek       | X553SA                      | [451784974b](https://linux-hardware.org/?probe=451784974b) | Sep 21, 2023 |
| HP            | EliteBook 840 G5 NOTEBOO... | [0e85445e8e](https://linux-hardware.org/?probe=0e85445e8e) | Sep 21, 2023 |
| HP            | EliteBook 840 G5 NOTEBOO... | [3a372bed63](https://linux-hardware.org/?probe=3a372bed63) | Sep 21, 2023 |
| Timi          | A35S                        | [ae2a6acf26](https://linux-hardware.org/?probe=ae2a6acf26) | Sep 21, 2023 |
| Kraftway      | ACCORD                      | [df4d5654d5](https://linux-hardware.org/?probe=df4d5654d5) | Sep 21, 2023 |
| ASUSTek       | K50IJ                       | [a1dcfd7ff7](https://linux-hardware.org/?probe=a1dcfd7ff7) | Sep 21, 2023 |
| Lenovo        | ThinkPad T510 43142PU       | [527f5eb1a9](https://linux-hardware.org/?probe=527f5eb1a9) | Sep 21, 2023 |
| HP            | 630                         | [1ed6efc4de](https://linux-hardware.org/?probe=1ed6efc4de) | Sep 21, 2023 |
| Lenovo        | B590 20208                  | [f8c48a3ed3](https://linux-hardware.org/?probe=f8c48a3ed3) | Sep 21, 2023 |
| Fujitsu Si... | AMILO Li3710                | [5a5c48d3df](https://linux-hardware.org/?probe=5a5c48d3df) | Sep 20, 2023 |
| Clevo         | NL41MU2                     | [68b62bb7da](https://linux-hardware.org/?probe=68b62bb7da) | Sep 20, 2023 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | [c8bbae1068](https://linux-hardware.org/?probe=c8bbae1068) | Sep 20, 2023 |
| ASUSTek       | 1001PX                      | [6331a101c7](https://linux-hardware.org/?probe=6331a101c7) | Sep 20, 2023 |
| HUAWEI        | BOM-WXX9                    | [4861bef61e](https://linux-hardware.org/?probe=4861bef61e) | Sep 20, 2023 |
| Samsung       | NC210/NC110                 | [1e194a2568](https://linux-hardware.org/?probe=1e194a2568) | Sep 20, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [27002ca3a9](https://linux-hardware.org/?probe=27002ca3a9) | Sep 20, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [17bfc616ef](https://linux-hardware.org/?probe=17bfc616ef) | Sep 20, 2023 |
| Maibenben     | MaiBook M Series            | [dc2eb7a7d7](https://linux-hardware.org/?probe=dc2eb7a7d7) | Sep 19, 2023 |
| Apple         | MacBookPro8,1               | [c1ca0a1d1c](https://linux-hardware.org/?probe=c1ca0a1d1c) | Sep 19, 2023 |
| HUAWEI        | KLVL-WXXW                   | [efed6450c5](https://linux-hardware.org/?probe=efed6450c5) | Sep 19, 2023 |
| Clevo         | W240EL/W250ELQ/W270ELQ      | [6e554fc589](https://linux-hardware.org/?probe=6e554fc589) | Sep 19, 2023 |
| MSI           | Summit E15 A11SCST          | [aa908f1cea](https://linux-hardware.org/?probe=aa908f1cea) | Sep 19, 2023 |
| Toshiba       | QOSMIO X300                 | [fe89cd3f23](https://linux-hardware.org/?probe=fe89cd3f23) | Sep 19, 2023 |
| Valve         | Jupiter                     | [458972a2c0](https://linux-hardware.org/?probe=458972a2c0) | Sep 19, 2023 |
| Acer          | Aspire ES1-520              | [8006999633](https://linux-hardware.org/?probe=8006999633) | Sep 19, 2023 |
| Acer          | Aspire A315-42              | [ae09470cce](https://linux-hardware.org/?probe=ae09470cce) | Sep 19, 2023 |
| HUAWEI        | BOM-WXX9                    | [286398db3c](https://linux-hardware.org/?probe=286398db3c) | Sep 19, 2023 |
| HUAWEI        | BOM-WXX9                    | [ad024119be](https://linux-hardware.org/?probe=ad024119be) | Sep 19, 2023 |
| MSI           | GF65 Thin 9SEXR             | [d8166ef941](https://linux-hardware.org/?probe=d8166ef941) | Sep 19, 2023 |
| Acer          | Aspire A315-22G             | [0c047cb731](https://linux-hardware.org/?probe=0c047cb731) | Sep 19, 2023 |
| HP            | Pavilion g6                 | [f11438b1a2](https://linux-hardware.org/?probe=f11438b1a2) | Sep 19, 2023 |
| Intel Clie... | LAPBC710                    | [af446fcb4d](https://linux-hardware.org/?probe=af446fcb4d) | Sep 19, 2023 |
| Intel Clie... | LAPBC710                    | [eae124fa61](https://linux-hardware.org/?probe=eae124fa61) | Sep 19, 2023 |
| HP            | Laptop 15s-eq2xxx           | [53549e3b08](https://linux-hardware.org/?probe=53549e3b08) | Sep 18, 2023 |
| iRU           | 17ALC                       | [2d0b23c813](https://linux-hardware.org/?probe=2d0b23c813) | Sep 18, 2023 |
| Acer          | Extensa 215-32              | [6879449933](https://linux-hardware.org/?probe=6879449933) | Sep 18, 2023 |
| HP            | Pavilion 15                 | [eb15fe383c](https://linux-hardware.org/?probe=eb15fe383c) | Sep 18, 2023 |
| Aquarius      | NS585                       | [6ac8bd5909](https://linux-hardware.org/?probe=6ac8bd5909) | Sep 18, 2023 |
| HP            | Pavilion 15                 | [fb86634643](https://linux-hardware.org/?probe=fb86634643) | Sep 18, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [4d986c5384](https://linux-hardware.org/?probe=4d986c5384) | Sep 18, 2023 |
| HP            | Notebook                    | [0c80a5c83f](https://linux-hardware.org/?probe=0c80a5c83f) | Sep 18, 2023 |
| Acer          | Aspire 5755G                | [f58cf1f72d](https://linux-hardware.org/?probe=f58cf1f72d) | Sep 18, 2023 |
| Fujitsu       | LIFEBOOK N6470              | [bbc02d8d99](https://linux-hardware.org/?probe=bbc02d8d99) | Sep 18, 2023 |
| Clevo         | NL41MU2                     | [ae7db27e79](https://linux-hardware.org/?probe=ae7db27e79) | Sep 18, 2023 |
| Acer          | Aspire 5755G                | [68cef2242a](https://linux-hardware.org/?probe=68cef2242a) | Sep 18, 2023 |
| Lenovo        | ThinkPad X250 20CMS0A200    | [43df4bd3f3](https://linux-hardware.org/?probe=43df4bd3f3) | Sep 18, 2023 |
| HUAWEI        | BOM-WXX9                    | [ce88b51f6e](https://linux-hardware.org/?probe=ce88b51f6e) | Sep 17, 2023 |
| HP            | ProBook 4535s               | [4fad5ba2da](https://linux-hardware.org/?probe=4fad5ba2da) | Sep 17, 2023 |
| Unknown       | Unknown                     | [3b4224eda5](https://linux-hardware.org/?probe=3b4224eda5) | Sep 17, 2023 |
| eMachines     | Rhine V1.43                 | [1dc929e263](https://linux-hardware.org/?probe=1dc929e263) | Sep 17, 2023 |
| Clevo         | W240EL/W250ELQ/W270ELQ      | [e5a3155306](https://linux-hardware.org/?probe=e5a3155306) | Sep 17, 2023 |
| iRU           | 15ALC                       | [c5839fb7da](https://linux-hardware.org/?probe=c5839fb7da) | Sep 17, 2023 |
| iRU           | 15ALC                       | [87679b8dc1](https://linux-hardware.org/?probe=87679b8dc1) | Sep 17, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [77a72808f7](https://linux-hardware.org/?probe=77a72808f7) | Sep 17, 2023 |
| Timi          | Redmi Book Pro 14 2022      | [0ebcb848ff](https://linux-hardware.org/?probe=0ebcb848ff) | Sep 16, 2023 |
| Acer          | Aspire A515-45              | [7cd5acacf7](https://linux-hardware.org/?probe=7cd5acacf7) | Sep 16, 2023 |
| Lenovo        | G570 20079                  | [f2da433d78](https://linux-hardware.org/?probe=f2da433d78) | Sep 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [80435bbec3](https://linux-hardware.org/?probe=80435bbec3) | Sep 16, 2023 |
| ASUSTek       | 1215P                       | [6741860726](https://linux-hardware.org/?probe=6741860726) | Sep 16, 2023 |
| Pegatron      | A35                         | [b95829115c](https://linux-hardware.org/?probe=b95829115c) | Sep 16, 2023 |
| ASUSTek       | 1215P                       | [51735ee7d6](https://linux-hardware.org/?probe=51735ee7d6) | Sep 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [567443136d](https://linux-hardware.org/?probe=567443136d) | Sep 15, 2023 |
| Timi          | Redmi Book Pro 14 2022      | [c5fccb4455](https://linux-hardware.org/?probe=c5fccb4455) | Sep 15, 2023 |
| MSI           | Modern 15 B7M               | [4d35879250](https://linux-hardware.org/?probe=4d35879250) | Sep 15, 2023 |
| F-PLUS EQU... | FNB-156-P1                  | [ddd1dc3953](https://linux-hardware.org/?probe=ddd1dc3953) | Sep 15, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [f9117dd665](https://linux-hardware.org/?probe=f9117dd665) | Sep 15, 2023 |
| HUAWEI        | NBD-WXX9                    | [282def5c2a](https://linux-hardware.org/?probe=282def5c2a) | Sep 15, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [c6cc55c6ec](https://linux-hardware.org/?probe=c6cc55c6ec) | Sep 15, 2023 |
| ASUSTek       | X507UB                      | [ca19710375](https://linux-hardware.org/?probe=ca19710375) | Sep 15, 2023 |
| TECNO         | MEGABOOK T1                 | [b15d4ed6b0](https://linux-hardware.org/?probe=b15d4ed6b0) | Sep 15, 2023 |
| HUAWEI        | HKD-WXX                     | [4d0eb9b8d2](https://linux-hardware.org/?probe=4d0eb9b8d2) | Sep 15, 2023 |
| Timi          | A35S                        | [b229627e35](https://linux-hardware.org/?probe=b229627e35) | Sep 14, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0ffb2a765f](https://linux-hardware.org/?probe=0ffb2a765f) | Sep 14, 2023 |
| HP            | G5000 (RY492EA#ACB)         | [0f0a19a64c](https://linux-hardware.org/?probe=0f0a19a64c) | Sep 14, 2023 |
| Clevo         | NL41MU2                     | [4400eaccdb](https://linux-hardware.org/?probe=4400eaccdb) | Sep 14, 2023 |
| ASUSTek       | T100TAM                     | [f3d6cb60ec](https://linux-hardware.org/?probe=f3d6cb60ec) | Sep 14, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [cf69e328c4](https://linux-hardware.org/?probe=cf69e328c4) | Sep 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [2f2e7e3663](https://linux-hardware.org/?probe=2f2e7e3663) | Sep 14, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [d61823257e](https://linux-hardware.org/?probe=d61823257e) | Sep 13, 2023 |
| Lenovo        | YogaAir 14s APU8 83AA       | [b8b03de96a](https://linux-hardware.org/?probe=b8b03de96a) | Sep 13, 2023 |
| Dell          | System Inspiron 17 7000 ... | [9dd436fa60](https://linux-hardware.org/?probe=9dd436fa60) | Sep 13, 2023 |
| HP            | Pavilion g6                 | [8ae79d7b93](https://linux-hardware.org/?probe=8ae79d7b93) | Sep 13, 2023 |
| HP            | Laptop 15-da3xxx            | [86c32c23db](https://linux-hardware.org/?probe=86c32c23db) | Sep 13, 2023 |
| HP            | ProBook 6570b               | [baf81a81a2](https://linux-hardware.org/?probe=baf81a81a2) | Sep 13, 2023 |
| Dell          | G3 3579                     | [0da9f9b572](https://linux-hardware.org/?probe=0da9f9b572) | Sep 13, 2023 |
| HP            | ProBook 4310s               | [5c60f06750](https://linux-hardware.org/?probe=5c60f06750) | Sep 13, 2023 |
| HP            | ProBook 6570b               | [90aaacf4af](https://linux-hardware.org/?probe=90aaacf4af) | Sep 13, 2023 |
| HP            | ProBook 445 G7              | [5210aaa5ee](https://linux-hardware.org/?probe=5210aaa5ee) | Sep 13, 2023 |
| ASUSTek       | N56VJ                       | [8cf70251ac](https://linux-hardware.org/?probe=8cf70251ac) | Sep 13, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [2a30486273](https://linux-hardware.org/?probe=2a30486273) | Sep 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [006062545f](https://linux-hardware.org/?probe=006062545f) | Sep 13, 2023 |
| Acer          | Aspire ES1-311              | [d191439979](https://linux-hardware.org/?probe=d191439979) | Sep 13, 2023 |
| HUAWEI        | KLVL-WXXW                   | [138dfabe47](https://linux-hardware.org/?probe=138dfabe47) | Sep 13, 2023 |
| Acer          | Aspire A515-45              | [1df9430f46](https://linux-hardware.org/?probe=1df9430f46) | Sep 13, 2023 |
| Timi          | Redmi Book Pro 14S          | [261ee2ede0](https://linux-hardware.org/?probe=261ee2ede0) | Sep 13, 2023 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [2260bcd7af](https://linux-hardware.org/?probe=2260bcd7af) | Sep 12, 2023 |
| HUAWEI        | BOM-WXX9                    | [546dbbeb91](https://linux-hardware.org/?probe=546dbbeb91) | Sep 12, 2023 |
| ASUSTek       | K53SK                       | [5dcbdaa6d7](https://linux-hardware.org/?probe=5dcbdaa6d7) | Sep 12, 2023 |
| HUAWEI        | NBD-WXX9                    | [663412fd9c](https://linux-hardware.org/?probe=663412fd9c) | Sep 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [9f94d7ad84](https://linux-hardware.org/?probe=9f94d7ad84) | Sep 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [15457ee4ca](https://linux-hardware.org/?probe=15457ee4ca) | Sep 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [675582a822](https://linux-hardware.org/?probe=675582a822) | Sep 12, 2023 |
| HP            | ENVY Notebook               | [cd276f172f](https://linux-hardware.org/?probe=cd276f172f) | Sep 12, 2023 |
| Lenovo        | ThinkPad E14 20RA002QRT     | [9aba9182e3](https://linux-hardware.org/?probe=9aba9182e3) | Sep 12, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [f018495b81](https://linux-hardware.org/?probe=f018495b81) | Sep 12, 2023 |
| Lenovo        | G770 20089                  | [39c8088b09](https://linux-hardware.org/?probe=39c8088b09) | Sep 12, 2023 |
| HUAWEI        | BOM-WXX9                    | [0224dfd46f](https://linux-hardware.org/?probe=0224dfd46f) | Sep 11, 2023 |
| Dell          | Vostro 5481                 | [c8a8b7db55](https://linux-hardware.org/?probe=c8a8b7db55) | Sep 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [825795d0df](https://linux-hardware.org/?probe=825795d0df) | Sep 11, 2023 |
| HP            | Pavilion DV6                | [fde8a8cef6](https://linux-hardware.org/?probe=fde8a8cef6) | Sep 11, 2023 |
| HP            | ProBook 4535s               | [7ba4ddd436](https://linux-hardware.org/?probe=7ba4ddd436) | Sep 11, 2023 |
| ASUSTek       | X505BA                      | [cbb45a815f](https://linux-hardware.org/?probe=cbb45a815f) | Sep 11, 2023 |
| Infinix       | INBOOK X2 GEN11             | [5e87de3be1](https://linux-hardware.org/?probe=5e87de3be1) | Sep 11, 2023 |
| Notebook      | W54_W94_W955TU,-T,-C        | [7418d15ca6](https://linux-hardware.org/?probe=7418d15ca6) | Sep 10, 2023 |
| Notebook      | W54_W94_W955TU,-T,-C        | [c1f536984f](https://linux-hardware.org/?probe=c1f536984f) | Sep 10, 2023 |
| realme        | RMNBXXXX                    | [93403f6054](https://linux-hardware.org/?probe=93403f6054) | Sep 10, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [2387d97fff](https://linux-hardware.org/?probe=2387d97fff) | Sep 10, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [b5a174bf19](https://linux-hardware.org/?probe=b5a174bf19) | Sep 10, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [30fd7bf070](https://linux-hardware.org/?probe=30fd7bf070) | Sep 10, 2023 |
| HUAWEI        | KLVL-WXXW                   | [7cb4d5f364](https://linux-hardware.org/?probe=7cb4d5f364) | Sep 10, 2023 |
| Apple         | MacBookPro13,3              | [225a9ae1c5](https://linux-hardware.org/?probe=225a9ae1c5) | Sep 10, 2023 |
| HP            | Unknown                     | [cb5704a65f](https://linux-hardware.org/?probe=cb5704a65f) | Sep 10, 2023 |
| ASUSTek       | N56VJ                       | [cb528e4c6d](https://linux-hardware.org/?probe=cb528e4c6d) | Sep 09, 2023 |
| Acer          | Swift SF314-43              | [7c50d60e91](https://linux-hardware.org/?probe=7c50d60e91) | Sep 09, 2023 |
| Toshiba       | Satellite C850-C1S          | [ce5643add2](https://linux-hardware.org/?probe=ce5643add2) | Sep 09, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [82c10c1ff9](https://linux-hardware.org/?probe=82c10c1ff9) | Sep 09, 2023 |
| HP            | Laptop 14s-dq2xxx           | [a61ebacf85](https://linux-hardware.org/?probe=a61ebacf85) | Sep 09, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [d2dbf4cee7](https://linux-hardware.org/?probe=d2dbf4cee7) | Sep 09, 2023 |
| Unknown       | Unknown                     | [bd4b5d82ed](https://linux-hardware.org/?probe=bd4b5d82ed) | Sep 09, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [57e235e93d](https://linux-hardware.org/?probe=57e235e93d) | Sep 09, 2023 |
| Lenovo        | G580 20157                  | [3a772f3179](https://linux-hardware.org/?probe=3a772f3179) | Sep 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [5e3574fbca](https://linux-hardware.org/?probe=5e3574fbca) | Sep 08, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [e0899f8743](https://linux-hardware.org/?probe=e0899f8743) | Sep 08, 2023 |
| Aquarius      | NS685U R11                  | [0a5a01ea58](https://linux-hardware.org/?probe=0a5a01ea58) | Sep 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X321... | [7796aa07e0](https://linux-hardware.org/?probe=7796aa07e0) | Sep 08, 2023 |
| Notebook      | W65_67SC                    | [cefbf3383a](https://linux-hardware.org/?probe=cefbf3383a) | Sep 08, 2023 |
| LTD Delovo... | 15CLG2                      | [2497c739e2](https://linux-hardware.org/?probe=2497c739e2) | Sep 08, 2023 |
| Notebook      | W65_67SC                    | [73eae4d8a0](https://linux-hardware.org/?probe=73eae4d8a0) | Sep 08, 2023 |
| Dell          | Vostro 15 3510              | [0937591ca4](https://linux-hardware.org/?probe=0937591ca4) | Sep 08, 2023 |
| ASUSTek       | X507UB                      | [4604e73045](https://linux-hardware.org/?probe=4604e73045) | Sep 08, 2023 |
| HONOR         | FRI-FXX                     | [6c852bb5bc](https://linux-hardware.org/?probe=6c852bb5bc) | Sep 07, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [e2f9ce90d3](https://linux-hardware.org/?probe=e2f9ce90d3) | Sep 07, 2023 |
| Lenovo        | V15-IGL 82C3                | [78ecb1b882](https://linux-hardware.org/?probe=78ecb1b882) | Sep 07, 2023 |
| Timi          | Redmi Book Pro 14S          | [b2776d8282](https://linux-hardware.org/?probe=b2776d8282) | Sep 07, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [9911fc5254](https://linux-hardware.org/?probe=9911fc5254) | Sep 07, 2023 |
| Valve         | Jupiter                     | [83b9205283](https://linux-hardware.org/?probe=83b9205283) | Sep 07, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [3c6e29c3c3](https://linux-hardware.org/?probe=3c6e29c3c3) | Sep 06, 2023 |
| ASUSTek       | ZenBook Pro Duo UX582LR_... | [b2ba03726a](https://linux-hardware.org/?probe=b2ba03726a) | Sep 06, 2023 |
| realme        | RMNBXXXX                    | [6783f1d181](https://linux-hardware.org/?probe=6783f1d181) | Sep 06, 2023 |
| HP            | Pavilion dv6                | [08d38c1680](https://linux-hardware.org/?probe=08d38c1680) | Sep 06, 2023 |
| HUAWEI        | NBD-WXX9                    | [29e1f84537](https://linux-hardware.org/?probe=29e1f84537) | Sep 06, 2023 |
| MSI           | GE70 2PE                    | [19dddb0418](https://linux-hardware.org/?probe=19dddb0418) | Sep 06, 2023 |
| realme        | RMNBXXXX                    | [9370483c5f](https://linux-hardware.org/?probe=9370483c5f) | Sep 06, 2023 |
| Timi          | Xiaomi Book Pro 14 2022     | [32c34f0aa2](https://linux-hardware.org/?probe=32c34f0aa2) | Sep 06, 2023 |
| Maibenben     | MaiBook M                   | [c3a39bc1f1](https://linux-hardware.org/?probe=c3a39bc1f1) | Sep 06, 2023 |
| ASUSTek       | X75VC                       | [ba211ae5ca](https://linux-hardware.org/?probe=ba211ae5ca) | Sep 06, 2023 |
| Clevo         | NL41MU2                     | [c309162d11](https://linux-hardware.org/?probe=c309162d11) | Sep 06, 2023 |
| ASUSTek       | X542UQ                      | [50ecc5159c](https://linux-hardware.org/?probe=50ecc5159c) | Sep 06, 2023 |
| ASUSTek       | X542UQ                      | [b34e0e7866](https://linux-hardware.org/?probe=b34e0e7866) | Sep 06, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [e8caa63849](https://linux-hardware.org/?probe=e8caa63849) | Sep 06, 2023 |
| ASUSTek       | N76VJ                       | [382d892ff6](https://linux-hardware.org/?probe=382d892ff6) | Sep 05, 2023 |
| Acer          | Nitro AN515-46              | [bbbba2bc47](https://linux-hardware.org/?probe=bbbba2bc47) | Sep 05, 2023 |
| Unknown       | Unknown                     | [9b4d95cf35](https://linux-hardware.org/?probe=9b4d95cf35) | Sep 05, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [7d6ff14b38](https://linux-hardware.org/?probe=7d6ff14b38) | Sep 05, 2023 |
| HP            | Pavilion Notebook           | [b8dd9b8f96](https://linux-hardware.org/?probe=b8dd9b8f96) | Sep 05, 2023 |
| Dell          | G5 5590                     | [40098c0a79](https://linux-hardware.org/?probe=40098c0a79) | Sep 05, 2023 |
| Dell          | G5 5590                     | [1af9fd689a](https://linux-hardware.org/?probe=1af9fd689a) | Sep 05, 2023 |
| HP            | EliteBook 840 G4            | [28d5496080](https://linux-hardware.org/?probe=28d5496080) | Sep 04, 2023 |
| ASUSTek       | X75VC                       | [0830aad0cc](https://linux-hardware.org/?probe=0830aad0cc) | Sep 04, 2023 |
| Toshiba       | Satellite A200              | [439b7547a5](https://linux-hardware.org/?probe=439b7547a5) | Sep 04, 2023 |
| Acer          | Aspire 3690                 | [503b015d34](https://linux-hardware.org/?probe=503b015d34) | Sep 04, 2023 |
| ASUSTek       | N76VB                       | [246d3b2d0a](https://linux-hardware.org/?probe=246d3b2d0a) | Sep 04, 2023 |
| HP            | Laptop 15s-fq2xxx           | [2135954523](https://linux-hardware.org/?probe=2135954523) | Sep 04, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [ee6914ebdf](https://linux-hardware.org/?probe=ee6914ebdf) | Sep 04, 2023 |
| Maibenben     | MaiBook M                   | [7189994067](https://linux-hardware.org/?probe=7189994067) | Sep 04, 2023 |
| HP            | EliteBook 845 14 inch G1... | [8a4af58adc](https://linux-hardware.org/?probe=8a4af58adc) | Sep 04, 2023 |
| MSI           | Prestige 14Evo A12M         | [68bea64ed6](https://linux-hardware.org/?probe=68bea64ed6) | Sep 04, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [8320743af2](https://linux-hardware.org/?probe=8320743af2) | Sep 04, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [18d1abc9ca](https://linux-hardware.org/?probe=18d1abc9ca) | Sep 04, 2023 |
| Lenovo        | B460e                       | [7134698bfb](https://linux-hardware.org/?probe=7134698bfb) | Sep 03, 2023 |
| ASUSTek       | X507UB                      | [e74c3ad568](https://linux-hardware.org/?probe=e74c3ad568) | Sep 03, 2023 |
| Apple         | MacBookAir6,2               | [94da12d8d8](https://linux-hardware.org/?probe=94da12d8d8) | Sep 03, 2023 |
| HUAWEI        | FRD-WX9                     | [5831652a84](https://linux-hardware.org/?probe=5831652a84) | Sep 03, 2023 |
| ASUSTek       | 1015BX                      | [7abcd39073](https://linux-hardware.org/?probe=7abcd39073) | Sep 03, 2023 |
| Lenovo        | ThinkPad T410 25188PG       | [603479bd64](https://linux-hardware.org/?probe=603479bd64) | Sep 03, 2023 |
| HP            | ENVY m6                     | [0a810c8663](https://linux-hardware.org/?probe=0a810c8663) | Sep 03, 2023 |
| Acer          | Nitro AN515-46              | [ebfb4ddd3e](https://linux-hardware.org/?probe=ebfb4ddd3e) | Sep 03, 2023 |
| Sony          | VPCEL1E1R                   | [64dec0f73c](https://linux-hardware.org/?probe=64dec0f73c) | Sep 03, 2023 |
| Sony          | VPCEL1E1R                   | [4a55a9ce8d](https://linux-hardware.org/?probe=4a55a9ce8d) | Sep 03, 2023 |
| HP            | Laptop 15-rb0xx             | [0f08b5b0ad](https://linux-hardware.org/?probe=0f08b5b0ad) | Sep 03, 2023 |
| Lenovo        | ThinkPad X230 23252SG       | [78c449e398](https://linux-hardware.org/?probe=78c449e398) | Sep 03, 2023 |
| Lenovo        | ThinkPad X230 23252SG       | [7f25cc995d](https://linux-hardware.org/?probe=7f25cc995d) | Sep 03, 2023 |
| Lenovo        | B590 20206                  | [3e11cfff1b](https://linux-hardware.org/?probe=3e11cfff1b) | Sep 02, 2023 |
| MSI           | GT60 2QE                    | [234502653b](https://linux-hardware.org/?probe=234502653b) | Sep 02, 2023 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | [3969affef8](https://linux-hardware.org/?probe=3969affef8) | Sep 02, 2023 |
| HP            | ProBook 430 G5              | [1785af95b8](https://linux-hardware.org/?probe=1785af95b8) | Sep 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [c5db2939ee](https://linux-hardware.org/?probe=c5db2939ee) | Sep 02, 2023 |
| Irbis         | NB133                       | [62f2194b9a](https://linux-hardware.org/?probe=62f2194b9a) | Sep 02, 2023 |
| HONOR         | HYM-WXX                     | [1af7f717b0](https://linux-hardware.org/?probe=1af7f717b0) | Sep 02, 2023 |
| ASUSTek       | N750JV                      | [f23cf01c1c](https://linux-hardware.org/?probe=f23cf01c1c) | Sep 02, 2023 |
| Lenovo        | G505 20240                  | [ea15ab596a](https://linux-hardware.org/?probe=ea15ab596a) | Sep 02, 2023 |
| HP            | 630                         | [a1f0efde46](https://linux-hardware.org/?probe=a1f0efde46) | Sep 02, 2023 |
| Dell          | Inspiron 3793               | [fb0900afbb](https://linux-hardware.org/?probe=fb0900afbb) | Sep 02, 2023 |
| Valve         | Jupiter                     | [8e59296a5c](https://linux-hardware.org/?probe=8e59296a5c) | Sep 02, 2023 |
| Prestigio     | Multipad Visconte V         | [3c60fe1d14](https://linux-hardware.org/?probe=3c60fe1d14) | Sep 01, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [d646fdb00d](https://linux-hardware.org/?probe=d646fdb00d) | Sep 01, 2023 |
| eMachines     | eME442                      | [7b765f910c](https://linux-hardware.org/?probe=7b765f910c) | Sep 01, 2023 |
| Gigabyte      | G5 KF                       | [b38cdf7987](https://linux-hardware.org/?probe=b38cdf7987) | Sep 01, 2023 |
| Gigabyte      | G5 KF                       | [3eef6bf0d1](https://linux-hardware.org/?probe=3eef6bf0d1) | Sep 01, 2023 |
| Packard Be... | EasyNote TE11HC             | [2a11f6be15](https://linux-hardware.org/?probe=2a11f6be15) | Sep 01, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [42547fa1b3](https://linux-hardware.org/?probe=42547fa1b3) | Sep 01, 2023 |
| ASUSTek       | ZenBook UX535LI_UX535LI     | [edd00c35fd](https://linux-hardware.org/?probe=edd00c35fd) | Sep 01, 2023 |
| Lenovo        | Legion R9000P2021H 82JQ     | [1e7179e4f0](https://linux-hardware.org/?probe=1e7179e4f0) | Sep 01, 2023 |
| HONOR         | HYM-WXX                     | [e9f211faf1](https://linux-hardware.org/?probe=e9f211faf1) | Sep 01, 2023 |
| HONOR         | HYM-WXX                     | [b1a3900bdd](https://linux-hardware.org/?probe=b1a3900bdd) | Sep 01, 2023 |
| ASUSTek       | W7S                         | [6865435d79](https://linux-hardware.org/?probe=6865435d79) | Aug 31, 2023 |
| ASUSTek       | ASUS EXPERTBOOK L2402CYA... | [9881dd3268](https://linux-hardware.org/?probe=9881dd3268) | Aug 31, 2023 |
| ASUSTek       | X550CC                      | [0265cb5d01](https://linux-hardware.org/?probe=0265cb5d01) | Aug 31, 2023 |
| HP            | Notebook                    | [0d55f397ff](https://linux-hardware.org/?probe=0d55f397ff) | Aug 31, 2023 |
| Lenovo        | Z50-70 20354                | [305133ce29](https://linux-hardware.org/?probe=305133ce29) | Aug 31, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [7c560dfe57](https://linux-hardware.org/?probe=7c560dfe57) | Aug 31, 2023 |
| HUAWEI        | KLVF-XX                     | [747a685cc1](https://linux-hardware.org/?probe=747a685cc1) | Aug 30, 2023 |
| HUAWEI        | BOM-WXX9                    | [ea587f2b2e](https://linux-hardware.org/?probe=ea587f2b2e) | Aug 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [ef1b605965](https://linux-hardware.org/?probe=ef1b605965) | Aug 30, 2023 |
| ASUSTek       | K52Je                       | [27136611ed](https://linux-hardware.org/?probe=27136611ed) | Aug 30, 2023 |
| Infinix       | INBOOK X2 GEN11             | [b196e48c97](https://linux-hardware.org/?probe=b196e48c97) | Aug 30, 2023 |
| Timi          | Redmi Book Pro 14 2022      | [0842215d23](https://linux-hardware.org/?probe=0842215d23) | Aug 30, 2023 |
| HP            | Laptop 17-ca1xxx            | [a7b83b57e0](https://linux-hardware.org/?probe=a7b83b57e0) | Aug 30, 2023 |
| Acer          | Nitro AN515-52              | [efee17a022](https://linux-hardware.org/?probe=efee17a022) | Aug 30, 2023 |
| HP            | Laptop 17-ca1xxx            | [d7860c1c92](https://linux-hardware.org/?probe=d7860c1c92) | Aug 30, 2023 |
| Acer          | TravelMate P259-MG          | [dc9b122d90](https://linux-hardware.org/?probe=dc9b122d90) | Aug 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [98d2e58ba6](https://linux-hardware.org/?probe=98d2e58ba6) | Aug 30, 2023 |
| HP            | ENVY Notebook               | [eda6f43e59](https://linux-hardware.org/?probe=eda6f43e59) | Aug 30, 2023 |
| Acer          | Aspire A515-57              | [c9a61f810d](https://linux-hardware.org/?probe=c9a61f810d) | Aug 30, 2023 |
| Acer          | Aspire A515-57              | [d6fded6169](https://linux-hardware.org/?probe=d6fded6169) | Aug 30, 2023 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | [7b3b082c14](https://linux-hardware.org/?probe=7b3b082c14) | Aug 30, 2023 |
| Digma         | EVE 11 C421Y ES1067EW       | [22e88dc9a5](https://linux-hardware.org/?probe=22e88dc9a5) | Aug 29, 2023 |
| Fujitsu Si... | AMILO Pro Edition V3405     | [95aa09fab6](https://linux-hardware.org/?probe=95aa09fab6) | Aug 29, 2023 |
| HP            | Pavilion dv7                | [2d5e628923](https://linux-hardware.org/?probe=2d5e628923) | Aug 29, 2023 |
| Clevo         | NL41MU2                     | [9bd0b91866](https://linux-hardware.org/?probe=9bd0b91866) | Aug 29, 2023 |
| Timi          | A34S                        | [eb6a3c2430](https://linux-hardware.org/?probe=eb6a3c2430) | Aug 29, 2023 |
| HP            | ProBook 430 G4 NOTEBOOK ... | [6ee102c046](https://linux-hardware.org/?probe=6ee102c046) | Aug 28, 2023 |
| Apple         | MacBook7,1                  | [c823f63fd6](https://linux-hardware.org/?probe=c823f63fd6) | Aug 28, 2023 |
| Apple         | MacBookPro11,3              | [a102cdc504](https://linux-hardware.org/?probe=a102cdc504) | Aug 28, 2023 |
| Dell          | Inspiron 3558               | [7c1198413a](https://linux-hardware.org/?probe=7c1198413a) | Aug 28, 2023 |
| ICL           | S1511 G1R                   | [421df1df8d](https://linux-hardware.org/?probe=421df1df8d) | Aug 28, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [a3a1e805b2](https://linux-hardware.org/?probe=a3a1e805b2) | Aug 27, 2023 |
| ASUSTek       | K42DY                       | [5a9171654b](https://linux-hardware.org/?probe=5a9171654b) | Aug 27, 2023 |
| Infinix       | INBOOK X2 GEN11             | [d8f8a287e6](https://linux-hardware.org/?probe=d8f8a287e6) | Aug 27, 2023 |
| ASUSTek       | X553SA                      | [ca9ccf934d](https://linux-hardware.org/?probe=ca9ccf934d) | Aug 27, 2023 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | [173b99bf55](https://linux-hardware.org/?probe=173b99bf55) | Aug 27, 2023 |
| Timi          | Redmi Book Pro 14 2022      | [8f85c500ec](https://linux-hardware.org/?probe=8f85c500ec) | Aug 27, 2023 |
| ASUSTek       | K55VD                       | [eadc869c4b](https://linux-hardware.org/?probe=eadc869c4b) | Aug 27, 2023 |
| Lenovo        | ThinkBook 14 G4 IAP 21DH    | [4e5f7a05c6](https://linux-hardware.org/?probe=4e5f7a05c6) | Aug 26, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [72e8fd41af](https://linux-hardware.org/?probe=72e8fd41af) | Aug 26, 2023 |
| Acer          | Aspire E5-573G              | [75836d26df](https://linux-hardware.org/?probe=75836d26df) | Aug 26, 2023 |
| Acer          | Aspire A515-45G             | [c0480c060a](https://linux-hardware.org/?probe=c0480c060a) | Aug 26, 2023 |
| HP            | ProBook 430 G1              | [aa3b7fe20f](https://linux-hardware.org/?probe=aa3b7fe20f) | Aug 26, 2023 |
| Chuwi         | CoreBook X                  | [95548b426e](https://linux-hardware.org/?probe=95548b426e) | Aug 26, 2023 |
| HUAWEI        | BOD-WXX9                    | [8f033793a9](https://linux-hardware.org/?probe=8f033793a9) | Aug 26, 2023 |
| HUAWEI        | BOD-WXX9                    | [0e107ac9bb](https://linux-hardware.org/?probe=0e107ac9bb) | Aug 26, 2023 |
| Chuwi         | CoreBook X                  | [6bd0ecde29](https://linux-hardware.org/?probe=6bd0ecde29) | Aug 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | [a305956d47](https://linux-hardware.org/?probe=a305956d47) | Aug 26, 2023 |
| MSI           | GL73 8RC                    | [5ca33a6111](https://linux-hardware.org/?probe=5ca33a6111) | Aug 26, 2023 |
| HP            | 240 G8 Notebook PC          | [088ef87d1b](https://linux-hardware.org/?probe=088ef87d1b) | Aug 26, 2023 |
| Lenovo        | IdeaPad Z480                | [e0989b8f9e](https://linux-hardware.org/?probe=e0989b8f9e) | Aug 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | [aa3de32445](https://linux-hardware.org/?probe=aa3de32445) | Aug 25, 2023 |
| ASUSTek       | K54HR                       | [5f24b13b35](https://linux-hardware.org/?probe=5f24b13b35) | Aug 25, 2023 |
| Lenovo        | 3000 G530 4151/200          | [a5812138d3](https://linux-hardware.org/?probe=a5812138d3) | Aug 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | [3ce0d3817d](https://linux-hardware.org/?probe=3ce0d3817d) | Aug 25, 2023 |
| HP            | ProBook 430 G5              | [2f5a204e94](https://linux-hardware.org/?probe=2f5a204e94) | Aug 25, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [add8b61fa2](https://linux-hardware.org/?probe=add8b61fa2) | Aug 24, 2023 |
| HP            | 635                         | [4c35f9ca58](https://linux-hardware.org/?probe=4c35f9ca58) | Aug 24, 2023 |
| Timi          | Redmi Book Pro 14 2022      | [298355e334](https://linux-hardware.org/?probe=298355e334) | Aug 24, 2023 |
| Lenovo        | ThinkPad Edge E120 3043A... | [14d6dcc28e](https://linux-hardware.org/?probe=14d6dcc28e) | Aug 24, 2023 |
| Lenovo        | G500 20236                  | [4ec7353bd2](https://linux-hardware.org/?probe=4ec7353bd2) | Aug 24, 2023 |
| Digma         | Pro Fortis M DN15P7-ADXW... | [8b2a8a66d0](https://linux-hardware.org/?probe=8b2a8a66d0) | Aug 24, 2023 |
| Lenovo        | ThinkPad X120e 0611AN2      | [9938e1fbcc](https://linux-hardware.org/?probe=9938e1fbcc) | Aug 24, 2023 |
| HP            | EliteBook 830 G5            | [15c7624753](https://linux-hardware.org/?probe=15c7624753) | Aug 23, 2023 |
| Acer          | Aspire ES1-311              | [93f204808e](https://linux-hardware.org/?probe=93f204808e) | Aug 23, 2023 |
| HUAWEI        | BOM-WXX9                    | [061ecf9479](https://linux-hardware.org/?probe=061ecf9479) | Aug 23, 2023 |
| HP            | Pavilion 15                 | [0228bd6d42](https://linux-hardware.org/?probe=0228bd6d42) | Aug 23, 2023 |
| Digma         | Pro Fortis M DN15P7-ADXW... | [400fb89d1d](https://linux-hardware.org/?probe=400fb89d1d) | Aug 23, 2023 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | [01beb6bf37](https://linux-hardware.org/?probe=01beb6bf37) | Aug 23, 2023 |
| ANCOMP        | LearnMate A15-501           | [f886cf8a23](https://linux-hardware.org/?probe=f886cf8a23) | Aug 23, 2023 |
| HUAWEI        | BOM-WXX9                    | [08801db21d](https://linux-hardware.org/?probe=08801db21d) | Aug 23, 2023 |
| HUAWEI        | BOM-WXX9                    | [9b3cf2a525](https://linux-hardware.org/?probe=9b3cf2a525) | Aug 23, 2023 |
| ASUSTek       | X507UB                      | [6c8e9739d4](https://linux-hardware.org/?probe=6c8e9739d4) | Aug 23, 2023 |
| Yadro Clie... | KVADRA LE15T                | [985b61f2b2](https://linux-hardware.org/?probe=985b61f2b2) | Aug 23, 2023 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [e3c7a7a5b3](https://linux-hardware.org/?probe=e3c7a7a5b3) | Aug 22, 2023 |
| Infinix       | INBOOK X2                   | [297d07a2e3](https://linux-hardware.org/?probe=297d07a2e3) | Aug 22, 2023 |
| COLORFUL      | X15 XS 22                   | [2e8aa13f76](https://linux-hardware.org/?probe=2e8aa13f76) | Aug 22, 2023 |
| HUAWEI        | BOM-WXX9                    | [10a345d2ef](https://linux-hardware.org/?probe=10a345d2ef) | Aug 22, 2023 |
| Valve         | Jupiter                     | [a83e32b89c](https://linux-hardware.org/?probe=a83e32b89c) | Aug 22, 2023 |
| HP            | Laptop 15-dw3xxx            | [6ca5d6cce7](https://linux-hardware.org/?probe=6ca5d6cce7) | Aug 22, 2023 |
| Lenovo        | B590 20206                  | [d3b3052832](https://linux-hardware.org/?probe=d3b3052832) | Aug 22, 2023 |
| HP            | ProBook 655 G1              | [39dbb86112](https://linux-hardware.org/?probe=39dbb86112) | Aug 22, 2023 |
| HP            | ProBook 655 G1              | [2d616412f1](https://linux-hardware.org/?probe=2d616412f1) | Aug 22, 2023 |
| Acer          | Aspire ES1-512              | [cb2839d263](https://linux-hardware.org/?probe=cb2839d263) | Aug 22, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [af048c393b](https://linux-hardware.org/?probe=af048c393b) | Aug 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [60c353baa1](https://linux-hardware.org/?probe=60c353baa1) | Aug 22, 2023 |
| HP            | ProBook 455 G8 Notebook ... | [7687b9e74a](https://linux-hardware.org/?probe=7687b9e74a) | Aug 22, 2023 |
| Irbis         | NB123                       | [6bfbd824c3](https://linux-hardware.org/?probe=6bfbd824c3) | Aug 22, 2023 |
| MSI           | Modern 14 C12M              | [86efcd3eb7](https://linux-hardware.org/?probe=86efcd3eb7) | Aug 21, 2023 |
| HONOR         | NMH-WDX9                    | [edc1d99b63](https://linux-hardware.org/?probe=edc1d99b63) | Aug 21, 2023 |
| HUAWEI        | BOM-WXX9                    | [3bea77516f](https://linux-hardware.org/?probe=3bea77516f) | Aug 21, 2023 |
| Sony          | VPCEH2J9R                   | [a919beee79](https://linux-hardware.org/?probe=a919beee79) | Aug 21, 2023 |
| HP            | EliteBook 835 13 inch G9... | [f973c9678d](https://linux-hardware.org/?probe=f973c9678d) | Aug 20, 2023 |
| Lenovo        | Legion R9000P2021H 82JQ     | [30f233a018](https://linux-hardware.org/?probe=30f233a018) | Aug 20, 2023 |
| HONOR         | BBR-WAX9                    | [1d013fbf4b](https://linux-hardware.org/?probe=1d013fbf4b) | Aug 20, 2023 |
| HP            | Pavilion Notebook           | [bc9275cc73](https://linux-hardware.org/?probe=bc9275cc73) | Aug 20, 2023 |
| Dell          | Inspiron 11-3157            | [eae8586474](https://linux-hardware.org/?probe=eae8586474) | Aug 20, 2023 |
| HP            | Laptop 17-by1xxx            | [658e65bba8](https://linux-hardware.org/?probe=658e65bba8) | Aug 20, 2023 |
| ROMBICA       | myBook Eclipse              | [01efda8d0a](https://linux-hardware.org/?probe=01efda8d0a) | Aug 20, 2023 |
| HUAWEI        | KLVD-WXX9                   | [8d8d50eabc](https://linux-hardware.org/?probe=8d8d50eabc) | Aug 20, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [b0580e41dc](https://linux-hardware.org/?probe=b0580e41dc) | Aug 20, 2023 |
| HUAWEI        | BOD-WXX9                    | [a3dc3ffc3b](https://linux-hardware.org/?probe=a3dc3ffc3b) | Aug 20, 2023 |
| Infomash      | RoverBook                   | [a105ac22d7](https://linux-hardware.org/?probe=a105ac22d7) | Aug 20, 2023 |
| HP            | Laptop 15s-eq2xxx           | [34f09bffb0](https://linux-hardware.org/?probe=34f09bffb0) | Aug 20, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [8838204e5f](https://linux-hardware.org/?probe=8838204e5f) | Aug 20, 2023 |
| HP            | Laptop 15s-eq2xxx           | [398280327e](https://linux-hardware.org/?probe=398280327e) | Aug 19, 2023 |
| HP            | Pavilion 17                 | [c6a4bc6b75](https://linux-hardware.org/?probe=c6a4bc6b75) | Aug 19, 2023 |
| HUAWEI        | BOD-WXX9                    | [dc1060bc0d](https://linux-hardware.org/?probe=dc1060bc0d) | Aug 19, 2023 |
| HUAWEI        | BOD-WXX9                    | [74c4c66eba](https://linux-hardware.org/?probe=74c4c66eba) | Aug 19, 2023 |
| Notebook      | WA50SRQ                     | [615e7be12b](https://linux-hardware.org/?probe=615e7be12b) | Aug 19, 2023 |
| Packard Be... | EasyNote ENTF71BM           | [36417c2601](https://linux-hardware.org/?probe=36417c2601) | Aug 19, 2023 |
| Lenovo        | ThinkPad SL510 28477MG      | [ed572b9b04](https://linux-hardware.org/?probe=ed572b9b04) | Aug 19, 2023 |
| Packard Be... | EasyNote ENTF71BM           | [81dd9b9a7a](https://linux-hardware.org/?probe=81dd9b9a7a) | Aug 19, 2023 |
| HP            | 630                         | [ad9f585249](https://linux-hardware.org/?probe=ad9f585249) | Aug 19, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [651f263a9d](https://linux-hardware.org/?probe=651f263a9d) | Aug 19, 2023 |
| HUAWEI        | NBM-WXX9                    | [ac85dd7bb4](https://linux-hardware.org/?probe=ac85dd7bb4) | Aug 19, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [6a0b53d7c1](https://linux-hardware.org/?probe=6a0b53d7c1) | Aug 18, 2023 |
| Notebook      | WA50SRQ                     | [5970fa0344](https://linux-hardware.org/?probe=5970fa0344) | Aug 18, 2023 |
| Lenovo        | IdeaPad Slim 3 15ABR8 82... | [12c6ae9006](https://linux-hardware.org/?probe=12c6ae9006) | Aug 18, 2023 |
| ANCOMP        | LearnMate A15-501           | [cf541ae2bd](https://linux-hardware.org/?probe=cf541ae2bd) | Aug 18, 2023 |
| HP            | Pavilion 15                 | [83dfd08b75](https://linux-hardware.org/?probe=83dfd08b75) | Aug 18, 2023 |
| MSI           | MS-1057                     | [081ae63942](https://linux-hardware.org/?probe=081ae63942) | Aug 18, 2023 |
| MSI           | MS-1057                     | [615f03f3b8](https://linux-hardware.org/?probe=615f03f3b8) | Aug 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | [417f4d6d5b](https://linux-hardware.org/?probe=417f4d6d5b) | Aug 17, 2023 |
| HP            | Pavilion g6                 | [085d83c79a](https://linux-hardware.org/?probe=085d83c79a) | Aug 17, 2023 |
| HUAWEI        | NBD-WXX9                    | [3a7f4ca491](https://linux-hardware.org/?probe=3a7f4ca491) | Aug 17, 2023 |
| HUAWEI        | BOM-WXX9                    | [e2078f93dd](https://linux-hardware.org/?probe=e2078f93dd) | Aug 17, 2023 |
| Positivo      | N6440                       | [66e9ee4711](https://linux-hardware.org/?probe=66e9ee4711) | Aug 17, 2023 |
| Sony          | VGN-NW2SRF_S                | [93a310f950](https://linux-hardware.org/?probe=93a310f950) | Aug 17, 2023 |
| Positivo      | N6440                       | [3516f8d728](https://linux-hardware.org/?probe=3516f8d728) | Aug 17, 2023 |
| Acer          | Aspire E5-575G              | [1bca67f78b](https://linux-hardware.org/?probe=1bca67f78b) | Aug 17, 2023 |
| Lenovo        | ThinkPad X220 4291MW5       | [adf4aceec8](https://linux-hardware.org/?probe=adf4aceec8) | Aug 17, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [cfe21994b6](https://linux-hardware.org/?probe=cfe21994b6) | Aug 17, 2023 |
| Unknown       | Toshiba AC100 / Dynabook... | [98629bd8c4](https://linux-hardware.org/?probe=98629bd8c4) | Aug 17, 2023 |
| MSI           | GF75 Thin 9SCSR             | [365fe49e34](https://linux-hardware.org/?probe=365fe49e34) | Aug 17, 2023 |
| Packard Be... | EasyNote TE11HC             | [f69a3b4363](https://linux-hardware.org/?probe=f69a3b4363) | Aug 17, 2023 |
| HP            | Laptop 15-bs1xx             | [8933be3bc7](https://linux-hardware.org/?probe=8933be3bc7) | Aug 16, 2023 |
| Packard Be... | EasyNote TS11HR             | [fb77a4db86](https://linux-hardware.org/?probe=fb77a4db86) | Aug 16, 2023 |
| Acer          | Aspire E5-575G              | [131eb14e26](https://linux-hardware.org/?probe=131eb14e26) | Aug 16, 2023 |
| Packard Be... | EasyNote TE11HC             | [af4abf9f1d](https://linux-hardware.org/?probe=af4abf9f1d) | Aug 16, 2023 |
| ASUSTek       | X541NA                      | [8e3f72e46d](https://linux-hardware.org/?probe=8e3f72e46d) | Aug 16, 2023 |
| Timi          | A35S                        | [7f78fd50bd](https://linux-hardware.org/?probe=7f78fd50bd) | Aug 16, 2023 |
| Acer          | Aspire A315-56              | [ea88be85a3](https://linux-hardware.org/?probe=ea88be85a3) | Aug 16, 2023 |
| A-DATA Tec... | XENIA 14                    | [59faf4a458](https://linux-hardware.org/?probe=59faf4a458) | Aug 15, 2023 |
| A-DATA Tec... | XENIA 14                    | [537cce8a8e](https://linux-hardware.org/?probe=537cce8a8e) | Aug 15, 2023 |
| MSI           | X460/X460DX                 | [2e5d1c9b46](https://linux-hardware.org/?probe=2e5d1c9b46) | Aug 15, 2023 |
| Acer          | Aspire A315-21G             | [b74079b9cd](https://linux-hardware.org/?probe=b74079b9cd) | Aug 15, 2023 |
| Lenovo        | ThinkPad X390 20Q1A005CD    | [c299d4ad92](https://linux-hardware.org/?probe=c299d4ad92) | Aug 15, 2023 |
| Lenovo        | G580 20157                  | [3156a63d06](https://linux-hardware.org/?probe=3156a63d06) | Aug 15, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [6c933602ca](https://linux-hardware.org/?probe=6c933602ca) | Aug 15, 2023 |
| Lenovo        | ThinkPad X120e 0611AN2      | [3750dc2cb1](https://linux-hardware.org/?probe=3750dc2cb1) | Aug 15, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [618b4d5598](https://linux-hardware.org/?probe=618b4d5598) | Aug 15, 2023 |
| Fujitsu Si... | AMILO Li 2727               | [fd38ce192c](https://linux-hardware.org/?probe=fd38ce192c) | Aug 15, 2023 |
| Dell          | Studio 1735                 | [ff082d7af8](https://linux-hardware.org/?probe=ff082d7af8) | Aug 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [52bd9574d8](https://linux-hardware.org/?probe=52bd9574d8) | Aug 14, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [85ce620e44](https://linux-hardware.org/?probe=85ce620e44) | Aug 14, 2023 |
| ASUSTek       | TUF Gaming FX705DY_FX705... | [4062060fba](https://linux-hardware.org/?probe=4062060fba) | Aug 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [74eb1759e1](https://linux-hardware.org/?probe=74eb1759e1) | Aug 14, 2023 |
| Acer          | Aspire V3-571G              | [1d96e3b473](https://linux-hardware.org/?probe=1d96e3b473) | Aug 13, 2023 |
| Dell          | Inspiron 3542               | [ae586a02aa](https://linux-hardware.org/?probe=ae586a02aa) | Aug 13, 2023 |
| Acer          | Swift SF314-43              | [e0b2f87734](https://linux-hardware.org/?probe=e0b2f87734) | Aug 13, 2023 |
| Maibenben     | MaiBook X series            | [823d437123](https://linux-hardware.org/?probe=823d437123) | Aug 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [307eb30c27](https://linux-hardware.org/?probe=307eb30c27) | Aug 13, 2023 |
| Lenovo        | ThinkPad T470 20HES0MV00    | [f709dd85f7](https://linux-hardware.org/?probe=f709dd85f7) | Aug 13, 2023 |
| HONOR         | NMH-WCX9                    | [788c2c9e31](https://linux-hardware.org/?probe=788c2c9e31) | Aug 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [7d7349fef7](https://linux-hardware.org/?probe=7d7349fef7) | Aug 12, 2023 |
| Irbis         | NB264                       | [ed38bccd6d](https://linux-hardware.org/?probe=ed38bccd6d) | Aug 12, 2023 |
| ASUSTek       | K53TK                       | [db9f130ade](https://linux-hardware.org/?probe=db9f130ade) | Aug 12, 2023 |
| Acer          | Aspire E1-571G              | [ca51aaad9f](https://linux-hardware.org/?probe=ca51aaad9f) | Aug 12, 2023 |
| ASUSTek       | T200TA                      | [affc999457](https://linux-hardware.org/?probe=affc999457) | Aug 12, 2023 |
| ASUSTek       | T200TA                      | [24d6504b2c](https://linux-hardware.org/?probe=24d6504b2c) | Aug 12, 2023 |
| Apple         | MacBookAir7,2               | [b80181bc47](https://linux-hardware.org/?probe=b80181bc47) | Aug 12, 2023 |
| HP            | ENVY Notebook               | [24c2810def](https://linux-hardware.org/?probe=24c2810def) | Aug 12, 2023 |
| Lenovo        | PIQY0                       | [0149927d91](https://linux-hardware.org/?probe=0149927d91) | Aug 11, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [377a0e25aa](https://linux-hardware.org/?probe=377a0e25aa) | Aug 11, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | [c2d9d3160b](https://linux-hardware.org/?probe=c2d9d3160b) | Aug 11, 2023 |
| MSI           | Sword 17 A11UD              | [8ad81394c8](https://linux-hardware.org/?probe=8ad81394c8) | Aug 11, 2023 |
| HP            | ENVY Notebook               | [6327abde35](https://linux-hardware.org/?probe=6327abde35) | Aug 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | [a4a009cd79](https://linux-hardware.org/?probe=a4a009cd79) | Aug 11, 2023 |
| HP            | Pavilion 15                 | [0f7859844f](https://linux-hardware.org/?probe=0f7859844f) | Aug 11, 2023 |
| Acer          | Extensa 2511G               | [536699834a](https://linux-hardware.org/?probe=536699834a) | Aug 11, 2023 |
| Acer          | Nitro AN515-52              | [c9b1265a23](https://linux-hardware.org/?probe=c9b1265a23) | Aug 11, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [7d63566e0a](https://linux-hardware.org/?probe=7d63566e0a) | Aug 11, 2023 |
| ASUSTek       | ZenBook UX535LI_UX535LI     | [29065a56ee](https://linux-hardware.org/?probe=29065a56ee) | Aug 11, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [46ae462027](https://linux-hardware.org/?probe=46ae462027) | Aug 11, 2023 |
| Fujitsu Si... | AMILO Li 2727               | [1dc2c421f8](https://linux-hardware.org/?probe=1dc2c421f8) | Aug 11, 2023 |
| HP            | Pavilion 15                 | [3de983a470](https://linux-hardware.org/?probe=3de983a470) | Aug 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [80f2f711d8](https://linux-hardware.org/?probe=80f2f711d8) | Aug 10, 2023 |
| Toshiba       | Satellite C660              | [26597d8a51](https://linux-hardware.org/?probe=26597d8a51) | Aug 10, 2023 |
| Acer          | Extensa 5630                | [1cc3eaf69a](https://linux-hardware.org/?probe=1cc3eaf69a) | Aug 10, 2023 |
| Acer          | Aspire V3-571G              | [6c4354fa1c](https://linux-hardware.org/?probe=6c4354fa1c) | Aug 10, 2023 |
| HP            | ENVY Notebook               | [9e8624aa8d](https://linux-hardware.org/?probe=9e8624aa8d) | Aug 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X321... | [204b2fa0a0](https://linux-hardware.org/?probe=204b2fa0a0) | Aug 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [70765ac17b](https://linux-hardware.org/?probe=70765ac17b) | Aug 09, 2023 |
| HP            | Pavilion 15                 | [8636764a35](https://linux-hardware.org/?probe=8636764a35) | Aug 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [f28e4b71d6](https://linux-hardware.org/?probe=f28e4b71d6) | Aug 09, 2023 |
| Chuwi         | GemiBook Pro                | [3702186068](https://linux-hardware.org/?probe=3702186068) | Aug 08, 2023 |
| ARDOR GAMI... | V15x_V17xPNKPNJPNH          | [77f61b77f5](https://linux-hardware.org/?probe=77f61b77f5) | Aug 08, 2023 |
| ASUSTek       | X501U                       | [1cd218236c](https://linux-hardware.org/?probe=1cd218236c) | Aug 08, 2023 |
| ARDOR GAMI... | V15x_V17xPNKPNJPNH          | [fa4f74161f](https://linux-hardware.org/?probe=fa4f74161f) | Aug 08, 2023 |
| HUAWEI        | BOHB-WAX9                   | [42303ab8af](https://linux-hardware.org/?probe=42303ab8af) | Aug 08, 2023 |
| Dell          | Precision M4700             | [95ac580b0d](https://linux-hardware.org/?probe=95ac580b0d) | Aug 08, 2023 |
| HP            | ENVY Notebook               | [9c6d8ac7f9](https://linux-hardware.org/?probe=9c6d8ac7f9) | Aug 08, 2023 |
| Dell          | Latitude 5511               | [e9ea435e85](https://linux-hardware.org/?probe=e9ea435e85) | Aug 08, 2023 |
| Acer          | Extensa 215-51K             | [27a26187b9](https://linux-hardware.org/?probe=27a26187b9) | Aug 08, 2023 |
| HP            | Presario CQ58               | [07f5cdfaa8](https://linux-hardware.org/?probe=07f5cdfaa8) | Aug 08, 2023 |
| Acer          | Aspire E5-573G              | [305061b67e](https://linux-hardware.org/?probe=305061b67e) | Aug 08, 2023 |
| Samsung       | R528/R728                   | [cc6458fab9](https://linux-hardware.org/?probe=cc6458fab9) | Aug 08, 2023 |
| Jumper        | QCYL-200                    | [24da6190dc](https://linux-hardware.org/?probe=24da6190dc) | Aug 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [36b0caba9e](https://linux-hardware.org/?probe=36b0caba9e) | Aug 07, 2023 |
| Acer          | Aspire A315-42G             | [eff926e4a9](https://linux-hardware.org/?probe=eff926e4a9) | Aug 07, 2023 |
| Echips Imp... | NQ15E                       | [7d5e97a545](https://linux-hardware.org/?probe=7d5e97a545) | Aug 07, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [36c52dfe36](https://linux-hardware.org/?probe=36c52dfe36) | Aug 07, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [be823adc05](https://linux-hardware.org/?probe=be823adc05) | Aug 07, 2023 |
| ASUSTek       | X751NV                      | [ff33d23814](https://linux-hardware.org/?probe=ff33d23814) | Aug 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | [bd036e1e65](https://linux-hardware.org/?probe=bd036e1e65) | Aug 07, 2023 |
| Dell          | XPS 15 9500                 | [dbefafc94d](https://linux-hardware.org/?probe=dbefafc94d) | Aug 07, 2023 |
| Dell          | Inspiron N5110              | [52c9bb6c33](https://linux-hardware.org/?probe=52c9bb6c33) | Aug 06, 2023 |
| ASUSTek       | UX32VD                      | [298a3261a0](https://linux-hardware.org/?probe=298a3261a0) | Aug 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [2771828543](https://linux-hardware.org/?probe=2771828543) | Aug 06, 2023 |
| Timi          | TM1701                      | [2fc0a44940](https://linux-hardware.org/?probe=2fc0a44940) | Aug 06, 2023 |
| ASUSTek       | X550CC                      | [0a99f6f654](https://linux-hardware.org/?probe=0a99f6f654) | Aug 06, 2023 |
| TECNO         | MEGABOOK T1                 | [ced0647d42](https://linux-hardware.org/?probe=ced0647d42) | Aug 06, 2023 |
| ASUSTek       | X550CC                      | [23298de8c1](https://linux-hardware.org/?probe=23298de8c1) | Aug 06, 2023 |
| Valve         | Jupiter                     | [6bf7b7dc2b](https://linux-hardware.org/?probe=6bf7b7dc2b) | Aug 05, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [efe021e3b5](https://linux-hardware.org/?probe=efe021e3b5) | Aug 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | [5f516e849d](https://linux-hardware.org/?probe=5f516e849d) | Aug 05, 2023 |
| Chuwi         | CoreBook XPro               | [776bcc618a](https://linux-hardware.org/?probe=776bcc618a) | Aug 05, 2023 |
| ASUSTek       | N53SV                       | [2c4db62652](https://linux-hardware.org/?probe=2c4db62652) | Aug 05, 2023 |
| Acer          | Aspire A715-72G             | [c95d1a55cd](https://linux-hardware.org/?probe=c95d1a55cd) | Aug 05, 2023 |
| MSI           | GE70 0NC                    | [c9fd935b80](https://linux-hardware.org/?probe=c9fd935b80) | Aug 05, 2023 |
| HP            | EliteBook 830 G5            | [d4ebcfaf3d](https://linux-hardware.org/?probe=d4ebcfaf3d) | Aug 05, 2023 |
| HP            | EliteBook 830 G5            | [cf67e6a006](https://linux-hardware.org/?probe=cf67e6a006) | Aug 05, 2023 |
| ASUSTek       | 1215N                       | [35853f5b92](https://linux-hardware.org/?probe=35853f5b92) | Aug 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [7abc08a315](https://linux-hardware.org/?probe=7abc08a315) | Aug 04, 2023 |
| Dell          | Vostro 5515                 | [bd17eec0e3](https://linux-hardware.org/?probe=bd17eec0e3) | Aug 04, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [59dda0e2b7](https://linux-hardware.org/?probe=59dda0e2b7) | Aug 04, 2023 |
| Dell          | Latitude E6510              | [b32213c71d](https://linux-hardware.org/?probe=b32213c71d) | Aug 03, 2023 |
| Samsung       | 305U1A                      | [f65d34a8fb](https://linux-hardware.org/?probe=f65d34a8fb) | Aug 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [2b8f90f79d](https://linux-hardware.org/?probe=2b8f90f79d) | Aug 03, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [7d96f87e00](https://linux-hardware.org/?probe=7d96f87e00) | Aug 03, 2023 |
| Notebook      | W54_W94_W955TU,-T,-C        | [1f1f14320c](https://linux-hardware.org/?probe=1f1f14320c) | Aug 03, 2023 |
| Panasonic     | CF-31WBLAXLM                | [580b017d88](https://linux-hardware.org/?probe=580b017d88) | Aug 03, 2023 |
| MSI           | Prestige 14Evo A12M         | [c9e4b6dd90](https://linux-hardware.org/?probe=c9e4b6dd90) | Aug 03, 2023 |
| MSI           | Modern 14 C12M              | [aa352b05aa](https://linux-hardware.org/?probe=aa352b05aa) | Aug 03, 2023 |
| ASUSTek       | 1015BX                      | [4770dbfc22](https://linux-hardware.org/?probe=4770dbfc22) | Aug 02, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [a1f99c3e4d](https://linux-hardware.org/?probe=a1f99c3e4d) | Aug 02, 2023 |
| Acer          | Aspire A715-71G             | [fabe23f1a8](https://linux-hardware.org/?probe=fabe23f1a8) | Aug 02, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [28ff7ce482](https://linux-hardware.org/?probe=28ff7ce482) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [e3f2347cf7](https://linux-hardware.org/?probe=e3f2347cf7) | Aug 02, 2023 |
| Sony          | VPCSB1V9R                   | [8d809c3877](https://linux-hardware.org/?probe=8d809c3877) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [2f4ed3cb1f](https://linux-hardware.org/?probe=2f4ed3cb1f) | Aug 02, 2023 |
| Unknown       | Unknown                     | [41ff18df05](https://linux-hardware.org/?probe=41ff18df05) | Aug 02, 2023 |
| Unknown       | Unknown                     | [eb3d428d41](https://linux-hardware.org/?probe=eb3d428d41) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [4a6b173235](https://linux-hardware.org/?probe=4a6b173235) | Aug 01, 2023 |
| Acer          | Aspire A315-23              | [ef1917aa93](https://linux-hardware.org/?probe=ef1917aa93) | Aug 01, 2023 |
| Dell          | Vostro 3500                 | [266d25478e](https://linux-hardware.org/?probe=266d25478e) | Aug 01, 2023 |
| Acer          | Aspire A315-23              | [9164151f28](https://linux-hardware.org/?probe=9164151f28) | Aug 01, 2023 |
| Dell          | Inspiron 5567               | [d252fa93be](https://linux-hardware.org/?probe=d252fa93be) | Aug 01, 2023 |
| Timi          | Xiaomi Book Pro 16 2022     | [1e963cc76b](https://linux-hardware.org/?probe=1e963cc76b) | Aug 01, 2023 |
| Teclast       | Tbolt 10 DG                 | [cd75496056](https://linux-hardware.org/?probe=cd75496056) | Aug 01, 2023 |
| Acer          | Aspire A715-71G             | [7f3c7327b7](https://linux-hardware.org/?probe=7f3c7327b7) | Aug 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [f7be9307b1](https://linux-hardware.org/?probe=f7be9307b1) | Jul 31, 2023 |
| Toshiba       | Satellite C870-D7K          | [9e8acac201](https://linux-hardware.org/?probe=9e8acac201) | Jul 31, 2023 |
| Acer          | Aspire V3-551G              | [a90eeb2fa3](https://linux-hardware.org/?probe=a90eeb2fa3) | Jul 31, 2023 |
| Dell          | G15 5511                    | [278d65cdc0](https://linux-hardware.org/?probe=278d65cdc0) | Jul 31, 2023 |
| Lenovo        | G580 20150                  | [81ab0317ab](https://linux-hardware.org/?probe=81ab0317ab) | Jul 31, 2023 |
| ASUSTek       | X411UA                      | [9ceaa9062e](https://linux-hardware.org/?probe=9ceaa9062e) | Jul 31, 2023 |
| Dell          | G15 5511                    | [e4570caa8f](https://linux-hardware.org/?probe=e4570caa8f) | Jul 31, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [c42c13e7be](https://linux-hardware.org/?probe=c42c13e7be) | Jul 31, 2023 |
| Samsung       | 300V3A/300V4A/300V5A        | [a757cca527](https://linux-hardware.org/?probe=a757cca527) | Jul 31, 2023 |
| ASUSTek       | F3Se                        | [e5f8a806ea](https://linux-hardware.org/?probe=e5f8a806ea) | Jul 31, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [8a2a5c6265](https://linux-hardware.org/?probe=8a2a5c6265) | Jul 30, 2023 |
| Acer          | Aspire A315-56              | [522c7e4381](https://linux-hardware.org/?probe=522c7e4381) | Jul 30, 2023 |
| Acer          | Aspire E5-573G              | [14307e0b7e](https://linux-hardware.org/?probe=14307e0b7e) | Jul 30, 2023 |
| HUAWEI        | BOM-WXX9                    | [583bc42f4e](https://linux-hardware.org/?probe=583bc42f4e) | Jul 30, 2023 |
| Timi          | Redmi Book Pro 14 2022      | [71379f70f2](https://linux-hardware.org/?probe=71379f70f2) | Jul 30, 2023 |
| Unknown       | Unknown                     | [b5f5ef27a8](https://linux-hardware.org/?probe=b5f5ef27a8) | Jul 30, 2023 |
| HP            | Pavilion dv6                | [2046d205d6](https://linux-hardware.org/?probe=2046d205d6) | Jul 30, 2023 |
| Dell          | Vostro A860                 | [0148ba9cdc](https://linux-hardware.org/?probe=0148ba9cdc) | Jul 30, 2023 |
| HP            | 250 G7 Notebook PC          | [cefd14313d](https://linux-hardware.org/?probe=cefd14313d) | Jul 30, 2023 |
| HP            | Pavilion dv7                | [cdf06f1680](https://linux-hardware.org/?probe=cdf06f1680) | Jul 30, 2023 |
| HONOR         | NBR-WAX9                    | [b69caa0c17](https://linux-hardware.org/?probe=b69caa0c17) | Jul 29, 2023 |
| HONOR         | NBR-WAX9                    | [d7434fdb2a](https://linux-hardware.org/?probe=d7434fdb2a) | Jul 29, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | [c3523b3823](https://linux-hardware.org/?probe=c3523b3823) | Jul 29, 2023 |
| Sony          | SVS13A1Z9RN                 | [533b3018ea](https://linux-hardware.org/?probe=533b3018ea) | Jul 29, 2023 |
| Lenovo        | Unknown                     | [d43f4e6715](https://linux-hardware.org/?probe=d43f4e6715) | Jul 29, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [ea4fee91b6](https://linux-hardware.org/?probe=ea4fee91b6) | Jul 28, 2023 |
| ASUSTek       | X411UA                      | [0126e6254a](https://linux-hardware.org/?probe=0126e6254a) | Jul 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [cb17388b8c](https://linux-hardware.org/?probe=cb17388b8c) | Jul 28, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [03b716e2bf](https://linux-hardware.org/?probe=03b716e2bf) | Jul 28, 2023 |
| HP            | OMEN by Laptop 17-cb1xxx    | [b24aea2d95](https://linux-hardware.org/?probe=b24aea2d95) | Jul 28, 2023 |
| Acer          | Aspire A517-53              | [41c9602cac](https://linux-hardware.org/?probe=41c9602cac) | Jul 28, 2023 |
| Acer          | Aspire A315-21G             | [0a4e1c4510](https://linux-hardware.org/?probe=0a4e1c4510) | Jul 28, 2023 |
| Acer          | Extensa 215-32              | [18d32a6c36](https://linux-hardware.org/?probe=18d32a6c36) | Jul 27, 2023 |
| Lenovo        | ThinkPad E490 20N80029RT    | [69cf27eaae](https://linux-hardware.org/?probe=69cf27eaae) | Jul 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [1b3e699a2a](https://linux-hardware.org/?probe=1b3e699a2a) | Jul 27, 2023 |
| Dell          | Inspiron 1520               | [a119f99239](https://linux-hardware.org/?probe=a119f99239) | Jul 27, 2023 |
| Valve         | Jupiter                     | [7ca21b7b46](https://linux-hardware.org/?probe=7ca21b7b46) | Jul 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [b8b95820c1](https://linux-hardware.org/?probe=b8b95820c1) | Jul 26, 2023 |
| HP            | Laptop 14s-dq0xxx           | [dc484f95af](https://linux-hardware.org/?probe=dc484f95af) | Jul 26, 2023 |

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
| ROSA R10         | 1494      | 10.18%  |
| ROSA R11         | 1444      | 9.84%   |
| ROSA R8.1        | 1043      | 7.11%   |
| ROSA R8          | 920       | 6.27%   |
| ROSA R9          | 846       | 5.76%   |
| ROSA R11.1       | 796       | 5.42%   |
| ROSA 12.2        | 784       | 5.34%   |
| Ubuntu 20.04     | 489       | 3.33%   |
| ROSA 12.4        | 391       | 2.66%   |
| ROSA 12.3        | 357       | 2.43%   |
| Ubuntu 22.04     | 286       | 1.95%   |
| Debian 11        | 281       | 1.91%   |
| Ubuntu 18.04     | 256       | 1.74%   |
| Arch Rolling     | 164       | 1.12%   |
| OpenMandriva 4.2 | 160       | 1.09%   |
| ROSA 12.1        | 116       | 0.79%   |
| Fedora 37        | 106       | 0.72%   |
| KDE neon 20.04   | 104       | 0.71%   |
| OpenMandriva 4.3 | 102       | 0.69%   |
| Fedora 38        | 101       | 0.69%   |
| Debian 12        | 101       | 0.69%   |
| Arch             | 98        | 0.67%   |
| Manjaro          | 97        | 0.66%   |
| Fedora 36        | 94        | 0.64%   |
| Linux Mint 19.3  | 85        | 0.58%   |
| Linux Mint 20.3  | 73        | 0.5%    |
| Fedora 35        | 71        | 0.48%   |
| ROSA 12          | 70        | 0.48%   |
| Linux Mint 20.1  | 69        | 0.47%   |
| Kubuntu 20.04    | 63        | 0.43%   |
| Debian 10        | 60        | 0.41%   |
| Linux Mint 20    | 59        | 0.4%    |
| Linux Mint 19.1  | 59        | 0.4%    |
| Linux Mint 18.3  | 59        | 0.4%    |
| ALT Linux 10.1   | 59        | 0.4%    |
| Fedora 34        | 57        | 0.39%   |
| Linux Mint 19.2  | 55        | 0.37%   |
| Kometa P10       | 54        | 0.37%   |
| Ubuntu 21.10     | 52        | 0.35%   |
| Xubuntu 20.04    | 51        | 0.35%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| ROSA          | 7107      | 54.37%  |
| Ubuntu        | 1330      | 10.18%  |
| Linux Mint    | 665       | 5.09%   |
| Fedora        | 501       | 3.83%   |
| Debian        | 453       | 3.47%   |
| OpenMandriva  | 395       | 3.02%   |
| Manjaro       | 361       | 2.76%   |
| ALT Linux     | 253       | 1.94%   |
| Arch          | 250       | 1.91%   |
| Endless       | 216       | 1.65%   |
| Kubuntu       | 164       | 1.25%   |
| KDE neon      | 147       | 1.12%   |
| Xubuntu       | 131       | 1%      |
| Red OS        | 110       | 0.84%   |
| Pop!_OS       | 103       | 0.79%   |
| Kali          | 75        | 0.57%   |
| Gentoo        | 68        | 0.52%   |
| Elementary    | 68        | 0.52%   |
| openSUSE      | 55        | 0.42%   |
| Lubuntu       | 48        | 0.37%   |
| RED           | 46        | 0.35%   |
| LMDE          | 42        | 0.32%   |
| Zorin         | 40        | 0.31%   |
| SteamOS       | 40        | 0.31%   |
| Clear Linux   | 34        | 0.26%   |
| Ubuntu MATE   | 33        | 0.25%   |
| ArcoLinux     | 31        | 0.24%   |
| Ubuntu Unity  | 27        | 0.21%   |
| EndeavourOS   | 22        | 0.17%   |
| Astra Linux   | 16        | 0.12%   |
| Artix         | 15        | 0.11%   |
| Ubuntu Budgie | 14        | 0.11%   |
| Parrot        | 14        | 0.11%   |
| MX            | 14        | 0.11%   |
| CentOS        | 13        | 0.1%    |
| RELS          | 11        | 0.08%   |
| Void Linux    | 10        | 0.08%   |
| Nobara        | 9         | 0.07%   |
| Devuan        | 9         | 0.07%   |
| Calculate     | 9         | 0.07%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| 5.10.74-generic-2rosa2021.1-x86_64  | 667       | 4.23%   |
| 4.9.60-nrj-desktop-1rosa-x86_64     | 621       | 3.94%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 621       | 3.94%   |
| 4.9.20-nrj-desktop-1rosa-x86_64     | 586       | 3.71%   |
| 4.1.34-nrj-desktop-2rosa-x86_64     | 350       | 2.22%   |
| 4.9.9-nrj-desktop-1rosa-x86_64      | 278       | 1.76%   |
| 4.9.124-nrj-desktop-1rosa-x86_64    | 275       | 1.74%   |
| 4.1.25-nrj-desktop-1rosa-x86_64     | 236       | 1.5%    |
| 6.1.20-generic-2rosa2021.1-x86_64   | 225       | 1.43%   |
| 4.1.38-nrj-desktop-2rosa-x86_64     | 218       | 1.38%   |
| 4.9.60-nrj-desktop-1rosa-i586       | 200       | 1.27%   |
| 4.9.76-nrj-desktop-1rosa-x86_64     | 175       | 1.11%   |
| 4.9.41-nrj-desktop-1rosa-x86_64     | 175       | 1.11%   |
| 4.9.20-nrj-desktop-1rosa-i586       | 174       | 1.1%    |
| 4.15.0-desktop-45.1rosa-i586        | 174       | 1.1%    |
| 4.15.0-desktop-68.5rosa-x86_64      | 169       | 1.07%   |
| 5.10.14-desktop-1omv4002            | 155       | 0.98%   |
| 5.4.32-generic-2rosa-x86_64         | 148       | 0.94%   |
| 5.10.118-generic-2rosa2021.1-x86_64 | 148       | 0.94%   |
| 4.9.155-nrj-desktop-1rosa-x86_64    | 147       | 0.93%   |
| 4.1.34-nrj-desktop-2rosa-i586       | 146       | 0.93%   |
| 4.15.0-desktop-122.124.1rosa-x86_64 | 140       | 0.89%   |
| 4.15.0-desktop-47.2rosa-x86_64      | 138       | 0.87%   |
| 5.4.83-generic-2rosa-x86_64         | 137       | 0.87%   |
| 5.15.75-generic-1rosa2021.1-x86_64  | 121       | 0.77%   |
| 5.10.0-7-amd64                      | 110       | 0.7%    |
| 4.15.0-desktop-94.1rosa-x86_64      | 107       | 0.68%   |
| 4.1.38-nrj-desktop-2rosa-i586       | 107       | 0.68%   |
| 5.15.79-generic-1rosa2021.1-x86_64  | 97        | 0.61%   |
| 4.9.95-nrj-desktop-2rosa-x86_64     | 96        | 0.61%   |
| 4.9.9-nrj-desktop-1rosa-i586        | 96        | 0.61%   |
| 5.16.7-desktop-1omv4003             | 91        | 0.58%   |
| 4.1.25-nrj-desktop-1rosa-i586       | 90        | 0.57%   |
| 6.1.38-generic-1rosa2021.1-x86_64   | 80        | 0.51%   |
| 4.9.124-nrj-desktop-1rosa-i586      | 78        | 0.49%   |
| 5.4.0-42-generic                    | 71        | 0.45%   |
| 4.15.0-desktop-60.7rosa-x86_64      | 69        | 0.44%   |
| 5.4.32-generic-2rosa-i586           | 63        | 0.4%    |
| 4.9.111-nrj-desktop-2rosa-x86_64    | 59        | 0.37%   |
| 5.15.0-56-generic                   | 58        | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 4.15.0   | 1896      | 12.4%   |
| 4.9.60   | 821       | 5.37%   |
| 4.9.20   | 763       | 4.99%   |
| 5.4.0    | 720       | 4.71%   |
| 5.10.74  | 700       | 4.58%   |
| 4.1.34   | 498       | 3.26%   |
| 5.15.0   | 437       | 2.86%   |
| 4.1.38   | 395       | 2.58%   |
| 4.9.9    | 374       | 2.45%   |
| 4.9.124  | 357       | 2.33%   |
| 5.10.0   | 332       | 2.17%   |
| 4.1.25   | 327       | 2.14%   |
| 5.3.0    | 251       | 1.64%   |
| 4.9.41   | 235       | 1.54%   |
| 6.1.20   | 232       | 1.52%   |
| 4.9.76   | 230       | 1.5%    |
| 5.13.0   | 216       | 1.41%   |
| 5.4.32   | 211       | 1.38%   |
| 5.11.0   | 209       | 1.37%   |
| 4.9.155  | 207       | 1.35%   |
| 5.8.0    | 204       | 1.33%   |
| 5.4.83   | 185       | 1.21%   |
| 5.0.0    | 170       | 1.11%   |
| 5.19.0   | 162       | 1.06%   |
| 5.10.14  | 158       | 1.03%   |
| 5.10.118 | 155       | 1.01%   |
| 5.15.75  | 153       | 1%      |
| 6.2.0    | 149       | 0.97%   |
| 6.1.0    | 131       | 0.86%   |
| 4.9.95   | 124       | 0.81%   |
| 5.15.79  | 101       | 0.66%   |
| 4.18.0   | 95        | 0.62%   |
| 5.16.7   | 93        | 0.61%   |
| 4.13.0   | 93        | 0.61%   |
| 6.1.38   | 90        | 0.59%   |
| 4.9.111  | 81        | 0.53%   |
| 4.19.0   | 73        | 0.48%   |
| 6.2.6    | 65        | 0.42%   |
| 4.9.87   | 58        | 0.38%   |
| 6.1.46   | 56        | 0.37%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.9     | 2898      | 20.11%  |
| 4.15    | 1911      | 13.26%  |
| 5.10    | 1650      | 11.45%  |
| 5.4     | 1247      | 8.65%   |
| 4.1     | 1202      | 8.34%   |
| 5.15    | 1078      | 7.48%   |
| 6.1     | 689       | 4.78%   |
| 6.2     | 305       | 2.12%   |
| 5.3     | 291       | 2.02%   |
| 5.11    | 277       | 1.92%   |
| 5.13    | 276       | 1.92%   |
| 5.8     | 264       | 1.83%   |
| 5.19    | 222       | 1.54%   |
| 5.0     | 178       | 1.24%   |
| 5.16    | 168       | 1.17%   |
| 6.0     | 146       | 1.01%   |
| 5.17    | 131       | 0.91%   |
| 6.4     | 123       | 0.85%   |
| 5.18    | 119       | 0.83%   |
| 4.19    | 114       | 0.79%   |
| 4.18    | 110       | 0.76%   |
| 4.13    | 109       | 0.76%   |
| 5.14    | 100       | 0.69%   |
| 6.5     | 94        | 0.65%   |
| 5.6     | 88        | 0.61%   |
| 6.3     | 76        | 0.53%   |
| 5.9     | 69        | 0.48%   |
| 5.7     | 50        | 0.35%   |
| 4.4     | 50        | 0.35%   |
| 4.16    | 50        | 0.35%   |
| 5.12    | 48        | 0.33%   |
| 5.5     | 41        | 0.28%   |
| 4.8     | 37        | 0.26%   |
| 4.10    | 35        | 0.24%   |
| 3.14    | 20        | 0.14%   |
| 4.14    | 19        | 0.13%   |
| 5.2     | 18        | 0.12%   |
| 3.10    | 16        | 0.11%   |
| 4.17    | 14        | 0.1%    |
| 4.12    | 13        | 0.09%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 11134     | 86.67%  |
| i686    | 1704      | 13.26%  |
| armv7l  | 6         | 0.05%   |
| ppc     | 1         | 0.01%   |
| aarch64 | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| KDE4               | 4163      | 30.58%  |
| KDE5               | 3552      | 26.09%  |
| GNOME              | 2708      | 19.89%  |
| Unknown            | 745       | 5.47%   |
| XFCE               | 545       | 4%      |
| LXQt               | 487       | 3.58%   |
| MATE               | 377       | 2.77%   |
| X-Cinnamon         | 312       | 2.29%   |
| Cinnamon           | 255       | 1.87%   |
| KDE                | 168       | 1.23%   |
| Pantheon           | 65        | 0.48%   |
| i3                 | 45        | 0.33%   |
| LXDE               | 36        | 0.26%   |
| Budgie             | 28        | 0.21%   |
| Unity              | 27        | 0.2%    |
| GNOME Flashback    | 20        | 0.15%   |
| sway               | 13        | 0.1%    |
| fly                | 11        | 0.08%   |
| Deepin             | 9         | 0.07%   |
| awesome            | 6         | 0.04%   |
| icewm              | 5         | 0.04%   |
| DWM                | 5         | 0.04%   |
| Trinity            | 4         | 0.03%   |
| fluxbox            | 4         | 0.03%   |
| bspwm              | 4         | 0.03%   |
| openbox            | 3         | 0.02%   |
| Hyprland           | 3         | 0.02%   |
| GNOME Classic      | 3         | 0.02%   |
| xmonad             | 2         | 0.01%   |
| qtile              | 1         | 0.01%   |
| pantheon-non-gnome | 1         | 0.01%   |
| none+i3            | 1         | 0.01%   |
| Lumina             | 1         | 0.01%   |
| Lubuntu            | 1         | 0.01%   |
| lightdm-xsession   | 1         | 0.01%   |
| Enlightenment      | 1         | 0.01%   |
| DDE                | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| X11         | 10182     | 77.76%  |
| Wayland     | 2382      | 18.19%  |
| Unknown     | 433       | 3.31%   |
| Tty         | 95        | 0.73%   |
| Web         | 1         | 0.01%   |
| Unspecified | 1         | 0.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| KDM     | 4182      | 30.81%  |
| SDDM    | 3598      | 26.51%  |
| Unknown | 2328      | 17.15%  |
| GDM     | 1653      | 12.18%  |
| LightDM | 803       | 5.92%   |
| GDM3    | 512       | 3.77%   |
| TDM     | 433       | 3.19%   |
| MDM     | 21        | 0.15%   |
| XDM     | 17        | 0.13%   |
| SLiM    | 9         | 0.07%   |
| FLY-DM  | 5         | 0.04%   |
| NODM    | 3         | 0.02%   |
| Ly      | 3         | 0.02%   |
| LXDM    | 3         | 0.02%   |
| GREETD  | 3         | 0.02%   |
| SLIMSKI | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| Unknown     | 5823      | 44.08%  |
| ru_RU       | 5663      | 42.87%  |
| en_US       | 1494      | 11.31%  |
| C           | 87        | 0.66%   |
| en_GB       | 59        | 0.45%   |
| ru_RU.UTF_8 | 19        | 0.14%   |
| ru_UA       | 9         | 0.07%   |
| POSIX       | 5         | 0.04%   |
| en_AG       | 5         | 0.04%   |
| zh_CN       | 4         | 0.03%   |
| C.UTF8      | 4         | 0.03%   |
| fr_FR       | 3         | 0.02%   |
| en_DK       | 3         | 0.02%   |
| en_CA       | 3         | 0.02%   |
| de_DE       | 3         | 0.02%   |
| ba_RU       | 3         | 0.02%   |
| uk_UA       | 2         | 0.02%   |
| tr_TR       | 2         | 0.02%   |
| pt_BR       | 2         | 0.02%   |
| it_IT       | 2         | 0.02%   |
| es_ES       | 2         | 0.02%   |
| cv_RU       | 2         | 0.02%   |
| tt_RU       | 1         | 0.01%   |
| ru_RU.UTF8  | 1         | 0.01%   |
| ru_RU.utf-8 | 1         | 0.01%   |
| myv_RU      | 1         | 0.01%   |
| ja_JP       | 1         | 0.01%   |
| en_NZ       | 1         | 0.01%   |
| en_IL       | 1         | 0.01%   |
| en_GB.utf-8 | 1         | 0.01%   |
| en_AU       | 1         | 0.01%   |
| en-US       | 1         | 0.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 7267      | 56.02%  |
| EFI  | 5705      | 43.98%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 8084      | 60.3%   |
| Unknown  | 3581      | 26.71%  |
| Btrfs    | 894       | 6.67%   |
| Overlay  | 586       | 4.37%   |
| Tmpfs    | 82        | 0.61%   |
| Xfs      | 68        | 0.51%   |
| Zfs      | 29        | 0.22%   |
| Ext3     | 21        | 0.16%   |
| Ext2     | 20        | 0.15%   |
| Aufs     | 19        | 0.14%   |
| F2fs     | 12        | 0.09%   |
| Rootfs   | 3         | 0.02%   |
| Reiserfs | 3         | 0.02%   |
| XXXXX    | 2         | 0.01%   |
| XXXXXXX  | 1         | 0.01%   |
| Ufs      | 1         | 0.01%   |
| Jfs      | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 4875      | 36.42%  |
| MBR     | 4799      | 35.85%  |
| Unknown | 3713      | 27.74%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 11555     | 88.27%  |
| Yes       | 1535      | 11.73%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 9473      | 71.81%  |
| Yes       | 3718      | 28.19%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 2292      | 18.03%  |
| ASUSTek Computer    | 2232      | 17.56%  |
| Hewlett-Packard     | 1820      | 14.31%  |
| Acer                | 1722      | 13.54%  |
| Dell                | 878       | 6.91%   |
| Samsung Electronics | 674       | 5.3%    |
| MSI                 | 338       | 2.66%   |
| Toshiba             | 304       | 2.39%   |
| Sony                | 277       | 2.18%   |
| HUAWEI              | 265       | 2.08%   |
| Packard Bell        | 180       | 1.42%   |
| eMachines           | 121       | 0.95%   |
| Clevo               | 115       | 0.9%    |
| Unknown             | 113       | 0.89%   |
| Timi                | 110       | 0.87%   |
| Apple               | 110       | 0.87%   |
| Aquarius            | 83        | 0.65%   |
| Notebook            | 80        | 0.63%   |
| Pegatron            | 63        | 0.5%    |
| HONOR               | 60        | 0.47%   |
| Digma               | 50        | 0.39%   |
| Fujitsu Siemens     | 47        | 0.37%   |
| Valve               | 41        | 0.32%   |
| Fujitsu             | 41        | 0.32%   |
| DNS                 | 39        | 0.31%   |
| Irbis               | 36        | 0.28%   |
| Intel               | 36        | 0.28%   |
| Maibenben           | 34        | 0.27%   |
| DEXP                | 33        | 0.26%   |
| Quanta              | 31        | 0.24%   |
| Prestigio           | 30        | 0.24%   |
| ICL                 | 30        | 0.24%   |
| Chuwi               | 28        | 0.22%   |
| Gigabyte Technology | 21        | 0.17%   |
| Haier               | 19        | 0.15%   |
| 3Logic Group        | 17        | 0.13%   |
| Infinix             | 14        | 0.11%   |
| Insyde              | 13        | 0.1%    |
| Panasonic           | 12        | 0.09%   |
| Kraftway            | 12        | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 193       | 1.52%   |
| HP Pavilion g6                             | 126       | 0.99%   |
| HP Notebook                                | 86        | 0.68%   |
| HP Pavilion dv6                            | 85        | 0.67%   |
| HP Laptop 15-bw0xx                         | 78        | 0.61%   |
| Acer Aspire V3-571G                        | 64        | 0.5%    |
| Lenovo G570 20079                          | 54        | 0.42%   |
| Aquarius NS585                             | 50        | 0.39%   |
| Lenovo B570e HuronRiver Platform           | 48        | 0.38%   |
| Lenovo B590 20206                          | 46        | 0.36%   |
| Clevo NL41MU2                              | 44        | 0.35%   |
| HP Pavilion dv7                            | 42        | 0.33%   |
| Valve Jupiter                              | 41        | 0.32%   |
| HP Pavilion 15                             | 41        | 0.32%   |
| Packard Bell EasyNote TE11HC               | 40        | 0.31%   |
| Lenovo B590 20208                          | 39        | 0.31%   |
| Lenovo G50-45 80E3                         | 36        | 0.28%   |
| Lenovo G500 20236                          | 35        | 0.28%   |
| HUAWEI NBLK-WAX9X                          | 35        | 0.28%   |
| Dell Inspiron N5110                        | 34        | 0.27%   |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B | 33        | 0.26%   |
| HP Pavilion g7                             | 33        | 0.26%   |
| Toshiba Satellite C660                     | 32        | 0.25%   |
| Lenovo G50-30 80G0                         | 32        | 0.25%   |
| ASUS X550CC                                | 32        | 0.25%   |
| ASUS K50IJ                                 | 32        | 0.25%   |
| Lenovo G580 20150                          | 31        | 0.24%   |
| Lenovo B560                                | 31        | 0.24%   |
| ASUS VivoBook 15_ASUS Laptop X540BA        | 31        | 0.24%   |
| Acer Aspire E1-571G                        | 30        | 0.24%   |
| Acer Aspire 5750G                          | 30        | 0.24%   |
| Samsung 355V4C/356V4C/3445VC/3545VC        | 29        | 0.23%   |
| Lenovo G580 20157                          | 29        | 0.23%   |
| Acer Aspire 5742G                          | 29        | 0.23%   |
| Samsung 300E4C/300E5C/300E7C               | 27        | 0.21%   |
| Dell Inspiron 3521                         | 27        | 0.21%   |
| Acer Extensa 2519                          | 26        | 0.2%    |
| HUAWEI BOM-WXX9                            | 25        | 0.2%    |
| HP Pavilion Notebook                       | 25        | 0.2%    |
| Dell Inspiron 3542                         | 25        | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 1172      | 9.22%   |
| Lenovo IdeaPad        | 678       | 5.33%   |
| HP Pavilion           | 516       | 4.06%   |
| Lenovo ThinkPad       | 511       | 4.02%   |
| Dell Inspiron         | 432       | 3.4%    |
| ASUS VivoBook         | 341       | 2.68%   |
| HP Laptop             | 322       | 2.53%   |
| Toshiba Satellite     | 281       | 2.21%   |
| HP ProBook            | 276       | 2.17%   |
| Unknown               | 193       | 1.52%   |
| Dell Latitude         | 173       | 1.36%   |
| Acer Extensa          | 161       | 1.27%   |
| Packard Bell EasyNote | 157       | 1.23%   |
| Dell Vostro           | 122       | 0.96%   |
| HP Compaq             | 100       | 0.79%   |
| HP EliteBook          | 98        | 0.77%   |
| Acer TravelMate       | 98        | 0.77%   |
| HP Notebook           | 87        | 0.68%   |
| Lenovo B590           | 85        | 0.67%   |
| Lenovo G580           | 81        | 0.64%   |
| Lenovo ThinkBook      | 75        | 0.59%   |
| Acer Nitro            | 65        | 0.51%   |
| HP 250                | 59        | 0.46%   |
| Acer Swift            | 57        | 0.45%   |
| Lenovo Legion         | 55        | 0.43%   |
| Lenovo G570           | 55        | 0.43%   |
| ASUS ZenBook          | 54        | 0.42%   |
| ASUS ROG              | 53        | 0.42%   |
| ASUS ASUS             | 50        | 0.39%   |
| Aquarius NS585        | 50        | 0.39%   |
| Lenovo B570e          | 48        | 0.38%   |
| HP ENVY               | 48        | 0.38%   |
| Samsung 355V4C        | 46        | 0.36%   |
| Samsung 300V3A        | 45        | 0.35%   |
| Dell XPS              | 45        | 0.35%   |
| Clevo NL41MU2         | 44        | 0.35%   |
| Notebook W65          | 42        | 0.33%   |
| Valve Jupiter         | 41        | 0.32%   |
| ASUS TUF              | 41        | 0.32%   |
| Fujitsu LIFEBOOK      | 40        | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 1548      | 12.18%  |
| 2012    | 1439      | 11.32%  |
| 2010    | 1033      | 8.12%   |
| 2013    | 882       | 6.94%   |
| 2019    | 844       | 6.64%   |
| 2021    | 724       | 5.69%   |
| 2018    | 707       | 5.56%   |
| 2020    | 690       | 5.43%   |
| 2017    | 679       | 5.34%   |
| 2009    | 634       | 4.99%   |
| 2008    | 619       | 4.87%   |
| 2014    | 602       | 4.73%   |
| 2015    | 525       | 4.13%   |
| 2016    | 515       | 4.05%   |
| 2007    | 470       | 3.7%    |
| 2022    | 444       | 3.49%   |
| 2006    | 204       | 1.6%    |
| 2023    | 73        | 0.57%   |
| 2005    | 54        | 0.42%   |
| Unknown | 14        | 0.11%   |
| 2004    | 11        | 0.09%   |
| 2003    | 2         | 0.02%   |
| 2001    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 12714     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 12143     | 94.99%  |
| Enabled  | 641       | 5.01%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 12697     | 99.87%  |
| Yes  | 17        | 0.13%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Notebooks | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 3590      | 27.48%  |
| 3.01-4.0        | 3580      | 27.41%  |
| 8.01-16.0       | 1875      | 14.35%  |
| 1.01-2.0        | 1479      | 11.32%  |
| 16.01-24.0      | 1093      | 8.37%   |
| 2.01-3.0        | 804       | 6.15%   |
| 0.51-1.0        | 275       | 2.11%   |
| 32.01-64.0      | 257       | 1.97%   |
| 24.01-32.0      | 69        | 0.53%   |
| 64.01-256.0     | 23        | 0.18%   |
| 0.01-0.5        | 14        | 0.11%   |
| Unknown         | 3         | 0.02%   |
| More than 256.0 | 1         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 5422      | 37.81%  |
| 0.51-1.0   | 4043      | 28.2%   |
| 2.01-3.0   | 2247      | 15.67%  |
| 3.01-4.0   | 1034      | 7.21%   |
| 4.01-8.0   | 1001      | 6.98%   |
| 0.01-0.5   | 311       | 2.17%   |
| 8.01-16.0  | 243       | 1.69%   |
| 16.01-24.0 | 16        | 0.11%   |
| 24.01-32.0 | 10        | 0.07%   |
| Unknown    | 10        | 0.07%   |
| 32.01-64.0 | 2         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 10031     | 76.7%   |
| 2       | 2667      | 20.39%  |
| 3       | 269       | 2.06%   |
| 0       | 89        | 0.68%   |
| 4       | 15        | 0.11%   |
| 5       | 6         | 0.05%   |
| Unknown | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 7143      | 55.47%  |
| Yes       | 5734      | 44.53%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 10816     | 84.9%   |
| No        | 1924      | 15.1%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 12482     | 98.06%  |
| No        | 247       | 1.94%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 9179      | 71.18%  |
| No        | 3717      | 28.82%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Russia  | 12714     | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Moscow           | 2885      | 21.06%  |
| St Petersburg    | 1246      | 9.1%    |
| Novosibirsk      | 410       | 2.99%   |
| Krasnodar        | 408       | 2.98%   |
| Voronezh         | 363       | 2.65%   |
| Yekaterinburg    | 354       | 2.58%   |
| Pecherskoye      | 337       | 2.46%   |
| Nizhniy Novgorod | 266       | 1.94%   |
| Samara           | 245       | 1.79%   |
| Perm             | 230       | 1.68%   |
| Chelyabinsk      | 218       | 1.59%   |
| Rostov-on-Don    | 212       | 1.55%   |
| Kazan’         | 171       | 1.25%   |
| Krasnoyarsk      | 154       | 1.12%   |
| Ufa              | 149       | 1.09%   |
| Saratov          | 149       | 1.09%   |
| Omsk             | 121       | 0.88%   |
| Khabarovsk       | 118       | 0.86%   |
| Tyumen           | 114       | 0.83%   |
| Vladivostok      | 110       | 0.8%    |
| Volgograd        | 108       | 0.79%   |
| Barnaul          | 107       | 0.78%   |
| Irkutsk          | 97        | 0.71%   |
| Yaroslavl        | 94        | 0.69%   |
| Kaliningrad      | 92        | 0.67%   |
| Stavropol        | 85        | 0.62%   |
| Kirov            | 82        | 0.6%    |
| Tula             | 77        | 0.56%   |
| Ryazan           | 74        | 0.54%   |
| Belgorod         | 72        | 0.53%   |
| Ulyanovsk        | 71        | 0.52%   |
| Tomsk            | 71        | 0.52%   |
| Surgut           | 71        | 0.52%   |
| Kemerovo         | 71        | 0.52%   |
| Tver             | 69        | 0.5%    |
| Ivanovo          | 61        | 0.45%   |
| Smolensk         | 58        | 0.42%   |
| Penza            | 58        | 0.42%   |
| Orenburg         | 57        | 0.42%   |
| Lipetsk          | 57        | 0.42%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2731      | 3662   | 17.45%  |
| Seagate             | 2281      | 2998   | 14.57%  |
| Samsung Electronics | 1501      | 2010   | 9.59%   |
| Toshiba             | 1474      | 1899   | 9.42%   |
| Hitachi             | 980       | 1281   | 6.26%   |
| Kingston            | 790       | 980    | 5.05%   |
| Unknown             | 636       | 817    | 4.06%   |
| HGST                | 571       | 798    | 3.65%   |
| SanDisk             | 495       | 642    | 3.16%   |
| SK hynix            | 427       | 552    | 2.73%   |
| Intel               | 368       | 470    | 2.35%   |
| A-DATA Technology   | 283       | 469    | 1.81%   |
| China               | 247       | 321    | 1.58%   |
| Micron Technology   | 208       | 261    | 1.33%   |
| Fujitsu             | 146       | 177    | 0.93%   |
| Crucial             | 138       | 170    | 0.88%   |
| SPCC                | 135       | 196    | 0.86%   |
| KIOXIA              | 131       | 157    | 0.84%   |
| Apacer              | 111       | 135    | 0.71%   |
| Smartbuy            | 102       | 117    | 0.65%   |
| OCZ                 | 90        | 106    | 0.57%   |
| Transcend           | 87        | 111    | 0.56%   |
| KingSpec            | 86        | 106    | 0.55%   |
| Plextor             | 85        | 108    | 0.54%   |
| HUAWEI              | 72        | 81     | 0.46%   |
| Phison              | 71        | 77     | 0.45%   |
| Silicon Motion      | 64        | 80     | 0.41%   |
| Netac               | 63        | 79     | 0.4%    |
| AMD                 | 55        | 62     | 0.35%   |
| Apple               | 54        | 67     | 0.34%   |
| BIWIN               | 53        | 54     | 0.34%   |
| Phison Electronics  | 51        | 57     | 0.33%   |
| Unknown             | 51        | 56     | 0.33%   |
| Patriot             | 48        | 55     | 0.31%   |
| JMicron Technology  | 40        | 41     | 0.26%   |
| GOODRAM             | 39        | 43     | 0.25%   |
| Gigabyte Technology | 36        | 41     | 0.23%   |
| FORESEE             | 33        | 37     | 0.21%   |
| KingDian            | 31        | 44     | 0.2%    |
| Corsair             | 31        | 39     | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB               | 272       | 1.69%   |
| Seagate ST500LT012-1DG142 500GB        | 264       | 1.64%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 255       | 1.59%   |
| Seagate ST9500325AS 500GB              | 207       | 1.29%   |
| Seagate ST1000LM035-1RK172 1TB         | 187       | 1.16%   |
| Seagate ST9320325AS 320GB              | 165       | 1.03%   |
| HGST HTS545050A7E680 500GB             | 151       | 0.94%   |
| Toshiba MQ01ABD100 1TB                 | 134       | 0.83%   |
| Toshiba MQ04ABF100 1TB                 | 121       | 0.75%   |
| Hitachi HTS543232A7A384 320GB          | 109       | 0.68%   |
| Seagate ST500LT012-9WS142 500GB        | 106       | 0.66%   |
| Kingston SA400S37240G 240GB SSD        | 101       | 0.63%   |
| HGST HTS545050A7E380 500GB             | 97        | 0.6%    |
| Seagate ST9250315AS 250GB              | 95        | 0.59%   |
| Seagate ST500LM012 HN-M500MBB 500GB    | 94        | 0.59%   |
| Kingston SA400S37120G 120GB SSD        | 92        | 0.57%   |
| Seagate ST320LT020-9YG142 320GB        | 91        | 0.57%   |
| WDC WD5000LPVX-22V0TT0 500GB           | 90        | 0.56%   |
| Hitachi HTS547550A9E384 500GB          | 89        | 0.55%   |
| HGST HTS541010A9E680 1TB               | 88        | 0.55%   |
| Hitachi HTS545025B9A300 250GB          | 87        | 0.54%   |
| HGST HTS721010A9E630 1TB               | 84        | 0.52%   |
| WDC WD3200BPVT-22JJ5T0 320GB           | 81        | 0.5%    |
| WDC WD10JPVX-22JC3T0 1TB               | 78        | 0.49%   |
| Hitachi HTS547575A9E384 752GB          | 78        | 0.49%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 75        | 0.47%   |
| WDC WD5000LPCX-21VHAT0 500GB           | 75        | 0.47%   |
| Kingston SV300S37A120G 120GB SSD       | 73        | 0.45%   |
| WDC WD5000LPCX-24VHAT0 500GB           | 70        | 0.44%   |
| WDC WDS120G2G0A-00JH30 120GB SSD       | 63        | 0.39%   |
| Toshiba MQ01ABD050 500GB               | 62        | 0.39%   |
| Toshiba MQ01ABD075 752GB               | 60        | 0.37%   |
| Samsung SSD 860 EVO 250GB              | 56        | 0.35%   |
| Samsung HM321HI 320GB                  | 56        | 0.35%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB | 55        | 0.34%   |
| Hitachi HTS545032B9A300 320GB          | 55        | 0.34%   |
| A-DATA SU800 512GB SSD                 | 55        | 0.34%   |
| WDC WD1600BEVT-22ZCT0 160GB            | 53        | 0.33%   |
| Hitachi HTS545050A7E380 500GB          | 53        | 0.33%   |
| Samsung SSD 860 EVO 500GB              | 52        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2268      | 2975   | 29.05%  |
| WDC                 | 2242      | 3014   | 28.72%  |
| Toshiba             | 1294      | 1668   | 16.58%  |
| Hitachi             | 980       | 1281   | 12.55%  |
| HGST                | 571       | 798    | 7.31%   |
| Samsung Electronics | 239       | 285    | 3.06%   |
| Fujitsu             | 145       | 176    | 1.86%   |
| Unknown             | 23        | 30     | 0.29%   |
| External            | 10        | 15     | 0.13%   |
| IBM/Hitachi         | 6         | 6      | 0.08%   |
| Apple               | 5         | 5      | 0.06%   |
| USB                 | 3         | 3      | 0.04%   |
| HGST HTS            | 3         | 3      | 0.04%   |
| QNAP                | 2         | 6      | 0.03%   |
| KESU                | 2         | 2      | 0.03%   |
| Unknown             | 2         | 2      | 0.03%   |
| ZALMAN              | 1         | 1      | 0.01%   |
| WD MediaMax         | 1         | 2      | 0.01%   |
| USB3.0              | 1         | 1      | 0.01%   |
| SILICONMOTION       | 1         | 1      | 0.01%   |
| OEM                 | 1         | 2      | 0.01%   |
| MARSHAL             | 1         | 1      | 0.01%   |
| JMicron Technology  | 1         | 1      | 0.01%   |
| Initio              | 1         | 1      | 0.01%   |
| IBM                 | 1         | 1      | 0.01%   |
| CLOVER              | 1         | 1      | 0.01%   |
| ACASIS              | 1         | 1      | 0.01%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 618       | 767    | 14.99%  |
| Samsung Electronics | 598       | 799    | 14.5%   |
| WDC                 | 280       | 332    | 6.79%   |
| SanDisk             | 276       | 373    | 6.69%   |
| China               | 246       | 320    | 5.97%   |
| A-DATA Technology   | 243       | 416    | 5.89%   |
| Crucial             | 131       | 160    | 3.18%   |
| SPCC                | 129       | 190    | 3.13%   |
| Intel               | 120       | 156    | 2.91%   |
| Smartbuy            | 99        | 114    | 2.4%    |
| Apacer              | 96        | 118    | 2.33%   |
| OCZ                 | 90        | 106    | 2.18%   |
| SK hynix            | 86        | 106    | 2.09%   |
| KingSpec            | 86        | 106    | 2.09%   |
| Plextor             | 85        | 108    | 2.06%   |
| Transcend           | 84        | 105    | 2.04%   |
| Toshiba             | 72        | 92     | 1.75%   |
| Micron Technology   | 63        | 93     | 1.53%   |
| AMD                 | 52        | 58     | 1.26%   |
| Patriot             | 48        | 55     | 1.16%   |
| Netac               | 44        | 55     | 1.07%   |
| GOODRAM             | 39        | 43     | 0.95%   |
| Apple               | 39        | 45     | 0.95%   |
| KingDian            | 30        | 43     | 0.73%   |
| Corsair             | 29        | 37     | 0.7%    |
| LITEON              | 24        | 30     | 0.58%   |
| LITEONIT            | 21        | 35     | 0.51%   |
| Unknown             | 19        | 21     | 0.46%   |
| XrayDisk            | 18        | 25     | 0.44%   |
| Gigabyte Technology | 17        | 20     | 0.41%   |
| Hewlett-Packard     | 15        | 23     | 0.36%   |
| Londisk             | 14        | 17     | 0.34%   |
| KingFast            | 14        | 16     | 0.34%   |
| TO Exter            | 13        | 16     | 0.32%   |
| Kingmax             | 13        | 25     | 0.32%   |
| Zheino              | 11        | 13     | 0.27%   |
| Team                | 11        | 15     | 0.27%   |
| ShiJi               | 9         | 10     | 0.22%   |
| FORESEE             | 8         | 8      | 0.19%   |
| Qumo                | 7         | 8      | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 7506      | 10282  | 50.21%  |
| SSD     | 3864      | 5368   | 25.85%  |
| NVMe    | 2733      | 3682   | 18.28%  |
| MMC     | 646       | 850    | 4.32%   |
| Unknown | 201       | 222    | 1.34%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 10095     | 15474  | 73.05%  |
| NVMe | 2718      | 3647   | 19.67%  |
| MMC  | 646       | 850    | 4.67%   |
| SAS  | 360       | 433    | 2.61%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 8343      | 12039  | 76.86%  |
| 0.51-1.0   | 2384      | 3443   | 21.96%  |
| 1.01-2.0   | 112       | 142    | 1.03%   |
| 3.01-4.0   | 5         | 12     | 0.05%   |
| 2.01-3.0   | 5         | 7      | 0.05%   |
| 4.01-10.0  | 5         | 6      | 0.05%   |
| 0          | 1         | 1      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 4099      | 29.48%  |
| 251-500        | 3656      | 26.3%   |
| 1-20           | 1519      | 10.93%  |
| 501-1000       | 1513      | 10.88%  |
| 51-100         | 1245      | 8.95%   |
| 21-50          | 950       | 6.83%   |
| 1001-2000      | 474       | 3.41%   |
| Unknown        | 302       | 2.17%   |
| 2001-3000      | 94        | 0.68%   |
| More than 3000 | 51        | 0.37%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 7974      | 56.1%   |
| 21-50          | 2019      | 14.2%   |
| 101-250        | 1377      | 9.69%   |
| 51-100         | 1316      | 9.26%   |
| 251-500        | 760       | 5.35%   |
| 501-1000       | 338       | 2.38%   |
| Unknown        | 302       | 2.12%   |
| 1001-2000      | 98        | 0.69%   |
| 2001-3000      | 18        | 0.13%   |
| More than 3000 | 12        | 0.08%   |
| 0              | 1         | 0.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB           | 141       | 195    | 4.53%   |
| Seagate ST500LT012-9WS142 500GB     | 96        | 114    | 3.08%   |
| Seagate ST9320325AS 320GB           | 90        | 115    | 2.89%   |
| HGST HTS545050A7E680 500GB          | 73        | 111    | 2.34%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 72        | 91     | 2.31%   |
| Seagate ST500LT012-1DG142 500GB     | 69        | 85     | 2.21%   |
| Seagate ST9250315AS 250GB           | 66        | 82     | 2.12%   |
| Seagate ST320LT020-9YG142 320GB     | 56        | 81     | 1.8%    |
| HGST HTS545050A7E380 500GB          | 48        | 76     | 1.54%   |
| Hitachi HTS545025B9A300 250GB       | 44        | 53     | 1.41%   |
| Hitachi HTS543232A7A384 320GB       | 44        | 50     | 1.41%   |
| Seagate ST320LT012-9WS14C 320GB     | 38        | 51     | 1.22%   |
| Hitachi HTS547550A9E384 500GB       | 35        | 48     | 1.12%   |
| Hitachi HTS547575A9E384 752GB       | 34        | 47     | 1.09%   |
| Toshiba MQ01ABF050 500GB            | 33        | 48     | 1.06%   |
| Toshiba MQ01ABD050 500GB            | 30        | 37     | 0.96%   |
| Hitachi HTS541612J9SA00 120GB       | 30        | 40     | 0.96%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 26        | 30     | 0.83%   |
| Hitachi HTS541680J9SA00 80GB        | 26        | 30     | 0.83%   |
| Toshiba MK3265GSX 320GB             | 25        | 31     | 0.8%    |
| HGST HTS541010A9E680 1TB            | 25        | 39     | 0.8%    |
| Seagate ST9500420AS 500GB           | 24        | 37     | 0.77%   |
| Samsung Electronics HM160HI 160GB   | 24        | 26     | 0.77%   |
| Hitachi HTS545032B9A300 320GB       | 23        | 29     | 0.74%   |
| Hitachi HTS545050A7E380 500GB       | 21        | 31     | 0.67%   |
| Toshiba MQ01ABD100 1TB              | 20        | 28     | 0.64%   |
| Hitachi HTS545050B9A300 500GB       | 20        | 27     | 0.64%   |
| Hitachi HTS542512K9SA00 120GB       | 20        | 26     | 0.64%   |
| WDC WD3200BPVT-22ZEST0 320GB        | 19        | 25     | 0.61%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 18        | 22     | 0.58%   |
| Samsung Electronics HM321HI 320GB   | 18        | 23     | 0.58%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 17        | 20     | 0.55%   |
| WDC WD2500BEVT-22A23T0 250GB        | 16        | 19     | 0.51%   |
| Toshiba MK3259GSXP 320GB            | 16        | 26     | 0.51%   |
| Samsung Electronics HM250HI 250GB   | 16        | 18     | 0.51%   |
| Hitachi HTS542516K9SA00 160GB       | 16        | 29     | 0.51%   |
| Toshiba MQ01ABD075 752GB            | 15        | 20     | 0.48%   |
| Seagate ST9160821AS 160GB           | 15        | 17     | 0.48%   |
| Hitachi HTS542525K9SA00 250GB       | 15        | 21     | 0.48%   |
| Seagate ST9250827AS 250GB           | 14        | 16     | 0.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Seagate                      | 931       | 1192   | 30.05%  |
| Hitachi                      | 523       | 665    | 16.88%  |
| WDC                          | 492       | 646    | 15.88%  |
| Toshiba                      | 438       | 576    | 14.14%  |
| HGST                         | 191       | 287    | 6.17%   |
| Samsung Electronics          | 128       | 149    | 4.13%   |
| Kingston                     | 51        | 63     | 1.65%   |
| Fujitsu                      | 45        | 62     | 1.45%   |
| SanDisk                      | 44        | 53     | 1.42%   |
| SK hynix                     | 27        | 35     | 0.87%   |
| Intel                        | 25        | 37     | 0.81%   |
| A-DATA Technology            | 20        | 27     | 0.65%   |
| China                        | 17        | 23     | 0.55%   |
| OCZ                          | 16        | 16     | 0.52%   |
| KingSpec                     | 13        | 15     | 0.42%   |
| SPCC                         | 12        | 13     | 0.39%   |
| LITEON                       | 11        | 12     | 0.36%   |
| Crucial                      | 10        | 13     | 0.32%   |
| Plextor                      | 9         | 11     | 0.29%   |
| Micron Technology            | 8         | 14     | 0.26%   |
| Corsair                      | 8         | 8      | 0.26%   |
| LITEONIT                     | 7         | 13     | 0.23%   |
| Netac                        | 6         | 7      | 0.19%   |
| AMD                          | 6         | 8      | 0.19%   |
| IBM/Hitachi                  | 5         | 5      | 0.16%   |
| Kingmax                      | 4         | 4      | 0.13%   |
| Apple                        | 4         | 4      | 0.13%   |
| Transcend                    | 3         | 3      | 0.1%    |
| SSSTC                        | 3         | 4      | 0.1%    |
| Smartbuy                     | 3         | 3      | 0.1%    |
| KingDian                     | 3         | 6      | 0.1%    |
| Unknown                      | 3         | 4      | 0.1%    |
| Team                         | 2         | 3      | 0.06%   |
| OCZ-VERTEX3                  | 2         | 2      | 0.06%   |
| Mushkin                      | 2         | 2      | 0.06%   |
| HGST HTS                     | 2         | 2      | 0.06%   |
| Zheino                       | 1         | 1      | 0.03%   |
| XrayDisk                     | 1         | 1      | 0.03%   |
| Unknown                      | 1         | 1      | 0.03%   |
| Shenzhen Longsys Electronics | 1         | 1      | 0.03%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 931       | 1192   | 34.41%  |
| Hitachi             | 523       | 665    | 19.33%  |
| WDC                 | 467       | 620    | 17.26%  |
| Toshiba             | 434       | 572    | 16.04%  |
| HGST                | 191       | 287    | 7.06%   |
| Samsung Electronics | 106       | 126    | 3.92%   |
| Fujitsu             | 45        | 62     | 1.66%   |
| IBM/Hitachi         | 5         | 5      | 0.18%   |
| HGST HTS            | 2         | 2      | 0.07%   |
| MARSHAL             | 1         | 1      | 0.04%   |
| External            | 1         | 1      | 0.04%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 2667      | 3533   | 87.27%  |
| SSD  | 367       | 457    | 12.01%  |
| NVMe | 22        | 25     | 0.72%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD1600BEVT-22ZCT0 160GB        | 4         | 5      | 4.26%   |
| Seagate ST9500325AS 500GB          | 4         | 4      | 4.26%   |
| Samsung Electronics HM321HI 320GB  | 4         | 5      | 4.26%   |
| HGST HTS721010A9E630 1TB           | 4         | 5      | 4.26%   |
| Toshiba MK3265GSX 320GB            | 3         | 3      | 3.19%   |
| Seagate ST9320325AS 320GB          | 3         | 3      | 3.19%   |
| Hitachi HTS547550A9E384 500GB      | 3         | 3      | 3.19%   |
| HGST HTS545050A7E680 500GB         | 3         | 3      | 3.19%   |
| WDC WD3200BEVT-22ZCT0 320GB        | 2         | 2      | 2.13%   |
| WDC WD1600BEVS-22RST0 160GB        | 2         | 2      | 2.13%   |
| Toshiba MQ01ABD050 500GB           | 2         | 2      | 2.13%   |
| Toshiba MK6465GSX 640GB            | 2         | 2      | 2.13%   |
| Toshiba MK3259GSXP 320GB           | 2         | 2      | 2.13%   |
| Seagate ST500LT012-1DG142 500GB    | 2         | 2      | 2.13%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2         | 2      | 2.13%   |
| Samsung Electronics HM160HI 160GB  | 2         | 2      | 2.13%   |
| Hitachi HTS545050A7E380 500GB      | 2         | 3      | 2.13%   |
| Hitachi HTS543225A7A384 250GB      | 2         | 3      | 2.13%   |
| HGST HTS541010A9E680 1TB           | 2         | 2      | 2.13%   |
| WDC WD800BEVS-22RST0 80GB          | 1         | 1      | 1.06%   |
| WDC WD7500BPVT-22HXZT3 752GB       | 1         | 1      | 1.06%   |
| WDC WD7500BPVT-22HXZT1 752GB       | 1         | 1      | 1.06%   |
| WDC WD5000M22K-24Z1LT0-SSHD-16GB   | 1         | 1      | 1.06%   |
| WDC WD5000LPCX-24VHAT0 500GB       | 1         | 1      | 1.06%   |
| WDC WD5000BPVT-80HXZT1 500GB       | 1         | 1      | 1.06%   |
| WDC WD5000BPVT-24HXZT3 500GB       | 1         | 1      | 1.06%   |
| WDC WD5000BEVT-35ZAT0 500GB        | 1         | 1      | 1.06%   |
| WDC WD5000BEVT-22A0RT0 500GB       | 1         | 1      | 1.06%   |
| WDC WD3200BPVT-80ZEST0 320GB       | 1         | 1      | 1.06%   |
| WDC WD3200BPVT-22JJ5T0 320GB       | 1         | 1      | 1.06%   |
| WDC WD3200BEVS-0 320GB             | 1         | 1      | 1.06%   |
| WDC WD2500LPCX-24C6HT0 250GB       | 1         | 1      | 1.06%   |
| WDC WD2500BEVT-35A23T0 250GB       | 1         | 1      | 1.06%   |
| WDC WD2500BEVT-24A23T0 250GB       | 1         | 1      | 1.06%   |
| WDC WD2500BEVT-22ZCT0 250GB        | 1         | 1      | 1.06%   |
| WDC WD1600BEVT-75ZCT2 160GB        | 1         | 1      | 1.06%   |
| WDC WD1200BEVS-07LAT0 120GB        | 1         | 1      | 1.06%   |
| WDC WD10JPVX-22JC3T0 1TB           | 1         | 1      | 1.06%   |
| Toshiba MK8037GSX 80GB             | 1         | 1      | 1.06%   |
| Toshiba MK8025GAL 80GB             | 1         | 2      | 1.06%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 27        | 28     | 28.72%  |
| Toshiba             | 16        | 18     | 17.02%  |
| Seagate             | 16        | 18     | 17.02%  |
| Samsung Electronics | 13        | 14     | 13.83%  |
| HGST                | 11        | 13     | 11.7%   |
| Hitachi             | 9         | 11     | 9.57%   |
| Fujitsu             | 1         | 1      | 1.06%   |
| Apple               | 1         | 2      | 1.06%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 7683      | 11565  | 54.88%  |
| Detected | 3209      | 4718   | 22.92%  |
| Malfunc  | 3012      | 4015   | 21.52%  |
| Failed   | 94        | 105    | 0.67%   |
| Limited  | 1         | 1      | 0.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 8962      | 63.29%  |
| AMD                                     | 2267      | 16.01%  |
| Samsung Electronics                     | 717       | 5.06%   |
| SanDisk                                 | 413       | 2.92%   |
| SK hynix                                | 325       | 2.3%    |
| Kingston Technology Company             | 186       | 1.31%   |
| Phison Electronics                      | 169       | 1.19%   |
| Micron Technology                       | 145       | 1.02%   |
| KIOXIA                                  | 142       | 1%      |
| Nvidia                                  | 128       | 0.9%    |
| Toshiba America Info Systems            | 113       | 0.8%    |
| Silicon Motion                          | 84        | 0.59%   |
| Silicon Integrated Systems [SiS]        | 76        | 0.54%   |
| Union Memory (Shenzhen)                 | 62        | 0.44%   |
| INNOGRIT                                | 47        | 0.33%   |
| Solid State Storage Technology          | 45        | 0.32%   |
| ADATA Technology                        | 45        | 0.32%   |
| Shenzhen Longsys Electronics            | 39        | 0.28%   |
| JMicron Technology                      | 35        | 0.25%   |
| Realtek Semiconductor                   | 30        | 0.21%   |
| Micron/Crucial Technology               | 14        | 0.1%    |
| Netac Technology                        | 13        | 0.09%   |
| Yangtze Memory Technologies             | 12        | 0.08%   |
| VIA Technologies                        | 12        | 0.08%   |
| MAXIO Technology (Hangzhou)             | 11        | 0.08%   |
| O2 Micro                                | 10        | 0.07%   |
| Apple                                   | 8         | 0.06%   |
| Lite-On Technology                      | 7         | 0.05%   |
| Shenzhen Shichuangyi Electronics        | 6         | 0.04%   |
| Lenovo                                  | 6         | 0.04%   |
| Marvell Technology Group                | 5         | 0.04%   |
| ASMedia Technology                      | 5         | 0.04%   |
| Unknown                                 | 4         | 0.03%   |
| Shenzhen Unionmemory Information System | 3         | 0.02%   |
| Jiangsu Huacun Elec.                    | 3         | 0.02%   |
| Zhaoxin                                 | 2         | 0.01%   |
| Silicon Image                           | 2         | 0.01%   |
| ShenZhen TIGO Semiconductor             | 2         | 0.01%   |
| Seagate Technology                      | 2         | 0.01%   |
| ULi Electronics                         | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 1572      | 10.09%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 1396      | 8.96%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 981       | 6.3%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 684       | 4.39%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 550       | 3.53%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 527       | 3.38%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 442       | 2.84%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 415       | 2.66%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 395       | 2.53%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 342       | 2.19%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 336       | 2.16%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 319       | 2.05%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 285       | 1.83%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 278       | 1.78%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 260       | 1.67%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 241       | 1.55%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 206       | 1.32%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 192       | 1.23%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 190       | 1.22%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 187       | 1.2%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 173       | 1.11%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 167       | 1.07%   |
| Intel Tiger Lake-LP SATA Controller                                              | 166       | 1.07%   |
| Intel Comet Lake SATA AHCI Controller                                            | 166       | 1.07%   |
| Intel Volume Management Device NVMe RAID Controller                              | 153       | 0.98%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 128       | 0.82%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 124       | 0.8%    |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 121       | 0.78%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 121       | 0.78%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 120       | 0.77%   |
| AMD SB600 Non-Raid-5 SATA                                                        | 118       | 0.76%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 117       | 0.75%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 116       | 0.74%   |
| AMD SB600 IDE                                                                    | 115       | 0.74%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 112       | 0.72%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 110       | 0.71%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 109       | 0.7%    |
| SK hynix BC501 NVMe Solid State Drive                                            | 104       | 0.67%   |
| Intel SSD 660P Series                                                            | 104       | 0.67%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 103       | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 10041     | 67.37%  |
| NVMe | 2737      | 18.36%  |
| IDE  | 1620      | 10.87%  |
| RAID | 507       | 3.4%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 9824      | 77.25%  |
| AMD          | 2878      | 22.63%  |
| ARM          | 6         | 0.05%   |
| CentaurHauls | 5         | 0.04%   |
| Unknown      | 3         | 0.02%   |
| PowerBook5,6 | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-3210M CPU @ 2.50GHz             | 167       | 1.31%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 166       | 1.3%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 159       | 1.25%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 153       | 1.2%    |
| Intel Core i5-3230M CPU @ 2.60GHz             | 146       | 1.14%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 141       | 1.11%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 134       | 1.05%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 128       | 1%      |
| Intel Pentium CPU B960 @ 2.20GHz              | 127       | 1%      |
| AMD Ryzen 5 5500U with Radeon Graphics        | 122       | 0.96%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 118       | 0.93%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 117       | 0.92%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 113       | 0.89%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 106       | 0.83%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 105       | 0.82%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 105       | 0.82%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 103       | 0.81%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 99        | 0.78%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 96        | 0.75%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 94        | 0.74%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 92        | 0.72%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 89        | 0.7%    |
| AMD E-450 APU with Radeon HD Graphics         | 87        | 0.68%   |
| Intel Atom CPU N455 @ 1.66GHz                 | 85        | 0.67%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 84        | 0.66%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 82        | 0.64%   |
| Intel Atom CPU N2600 @ 1.60GHz                | 82        | 0.64%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 79        | 0.62%   |
| AMD A10-4600M APU with Radeon HD Graphics     | 76        | 0.6%    |
| Intel Pentium CPU 2020M @ 2.40GHz             | 75        | 0.59%   |
| Intel Core i3-3120M CPU @ 2.50GHz             | 75        | 0.59%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 73        | 0.57%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 72        | 0.56%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 69        | 0.54%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 68        | 0.53%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 68        | 0.53%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 68        | 0.53%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 66        | 0.52%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 65        | 0.51%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 65        | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 2393      | 18.77%  |
| Intel Core i3                  | 1591      | 12.48%  |
| Intel Core i7                  | 1214      | 9.52%   |
| Intel Celeron                  | 932       | 7.31%   |
| Intel Pentium                  | 866       | 6.79%   |
| Intel Atom                     | 732       | 5.74%   |
| Other                          | 668       | 5.24%   |
| Intel Core 2 Duo               | 659       | 5.17%   |
| AMD Ryzen 5                    | 545       | 4.28%   |
| AMD Ryzen 7                    | 312       | 2.45%   |
| AMD A6                         | 259       | 2.03%   |
| Intel Pentium Dual-Core        | 211       | 1.66%   |
| AMD A4                         | 177       | 1.39%   |
| AMD A8                         | 169       | 1.33%   |
| AMD A10                        | 160       | 1.26%   |
| AMD E                          | 153       | 1.2%    |
| AMD Ryzen 3                    | 142       | 1.11%   |
| AMD E1                         | 121       | 0.95%   |
| Intel Genuine                  | 111       | 0.87%   |
| AMD E2                         | 106       | 0.83%   |
| Intel Pentium Dual             | 100       | 0.78%   |
| Intel Core 2                   | 100       | 0.78%   |
| Intel Celeron M                | 78        | 0.61%   |
| Intel Celeron Dual-Core        | 78        | 0.61%   |
| Intel Pentium Silver           | 76        | 0.6%    |
| AMD Turion 64 X2 Mobile        | 74        | 0.58%   |
| AMD Phenom II                  | 74        | 0.58%   |
| Intel Pentium M                | 59        | 0.46%   |
| AMD Athlon                     | 48        | 0.38%   |
| AMD Ryzen 9                    | 37        | 0.29%   |
| AMD C-60                       | 37        | 0.29%   |
| AMD Athlon II                  | 35        | 0.27%   |
| AMD Athlon 64 X2               | 29        | 0.23%   |
| AMD Athlon X2                  | 27        | 0.21%   |
| AMD Turion X2 Dual-Core Mobile | 26        | 0.2%    |
| AMD Turion II Dual-Core        | 26        | 0.2%    |
| AMD Ryzen 7 PRO                | 25        | 0.2%    |
| AMD C-50                       | 22        | 0.17%   |
| Intel Core Duo                 | 21        | 0.16%   |
| AMD Athlon II Dual-Core        | 21        | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 7508      | 58.7%   |
| 4       | 3199      | 25.01%  |
| 1       | 727       | 5.68%   |
| 6       | 533       | 4.17%   |
| 8       | 383       | 2.99%   |
| Unknown | 287       | 2.24%   |
| 12      | 50        | 0.39%   |
| 10      | 40        | 0.31%   |
| 14      | 35        | 0.27%   |
| 3       | 25        | 0.2%    |
| 24      | 2         | 0.02%   |
| 192     | 1         | 0.01%   |
| 16      | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 12700     | 99.83%  |
| Unknown | 15        | 0.12%   |
| 2       | 5         | 0.04%   |
| 4       | 2         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 7481      | 58.4%   |
| 1       | 5041      | 39.35%  |
| Unknown | 287       | 2.24%   |
| 4       | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 12215     | 95.92%  |
| 32-bit         | 386       | 3.03%   |
| Unknown        | 131       | 1.03%   |
| 64-bit         | 2         | 0.02%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1584      | 12.16%  |
| 0x206a7    | 1341      | 10.29%  |
| 0x306a9    | 1071      | 8.22%   |
| 0x1067a    | 494       | 3.79%   |
| 0x20655    | 467       | 3.58%   |
| 0x6fd      | 349       | 2.68%   |
| 0x806ec    | 327       | 2.51%   |
| 0x106ca    | 318       | 2.44%   |
| 0x40651    | 315       | 2.42%   |
| 0x806ea    | 294       | 2.26%   |
| 0x30678    | 277       | 2.13%   |
| 0x806c1    | 273       | 2.1%    |
| 0x406e3    | 246       | 1.89%   |
| 0x306c3    | 244       | 1.87%   |
| 0x806e9    | 220       | 1.69%   |
| 0x906ea    | 198       | 1.52%   |
| 0x08108109 | 190       | 1.46%   |
| 0x306d4    | 186       | 1.43%   |
| 0x406c4    | 179       | 1.37%   |
| 0x06001119 | 178       | 1.37%   |
| 0x05000119 | 172       | 1.32%   |
| 0x10676    | 166       | 1.27%   |
| 0x07030105 | 156       | 1.2%    |
| 0x20652    | 153       | 1.17%   |
| 0x06006705 | 153       | 1.17%   |
| 0x0a50000c | 148       | 1.14%   |
| 0x03000027 | 146       | 1.12%   |
| 0x010000c8 | 135       | 1.04%   |
| 0x08108102 | 126       | 0.97%   |
| 0x30661    | 124       | 0.95%   |
| 0x106c2    | 118       | 0.91%   |
| 0x08608103 | 116       | 0.89%   |
| 0x406c3    | 112       | 0.86%   |
| 0x10661    | 106       | 0.81%   |
| 0x08600106 | 104       | 0.8%    |
| 0x706a1    | 102       | 0.78%   |
| 0x706e5    | 101       | 0.78%   |
| 0x506c9    | 101       | 0.78%   |
| 0x6e8      | 84        | 0.64%   |
| 0x906e9    | 83        | 0.64%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 1474      | 11.57%  |
| SandyBridge      | 1437      | 11.28%  |
| IvyBridge        | 1156      | 9.07%   |
| Penryn           | 680       | 5.34%   |
| Core             | 662       | 5.2%    |
| Westmere         | 654       | 5.13%   |
| Haswell          | 637       | 5%      |
| Silvermont       | 627       | 4.92%   |
| Bonnell          | 546       | 4.29%   |
| Unknown          | 437       | 3.43%   |
| TigerLake        | 376       | 2.95%   |
| Skylake          | 335       | 2.63%   |
| Zen+             | 334       | 2.62%   |
| Excavator        | 295       | 2.32%   |
| Bobcat           | 262       | 2.06%   |
| Zen 2            | 249       | 1.95%   |
| Piledriver       | 217       | 1.7%    |
| Zen 3            | 214       | 1.68%   |
| Broadwell        | 210       | 1.65%   |
| Puma             | 204       | 1.6%    |
| K10              | 200       | 1.57%   |
| Goldmont plus    | 193       | 1.51%   |
| P6               | 191       | 1.5%    |
| K10 Llano        | 170       | 1.33%   |
| IceLake          | 165       | 1.29%   |
| K8 Hammer        | 156       | 1.22%   |
| Goldmont         | 128       | 1%      |
| Alderlake Hybrid | 115       | 0.9%    |
| CometLake        | 104       | 0.82%   |
| Jaguar           | 99        | 0.78%   |
| Zen              | 72        | 0.57%   |
| K8 & K10 hybrid  | 72        | 0.57%   |
| Nehalem          | 27        | 0.21%   |
| Tremont          | 24        | 0.19%   |
| Steamroller      | 15        | 0.12%   |
| NetBurst         | 5         | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 8492      | 52%     |
| AMD                              | 4070      | 24.92%  |
| Nvidia                           | 3721      | 22.79%  |
| Silicon Integrated Systems [SiS] | 33        | 0.2%    |
| VIA Technologies                 | 9         | 0.06%   |
| Zhaoxin                          | 2         | 0.01%   |
| ATI Technologies                 | 2         | 0.01%   |
| ASPEED Technology                | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1293      | 7.41%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1123      | 6.43%   |
| Intel Core Processor Integrated Graphics Controller                                      | 362       | 2.07%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 357       | 2.04%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 354       | 2.03%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 345       | 1.98%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 341       | 1.95%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 321       | 1.84%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 319       | 1.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 308       | 1.76%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 287       | 1.64%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 262       | 1.5%    |
| Intel UHD Graphics 620                                                                   | 253       | 1.45%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 249       | 1.43%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 249       | 1.43%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 245       | 1.4%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 242       | 1.39%   |
| Intel HD Graphics 620                                                                    | 239       | 1.37%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 238       | 1.36%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 231       | 1.32%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 226       | 1.29%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 223       | 1.28%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 217       | 1.24%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 215       | 1.23%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 196       | 1.12%   |
| AMD Lucienne                                                                             | 191       | 1.09%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 185       | 1.06%   |
| Intel HD Graphics 5500                                                                   | 169       | 0.97%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 161       | 0.92%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 157       | 0.9%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 153       | 0.88%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 138       | 0.79%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 128       | 0.73%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 128       | 0.73%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 126       | 0.72%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 120       | 0.69%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 119       | 0.68%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 116       | 0.66%   |
| Nvidia GM108M [GeForce 840M]                                                             | 108       | 0.62%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 108       | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 5089      | 39.88%  |
| Intel + Nvidia     | 2812      | 22.04%  |
| 1 x AMD            | 2624      | 20.56%  |
| 1 x Nvidia         | 696       | 5.45%   |
| 2 x AMD            | 647       | 5.07%   |
| Intel + AMD        | 595       | 4.66%   |
| AMD + Nvidia       | 212       | 1.66%   |
| 1 x SiS            | 33        | 0.26%   |
| Other              | 18        | 0.14%   |
| 2 x Intel          | 18        | 0.14%   |
| 1 x VIA            | 9         | 0.07%   |
| 2 x Nvidia         | 3         | 0.02%   |
| 1 x Zhaoxin        | 2         | 0.02%   |
| Nvidia + ASPEED    | 1         | 0.01%   |
| Intel + 2 x Nvidia | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 11243     | 86.55%  |
| Proprietary | 1148      | 8.84%   |
| Unknown     | 599       | 4.61%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 4890      | 36.9%   |
| 1.01-2.0   | 3390      | 25.58%  |
| 0.01-0.5   | 3121      | 23.55%  |
| 0.51-1.0   | 987       | 7.45%   |
| 3.01-4.0   | 729       | 5.5%    |
| 5.01-6.0   | 77        | 0.58%   |
| 7.01-8.0   | 28        | 0.21%   |
| 2.01-3.0   | 21        | 0.16%   |
| 8.01-16.0  | 7         | 0.05%   |
| 16.01-24.0 | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 2636      | 20.27%  |
| LG Display              | 1931      | 14.85%  |
| Samsung Electronics     | 1703      | 13.09%  |
| BOE                     | 1663      | 12.79%  |
| Chimei Innolux          | 1561      | 12%     |
| Chi Mei Optoelectronics | 848       | 6.52%   |
| LG Philips              | 236       | 1.81%   |
| Lenovo                  | 205       | 1.58%   |
| HannStar                | 187       | 1.44%   |
| PANDA                   | 179       | 1.38%   |
| Goldstar                | 140       | 1.08%   |
| Dell                    | 133       | 1.02%   |
| InfoVision              | 119       | 0.91%   |
| CPT                     | 118       | 0.91%   |
| Apple                   | 117       | 0.9%    |
| Sharp                   | 106       | 0.82%   |
| BenQ                    | 102       | 0.78%   |
| Acer                    | 95        | 0.73%   |
| Philips                 | 82        | 0.63%   |
| AOC                     | 72        | 0.55%   |
| Sony                    | 67        | 0.52%   |
| Hewlett-Packard         | 55        | 0.42%   |
| TMX                     | 45        | 0.35%   |
| Ancor Communications    | 45        | 0.35%   |
| CSO                     | 43        | 0.33%   |
| ViewSonic               | 42        | 0.32%   |
| Valve                   | 36        | 0.28%   |
| InnoLux Display         | 34        | 0.26%   |
| Iiyama                  | 34        | 0.26%   |
| Quanta Display          | 29        | 0.22%   |
| Toshiba                 | 28        | 0.22%   |
| NEC Computers           | 25        | 0.19%   |
| Unknown                 | 15        | 0.12%   |
| Mi                      | 14        | 0.11%   |
| HKC                     | 14        | 0.11%   |
| Panasonic               | 13        | 0.1%    |
| HUAWEI                  | 12        | 0.09%   |
| ASUSTek Computer        | 12        | 0.09%   |
| Nvidia                  | 11        | 0.08%   |
| S2-Tek                  | 8         | 0.06%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 237       | 1.81%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 209       | 1.6%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 179       | 1.37%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 162       | 1.24%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 159       | 1.21%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 113       | 0.86%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch      | 106       | 0.81%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 103       | 0.79%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch             | 100       | 0.76%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 95        | 0.73%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                      | 95        | 0.73%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch      | 89        | 0.68%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 89        | 0.68%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                 | 77        | 0.59%   |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch             | 77        | 0.59%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch  | 76        | 0.58%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch             | 75        | 0.57%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch      | 74        | 0.57%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch               | 69        | 0.53%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch          | 69        | 0.53%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 68        | 0.52%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch             | 66        | 0.5%    |
| Lenovo LCD Monitor LEN40B0 1366x768 345x194mm 15.6-inch                   | 65        | 0.5%    |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                     | 65        | 0.5%    |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                     | 63        | 0.48%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch             | 62        | 0.47%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                     | 60        | 0.46%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch  | 59        | 0.45%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                     | 58        | 0.44%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch             | 55        | 0.42%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch             | 54        | 0.41%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch           | 52        | 0.4%    |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 52        | 0.4%    |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch               | 50        | 0.38%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch           | 50        | 0.38%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch               | 49        | 0.37%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 48        | 0.37%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch          | 48        | 0.37%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                     | 47        | 0.36%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch               | 46        | 0.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 5094      | 40.29%  |
| 1920x1080 (FHD)    | 4062      | 32.13%  |
| 1600x900 (HD+)     | 816       | 6.45%   |
| 1280x800 (WXGA)    | 813       | 6.43%   |
| 1024x600           | 397       | 3.14%   |
| 1440x900 (WXGA+)   | 195       | 1.54%   |
| 3840x2160 (4K)     | 194       | 1.53%   |
| 2560x1440 (QHD)    | 147       | 1.16%   |
| 1920x1200 (WUXGA)  | 146       | 1.15%   |
| 1280x1024 (SXGA)   | 127       | 1%      |
| 2560x1600          | 92        | 0.73%   |
| 1680x1050 (WSXGA+) | 88        | 0.7%    |
| 2160x1440          | 73        | 0.58%   |
| 800x1280           | 40        | 0.32%   |
| 2880x1800          | 39        | 0.31%   |
| 1024x768 (XGA)     | 39        | 0.31%   |
| 3200x2000          | 26        | 0.21%   |
| 3440x1440          | 21        | 0.17%   |
| 2560x1080          | 21        | 0.17%   |
| 1360x768           | 20        | 0.16%   |
| 1280x720 (HD)      | 20        | 0.16%   |
| 2288x1287          | 19        | 0.15%   |
| 2520x1680          | 14        | 0.11%   |
| 1680x945           | 14        | 0.11%   |
| 3000x2000          | 13        | 0.1%    |
| 1400x1050          | 10        | 0.08%   |
| 3840x2400          | 9         | 0.07%   |
| 3200x1800 (QHD+)   | 8         | 0.06%   |
| 2880x1620          | 8         | 0.06%   |
| 1920x540           | 8         | 0.06%   |
| 3456x2160          | 7         | 0.06%   |
| 2240x1400          | 7         | 0.06%   |
| 1600x1200          | 7         | 0.06%   |
| Unknown            | 6         | 0.05%   |
| 1024x576           | 5         | 0.04%   |
| 2256x1504          | 4         | 0.03%   |
| 3120x2080          | 3         | 0.02%   |
| 2736x1824          | 3         | 0.02%   |
| 3840x1080          | 2         | 0.02%   |
| 2304x1440          | 2         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 7235      | 55.7%   |
| 17      | 1139      | 8.77%   |
| 13      | 1091      | 8.4%    |
| 14      | 1083      | 8.34%   |
| 10      | 405       | 3.12%   |
| 11      | 263       | 2.02%   |
| 24      | 226       | 1.74%   |
| 12      | 222       | 1.71%   |
| 23      | 192       | 1.48%   |
| 27      | 172       | 1.32%   |
| 21      | 168       | 1.29%   |
| 16      | 163       | 1.25%   |
| 19      | 97        | 0.75%   |
| 18      | 84        | 0.65%   |
| Unknown | 57        | 0.44%   |
| 31      | 43        | 0.33%   |
| 34      | 40        | 0.31%   |
| 20      | 37        | 0.28%   |
| 7       | 36        | 0.28%   |
| 22      | 32        | 0.25%   |
| 8       | 23        | 0.18%   |
| 40      | 21        | 0.16%   |
| 32      | 21        | 0.16%   |
| 52      | 16        | 0.12%   |
| 54      | 15        | 0.12%   |
| 72      | 12        | 0.09%   |
| 142     | 9         | 0.07%   |
| 86      | 9         | 0.07%   |
| 42      | 9         | 0.07%   |
| 26      | 9         | 0.07%   |
| 84      | 8         | 0.06%   |
| 25      | 7         | 0.05%   |
| 28      | 6         | 0.05%   |
| 48      | 4         | 0.03%   |
| 46      | 4         | 0.03%   |
| 3       | 4         | 0.03%   |
| 50      | 3         | 0.02%   |
| 36      | 3         | 0.02%   |
| 29      | 3         | 0.02%   |
| 9       | 3         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 8757      | 67.78%  |
| 201-300        | 1492      | 11.55%  |
| 351-400        | 1375      | 10.64%  |
| 501-600        | 575       | 4.45%   |
| 401-500        | 349       | 2.7%    |
| 701-800        | 65        | 0.5%    |
| 601-700        | 62        | 0.48%   |
| Unknown        | 57        | 0.44%   |
| 1001-1500      | 56        | 0.43%   |
| 1-100          | 40        | 0.31%   |
| 801-900        | 24        | 0.19%   |
| 101-200        | 23        | 0.18%   |
| 1501-2000      | 22        | 0.17%   |
| 901-1000       | 13        | 0.1%    |
| More than 2000 | 10        | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 10319     | 84.48%  |
| 16/10   | 1428      | 11.69%  |
| 3/2     | 136       | 1.11%   |
| 5/4     | 117       | 0.96%   |
| 4/3     | 77        | 0.63%   |
| 21/9    | 46        | 0.38%   |
| 0.67    | 36        | 0.29%   |
| Unknown | 25        | 0.2%    |
| 6/5     | 9         | 0.07%   |
| 1.00    | 9         | 0.07%   |
| 0.56    | 9         | 0.07%   |
| 3.73    | 2         | 0.02%   |
| 3.40    | 1         | 0.01%   |
| 1.96    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 7245      | 55.77%  |
| 81-90          | 1697      | 13.06%  |
| 121-130        | 905       | 6.97%   |
| 201-250        | 531       | 4.09%   |
| 71-80          | 465       | 3.58%   |
| 41-50          | 408       | 3.14%   |
| 51-60          | 264       | 2.03%   |
| 131-140        | 203       | 1.56%   |
| 61-70          | 201       | 1.55%   |
| 301-350        | 178       | 1.37%   |
| 151-200        | 175       | 1.35%   |
| 141-150        | 125       | 0.96%   |
| 351-500        | 114       | 0.88%   |
| 91-100         | 93        | 0.72%   |
| More than 1000 | 83        | 0.64%   |
| 111-120        | 82        | 0.63%   |
| 1-40           | 63        | 0.48%   |
| 251-300        | 60        | 0.46%   |
| Unknown        | 57        | 0.44%   |
| 501-1000       | 42        | 0.32%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 5560      | 43.34%  |
| 121-160       | 4072      | 31.74%  |
| 51-100        | 2320      | 18.08%  |
| 161-240       | 569       | 4.43%   |
| More than 240 | 159       | 1.24%   |
| 1-50          | 93        | 0.72%   |
| Unknown       | 57        | 0.44%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 11405     | 88.09%  |
| 2     | 1098      | 8.48%   |
| 0     | 387       | 2.99%   |
| 3     | 57        | 0.44%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 7446      | 35.03%  |
| Qualcomm Atheros                       | 4945      | 23.27%  |
| Intel                                  | 3924      | 18.46%  |
| Broadcom                               | 1914      | 9%      |
| Marvell Technology Group               | 488       | 2.3%    |
| Broadcom Limited                       | 466       | 2.19%   |
| Ralink                                 | 355       | 1.67%   |
| MediaTek                               | 272       | 1.28%   |
| Huawei Technologies                    | 221       | 1.04%   |
| JMicron Technology                     | 118       | 0.56%   |
| Attansic Technology                    | 113       | 0.53%   |
| Xiaomi                                 | 103       | 0.48%   |
| TP-Link                                | 91        | 0.43%   |
| Ralink Technology                      | 81        | 0.38%   |
| Nvidia                                 | 71        | 0.33%   |
| Samsung Electronics                    | 54        | 0.25%   |
| Qualcomm                               | 54        | 0.25%   |
| Silicon Integrated Systems [SiS]       | 49        | 0.23%   |
| ZTE WCDMA Technologies MSM             | 38        | 0.18%   |
| ASIX Electronics                       | 38        | 0.18%   |
| D-Link                                 | 33        | 0.16%   |
| ASUSTek Computer                       | 29        | 0.14%   |
| Qualcomm Atheros Communications        | 26        | 0.12%   |
| Sierra Wireless                        | 24        | 0.11%   |
| Hewlett-Packard                        | 24        | 0.11%   |
| Ericsson Business Mobile Networks      | 24        | 0.11%   |
| Gemtek                                 | 20        | 0.09%   |
| Lenovo                                 | 19        | 0.09%   |
| Dell                                   | 18        | 0.08%   |
| Vimtron Electronics                    | 14        | 0.07%   |
| OPPO Electronics                       | 12        | 0.06%   |
| Fibocom                                | 12        | 0.06%   |
| VIA Technologies                       | 8         | 0.04%   |
| D-Link System                          | 8         | 0.04%   |
| ICS Advent                             | 7         | 0.03%   |
| HTC (High Tech Computer)               | 7         | 0.03%   |
| HMD Global                             | 7         | 0.03%   |
| Apple                                  | 7         | 0.03%   |
| T & A Mobile Phones                    | 6         | 0.03%   |
| Sony Ericsson Mobile Communications AB | 6         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 4439      | 18.1%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 1698      | 6.93%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1434      | 5.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 798       | 3.25%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 636       | 2.59%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 587       | 2.39%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 524       | 2.14%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 416       | 1.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 404       | 1.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 379       | 1.55%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 353       | 1.44%   |
| Broadcom BCM43142 802.11b/g/n                                           | 318       | 1.3%    |
| Intel Wi-Fi 6 AX201                                                     | 302       | 1.23%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 281       | 1.15%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 277       | 1.13%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 249       | 1.02%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 222       | 0.91%   |
| Intel Wireless 8265 / 8275                                              | 221       | 0.9%    |
| Intel Wi-Fi 6 AX200                                                     | 209       | 0.85%   |
| Intel Wireless 7265                                                     | 206       | 0.84%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 200       | 0.82%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 197       | 0.8%    |
| Realtek RTL8723DE Wireless Network Adapter                              | 196       | 0.8%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 193       | 0.79%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 186       | 0.76%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 164       | 0.67%   |
| Intel WiFi Link 5100                                                    | 157       | 0.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 147       | 0.6%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 147       | 0.6%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 144       | 0.59%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 140       | 0.57%   |
| Intel Wireless 3165                                                     | 140       | 0.57%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 140       | 0.57%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 138       | 0.56%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 136       | 0.55%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 133       | 0.54%   |
| Intel Wireless 7260                                                     | 132       | 0.54%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 128       | 0.52%   |
| Intel Centrino Wireless-N 130                                           | 128       | 0.52%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 125       | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Qualcomm Atheros                  | 4271      | 33.22%  |
| Intel                             | 3784      | 29.43%  |
| Realtek Semiconductor             | 2258      | 17.56%  |
| Broadcom                          | 1374      | 10.69%  |
| Ralink                            | 355       | 2.76%   |
| Broadcom Limited                  | 253       | 1.97%   |
| MediaTek                          | 230       | 1.79%   |
| Ralink Technology                 | 81        | 0.63%   |
| TP-Link                           | 59        | 0.46%   |
| Qualcomm                          | 28        | 0.22%   |
| ASUSTek Computer                  | 27        | 0.21%   |
| Qualcomm Atheros Communications   | 26        | 0.2%    |
| Sierra Wireless                   | 24        | 0.19%   |
| D-Link                            | 17        | 0.13%   |
| Fibocom                           | 12        | 0.09%   |
| Dell                              | 9         | 0.07%   |
| D-Link System                     | 8         | 0.06%   |
| Tenda                             | 4         | 0.03%   |
| Micro Star International          | 4         | 0.03%   |
| Ericsson Business Mobile Networks | 4         | 0.03%   |
| Unknown                           | 4         | 0.03%   |
| Xiaomi                            | 3         | 0.02%   |
| Mercucys                          | 3         | 0.02%   |
| Hewlett-Packard                   | 3         | 0.02%   |
| Edimax Technology                 | 3         | 0.02%   |
| ZyXEL Communications              | 2         | 0.02%   |
| Fujitsu Siemens Computers         | 2         | 0.02%   |
| Wacom                             | 1         | 0.01%   |
| Quectel Wireless Solutions        | 1         | 0.01%   |
| Qcom                              | 1         | 0.01%   |
| NetGear                           | 1         | 0.01%   |
| Microsoft                         | 1         | 0.01%   |
| Linksys                           | 1         | 0.01%   |
| ASUSTek Computer (wrong ID)       | 1         | 0.01%   |
| Askey Computer                    | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1434      | 11.11%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 798       | 6.18%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 636       | 4.93%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 587       | 4.55%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 524       | 4.06%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 416       | 3.22%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 404       | 3.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 379       | 2.94%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 353       | 2.73%   |
| Broadcom BCM43142 802.11b/g/n                                           | 318       | 2.46%   |
| Intel Wi-Fi 6 AX201                                                     | 302       | 2.34%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 281       | 2.18%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 222       | 1.72%   |
| Intel Wireless 8265 / 8275                                              | 221       | 1.71%   |
| Intel Wi-Fi 6 AX200                                                     | 209       | 1.62%   |
| Intel Wireless 7265                                                     | 206       | 1.6%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 197       | 1.53%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 196       | 1.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 193       | 1.5%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 186       | 1.44%   |
| Intel WiFi Link 5100                                                    | 157       | 1.22%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 147       | 1.14%   |
| Intel Wireless 3165                                                     | 140       | 1.08%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 140       | 1.08%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 138       | 1.07%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 136       | 1.05%   |
| Intel Wireless 7260                                                     | 132       | 1.02%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 128       | 0.99%   |
| Intel Centrino Wireless-N 130                                           | 128       | 0.99%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 115       | 0.89%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 113       | 0.88%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 103       | 0.8%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 100       | 0.77%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 99        | 0.77%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 92        | 0.71%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 91        | 0.71%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 87        | 0.67%   |
| Intel Centrino Wireless-N 2230                                          | 85        | 0.66%   |
| Intel WiMAX/WiFi Link 5150                                              | 84        | 0.65%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 82        | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 6509      | 57.68%  |
| Qualcomm Atheros                       | 1448      | 12.83%  |
| Intel                                  | 960       | 8.51%   |
| Broadcom                               | 726       | 6.43%   |
| Marvell Technology Group               | 488       | 4.32%   |
| Broadcom Limited                       | 223       | 1.98%   |
| JMicron Technology                     | 118       | 1.05%   |
| Attansic Technology                    | 113       | 1%      |
| Xiaomi                                 | 100       | 0.89%   |
| Huawei Technologies                    | 72        | 0.64%   |
| Nvidia                                 | 70        | 0.62%   |
| Samsung Electronics                    | 54        | 0.48%   |
| Silicon Integrated Systems [SiS]       | 48        | 0.43%   |
| MediaTek                               | 40        | 0.35%   |
| ZTE WCDMA Technologies MSM             | 38        | 0.34%   |
| ASIX Electronics                       | 38        | 0.34%   |
| TP-Link                                | 32        | 0.28%   |
| Qualcomm                               | 26        | 0.23%   |
| Gemtek                                 | 20        | 0.18%   |
| Lenovo                                 | 19        | 0.17%   |
| D-Link                                 | 16        | 0.14%   |
| Vimtron Electronics                    | 14        | 0.12%   |
| OPPO Electronics                       | 12        | 0.11%   |
| VIA Technologies                       | 8         | 0.07%   |
| Hewlett-Packard                        | 8         | 0.07%   |
| ICS Advent                             | 7         | 0.06%   |
| HTC (High Tech Computer)               | 7         | 0.06%   |
| HMD Global                             | 7         | 0.06%   |
| Apple                                  | 7         | 0.06%   |
| DisplayLink                            | 6         | 0.05%   |
| Sony Ericsson Mobile Communications AB | 5         | 0.04%   |
| NTmore                                 | 5         | 0.04%   |
| Google                                 | 5         | 0.04%   |
| T & A Mobile Phones                    | 4         | 0.04%   |
| GCT Semiconductor                      | 4         | 0.04%   |
| Spreadtrum Communications              | 3         | 0.03%   |
| LG Electronics                         | 3         | 0.03%   |
| ASUSTek Computer                       | 3         | 0.03%   |
| Motorola PCS                           | 2         | 0.02%   |
| LeEco                                  | 2         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 4439      | 39.18%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 1698      | 14.99%  |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 277       | 2.44%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 249       | 2.2%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 200       | 1.77%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 164       | 1.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 147       | 1.3%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 144       | 1.27%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 140       | 1.24%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 133       | 1.17%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 125       | 1.1%    |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 123       | 1.09%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 116       | 1.02%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 113       | 1%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 112       | 0.99%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 107       | 0.94%   |
| Intel WiMAX Connection 2400m                                                   | 102       | 0.9%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 98        | 0.86%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 84        | 0.74%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 84        | 0.74%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 81        | 0.71%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 79        | 0.7%    |
| Intel Ethernet Connection (13) I219-V                                          | 75        | 0.66%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 72        | 0.64%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 70        | 0.62%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 67        | 0.59%   |
| Intel Ethernet Connection (6) I219-V                                           | 66        | 0.58%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 63        | 0.56%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 60        | 0.53%   |
| Intel 82577LM Gigabit Network Connection                                       | 55        | 0.49%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 51        | 0.45%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 49        | 0.43%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 47        | 0.41%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 47        | 0.41%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 46        | 0.41%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 45        | 0.4%    |
| Intel Ethernet Connection (10) I219-V                                          | 40        | 0.35%   |
| Intel Ethernet Connection (4) I219-V                                           | 39        | 0.34%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 38        | 0.34%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 37        | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 12478     | 53%     |
| Ethernet | 10786     | 45.82%  |
| Modem    | 267       | 1.13%   |
| Unknown  | 11        | 0.05%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 10195     | 77.65%  |
| Ethernet | 2931      | 22.32%  |
| Modem    | 4         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 10252     | 80.49%  |
| 1     | 2201      | 17.28%  |
| 0     | 260       | 2.04%   |
| 3     | 24        | 0.19%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 12485     | 97.63%  |
| Yes  | 303       | 2.37%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2611      | 28.16%  |
| Qualcomm Atheros Communications | 1244      | 13.42%  |
| Realtek Semiconductor           | 1172      | 12.64%  |
| IMC Networks                    | 789       | 8.51%   |
| Lite-On Technology              | 654       | 7.05%   |
| Broadcom                        | 640       | 6.9%    |
| Foxconn / Hon Hai               | 575       | 6.2%    |
| Ralink                          | 197       | 2.12%   |
| ASUSTek Computer                | 194       | 2.09%   |
| Realtek                         | 164       | 1.77%   |
| Foxconn International           | 158       | 1.7%    |
| Toshiba                         | 156       | 1.68%   |
| Hewlett-Packard                 | 132       | 1.42%   |
| Cambridge Silicon Radio         | 128       | 1.38%   |
| Dell                            | 113       | 1.22%   |
| Apple                           | 100       | 1.08%   |
| Alps Electric                   | 67        | 0.72%   |
| MediaTek                        | 40        | 0.43%   |
| Ralink Technology               | 38        | 0.41%   |
| Opticis                         | 33        | 0.36%   |
| Chicony Electronics             | 23        | 0.25%   |
| Micro Star International        | 12        | 0.13%   |
| Askey Computer                  | 7         | 0.08%   |
| USI                             | 6         | 0.06%   |
| Taiyo Yuden                     | 5         | 0.05%   |
| TP-Link                         | 3         | 0.03%   |
| Integrated System Solution      | 3         | 0.03%   |
| Samsung Electronics             | 2         | 0.02%   |
| Qcom                            | 2         | 0.02%   |
| Unknown                         | 2         | 0.02%   |
| Syntek                          | 1         | 0.01%   |
| ISSC                            | 1         | 0.01%   |
| Fujitsu                         | 1         | 0.01%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 805       | 8.68%   |
| Realtek Bluetooth Radio                                                             | 657       | 7.08%   |
| Intel AX201 Bluetooth                                                               | 534       | 5.76%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 525       | 5.66%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 376       | 4.05%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 372       | 4.01%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 288       | 3.1%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 261       | 2.81%   |
| IMC Networks Bluetooth Radio                                                        | 257       | 2.77%   |
| Intel AX200 Bluetooth                                                               | 209       | 2.25%   |
| Intel Bluetooth Device                                                              | 201       | 2.17%   |
| Ralink RT3290 Bluetooth                                                             | 197       | 2.12%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 191       | 2.06%   |
| IMC Networks Bluetooth Device                                                       | 176       | 1.9%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 167       | 1.8%    |
| Lite-On Atheros AR3012 Bluetooth                                                    | 165       | 1.78%   |
| Realtek Bluetooth Radio                                                             | 164       | 1.77%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 156       | 1.68%   |
| Lite-On Bluetooth Device                                                            | 147       | 1.58%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 147       | 1.58%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 140       | 1.51%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 128       | 1.38%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 110       | 1.19%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 109       | 1.17%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 107       | 1.15%   |
| Realtek RTL8723B Bluetooth                                                          | 103       | 1.11%   |
| Broadcom BCM2045 Bluetooth                                                          | 82        | 0.88%   |
| IMC Networks Wireless_Device                                                        | 81        | 0.87%   |
| Qualcomm Atheros Bluetooth                                                          | 73        | 0.79%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 71        | 0.77%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                                               | 66        | 0.71%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 65        | 0.7%    |
| Broadcom HP Portable Valentine                                                      | 62        | 0.67%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 60        | 0.65%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 60        | 0.65%   |
| Toshiba Integrated Bluetooth HCI                                                    | 59        | 0.64%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 59        | 0.64%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 59        | 0.64%   |
| ASUS BT-253 Bluetooth Adapter                                                       | 57        | 0.61%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 55        | 0.59%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 9434      | 64.69%  |
| AMD                                          | 3371      | 23.11%  |
| Nvidia                                       | 1277      | 8.76%   |
| C-Media Electronics                          | 103       | 0.71%   |
| Silicon Integrated Systems [SiS]             | 76        | 0.52%   |
| Logitech                                     | 25        | 0.17%   |
| Creative Technology                          | 24        | 0.16%   |
| Realtek Semiconductor                        | 22        | 0.15%   |
| JMTek                                        | 20        | 0.14%   |
| Generalplus Technology                       | 16        | 0.11%   |
| Texas Instruments                            | 15        | 0.1%    |
| Lenovo                                       | 15        | 0.1%    |
| VIA Technologies                             | 12        | 0.08%   |
| GN Netcom                                    | 11        | 0.08%   |
| Plantronics                                  | 10        | 0.07%   |
| Promethean Limited                           | 8         | 0.05%   |
| ASUSTek Computer                             | 8         | 0.05%   |
| Sennheiser Communications                    | 7         | 0.05%   |
| SteelSeries ApS                              | 6         | 0.04%   |
| Samson Technologies                          | 6         | 0.04%   |
| Focusrite-Novation                           | 6         | 0.04%   |
| Yamaha                                       | 5         | 0.03%   |
| A4Tech                                       | 5         | 0.03%   |
| Zoran Co. Personal Media Division (Nogatech) | 4         | 0.03%   |
| Thesycon Systemsoftware & Consulting         | 4         | 0.03%   |
| Razer USA                                    | 4         | 0.03%   |
| Hewlett-Packard                              | 4         | 0.03%   |
| SAVITECH                                     | 3         | 0.02%   |
| Nordic Semiconductor ASA                     | 3         | 0.02%   |
| Kingston Technology                          | 3         | 0.02%   |
| GYROCOM C&C                                  | 3         | 0.02%   |
| Apple                                        | 3         | 0.02%   |
| Zhaoxin                                      | 2         | 0.01%   |
| XMOS                                         | 2         | 0.01%   |
| TTGK Technology                              | 2         | 0.01%   |
| Sony                                         | 2         | 0.01%   |
| Samsung Electronics                          | 2         | 0.01%   |
| Roland                                       | 2         | 0.01%   |
| Microsoft                                    | 2         | 0.01%   |
| M-Audio                                      | 2         | 0.01%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1534      | 8.58%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1053      | 5.89%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 1039      | 5.81%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 843       | 4.72%   |
| AMD FCH Azalia Controller                                                                         | 774       | 4.33%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 745       | 4.17%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 678       | 3.79%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 612       | 3.42%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 606       | 3.39%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 571       | 3.19%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 444       | 2.48%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 380       | 2.13%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 376       | 2.1%    |
| AMD Kabini HDMI/DP Audio                                                                          | 367       | 2.05%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 355       | 1.99%   |
| Intel 8 Series HD Audio Controller                                                                | 355       | 1.99%   |
| Intel Cannon Lake PCH cAVS                                                                        | 297       | 1.66%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 297       | 1.66%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 284       | 1.59%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 282       | 1.58%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 264       | 1.48%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 253       | 1.42%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 245       | 1.37%   |
| AMD High Definition Audio Controller                                                              | 242       | 1.35%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 235       | 1.31%   |
| AMD Wrestler HDMI Audio                                                                           | 227       | 1.27%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 221       | 1.24%   |
| AMD Trinity HDMI Audio Controller                                                                 | 219       | 1.22%   |
| Intel Broadwell-U Audio Controller                                                                | 210       | 1.17%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 207       | 1.16%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 192       | 1.07%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 170       | 0.95%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 170       | 0.95%   |
| Nvidia High Definition Audio Controller                                                           | 141       | 0.79%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 140       | 0.78%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 138       | 0.77%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 129       | 0.72%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 128       | 0.72%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 120       | 0.67%   |
| Intel CM238 HD Audio Controller                                                                   | 105       | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Samsung Electronics                | 3006      | 23.52%  |
| SK hynix                           | 2433      | 19.03%  |
| Unknown                            | 1571      | 12.29%  |
| Kingston                           | 1403      | 10.98%  |
| Micron Technology                  | 1111      | 8.69%   |
| Elpida                             | 482       | 3.77%   |
| Nanya Technology                   | 389       | 3.04%   |
| Ramaxel Technology                 | 363       | 2.84%   |
| Crucial                            | 340       | 2.66%   |
| A-DATA Technology                  | 340       | 2.66%   |
| AMD                                | 162       | 1.27%   |
| ASint Technology                   | 128       | 1%      |
| Unknown (ABCD)                     | 110       | 0.86%   |
| Patriot                            | 103       | 0.81%   |
| Corsair                            | 95        | 0.74%   |
| Goldkey                            | 80        | 0.63%   |
| 48spaces                           | 80        | 0.63%   |
| SHARETRONIC                        | 53        | 0.41%   |
| Foxline                            | 50        | 0.39%   |
| ACPI Digital                       | 43        | 0.34%   |
| Apacer                             | 40        | 0.31%   |
| Unknown                            | 40        | 0.31%   |
| Transcend                          | 39        | 0.31%   |
| GOODRAM                            | 34        | 0.27%   |
| Qimonda                            | 28        | 0.22%   |
| Kllisre                            | 26        | 0.2%    |
| Unifosa                            | 23        | 0.18%   |
| Qumo                               | 19        | 0.15%   |
| Toshiba                            | 16        | 0.13%   |
| ChangXin Memory                    | 16        | 0.13%   |
| Silicon Power                      | 13        | 0.1%    |
| Kingmax                            | 8         | 0.06%   |
| Kingmax Semiconductor              | 7         | 0.05%   |
| Lexar Co Limited                   | 5         | 0.04%   |
| Ankowall                           | 5         | 0.04%   |
| Unknown (8AD6)                     | 4         | 0.03%   |
| Kimtigo Semiconductor (HK) Limited | 4         | 0.03%   |
| Unknown (0x0BEC)                   | 3         | 0.02%   |
| Unknown (08AE)                     | 3         | 0.02%   |
| SGS/Thomson                        | 3         | 0.02%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 229       | 1.66%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 156       | 1.13%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s                     | 150       | 1.08%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM 4199MT/s                          | 149       | 1.08%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 139       | 1.01%   |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s                  | 137       | 0.99%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s                     | 130       | 0.94%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 126       | 0.91%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                             | 122       | 0.88%   |
| Unknown RAM Module 2048MB SODIMM DDR2                                     | 111       | 0.8%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 111       | 0.8%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 104       | 0.75%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s          | 99        | 0.72%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s                     | 96        | 0.69%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s                     | 96        | 0.69%   |
| Unknown RAM Module 1024MB SODIMM DDR2                                     | 95        | 0.69%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 91        | 0.66%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 91        | 0.66%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                             | 90        | 0.65%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s                     | 85        | 0.61%   |
| 48spaces RAM 012345678901234567890123456789012345 2GB SODIMM DDR3 667MT/s | 79        | 0.57%   |
| A-DATA RAM AD73I1C1674EV 4GB SODIMM DDR3 1334MT/s                         | 77        | 0.56%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s                    | 74        | 0.54%   |
| Unknown RAM Module 4096MB SODIMM DDR3                                     | 71        | 0.51%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s                     | 71        | 0.51%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 66        | 0.48%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s                    | 65        | 0.47%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s                      | 65        | 0.47%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s                     | 63        | 0.46%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s                    | 61        | 0.44%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s                     | 60        | 0.43%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s                     | 60        | 0.43%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s                             | 59        | 0.43%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 59        | 0.43%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s                    | 59        | 0.43%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                | 58        | 0.42%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s                     | 57        | 0.41%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s                     | 56        | 0.41%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s                    | 55        | 0.4%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s               | 55        | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 5358      | 50%     |
| DDR4    | 2807      | 26.19%  |
| DDR2    | 1151      | 10.74%  |
| SDRAM   | 527       | 4.92%   |
| LPDDR4  | 336       | 3.14%   |
| Unknown | 136       | 1.27%   |
| DDR     | 134       | 1.25%   |
| DRAM    | 100       | 0.93%   |
| LPDDR3  | 86        | 0.8%    |
| LPDDR5  | 46        | 0.43%   |
| DDR5    | 35        | 0.33%   |
| SRAM    | 1         | 0.01%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 9850      | 93.63%  |
| Row Of Chips | 543       | 5.16%   |
| DIMM         | 95        | 0.9%    |
| Chip         | 24        | 0.23%   |
| Unknown      | 8         | 0.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Notebooks | Percent |
|---------|-----------|---------|
| 4096    | 4392      | 35.49%  |
| 2048    | 3258      | 26.33%  |
| 8192    | 2859      | 23.1%   |
| 1024    | 1070      | 8.65%   |
| 16384   | 523       | 4.23%   |
| 512     | 141       | 1.14%   |
| 32768   | 102       | 0.82%   |
| 256     | 16        | 0.13%   |
| 12288   | 5         | 0.04%   |
| Unknown | 5         | 0.04%   |
| 1536    | 3         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 3207      | 26.9%   |
| 1334    | 1351      | 11.33%  |
| 2667    | 1312      | 11%     |
| 3200    | 1200      | 10.06%  |
| 1333    | 853       | 7.15%   |
| 667     | 702       | 5.89%   |
| Unknown | 658       | 5.52%   |
| 2400    | 550       | 4.61%   |
| 4199    | 288       | 2.42%   |
| 800     | 269       | 2.26%   |
| 1067    | 258       | 2.16%   |
| 2133    | 244       | 2.05%   |
| 533     | 160       | 1.34%   |
| 3266    | 150       | 1.26%   |
| 2048    | 110       | 0.92%   |
| 1066    | 108       | 0.91%   |
| 975     | 67        | 0.56%   |
| 4267    | 66        | 0.55%   |
| 1867    | 59        | 0.49%   |
| 333     | 48        | 0.4%    |
| 6400    | 45        | 0.38%   |
| 4800    | 34        | 0.29%   |
| 3733    | 32        | 0.27%   |
| 400     | 27        | 0.23%   |
| 1639    | 23        | 0.19%   |
| 4266    | 22        | 0.18%   |
| 1866    | 20        | 0.17%   |
| 8400    | 17        | 0.14%   |
| 2933    | 9         | 0.08%   |
| 200     | 4         | 0.03%   |
| 65535   | 3         | 0.03%   |
| 5600    | 3         | 0.03%   |
| 2666    | 3         | 0.03%   |
| 1776    | 3         | 0.03%   |
| 266     | 3         | 0.03%   |
| 100     | 3         | 0.03%   |
| 1       | 3         | 0.03%   |
| 2800    | 2         | 0.02%   |
| 2267    | 2         | 0.02%   |
| 666     | 2         | 0.02%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 66        | 27.39%  |
| Canon                  | 47        | 19.5%   |
| Samsung Electronics    | 38        | 15.77%  |
| Seiko Epson            | 22        | 9.13%   |
| Brother Industries     | 17        | 7.05%   |
| Xerox                  | 13        | 5.39%   |
| Panasonic (Matsushita) | 12        | 4.98%   |
| Ricoh                  | 9         | 3.73%   |
| Pantum                 | 7         | 2.9%    |
| Kyocera                | 4         | 1.66%   |
| Xiaomi                 | 2         | 0.83%   |
| Prolific Technology    | 1         | 0.41%   |
| NXP Semiconductors     | 1         | 0.41%   |
| Lexmark International  | 1         | 0.41%   |
| iDPRT                  | 1         | 0.41%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| HP LaserJet 1020                                             | 9         | 3.72%   |
| Samsung SCX-4200 series                                      | 6         | 2.48%   |
| Samsung SCX-3400 Series                                      | 6         | 2.48%   |
| Panasonic (Matsushita) KX-MB1500RU                           | 6         | 2.48%   |
| HP LaserJet P1102                                            | 6         | 2.48%   |
| Samsung SCX-3200 Series                                      | 5         | 2.07%   |
| Panasonic (Matsushita) KX-MB2030 Multifunction Laser Printer | 5         | 2.07%   |
| Xerox B205                                                   | 4         | 1.65%   |
| Samsung ML-1210 Printer                                      | 4         | 1.65%   |
| Samsung M2020 Series                                         | 4         | 1.65%   |
| HP LaserJet 1200                                             | 4         | 1.65%   |
| Canon PIXMA MG2500 Series                                    | 4         | 1.65%   |
| Canon LBP6020                                                | 4         | 1.65%   |
| Brother HL-1110 series                                       | 4         | 1.65%   |
| Seiko Epson L210 Series                                      | 3         | 1.24%   |
| Seiko Epson L200 Series                                      | 3         | 1.24%   |
| Samsung ML-1640 Series Laser Printer                         | 3         | 1.24%   |
| HP LaserJet P1005                                            | 3         | 1.24%   |
| HP LaserJet 1018                                             | 3         | 1.24%   |
| HP DeskJet 2300 series                                       | 3         | 1.24%   |
| Canon MF4010 series                                          | 3         | 1.24%   |
| Canon LBP7010C/7018C                                         | 3         | 1.24%   |
| Canon LBP3010/LBP3018/LBP3050                                | 3         | 1.24%   |
| Canon LaserShot LBP-1120 Printer                             | 3         | 1.24%   |
| Canon G1000 series                                           | 3         | 1.24%   |
| Brother HL-L2300D series                                     | 3         | 1.24%   |
| Xiaomi MiMouse 2                                             | 2         | 0.83%   |
| Xerox Phaser 3020                                            | 2         | 0.83%   |
| Seiko Epson USB2.0 Printer                                   | 2         | 0.83%   |
| Seiko Epson Printer                                          | 2         | 0.83%   |
| Seiko Epson L132 Series                                      | 2         | 0.83%   |
| Seiko Epson L120 Series                                      | 2         | 0.83%   |
| Samsung ML-1865                                              | 2         | 0.83%   |
| Samsung M2070 Series                                         | 2         | 0.83%   |
| Ricoh SP 150SUw                                              | 2         | 0.83%   |
| Pantum P2200 series                                          | 2         | 0.83%   |
| Pantum M6500 series                                          | 2         | 0.83%   |
| Kyocera FS-1120MFP                                           | 2         | 0.83%   |
| HP LaserJet Professional P1102w                              | 2         | 0.83%   |
| HP LaserJet 1320                                             | 2         | 0.83%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Seiko Epson                 | 15        | 34.09%  |
| Canon                       | 10        | 22.73%  |
| Hewlett-Packard             | 8         | 18.18%  |
| Mustek Systems              | 5         | 11.36%  |
| Ultima Electronics          | 2         | 4.55%   |
| KYE Systems (Mouse Systems) | 2         | 4.55%   |
| Acer Peripherals (now BenQ) | 2         | 4.55%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 5         | 11.36%  |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 2         | 4.55%   |
| Seiko Epson GT-F670 [Perfection V200 Photo]                                           | 2         | 4.55%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 2         | 4.55%   |
| Mustek Systems BearPaw 1200 TA/CS                                                     | 2         | 4.55%   |
| HP ScanJet 3770                                                                       | 2         | 4.55%   |
| HP ScanJet 2400c                                                                      | 2         | 4.55%   |
| HP Scanjet 200                                                                        | 2         | 4.55%   |
| Canon CanoScan LIDE 25                                                                | 2         | 4.55%   |
| Canon CanoScan LiDE 120                                                               | 2         | 4.55%   |
| Canon CanoScan LiDE 110                                                               | 2         | 4.55%   |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]                                           | 1         | 2.27%   |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 1         | 2.27%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 1         | 2.27%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                   | 1         | 2.27%   |
| Seiko Epson GT-9700F [Perfection 2450 PHOTO]                                          | 1         | 2.27%   |
| Seiko Epson GT-7400U [Perfection 1270]                                                | 1         | 2.27%   |
| Mustek Systems SNAPSCAN e22                                                           | 1         | 2.27%   |
| Mustek Systems BearPaw 2448 CU Pro                                                    | 1         | 2.27%   |
| Mustek Systems BearPaw 2400 TA Plus                                                   | 1         | 2.27%   |
| KYE Systems (Mouse Systems) ColorPage-Vivid4                                          | 1         | 2.27%   |
| KYE Systems (Mouse Systems) ColorPage-Vivid 1200 XE                                   | 1         | 2.27%   |
| HP ScanJet G4010                                                                      | 1         | 2.27%   |
| HP Scanjet 300                                                                        | 1         | 2.27%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 1         | 2.27%   |
| Canon CanoScan LiDE 70                                                                | 1         | 2.27%   |
| Canon CanoScan LiDE 220                                                               | 1         | 2.27%   |
| Canon CanoScan 4400F                                                                  | 1         | 2.27%   |
| Acer Peripherals (now BenQ) Benq 5150/5250                                            | 1         | 2.27%   |
| Acer Peripherals (now BenQ) Benq 5000                                                 | 1         | 2.27%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 2793      | 25.02%  |
| IMC Networks                           | 1367      | 12.24%  |
| Bison Electronics                      | 749       | 6.71%   |
| Realtek Semiconductor                  | 746       | 6.68%   |
| Suyin                                  | 660       | 5.91%   |
| Microdia                               | 571       | 5.11%   |
| Sunplus Innovation Technology          | 539       | 4.83%   |
| Quanta                                 | 516       | 4.62%   |
| Silicon Motion                         | 420       | 3.76%   |
| Cheng Uei Precision Industry (Foxlink) | 404       | 3.62%   |
| Syntek                                 | 341       | 3.05%   |
| Acer                                   | 327       | 2.93%   |
| Alcor Micro                            | 299       | 2.68%   |
| Z-Star Microelectronics                | 167       | 1.5%    |
| Lite-On Technology                     | 130       | 1.16%   |
| Ricoh                                  | 122       | 1.09%   |
| Luxvisions Innotech Limited            | 119       | 1.07%   |
| Apple                                  | 119       | 1.07%   |
| ALi                                    | 108       | 0.97%   |
| DigiTech                               | 85        | 0.76%   |
| Logitech                               | 65        | 0.58%   |
| Sonix Technology                       | 58        | 0.52%   |
| SunplusIT                              | 46        | 0.41%   |
| Lenovo                                 | 41        | 0.37%   |
| Samsung Electronics                    | 37        | 0.33%   |
| Primax Electronics                     | 36        | 0.32%   |
| icSpring                               | 33        | 0.3%    |
| Y Media                                | 24        | 0.21%   |
| Importek                               | 23        | 0.21%   |
| Sunplus Technology                     | 18        | 0.16%   |
| Unknown                                | 17        | 0.15%   |
| OmniVision Technologies                | 15        | 0.13%   |
| GEMBIRD                                | 15        | 0.13%   |
| USB Camera CS                          | 14        | 0.13%   |
| Image Processor                        | 9         | 0.08%   |
| Genesys Logic                          | 9         | 0.08%   |
| Shine-optics                           | 8         | 0.07%   |
| Pixart Imaging                         | 7         | 0.06%   |
| ShineTech                              | 6         | 0.05%   |
| Nebraska Furniture Mart                | 6         | 0.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony HD WebCam                                | 293       | 2.62%   |
| Chicony Integrated Camera                        | 270       | 2.41%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 257       | 2.3%    |
| Chicony Lenovo EasyCamera                        | 228       | 2.04%   |
| Bison Lenovo Integrated Webcam                   | 215       | 1.92%   |
| IMC Networks USB2.0 HD UVC WebCam                | 213       | 1.9%    |
| Sunplus HD WebCam                                | 175       | 1.57%   |
| Microdia Integrated_Webcam_HD                    | 164       | 1.47%   |
| IMC Networks Integrated Camera                   | 158       | 1.41%   |
| IMC Networks UVC VGA Webcam                      | 144       | 1.29%   |
| Chicony USB2.0 HD UVC WebCam                     | 140       | 1.25%   |
| Chicony USB 2.0 Camera                           | 125       | 1.12%   |
| Bison Lenovo EasyCamera                          | 117       | 1.05%   |
| Realtek Integrated_Webcam_HD                     | 116       | 1.04%   |
| Acer BisonCam, NB Pro                            | 112       | 1%      |
| Chicony VGA WebCam                               | 111       | 0.99%   |
| Quanta VGA WebCam                                | 110       | 0.98%   |
| Chicony HP Webcam                                | 108       | 0.97%   |
| Syntek Integrated Camera                         | 107       | 0.96%   |
| Realtek Lenovo EasyCamera                        | 101       | 0.9%    |
| IMC Networks HD Camera                           | 94        | 0.84%   |
| Chicony USB2.0 VGA UVC WebCam                    | 93        | 0.83%   |
| Alcor Micro Asus Integrated Webcam               | 90        | 0.8%    |
| Silicon Motion WebCam SC-0311139N                | 86        | 0.77%   |
| IMC Networks Integrated Webcam                   | 81        | 0.72%   |
| Syntek Lenovo EasyCamera                         | 80        | 0.72%   |
| Chicony 2.0M UVC Webcam / CNF7129                | 80        | 0.72%   |
| Realtek USB Camera                               | 79        | 0.71%   |
| Suyin Acer/HP Integrated Webcam [CN0314]         | 78        | 0.7%    |
| Chicony HP Truevision HD                         | 78        | 0.7%    |
| Sunplus Integrated_Webcam_HD                     | 77        | 0.69%   |
| DigiTech USB 2.0 PC Camera                       | 77        | 0.69%   |
| ALi Gateway Webcam                               | 72        | 0.64%   |
| Alcor Micro USB 2.0 Camera                       | 72        | 0.64%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 71        | 0.63%   |
| IMC Networks ov9734_azurewave_camera             | 70        | 0.63%   |
| Bison Integrated Camera                          | 70        | 0.63%   |
| Bison HD Webcam                                  | 69        | 0.62%   |
| Quanta ov9734_techfront_camera                   | 68        | 0.61%   |
| Chicony EasyCamera                               | 67        | 0.6%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 461       | 30.37%  |
| Shenzhen Goodix Technology         | 322       | 21.21%  |
| Synaptics                          | 215       | 14.16%  |
| AuthenTec                          | 142       | 9.35%   |
| Upek                               | 112       | 7.38%   |
| Elan Microelectronics              | 102       | 6.72%   |
| LighTuning Technology              | 96        | 6.32%   |
| STMicroelectronics                 | 35        | 2.31%   |
| Realtek USB2.0 Finger Print Bridge | 16        | 1.05%   |
| Focal-systems.Corp                 | 14        | 0.92%   |
| Samsung Electronics                | 1         | 0.07%   |
| GDMicroelectronics                 | 1         | 0.07%   |
| FocalTech                          | 1         | 0.07%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 265       | 17.46%  |
| Validity Sensors Fingerprint scanner                                       | 104       | 6.85%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 94        | 6.19%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 89        | 5.86%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 75        | 4.94%   |
| Elan ELAN:Fingerprint                                                      | 68        | 4.48%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 67        | 4.41%   |
| Shenzhen Goodix Fingerprint Reader                                         | 49        | 3.23%   |
| LighTuning Fingerprint Reader                                              | 45        | 2.96%   |
| AuthenTec AES1600                                                          | 43        | 2.83%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 35        | 2.31%   |
| STMicroelectronics Fingerprint Reader                                      | 35        | 2.31%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 35        | 2.31%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 33        | 2.17%   |
| Elan ELAN:ARM-M4                                                           | 31        | 2.04%   |
| Validity Sensors VFS491                                                    | 28        | 1.84%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 28        | 1.84%   |
| AuthenTec AES2810                                                          | 28        | 1.84%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 27        | 1.78%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 25        | 1.65%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 22        | 1.45%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 21        | 1.38%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 19        | 1.25%   |
| Upek TCS5B Fingerprint sensor                                              | 18        | 1.19%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 18        | 1.19%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 18        | 1.19%   |
| Synaptics Fingerprint reader [HP G6]                                       | 16        | 1.05%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 16        | 1.05%   |
| Validity Sensors Synaptics WBDI                                            | 15        | 0.99%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 15        | 0.99%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 14        | 0.92%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 14        | 0.92%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 12        | 0.79%   |
| Synaptics UWP WBDI Device                                                  | 12        | 0.79%   |
| Synaptics  WBDI                                                            | 12        | 0.79%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 11        | 0.72%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 10        | 0.66%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 9         | 0.59%   |
| Shenzhen Goodix FingerPrint                                                | 8         | 0.53%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 8         | 0.53%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 105       | 37.63%  |
| Broadcom                  | 90        | 32.26%  |
| Upek                      | 26        | 9.32%   |
| O2 Micro                  | 21        | 7.53%   |
| Lenovo                    | 16        | 5.73%   |
| Yubico.com                | 5         | 1.79%   |
| Gemalto (was Gemplus)     | 4         | 1.43%   |
| Aladdin R.D.              | 4         | 1.43%   |
| Aladdin Knowledge Systems | 4         | 1.43%   |
| Aktiv                     | 3         | 1.08%   |
| Microchip Technology      | 1         | 0.36%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 103       | 36.92%  |
| Broadcom BCM5880 Secure Applications Processor                               | 34        | 12.19%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 26        | 9.32%   |
| Broadcom 5880                                                                | 20        | 7.17%   |
| Broadcom 58200                                                               | 20        | 7.17%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 18        | 6.45%   |
| Lenovo Integrated Smart Card Reader                                          | 16        | 5.73%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 16        | 5.73%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 5         | 1.79%   |
| Aladdin R.D. JaCarta                                                         | 4         | 1.43%   |
| Aladdin Knowledge Systems Token JC                                           | 4         | 1.43%   |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 1.08%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 1.08%   |
| Aktiv Rutoken lite                                                           | 3         | 1.08%   |
| Microchip Technology SMSC USX101x Reader                                     | 1         | 0.36%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.36%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.36%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.36%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 8727      | 66.08%  |
| 1     | 3584      | 27.14%  |
| 2     | 748       | 5.66%   |
| 3     | 119       | 0.9%    |
| 4     | 19        | 0.14%   |
| 5     | 6         | 0.05%   |
| 6     | 2         | 0.02%   |
| 7     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 1928      | 37.62%  |
| Fingerprint reader       | 1511      | 29.48%  |
| Net/wireless             | 462       | 9.01%   |
| Bluetooth                | 268       | 5.23%   |
| Multimedia controller    | 261       | 5.09%   |
| Chipcard                 | 240       | 4.68%   |
| Camera                   | 133       | 2.6%    |
| Communication controller | 83        | 1.62%   |
| Flash memory             | 67        | 1.31%   |
| Storage                  | 66        | 1.29%   |
| Card reader              | 30        | 0.59%   |
| Sound                    | 22        | 0.43%   |
| Net/ethernet             | 17        | 0.33%   |
| Modem                    | 13        | 0.25%   |
| Network                  | 7         | 0.14%   |
| Dvb card                 | 6         | 0.12%   |
| Storage/ide              | 4         | 0.08%   |
| Firewire controller      | 2         | 0.04%   |
| Wireless                 | 1         | 0.02%   |
| Unclassified device      | 1         | 0.02%   |
| Tv card                  | 1         | 0.02%   |
| Storage/raid             | 1         | 0.02%   |
| Storage/nvme             | 1         | 0.02%   |

