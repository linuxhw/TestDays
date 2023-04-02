Fedora - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Fedora.

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

Total: 9193

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | T100TA                      | [5be9a0230e](https://linux-hardware.org/?probe=5be9a0230e) | Apr 01, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [36fab57ba7](https://linux-hardware.org/?probe=36fab57ba7) | Mar 31, 2023 |
| Dell          | Inspiron 7577               | [5800e3859c](https://linux-hardware.org/?probe=5800e3859c) | Mar 31, 2023 |
| Acer          | Nitro AN515-54              | [9e7aa15a9f](https://linux-hardware.org/?probe=9e7aa15a9f) | Mar 31, 2023 |
| HUAWEI        | HN-WX9X                     | [b10ed7894c](https://linux-hardware.org/?probe=b10ed7894c) | Mar 31, 2023 |
| Acer          | Swift SF113-31              | [fc0539603c](https://linux-hardware.org/?probe=fc0539603c) | Mar 31, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | [c76f4f4354](https://linux-hardware.org/?probe=c76f4f4354) | Mar 31, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | [3a74487ae8](https://linux-hardware.org/?probe=3a74487ae8) | Mar 31, 2023 |
| Toshiba       | Satellite U940              | [277dba9c1f](https://linux-hardware.org/?probe=277dba9c1f) | Mar 31, 2023 |
| Toshiba       | Satellite U940              | [8a5046cad7](https://linux-hardware.org/?probe=8a5046cad7) | Mar 31, 2023 |
| HP            | EliteBook 8460p             | [1d5f866283](https://linux-hardware.org/?probe=1d5f866283) | Mar 31, 2023 |
| MSI           | GS66 Stealth 10SF           | [a2589dd6f5](https://linux-hardware.org/?probe=a2589dd6f5) | Mar 31, 2023 |
| Google        | Cave                        | [8bd24407be](https://linux-hardware.org/?probe=8bd24407be) | Mar 31, 2023 |
| Exo           | Smart XL4                   | [6421142cb6](https://linux-hardware.org/?probe=6421142cb6) | Mar 31, 2023 |
| Dell          | Latitude D620               | [801ede47a2](https://linux-hardware.org/?probe=801ede47a2) | Mar 31, 2023 |
| Acer          | Swift SFA16-41              | [e110fbb7d6](https://linux-hardware.org/?probe=e110fbb7d6) | Mar 31, 2023 |
| HP            | EliteBook 6930p             | [5b087b11f5](https://linux-hardware.org/?probe=5b087b11f5) | Mar 30, 2023 |
| Dell          | Precision 5510              | [4bbf7f5ef2](https://linux-hardware.org/?probe=4bbf7f5ef2) | Mar 30, 2023 |
| AIR           | CX30500                     | [2ea4d0ec83](https://linux-hardware.org/?probe=2ea4d0ec83) | Mar 30, 2023 |
| Lenovo        | ThinkPad T470s 20HGS23V0... | [6af08c4bfe](https://linux-hardware.org/?probe=6af08c4bfe) | Mar 30, 2023 |
| Lenovo        | ThinkPad T470s 20HGS23V0... | [6f0d3fd82b](https://linux-hardware.org/?probe=6f0d3fd82b) | Mar 30, 2023 |
| HUAWEI        | KLVL-WXXW                   | [ab31f6f63d](https://linux-hardware.org/?probe=ab31f6f63d) | Mar 30, 2023 |
| Dell          | Inspiron 15 5510            | [162132b606](https://linux-hardware.org/?probe=162132b606) | Mar 30, 2023 |
| Toshiba       | Satellite C850-C5K          | [8fc7451def](https://linux-hardware.org/?probe=8fc7451def) | Mar 30, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | [5cf96e41e0](https://linux-hardware.org/?probe=5cf96e41e0) | Mar 30, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [c73c5374a4](https://linux-hardware.org/?probe=c73c5374a4) | Mar 30, 2023 |
| Dell          | G15 5515                    | [7bb6311632](https://linux-hardware.org/?probe=7bb6311632) | Mar 30, 2023 |
| HP            | 250 G6 Notebook PC          | [159d154fca](https://linux-hardware.org/?probe=159d154fca) | Mar 30, 2023 |
| Dell          | Latitude 5580               | [84157deda8](https://linux-hardware.org/?probe=84157deda8) | Mar 29, 2023 |
| Dell          | XPS 13 7390                 | [2eb96be1ee](https://linux-hardware.org/?probe=2eb96be1ee) | Mar 29, 2023 |
| Lenovo        | ThinkPad T470s 20HGS07D0... | [7a8b075b23](https://linux-hardware.org/?probe=7a8b075b23) | Mar 29, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [d74490158e](https://linux-hardware.org/?probe=d74490158e) | Mar 29, 2023 |
| Apple         | MacBookPro8,1               | [6023df2b8b](https://linux-hardware.org/?probe=6023df2b8b) | Mar 29, 2023 |
| Dell          | Latitude 5420               | [aee5c648e7](https://linux-hardware.org/?probe=aee5c648e7) | Mar 29, 2023 |
| Dell          | Latitude 7430               | [3f3b04c185](https://linux-hardware.org/?probe=3f3b04c185) | Mar 29, 2023 |
| HP            | EliteBook 8770w             | [46a3f1d497](https://linux-hardware.org/?probe=46a3f1d497) | Mar 29, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [2f6655b77c](https://linux-hardware.org/?probe=2f6655b77c) | Mar 29, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | [bf2f7820cd](https://linux-hardware.org/?probe=bf2f7820cd) | Mar 29, 2023 |
| Notebook      | L140CU                      | [e24f4b285d](https://linux-hardware.org/?probe=e24f4b285d) | Mar 29, 2023 |
| Notebook      | L140CU                      | [b1b0a5fc03](https://linux-hardware.org/?probe=b1b0a5fc03) | Mar 29, 2023 |
| ASUSTek       | Zenbook UX5401ZA_UX5401Z... | [c8f2b78c09](https://linux-hardware.org/?probe=c8f2b78c09) | Mar 29, 2023 |
| Clevo         | M815P                       | [ac4eae2a0b](https://linux-hardware.org/?probe=ac4eae2a0b) | Mar 29, 2023 |
| HP            | Pavilion g7                 | [5b1e547f92](https://linux-hardware.org/?probe=5b1e547f92) | Mar 29, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [ccb2d60f5c](https://linux-hardware.org/?probe=ccb2d60f5c) | Mar 29, 2023 |
| HP            | Pavilion g7                 | [ce74564fd9](https://linux-hardware.org/?probe=ce74564fd9) | Mar 28, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [5520b0fc5f](https://linux-hardware.org/?probe=5520b0fc5f) | Mar 28, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | [67789fc0d1](https://linux-hardware.org/?probe=67789fc0d1) | Mar 28, 2023 |
| Lenovo        | ThinkPad T470p 20J7S0QK0... | [7f5fb11940](https://linux-hardware.org/?probe=7f5fb11940) | Mar 28, 2023 |
| ASUSTek       | TX201LA                     | [27c77d0b6c](https://linux-hardware.org/?probe=27c77d0b6c) | Mar 28, 2023 |
| Lenovo        | ThinkPad T495 20NJ000XGE    | [70715024f2](https://linux-hardware.org/?probe=70715024f2) | Mar 28, 2023 |
| HP            | Compaq 6720s                | [9998cb9bfb](https://linux-hardware.org/?probe=9998cb9bfb) | Mar 27, 2023 |
| Dell          | Inspiron N5110              | [7ff133a50e](https://linux-hardware.org/?probe=7ff133a50e) | Mar 27, 2023 |
| HP            | 250 G1                      | [75cf798dde](https://linux-hardware.org/?probe=75cf798dde) | Mar 27, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [3173dc99b6](https://linux-hardware.org/?probe=3173dc99b6) | Mar 27, 2023 |
| Dell          | Latitude E5250              | [7d9e678484](https://linux-hardware.org/?probe=7d9e678484) | Mar 27, 2023 |
| Dell          | Inspiron N5110              | [6b3c579924](https://linux-hardware.org/?probe=6b3c579924) | Mar 27, 2023 |
| Alienware     | 17 R4                       | [4a61d300b5](https://linux-hardware.org/?probe=4a61d300b5) | Mar 27, 2023 |
| Acer          | Predator PT515-51           | [2ac6541cf1](https://linux-hardware.org/?probe=2ac6541cf1) | Mar 27, 2023 |
| Dell          | Latitude 7280               | [409cf549eb](https://linux-hardware.org/?probe=409cf549eb) | Mar 27, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [0ab4054ab9](https://linux-hardware.org/?probe=0ab4054ab9) | Mar 26, 2023 |
| Dell          | G15 5515                    | [3af5157823](https://linux-hardware.org/?probe=3af5157823) | Mar 26, 2023 |
| Chuwi         | HeroBook Air                | [836112a53f](https://linux-hardware.org/?probe=836112a53f) | Mar 26, 2023 |
| Lenovo        | G50-80 80E5                 | [250e0a99d1](https://linux-hardware.org/?probe=250e0a99d1) | Mar 26, 2023 |
| Acer          | Nitro AN515-55              | [36d5ba7071](https://linux-hardware.org/?probe=36d5ba7071) | Mar 26, 2023 |
| Acer          | Nitro AN515-54              | [2163c72a12](https://linux-hardware.org/?probe=2163c72a12) | Mar 25, 2023 |
| Dell          | Vostro 15 3515              | [a999580cf7](https://linux-hardware.org/?probe=a999580cf7) | Mar 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [31788e7103](https://linux-hardware.org/?probe=31788e7103) | Mar 25, 2023 |
| Dell          | Latitude E6230              | [1a248bdc33](https://linux-hardware.org/?probe=1a248bdc33) | Mar 25, 2023 |
| Lenovo        | G580 2189                   | [edba6da5b6](https://linux-hardware.org/?probe=edba6da5b6) | Mar 25, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [ae09be520b](https://linux-hardware.org/?probe=ae09be520b) | Mar 25, 2023 |
| HP            | OMEN by Laptop 16-b1xxx     | [0096d3d3b1](https://linux-hardware.org/?probe=0096d3d3b1) | Mar 25, 2023 |
| ASUSTek       | GL503VS                     | [8e066fcf6e](https://linux-hardware.org/?probe=8e066fcf6e) | Mar 25, 2023 |
| MSI           | Summit E16FlipEvo A11MT     | [62839dd4ac](https://linux-hardware.org/?probe=62839dd4ac) | Mar 24, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [24784bc54d](https://linux-hardware.org/?probe=24784bc54d) | Mar 24, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [c2255f36b2](https://linux-hardware.org/?probe=c2255f36b2) | Mar 24, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | [cbb1418cfa](https://linux-hardware.org/?probe=cbb1418cfa) | Mar 24, 2023 |
| Acer          | Aspire E5-574               | [51a085fb56](https://linux-hardware.org/?probe=51a085fb56) | Mar 24, 2023 |
| Dell          | G15 5515                    | [3510cdb4cf](https://linux-hardware.org/?probe=3510cdb4cf) | Mar 24, 2023 |
| Dell          | Precision 3551              | [bc979e320b](https://linux-hardware.org/?probe=bc979e320b) | Mar 24, 2023 |
| Dell          | Precision 3551              | [0509bee16a](https://linux-hardware.org/?probe=0509bee16a) | Mar 24, 2023 |
| ASUSTek       | ZenBook UX433FN_BX433FN     | [d8e67b032e](https://linux-hardware.org/?probe=d8e67b032e) | Mar 24, 2023 |
| MSI           | Modern 14 B4MW              | [c81d9f3b07](https://linux-hardware.org/?probe=c81d9f3b07) | Mar 24, 2023 |
| HP            | Laptop 17-by3xxx            | [01cac0e411](https://linux-hardware.org/?probe=01cac0e411) | Mar 24, 2023 |
| Lenovo        | IdeaPad Yoga 13 20175       | [56d564423e](https://linux-hardware.org/?probe=56d564423e) | Mar 24, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [ca7d9a9342](https://linux-hardware.org/?probe=ca7d9a9342) | Mar 24, 2023 |
| Dell          | Latitude 5580               | [d4ad4c55a6](https://linux-hardware.org/?probe=d4ad4c55a6) | Mar 24, 2023 |
| Dell          | Latitude 5285               | [a8114ded15](https://linux-hardware.org/?probe=a8114ded15) | Mar 23, 2023 |
| HP            | 250 G4                      | [e0ff721413](https://linux-hardware.org/?probe=e0ff721413) | Mar 23, 2023 |
| Dell          | Latitude 5285               | [baa8f358cf](https://linux-hardware.org/?probe=baa8f358cf) | Mar 23, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [aeb25bc22b](https://linux-hardware.org/?probe=aeb25bc22b) | Mar 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [2d44e8f5c2](https://linux-hardware.org/?probe=2d44e8f5c2) | Mar 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [19efb75aa1](https://linux-hardware.org/?probe=19efb75aa1) | Mar 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [85accc79b1](https://linux-hardware.org/?probe=85accc79b1) | Mar 23, 2023 |
| Dell          | Latitude 5480               | [ff60b91842](https://linux-hardware.org/?probe=ff60b91842) | Mar 23, 2023 |
| Acer          | Aspire E3-112               | [721e804a03](https://linux-hardware.org/?probe=721e804a03) | Mar 23, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [950e4b69e8](https://linux-hardware.org/?probe=950e4b69e8) | Mar 23, 2023 |
| Dell          | Inspiron N5110              | [69e58cde56](https://linux-hardware.org/?probe=69e58cde56) | Mar 23, 2023 |
| HUAWEI        | KPL-W0X                     | [80e6d9af10](https://linux-hardware.org/?probe=80e6d9af10) | Mar 22, 2023 |
| Lenovo        | ThinkPad L380 20M6S3Q000    | [aab8aada0e](https://linux-hardware.org/?probe=aab8aada0e) | Mar 22, 2023 |
| Lenovo        | Legion 5 82B5               | [5298c41263](https://linux-hardware.org/?probe=5298c41263) | Mar 22, 2023 |
| Dell          | Inspiron N5110              | [2be6f0d943](https://linux-hardware.org/?probe=2be6f0d943) | Mar 22, 2023 |
| Apple         | MacBookPro11,5              | [ac5768cd3f](https://linux-hardware.org/?probe=ac5768cd3f) | Mar 22, 2023 |
| HP            | Laptop 15s-eq2xxx           | [ea18262536](https://linux-hardware.org/?probe=ea18262536) | Mar 22, 2023 |
| Dell          | XPS 13 9310                 | [386f37d114](https://linux-hardware.org/?probe=386f37d114) | Mar 22, 2023 |
| Samsung       | 550XDA                      | [b145c438d7](https://linux-hardware.org/?probe=b145c438d7) | Mar 22, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [4ee498d9fc](https://linux-hardware.org/?probe=4ee498d9fc) | Mar 22, 2023 |
| MSI           | GF63 Thin 11SC              | [a63c9ded60](https://linux-hardware.org/?probe=a63c9ded60) | Mar 22, 2023 |
| MSI           | GF63 Thin 11SC              | [cc5ca6f040](https://linux-hardware.org/?probe=cc5ca6f040) | Mar 22, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [5207701ff8](https://linux-hardware.org/?probe=5207701ff8) | Mar 22, 2023 |
| Lenovo        | Legion 5 82B5               | [8dfc670e24](https://linux-hardware.org/?probe=8dfc670e24) | Mar 22, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [23e4353a34](https://linux-hardware.org/?probe=23e4353a34) | Mar 22, 2023 |
| HP            | EliteBook 8470p             | [61025e6e8b](https://linux-hardware.org/?probe=61025e6e8b) | Mar 22, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [80d1a2d67d](https://linux-hardware.org/?probe=80d1a2d67d) | Mar 22, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [eb718edb23](https://linux-hardware.org/?probe=eb718edb23) | Mar 22, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QH... | [883d4de906](https://linux-hardware.org/?probe=883d4de906) | Mar 21, 2023 |
| Lenovo        | B50-10 80QR                 | [134bf99094](https://linux-hardware.org/?probe=134bf99094) | Mar 21, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [b4d5442d02](https://linux-hardware.org/?probe=b4d5442d02) | Mar 21, 2023 |
| HP            | Pavilion Laptop 15-cs2xx... | [6d96576431](https://linux-hardware.org/?probe=6d96576431) | Mar 21, 2023 |
| Acer          | Aspire F5-573G              | [ec2390af74](https://linux-hardware.org/?probe=ec2390af74) | Mar 21, 2023 |
| Dell          | Vostro 14-5480              | [ee892df403](https://linux-hardware.org/?probe=ee892df403) | Mar 21, 2023 |
| Notebook      | W51XTU                      | [de60f3fcba](https://linux-hardware.org/?probe=de60f3fcba) | Mar 21, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [57663c8d60](https://linux-hardware.org/?probe=57663c8d60) | Mar 21, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [f5cbd1977f](https://linux-hardware.org/?probe=f5cbd1977f) | Mar 20, 2023 |
| Hampoo        | Cherry Trail CR Hampoo_r... | [e7eb855568](https://linux-hardware.org/?probe=e7eb855568) | Mar 20, 2023 |
| HP            | Laptop 15-dy1xxx            | [1686ba2df4](https://linux-hardware.org/?probe=1686ba2df4) | Mar 20, 2023 |
| Lenovo        | ThinkPad T480s 20L8002WM... | [762762da77](https://linux-hardware.org/?probe=762762da77) | Mar 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [7fb78c1c79](https://linux-hardware.org/?probe=7fb78c1c79) | Mar 20, 2023 |
| HUAWEI        | FRD-WX9                     | [b5a517c552](https://linux-hardware.org/?probe=b5a517c552) | Mar 20, 2023 |
| Acer          | Aspire F5-573G              | [e3e0efa236](https://linux-hardware.org/?probe=e3e0efa236) | Mar 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [3c0b6b8fdf](https://linux-hardware.org/?probe=3c0b6b8fdf) | Mar 20, 2023 |
| Acer          | Aspire 5935                 | [0634ed91ba](https://linux-hardware.org/?probe=0634ed91ba) | Mar 19, 2023 |
| Dell          | XPS 15 9570                 | [4ad2d5c249](https://linux-hardware.org/?probe=4ad2d5c249) | Mar 19, 2023 |
| Prestigio     | PSB141C01BFH                | [9190e0a0e7](https://linux-hardware.org/?probe=9190e0a0e7) | Mar 19, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [4223bbbf7e](https://linux-hardware.org/?probe=4223bbbf7e) | Mar 19, 2023 |
| Avell High... | B.ON                        | [b215c2fd75](https://linux-hardware.org/?probe=b215c2fd75) | Mar 19, 2023 |
| HP            | 250 G7 Notebook PC          | [5033dda127](https://linux-hardware.org/?probe=5033dda127) | Mar 19, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D60... | [63b182c7d6](https://linux-hardware.org/?probe=63b182c7d6) | Mar 19, 2023 |
| Toshiba       | Satellite C75D-B            | [1ff56ed31f](https://linux-hardware.org/?probe=1ff56ed31f) | Mar 19, 2023 |
| HP            | G62                         | [2cb4092da0](https://linux-hardware.org/?probe=2cb4092da0) | Mar 19, 2023 |
| HP            | G62                         | [76d7e36f21](https://linux-hardware.org/?probe=76d7e36f21) | Mar 19, 2023 |
| HONOR         | GLO-FX6P                    | [0fb3ebc365](https://linux-hardware.org/?probe=0fb3ebc365) | Mar 19, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [88b7883383](https://linux-hardware.org/?probe=88b7883383) | Mar 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [cbad8c5f1e](https://linux-hardware.org/?probe=cbad8c5f1e) | Mar 18, 2023 |
| Acer          | Aspire A315-54              | [49b005770d](https://linux-hardware.org/?probe=49b005770d) | Mar 18, 2023 |
| Acer          | Aspire A315-54              | [6af556d727](https://linux-hardware.org/?probe=6af556d727) | Mar 18, 2023 |
| HP            | Laptop 15-db1xxx            | [08df29b00e](https://linux-hardware.org/?probe=08df29b00e) | Mar 18, 2023 |
| Dell          | Vostro 5471                 | [3b0eb35766](https://linux-hardware.org/?probe=3b0eb35766) | Mar 18, 2023 |
| Dell          | Vostro 5471                 | [7743b2a5a9](https://linux-hardware.org/?probe=7743b2a5a9) | Mar 18, 2023 |
| ASUSTek       | X750JN                      | [7dd8257bc8](https://linux-hardware.org/?probe=7dd8257bc8) | Mar 18, 2023 |
| MSI           | GF65 Thin 10UE              | [8d2db4b0fe](https://linux-hardware.org/?probe=8d2db4b0fe) | Mar 17, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [f219a6e14a](https://linux-hardware.org/?probe=f219a6e14a) | Mar 17, 2023 |
| HIPER         | WORKBOOK                    | [ed14fd6e80](https://linux-hardware.org/?probe=ed14fd6e80) | Mar 17, 2023 |
| ASUSTek       | X750JN                      | [7ee3dac323](https://linux-hardware.org/?probe=7ee3dac323) | Mar 17, 2023 |
| Dell          | Inspiron 3542               | [d79a6ae160](https://linux-hardware.org/?probe=d79a6ae160) | Mar 17, 2023 |
| Dell          | Inspiron 3542               | [691f338c53](https://linux-hardware.org/?probe=691f338c53) | Mar 17, 2023 |
| ASUSTek       | X555LB                      | [a00be2eabe](https://linux-hardware.org/?probe=a00be2eabe) | Mar 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [2ab659150c](https://linux-hardware.org/?probe=2ab659150c) | Mar 16, 2023 |
| HONOR         | BMH-WCX9                    | [47a9ec2aa1](https://linux-hardware.org/?probe=47a9ec2aa1) | Mar 16, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [03123126d0](https://linux-hardware.org/?probe=03123126d0) | Mar 16, 2023 |
| HP            | Laptop 15-da0xxx            | [d00b579583](https://linux-hardware.org/?probe=d00b579583) | Mar 16, 2023 |
| HP            | EliteBook 850 G2            | [f2b9853f35](https://linux-hardware.org/?probe=f2b9853f35) | Mar 16, 2023 |
| Lenovo        | ThinkPad T540p 20BFS1N00... | [03b210c1f8](https://linux-hardware.org/?probe=03b210c1f8) | Mar 16, 2023 |
| Dell          | Latitude D620               | [1731735e10](https://linux-hardware.org/?probe=1731735e10) | Mar 16, 2023 |
| LG Electro... | 15Z980-G.BH72P1             | [0bba01d850](https://linux-hardware.org/?probe=0bba01d850) | Mar 16, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [5667e8416e](https://linux-hardware.org/?probe=5667e8416e) | Mar 16, 2023 |
| Dell          | Latitude E5470              | [cc4f08349d](https://linux-hardware.org/?probe=cc4f08349d) | Mar 16, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [5bf235f5d3](https://linux-hardware.org/?probe=5bf235f5d3) | Mar 16, 2023 |
| Dell          | Latitude E6430              | [e48fceb5f2](https://linux-hardware.org/?probe=e48fceb5f2) | Mar 16, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [907581c9cc](https://linux-hardware.org/?probe=907581c9cc) | Mar 16, 2023 |
| MSI           | Modern 14 B11MOL            | [33bbc272c0](https://linux-hardware.org/?probe=33bbc272c0) | Mar 15, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0AF00    | [fe02ac3290](https://linux-hardware.org/?probe=fe02ac3290) | Mar 15, 2023 |
| Toshiba       | Satellite P870              | [113fcf770d](https://linux-hardware.org/?probe=113fcf770d) | Mar 15, 2023 |
| HP            | Pavilion Notebook           | [db96098c80](https://linux-hardware.org/?probe=db96098c80) | Mar 15, 2023 |
| Dell          | Inspiron 7577               | [d19eaf791f](https://linux-hardware.org/?probe=d19eaf791f) | Mar 15, 2023 |
| Dell          | Latitude 7430               | [58024877c3](https://linux-hardware.org/?probe=58024877c3) | Mar 15, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [1e802bfcd0](https://linux-hardware.org/?probe=1e802bfcd0) | Mar 15, 2023 |
| Dell          | Latitude 5530               | [aac966a8af](https://linux-hardware.org/?probe=aac966a8af) | Mar 15, 2023 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | [59d7fa9a34](https://linux-hardware.org/?probe=59d7fa9a34) | Mar 15, 2023 |
| HIPER         | WORKBOOK                    | [3d1c928bcb](https://linux-hardware.org/?probe=3d1c928bcb) | Mar 15, 2023 |
| Dell          | Latitude 7390               | [7cc6b3a278](https://linux-hardware.org/?probe=7cc6b3a278) | Mar 15, 2023 |
| Dell          | Inspiron 7577               | [a519acdd2e](https://linux-hardware.org/?probe=a519acdd2e) | Mar 15, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [96f3739077](https://linux-hardware.org/?probe=96f3739077) | Mar 15, 2023 |
| HP            | 245 G8 Notebook PC          | [6c73c46184](https://linux-hardware.org/?probe=6c73c46184) | Mar 15, 2023 |
| ASUSTek       | X550MD                      | [2cd5ae8a43](https://linux-hardware.org/?probe=2cd5ae8a43) | Mar 15, 2023 |
| Toshiba       | Satellite P55t-B            | [7bd981d445](https://linux-hardware.org/?probe=7bd981d445) | Mar 15, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [fb73add0f6](https://linux-hardware.org/?probe=fb73add0f6) | Mar 14, 2023 |
| Dell          | Inspiron 7375               | [430599b2da](https://linux-hardware.org/?probe=430599b2da) | Mar 14, 2023 |
| Lenovo        | ThinkPad T490 20N3S3UL00    | [a9db94aee2](https://linux-hardware.org/?probe=a9db94aee2) | Mar 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [112d979fc6](https://linux-hardware.org/?probe=112d979fc6) | Mar 14, 2023 |
| Exo           | Smart XS1                   | [e1e04684eb](https://linux-hardware.org/?probe=e1e04684eb) | Mar 14, 2023 |
| HUAWEI        | CREM-WXX9                   | [933110cc30](https://linux-hardware.org/?probe=933110cc30) | Mar 14, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [d23ddde885](https://linux-hardware.org/?probe=d23ddde885) | Mar 14, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [eac2f2ae40](https://linux-hardware.org/?probe=eac2f2ae40) | Mar 14, 2023 |
| System76      | Gazelle                     | [d45f36e46f](https://linux-hardware.org/?probe=d45f36e46f) | Mar 14, 2023 |
| MSI           | Katana GF76 11UD            | [37edbdcce5](https://linux-hardware.org/?probe=37edbdcce5) | Mar 14, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D60... | [2c2920d462](https://linux-hardware.org/?probe=2c2920d462) | Mar 14, 2023 |
| HP            | ProBook 450 G3              | [d422d0d291](https://linux-hardware.org/?probe=d422d0d291) | Mar 14, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [e6792912bf](https://linux-hardware.org/?probe=e6792912bf) | Mar 14, 2023 |
| Dell          | Inspiron M5010              | [0a5d0c9169](https://linux-hardware.org/?probe=0a5d0c9169) | Mar 14, 2023 |
| MSI           | Stealth GS77 12UHS          | [fe00606a03](https://linux-hardware.org/?probe=fe00606a03) | Mar 14, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [59d2c50a02](https://linux-hardware.org/?probe=59d2c50a02) | Mar 14, 2023 |
| Toshiba       | Satellite L40               | [bfc73429bb](https://linux-hardware.org/?probe=bfc73429bb) | Mar 13, 2023 |
| Dell          | Inspiron 13 5320            | [efbe50cd5c](https://linux-hardware.org/?probe=efbe50cd5c) | Mar 13, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [70de894994](https://linux-hardware.org/?probe=70de894994) | Mar 13, 2023 |
| ASUSTek       | X510UAR                     | [815dfc26ec](https://linux-hardware.org/?probe=815dfc26ec) | Mar 13, 2023 |
| Samsung       | 300E5M/300E5L               | [8567b21f41](https://linux-hardware.org/?probe=8567b21f41) | Mar 13, 2023 |
| HUAWEI        | BOD-WXX9                    | [74452c1274](https://linux-hardware.org/?probe=74452c1274) | Mar 13, 2023 |
| Acer          | Aspire R7-371T              | [b6aef449b6](https://linux-hardware.org/?probe=b6aef449b6) | Mar 13, 2023 |
| Lenovo        | IdeaPad U300s 20111         | [aaaee5fcf5](https://linux-hardware.org/?probe=aaaee5fcf5) | Mar 12, 2023 |
| Lenovo        | IdeaPad U300s 20111         | [3f3945f7e3](https://linux-hardware.org/?probe=3f3945f7e3) | Mar 12, 2023 |
| Lenovo        | ThinkPad 11e 3rd Gen 20G... | [1e037723cc](https://linux-hardware.org/?probe=1e037723cc) | Mar 12, 2023 |
| TECNO         | MEGABOOK T1                 | [000c3e4761](https://linux-hardware.org/?probe=000c3e4761) | Mar 12, 2023 |
| Dell          | Inspiron 5565               | [9415690de2](https://linux-hardware.org/?probe=9415690de2) | Mar 12, 2023 |
| Insyde        | BayTrail                    | [8d0337a8ee](https://linux-hardware.org/?probe=8d0337a8ee) | Mar 12, 2023 |
| Lenovo        | ThinkPad E590 20NBA000AU    | [47bfd44610](https://linux-hardware.org/?probe=47bfd44610) | Mar 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [5c45eb6864](https://linux-hardware.org/?probe=5c45eb6864) | Mar 12, 2023 |
| HUAWEI        | BOD-WXX9                    | [1875fd875d](https://linux-hardware.org/?probe=1875fd875d) | Mar 12, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [28769bd85b](https://linux-hardware.org/?probe=28769bd85b) | Mar 12, 2023 |
| Dell          | Vostro 14-5480              | [3ea64e75d4](https://linux-hardware.org/?probe=3ea64e75d4) | Mar 12, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | [8a8b88087b](https://linux-hardware.org/?probe=8a8b88087b) | Mar 12, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [8aff6217a5](https://linux-hardware.org/?probe=8aff6217a5) | Mar 11, 2023 |
| Dell          | XPS 13 9310                 | [599f8de7ba](https://linux-hardware.org/?probe=599f8de7ba) | Mar 11, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [2a0539c2b1](https://linux-hardware.org/?probe=2a0539c2b1) | Mar 11, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | [5d69c96eca](https://linux-hardware.org/?probe=5d69c96eca) | Mar 11, 2023 |
| BESSTAR Te... | X300                        | [3f12a2f32e](https://linux-hardware.org/?probe=3f12a2f32e) | Mar 11, 2023 |
| BESSTAR Te... | X300                        | [a6ba9c1545](https://linux-hardware.org/?probe=a6ba9c1545) | Mar 11, 2023 |
| Lenovo        | ThinkPad Edge E535 32605... | [ade1e690bb](https://linux-hardware.org/?probe=ade1e690bb) | Mar 11, 2023 |
| Proline       | V146SH                      | [460deab2ea](https://linux-hardware.org/?probe=460deab2ea) | Mar 11, 2023 |
| Dell          | XPS 13 9300                 | [d3b7f2f978](https://linux-hardware.org/?probe=d3b7f2f978) | Mar 11, 2023 |
| ASUSTek       | G752VL                      | [4a4ea6f987](https://linux-hardware.org/?probe=4a4ea6f987) | Mar 11, 2023 |
| Fujitsu       | LIFEBOOK U759               | [01025c7c43](https://linux-hardware.org/?probe=01025c7c43) | Mar 11, 2023 |
| ASUSTek       | ZenBook 13 UX331UAL         | [9b38c9668e](https://linux-hardware.org/?probe=9b38c9668e) | Mar 10, 2023 |
| Dell          | XPS 13 9310                 | [037f2e4a2d](https://linux-hardware.org/?probe=037f2e4a2d) | Mar 10, 2023 |
| HONOR         | NMH-WCX9                    | [f9cf8b06f6](https://linux-hardware.org/?probe=f9cf8b06f6) | Mar 10, 2023 |
| Lenovo        | ThinkPad T460 20LPS3K002    | [c375b36f4a](https://linux-hardware.org/?probe=c375b36f4a) | Mar 10, 2023 |
| Acer          | Swift SFX14-41G             | [80ecfacebf](https://linux-hardware.org/?probe=80ecfacebf) | Mar 10, 2023 |
| Unknown       | Unknown                     | [cd382356be](https://linux-hardware.org/?probe=cd382356be) | Mar 10, 2023 |
| HP            | Laptop 14-cm0xxx            | [d35d11c64e](https://linux-hardware.org/?probe=d35d11c64e) | Mar 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [d35772b8bc](https://linux-hardware.org/?probe=d35772b8bc) | Mar 09, 2023 |
| HP            | Notebook                    | [b5ee32f085](https://linux-hardware.org/?probe=b5ee32f085) | Mar 09, 2023 |
| Lenovo        | ThinkPad T440p 20AWS0XX0... | [780937bb9f](https://linux-hardware.org/?probe=780937bb9f) | Mar 09, 2023 |
| Dell          | XPS 15 9530                 | [d7129009b0](https://linux-hardware.org/?probe=d7129009b0) | Mar 09, 2023 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | [e4164a80cd](https://linux-hardware.org/?probe=e4164a80cd) | Mar 09, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [c50daaf3b9](https://linux-hardware.org/?probe=c50daaf3b9) | Mar 09, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [5535b412ed](https://linux-hardware.org/?probe=5535b412ed) | Mar 09, 2023 |
| Dell          | Inspiron 7375               | [2dbb99bbb2](https://linux-hardware.org/?probe=2dbb99bbb2) | Mar 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [2664be8926](https://linux-hardware.org/?probe=2664be8926) | Mar 09, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | [dc915e443d](https://linux-hardware.org/?probe=dc915e443d) | Mar 09, 2023 |
| HP            | Laptop 15-dy2xxx            | [97698bd9a9](https://linux-hardware.org/?probe=97698bd9a9) | Mar 09, 2023 |
| Google        | Cave                        | [37d6d413b7](https://linux-hardware.org/?probe=37d6d413b7) | Mar 09, 2023 |
| Dell          | Inspiron 3505               | [5ffa875792](https://linux-hardware.org/?probe=5ffa875792) | Mar 08, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b349a8eedd](https://linux-hardware.org/?probe=b349a8eedd) | Mar 08, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [ac772ea51f](https://linux-hardware.org/?probe=ac772ea51f) | Mar 08, 2023 |
| Lenovo        | ThinkPad T450s 20BX0013G... | [11cf435bfe](https://linux-hardware.org/?probe=11cf435bfe) | Mar 08, 2023 |
| Acer          | Aspire A315-58              | [f4de2d1a2a](https://linux-hardware.org/?probe=f4de2d1a2a) | Mar 08, 2023 |
| HP            | OMEN by Laptop              | [a3a369de93](https://linux-hardware.org/?probe=a3a369de93) | Mar 08, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [439ea07bc5](https://linux-hardware.org/?probe=439ea07bc5) | Mar 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S0S... | [2e864ba25e](https://linux-hardware.org/?probe=2e864ba25e) | Mar 08, 2023 |
| Dell          | Inspiron 14 5420            | [cb6ec54195](https://linux-hardware.org/?probe=cb6ec54195) | Mar 08, 2023 |
| Dell          | Latitude 5400               | [3d2504745e](https://linux-hardware.org/?probe=3d2504745e) | Mar 08, 2023 |
| HP            | ProBook 440 G7              | [7f4678dcf1](https://linux-hardware.org/?probe=7f4678dcf1) | Mar 07, 2023 |
| HP            | ProBook 450 G6              | [44c6479881](https://linux-hardware.org/?probe=44c6479881) | Mar 07, 2023 |
| Dell          | Latitude 7290               | [38f12088b2](https://linux-hardware.org/?probe=38f12088b2) | Mar 07, 2023 |
| HUAWEI        | CREM-WXX9                   | [1aaf3d1b9f](https://linux-hardware.org/?probe=1aaf3d1b9f) | Mar 07, 2023 |
| MSI           | Modern 15 A5M               | [e88ffa7e1d](https://linux-hardware.org/?probe=e88ffa7e1d) | Mar 07, 2023 |
| Acer          | One S1001                   | [b43d7f0a84](https://linux-hardware.org/?probe=b43d7f0a84) | Mar 06, 2023 |
| HUAWEI        | KLVD-WXX9                   | [1209c224e1](https://linux-hardware.org/?probe=1209c224e1) | Mar 06, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | [798d6e74da](https://linux-hardware.org/?probe=798d6e74da) | Mar 06, 2023 |
| HP            | ProBook 450 G4              | [72af4386e5](https://linux-hardware.org/?probe=72af4386e5) | Mar 06, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X6... | [bd9c4997b0](https://linux-hardware.org/?probe=bd9c4997b0) | Mar 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [98a2c9f264](https://linux-hardware.org/?probe=98a2c9f264) | Mar 06, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [4e05d0a0e9](https://linux-hardware.org/?probe=4e05d0a0e9) | Mar 06, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [4b6c93e678](https://linux-hardware.org/?probe=4b6c93e678) | Mar 06, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [0fca5ee94e](https://linux-hardware.org/?probe=0fca5ee94e) | Mar 06, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [d256faa9fc](https://linux-hardware.org/?probe=d256faa9fc) | Mar 06, 2023 |
| Dell          | Inspiron 15 3525            | [cc3e080ded](https://linux-hardware.org/?probe=cc3e080ded) | Mar 06, 2023 |
| Dell          | Inspiron 3593               | [f33f04396c](https://linux-hardware.org/?probe=f33f04396c) | Mar 05, 2023 |
| Acer          | Aspire A515-57T             | [ebd1e9103e](https://linux-hardware.org/?probe=ebd1e9103e) | Mar 05, 2023 |
| Google        | Lillipup                    | [6c7cf4cd9e](https://linux-hardware.org/?probe=6c7cf4cd9e) | Mar 05, 2023 |
| Lenovo        | ThinkPad T15p Gen 1 20TN... | [0811163639](https://linux-hardware.org/?probe=0811163639) | Mar 05, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [42469e8f5d](https://linux-hardware.org/?probe=42469e8f5d) | Mar 05, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [d42a19d17b](https://linux-hardware.org/?probe=d42a19d17b) | Mar 05, 2023 |
| Dell          | Latitude 5410               | [6f55e8bbfe](https://linux-hardware.org/?probe=6f55e8bbfe) | Mar 05, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U4S... | [fb996384c6](https://linux-hardware.org/?probe=fb996384c6) | Mar 05, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [925e02d1dc](https://linux-hardware.org/?probe=925e02d1dc) | Mar 04, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [e2ad6f0e57](https://linux-hardware.org/?probe=e2ad6f0e57) | Mar 04, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [7d9acf8639](https://linux-hardware.org/?probe=7d9acf8639) | Mar 04, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [a28f5eeec0](https://linux-hardware.org/?probe=a28f5eeec0) | Mar 04, 2023 |
| Toshiba       | Satellite L40               | [bd108fcfba](https://linux-hardware.org/?probe=bd108fcfba) | Mar 04, 2023 |
| Lenovo        | ThinkPad X230 23255SM       | [2f5cd26eae](https://linux-hardware.org/?probe=2f5cd26eae) | Mar 04, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [6f7115f084](https://linux-hardware.org/?probe=6f7115f084) | Mar 04, 2023 |
| Purism        | Librem 14                   | [fbae41cbd5](https://linux-hardware.org/?probe=fbae41cbd5) | Mar 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [bd5e51c339](https://linux-hardware.org/?probe=bd5e51c339) | Mar 04, 2023 |
| Toshiba       | Satellite L40               | [e3f1423c39](https://linux-hardware.org/?probe=e3f1423c39) | Mar 04, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | [1bcec582e3](https://linux-hardware.org/?probe=1bcec582e3) | Mar 03, 2023 |
| Clevo         | W25xHNx                     | [5227127f81](https://linux-hardware.org/?probe=5227127f81) | Mar 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [1ee7b087a8](https://linux-hardware.org/?probe=1ee7b087a8) | Mar 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [4b20311834](https://linux-hardware.org/?probe=4b20311834) | Mar 03, 2023 |
| HP            | EliteBook 830 G5            | [cd6c75d08e](https://linux-hardware.org/?probe=cd6c75d08e) | Mar 03, 2023 |
| Chuwi         | HeroBook Air                | [43248e0ae9](https://linux-hardware.org/?probe=43248e0ae9) | Mar 03, 2023 |
| Toshiba       | Satellite L515              | [daf95cc1e5](https://linux-hardware.org/?probe=daf95cc1e5) | Mar 03, 2023 |
| MSI           | GS63VR 6RF                  | [dd60a9c73b](https://linux-hardware.org/?probe=dd60a9c73b) | Mar 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [5906e1b848](https://linux-hardware.org/?probe=5906e1b848) | Mar 03, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [c4c7ebf544](https://linux-hardware.org/?probe=c4c7ebf544) | Mar 03, 2023 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [e5b411431c](https://linux-hardware.org/?probe=e5b411431c) | Mar 02, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [22c9e146ee](https://linux-hardware.org/?probe=22c9e146ee) | Mar 02, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | [aa0e36b22e](https://linux-hardware.org/?probe=aa0e36b22e) | Mar 02, 2023 |
| Apple         | MacBookAir5,2               | [6b7925d129](https://linux-hardware.org/?probe=6b7925d129) | Mar 02, 2023 |
| HP            | 255 G3                      | [78c4cd0a9c](https://linux-hardware.org/?probe=78c4cd0a9c) | Mar 01, 2023 |
| HUAWEI        | KLVD-WXX9                   | [8c878d99a1](https://linux-hardware.org/?probe=8c878d99a1) | Mar 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [9ba7cfbdeb](https://linux-hardware.org/?probe=9ba7cfbdeb) | Mar 01, 2023 |
| Lenovo        | ThinkBook 15 G4 ABA 21DL    | [94809b7bc2](https://linux-hardware.org/?probe=94809b7bc2) | Mar 01, 2023 |
| Apple         | MacBookPro7,1               | [4d1bdc90ea](https://linux-hardware.org/?probe=4d1bdc90ea) | Mar 01, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [6a99428156](https://linux-hardware.org/?probe=6a99428156) | Mar 01, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [3db8300147](https://linux-hardware.org/?probe=3db8300147) | Mar 01, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [1c09e468d0](https://linux-hardware.org/?probe=1c09e468d0) | Mar 01, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [165c0356a5](https://linux-hardware.org/?probe=165c0356a5) | Mar 01, 2023 |
| Lenovo        | ThinkPad X13 Gen 3 21CM0... | [40516fd80e](https://linux-hardware.org/?probe=40516fd80e) | Mar 01, 2023 |
| HUAWEI        | CREM-WXX9                   | [22d51a725f](https://linux-hardware.org/?probe=22d51a725f) | Feb 28, 2023 |
| Dell          | Latitude E7270              | [2718026d03](https://linux-hardware.org/?probe=2718026d03) | Feb 28, 2023 |
| TECNO         | MEGABOOK T1                 | [3b70c27ca4](https://linux-hardware.org/?probe=3b70c27ca4) | Feb 28, 2023 |
| HUAWEI        | MRC-WX0                     | [e2776f99bf](https://linux-hardware.org/?probe=e2776f99bf) | Feb 28, 2023 |
| HP            | ProBook 635 Aero G8 Note... | [93ee76f198](https://linux-hardware.org/?probe=93ee76f198) | Feb 28, 2023 |
| Acer          | Aspire A315-59              | [9a897f5d7c](https://linux-hardware.org/?probe=9a897f5d7c) | Feb 28, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | [b5a4a1809f](https://linux-hardware.org/?probe=b5a4a1809f) | Feb 28, 2023 |
| TECNO         | MEGABOOK T1                 | [3d003c6d17](https://linux-hardware.org/?probe=3d003c6d17) | Feb 28, 2023 |
| ASUSTek       | ROG Strix G712LW_G712LW     | [ed67c567d2](https://linux-hardware.org/?probe=ed67c567d2) | Feb 28, 2023 |
| Standard      | Unknown                     | [63732ac2da](https://linux-hardware.org/?probe=63732ac2da) | Feb 28, 2023 |
| Dell          | Precision 5570              | [7e8d7c37cb](https://linux-hardware.org/?probe=7e8d7c37cb) | Feb 28, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [c829e9e0b8](https://linux-hardware.org/?probe=c829e9e0b8) | Feb 27, 2023 |
| HP            | EliteBook Folio 9470m       | [45403acec9](https://linux-hardware.org/?probe=45403acec9) | Feb 27, 2023 |
| HUAWEI        | MACHR-WX9                   | [b1ef7c7ea1](https://linux-hardware.org/?probe=b1ef7c7ea1) | Feb 27, 2023 |
| Apple         | MacBookAir6,1               | [1c1dc86eb1](https://linux-hardware.org/?probe=1c1dc86eb1) | Feb 27, 2023 |
| HP            | EliteBook 845 14 inch G9... | [ed251c6cfe](https://linux-hardware.org/?probe=ed251c6cfe) | Feb 27, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [dd5ce2c6db](https://linux-hardware.org/?probe=dd5ce2c6db) | Feb 27, 2023 |
| Toshiba       | Satellite P870              | [6d9216b866](https://linux-hardware.org/?probe=6d9216b866) | Feb 27, 2023 |
| Dell          | Inspiron 15 3511            | [4c96506f38](https://linux-hardware.org/?probe=4c96506f38) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [d7e55bb97e](https://linux-hardware.org/?probe=d7e55bb97e) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [091e4e3188](https://linux-hardware.org/?probe=091e4e3188) | Feb 27, 2023 |
| Apple         | MacBookAir6,1               | [058ecdce01](https://linux-hardware.org/?probe=058ecdce01) | Feb 27, 2023 |
| Lenovo        | ThinkPad X395 20NL0006US    | [9030fac261](https://linux-hardware.org/?probe=9030fac261) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [fe8735a027](https://linux-hardware.org/?probe=fe8735a027) | Feb 26, 2023 |
| HP            | Notebook                    | [ab0dddc914](https://linux-hardware.org/?probe=ab0dddc914) | Feb 26, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [6b712e555f](https://linux-hardware.org/?probe=6b712e555f) | Feb 26, 2023 |
| Dell          | Vostro 3578                 | [da6968c8ac](https://linux-hardware.org/?probe=da6968c8ac) | Feb 26, 2023 |
| Samsung       | 370E4K                      | [7b769eb33e](https://linux-hardware.org/?probe=7b769eb33e) | Feb 26, 2023 |
| HUAWEI        | CREM-WXX9                   | [c026a25fb2](https://linux-hardware.org/?probe=c026a25fb2) | Feb 26, 2023 |
| HP            | 250 G6 Notebook PC          | [af6a897a26](https://linux-hardware.org/?probe=af6a897a26) | Feb 26, 2023 |
| Timi          | TM1612                      | [eb4a3f330e](https://linux-hardware.org/?probe=eb4a3f330e) | Feb 26, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [d3b6621252](https://linux-hardware.org/?probe=d3b6621252) | Feb 26, 2023 |
| Acer          | Nitro AN515-52              | [f589c3687b](https://linux-hardware.org/?probe=f589c3687b) | Feb 26, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [d610badec8](https://linux-hardware.org/?probe=d610badec8) | Feb 26, 2023 |
| Acer          | TravelMate P633-V           | [b4841d9589](https://linux-hardware.org/?probe=b4841d9589) | Feb 26, 2023 |
| Lenovo        | ThinkPad T61 6464A13        | [e981803528](https://linux-hardware.org/?probe=e981803528) | Feb 26, 2023 |
| Standard      | Unknown                     | [9d002e0593](https://linux-hardware.org/?probe=9d002e0593) | Feb 26, 2023 |
| Lenovo        | Legion 5 82B5               | [8db23a7237](https://linux-hardware.org/?probe=8db23a7237) | Feb 25, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [bd2c3ecd74](https://linux-hardware.org/?probe=bd2c3ecd74) | Feb 25, 2023 |
| Lenovo        | ThinkPad T480 20L5S03600    | [5c9736ab0c](https://linux-hardware.org/?probe=5c9736ab0c) | Feb 25, 2023 |
| Dell          | Vostro 14-5459              | [1f96898a48](https://linux-hardware.org/?probe=1f96898a48) | Feb 25, 2023 |
| Dell          | Latitude E6420              | [7ae4fe9340](https://linux-hardware.org/?probe=7ae4fe9340) | Feb 25, 2023 |
| Acer          | TravelMate P633-V           | [fd426b6c71](https://linux-hardware.org/?probe=fd426b6c71) | Feb 25, 2023 |
| Dell          | Latitude 5511               | [4402838fb3](https://linux-hardware.org/?probe=4402838fb3) | Feb 25, 2023 |
| Google        | Voxel                       | [ce917fe8ec](https://linux-hardware.org/?probe=ce917fe8ec) | Feb 25, 2023 |
| Google        | Voxel                       | [93ea143f69](https://linux-hardware.org/?probe=93ea143f69) | Feb 25, 2023 |
| Dell          | Inspiron 5759               | [be0b15660e](https://linux-hardware.org/?probe=be0b15660e) | Feb 25, 2023 |
| HUAWEI        | MACH-WX9                    | [52924074db](https://linux-hardware.org/?probe=52924074db) | Feb 25, 2023 |
| Dell          | Precision 5520              | [c41014658b](https://linux-hardware.org/?probe=c41014658b) | Feb 25, 2023 |
| Dell          | System XPS L321X            | [4de5ba1c80](https://linux-hardware.org/?probe=4de5ba1c80) | Feb 25, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [1c1e5c991f](https://linux-hardware.org/?probe=1c1e5c991f) | Feb 25, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [9cbbaaf012](https://linux-hardware.org/?probe=9cbbaaf012) | Feb 24, 2023 |
| Chuwi         | GemiBook Pro                | [f8f1005d73](https://linux-hardware.org/?probe=f8f1005d73) | Feb 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [787270bc9e](https://linux-hardware.org/?probe=787270bc9e) | Feb 24, 2023 |
| Lenovo        | Yoga Pro 14s IAH7 82TK      | [ade006d016](https://linux-hardware.org/?probe=ade006d016) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [2bbce041f5](https://linux-hardware.org/?probe=2bbce041f5) | Feb 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [f7063f868f](https://linux-hardware.org/?probe=f7063f868f) | Feb 24, 2023 |
| HP            | 245 G8 Notebook PC          | [7686bcd76d](https://linux-hardware.org/?probe=7686bcd76d) | Feb 24, 2023 |
| Dell          | Inspiron 13-7359            | [7858955f02](https://linux-hardware.org/?probe=7858955f02) | Feb 24, 2023 |
| Toshiba       | Satellite L515              | [969c2042b9](https://linux-hardware.org/?probe=969c2042b9) | Feb 24, 2023 |
| Dell          | G5 5587                     | [1f43871064](https://linux-hardware.org/?probe=1f43871064) | Feb 24, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [f92ac89547](https://linux-hardware.org/?probe=f92ac89547) | Feb 23, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [4b0436b55d](https://linux-hardware.org/?probe=4b0436b55d) | Feb 23, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [a4c4313238](https://linux-hardware.org/?probe=a4c4313238) | Feb 23, 2023 |
| HP            | EliteBook 840 G6            | [ea6777bf2d](https://linux-hardware.org/?probe=ea6777bf2d) | Feb 23, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | [bb2bef71e0](https://linux-hardware.org/?probe=bb2bef71e0) | Feb 23, 2023 |
| Lenovo        | ThinkPad X230 2325CS6       | [ed9501bbcb](https://linux-hardware.org/?probe=ed9501bbcb) | Feb 23, 2023 |
| Dell          | Inspiron 13-7359            | [39d95063c3](https://linux-hardware.org/?probe=39d95063c3) | Feb 23, 2023 |
| ASUSTek       | K56CA                       | [d8475e4c48](https://linux-hardware.org/?probe=d8475e4c48) | Feb 23, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [e23562af05](https://linux-hardware.org/?probe=e23562af05) | Feb 23, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [becb5b0ba1](https://linux-hardware.org/?probe=becb5b0ba1) | Feb 22, 2023 |
| CyberPower... | Tracer IV GM5MQ8W           | [284e8a4fb1](https://linux-hardware.org/?probe=284e8a4fb1) | Feb 22, 2023 |
| Dell          | Latitude E5570              | [338538c1c9](https://linux-hardware.org/?probe=338538c1c9) | Feb 22, 2023 |
| Gigabyte      | G5 KD                       | [65c50530c8](https://linux-hardware.org/?probe=65c50530c8) | Feb 22, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [7d3442e2a7](https://linux-hardware.org/?probe=7d3442e2a7) | Feb 22, 2023 |
| Alienware     | x14                         | [0b32a33625](https://linux-hardware.org/?probe=0b32a33625) | Feb 22, 2023 |
| Alienware     | x14                         | [04094754b6](https://linux-hardware.org/?probe=04094754b6) | Feb 22, 2023 |
| HP            | Notebook                    | [f6d3ba25ba](https://linux-hardware.org/?probe=f6d3ba25ba) | Feb 22, 2023 |
| Samsung       | 767XCL                      | [3fb09fb626](https://linux-hardware.org/?probe=3fb09fb626) | Feb 22, 2023 |
| Dell          | Latitude 5491               | [fd68ba9595](https://linux-hardware.org/?probe=fd68ba9595) | Feb 21, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [a459216464](https://linux-hardware.org/?probe=a459216464) | Feb 21, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [7ead9488ae](https://linux-hardware.org/?probe=7ead9488ae) | Feb 21, 2023 |
| Apple         | MacBookAir6,1               | [b9117f0c6f](https://linux-hardware.org/?probe=b9117f0c6f) | Feb 21, 2023 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | [c0733771d5](https://linux-hardware.org/?probe=c0733771d5) | Feb 21, 2023 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | [039bb422e0](https://linux-hardware.org/?probe=039bb422e0) | Feb 21, 2023 |
| Acer          | Aspire SW3-013              | [f0111df214](https://linux-hardware.org/?probe=f0111df214) | Feb 21, 2023 |
| Alienware     | 15 R2                       | [96aa09ae59](https://linux-hardware.org/?probe=96aa09ae59) | Feb 21, 2023 |
| HP            | EliteBook 2540p             | [bf037f7503](https://linux-hardware.org/?probe=bf037f7503) | Feb 21, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [d1f67d5e08](https://linux-hardware.org/?probe=d1f67d5e08) | Feb 21, 2023 |
| Acer          | Nitro AN515-52              | [9989903f85](https://linux-hardware.org/?probe=9989903f85) | Feb 21, 2023 |
| Dell          | XPS 13 7390                 | [2b329d108f](https://linux-hardware.org/?probe=2b329d108f) | Feb 21, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [53737369e8](https://linux-hardware.org/?probe=53737369e8) | Feb 21, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [b8c4b41baf](https://linux-hardware.org/?probe=b8c4b41baf) | Feb 21, 2023 |
| Dell          | XPS 13 7390                 | [a3ed8101b1](https://linux-hardware.org/?probe=a3ed8101b1) | Feb 20, 2023 |
| MSI           | Modern 15 A5M               | [f6c80ff7a9](https://linux-hardware.org/?probe=f6c80ff7a9) | Feb 20, 2023 |
| Fujitsu       | LIFEBOOK E559               | [5e4c3607c7](https://linux-hardware.org/?probe=5e4c3607c7) | Feb 20, 2023 |
| Fujitsu       | LIFEBOOK A357               | [a813f73ea2](https://linux-hardware.org/?probe=a813f73ea2) | Feb 20, 2023 |
| MSI           | Bravo 15 B5ED               | [a0b7f1b5f8](https://linux-hardware.org/?probe=a0b7f1b5f8) | Feb 20, 2023 |
| Lenovo        | ThinkPad T530 239265U       | [9f60ca6bf5](https://linux-hardware.org/?probe=9f60ca6bf5) | Feb 20, 2023 |
| Dell          | XPS 13 7390                 | [542077cc42](https://linux-hardware.org/?probe=542077cc42) | Feb 20, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [057dcdc86b](https://linux-hardware.org/?probe=057dcdc86b) | Feb 20, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | [d8abf7361b](https://linux-hardware.org/?probe=d8abf7361b) | Feb 20, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [89eb85b36f](https://linux-hardware.org/?probe=89eb85b36f) | Feb 19, 2023 |
| Chuwi         | HeroBook Air                | [c669fff700](https://linux-hardware.org/?probe=c669fff700) | Feb 19, 2023 |
| Acer          | Predator PH315-52           | [7432db815e](https://linux-hardware.org/?probe=7432db815e) | Feb 19, 2023 |
| Acer          | Predator PH315-52           | [aaee9da394](https://linux-hardware.org/?probe=aaee9da394) | Feb 19, 2023 |
| ASUSTek       | ROG Strix G733ZW_G733ZW     | [72f074b930](https://linux-hardware.org/?probe=72f074b930) | Feb 19, 2023 |
| Dell          | Latitude E6430              | [23c0ff9281](https://linux-hardware.org/?probe=23c0ff9281) | Feb 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [b1d168b6ce](https://linux-hardware.org/?probe=b1d168b6ce) | Feb 19, 2023 |
| Dell          | Latitude E6430              | [d97087b55f](https://linux-hardware.org/?probe=d97087b55f) | Feb 19, 2023 |
| Lenovo        | ThinkPad E555 20DH000TUK    | [b2d5c9de8b](https://linux-hardware.org/?probe=b2d5c9de8b) | Feb 19, 2023 |
| Standard      | Unknown                     | [149bdc4e40](https://linux-hardware.org/?probe=149bdc4e40) | Feb 19, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [9b0ecbd3c7](https://linux-hardware.org/?probe=9b0ecbd3c7) | Feb 19, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | [ee24b75c39](https://linux-hardware.org/?probe=ee24b75c39) | Feb 19, 2023 |
| Dell          | Precision M4500             | [b0d8bf3c56](https://linux-hardware.org/?probe=b0d8bf3c56) | Feb 19, 2023 |
| Apple         | MacBookAir6,1               | [5cade7cfc3](https://linux-hardware.org/?probe=5cade7cfc3) | Feb 19, 2023 |
| Google        | Kled                        | [788d726509](https://linux-hardware.org/?probe=788d726509) | Feb 18, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [9b53b2b842](https://linux-hardware.org/?probe=9b53b2b842) | Feb 18, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [cdfcc639d3](https://linux-hardware.org/?probe=cdfcc639d3) | Feb 18, 2023 |
| Lenovo        | ThinkPad T530 2429F27       | [b835147a32](https://linux-hardware.org/?probe=b835147a32) | Feb 18, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | [fb2cbe3576](https://linux-hardware.org/?probe=fb2cbe3576) | Feb 18, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [a424b3aa47](https://linux-hardware.org/?probe=a424b3aa47) | Feb 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [e7988c5ab6](https://linux-hardware.org/?probe=e7988c5ab6) | Feb 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | [6d2b283e83](https://linux-hardware.org/?probe=6d2b283e83) | Feb 18, 2023 |
| Dell          | Precision 5560              | [24e5de4a3d](https://linux-hardware.org/?probe=24e5de4a3d) | Feb 18, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [c4a1fe4a4f](https://linux-hardware.org/?probe=c4a1fe4a4f) | Feb 17, 2023 |
| Lenovo        | ThinkPad T490 20N2001YUS    | [53ef9ffad8](https://linux-hardware.org/?probe=53ef9ffad8) | Feb 17, 2023 |
| Dell          | Latitude 5491               | [8a3298cdff](https://linux-hardware.org/?probe=8a3298cdff) | Feb 17, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [e4483255db](https://linux-hardware.org/?probe=e4483255db) | Feb 17, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [09aefeb3d6](https://linux-hardware.org/?probe=09aefeb3d6) | Feb 17, 2023 |
| Dell          | Inspiron 5566               | [502adcba49](https://linux-hardware.org/?probe=502adcba49) | Feb 17, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | [cc44156b99](https://linux-hardware.org/?probe=cc44156b99) | Feb 17, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | [bc234d0b32](https://linux-hardware.org/?probe=bc234d0b32) | Feb 17, 2023 |
| HP            | ENVY Laptop 17-ch2xxx       | [c1abb80cb1](https://linux-hardware.org/?probe=c1abb80cb1) | Feb 17, 2023 |
| Lenovo        | ZIWB2                       | [8ade075157](https://linux-hardware.org/?probe=8ade075157) | Feb 16, 2023 |
| HP            | 245 G8 Notebook PC          | [c48e458030](https://linux-hardware.org/?probe=c48e458030) | Feb 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [4657fc266d](https://linux-hardware.org/?probe=4657fc266d) | Feb 16, 2023 |
| Acer          | Swift SF314-511             | [71778cedf9](https://linux-hardware.org/?probe=71778cedf9) | Feb 16, 2023 |
| Samsung       | 940XFG                      | [56f236f8ab](https://linux-hardware.org/?probe=56f236f8ab) | Feb 16, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [ddc2c7ec7a](https://linux-hardware.org/?probe=ddc2c7ec7a) | Feb 16, 2023 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | [5a3b0950b3](https://linux-hardware.org/?probe=5a3b0950b3) | Feb 16, 2023 |
| Lenovo        | Y50-70 20378                | [09301690c5](https://linux-hardware.org/?probe=09301690c5) | Feb 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | [159244d1a4](https://linux-hardware.org/?probe=159244d1a4) | Feb 15, 2023 |
| HP            | Notebook                    | [9fe647f9a1](https://linux-hardware.org/?probe=9fe647f9a1) | Feb 15, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [36f57d56f8](https://linux-hardware.org/?probe=36f57d56f8) | Feb 15, 2023 |
| HP            | Notebook                    | [c4516fb37a](https://linux-hardware.org/?probe=c4516fb37a) | Feb 15, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [7fd55795a0](https://linux-hardware.org/?probe=7fd55795a0) | Feb 15, 2023 |
| Lenovo        | ThinkPad P50 20EQS64N09     | [72fad631b7](https://linux-hardware.org/?probe=72fad631b7) | Feb 15, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [70885f1dfd](https://linux-hardware.org/?probe=70885f1dfd) | Feb 15, 2023 |
| HP            | Laptop 15s-eq2xxx           | [92a9452070](https://linux-hardware.org/?probe=92a9452070) | Feb 15, 2023 |
| Dell          | Inspiron 7375               | [3916d619ed](https://linux-hardware.org/?probe=3916d619ed) | Feb 15, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [1ca19c3d1d](https://linux-hardware.org/?probe=1ca19c3d1d) | Feb 14, 2023 |
| ASUSTek       | UL30A                       | [90114a4fe4](https://linux-hardware.org/?probe=90114a4fe4) | Feb 14, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [390686f5f6](https://linux-hardware.org/?probe=390686f5f6) | Feb 14, 2023 |
| HP            | ProBook 440 G7              | [bc4811db07](https://linux-hardware.org/?probe=bc4811db07) | Feb 14, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [cbcadcf80a](https://linux-hardware.org/?probe=cbcadcf80a) | Feb 14, 2023 |
| Dell          | Latitude E7270              | [03199b7612](https://linux-hardware.org/?probe=03199b7612) | Feb 14, 2023 |
| Lenovo        | IdeaPad 520S-14IKB 81BL     | [008d06fbf8](https://linux-hardware.org/?probe=008d06fbf8) | Feb 14, 2023 |
| Timi          | Xiaomi NoteBook Pro         | [561e1a6160](https://linux-hardware.org/?probe=561e1a6160) | Feb 14, 2023 |
| Dell          | Latitude 7430               | [82dcb0a8a2](https://linux-hardware.org/?probe=82dcb0a8a2) | Feb 14, 2023 |
| Dell          | G3 3579                     | [35c8b69b8c](https://linux-hardware.org/?probe=35c8b69b8c) | Feb 14, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [a3b0220b10](https://linux-hardware.org/?probe=a3b0220b10) | Feb 14, 2023 |
| HP            | EliteBook 840 G5            | [2f78b0c253](https://linux-hardware.org/?probe=2f78b0c253) | Feb 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [ac71e5b8ef](https://linux-hardware.org/?probe=ac71e5b8ef) | Feb 14, 2023 |
| Dell          | Inspiron 14 5420            | [45862fde09](https://linux-hardware.org/?probe=45862fde09) | Feb 13, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [1f0e965483](https://linux-hardware.org/?probe=1f0e965483) | Feb 13, 2023 |
| Dell          | Inspiron 14 5420            | [8153aeb3fb](https://linux-hardware.org/?probe=8153aeb3fb) | Feb 13, 2023 |
| Dell          | XPS 15 9560                 | [01319ac289](https://linux-hardware.org/?probe=01319ac289) | Feb 13, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [f701208fd4](https://linux-hardware.org/?probe=f701208fd4) | Feb 13, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [3b7765dfcc](https://linux-hardware.org/?probe=3b7765dfcc) | Feb 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [6add161dbe](https://linux-hardware.org/?probe=6add161dbe) | Feb 13, 2023 |
| Dell          | Latitude 5511               | [161095d97a](https://linux-hardware.org/?probe=161095d97a) | Feb 13, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | [7e90fe56d1](https://linux-hardware.org/?probe=7e90fe56d1) | Feb 13, 2023 |
| MSI           | Raider GE77HX 12UHS         | [abd464b0d3](https://linux-hardware.org/?probe=abd464b0d3) | Feb 13, 2023 |
| HP            | ProBook 445 G7              | [7fdcffc633](https://linux-hardware.org/?probe=7fdcffc633) | Feb 13, 2023 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | [0560a363b8](https://linux-hardware.org/?probe=0560a363b8) | Feb 12, 2023 |
| Dell          | Venue 10 Pro 5055           | [7afcfff799](https://linux-hardware.org/?probe=7afcfff799) | Feb 12, 2023 |
| MACHENIKE     | MACHCREATOR-16              | [cde8e637d2](https://linux-hardware.org/?probe=cde8e637d2) | Feb 12, 2023 |
| MACHENIKE     | MACHCREATOR-16              | [a3ac4db738](https://linux-hardware.org/?probe=a3ac4db738) | Feb 12, 2023 |
| Acer          | Aspire A715-74G             | [cdd913ae48](https://linux-hardware.org/?probe=cdd913ae48) | Feb 12, 2023 |
| Dell          | Latitude E6420              | [6ffa1ea310](https://linux-hardware.org/?probe=6ffa1ea310) | Feb 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [04cfa15383](https://linux-hardware.org/?probe=04cfa15383) | Feb 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [3c8717baf4](https://linux-hardware.org/?probe=3c8717baf4) | Feb 12, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [8f74caf33e](https://linux-hardware.org/?probe=8f74caf33e) | Feb 12, 2023 |
| HP            | EliteBook 840 G5            | [b569293b7b](https://linux-hardware.org/?probe=b569293b7b) | Feb 12, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [a4b4558244](https://linux-hardware.org/?probe=a4b4558244) | Feb 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [1e3ceef5e6](https://linux-hardware.org/?probe=1e3ceef5e6) | Feb 12, 2023 |
| HP            | Notebook                    | [729f2b5250](https://linux-hardware.org/?probe=729f2b5250) | Feb 12, 2023 |
| HP            | Notebook                    | [155c8fa16e](https://linux-hardware.org/?probe=155c8fa16e) | Feb 12, 2023 |
| ASUSTek       | X510UAR                     | [365b6606cd](https://linux-hardware.org/?probe=365b6606cd) | Feb 12, 2023 |
| HUAWEI        | NBD-WXX9                    | [c8caa92db3](https://linux-hardware.org/?probe=c8caa92db3) | Feb 11, 2023 |
| Lenovo        | IdeaPad S540-15IWL          | [321710ca2d](https://linux-hardware.org/?probe=321710ca2d) | Feb 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [40116058d1](https://linux-hardware.org/?probe=40116058d1) | Feb 11, 2023 |
| HONOR         | BBR-WAX9                    | [de54b14304](https://linux-hardware.org/?probe=de54b14304) | Feb 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [8e00bdf032](https://linux-hardware.org/?probe=8e00bdf032) | Feb 11, 2023 |
| Dell          | Vostro 15 3515              | [22d5eabee5](https://linux-hardware.org/?probe=22d5eabee5) | Feb 11, 2023 |
| HP            | Pavilion Power Laptop 15... | [2beb0c0b30](https://linux-hardware.org/?probe=2beb0c0b30) | Feb 11, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [a1133b56be](https://linux-hardware.org/?probe=a1133b56be) | Feb 11, 2023 |
| ASUSTek       | G75VW                       | [e2eeee26af](https://linux-hardware.org/?probe=e2eeee26af) | Feb 11, 2023 |
| Acer          | Aspire A315-23              | [f56c83d6dd](https://linux-hardware.org/?probe=f56c83d6dd) | Feb 11, 2023 |
| Dell          | Latitude E7270              | [c684709755](https://linux-hardware.org/?probe=c684709755) | Feb 11, 2023 |
| Dell          | XPS 15 9500                 | [11222774d3](https://linux-hardware.org/?probe=11222774d3) | Feb 10, 2023 |
| Acer          | TravelMate 7730             | [a9a9e21b5a](https://linux-hardware.org/?probe=a9a9e21b5a) | Feb 10, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [a64bb02ece](https://linux-hardware.org/?probe=a64bb02ece) | Feb 10, 2023 |
| Dell          | Inspiron 7559               | [956a602343](https://linux-hardware.org/?probe=956a602343) | Feb 10, 2023 |
| ASUSTek       | ROG Strix G733QR_G733QR     | [da12318597](https://linux-hardware.org/?probe=da12318597) | Feb 10, 2023 |
| Dell          | XPS 13 9310                 | [0461c55b4a](https://linux-hardware.org/?probe=0461c55b4a) | Feb 10, 2023 |
| MSI           | Raider GE77HX 12UHS         | [d77cac7fb6](https://linux-hardware.org/?probe=d77cac7fb6) | Feb 10, 2023 |
| Apple         | MacBookPro11,3              | [b0ffb00d43](https://linux-hardware.org/?probe=b0ffb00d43) | Feb 10, 2023 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | [9b8563ab53](https://linux-hardware.org/?probe=9b8563ab53) | Feb 10, 2023 |
| Acer          | Swift SF314-54              | [8d92b8e7c5](https://linux-hardware.org/?probe=8d92b8e7c5) | Feb 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [3f4b71a601](https://linux-hardware.org/?probe=3f4b71a601) | Feb 09, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [25e4994344](https://linux-hardware.org/?probe=25e4994344) | Feb 09, 2023 |
| Lenovo        | ThinkPad T590 20N5S4R800    | [6a55f84594](https://linux-hardware.org/?probe=6a55f84594) | Feb 09, 2023 |
| HP            | EliteBook 8460p             | [91de8b5956](https://linux-hardware.org/?probe=91de8b5956) | Feb 09, 2023 |
| Monster       | TULPAR T7 V5.x              | [edc2a0bc35](https://linux-hardware.org/?probe=edc2a0bc35) | Feb 09, 2023 |
| Monster       | TULPAR T7 V5.x              | [8d1a082e35](https://linux-hardware.org/?probe=8d1a082e35) | Feb 09, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [8d2e488f38](https://linux-hardware.org/?probe=8d2e488f38) | Feb 09, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [467c3e9149](https://linux-hardware.org/?probe=467c3e9149) | Feb 09, 2023 |
| HP            | 2000                        | [f76b7389d7](https://linux-hardware.org/?probe=f76b7389d7) | Feb 09, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [81a3a141ba](https://linux-hardware.org/?probe=81a3a141ba) | Feb 08, 2023 |
| Acer          | Aspire A315-59              | [78d55087bb](https://linux-hardware.org/?probe=78d55087bb) | Feb 08, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C7C... | [26fb33ec6c](https://linux-hardware.org/?probe=26fb33ec6c) | Feb 08, 2023 |
| Dell          | Latitude 3570               | [dc460632ef](https://linux-hardware.org/?probe=dc460632ef) | Feb 08, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [bc2ea675c8](https://linux-hardware.org/?probe=bc2ea675c8) | Feb 08, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f268d3da5e](https://linux-hardware.org/?probe=f268d3da5e) | Feb 08, 2023 |
| ASUSTek       | X510UAR                     | [0b2a31bed4](https://linux-hardware.org/?probe=0b2a31bed4) | Feb 08, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS1... | [9bf97a14cf](https://linux-hardware.org/?probe=9bf97a14cf) | Feb 08, 2023 |
| ASUSTek       | X510UAR                     | [b440353d20](https://linux-hardware.org/?probe=b440353d20) | Feb 08, 2023 |
| Google        | Delbin                      | [268fbe9849](https://linux-hardware.org/?probe=268fbe9849) | Feb 08, 2023 |
| Google        | Delbin                      | [1afd4fec8d](https://linux-hardware.org/?probe=1afd4fec8d) | Feb 08, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS1... | [5e5ec021d0](https://linux-hardware.org/?probe=5e5ec021d0) | Feb 08, 2023 |
| Apple         | MacBookPro10,1              | [fd61c4416f](https://linux-hardware.org/?probe=fd61c4416f) | Feb 08, 2023 |
| HP            | Pavilion 17                 | [9bd81582a4](https://linux-hardware.org/?probe=9bd81582a4) | Feb 07, 2023 |
| HP            | Pavilion 17                 | [45eb87271b](https://linux-hardware.org/?probe=45eb87271b) | Feb 07, 2023 |
| TUXEDO        | InfinityBook S 14 Gen6      | [9e019a0396](https://linux-hardware.org/?probe=9e019a0396) | Feb 07, 2023 |
| MSI           | Modern 14 B11MOU            | [325806b7cc](https://linux-hardware.org/?probe=325806b7cc) | Feb 07, 2023 |
| MSI           | Modern 14 B11MOU            | [870a2912c9](https://linux-hardware.org/?probe=870a2912c9) | Feb 07, 2023 |
| HUAWEI        | MACH-WX9                    | [263101d492](https://linux-hardware.org/?probe=263101d492) | Feb 07, 2023 |
| Dell          | Latitude 5330               | [30cd96be4d](https://linux-hardware.org/?probe=30cd96be4d) | Feb 07, 2023 |
| Timi          | TM1613                      | [503133b0db](https://linux-hardware.org/?probe=503133b0db) | Feb 07, 2023 |
| Samsung       | 900X5N                      | [91793918de](https://linux-hardware.org/?probe=91793918de) | Feb 07, 2023 |
| HP            | Laptop 15-bw0xx             | [da8dac3c03](https://linux-hardware.org/?probe=da8dac3c03) | Feb 07, 2023 |
| Google        | Kefka                       | [5f290f685b](https://linux-hardware.org/?probe=5f290f685b) | Feb 06, 2023 |
| Dell          | Latitude 5490               | [95de125f35](https://linux-hardware.org/?probe=95de125f35) | Feb 06, 2023 |
| ASUSTek       | P453UA                      | [476ff28577](https://linux-hardware.org/?probe=476ff28577) | Feb 06, 2023 |
| MSI           | Stealth 15M B12UE           | [44de7ac1aa](https://linux-hardware.org/?probe=44de7ac1aa) | Feb 06, 2023 |
| ASUSTek       | G73Sw                       | [42e7c32817](https://linux-hardware.org/?probe=42e7c32817) | Feb 06, 2023 |
| Dell          | Inspiron 5749               | [2fbf439175](https://linux-hardware.org/?probe=2fbf439175) | Feb 06, 2023 |
| HONOR         | NMH-WCX9                    | [1f2418bafb](https://linux-hardware.org/?probe=1f2418bafb) | Feb 06, 2023 |
| Toshiba       | Satellite L50-B             | [fe59cbe322](https://linux-hardware.org/?probe=fe59cbe322) | Feb 06, 2023 |
| HP            | 2000                        | [5e672192b6](https://linux-hardware.org/?probe=5e672192b6) | Feb 06, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [f3ec6a2ed1](https://linux-hardware.org/?probe=f3ec6a2ed1) | Feb 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [da270fa237](https://linux-hardware.org/?probe=da270fa237) | Feb 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [69b76f313e](https://linux-hardware.org/?probe=69b76f313e) | Feb 05, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [de72d92ada](https://linux-hardware.org/?probe=de72d92ada) | Feb 05, 2023 |
| HUAWEI        | KLVL-WXX9                   | [c222b31f37](https://linux-hardware.org/?probe=c222b31f37) | Feb 05, 2023 |
| Google        | Kefka                       | [59e3f92752](https://linux-hardware.org/?probe=59e3f92752) | Feb 05, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | [a0fea9707e](https://linux-hardware.org/?probe=a0fea9707e) | Feb 05, 2023 |
| ASUSTek       | X556UV                      | [ae90dba4ca](https://linux-hardware.org/?probe=ae90dba4ca) | Feb 04, 2023 |
| Dell          | Inspiron 3593               | [2e87d3f607](https://linux-hardware.org/?probe=2e87d3f607) | Feb 04, 2023 |
| Dell          | Vostro 15 3515              | [c4c5c0888a](https://linux-hardware.org/?probe=c4c5c0888a) | Feb 04, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | [8771985f5b](https://linux-hardware.org/?probe=8771985f5b) | Feb 04, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | [9592836c3b](https://linux-hardware.org/?probe=9592836c3b) | Feb 04, 2023 |
| Dell          | XPS 15 9550                 | [200495d065](https://linux-hardware.org/?probe=200495d065) | Feb 04, 2023 |
| ASUSTek       | X200CA                      | [38cdc2564e](https://linux-hardware.org/?probe=38cdc2564e) | Feb 04, 2023 |
| HP            | Laptop 17-ak0xx             | [2ec4deba0b](https://linux-hardware.org/?probe=2ec4deba0b) | Feb 04, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [cfaa43cc81](https://linux-hardware.org/?probe=cfaa43cc81) | Feb 04, 2023 |
| ASUSTek       | X200CA                      | [8c2a91c204](https://linux-hardware.org/?probe=8c2a91c204) | Feb 04, 2023 |
| SiComputer    | Nauta 01C                   | [1579a837f7](https://linux-hardware.org/?probe=1579a837f7) | Feb 04, 2023 |
| HUAWEI        | CREM-WXX9                   | [43a0910ff6](https://linux-hardware.org/?probe=43a0910ff6) | Feb 04, 2023 |
| Lenovo        | ThinkPad P72 20MB0005GE     | [6322972a9c](https://linux-hardware.org/?probe=6322972a9c) | Feb 04, 2023 |
| MSI           | Stealth 15M B12UE           | [c0434c976e](https://linux-hardware.org/?probe=c0434c976e) | Feb 04, 2023 |
| HP            | ZBook Power 15.6 inch G9... | [1e38d08821](https://linux-hardware.org/?probe=1e38d08821) | Feb 03, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [0b73c3afe8](https://linux-hardware.org/?probe=0b73c3afe8) | Feb 03, 2023 |
| Dell          | Latitude 5530               | [dd0a933124](https://linux-hardware.org/?probe=dd0a933124) | Feb 03, 2023 |
| Dynabook      | PORTEGE X30L-K              | [af43366b45](https://linux-hardware.org/?probe=af43366b45) | Feb 03, 2023 |
| Acer          | Aspire 5750G                | [fa1e255519](https://linux-hardware.org/?probe=fa1e255519) | Feb 03, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [d7fff6982b](https://linux-hardware.org/?probe=d7fff6982b) | Feb 03, 2023 |
| Acer          | Aspire 5750G                | [ada6dd2b76](https://linux-hardware.org/?probe=ada6dd2b76) | Feb 03, 2023 |
| MACHENIKE     | MACHCREATOR-16              | [4608209d2d](https://linux-hardware.org/?probe=4608209d2d) | Feb 03, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [a1073e64f7](https://linux-hardware.org/?probe=a1073e64f7) | Feb 03, 2023 |
| Dell          | Latitude E6430              | [10b3b0cfbb](https://linux-hardware.org/?probe=10b3b0cfbb) | Feb 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [9c5cfbc1a1](https://linux-hardware.org/?probe=9c5cfbc1a1) | Feb 03, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [b660fd4859](https://linux-hardware.org/?probe=b660fd4859) | Feb 03, 2023 |
| ASUSTek       | UL30A                       | [11885376b2](https://linux-hardware.org/?probe=11885376b2) | Feb 03, 2023 |
| HP            | ProBook 440 G7              | [f9a4f80656](https://linux-hardware.org/?probe=f9a4f80656) | Feb 03, 2023 |
| ASUSTek       | G751JT                      | [2085089213](https://linux-hardware.org/?probe=2085089213) | Feb 03, 2023 |
| HUAWEI        | CREM-WXX9                   | [f794d33e76](https://linux-hardware.org/?probe=f794d33e76) | Feb 02, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [8c9b8348a4](https://linux-hardware.org/?probe=8c9b8348a4) | Feb 02, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [bd19e14a45](https://linux-hardware.org/?probe=bd19e14a45) | Feb 02, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [e49b22de8a](https://linux-hardware.org/?probe=e49b22de8a) | Feb 02, 2023 |
| Acer          | Aspire F5-573G              | [ba43497e32](https://linux-hardware.org/?probe=ba43497e32) | Feb 02, 2023 |
| Acer          | Aspire A715-42G             | [a169951063](https://linux-hardware.org/?probe=a169951063) | Feb 02, 2023 |
| HP            | EliteBook 840 G2            | [7dd8dceb80](https://linux-hardware.org/?probe=7dd8dceb80) | Feb 02, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [27c816b62a](https://linux-hardware.org/?probe=27c816b62a) | Feb 02, 2023 |
| HP            | EliteBook 840 G2            | [3339c49f38](https://linux-hardware.org/?probe=3339c49f38) | Feb 02, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [1c6ed7ede6](https://linux-hardware.org/?probe=1c6ed7ede6) | Feb 02, 2023 |
| ASUSTek       | ZenBook UX425JA_UX425JA     | [367646ee16](https://linux-hardware.org/?probe=367646ee16) | Feb 02, 2023 |
| Lenovo        | ZIWB2                       | [b7ff6b4dd5](https://linux-hardware.org/?probe=b7ff6b4dd5) | Feb 02, 2023 |
| ASUSTek       | K54L                        | [8568b17267](https://linux-hardware.org/?probe=8568b17267) | Feb 02, 2023 |
| Acer          | Aspire A715-42G             | [45890fca78](https://linux-hardware.org/?probe=45890fca78) | Feb 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [159a453649](https://linux-hardware.org/?probe=159a453649) | Feb 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [0538afb301](https://linux-hardware.org/?probe=0538afb301) | Feb 02, 2023 |
| Dell          | XPS 15 9510                 | [78ea388883](https://linux-hardware.org/?probe=78ea388883) | Feb 02, 2023 |
| MACHENIKE     | MACHCREATOR-16              | [81e773eade](https://linux-hardware.org/?probe=81e773eade) | Feb 02, 2023 |
| Dell          | Latitude E6430              | [55c398146b](https://linux-hardware.org/?probe=55c398146b) | Feb 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | [8bc290ef67](https://linux-hardware.org/?probe=8bc290ef67) | Feb 01, 2023 |
| MSI           | Modern 14 B11MOU            | [542173e9a2](https://linux-hardware.org/?probe=542173e9a2) | Feb 01, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [ab31f6153e](https://linux-hardware.org/?probe=ab31f6153e) | Feb 01, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [22abfb4a79](https://linux-hardware.org/?probe=22abfb4a79) | Feb 01, 2023 |
| Lenovo        | ThinkPad A485 20MVS0U500    | [b398a8e8e6](https://linux-hardware.org/?probe=b398a8e8e6) | Feb 01, 2023 |
| ASUSTek       | N552VW                      | [1ebeeec517](https://linux-hardware.org/?probe=1ebeeec517) | Feb 01, 2023 |
| Dell          | Inspiron 7501               | [426493e8a5](https://linux-hardware.org/?probe=426493e8a5) | Feb 01, 2023 |
| HP            | Laptop 14-dq4xxx            | [c102edf6a0](https://linux-hardware.org/?probe=c102edf6a0) | Feb 01, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [6b9dc508e1](https://linux-hardware.org/?probe=6b9dc508e1) | Feb 01, 2023 |
| Dell          | Inspiron 5748               | [7ee6505f8d](https://linux-hardware.org/?probe=7ee6505f8d) | Feb 01, 2023 |
| ASUSTek       | Zenbook UX8402ZA_UX8402Z... | [1d212c67b2](https://linux-hardware.org/?probe=1d212c67b2) | Jan 31, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [70310e25d1](https://linux-hardware.org/?probe=70310e25d1) | Jan 31, 2023 |
| HUAWEI        | HN-WX9X                     | [4b8ddf5d09](https://linux-hardware.org/?probe=4b8ddf5d09) | Jan 31, 2023 |
| Dell          | Inspiron 5748               | [ecbd4ac8b6](https://linux-hardware.org/?probe=ecbd4ac8b6) | Jan 31, 2023 |
| Lenovo        | ThinkPad T530 2429F27       | [85ac6a588d](https://linux-hardware.org/?probe=85ac6a588d) | Jan 31, 2023 |
| ASUSTek       | Zenbook UX8402ZA_UX8402Z... | [4dcc88b215](https://linux-hardware.org/?probe=4dcc88b215) | Jan 31, 2023 |
| TUXEDO        | Stellaris Intel Gen4        | [2df9f60f2e](https://linux-hardware.org/?probe=2df9f60f2e) | Jan 31, 2023 |
| Acer          | Predator PH315-52           | [b1c77eb9c7](https://linux-hardware.org/?probe=b1c77eb9c7) | Jan 31, 2023 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | [a64ae29757](https://linux-hardware.org/?probe=a64ae29757) | Jan 31, 2023 |
| Samsung       | 550XCJ/550XCR               | [75fad3daf3](https://linux-hardware.org/?probe=75fad3daf3) | Jan 31, 2023 |
| Dell          | XPS 15 9570                 | [ee60c1c921](https://linux-hardware.org/?probe=ee60c1c921) | Jan 31, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | [87904d9d06](https://linux-hardware.org/?probe=87904d9d06) | Jan 31, 2023 |
| MACHENIKE     | MACHCREATOR-16              | [c44c077d1e](https://linux-hardware.org/?probe=c44c077d1e) | Jan 30, 2023 |
| Dell          | Vostro 15 3515              | [357d14774f](https://linux-hardware.org/?probe=357d14774f) | Jan 30, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603ZX... | [7442c84b55](https://linux-hardware.org/?probe=7442c84b55) | Jan 30, 2023 |
| Dell          | Latitude 7480               | [f3a84b494f](https://linux-hardware.org/?probe=f3a84b494f) | Jan 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1ecef01472](https://linux-hardware.org/?probe=1ecef01472) | Jan 30, 2023 |
| HP            | Pavilion 15                 | [6ceccb3d73](https://linux-hardware.org/?probe=6ceccb3d73) | Jan 30, 2023 |
| Lenovo        | ThinkPad T430 2347G4U       | [5802e6b9b9](https://linux-hardware.org/?probe=5802e6b9b9) | Jan 30, 2023 |
| Dell          | XPS 15 9570                 | [1d06f2715a](https://linux-hardware.org/?probe=1d06f2715a) | Jan 30, 2023 |
| Dell          | Vostro 7620                 | [b6d43b8741](https://linux-hardware.org/?probe=b6d43b8741) | Jan 29, 2023 |
| MACHENIKE     | MACHCREATOR-16              | [e3d7c03a2e](https://linux-hardware.org/?probe=e3d7c03a2e) | Jan 29, 2023 |
| Lenovo        | 3000 N200 0769BAG           | [f8f410eb2a](https://linux-hardware.org/?probe=f8f410eb2a) | Jan 29, 2023 |
| HP            | Laptop 14-cm0xxx            | [9b93652159](https://linux-hardware.org/?probe=9b93652159) | Jan 29, 2023 |
| Acer          | Aspire V5-573G              | [e253d5b49b](https://linux-hardware.org/?probe=e253d5b49b) | Jan 29, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [32d5472e21](https://linux-hardware.org/?probe=32d5472e21) | Jan 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [47246aa8b5](https://linux-hardware.org/?probe=47246aa8b5) | Jan 29, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [dd07a46c6a](https://linux-hardware.org/?probe=dd07a46c6a) | Jan 29, 2023 |
| TECNO         | MEGABOOK T1                 | [db0e6c89b4](https://linux-hardware.org/?probe=db0e6c89b4) | Jan 29, 2023 |
| Lenovo        | IdeaPad S340-14IML 81N9     | [58e620077b](https://linux-hardware.org/?probe=58e620077b) | Jan 29, 2023 |
| Razer         | Blade 15 (2022) - RZ09-0... | [41d33a9029](https://linux-hardware.org/?probe=41d33a9029) | Jan 29, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [086e08a04b](https://linux-hardware.org/?probe=086e08a04b) | Jan 29, 2023 |
| Acer          | Aspire 5733                 | [da753d74a1](https://linux-hardware.org/?probe=da753d74a1) | Jan 29, 2023 |
| Dell          | XPS 13 7390                 | [60c03ee1f7](https://linux-hardware.org/?probe=60c03ee1f7) | Jan 29, 2023 |
| HP            | EliteBook 840 G1            | [30549ebd3a](https://linux-hardware.org/?probe=30549ebd3a) | Jan 28, 2023 |
| HP            | Laptop 15-da2xxx            | [8384a02b4b](https://linux-hardware.org/?probe=8384a02b4b) | Jan 28, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [53015adc9d](https://linux-hardware.org/?probe=53015adc9d) | Jan 28, 2023 |
| HUAWEI        | MACH-WX9                    | [5b00f79b72](https://linux-hardware.org/?probe=5b00f79b72) | Jan 28, 2023 |
| HP            | ENVY Laptop 17-cg0xxx       | [ed1ce46901](https://linux-hardware.org/?probe=ed1ce46901) | Jan 28, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [844e4e4b2a](https://linux-hardware.org/?probe=844e4e4b2a) | Jan 28, 2023 |
| HP            | ENVY Laptop 17-cg0xxx       | [ab3f84f96b](https://linux-hardware.org/?probe=ab3f84f96b) | Jan 28, 2023 |
| Apple         | MacBookPro11,4              | [8a5423443a](https://linux-hardware.org/?probe=8a5423443a) | Jan 28, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [7e6cf30d81](https://linux-hardware.org/?probe=7e6cf30d81) | Jan 28, 2023 |
| Timi          | A35S                        | [b6611f9b22](https://linux-hardware.org/?probe=b6611f9b22) | Jan 28, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [4a82904f14](https://linux-hardware.org/?probe=4a82904f14) | Jan 28, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [fb7b1bdaf5](https://linux-hardware.org/?probe=fb7b1bdaf5) | Jan 27, 2023 |
| Lenovo        | ThinkPad T450s 20BWS23W0... | [41c82dbadb](https://linux-hardware.org/?probe=41c82dbadb) | Jan 27, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [a69331d2ea](https://linux-hardware.org/?probe=a69331d2ea) | Jan 27, 2023 |
| Acer          | Swift SF314-511             | [c47b08d2a9](https://linux-hardware.org/?probe=c47b08d2a9) | Jan 27, 2023 |
| HONOR         | BMH-WCX9                    | [882bb3b505](https://linux-hardware.org/?probe=882bb3b505) | Jan 27, 2023 |
| MECHREVO      | Code10-7CC6U                | [86e769b2a3](https://linux-hardware.org/?probe=86e769b2a3) | Jan 27, 2023 |
| Dell          | XPS 15 7590                 | [4ecf66ddd9](https://linux-hardware.org/?probe=4ecf66ddd9) | Jan 27, 2023 |
| Dell          | Precision 3550              | [4c42615cef](https://linux-hardware.org/?probe=4c42615cef) | Jan 27, 2023 |
| HUAWEI        | BOHB-WAX9                   | [00e21c8359](https://linux-hardware.org/?probe=00e21c8359) | Jan 27, 2023 |
| Dynabook      | TECRA A50-J                 | [a2ad3f4eb3](https://linux-hardware.org/?probe=a2ad3f4eb3) | Jan 27, 2023 |
| Dynabook      | TECRA A50-J                 | [3921b100b4](https://linux-hardware.org/?probe=3921b100b4) | Jan 27, 2023 |
| ASUSTek       | X550VX                      | [37d2157b37](https://linux-hardware.org/?probe=37d2157b37) | Jan 26, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | [9dfc820ceb](https://linux-hardware.org/?probe=9dfc820ceb) | Jan 26, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | [0168a5cae2](https://linux-hardware.org/?probe=0168a5cae2) | Jan 26, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [4024f7c3bd](https://linux-hardware.org/?probe=4024f7c3bd) | Jan 26, 2023 |
| ASUSTek       | K55VD                       | [b2b19ec3f1](https://linux-hardware.org/?probe=b2b19ec3f1) | Jan 26, 2023 |
| Acer          | Swift SF314-511             | [9c04ff43a3](https://linux-hardware.org/?probe=9c04ff43a3) | Jan 26, 2023 |
| Lenovo        | ThinkPad T495 20NKS01Y00    | [a1dfc58700](https://linux-hardware.org/?probe=a1dfc58700) | Jan 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [303593899d](https://linux-hardware.org/?probe=303593899d) | Jan 26, 2023 |
| Dell          | Latitude 7480               | [3cb61c5b71](https://linux-hardware.org/?probe=3cb61c5b71) | Jan 26, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HM... | [26f64a2ad0](https://linux-hardware.org/?probe=26f64a2ad0) | Jan 26, 2023 |
| GPU Compan... | GWTN156-11                  | [e7f1ea09b5](https://linux-hardware.org/?probe=e7f1ea09b5) | Jan 26, 2023 |
| Multilaser    | PC150                       | [1c4ace00d1](https://linux-hardware.org/?probe=1c4ace00d1) | Jan 26, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 D... | [d2a46bd14a](https://linux-hardware.org/?probe=d2a46bd14a) | Jan 26, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | [8725d530e5](https://linux-hardware.org/?probe=8725d530e5) | Jan 26, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [ea142e4848](https://linux-hardware.org/?probe=ea142e4848) | Jan 25, 2023 |
| HP            | EliteBook 2540p             | [f03240c746](https://linux-hardware.org/?probe=f03240c746) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [af63cfc79a](https://linux-hardware.org/?probe=af63cfc79a) | Jan 25, 2023 |
| Clevo         | M815P                       | [cfc5f6689f](https://linux-hardware.org/?probe=cfc5f6689f) | Jan 25, 2023 |
| MSI           | GL63 8RC                    | [138e8de541](https://linux-hardware.org/?probe=138e8de541) | Jan 25, 2023 |
| Acer          | Aspire A315-59              | [33292253d0](https://linux-hardware.org/?probe=33292253d0) | Jan 25, 2023 |
| HP            | ZBook Power 15.6 inch G9... | [dd2f21ab84](https://linux-hardware.org/?probe=dd2f21ab84) | Jan 25, 2023 |
| Dynabook      | TECRA A50-J                 | [2f24f18672](https://linux-hardware.org/?probe=2f24f18672) | Jan 25, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [993ba3e73b](https://linux-hardware.org/?probe=993ba3e73b) | Jan 25, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [aa6488b6b8](https://linux-hardware.org/?probe=aa6488b6b8) | Jan 25, 2023 |
| Fujitsu Si... | AMILO Notebook Xa 3530      | [e8384494a3](https://linux-hardware.org/?probe=e8384494a3) | Jan 25, 2023 |
| Dell          | Inspiron 5402               | [d8df4aafe8](https://linux-hardware.org/?probe=d8df4aafe8) | Jan 25, 2023 |
| Dell          | Inspiron 5468               | [3e59c1f38b](https://linux-hardware.org/?probe=3e59c1f38b) | Jan 25, 2023 |
| Acer          | Nitro AN515-42              | [cb02367642](https://linux-hardware.org/?probe=cb02367642) | Jan 25, 2023 |
| Dell          | Latitude 5420               | [cd6dc3695e](https://linux-hardware.org/?probe=cd6dc3695e) | Jan 24, 2023 |
| Dell          | Latitude 5520               | [662284824b](https://linux-hardware.org/?probe=662284824b) | Jan 24, 2023 |
| HP            | ProBook 6570b               | [841250ba59](https://linux-hardware.org/?probe=841250ba59) | Jan 24, 2023 |
| Dell          | Latitude E6410              | [854634fb32](https://linux-hardware.org/?probe=854634fb32) | Jan 24, 2023 |
| Dell          | Latitude E6410              | [a5edbef8d2](https://linux-hardware.org/?probe=a5edbef8d2) | Jan 24, 2023 |
| Lenovo        | ThinkPad T500 2082BPG       | [08a30fd24c](https://linux-hardware.org/?probe=08a30fd24c) | Jan 24, 2023 |
| Lenovo        | ThinkPad E15 20RD0011RT     | [3fb25133ec](https://linux-hardware.org/?probe=3fb25133ec) | Jan 24, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [c2226035ce](https://linux-hardware.org/?probe=c2226035ce) | Jan 24, 2023 |
| Google        | Treeya                      | [27a381272a](https://linux-hardware.org/?probe=27a381272a) | Jan 24, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [a227de29c5](https://linux-hardware.org/?probe=a227de29c5) | Jan 24, 2023 |
| Dell          | Precision 3551              | [1338d3df20](https://linux-hardware.org/?probe=1338d3df20) | Jan 23, 2023 |
| HP            | ProBook 430 G8 Notebook ... | [335275777a](https://linux-hardware.org/?probe=335275777a) | Jan 23, 2023 |
| Dell          | Latitude 3420               | [d2a8b9657a](https://linux-hardware.org/?probe=d2a8b9657a) | Jan 23, 2023 |
| Dell          | Latitude 7490               | [e40bb2f01f](https://linux-hardware.org/?probe=e40bb2f01f) | Jan 23, 2023 |
| Dell          | Latitude 7490               | [31789ae630](https://linux-hardware.org/?probe=31789ae630) | Jan 23, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [091effd2ac](https://linux-hardware.org/?probe=091effd2ac) | Jan 23, 2023 |
| Apple         | MacBookPro9,1               | [0a597ba033](https://linux-hardware.org/?probe=0a597ba033) | Jan 23, 2023 |
| MACHENIKE     | MACHCREATOR-16              | [7b3107564a](https://linux-hardware.org/?probe=7b3107564a) | Jan 23, 2023 |
| Lenovo        | Erazer Z500 20226           | [6e7a21c6d5](https://linux-hardware.org/?probe=6e7a21c6d5) | Jan 23, 2023 |
| MACHENIKE     | MACHCREATOR-16              | [6b370a283e](https://linux-hardware.org/?probe=6b370a283e) | Jan 23, 2023 |
| Lenovo        | Erazer Z500 20226           | [7d6077c27c](https://linux-hardware.org/?probe=7d6077c27c) | Jan 23, 2023 |
| Apple         | MacBookPro9,1               | [90884b19a9](https://linux-hardware.org/?probe=90884b19a9) | Jan 23, 2023 |
| Lenovo        | ThinkPad P50 20EQS12Q3M     | [e46b5a8b46](https://linux-hardware.org/?probe=e46b5a8b46) | Jan 23, 2023 |
| Dell          | Latitude E6500              | [ba7c36fe15](https://linux-hardware.org/?probe=ba7c36fe15) | Jan 23, 2023 |
| Dynabook      | TECRA A50-J                 | [689fe06d4d](https://linux-hardware.org/?probe=689fe06d4d) | Jan 23, 2023 |
| Dynabook      | TECRA A50-J                 | [92690b43cd](https://linux-hardware.org/?probe=92690b43cd) | Jan 23, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [d03b7c0a68](https://linux-hardware.org/?probe=d03b7c0a68) | Jan 22, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [07005e3e32](https://linux-hardware.org/?probe=07005e3e32) | Jan 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | [d999192dbf](https://linux-hardware.org/?probe=d999192dbf) | Jan 22, 2023 |
| HP            | EliteBook 820 G3            | [3edd4ab0dc](https://linux-hardware.org/?probe=3edd4ab0dc) | Jan 22, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [523d0331a1](https://linux-hardware.org/?probe=523d0331a1) | Jan 21, 2023 |
| HP            | Victus by Gaming Laptop ... | [0aa98390a7](https://linux-hardware.org/?probe=0aa98390a7) | Jan 21, 2023 |
| Acer          | Predator G9-591             | [0544a1b07c](https://linux-hardware.org/?probe=0544a1b07c) | Jan 21, 2023 |
| Dell          | XPS 9315                    | [9dfb19b7c1](https://linux-hardware.org/?probe=9dfb19b7c1) | Jan 21, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [e8a0c0066b](https://linux-hardware.org/?probe=e8a0c0066b) | Jan 21, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [adeb24c41e](https://linux-hardware.org/?probe=adeb24c41e) | Jan 21, 2023 |
| Dell          | G5 5587                     | [96ca22c550](https://linux-hardware.org/?probe=96ca22c550) | Jan 21, 2023 |
| Dell          | G5 5587                     | [a070a8ba69](https://linux-hardware.org/?probe=a070a8ba69) | Jan 21, 2023 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [c228c064b7](https://linux-hardware.org/?probe=c228c064b7) | Jan 20, 2023 |
| Positivo B... | VJFE43F11X-XXXXXX           | [138a9b3b0c](https://linux-hardware.org/?probe=138a9b3b0c) | Jan 20, 2023 |
| Dell          | Venue 8 Pro 5830            | [4f815d5b4f](https://linux-hardware.org/?probe=4f815d5b4f) | Jan 20, 2023 |
| Acer          | Aspire A315-42G             | [ed4c536efa](https://linux-hardware.org/?probe=ed4c536efa) | Jan 20, 2023 |
| Lenovo        | ThinkPad T490 20N3S0E000    | [d324a863a5](https://linux-hardware.org/?probe=d324a863a5) | Jan 20, 2023 |
| ASUSTek       | ZenBook UX434IQ_UM433IQ     | [17b4a2466c](https://linux-hardware.org/?probe=17b4a2466c) | Jan 20, 2023 |
| Acer          | Aspire A515-45              | [9d5faff505](https://linux-hardware.org/?probe=9d5faff505) | Jan 20, 2023 |
| MSI           | GS66 Stealth 10UE           | [d5a2a6aaa8](https://linux-hardware.org/?probe=d5a2a6aaa8) | Jan 19, 2023 |
| Positivo B... | VJFE43F11X-XXXXXX           | [cc9e6f8862](https://linux-hardware.org/?probe=cc9e6f8862) | Jan 19, 2023 |
| SLIMBOOK      | TITAN                       | [15c0522754](https://linux-hardware.org/?probe=15c0522754) | Jan 19, 2023 |
| SLIMBOOK      | TITAN                       | [e81652a68c](https://linux-hardware.org/?probe=e81652a68c) | Jan 19, 2023 |
| Dell          | Precision 3551              | [4ff5a0ab8d](https://linux-hardware.org/?probe=4ff5a0ab8d) | Jan 19, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [440ff298e7](https://linux-hardware.org/?probe=440ff298e7) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [0f079e1dc7](https://linux-hardware.org/?probe=0f079e1dc7) | Jan 19, 2023 |
| Acer          | Aspire A315-23              | [90049e4bb7](https://linux-hardware.org/?probe=90049e4bb7) | Jan 19, 2023 |
| Acer          | Nitro AN515-42              | [d6a24ede85](https://linux-hardware.org/?probe=d6a24ede85) | Jan 19, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [6a47296f0c](https://linux-hardware.org/?probe=6a47296f0c) | Jan 19, 2023 |
| Dell          | Latitude 3410               | [187aebc2cd](https://linux-hardware.org/?probe=187aebc2cd) | Jan 19, 2023 |
| Intel Clie... | LAPRC510                    | [6d570a1aee](https://linux-hardware.org/?probe=6d570a1aee) | Jan 19, 2023 |
| HP            | ENVY Laptop 17-ce0xxx       | [1a0f3869dd](https://linux-hardware.org/?probe=1a0f3869dd) | Jan 18, 2023 |
| ASUSTek       | X455LF                      | [9995b86c04](https://linux-hardware.org/?probe=9995b86c04) | Jan 18, 2023 |
| HP            | Victus by Gaming Laptop ... | [533d99e2f1](https://linux-hardware.org/?probe=533d99e2f1) | Jan 18, 2023 |
| Lenovo        | ThinkPad E15 20RD0011RT     | [d27ca45841](https://linux-hardware.org/?probe=d27ca45841) | Jan 18, 2023 |
| Dell          | Precision 3561              | [9528d74be6](https://linux-hardware.org/?probe=9528d74be6) | Jan 18, 2023 |
| Dell          | Precision 3561              | [5f23addbde](https://linux-hardware.org/?probe=5f23addbde) | Jan 18, 2023 |
| Acer          | Swift SFX14-41G             | [1b916fe30d](https://linux-hardware.org/?probe=1b916fe30d) | Jan 18, 2023 |
| Lenovo        | Yoga 500-14IHW 80N5         | [e233e8d6d2](https://linux-hardware.org/?probe=e233e8d6d2) | Jan 18, 2023 |
| Acer          | Nitro AN515-54              | [4a997fa99d](https://linux-hardware.org/?probe=4a997fa99d) | Jan 17, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [a81a940d33](https://linux-hardware.org/?probe=a81a940d33) | Jan 17, 2023 |
| HP            | Laptop 17-ca0xxx            | [a8fbe01fc5](https://linux-hardware.org/?probe=a8fbe01fc5) | Jan 17, 2023 |
| Acer          | Aspire A315-59              | [469c40ec75](https://linux-hardware.org/?probe=469c40ec75) | Jan 17, 2023 |
| Timi          | Xiaomi NoteBook Pro         | [681de2b0c1](https://linux-hardware.org/?probe=681de2b0c1) | Jan 17, 2023 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [aa6ca0d358](https://linux-hardware.org/?probe=aa6ca0d358) | Jan 17, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [7b36d7e8eb](https://linux-hardware.org/?probe=7b36d7e8eb) | Jan 17, 2023 |
| Timi          | Xiaomi NoteBook Pro         | [f1ee502754](https://linux-hardware.org/?probe=f1ee502754) | Jan 17, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [0d91852ebf](https://linux-hardware.org/?probe=0d91852ebf) | Jan 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c16356f056](https://linux-hardware.org/?probe=c16356f056) | Jan 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [70b8007dcc](https://linux-hardware.org/?probe=70b8007dcc) | Jan 17, 2023 |
| Acer          | Aspire AV14-51              | [596219796d](https://linux-hardware.org/?probe=596219796d) | Jan 17, 2023 |
| HUAWEI        | BOHB-WAX9                   | [b39c4fc9b7](https://linux-hardware.org/?probe=b39c4fc9b7) | Jan 16, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | [1c81e8c322](https://linux-hardware.org/?probe=1c81e8c322) | Jan 16, 2023 |
| Dell          | Inspiron 11 - 3147          | [af542a44ad](https://linux-hardware.org/?probe=af542a44ad) | Jan 16, 2023 |
| PC Special... | Recoil II RTX               | [33850c8810](https://linux-hardware.org/?probe=33850c8810) | Jan 16, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [b53dd87f87](https://linux-hardware.org/?probe=b53dd87f87) | Jan 16, 2023 |
| Schenker      | XMG CORE 15 (M22)           | [6c2b631f12](https://linux-hardware.org/?probe=6c2b631f12) | Jan 16, 2023 |
| HP            | 15                          | [ae082994e2](https://linux-hardware.org/?probe=ae082994e2) | Jan 16, 2023 |
| Acer          | Nitro AN515-46              | [1de96d005a](https://linux-hardware.org/?probe=1de96d005a) | Jan 16, 2023 |
| Acer          | Nitro AN515-46              | [f0eab1c81a](https://linux-hardware.org/?probe=f0eab1c81a) | Jan 16, 2023 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [e1aa5d3186](https://linux-hardware.org/?probe=e1aa5d3186) | Jan 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [1a51848ffb](https://linux-hardware.org/?probe=1a51848ffb) | Jan 16, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [b36eb94e80](https://linux-hardware.org/?probe=b36eb94e80) | Jan 16, 2023 |
| HP            | 255 G6 Notebook PC          | [4d2e9f3ee4](https://linux-hardware.org/?probe=4d2e9f3ee4) | Jan 16, 2023 |
| Lenovo        | ThinkPad T440s 20AQ0069G... | [cb2e9f2623](https://linux-hardware.org/?probe=cb2e9f2623) | Jan 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [8fb168e741](https://linux-hardware.org/?probe=8fb168e741) | Jan 16, 2023 |
| Lenovo        | ThinkPad T460s 20FAS5QW0... | [dd953776aa](https://linux-hardware.org/?probe=dd953776aa) | Jan 16, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [a38eb750aa](https://linux-hardware.org/?probe=a38eb750aa) | Jan 16, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [9ac2f0ab83](https://linux-hardware.org/?probe=9ac2f0ab83) | Jan 15, 2023 |
| HP            | EliteBook 840 G2            | [4850c49a4a](https://linux-hardware.org/?probe=4850c49a4a) | Jan 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [448ae92dc8](https://linux-hardware.org/?probe=448ae92dc8) | Jan 15, 2023 |
| HP            | EliteBook 840 G2            | [972e3e026a](https://linux-hardware.org/?probe=972e3e026a) | Jan 15, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [57d99b139f](https://linux-hardware.org/?probe=57d99b139f) | Jan 15, 2023 |
| Acer          | Aspire A515-43              | [cefbe7ee6e](https://linux-hardware.org/?probe=cefbe7ee6e) | Jan 15, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [fcc6481e2a](https://linux-hardware.org/?probe=fcc6481e2a) | Jan 15, 2023 |
| HP            | Pavilion Laptop 14-bk0xx    | [ebe90b5052](https://linux-hardware.org/?probe=ebe90b5052) | Jan 15, 2023 |
| Dell          | Inspiron N5110              | [20625ce99d](https://linux-hardware.org/?probe=20625ce99d) | Jan 14, 2023 |
| HP            | Pavilion dv6                | [60f339781c](https://linux-hardware.org/?probe=60f339781c) | Jan 14, 2023 |
| Olivetti      | Olibook P55-431W850-8G50... | [fe5c9c2425](https://linux-hardware.org/?probe=fe5c9c2425) | Jan 14, 2023 |
| Olivetti      | Olibook P55-431W850-8G50... | [649546bc61](https://linux-hardware.org/?probe=649546bc61) | Jan 14, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [86fff559f5](https://linux-hardware.org/?probe=86fff559f5) | Jan 14, 2023 |
| HP            | Pavilion Laptop 14-bk0xx    | [bcbf941284](https://linux-hardware.org/?probe=bcbf941284) | Jan 14, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [efffe2d61b](https://linux-hardware.org/?probe=efffe2d61b) | Jan 14, 2023 |
| MSI           | PS63 Modern 8RC             | [e55e0d9d0a](https://linux-hardware.org/?probe=e55e0d9d0a) | Jan 14, 2023 |
| HP            | ZBook 15 G4                 | [3325b8ab60](https://linux-hardware.org/?probe=3325b8ab60) | Jan 14, 2023 |
| System76      | Oryx Pro                    | [f706b667bb](https://linux-hardware.org/?probe=f706b667bb) | Jan 14, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [5047da7461](https://linux-hardware.org/?probe=5047da7461) | Jan 14, 2023 |
| Acer          | Swift SF314-43              | [e292f699eb](https://linux-hardware.org/?probe=e292f699eb) | Jan 14, 2023 |
| Acer          | Nitro AN515-54              | [ea080033f1](https://linux-hardware.org/?probe=ea080033f1) | Jan 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [9096450d56](https://linux-hardware.org/?probe=9096450d56) | Jan 14, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [bbf1dabe59](https://linux-hardware.org/?probe=bbf1dabe59) | Jan 14, 2023 |
| Dell          | Latitude 7430               | [9caa5939ef](https://linux-hardware.org/?probe=9caa5939ef) | Jan 13, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [61c432b134](https://linux-hardware.org/?probe=61c432b134) | Jan 13, 2023 |
| Apple         | MacBookPro11,3              | [c94f291c81](https://linux-hardware.org/?probe=c94f291c81) | Jan 13, 2023 |
| Acer          | Nitro AN515-44              | [b2c96e31d9](https://linux-hardware.org/?probe=b2c96e31d9) | Jan 13, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [810b2daeef](https://linux-hardware.org/?probe=810b2daeef) | Jan 13, 2023 |
| Toshiba       | Satellite L855D             | [0606d04520](https://linux-hardware.org/?probe=0606d04520) | Jan 13, 2023 |
| Dell          | Inspiron 5721               | [b9435f9f7d](https://linux-hardware.org/?probe=b9435f9f7d) | Jan 13, 2023 |
| Acer          | Predator PH315-52           | [c6a710b940](https://linux-hardware.org/?probe=c6a710b940) | Jan 13, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [64c403ce6d](https://linux-hardware.org/?probe=64c403ce6d) | Jan 13, 2023 |
| Lenovo        | ThinkPad T495s 20QKS2R40... | [28d821da5f](https://linux-hardware.org/?probe=28d821da5f) | Jan 13, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [f9d244586a](https://linux-hardware.org/?probe=f9d244586a) | Jan 13, 2023 |
| Lenovo        | ThinkPad T495s 20QKS2R40... | [e78a057172](https://linux-hardware.org/?probe=e78a057172) | Jan 13, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [05899ebb86](https://linux-hardware.org/?probe=05899ebb86) | Jan 13, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [033a92981f](https://linux-hardware.org/?probe=033a92981f) | Jan 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [4236e82f21](https://linux-hardware.org/?probe=4236e82f21) | Jan 13, 2023 |
| Acer          | Predator PT515-51           | [150f12dceb](https://linux-hardware.org/?probe=150f12dceb) | Jan 12, 2023 |
| Dell          | G15 5520                    | [1aeaf74f9a](https://linux-hardware.org/?probe=1aeaf74f9a) | Jan 12, 2023 |
| HP            | ProBook 450 G6              | [f675188c46](https://linux-hardware.org/?probe=f675188c46) | Jan 12, 2023 |
| Lenovo        | ThinkPad T430 2347B85       | [01fce134df](https://linux-hardware.org/?probe=01fce134df) | Jan 12, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [e9783891d1](https://linux-hardware.org/?probe=e9783891d1) | Jan 12, 2023 |
| Acer          | Nitro AN517-42              | [c8440739f9](https://linux-hardware.org/?probe=c8440739f9) | Jan 12, 2023 |
| Dell          | Latitude E5550              | [0b14eb18d9](https://linux-hardware.org/?probe=0b14eb18d9) | Jan 12, 2023 |
| Lenovo        | ThinkPad T430 2349W1C       | [1f310a8a2e](https://linux-hardware.org/?probe=1f310a8a2e) | Jan 12, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [fad743f278](https://linux-hardware.org/?probe=fad743f278) | Jan 12, 2023 |
| HUAWEI        | KLVL-WXXW                   | [1270cfda4e](https://linux-hardware.org/?probe=1270cfda4e) | Jan 11, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [8c1eb7fc02](https://linux-hardware.org/?probe=8c1eb7fc02) | Jan 11, 2023 |
| Dell          | Latitude E5550              | [5e76d378f9](https://linux-hardware.org/?probe=5e76d378f9) | Jan 11, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [ec0f3564ed](https://linux-hardware.org/?probe=ec0f3564ed) | Jan 11, 2023 |
| Acer          | Aspire A315-59              | [a436e3e89f](https://linux-hardware.org/?probe=a436e3e89f) | Jan 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [c79ad1fc10](https://linux-hardware.org/?probe=c79ad1fc10) | Jan 11, 2023 |
| Acer          | Predator G9-591             | [aa9794813e](https://linux-hardware.org/?probe=aa9794813e) | Jan 11, 2023 |
| Dell          | Latitude E7440              | [bfdc9dfc63](https://linux-hardware.org/?probe=bfdc9dfc63) | Jan 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [25090a9dcb](https://linux-hardware.org/?probe=25090a9dcb) | Jan 11, 2023 |
| MSI           | Modern 14 B4MW              | [815ee96451](https://linux-hardware.org/?probe=815ee96451) | Jan 11, 2023 |
| HP            | Pavilion Laptop 13-bb0xx... | [790736a10e](https://linux-hardware.org/?probe=790736a10e) | Jan 11, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [fdb726b276](https://linux-hardware.org/?probe=fdb726b276) | Jan 11, 2023 |
| Infinix       | INBOOK X2                   | [11aac46bdc](https://linux-hardware.org/?probe=11aac46bdc) | Jan 10, 2023 |
| ASUSTek       | X510UAR                     | [dc3e0fffe7](https://linux-hardware.org/?probe=dc3e0fffe7) | Jan 10, 2023 |
| ASUSTek       | X510UAR                     | [53d6bec0e8](https://linux-hardware.org/?probe=53d6bec0e8) | Jan 10, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [62ddf88d2d](https://linux-hardware.org/?probe=62ddf88d2d) | Jan 10, 2023 |
| Lenovo        | ThinkPad T590 20N5S4R800    | [51d6d75e64](https://linux-hardware.org/?probe=51d6d75e64) | Jan 10, 2023 |
| ASUSTek       | FX503VD                     | [c3a958527e](https://linux-hardware.org/?probe=c3a958527e) | Jan 10, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [37b5b1648e](https://linux-hardware.org/?probe=37b5b1648e) | Jan 10, 2023 |
| Lenovo        | ThinkPad P53 20QNS00X00     | [e16ef8937b](https://linux-hardware.org/?probe=e16ef8937b) | Jan 09, 2023 |
| HP            | ProBook 4520s               | [8e1eba4ad4](https://linux-hardware.org/?probe=8e1eba4ad4) | Jan 09, 2023 |
| Alienware     | m15 Ryzen Ed. R5            | [ef83299ad4](https://linux-hardware.org/?probe=ef83299ad4) | Jan 09, 2023 |
| Chuwi         | GemiBook                    | [918dc5f283](https://linux-hardware.org/?probe=918dc5f283) | Jan 09, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [ad39556257](https://linux-hardware.org/?probe=ad39556257) | Jan 09, 2023 |
| HP            | EliteBook 850 G4            | [e6cb9446f5](https://linux-hardware.org/?probe=e6cb9446f5) | Jan 09, 2023 |
| HP            | Laptop 15-da1xxx            | [2fa89881b4](https://linux-hardware.org/?probe=2fa89881b4) | Jan 09, 2023 |
| Dell          | XPS 15 9520                 | [2e13f150e6](https://linux-hardware.org/?probe=2e13f150e6) | Jan 09, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [6e756926b8](https://linux-hardware.org/?probe=6e756926b8) | Jan 09, 2023 |
| Apple         | MacBookPro11,1              | [92a4be502c](https://linux-hardware.org/?probe=92a4be502c) | Jan 09, 2023 |
| Acer          | Iconia W700                 | [bcfec36896](https://linux-hardware.org/?probe=bcfec36896) | Jan 09, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HM... | [8be13470fb](https://linux-hardware.org/?probe=8be13470fb) | Jan 09, 2023 |
| Lenovo        | IdeaPad 720-15IKB 81AG      | [8c76c72880](https://linux-hardware.org/?probe=8c76c72880) | Jan 08, 2023 |
| HP            | ProBook 6465b               | [336f10e70b](https://linux-hardware.org/?probe=336f10e70b) | Jan 08, 2023 |
| ASUSTek       | X541UVK                     | [50e9caee7f](https://linux-hardware.org/?probe=50e9caee7f) | Jan 08, 2023 |
| Lenovo        | V330-15IKB 81AX             | [1ca4c751d8](https://linux-hardware.org/?probe=1ca4c751d8) | Jan 08, 2023 |
| Framework     | Laptop                      | [0c13e3ab8d](https://linux-hardware.org/?probe=0c13e3ab8d) | Jan 08, 2023 |
| Acer          | Aspire A315-41              | [b4ed141fd3](https://linux-hardware.org/?probe=b4ed141fd3) | Jan 08, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CR... | [ff783dac11](https://linux-hardware.org/?probe=ff783dac11) | Jan 08, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D4C... | [d2e10cee5b](https://linux-hardware.org/?probe=d2e10cee5b) | Jan 08, 2023 |
| Dell          | Latitude 3450               | [e4e8bee1cb](https://linux-hardware.org/?probe=e4e8bee1cb) | Jan 08, 2023 |
| HP            | EliteBook 745 G5            | [b732d98167](https://linux-hardware.org/?probe=b732d98167) | Jan 08, 2023 |
| Acer          | Aspire A715-42G             | [206359e4ad](https://linux-hardware.org/?probe=206359e4ad) | Jan 08, 2023 |
| ASUSTek       | ROG Strix G512LI_G512LI     | [f75fea559f](https://linux-hardware.org/?probe=f75fea559f) | Jan 08, 2023 |
| Acer          | Aspire A715-42G             | [eed9db8255](https://linux-hardware.org/?probe=eed9db8255) | Jan 08, 2023 |
| Lenovo        | ThinkPad P53 20QNS00X00     | [6290949f56](https://linux-hardware.org/?probe=6290949f56) | Jan 08, 2023 |
| HP            | ZBook Fury 15 G7 Mobile ... | [2b8c216e1a](https://linux-hardware.org/?probe=2b8c216e1a) | Jan 08, 2023 |
| Dell          | Vostro 15-3568              | [a6c731c83b](https://linux-hardware.org/?probe=a6c731c83b) | Jan 08, 2023 |
| Dell          | Inspiron 5567               | [a43647cad6](https://linux-hardware.org/?probe=a43647cad6) | Jan 08, 2023 |
| Acer          | Predator PT515-51           | [a33d9c5a74](https://linux-hardware.org/?probe=a33d9c5a74) | Jan 07, 2023 |
| HP            | EliteBook 850 G6            | [595e6fa89a](https://linux-hardware.org/?probe=595e6fa89a) | Jan 07, 2023 |
| Dell          | XPS 15 9510                 | [f0a688060c](https://linux-hardware.org/?probe=f0a688060c) | Jan 07, 2023 |
| Lenovo        | ThinkPad T530 2392CTO       | [8c1cf48875](https://linux-hardware.org/?probe=8c1cf48875) | Jan 07, 2023 |
| Framework     | Laptop                      | [cfabfdec3c](https://linux-hardware.org/?probe=cfabfdec3c) | Jan 07, 2023 |
| System76      | Lemur Pro                   | [36156d9aa7](https://linux-hardware.org/?probe=36156d9aa7) | Jan 07, 2023 |
| Dell          | Inspiron 13 5320            | [0007a36030](https://linux-hardware.org/?probe=0007a36030) | Jan 07, 2023 |
| HP            | EliteBook 840 G3            | [667330c83f](https://linux-hardware.org/?probe=667330c83f) | Jan 07, 2023 |
| HP            | ZBook Studio G5             | [dfd35ce9ca](https://linux-hardware.org/?probe=dfd35ce9ca) | Jan 07, 2023 |
| Alienware     | m15 Ryzen Ed. R5            | [bf4c8770e7](https://linux-hardware.org/?probe=bf4c8770e7) | Jan 07, 2023 |
| Dell          | Inspiron 7577               | [ff95fa094b](https://linux-hardware.org/?probe=ff95fa094b) | Jan 06, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [1fc8d104f7](https://linux-hardware.org/?probe=1fc8d104f7) | Jan 06, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [0a6589c07d](https://linux-hardware.org/?probe=0a6589c07d) | Jan 06, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [ab29e81efd](https://linux-hardware.org/?probe=ab29e81efd) | Jan 06, 2023 |
| HP            | Laptop 15s-eq2xxx           | [684653e302](https://linux-hardware.org/?probe=684653e302) | Jan 06, 2023 |
| Acer          | Aspire A515-47              | [896288776d](https://linux-hardware.org/?probe=896288776d) | Jan 06, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [9946b25232](https://linux-hardware.org/?probe=9946b25232) | Jan 06, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [fd5120fea6](https://linux-hardware.org/?probe=fd5120fea6) | Jan 06, 2023 |
| Lenovo        | ThinkPad T430 2349KB4       | [4546ecbe85](https://linux-hardware.org/?probe=4546ecbe85) | Jan 06, 2023 |
| Chuwi         | HeroBook Air                | [58434d2c3c](https://linux-hardware.org/?probe=58434d2c3c) | Jan 06, 2023 |
| Dell          | XPS 15 9520                 | [ec6743fa1b](https://linux-hardware.org/?probe=ec6743fa1b) | Jan 06, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [c84d3b6b03](https://linux-hardware.org/?probe=c84d3b6b03) | Jan 06, 2023 |
| Dell          | G15 5525                    | [2c61cbc942](https://linux-hardware.org/?probe=2c61cbc942) | Jan 06, 2023 |
| HP            | 240 G8                      | [efc7e61483](https://linux-hardware.org/?probe=efc7e61483) | Jan 06, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [cddb2a7b81](https://linux-hardware.org/?probe=cddb2a7b81) | Jan 06, 2023 |
| Lenovo        | Z50-75 80EC                 | [7fe70dc4c8](https://linux-hardware.org/?probe=7fe70dc4c8) | Jan 06, 2023 |
| Apple         | MacBookPro12,1              | [0cca8fbbb6](https://linux-hardware.org/?probe=0cca8fbbb6) | Jan 05, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [c47405aaf4](https://linux-hardware.org/?probe=c47405aaf4) | Jan 05, 2023 |
| Lenovo        | ThinkPad X220 4290KJ6       | [8296e61afd](https://linux-hardware.org/?probe=8296e61afd) | Jan 05, 2023 |
| Acer          | Predator PT515-51           | [77651b16db](https://linux-hardware.org/?probe=77651b16db) | Jan 05, 2023 |
| Lenovo        | ThinkPad T460 20FMS49100    | [28af5637ef](https://linux-hardware.org/?probe=28af5637ef) | Jan 05, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [1d25f1df44](https://linux-hardware.org/?probe=1d25f1df44) | Jan 05, 2023 |
| Lenovo        | ThinkPad T460 20FMS49100    | [4605f322cb](https://linux-hardware.org/?probe=4605f322cb) | Jan 05, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [31f9cd0972](https://linux-hardware.org/?probe=31f9cd0972) | Jan 05, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [a2ec6616aa](https://linux-hardware.org/?probe=a2ec6616aa) | Jan 05, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [8ac0b43549](https://linux-hardware.org/?probe=8ac0b43549) | Jan 05, 2023 |
| MSI           | Modern 14 B4MW              | [b7855a84cf](https://linux-hardware.org/?probe=b7855a84cf) | Jan 05, 2023 |
| Lenovo        | ThinkPad T460s 20FAS5QW0... | [4853686d6c](https://linux-hardware.org/?probe=4853686d6c) | Jan 05, 2023 |
| HP            | EliteBook 840 G5 NOTEBOO... | [343d0f4c48](https://linux-hardware.org/?probe=343d0f4c48) | Jan 04, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [e06b51ae0a](https://linux-hardware.org/?probe=e06b51ae0a) | Jan 04, 2023 |
| ASUSTek       | X510UAR                     | [39f45e87d1](https://linux-hardware.org/?probe=39f45e87d1) | Jan 04, 2023 |
| ASUSTek       | X510UAR                     | [2f4bb5b17d](https://linux-hardware.org/?probe=2f4bb5b17d) | Jan 04, 2023 |
| Chuwi         | GemiBook Pro                | [272d23ec5d](https://linux-hardware.org/?probe=272d23ec5d) | Jan 04, 2023 |
| HP            | EliteBook 840 G3            | [76f2ef98b9](https://linux-hardware.org/?probe=76f2ef98b9) | Jan 04, 2023 |
| Acer          | Swift SF314-43              | [50d8f0c1cb](https://linux-hardware.org/?probe=50d8f0c1cb) | Jan 04, 2023 |
| HP            | Notebook                    | [679c0bfbe8](https://linux-hardware.org/?probe=679c0bfbe8) | Jan 04, 2023 |
| HP            | EliteBook 845 14 inch G9... | [26826e3c23](https://linux-hardware.org/?probe=26826e3c23) | Jan 04, 2023 |
| Dell          | XPS 15 9550                 | [72f8edfe5b](https://linux-hardware.org/?probe=72f8edfe5b) | Jan 04, 2023 |
| HP            | ZBook 15 G3                 | [6a38362bbe](https://linux-hardware.org/?probe=6a38362bbe) | Jan 04, 2023 |
| Unknown       | Unknown                     | [b363093f89](https://linux-hardware.org/?probe=b363093f89) | Jan 04, 2023 |
| Acer          | Nitro AN515-45              | [5741654cdc](https://linux-hardware.org/?probe=5741654cdc) | Jan 04, 2023 |
| MSI           | Modern 14 B11MOU            | [036ae164e8](https://linux-hardware.org/?probe=036ae164e8) | Jan 04, 2023 |
| Toshiba       | Satellite C75D-B            | [d5380976a2](https://linux-hardware.org/?probe=d5380976a2) | Jan 03, 2023 |
| Clevo         | M815P                       | [7f1503c5e6](https://linux-hardware.org/?probe=7f1503c5e6) | Jan 03, 2023 |
| MSI           | Katana GF66 11SC            | [d788f444ff](https://linux-hardware.org/?probe=d788f444ff) | Jan 03, 2023 |
| HP            | ProBook 6570b               | [875054c6d7](https://linux-hardware.org/?probe=875054c6d7) | Jan 03, 2023 |
| ASUSTek       | X453MA                      | [1584b0616c](https://linux-hardware.org/?probe=1584b0616c) | Jan 03, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [40af3a30ca](https://linux-hardware.org/?probe=40af3a30ca) | Jan 03, 2023 |
| Lenovo        | ThinkPad T590 20N5S2NC1V    | [c621679405](https://linux-hardware.org/?probe=c621679405) | Jan 03, 2023 |
| HP            | 240 G8 Notebook PC          | [a316608c78](https://linux-hardware.org/?probe=a316608c78) | Jan 03, 2023 |
| Lenovo        | ThinkPad T460s 20FAS5QW0... | [373efc41b0](https://linux-hardware.org/?probe=373efc41b0) | Jan 03, 2023 |
| MSI           | Katana GF66 11SC            | [5a078a161f](https://linux-hardware.org/?probe=5a078a161f) | Jan 03, 2023 |
| Lenovo        | ThinkPad T530 24296FG       | [303cb1bd6f](https://linux-hardware.org/?probe=303cb1bd6f) | Jan 02, 2023 |
| Toshiba       | Satellite C50-A             | [9b02393248](https://linux-hardware.org/?probe=9b02393248) | Jan 02, 2023 |
| HP            | Notebook                    | [530e6cfeb9](https://linux-hardware.org/?probe=530e6cfeb9) | Jan 02, 2023 |
| Clevo         | M815P                       | [034cecc238](https://linux-hardware.org/?probe=034cecc238) | Jan 02, 2023 |
| HP            | ZBook 15 G3                 | [7ef67aea7b](https://linux-hardware.org/?probe=7ef67aea7b) | Jan 02, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [daeb060f32](https://linux-hardware.org/?probe=daeb060f32) | Jan 02, 2023 |
| Acer          | Aspire A315-31              | [4a79c65764](https://linux-hardware.org/?probe=4a79c65764) | Jan 02, 2023 |
| ASUSTek       | X756UXK                     | [f0bc632c50](https://linux-hardware.org/?probe=f0bc632c50) | Jan 02, 2023 |
| Dell          | Latitude 7410               | [acb8ce902e](https://linux-hardware.org/?probe=acb8ce902e) | Jan 01, 2023 |
| Dell          | Inspiron 5580               | [c6a044c898](https://linux-hardware.org/?probe=c6a044c898) | Jan 01, 2023 |
| Acer          | Aspire A315-59              | [f84116ec07](https://linux-hardware.org/?probe=f84116ec07) | Jan 01, 2023 |
| Dell          | Latitude E7240              | [ca82922df4](https://linux-hardware.org/?probe=ca82922df4) | Jan 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [5a95ae3186](https://linux-hardware.org/?probe=5a95ae3186) | Jan 01, 2023 |
| Fujitsu       | LIFEBOOK U749               | [c09072c09f](https://linux-hardware.org/?probe=c09072c09f) | Jan 01, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [f438866c0d](https://linux-hardware.org/?probe=f438866c0d) | Jan 01, 2023 |
| Acer          | Aspire 4750                 | [f871c26332](https://linux-hardware.org/?probe=f871c26332) | Jan 01, 2023 |
| Lenovo        | ThinkPad X270 20K60018GE    | [a92939c1f5](https://linux-hardware.org/?probe=a92939c1f5) | Jan 01, 2023 |
| Lenovo        | ThinkPad X390 20Q00051GE    | [5b3d1b750d](https://linux-hardware.org/?probe=5b3d1b750d) | Dec 31, 2022 |
| Valve         | Jupiter                     | [c0fb48bccb](https://linux-hardware.org/?probe=c0fb48bccb) | Dec 31, 2022 |
| System76      | Oryx Pro                    | [0d65e57758](https://linux-hardware.org/?probe=0d65e57758) | Dec 31, 2022 |
| Lenovo        | ThinkPad X390 20Q00051GE    | [775096be09](https://linux-hardware.org/?probe=775096be09) | Dec 31, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [322cf5484d](https://linux-hardware.org/?probe=322cf5484d) | Dec 31, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [5fbe1632b0](https://linux-hardware.org/?probe=5fbe1632b0) | Dec 31, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [5a479fed95](https://linux-hardware.org/?probe=5a479fed95) | Dec 31, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [591d985e85](https://linux-hardware.org/?probe=591d985e85) | Dec 31, 2022 |
| HP            | Pavilion dv6700             | [4b3b106bee](https://linux-hardware.org/?probe=4b3b106bee) | Dec 30, 2022 |
| MACHENIKE     | MACHCREATOR-16              | [f7ed4a6609](https://linux-hardware.org/?probe=f7ed4a6609) | Dec 30, 2022 |
| Dell          | Inspiron 3421               | [d2cd50a2a6](https://linux-hardware.org/?probe=d2cd50a2a6) | Dec 30, 2022 |
| Timi          | A35S                        | [c62c9ae956](https://linux-hardware.org/?probe=c62c9ae956) | Dec 30, 2022 |
| Dell          | Inspiron 3421               | [ae7d821823](https://linux-hardware.org/?probe=ae7d821823) | Dec 30, 2022 |
| Dell          | XPS 15 9520                 | [19b4bfd852](https://linux-hardware.org/?probe=19b4bfd852) | Dec 30, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| Fedora 36 | 1209      | 18.35%  |
| Fedora 37 | 1056      | 16.02%  |
| Fedora 35 | 960       | 14.57%  |
| Fedora 34 | 935       | 14.19%  |
| Fedora 33 | 855       | 12.97%  |
| Fedora 32 | 746       | 11.32%  |
| Fedora 31 | 503       | 7.63%   |
| Fedora 30 | 162       | 2.46%   |
| Fedora 29 | 90        | 1.37%   |
| Fedora 38 | 30        | 0.46%   |
| Fedora 28 | 22        | 0.33%   |
| Fedora 27 | 8         | 0.12%   |
| Fedora 39 | 4         | 0.06%   |
| Fedora 24 | 4         | 0.06%   |
| Fedora 21 | 4         | 0.06%   |
| Fedora 25 | 2         | 0.03%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Fedora | 5911      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 5.17.5-300.fc36.x86_64  | 111       | 1.51%   |
| 5.16.18-200.fc35.x86_64 | 92        | 1.25%   |
| 5.9.16-200.fc33.x86_64  | 90        | 1.22%   |
| 5.11.12-300.fc34.x86_64 | 77        | 1.05%   |
| 6.0.7-301.fc37.x86_64   | 76        | 1.03%   |
| 6.0.15-300.fc37.x86_64  | 75        | 1.02%   |
| 6.0.5-200.fc36.x86_64   | 69        | 0.94%   |
| 5.14.10-300.fc35.x86_64 | 69        | 0.94%   |
| 5.8.16-300.fc33.x86_64  | 64        | 0.87%   |
| 5.18.13-200.fc36.x86_64 | 61        | 0.83%   |
| 5.8.15-301.fc33.x86_64  | 60        | 0.81%   |
| 6.1.14-200.fc37.x86_64  | 59        | 0.8%    |
| 5.8.4-200.fc32.x86_64   | 57        | 0.77%   |
| 6.1.7-200.fc37.x86_64   | 56        | 0.76%   |
| 6.0.8-300.fc37.x86_64   | 54        | 0.73%   |
| 5.13.12-200.fc34.x86_64 | 54        | 0.73%   |
| 6.0.9-300.fc37.x86_64   | 51        | 0.69%   |
| 6.0.12-300.fc37.x86_64  | 51        | 0.69%   |
| 6.1.18-200.fc37.x86_64  | 50        | 0.68%   |
| 5.18.11-200.fc36.x86_64 | 50        | 0.68%   |
| 5.19.16-200.fc36.x86_64 | 47        | 0.64%   |
| 5.8.18-300.fc33.x86_64  | 46        | 0.62%   |
| 5.17.11-300.fc36.x86_64 | 46        | 0.62%   |
| 5.14.16-301.fc35.x86_64 | 46        | 0.62%   |
| 5.9.8-200.fc33.x86_64   | 45        | 0.61%   |
| 5.18.16-200.fc36.x86_64 | 45        | 0.61%   |
| 5.16.16-200.fc35.x86_64 | 44        | 0.6%    |
| 6.1.8-200.fc37.x86_64   | 43        | 0.58%   |
| 5.17.6-300.fc36.x86_64  | 43        | 0.58%   |
| 6.1.11-200.fc37.x86_64  | 42        | 0.57%   |
| 5.19.9-200.fc36.x86_64  | 42        | 0.57%   |
| 5.15.6-200.fc35.x86_64  | 42        | 0.57%   |
| 5.16.12-200.fc35.x86_64 | 41        | 0.56%   |
| 5.10.19-200.fc33.x86_64 | 41        | 0.56%   |
| 5.9.11-200.fc33.x86_64  | 40        | 0.54%   |
| 6.1.9-200.fc37.x86_64   | 39        | 0.53%   |
| 5.3.16-300.fc31.x86_64  | 39        | 0.53%   |
| 5.18.17-200.fc36.x86_64 | 39        | 0.53%   |
| 5.12.13-300.fc34.x86_64 | 39        | 0.53%   |
| 5.7.8-200.fc32.x86_64   | 38        | 0.52%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.17.5  | 145       | 1.97%   |
| 5.9.16  | 96        | 1.3%    |
| 5.16.18 | 95        | 1.29%   |
| 5.8.15  | 87        | 1.18%   |
| 6.0.7   | 86        | 1.17%   |
| 6.0.15  | 85        | 1.15%   |
| 5.11.12 | 84        | 1.14%   |
| 5.8.16  | 81        | 1.1%    |
| 5.14.10 | 78        | 1.06%   |
| 6.0.5   | 75        | 1.02%   |
| 5.19.16 | 75        | 1.02%   |
| 6.0.9   | 66        | 0.9%    |
| 5.11.11 | 66        | 0.9%    |
| 5.18.13 | 65        | 0.88%   |
| 6.0.8   | 64        | 0.87%   |
| 5.8.18  | 64        | 0.87%   |
| 6.1.14  | 62        | 0.84%   |
| 6.1.7   | 60        | 0.82%   |
| 6.0.12  | 58        | 0.79%   |
| 5.8.4   | 57        | 0.77%   |
| 5.13.12 | 57        | 0.77%   |
| 5.14.18 | 56        | 0.76%   |
| 5.18.11 | 53        | 0.72%   |
| 5.14.16 | 52        | 0.71%   |
| 6.1.18  | 51        | 0.69%   |
| 5.9.8   | 51        | 0.69%   |
| 5.19.8  | 50        | 0.68%   |
| 5.17.11 | 50        | 0.68%   |
| 5.15.6  | 50        | 0.68%   |
| 5.19.9  | 49        | 0.67%   |
| 5.18.16 | 48        | 0.65%   |
| 5.17.6  | 47        | 0.64%   |
| 5.16.16 | 47        | 0.64%   |
| 6.1.8   | 46        | 0.63%   |
| 5.16.12 | 46        | 0.63%   |
| 6.1.11  | 45        | 0.61%   |
| 6.0.10  | 45        | 0.61%   |
| 5.10.19 | 45        | 0.61%   |
| 5.6.6   | 44        | 0.6%    |
| 5.18.5  | 44        | 0.6%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.0     | 621       | 8.83%   |
| 5.17    | 509       | 7.24%   |
| 6.1     | 473       | 6.73%   |
| 5.8     | 464       | 6.6%    |
| 5.11    | 449       | 6.39%   |
| 5.19    | 446       | 6.35%   |
| 5.18    | 409       | 5.82%   |
| 5.14    | 392       | 5.58%   |
| 5.16    | 384       | 5.46%   |
| 5.15    | 310       | 4.41%   |
| 5.9     | 304       | 4.32%   |
| 5.13    | 303       | 4.31%   |
| 5.10    | 293       | 4.17%   |
| 5.6     | 286       | 4.07%   |
| 5.12    | 282       | 4.01%   |
| 5.7     | 221       | 3.14%   |
| 5.3     | 194       | 2.76%   |
| 5.5     | 183       | 2.6%    |
| 5.4     | 168       | 2.39%   |
| 6.2     | 89        | 1.27%   |
| 5.0     | 61        | 0.87%   |
| 5.2     | 47        | 0.67%   |
| 5.1     | 43        | 0.61%   |
| 4.19    | 30        | 0.43%   |
| 4.18    | 27        | 0.38%   |
| 4.20    | 18        | 0.26%   |
| 4.16    | 3         | 0.04%   |
| 4.15    | 3         | 0.04%   |
| 4.11    | 3         | 0.04%   |
| 4.1     | 3         | 0.04%   |
| 6.3     | 2         | 0.03%   |
| 4.8     | 2         | 0.03%   |
| 4.17    | 2         | 0.03%   |
| 4.5     | 1         | 0.01%   |
| 4.14    | 1         | 0.01%   |
| 4.10    | 1         | 0.01%   |
| 3.17    | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 5902      | 99.83%  |
| i686    | 5         | 0.08%   |
| aarch64 | 4         | 0.07%   |
| Unknown | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 4463      | 73.37%  |
| KDE5            | 666       | 10.95%  |
| Unknown         | 304       | 5%      |
| KDE             | 136       | 2.24%   |
| XFCE            | 130       | 2.14%   |
| X-Cinnamon      | 84        | 1.38%   |
| MATE            | 83        | 1.36%   |
| Cinnamon        | 69        | 1.13%   |
| i3              | 30        | 0.49%   |
| LXQt            | 21        | 0.35%   |
| GNOME Classic   | 21        | 0.35%   |
| LXDE            | 16        | 0.26%   |
| sway            | 15        | 0.25%   |
| Deepin          | 12        | 0.2%    |
| Pantheon        | 4         | 0.07%   |
| awesome         | 4         | 0.07%   |
| openbox         | 3         | 0.05%   |
| KDE4            | 3         | 0.05%   |
| GNOME Flashback | 3         | 0.05%   |
| fluxbox         | 3         | 0.05%   |
| Budgie          | 3         | 0.05%   |
| xinit-compat    | 2         | 0.03%   |
| dwm             | 2         | 0.03%   |
| bspwm           | 2         | 0.03%   |
| xmonad          | 1         | 0.02%   |
| qtile           | 1         | 0.02%   |
| KDE:old         | 1         | 0.02%   |
| GNOME-Classic   | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 3943      | 64.23%  |
| X11     | 1954      | 31.83%  |
| Unknown | 197       | 3.21%   |
| Tty     | 45        | 0.73%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 3031      | 49.86%  |
| GDM     | 2282      | 37.54%  |
| SDDM    | 425       | 6.99%   |
| LightDM | 229       | 3.77%   |
| TDM     | 87        | 1.43%   |
| XDM     | 10        | 0.16%   |
| KDM     | 8         | 0.13%   |
| LXDM    | 5         | 0.08%   |
| Ly      | 1         | 0.02%   |
| GREETD  | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 3069      | 50.93%  |
| en_GB   | 402       | 6.67%   |
| Unknown | 367       | 6.09%   |
| pt_BR   | 280       | 4.65%   |
| ru_RU   | 274       | 4.55%   |
| de_DE   | 206       | 3.42%   |
| fr_FR   | 180       | 2.99%   |
| it_IT   | 163       | 2.7%    |
| pl_PL   | 100       | 1.66%   |
| es_ES   | 92        | 1.53%   |
| en_CA   | 84        | 1.39%   |
| en_IN   | 77        | 1.28%   |
| en_AU   | 77        | 1.28%   |
| es_MX   | 54        | 0.9%    |
| cs_CZ   | 40        | 0.66%   |
| es_CL   | 34        | 0.56%   |
| tr_TR   | 31        | 0.51%   |
| es_AR   | 31        | 0.51%   |
| zh_CN   | 28        | 0.46%   |
| nl_NL   | 24        | 0.4%    |
| de_AT   | 22        | 0.37%   |
| sv_SE   | 20        | 0.33%   |
| pt_PT   | 20        | 0.33%   |
| en_NZ   | 20        | 0.33%   |
| C       | 20        | 0.33%   |
| es_CO   | 18        | 0.3%    |
| hu_HU   | 17        | 0.28%   |
| en_DK   | 17        | 0.28%   |
| en_IE   | 15        | 0.25%   |
| en_ZA   | 14        | 0.23%   |
| fr_CA   | 12        | 0.2%    |
| fi_FI   | 12        | 0.2%    |
| ru_UA   | 11        | 0.18%   |
| fr_BE   | 11        | 0.18%   |
| de_CH   | 10        | 0.17%   |
| nb_NO   | 9         | 0.15%   |
| uk_UA   | 8         | 0.13%   |
| sk_SK   | 8         | 0.13%   |
| en_SG   | 8         | 0.13%   |
| da_DK   | 8         | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 4775      | 79.69%  |
| BIOS | 1217      | 20.31%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type                | Notebooks | Percent |
|---------------------|-----------|---------|
| Btrfs               | 3528      | 58.17%  |
| Ext4                | 2174      | 35.85%  |
| Unknown             | 195       | 3.22%   |
| Xfs                 | 147       | 2.42%   |
| Overlay             | 11        | 0.18%   |
| F2fs                | 3         | 0.05%   |
| Ext3                | 3         | 0.05%   |
| Zfs                 | 2         | 0.03%   |
| Fuse.fuse-overlayfs | 2         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 3017      | 49.88%  |
| GPT     | 2647      | 43.76%  |
| MBR     | 385       | 6.36%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 5432      | 90.78%  |
| Yes       | 552       | 9.22%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 4866      | 81.29%  |
| Yes       | 1120      | 18.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 1765      | 29.86%  |
| Dell                   | 1082      | 18.3%   |
| Hewlett-Packard        | 872       | 14.75%  |
| ASUSTek Computer       | 593       | 10.03%  |
| Acer                   | 395       | 6.68%   |
| Apple                  | 149       | 2.52%   |
| MSI                    | 134       | 2.27%   |
| HUAWEI                 | 117       | 1.98%   |
| Toshiba                | 85        | 1.44%   |
| Samsung Electronics    | 79        | 1.34%   |
| Sony                   | 47        | 0.8%    |
| Notebook               | 47        | 0.8%    |
| Timi                   | 39        | 0.66%   |
| Framework              | 30        | 0.51%   |
| Unknown                | 30        | 0.51%   |
| Google                 | 25        | 0.42%   |
| Alienware              | 25        | 0.42%   |
| Fujitsu                | 24        | 0.41%   |
| Positivo               | 22        | 0.37%   |
| TUXEDO                 | 18        | 0.3%    |
| System76               | 18        | 0.3%    |
| LG Electronics         | 16        | 0.27%   |
| Razer                  | 15        | 0.25%   |
| Chuwi                  | 11        | 0.19%   |
| HONOR                  | 10        | 0.17%   |
| Gigabyte Technology    | 10        | 0.17%   |
| Avell High Performance | 10        | 0.17%   |
| PC Specialist          | 8         | 0.14%   |
| SLIMBOOK               | 7         | 0.12%   |
| Schenker               | 7         | 0.12%   |
| Panasonic              | 7         | 0.12%   |
| GPU Company            | 7         | 0.12%   |
| GPD                    | 7         | 0.12%   |
| Fujitsu Siemens        | 7         | 0.12%   |
| Packard Bell           | 6         | 0.1%    |
| Hampoo                 | 6         | 0.1%    |
| Clevo                  | 6         | 0.1%    |
| Standard               | 5         | 0.08%   |
| Gateway                | 5         | 0.08%   |
| eMachines              | 5         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 50        | 0.85%   |
| HP Notebook                                | 30        | 0.51%   |
| Dell XPS 15 9570                           | 25        | 0.42%   |
| Framework Laptop                           | 23        | 0.39%   |
| Dell XPS 15 7590                           | 22        | 0.37%   |
| Dell XPS 13 9370                           | 21        | 0.36%   |
| Dell Latitude 7490                         | 21        | 0.36%   |
| Dell XPS 15 9560                           | 19        | 0.32%   |
| Dell XPS 13 9360                           | 19        | 0.32%   |
| HP EliteBook 840 G6                        | 18        | 0.3%    |
| Dell XPS 13 9310                           | 18        | 0.3%    |
| Dell XPS 13 7390                           | 18        | 0.3%    |
| HP Pavilion dv6                            | 17        | 0.29%   |
| Dell XPS 15 9550                           | 16        | 0.27%   |
| HP Pavilion 15                             | 15        | 0.25%   |
| Dell XPS 15 9500                           | 15        | 0.25%   |
| Dell Latitude E7450                        | 15        | 0.25%   |
| HP Laptop 15-da0xxx                        | 14        | 0.24%   |
| Dell XPS 13 9300                           | 14        | 0.24%   |
| Lenovo ThinkPad X1 Carbon Gen 8 20U9CTO1WW | 13        | 0.22%   |
| Lenovo ThinkBook 15 G2 ITL 20VE            | 13        | 0.22%   |
| HP Pavilion Notebook                       | 13        | 0.22%   |
| Dell Latitude E6420                        | 13        | 0.22%   |
| Dell Latitude 5480                         | 13        | 0.22%   |
| Dell Inspiron 15 7000 Gaming               | 13        | 0.22%   |
| Apple MacBookPro12,1                       | 13        | 0.22%   |
| Lenovo IdeaPad 5 15ARE05 81YQ              | 12        | 0.2%    |
| HUAWEI KLVL-WXX9                           | 12        | 0.2%    |
| HP EliteBook 840 G3                        | 12        | 0.2%    |
| Dell Latitude E7440                        | 12        | 0.2%    |
| Dell Inspiron 5570                         | 12        | 0.2%    |
| HUAWEI NBLK-WAX9X                          | 11        | 0.19%   |
| ASUS ROG Zephyrus G14 GA401QM_GA401QM      | 11        | 0.19%   |
| Apple MacBookPro9,2                        | 11        | 0.19%   |
| Acer Aspire E5-573G                        | 11        | 0.19%   |
| HUAWEI MACH-WX9                            | 10        | 0.17%   |
| HP Pavilion dv7                            | 10        | 0.17%   |
| Dell XPS 15 9510                           | 10        | 0.17%   |
| Dell XPS 13 9380                           | 10        | 0.17%   |
| Dell XPS 13 9350                           | 10        | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 1089      | 18.42%  |
| Lenovo IdeaPad     | 350       | 5.92%   |
| Dell Latitude      | 322       | 5.45%   |
| Dell Inspiron      | 305       | 5.16%   |
| Acer Aspire        | 252       | 4.26%   |
| Dell XPS           | 251       | 4.25%   |
| HP Pavilion        | 185       | 3.13%   |
| HP EliteBook       | 172       | 2.91%   |
| HP ProBook         | 138       | 2.33%   |
| HP Laptop          | 123       | 2.08%   |
| ASUS VivoBook      | 112       | 1.89%   |
| ASUS ROG           | 92        | 1.56%   |
| Dell Precision     | 86        | 1.45%   |
| Toshiba Satellite  | 73        | 1.23%   |
| Lenovo Legion      | 66        | 1.12%   |
| Lenovo ThinkBook   | 65        | 1.1%    |
| Dell Vostro        | 55        | 0.93%   |
| Acer Nitro         | 52        | 0.88%   |
| Lenovo Yoga        | 51        | 0.86%   |
| ASUS ASUS          | 50        | 0.85%   |
| Unknown            | 50        | 0.85%   |
| HP ZBook           | 49        | 0.83%   |
| ASUS ZenBook       | 47        | 0.8%    |
| Acer Swift         | 41        | 0.69%   |
| HP ENVY            | 36        | 0.61%   |
| Apple MacBookPro11 | 31        | 0.52%   |
| HP Notebook        | 30        | 0.51%   |
| Framework Laptop   | 30        | 0.51%   |
| HP OMEN            | 29        | 0.49%   |
| ASUS TUF           | 28        | 0.47%   |
| MSI Modern         | 22        | 0.37%   |
| Fujitsu LIFEBOOK   | 20        | 0.34%   |
| Dell G5            | 19        | 0.32%   |
| Acer Predator      | 18        | 0.3%    |
| HP 250             | 16        | 0.27%   |
| Razer Blade        | 14        | 0.24%   |
| Apple MacBookPro9  | 14        | 0.24%   |
| Dell G3            | 13        | 0.22%   |
| Apple MacBookPro12 | 13        | 0.22%   |
| HUAWEI KLVL-WXX9   | 12        | 0.2%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 817       | 13.82%  |
| 2019    | 785       | 13.28%  |
| 2021    | 669       | 11.32%  |
| 2018    | 644       | 10.89%  |
| 2017    | 466       | 7.88%   |
| 2015    | 378       | 6.39%   |
| 2016    | 364       | 6.16%   |
| 2012    | 340       | 5.75%   |
| 2013    | 329       | 5.57%   |
| 2014    | 283       | 4.79%   |
| 2011    | 264       | 4.47%   |
| 2022    | 256       | 4.33%   |
| 2010    | 135       | 2.28%   |
| 2008    | 83        | 1.4%    |
| 2009    | 63        | 1.07%   |
| 2007    | 17        | 0.29%   |
| 2023    | 6         | 0.1%    |
| 2006    | 6         | 0.1%    |
| Unknown | 5         | 0.08%   |
| 2003    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 5911      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 4774      | 79.42%  |
| Enabled  | 1237      | 20.58%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 5870      | 99.31%  |
| Yes  | 41        | 0.69%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1769      | 29.48%  |
| 16.01-24.0  | 1438      | 23.97%  |
| 8.01-16.0   | 1184      | 19.73%  |
| 32.01-64.0  | 659       | 10.98%  |
| 3.01-4.0    | 589       | 9.82%   |
| 1.01-2.0    | 114       | 1.9%    |
| 24.01-32.0  | 108       | 1.8%    |
| 64.01-256.0 | 103       | 1.72%   |
| 2.01-3.0    | 24        | 0.4%    |
| 0.51-1.0    | 10        | 0.17%   |
| Unknown     | 2         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 1868      | 28.06%  |
| 4.01-8.0   | 1811      | 27.2%   |
| 3.01-4.0   | 1446      | 21.72%  |
| 1.01-2.0   | 902       | 13.55%  |
| 8.01-16.0  | 482       | 7.24%   |
| 0.51-1.0   | 69        | 1.04%   |
| 16.01-24.0 | 54        | 0.81%   |
| 24.01-32.0 | 13        | 0.2%    |
| 32.01-64.0 | 7         | 0.11%   |
| 0.01-0.5   | 3         | 0.05%   |
| Unknown    | 2         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 4342      | 72.19%  |
| 2      | 1427      | 23.72%  |
| 3      | 172       | 2.86%   |
| 0      | 35        | 0.58%   |
| 4      | 27        | 0.45%   |
| 6      | 6         | 0.1%    |
| 5      | 6         | 0.1%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 4680      | 78.79%  |
| Yes       | 1260      | 21.21%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4403      | 74.1%   |
| No        | 1539      | 25.9%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 5799      | 98.02%  |
| No        | 117       | 1.98%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4963      | 82.95%  |
| No        | 1020      | 17.05%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 1001      | 16.76%  |
| Brazil      | 434       | 7.27%   |
| Germany     | 409       | 6.85%   |
| Russia      | 389       | 6.51%   |
| Italy       | 283       | 4.74%   |
| France      | 246       | 4.12%   |
| India       | 229       | 3.83%   |
| UK          | 205       | 3.43%   |
| Poland      | 183       | 3.06%   |
| Netherlands | 169       | 2.83%   |
| Canada      | 163       | 2.73%   |
| Spain       | 144       | 2.41%   |
| Mexico      | 102       | 1.71%   |
| Czechia     | 102       | 1.71%   |
| Turkey      | 97        | 1.62%   |
| Australia   | 95        | 1.59%   |
| Austria     | 81        | 1.36%   |
| Sweden      | 80        | 1.34%   |
| Switzerland | 66        | 1.1%    |
| Ukraine     | 60        | 1%      |
| Argentina   | 59        | 0.99%   |
| Portugal    | 57        | 0.95%   |
| Belgium     | 55        | 0.92%   |
| Indonesia   | 54        | 0.9%    |
| Romania     | 53        | 0.89%   |
| Norway      | 51        | 0.85%   |
| Finland     | 51        | 0.85%   |
| Hungary     | 48        | 0.8%    |
| Chile       | 46        | 0.77%   |
| Denmark     | 42        | 0.7%    |
| China       | 38        | 0.64%   |
| Iran        | 34        | 0.57%   |
| Colombia    | 34        | 0.57%   |
| Greece      | 31        | 0.52%   |
| Bulgaria    | 31        | 0.52%   |
| Slovakia    | 30        | 0.5%    |
| Israel      | 30        | 0.5%    |
| Belarus     | 29        | 0.49%   |
| New Zealand | 27        | 0.45%   |
| Japan       | 26        | 0.44%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 131       | 2.06%   |
| Sao Paulo         | 60        | 0.94%   |
| St Petersburg     | 57        | 0.89%   |
| Vienna            | 52        | 0.82%   |
| Paris             | 48        | 0.75%   |
| Berlin            | 47        | 0.74%   |
| Istanbul          | 44        | 0.69%   |
| Amsterdam         | 44        | 0.69%   |
| Prague            | 43        | 0.67%   |
| Milan             | 43        | 0.67%   |
| Warsaw            | 42        | 0.66%   |
| Madrid            | 38        | 0.6%    |
| Munich            | 33        | 0.52%   |
| Oslo              | 31        | 0.49%   |
| Bengaluru         | 31        | 0.49%   |
| Helsinki          | 29        | 0.45%   |
| Sydney            | 28        | 0.44%   |
| Mexico City       | 28        | 0.44%   |
| Melbourne         | 28        | 0.44%   |
| Frankfurt am Main | 24        | 0.38%   |
| Budapest          | 24        | 0.38%   |
| Zurich            | 23        | 0.36%   |
| Kyiv              | 23        | 0.36%   |
| Bucharest         | 23        | 0.36%   |
| Rio de Janeiro    | 22        | 0.35%   |
| Brisbane          | 22        | 0.35%   |
| Lisbon            | 21        | 0.33%   |
| Jakarta           | 21        | 0.33%   |
| Tehran            | 20        | 0.31%   |
| Singapore         | 20        | 0.31%   |
| London            | 20        | 0.31%   |
| Hamburg           | 20        | 0.31%   |
| Sofia             | 19        | 0.3%    |
| Santiago          | 19        | 0.3%    |
| Montreal          | 19        | 0.3%    |
| Delft             | 19        | 0.3%    |
| Chicago           | 19        | 0.3%    |
| Brasília         | 19        | 0.3%    |
| Rome              | 18        | 0.28%   |
| Portland          | 18        | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 1587      | 2291   | 21.16%  |
| WDC                       | 779       | 985    | 10.39%  |
| Seagate                   | 570       | 754    | 7.6%    |
| SanDisk                   | 530       | 692    | 7.07%   |
| Toshiba                   | 524       | 650    | 6.99%   |
| SK hynix                  | 451       | 559    | 6.01%   |
| Unknown                   | 391       | 513    | 5.21%   |
| Kingston                  | 361       | 446    | 4.81%   |
| Intel                     | 317       | 445    | 4.23%   |
| Micron Technology         | 235       | 307    | 3.13%   |
| Crucial                   | 229       | 297    | 3.05%   |
| HGST                      | 155       | 219    | 2.07%   |
| KIOXIA                    | 114       | 158    | 1.52%   |
| A-DATA Technology         | 113       | 130    | 1.51%   |
| Apple                     | 86        | 110    | 1.15%   |
| Hitachi                   | 77        | 89     | 1.03%   |
| LITEON                    | 72        | 78     | 0.96%   |
| Phison                    | 54        | 60     | 0.72%   |
| China                     | 46        | 52     | 0.61%   |
| Silicon Motion            | 38        | 54     | 0.51%   |
| PNY                       | 36        | 47     | 0.48%   |
| Transcend                 | 35        | 52     | 0.47%   |
| SPCC                      | 31        | 40     | 0.41%   |
| LITEONIT                  | 25        | 31     | 0.33%   |
| ADATA Technology          | 25        | 26     | 0.33%   |
| Micron/Crucial Technology | 24        | 26     | 0.32%   |
| Lenovo                    | 21        | 24     | 0.28%   |
| Corsair                   | 21        | 26     | 0.28%   |
| Unknown                   | 19        | 23     | 0.25%   |
| XPG                       | 18        | 27     | 0.24%   |
| Realtek Semiconductor     | 17        | 22     | 0.23%   |
| Patriot                   | 17        | 23     | 0.23%   |
| UMIS                      | 16        | 19     | 0.21%   |
| Phison Electronics        | 16        | 17     | 0.21%   |
| JMicron Technology        | 16        | 18     | 0.21%   |
| OCZ                       | 15        | 17     | 0.2%    |
| Team                      | 14        | 17     | 0.19%   |
| Intenso                   | 14        | 17     | 0.19%   |
| Gigabyte Technology       | 14        | 16     | 0.19%   |
| KingSpec                  | 13        | 16     | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 119       | 1.51%   |
| Samsung NVMe SSD Drive 512GB                        | 113       | 1.44%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 83        | 1.05%   |
| SanDisk NVMe SSD Drive 512GB                        | 77        | 0.98%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 68        | 0.86%   |
| Kingston SA400S37240G 240GB SSD                     | 68        | 0.86%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 67        | 0.85%   |
| HGST HTS721010A9E630 1TB                            | 67        | 0.85%   |
| Unknown MMC Card  32GB                              | 63        | 0.8%    |
| Toshiba MQ04ABF100 1TB                              | 63        | 0.8%    |
| Toshiba MQ01ABD100 1TB                              | 54        | 0.69%   |
| Samsung SSD 860 EVO 500GB                           | 53        | 0.67%   |
| Unknown MMC Card  64GB                              | 51        | 0.65%   |
| SK hynix NVMe SSD Drive 512GB                       | 51        | 0.65%   |
| Samsung NVMe SSD Drive 1024GB                       | 51        | 0.65%   |
| SanDisk NVMe SSD Drive 256GB                        | 46        | 0.58%   |
| Intel NVMe SSD Drive 512GB                          | 46        | 0.58%   |
| Samsung NVMe SSD Drive 1TB                          | 43        | 0.55%   |
| Kingston SA400S37480G 480GB SSD                     | 43        | 0.55%   |
| Samsung SSD 850 EVO 250GB                           | 40        | 0.51%   |
| Samsung SSD 850 EVO 500GB                           | 39        | 0.5%    |
| Toshiba NVMe SSD Drive 512GB                        | 38        | 0.48%   |
| Unknown MMC Card  128GB                             | 37        | 0.47%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 35        | 0.44%   |
| Toshiba NVMe SSD Drive 256GB                        | 33        | 0.42%   |
| Seagate ST500LT012-1DG142 500GB                     | 33        | 0.42%   |
| Samsung SSD 860 EVO 250GB                           | 33        | 0.42%   |
| Samsung NVMe SSD Drive 500GB                        | 33        | 0.42%   |
| Crucial CT240BX500SSD1 240GB                        | 32        | 0.41%   |
| Seagate Expansion+ 2TB                              | 31        | 0.39%   |
| Samsung SSD 860 EVO 1TB                             | 31        | 0.39%   |
| WDC WD10SPZX-21Z10T0 1TB                            | 30        | 0.38%   |
| SK hynix NVMe SSD Drive 256GB                       | 30        | 0.38%   |
| Crucial CT1000MX500SSD1 1TB                         | 29        | 0.37%   |
| Samsung SSD 970 EVO Plus 1TB                        | 28        | 0.36%   |
| Samsung MZVLB512HBJQ-000L7 512GB                    | 28        | 0.36%   |
| HGST HTS541010A9E680 1TB                            | 28        | 0.36%   |
| Samsung MZVLB1T0HBLR-000L7 1TB                      | 27        | 0.34%   |
| Crucial CT500MX500SSD1 500GB                        | 26        | 0.33%   |
| WDC WD10SPZX-24Z10 1TB                              | 25        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 550       | 724    | 36.69%  |
| WDC                 | 391       | 502    | 26.08%  |
| Toshiba             | 251       | 303    | 16.74%  |
| HGST                | 155       | 219    | 10.34%  |
| Hitachi             | 77        | 89     | 5.14%   |
| Unknown             | 20        | 29     | 1.33%   |
| Samsung Electronics | 13        | 16     | 0.87%   |
| Fujitsu             | 11        | 11     | 0.73%   |
| SABRENT             | 9         | 9      | 0.6%    |
| Apple               | 7         | 8      | 0.47%   |
| USB3.0              | 2         | 2      | 0.13%   |
| LIO-ORG             | 2         | 8      | 0.13%   |
| HGST HTS            | 2         | 2      | 0.13%   |
| External            | 2         | 2      | 0.13%   |
| ASMT                | 2         | 2      | 0.13%   |
| Phison              | 1         | 2      | 0.07%   |
| LaCie               | 1         | 2      | 0.07%   |
| JMicron Technology  | 1         | 1      | 0.07%   |
| Intenso             | 1         | 1      | 0.07%   |
| IB-AC703            | 1         | 1      | 0.07%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 590       | 846    | 25.28%  |
| Kingston            | 258       | 318    | 11.05%  |
| SanDisk             | 247       | 342    | 10.58%  |
| Crucial             | 202       | 269    | 8.65%   |
| WDC                 | 124       | 160    | 5.31%   |
| Intel               | 87        | 137    | 3.73%   |
| Micron Technology   | 78        | 96     | 3.34%   |
| A-DATA Technology   | 74        | 87     | 3.17%   |
| SK hynix            | 65        | 79     | 2.78%   |
| Apple               | 59        | 66     | 2.53%   |
| LITEON              | 57        | 63     | 2.44%   |
| Toshiba             | 47        | 61     | 2.01%   |
| China               | 45        | 51     | 1.93%   |
| PNY                 | 34        | 44     | 1.46%   |
| Transcend           | 30        | 43     | 1.29%   |
| LITEONIT            | 25        | 31     | 1.07%   |
| SPCC                | 24        | 33     | 1.03%   |
| Patriot             | 15        | 20     | 0.64%   |
| OCZ                 | 14        | 16     | 0.6%    |
| Corsair             | 14        | 16     | 0.6%    |
| Intenso             | 13        | 15     | 0.56%   |
| KingSpec            | 12        | 14     | 0.51%   |
| Gigabyte Technology | 12        | 14     | 0.51%   |
| GOODRAM             | 11        | 15     | 0.47%   |
| Netac               | 10        | 13     | 0.43%   |
| Team                | 9         | 12     | 0.39%   |
| Seagate             | 9         | 9      | 0.39%   |
| JMicron Technology  | 9         | 11     | 0.39%   |
| Lexar               | 8         | 16     | 0.34%   |
| Apacer              | 8         | 9      | 0.34%   |
| Unknown             | 6         | 6      | 0.26%   |
| Plextor             | 6         | 7      | 0.26%   |
| Hewlett-Packard     | 6         | 6      | 0.26%   |
| TO Exter            | 5         | 5      | 0.21%   |
| FORESEE             | 5         | 5      | 0.21%   |
| Mushkin             | 4         | 12     | 0.17%   |
| Dogfish             | 4         | 4      | 0.17%   |
| BIWIN               | 4         | 5      | 0.17%   |
| Unknown             | 4         | 5      | 0.17%   |
| Vaseky              | 3         | 4      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 3026      | 4240   | 42.69%  |
| SSD     | 2161      | 3082   | 30.49%  |
| HDD     | 1446      | 1933   | 20.4%   |
| MMC     | 367       | 490    | 5.18%   |
| Unknown | 88        | 99     | 1.24%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3148      | 4799   | 46.4%   |
| NVMe | 3024      | 4230   | 44.57%  |
| MMC  | 367       | 490    | 5.41%   |
| SAS  | 246       | 325    | 3.63%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2227      | 3151   | 61.79%  |
| 0.51-1.0   | 1201      | 1614   | 33.32%  |
| 1.01-2.0   | 150       | 222    | 4.16%   |
| 4.01-10.0  | 15        | 16     | 0.42%   |
| 3.01-4.0   | 9         | 9      | 0.25%   |
| 2.01-3.0   | 1         | 1      | 0.03%   |
| 0          | 1         | 2      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 1361      | 21.92%  |
| 501-1000       | 1301      | 20.95%  |
| 101-250        | 1170      | 18.84%  |
| 1-20           | 660       | 10.63%  |
| 1001-2000      | 646       | 10.4%   |
| Unknown        | 442       | 7.12%   |
| 51-100         | 252       | 4.06%   |
| 21-50          | 144       | 2.32%   |
| More than 3000 | 119       | 1.92%   |
| 2001-3000      | 115       | 1.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1910      | 29.3%   |
| 21-50          | 1147      | 17.59%  |
| 101-250        | 1034      | 15.86%  |
| 51-100         | 869       | 13.33%  |
| 251-500        | 617       | 9.46%   |
| Unknown        | 442       | 6.78%   |
| 501-1000       | 358       | 5.49%   |
| 1001-2000      | 110       | 1.69%   |
| More than 3000 | 17        | 0.26%   |
| 2001-3000      | 14        | 0.21%   |
| 0              | 1         | 0.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB                | 10        | 10     | 3.62%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 9         | 19     | 3.26%   |
| Seagate ST1000LM035-1RK172 1TB                 | 7         | 7      | 2.54%   |
| Toshiba MQ01ABD100 1TB                         | 6         | 6      | 2.17%   |
| Seagate ST9500325AS 500GB                      | 6         | 8      | 2.17%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 6         | 6      | 2.17%   |
| HGST HTS721010A9E630 1TB                       | 6         | 8      | 2.17%   |
| HGST HTS545050A7E680 500GB                     | 6         | 6      | 2.17%   |
| HGST HTS541010A9E680 1TB                       | 6         | 6      | 2.17%   |
| Toshiba MQ01ABD075 752GB                       | 4         | 4      | 1.45%   |
| Hitachi HTS547575A9E384 752GB                  | 4         | 6      | 1.45%   |
| SK hynix SC308 SATA 128GB SSD                  | 3         | 3      | 1.09%   |
| Seagate ST9320325AS 320GB                      | 3         | 3      | 1.09%   |
| Seagate ST500LM021-1KJ152 500GB                | 3         | 4      | 1.09%   |
| Samsung Electronics SSD 870 EVO 500GB          | 3         | 6      | 1.09%   |
| Hitachi HTS545050B9A300 500GB                  | 3         | 3      | 1.09%   |
| Crucial CT1000P1SSD8 1TB                       | 3         | 3      | 1.09%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD               | 2         | 2      | 0.72%   |
| WDC WD10SPZX-24Z10 1TB                         | 2         | 2      | 0.72%   |
| Toshiba MQ01ACF050 500GB                       | 2         | 2      | 0.72%   |
| Toshiba MQ01ABD050V 500GB                      | 2         | 2      | 0.72%   |
| Toshiba MK5061GSY 500GB                        | 2         | 2      | 0.72%   |
| Toshiba MK3275GSX 320GB                        | 2         | 3      | 0.72%   |
| SPCC Solid State Disk 256GB                    | 2         | 2      | 0.72%   |
| SK hynix HFS256G39TND-N210A 256GB SSD          | 2         | 2      | 0.72%   |
| SK hynix HFS128G39TND-N210A 128GB SSD          | 2         | 2      | 0.72%   |
| Seagate ST9500420AS 500GB                      | 2         | 3      | 0.72%   |
| Seagate ST500LM012 HN-M500MBB 500GB            | 2         | 2      | 0.72%   |
| Seagate ST500LM000-SSHD-8GB                    | 2         | 3      | 0.72%   |
| Seagate ST500LM000-1EJ162 500GB                | 2         | 2      | 0.72%   |
| Seagate ST2000LM003 HN-M201RAD 2TB             | 2         | 2      | 0.72%   |
| Seagate ST1000LM014-1EJ164 1TB                 | 2         | 2      | 0.72%   |
| SanDisk SSD PLUS 240GB                         | 2         | 2      | 0.72%   |
| SanDisk SD6PP4M-256G-1006 256GB SSD            | 2         | 2      | 0.72%   |
| Samsung Electronics SSD 980 1TB                | 2         | 2      | 0.72%   |
| LITEON CV8-8E128-HP 128GB SSD                  | 2         | 2      | 0.72%   |
| Kingston SV300S37A480G 480GB SSD               | 2         | 2      | 0.72%   |
| Intel SSDSC2BF180A5L 180GB                     | 2         | 2      | 0.72%   |
| Hitachi HTS545032B9A300 320GB                  | 2         | 2      | 0.72%   |
| Hitachi HTS545025B9SA02 250GB                  | 2         | 3      | 0.72%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 59        | 76     | 21.45%  |
| Toshiba             | 30        | 31     | 10.91%  |
| WDC                 | 28        | 31     | 10.18%  |
| HGST                | 24        | 26     | 8.73%   |
| Samsung Electronics | 23        | 28     | 8.36%   |
| Hitachi             | 19        | 22     | 6.91%   |
| Micron Technology   | 14        | 17     | 5.09%   |
| SK hynix            | 12        | 13     | 4.36%   |
| Intel               | 12        | 23     | 4.36%   |
| SanDisk             | 10        | 12     | 3.64%   |
| Crucial             | 10        | 17     | 3.64%   |
| Kingston            | 6         | 6      | 2.18%   |
| A-DATA Technology   | 5         | 5      | 1.82%   |
| LITEON              | 4         | 4      | 1.45%   |
| Fujitsu             | 3         | 3      | 1.09%   |
| SPCC                | 2         | 2      | 0.73%   |
| LITEONIT            | 2         | 3      | 0.73%   |
| walram              | 1         | 1      | 0.36%   |
| Union Memory        | 1         | 1      | 0.36%   |
| Teclast             | 1         | 1      | 0.36%   |
| SSD                 | 1         | 1      | 0.36%   |
| PNY                 | 1         | 1      | 0.36%   |
| Plextor             | 1         | 1      | 0.36%   |
| Origin              | 1         | 1      | 0.36%   |
| OCZ-VERTEX3         | 1         | 1      | 0.36%   |
| Lenovo              | 1         | 2      | 0.36%   |
| HGST HTS            | 1         | 1      | 0.36%   |
| China               | 1         | 1      | 0.36%   |
| Unknown             | 1         | 1      | 0.36%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 59        | 76     | 35.98%  |
| Toshiba             | 29        | 30     | 17.68%  |
| WDC                 | 26        | 29     | 15.85%  |
| HGST                | 24        | 26     | 14.63%  |
| Hitachi             | 19        | 22     | 11.59%  |
| Samsung Electronics | 3         | 3      | 1.83%   |
| Fujitsu             | 3         | 3      | 1.83%   |
| HGST HTS            | 1         | 1      | 0.61%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 163       | 190    | 59.71%  |
| SSD  | 89        | 118    | 32.6%   |
| NVMe | 21        | 24     | 7.69%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC PC SN520 SDAPMUW-512G-1001 512GB             | 1         | 1      | 14.29%  |
| Toshiba THNSN5512GPUK NVMe 512GB                 | 1         | 1      | 14.29%  |
| Seagate ST1000LM035-1RK172 1TB                   | 1         | 1      | 14.29%  |
| Samsung Electronics SSD 980 500GB                | 1         | 1      | 14.29%  |
| Samsung Electronics SSD 980 1TB                  | 1         | 1      | 14.29%  |
| Samsung Electronics MZNTY128HDHP-00000 128GB SSD | 1         | 1      | 14.29%  |
| HGST HTS721010A9E630 1TB                         | 1         | 1      | 14.29%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 42.86%  |
| WDC                 | 1         | 1      | 14.29%  |
| Toshiba             | 1         | 1      | 14.29%  |
| Seagate             | 1         | 1      | 14.29%  |
| HGST                | 1         | 1      | 14.29%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 3356      | 5597   | 52.8%   |
| Works    | 2727      | 3908   | 42.9%   |
| Malfunc  | 266       | 332    | 4.19%   |
| Failed   | 7         | 7      | 0.11%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 3673      | 49.93%  |
| Samsung Electronics                     | 1067      | 14.51%  |
| AMD                                     | 616       | 8.37%   |
| SanDisk                                 | 532       | 7.23%   |
| SK hynix                                | 372       | 5.06%   |
| Toshiba America Info Systems            | 232       | 3.15%   |
| Micron Technology                       | 159       | 2.16%   |
| KIOXIA                                  | 115       | 1.56%   |
| Kingston Technology Company             | 114       | 1.55%   |
| Phison Electronics                      | 81        | 1.1%    |
| ADATA Technology                        | 74        | 1.01%   |
| Silicon Motion                          | 54        | 0.73%   |
| Micron/Crucial Technology               | 49        | 0.67%   |
| Union Memory (Shenzhen)                 | 30        | 0.41%   |
| Lite-On Technology                      | 28        | 0.38%   |
| Realtek Semiconductor                   | 24        | 0.33%   |
| Nvidia                                  | 24        | 0.33%   |
| Solid State Storage Technology          | 22        | 0.3%    |
| Lenovo                                  | 21        | 0.29%   |
| Apple                                   | 17        | 0.23%   |
| Seagate Technology                      | 9         | 0.12%   |
| Yangtze Memory Technologies             | 7         | 0.1%    |
| Shenzhen Longsys Electronics            | 6         | 0.08%   |
| Marvell Technology Group                | 6         | 0.08%   |
| JMicron Technology                      | 5         | 0.07%   |
| MAXIO Technology (Hangzhou)             | 3         | 0.04%   |
| Biwin Storage Technology                | 3         | 0.04%   |
| Silicon Integrated Systems [SiS]        | 2         | 0.03%   |
| ULi Electronics                         | 1         | 0.01%   |
| Transcend                               | 1         | 0.01%   |
| Shenzhen Unionmemory Information System | 1         | 0.01%   |
| OCZ Technology Group                    | 1         | 0.01%   |
| Netac Technology                        | 1         | 0.01%   |
| Lite-On IT Corp. / Plextor              | 1         | 0.01%   |
| INNOGRIT                                | 1         | 0.01%   |
| Enmotus                                 | 1         | 0.01%   |
| Beijing Starblaze Technology            | 1         | 0.01%   |
| ASMedia Technology                      | 1         | 0.01%   |
| Unknown                                 | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 606       | 7.89%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 584       | 7.6%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 551       | 7.17%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 372       | 4.84%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 359       | 4.67%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 236       | 3.07%   |
| Intel Volume Management Device NVMe RAID Controller                            | 235       | 3.06%   |
| Samsung NVMe SSD Controller 980                                                | 226       | 2.94%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 218       | 2.84%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 201       | 2.62%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 181       | 2.36%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 166       | 2.16%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 160       | 2.08%   |
| Micron NVMe Storage Controller                                                 | 157       | 2.04%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 147       | 1.91%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 137       | 1.78%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 132       | 1.72%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 105       | 1.37%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 101       | 1.31%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 100       | 1.3%    |
| Intel Comet Lake SATA AHCI Controller                                          | 100       | 1.3%    |
| Intel Tiger Lake-LP SATA Controller                                            | 97        | 1.26%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 91        | 1.18%   |
| Intel SSD 660P Series                                                          | 85        | 1.11%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 85        | 1.11%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 68        | 0.88%   |
| SK hynix Non-Volatile memory controller                                        | 67        | 0.87%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 66        | 0.86%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 65        | 0.85%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 63        | 0.82%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 63        | 0.82%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 63        | 0.82%   |
| SK hynix BC511                                                                 | 55        | 0.72%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 55        | 0.72%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 54        | 0.7%    |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 50        | 0.65%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 50        | 0.65%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 50        | 0.65%   |
| Intel Non-Volatile memory controller                                           | 49        | 0.64%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 49        | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 3659      | 49.36%  |
| NVMe | 3030      | 40.87%  |
| RAID | 622       | 8.39%   |
| IDE  | 102       | 1.38%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 4788      | 81%     |
| AMD     | 1118      | 18.91%  |
| ARM     | 3         | 0.05%   |
| Unknown | 2         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 153       | 2.59%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 132       | 2.23%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 130       | 2.2%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 124       | 2.1%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 108       | 1.83%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 101       | 1.71%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 101       | 1.71%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 101       | 1.71%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 99        | 1.67%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 99        | 1.67%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 90        | 1.52%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 90        | 1.52%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 89        | 1.51%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 83        | 1.4%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 83        | 1.4%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 71        | 1.2%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 68        | 1.15%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 64        | 1.08%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 61        | 1.03%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 61        | 1.03%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 60        | 1.01%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 60        | 1.01%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 58        | 0.98%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 53        | 0.9%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 50        | 0.85%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 48        | 0.81%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 45        | 0.76%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 45        | 0.76%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 44        | 0.74%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 42        | 0.71%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 41        | 0.69%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 40        | 0.68%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 38        | 0.64%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 37        | 0.63%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 37        | 0.63%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 36        | 0.61%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 36        | 0.61%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 34        | 0.58%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 34        | 0.58%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 33        | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 1807      | 30.57%  |
| Intel Core i5                  | 1502      | 25.41%  |
| Other                          | 596       | 10.08%  |
| Intel Core i3                  | 358       | 6.06%   |
| AMD Ryzen 5                    | 345       | 5.84%   |
| AMD Ryzen 7                    | 319       | 5.4%    |
| Intel Celeron                  | 135       | 2.28%   |
| Intel Core 2 Duo               | 98        | 1.66%   |
| Intel Atom                     | 92        | 1.56%   |
| AMD Ryzen 7 PRO                | 84        | 1.42%   |
| AMD Ryzen 9                    | 81        | 1.37%   |
| Intel Pentium                  | 71        | 1.2%    |
| Intel Core i9                  | 55        | 0.93%   |
| AMD Ryzen 3                    | 50        | 0.85%   |
| AMD Ryzen 5 PRO                | 47        | 0.8%    |
| AMD A6                         | 34        | 0.58%   |
| AMD A10                        | 28        | 0.47%   |
| AMD A8                         | 25        | 0.42%   |
| Intel Pentium Silver           | 20        | 0.34%   |
| AMD A4                         | 20        | 0.34%   |
| Intel Xeon                     | 14        | 0.24%   |
| Intel Pentium Dual-Core        | 14        | 0.24%   |
| AMD E1                         | 11        | 0.19%   |
| AMD A12                        | 10        | 0.17%   |
| AMD Athlon                     | 9         | 0.15%   |
| Intel Core m3                  | 8         | 0.14%   |
| AMD E                          | 8         | 0.14%   |
| Intel Pentium Dual             | 7         | 0.12%   |
| Intel Genuine                  | 6         | 0.1%    |
| Intel Core m5                  | 6         | 0.1%    |
| Intel Core m7                  | 5         | 0.08%   |
| Intel Core M                   | 5         | 0.08%   |
| AMD PRO A10                    | 4         | 0.07%   |
| AMD Phenom II                  | 4         | 0.07%   |
| AMD E2                         | 4         | 0.07%   |
| AMD Athlon II                  | 4         | 0.07%   |
| Intel Core 2                   | 3         | 0.05%   |
| AMD Turion X2 Dual-Core Mobile | 3         | 0.05%   |
| Intel Celeron Dual-Core        | 2         | 0.03%   |
| AMD Turion 64 X2 Mobile        | 2         | 0.03%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 4       | 2435      | 41.18%  |
| 2       | 2186      | 36.97%  |
| 6       | 590       | 9.98%   |
| 8       | 547       | 9.25%   |
| 14      | 50        | 0.85%   |
| 12      | 47        | 0.79%   |
| 10      | 29        | 0.49%   |
| 1       | 20        | 0.34%   |
| 16      | 5         | 0.08%   |
| 3       | 2         | 0.03%   |
| 5       | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 5910      | 99.97%  |
| 2       | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 5190      | 87.67%  |
| 1       | 729       | 12.31%  |
| Unknown | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 5774      | 97.34%  |
| Unknown        | 151       | 2.55%   |
| 32-bit         | 4         | 0.07%   |
| 64-bit         | 3         | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 405       | 6.72%   |
| 0x806ec    | 394       | 6.54%   |
| 0x806ea    | 379       | 6.29%   |
| 0x306a9    | 354       | 5.88%   |
| 0x806c1    | 343       | 5.69%   |
| 0x206a7    | 276       | 4.58%   |
| 0x906ea    | 270       | 4.48%   |
| 0x406e3    | 269       | 4.47%   |
| 0x806e9    | 267       | 4.43%   |
| 0x40651    | 220       | 3.65%   |
| 0x306d4    | 213       | 3.54%   |
| 0x306c3    | 168       | 2.79%   |
| 0x0a50000c | 164       | 2.72%   |
| 0xa0652    | 162       | 2.69%   |
| 0x08600106 | 119       | 1.98%   |
| 0x906e9    | 118       | 1.96%   |
| 0x506e3    | 111       | 1.84%   |
| 0x08108109 | 108       | 1.79%   |
| 0x08108102 | 108       | 1.79%   |
| 0x706e5    | 104       | 1.73%   |
| 0x906a3    | 88        | 1.46%   |
| 0x20655    | 81        | 1.34%   |
| 0x806eb    | 75        | 1.25%   |
| 0x30678    | 74        | 1.23%   |
| 0x08608103 | 73        | 1.21%   |
| 0x1067a    | 70        | 1.16%   |
| 0x08600104 | 70        | 1.16%   |
| 0x806d1    | 59        | 0.98%   |
| 0x906ed    | 56        | 0.93%   |
| 0x08600103 | 48        | 0.8%    |
| 0x406c4    | 42        | 0.7%    |
| 0x0a404102 | 36        | 0.6%    |
| 0x706a8    | 34        | 0.56%   |
| 0x0810100b | 34        | 0.56%   |
| 0x406c3    | 30        | 0.5%    |
| 0x906a4    | 28        | 0.46%   |
| 0x506c9    | 28        | 0.46%   |
| 0x08608102 | 28        | 0.46%   |
| 0x20652    | 27        | 0.45%   |
| 0x40661    | 26        | 0.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 1665      | 28.15%  |
| Haswell          | 431       | 7.29%   |
| Skylake          | 407       | 6.88%   |
| TigerLake        | 385       | 6.51%   |
| IvyBridge        | 371       | 6.27%   |
| SandyBridge      | 289       | 4.89%   |
| Zen 2            | 280       | 4.73%   |
| Zen+             | 224       | 3.79%   |
| Broadwell        | 217       | 3.67%   |
| Zen 3            | 202       | 3.42%   |
| CometLake        | 187       | 3.16%   |
| Unknown          | 185       | 3.13%   |
| Icelake          | 174       | 2.94%   |
| Silvermont       | 161       | 2.72%   |
| Alderlake Hybrid | 126       | 2.13%   |
| Westmere         | 113       | 1.91%   |
| Penryn           | 101       | 1.71%   |
| Zen              | 65        | 1.1%    |
| Goldmont plus    | 58        | 0.98%   |
| Excavator        | 55        | 0.93%   |
| Goldmont         | 30        | 0.51%   |
| Puma             | 29        | 0.49%   |
| Core             | 29        | 0.49%   |
| Piledriver       | 24        | 0.41%   |
| Jaguar           | 19        | 0.32%   |
| Nehalem          | 17        | 0.29%   |
| Bobcat           | 15        | 0.25%   |
| Tremont          | 11        | 0.19%   |
| K10              | 11        | 0.19%   |
| K10 Llano        | 9         | 0.15%   |
| Steamroller      | 7         | 0.12%   |
| K8 & K10 hybrid  | 5         | 0.08%   |
| Bonnell          | 5         | 0.08%   |
| K8 Hammer        | 4         | 0.07%   |
| P6               | 3         | 0.05%   |
| NetBurst         | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 4511      | 57.74%  |
| Nvidia                           | 1882      | 24.09%  |
| AMD                              | 1418      | 18.15%  |
| Silicon Integrated Systems [SiS] | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 393       | 4.94%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 353       | 4.44%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 342       | 4.3%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 294       | 3.69%   |
| Intel HD Graphics 620                                                                    | 274       | 3.44%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 272       | 3.42%   |
| AMD Renoir                                                                               | 271       | 3.41%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 254       | 3.19%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 247       | 3.1%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 225       | 2.83%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 224       | 2.81%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 221       | 2.78%   |
| Intel HD Graphics 5500                                                                   | 191       | 2.4%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 172       | 2.16%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 169       | 2.12%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 155       | 1.95%   |
| Intel HD Graphics 630                                                                    | 111       | 1.39%   |
| AMD Lucienne                                                                             | 104       | 1.31%   |
| Intel HD Graphics 530                                                                    | 102       | 1.28%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 97        | 1.22%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 91        | 1.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 89        | 1.12%   |
| Intel Core Processor Integrated Graphics Controller                                      | 87        | 1.09%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 86        | 1.08%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 82        | 1.03%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 81        | 1.02%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 79        | 0.99%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 72        | 0.9%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 71        | 0.89%   |
| Nvidia GP108M [GeForce MX150]                                                            | 66        | 0.83%   |
| AMD Rembrandt [Radeon 680M]                                                              | 64        | 0.8%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 60        | 0.75%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 60        | 0.75%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 54        | 0.68%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 53        | 0.67%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 53        | 0.67%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 48        | 0.6%    |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 44        | 0.55%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 44        | 0.55%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 44        | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 2808      | 47.34%  |
| Intel + Nvidia     | 1459      | 24.6%   |
| 1 x AMD            | 877       | 14.79%  |
| Intel + AMD        | 238       | 4.01%   |
| 1 x Nvidia         | 230       | 3.88%   |
| AMD + Nvidia       | 193       | 3.25%   |
| 2 x AMD            | 110       | 1.85%   |
| Other              | 7         | 0.12%   |
| 2 x Intel          | 4         | 0.07%   |
| 2 x Nvidia         | 2         | 0.03%   |
| Intel + 2 x Nvidia | 2         | 0.03%   |
| 1 x SiS            | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 5069      | 84.74%  |
| Proprietary | 836       | 13.98%  |
| Unknown     | 77        | 1.29%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 3680      | 61.04%  |
| 1.01-2.0   | 822       | 13.63%  |
| 0.01-0.5   | 616       | 10.22%  |
| 3.01-4.0   | 396       | 6.57%   |
| 0.51-1.0   | 324       | 5.37%   |
| 5.01-6.0   | 77        | 1.28%   |
| 7.01-8.0   | 73        | 1.21%   |
| 2.01-3.0   | 23        | 0.38%   |
| 8.01-16.0  | 18        | 0.3%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 1263      | 17.34%  |
| BOE                     | 1052      | 14.44%  |
| Chimei Innolux          | 980       | 13.45%  |
| LG Display              | 976       | 13.4%   |
| Samsung Electronics     | 563       | 7.73%   |
| Dell                    | 345       | 4.74%   |
| Sharp                   | 320       | 4.39%   |
| Goldstar                | 216       | 2.96%   |
| Lenovo                  | 154       | 2.11%   |
| Apple                   | 149       | 2.05%   |
| PANDA                   | 137       | 1.88%   |
| Hewlett-Packard         | 123       | 1.69%   |
| CSO                     | 82        | 1.13%   |
| BenQ                    | 79        | 1.08%   |
| Acer                    | 79        | 1.08%   |
| Chi Mei Optoelectronics | 78        | 1.07%   |
| Philips                 | 76        | 1.04%   |
| AOC                     | 76        | 1.04%   |
| InfoVision              | 65        | 0.89%   |
| Ancor Communications    | 55        | 0.75%   |
| Iiyama                  | 33        | 0.45%   |
| ViewSonic               | 32        | 0.44%   |
| TMX                     | 27        | 0.37%   |
| ASUSTek Computer        | 26        | 0.36%   |
| Sony                    | 19        | 0.26%   |
| Panasonic               | 19        | 0.26%   |
| JDI                     | 19        | 0.26%   |
| Toshiba                 | 15        | 0.21%   |
| LG Philips              | 12        | 0.16%   |
| MSI                     | 11        | 0.15%   |
| Sceptre Tech            | 10        | 0.14%   |
| CPT                     | 9         | 0.12%   |
| HannStar                | 8         | 0.11%   |
| Eizo                    | 8         | 0.11%   |
| Vizio                   | 7         | 0.1%    |
| NEC Computers           | 7         | 0.1%    |
| Fujitsu Siemens         | 7         | 0.1%    |
| Vestel Elektronik       | 6         | 0.08%   |
| RTK                     | 6         | 0.08%   |
| Mi                      | 6         | 0.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 63        | 0.85%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 55        | 0.74%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch       | 51        | 0.69%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 47        | 0.64%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 43        | 0.58%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 38        | 0.51%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch       | 38        | 0.51%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 36        | 0.49%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 35        | 0.47%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 33        | 0.45%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 32        | 0.43%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 32        | 0.43%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                | 32        | 0.43%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch        | 32        | 0.43%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 27        | 0.36%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 27        | 0.36%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch             | 26        | 0.35%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 25        | 0.34%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 24        | 0.32%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch     | 24        | 0.32%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch         | 23        | 0.31%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 22        | 0.3%    |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 22        | 0.3%    |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch       | 22        | 0.3%    |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 21        | 0.28%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 21        | 0.28%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 21        | 0.28%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                | 21        | 0.28%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch       | 21        | 0.28%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch       | 21        | 0.28%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch              | 20        | 0.27%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch          | 20        | 0.27%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch         | 20        | 0.27%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 20        | 0.27%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 20        | 0.27%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch     | 19        | 0.26%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                | 19        | 0.26%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                    | 18        | 0.24%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                | 18        | 0.24%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch              | 17        | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 3414      | 51.15%  |
| 1366x768 (WXGA)    | 1318      | 19.75%  |
| 3840x2160 (4K)     | 379       | 5.68%   |
| 2560x1440 (QHD)    | 287       | 4.3%    |
| 1600x900 (HD+)     | 239       | 3.58%   |
| 1920x1200 (WUXGA)  | 186       | 2.79%   |
| 2560x1600          | 116       | 1.74%   |
| 1280x800 (WXGA)    | 98        | 1.47%   |
| 2880x1800          | 83        | 1.24%   |
| 2560x1080          | 64        | 0.96%   |
| 1440x900 (WXGA+)   | 60        | 0.9%    |
| 3440x1440          | 59        | 0.88%   |
| 3840x2400          | 47        | 0.7%    |
| 2160x1440          | 41        | 0.61%   |
| 1680x1050 (WSXGA+) | 39        | 0.58%   |
| 1280x1024 (SXGA)   | 34        | 0.51%   |
| 3200x1800 (QHD+)   | 32        | 0.48%   |
| 2256x1504          | 32        | 0.48%   |
| 3000x2000          | 18        | 0.27%   |
| 1360x768           | 18        | 0.27%   |
| 3456x2160          | 9         | 0.13%   |
| 3200x2000          | 9         | 0.13%   |
| 2520x1680          | 9         | 0.13%   |
| 2240x1400          | 9         | 0.13%   |
| 3072x1920          | 8         | 0.12%   |
| 2160x1350          | 6         | 0.09%   |
| 1920x1280          | 6         | 0.09%   |
| 3840x1600          | 5         | 0.07%   |
| 3840x1080          | 5         | 0.07%   |
| 1920x540           | 5         | 0.07%   |
| 1024x768 (XGA)     | 5         | 0.07%   |
| 1024x600           | 5         | 0.07%   |
| Unknown            | 3         | 0.04%   |
| 2880x1920          | 2         | 0.03%   |
| 2736x1824          | 2         | 0.03%   |
| 1920x515           | 2         | 0.03%   |
| 1680x945           | 2         | 0.03%   |
| 1600x1200          | 2         | 0.03%   |
| 9360x2160          | 1         | 0.01%   |
| 800x1280           | 1         | 0.01%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 2697      | 37%     |
| 13      | 1192      | 16.35%  |
| 14      | 1021      | 14.01%  |
| 17      | 371       | 5.09%   |
| 27      | 347       | 4.76%   |
| 24      | 324       | 4.44%   |
| 23      | 244       | 3.35%   |
| 12      | 195       | 2.67%   |
| 21      | 165       | 2.26%   |
| 34      | 106       | 1.45%   |
| 16      | 100       | 1.37%   |
| 31      | 70        | 0.96%   |
| 18      | 69        | 0.95%   |
| 11      | 66        | 0.91%   |
| 19      | 37        | 0.51%   |
| 20      | 33        | 0.45%   |
| 22      | 26        | 0.36%   |
| Unknown | 25        | 0.34%   |
| 40      | 23        | 0.32%   |
| 25      | 23        | 0.32%   |
| 84      | 17        | 0.23%   |
| 32      | 15        | 0.21%   |
| 35      | 12        | 0.16%   |
| 29      | 12        | 0.16%   |
| 26      | 11        | 0.15%   |
| 10      | 11        | 0.15%   |
| 54      | 9         | 0.12%   |
| 72      | 8         | 0.11%   |
| 48      | 6         | 0.08%   |
| 37      | 6         | 0.08%   |
| 28      | 6         | 0.08%   |
| 39      | 5         | 0.07%   |
| 74      | 3         | 0.04%   |
| 57      | 3         | 0.04%   |
| 42      | 3         | 0.04%   |
| 36      | 3         | 0.04%   |
| 33      | 3         | 0.04%   |
| 69      | 2         | 0.03%   |
| 65      | 2         | 0.03%   |
| 63      | 2         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 4379      | 60.7%   |
| 501-600     | 854       | 11.84%  |
| 201-300     | 830       | 11.51%  |
| 351-400     | 449       | 6.22%   |
| 401-500     | 310       | 4.3%    |
| 701-800     | 127       | 1.76%   |
| 601-700     | 122       | 1.69%   |
| 801-900     | 48        | 0.67%   |
| 1001-1500   | 32        | 0.44%   |
| 1501-2000   | 30        | 0.42%   |
| Unknown     | 25        | 0.35%   |
| 901-1000    | 6         | 0.08%   |
| 101-200     | 1         | 0.01%   |
| 1-100       | 1         | 0.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 5132      | 83.41%  |
| 16/10   | 694       | 11.28%  |
| 21/9    | 129       | 2.1%    |
| 3/2     | 121       | 1.97%   |
| 5/4     | 32        | 0.52%   |
| 4/3     | 15        | 0.24%   |
| Unknown | 11        | 0.18%   |
| 32/9    | 9         | 0.15%   |
| 6/5     | 2         | 0.03%   |
| 3.88    | 1         | 0.02%   |
| 3.73    | 1         | 0.02%   |
| 3.40    | 1         | 0.02%   |
| 3.33    | 1         | 0.02%   |
| 0.89    | 1         | 0.02%   |
| 0.67    | 1         | 0.02%   |
| 0.62    | 1         | 0.02%   |
| 0.56    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 2703      | 37.17%  |
| 81-90          | 1757      | 24.16%  |
| 201-250        | 606       | 8.33%   |
| 71-80          | 449       | 6.17%   |
| 301-350        | 357       | 4.91%   |
| 121-130        | 339       | 4.66%   |
| 351-500        | 217       | 2.98%   |
| 61-70          | 187       | 2.57%   |
| 251-300        | 131       | 1.8%    |
| 151-200        | 109       | 1.5%    |
| 111-120        | 90        | 1.24%   |
| 141-150        | 71        | 0.98%   |
| 51-60          | 67        | 0.92%   |
| 501-1000       | 54        | 0.74%   |
| More than 1000 | 53        | 0.73%   |
| 131-140        | 27        | 0.37%   |
| Unknown        | 25        | 0.34%   |
| 91-100         | 16        | 0.22%   |
| 41-50          | 11        | 0.15%   |
| 1-40           | 3         | 0.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 3212      | 45.22%  |
| 101-120       | 1570      | 22.1%   |
| 51-100        | 1124      | 15.82%  |
| 161-240       | 747       | 10.52%  |
| More than 240 | 381       | 5.36%   |
| 1-50          | 44        | 0.62%   |
| Unknown       | 25        | 0.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 4482      | 73.19%  |
| 2     | 1329      | 21.7%   |
| 3     | 174       | 2.84%   |
| 0     | 123       | 2.01%   |
| 4     | 14        | 0.23%   |
| 5     | 2         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 3617      | 40.32%  |
| Realtek Semiconductor             | 2917      | 32.52%  |
| Qualcomm Atheros                  | 1040      | 11.59%  |
| Broadcom                          | 373       | 4.16%   |
| MediaTek                          | 188       | 2.1%    |
| Lenovo                            | 86        | 0.96%   |
| Broadcom Limited                  | 85        | 0.95%   |
| ASIX Electronics                  | 60        | 0.67%   |
| Sierra Wireless                   | 59        | 0.66%   |
| TP-Link                           | 55        | 0.61%   |
| Dell                              | 41        | 0.46%   |
| Ralink                            | 40        | 0.45%   |
| Qualcomm                          | 38        | 0.42%   |
| DisplayLink                       | 36        | 0.4%    |
| Marvell Technology Group          | 33        | 0.37%   |
| Ericsson Business Mobile Networks | 28        | 0.31%   |
| Ralink Technology                 | 27        | 0.3%    |
| Hewlett-Packard                   | 25        | 0.28%   |
| Samsung Electronics               | 23        | 0.26%   |
| Nvidia                            | 17        | 0.19%   |
| Huawei Technologies               | 17        | 0.19%   |
| Xiaomi                            | 15        | 0.17%   |
| ASUSTek Computer                  | 14        | 0.16%   |
| Apple                             | 13        | 0.14%   |
| Fibocom                           | 11        | 0.12%   |
| JMicron Technology                | 10        | 0.11%   |
| Google                            | 10        | 0.11%   |
| NetGear                           | 8         | 0.09%   |
| Qualcomm Atheros Communications   | 6         | 0.07%   |
| Linksys                           | 6         | 0.07%   |
| D-Link                            | 6         | 0.07%   |
| T & A Mobile Phones               | 5         | 0.06%   |
| OPPO Electronics                  | 5         | 0.06%   |
| D-Link System                     | 5         | 0.06%   |
| OnePlus Technology (Shenzhen)     | 4         | 0.04%   |
| Motorola PCS                      | 4         | 0.04%   |
| Microsoft                         | 4         | 0.04%   |
| Edimax Technology                 | 4         | 0.04%   |
| Cypress Semiconductor             | 3         | 0.03%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1833      | 16.75%  |
| Intel Wi-Fi 6 AX200                                               | 442       | 4.04%   |
| Intel Wireless 8265 / 8275                                        | 395       | 3.61%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 386       | 3.53%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 327       | 2.99%   |
| Intel Wi-Fi 6 AX201                                               | 293       | 2.68%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 248       | 2.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 231       | 2.11%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 223       | 2.04%   |
| Intel Wireless 8260                                               | 220       | 2.01%   |
| Intel Wireless 7260                                               | 199       | 1.82%   |
| Intel Wireless 7265                                               | 195       | 1.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 179       | 1.64%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 176       | 1.61%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 169       | 1.54%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 158       | 1.44%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 157       | 1.43%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 147       | 1.34%   |
| Intel Ethernet Connection (4) I219-LM                             | 146       | 1.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 144       | 1.32%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 140       | 1.28%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 136       | 1.24%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 134       | 1.22%   |
| Intel Wireless 3165                                               | 103       | 0.94%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 96        | 0.88%   |
| Intel Ethernet Connection I219-LM                                 | 92        | 0.84%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 91        | 0.83%   |
| Intel Wireless-AC 9260                                            | 90        | 0.82%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 86        | 0.79%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 85        | 0.78%   |
| Intel Ethernet Connection (4) I219-V                              | 85        | 0.78%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 75        | 0.69%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 74        | 0.68%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 72        | 0.66%   |
| Intel Ethernet Connection I218-LM                                 | 72        | 0.66%   |
| Intel Centrino Ultimate-N 6300                                    | 69        | 0.63%   |
| Intel Wireless 3160                                               | 66        | 0.6%    |
| Intel Ethernet Connection (6) I219-V                              | 64        | 0.58%   |
| Intel Ethernet Connection (3) I218-LM                             | 62        | 0.57%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 60        | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 3524      | 58.02%  |
| Qualcomm Atheros                      | 911       | 15%     |
| Realtek Semiconductor                 | 795       | 13.09%  |
| Broadcom                              | 303       | 4.99%   |
| MediaTek                              | 182       | 3%      |
| Broadcom Limited                      | 64        | 1.05%   |
| Sierra Wireless                       | 59        | 0.97%   |
| Ralink                                | 40        | 0.66%   |
| TP-Link                               | 39        | 0.64%   |
| Dell                                  | 31        | 0.51%   |
| Qualcomm                              | 29        | 0.48%   |
| Ralink Technology                     | 27        | 0.44%   |
| ASUSTek Computer                      | 13        | 0.21%   |
| Fibocom                               | 11        | 0.18%   |
| NetGear                               | 7         | 0.12%   |
| Hewlett-Packard                       | 7         | 0.12%   |
| Qualcomm Atheros Communications       | 6         | 0.1%    |
| Linksys                               | 5         | 0.08%   |
| D-Link System                         | 5         | 0.08%   |
| Edimax Technology                     | 4         | 0.07%   |
| Microsoft                             | 3         | 0.05%   |
| D-Link                                | 3         | 0.05%   |
| Belkin Components                     | 2         | 0.03%   |
| TRENDnet                              | 1         | 0.02%   |
| Quectel Wireless Solutions            | 1         | 0.02%   |
| IMC Networks                          | 1         | 0.02%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 442       | 7.24%   |
| Intel Wireless 8265 / 8275                                     | 395       | 6.47%   |
| Intel Wi-Fi 6 AX201                                            | 293       | 4.8%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 248       | 4.06%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 223       | 3.65%   |
| Intel Wireless 8260                                            | 220       | 3.6%    |
| Intel Wireless 7260                                            | 199       | 3.26%   |
| Intel Wireless 7265                                            | 195       | 3.19%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 179       | 2.93%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 176       | 2.88%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 169       | 2.77%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 158       | 2.59%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 157       | 2.57%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 147       | 2.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 144       | 2.36%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 140       | 2.29%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 136       | 2.23%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 134       | 2.19%   |
| Intel Wireless 3165                                            | 103       | 1.69%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 96        | 1.57%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 91        | 1.49%   |
| Intel Wireless-AC 9260                                         | 90        | 1.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 86        | 1.41%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 85        | 1.39%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 75        | 1.23%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 74        | 1.21%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 72        | 1.18%   |
| Intel Centrino Ultimate-N 6300                                 | 69        | 1.13%   |
| Intel Wireless 3160                                            | 66        | 1.08%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 60        | 0.98%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 57        | 0.93%   |
| Broadcom BCM43142 802.11b/g/n                                  | 56        | 0.92%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 44        | 0.72%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 42        | 0.69%   |
| Intel Centrino Advanced-N 6235                                 | 41        | 0.67%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 35        | 0.57%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 33        | 0.54%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 30        | 0.49%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 30        | 0.49%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 29        | 0.47%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2596      | 55.47%  |
| Intel                                  | 1339      | 28.61%  |
| Qualcomm Atheros                       | 219       | 4.68%   |
| Broadcom                               | 123       | 2.63%   |
| Lenovo                                 | 84        | 1.79%   |
| ASIX Electronics                       | 60        | 1.28%   |
| DisplayLink                            | 36        | 0.77%   |
| Marvell Technology Group               | 33        | 0.71%   |
| Samsung Electronics                    | 23        | 0.49%   |
| Broadcom Limited                       | 21        | 0.45%   |
| TP-Link                                | 18        | 0.38%   |
| Nvidia                                 | 17        | 0.36%   |
| Xiaomi                                 | 15        | 0.32%   |
| Apple                                  | 13        | 0.28%   |
| JMicron Technology                     | 10        | 0.21%   |
| Google                                 | 10        | 0.21%   |
| Qualcomm                               | 9         | 0.19%   |
| Huawei Technologies                    | 9         | 0.19%   |
| MediaTek                               | 6         | 0.13%   |
| Hewlett-Packard                        | 6         | 0.13%   |
| OPPO Electronics                       | 5         | 0.11%   |
| OnePlus Technology (Shenzhen)          | 3         | 0.06%   |
| D-Link                                 | 3         | 0.06%   |
| Cypress Semiconductor                  | 3         | 0.06%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.04%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.04%   |
| ICS Advent                             | 2         | 0.04%   |
| vivo                                   | 1         | 0.02%   |
| T & A Mobile Phones                    | 1         | 0.02%   |
| Spreadtrum Communications              | 1         | 0.02%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.02%   |
| Novatel Wireless                       | 1         | 0.02%   |
| NetGear                                | 1         | 0.02%   |
| Motorola PCS                           | 1         | 0.02%   |
| Microsoft                              | 1         | 0.02%   |
| Linksys                                | 1         | 0.02%   |
| LG Electronics                         | 1         | 0.02%   |
| HMD Global                             | 1         | 0.02%   |
| ASUSTek Computer                       | 1         | 0.02%   |
| Aquantia                               | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1833      | 38.55%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 386       | 8.12%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 327       | 6.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 231       | 4.86%   |
| Intel Ethernet Connection (4) I219-LM                             | 146       | 3.07%   |
| Intel Ethernet Connection I219-LM                                 | 92        | 1.93%   |
| Intel Ethernet Connection (4) I219-V                              | 85        | 1.79%   |
| Intel Ethernet Connection I218-LM                                 | 72        | 1.51%   |
| Intel Ethernet Connection (6) I219-V                              | 64        | 1.35%   |
| Intel Ethernet Connection (3) I218-LM                             | 62        | 1.3%    |
| Intel Ethernet Connection I217-LM                                 | 56        | 1.18%   |
| Intel Ethernet Connection (10) I219-V                             | 55        | 1.16%   |
| ASIX AX88179 Gigabit Ethernet                                     | 55        | 1.16%   |
| Intel Ethernet Connection (7) I219-LM                             | 54        | 1.14%   |
| Intel Ethernet Connection (6) I219-LM                             | 51        | 1.07%   |
| Intel 82577LM Gigabit Network Connection                          | 39        | 0.82%   |
| Intel Ethernet Connection (2) I219-LM                             | 37        | 0.78%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 36        | 0.76%   |
| Intel Ethernet Connection I219-V                                  | 35        | 0.74%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 32        | 0.67%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 31        | 0.65%   |
| Intel Ethernet Connection (13) I219-V                             | 31        | 0.65%   |
| Realtek RTL8125 2.5GbE Controller                                 | 30        | 0.63%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 29        | 0.61%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 28        | 0.59%   |
| Intel Ethernet Connection (7) I219-V                              | 26        | 0.55%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 25        | 0.53%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 25        | 0.53%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 24        | 0.5%    |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 23        | 0.48%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 22        | 0.46%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 21        | 0.44%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 19        | 0.4%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 18        | 0.38%   |
| Intel Ethernet Connection I217-V                                  | 18        | 0.38%   |
| Lenovo ThinkPad TBT3 LAN                                          | 17        | 0.36%   |
| Intel Ethernet Connection (10) I219-LM                            | 17        | 0.36%   |
| Intel 82567LM Gigabit Network Connection                          | 17        | 0.36%   |
| Realtek Killer E3000 2.5GbE Controller                            | 16        | 0.34%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 15        | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 5801      | 56.41%  |
| Ethernet | 4400      | 42.78%  |
| Modem    | 71        | 0.69%   |
| Unknown  | 12        | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 5059      | 80.09%  |
| Ethernet | 1256      | 19.88%  |
| Modem    | 2         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 3951      | 66.76%  |
| 1     | 1781      | 30.09%  |
| 0     | 113       | 1.91%   |
| 3     | 73        | 1.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Notebooks | Percent |
|---------|-----------|---------|
| No      | 4967      | 82.4%   |
| Yes     | 1058      | 17.55%  |
| Unknown | 3         | 0.05%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2912      | 58.18%  |
| Realtek Semiconductor           | 470       | 9.39%   |
| Qualcomm Atheros Communications | 453       | 9.05%   |
| IMC Networks                    | 212       | 4.24%   |
| Broadcom                        | 200       | 4%      |
| Lite-On Technology              | 189       | 3.78%   |
| Foxconn / Hon Hai               | 176       | 3.52%   |
| Apple                           | 123       | 2.46%   |
| Realtek                         | 58        | 1.16%   |
| Dell                            | 39        | 0.78%   |
| Cambridge Silicon Radio         | 39        | 0.78%   |
| Ralink                          | 27        | 0.54%   |
| Hewlett-Packard                 | 27        | 0.54%   |
| Toshiba                         | 20        | 0.4%    |
| ASUSTek Computer                | 16        | 0.32%   |
| Foxconn International           | 9         | 0.18%   |
| USI                             | 6         | 0.12%   |
| MediaTek                        | 6         | 0.12%   |
| Opticis                         | 5         | 0.1%    |
| Ralink Technology               | 4         | 0.08%   |
| Chicony Electronics             | 3         | 0.06%   |
| Alps Electric                   | 3         | 0.06%   |
| Smart Modular Technologies      | 2         | 0.04%   |
| Qcom                            | 2         | 0.04%   |
| Taiyo Yuden                     | 1         | 0.02%   |
| Micro Star International        | 1         | 0.02%   |
| Corsair                         | 1         | 0.02%   |
| Askey Computer                  | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 1086      | 21.69%  |
| Intel AX201 Bluetooth                               | 584       | 11.66%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 448       | 8.95%   |
| Intel AX200 Bluetooth                               | 431       | 8.61%   |
| Realtek Bluetooth Radio                             | 276       | 5.51%   |
| Qualcomm Atheros  Bluetooth Device                  | 263       | 5.25%   |
| Realtek  Bluetooth 4.2 Adapter                      | 116       | 2.32%   |
| Apple Bluetooth Host Controller                     | 90        | 1.8%    |
| Intel AX210 Bluetooth                               | 89        | 1.78%   |
| IMC Networks Wireless_Device                        | 78        | 1.56%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 77        | 1.54%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 76        | 1.52%   |
| Intel Bluetooth Device                              | 73        | 1.46%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 69        | 1.38%   |
| Foxconn / Hon Hai Wireless_Device                   | 69        | 1.38%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 66        | 1.32%   |
| IMC Networks Bluetooth Radio                        | 63        | 1.26%   |
| Foxconn / Hon Hai Bluetooth Device                  | 62        | 1.24%   |
| Realtek Bluetooth Radio                             | 58        | 1.16%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 47        | 0.94%   |
| Lite-On Bluetooth Device                            | 47        | 0.94%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 44        | 0.88%   |
| Intel Wireless-AC 3168 Bluetooth                    | 41        | 0.82%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 40        | 0.8%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 39        | 0.78%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 34        | 0.68%   |
| Broadcom BCM2045B (BDC-2.1)                         | 34        | 0.68%   |
| IMC Networks Bluetooth Device                       | 31        | 0.62%   |
| Ralink RT3290 Bluetooth                             | 27        | 0.54%   |
| Lite-On Atheros AR3012 Bluetooth                    | 24        | 0.48%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 23        | 0.46%   |
| Realtek RTL8723B Bluetooth                          | 22        | 0.44%   |
| Apple Bluetooth USB Host Controller                 | 22        | 0.44%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 20        | 0.4%    |
| Lite-On Wireless_Device                             | 19        | 0.38%   |
| HP Broadcom 2070 Bluetooth Combo                    | 19        | 0.38%   |
| Dell DW375 Bluetooth Module                         | 18        | 0.36%   |
| Dell BCM20702A0 Bluetooth Module                    | 17        | 0.34%   |
| Realtek RTL8821A Bluetooth                          | 14        | 0.28%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 14        | 0.28%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 4667      | 61.39%  |
| AMD                         | 1197      | 15.75%  |
| Nvidia                      | 1002      | 13.18%  |
| Lenovo                      | 99        | 1.3%    |
| C-Media Electronics         | 76        | 1%      |
| Realtek Semiconductor       | 72        | 0.95%   |
| GN Netcom                   | 53        | 0.7%    |
| Logitech                    | 49        | 0.64%   |
| Plantronics                 | 37        | 0.49%   |
| Hewlett-Packard             | 26        | 0.34%   |
| JMTek                       | 20        | 0.26%   |
| Texas Instruments           | 16        | 0.21%   |
| Kingston Technology         | 15        | 0.2%    |
| Creative Technology         | 15        | 0.2%    |
| SteelSeries ApS             | 13        | 0.17%   |
| Corsair                     | 12        | 0.16%   |
| Razer USA                   | 11        | 0.14%   |
| Apple                       | 11        | 0.14%   |
| Sennheiser Communications   | 10        | 0.13%   |
| Generalplus Technology      | 10        | 0.13%   |
| Sony                        | 9         | 0.12%   |
| Blue Microphones            | 9         | 0.12%   |
| Samson Technologies         | 8         | 0.11%   |
| RODE Microphones            | 8         | 0.11%   |
| Dell                        | 7         | 0.09%   |
| Conexant Systems            | 7         | 0.09%   |
| XMOS                        | 6         | 0.08%   |
| Samsung Electronics         | 6         | 0.08%   |
| No brand                    | 6         | 0.08%   |
| Microsoft                   | 6         | 0.08%   |
| Focusrite-Novation          | 6         | 0.08%   |
| CMX Systems                 | 6         | 0.08%   |
| ASUSTek Computer            | 6         | 0.08%   |
| SAVITECH                    | 5         | 0.07%   |
| Tenx Technology             | 4         | 0.05%   |
| PreSonus Audio Electronics  | 4         | 0.05%   |
| M-Audio                     | 4         | 0.05%   |
| GYROCOM C&C                 | 4         | 0.05%   |
| FiiO Electronics Technology | 4         | 0.05%   |
| Yamaha                      | 3         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 978       | 10.56%  |
| AMD Family 17h/19h HD Audio Controller                                     | 905       | 9.77%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 498       | 5.38%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 408       | 4.41%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 384       | 4.15%   |
| Intel Cannon Lake PCH cAVS                                                 | 337       | 3.64%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 277       | 2.99%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 268       | 2.89%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 252       | 2.72%   |
| Intel Comet Lake PCH-LP cAVS                                               | 239       | 2.58%   |
| Intel Haswell-ULT HD Audio Controller                                      | 227       | 2.45%   |
| Intel 8 Series HD Audio Controller                                         | 227       | 2.45%   |
| Intel Broadwell-U Audio Controller                                         | 217       | 2.34%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 214       | 2.31%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 204       | 2.2%    |
| Intel Comet Lake PCH cAVS                                                  | 169       | 1.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 164       | 1.77%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 153       | 1.65%   |
| Intel CM238 HD Audio Controller                                            | 131       | 1.41%   |
| Nvidia GP107GL High Definition Audio Controller                            | 129       | 1.39%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 129       | 1.39%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 124       | 1.34%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 118       | 1.27%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 112       | 1.21%   |
| AMD FCH Azalia Controller                                                  | 96        | 1.04%   |
| Nvidia GA106 High Definition Audio Controller                              | 81        | 0.87%   |
| Nvidia TU106 High Definition Audio Controller                              | 78        | 0.84%   |
| AMD Kabini HDMI/DP Audio                                                   | 78        | 0.84%   |
| Realtek Semiconductor USB Audio                                            | 71        | 0.77%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 70        | 0.76%   |
| Nvidia GF108 High Definition Audio Controller                              | 66        | 0.71%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 62        | 0.67%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 58        | 0.63%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 58        | 0.63%   |
| Nvidia GK107 HDMI Audio Controller                                         | 57        | 0.62%   |
| Nvidia TU116 High Definition Audio Controller                              | 54        | 0.58%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 52        | 0.56%   |
| Nvidia GA104 High Definition Audio Controller                              | 45        | 0.49%   |
| Nvidia GP106 High Definition Audio Controller                              | 44        | 0.48%   |
| Nvidia Audio device                                                        | 42        | 0.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1120      | 29.77%  |
| SK hynix            | 854       | 22.7%   |
| Micron Technology   | 535       | 14.22%  |
| Kingston            | 315       | 8.37%   |
| Crucial             | 210       | 5.58%   |
| Unknown             | 193       | 5.13%   |
| Ramaxel Technology  | 91        | 2.42%   |
| A-DATA Technology   | 87        | 2.31%   |
| Corsair             | 56        | 1.49%   |
| Elpida              | 34        | 0.9%    |
| Smart               | 30        | 0.8%    |
| Unknown (ABCD)      | 24        | 0.64%   |
| Team                | 23        | 0.61%   |
| G.Skill             | 23        | 0.61%   |
| Nanya Technology    | 18        | 0.48%   |
| Patriot             | 17        | 0.45%   |
| Smart Brazil        | 11        | 0.29%   |
| Teikon              | 10        | 0.27%   |
| GOODRAM             | 10        | 0.27%   |
| Unknown             | 10        | 0.27%   |
| Transcend           | 9         | 0.24%   |
| Avant               | 8         | 0.21%   |
| Goldkey             | 5         | 0.13%   |
| Silicon Power       | 4         | 0.11%   |
| Apacer              | 4         | 0.11%   |
| PUSKILL             | 3         | 0.08%   |
| OnBoard             | 3         | 0.08%   |
| Kllisre             | 3         | 0.08%   |
| CSX                 | 3         | 0.08%   |
| Timetec             | 2         | 0.05%   |
| SHARETRONIC         | 2         | 0.05%   |
| Sesame              | 2         | 0.05%   |
| RZX                 | 2         | 0.05%   |
| Qimonda             | 2         | 0.05%   |
| PNY                 | 2         | 0.05%   |
| Memox               | 2         | 0.05%   |
| Lexar               | 2         | 0.05%   |
| ChangXin Memory     | 2         | 0.05%   |
| ASint Technology    | 2         | 0.05%   |
| Wilk                | 1         | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 72        | 1.82%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 68        | 1.72%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 53        | 1.34%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 51        | 1.29%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 35        | 0.88%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 32        | 0.81%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 31        | 0.78%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 30        | 0.76%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 30        | 0.76%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 29        | 0.73%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 28        | 0.71%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 28        | 0.71%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 28        | 0.71%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 28        | 0.71%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 28        | 0.71%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 27        | 0.68%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 27        | 0.68%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 26        | 0.66%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 25        | 0.63%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 25        | 0.63%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 25        | 0.63%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 25        | 0.63%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 23        | 0.58%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 23        | 0.58%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 23        | 0.58%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 22        | 0.55%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 21        | 0.53%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 21        | 0.53%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 21        | 0.53%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 21        | 0.53%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 21        | 0.53%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 20        | 0.5%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 20        | 0.5%    |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 20        | 0.5%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 20        | 0.5%    |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 20        | 0.5%    |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 19        | 0.48%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 19        | 0.48%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 19        | 0.48%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 19        | 0.48%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 1821      | 58.09%  |
| DDR3    | 814       | 25.96%  |
| LPDDR3  | 180       | 5.74%   |
| LPDDR4  | 168       | 5.36%   |
| LPDDR5  | 42        | 1.34%   |
| DDR2    | 40        | 1.28%   |
| DDR5    | 35        | 1.12%   |
| SDRAM   | 18        | 0.57%   |
| Unknown | 13        | 0.41%   |
| DDR     | 3         | 0.1%    |
| DRAM    | 1         | 0.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 2693      | 84.31%  |
| Row Of Chips | 427       | 13.37%  |
| Chip         | 45        | 1.41%   |
| DIMM         | 17        | 0.53%   |
| Unknown      | 12        | 0.38%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 1472      | 43.14%  |
| 4096  | 897       | 26.29%  |
| 16384 | 628       | 18.41%  |
| 2048  | 252       | 7.39%   |
| 32768 | 119       | 3.49%   |
| 1024  | 40        | 1.17%   |
| 3072  | 2         | 0.06%   |
| 512   | 1         | 0.03%   |
| 64    | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 831       | 24.59%  |
| 3200    | 761       | 22.52%  |
| 1600    | 592       | 17.52%  |
| 2400    | 265       | 7.84%   |
| 2133    | 240       | 7.1%    |
| 1333    | 102       | 3.02%   |
| 1334    | 93        | 2.75%   |
| 4267    | 82        | 2.43%   |
| 1867    | 71        | 2.1%    |
| 3266    | 53        | 1.57%   |
| 6400    | 43        | 1.27%   |
| 4800    | 40        | 1.18%   |
| 1067    | 34        | 1.01%   |
| Unknown | 27        | 0.8%    |
| 8400    | 24        | 0.71%   |
| 667     | 24        | 0.71%   |
| 4266    | 22        | 0.65%   |
| 1066    | 16        | 0.47%   |
| 4199    | 15        | 0.44%   |
| 3733    | 13        | 0.38%   |
| 800     | 11        | 0.33%   |
| 975     | 4         | 0.12%   |
| 2933    | 3         | 0.09%   |
| 933     | 2         | 0.06%   |
| 533     | 2         | 0.06%   |
| 3400    | 1         | 0.03%   |
| 2800    | 1         | 0.03%   |
| 2048    | 1         | 0.03%   |
| 1866    | 1         | 0.03%   |
| 1777    | 1         | 0.03%   |
| 1639    | 1         | 0.03%   |
| 1200    | 1         | 0.03%   |
| 333     | 1         | 0.03%   |
| 133     | 1         | 0.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 9         | 25%     |
| Canon               | 8         | 22.22%  |
| Samsung Electronics | 6         | 16.67%  |
| Brother Industries  | 4         | 11.11%  |
| Seiko Epson         | 3         | 8.33%   |
| Prolific Technology | 2         | 5.56%   |
| Ricoh               | 1         | 2.78%   |
| Pantum              | 1         | 2.78%   |
| NXP Semiconductors  | 1         | 2.78%   |
| MiiiW               | 1         | 2.78%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port        | 2         | 5.56%   |
| Seiko Epson WF-2830 Series           | 1         | 2.78%   |
| Seiko Epson L200 Series              | 1         | 2.78%   |
| Seiko Epson ET-2710 Series           | 1         | 2.78%   |
| Samsung SCX-4200 series              | 1         | 2.78%   |
| Samsung SCX-3200 Series              | 1         | 2.78%   |
| Samsung ML-331x Series Laser Printer | 1         | 2.78%   |
| Samsung M2070 Series                 | 1         | 2.78%   |
| Samsung CLX-6260 Series              | 1         | 2.78%   |
| Samsung C43x Series                  | 1         | 2.78%   |
| Ricoh SP 212SUw                      | 1         | 2.78%   |
| Pantum P2500W series                 | 1         | 2.78%   |
| NXP Semiconductors Printer-80        | 1         | 2.78%   |
| MiiiW MW USB Receiver                | 1         | 2.78%   |
| HP Photosmart B010 series            | 1         | 2.78%   |
| HP Officejet 2620 series             | 1         | 2.78%   |
| HP LaserJet 400 colorMFP M475dw      | 1         | 2.78%   |
| HP ENVY Pro 6400 series              | 1         | 2.78%   |
| HP ENVY 4500 series                  | 1         | 2.78%   |
| HP Deskjet 3510 series               | 1         | 2.78%   |
| HP Deskjet 3050A                     | 1         | 2.78%   |
| HP DeskJet 2300 series               | 1         | 2.78%   |
| HP DeskJet 2130 series               | 1         | 2.78%   |
| Canon TR8500 series                  | 1         | 2.78%   |
| Canon TR150 series                   | 1         | 2.78%   |
| Canon PIXMA MG3600 Series            | 1         | 2.78%   |
| Canon PIXMA MG3500 Series            | 1         | 2.78%   |
| Canon PIXMA MG3000 series            | 1         | 2.78%   |
| Canon MF3110                         | 1         | 2.78%   |
| Canon MF220 Series                   | 1         | 2.78%   |
| Canon iP7200 series                  | 1         | 2.78%   |
| Brother Printer                      | 1         | 2.78%   |
| Brother HL-5250DN Printer            | 1         | 2.78%   |
| Brother DCP-T220                     | 1         | 2.78%   |
| Brother DCP-1600                     | 1         | 2.78%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 6         | 60%     |
| Seiko Epson     | 3         | 30%     |
| Hewlett-Packard | 1         | 10%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20          | 2         | 20%     |
| Canon CanoScan LiDE 220                     | 2         | 20%     |
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1         | 10%     |
| Seiko Epson GT-X770 [Perfection V500]       | 1         | 10%     |
| Seiko Epson ES-D400 [GT-S80]                | 1         | 10%     |
| HP Scanjet 300                              | 1         | 10%     |
| Canon CanoScan N650U/N656U                  | 1         | 10%     |
| Canon CanoScan LiDE 210                     | 1         | 10%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1373      | 24.71%  |
| IMC Networks                           | 684       | 12.31%  |
| Microdia                               | 507       | 9.12%   |
| Realtek Semiconductor                  | 477       | 8.58%   |
| Acer                                   | 453       | 8.15%   |
| Quanta                                 | 317       | 5.7%    |
| Sunplus Innovation Technology          | 295       | 5.31%   |
| Cheng Uei Precision Industry (Foxlink) | 221       | 3.98%   |
| Lite-On Technology                     | 164       | 2.95%   |
| Syntek                                 | 152       | 2.74%   |
| Logitech                               | 130       | 2.34%   |
| Apple                                  | 111       | 2%      |
| Luxvisions Innotech Limited            | 98        | 1.76%   |
| Suyin                                  | 90        | 1.62%   |
| Silicon Motion                         | 67        | 1.21%   |
| Bison Electronics                      | 63        | 1.13%   |
| Alcor Micro                            | 40        | 0.72%   |
| Samsung Electronics                    | 36        | 0.65%   |
| Ricoh                                  | 33        | 0.59%   |
| Sonix Technology                       | 26        | 0.47%   |
| Primax Electronics                     | 20        | 0.36%   |
| Lenovo                                 | 20        | 0.36%   |
| Microsoft                              | 16        | 0.29%   |
| Importek                               | 14        | 0.25%   |
| Z-Star Microelectronics                | 11        | 0.2%    |
| SunplusIT                              | 11        | 0.2%    |
| Generalplus Technology                 | 9         | 0.16%   |
| USB Camera                             | 8         | 0.14%   |
| ARC International                      | 8         | 0.14%   |
| KYE Systems (Mouse Systems)            | 6         | 0.11%   |
| ALi                                    | 6         | 0.11%   |
| Pixart Imaging                         | 5         | 0.09%   |
| MacroSilicon                           | 5         | 0.09%   |
| Intel                                  | 5         | 0.09%   |
| WaveRider Communications               | 4         | 0.07%   |
| Tobii Technology AB                    | 4         | 0.07%   |
| Shenzhen Kingcome Optoelectronic       | 4         | 0.07%   |
| Y Media                                | 3         | 0.05%   |
| Tripath Technology                     | 3         | 0.05%   |
| Razer USA                              | 3         | 0.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 496       | 8.84%   |
| Microdia Integrated_Webcam_HD                       | 293       | 5.22%   |
| IMC Networks Integrated Camera                      | 271       | 4.83%   |
| Realtek Integrated_Webcam_HD                        | 217       | 3.87%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 173       | 3.08%   |
| Chicony HD WebCam                                   | 134       | 2.39%   |
| Sunplus Integrated_Webcam_HD                        | 130       | 2.32%   |
| Acer Integrated Camera                              | 121       | 2.16%   |
| Syntek Integrated Camera                            | 99        | 1.77%   |
| Chicony Integrated Camera (1280x720@30)             | 78        | 1.39%   |
| Lite-On Integrated Camera                           | 76        | 1.35%   |
| Quanta HD User Facing                               | 69        | 1.23%   |
| Chicony HP HD Camera                                | 59        | 1.05%   |
| Acer SunplusIT Integrated Camera                    | 56        | 1%      |
| IMC Networks USB2.0 VGA UVC WebCam                  | 53        | 0.94%   |
| Acer Lenovo EasyCamera                              | 53        | 0.94%   |
| Quanta HP TrueVision HD Camera                      | 49        | 0.87%   |
| IMC Networks HD Camera                              | 44        | 0.78%   |
| Chicony USB2.0 Camera                               | 43        | 0.77%   |
| Acer HD Webcam                                      | 43        | 0.77%   |
| Microdia Integrated Webcam                          | 41        | 0.73%   |
| Quanta HP HD Camera                                 | 38        | 0.68%   |
| Lite-On HP HD Camera                                | 37        | 0.66%   |
| Samsung Galaxy A5 (MTP)                             | 36        | 0.64%   |
| Chicony Integrated IR Camera                        | 35        | 0.62%   |
| Bison Integrated Camera                             | 35        | 0.62%   |
| Chicony HP TrueVision HD Camera                     | 34        | 0.61%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 34        | 0.61%   |
| Realtek Integrated Webcam                           | 33        | 0.59%   |
| Chicony HP Wide Vision HD Camera                    | 33        | 0.59%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 33        | 0.59%   |
| Realtek USB Camera                                  | 32        | 0.57%   |
| Quanta HD Webcam                                    | 32        | 0.57%   |
| Logitech HD Pro Webcam C920                         | 32        | 0.57%   |
| Sunplus HD WebCam                                   | 31        | 0.55%   |
| Chicony HD User Facing                              | 31        | 0.55%   |
| Apple Built-in iSight                               | 31        | 0.55%   |
| Quanta VGA WebCam                                   | 29        | 0.52%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 29        | 0.52%   |
| Chicony USB2.0 HD UVC WebCam                        | 29        | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 527       | 36.37%  |
| Validity Sensors                   | 446       | 30.78%  |
| Shenzhen Goodix Technology         | 239       | 16.49%  |
| Elan Microelectronics              | 83        | 5.73%   |
| Upek                               | 55        | 3.8%    |
| LighTuning Technology              | 50        | 3.45%   |
| AuthenTec                          | 31        | 2.14%   |
| Samsung Electronics                | 6         | 0.41%   |
| STMicroelectronics                 | 4         | 0.28%   |
| Focal-systems.Corp                 | 4         | 0.28%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 0.21%   |
| Dell                               | 1         | 0.07%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 260       | 17.93%  |
| Shenzhen Goodix  Fingerprint Device                                        | 141       | 9.72%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 101       | 6.97%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 89        | 6.14%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 84        | 5.79%   |
| Shenzhen Goodix FingerPrint                                                | 54        | 3.72%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 53        | 3.66%   |
| Elan ELAN:Fingerprint                                                      | 52        | 3.59%   |
| Validity Sensors Synaptics WBDI                                            | 48        | 3.31%   |
| Shenzhen Goodix Fingerprint Reader                                         | 44        | 3.03%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 40        | 2.76%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 40        | 2.76%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 36        | 2.48%   |
| Elan ELAN:ARM-M4                                                           | 30        | 2.07%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 28        | 1.93%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 26        | 1.79%   |
| Validity Sensors VFS491                                                    | 25        | 1.72%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 23        | 1.59%   |
| Synaptics  WBDI                                                            | 21        | 1.45%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 19        | 1.31%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 18        | 1.24%   |
| Validity Sensors Fingerprint scanner                                       | 17        | 1.17%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 17        | 1.17%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 16        | 1.1%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 15        | 1.03%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 13        | 0.9%    |
| Synaptics UWP WBDI Device                                                  | 13        | 0.9%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 12        | 0.83%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 11        | 0.76%   |
| Synaptics WBDI                                                             | 9         | 0.62%   |
| Synaptics UWP WBDI                                                         | 9         | 0.62%   |
| AuthenTec Fingerprint Sensor                                               | 8         | 0.55%   |
| AuthenTec AES2810                                                          | 7         | 0.48%   |
| Unknown                                                                    | 7         | 0.48%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 6         | 0.41%   |
| Synaptics WBDI Device                                                      | 6         | 0.41%   |
| Validity Sensors VFS Fingerprint sensor                                    | 5         | 0.34%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 0.34%   |
| STMicroelectronics Fingerprint Reader                                      | 4         | 0.28%   |
| Samsung Fingerprint Device                                                 | 4         | 0.28%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Alcor Micro                | 234       | 42.09%  |
| Broadcom                   | 219       | 39.39%  |
| Upek                       | 36        | 6.47%   |
| Lenovo                     | 30        | 5.4%    |
| O2 Micro                   | 12        | 2.16%   |
| Gemalto (was Gemplus)      | 6         | 1.08%   |
| SCM Microsystems           | 3         | 0.54%   |
| OmniKey                    | 3         | 0.54%   |
| Aladdin Knowledge Systems  | 3         | 0.54%   |
| Yubico.com                 | 2         | 0.36%   |
| Realtek Semiconductor      | 2         | 0.36%   |
| Reiner SCT Kartensysteme   | 1         | 0.18%   |
| Purism, SPC                | 1         | 0.18%   |
| Hewlett-Packard            | 1         | 0.18%   |
| Chicony Electronics        | 1         | 0.18%   |
| Athena Smartcard Solutions | 1         | 0.18%   |
| Advanced Card Systems      | 1         | 0.18%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 233       | 41.91%  |
| Broadcom 5880                                                                | 74        | 13.31%  |
| Broadcom 58200                                                               | 55        | 9.89%   |
| Broadcom BCM5880 Secure Applications Processor                               | 52        | 9.35%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 36        | 6.47%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 36        | 6.47%   |
| Lenovo Integrated Smart Card Reader                                          | 29        | 5.22%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 9         | 1.62%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 5         | 0.9%    |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 0.54%   |
| Aladdin Knowledge Systems Token JC                                           | 3         | 0.54%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 0.36%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 0.36%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.36%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.18%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 0.18%   |
| SCM Microsystems CLOUD 2900 R Smart Card Reader                              | 1         | 0.18%   |
| Reiner SCT Kartensysteme tanJack USB                                         | 1         | 0.18%   |
| Purism, SPC Librem Key                                                       | 1         | 0.18%   |
| OmniKey CardMan 4321                                                         | 1         | 0.18%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.18%   |
| OmniKey CardMan 1021                                                         | 1         | 0.18%   |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.18%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.18%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.18%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.18%   |
| Athena Smartcard Solutions ASEDrive CCID                                     | 1         | 0.18%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.18%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.18%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 3559      | 58.37%  |
| 1     | 2084      | 34.18%  |
| 2     | 386       | 6.33%   |
| 3     | 47        | 0.77%   |
| 4     | 8         | 0.13%   |
| 5     | 6         | 0.1%    |
| 7     | 3         | 0.05%   |
| 6     | 3         | 0.05%   |
| 8     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 1435      | 48.28%  |
| Graphics card            | 543       | 18.27%  |
| Multimedia controller    | 263       | 8.85%   |
| Net/wireless             | 197       | 6.63%   |
| Chipcard                 | 195       | 6.56%   |
| Camera                   | 113       | 3.8%    |
| Bluetooth                | 60        | 2.02%   |
| Storage                  | 44        | 1.48%   |
| Card reader              | 41        | 1.38%   |
| Sound                    | 20        | 0.67%   |
| Net/ethernet             | 17        | 0.57%   |
| Communication controller | 16        | 0.54%   |
| Network                  | 15        | 0.5%    |
| Modem                    | 8         | 0.27%   |
| Flash memory             | 2         | 0.07%   |
| Video                    | 1         | 0.03%   |
| Firewire controller      | 1         | 0.03%   |
| Dvb card                 | 1         | 0.03%   |

