Linux Mint - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------

A project to collect tested hardware configurations for Linux Mint.

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

Total: 12160

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HUAWEI        | NBLK-WAX9X                  | [2391058f73](https://linux-hardware.org/?probe=2391058f73) | Jan 01, 2023 |
| Dell          | Latitude 7370               | [cf1f751fbf](https://linux-hardware.org/?probe=cf1f751fbf) | Dec 31, 2022 |
| ASUSTek       | UX31E                       | [58391b15a5](https://linux-hardware.org/?probe=58391b15a5) | Dec 31, 2022 |
| ASUSTek       | X540YA                      | [37ef421251](https://linux-hardware.org/?probe=37ef421251) | Dec 31, 2022 |
| Dell          | Inspiron 1420               | [fe6a8714da](https://linux-hardware.org/?probe=fe6a8714da) | Dec 31, 2022 |
| Dell          | Latitude 7370               | [c9423665bb](https://linux-hardware.org/?probe=c9423665bb) | Dec 31, 2022 |
| Dell          | Latitude D620               | [5337d0b0f9](https://linux-hardware.org/?probe=5337d0b0f9) | Dec 31, 2022 |
| Dell          | Latitude D620               | [ea81d9f6a5](https://linux-hardware.org/?probe=ea81d9f6a5) | Dec 31, 2022 |
| HP            | Pavilion 17                 | [c87d61d0cd](https://linux-hardware.org/?probe=c87d61d0cd) | Dec 31, 2022 |
| HP            | Pavilion 17                 | [bbf52af119](https://linux-hardware.org/?probe=bbf52af119) | Dec 31, 2022 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [fc108fb0d8](https://linux-hardware.org/?probe=fc108fb0d8) | Dec 31, 2022 |
| Dell          | G15 5520                    | [2e82f45fb6](https://linux-hardware.org/?probe=2e82f45fb6) | Dec 30, 2022 |
| Acer          | Aspire E5-576G              | [883bd1cd8d](https://linux-hardware.org/?probe=883bd1cd8d) | Dec 30, 2022 |
| Chuwi         | HeroBook Pro                | [cdc31b8338](https://linux-hardware.org/?probe=cdc31b8338) | Dec 30, 2022 |
| Acer          | Predator G3-572             | [ab03199a79](https://linux-hardware.org/?probe=ab03199a79) | Dec 30, 2022 |
| Compaq        | CQ-27                       | [fc5b98e1db](https://linux-hardware.org/?probe=fc5b98e1db) | Dec 30, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [347dc56d43](https://linux-hardware.org/?probe=347dc56d43) | Dec 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [c28fb2edb2](https://linux-hardware.org/?probe=c28fb2edb2) | Dec 30, 2022 |
| Lenovo        | G575 4383                   | [7c203c43cc](https://linux-hardware.org/?probe=7c203c43cc) | Dec 30, 2022 |
| Lenovo        | G575 4383                   | [c9656285fc](https://linux-hardware.org/?probe=c9656285fc) | Dec 30, 2022 |
| HP            | Pavilion dv7                | [6ba364face](https://linux-hardware.org/?probe=6ba364face) | Dec 30, 2022 |
| HP            | Laptop 17-ca2xxx            | [add21e3026](https://linux-hardware.org/?probe=add21e3026) | Dec 30, 2022 |
| HP            | 250 G8 Notebook PC          | [6b8db26ab8](https://linux-hardware.org/?probe=6b8db26ab8) | Dec 30, 2022 |
| Acer          | Aspire A115-32              | [7c8ec90c8a](https://linux-hardware.org/?probe=7c8ec90c8a) | Dec 30, 2022 |
| Dell          | Inspiron 5593               | [bf0f36d69a](https://linux-hardware.org/?probe=bf0f36d69a) | Dec 30, 2022 |
| Lenovo        | ThinkPad T430 23426FU       | [eec74990ca](https://linux-hardware.org/?probe=eec74990ca) | Dec 30, 2022 |
| Dell          | Inspiron N5110              | [08682d735c](https://linux-hardware.org/?probe=08682d735c) | Dec 30, 2022 |
| Acer          | Predator G3-572             | [f99480426f](https://linux-hardware.org/?probe=f99480426f) | Dec 29, 2022 |
| Dell          | Latitude E6430              | [8ecaae98d3](https://linux-hardware.org/?probe=8ecaae98d3) | Dec 29, 2022 |
| Lenovo        | G40-30 80FY                 | [49bb82ca4b](https://linux-hardware.org/?probe=49bb82ca4b) | Dec 29, 2022 |
| Lenovo        | IdeaPad 320-14IAP 80XQ      | [e133481ab3](https://linux-hardware.org/?probe=e133481ab3) | Dec 29, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | [6c836dde26](https://linux-hardware.org/?probe=6c836dde26) | Dec 29, 2022 |
| Dell          | Latitude E6410              | [0ee655e2cc](https://linux-hardware.org/?probe=0ee655e2cc) | Dec 29, 2022 |
| Acer          | Aspire 4820TG               | [77721c13c4](https://linux-hardware.org/?probe=77721c13c4) | Dec 29, 2022 |
| Acer          | Aspire A515-55              | [296961ae2d](https://linux-hardware.org/?probe=296961ae2d) | Dec 29, 2022 |
| ASUSTek       | GL553VD                     | [9c4eab8774](https://linux-hardware.org/?probe=9c4eab8774) | Dec 29, 2022 |
| Acer          | Aspire AV14-51              | [4f92ccde69](https://linux-hardware.org/?probe=4f92ccde69) | Dec 29, 2022 |
| Acer          | Aspire 5680                 | [c14cfe5386](https://linux-hardware.org/?probe=c14cfe5386) | Dec 29, 2022 |
| Shenzhen W... | TANK56                      | [4cd3e6c8e4](https://linux-hardware.org/?probe=4cd3e6c8e4) | Dec 29, 2022 |
| ASUSTek       | N551JM                      | [932615a484](https://linux-hardware.org/?probe=932615a484) | Dec 29, 2022 |
| TrekStor      | Primebook P14               | [c22676280e](https://linux-hardware.org/?probe=c22676280e) | Dec 29, 2022 |
| Acer          | Aspire V3-772               | [9f431b484a](https://linux-hardware.org/?probe=9f431b484a) | Dec 29, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [2ea31ca86e](https://linux-hardware.org/?probe=2ea31ca86e) | Dec 29, 2022 |
| Lenovo        | ThinkPad X240 20AL007AMZ    | [bcb9b7a061](https://linux-hardware.org/?probe=bcb9b7a061) | Dec 29, 2022 |
| HP            | ZBook 17 G4                 | [86eec5f93c](https://linux-hardware.org/?probe=86eec5f93c) | Dec 29, 2022 |
| Lenovo        | ThinkPad T430 23426FU       | [9e4e7d1738](https://linux-hardware.org/?probe=9e4e7d1738) | Dec 29, 2022 |
| Lenovo        | ThinkPad T490s 20NYS9MJ0... | [8489abdbe7](https://linux-hardware.org/?probe=8489abdbe7) | Dec 29, 2022 |
| Unknown       | Unknown                     | [0c7bea2d0f](https://linux-hardware.org/?probe=0c7bea2d0f) | Dec 29, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [0760eec7e2](https://linux-hardware.org/?probe=0760eec7e2) | Dec 28, 2022 |
| HP            | Compaq 6730s                | [9294bf57da](https://linux-hardware.org/?probe=9294bf57da) | Dec 28, 2022 |
| HP            | EliteBook 2540p             | [ec9251ac5d](https://linux-hardware.org/?probe=ec9251ac5d) | Dec 28, 2022 |
| HP            | Mini 100e                   | [dd184e04ad](https://linux-hardware.org/?probe=dd184e04ad) | Dec 28, 2022 |
| Fujitsu       | LIFEBOOK A544               | [efdc6bb5cb](https://linux-hardware.org/?probe=efdc6bb5cb) | Dec 28, 2022 |
| HP            | EliteBook 850 G6            | [b30d6f1b58](https://linux-hardware.org/?probe=b30d6f1b58) | Dec 28, 2022 |
| HP            | Laptop 15-dw0xxx            | [7c2b9af9c3](https://linux-hardware.org/?probe=7c2b9af9c3) | Dec 28, 2022 |
| HP            | EliteBook 820 G3            | [3c494dd1eb](https://linux-hardware.org/?probe=3c494dd1eb) | Dec 28, 2022 |
| HP            | EliteBook 8440p             | [6674099744](https://linux-hardware.org/?probe=6674099744) | Dec 27, 2022 |
| Packard Be... | EasyNote TJ65               | [57bfe7c99d](https://linux-hardware.org/?probe=57bfe7c99d) | Dec 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [2c2b5135eb](https://linux-hardware.org/?probe=2c2b5135eb) | Dec 27, 2022 |
| Dell          | Latitude 5420               | [06dc453cbc](https://linux-hardware.org/?probe=06dc453cbc) | Dec 27, 2022 |
| HP            | EliteBook 820 G3            | [95555948a2](https://linux-hardware.org/?probe=95555948a2) | Dec 27, 2022 |
| HP            | 255 15.6 inch G9 Noteboo... | [dc9d334f95](https://linux-hardware.org/?probe=dc9d334f95) | Dec 27, 2022 |
| Dell          | Venue 11 Pro 5130           | [c68cba64e9](https://linux-hardware.org/?probe=c68cba64e9) | Dec 27, 2022 |
| Dell          | Latitude 3510               | [ac931934de](https://linux-hardware.org/?probe=ac931934de) | Dec 27, 2022 |
| Dell          | Latitude 3510               | [5db1cf6cb6](https://linux-hardware.org/?probe=5db1cf6cb6) | Dec 27, 2022 |
| HP            | Notebook                    | [8ba42c8ebc](https://linux-hardware.org/?probe=8ba42c8ebc) | Dec 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [a7b2bad562](https://linux-hardware.org/?probe=a7b2bad562) | Dec 27, 2022 |
| Dell          | Inspiron 5579               | [6fbb0cbd09](https://linux-hardware.org/?probe=6fbb0cbd09) | Dec 27, 2022 |
| Dell          | Inspiron 5579               | [838cda532a](https://linux-hardware.org/?probe=838cda532a) | Dec 27, 2022 |
| GPU Compan... | GWTN156-3BK                 | [7c9c57b704](https://linux-hardware.org/?probe=7c9c57b704) | Dec 27, 2022 |
| Acer          | Swift SF314-56              | [41ca6b15cf](https://linux-hardware.org/?probe=41ca6b15cf) | Dec 26, 2022 |
| HP            | Mini 100e                   | [bf749ac406](https://linux-hardware.org/?probe=bf749ac406) | Dec 26, 2022 |
| Lenovo        | Legion Y7000P 81LD          | [d27a1b703b](https://linux-hardware.org/?probe=d27a1b703b) | Dec 26, 2022 |
| HP            | Laptop 15-dy2xxx            | [8e2393e7b4](https://linux-hardware.org/?probe=8e2393e7b4) | Dec 26, 2022 |
| ASUSTek       | K61IC                       | [4c34b8d5a1](https://linux-hardware.org/?probe=4c34b8d5a1) | Dec 26, 2022 |
| Dell          | Latitude E6400              | [435ac90ddc](https://linux-hardware.org/?probe=435ac90ddc) | Dec 26, 2022 |
| HP            | Compaq 6730s                | [ac1ae104e8](https://linux-hardware.org/?probe=ac1ae104e8) | Dec 26, 2022 |
| Dell          | Latitude E4310              | [f63df6ad2c](https://linux-hardware.org/?probe=f63df6ad2c) | Dec 26, 2022 |
| HP            | Compaq 6730s                | [0cc88159aa](https://linux-hardware.org/?probe=0cc88159aa) | Dec 26, 2022 |
| ASUSTek       | X550LD                      | [e0a09344e0](https://linux-hardware.org/?probe=e0a09344e0) | Dec 26, 2022 |
| ASUSTek       | X550LD                      | [d6948e7207](https://linux-hardware.org/?probe=d6948e7207) | Dec 26, 2022 |
| Samsung       | RV420/RV520/RV720/E3530/... | [4665d79293](https://linux-hardware.org/?probe=4665d79293) | Dec 25, 2022 |
| MSI           | CR700                       | [92b97fec48](https://linux-hardware.org/?probe=92b97fec48) | Dec 25, 2022 |
| MSI           | CR700                       | [df25c10894](https://linux-hardware.org/?probe=df25c10894) | Dec 25, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [ff90a6a029](https://linux-hardware.org/?probe=ff90a6a029) | Dec 25, 2022 |
| Lenovo        | ThinkPad L14 Gen 3 21C1C... | [f27b950cd8](https://linux-hardware.org/?probe=f27b950cd8) | Dec 25, 2022 |
| Acer          | Aspire A515-57G             | [2e82fb3f66](https://linux-hardware.org/?probe=2e82fb3f66) | Dec 25, 2022 |
| HP            | 2000                        | [7abc0ff528](https://linux-hardware.org/?probe=7abc0ff528) | Dec 25, 2022 |
| Sony          | SVE15133CNB                 | [40ac0f9ffc](https://linux-hardware.org/?probe=40ac0f9ffc) | Dec 25, 2022 |
| Lenovo        | ThinkPad T500 2055A38       | [90a67d3589](https://linux-hardware.org/?probe=90a67d3589) | Dec 25, 2022 |
| MSI           | GP62M 7REX                  | [f49c90b8dc](https://linux-hardware.org/?probe=f49c90b8dc) | Dec 25, 2022 |
| ASUSTek       | X750JN                      | [a604b57c92](https://linux-hardware.org/?probe=a604b57c92) | Dec 25, 2022 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | [bc961748be](https://linux-hardware.org/?probe=bc961748be) | Dec 25, 2022 |
| Lenovo        | ThinkPad L530 24781P9       | [fd8de03405](https://linux-hardware.org/?probe=fd8de03405) | Dec 25, 2022 |
| Lenovo        | Yoga 2 13 20344             | [9d8bce4c41](https://linux-hardware.org/?probe=9d8bce4c41) | Dec 25, 2022 |
| Acer          | Aspire ES1-523              | [41211efaae](https://linux-hardware.org/?probe=41211efaae) | Dec 25, 2022 |
| Chuwi         | HeroBook Air                | [ccd5d4bac3](https://linux-hardware.org/?probe=ccd5d4bac3) | Dec 25, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [c95a4418f0](https://linux-hardware.org/?probe=c95a4418f0) | Dec 24, 2022 |
| ASUSTek       | Q502LA                      | [386702ad8a](https://linux-hardware.org/?probe=386702ad8a) | Dec 24, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [a36ea47b5c](https://linux-hardware.org/?probe=a36ea47b5c) | Dec 24, 2022 |
| Toshiba       | Satellite P755              | [723232bde6](https://linux-hardware.org/?probe=723232bde6) | Dec 24, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | [44c6de2137](https://linux-hardware.org/?probe=44c6de2137) | Dec 24, 2022 |
| Samsung       | RF511/RF411/RF711           | [b0a9f1ed91](https://linux-hardware.org/?probe=b0a9f1ed91) | Dec 24, 2022 |
| ASUSTek       | K52JT                       | [915e35ba2b](https://linux-hardware.org/?probe=915e35ba2b) | Dec 24, 2022 |
| ASUSTek       | X750JN                      | [cc5facc858](https://linux-hardware.org/?probe=cc5facc858) | Dec 23, 2022 |
| HP            | Pavilion g7                 | [5620f164c9](https://linux-hardware.org/?probe=5620f164c9) | Dec 23, 2022 |
| Lenovo        | Legion 7 16ITHg6 82K6       | [2c6f47974f](https://linux-hardware.org/?probe=2c6f47974f) | Dec 23, 2022 |
| Chuwi         | HeroBook Air                | [8f4eea6be8](https://linux-hardware.org/?probe=8f4eea6be8) | Dec 23, 2022 |
| HP            | ZBook Firefly 15 G7 Mobi... | [64e7d7f26c](https://linux-hardware.org/?probe=64e7d7f26c) | Dec 23, 2022 |
| Lenovo        | Y50-70 Touch 20349          | [9266f8399c](https://linux-hardware.org/?probe=9266f8399c) | Dec 23, 2022 |
| Acer          | Aspire ES1-523              | [476f9315a1](https://linux-hardware.org/?probe=476f9315a1) | Dec 23, 2022 |
| Google        | Bobba360                    | [bdad461cec](https://linux-hardware.org/?probe=bdad461cec) | Dec 23, 2022 |
| Acer          | Aspire M5-481T              | [22eafd12e4](https://linux-hardware.org/?probe=22eafd12e4) | Dec 23, 2022 |
| Acer          | Aspire M5-481T              | [f250052dff](https://linux-hardware.org/?probe=f250052dff) | Dec 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [aeb7addbc3](https://linux-hardware.org/?probe=aeb7addbc3) | Dec 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [2a0cacc27e](https://linux-hardware.org/?probe=2a0cacc27e) | Dec 23, 2022 |
| Positivo      | C4128E-S                    | [2fce43e57f](https://linux-hardware.org/?probe=2fce43e57f) | Dec 23, 2022 |
| Toshiba       | Satellite C70D-B            | [82cc0b362d](https://linux-hardware.org/?probe=82cc0b362d) | Dec 23, 2022 |
| HP            | Laptop 15-db0xxx            | [3e269dcad0](https://linux-hardware.org/?probe=3e269dcad0) | Dec 23, 2022 |
| HP            | Laptop 15-db0xxx            | [27f289cf57](https://linux-hardware.org/?probe=27f289cf57) | Dec 23, 2022 |
| Dell          | Latitude 7490               | [d5223c073b](https://linux-hardware.org/?probe=d5223c073b) | Dec 23, 2022 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [5ce0dacccf](https://linux-hardware.org/?probe=5ce0dacccf) | Dec 23, 2022 |
| Fujitsu       | LIFEBOOK AH544              | [431eac7d11](https://linux-hardware.org/?probe=431eac7d11) | Dec 22, 2022 |
| HP            | Compaq 6730b (GW687AV)      | [8c936284b0](https://linux-hardware.org/?probe=8c936284b0) | Dec 22, 2022 |
| Acer          | Aspire ES1-311              | [e5d7bd61f1](https://linux-hardware.org/?probe=e5d7bd61f1) | Dec 22, 2022 |
| Unknown       | Unknown                     | [c9637c2acf](https://linux-hardware.org/?probe=c9637c2acf) | Dec 22, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [451f22ab12](https://linux-hardware.org/?probe=451f22ab12) | Dec 22, 2022 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | [9100b276c2](https://linux-hardware.org/?probe=9100b276c2) | Dec 22, 2022 |
| eMachines     | E725                        | [86939210d0](https://linux-hardware.org/?probe=86939210d0) | Dec 22, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | [a62d8c781d](https://linux-hardware.org/?probe=a62d8c781d) | Dec 22, 2022 |
| Lenovo        | G510 20238                  | [b5fcbb8663](https://linux-hardware.org/?probe=b5fcbb8663) | Dec 22, 2022 |
| Lenovo        | G510 20238                  | [2489f01426](https://linux-hardware.org/?probe=2489f01426) | Dec 22, 2022 |
| Acer          | Aspire ES1-523              | [d034bb7c92](https://linux-hardware.org/?probe=d034bb7c92) | Dec 22, 2022 |
| Acer          | Aspire ES1-523              | [806aa49648](https://linux-hardware.org/?probe=806aa49648) | Dec 22, 2022 |
| Dell          | Latitude E7250              | [9d6fed05b1](https://linux-hardware.org/?probe=9d6fed05b1) | Dec 22, 2022 |
| HP            | ProBook 450 15.6 inch G9... | [e160bf6ea0](https://linux-hardware.org/?probe=e160bf6ea0) | Dec 22, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [54fb90def3](https://linux-hardware.org/?probe=54fb90def3) | Dec 22, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [a2d763d722](https://linux-hardware.org/?probe=a2d763d722) | Dec 21, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [92515d8a95](https://linux-hardware.org/?probe=92515d8a95) | Dec 21, 2022 |
| Acer          | Gateway NE46Rs1             | [45a25a89d7](https://linux-hardware.org/?probe=45a25a89d7) | Dec 21, 2022 |
| ASUSTek       | S500CA                      | [305c04a6ce](https://linux-hardware.org/?probe=305c04a6ce) | Dec 21, 2022 |
| Acer          | Aspire ES1-523              | [3528a9d40f](https://linux-hardware.org/?probe=3528a9d40f) | Dec 21, 2022 |
| Acer          | Aspire 5680                 | [9b188c358e](https://linux-hardware.org/?probe=9b188c358e) | Dec 21, 2022 |
| HP            | 255 15.6 inch G9 Noteboo... | [54b5dfbdbb](https://linux-hardware.org/?probe=54b5dfbdbb) | Dec 21, 2022 |
| Schenker      | XMG APEX 15 MAX (E22)       | [6b46538fea](https://linux-hardware.org/?probe=6b46538fea) | Dec 21, 2022 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | [97d8552a67](https://linux-hardware.org/?probe=97d8552a67) | Dec 21, 2022 |
| ASUSTek       | N55SF                       | [b1d6a6a73d](https://linux-hardware.org/?probe=b1d6a6a73d) | Dec 21, 2022 |
| Dell          | Inspiron 15 3511            | [e7bf0c0a09](https://linux-hardware.org/?probe=e7bf0c0a09) | Dec 21, 2022 |
| Lenovo        | ThinkPad X250 20CM001PGE    | [8d98e783c2](https://linux-hardware.org/?probe=8d98e783c2) | Dec 21, 2022 |
| ASUSTek       | N55SF                       | [bbec56fa90](https://linux-hardware.org/?probe=bbec56fa90) | Dec 21, 2022 |
| Dell          | Latitude E6420              | [3244fe3048](https://linux-hardware.org/?probe=3244fe3048) | Dec 20, 2022 |
| Lenovo        | ThinkPad X230 2325AEG       | [5000a7274b](https://linux-hardware.org/?probe=5000a7274b) | Dec 20, 2022 |
| Medion        | P7621                       | [eced009b2a](https://linux-hardware.org/?probe=eced009b2a) | Dec 20, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [87d3186549](https://linux-hardware.org/?probe=87d3186549) | Dec 20, 2022 |
| Acer          | Swift SF314-56              | [ffeb38a953](https://linux-hardware.org/?probe=ffeb38a953) | Dec 20, 2022 |
| Dell          | Latitude E6430              | [a1db0f0a18](https://linux-hardware.org/?probe=a1db0f0a18) | Dec 20, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | [a7364cab6e](https://linux-hardware.org/?probe=a7364cab6e) | Dec 20, 2022 |
| Multilaser    | UB23X LINUX                 | [9f7503d89d](https://linux-hardware.org/?probe=9f7503d89d) | Dec 20, 2022 |
| Dell          | Latitude E6420              | [7d592f1759](https://linux-hardware.org/?probe=7d592f1759) | Dec 20, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [d79e681980](https://linux-hardware.org/?probe=d79e681980) | Dec 19, 2022 |
| Multilaser    | UB23X LINUX                 | [502d9cd6ce](https://linux-hardware.org/?probe=502d9cd6ce) | Dec 19, 2022 |
| Dell          | Inspiron N5050              | [41fb3c537a](https://linux-hardware.org/?probe=41fb3c537a) | Dec 19, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [72bfd0a0f6](https://linux-hardware.org/?probe=72bfd0a0f6) | Dec 19, 2022 |
| Fujitsu Si... | LIFEBOOK T5010              | [9f5485a1ed](https://linux-hardware.org/?probe=9f5485a1ed) | Dec 19, 2022 |
| Fujitsu Si... | LIFEBOOK T5010              | [e7fe928198](https://linux-hardware.org/?probe=e7fe928198) | Dec 19, 2022 |
| HP            | Pavilion g6                 | [4ffa593ffe](https://linux-hardware.org/?probe=4ffa593ffe) | Dec 19, 2022 |
| HP            | Pavilion g6                 | [ede790ce3c](https://linux-hardware.org/?probe=ede790ce3c) | Dec 19, 2022 |
| Lenovo        | ThinkPad T450 20BUS0EW11    | [9fca55febc](https://linux-hardware.org/?probe=9fca55febc) | Dec 19, 2022 |
| Lenovo        | ThinkPad T450 20BUS0EW11    | [57605a26eb](https://linux-hardware.org/?probe=57605a26eb) | Dec 19, 2022 |
| Packard Be... | EasyNote TR85               | [6c56016ed0](https://linux-hardware.org/?probe=6c56016ed0) | Dec 19, 2022 |
| Packard Be... | EasyNote TR85               | [abd93a5cca](https://linux-hardware.org/?probe=abd93a5cca) | Dec 19, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [c20be92503](https://linux-hardware.org/?probe=c20be92503) | Dec 19, 2022 |
| HP            | 620                         | [c5ed6ae3bf](https://linux-hardware.org/?probe=c5ed6ae3bf) | Dec 19, 2022 |
| Lenovo        | ThinkPad T430 2347CM9       | [cc1c68fe85](https://linux-hardware.org/?probe=cc1c68fe85) | Dec 19, 2022 |
| Dell          | MXG071                      | [b999ae7bba](https://linux-hardware.org/?probe=b999ae7bba) | Dec 19, 2022 |
| Dell          | MXG071                      | [587b5fb932](https://linux-hardware.org/?probe=587b5fb932) | Dec 19, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [3a6e0b953f](https://linux-hardware.org/?probe=3a6e0b953f) | Dec 19, 2022 |
| Dell          | Latitude E6440              | [3b6ac9ce59](https://linux-hardware.org/?probe=3b6ac9ce59) | Dec 19, 2022 |
| HP            | ProBook 4530s               | [2c6a27a08d](https://linux-hardware.org/?probe=2c6a27a08d) | Dec 19, 2022 |
| HP            | ProBook 4530s               | [19892439d6](https://linux-hardware.org/?probe=19892439d6) | Dec 19, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [686a93a02a](https://linux-hardware.org/?probe=686a93a02a) | Dec 19, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [1489f7e01d](https://linux-hardware.org/?probe=1489f7e01d) | Dec 18, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [44a96b54b6](https://linux-hardware.org/?probe=44a96b54b6) | Dec 18, 2022 |
| Acer          | Swift SF314-56              | [3d8b3f7f82](https://linux-hardware.org/?probe=3d8b3f7f82) | Dec 18, 2022 |
| AXDIA Inte... | myBook PRO14 SE V2          | [14b79d7a8b](https://linux-hardware.org/?probe=14b79d7a8b) | Dec 18, 2022 |
| Dell          | Inspiron 7720               | [f29071b4a8](https://linux-hardware.org/?probe=f29071b4a8) | Dec 18, 2022 |
| Acer          | Aspire A517-52G             | [225e2eaae8](https://linux-hardware.org/?probe=225e2eaae8) | Dec 18, 2022 |
| GTZS          | Unknown                     | [e3260fee79](https://linux-hardware.org/?probe=e3260fee79) | Dec 18, 2022 |
| Dell          | Latitude E7470              | [262849f0f6](https://linux-hardware.org/?probe=262849f0f6) | Dec 18, 2022 |
| ASUSTek       | K55A                        | [6129e825d9](https://linux-hardware.org/?probe=6129e825d9) | Dec 18, 2022 |
| ASUSTek       | X555UJ                      | [94a9979dd8](https://linux-hardware.org/?probe=94a9979dd8) | Dec 18, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [4b86a906e7](https://linux-hardware.org/?probe=4b86a906e7) | Dec 18, 2022 |
| Lenovo        | IdeaPad Z570 10249UU        | [2160e3e2c3](https://linux-hardware.org/?probe=2160e3e2c3) | Dec 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [071b57d5f6](https://linux-hardware.org/?probe=071b57d5f6) | Dec 18, 2022 |
| HP            | Laptop 15s-fq2xxx           | [ab6fd91b71](https://linux-hardware.org/?probe=ab6fd91b71) | Dec 17, 2022 |
| Acer          | Aspire 5680                 | [64f5eb2f4b](https://linux-hardware.org/?probe=64f5eb2f4b) | Dec 17, 2022 |
| Samsung       | RV415/RV515                 | [dcf4e8200b](https://linux-hardware.org/?probe=dcf4e8200b) | Dec 17, 2022 |
| Acer          | Aspire E1-531               | [633910e332](https://linux-hardware.org/?probe=633910e332) | Dec 17, 2022 |
| Sony          | VPCCW21FX                   | [9d82e3655b](https://linux-hardware.org/?probe=9d82e3655b) | Dec 17, 2022 |
| MSI           | GF75 Thin 10SCSXR           | [09cdbbcf3f](https://linux-hardware.org/?probe=09cdbbcf3f) | Dec 17, 2022 |
| Toshiba       | Satellite S70-A             | [3eddeb0d68](https://linux-hardware.org/?probe=3eddeb0d68) | Dec 17, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [f82368713d](https://linux-hardware.org/?probe=f82368713d) | Dec 17, 2022 |
| HUAWEI        | KLVL-WXXW                   | [1deb35f268](https://linux-hardware.org/?probe=1deb35f268) | Dec 17, 2022 |
| Toshiba       | Satellite C70D-B            | [182e467ce6](https://linux-hardware.org/?probe=182e467ce6) | Dec 17, 2022 |
| MSI           | GF75 Thin 10SCSXR           | [8f884fc451](https://linux-hardware.org/?probe=8f884fc451) | Dec 17, 2022 |
| Apple         | MacBookPro8,2               | [4ed1785ef7](https://linux-hardware.org/?probe=4ed1785ef7) | Dec 17, 2022 |
| HP            | EliteBook 820 G3            | [5e5909e93f](https://linux-hardware.org/?probe=5e5909e93f) | Dec 17, 2022 |
| Dell          | Inspiron N7010              | [de5dc0c3ea](https://linux-hardware.org/?probe=de5dc0c3ea) | Dec 17, 2022 |
| Dell          | Latitude E5570              | [cc58177561](https://linux-hardware.org/?probe=cc58177561) | Dec 17, 2022 |
| Acer          | Extensa 7630EZ              | [e17ca259c0](https://linux-hardware.org/?probe=e17ca259c0) | Dec 16, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [9f0911ee6b](https://linux-hardware.org/?probe=9f0911ee6b) | Dec 16, 2022 |
| Acer          | Extensa 7630EZ              | [fac3dd4a6c](https://linux-hardware.org/?probe=fac3dd4a6c) | Dec 16, 2022 |
| Lenovo        | ThinkPad T570 20H9S04C00    | [f3093ba13c](https://linux-hardware.org/?probe=f3093ba13c) | Dec 16, 2022 |
| Chuwi         | HeroBook Air                | [6da143680b](https://linux-hardware.org/?probe=6da143680b) | Dec 16, 2022 |
| Dell          | Inspiron 1501               | [1bb0000755](https://linux-hardware.org/?probe=1bb0000755) | Dec 16, 2022 |
| Acer          | Aspire A515-57              | [4e9bbbaa1f](https://linux-hardware.org/?probe=4e9bbbaa1f) | Dec 16, 2022 |
| HUAWEI        | BOM-WXX9                    | [dd664077fe](https://linux-hardware.org/?probe=dd664077fe) | Dec 16, 2022 |
| HP            | Laptop 15s-fq2xxx           | [d9c3d0a5cd](https://linux-hardware.org/?probe=d9c3d0a5cd) | Dec 16, 2022 |
| HP            | HDX16                       | [6be9713552](https://linux-hardware.org/?probe=6be9713552) | Dec 15, 2022 |
| Avell High... | A60 MUV                     | [204d35bad7](https://linux-hardware.org/?probe=204d35bad7) | Dec 15, 2022 |
| HP            | EliteBook 850 G2            | [d0d30cd96f](https://linux-hardware.org/?probe=d0d30cd96f) | Dec 14, 2022 |
| ASUSTek       | K53U                        | [cbbffb5194](https://linux-hardware.org/?probe=cbbffb5194) | Dec 14, 2022 |
| HP            | Laptop 15-da2xxx            | [cd64f27416](https://linux-hardware.org/?probe=cd64f27416) | Dec 14, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [b7d1538f13](https://linux-hardware.org/?probe=b7d1538f13) | Dec 14, 2022 |
| ASUSTek       | X550VX                      | [0ee46688fb](https://linux-hardware.org/?probe=0ee46688fb) | Dec 14, 2022 |
| Acer          | Aspire ES1-531              | [36bd6688bb](https://linux-hardware.org/?probe=36bd6688bb) | Dec 14, 2022 |
| Acer          | Aspire ES1-531              | [ed5d274c1a](https://linux-hardware.org/?probe=ed5d274c1a) | Dec 14, 2022 |
| Lenovo        | ThinkPad W541 20EGS06T00    | [2cdb5f249e](https://linux-hardware.org/?probe=2cdb5f249e) | Dec 14, 2022 |
| MSI           | GL73 8RC                    | [770d74f714](https://linux-hardware.org/?probe=770d74f714) | Dec 14, 2022 |
| Dell          | Latitude E7450              | [196b96ea5e](https://linux-hardware.org/?probe=196b96ea5e) | Dec 14, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [c476fb8f49](https://linux-hardware.org/?probe=c476fb8f49) | Dec 13, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [6e2b72eefe](https://linux-hardware.org/?probe=6e2b72eefe) | Dec 13, 2022 |
| Dell          | Latitude E4310              | [dd3e716d03](https://linux-hardware.org/?probe=dd3e716d03) | Dec 13, 2022 |
| Lenovo        | B71-80 80RJ                 | [8369524e4e](https://linux-hardware.org/?probe=8369524e4e) | Dec 13, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [5d00840ad3](https://linux-hardware.org/?probe=5d00840ad3) | Dec 13, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [5dd8c45fee](https://linux-hardware.org/?probe=5dd8c45fee) | Dec 13, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [1129626fee](https://linux-hardware.org/?probe=1129626fee) | Dec 13, 2022 |
| Dynabook      | Satellite Pro C50-H-11D     | [f2f233cc99](https://linux-hardware.org/?probe=f2f233cc99) | Dec 13, 2022 |
| HP            | EliteBook 820 G3            | [ff5b82cee3](https://linux-hardware.org/?probe=ff5b82cee3) | Dec 13, 2022 |
| Lenovo        | IdeaPad S145-14IGM 81MW     | [9866855d37](https://linux-hardware.org/?probe=9866855d37) | Dec 13, 2022 |
| Lenovo        | ThinkPad SL510 2847A72      | [77518bc6c6](https://linux-hardware.org/?probe=77518bc6c6) | Dec 13, 2022 |
| Dell          | System Inspiron 7720        | [8e5e2683e3](https://linux-hardware.org/?probe=8e5e2683e3) | Dec 13, 2022 |
| Lenovo        | ThinkPad T400 647419G       | [a73b681605](https://linux-hardware.org/?probe=a73b681605) | Dec 13, 2022 |
| Apple         | MacBookPro8,2               | [05ef133104](https://linux-hardware.org/?probe=05ef133104) | Dec 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [ca560a74e4](https://linux-hardware.org/?probe=ca560a74e4) | Dec 12, 2022 |
| HP            | EliteBook 820 G3            | [1e0eec72b2](https://linux-hardware.org/?probe=1e0eec72b2) | Dec 12, 2022 |
| Unknown       | Unknown                     | [535aa05a37](https://linux-hardware.org/?probe=535aa05a37) | Dec 12, 2022 |
| GPU Compan... | GWTC116-2                   | [fcb499b33f](https://linux-hardware.org/?probe=fcb499b33f) | Dec 12, 2022 |
| GPU Compan... | GWTC116-2                   | [d29d953915](https://linux-hardware.org/?probe=d29d953915) | Dec 12, 2022 |
| Dell          | XPS L521X                   | [c69c906797](https://linux-hardware.org/?probe=c69c906797) | Dec 12, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ce1ae34933](https://linux-hardware.org/?probe=ce1ae34933) | Dec 12, 2022 |
| Lenovo        | ThinkPad T61 8891CTO        | [438785c8af](https://linux-hardware.org/?probe=438785c8af) | Dec 12, 2022 |
| Toshiba       | Satellite C70D-B            | [56adac1fcb](https://linux-hardware.org/?probe=56adac1fcb) | Dec 12, 2022 |
| MSI           | Summit E16FlipEvo A12MT     | [426289da4e](https://linux-hardware.org/?probe=426289da4e) | Dec 11, 2022 |
| HP            | EliteBook 8570w             | [367579550b](https://linux-hardware.org/?probe=367579550b) | Dec 11, 2022 |
| HP            | Pavilion TS 11              | [db2a3e8ebb](https://linux-hardware.org/?probe=db2a3e8ebb) | Dec 11, 2022 |
| Toshiba       | Satellite L455              | [e92985332e](https://linux-hardware.org/?probe=e92985332e) | Dec 11, 2022 |
| Lenovo        | IdeaPad 320-17AST 80XW      | [474f4f4c43](https://linux-hardware.org/?probe=474f4f4c43) | Dec 11, 2022 |
| HP            | Pavilion g6                 | [964081eed7](https://linux-hardware.org/?probe=964081eed7) | Dec 11, 2022 |
| Google        | Blooglet                    | [a9d65d2144](https://linux-hardware.org/?probe=a9d65d2144) | Dec 11, 2022 |
| HP            | EliteBook 830 G6            | [cea4c76b9d](https://linux-hardware.org/?probe=cea4c76b9d) | Dec 11, 2022 |
| Alienware     | M17xR4                      | [9781f15a4b](https://linux-hardware.org/?probe=9781f15a4b) | Dec 11, 2022 |
| Toshiba       | Satellite S70-A             | [662bfb443c](https://linux-hardware.org/?probe=662bfb443c) | Dec 11, 2022 |
| Sony          | VPCEE27FL                   | [dd2bc8b6ff](https://linux-hardware.org/?probe=dd2bc8b6ff) | Dec 10, 2022 |
| Dell          | Inspiron 1545               | [31ad9ff6a7](https://linux-hardware.org/?probe=31ad9ff6a7) | Dec 10, 2022 |
| Dell          | Inspiron 1545               | [f147df85e6](https://linux-hardware.org/?probe=f147df85e6) | Dec 10, 2022 |
| Dell          | Inspiron 13-5378            | [2a7d96e2eb](https://linux-hardware.org/?probe=2a7d96e2eb) | Dec 10, 2022 |
| HP            | ENVY Notebook               | [a51327749c](https://linux-hardware.org/?probe=a51327749c) | Dec 10, 2022 |
| HP            | EliteBook 840 G1            | [350102190e](https://linux-hardware.org/?probe=350102190e) | Dec 10, 2022 |
| HP            | EliteBook 840 G1            | [688e981eee](https://linux-hardware.org/?probe=688e981eee) | Dec 10, 2022 |
| Acer          | Aspire ES1-512              | [c9313e3820](https://linux-hardware.org/?probe=c9313e3820) | Dec 10, 2022 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | [829b36bf0f](https://linux-hardware.org/?probe=829b36bf0f) | Dec 10, 2022 |
| Lenovo        | ThinkPad T510 4349WHC       | [290bcc9d81](https://linux-hardware.org/?probe=290bcc9d81) | Dec 10, 2022 |
| HP            | ZBook 15 G3                 | [798cc5d6fa](https://linux-hardware.org/?probe=798cc5d6fa) | Dec 10, 2022 |
| ASUSTek       | K75VM                       | [dcf550e3ae](https://linux-hardware.org/?probe=dcf550e3ae) | Dec 10, 2022 |
| ASUSTek       | K75VM                       | [3dd374de1a](https://linux-hardware.org/?probe=3dd374de1a) | Dec 09, 2022 |
| Google        | Babytiger                   | [eccc497375](https://linux-hardware.org/?probe=eccc497375) | Dec 09, 2022 |
| Lenovo        | Flex 2-15 20405             | [34e9561e23](https://linux-hardware.org/?probe=34e9561e23) | Dec 09, 2022 |
| Google        | Babytiger                   | [8a865ee5c3](https://linux-hardware.org/?probe=8a865ee5c3) | Dec 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [ed7cb7fb48](https://linux-hardware.org/?probe=ed7cb7fb48) | Dec 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [18b2579f75](https://linux-hardware.org/?probe=18b2579f75) | Dec 09, 2022 |
| MSI           | GP66 Leopard 11UG           | [daffbd93fb](https://linux-hardware.org/?probe=daffbd93fb) | Dec 09, 2022 |
| Dell          | Latitude 7390               | [79812ceedd](https://linux-hardware.org/?probe=79812ceedd) | Dec 09, 2022 |
| Acer          | Swift SF314-511             | [c3c6c2f4fc](https://linux-hardware.org/?probe=c3c6c2f4fc) | Dec 09, 2022 |
| Samsung       | 530U3C/530U4C/532U3C        | [63e4c154a2](https://linux-hardware.org/?probe=63e4c154a2) | Dec 09, 2022 |
| Google        | Chell                       | [8719579038](https://linux-hardware.org/?probe=8719579038) | Dec 09, 2022 |
| MSI           | GF72 8RD                    | [f943786d2c](https://linux-hardware.org/?probe=f943786d2c) | Dec 09, 2022 |
| Google        | Blooglet                    | [241c0f4331](https://linux-hardware.org/?probe=241c0f4331) | Dec 09, 2022 |
| Acer          | TravelMate B117-M           | [00ff19b078](https://linux-hardware.org/?probe=00ff19b078) | Dec 08, 2022 |
| Notebook      | P65_P67SA                   | [4f79e1d964](https://linux-hardware.org/?probe=4f79e1d964) | Dec 08, 2022 |
| Acer          | Swift SF515-51T             | [6c3140ce31](https://linux-hardware.org/?probe=6c3140ce31) | Dec 08, 2022 |
| Toshiba       | Satellite S70-A             | [fa940c8e7a](https://linux-hardware.org/?probe=fa940c8e7a) | Dec 08, 2022 |
| Google        | Nami                        | [9861d341a7](https://linux-hardware.org/?probe=9861d341a7) | Dec 08, 2022 |
| Google        | Auron_Paine                 | [b920aea233](https://linux-hardware.org/?probe=b920aea233) | Dec 08, 2022 |
| Lenovo        | ThinkPad T510 4349WHC       | [fd6203739f](https://linux-hardware.org/?probe=fd6203739f) | Dec 08, 2022 |
| Alienware     | M17xR4                      | [49d5102ce9](https://linux-hardware.org/?probe=49d5102ce9) | Dec 08, 2022 |
| HP            | EliteBook 8730w             | [780eecb7f6](https://linux-hardware.org/?probe=780eecb7f6) | Dec 08, 2022 |
| HP            | Laptop 17-by3xxx            | [2f1a22d949](https://linux-hardware.org/?probe=2f1a22d949) | Dec 08, 2022 |
| Apple         | MacBookPro6,1               | [6bb486dbb5](https://linux-hardware.org/?probe=6bb486dbb5) | Dec 07, 2022 |
| Lenovo        | B71-80 80RJ                 | [b08283f242](https://linux-hardware.org/?probe=b08283f242) | Dec 07, 2022 |
| ASUSTek       | N55SF                       | [cfb7b0f7ad](https://linux-hardware.org/?probe=cfb7b0f7ad) | Dec 07, 2022 |
| Apple         | MacBookPro12,1              | [e15b555b1a](https://linux-hardware.org/?probe=e15b555b1a) | Dec 07, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | [bf8647ecdc](https://linux-hardware.org/?probe=bf8647ecdc) | Dec 07, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | [dfc7911df2](https://linux-hardware.org/?probe=dfc7911df2) | Dec 07, 2022 |
| Apple         | MacBookPro9,2               | [27dc9420ed](https://linux-hardware.org/?probe=27dc9420ed) | Dec 07, 2022 |
| Apple         | MacBookPro9,2               | [9b7c1953a6](https://linux-hardware.org/?probe=9b7c1953a6) | Dec 07, 2022 |
| Lenovo        | ThinkPad T510 4349WHC       | [8ddc2eef9c](https://linux-hardware.org/?probe=8ddc2eef9c) | Dec 07, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [db53a5df72](https://linux-hardware.org/?probe=db53a5df72) | Dec 07, 2022 |
| Acer          | Swift SF314-42              | [4c5be8eaf3](https://linux-hardware.org/?probe=4c5be8eaf3) | Dec 07, 2022 |
| Lenovo        | ThinkPad X270 20HN001NUS    | [249d7f1263](https://linux-hardware.org/?probe=249d7f1263) | Dec 07, 2022 |
| HP            | Notebook                    | [37eead7e86](https://linux-hardware.org/?probe=37eead7e86) | Dec 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [388bcfc8e6](https://linux-hardware.org/?probe=388bcfc8e6) | Dec 07, 2022 |
| Lenovo        | G570 20079                  | [4f31a3f1b9](https://linux-hardware.org/?probe=4f31a3f1b9) | Dec 07, 2022 |
| Lenovo        | G570 20079                  | [e17df2feb2](https://linux-hardware.org/?probe=e17df2feb2) | Dec 07, 2022 |
| Dell          | Inspiron 7720               | [180d05d4c1](https://linux-hardware.org/?probe=180d05d4c1) | Dec 06, 2022 |
| Apple         | MacBookPro6,1               | [68fa42c5f5](https://linux-hardware.org/?probe=68fa42c5f5) | Dec 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [ce36965c1f](https://linux-hardware.org/?probe=ce36965c1f) | Dec 06, 2022 |
| Lenovo        | ThinkPad P17 Gen 1 20SN0... | [3327de3dc5](https://linux-hardware.org/?probe=3327de3dc5) | Dec 06, 2022 |
| Apple         | MacBook4,1                  | [109d33ef14](https://linux-hardware.org/?probe=109d33ef14) | Dec 06, 2022 |
| Acer          | Aspire A515-51G             | [10f8aab734](https://linux-hardware.org/?probe=10f8aab734) | Dec 06, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [87d3ead3ba](https://linux-hardware.org/?probe=87d3ead3ba) | Dec 06, 2022 |
| MSI           | Pulse GL66 12UEK            | [ea01a2005e](https://linux-hardware.org/?probe=ea01a2005e) | Dec 06, 2022 |
| Lenovo        | ThinkPad T460 20FMS2291X    | [312119ddbd](https://linux-hardware.org/?probe=312119ddbd) | Dec 06, 2022 |
| Dell          | Latitude E6440              | [425331326b](https://linux-hardware.org/?probe=425331326b) | Dec 06, 2022 |
| Dell          | Latitude E5430 vPro         | [9ccc3c8d05](https://linux-hardware.org/?probe=9ccc3c8d05) | Dec 06, 2022 |
| Dell          | Latitude E6420              | [3d516c4ca3](https://linux-hardware.org/?probe=3d516c4ca3) | Dec 06, 2022 |
| Acer          | Swift SF313-52              | [3dfa942513](https://linux-hardware.org/?probe=3dfa942513) | Dec 06, 2022 |
| Acer          | Aspire F5-573               | [c5f8c3ee20](https://linux-hardware.org/?probe=c5f8c3ee20) | Dec 06, 2022 |
| MSI           | Pulse GL66 12UEK            | [4438c9636c](https://linux-hardware.org/?probe=4438c9636c) | Dec 06, 2022 |
| HP            | EliteBook 2560p             | [bbe22c0ea7](https://linux-hardware.org/?probe=bbe22c0ea7) | Dec 06, 2022 |
| HP            | ProBook 650 G1              | [d080bb3fe0](https://linux-hardware.org/?probe=d080bb3fe0) | Dec 05, 2022 |
| HP            | ProBook 650 G1              | [8e3bfa4f20](https://linux-hardware.org/?probe=8e3bfa4f20) | Dec 05, 2022 |
| Acidanther... | MacBookPro16,1              | [10e08ba745](https://linux-hardware.org/?probe=10e08ba745) | Dec 05, 2022 |
| Google        | Chell                       | [3ffe532315](https://linux-hardware.org/?probe=3ffe532315) | Dec 05, 2022 |
| Dynabook      | PORTEGE X40-J               | [3f1fc426b0](https://linux-hardware.org/?probe=3f1fc426b0) | Dec 05, 2022 |
| HP            | Pavilion g6                 | [d2b43c2803](https://linux-hardware.org/?probe=d2b43c2803) | Dec 05, 2022 |
| Dell          | Inspiron 15-3567            | [ab7d61cced](https://linux-hardware.org/?probe=ab7d61cced) | Dec 05, 2022 |
| HP            | EliteBook 2560p             | [21462d212f](https://linux-hardware.org/?probe=21462d212f) | Dec 05, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [d632edc927](https://linux-hardware.org/?probe=d632edc927) | Dec 05, 2022 |
| Acer          | One Z1401                   | [835ad73eff](https://linux-hardware.org/?probe=835ad73eff) | Dec 05, 2022 |
| HP            | EliteBook 840 G2            | [ff90421b87](https://linux-hardware.org/?probe=ff90421b87) | Dec 05, 2022 |
| HP            | EliteBook 840 G1            | [3bc6ea9cfa](https://linux-hardware.org/?probe=3bc6ea9cfa) | Dec 05, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [412bffea3b](https://linux-hardware.org/?probe=412bffea3b) | Dec 05, 2022 |
| HP            | EliteBook 840 G1            | [aaed16d626](https://linux-hardware.org/?probe=aaed16d626) | Dec 05, 2022 |
| HP            | EliteBook 840 G2            | [cd63efdbd4](https://linux-hardware.org/?probe=cd63efdbd4) | Dec 05, 2022 |
| ASUSTek       | X555LJ                      | [a849daba2b](https://linux-hardware.org/?probe=a849daba2b) | Dec 05, 2022 |
| Acer          | Aspire V3-772               | [942312fe9e](https://linux-hardware.org/?probe=942312fe9e) | Dec 05, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [2ac449d25f](https://linux-hardware.org/?probe=2ac449d25f) | Dec 05, 2022 |
| Lenovo        | Flex 2-15 20405             | [f1d48bd497](https://linux-hardware.org/?probe=f1d48bd497) | Dec 05, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [d74f52b716](https://linux-hardware.org/?probe=d74f52b716) | Dec 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [7a802a74b7](https://linux-hardware.org/?probe=7a802a74b7) | Dec 04, 2022 |
| Lenovo        | ThinkPad T450 20BUS00700    | [141e7e9992](https://linux-hardware.org/?probe=141e7e9992) | Dec 04, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | [8d5c8e8f4d](https://linux-hardware.org/?probe=8d5c8e8f4d) | Dec 04, 2022 |
| HP            | Laptop 17-ca0xxx            | [eea07d92b7](https://linux-hardware.org/?probe=eea07d92b7) | Dec 04, 2022 |
| Dell          | Latitude 7290               | [3f0e476980](https://linux-hardware.org/?probe=3f0e476980) | Dec 04, 2022 |
| ASUSTek       | X750JN                      | [af27460f17](https://linux-hardware.org/?probe=af27460f17) | Dec 04, 2022 |
| Google        | Lars                        | [efe9cef4b9](https://linux-hardware.org/?probe=efe9cef4b9) | Dec 04, 2022 |
| Samsung       | 270E5J/2570EJ               | [084c39f0b7](https://linux-hardware.org/?probe=084c39f0b7) | Dec 04, 2022 |
| Toshiba       | Satellite A210              | [05f690559c](https://linux-hardware.org/?probe=05f690559c) | Dec 03, 2022 |
| Toshiba       | Satellite A210              | [b911bfbb6c](https://linux-hardware.org/?probe=b911bfbb6c) | Dec 03, 2022 |
| Lenovo        | Flex 2-15 20405             | [1c7a361986](https://linux-hardware.org/?probe=1c7a361986) | Dec 03, 2022 |
| SGIN          | laptop                      | [1c676d77ee](https://linux-hardware.org/?probe=1c676d77ee) | Dec 03, 2022 |
| Acer          | Aspire A315-59              | [abc4c3e5c6](https://linux-hardware.org/?probe=abc4c3e5c6) | Dec 03, 2022 |
| Acer          | Aspire E5-575G              | [dddc2b5f29](https://linux-hardware.org/?probe=dddc2b5f29) | Dec 03, 2022 |
| HP            | 250 G8 Notebook PC          | [f6bba1c80e](https://linux-hardware.org/?probe=f6bba1c80e) | Dec 03, 2022 |
| Google        | Lars                        | [ad022bfd93](https://linux-hardware.org/?probe=ad022bfd93) | Dec 03, 2022 |
| HP            | Pavilion 15                 | [87de142ecd](https://linux-hardware.org/?probe=87de142ecd) | Dec 03, 2022 |
| Lenovo        | ThinkPad T440p 20AWS17N0... | [716a6802ca](https://linux-hardware.org/?probe=716a6802ca) | Dec 03, 2022 |
| Acer          | TravelMate B117-M           | [0b86a9c3b9](https://linux-hardware.org/?probe=0b86a9c3b9) | Dec 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [c0f7c4b788](https://linux-hardware.org/?probe=c0f7c4b788) | Dec 03, 2022 |
| Sony          | SVE14A18ECH                 | [4ea36d0512](https://linux-hardware.org/?probe=4ea36d0512) | Dec 03, 2022 |
| Google        | Blooglet                    | [045f75ab43](https://linux-hardware.org/?probe=045f75ab43) | Dec 03, 2022 |
| ONE-NETBOO... | One-Mix3 Pro                | [1ae0144b92](https://linux-hardware.org/?probe=1ae0144b92) | Dec 03, 2022 |
| HP            | Laptop 14-dk0xxx            | [0b2fa11453](https://linux-hardware.org/?probe=0b2fa11453) | Dec 03, 2022 |
| Dell          | System XPS L502X            | [16dd4457fb](https://linux-hardware.org/?probe=16dd4457fb) | Dec 03, 2022 |
| Dell          | G15 5515                    | [218e5c2825](https://linux-hardware.org/?probe=218e5c2825) | Dec 03, 2022 |
| Lenovo        | G580 2189                   | [80fe3f7171](https://linux-hardware.org/?probe=80fe3f7171) | Dec 03, 2022 |
| Dell          | Inspiron 15-7568            | [9887f68589](https://linux-hardware.org/?probe=9887f68589) | Dec 03, 2022 |
| Apple         | MacBook7,1                  | [2ac1c5691b](https://linux-hardware.org/?probe=2ac1c5691b) | Dec 02, 2022 |
| Dell          | Vostro 5502                 | [86341e8306](https://linux-hardware.org/?probe=86341e8306) | Dec 02, 2022 |
| Lenovo        | ThinkPad R400 7439UN4       | [45ab8bdd27](https://linux-hardware.org/?probe=45ab8bdd27) | Dec 02, 2022 |
| HP            | Stream Notebook             | [dc16cc5c95](https://linux-hardware.org/?probe=dc16cc5c95) | Dec 02, 2022 |
| Dell          | Latitude E5530 non-vPro     | [fe5fd075f2](https://linux-hardware.org/?probe=fe5fd075f2) | Dec 02, 2022 |
| Dell          | Latitude E5530 non-vPro     | [476f1de597](https://linux-hardware.org/?probe=476f1de597) | Dec 02, 2022 |
| HP            | ProBook 6550b               | [564bf050f2](https://linux-hardware.org/?probe=564bf050f2) | Dec 02, 2022 |
| Lenovo        | B590 20208                  | [367c0f8907](https://linux-hardware.org/?probe=367c0f8907) | Dec 02, 2022 |
| MSI           | GL73 8RC                    | [3e35cfb524](https://linux-hardware.org/?probe=3e35cfb524) | Dec 02, 2022 |
| HP            | ENVY Notebook               | [0c514cccfb](https://linux-hardware.org/?probe=0c514cccfb) | Dec 02, 2022 |
| Dell          | Latitude E6410              | [92bae2f9d5](https://linux-hardware.org/?probe=92bae2f9d5) | Dec 02, 2022 |
| TUXEDO        | Book BA1510                 | [0e6c8cb124](https://linux-hardware.org/?probe=0e6c8cb124) | Dec 02, 2022 |
| LG Electro... | 17Z90Q-G.AA79G              | [4ebebe7785](https://linux-hardware.org/?probe=4ebebe7785) | Dec 01, 2022 |
| HP            | Stream Laptop 14-cb1XX      | [e8ecfcc3cd](https://linux-hardware.org/?probe=e8ecfcc3cd) | Dec 01, 2022 |
| MSI           | GF72 8RD                    | [c03f783ea5](https://linux-hardware.org/?probe=c03f783ea5) | Dec 01, 2022 |
| HP            | Stream Laptop 14-cb1XX      | [80c9d45a14](https://linux-hardware.org/?probe=80c9d45a14) | Dec 01, 2022 |
| Packard Be... | DOT S                       | [bb05d9a173](https://linux-hardware.org/?probe=bb05d9a173) | Dec 01, 2022 |
| Acer          | Aspire 3830TG               | [8bb246cbaa](https://linux-hardware.org/?probe=8bb246cbaa) | Dec 01, 2022 |
| Acer          | Aspire 3830TG               | [46bcb20e26](https://linux-hardware.org/?probe=46bcb20e26) | Dec 01, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | [5b22a7d584](https://linux-hardware.org/?probe=5b22a7d584) | Dec 01, 2022 |
| Lenovo        | ThinkPad T420 4236V6S       | [5900d34c9a](https://linux-hardware.org/?probe=5900d34c9a) | Dec 01, 2022 |
| Lenovo        | ThinkPad L560 20F10034MX    | [34842eb8d9](https://linux-hardware.org/?probe=34842eb8d9) | Dec 01, 2022 |
| Mediacom      | SmartBook 14 FullHD - SB... | [1df1f552ff](https://linux-hardware.org/?probe=1df1f552ff) | Dec 01, 2022 |
| Acer          | Aspire 5750G                | [a8236e24a5](https://linux-hardware.org/?probe=a8236e24a5) | Dec 01, 2022 |
| Dell          | Latitude E7470              | [457187e169](https://linux-hardware.org/?probe=457187e169) | Dec 01, 2022 |
| Acer          | Aspire 5750G                | [198d7f2534](https://linux-hardware.org/?probe=198d7f2534) | Dec 01, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [65fa0de0a2](https://linux-hardware.org/?probe=65fa0de0a2) | Dec 01, 2022 |
| Dell          | Latitude E7240              | [0945377dfb](https://linux-hardware.org/?probe=0945377dfb) | Dec 01, 2022 |
| In-Sing       | NK81J                       | [bca0a3709f](https://linux-hardware.org/?probe=bca0a3709f) | Dec 01, 2022 |
| Dell          | Latitude E7470              | [b24884fe44](https://linux-hardware.org/?probe=b24884fe44) | Dec 01, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | [19c2f41d14](https://linux-hardware.org/?probe=19c2f41d14) | Dec 01, 2022 |
| Apple         | MacBookPro11,4              | [138689463a](https://linux-hardware.org/?probe=138689463a) | Dec 01, 2022 |
| GPU Compan... | GWTC116-2                   | [d004be9ab6](https://linux-hardware.org/?probe=d004be9ab6) | Dec 01, 2022 |
| Apple         | MacBookPro11,4              | [16d0cef78c](https://linux-hardware.org/?probe=16d0cef78c) | Dec 01, 2022 |
| Dell          | Inspiron MM061              | [703ef1c899](https://linux-hardware.org/?probe=703ef1c899) | Nov 30, 2022 |
| HUAWEI        | KLVL-WXX9                   | [ea8b9066f6](https://linux-hardware.org/?probe=ea8b9066f6) | Nov 30, 2022 |
| Lenovo        | IdeaPad 310-15IAP 80TT      | [3aa3302b92](https://linux-hardware.org/?probe=3aa3302b92) | Nov 30, 2022 |
| HP            | ElitePad 1000 G2            | [0b05465735](https://linux-hardware.org/?probe=0b05465735) | Nov 30, 2022 |
| Acer          | Aspire A315-34              | [6bf371252b](https://linux-hardware.org/?probe=6bf371252b) | Nov 30, 2022 |
| GPU Compan... | GWTN156-2BK                 | [1ed3629f61](https://linux-hardware.org/?probe=1ed3629f61) | Nov 30, 2022 |
| HP            | ZBook 15v G5                | [aabc35ae2a](https://linux-hardware.org/?probe=aabc35ae2a) | Nov 30, 2022 |
| Dell          | Latitude E6440              | [0c3dd709dd](https://linux-hardware.org/?probe=0c3dd709dd) | Nov 30, 2022 |
| Acer          | Aspire E5-575G              | [1ca5144296](https://linux-hardware.org/?probe=1ca5144296) | Nov 30, 2022 |
| Acer          | Aspire E5-575               | [b393262562](https://linux-hardware.org/?probe=b393262562) | Nov 30, 2022 |
| GPU Compan... | GWTN156-2BK                 | [dbba08e68e](https://linux-hardware.org/?probe=dbba08e68e) | Nov 30, 2022 |
| Tactus        | GeoBook 140                 | [91342e56df](https://linux-hardware.org/?probe=91342e56df) | Nov 29, 2022 |
| Acer          | Aspire A315-34              | [56bb76fb28](https://linux-hardware.org/?probe=56bb76fb28) | Nov 29, 2022 |
| HP            | Pavilion 17                 | [431ce9bd18](https://linux-hardware.org/?probe=431ce9bd18) | Nov 29, 2022 |
| Apple         | MacBookAir8,1               | [7581ef0e85](https://linux-hardware.org/?probe=7581ef0e85) | Nov 29, 2022 |
| HUAWEI        | CREM-WXX9                   | [ddad96715a](https://linux-hardware.org/?probe=ddad96715a) | Nov 29, 2022 |
| HP            | Pavilion g6                 | [fefac15f4c](https://linux-hardware.org/?probe=fefac15f4c) | Nov 29, 2022 |
| HP            | Victus by Laptop 16-d0xx... | [dae405ee81](https://linux-hardware.org/?probe=dae405ee81) | Nov 29, 2022 |
| ASUSTek       | G751JL                      | [1bfbfafe68](https://linux-hardware.org/?probe=1bfbfafe68) | Nov 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [140872c53d](https://linux-hardware.org/?probe=140872c53d) | Nov 29, 2022 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | [687d4d78a4](https://linux-hardware.org/?probe=687d4d78a4) | Nov 29, 2022 |
| Dell          | Latitude E5440              | [90d18073d6](https://linux-hardware.org/?probe=90d18073d6) | Nov 29, 2022 |
| HP            | Laptop 14s-fq0xxx           | [e71c023456](https://linux-hardware.org/?probe=e71c023456) | Nov 29, 2022 |
| Thomson       | N17V3C8WH512                | [b89cd0328a](https://linux-hardware.org/?probe=b89cd0328a) | Nov 29, 2022 |
| AMI           | Intel                       | [3e2e312c6e](https://linux-hardware.org/?probe=3e2e312c6e) | Nov 29, 2022 |
| Acer          | Aspire A315-22              | [c52689296b](https://linux-hardware.org/?probe=c52689296b) | Nov 29, 2022 |
| Unknown       | Unknown                     | [d2789773ef](https://linux-hardware.org/?probe=d2789773ef) | Nov 29, 2022 |
| Acer          | Aspire A315-59              | [f7a1cff386](https://linux-hardware.org/?probe=f7a1cff386) | Nov 28, 2022 |
| Chuwi         | HeroBook Pro                | [df7f48022d](https://linux-hardware.org/?probe=df7f48022d) | Nov 28, 2022 |
| Chuwi         | HeroBook Pro                | [c8e48e2c0f](https://linux-hardware.org/?probe=c8e48e2c0f) | Nov 28, 2022 |
| Lenovo        | G700 20251                  | [49167f9f67](https://linux-hardware.org/?probe=49167f9f67) | Nov 28, 2022 |
| Unknown       | Unknown                     | [390854c8dd](https://linux-hardware.org/?probe=390854c8dd) | Nov 28, 2022 |
| HP            | EliteBook Folio 9480m       | [7f9d229259](https://linux-hardware.org/?probe=7f9d229259) | Nov 28, 2022 |
| ASUSTek       | X453MA                      | [f30a5c4808](https://linux-hardware.org/?probe=f30a5c4808) | Nov 28, 2022 |
| HP            | 255 G6 Notebook PC          | [e17172d1c5](https://linux-hardware.org/?probe=e17172d1c5) | Nov 28, 2022 |
| Dell          | Latitude E6320              | [bcbdb4bf67](https://linux-hardware.org/?probe=bcbdb4bf67) | Nov 28, 2022 |
| Dell          | Latitude E6320              | [f77e444066](https://linux-hardware.org/?probe=f77e444066) | Nov 28, 2022 |
| Acer          | TravelMate B113             | [567c2d2e20](https://linux-hardware.org/?probe=567c2d2e20) | Nov 28, 2022 |
| HUAWEI        | BOD-WXX9                    | [5b2f9bfd5c](https://linux-hardware.org/?probe=5b2f9bfd5c) | Nov 28, 2022 |
| Dell          | Latitude E6420              | [15ee6e2e20](https://linux-hardware.org/?probe=15ee6e2e20) | Nov 28, 2022 |
| Lenovo        | Flex 2-15 20405             | [7e37de4475](https://linux-hardware.org/?probe=7e37de4475) | Nov 28, 2022 |
| Dell          | Latitude E6420              | [251fb963fe](https://linux-hardware.org/?probe=251fb963fe) | Nov 28, 2022 |
| ASUSTek       | TUF Gaming FX705GM_FX705... | [3515e0a362](https://linux-hardware.org/?probe=3515e0a362) | Nov 27, 2022 |
| Lenovo        | S20-30 Touch 20434          | [63d2134051](https://linux-hardware.org/?probe=63d2134051) | Nov 27, 2022 |
| HP            | EliteBook 8460p             | [a39632439e](https://linux-hardware.org/?probe=a39632439e) | Nov 27, 2022 |
| HP            | ENVY Laptop 17-ce1xxx       | [60c25a49bc](https://linux-hardware.org/?probe=60c25a49bc) | Nov 27, 2022 |
| Unknown       | Unknown                     | [9e16a80342](https://linux-hardware.org/?probe=9e16a80342) | Nov 27, 2022 |
| Jumper        | EZbook                      | [a93aa75e5f](https://linux-hardware.org/?probe=a93aa75e5f) | Nov 27, 2022 |
| ASUSTek       | E402SA                      | [05983f8566](https://linux-hardware.org/?probe=05983f8566) | Nov 26, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [7a5c0ebf68](https://linux-hardware.org/?probe=7a5c0ebf68) | Nov 26, 2022 |
| MSI           | GF72 8RD                    | [fb92041c1b](https://linux-hardware.org/?probe=fb92041c1b) | Nov 26, 2022 |
| Lenovo        | ThinkPad X1 Carbon 34601... | [ed678da106](https://linux-hardware.org/?probe=ed678da106) | Nov 26, 2022 |
| Lenovo        | ThinkPad T460s 20FAS4KH0... | [585b6910fa](https://linux-hardware.org/?probe=585b6910fa) | Nov 26, 2022 |
| Lenovo        | ThinkPad T460s 20FAS4KH0... | [138231da75](https://linux-hardware.org/?probe=138231da75) | Nov 26, 2022 |
| ASUSTek       | T100TA                      | [2734591eb0](https://linux-hardware.org/?probe=2734591eb0) | Nov 26, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | [694d1d5e96](https://linux-hardware.org/?probe=694d1d5e96) | Nov 26, 2022 |
| Lenovo        | G40-80 80JE                 | [47d9a5f1ca](https://linux-hardware.org/?probe=47d9a5f1ca) | Nov 26, 2022 |
| Lenovo        | G40-80 80JE                 | [5d324af4d0](https://linux-hardware.org/?probe=5d324af4d0) | Nov 26, 2022 |
| Acer          | Nitro AN515-54              | [e82fa602d4](https://linux-hardware.org/?probe=e82fa602d4) | Nov 26, 2022 |
| Acer          | Nitro AN515-54              | [604339bd15](https://linux-hardware.org/?probe=604339bd15) | Nov 26, 2022 |
| HP            | OMEN by Laptop 15t-ek000    | [4189c96f5e](https://linux-hardware.org/?probe=4189c96f5e) | Nov 26, 2022 |
| HP            | Pavilion ZV6100 (EC356UA... | [c6fcc7764f](https://linux-hardware.org/?probe=c6fcc7764f) | Nov 26, 2022 |
| Samsung       | RV410/RV510/S3510/E3510     | [cd5eb0566d](https://linux-hardware.org/?probe=cd5eb0566d) | Nov 26, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | [b669fa97c4](https://linux-hardware.org/?probe=b669fa97c4) | Nov 26, 2022 |
| Samsung       | RC530/RC730                 | [64515ff8b1](https://linux-hardware.org/?probe=64515ff8b1) | Nov 26, 2022 |
| MSI           | GE62 2QC                    | [6bdf66b3b6](https://linux-hardware.org/?probe=6bdf66b3b6) | Nov 26, 2022 |
| MSI           | MS-16G1                     | [8d8233d2a9](https://linux-hardware.org/?probe=8d8233d2a9) | Nov 25, 2022 |
| Acer          | Aspire 5349                 | [82be349d91](https://linux-hardware.org/?probe=82be349d91) | Nov 25, 2022 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | [02eeb74e28](https://linux-hardware.org/?probe=02eeb74e28) | Nov 25, 2022 |
| HP            | ProBook 450 G6              | [d044aabfec](https://linux-hardware.org/?probe=d044aabfec) | Nov 25, 2022 |
| HP            | Pavilion Laptop 15-ck0xx    | [4393448090](https://linux-hardware.org/?probe=4393448090) | Nov 25, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [90fcc2d8d5](https://linux-hardware.org/?probe=90fcc2d8d5) | Nov 24, 2022 |
| Alienware     | M17xR3                      | [438f3639aa](https://linux-hardware.org/?probe=438f3639aa) | Nov 24, 2022 |
| Dell          | Inspiron 15 3520            | [7c53fcc73b](https://linux-hardware.org/?probe=7c53fcc73b) | Nov 24, 2022 |
| Dell          | Latitude E6540              | [5c474a2cdb](https://linux-hardware.org/?probe=5c474a2cdb) | Nov 24, 2022 |
| Lenovo        | Flex 2-15 20405             | [054a6670b3](https://linux-hardware.org/?probe=054a6670b3) | Nov 24, 2022 |
| HP            | Laptop 15-dw0xxx            | [894c4e9ebf](https://linux-hardware.org/?probe=894c4e9ebf) | Nov 24, 2022 |
| Dell          | Latitude E6440              | [21d39df616](https://linux-hardware.org/?probe=21d39df616) | Nov 24, 2022 |
| Acer          | Aspire R3-131T              | [5395a2556c](https://linux-hardware.org/?probe=5395a2556c) | Nov 24, 2022 |
| Aquarius      | NS685U R11                  | [0a9856bad0](https://linux-hardware.org/?probe=0a9856bad0) | Nov 24, 2022 |
| Lenovo        | ThinkPad T460 20FMS0VG25    | [06221c9746](https://linux-hardware.org/?probe=06221c9746) | Nov 24, 2022 |
| Razer         | Blade Stealth               | [98889c6c3e](https://linux-hardware.org/?probe=98889c6c3e) | Nov 23, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [6646978243](https://linux-hardware.org/?probe=6646978243) | Nov 23, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [ddcb37ea55](https://linux-hardware.org/?probe=ddcb37ea55) | Nov 23, 2022 |
| Apple         | MacBookAir7,1               | [f735b3e731](https://linux-hardware.org/?probe=f735b3e731) | Nov 23, 2022 |
| Lenovo        | ThinkPad T460 20FMS0VG25    | [b00a1e7f6a](https://linux-hardware.org/?probe=b00a1e7f6a) | Nov 23, 2022 |
| HP            | EliteBook 2560p             | [4c27c5511f](https://linux-hardware.org/?probe=4c27c5511f) | Nov 23, 2022 |
| Lenovo        | ThinkPad P15v Gen 3 21D9... | [f02593fc75](https://linux-hardware.org/?probe=f02593fc75) | Nov 23, 2022 |
| Dell          | Inspiron 5567               | [96e8bf5249](https://linux-hardware.org/?probe=96e8bf5249) | Nov 23, 2022 |
| HP            | Pavilion dv7                | [aa62e3eea2](https://linux-hardware.org/?probe=aa62e3eea2) | Nov 23, 2022 |
| Dell          | G3 3579                     | [7f4d27ea26](https://linux-hardware.org/?probe=7f4d27ea26) | Nov 23, 2022 |
| Dell          | Latitude E5440              | [9a39d45cee](https://linux-hardware.org/?probe=9a39d45cee) | Nov 22, 2022 |
| Lenovo        | ThinkPad T450 20BUS08L00    | [080bbeb75a](https://linux-hardware.org/?probe=080bbeb75a) | Nov 22, 2022 |
| Lenovo        | ThinkPad T450 20BUS08L00    | [31ddbc5ee3](https://linux-hardware.org/?probe=31ddbc5ee3) | Nov 22, 2022 |
| HP            | Pavilion dv5                | [2a497ff54f](https://linux-hardware.org/?probe=2a497ff54f) | Nov 22, 2022 |
| HP            | Notebook                    | [ab824250b9](https://linux-hardware.org/?probe=ab824250b9) | Nov 22, 2022 |
| Dell          | Latitude 5480               | [5b9f1e717c](https://linux-hardware.org/?probe=5b9f1e717c) | Nov 21, 2022 |
| Acer          | TravelMate 5760             | [54c460334e](https://linux-hardware.org/?probe=54c460334e) | Nov 21, 2022 |
| ASUSTek       | E200HA                      | [635e9fe863](https://linux-hardware.org/?probe=635e9fe863) | Nov 21, 2022 |
| Lenovo        | ThinkPad T450 20BUA0AEIG    | [48956b6f61](https://linux-hardware.org/?probe=48956b6f61) | Nov 21, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [c3048ea26d](https://linux-hardware.org/?probe=c3048ea26d) | Nov 21, 2022 |
| HP            | EliteBook 840 G5            | [62ffc22eea](https://linux-hardware.org/?probe=62ffc22eea) | Nov 21, 2022 |
| HP            | Pavilion Notebook           | [9599fd68a9](https://linux-hardware.org/?probe=9599fd68a9) | Nov 21, 2022 |
| Lenovo        | ThinkPad T440 20B7000LGE    | [9194594686](https://linux-hardware.org/?probe=9194594686) | Nov 21, 2022 |
| Dell          | Latitude E5440              | [6d90726959](https://linux-hardware.org/?probe=6d90726959) | Nov 21, 2022 |
| Toshiba       | IS 1422                     | [aa59e6576d](https://linux-hardware.org/?probe=aa59e6576d) | Nov 21, 2022 |
| MSI           | CX700                       | [69c6ae1f04](https://linux-hardware.org/?probe=69c6ae1f04) | Nov 20, 2022 |
| HP            | 15                          | [51711b792f](https://linux-hardware.org/?probe=51711b792f) | Nov 20, 2022 |
| HP            | Pavilion 17                 | [fb907a2d35](https://linux-hardware.org/?probe=fb907a2d35) | Nov 20, 2022 |
| Lenovo        | Z50-70 20354                | [4de72c5631](https://linux-hardware.org/?probe=4de72c5631) | Nov 20, 2022 |
| HP            | Pavilion 17                 | [7af6f3d045](https://linux-hardware.org/?probe=7af6f3d045) | Nov 20, 2022 |
| HP            | EliteBook 830 G7 Noteboo... | [1b60e76184](https://linux-hardware.org/?probe=1b60e76184) | Nov 20, 2022 |
| HP            | ENVY Laptop 13-ba1xxx       | [4a270e871f](https://linux-hardware.org/?probe=4a270e871f) | Nov 20, 2022 |
| ASUSTek       | F5VL                        | [05614f05b7](https://linux-hardware.org/?probe=05614f05b7) | Nov 20, 2022 |
| ASUSTek       | F5VL                        | [a95f905ff3](https://linux-hardware.org/?probe=a95f905ff3) | Nov 20, 2022 |
| GPU Compan... | GWTN156-2BK                 | [ed63205687](https://linux-hardware.org/?probe=ed63205687) | Nov 20, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [d8f53f887a](https://linux-hardware.org/?probe=d8f53f887a) | Nov 20, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c967893dd4](https://linux-hardware.org/?probe=c967893dd4) | Nov 20, 2022 |
| HP            | ZBook 15 G4                 | [ad20223c29](https://linux-hardware.org/?probe=ad20223c29) | Nov 20, 2022 |
| Samsung       | RC410/RC510/RC710           | [06a337fda3](https://linux-hardware.org/?probe=06a337fda3) | Nov 20, 2022 |
| Samsung       | RC410/RC510/RC710           | [965d9d2f5c](https://linux-hardware.org/?probe=965d9d2f5c) | Nov 20, 2022 |
| Irbis         | NB121                       | [32a784f767](https://linux-hardware.org/?probe=32a784f767) | Nov 20, 2022 |
| ASUSTek       | K50IJ                       | [c57a9ae3d5](https://linux-hardware.org/?probe=c57a9ae3d5) | Nov 19, 2022 |
| Apple         | MacBookPro5,1               | [4f04b7d627](https://linux-hardware.org/?probe=4f04b7d627) | Nov 19, 2022 |
| ASUSTek       | K50IJ                       | [99ed91b58d](https://linux-hardware.org/?probe=99ed91b58d) | Nov 19, 2022 |
| Toshiba       | Satellite L50D-B            | [68d1c8a80a](https://linux-hardware.org/?probe=68d1c8a80a) | Nov 19, 2022 |
| ASUSTek       | B451JA                      | [faeb294d65](https://linux-hardware.org/?probe=faeb294d65) | Nov 19, 2022 |
| MSI           | GP62M 7REX                  | [2125546b68](https://linux-hardware.org/?probe=2125546b68) | Nov 19, 2022 |
| Acer          | Aspire A515-44G             | [51035e77a1](https://linux-hardware.org/?probe=51035e77a1) | Nov 19, 2022 |
| Digma         | EVE 15 C423 ES5069EW        | [9737dae1ac](https://linux-hardware.org/?probe=9737dae1ac) | Nov 19, 2022 |
| MSI           | GP62M 7REX                  | [6ea684de8c](https://linux-hardware.org/?probe=6ea684de8c) | Nov 19, 2022 |
| ALLDOCUBE     | i1405S                      | [551bc2b1e6](https://linux-hardware.org/?probe=551bc2b1e6) | Nov 19, 2022 |
| Toshiba       | QOSMIO X70-A                | [75f0b58b20](https://linux-hardware.org/?probe=75f0b58b20) | Nov 19, 2022 |
| Alienware     | m15 R4                      | [2db8555d73](https://linux-hardware.org/?probe=2db8555d73) | Nov 18, 2022 |
| Acer          | Aspire V3-772G              | [bc46ec232a](https://linux-hardware.org/?probe=bc46ec232a) | Nov 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [d7992855ba](https://linux-hardware.org/?probe=d7992855ba) | Nov 18, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [ea12bf4774](https://linux-hardware.org/?probe=ea12bf4774) | Nov 18, 2022 |
| Dell          | Inspiron 3793               | [fb5878b057](https://linux-hardware.org/?probe=fb5878b057) | Nov 18, 2022 |
| HP            | Laptop 15-da2xxx            | [e55a0e2ae1](https://linux-hardware.org/?probe=e55a0e2ae1) | Nov 18, 2022 |
| HP            | Elite x2 1012 G1            | [ef366c64fe](https://linux-hardware.org/?probe=ef366c64fe) | Nov 18, 2022 |
| Samsung       | R610                        | [b6c7aa2939](https://linux-hardware.org/?probe=b6c7aa2939) | Nov 18, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [af679e6195](https://linux-hardware.org/?probe=af679e6195) | Nov 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [8e17476123](https://linux-hardware.org/?probe=8e17476123) | Nov 17, 2022 |
| Acer          | Aspire V3-371               | [b184d85960](https://linux-hardware.org/?probe=b184d85960) | Nov 17, 2022 |
| Apple         | MacBook4,1                  | [06c160b1a8](https://linux-hardware.org/?probe=06c160b1a8) | Nov 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [f48e29fef2](https://linux-hardware.org/?probe=f48e29fef2) | Nov 16, 2022 |
| Toshiba       | Satellite L10W-B-101        | [544ad40774](https://linux-hardware.org/?probe=544ad40774) | Nov 16, 2022 |
| Acer          | Aspire A315-42              | [121ed6e51d](https://linux-hardware.org/?probe=121ed6e51d) | Nov 16, 2022 |
| HP            | Pavilion dv9500             | [65a473401c](https://linux-hardware.org/?probe=65a473401c) | Nov 16, 2022 |
| Sony          | SVE14A15FBB                 | [1b368520d1](https://linux-hardware.org/?probe=1b368520d1) | Nov 16, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | [d0bcf66bd1](https://linux-hardware.org/?probe=d0bcf66bd1) | Nov 16, 2022 |
| Lenovo        | ThinkPad T440 20B6009TUS    | [57ae2fbd3c](https://linux-hardware.org/?probe=57ae2fbd3c) | Nov 16, 2022 |
| AMI           | Intel                       | [36327e3aca](https://linux-hardware.org/?probe=36327e3aca) | Nov 16, 2022 |
| HP            | Pavilion Laptop 15-eh2xx... | [21cd2084c5](https://linux-hardware.org/?probe=21cd2084c5) | Nov 16, 2022 |
| AMI           | Intel                       | [ac36a02403](https://linux-hardware.org/?probe=ac36a02403) | Nov 16, 2022 |
| Lenovo        | IdeaPad 1 14IAU7 82QC       | [12073cb314](https://linux-hardware.org/?probe=12073cb314) | Nov 16, 2022 |
| ALLDOCUBE     | i1405S                      | [f35dc553a2](https://linux-hardware.org/?probe=f35dc553a2) | Nov 16, 2022 |
| HP            | Laptop 15-da2xxx            | [b1ed3e6190](https://linux-hardware.org/?probe=b1ed3e6190) | Nov 16, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [f8eb11ba08](https://linux-hardware.org/?probe=f8eb11ba08) | Nov 15, 2022 |
| Dell          | XPS 15 9550                 | [12ec05ef8f](https://linux-hardware.org/?probe=12ec05ef8f) | Nov 15, 2022 |
| Acer          | Aspire 5742G                | [4a80ba0608](https://linux-hardware.org/?probe=4a80ba0608) | Nov 15, 2022 |
| Dell          | Inspiron N5050              | [ddc155c281](https://linux-hardware.org/?probe=ddc155c281) | Nov 15, 2022 |
| HP            | 250 G6 Notebook PC          | [439fe62e2e](https://linux-hardware.org/?probe=439fe62e2e) | Nov 15, 2022 |
| ASUSTek       | T100HAN                     | [f973b6bcd4](https://linux-hardware.org/?probe=f973b6bcd4) | Nov 15, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [b59bffff0b](https://linux-hardware.org/?probe=b59bffff0b) | Nov 15, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [e9182b2177](https://linux-hardware.org/?probe=e9182b2177) | Nov 15, 2022 |
| Dell          | Latitude E6510              | [21a6415538](https://linux-hardware.org/?probe=21a6415538) | Nov 15, 2022 |
| Dell          | Inspiron 3505               | [ce754fa34b](https://linux-hardware.org/?probe=ce754fa34b) | Nov 15, 2022 |
| Dell          | Latitude E6510              | [3ce2f9981f](https://linux-hardware.org/?probe=3ce2f9981f) | Nov 15, 2022 |
| Dell          | Latitude E7450              | [3020a4edfc](https://linux-hardware.org/?probe=3020a4edfc) | Nov 15, 2022 |
| ASUSTek       | K50IJ                       | [c7ac1636bc](https://linux-hardware.org/?probe=c7ac1636bc) | Nov 15, 2022 |
| Dell          | Inspiron 7501               | [15cd1d588f](https://linux-hardware.org/?probe=15cd1d588f) | Nov 15, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [d82617ae65](https://linux-hardware.org/?probe=d82617ae65) | Nov 15, 2022 |
| Chuwi         | GemiBook Pro                | [d9b2356cf0](https://linux-hardware.org/?probe=d9b2356cf0) | Nov 15, 2022 |
| Acer          | Aspire ES1-572              | [a21cf96dd6](https://linux-hardware.org/?probe=a21cf96dd6) | Nov 15, 2022 |
| Acer          | Aspire ES1-572              | [14e272fe11](https://linux-hardware.org/?probe=14e272fe11) | Nov 15, 2022 |
| Acer          | Aspire E5-722               | [7e26ae7fe8](https://linux-hardware.org/?probe=7e26ae7fe8) | Nov 14, 2022 |
| Dell          | Latitude E6320              | [a4767dfe35](https://linux-hardware.org/?probe=a4767dfe35) | Nov 14, 2022 |
| Acer          | Aspire A315-42              | [333067d4c6](https://linux-hardware.org/?probe=333067d4c6) | Nov 14, 2022 |
| ASUSTek       | X502CA                      | [b47b397c38](https://linux-hardware.org/?probe=b47b397c38) | Nov 14, 2022 |
| Acer          | Aspire 5600                 | [9fe2a7d245](https://linux-hardware.org/?probe=9fe2a7d245) | Nov 14, 2022 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | [ccbda507a9](https://linux-hardware.org/?probe=ccbda507a9) | Nov 14, 2022 |
| Samsung       | RV411                       | [ded212573f](https://linux-hardware.org/?probe=ded212573f) | Nov 14, 2022 |
| Toshiba       | Satellite L50D-B            | [6c53b0c32d](https://linux-hardware.org/?probe=6c53b0c32d) | Nov 14, 2022 |
| Acer          | Aspire V3-771               | [5682e576ad](https://linux-hardware.org/?probe=5682e576ad) | Nov 14, 2022 |
| Lenovo        | IdeaPad 320-17AST 80XW      | [d8e3815f50](https://linux-hardware.org/?probe=d8e3815f50) | Nov 14, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [1de723e880](https://linux-hardware.org/?probe=1de723e880) | Nov 14, 2022 |
| Lenovo        | ThinkPad T450 20BUS1S81K    | [ee3fb9c9d2](https://linux-hardware.org/?probe=ee3fb9c9d2) | Nov 14, 2022 |
| Lenovo        | G50-80 80R0                 | [35193d2431](https://linux-hardware.org/?probe=35193d2431) | Nov 14, 2022 |
| Multilaser    | PC121                       | [5870f0d565](https://linux-hardware.org/?probe=5870f0d565) | Nov 14, 2022 |
| Acer          | Aspire VN7-791              | [736c2f5664](https://linux-hardware.org/?probe=736c2f5664) | Nov 14, 2022 |
| Lenovo        | Flex 2-15 20405             | [d360e03bd5](https://linux-hardware.org/?probe=d360e03bd5) | Nov 13, 2022 |
| Lenovo        | Flex 2-15 20405             | [6024035af3](https://linux-hardware.org/?probe=6024035af3) | Nov 13, 2022 |
| HP            | EliteBook 6930p             | [4b6c28bf91](https://linux-hardware.org/?probe=4b6c28bf91) | Nov 13, 2022 |
| Lenovo        | ThinkPad L490 20Q5CTO1WW    | [575d67b22c](https://linux-hardware.org/?probe=575d67b22c) | Nov 13, 2022 |
| Medion        | E4254 MD63100               | [b38503d9ac](https://linux-hardware.org/?probe=b38503d9ac) | Nov 13, 2022 |
| HP            | Laptop 15-dw3xxx            | [146a0f987b](https://linux-hardware.org/?probe=146a0f987b) | Nov 13, 2022 |
| ASUSTek       | A6JC                        | [dce6c2a8f4](https://linux-hardware.org/?probe=dce6c2a8f4) | Nov 13, 2022 |
| Medion        | E4254 MD63100               | [bc622b98f9](https://linux-hardware.org/?probe=bc622b98f9) | Nov 13, 2022 |
| Lenovo        | ThinkPad T530 2429A11       | [f5aa671555](https://linux-hardware.org/?probe=f5aa671555) | Nov 13, 2022 |
| Lenovo        | IdeaPadFlex 14 20308        | [04a42845bf](https://linux-hardware.org/?probe=04a42845bf) | Nov 12, 2022 |
| Acer          | Aspire 3830TG               | [2ce4863890](https://linux-hardware.org/?probe=2ce4863890) | Nov 12, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [a174d2b2b3](https://linux-hardware.org/?probe=a174d2b2b3) | Nov 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [be205ddec9](https://linux-hardware.org/?probe=be205ddec9) | Nov 12, 2022 |
| Dell          | Latitude D630               | [ef49631a3c](https://linux-hardware.org/?probe=ef49631a3c) | Nov 12, 2022 |
| MSI           | GF65 Thin 9SD               | [07d4e41a25](https://linux-hardware.org/?probe=07d4e41a25) | Nov 12, 2022 |
| Lenovo        | G580 20150                  | [cae1dbbb12](https://linux-hardware.org/?probe=cae1dbbb12) | Nov 12, 2022 |
| HP            | 15                          | [bebef9206b](https://linux-hardware.org/?probe=bebef9206b) | Nov 12, 2022 |
| Lenovo        | ThinkPad A285 20MX000HMX    | [d199e5d35b](https://linux-hardware.org/?probe=d199e5d35b) | Nov 12, 2022 |
| Dell          | Latitude 7480               | [62d1e401a4](https://linux-hardware.org/?probe=62d1e401a4) | Nov 12, 2022 |
| ASUSTek       | X550LC                      | [2cfd92452e](https://linux-hardware.org/?probe=2cfd92452e) | Nov 12, 2022 |
| HP            | ZBook 15 G3                 | [824c0f9b36](https://linux-hardware.org/?probe=824c0f9b36) | Nov 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [0d6bd34095](https://linux-hardware.org/?probe=0d6bd34095) | Nov 12, 2022 |
| HP            | Compaq 6820s                | [c852376664](https://linux-hardware.org/?probe=c852376664) | Nov 12, 2022 |
| HP            | Compaq 6820s                | [dee9dbd56f](https://linux-hardware.org/?probe=dee9dbd56f) | Nov 12, 2022 |
| Dell          | XPS 15 9560                 | [cbfad6591d](https://linux-hardware.org/?probe=cbfad6591d) | Nov 12, 2022 |
| Standard      | MB40II                      | [c95529c90a](https://linux-hardware.org/?probe=c95529c90a) | Nov 12, 2022 |
| MSI           | GF65 Thin 9SD               | [17b1c5bc7c](https://linux-hardware.org/?probe=17b1c5bc7c) | Nov 12, 2022 |
| MSI           | GF65 Thin 9SD               | [f0b46e9613](https://linux-hardware.org/?probe=f0b46e9613) | Nov 11, 2022 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | [4406929fb6](https://linux-hardware.org/?probe=4406929fb6) | Nov 11, 2022 |
| HP            | Pavilion 15                 | [f6125d7605](https://linux-hardware.org/?probe=f6125d7605) | Nov 11, 2022 |
| HP            | Pavilion 15                 | [a598e64905](https://linux-hardware.org/?probe=a598e64905) | Nov 11, 2022 |
| Dell          | Latitude E6540              | [5ac9150dae](https://linux-hardware.org/?probe=5ac9150dae) | Nov 11, 2022 |
| HP            | EliteBook 850 G5            | [331a1db69d](https://linux-hardware.org/?probe=331a1db69d) | Nov 11, 2022 |
| HP            | Pavilion g4                 | [44162d8878](https://linux-hardware.org/?probe=44162d8878) | Nov 11, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | [08963a61fb](https://linux-hardware.org/?probe=08963a61fb) | Nov 10, 2022 |
| Lenovo        | Legion 7 16ITHg6 82K6       | [eebc3537d1](https://linux-hardware.org/?probe=eebc3537d1) | Nov 09, 2022 |
| Lenovo        | Y520-15IKBM 80YY            | [36b3c3d634](https://linux-hardware.org/?probe=36b3c3d634) | Nov 09, 2022 |
| ASUSTek       | K501UB                      | [c0f4434ec3](https://linux-hardware.org/?probe=c0f4434ec3) | Nov 09, 2022 |
| HP            | 15                          | [c301aa00eb](https://linux-hardware.org/?probe=c301aa00eb) | Nov 09, 2022 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [1cee1a7bd4](https://linux-hardware.org/?probe=1cee1a7bd4) | Nov 09, 2022 |
| HP            | ProBook 640 G1              | [3189f08179](https://linux-hardware.org/?probe=3189f08179) | Nov 09, 2022 |
| Google        | Atlas                       | [77922a522d](https://linux-hardware.org/?probe=77922a522d) | Nov 09, 2022 |
| Google        | Atlas                       | [829fcb8f6a](https://linux-hardware.org/?probe=829fcb8f6a) | Nov 09, 2022 |
| Acer          | Aspire 5742                 | [9c688c611e](https://linux-hardware.org/?probe=9c688c611e) | Nov 09, 2022 |
| Infinix       | INBOOK X2                   | [d342b7930f](https://linux-hardware.org/?probe=d342b7930f) | Nov 09, 2022 |
| MSI           | GE62 2QC                    | [513a929878](https://linux-hardware.org/?probe=513a929878) | Nov 08, 2022 |
| Google        | Cyan                        | [814cdea7b3](https://linux-hardware.org/?probe=814cdea7b3) | Nov 08, 2022 |
| ASUSTek       | N61Vg                       | [5205b24cb0](https://linux-hardware.org/?probe=5205b24cb0) | Nov 08, 2022 |
| Acer          | Aspire A515-51G             | [7f498c5723](https://linux-hardware.org/?probe=7f498c5723) | Nov 08, 2022 |
| Sony          | VGN-CS11Z_R                 | [865efadfee](https://linux-hardware.org/?probe=865efadfee) | Nov 08, 2022 |
| Mediacom      | SmartBook 14 FullHD - SB... | [2e0a3f4943](https://linux-hardware.org/?probe=2e0a3f4943) | Nov 08, 2022 |
| Lenovo        | ThinkPad W541 20EGS0V700    | [d03ec65abc](https://linux-hardware.org/?probe=d03ec65abc) | Nov 08, 2022 |
| ASUSTek       | UL30A                       | [a7ede6f17c](https://linux-hardware.org/?probe=a7ede6f17c) | Nov 08, 2022 |
| Toshiba       | Satellite C50-A-1HF         | [8384350121](https://linux-hardware.org/?probe=8384350121) | Nov 08, 2022 |
| Dell          | Latitude E5550              | [fb23ef865d](https://linux-hardware.org/?probe=fb23ef865d) | Nov 08, 2022 |
| Dell          | Latitude E5550              | [61527de973](https://linux-hardware.org/?probe=61527de973) | Nov 08, 2022 |
| Google        | Lick                        | [8a161ee3b6](https://linux-hardware.org/?probe=8a161ee3b6) | Nov 08, 2022 |
| Acer          | Aspire A314-35              | [14751e1ae3](https://linux-hardware.org/?probe=14751e1ae3) | Nov 08, 2022 |
| Lenovo        | ThinkPad T495 20NKS01Y00    | [9c3a72fffb](https://linux-hardware.org/?probe=9c3a72fffb) | Nov 07, 2022 |
| HP            | 240 G1                      | [2240f45c47](https://linux-hardware.org/?probe=2240f45c47) | Nov 07, 2022 |
| HP            | Pavilion Sleekbook 14 PC    | [589354a449](https://linux-hardware.org/?probe=589354a449) | Nov 07, 2022 |
| Unknown       | Unknown                     | [010a383efa](https://linux-hardware.org/?probe=010a383efa) | Nov 07, 2022 |
| HP            | EliteBook 8470p             | [e94c6ad334](https://linux-hardware.org/?probe=e94c6ad334) | Nov 07, 2022 |
| ASUSTek       | UX490UAR                    | [dc90947100](https://linux-hardware.org/?probe=dc90947100) | Nov 07, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [3febd144a4](https://linux-hardware.org/?probe=3febd144a4) | Nov 07, 2022 |
| ASUSTek       | K52Jr                       | [7be3408f46](https://linux-hardware.org/?probe=7be3408f46) | Nov 07, 2022 |
| Lenovo        | G475 20080                  | [f0f78f8e7e](https://linux-hardware.org/?probe=f0f78f8e7e) | Nov 07, 2022 |
| Lenovo        | ThinkPad T470p 20J60018G... | [b9650901a5](https://linux-hardware.org/?probe=b9650901a5) | Nov 07, 2022 |
| Lenovo        | IdeaPad 320-17AST 80XW      | [08c701b06d](https://linux-hardware.org/?probe=08c701b06d) | Nov 06, 2022 |
| HP            | EliteBook 2570p             | [2ac38253fa](https://linux-hardware.org/?probe=2ac38253fa) | Nov 06, 2022 |
| Acer          | Aspire 5742                 | [028e3c3f64](https://linux-hardware.org/?probe=028e3c3f64) | Nov 06, 2022 |
| Samsung       | 550XDA                      | [a57a40964e](https://linux-hardware.org/?probe=a57a40964e) | Nov 06, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | [5cee459a0f](https://linux-hardware.org/?probe=5cee459a0f) | Nov 06, 2022 |
| DNS           | W9x0LU                      | [2ebfe190c5](https://linux-hardware.org/?probe=2ebfe190c5) | Nov 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E203... | [d793aac21d](https://linux-hardware.org/?probe=d793aac21d) | Nov 06, 2022 |
| MSI           | GS60 6QE                    | [0e3f36f88f](https://linux-hardware.org/?probe=0e3f36f88f) | Nov 06, 2022 |
| Dell          | Inspiron 15-3552            | [f72391a03b](https://linux-hardware.org/?probe=f72391a03b) | Nov 05, 2022 |
| Toshiba       | Satellite P55-B             | [2633d644c5](https://linux-hardware.org/?probe=2633d644c5) | Nov 05, 2022 |
| Toshiba       | Satellite P55-B             | [9bee514d84](https://linux-hardware.org/?probe=9bee514d84) | Nov 05, 2022 |
| HP            | EliteBook 8560w             | [79ef8c0fb9](https://linux-hardware.org/?probe=79ef8c0fb9) | Nov 05, 2022 |
| HP            | Laptop 15-bs0xx             | [431f0124a5](https://linux-hardware.org/?probe=431f0124a5) | Nov 05, 2022 |
| Dell          | G3 3500                     | [36918f305b](https://linux-hardware.org/?probe=36918f305b) | Nov 05, 2022 |
| Samsung       | 270E5J/2570EJ               | [1466580b6e](https://linux-hardware.org/?probe=1466580b6e) | Nov 05, 2022 |
| Toshiba       | Satellite L500              | [0d6bb9cde0](https://linux-hardware.org/?probe=0d6bb9cde0) | Nov 05, 2022 |
| Toshiba       | Satellite L500              | [3d7692d178](https://linux-hardware.org/?probe=3d7692d178) | Nov 05, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [ece385acfe](https://linux-hardware.org/?probe=ece385acfe) | Nov 05, 2022 |
| Dell          | Inspiron 11-3168            | [71fac7ca47](https://linux-hardware.org/?probe=71fac7ca47) | Nov 05, 2022 |
| Lenovo        | Legion 7 16ITHg6 82K6       | [88a69a9a20](https://linux-hardware.org/?probe=88a69a9a20) | Nov 05, 2022 |
| Toshiba       | IS 1422                     | [2ea67b9fac](https://linux-hardware.org/?probe=2ea67b9fac) | Nov 05, 2022 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | [c42e078d94](https://linux-hardware.org/?probe=c42e078d94) | Nov 04, 2022 |
| Lenovo        | B71-80 80RJ                 | [25e9f48d6e](https://linux-hardware.org/?probe=25e9f48d6e) | Nov 04, 2022 |
| Acer          | Aspire A715-74G             | [fa89b7a988](https://linux-hardware.org/?probe=fa89b7a988) | Nov 04, 2022 |
| HP            | EliteBook Folio 1040 G1     | [1582ffa7f2](https://linux-hardware.org/?probe=1582ffa7f2) | Nov 04, 2022 |
| HP            | Pavilion g6                 | [38b8d5a898](https://linux-hardware.org/?probe=38b8d5a898) | Nov 04, 2022 |
| Acer          | Aspire 5738                 | [f5ac63680f](https://linux-hardware.org/?probe=f5ac63680f) | Nov 04, 2022 |
| Lenovo        | ThinkPad W541 20EGS2M300    | [28ebd68fbc](https://linux-hardware.org/?probe=28ebd68fbc) | Nov 04, 2022 |
| Lenovo        | ThinkPad W541 20EGS2M300    | [9dd90ba8d3](https://linux-hardware.org/?probe=9dd90ba8d3) | Nov 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [cc28dc5c8b](https://linux-hardware.org/?probe=cc28dc5c8b) | Nov 04, 2022 |
| HP            | ZBook 15 G3                 | [c9c8a9e899](https://linux-hardware.org/?probe=c9c8a9e899) | Nov 04, 2022 |
| Sony          | VPCEB4L1E                   | [5448ca63bc](https://linux-hardware.org/?probe=5448ca63bc) | Nov 04, 2022 |
| Dell          | G3 3590                     | [03fec4f4d4](https://linux-hardware.org/?probe=03fec4f4d4) | Nov 04, 2022 |
| HP            | EliteBook 2570p             | [2c28f25521](https://linux-hardware.org/?probe=2c28f25521) | Nov 03, 2022 |
| Lenovo        | G580 20150                  | [64c65685da](https://linux-hardware.org/?probe=64c65685da) | Nov 03, 2022 |
| Acer          | Swift SF314-56              | [71d2233bad](https://linux-hardware.org/?probe=71d2233bad) | Nov 03, 2022 |
| HP            | Laptop 17-ca0xxx            | [af3aa996df](https://linux-hardware.org/?probe=af3aa996df) | Nov 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [bf3996f87d](https://linux-hardware.org/?probe=bf3996f87d) | Nov 03, 2022 |
| ASUSTek       | K50IJ                       | [5aa399c2c2](https://linux-hardware.org/?probe=5aa399c2c2) | Nov 03, 2022 |
| Acer          | Swift SF314-56              | [02a825cde6](https://linux-hardware.org/?probe=02a825cde6) | Nov 03, 2022 |
| Dell          | Inspiron 5379               | [329ecd4e64](https://linux-hardware.org/?probe=329ecd4e64) | Nov 03, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [43609f5bd5](https://linux-hardware.org/?probe=43609f5bd5) | Nov 03, 2022 |
| HP            | EliteBook 8570p             | [00fcfee8fa](https://linux-hardware.org/?probe=00fcfee8fa) | Nov 03, 2022 |
| HP            | EliteBook 8470p             | [d754cc7217](https://linux-hardware.org/?probe=d754cc7217) | Nov 03, 2022 |
| UMAX          | VisionBook N15G Plus        | [eba9cd6286](https://linux-hardware.org/?probe=eba9cd6286) | Nov 03, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [dfe209bf08](https://linux-hardware.org/?probe=dfe209bf08) | Nov 03, 2022 |
| Star Labs     | StarBook                    | [1cfe5c0920](https://linux-hardware.org/?probe=1cfe5c0920) | Nov 02, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [3bd662e577](https://linux-hardware.org/?probe=3bd662e577) | Nov 02, 2022 |
| Dell          | G15 5515                    | [92f1423303](https://linux-hardware.org/?probe=92f1423303) | Nov 02, 2022 |
| ASUSTek       | X540SAA                     | [ccaedd7155](https://linux-hardware.org/?probe=ccaedd7155) | Nov 02, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [a3b1926b7e](https://linux-hardware.org/?probe=a3b1926b7e) | Nov 02, 2022 |
| Lenovo        | G560 0679                   | [c97e8f3436](https://linux-hardware.org/?probe=c97e8f3436) | Nov 02, 2022 |
| HP            | EliteBook 2730p             | [79830976d8](https://linux-hardware.org/?probe=79830976d8) | Nov 02, 2022 |
| Dell          | G15 5515                    | [dae7c630d5](https://linux-hardware.org/?probe=dae7c630d5) | Nov 02, 2022 |
| Dell          | Inspiron 15-3567            | [a9b57edf35](https://linux-hardware.org/?probe=a9b57edf35) | Nov 02, 2022 |
| Dell          | Inspiron 15 3511            | [5786a01590](https://linux-hardware.org/?probe=5786a01590) | Nov 02, 2022 |
| HP            | ProBook 4530s               | [6490664312](https://linux-hardware.org/?probe=6490664312) | Nov 01, 2022 |
| Lenovo        | IdeaPad 320-17AST 80XW      | [9fa0489d64](https://linux-hardware.org/?probe=9fa0489d64) | Nov 01, 2022 |
| HP            | ProBook 4530s               | [34682f3bfe](https://linux-hardware.org/?probe=34682f3bfe) | Nov 01, 2022 |
| Lenovo        | IdeaPad 320-17AST 80XW      | [411a5da53c](https://linux-hardware.org/?probe=411a5da53c) | Nov 01, 2022 |
| Apple         | MacBookPro9,2               | [4cdb36db63](https://linux-hardware.org/?probe=4cdb36db63) | Nov 01, 2022 |
| HUAWEI        | MACHC-WAX9                  | [e4f3828910](https://linux-hardware.org/?probe=e4f3828910) | Nov 01, 2022 |
| ASUSTek       | N61Vg                       | [27f288e5f1](https://linux-hardware.org/?probe=27f288e5f1) | Nov 01, 2022 |
| HP            | ZBook 15 G2                 | [05eeb9e341](https://linux-hardware.org/?probe=05eeb9e341) | Nov 01, 2022 |
| Packard Be... | EasyNote TE11BZ             | [0301f1ddf1](https://linux-hardware.org/?probe=0301f1ddf1) | Oct 31, 2022 |
| ASUSTek       | K54L                        | [200f6044c2](https://linux-hardware.org/?probe=200f6044c2) | Oct 31, 2022 |
| Lenovo        | G700                        | [9bf9b4e263](https://linux-hardware.org/?probe=9bf9b4e263) | Oct 31, 2022 |
| HP            | Pavilion Laptop 14-ec1xx... | [1563c60737](https://linux-hardware.org/?probe=1563c60737) | Oct 31, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [a75bc2ff26](https://linux-hardware.org/?probe=a75bc2ff26) | Oct 30, 2022 |
| HP            | Laptop 15-bs1xx             | [fabbcc9035](https://linux-hardware.org/?probe=fabbcc9035) | Oct 30, 2022 |
| ASUSTek       | G74Sx                       | [c24c24ab27](https://linux-hardware.org/?probe=c24c24ab27) | Oct 30, 2022 |
| HP            | 15                          | [34e1ac4cbe](https://linux-hardware.org/?probe=34e1ac4cbe) | Oct 30, 2022 |
| Lenovo        | V110-15IAP 80TG             | [01d8b89e0d](https://linux-hardware.org/?probe=01d8b89e0d) | Oct 30, 2022 |
| Dell          | Studio 1735                 | [8f070a2831](https://linux-hardware.org/?probe=8f070a2831) | Oct 30, 2022 |
| Lenovo        | V110-15IAP 80TG             | [183feb626d](https://linux-hardware.org/?probe=183feb626d) | Oct 30, 2022 |
| HP            | ProBook 6540b               | [be9c128b00](https://linux-hardware.org/?probe=be9c128b00) | Oct 30, 2022 |
| HP            | ProBook 6560b               | [89feda4b09](https://linux-hardware.org/?probe=89feda4b09) | Oct 30, 2022 |
| HP            | Unknown                     | [6e024c825e](https://linux-hardware.org/?probe=6e024c825e) | Oct 30, 2022 |
| HP            | Laptop 17-by1xxx            | [b3e8975edf](https://linux-hardware.org/?probe=b3e8975edf) | Oct 29, 2022 |
| ASUSTek       | E200HA                      | [18ca81370b](https://linux-hardware.org/?probe=18ca81370b) | Oct 29, 2022 |
| HP            | Laptop 17-bs0xx             | [68238274ff](https://linux-hardware.org/?probe=68238274ff) | Oct 29, 2022 |
| ASUSTek       | E200HA                      | [0a95698cb6](https://linux-hardware.org/?probe=0a95698cb6) | Oct 29, 2022 |
| Dell          | XPS 13 9370                 | [7bf374b38a](https://linux-hardware.org/?probe=7bf374b38a) | Oct 29, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | [ce9df2cf8f](https://linux-hardware.org/?probe=ce9df2cf8f) | Oct 29, 2022 |
| SANTECH       | PCx0Dx                      | [24462321e8](https://linux-hardware.org/?probe=24462321e8) | Oct 29, 2022 |
| Acer          | Nitro AN515-52              | [38570237ac](https://linux-hardware.org/?probe=38570237ac) | Oct 29, 2022 |
| Acer          | Nitro AN515-52              | [5551d222b2](https://linux-hardware.org/?probe=5551d222b2) | Oct 29, 2022 |
| ASUSTek       | X751NV                      | [9ef2717db0](https://linux-hardware.org/?probe=9ef2717db0) | Oct 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [1d4a6dc6dc](https://linux-hardware.org/?probe=1d4a6dc6dc) | Oct 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [a1694d3adc](https://linux-hardware.org/?probe=a1694d3adc) | Oct 29, 2022 |
| ASUSTek       | K55VJ                       | [6dc11e517b](https://linux-hardware.org/?probe=6dc11e517b) | Oct 29, 2022 |
| Wortmann      | CR700                       | [7030308edf](https://linux-hardware.org/?probe=7030308edf) | Oct 29, 2022 |
| Dell          | Inspiron 7737               | [f352df76ef](https://linux-hardware.org/?probe=f352df76ef) | Oct 29, 2022 |
| Lenovo        | ThinkPad T450s 20BWS0DD0... | [973a3662b9](https://linux-hardware.org/?probe=973a3662b9) | Oct 29, 2022 |
| Kruger&Mat... | KM1406                      | [70b8441ccf](https://linux-hardware.org/?probe=70b8441ccf) | Oct 29, 2022 |
| Dell          | Inspiron 3583               | [4f6c1e374f](https://linux-hardware.org/?probe=4f6c1e374f) | Oct 29, 2022 |
| ASUSTek       | K50C                        | [af80714f09](https://linux-hardware.org/?probe=af80714f09) | Oct 29, 2022 |
| Acer          | Aspire SW5-012              | [90dd31edc8](https://linux-hardware.org/?probe=90dd31edc8) | Oct 29, 2022 |
| ASUSTek       | K50C                        | [ca606469d8](https://linux-hardware.org/?probe=ca606469d8) | Oct 29, 2022 |
| Prestigio     | PSB141S01                   | [646d3fd287](https://linux-hardware.org/?probe=646d3fd287) | Oct 28, 2022 |
| Lenovo        | ThinkPad Edge E320 1298R... | [c79d1e6209](https://linux-hardware.org/?probe=c79d1e6209) | Oct 28, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [8429395d7d](https://linux-hardware.org/?probe=8429395d7d) | Oct 28, 2022 |
| Dell          | Latitude 5531               | [a7ff9a34d2](https://linux-hardware.org/?probe=a7ff9a34d2) | Oct 28, 2022 |
| Dell          | Latitude 5531               | [73ddced77b](https://linux-hardware.org/?probe=73ddced77b) | Oct 28, 2022 |
| Fujitsu       | LIFEBOOK U728               | [c5867e7dd3](https://linux-hardware.org/?probe=c5867e7dd3) | Oct 28, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [366e5edec9](https://linux-hardware.org/?probe=366e5edec9) | Oct 28, 2022 |
| Dell          | XPS 15 9510                 | [d3879c6bb0](https://linux-hardware.org/?probe=d3879c6bb0) | Oct 28, 2022 |
| HP            | EliteBook 820 G2            | [7056cf1574](https://linux-hardware.org/?probe=7056cf1574) | Oct 28, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | [2829b0b18f](https://linux-hardware.org/?probe=2829b0b18f) | Oct 28, 2022 |
| Unknown       | Unknown                     | [c867c45a75](https://linux-hardware.org/?probe=c867c45a75) | Oct 28, 2022 |
| Samsung       | 275E4E/275E5E               | [d3aebcbac6](https://linux-hardware.org/?probe=d3aebcbac6) | Oct 27, 2022 |
| Unknown       | Unknown                     | [967c2c956d](https://linux-hardware.org/?probe=967c2c956d) | Oct 27, 2022 |
| Dell          | Inspiron 15-7568            | [ae536fa220](https://linux-hardware.org/?probe=ae536fa220) | Oct 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21E6C... | [7ffc8c3537](https://linux-hardware.org/?probe=7ffc8c3537) | Oct 27, 2022 |
| Acer          | Aspire A315-54              | [6de38f7802](https://linux-hardware.org/?probe=6de38f7802) | Oct 27, 2022 |
| ASUSTek       | Q304UAK                     | [2c51d603ee](https://linux-hardware.org/?probe=2c51d603ee) | Oct 27, 2022 |
| HP            | ProBook 6560b               | [222a5c2dbe](https://linux-hardware.org/?probe=222a5c2dbe) | Oct 27, 2022 |
| ASUSTek       | Q304UAK                     | [4b624e6f98](https://linux-hardware.org/?probe=4b624e6f98) | Oct 27, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [3541e2e011](https://linux-hardware.org/?probe=3541e2e011) | Oct 27, 2022 |
| HP            | ProBook 640 G1              | [b096155d39](https://linux-hardware.org/?probe=b096155d39) | Oct 27, 2022 |
| Acer          | Swift SF314-512             | [951c734c1b](https://linux-hardware.org/?probe=951c734c1b) | Oct 27, 2022 |
| MSI           | Katana GF66 12UC            | [9b8f917e6b](https://linux-hardware.org/?probe=9b8f917e6b) | Oct 27, 2022 |
| HP            | ProBook 450 G3              | [4aa258716b](https://linux-hardware.org/?probe=4aa258716b) | Oct 26, 2022 |
| HP            | ProBook 450 G3              | [26d1b8b2b2](https://linux-hardware.org/?probe=26d1b8b2b2) | Oct 26, 2022 |
| Acer          | Aspire A315-21              | [14f5f5ceeb](https://linux-hardware.org/?probe=14f5f5ceeb) | Oct 26, 2022 |
| HP            | ProBook 640 G1              | [e30a33bfd8](https://linux-hardware.org/?probe=e30a33bfd8) | Oct 26, 2022 |
| Acidanther... | MacBookPro16,1              | [45fd84f413](https://linux-hardware.org/?probe=45fd84f413) | Oct 26, 2022 |
| HP            | EliteBook 840 G5            | [4b28c73302](https://linux-hardware.org/?probe=4b28c73302) | Oct 26, 2022 |
| Dell          | Latitude E4300              | [8ee3fadd0b](https://linux-hardware.org/?probe=8ee3fadd0b) | Oct 26, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | [c19eaa0502](https://linux-hardware.org/?probe=c19eaa0502) | Oct 26, 2022 |
| HP            | Pavilion dv6                | [03e2594419](https://linux-hardware.org/?probe=03e2594419) | Oct 25, 2022 |
| Dell          | Precision 5560              | [c6cfa3f96d](https://linux-hardware.org/?probe=c6cfa3f96d) | Oct 25, 2022 |
| Dell          | Precision 5560              | [e0dce17c1f](https://linux-hardware.org/?probe=e0dce17c1f) | Oct 25, 2022 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [814da05eec](https://linux-hardware.org/?probe=814da05eec) | Oct 25, 2022 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [80177955c3](https://linux-hardware.org/?probe=80177955c3) | Oct 25, 2022 |
| Lenovo        | G40-80 80JE                 | [97dfa18602](https://linux-hardware.org/?probe=97dfa18602) | Oct 25, 2022 |
| Toshiba       | Satellite U920t             | [268814e9ab](https://linux-hardware.org/?probe=268814e9ab) | Oct 25, 2022 |
| HP            | EliteBook 8570p             | [c3ec764ff3](https://linux-hardware.org/?probe=c3ec764ff3) | Oct 25, 2022 |
| HP            | 8433 11                     | [81740a5a8e](https://linux-hardware.org/?probe=81740a5a8e) | Oct 25, 2022 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [18931ec5f6](https://linux-hardware.org/?probe=18931ec5f6) | Oct 25, 2022 |
| Lenovo        | V15-IIL 82C5                | [a56ad41b2f](https://linux-hardware.org/?probe=a56ad41b2f) | Oct 25, 2022 |
| HP            | 250 G6 Notebook PC          | [e2baff543b](https://linux-hardware.org/?probe=e2baff543b) | Oct 24, 2022 |
| Sony          | SVE1712Z1EB                 | [23b6ac5cde](https://linux-hardware.org/?probe=23b6ac5cde) | Oct 24, 2022 |
| Olivetti      | Olibook P75B                | [a1b4023949](https://linux-hardware.org/?probe=a1b4023949) | Oct 24, 2022 |
| Dell          | Studio 1735                 | [21959a7db7](https://linux-hardware.org/?probe=21959a7db7) | Oct 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [e198c305e4](https://linux-hardware.org/?probe=e198c305e4) | Oct 24, 2022 |
| HP            | Laptop 17-cp0xxx            | [4a818d766f](https://linux-hardware.org/?probe=4a818d766f) | Oct 24, 2022 |
| Dell          | Latitude E7240              | [33c37015df](https://linux-hardware.org/?probe=33c37015df) | Oct 24, 2022 |
| ASUSTek       | X550LC                      | [75c0c3e97b](https://linux-hardware.org/?probe=75c0c3e97b) | Oct 24, 2022 |
| Dell          | XPS L412Z                   | [92d8a4b47a](https://linux-hardware.org/?probe=92d8a4b47a) | Oct 24, 2022 |
| Apple         | MacBookAir7,2               | [7b901320c7](https://linux-hardware.org/?probe=7b901320c7) | Oct 24, 2022 |
| Apple         | MacBookAir7,2               | [daac29aff2](https://linux-hardware.org/?probe=daac29aff2) | Oct 24, 2022 |
| Dell          | Studio 1735                 | [4385640990](https://linux-hardware.org/?probe=4385640990) | Oct 23, 2022 |
| ASUSTek       | X550EA                      | [6a7b7a70a5](https://linux-hardware.org/?probe=6a7b7a70a5) | Oct 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [4c0e49ae2b](https://linux-hardware.org/?probe=4c0e49ae2b) | Oct 23, 2022 |
| ASUSTek       | X550EA                      | [e2c2ac571f](https://linux-hardware.org/?probe=e2c2ac571f) | Oct 23, 2022 |
| Chuwi         | HeroBook Air                | [753874362e](https://linux-hardware.org/?probe=753874362e) | Oct 23, 2022 |
| MSI           | Modern 14 C12M              | [2991b1a2cf](https://linux-hardware.org/?probe=2991b1a2cf) | Oct 23, 2022 |
| MSI           | Modern 14 C12M              | [2015c6f7fc](https://linux-hardware.org/?probe=2015c6f7fc) | Oct 23, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | [8138e910ce](https://linux-hardware.org/?probe=8138e910ce) | Oct 23, 2022 |
| HP            | 15                          | [5baa47ecd1](https://linux-hardware.org/?probe=5baa47ecd1) | Oct 23, 2022 |
| Apple         | MacBookPro8,1               | [33bef6bb6f](https://linux-hardware.org/?probe=33bef6bb6f) | Oct 23, 2022 |
| Acer          | Aspire A315-53              | [5388646329](https://linux-hardware.org/?probe=5388646329) | Oct 23, 2022 |
| Apple         | MacBookPro8,1               | [da114c9e74](https://linux-hardware.org/?probe=da114c9e74) | Oct 23, 2022 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [62bdd854b4](https://linux-hardware.org/?probe=62bdd854b4) | Oct 23, 2022 |
| Dell          | Vostro 1520                 | [a5106ca47d](https://linux-hardware.org/?probe=a5106ca47d) | Oct 22, 2022 |
| Dell          | XPS 13 9305                 | [8fec9e2536](https://linux-hardware.org/?probe=8fec9e2536) | Oct 22, 2022 |
| Lenovo        | Legion Y730-17ICH 81HG      | [c9a85159dd](https://linux-hardware.org/?probe=c9a85159dd) | Oct 22, 2022 |
| Acer          | TravelMate P256-M           | [7ca952de68](https://linux-hardware.org/?probe=7ca952de68) | Oct 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [1f26696990](https://linux-hardware.org/?probe=1f26696990) | Oct 22, 2022 |
| Lenovo        | Legion Y730-17ICH 81HG      | [15a66ac64c](https://linux-hardware.org/?probe=15a66ac64c) | Oct 22, 2022 |
| Dell          | Latitude E4300              | [fb144bfcb2](https://linux-hardware.org/?probe=fb144bfcb2) | Oct 22, 2022 |
| ASUSTek       | X550LN                      | [7a6daf6023](https://linux-hardware.org/?probe=7a6daf6023) | Oct 22, 2022 |
| Acer          | Aspire A315-53              | [72f0c231fb](https://linux-hardware.org/?probe=72f0c231fb) | Oct 21, 2022 |
| Positivo      | S14CT01                     | [1a5f77c8f9](https://linux-hardware.org/?probe=1a5f77c8f9) | Oct 21, 2022 |
| MAXDATA       | obook2-1                    | [c7e03dae2f](https://linux-hardware.org/?probe=c7e03dae2f) | Oct 21, 2022 |
| HP            | EliteBook 820 G1            | [7abef2546e](https://linux-hardware.org/?probe=7abef2546e) | Oct 21, 2022 |
| Google        | Treeya                      | [1a93d190b0](https://linux-hardware.org/?probe=1a93d190b0) | Oct 21, 2022 |
| Dell          | Latitude E5530 non-vPro     | [de5adb6775](https://linux-hardware.org/?probe=de5adb6775) | Oct 21, 2022 |
| MAXDATA       | obook2-1                    | [0f73d884ff](https://linux-hardware.org/?probe=0f73d884ff) | Oct 21, 2022 |
| Acer          | Aspire S3                   | [a24603a142](https://linux-hardware.org/?probe=a24603a142) | Oct 20, 2022 |
| Gigabyte      | X7X7                        | [f2c35e3917](https://linux-hardware.org/?probe=f2c35e3917) | Oct 20, 2022 |
| Lenovo        | G780                        | [986b0fdbd0](https://linux-hardware.org/?probe=986b0fdbd0) | Oct 20, 2022 |
| Toshiba       | Satellite C660              | [3632c8a48d](https://linux-hardware.org/?probe=3632c8a48d) | Oct 20, 2022 |
| HP            | EliteBook 840 G5            | [ef1acaa7da](https://linux-hardware.org/?probe=ef1acaa7da) | Oct 20, 2022 |
| HP            | EliteBook 840 G5            | [3ec2887574](https://linux-hardware.org/?probe=3ec2887574) | Oct 20, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [f5073cd7a2](https://linux-hardware.org/?probe=f5073cd7a2) | Oct 20, 2022 |
| ASUSTek       | X540SAA                     | [e3fef524ee](https://linux-hardware.org/?probe=e3fef524ee) | Oct 20, 2022 |
| Lenovo        | G505s 20255                 | [a105e25fa5](https://linux-hardware.org/?probe=a105e25fa5) | Oct 20, 2022 |
| GPU Compan... | GWNR71517                   | [27ae96160e](https://linux-hardware.org/?probe=27ae96160e) | Oct 20, 2022 |
| GPU Compan... | GWNR71517                   | [d55bceb8fb](https://linux-hardware.org/?probe=d55bceb8fb) | Oct 19, 2022 |
| Toshiba       | Satellite A300              | [ce897bc567](https://linux-hardware.org/?probe=ce897bc567) | Oct 19, 2022 |
| Lenovo        | ThinkPad T460s 20FAS1Q10... | [a96060006f](https://linux-hardware.org/?probe=a96060006f) | Oct 19, 2022 |
| Alcor Digi... | Snugbook N1431              | [eb7940e5a4](https://linux-hardware.org/?probe=eb7940e5a4) | Oct 19, 2022 |
| HP            | EliteBook 840 G6            | [e5f7b07e9c](https://linux-hardware.org/?probe=e5f7b07e9c) | Oct 19, 2022 |
| Acer          | Aspire V5-571PG             | [e00a049460](https://linux-hardware.org/?probe=e00a049460) | Oct 19, 2022 |
| HP            | EliteBook 840 G6            | [25bb674789](https://linux-hardware.org/?probe=25bb674789) | Oct 19, 2022 |
| Dell          | XPS L412Z                   | [eb1b1f7950](https://linux-hardware.org/?probe=eb1b1f7950) | Oct 19, 2022 |
| ASUSTek       | N82JV                       | [7157bb5872](https://linux-hardware.org/?probe=7157bb5872) | Oct 19, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [6271fbb0fb](https://linux-hardware.org/?probe=6271fbb0fb) | Oct 19, 2022 |
| HUAWEI        | MACHD-WXX9                  | [5086e64fed](https://linux-hardware.org/?probe=5086e64fed) | Oct 19, 2022 |
| HP            | Pavilion Notebook           | [0d145a7293](https://linux-hardware.org/?probe=0d145a7293) | Oct 19, 2022 |
| Dell          | Latitude E7440              | [5c81fc2db0](https://linux-hardware.org/?probe=5c81fc2db0) | Oct 19, 2022 |
| Alcor Digi... | Snugbook N1431              | [098e362854](https://linux-hardware.org/?probe=098e362854) | Oct 19, 2022 |
| HP            | ENVY Laptop 17-bw0xxx       | [6b7263006f](https://linux-hardware.org/?probe=6b7263006f) | Oct 18, 2022 |
| Dell          | G15 5510                    | [1286ecf9dd](https://linux-hardware.org/?probe=1286ecf9dd) | Oct 18, 2022 |
| HP            | 15                          | [072d4ee592](https://linux-hardware.org/?probe=072d4ee592) | Oct 18, 2022 |
| Lenovo        | ThinkPad T15g Gen 1 20US... | [ec42bc932e](https://linux-hardware.org/?probe=ec42bc932e) | Oct 18, 2022 |
| HP            | Laptop 17-bs0xx             | [369934a06c](https://linux-hardware.org/?probe=369934a06c) | Oct 18, 2022 |
| Acer          | Aspire 5830T                | [2423f8bf08](https://linux-hardware.org/?probe=2423f8bf08) | Oct 18, 2022 |
| Acer          | Swift SF314-54              | [04fed978ae](https://linux-hardware.org/?probe=04fed978ae) | Oct 18, 2022 |
| HP            | ZBook 14u G5                | [151433ee2e](https://linux-hardware.org/?probe=151433ee2e) | Oct 18, 2022 |
| MOTILE        | M141                        | [c9ca7c65f0](https://linux-hardware.org/?probe=c9ca7c65f0) | Oct 18, 2022 |
| HP            | EliteBook Folio 9470m       | [c1e67135ac](https://linux-hardware.org/?probe=c1e67135ac) | Oct 18, 2022 |
| Acer          | Aspire E5-573               | [baf225a894](https://linux-hardware.org/?probe=baf225a894) | Oct 17, 2022 |
| Monster       | TULPAR T5 V21.6             | [eaeb6f6610](https://linux-hardware.org/?probe=eaeb6f6610) | Oct 17, 2022 |
| HUAWEI        | BOM-WXX9                    | [594b141136](https://linux-hardware.org/?probe=594b141136) | Oct 17, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [a4ebad3748](https://linux-hardware.org/?probe=a4ebad3748) | Oct 17, 2022 |
| Acer          | Aspire 6930                 | [7ef117fa52](https://linux-hardware.org/?probe=7ef117fa52) | Oct 17, 2022 |
| Apple         | MacBook5,1                  | [84200c663d](https://linux-hardware.org/?probe=84200c663d) | Oct 17, 2022 |
| Toshiba       | Satellite U920t             | [75918848c4](https://linux-hardware.org/?probe=75918848c4) | Oct 17, 2022 |
| Toshiba       | Satellite U920t             | [9eb5519133](https://linux-hardware.org/?probe=9eb5519133) | Oct 17, 2022 |
| Multilaser    | PC024                       | [892f53a067](https://linux-hardware.org/?probe=892f53a067) | Oct 17, 2022 |
| ASUSTek       | X553MA                      | [71cfc713af](https://linux-hardware.org/?probe=71cfc713af) | Oct 17, 2022 |
| ASUSTek       | M70Vn                       | [e9301bdee2](https://linux-hardware.org/?probe=e9301bdee2) | Oct 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [62fd5f4526](https://linux-hardware.org/?probe=62fd5f4526) | Oct 16, 2022 |
| Dell          | Latitude 3500               | [d578b45420](https://linux-hardware.org/?probe=d578b45420) | Oct 16, 2022 |
| HP            | 245 G7 Notebook PC          | [c164c2ab59](https://linux-hardware.org/?probe=c164c2ab59) | Oct 16, 2022 |
| HP            | Notebook                    | [f88b853298](https://linux-hardware.org/?probe=f88b853298) | Oct 16, 2022 |
| Acer          | Aspire 5742G                | [79a5162024](https://linux-hardware.org/?probe=79a5162024) | Oct 16, 2022 |
| Thomson       | NEO14A-4WH128               | [daa7836c39](https://linux-hardware.org/?probe=daa7836c39) | Oct 16, 2022 |
| Dell          | Latitude E7450              | [500311a1b8](https://linux-hardware.org/?probe=500311a1b8) | Oct 16, 2022 |
| Acer          | Aspire V3-571               | [8457aa21e7](https://linux-hardware.org/?probe=8457aa21e7) | Oct 16, 2022 |
| HP            | Laptop 17-bs0xx             | [090cc3b6c5](https://linux-hardware.org/?probe=090cc3b6c5) | Oct 16, 2022 |
| Dell          | Inspiron 3505               | [ea75db9cc9](https://linux-hardware.org/?probe=ea75db9cc9) | Oct 16, 2022 |
| HP            | ZBook 14u G5                | [c35a9f90e8](https://linux-hardware.org/?probe=c35a9f90e8) | Oct 15, 2022 |
| ASUSTek       | X751NV                      | [174ee8f3e7](https://linux-hardware.org/?probe=174ee8f3e7) | Oct 15, 2022 |
| Google        | Coral                       | [a1811601a0](https://linux-hardware.org/?probe=a1811601a0) | Oct 15, 2022 |
| Google        | Coral                       | [93a674ea2b](https://linux-hardware.org/?probe=93a674ea2b) | Oct 15, 2022 |
| HP            | Pavilion ZV6100 (EC356UA... | [a001b5a9f9](https://linux-hardware.org/?probe=a001b5a9f9) | Oct 15, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [7d6c345f35](https://linux-hardware.org/?probe=7d6c345f35) | Oct 15, 2022 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [6a0a056c36](https://linux-hardware.org/?probe=6a0a056c36) | Oct 15, 2022 |
| Acer          | AOD270                      | [7fbd540e61](https://linux-hardware.org/?probe=7fbd540e61) | Oct 15, 2022 |
| Acer          | Aspire 7730ZG               | [4796b36078](https://linux-hardware.org/?probe=4796b36078) | Oct 15, 2022 |
| HP            | ENVY Notebook               | [ae760be223](https://linux-hardware.org/?probe=ae760be223) | Oct 15, 2022 |
| Compaq        | 420                         | [cc3fae2a79](https://linux-hardware.org/?probe=cc3fae2a79) | Oct 15, 2022 |
| HP            | ZBook Firefly 14 inch G8... | [b7a5ca0670](https://linux-hardware.org/?probe=b7a5ca0670) | Oct 15, 2022 |
| ASUSTek       | X541UV                      | [ba7c1c3d83](https://linux-hardware.org/?probe=ba7c1c3d83) | Oct 14, 2022 |
| Lenovo        | V15 G2 IJL 82QY             | [240811f34a](https://linux-hardware.org/?probe=240811f34a) | Oct 14, 2022 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [fefb833511](https://linux-hardware.org/?probe=fefb833511) | Oct 14, 2022 |
| Getac         | V110G3                      | [09cd83f0ec](https://linux-hardware.org/?probe=09cd83f0ec) | Oct 14, 2022 |
| Google        | Dragonair                   | [4cfbc6aeac](https://linux-hardware.org/?probe=4cfbc6aeac) | Oct 14, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [bc23ce28e0](https://linux-hardware.org/?probe=bc23ce28e0) | Oct 14, 2022 |
| Lenovo        | ThinkPad E595 20NF001HMX    | [1ae4e8967a](https://linux-hardware.org/?probe=1ae4e8967a) | Oct 14, 2022 |
| Qilive        | QW20141BSP                  | [a497e419fe](https://linux-hardware.org/?probe=a497e419fe) | Oct 13, 2022 |
| ASUSTek       | X502CA                      | [1243c07d09](https://linux-hardware.org/?probe=1243c07d09) | Oct 13, 2022 |
| ASUSTek       | X502CA                      | [064718ff22](https://linux-hardware.org/?probe=064718ff22) | Oct 13, 2022 |
| HP            | EliteBook 840 G1            | [fe9dde997d](https://linux-hardware.org/?probe=fe9dde997d) | Oct 13, 2022 |
| ASUSTek       | X553MA                      | [256cb98ed8](https://linux-hardware.org/?probe=256cb98ed8) | Oct 13, 2022 |
| Acer          | Swift SF314-57              | [5eafc7c12c](https://linux-hardware.org/?probe=5eafc7c12c) | Oct 13, 2022 |
| HUAWEI        | MACHD-WXX9                  | [5f0c4b3acb](https://linux-hardware.org/?probe=5f0c4b3acb) | Oct 13, 2022 |
| Dell          | Latitude E5550              | [fc1fa79f81](https://linux-hardware.org/?probe=fc1fa79f81) | Oct 13, 2022 |
| Dell          | Inspiron 5759               | [2656af4553](https://linux-hardware.org/?probe=2656af4553) | Oct 13, 2022 |
| Dell          | Precision 3550              | [e4d97d0229](https://linux-hardware.org/?probe=e4d97d0229) | Oct 13, 2022 |
| Acer          | Aspire 5732Z                | [b75d98cfc2](https://linux-hardware.org/?probe=b75d98cfc2) | Oct 13, 2022 |
| Daten Tecn... | DT02-M4                     | [d800a06da5](https://linux-hardware.org/?probe=d800a06da5) | Oct 12, 2022 |
| Daten Tecn... | DT02-M4                     | [9d4c4f0c96](https://linux-hardware.org/?probe=9d4c4f0c96) | Oct 12, 2022 |
| HUAWEI        | HVY-WXX9                    | [a2ec61226c](https://linux-hardware.org/?probe=a2ec61226c) | Oct 12, 2022 |
| HP            | EliteBook 8570p             | [51954462c5](https://linux-hardware.org/?probe=51954462c5) | Oct 12, 2022 |
| Dell          | G3 3500                     | [831b4e147e](https://linux-hardware.org/?probe=831b4e147e) | Oct 12, 2022 |
| ASUSTek       | M70Vn                       | [62cb9744e6](https://linux-hardware.org/?probe=62cb9744e6) | Oct 12, 2022 |
| ASUSTek       | X751LD                      | [230969c119](https://linux-hardware.org/?probe=230969c119) | Oct 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [f7f3439df7](https://linux-hardware.org/?probe=f7f3439df7) | Oct 11, 2022 |
| Lenovo        | IdeaPad 320-15IKB Touch ... | [89ee3db150](https://linux-hardware.org/?probe=89ee3db150) | Oct 11, 2022 |
| Acer          | Aspire ES1-571              | [3e2cf72b67](https://linux-hardware.org/?probe=3e2cf72b67) | Oct 11, 2022 |
| Acer          | Aspire ES1-571              | [6c313eca4e](https://linux-hardware.org/?probe=6c313eca4e) | Oct 11, 2022 |
| HP            | Laptop 17-by4xxx            | [392c089837](https://linux-hardware.org/?probe=392c089837) | Oct 10, 2022 |
| Acer          | Aspire E1-572               | [4097531dec](https://linux-hardware.org/?probe=4097531dec) | Oct 10, 2022 |
| Dell          | Latitude E7240              | [3f9f9c38d1](https://linux-hardware.org/?probe=3f9f9c38d1) | Oct 10, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | [b8e434e4db](https://linux-hardware.org/?probe=b8e434e4db) | Oct 10, 2022 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [989fe39fa7](https://linux-hardware.org/?probe=989fe39fa7) | Oct 10, 2022 |
| Sony          | VGN-N21E_W                  | [464905b4f8](https://linux-hardware.org/?probe=464905b4f8) | Oct 10, 2022 |
| Letni         | Z156                        | [994c588906](https://linux-hardware.org/?probe=994c588906) | Oct 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [98a14153ba](https://linux-hardware.org/?probe=98a14153ba) | Oct 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [58eb34d574](https://linux-hardware.org/?probe=58eb34d574) | Oct 10, 2022 |
| HP            | Compaq 6710b (GB887EA#AC... | [9f2e301993](https://linux-hardware.org/?probe=9f2e301993) | Oct 10, 2022 |
| HP            | Compaq 6710b (GB887EA#AC... | [af662698b9](https://linux-hardware.org/?probe=af662698b9) | Oct 10, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [e860301211](https://linux-hardware.org/?probe=e860301211) | Oct 09, 2022 |
| HP            | Pavilion g6                 | [582de9d5d6](https://linux-hardware.org/?probe=582de9d5d6) | Oct 09, 2022 |
| HP            | Pavilion g6                 | [f1b7cbae01](https://linux-hardware.org/?probe=f1b7cbae01) | Oct 09, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [cd06846004](https://linux-hardware.org/?probe=cd06846004) | Oct 09, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [2f4281aaaf](https://linux-hardware.org/?probe=2f4281aaaf) | Oct 09, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [71ef13e7f5](https://linux-hardware.org/?probe=71ef13e7f5) | Oct 09, 2022 |
| Dell          | Vostro 1520                 | [2de097618b](https://linux-hardware.org/?probe=2de097618b) | Oct 09, 2022 |
| MSI           | MS-7A34                     | [9f2f5898d2](https://linux-hardware.org/?probe=9f2f5898d2) | Oct 09, 2022 |
| MSI           | MS-7A34                     | [2b1c4c2738](https://linux-hardware.org/?probe=2b1c4c2738) | Oct 09, 2022 |
| Acer          | Aspire V5-471               | [46e5edbd41](https://linux-hardware.org/?probe=46e5edbd41) | Oct 08, 2022 |
| Fujitsu Si... | AMILO Pa 1538               | [11d843f241](https://linux-hardware.org/?probe=11d843f241) | Oct 08, 2022 |
| Sony          | VGN-AR71J                   | [57348f6a71](https://linux-hardware.org/?probe=57348f6a71) | Oct 08, 2022 |
| Lenovo        | ThinkPad T495 20NKS01Y00    | [ff4f9614fd](https://linux-hardware.org/?probe=ff4f9614fd) | Oct 08, 2022 |
| HP            | Pavilion Sleekbook 14 PC    | [acd8e18972](https://linux-hardware.org/?probe=acd8e18972) | Oct 08, 2022 |
| Dell          | Inspiron 3583               | [35b77097e9](https://linux-hardware.org/?probe=35b77097e9) | Oct 08, 2022 |
| Lenovo        | ThinkPad X200 7458EB2       | [70673f67bd](https://linux-hardware.org/?probe=70673f67bd) | Oct 08, 2022 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | [1b720b4302](https://linux-hardware.org/?probe=1b720b4302) | Oct 08, 2022 |
| Toshiba       | Satellite P200              | [55e4a786bd](https://linux-hardware.org/?probe=55e4a786bd) | Oct 08, 2022 |
| Apple         | MacBookAir6,2               | [9f434d86be](https://linux-hardware.org/?probe=9f434d86be) | Oct 08, 2022 |
| Dell          | Venue 11 Pro 5130           | [776d52e413](https://linux-hardware.org/?probe=776d52e413) | Oct 08, 2022 |
| Dell          | Inspiron 3520               | [5cf6d495ff](https://linux-hardware.org/?probe=5cf6d495ff) | Oct 08, 2022 |
| Lenovo        | IdeaPad Z500 5931           | [76791672ad](https://linux-hardware.org/?probe=76791672ad) | Oct 08, 2022 |
| Dell          | Inspiron 3537               | [39b5d635aa](https://linux-hardware.org/?probe=39b5d635aa) | Oct 08, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [b3b9f964b7](https://linux-hardware.org/?probe=b3b9f964b7) | Oct 08, 2022 |
| Standard      | MB40II                      | [97b446abda](https://linux-hardware.org/?probe=97b446abda) | Oct 08, 2022 |
| Unknown       | Unknown                     | [b941499384](https://linux-hardware.org/?probe=b941499384) | Oct 08, 2022 |
| Quanta        | TWS                         | [f7ba149979](https://linux-hardware.org/?probe=f7ba149979) | Oct 08, 2022 |
| Samsung       | RC530/RC730                 | [ee62bfc634](https://linux-hardware.org/?probe=ee62bfc634) | Oct 07, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [dc99eb14fb](https://linux-hardware.org/?probe=dc99eb14fb) | Oct 07, 2022 |
| Timi          | RedmiBook Pro 15S           | [108ff1fbdd](https://linux-hardware.org/?probe=108ff1fbdd) | Oct 07, 2022 |
| Apple         | MacBookPro9,2               | [acc90115ba](https://linux-hardware.org/?probe=acc90115ba) | Oct 06, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [2bcb266a0a](https://linux-hardware.org/?probe=2bcb266a0a) | Oct 06, 2022 |
| Fujitsu       | LIFEBOOK E752               | [b7c6acd46c](https://linux-hardware.org/?probe=b7c6acd46c) | Oct 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [19c7d98b00](https://linux-hardware.org/?probe=19c7d98b00) | Oct 06, 2022 |
| ASUSTek       | X580VD                      | [16d2a296c8](https://linux-hardware.org/?probe=16d2a296c8) | Oct 06, 2022 |
| Positivo      | W940SU2                     | [d403edabc4](https://linux-hardware.org/?probe=d403edabc4) | Oct 06, 2022 |
| HP            | ProBook 650 G2              | [9a79250780](https://linux-hardware.org/?probe=9a79250780) | Oct 06, 2022 |
| Sony          | SVF15A13SAB                 | [7c39add556](https://linux-hardware.org/?probe=7c39add556) | Oct 06, 2022 |
| HONOR         | BOD-WXX9                    | [26c4b5f06a](https://linux-hardware.org/?probe=26c4b5f06a) | Oct 06, 2022 |
| ASUSTek       | 1001PXD                     | [524e4ab046](https://linux-hardware.org/?probe=524e4ab046) | Oct 06, 2022 |
| ASUSTek       | X55U                        | [88b9f9be12](https://linux-hardware.org/?probe=88b9f9be12) | Oct 05, 2022 |
| Toshiba       | Satellite L10W-B-101        | [403446f5ce](https://linux-hardware.org/?probe=403446f5ce) | Oct 05, 2022 |
| HP            | EliteBook 8470p             | [4ba28bc3a8](https://linux-hardware.org/?probe=4ba28bc3a8) | Oct 05, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Linux_Mint/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Linux Mint 20.3 | 1525      | 18.01%  |
| Linux Mint 20.2 | 1320      | 15.59%  |
| Linux Mint 19.3 | 1226      | 14.48%  |
| Linux Mint 20.1 | 1222      | 14.43%  |
| Linux Mint 20   | 1113      | 13.14%  |
| Linux Mint 21   | 707       | 8.35%   |
| Linux Mint 19.1 | 473       | 5.59%   |
| Linux Mint 19.2 | 425       | 5.02%   |
| Linux Mint 19   | 193       | 2.28%   |
| Linux Mint 18.3 | 150       | 1.77%   |
| Linux Mint 21.1 | 63        | 0.74%   |
| Linux Mint 18.2 | 21        | 0.25%   |
| Linux Mint 18.1 | 12        | 0.14%   |
| Linux Mint 18   | 10        | 0.12%   |
| Linux Mint 17.3 | 4         | 0.05%   |
| Linux Mint 17   | 2         | 0.02%   |
| Linux Mint 17.2 | 1         | 0.01%   |
| Linux Mint 15   | 1         | 0.01%   |
| Linux Mint 13   | 1         | 0.01%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| Linux Mint | 7890      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.4.0-91-generic  | 400       | 4.26%   |
| 5.4.0-58-generic  | 282       | 3%      |
| 5.4.0-74-generic  | 263       | 2.8%    |
| 5.4.0-42-generic  | 218       | 2.32%   |
| 5.0.0-32-generic  | 212       | 2.26%   |
| 5.15.0-56-generic | 197       | 2.1%    |
| 5.4.0-65-generic  | 175       | 1.86%   |
| 5.4.0-80-generic  | 160       | 1.7%    |
| 5.4.0-77-generic  | 156       | 1.66%   |
| 5.4.0-66-generic  | 156       | 1.66%   |
| 5.4.0-81-generic  | 152       | 1.62%   |
| 5.4.0-72-generic  | 144       | 1.53%   |
| 5.4.0-100-generic | 142       | 1.51%   |
| 5.4.0-73-generic  | 139       | 1.48%   |
| 5.4.0-122-generic | 136       | 1.45%   |
| 5.4.0-70-generic  | 132       | 1.41%   |
| 4.15.0-20-generic | 129       | 1.37%   |
| 4.15.0-54-generic | 128       | 1.36%   |
| 5.4.0-90-generic  | 127       | 1.35%   |
| 5.15.0-52-generic | 123       | 1.31%   |
| 5.4.0-89-generic  | 122       | 1.3%    |
| 5.4.0-107-generic | 121       | 1.29%   |
| 5.4.0-26-generic  | 116       | 1.24%   |
| 5.4.0-88-generic  | 115       | 1.23%   |
| 5.4.0-109-generic | 111       | 1.18%   |
| 5.4.0-48-generic  | 110       | 1.17%   |
| 5.15.0-41-generic | 104       | 1.11%   |
| 5.15.0-47-generic | 99        | 1.05%   |
| 5.4.0-96-generic  | 98        | 1.04%   |
| 5.15.0-46-generic | 95        | 1.01%   |
| 5.3.0-46-generic  | 92        | 0.98%   |
| 5.4.0-84-generic  | 91        | 0.97%   |
| 5.4.0-121-generic | 86        | 0.92%   |
| 5.15.0-48-generic | 83        | 0.88%   |
| 5.15.0-53-generic | 82        | 0.87%   |
| 5.3.0-51-generic  | 79        | 0.84%   |
| 5.3.0-53-generic  | 78        | 0.83%   |
| 5.4.0-104-generic | 77        | 0.82%   |
| 5.4.0-52-generic  | 75        | 0.8%    |
| 5.4.0-99-generic  | 74        | 0.79%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 4617      | 55.27%  |
| 4.15.0  | 1075      | 12.87%  |
| 5.15.0  | 833       | 9.97%   |
| 5.3.0   | 516       | 6.18%   |
| 5.0.0   | 321       | 3.84%   |
| 5.13.0  | 191       | 2.29%   |
| 5.8.0   | 177       | 2.12%   |
| 5.11.0  | 162       | 1.94%   |
| 4.10.0  | 51        | 0.61%   |
| 5.14.0  | 38        | 0.45%   |
| 4.18.0  | 36        | 0.43%   |
| 4.4.0   | 33        | 0.4%    |
| 4.13.0  | 32        | 0.38%   |
| 5.10.0  | 22        | 0.26%   |
| 5.6.0   | 13        | 0.16%   |
| 4.8.0   | 11        | 0.13%   |
| 5.7.1   | 8         | 0.1%    |
| 6.0.0   | 7         | 0.08%   |
| 5.17.0  | 6         | 0.07%   |
| 5.9.8   | 4         | 0.05%   |
| 5.9.0   | 4         | 0.05%   |
| 5.9.1   | 3         | 0.04%   |
| 5.7.11  | 3         | 0.04%   |
| 5.7.0   | 3         | 0.04%   |
| 5.5.0   | 3         | 0.04%   |
| 5.4.2   | 3         | 0.04%   |
| 5.18.2  | 3         | 0.04%   |
| 5.18.12 | 3         | 0.04%   |
| 5.17.5  | 3         | 0.04%   |
| Unknown | 3         | 0.04%   |
| 5.9.4   | 2         | 0.02%   |
| 5.9.10  | 2         | 0.02%   |
| 5.8.9   | 2         | 0.02%   |
| 5.8.16  | 2         | 0.02%   |
| 5.8.10  | 2         | 0.02%   |
| 5.6.2   | 2         | 0.02%   |
| 5.3.8   | 2         | 0.02%   |
| 5.3.6   | 2         | 0.02%   |
| 5.3.11  | 2         | 0.02%   |
| 5.2.0   | 2         | 0.02%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 4625      | 55.42%  |
| 4.15    | 1077      | 12.9%   |
| 5.15    | 849       | 10.17%  |
| 5.3     | 527       | 6.31%   |
| 5.0     | 324       | 3.88%   |
| 5.13    | 196       | 2.35%   |
| 5.8     | 187       | 2.24%   |
| 5.11    | 165       | 1.98%   |
| 4.10    | 51        | 0.61%   |
| 5.14    | 44        | 0.53%   |
| 4.18    | 38        | 0.46%   |
| 5.10    | 34        | 0.41%   |
| 4.4     | 33        | 0.4%    |
| 4.13    | 33        | 0.4%    |
| 5.6     | 19        | 0.23%   |
| 5.9     | 18        | 0.22%   |
| 5.7     | 16        | 0.19%   |
| 5.17    | 13        | 0.16%   |
| 6.0     | 11        | 0.13%   |
| 5.18    | 11        | 0.13%   |
| 4.8     | 11        | 0.13%   |
| 5.16    | 9         | 0.11%   |
| 5.12    | 9         | 0.11%   |
| 5.5     | 6         | 0.07%   |
| 5.1     | 6         | 0.07%   |
| 5.2     | 5         | 0.06%   |
| 4.19    | 5         | 0.06%   |
| 5.19    | 4         | 0.05%   |
| 4.20    | 3         | 0.04%   |
| Unknown | 3         | 0.04%   |
| 4.16    | 2         | 0.02%   |
| 3.13    | 2         | 0.02%   |
| 6.1     | 1         | 0.01%   |
| 5       | 1         | 0.01%   |
| 4.7     | 1         | 0.01%   |
| 4.17    | 1         | 0.01%   |
| 4.12    | 1         | 0.01%   |
| 4.11    | 1         | 0.01%   |
| 3.8     | 1         | 0.01%   |
| 3.2     | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 7485      | 94.82%  |
| i686   | 409       | 5.18%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| X-Cinnamon    | 4529      | 55.86%  |
| MATE          | 894       | 11.03%  |
| Cinnamon      | 879       | 10.84%  |
| XFCE          | 841       | 10.37%  |
| Unknown       | 705       | 8.7%    |
| GNOME         | 200       | 2.47%   |
| KDE5          | 22        | 0.27%   |
| KDE           | 17        | 0.21%   |
| i3            | 9         | 0.11%   |
| Deepin        | 3         | 0.04%   |
| Budgie        | 2         | 0.02%   |
| qtile         | 1         | 0.01%   |
| Pantheon      | 1         | 0.01%   |
| openbox       | 1         | 0.01%   |
| LXQt          | 1         | 0.01%   |
| LXDE          | 1         | 0.01%   |
| KDE4          | 1         | 0.01%   |
| GNOME Classic | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 7873      | 99.67%  |
| Wayland | 13        | 0.16%   |
| Tty     | 8         | 0.1%    |
| Unknown | 5         | 0.06%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 4759      | 59.08%  |
| LightDM | 1876      | 23.29%  |
| TDM     | 1331      | 16.52%  |
| MDM     | 40        | 0.5%    |
| GDM     | 23        | 0.29%   |
| SDDM    | 17        | 0.21%   |
| GDM3    | 8         | 0.1%    |
| LXDM    | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 2065      | 25.79%  |
| de_DE   | 1066      | 13.31%  |
| Unknown | 936       | 11.69%  |
| pt_BR   | 679       | 8.48%   |
| ru_RU   | 353       | 4.41%   |
| fr_FR   | 321       | 4.01%   |
| en_GB   | 310       | 3.87%   |
| C       | 276       | 3.45%   |
| it_IT   | 192       | 2.4%    |
| pl_PL   | 162       | 2.02%   |
| es_ES   | 158       | 1.97%   |
| en_CA   | 149       | 1.86%   |
| en_IN   | 102       | 1.27%   |
| en_AU   | 102       | 1.27%   |
| nl_NL   | 78        | 0.97%   |
| cs_CZ   | 62        | 0.77%   |
| es_MX   | 61        | 0.76%   |
| en_ZA   | 59        | 0.74%   |
| hu_HU   | 56        | 0.7%    |
| es_AR   | 53        | 0.66%   |
| pt_PT   | 48        | 0.6%    |
| de_AT   | 47        | 0.59%   |
| ru_UA   | 45        | 0.56%   |
| de_CH   | 40        | 0.5%    |
| tr_TR   | 35        | 0.44%   |
| sv_SE   | 31        | 0.39%   |
| es_CL   | 29        | 0.36%   |
| fr_CA   | 27        | 0.34%   |
| fi_FI   | 25        | 0.31%   |
| el_GR   | 25        | 0.31%   |
| es_CO   | 23        | 0.29%   |
| zh_CN   | 22        | 0.27%   |
| fr_BE   | 22        | 0.27%   |
| sk_SK   | 21        | 0.26%   |
| bg_BG   | 21        | 0.26%   |
| en_NZ   | 20        | 0.25%   |
| en_IE   | 20        | 0.25%   |
| nl_BE   | 18        | 0.22%   |
| uk_UA   | 16        | 0.2%    |
| en_PH   | 16        | 0.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 4106      | 51.45%  |
| BIOS | 3875      | 48.55%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 6924      | 86.73%  |
| Unknown  | 644       | 8.07%   |
| Overlay  | 253       | 3.17%   |
| Btrfs    | 99        | 1.24%   |
| Xfs      | 18        | 0.23%   |
| Ext3     | 16        | 0.2%    |
| Ext2     | 12        | 0.15%   |
| Zfs      | 11        | 0.14%   |
| Aufs     | 2         | 0.03%   |
| XXXXX    | 1         | 0.01%   |
| Reiserfs | 1         | 0.01%   |
| Jfs      | 1         | 0.01%   |
| ExX4     | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 4839      | 60.47%  |
| GPT     | 2196      | 27.44%  |
| MBR     | 967       | 12.08%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 7491      | 94.39%  |
| Yes       | 445       | 5.61%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 6523      | 82.09%  |
| Yes       | 1423      | 17.91%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 1611      | 20.42%  |
| Lenovo              | 1416      | 17.95%  |
| Dell                | 1176      | 14.9%   |
| Acer                | 826       | 10.47%  |
| ASUSTek Computer    | 784       | 9.94%   |
| Toshiba             | 289       | 3.66%   |
| Samsung Electronics | 251       | 3.18%   |
| Apple               | 182       | 2.31%   |
| Sony                | 144       | 1.83%   |
| MSI                 | 112       | 1.42%   |
| Medion              | 75        | 0.95%   |
| Positivo            | 70        | 0.89%   |
| Google              | 64        | 0.81%   |
| Fujitsu             | 63        | 0.8%    |
| Unknown             | 53        | 0.67%   |
| Notebook            | 52        | 0.66%   |
| Packard Bell        | 47        | 0.6%    |
| HUAWEI              | 44        | 0.56%   |
| Fujitsu Siemens     | 43        | 0.54%   |
| LG Electronics      | 26        | 0.33%   |
| Alienware           | 24        | 0.3%    |
| Timi                | 20        | 0.25%   |
| Intel               | 20        | 0.25%   |
| Gateway             | 20        | 0.25%   |
| eMachines           | 19        | 0.24%   |
| Chuwi               | 19        | 0.24%   |
| Itautec             | 18        | 0.23%   |
| Digibras            | 18        | 0.23%   |
| GPU Company         | 16        | 0.2%    |
| Semp Toshiba        | 15        | 0.19%   |
| Panasonic           | 15        | 0.19%   |
| Clevo               | 15        | 0.19%   |
| TUXEDO              | 13        | 0.16%   |
| AMI                 | 12        | 0.15%   |
| Gigabyte Technology | 11        | 0.14%   |
| OEM                 | 9         | 0.11%   |
| Schenker            | 8         | 0.1%    |
| Compaq              | 8         | 0.1%    |
| Compal              | 8         | 0.1%    |
| Thomson             | 7         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Unknown                      | 87        | 1.1%    |
| HP Notebook                  | 60        | 0.76%   |
| HP Pavilion g6               | 42        | 0.53%   |
| HP Pavilion dv6              | 36        | 0.46%   |
| HP Pavilion 15               | 30        | 0.38%   |
| ASUS P50IJ                   | 30        | 0.38%   |
| HP Pavilion dv7              | 29        | 0.37%   |
| HP Laptop 15-bw0xx           | 29        | 0.37%   |
| Positivo Mobile              | 25        | 0.32%   |
| Dell Inspiron 15-3567        | 24        | 0.3%    |
| Dell Latitude E6420          | 21        | 0.27%   |
| HP Laptop 15-bs0xx           | 20        | 0.25%   |
| HP 15                        | 20        | 0.25%   |
| Dell Latitude E6410          | 20        | 0.25%   |
| Dell Inspiron 1545           | 20        | 0.25%   |
| HP Pavilion g7               | 18        | 0.23%   |
| Dell Latitude E6430          | 18        | 0.23%   |
| HP Pavilion Notebook         | 17        | 0.22%   |
| Dell Latitude E6540          | 17        | 0.22%   |
| Dell Latitude E6400          | 17        | 0.22%   |
| Apple MacBookPro9,2          | 17        | 0.22%   |
| Apple MacBookPro8,1          | 17        | 0.22%   |
| Samsung 300E4C/300E5C/300E7C | 15        | 0.19%   |
| HP ProBook 4530s             | 15        | 0.19%   |
| Dell Inspiron 1525           | 15        | 0.19%   |
| HP ProBook 4540s             | 14        | 0.18%   |
| HP EliteBook 8460p           | 14        | 0.18%   |
| HP EliteBook 840 G1          | 14        | 0.18%   |
| Lenovo G50-70 20351          | 13        | 0.16%   |
| HP Pavilion 17               | 13        | 0.16%   |
| HP Laptop 15-db0xxx          | 13        | 0.16%   |
| HP Laptop 15-bs1xx           | 13        | 0.16%   |
| HP EliteBook 8470p           | 13        | 0.16%   |
| HP 2000                      | 13        | 0.16%   |
| Dell Latitude E6510          | 13        | 0.16%   |
| Dell Inspiron 3583           | 13        | 0.16%   |
| Samsung 340XAA/350XAA/550XAA | 12        | 0.15%   |
| HP G42                       | 12        | 0.15%   |
| Dell Latitude D630           | 12        | 0.15%   |
| Dell Inspiron 5570           | 12        | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 640       | 8.11%   |
| Acer Aspire           | 614       | 7.78%   |
| Dell Inspiron         | 457       | 5.79%   |
| Dell Latitude         | 419       | 5.31%   |
| Lenovo IdeaPad        | 387       | 4.9%    |
| HP Pavilion           | 381       | 4.83%   |
| HP Laptop             | 260       | 3.3%    |
| Toshiba Satellite     | 244       | 3.09%   |
| HP EliteBook          | 217       | 2.75%   |
| HP ProBook            | 213       | 2.7%    |
| ASUS VivoBook         | 105       | 1.33%   |
| Dell Vostro           | 92        | 1.17%   |
| Unknown               | 87        | 1.1%    |
| HP Compaq             | 74        | 0.94%   |
| Dell XPS              | 74        | 0.94%   |
| HP Notebook           | 60        | 0.76%   |
| Fujitsu LIFEBOOK      | 57        | 0.72%   |
| Dell Precision        | 53        | 0.67%   |
| HP 250                | 46        | 0.58%   |
| HP ENVY               | 45        | 0.57%   |
| Acer Swift            | 45        | 0.57%   |
| Packard Bell EasyNote | 41        | 0.52%   |
| HP ZBook              | 39        | 0.49%   |
| Acer TravelMate       | 35        | 0.44%   |
| Lenovo Legion         | 32        | 0.41%   |
| ASUS ZenBook          | 32        | 0.41%   |
| Acer Extensa          | 31        | 0.39%   |
| HP 255                | 30        | 0.38%   |
| ASUS P50IJ            | 30        | 0.38%   |
| Apple MacBookPro8     | 27        | 0.34%   |
| Lenovo Yoga           | 26        | 0.33%   |
| HP Presario           | 26        | 0.33%   |
| HP OMEN               | 26        | 0.33%   |
| ASUS ASUS             | 26        | 0.33%   |
| Acer Nitro            | 26        | 0.33%   |
| Positivo Mobile       | 25        | 0.32%   |
| Fujitsu Siemens AMILO | 23        | 0.29%   |
| ASUS TUF              | 23        | 0.29%   |
| HP 15                 | 22        | 0.28%   |
| Apple MacBookPro9     | 22        | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 764       | 9.68%   |
| 2012    | 726       | 9.2%    |
| 2013    | 649       | 8.23%   |
| 2019    | 570       | 7.22%   |
| 2010    | 523       | 6.63%   |
| 2018    | 522       | 6.62%   |
| 2020    | 510       | 6.46%   |
| 2017    | 493       | 6.25%   |
| 2016    | 461       | 5.84%   |
| 2015    | 460       | 5.83%   |
| 2021    | 457       | 5.79%   |
| 2014    | 456       | 5.78%   |
| 2008    | 436       | 5.53%   |
| 2009    | 346       | 4.39%   |
| 2007    | 251       | 3.18%   |
| 2006    | 104       | 1.32%   |
| 2022    | 103       | 1.31%   |
| 2005    | 34        | 0.43%   |
| 2004    | 12        | 0.15%   |
| Unknown | 10        | 0.13%   |
| 2003    | 3         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 7890      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 7040      | 88.58%  |
| Enabled  | 908       | 11.42%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 7818      | 99.07%  |
| Yes  | 73        | 0.93%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 2309      | 28.92%  |
| 3.01-4.0    | 2235      | 27.99%  |
| 8.01-16.0   | 1235      | 15.47%  |
| 16.01-24.0  | 996       | 12.47%  |
| 1.01-2.0    | 590       | 7.39%   |
| 32.01-64.0  | 228       | 2.86%   |
| 2.01-3.0    | 210       | 2.63%   |
| 0.51-1.0    | 89        | 1.11%   |
| 24.01-32.0  | 60        | 0.75%   |
| 64.01-256.0 | 31        | 0.39%   |
| 0.01-0.5    | 1         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 3685      | 42.53%  |
| 2.01-3.0   | 2193      | 25.31%  |
| 3.01-4.0   | 935       | 10.79%  |
| 0.51-1.0   | 820       | 9.46%   |
| 4.01-8.0   | 796       | 9.19%   |
| 8.01-16.0  | 149       | 1.72%   |
| 0.01-0.5   | 65        | 0.75%   |
| 16.01-24.0 | 15        | 0.17%   |
| Unknown    | 4         | 0.05%   |
| 24.01-32.0 | 2         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 5821      | 72.29%  |
| 2      | 1903      | 23.63%  |
| 3      | 222       | 2.76%   |
| 0      | 65        | 0.81%   |
| 4      | 28        | 0.35%   |
| 5      | 9         | 0.11%   |
| 7      | 2         | 0.02%   |
| 9      | 1         | 0.01%   |
| 6      | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 4243      | 53.49%  |
| Yes       | 3689      | 46.51%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 6777      | 85.62%  |
| No        | 1138      | 14.38%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 7734      | 97.95%  |
| No        | 162       | 2.05%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 5542      | 69.41%  |
| No        | 2442      | 30.59%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| Germany      | 1234      | 15.54%  |
| USA          | 1177      | 14.82%  |
| Brazil       | 927       | 11.68%  |
| Russia       | 567       | 7.14%   |
| France       | 354       | 4.46%   |
| UK           | 293       | 3.69%   |
| Italy        | 247       | 3.11%   |
| Spain        | 207       | 2.61%   |
| Poland       | 204       | 2.57%   |
| Canada       | 199       | 2.51%   |
| Netherlands  | 158       | 1.99%   |
| Ukraine      | 156       | 1.96%   |
| India        | 124       | 1.56%   |
| Australia    | 117       | 1.47%   |
| Mexico       | 96        | 1.21%   |
| Czechia      | 90        | 1.13%   |
| Belgium      | 90        | 1.13%   |
| Switzerland  | 85        | 1.07%   |
| Austria      | 84        | 1.06%   |
| Portugal     | 79        | 0.99%   |
| Turkey       | 74        | 0.93%   |
| Argentina    | 73        | 0.92%   |
| Hungary      | 71        | 0.89%   |
| Sweden       | 67        | 0.84%   |
| South Africa | 64        | 0.81%   |
| Greece       | 58        | 0.73%   |
| Finland      | 51        | 0.64%   |
| Bulgaria     | 51        | 0.64%   |
| Romania      | 47        | 0.59%   |
| Colombia     | 39        | 0.49%   |
| Slovakia     | 38        | 0.48%   |
| Denmark      | 38        | 0.48%   |
| Chile        | 37        | 0.47%   |
| Norway       | 34        | 0.43%   |
| Indonesia    | 33        | 0.42%   |
| Belarus      | 31        | 0.39%   |
| Ireland      | 28        | 0.35%   |
| New Zealand  | 27        | 0.34%   |
| China        | 26        | 0.33%   |
| Serbia       | 23        | 0.29%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 147       | 1.75%   |
| Berlin            | 118       | 1.41%   |
| Sao Paulo         | 102       | 1.21%   |
| St Petersburg     | 64        | 0.76%   |
| Rio de Janeiro    | 57        | 0.68%   |
| Vienna            | 56        | 0.67%   |
| Rockville         | 54        | 0.64%   |
| Paris             | 54        | 0.64%   |
| Kyiv              | 52        | 0.62%   |
| Milan             | 47        | 0.56%   |
| Warsaw            | 45        | 0.54%   |
| Hamburg           | 44        | 0.52%   |
| Munich            | 41        | 0.49%   |
| Frankfurt am Main | 37        | 0.44%   |
| Sydney            | 35        | 0.42%   |
| Madrid            | 33        | 0.39%   |
| Chicago           | 32        | 0.38%   |
| Porto Alegre      | 31        | 0.37%   |
| Cologne           | 30        | 0.36%   |
| Prague            | 29        | 0.35%   |
| Istanbul          | 29        | 0.35%   |
| Belo Horizonte    | 29        | 0.35%   |
| Amsterdam         | 29        | 0.35%   |
| Curitiba          | 28        | 0.33%   |
| Sofia             | 26        | 0.31%   |
| Stuttgart         | 25        | 0.3%    |
| Rome              | 25        | 0.3%    |
| Barcelona         | 25        | 0.3%    |
| Athens            | 25        | 0.3%    |
| Zurich            | 24        | 0.29%   |
| Melbourne         | 24        | 0.29%   |
| London            | 24        | 0.29%   |
| Budapest          | 24        | 0.29%   |
| Brasília         | 23        | 0.27%   |
| Toronto           | 22        | 0.26%   |
| Krasnodar         | 22        | 0.26%   |
| Helsinki          | 22        | 0.26%   |
| Fortaleza         | 22        | 0.26%   |
| Montreal          | 21        | 0.25%   |
| Mexico City       | 21        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 1349      | 1704   | 13.92%  |
| Seagate                   | 1323      | 1628   | 13.65%  |
| Samsung Electronics       | 1241      | 1626   | 12.81%  |
| Toshiba                   | 882       | 1068   | 9.1%    |
| Unknown                   | 619       | 823    | 6.39%   |
| SanDisk                   | 518       | 698    | 5.35%   |
| Kingston                  | 516       | 628    | 5.33%   |
| Hitachi                   | 394       | 480    | 4.07%   |
| Crucial                   | 300       | 411    | 3.1%    |
| HGST                      | 280       | 361    | 2.89%   |
| SK hynix                  | 277       | 317    | 2.86%   |
| Intel                     | 224       | 289    | 2.31%   |
| Micron Technology         | 143       | 180    | 1.48%   |
| A-DATA Technology         | 135       | 175    | 1.39%   |
| China                     | 100       | 124    | 1.03%   |
| Fujitsu                   | 94        | 119    | 0.97%   |
| Apple                     | 89        | 109    | 0.92%   |
| KIOXIA                    | 71        | 88     | 0.73%   |
| LITEON                    | 61        | 79     | 0.63%   |
| Intenso                   | 53        | 64     | 0.55%   |
| PNY                       | 51        | 60     | 0.53%   |
| LITEONIT                  | 42        | 51     | 0.43%   |
| Transcend                 | 39        | 49     | 0.4%    |
| SPCC                      | 39        | 51     | 0.4%    |
| OCZ                       | 37        | 46     | 0.38%   |
| Phison                    | 36        | 43     | 0.37%   |
| Patriot                   | 36        | 51     | 0.37%   |
| Unknown                   | 33        | 37     | 0.34%   |
| GOODRAM                   | 31        | 42     | 0.32%   |
| KingSpec                  | 30        | 36     | 0.31%   |
| JMicron Technology        | 29        | 38     | 0.3%    |
| Netac                     | 26        | 28     | 0.27%   |
| Apacer                    | 21        | 24     | 0.22%   |
| SSSTC                     | 18        | 18     | 0.19%   |
| Plextor                   | 17        | 21     | 0.18%   |
| Corsair                   | 17        | 18     | 0.18%   |
| Team                      | 15        | 17     | 0.15%   |
| Micron/Crucial Technology | 15        | 19     | 0.15%   |
| Lexar                     | 15        | 20     | 0.15%   |
| Silicon Motion            | 14        | 16     | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                 | 157       | 1.57%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 151       | 1.51%   |
| Seagate ST1000LM035-1RK172 1TB         | 147       | 1.47%   |
| Kingston SA400S37240G 240GB SSD        | 142       | 1.42%   |
| Toshiba MQ01ABD100 1TB                 | 139       | 1.39%   |
| Toshiba MQ01ABF050 500GB               | 111       | 1.11%   |
| Unknown MMC Card  64GB                 | 105       | 1.05%   |
| Seagate ST9500325AS 500GB              | 97        | 0.97%   |
| Seagate ST500LT012-1DG142 500GB        | 93        | 0.93%   |
| Toshiba MQ04ABF100 1TB                 | 86        | 0.86%   |
| Unknown MMC Card  128GB                | 72        | 0.72%   |
| Seagate ST500LM012 HN-M500MBB 500GB    | 67        | 0.67%   |
| Kingston SA400S37480G 480GB SSD        | 67        | 0.67%   |
| Samsung SSD 860 EVO 500GB              | 66        | 0.66%   |
| HGST HTS721010A9E630 1TB               | 61        | 0.61%   |
| HGST HTS545050A7E680 500GB             | 56        | 0.56%   |
| Samsung SSD 850 EVO 500GB              | 55        | 0.55%   |
| Kingston SA400S37120G 120GB SSD        | 55        | 0.55%   |
| Unknown MMC Card  16GB                 | 54        | 0.54%   |
| Samsung SSD 850 EVO 250GB              | 51        | 0.51%   |
| WDC WD10JPVX-22JC3T0 1TB               | 49        | 0.49%   |
| HGST HTS541010A9E680 1TB               | 47        | 0.47%   |
| Seagate ST500LT012-9WS142 500GB        | 46        | 0.46%   |
| Samsung SSD 860 EVO 1TB                | 45        | 0.45%   |
| SanDisk NVMe SSD Drive 512GB           | 43        | 0.43%   |
| Crucial CT500MX500SSD1 500GB           | 43        | 0.43%   |
| Samsung NVMe SSD Drive 512GB           | 42        | 0.42%   |
| SanDisk SSD PLUS 240GB                 | 40        | 0.4%    |
| Seagate Expansion 4TB                  | 37        | 0.37%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 37        | 0.37%   |
| Crucial CT1000MX500SSD1 1TB            | 37        | 0.37%   |
| WDC WD10SPZX-24Z10 1TB                 | 36        | 0.36%   |
| WDC WD5000LPVX-22V0TT0 500GB           | 34        | 0.34%   |
| WDC WD10SPZX-21Z10T0 1TB               | 34        | 0.34%   |
| Seagate ST9320325AS 320GB              | 34        | 0.34%   |
| Samsung SSD 840 EVO 500GB              | 34        | 0.34%   |
| Crucial CT240BX500SSD1 240GB           | 34        | 0.34%   |
| Seagate ST9500420AS 500GB              | 33        | 0.33%   |
| Seagate ST1000LM048-2E7172 1TB         | 33        | 0.33%   |
| Unknown                                | 33        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1302      | 1594   | 32.7%   |
| WDC                 | 1007      | 1246   | 25.29%  |
| Toshiba             | 723       | 862    | 18.16%  |
| Hitachi             | 394       | 480    | 9.89%   |
| HGST                | 280       | 361    | 7.03%   |
| Samsung Electronics | 99        | 117    | 2.49%   |
| Fujitsu             | 93        | 117    | 2.34%   |
| Unknown             | 28        | 38     | 0.7%    |
| Apple               | 15        | 16     | 0.38%   |
| ASMT                | 6         | 8      | 0.15%   |
| JMicron Technology  | 4         | 5      | 0.1%    |
| HGST HTS            | 4         | 6      | 0.1%    |
| USB3.0              | 3         | 4      | 0.08%   |
| USB                 | 2         | 2      | 0.05%   |
| PHD 3.0             | 2         | 2      | 0.05%   |
| Initio              | 2         | 2      | 0.05%   |
| IBM/Hitachi         | 2         | 2      | 0.05%   |
| HGST HUS            | 2         | 2      | 0.05%   |
| ASMedia             | 2         | 2      | 0.05%   |
| Apricorn            | 2         | 4      | 0.05%   |
| SILICONMOTION       | 1         | 2      | 0.03%   |
| SAGE                | 1         | 2      | 0.03%   |
| Pioneer             | 1         | 1      | 0.03%   |
| Maxtor              | 1         | 1      | 0.03%   |
| KESU                | 1         | 1      | 0.03%   |
| Intenso             | 1         | 1      | 0.03%   |
| Inateck             | 1         | 1      | 0.03%   |
| Dell                | 1         | 1      | 0.03%   |
| ASUSTOR             | 1         | 2      | 0.03%   |
| APPLE HD            | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 722       | 948    | 21.71%  |
| Kingston            | 438       | 539    | 13.17%  |
| SanDisk             | 376       | 509    | 11.31%  |
| Crucial             | 284       | 395    | 8.54%   |
| WDC                 | 200       | 250    | 6.02%   |
| A-DATA Technology   | 120       | 159    | 3.61%   |
| China               | 100       | 124    | 3.01%   |
| Intel               | 84        | 119    | 2.53%   |
| Toshiba             | 64        | 78     | 1.92%   |
| Micron Technology   | 63        | 87     | 1.89%   |
| SK hynix            | 59        | 74     | 1.77%   |
| LITEON              | 58        | 76     | 1.74%   |
| Apple               | 49        | 55     | 1.47%   |
| PNY                 | 48        | 57     | 1.44%   |
| Intenso             | 44        | 53     | 1.32%   |
| LITEONIT            | 42        | 51     | 1.26%   |
| OCZ                 | 37        | 46     | 1.11%   |
| Transcend           | 36        | 46     | 1.08%   |
| SPCC                | 36        | 48     | 1.08%   |
| Patriot             | 34        | 49     | 1.02%   |
| KingSpec            | 30        | 36     | 0.9%    |
| GOODRAM             | 30        | 41     | 0.9%    |
| Netac               | 24        | 26     | 0.72%   |
| Apacer              | 20        | 23     | 0.6%    |
| Plextor             | 15        | 19     | 0.45%   |
| Lexar               | 15        | 20     | 0.45%   |
| Team                | 14        | 16     | 0.42%   |
| JMicron Technology  | 14        | 19     | 0.42%   |
| Unknown             | 14        | 17     | 0.42%   |
| Corsair             | 12        | 13     | 0.36%   |
| KingDian            | 11        | 18     | 0.33%   |
| Teclast             | 10        | 11     | 0.3%    |
| Gigabyte Technology | 10        | 12     | 0.3%    |
| TO Exter            | 9         | 11     | 0.27%   |
| Dogfish             | 9         | 15     | 0.27%   |
| Seagate             | 8         | 12     | 0.24%   |
| Hewlett-Packard     | 8         | 9      | 0.24%   |
| BHT                 | 8         | 8      | 0.24%   |
| KingFast            | 7         | 7      | 0.21%   |
| Union Memory        | 6         | 7      | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 3861      | 4883   | 41.43%  |
| SSD     | 3111      | 4308   | 33.38%  |
| NVMe    | 1596      | 2068   | 17.12%  |
| MMC     | 617       | 816    | 6.62%   |
| Unknown | 135       | 167    | 1.45%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 6276      | 8953   | 71.37%  |
| NVMe | 1582      | 2044   | 17.99%  |
| MMC  | 617       | 816    | 7.02%   |
| SAS  | 319       | 429    | 3.63%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 4785      | 6464   | 69.92%  |
| 0.51-1.0   | 1828      | 2380   | 26.71%  |
| 1.01-2.0   | 156       | 240    | 2.28%   |
| 3.01-4.0   | 56        | 75     | 0.82%   |
| 4.01-10.0  | 18        | 31     | 0.26%   |
| 10.01-20.0 | 1         | 1      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 2676      | 32.66%  |
| 251-500        | 2343      | 28.6%   |
| 501-1000       | 1224      | 14.94%  |
| 51-100         | 622       | 7.59%   |
| 1001-2000      | 439       | 5.36%   |
| 21-50          | 392       | 4.78%   |
| 1-20           | 252       | 3.08%   |
| More than 3000 | 100       | 1.22%   |
| 2001-3000      | 99        | 1.21%   |
| Unknown        | 46        | 0.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 2691      | 31.22%  |
| 21-50          | 2036      | 23.62%  |
| 101-250        | 1343      | 15.58%  |
| 51-100         | 1320      | 15.32%  |
| 251-500        | 674       | 7.82%   |
| 501-1000       | 330       | 3.83%   |
| 1001-2000      | 123       | 1.43%   |
| Unknown        | 46        | 0.53%   |
| More than 3000 | 29        | 0.34%   |
| 2001-3000      | 27        | 0.31%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB           | 20        | 23     | 3.37%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 19        | 19     | 3.2%    |
| Seagate ST1000LM035-1RK172 1TB      | 18        | 25     | 3.03%   |
| HGST HTS545050A7E680 500GB          | 16        | 37     | 2.69%   |
| Seagate ST500LT012-9WS142 500GB     | 15        | 16     | 2.53%   |
| Seagate ST500LT012-1DG142 500GB     | 12        | 13     | 2.02%   |
| Toshiba MQ01ABD100 1TB              | 11        | 12     | 1.85%   |
| Toshiba MQ01ABF050 500GB            | 10        | 11     | 1.68%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 9         | 10     | 1.52%   |
| HGST HTS725050A7E630 500GB          | 9         | 9      | 1.52%   |
| LITEON CV8-8E128-HP 128GB SSD       | 8         | 10     | 1.35%   |
| HGST HTS721010A9E630 1TB            | 8         | 8      | 1.35%   |
| HGST HTS541010A9E680 1TB            | 8         | 8      | 1.35%   |
| Toshiba MK7575GSX 752GB             | 7         | 7      | 1.18%   |
| Hitachi HTS547575A9E384 752GB       | 7         | 7      | 1.18%   |
| Seagate ST9500420AS 500GB           | 6         | 6      | 1.01%   |
| Seagate ST9320325AS 320GB           | 6         | 6      | 1.01%   |
| HGST HTS545050A7E380 500GB          | 6         | 7      | 1.01%   |
| WDC WD10JPVX-22JC3T0 1TB            | 5         | 5      | 0.84%   |
| Toshiba MQ04ABF100 1TB              | 5         | 5      | 0.84%   |
| Toshiba MK3265GSX 320GB             | 5         | 5      | 0.84%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD | 5         | 5      | 0.84%   |
| SanDisk SD8SN8U-128G-1006 128GB SSD | 5         | 7      | 0.84%   |
| Hitachi HTS547550A9E384 500GB       | 5         | 5      | 0.84%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 4         | 4      | 0.67%   |
| WDC WD10JPVX-60JC3T0 1TB            | 4         | 6      | 0.67%   |
| Toshiba MK1652GSX 160GB             | 4         | 4      | 0.67%   |
| Seagate ST9250410AS 250GB           | 4         | 4      | 0.67%   |
| Seagate ST9250315AS 250GB           | 4         | 4      | 0.67%   |
| Seagate ST500LM021-1KJ152 500GB     | 4         | 4      | 0.67%   |
| Seagate ST500LM000-SSHD-8GB         | 4         | 4      | 0.67%   |
| Seagate ST320LT020-9YG142 320GB     | 4         | 4      | 0.67%   |
| Seagate ST2000LM007-1R8174 2TB      | 4         | 4      | 0.67%   |
| Seagate ST1000LM014-1EJ164 1TB      | 4         | 4      | 0.67%   |
| Hitachi HTS545050A7E380 500GB       | 4         | 4      | 0.67%   |
| Hitachi HTS545025B9A300 250GB       | 4         | 4      | 0.67%   |
| Hitachi HTS543232A7A384 320GB       | 4         | 4      | 0.67%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 3         | 3      | 0.51%   |
| WDC WD5000LPVT-22G33T0 500GB        | 3         | 3      | 0.51%   |
| Toshiba MK5059GSXP 500GB            | 3         | 3      | 0.51%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 178       | 196    | 30.07%  |
| Toshiba             | 83        | 90     | 14.02%  |
| WDC                 | 75        | 86     | 12.67%  |
| Hitachi             | 62        | 64     | 10.47%  |
| HGST                | 53        | 75     | 8.95%   |
| SanDisk             | 29        | 34     | 4.9%    |
| Samsung Electronics | 16        | 19     | 2.7%    |
| Kingston            | 16        | 16     | 2.7%    |
| Intel               | 14        | 14     | 2.36%   |
| Crucial             | 12        | 17     | 2.03%   |
| SK hynix            | 8         | 10     | 1.35%   |
| LITEON              | 8         | 10     | 1.35%   |
| Micron Technology   | 5         | 7      | 0.84%   |
| Fujitsu             | 5         | 5      | 0.84%   |
| A-DATA Technology   | 4         | 4      | 0.68%   |
| LITEONIT            | 3         | 3      | 0.51%   |
| China               | 3         | 3      | 0.51%   |
| Apple               | 3         | 3      | 0.51%   |
| OCZ                 | 2         | 2      | 0.34%   |
| KingSpec            | 2         | 2      | 0.34%   |
| XPG                 | 1         | 1      | 0.17%   |
| WDC WDS2            | 1         | 1      | 0.17%   |
| Transcend           | 1         | 1      | 0.17%   |
| SSSTC               | 1         | 1      | 0.17%   |
| PNY                 | 1         | 2      | 0.17%   |
| Patriot             | 1         | 1      | 0.17%   |
| Lenovo              | 1         | 1      | 0.17%   |
| JMicron Technology  | 1         | 1      | 0.17%   |
| JDa                 | 1         | 1      | 0.17%   |
| JD                  | 1         | 1      | 0.17%   |
| HGST HTS            | 1         | 1      | 0.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 178       | 196    | 38.86%  |
| Toshiba             | 78        | 84     | 17.03%  |
| WDC                 | 70        | 81     | 15.28%  |
| Hitachi             | 62        | 64     | 13.54%  |
| HGST                | 53        | 75     | 11.57%  |
| Samsung Electronics | 9         | 12     | 1.97%   |
| Fujitsu             | 5         | 5      | 1.09%   |
| JMicron Technology  | 1         | 1      | 0.22%   |
| HGST HTS            | 1         | 1      | 0.22%   |
| Apple               | 1         | 1      | 0.22%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 455       | 520    | 77.38%  |
| SSD  | 126       | 145    | 21.43%  |
| NVMe | 7         | 7      | 1.19%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-80V0TT0 500GB                   | 2         | 2      | 18.18%  |
| Toshiba THNSN5512GPU7 512GB                    | 1         | 1      | 9.09%   |
| Toshiba MQ01ABF032 320GB                       | 1         | 1      | 9.09%   |
| Toshiba MQ01ABD075 752GB                       | 1         | 1      | 9.09%   |
| Seagate ST9160821AS 160GB                      | 1         | 1      | 9.09%   |
| Seagate ST500LM012 HN-M500MBB 500GB            | 1         | 1      | 9.09%   |
| Seagate ST1000LM 024 HN-M101MBB 1TB            | 1         | 1      | 9.09%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 9.09%   |
| Hitachi HTS547550A9E384 500GB                  | 1         | 1      | 9.09%   |
| HGST HTS545050A7E380 500GB                     | 1         | 1      | 9.09%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Toshiba           | 3         | 3      | 27.27%  |
| Seagate           | 3         | 3      | 27.27%  |
| WDC               | 2         | 2      | 18.18%  |
| Micron Technology | 1         | 1      | 9.09%   |
| Hitachi           | 1         | 1      | 9.09%   |
| HGST              | 1         | 1      | 9.09%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 5119      | 8023   | 61.53%  |
| Works    | 2612      | 3535   | 31.39%  |
| Malfunc  | 577       | 672    | 6.94%   |
| Failed   | 11        | 11     | 0.13%   |
| Limited  | 1         | 1      | 0.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 5911      | 68.37%  |
| AMD                              | 995       | 11.51%  |
| Samsung Electronics              | 479       | 5.54%   |
| SanDisk                          | 277       | 3.2%    |
| SK hynix                         | 206       | 2.38%   |
| Toshiba America Info Systems     | 97        | 1.12%   |
| Kingston Technology Company      | 83        | 0.96%   |
| Micron Technology                | 81        | 0.94%   |
| KIOXIA                           | 74        | 0.86%   |
| Nvidia                           | 69        | 0.8%    |
| Silicon Integrated Systems [SiS] | 63        | 0.73%   |
| Phison Electronics               | 52        | 0.6%    |
| Union Memory (Shenzhen)          | 33        | 0.38%   |
| Solid State Storage Technology   | 27        | 0.31%   |
| Micron/Crucial Technology        | 26        | 0.3%    |
| Apple                            | 24        | 0.28%   |
| Silicon Motion                   | 23        | 0.27%   |
| ADATA Technology                 | 23        | 0.27%   |
| VIA Technologies                 | 17        | 0.2%    |
| Realtek Semiconductor            | 16        | 0.19%   |
| Lite-On Technology               | 12        | 0.14%   |
| Marvell Technology Group         | 11        | 0.13%   |
| JMicron Technology               | 10        | 0.12%   |
| Lenovo                           | 8         | 0.09%   |
| Silicon Image                    | 6         | 0.07%   |
| ASMedia Technology               | 5         | 0.06%   |
| Shenzhen Longsys Electronics     | 4         | 0.05%   |
| Yangtze Memory Technologies      | 3         | 0.03%   |
| Seagate Technology               | 3         | 0.03%   |
| OCZ Technology Group             | 3         | 0.03%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.02%   |
| ULi Electronics                  | 1         | 0.01%   |
| Transcend                        | 1         | 0.01%   |
| Biwin Storage Technology         | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 772       | 8.15%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 745       | 7.86%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 588       | 6.21%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 540       | 5.7%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 439       | 4.63%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 397       | 4.19%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 355       | 3.75%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 281       | 2.97%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 222       | 2.34%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 221       | 2.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 214       | 2.26%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 211       | 2.23%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 182       | 1.92%   |
| Intel Volume Management Device NVMe RAID Controller                              | 151       | 1.59%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 142       | 1.5%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 140       | 1.48%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 138       | 1.46%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 138       | 1.46%   |
| Samsung NVMe SSD Controller 980                                                  | 135       | 1.43%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 135       | 1.43%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 115       | 1.21%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 108       | 1.14%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 107       | 1.13%   |
| Intel Tiger Lake-LP SATA Controller                                              | 100       | 1.06%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 91        | 0.96%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 87        | 0.92%   |
| Intel SSD 660P Series                                                            | 83        | 0.88%   |
| Micron Non-Volatile memory controller                                            | 81        | 0.86%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 79        | 0.83%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 78        | 0.82%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 73        | 0.77%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 68        | 0.72%   |
| Intel Comet Lake SATA AHCI Controller                                            | 66        | 0.7%    |
| SK hynix BC501 NVMe Solid State Drive                                            | 64        | 0.68%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 63        | 0.67%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 62        | 0.65%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 54        | 0.57%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 54        | 0.57%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 53        | 0.56%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 52        | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 6016      | 66.34%  |
| NVMe | 1584      | 17.47%  |
| IDE  | 861       | 9.49%   |
| RAID | 607       | 6.69%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 6605      | 83.71%  |
| AMD          | 1284      | 16.27%  |
| CentaurHauls | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 107       | 1.35%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 105       | 1.33%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 100       | 1.27%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 93        | 1.18%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 92        | 1.16%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 83        | 1.05%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 82        | 1.04%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 75        | 0.95%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 74        | 0.94%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 74        | 0.94%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 72        | 0.91%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 71        | 0.9%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 70        | 0.89%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 67        | 0.85%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 66        | 0.84%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 66        | 0.84%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 65        | 0.82%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 62        | 0.79%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 59        | 0.75%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 57        | 0.72%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 56        | 0.71%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 56        | 0.71%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 56        | 0.71%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 52        | 0.66%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 52        | 0.66%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 52        | 0.66%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 52        | 0.66%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 51        | 0.65%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 50        | 0.63%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 50        | 0.63%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 50        | 0.63%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 48        | 0.61%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 47        | 0.6%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 46        | 0.58%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 46        | 0.58%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 45        | 0.57%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 45        | 0.57%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 44        | 0.56%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 44        | 0.56%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 43        | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1925      | 24.38%  |
| Intel Core i7           | 1386      | 17.55%  |
| Intel Core i3           | 809       | 10.25%  |
| Intel Celeron           | 583       | 7.38%   |
| Intel Core 2 Duo        | 513       | 6.5%    |
| Other                   | 353       | 4.47%   |
| Intel Pentium           | 302       | 3.82%   |
| Intel Atom              | 271       | 3.43%   |
| AMD Ryzen 5             | 237       | 3%      |
| AMD Ryzen 7             | 171       | 2.17%   |
| Intel Pentium Dual-Core | 112       | 1.42%   |
| AMD A6                  | 109       | 1.38%   |
| AMD A4                  | 92        | 1.17%   |
| Intel Pentium Dual      | 83        | 1.05%   |
| AMD A8                  | 73        | 0.92%   |
| Intel Core 2            | 70        | 0.89%   |
| Intel Genuine           | 65        | 0.82%   |
| AMD A10                 | 60        | 0.76%   |
| AMD Ryzen 3             | 56        | 0.71%   |
| AMD E                   | 53        | 0.67%   |
| AMD E1                  | 47        | 0.6%    |
| Intel Pentium Silver    | 46        | 0.58%   |
| AMD E2                  | 42        | 0.53%   |
| AMD Turion 64 X2 Mobile | 41        | 0.52%   |
| Intel Celeron M         | 32        | 0.41%   |
| AMD Ryzen 7 PRO         | 32        | 0.41%   |
| Intel Pentium M         | 22        | 0.28%   |
| Intel Core i9           | 19        | 0.24%   |
| Intel Celeron Dual-Core | 19        | 0.24%   |
| AMD Ryzen 9             | 16        | 0.2%    |
| AMD Athlon II Dual-Core | 15        | 0.19%   |
| AMD Athlon              | 15        | 0.19%   |
| Intel Core Duo          | 14        | 0.18%   |
| AMD A12                 | 14        | 0.18%   |
| AMD Athlon II           | 13        | 0.16%   |
| AMD C-60                | 12        | 0.15%   |
| AMD Turion 64 Mobile    | 11        | 0.14%   |
| AMD Ryzen 5 PRO         | 11        | 0.14%   |
| AMD Athlon 64 X2        | 11        | 0.14%   |
| AMD Athlon X2           | 10        | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 4898      | 62.05%  |
| 4      | 2102      | 26.63%  |
| 1      | 316       | 4%      |
| 6      | 313       | 3.97%   |
| 8      | 223       | 2.82%   |
| 14     | 18        | 0.23%   |
| 10     | 10        | 0.13%   |
| 12     | 8         | 0.1%    |
| 3      | 4         | 0.05%   |
| 5      | 2         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 7890      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 5144      | 65.16%  |
| 1      | 2748      | 34.81%  |
| 4      | 2         | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 7302      | 91.84%  |
| Unknown        | 502       | 6.31%   |
| 32-bit         | 147       | 1.85%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 723       | 9%      |
| 0x306a9    | 652       | 8.12%   |
| Unknown    | 636       | 7.92%   |
| 0x40651    | 377       | 4.69%   |
| 0x1067a    | 376       | 4.68%   |
| 0x20655    | 304       | 3.78%   |
| 0x406e3    | 269       | 3.35%   |
| 0x306d4    | 250       | 3.11%   |
| 0x306c3    | 235       | 2.93%   |
| 0x806ea    | 224       | 2.79%   |
| 0x806c1    | 220       | 2.74%   |
| 0x6fd      | 205       | 2.55%   |
| 0x806e9    | 201       | 2.5%    |
| 0x806ec    | 192       | 2.39%   |
| 0x906ea    | 166       | 2.07%   |
| 0x30678    | 166       | 2.07%   |
| 0x406c4    | 155       | 1.93%   |
| 0x10676    | 126       | 1.57%   |
| 0x20652    | 122       | 1.52%   |
| 0x06006705 | 99        | 1.23%   |
| 0x08108109 | 97        | 1.21%   |
| 0x706e5    | 86        | 1.07%   |
| 0x406c3    | 82        | 1.02%   |
| 0x506e3    | 81        | 1.01%   |
| 0x05000119 | 79        | 0.98%   |
| 0x08108102 | 78        | 0.97%   |
| 0x706a1    | 76        | 0.95%   |
| 0x706a8    | 75        | 0.93%   |
| 0x506c9    | 75        | 0.93%   |
| 0x906e9    | 73        | 0.91%   |
| 0x08600106 | 73        | 0.91%   |
| 0x106ca    | 72        | 0.9%    |
| 0x0a50000c | 72        | 0.9%    |
| 0xa0652    | 71        | 0.88%   |
| 0x806eb    | 71        | 0.88%   |
| 0x07030105 | 66        | 0.82%   |
| 0x6f6      | 56        | 0.7%    |
| 0x08608103 | 56        | 0.7%    |
| 0x06001119 | 56        | 0.7%    |
| 0x0700010f | 51        | 0.63%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 1033      | 13.09%  |
| SandyBridge      | 754       | 9.55%   |
| IvyBridge        | 699       | 8.85%   |
| Haswell          | 660       | 8.36%   |
| Penryn           | 520       | 6.59%   |
| Westmere         | 445       | 5.64%   |
| Silvermont       | 437       | 5.54%   |
| Skylake          | 389       | 4.93%   |
| Core             | 362       | 4.59%   |
| Broadwell        | 262       | 3.32%   |
| TigerLake        | 231       | 2.93%   |
| Excavator        | 194       | 2.46%   |
| Zen+             | 190       | 2.41%   |
| Goldmont plus    | 155       | 1.96%   |
| Bonnell          | 146       | 1.85%   |
| Zen 2            | 136       | 1.72%   |
| Icelake          | 127       | 1.61%   |
| Unknown          | 116       | 1.47%   |
| P6               | 107       | 1.36%   |
| Bobcat           | 103       | 1.3%    |
| Puma             | 96        | 1.22%   |
| CometLake        | 92        | 1.17%   |
| Zen 3            | 83        | 1.05%   |
| K8 Hammer        | 82        | 1.04%   |
| Goldmont         | 79        | 1%      |
| Piledriver       | 65        | 0.82%   |
| Jaguar           | 60        | 0.76%   |
| K10              | 59        | 0.75%   |
| K10 Llano        | 51        | 0.65%   |
| Zen              | 46        | 0.58%   |
| Nehalem          | 30        | 0.38%   |
| Alderlake Hybrid | 28        | 0.35%   |
| K8 & K10 hybrid  | 22        | 0.28%   |
| Tremont          | 14        | 0.18%   |
| Steamroller      | 13        | 0.16%   |
| NetBurst         | 7         | 0.09%   |
| K6               | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 5893      | 61.33%  |
| AMD                              | 1893      | 19.7%   |
| Nvidia                           | 1755      | 18.27%  |
| Silicon Integrated Systems [SiS] | 53        | 0.55%   |
| VIA Technologies                 | 13        | 0.14%   |
| S3 Graphics                      | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 694       | 6.89%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 664       | 6.59%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 391       | 3.88%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 341       | 3.39%   |
| Intel Core Processor Integrated Graphics Controller                                      | 321       | 3.19%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 256       | 2.54%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 246       | 2.44%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 237       | 2.35%   |
| Intel HD Graphics 5500                                                                   | 222       | 2.2%    |
| Intel UHD Graphics 620                                                                   | 221       | 2.19%   |
| Intel HD Graphics 620                                                                    | 217       | 2.15%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 193       | 1.92%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 191       | 1.9%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 184       | 1.83%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 174       | 1.73%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 168       | 1.67%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 152       | 1.51%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 152       | 1.51%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 142       | 1.41%   |
| AMD Renoir                                                                               | 133       | 1.32%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 132       | 1.31%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 124       | 1.23%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 98        | 0.97%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 94        | 0.93%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 94        | 0.93%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 91        | 0.9%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 90        | 0.89%   |
| AMD Lucienne                                                                             | 76        | 0.75%   |
| Intel HD Graphics 530                                                                    | 75        | 0.74%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 75        | 0.74%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 73        | 0.72%   |
| Intel HD Graphics 630                                                                    | 70        | 0.7%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 70        | 0.7%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 69        | 0.69%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 69        | 0.69%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 68        | 0.68%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 60        | 0.6%    |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 58        | 0.58%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 57        | 0.57%   |
| Intel HD Graphics 500                                                                    | 57        | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 4257      | 53.89%  |
| 1 x AMD         | 1280      | 16.2%   |
| Intel + Nvidia  | 1263      | 15.99%  |
| 1 x Nvidia      | 404       | 5.11%   |
| Intel + AMD     | 364       | 4.61%   |
| 2 x AMD         | 167       | 2.11%   |
| AMD + Nvidia    | 80        | 1.01%   |
| 1 x SiS         | 53        | 0.67%   |
| 1 x VIA         | 13        | 0.16%   |
| Other           | 9         | 0.11%   |
| 2 x Nvidia      | 8         | 0.1%    |
| 1 x S3 Graphics | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 6515      | 81.85%  |
| Proprietary | 1045      | 13.13%  |
| Unknown     | 400       | 5.03%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 4539      | 56.38%  |
| 0.01-0.5   | 1224      | 15.2%   |
| 1.01-2.0   | 1211      | 15.04%  |
| 0.51-1.0   | 494       | 6.14%   |
| 3.01-4.0   | 439       | 5.45%   |
| 5.01-6.0   | 78        | 0.97%   |
| 7.01-8.0   | 46        | 0.57%   |
| 2.01-3.0   | 19        | 0.24%   |
| 8.01-16.0  | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 1737      | 20.85%  |
| LG Display              | 1311      | 15.73%  |
| Chimei Innolux          | 1017      | 12.21%  |
| BOE                     | 973       | 11.68%  |
| Samsung Electronics     | 968       | 11.62%  |
| Chi Mei Optoelectronics | 259       | 3.11%   |
| Apple                   | 187       | 2.24%   |
| Lenovo                  | 164       | 1.97%   |
| Goldstar                | 162       | 1.94%   |
| Dell                    | 155       | 1.86%   |
| LG Philips              | 124       | 1.49%   |
| Sharp                   | 98        | 1.18%   |
| PANDA                   | 94        | 1.13%   |
| InfoVision              | 88        | 1.06%   |
| Hewlett-Packard         | 83        | 1%      |
| Philips                 | 78        | 0.94%   |
| Acer                    | 73        | 0.88%   |
| AOC                     | 62        | 0.74%   |
| CPT                     | 58        | 0.7%    |
| Sony                    | 56        | 0.67%   |
| BenQ                    | 46        | 0.55%   |
| Ancor Communications    | 35        | 0.42%   |
| Seiko/Epson             | 34        | 0.41%   |
| HannStar                | 31        | 0.37%   |
| Toshiba                 | 30        | 0.36%   |
| InnoLux Display         | 28        | 0.34%   |
| LGD                     | 27        | 0.32%   |
| Iiyama                  | 27        | 0.32%   |
| Quanta Display          | 23        | 0.28%   |
| Panasonic               | 15        | 0.18%   |
| ViewSonic               | 13        | 0.16%   |
| NEC Computers           | 11        | 0.13%   |
| Vestel Elektronik       | 10        | 0.12%   |
| Unknown                 | 10        | 0.12%   |
| JDI                     | 9         | 0.11%   |
| CSO                     | 9         | 0.11%   |
| LPL                     | 8         | 0.1%    |
| Fujitsu Siemens         | 8         | 0.1%    |
| Eizo                    | 8         | 0.1%    |
| ASUSTek Computer        | 8         | 0.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 89        | 1.06%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 79        | 0.94%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 69        | 0.82%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 61        | 0.73%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch             | 56        | 0.67%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch             | 53        | 0.63%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 51        | 0.61%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 49        | 0.58%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                      | 42        | 0.5%    |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch            | 42        | 0.5%    |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 41        | 0.49%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 38        | 0.45%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch             | 38        | 0.45%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 37        | 0.44%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 36        | 0.43%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 36        | 0.43%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch               | 34        | 0.4%    |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch             | 33        | 0.39%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch           | 32        | 0.38%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                      | 32        | 0.38%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch             | 32        | 0.38%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch           | 30        | 0.36%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                     | 27        | 0.32%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch             | 27        | 0.32%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch             | 25        | 0.3%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 24        | 0.29%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                     | 24        | 0.29%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                      | 24        | 0.29%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch             | 24        | 0.29%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch             | 24        | 0.29%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch               | 23        | 0.27%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x193mm 15.5-inch                   | 23        | 0.27%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch           | 23        | 0.27%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                      | 23        | 0.27%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch             | 23        | 0.27%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch             | 23        | 0.27%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch             | 23        | 0.27%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch              | 22        | 0.26%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch          | 22        | 0.26%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 22        | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 3278      | 40.89%  |
| 1920x1080 (FHD)    | 2519      | 31.42%  |
| 1600x900 (HD+)     | 580       | 7.24%   |
| 1280x800 (WXGA)    | 486       | 6.06%   |
| 1440x900 (WXGA+)   | 212       | 2.64%   |
| 3840x2160 (4K)     | 173       | 2.16%   |
| 1920x1200 (WUXGA)  | 107       | 1.33%   |
| 1024x600           | 83        | 1.04%   |
| 2560x1440 (QHD)    | 78        | 0.97%   |
| 1680x1050 (WSXGA+) | 72        | 0.9%    |
| 1280x1024 (SXGA)   | 63        | 0.79%   |
| 1360x768           | 41        | 0.51%   |
| 2560x1600          | 35        | 0.44%   |
| 2560x1080          | 30        | 0.37%   |
| 2880x1800          | 28        | 0.35%   |
| Unknown            | 26        | 0.32%   |
| 1024x768 (XGA)     | 23        | 0.29%   |
| 3200x1800 (QHD+)   | 17        | 0.21%   |
| 1680x945           | 17        | 0.21%   |
| 2160x1440          | 16        | 0.2%    |
| 3440x1440          | 14        | 0.17%   |
| 1920x540           | 13        | 0.16%   |
| 3000x2000          | 11        | 0.14%   |
| 3840x2400          | 8         | 0.1%    |
| 3072x1920          | 7         | 0.09%   |
| 1280x720 (HD)      | 7         | 0.09%   |
| 2256x1504          | 6         | 0.07%   |
| 3840x1080          | 5         | 0.06%   |
| 1920x1280          | 5         | 0.06%   |
| 1400x1050          | 5         | 0.06%   |
| 1600x1200          | 4         | 0.05%   |
| 1280x768           | 4         | 0.05%   |
| 3200x2000          | 3         | 0.04%   |
| 3840x1200          | 2         | 0.02%   |
| 3456x2160          | 2         | 0.02%   |
| 3286x1080          | 2         | 0.02%   |
| 3200x1200          | 2         | 0.02%   |
| 2304x1440          | 2         | 0.02%   |
| 2288x1287          | 2         | 0.02%   |
| 1280x960           | 2         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 3753      | 45.07%  |
| 13      | 983       | 11.8%   |
| 14      | 965       | 11.59%  |
| 17      | 731       | 8.78%   |
| 11      | 213       | 2.56%   |
| 12      | 200       | 2.4%    |
| 24      | 185       | 2.22%   |
| Unknown | 184       | 2.21%   |
| 23      | 167       | 2.01%   |
| 27      | 147       | 1.77%   |
| 21      | 138       | 1.66%   |
| 18      | 103       | 1.24%   |
| 10      | 86        | 1.03%   |
| 19      | 71        | 0.85%   |
| 31      | 58        | 0.7%    |
| 34      | 44        | 0.53%   |
| 22      | 43        | 0.52%   |
| 16      | 37        | 0.44%   |
| 72      | 36        | 0.43%   |
| 84      | 26        | 0.31%   |
| 20      | 26        | 0.31%   |
| 32      | 22        | 0.26%   |
| 40      | 17        | 0.2%    |
| 54      | 11        | 0.13%   |
| 25      | 10        | 0.12%   |
| 8       | 8         | 0.1%    |
| 28      | 7         | 0.08%   |
| 26      | 7         | 0.08%   |
| 65      | 6         | 0.07%   |
| 48      | 4         | 0.05%   |
| 47      | 4         | 0.05%   |
| 46      | 4         | 0.05%   |
| 74      | 3         | 0.04%   |
| 52      | 3         | 0.04%   |
| 33      | 3         | 0.04%   |
| 29      | 3         | 0.04%   |
| 42      | 2         | 0.02%   |
| 41      | 2         | 0.02%   |
| 39      | 2         | 0.02%   |
| 37      | 2         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 5189      | 62.65%  |
| 201-300     | 910       | 10.99%  |
| 351-400     | 882       | 10.65%  |
| 501-600     | 482       | 5.82%   |
| 401-500     | 342       | 4.13%   |
| Unknown     | 184       | 2.22%   |
| 601-700     | 86        | 1.04%   |
| 701-800     | 69        | 0.83%   |
| 1501-2000   | 65        | 0.78%   |
| 1001-1500   | 37        | 0.45%   |
| 801-900     | 23        | 0.28%   |
| 101-200     | 8         | 0.1%    |
| 901-1000    | 5         | 0.06%   |
| 1-100       | 1         | 0.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 6276      | 83.15%  |
| 16/10   | 908       | 12.03%  |
| Unknown | 152       | 2.01%   |
| 5/4     | 62        | 0.82%   |
| 3/2     | 56        | 0.74%   |
| 21/9    | 45        | 0.6%    |
| 4/3     | 40        | 0.53%   |
| 6/5     | 4         | 0.05%   |
| 32/9    | 3         | 0.04%   |
| 1.96    | 1         | 0.01%   |
| 0.62    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 3742      | 44.98%  |
| 81-90          | 1631      | 19.61%  |
| 121-130        | 591       | 7.1%    |
| 201-250        | 444       | 5.34%   |
| 71-80          | 310       | 3.73%   |
| 51-60          | 213       | 2.56%   |
| 61-70          | 193       | 2.32%   |
| Unknown        | 184       | 2.21%   |
| 301-350        | 151       | 1.82%   |
| 151-200        | 146       | 1.76%   |
| 351-500        | 133       | 1.6%    |
| 141-150        | 117       | 1.41%   |
| 131-140        | 114       | 1.37%   |
| More than 1000 | 91        | 1.09%   |
| 41-50          | 87        | 1.05%   |
| 251-300        | 62        | 0.75%   |
| 501-1000       | 40        | 0.48%   |
| 91-100         | 35        | 0.42%   |
| 111-120        | 26        | 0.31%   |
| 1-40           | 9         | 0.11%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 3465      | 42.4%   |
| 121-160       | 2567      | 31.41%  |
| 51-100        | 1445      | 17.68%  |
| 161-240       | 277       | 3.39%   |
| Unknown       | 184       | 2.25%   |
| More than 240 | 120       | 1.47%   |
| 1-50          | 115       | 1.41%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 6529      | 81.51%  |
| 2     | 1020      | 12.73%  |
| 0     | 379       | 4.73%   |
| 3     | 78        | 0.97%   |
| 4     | 4         | 0.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 4407      | 33.8%   |
| Intel                             | 3376      | 25.89%  |
| Qualcomm Atheros                  | 2369      | 18.17%  |
| Broadcom                          | 1030      | 7.9%    |
| Broadcom Limited                  | 240       | 1.84%   |
| Marvell Technology Group          | 233       | 1.79%   |
| Ralink                            | 189       | 1.45%   |
| Ralink Technology                 | 103       | 0.79%   |
| MediaTek                          | 94        | 0.72%   |
| TP-Link                           | 87        | 0.67%   |
| ASIX Electronics                  | 62        | 0.48%   |
| Samsung Electronics               | 59        | 0.45%   |
| Dell                              | 58        | 0.44%   |
| JMicron Technology                | 56        | 0.43%   |
| Silicon Integrated Systems [SiS]  | 53        | 0.41%   |
| Nvidia                            | 49        | 0.38%   |
| Ericsson Business Mobile Networks | 49        | 0.38%   |
| Xiaomi                            | 43        | 0.33%   |
| Huawei Technologies               | 41        | 0.31%   |
| Sierra Wireless                   | 40        | 0.31%   |
| Hewlett-Packard                   | 40        | 0.31%   |
| DisplayLink                       | 25        | 0.19%   |
| Edimax Technology                 | 20        | 0.15%   |
| Qualcomm                          | 19        | 0.15%   |
| NetGear                           | 19        | 0.15%   |
| Qualcomm Atheros Communications   | 18        | 0.14%   |
| Motorola PCS                      | 17        | 0.13%   |
| Attansic Technology               | 17        | 0.13%   |
| Lenovo                            | 15        | 0.12%   |
| ASUSTek Computer                  | 15        | 0.12%   |
| VIA Technologies                  | 14        | 0.11%   |
| D-Link                            | 14        | 0.11%   |
| ICS Advent                        | 13        | 0.1%    |
| Belkin Components                 | 11        | 0.08%   |
| D-Link System                     | 9         | 0.07%   |
| Linksys                           | 8         | 0.06%   |
| AMD                               | 8         | 0.06%   |
| Microsoft                         | 7         | 0.05%   |
| Google                            | 7         | 0.05%   |
| T & A Mobile Phones               | 6         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 2515      | 16.14%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 1123      | 7.21%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 408       | 2.62%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 381       | 2.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 379       | 2.43%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 342       | 2.19%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 334       | 2.14%   |
| Intel Wireless 7260                                                     | 271       | 1.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 260       | 1.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 231       | 1.48%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 218       | 1.4%    |
| Intel Wireless 8265 / 8275                                              | 198       | 1.27%   |
| Intel Wireless 7265                                                     | 198       | 1.27%   |
| Intel Wi-Fi 6 AX200                                                     | 181       | 1.16%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 154       | 0.99%   |
| Intel Wi-Fi 6 AX201                                                     | 154       | 0.99%   |
| Broadcom BCM43142 802.11b/g/n                                           | 154       | 0.99%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 152       | 0.98%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 143       | 0.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 139       | 0.89%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 139       | 0.89%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 137       | 0.88%   |
| Intel Wireless 8260                                                     | 137       | 0.88%   |
| Intel Wireless 3165                                                     | 130       | 0.83%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 127       | 0.82%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 116       | 0.74%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 116       | 0.74%   |
| Intel Wireless 3160                                                     | 113       | 0.73%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 112       | 0.72%   |
| Intel 82577LM Gigabit Network Connection                                | 108       | 0.69%   |
| Intel WiFi Link 5100                                                    | 95        | 0.61%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 90        | 0.58%   |
| Intel Ethernet Connection I218-LM                                       | 90        | 0.58%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 90        | 0.58%   |
| Intel Centrino Ultimate-N 6300                                          | 88        | 0.56%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 86        | 0.55%   |
| Intel Centrino Advanced-N 6200                                          | 85        | 0.55%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 84        | 0.54%   |
| Intel 82567LM Gigabit Network Connection                                | 80        | 0.51%   |
| Intel Ethernet Connection I217-LM                                       | 79        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 3185      | 38.63%  |
| Qualcomm Atheros                      | 2046      | 24.82%  |
| Realtek Semiconductor                 | 1391      | 16.87%  |
| Broadcom                              | 780       | 9.46%   |
| Ralink                                | 189       | 2.29%   |
| Broadcom Limited                      | 154       | 1.87%   |
| Ralink Technology                     | 103       | 1.25%   |
| MediaTek                              | 82        | 0.99%   |
| TP-Link                               | 81        | 0.98%   |
| Sierra Wireless                       | 40        | 0.49%   |
| Dell                                  | 29        | 0.35%   |
| Edimax Technology                     | 20        | 0.24%   |
| Qualcomm Atheros Communications       | 18        | 0.22%   |
| NetGear                               | 18        | 0.22%   |
| ASUSTek Computer                      | 15        | 0.18%   |
| D-Link                                | 11        | 0.13%   |
| Belkin Components                     | 11        | 0.13%   |
| D-Link System                         | 9         | 0.11%   |
| Hewlett-Packard                       | 8         | 0.1%    |
| Qualcomm                              | 7         | 0.08%   |
| Microsoft                             | 6         | 0.07%   |
| Linksys                               | 6         | 0.07%   |
| Micro Star International              | 4         | 0.05%   |
| Fibocom                               | 4         | 0.05%   |
| AVM                                   | 4         | 0.05%   |
| ZyDAS                                 | 2         | 0.02%   |
| TRENDnet                              | 2         | 0.02%   |
| Sitecom Europe                        | 2         | 0.02%   |
| Marvell Technology Group              | 2         | 0.02%   |
| Fujitsu Siemens Computers             | 2         | 0.02%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.02%   |
| Xiaomi                                | 1         | 0.01%   |
| Winbond Electronics                   | 1         | 0.01%   |
| Texas Instruments                     | 1         | 0.01%   |
| Silicon Integrated Systems [SiS]      | 1         | 0.01%   |
| Senao                                 | 1         | 0.01%   |
| Philips (or NXP)                      | 1         | 0.01%   |
| Pegatron                              | 1         | 0.01%   |
| Mercucys                              | 1         | 0.01%   |
| Encore Electronics                    | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 408       | 4.9%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 381       | 4.58%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 379       | 4.56%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 342       | 4.11%   |
| Intel Wireless 7260                                                     | 271       | 3.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 260       | 3.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 231       | 2.78%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 218       | 2.62%   |
| Intel Wireless 8265 / 8275                                              | 198       | 2.38%   |
| Intel Wireless 7265                                                     | 198       | 2.38%   |
| Intel Wi-Fi 6 AX200                                                     | 181       | 2.18%   |
| Intel Wi-Fi 6 AX201                                                     | 154       | 1.85%   |
| Broadcom BCM43142 802.11b/g/n                                           | 154       | 1.85%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 152       | 1.83%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 143       | 1.72%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 139       | 1.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 139       | 1.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 137       | 1.65%   |
| Intel Wireless 8260                                                     | 137       | 1.65%   |
| Intel Wireless 3165                                                     | 130       | 1.56%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 116       | 1.39%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 116       | 1.39%   |
| Intel Wireless 3160                                                     | 113       | 1.36%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 112       | 1.35%   |
| Intel WiFi Link 5100                                                    | 95        | 1.14%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 90        | 1.08%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 90        | 1.08%   |
| Intel Centrino Ultimate-N 6300                                          | 88        | 1.06%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 86        | 1.03%   |
| Intel Centrino Advanced-N 6200                                          | 85        | 1.02%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 84        | 1.01%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 76        | 0.91%   |
| Intel Centrino Wireless-N 2230                                          | 75        | 0.9%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 73        | 0.88%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 72        | 0.87%   |
| Intel Centrino Advanced-N 6235                                          | 71        | 0.85%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 70        | 0.84%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 65        | 0.78%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 63        | 0.76%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 61        | 0.73%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 3891      | 55.4%   |
| Intel                                  | 1267      | 18.04%  |
| Qualcomm Atheros                       | 608       | 8.66%   |
| Broadcom                               | 396       | 5.64%   |
| Marvell Technology Group               | 231       | 3.29%   |
| Broadcom Limited                       | 93        | 1.32%   |
| ASIX Electronics                       | 62        | 0.88%   |
| Samsung Electronics                    | 57        | 0.81%   |
| JMicron Technology                     | 56        | 0.8%    |
| Silicon Integrated Systems [SiS]       | 51        | 0.73%   |
| Nvidia                                 | 48        | 0.68%   |
| Xiaomi                                 | 42        | 0.6%    |
| Huawei Technologies                    | 27        | 0.38%   |
| DisplayLink                            | 25        | 0.36%   |
| Attansic Technology                    | 17        | 0.24%   |
| Lenovo                                 | 15        | 0.21%   |
| VIA Technologies                       | 14        | 0.2%    |
| ICS Advent                             | 13        | 0.19%   |
| Motorola PCS                           | 12        | 0.17%   |
| Qualcomm                               | 11        | 0.16%   |
| MediaTek                               | 11        | 0.16%   |
| Hewlett-Packard                        | 11        | 0.16%   |
| Google                                 | 7         | 0.1%    |
| TP-Link                                | 6         | 0.09%   |
| HMD Global                             | 5         | 0.07%   |
| Apple                                  | 5         | 0.07%   |
| T & A Mobile Phones                    | 4         | 0.06%   |
| OPPO Electronics                       | 4         | 0.06%   |
| MosChip Semiconductor                  | 3         | 0.04%   |
| D-Link                                 | 3         | 0.04%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.03%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.03%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.03%   |
| Microchip Technology                   | 2         | 0.03%   |
| Linksys                                | 2         | 0.03%   |
| HTC (High Tech Computer)               | 2         | 0.03%   |
| Vimtron Electronics                    | 1         | 0.01%   |
| ULi Electronics                        | 1         | 0.01%   |
| Spreadtrum Communications              | 1         | 0.01%   |
| Promise Technology                     | 1         | 0.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 2515      | 35.61%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 1123      | 15.9%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 334       | 4.73%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 154       | 2.18%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 127       | 1.8%    |
| Intel 82577LM Gigabit Network Connection                                       | 108       | 1.53%   |
| Intel Ethernet Connection I218-LM                                              | 90        | 1.27%   |
| Intel 82567LM Gigabit Network Connection                                       | 80        | 1.13%   |
| Intel Ethernet Connection I217-LM                                              | 79        | 1.12%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 74        | 1.05%   |
| Intel Ethernet Connection I219-LM                                              | 73        | 1.03%   |
| Intel Ethernet Connection (3) I218-LM                                          | 66        | 0.93%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 62        | 0.88%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 62        | 0.88%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 60        | 0.85%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 57        | 0.81%   |
| Intel Ethernet Connection (4) I219-LM                                          | 57        | 0.81%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 55        | 0.78%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 49        | 0.69%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 49        | 0.69%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 48        | 0.68%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 48        | 0.68%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 47        | 0.67%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 43        | 0.61%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 40        | 0.57%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 38        | 0.54%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 38        | 0.54%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 37        | 0.52%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 37        | 0.52%   |
| Intel 82579V Gigabit Network Connection                                        | 34        | 0.48%   |
| Intel Ethernet Connection I219-V                                               | 31        | 0.44%   |
| Intel Ethernet Connection (4) I219-V                                           | 31        | 0.44%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 30        | 0.42%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 29        | 0.41%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 29        | 0.41%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 29        | 0.41%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 29        | 0.41%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 29        | 0.41%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 29        | 0.41%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 28        | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 7736      | 52.62%  |
| Ethernet | 6769      | 46.04%  |
| Modem    | 184       | 1.25%   |
| Unknown  | 14        | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 6407      | 77.22%  |
| Ethernet | 1887      | 22.74%  |
| Unknown  | 2         | 0.02%   |
| Modem    | 1         | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 6283      | 79.52%  |
| 1     | 1408      | 17.82%  |
| 0     | 168       | 2.13%   |
| 3     | 42        | 0.53%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 6528      | 81.09%  |
| Yes  | 1522      | 18.91%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2110      | 37.72%  |
| Realtek Semiconductor           | 703       | 12.57%  |
| Qualcomm Atheros Communications | 689       | 12.32%  |
| Broadcom                        | 414       | 7.4%    |
| Lite-On Technology              | 297       | 5.31%   |
| IMC Networks                    | 256       | 4.58%   |
| Foxconn / Hon Hai               | 202       | 3.61%   |
| Apple                           | 161       | 2.88%   |
| Dell                            | 137       | 2.45%   |
| Hewlett-Packard                 | 119       | 2.13%   |
| Cambridge Silicon Radio         | 115       | 2.06%   |
| Ralink                          | 90        | 1.61%   |
| Toshiba                         | 71        | 1.27%   |
| ASUSTek Computer                | 39        | 0.7%    |
| Foxconn International           | 32        | 0.57%   |
| Alps Electric                   | 31        | 0.55%   |
| Ralink Technology               | 29        | 0.52%   |
| Realtek                         | 28        | 0.5%    |
| Chicony Electronics             | 11        | 0.2%    |
| Qcom                            | 10        | 0.18%   |
| Unknown                         | 8         | 0.14%   |
| Taiyo Yuden                     | 8         | 0.14%   |
| MediaTek                        | 8         | 0.14%   |
| Askey Computer                  | 7         | 0.13%   |
| Edimax Technology               | 4         | 0.07%   |
| Micro Star International        | 3         | 0.05%   |
| Fujitsu                         | 3         | 0.05%   |
| Dynex                           | 3         | 0.05%   |
| Opticis                         | 2         | 0.04%   |
| TP-Link                         | 1         | 0.02%   |
| Primax Electronics              | 1         | 0.02%   |
| Belkin Components               | 1         | 0.02%   |
| Unknown                         | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 1011      | 18.06%  |
| Realtek Bluetooth Radio                             | 401       | 7.16%   |
| Qualcomm Atheros  Bluetooth Device                  | 320       | 5.72%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 311       | 5.56%   |
| Intel AX201 Bluetooth                               | 286       | 5.11%   |
| Realtek  Bluetooth 4.2 Adapter                      | 236       | 4.22%   |
| Intel AX200 Bluetooth                               | 176       | 3.14%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 126       | 2.25%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 118       | 2.11%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 115       | 2.05%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 115       | 2.05%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 114       | 2.04%   |
| Ralink RT3290 Bluetooth                             | 90        | 1.61%   |
| IMC Networks Bluetooth Device                       | 82        | 1.47%   |
| Apple Bluetooth Host Controller                     | 80        | 1.43%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 71        | 1.27%   |
| IMC Networks Bluetooth Radio                        | 71        | 1.27%   |
| Foxconn / Hon Hai Bluetooth Device                  | 65        | 1.16%   |
| HP Broadcom 2070 Bluetooth Combo                    | 63        | 1.13%   |
| Lite-On Atheros AR3012 Bluetooth                    | 59        | 1.05%   |
| Intel Wireless-AC 3168 Bluetooth                    | 55        | 0.98%   |
| Lite-On Bluetooth Device                            | 54        | 0.96%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 53        | 0.95%   |
| Broadcom BCM2045B (BDC-2.1)                         | 52        | 0.93%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 51        | 0.91%   |
| Apple Bluetooth USB Host Controller                 | 49        | 0.88%   |
| Dell DW375 Bluetooth Module                         | 46        | 0.82%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 45        | 0.8%    |
| Qualcomm Atheros AR9462 Bluetooth                   | 40        | 0.71%   |
| Broadcom BCM2045 Bluetooth                          | 37        | 0.66%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 36        | 0.64%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 36        | 0.64%   |
| Foxconn International BCM43142A0 Bluetooth module   | 32        | 0.57%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 31        | 0.55%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 30        | 0.54%   |
| IMC Networks Wireless_Device                        | 30        | 0.54%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 30        | 0.54%   |
| Realtek RTL8723B Bluetooth                          | 29        | 0.52%   |
| Realtek Bluetooth Radio                             | 28        | 0.5%    |
| Broadcom HP Portable SoftSailing                    | 27        | 0.48%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 6344      | 69.45%  |
| AMD                                          | 1506      | 16.49%  |
| Nvidia                                       | 803       | 8.79%   |
| C-Media Electronics                          | 71        | 0.78%   |
| Silicon Integrated Systems [SiS]             | 63        | 0.69%   |
| Logitech                                     | 39        | 0.43%   |
| GN Netcom                                    | 20        | 0.22%   |
| Texas Instruments                            | 19        | 0.21%   |
| Plantronics                                  | 19        | 0.21%   |
| JMTek                                        | 19        | 0.21%   |
| Realtek Semiconductor                        | 17        | 0.19%   |
| Lenovo                                       | 17        | 0.19%   |
| VIA Technologies                             | 16        | 0.18%   |
| Generalplus Technology                       | 14        | 0.15%   |
| Apple                                        | 13        | 0.14%   |
| Kingston Technology                          | 12        | 0.13%   |
| Creative Technology                          | 11        | 0.12%   |
| SteelSeries ApS                              | 9         | 0.1%    |
| Hewlett-Packard                              | 9         | 0.1%    |
| Microsoft                                    | 6         | 0.07%   |
| Sony                                         | 5         | 0.05%   |
| Razer USA                                    | 5         | 0.05%   |
| Corsair                                      | 5         | 0.05%   |
| Tenx Technology                              | 4         | 0.04%   |
| Samson Technologies                          | 4         | 0.04%   |
| PreSonus Audio Electronics                   | 4         | 0.04%   |
| BR25                                         | 4         | 0.04%   |
| OPPO Electronics                             | 3         | 0.03%   |
| Focusrite-Novation                           | 3         | 0.03%   |
| Dell                                         | 3         | 0.03%   |
| BEHRINGER International                      | 3         | 0.03%   |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 0.02%   |
| XMOS                                         | 2         | 0.02%   |
| Trust                                        | 2         | 0.02%   |
| Silicon Motion                               | 2         | 0.02%   |
| RODE Microphones                             | 2         | 0.02%   |
| QinHeng Electronics                          | 2         | 0.02%   |
| Micro Star International                     | 2         | 0.02%   |
| KORG                                         | 2         | 0.02%   |
| GYROCOM C&C                                  | 2         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 854       | 7.66%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 759       | 6.81%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 595       | 5.34%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 522       | 4.68%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 475       | 4.26%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 465       | 4.17%   |
| Intel 8 Series HD Audio Controller                                                                | 394       | 3.54%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 391       | 3.51%   |
| AMD FCH Azalia Controller                                                                         | 324       | 2.91%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 274       | 2.46%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 271       | 2.43%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 266       | 2.39%   |
| Intel Broadwell-U Audio Controller                                                                | 262       | 2.35%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 258       | 2.32%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 230       | 2.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 228       | 2.05%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 228       | 2.05%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 219       | 1.97%   |
| AMD Kabini HDMI/DP Audio                                                                          | 206       | 1.85%   |
| Intel Cannon Lake PCH cAVS                                                                        | 192       | 1.72%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 186       | 1.67%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 186       | 1.67%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 182       | 1.63%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 159       | 1.43%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 157       | 1.41%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 154       | 1.38%   |
| AMD High Definition Audio Controller                                                              | 142       | 1.27%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 114       | 1.02%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 99        | 0.89%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 92        | 0.83%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 91        | 0.82%   |
| Intel CM238 HD Audio Controller                                                                   | 82        | 0.74%   |
| Intel Comet Lake PCH cAVS                                                                         | 79        | 0.71%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 79        | 0.71%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 76        | 0.68%   |
| AMD Wrestler HDMI Audio                                                                           | 75        | 0.67%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 66        | 0.59%   |
| AMD Trinity HDMI Audio Controller                                                                 | 65        | 0.58%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 61        | 0.55%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 59        | 0.53%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1146      | 27.33%  |
| SK hynix            | 935       | 22.3%   |
| Micron Technology   | 480       | 11.45%  |
| Kingston            | 361       | 8.61%   |
| Unknown             | 294       | 7.01%   |
| Crucial             | 170       | 4.05%   |
| Elpida              | 112       | 2.67%   |
| Ramaxel Technology  | 111       | 2.65%   |
| A-DATA Technology   | 87        | 2.07%   |
| Smart               | 66        | 1.57%   |
| Nanya Technology    | 62        | 1.48%   |
| Unknown (ABCD)      | 61        | 1.45%   |
| Corsair             | 59        | 1.41%   |
| Teikon              | 18        | 0.43%   |
| G.Skill             | 18        | 0.43%   |
| Transcend           | 16        | 0.38%   |
| ASint Technology    | 13        | 0.31%   |
| Apacer              | 13        | 0.31%   |
| Unknown             | 11        | 0.26%   |
| Team                | 10        | 0.24%   |
| GOODRAM             | 10        | 0.24%   |
| Smart Brazil        | 9         | 0.21%   |
| Patriot             | 8         | 0.19%   |
| Avant               | 8         | 0.19%   |
| PNY                 | 6         | 0.14%   |
| Goldkey             | 6         | 0.14%   |
| SHARETRONIC         | 5         | 0.12%   |
| Sesame              | 5         | 0.12%   |
| Qimonda             | 5         | 0.12%   |
| Kllisre             | 5         | 0.12%   |
| AMD                 | 5         | 0.12%   |
| Toshiba             | 4         | 0.1%    |
| Multilaser          | 4         | 0.1%    |
| High Bridge         | 4         | 0.1%    |
| Timetec             | 3         | 0.07%   |
| PUSKILL             | 3         | 0.07%   |
| fef5                | 3         | 0.07%   |
| CSX                 | 3         | 0.07%   |
| 48spaces            | 3         | 0.07%   |
| ZIFEI               | 2         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 64        | 1.43%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 63        | 1.41%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 58        | 1.3%    |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 56        | 1.25%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 51        | 1.14%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 51        | 1.14%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 46        | 1.03%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 45        | 1.01%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 43        | 0.96%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 42        | 0.94%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 42        | 0.94%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 38        | 0.85%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 38        | 0.85%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 35        | 0.78%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 33        | 0.74%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 33        | 0.74%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 33        | 0.74%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 33        | 0.74%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 31        | 0.69%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 31        | 0.69%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 31        | 0.69%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 26        | 0.58%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 25        | 0.56%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 25        | 0.56%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 25        | 0.56%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 24        | 0.54%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 23        | 0.51%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 23        | 0.51%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 23        | 0.51%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 22        | 0.49%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 22        | 0.49%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 21        | 0.47%   |
| SK hynix RAM HMA851S6AFR6N-UH 2GB SODIMM LPDDR4 2667MT/s         | 21        | 0.47%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 21        | 0.47%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 21        | 0.47%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 21        | 0.47%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 21        | 0.47%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 19        | 0.42%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 19        | 0.42%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 18        | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 1546      | 43.91%  |
| DDR4    | 1393      | 39.56%  |
| LPDDR4  | 169       | 4.8%    |
| DDR2    | 161       | 4.57%   |
| SDRAM   | 90        | 2.56%   |
| LPDDR3  | 83        | 2.36%   |
| DDR     | 22        | 0.62%   |
| Unknown | 21        | 0.6%    |
| DRAM    | 17        | 0.48%   |
| DDR5    | 10        | 0.28%   |
| LPDDR5  | 7         | 0.2%    |
| RAM     | 2         | 0.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 3211      | 91.66%  |
| Row Of Chips | 227       | 6.48%   |
| DIMM         | 27        | 0.77%   |
| Chip         | 19        | 0.54%   |
| Unknown      | 19        | 0.54%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 1413      | 36.62%  |
| 8192  | 1345      | 34.85%  |
| 2048  | 578       | 14.98%  |
| 16384 | 346       | 8.97%   |
| 1024  | 130       | 3.37%   |
| 32768 | 32        | 0.83%   |
| 512   | 11        | 0.29%   |
| 256   | 2         | 0.05%   |
| 3072  | 1         | 0.03%   |
| 1536  | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 1071      | 27.92%  |
| 2667    | 671       | 17.49%  |
| 3200    | 497       | 12.96%  |
| 2400    | 313       | 8.16%   |
| 1334    | 255       | 6.65%   |
| 1333    | 198       | 5.16%   |
| 2133    | 152       | 3.96%   |
| Unknown | 91        | 2.37%   |
| 667     | 87        | 2.27%   |
| 1067    | 71        | 1.85%   |
| 3266    | 63        | 1.64%   |
| 4267    | 52        | 1.36%   |
| 4199    | 49        | 1.28%   |
| 800     | 41        | 1.07%   |
| 1867    | 40        | 1.04%   |
| 1066    | 39        | 1.02%   |
| 2048    | 27        | 0.7%    |
| 8400    | 18        | 0.47%   |
| 975     | 18        | 0.47%   |
| 4800    | 14        | 0.36%   |
| 533     | 14        | 0.36%   |
| 4266    | 9         | 0.23%   |
| 6400    | 7         | 0.18%   |
| 1639    | 5         | 0.13%   |
| 333     | 5         | 0.13%   |
| 3000    | 4         | 0.1%    |
| 1866    | 4         | 0.1%    |
| 1200    | 4         | 0.1%    |
| 933     | 4         | 0.1%    |
| 400     | 4         | 0.1%    |
| 2933    | 2         | 0.05%   |
| 1776    | 2         | 0.05%   |
| 3733    | 1         | 0.03%   |
| 2800    | 1         | 0.03%   |
| 2267    | 1         | 0.03%   |
| 1400    | 1         | 0.03%   |
| 266     | 1         | 0.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 34        | 32.69%  |
| Canon                 | 23        | 22.12%  |
| Brother Industries    | 18        | 17.31%  |
| Samsung Electronics   | 12        | 11.54%  |
| Seiko Epson           | 7         | 6.73%   |
| Kyocera               | 4         | 3.85%   |
| Prolific Technology   | 2         | 1.92%   |
| STMicroelectronics    | 1         | 0.96%   |
| QinHeng Electronics   | 1         | 0.96%   |
| Lexmark International | 1         | 0.96%   |
| Dell                  | 1         | 0.96%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP DeskJet 2700 series                                    | 4         | 3.77%   |
| Canon PIXMA MG2500 Series                                 | 4         | 3.77%   |
| Samsung M267x 287x Series                                 | 3         | 2.83%   |
| Seiko Epson L805 Series                                   | 2         | 1.89%   |
| Seiko Epson L3150 Series                                  | 2         | 1.89%   |
| Samsung M2020 Series                                      | 2         | 1.89%   |
| Prolific PL2305 Parallel Port                             | 2         | 1.89%   |
| Kyocera Mita FS-820                                       | 2         | 1.89%   |
| HP OfficeJet 3830 series                                  | 2         | 1.89%   |
| HP LaserJet P2035                                         | 2         | 1.89%   |
| HP Ink Tank Wireless 410 series                           | 2         | 1.89%   |
| HP ENVY 4520 series                                       | 2         | 1.89%   |
| HP Deskjet 2540 series                                    | 2         | 1.89%   |
| HP Deskjet 1000 J110 series                               | 2         | 1.89%   |
| Canon PIXMA MX920 Series                                  | 2         | 1.89%   |
| Canon LBP6030w/6018w                                      | 2         | 1.89%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 0.94%   |
| Seiko Epson WF-3520 Series                                | 1         | 0.94%   |
| Seiko Epson WF-2830 Series                                | 1         | 0.94%   |
| Seiko Epson ET-2600 Series                                | 1         | 0.94%   |
| Samsung SCX-6545 Series                                   | 1         | 0.94%   |
| Samsung ML-2510 Series                                    | 1         | 0.94%   |
| Samsung ML-216x Series Laser Printer                      | 1         | 0.94%   |
| Samsung ML-1660 Series                                    | 1         | 0.94%   |
| Samsung M2070 Series                                      | 1         | 0.94%   |
| Samsung CLP-300 Series                                    | 1         | 0.94%   |
| Samsung C3060 Series                                      | 1         | 0.94%   |
| QinHeng CH340S                                            | 1         | 0.94%   |
| Lexmark International InkJet Color Printer                | 1         | 0.94%   |
| Kyocera FS-1030D printer                                  | 1         | 0.94%   |
| Kyocera ECOSYS M5526cdw                                   | 1         | 0.94%   |
| HP OfficeJet Pro 8030 series                              | 1         | 0.94%   |
| HP LaserJet Professional P 1102w                          | 1         | 0.94%   |
| HP LaserJet Pro M404-M405                                 | 1         | 0.94%   |
| HP LaserJet P1505n                                        | 1         | 0.94%   |
| HP LaserJet CP 1025                                       | 1         | 0.94%   |
| HP LaserJet 1020                                          | 1         | 0.94%   |
| HP LaserJet 1018                                          | 1         | 0.94%   |
| HP ENVY 5000 series                                       | 1         | 0.94%   |
| HP DeskJet F4100 Printer series                           | 1         | 0.94%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor            | Notebooks | Percent |
|-------------------|-----------|---------|
| Canon             | 13        | 68.42%  |
| Hewlett-Packard   | 3         | 15.79%  |
| Seiko Epson       | 1         | 5.26%   |
| Canon Electronics | 1         | 5.26%   |
| AGFA-Gevaert NV   | 1         | 5.26%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 120                     | 2         | 10%     |
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1         | 5%      |
| HP ScanJet 5300c/5370c                      | 1         | 5%      |
| HP ScanJet 2400c                            | 1         | 5%      |
| HP ScanJet 2200c                            | 1         | 5%      |
| Canon P-150 Scanner                         | 1         | 5%      |
| Canon CanoScan N670U/N676U/LiDE 20          | 1         | 5%      |
| Canon CanoScan N650U/N656U                  | 1         | 5%      |
| Canon CanoScan LiDE 700F                    | 1         | 5%      |
| Canon CanoScan LiDE 600F                    | 1         | 5%      |
| Canon CanoScan LiDE 500F                    | 1         | 5%      |
| Canon CanoScan LiDE 220                     | 1         | 5%      |
| Canon CanoScan LiDE 110                     | 1         | 5%      |
| Canon CanoScan LiDE 100                     | 1         | 5%      |
| Canon CanoScan 4400F                        | 1         | 5%      |
| Canon CanoScan 4200F                        | 1         | 5%      |
| Canon CanoScan 3200F                        | 1         | 5%      |
| Canon CanoScan 1220U                        | 1         | 5%      |
| AGFA-Gevaert NV SnapScan 1212U (?)          | 1         | 5%      |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1716      | 25.32%  |
| IMC Networks                           | 586       | 8.65%   |
| Realtek Semiconductor                  | 533       | 7.86%   |
| Acer                                   | 525       | 7.75%   |
| Microdia                               | 523       | 7.72%   |
| Sunplus Innovation Technology          | 416       | 6.14%   |
| Suyin                                  | 346       | 5.1%    |
| Cheng Uei Precision Industry (Foxlink) | 342       | 5.05%   |
| Quanta                                 | 341       | 5.03%   |
| Syntek                                 | 182       | 2.69%   |
| Silicon Motion                         | 178       | 2.63%   |
| Lite-On Technology                     | 140       | 2.07%   |
| Alcor Micro                            | 119       | 1.76%   |
| Apple                                  | 117       | 1.73%   |
| Ricoh                                  | 88        | 1.3%    |
| Luxvisions Innotech Limited            | 69        | 1.02%   |
| Logitech                               | 66        | 0.97%   |
| Samsung Electronics                    | 48        | 0.71%   |
| Z-Star Microelectronics                | 47        | 0.69%   |
| Importek                               | 44        | 0.65%   |
| Lenovo                                 | 40        | 0.59%   |
| ALi                                    | 33        | 0.49%   |
| Primax Electronics                     | 32        | 0.47%   |
| OmniVision Technologies                | 19        | 0.28%   |
| USB Camera                             | 18        | 0.27%   |
| DigiTech                               | 18        | 0.27%   |
| Sonix Technology                       | 16        | 0.24%   |
| SunplusIT                              | 13        | 0.19%   |
| Y Media                                | 11        | 0.16%   |
| Microsoft                              | 9         | 0.13%   |
| GEMBIRD                                | 9         | 0.13%   |
| Generalplus Technology                 | 8         | 0.12%   |
| Sunplus Technology                     | 7         | 0.1%    |
| Jieli Technology                       | 6         | 0.09%   |
| Intel                                  | 6         | 0.09%   |
| Unknown                                | 5         | 0.07%   |
| LG Electronics                         | 5         | 0.07%   |
| Image Processor                        | 5         | 0.07%   |
| Trust                                  | 4         | 0.06%   |
| DJJHFA1BIF5595                         | 4         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 240       | 3.53%   |
| Chicony HD WebCam                                | 174       | 2.56%   |
| Microdia Integrated_Webcam_HD                    | 163       | 2.4%    |
| Realtek Integrated_Webcam_HD                     | 128       | 1.88%   |
| Acer Integrated Camera                           | 122       | 1.79%   |
| Sunplus Integrated_Webcam_HD                     | 121       | 1.78%   |
| IMC Networks USB2.0 HD UVC WebCam                | 121       | 1.78%   |
| IMC Networks Integrated Camera                   | 110       | 1.62%   |
| Chicony USB 2.0 Camera                           | 75        | 1.1%    |
| Acer Lenovo EasyCamera                           | 73        | 1.07%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 71        | 1.04%   |
| Realtek USB Camera                               | 66        | 0.97%   |
| Microdia Integrated Webcam                       | 66        | 0.97%   |
| Chicony USB2.0 HD UVC WebCam                     | 66        | 0.97%   |
| Chicony HP Truevision HD                         | 63        | 0.93%   |
| Chicony HP HD Camera                             | 62        | 0.91%   |
| Syntek Integrated Camera                         | 61        | 0.9%    |
| Sunplus HD WebCam                                | 59        | 0.87%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 58        | 0.85%   |
| Chicony HP Webcam                                | 56        | 0.82%   |
| Chicony Lenovo EasyCamera                        | 55        | 0.81%   |
| Chicony HP TrueVision HD Camera                  | 55        | 0.81%   |
| Chicony EasyCamera                               | 55        | 0.81%   |
| Lite-On Integrated Camera                        | 51        | 0.75%   |
| Quanta VGA WebCam                                | 50        | 0.74%   |
| Quanta HP TrueVision HD Camera                   | 49        | 0.72%   |
| Quanta HD User Facing                            | 49        | 0.72%   |
| Acer BisonCam, NB Pro                            | 49        | 0.72%   |
| Syntek Lenovo EasyCamera                         | 48        | 0.71%   |
| Chicony VGA Webcam                               | 48        | 0.71%   |
| Chicony HD User Facing                           | 47        | 0.69%   |
| Apple FaceTime HD Camera                         | 47        | 0.69%   |
| Acer EasyCamera                                  | 47        | 0.69%   |
| Samsung Galaxy A5 (MTP)                          | 46        | 0.68%   |
| Chicony USB2.0 VGA UVC WebCam                    | 46        | 0.68%   |
| Quanta HP Webcam                                 | 45        | 0.66%   |
| Chicony TOSHIBA Web Camera - HD                  | 44        | 0.65%   |
| Cheng Uei Precision Industry (Foxlink) Webcam    | 44        | 0.65%   |
| Acer Lenovo Integrated Webcam                    | 44        | 0.65%   |
| Suyin Acer/HP Integrated Webcam [CN0314]         | 43        | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 467       | 43.08%  |
| Synaptics                  | 166       | 15.31%  |
| AuthenTec                  | 114       | 10.52%  |
| Upek                       | 97        | 8.95%   |
| Shenzhen Goodix Technology | 89        | 8.21%   |
| Elan Microelectronics      | 63        | 5.81%   |
| LighTuning Technology      | 55        | 5.07%   |
| STMicroelectronics         | 22        | 2.03%   |
| Focal-systems.Corp         | 4         | 0.37%   |
| HOLTEK                     | 3         | 0.28%   |
| Next Biometrics            | 2         | 0.18%   |
| Suprema                    | 1         | 0.09%   |
| GDMicroelectronics         | 1         | 0.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 102       | 9.41%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 93        | 8.58%   |
| Shenzhen Goodix  Fingerprint Device                                        | 53        | 4.89%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 52        | 4.8%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 49        | 4.52%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 49        | 4.52%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 46        | 4.24%   |
| Validity Sensors Fingerprint scanner                                       | 36        | 3.32%   |
| AuthenTec AES2810                                                          | 36        | 3.32%   |
| Validity Sensors VFS491                                                    | 35        | 3.23%   |
| Unknown                                                                    | 35        | 3.23%   |
| Elan ELAN:Fingerprint                                                      | 32        | 2.95%   |
| Elan ELAN:ARM-M4                                                           | 28        | 2.58%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 26        | 2.4%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 25        | 2.31%   |
| Shenzhen Goodix Fingerprint Reader                                         | 24        | 2.21%   |
| AuthenTec AES1600                                                          | 24        | 2.21%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 22        | 2.03%   |
| STMicroelectronics Fingerprint Reader                                      | 22        | 2.03%   |
| Validity Sensors Synaptics WBDI                                            | 21        | 1.94%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 21        | 1.94%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 19        | 1.75%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 19        | 1.75%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 17        | 1.57%   |
| AuthenTec Fingerprint Sensor                                               | 17        | 1.57%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 16        | 1.48%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 16        | 1.48%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 15        | 1.38%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 14        | 1.29%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 13        | 1.2%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 13        | 1.2%    |
| LighTuning Fingerprint Reader                                              | 13        | 1.2%    |
| Synaptics  WBDI                                                            | 12        | 1.11%   |
| Shenzhen Goodix FingerPrint                                                | 12        | 1.11%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 9         | 0.83%   |
| Validity Sensors VFS Fingerprint sensor                                    | 8         | 0.74%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 8         | 0.74%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 6         | 0.55%   |
| Upek TCS5B Fingerprint sensor                                              | 4         | 0.37%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 4         | 0.37%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 262       | 48.16%  |
| Alcor Micro               | 125       | 22.98%  |
| O2 Micro                  | 58        | 10.66%  |
| Upek                      | 38        | 6.99%   |
| Lenovo                    | 36        | 6.62%   |
| Gemalto (was Gemplus)     | 7         | 1.29%   |
| SCM Microsystems          | 6         | 1.1%    |
| Realtek Semiconductor     | 3         | 0.55%   |
| OmniKey                   | 2         | 0.37%   |
| NXP Semiconductors        | 1         | 0.18%   |
| In Focus Systems          | 1         | 0.18%   |
| Giesecke & Devrient       | 1         | 0.18%   |
| Clay Logic                | 1         | 0.18%   |
| Cherry                    | 1         | 0.18%   |
| C3PO                      | 1         | 0.18%   |
| Aladdin Knowledge Systems | 1         | 0.18%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 124       | 22.79%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 123       | 22.61%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 60        | 11.03%  |
| Broadcom 5880                                                                | 48        | 8.82%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 46        | 8.46%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 38        | 6.99%   |
| Lenovo Integrated Smart Card Reader                                          | 36        | 6.62%   |
| Broadcom 58200                                                               | 26        | 4.78%   |
| O2 Micro Oz776 SmartCard Reader                                              | 12        | 2.21%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 5         | 0.92%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 4         | 0.74%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 3         | 0.55%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 2         | 0.37%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 0.37%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 2         | 0.37%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 0.37%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 0.37%   |
| OmniKey CardMan 4321                                                         | 1         | 0.18%   |
| OmniKey CardMan 1021                                                         | 1         | 0.18%   |
| NXP Semiconductors PR533                                                     | 1         | 0.18%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.18%   |
| Giesecke & Devrient StarSign CUT                                             | 1         | 0.18%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.18%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.18%   |
| C3PO USB SMART CARD READER                                                   | 1         | 0.18%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.18%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 5082      | 63.06%  |
| 1     | 2303      | 28.58%  |
| 2     | 538       | 6.68%   |
| 3     | 90        | 1.12%   |
| 4     | 28        | 0.35%   |
| 5     | 9         | 0.11%   |
| 6     | 7         | 0.09%   |
| 7     | 2         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 1069      | 29.04%  |
| Graphics card            | 844       | 22.93%  |
| Chipcard                 | 517       | 14.05%  |
| Net/wireless             | 486       | 13.2%   |
| Multimedia controller    | 193       | 5.24%   |
| Bluetooth                | 132       | 3.59%   |
| Storage                  | 94        | 2.55%   |
| Communication controller | 82        | 2.23%   |
| Camera                   | 64        | 1.74%   |
| Sound                    | 57        | 1.55%   |
| Modem                    | 34        | 0.92%   |
| Card reader              | 32        | 0.87%   |
| Net/ethernet             | 27        | 0.73%   |
| Flash memory             | 24        | 0.65%   |
| Network                  | 8         | 0.22%   |
| Storage/ide              | 6         | 0.16%   |
| Unassigned class         | 4         | 0.11%   |
| Tv card                  | 2         | 0.05%   |
| Firewire controller      | 2         | 0.05%   |
| Unclassified device      | 1         | 0.03%   |
| Storage/raid             | 1         | 0.03%   |
| Storage/nvme             | 1         | 0.03%   |
| Dvb card                 | 1         | 0.03%   |

