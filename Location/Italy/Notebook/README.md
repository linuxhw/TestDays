Linux in Italy - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Italy.

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

Total: 5138

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Aspire E5-573G              | [527a92f562](https://linux-hardware.org/?probe=527a92f562) | Dec 31, 2022 |
| HP            | Notebook                    | [d25df9daf4](https://linux-hardware.org/?probe=d25df9daf4) | Dec 31, 2022 |
| ASUSTek       | ProArt StudioBook H5600Q... | [07ca2ed63d](https://linux-hardware.org/?probe=07ca2ed63d) | Dec 31, 2022 |
| Dell          | XPS 9320                    | [c98fd80f29](https://linux-hardware.org/?probe=c98fd80f29) | Dec 31, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [60989ad0c4](https://linux-hardware.org/?probe=60989ad0c4) | Dec 31, 2022 |
| HP            | Compaq 6710b (KE207ES#AB... | [d7d0be3872](https://linux-hardware.org/?probe=d7d0be3872) | Dec 30, 2022 |
| Chuwi         | HeroBook                    | [1664994b07](https://linux-hardware.org/?probe=1664994b07) | Dec 30, 2022 |
| ASUSTek       | K55VD                       | [e4c90250df](https://linux-hardware.org/?probe=e4c90250df) | Dec 30, 2022 |
| MSI           | GP72MVR 7RFX                | [cefedef93c](https://linux-hardware.org/?probe=cefedef93c) | Dec 30, 2022 |
| Lenovo        | ThinkPad W541 20EF0011IX    | [a2f6a6831a](https://linux-hardware.org/?probe=a2f6a6831a) | Dec 30, 2022 |
| Lenovo        | ThinkPad W541 20EF0011IX    | [3f5a2c6ea1](https://linux-hardware.org/?probe=3f5a2c6ea1) | Dec 30, 2022 |
| ASUSTek       | X556UQK                     | [42a9dc760d](https://linux-hardware.org/?probe=42a9dc760d) | Dec 30, 2022 |
| Dell          | Inspiron 5593               | [bf0f36d69a](https://linux-hardware.org/?probe=bf0f36d69a) | Dec 30, 2022 |
| HP            | 255 G3                      | [89d6bd459c](https://linux-hardware.org/?probe=89d6bd459c) | Dec 30, 2022 |
| Dell          | Latitude E6410              | [0ee655e2cc](https://linux-hardware.org/?probe=0ee655e2cc) | Dec 29, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [2d653884d9](https://linux-hardware.org/?probe=2d653884d9) | Dec 29, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | [587aa5f819](https://linux-hardware.org/?probe=587aa5f819) | Dec 29, 2022 |
| Lenovo        | ThinkPad E580 20KS001RIX    | [4ca01731b4](https://linux-hardware.org/?probe=4ca01731b4) | Dec 29, 2022 |
| HP            | Compaq 6730s                | [9294bf57da](https://linux-hardware.org/?probe=9294bf57da) | Dec 28, 2022 |
| Lenovo        | ThinkPad E480 20KQS13M00    | [fb7e2874d3](https://linux-hardware.org/?probe=fb7e2874d3) | Dec 28, 2022 |
| Apple         | MacBookPro8,1               | [7b03f438db](https://linux-hardware.org/?probe=7b03f438db) | Dec 28, 2022 |
| Fujitsu       | LIFEBOOK A544               | [efdc6bb5cb](https://linux-hardware.org/?probe=efdc6bb5cb) | Dec 28, 2022 |
| Acer          | Aspire A315-55G             | [92155ba882](https://linux-hardware.org/?probe=92155ba882) | Dec 28, 2022 |
| HP            | ProBook 440 G6              | [6240bc3677](https://linux-hardware.org/?probe=6240bc3677) | Dec 28, 2022 |
| HP            | ProBook 440 G6              | [f5689c6edc](https://linux-hardware.org/?probe=f5689c6edc) | Dec 28, 2022 |
| HP            | EliteBook 850 G3            | [0dede5b37a](https://linux-hardware.org/?probe=0dede5b37a) | Dec 28, 2022 |
| System76      | Darter Pro                  | [a46000c111](https://linux-hardware.org/?probe=a46000c111) | Dec 28, 2022 |
| HP            | 250 G8 Notebook PC          | [7d79eadc7d](https://linux-hardware.org/?probe=7d79eadc7d) | Dec 28, 2022 |
| Teclast       | F15Plus 2                   | [71564a5900](https://linux-hardware.org/?probe=71564a5900) | Dec 27, 2022 |
| Teclast       | F15Plus 2                   | [4d10c4922e](https://linux-hardware.org/?probe=4d10c4922e) | Dec 27, 2022 |
| Packard Be... | EasyNote TJ65               | [57bfe7c99d](https://linux-hardware.org/?probe=57bfe7c99d) | Dec 27, 2022 |
| ASUSTek       | X550VXK                     | [301db79821](https://linux-hardware.org/?probe=301db79821) | Dec 27, 2022 |
| ASUSTek       | X550VXK                     | [039600625a](https://linux-hardware.org/?probe=039600625a) | Dec 27, 2022 |
| Dell          | XPS 9320                    | [7a2537eba2](https://linux-hardware.org/?probe=7a2537eba2) | Dec 27, 2022 |
| Dell          | Inspiron 15 3525            | [64a70af984](https://linux-hardware.org/?probe=64a70af984) | Dec 27, 2022 |
| System76      | Darter Pro                  | [c5aebaaece](https://linux-hardware.org/?probe=c5aebaaece) | Dec 27, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [d75dbe1e39](https://linux-hardware.org/?probe=d75dbe1e39) | Dec 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [1cf2ac2b8b](https://linux-hardware.org/?probe=1cf2ac2b8b) | Dec 27, 2022 |
| HP            | Pavilion 15                 | [9843ba5174](https://linux-hardware.org/?probe=9843ba5174) | Dec 26, 2022 |
| Notebook      | NP5x_NP6x_NP7xPNK_PNH_PN... | [792a203576](https://linux-hardware.org/?probe=792a203576) | Dec 26, 2022 |
| MSI           | GS76 Stealth 11UG           | [10e22b317f](https://linux-hardware.org/?probe=10e22b317f) | Dec 26, 2022 |
| Lenovo        | ThinkPad E590 20NB001AMX    | [047944fa9f](https://linux-hardware.org/?probe=047944fa9f) | Dec 26, 2022 |
| HP            | Laptop 15-da0xxx            | [96a4f739b8](https://linux-hardware.org/?probe=96a4f739b8) | Dec 26, 2022 |
| HP            | Laptop 15-da0xxx            | [19af161114](https://linux-hardware.org/?probe=19af161114) | Dec 26, 2022 |
| HP            | EliteBook 840 G4            | [1c5b59d2e4](https://linux-hardware.org/?probe=1c5b59d2e4) | Dec 26, 2022 |
| HP            | EliteBook 840 G4            | [730469b496](https://linux-hardware.org/?probe=730469b496) | Dec 26, 2022 |
| HP            | EliteBook 820 G1            | [6a2c20cb74](https://linux-hardware.org/?probe=6a2c20cb74) | Dec 26, 2022 |
| HP            | 255 G8 Notebook PC          | [2df8b7768a](https://linux-hardware.org/?probe=2df8b7768a) | Dec 26, 2022 |
| HP            | Compaq 6730s                | [ac1ae104e8](https://linux-hardware.org/?probe=ac1ae104e8) | Dec 26, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [38a87e716e](https://linux-hardware.org/?probe=38a87e716e) | Dec 26, 2022 |
| HP            | Compaq 6730s                | [0cc88159aa](https://linux-hardware.org/?probe=0cc88159aa) | Dec 26, 2022 |
| Lenovo        | ThinkPad X1 Carbon 34604... | [dfb555f802](https://linux-hardware.org/?probe=dfb555f802) | Dec 26, 2022 |
| Samsung       | RV420/RV520/RV720/E3530/... | [4665d79293](https://linux-hardware.org/?probe=4665d79293) | Dec 25, 2022 |
| SANTECH       | NHx0DB,DE                   | [a0996d42bd](https://linux-hardware.org/?probe=a0996d42bd) | Dec 25, 2022 |
| Toshiba       | Satellite Pro S500          | [cd547b04a1](https://linux-hardware.org/?probe=cd547b04a1) | Dec 25, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [ff90a6a029](https://linux-hardware.org/?probe=ff90a6a029) | Dec 25, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [faba7b00c6](https://linux-hardware.org/?probe=faba7b00c6) | Dec 25, 2022 |
| WYSE          | XM CLASS                    | [948bfb388d](https://linux-hardware.org/?probe=948bfb388d) | Dec 25, 2022 |
| HP            | EliteBook 8440p             | [571afe8b70](https://linux-hardware.org/?probe=571afe8b70) | Dec 24, 2022 |
| Dell          | XPS 9320                    | [f55956cac2](https://linux-hardware.org/?probe=f55956cac2) | Dec 24, 2022 |
| Dell          | Latitude 5590               | [f7011844b5](https://linux-hardware.org/?probe=f7011844b5) | Dec 24, 2022 |
| Dell          | Latitude 5590               | [3f1acac04f](https://linux-hardware.org/?probe=3f1acac04f) | Dec 24, 2022 |
| HP            | 255 G8 Notebook PC          | [3f72d88324](https://linux-hardware.org/?probe=3f72d88324) | Dec 24, 2022 |
| Dell          | Latitude 5590               | [e439eb94d4](https://linux-hardware.org/?probe=e439eb94d4) | Dec 24, 2022 |
| Dell          | Latitude 5590               | [816056e28e](https://linux-hardware.org/?probe=816056e28e) | Dec 24, 2022 |
| HUAWEI        | KPR-WX9                     | [e2b01c4a0f](https://linux-hardware.org/?probe=e2b01c4a0f) | Dec 23, 2022 |
| Dell          | Inspiron 15 5510            | [d53469cd41](https://linux-hardware.org/?probe=d53469cd41) | Dec 23, 2022 |
| Dell          | Inspiron 15 5510            | [9ddf91aa1b](https://linux-hardware.org/?probe=9ddf91aa1b) | Dec 23, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [f114731a78](https://linux-hardware.org/?probe=f114731a78) | Dec 23, 2022 |
| Acer          | Aspire A515-52G             | [586dd36eed](https://linux-hardware.org/?probe=586dd36eed) | Dec 23, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [214b2a3235](https://linux-hardware.org/?probe=214b2a3235) | Dec 23, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B3302CEA... | [756390ae0c](https://linux-hardware.org/?probe=756390ae0c) | Dec 23, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B3302CEA... | [c2dd56664a](https://linux-hardware.org/?probe=c2dd56664a) | Dec 23, 2022 |
| Timi          | TM1701                      | [2f28d7e2dc](https://linux-hardware.org/?probe=2f28d7e2dc) | Dec 23, 2022 |
| Timi          | TM1701                      | [dfb4f8774f](https://linux-hardware.org/?probe=dfb4f8774f) | Dec 23, 2022 |
| Dell          | XPS 9320                    | [7bb7ba7202](https://linux-hardware.org/?probe=7bb7ba7202) | Dec 23, 2022 |
| Medion        | X6816                       | [bafbf1ea90](https://linux-hardware.org/?probe=bafbf1ea90) | Dec 23, 2022 |
| Medion        | X6816                       | [ac9627e5d4](https://linux-hardware.org/?probe=ac9627e5d4) | Dec 23, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [db7dc4fa25](https://linux-hardware.org/?probe=db7dc4fa25) | Dec 22, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [e8ac233c29](https://linux-hardware.org/?probe=e8ac233c29) | Dec 22, 2022 |
| HP            | Compaq 6730b (GW687AV)      | [8c936284b0](https://linux-hardware.org/?probe=8c936284b0) | Dec 22, 2022 |
| Monster       | TULPAR T5 V20.1             | [23cb6e06f8](https://linux-hardware.org/?probe=23cb6e06f8) | Dec 22, 2022 |
| HP            | Pavilion dv9000 (RR329EA... | [6fc7281f2f](https://linux-hardware.org/?probe=6fc7281f2f) | Dec 22, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | [a62d8c781d](https://linux-hardware.org/?probe=a62d8c781d) | Dec 22, 2022 |
| HUAWEI        | VLT-WX0                     | [6f2d542a6e](https://linux-hardware.org/?probe=6f2d542a6e) | Dec 22, 2022 |
| Packard Be... | DOT S                       | [c26f1d77e6](https://linux-hardware.org/?probe=c26f1d77e6) | Dec 22, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [54273f1267](https://linux-hardware.org/?probe=54273f1267) | Dec 22, 2022 |
| ASUSTek       | 1215P                       | [a39ca1c22f](https://linux-hardware.org/?probe=a39ca1c22f) | Dec 21, 2022 |
| ASUSTek       | 1215P                       | [ed3dc80f1b](https://linux-hardware.org/?probe=ed3dc80f1b) | Dec 21, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | [543b6fc9db](https://linux-hardware.org/?probe=543b6fc9db) | Dec 21, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | [5ea57fb331](https://linux-hardware.org/?probe=5ea57fb331) | Dec 21, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | [c4f6f99d36](https://linux-hardware.org/?probe=c4f6f99d36) | Dec 21, 2022 |
| Dell          | Latitude E7470              | [e171eea812](https://linux-hardware.org/?probe=e171eea812) | Dec 21, 2022 |
| ASUSTek       | S551LB                      | [5e48f71064](https://linux-hardware.org/?probe=5e48f71064) | Dec 20, 2022 |
| HP            | Sona                        | [85c88dea70](https://linux-hardware.org/?probe=85c88dea70) | Dec 20, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | [a4549398af](https://linux-hardware.org/?probe=a4549398af) | Dec 20, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [2b8c2f06eb](https://linux-hardware.org/?probe=2b8c2f06eb) | Dec 20, 2022 |
| Notebook      | PCX0DX                      | [83c28a3013](https://linux-hardware.org/?probe=83c28a3013) | Dec 20, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [9f5a91c628](https://linux-hardware.org/?probe=9f5a91c628) | Dec 19, 2022 |
| Sony          | VGN-FW11E                   | [2d57afaa38](https://linux-hardware.org/?probe=2d57afaa38) | Dec 19, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [686a93a02a](https://linux-hardware.org/?probe=686a93a02a) | Dec 19, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [8e10fc1464](https://linux-hardware.org/?probe=8e10fc1464) | Dec 18, 2022 |
| ASUSTek       | 900SD                       | [43d2c88062](https://linux-hardware.org/?probe=43d2c88062) | Dec 18, 2022 |
| Lenovo        | ThinkPad R61 77324TG        | [90c300a51c](https://linux-hardware.org/?probe=90c300a51c) | Dec 18, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [7dc7a80819](https://linux-hardware.org/?probe=7dc7a80819) | Dec 18, 2022 |
| Acer          | TravelMate P253             | [97d650e93f](https://linux-hardware.org/?probe=97d650e93f) | Dec 18, 2022 |
| Dell          | Latitude E7470              | [262849f0f6](https://linux-hardware.org/?probe=262849f0f6) | Dec 18, 2022 |
| HP            | Laptop 15s-fq2xxx           | [ab6fd91b71](https://linux-hardware.org/?probe=ab6fd91b71) | Dec 17, 2022 |
| HP            | Laptop 15s-fq2xxx           | [1a23b502b9](https://linux-hardware.org/?probe=1a23b502b9) | Dec 17, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | [75126bccca](https://linux-hardware.org/?probe=75126bccca) | Dec 17, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [a54756ab6f](https://linux-hardware.org/?probe=a54756ab6f) | Dec 17, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [fc473cc90f](https://linux-hardware.org/?probe=fc473cc90f) | Dec 17, 2022 |
| WYSE          | XM CLASS                    | [8aac2f31cb](https://linux-hardware.org/?probe=8aac2f31cb) | Dec 17, 2022 |
| HP            | EliteBook 820 G3            | [5e5909e93f](https://linux-hardware.org/?probe=5e5909e93f) | Dec 17, 2022 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [feb5e321dc](https://linux-hardware.org/?probe=feb5e321dc) | Dec 16, 2022 |
| Acer          | TravelMate P253             | [80188fd5bf](https://linux-hardware.org/?probe=80188fd5bf) | Dec 16, 2022 |
| Toshiba       | Satellite M70               | [9415a97254](https://linux-hardware.org/?probe=9415a97254) | Dec 16, 2022 |
| Dell          | XPS 15 9520                 | [dcf616e068](https://linux-hardware.org/?probe=dcf616e068) | Dec 16, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | [665bd04471](https://linux-hardware.org/?probe=665bd04471) | Dec 16, 2022 |
| Alienware     | 15                          | [6da8e1748a](https://linux-hardware.org/?probe=6da8e1748a) | Dec 16, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [30fda215a5](https://linux-hardware.org/?probe=30fda215a5) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [d5cf351351](https://linux-hardware.org/?probe=d5cf351351) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [e2056deb8a](https://linux-hardware.org/?probe=e2056deb8a) | Dec 16, 2022 |
| HUAWEI        | BOM-WXX9                    | [dd664077fe](https://linux-hardware.org/?probe=dd664077fe) | Dec 16, 2022 |
| HP            | Laptop 15s-fq2xxx           | [d9c3d0a5cd](https://linux-hardware.org/?probe=d9c3d0a5cd) | Dec 16, 2022 |
| HP            | Laptop 15-da0xxx            | [d871acfe36](https://linux-hardware.org/?probe=d871acfe36) | Dec 16, 2022 |
| Toshiba       | Satellite M70               | [79506873c1](https://linux-hardware.org/?probe=79506873c1) | Dec 15, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [18d67ba2ab](https://linux-hardware.org/?probe=18d67ba2ab) | Dec 15, 2022 |
| Packard Be... | EasyNote TJ71               | [f722162e15](https://linux-hardware.org/?probe=f722162e15) | Dec 15, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [5e8318b8b8](https://linux-hardware.org/?probe=5e8318b8b8) | Dec 15, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [57ecebdc0f](https://linux-hardware.org/?probe=57ecebdc0f) | Dec 15, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [d5c9abda1e](https://linux-hardware.org/?probe=d5c9abda1e) | Dec 15, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | [1d57f3ab30](https://linux-hardware.org/?probe=1d57f3ab30) | Dec 15, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | [a1d6879fab](https://linux-hardware.org/?probe=a1d6879fab) | Dec 15, 2022 |
| HP            | Compaq 6735s                | [72d29aa11f](https://linux-hardware.org/?probe=72d29aa11f) | Dec 14, 2022 |
| Samsung       | 750XDA                      | [0120054e9f](https://linux-hardware.org/?probe=0120054e9f) | Dec 14, 2022 |
| ASUSTek       | X302LA                      | [8404a0b0c6](https://linux-hardware.org/?probe=8404a0b0c6) | Dec 14, 2022 |
| PC Special... | Elimina Iv 17               | [66a5d6dd6a](https://linux-hardware.org/?probe=66a5d6dd6a) | Dec 13, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [6fc042d213](https://linux-hardware.org/?probe=6fc042d213) | Dec 13, 2022 |
| HP            | EliteBook 820 G3            | [ff5b82cee3](https://linux-hardware.org/?probe=ff5b82cee3) | Dec 13, 2022 |
| Lenovo        | G505 20240                  | [e6777c2fbc](https://linux-hardware.org/?probe=e6777c2fbc) | Dec 13, 2022 |
| Lenovo        | ThinkPad T480s 20L8002WM... | [d742af8997](https://linux-hardware.org/?probe=d742af8997) | Dec 13, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [c62c8e69b0](https://linux-hardware.org/?probe=c62c8e69b0) | Dec 12, 2022 |
| MSI           | GS65 Stealth Thin 8RF       | [074195107c](https://linux-hardware.org/?probe=074195107c) | Dec 12, 2022 |
| Packard Be... | EasyNote TJ71               | [45630329df](https://linux-hardware.org/?probe=45630329df) | Dec 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [a9505fa3e4](https://linux-hardware.org/?probe=a9505fa3e4) | Dec 12, 2022 |
| HP            | EliteBook 820 G3            | [1e0eec72b2](https://linux-hardware.org/?probe=1e0eec72b2) | Dec 12, 2022 |
| Apple         | MacBookPro14,3              | [7cefe54b56](https://linux-hardware.org/?probe=7cefe54b56) | Dec 12, 2022 |
| HP            | EliteBook 8570w             | [367579550b](https://linux-hardware.org/?probe=367579550b) | Dec 11, 2022 |
| SGIN          | laptop                      | [8f650d00dd](https://linux-hardware.org/?probe=8f650d00dd) | Dec 11, 2022 |
| Toshiba       | Satellite L455              | [e92985332e](https://linux-hardware.org/?probe=e92985332e) | Dec 11, 2022 |
| Lenovo        | G50-45 80E3                 | [754e028997](https://linux-hardware.org/?probe=754e028997) | Dec 11, 2022 |
| Lenovo        | G50-45 80E3                 | [fb2f97325d](https://linux-hardware.org/?probe=fb2f97325d) | Dec 11, 2022 |
| HP            | Laptop 15s-fq2xxx           | [129c077e02](https://linux-hardware.org/?probe=129c077e02) | Dec 11, 2022 |
| ASUSTek       | K50C                        | [6cf2037e0f](https://linux-hardware.org/?probe=6cf2037e0f) | Dec 11, 2022 |
| ASUSTek       | S551LN                      | [9aabc2d159](https://linux-hardware.org/?probe=9aabc2d159) | Dec 11, 2022 |
| Google        | Blooglet                    | [a9d65d2144](https://linux-hardware.org/?probe=a9d65d2144) | Dec 11, 2022 |
| Valve         | Jupiter                     | [26c1e67dff](https://linux-hardware.org/?probe=26c1e67dff) | Dec 11, 2022 |
| Valve         | Jupiter                     | [e143b181a1](https://linux-hardware.org/?probe=e143b181a1) | Dec 11, 2022 |
| HP            | Pavilion dv6000 (RY649EA... | [9deecc89f5](https://linux-hardware.org/?probe=9deecc89f5) | Dec 10, 2022 |
| Acer          | TravelMate 4070             | [8f9e4c0e26](https://linux-hardware.org/?probe=8f9e4c0e26) | Dec 10, 2022 |
| HUAWEI        | CREM-WXX9                   | [1b6dee1e4a](https://linux-hardware.org/?probe=1b6dee1e4a) | Dec 10, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [61b2bab886](https://linux-hardware.org/?probe=61b2bab886) | Dec 10, 2022 |
| ASUSTek       | VivoBook S15 X510UF         | [5f72ad2758](https://linux-hardware.org/?probe=5f72ad2758) | Dec 10, 2022 |
| HUAWEI        | CREM-WXX9                   | [fdda7ba30e](https://linux-hardware.org/?probe=fdda7ba30e) | Dec 10, 2022 |
| Acer          | Aspire ES1-512              | [c9313e3820](https://linux-hardware.org/?probe=c9313e3820) | Dec 10, 2022 |
| SANTECH       | NHx0DB,DE                   | [89e8d0f23e](https://linux-hardware.org/?probe=89e8d0f23e) | Dec 10, 2022 |
| Dell          | Inspiron 5570               | [4d78d14f00](https://linux-hardware.org/?probe=4d78d14f00) | Dec 10, 2022 |
| Toshiba       | Satellite C70-C-11L         | [8de407e526](https://linux-hardware.org/?probe=8de407e526) | Dec 09, 2022 |
| HP            | 250 G3                      | [7e7b65bb5f](https://linux-hardware.org/?probe=7e7b65bb5f) | Dec 09, 2022 |
| HP            | 250 G3                      | [170a8b35c6](https://linux-hardware.org/?probe=170a8b35c6) | Dec 09, 2022 |
| Packard Be... | EasyNote TJ71               | [4c0af21017](https://linux-hardware.org/?probe=4c0af21017) | Dec 09, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [d28d2da00b](https://linux-hardware.org/?probe=d28d2da00b) | Dec 09, 2022 |
| Google        | Blooglet                    | [241c0f4331](https://linux-hardware.org/?probe=241c0f4331) | Dec 09, 2022 |
| HP            | EliteBook 830 G8 Noteboo... | [5d96a0484a](https://linux-hardware.org/?probe=5d96a0484a) | Dec 08, 2022 |
| HP            | EliteBook 840 G5            | [946807e266](https://linux-hardware.org/?probe=946807e266) | Dec 08, 2022 |
| HP            | Pavilion Laptop 15-eg1xx... | [970f8e990b](https://linux-hardware.org/?probe=970f8e990b) | Dec 08, 2022 |
| HP            | Pavilion Laptop 15-eg1xx... | [0e7da55713](https://linux-hardware.org/?probe=0e7da55713) | Dec 08, 2022 |
| Toshiba       | Satellite C850-1LJ          | [4af2ab112f](https://linux-hardware.org/?probe=4af2ab112f) | Dec 08, 2022 |
| Lenovo        | ThinkPad P52 20M9001KIX     | [f470667df1](https://linux-hardware.org/?probe=f470667df1) | Dec 08, 2022 |
| Lenovo        | ThinkPad P52 20M9001KIX     | [2562e31e5a](https://linux-hardware.org/?probe=2562e31e5a) | Dec 08, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | [182678a056](https://linux-hardware.org/?probe=182678a056) | Dec 08, 2022 |
| Packard Be... | EasyNote TJ71               | [f4bf9ede5b](https://linux-hardware.org/?probe=f4bf9ede5b) | Dec 08, 2022 |
| HP            | ProBook 640 G1              | [c3bf44d032](https://linux-hardware.org/?probe=c3bf44d032) | Dec 08, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | [c66f0c0c8d](https://linux-hardware.org/?probe=c66f0c0c8d) | Dec 08, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | [ca25d43c56](https://linux-hardware.org/?probe=ca25d43c56) | Dec 08, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | [104e0e02d1](https://linux-hardware.org/?probe=104e0e02d1) | Dec 08, 2022 |
| Acer          | TravelMate 4070             | [ec589662a2](https://linux-hardware.org/?probe=ec589662a2) | Dec 08, 2022 |
| Toshiba       | Satellite Pro S500          | [bcf1460e47](https://linux-hardware.org/?probe=bcf1460e47) | Dec 08, 2022 |
| HP            | EliteBook 840 G5            | [bb11ec4f3f](https://linux-hardware.org/?probe=bb11ec4f3f) | Dec 08, 2022 |
| Google        | Sasuke                      | [527f49b0ae](https://linux-hardware.org/?probe=527f49b0ae) | Dec 07, 2022 |
| Dell          | Inspiron 5505               | [183c4593a7](https://linux-hardware.org/?probe=183c4593a7) | Dec 07, 2022 |
| Google        | Sasuke                      | [5bd0b833cb](https://linux-hardware.org/?probe=5bd0b833cb) | Dec 07, 2022 |
| Acer          | Aspire 5935                 | [01da97dae6](https://linux-hardware.org/?probe=01da97dae6) | Dec 07, 2022 |
| Dell          | Studio 1558                 | [ce0c8ffe20](https://linux-hardware.org/?probe=ce0c8ffe20) | Dec 06, 2022 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | [799ba39d5e](https://linux-hardware.org/?probe=799ba39d5e) | Dec 06, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [10fea00e5a](https://linux-hardware.org/?probe=10fea00e5a) | Dec 06, 2022 |
| Teclast       | F7 Plus                     | [5e155a318e](https://linux-hardware.org/?probe=5e155a318e) | Dec 06, 2022 |
| Acer          | Aspire 5935                 | [44895b82f9](https://linux-hardware.org/?probe=44895b82f9) | Dec 05, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [dd7a026e5e](https://linux-hardware.org/?probe=dd7a026e5e) | Dec 05, 2022 |
| MSI           | Creator 15M A9SD            | [f8e6206ba6](https://linux-hardware.org/?probe=f8e6206ba6) | Dec 05, 2022 |
| Toshiba       | Satellite L50-B             | [6d92129c25](https://linux-hardware.org/?probe=6d92129c25) | Dec 05, 2022 |
| ASUSTek       | K53SC                       | [57e7bb2427](https://linux-hardware.org/?probe=57e7bb2427) | Dec 05, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [fd9114a304](https://linux-hardware.org/?probe=fd9114a304) | Dec 04, 2022 |
| ASUSTek       | X750JN                      | [af27460f17](https://linux-hardware.org/?probe=af27460f17) | Dec 04, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [888ec24e9d](https://linux-hardware.org/?probe=888ec24e9d) | Dec 04, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [ac92442dbc](https://linux-hardware.org/?probe=ac92442dbc) | Dec 04, 2022 |
| Schenker      | XMG APEX (Mid 2021)         | [41824c584f](https://linux-hardware.org/?probe=41824c584f) | Dec 03, 2022 |
| Acer          | Aspire A315-23              | [8c3beba1e1](https://linux-hardware.org/?probe=8c3beba1e1) | Dec 03, 2022 |
| Acer          | Aspire A315-21              | [91eb1913d7](https://linux-hardware.org/?probe=91eb1913d7) | Dec 03, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [f34caf87d5](https://linux-hardware.org/?probe=f34caf87d5) | Dec 03, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [c00aab388c](https://linux-hardware.org/?probe=c00aab388c) | Dec 03, 2022 |
| Lenovo        | XiaoXinPro 16ACH 2021 82... | [2085f260e1](https://linux-hardware.org/?probe=2085f260e1) | Dec 03, 2022 |
| HP            | Pavilion 15                 | [87de142ecd](https://linux-hardware.org/?probe=87de142ecd) | Dec 03, 2022 |
| Google        | Blooglet                    | [045f75ab43](https://linux-hardware.org/?probe=045f75ab43) | Dec 03, 2022 |
| HUAWEI        | MACHC-WAX9                  | [958e17ffc9](https://linux-hardware.org/?probe=958e17ffc9) | Dec 03, 2022 |
| Lenovo        | G580 2189                   | [80fe3f7171](https://linux-hardware.org/?probe=80fe3f7171) | Dec 03, 2022 |
| Samsung       | 530U3C/530U4C/532U3C        | [91edd3827d](https://linux-hardware.org/?probe=91edd3827d) | Dec 02, 2022 |
| Dell          | XPS 15 9570                 | [867e3d70f0](https://linux-hardware.org/?probe=867e3d70f0) | Dec 02, 2022 |
| HP            | Unknown                     | [741029c3af](https://linux-hardware.org/?probe=741029c3af) | Dec 02, 2022 |
| HP            | Notebook                    | [4184c8fa06](https://linux-hardware.org/?probe=4184c8fa06) | Dec 02, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [9d27bb4f90](https://linux-hardware.org/?probe=9d27bb4f90) | Dec 01, 2022 |
| Mediacom      | SmartBook 14 FullHD - SB... | [1df1f552ff](https://linux-hardware.org/?probe=1df1f552ff) | Dec 01, 2022 |
| Acer          | Aspire 5750G                | [a8236e24a5](https://linux-hardware.org/?probe=a8236e24a5) | Dec 01, 2022 |
| HP            | ProBook 440 G7              | [a54a325001](https://linux-hardware.org/?probe=a54a325001) | Dec 01, 2022 |
| Acer          | Aspire 5750G                | [198d7f2534](https://linux-hardware.org/?probe=198d7f2534) | Dec 01, 2022 |
| ASUSTek       | K52F                        | [63c08600c3](https://linux-hardware.org/?probe=63c08600c3) | Dec 01, 2022 |
| ASUSTek       | K52F                        | [4276cc2cb9](https://linux-hardware.org/?probe=4276cc2cb9) | Dec 01, 2022 |
| Dell          | Studio 1558                 | [cf40788ef8](https://linux-hardware.org/?probe=cf40788ef8) | Nov 30, 2022 |
| ASUSTek       | K53SC                       | [6d21dd6cea](https://linux-hardware.org/?probe=6d21dd6cea) | Nov 30, 2022 |
| HP            | Pavilion g6                 | [c552ca011c](https://linux-hardware.org/?probe=c552ca011c) | Nov 30, 2022 |
| Apple         | MacBook4,1                  | [0866a64897](https://linux-hardware.org/?probe=0866a64897) | Nov 30, 2022 |
| Apple         | MacBookAir8,1               | [7581ef0e85](https://linux-hardware.org/?probe=7581ef0e85) | Nov 29, 2022 |
| HUAWEI        | BOD-WXX9                    | [a2b8deb4e3](https://linux-hardware.org/?probe=a2b8deb4e3) | Nov 29, 2022 |
| Lenovo        | IdeaPad 110-15AST 80TR      | [cbb0c1dca7](https://linux-hardware.org/?probe=cbb0c1dca7) | Nov 29, 2022 |
| HP            | Compaq nc6320 (GB940ES#A... | [bb417133ee](https://linux-hardware.org/?probe=bb417133ee) | Nov 29, 2022 |
| HP            | Compaq nc6320 (GB940ES#A... | [ddb2f42bcc](https://linux-hardware.org/?probe=ddb2f42bcc) | Nov 29, 2022 |
| Acer          | Aspire 5738                 | [a9697f1e7a](https://linux-hardware.org/?probe=a9697f1e7a) | Nov 28, 2022 |
| MSI           | Prestige 15 A12SC           | [af2a404105](https://linux-hardware.org/?probe=af2a404105) | Nov 28, 2022 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [ab9b95babe](https://linux-hardware.org/?probe=ab9b95babe) | Nov 28, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [1620a1a2cb](https://linux-hardware.org/?probe=1620a1a2cb) | Nov 28, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [0d99651537](https://linux-hardware.org/?probe=0d99651537) | Nov 28, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [3f660318ea](https://linux-hardware.org/?probe=3f660318ea) | Nov 28, 2022 |
| Unknown       | Unknown                     | [4f73de3788](https://linux-hardware.org/?probe=4f73de3788) | Nov 27, 2022 |
| Dell          | XPS 13 9305                 | [c306dcfa4f](https://linux-hardware.org/?probe=c306dcfa4f) | Nov 27, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [44a305db4d](https://linux-hardware.org/?probe=44a305db4d) | Nov 27, 2022 |
| ASUSTek       | VivoBook S15 X510UF         | [7bd68a8bb1](https://linux-hardware.org/?probe=7bd68a8bb1) | Nov 27, 2022 |
| Lenovo        | S20-30 Touch 20434          | [63d2134051](https://linux-hardware.org/?probe=63d2134051) | Nov 27, 2022 |
| Lenovo        | B50-30 80ES                 | [ced4c1f563](https://linux-hardware.org/?probe=ced4c1f563) | Nov 27, 2022 |
| Dell          | G5 5587                     | [689db41249](https://linux-hardware.org/?probe=689db41249) | Nov 27, 2022 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [f397d89e9b](https://linux-hardware.org/?probe=f397d89e9b) | Nov 27, 2022 |
| Lenovo        | ThinkPad X280 20KES2DD0D    | [394b24459c](https://linux-hardware.org/?probe=394b24459c) | Nov 27, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0XX0... | [f91c391079](https://linux-hardware.org/?probe=f91c391079) | Nov 26, 2022 |
| MSI           | Creator 15M A9SD            | [8b47bbf475](https://linux-hardware.org/?probe=8b47bbf475) | Nov 26, 2022 |
| Lenovo        | Y50-70 20378                | [57e4892065](https://linux-hardware.org/?probe=57e4892065) | Nov 26, 2022 |
| HUAWEI        | KLVL-WXX9                   | [ce7815f106](https://linux-hardware.org/?probe=ce7815f106) | Nov 26, 2022 |
| Lenovo        | ThinkPad T495 20NJS0L100    | [1e9e7f34df](https://linux-hardware.org/?probe=1e9e7f34df) | Nov 26, 2022 |
| Sony          | SVP1121X9EB                 | [78df785a47](https://linux-hardware.org/?probe=78df785a47) | Nov 26, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [123efdf4df](https://linux-hardware.org/?probe=123efdf4df) | Nov 26, 2022 |
| ASUSTek       | X202E                       | [24a8811d77](https://linux-hardware.org/?probe=24a8811d77) | Nov 25, 2022 |
| ASUSTek       | X202E                       | [69a3fa54c1](https://linux-hardware.org/?probe=69a3fa54c1) | Nov 25, 2022 |
| Lenovo        | ThinkPad T430 2349IF8       | [4d8bd1760a](https://linux-hardware.org/?probe=4d8bd1760a) | Nov 25, 2022 |
| MSI           | Creator 15M A9SD            | [a15ef33296](https://linux-hardware.org/?probe=a15ef33296) | Nov 25, 2022 |
| Acer          | Nitro AN515-45              | [10186425ec](https://linux-hardware.org/?probe=10186425ec) | Nov 25, 2022 |
| HP            | ProBook 450 G6              | [d044aabfec](https://linux-hardware.org/?probe=d044aabfec) | Nov 25, 2022 |
| Acer          | Nitro AN515-45              | [5a7b57dae6](https://linux-hardware.org/?probe=5a7b57dae6) | Nov 25, 2022 |
| Dell          | Latitude 3450               | [d7af694917](https://linux-hardware.org/?probe=d7af694917) | Nov 25, 2022 |
| ASUSTek       | X551CAP                     | [f40e3110d0](https://linux-hardware.org/?probe=f40e3110d0) | Nov 24, 2022 |
| Alienware     | 15                          | [3423725ae2](https://linux-hardware.org/?probe=3423725ae2) | Nov 24, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [2d1c8c7ea5](https://linux-hardware.org/?probe=2d1c8c7ea5) | Nov 24, 2022 |
| ASUSTek       | X510UQ                      | [5972ededc2](https://linux-hardware.org/?probe=5972ededc2) | Nov 24, 2022 |
| HP            | Pavilion 15                 | [b0d1e2e0ba](https://linux-hardware.org/?probe=b0d1e2e0ba) | Nov 24, 2022 |
| HP            | Laptop 15-dw0xxx            | [894c4e9ebf](https://linux-hardware.org/?probe=894c4e9ebf) | Nov 24, 2022 |
| Acer          | Aspire V3-772G              | [7ce85c6de5](https://linux-hardware.org/?probe=7ce85c6de5) | Nov 23, 2022 |
| Lenovo        | G500 20236                  | [2bfa796e90](https://linux-hardware.org/?probe=2bfa796e90) | Nov 23, 2022 |
| Lenovo        | G500 20236                  | [afcb386e71](https://linux-hardware.org/?probe=afcb386e71) | Nov 23, 2022 |
| Unknown       | Unknown                     | [f40545f0d5](https://linux-hardware.org/?probe=f40545f0d5) | Nov 23, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [fd8121fecd](https://linux-hardware.org/?probe=fd8121fecd) | Nov 22, 2022 |
| HP            | 250 G7 Notebook PC          | [242d685287](https://linux-hardware.org/?probe=242d685287) | Nov 22, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [923ccf8b76](https://linux-hardware.org/?probe=923ccf8b76) | Nov 22, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [e9ba2ff234](https://linux-hardware.org/?probe=e9ba2ff234) | Nov 22, 2022 |
| Toshiba       | Satellite Pro S500          | [a9d392c0c3](https://linux-hardware.org/?probe=a9d392c0c3) | Nov 22, 2022 |
| ASUSTek       | GL503VS                     | [18fa411a6d](https://linux-hardware.org/?probe=18fa411a6d) | Nov 22, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [bdf1794487](https://linux-hardware.org/?probe=bdf1794487) | Nov 22, 2022 |
| HUAWEI        | BOHB-WAX9                   | [b0d3226df4](https://linux-hardware.org/?probe=b0d3226df4) | Nov 21, 2022 |
| Acer          | Aspire A515-45              | [b0b972f8ef](https://linux-hardware.org/?probe=b0b972f8ef) | Nov 21, 2022 |
| Dell          | Latitude 9420               | [ddf8c8749c](https://linux-hardware.org/?probe=ddf8c8749c) | Nov 21, 2022 |
| MSI           | Creator 15M A9SD            | [e6d5440b09](https://linux-hardware.org/?probe=e6d5440b09) | Nov 21, 2022 |
| HP            | Laptop 14s-fq0xxx           | [a94bd1fd5a](https://linux-hardware.org/?probe=a94bd1fd5a) | Nov 21, 2022 |
| HP            | Laptop 14s-fq0xxx           | [cc9c76c85c](https://linux-hardware.org/?probe=cc9c76c85c) | Nov 21, 2022 |
| HP            | Laptop 15-db0xxx            | [f634446cde](https://linux-hardware.org/?probe=f634446cde) | Nov 21, 2022 |
| Google        | Sasuke                      | [35330e59ad](https://linux-hardware.org/?probe=35330e59ad) | Nov 20, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [aaa2d66240](https://linux-hardware.org/?probe=aaa2d66240) | Nov 20, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [3ecbc7acb4](https://linux-hardware.org/?probe=3ecbc7acb4) | Nov 20, 2022 |
| HP            | Pavilion Laptop 14-ce2xx... | [cd2b457ffb](https://linux-hardware.org/?probe=cd2b457ffb) | Nov 20, 2022 |
| HP            | Notebook                    | [1278403b39](https://linux-hardware.org/?probe=1278403b39) | Nov 20, 2022 |
| Lenovo        | ThinkPad L380 20M6S4E000    | [4f65299a92](https://linux-hardware.org/?probe=4f65299a92) | Nov 20, 2022 |
| Sony          | VPCEB2M1E                   | [eeefed51e4](https://linux-hardware.org/?probe=eeefed51e4) | Nov 20, 2022 |
| Acer          | Nitro AN515-54              | [b9d2b8c218](https://linux-hardware.org/?probe=b9d2b8c218) | Nov 20, 2022 |
| Dell          | XPS 13 7390                 | [9f6c38b4ee](https://linux-hardware.org/?probe=9f6c38b4ee) | Nov 20, 2022 |
| Acer          | aspire5740                  | [6cdc4f5cfc](https://linux-hardware.org/?probe=6cdc4f5cfc) | Nov 20, 2022 |
| Acer          | Aspire ES1-521              | [6af4249f1a](https://linux-hardware.org/?probe=6af4249f1a) | Nov 20, 2022 |
| Apple         | MacBookPro5,1               | [4f04b7d627](https://linux-hardware.org/?probe=4f04b7d627) | Nov 19, 2022 |
| Acer          | Aspire ES1-111M             | [3b15bcfd88](https://linux-hardware.org/?probe=3b15bcfd88) | Nov 19, 2022 |
| HUAWEI        | BOHB-WAX9                   | [8ffb460b9e](https://linux-hardware.org/?probe=8ffb460b9e) | Nov 19, 2022 |
| Olidata       | T7700                       | [d8220596fc](https://linux-hardware.org/?probe=d8220596fc) | Nov 19, 2022 |
| Apple         | MacBook4,1                  | [c2d79be90d](https://linux-hardware.org/?probe=c2d79be90d) | Nov 19, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [36bc4b545f](https://linux-hardware.org/?probe=36bc4b545f) | Nov 19, 2022 |
| HP            | Presario CQ58               | [fc1d1892ef](https://linux-hardware.org/?probe=fc1d1892ef) | Nov 19, 2022 |
| Apple         | MacBookAir4,2               | [c11ad764af](https://linux-hardware.org/?probe=c11ad764af) | Nov 19, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [0b0d1f6427](https://linux-hardware.org/?probe=0b0d1f6427) | Nov 19, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [865fa07274](https://linux-hardware.org/?probe=865fa07274) | Nov 19, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [68d651f36b](https://linux-hardware.org/?probe=68d651f36b) | Nov 19, 2022 |
| Sony          | VPCYA1C5E                   | [416067b991](https://linux-hardware.org/?probe=416067b991) | Nov 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [6e0f255eeb](https://linux-hardware.org/?probe=6e0f255eeb) | Nov 18, 2022 |
| Fujitsu       | LIFEBOOK U759               | [945910eb8a](https://linux-hardware.org/?probe=945910eb8a) | Nov 18, 2022 |
| Acer          | Aspire V5-573G              | [f58db71272](https://linux-hardware.org/?probe=f58db71272) | Nov 18, 2022 |
| HP            | Laptop 17-cp0xxx            | [e18aef24ac](https://linux-hardware.org/?probe=e18aef24ac) | Nov 17, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21E3C... | [dee1a4e29e](https://linux-hardware.org/?probe=dee1a4e29e) | Nov 17, 2022 |
| Dell          | XPS 13 7390                 | [19d18ac52c](https://linux-hardware.org/?probe=19d18ac52c) | Nov 17, 2022 |
| Mediacom      | FlexBook_edge13-M-FBE13     | [aa7f8583b6](https://linux-hardware.org/?probe=aa7f8583b6) | Nov 17, 2022 |
| Mediacom      | FlexBook_edge13-M-FBE13     | [c15d4ee015](https://linux-hardware.org/?probe=c15d4ee015) | Nov 17, 2022 |
| Mediacom      | FlexBook_edge13-M-FBE13     | [b5106cb728](https://linux-hardware.org/?probe=b5106cb728) | Nov 17, 2022 |
| ASUSTek       | X541UV                      | [74aca760f1](https://linux-hardware.org/?probe=74aca760f1) | Nov 17, 2022 |
| HP            | Laptop 15-dw0xxx            | [b81771eed0](https://linux-hardware.org/?probe=b81771eed0) | Nov 17, 2022 |
| MSI           | Creator 15M A9SD            | [f1fdc384f9](https://linux-hardware.org/?probe=f1fdc384f9) | Nov 17, 2022 |
| HP            | Laptop 15-db0xxx            | [5aa50e7f6c](https://linux-hardware.org/?probe=5aa50e7f6c) | Nov 17, 2022 |
| HP            | OMEN by Laptop 15-dh0xxx    | [523e8a1c6b](https://linux-hardware.org/?probe=523e8a1c6b) | Nov 17, 2022 |
| HP            | 250 G4                      | [3f2660a101](https://linux-hardware.org/?probe=3f2660a101) | Nov 16, 2022 |
| HP            | 250 G4                      | [cc4a368fd3](https://linux-hardware.org/?probe=cc4a368fd3) | Nov 16, 2022 |
| ASUSTek       | N53Jf                       | [61f5cf6214](https://linux-hardware.org/?probe=61f5cf6214) | Nov 16, 2022 |
| HP            | Laptop 15-db0xxx            | [f6202bb6fa](https://linux-hardware.org/?probe=f6202bb6fa) | Nov 16, 2022 |
| MSI           | Prestige 14Evo A11M         | [78601d078c](https://linux-hardware.org/?probe=78601d078c) | Nov 16, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [922ce95539](https://linux-hardware.org/?probe=922ce95539) | Nov 16, 2022 |
| Dell          | XPS 15 9570                 | [d62ee2298d](https://linux-hardware.org/?probe=d62ee2298d) | Nov 16, 2022 |
| Toshiba       | Satellite Pro S500          | [f528238460](https://linux-hardware.org/?probe=f528238460) | Nov 16, 2022 |
| Toshiba       | Satellite Pro S500          | [97ccc55f03](https://linux-hardware.org/?probe=97ccc55f03) | Nov 16, 2022 |
| Fujitsu       | LIFEBOOK E554               | [df8344d098](https://linux-hardware.org/?probe=df8344d098) | Nov 16, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [809e86d562](https://linux-hardware.org/?probe=809e86d562) | Nov 15, 2022 |
| HP            | ProBook 450 G7              | [612006bada](https://linux-hardware.org/?probe=612006bada) | Nov 15, 2022 |
| HP            | ProBook 450 G7              | [2e122b28c4](https://linux-hardware.org/?probe=2e122b28c4) | Nov 15, 2022 |
| Fujitsu       | LIFEBOOK E557               | [a57972523b](https://linux-hardware.org/?probe=a57972523b) | Nov 15, 2022 |
| MSI           | PS63 Modern 8RC             | [699ea2cc17](https://linux-hardware.org/?probe=699ea2cc17) | Nov 15, 2022 |
| System76      | Oryx Pro                    | [3ea0d459e1](https://linux-hardware.org/?probe=3ea0d459e1) | Nov 15, 2022 |
| Acer          | Aspire A715-42G             | [403bc1b6b5](https://linux-hardware.org/?probe=403bc1b6b5) | Nov 14, 2022 |
| Acer          | Aspire A715-42G             | [6209796b42](https://linux-hardware.org/?probe=6209796b42) | Nov 14, 2022 |
| Lenovo        | ThinkPad T430 2349IF8       | [b6e353af2b](https://linux-hardware.org/?probe=b6e353af2b) | Nov 14, 2022 |
| Lenovo        | ThinkPad T430 2349IF8       | [c642a76e3e](https://linux-hardware.org/?probe=c642a76e3e) | Nov 14, 2022 |
| ASUSTek       | N751JX                      | [cea52af467](https://linux-hardware.org/?probe=cea52af467) | Nov 14, 2022 |
| Olidata       | T7700                       | [488f74cf4b](https://linux-hardware.org/?probe=488f74cf4b) | Nov 14, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | [d28a778811](https://linux-hardware.org/?probe=d28a778811) | Nov 14, 2022 |
| Microtech     | ebookLite                   | [471a1a6ac7](https://linux-hardware.org/?probe=471a1a6ac7) | Nov 14, 2022 |
| MSI           | Prestige 15 A12SC           | [211fdda09b](https://linux-hardware.org/?probe=211fdda09b) | Nov 14, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [0d39dde901](https://linux-hardware.org/?probe=0d39dde901) | Nov 14, 2022 |
| Acer          | Aspire 5600                 | [9fe2a7d245](https://linux-hardware.org/?probe=9fe2a7d245) | Nov 14, 2022 |
| Acer          | TravelMate P259-G2-MG       | [27d3da0f8a](https://linux-hardware.org/?probe=27d3da0f8a) | Nov 14, 2022 |
| Sony          | VGN-NS21M_W                 | [b3f4aef7a4](https://linux-hardware.org/?probe=b3f4aef7a4) | Nov 14, 2022 |
| Packard Be... | DOT S                       | [4e6d343f5c](https://linux-hardware.org/?probe=4e6d343f5c) | Nov 14, 2022 |
| Lenovo        | G510 20238                  | [99c1eee67d](https://linux-hardware.org/?probe=99c1eee67d) | Nov 14, 2022 |
| HP            | Laptop 15s-eq2xxx           | [36df61fb32](https://linux-hardware.org/?probe=36df61fb32) | Nov 13, 2022 |
| HUAWEI        | CREM-WXX9                   | [b33f7744b5](https://linux-hardware.org/?probe=b33f7744b5) | Nov 13, 2022 |
| HUAWEI        | CREM-WXX9                   | [9d7853c05b](https://linux-hardware.org/?probe=9d7853c05b) | Nov 13, 2022 |
| Lenovo        | ThinkPad L450 20DSS1GD00    | [b0ea02b16c](https://linux-hardware.org/?probe=b0ea02b16c) | Nov 13, 2022 |
| Lenovo        | ThinkPad T430 2349P25       | [ba76ce6af6](https://linux-hardware.org/?probe=ba76ce6af6) | Nov 13, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [48e0868598](https://linux-hardware.org/?probe=48e0868598) | Nov 13, 2022 |
| HP            | 250 G4                      | [58f7b77f39](https://linux-hardware.org/?probe=58f7b77f39) | Nov 12, 2022 |
| HP            | 250 G4                      | [f700001da4](https://linux-hardware.org/?probe=f700001da4) | Nov 12, 2022 |
| Acer          | aspire5740                  | [5218638790](https://linux-hardware.org/?probe=5218638790) | Nov 12, 2022 |
| Microtech     | ebookLite                   | [9c3039fa75](https://linux-hardware.org/?probe=9c3039fa75) | Nov 12, 2022 |
| Unknown       | Unknown                     | [0dff6ba2e2](https://linux-hardware.org/?probe=0dff6ba2e2) | Nov 12, 2022 |
| Acer          | aspire5740                  | [ba3ea314f0](https://linux-hardware.org/?probe=ba3ea314f0) | Nov 12, 2022 |
| HP            | 15                          | [bebef9206b](https://linux-hardware.org/?probe=bebef9206b) | Nov 12, 2022 |
| Dell          | Inspiron 15 3511            | [361f37b08d](https://linux-hardware.org/?probe=361f37b08d) | Nov 11, 2022 |
| Dell          | Latitude E6440              | [7d35b21aae](https://linux-hardware.org/?probe=7d35b21aae) | Nov 11, 2022 |
| ASUSTek       | X550JD                      | [9c88cc6c32](https://linux-hardware.org/?probe=9c88cc6c32) | Nov 11, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | [969fa6c183](https://linux-hardware.org/?probe=969fa6c183) | Nov 11, 2022 |
| Dell          | Latitude 12 Rugged Extre... | [d5b955a7b3](https://linux-hardware.org/?probe=d5b955a7b3) | Nov 11, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | [08963a61fb](https://linux-hardware.org/?probe=08963a61fb) | Nov 10, 2022 |
| Dell          | Venue 11 Pro 7140           | [78a6cdf739](https://linux-hardware.org/?probe=78a6cdf739) | Nov 10, 2022 |
| ASUSTek       | N550JK                      | [befb8455f0](https://linux-hardware.org/?probe=befb8455f0) | Nov 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [fc22f217b3](https://linux-hardware.org/?probe=fc22f217b3) | Nov 10, 2022 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | [89839b84cb](https://linux-hardware.org/?probe=89839b84cb) | Nov 10, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [31e940a232](https://linux-hardware.org/?probe=31e940a232) | Nov 10, 2022 |
| Microtech     | ebookLite                   | [63f80f900a](https://linux-hardware.org/?probe=63f80f900a) | Nov 10, 2022 |
| Timi          | TM1701                      | [917ec43bd1](https://linux-hardware.org/?probe=917ec43bd1) | Nov 09, 2022 |
| HP            | Pavilion Notebook           | [150409691d](https://linux-hardware.org/?probe=150409691d) | Nov 09, 2022 |
| HP            | 15                          | [c301aa00eb](https://linux-hardware.org/?probe=c301aa00eb) | Nov 09, 2022 |
| MSI           | GL63 8RD                    | [e10069a2f8](https://linux-hardware.org/?probe=e10069a2f8) | Nov 09, 2022 |
| Lenovo        | ThinkPad X250 20CLS3AJ00    | [ec16a4b3c5](https://linux-hardware.org/?probe=ec16a4b3c5) | Nov 09, 2022 |
| Toshiba       | Satellite L50-B             | [8939445388](https://linux-hardware.org/?probe=8939445388) | Nov 09, 2022 |
| ASUSTek       | VivoBook S15 X510UF         | [a2e9b34d94](https://linux-hardware.org/?probe=a2e9b34d94) | Nov 09, 2022 |
| Dell          | XPS 15 9560                 | [439ec3a470](https://linux-hardware.org/?probe=439ec3a470) | Nov 09, 2022 |
| Toshiba       | Satellite L50-B             | [420aaf8ede](https://linux-hardware.org/?probe=420aaf8ede) | Nov 09, 2022 |
| ASUSTek       | UX305FA                     | [4bdd2e5e51](https://linux-hardware.org/?probe=4bdd2e5e51) | Nov 08, 2022 |
| Sony          | VGN-CS11Z_R                 | [865efadfee](https://linux-hardware.org/?probe=865efadfee) | Nov 08, 2022 |
| Mediacom      | SmartBook 14 FullHD - SB... | [2e0a3f4943](https://linux-hardware.org/?probe=2e0a3f4943) | Nov 08, 2022 |
| ASUSTek       | UL30A                       | [a7ede6f17c](https://linux-hardware.org/?probe=a7ede6f17c) | Nov 08, 2022 |
| HP            | Pavilion Notebook           | [656885b89d](https://linux-hardware.org/?probe=656885b89d) | Nov 08, 2022 |
| Apple         | MacBookPro11,4              | [9b54aae918](https://linux-hardware.org/?probe=9b54aae918) | Nov 08, 2022 |
| Apple         | MacBookPro11,4              | [46e5fff8cf](https://linux-hardware.org/?probe=46e5fff8cf) | Nov 08, 2022 |
| HP            | EliteBook 8540w             | [b373db743a](https://linux-hardware.org/?probe=b373db743a) | Nov 08, 2022 |
| HP            | EliteBook 8540w             | [6d246a753e](https://linux-hardware.org/?probe=6d246a753e) | Nov 08, 2022 |
| Lenovo        | G50-45 80E3                 | [70940de14e](https://linux-hardware.org/?probe=70940de14e) | Nov 08, 2022 |
| Dell          | XPS 13 9360                 | [a35aee6ec2](https://linux-hardware.org/?probe=a35aee6ec2) | Nov 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | [b8f810cd9e](https://linux-hardware.org/?probe=b8f810cd9e) | Nov 07, 2022 |
| Dell          | Venue 11 Pro 7140           | [da4eb1c67f](https://linux-hardware.org/?probe=da4eb1c67f) | Nov 07, 2022 |
| HP            | ZBook 15 G6                 | [3339953a1e](https://linux-hardware.org/?probe=3339953a1e) | Nov 07, 2022 |
| Dell          | Precision M4500             | [0ace37e277](https://linux-hardware.org/?probe=0ace37e277) | Nov 06, 2022 |
| HP            | Laptop 15-db0xxx            | [32b59c7a7d](https://linux-hardware.org/?probe=32b59c7a7d) | Nov 06, 2022 |
| HP            | Notebook                    | [59b70f4c7c](https://linux-hardware.org/?probe=59b70f4c7c) | Nov 06, 2022 |
| HP            | Laptop 15-db0xxx            | [f0c8aff40f](https://linux-hardware.org/?probe=f0c8aff40f) | Nov 06, 2022 |
| Dell          | Latitude E6440              | [68593d9a9d](https://linux-hardware.org/?probe=68593d9a9d) | Nov 06, 2022 |
| HP            | EliteBook 2570p             | [2ac38253fa](https://linux-hardware.org/?probe=2ac38253fa) | Nov 06, 2022 |
| Teclast       | F6 Pro                      | [bfba140f45](https://linux-hardware.org/?probe=bfba140f45) | Nov 06, 2022 |
| HUAWEI        | HN-WX9X                     | [4777921b9b](https://linux-hardware.org/?probe=4777921b9b) | Nov 06, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | [912bfcc57e](https://linux-hardware.org/?probe=912bfcc57e) | Nov 06, 2022 |
| HP            | Laptop 15-dw1xxx            | [a2d210c1c5](https://linux-hardware.org/?probe=a2d210c1c5) | Nov 06, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | [8090894691](https://linux-hardware.org/?probe=8090894691) | Nov 06, 2022 |
| Sony          | VGN-FW21E                   | [8be58df3e0](https://linux-hardware.org/?probe=8be58df3e0) | Nov 06, 2022 |
| Lenovo        | ThinkPad T520 42406AG       | [1038487513](https://linux-hardware.org/?probe=1038487513) | Nov 06, 2022 |
| Lenovo        | G50-45 80E3                 | [7818a033c6](https://linux-hardware.org/?probe=7818a033c6) | Nov 06, 2022 |
| HP            | Pavilion dv6                | [f13b221630](https://linux-hardware.org/?probe=f13b221630) | Nov 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X531... | [55d115647e](https://linux-hardware.org/?probe=55d115647e) | Nov 06, 2022 |
| HP            | Laptop 15s-eq0xxx           | [ec4fd96563](https://linux-hardware.org/?probe=ec4fd96563) | Nov 06, 2022 |
| HP            | Laptop 15s-eq0xxx           | [4c9e9f49aa](https://linux-hardware.org/?probe=4c9e9f49aa) | Nov 06, 2022 |
| HP            | Laptop 15-dw0xxx            | [46c9baf82c](https://linux-hardware.org/?probe=46c9baf82c) | Nov 05, 2022 |
| HP            | Laptop 15-dw0xxx            | [5783283bd4](https://linux-hardware.org/?probe=5783283bd4) | Nov 05, 2022 |
| HP            | Stream Laptop 14-ax0XX      | [578079d456](https://linux-hardware.org/?probe=578079d456) | Nov 05, 2022 |
| Acer          | Aspire 5741G                | [10c1cb72e2](https://linux-hardware.org/?probe=10c1cb72e2) | Nov 05, 2022 |
| Google        | Sasuke                      | [216a160b84](https://linux-hardware.org/?probe=216a160b84) | Nov 05, 2022 |
| ASUSTek       | T200TAC                     | [e14cb334c4](https://linux-hardware.org/?probe=e14cb334c4) | Nov 05, 2022 |
| Lenovo        | Z50-70 20354                | [0c65bd2797](https://linux-hardware.org/?probe=0c65bd2797) | Nov 05, 2022 |
| ASUSTek       | X200CA                      | [91d85f8376](https://linux-hardware.org/?probe=91d85f8376) | Nov 05, 2022 |
| Dell          | Inspiron 7570               | [158f7b0bcd](https://linux-hardware.org/?probe=158f7b0bcd) | Nov 05, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | [f1117abc19](https://linux-hardware.org/?probe=f1117abc19) | Nov 05, 2022 |
| HP            | Pro x2 410 G1 PC            | [9ac029fa2c](https://linux-hardware.org/?probe=9ac029fa2c) | Nov 05, 2022 |
| HP            | Pro x2 410 G1 PC            | [6b6622e981](https://linux-hardware.org/?probe=6b6622e981) | Nov 05, 2022 |
| Dell          | Inspiron 5502               | [204c296466](https://linux-hardware.org/?probe=204c296466) | Nov 04, 2022 |
| ASUSTek       | K53SD                       | [809577d2bb](https://linux-hardware.org/?probe=809577d2bb) | Nov 04, 2022 |
| Lenovo        | ThinkPad P51 20HH0014IX     | [e519495581](https://linux-hardware.org/?probe=e519495581) | Nov 04, 2022 |
| Dell          | Inspiron 7577               | [78b49e6f73](https://linux-hardware.org/?probe=78b49e6f73) | Nov 04, 2022 |
| Acer          | Aspire E1-570G              | [3614ee4149](https://linux-hardware.org/?probe=3614ee4149) | Nov 04, 2022 |
| ASUSTek       | E200HA                      | [6a9cb1ae1d](https://linux-hardware.org/?probe=6a9cb1ae1d) | Nov 04, 2022 |
| Acer          | Aspire E1-570G              | [c58816cb3d](https://linux-hardware.org/?probe=c58816cb3d) | Nov 04, 2022 |
| Lenovo        | B50-45 80F0                 | [2d36803ec6](https://linux-hardware.org/?probe=2d36803ec6) | Nov 04, 2022 |
| Lenovo        | IdeaPad Creator 5 15IMH0... | [72b1a49ec9](https://linux-hardware.org/?probe=72b1a49ec9) | Nov 04, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | [99e32a37ff](https://linux-hardware.org/?probe=99e32a37ff) | Nov 04, 2022 |
| ASUSTek       | ROG Strix G513IE_G513IE     | [1d1783ca36](https://linux-hardware.org/?probe=1d1783ca36) | Nov 04, 2022 |
| Apple         | MacBookPro11,5              | [2101c9063a](https://linux-hardware.org/?probe=2101c9063a) | Nov 04, 2022 |
| ASUSTek       | ROG Strix G513IE_G513IE     | [1333104aae](https://linux-hardware.org/?probe=1333104aae) | Nov 04, 2022 |
| ASUSTek       | Unknown                     | [f1a58eaa87](https://linux-hardware.org/?probe=f1a58eaa87) | Nov 04, 2022 |
| Toshiba       | Satellite L350              | [17157970ee](https://linux-hardware.org/?probe=17157970ee) | Nov 04, 2022 |
| Toshiba       | Satellite L350              | [7479ad8a79](https://linux-hardware.org/?probe=7479ad8a79) | Nov 04, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [d04fddb1cc](https://linux-hardware.org/?probe=d04fddb1cc) | Nov 04, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [9cb27611ff](https://linux-hardware.org/?probe=9cb27611ff) | Nov 04, 2022 |
| ASUSTek       | X555LJ                      | [b46456d0c2](https://linux-hardware.org/?probe=b46456d0c2) | Nov 04, 2022 |
| ASUSTek       | X555LJ                      | [e57ec28998](https://linux-hardware.org/?probe=e57ec28998) | Nov 03, 2022 |
| Acer          | Aspire 7720                 | [4599565d35](https://linux-hardware.org/?probe=4599565d35) | Nov 03, 2022 |
| Lenovo        | V145-15AST 81MT             | [077d7d4379](https://linux-hardware.org/?probe=077d7d4379) | Nov 03, 2022 |
| HP            | EliteBook 2570p             | [2c28f25521](https://linux-hardware.org/?probe=2c28f25521) | Nov 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [c796c2f9ee](https://linux-hardware.org/?probe=c796c2f9ee) | Nov 03, 2022 |
| ASUSTek       | X550LD                      | [0847d7c7e6](https://linux-hardware.org/?probe=0847d7c7e6) | Nov 03, 2022 |
| Acer          | Aspire 5732Z                | [7c6f7aa3e8](https://linux-hardware.org/?probe=7c6f7aa3e8) | Nov 03, 2022 |
| Dell          | Inspiron 5570               | [33d3e9ce22](https://linux-hardware.org/?probe=33d3e9ce22) | Nov 03, 2022 |
| Dell          | Latitude 7280               | [ec1ac4ec28](https://linux-hardware.org/?probe=ec1ac4ec28) | Nov 03, 2022 |
| Lenovo        | ThinkPad T430 23501B6       | [f059837f31](https://linux-hardware.org/?probe=f059837f31) | Nov 03, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IU    | [9e1b981f01](https://linux-hardware.org/?probe=9e1b981f01) | Nov 03, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [e2f82d9c90](https://linux-hardware.org/?probe=e2f82d9c90) | Nov 03, 2022 |
| Microtech     | CoreBook                    | [1276c24890](https://linux-hardware.org/?probe=1276c24890) | Nov 03, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [ec7425c123](https://linux-hardware.org/?probe=ec7425c123) | Nov 03, 2022 |
| Acer          | Aspire V5-573G              | [2bab719066](https://linux-hardware.org/?probe=2bab719066) | Nov 03, 2022 |
| Lenovo        | ThinkPad Edge E530 3259M... | [2bca9d747b](https://linux-hardware.org/?probe=2bca9d747b) | Nov 03, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [eeb167d869](https://linux-hardware.org/?probe=eeb167d869) | Nov 02, 2022 |
| HP            | Pavilion Gaming Laptop      | [695b3d82a7](https://linux-hardware.org/?probe=695b3d82a7) | Nov 02, 2022 |
| HP            | Pavilion Gaming Laptop      | [9b9e55c471](https://linux-hardware.org/?probe=9b9e55c471) | Nov 02, 2022 |
| ASUSTek       | X540SAA                     | [ccaedd7155](https://linux-hardware.org/?probe=ccaedd7155) | Nov 02, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [a3b1926b7e](https://linux-hardware.org/?probe=a3b1926b7e) | Nov 02, 2022 |
| MSI           | Prestige 15 A11SCX          | [973b498b3f](https://linux-hardware.org/?probe=973b498b3f) | Nov 02, 2022 |
| HP            | Laptop                      | [e1cd3de91a](https://linux-hardware.org/?probe=e1cd3de91a) | Nov 02, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [9819da96f2](https://linux-hardware.org/?probe=9819da96f2) | Nov 02, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [2d931f9e99](https://linux-hardware.org/?probe=2d931f9e99) | Nov 02, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [335af8b89b](https://linux-hardware.org/?probe=335af8b89b) | Nov 02, 2022 |
| HUAWEI        | BOD-WXX9                    | [d4ac3a5f04](https://linux-hardware.org/?probe=d4ac3a5f04) | Nov 02, 2022 |
| HP            | G42                         | [18c487d99d](https://linux-hardware.org/?probe=18c487d99d) | Nov 02, 2022 |
| Jumper        | EZbook                      | [08ec434199](https://linux-hardware.org/?probe=08ec434199) | Nov 02, 2022 |
| Notebook      | P65_P67SE                   | [9b99df1e15](https://linux-hardware.org/?probe=9b99df1e15) | Nov 02, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [d3beec5427](https://linux-hardware.org/?probe=d3beec5427) | Nov 02, 2022 |
| Apple         | MacBookPro11,5              | [f22ebdf694](https://linux-hardware.org/?probe=f22ebdf694) | Nov 01, 2022 |
| Apple         | MacBookPro11,5              | [a27142d25c](https://linux-hardware.org/?probe=a27142d25c) | Nov 01, 2022 |
| Lenovo        | ThinkPad X201 3680BR4       | [eeeeb33766](https://linux-hardware.org/?probe=eeeeb33766) | Nov 01, 2022 |
| Dell          | Precision 7530              | [b1b5f7678c](https://linux-hardware.org/?probe=b1b5f7678c) | Nov 01, 2022 |
| HP            | ProBook 4530s               | [34682f3bfe](https://linux-hardware.org/?probe=34682f3bfe) | Nov 01, 2022 |
| HP            | EliteBook 830 G5            | [379443a5d6](https://linux-hardware.org/?probe=379443a5d6) | Nov 01, 2022 |
| Lenovo        | ThinkPad T420 4236PG6       | [49d423bc50](https://linux-hardware.org/?probe=49d423bc50) | Nov 01, 2022 |
| HP            | EliteBook 830 G5            | [5e099af04c](https://linux-hardware.org/?probe=5e099af04c) | Nov 01, 2022 |
| Lenovo        | ThinkPad L590 20Q7001KIX    | [c8e545615f](https://linux-hardware.org/?probe=c8e545615f) | Nov 01, 2022 |
| Toshiba       | Satellite L50-B             | [c242c45dbe](https://linux-hardware.org/?probe=c242c45dbe) | Nov 01, 2022 |
| Acer          | Swift SF314-41              | [921b1a7ebf](https://linux-hardware.org/?probe=921b1a7ebf) | Nov 01, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [6db184e152](https://linux-hardware.org/?probe=6db184e152) | Nov 01, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [60cfb7dcc6](https://linux-hardware.org/?probe=60cfb7dcc6) | Nov 01, 2022 |
| SANTECH       | X170KM-G                    | [073f9a1d24](https://linux-hardware.org/?probe=073f9a1d24) | Nov 01, 2022 |
| Apple         | MacBookAir7,2               | [2532d13f74](https://linux-hardware.org/?probe=2532d13f74) | Nov 01, 2022 |
| Dell          | Precision 3510              | [a87bb1e8dd](https://linux-hardware.org/?probe=a87bb1e8dd) | Nov 01, 2022 |
| Acer          | Aspire one                  | [bfb9f97d74](https://linux-hardware.org/?probe=bfb9f97d74) | Oct 31, 2022 |
| Packard Be... | EasyNote TE11BZ             | [0301f1ddf1](https://linux-hardware.org/?probe=0301f1ddf1) | Oct 31, 2022 |
| Acer          | Aspire V5-561G              | [ea7f8f381b](https://linux-hardware.org/?probe=ea7f8f381b) | Oct 31, 2022 |
| SANTECH       | NL5xRU                      | [63e1b4298d](https://linux-hardware.org/?probe=63e1b4298d) | Oct 31, 2022 |
| ASUSTek       | X510UNR                     | [6a28e2929d](https://linux-hardware.org/?probe=6a28e2929d) | Oct 31, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [027cfb43c4](https://linux-hardware.org/?probe=027cfb43c4) | Oct 31, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [113930496e](https://linux-hardware.org/?probe=113930496e) | Oct 31, 2022 |
| Acer          | Aspire one                  | [82b34552f6](https://linux-hardware.org/?probe=82b34552f6) | Oct 31, 2022 |
| HP            | Victus by Laptop 16-d1xx... | [f141a6cddf](https://linux-hardware.org/?probe=f141a6cddf) | Oct 31, 2022 |
| HP            | Victus by Laptop 16-d1xx... | [b9890126af](https://linux-hardware.org/?probe=b9890126af) | Oct 31, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | [5355a5547a](https://linux-hardware.org/?probe=5355a5547a) | Oct 31, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [2934bab108](https://linux-hardware.org/?probe=2934bab108) | Oct 31, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [34727cd696](https://linux-hardware.org/?probe=34727cd696) | Oct 31, 2022 |
| Lenovo        | ThinkPad Edge E530 3259M... | [aa1f78db58](https://linux-hardware.org/?probe=aa1f78db58) | Oct 31, 2022 |
| Lenovo        | ThinkPad Edge E530 3259M... | [26b5f59993](https://linux-hardware.org/?probe=26b5f59993) | Oct 31, 2022 |
| Acer          | Nitro AN517-55              | [9653f093e1](https://linux-hardware.org/?probe=9653f093e1) | Oct 31, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | [209fa66bb9](https://linux-hardware.org/?probe=209fa66bb9) | Oct 30, 2022 |
| Acer          | Aspire 5732Z                | [df73e0ca67](https://linux-hardware.org/?probe=df73e0ca67) | Oct 30, 2022 |
| HP            | x2 210                      | [8ed0a97ee9](https://linux-hardware.org/?probe=8ed0a97ee9) | Oct 30, 2022 |
| HP            | EliteBook 840 G5            | [f8c58b7061](https://linux-hardware.org/?probe=f8c58b7061) | Oct 30, 2022 |
| ASUSTek       | N751JK                      | [eea92055f3](https://linux-hardware.org/?probe=eea92055f3) | Oct 30, 2022 |
| ASUSTek       | X510UNR                     | [41a0a441d3](https://linux-hardware.org/?probe=41a0a441d3) | Oct 30, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | [89595b2fa9](https://linux-hardware.org/?probe=89595b2fa9) | Oct 30, 2022 |
| HP            | ProBook 6560b               | [89feda4b09](https://linux-hardware.org/?probe=89feda4b09) | Oct 30, 2022 |
| HUAWEI        | KLVL-WXX9                   | [4e4e0ac802](https://linux-hardware.org/?probe=4e4e0ac802) | Oct 30, 2022 |
| HUAWEI        | KLVL-WXX9                   | [8887bce606](https://linux-hardware.org/?probe=8887bce606) | Oct 30, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [423ad57e72](https://linux-hardware.org/?probe=423ad57e72) | Oct 29, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [f8b4ce6c3f](https://linux-hardware.org/?probe=f8b4ce6c3f) | Oct 29, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [69198e503e](https://linux-hardware.org/?probe=69198e503e) | Oct 29, 2022 |
| HP            | Laptop 15-dw0xxx            | [f6b00cb10f](https://linux-hardware.org/?probe=f6b00cb10f) | Oct 29, 2022 |
| Toshiba       | Satellite L50-A-1D6         | [77f308d89c](https://linux-hardware.org/?probe=77f308d89c) | Oct 29, 2022 |
| Dell          | Precision 7520              | [f54f6d6354](https://linux-hardware.org/?probe=f54f6d6354) | Oct 29, 2022 |
| SANTECH       | PCx0Dx                      | [24462321e8](https://linux-hardware.org/?probe=24462321e8) | Oct 29, 2022 |
| Dell          | Precision 3570              | [fb016d8d01](https://linux-hardware.org/?probe=fb016d8d01) | Oct 29, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [1925c8ce1f](https://linux-hardware.org/?probe=1925c8ce1f) | Oct 29, 2022 |
| Dell          | Precision 3510              | [bc9324156f](https://linux-hardware.org/?probe=bc9324156f) | Oct 29, 2022 |
| HP            | OMEN by Laptop 15-dc1xxx    | [20d95ce78c](https://linux-hardware.org/?probe=20d95ce78c) | Oct 29, 2022 |
| HP            | Pavilion dv5                | [8bd42e12c3](https://linux-hardware.org/?probe=8bd42e12c3) | Oct 29, 2022 |
| Dell          | Inspiron 5570               | [6555e01443](https://linux-hardware.org/?probe=6555e01443) | Oct 29, 2022 |
| Dell          | Inspiron 1525               | [ffb4369f83](https://linux-hardware.org/?probe=ffb4369f83) | Oct 29, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [be41a03a4d](https://linux-hardware.org/?probe=be41a03a4d) | Oct 29, 2022 |
| Acer          | Predator PH315-53           | [b3dd383a83](https://linux-hardware.org/?probe=b3dd383a83) | Oct 29, 2022 |
| Teclast       | F7 Plus                     | [f416278476](https://linux-hardware.org/?probe=f416278476) | Oct 29, 2022 |
| Insyde        | Braswell                    | [d98b2d9661](https://linux-hardware.org/?probe=d98b2d9661) | Oct 29, 2022 |
| HUAWEI        | VLT-WX0                     | [e3662dc3bd](https://linux-hardware.org/?probe=e3662dc3bd) | Oct 29, 2022 |
| HUAWEI        | VLT-WX0                     | [7b414a3c7c](https://linux-hardware.org/?probe=7b414a3c7c) | Oct 29, 2022 |
| HP            | Pavilion dv6                | [6406b8b769](https://linux-hardware.org/?probe=6406b8b769) | Oct 29, 2022 |
| HP            | Pavilion dv6                | [7873dfb4cf](https://linux-hardware.org/?probe=7873dfb4cf) | Oct 29, 2022 |
| Acer          | Aspire E5-571G              | [cc0f34a2fa](https://linux-hardware.org/?probe=cc0f34a2fa) | Oct 29, 2022 |
| HUAWEI        | BOD-WXX9                    | [880d3ba9c9](https://linux-hardware.org/?probe=880d3ba9c9) | Oct 29, 2022 |
| Dell          | Latitude 5531               | [cdea65fd5c](https://linux-hardware.org/?probe=cdea65fd5c) | Oct 29, 2022 |
| ASUSTek       | K53SV                       | [4ead64f80f](https://linux-hardware.org/?probe=4ead64f80f) | Oct 28, 2022 |
| Apple         | MacBookPro14,3              | [6383143b5b](https://linux-hardware.org/?probe=6383143b5b) | Oct 28, 2022 |
| ASUSTek       | K53SV                       | [d3043c50ae](https://linux-hardware.org/?probe=d3043c50ae) | Oct 28, 2022 |
| Chuwi         | LapBook Pro                 | [d362ed14bf](https://linux-hardware.org/?probe=d362ed14bf) | Oct 28, 2022 |
| MSI           | Prestige 15 A12UC           | [3d4c4364f1](https://linux-hardware.org/?probe=3d4c4364f1) | Oct 28, 2022 |
| MSI           | Prestige 14Evo A12M         | [5e32f7b38b](https://linux-hardware.org/?probe=5e32f7b38b) | Oct 28, 2022 |
| HP            | Laptop 15s-eq2xxx           | [9dcb685f5e](https://linux-hardware.org/?probe=9dcb685f5e) | Oct 28, 2022 |
| Dell          | XPS 13 9310                 | [7205cfe7b4](https://linux-hardware.org/?probe=7205cfe7b4) | Oct 28, 2022 |
| Toshiba       | Satellite C650D             | [0696abd43c](https://linux-hardware.org/?probe=0696abd43c) | Oct 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [cfa027a9e2](https://linux-hardware.org/?probe=cfa027a9e2) | Oct 28, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [df9ef8c115](https://linux-hardware.org/?probe=df9ef8c115) | Oct 28, 2022 |
| Toshiba       | Satellite C650D             | [d42867d201](https://linux-hardware.org/?probe=d42867d201) | Oct 28, 2022 |
| Dell          | Precision 3510              | [b1f2e24e41](https://linux-hardware.org/?probe=b1f2e24e41) | Oct 28, 2022 |
| Dell          | Precision 3510              | [bb81eb9627](https://linux-hardware.org/?probe=bb81eb9627) | Oct 28, 2022 |
| Lenovo        | ThinkPad P52 20M9S1EM00     | [40de74c5c5](https://linux-hardware.org/?probe=40de74c5c5) | Oct 28, 2022 |
| HP            | Laptop 15s-fq4xxx           | [e06398e1bc](https://linux-hardware.org/?probe=e06398e1bc) | Oct 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [83179a6cea](https://linux-hardware.org/?probe=83179a6cea) | Oct 28, 2022 |
| Dell          | Latitude 5521               | [460057b367](https://linux-hardware.org/?probe=460057b367) | Oct 28, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [7d99f01f0e](https://linux-hardware.org/?probe=7d99f01f0e) | Oct 28, 2022 |
| Lenovo        | ThinkPad W540 20BHS0730D    | [f24dc12e06](https://linux-hardware.org/?probe=f24dc12e06) | Oct 28, 2022 |
| MSI           | Stealth GS66 12UGS          | [98b47019d1](https://linux-hardware.org/?probe=98b47019d1) | Oct 28, 2022 |
| Samsung       | 950XDB/951XDB/950XDY        | [2fdc53f0f3](https://linux-hardware.org/?probe=2fdc53f0f3) | Oct 28, 2022 |
| MSI           | Modern 14 B10RBSW           | [9c3c17a82e](https://linux-hardware.org/?probe=9c3c17a82e) | Oct 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [6314ec0dd1](https://linux-hardware.org/?probe=6314ec0dd1) | Oct 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [dcd40f9f78](https://linux-hardware.org/?probe=dcd40f9f78) | Oct 28, 2022 |
| Acer          | Aspire E5-573G              | [f575803f23](https://linux-hardware.org/?probe=f575803f23) | Oct 28, 2022 |
| Apple         | MacBookPro11,5              | [fc35e765fd](https://linux-hardware.org/?probe=fc35e765fd) | Oct 28, 2022 |
| MSI           | Katana GF66 11UC            | [83088617d3](https://linux-hardware.org/?probe=83088617d3) | Oct 28, 2022 |
| SANTECH       | NHx0DB,DE                   | [db8c0489f4](https://linux-hardware.org/?probe=db8c0489f4) | Oct 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [033cc83715](https://linux-hardware.org/?probe=033cc83715) | Oct 28, 2022 |
| HUAWEI        | KLVL-WXX9                   | [176fa68922](https://linux-hardware.org/?probe=176fa68922) | Oct 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [1d64fb48e7](https://linux-hardware.org/?probe=1d64fb48e7) | Oct 27, 2022 |
| Timi          | TM1701                      | [f246345845](https://linux-hardware.org/?probe=f246345845) | Oct 27, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [53832f0517](https://linux-hardware.org/?probe=53832f0517) | Oct 27, 2022 |
| ASUSTek       | S551LN                      | [30d97ad99e](https://linux-hardware.org/?probe=30d97ad99e) | Oct 27, 2022 |
| Unknown       | Unknown                     | [a03935aadd](https://linux-hardware.org/?probe=a03935aadd) | Oct 27, 2022 |
| Samsung       | 950XDB/951XDB/950XDY        | [f27c4e1041](https://linux-hardware.org/?probe=f27c4e1041) | Oct 27, 2022 |
| HP            | 255 G7 Notebook PC          | [8cf00ceef5](https://linux-hardware.org/?probe=8cf00ceef5) | Oct 27, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [639503102e](https://linux-hardware.org/?probe=639503102e) | Oct 27, 2022 |
| HP            | 255 G8 Notebook PC          | [ba5aec702a](https://linux-hardware.org/?probe=ba5aec702a) | Oct 27, 2022 |
| HP            | ProBook 640 G1              | [3a9f97607d](https://linux-hardware.org/?probe=3a9f97607d) | Oct 27, 2022 |
| Unknown       | Unknown                     | [069ce9d405](https://linux-hardware.org/?probe=069ce9d405) | Oct 27, 2022 |
| MSI           | PS63 Modern 8RC             | [36b663cec7](https://linux-hardware.org/?probe=36b663cec7) | Oct 27, 2022 |
| MSI           | PS63 Modern 8RC             | [e00fd51503](https://linux-hardware.org/?probe=e00fd51503) | Oct 27, 2022 |
| HP            | ProBook 450 G5              | [664bf1184f](https://linux-hardware.org/?probe=664bf1184f) | Oct 27, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [264d164669](https://linux-hardware.org/?probe=264d164669) | Oct 27, 2022 |
| Dell          | Latitude 9420               | [a601281b46](https://linux-hardware.org/?probe=a601281b46) | Oct 27, 2022 |
| Dell          | Latitude E5530 non-vPro     | [a5c5f0ec1e](https://linux-hardware.org/?probe=a5c5f0ec1e) | Oct 27, 2022 |
| HP            | Pavilion dv6                | [ed392a140d](https://linux-hardware.org/?probe=ed392a140d) | Oct 27, 2022 |
| HP            | Pavilion dv6                | [1e14922876](https://linux-hardware.org/?probe=1e14922876) | Oct 27, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [0c037323d9](https://linux-hardware.org/?probe=0c037323d9) | Oct 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [24da197a3a](https://linux-hardware.org/?probe=24da197a3a) | Oct 27, 2022 |
| Dell          | Inspiron 5515               | [74ad4c8c59](https://linux-hardware.org/?probe=74ad4c8c59) | Oct 27, 2022 |
| HP            | ProBook 6560b               | [222a5c2dbe](https://linux-hardware.org/?probe=222a5c2dbe) | Oct 27, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [670823778e](https://linux-hardware.org/?probe=670823778e) | Oct 27, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [a308f68bce](https://linux-hardware.org/?probe=a308f68bce) | Oct 27, 2022 |
| Acer          | Aspire 5750G                | [b51a20d480](https://linux-hardware.org/?probe=b51a20d480) | Oct 27, 2022 |
| MSI           | Katana GF66 12UC            | [9b8f917e6b](https://linux-hardware.org/?probe=9b8f917e6b) | Oct 27, 2022 |
| Dell          | Inspiron 5590               | [f1a5637218](https://linux-hardware.org/?probe=f1a5637218) | Oct 27, 2022 |
| Lenovo        | ThinkPad X260 20F5S2WX05    | [710f95eab8](https://linux-hardware.org/?probe=710f95eab8) | Oct 27, 2022 |
| Lenovo        | ThinkPad T480s 20L8S5YM0... | [c348de09bf](https://linux-hardware.org/?probe=c348de09bf) | Oct 26, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [0d705b0971](https://linux-hardware.org/?probe=0d705b0971) | Oct 26, 2022 |
| HP            | ProBook 450 G3              | [4aa258716b](https://linux-hardware.org/?probe=4aa258716b) | Oct 26, 2022 |
| HP            | ProBook 450 G3              | [26d1b8b2b2](https://linux-hardware.org/?probe=26d1b8b2b2) | Oct 26, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [022cfe6707](https://linux-hardware.org/?probe=022cfe6707) | Oct 26, 2022 |
| ASUSTek       | X555LAB                     | [44d47f5024](https://linux-hardware.org/?probe=44d47f5024) | Oct 26, 2022 |
| ASUSTek       | VivoBook S15 X510UF         | [85b4bc70fa](https://linux-hardware.org/?probe=85b4bc70fa) | Oct 26, 2022 |
| HP            | 240 G8 Notebook PC          | [25765f4a76](https://linux-hardware.org/?probe=25765f4a76) | Oct 26, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | [7e1a95e569](https://linux-hardware.org/?probe=7e1a95e569) | Oct 26, 2022 |
| Lenovo        | ThinkPad T480 20L50000IX    | [bcb1b11c50](https://linux-hardware.org/?probe=bcb1b11c50) | Oct 26, 2022 |
| HP            | 250 G8 Notebook PC          | [d4ebaa71a2](https://linux-hardware.org/?probe=d4ebaa71a2) | Oct 26, 2022 |
| Acer          | Extensa 2540                | [367660309f](https://linux-hardware.org/?probe=367660309f) | Oct 26, 2022 |
| Lenovo        | ThinkPad E470 20H1006JIX    | [8bc8778497](https://linux-hardware.org/?probe=8bc8778497) | Oct 26, 2022 |
| Timi          | A7S                         | [004df6b9a1](https://linux-hardware.org/?probe=004df6b9a1) | Oct 26, 2022 |
| HP            | Laptop 17-cp0xxx            | [60d57edbfb](https://linux-hardware.org/?probe=60d57edbfb) | Oct 26, 2022 |
| Dell          | XPS 15 9520                 | [1ede815931](https://linux-hardware.org/?probe=1ede815931) | Oct 26, 2022 |
| Lenovo        | ThinkPad T450 20BUS0S902    | [1115da2433](https://linux-hardware.org/?probe=1115da2433) | Oct 26, 2022 |
| MSI           | Stealth GS66 12UH           | [3c985bb814](https://linux-hardware.org/?probe=3c985bb814) | Oct 26, 2022 |
| MSI           | Stealth GS66 12UH           | [336132b016](https://linux-hardware.org/?probe=336132b016) | Oct 26, 2022 |
| ASUSTek       | 1005HA                      | [118fed891f](https://linux-hardware.org/?probe=118fed891f) | Oct 26, 2022 |
| Dell          | Latitude E5570              | [2d59f069b4](https://linux-hardware.org/?probe=2d59f069b4) | Oct 26, 2022 |
| Dell          | XPS 15 7590                 | [5265f4d89f](https://linux-hardware.org/?probe=5265f4d89f) | Oct 26, 2022 |
| HP            | EliteBook 840 G5            | [4b28c73302](https://linux-hardware.org/?probe=4b28c73302) | Oct 26, 2022 |
| HUAWEI        | HN-WX9X                     | [042ffc026d](https://linux-hardware.org/?probe=042ffc026d) | Oct 26, 2022 |
| MSI           | Modern 15 A11M              | [0a658be9fc](https://linux-hardware.org/?probe=0a658be9fc) | Oct 26, 2022 |
| Timi          | A7S                         | [77a87009dd](https://linux-hardware.org/?probe=77a87009dd) | Oct 26, 2022 |
| HP            | Spectre Laptop 13-af0xx     | [1ded224c69](https://linux-hardware.org/?probe=1ded224c69) | Oct 26, 2022 |
| Google        | Apel                        | [f3bf9850dd](https://linux-hardware.org/?probe=f3bf9850dd) | Oct 26, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [53e6b23ebf](https://linux-hardware.org/?probe=53e6b23ebf) | Oct 26, 2022 |
| Acer          | Aspire E5-571               | [2920658e38](https://linux-hardware.org/?probe=2920658e38) | Oct 25, 2022 |
| Samsung       | 767XCL                      | [17bd1b4506](https://linux-hardware.org/?probe=17bd1b4506) | Oct 25, 2022 |
| Dell          | Latitude E6430              | [f196a9762f](https://linux-hardware.org/?probe=f196a9762f) | Oct 25, 2022 |
| Dell          | Latitude E6430              | [8062ec17fd](https://linux-hardware.org/?probe=8062ec17fd) | Oct 25, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [2d7fa062e3](https://linux-hardware.org/?probe=2d7fa062e3) | Oct 25, 2022 |
| ASUSTek       | N751JK                      | [f6f0ff5048](https://linux-hardware.org/?probe=f6f0ff5048) | Oct 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [7bf16d5a25](https://linux-hardware.org/?probe=7bf16d5a25) | Oct 25, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [94fa6196b8](https://linux-hardware.org/?probe=94fa6196b8) | Oct 25, 2022 |
| HP            | Pavilion dv6                | [03e2594419](https://linux-hardware.org/?probe=03e2594419) | Oct 25, 2022 |
| Apple         | MacBook5,1                  | [da04330684](https://linux-hardware.org/?probe=da04330684) | Oct 25, 2022 |
| Dell          | XPS 15 9570                 | [5f9de95e9c](https://linux-hardware.org/?probe=5f9de95e9c) | Oct 25, 2022 |
| Lenovo        | V15-IGL 82C3                | [264fcfd9f1](https://linux-hardware.org/?probe=264fcfd9f1) | Oct 25, 2022 |
| Dell          | Precision M6800             | [6c15780d7a](https://linux-hardware.org/?probe=6c15780d7a) | Oct 25, 2022 |
| HP            | ENVY 15                     | [faf3ff2256](https://linux-hardware.org/?probe=faf3ff2256) | Oct 25, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [cca91f3fe8](https://linux-hardware.org/?probe=cca91f3fe8) | Oct 25, 2022 |
| Dell          | Latitude E7270              | [7f2c8b9e9c](https://linux-hardware.org/?probe=7f2c8b9e9c) | Oct 25, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [8f34a9c24c](https://linux-hardware.org/?probe=8f34a9c24c) | Oct 25, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [a8c29545e6](https://linux-hardware.org/?probe=a8c29545e6) | Oct 25, 2022 |
| Dell          | Inspiron 3501               | [6764a6860f](https://linux-hardware.org/?probe=6764a6860f) | Oct 25, 2022 |
| Lenovo        | ThinkPad T470 20HES0FW00    | [1f939e0414](https://linux-hardware.org/?probe=1f939e0414) | Oct 25, 2022 |
| Dell          | Latitude 5500               | [6e1b321740](https://linux-hardware.org/?probe=6e1b321740) | Oct 25, 2022 |
| HP            | Laptop 15s-fq1xxx           | [badb0d5aee](https://linux-hardware.org/?probe=badb0d5aee) | Oct 25, 2022 |
| HP            | Laptop 15s-fq1xxx           | [f4174b55a2](https://linux-hardware.org/?probe=f4174b55a2) | Oct 25, 2022 |
| Lenovo        | Z50-70 20354                | [08b673e57b](https://linux-hardware.org/?probe=08b673e57b) | Oct 25, 2022 |
| LG Electro... | 17Z90N-V.AA55D              | [bf40de3f5a](https://linux-hardware.org/?probe=bf40de3f5a) | Oct 25, 2022 |
| Acer          | Aspire A715-42G             | [72b73a6552](https://linux-hardware.org/?probe=72b73a6552) | Oct 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [b2bb88f27f](https://linux-hardware.org/?probe=b2bb88f27f) | Oct 25, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [26415e4b74](https://linux-hardware.org/?probe=26415e4b74) | Oct 25, 2022 |
| Apple         | MacBookAir6,1               | [4785b7f6f6](https://linux-hardware.org/?probe=4785b7f6f6) | Oct 25, 2022 |
| HP            | 650                         | [d7b73bebc7](https://linux-hardware.org/?probe=d7b73bebc7) | Oct 25, 2022 |
| Lenovo        | ThinkPad T460 20FMS08H00    | [13422369f7](https://linux-hardware.org/?probe=13422369f7) | Oct 25, 2022 |
| Dell          | Inspiron 7559               | [2a1b8eb060](https://linux-hardware.org/?probe=2a1b8eb060) | Oct 25, 2022 |
| Dell          | Vostro 15 5501              | [3338297022](https://linux-hardware.org/?probe=3338297022) | Oct 25, 2022 |
| Dell          | Precision 3530              | [8d806f9e53](https://linux-hardware.org/?probe=8d806f9e53) | Oct 25, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | [f8aa3a7277](https://linux-hardware.org/?probe=f8aa3a7277) | Oct 25, 2022 |
| HP            | 255 G8 Notebook PC          | [30c305f07c](https://linux-hardware.org/?probe=30c305f07c) | Oct 25, 2022 |
| HP            | Laptop 15s-eq2xxx           | [3146a3d644](https://linux-hardware.org/?probe=3146a3d644) | Oct 25, 2022 |
| ASUSTek       | GL502VMK                    | [9a18ff1b13](https://linux-hardware.org/?probe=9a18ff1b13) | Oct 25, 2022 |
| Lenovo        | Yoga 900S-12ISK 80ML        | [0c13fbf129](https://linux-hardware.org/?probe=0c13fbf129) | Oct 25, 2022 |
| PC Special... | N13xWU                      | [4d728f13c9](https://linux-hardware.org/?probe=4d728f13c9) | Oct 25, 2022 |
| Dell          | XPS 15 7590                 | [7f9028d036](https://linux-hardware.org/?probe=7f9028d036) | Oct 25, 2022 |
| PC Special... | N13xWU                      | [58b775c64c](https://linux-hardware.org/?probe=58b775c64c) | Oct 25, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | [86b8ce83b2](https://linux-hardware.org/?probe=86b8ce83b2) | Oct 25, 2022 |
| Toshiba       | Satellite Pro S500          | [a26efdcfb5](https://linux-hardware.org/?probe=a26efdcfb5) | Oct 25, 2022 |
| Dell          | XPS 15 7590                 | [811985183a](https://linux-hardware.org/?probe=811985183a) | Oct 25, 2022 |
| HP            | Laptop 15-dw0xxx            | [4e87fd9438](https://linux-hardware.org/?probe=4e87fd9438) | Oct 25, 2022 |
| HP            | ProBook 640 G1              | [cfb2e32cea](https://linux-hardware.org/?probe=cfb2e32cea) | Oct 25, 2022 |
| ASUSTek       | X555YI                      | [5d6562117a](https://linux-hardware.org/?probe=5d6562117a) | Oct 25, 2022 |
| HP            | EliteBook 820 G2            | [b31fec75e1](https://linux-hardware.org/?probe=b31fec75e1) | Oct 25, 2022 |
| Timi          | Mi Laptop Pro 15            | [4474edfd79](https://linux-hardware.org/?probe=4474edfd79) | Oct 25, 2022 |
| Dell          | G15 5511                    | [0f47c64bab](https://linux-hardware.org/?probe=0f47c64bab) | Oct 25, 2022 |
| ASUSTek       | GL553VD                     | [20278229cd](https://linux-hardware.org/?probe=20278229cd) | Oct 25, 2022 |
| HUAWEI        | BOHB-WAX9                   | [fe222419ec](https://linux-hardware.org/?probe=fe222419ec) | Oct 25, 2022 |
| Acer          | Aspire A515-45              | [4584821ae6](https://linux-hardware.org/?probe=4584821ae6) | Oct 25, 2022 |
| HP            | 340S G7 Notebook PC         | [95707c7cd5](https://linux-hardware.org/?probe=95707c7cd5) | Oct 25, 2022 |
| Lenovo        | ThinkPad T495 20NJ000XIX    | [169601c723](https://linux-hardware.org/?probe=169601c723) | Oct 25, 2022 |
| Lenovo        | ThinkPad T495 20NJ000XIX    | [efb9c3d448](https://linux-hardware.org/?probe=efb9c3d448) | Oct 25, 2022 |
| Lenovo        | B51-80 80LM                 | [aaed1997fd](https://linux-hardware.org/?probe=aaed1997fd) | Oct 25, 2022 |
| HP            | Spectre Laptop 13-af0xx     | [7e6d814d87](https://linux-hardware.org/?probe=7e6d814d87) | Oct 25, 2022 |
| Dell          | XPS 15 9500                 | [f827f47265](https://linux-hardware.org/?probe=f827f47265) | Oct 25, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [42647c28ba](https://linux-hardware.org/?probe=42647c28ba) | Oct 25, 2022 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [18931ec5f6](https://linux-hardware.org/?probe=18931ec5f6) | Oct 25, 2022 |
| Fujitsu       | LIFEBOOK A532               | [e176b2ac7c](https://linux-hardware.org/?probe=e176b2ac7c) | Oct 25, 2022 |
| ASUSTek       | X555LI                      | [fe6b4aa2a6](https://linux-hardware.org/?probe=fe6b4aa2a6) | Oct 25, 2022 |
| HP            | Pavilion Notebook           | [35cf015c33](https://linux-hardware.org/?probe=35cf015c33) | Oct 25, 2022 |
| Dell          | Inspiron 13-7359            | [5a6d4ce6e7](https://linux-hardware.org/?probe=5a6d4ce6e7) | Oct 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [dc70e52da3](https://linux-hardware.org/?probe=dc70e52da3) | Oct 25, 2022 |
| MSI           | Prestige 14Evo A11M         | [7c4edd1a6d](https://linux-hardware.org/?probe=7c4edd1a6d) | Oct 24, 2022 |
| Sony          | SVE1712Z1EB                 | [23b6ac5cde](https://linux-hardware.org/?probe=23b6ac5cde) | Oct 24, 2022 |
| HP            | 470 G8 Notebook PC          | [1cae6fb5ac](https://linux-hardware.org/?probe=1cae6fb5ac) | Oct 24, 2022 |
| Dell          | Latitude E6430              | [3fbd9c277d](https://linux-hardware.org/?probe=3fbd9c277d) | Oct 24, 2022 |
| HUAWEI        | KLVD-WXX9                   | [1bbbcd4843](https://linux-hardware.org/?probe=1bbbcd4843) | Oct 24, 2022 |
| Dell          | Inspiron 16 7610            | [96ae3c2941](https://linux-hardware.org/?probe=96ae3c2941) | Oct 24, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [15ced71b20](https://linux-hardware.org/?probe=15ced71b20) | Oct 24, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [c6134bcca2](https://linux-hardware.org/?probe=c6134bcca2) | Oct 24, 2022 |
| HP            | 470 G8 Notebook PC          | [4c3e8196af](https://linux-hardware.org/?probe=4c3e8196af) | Oct 24, 2022 |
| ASUSTek       | GL553VD                     | [a9235eda91](https://linux-hardware.org/?probe=a9235eda91) | Oct 24, 2022 |
| Acer          | Aspire A515-52G             | [f569841512](https://linux-hardware.org/?probe=f569841512) | Oct 24, 2022 |
| HUAWEI        | KLVL-WXX9                   | [8994af98ff](https://linux-hardware.org/?probe=8994af98ff) | Oct 24, 2022 |
| Acer          | Aspire ES1-520              | [44375f0b06](https://linux-hardware.org/?probe=44375f0b06) | Oct 24, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | [4948eb3b16](https://linux-hardware.org/?probe=4948eb3b16) | Oct 24, 2022 |
| Acer          | Nitro AN517-51              | [7fed0ea2a9](https://linux-hardware.org/?probe=7fed0ea2a9) | Oct 24, 2022 |
| Dell          | Inspiron 5570               | [aeae483e35](https://linux-hardware.org/?probe=aeae483e35) | Oct 24, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | [eae727e6a0](https://linux-hardware.org/?probe=eae727e6a0) | Oct 24, 2022 |
| Notebook      | PCX0DX                      | [e29790dc3c](https://linux-hardware.org/?probe=e29790dc3c) | Oct 24, 2022 |
| HUAWEI        | KLVL-WXX9                   | [fc7326f81b](https://linux-hardware.org/?probe=fc7326f81b) | Oct 24, 2022 |
| HP            | Laptop 15s-fq0xxx           | [2510215a0b](https://linux-hardware.org/?probe=2510215a0b) | Oct 24, 2022 |
| MSI           | GE62 7RE                    | [bd5b8943f4](https://linux-hardware.org/?probe=bd5b8943f4) | Oct 24, 2022 |
| Dell          | XPS 15 9560                 | [37fc32cacd](https://linux-hardware.org/?probe=37fc32cacd) | Oct 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [95ad909dc8](https://linux-hardware.org/?probe=95ad909dc8) | Oct 24, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [9b7ac9b23e](https://linux-hardware.org/?probe=9b7ac9b23e) | Oct 24, 2022 |
| HP            | Pavilion Notebook           | [d953ededc3](https://linux-hardware.org/?probe=d953ededc3) | Oct 24, 2022 |
| Olivetti      | Olibook P75B                | [a1b4023949](https://linux-hardware.org/?probe=a1b4023949) | Oct 24, 2022 |
| HP            | 340S G7 Notebook PC         | [dc8eab937b](https://linux-hardware.org/?probe=dc8eab937b) | Oct 24, 2022 |
| Lenovo        | ThinkPad T480 20L5000AIX    | [43650773c9](https://linux-hardware.org/?probe=43650773c9) | Oct 24, 2022 |
| HUAWEI        | KPL-W0X                     | [aea737fcab](https://linux-hardware.org/?probe=aea737fcab) | Oct 24, 2022 |
| Dell          | Latitude E5500              | [10cb5545fd](https://linux-hardware.org/?probe=10cb5545fd) | Oct 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [e198c305e4](https://linux-hardware.org/?probe=e198c305e4) | Oct 24, 2022 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | [d663683611](https://linux-hardware.org/?probe=d663683611) | Oct 24, 2022 |
| ASUSTek       | X555LAB                     | [506468af47](https://linux-hardware.org/?probe=506468af47) | Oct 24, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [417beae8e5](https://linux-hardware.org/?probe=417beae8e5) | Oct 24, 2022 |
| Packard Be... | DOT S                       | [f280a6ccbc](https://linux-hardware.org/?probe=f280a6ccbc) | Oct 24, 2022 |
| ASUSTek       | X555LAB                     | [a1e654c422](https://linux-hardware.org/?probe=a1e654c422) | Oct 24, 2022 |
| HP            | EliteBook 8440p             | [0ffbef18a5](https://linux-hardware.org/?probe=0ffbef18a5) | Oct 24, 2022 |
| Lenovo        | ThinkPad X230 232465G       | [4cfe90552b](https://linux-hardware.org/?probe=4cfe90552b) | Oct 24, 2022 |
| MSI           | Stealth 15M B12UE           | [a6190e6271](https://linux-hardware.org/?probe=a6190e6271) | Oct 24, 2022 |
| Lenovo        | ThinkPad T470 20HES4VB00    | [f7b39d371a](https://linux-hardware.org/?probe=f7b39d371a) | Oct 24, 2022 |
| Acer          | Aspire A315-42              | [20dcade848](https://linux-hardware.org/?probe=20dcade848) | Oct 24, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [22a138a507](https://linux-hardware.org/?probe=22a138a507) | Oct 24, 2022 |
| HUAWEI        | MateBook D                  | [b219f88756](https://linux-hardware.org/?probe=b219f88756) | Oct 24, 2022 |
| Dell          | Latitude 7490               | [96759bdb49](https://linux-hardware.org/?probe=96759bdb49) | Oct 24, 2022 |
| Dell          | Inspiron 5590               | [802e0f0c61](https://linux-hardware.org/?probe=802e0f0c61) | Oct 24, 2022 |
| ASUSTek       | UX310UQ                     | [5a928ace3b](https://linux-hardware.org/?probe=5a928ace3b) | Oct 24, 2022 |
| Dell          | Latitude E7240              | [33c37015df](https://linux-hardware.org/?probe=33c37015df) | Oct 24, 2022 |
| HUAWEI        | MACHD-WXX9                  | [9e56111afe](https://linux-hardware.org/?probe=9e56111afe) | Oct 24, 2022 |
| Acer          | Aspire A515-45              | [b39d63f4f2](https://linux-hardware.org/?probe=b39d63f4f2) | Oct 24, 2022 |
| Lenovo        | G50-45 80MQ                 | [2628815c23](https://linux-hardware.org/?probe=2628815c23) | Oct 24, 2022 |
| Chuwi         | HeroBook Air                | [055a6c2be8](https://linux-hardware.org/?probe=055a6c2be8) | Oct 23, 2022 |
| Chuwi         | HeroBook Air                | [cb299f8f1b](https://linux-hardware.org/?probe=cb299f8f1b) | Oct 23, 2022 |
| Chuwi         | HeroBook Air                | [753874362e](https://linux-hardware.org/?probe=753874362e) | Oct 23, 2022 |
| ASUSTek       | K53SJ                       | [8c85e545f2](https://linux-hardware.org/?probe=8c85e545f2) | Oct 23, 2022 |
| HP            | 340S G7 Notebook PC         | [406538a0de](https://linux-hardware.org/?probe=406538a0de) | Oct 23, 2022 |
| Dell          | XPS 13 9305                 | [8fec9e2536](https://linux-hardware.org/?probe=8fec9e2536) | Oct 22, 2022 |
| Acer          | Aspire V3-772G              | [7361aed7f9](https://linux-hardware.org/?probe=7361aed7f9) | Oct 22, 2022 |
| Acer          | Aspire 5733                 | [ef561df926](https://linux-hardware.org/?probe=ef561df926) | Oct 22, 2022 |
| Dell          | Latitude E6440              | [030896045a](https://linux-hardware.org/?probe=030896045a) | Oct 22, 2022 |
| HUAWEI        | MACHD-WXX9                  | [74c290e909](https://linux-hardware.org/?probe=74c290e909) | Oct 22, 2022 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | [f460f8dc4e](https://linux-hardware.org/?probe=f460f8dc4e) | Oct 22, 2022 |
| HP            | Laptop 17-cp0xxx            | [d0a1d2c4f5](https://linux-hardware.org/?probe=d0a1d2c4f5) | Oct 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [66418dda52](https://linux-hardware.org/?probe=66418dda52) | Oct 22, 2022 |
| Dell          | Latitude E5530 non-vPro     | [20f991643f](https://linux-hardware.org/?probe=20f991643f) | Oct 21, 2022 |
| MSI           | Prestige 14Evo A11M         | [c63a7ccdeb](https://linux-hardware.org/?probe=c63a7ccdeb) | Oct 21, 2022 |
| LG Electro... | 16Z90P-G.AP75D              | [1e1526e9d8](https://linux-hardware.org/?probe=1e1526e9d8) | Oct 21, 2022 |
| Lenovo        | ThinkPad E550 20DFCTO1WW    | [0249022aca](https://linux-hardware.org/?probe=0249022aca) | Oct 20, 2022 |
| Lenovo        | V110-15IAP 80TG             | [68a04f2544](https://linux-hardware.org/?probe=68a04f2544) | Oct 20, 2022 |
| HP            | Laptop 15s-eq2xxx           | [f966d5d584](https://linux-hardware.org/?probe=f966d5d584) | Oct 20, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [d042d922e5](https://linux-hardware.org/?probe=d042d922e5) | Oct 20, 2022 |
| ASUSTek       | T200TAC                     | [0aad9d8ecd](https://linux-hardware.org/?probe=0aad9d8ecd) | Oct 20, 2022 |
| ASUSTek       | X540SAA                     | [e3fef524ee](https://linux-hardware.org/?probe=e3fef524ee) | Oct 20, 2022 |
| Sony          | SVE1513B1EW                 | [77ef0b542b](https://linux-hardware.org/?probe=77ef0b542b) | Oct 20, 2022 |
| Microtech     | CoreBook                    | [0592b30e41](https://linux-hardware.org/?probe=0592b30e41) | Oct 19, 2022 |
| Microtech     | CoreBook                    | [536451ed8a](https://linux-hardware.org/?probe=536451ed8a) | Oct 19, 2022 |
| Dell          | Inspiron 7590               | [43ec5b2df8](https://linux-hardware.org/?probe=43ec5b2df8) | Oct 19, 2022 |
| Acer          | Aspire ES1-331              | [f5ace96d5d](https://linux-hardware.org/?probe=f5ace96d5d) | Oct 19, 2022 |
| ASUSTek       | T200TAC                     | [c33c750766](https://linux-hardware.org/?probe=c33c750766) | Oct 18, 2022 |
| Fujitsu       | LIFEBOOK E753               | [1fbb05ae6b](https://linux-hardware.org/?probe=1fbb05ae6b) | Oct 18, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [08327d561d](https://linux-hardware.org/?probe=08327d561d) | Oct 18, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [2c47736da1](https://linux-hardware.org/?probe=2c47736da1) | Oct 18, 2022 |
| MSI           | Summit E16Flip A11UCT       | [f1ec40e34d](https://linux-hardware.org/?probe=f1ec40e34d) | Oct 17, 2022 |
| Lenovo        | G50-70 20351                | [a1e9be5323](https://linux-hardware.org/?probe=a1e9be5323) | Oct 17, 2022 |
| Lenovo        | ThinkPad T60 1952CTO        | [f84f14587b](https://linux-hardware.org/?probe=f84f14587b) | Oct 17, 2022 |
| Samsung       | R509                        | [ce3166845f](https://linux-hardware.org/?probe=ce3166845f) | Oct 17, 2022 |
| HP            | 255 G3                      | [a6ef9f4649](https://linux-hardware.org/?probe=a6ef9f4649) | Oct 17, 2022 |
| Dell          | Latitude 3380               | [76a82ca1e6](https://linux-hardware.org/?probe=76a82ca1e6) | Oct 17, 2022 |
| HUAWEI        | BOM-WXX9                    | [594b141136](https://linux-hardware.org/?probe=594b141136) | Oct 17, 2022 |
| HP            | Laptop 15s-eq2xxx           | [57436f7d31](https://linux-hardware.org/?probe=57436f7d31) | Oct 17, 2022 |
| Notebook      | W230SS                      | [abb5e7fda8](https://linux-hardware.org/?probe=abb5e7fda8) | Oct 16, 2022 |
| Lenovo        | Legion S7 16ARHA7 82UG      | [5c38639fff](https://linux-hardware.org/?probe=5c38639fff) | Oct 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [0cceedcb07](https://linux-hardware.org/?probe=0cceedcb07) | Oct 16, 2022 |
| Lenovo        | Legion S7 16ARHA7 82UG      | [eae5ab7d9c](https://linux-hardware.org/?probe=eae5ab7d9c) | Oct 16, 2022 |
| Acer          | Aspire E5-575G              | [4aff854065](https://linux-hardware.org/?probe=4aff854065) | Oct 16, 2022 |
| Acer          | Aspire A515-45              | [7a8b3b953d](https://linux-hardware.org/?probe=7a8b3b953d) | Oct 15, 2022 |
| ASUSTek       | X555UA                      | [f0adae0aba](https://linux-hardware.org/?probe=f0adae0aba) | Oct 14, 2022 |
| HP            | Pavilion g6                 | [4fbce46637](https://linux-hardware.org/?probe=4fbce46637) | Oct 14, 2022 |
| Chuwi         | HeroBook Pro                | [4fe76d84fd](https://linux-hardware.org/?probe=4fe76d84fd) | Oct 13, 2022 |
| Dell          | Studio 1555                 | [52104abe69](https://linux-hardware.org/?probe=52104abe69) | Oct 13, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [e2db064195](https://linux-hardware.org/?probe=e2db064195) | Oct 13, 2022 |
| Dell          | Vostro 3558                 | [855e0d050c](https://linux-hardware.org/?probe=855e0d050c) | Oct 13, 2022 |
| HP            | 340S G7 Notebook PC         | [1927ae6949](https://linux-hardware.org/?probe=1927ae6949) | Oct 12, 2022 |
| Acer          | Aspire 5740                 | [273721cef2](https://linux-hardware.org/?probe=273721cef2) | Oct 12, 2022 |
| ASUSTek       | N550JK                      | [457bef52a9](https://linux-hardware.org/?probe=457bef52a9) | Oct 12, 2022 |
| Dell          | Inspiron 7520               | [df55c5c266](https://linux-hardware.org/?probe=df55c5c266) | Oct 12, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [00d174fcf4](https://linux-hardware.org/?probe=00d174fcf4) | Oct 12, 2022 |
| ASUSTek       | E402MA                      | [807cf84523](https://linux-hardware.org/?probe=807cf84523) | Oct 11, 2022 |
| Lenovo        | ThinkPad T470 20JNS08H00    | [8926251d64](https://linux-hardware.org/?probe=8926251d64) | Oct 11, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [e060b11754](https://linux-hardware.org/?probe=e060b11754) | Oct 11, 2022 |
| HP            | Presario CQ57               | [b67f538b81](https://linux-hardware.org/?probe=b67f538b81) | Oct 10, 2022 |
| Dell          | Inspiron 7520               | [aa8415aa98](https://linux-hardware.org/?probe=aa8415aa98) | Oct 10, 2022 |
| Lenovo        | IdeaPad S510p 20298         | [f3a23a25c6](https://linux-hardware.org/?probe=f3a23a25c6) | Oct 10, 2022 |
| Unknown       | Unknown                     | [d00832c27c](https://linux-hardware.org/?probe=d00832c27c) | Oct 09, 2022 |
| ASUSTek       | P552LA                      | [6985e4f01e](https://linux-hardware.org/?probe=6985e4f01e) | Oct 09, 2022 |
| HUAWEI        | KLVL-WXX9                   | [fda26adf83](https://linux-hardware.org/?probe=fda26adf83) | Oct 09, 2022 |
| HUAWEI        | KLVL-WXX9                   | [a5511bd426](https://linux-hardware.org/?probe=a5511bd426) | Oct 09, 2022 |
| Fujitsu Si... | AMILO Pa 1538               | [11d843f241](https://linux-hardware.org/?probe=11d843f241) | Oct 08, 2022 |
| HP            | 255 G1                      | [fc9f63bfb6](https://linux-hardware.org/?probe=fc9f63bfb6) | Oct 08, 2022 |
| ASUSTek       | K50ID                       | [05e82f0dd5](https://linux-hardware.org/?probe=05e82f0dd5) | Oct 08, 2022 |
| Acer          | Aspire 5739G                | [9a380f66ea](https://linux-hardware.org/?probe=9a380f66ea) | Oct 08, 2022 |
| Dell          | Latitude 5580               | [77173e171f](https://linux-hardware.org/?probe=77173e171f) | Oct 08, 2022 |
| Lenovo        | IdeaPad Z500 5931           | [76791672ad](https://linux-hardware.org/?probe=76791672ad) | Oct 08, 2022 |
| HP            | Laptop 15-dw0xxx            | [3427421197](https://linux-hardware.org/?probe=3427421197) | Oct 08, 2022 |
| AZW           | GT-R                        | [d6abb5cc99](https://linux-hardware.org/?probe=d6abb5cc99) | Oct 07, 2022 |
| MSI           | Prestige 14Evo A11M         | [68137e0e8d](https://linux-hardware.org/?probe=68137e0e8d) | Oct 07, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [9e3105f47c](https://linux-hardware.org/?probe=9e3105f47c) | Oct 07, 2022 |
| HP            | Pavilion Laptop 15-cw0xx... | [2105a7b1c9](https://linux-hardware.org/?probe=2105a7b1c9) | Oct 07, 2022 |
| Packard Be... | EasyNote TJ65               | [bb815f037b](https://linux-hardware.org/?probe=bb815f037b) | Oct 06, 2022 |
| ASUSTek       | X580VD                      | [16d2a296c8](https://linux-hardware.org/?probe=16d2a296c8) | Oct 06, 2022 |
| Lenovo        | LEGIONC7 82EH               | [880c4773fd](https://linux-hardware.org/?probe=880c4773fd) | Oct 06, 2022 |
| Lenovo        | G510 20238                  | [18a7e32e6d](https://linux-hardware.org/?probe=18a7e32e6d) | Oct 06, 2022 |
| HP            | Pavilion Laptop 15-cw0xx... | [eaafe4ad36](https://linux-hardware.org/?probe=eaafe4ad36) | Oct 05, 2022 |
| HP            | 250 G5 Notebook PC          | [614d8b9df8](https://linux-hardware.org/?probe=614d8b9df8) | Oct 05, 2022 |
| HP            | EliteBook 8470p             | [4ba28bc3a8](https://linux-hardware.org/?probe=4ba28bc3a8) | Oct 05, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [72a5f6b03c](https://linux-hardware.org/?probe=72a5f6b03c) | Oct 05, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [a51c98849b](https://linux-hardware.org/?probe=a51c98849b) | Oct 05, 2022 |
| Dell          | XPS 15 9570                 | [0edf82b5be](https://linux-hardware.org/?probe=0edf82b5be) | Oct 05, 2022 |
| Microtech     | EBL14                       | [8420051a94](https://linux-hardware.org/?probe=8420051a94) | Oct 05, 2022 |
| HP            | Laptop 15s-eq3xxx           | [2bd986670e](https://linux-hardware.org/?probe=2bd986670e) | Oct 04, 2022 |
| AZW           | GT-R                        | [781d42cdb2](https://linux-hardware.org/?probe=781d42cdb2) | Oct 04, 2022 |
| Dell          | Latitude 5420               | [e4d629b41b](https://linux-hardware.org/?probe=e4d629b41b) | Oct 04, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | [ca89628082](https://linux-hardware.org/?probe=ca89628082) | Oct 03, 2022 |
| Dell          | Latitude E5540              | [9804fbe4c4](https://linux-hardware.org/?probe=9804fbe4c4) | Oct 03, 2022 |
| HP            | 250 G4                      | [7c892fab7a](https://linux-hardware.org/?probe=7c892fab7a) | Oct 03, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | [9c3f9bb60e](https://linux-hardware.org/?probe=9c3f9bb60e) | Oct 03, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [10e3123558](https://linux-hardware.org/?probe=10e3123558) | Oct 03, 2022 |
| HP            | 255 G8 Notebook PC          | [1a2e047ca1](https://linux-hardware.org/?probe=1a2e047ca1) | Oct 03, 2022 |
| Apple         | MacBook7,1                  | [49595ef8f4](https://linux-hardware.org/?probe=49595ef8f4) | Oct 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [cd9376ae2c](https://linux-hardware.org/?probe=cd9376ae2c) | Oct 02, 2022 |
| Lenovo        | ThinkPad L540 20AUA13S00    | [04ffca5382](https://linux-hardware.org/?probe=04ffca5382) | Oct 01, 2022 |
| HP            | 250 G3                      | [753ef53a5a](https://linux-hardware.org/?probe=753ef53a5a) | Oct 01, 2022 |
| Lenovo        | V130-15IKB 81HN             | [44a4ed90e1](https://linux-hardware.org/?probe=44a4ed90e1) | Oct 01, 2022 |
| Fujitsu       | LIFEBOOK S904               | [c9c83f0112](https://linux-hardware.org/?probe=c9c83f0112) | Oct 01, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [5bfc8f0a7d](https://linux-hardware.org/?probe=5bfc8f0a7d) | Sep 30, 2022 |
| SANTECH       | NHx0EH_EJ_EK                | [01366bbeb7](https://linux-hardware.org/?probe=01366bbeb7) | Sep 30, 2022 |
| HP            | Laptop 15s-eq3xxx           | [b15bae8e77](https://linux-hardware.org/?probe=b15bae8e77) | Sep 30, 2022 |
| HP            | Laptop 15s-eq3xxx           | [126b8dd3ec](https://linux-hardware.org/?probe=126b8dd3ec) | Sep 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [2c6b161d0f](https://linux-hardware.org/?probe=2c6b161d0f) | Sep 29, 2022 |
| HP            | ProBook 440 G7              | [99f729e814](https://linux-hardware.org/?probe=99f729e814) | Sep 29, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | [f5ddf4a2b4](https://linux-hardware.org/?probe=f5ddf4a2b4) | Sep 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [cd08dccca4](https://linux-hardware.org/?probe=cd08dccca4) | Sep 28, 2022 |
| Lenovo        | IdeaPad Z510 20287          | [78badcba3c](https://linux-hardware.org/?probe=78badcba3c) | Sep 28, 2022 |
| HP            | Pavilion Laptop 14-ce2xx... | [6eab6db53b](https://linux-hardware.org/?probe=6eab6db53b) | Sep 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [47acb38827](https://linux-hardware.org/?probe=47acb38827) | Sep 27, 2022 |
| Acer          | TravelMate 5730             | [88b501ffbe](https://linux-hardware.org/?probe=88b501ffbe) | Sep 27, 2022 |
| Lenovo        | V15-ADA 82C7                | [e53b87c0fd](https://linux-hardware.org/?probe=e53b87c0fd) | Sep 26, 2022 |
| Fujitsu       | LIFEBOOK A544               | [6e4694775c](https://linux-hardware.org/?probe=6e4694775c) | Sep 26, 2022 |
| Lenovo        | ThinkPad T480s 20L7001PI... | [31235a45b5](https://linux-hardware.org/?probe=31235a45b5) | Sep 26, 2022 |
| Acer          | Aspire E1-570G              | [ed657bfbb6](https://linux-hardware.org/?probe=ed657bfbb6) | Sep 26, 2022 |
| Razer         | Blade 15 Base Model (Ear... | [1b4db0c30c](https://linux-hardware.org/?probe=1b4db0c30c) | Sep 26, 2022 |
| Acer          | Aspire A515-51G             | [c45069d56d](https://linux-hardware.org/?probe=c45069d56d) | Sep 26, 2022 |
| Acer          | Aspire A515-51G             | [3441e0cac3](https://linux-hardware.org/?probe=3441e0cac3) | Sep 26, 2022 |
| Razer         | Blade 14 - RZ09-0370        | [a5e00e04bd](https://linux-hardware.org/?probe=a5e00e04bd) | Sep 25, 2022 |
| Unknown       | A116C1_1                    | [470cd9917c](https://linux-hardware.org/?probe=470cd9917c) | Sep 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [7be473c3c6](https://linux-hardware.org/?probe=7be473c3c6) | Sep 25, 2022 |
| Lenovo        | IdeaPad3-15ADA05 81W1       | [d2192ee6f0](https://linux-hardware.org/?probe=d2192ee6f0) | Sep 25, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [d277bf47ec](https://linux-hardware.org/?probe=d277bf47ec) | Sep 25, 2022 |
| Lenovo        | ThinkPad T440p              | [270cf10219](https://linux-hardware.org/?probe=270cf10219) | Sep 25, 2022 |
| Apple         | MacBookPro16,1              | [6e7d310781](https://linux-hardware.org/?probe=6e7d310781) | Sep 25, 2022 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | [96f4499ec5](https://linux-hardware.org/?probe=96f4499ec5) | Sep 25, 2022 |
| HP            | 255 G5                      | [2a8f595510](https://linux-hardware.org/?probe=2a8f595510) | Sep 24, 2022 |
| Razer         | Blade 15 Base Model (Ear... | [029c059963](https://linux-hardware.org/?probe=029c059963) | Sep 24, 2022 |
| Dell          | Vostro V131                 | [809655978a](https://linux-hardware.org/?probe=809655978a) | Sep 24, 2022 |
| HUAWEI        | BOHB-WAX9                   | [18a4d2bb72](https://linux-hardware.org/?probe=18a4d2bb72) | Sep 23, 2022 |
| HP            | 250 G4                      | [5d4c56fe14](https://linux-hardware.org/?probe=5d4c56fe14) | Sep 23, 2022 |
| Fujitsu       | LIFEBOOK A544               | [648fb5c63e](https://linux-hardware.org/?probe=648fb5c63e) | Sep 22, 2022 |
| Dell          | Latitude 5501               | [f40716377a](https://linux-hardware.org/?probe=f40716377a) | Sep 22, 2022 |
| Lenovo        | G50-45 80E3                 | [41af175db4](https://linux-hardware.org/?probe=41af175db4) | Sep 21, 2022 |
| Unknown       | Unknown                     | [af65739ccc](https://linux-hardware.org/?probe=af65739ccc) | Sep 21, 2022 |
| Dell          | Latitude E5530 non-vPro     | [6352f6fb82](https://linux-hardware.org/?probe=6352f6fb82) | Sep 21, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y3C... | [8c6fcedcd5](https://linux-hardware.org/?probe=8c6fcedcd5) | Sep 21, 2022 |
| ASUSTek       | GL553VD                     | [e6cb381fd2](https://linux-hardware.org/?probe=e6cb381fd2) | Sep 21, 2022 |
| HP            | Pavilion 15                 | [56a10ce74c](https://linux-hardware.org/?probe=56a10ce74c) | Sep 21, 2022 |
| Timi          | A35S                        | [a57a688f31](https://linux-hardware.org/?probe=a57a688f31) | Sep 21, 2022 |
| Intel         | Kabylake Platform           | [8b1c5eb5bf](https://linux-hardware.org/?probe=8b1c5eb5bf) | Sep 21, 2022 |
| HP            | Folio 13                    | [eafa8204e9](https://linux-hardware.org/?probe=eafa8204e9) | Sep 20, 2022 |
| ASUSTek       | X541UAK                     | [b5a6e3ca5e](https://linux-hardware.org/?probe=b5a6e3ca5e) | Sep 20, 2022 |
| HP            | Pavilion Power Laptop 15... | [360e860fb1](https://linux-hardware.org/?probe=360e860fb1) | Sep 20, 2022 |
| HP            | EliteBook 840 14 inch G9... | [450a86c900](https://linux-hardware.org/?probe=450a86c900) | Sep 20, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [32120dfcd4](https://linux-hardware.org/?probe=32120dfcd4) | Sep 20, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [8003baae8c](https://linux-hardware.org/?probe=8003baae8c) | Sep 19, 2022 |
| HUAWEI        | BOM-WXX9                    | [f2906f8b8d](https://linux-hardware.org/?probe=f2906f8b8d) | Sep 19, 2022 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [9b14ec4438](https://linux-hardware.org/?probe=9b14ec4438) | Sep 19, 2022 |
| MSI           | Prestige 14Evo A11M         | [4b412dd569](https://linux-hardware.org/?probe=4b412dd569) | Sep 19, 2022 |
| HP            | G42                         | [3f584eb1af](https://linux-hardware.org/?probe=3f584eb1af) | Sep 19, 2022 |
| Dell          | Latitude 5420               | [2d9d6512bc](https://linux-hardware.org/?probe=2d9d6512bc) | Sep 19, 2022 |
| Acer          | Aspire A515-51G             | [3f987553d9](https://linux-hardware.org/?probe=3f987553d9) | Sep 18, 2022 |
| Microtech     | CoreBook                    | [6b1a53d2c2](https://linux-hardware.org/?probe=6b1a53d2c2) | Sep 18, 2022 |
| HP            | EliteBook 850 G3            | [6a2f2c9841](https://linux-hardware.org/?probe=6a2f2c9841) | Sep 18, 2022 |
| Lenovo        | ThinkPad T440p              | [bf397424f3](https://linux-hardware.org/?probe=bf397424f3) | Sep 18, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [f40cc0db8a](https://linux-hardware.org/?probe=f40cc0db8a) | Sep 18, 2022 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [751df30316](https://linux-hardware.org/?probe=751df30316) | Sep 18, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [87c3b99589](https://linux-hardware.org/?probe=87c3b99589) | Sep 18, 2022 |
| MSI           | Prestige 15 A12UC           | [48437ccf94](https://linux-hardware.org/?probe=48437ccf94) | Sep 17, 2022 |
| NEC Comput... | PC-VY21AEZ75                | [a24d79ffc2](https://linux-hardware.org/?probe=a24d79ffc2) | Sep 17, 2022 |
| MSI           | Prestige 14Evo A11M         | [f474823b5a](https://linux-hardware.org/?probe=f474823b5a) | Sep 17, 2022 |
| Lenovo        | G50-45 80E3                 | [6c5b0c0659](https://linux-hardware.org/?probe=6c5b0c0659) | Sep 17, 2022 |
| HP            | 250 G8 Notebook PC          | [6dd18a5a96](https://linux-hardware.org/?probe=6dd18a5a96) | Sep 17, 2022 |
| MSI           | Delta 15 A5EFK              | [382e0f70a3](https://linux-hardware.org/?probe=382e0f70a3) | Sep 17, 2022 |
| Lenovo        | G50-45 80E3                 | [8c355ea88e](https://linux-hardware.org/?probe=8c355ea88e) | Sep 17, 2022 |
| Dell          | XPS 15 9560                 | [4a903b438f](https://linux-hardware.org/?probe=4a903b438f) | Sep 17, 2022 |
| HP            | Unknown                     | [e87c925eb0](https://linux-hardware.org/?probe=e87c925eb0) | Sep 16, 2022 |
| HP            | Laptop 15s-fq2xxx           | [e7bb3017fb](https://linux-hardware.org/?probe=e7bb3017fb) | Sep 16, 2022 |
| HP            | Laptop 15s-fq2xxx           | [c81727b775](https://linux-hardware.org/?probe=c81727b775) | Sep 16, 2022 |
| Lenovo        | G50-45 80E3                 | [59c06bcd6f](https://linux-hardware.org/?probe=59c06bcd6f) | Sep 16, 2022 |
| Dell          | Inspiron 15-3552            | [583d7c550e](https://linux-hardware.org/?probe=583d7c550e) | Sep 16, 2022 |
| Acer          | Swift SF314-54              | [c3b076c416](https://linux-hardware.org/?probe=c3b076c416) | Sep 15, 2022 |
| Chuwi         | CoreBook X                  | [e59a625390](https://linux-hardware.org/?probe=e59a625390) | Sep 15, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U4S... | [b7ed5c7f4a](https://linux-hardware.org/?probe=b7ed5c7f4a) | Sep 14, 2022 |
| MSI           | Prestige 14Evo A11M         | [5a69611620](https://linux-hardware.org/?probe=5a69611620) | Sep 13, 2022 |
| MSI           | Prestige 14Evo A11M         | [4c5dc2ec7d](https://linux-hardware.org/?probe=4c5dc2ec7d) | Sep 13, 2022 |
| ASUSTek       | X541UJ                      | [9745e99a08](https://linux-hardware.org/?probe=9745e99a08) | Sep 13, 2022 |
| Dell          | Venue 11 Pro 7140           | [d6fed8866c](https://linux-hardware.org/?probe=d6fed8866c) | Sep 13, 2022 |
| Dell          | XPS 17 9700                 | [24eaecfdd8](https://linux-hardware.org/?probe=24eaecfdd8) | Sep 13, 2022 |
| Apple         | MacBook5,1                  | [8bdaf4361b](https://linux-hardware.org/?probe=8bdaf4361b) | Sep 12, 2022 |
| Toshiba       | PORTEGE Z30-B               | [6b1829aad1](https://linux-hardware.org/?probe=6b1829aad1) | Sep 12, 2022 |
| Toshiba       | PORTEGE Z30-B               | [9ef29f2258](https://linux-hardware.org/?probe=9ef29f2258) | Sep 12, 2022 |
| Apple         | MacBook5,1                  | [be66df4eb9](https://linux-hardware.org/?probe=be66df4eb9) | Sep 12, 2022 |
| Sony          | SVE1512J6EW                 | [69e2400606](https://linux-hardware.org/?probe=69e2400606) | Sep 11, 2022 |
| HP            | ProBook 645 G3              | [0bd9070bee](https://linux-hardware.org/?probe=0bd9070bee) | Sep 11, 2022 |
| Valve         | Jupiter                     | [694e9a60ad](https://linux-hardware.org/?probe=694e9a60ad) | Sep 11, 2022 |
| HP            | G42                         | [092b9e2c38](https://linux-hardware.org/?probe=092b9e2c38) | Sep 11, 2022 |
| HP            | 255 G8 Notebook PC          | [d2c057ed6e](https://linux-hardware.org/?probe=d2c057ed6e) | Sep 11, 2022 |
| HP            | Presario CQ56               | [ccc7d97678](https://linux-hardware.org/?probe=ccc7d97678) | Sep 11, 2022 |
| HP            | 255 G8 Notebook PC          | [cca78f4488](https://linux-hardware.org/?probe=cca78f4488) | Sep 11, 2022 |
| HP            | Pavilion dv6000 (RP986EA... | [f20de20683](https://linux-hardware.org/?probe=f20de20683) | Sep 11, 2022 |
| Apple         | MacBookPro12,1              | [4bb5badf61](https://linux-hardware.org/?probe=4bb5badf61) | Sep 10, 2022 |
| Lenovo        | ThinkPad L380 20M6S48000    | [74102b95cb](https://linux-hardware.org/?probe=74102b95cb) | Sep 10, 2022 |
| ASUSTek       | UX310UQK                    | [dc650f1d77](https://linux-hardware.org/?probe=dc650f1d77) | Sep 10, 2022 |
| Dell          | Inspiron 16 5625            | [5ae1f0d923](https://linux-hardware.org/?probe=5ae1f0d923) | Sep 10, 2022 |
| Dell          | Venue 11 Pro 7140           | [08aadcd875](https://linux-hardware.org/?probe=08aadcd875) | Sep 10, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [498a2244e4](https://linux-hardware.org/?probe=498a2244e4) | Sep 09, 2022 |
| Apple         | MacBookPro11,2              | [47708e7772](https://linux-hardware.org/?probe=47708e7772) | Sep 09, 2022 |
| Apple         | MacBookPro11,4              | [c5d5b88740](https://linux-hardware.org/?probe=c5d5b88740) | Sep 09, 2022 |
| Dell          | Latitude 7490               | [189b1d9ab2](https://linux-hardware.org/?probe=189b1d9ab2) | Sep 09, 2022 |
| Dell          | Latitude E6230              | [30d4c452fe](https://linux-hardware.org/?probe=30d4c452fe) | Sep 09, 2022 |
| Dell          | System XPS L702X            | [fa770ba044](https://linux-hardware.org/?probe=fa770ba044) | Sep 09, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [cada1ee58d](https://linux-hardware.org/?probe=cada1ee58d) | Sep 09, 2022 |
| Acer          | Aspire 5715Z                | [614ae0addd](https://linux-hardware.org/?probe=614ae0addd) | Sep 09, 2022 |
| Notebook      | W230SS                      | [9ea483f3dd](https://linux-hardware.org/?probe=9ea483f3dd) | Sep 09, 2022 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | [b4e36a92c7](https://linux-hardware.org/?probe=b4e36a92c7) | Sep 08, 2022 |
| Dell          | XPS 15 7590                 | [57cbaefc6e](https://linux-hardware.org/?probe=57cbaefc6e) | Sep 08, 2022 |
| Acer          | Aspire 5736Z                | [820b817bff](https://linux-hardware.org/?probe=820b817bff) | Sep 08, 2022 |
| Dell          | Latitude E5450              | [305ef21301](https://linux-hardware.org/?probe=305ef21301) | Sep 08, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | [7cf6479781](https://linux-hardware.org/?probe=7cf6479781) | Sep 08, 2022 |
| LG Electro... | 17Z90P-G.AA86D              | [1f304e9792](https://linux-hardware.org/?probe=1f304e9792) | Sep 07, 2022 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | [ac71ea732f](https://linux-hardware.org/?probe=ac71ea732f) | Sep 07, 2022 |
| HP            | Pavilion dv7                | [4a39ae67d5](https://linux-hardware.org/?probe=4a39ae67d5) | Sep 07, 2022 |
| Dell          | XPS 13 9305                 | [bc21b4b2a8](https://linux-hardware.org/?probe=bc21b4b2a8) | Sep 07, 2022 |
| ASUSTek       | X541UJ                      | [84b26ca406](https://linux-hardware.org/?probe=84b26ca406) | Sep 07, 2022 |
| Dell          | Inspiron 5584               | [3691775658](https://linux-hardware.org/?probe=3691775658) | Sep 07, 2022 |
| Toshiba       | Satellite C660              | [e7ad5166eb](https://linux-hardware.org/?probe=e7ad5166eb) | Sep 07, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [72ba31c33a](https://linux-hardware.org/?probe=72ba31c33a) | Sep 07, 2022 |
| Lenovo        | ThinkPad Edge E531 6885D... | [673c26165e](https://linux-hardware.org/?probe=673c26165e) | Sep 07, 2022 |
| MSI           | Modern 14 B11MOL            | [1ce0bfd512](https://linux-hardware.org/?probe=1ce0bfd512) | Sep 06, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | [ff127ee255](https://linux-hardware.org/?probe=ff127ee255) | Sep 06, 2022 |
| ASUSTek       | P751JF                      | [6f3898fe12](https://linux-hardware.org/?probe=6f3898fe12) | Sep 06, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | [d20b550fd6](https://linux-hardware.org/?probe=d20b550fd6) | Sep 06, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [76c716061a](https://linux-hardware.org/?probe=76c716061a) | Sep 06, 2022 |
| Lenovo        | ThinkPad T480s 20L8SC160... | [b860019cf4](https://linux-hardware.org/?probe=b860019cf4) | Sep 06, 2022 |
| HP            | 255 G8 Notebook PC          | [5c53e30fe6](https://linux-hardware.org/?probe=5c53e30fe6) | Sep 06, 2022 |
| ASUSTek       | X555LAB                     | [b10937286d](https://linux-hardware.org/?probe=b10937286d) | Sep 06, 2022 |
| Acer          | Aspire 5920G                | [af0e5553e9](https://linux-hardware.org/?probe=af0e5553e9) | Sep 05, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [dd3b771e55](https://linux-hardware.org/?probe=dd3b771e55) | Sep 05, 2022 |
| Gateway       | NS30                        | [2ade42aacf](https://linux-hardware.org/?probe=2ade42aacf) | Sep 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [ef9be6aaac](https://linux-hardware.org/?probe=ef9be6aaac) | Sep 05, 2022 |
| Dell          | Inspiron 16 5625            | [d38282759b](https://linux-hardware.org/?probe=d38282759b) | Sep 05, 2022 |
| Dell          | Latitude E6520              | [e37ba07a92](https://linux-hardware.org/?probe=e37ba07a92) | Sep 05, 2022 |
| HP            | 250 G8 Notebook PC          | [312e65fd07](https://linux-hardware.org/?probe=312e65fd07) | Sep 05, 2022 |
| Samsung       | 270E5G/270E5U               | [0300dd1a2d](https://linux-hardware.org/?probe=0300dd1a2d) | Sep 05, 2022 |
| HP            | Laptop 15s-eq2xxx           | [92b56566ae](https://linux-hardware.org/?probe=92b56566ae) | Sep 05, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Italy/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 462       | 12.33%  |
| Ubuntu 18.04                 | 287       | 7.66%   |
| Ubuntu 22.04                 | 181       | 4.83%   |
| OpenMandriva 4.2             | 105       | 2.8%    |
| Arch Rolling                 | 96        | 2.56%   |
| OpenMandriva 4.3             | 92        | 2.45%   |
| Fedora 36                    | 87        | 2.32%   |
| Debian 11                    | 81        | 2.16%   |
| Arch                         | 75        | 2%      |
| Xubuntu 18.04                | 69        | 1.84%   |
| Ubuntu 19.10                 | 68        | 1.81%   |
| Ubuntu 20.10                 | 61        | 1.63%   |
| Xubuntu 20.04                | 59        | 1.57%   |
| Ubuntu 21.10                 | 59        | 1.57%   |
| Ubuntu 19.04                 | 56        | 1.49%   |
| Linux Mint 20.3              | 54        | 1.44%   |
| KDE neon 20.04               | 54        | 1.44%   |
| Pop!_OS 22.04                | 53        | 1.41%   |
| Zorin 15                     | 49        | 1.31%   |
| Debian 10                    | 45        | 1.2%    |
| Zorin 16                     | 44        | 1.17%   |
| Linux Mint 21                | 42        | 1.12%   |
| Fedora 35                    | 42        | 1.12%   |
| Ubuntu 22.10                 | 40        | 1.07%   |
| Ubuntu 21.04                 | 40        | 1.07%   |
| Ubuntu 18.10                 | 40        | 1.07%   |
| Linux Mint 20.1              | 36        | 0.96%   |
| Pop!_OS 20.10                | 35        | 0.93%   |
| Linux Mint 19.3              | 35        | 0.93%   |
| Kubuntu 20.04                | 35        | 0.93%   |
| Fedora 33                    | 35        | 0.93%   |
| Linux Mint 20.2              | 34        | 0.91%   |
| Kubuntu 22.04                | 33        | 0.88%   |
| EndeavourOS Rolling          | 33        | 0.88%   |
| Linux Mint 20                | 32        | 0.85%   |
| ROSA R10                     | 29        | 0.77%   |
| Fedora 34                    | 27        | 0.72%   |
| Manjaro                      | 26        | 0.69%   |
| Fedora 32                    | 26        | 0.69%   |
| openSUSE Tumbleweed-XXXXXXXX | 25        | 0.67%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1242      | 34.84%  |
| Fedora        | 249       | 6.98%   |
| Linux Mint    | 247       | 6.93%   |
| OpenMandriva  | 225       | 6.31%   |
| Xubuntu       | 172       | 4.82%   |
| Arch          | 167       | 4.68%   |
| Debian        | 157       | 4.4%    |
| Pop!_OS       | 145       | 4.07%   |
| Manjaro       | 110       | 3.09%   |
| Kubuntu       | 106       | 2.97%   |
| Zorin         | 99        | 2.78%   |
| ROSA          | 84        | 2.36%   |
| KDE neon      | 66        | 1.85%   |
| Lubuntu       | 55        | 1.54%   |
| openSUSE      | 40        | 1.12%   |
| Endless       | 37        | 1.04%   |
| Elementary    | 37        | 1.04%   |
| Ubuntu MATE   | 35        | 0.98%   |
| EndeavourOS   | 35        | 0.98%   |
| ArcoLinux     | 21        | 0.59%   |
| BlackPanther  | 20        | 0.56%   |
| Ubuntu Unity  | 19        | 0.53%   |
| Gentoo        | 18        | 0.5%    |
| LMDE          | 17        | 0.48%   |
| MX            | 16        | 0.45%   |
| Kali          | 15        | 0.42%   |
| Clear Linux   | 15        | 0.42%   |
| Ubuntu Budgie | 12        | 0.34%   |
| Peppermint    | 11        | 0.31%   |
| Garuda Linux  | 11        | 0.31%   |
| Parrot        | 7         | 0.2%    |
| LinuxFX       | 6         | 0.17%   |
| SteamOS       | 5         | 0.14%   |
| Chrome OS     | 5         | 0.14%   |
| CentOS        | 4         | 0.11%   |
| Xero          | 3         | 0.08%   |
| Ubuntu Studio | 3         | 0.08%   |
| Slackware     | 3         | 0.08%   |
| Nobara        | 3         | 0.08%   |
| NixOS         | 3         | 0.08%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 100       | 2.43%   |
| 5.15.0-52-generic        | 95        | 2.31%   |
| 5.16.7-desktop-1omv4003  | 90        | 2.19%   |
| 5.4.0-42-generic         | 68        | 1.66%   |
| 5.15.0-46-generic        | 41        | 1%      |
| 5.4.0-26-generic         | 40        | 0.97%   |
| 5.3.0-46-generic         | 40        | 0.97%   |
| 5.4.0-52-generic         | 36        | 0.88%   |
| 5.4.0-29-generic         | 36        | 0.88%   |
| 5.15.0-56-generic        | 36        | 0.88%   |
| 5.15.0-47-generic        | 34        | 0.83%   |
| 5.4.0-58-generic         | 33        | 0.8%    |
| 5.3.0-40-generic         | 32        | 0.78%   |
| 5.3.0-42-generic         | 31        | 0.75%   |
| 5.4.0-48-generic         | 30        | 0.73%   |
| 6.0.2-arch1-1            | 28        | 0.68%   |
| 5.15.0-43-generic        | 28        | 0.68%   |
| 5.13.0-28-generic        | 27        | 0.66%   |
| 5.0.0-37-generic         | 27        | 0.66%   |
| 5.15.0-53-generic        | 25        | 0.61%   |
| 5.15.0-48-generic        | 25        | 0.61%   |
| 5.15.0-41-generic        | 25        | 0.61%   |
| 5.10.0-19-amd64          | 24        | 0.58%   |
| 5.3.0-51-generic         | 23        | 0.56%   |
| 5.19.0-23-generic        | 23        | 0.56%   |
| 5.4.0-54-generic         | 22        | 0.54%   |
| 5.4.0-47-generic         | 22        | 0.54%   |
| 5.4.0-28-generic         | 22        | 0.54%   |
| 5.15.0-50-generic        | 21        | 0.51%   |
| 4.18.0-15-generic        | 21        | 0.51%   |
| 5.4.0-33-generic         | 20        | 0.49%   |
| 5.4.0-37-generic         | 19        | 0.46%   |
| 5.19.16-200.fc36.x86_64  | 19        | 0.46%   |
| 5.19.0-76051900-generic  | 19        | 0.46%   |
| 5.13.0-30-generic        | 19        | 0.46%   |
| 5.11.0-38-generic        | 19        | 0.46%   |
| 5.4.0-91-generic         | 18        | 0.44%   |
| 5.11.0-37-generic        | 18        | 0.44%   |
| 4.18.16-desktop-1bP      | 18        | 0.44%   |
| 5.4.0-53-generic         | 17        | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 675       | 17.51%  |
| 5.15.0  | 365       | 9.47%   |
| 4.15.0  | 236       | 6.12%   |
| 5.3.0   | 223       | 5.78%   |
| 5.8.0   | 201       | 5.21%   |
| 5.13.0  | 189       | 4.9%    |
| 5.11.0  | 167       | 4.33%   |
| 5.0.0   | 113       | 2.93%   |
| 5.10.0  | 108       | 2.8%    |
| 5.10.14 | 100       | 2.59%   |
| 5.16.7  | 92        | 2.39%   |
| 4.18.0  | 86        | 2.23%   |
| 5.19.0  | 77        | 2%      |
| 6.0.2   | 53        | 1.37%   |
| 4.19.0  | 44        | 1.14%   |
| 5.19.16 | 29        | 0.75%   |
| 6.0.0   | 23        | 0.6%    |
| 5.17.5  | 20        | 0.52%   |
| 4.18.16 | 19        | 0.49%   |
| 4.9.60  | 18        | 0.47%   |
| 4.9.20  | 17        | 0.44%   |
| 6.0.6   | 16        | 0.41%   |
| 4.4.0   | 15        | 0.39%   |
| 5.17.1  | 14        | 0.36%   |
| 6.0.5   | 13        | 0.34%   |
| 6.0.12  | 13        | 0.34%   |
| 5.18.0  | 13        | 0.34%   |
| 6.0.9   | 11        | 0.29%   |
| 6.0.7   | 11        | 0.29%   |
| 5.19.12 | 11        | 0.29%   |
| 6.0.11  | 10        | 0.26%   |
| 5.19.6  | 10        | 0.26%   |
| 5.17.0  | 10        | 0.26%   |
| 5.16.11 | 10        | 0.26%   |
| 5.16.0  | 10        | 0.26%   |
| 5.14.14 | 10        | 0.26%   |
| 6.0.10  | 9         | 0.23%   |
| 5.9.8   | 9         | 0.23%   |
| 5.19.4  | 9         | 0.23%   |
| 5.14.0  | 9         | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 721       | 18.87%  |
| 5.15    | 445       | 11.65%  |
| 5.10    | 262       | 6.86%   |
| 5.3     | 248       | 6.49%   |
| 5.8     | 241       | 6.31%   |
| 4.15    | 237       | 6.2%    |
| 5.13    | 211       | 5.52%   |
| 5.11    | 204       | 5.34%   |
| 5.19    | 180       | 4.71%   |
| 6.0     | 173       | 4.53%   |
| 5.16    | 142       | 3.72%   |
| 5.0     | 116       | 3.04%   |
| 4.18    | 108       | 2.83%   |
| 5.17    | 65        | 1.7%    |
| 4.9     | 60        | 1.57%   |
| 4.19    | 57        | 1.49%   |
| 5.18    | 54        | 1.41%   |
| 5.14    | 54        | 1.41%   |
| 5.9     | 46        | 1.2%    |
| 5.12    | 38        | 0.99%   |
| 5.6     | 34        | 0.89%   |
| 5.5     | 34        | 0.89%   |
| 5.7     | 23        | 0.6%    |
| 4.4     | 16        | 0.42%   |
| 6.1     | 11        | 0.29%   |
| 5.2     | 9         | 0.24%   |
| 4.13    | 6         | 0.16%   |
| 4.1     | 6         | 0.16%   |
| 5.1     | 4         | 0.1%    |
| 4.12    | 4         | 0.1%    |
| 4.20    | 3         | 0.08%   |
| 4.17    | 3         | 0.08%   |
| 4.16    | 2         | 0.05%   |
| 3.10    | 2         | 0.05%   |
| 4.14    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 3243      | 94.05%  |
| i686   | 204       | 5.92%   |
| armv7l | 1         | 0.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 1586      | 44.07%  |
| KDE5             | 635       | 17.64%  |
| Unknown          | 395       | 10.98%  |
| XFCE             | 324       | 9%      |
| X-Cinnamon       | 194       | 5.39%   |
| MATE             | 96        | 2.67%   |
| KDE              | 66        | 1.83%   |
| LXQt             | 57        | 1.58%   |
| KDE4             | 50        | 1.39%   |
| Pantheon         | 36        | 1%      |
| Cinnamon         | 26        | 0.72%   |
| LXDE             | 25        | 0.69%   |
| Unity            | 20        | 0.56%   |
| Budgie           | 18        | 0.5%    |
| i3               | 15        | 0.42%   |
| GNOME Flashback  | 15        | 0.42%   |
| sway             | 5         | 0.14%   |
| Deepin           | 5         | 0.14%   |
| GNOME Classic    | 4         | 0.11%   |
| DWM              | 4         | 0.11%   |
| bspwm            | 4         | 0.11%   |
| Hyprland         | 3         | 0.08%   |
| xubuntu          | 2         | 0.06%   |
| qtile            | 2         | 0.06%   |
| openbox          | 2         | 0.06%   |
| Enlightenment    | 2         | 0.06%   |
| ubuntu           | 1         | 0.03%   |
| Trinity          | 1         | 0.03%   |
| none+i3          | 1         | 0.03%   |
| none+bspwm       | 1         | 0.03%   |
| lightdm-xsession | 1         | 0.03%   |
| gamescope        | 1         | 0.03%   |
| Cutefish         | 1         | 0.03%   |
| awesome          | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2738      | 76.93%  |
| Wayland | 583       | 16.38%  |
| Unknown | 205       | 5.76%   |
| Tty     | 33        | 0.93%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1676      | 46.85%  |
| SDDM    | 598       | 16.72%  |
| GDM     | 438       | 12.24%  |
| GDM3    | 384       | 10.74%  |
| LightDM | 317       | 8.86%   |
| TDM     | 96        | 2.68%   |
| KDM     | 51        | 1.43%   |
| XDM     | 6         | 0.17%   |
| SLiM    | 4         | 0.11%   |
| LXDM    | 3         | 0.08%   |
| WDM     | 1         | 0.03%   |
| MDM     | 1         | 0.03%   |
| Ly      | 1         | 0.03%   |
| GREETD  | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang         | Notebooks | Percent |
|--------------|-----------|---------|
| it_IT        | 2186      | 61.72%  |
| en_US        | 737       | 20.81%  |
| Unknown      | 430       | 12.14%  |
| en_GB        | 73        | 2.06%   |
| C            | 49        | 1.38%   |
| de_DE        | 10        | 0.28%   |
| fr_FR        | 9         | 0.25%   |
| es_ES        | 8         | 0.23%   |
| de_IT        | 7         | 0.2%    |
| ru_RU        | 5         | 0.14%   |
| POSIX        | 4         | 0.11%   |
| en_AU        | 3         | 0.08%   |
| en_US.UTF8   | 2         | 0.06%   |
| en_AG        | 2         | 0.06%   |
| ro_RO        | 1         | 0.03%   |
| pt_BR        | 1         | 0.03%   |
| pl_PL        | 1         | 0.03%   |
| it_IT@euro   | 1         | 0.03%   |
| it_IT.UTF -8 | 1         | 0.03%   |
| it_CH        | 1         | 0.03%   |
| fur_IT       | 1         | 0.03%   |
| fr_BE        | 1         | 0.03%   |
| es_US        | 1         | 0.03%   |
| en_US@euro   | 1         | 0.03%   |
| en_US.utf-8  | 1         | 0.03%   |
| en_IN        | 1         | 0.03%   |
| en_IE        | 1         | 0.03%   |
| de_CH        | 1         | 0.03%   |
| de_AT        | 1         | 0.03%   |
| C.UTF8       | 1         | 0.03%   |
| bg_BG        | 1         | 0.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 1817      | 51.93%  |
| BIOS | 1682      | 48.07%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 2749      | 78.41%  |
| Overlay  | 305       | 8.7%    |
| Btrfs    | 273       | 7.79%   |
| Unknown  | 103       | 2.94%   |
| Xfs      | 27        | 0.77%   |
| Zfs      | 18        | 0.51%   |
| Ext2     | 11        | 0.31%   |
| F2fs     | 7         | 0.2%    |
| Ext3     | 5         | 0.14%   |
| Tmpfs    | 4         | 0.11%   |
| XXX4     | 2         | 0.06%   |
| Reiserfs | 1         | 0.03%   |
| Jfs      | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1848      | 52.51%  |
| GPT     | 1303      | 37.03%  |
| MBR     | 368       | 10.46%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3086      | 88.22%  |
| Yes       | 412       | 11.78%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2334      | 66.53%  |
| Yes       | 1174      | 33.47%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 775       | 22.5%   |
| ASUSTek Computer    | 557       | 16.17%  |
| Lenovo              | 551       | 16%     |
| Acer                | 393       | 11.41%  |
| Dell                | 359       | 10.42%  |
| Toshiba             | 96        | 2.79%   |
| Sony                | 82        | 2.38%   |
| Apple               | 82        | 2.38%   |
| HUAWEI              | 77        | 2.24%   |
| MSI                 | 65        | 1.89%   |
| Samsung Electronics | 64        | 1.86%   |
| Fujitsu             | 37        | 1.07%   |
| Packard Bell        | 29        | 0.84%   |
| Unknown             | 26        | 0.75%   |
| Mediacom            | 23        | 0.67%   |
| Chuwi               | 20        | 0.58%   |
| Teclast             | 19        | 0.55%   |
| Notebook            | 18        | 0.52%   |
| Fujitsu Siemens     | 18        | 0.52%   |
| Timi                | 15        | 0.44%   |
| Microtech           | 13        | 0.38%   |
| PC Specialist       | 11        | 0.32%   |
| TUXEDO              | 10        | 0.29%   |
| SANTECH             | 8         | 0.23%   |
| eMachines           | 7         | 0.2%    |
| TrekStor            | 6         | 0.17%   |
| Jumper              | 6         | 0.17%   |
| LG Electronics      | 5         | 0.15%   |
| Google              | 5         | 0.15%   |
| Alienware           | 5         | 0.15%   |
| YASHI               | 3         | 0.09%   |
| Valve               | 3         | 0.09%   |
| System76            | 3         | 0.09%   |
| Razer               | 3         | 0.09%   |
| Olivetti            | 3         | 0.09%   |
| TELECOMITALIA       | 2         | 0.06%   |
| SiComputer          | 2         | 0.06%   |
| Schenker            | 2         | 0.06%   |
| MicroByte           | 2         | 0.06%   |
| Intel               | 2         | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| HP Pavilion dv6                            | 49        | 1.42%   |
| Unknown                                    | 39        | 1.13%   |
| HP Notebook                                | 33        | 0.96%   |
| HP Pavilion 15                             | 23        | 0.67%   |
| HP Pavilion g6                             | 20        | 0.58%   |
| HUAWEI NBLK-WAX9X                          | 16        | 0.46%   |
| HP 255 G8 Notebook PC                      | 15        | 0.44%   |
| HP 255 G7 Notebook PC                      | 12        | 0.35%   |
| HP 15                                      | 12        | 0.35%   |
| Dell XPS 15 7590                           | 12        | 0.35%   |
| HP G62                                     | 11        | 0.32%   |
| HP 255 G6 Notebook PC                      | 11        | 0.32%   |
| Apple MacBook4,1                           | 11        | 0.32%   |
| Mediacom SmartBook 14 FullHD - SB14UC      | 10        | 0.29%   |
| Lenovo IdeaPad 3 15ADA05 81W1              | 10        | 0.29%   |
| HP 250 G6 Notebook PC                      | 10        | 0.29%   |
| HUAWEI KLVL-WXX9                           | 9         | 0.26%   |
| Dell XPS 15 9560                           | 9         | 0.26%   |
| Lenovo V145-15AST 81MT                     | 8         | 0.23%   |
| HP ProBook 450 G5                          | 8         | 0.23%   |
| HP Pavilion x2 Detachable                  | 8         | 0.23%   |
| HP Laptop 15s-eq2xxx                       | 8         | 0.23%   |
| HP Compaq 6730s                            | 8         | 0.23%   |
| Dell XPS 15 9570                           | 8         | 0.23%   |
| ASUS VivoBook_ASUSLaptop X580GD_N580GD     | 8         | 0.23%   |
| ASUS K53SC                                 | 8         | 0.23%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 7         | 0.2%    |
| Microtech ebookPro                         | 7         | 0.2%    |
| Lenovo G50-45 80E3                         | 7         | 0.2%    |
| HP ProBook 450 G6                          | 7         | 0.2%    |
| HP Pavilion Notebook                       | 7         | 0.2%    |
| HP Laptop 15s-fq1xxx                       | 7         | 0.2%    |
| HP Laptop 15-da0xxx                        | 7         | 0.2%    |
| HP ENVY 15                                 | 7         | 0.2%    |
| HP EliteBook 8440p                         | 7         | 0.2%    |
| HP EliteBook 2570p                         | 7         | 0.2%    |
| HP 620                                     | 7         | 0.2%    |
| HP 250 G7 Notebook PC                      | 7         | 0.2%    |
| Dell Latitude E7440                        | 7         | 0.2%    |
| Dell Inspiron 5570                         | 7         | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 269       | 7.81%   |
| Acer Aspire           | 259       | 7.52%   |
| HP Pavilion           | 209       | 6.07%   |
| Dell Latitude         | 134       | 3.89%   |
| Lenovo IdeaPad        | 125       | 3.63%   |
| HP EliteBook          | 92        | 2.67%   |
| Toshiba Satellite     | 84        | 2.44%   |
| ASUS VivoBook         | 84        | 2.44%   |
| Dell XPS              | 79        | 2.29%   |
| HP Laptop             | 74        | 2.15%   |
| Dell Inspiron         | 72        | 2.09%   |
| HP ProBook            | 70        | 2.03%   |
| HP Compaq             | 60        | 1.74%   |
| HP 255                | 52        | 1.51%   |
| HP 250                | 41        | 1.19%   |
| Unknown               | 39        | 1.13%   |
| Fujitsu LIFEBOOK      | 35        | 1.02%   |
| HP Notebook           | 33        | 0.96%   |
| Acer TravelMate       | 29        | 0.84%   |
| Acer Swift            | 29        | 0.84%   |
| Acer Extensa          | 29        | 0.84%   |
| Dell Vostro           | 28        | 0.81%   |
| Lenovo ThinkBook      | 27        | 0.78%   |
| Dell Precision        | 26        | 0.75%   |
| Packard Bell EasyNote | 22        | 0.64%   |
| ASUS ROG              | 17        | 0.49%   |
| HUAWEI NBLK-WAX9X     | 16        | 0.46%   |
| Apple MacBookPro11    | 16        | 0.46%   |
| HP Presario           | 14        | 0.41%   |
| HP ENVY               | 14        | 0.41%   |
| Acer Nitro            | 13        | 0.38%   |
| Mediacom SmartBook    | 12        | 0.35%   |
| HP ZBook              | 12        | 0.35%   |
| HP 15                 | 12        | 0.35%   |
| ASUS ZenBook          | 12        | 0.35%   |
| Lenovo Legion         | 11        | 0.32%   |
| HP OMEN               | 11        | 0.32%   |
| HP G62                | 11        | 0.32%   |
| Fujitsu Siemens AMILO | 11        | 0.32%   |
| Apple MacBook4        | 11        | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 302       | 8.77%   |
| 2020    | 299       | 8.68%   |
| 2018    | 280       | 8.13%   |
| 2013    | 236       | 6.85%   |
| 2021    | 235       | 6.82%   |
| 2017    | 234       | 6.79%   |
| 2008    | 212       | 6.16%   |
| 2011    | 211       | 6.13%   |
| 2010    | 210       | 6.1%    |
| 2016    | 205       | 5.95%   |
| 2012    | 201       | 5.84%   |
| 2015    | 198       | 5.75%   |
| 2014    | 196       | 5.69%   |
| 2009    | 167       | 4.85%   |
| 2007    | 113       | 3.28%   |
| 2006    | 61        | 1.77%   |
| 2022    | 52        | 1.51%   |
| 2005    | 23        | 0.67%   |
| Unknown | 5         | 0.15%   |
| 2004    | 3         | 0.09%   |
| 2003    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 3444      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 3130      | 90.05%  |
| Enabled  | 346       | 9.95%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3431      | 99.62%  |
| Yes  | 13        | 0.38%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 945       | 27.12%  |
| 3.01-4.0    | 905       | 25.98%  |
| 16.01-24.0  | 545       | 15.64%  |
| 8.01-16.0   | 529       | 15.18%  |
| 1.01-2.0    | 241       | 6.92%   |
| 32.01-64.0  | 149       | 4.28%   |
| 2.01-3.0    | 82        | 2.35%   |
| 0.51-1.0    | 44        | 1.26%   |
| 24.01-32.0  | 23        | 0.66%   |
| 64.01-256.0 | 18        | 0.52%   |
| 0.01-0.5    | 3         | 0.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1491      | 39.33%  |
| 2.01-3.0   | 896       | 23.63%  |
| 4.01-8.0   | 457       | 12.05%  |
| 3.01-4.0   | 443       | 11.69%  |
| 0.51-1.0   | 340       | 8.97%   |
| 8.01-16.0  | 110       | 2.9%    |
| 0.01-0.5   | 45        | 1.19%   |
| 16.01-24.0 | 7         | 0.18%   |
| 24.01-32.0 | 1         | 0.03%   |
| Unknown    | 1         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2627      | 75.08%  |
| 2      | 754       | 21.55%  |
| 3      | 79        | 2.26%   |
| 0      | 24        | 0.69%   |
| 4      | 11        | 0.31%   |
| 6      | 2         | 0.06%   |
| 5      | 2         | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1927      | 55.68%  |
| Yes       | 1534      | 44.32%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2778      | 80.31%  |
| No        | 681       | 19.69%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3377      | 97.94%  |
| No        | 71        | 2.06%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2490      | 71.39%  |
| No        | 998       | 28.61%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Italy   | 3444      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Milan               | 517       | 13.45%  |
| Rome                | 402       | 10.46%  |
| Turin               | 133       | 3.46%   |
| Naples              | 76        | 1.98%   |
| Bologna             | 74        | 1.93%   |
| Florence            | 69        | 1.8%    |
| Rho                 | 60        | 1.56%   |
| Genoa               | 55        | 1.43%   |
| Padova              | 51        | 1.33%   |
| Palermo             | 44        | 1.14%   |
| Verona              | 42        | 1.09%   |
| Bari                | 37        | 0.96%   |
| Brescia             | 31        | 0.81%   |
| Catania             | 28        | 0.73%   |
| Trieste             | 27        | 0.7%    |
| Parma               | 24        | 0.62%   |
| Bergamo             | 22        | 0.57%   |
| Bolzano             | 21        | 0.55%   |
| Pisa                | 20        | 0.52%   |
| Casalecchio di Reno | 20        | 0.52%   |
| Trento              | 18        | 0.47%   |
| Modena              | 18        | 0.47%   |
| Venice              | 16        | 0.42%   |
| Perugia             | 16        | 0.42%   |
| Seregno             | 15        | 0.39%   |
| Reggio Emilia       | 15        | 0.39%   |
| Monza               | 15        | 0.39%   |
| Cagliari            | 15        | 0.39%   |
| Udine               | 14        | 0.36%   |
| Sesto San Giovanni  | 13        | 0.34%   |
| Salerno             | 13        | 0.34%   |
| Taranto             | 12        | 0.31%   |
| Reggio Calabria     | 12        | 0.31%   |
| Forlì              | 12        | 0.31%   |
| Mestre              | 11        | 0.29%   |
| Legnano             | 11        | 0.29%   |
| Vicenza             | 10        | 0.26%   |
| Spinetoli           | 10        | 0.26%   |
| Pescara             | 10        | 0.26%   |
| Novara              | 10        | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 752       | 975    | 17.81%  |
| WDC                       | 429       | 523    | 10.16%  |
| Seagate                   | 411       | 493    | 9.73%   |
| Toshiba                   | 301       | 378    | 7.13%   |
| Sandisk                   | 266       | 347    | 6.3%    |
| Unknown                   | 252       | 335    | 5.97%   |
| Kingston                  | 241       | 282    | 5.71%   |
| Crucial                   | 238       | 271    | 5.64%   |
| Hitachi                   | 206       | 246    | 4.88%   |
| SK hynix                  | 157       | 190    | 3.72%   |
| HGST                      | 155       | 196    | 3.67%   |
| Micron Technology         | 107       | 126    | 2.53%   |
| Intel                     | 92        | 111    | 2.18%   |
| KIOXIA                    | 47        | 56     | 1.11%   |
| Fujitsu                   | 43        | 51     | 1.02%   |
| Phison                    | 36        | 55     | 0.85%   |
| China                     | 34        | 37     | 0.81%   |
| Apple                     | 28        | 30     | 0.66%   |
| SPCC                      | 23        | 28     | 0.54%   |
| LITEON                    | 21        | 26     | 0.5%    |
| Transcend                 | 20        | 24     | 0.47%   |
| JMicron Technology        | 20        | 23     | 0.47%   |
| Intenso                   | 18        | 18     | 0.43%   |
| Netac                     | 15        | 16     | 0.36%   |
| KingDian                  | 14        | 19     | 0.33%   |
| Teclast                   | 13        | 17     | 0.31%   |
| A-DATA Technology         | 13        | 15     | 0.31%   |
| PNY                       | 11        | 13     | 0.26%   |
| Drevo                     | 11        | 12     | 0.26%   |
| Unknown                   | 11        | 16     | 0.26%   |
| SABRENT                   | 10        | 10     | 0.24%   |
| Silicon Motion            | 9         | 12     | 0.21%   |
| LITEONIT                  | 9         | 19     | 0.21%   |
| Phison Electronics        | 8         | 9      | 0.19%   |
| Lenovo                    | 8         | 8      | 0.19%   |
| Corsair                   | 8         | 9      | 0.19%   |
| TCSUNBOW                  | 7         | 8      | 0.17%   |
| Patriot                   | 7         | 10     | 0.17%   |
| Microtech                 | 7         | 16     | 0.17%   |
| Micron/Crucial Technology | 7         | 8      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 65        | 1.49%   |
| Unknown MMC Card  32GB                              | 57        | 1.3%    |
| Crucial CT500MX500SSD1 500GB                        | 56        | 1.28%   |
| Toshiba MQ01ABF050 500GB                            | 55        | 1.26%   |
| Samsung SSD 860 EVO 500GB                           | 53        | 1.21%   |
| Samsung SSD 850 EVO 250GB                           | 46        | 1.05%   |
| Seagate ST500LT012-1DG142 500GB                     | 44        | 1.01%   |
| Seagate ST1000LM035-1RK172 1TB                      | 43        | 0.98%   |
| HGST HTS545050A7E680 500GB                          | 43        | 0.98%   |
| HGST HTS721010A9E630 1TB                            | 42        | 0.96%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 39        | 0.89%   |
| Samsung SSD 850 EVO 500GB                           | 38        | 0.87%   |
| Samsung NVMe SSD Drive 512GB                        | 32        | 0.73%   |
| Kingston SA400S37480G 480GB SSD                     | 32        | 0.73%   |
| Unknown MMC Card  64GB                              | 30        | 0.69%   |
| Crucial CT240BX500SSD1 240GB                        | 30        | 0.69%   |
| Toshiba MQ01ABD100 1TB                              | 28        | 0.64%   |
| SanDisk NVMe SSD Drive 512GB                        | 28        | 0.64%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 28        | 0.64%   |
| Seagate ST9500325AS 500GB                           | 25        | 0.57%   |
| SanDisk SSD PLUS 240GB                              | 23        | 0.53%   |
| Samsung SSD 860 EVO 250GB                           | 23        | 0.53%   |
| Toshiba MQ04ABF100 1TB                              | 22        | 0.5%    |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 22        | 0.5%    |
| SanDisk NVMe SSD Drive 256GB                        | 20        | 0.46%   |
| Samsung SSD 860 EVO 1TB                             | 20        | 0.46%   |
| SK hynix NVMe SSD Drive 512GB                       | 19        | 0.43%   |
| Crucial CT480BX500SSD1 480GB                        | 19        | 0.43%   |
| Crucial CT1000MX500SSD1 1TB                         | 19        | 0.43%   |
| Seagate M3 Portable 4TB                             | 18        | 0.41%   |
| WDC WD5000LPVX-22V0TT0 500GB                        | 17        | 0.39%   |
| Kingston SA400S37120G 120GB SSD                     | 17        | 0.39%   |
| Hitachi HTS545050A7E380 500GB                       | 17        | 0.39%   |
| Samsung SSD 840 EVO 250GB                           | 16        | 0.37%   |
| Kingston SV300S37A120G 120GB SSD                    | 16        | 0.37%   |
| Hitachi HTS545050B9A300 500GB                       | 16        | 0.37%   |
| HGST HTS541010A9E680 1TB                            | 16        | 0.37%   |
| Toshiba NVMe SSD Drive 512GB                        | 15        | 0.34%   |
| Seagate ST9320325AS 320GB                           | 15        | 0.34%   |
| Samsung MZVLQ512HALU-000H1 512GB                    | 15        | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 392       | 465    | 28.34%  |
| WDC                 | 310       | 378    | 22.42%  |
| Toshiba             | 208       | 245    | 15.04%  |
| Hitachi             | 206       | 246    | 14.9%   |
| HGST                | 155       | 196    | 11.21%  |
| Fujitsu             | 43        | 51     | 3.11%   |
| Samsung Electronics | 40        | 51     | 2.89%   |
| Unknown             | 16        | 17     | 1.16%   |
| ASMT                | 3         | 4      | 0.22%   |
| IBM/Hitachi         | 2         | 3      | 0.14%   |
| HGST HTS            | 2         | 2      | 0.14%   |
| USB3.0              | 1         | 1      | 0.07%   |
| StoreJet            | 1         | 1      | 0.07%   |
| Intenso             | 1         | 1      | 0.07%   |
| Generic-            | 1         | 1      | 0.07%   |
| DAS                 | 1         | 4      | 0.07%   |
| Apple               | 1         | 1      | 0.07%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 397       | 503    | 27.12%  |
| Crucial             | 222       | 255    | 15.16%  |
| Kingston            | 187       | 215    | 12.77%  |
| SanDisk             | 151       | 186    | 10.31%  |
| Micron Technology   | 51        | 65     | 3.48%   |
| WDC                 | 39        | 48     | 2.66%   |
| SK hynix            | 39        | 44     | 2.66%   |
| China               | 33        | 36     | 2.25%   |
| Toshiba             | 24        | 39     | 1.64%   |
| Transcend           | 20        | 24     | 1.37%   |
| Apple               | 20        | 21     | 1.37%   |
| SPCC                | 19        | 23     | 1.3%    |
| Intel               | 19        | 23     | 1.3%    |
| LITEON              | 17        | 19     | 1.16%   |
| Netac               | 15        | 16     | 1.02%   |
| KingDian            | 14        | 19     | 0.96%   |
| Intenso             | 14        | 14     | 0.96%   |
| Teclast             | 13        | 17     | 0.89%   |
| PNY                 | 10        | 11     | 0.68%   |
| JMicron Technology  | 10        | 11     | 0.68%   |
| Drevo               | 10        | 11     | 0.68%   |
| A-DATA Technology   | 10        | 11     | 0.68%   |
| LITEONIT            | 9         | 19     | 0.61%   |
| Corsair             | 8         | 9      | 0.55%   |
| Unknown             | 8         | 13     | 0.55%   |
| Patriot             | 7         | 10     | 0.48%   |
| Microtech           | 7         | 16     | 0.48%   |
| GOODRAM             | 6         | 7      | 0.41%   |
| Dogfish             | 6         | 7      | 0.41%   |
| TCSUNBOW            | 5         | 5      | 0.34%   |
| FORESEE             | 5         | 5      | 0.34%   |
| Verbatim            | 4         | 9      | 0.27%   |
| KingSpec            | 4         | 5      | 0.27%   |
| BAITITON            | 4         | 4      | 0.27%   |
| Team                | 3         | 3      | 0.2%    |
| Phison              | 3         | 4      | 0.2%    |
| OCZ                 | 3         | 3      | 0.2%    |
| Leven               | 3         | 3      | 0.2%    |
| Hewlett-Packard     | 3         | 4      | 0.2%    |
| Emtec               | 3         | 3      | 0.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 1386      | 1781   | 34.38%  |
| HDD     | 1340      | 1667   | 33.23%  |
| NVMe    | 993       | 1355   | 24.63%  |
| MMC     | 246       | 339    | 6.1%    |
| Unknown | 67        | 80     | 1.66%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2469      | 3364   | 64.11%  |
| NVMe | 984       | 1336   | 25.55%  |
| MMC  | 246       | 339    | 6.39%   |
| SAS  | 152       | 183    | 3.95%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2047      | 2671   | 76.72%  |
| 0.51-1.0   | 565       | 712    | 21.18%  |
| 1.01-2.0   | 37        | 43     | 1.39%   |
| 3.01-4.0   | 18        | 21     | 0.67%   |
| 4.01-10.0  | 1         | 1      | 0.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1103      | 30.55%  |
| 251-500        | 938       | 25.98%  |
| 501-1000       | 391       | 10.83%  |
| 1-20           | 341       | 9.44%   |
| 51-100         | 307       | 8.5%    |
| 21-50          | 192       | 5.32%   |
| 1001-2000      | 164       | 4.54%   |
| Unknown        | 74        | 2.05%   |
| 2001-3000      | 53        | 1.47%   |
| More than 3000 | 48        | 1.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1651      | 43.97%  |
| 21-50          | 598       | 15.93%  |
| 101-250        | 498       | 13.26%  |
| 51-100         | 465       | 12.38%  |
| 251-500        | 263       | 7%      |
| 501-1000       | 134       | 3.57%   |
| Unknown        | 74        | 1.97%   |
| 1001-2000      | 42        | 1.12%   |
| 2001-3000      | 16        | 0.43%   |
| More than 3000 | 14        | 0.37%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| HGST HTS545050A7E680 500GB                     | 10        | 11     | 4.76%   |
| Seagate ST9500325AS 500GB                      | 6         | 6      | 2.86%   |
| Seagate ST1000LM035-1RK172 1TB                 | 6         | 6      | 2.86%   |
| WDC WD3200BEVT-60A23T0 320GB                   | 5         | 5      | 2.38%   |
| Seagate ST500LT012-1DG142 500GB                | 5         | 5      | 2.38%   |
| Hitachi HTS725050A9A364 500GB                  | 5         | 5      | 2.38%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 4         | 4      | 1.9%    |
| Hitachi HTS545050A7E380 500GB                  | 4         | 4      | 1.9%    |
| HGST HTS725050A7E630 500GB                     | 4         | 4      | 1.9%    |
| Toshiba MQ01ABF050 500GB                       | 3         | 3      | 1.43%   |
| SK hynix HFS512G39TND-N210A 512GB SSD          | 3         | 3      | 1.43%   |
| Seagate ST500LT012-9WS142 500GB                | 3         | 3      | 1.43%   |
| Hitachi HTS547550A9E384 500GB                  | 3         | 3      | 1.43%   |
| HGST HTS721010A9E630 1TB                       | 3         | 3      | 1.43%   |
| WDC WD5000LPCX-24C6HT0 500GB                   | 2         | 2      | 0.95%   |
| WDC WD5000BEVT-22ZAT0 500GB                    | 2         | 2      | 0.95%   |
| WDC WD10JPVX-22JC3T0 1TB                       | 2         | 3      | 0.95%   |
| Toshiba MQ01ABD100 1TB                         | 2         | 2      | 0.95%   |
| Toshiba MK5065GSX 500GB                        | 2         | 2      | 0.95%   |
| SK hynix HFS128G39TND-N210A 128GB SSD          | 2         | 2      | 0.95%   |
| Seagate ST9320423AS 320GB                      | 2         | 2      | 0.95%   |
| Seagate ST9320325AS 320GB                      | 2         | 2      | 0.95%   |
| Seagate ST9250315AS 250GB                      | 2         | 2      | 0.95%   |
| Seagate ST9160310AS 160GB                      | 2         | 3      | 0.95%   |
| Seagate ST500LM021-1KJ152 500GB                | 2         | 2      | 0.95%   |
| Seagate ST320LT020-9YG142 320GB                | 2         | 2      | 0.95%   |
| Seagate ST1000LM014-1EJ164 1TB                 | 2         | 2      | 0.95%   |
| Micron Technology 1100_MTFDDAV512TBN 512GB SSD | 2         | 2      | 0.95%   |
| Hitachi HTS543232A7A384 320GB                  | 2         | 3      | 0.95%   |
| Hitachi HTS543225L9A300 250GB                  | 2         | 2      | 0.95%   |
| Hitachi HTS542516K9SA00 160GB                  | 2         | 2      | 0.95%   |
| HGST HTS541075A9E680 752GB                     | 2         | 2      | 0.95%   |
| HGST HTS541010A9E680 1TB                       | 2         | 2      | 0.95%   |
| Crucial CT525MX300SSD1 528GB                   | 2         | 2      | 0.95%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD               | 1         | 1      | 0.48%   |
| WDC WDS2 40G2G0A-00JH30 240GB SSD              | 1         | 1      | 0.48%   |
| WDC WD7500BPVT-80HXZT3 752GB                   | 1         | 2      | 0.48%   |
| WDC WD7500BPVT-80HXZT1 752GB                   | 1         | 1      | 0.48%   |
| WDC WD5000LPVX-22V0TT0 500GB                   | 1         | 1      | 0.48%   |
| WDC WD5000LPLX-00ZNTT0 500GB                   | 1         | 1      | 0.48%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 45        | 46     | 21.43%  |
| Hitachi             | 38        | 39     | 18.1%   |
| WDC                 | 27        | 31     | 12.86%  |
| Toshiba             | 25        | 25     | 11.9%   |
| HGST                | 22        | 23     | 10.48%  |
| Samsung Electronics | 8         | 8      | 3.81%   |
| SK hynix            | 7         | 8      | 3.33%   |
| Crucial             | 7         | 7      | 3.33%   |
| Micron Technology   | 6         | 6      | 2.86%   |
| Intel               | 4         | 6      | 1.9%    |
| Fujitsu             | 4         | 4      | 1.9%    |
| SanDisk             | 3         | 3      | 1.43%   |
| Kingston            | 3         | 3      | 1.43%   |
| Drevo               | 2         | 2      | 0.95%   |
| WDC WDS2            | 1         | 1      | 0.48%   |
| Unknown             | 1         | 1      | 0.48%   |
| Transcend           | 1         | 2      | 0.48%   |
| TCSUNBOW            | 1         | 1      | 0.48%   |
| NGFF                | 1         | 1      | 0.48%   |
| LITEON              | 1         | 1      | 0.48%   |
| KingSpec            | 1         | 1      | 0.48%   |
| KingDian            | 1         | 1      | 0.48%   |
| BAITITON            | 1         | 1      | 0.48%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 45        | 46     | 27.61%  |
| Hitachi             | 38        | 39     | 23.31%  |
| WDC                 | 26        | 30     | 15.95%  |
| Toshiba             | 24        | 24     | 14.72%  |
| HGST                | 22        | 23     | 13.5%   |
| Fujitsu             | 4         | 4      | 2.45%   |
| Samsung Electronics | 3         | 3      | 1.84%   |
| Unknown             | 1         | 1      | 0.61%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 162       | 170    | 77.51%  |
| SSD  | 42        | 43     | 20.1%   |
| NVMe | 5         | 8      | 2.39%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                | Notebooks | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-26A0RT0 500GB         | 1         | 1      | 12.5%   |
| WDC WD5000BEVT-22A0RT0 500GB         | 1         | 1      | 12.5%   |
| WDC WD10JPVX-60JC3T0 1TB             | 1         | 1      | 12.5%   |
| WDC PC SN520 SDAPNUW-256G-1102 256GB | 1         | 1      | 12.5%   |
| Toshiba MK3265GSX 320GB              | 1         | 1      | 12.5%   |
| Seagate ST9500420AS 500GB            | 1         | 3      | 12.5%   |
| Seagate ST2000LX001-1RG174 2TB       | 1         | 1      | 12.5%   |
| Hitachi HTS545050A7E380 500GB        | 1         | 1      | 12.5%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 4      | 50%     |
| Seagate | 2         | 4      | 25%     |
| Toshiba | 1         | 1      | 12.5%   |
| Hitachi | 1         | 1      | 12.5%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2094      | 3167   | 57.34%  |
| Works    | 1341      | 1824   | 36.72%  |
| Malfunc  | 209       | 221    | 5.72%   |
| Failed   | 8         | 10     | 0.22%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2461      | 62.51%  |
| AMD                              | 399       | 10.13%  |
| Samsung Electronics              | 349       | 8.86%   |
| SanDisk                          | 174       | 4.42%   |
| SK hynix                         | 109       | 2.77%   |
| Toshiba America Info Systems     | 69        | 1.75%   |
| Micron Technology                | 58        | 1.47%   |
| Kingston Technology Company      | 56        | 1.42%   |
| KIOXIA                           | 51        | 1.3%    |
| Nvidia                           | 44        | 1.12%   |
| Phison Electronics               | 42        | 1.07%   |
| Silicon Integrated Systems [SiS] | 24        | 0.61%   |
| Micron/Crucial Technology        | 21        | 0.53%   |
| Union Memory (Shenzhen)          | 10        | 0.25%   |
| Solid State Storage Technology   | 9         | 0.23%   |
| Silicon Motion                   | 9         | 0.23%   |
| VIA Technologies                 | 7         | 0.18%   |
| Lenovo                           | 7         | 0.18%   |
| Apple                            | 7         | 0.18%   |
| Lite-On Technology               | 6         | 0.15%   |
| ADATA Technology                 | 5         | 0.13%   |
| Silicon Image                    | 3         | 0.08%   |
| Seagate Technology               | 3         | 0.08%   |
| ASMedia Technology               | 3         | 0.08%   |
| Yangtze Memory Technologies      | 2         | 0.05%   |
| Shenzhen Longsys Electronics     | 2         | 0.05%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.05%   |
| JMicron Technology               | 2         | 0.05%   |
| Realtek Semiconductor            | 1         | 0.03%   |
| O2 Micro                         | 1         | 0.03%   |
| Marvell Technology Group         | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 322       | 7.54%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 288       | 6.74%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 231       | 5.41%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 207       | 4.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 196       | 4.59%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 186       | 4.36%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 168       | 3.93%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 136       | 3.19%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 116       | 2.72%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 102       | 2.39%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 99        | 2.32%   |
| Samsung NVMe SSD Controller 980                                                  | 91        | 2.13%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 90        | 2.11%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 84        | 1.97%   |
| Intel Volume Management Device NVMe RAID Controller                              | 77        | 1.8%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 76        | 1.78%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 72        | 1.69%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 67        | 1.57%   |
| Micron Non-Volatile memory controller                                            | 58        | 1.36%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 48        | 1.12%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 48        | 1.12%   |
| Intel Comet Lake SATA AHCI Controller                                            | 47        | 1.1%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 46        | 1.08%   |
| Intel SSD 660P Series                                                            | 45        | 1.05%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 44        | 1.03%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 41        | 0.96%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 40        | 0.94%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 38        | 0.89%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 38        | 0.89%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 37        | 0.87%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 36        | 0.84%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 36        | 0.84%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 33        | 0.77%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 33        | 0.77%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 31        | 0.73%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 31        | 0.73%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 30        | 0.7%    |
| SanDisk Non-Volatile memory controller                                           | 29        | 0.68%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 29        | 0.68%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 26        | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 2455      | 59.75%  |
| NVMe | 991       | 24.12%  |
| IDE  | 372       | 9.05%   |
| RAID | 291       | 7.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 2861      | 83.07%  |
| AMD          | 579       | 16.81%  |
| CentaurHauls | 2         | 0.06%   |
| ARM          | 1         | 0.03%   |
| Unknown      | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 74        | 2.15%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 58        | 1.68%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 52        | 1.51%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 52        | 1.51%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 50        | 1.45%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 46        | 1.34%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 44        | 1.28%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 43        | 1.25%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 43        | 1.25%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 41        | 1.19%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 37        | 1.07%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 36        | 1.04%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 36        | 1.04%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 36        | 1.04%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 34        | 0.99%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 33        | 0.96%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 33        | 0.96%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 29        | 0.84%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 28        | 0.81%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 26        | 0.75%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 26        | 0.75%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 26        | 0.75%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 25        | 0.73%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 25        | 0.73%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 24        | 0.7%    |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 24        | 0.7%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 24        | 0.7%    |
| Intel Celeron N4020 CPU @ 1.10GHz             | 22        | 0.64%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 21        | 0.61%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 21        | 0.61%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 20        | 0.58%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 20        | 0.58%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 20        | 0.58%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 20        | 0.58%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 20        | 0.58%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 20        | 0.58%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 20        | 0.58%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 20        | 0.58%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 19        | 0.55%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 19        | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 868       | 25.2%   |
| Intel Core i5           | 671       | 19.48%  |
| Intel Core 2 Duo        | 256       | 7.43%   |
| Intel Core i3           | 252       | 7.31%   |
| Intel Celeron           | 215       | 6.24%   |
| Other                   | 199       | 5.78%   |
| Intel Atom              | 148       | 4.3%    |
| AMD Ryzen 5             | 119       | 3.45%   |
| AMD Ryzen 7             | 108       | 3.13%   |
| Intel Pentium           | 44        | 1.28%   |
| AMD E1                  | 39        | 1.13%   |
| Intel Pentium Dual-Core | 37        | 1.07%   |
| Intel Pentium Dual      | 35        | 1.02%   |
| Intel Genuine           | 35        | 1.02%   |
| Intel Core 2            | 31        | 0.9%    |
| AMD A4                  | 30        | 0.87%   |
| AMD A8                  | 29        | 0.84%   |
| AMD A6                  | 26        | 0.75%   |
| AMD A10                 | 25        | 0.73%   |
| AMD Ryzen 3             | 21        | 0.61%   |
| AMD E2                  | 21        | 0.61%   |
| AMD Ryzen 9             | 18        | 0.52%   |
| Intel Core i9           | 17        | 0.49%   |
| Intel Pentium M         | 16        | 0.46%   |
| AMD Turion 64 X2 Mobile | 15        | 0.44%   |
| Intel Pentium Silver    | 14        | 0.41%   |
| Intel Celeron M         | 13        | 0.38%   |
| AMD Sempron             | 12        | 0.35%   |
| AMD Ryzen 7 PRO         | 12        | 0.35%   |
| AMD Ryzen 5 PRO         | 10        | 0.29%   |
| AMD Mobile Sempron      | 9         | 0.26%   |
| AMD E                   | 8         | 0.23%   |
| Intel Core m3           | 7         | 0.2%    |
| Intel Celeron Dual-Core | 7         | 0.2%    |
| Intel Core M            | 5         | 0.15%   |
| AMD Athlon II           | 5         | 0.15%   |
| AMD A12                 | 5         | 0.15%   |
| AMD Turion 64 Mobile    | 4         | 0.12%   |
| AMD Athlon X2           | 4         | 0.12%   |
| AMD Athlon              | 4         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1791      | 51.96%  |
| 4       | 1120      | 32.49%  |
| 6       | 185       | 5.37%   |
| 1       | 162       | 4.7%    |
| 8       | 155       | 4.5%    |
| 14      | 22        | 0.64%   |
| 12      | 5         | 0.15%   |
| 10      | 4         | 0.12%   |
| 16      | 1         | 0.03%   |
| 5       | 1         | 0.03%   |
| Unknown | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3444      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 2363      | 68.49%  |
| 1       | 1086      | 31.48%  |
| Unknown | 1         | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3324      | 96.38%  |
| 32-bit         | 97        | 2.81%   |
| Unknown        | 28        | 0.81%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 655       | 18.46%  |
| 0x206a7    | 196       | 5.52%   |
| 0x306a9    | 189       | 5.33%   |
| 0x1067a    | 130       | 3.66%   |
| 0x806ea    | 125       | 3.52%   |
| 0x40651    | 124       | 3.49%   |
| 0x806ec    | 114       | 3.21%   |
| 0x406e3    | 111       | 3.13%   |
| 0x806c1    | 99        | 2.79%   |
| 0x806e9    | 92        | 2.59%   |
| 0x6fd      | 90        | 2.54%   |
| 0x20655    | 88        | 2.48%   |
| 0x906ea    | 83        | 2.34%   |
| 0x306d4    | 77        | 2.17%   |
| 0x306c3    | 77        | 2.17%   |
| 0x10676    | 68        | 1.92%   |
| 0x08108109 | 60        | 1.69%   |
| 0x706e5    | 52        | 1.47%   |
| 0x806eb    | 46        | 1.3%    |
| 0x406c3    | 45        | 1.27%   |
| 0x906e9    | 43        | 1.21%   |
| 0x30678    | 42        | 1.18%   |
| 0x20652    | 41        | 1.16%   |
| 0xa0652    | 40        | 1.13%   |
| 0x06006705 | 40        | 1.13%   |
| 0x106ca    | 38        | 1.07%   |
| 0x406c4    | 36        | 1.01%   |
| 0x08608103 | 36        | 1.01%   |
| 0x706a8    | 35        | 0.99%   |
| 0x706a1    | 34        | 0.96%   |
| 0x506c9    | 30        | 0.85%   |
| 0x0a50000c | 30        | 0.85%   |
| 0x07030105 | 29        | 0.82%   |
| 0x506e3    | 28        | 0.79%   |
| 0x106c2    | 25        | 0.7%    |
| 0x08600106 | 25        | 0.7%    |
| 0x08108102 | 25        | 0.7%    |
| 0x6e8      | 23        | 0.65%   |
| 0x6f6      | 22        | 0.62%   |
| 0x08600104 | 22        | 0.62%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 616       | 17.87%  |
| Haswell          | 258       | 7.48%   |
| IvyBridge        | 231       | 6.7%    |
| Penryn           | 230       | 6.67%   |
| SandyBridge      | 226       | 6.56%   |
| Core             | 177       | 5.13%   |
| Skylake          | 174       | 5.05%   |
| Westmere         | 147       | 4.26%   |
| Silvermont       | 146       | 4.24%   |
| TigerLake        | 124       | 3.6%    |
| Zen+             | 98        | 2.84%   |
| Broadwell        | 91        | 2.64%   |
| Unknown          | 88        | 2.55%   |
| Excavator        | 82        | 2.38%   |
| Goldmont plus    | 79        | 2.29%   |
| Bonnell          | 78        | 2.26%   |
| IceLake          | 74        | 2.15%   |
| Zen 2            | 66        | 1.91%   |
| P6               | 57        | 1.65%   |
| CometLake        | 54        | 1.57%   |
| Zen 3            | 46        | 1.33%   |
| Puma             | 38        | 1.1%    |
| K8 Hammer        | 38        | 1.1%    |
| Goldmont         | 36        | 1.04%   |
| Jaguar           | 35        | 1.02%   |
| Bobcat           | 25        | 0.73%   |
| Alderlake Hybrid | 21        | 0.61%   |
| Zen              | 20        | 0.58%   |
| Nehalem          | 19        | 0.55%   |
| K10              | 19        | 0.55%   |
| K8 & K10 hybrid  | 16        | 0.46%   |
| K10 Llano        | 13        | 0.38%   |
| Steamroller      | 10        | 0.29%   |
| Piledriver       | 9         | 0.26%   |
| Tremont          | 3         | 0.09%   |
| NetBurst         | 3         | 0.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2497      | 56.83%  |
| Nvidia                           | 1021      | 23.24%  |
| AMD                              | 856       | 19.48%  |
| Silicon Integrated Systems [SiS] | 14        | 0.32%   |
| VIA Technologies                 | 5         | 0.11%   |
| S3 Graphics                      | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 220       | 4.77%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 197       | 4.27%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 150       | 3.25%   |
| Intel UHD Graphics 620                                                                   | 148       | 3.21%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 128       | 2.78%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 122       | 2.65%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 116       | 2.52%   |
| Intel HD Graphics 620                                                                    | 103       | 2.23%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 101       | 2.19%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 99        | 2.15%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 98        | 2.12%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 93        | 2.02%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 92        | 1.99%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 91        | 1.97%   |
| Intel Core Processor Integrated Graphics Controller                                      | 87        | 1.89%   |
| Intel HD Graphics 5500                                                                   | 78        | 1.69%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 70        | 1.52%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 70        | 1.52%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 65        | 1.41%   |
| AMD Renoir                                                                               | 64        | 1.39%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 63        | 1.37%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 59        | 1.28%   |
| AMD Lucienne                                                                             | 56        | 1.21%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 54        | 1.17%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 53        | 1.15%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 53        | 1.15%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 48        | 1.04%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 45        | 0.98%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 42        | 0.91%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 42        | 0.91%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 41        | 0.89%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 40        | 0.87%   |
| Nvidia GP108M [GeForce MX150]                                                            | 39        | 0.85%   |
| Intel HD Graphics 630                                                                    | 39        | 0.85%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 39        | 0.85%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 38        | 0.82%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 33        | 0.72%   |
| Intel HD Graphics 530                                                                    | 33        | 0.72%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 32        | 0.69%   |
| Nvidia GM108M [GeForce MX130]                                                            | 30        | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 1584      | 45.93%  |
| Intel + Nvidia  | 752       | 21.8%   |
| 1 x AMD         | 579       | 16.79%  |
| 1 x Nvidia      | 224       | 6.49%   |
| Intel + AMD     | 155       | 4.49%   |
| 2 x AMD         | 80        | 2.32%   |
| AMD + Nvidia    | 43        | 1.25%   |
| 1 x SiS         | 14        | 0.41%   |
| Other           | 5         | 0.14%   |
| 1 x VIA         | 5         | 0.14%   |
| 2 x Nvidia      | 4         | 0.12%   |
| 2 x Intel       | 3         | 0.09%   |
| 1 x S3 Graphics | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2928      | 84.09%  |
| Proprietary | 461       | 13.24%  |
| Unknown     | 93        | 2.67%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2090      | 59.24%  |
| 0.01-0.5   | 509       | 14.43%  |
| 1.01-2.0   | 476       | 13.49%  |
| 0.51-1.0   | 242       | 6.86%   |
| 3.01-4.0   | 151       | 4.28%   |
| 5.01-6.0   | 33        | 0.94%   |
| 7.01-8.0   | 16        | 0.45%   |
| 2.01-3.0   | 9         | 0.26%   |
| 8.01-16.0  | 2         | 0.06%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 739       | 19.66%  |
| Chimei Innolux          | 531       | 14.13%  |
| LG Display              | 506       | 13.46%  |
| BOE                     | 476       | 12.66%  |
| Samsung Electronics     | 436       | 11.6%   |
| Chi Mei Optoelectronics | 121       | 3.22%   |
| Sharp                   | 91        | 2.42%   |
| Apple                   | 80        | 2.13%   |
| Goldstar                | 65        | 1.73%   |
| Philips                 | 60        | 1.6%    |
| LG Philips              | 60        | 1.6%    |
| Hewlett-Packard         | 58        | 1.54%   |
| Lenovo                  | 50        | 1.33%   |
| PANDA                   | 47        | 1.25%   |
| Dell                    | 44        | 1.17%   |
| Ancor Communications    | 42        | 1.12%   |
| Acer                    | 32        | 0.85%   |
| HannStar                | 31        | 0.82%   |
| BenQ                    | 28        | 0.74%   |
| Sony                    | 25        | 0.67%   |
| InfoVision              | 25        | 0.67%   |
| CPT                     | 20        | 0.53%   |
| AOC                     | 19        | 0.51%   |
| CSO                     | 18        | 0.48%   |
| Toshiba                 | 13        | 0.35%   |
| Quanta Display          | 13        | 0.35%   |
| LGD                     | 13        | 0.35%   |
| Seiko/Epson             | 8         | 0.21%   |
| ASUSTek Computer        | 8         | 0.21%   |
| TMX                     | 7         | 0.19%   |
| MSI                     | 7         | 0.19%   |
| Vestel Elektronik       | 5         | 0.13%   |
| InnoLux Display         | 5         | 0.13%   |
| Nvidia                  | 4         | 0.11%   |
| Eizo                    | 4         | 0.11%   |
| Tianma XM               | 3         | 0.08%   |
| Panasonic               | 3         | 0.08%   |
| LPL                     | 3         | 0.08%   |
| Iiyama                  | 3         | 0.08%   |
| Hitachi                 | 3         | 0.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 59        | 1.56%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 35        | 0.92%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 33        | 0.87%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 31        | 0.82%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 27        | 0.71%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 26        | 0.69%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 26        | 0.69%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 26        | 0.69%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 25        | 0.66%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 25        | 0.66%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 24        | 0.63%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 23        | 0.61%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 23        | 0.61%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 21        | 0.55%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 21        | 0.55%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 20        | 0.53%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 20        | 0.53%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 18        | 0.47%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 18        | 0.47%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 16        | 0.42%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 15        | 0.4%    |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 14        | 0.37%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 14        | 0.37%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 14        | 0.37%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 14        | 0.37%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch     | 13        | 0.34%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch              | 13        | 0.34%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                 | 13        | 0.34%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 13        | 0.34%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 13        | 0.34%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch     | 12        | 0.32%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 12        | 0.32%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch        | 11        | 0.29%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 11        | 0.29%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 11        | 0.29%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch          | 11        | 0.29%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                    | 11        | 0.29%   |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch                    | 11        | 0.29%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch            | 11        | 0.29%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 11        | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1382      | 38.74%  |
| 1366x768 (WXGA)    | 1230      | 34.48%  |
| 1280x800 (WXGA)    | 264       | 7.4%    |
| 1600x900 (HD+)     | 124       | 3.48%   |
| 3840x2160 (4K)     | 107       | 3%      |
| 1440x900 (WXGA+)   | 63        | 1.77%   |
| 2560x1440 (QHD)    | 57        | 1.6%    |
| 1024x600           | 55        | 1.54%   |
| 1920x1200 (WUXGA)  | 52        | 1.46%   |
| 1680x1050 (WSXGA+) | 30        | 0.84%   |
| 2560x1600          | 27        | 0.76%   |
| 2160x1440          | 26        | 0.73%   |
| 1280x1024 (SXGA)   | 22        | 0.62%   |
| 2880x1800          | 19        | 0.53%   |
| 3840x2400          | 12        | 0.34%   |
| 1360x768           | 12        | 0.34%   |
| 2560x1080          | 9         | 0.25%   |
| 3440x1440          | 7         | 0.2%    |
| 3200x1800 (QHD+)   | 7         | 0.2%    |
| 1024x768 (XGA)     | 7         | 0.2%    |
| 3000x2000          | 6         | 0.17%   |
| 3072x1920          | 5         | 0.14%   |
| 1920x1280          | 4         | 0.11%   |
| 800x1280           | 3         | 0.08%   |
| 2520x1680          | 3         | 0.08%   |
| 1400x1050          | 3         | 0.08%   |
| Unknown            | 3         | 0.08%   |
| 3840x1600          | 2         | 0.06%   |
| 3840x1080          | 2         | 0.06%   |
| 3456x2160          | 2         | 0.06%   |
| 2240x1400          | 2         | 0.06%   |
| 1920x540           | 2         | 0.06%   |
| 1600x1200          | 2         | 0.06%   |
| 1280x960           | 2         | 0.06%   |
| 1280x720 (HD)      | 2         | 0.06%   |
| 3200x2000          | 1         | 0.03%   |
| 2880x1920          | 1         | 0.03%   |
| 2880x1620          | 1         | 0.03%   |
| 2736x1824          | 1         | 0.03%   |
| 2732x768           | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1948      | 51.85%  |
| 13      | 451       | 12%     |
| 14      | 322       | 8.57%   |
| 17      | 179       | 4.76%   |
| 24      | 115       | 3.06%   |
| 27      | 109       | 2.9%    |
| 12      | 97        | 2.58%   |
| 23      | 86        | 2.29%   |
| 21      | 66        | 1.76%   |
| 11      | 59        | 1.57%   |
| 10      | 59        | 1.57%   |
| Unknown | 58        | 1.54%   |
| 16      | 35        | 0.93%   |
| 19      | 25        | 0.67%   |
| 18      | 25        | 0.67%   |
| 22      | 16        | 0.43%   |
| 31      | 12        | 0.32%   |
| 34      | 11        | 0.29%   |
| 20      | 11        | 0.29%   |
| 84      | 10        | 0.27%   |
| 54      | 8         | 0.21%   |
| 25      | 7         | 0.19%   |
| 32      | 6         | 0.16%   |
| 8       | 6         | 0.16%   |
| 72      | 5         | 0.13%   |
| 65      | 3         | 0.08%   |
| 40      | 3         | 0.08%   |
| 26      | 3         | 0.08%   |
| 58      | 2         | 0.05%   |
| 52      | 2         | 0.05%   |
| 48      | 2         | 0.05%   |
| 47      | 2         | 0.05%   |
| 46      | 2         | 0.05%   |
| 37      | 2         | 0.05%   |
| 35      | 2         | 0.05%   |
| 142     | 1         | 0.03%   |
| 49      | 1         | 0.03%   |
| 42      | 1         | 0.03%   |
| 39      | 1         | 0.03%   |
| 30      | 1         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 2460      | 65.92%  |
| 201-300        | 462       | 12.38%  |
| 501-600        | 292       | 7.82%   |
| 351-400        | 234       | 6.27%   |
| 401-500        | 129       | 3.46%   |
| Unknown        | 58        | 1.55%   |
| 601-700        | 27        | 0.72%   |
| 1001-1500      | 21        | 0.56%   |
| 701-800        | 17        | 0.46%   |
| 1501-2000      | 15        | 0.4%    |
| 801-900        | 8         | 0.21%   |
| 101-200        | 7         | 0.19%   |
| More than 2000 | 1         | 0.03%   |
| 901-1000       | 1         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 2767      | 81.69%  |
| 16/10   | 465       | 13.73%  |
| 3/2     | 47        | 1.39%   |
| Unknown | 43        | 1.27%   |
| 5/4     | 23        | 0.68%   |
| 21/9    | 17        | 0.5%    |
| 4/3     | 16        | 0.47%   |
| 0.62    | 3         | 0.09%   |
| 6/5     | 2         | 0.06%   |
| 32/9    | 2         | 0.06%   |
| 2.21    | 1         | 0.03%   |
| 1.00    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1948      | 51.99%  |
| 81-90          | 584       | 15.59%  |
| 201-250        | 237       | 6.33%   |
| 71-80          | 186       | 4.96%   |
| 121-130        | 139       | 3.71%   |
| 301-350        | 112       | 2.99%   |
| 61-70          | 94        | 2.51%   |
| 41-50          | 60        | 1.6%    |
| 51-60          | 59        | 1.57%   |
| Unknown        | 58        | 1.55%   |
| 151-200        | 48        | 1.28%   |
| 251-300        | 39        | 1.04%   |
| 141-150        | 35        | 0.93%   |
| 351-500        | 32        | 0.85%   |
| More than 1000 | 31        | 0.83%   |
| 131-140        | 27        | 0.72%   |
| 111-120        | 26        | 0.69%   |
| 91-100         | 14        | 0.37%   |
| 501-1000       | 12        | 0.32%   |
| 1-40           | 6         | 0.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1335      | 36.15%  |
| 101-120       | 1225      | 33.17%  |
| 51-100        | 742       | 20.09%  |
| 161-240       | 225       | 6.09%   |
| More than 240 | 82        | 2.22%   |
| Unknown       | 58        | 1.57%   |
| 1-50          | 26        | 0.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2903      | 82.38%  |
| 2     | 475       | 13.48%  |
| 0     | 105       | 2.98%   |
| 3     | 38        | 1.08%   |
| 4     | 3         | 0.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1850      | 33.31%  |
| Intel                             | 1628      | 29.31%  |
| Qualcomm Atheros                  | 884       | 15.92%  |
| Broadcom                          | 425       | 7.65%   |
| Marvell Technology Group          | 114       | 2.05%   |
| Broadcom Limited                  | 94        | 1.69%   |
| Ralink                            | 62        | 1.12%   |
| MediaTek                          | 56        | 1.01%   |
| TP-Link                           | 47        | 0.85%   |
| Ralink Technology                 | 42        | 0.76%   |
| Nvidia                            | 30        | 0.54%   |
| ASIX Electronics                  | 24        | 0.43%   |
| Dell                              | 23        | 0.41%   |
| Huawei Technologies               | 20        | 0.36%   |
| Silicon Integrated Systems [SiS]  | 17        | 0.31%   |
| Samsung Electronics               | 17        | 0.31%   |
| Ericsson Business Mobile Networks | 16        | 0.29%   |
| Attansic Technology               | 16        | 0.29%   |
| Sierra Wireless                   | 15        | 0.27%   |
| JMicron Technology                | 15        | 0.27%   |
| Xiaomi                            | 12        | 0.22%   |
| Qualcomm Atheros Communications   | 12        | 0.22%   |
| Hewlett-Packard                   | 11        | 0.2%    |
| Sitecom Europe                    | 8         | 0.14%   |
| Qualcomm                          | 7         | 0.13%   |
| Lenovo                            | 7         | 0.13%   |
| Apple                             | 7         | 0.13%   |
| DisplayLink                       | 6         | 0.11%   |
| D-Link System                     | 6         | 0.11%   |
| AMD                               | 6         | 0.11%   |
| ZTE WCDMA Technologies MSM        | 5         | 0.09%   |
| T & A Mobile Phones               | 5         | 0.09%   |
| OnePlus Technology (Shenzhen)     | 5         | 0.09%   |
| Fibocom                           | 5         | 0.09%   |
| NetGear                           | 4         | 0.07%   |
| ICS Advent                        | 4         | 0.07%   |
| D-Link                            | 4         | 0.07%   |
| ZyDAS                             | 3         | 0.05%   |
| VIA Technologies                  | 3         | 0.05%   |
| Motorola PCS                      | 3         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 1113      | 17.05%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 358       | 5.49%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 166       | 2.54%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 153       | 2.34%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 151       | 2.31%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 132       | 2.02%   |
| Intel Wireless 8265 / 8275                                              | 130       | 1.99%   |
| Intel Wi-Fi 6 AX200                                                     | 119       | 1.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 114       | 1.75%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 108       | 1.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 106       | 1.62%   |
| Intel Wireless 7265                                                     | 100       | 1.53%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 96        | 1.47%   |
| Intel Wireless 3165                                                     | 94        | 1.44%   |
| Intel Wi-Fi 6 AX201                                                     | 84        | 1.29%   |
| Intel Wireless 7260                                                     | 82        | 1.26%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 75        | 1.15%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 74        | 1.13%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 72        | 1.1%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 70        | 1.07%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 69        | 1.06%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 68        | 1.04%   |
| Intel WiFi Link 5100                                                    | 65        | 1%      |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 59        | 0.9%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 58        | 0.89%   |
| Intel Wireless 8260                                                     | 56        | 0.86%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 54        | 0.83%   |
| Broadcom BCM43142 802.11b/g/n                                           | 54        | 0.83%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 44        | 0.67%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 40        | 0.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 40        | 0.61%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 39        | 0.6%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 34        | 0.52%   |
| Intel Centrino Advanced-N 6200                                          | 34        | 0.52%   |
| Intel Ethernet Connection I218-LM                                       | 33        | 0.51%   |
| Intel Ethernet Connection (4) I219-LM                                   | 32        | 0.49%   |
| Intel 82577LM Gigabit Network Connection                                | 32        | 0.49%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 31        | 0.48%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 31        | 0.48%   |
| Intel 82567LM Gigabit Network Connection                                | 30        | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1565      | 44.01%  |
| Qualcomm Atheros                      | 801       | 22.53%  |
| Realtek Semiconductor                 | 536       | 15.07%  |
| Broadcom                              | 306       | 8.61%   |
| Broadcom Limited                      | 63        | 1.77%   |
| Ralink                                | 62        | 1.74%   |
| MediaTek                              | 54        | 1.52%   |
| Ralink Technology                     | 42        | 1.18%   |
| TP-Link                               | 39        | 1.1%    |
| Sierra Wireless                       | 15        | 0.42%   |
| Dell                                  | 14        | 0.39%   |
| Qualcomm Atheros Communications       | 12        | 0.34%   |
| Sitecom Europe                        | 7         | 0.2%    |
| D-Link System                         | 6         | 0.17%   |
| Fibocom                               | 5         | 0.14%   |
| NetGear                               | 4         | 0.11%   |
| ZyDAS                                 | 3         | 0.08%   |
| D-Link                                | 3         | 0.08%   |
| Belkin Components                     | 3         | 0.08%   |
| ASUSTek Computer                      | 3         | 0.08%   |
| U.S. Robotics                         | 2         | 0.06%   |
| Qualcomm                              | 2         | 0.06%   |
| Qcom                                  | 2         | 0.06%   |
| Microsoft                             | 2         | 0.06%   |
| Hewlett-Packard                       | 2         | 0.06%   |
| ZyXEL Communications                  | 1         | 0.03%   |
| AVM                                   | 1         | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 166       | 4.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 153       | 4.28%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 151       | 4.23%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 132       | 3.7%    |
| Intel Wireless 8265 / 8275                                              | 130       | 3.64%   |
| Intel Wi-Fi 6 AX200                                                     | 119       | 3.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 108       | 3.02%   |
| Intel Wireless 7265                                                     | 100       | 2.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 96        | 2.69%   |
| Intel Wireless 3165                                                     | 94        | 2.63%   |
| Intel Wi-Fi 6 AX201                                                     | 84        | 2.35%   |
| Intel Wireless 7260                                                     | 82        | 2.3%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 75        | 2.1%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 74        | 2.07%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 72        | 2.02%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 70        | 1.96%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 69        | 1.93%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 68        | 1.9%    |
| Intel WiFi Link 5100                                                    | 65        | 1.82%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 59        | 1.65%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 58        | 1.62%   |
| Intel Wireless 8260                                                     | 56        | 1.57%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 54        | 1.51%   |
| Broadcom BCM43142 802.11b/g/n                                           | 54        | 1.51%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 44        | 1.23%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 40        | 1.12%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 39        | 1.09%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 34        | 0.95%   |
| Intel Centrino Advanced-N 6200                                          | 34        | 0.95%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 31        | 0.87%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 31        | 0.87%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 29        | 0.81%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 29        | 0.81%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 28        | 0.78%   |
| Intel Centrino Wireless-N 2230                                          | 28        | 0.78%   |
| Intel Centrino Ultimate-N 6300                                          | 28        | 0.78%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 27        | 0.76%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 27        | 0.76%   |
| Intel Wireless-AC 9260                                                  | 26        | 0.73%   |
| Intel Wireless 3160                                                     | 26        | 0.73%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1655      | 57.77%  |
| Intel                            | 495       | 17.28%  |
| Qualcomm Atheros                 | 179       | 6.25%   |
| Broadcom                         | 172       | 6%      |
| Marvell Technology Group         | 114       | 3.98%   |
| Broadcom Limited                 | 32        | 1.12%   |
| Nvidia                           | 29        | 1.01%   |
| ASIX Electronics                 | 24        | 0.84%   |
| Samsung Electronics              | 16        | 0.56%   |
| Huawei Technologies              | 16        | 0.56%   |
| Attansic Technology              | 16        | 0.56%   |
| Silicon Integrated Systems [SiS] | 15        | 0.52%   |
| JMicron Technology               | 15        | 0.52%   |
| Xiaomi                           | 12        | 0.42%   |
| TP-Link                          | 8         | 0.28%   |
| Lenovo                           | 7         | 0.24%   |
| Apple                            | 7         | 0.24%   |
| DisplayLink                      | 6         | 0.21%   |
| ZTE WCDMA Technologies MSM       | 5         | 0.17%   |
| Qualcomm                         | 5         | 0.17%   |
| OnePlus Technology (Shenzhen)    | 5         | 0.17%   |
| T & A Mobile Phones              | 4         | 0.14%   |
| ICS Advent                       | 4         | 0.14%   |
| VIA Technologies                 | 3         | 0.1%    |
| Motorola PCS                     | 3         | 0.1%    |
| HMD Global                       | 3         | 0.1%    |
| Spreadtrum Communications        | 2         | 0.07%   |
| OPPO Electronics                 | 2         | 0.07%   |
| MediaTek                         | 2         | 0.07%   |
| LG Electronics                   | 2         | 0.07%   |
| Hewlett-Packard                  | 2         | 0.07%   |
| Sitecom Europe                   | 1         | 0.03%   |
| MosChip Semiconductor            | 1         | 0.03%   |
| Microchip Technology             | 1         | 0.03%   |
| D-Link                           | 1         | 0.03%   |
| Accton Technology                | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 1113      | 38.58%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 358       | 12.41%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 114       | 3.95%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 106       | 3.67%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 40        | 1.39%   |
| Intel Ethernet Connection I218-LM                                              | 33        | 1.14%   |
| Intel Ethernet Connection (4) I219-LM                                          | 32        | 1.11%   |
| Intel 82577LM Gigabit Network Connection                                       | 32        | 1.11%   |
| Intel 82567LM Gigabit Network Connection                                       | 30        | 1.04%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 30        | 1.04%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 30        | 1.04%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 28        | 0.97%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 26        | 0.9%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 25        | 0.87%   |
| Intel Ethernet Connection I217-LM                                              | 22        | 0.76%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 21        | 0.73%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 21        | 0.73%   |
| Intel Ethernet Connection I219-LM                                              | 21        | 0.73%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 20        | 0.69%   |
| Intel Ethernet Connection (3) I218-LM                                          | 20        | 0.69%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 20        | 0.69%   |
| Intel Ethernet Connection I219-V                                               | 18        | 0.62%   |
| Intel Ethernet Connection (4) I219-V                                           | 18        | 0.62%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 17        | 0.59%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 17        | 0.59%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 17        | 0.59%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 16        | 0.55%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 16        | 0.55%   |
| Nvidia MCP79 Ethernet                                                          | 15        | 0.52%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 15        | 0.52%   |
| Intel Ethernet Connection (6) I219-V                                           | 15        | 0.52%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 15        | 0.52%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 15        | 0.52%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 14        | 0.49%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 14        | 0.49%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 14        | 0.49%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 14        | 0.49%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 13        | 0.45%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 12        | 0.42%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 12        | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3377      | 54.34%  |
| Ethernet | 2769      | 44.55%  |
| Modem    | 63        | 1.01%   |
| Unknown  | 6         | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2836      | 79.46%  |
| Ethernet | 730       | 20.45%  |
| Unknown  | 2         | 0.06%   |
| Modem    | 1         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2548      | 73.86%  |
| 1     | 803       | 23.28%  |
| 0     | 78        | 2.26%   |
| 3     | 21        | 0.61%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3264      | 94.09%  |
| Yes  | 205       | 5.91%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1118      | 44.45%  |
| Realtek Semiconductor           | 304       | 12.09%  |
| Qualcomm Atheros Communications | 182       | 7.24%   |
| Lite-On Technology              | 145       | 5.77%   |
| IMC Networks                    | 141       | 5.61%   |
| Broadcom                        | 141       | 5.61%   |
| Foxconn / Hon Hai               | 114       | 4.53%   |
| Apple                           | 72        | 2.86%   |
| Hewlett-Packard                 | 58        | 2.31%   |
| Realtek                         | 48        | 1.91%   |
| Dell                            | 38        | 1.51%   |
| Cambridge Silicon Radio         | 36        | 1.43%   |
| Toshiba                         | 29        | 1.15%   |
| Ralink                          | 29        | 1.15%   |
| ASUSTek Computer                | 15        | 0.6%    |
| Alps Electric                   | 14        | 0.56%   |
| Ralink Technology               | 7         | 0.28%   |
| Foxconn International           | 5         | 0.2%    |
| MediaTek                        | 4         | 0.16%   |
| Askey Computer                  | 4         | 0.16%   |
| Chicony Electronics             | 3         | 0.12%   |
| Taiyo Yuden                     | 2         | 0.08%   |
| Integrated System Solution      | 2         | 0.08%   |
| Unknown                         | 1         | 0.04%   |
| Sitecom Europe                  | 1         | 0.04%   |
| Opticis                         | 1         | 0.04%   |
| Conwise Technology              | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 490       | 19.48%  |
| Realtek Bluetooth Radio                                                             | 194       | 7.71%   |
| Intel AX201 Bluetooth                                                               | 180       | 7.16%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 173       | 6.88%   |
| Intel AX200 Bluetooth                                                               | 114       | 4.53%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 88        | 3.5%    |
| Qualcomm Atheros  Bluetooth Device                                                  | 71        | 2.82%   |
| IMC Networks Bluetooth Device                                                       | 66        | 2.62%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 49        | 1.95%   |
| Realtek Bluetooth Radio                                                             | 48        | 1.91%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 45        | 1.79%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 41        | 1.63%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 39        | 1.55%   |
| Apple Bluetooth Host Controller                                                     | 38        | 1.51%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 36        | 1.43%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 34        | 1.35%   |
| Lite-On Bluetooth Device                                                            | 34        | 1.35%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 34        | 1.35%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 33        | 1.31%   |
| IMC Networks Bluetooth Radio                                                        | 32        | 1.27%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 31        | 1.23%   |
| Ralink RT3290 Bluetooth                                                             | 29        | 1.15%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 28        | 1.11%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 27        | 1.07%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 25        | 0.99%   |
| Broadcom BCM2045 Bluetooth                                                          | 24        | 0.95%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 22        | 0.87%   |
| Intel Bluetooth Device                                                              | 19        | 0.76%   |
| Intel AX210 Bluetooth                                                               | 18        | 0.72%   |
| Apple Bluetooth HCI                                                                 | 18        | 0.72%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 15        | 0.6%    |
| IMC Networks Wireless_Device                                                        | 15        | 0.6%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 15        | 0.6%    |
| Realtek RTL8723B Bluetooth                                                          | 14        | 0.56%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 14        | 0.56%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 14        | 0.56%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 14        | 0.56%   |
| Toshiba Integrated Bluetooth HCI                                                    | 13        | 0.52%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 13        | 0.52%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 13        | 0.52%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2737      | 67.76%  |
| AMD                              | 686       | 16.98%  |
| Nvidia                           | 398       | 9.85%   |
| Silicon Integrated Systems [SiS] | 24        | 0.59%   |
| C-Media Electronics              | 23        | 0.57%   |
| Logitech                         | 16        | 0.4%    |
| GN Netcom                        | 16        | 0.4%    |
| JMTek                            | 13        | 0.32%   |
| Realtek Semiconductor            | 11        | 0.27%   |
| Generalplus Technology           | 8         | 0.2%    |
| Lenovo                           | 7         | 0.17%   |
| VIA Technologies                 | 6         | 0.15%   |
| Texas Instruments                | 6         | 0.15%   |
| CMX Systems                      | 6         | 0.15%   |
| Apple                            | 5         | 0.12%   |
| Plantronics                      | 4         | 0.1%    |
| Huawei Technologies              | 4         | 0.1%    |
| Hewlett-Packard                  | 4         | 0.1%    |
| Fujitsu                          | 4         | 0.1%    |
| Creative Technology              | 4         | 0.1%    |
| BEHRINGER International          | 4         | 0.1%    |
| Sony                             | 3         | 0.07%   |
| Samson Technologies              | 3         | 0.07%   |
| M-Audio                          | 3         | 0.07%   |
| Syntek                           | 2         | 0.05%   |
| Razer USA                        | 2         | 0.05%   |
| Medeli Electronics               | 2         | 0.05%   |
| Focusrite-Novation               | 2         | 0.05%   |
| Dell                             | 2         | 0.05%   |
| Cambridge Silicon Radio          | 2         | 0.05%   |
| XMOS                             | 1         | 0.02%   |
| TEAC                             | 1         | 0.02%   |
| SmartlinkTechnology              | 1         | 0.02%   |
| Schiit Audio                     | 1         | 0.02%   |
| RODE Microphones                 | 1         | 0.02%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.02%   |
| Numark                           | 1         | 0.02%   |
| MosArt Semiconductor             | 1         | 0.02%   |
| Microsoft                        | 1         | 0.02%   |
| Micro Star International         | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 395       | 8.09%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 281       | 5.76%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 257       | 5.26%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 204       | 4.18%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 200       | 4.1%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 166       | 3.4%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 152       | 3.11%   |
| Intel 8 Series HD Audio Controller                                                                | 152       | 3.11%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 146       | 2.99%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 135       | 2.77%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 124       | 2.54%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 119       | 2.44%   |
| AMD FCH Azalia Controller                                                                         | 118       | 2.42%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 111       | 2.27%   |
| Intel Cannon Lake PCH cAVS                                                                        | 108       | 2.21%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 108       | 2.21%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 102       | 2.09%   |
| AMD Kabini HDMI/DP Audio                                                                          | 96        | 1.97%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 95        | 1.95%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 91        | 1.86%   |
| Intel Broadwell-U Audio Controller                                                                | 91        | 1.86%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 87        | 1.78%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 82        | 1.68%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 78        | 1.6%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 59        | 1.21%   |
| AMD High Definition Audio Controller                                                              | 59        | 1.21%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 52        | 1.07%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 51        | 1.04%   |
| Intel Comet Lake PCH cAVS                                                                         | 51        | 1.04%   |
| Intel CM238 HD Audio Controller                                                                   | 51        | 1.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 44        | 0.9%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 38        | 0.78%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 37        | 0.76%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 36        | 0.74%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 36        | 0.74%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 30        | 0.61%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 29        | 0.59%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 28        | 0.57%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 28        | 0.57%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 28        | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 646       | 29.62%  |
| SK hynix                     | 469       | 21.5%   |
| Micron Technology            | 271       | 12.43%  |
| Kingston                     | 196       | 8.99%   |
| Unknown                      | 194       | 8.9%    |
| Crucial                      | 97        | 4.45%   |
| Ramaxel Technology           | 57        | 2.61%   |
| Elpida                       | 51        | 2.34%   |
| Unknown (ABCD)               | 46        | 2.11%   |
| A-DATA Technology            | 36        | 1.65%   |
| Corsair                      | 30        | 1.38%   |
| Nanya Technology             | 25        | 1.15%   |
| Team                         | 7         | 0.32%   |
| Unknown                      | 7         | 0.32%   |
| Transcend                    | 6         | 0.28%   |
| ASint Technology             | 6         | 0.28%   |
| Toshiba                      | 5         | 0.23%   |
| G.Skill                      | 5         | 0.23%   |
| Qimonda                      | 4         | 0.18%   |
| 48spaces                     | 4         | 0.18%   |
| Timetec                      | 3         | 0.14%   |
| Patriot                      | 2         | 0.09%   |
| Unknown (8A02)               | 1         | 0.05%   |
| Unknown (7F7F7F7F7F7F6B00)   | 1         | 0.05%   |
| Unknown (0x08A4FFFFFFFFFFFF) | 1         | 0.05%   |
| Unigen                       | 1         | 0.05%   |
| Unifosa                      | 1         | 0.05%   |
| Smart Brazil                 | 1         | 0.05%   |
| SHARETRONIC                  | 1         | 0.05%   |
| Sesame                       | 1         | 0.05%   |
| Neo Forza                    | 1         | 0.05%   |
| Infineon                     | 1         | 0.05%   |
| Goldkey                      | 1         | 0.05%   |
| Essencore Limited            | 1         | 0.05%   |
| ChangXin Memory              | 1         | 0.05%   |
| Avant                        | 1         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 42        | 1.82%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 33        | 1.43%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 33        | 1.43%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 31        | 1.34%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 27        | 1.17%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 25        | 1.08%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 24        | 1.04%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 23        | 0.99%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 22        | 0.95%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 21        | 0.91%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 20        | 0.86%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 19        | 0.82%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 19        | 0.82%   |
| SK hynix RAM HMA851S6AFR6N-UH 2GB SODIMM LPDDR4 2667MT/s         | 18        | 0.78%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 18        | 0.78%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 17        | 0.73%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 17        | 0.73%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 16        | 0.69%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 16        | 0.69%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 16        | 0.69%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 15        | 0.65%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 15        | 0.65%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 15        | 0.65%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 14        | 0.61%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 14        | 0.61%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 14        | 0.61%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 14        | 0.61%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 13        | 0.56%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 13        | 0.56%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 13        | 0.56%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 13        | 0.56%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 12        | 0.52%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 12        | 0.52%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 12        | 0.52%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 11        | 0.48%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 11        | 0.48%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 11        | 0.48%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 11        | 0.48%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 11        | 0.48%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 11        | 0.48%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 847       | 45.13%  |
| DDR3    | 660       | 35.16%  |
| LPDDR4  | 115       | 6.13%   |
| DDR2    | 111       | 5.91%   |
| LPDDR3  | 56        | 2.98%   |
| SDRAM   | 41        | 2.18%   |
| Unknown | 14        | 0.75%   |
| DDR5    | 12        | 0.64%   |
| DRAM    | 10        | 0.53%   |
| DDR     | 8         | 0.43%   |
| LPDDR5  | 3         | 0.16%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1684      | 89.05%  |
| Row Of Chips | 185       | 9.78%   |
| DIMM         | 11        | 0.58%   |
| Chip         | 9         | 0.48%   |
| Unknown      | 2         | 0.11%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 746       | 36.79%  |
| 4096  | 667       | 32.89%  |
| 2048  | 278       | 13.71%  |
| 16384 | 234       | 11.54%  |
| 1024  | 60        | 2.96%   |
| 32768 | 26        | 1.28%   |
| 512   | 15        | 0.74%   |
| 6144  | 1         | 0.05%   |
| 256   | 1         | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 417       | 20.59%  |
| 2667    | 413       | 20.4%   |
| 3200    | 302       | 14.91%  |
| 2400    | 183       | 9.04%   |
| 1334    | 118       | 5.83%   |
| 2133    | 102       | 5.04%   |
| 1333    | 78        | 3.85%   |
| Unknown | 72        | 3.56%   |
| 667     | 62        | 3.06%   |
| 4267    | 38        | 1.88%   |
| 1066    | 32        | 1.58%   |
| 3266    | 31        | 1.53%   |
| 800     | 26        | 1.28%   |
| 1067    | 22        | 1.09%   |
| 1867    | 21        | 1.04%   |
| 4199    | 16        | 0.79%   |
| 8400    | 14        | 0.69%   |
| 533     | 14        | 0.69%   |
| 4800    | 13        | 0.64%   |
| 2048    | 11        | 0.54%   |
| 975     | 9         | 0.44%   |
| 4266    | 5         | 0.25%   |
| 2933    | 5         | 0.25%   |
| 6400    | 3         | 0.15%   |
| 3733    | 3         | 0.15%   |
| 3400    | 2         | 0.1%    |
| 1639    | 2         | 0.1%    |
| 400     | 2         | 0.1%    |
| 333     | 2         | 0.1%    |
| 3600    | 1         | 0.05%   |
| 2267    | 1         | 0.05%   |
| 2134    | 1         | 0.05%   |
| 2000    | 1         | 0.05%   |
| 1866    | 1         | 0.05%   |
| 1776    | 1         | 0.05%   |
| 1200    | 1         | 0.05%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 19        | 33.93%  |
| Samsung Electronics | 14        | 25%     |
| Canon               | 9         | 16.07%  |
| Brother Industries  | 5         | 8.93%   |
| Seiko Epson         | 3         | 5.36%   |
| Pantum              | 2         | 3.57%   |
| Xerox               | 1         | 1.79%   |
| Sagem               | 1         | 1.79%   |
| ICS Advent          | 1         | 1.79%   |
| Apple               | 1         | 1.79%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Samsung ML-216x Series Laser Printer | 2         | 3.51%   |
| Samsung M267x 287x Series            | 2         | 3.51%   |
| Samsung M2070 Series                 | 2         | 3.51%   |
| HP OfficeJet 3830 series             | 2         | 3.51%   |
| Xerox B215                           | 1         | 1.75%   |
| Seiko Epson WF-2510 Series           | 1         | 1.75%   |
| Seiko Epson Printer                  | 1         | 1.75%   |
| Seiko Epson L355 Series              | 1         | 1.75%   |
| Samsung SCX-483x 5x3x Series         | 1         | 1.75%   |
| Samsung SCX-4623 Series              | 1         | 1.75%   |
| Samsung SCX-4300 Series              | 1         | 1.75%   |
| Samsung ML-331x Series Laser Printer | 1         | 1.75%   |
| Samsung ML-1865W Series              | 1         | 1.75%   |
| Samsung ML-1640 Series Laser Printer | 1         | 1.75%   |
| Samsung CLP-325 Color Laser Printer  | 1         | 1.75%   |
| Samsung C3060 Series                 | 1         | 1.75%   |
| Sagem Laser Pro LL                   | 1         | 1.75%   |
| Pantum P2500W series                 | 1         | 1.75%   |
| Pantum M6500W series                 | 1         | 1.75%   |
| ICS Advent Parallel Adapter          | 1         | 1.75%   |
| HP Officejet Pro 6230                | 1         | 1.75%   |
| HP OfficeJet 5600 (USBHUB)           | 1         | 1.75%   |
| HP Officejet 2620 series             | 1         | 1.75%   |
| HP LaserJet P3005                    | 1         | 1.75%   |
| HP LaserJet P2055 series             | 1         | 1.75%   |
| HP LaserJet P1102                    | 1         | 1.75%   |
| HP LaserJet 1200                     | 1         | 1.75%   |
| HP LaserJet 1020                     | 1         | 1.75%   |
| HP LaserJet 1015                     | 1         | 1.75%   |
| HP LaserJet 1010                     | 1         | 1.75%   |
| HP ENVY 5000 series                  | 1         | 1.75%   |
| HP ENVY 4520 series                  | 1         | 1.75%   |
| HP DeskJet 940c                      | 1         | 1.75%   |
| HP DeskJet 840c                      | 1         | 1.75%   |
| HP Deskjet 3520 series               | 1         | 1.75%   |
| HP DeskJet 2700 series               | 1         | 1.75%   |
| HP Deskjet 2050 J510                 | 1         | 1.75%   |
| HP Deskjet 1510                      | 1         | 1.75%   |
| Canon TS6100 series                  | 1         | 1.75%   |
| Canon TR4500 series                  | 1         | 1.75%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Seiko Epson     | 5         | 41.67%  |
| Canon           | 5         | 41.67%  |
| Hewlett-Packard | 2         | 16.67%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]        | 2         | 15.38%  |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 7.69%   |
| Seiko Epson ES-D400 [GT-S80]                             | 1         | 7.69%   |
| Seiko Epson CC-570L [Stylus CX3100/CX3200]               | 1         | 7.69%   |
| HP Scanjet G2710                                         | 1         | 7.69%   |
| HP ScanJet 3570c                                         | 1         | 7.69%   |
| Canon CanoScan LIDE 25                                   | 1         | 7.69%   |
| Canon CanoScan LiDE 220                                  | 1         | 7.69%   |
| Canon CanoScan LiDE 120                                  | 1         | 7.69%   |
| Canon CanoScan LiDE 100                                  | 1         | 7.69%   |
| Canon CanoScan 4400F                                     | 1         | 7.69%   |
| Canon CanoScan 1220U                                     | 1         | 7.69%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 813       | 26.54%  |
| IMC Networks                           | 384       | 12.54%  |
| Acer                                   | 238       | 7.77%   |
| Realtek Semiconductor                  | 234       | 7.64%   |
| Microdia                               | 219       | 7.15%   |
| Suyin                                  | 159       | 5.19%   |
| Quanta                                 | 159       | 5.19%   |
| Cheng Uei Precision Industry (Foxlink) | 129       | 4.21%   |
| Sunplus Innovation Technology          | 128       | 4.18%   |
| Alcor Micro                            | 84        | 2.74%   |
| Lite-On Technology                     | 75        | 2.45%   |
| Syntek                                 | 71        | 2.32%   |
| Apple                                  | 66        | 2.15%   |
| Luxvisions Innotech Limited            | 45        | 1.47%   |
| Ricoh                                  | 42        | 1.37%   |
| Silicon Motion                         | 39        | 1.27%   |
| Logitech                               | 20        | 0.65%   |
| Z-Star Microelectronics                | 18        | 0.59%   |
| ALi                                    | 14        | 0.46%   |
| Primax Electronics                     | 13        | 0.42%   |
| Samsung Electronics                    | 11        | 0.36%   |
| USB Camera                             | 9         | 0.29%   |
| Lenovo                                 | 7         | 0.23%   |
| Importek                               | 6         | 0.2%    |
| DJJHFA1BIF5595                         | 6         | 0.2%    |
| DigiTech                               | 6         | 0.2%    |
| Sunplus Technology                     | 5         | 0.16%   |
| Genesys Logic                          | 5         | 0.16%   |
| ARC International                      | 5         | 0.16%   |
| GEMBIRD                                | 4         | 0.13%   |
| SunplusIT                              | 3         | 0.1%    |
| Sonix Technology                       | 3         | 0.1%    |
| Generalplus Technology                 | 3         | 0.1%    |
| WaveRider Communications               | 2         | 0.07%   |
| USB Camera CS                          | 2         | 0.07%   |
| Pixart Imaging                         | 2         | 0.07%   |
| OmniVision Technologies                | 2         | 0.07%   |
| Nebraska Furniture Mart                | 2         | 0.07%   |
| Mustek Systems                         | 2         | 0.07%   |
| Microsoft                              | 2         | 0.07%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 121       | 3.93%   |
| Microdia Integrated_Webcam_HD                           | 96        | 3.12%   |
| Chicony HD WebCam                                       | 79        | 2.57%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 68        | 2.21%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 66        | 2.15%   |
| IMC Networks Integrated Camera                          | 59        | 1.92%   |
| Acer Integrated Camera                                  | 58        | 1.89%   |
| Realtek Integrated_Webcam_HD                            | 51        | 1.66%   |
| Realtek USB Camera                                      | 49        | 1.59%   |
| Chicony USB2.0 HD UVC WebCam                            | 39        | 1.27%   |
| Alcor Micro USB 2.0 Camera                              | 39        | 1.27%   |
| Chicony USB2.0 VGA UVC WebCam                           | 38        | 1.24%   |
| Syntek Integrated Camera                                | 34        | 1.11%   |
| Sunplus Integrated_Webcam_HD                            | 34        | 1.11%   |
| Quanta HP TrueVision HD Camera                          | 31        | 1.01%   |
| Chicony HP TrueVision HD                                | 31        | 1.01%   |
| Acer Lenovo EasyCamera                                  | 31        | 1.01%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 29        | 0.94%   |
| Chicony HP Webcam                                       | 28        | 0.91%   |
| Chicony FJ Camera                                       | 28        | 0.91%   |
| Chicony HP TrueVision HD Camera                         | 26        | 0.85%   |
| Quanta HP Webcam                                        | 25        | 0.81%   |
| Apple iPhone5/5C/5S/6                                   | 24        | 0.78%   |
| Sunplus HD WebCam                                       | 23        | 0.75%   |
| IMC Networks ov9734_azurewave_camera                    | 23        | 0.75%   |
| Alcor Micro Asus Integrated Webcam                      | 23        | 0.75%   |
| Realtek USB2.0 VGA UVC WebCam                           | 22        | 0.72%   |
| Chicony HP HD Camera                                    | 22        | 0.72%   |
| Acer SunplusIT Integrated Camera                        | 21        | 0.68%   |
| Acer HD Webcam                                          | 21        | 0.68%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 20        | 0.65%   |
| IMC Networks UVC VGA Webcam                             | 20        | 0.65%   |
| Chicony USB2.0 Camera                                   | 20        | 0.65%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 20        | 0.65%   |
| Suyin HP Truevision HD                                  | 19        | 0.62%   |
| Microdia Integrated Webcam                              | 19        | 0.62%   |
| IMC Networks HD Camera                                  | 19        | 0.62%   |
| Suyin Acer CrystalEye Webcam                            | 18        | 0.59%   |
| Quanta HD User Facing                                   | 18        | 0.59%   |
| Lite-On HP HD Camera                                    | 18        | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 175       | 30.76%  |
| Synaptics                          | 126       | 22.14%  |
| Shenzhen Goodix Technology         | 98        | 17.22%  |
| Elan Microelectronics              | 61        | 10.72%  |
| AuthenTec                          | 34        | 5.98%   |
| Upek                               | 33        | 5.8%    |
| LighTuning Technology              | 32        | 5.62%   |
| STMicroelectronics                 | 5         | 0.88%   |
| Focal-systems.Corp                 | 4         | 0.7%    |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.18%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 73        | 12.83%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 39        | 6.85%   |
| Elan ELAN:ARM-M4                                                           | 39        | 6.85%   |
| Unknown                                                                    | 36        | 6.33%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 33        | 5.8%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 28        | 4.92%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 22        | 3.87%   |
| Elan ELAN:Fingerprint                                                      | 22        | 3.87%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 19        | 3.34%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 18        | 3.16%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 17        | 2.99%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 16        | 2.81%   |
| Shenzhen Goodix Fingerprint Reader                                         | 15        | 2.64%   |
| Validity Sensors Fingerprint scanner                                       | 14        | 2.46%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 13        | 2.28%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 13        | 2.28%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 12        | 2.11%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 11        | 1.93%   |
| Validity Sensors VFS491                                                    | 10        | 1.76%   |
| Shenzhen Goodix FingerPrint                                                | 10        | 1.76%   |
| Synaptics  WBDI                                                            | 9         | 1.58%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 9         | 1.58%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 8         | 1.41%   |
| Validity Sensors VFS Fingerprint sensor                                    | 7         | 1.23%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 7         | 1.23%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 1.23%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 6         | 1.05%   |
| AuthenTec AES1600                                                          | 6         | 1.05%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 0.88%   |
| Upek TCS5B Fingerprint sensor                                              | 5         | 0.88%   |
| STMicroelectronics Fingerprint Reader                                      | 5         | 0.88%   |
| LighTuning Fingerprint Reader                                              | 5         | 0.88%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 5         | 0.88%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 0.7%    |
| Focal-systems.Corp FT9201Fingerprint.                                      | 4         | 0.7%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 0.53%   |
| AuthenTec AES2810                                                          | 3         | 0.53%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.53%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 2         | 0.35%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 2         | 0.35%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Broadcom                 | 92        | 39.66%  |
| Alcor Micro              | 73        | 31.47%  |
| O2 Micro                 | 27        | 11.64%  |
| Lenovo                   | 15        | 6.47%   |
| Upek                     | 9         | 3.88%   |
| Gemalto (was Gemplus)    | 4         | 1.72%   |
| BIT4ID                   | 3         | 1.29%   |
| Advanced Card Systems    | 3         | 1.29%   |
| Realtek Semiconductor    | 2         | 0.86%   |
| SCM Microsystems         | 1         | 0.43%   |
| Reiner SCT Kartensysteme | 1         | 0.43%   |
| OmniKey                  | 1         | 0.43%   |
| In Focus Systems         | 1         | 0.43%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 71        | 30.6%   |
| Broadcom BCM5880 Secure Applications Processor                               | 30        | 12.93%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 23        | 9.91%   |
| Broadcom 58200                                                               | 23        | 9.91%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 20        | 8.62%   |
| Broadcom 5880                                                                | 17        | 7.33%   |
| Lenovo Integrated Smart Card Reader                                          | 15        | 6.47%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 9         | 3.88%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 1.72%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 1.29%   |
| BIT4ID miniLector EVO                                                        | 3         | 1.29%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 3         | 1.29%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 0.86%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.86%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 0.86%   |
| SCM Microsystems uTrust 3700 F CL Reader                                     | 1         | 0.43%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.43%   |
| OmniKey CardMan Smart@Link                                                   | 1         | 0.43%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.43%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.43%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 2205      | 62.45%  |
| 1     | 1052      | 29.79%  |
| 2     | 242       | 6.85%   |
| 3     | 20        | 0.57%   |
| 4     | 9         | 0.25%   |
| 5     | 2         | 0.06%   |
| 6     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 563       | 35.43%  |
| Graphics card            | 347       | 21.84%  |
| Chipcard                 | 202       | 12.71%  |
| Net/wireless             | 157       | 9.88%   |
| Multimedia controller    | 73        | 4.59%   |
| Camera                   | 58        | 3.65%   |
| Bluetooth                | 53        | 3.34%   |
| Storage                  | 28        | 1.76%   |
| Communication controller | 26        | 1.64%   |
| Flash memory             | 18        | 1.13%   |
| Modem                    | 17        | 1.07%   |
| Sound                    | 16        | 1.01%   |
| Net/ethernet             | 12        | 0.76%   |
| Card reader              | 12        | 0.76%   |
| Network                  | 3         | 0.19%   |
| Storage/raid             | 1         | 0.06%   |
| Storage/nvme             | 1         | 0.06%   |
| Storage/ide              | 1         | 0.06%   |
| Dvb card                 | 1         | 0.06%   |

