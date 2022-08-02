Fedora 36 - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Fedora 36.

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

Total: 763

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [3a496f366f](https://linux-hardware.org/?probe=3a496f366f) | Aug 01, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [16a3f81537](https://linux-hardware.org/?probe=16a3f81537) | Aug 01, 2022 |
| Dell          | Latitude D620               | [f378606941](https://linux-hardware.org/?probe=f378606941) | Aug 01, 2022 |
| HONOR         | NBR-WAX9                    | [e9fcbc7798](https://linux-hardware.org/?probe=e9fcbc7798) | Aug 01, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [c79c2bd215](https://linux-hardware.org/?probe=c79c2bd215) | Jul 31, 2022 |
| HP            | Laptop 15s-eq0xxx           | [d1ae6a188c](https://linux-hardware.org/?probe=d1ae6a188c) | Jul 31, 2022 |
| HP            | Laptop 15s-eq0xxx           | [bce4496b78](https://linux-hardware.org/?probe=bce4496b78) | Jul 31, 2022 |
| HP            | Laptop 15s-eq2xxx           | [fc1b36d062](https://linux-hardware.org/?probe=fc1b36d062) | Jul 31, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | [0f38b878b5](https://linux-hardware.org/?probe=0f38b878b5) | Jul 31, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | [4b9354d287](https://linux-hardware.org/?probe=4b9354d287) | Jul 31, 2022 |
| HP            | Pavilion g6                 | [5867423d27](https://linux-hardware.org/?probe=5867423d27) | Jul 31, 2022 |
| ASUSTek       | Zenbook UX5401ZA_UX5401Z... | [b8daa2d973](https://linux-hardware.org/?probe=b8daa2d973) | Jul 30, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [85208906cd](https://linux-hardware.org/?probe=85208906cd) | Jul 30, 2022 |
| HP            | EliteBook 8570w             | [1876d4e53d](https://linux-hardware.org/?probe=1876d4e53d) | Jul 30, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | [8a472804e4](https://linux-hardware.org/?probe=8a472804e4) | Jul 30, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [0359549c36](https://linux-hardware.org/?probe=0359549c36) | Jul 30, 2022 |
| Dell          | Inspiron M5010              | [bd4cf45b33](https://linux-hardware.org/?probe=bd4cf45b33) | Jul 30, 2022 |
| Acer          | Aspire A715-41G             | [3881e3998f](https://linux-hardware.org/?probe=3881e3998f) | Jul 30, 2022 |
| Acer          | Nitro AN515-55              | [b279b1558f](https://linux-hardware.org/?probe=b279b1558f) | Jul 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [320bc76144](https://linux-hardware.org/?probe=320bc76144) | Jul 30, 2022 |
| Dell          | Latitude E6520              | [0a7e1cdcaf](https://linux-hardware.org/?probe=0a7e1cdcaf) | Jul 30, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [e5e5cc4bbc](https://linux-hardware.org/?probe=e5e5cc4bbc) | Jul 29, 2022 |
| HP            | Victus by Gaming Laptop ... | [8d729c2a6b](https://linux-hardware.org/?probe=8d729c2a6b) | Jul 29, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [cd5aa49da7](https://linux-hardware.org/?probe=cd5aa49da7) | Jul 29, 2022 |
| Lenovo        | Yoga S740-14IIL 81RM        | [a308d89f1f](https://linux-hardware.org/?probe=a308d89f1f) | Jul 29, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [486ef751f0](https://linux-hardware.org/?probe=486ef751f0) | Jul 29, 2022 |
| Dell          | XPS 15 9560                 | [40ba0a0b07](https://linux-hardware.org/?probe=40ba0a0b07) | Jul 29, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [3986399fe4](https://linux-hardware.org/?probe=3986399fe4) | Jul 29, 2022 |
| Lenovo        | ThinkPad X240 20AMS28505    | [f159c45adf](https://linux-hardware.org/?probe=f159c45adf) | Jul 29, 2022 |
| Dell          | Inspiron 7460               | [9f3420ac40](https://linux-hardware.org/?probe=9f3420ac40) | Jul 29, 2022 |
| HUAWEI        | WRT-WX9                     | [ed09406e6c](https://linux-hardware.org/?probe=ed09406e6c) | Jul 28, 2022 |
| HP            | EliteBook 820 G3            | [a96c616d62](https://linux-hardware.org/?probe=a96c616d62) | Jul 28, 2022 |
| HP            | 348 G4                      | [034e49f6dc](https://linux-hardware.org/?probe=034e49f6dc) | Jul 28, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [238fa8aa34](https://linux-hardware.org/?probe=238fa8aa34) | Jul 28, 2022 |
| Acer          | Aspire A515-45              | [47dee227ba](https://linux-hardware.org/?probe=47dee227ba) | Jul 28, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [066e5eb95d](https://linux-hardware.org/?probe=066e5eb95d) | Jul 28, 2022 |
| ASUSTek       | X750JN                      | [58fe3e4ae8](https://linux-hardware.org/?probe=58fe3e4ae8) | Jul 28, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [1bc8715e4e](https://linux-hardware.org/?probe=1bc8715e4e) | Jul 27, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [c68abe4e1a](https://linux-hardware.org/?probe=c68abe4e1a) | Jul 27, 2022 |
| Clevo         | M570TU                      | [b1f3c16be7](https://linux-hardware.org/?probe=b1f3c16be7) | Jul 27, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [e3fff7dcf4](https://linux-hardware.org/?probe=e3fff7dcf4) | Jul 27, 2022 |
| HP            | ZBook 17 G5                 | [c1ab099582](https://linux-hardware.org/?probe=c1ab099582) | Jul 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [f7d226a34a](https://linux-hardware.org/?probe=f7d226a34a) | Jul 27, 2022 |
| HP            | ZBook 17 G5                 | [b690b57222](https://linux-hardware.org/?probe=b690b57222) | Jul 27, 2022 |
| HP            | ZBook 17 G5                 | [af6e67c798](https://linux-hardware.org/?probe=af6e67c798) | Jul 27, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [2773e9510b](https://linux-hardware.org/?probe=2773e9510b) | Jul 27, 2022 |
| HP            | Laptop 15s-eq2xxx           | [90b6fd9754](https://linux-hardware.org/?probe=90b6fd9754) | Jul 27, 2022 |
| HP            | Laptop 15s-eq2xxx           | [1af666a847](https://linux-hardware.org/?probe=1af666a847) | Jul 27, 2022 |
| ASUSTek       | X750JN                      | [a4f3fc8ddd](https://linux-hardware.org/?probe=a4f3fc8ddd) | Jul 27, 2022 |
| HUAWEI        | HVY-WXX9                    | [c2fc2235eb](https://linux-hardware.org/?probe=c2fc2235eb) | Jul 27, 2022 |
| HUAWEI        | HVY-WXX9                    | [f18835e5a1](https://linux-hardware.org/?probe=f18835e5a1) | Jul 27, 2022 |
| HP            | Notebook                    | [f85df4e2d5](https://linux-hardware.org/?probe=f85df4e2d5) | Jul 26, 2022 |
| Dell          | Latitude E6520              | [b7436c1d3d](https://linux-hardware.org/?probe=b7436c1d3d) | Jul 26, 2022 |
| Lenovo        | ThinkPad T430 2349DN4       | [0c145b1409](https://linux-hardware.org/?probe=0c145b1409) | Jul 25, 2022 |
| Dell          | Latitude 7320               | [83301910d0](https://linux-hardware.org/?probe=83301910d0) | Jul 25, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [52d58f31bb](https://linux-hardware.org/?probe=52d58f31bb) | Jul 25, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [d3ac2d72dd](https://linux-hardware.org/?probe=d3ac2d72dd) | Jul 25, 2022 |
| ASUSTek       | K55VJ                       | [7c0ae7deec](https://linux-hardware.org/?probe=7c0ae7deec) | Jul 25, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [2db0d89beb](https://linux-hardware.org/?probe=2db0d89beb) | Jul 25, 2022 |
| Dell          | Latitude E6520              | [0675bbd9d0](https://linux-hardware.org/?probe=0675bbd9d0) | Jul 25, 2022 |
| Aquarius      | Cmp NS765                   | [9c9200701e](https://linux-hardware.org/?probe=9c9200701e) | Jul 24, 2022 |
| Dell          | Latitude E5420              | [b298e3bffa](https://linux-hardware.org/?probe=b298e3bffa) | Jul 24, 2022 |
| HP            | Notebook                    | [d5802ce082](https://linux-hardware.org/?probe=d5802ce082) | Jul 24, 2022 |
| Dell          | Latitude E6520              | [b5d9fa066a](https://linux-hardware.org/?probe=b5d9fa066a) | Jul 24, 2022 |
| Lenovo        | ThinkPad T590 20N5S4R800    | [60dd75eca9](https://linux-hardware.org/?probe=60dd75eca9) | Jul 24, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [3721b1c82a](https://linux-hardware.org/?probe=3721b1c82a) | Jul 24, 2022 |
| Apple         | MacBookPro9,2               | [99ee81b243](https://linux-hardware.org/?probe=99ee81b243) | Jul 23, 2022 |
| Lenovo        | IdeaPad 5 Pro 16IHU6 82L... | [b16e17a798](https://linux-hardware.org/?probe=b16e17a798) | Jul 23, 2022 |
| Lenovo        | ThinkPad T480s 20L8S02D0... | [ce6a0d666e](https://linux-hardware.org/?probe=ce6a0d666e) | Jul 23, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [1c50bea602](https://linux-hardware.org/?probe=1c50bea602) | Jul 23, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [e06aafac8c](https://linux-hardware.org/?probe=e06aafac8c) | Jul 23, 2022 |
| Lenovo        | ThinkPad T480s 20L8S02D0... | [6a1cb48f15](https://linux-hardware.org/?probe=6a1cb48f15) | Jul 23, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [1077085bf6](https://linux-hardware.org/?probe=1077085bf6) | Jul 23, 2022 |
| Lenovo        | 81FV                        | [aa9e5c9f73](https://linux-hardware.org/?probe=aa9e5c9f73) | Jul 22, 2022 |
| Dell          | Latitude E7440              | [d5ca3d7f7e](https://linux-hardware.org/?probe=d5ca3d7f7e) | Jul 22, 2022 |
| Lenovo        | ThinkPad T480s 20L8S02D0... | [55f1eaa96c](https://linux-hardware.org/?probe=55f1eaa96c) | Jul 22, 2022 |
| HP            | Laptop 15s-eq2xxx           | [5670dc3033](https://linux-hardware.org/?probe=5670dc3033) | Jul 22, 2022 |
| Lenovo        | ThinkPad T480s 20L8S02D0... | [090cc78b83](https://linux-hardware.org/?probe=090cc78b83) | Jul 22, 2022 |
| Lenovo        | ThinkPad T430 2349DN4       | [fa8f2adca9](https://linux-hardware.org/?probe=fa8f2adca9) | Jul 22, 2022 |
| ASUSTek       | X750JN                      | [6bf181ed49](https://linux-hardware.org/?probe=6bf181ed49) | Jul 22, 2022 |
| Acer          | Aspire V3-572               | [5938905628](https://linux-hardware.org/?probe=5938905628) | Jul 22, 2022 |
| Samsung       | 550XBE/350XBE               | [b23cfb57cf](https://linux-hardware.org/?probe=b23cfb57cf) | Jul 21, 2022 |
| HP            | 240 G4                      | [449fb8b8f8](https://linux-hardware.org/?probe=449fb8b8f8) | Jul 21, 2022 |
| Dell          | XPS 15 9520                 | [51ddccaf88](https://linux-hardware.org/?probe=51ddccaf88) | Jul 21, 2022 |
| ASUSTek       | X541NA                      | [51aefa0464](https://linux-hardware.org/?probe=51aefa0464) | Jul 21, 2022 |
| Lenovo        | ThinkPad T580 20LAS27000    | [a78a8e806f](https://linux-hardware.org/?probe=a78a8e806f) | Jul 21, 2022 |
| HP            | Laptop 17-by0xxx            | [afa7d8ba6c](https://linux-hardware.org/?probe=afa7d8ba6c) | Jul 21, 2022 |
| ASUSTek       | X541UVK                     | [a34ee52169](https://linux-hardware.org/?probe=a34ee52169) | Jul 21, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [c1204438f8](https://linux-hardware.org/?probe=c1204438f8) | Jul 20, 2022 |
| GPU Compan... | GWNR51416                   | [ea200c839f](https://linux-hardware.org/?probe=ea200c839f) | Jul 20, 2022 |
| HP            | EliteBook 850 G5            | [0ffa75c50b](https://linux-hardware.org/?probe=0ffa75c50b) | Jul 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [3c346ed8da](https://linux-hardware.org/?probe=3c346ed8da) | Jul 20, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [4cde663cf9](https://linux-hardware.org/?probe=4cde663cf9) | Jul 20, 2022 |
| GPU Compan... | GWNR51416                   | [effe49f996](https://linux-hardware.org/?probe=effe49f996) | Jul 20, 2022 |
| GPU Compan... | GWNR51416                   | [8d18b6813f](https://linux-hardware.org/?probe=8d18b6813f) | Jul 20, 2022 |
| Dell          | G3 3590                     | [920eed9524](https://linux-hardware.org/?probe=920eed9524) | Jul 19, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [944ba71eef](https://linux-hardware.org/?probe=944ba71eef) | Jul 19, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [56e3efd7bc](https://linux-hardware.org/?probe=56e3efd7bc) | Jul 19, 2022 |
| HP            | Notebook                    | [79c0f60f74](https://linux-hardware.org/?probe=79c0f60f74) | Jul 19, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [ac6aba12f5](https://linux-hardware.org/?probe=ac6aba12f5) | Jul 19, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [7f4f42a3f7](https://linux-hardware.org/?probe=7f4f42a3f7) | Jul 19, 2022 |
| HP            | EliteBook 8570w             | [6b8bf59f68](https://linux-hardware.org/?probe=6b8bf59f68) | Jul 19, 2022 |
| Lenovo        | IdeaPad U430 Touch 20270    | [2c43b01e55](https://linux-hardware.org/?probe=2c43b01e55) | Jul 18, 2022 |
| Dell          | Latitude E6230              | [a66cad27e9](https://linux-hardware.org/?probe=a66cad27e9) | Jul 18, 2022 |
| Dell          | Latitude E7470              | [709a460528](https://linux-hardware.org/?probe=709a460528) | Jul 18, 2022 |
| MSI           | MS-14Y1                     | [782beac866](https://linux-hardware.org/?probe=782beac866) | Jul 18, 2022 |
| Google        | Kohaku                      | [2f21de3ff6](https://linux-hardware.org/?probe=2f21de3ff6) | Jul 18, 2022 |
| Pegatron      | D15K                        | [7f8fa03161](https://linux-hardware.org/?probe=7f8fa03161) | Jul 17, 2022 |
| Framework     | Laptop                      | [84d20eb09a](https://linux-hardware.org/?probe=84d20eb09a) | Jul 17, 2022 |
| Framework     | Laptop                      | [0489cc39db](https://linux-hardware.org/?probe=0489cc39db) | Jul 17, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [df94c841af](https://linux-hardware.org/?probe=df94c841af) | Jul 17, 2022 |
| Dell          | Inspiron 5515               | [502c19838a](https://linux-hardware.org/?probe=502c19838a) | Jul 17, 2022 |
| Unknown       | Unknown                     | [251f348fe5](https://linux-hardware.org/?probe=251f348fe5) | Jul 17, 2022 |
| ASUSTek       | X541NA                      | [3caa5cc13d](https://linux-hardware.org/?probe=3caa5cc13d) | Jul 17, 2022 |
| Dell          | Latitude E5440              | [c8e68471c1](https://linux-hardware.org/?probe=c8e68471c1) | Jul 16, 2022 |
| Acer          | Aspire A315-23              | [5f1ff52baa](https://linux-hardware.org/?probe=5f1ff52baa) | Jul 16, 2022 |
| HP            | 250 G5                      | [979d1aea6f](https://linux-hardware.org/?probe=979d1aea6f) | Jul 16, 2022 |
| Lenovo        | ThinkPad T420 4236C92       | [40d837716b](https://linux-hardware.org/?probe=40d837716b) | Jul 16, 2022 |
| Alienware     | x17 R1                      | [9fc2d6416d](https://linux-hardware.org/?probe=9fc2d6416d) | Jul 16, 2022 |
| System76      | Bonobo Extreme              | [6c7f545300](https://linux-hardware.org/?probe=6c7f545300) | Jul 16, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [18d1378620](https://linux-hardware.org/?probe=18d1378620) | Jul 16, 2022 |
| Dell          | XPS 13 7390                 | [eff723b9f2](https://linux-hardware.org/?probe=eff723b9f2) | Jul 16, 2022 |
| Acer          | Aspire V3-572               | [48dd04e4c8](https://linux-hardware.org/?probe=48dd04e4c8) | Jul 16, 2022 |
| Acer          | Aspire V3-572               | [3378b0fc15](https://linux-hardware.org/?probe=3378b0fc15) | Jul 16, 2022 |
| Toshiba       | Satellite L505D             | [1d7b1ed7c8](https://linux-hardware.org/?probe=1d7b1ed7c8) | Jul 15, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [42de47cdc1](https://linux-hardware.org/?probe=42de47cdc1) | Jul 15, 2022 |
| Lenovo        | ThinkPad T480 20L6S0EK00    | [dd43fd4b04](https://linux-hardware.org/?probe=dd43fd4b04) | Jul 15, 2022 |
| Lenovo        | ThinkPad T480 20L6S0EK00    | [9ca58ddce1](https://linux-hardware.org/?probe=9ca58ddce1) | Jul 15, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [329ce2f7f8](https://linux-hardware.org/?probe=329ce2f7f8) | Jul 15, 2022 |
| Dell          | G3 3590                     | [86835e6c2b](https://linux-hardware.org/?probe=86835e6c2b) | Jul 15, 2022 |
| ASUSTek       | X541NA                      | [b9476b6cf9](https://linux-hardware.org/?probe=b9476b6cf9) | Jul 15, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [7812a0737e](https://linux-hardware.org/?probe=7812a0737e) | Jul 15, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [ea97effc52](https://linux-hardware.org/?probe=ea97effc52) | Jul 14, 2022 |
| Dell          | Inspiron M5010              | [56be64f444](https://linux-hardware.org/?probe=56be64f444) | Jul 14, 2022 |
| ASUSTek       | GL702ZC                     | [755f571a3e](https://linux-hardware.org/?probe=755f571a3e) | Jul 14, 2022 |
| Lenovo        | G400s VILG1                 | [fbaf6e2d8f](https://linux-hardware.org/?probe=fbaf6e2d8f) | Jul 13, 2022 |
| Lenovo        | G400s VILG1                 | [33853365fd](https://linux-hardware.org/?probe=33853365fd) | Jul 13, 2022 |
| Gigabyte      | AERO 17 KC                  | [b6398b12e2](https://linux-hardware.org/?probe=b6398b12e2) | Jul 13, 2022 |
| Lenovo        | ThinkPad P50 20EQA05JCL     | [43f5b3c05d](https://linux-hardware.org/?probe=43f5b3c05d) | Jul 13, 2022 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [f91143bc89](https://linux-hardware.org/?probe=f91143bc89) | Jul 13, 2022 |
| GPD           | G1621-02                    | [25da86e752](https://linux-hardware.org/?probe=25da86e752) | Jul 13, 2022 |
| Sony          | SVF1531V8CW                 | [bebf2fb162](https://linux-hardware.org/?probe=bebf2fb162) | Jul 13, 2022 |
| Dell          | Inspiron 5559               | [a687046e06](https://linux-hardware.org/?probe=a687046e06) | Jul 13, 2022 |
| Dell          | Inspiron 5559               | [c4b25937a7](https://linux-hardware.org/?probe=c4b25937a7) | Jul 13, 2022 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | [de328d9562](https://linux-hardware.org/?probe=de328d9562) | Jul 13, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [f422c77bb1](https://linux-hardware.org/?probe=f422c77bb1) | Jul 12, 2022 |
| Lenovo        | ThinkPad T490s 20NYS0LY0... | [882680a962](https://linux-hardware.org/?probe=882680a962) | Jul 12, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [eb883a57f4](https://linux-hardware.org/?probe=eb883a57f4) | Jul 12, 2022 |
| HP            | Sona                        | [504fddb8e9](https://linux-hardware.org/?probe=504fddb8e9) | Jul 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [ea08980c33](https://linux-hardware.org/?probe=ea08980c33) | Jul 11, 2022 |
| VALE          | Notebook Classic C140       | [d6cc520dbe](https://linux-hardware.org/?probe=d6cc520dbe) | Jul 11, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [6b29072d9e](https://linux-hardware.org/?probe=6b29072d9e) | Jul 11, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [ce42b6cb75](https://linux-hardware.org/?probe=ce42b6cb75) | Jul 11, 2022 |
| HP            | ProBook 6570b               | [5796920cf8](https://linux-hardware.org/?probe=5796920cf8) | Jul 11, 2022 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | [c1ed74053e](https://linux-hardware.org/?probe=c1ed74053e) | Jul 11, 2022 |
| Framework     | Laptop                      | [a13ef2beee](https://linux-hardware.org/?probe=a13ef2beee) | Jul 11, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [a379e2a103](https://linux-hardware.org/?probe=a379e2a103) | Jul 11, 2022 |
| HP            | ProBook 6570b               | [4b10924d6a](https://linux-hardware.org/?probe=4b10924d6a) | Jul 10, 2022 |
| Panasonic     | FZG1-3                      | [753cc1d311](https://linux-hardware.org/?probe=753cc1d311) | Jul 10, 2022 |
| Panasonic     | FZG1-3                      | [01d4651376](https://linux-hardware.org/?probe=01d4651376) | Jul 10, 2022 |
| MSI           | GL75 Leopard 10SEK          | [532348a02c](https://linux-hardware.org/?probe=532348a02c) | Jul 10, 2022 |
| Dell          | Inspiron 3558               | [14cacca8ad](https://linux-hardware.org/?probe=14cacca8ad) | Jul 09, 2022 |
| Lenovo        | IdeaPad 110-14ISK 80UC      | [269ebd1a4d](https://linux-hardware.org/?probe=269ebd1a4d) | Jul 09, 2022 |
| HP            | ZBook Power G7 Mobile Wo... | [8270068517](https://linux-hardware.org/?probe=8270068517) | Jul 09, 2022 |
| MSI           | Summit E13FlipEvo A11MT     | [36151ae5c3](https://linux-hardware.org/?probe=36151ae5c3) | Jul 09, 2022 |
| MSI           | Bravo 17 A4DDK              | [9f9d1cac61](https://linux-hardware.org/?probe=9f9d1cac61) | Jul 09, 2022 |
| Dell          | Vostro 3590                 | [7195de93ae](https://linux-hardware.org/?probe=7195de93ae) | Jul 09, 2022 |
| HP            | Laptop 17z-cp000            | [f6f0740c36](https://linux-hardware.org/?probe=f6f0740c36) | Jul 09, 2022 |
| HP            | ProBook 6570b               | [b90b75215d](https://linux-hardware.org/?probe=b90b75215d) | Jul 09, 2022 |
| Acer          | Predator PH315-53           | [b6c6516360](https://linux-hardware.org/?probe=b6c6516360) | Jul 09, 2022 |
| Dell          | Latitude 3400               | [6a36fb9dd9](https://linux-hardware.org/?probe=6a36fb9dd9) | Jul 09, 2022 |
| HP            | EliteBook 8470p             | [c048bb9697](https://linux-hardware.org/?probe=c048bb9697) | Jul 09, 2022 |
| MSI           | GF63 Thin 8RCS              | [886728c1b6](https://linux-hardware.org/?probe=886728c1b6) | Jul 08, 2022 |
| Lenovo        | V14-ADA 82C6                | [e72ccdd0c6](https://linux-hardware.org/?probe=e72ccdd0c6) | Jul 08, 2022 |
| ASUSTek       | X550CC                      | [a57dba854b](https://linux-hardware.org/?probe=a57dba854b) | Jul 08, 2022 |
| Notebook      | NH55RGQ                     | [37de891a60](https://linux-hardware.org/?probe=37de891a60) | Jul 08, 2022 |
| Lenovo        | ThinkPad T460 20FMS2292S    | [cd5635c63c](https://linux-hardware.org/?probe=cd5635c63c) | Jul 08, 2022 |
| HP            | Pavilion g6                 | [30085f92b1](https://linux-hardware.org/?probe=30085f92b1) | Jul 08, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [a64c483143](https://linux-hardware.org/?probe=a64c483143) | Jul 08, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [84f475721b](https://linux-hardware.org/?probe=84f475721b) | Jul 08, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [447ba923ac](https://linux-hardware.org/?probe=447ba923ac) | Jul 08, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [75f67b342a](https://linux-hardware.org/?probe=75f67b342a) | Jul 08, 2022 |
| Acer          | Predator PH315-53           | [69b6f2bdad](https://linux-hardware.org/?probe=69b6f2bdad) | Jul 08, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [e850b43a12](https://linux-hardware.org/?probe=e850b43a12) | Jul 07, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [39e56d90b1](https://linux-hardware.org/?probe=39e56d90b1) | Jul 07, 2022 |
| Acer          | Nitro AN515-55              | [85845c3282](https://linux-hardware.org/?probe=85845c3282) | Jul 07, 2022 |
| ASUSTek       | X555DG                      | [b7a2c97bf2](https://linux-hardware.org/?probe=b7a2c97bf2) | Jul 07, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [e1f5b40789](https://linux-hardware.org/?probe=e1f5b40789) | Jul 07, 2022 |
| Lenovo        | ThinkPad T500 2242CTO       | [106199561c](https://linux-hardware.org/?probe=106199561c) | Jul 07, 2022 |
| Dell          | XPS 17 9710                 | [81b2d3fa4f](https://linux-hardware.org/?probe=81b2d3fa4f) | Jul 06, 2022 |
| Toshiba       | Satellite L505D             | [cf5fedc6e5](https://linux-hardware.org/?probe=cf5fedc6e5) | Jul 06, 2022 |
| HP            | ProBook 450 G2              | [aeb16eb1eb](https://linux-hardware.org/?probe=aeb16eb1eb) | Jul 06, 2022 |
| Lenovo        | ThinkPad L380 20M5000FUS    | [9c6ab1a171](https://linux-hardware.org/?probe=9c6ab1a171) | Jul 06, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [c75201835c](https://linux-hardware.org/?probe=c75201835c) | Jul 06, 2022 |
| Dell          | Inspiron 16 5625            | [dcbe63005c](https://linux-hardware.org/?probe=dcbe63005c) | Jul 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [c8b9e41a50](https://linux-hardware.org/?probe=c8b9e41a50) | Jul 06, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [dcd03a28be](https://linux-hardware.org/?probe=dcd03a28be) | Jul 06, 2022 |
| HP            | ZBook Firefly 15.6 inch ... | [454fed051a](https://linux-hardware.org/?probe=454fed051a) | Jul 06, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [5afb466a35](https://linux-hardware.org/?probe=5afb466a35) | Jul 06, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [162080ffcf](https://linux-hardware.org/?probe=162080ffcf) | Jul 06, 2022 |
| Acer          | Aspire V3-572               | [4df173f8f2](https://linux-hardware.org/?probe=4df173f8f2) | Jul 06, 2022 |
| Acer          | Aspire V3-572               | [8dbec85d36](https://linux-hardware.org/?probe=8dbec85d36) | Jul 06, 2022 |
| Lenovo        | ThinkPad T460p 20FXS0550... | [a3c85d395b](https://linux-hardware.org/?probe=a3c85d395b) | Jul 05, 2022 |
| System76      | Oryx Pro                    | [338a8ed5ab](https://linux-hardware.org/?probe=338a8ed5ab) | Jul 05, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [4009adaca2](https://linux-hardware.org/?probe=4009adaca2) | Jul 05, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | [4826df34b3](https://linux-hardware.org/?probe=4826df34b3) | Jul 05, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [0d03afb249](https://linux-hardware.org/?probe=0d03afb249) | Jul 05, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [4d4cd5bae0](https://linux-hardware.org/?probe=4d4cd5bae0) | Jul 05, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [2cbcdfe2db](https://linux-hardware.org/?probe=2cbcdfe2db) | Jul 05, 2022 |
| HP            | ZBook Power G7 Mobile Wo... | [7f64f81a29](https://linux-hardware.org/?probe=7f64f81a29) | Jul 04, 2022 |
| HP            | ProBook 645 G3              | [5c37a32531](https://linux-hardware.org/?probe=5c37a32531) | Jul 04, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [7bb2a0b59a](https://linux-hardware.org/?probe=7bb2a0b59a) | Jul 04, 2022 |
| HUAWEI        | KLVL-WXXW                   | [59a1c1c8b1](https://linux-hardware.org/?probe=59a1c1c8b1) | Jul 04, 2022 |
| Chuwi         | GemiBook                    | [881c250e4f](https://linux-hardware.org/?probe=881c250e4f) | Jul 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [9e9a46d8ec](https://linux-hardware.org/?probe=9e9a46d8ec) | Jul 04, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [2ed808bbcc](https://linux-hardware.org/?probe=2ed808bbcc) | Jul 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [5a6c158296](https://linux-hardware.org/?probe=5a6c158296) | Jul 04, 2022 |
| ASUSTek       | TP501UB                     | [4cebce6bab](https://linux-hardware.org/?probe=4cebce6bab) | Jul 04, 2022 |
| ASUSTek       | TP501UB                     | [6ee62813e8](https://linux-hardware.org/?probe=6ee62813e8) | Jul 04, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [d2dd306cb4](https://linux-hardware.org/?probe=d2dd306cb4) | Jul 04, 2022 |
| HP            | Notebook                    | [b9eb2e4cdd](https://linux-hardware.org/?probe=b9eb2e4cdd) | Jul 04, 2022 |
| HP            | 255 G8 Notebook PC          | [af74b651d5](https://linux-hardware.org/?probe=af74b651d5) | Jul 04, 2022 |
| HP            | EliteBook 8470p             | [4600681149](https://linux-hardware.org/?probe=4600681149) | Jul 03, 2022 |
| HP            | EliteBook 8470p             | [85c5a62101](https://linux-hardware.org/?probe=85c5a62101) | Jul 03, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [d0e94cff94](https://linux-hardware.org/?probe=d0e94cff94) | Jul 03, 2022 |
| HP            | EliteBook 840 G1            | [9705c40e85](https://linux-hardware.org/?probe=9705c40e85) | Jul 03, 2022 |
| Apple         | MacBookPro5,1               | [ac53d2f956](https://linux-hardware.org/?probe=ac53d2f956) | Jul 02, 2022 |
| Dell          | XPS 13 9350                 | [0c8bcdbcb1](https://linux-hardware.org/?probe=0c8bcdbcb1) | Jul 02, 2022 |
| Lenovo        | ThinkPad T480s 20L7004NM... | [716bd7e41f](https://linux-hardware.org/?probe=716bd7e41f) | Jul 02, 2022 |
| Lenovo        | ThinkPad T480 20L6S2EQ00    | [576f59ec1b](https://linux-hardware.org/?probe=576f59ec1b) | Jul 02, 2022 |
| Lenovo        | ThinkPad T480 20L6S2EQ00    | [4d9cb098c8](https://linux-hardware.org/?probe=4d9cb098c8) | Jul 01, 2022 |
| Lenovo        | ThinkPad T480 20L6S2EQ00    | [1b45ef7d10](https://linux-hardware.org/?probe=1b45ef7d10) | Jul 01, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [16413aeb23](https://linux-hardware.org/?probe=16413aeb23) | Jul 01, 2022 |
| HP            | Laptop 14s-cf2xxx           | [8da2258fea](https://linux-hardware.org/?probe=8da2258fea) | Jul 01, 2022 |
| Dell          | Inspiron M5010              | [14b9aa33d2](https://linux-hardware.org/?probe=14b9aa33d2) | Jul 01, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [2671f4ffe2](https://linux-hardware.org/?probe=2671f4ffe2) | Jul 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [c9d0d64896](https://linux-hardware.org/?probe=c9d0d64896) | Jul 01, 2022 |
| Framework     | Laptop                      | [1089f37daf](https://linux-hardware.org/?probe=1089f37daf) | Jul 01, 2022 |
| Lenovo        | ThinkPad T460 20FMS2292S    | [cf313915ab](https://linux-hardware.org/?probe=cf313915ab) | Jun 30, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [3af286a188](https://linux-hardware.org/?probe=3af286a188) | Jun 30, 2022 |
| HP            | EliteBook 8470p             | [cd488e4f64](https://linux-hardware.org/?probe=cd488e4f64) | Jun 30, 2022 |
| HP            | EliteBook 8470p             | [52dfa0a4ee](https://linux-hardware.org/?probe=52dfa0a4ee) | Jun 30, 2022 |
| Acer          | Aspire A315-55G             | [e6d7a2a642](https://linux-hardware.org/?probe=e6d7a2a642) | Jun 30, 2022 |
| HP            | Laptop 15-da0xxx            | [9c512247ff](https://linux-hardware.org/?probe=9c512247ff) | Jun 30, 2022 |
| Lenovo        | ThinkPad T410 2518A37       | [4e15b37546](https://linux-hardware.org/?probe=4e15b37546) | Jun 30, 2022 |
| Dell          | Inspiron 3543               | [1f9d3b4a6c](https://linux-hardware.org/?probe=1f9d3b4a6c) | Jun 29, 2022 |
| HP            | Laptop 15s-eq2xxx           | [5acbf09f01](https://linux-hardware.org/?probe=5acbf09f01) | Jun 29, 2022 |
| ASUSTek       | UX302LA                     | [6092e85ae8](https://linux-hardware.org/?probe=6092e85ae8) | Jun 29, 2022 |
| Getac         | B300-X                      | [eb752b6c15](https://linux-hardware.org/?probe=eb752b6c15) | Jun 29, 2022 |
| HUAWEI        | BOD-WXX9                    | [9c3e14320e](https://linux-hardware.org/?probe=9c3e14320e) | Jun 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [43c87260b2](https://linux-hardware.org/?probe=43c87260b2) | Jun 29, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [7406ba0eb2](https://linux-hardware.org/?probe=7406ba0eb2) | Jun 29, 2022 |
| Alienware     | 17                          | [715b5b0dce](https://linux-hardware.org/?probe=715b5b0dce) | Jun 29, 2022 |
| Apple         | MacBookAir6,1               | [c3172fd9cf](https://linux-hardware.org/?probe=c3172fd9cf) | Jun 28, 2022 |
| Dell          | Precision M6800             | [027cb621ef](https://linux-hardware.org/?probe=027cb621ef) | Jun 28, 2022 |
| Dell          | Latitude 5511               | [c361c37273](https://linux-hardware.org/?probe=c361c37273) | Jun 28, 2022 |
| ASUSTek       | X750JN                      | [4ba4d14a1a](https://linux-hardware.org/?probe=4ba4d14a1a) | Jun 28, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [d240efa39f](https://linux-hardware.org/?probe=d240efa39f) | Jun 28, 2022 |
| Apple         | MacBookPro12,1              | [570dd2f164](https://linux-hardware.org/?probe=570dd2f164) | Jun 28, 2022 |
| Toshiba       | Satellite C855-12R          | [e94a109546](https://linux-hardware.org/?probe=e94a109546) | Jun 28, 2022 |
| Dell          | Inspiron N5110              | [239e8c86c0](https://linux-hardware.org/?probe=239e8c86c0) | Jun 28, 2022 |
| Dell          | Latitude E6520              | [f688527838](https://linux-hardware.org/?probe=f688527838) | Jun 27, 2022 |
| Gigabyte      | RC14UD                      | [d2b55252d8](https://linux-hardware.org/?probe=d2b55252d8) | Jun 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [1c4ace32a2](https://linux-hardware.org/?probe=1c4ace32a2) | Jun 27, 2022 |
| Apple         | MacBookPro5,1               | [1e14793557](https://linux-hardware.org/?probe=1e14793557) | Jun 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [3a651b23fb](https://linux-hardware.org/?probe=3a651b23fb) | Jun 26, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS5... | [de3ca4e422](https://linux-hardware.org/?probe=de3ca4e422) | Jun 26, 2022 |
| Acer          | Swift SF114-32              | [25e6653354](https://linux-hardware.org/?probe=25e6653354) | Jun 26, 2022 |
| MSI           | GF63 Thin 9SCXR             | [db6195eed2](https://linux-hardware.org/?probe=db6195eed2) | Jun 26, 2022 |
| Timi          | A35S                        | [606e376264](https://linux-hardware.org/?probe=606e376264) | Jun 26, 2022 |
| Dell          | Latitude 7300               | [a7939aeb9e](https://linux-hardware.org/?probe=a7939aeb9e) | Jun 26, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [400eaba39f](https://linux-hardware.org/?probe=400eaba39f) | Jun 26, 2022 |
| HP            | Compaq CQ58                 | [5948b56a82](https://linux-hardware.org/?probe=5948b56a82) | Jun 25, 2022 |
| Dell          | XPS 13 9310                 | [fa3d29c80b](https://linux-hardware.org/?probe=fa3d29c80b) | Jun 25, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [81a9b9847d](https://linux-hardware.org/?probe=81a9b9847d) | Jun 25, 2022 |
| Dell          | Inspiron 5437               | [e206b319a2](https://linux-hardware.org/?probe=e206b319a2) | Jun 25, 2022 |
| Gigabyte      | G5 KC                       | [5ef620811f](https://linux-hardware.org/?probe=5ef620811f) | Jun 25, 2022 |
| HP            | Pavilion g6                 | [d2e82f01d9](https://linux-hardware.org/?probe=d2e82f01d9) | Jun 25, 2022 |
| HP            | Laptop 15s-fq2xxx           | [170f5de9e2](https://linux-hardware.org/?probe=170f5de9e2) | Jun 25, 2022 |
| HP            | OMEN Notebook PC 15         | [66f845b63e](https://linux-hardware.org/?probe=66f845b63e) | Jun 25, 2022 |
| Unknown       | Unknown                     | [6e62883390](https://linux-hardware.org/?probe=6e62883390) | Jun 25, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [66283ad8cd](https://linux-hardware.org/?probe=66283ad8cd) | Jun 24, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [3b78b34416](https://linux-hardware.org/?probe=3b78b34416) | Jun 24, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [58ab145788](https://linux-hardware.org/?probe=58ab145788) | Jun 24, 2022 |
| HP            | Laptop 15-ef2xxx            | [3e16709617](https://linux-hardware.org/?probe=3e16709617) | Jun 24, 2022 |
| Packard Be... | EasyNote TE69HW             | [d292d79bbe](https://linux-hardware.org/?probe=d292d79bbe) | Jun 24, 2022 |
| Lenovo        | ThinkPad T520 4243VE1       | [7fcfec26eb](https://linux-hardware.org/?probe=7fcfec26eb) | Jun 24, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [2c0b9c6402](https://linux-hardware.org/?probe=2c0b9c6402) | Jun 24, 2022 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [bb8541d805](https://linux-hardware.org/?probe=bb8541d805) | Jun 24, 2022 |
| Acer          | Nitro AN515-54              | [afce38a95a](https://linux-hardware.org/?probe=afce38a95a) | Jun 24, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [d4b96de9b6](https://linux-hardware.org/?probe=d4b96de9b6) | Jun 24, 2022 |
| Dell          | Precision 5550              | [0811e8c956](https://linux-hardware.org/?probe=0811e8c956) | Jun 23, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [ac634d8aa9](https://linux-hardware.org/?probe=ac634d8aa9) | Jun 23, 2022 |
| Dell          | Precision 5550              | [0ae65f654e](https://linux-hardware.org/?probe=0ae65f654e) | Jun 23, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [926d4055f7](https://linux-hardware.org/?probe=926d4055f7) | Jun 23, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | [223e43004a](https://linux-hardware.org/?probe=223e43004a) | Jun 23, 2022 |
| HP            | 250 G7 Notebook PC          | [6ec1b55ac0](https://linux-hardware.org/?probe=6ec1b55ac0) | Jun 23, 2022 |
| Lenovo        | G510 20238                  | [1b382e0eb0](https://linux-hardware.org/?probe=1b382e0eb0) | Jun 23, 2022 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [5dd91493a8](https://linux-hardware.org/?probe=5dd91493a8) | Jun 23, 2022 |
| ASUSTek       | K46CB                       | [65344cb089](https://linux-hardware.org/?probe=65344cb089) | Jun 23, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [f002062377](https://linux-hardware.org/?probe=f002062377) | Jun 22, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [1967dad271](https://linux-hardware.org/?probe=1967dad271) | Jun 22, 2022 |
| Positivo      | VJF155F11UAR                | [77c5ca4f1e](https://linux-hardware.org/?probe=77c5ca4f1e) | Jun 22, 2022 |
| Acer          | NC-E5-774G-75TJ             | [55fce68116](https://linux-hardware.org/?probe=55fce68116) | Jun 22, 2022 |
| HP            | ZBook 17 G4                 | [bf03eb0fa7](https://linux-hardware.org/?probe=bf03eb0fa7) | Jun 22, 2022 |
| Fujitsu       | LIFEBOOK U745               | [0fffb61902](https://linux-hardware.org/?probe=0fffb61902) | Jun 22, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [dda5fb9c20](https://linux-hardware.org/?probe=dda5fb9c20) | Jun 21, 2022 |
| HUAWEI        | MACH-WX9                    | [c6f721f315](https://linux-hardware.org/?probe=c6f721f315) | Jun 21, 2022 |
| HP            | EliteBook 830 G6            | [7c7d9af667](https://linux-hardware.org/?probe=7c7d9af667) | Jun 21, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [ae54449547](https://linux-hardware.org/?probe=ae54449547) | Jun 21, 2022 |
| GEO           | GeoBook 240                 | [f08637137c](https://linux-hardware.org/?probe=f08637137c) | Jun 21, 2022 |
| Dell          | XPS 13 9380                 | [dc134b17e9](https://linux-hardware.org/?probe=dc134b17e9) | Jun 21, 2022 |
| HP            | ProBook 440 G6              | [eeeee7321e](https://linux-hardware.org/?probe=eeeee7321e) | Jun 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [27623895a1](https://linux-hardware.org/?probe=27623895a1) | Jun 20, 2022 |
| Lenovo        | ThinkPad T495s 20QJ0012G... | [92638f1b46](https://linux-hardware.org/?probe=92638f1b46) | Jun 20, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [52aa806063](https://linux-hardware.org/?probe=52aa806063) | Jun 20, 2022 |
| Panasonic     | CFSV9-1                     | [4b7dd23ccd](https://linux-hardware.org/?probe=4b7dd23ccd) | Jun 20, 2022 |
| Apple         | MacBookPro12,1              | [666e91f182](https://linux-hardware.org/?probe=666e91f182) | Jun 20, 2022 |
| Dell          | XPS 15 9520                 | [ec6f5cce04](https://linux-hardware.org/?probe=ec6f5cce04) | Jun 20, 2022 |
| Google        | Droid                       | [5a175a2a78](https://linux-hardware.org/?probe=5a175a2a78) | Jun 20, 2022 |
| Apple         | MacBookPro12,1              | [5d9f65fbc9](https://linux-hardware.org/?probe=5d9f65fbc9) | Jun 20, 2022 |
| HP            | EliteBook 865 16 inch G9... | [9a543a0273](https://linux-hardware.org/?probe=9a543a0273) | Jun 20, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | [bbb3795dc2](https://linux-hardware.org/?probe=bbb3795dc2) | Jun 20, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [9cf3c1f84c](https://linux-hardware.org/?probe=9cf3c1f84c) | Jun 19, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [df2017f7d5](https://linux-hardware.org/?probe=df2017f7d5) | Jun 19, 2022 |
| Micro Elec... | MG-VCP17I-3070              | [e09cfb9236](https://linux-hardware.org/?probe=e09cfb9236) | Jun 19, 2022 |
| HP            | Pavilion dv7                | [ab34fbb528](https://linux-hardware.org/?probe=ab34fbb528) | Jun 19, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [3c8a4e8226](https://linux-hardware.org/?probe=3c8a4e8226) | Jun 18, 2022 |
| HUAWEI        | KLVL-WXX9                   | [a71adbf68f](https://linux-hardware.org/?probe=a71adbf68f) | Jun 18, 2022 |
| HP            | ProBook 470 G5              | [b070339877](https://linux-hardware.org/?probe=b070339877) | Jun 18, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [4a1a0294d8](https://linux-hardware.org/?probe=4a1a0294d8) | Jun 18, 2022 |
| Dell          | Precision 3571              | [9d6985b0f0](https://linux-hardware.org/?probe=9d6985b0f0) | Jun 18, 2022 |
| Dell          | Precision 3571              | [285846e1a4](https://linux-hardware.org/?probe=285846e1a4) | Jun 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [91af0ec6df](https://linux-hardware.org/?probe=91af0ec6df) | Jun 18, 2022 |
| Acer          | Swift SF314-43              | [a6116d2e8c](https://linux-hardware.org/?probe=a6116d2e8c) | Jun 18, 2022 |
| ASUSTek       | TUF Gaming FX505DY_TUF50... | [df304b4da1](https://linux-hardware.org/?probe=df304b4da1) | Jun 17, 2022 |
| Acer          | Swift SF314-43              | [674addd96b](https://linux-hardware.org/?probe=674addd96b) | Jun 17, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [e0b7e5c636](https://linux-hardware.org/?probe=e0b7e5c636) | Jun 17, 2022 |
| Dell          | XPS 13 7390                 | [9cbdc324b7](https://linux-hardware.org/?probe=9cbdc324b7) | Jun 17, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [cb6bf6ab7c](https://linux-hardware.org/?probe=cb6bf6ab7c) | Jun 17, 2022 |
| Sony          | SVE15128CNB                 | [029a230c77](https://linux-hardware.org/?probe=029a230c77) | Jun 17, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [2a28e582b5](https://linux-hardware.org/?probe=2a28e582b5) | Jun 17, 2022 |
| Acer          | Aspire E5-476G              | [df4b512aa8](https://linux-hardware.org/?probe=df4b512aa8) | Jun 17, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [a7431ef0c5](https://linux-hardware.org/?probe=a7431ef0c5) | Jun 17, 2022 |
| Samsung       | 500R5M/500R5W/501R5M        | [91f1df8a58](https://linux-hardware.org/?probe=91f1df8a58) | Jun 17, 2022 |
| Acer          | Predator PH315-53           | [7e65c001a5](https://linux-hardware.org/?probe=7e65c001a5) | Jun 17, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [e4d5856a72](https://linux-hardware.org/?probe=e4d5856a72) | Jun 16, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [4e53a55031](https://linux-hardware.org/?probe=4e53a55031) | Jun 16, 2022 |
| Dell          | XPS 13 7390                 | [7dbb9f4adf](https://linux-hardware.org/?probe=7dbb9f4adf) | Jun 16, 2022 |
| Micro Elec... | MG-VCP17I-3070              | [c6d123b5ec](https://linux-hardware.org/?probe=c6d123b5ec) | Jun 16, 2022 |
| Micro Elec... | MG-VCP17I-3070              | [d28d429121](https://linux-hardware.org/?probe=d28d429121) | Jun 16, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | [7d8683dfac](https://linux-hardware.org/?probe=7d8683dfac) | Jun 16, 2022 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | [f83da947b8](https://linux-hardware.org/?probe=f83da947b8) | Jun 16, 2022 |
| Itautec       | Infoway w7430               | [776d876064](https://linux-hardware.org/?probe=776d876064) | Jun 16, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [388285efe8](https://linux-hardware.org/?probe=388285efe8) | Jun 15, 2022 |
| HP            | Laptop 17-cp0xxx            | [6b73227c17](https://linux-hardware.org/?probe=6b73227c17) | Jun 15, 2022 |
| Acer          | Predator PH315-53           | [155af690bd](https://linux-hardware.org/?probe=155af690bd) | Jun 15, 2022 |
| Dell          | XPS 15 9520                 | [bdd4ec2ef9](https://linux-hardware.org/?probe=bdd4ec2ef9) | Jun 15, 2022 |
| Dell          | XPS 15 9520                 | [03140c6f93](https://linux-hardware.org/?probe=03140c6f93) | Jun 15, 2022 |
| HP            | Laptop 17-cp0xxx            | [6f25a1e394](https://linux-hardware.org/?probe=6f25a1e394) | Jun 15, 2022 |
| Dell          | Inspiron 7472               | [788b7856ca](https://linux-hardware.org/?probe=788b7856ca) | Jun 15, 2022 |
| Timi          | Redmi Book Pro 15 2022      | [76fd9cba2e](https://linux-hardware.org/?probe=76fd9cba2e) | Jun 15, 2022 |
| Dell          | Precision 3551              | [3499839fd0](https://linux-hardware.org/?probe=3499839fd0) | Jun 14, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [b6f26fecef](https://linux-hardware.org/?probe=b6f26fecef) | Jun 14, 2022 |
| HP            | Notebook                    | [390f55db2e](https://linux-hardware.org/?probe=390f55db2e) | Jun 14, 2022 |
| HP            | OMEN by Laptop 15-dc1xxx    | [17077cf1d8](https://linux-hardware.org/?probe=17077cf1d8) | Jun 14, 2022 |
| Dell          | XPS 15 9510                 | [61104911ed](https://linux-hardware.org/?probe=61104911ed) | Jun 14, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDC... | [b10e894950](https://linux-hardware.org/?probe=b10e894950) | Jun 14, 2022 |
| Timi          | Redmi Book Pro 15 2022      | [b3259c0af4](https://linux-hardware.org/?probe=b3259c0af4) | Jun 14, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [35cbb5ff8b](https://linux-hardware.org/?probe=35cbb5ff8b) | Jun 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [e2385e525c](https://linux-hardware.org/?probe=e2385e525c) | Jun 14, 2022 |
| Lenovo        | ThinkBook 16 G4+ IAP 21C... | [605cab3041](https://linux-hardware.org/?probe=605cab3041) | Jun 14, 2022 |
| HP            | Pavilion Notebook           | [cf08ff4333](https://linux-hardware.org/?probe=cf08ff4333) | Jun 14, 2022 |
| HP            | Pavilion Notebook           | [4b4bd76de7](https://linux-hardware.org/?probe=4b4bd76de7) | Jun 14, 2022 |
| ASUSTek       | Zenbook UX5401ZA_UX5401Z... | [2b87adfa9f](https://linux-hardware.org/?probe=2b87adfa9f) | Jun 13, 2022 |
| HP            | Pavilion g6                 | [20bd05081e](https://linux-hardware.org/?probe=20bd05081e) | Jun 13, 2022 |
| HP            | Pavilion g6                 | [d147676849](https://linux-hardware.org/?probe=d147676849) | Jun 13, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | [b8b4869fa1](https://linux-hardware.org/?probe=b8b4869fa1) | Jun 13, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [221099208b](https://linux-hardware.org/?probe=221099208b) | Jun 13, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [0a985a9f53](https://linux-hardware.org/?probe=0a985a9f53) | Jun 13, 2022 |
| Lenovo        | Y50-70 20378                | [6153f90073](https://linux-hardware.org/?probe=6153f90073) | Jun 13, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [17d6efccfa](https://linux-hardware.org/?probe=17d6efccfa) | Jun 12, 2022 |
| Acer          | Aspire E5-573G              | [967ef390e0](https://linux-hardware.org/?probe=967ef390e0) | Jun 12, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | [dbe7d6b6bf](https://linux-hardware.org/?probe=dbe7d6b6bf) | Jun 12, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | [554002fe47](https://linux-hardware.org/?probe=554002fe47) | Jun 12, 2022 |
| HP            | Laptop 15s-fq3xxx           | [6acd8f6081](https://linux-hardware.org/?probe=6acd8f6081) | Jun 12, 2022 |
| Acer          | Aspire R7-371T              | [b791797ef3](https://linux-hardware.org/?probe=b791797ef3) | Jun 12, 2022 |
| Acer          | Aspire R7-371T              | [d573a80e21](https://linux-hardware.org/?probe=d573a80e21) | Jun 12, 2022 |
| Apple         | MacBookPro6,2               | [a677849f96](https://linux-hardware.org/?probe=a677849f96) | Jun 12, 2022 |
| ASUSTek       | X750JN                      | [6748bf6f1e](https://linux-hardware.org/?probe=6748bf6f1e) | Jun 11, 2022 |
| HP            | ProBook 650 G1              | [8f468e1fc9](https://linux-hardware.org/?probe=8f468e1fc9) | Jun 11, 2022 |
| Lenovo        | ThinkPad T420 4180BE1       | [a3c2ffc8e0](https://linux-hardware.org/?probe=a3c2ffc8e0) | Jun 11, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [3c8959c8dc](https://linux-hardware.org/?probe=3c8959c8dc) | Jun 11, 2022 |
| HP            | Laptop 17-bs1xx             | [aa23e1d53e](https://linux-hardware.org/?probe=aa23e1d53e) | Jun 11, 2022 |
| HUAWEI        | WRT-WX9                     | [13dcf888fe](https://linux-hardware.org/?probe=13dcf888fe) | Jun 10, 2022 |
| Acer          | Swift SF114-32              | [63f76026b7](https://linux-hardware.org/?probe=63f76026b7) | Jun 10, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [1967d32245](https://linux-hardware.org/?probe=1967d32245) | Jun 10, 2022 |
| Dell          | XPS 15 9570                 | [f37ad0aba6](https://linux-hardware.org/?probe=f37ad0aba6) | Jun 10, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [14e32dc3cb](https://linux-hardware.org/?probe=14e32dc3cb) | Jun 10, 2022 |
| HP            | Laptop 14s-fq0xxx           | [0a77925edb](https://linux-hardware.org/?probe=0a77925edb) | Jun 10, 2022 |
| Lenovo        | ThinkPad P50 20EQS3B30R     | [c97b8918a0](https://linux-hardware.org/?probe=c97b8918a0) | Jun 10, 2022 |
| HP            | ZBook 15                    | [540fada7d4](https://linux-hardware.org/?probe=540fada7d4) | Jun 09, 2022 |
| HP            | ZBook 15                    | [5e3ff70430](https://linux-hardware.org/?probe=5e3ff70430) | Jun 09, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [158a18f6d1](https://linux-hardware.org/?probe=158a18f6d1) | Jun 09, 2022 |
| Lenovo        | ThinkPad E480 20KNS0E200    | [321a2df7db](https://linux-hardware.org/?probe=321a2df7db) | Jun 09, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | [e934effe87](https://linux-hardware.org/?probe=e934effe87) | Jun 09, 2022 |
| HP            | ENVY dv7                    | [f7401e6566](https://linux-hardware.org/?probe=f7401e6566) | Jun 09, 2022 |
| Toshiba       | Satellite C50-A             | [1f5918622d](https://linux-hardware.org/?probe=1f5918622d) | Jun 08, 2022 |
| Toshiba       | Satellite C50-A             | [20a629adc2](https://linux-hardware.org/?probe=20a629adc2) | Jun 08, 2022 |
| HUAWEI        | KLVL-WXX9                   | [4ce4c3ad20](https://linux-hardware.org/?probe=4ce4c3ad20) | Jun 08, 2022 |
| Lenovo        | ThinkPad T400 6475AJ1       | [3ef905b44a](https://linux-hardware.org/?probe=3ef905b44a) | Jun 08, 2022 |
| VIT           | M2420                       | [8152d4c61b](https://linux-hardware.org/?probe=8152d4c61b) | Jun 08, 2022 |
| VIT           | M2420                       | [d09de8cbd7](https://linux-hardware.org/?probe=d09de8cbd7) | Jun 07, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B9400CEA... | [73823d7212](https://linux-hardware.org/?probe=73823d7212) | Jun 07, 2022 |
| Lenovo        | IdeaPad S540-15IWL          | [1a79b3a2ab](https://linux-hardware.org/?probe=1a79b3a2ab) | Jun 07, 2022 |
| HP            | 250 G7 Notebook PC          | [c45207e9ed](https://linux-hardware.org/?probe=c45207e9ed) | Jun 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [14a3f31e7d](https://linux-hardware.org/?probe=14a3f31e7d) | Jun 07, 2022 |
| HP            | 250 G7 Notebook PC          | [fa7cd44609](https://linux-hardware.org/?probe=fa7cd44609) | Jun 07, 2022 |
| Apple         | MacBook4,1                  | [c8e7bd54a3](https://linux-hardware.org/?probe=c8e7bd54a3) | Jun 07, 2022 |
| Dell          | Inspiron 3542               | [8fcf9a9913](https://linux-hardware.org/?probe=8fcf9a9913) | Jun 07, 2022 |
| HP            | Laptop 15-dy0xxx            | [e2a9ba60e2](https://linux-hardware.org/?probe=e2a9ba60e2) | Jun 07, 2022 |
| Unknown       | Unknown                     | [6c562bbebb](https://linux-hardware.org/?probe=6c562bbebb) | Jun 06, 2022 |
| Apple         | MacBookPro14,3              | [0d56225d08](https://linux-hardware.org/?probe=0d56225d08) | Jun 06, 2022 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [5f55cd1869](https://linux-hardware.org/?probe=5f55cd1869) | Jun 06, 2022 |
| HP            | EliteBook 8740w             | [178b330cc1](https://linux-hardware.org/?probe=178b330cc1) | Jun 06, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [bec76e5f74](https://linux-hardware.org/?probe=bec76e5f74) | Jun 06, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [0732a60437](https://linux-hardware.org/?probe=0732a60437) | Jun 06, 2022 |
| HP            | 250 G5                      | [1cbf1a1c53](https://linux-hardware.org/?probe=1cbf1a1c53) | Jun 06, 2022 |
| Lenovo        | 81WE                        | [31217f3c4a](https://linux-hardware.org/?probe=31217f3c4a) | Jun 06, 2022 |
| Lenovo        | G580 2689PWG                | [e7e658bc95](https://linux-hardware.org/?probe=e7e658bc95) | Jun 06, 2022 |
| Dell          | XPS 13 9370                 | [568a879289](https://linux-hardware.org/?probe=568a879289) | Jun 06, 2022 |
| Lenovo        | G580 2689PWG                | [e51b9086bd](https://linux-hardware.org/?probe=e51b9086bd) | Jun 06, 2022 |
| HP            | 250 G5                      | [7cbd2a6796](https://linux-hardware.org/?probe=7cbd2a6796) | Jun 06, 2022 |
| HP            | 250 G5                      | [6668b9ad94](https://linux-hardware.org/?probe=6668b9ad94) | Jun 06, 2022 |
| Apple         | MacBookAir5,1               | [f9ac66019f](https://linux-hardware.org/?probe=f9ac66019f) | Jun 06, 2022 |
| Apple         | MacBookPro14,3              | [8fbfe75f53](https://linux-hardware.org/?probe=8fbfe75f53) | Jun 06, 2022 |
| Lenovo        | ThinkPad T420 4177CTO       | [fe28db8adc](https://linux-hardware.org/?probe=fe28db8adc) | Jun 06, 2022 |
| HP            | EliteBook 2560p             | [9cd1c3d383](https://linux-hardware.org/?probe=9cd1c3d383) | Jun 05, 2022 |
| Apple         | MacBookPro10,1              | [9e49a2cbac](https://linux-hardware.org/?probe=9e49a2cbac) | Jun 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [7084316e82](https://linux-hardware.org/?probe=7084316e82) | Jun 05, 2022 |
| Acer          | Aspire R3-131T              | [f1becc237d](https://linux-hardware.org/?probe=f1becc237d) | Jun 05, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [155a8dd1a5](https://linux-hardware.org/?probe=155a8dd1a5) | Jun 05, 2022 |
| Dell          | Latitude 7490               | [feb1fc06d4](https://linux-hardware.org/?probe=feb1fc06d4) | Jun 05, 2022 |
| ASUSTek       | X541NA                      | [0c40d3f3d2](https://linux-hardware.org/?probe=0c40d3f3d2) | Jun 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [84d72b2b06](https://linux-hardware.org/?probe=84d72b2b06) | Jun 05, 2022 |
| HP            | ProBook 650 G1              | [be6fcc008b](https://linux-hardware.org/?probe=be6fcc008b) | Jun 04, 2022 |
| Acer          | Aspire E5-573G              | [31de2e546e](https://linux-hardware.org/?probe=31de2e546e) | Jun 04, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [41862e04b8](https://linux-hardware.org/?probe=41862e04b8) | Jun 03, 2022 |
| Dell          | Precision 5540              | [641aabe445](https://linux-hardware.org/?probe=641aabe445) | Jun 03, 2022 |
| Notebook      | NL40_50CU                   | [df0357703d](https://linux-hardware.org/?probe=df0357703d) | Jun 03, 2022 |
| Dell          | XPS 15 9560                 | [38de8409ef](https://linux-hardware.org/?probe=38de8409ef) | Jun 02, 2022 |
| Framework     | Laptop                      | [625917cfcd](https://linux-hardware.org/?probe=625917cfcd) | Jun 02, 2022 |
| HP            | Laptop 15s-eq2xxx           | [3aa4194ab3](https://linux-hardware.org/?probe=3aa4194ab3) | Jun 02, 2022 |
| Lenovo        | IdeaPad L340-17IWL 81M0     | [b5bb3c0725](https://linux-hardware.org/?probe=b5bb3c0725) | Jun 02, 2022 |
| ASUSTek       | N82JV                       | [623436f0c3](https://linux-hardware.org/?probe=623436f0c3) | Jun 02, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [ff63d0c19b](https://linux-hardware.org/?probe=ff63d0c19b) | Jun 02, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [978a80c358](https://linux-hardware.org/?probe=978a80c358) | Jun 02, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [d81154a7e1](https://linux-hardware.org/?probe=d81154a7e1) | Jun 02, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B3302CEA... | [ad66932f23](https://linux-hardware.org/?probe=ad66932f23) | Jun 02, 2022 |
| Dell          | Inspiron 3531               | [c2d9f4b84b](https://linux-hardware.org/?probe=c2d9f4b84b) | Jun 02, 2022 |
| HUAWEI        | MACH-WX9                    | [70ad46aa8e](https://linux-hardware.org/?probe=70ad46aa8e) | Jun 01, 2022 |
| Acer          | Swift SFX14-41G             | [38fb3963cd](https://linux-hardware.org/?probe=38fb3963cd) | Jun 01, 2022 |
| Acer          | Swift SFX14-41G             | [6f5f1c9373](https://linux-hardware.org/?probe=6f5f1c9373) | Jun 01, 2022 |
| Lenovo        | Edge 15 80K9                | [5c8bb97759](https://linux-hardware.org/?probe=5c8bb97759) | Jun 01, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [ae39e96b1a](https://linux-hardware.org/?probe=ae39e96b1a) | Jun 01, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [0f84f94a6a](https://linux-hardware.org/?probe=0f84f94a6a) | Jun 01, 2022 |
| HP            | EliteBook 2560p             | [af6a91d3c7](https://linux-hardware.org/?probe=af6a91d3c7) | Jun 01, 2022 |
| Dell          | Inspiron 5415               | [942b343fff](https://linux-hardware.org/?probe=942b343fff) | Jun 01, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [1e6ab0f183](https://linux-hardware.org/?probe=1e6ab0f183) | May 31, 2022 |
| ASUSTek       | X541NA                      | [3d32754542](https://linux-hardware.org/?probe=3d32754542) | May 31, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [dc3ee2e520](https://linux-hardware.org/?probe=dc3ee2e520) | May 31, 2022 |
| Lenovo        | Edge 15 80K9                | [9bbdfc95bb](https://linux-hardware.org/?probe=9bbdfc95bb) | May 31, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [956299505f](https://linux-hardware.org/?probe=956299505f) | May 31, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [9b53c4df9d](https://linux-hardware.org/?probe=9b53c4df9d) | May 31, 2022 |
| ASUSTek       | N501VW                      | [2f8215fb0a](https://linux-hardware.org/?probe=2f8215fb0a) | May 31, 2022 |
| HP            | EliteBook 840 G3            | [92acbd4c3f](https://linux-hardware.org/?probe=92acbd4c3f) | May 31, 2022 |
| Apple         | MacBookPro8,3               | [38f4cc4c5a](https://linux-hardware.org/?probe=38f4cc4c5a) | May 31, 2022 |
| Dell          | XPS 15 9520                 | [4d4c32223e](https://linux-hardware.org/?probe=4d4c32223e) | May 31, 2022 |
| Dell          | Inspiron 5547               | [066f6369b2](https://linux-hardware.org/?probe=066f6369b2) | May 31, 2022 |
| HP            | 255 G1                      | [86f7198193](https://linux-hardware.org/?probe=86f7198193) | May 31, 2022 |
| Lenovo        | ThinkPad E595 20NF001PTX    | [cf41cc78f7](https://linux-hardware.org/?probe=cf41cc78f7) | May 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [5a813419eb](https://linux-hardware.org/?probe=5a813419eb) | May 30, 2022 |
| Lenovo        | Edge 15 80K9                | [586a31368f](https://linux-hardware.org/?probe=586a31368f) | May 30, 2022 |
| Google        | Droid                       | [35e3edeab3](https://linux-hardware.org/?probe=35e3edeab3) | May 30, 2022 |
| Framework     | Laptop                      | [f1c2a80b70](https://linux-hardware.org/?probe=f1c2a80b70) | May 30, 2022 |
| Lenovo        | ThinkPad X240 20AM0040BR    | [e0ff07b590](https://linux-hardware.org/?probe=e0ff07b590) | May 30, 2022 |
| IT Channel... | PA70Hx                      | [091ad22c2d](https://linux-hardware.org/?probe=091ad22c2d) | May 30, 2022 |
| ASUSTek       | ZenBook UX325SA_UM325SA     | [378e6ca9c6](https://linux-hardware.org/?probe=378e6ca9c6) | May 30, 2022 |
| Dell          | XPS 15 9520                 | [eee1a317b6](https://linux-hardware.org/?probe=eee1a317b6) | May 30, 2022 |
| MSI           | GE60 2PE                    | [1e15d749ee](https://linux-hardware.org/?probe=1e15d749ee) | May 30, 2022 |
| ASUSTek       | X541NA                      | [c1fd0c2d4f](https://linux-hardware.org/?probe=c1fd0c2d4f) | May 30, 2022 |
| MSI           | GE60 2PE                    | [b52762040d](https://linux-hardware.org/?probe=b52762040d) | May 30, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [15fb1b0353](https://linux-hardware.org/?probe=15fb1b0353) | May 30, 2022 |
| Dell          | Inspiron 7472               | [7d8d96d851](https://linux-hardware.org/?probe=7d8d96d851) | May 29, 2022 |
| ASUSTek       | UX51VZA                     | [c7c6e27cae](https://linux-hardware.org/?probe=c7c6e27cae) | May 29, 2022 |
| Dell          | Latitude E7470              | [159516aefb](https://linux-hardware.org/?probe=159516aefb) | May 29, 2022 |
| Acer          | Aspire E5-573G              | [bd9b967f9b](https://linux-hardware.org/?probe=bd9b967f9b) | May 29, 2022 |
| Dell          | XPS 15 9520                 | [75d345243e](https://linux-hardware.org/?probe=75d345243e) | May 29, 2022 |
| Notebook      | P65_P67SG                   | [a2aecd5cd3](https://linux-hardware.org/?probe=a2aecd5cd3) | May 29, 2022 |
| MSI           | GE60 2PE                    | [84d5af4ebe](https://linux-hardware.org/?probe=84d5af4ebe) | May 29, 2022 |
| MSI           | GE60 2PE                    | [c8d325a744](https://linux-hardware.org/?probe=c8d325a744) | May 29, 2022 |
| HP            | Pavilion 17                 | [077be5d10b](https://linux-hardware.org/?probe=077be5d10b) | May 28, 2022 |
| Dell          | Precision 7710              | [befe390051](https://linux-hardware.org/?probe=befe390051) | May 28, 2022 |
| Dell          | Vostro 5515                 | [ae8649e10b](https://linux-hardware.org/?probe=ae8649e10b) | May 28, 2022 |
| Lenovo        | Y70-70 Touch 80DU           | [4c4689f4b7](https://linux-hardware.org/?probe=4c4689f4b7) | May 28, 2022 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | [df2d7a274d](https://linux-hardware.org/?probe=df2d7a274d) | May 28, 2022 |
| Lenovo        | ThinkPad P52 20MAS3X200     | [da2a67f904](https://linux-hardware.org/?probe=da2a67f904) | May 28, 2022 |
| Lenovo        | Yoga 300-11IBY 80M0         | [8d120a2350](https://linux-hardware.org/?probe=8d120a2350) | May 28, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [af42d8d0b4](https://linux-hardware.org/?probe=af42d8d0b4) | May 27, 2022 |
| Timi          | A35S                        | [8a1bee3210](https://linux-hardware.org/?probe=8a1bee3210) | May 27, 2022 |
| Dell          | XPS 15 9570                 | [93d1ebbb72](https://linux-hardware.org/?probe=93d1ebbb72) | May 27, 2022 |
| Login Info... | LOG-QAL30                   | [5643c9fb9b](https://linux-hardware.org/?probe=5643c9fb9b) | May 27, 2022 |
| Login Info... | LOG-QAL30                   | [644f3a8dbc](https://linux-hardware.org/?probe=644f3a8dbc) | May 27, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [983144763a](https://linux-hardware.org/?probe=983144763a) | May 27, 2022 |
| Lenovo        | 14w 81MQS02H00              | [e31087bfa9](https://linux-hardware.org/?probe=e31087bfa9) | May 27, 2022 |
| Dell          | Inspiron 7460               | [3171915433](https://linux-hardware.org/?probe=3171915433) | May 27, 2022 |
| Sony          | VPCEE3S1E                   | [f3c7988996](https://linux-hardware.org/?probe=f3c7988996) | May 27, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS3... | [88aabea122](https://linux-hardware.org/?probe=88aabea122) | May 27, 2022 |
| ASUSTek       | UX51VZA                     | [5507c9109e](https://linux-hardware.org/?probe=5507c9109e) | May 27, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [9b4287fa8b](https://linux-hardware.org/?probe=9b4287fa8b) | May 26, 2022 |
| HP            | Pavilion TS 14              | [b7b3d504e2](https://linux-hardware.org/?probe=b7b3d504e2) | May 26, 2022 |
| Dell          | Inspiron 5502               | [90ee31b219](https://linux-hardware.org/?probe=90ee31b219) | May 26, 2022 |
| Dell          | XPS 13 7390                 | [4aa126f1e7](https://linux-hardware.org/?probe=4aa126f1e7) | May 26, 2022 |
| Dell          | Inspiron 3543               | [bf6cb72634](https://linux-hardware.org/?probe=bf6cb72634) | May 26, 2022 |
| HUAWEI        | HN-WX9X                     | [ebb7ce2605](https://linux-hardware.org/?probe=ebb7ce2605) | May 26, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | [ad9da27671](https://linux-hardware.org/?probe=ad9da27671) | May 26, 2022 |
| Samsung       | 550XDA                      | [807781d70e](https://linux-hardware.org/?probe=807781d70e) | May 26, 2022 |
| Acer          | Aspire E5-573G              | [6f5b6d8d03](https://linux-hardware.org/?probe=6f5b6d8d03) | May 25, 2022 |
| ASUSTek       | GL502VMK                    | [dfca615a89](https://linux-hardware.org/?probe=dfca615a89) | May 25, 2022 |
| HP            | Notebook                    | [05e785c8c2](https://linux-hardware.org/?probe=05e785c8c2) | May 25, 2022 |
| HP            | Notebook                    | [17ca21b3a4](https://linux-hardware.org/?probe=17ca21b3a4) | May 25, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [dcbaf5defc](https://linux-hardware.org/?probe=dcbaf5defc) | May 25, 2022 |
| HP            | Unknown                     | [c6b346ecc6](https://linux-hardware.org/?probe=c6b346ecc6) | May 25, 2022 |
| Lenovo        | ThinkPad W540 20BHS04B00    | [376f43287f](https://linux-hardware.org/?probe=376f43287f) | May 25, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RS... | [940a448ea6](https://linux-hardware.org/?probe=940a448ea6) | May 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [93c67e62e7](https://linux-hardware.org/?probe=93c67e62e7) | May 24, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [00baf8a2ff](https://linux-hardware.org/?probe=00baf8a2ff) | May 24, 2022 |
| ROCK Pi       | Unknown                     | [aa891c0178](https://linux-hardware.org/?probe=aa891c0178) | May 24, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [24c2ad0798](https://linux-hardware.org/?probe=24c2ad0798) | May 24, 2022 |
| Dell          | Precision 3561              | [71657d24c1](https://linux-hardware.org/?probe=71657d24c1) | May 24, 2022 |
| Dell          | Precision 3561              | [385a286d0d](https://linux-hardware.org/?probe=385a286d0d) | May 24, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [eccd990241](https://linux-hardware.org/?probe=eccd990241) | May 24, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [1b061ef293](https://linux-hardware.org/?probe=1b061ef293) | May 24, 2022 |
| Lenovo        | ThinkPad W540 20BHS04B00    | [8d62205131](https://linux-hardware.org/?probe=8d62205131) | May 23, 2022 |
| Lenovo        | ThinkPad T480s 20L8S1RS0... | [174f6e2270](https://linux-hardware.org/?probe=174f6e2270) | May 23, 2022 |
| ASUSTek       | X550CL                      | [49ebd9e68d](https://linux-hardware.org/?probe=49ebd9e68d) | May 23, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [377330c2b5](https://linux-hardware.org/?probe=377330c2b5) | May 23, 2022 |
| Dell          | Vostro 5490                 | [413a708e81](https://linux-hardware.org/?probe=413a708e81) | May 23, 2022 |
| Gigabyte      | P34V5                       | [6fa844b91e](https://linux-hardware.org/?probe=6fa844b91e) | May 23, 2022 |
| Gigabyte      | P34V5                       | [3ad8e4b239](https://linux-hardware.org/?probe=3ad8e4b239) | May 23, 2022 |
| Dell          | XPS 13 9310                 | [a76a3417d7](https://linux-hardware.org/?probe=a76a3417d7) | May 23, 2022 |
| Toshiba       | Unknown                     | [56ac954440](https://linux-hardware.org/?probe=56ac954440) | May 23, 2022 |
| Lenovo        | ThinkPad X230 2325AC7       | [bf82ad1cc3](https://linux-hardware.org/?probe=bf82ad1cc3) | May 23, 2022 |
| Sony          | VPCSA2Z9R                   | [5697622de7](https://linux-hardware.org/?probe=5697622de7) | May 22, 2022 |
| Lenovo        | ThinkPad X270 20HMS1QT0E    | [f17079bdce](https://linux-hardware.org/?probe=f17079bdce) | May 22, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [bdb9536c9c](https://linux-hardware.org/?probe=bdb9536c9c) | May 22, 2022 |
| Acer          | Swift SF514-52T             | [d49880e4c2](https://linux-hardware.org/?probe=d49880e4c2) | May 22, 2022 |
| Acer          | Swift SF514-52T             | [40d5ca6bab](https://linux-hardware.org/?probe=40d5ca6bab) | May 22, 2022 |
| HP            | 15-dc1018ur                 | [aceb1a1011](https://linux-hardware.org/?probe=aceb1a1011) | May 22, 2022 |
| Dell          | Inspiron 5567               | [afca2e1045](https://linux-hardware.org/?probe=afca2e1045) | May 22, 2022 |
| Lenovo        | ThinkPad W520 42763JF       | [2b87bae835](https://linux-hardware.org/?probe=2b87bae835) | May 22, 2022 |
| HP            | ProBook 470 G5              | [4be19d46e1](https://linux-hardware.org/?probe=4be19d46e1) | May 21, 2022 |
| Lenovo        | Legion 7 15IMH05 81YT       | [a44f38fd50](https://linux-hardware.org/?probe=a44f38fd50) | May 21, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [1c2288918d](https://linux-hardware.org/?probe=1c2288918d) | May 21, 2022 |
| HP            | Unknown                     | [2277c14d4d](https://linux-hardware.org/?probe=2277c14d4d) | May 21, 2022 |
| Dell          | XPS 13 9310                 | [06943bb7f1](https://linux-hardware.org/?probe=06943bb7f1) | May 21, 2022 |
| Acer          | Swift SF314-54              | [478550abf1](https://linux-hardware.org/?probe=478550abf1) | May 21, 2022 |
| Dell          | Latitude 5490               | [450756ee49](https://linux-hardware.org/?probe=450756ee49) | May 21, 2022 |
| HP            | Laptop 15s-eq1xxx           | [702e495c23](https://linux-hardware.org/?probe=702e495c23) | May 21, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [cc0b92bd45](https://linux-hardware.org/?probe=cc0b92bd45) | May 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [d5b9f1fd4a](https://linux-hardware.org/?probe=d5b9f1fd4a) | May 20, 2022 |
| HP            | Pavilion g4                 | [b29455a037](https://linux-hardware.org/?probe=b29455a037) | May 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [567c91351f](https://linux-hardware.org/?probe=567c91351f) | May 20, 2022 |
| HP            | Pavilion g4                 | [001f7d91d2](https://linux-hardware.org/?probe=001f7d91d2) | May 20, 2022 |
| Acer          | Aspire 8940G                | [f6f8622b30](https://linux-hardware.org/?probe=f6f8622b30) | May 20, 2022 |
| Google        | Glimmer                     | [78c39ceda9](https://linux-hardware.org/?probe=78c39ceda9) | May 20, 2022 |
| Dell          | Inspiron 5459               | [ea99252046](https://linux-hardware.org/?probe=ea99252046) | May 20, 2022 |
| Samsung       | 550XDA                      | [1f77e9f8f6](https://linux-hardware.org/?probe=1f77e9f8f6) | May 19, 2022 |
| Samsung       | 550XDA                      | [8c31783747](https://linux-hardware.org/?probe=8c31783747) | May 19, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [e8df231af7](https://linux-hardware.org/?probe=e8df231af7) | May 19, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [711e483bb9](https://linux-hardware.org/?probe=711e483bb9) | May 19, 2022 |
| Lenovo        | IdeaPad Creator 5 15IMH0... | [59d945a9b3](https://linux-hardware.org/?probe=59d945a9b3) | May 19, 2022 |
| eMachines     | E525                        | [2c397d4229](https://linux-hardware.org/?probe=2c397d4229) | May 19, 2022 |
| eMachines     | E525                        | [7a1e439150](https://linux-hardware.org/?probe=7a1e439150) | May 19, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [0e0fc0905a](https://linux-hardware.org/?probe=0e0fc0905a) | May 19, 2022 |
| SKIKK         | GREEN 4                     | [f58c4904f7](https://linux-hardware.org/?probe=f58c4904f7) | May 19, 2022 |
| Toshiba       | Satellite U940              | [249374be01](https://linux-hardware.org/?probe=249374be01) | May 19, 2022 |
| Apple         | MacBookPro8,1               | [94d2bd3233](https://linux-hardware.org/?probe=94d2bd3233) | May 19, 2022 |
| Lenovo        | ThinkPad P52 20MAS3X200     | [7f0fc0c72e](https://linux-hardware.org/?probe=7f0fc0c72e) | May 19, 2022 |
| Lenovo        | ThinkPad P50 20EQS1DD00     | [819420bd66](https://linux-hardware.org/?probe=819420bd66) | May 19, 2022 |
| Lenovo        | ThinkPad P50 20EQS1DD00     | [479ab8b5d7](https://linux-hardware.org/?probe=479ab8b5d7) | May 19, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [592a32a1af](https://linux-hardware.org/?probe=592a32a1af) | May 18, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [e83ddc569f](https://linux-hardware.org/?probe=e83ddc569f) | May 18, 2022 |
| Dell          | XPS 13 7390                 | [98752f9fb4](https://linux-hardware.org/?probe=98752f9fb4) | May 18, 2022 |
| Dell          | Latitude E6420              | [0f06571934](https://linux-hardware.org/?probe=0f06571934) | May 18, 2022 |
| ASUSTek       | X556URK                     | [b217fd2c65](https://linux-hardware.org/?probe=b217fd2c65) | May 18, 2022 |
| Apple         | MacBookAir7,2               | [a46fea4edb](https://linux-hardware.org/?probe=a46fea4edb) | May 18, 2022 |
| Samsung       | 270E5G/270E5U               | [8d8783e43f](https://linux-hardware.org/?probe=8d8783e43f) | May 18, 2022 |
| Samsung       | 270E5G/270E5U               | [6e01c5c9f5](https://linux-hardware.org/?probe=6e01c5c9f5) | May 18, 2022 |
| Lenovo        | IdeaPad Y500 20193          | [a3931c5e60](https://linux-hardware.org/?probe=a3931c5e60) | May 17, 2022 |
| HP            | Laptop 15s-eq2xxx           | [9e7bf270db](https://linux-hardware.org/?probe=9e7bf270db) | May 17, 2022 |
| Dell          | Latitude E6230              | [1afeba4362](https://linux-hardware.org/?probe=1afeba4362) | May 17, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [f86ea538c8](https://linux-hardware.org/?probe=f86ea538c8) | May 17, 2022 |
| Dell          | Latitude 5520               | [320ed1c4fc](https://linux-hardware.org/?probe=320ed1c4fc) | May 17, 2022 |
| Dell          | Latitude 5520               | [18823f33fb](https://linux-hardware.org/?probe=18823f33fb) | May 17, 2022 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [331099a3da](https://linux-hardware.org/?probe=331099a3da) | May 17, 2022 |
| Lenovo        | IdeaPad Slim 7 14ITL05 8... | [2179a16a87](https://linux-hardware.org/?probe=2179a16a87) | May 17, 2022 |
| Notebook      | N8xEJEK                     | [5c2c66e8f5](https://linux-hardware.org/?probe=5c2c66e8f5) | May 17, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [61c1716210](https://linux-hardware.org/?probe=61c1716210) | May 16, 2022 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [e99a8117ba](https://linux-hardware.org/?probe=e99a8117ba) | May 16, 2022 |
| Dell          | XPS 13 9350                 | [cf7f597752](https://linux-hardware.org/?probe=cf7f597752) | May 16, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [06afc33451](https://linux-hardware.org/?probe=06afc33451) | May 16, 2022 |
| Lenovo        | ThinkPad T440p 20AW000KU... | [66fc91a0d0](https://linux-hardware.org/?probe=66fc91a0d0) | May 16, 2022 |
| Dell          | XPS 15 7590                 | [7f7463682a](https://linux-hardware.org/?probe=7f7463682a) | May 16, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [1661f9e71d](https://linux-hardware.org/?probe=1661f9e71d) | May 16, 2022 |
| Acer          | Nitro AN515-45              | [2dac9974af](https://linux-hardware.org/?probe=2dac9974af) | May 16, 2022 |
| Lenovo        | ThinkPad T440 20B7A1P700    | [ee54db9f9e](https://linux-hardware.org/?probe=ee54db9f9e) | May 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [a15788c695](https://linux-hardware.org/?probe=a15788c695) | May 15, 2022 |
| HP            | 250 G7 Notebook PC          | [4e824e7eac](https://linux-hardware.org/?probe=4e824e7eac) | May 15, 2022 |
| Positivo      | H14BU08                     | [ba7d402358](https://linux-hardware.org/?probe=ba7d402358) | May 15, 2022 |
| Lenovo        | V14-IIL 82C4                | [b95acee640](https://linux-hardware.org/?probe=b95acee640) | May 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [a442279a0b](https://linux-hardware.org/?probe=a442279a0b) | May 15, 2022 |
| Acer          | Swift SF515-51T             | [3e3380c801](https://linux-hardware.org/?probe=3e3380c801) | May 15, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [6c635e0f3d](https://linux-hardware.org/?probe=6c635e0f3d) | May 15, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [88c0d2c252](https://linux-hardware.org/?probe=88c0d2c252) | May 15, 2022 |
| Acer          | AO532h                      | [6055013560](https://linux-hardware.org/?probe=6055013560) | May 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [6adb7e22c5](https://linux-hardware.org/?probe=6adb7e22c5) | May 14, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [8c71a3bd1b](https://linux-hardware.org/?probe=8c71a3bd1b) | May 13, 2022 |
| HP            | EliteBook 8470p             | [2c8d1eec1e](https://linux-hardware.org/?probe=2c8d1eec1e) | May 13, 2022 |
| TUXEDO        | Pulse 14 Gen1               | [31d9027f23](https://linux-hardware.org/?probe=31d9027f23) | May 13, 2022 |
| HP            | EliteBook 8470p             | [074043a5ca](https://linux-hardware.org/?probe=074043a5ca) | May 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [ffbf67b890](https://linux-hardware.org/?probe=ffbf67b890) | May 12, 2022 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [deb6fa57ef](https://linux-hardware.org/?probe=deb6fa57ef) | May 12, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [7aaffeda48](https://linux-hardware.org/?probe=7aaffeda48) | May 12, 2022 |
| Lenovo        | ThinkPad P51 20HJS02H00     | [fc7562c140](https://linux-hardware.org/?probe=fc7562c140) | May 12, 2022 |
| Lenovo        | ThinkPad P51 20HJS02H00     | [810fda94b1](https://linux-hardware.org/?probe=810fda94b1) | May 12, 2022 |
| Dell          | Latitude 5420               | [ac04d4cb5b](https://linux-hardware.org/?probe=ac04d4cb5b) | May 12, 2022 |
| ICL           | Unknown                     | [cfb2a7c82f](https://linux-hardware.org/?probe=cfb2a7c82f) | May 12, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [9baa4a9f57](https://linux-hardware.org/?probe=9baa4a9f57) | May 12, 2022 |
| Dell          | XPS 15 9500                 | [da0e4e32b4](https://linux-hardware.org/?probe=da0e4e32b4) | May 12, 2022 |
| Lenovo        | IdeaPad S540-15IWL          | [bbf4ef2a08](https://linux-hardware.org/?probe=bbf4ef2a08) | May 11, 2022 |
| Lenovo        | ThinkPad X395 20NL0007US    | [aea9571086](https://linux-hardware.org/?probe=aea9571086) | May 11, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [b0951956fa](https://linux-hardware.org/?probe=b0951956fa) | May 11, 2022 |
| Lenovo        | ThinkPad T480 20L6S5M40M    | [f2213829f0](https://linux-hardware.org/?probe=f2213829f0) | May 11, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [607c0a2833](https://linux-hardware.org/?probe=607c0a2833) | May 11, 2022 |
| Lenovo        | ThinkPad E570 20H5CTO1WW    | [a22c347eaf](https://linux-hardware.org/?probe=a22c347eaf) | May 11, 2022 |
| Lenovo        | ThinkPad T590 20N5S2NC0N    | [61327f1e21](https://linux-hardware.org/?probe=61327f1e21) | May 11, 2022 |
| Positivo      | C41TB                       | [2df08b295b](https://linux-hardware.org/?probe=2df08b295b) | May 11, 2022 |
| Lenovo        | Z50-70 20354                | [7dd92b7a41](https://linux-hardware.org/?probe=7dd92b7a41) | May 11, 2022 |
| Positivo      | C41TB                       | [164d3a45c4](https://linux-hardware.org/?probe=164d3a45c4) | May 11, 2022 |
| Lenovo        | B40-70 80F30017BR           | [352c705bf3](https://linux-hardware.org/?probe=352c705bf3) | May 11, 2022 |
| Lenovo        | B40-70 80F30017BR           | [cb100c3884](https://linux-hardware.org/?probe=cb100c3884) | May 11, 2022 |
| Dell          | Inspiron 3542               | [9762e9155b](https://linux-hardware.org/?probe=9762e9155b) | May 11, 2022 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [6cacb1c49c](https://linux-hardware.org/?probe=6cacb1c49c) | May 11, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [a8c09f53de](https://linux-hardware.org/?probe=a8c09f53de) | May 10, 2022 |
| Acer          | Swift SF314-54              | [cc3411e0b4](https://linux-hardware.org/?probe=cc3411e0b4) | May 10, 2022 |
| Dell          | XPS 13 7390                 | [a5630f81ad](https://linux-hardware.org/?probe=a5630f81ad) | May 10, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [03fc6852e2](https://linux-hardware.org/?probe=03fc6852e2) | May 10, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [20eb5bfb9f](https://linux-hardware.org/?probe=20eb5bfb9f) | May 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [2c069935d3](https://linux-hardware.org/?probe=2c069935d3) | May 10, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [a0dd43509d](https://linux-hardware.org/?probe=a0dd43509d) | May 09, 2022 |
| Standard      | Unknown                     | [3d9f8907fd](https://linux-hardware.org/?probe=3d9f8907fd) | May 09, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [ef9c4b3841](https://linux-hardware.org/?probe=ef9c4b3841) | May 09, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [86acc529d3](https://linux-hardware.org/?probe=86acc529d3) | May 09, 2022 |
| LG Electro... | 16Z90P-K.AAS9U1             | [26536e15bf](https://linux-hardware.org/?probe=26536e15bf) | May 09, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [11cb46c902](https://linux-hardware.org/?probe=11cb46c902) | May 08, 2022 |
| Acer          | Aspire ES1-531              | [a7927b8b27](https://linux-hardware.org/?probe=a7927b8b27) | May 08, 2022 |
| ASUSTek       | N76VZ                       | [f1e06f5c2f](https://linux-hardware.org/?probe=f1e06f5c2f) | May 08, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | [7894bd4591](https://linux-hardware.org/?probe=7894bd4591) | May 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [8fda480b12](https://linux-hardware.org/?probe=8fda480b12) | May 06, 2022 |
| Dell          | Precision 3520              | [2d5c4aa671](https://linux-hardware.org/?probe=2d5c4aa671) | May 05, 2022 |
| HP            | Laptop 15s-eq1xxx           | [f255a41930](https://linux-hardware.org/?probe=f255a41930) | May 05, 2022 |
| Toshiba       | IS 1413G                    | [8ca57528af](https://linux-hardware.org/?probe=8ca57528af) | May 04, 2022 |
| Toshiba       | IS 1413G                    | [3bc61ca207](https://linux-hardware.org/?probe=3bc61ca207) | May 04, 2022 |
| HP            | Laptop 15s-eq2xxx           | [8fbc520a1b](https://linux-hardware.org/?probe=8fbc520a1b) | May 03, 2022 |
| ASUSTek       | N76VZ                       | [b9c2a28ba0](https://linux-hardware.org/?probe=b9c2a28ba0) | May 03, 2022 |
| HP            | Laptop 15s-eq1xxx           | [7636de5c44](https://linux-hardware.org/?probe=7636de5c44) | May 02, 2022 |
| Lenovo        | IdeaPad 310-14ISK 80UG      | [72f6ebfc11](https://linux-hardware.org/?probe=72f6ebfc11) | May 01, 2022 |
| Lenovo        | IdeaPad 310-14ISK 80UG      | [0205c9da07](https://linux-hardware.org/?probe=0205c9da07) | May 01, 2022 |
| Dell          | XPS 13 9310                 | [03b461596c](https://linux-hardware.org/?probe=03b461596c) | May 01, 2022 |
| Dell          | XPS 15 9570                 | [133b6670de](https://linux-hardware.org/?probe=133b6670de) | May 01, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [428509b262](https://linux-hardware.org/?probe=428509b262) | May 01, 2022 |
| Toshiba       | IS 1413G                    | [6d0ad0b8f2](https://linux-hardware.org/?probe=6d0ad0b8f2) | May 01, 2022 |
| HP            | Laptop 14-dq2xxx            | [6cefd4f4de](https://linux-hardware.org/?probe=6cefd4f4de) | May 01, 2022 |
| ASUSTek       | G75VX                       | [fb58cab830](https://linux-hardware.org/?probe=fb58cab830) | Apr 30, 2022 |
| HP            | ZBook Firefly 15 inch G8... | [6cdff366fa](https://linux-hardware.org/?probe=6cdff366fa) | Apr 28, 2022 |
| MSI           | Stealth GS66 12UGS          | [bf36d72c14](https://linux-hardware.org/?probe=bf36d72c14) | Apr 26, 2022 |
| Acer          | Nitro AN515-43              | [99527fd065](https://linux-hardware.org/?probe=99527fd065) | Apr 26, 2022 |
| MSI           | Stealth GS66 12UGS          | [273526bab2](https://linux-hardware.org/?probe=273526bab2) | Apr 26, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [620718bb9e](https://linux-hardware.org/?probe=620718bb9e) | Apr 26, 2022 |
| Acer          | Aspire A515-45              | [128cdc0a61](https://linux-hardware.org/?probe=128cdc0a61) | Apr 26, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [0d3c8ed904](https://linux-hardware.org/?probe=0d3c8ed904) | Apr 25, 2022 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [b4577b2374](https://linux-hardware.org/?probe=b4577b2374) | Apr 25, 2022 |
| Dell          | Latitude 7280               | [7ad22b030d](https://linux-hardware.org/?probe=7ad22b030d) | Apr 24, 2022 |
| Lenovo        | ThinkPad T450s 20BWS2HP0... | [762843e768](https://linux-hardware.org/?probe=762843e768) | Apr 23, 2022 |
| Lenovo        | ThinkPad T450s 20BWS2HP0... | [11ec4d291b](https://linux-hardware.org/?probe=11ec4d291b) | Apr 23, 2022 |
| Dell          | Latitude E7450              | [5ce1623306](https://linux-hardware.org/?probe=5ce1623306) | Apr 22, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [b6a457c33a](https://linux-hardware.org/?probe=b6a457c33a) | Apr 21, 2022 |
| Wiltronic     | iVIEW i896QW                | [34e1873984](https://linux-hardware.org/?probe=34e1873984) | Apr 21, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | [9e1d98199a](https://linux-hardware.org/?probe=9e1d98199a) | Apr 18, 2022 |
| Lenovo        | ThinkPad W530 2463A49       | [202b5d34a1](https://linux-hardware.org/?probe=202b5d34a1) | Apr 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [81b837dc13](https://linux-hardware.org/?probe=81b837dc13) | Apr 18, 2022 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [b895187681](https://linux-hardware.org/?probe=b895187681) | Apr 17, 2022 |
| MSI           | Modern 14 B4MW              | [5d8e6ca082](https://linux-hardware.org/?probe=5d8e6ca082) | Apr 16, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [6f75f679f9](https://linux-hardware.org/?probe=6f75f679f9) | Apr 16, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [5bff5642ba](https://linux-hardware.org/?probe=5bff5642ba) | Apr 15, 2022 |
| Toshiba       | Satellite U840              | [9468123a43](https://linux-hardware.org/?probe=9468123a43) | Apr 15, 2022 |
| Dell          | Studio 1537                 | [56c84908d2](https://linux-hardware.org/?probe=56c84908d2) | Apr 15, 2022 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | [7436528d4f](https://linux-hardware.org/?probe=7436528d4f) | Apr 14, 2022 |
| Dell          | Inspiron 3505               | [719a1712f2](https://linux-hardware.org/?probe=719a1712f2) | Apr 14, 2022 |
| Dell          | Inspiron 3505               | [5781ceb5ca](https://linux-hardware.org/?probe=5781ceb5ca) | Apr 14, 2022 |
| Dell          | Inspiron 5548               | [77a3c1a7ce](https://linux-hardware.org/?probe=77a3c1a7ce) | Apr 14, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [9dd2675f34](https://linux-hardware.org/?probe=9dd2675f34) | Apr 14, 2022 |
| Dell          | XPS 13 9370                 | [0175e41474](https://linux-hardware.org/?probe=0175e41474) | Apr 14, 2022 |
| Dell          | XPS 13 9305                 | [48c7781b77](https://linux-hardware.org/?probe=48c7781b77) | Apr 14, 2022 |
| Dell          | Precision 7540              | [2aff9a81ff](https://linux-hardware.org/?probe=2aff9a81ff) | Apr 13, 2022 |
| Toshiba       | Satellite U840              | [c6fe138c8f](https://linux-hardware.org/?probe=c6fe138c8f) | Apr 13, 2022 |
| HP            | Laptop 15-dw3xxx            | [95cff2fbb1](https://linux-hardware.org/?probe=95cff2fbb1) | Apr 13, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | [c3d7c67155](https://linux-hardware.org/?probe=c3d7c67155) | Apr 12, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [73bb0eeab0](https://linux-hardware.org/?probe=73bb0eeab0) | Apr 12, 2022 |
| Intel         | W7650                       | [4bd778e810](https://linux-hardware.org/?probe=4bd778e810) | Apr 11, 2022 |
| MSI           | GS66 Stealth 10UH           | [5589b339ed](https://linux-hardware.org/?probe=5589b339ed) | Apr 11, 2022 |
| Dell          | Studio 1537                 | [048fceac96](https://linux-hardware.org/?probe=048fceac96) | Apr 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [5a60603c45](https://linux-hardware.org/?probe=5a60603c45) | Apr 11, 2022 |
| HP            | Pavilion 15                 | [c913cb5a4a](https://linux-hardware.org/?probe=c913cb5a4a) | Apr 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [ff93a4d2f5](https://linux-hardware.org/?probe=ff93a4d2f5) | Apr 08, 2022 |
| Lenovo        | ThinkPad T495 20NJ000XIX    | [f00fb05977](https://linux-hardware.org/?probe=f00fb05977) | Apr 07, 2022 |
| MSI           | GS66 Stealth 10UH           | [bd6f031bc8](https://linux-hardware.org/?probe=bd6f031bc8) | Apr 06, 2022 |
| Acer          | Swift SF114-32              | [3947799e36](https://linux-hardware.org/?probe=3947799e36) | Apr 05, 2022 |
| MSI           | Prestige 14Evo A11M         | [29b43c3e27](https://linux-hardware.org/?probe=29b43c3e27) | Apr 05, 2022 |
| Acer          | Swift SF314-41              | [564cfd1f31](https://linux-hardware.org/?probe=564cfd1f31) | Apr 04, 2022 |
| Acer          | Aspire A515-45              | [eb69a7978b](https://linux-hardware.org/?probe=eb69a7978b) | Apr 04, 2022 |
| Lenovo        | IdeaPad 320S-13IKB 81AK     | [8444b44333](https://linux-hardware.org/?probe=8444b44333) | Apr 04, 2022 |
| Chuwi         | Hi10 Go                     | [cfa6610288](https://linux-hardware.org/?probe=cfa6610288) | Apr 04, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [8c1841d2d0](https://linux-hardware.org/?probe=8c1841d2d0) | Apr 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [5eef69398a](https://linux-hardware.org/?probe=5eef69398a) | Apr 03, 2022 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | [ba4863a7bb](https://linux-hardware.org/?probe=ba4863a7bb) | Apr 02, 2022 |
| Lenovo        | IdeaPad Yoga 13 20175       | [cd942b0305](https://linux-hardware.org/?probe=cd942b0305) | Apr 02, 2022 |
| Dell          | Inspiron 5548               | [9e35cab29a](https://linux-hardware.org/?probe=9e35cab29a) | Apr 02, 2022 |
| Dell          | XPS 13 9333                 | [f4fb42182f](https://linux-hardware.org/?probe=f4fb42182f) | Apr 01, 2022 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | [4c0c1422e7](https://linux-hardware.org/?probe=4c0c1422e7) | Mar 31, 2022 |
| Lenovo        | ThinkPad X260 20F5S0HK1J    | [a83d3cbe5f](https://linux-hardware.org/?probe=a83d3cbe5f) | Mar 31, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [cc95f0e3ab](https://linux-hardware.org/?probe=cc95f0e3ab) | Mar 31, 2022 |
| VALE          | Notebook Slim S132          | [138a4f1d68](https://linux-hardware.org/?probe=138a4f1d68) | Mar 31, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20STS... | [05c02cbe41](https://linux-hardware.org/?probe=05c02cbe41) | Mar 31, 2022 |
| Avell High... | B.ON                        | [697fc1d4ec](https://linux-hardware.org/?probe=697fc1d4ec) | Mar 29, 2022 |
| Framework     | Laptop                      | [a22656afee](https://linux-hardware.org/?probe=a22656afee) | Mar 28, 2022 |
| Dell          | XPS 17 9710                 | [461d175c44](https://linux-hardware.org/?probe=461d175c44) | Mar 28, 2022 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | [16ac712c84](https://linux-hardware.org/?probe=16ac712c84) | Mar 24, 2022 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [1b57f1f410](https://linux-hardware.org/?probe=1b57f1f410) | Mar 13, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [917a6b65a8](https://linux-hardware.org/?probe=917a6b65a8) | Mar 10, 2022 |
| Sony          | VGN-FW21E                   | [930ce5581f](https://linux-hardware.org/?probe=930ce5581f) | Feb 25, 2022 |
| Unknown       | Unknown                     | [033354ee53](https://linux-hardware.org/?probe=033354ee53) | Jan 02, 2022 |
| Unknown       | Unknown                     | [ea795a97e1](https://linux-hardware.org/?probe=ea795a97e1) | Dec 26, 2021 |
| Unknown       | Unknown                     | [2b26e185d0](https://linux-hardware.org/?probe=2b26e185d0) | Dec 06, 2021 |
| Positivo      | CHT12CP                     | [53054c8f7a](https://linux-hardware.org/?probe=53054c8f7a) | Nov 20, 2021 |
| Lenovo        | IdeaPadFlex 14 20308        | [1734da4566](https://linux-hardware.org/?probe=1734da4566) | Nov 13, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [2da0673527](https://linux-hardware.org/?probe=2da0673527) | Nov 01, 2021 |
| Notebook      | PCx0Dx                      | [b1a527acdc](https://linux-hardware.org/?probe=b1a527acdc) | Oct 11, 2021 |
| Notebook      | PCx0Dx                      | [90d4556fdf](https://linux-hardware.org/?probe=90d4556fdf) | Oct 11, 2021 |
| Unknown       | Unknown                     | [af4bbffabf](https://linux-hardware.org/?probe=af4bbffabf) | Sep 27, 2021 |
| Unknown       | Unknown                     | [81fd834473](https://linux-hardware.org/?probe=81fd834473) | Sep 26, 2021 |
| HP            | ProBook 4740s               | [77b2eed991](https://linux-hardware.org/?probe=77b2eed991) | Sep 22, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                                       | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| 5.17.5-300.fc36.x86_64                                        | 54        | 9.11%   |
| 5.18.11-200.fc36.x86_64                                       | 48        | 8.09%   |
| 5.17.11-300.fc36.x86_64                                       | 45        | 7.59%   |
| 5.17.6-300.fc36.x86_64                                        | 43        | 7.25%   |
| 5.18.5-200.fc36.x86_64                                        | 39        | 6.58%   |
| 5.17.13-300.fc36.x86_64                                       | 36        | 6.07%   |
| 5.18.13-200.fc36.x86_64                                       | 35        | 5.9%    |
| 5.18.9-200.fc36.x86_64                                        | 28        | 4.72%   |
| 5.17.8-300.fc36.x86_64                                        | 28        | 4.72%   |
| 5.17.12-300.fc36.x86_64                                       | 27        | 4.55%   |
| 5.18.6-200.fc36.x86_64                                        | 26        | 4.38%   |
| 5.17.7-300.fc36.x86_64                                        | 24        | 4.05%   |
| 5.18.7-200.fc36.x86_64                                        | 23        | 3.88%   |
| 5.17.9-300.fc36.x86_64                                        | 21        | 3.54%   |
| 5.18.10-200.fc36.x86_64                                       | 20        | 3.37%   |
| 5.17.1-300.fc36.x86_64                                        | 16        | 2.7%    |
| 5.17.3-302.fc36.x86_64                                        | 14        | 2.36%   |
| 5.17.2-300.fc36.x86_64                                        | 13        | 2.19%   |
| 5.17.0-0.rc7.116.fc36.x86_64                                  | 12        | 2.02%   |
| 5.17.14-300.fc36.x86_64                                       | 5         | 0.84%   |
| 5.18.5-201.fsync.fc36.x86_64                                  | 3         | 0.51%   |
| 5.18.1-200.fc36.x86_64                                        | 3         | 0.51%   |
| 5.17.0-300.fc36.x86_64                                        | 3         | 0.51%   |
| 5.18.10-201.fsync.fc36.x86_64                                 | 2         | 0.34%   |
| 5.17.5-301.fsync.fc36.x86_64                                  | 2         | 0.34%   |
| 5.17.0-0.rc5.102.fc36.x86_64                                  | 2         | 0.34%   |
| 5.18.8-200.fc36.x86_64                                        | 1         | 0.17%   |
| 5.18.5-250.vanilla.1.fc36.x86_64                              | 1         | 0.17%   |
| 5.18.4-xm1.0.fc36.x86_64                                      | 1         | 0.17%   |
| 5.18.4-125.vanilla.1.fc36.x86_64                              | 1         | 0.17%   |
| 5.18.2-200.fc36.x86_64                                        | 1         | 0.17%   |
| 5.18.10-250.vanilla.1.fc36.x86_64                             | 1         | 0.17%   |
| 5.18.0-0.rc3.220422.d569e86915b7f2f.31.vanilla.1.fc36.x86_64  | 1         | 0.17%   |
| 5.17.7-301.fsync.fc36.x86_64                                  | 1         | 0.17%   |
| 5.17.4-300.fc36.x86_64                                        | 1         | 0.17%   |
| 5.17.3-301.fsync.fc36.x86_64                                  | 1         | 0.17%   |
| 5.16.9-200.rog.fc35.x86_64                                    | 1         | 0.17%   |
| 5.16.9-200.fc35.x86_64                                        | 1         | 0.17%   |
| 5.16.16-200.fc35.x86_64                                       | 1         | 0.17%   |
| 5.16.0-0.rc7.20211231git4f3d93c6eaff.52.vanilla.1.fc36.x86_64 | 1         | 0.17%   |
| 5.15.0-60.fc36.x86_64                                         | 1         | 0.17%   |
| 5.15.0-0.rc7.20211028git1fc596a56b33.56.fc36.x86_64           | 1         | 0.17%   |
| 5.15.0-0.rc4.20211008git1da38549dd64.36.fc36.x86_64           | 1         | 0.17%   |
| 5.15.0-0.rc2.20210923git58e2cf5d7946.21.vanilla.1.fc36.x86_64 | 1         | 0.17%   |
| 5.15.0-0.rc2.18.fc36.x86_64                                   | 1         | 0.17%   |
| 5.14.14-300.fc35.x86_64                                       | 1         | 0.17%   |
| 5.14.10-300.fc35.x86_64                                       | 1         | 0.17%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.17.5  | 56        | 9.44%   |
| 5.18.11 | 48        | 8.09%   |
| 5.17.11 | 45        | 7.59%   |
| 5.18.5  | 43        | 7.25%   |
| 5.17.6  | 43        | 7.25%   |
| 5.17.13 | 36        | 6.07%   |
| 5.18.13 | 35        | 5.9%    |
| 5.18.9  | 28        | 4.72%   |
| 5.17.8  | 28        | 4.72%   |
| 5.17.12 | 27        | 4.55%   |
| 5.18.6  | 26        | 4.38%   |
| 5.17.7  | 25        | 4.22%   |
| 5.18.7  | 23        | 3.88%   |
| 5.18.10 | 23        | 3.88%   |
| 5.17.9  | 21        | 3.54%   |
| 5.17.0  | 17        | 2.87%   |
| 5.17.1  | 16        | 2.7%    |
| 5.17.3  | 15        | 2.53%   |
| 5.17.2  | 13        | 2.19%   |
| 5.17.14 | 5         | 0.84%   |
| 5.15.0  | 5         | 0.84%   |
| 5.18.1  | 3         | 0.51%   |
| 5.18.4  | 2         | 0.34%   |
| 5.16.9  | 2         | 0.34%   |
| 5.18.8  | 1         | 0.17%   |
| 5.18.2  | 1         | 0.17%   |
| 5.18.0  | 1         | 0.17%   |
| 5.17.4  | 1         | 0.17%   |
| 5.16.16 | 1         | 0.17%   |
| 5.16.0  | 1         | 0.17%   |
| 5.14.14 | 1         | 0.17%   |
| 5.14.10 | 1         | 0.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.17    | 337       | 58.81%  |
| 5.18    | 225       | 39.27%  |
| 5.15    | 5         | 0.87%   |
| 5.16    | 4         | 0.7%    |
| 5.14    | 2         | 0.35%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 557       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 443       | 79.11%  |
| KDE5          | 73        | 13.04%  |
| Unknown       | 14        | 2.5%    |
| X-Cinnamon    | 7         | 1.25%   |
| XFCE          | 6         | 1.07%   |
| i3            | 6         | 1.07%   |
| Cinnamon      | 4         | 0.71%   |
| MATE          | 2         | 0.36%   |
| awesome       | 2         | 0.36%   |
| openbox       | 1         | 0.18%   |
| GNOME Classic | 1         | 0.18%   |
| Deepin        | 1         | 0.18%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 432       | 77.01%  |
| X11     | 118       | 21.03%  |
| Unknown | 8         | 1.43%   |
| Tty     | 3         | 0.53%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 296       | 52.86%  |
| GDM     | 204       | 36.43%  |
| SDDM    | 36        | 6.43%   |
| LightDM | 23        | 4.11%   |
| Ly      | 1         | 0.18%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 311       | 55.73%  |
| ru_RU   | 42        | 7.53%   |
| pt_BR   | 26        | 4.66%   |
| en_GB   | 25        | 4.48%   |
| de_DE   | 22        | 3.94%   |
| pl_PL   | 13        | 2.33%   |
| fr_FR   | 12        | 2.15%   |
| en_AU   | 11        | 1.97%   |
| it_IT   | 10        | 1.79%   |
| en_IN   | 8         | 1.43%   |
| es_MX   | 7         | 1.25%   |
| es_ES   | 6         | 1.08%   |
| es_CL   | 6         | 1.08%   |
| nl_NL   | 4         | 0.72%   |
| en_CA   | 4         | 0.72%   |
| de_AT   | 4         | 0.72%   |
| tr_TR   | 3         | 0.54%   |
| pt_PT   | 3         | 0.54%   |
| es_AR   | 3         | 0.54%   |
| en_NZ   | 3         | 0.54%   |
| ru_UA   | 2         | 0.36%   |
| nl_BE   | 2         | 0.36%   |
| hu_HU   | 2         | 0.36%   |
| hr_HR   | 2         | 0.36%   |
| en_IL   | 2         | 0.36%   |
| de_CH   | 2         | 0.36%   |
| cs_CZ   | 2         | 0.36%   |
| zh_CN   | 1         | 0.18%   |
| sv_SE   | 1         | 0.18%   |
| sr_RS   | 1         | 0.18%   |
| nb_NO   | 1         | 0.18%   |
| id_ID   | 1         | 0.18%   |
| gl_ES   | 1         | 0.18%   |
| fr_CA   | 1         | 0.18%   |
| fr_BE   | 1         | 0.18%   |
| es_VE   | 1         | 0.18%   |
| es_UY   | 1         | 0.18%   |
| es_SV   | 1         | 0.18%   |
| es_GT   | 1         | 0.18%   |
| es_EC   | 1         | 0.18%   |
| en_PH   | 1         | 0.18%   |
| en_NL   | 1         | 0.18%   |
| en_IE   | 1         | 0.18%   |
| en_DK   | 1         | 0.18%   |
| el_GR   | 1         | 0.18%   |
| da_DK   | 1         | 0.18%   |
| ba_RU   | 1         | 0.18%   |
| Unknown | 1         | 0.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 476       | 85.3%   |
| BIOS | 82        | 14.7%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 451       | 80.97%  |
| Ext4    | 95        | 17.06%  |
| Xfs     | 8         | 1.44%   |
| F2fs    | 2         | 0.36%   |
| Unknown | 1         | 0.18%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 302       | 53.93%  |
| GPT     | 234       | 41.79%  |
| MBR     | 24        | 4.29%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 500       | 89.61%  |
| Yes       | 58        | 10.39%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 454       | 81.36%  |
| Yes       | 104       | 18.64%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 173       | 31.06%  |
| Hewlett-Packard        | 95        | 17.06%  |
| Dell                   | 82        | 14.72%  |
| ASUSTek Computer       | 64        | 11.49%  |
| Acer                   | 28        | 5.03%   |
| Apple                  | 13        | 2.33%   |
| MSI                    | 11        | 1.97%   |
| HUAWEI                 | 9         | 1.62%   |
| Samsung Electronics    | 7         | 1.26%   |
| Toshiba                | 6         | 1.08%   |
| Framework              | 6         | 1.08%   |
| Sony                   | 5         | 0.9%    |
| Notebook               | 5         | 0.9%    |
| Positivo               | 4         | 0.72%   |
| Gigabyte Technology    | 4         | 0.72%   |
| Unknown                | 4         | 0.72%   |
| Timi                   | 3         | 0.54%   |
| VALE                   | 2         | 0.36%   |
| System76               | 2         | 0.36%   |
| Panasonic              | 2         | 0.36%   |
| GPU Company            | 2         | 0.36%   |
| Google                 | 2         | 0.36%   |
| Chuwi                  | 2         | 0.36%   |
| Alienware              | 2         | 0.36%   |
| Wiltronic              | 1         | 0.18%   |
| VIT                    | 1         | 0.18%   |
| TUXEDO                 | 1         | 0.18%   |
| Standard               | 1         | 0.18%   |
| SLIMBOOK               | 1         | 0.18%   |
| SKIKK                  | 1         | 0.18%   |
| ROCK Pi                | 1         | 0.18%   |
| Pegatron               | 1         | 0.18%   |
| Packard Bell           | 1         | 0.18%   |
| Micro Electronics      | 1         | 0.18%   |
| Login Informatica      | 1         | 0.18%   |
| LG Electronics         | 1         | 0.18%   |
| Itautec                | 1         | 0.18%   |
| IT Channel Pty         | 1         | 0.18%   |
| ICL                    | 1         | 0.18%   |
| HONOR                  | 1         | 0.18%   |
| GPD                    | 1         | 0.18%   |
| Getac                  | 1         | 0.18%   |
| GEO                    | 1         | 0.18%   |
| Fujitsu                | 1         | 0.18%   |
| eMachines              | 1         | 0.18%   |
| Clevo                  | 1         | 0.18%   |
| Avell High Performance | 1         | 0.18%   |
| Aquarius               | 1         | 0.18%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 10        | 1.8%    |
| Framework Laptop                       | 6         | 1.08%   |
| HP Notebook                            | 5         | 0.9%    |
| Lenovo IdeaPad 5 15ARE05 81YQ          | 4         | 0.72%   |
| HP Pavilion g6                         | 4         | 0.72%   |
| HP EliteBook 8470p                     | 4         | 0.72%   |
| Lenovo ThinkBook 15 G2 ITL 20VE        | 3         | 0.54%   |
| Lenovo ThinkBook 14 G3 ACL 21A2        | 3         | 0.54%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY   | 3         | 0.54%   |
| HP Pavilion Aero Laptop 13-be0xxx      | 3         | 0.54%   |
| Dell XPS 15 9570                       | 3         | 0.54%   |
| Dell XPS 13 9310                       | 3         | 0.54%   |
| ASUS ROG Zephyrus G14 GA402RJ_GA402RJ  | 3         | 0.54%   |
| ASUS ROG Strix G513QY_G513QY           | 3         | 0.54%   |
| Timi A35S                              | 2         | 0.36%   |
| Samsung 550XDA                         | 2         | 0.36%   |
| Lenovo ThinkBook 16p Gen 2 20YM        | 2         | 0.36%   |
| Lenovo IdeaPad 530S-14IKB 81EU         | 2         | 0.36%   |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7       | 2         | 0.36%   |
| Lenovo IdeaPad 5 14ARE05 81YM          | 2         | 0.36%   |
| Lenovo IdeaPad 5 14ALC05 82LM          | 2         | 0.36%   |
| HUAWEI KLVL-WXX9                       | 2         | 0.36%   |
| HP ZBook Fury 15 G7 Mobile Workstation | 2         | 0.36%   |
| HP ZBook 17 G5                         | 2         | 0.36%   |
| HP ProBook 470 G5                      | 2         | 0.36%   |
| HP Pavilion Laptop 15-cw1xxx           | 2         | 0.36%   |
| HP Pavilion Laptop 15-cs0xxx           | 2         | 0.36%   |
| HP 250 G7 Notebook PC                  | 2         | 0.36%   |
| GPU Company GWNR51416                  | 2         | 0.36%   |
| Dell XPS 17 9710                       | 2         | 0.36%   |
| Dell XPS 15 9560                       | 2         | 0.36%   |
| Dell XPS 15 9520                       | 2         | 0.36%   |
| Dell XPS 13 9370                       | 2         | 0.36%   |
| Dell XPS 13 9350                       | 2         | 0.36%   |
| Dell XPS 13 7390                       | 2         | 0.36%   |
| Dell Latitude E7470                    | 2         | 0.36%   |
| Dell Latitude E6520                    | 2         | 0.36%   |
| Dell Latitude E6230                    | 2         | 0.36%   |
| Dell Inspiron 7472                     | 2         | 0.36%   |
| Dell Inspiron 7460                     | 2         | 0.36%   |
| Dell Inspiron 3542                     | 2         | 0.36%   |
| Dell G3 3590                           | 2         | 0.36%   |
| ASUS X541NA                            | 2         | 0.36%   |
| ASUS VivoBook_ASUSLaptop X512DA_F512DA | 2         | 0.36%   |
| ASUS ROG Zephyrus G14 GA401QM_GA401QM  | 2         | 0.36%   |
| ASUS ROG Strix G513QM_G513QM           | 2         | 0.36%   |
| Apple MacBookPro12,1                   | 2         | 0.36%   |
| Acer Swift SF114-32                    | 2         | 0.36%   |
| Acer Nitro AN515-55                    | 2         | 0.36%   |
| Acer Aspire E5-573G                    | 2         | 0.36%   |
| Acer Aspire A515-45                    | 2         | 0.36%   |
| Wiltronic iVIEW i896QW                 | 1         | 0.18%   |
| VIT M2420                              | 1         | 0.18%   |
| VALE Notebook Slim S132                | 1         | 0.18%   |
| VALE Notebook Classic C140             | 1         | 0.18%   |
| TUXEDO Pulse 14 Gen1                   | 1         | 0.18%   |
| Toshiba Satellite U940                 | 1         | 0.18%   |
| Toshiba Satellite U840                 | 1         | 0.18%   |
| Toshiba Satellite L505D                | 1         | 0.18%   |
| Toshiba Satellite C855-12R             | 1         | 0.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 92        | 16.52%  |
| Lenovo IdeaPad        | 49        | 8.8%    |
| HP Pavilion           | 24        | 4.31%   |
| Dell XPS              | 24        | 4.31%   |
| Dell Inspiron         | 22        | 3.95%   |
| Dell Latitude         | 21        | 3.77%   |
| ASUS ROG              | 19        | 3.41%   |
| HP Laptop             | 16        | 2.87%   |
| HP EliteBook          | 13        | 2.33%   |
| ASUS VivoBook         | 13        | 2.33%   |
| Acer Aspire           | 13        | 2.33%   |
| Lenovo ThinkBook      | 11        | 1.97%   |
| HP ProBook            | 11        | 1.97%   |
| Unknown               | 10        | 1.8%    |
| HP ZBook              | 9         | 1.62%   |
| Dell Precision        | 9         | 1.62%   |
| ASUS ASUS             | 7         | 1.26%   |
| Acer Swift            | 7         | 1.26%   |
| Framework Laptop      | 6         | 1.08%   |
| Toshiba Satellite     | 5         | 0.9%    |
| HP Notebook           | 5         | 0.9%    |
| Acer Nitro            | 5         | 0.9%    |
| Lenovo Legion         | 4         | 0.72%   |
| ASUS Zenbook          | 4         | 0.72%   |
| Lenovo Yoga           | 3         | 0.54%   |
| HP OMEN               | 3         | 0.54%   |
| HP 250                | 3         | 0.54%   |
| Dell Vostro           | 3         | 0.54%   |
| ASUS TUF              | 3         | 0.54%   |
| VALE Notebook         | 2         | 0.36%   |
| Timi A35S             | 2         | 0.36%   |
| Samsung 550XDA        | 2         | 0.36%   |
| MSI GF63              | 2         | 0.36%   |
| HUAWEI KLVL-WXX9      | 2         | 0.36%   |
| HP ENVY               | 2         | 0.36%   |
| GPU Company GWNR51416 | 2         | 0.36%   |
| Dell G3               | 2         | 0.36%   |
| ASUS X541NA           | 2         | 0.36%   |
| Apple MacBookPro8     | 2         | 0.36%   |
| Apple MacBookPro12    | 2         | 0.36%   |
| Wiltronic iVIEW       | 1         | 0.18%   |
| VIT M2420             | 1         | 0.18%   |
| TUXEDO Pulse          | 1         | 0.18%   |
| Timi Redmi            | 1         | 0.18%   |
| System76 Oryx         | 1         | 0.18%   |
| System76 Bonobo       | 1         | 0.18%   |
| Sony VPCSA2Z9R        | 1         | 0.18%   |
| Sony VPCEE3S1E        | 1         | 0.18%   |
| Sony VGN-FW21E        | 1         | 0.18%   |
| Sony SVF1531V8CW      | 1         | 0.18%   |
| Sony SVE15128CNB      | 1         | 0.18%   |
| SLIMBOOK PROX-AMD5    | 1         | 0.18%   |
| SKIKK GREEN           | 1         | 0.18%   |
| Samsung 550XBE        | 1         | 0.18%   |
| Samsung 500R5M        | 1         | 0.18%   |
| Samsung 355V4C        | 1         | 0.18%   |
| Samsung 300E4A        | 1         | 0.18%   |
| Samsung 270E5G        | 1         | 0.18%   |
| Positivo VJF155F11UAR | 1         | 0.18%   |
| Positivo H14BU08      | 1         | 0.18%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 115       | 20.65%  |
| 2020 | 95        | 17.06%  |
| 2019 | 58        | 10.41%  |
| 2018 | 58        | 10.41%  |
| 2013 | 30        | 5.39%   |
| 2017 | 29        | 5.21%   |
| 2016 | 28        | 5.03%   |
| 2015 | 28        | 5.03%   |
| 2011 | 28        | 5.03%   |
| 2022 | 25        | 4.49%   |
| 2012 | 25        | 4.49%   |
| 2014 | 19        | 3.41%   |
| 2008 | 7         | 1.26%   |
| 2010 | 6         | 1.08%   |
| 2009 | 6         | 1.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 557       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 432       | 77.42%  |
| Enabled  | 126       | 22.58%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 554       | 99.46%  |
| Yes  | 3         | 0.54%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 174       | 31.13%  |
| 8.01-16.0   | 127       | 22.72%  |
| 16.01-24.0  | 110       | 19.68%  |
| 32.01-64.0  | 73        | 13.06%  |
| 3.01-4.0    | 48        | 8.59%   |
| 64.01-256.0 | 13        | 2.33%   |
| 24.01-32.0  | 8         | 1.43%   |
| 1.01-2.0    | 5         | 0.89%   |
| 2.01-3.0    | 1         | 0.18%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 178       | 30.8%   |
| 2.01-3.0   | 158       | 27.34%  |
| 3.01-4.0   | 147       | 25.43%  |
| 1.01-2.0   | 61        | 10.55%  |
| 8.01-16.0  | 27        | 4.67%   |
| 0.51-1.0   | 3         | 0.52%   |
| 24.01-32.0 | 2         | 0.35%   |
| 16.01-24.0 | 2         | 0.35%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 413       | 73.62%  |
| 2      | 130       | 23.17%  |
| 3      | 15        | 2.67%   |
| 4      | 2         | 0.36%   |
| 0      | 1         | 0.18%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 456       | 81.87%  |
| Yes       | 101       | 18.13%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 396       | 71.1%   |
| No        | 161       | 28.9%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 550       | 98.74%  |
| No        | 7         | 1.26%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 498       | 89.41%  |
| No        | 59        | 10.59%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| USA                | 103       | 18.36%  |
| Russia             | 48        | 8.56%   |
| Brazil             | 37        | 6.6%    |
| Germany            | 36        | 6.42%   |
| India              | 28        | 4.99%   |
| Poland             | 22        | 3.92%   |
| Italy              | 21        | 3.74%   |
| UK                 | 16        | 2.85%   |
| Mexico             | 16        | 2.85%   |
| France             | 16        | 2.85%   |
| Netherlands        | 15        | 2.67%   |
| Australia          | 14        | 2.5%    |
| Turkey             | 12        | 2.14%   |
| Indonesia          | 11        | 1.96%   |
| Spain              | 10        | 1.78%   |
| Canada             | 8         | 1.43%   |
| Belgium            | 8         | 1.43%   |
| Chile              | 7         | 1.25%   |
| Austria            | 7         | 1.25%   |
| Switzerland        | 5         | 0.89%   |
| Norway             | 5         | 0.89%   |
| Hungary            | 5         | 0.89%   |
| Czechia            | 5         | 0.89%   |
| Croatia            | 5         | 0.89%   |
| Argentina          | 5         | 0.89%   |
| Sweden             | 4         | 0.71%   |
| Romania            | 4         | 0.71%   |
| Portugal           | 4         | 0.71%   |
| Philippines        | 4         | 0.71%   |
| Israel             | 4         | 0.71%   |
| Belarus            | 4         | 0.71%   |
| Ukraine            | 3         | 0.53%   |
| Taiwan             | 3         | 0.53%   |
| Singapore          | 3         | 0.53%   |
| Moldova            | 3         | 0.53%   |
| Japan              | 3         | 0.53%   |
| Colombia           | 3         | 0.53%   |
| Bulgaria           | 3         | 0.53%   |
| Venezuela          | 2         | 0.36%   |
| South Africa       | 2         | 0.36%   |
| Slovakia           | 2         | 0.36%   |
| New Zealand        | 2         | 0.36%   |
| Nepal              | 2         | 0.36%   |
| Kazakhstan         | 2         | 0.36%   |
| Ireland            | 2         | 0.36%   |
| Iceland            | 2         | 0.36%   |
| Hong Kong          | 2         | 0.36%   |
| Estonia            | 2         | 0.36%   |
| El Salvador        | 2         | 0.36%   |
| Egypt              | 2         | 0.36%   |
| Dominican Republic | 2         | 0.36%   |
| Denmark            | 2         | 0.36%   |
| Uzbekistan         | 1         | 0.18%   |
| UAE                | 1         | 0.18%   |
| Serbia             | 1         | 0.18%   |
| Saudi Arabia       | 1         | 0.18%   |
| Qatar              | 1         | 0.18%   |
| Puerto Rico        | 1         | 0.18%   |
| Peru               | 1         | 0.18%   |
| Myanmar            | 1         | 0.18%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Moscow             | 14        | 2.44%   |
| St Petersburg      | 12        | 2.09%   |
| Sao Paulo          | 8         | 1.4%    |
| Warsaw             | 7         | 1.22%   |
| Melbourne          | 7         | 1.22%   |
| Istanbul           | 6         | 1.05%   |
| Munich             | 5         | 0.87%   |
| Kolkata            | 5         | 0.87%   |
| Budapest           | 5         | 0.87%   |
| Berlin             | 5         | 0.87%   |
| Santiago           | 4         | 0.7%    |
| Paris              | 4         | 0.7%    |
| Oslo               | 4         | 0.7%    |
| Minsk              | 4         | 0.7%    |
| Zagreb             | 3         | 0.52%   |
| Vienna             | 3         | 0.52%   |
| Sofia              | 3         | 0.52%   |
| Singapore          | 3         | 0.52%   |
| Rome               | 3         | 0.52%   |
| Prague             | 3         | 0.52%   |
| Mexico City        | 3         | 0.52%   |
| Bogor              | 3         | 0.52%   |
| Bengaluru          | 3         | 0.52%   |
| Zurich             | 2         | 0.35%   |
| Yaroslavl          | 2         | 0.35%   |
| Vijayawada         | 2         | 0.35%   |
| Tyumen             | 2         | 0.35%   |
| Tokyo              | 2         | 0.35%   |
| Tallinn            | 2         | 0.35%   |
| Stockholm          | 2         | 0.35%   |
| Springboro         | 2         | 0.35%   |
| Southampton        | 2         | 0.35%   |
| Seattle            | 2         | 0.35%   |
| Santo Domingo Este | 2         | 0.35%   |
| San Diego          | 2         | 0.35%   |
| Samara             | 2         | 0.35%   |
| Rotterdam          | 2         | 0.35%   |
| Rostov-on-Don      | 2         | 0.35%   |
| Rosario            | 2         | 0.35%   |
| Rio de Janeiro     | 2         | 0.35%   |
| Reykjavik          | 2         | 0.35%   |
| Regina             | 2         | 0.35%   |
| Raleigh            | 2         | 0.35%   |
| Parker             | 2         | 0.35%   |
| New York           | 2         | 0.35%   |
| Nantes             | 2         | 0.35%   |
| Mundelein          | 2         | 0.35%   |
| Milan              | 2         | 0.35%   |
| Merritt Island     | 2         | 0.35%   |
| Los Angeles        | 2         | 0.35%   |
| Lima               | 2         | 0.35%   |
| Krakow             | 2         | 0.35%   |
| Jakarta            | 2         | 0.35%   |
| Jaipur             | 2         | 0.35%   |
| Izmir              | 2         | 0.35%   |
| Heidelberg         | 2         | 0.35%   |
| Halifax            | 2         | 0.35%   |
| Guadalajara        | 2         | 0.35%   |
| Gdansk             | 2         | 0.35%   |
| Denver             | 2         | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 146       | 175    | 20.92%  |
| WDC                            | 59        | 66     | 8.45%   |
| Seagate                        | 54        | 55     | 7.74%   |
| SanDisk                        | 50        | 55     | 7.16%   |
| SK hynix                       | 44        | 46     | 6.3%    |
| Toshiba                        | 39        | 42     | 5.59%   |
| Kingston                       | 32        | 35     | 4.58%   |
| Micron Technology              | 29        | 32     | 4.15%   |
| Intel                          | 29        | 38     | 4.15%   |
| Unknown                        | 24        | 31     | 3.44%   |
| Crucial                        | 22        | 22     | 3.15%   |
| KIOXIA                         | 16        | 20     | 2.29%   |
| A-DATA Technology              | 13        | 14     | 1.86%   |
| HGST                           | 11        | 11     | 1.58%   |
| Phison                         | 8         | 8      | 1.15%   |
| Apple                          | 8         | 8      | 1.15%   |
| Silicon Motion                 | 7         | 7      | 1%      |
| Hitachi                        | 7         | 7      | 1%      |
| Unknown                        | 6         | 6      | 0.86%   |
| SSSTC                          | 5         | 5      | 0.72%   |
| LITEON                         | 5         | 5      | 0.72%   |
| China                          | 5         | 6      | 0.72%   |
| XPG                            | 4         | 5      | 0.57%   |
| UMIS                           | 4         | 4      | 0.57%   |
| SABRENT                        | 4         | 4      | 0.57%   |
| PNY                            | 4         | 5      | 0.57%   |
| Intenso                        | 4         | 4      | 0.57%   |
| Solid State Storage Technology | 3         | 3      | 0.43%   |
| Netac                          | 3         | 3      | 0.43%   |
| Lenovo                         | 3         | 4      | 0.43%   |
| Fujitsu                        | 3         | 3      | 0.43%   |
| Transcend                      | 2         | 2      | 0.29%   |
| Patriot                        | 2         | 3      | 0.29%   |
| LITEONIT                       | 2         | 2      | 0.29%   |
| Lite-On                        | 2         | 2      | 0.29%   |
| Lexar                          | 2         | 2      | 0.29%   |
| KingFast                       | 2         | 2      | 0.29%   |
| JMicron Technology             | 2         | 2      | 0.29%   |
| GALAX                          | 2         | 2      | 0.29%   |
| WDC WDS2                       | 1         | 1      | 0.14%   |
| Vaseky                         | 1         | 1      | 0.14%   |
| USB3.0                         | 1         | 1      | 0.14%   |
| Union Memory (Shenzhen)        | 1         | 1      | 0.14%   |
| Teclast                        | 1         | 1      | 0.14%   |
| Team                           | 1         | 1      | 0.14%   |
| T-FORCE                        | 1         | 1      | 0.14%   |
| Realtek Semiconductor          | 1         | 1      | 0.14%   |
| RCESSD                         | 1         | 1      | 0.14%   |
| Origin                         | 1         | 1      | 0.14%   |
| OCZ-VERTEX3                    | 1         | 1      | 0.14%   |
| OCZ                            | 1         | 1      | 0.14%   |
| new                            | 1         | 1      | 0.14%   |
| Mass                           | 1         | 1      | 0.14%   |
| Leven                          | 1         | 1      | 0.14%   |
| KingDian                       | 1         | 1      | 0.14%   |
| IB-AC703                       | 1         | 1      | 0.14%   |
| HPE                            | 1         | 1      | 0.14%   |
| Hewlett-Packard                | 1         | 1      | 0.14%   |
| GOODRAM                        | 1         | 2      | 0.14%   |
| GLOWAY                         | 1         | 1      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| SanDisk NVMe SSD Drive 512GB              | 16        | 2.21%   |
| Samsung NVMe SSD Drive 512GB              | 14        | 1.94%   |
| Samsung NVMe SSD Drive 256GB              | 12        | 1.66%   |
| Intel NVMe SSD Drive 512GB                | 12        | 1.66%   |
| Seagate ST1000LM035-1RK172 1TB            | 11        | 1.52%   |
| Samsung NVMe SSD Drive 1TB                | 11        | 1.52%   |
| Samsung NVMe SSD Drive 1024GB             | 11        | 1.52%   |
| SK hynix NVMe SSD Drive 512GB             | 10        | 1.38%   |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 10        | 1.38%   |
| Toshiba NVMe SSD Drive 512GB              | 7         | 0.97%   |
| SanDisk NVMe SSD Drive 1024GB             | 7         | 0.97%   |
| HGST HTS721010A9E630 1TB                  | 7         | 0.97%   |
| Unknown MMC Card  64GB                    | 6         | 0.83%   |
| Toshiba MQ01ABD100 1TB                    | 6         | 0.83%   |
| Micron NVMe SSD Drive 512GB               | 6         | 0.83%   |
| Unknown                                   | 6         | 0.83%   |
| Toshiba NVMe SSD Drive 256GB              | 5         | 0.69%   |
| Toshiba MQ04ABF100 1TB                    | 5         | 0.69%   |
| SK hynix NVMe SSD Drive 256GB             | 5         | 0.69%   |
| SK hynix NVMe SSD Drive 1024GB            | 5         | 0.69%   |
| Samsung SSD 860 EVO 250GB                 | 5         | 0.69%   |
| Samsung NVMe SSD Drive 500GB              | 5         | 0.69%   |
| KIOXIA NVMe SSD Drive 512GB               | 5         | 0.69%   |
| Kingston SA400S37240G 240GB SSD           | 5         | 0.69%   |
| Unknown MMC Card  32GB                    | 4         | 0.55%   |
| Unknown MMC Card  128GB                   | 4         | 0.55%   |
| Seagate ST1000LM049-2GH172 1TB            | 4         | 0.55%   |
| SanDisk NVMe SSD Drive 1TB                | 4         | 0.55%   |
| Samsung SSD 980 PRO 1TB                   | 4         | 0.55%   |
| Samsung NVMe SSD Drive 2TB                | 4         | 0.55%   |
| Samsung MZVLB1T0HBLR-000L7 1TB            | 4         | 0.55%   |
| Samsung MZALQ512HALU-000L2 512GB          | 4         | 0.55%   |
| SABRENT Disk 1TB                          | 4         | 0.55%   |
| Micron NVMe SSD Drive 1024GB              | 4         | 0.55%   |
| Crucial CT480BX500SSD1 480GB              | 4         | 0.55%   |
| WDC WD10SPZX-24Z10 1TB                    | 3         | 0.41%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB      | 3         | 0.41%   |
| Toshiba KXG6AZNV512G 512GB                | 3         | 0.41%   |
| Solid State Storage NVMe SSD Drive 256GB  | 3         | 0.41%   |
| SK hynix SKHynix_HFM512GDHTNI-87A0B 512GB | 3         | 0.41%   |
| Silicon Motion NVMe SSD Drive 256GB       | 3         | 0.41%   |
| Seagate ST1000LM048-2E7172 1TB            | 3         | 0.41%   |
| Seagate Expansion 1TB                     | 3         | 0.41%   |
| SanDisk SSD PLUS 480GB                    | 3         | 0.41%   |
| Samsung MZALQ512HBLU-00BL2 512GB          | 3         | 0.41%   |
| Kingston SA400S37960G 960GB SSD           | 3         | 0.41%   |
| Kingston NVMe SSD Drive 512GB             | 3         | 0.41%   |
| Kingston NVMe SSD Drive 1TB               | 3         | 0.41%   |
| Crucial CT500MX500SSD1 500GB              | 3         | 0.41%   |
| Crucial CT1000P2SSD8 1TB                  | 3         | 0.41%   |
| Crucial CT1000MX500SSD1 1TB               | 3         | 0.41%   |
| WDC WDS240G2G0A-00JH30 240GB SSD          | 2         | 0.28%   |
| WDC WDS100T2B0A-00SM50 1TB SSD            | 2         | 0.28%   |
| WDC WD1600BEVT-22ZCT0 160GB               | 2         | 0.28%   |
| WDC WD10SPZX-24Z10T0 1TB                  | 2         | 0.28%   |
| WDC WD10JPVX-75JC3T0 1TB                  | 2         | 0.28%   |
| WDC PC SN530 SDBPNPZ-256G-1006 256GB      | 2         | 0.28%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB      | 2         | 0.28%   |
| WDC PC SN530 SDBPMPZ-256G-1001 256GB      | 2         | 0.28%   |
| Unknown DA4064  64GB                      | 2         | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 51        | 52     | 41.46%  |
| WDC      | 25        | 29     | 20.33%  |
| Toshiba  | 17        | 19     | 13.82%  |
| HGST     | 11        | 11     | 8.94%   |
| Hitachi  | 7         | 7      | 5.69%   |
| SABRENT  | 4         | 4      | 3.25%   |
| Fujitsu  | 3         | 3      | 2.44%   |
| Unknown  | 2         | 3      | 1.63%   |
| Apple    | 2         | 2      | 1.63%   |
| IB-AC703 | 1         | 1      | 0.81%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 49        | 55     | 25.65%  |
| Kingston            | 19        | 21     | 9.95%   |
| Crucial             | 19        | 19     | 9.95%   |
| SanDisk             | 18        | 20     | 9.42%   |
| Micron Technology   | 8         | 8      | 4.19%   |
| WDC                 | 7         | 9      | 3.66%   |
| Intel               | 6         | 6      | 3.14%   |
| Apple               | 6         | 6      | 3.14%   |
| A-DATA Technology   | 6         | 7      | 3.14%   |
| LITEON              | 4         | 4      | 2.09%   |
| Intenso             | 4         | 4      | 2.09%   |
| China               | 4         | 5      | 2.09%   |
| PNY                 | 3         | 3      | 1.57%   |
| Netac               | 3         | 3      | 1.57%   |
| Transcend           | 2         | 2      | 1.05%   |
| SK hynix            | 2         | 2      | 1.05%   |
| Seagate             | 2         | 2      | 1.05%   |
| Patriot             | 2         | 3      | 1.05%   |
| LITEONIT            | 2         | 2      | 1.05%   |
| Lexar               | 2         | 2      | 1.05%   |
| GALAX               | 2         | 2      | 1.05%   |
| Unknown             | 2         | 2      | 1.05%   |
| WDC WDS2            | 1         | 1      | 0.52%   |
| Vaseky              | 1         | 1      | 0.52%   |
| USB3.0              | 1         | 1      | 0.52%   |
| Teclast             | 1         | 1      | 0.52%   |
| Origin              | 1         | 1      | 0.52%   |
| OCZ-VERTEX3         | 1         | 1      | 0.52%   |
| OCZ                 | 1         | 1      | 0.52%   |
| Leven               | 1         | 1      | 0.52%   |
| KingFast            | 1         | 1      | 0.52%   |
| HPE                 | 1         | 1      | 0.52%   |
| GOODRAM             | 1         | 2      | 0.52%   |
| GLOWAY              | 1         | 1      | 0.52%   |
| Gigabyte Technology | 1         | 1      | 0.52%   |
| EZCOOL              | 1         | 1      | 0.52%   |
| EAGET               | 1         | 1      | 0.52%   |
| Dogfish             | 1         | 1      | 0.52%   |
| Corsair             | 1         | 2      | 0.52%   |
| Apacer              | 1         | 1      | 0.52%   |
| ADATA SU            | 1         | 1      | 0.52%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 332       | 397    | 50.3%   |
| SSD     | 171       | 208    | 25.91%  |
| HDD     | 122       | 131    | 18.48%  |
| MMC     | 24        | 31     | 3.64%   |
| Unknown | 11        | 12     | 1.67%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 332       | 396    | 51.31%  |
| SATA | 264       | 323    | 40.8%   |
| SAS  | 27        | 29     | 4.17%   |
| MMC  | 24        | 31     | 3.71%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 172       | 199    | 57.53%  |
| 0.51-1.0   | 114       | 126    | 38.13%  |
| 1.01-2.0   | 11        | 12     | 3.68%   |
| 4.01-10.0  | 2         | 2      | 0.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 501-1000       | 126       | 22.22%  |
| 251-500        | 117       | 20.63%  |
| 101-250        | 76        | 13.4%   |
| 1001-2000      | 74        | 13.05%  |
| 1-20           | 72        | 12.7%   |
| Unknown        | 50        | 8.82%   |
| 51-100         | 23        | 4.06%   |
| 2001-3000      | 12        | 2.12%   |
| More than 3000 | 9         | 1.59%   |
| 21-50          | 8         | 1.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 204       | 35.66%  |
| 21-50          | 91        | 15.91%  |
| 101-250        | 68        | 11.89%  |
| 51-100         | 65        | 11.36%  |
| 251-500        | 56        | 9.79%   |
| Unknown        | 50        | 8.74%   |
| 501-1000       | 32        | 5.59%   |
| 1001-2000      | 5         | 0.87%   |
| More than 3000 | 1         | 0.17%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB           | 3         | 3      | 14.29%  |
| HGST HTS721010A9E630 1TB                     | 2         | 2      | 9.52%   |
| WDC WD5000LPCX-24C6HT0 500GB                 | 1         | 1      | 4.76%   |
| WDC WD5000LPCX-00VHAT0 500GB                 | 1         | 1      | 4.76%   |
| Toshiba MK5055GSX 500GB                      | 1         | 1      | 4.76%   |
| Seagate ST9320325AS 320GB                    | 1         | 1      | 4.76%   |
| Seagate ST500LT012-1DG142 500GB              | 1         | 1      | 4.76%   |
| Seagate ST500LM021-1KJ152 500GB              | 1         | 1      | 4.76%   |
| SanDisk SD6PP4M-256G-1006 256GB SSD          | 1         | 1      | 4.76%   |
| Samsung Electronics SSD 870 EVO 500GB        | 1         | 1      | 4.76%   |
| Samsung Electronics SSD 840 Series 250GB     | 1         | 1      | 4.76%   |
| Origin Inception TLC830 Pro Series 256GB SSD | 1         | 1      | 4.76%   |
| OCZ-VERTEX3 MI 120GB SSD                     | 1         | 1      | 4.76%   |
| Micron Technology 1100 SATA 256GB SSD        | 1         | 1      | 4.76%   |
| LITEONIT LCS-128M6S-HP 128GB SSD             | 1         | 1      | 4.76%   |
| Lenovo LENSE20512GMSP34MEAT2TA 512GB         | 1         | 1      | 4.76%   |
| Hitachi HTS547575A9E384 752GB                | 1         | 1      | 4.76%   |
| Fujitsu MJA2500BH G1 500GB                   | 1         | 1      | 4.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 28.57%  |
| WDC                 | 2         | 2      | 9.52%   |
| Samsung Electronics | 2         | 2      | 9.52%   |
| HGST                | 2         | 2      | 9.52%   |
| Toshiba             | 1         | 1      | 4.76%   |
| SanDisk             | 1         | 1      | 4.76%   |
| Origin              | 1         | 1      | 4.76%   |
| OCZ-VERTEX3         | 1         | 1      | 4.76%   |
| Micron Technology   | 1         | 1      | 4.76%   |
| LITEONIT            | 1         | 1      | 4.76%   |
| Lenovo              | 1         | 1      | 4.76%   |
| Hitachi             | 1         | 1      | 4.76%   |
| Fujitsu             | 1         | 1      | 4.76%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 6      | 46.15%  |
| WDC     | 2         | 2      | 15.38%  |
| HGST    | 2         | 2      | 15.38%  |
| Toshiba | 1         | 1      | 7.69%   |
| Hitachi | 1         | 1      | 7.69%   |
| Fujitsu | 1         | 1      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 13     | 61.9%   |
| SSD  | 7         | 7      | 33.33%  |
| NVMe | 1         | 1      | 4.76%   |

Failed Drives
-------------

Failed drive models

Zero info for selected period =(

Failed Drive Vendor
-------------------

Failed drive vendors

Zero info for selected period =(

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 332       | 460    | 56.27%  |
| Works    | 238       | 298    | 40.34%  |
| Malfunc  | 20        | 21     | 3.39%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 327       | 45.35%  |
| Samsung Electronics            | 104       | 14.42%  |
| AMD                            | 65        | 9.02%   |
| SanDisk                        | 56        | 7.77%   |
| SK hynix                       | 41        | 5.69%   |
| Toshiba America Info Systems   | 27        | 3.74%   |
| Micron Technology              | 21        | 2.91%   |
| Kingston Technology Company    | 13        | 1.8%    |
| ADATA Technology               | 12        | 1.66%   |
| KIOXIA                         | 11        | 1.53%   |
| Phison Electronics             | 10        | 1.39%   |
| Solid State Storage Technology | 7         | 0.97%   |
| Silicon Motion                 | 7         | 0.97%   |
| Union Memory (Shenzhen)        | 5         | 0.69%   |
| Micron/Crucial Technology      | 3         | 0.42%   |
| Lite-On Technology             | 3         | 0.42%   |
| Lenovo                         | 3         | 0.42%   |
| Marvell Technology Group       | 2         | 0.28%   |
| Unknown                        | 1         | 0.14%   |
| Realtek Semiconductor          | 1         | 0.14%   |
| Nvidia                         | 1         | 0.14%   |
| Biwin Storage Technology       | 1         | 0.14%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 62        | 8.26%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 47        | 6.26%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 45        | 5.99%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 32        | 4.26%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 31        | 4.13%   |
| Intel Volume Management Device NVMe RAID Controller                              | 29        | 3.86%   |
| Samsung NVMe SSD Controller 980                                                  | 28        | 3.73%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 23        | 3.06%   |
| Micron Non-Volatile memory controller                                            | 21        | 2.8%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 19        | 2.53%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 17        | 2.26%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 17        | 2.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 17        | 2.26%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 16        | 2.13%   |
| SanDisk Non-Volatile memory controller                                           | 16        | 2.13%   |
| SK hynix Gold P31 SSD                                                            | 15        | 2%      |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 14        | 1.86%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 13        | 1.73%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 12        | 1.6%    |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 11        | 1.46%   |
| Intel Tiger Lake-LP SATA Controller                                              | 11        | 1.46%   |
| Intel Non-Volatile memory controller                                             | 11        | 1.46%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 10        | 1.33%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 10        | 1.33%   |
| SK hynix BC511                                                                   | 9         | 1.2%    |
| Intel Comet Lake SATA AHCI Controller                                            | 9         | 1.2%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 8         | 1.07%   |
| Solid State Storage Non-Volatile memory controller                               | 7         | 0.93%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 7         | 0.93%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 7         | 0.93%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 7         | 0.93%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                      | 6         | 0.8%    |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 6         | 0.8%    |
| Intel SSD 660P Series                                                            | 6         | 0.8%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 6         | 0.8%    |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 5         | 0.67%   |
| SK hynix Non-Volatile memory controller                                          | 5         | 0.67%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 5         | 0.67%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 5         | 0.67%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 5         | 0.67%   |
| Phison E12 NVMe Controller                                                       | 5         | 0.67%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 5         | 0.67%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 5         | 0.67%   |
| ADATA Non-Volatile memory controller                                             | 5         | 0.67%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 4         | 0.53%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 4         | 0.53%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 4         | 0.53%   |
| SanDisk PC SN520 NVMe SSD                                                        | 4         | 0.53%   |
| Samsung Electronics SATA controller                                              | 4         | 0.53%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 4         | 0.53%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 4         | 0.53%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 4         | 0.53%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 4         | 0.53%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                             | 3         | 0.4%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 3         | 0.4%    |
| Lite-On Non-Volatile memory controller                                           | 3         | 0.4%    |
| Lenovo Non-Volatile memory controller                                            | 3         | 0.4%    |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 3         | 0.4%    |
| Kingston Company SNVS2000G [NV1 NVMe PCIe SSD 2TB]                               | 3         | 0.4%    |
| Kingston Company OM3PDP3 NVMe SSD                                                | 3         | 0.4%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 331       | 45.66%  |
| SATA | 326       | 44.97%  |
| RAID | 61        | 8.41%   |
| IDE  | 7         | 0.97%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 414       | 74.33%  |
| AMD     | 142       | 25.49%  |
| Unknown | 1         | 0.18%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 25        | 4.49%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 15        | 2.69%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 15        | 2.69%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 14        | 2.51%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 13        | 2.33%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 10        | 1.8%    |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 10        | 1.8%    |
| AMD Ryzen 5 5500U with Radeon Graphics        | 10        | 1.8%    |
| AMD Ryzen 7 5700U with Radeon Graphics        | 9         | 1.62%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 8         | 1.44%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 8         | 1.44%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 8         | 1.44%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 7         | 1.26%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 7         | 1.26%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 7         | 1.26%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 7         | 1.26%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 6         | 1.08%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 6         | 1.08%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 6         | 1.08%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 6         | 1.08%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 6         | 1.08%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 6         | 1.08%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 6         | 1.08%   |
| AMD Ryzen 5 5600U with Radeon Graphics        | 6         | 1.08%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 5         | 0.9%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 5         | 0.9%    |
| Intel Core i5-10300H CPU @ 2.50GHz            | 5         | 0.9%    |
| AMD Ryzen 9 6900HS with Radeon Graphics       | 5         | 0.9%    |
| AMD Ryzen 5 4600H with Radeon Graphics        | 5         | 0.9%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 4         | 0.72%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 4         | 0.72%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 4         | 0.72%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 4         | 0.72%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 0.72%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 4         | 0.72%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 4         | 0.72%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 0.72%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 4         | 0.72%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 4         | 0.72%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 4         | 0.72%   |
| AMD Ryzen 9 5900HS with Radeon Graphics       | 4         | 0.72%   |
| AMD Ryzen 7 PRO 5850U with Radeon Graphics    | 4         | 0.72%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 4         | 0.72%   |
| AMD Ryzen 7 5800U with Radeon Graphics        | 4         | 0.72%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 4         | 0.72%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 4         | 0.72%   |
| Intel Core i9-10885H CPU @ 2.40GHz            | 3         | 0.54%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 3         | 0.54%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 3         | 0.54%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 0.54%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 3         | 0.54%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 3         | 0.54%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 3         | 0.54%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 3         | 0.54%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 3         | 0.54%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 3         | 0.54%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 3         | 0.54%   |
| Intel Core i5-3360M CPU @ 2.80GHz             | 3         | 0.54%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 3         | 0.54%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 3         | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 145       | 26.03%  |
| Intel Core i5           | 126       | 22.62%  |
| Other                   | 73        | 13.11%  |
| AMD Ryzen 5             | 48        | 8.62%   |
| AMD Ryzen 7             | 38        | 6.82%   |
| Intel Core i3           | 31        | 5.57%   |
| AMD Ryzen 9             | 18        | 3.23%   |
| Intel Celeron           | 15        | 2.69%   |
| AMD Ryzen 7 PRO         | 12        | 2.15%   |
| AMD Ryzen 3             | 9         | 1.62%   |
| Intel Core 2 Duo        | 7         | 1.26%   |
| AMD A10                 | 7         | 1.26%   |
| Intel Pentium           | 5         | 0.9%    |
| Intel Pentium Silver    | 4         | 0.72%   |
| Intel Core i9           | 4         | 0.72%   |
| Intel Atom              | 4         | 0.72%   |
| AMD A8                  | 2         | 0.36%   |
| Intel Pentium Dual-Core | 1         | 0.18%   |
| Intel Core 2            | 1         | 0.18%   |
| AMD Ryzen 5 PRO         | 1         | 0.18%   |
| AMD PRO A8              | 1         | 0.18%   |
| AMD Phenom II           | 1         | 0.18%   |
| AMD E1                  | 1         | 0.18%   |
| AMD Athlon II Dual-Core | 1         | 0.18%   |
| AMD Athlon II           | 1         | 0.18%   |
| AMD A6                  | 1         | 0.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 224       | 40.22%  |
| 2      | 180       | 32.32%  |
| 8      | 79        | 14.18%  |
| 6      | 63        | 11.31%  |
| 14     | 7         | 1.26%   |
| 12     | 1         | 0.18%   |
| 10     | 1         | 0.18%   |
| 3      | 1         | 0.18%   |
| 1      | 1         | 0.18%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 557       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 498       | 89.41%  |
| 1      | 59        | 10.59%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 557       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806c1    | 52        | 9.32%   |
| 0x806ea    | 33        | 5.91%   |
| 0x306a9    | 33        | 5.91%   |
| 0x0a50000c | 29        | 5.2%    |
| 0x806ec    | 27        | 4.84%   |
| 0xa0652    | 26        | 4.66%   |
| 0x906ea    | 26        | 4.66%   |
| 0x206a7    | 26        | 4.66%   |
| 0x40651    | 23        | 4.12%   |
| 0x08108109 | 21        | 3.76%   |
| 0x806e9    | 18        | 3.23%   |
| 0x406e3    | 18        | 3.23%   |
| 0x306d4    | 18        | 3.23%   |
| Unknown    | 17        | 3.05%   |
| 0x08608103 | 16        | 2.87%   |
| 0x08600106 | 15        | 2.69%   |
| 0x306c3    | 12        | 2.15%   |
| 0x906e9    | 9         | 1.61%   |
| 0x08108102 | 9         | 1.61%   |
| 0x906a3    | 8         | 1.43%   |
| 0x506e3    | 8         | 1.43%   |
| 0x08600104 | 8         | 1.43%   |
| 0x706e5    | 7         | 1.25%   |
| 0x0a404101 | 7         | 1.25%   |
| 0x806eb    | 6         | 1.08%   |
| 0x806d1    | 6         | 1.08%   |
| 0x706a8    | 6         | 1.08%   |
| 0x08608102 | 5         | 0.9%    |
| 0x08600103 | 5         | 0.9%    |
| 0x506c9    | 4         | 0.72%   |
| 0x1067a    | 4         | 0.72%   |
| 0x906ed    | 3         | 0.54%   |
| 0x906c0    | 3         | 0.54%   |
| 0x706a1    | 3         | 0.54%   |
| 0x406c4    | 3         | 0.54%   |
| 0x30678    | 3         | 0.54%   |
| 0x20655    | 3         | 0.54%   |
| 0x106e5    | 3         | 0.54%   |
| 0x10676    | 3         | 0.54%   |
| 0x0600611a | 3         | 0.54%   |
| 0x806c2    | 2         | 0.36%   |
| 0x406c3    | 2         | 0.36%   |
| 0x20652    | 2         | 0.36%   |
| 0x0a50000b | 2         | 0.36%   |
| 0x0a404102 | 2         | 0.36%   |
| 0x0810100b | 2         | 0.36%   |
| 0x06001116 | 2         | 0.36%   |
| 0x010000c8 | 2         | 0.36%   |
| 0xa0660    | 1         | 0.18%   |
| 0x6f2      | 1         | 0.18%   |
| 0x106ca    | 1         | 0.18%   |
| 0x08200103 | 1         | 0.18%   |
| 0x08101016 | 1         | 0.18%   |
| 0x08001137 | 1         | 0.18%   |
| 0x07030105 | 1         | 0.18%   |
| 0x06006705 | 1         | 0.18%   |
| 0x06006118 | 1         | 0.18%   |
| 0x06006115 | 1         | 0.18%   |
| 0x06006110 | 1         | 0.18%   |
| 0x0500010d | 1         | 0.18%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 126       | 22.62%  |
| TigerLake        | 56        | 10.05%  |
| Haswell          | 35        | 6.28%   |
| IvyBridge        | 33        | 5.92%   |
| Zen 3            | 32        | 5.75%   |
| Unknown          | 31        | 5.57%   |
| Zen+             | 30        | 5.39%   |
| Zen 2            | 30        | 5.39%   |
| Skylake          | 28        | 5.03%   |
| CometLake        | 28        | 5.03%   |
| SandyBridge      | 26        | 4.67%   |
| Broadwell        | 18        | 3.23%   |
| IceLake          | 13        | 2.33%   |
| Goldmont plus    | 9         | 1.62%   |
| Silvermont       | 8         | 1.44%   |
| Penryn           | 8         | 1.44%   |
| Alderlake Hybrid | 8         | 1.44%   |
| Excavator        | 7         | 1.26%   |
| Westmere         | 6         | 1.08%   |
| Zen              | 5         | 0.9%    |
| Goldmont         | 4         | 0.72%   |
| Tremont          | 3         | 0.54%   |
| Nehalem          | 3         | 0.54%   |
| K10              | 3         | 0.54%   |
| Piledriver       | 2         | 0.36%   |
| Puma             | 1         | 0.18%   |
| K10 Llano        | 1         | 0.18%   |
| Core             | 1         | 0.18%   |
| Bonnell          | 1         | 0.18%   |
| Bobcat           | 1         | 0.18%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 389       | 52.36%  |
| Nvidia | 189       | 25.44%  |
| AMD    | 165       | 22.21%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 54        | 7.09%   |
| Intel UHD Graphics 620                                                                   | 35        | 4.59%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 31        | 4.07%   |
| AMD Renoir                                                                               | 30        | 3.94%   |
| AMD Cezanne                                                                              | 30        | 3.94%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 28        | 3.67%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 26        | 3.41%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 24        | 3.15%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 24        | 3.15%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 23        | 3.02%   |
| AMD Lucienne                                                                             | 21        | 2.76%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 18        | 2.36%   |
| Intel HD Graphics 620                                                                    | 18        | 2.36%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 17        | 2.23%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 16        | 2.1%    |
| Intel HD Graphics 5500                                                                   | 15        | 1.97%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 14        | 1.84%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 11        | 1.44%   |
| Nvidia GP108M [GeForce MX150]                                                            | 9         | 1.18%   |
| AMD Rembrandt [Radeon 680M]                                                              | 9         | 1.18%   |
| Intel HD Graphics 530                                                                    | 8         | 1.05%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 8         | 1.05%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 7         | 0.92%   |
| Nvidia TU117M                                                                            | 7         | 0.92%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 7         | 0.92%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 7         | 0.92%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 7         | 0.92%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 6         | 0.79%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 6         | 0.79%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 6         | 0.79%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 6         | 0.79%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 0.79%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 6         | 0.79%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 6         | 0.79%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 5         | 0.66%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 5         | 0.66%   |
| Nvidia GP108M [GeForce MX250]                                                            | 5         | 0.66%   |
| Intel HD Graphics 630                                                                    | 5         | 0.66%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 0.66%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 0.66%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 0.52%   |
| Nvidia GM108M [GeForce 840M]                                                             | 4         | 0.52%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 4         | 0.52%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                                 | 4         | 0.52%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 0.52%   |
| Nvidia TU117GLM [Quadro T500 Mobile]                                                     | 3         | 0.39%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 3         | 0.39%   |
| Nvidia GM108M [GeForce MX130]                                                            | 3         | 0.39%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 3         | 0.39%   |
| Nvidia GK107M [GeForce GT 650M]                                                          | 3         | 0.39%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 0.39%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 0.39%   |
| Intel JasperLake [UHD Graphics]                                                          | 3         | 0.39%   |
| Intel HD Graphics 500                                                                    | 3         | 0.39%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 3         | 0.39%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 0.39%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 3         | 0.39%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 0.39%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                                     | 3         | 0.39%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 3         | 0.39%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 228       | 40.93%  |
| Intel + Nvidia | 141       | 25.31%  |
| 1 x AMD        | 105       | 18.85%  |
| AMD + Nvidia   | 26        | 4.67%   |
| 1 x Nvidia     | 21        | 3.77%   |
| Intel + AMD    | 18        | 3.23%   |
| 2 x AMD        | 16        | 2.87%   |
| Other          | 1         | 0.18%   |
| 2 x Nvidia     | 1         | 0.18%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 474       | 84.79%  |
| Proprietary | 80        | 14.31%  |
| Unknown     | 5         | 0.89%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 293       | 52.42%  |
| 1.01-2.0   | 93        | 16.64%  |
| 0.01-0.5   | 82        | 14.67%  |
| 3.01-4.0   | 45        | 8.05%   |
| 0.51-1.0   | 23        | 4.11%   |
| 7.01-8.0   | 8         | 1.43%   |
| 5.01-6.0   | 8         | 1.43%   |
| 2.01-3.0   | 4         | 0.72%   |
| 8.01-16.0  | 3         | 0.54%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 140       | 20.83%  |
| BOE                     | 113       | 16.82%  |
| Chimei Innolux          | 86        | 12.8%   |
| LG Display              | 83        | 12.35%  |
| Samsung Electronics     | 42        | 6.25%   |
| Dell                    | 28        | 4.17%   |
| Sharp                   | 24        | 3.57%   |
| Goldstar                | 23        | 3.42%   |
| Lenovo                  | 15        | 2.23%   |
| Apple                   | 14        | 2.08%   |
| PANDA                   | 13        | 1.93%   |
| CSO                     | 12        | 1.79%   |
| Philips                 | 11        | 1.64%   |
| Hewlett-Packard         | 11        | 1.64%   |
| Chi Mei Optoelectronics | 8         | 1.19%   |
| TMX                     | 6         | 0.89%   |
| InfoVision              | 6         | 0.89%   |
| ViewSonic               | 5         | 0.74%   |
| BenQ                    | 5         | 0.74%   |
| Ancor Communications    | 4         | 0.6%    |
| Acer                    | 3         | 0.45%   |
| Vizio                   | 2         | 0.3%    |
| SKY                     | 2         | 0.3%    |
| MSI                     | 2         | 0.3%    |
| Toshiba                 | 1         | 0.15%   |
| Sceptre Tech            | 1         | 0.15%   |
| ONN                     | 1         | 0.15%   |
| LG Philips              | 1         | 0.15%   |
| JDI                     | 1         | 0.15%   |
| Insignia                | 1         | 0.15%   |
| Iiyama                  | 1         | 0.15%   |
| HKC                     | 1         | 0.15%   |
| HannStar                | 1         | 0.15%   |
| Eizo                    | 1         | 0.15%   |
| ASUSTek Computer        | 1         | 0.15%   |
| Aosiman                 | 1         | 0.15%   |
| AOC                     | 1         | 0.15%   |
| Unknown                 | 1         | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 8         | 1.17%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 7         | 1.02%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 6         | 0.87%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 6         | 0.87%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                     | 6         | 0.87%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch            | 6         | 0.87%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch            | 5         | 0.73%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 5         | 0.73%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch            | 5         | 0.73%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch              | 4         | 0.58%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                         | 4         | 0.58%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 4         | 0.58%   |
| Chimei Innolux LCD Monitor CMN1540 2560x1440 344x193mm 15.5-inch          | 4         | 0.58%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch          | 4         | 0.58%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch          | 4         | 0.58%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                     | 4         | 0.58%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                      | 4         | 0.58%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch            | 4         | 0.58%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch                   | 3         | 0.44%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                   | 3         | 0.44%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch                   | 3         | 0.44%   |
| LG Display LCD Monitor LGD056D 1920x1080 382x215mm 17.3-inch              | 3         | 0.44%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch               | 3         | 0.44%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch          | 3         | 0.44%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 3         | 0.44%   |
| Chimei Innolux LCD Monitor CMN14C8 1920x1080 309x173mm 13.9-inch          | 3         | 0.44%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch           | 3         | 0.44%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 3         | 0.44%   |
| BOE LCD Monitor BOE0A1D 2560x1600 302x189mm 14.0-inch                     | 3         | 0.44%   |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch            | 3         | 0.44%   |
| AU Optronics LCD Monitor AUO6496 1920x1200 286x178mm 13.3-inch            | 3         | 0.44%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch            | 3         | 0.44%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch            | 3         | 0.44%   |
| AU Optronics LCD Monitor AUO5A2D 1920x1080 293x165mm 13.2-inch            | 3         | 0.44%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 309x174mm 14.0-inch            | 3         | 0.44%   |
| AU Optronics LCD Monitor AUO11EC 1366x768 344x193mm 15.5-inch             | 3         | 0.44%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch             | 3         | 0.44%   |
| ViewSonic VA2719-2K VSC6B34 2560x1440 597x336mm 27.0-inch                 | 2         | 0.29%   |
| TMX TL156MDMP11-0 TMX1560 3200x2000 336x210mm 15.6-inch                   | 2         | 0.29%   |
| SKY TV-PHILCO SKY0104 1920x1080 885x498mm 40.0-inch                       | 2         | 0.29%   |
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch                   | 2         | 0.29%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                   | 2         | 0.29%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                   | 2         | 0.29%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch                   | 2         | 0.29%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 2         | 0.29%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 294x165mm 13.3-inch     | 2         | 0.29%   |
| Samsung Electronics LCD Monitor SDC4150 3456x2160 336x210mm 15.6-inch     | 2         | 0.29%   |
| Samsung Electronics LCD Monitor SDC414D 3456x2160 336x210mm 15.6-inch     | 2         | 0.29%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch         | 2         | 0.29%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch                  | 2         | 0.29%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch                   | 2         | 0.29%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch              | 2         | 0.29%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch              | 2         | 0.29%   |
| LG Display LCD Monitor LGD059E 1920x1080 382x215mm 17.3-inch              | 2         | 0.29%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch              | 2         | 0.29%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch              | 2         | 0.29%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch               | 2         | 0.29%   |
| LG Display LCD Monitor LGD036C 1366x768 277x156mm 12.5-inch               | 2         | 0.29%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 2         | 0.29%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch               | 2         | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 340       | 54.05%  |
| 1366x768 (WXGA)   | 105       | 16.69%  |
| 3840x2160 (4K)    | 31        | 4.93%   |
| 2560x1440 (QHD)   | 29        | 4.61%   |
| 1920x1200 (WUXGA) | 28        | 4.45%   |
| 1600x900 (HD+)    | 19        | 3.02%   |
| 2560x1600         | 10        | 1.59%   |
| 3440x1440         | 7         | 1.11%   |
| 1280x800 (WXGA)   | 7         | 1.11%   |
| 3840x2400         | 6         | 0.95%   |
| 2256x1504         | 6         | 0.95%   |
| 2160x1440         | 6         | 0.95%   |
| 1280x1024 (SXGA)  | 6         | 0.95%   |
| 3456x2160         | 5         | 0.79%   |
| 2880x1800         | 5         | 0.79%   |
| 2560x1080         | 4         | 0.64%   |
| 1440x900 (WXGA+)  | 4         | 0.64%   |
| 3200x2000         | 2         | 0.32%   |
| 2240x1400         | 2         | 0.32%   |
| 3840x1600         | 1         | 0.16%   |
| 3200x1800 (QHD+)  | 1         | 0.16%   |
| 3000x2000         | 1         | 0.16%   |
| 1920x550          | 1         | 0.16%   |
| 1360x768          | 1         | 0.16%   |
| 1024x768 (XGA)    | 1         | 0.16%   |
| 1024x600          | 1         | 0.16%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 253       | 37.43%  |
| 14      | 113       | 16.72%  |
| 13      | 111       | 16.42%  |
| 17      | 38        | 5.62%   |
| 27      | 32        | 4.73%   |
| 24      | 25        | 3.7%    |
| 21      | 18        | 2.66%   |
| 23      | 15        | 2.22%   |
| 12      | 13        | 1.92%   |
| 31      | 12        | 1.78%   |
| 34      | 10        | 1.48%   |
| 16      | 9         | 1.33%   |
| 11      | 6         | 0.89%   |
| 18      | 4         | 0.59%   |
| 40      | 3         | 0.44%   |
| 19      | 3         | 0.44%   |
| 10      | 2         | 0.3%    |
| Unknown | 2         | 0.3%    |
| 84      | 1         | 0.15%   |
| 39      | 1         | 0.15%   |
| 37      | 1         | 0.15%   |
| 29      | 1         | 0.15%   |
| 26      | 1         | 0.15%   |
| 25      | 1         | 0.15%   |
| 20      | 1         | 0.15%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 426       | 63.49%  |
| 201-300     | 75        | 11.18%  |
| 501-600     | 68        | 10.13%  |
| 351-400     | 45        | 6.71%   |
| 401-500     | 24        | 3.58%   |
| 601-700     | 15        | 2.24%   |
| 701-800     | 9         | 1.34%   |
| 801-900     | 6         | 0.89%   |
| Unknown     | 2         | 0.3%    |
| 1501-2000   | 1         | 0.15%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 478       | 82.13%  |
| 16/10   | 70        | 12.03%  |
| 3/2     | 13        | 2.23%   |
| 21/9    | 12        | 2.06%   |
| 5/4     | 5         | 0.86%   |
| 4/3     | 2         | 0.34%   |
| 32/9    | 1         | 0.17%   |
| Unknown | 1         | 0.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 255       | 37.78%  |
| 81-90          | 182       | 26.96%  |
| 201-250        | 42        | 6.22%   |
| 71-80          | 41        | 6.07%   |
| 301-350        | 34        | 5.04%   |
| 121-130        | 34        | 5.04%   |
| 351-500        | 20        | 2.96%   |
| 251-300        | 14        | 2.07%   |
| 61-70          | 12        | 1.78%   |
| 151-200        | 8         | 1.19%   |
| 111-120        | 7         | 1.04%   |
| 51-60          | 6         | 0.89%   |
| 141-150        | 6         | 0.89%   |
| 501-1000       | 5         | 0.74%   |
| 131-140        | 3         | 0.44%   |
| 41-50          | 2         | 0.3%    |
| Unknown        | 2         | 0.3%    |
| More than 1000 | 1         | 0.15%   |
| 91-100         | 1         | 0.15%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 331       | 50.08%  |
| 101-120       | 128       | 19.36%  |
| 161-240       | 82        | 12.41%  |
| 51-100        | 80        | 12.1%   |
| More than 240 | 37        | 5.6%    |
| Unknown       | 2         | 0.3%    |
| 1-50          | 1         | 0.15%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 434       | 77.36%  |
| 2     | 103       | 18.36%  |
| 3     | 11        | 1.96%   |
| 0     | 8         | 1.43%   |
| 4     | 4         | 0.71%   |
| 5     | 1         | 0.18%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 315       | 38.65%  |
| Realtek Semiconductor             | 291       | 35.71%  |
| Qualcomm Atheros                  | 79        | 9.69%   |
| MediaTek                          | 31        | 3.8%    |
| Broadcom                          | 31        | 3.8%    |
| Broadcom Limited                  | 10        | 1.23%   |
| Lenovo                            | 7         | 0.86%   |
| TP-Link                           | 6         | 0.74%   |
| Sierra Wireless                   | 5         | 0.61%   |
| Ralink                            | 4         | 0.49%   |
| Qualcomm                          | 4         | 0.49%   |
| Samsung Electronics               | 3         | 0.37%   |
| Ralink Technology                 | 3         | 0.37%   |
| ASIX Electronics                  | 3         | 0.37%   |
| Marvell Technology Group          | 2         | 0.25%   |
| Fibocom                           | 2         | 0.25%   |
| Ericsson Business Mobile Networks | 2         | 0.25%   |
| D-Link                            | 2         | 0.25%   |
| Belkin Components                 | 2         | 0.25%   |
| Xiaomi                            | 1         | 0.12%   |
| OPPO Electronics                  | 1         | 0.12%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.12%   |
| Nvidia                            | 1         | 0.12%   |
| MicroPython                       | 1         | 0.12%   |
| Linksys                           | 1         | 0.12%   |
| Huawei Technologies               | 1         | 0.12%   |
| Hewlett-Packard                   | 1         | 0.12%   |
| Edimax Technology                 | 1         | 0.12%   |
| DisplayLink                       | 1         | 0.12%   |
| Dell                              | 1         | 0.12%   |
| ASUSTek Computer                  | 1         | 0.12%   |
| Adafruit                          | 1         | 0.12%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 170       | 16.92%  |
| Intel Wi-Fi 6 AX201                                               | 41        | 4.08%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 39        | 3.88%   |
| Intel Wi-Fi 6 AX200                                               | 36        | 3.58%   |
| Intel Wireless 8265 / 8275                                        | 29        | 2.89%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 28        | 2.79%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 27        | 2.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 24        | 2.39%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 23        | 2.29%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 23        | 2.29%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 21        | 2.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 21        | 2.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 18        | 1.79%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 15        | 1.49%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 15        | 1.49%   |
| Intel Wireless 7265                                               | 14        | 1.39%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 14        | 1.39%   |
| Intel Wireless 8260                                               | 13        | 1.29%   |
| Intel Wireless 7260                                               | 13        | 1.29%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 12        | 1.19%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 11        | 1.09%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 10        | 1%      |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 10        | 1%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 10        | 1%      |
| Intel Ethernet Connection (4) I219-LM                             | 10        | 1%      |
| Intel Centrino Ultimate-N 6300                                    | 10        | 1%      |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 10        | 1%      |
| Intel Wireless-AC 9260                                            | 9         | 0.9%    |
| Intel Ethernet Connection (4) I219-V                              | 8         | 0.8%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 8         | 0.8%    |
| Realtek RTL8125 2.5GbE Controller                                 | 7         | 0.7%    |
| Intel Wireless 3165                                               | 7         | 0.7%    |
| Intel Wireless 3160                                               | 7         | 0.7%    |
| Intel Ethernet Connection I218-LM                                 | 7         | 0.7%    |
| Intel Ethernet Connection (13) I219-V                             | 7         | 0.7%    |
| Intel Ethernet Connection I219-LM                                 | 6         | 0.6%    |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 6         | 0.6%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 0.5%    |
| MediaTek WLAN controller                                          | 5         | 0.5%    |
| Intel Tiger Lake PCH CNVi WiFi                                    | 5         | 0.5%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 5         | 0.5%    |
| Intel Gemini Lake PCH CNVi WiFi                                   | 5         | 0.5%    |
| Intel Ethernet Connection (7) I219-LM                             | 5         | 0.5%    |
| Intel Ethernet Connection (2) I219-LM                             | 5         | 0.5%    |
| Intel Ethernet Connection (10) I219-V                             | 5         | 0.5%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 5         | 0.5%    |
| Broadcom BCM43228 802.11a/b/g/n                                   | 5         | 0.5%    |
| Broadcom BCM43142 802.11b/g/n                                     | 5         | 0.5%    |
| Realtek RTL8723DE Wireless Network Adapter                        | 4         | 0.4%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 4         | 0.4%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 4         | 0.4%    |
| Intel Ethernet Connection I217-LM                                 | 4         | 0.4%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4         | 0.4%    |
| Intel Centrino Advanced-N 6235                                    | 4         | 0.4%    |
| Intel 82577LM Gigabit Network Connection                          | 4         | 0.4%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 4         | 0.4%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 0.3%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 0.3%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 0.3%    |
| Lenovo ThinkPad Lan                                               | 3         | 0.3%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 303       | 52.6%   |
| Realtek Semiconductor | 106       | 18.4%   |
| Qualcomm Atheros      | 71        | 12.33%  |
| MediaTek              | 31        | 5.38%   |
| Broadcom              | 28        | 4.86%   |
| Broadcom Limited      | 8         | 1.39%   |
| TP-Link               | 5         | 0.87%   |
| Sierra Wireless       | 5         | 0.87%   |
| Ralink                | 4         | 0.69%   |
| Qualcomm              | 4         | 0.69%   |
| Ralink Technology     | 3         | 0.52%   |
| Fibocom               | 2         | 0.35%   |
| Belkin Components     | 2         | 0.35%   |
| Linksys               | 1         | 0.17%   |
| Edimax Technology     | 1         | 0.17%   |
| D-Link                | 1         | 0.17%   |
| ASUSTek Computer      | 1         | 0.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                            | 41        | 7.09%   |
| Intel Wi-Fi 6 AX200                                            | 36        | 6.23%   |
| Intel Wireless 8265 / 8275                                     | 29        | 5.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 27        | 4.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 24        | 4.15%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 23        | 3.98%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 23        | 3.98%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 21        | 3.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 18        | 3.11%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 15        | 2.6%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 15        | 2.6%    |
| Intel Wireless 7265                                            | 14        | 2.42%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 14        | 2.42%   |
| Intel Wireless 8260                                            | 13        | 2.25%   |
| Intel Wireless 7260                                            | 13        | 2.25%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 12        | 2.08%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 11        | 1.9%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 10        | 1.73%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 10        | 1.73%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 10        | 1.73%   |
| Intel Centrino Ultimate-N 6300                                 | 10        | 1.73%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 10        | 1.73%   |
| Intel Wireless-AC 9260                                         | 9         | 1.56%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 8         | 1.38%   |
| Intel Wireless 3165                                            | 7         | 1.21%   |
| Intel Wireless 3160                                            | 7         | 1.21%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 6         | 1.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 5         | 0.87%   |
| MediaTek WLAN controller                                       | 5         | 0.87%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 5         | 0.87%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 5         | 0.87%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 5         | 0.87%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 5         | 0.87%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 5         | 0.87%   |
| Broadcom BCM43142 802.11b/g/n                                  | 5         | 0.87%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 4         | 0.69%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 4         | 0.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 4         | 0.69%   |
| Intel Centrino Advanced-N 6235                                 | 4         | 0.69%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 4         | 0.69%   |
| Intel WiFi Link 5100                                           | 3         | 0.52%   |
| Intel Centrino Wireless-N 2230                                 | 3         | 0.52%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 3         | 0.52%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 3         | 0.52%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 2         | 0.35%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 2         | 0.35%   |
| Sierra Wireless EM7455                                         | 2         | 0.35%   |
| Sierra Wireless EM7305 Modem                                   | 2         | 0.35%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 2         | 0.35%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 2         | 0.35%   |
| Realtek 802.11ac NIC                                           | 2         | 0.35%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 2         | 0.35%   |
| Qualcomm QCA6390 Wireless Network Adapter                      | 2         | 0.35%   |
| Fibocom L830-EB-00 LTE WWAN Modem                              | 2         | 0.35%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 2         | 0.35%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter     | 2         | 0.35%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter             | 2         | 0.35%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 2         | 0.35%   |
| TP-Link 802.11ac WLAN Adapter                                  | 1         | 0.17%   |
| Sierra Wireless EM7345 4G LTE                                  | 1         | 0.17%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 246       | 59.56%  |
| Intel                    | 116       | 28.09%  |
| Qualcomm Atheros         | 17        | 4.12%   |
| Broadcom                 | 8         | 1.94%   |
| Lenovo                   | 7         | 1.69%   |
| Samsung Electronics      | 3         | 0.73%   |
| ASIX Electronics         | 3         | 0.73%   |
| TP-Link                  | 2         | 0.48%   |
| Marvell Technology Group | 2         | 0.48%   |
| Broadcom Limited         | 2         | 0.48%   |
| Xiaomi                   | 1         | 0.24%   |
| OPPO Electronics         | 1         | 0.24%   |
| Nvidia                   | 1         | 0.24%   |
| Huawei Technologies      | 1         | 0.24%   |
| Hewlett-Packard          | 1         | 0.24%   |
| DisplayLink              | 1         | 0.24%   |
| D-Link                   | 1         | 0.24%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 170       | 40.38%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 39        | 9.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 28        | 6.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 21        | 4.99%   |
| Intel Ethernet Connection (4) I219-LM                             | 10        | 2.38%   |
| Intel Ethernet Connection (4) I219-V                              | 8         | 1.9%    |
| Realtek RTL8125 2.5GbE Controller                                 | 7         | 1.66%   |
| Intel Ethernet Connection I218-LM                                 | 7         | 1.66%   |
| Intel Ethernet Connection (13) I219-V                             | 7         | 1.66%   |
| Intel Ethernet Connection I219-LM                                 | 6         | 1.43%   |
| Intel Ethernet Connection (7) I219-LM                             | 5         | 1.19%   |
| Intel Ethernet Connection (2) I219-LM                             | 5         | 1.19%   |
| Intel Ethernet Connection (10) I219-V                             | 5         | 1.19%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 4         | 0.95%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 0.95%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 0.95%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 0.71%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 0.71%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 0.71%   |
| Lenovo ThinkPad Lan                                               | 3         | 0.71%   |
| Intel Ethernet Connection (6) I219-LM                             | 3         | 0.71%   |
| Intel Ethernet Connection (13) I219-LM                            | 3         | 0.71%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 0.71%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 0.71%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 2         | 0.48%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 0.48%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.48%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.48%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.48%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.48%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.48%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.48%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.48%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 2         | 0.48%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.48%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.48%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 0.48%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.48%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 0.48%   |
| Intel Ethernet Connection (11) I219-LM                            | 2         | 0.48%   |
| Intel Ethernet Connection (10) I219-LM                            | 2         | 0.48%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 0.48%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.24%   |
| OPPO SDM720G-IDP _SN:B922E265                                     | 1         | 0.24%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.24%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.24%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.24%   |
| Lenovo USB-C Hub                                                  | 1         | 0.24%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 0.24%   |
| Intel WiMAX Connection 2400m                                      | 1         | 0.24%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.24%   |
| Intel Ethernet Controller I225-V                                  | 1         | 0.24%   |
| Intel Ethernet controller                                         | 1         | 0.24%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.24%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.24%   |
| Intel Ethernet Connection (5) I219-V                              | 1         | 0.24%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 0.24%   |
| Intel Ethernet Connection (16) I219-V                             | 1         | 0.24%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 0.24%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 0.24%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 551       | 57.82%  |
| Ethernet | 396       | 41.55%  |
| Modem    | 5         | 0.52%   |
| Unknown  | 1         | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 489       | 82.74%  |
| Ethernet | 102       | 17.26%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 349       | 62.66%  |
| 1     | 191       | 34.29%  |
| 3     | 10        | 1.8%    |
| 0     | 7         | 1.26%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 423       | 75.67%  |
| Yes  | 136       | 24.33%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 259       | 51.7%   |
| Realtek Semiconductor           | 72        | 14.37%  |
| Qualcomm Atheros Communications | 42        | 8.38%   |
| IMC Networks                    | 28        | 5.59%   |
| Foxconn / Hon Hai               | 24        | 4.79%   |
| Broadcom                        | 23        | 4.59%   |
| Lite-On Technology              | 14        | 2.79%   |
| Apple                           | 12        | 2.4%    |
| Realtek                         | 5         | 1%      |
| Cambridge Silicon Radio         | 5         | 1%      |
| Ralink                          | 4         | 0.8%    |
| Dell                            | 4         | 0.8%    |
| Toshiba                         | 2         | 0.4%    |
| Hewlett-Packard                 | 2         | 0.4%    |
| ASUSTek Computer                | 2         | 0.4%    |
| USI                             | 1         | 0.2%    |
| Qcom                            | 1         | 0.2%    |
| Opticis                         | 1         | 0.2%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 80        | 15.97%  |
| Intel AX201 Bluetooth                                                               | 63        | 12.57%  |
| Realtek Bluetooth Radio                                                             | 49        | 9.78%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 42        | 8.38%   |
| Intel AX200 Bluetooth                                                               | 36        | 7.19%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 30        | 5.99%   |
| Intel AX210 Bluetooth                                                               | 15        | 2.99%   |
| Intel Bluetooth Device                                                              | 14        | 2.79%   |
| IMC Networks Wireless_Device                                                        | 14        | 2.79%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 13        | 2.59%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 10        | 2%      |
| IMC Networks Bluetooth Radio                                                        | 7         | 1.4%    |
| Broadcom BCM2045B (BDC-2.1)                                                         | 7         | 1.4%    |
| Apple Bluetooth Host Controller                                                     | 7         | 1.4%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 6         | 1.2%    |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 6         | 1.2%    |
| Realtek Bluetooth Radio                                                             | 5         | 1%      |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 5         | 1%      |
| Lite-On Wireless_Device                                                             | 5         | 1%      |
| Foxconn / Hon Hai Bluetooth Device                                                  | 5         | 1%      |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 5         | 1%      |
| Broadcom HP Portable SoftSailing                                                    | 5         | 1%      |
| Ralink RT3290 Bluetooth                                                             | 4         | 0.8%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 4         | 0.8%    |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 3         | 0.6%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 0.6%    |
| Lite-On Bluetooth Device                                                            | 3         | 0.6%    |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 0.6%    |
| Apple Bluetooth USB Host Controller                                                 | 3         | 0.6%    |
| Realtek RTL8821A Bluetooth                                                          | 2         | 0.4%    |
| Realtek RTL8723B Bluetooth                                                          | 2         | 0.4%    |
| Qualcomm Atheros Bluetooth                                                          | 2         | 0.4%    |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 0.4%    |
| IMC Networks Bluetooth Device                                                       | 2         | 0.4%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 0.4%    |
| Foxconn / Hon Hai BCM20702A0                                                        | 2         | 0.4%    |
| Dell DW375 Bluetooth Module                                                         | 2         | 0.4%    |
| Broadcom BCM43142A0 Bluetooth Device                                                | 2         | 0.4%    |
| Broadcom BCM2045A0                                                                  | 2         | 0.4%    |
| USI Bluetooth Device                                                                | 1         | 0.2%    |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.2%    |
| Toshiba Bluetooth USB Host Controller                                               | 1         | 0.2%    |
| Qcom Bluetooth USB                                                                  | 1         | 0.2%    |
| Opticis Bluetooth Radio                                                             | 1         | 0.2%    |
| Lite-On Bluetooth Radio                                                             | 1         | 0.2%    |
| Lite-On Atheros Bluetooth                                                           | 1         | 0.2%    |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 0.2%    |
| IMC Networks BCM20702A0                                                             | 1         | 0.2%    |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.2%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.2%    |
| Foxconn / Hon Hai BT                                                                | 1         | 0.2%    |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth                                       | 1         | 0.2%    |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.2%    |
| Foxconn / Hon Hai BCM43142A0                                                        | 1         | 0.2%    |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 1         | 0.2%    |
| Dell Wireless 370 Bluetooth Mini-card                                               | 1         | 0.2%    |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 0.2%    |
| Broadcom HP Portable Valentine                                                      | 1         | 0.2%    |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.2%    |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 0.2%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 410       | 57.26%  |
| AMD                         | 148       | 20.67%  |
| Nvidia                      | 102       | 14.25%  |
| Lenovo                      | 7         | 0.98%   |
| Hewlett-Packard             | 6         | 0.84%   |
| GN Netcom                   | 6         | 0.84%   |
| Realtek Semiconductor       | 5         | 0.7%    |
| C-Media Electronics         | 5         | 0.7%    |
| Plantronics                 | 4         | 0.56%   |
| Texas Instruments           | 2         | 0.28%   |
| No brand                    | 2         | 0.28%   |
| Focusrite-Novation          | 2         | 0.28%   |
| Conexant Systems            | 2         | 0.28%   |
| XMOS                        | 1         | 0.14%   |
| Sony                        | 1         | 0.14%   |
| Sennheiser Communications   | 1         | 0.14%   |
| Samsung Electronics         | 1         | 0.14%   |
| Samson Technologies         | 1         | 0.14%   |
| RODE Microphones            | 1         | 0.14%   |
| Razer USA                   | 1         | 0.14%   |
| Logitech                    | 1         | 0.14%   |
| FiiO Electronics Technology | 1         | 0.14%   |
| fifinemicrophone.com        | 1         | 0.14%   |
| FIFINE Microphones          | 1         | 0.14%   |
| Creative Technology         | 1         | 0.14%   |
| Corsair                     | 1         | 0.14%   |
| Cooler Master               | 1         | 0.14%   |
| AOKEO                       | 1         | 0.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 122       | 13.54%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 74        | 8.21%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 71        | 7.88%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 56        | 6.22%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 39        | 4.33%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 33        | 3.66%   |
| Intel Cannon Lake PCH cAVS                                                                        | 29        | 3.22%   |
| Intel Comet Lake PCH cAVS                                                                         | 26        | 2.89%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 23        | 2.55%   |
| Intel 8 Series HD Audio Controller                                                                | 23        | 2.55%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 20        | 2.22%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 18        | 2%      |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 18        | 2%      |
| Intel Broadwell-U Audio Controller                                                                | 18        | 2%      |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 17        | 1.89%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 17        | 1.89%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 13        | 1.44%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 12        | 1.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 11        | 1.22%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 9         | 1%      |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 9         | 1%      |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 9         | 1%      |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 9         | 1%      |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 9         | 1%      |
| Intel CM238 HD Audio Controller                                                                   | 8         | 0.89%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 8         | 0.89%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 7         | 0.78%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 7         | 0.78%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 7         | 0.78%   |
| AMD Kabini HDMI/DP Audio                                                                          | 7         | 0.78%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 7         | 0.78%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 6         | 0.67%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 6         | 0.67%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 0.67%   |
| Hewlett-Packard USB Audio                                                                         | 6         | 0.67%   |
| Realtek Semiconductor USB Audio                                                                   | 5         | 0.55%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 5         | 0.55%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 5         | 0.55%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 5         | 0.55%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 5         | 0.55%   |
| AMD FCH Azalia Controller                                                                         | 5         | 0.55%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 4         | 0.44%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 4         | 0.44%   |
| Nvidia Audio device                                                                               | 4         | 0.44%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4         | 0.44%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.33%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                                      | 3         | 0.33%   |
| Intel Jasper Lake HD Audio                                                                        | 3         | 0.33%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.33%   |
| C-Media Electronics USB Audio Device                                                              | 3         | 0.33%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 3         | 0.33%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 0.33%   |
| Plantronics Blackwire 325.1                                                                       | 2         | 0.22%   |
| Nvidia TU104 HD Audio Controller                                                                  | 2         | 0.22%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 0.22%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 2         | 0.22%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 0.22%   |
| Lenovo ThinkPad Dock USB Audio                                                                    | 2         | 0.22%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 0.22%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 0.22%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 98        | 30.06%  |
| SK hynix            | 76        | 23.31%  |
| Micron Technology   | 50        | 15.34%  |
| Crucial             | 21        | 6.44%   |
| Kingston            | 18        | 5.52%   |
| Ramaxel Technology  | 12        | 3.68%   |
| Unknown             | 11        | 3.37%   |
| A-DATA Technology   | 6         | 1.84%   |
| Unknown (ABCD)      | 5         | 1.53%   |
| Smart               | 4         | 1.23%   |
| G.Skill             | 4         | 1.23%   |
| Team                | 3         | 0.92%   |
| Patriot             | 3         | 0.92%   |
| Nanya Technology    | 3         | 0.92%   |
| Unknown             | 2         | 0.61%   |
| Silicon Power       | 1         | 0.31%   |
| Sesame              | 1         | 0.31%   |
| Qimonda             | 1         | 0.31%   |
| Neo Forza           | 1         | 0.31%   |
| Kllisre             | 1         | 0.31%   |
| Hikvision           | 1         | 0.31%   |
| Goldkey             | 1         | 0.31%   |
| Elpida              | 1         | 0.31%   |
| Corsair             | 1         | 0.31%   |
| Atermiter           | 1         | 0.31%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 9         | 2.61%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s         | 6         | 1.74%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 1.74%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 6         | 1.74%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 5         | 1.45%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 1.45%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 5         | 1.45%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 5         | 1.45%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 5         | 1.45%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 4         | 1.16%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 3         | 0.87%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.87%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.87%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 0.87%   |
| Samsung RAM M471A1K43EB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 3         | 0.87%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 0.87%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 3         | 0.87%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 2         | 0.58%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 2         | 0.58%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 2         | 0.58%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s            | 2         | 0.58%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.58%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.58%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.58%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s          | 2         | 0.58%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.58%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 2         | 0.58%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 0.58%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2400MT/s        | 2         | 0.58%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 0.58%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.58%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.58%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s       | 2         | 0.58%   |
| SK hynix RAM H9CCNNNBJTALAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s | 2         | 0.58%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 2         | 0.58%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 2         | 0.58%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.58%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.58%   |
| Samsung RAM M471B1G73BH0-CK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.58%   |
| Samsung RAM M471A5244CB0-CWE 4096MB Row Of Chips DDR4 3200MT/s   | 2         | 0.58%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 0.58%   |
| Samsung RAM M471A2K43CB1-CRC 16384MB SODIMM DDR4 2667MT/s        | 2         | 0.58%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.58%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 2         | 0.58%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM 4800MT/s               | 2         | 0.58%   |
| Ramaxel RAM RMSA3320MJ78HAF-3200 8GB SODIMM DDR4 3200MT/s        | 2         | 0.58%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.58%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 2         | 0.58%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 2         | 0.58%   |
| Micron RAM 4ATF1G64HZ-3G2B1 8GB Row Of Chips DDR4 3200MT/s       | 2         | 0.58%   |
| Micron RAM 16JSF25664HZ-1G1F1 2GB SODIMM DDR3 1067MT/s           | 2         | 0.58%   |
| Kingston RAM KHX2666C15S4/8G 8GB SODIMM DDR4 2667MT/s            | 2         | 0.58%   |
| Crucial RAM CT16G4SFRA32A.M16FRS 16GB SODIMM DDR4 3200MT/s       | 2         | 0.58%   |
| A-DATA RAM AO1P32NC8W1-BD2SHC 8GB SODIMM DDR4 3200MT/s           | 2         | 0.58%   |
| Unknown                                                          | 2         | 0.58%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                      | 1         | 0.29%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                      | 1         | 0.29%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 0.29%   |
| Unknown RAM Module 4GB SODIMM DDR3 1066MT/s                      | 1         | 0.29%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 156       | 58.21%  |
| DDR3    | 60        | 22.39%  |
| LPDDR4  | 23        | 8.58%   |
| LPDDR3  | 15        | 5.6%    |
| Unknown | 9         | 3.36%   |
| LPDDR5  | 3         | 1.12%   |
| DDR2    | 2         | 0.75%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 230       | 82.44%  |
| Row Of Chips | 45        | 16.13%  |
| Chip         | 3         | 1.08%   |
| Unknown      | 1         | 0.36%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 121       | 41.58%  |
| 4096  | 97        | 33.33%  |
| 16384 | 43        | 14.78%  |
| 2048  | 14        | 4.81%   |
| 32768 | 13        | 4.47%   |
| 1024  | 2         | 0.69%   |
| 3072  | 1         | 0.34%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 82        | 28.47%  |
| 2667    | 61        | 21.18%  |
| 1600    | 51        | 17.71%  |
| 2400    | 21        | 7.29%   |
| 2133    | 15        | 5.21%   |
| 4267    | 10        | 3.47%   |
| 4800    | 7         | 2.43%   |
| 1867    | 7         | 2.43%   |
| 3266    | 6         | 2.08%   |
| 1333    | 6         | 2.08%   |
| 6400    | 4         | 1.39%   |
| 1334    | 4         | 1.39%   |
| Unknown | 4         | 1.39%   |
| 4266    | 3         | 1.04%   |
| 1067    | 2         | 0.69%   |
| 8400    | 1         | 0.35%   |
| 3733    | 1         | 0.35%   |
| 1200    | 1         | 0.35%   |
| 1066    | 1         | 0.35%   |
| 667     | 1         | 0.35%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 210 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 121       | 22.96%  |
| IMC Networks                           | 81        | 15.37%  |
| Microdia                               | 49        | 9.3%    |
| Acer                                   | 47        | 8.92%   |
| Realtek Semiconductor                  | 40        | 7.59%   |
| Quanta                                 | 32        | 6.07%   |
| Cheng Uei Precision Industry (Foxlink) | 24        | 4.55%   |
| Syntek                                 | 21        | 3.98%   |
| Sunplus Innovation Technology          | 19        | 3.61%   |
| Lite-On Technology                     | 15        | 2.85%   |
| Luxvisions Innotech Limited            | 14        | 2.66%   |
| Logitech                               | 9         | 1.71%   |
| Apple                                  | 9         | 1.71%   |
| Suyin                                  | 8         | 1.52%   |
| Silicon Motion                         | 6         | 1.14%   |
| Samsung Electronics                    | 5         | 0.95%   |
| Ricoh                                  | 5         | 0.95%   |
| Primax Electronics                     | 4         | 0.76%   |
| Alcor Micro                            | 3         | 0.57%   |
| SunplusIT                              | 2         | 0.38%   |
| Sonix Technology                       | 2         | 0.38%   |
| Z-Star Microelectronics                | 1         | 0.19%   |
| Xiaomi                                 | 1         | 0.19%   |
| OPPO Electronics                       | 1         | 0.19%   |
| Lenovo                                 | 1         | 0.19%   |
| KYE Systems (Mouse Systems)            | 1         | 0.19%   |
| Intel                                  | 1         | 0.19%   |
| icSpring                               | 1         | 0.19%   |
| Hewlett-Packard                        | 1         | 0.19%   |
| Generalplus Technology                 | 1         | 0.19%   |
| BKX-210918                             | 1         | 0.19%   |
| ARC International                      | 1         | 0.19%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 41        | 7.71%   |
| IMC Networks Integrated Camera                          | 35        | 6.58%   |
| Microdia Integrated_Webcam_HD                           | 33        | 6.2%    |
| IMC Networks USB2.0 HD UVC WebCam                       | 25        | 4.7%    |
| Realtek Integrated_Webcam_HD                            | 16        | 3.01%   |
| Acer Integrated Camera                                  | 16        | 3.01%   |
| Syntek Integrated Camera                                | 15        | 2.82%   |
| Chicony HD Webcam                                       | 14        | 2.63%   |
| Chicony Integrated Camera (1280x720@30)                 | 10        | 1.88%   |
| Quanta HD User Facing                                   | 9         | 1.69%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 9         | 1.69%   |
| Lite-On Integrated Camera                               | 8         | 1.5%    |
| Chicony HP TrueVision HD Camera                         | 8         | 1.5%    |
| Chicony HP Wide Vision HD Camera                        | 7         | 1.32%   |
| Quanta HP HD Camera                                     | 6         | 1.13%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 6         | 1.13%   |
| Sunplus Integrated_Webcam_HD                            | 5         | 0.94%   |
| Samsung Galaxy A5 (MTP)                                 | 5         | 0.94%   |
| Quanta HP TrueVision HD Camera                          | 5         | 0.94%   |
| Chicony USB 2.0 Camera                                  | 5         | 0.94%   |
| Realtek Integrated Webcam                               | 4         | 0.75%   |
| Primax HP HD Webcam [Fixed]                             | 4         | 0.75%   |
| Chicony Lenovo Integrated Camera (0.3MP)                | 4         | 0.75%   |
| Cheng Uei Precision Industry (Foxlink) Webcam           | 4         | 0.75%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera        | 4         | 0.75%   |
| Acer Lenovo EasyCamera                                  | 4         | 0.75%   |
| Acer BisonCam, NB Pro                                   | 4         | 0.75%   |
| Syntek Lenovo EasyCamera                                | 3         | 0.56%   |
| Syntek EasyCamera                                       | 3         | 0.56%   |
| Sunplus HD WebCam                                       | 3         | 0.56%   |
| Quanta HP Webcam                                        | 3         | 0.56%   |
| Microdia Amcrest AWC2198 USB Webcam                     | 3         | 0.56%   |
| Lite-On HP Wide Vision HD Camera                        | 3         | 0.56%   |
| Lite-On HP HD Camera                                    | 3         | 0.56%   |
| IMC Networks HD Camera                                  | 3         | 0.56%   |
| Chicony USB2.0 HD UVC WebCam                            | 3         | 0.56%   |
| Chicony USB2.0 Camera                                   | 3         | 0.56%   |
| Chicony HP Webcam                                       | 3         | 0.56%   |
| Chicony EasyCamera                                      | 3         | 0.56%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 3         | 0.56%   |
| Apple FaceTime HD Camera                                | 3         | 0.56%   |
| Acer SunplusIT Integrated Camera                        | 3         | 0.56%   |
| Acer HD Webcam                                          | 3         | 0.56%   |
| Acer HD Camera                                          | 3         | 0.56%   |
| Acer BisonCam,NB Pro                                    | 3         | 0.56%   |
| Suyin HP Truevision HD                                  | 2         | 0.38%   |
| Sunplus Laptop Integrated Webcam HD                     | 2         | 0.38%   |
| Sunplus Integrated_Webcam_FHD                           | 2         | 0.38%   |
| Sunplus ASUS USB2.0 Webcam                              | 2         | 0.38%   |
| Sonix USB2.0 HD UVC WebCam                              | 2         | 0.38%   |
| Silicon Motion Web Camera                               | 2         | 0.38%   |
| Ricoh Laptop_Integrated_Webcam_FHD                      | 2         | 0.38%   |
| Realtek USB2.0 HD UVC WebCam                            | 2         | 0.38%   |
| Realtek Lenovo EasyCamera                               | 2         | 0.38%   |
| Realtek Laptop Camera                                   | 2         | 0.38%   |
| Realtek Front Camera                                    | 2         | 0.38%   |
| Quanta HP Wide Vision HD Camera                         | 2         | 0.38%   |
| Quanta HD Webcam                                        | 2         | 0.38%   |
| Microdia Integrated Webcam HD                           | 2         | 0.38%   |
| Microdia Integrated Webcam                              | 2         | 0.38%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 54        | 36.73%  |
| Validity Sensors           | 37        | 25.17%  |
| Shenzhen Goodix Technology | 28        | 19.05%  |
| LighTuning Technology      | 8         | 5.44%   |
| Elan Microelectronics      | 8         | 5.44%   |
| Upek                       | 6         | 4.08%   |
| Focal-systems.Corp         | 3         | 2.04%   |
| AuthenTec                  | 3         | 2.04%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 28        | 19.05%  |
| Shenzhen Goodix  Fingerprint Device                                        | 16        | 10.88%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 10        | 6.8%    |
| Unknown                                                                    | 9         | 6.12%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 7         | 4.76%   |
| Shenzhen Goodix Fingerprint Reader                                         | 7         | 4.76%   |
| Validity Sensors VFS491                                                    | 6         | 4.08%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 6         | 4.08%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 5         | 3.4%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 5         | 3.4%    |
| Shenzhen Goodix FingerPrint                                                | 5         | 3.4%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 3.4%    |
| Elan ELAN:ARM-M4                                                           | 5         | 3.4%    |
| Validity Sensors Synaptics WBDI                                            | 4         | 2.72%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 3         | 2.04%   |
| Elan ELAN:Fingerprint                                                      | 3         | 2.04%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 1.36%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 1.36%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.36%   |
| Synaptics WBDI Device                                                      | 2         | 1.36%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 1.36%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 1.36%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 0.68%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.68%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.68%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.68%   |
| Synaptics  WBDI                                                            | 1         | 0.68%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 0.68%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.68%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.68%   |
| AuthenTec AES2810                                                          | 1         | 0.68%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.68%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.68%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 20        | 46.51%  |
| Broadcom              | 18        | 41.86%  |
| Upek                  | 2         | 4.65%   |
| OmniKey               | 1         | 2.33%   |
| O2 Micro              | 1         | 2.33%   |
| Gemalto (was Gemplus) | 1         | 2.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 19        | 44.19%  |
| Broadcom 58200                                                               | 7         | 16.28%  |
| Broadcom 5880                                                                | 5         | 11.63%  |
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 9.3%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 4.65%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 4.65%   |
| OmniKey CardMan 1021                                                         | 1         | 2.33%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 2.33%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 2.33%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 2.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 306       | 54.35%  |
| 1     | 204       | 36.23%  |
| 2     | 43        | 7.64%   |
| 3     | 9         | 1.6%    |
| 8     | 1         | 0.18%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 146       | 46.95%  |
| Graphics card         | 67        | 21.54%  |
| Multimedia controller | 28        | 9%      |
| Net/wireless          | 17        | 5.47%   |
| Camera                | 16        | 5.14%   |
| Chipcard              | 9         | 2.89%   |
| Bluetooth             | 9         | 2.89%   |
| Card reader           | 7         | 2.25%   |
| Storage               | 4         | 1.29%   |
| Sound                 | 2         | 0.64%   |
| Network               | 2         | 0.64%   |
| Net/ethernet          | 2         | 0.64%   |
| Modem                 | 2         | 0.64%   |

