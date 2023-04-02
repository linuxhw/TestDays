Linux in Poland - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Poland.

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

Total: 4012

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | G560 20042                  | [c5a4783dfb](https://linux-hardware.org/?probe=c5a4783dfb) | Apr 01, 2023 |
| HP            | Compaq Presario CQ60        | [e5a729243d](https://linux-hardware.org/?probe=e5a729243d) | Mar 31, 2023 |
| Samsung       | 950XED                      | [c3b37a213a](https://linux-hardware.org/?probe=c3b37a213a) | Mar 31, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [e2c6f05595](https://linux-hardware.org/?probe=e2c6f05595) | Mar 31, 2023 |
| HUAWEI        | KPL-W0X                     | [6e93ca4159](https://linux-hardware.org/?probe=6e93ca4159) | Mar 31, 2023 |
| Acer          | TravelMate 8172Z            | [10cc090653](https://linux-hardware.org/?probe=10cc090653) | Mar 31, 2023 |
| Dell          | Latitude D620               | [801ede47a2](https://linux-hardware.org/?probe=801ede47a2) | Mar 31, 2023 |
| ASUSTek       | K53SJ                       | [aa9a729217](https://linux-hardware.org/?probe=aa9a729217) | Mar 30, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [6b9737a62f](https://linux-hardware.org/?probe=6b9737a62f) | Mar 30, 2023 |
| HP            | Laptop 15s-fq2xxx           | [f78b6ab8c5](https://linux-hardware.org/?probe=f78b6ab8c5) | Mar 30, 2023 |
| Dell          | Latitude E6530              | [eb7392d1ae](https://linux-hardware.org/?probe=eb7392d1ae) | Mar 29, 2023 |
| Lenovo        | G570 20079                  | [680c7a04ed](https://linux-hardware.org/?probe=680c7a04ed) | Mar 29, 2023 |
| GPD           | G1621-02                    | [2ed8b6c147](https://linux-hardware.org/?probe=2ed8b6c147) | Mar 29, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [fa1a582da6](https://linux-hardware.org/?probe=fa1a582da6) | Mar 29, 2023 |
| HP            | 250 G6 Notebook PC          | [94cdfc44d1](https://linux-hardware.org/?probe=94cdfc44d1) | Mar 28, 2023 |
| Kiano         | Elegance 14.2               | [ea2013b347](https://linux-hardware.org/?probe=ea2013b347) | Mar 28, 2023 |
| Lenovo        | ThinkPad T470p 20J7S0QK0... | [7f5fb11940](https://linux-hardware.org/?probe=7f5fb11940) | Mar 28, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [856b789461](https://linux-hardware.org/?probe=856b789461) | Mar 28, 2023 |
| Dell          | Latitude 7490               | [41d01ead49](https://linux-hardware.org/?probe=41d01ead49) | Mar 28, 2023 |
| Dell          | Inspiron 5735               | [823a6ece98](https://linux-hardware.org/?probe=823a6ece98) | Mar 27, 2023 |
| Lenovo        | ThinkPad X250 20CLS47P00    | [e287203572](https://linux-hardware.org/?probe=e287203572) | Mar 27, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [60012fd503](https://linux-hardware.org/?probe=60012fd503) | Mar 27, 2023 |
| Dell          | XPS 13 7390                 | [aaeb6059a2](https://linux-hardware.org/?probe=aaeb6059a2) | Mar 27, 2023 |
| Dell          | Precision 7670              | [eece926391](https://linux-hardware.org/?probe=eece926391) | Mar 27, 2023 |
| Dell          | Latitude 3190               | [757f1fc2e7](https://linux-hardware.org/?probe=757f1fc2e7) | Mar 27, 2023 |
| Dell          | Precision 7670              | [5b8f0590ec](https://linux-hardware.org/?probe=5b8f0590ec) | Mar 27, 2023 |
| Lenovo        | ThinkPad T520 4243RP3       | [38fa314d2f](https://linux-hardware.org/?probe=38fa314d2f) | Mar 26, 2023 |
| MSI           | Creator Z16 A11UET          | [0133ab37af](https://linux-hardware.org/?probe=0133ab37af) | Mar 26, 2023 |
| Sony          | VGN-BX61VN                  | [76f62cf9c1](https://linux-hardware.org/?probe=76f62cf9c1) | Mar 26, 2023 |
| Lenovo        | G50-80 80E5                 | [250e0a99d1](https://linux-hardware.org/?probe=250e0a99d1) | Mar 26, 2023 |
| Lenovo        | G510 20238                  | [f406bad420](https://linux-hardware.org/?probe=f406bad420) | Mar 26, 2023 |
| Lenovo        | ThinkPad W520 4282PQ7       | [ff42aa158f](https://linux-hardware.org/?probe=ff42aa158f) | Mar 25, 2023 |
| HP            | Notebook                    | [7c4088912e](https://linux-hardware.org/?probe=7c4088912e) | Mar 25, 2023 |
| Lenovo        | ThinkPad T480s 20L7S0YA0... | [f4cb79dbf8](https://linux-hardware.org/?probe=f4cb79dbf8) | Mar 25, 2023 |
| Valve         | Jupiter                     | [6a7628c31d](https://linux-hardware.org/?probe=6a7628c31d) | Mar 25, 2023 |
| HP            | Pavilion dv6                | [29a94d3d9e](https://linux-hardware.org/?probe=29a94d3d9e) | Mar 25, 2023 |
| HP            | Pavilion dv6                | [c3a6c3f669](https://linux-hardware.org/?probe=c3a6c3f669) | Mar 25, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [7f32708bde](https://linux-hardware.org/?probe=7f32708bde) | Mar 24, 2023 |
| HP            | Pavilion Notebook           | [446c510c65](https://linux-hardware.org/?probe=446c510c65) | Mar 24, 2023 |
| Toshiba       | Satellite C855-12N          | [cb9692876c](https://linux-hardware.org/?probe=cb9692876c) | Mar 24, 2023 |
| Toshiba       | Satellite Pro A50-C         | [2fe9003124](https://linux-hardware.org/?probe=2fe9003124) | Mar 24, 2023 |
| Toshiba       | Satellite Pro A50-C         | [95c5c45220](https://linux-hardware.org/?probe=95c5c45220) | Mar 24, 2023 |
| MSI           | Creator Z17 A12UHST         | [47814b01b6](https://linux-hardware.org/?probe=47814b01b6) | Mar 24, 2023 |
| Sony          | SVE1512M6ESI                | [db00c70eb7](https://linux-hardware.org/?probe=db00c70eb7) | Mar 24, 2023 |
| Dell          | Latitude E7450              | [c1e43b6a40](https://linux-hardware.org/?probe=c1e43b6a40) | Mar 23, 2023 |
| Lenovo        | G580                        | [367ed9241a](https://linux-hardware.org/?probe=367ed9241a) | Mar 23, 2023 |
| Lenovo        | G580                        | [6ee526d77a](https://linux-hardware.org/?probe=6ee526d77a) | Mar 22, 2023 |
| Acer          | Aspire VN7-791              | [054efde4e8](https://linux-hardware.org/?probe=054efde4e8) | Mar 22, 2023 |
| Lenovo        | G50-80 80E5                 | [f6ad6626ff](https://linux-hardware.org/?probe=f6ad6626ff) | Mar 22, 2023 |
| HUAWEI        | KPL-W0X                     | [0ae6ab3ff6](https://linux-hardware.org/?probe=0ae6ab3ff6) | Mar 21, 2023 |
| Unknown       | Unknown                     | [31ee1d66d8](https://linux-hardware.org/?probe=31ee1d66d8) | Mar 21, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [57663c8d60](https://linux-hardware.org/?probe=57663c8d60) | Mar 21, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [f5cbd1977f](https://linux-hardware.org/?probe=f5cbd1977f) | Mar 20, 2023 |
| Dell          | Latitude 3190               | [f4bea67dcc](https://linux-hardware.org/?probe=f4bea67dcc) | Mar 20, 2023 |
| HP            | EliteBook 830 G5            | [ba804b8e21](https://linux-hardware.org/?probe=ba804b8e21) | Mar 20, 2023 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [919ccc204b](https://linux-hardware.org/?probe=919ccc204b) | Mar 19, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [c89c2e1369](https://linux-hardware.org/?probe=c89c2e1369) | Mar 18, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [31299394e0](https://linux-hardware.org/?probe=31299394e0) | Mar 18, 2023 |
| Fujitsu       | LIFEBOOK AH530              | [e40cf4f577](https://linux-hardware.org/?probe=e40cf4f577) | Mar 18, 2023 |
| Dell          | Venue 11 Pro 7130 MS        | [2a3bb3e212](https://linux-hardware.org/?probe=2a3bb3e212) | Mar 18, 2023 |
| Dell          | Venue 11 Pro 7130 MS        | [56fab2cb17](https://linux-hardware.org/?probe=56fab2cb17) | Mar 18, 2023 |
| Lenovo        | G570 20079                  | [2d7a146140](https://linux-hardware.org/?probe=2d7a146140) | Mar 18, 2023 |
| ASUSTek       | K52Jc                       | [07dc0a0959](https://linux-hardware.org/?probe=07dc0a0959) | Mar 18, 2023 |
| ASUSTek       | K52Jc                       | [f61ec5ce9f](https://linux-hardware.org/?probe=f61ec5ce9f) | Mar 18, 2023 |
| Dell          | Latitude 5420               | [318da7f6c0](https://linux-hardware.org/?probe=318da7f6c0) | Mar 18, 2023 |
| Toshiba       | QOSMIO X500                 | [2ce878e92e](https://linux-hardware.org/?probe=2ce878e92e) | Mar 17, 2023 |
| Dell          | G5 5590                     | [9686d438e6](https://linux-hardware.org/?probe=9686d438e6) | Mar 17, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [728c9ad9f5](https://linux-hardware.org/?probe=728c9ad9f5) | Mar 17, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | [593bd6b3ac](https://linux-hardware.org/?probe=593bd6b3ac) | Mar 17, 2023 |
| Dell          | Latitude E7440              | [8a6e751b61](https://linux-hardware.org/?probe=8a6e751b61) | Mar 16, 2023 |
| HP            | Laptop 15-bs0xx             | [f53eccbbe9](https://linux-hardware.org/?probe=f53eccbbe9) | Mar 16, 2023 |
| Dell          | Latitude 5511               | [7444a8c723](https://linux-hardware.org/?probe=7444a8c723) | Mar 16, 2023 |
| Dell          | Latitude D620               | [1731735e10](https://linux-hardware.org/?probe=1731735e10) | Mar 16, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [eb0beb38eb](https://linux-hardware.org/?probe=eb0beb38eb) | Mar 16, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [c54f2ca880](https://linux-hardware.org/?probe=c54f2ca880) | Mar 16, 2023 |
| Sony          | VPCEH1S1E                   | [9e8a96156c](https://linux-hardware.org/?probe=9e8a96156c) | Mar 15, 2023 |
| Lenovo        | ThinkPad T440p 20AWS19P0... | [6a2d338526](https://linux-hardware.org/?probe=6a2d338526) | Mar 15, 2023 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | [59d7fa9a34](https://linux-hardware.org/?probe=59d7fa9a34) | Mar 15, 2023 |
| Dell          | Latitude 7390               | [7cc6b3a278](https://linux-hardware.org/?probe=7cc6b3a278) | Mar 15, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | [97fe8661ed](https://linux-hardware.org/?probe=97fe8661ed) | Mar 14, 2023 |
| Kiano         | Elegance 14.2               | [f9ed050c6a](https://linux-hardware.org/?probe=f9ed050c6a) | Mar 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [daa3d3869e](https://linux-hardware.org/?probe=daa3d3869e) | Mar 14, 2023 |
| HP            | ProBook 450 G3              | [d422d0d291](https://linux-hardware.org/?probe=d422d0d291) | Mar 14, 2023 |
| Lenovo        | ThinkPad X301 2776LEG       | [7b0df25d34](https://linux-hardware.org/?probe=7b0df25d34) | Mar 14, 2023 |
| Lenovo        | ThinkPad X301 2776LEG       | [65fe38f62e](https://linux-hardware.org/?probe=65fe38f62e) | Mar 14, 2023 |
| Toshiba       | Satellite L40               | [bfc73429bb](https://linux-hardware.org/?probe=bfc73429bb) | Mar 13, 2023 |
| Samsung       | 300E4A/300E5A/300E7A        | [6c76af84cb](https://linux-hardware.org/?probe=6c76af84cb) | Mar 13, 2023 |
| Acer          | Aspire A315-24P             | [b9cfb4b900](https://linux-hardware.org/?probe=b9cfb4b900) | Mar 13, 2023 |
| Acer          | Aspire A315-24P             | [fba21e619d](https://linux-hardware.org/?probe=fba21e619d) | Mar 13, 2023 |
| HP            | Pavilion dv6                | [f649c78020](https://linux-hardware.org/?probe=f649c78020) | Mar 13, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [bc375a2ddd](https://linux-hardware.org/?probe=bc375a2ddd) | Mar 13, 2023 |
| Dell          | Latitude 3190               | [97cc3ffc79](https://linux-hardware.org/?probe=97cc3ffc79) | Mar 13, 2023 |
| ASUSTek       | X551MA                      | [37b002e8ec](https://linux-hardware.org/?probe=37b002e8ec) | Mar 12, 2023 |
| Lenovo        | ThinkPad X240 20AMS0XP0S    | [a2ee9a2818](https://linux-hardware.org/?probe=a2ee9a2818) | Mar 12, 2023 |
| ASUSTek       | N550JK                      | [bb5d069d90](https://linux-hardware.org/?probe=bb5d069d90) | Mar 12, 2023 |
| Google        | Electro                     | [86cbc9d907](https://linux-hardware.org/?probe=86cbc9d907) | Mar 12, 2023 |
| HP            | 250 G6 Notebook PC          | [d173735b81](https://linux-hardware.org/?probe=d173735b81) | Mar 11, 2023 |
| Dell          | Precision M6600             | [9d5e2f1e01](https://linux-hardware.org/?probe=9d5e2f1e01) | Mar 11, 2023 |
| Acer          | Extensa 5620                | [f95239bf35](https://linux-hardware.org/?probe=f95239bf35) | Mar 11, 2023 |
| Kiano         | Elegance 14.2               | [5714b30108](https://linux-hardware.org/?probe=5714b30108) | Mar 11, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [82b5297ab8](https://linux-hardware.org/?probe=82b5297ab8) | Mar 11, 2023 |
| Lenovo        | ThinkPad T440p 20AWS19P0... | [44867c946f](https://linux-hardware.org/?probe=44867c946f) | Mar 10, 2023 |
| Dell          | Latitude E6530              | [70b72984bc](https://linux-hardware.org/?probe=70b72984bc) | Mar 10, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | [2d99e047c9](https://linux-hardware.org/?probe=2d99e047c9) | Mar 10, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [99d5f17b22](https://linux-hardware.org/?probe=99d5f17b22) | Mar 09, 2023 |
| HP            | Laptop 15s-eq0xxx           | [7a7e8bc855](https://linux-hardware.org/?probe=7a7e8bc855) | Mar 09, 2023 |
| ASUSTek       | X550CL                      | [9acfcb9b4f](https://linux-hardware.org/?probe=9acfcb9b4f) | Mar 09, 2023 |
| Lenovo        | IdeaPad Y580                | [cc2d7d8a95](https://linux-hardware.org/?probe=cc2d7d8a95) | Mar 09, 2023 |
| Dell          | Latitude E6440              | [b00f44cd46](https://linux-hardware.org/?probe=b00f44cd46) | Mar 09, 2023 |
| Dell          | Latitude E6440              | [3b9229e07a](https://linux-hardware.org/?probe=3b9229e07a) | Mar 09, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [c50daaf3b9](https://linux-hardware.org/?probe=c50daaf3b9) | Mar 09, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [fdc32a6871](https://linux-hardware.org/?probe=fdc32a6871) | Mar 09, 2023 |
| ASUSTek       | X550CL                      | [21f11cf791](https://linux-hardware.org/?probe=21f11cf791) | Mar 09, 2023 |
| HP            | EliteBook 8570w             | [dfd9b7a9b9](https://linux-hardware.org/?probe=dfd9b7a9b9) | Mar 08, 2023 |
| HP            | ENVY 6                      | [4873f7b85f](https://linux-hardware.org/?probe=4873f7b85f) | Mar 08, 2023 |
| Lenovo        | ThinkPad T61 7661BM5        | [daf29f1a82](https://linux-hardware.org/?probe=daf29f1a82) | Mar 08, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [233722f0e1](https://linux-hardware.org/?probe=233722f0e1) | Mar 07, 2023 |
| Dell          | Latitude 7290               | [38f12088b2](https://linux-hardware.org/?probe=38f12088b2) | Mar 07, 2023 |
| HUAWEI        | KPL-W0X                     | [76ebbe553f](https://linux-hardware.org/?probe=76ebbe553f) | Mar 06, 2023 |
| Dell          | Latitude 3190               | [a3a4113ab4](https://linux-hardware.org/?probe=a3a4113ab4) | Mar 06, 2023 |
| Lenovo        | Legion 5 17ACH6 82K0        | [6db57d4d9f](https://linux-hardware.org/?probe=6db57d4d9f) | Mar 05, 2023 |
| ASUSTek       | X551MA                      | [b77e06361b](https://linux-hardware.org/?probe=b77e06361b) | Mar 05, 2023 |
| Lenovo        | ThinkPad T440p 20AWS37F0... | [48677f9f86](https://linux-hardware.org/?probe=48677f9f86) | Mar 05, 2023 |
| IGEL Techn... | H830C                       | [3619b3fcee](https://linux-hardware.org/?probe=3619b3fcee) | Mar 05, 2023 |
| ASUSTek       | N71Vg                       | [4d83fda5ba](https://linux-hardware.org/?probe=4d83fda5ba) | Mar 05, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [8b36c984f8](https://linux-hardware.org/?probe=8b36c984f8) | Mar 05, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [65006682e6](https://linux-hardware.org/?probe=65006682e6) | Mar 05, 2023 |
| HP            | 15                          | [0efd9be7ae](https://linux-hardware.org/?probe=0efd9be7ae) | Mar 04, 2023 |
| HP            | 15                          | [b8a33a3d73](https://linux-hardware.org/?probe=b8a33a3d73) | Mar 04, 2023 |
| Lenovo        | ThinkPad T420 4177R3U       | [525dd38cf1](https://linux-hardware.org/?probe=525dd38cf1) | Mar 04, 2023 |
| Toshiba       | Satellite L40               | [bd108fcfba](https://linux-hardware.org/?probe=bd108fcfba) | Mar 04, 2023 |
| HP            | Notebook                    | [229fbff95c](https://linux-hardware.org/?probe=229fbff95c) | Mar 04, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [afe8ef7318](https://linux-hardware.org/?probe=afe8ef7318) | Mar 04, 2023 |
| HP            | EliteBook 830 G5            | [82acbe37f7](https://linux-hardware.org/?probe=82acbe37f7) | Mar 04, 2023 |
| Dell          | Vostro 3350                 | [1bfad93a1e](https://linux-hardware.org/?probe=1bfad93a1e) | Mar 04, 2023 |
| Dell          | Vostro 3350                 | [f782f8e288](https://linux-hardware.org/?probe=f782f8e288) | Mar 04, 2023 |
| Apple         | MacBookPro8,2               | [0b0c5a6895](https://linux-hardware.org/?probe=0b0c5a6895) | Mar 04, 2023 |
| ASUSTek       | X550CL                      | [c16eae7537](https://linux-hardware.org/?probe=c16eae7537) | Mar 04, 2023 |
| IGEL Techn... | H830C                       | [4625dc0660](https://linux-hardware.org/?probe=4625dc0660) | Mar 04, 2023 |
| Toshiba       | Satellite L40               | [e3f1423c39](https://linux-hardware.org/?probe=e3f1423c39) | Mar 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | [0228fd4ab1](https://linux-hardware.org/?probe=0228fd4ab1) | Mar 04, 2023 |
| Dell          | Latitude 5480               | [4679c9328e](https://linux-hardware.org/?probe=4679c9328e) | Mar 03, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [9186971572](https://linux-hardware.org/?probe=9186971572) | Mar 03, 2023 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | [25f45efbc1](https://linux-hardware.org/?probe=25f45efbc1) | Mar 03, 2023 |
| ASUSTek       | X551MA                      | [608c8a42da](https://linux-hardware.org/?probe=608c8a42da) | Mar 03, 2023 |
| ASUSTek       | X551MA                      | [fa55d9fb5c](https://linux-hardware.org/?probe=fa55d9fb5c) | Mar 03, 2023 |
| Lenovo        | ThinkPad T480s 20L8S2B50... | [8268a3bbf3](https://linux-hardware.org/?probe=8268a3bbf3) | Mar 03, 2023 |
| ASUSTek       | N61Vn                       | [9528e36d7b](https://linux-hardware.org/?probe=9528e36d7b) | Mar 03, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [726752f23a](https://linux-hardware.org/?probe=726752f23a) | Mar 02, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [a5288ab43b](https://linux-hardware.org/?probe=a5288ab43b) | Mar 02, 2023 |
| HP            | ZBook Power G7 Mobile Wo... | [e87ce2454c](https://linux-hardware.org/?probe=e87ce2454c) | Mar 02, 2023 |
| Dell          | Latitude D830               | [83415c82ac](https://linux-hardware.org/?probe=83415c82ac) | Mar 02, 2023 |
| Acer          | Aspire V3-574G              | [e943ab2cde](https://linux-hardware.org/?probe=e943ab2cde) | Mar 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [9b0d952fa9](https://linux-hardware.org/?probe=9b0d952fa9) | Mar 01, 2023 |
| Notebook      | NS50_70MU                   | [18ff6f22a6](https://linux-hardware.org/?probe=18ff6f22a6) | Mar 01, 2023 |
| Dell          | Latitude 5420               | [0596aff5c4](https://linux-hardware.org/?probe=0596aff5c4) | Feb 28, 2023 |
| Lenovo        | Yoga710-14ISK 80TY          | [756e003316](https://linux-hardware.org/?probe=756e003316) | Feb 28, 2023 |
| HP            | ZBook 15u G3                | [9c49a1748b](https://linux-hardware.org/?probe=9c49a1748b) | Feb 28, 2023 |
| Lenovo        | ThinkPad E560 20EV000UUK    | [7060b60651](https://linux-hardware.org/?probe=7060b60651) | Feb 27, 2023 |
| HP            | ProBook 430 G6              | [a184aa7141](https://linux-hardware.org/?probe=a184aa7141) | Feb 27, 2023 |
| Lenovo        | G50-80 80E5                 | [d7bb021829](https://linux-hardware.org/?probe=d7bb021829) | Feb 27, 2023 |
| ASUSTek       | K75VJ                       | [7fc0fff829](https://linux-hardware.org/?probe=7fc0fff829) | Feb 27, 2023 |
| Dell          | Latitude 7390               | [a2167ae72b](https://linux-hardware.org/?probe=a2167ae72b) | Feb 27, 2023 |
| Schenker      | VISION (E22)                | [498444ca02](https://linux-hardware.org/?probe=498444ca02) | Feb 27, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [1ce9430009](https://linux-hardware.org/?probe=1ce9430009) | Feb 27, 2023 |
| HP            | Notebook                    | [a1180ad479](https://linux-hardware.org/?probe=a1180ad479) | Feb 27, 2023 |
| HP            | Notebook                    | [ee2645efa8](https://linux-hardware.org/?probe=ee2645efa8) | Feb 27, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [d57bb59dee](https://linux-hardware.org/?probe=d57bb59dee) | Feb 27, 2023 |
| ASUSTek       | K52F                        | [fa30ea101a](https://linux-hardware.org/?probe=fa30ea101a) | Feb 27, 2023 |
| Dell          | Latitude 3190               | [279b385865](https://linux-hardware.org/?probe=279b385865) | Feb 27, 2023 |
| HP            | Notebook                    | [0d838134b7](https://linux-hardware.org/?probe=0d838134b7) | Feb 27, 2023 |
| Acer          | Aspire ES1-711              | [8e397cc54f](https://linux-hardware.org/?probe=8e397cc54f) | Feb 26, 2023 |
| Gigabyte      | MMLP5AP-00                  | [eb5ca5bb8d](https://linux-hardware.org/?probe=eb5ca5bb8d) | Feb 26, 2023 |
| Valve         | Jupiter                     | [f7289abeb1](https://linux-hardware.org/?probe=f7289abeb1) | Feb 26, 2023 |
| Dell          | Latitude D630               | [cfdc009ff1](https://linux-hardware.org/?probe=cfdc009ff1) | Feb 26, 2023 |
| Acer          | Aspire E5-571G              | [07fe4333eb](https://linux-hardware.org/?probe=07fe4333eb) | Feb 25, 2023 |
| Sony          | VGN-FZ31M                   | [6b830e36f1](https://linux-hardware.org/?probe=6b830e36f1) | Feb 25, 2023 |
| HP            | ZBook 15u G3                | [92879d708d](https://linux-hardware.org/?probe=92879d708d) | Feb 24, 2023 |
| HP            | ZBook 15u G3                | [8a698df80f](https://linux-hardware.org/?probe=8a698df80f) | Feb 24, 2023 |
| HP            | EliteBook 840 G2            | [f1fa3164f9](https://linux-hardware.org/?probe=f1fa3164f9) | Feb 24, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [00591dc764](https://linux-hardware.org/?probe=00591dc764) | Feb 23, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [a85b9d1452](https://linux-hardware.org/?probe=a85b9d1452) | Feb 23, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [e2cdf5625c](https://linux-hardware.org/?probe=e2cdf5625c) | Feb 23, 2023 |
| Dell          | XPS 9320                    | [94e7c2d282](https://linux-hardware.org/?probe=94e7c2d282) | Feb 23, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [bfbb3aab2c](https://linux-hardware.org/?probe=bfbb3aab2c) | Feb 23, 2023 |
| ASUSTek       | 1215B                       | [970d77d150](https://linux-hardware.org/?probe=970d77d150) | Feb 22, 2023 |
| Notebook      | NS50_70MU                   | [a213ec0ba4](https://linux-hardware.org/?probe=a213ec0ba4) | Feb 22, 2023 |
| Apple         | MacBookPro8,1               | [b7071da133](https://linux-hardware.org/?probe=b7071da133) | Feb 22, 2023 |
| Dell          | Latitude 5491               | [fd68ba9595](https://linux-hardware.org/?probe=fd68ba9595) | Feb 21, 2023 |
| Fujitsu       | LIFEBOOK E744               | [bdcee122d3](https://linux-hardware.org/?probe=bdcee122d3) | Feb 21, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [88be67bbc1](https://linux-hardware.org/?probe=88be67bbc1) | Feb 21, 2023 |
| Lenovo        | ThinkPad R61 8933W4S        | [fec1a43d91](https://linux-hardware.org/?probe=fec1a43d91) | Feb 21, 2023 |
| Dell          | System XPS L502X            | [7352f47bb0](https://linux-hardware.org/?probe=7352f47bb0) | Feb 20, 2023 |
| Lenovo        | ThinkPad T410s 2924W3S      | [24081de7f1](https://linux-hardware.org/?probe=24081de7f1) | Feb 20, 2023 |
| HP            | 620                         | [c3dae62545](https://linux-hardware.org/?probe=c3dae62545) | Feb 20, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [e61bce94ea](https://linux-hardware.org/?probe=e61bce94ea) | Feb 20, 2023 |
| Acer          | Aspire A515-44              | [5fc82de1e4](https://linux-hardware.org/?probe=5fc82de1e4) | Feb 20, 2023 |
| Fujitsu       | LIFEBOOK E559               | [5e4c3607c7](https://linux-hardware.org/?probe=5e4c3607c7) | Feb 20, 2023 |
| Dell          | Latitude 3190               | [c05229588b](https://linux-hardware.org/?probe=c05229588b) | Feb 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [0d1a7d0dbe](https://linux-hardware.org/?probe=0d1a7d0dbe) | Feb 20, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | [3ddfaa902f](https://linux-hardware.org/?probe=3ddfaa902f) | Feb 20, 2023 |
| Acer          | Aspire A515-44              | [14e85e829f](https://linux-hardware.org/?probe=14e85e829f) | Feb 20, 2023 |
| Dell          | Latitude E7270              | [4eb17c846c](https://linux-hardware.org/?probe=4eb17c846c) | Feb 20, 2023 |
| Lenovo        | G510 20238                  | [7bc24845b3](https://linux-hardware.org/?probe=7bc24845b3) | Feb 20, 2023 |
| Lenovo        | G510 20238                  | [d6f20de9d5](https://linux-hardware.org/?probe=d6f20de9d5) | Feb 19, 2023 |
| Dell          | Vostro 5502                 | [49252b4695](https://linux-hardware.org/?probe=49252b4695) | Feb 19, 2023 |
| HP            | Unknown                     | [69b276cb01](https://linux-hardware.org/?probe=69b276cb01) | Feb 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [5300c136fd](https://linux-hardware.org/?probe=5300c136fd) | Feb 19, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [5ff3cab69f](https://linux-hardware.org/?probe=5ff3cab69f) | Feb 19, 2023 |
| Apple         | MacBookAir6,1               | [5cade7cfc3](https://linux-hardware.org/?probe=5cade7cfc3) | Feb 19, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [238f636180](https://linux-hardware.org/?probe=238f636180) | Feb 18, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [9b53b2b842](https://linux-hardware.org/?probe=9b53b2b842) | Feb 18, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [cdfcc639d3](https://linux-hardware.org/?probe=cdfcc639d3) | Feb 18, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [cbf0e3814c](https://linux-hardware.org/?probe=cbf0e3814c) | Feb 18, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [a424b3aa47](https://linux-hardware.org/?probe=a424b3aa47) | Feb 18, 2023 |
| Dell          | Latitude 3520               | [8df8f4c6fc](https://linux-hardware.org/?probe=8df8f4c6fc) | Feb 18, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [27958da7cc](https://linux-hardware.org/?probe=27958da7cc) | Feb 18, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [2f3a14eeaa](https://linux-hardware.org/?probe=2f3a14eeaa) | Feb 18, 2023 |
| MSI           | GL65 9SD                    | [a702514760](https://linux-hardware.org/?probe=a702514760) | Feb 17, 2023 |
| Dell          | Inspiron 5570               | [be29883368](https://linux-hardware.org/?probe=be29883368) | Feb 17, 2023 |
| Dell          | Latitude 5491               | [8a3298cdff](https://linux-hardware.org/?probe=8a3298cdff) | Feb 17, 2023 |
| Dell          | Latitude 5511               | [5c3a80271b](https://linux-hardware.org/?probe=5c3a80271b) | Feb 17, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [4a5c7432ae](https://linux-hardware.org/?probe=4a5c7432ae) | Feb 17, 2023 |
| HP            | ZBook Studio G3             | [af86e6cb72](https://linux-hardware.org/?probe=af86e6cb72) | Feb 17, 2023 |
| Lenovo        | ThinkPad T61 7661BM5        | [c829d5ed74](https://linux-hardware.org/?probe=c829d5ed74) | Feb 16, 2023 |
| Apple         | MacBookAir6,1               | [c96e404e3f](https://linux-hardware.org/?probe=c96e404e3f) | Feb 16, 2023 |
| Lenovo        | ThinkPad L13 20R30006PB     | [aad1f06bb9](https://linux-hardware.org/?probe=aad1f06bb9) | Feb 16, 2023 |
| MSI           | Creator Z17 A12UHST         | [a70040c510](https://linux-hardware.org/?probe=a70040c510) | Feb 16, 2023 |
| RTD Embedd... | CMA34CR                     | [dd8527bd65](https://linux-hardware.org/?probe=dd8527bd65) | Feb 16, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [73787e9141](https://linux-hardware.org/?probe=73787e9141) | Feb 16, 2023 |
| Dell          | Latitude 5480               | [ee1b786fd9](https://linux-hardware.org/?probe=ee1b786fd9) | Feb 15, 2023 |
| Lenovo        | Y50-70 20378                | [09301690c5](https://linux-hardware.org/?probe=09301690c5) | Feb 15, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [74a61dff13](https://linux-hardware.org/?probe=74a61dff13) | Feb 15, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [b53cdde5a7](https://linux-hardware.org/?probe=b53cdde5a7) | Feb 15, 2023 |
| HP            | EliteBook 650 15.6 inch ... | [2be1a08ef2](https://linux-hardware.org/?probe=2be1a08ef2) | Feb 15, 2023 |
| GPU Compan... | GWTN141-4                   | [1492f5c475](https://linux-hardware.org/?probe=1492f5c475) | Feb 15, 2023 |
| Dell          | System XPS L502X            | [2ea016be2a](https://linux-hardware.org/?probe=2ea016be2a) | Feb 14, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [65a5587c6d](https://linux-hardware.org/?probe=65a5587c6d) | Feb 14, 2023 |
| Acer          | Aspire A315-35              | [971fa91888](https://linux-hardware.org/?probe=971fa91888) | Feb 14, 2023 |
| Google        | Lillipup                    | [af7451beff](https://linux-hardware.org/?probe=af7451beff) | Feb 14, 2023 |
| Unknown       | Unknown                     | [1f80b65b37](https://linux-hardware.org/?probe=1f80b65b37) | Feb 13, 2023 |
| Unknown       | Unknown                     | [8b28eb095c](https://linux-hardware.org/?probe=8b28eb095c) | Feb 13, 2023 |
| Medion        | Akoya THE TOUCH 10          | [ec6afad108](https://linux-hardware.org/?probe=ec6afad108) | Feb 13, 2023 |
| Timi          | TM1613                      | [ce33c5c02e](https://linux-hardware.org/?probe=ce33c5c02e) | Feb 13, 2023 |
| Lenovo        | IdeaPad S210 Touch 20257    | [d132553080](https://linux-hardware.org/?probe=d132553080) | Feb 13, 2023 |
| Dell          | Latitude 5511               | [161095d97a](https://linux-hardware.org/?probe=161095d97a) | Feb 13, 2023 |
| TrekStor      | Surfbook W2                 | [f43f606f80](https://linux-hardware.org/?probe=f43f606f80) | Feb 13, 2023 |
| Dell          | Latitude 3190               | [f2fd97186c](https://linux-hardware.org/?probe=f2fd97186c) | Feb 13, 2023 |
| Dell          | Latitude E6420              | [6ffa1ea310](https://linux-hardware.org/?probe=6ffa1ea310) | Feb 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [04cfa15383](https://linux-hardware.org/?probe=04cfa15383) | Feb 12, 2023 |
| Lenovo        | ThinkPad T470s 20HGS1LM0... | [8ee6dd00d1](https://linux-hardware.org/?probe=8ee6dd00d1) | Feb 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [40116058d1](https://linux-hardware.org/?probe=40116058d1) | Feb 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [8e00bdf032](https://linux-hardware.org/?probe=8e00bdf032) | Feb 11, 2023 |
| Apple         | MacBookAir5,2               | [4f99163f99](https://linux-hardware.org/?probe=4f99163f99) | Feb 11, 2023 |
| Lenovo        | ThinkPad T430 2347BS4       | [682be07637](https://linux-hardware.org/?probe=682be07637) | Feb 11, 2023 |
| Valve         | Jupiter                     | [081d9e5294](https://linux-hardware.org/?probe=081d9e5294) | Feb 11, 2023 |
| HP            | ProBook 430 G3              | [e995a466a1](https://linux-hardware.org/?probe=e995a466a1) | Feb 10, 2023 |
| Toshiba       | Satellite L750              | [b6239c152e](https://linux-hardware.org/?probe=b6239c152e) | Feb 10, 2023 |
| Acer          | Aspire ES1-111M             | [82eea49fcd](https://linux-hardware.org/?probe=82eea49fcd) | Feb 09, 2023 |
| Acer          | Aspire ES1-111M             | [accbac47d5](https://linux-hardware.org/?probe=accbac47d5) | Feb 09, 2023 |
| Lenovo        | ThinkPad T530 2429MY2       | [9b5ffc7c58](https://linux-hardware.org/?probe=9b5ffc7c58) | Feb 09, 2023 |
| MSI           | Creator Z17 A12UHST         | [8885828bb8](https://linux-hardware.org/?probe=8885828bb8) | Feb 09, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [467c3e9149](https://linux-hardware.org/?probe=467c3e9149) | Feb 09, 2023 |
| Valve         | Jupiter                     | [26cb195bab](https://linux-hardware.org/?probe=26cb195bab) | Feb 08, 2023 |
| Dell          | Latitude 3570               | [dc460632ef](https://linux-hardware.org/?probe=dc460632ef) | Feb 08, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [842956e023](https://linux-hardware.org/?probe=842956e023) | Feb 08, 2023 |
| Dell          | Latitude E6520              | [c9c89084e8](https://linux-hardware.org/?probe=c9c89084e8) | Feb 07, 2023 |
| Dell          | Latitude E4300              | [aaad0477e4](https://linux-hardware.org/?probe=aaad0477e4) | Feb 07, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [307d491fc8](https://linux-hardware.org/?probe=307d491fc8) | Feb 07, 2023 |
| Dell          | Latitude 3520               | [d7569fa081](https://linux-hardware.org/?probe=d7569fa081) | Feb 06, 2023 |
| Valve         | Jupiter                     | [edc8beac1f](https://linux-hardware.org/?probe=edc8beac1f) | Feb 06, 2023 |
| Dell          | Latitude 5511               | [57e8ce4f20](https://linux-hardware.org/?probe=57e8ce4f20) | Feb 06, 2023 |
| Dell          | Latitude 3190               | [eafbc050e8](https://linux-hardware.org/?probe=eafbc050e8) | Feb 06, 2023 |
| HP            | EliteBook 820 G2            | [e8c0f3b7de](https://linux-hardware.org/?probe=e8c0f3b7de) | Feb 05, 2023 |
| HP            | EliteBook 820 G2            | [eb5a23a73b](https://linux-hardware.org/?probe=eb5a23a73b) | Feb 05, 2023 |
| Lenovo        | IdeaPad Y580                | [30d8845f10](https://linux-hardware.org/?probe=30d8845f10) | Feb 05, 2023 |
| Lenovo        | ThinkPad T15 Gen 1 20S6C... | [262dfe3aa9](https://linux-hardware.org/?probe=262dfe3aa9) | Feb 05, 2023 |
| Lenovo        | ThinkBook 14s-IWL 20RM      | [dbef2c679a](https://linux-hardware.org/?probe=dbef2c679a) | Feb 05, 2023 |
| Dell          | Inspiron 5570               | [eb399b4ffa](https://linux-hardware.org/?probe=eb399b4ffa) | Feb 05, 2023 |
| Lenovo        | ThinkBook 14s-IWL 20RM      | [14fb68ece0](https://linux-hardware.org/?probe=14fb68ece0) | Feb 05, 2023 |
| Apple         | MacBookPro8,1               | [d6adca1255](https://linux-hardware.org/?probe=d6adca1255) | Feb 04, 2023 |
| Dell          | Inspiron 5570               | [6e8ab1a5cb](https://linux-hardware.org/?probe=6e8ab1a5cb) | Feb 04, 2023 |
| Apple         | MacBookPro8,3               | [9d397c2187](https://linux-hardware.org/?probe=9d397c2187) | Feb 04, 2023 |
| Apple         | MacBookPro8,3               | [7b676dec23](https://linux-hardware.org/?probe=7b676dec23) | Feb 04, 2023 |
| Acer          | Aspire A515-51G             | [149465f225](https://linux-hardware.org/?probe=149465f225) | Feb 04, 2023 |
| Dell          | Vostro 3550                 | [4f1125bc93](https://linux-hardware.org/?probe=4f1125bc93) | Feb 04, 2023 |
| Lenovo        | G510 20238                  | [a385ff6f36](https://linux-hardware.org/?probe=a385ff6f36) | Feb 04, 2023 |
| Lenovo        | ThinkPad R500 2716W2K       | [a645368e82](https://linux-hardware.org/?probe=a645368e82) | Feb 04, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [c6dae92093](https://linux-hardware.org/?probe=c6dae92093) | Feb 03, 2023 |
| ASUSTek       | 1101HA                      | [28cb433eb0](https://linux-hardware.org/?probe=28cb433eb0) | Feb 03, 2023 |
| Dell          | Latitude 5480               | [da9f98059c](https://linux-hardware.org/?probe=da9f98059c) | Feb 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [9c5cfbc1a1](https://linux-hardware.org/?probe=9c5cfbc1a1) | Feb 03, 2023 |
| HP            | Unknown                     | [4b28efe30c](https://linux-hardware.org/?probe=4b28efe30c) | Feb 03, 2023 |
| Samsung       | 530U3C/530U4C/532U3C        | [4b1dc3d64b](https://linux-hardware.org/?probe=4b1dc3d64b) | Feb 02, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [1c6ed7ede6](https://linux-hardware.org/?probe=1c6ed7ede6) | Feb 02, 2023 |
| Dell          | Vostro 3580                 | [7efc294bac](https://linux-hardware.org/?probe=7efc294bac) | Feb 02, 2023 |
| MSI           | GV62 7RD                    | [c22fffb4e9](https://linux-hardware.org/?probe=c22fffb4e9) | Feb 02, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [ac6a930ffc](https://linux-hardware.org/?probe=ac6a930ffc) | Feb 02, 2023 |
| Dell          | Precision 7540              | [1d0d197808](https://linux-hardware.org/?probe=1d0d197808) | Feb 01, 2023 |
| Dell          | Latitude E7240              | [fe655eca77](https://linux-hardware.org/?probe=fe655eca77) | Jan 31, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [62f941075c](https://linux-hardware.org/?probe=62f941075c) | Jan 31, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [70310e25d1](https://linux-hardware.org/?probe=70310e25d1) | Jan 31, 2023 |
| Dell          | Latitude 5410               | [717012530d](https://linux-hardware.org/?probe=717012530d) | Jan 31, 2023 |
| Unknown       | Unknown                     | [e6c824b966](https://linux-hardware.org/?probe=e6c824b966) | Jan 31, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [aaaa563786](https://linux-hardware.org/?probe=aaaa563786) | Jan 31, 2023 |
| HP            | Compaq 6730s                | [1b083e5b64](https://linux-hardware.org/?probe=1b083e5b64) | Jan 31, 2023 |
| HP            | Compaq 6730s                | [ced2899d20](https://linux-hardware.org/?probe=ced2899d20) | Jan 31, 2023 |
| HP            | ProBook 650 G1              | [fc09442b7c](https://linux-hardware.org/?probe=fc09442b7c) | Jan 30, 2023 |
| HP            | ProBook 650 G1              | [b78602c91d](https://linux-hardware.org/?probe=b78602c91d) | Jan 30, 2023 |
| Dell          | Latitude E5430 non-vPro     | [d1e99e3f04](https://linux-hardware.org/?probe=d1e99e3f04) | Jan 30, 2023 |
| Toshiba       | Satellite P750              | [1cc0f342b5](https://linux-hardware.org/?probe=1cc0f342b5) | Jan 30, 2023 |
| Apple         | MacBookPro5,2               | [4cb11c2a78](https://linux-hardware.org/?probe=4cb11c2a78) | Jan 30, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603ZX... | [7442c84b55](https://linux-hardware.org/?probe=7442c84b55) | Jan 30, 2023 |
| Dell          | Inspiron 5758               | [de58233dca](https://linux-hardware.org/?probe=de58233dca) | Jan 30, 2023 |
| HP            | ZBook 15u G3                | [7f985597d7](https://linux-hardware.org/?probe=7f985597d7) | Jan 30, 2023 |
| HP            | ZBook 15u G3                | [7a35a6d886](https://linux-hardware.org/?probe=7a35a6d886) | Jan 30, 2023 |
| Dell          | Latitude 5480               | [ee87ac218f](https://linux-hardware.org/?probe=ee87ac218f) | Jan 30, 2023 |
| Dell          | Latitude 5480               | [3cbac640e1](https://linux-hardware.org/?probe=3cbac640e1) | Jan 30, 2023 |
| Dell          | Latitude 3190               | [a53530646a](https://linux-hardware.org/?probe=a53530646a) | Jan 30, 2023 |
| Dell          | Latitude E6520              | [81717ed3df](https://linux-hardware.org/?probe=81717ed3df) | Jan 30, 2023 |
| Apple         | MacBookPro11,1              | [e5af375b93](https://linux-hardware.org/?probe=e5af375b93) | Jan 29, 2023 |
| Apple         | MacBookPro11,1              | [41d67fcba8](https://linux-hardware.org/?probe=41d67fcba8) | Jan 29, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [e2fa9aa820](https://linux-hardware.org/?probe=e2fa9aa820) | Jan 29, 2023 |
| ASUSTek       | 1215B                       | [8d26a8d157](https://linux-hardware.org/?probe=8d26a8d157) | Jan 28, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [fb7b1bdaf5](https://linux-hardware.org/?probe=fb7b1bdaf5) | Jan 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [f6d7ba9d48](https://linux-hardware.org/?probe=f6d7ba9d48) | Jan 27, 2023 |
| HP            | EliteBook 640 14 inch G9... | [bbdf827cef](https://linux-hardware.org/?probe=bbdf827cef) | Jan 27, 2023 |
| ASUSTek       | X540SA                      | [93aed28230](https://linux-hardware.org/?probe=93aed28230) | Jan 27, 2023 |
| Kruger&Mat... | KM1406                      | [c944e8058f](https://linux-hardware.org/?probe=c944e8058f) | Jan 27, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [bd7e955a3e](https://linux-hardware.org/?probe=bd7e955a3e) | Jan 27, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [1f74ea5c27](https://linux-hardware.org/?probe=1f74ea5c27) | Jan 27, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [af3748a4f0](https://linux-hardware.org/?probe=af3748a4f0) | Jan 26, 2023 |
| Acer          | Nitro AN517-55              | [7273b8320c](https://linux-hardware.org/?probe=7273b8320c) | Jan 26, 2023 |
| Lenovo        | ThinkPad T440p 20AWS24B0... | [e4ddea6092](https://linux-hardware.org/?probe=e4ddea6092) | Jan 26, 2023 |
| Acer          | Nitro AN517-55              | [2de4e60fef](https://linux-hardware.org/?probe=2de4e60fef) | Jan 26, 2023 |
| HP            | EliteBook Folio 1040 G1     | [4811286faf](https://linux-hardware.org/?probe=4811286faf) | Jan 26, 2023 |
| Dell          | XPS 9320                    | [a1040b4a3f](https://linux-hardware.org/?probe=a1040b4a3f) | Jan 26, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [26f46d5b40](https://linux-hardware.org/?probe=26f46d5b40) | Jan 25, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [f1e6112f8c](https://linux-hardware.org/?probe=f1e6112f8c) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [baae797a05](https://linux-hardware.org/?probe=baae797a05) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [427a7fa0cb](https://linux-hardware.org/?probe=427a7fa0cb) | Jan 25, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [7fcc3fb992](https://linux-hardware.org/?probe=7fcc3fb992) | Jan 25, 2023 |
| Samsung       | R710                        | [17a3e2ddd9](https://linux-hardware.org/?probe=17a3e2ddd9) | Jan 25, 2023 |
| Dell          | Latitude E6520              | [baf618d1a1](https://linux-hardware.org/?probe=baf618d1a1) | Jan 25, 2023 |
| Dell          | Latitude E6520              | [615879d5e9](https://linux-hardware.org/?probe=615879d5e9) | Jan 24, 2023 |
| Dell          | Latitude 5420               | [cd6dc3695e](https://linux-hardware.org/?probe=cd6dc3695e) | Jan 24, 2023 |
| Lenovo        | ThinkPad T500 2082BPG       | [08a30fd24c](https://linux-hardware.org/?probe=08a30fd24c) | Jan 24, 2023 |
| Dell          | Latitude E5530 non-vPro     | [5ddcb9f78b](https://linux-hardware.org/?probe=5ddcb9f78b) | Jan 23, 2023 |
| Samsung       | 300E4A/300E5A/300E7A        | [c8ec385a88](https://linux-hardware.org/?probe=c8ec385a88) | Jan 23, 2023 |
| Dell          | Latitude 3190               | [7d38c480af](https://linux-hardware.org/?probe=7d38c480af) | Jan 23, 2023 |
| Dell          | Latitude E6500              | [ba7c36fe15](https://linux-hardware.org/?probe=ba7c36fe15) | Jan 23, 2023 |
| Lenovo        | ThinkPad R500 2716W2K       | [ffe1ffc80e](https://linux-hardware.org/?probe=ffe1ffc80e) | Jan 23, 2023 |
| HP            | OMEN by Laptop 17-ck0xxx    | [d3686f2fc3](https://linux-hardware.org/?probe=d3686f2fc3) | Jan 21, 2023 |
| Dell          | Latitude 9420               | [4b847961df](https://linux-hardware.org/?probe=4b847961df) | Jan 21, 2023 |
| Dell          | Latitude 5501               | [72581be7e7](https://linux-hardware.org/?probe=72581be7e7) | Jan 21, 2023 |
| Lenovo        | G560 20042                  | [9c78155cfe](https://linux-hardware.org/?probe=9c78155cfe) | Jan 20, 2023 |
| Lenovo        | G560 20042                  | [61e3ee0517](https://linux-hardware.org/?probe=61e3ee0517) | Jan 20, 2023 |
| HP            | Pavilion dv5                | [94ba65752b](https://linux-hardware.org/?probe=94ba65752b) | Jan 20, 2023 |
| Acer          | Aspire A114-31              | [b341182acd](https://linux-hardware.org/?probe=b341182acd) | Jan 20, 2023 |
| Lenovo        | ThinkPad P51 20HJS1EJ1B     | [2ac4b56c2f](https://linux-hardware.org/?probe=2ac4b56c2f) | Jan 20, 2023 |
| ASUSTek       | ROG Strix G713RM_G713RM     | [844d97dd92](https://linux-hardware.org/?probe=844d97dd92) | Jan 20, 2023 |
| Dell          | Precision M6600             | [4d697ebfd5](https://linux-hardware.org/?probe=4d697ebfd5) | Jan 19, 2023 |
| Dell          | Inspiron 5567               | [a993e95dde](https://linux-hardware.org/?probe=a993e95dde) | Jan 19, 2023 |
| MSI           | Creator Z17 A12UHST         | [1fd7f0acb7](https://linux-hardware.org/?probe=1fd7f0acb7) | Jan 19, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [16f5041f1d](https://linux-hardware.org/?probe=16f5041f1d) | Jan 19, 2023 |
| Lenovo        | Z51-70 80K6                 | [90746298fc](https://linux-hardware.org/?probe=90746298fc) | Jan 19, 2023 |
| Acer          | Aspire A114-31              | [30698dacda](https://linux-hardware.org/?probe=30698dacda) | Jan 19, 2023 |
| Dell          | Latitude 9420               | [3fd325486b](https://linux-hardware.org/?probe=3fd325486b) | Jan 18, 2023 |
| Alienware     | M17xR4                      | [5cce1e5932](https://linux-hardware.org/?probe=5cce1e5932) | Jan 18, 2023 |
| Dell          | Precision 5750              | [592f9624d3](https://linux-hardware.org/?probe=592f9624d3) | Jan 18, 2023 |
| MSI           | GP65 Leopard 10SFK          | [3c09479564](https://linux-hardware.org/?probe=3c09479564) | Jan 18, 2023 |
| Lenovo        | ThinkPad E560 20EV000UUK    | [2ad3913a19](https://linux-hardware.org/?probe=2ad3913a19) | Jan 18, 2023 |
| Lenovo        | ThinkPad E560 20EV000UUK    | [6f463ee96b](https://linux-hardware.org/?probe=6f463ee96b) | Jan 18, 2023 |
| Dell          | Latitude D630               | [0d267a0217](https://linux-hardware.org/?probe=0d267a0217) | Jan 17, 2023 |
| HP            | Pavilion Gaming Notebook    | [03a01ae5f7](https://linux-hardware.org/?probe=03a01ae5f7) | Jan 17, 2023 |
| Lenovo        | ThinkPad E480 20KN0064PB    | [a49c7ed379](https://linux-hardware.org/?probe=a49c7ed379) | Jan 17, 2023 |
| Lenovo        | ThinkPad E480 20KN0064PB    | [9d20f03ffd](https://linux-hardware.org/?probe=9d20f03ffd) | Jan 17, 2023 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [aa6ca0d358](https://linux-hardware.org/?probe=aa6ca0d358) | Jan 17, 2023 |
| ASUSTek       | K53SJ                       | [267ce15a0c](https://linux-hardware.org/?probe=267ce15a0c) | Jan 17, 2023 |
| ASUSTek       | Zenbook UM6702RC_RM6702R... | [21ed6bd75d](https://linux-hardware.org/?probe=21ed6bd75d) | Jan 17, 2023 |
| Dell          | Inspiron 3583               | [79b74ef79b](https://linux-hardware.org/?probe=79b74ef79b) | Jan 16, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [11ca9b863c](https://linux-hardware.org/?probe=11ca9b863c) | Jan 16, 2023 |
| Dell          | Inspiron 11 - 3147          | [af542a44ad](https://linux-hardware.org/?probe=af542a44ad) | Jan 16, 2023 |
| Dell          | Latitude 3190               | [96d1e3a219](https://linux-hardware.org/?probe=96d1e3a219) | Jan 16, 2023 |
| Lenovo        | ThinkPad T460s 20FAS5QW0... | [dd953776aa](https://linux-hardware.org/?probe=dd953776aa) | Jan 16, 2023 |
| Lenovo        | ThinkPad T510 4384FF3       | [b62dac21bd](https://linux-hardware.org/?probe=b62dac21bd) | Jan 15, 2023 |
| Chuwi         | AeroBook Pro                | [13da35b0f7](https://linux-hardware.org/?probe=13da35b0f7) | Jan 15, 2023 |
| ASUSTek       | X510UQR                     | [2fb1d0a04c](https://linux-hardware.org/?probe=2fb1d0a04c) | Jan 14, 2023 |
| Acer          | AO725                       | [739986d5fa](https://linux-hardware.org/?probe=739986d5fa) | Jan 14, 2023 |
| Lenovo        | G585                        | [c7453a5e19](https://linux-hardware.org/?probe=c7453a5e19) | Jan 14, 2023 |
| MSI           | GE70 2QD                    | [5e408d7d3d](https://linux-hardware.org/?probe=5e408d7d3d) | Jan 14, 2023 |
| Dell          | Vostro 3550                 | [3f68ef3681](https://linux-hardware.org/?probe=3f68ef3681) | Jan 13, 2023 |
| HP            | EliteBook 8570w             | [84035db95c](https://linux-hardware.org/?probe=84035db95c) | Jan 13, 2023 |
| Samsung       | SR700                       | [329a7864c0](https://linux-hardware.org/?probe=329a7864c0) | Jan 13, 2023 |
| HP            | Notebook                    | [3fc38fa55e](https://linux-hardware.org/?probe=3fc38fa55e) | Jan 13, 2023 |
| Kiano         | Elegance 13.3               | [2e77ce51b9](https://linux-hardware.org/?probe=2e77ce51b9) | Jan 13, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [05899ebb86](https://linux-hardware.org/?probe=05899ebb86) | Jan 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [4236e82f21](https://linux-hardware.org/?probe=4236e82f21) | Jan 13, 2023 |
| HP            | ProBook 450 G6              | [f675188c46](https://linux-hardware.org/?probe=f675188c46) | Jan 12, 2023 |
| MSI           | GE70 2QD                    | [8dce1e9fdd](https://linux-hardware.org/?probe=8dce1e9fdd) | Jan 12, 2023 |
| Lenovo        | Legion Y740S-15IMH 81YX     | [b61eb04be5](https://linux-hardware.org/?probe=b61eb04be5) | Jan 11, 2023 |
| Sony          | VPCEJ2S1E                   | [f387a3dcf6](https://linux-hardware.org/?probe=f387a3dcf6) | Jan 11, 2023 |
| MSI           | GL75 9SE                    | [e3478b20bd](https://linux-hardware.org/?probe=e3478b20bd) | Jan 11, 2023 |
| ASUSTek       | 1215N                       | [140d48870a](https://linux-hardware.org/?probe=140d48870a) | Jan 11, 2023 |
| ASUSTek       | 1215N                       | [f6588e6319](https://linux-hardware.org/?probe=f6588e6319) | Jan 11, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b828defe64](https://linux-hardware.org/?probe=b828defe64) | Jan 11, 2023 |
| Dell          | Latitude D630               | [64877fdf78](https://linux-hardware.org/?probe=64877fdf78) | Jan 11, 2023 |
| ASUSTek       | X550CC                      | [2aa757ef35](https://linux-hardware.org/?probe=2aa757ef35) | Jan 10, 2023 |
| Samsung       | 550P5C/550P7C               | [33529c6c45](https://linux-hardware.org/?probe=33529c6c45) | Jan 10, 2023 |
| Acer          | Extensa 2540                | [6bddd00c3f](https://linux-hardware.org/?probe=6bddd00c3f) | Jan 10, 2023 |
| Dell          | Latitude E4310              | [1cd2d3300a](https://linux-hardware.org/?probe=1cd2d3300a) | Jan 09, 2023 |
| Dell          | Latitude E5470              | [41c1a02ca6](https://linux-hardware.org/?probe=41c1a02ca6) | Jan 09, 2023 |
| Chuwi         | GemiBook                    | [918dc5f283](https://linux-hardware.org/?probe=918dc5f283) | Jan 09, 2023 |
| Lenovo        | ThinkPad X201 3626D15       | [3d615a1b12](https://linux-hardware.org/?probe=3d615a1b12) | Jan 09, 2023 |
| Dell          | Latitude 3190               | [055e045e52](https://linux-hardware.org/?probe=055e045e52) | Jan 09, 2023 |
| MSI           | GT680R/GX680R/GT683R/GT6... | [0b23cb61e0](https://linux-hardware.org/?probe=0b23cb61e0) | Jan 09, 2023 |
| Samsung       | R780/R778                   | [e26d6dd084](https://linux-hardware.org/?probe=e26d6dd084) | Jan 08, 2023 |
| Acer          | Aspire one 1-131            | [06c3411258](https://linux-hardware.org/?probe=06c3411258) | Jan 08, 2023 |
| Lenovo        | G51-35 80M8                 | [fe19098e1d](https://linux-hardware.org/?probe=fe19098e1d) | Jan 08, 2023 |
| Acer          | Aspire A315-41              | [b4ed141fd3](https://linux-hardware.org/?probe=b4ed141fd3) | Jan 08, 2023 |
| Lenovo        | ThinkPad T460 20FMS0BX0T    | [e05bd2254f](https://linux-hardware.org/?probe=e05bd2254f) | Jan 08, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [de3c61df29](https://linux-hardware.org/?probe=de3c61df29) | Jan 08, 2023 |
| HP            | 655                         | [4c7544d7ad](https://linux-hardware.org/?probe=4c7544d7ad) | Jan 08, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | [1ad8a2f766](https://linux-hardware.org/?probe=1ad8a2f766) | Jan 08, 2023 |
| HP            | ENVY m6                     | [b5089c7b29](https://linux-hardware.org/?probe=b5089c7b29) | Jan 07, 2023 |
| HP            | ProBook 5330m               | [37416931cd](https://linux-hardware.org/?probe=37416931cd) | Jan 07, 2023 |
| Lenovo        | S145-15API 81UT             | [fafc9e3fb7](https://linux-hardware.org/?probe=fafc9e3fb7) | Jan 07, 2023 |
| Apple         | MacBookPro9,2               | [e0e6ab58b6](https://linux-hardware.org/?probe=e0e6ab58b6) | Jan 06, 2023 |
| Dell          | Latitude E6520              | [96679022de](https://linux-hardware.org/?probe=96679022de) | Jan 06, 2023 |
| MSI           | Creator Z17 A12UHST         | [d0299b2518](https://linux-hardware.org/?probe=d0299b2518) | Jan 06, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [c84d3b6b03](https://linux-hardware.org/?probe=c84d3b6b03) | Jan 06, 2023 |
| Lenovo        | Legion 5 17ACH6 82K0        | [9a108faf93](https://linux-hardware.org/?probe=9a108faf93) | Jan 06, 2023 |
| MSI           | GP76 Leopard 10UE           | [117e9ffed7](https://linux-hardware.org/?probe=117e9ffed7) | Jan 06, 2023 |
| MSI           | GP76 Leopard 10UE           | [cacdaaf5c5](https://linux-hardware.org/?probe=cacdaaf5c5) | Jan 05, 2023 |
| Acer          | NG-A715-72G-70F7            | [bbedda14e5](https://linux-hardware.org/?probe=bbedda14e5) | Jan 05, 2023 |
| Acer          | NG-A715-72G-70F7            | [d2c2a681a2](https://linux-hardware.org/?probe=d2c2a681a2) | Jan 05, 2023 |
| Acer          | Aspire A715-74G             | [e0cf0ea368](https://linux-hardware.org/?probe=e0cf0ea368) | Jan 05, 2023 |
| Lenovo        | ThinkPad T460s 20FAS5QW0... | [4853686d6c](https://linux-hardware.org/?probe=4853686d6c) | Jan 05, 2023 |
| ASUSTek       | K55VM                       | [d4d53ed49f](https://linux-hardware.org/?probe=d4d53ed49f) | Jan 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [307c51149d](https://linux-hardware.org/?probe=307c51149d) | Jan 03, 2023 |
| Acer          | Nitro AN515-55              | [c5bc3a8eae](https://linux-hardware.org/?probe=c5bc3a8eae) | Jan 03, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [1a3964dd30](https://linux-hardware.org/?probe=1a3964dd30) | Jan 03, 2023 |
| Dell          | XPS 13 7390                 | [b45f76c172](https://linux-hardware.org/?probe=b45f76c172) | Jan 03, 2023 |
| Lenovo        | ThinkPad T460s 20FAS5QW0... | [373efc41b0](https://linux-hardware.org/?probe=373efc41b0) | Jan 03, 2023 |
| Fujitsu       | LIFEBOOK S751               | [5fbed33610](https://linux-hardware.org/?probe=5fbed33610) | Jan 03, 2023 |
| Lenovo        | IdeaPad S540-14IWL 81ND     | [99ba91623a](https://linux-hardware.org/?probe=99ba91623a) | Jan 02, 2023 |
| Acer          | Aspire E1-571               | [eb3f1a0f5f](https://linux-hardware.org/?probe=eb3f1a0f5f) | Jan 02, 2023 |
| Dell          | Latitude 3190               | [19f42109a3](https://linux-hardware.org/?probe=19f42109a3) | Jan 02, 2023 |
| MSI           | PE60 6QE                    | [c331237e28](https://linux-hardware.org/?probe=c331237e28) | Jan 02, 2023 |
| MSI           | PE60 6QE                    | [1ce680cb4d](https://linux-hardware.org/?probe=1ce680cb4d) | Jan 01, 2023 |
| Gigabyte      | RC14UD                      | [24d32a2b05](https://linux-hardware.org/?probe=24d32a2b05) | Jan 01, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | [48c688033a](https://linux-hardware.org/?probe=48c688033a) | Dec 30, 2022 |
| ASUSTek       | K72F                        | [f761bf9bd6](https://linux-hardware.org/?probe=f761bf9bd6) | Dec 30, 2022 |
| Lenovo        | ThinkPad R61 8918DEG        | [82cbc15539](https://linux-hardware.org/?probe=82cbc15539) | Dec 30, 2022 |
| HP            | EliteBook 745 G5            | [d819dbd901](https://linux-hardware.org/?probe=d819dbd901) | Dec 30, 2022 |
| HP            | ProBook 450 G7              | [ca7468f975](https://linux-hardware.org/?probe=ca7468f975) | Dec 29, 2022 |
| Dell          | Latitude E6420              | [9733c425b6](https://linux-hardware.org/?probe=9733c425b6) | Dec 29, 2022 |
| Lenovo        | Y50-70 20378                | [fe7926d39a](https://linux-hardware.org/?probe=fe7926d39a) | Dec 28, 2022 |
| Dell          | Inspiron 3583               | [41c7a16579](https://linux-hardware.org/?probe=41c7a16579) | Dec 28, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [27e072cb3e](https://linux-hardware.org/?probe=27e072cb3e) | Dec 28, 2022 |
| Lenovo        | Y50-70 20378                | [e232c2de6d](https://linux-hardware.org/?probe=e232c2de6d) | Dec 28, 2022 |
| HP            | EliteBook 745 G3            | [1ca2f43148](https://linux-hardware.org/?probe=1ca2f43148) | Dec 27, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [03cca95360](https://linux-hardware.org/?probe=03cca95360) | Dec 27, 2022 |
| HP            | EliteBook 820 G3            | [95555948a2](https://linux-hardware.org/?probe=95555948a2) | Dec 27, 2022 |
| Acer          | Nitro AN515-44              | [58b02cceb0](https://linux-hardware.org/?probe=58b02cceb0) | Dec 27, 2022 |
| Dell          | Latitude 3190               | [f395b56cec](https://linux-hardware.org/?probe=f395b56cec) | Dec 26, 2022 |
| ASUSTek       | X550LD                      | [e0a09344e0](https://linux-hardware.org/?probe=e0a09344e0) | Dec 26, 2022 |
| ASUSTek       | X550LD                      | [d6948e7207](https://linux-hardware.org/?probe=d6948e7207) | Dec 26, 2022 |
| Acer          | Nitro AN515-31              | [249f50d430](https://linux-hardware.org/?probe=249f50d430) | Dec 25, 2022 |
| Lenovo        | ThinkPad T430 23472Y0       | [4a2d13391c](https://linux-hardware.org/?probe=4a2d13391c) | Dec 25, 2022 |
| GPU Compan... | GWTN141-10                  | [38ed4755c3](https://linux-hardware.org/?probe=38ed4755c3) | Dec 24, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [af18889189](https://linux-hardware.org/?probe=af18889189) | Dec 23, 2022 |
| HP            | 255 G7 Notebook PC          | [5bedf1557b](https://linux-hardware.org/?probe=5bedf1557b) | Dec 23, 2022 |
| Fujitsu       | LIFEBOOK S751               | [f3dc3c0121](https://linux-hardware.org/?probe=f3dc3c0121) | Dec 22, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [bf600b6f1c](https://linux-hardware.org/?probe=bf600b6f1c) | Dec 22, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [06d78a17c1](https://linux-hardware.org/?probe=06d78a17c1) | Dec 21, 2022 |
| Dell          | Precision 3520              | [1763494294](https://linux-hardware.org/?probe=1763494294) | Dec 21, 2022 |
| Sony          | SVE1112M1EB                 | [74e100e63b](https://linux-hardware.org/?probe=74e100e63b) | Dec 21, 2022 |
| ASUSTek       | N55SF                       | [b1d6a6a73d](https://linux-hardware.org/?probe=b1d6a6a73d) | Dec 21, 2022 |
| ASUSTek       | N55SF                       | [bbec56fa90](https://linux-hardware.org/?probe=bbec56fa90) | Dec 21, 2022 |
| Dell          | G15 5510                    | [86d0642973](https://linux-hardware.org/?probe=86d0642973) | Dec 20, 2022 |
| ASUSTek       | TUF Gaming FX505GE          | [094e72dc22](https://linux-hardware.org/?probe=094e72dc22) | Dec 20, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [0d59e38c20](https://linux-hardware.org/?probe=0d59e38c20) | Dec 20, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [37513092d6](https://linux-hardware.org/?probe=37513092d6) | Dec 20, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [03e2c64868](https://linux-hardware.org/?probe=03e2c64868) | Dec 20, 2022 |
| Dell          | Vostro 15 3510              | [f2467d713d](https://linux-hardware.org/?probe=f2467d713d) | Dec 19, 2022 |
| Dell          | Latitude 3190               | [9227c8dbfb](https://linux-hardware.org/?probe=9227c8dbfb) | Dec 19, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [44a96b54b6](https://linux-hardware.org/?probe=44a96b54b6) | Dec 18, 2022 |
| Apple         | MacBookPro14,1              | [8c0c2353ab](https://linux-hardware.org/?probe=8c0c2353ab) | Dec 18, 2022 |
| Valve         | Jupiter                     | [72f897b9d3](https://linux-hardware.org/?probe=72f897b9d3) | Dec 17, 2022 |
| Toshiba       | Satellite L650              | [7ea253aa11](https://linux-hardware.org/?probe=7ea253aa11) | Dec 17, 2022 |
| Apple         | MacBookPro11,1              | [d3517edb25](https://linux-hardware.org/?probe=d3517edb25) | Dec 17, 2022 |
| Dell          | Latitude E6330              | [ca6551bf8e](https://linux-hardware.org/?probe=ca6551bf8e) | Dec 17, 2022 |
| Dell          | Latitude E5570              | [cc58177561](https://linux-hardware.org/?probe=cc58177561) | Dec 17, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | [0d7a54bc21](https://linux-hardware.org/?probe=0d7a54bc21) | Dec 16, 2022 |
| Dell          | Latitude E6410              | [173f8a8dc8](https://linux-hardware.org/?probe=173f8a8dc8) | Dec 16, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | [4f63e7b8d1](https://linux-hardware.org/?probe=4f63e7b8d1) | Dec 15, 2022 |
| Dell          | Latitude 5420               | [5fa4cbba73](https://linux-hardware.org/?probe=5fa4cbba73) | Dec 15, 2022 |
| Lenovo        | ThinkPad T530 24295XU       | [0ebd945403](https://linux-hardware.org/?probe=0ebd945403) | Dec 15, 2022 |
| Gigabyte      | MMLP3AP-00                  | [6b53aab624](https://linux-hardware.org/?probe=6b53aab624) | Dec 14, 2022 |
| Google        | Ultima                      | [867abc2b8f](https://linux-hardware.org/?probe=867abc2b8f) | Dec 14, 2022 |
| ASUSTek       | M3N                         | [4e9f8e4c01](https://linux-hardware.org/?probe=4e9f8e4c01) | Dec 14, 2022 |
| Dell          | Inspiron 3451               | [de7f9d5e33](https://linux-hardware.org/?probe=de7f9d5e33) | Dec 14, 2022 |
| Dell          | XPS L501X                   | [f540185d6c](https://linux-hardware.org/?probe=f540185d6c) | Dec 14, 2022 |
| Dell          | XPS L501X                   | [32e195f4c6](https://linux-hardware.org/?probe=32e195f4c6) | Dec 14, 2022 |
| ASUSTek       | M3N                         | [ff772de294](https://linux-hardware.org/?probe=ff772de294) | Dec 13, 2022 |
| HUAWEI        | HVY-WXX9                    | [37284f659a](https://linux-hardware.org/?probe=37284f659a) | Dec 13, 2022 |
| MSI           | Creator Z17 A12UHST         | [61685b4f1a](https://linux-hardware.org/?probe=61685b4f1a) | Dec 12, 2022 |
| Dell          | Latitude 5411               | [af806502e8](https://linux-hardware.org/?probe=af806502e8) | Dec 12, 2022 |
| Dell          | Latitude 5411               | [334ca886a4](https://linux-hardware.org/?probe=334ca886a4) | Dec 12, 2022 |
| HP            | Pavilion dv7                | [1e10e0306f](https://linux-hardware.org/?probe=1e10e0306f) | Dec 12, 2022 |
| Dell          | Latitude 3190               | [c2c5f3feb3](https://linux-hardware.org/?probe=c2c5f3feb3) | Dec 12, 2022 |
| Apple         | MacBookPro11,1              | [492b382af1](https://linux-hardware.org/?probe=492b382af1) | Dec 11, 2022 |
| HP            | EliteBook 830 G6            | [cea4c76b9d](https://linux-hardware.org/?probe=cea4c76b9d) | Dec 11, 2022 |
| Samsung       | 270E5G/270E5U               | [93075de512](https://linux-hardware.org/?probe=93075de512) | Dec 08, 2022 |
| MSI           | Vector GP76 12UGS           | [d6c55a874f](https://linux-hardware.org/?probe=d6c55a874f) | Dec 08, 2022 |
| Google        | Glimmer                     | [ad4b3f5575](https://linux-hardware.org/?probe=ad4b3f5575) | Dec 08, 2022 |
| Apple         | MacBookPro12,1              | [e15b555b1a](https://linux-hardware.org/?probe=e15b555b1a) | Dec 07, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [3a9774bdac](https://linux-hardware.org/?probe=3a9774bdac) | Dec 07, 2022 |
| Dell          | Latitude 5480               | [0cd7d6e4c0](https://linux-hardware.org/?probe=0cd7d6e4c0) | Dec 07, 2022 |
| Panasonic     | CFMX4-1                     | [c25c16fc1a](https://linux-hardware.org/?probe=c25c16fc1a) | Dec 06, 2022 |
| Dell          | Latitude E7440              | [9a859c9a5d](https://linux-hardware.org/?probe=9a859c9a5d) | Dec 06, 2022 |
| Dell          | Latitude 5310               | [06d96a49a1](https://linux-hardware.org/?probe=06d96a49a1) | Dec 06, 2022 |
| Dell          | Latitude E7440              | [63b84a9439](https://linux-hardware.org/?probe=63b84a9439) | Dec 06, 2022 |
| HP            | EliteBook 8470p             | [e2be1fe149](https://linux-hardware.org/?probe=e2be1fe149) | Dec 06, 2022 |
| Dell          | Latitude 5411               | [62e5941721](https://linux-hardware.org/?probe=62e5941721) | Dec 06, 2022 |
| Dell          | Latitude 5411               | [e0815067bd](https://linux-hardware.org/?probe=e0815067bd) | Dec 06, 2022 |
| Dell          | Latitude 5310               | [f3801600ff](https://linux-hardware.org/?probe=f3801600ff) | Dec 06, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [119ec75a5f](https://linux-hardware.org/?probe=119ec75a5f) | Dec 05, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [36985fd47e](https://linux-hardware.org/?probe=36985fd47e) | Dec 05, 2022 |
| Apple         | MacBookPro11,1              | [5b0565920f](https://linux-hardware.org/?probe=5b0565920f) | Dec 05, 2022 |
| ASUSTek       | X555LJ                      | [a849daba2b](https://linux-hardware.org/?probe=a849daba2b) | Dec 05, 2022 |
| Dell          | Latitude 3190               | [12975376ba](https://linux-hardware.org/?probe=12975376ba) | Dec 05, 2022 |
| MSI           | GF63 Thin 9RCX              | [1bf4364f61](https://linux-hardware.org/?probe=1bf4364f61) | Dec 05, 2022 |
| GMKtec        | NucBox5                     | [cdfbbcc5b2](https://linux-hardware.org/?probe=cdfbbcc5b2) | Dec 04, 2022 |
| Lenovo        | G770 20089                  | [d35d60f972](https://linux-hardware.org/?probe=d35d60f972) | Dec 04, 2022 |
| MSI           | Creator Z17 A12UHST         | [afbbf473b9](https://linux-hardware.org/?probe=afbbf473b9) | Dec 04, 2022 |
| Dell          | Vostro 5471                 | [0bad01b327](https://linux-hardware.org/?probe=0bad01b327) | Dec 04, 2022 |
| HP            | Pavilion dv7                | [90c7688386](https://linux-hardware.org/?probe=90c7688386) | Dec 04, 2022 |
| Google        | Lars                        | [efe9cef4b9](https://linux-hardware.org/?probe=efe9cef4b9) | Dec 04, 2022 |
| Dell          | XPS 15 9570                 | [ec5047129a](https://linux-hardware.org/?probe=ec5047129a) | Dec 03, 2022 |
| HP            | Pavilion dv7                | [c398cf4372](https://linux-hardware.org/?probe=c398cf4372) | Dec 03, 2022 |
| HP            | Pavilion dv7                | [e34ad54f3b](https://linux-hardware.org/?probe=e34ad54f3b) | Dec 03, 2022 |
| Google        | Lars                        | [ad022bfd93](https://linux-hardware.org/?probe=ad022bfd93) | Dec 03, 2022 |
| Dell          | G15 5515                    | [218e5c2825](https://linux-hardware.org/?probe=218e5c2825) | Dec 03, 2022 |
| Dell          | Latitude 5480               | [4eba5810d7](https://linux-hardware.org/?probe=4eba5810d7) | Dec 03, 2022 |
| Dell          | Vostro 5502                 | [86341e8306](https://linux-hardware.org/?probe=86341e8306) | Dec 02, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [4d33c2ab30](https://linux-hardware.org/?probe=4d33c2ab30) | Dec 02, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [929550dc41](https://linux-hardware.org/?probe=929550dc41) | Dec 01, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [615b292682](https://linux-hardware.org/?probe=615b292682) | Dec 01, 2022 |
| HP            | Pavilion dv7                | [aa6cdce8f8](https://linux-hardware.org/?probe=aa6cdce8f8) | Dec 01, 2022 |
| Lenovo        | IdeaPad 310-15IAP 80TT      | [3aa3302b92](https://linux-hardware.org/?probe=3aa3302b92) | Nov 30, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [c3d55f501c](https://linux-hardware.org/?probe=c3d55f501c) | Nov 30, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [f4de100586](https://linux-hardware.org/?probe=f4de100586) | Nov 29, 2022 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [802af80043](https://linux-hardware.org/?probe=802af80043) | Nov 29, 2022 |
| HP            | Pavilion dv7                | [1ba2fdd19b](https://linux-hardware.org/?probe=1ba2fdd19b) | Nov 29, 2022 |
| Dell          | Latitude E6540              | [48c805974c](https://linux-hardware.org/?probe=48c805974c) | Nov 29, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [9c45563fb6](https://linux-hardware.org/?probe=9c45563fb6) | Nov 29, 2022 |
| HP            | Pavilion dv7                | [db7897d2fc](https://linux-hardware.org/?probe=db7897d2fc) | Nov 28, 2022 |
| HP            | ProBook 640 G2              | [56ceffe338](https://linux-hardware.org/?probe=56ceffe338) | Nov 28, 2022 |
| Dell          | Latitude 3190               | [3c4756b965](https://linux-hardware.org/?probe=3c4756b965) | Nov 28, 2022 |
| HUAWEI        | MRC-WX0                     | [98f550465b](https://linux-hardware.org/?probe=98f550465b) | Nov 28, 2022 |
| Valve         | Jupiter                     | [ef85b8ab38](https://linux-hardware.org/?probe=ef85b8ab38) | Nov 28, 2022 |
| Valve         | Jupiter                     | [622315486c](https://linux-hardware.org/?probe=622315486c) | Nov 28, 2022 |
| ASUSTek       | G75VX                       | [87ef485975](https://linux-hardware.org/?probe=87ef485975) | Nov 27, 2022 |
| Acer          | AO722                       | [fb75768c70](https://linux-hardware.org/?probe=fb75768c70) | Nov 26, 2022 |
| HP            | ProBook 6470b               | [c8da54315e](https://linux-hardware.org/?probe=c8da54315e) | Nov 26, 2022 |
| Dell          | Latitude E6220              | [aa8d2d2fc7](https://linux-hardware.org/?probe=aa8d2d2fc7) | Nov 26, 2022 |
| Dell          | Vostro 5471                 | [7a6ec88b73](https://linux-hardware.org/?probe=7a6ec88b73) | Nov 26, 2022 |
| Dell          | Vostro 5471                 | [b9bbfd7551](https://linux-hardware.org/?probe=b9bbfd7551) | Nov 26, 2022 |
| Lenovo        | B51-80 80LM                 | [848b6ab7b3](https://linux-hardware.org/?probe=848b6ab7b3) | Nov 26, 2022 |
| Lenovo        | B51-80 80LM                 | [c34893c661](https://linux-hardware.org/?probe=c34893c661) | Nov 26, 2022 |
| Valve         | Jupiter                     | [7412d8b03b](https://linux-hardware.org/?probe=7412d8b03b) | Nov 26, 2022 |
| Valve         | Jupiter                     | [24d078fe91](https://linux-hardware.org/?probe=24d078fe91) | Nov 26, 2022 |
| Dell          | Latitude E6420              | [c3e8903f19](https://linux-hardware.org/?probe=c3e8903f19) | Nov 25, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [4261949a3e](https://linux-hardware.org/?probe=4261949a3e) | Nov 25, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [8acafcf4ab](https://linux-hardware.org/?probe=8acafcf4ab) | Nov 25, 2022 |
| Dell          | Inspiron 14 Plus 7420       | [a35ca4bbbe](https://linux-hardware.org/?probe=a35ca4bbbe) | Nov 24, 2022 |
| Dell          | Latitude 5310               | [8b4ad51670](https://linux-hardware.org/?probe=8b4ad51670) | Nov 24, 2022 |
| HP            | EliteBook 8560p             | [e7bf51183d](https://linux-hardware.org/?probe=e7bf51183d) | Nov 24, 2022 |
| Dell          | Latitude 5310               | [a5265c8a0e](https://linux-hardware.org/?probe=a5265c8a0e) | Nov 24, 2022 |
| HP            | 250 G6 Notebook PC          | [8f1bec4fe9](https://linux-hardware.org/?probe=8f1bec4fe9) | Nov 24, 2022 |
| ASUSTek       | K51AC                       | [0b2413e13c](https://linux-hardware.org/?probe=0b2413e13c) | Nov 24, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [e7717a62cb](https://linux-hardware.org/?probe=e7717a62cb) | Nov 23, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [ac72570183](https://linux-hardware.org/?probe=ac72570183) | Nov 23, 2022 |
| Kruger&Mat... | KM1406                      | [d639be7513](https://linux-hardware.org/?probe=d639be7513) | Nov 23, 2022 |
| Kruger&Mat... | KM1406                      | [a7e0207e4b](https://linux-hardware.org/?probe=a7e0207e4b) | Nov 23, 2022 |
| Lenovo        | IdeaPad 520S-14IKB 80X2     | [57dfd88985](https://linux-hardware.org/?probe=57dfd88985) | Nov 23, 2022 |
| HP            | Pavilion dv6                | [e3921e4da9](https://linux-hardware.org/?probe=e3921e4da9) | Nov 23, 2022 |
| MSI           | Modern 15 A5M               | [51ca9fa048](https://linux-hardware.org/?probe=51ca9fa048) | Nov 23, 2022 |
| MSI           | Modern 15 A5M               | [0ca1ce1d74](https://linux-hardware.org/?probe=0ca1ce1d74) | Nov 23, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [6d217fbd52](https://linux-hardware.org/?probe=6d217fbd52) | Nov 23, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [ad63d86cb9](https://linux-hardware.org/?probe=ad63d86cb9) | Nov 23, 2022 |
| HP            | G5000 (GF783EA#AKD)         | [2437328d23](https://linux-hardware.org/?probe=2437328d23) | Nov 22, 2022 |
| Dell          | Latitude 3420               | [30434de3e9](https://linux-hardware.org/?probe=30434de3e9) | Nov 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [c345afe01a](https://linux-hardware.org/?probe=c345afe01a) | Nov 22, 2022 |
| MSI           | Creator Z17 A12UHST         | [e36ab20d8c](https://linux-hardware.org/?probe=e36ab20d8c) | Nov 22, 2022 |
| MSI           | Creator Z17 A12UHST         | [014cf9f78d](https://linux-hardware.org/?probe=014cf9f78d) | Nov 22, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [a5dcbbbacd](https://linux-hardware.org/?probe=a5dcbbbacd) | Nov 22, 2022 |
| HP            | EliteBook Folio 1040 G1     | [26ac531682](https://linux-hardware.org/?probe=26ac531682) | Nov 22, 2022 |
| Dell          | Latitude 5410               | [7fd0b3fca7](https://linux-hardware.org/?probe=7fd0b3fca7) | Nov 21, 2022 |
| Dell          | Latitude 5490               | [295073cd07](https://linux-hardware.org/?probe=295073cd07) | Nov 21, 2022 |
| Dell          | Latitude 5310               | [9c19a3de68](https://linux-hardware.org/?probe=9c19a3de68) | Nov 21, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [0a98e4cae4](https://linux-hardware.org/?probe=0a98e4cae4) | Nov 21, 2022 |
| Dell          | Latitude 3190               | [1cfe937b0e](https://linux-hardware.org/?probe=1cfe937b0e) | Nov 21, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | [740b4f9f03](https://linux-hardware.org/?probe=740b4f9f03) | Nov 20, 2022 |
| HP            | Compaq Presario CQ60        | [3f18cccea5](https://linux-hardware.org/?probe=3f18cccea5) | Nov 20, 2022 |
| HUAWEI        | HVY-WXX9                    | [2030d33f00](https://linux-hardware.org/?probe=2030d33f00) | Nov 20, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [d8f53f887a](https://linux-hardware.org/?probe=d8f53f887a) | Nov 20, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c967893dd4](https://linux-hardware.org/?probe=c967893dd4) | Nov 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [1af7bd26fd](https://linux-hardware.org/?probe=1af7bd26fd) | Nov 19, 2022 |
| Lenovo        | S145-15API 81UT             | [fd832d05e2](https://linux-hardware.org/?probe=fd832d05e2) | Nov 19, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [8e7aa30e4e](https://linux-hardware.org/?probe=8e7aa30e4e) | Nov 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [ad7abfb8cb](https://linux-hardware.org/?probe=ad7abfb8cb) | Nov 19, 2022 |
| Acer          | Aspire V3-772G              | [bc46ec232a](https://linux-hardware.org/?probe=bc46ec232a) | Nov 18, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [4d8be4bb54](https://linux-hardware.org/?probe=4d8be4bb54) | Nov 18, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [dd25be7aef](https://linux-hardware.org/?probe=dd25be7aef) | Nov 17, 2022 |
| Dell          | Inspiron 13-5368            | [203df386a1](https://linux-hardware.org/?probe=203df386a1) | Nov 17, 2022 |
| Dell          | Inspiron 3451               | [105a376344](https://linux-hardware.org/?probe=105a376344) | Nov 17, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [5fd36e3d66](https://linux-hardware.org/?probe=5fd36e3d66) | Nov 17, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [62b2a72fa9](https://linux-hardware.org/?probe=62b2a72fa9) | Nov 16, 2022 |
| Lenovo        | ThinkPad T430 23498M7       | [fe520ea826](https://linux-hardware.org/?probe=fe520ea826) | Nov 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [b5eb364ac6](https://linux-hardware.org/?probe=b5eb364ac6) | Nov 16, 2022 |
| Valve         | Jupiter                     | [4ab915f825](https://linux-hardware.org/?probe=4ab915f825) | Nov 15, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [d07cacacde](https://linux-hardware.org/?probe=d07cacacde) | Nov 15, 2022 |
| HP            | ProBook 6450b               | [ee3a2a2ef8](https://linux-hardware.org/?probe=ee3a2a2ef8) | Nov 14, 2022 |
| Toshiba       | Satellite P300              | [02285947b8](https://linux-hardware.org/?probe=02285947b8) | Nov 13, 2022 |
| Dell          | Inspiron 3583               | [6fcf5c9bd6](https://linux-hardware.org/?probe=6fcf5c9bd6) | Nov 13, 2022 |
| Acer          | Aspire E1-531G              | [9f3c8742f7](https://linux-hardware.org/?probe=9f3c8742f7) | Nov 13, 2022 |
| Lenovo        | G580 20150                  | [7a628290f2](https://linux-hardware.org/?probe=7a628290f2) | Nov 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [1067cba3cc](https://linux-hardware.org/?probe=1067cba3cc) | Nov 12, 2022 |
| Dell          | Latitude E6540              | [e28c12e783](https://linux-hardware.org/?probe=e28c12e783) | Nov 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [59aa7d31d8](https://linux-hardware.org/?probe=59aa7d31d8) | Nov 11, 2022 |
| Apple         | MacBookPro14,1              | [2981b232db](https://linux-hardware.org/?probe=2981b232db) | Nov 11, 2022 |
| Lenovo        | ThinkPad P53 20QNS00Y00     | [3ebec87cd1](https://linux-hardware.org/?probe=3ebec87cd1) | Nov 11, 2022 |
| Lenovo        | G580 20150                  | [11344e1661](https://linux-hardware.org/?probe=11344e1661) | Nov 11, 2022 |
| Dell          | Latitude 7480               | [cd19ef7ab8](https://linux-hardware.org/?probe=cd19ef7ab8) | Nov 10, 2022 |
| Dell          | Latitude 7480               | [100bc3303a](https://linux-hardware.org/?probe=100bc3303a) | Nov 10, 2022 |
| MSI           | Stealth GS77 12UGS          | [bf125e16a2](https://linux-hardware.org/?probe=bf125e16a2) | Nov 10, 2022 |
| Dell          | Latitude E6330              | [04113ad3de](https://linux-hardware.org/?probe=04113ad3de) | Nov 10, 2022 |
| Dell          | Inspiron N7010              | [8d43f2e3fc](https://linux-hardware.org/?probe=8d43f2e3fc) | Nov 10, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [9d27997bce](https://linux-hardware.org/?probe=9d27997bce) | Nov 09, 2022 |
| MSI           | Creator Z17 A12UHST         | [a3b1e0d746](https://linux-hardware.org/?probe=a3b1e0d746) | Nov 09, 2022 |
| Dell          | XPS 15 9550                 | [6642f568d4](https://linux-hardware.org/?probe=6642f568d4) | Nov 09, 2022 |
| MSI           | Stealth GS77 12UGS          | [ae6b308816](https://linux-hardware.org/?probe=ae6b308816) | Nov 08, 2022 |
| Dell          | G5 5587                     | [972a2dcaa0](https://linux-hardware.org/?probe=972a2dcaa0) | Nov 08, 2022 |
| Lenovo        | ThinkPad P53 20QQS2CY00     | [98e9599ea3](https://linux-hardware.org/?probe=98e9599ea3) | Nov 08, 2022 |
| Dell          | Latitude E7470              | [3938dbeadd](https://linux-hardware.org/?probe=3938dbeadd) | Nov 08, 2022 |
| ASUSTek       | Zenbook UM5401QA_UM5401Q... | [d19fce3e6c](https://linux-hardware.org/?probe=d19fce3e6c) | Nov 08, 2022 |
| MSI           | Creator Z17 A12UHST         | [891dbf2492](https://linux-hardware.org/?probe=891dbf2492) | Nov 07, 2022 |
| Acer          | Aspire E5-573G              | [fafbf5ba02](https://linux-hardware.org/?probe=fafbf5ba02) | Nov 07, 2022 |
| HP            | ProBook 5330m               | [7ddff41cb6](https://linux-hardware.org/?probe=7ddff41cb6) | Nov 07, 2022 |
| HP            | ProBook 6570b               | [1fec197471](https://linux-hardware.org/?probe=1fec197471) | Nov 06, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | [e872e8551e](https://linux-hardware.org/?probe=e872e8551e) | Nov 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [3ec96d66bb](https://linux-hardware.org/?probe=3ec96d66bb) | Nov 05, 2022 |
| Lenovo        | ThinkPad L480 20LS001AMC    | [010fd86c32](https://linux-hardware.org/?probe=010fd86c32) | Nov 04, 2022 |
| Acer          | Aspire A715-74G             | [fa89b7a988](https://linux-hardware.org/?probe=fa89b7a988) | Nov 04, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [24e798d2a5](https://linux-hardware.org/?probe=24e798d2a5) | Nov 04, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | [391881cdd5](https://linux-hardware.org/?probe=391881cdd5) | Nov 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [455bdc6c45](https://linux-hardware.org/?probe=455bdc6c45) | Nov 03, 2022 |
| HP            | EliteBook 745 G2            | [c6505744ca](https://linux-hardware.org/?probe=c6505744ca) | Nov 03, 2022 |
| Dell          | Latitude E6540              | [fe0f06d2d3](https://linux-hardware.org/?probe=fe0f06d2d3) | Nov 02, 2022 |
| Dell          | Latitude E6430              | [2b6012cc1d](https://linux-hardware.org/?probe=2b6012cc1d) | Nov 02, 2022 |
| Dell          | G15 5515                    | [92f1423303](https://linux-hardware.org/?probe=92f1423303) | Nov 02, 2022 |
| Dell          | G15 5515                    | [dae7c630d5](https://linux-hardware.org/?probe=dae7c630d5) | Nov 02, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [310895b721](https://linux-hardware.org/?probe=310895b721) | Nov 01, 2022 |
| HUAWEI        | KPL-W0X                     | [6d6a8caf61](https://linux-hardware.org/?probe=6d6a8caf61) | Nov 01, 2022 |
| HP            | Unknown                     | [1ca885060e](https://linux-hardware.org/?probe=1ca885060e) | Nov 01, 2022 |
| HP            | EliteBook 745 G2            | [0786ded6c8](https://linux-hardware.org/?probe=0786ded6c8) | Oct 31, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [b4fedd7c20](https://linux-hardware.org/?probe=b4fedd7c20) | Oct 31, 2022 |
| Dell          | Latitude 3190               | [fe0d1261a6](https://linux-hardware.org/?probe=fe0d1261a6) | Oct 31, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [24d91cf27b](https://linux-hardware.org/?probe=24d91cf27b) | Oct 30, 2022 |
| HP            | ProBook 6540b               | [be9c128b00](https://linux-hardware.org/?probe=be9c128b00) | Oct 30, 2022 |
| Kiano         | SlimNote 1.0                | [db1ae618d8](https://linux-hardware.org/?probe=db1ae618d8) | Oct 29, 2022 |
| Dell          | Latitude 5501               | [67f979a26d](https://linux-hardware.org/?probe=67f979a26d) | Oct 29, 2022 |
| ASUSTek       | X75VC                       | [9c1ab509ec](https://linux-hardware.org/?probe=9c1ab509ec) | Oct 29, 2022 |
| Lenovo        | ThinkPad T450s 20BWS0DD0... | [973a3662b9](https://linux-hardware.org/?probe=973a3662b9) | Oct 29, 2022 |
| Kruger&Mat... | KM1406                      | [70b8441ccf](https://linux-hardware.org/?probe=70b8441ccf) | Oct 29, 2022 |
| Dell          | Inspiron 7520               | [91f0c87afa](https://linux-hardware.org/?probe=91f0c87afa) | Oct 29, 2022 |
| HP            | 250 G8 Notebook PC          | [59c02d4967](https://linux-hardware.org/?probe=59c02d4967) | Oct 28, 2022 |
| Dell          | Latitude 5531               | [a7ff9a34d2](https://linux-hardware.org/?probe=a7ff9a34d2) | Oct 28, 2022 |
| Dell          | Latitude 5531               | [73ddced77b](https://linux-hardware.org/?probe=73ddced77b) | Oct 28, 2022 |
| HP            | EliteBook 840 G6            | [89cc00ef58](https://linux-hardware.org/?probe=89cc00ef58) | Oct 28, 2022 |
| Fujitsu       | LIFEBOOK U728               | [c5867e7dd3](https://linux-hardware.org/?probe=c5867e7dd3) | Oct 28, 2022 |
| Dell          | XPS 15 9510                 | [d3879c6bb0](https://linux-hardware.org/?probe=d3879c6bb0) | Oct 28, 2022 |
| Lenovo        | ThinkPad T430 23498M7       | [f936993d28](https://linux-hardware.org/?probe=f936993d28) | Oct 28, 2022 |
| Gateway       | P-7805u                     | [7597071801](https://linux-hardware.org/?probe=7597071801) | Oct 28, 2022 |
| Dell          | Latitude E6530              | [71b2df6eff](https://linux-hardware.org/?probe=71b2df6eff) | Oct 27, 2022 |
| Acer          | Aspire A114-32              | [4261d8dd66](https://linux-hardware.org/?probe=4261d8dd66) | Oct 27, 2022 |
| Acer          | Aspire A114-32              | [216730dba7](https://linux-hardware.org/?probe=216730dba7) | Oct 27, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [00e77b8815](https://linux-hardware.org/?probe=00e77b8815) | Oct 26, 2022 |
| Dell          | Latitude E6530              | [c271a351aa](https://linux-hardware.org/?probe=c271a351aa) | Oct 26, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [94d1c333ac](https://linux-hardware.org/?probe=94d1c333ac) | Oct 26, 2022 |
| HUAWEI        | HKD-WXX                     | [2ff7652d3a](https://linux-hardware.org/?probe=2ff7652d3a) | Oct 26, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [082e572642](https://linux-hardware.org/?probe=082e572642) | Oct 26, 2022 |
| Lenovo        | ThinkPad T490s 20NX002QU... | [6ba1aaf015](https://linux-hardware.org/?probe=6ba1aaf015) | Oct 26, 2022 |
| Lenovo        | ThinkPad T490s 20NX002QU... | [062d1d3b82](https://linux-hardware.org/?probe=062d1d3b82) | Oct 26, 2022 |
| Lenovo        | ThinkPad R500 2716W2K       | [c9a59d0ee9](https://linux-hardware.org/?probe=c9a59d0ee9) | Oct 26, 2022 |
| MSI           | Creator Z17 A12UHST         | [18df556ca1](https://linux-hardware.org/?probe=18df556ca1) | Oct 25, 2022 |
| ASUSTek       | X540SA                      | [a515dd93cd](https://linux-hardware.org/?probe=a515dd93cd) | Oct 25, 2022 |
| Lenovo        | ThinkPad T490 20N3S9DJ00    | [c1a4fde481](https://linux-hardware.org/?probe=c1a4fde481) | Oct 24, 2022 |
| Lenovo        | ThinkPad T490 20N3S9DJ00    | [80bf151a4d](https://linux-hardware.org/?probe=80bf151a4d) | Oct 24, 2022 |
| Dell          | Latitude 3190               | [b116ac92f3](https://linux-hardware.org/?probe=b116ac92f3) | Oct 24, 2022 |
| HP            | ZBook 17 G6                 | [d28d720a26](https://linux-hardware.org/?probe=d28d720a26) | Oct 23, 2022 |
| Dell          | Latitude 7390               | [f282e79ccb](https://linux-hardware.org/?probe=f282e79ccb) | Oct 23, 2022 |
| Dell          | Latitude 7390               | [ec27a5efb5](https://linux-hardware.org/?probe=ec27a5efb5) | Oct 23, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [1f26696990](https://linux-hardware.org/?probe=1f26696990) | Oct 22, 2022 |
| Lenovo        | ThinkPad SL500 27463ZG      | [88a93e44f9](https://linux-hardware.org/?probe=88a93e44f9) | Oct 22, 2022 |
| ASUSTek       | X550LN                      | [7a6daf6023](https://linux-hardware.org/?probe=7a6daf6023) | Oct 22, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [f5af95bb9a](https://linux-hardware.org/?probe=f5af95bb9a) | Oct 21, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [5def3f5324](https://linux-hardware.org/?probe=5def3f5324) | Oct 21, 2022 |
| Acer          | Aspire A515-51G             | [d607def641](https://linux-hardware.org/?probe=d607def641) | Oct 20, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [7cd6e349f0](https://linux-hardware.org/?probe=7cd6e349f0) | Oct 20, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [344040aee1](https://linux-hardware.org/?probe=344040aee1) | Oct 19, 2022 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | [67ebd92594](https://linux-hardware.org/?probe=67ebd92594) | Oct 19, 2022 |
| MSI           | Creator Z17 A12UHST         | [5d65b94f2b](https://linux-hardware.org/?probe=5d65b94f2b) | Oct 19, 2022 |
| Lenovo        | Legion 5 17ACH6 82K0        | [431a84fc31](https://linux-hardware.org/?probe=431a84fc31) | Oct 18, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [8bc82af4e5](https://linux-hardware.org/?probe=8bc82af4e5) | Oct 18, 2022 |
| Lenovo        | G580 20150                  | [7639ea3b73](https://linux-hardware.org/?probe=7639ea3b73) | Oct 18, 2022 |
| Dell          | Latitude 5421               | [77cbc2b788](https://linux-hardware.org/?probe=77cbc2b788) | Oct 18, 2022 |
| Dell          | Vostro 7580                 | [69cc3a8c62](https://linux-hardware.org/?probe=69cc3a8c62) | Oct 18, 2022 |
| HP            | ZBook 17 G6                 | [2f27f08ce8](https://linux-hardware.org/?probe=2f27f08ce8) | Oct 17, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [b8dbd1daf9](https://linux-hardware.org/?probe=b8dbd1daf9) | Oct 17, 2022 |
| Dell          | Inspiron 3541               | [858e5b974b](https://linux-hardware.org/?probe=858e5b974b) | Oct 17, 2022 |
| Dell          | Vostro 15-3568              | [b7ea5640c2](https://linux-hardware.org/?probe=b7ea5640c2) | Oct 17, 2022 |
| Dell          | Latitude E6430              | [2e8f3bd664](https://linux-hardware.org/?probe=2e8f3bd664) | Oct 16, 2022 |
| Acer          | Aspire SW5-012              | [530046bf8a](https://linux-hardware.org/?probe=530046bf8a) | Oct 15, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [bf6d77aefd](https://linux-hardware.org/?probe=bf6d77aefd) | Oct 15, 2022 |
| HUAWEI        | KLVD-WXX9                   | [bb7d61198e](https://linux-hardware.org/?probe=bb7d61198e) | Oct 14, 2022 |
| HP            | ENVY 15                     | [09bfbadebe](https://linux-hardware.org/?probe=09bfbadebe) | Oct 14, 2022 |
| MSI           | MS-N014                     | [87e6e540be](https://linux-hardware.org/?probe=87e6e540be) | Oct 14, 2022 |
| Lenovo        | G500s 20245                 | [61539bde5e](https://linux-hardware.org/?probe=61539bde5e) | Oct 13, 2022 |
| Dell          | Inspiron 5551               | [64865d9bb5](https://linux-hardware.org/?probe=64865d9bb5) | Oct 13, 2022 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | [973f501233](https://linux-hardware.org/?probe=973f501233) | Oct 13, 2022 |
| Dell          | Inspiron 3451               | [37b9e0d491](https://linux-hardware.org/?probe=37b9e0d491) | Oct 13, 2022 |
| Lenovo        | G580 20150                  | [8e564b93cb](https://linux-hardware.org/?probe=8e564b93cb) | Oct 13, 2022 |
| Acer          | Aspire A315-21              | [a122b26729](https://linux-hardware.org/?probe=a122b26729) | Oct 12, 2022 |
| Dell          | XPS 13 9310                 | [8437ac2ffc](https://linux-hardware.org/?probe=8437ac2ffc) | Oct 12, 2022 |
| Lenovo        | ThinkPad T530 24297TG       | [d6dec1ab6d](https://linux-hardware.org/?probe=d6dec1ab6d) | Oct 12, 2022 |
| ASUSTek       | X705UDR                     | [5c8601bb4f](https://linux-hardware.org/?probe=5c8601bb4f) | Oct 11, 2022 |
| ASUSTek       | G750JW                      | [251f32c620](https://linux-hardware.org/?probe=251f32c620) | Oct 11, 2022 |
| Lenovo        | ThinkPad X200s 7470A98      | [2aea48a0f2](https://linux-hardware.org/?probe=2aea48a0f2) | Oct 11, 2022 |
| Lenovo        | ThinkPad X200s 7470A98      | [10d90de300](https://linux-hardware.org/?probe=10d90de300) | Oct 11, 2022 |
| Lenovo        | ThinkPad P50 20EQS5MP00     | [83858a99c3](https://linux-hardware.org/?probe=83858a99c3) | Oct 10, 2022 |
| Lenovo        | ThinkPad SL500 27463ZG      | [4c575be5d7](https://linux-hardware.org/?probe=4c575be5d7) | Oct 10, 2022 |
| Acer          | Enduro EUN314-51W           | [14741407aa](https://linux-hardware.org/?probe=14741407aa) | Oct 10, 2022 |
| Dell          | Latitude 3190               | [bee132f486](https://linux-hardware.org/?probe=bee132f486) | Oct 10, 2022 |
| ASUSTek       | GL503VD                     | [1405b367c2](https://linux-hardware.org/?probe=1405b367c2) | Oct 09, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [94ccd99c78](https://linux-hardware.org/?probe=94ccd99c78) | Oct 09, 2022 |
| ASUSTek       | X550VB                      | [a7c1c1cb1b](https://linux-hardware.org/?probe=a7c1c1cb1b) | Oct 09, 2022 |
| Dell          | Inspiron N7010              | [8d58156239](https://linux-hardware.org/?probe=8d58156239) | Oct 09, 2022 |
| Dell          | Precision 7530              | [7f71730e68](https://linux-hardware.org/?probe=7f71730e68) | Oct 07, 2022 |
| Dell          | Inspiron 3451               | [29de9dfa4a](https://linux-hardware.org/?probe=29de9dfa4a) | Oct 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [ae8f71dbd3](https://linux-hardware.org/?probe=ae8f71dbd3) | Oct 06, 2022 |
| Toshiba       | Satellite L40               | [0f3e9273a6](https://linux-hardware.org/?probe=0f3e9273a6) | Oct 06, 2022 |
| Lenovo        | ThinkPad T480 20L50007PB    | [4c7a6898bf](https://linux-hardware.org/?probe=4c7a6898bf) | Oct 06, 2022 |
| Dell          | Vostro 15-3568              | [ed969ece24](https://linux-hardware.org/?probe=ed969ece24) | Oct 05, 2022 |
| Dell          | Precision 3541              | [bfef2cb8a3](https://linux-hardware.org/?probe=bfef2cb8a3) | Oct 05, 2022 |
| ASUSTek       | X550CC                      | [147483a370](https://linux-hardware.org/?probe=147483a370) | Oct 05, 2022 |
| Valve         | Jupiter                     | [ac2707d2e6](https://linux-hardware.org/?probe=ac2707d2e6) | Oct 05, 2022 |
| Lenovo        | ThinkPad T460p 20FW002CP... | [b7cd76d0b6](https://linux-hardware.org/?probe=b7cd76d0b6) | Oct 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [d389c9fa00](https://linux-hardware.org/?probe=d389c9fa00) | Oct 05, 2022 |
| Lenovo        | Z51-70 80K6                 | [736ded7422](https://linux-hardware.org/?probe=736ded7422) | Oct 04, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [b8ad7a8464](https://linux-hardware.org/?probe=b8ad7a8464) | Oct 04, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [6c821c0c08](https://linux-hardware.org/?probe=6c821c0c08) | Oct 03, 2022 |
| HP            | ProBook 640 G2              | [2dc13504cf](https://linux-hardware.org/?probe=2dc13504cf) | Oct 03, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0QK0... | [a9c2a1eca0](https://linux-hardware.org/?probe=a9c2a1eca0) | Oct 03, 2022 |
| ASUSTek       | 1225B                       | [9bb2d54ca7](https://linux-hardware.org/?probe=9bb2d54ca7) | Oct 03, 2022 |
| Dell          | Inspiron 3451               | [9bf3a4a735](https://linux-hardware.org/?probe=9bf3a4a735) | Oct 03, 2022 |
| Dynabook      | PORTEGE X40-G               | [fc68a9cdbf](https://linux-hardware.org/?probe=fc68a9cdbf) | Oct 03, 2022 |
| Dell          | Latitude 3190               | [29b38a4a94](https://linux-hardware.org/?probe=29b38a4a94) | Oct 03, 2022 |
| Acer          | Aspire 5755G                | [c552cb5631](https://linux-hardware.org/?probe=c552cb5631) | Oct 02, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [05e921b4aa](https://linux-hardware.org/?probe=05e921b4aa) | Oct 02, 2022 |
| Acer          | Aspire 4733Z                | [4be4debbe5](https://linux-hardware.org/?probe=4be4debbe5) | Oct 01, 2022 |
| Lenovo        | ThinkPad SL500 27463ZG      | [34006e3b46](https://linux-hardware.org/?probe=34006e3b46) | Oct 01, 2022 |
| Dell          | Inspiron 3451               | [aee33639b9](https://linux-hardware.org/?probe=aee33639b9) | Oct 01, 2022 |
| Acer          | Aspire A715-74G             | [17abc08754](https://linux-hardware.org/?probe=17abc08754) | Sep 30, 2022 |
| HP            | Pavilion Laptop 17-ar0xx    | [733654d30d](https://linux-hardware.org/?probe=733654d30d) | Sep 30, 2022 |
| Lenovo        | G500s 20245                 | [b9001f7817](https://linux-hardware.org/?probe=b9001f7817) | Sep 29, 2022 |
| HP            | ZBook Firefly 15.6 inch ... | [be74c01cca](https://linux-hardware.org/?probe=be74c01cca) | Sep 29, 2022 |
| Dell          | Latitude E6330              | [b075fbcb56](https://linux-hardware.org/?probe=b075fbcb56) | Sep 29, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [82528435d8](https://linux-hardware.org/?probe=82528435d8) | Sep 29, 2022 |
| MSI           | Creator Z17 A12UHST         | [4b9249b9b0](https://linux-hardware.org/?probe=4b9249b9b0) | Sep 29, 2022 |
| Dell          | Inspiron 5558               | [a42a4722f7](https://linux-hardware.org/?probe=a42a4722f7) | Sep 28, 2022 |
| Valve         | Jupiter                     | [bdc84f1b9b](https://linux-hardware.org/?probe=bdc84f1b9b) | Sep 28, 2022 |
| ASUSTek       | Zenbook UM5401QA_UM5401Q... | [04fbd64661](https://linux-hardware.org/?probe=04fbd64661) | Sep 27, 2022 |
| Dell          | Precision 3561              | [77a4030052](https://linux-hardware.org/?probe=77a4030052) | Sep 27, 2022 |
| Toshiba       | Satellite C850-1LK          | [f0240dcb2d](https://linux-hardware.org/?probe=f0240dcb2d) | Sep 27, 2022 |
| Lenovo        | ThinkPad SL500 27463ZG      | [70860ec433](https://linux-hardware.org/?probe=70860ec433) | Sep 26, 2022 |
| Lenovo        | ThinkPad Edge E430 3254A... | [cb5f6f279b](https://linux-hardware.org/?probe=cb5f6f279b) | Sep 26, 2022 |
| Lenovo        | ThinkPad Edge E430 3254A... | [3f11c520e0](https://linux-hardware.org/?probe=3f11c520e0) | Sep 26, 2022 |
| HP            | ZBook 15 G6                 | [476623a6a1](https://linux-hardware.org/?probe=476623a6a1) | Sep 26, 2022 |
| Dell          | Latitude 3190               | [27ac75e10c](https://linux-hardware.org/?probe=27ac75e10c) | Sep 26, 2022 |
| Valve         | Jupiter                     | [ebf3e70cf7](https://linux-hardware.org/?probe=ebf3e70cf7) | Sep 25, 2022 |
| Acer          | P5WE0                       | [124f7bdd77](https://linux-hardware.org/?probe=124f7bdd77) | Sep 25, 2022 |
| HP            | Laptop 17-cp0xxx            | [dafafa97a4](https://linux-hardware.org/?probe=dafafa97a4) | Sep 24, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [89a1a3179d](https://linux-hardware.org/?probe=89a1a3179d) | Sep 24, 2022 |
| Toshiba       | Satellite P205              | [2a1450578e](https://linux-hardware.org/?probe=2a1450578e) | Sep 23, 2022 |
| Fujitsu       | LIFEBOOK S760               | [ceda61113a](https://linux-hardware.org/?probe=ceda61113a) | Sep 23, 2022 |
| Toshiba       | Satellite P205              | [98e97d946a](https://linux-hardware.org/?probe=98e97d946a) | Sep 23, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [36c369745a](https://linux-hardware.org/?probe=36c369745a) | Sep 23, 2022 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | [0121aac33a](https://linux-hardware.org/?probe=0121aac33a) | Sep 22, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [de7c138e21](https://linux-hardware.org/?probe=de7c138e21) | Sep 22, 2022 |
| Lenovo        | G505s 20255                 | [671c1cb6c4](https://linux-hardware.org/?probe=671c1cb6c4) | Sep 21, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [967110ef60](https://linux-hardware.org/?probe=967110ef60) | Sep 21, 2022 |
| HP            | EliteBook 840 G2            | [030ce84327](https://linux-hardware.org/?probe=030ce84327) | Sep 20, 2022 |
| Framework     | Laptop                      | [dd163cfa96](https://linux-hardware.org/?probe=dd163cfa96) | Sep 20, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [21c74278f8](https://linux-hardware.org/?probe=21c74278f8) | Sep 20, 2022 |
| Dell          | Latitude E4310              | [c77a454d4e](https://linux-hardware.org/?probe=c77a454d4e) | Sep 20, 2022 |
| Dell          | Latitude E4310              | [4e8bf046d8](https://linux-hardware.org/?probe=4e8bf046d8) | Sep 19, 2022 |
| Apple         | MacBook9,1                  | [e6898c8aa0](https://linux-hardware.org/?probe=e6898c8aa0) | Sep 19, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [85952e171d](https://linux-hardware.org/?probe=85952e171d) | Sep 19, 2022 |
| HP            | ProBook 470 G5              | [eb67db5bff](https://linux-hardware.org/?probe=eb67db5bff) | Sep 19, 2022 |
| Lenovo        | ThinkPad T420 4180MY7       | [e6a930e933](https://linux-hardware.org/?probe=e6a930e933) | Sep 19, 2022 |
| HP            | ProBook 470 G5              | [793fa18b58](https://linux-hardware.org/?probe=793fa18b58) | Sep 19, 2022 |
| ASUSTek       | GL502VSK                    | [a6dc9b627f](https://linux-hardware.org/?probe=a6dc9b627f) | Sep 19, 2022 |
| Toshiba       | PORTEGE Z30-A               | [419bf72e22](https://linux-hardware.org/?probe=419bf72e22) | Sep 19, 2022 |
| Dell          | Latitude 3190               | [f96d782326](https://linux-hardware.org/?probe=f96d782326) | Sep 19, 2022 |
| Valve         | Jupiter                     | [52352bab7a](https://linux-hardware.org/?probe=52352bab7a) | Sep 19, 2022 |
| HP            | Notebook                    | [d29681d2ed](https://linux-hardware.org/?probe=d29681d2ed) | Sep 17, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [9c23c7bb58](https://linux-hardware.org/?probe=9c23c7bb58) | Sep 17, 2022 |
| Lenovo        | G50-80 80E5                 | [5023f912e2](https://linux-hardware.org/?probe=5023f912e2) | Sep 16, 2022 |
| Lenovo        | ThinkPad T420 4180A32       | [44841341fd](https://linux-hardware.org/?probe=44841341fd) | Sep 16, 2022 |
| Dell          | Latitude 5511               | [9a2faa8d22](https://linux-hardware.org/?probe=9a2faa8d22) | Sep 16, 2022 |
| HP            | ProBook 470 G5              | [b15d9e1fe4](https://linux-hardware.org/?probe=b15d9e1fe4) | Sep 16, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZX... | [099e5d3523](https://linux-hardware.org/?probe=099e5d3523) | Sep 16, 2022 |
| Dell          | Inspiron 3451               | [fcdfa43a37](https://linux-hardware.org/?probe=fcdfa43a37) | Sep 15, 2022 |
| Dell          | Inspiron 5584               | [677d683644](https://linux-hardware.org/?probe=677d683644) | Sep 14, 2022 |
| Dell          | Latitude 5521               | [c342e3ab13](https://linux-hardware.org/?probe=c342e3ab13) | Sep 14, 2022 |
| HUAWEI        | KLVL-WXX9                   | [98ae2af06f](https://linux-hardware.org/?probe=98ae2af06f) | Sep 14, 2022 |
| Dell          | Inspiron 3451               | [f06aa45765](https://linux-hardware.org/?probe=f06aa45765) | Sep 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [efc31007ac](https://linux-hardware.org/?probe=efc31007ac) | Sep 12, 2022 |
| Dell          | Latitude 3190               | [3c0abb17a9](https://linux-hardware.org/?probe=3c0abb17a9) | Sep 12, 2022 |
| HUAWEI        | KPL-W0X                     | [eff4400b7d](https://linux-hardware.org/?probe=eff4400b7d) | Sep 10, 2022 |
| Lenovo        | ThinkPad L420 7829H86       | [406535e915](https://linux-hardware.org/?probe=406535e915) | Sep 10, 2022 |
| Acer          | Nitro AN517-55              | [16fa00177a](https://linux-hardware.org/?probe=16fa00177a) | Sep 10, 2022 |
| Toshiba       | Satellite L40               | [ef6556670c](https://linux-hardware.org/?probe=ef6556670c) | Sep 09, 2022 |
| Dell          | Latitude E6330              | [9f2183ce75](https://linux-hardware.org/?probe=9f2183ce75) | Sep 09, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | [c2f25bcea8](https://linux-hardware.org/?probe=c2f25bcea8) | Sep 08, 2022 |
| Gigabyte      | AORUS 15G XC                | [ea131dfe2c](https://linux-hardware.org/?probe=ea131dfe2c) | Sep 08, 2022 |
| Dell          | Latitude E6540              | [5700f37281](https://linux-hardware.org/?probe=5700f37281) | Sep 08, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [6812b52b92](https://linux-hardware.org/?probe=6812b52b92) | Sep 08, 2022 |
| Dell          | Inspiron 3541               | [2cc868e8f0](https://linux-hardware.org/?probe=2cc868e8f0) | Sep 08, 2022 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [6ee5358914](https://linux-hardware.org/?probe=6ee5358914) | Sep 08, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | [63524aa492](https://linux-hardware.org/?probe=63524aa492) | Sep 07, 2022 |
| HP            | EliteBook 8440p             | [5cf26fac4d](https://linux-hardware.org/?probe=5cf26fac4d) | Sep 07, 2022 |
| Samsung       | RC420/RC520/RC720           | [a6b07acfe5](https://linux-hardware.org/?probe=a6b07acfe5) | Sep 07, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | [4adadf9e6a](https://linux-hardware.org/?probe=4adadf9e6a) | Sep 06, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [4615004e85](https://linux-hardware.org/?probe=4615004e85) | Sep 06, 2022 |
| Lenovo        | G580 20150                  | [e0bb6ae251](https://linux-hardware.org/?probe=e0bb6ae251) | Sep 05, 2022 |
| Dell          | Latitude 3190               | [25c70ea2f3](https://linux-hardware.org/?probe=25c70ea2f3) | Sep 05, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [d802875fec](https://linux-hardware.org/?probe=d802875fec) | Sep 04, 2022 |
| Dell          | Latitude E5430 non-vPro     | [96d17dc188](https://linux-hardware.org/?probe=96d17dc188) | Sep 04, 2022 |
| Dell          | Latitude E6330              | [e4dcf51a84](https://linux-hardware.org/?probe=e4dcf51a84) | Sep 04, 2022 |
| HP            | 620                         | [096486e01d](https://linux-hardware.org/?probe=096486e01d) | Sep 03, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [6b62abaaaf](https://linux-hardware.org/?probe=6b62abaaaf) | Sep 03, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ec466abbf7](https://linux-hardware.org/?probe=ec466abbf7) | Sep 03, 2022 |
| Dell          | Latitude E6330              | [626c1e28b1](https://linux-hardware.org/?probe=626c1e28b1) | Sep 03, 2022 |
| Dell          | Latitude E6330              | [6c7adba5b6](https://linux-hardware.org/?probe=6c7adba5b6) | Sep 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [6669ffa68e](https://linux-hardware.org/?probe=6669ffa68e) | Sep 02, 2022 |
| Dell          | Latitude E6220              | [e249853663](https://linux-hardware.org/?probe=e249853663) | Sep 02, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [8320ded55c](https://linux-hardware.org/?probe=8320ded55c) | Sep 02, 2022 |
| Valve         | Jupiter                     | [ad3ce497e7](https://linux-hardware.org/?probe=ad3ce497e7) | Sep 02, 2022 |
| Dell          | Latitude E6220              | [99c8b865ad](https://linux-hardware.org/?probe=99c8b865ad) | Sep 02, 2022 |
| Dell          | Latitude E6330              | [179123f301](https://linux-hardware.org/?probe=179123f301) | Sep 01, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [12abd434b5](https://linux-hardware.org/?probe=12abd434b5) | Sep 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [e16313490d](https://linux-hardware.org/?probe=e16313490d) | Sep 01, 2022 |
| Valve         | Jupiter                     | [60db4bfa03](https://linux-hardware.org/?probe=60db4bfa03) | Aug 31, 2022 |
| Dell          | Latitude E6330              | [b5766d41fa](https://linux-hardware.org/?probe=b5766d41fa) | Aug 31, 2022 |
| Lenovo        | ThinkPad L490 20Q5001YPB    | [daae538154](https://linux-hardware.org/?probe=daae538154) | Aug 30, 2022 |
| Dell          | Latitude 3190               | [0998f7a5d1](https://linux-hardware.org/?probe=0998f7a5d1) | Aug 29, 2022 |
| Dell          | Latitude 9420               | [0b8d883170](https://linux-hardware.org/?probe=0b8d883170) | Aug 29, 2022 |
| ASUSTek       | F3E                         | [1314dc63b6](https://linux-hardware.org/?probe=1314dc63b6) | Aug 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [7ed4b144d7](https://linux-hardware.org/?probe=7ed4b144d7) | Aug 28, 2022 |
| HP            | Pavilion dv6700             | [8fae050683](https://linux-hardware.org/?probe=8fae050683) | Aug 28, 2022 |
| Dell          | Latitude E6400              | [666ba32534](https://linux-hardware.org/?probe=666ba32534) | Aug 28, 2022 |
| HP            | Pavilion dv6700             | [1912258e10](https://linux-hardware.org/?probe=1912258e10) | Aug 27, 2022 |
| Lenovo        | G580 20150                  | [1813b94682](https://linux-hardware.org/?probe=1813b94682) | Aug 27, 2022 |
| HP            | 15                          | [310d617e09](https://linux-hardware.org/?probe=310d617e09) | Aug 26, 2022 |
| ASUSTek       | X705UAP                     | [eacfc15b6c](https://linux-hardware.org/?probe=eacfc15b6c) | Aug 24, 2022 |
| Dell          | Inspiron 5402               | [936ea503c8](https://linux-hardware.org/?probe=936ea503c8) | Aug 24, 2022 |
| Acer          | Aspire E5-571               | [659e36b0ed](https://linux-hardware.org/?probe=659e36b0ed) | Aug 23, 2022 |
| Dell          | Latitude 5521               | [b14afc8c75](https://linux-hardware.org/?probe=b14afc8c75) | Aug 22, 2022 |
| Dell          | XPS 15 9560                 | [29d52f610c](https://linux-hardware.org/?probe=29d52f610c) | Aug 22, 2022 |
| Dell          | Latitude 3190               | [74fd1046be](https://linux-hardware.org/?probe=74fd1046be) | Aug 22, 2022 |
| Lenovo        | ThinkPad T400 6474B84       | [f8a6513790](https://linux-hardware.org/?probe=f8a6513790) | Aug 22, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [a80c24ae6b](https://linux-hardware.org/?probe=a80c24ae6b) | Aug 21, 2022 |
| Valve         | Jupiter                     | [eb63fecd35](https://linux-hardware.org/?probe=eb63fecd35) | Aug 19, 2022 |
| HP            | Compaq nx7300 (RH678EA#A... | [6fc01cef23](https://linux-hardware.org/?probe=6fc01cef23) | Aug 19, 2022 |
| Acer          | Aspire E5-475               | [f21f1687d5](https://linux-hardware.org/?probe=f21f1687d5) | Aug 19, 2022 |
| Acer          | Aspire E5-475               | [04b38f1dfd](https://linux-hardware.org/?probe=04b38f1dfd) | Aug 19, 2022 |
| Dell          | Latitude E5430 non-vPro     | [ac7fb69037](https://linux-hardware.org/?probe=ac7fb69037) | Aug 19, 2022 |
| Dell          | Latitude 7280               | [63e00d0c9d](https://linux-hardware.org/?probe=63e00d0c9d) | Aug 18, 2022 |
| HP            | ZBook 17 G6                 | [fdcb40d147](https://linux-hardware.org/?probe=fdcb40d147) | Aug 18, 2022 |
| HP            | ZBook 17 G6                 | [cf5500d7b1](https://linux-hardware.org/?probe=cf5500d7b1) | Aug 18, 2022 |
| Lenovo        | ThinkPad E520 1143CWG       | [bc6f3f891a](https://linux-hardware.org/?probe=bc6f3f891a) | Aug 18, 2022 |
| NEC Comput... | PC-LJ730MG6W                | [c0e6c7edb7](https://linux-hardware.org/?probe=c0e6c7edb7) | Aug 17, 2022 |
| MSI           | GT72S 6QE                   | [20121e68c8](https://linux-hardware.org/?probe=20121e68c8) | Aug 16, 2022 |
| Dell          | Latitude 3190               | [5564506d3c](https://linux-hardware.org/?probe=5564506d3c) | Aug 15, 2022 |
| Dell          | Latitude E5430 vPro         | [08f713e80b](https://linux-hardware.org/?probe=08f713e80b) | Aug 13, 2022 |
| HP            | EliteBook 2760p             | [bb4c1e4c3a](https://linux-hardware.org/?probe=bb4c1e4c3a) | Aug 13, 2022 |
| Acer          | Aspire A515-51G             | [f0e405bc07](https://linux-hardware.org/?probe=f0e405bc07) | Aug 13, 2022 |
| ASUSTek       | UX303LAB                    | [169419cea0](https://linux-hardware.org/?probe=169419cea0) | Aug 12, 2022 |
| HP            | ZBook 15 G4                 | [92cacb2a11](https://linux-hardware.org/?probe=92cacb2a11) | Aug 12, 2022 |
| HP            | EliteBook 2760p             | [0ce6a49a7f](https://linux-hardware.org/?probe=0ce6a49a7f) | Aug 12, 2022 |
| Lenovo        | Z710 20250                  | [8c7b1d0773](https://linux-hardware.org/?probe=8c7b1d0773) | Aug 11, 2022 |
| Lenovo        | G580 20150                  | [6a07e79eb7](https://linux-hardware.org/?probe=6a07e79eb7) | Aug 11, 2022 |
| Lenovo        | G580 20150                  | [7e83b07cca](https://linux-hardware.org/?probe=7e83b07cca) | Aug 11, 2022 |
| HP            | 255 G4                      | [3ed3978b93](https://linux-hardware.org/?probe=3ed3978b93) | Aug 11, 2022 |
| Alienware     | M17xR4                      | [a9d3769b5b](https://linux-hardware.org/?probe=a9d3769b5b) | Aug 10, 2022 |
| Dell          | Latitude 5521               | [25f117c439](https://linux-hardware.org/?probe=25f117c439) | Aug 10, 2022 |
| HP            | Pavilion HDX9200            | [079cb2197b](https://linux-hardware.org/?probe=079cb2197b) | Aug 10, 2022 |
| HP            | 255 G4                      | [44b5858d14](https://linux-hardware.org/?probe=44b5858d14) | Aug 10, 2022 |
| HP            | Compaq Presario CQ60        | [20f30b16e5](https://linux-hardware.org/?probe=20f30b16e5) | Aug 09, 2022 |
| Toshiba       | Satellite A300              | [4f83e69c06](https://linux-hardware.org/?probe=4f83e69c06) | Aug 09, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [1c9cd79646](https://linux-hardware.org/?probe=1c9cd79646) | Aug 09, 2022 |
| Lenovo        | ThinkPad L480 20LS001AMC    | [47d4f751e1](https://linux-hardware.org/?probe=47d4f751e1) | Aug 09, 2022 |
| Dell          | Latitude 3190               | [5818ff09cb](https://linux-hardware.org/?probe=5818ff09cb) | Aug 08, 2022 |
| Dell          | Vostro 3500                 | [71390cb3ec](https://linux-hardware.org/?probe=71390cb3ec) | Aug 07, 2022 |
| PC Special... | Recoil II                   | [1e05c3546f](https://linux-hardware.org/?probe=1e05c3546f) | Aug 07, 2022 |
| ASUSTek       | K52JT                       | [013f296b81](https://linux-hardware.org/?probe=013f296b81) | Aug 07, 2022 |
| MSI           | Creator Z17 A12UHST         | [ccbb6bb183](https://linux-hardware.org/?probe=ccbb6bb183) | Aug 05, 2022 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [0a34d32db6](https://linux-hardware.org/?probe=0a34d32db6) | Aug 05, 2022 |
| Lenovo        | ThinkPad T440s 20AR003SM... | [e835f1eca5](https://linux-hardware.org/?probe=e835f1eca5) | Aug 04, 2022 |
| Acer          | Aspire E5-571               | [a249c68580](https://linux-hardware.org/?probe=a249c68580) | Aug 04, 2022 |
| Fujitsu Si... | AMILO Li1705                | [87d90381e1](https://linux-hardware.org/?probe=87d90381e1) | Aug 04, 2022 |
| Dell          | Inspiron 3583               | [7f2e8ddf72](https://linux-hardware.org/?probe=7f2e8ddf72) | Aug 04, 2022 |
| ASUSTek       | G550JK                      | [e73f25c149](https://linux-hardware.org/?probe=e73f25c149) | Aug 03, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [fcef4276cb](https://linux-hardware.org/?probe=fcef4276cb) | Aug 03, 2022 |
| Lenovo        | Yoga 900-13ISK 80MK         | [1d0650ff70](https://linux-hardware.org/?probe=1d0650ff70) | Aug 03, 2022 |
| MSI           | Creator Z17 A12UHST         | [87533b4847](https://linux-hardware.org/?probe=87533b4847) | Aug 03, 2022 |
| ASUSTek       | G550JK                      | [76414b53ee](https://linux-hardware.org/?probe=76414b53ee) | Aug 03, 2022 |
| HP            | ProBook 650 G8 Notebook ... | [1b11fecca3](https://linux-hardware.org/?probe=1b11fecca3) | Aug 02, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [71c6ba6061](https://linux-hardware.org/?probe=71c6ba6061) | Aug 01, 2022 |
| Dell          | Latitude 3190               | [1f86e5fa57](https://linux-hardware.org/?probe=1f86e5fa57) | Aug 01, 2022 |
| Acer          | Aspire 5730                 | [1541bd94e2](https://linux-hardware.org/?probe=1541bd94e2) | Jul 31, 2022 |
| Acer          | Aspire V5-591G              | [80396b28bf](https://linux-hardware.org/?probe=80396b28bf) | Jul 31, 2022 |
| HP            | 550                         | [efc4b32963](https://linux-hardware.org/?probe=efc4b32963) | Jul 30, 2022 |
| Dell          | XPS M1330                   | [2abad8da86](https://linux-hardware.org/?probe=2abad8da86) | Jul 30, 2022 |
| Acer          | Aspire 5730                 | [8ac8b8a87a](https://linux-hardware.org/?probe=8ac8b8a87a) | Jul 30, 2022 |
| Dell          | Precision 5550              | [e11d4be493](https://linux-hardware.org/?probe=e11d4be493) | Jul 30, 2022 |
| Lenovo        | ThinkPad L480 20LS002CPB    | [35764371d6](https://linux-hardware.org/?probe=35764371d6) | Jul 29, 2022 |
| Dell          | Latitude E7470              | [9f4d55071c](https://linux-hardware.org/?probe=9f4d55071c) | Jul 28, 2022 |
| Dell          | Latitude 5421               | [ec91a9ea85](https://linux-hardware.org/?probe=ec91a9ea85) | Jul 27, 2022 |
| Lenovo        | G50-70 20351                | [4ddfbb6ad8](https://linux-hardware.org/?probe=4ddfbb6ad8) | Jul 26, 2022 |
| Toshiba       | Satellite L750D             | [c8e9ea3fdd](https://linux-hardware.org/?probe=c8e9ea3fdd) | Jul 26, 2022 |
| HP            | Laptop 15s-eq0xxx           | [aabcc30a17](https://linux-hardware.org/?probe=aabcc30a17) | Jul 25, 2022 |
| Dell          | Latitude 3190               | [2ec6ff1812](https://linux-hardware.org/?probe=2ec6ff1812) | Jul 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | [123fc55893](https://linux-hardware.org/?probe=123fc55893) | Jul 24, 2022 |
| Lenovo        | IdeaPad 5 Pro 16IHU6 82L... | [b16e17a798](https://linux-hardware.org/?probe=b16e17a798) | Jul 23, 2022 |
| Lenovo        | G50-30 80G0                 | [597fb27e56](https://linux-hardware.org/?probe=597fb27e56) | Jul 23, 2022 |
| Lenovo        | G50-30 80G0                 | [8b1930ddbd](https://linux-hardware.org/?probe=8b1930ddbd) | Jul 22, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [4e47525879](https://linux-hardware.org/?probe=4e47525879) | Jul 22, 2022 |
| Packard Be... | EasyNote TE11BZ             | [e1099c5342](https://linux-hardware.org/?probe=e1099c5342) | Jul 22, 2022 |
| Dell          | Inspiron MM061              | [8e0cd55a28](https://linux-hardware.org/?probe=8e0cd55a28) | Jul 22, 2022 |
| ASUSTek       | X550CL                      | [abd0b78e41](https://linux-hardware.org/?probe=abd0b78e41) | Jul 21, 2022 |
| Dell          | Latitude E6540              | [4688c6f312](https://linux-hardware.org/?probe=4688c6f312) | Jul 21, 2022 |
| HP            | EliteBook 840 G5            | [03afe0a303](https://linux-hardware.org/?probe=03afe0a303) | Jul 20, 2022 |
| HP            | 250 G6 Notebook PC          | [83d1355e61](https://linux-hardware.org/?probe=83d1355e61) | Jul 19, 2022 |
| Dell          | Latitude 3190               | [4fa9fe26c1](https://linux-hardware.org/?probe=4fa9fe26c1) | Jul 18, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [18d1378620](https://linux-hardware.org/?probe=18d1378620) | Jul 16, 2022 |
| MSI           | Creator Z17 A12UHST         | [ef0c958c66](https://linux-hardware.org/?probe=ef0c958c66) | Jul 15, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [329ce2f7f8](https://linux-hardware.org/?probe=329ce2f7f8) | Jul 15, 2022 |
| Lenovo        | G580 20150                  | [d6b737940e](https://linux-hardware.org/?probe=d6b737940e) | Jul 15, 2022 |
| HP            | Pavilion dv6700             | [4d653cf4e6](https://linux-hardware.org/?probe=4d653cf4e6) | Jul 15, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [ea97effc52](https://linux-hardware.org/?probe=ea97effc52) | Jul 14, 2022 |
| HP            | Laptop 15s-eq1xxx           | [57ef4db755](https://linux-hardware.org/?probe=57ef4db755) | Jul 14, 2022 |
| Hyperbook     | Z15 Zen                     | [41129ecc5e](https://linux-hardware.org/?probe=41129ecc5e) | Jul 14, 2022 |
| Dell          | Inspiron 3451               | [c95dd7e491](https://linux-hardware.org/?probe=c95dd7e491) | Jul 13, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [f422c77bb1](https://linux-hardware.org/?probe=f422c77bb1) | Jul 12, 2022 |
| HP            | EliteBook 8570w             | [495c5afa4b](https://linux-hardware.org/?probe=495c5afa4b) | Jul 12, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [2566bb66dd](https://linux-hardware.org/?probe=2566bb66dd) | Jul 12, 2022 |
| Dell          | Latitude E6420              | [d3bbc4a899](https://linux-hardware.org/?probe=d3bbc4a899) | Jul 12, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [6b29072d9e](https://linux-hardware.org/?probe=6b29072d9e) | Jul 11, 2022 |
| Samsung       | 905S3G/906S3G/915S3G/930... | [24dc866c51](https://linux-hardware.org/?probe=24dc866c51) | Jul 11, 2022 |
| Dell          | Latitude 3190               | [b3c7283cdb](https://linux-hardware.org/?probe=b3c7283cdb) | Jul 11, 2022 |
| HP            | ProBook 4740s               | [18ff2d02bd](https://linux-hardware.org/?probe=18ff2d02bd) | Jul 10, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [6ed9abc24e](https://linux-hardware.org/?probe=6ed9abc24e) | Jul 10, 2022 |
| Lenovo        | ThinkPad R61 8932FJG        | [d783a022b3](https://linux-hardware.org/?probe=d783a022b3) | Jul 08, 2022 |
| Dell          | Latitude D420               | [2e3ded5234](https://linux-hardware.org/?probe=2e3ded5234) | Jul 08, 2022 |
| Acer          | Aspire A715-75G             | [4a6cc98dd6](https://linux-hardware.org/?probe=4a6cc98dd6) | Jul 08, 2022 |
| MSI           | GF63 Thin 8RCS              | [886728c1b6](https://linux-hardware.org/?probe=886728c1b6) | Jul 08, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | [5cf26aa015](https://linux-hardware.org/?probe=5cf26aa015) | Jul 08, 2022 |
| Lenovo        | ThinkPad T410 2537W2L       | [a2e55ad8ac](https://linux-hardware.org/?probe=a2e55ad8ac) | Jul 07, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [c75201835c](https://linux-hardware.org/?probe=c75201835c) | Jul 06, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [4009adaca2](https://linux-hardware.org/?probe=4009adaca2) | Jul 05, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [b4732a4bda](https://linux-hardware.org/?probe=b4732a4bda) | Jul 05, 2022 |
| Lenovo        | ThinkPad P53 20QNS00Y00     | [64dc631691](https://linux-hardware.org/?probe=64dc631691) | Jul 05, 2022 |
| HP            | ProBook 6475b               | [02eab8bd42](https://linux-hardware.org/?probe=02eab8bd42) | Jul 05, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | [7d6a8718a8](https://linux-hardware.org/?probe=7d6a8718a8) | Jul 05, 2022 |
| Dell          | Latitude 7280               | [5333012df2](https://linux-hardware.org/?probe=5333012df2) | Jul 04, 2022 |
| Dell          | Latitude 3190               | [f5c0f0798a](https://linux-hardware.org/?probe=f5c0f0798a) | Jul 04, 2022 |
| Dell          | Inspiron 5567               | [740ba48457](https://linux-hardware.org/?probe=740ba48457) | Jul 03, 2022 |
| Dell          | Latitude E6420              | [e1b517f8af](https://linux-hardware.org/?probe=e1b517f8af) | Jul 03, 2022 |
| Dell          | Inspiron 3451               | [a57cf9cc46](https://linux-hardware.org/?probe=a57cf9cc46) | Jul 03, 2022 |
| ASUSTek       | X55U                        | [ed55b4ef39](https://linux-hardware.org/?probe=ed55b4ef39) | Jul 03, 2022 |
| Lenovo        | ThinkPad E470 20H1007MPB    | [7a20748cc1](https://linux-hardware.org/?probe=7a20748cc1) | Jul 03, 2022 |
| Lenovo        | ThinkPad Edge E430 3254A... | [8b717c6bdf](https://linux-hardware.org/?probe=8b717c6bdf) | Jul 02, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [10ff366630](https://linux-hardware.org/?probe=10ff366630) | Jul 01, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [2671f4ffe2](https://linux-hardware.org/?probe=2671f4ffe2) | Jul 01, 2022 |
| Lenovo        | ThinkPad T450s 20BX002NM... | [3bb2e1821b](https://linux-hardware.org/?probe=3bb2e1821b) | Jul 01, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Poland/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 340       | 11.68%  |
| OpenMandriva 4.2             | 187       | 6.42%   |
| Ubuntu 18.04                 | 166       | 5.7%    |
| Ubuntu 22.04                 | 135       | 4.64%   |
| OpenMandriva 4.3             | 107       | 3.67%   |
| Debian 11                    | 86        | 2.95%   |
| Arch Rolling                 | 55        | 1.89%   |
| ROSA R10                     | 50        | 1.72%   |
| OpenMandriva 23.01           | 49        | 1.68%   |
| Linux Mint 20.3              | 45        | 1.55%   |
| Linux Mint 20.1              | 42        | 1.44%   |
| Arch                         | 42        | 1.44%   |
| KDE neon 20.04               | 40        | 1.37%   |
| ROSA R9                      | 39        | 1.34%   |
| Fedora 37                    | 38        | 1.3%    |
| Fedora 36                    | 36        | 1.24%   |
| ROSA R11.1                   | 34        | 1.17%   |
| Manjaro                      | 34        | 1.17%   |
| Zorin 16                     | 33        | 1.13%   |
| Linux Mint 21.1              | 33        | 1.13%   |
| Linux Mint 20.2              | 33        | 1.13%   |
| Ubuntu 21.04                 | 32        | 1.1%    |
| Ubuntu 20.10                 | 32        | 1.1%    |
| Linux Mint 19.3              | 31        | 1.06%   |
| ROSA R11                     | 29        | 1%      |
| Zorin 15                     | 27        | 0.93%   |
| Ubuntu 19.10                 | 27        | 0.93%   |
| Linux Mint 20                | 27        | 0.93%   |
| Ubuntu 22.10                 | 26        | 0.89%   |
| Ubuntu 21.10                 | 26        | 0.89%   |
| Xubuntu 20.04                | 25        | 0.86%   |
| ROSA R8                      | 25        | 0.86%   |
| Linux Mint 21                | 25        | 0.86%   |
| Fedora 33                    | 25        | 0.86%   |
| Fedora 32                    | 24        | 0.82%   |
| Fedora 35                    | 23        | 0.79%   |
| Debian 10                    | 23        | 0.79%   |
| openSUSE Tumbleweed-XXXXXXXX | 22        | 0.76%   |
| Pop!_OS 20.04                | 20        | 0.69%   |
| Fedora 34                    | 20        | 0.69%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 783       | 28.56%  |
| OpenMandriva  | 367       | 13.38%  |
| Linux Mint    | 238       | 8.68%   |
| Fedora        | 183       | 6.67%   |
| ROSA          | 181       | 6.6%    |
| Debian        | 132       | 4.81%   |
| Manjaro       | 106       | 3.87%   |
| Arch          | 93        | 3.39%   |
| Pop!_OS       | 70        | 2.55%   |
| Zorin         | 63        | 2.3%    |
| KDE neon      | 54        | 1.97%   |
| Kubuntu       | 49        | 1.79%   |
| Xubuntu       | 44        | 1.6%    |
| Kali          | 37        | 1.35%   |
| Lubuntu       | 26        | 0.95%   |
| openSUSE      | 24        | 0.88%   |
| Endless       | 23        | 0.84%   |
| Elementary    | 23        | 0.84%   |
| Gentoo        | 20        | 0.73%   |
| ArcoLinux     | 20        | 0.73%   |
| LMDE          | 18        | 0.66%   |
| SteamOS       | 14        | 0.51%   |
| Clear Linux   | 13        | 0.47%   |
| EndeavourOS   | 12        | 0.44%   |
| Nobara        | 11        | 0.4%    |
| Ubuntu Unity  | 10        | 0.36%   |
| Ubuntu MATE   | 9         | 0.33%   |
| Garuda Linux  | 9         | 0.33%   |
| LinuxFX       | 8         | 0.29%   |
| Ubuntu Budgie | 7         | 0.26%   |
| Peppermint    | 7         | 0.26%   |
| MX            | 7         | 0.26%   |
| BlackPanther  | 7         | 0.26%   |
| CentOS        | 5         | 0.18%   |
| Xero          | 4         | 0.15%   |
| Parrot        | 4         | 0.15%   |
| NixOS         | 4         | 0.15%   |
| Linux Lite    | 4         | 0.15%   |
| Sparky        | 3         | 0.11%   |
| Solus         | 3         | 0.11%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002        | 177       | 5.56%   |
| 5.16.7-desktop-1omv4003         | 105       | 3.3%    |
| 6.1.1-desktop-1omv2290          | 46        | 1.44%   |
| 5.4.0-42-generic                | 44        | 1.38%   |
| 5.15.0-56-generic               | 34        | 1.07%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 26        | 0.82%   |
| 5.15.0-58-generic               | 25        | 0.78%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 24        | 0.75%   |
| 5.4.0-52-generic                | 22        | 0.69%   |
| 5.4.0-48-generic                | 22        | 0.69%   |
| 5.15.0-43-generic               | 22        | 0.69%   |
| 5.15.0-52-generic               | 21        | 0.66%   |
| 5.4.0-29-generic                | 20        | 0.63%   |
| 5.4.0-58-generic                | 19        | 0.6%    |
| 5.4.0-26-generic                | 19        | 0.6%    |
| 5.19.0-35-generic               | 19        | 0.6%    |
| 5.3.0-46-generic                | 18        | 0.56%   |
| 5.15.0-53-generic               | 18        | 0.56%   |
| 5.4.0-33-generic                | 17        | 0.53%   |
| 5.11.0-37-generic               | 17        | 0.53%   |
| 5.0.0-37-generic                | 17        | 0.53%   |
| 5.4.0-54-generic                | 16        | 0.5%    |
| 5.15.0-48-generic               | 16        | 0.5%    |
| 4.15.0-desktop-45.1rosa-x86_64  | 16        | 0.5%    |
| 4.1.34-nrj-desktop-2rosa-x86_64 | 16        | 0.5%    |
| 5.8.0-43-generic                | 15        | 0.47%   |
| 5.4.0-40-generic                | 14        | 0.44%   |
| 5.4.0-37-generic                | 14        | 0.44%   |
| 5.3.0-40-generic                | 14        | 0.44%   |
| 5.3.0-42-generic                | 13        | 0.41%   |
| 5.19.0-32-generic               | 13        | 0.41%   |
| 5.15.0-60-generic               | 13        | 0.41%   |
| 5.13.0-39-generic               | 13        | 0.41%   |
| 5.13.0-27-generic               | 13        | 0.41%   |
| 5.11.0-43-generic               | 13        | 0.41%   |
| 5.11.0-27-generic               | 13        | 0.41%   |
| 5.11.0-25-generic               | 13        | 0.41%   |
| 4.15.0-43-generic               | 13        | 0.41%   |
| 5.4.0-91-generic                | 12        | 0.38%   |
| 5.4.0-74-generic                | 12        | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 442       | 14.61%  |
| 5.15.0  | 234       | 7.74%   |
| 5.10.14 | 178       | 5.88%   |
| 4.15.0  | 148       | 4.89%   |
| 5.11.0  | 144       | 4.76%   |
| 5.8.0   | 127       | 4.2%    |
| 5.13.0  | 118       | 3.9%    |
| 5.16.7  | 106       | 3.5%    |
| 5.3.0   | 103       | 3.4%    |
| 5.10.0  | 101       | 3.34%   |
| 5.19.0  | 63        | 2.08%   |
| 5.0.0   | 61        | 2.02%   |
| 4.18.0  | 58        | 1.92%   |
| 6.1.1   | 47        | 1.55%   |
| 4.9.20  | 35        | 1.16%   |
| 4.9.60  | 32        | 1.06%   |
| 4.19.0  | 30        | 0.99%   |
| 5.14.0  | 25        | 0.83%   |
| 4.1.34  | 22        | 0.73%   |
| 6.0.0   | 17        | 0.56%   |
| 6.2.6   | 14        | 0.46%   |
| 5.11.12 | 14        | 0.46%   |
| 4.1.38  | 14        | 0.46%   |
| 5.17.0  | 12        | 0.4%    |
| 6.0.7   | 11        | 0.36%   |
| 5.9.0   | 11        | 0.36%   |
| 5.17.5  | 11        | 0.36%   |
| 5.4.32  | 10        | 0.33%   |
| 5.16.0  | 9         | 0.3%    |
| 6.1.0   | 8         | 0.26%   |
| 5.5.0   | 8         | 0.26%   |
| 5.4.83  | 8         | 0.26%   |
| 4.9.76  | 8         | 0.26%   |
| 6.1.8   | 7         | 0.23%   |
| 6.1.12  | 7         | 0.23%   |
| 6.1.10  | 7         | 0.23%   |
| 5.19.14 | 7         | 0.23%   |
| 5.18.12 | 7         | 0.23%   |
| 5.18.0  | 7         | 0.23%   |
| 5.16.11 | 7         | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 500       | 16.9%   |
| 5.10    | 330       | 11.15%  |
| 5.15    | 298       | 10.07%  |
| 5.11    | 182       | 6.15%   |
| 5.16    | 160       | 5.41%   |
| 5.8     | 158       | 5.34%   |
| 4.15    | 148       | 5%      |
| 5.13    | 135       | 4.56%   |
| 5.3     | 116       | 3.92%   |
| 6.1     | 105       | 3.55%   |
| 4.9     | 100       | 3.38%   |
| 5.19    | 99        | 3.35%   |
| 6.0     | 72        | 2.43%   |
| 5.0     | 67        | 2.26%   |
| 4.18    | 61        | 2.06%   |
| 5.14    | 55        | 1.86%   |
| 5.17    | 49        | 1.66%   |
| 5.9     | 42        | 1.42%   |
| 5.6     | 42        | 1.42%   |
| 5.18    | 39        | 1.32%   |
| 4.19    | 36        | 1.22%   |
| 4.1     | 35        | 1.18%   |
| 6.2     | 30        | 1.01%   |
| 5.12    | 25        | 0.84%   |
| 5.5     | 23        | 0.78%   |
| 5.7     | 20        | 0.68%   |
| 4.4     | 8         | 0.27%   |
| 5.1     | 6         | 0.2%    |
| 5.2     | 4         | 0.14%   |
| 3.10    | 4         | 0.14%   |
| 4.20    | 2         | 0.07%   |
| 4.13    | 2         | 0.07%   |
| 4.10    | 2         | 0.07%   |
| 4.17    | 1         | 0.03%   |
| 4.14    | 1         | 0.03%   |
| 4.12    | 1         | 0.03%   |
| 4.11    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 2535      | 95.95%  |
| i686    | 106       | 4.01%   |
| aarch64 | 1         | 0.04%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 1035      | 37.39%  |
| KDE5            | 666       | 24.06%  |
| Unknown         | 256       | 9.25%   |
| XFCE            | 189       | 6.83%   |
| X-Cinnamon      | 170       | 6.14%   |
| KDE4            | 97        | 3.5%    |
| KDE             | 71        | 2.57%   |
| MATE            | 63        | 2.28%   |
| Cinnamon        | 42        | 1.52%   |
| LXQt            | 41        | 1.48%   |
| LXDE            | 36        | 1.3%    |
| Pantheon        | 22        | 0.79%   |
| i3              | 15        | 0.54%   |
| Budgie          | 14        | 0.51%   |
| Unity           | 12        | 0.43%   |
| Deepin          | 9         | 0.33%   |
| GNOME Flashback | 6         | 0.22%   |
| sway            | 3         | 0.11%   |
| GNOME Classic   | 3         | 0.11%   |
| awesome         | 3         | 0.11%   |
| Trinity         | 2         | 0.07%   |
| qtile           | 2         | 0.07%   |
| Hyprland        | 2         | 0.07%   |
| Fluxbox         | 2         | 0.07%   |
| DWM             | 2         | 0.07%   |
| stumpwm         | 1         | 0.04%   |
| qt5ct           | 1         | 0.04%   |
| openbox         | 1         | 0.04%   |
| icewm           | 1         | 0.04%   |
| GNUstep         | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2156      | 79.26%  |
| Wayland | 405       | 14.89%  |
| Unknown | 131       | 4.82%   |
| Tty     | 28        | 1.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1118      | 40.49%  |
| SDDM    | 643       | 23.29%  |
| GDM     | 343       | 12.42%  |
| GDM3    | 233       | 8.44%   |
| LightDM | 217       | 7.86%   |
| KDM     | 99        | 3.59%   |
| TDM     | 95        | 3.44%   |
| XDM     | 5         | 0.18%   |
| NODM    | 2         | 0.07%   |
| Ly      | 2         | 0.07%   |
| SLIMSKI | 1         | 0.04%   |
| SLiM    | 1         | 0.04%   |
| MDM     | 1         | 0.04%   |
| LXDM    | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| pl_PL   | 1441      | 52.82%  |
| en_US   | 736       | 26.98%  |
| Unknown | 372       | 13.64%  |
| en_GB   | 73        | 2.68%   |
| C       | 44        | 1.61%   |
| ru_RU   | 16        | 0.59%   |
| szl_PL  | 9         | 0.33%   |
| de_DE   | 5         | 0.18%   |
| uk_UA   | 4         | 0.15%   |
| fr_FR   | 3         | 0.11%   |
| en_IE   | 3         | 0.11%   |
| ru_UA   | 2         | 0.07%   |
| nl_NL   | 2         | 0.07%   |
| it_IT   | 2         | 0.07%   |
| hu_HU   | 2         | 0.07%   |
| en_DK   | 2         | 0.07%   |
| C.UTF8  | 2         | 0.07%   |
| sk_SK   | 1         | 0.04%   |
| POSIX   | 1         | 0.04%   |
| es_ES   | 1         | 0.04%   |
| es_AR   | 1         | 0.04%   |
| en_IN   | 1         | 0.04%   |
| en_CA   | 1         | 0.04%   |
| en_AU   | 1         | 0.04%   |
| en_AG   | 1         | 0.04%   |
| af_ZA   | 1         | 0.04%   |
| aa_DJ   | 1         | 0.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 1397      | 51.88%  |
| EFI  | 1296      | 48.12%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 1894      | 69.63%  |
| Overlay  | 347       | 12.76%  |
| Btrfs    | 225       | 8.27%   |
| Unknown  | 173       | 6.36%   |
| Xfs      | 38        | 1.4%    |
| Zfs      | 21        | 0.77%   |
| F2fs     | 9         | 0.33%   |
| Rootfs   | 3         | 0.11%   |
| Ext3     | 3         | 0.11%   |
| Ext2     | 3         | 0.11%   |
| Tmpfs    | 2         | 0.07%   |
| XXXXX    | 1         | 0.04%   |
| Bcachefs | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1263      | 46.59%  |
| GPT     | 1001      | 36.92%  |
| MBR     | 447       | 16.49%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2280      | 84.7%   |
| Yes       | 412       | 15.3%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1819      | 67.7%   |
| Yes       | 868       | 32.3%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 693       | 26.27%  |
| Dell                | 564       | 21.38%  |
| Hewlett-Packard     | 399       | 15.13%  |
| ASUSTek Computer    | 313       | 11.87%  |
| Acer                | 171       | 6.48%   |
| Samsung Electronics | 73        | 2.77%   |
| Toshiba             | 72        | 2.73%   |
| MSI                 | 61        | 2.31%   |
| Sony                | 37        | 1.4%    |
| HUAWEI              | 28        | 1.06%   |
| Apple               | 24        | 0.91%   |
| Fujitsu             | 22        | 0.83%   |
| Fujitsu Siemens     | 20        | 0.76%   |
| Valve               | 13        | 0.49%   |
| Notebook            | 13        | 0.49%   |
| Google              | 13        | 0.49%   |
| Packard Bell        | 12        | 0.45%   |
| Kiano               | 9         | 0.34%   |
| eMachines           | 9         | 0.34%   |
| Medion              | 8         | 0.3%    |
| Timi                | 7         | 0.27%   |
| Unknown             | 6         | 0.23%   |
| Kruger&Matz         | 4         | 0.15%   |
| Gigabyte Technology | 4         | 0.15%   |
| Alienware           | 4         | 0.15%   |
| mPTech              | 3         | 0.11%   |
| Clevo               | 3         | 0.11%   |
| Chuwi               | 3         | 0.11%   |
| TrekStor            | 2         | 0.08%   |
| Teclast             | 2         | 0.08%   |
| System76            | 2         | 0.08%   |
| Star Labs           | 2         | 0.08%   |
| Schenker            | 2         | 0.08%   |
| Panasonic           | 2         | 0.08%   |
| MODECOM             | 2         | 0.08%   |
| MAXDATA             | 2         | 0.08%   |
| Maibenben           | 2         | 0.08%   |
| Intel               | 2         | 0.08%   |
| IBM                 | 2         | 0.08%   |
| GPU Company         | 2         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Dell Inspiron 3451                   | 31        | 1.18%   |
| Unknown                              | 27        | 1.02%   |
| Dell Latitude E6400                  | 15        | 0.57%   |
| Dell Latitude E6540                  | 14        | 0.53%   |
| Valve Jupiter                        | 13        | 0.49%   |
| Lenovo G50-30 80G0                   | 12        | 0.45%   |
| Dell Latitude 5480                   | 12        | 0.45%   |
| Dell Latitude E6430                  | 11        | 0.42%   |
| Dell Latitude D630                   | 11        | 0.42%   |
| HP Pavilion dv7                      | 10        | 0.38%   |
| Dell Latitude 5490                   | 10        | 0.38%   |
| Dell Latitude E7440                  | 9         | 0.34%   |
| Dell Latitude E6420                  | 9         | 0.34%   |
| ASUS X555LJ                          | 9         | 0.34%   |
| Lenovo Legion Y530-15ICH 81FV        | 8         | 0.3%    |
| Lenovo G580 20150                    | 8         | 0.3%    |
| Lenovo G510 20238                    | 8         | 0.3%    |
| HP Pavilion Gaming Laptop 15-ec1xxx  | 8         | 0.3%    |
| HP Pavilion dv6                      | 8         | 0.3%    |
| HP Notebook                          | 8         | 0.3%    |
| HP 15                                | 8         | 0.3%    |
| Dell Latitude 5420                   | 8         | 0.3%    |
| Lenovo Legion Y540-15IRH 81SX        | 7         | 0.27%   |
| Lenovo G50-80 80E5                   | 7         | 0.27%   |
| HP EliteBook 6930p                   | 7         | 0.27%   |
| HP 250 G6 Notebook PC                | 7         | 0.27%   |
| Dell Latitude E7450                  | 7         | 0.27%   |
| Dell Latitude E6330                  | 7         | 0.27%   |
| Dell Latitude E5430 non-vPro         | 7         | 0.27%   |
| Dell Latitude 5511                   | 7         | 0.27%   |
| Toshiba Satellite A300               | 6         | 0.23%   |
| Samsung 550P5C/550P7C                | 6         | 0.23%   |
| Samsung 350V5C/351V5C/3540VC/3440VC  | 6         | 0.23%   |
| Lenovo Z51-70 80K6                   | 6         | 0.23%   |
| Lenovo Y520-15IKBN 80WK              | 6         | 0.23%   |
| Lenovo Legion 5 15ARH05 82B5         | 6         | 0.23%   |
| Lenovo IdeaPad Y700-15ISK 80NV       | 6         | 0.23%   |
| Lenovo IdeaPad Y510P 20217           | 6         | 0.23%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY | 6         | 0.23%   |
| Lenovo IdeaPad 100-15IBY 80MJ        | 6         | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 313       | 11.87%  |
| Dell Latitude         | 297       | 11.26%  |
| Dell Inspiron         | 144       | 5.46%   |
| Lenovo IdeaPad        | 140       | 5.31%   |
| Acer Aspire           | 108       | 4.09%   |
| HP EliteBook          | 86        | 3.26%   |
| HP Pavilion           | 85        | 3.22%   |
| HP ProBook            | 62        | 2.35%   |
| Toshiba Satellite     | 58        | 2.2%    |
| Lenovo Legion         | 47        | 1.78%   |
| ASUS VivoBook         | 36        | 1.36%   |
| Dell Precision        | 35        | 1.33%   |
| HP Laptop             | 32        | 1.21%   |
| Dell Vostro           | 30        | 1.14%   |
| Dell XPS              | 29        | 1.1%    |
| Unknown               | 27        | 1.02%   |
| HP Compaq             | 20        | 0.76%   |
| Fujitsu LIFEBOOK      | 20        | 0.76%   |
| HP 250                | 19        | 0.72%   |
| ASUS ASUS             | 19        | 0.72%   |
| ASUS TUF              | 17        | 0.64%   |
| HP ZBook              | 16        | 0.61%   |
| ASUS ROG              | 16        | 0.61%   |
| Acer Extensa          | 15        | 0.57%   |
| Lenovo ThinkBook      | 14        | 0.53%   |
| Valve Jupiter         | 13        | 0.49%   |
| Packard Bell EasyNote | 12        | 0.45%   |
| Lenovo G50-30         | 12        | 0.45%   |
| Acer TravelMate       | 12        | 0.45%   |
| Lenovo Yoga           | 11        | 0.42%   |
| HP OMEN               | 11        | 0.42%   |
| Acer Nitro            | 11        | 0.42%   |
| Lenovo G580           | 10        | 0.38%   |
| Lenovo G50-80         | 9         | 0.34%   |
| ASUS X555LJ           | 9         | 0.34%   |
| Acer Swift            | 9         | 0.34%   |
| Lenovo G510           | 8         | 0.3%    |
| HP Notebook           | 8         | 0.3%    |
| HP 15                 | 8         | 0.3%    |
| Fujitsu Siemens AMILO | 8         | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 227       | 8.61%   |
| 2012    | 225       | 8.53%   |
| 2013    | 219       | 8.3%    |
| 2011    | 216       | 8.19%   |
| 2020    | 213       | 8.07%   |
| 2018    | 182       | 6.9%    |
| 2014    | 178       | 6.75%   |
| 2008    | 172       | 6.52%   |
| 2015    | 168       | 6.37%   |
| 2021    | 145       | 5.5%    |
| 2017    | 143       | 5.42%   |
| 2010    | 139       | 5.27%   |
| 2016    | 119       | 4.51%   |
| 2007    | 104       | 3.94%   |
| 2009    | 93        | 3.53%   |
| 2022    | 54        | 2.05%   |
| 2006    | 33        | 1.25%   |
| 2005    | 3         | 0.11%   |
| 2023    | 2         | 0.08%   |
| 2004    | 2         | 0.08%   |
| Unknown | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2638      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 2441      | 91.8%   |
| Enabled  | 218       | 8.2%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2623      | 99.43%  |
| Yes  | 15        | 0.57%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 675       | 25.27%  |
| 4.01-8.0    | 632       | 23.66%  |
| 8.01-16.0   | 445       | 16.66%  |
| 16.01-24.0  | 425       | 15.91%  |
| 32.01-64.0  | 217       | 8.12%   |
| 1.01-2.0    | 120       | 4.49%   |
| 2.01-3.0    | 85        | 3.18%   |
| 24.01-32.0  | 29        | 1.09%   |
| 64.01-256.0 | 23        | 0.86%   |
| 0.51-1.0    | 20        | 0.75%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1105      | 37.42%  |
| 2.01-3.0   | 658       | 22.28%  |
| 4.01-8.0   | 394       | 13.34%  |
| 3.01-4.0   | 365       | 12.36%  |
| 0.51-1.0   | 248       | 8.4%    |
| 8.01-16.0  | 132       | 4.47%   |
| 0.01-0.5   | 30        | 1.02%   |
| 16.01-24.0 | 15        | 0.51%   |
| 24.01-32.0 | 6         | 0.2%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1967      | 72.74%  |
| 2      | 613       | 22.67%  |
| 3      | 73        | 2.7%    |
| 0      | 38        | 1.41%   |
| 4      | 11        | 0.41%   |
| 5      | 2         | 0.07%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1562      | 58.59%  |
| Yes       | 1104      | 41.41%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2310      | 87.2%   |
| No        | 339       | 12.8%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2600      | 98.45%  |
| No        | 41        | 1.55%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2026      | 75.48%  |
| No        | 658       | 24.52%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Poland  | 2638      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Warsaw                 | 620       | 21.78%  |
| Krakow                 | 231       | 8.11%   |
| Wroclaw                | 169       | 5.94%   |
| Poznan                 | 154       | 5.41%   |
| Lodz                   | 97        | 3.41%   |
| Gdansk                 | 93        | 3.27%   |
| Katowice               | 73        | 2.56%   |
| Lublin                 | 37        | 1.3%    |
| Gdynia                 | 32        | 1.12%   |
| Szczecin               | 30        | 1.05%   |
| Rzeszów               | 23        | 0.81%   |
| Bialystok              | 23        | 0.81%   |
| Torun                  | 22        | 0.77%   |
| Ruda Śląska          | 22        | 0.77%   |
| Częstochowa           | 22        | 0.77%   |
| Bydgoszcz              | 22        | 0.77%   |
| Gliwice                | 20        | 0.7%    |
| Elblag                 | 19        | 0.67%   |
| Bytom                  | 16        | 0.56%   |
| Sosnowiec              | 14        | 0.49%   |
| Olsztyn                | 14        | 0.49%   |
| Kielce                 | 14        | 0.49%   |
| Płock                 | 13        | 0.46%   |
| Opole                  | 13        | 0.46%   |
| Chorzów               | 13        | 0.46%   |
| Tarnów                | 12        | 0.42%   |
| Blizniew               | 11        | 0.39%   |
| Siemianowice Śląskie | 10        | 0.35%   |
| Pruszków              | 10        | 0.35%   |
| Zabrze                 | 9         | 0.32%   |
| Tychy                  | 9         | 0.32%   |
| Rybnik                 | 8         | 0.28%   |
| Gorzów Wielkopolski   | 8         | 0.28%   |
| Bielsko-Biala          | 8         | 0.28%   |
| Zielona Góra          | 7         | 0.25%   |
| Skawina                | 7         | 0.25%   |
| Mielec                 | 7         | 0.25%   |
| Chojnice               | 7         | 0.25%   |
| Wejherowo              | 6         | 0.21%   |
| Tarnowskie Gory        | 6         | 0.21%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 467       | 619    | 14.19%  |
| Seagate             | 390       | 484    | 11.85%  |
| WDC                 | 361       | 445    | 10.97%  |
| Toshiba             | 221       | 275    | 6.72%   |
| GOODRAM             | 210       | 267    | 6.38%   |
| Unknown             | 156       | 198    | 4.74%   |
| SanDisk             | 149       | 186    | 4.53%   |
| Hitachi             | 127       | 151    | 3.86%   |
| Kingston            | 124       | 166    | 3.77%   |
| SK hynix            | 119       | 151    | 3.62%   |
| Intel               | 118       | 149    | 3.59%   |
| A-DATA Technology   | 115       | 135    | 3.5%    |
| Crucial             | 113       | 163    | 3.43%   |
| HGST                | 71        | 89     | 2.16%   |
| Micron Technology   | 69        | 89     | 2.1%    |
| KIOXIA              | 34        | 38     | 1.03%   |
| SPCC                | 30        | 36     | 0.91%   |
| Patriot             | 27        | 35     | 0.82%   |
| Plextor             | 25        | 38     | 0.76%   |
| PNY                 | 24        | 25     | 0.73%   |
| Fujitsu             | 21        | 22     | 0.64%   |
| LITEON              | 18        | 22     | 0.55%   |
| Transcend           | 16        | 17     | 0.49%   |
| Phison              | 13        | 18     | 0.4%    |
| LITEONIT            | 13        | 15     | 0.4%    |
| China               | 13        | 16     | 0.4%    |
| KIOXIA-EXCERIA      | 12        | 13     | 0.36%   |
| Apacer              | 12        | 19     | 0.36%   |
| Phison Electronics  | 11        | 11     | 0.33%   |
| Apple               | 10        | 12     | 0.3%    |
| Silicon Motion      | 9         | 11     | 0.27%   |
| OCZ                 | 8         | 8      | 0.24%   |
| JMicron Technology  | 8         | 8      | 0.24%   |
| Lenovo              | 7         | 9      | 0.21%   |
| HUAWEI              | 7         | 9      | 0.21%   |
| Unknown             | 7         | 9      | 0.21%   |
| Union Memory        | 6         | 9      | 0.18%   |
| XPG                 | 5         | 6      | 0.15%   |
| Lite-On             | 5         | 6      | 0.15%   |
| Lexar               | 5         | 5      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST500LT012-1DG142 500GB                     | 55        | 1.61%   |
| Seagate ST1000LM035-1RK172 1TB                      | 46        | 1.35%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 40        | 1.17%   |
| Intel NVMe SSD Drive 512GB                          | 25        | 0.73%   |
| Unknown MMC Card  32GB                              | 24        | 0.7%    |
| Toshiba MQ01ABD100 1TB                              | 24        | 0.7%    |
| Seagate ST9500325AS 500GB                           | 24        | 0.7%    |
| GOODRAM SSDPR-CX400-256-G2 256GB                    | 24        | 0.7%    |
| GOODRAM SSD 120GB                                   | 23        | 0.68%   |
| Crucial CT500MX500SSD1 500GB                        | 23        | 0.68%   |
| Samsung NVMe SSD Drive 512GB                        | 21        | 0.62%   |
| Kingston SA400S37240G 240GB SSD                     | 21        | 0.62%   |
| HGST HTS721010A9E630 1TB                            | 19        | 0.56%   |
| Crucial CT1000MX500SSD1 1TB                         | 19        | 0.56%   |
| Unknown MMC Card  64GB                              | 18        | 0.53%   |
| Toshiba MQ01ABF050 500GB                            | 18        | 0.53%   |
| Samsung SSD 860 EVO 500GB                           | 18        | 0.53%   |
| Samsung SSD 850 EVO 250GB                           | 18        | 0.53%   |
| Intel SSDPEKNW512G8H 512GB                          | 18        | 0.53%   |
| SanDisk NVMe SSD Drive 512GB                        | 17        | 0.5%    |
| GOODRAM SSD 240GB                                   | 16        | 0.47%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 15        | 0.44%   |
| GOODRAM SSDPR-CX400-512 512GB                       | 15        | 0.44%   |
| WDC WD10JPCX-24UE4T0 1TB                            | 14        | 0.41%   |
| Seagate Expansion+ 2TB                              | 14        | 0.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 14        | 0.41%   |
| HGST HTS725050A7E630 500GB                          | 14        | 0.41%   |
| GOODRAM SSDPR-CX400-512-G2 512GB                    | 14        | 0.41%   |
| GOODRAM SSDPR-CX400-256 256GB                       | 13        | 0.38%   |
| Crucial CT240BX500SSD1 240GB                        | 13        | 0.38%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 12        | 0.35%   |
| SK hynix NVMe SSD Drive 512GB                       | 12        | 0.35%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 12        | 0.35%   |
| Patriot Burst 120GB SSD                             | 12        | 0.35%   |
| HGST HTS545050A7E680 500GB                          | 12        | 0.35%   |
| A-DATA SU800 256GB SSD                              | 12        | 0.35%   |
| Toshiba NVMe SSD Drive 512GB                        | 11        | 0.32%   |
| Seagate ST1000LM014-SSHD-8GB                        | 11        | 0.32%   |
| SanDisk SDSSDA240G 240GB                            | 11        | 0.32%   |
| Samsung SSD 860 EVO 250GB                           | 11        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 387       | 479    | 36.68%  |
| WDC                 | 245       | 296    | 23.22%  |
| Toshiba             | 149       | 184    | 14.12%  |
| Hitachi             | 127       | 151    | 12.04%  |
| HGST                | 71        | 89     | 6.73%   |
| Samsung Electronics | 33        | 34     | 3.13%   |
| Fujitsu             | 21        | 22     | 1.99%   |
| Unknown             | 5         | 5      | 0.47%   |
| ASMT                | 5         | 5      | 0.47%   |
| USB3.0              | 3         | 3      | 0.28%   |
| ASMedia             | 3         | 3      | 0.28%   |
| StoreJet            | 1         | 1      | 0.09%   |
| SAGE                | 1         | 1      | 0.09%   |
| PHD 3.0             | 1         | 1      | 0.09%   |
| LaCie               | 1         | 2      | 0.09%   |
| IBM/Hitachi         | 1         | 1      | 0.09%   |
| Apple               | 1         | 1      | 0.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 221       | 286    | 17.62%  |
| GOODRAM             | 207       | 264    | 16.51%  |
| Crucial             | 109       | 158    | 8.69%   |
| A-DATA Technology   | 97        | 115    | 7.74%   |
| Kingston            | 96        | 126    | 7.66%   |
| SanDisk             | 90        | 113    | 7.18%   |
| WDC                 | 52        | 59     | 4.15%   |
| Intel               | 34        | 39     | 2.71%   |
| SK hynix            | 33        | 42     | 2.63%   |
| Micron Technology   | 31        | 40     | 2.47%   |
| Toshiba             | 30        | 33     | 2.39%   |
| SPCC                | 28        | 34     | 2.23%   |
| Patriot             | 25        | 33     | 1.99%   |
| Plextor             | 22        | 35     | 1.75%   |
| LITEON              | 18        | 22     | 1.44%   |
| PNY                 | 17        | 18     | 1.36%   |
| Transcend           | 15        | 16     | 1.2%    |
| LITEONIT            | 13        | 15     | 1.04%   |
| China               | 13        | 16     | 1.04%   |
| KIOXIA-EXCERIA      | 11        | 12     | 0.88%   |
| Apacer              | 10        | 17     | 0.8%    |
| OCZ                 | 8         | 8      | 0.64%   |
| JMicron Technology  | 7         | 7      | 0.56%   |
| Apple               | 6         | 6      | 0.48%   |
| KingSpec            | 4         | 5      | 0.32%   |
| 2-Power             | 3         | 3      | 0.24%   |
| Unknown             | 3         | 3      | 0.24%   |
| Union Memory        | 2         | 3      | 0.16%   |
| Team                | 2         | 2      | 0.16%   |
| Ramaxel Technology  | 2         | 3      | 0.16%   |
| Netac               | 2         | 3      | 0.16%   |
| Micron_1            | 2         | 2      | 0.16%   |
| Intenso             | 2         | 2      | 0.16%   |
| HS-SSD-C100         | 2         | 4      | 0.16%   |
| Gigabyte Technology | 2         | 3      | 0.16%   |
| Corsair             | 2         | 2      | 0.16%   |
| BIWIN               | 2         | 2      | 0.16%   |
| Wolf                | 1         | 2      | 0.08%   |
| WDC WDS2            | 1         | 1      | 0.08%   |
| W800SH              | 1         | 1      | 0.08%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 1146      | 1583   | 36.98%  |
| HDD     | 1012      | 1278   | 32.66%  |
| NVMe    | 762       | 1045   | 24.59%  |
| MMC     | 145       | 183    | 4.68%   |
| Unknown | 34        | 43     | 1.1%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1921      | 2772   | 65.36%  |
| NVMe | 762       | 1041   | 25.93%  |
| MMC  | 145       | 183    | 4.93%   |
| SAS  | 111       | 136    | 3.78%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1568      | 2130   | 73.79%  |
| 0.51-1.0   | 497       | 656    | 23.39%  |
| 1.01-2.0   | 50        | 62     | 2.35%   |
| 4.01-10.0  | 5         | 5      | 0.24%   |
| 2.01-3.0   | 3         | 6      | 0.14%   |
| 3.01-4.0   | 2         | 2      | 0.09%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 851       | 30.21%  |
| 251-500        | 629       | 22.33%  |
| 1-20           | 360       | 12.78%  |
| 501-1000       | 306       | 10.86%  |
| 51-100         | 244       | 8.66%   |
| 21-50          | 128       | 4.54%   |
| 1001-2000      | 126       | 4.47%   |
| Unknown        | 108       | 3.83%   |
| 2001-3000      | 36        | 1.28%   |
| More than 3000 | 29        | 1.03%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1260      | 43.17%  |
| 21-50          | 476       | 16.31%  |
| 101-250        | 380       | 13.02%  |
| 51-100         | 372       | 12.74%  |
| 251-500        | 161       | 5.52%   |
| Unknown        | 108       | 3.7%    |
| 501-1000       | 107       | 3.67%   |
| 1001-2000      | 41        | 1.4%    |
| 2001-3000      | 9         | 0.31%   |
| More than 3000 | 5         | 0.17%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                      | 9         | 9      | 3%      |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 8         | 9      | 2.67%   |
| Seagate ST500LT012-9WS142 500GB                | 7         | 26     | 2.33%   |
| Seagate ST500LT012-1DG142 500GB                | 6         | 9      | 2%      |
| HGST HTS545050A7E680 500GB                     | 5         | 5      | 1.67%   |
| WDC WD5000BEVT-22ZAT0 500GB                    | 4         | 4      | 1.33%   |
| WDC WD10JPVX-22JC3T0 1TB                       | 4         | 4      | 1.33%   |
| Hitachi HTS541612J9SA00 120GB                  | 4         | 5      | 1.33%   |
| WDC WD3200BPVT-80ZEST0 320GB                   | 3         | 3      | 1%      |
| Toshiba MQ01ABD100 1TB                         | 3         | 4      | 1%      |
| Toshiba MK1246GSX 120GB                        | 3         | 3      | 1%      |
| SK hynix PC711 HFS512GDE9X073N 512GB           | 3         | 3      | 1%      |
| Seagate ST9500420AS 500GB                      | 3         | 3      | 1%      |
| Seagate ST9320325AS 320GB                      | 3         | 3      | 1%      |
| Seagate ST9250827AS 250GB                      | 3         | 3      | 1%      |
| Seagate ST9250410AS 250GB                      | 3         | 3      | 1%      |
| Seagate ST320LT020-9YG142 320GB                | 3         | 3      | 1%      |
| Seagate ST1000LM014-1EJ164 1TB                 | 3         | 4      | 1%      |
| WDC WD7500BPKT-22PK4T0 752GB                   | 2         | 2      | 0.67%   |
| WDC WD1600BEVT-75A23T0 160GB                   | 2         | 2      | 0.67%   |
| WDC WD1600BEVT-22A23T0 160GB                   | 2         | 2      | 0.67%   |
| Toshiba MK5075GSX 500GB                        | 2         | 2      | 0.67%   |
| Toshiba MK3265GSX 320GB                        | 2         | 2      | 0.67%   |
| Toshiba MK1637GSX 160GB                        | 2         | 2      | 0.67%   |
| Seagate ST980811AS 80GB                        | 2         | 2      | 0.67%   |
| Seagate ST9250315AS 250GB                      | 2         | 2      | 0.67%   |
| Seagate ST9160821AS 160GB                      | 2         | 3      | 0.67%   |
| Seagate ST500LM012 HN-M500MBB 500GB            | 2         | 2      | 0.67%   |
| Seagate ST1000LM014-SSHD-8GB                   | 2         | 2      | 0.67%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD            | 2         | 2      | 0.67%   |
| Samsung Electronics HM250HI 250GB              | 2         | 2      | 0.67%   |
| Micron Technology 1100_MTFDDAK256TBN 256GB SSD | 2         | 2      | 0.67%   |
| LITEONIT LCT-256M3S 2.5 7mm 256GB SSD          | 2         | 2      | 0.67%   |
| Kingston SV300S37A120G 120GB SSD               | 2         | 2      | 0.67%   |
| Hitachi HTS725050A9A364 500GB                  | 2         | 3      | 0.67%   |
| Hitachi HTS545050A7E380 500GB                  | 2         | 2      | 0.67%   |
| Hitachi HTS543232A7A384 320GB                  | 2         | 3      | 0.67%   |
| Hitachi HTS543225L9SA00 250GB                  | 2         | 2      | 0.67%   |
| Hitachi HTS543225L9A300 250GB                  | 2         | 2      | 0.67%   |
| Hitachi HTS542516K9SA00 160GB                  | 2         | 2      | 0.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 77        | 105    | 25.75%  |
| WDC                 | 38        | 39     | 12.71%  |
| Toshiba             | 37        | 47     | 12.37%  |
| Hitachi             | 32        | 37     | 10.7%   |
| Samsung Electronics | 18        | 19     | 6.02%   |
| A-DATA Technology   | 17        | 19     | 5.69%   |
| HGST                | 15        | 16     | 5.02%   |
| SK hynix            | 8         | 8      | 2.68%   |
| SanDisk             | 8         | 9      | 2.68%   |
| Kingston            | 6         | 6      | 2.01%   |
| Intel               | 6         | 6      | 2.01%   |
| Micron Technology   | 5         | 5      | 1.67%   |
| Fujitsu             | 4         | 4      | 1.34%   |
| Crucial             | 4         | 8      | 1.34%   |
| LITEONIT            | 3         | 3      | 1%      |
| LITEON              | 3         | 3      | 1%      |
| ASMedia             | 3         | 3      | 1%      |
| Patriot             | 2         | 4      | 0.67%   |
| OCZ                 | 2         | 2      | 0.67%   |
| China               | 2         | 2      | 0.67%   |
| SPCC                | 1         | 1      | 0.33%   |
| RENICE              | 1         | 1      | 0.33%   |
| Plextor             | 1         | 1      | 0.33%   |
| Platinet            | 1         | 1      | 0.33%   |
| Lexar               | 1         | 1      | 0.33%   |
| Lenovo              | 1         | 1      | 0.33%   |
| KingSpec            | 1         | 1      | 0.33%   |
| Apple               | 1         | 1      | 0.33%   |
| Apacer              | 1         | 1      | 0.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 77        | 105    | 36.49%  |
| WDC                 | 36        | 37     | 17.06%  |
| Toshiba             | 34        | 44     | 16.11%  |
| Hitachi             | 32        | 37     | 15.17%  |
| HGST                | 15        | 16     | 7.11%   |
| Samsung Electronics | 10        | 10     | 4.74%   |
| Fujitsu             | 4         | 4      | 1.9%    |
| ASMedia             | 3         | 3      | 1.42%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 209       | 256    | 70.85%  |
| SSD  | 72        | 82     | 24.41%  |
| NVMe | 14        | 16     | 4.75%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD800BEVS-75RST0 80GB       | 1         | 1      | 20%     |
| WDC WD3200BEKT-75PVMT1 320GB    | 1         | 1      | 20%     |
| WDC WD2500BEVS-22UST0 250GB     | 1         | 1      | 20%     |
| Toshiba MK3265GSXN 320GB        | 1         | 1      | 20%     |
| Seagate ST320LT020-9YG142 320GB | 1         | 1      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 3      | 60%     |
| Toshiba | 1         | 1      | 20%     |
| Seagate | 1         | 1      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1331      | 2083   | 47.3%   |
| Works    | 1189      | 1690   | 42.25%  |
| Malfunc  | 289       | 354    | 10.27%  |
| Failed   | 5         | 5      | 0.18%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2038      | 66.6%   |
| AMD                              | 246       | 8.04%   |
| Samsung Electronics              | 229       | 7.48%   |
| SanDisk                          | 118       | 3.86%   |
| SK hynix                         | 86        | 2.81%   |
| Toshiba America Info Systems     | 46        | 1.5%    |
| Phison Electronics               | 38        | 1.24%   |
| Micron Technology                | 38        | 1.24%   |
| KIOXIA                           | 37        | 1.21%   |
| Kingston Technology Company      | 32        | 1.05%   |
| ADATA Technology                 | 24        | 0.78%   |
| Nvidia                           | 19        | 0.62%   |
| Silicon Motion                   | 17        | 0.56%   |
| Union Memory (Shenzhen)          | 14        | 0.46%   |
| Silicon Integrated Systems [SiS] | 11        | 0.36%   |
| Lite-On Technology               | 9         | 0.29%   |
| Realtek Semiconductor            | 8         | 0.26%   |
| Micron/Crucial Technology        | 8         | 0.26%   |
| Solid State Storage Technology   | 7         | 0.23%   |
| Lenovo                           | 7         | 0.23%   |
| VIA Technologies                 | 5         | 0.16%   |
| JMicron Technology               | 5         | 0.16%   |
| Shenzhen Longsys Electronics     | 4         | 0.13%   |
| MAXIO Technology (Hangzhou)      | 4         | 0.13%   |
| Yangtze Memory Technologies      | 2         | 0.07%   |
| Apple                            | 2         | 0.07%   |
| Silicon Image                    | 1         | 0.03%   |
| O2 Micro                         | 1         | 0.03%   |
| Marvell Technology Group         | 1         | 0.03%   |
| Biwin Storage Technology         | 1         | 0.03%   |
| ASMedia Technology               | 1         | 0.03%   |
| Unknown                          | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 221       | 6.55%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 202       | 5.99%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 177       | 5.25%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 159       | 4.71%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 158       | 4.68%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 129       | 3.82%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 112       | 3.32%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 111       | 3.29%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 102       | 3.02%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 96        | 2.85%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 94        | 2.79%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 86        | 2.55%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 76        | 2.25%   |
| Intel Volume Management Device NVMe RAID Controller                            | 73        | 2.16%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 72        | 2.13%   |
| Samsung NVMe SSD Controller 980                                                | 70        | 2.08%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 67        | 1.99%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 65        | 1.93%   |
| Intel SSD 660P Series                                                          | 57        | 1.69%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 54        | 1.6%    |
| Micron NVMe Storage Controller                                                 | 38        | 1.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 38        | 1.13%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 37        | 1.1%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 37        | 1.1%    |
| KIOXIA NVMe SSD Controller BG4                                                 | 34        | 1.01%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 31        | 0.92%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 29        | 0.86%   |
| Intel Tiger Lake-LP SATA Controller                                            | 27        | 0.8%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 27        | 0.8%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 24        | 0.71%   |
| Intel Comet Lake SATA AHCI Controller                                          | 23        | 0.68%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 23        | 0.68%   |
| SK hynix BC511                                                                 | 22        | 0.65%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 22        | 0.65%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 22        | 0.65%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 22        | 0.65%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 22        | 0.65%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 20        | 0.59%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 19        | 0.56%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 18        | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1891      | 58.95%  |
| NVMe | 771       | 24.03%  |
| IDE  | 303       | 9.45%   |
| RAID | 243       | 7.57%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 2244      | 85.06%  |
| AMD          | 392       | 14.86%  |
| QUALCOMM     | 1         | 0.04%   |
| CentaurHauls | 1         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron CPU N2840 @ 2.16GHz             | 49        | 1.86%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 43        | 1.63%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 38        | 1.44%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 36        | 1.36%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 35        | 1.33%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 34        | 1.29%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 33        | 1.25%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 33        | 1.25%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 33        | 1.25%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 30        | 1.14%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 29        | 1.1%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 29        | 1.1%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 29        | 1.1%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 26        | 0.98%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 26        | 0.98%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 26        | 0.98%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 24        | 0.91%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 23        | 0.87%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 23        | 0.87%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 22        | 0.83%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 22        | 0.83%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 21        | 0.8%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 21        | 0.8%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 20        | 0.76%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 20        | 0.76%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 20        | 0.76%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 19        | 0.72%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 19        | 0.72%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 19        | 0.72%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 18        | 0.68%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 17        | 0.64%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 17        | 0.64%   |
| Intel Core i5-3340M CPU @ 2.70GHz             | 17        | 0.64%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 17        | 0.64%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 17        | 0.64%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 16        | 0.61%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 16        | 0.61%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 16        | 0.61%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 16        | 0.61%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 15        | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 742       | 28.12%  |
| Intel Core i7                  | 510       | 19.33%  |
| Intel Core 2 Duo               | 218       | 8.26%   |
| Intel Core i3                  | 216       | 8.18%   |
| Other                          | 146       | 5.53%   |
| Intel Celeron                  | 146       | 5.53%   |
| AMD Ryzen 5                    | 119       | 4.51%   |
| Intel Pentium                  | 84        | 3.18%   |
| AMD Ryzen 7                    | 83        | 3.15%   |
| Intel Atom                     | 53        | 2.01%   |
| Intel Pentium Dual-Core        | 36        | 1.36%   |
| AMD A6                         | 23        | 0.87%   |
| Intel Core 2                   | 20        | 0.76%   |
| Intel Pentium Dual             | 17        | 0.64%   |
| AMD Ryzen 7 PRO                | 16        | 0.61%   |
| Intel Genuine                  | 15        | 0.57%   |
| AMD A8                         | 15        | 0.57%   |
| AMD E                          | 12        | 0.45%   |
| AMD A10                        | 12        | 0.45%   |
| Intel Celeron M                | 11        | 0.42%   |
| AMD E1                         | 11        | 0.42%   |
| AMD A4                         | 11        | 0.42%   |
| Intel Xeon                     | 9         | 0.34%   |
| Intel Pentium M                | 8         | 0.3%    |
| AMD E2                         | 8         | 0.3%    |
| AMD Turion 64 X2 Mobile        | 7         | 0.27%   |
| AMD Ryzen 9                    | 7         | 0.27%   |
| AMD Athlon X2                  | 7         | 0.27%   |
| AMD Ryzen 3                    | 6         | 0.23%   |
| Intel Core Duo                 | 5         | 0.19%   |
| AMD C-60                       | 5         | 0.19%   |
| Intel Core i9                  | 4         | 0.15%   |
| Intel Celeron Dual-Core        | 4         | 0.15%   |
| AMD Turion X2 Dual-Core Mobile | 4         | 0.15%   |
| AMD Ryzen 5 PRO                | 4         | 0.15%   |
| AMD Phenom II                  | 4         | 0.15%   |
| AMD Athlon II                  | 4         | 0.15%   |
| Intel Core M                   | 3         | 0.11%   |
| Intel Pentium Silver           | 2         | 0.08%   |
| Intel Core m5                  | 2         | 0.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1479      | 56%     |
| 4       | 763       | 28.89%  |
| 6       | 169       | 6.4%    |
| 8       | 117       | 4.43%   |
| 1       | 66        | 2.5%    |
| Unknown | 21        | 0.8%    |
| 14      | 10        | 0.38%   |
| 12      | 7         | 0.27%   |
| 10      | 4         | 0.15%   |
| 3       | 2         | 0.08%   |
| 192     | 1         | 0.04%   |
| 16      | 1         | 0.04%   |
| 5       | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 2635      | 99.89%  |
| Unknown | 2         | 0.08%   |
| 2       | 1         | 0.04%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1852      | 70.02%  |
| 1       | 771       | 29.15%  |
| Unknown | 21        | 0.79%   |
| 8       | 1         | 0.04%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2558      | 96.78%  |
| 32-bit         | 45        | 1.7%    |
| Unknown        | 39        | 1.48%   |
| 64-bit         | 1         | 0.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 501       | 18.42%  |
| 0x206a7    | 193       | 7.1%    |
| 0x306a9    | 181       | 6.65%   |
| 0x1067a    | 107       | 3.93%   |
| 0x40651    | 99        | 3.64%   |
| 0x306c3    | 85        | 3.13%   |
| 0x20655    | 85        | 3.13%   |
| 0x906ea    | 82        | 3.01%   |
| 0x806ec    | 80        | 2.94%   |
| 0x30678    | 80        | 2.94%   |
| 0x306d4    | 79        | 2.9%    |
| 0x806c1    | 76        | 2.79%   |
| 0x406e3    | 73        | 2.68%   |
| 0x806ea    | 70        | 2.57%   |
| 0x6fd      | 69        | 2.54%   |
| 0x806e9    | 57        | 2.1%    |
| 0x10676    | 51        | 1.88%   |
| 0x506e3    | 48        | 1.76%   |
| 0x906e9    | 43        | 1.58%   |
| 0x0a50000c | 39        | 1.43%   |
| 0x20652    | 32        | 1.18%   |
| 0xa0652    | 30        | 1.1%    |
| 0x08600106 | 28        | 1.03%   |
| 0x08108109 | 25        | 0.92%   |
| 0x806eb    | 24        | 0.88%   |
| 0x08108102 | 23        | 0.85%   |
| 0x706e5    | 20        | 0.74%   |
| 0x6fb      | 19        | 0.7%    |
| 0x6f6      | 17        | 0.63%   |
| 0x08600103 | 17        | 0.63%   |
| 0x906ed    | 16        | 0.59%   |
| 0x806d1    | 16        | 0.59%   |
| 0x106ca    | 16        | 0.59%   |
| 0x08600104 | 16        | 0.59%   |
| 0x06001119 | 16        | 0.59%   |
| 0x906a3    | 15        | 0.55%   |
| 0x406c3    | 15        | 0.55%   |
| 0x106c2    | 14        | 0.51%   |
| 0x05000119 | 13        | 0.48%   |
| 0x6e8      | 12        | 0.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 454       | 17.2%   |
| Haswell          | 227       | 8.6%    |
| SandyBridge      | 225       | 8.52%   |
| IvyBridge        | 218       | 8.26%   |
| Penryn           | 177       | 6.7%    |
| Skylake          | 146       | 5.53%   |
| Core             | 141       | 5.34%   |
| Westmere         | 130       | 4.92%   |
| Silvermont       | 122       | 4.62%   |
| Broadwell        | 106       | 4.02%   |
| TigerLake        | 89        | 3.37%   |
| Zen 2            | 88        | 3.33%   |
| Zen+             | 60        | 2.27%   |
| Zen 3            | 48        | 1.82%   |
| Unknown          | 48        | 1.82%   |
| CometLake        | 40        | 1.52%   |
| IceLake          | 39        | 1.48%   |
| Bonnell          | 33        | 1.25%   |
| Bobcat           | 30        | 1.14%   |
| P6               | 29        | 1.1%    |
| Zen              | 20        | 0.76%   |
| Piledriver       | 20        | 0.76%   |
| Alderlake Hybrid | 18        | 0.68%   |
| Goldmont plus    | 16        | 0.61%   |
| Goldmont         | 16        | 0.61%   |
| Excavator        | 15        | 0.57%   |
| K8 & K10 hybrid  | 14        | 0.53%   |
| Puma             | 13        | 0.49%   |
| K8 Hammer        | 13        | 0.49%   |
| K10              | 12        | 0.45%   |
| Jaguar           | 12        | 0.45%   |
| K10 Llano        | 9         | 0.34%   |
| Nehalem          | 7         | 0.27%   |
| Steamroller      | 4         | 0.15%   |
| Tremont          | 1         | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1998      | 58.4%   |
| Nvidia                           | 813       | 23.76%  |
| AMD                              | 599       | 17.51%  |
| Silicon Integrated Systems [SiS] | 6         | 0.18%   |
| VIA Technologies                 | 5         | 0.15%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 210       | 5.88%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 207       | 5.79%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 119       | 3.33%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 102       | 2.85%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 101       | 2.83%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 96        | 2.69%   |
| Intel HD Graphics 5500                                                                   | 94        | 2.63%   |
| Intel Core Processor Integrated Graphics Controller                                      | 91        | 2.55%   |
| Intel UHD Graphics 620                                                                   | 89        | 2.49%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 88        | 2.46%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 82        | 2.29%   |
| AMD Renoir                                                                               | 82        | 2.29%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 81        | 2.27%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 72        | 2.02%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 71        | 1.99%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 71        | 1.99%   |
| Intel HD Graphics 620                                                                    | 66        | 1.85%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 61        | 1.71%   |
| Intel HD Graphics 630                                                                    | 50        | 1.4%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 48        | 1.34%   |
| Intel HD Graphics 530                                                                    | 48        | 1.34%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 43        | 1.2%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 42        | 1.18%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 40        | 1.12%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 37        | 1.04%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 36        | 1.01%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 35        | 0.98%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 34        | 0.95%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 28        | 0.78%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 28        | 0.78%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 28        | 0.78%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 26        | 0.73%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 25        | 0.7%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 24        | 0.67%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 24        | 0.67%   |
| Nvidia GM108M [GeForce 840M]                                                             | 21        | 0.59%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 21        | 0.59%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 21        | 0.59%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 21        | 0.59%   |
| Nvidia TU117M                                                                            | 20        | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1282      | 48.45%  |
| Intel + Nvidia           | 563       | 21.28%  |
| 1 x AMD                  | 338       | 12.77%  |
| 1 x Nvidia               | 181       | 6.84%   |
| Intel + AMD              | 149       | 5.63%   |
| AMD + Nvidia             | 68        | 2.57%   |
| 2 x AMD                  | 42        | 1.59%   |
| 2 x Intel                | 7         | 0.26%   |
| 1 x SiS                  | 6         | 0.23%   |
| 1 x VIA                  | 5         | 0.19%   |
| Other                    | 3         | 0.11%   |
| 2 x Nvidia               | 1         | 0.04%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2234      | 83.55%  |
| Proprietary | 368       | 13.76%  |
| Unknown     | 72        | 2.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1602      | 59.11%  |
| 1.01-2.0   | 368       | 13.58%  |
| 0.01-0.5   | 342       | 12.62%  |
| 0.51-1.0   | 169       | 6.24%   |
| 3.01-4.0   | 163       | 6.01%   |
| 5.01-6.0   | 45        | 1.66%   |
| 7.01-8.0   | 15        | 0.55%   |
| 2.01-3.0   | 4         | 0.15%   |
| 8.01-16.0  | 2         | 0.07%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 545       | 18%     |
| LG Display              | 475       | 15.69%  |
| Samsung Electronics     | 382       | 12.62%  |
| BOE                     | 347       | 11.46%  |
| Chimei Innolux          | 323       | 10.67%  |
| Dell                    | 117       | 3.86%   |
| Chi Mei Optoelectronics | 106       | 3.5%    |
| Lenovo                  | 95        | 3.14%   |
| Goldstar                | 58        | 1.92%   |
| Iiyama                  | 53        | 1.75%   |
| Sharp                   | 43        | 1.42%   |
| LG Philips              | 40        | 1.32%   |
| PANDA                   | 32        | 1.06%   |
| Philips                 | 30        | 0.99%   |
| BenQ                    | 26        | 0.86%   |
| AOC                     | 26        | 0.86%   |
| Acer                    | 24        | 0.79%   |
| InfoVision              | 23        | 0.76%   |
| Hewlett-Packard         | 22        | 0.73%   |
| NEC Computers           | 21        | 0.69%   |
| Apple                   | 19        | 0.63%   |
| HannStar                | 16        | 0.53%   |
| Ancor Communications    | 16        | 0.53%   |
| Eizo                    | 14        | 0.46%   |
| CPT                     | 14        | 0.46%   |
| CSO                     | 11        | 0.36%   |
| LGD                     | 9         | 0.3%    |
| ASUSTek Computer        | 9         | 0.3%    |
| Toshiba                 | 8         | 0.26%   |
| Seiko/Epson             | 8         | 0.26%   |
| Mi                      | 8         | 0.26%   |
| Sony                    | 7         | 0.23%   |
| Valve                   | 6         | 0.2%    |
| Panasonic               | 6         | 0.2%    |
| MSI                     | 6         | 0.2%    |
| Fujitsu Siemens         | 6         | 0.2%    |
| InnoLux Display         | 5         | 0.17%   |
| IBM                     | 5         | 0.17%   |
| Vestel Elektronik       | 4         | 0.13%   |
| TMX                     | 4         | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0629 1366x768 309x173mm 13.9-inch                     | 31        | 1%      |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 29        | 0.94%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 28        | 0.91%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 24        | 0.78%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 22        | 0.71%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 22        | 0.71%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 21        | 0.68%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 19        | 0.61%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch                  | 17        | 0.55%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 17        | 0.55%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 15        | 0.48%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 15        | 0.48%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch             | 13        | 0.42%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 13        | 0.42%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 13        | 0.42%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 13        | 0.42%   |
| BOE LCD Monitor BOE06FB 1920x1080 344x194mm 15.5-inch                    | 13        | 0.42%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 13        | 0.42%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 12        | 0.39%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 12        | 0.39%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 11        | 0.36%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 11        | 0.36%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 11        | 0.36%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 11        | 0.36%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 11        | 0.36%   |
| Samsung Electronics LCD Monitor SDC4852 3840x2160 344x194mm 15.5-inch    | 10        | 0.32%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 10        | 0.32%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 10        | 0.32%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch           | 10        | 0.32%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 9         | 0.29%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 9         | 0.29%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch             | 9         | 0.29%   |
| Lenovo LCD Monitor LEN4050 1280x800 331x207mm 15.4-inch                  | 9         | 0.29%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 9         | 0.29%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch          | 9         | 0.29%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 9         | 0.29%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 9         | 0.29%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 9         | 0.29%   |
| BOE LCD Monitor BOE06E2 1920x1080 309x173mm 13.9-inch                    | 9         | 0.29%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 9         | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1145      | 40.72%  |
| 1366x768 (WXGA)    | 758       | 26.96%  |
| 1600x900 (HD+)     | 198       | 7.04%   |
| 1280x800 (WXGA)    | 176       | 6.26%   |
| 2560x1440 (QHD)    | 83        | 2.95%   |
| 3840x2160 (4K)     | 82        | 2.92%   |
| 1920x1200 (WUXGA)  | 67        | 2.38%   |
| 1440x900 (WXGA+)   | 64        | 2.28%   |
| 1680x1050 (WSXGA+) | 50        | 1.78%   |
| 1024x600           | 26        | 0.92%   |
| 1280x1024 (SXGA)   | 21        | 0.75%   |
| 3440x1440          | 20        | 0.71%   |
| 2560x1600          | 19        | 0.68%   |
| 2560x1080          | 12        | 0.43%   |
| 800x1280           | 9         | 0.32%   |
| Unknown            | 9         | 0.32%   |
| 3840x2400          | 8         | 0.28%   |
| 2160x1440          | 8         | 0.28%   |
| 2880x1800          | 7         | 0.25%   |
| 1024x768 (XGA)     | 7         | 0.25%   |
| 3200x1800 (QHD+)   | 5         | 0.18%   |
| 1680x945           | 4         | 0.14%   |
| 3286x1080          | 3         | 0.11%   |
| 1400x1050          | 3         | 0.11%   |
| 3840x1600          | 2         | 0.07%   |
| 3840x1080          | 2         | 0.07%   |
| 3456x2160          | 2         | 0.07%   |
| 3000x2000          | 2         | 0.07%   |
| 2288x1287          | 2         | 0.07%   |
| 2256x1504          | 2         | 0.07%   |
| 1280x768           | 2         | 0.07%   |
| 1280x720 (HD)      | 2         | 0.07%   |
| 6400x1600          | 1         | 0.04%   |
| 5120x1600          | 1         | 0.04%   |
| 3300x2200          | 1         | 0.04%   |
| 3200x2000          | 1         | 0.04%   |
| 2520x1680          | 1         | 0.04%   |
| 2304x1440          | 1         | 0.04%   |
| 2240x1400          | 1         | 0.04%   |
| 2048x1152          | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1305      | 42.89%  |
| 13      | 353       | 11.6%   |
| 14      | 333       | 10.94%  |
| 17      | 229       | 7.53%   |
| 24      | 131       | 4.3%    |
| 23      | 105       | 3.45%   |
| 12      | 93        | 3.06%   |
| 27      | 90        | 2.96%   |
| 21      | 59        | 1.94%   |
| Unknown | 59        | 1.94%   |
| 11      | 37        | 1.22%   |
| 34      | 33        | 1.08%   |
| 10      | 28        | 0.92%   |
| 16      | 25        | 0.82%   |
| 22      | 24        | 0.79%   |
| 19      | 24        | 0.79%   |
| 18      | 19        | 0.62%   |
| 31      | 16        | 0.53%   |
| 25      | 11        | 0.36%   |
| 48      | 9         | 0.3%    |
| 20      | 9         | 0.3%    |
| 84      | 8         | 0.26%   |
| 40      | 6         | 0.2%    |
| 7       | 6         | 0.2%    |
| 72      | 5         | 0.16%   |
| 32      | 4         | 0.13%   |
| 43      | 3         | 0.1%    |
| 37      | 3         | 0.1%    |
| 65      | 2         | 0.07%   |
| 28      | 2         | 0.07%   |
| 26      | 2         | 0.07%   |
| 142     | 1         | 0.03%   |
| 54      | 1         | 0.03%   |
| 52      | 1         | 0.03%   |
| 49      | 1         | 0.03%   |
| 46      | 1         | 0.03%   |
| 35      | 1         | 0.03%   |
| 33      | 1         | 0.03%   |
| 29      | 1         | 0.03%   |
| 8       | 1         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 1809      | 60.4%   |
| 501-600        | 303       | 10.12%  |
| 201-300        | 302       | 10.08%  |
| 351-400        | 288       | 9.62%   |
| 401-500        | 121       | 4.04%   |
| Unknown        | 59        | 1.97%   |
| 701-800        | 38        | 1.27%   |
| 601-700        | 25        | 0.83%   |
| 1001-1500      | 15        | 0.5%    |
| 1501-2000      | 13        | 0.43%   |
| 801-900        | 10        | 0.33%   |
| 1-100          | 7         | 0.23%   |
| 901-1000       | 3         | 0.1%    |
| More than 2000 | 1         | 0.03%   |
| 101-200        | 1         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 2122      | 79.77%  |
| 16/10   | 376       | 14.14%  |
| Unknown | 46        | 1.73%   |
| 21/9    | 36        | 1.35%   |
| 3/2     | 29        | 1.09%   |
| 5/4     | 22        | 0.83%   |
| 4/3     | 15        | 0.56%   |
| 0.67    | 6         | 0.23%   |
| 0.62    | 4         | 0.15%   |
| 32/9    | 2         | 0.08%   |
| 6/5     | 1         | 0.04%   |
| 1.00    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1303      | 43.1%   |
| 81-90          | 558       | 18.46%  |
| 201-250        | 243       | 8.04%   |
| 121-130        | 181       | 5.99%   |
| 71-80          | 120       | 3.97%   |
| 61-70          | 92        | 3.04%   |
| 301-350        | 92        | 3.04%   |
| 251-300        | 65        | 2.15%   |
| Unknown        | 59        | 1.95%   |
| 351-500        | 55        | 1.82%   |
| 131-140        | 43        | 1.42%   |
| 151-200        | 40        | 1.32%   |
| 51-60          | 37        | 1.22%   |
| 41-50          | 28        | 0.93%   |
| 141-150        | 27        | 0.89%   |
| More than 1000 | 26        | 0.86%   |
| 91-100         | 17        | 0.56%   |
| 111-120        | 15        | 0.5%    |
| 501-1000       | 14        | 0.46%   |
| 1-40           | 8         | 0.26%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1205      | 40.63%  |
| 101-120       | 877       | 29.57%  |
| 51-100        | 611       | 20.6%   |
| 161-240       | 133       | 4.48%   |
| More than 240 | 60        | 2.02%   |
| Unknown       | 59        | 1.99%   |
| 1-50          | 21        | 0.71%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2136      | 78.56%  |
| 2     | 445       | 16.37%  |
| 3     | 65        | 2.39%   |
| 0     | 63        | 2.32%   |
| 4     | 8         | 0.29%   |
| 6     | 1         | 0.04%   |
| 5     | 1         | 0.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1542      | 35.44%  |
| Realtek Semiconductor             | 1226      | 28.18%  |
| Qualcomm Atheros                  | 648       | 14.89%  |
| Broadcom                          | 300       | 6.89%   |
| Broadcom Limited                  | 87        | 2%      |
| Dell                              | 74        | 1.7%    |
| Marvell Technology Group          | 63        | 1.45%   |
| Huawei Technologies               | 59        | 1.36%   |
| MediaTek                          | 42        | 0.97%   |
| Ralink                            | 33        | 0.76%   |
| Ericsson Business Mobile Networks | 25        | 0.57%   |
| TP-Link                           | 24        | 0.55%   |
| Samsung Electronics               | 22        | 0.51%   |
| Hewlett-Packard                   | 22        | 0.51%   |
| JMicron Technology                | 17        | 0.39%   |
| Xiaomi                            | 15        | 0.34%   |
| Sierra Wireless                   | 15        | 0.34%   |
| Lenovo                            | 12        | 0.28%   |
| Nvidia                            | 11        | 0.25%   |
| Ralink Technology                 | 10        | 0.23%   |
| DisplayLink                       | 10        | 0.23%   |
| ASIX Electronics                  | 10        | 0.23%   |
| Silicon Integrated Systems [SiS]  | 9         | 0.21%   |
| Qualcomm Atheros Communications   | 9         | 0.21%   |
| Fibocom                           | 8         | 0.18%   |
| Qualcomm                          | 7         | 0.16%   |
| ASUSTek Computer                  | 6         | 0.14%   |
| NetGear                           | 5         | 0.11%   |
| Motorola PCS                      | 5         | 0.11%   |
| ZTE WCDMA Technologies MSM        | 4         | 0.09%   |
| VIA Technologies                  | 4         | 0.09%   |
| Attansic Technology               | 3         | 0.07%   |
| Microsoft                         | 2         | 0.05%   |
| HTC (High Tech Computer)          | 2         | 0.05%   |
| Edimax Technology                 | 2         | 0.05%   |
| Uniden                            | 1         | 0.02%   |
| Toshiba                           | 1         | 0.02%   |
| Tenda                             | 1         | 0.02%   |
| Sweex                             | 1         | 0.02%   |
| Sigma Designs                     | 1         | 0.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 803       | 15.19%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 227       | 4.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 152       | 2.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 117       | 2.21%   |
| Intel Wireless 8265 / 8275                                              | 113       | 2.14%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 113       | 2.14%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 106       | 2.01%   |
| Intel Wi-Fi 6 AX200                                                     | 101       | 1.91%   |
| Intel Wireless 7260                                                     | 97        | 1.84%   |
| Intel Wireless 8260                                                     | 82        | 1.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 80        | 1.51%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 76        | 1.44%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 75        | 1.42%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 74        | 1.4%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 71        | 1.34%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 71        | 1.34%   |
| Intel Wi-Fi 6 AX201                                                     | 70        | 1.32%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 68        | 1.29%   |
| Intel Wireless 7265                                                     | 63        | 1.19%   |
| Intel Wireless 3160                                                     | 60        | 1.14%   |
| Intel 82567LM Gigabit Network Connection                                | 50        | 0.95%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 49        | 0.93%   |
| Intel Wireless 3165                                                     | 48        | 0.91%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 48        | 0.91%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 46        | 0.87%   |
| Intel Centrino Ultimate-N 6300                                          | 45        | 0.85%   |
| Broadcom BCM43142 802.11b/g/n                                           | 45        | 0.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 43        | 0.81%   |
| Intel Ethernet Connection I218-LM                                       | 43        | 0.81%   |
| Intel WiFi Link 5100                                                    | 42        | 0.79%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 41        | 0.78%   |
| Intel 82577LM Gigabit Network Connection                                | 40        | 0.76%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 38        | 0.72%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 37        | 0.7%    |
| Intel Ethernet Connection I217-LM                                       | 37        | 0.7%    |
| Intel Ethernet Connection (4) I219-LM                                   | 37        | 0.7%    |
| Huawei E353/E3131                                                       | 37        | 0.7%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 35        | 0.66%   |
| Intel Centrino Advanced-N 6200                                          | 33        | 0.62%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 32        | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1468      | 53.19%  |
| Qualcomm Atheros                | 540       | 19.57%  |
| Realtek Semiconductor           | 287       | 10.4%   |
| Broadcom                        | 207       | 7.5%    |
| Broadcom Limited                | 49        | 1.78%   |
| Dell                            | 47        | 1.7%    |
| MediaTek                        | 39        | 1.41%   |
| Ralink                          | 33        | 1.2%    |
| TP-Link                         | 20        | 0.72%   |
| Sierra Wireless                 | 15        | 0.54%   |
| Ralink Technology               | 10        | 0.36%   |
| Qualcomm Atheros Communications | 9         | 0.33%   |
| Fibocom                         | 8         | 0.29%   |
| Hewlett-Packard                 | 6         | 0.22%   |
| ASUSTek Computer                | 6         | 0.22%   |
| Qualcomm                        | 5         | 0.18%   |
| NetGear                         | 2         | 0.07%   |
| Microsoft                       | 2         | 0.07%   |
| Edimax Technology               | 2         | 0.07%   |
| Tenda                           | 1         | 0.04%   |
| Sweex                           | 1         | 0.04%   |
| Sagem                           | 1         | 0.04%   |
| Linksys                         | 1         | 0.04%   |
| Belkin Components               | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 117       | 4.23%   |
| Intel Wireless 8265 / 8275                                              | 113       | 4.09%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 113       | 4.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 106       | 3.84%   |
| Intel Wi-Fi 6 AX200                                                     | 101       | 3.65%   |
| Intel Wireless 7260                                                     | 97        | 3.51%   |
| Intel Wireless 8260                                                     | 82        | 2.97%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 80        | 2.89%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 76        | 2.75%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 75        | 2.71%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 74        | 2.68%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 71        | 2.57%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 71        | 2.57%   |
| Intel Wi-Fi 6 AX201                                                     | 70        | 2.53%   |
| Intel Wireless 7265                                                     | 63        | 2.28%   |
| Intel Wireless 3160                                                     | 60        | 2.17%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 49        | 1.77%   |
| Intel Wireless 3165                                                     | 48        | 1.74%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 48        | 1.74%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 46        | 1.66%   |
| Intel Centrino Ultimate-N 6300                                          | 45        | 1.63%   |
| Broadcom BCM43142 802.11b/g/n                                           | 45        | 1.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 43        | 1.56%   |
| Intel WiFi Link 5100                                                    | 42        | 1.52%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 41        | 1.48%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 38        | 1.37%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 37        | 1.34%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 35        | 1.27%   |
| Intel Centrino Advanced-N 6200                                          | 33        | 1.19%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 32        | 1.16%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 31        | 1.12%   |
| Intel Centrino Advanced-N 6235                                          | 31        | 1.12%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 29        | 1.05%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 29        | 1.05%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 28        | 1.01%   |
| Intel Centrino Wireless-N 2230                                          | 27        | 0.98%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 19        | 0.69%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 19        | 0.69%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 18        | 0.65%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 18        | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1119      | 46.57%  |
| Intel                            | 678       | 28.21%  |
| Qualcomm Atheros                 | 193       | 8.03%   |
| Broadcom                         | 129       | 5.37%   |
| Marvell Technology Group         | 63        | 2.62%   |
| Huawei Technologies              | 42        | 1.75%   |
| Broadcom Limited                 | 39        | 1.62%   |
| Samsung Electronics              | 20        | 0.83%   |
| JMicron Technology               | 17        | 0.71%   |
| Xiaomi                           | 14        | 0.58%   |
| Lenovo                           | 12        | 0.5%    |
| Nvidia                           | 11        | 0.46%   |
| DisplayLink                      | 10        | 0.42%   |
| ASIX Electronics                 | 10        | 0.42%   |
| Silicon Integrated Systems [SiS] | 9         | 0.37%   |
| Motorola PCS                     | 5         | 0.21%   |
| VIA Technologies                 | 4         | 0.17%   |
| TP-Link                          | 4         | 0.17%   |
| ZTE WCDMA Technologies MSM       | 3         | 0.12%   |
| NetGear                          | 3         | 0.12%   |
| Hewlett-Packard                  | 3         | 0.12%   |
| Attansic Technology              | 3         | 0.12%   |
| Qualcomm                         | 2         | 0.08%   |
| MediaTek                         | 2         | 0.08%   |
| HTC (High Tech Computer)         | 2         | 0.08%   |
| QinHeng Electronics              | 1         | 0.04%   |
| OPPO Electronics                 | 1         | 0.04%   |
| LG Electronics                   | 1         | 0.04%   |
| ICS Advent                       | 1         | 0.04%   |
| HMD Global                       | 1         | 0.04%   |
| Apple                            | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 803       | 33.2%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 227       | 9.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 152       | 6.28%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 68        | 2.81%   |
| Intel 82567LM Gigabit Network Connection                          | 50        | 2.07%   |
| Intel Ethernet Connection I218-LM                                 | 43        | 1.78%   |
| Intel 82577LM Gigabit Network Connection                          | 40        | 1.65%   |
| Intel Ethernet Connection I217-LM                                 | 37        | 1.53%   |
| Intel Ethernet Connection (4) I219-LM                             | 37        | 1.53%   |
| Huawei E353/E3131                                                 | 37        | 1.53%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 31        | 1.28%   |
| Intel Ethernet Connection (3) I218-LM                             | 30        | 1.24%   |
| Intel Ethernet Connection (6) I219-V                              | 28        | 1.16%   |
| Intel Ethernet Connection I219-LM                                 | 26        | 1.07%   |
| Intel Ethernet Connection (7) I219-LM                             | 26        | 1.07%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 22        | 0.91%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 21        | 0.87%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 21        | 0.87%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 19        | 0.79%   |
| Intel Ethernet Connection (4) I219-V                              | 18        | 0.74%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 16        | 0.66%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 16        | 0.66%   |
| Intel 82579V Gigabit Network Connection                           | 16        | 0.66%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 16        | 0.66%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 14        | 0.58%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 14        | 0.58%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 14        | 0.58%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 14        | 0.58%   |
| Intel Ethernet Connection I219-V                                  | 14        | 0.58%   |
| Intel Ethernet Connection (5) I219-LM                             | 14        | 0.58%   |
| Intel Ethernet Connection (2) I219-LM                             | 14        | 0.58%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 13        | 0.54%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 13        | 0.54%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 12        | 0.5%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 12        | 0.5%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 11        | 0.45%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 11        | 0.45%   |
| Intel Ethernet Connection (13) I219-V                             | 11        | 0.45%   |
| Intel Ethernet Connection (11) I219-LM                            | 11        | 0.45%   |
| Intel 82566MM Gigabit Network Connection                          | 11        | 0.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2600      | 51.92%  |
| Ethernet | 2306      | 46.05%  |
| Modem    | 96        | 1.92%   |
| Unknown  | 6         | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2132      | 77.67%  |
| Ethernet | 613       | 22.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2160      | 81.79%  |
| 1     | 441       | 16.7%   |
| 0     | 32        | 1.21%   |
| 3     | 8         | 0.3%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2476      | 92.98%  |
| Yes  | 187       | 7.02%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 967       | 47.33%  |
| Qualcomm Atheros Communications | 221       | 10.82%  |
| Broadcom                        | 161       | 7.88%   |
| Realtek Semiconductor           | 142       | 6.95%   |
| IMC Networks                    | 102       | 4.99%   |
| Dell                            | 83        | 4.06%   |
| Foxconn / Hon Hai               | 66        | 3.23%   |
| Lite-On Technology              | 59        | 2.89%   |
| Hewlett-Packard                 | 59        | 2.89%   |
| ASUSTek Computer                | 31        | 1.52%   |
| Toshiba                         | 26        | 1.27%   |
| Cambridge Silicon Radio         | 24        | 1.17%   |
| Apple                           | 20        | 0.98%   |
| Ralink                          | 18        | 0.88%   |
| Foxconn International           | 15        | 0.73%   |
| Realtek                         | 10        | 0.49%   |
| Alps Electric                   | 7         | 0.34%   |
| Chicony Electronics             | 6         | 0.29%   |
| Taiyo Yuden                     | 5         | 0.24%   |
| Ralink Technology               | 3         | 0.15%   |
| MediaTek                        | 3         | 0.15%   |
| Integrated System Solution      | 3         | 0.15%   |
| USI                             | 2         | 0.1%    |
| Micro Star International        | 2         | 0.1%    |
| Askey Computer                  | 2         | 0.1%    |
| TP-Link                         | 1         | 0.05%   |
| Opticis                         | 1         | 0.05%   |
| Fujitsu                         | 1         | 0.05%   |
| Edimax Technology               | 1         | 0.05%   |
| Creative Technology             | 1         | 0.05%   |
| AboCom Systems                  | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 454       | 22.21%  |
| Intel AX201 Bluetooth                               | 148       | 7.24%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 131       | 6.41%   |
| Qualcomm Atheros  Bluetooth Device                  | 97        | 4.75%   |
| Intel AX200 Bluetooth                               | 95        | 4.65%   |
| Realtek Bluetooth Radio                             | 88        | 4.31%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 55        | 2.69%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 52        | 2.54%   |
| IMC Networks Bluetooth Radio                        | 41        | 2.01%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 38        | 1.86%   |
| Broadcom BCM2045B (BDC-2.1)                         | 38        | 1.86%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 35        | 1.71%   |
| Realtek  Bluetooth 4.2 Adapter                      | 30        | 1.47%   |
| Intel Wireless-AC 3168 Bluetooth                    | 29        | 1.42%   |
| Dell BCM20702A0 Bluetooth Module                    | 26        | 1.27%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 24        | 1.17%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 24        | 1.17%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 24        | 1.17%   |
| HP Broadcom 2070 Bluetooth Combo                    | 23        | 1.13%   |
| Dell DW375 Bluetooth Module                         | 22        | 1.08%   |
| IMC Networks Bluetooth Device                       | 19        | 0.93%   |
| Ralink RT3290 Bluetooth                             | 18        | 0.88%   |
| Realtek RTL8723B Bluetooth                          | 17        | 0.83%   |
| IMC Networks Wireless_Device                        | 17        | 0.83%   |
| Broadcom BCM2070 Bluetooth Device                   | 17        | 0.83%   |
| Lite-On Bluetooth Device                            | 16        | 0.78%   |
| Lite-On Atheros AR3012 Bluetooth                    | 15        | 0.73%   |
| Foxconn International BCM43142A0 Bluetooth module   | 15        | 0.73%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 14        | 0.68%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 14        | 0.68%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 13        | 0.64%   |
| Foxconn / Hon Hai Wireless_Device                   | 13        | 0.64%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 12        | 0.59%   |
| Intel Bluetooth Device                              | 12        | 0.59%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 12        | 0.59%   |
| Foxconn / Hon Hai Bluetooth Device                  | 12        | 0.59%   |
| Dell Wireless 360 Bluetooth                         | 12        | 0.59%   |
| Broadcom HP Portable SoftSailing                    | 12        | 0.59%   |
| Toshiba Integrated Bluetooth HCI                    | 11        | 0.54%   |
| Dell Wireless 370 Bluetooth Mini-card               | 11        | 0.54%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2199      | 68.06%  |
| AMD                                          | 447       | 13.83%  |
| Nvidia                                       | 397       | 12.29%  |
| C-Media Electronics                          | 19        | 0.59%   |
| Creative Technology                          | 17        | 0.53%   |
| Realtek Semiconductor                        | 15        | 0.46%   |
| Lenovo                                       | 14        | 0.43%   |
| Silicon Integrated Systems [SiS]             | 11        | 0.34%   |
| Plantronics                                  | 11        | 0.34%   |
| Logitech                                     | 11        | 0.34%   |
| GN Netcom                                    | 9         | 0.28%   |
| SteelSeries ApS                              | 6         | 0.19%   |
| Hewlett-Packard                              | 6         | 0.19%   |
| VIA Technologies                             | 5         | 0.15%   |
| Texas Instruments                            | 5         | 0.15%   |
| Dell                                         | 5         | 0.15%   |
| Generalplus Technology                       | 4         | 0.12%   |
| Focusrite-Novation                           | 4         | 0.12%   |
| Sennheiser Communications                    | 3         | 0.09%   |
| Samson Technologies                          | 3         | 0.09%   |
| Kingston Technology                          | 3         | 0.09%   |
| JMTek                                        | 3         | 0.09%   |
| TTGK Technology                              | 2         | 0.06%   |
| DSEA A/S                                     | 2         | 0.06%   |
| DCMT Technology                              | 2         | 0.06%   |
| BEHRINGER International                      | 2         | 0.06%   |
| AudioQuest                                   | 2         | 0.06%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.03%   |
| Yamaha                                       | 1         | 0.03%   |
| USB MICROPHONE                               | 1         | 0.03%   |
| Turtle Beach                                 | 1         | 0.03%   |
| THX                                          | 1         | 0.03%   |
| Thesycon Systemsoftware & Consulting         | 1         | 0.03%   |
| Sony                                         | 1         | 0.03%   |
| Silicon Motion                               | 1         | 0.03%   |
| SAVITECH                                     | 1         | 0.03%   |
| Razer USA                                    | 1         | 0.03%   |
| Native Instruments                           | 1         | 0.03%   |
| MCS                                          | 1         | 0.03%   |
| Mark of the Unicorn                          | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 259       | 6.71%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 252       | 6.53%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 229       | 5.93%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 182       | 4.72%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 166       | 4.3%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 137       | 3.55%   |
| Intel 8 Series HD Audio Controller                                                                | 124       | 3.21%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 122       | 3.16%   |
| Intel Cannon Lake PCH cAVS                                                                        | 122       | 3.16%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 110       | 2.85%   |
| Intel Broadwell-U Audio Controller                                                                | 106       | 2.75%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 105       | 2.72%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 104       | 2.69%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 103       | 2.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 94        | 2.44%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 89        | 2.31%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 79        | 2.05%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 73        | 1.89%   |
| AMD FCH Azalia Controller                                                                         | 73        | 1.89%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 69        | 1.79%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 69        | 1.79%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 58        | 1.5%    |
| Intel CM238 HD Audio Controller                                                                   | 56        | 1.45%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 53        | 1.37%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 50        | 1.3%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 45        | 1.17%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 42        | 1.09%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 40        | 1.04%   |
| Intel Comet Lake PCH cAVS                                                                         | 38        | 0.98%   |
| AMD Kabini HDMI/DP Audio                                                                          | 30        | 0.78%   |
| AMD Wrestler HDMI Audio                                                                           | 28        | 0.73%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 24        | 0.62%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 24        | 0.62%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 24        | 0.62%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 24        | 0.62%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 21        | 0.54%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 21        | 0.54%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 20        | 0.52%   |
| AMD Trinity HDMI Audio Controller                                                                 | 20        | 0.52%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 19        | 0.49%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 577       | 28.05%  |
| SK hynix                     | 431       | 20.95%  |
| Micron Technology            | 226       | 10.99%  |
| Kingston                     | 215       | 10.45%  |
| Unknown                      | 154       | 7.49%   |
| GOODRAM                      | 101       | 4.91%   |
| Crucial                      | 83        | 4.04%   |
| Ramaxel Technology           | 50        | 2.43%   |
| A-DATA Technology            | 45        | 2.19%   |
| Nanya Technology             | 36        | 1.75%   |
| Elpida                       | 34        | 1.65%   |
| Patriot                      | 17        | 0.83%   |
| Unknown                      | 11        | 0.53%   |
| Unknown (ABCD)               | 10        | 0.49%   |
| Qimonda                      | 10        | 0.49%   |
| Wilk                         | 9         | 0.44%   |
| Corsair                      | 7         | 0.34%   |
| ASint Technology             | 7         | 0.34%   |
| G.Skill                      | 5         | 0.24%   |
| Unifosa                      | 3         | 0.15%   |
| Apacer                       | 3         | 0.15%   |
| 48spaces                     | 3         | 0.15%   |
| Toshiba                      | 2         | 0.1%    |
| SHARETRONIC                  | 2         | 0.1%    |
| Patriot Memory (PDP Systems) | 2         | 0.1%    |
| fef5                         | 2         | 0.1%    |
| Unknown (8A02)               | 1         | 0.05%   |
| Unknown (768A)               | 1         | 0.05%   |
| Transcend                    | 1         | 0.05%   |
| Team                         | 1         | 0.05%   |
| Swissbit                     | 1         | 0.05%   |
| Smart                        | 1         | 0.05%   |
| PNY                          | 1         | 0.05%   |
| Goldkey                      | 1         | 0.05%   |
| ChangXin Memory              | 1         | 0.05%   |
| 8CFD000080AD                 | 1         | 0.05%   |
| 430112204340C940             | 1         | 0.05%   |
| 430112174392063E             | 1         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s   | 36        | 1.64%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 29        | 1.32%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s   | 28        | 1.27%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s              | 26        | 1.18%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s  | 26        | 1.18%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 24        | 1.09%   |
| GOODRAM RAM GR2666S464L19/16G 16GB SODIMM DDR4 2667MT/s | 23        | 1.05%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s  | 22        | 1%      |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s   | 22        | 1%      |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s   | 21        | 0.95%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s   | 20        | 0.91%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s   | 20        | 0.91%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s   | 20        | 0.91%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s   | 19        | 0.86%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s  | 18        | 0.82%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s  | 17        | 0.77%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s   | 16        | 0.73%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 800MT/s    | 15        | 0.68%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s   | 15        | 0.68%   |
| GOODRAM RAM GR3200S464L22/16G 16GB SODIMM DDR4 3200MT/s | 15        | 0.68%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s  | 14        | 0.64%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s   | 14        | 0.64%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s  | 13        | 0.59%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s   | 13        | 0.59%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s   | 13        | 0.59%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s   | 13        | 0.59%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 12        | 0.55%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s   | 12        | 0.55%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s   | 12        | 0.55%   |
| Kingston RAM KHX2400C14S4/16G 16GB SODIMM DDR4 2667MT/s | 12        | 0.55%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s | 12        | 0.55%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s  | 11        | 0.5%    |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s   | 11        | 0.5%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s   | 11        | 0.5%    |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s  | 11        | 0.5%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s   | 11        | 0.5%    |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s    | 11        | 0.5%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s    | 11        | 0.5%    |
| Unknown                                                 | 11        | 0.5%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s  | 10        | 0.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 667       | 39.44%  |
| DDR4    | 659       | 38.97%  |
| DDR2    | 155       | 9.17%   |
| SDRAM   | 74        | 4.38%   |
| LPDDR4  | 55        | 3.25%   |
| LPDDR3  | 35        | 2.07%   |
| Unknown | 13        | 0.77%   |
| DDR5    | 11        | 0.65%   |
| DDR     | 10        | 0.59%   |
| LPDDR5  | 7         | 0.41%   |
| DRAM    | 5         | 0.3%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| SODIMM          | 1548      | 93.2%   |
| Row Of Chips    | 86        | 5.18%   |
| Chip            | 11        | 0.66%   |
| Unknown         | 8         | 0.48%   |
| DIMM            | 7         | 0.42%   |
| Proprietary Car | 1         | 0.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Notebooks | Percent |
|---------|-----------|---------|
| 4096    | 569       | 30.74%  |
| 8192    | 561       | 30.31%  |
| 2048    | 302       | 16.32%  |
| 16384   | 266       | 14.37%  |
| 1024    | 106       | 5.73%   |
| 32768   | 31        | 1.67%   |
| 512     | 9         | 0.49%   |
| Unknown | 4         | 0.22%   |
| 131072  | 1         | 0.05%   |
| 1536    | 1         | 0.05%   |
| 256     | 1         | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 476       | 25.74%  |
| 2667    | 331       | 17.9%   |
| 3200    | 249       | 13.47%  |
| 1334    | 120       | 6.49%   |
| 2400    | 106       | 5.73%   |
| 2133    | 79        | 4.27%   |
| 667     | 77        | 4.16%   |
| 1333    | 70        | 3.79%   |
| Unknown | 55        | 2.97%   |
| 4199    | 42        | 2.27%   |
| 1067    | 37        | 2%      |
| 800     | 30        | 1.62%   |
| 2048    | 25        | 1.35%   |
| 975     | 25        | 1.35%   |
| 533     | 22        | 1.19%   |
| 4267    | 17        | 0.92%   |
| 1867    | 14        | 0.76%   |
| 4800    | 12        | 0.65%   |
| 3266    | 12        | 0.65%   |
| 8400    | 11        | 0.59%   |
| 1066    | 9         | 0.49%   |
| 6400    | 7         | 0.38%   |
| 4266    | 5         | 0.27%   |
| 3733    | 5         | 0.27%   |
| 400     | 4         | 0.22%   |
| 333     | 4         | 0.22%   |
| 2933    | 1         | 0.05%   |
| 2134    | 1         | 0.05%   |
| 1776    | 1         | 0.05%   |
| 1639    | 1         | 0.05%   |
| 933     | 1         | 0.05%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 10        | 43.48%  |
| Samsung Electronics | 5         | 21.74%  |
| Canon               | 3         | 13.04%  |
| Seiko Epson         | 2         | 8.7%    |
| Zebra               | 1         | 4.35%   |
| Xerox               | 1         | 4.35%   |
| Brother Industries  | 1         | 4.35%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Samsung M2020 Series                    | 2         | 8.7%    |
| HP Deskjet F2280 series                 | 2         | 8.7%    |
| Zebra ZTC GX420t                        | 1         | 4.35%   |
| Xerox Phaser 6000B                      | 1         | 4.35%   |
| Seiko Epson L396 Series                 | 1         | 4.35%   |
| Seiko Epson AL-M310DN                   | 1         | 4.35%   |
| Samsung Xerox Phaser 3117 Laser Printer | 1         | 4.35%   |
| Samsung SCX-6545 Series                 | 1         | 4.35%   |
| Samsung SCX-3400 Series                 | 1         | 4.35%   |
| HP LaserJet P1102                       | 1         | 4.35%   |
| HP LaserJet P1005                       | 1         | 4.35%   |
| HP LaserJet 1020                        | 1         | 4.35%   |
| HP LaserJet 1018                        | 1         | 4.35%   |
| HP Ink Tank Wireless 410 series         | 1         | 4.35%   |
| HP Deskjet Ink Advant K209a-z           | 1         | 4.35%   |
| HP Deskjet D1500 series                 | 1         | 4.35%   |
| HP Deskjet 2540 series                  | 1         | 4.35%   |
| Canon PIXMA MG3000 series               | 1         | 4.35%   |
| Canon MG5600 series                     | 1         | 4.35%   |
| Canon LiDE 400                          | 1         | 4.35%   |
| Brother DCP-1610W                       | 1         | 4.35%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Canon                  | 2         | 50%     |
| Plustek                | 1         | 25%     |
| Microtek International | 1         | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Plustek OpticSlim 1200 Scanner         | 1         | 25%     |
| Microtek International USB1200 Scanner | 1         | 25%     |
| Canon CanoScan N670U/N676U/LiDE 20     | 1         | 25%     |
| Canon CanoScan N1240U/LiDE 30          | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 543       | 23.86%  |
| IMC Networks                           | 240       | 10.54%  |
| Microdia                               | 239       | 10.5%   |
| Realtek Semiconductor                  | 209       | 9.18%   |
| Acer                                   | 153       | 6.72%   |
| Sunplus Innovation Technology          | 127       | 5.58%   |
| Quanta                                 | 108       | 4.75%   |
| Suyin                                  | 107       | 4.7%    |
| Cheng Uei Precision Industry (Foxlink) | 80        | 3.51%   |
| Syntek                                 | 74        | 3.25%   |
| Silicon Motion                         | 52        | 2.28%   |
| Lite-On Technology                     | 52        | 2.28%   |
| Bison Electronics                      | 32        | 1.41%   |
| Ricoh                                  | 29        | 1.27%   |
| Logitech                               | 26        | 1.14%   |
| Lenovo                                 | 25        | 1.1%    |
| Alcor Micro                            | 25        | 1.1%    |
| Luxvisions Innotech Limited            | 22        | 0.97%   |
| Apple                                  | 21        | 0.92%   |
| Z-Star Microelectronics                | 14        | 0.62%   |
| DigiTech                               | 11        | 0.48%   |
| Creative Technology                    | 10        | 0.44%   |
| Primax Electronics                     | 9         | 0.4%    |
| Intel                                  | 9         | 0.4%    |
| ALi                                    | 8         | 0.35%   |
| Sonix Technology                       | 7         | 0.31%   |
| Samsung Electronics                    | 7         | 0.31%   |
| Generalplus Technology                 | 5         | 0.22%   |
| Microsoft                              | 4         | 0.18%   |
| Importek                               | 4         | 0.18%   |
| Sunplus Technology                     | 2         | 0.09%   |
| OmniVision Technologies                | 2         | 0.09%   |
| MacroSilicon                           | 2         | 0.09%   |
| Foxconn / Hon Hai                      | 2         | 0.09%   |
| Cubeternet                             | 2         | 0.09%   |
| Alpha Imaging Technology               | 2         | 0.09%   |
| WaveRider Communications               | 1         | 0.04%   |
| Trust                                  | 1         | 0.04%   |
| SunplusIT                              | 1         | 0.04%   |
| Razer USA                              | 1         | 0.04%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 110       | 4.82%   |
| Microdia Integrated_Webcam_HD            | 83        | 3.64%   |
| Realtek Integrated_Webcam_HD             | 74        | 3.24%   |
| IMC Networks Integrated Camera           | 63        | 2.76%   |
| IMC Networks USB2.0 HD UVC WebCam        | 59        | 2.59%   |
| Sunplus Integrated_Webcam_HD             | 53        | 2.32%   |
| Chicony Lenovo EasyCamera                | 44        | 1.93%   |
| Microdia Integrated Webcam               | 38        | 1.67%   |
| Chicony HD WebCam                        | 38        | 1.67%   |
| Acer Lenovo EasyCamera                   | 37        | 1.62%   |
| Suyin Integrated_Webcam_HD               | 35        | 1.53%   |
| Syntek Lenovo EasyCamera                 | 29        | 1.27%   |
| Realtek Lenovo EasyCamera                | 27        | 1.18%   |
| Syntek Integrated Camera                 | 25        | 1.1%    |
| Lite-On Integrated Camera                | 22        | 0.96%   |
| Quanta HP TrueVision HD Camera           | 21        | 0.92%   |
| Chicony USB2.0 HD UVC WebCam             | 21        | 0.92%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 20        | 0.88%   |
| Chicony HP HD Camera                     | 20        | 0.88%   |
| Acer Lenovo Integrated Webcam            | 20        | 0.88%   |
| Realtek USB Camera                       | 19        | 0.83%   |
| Acer Integrated Camera                   | 19        | 0.83%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 18        | 0.79%   |
| Quanta HD User Facing                    | 18        | 0.79%   |
| Acer SunplusIT Integrated Camera         | 18        | 0.79%   |
| Microdia Laptop_Integrated_Webcam_HD     | 17        | 0.74%   |
| IMC Networks Integrated Webcam           | 17        | 0.74%   |
| Bison Integrated Camera                  | 17        | 0.74%   |
| Chicony USB 2.0 Camera                   | 16        | 0.7%    |
| Realtek Integrated Webcam                | 15        | 0.66%   |
| Chicony USB2.0 VGA UVC WebCam            | 15        | 0.66%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 15        | 0.66%   |
| Lite-On HP HD Camera                     | 14        | 0.61%   |
| Chicony Integrated Camera (1280x720@30)  | 14        | 0.61%   |
| Chicony VGA Webcam                       | 13        | 0.57%   |
| Acer EasyCamera                          | 13        | 0.57%   |
| Sunplus HD WebCam                        | 12        | 0.53%   |
| Chicony HP HD Webcam [Fixed]             | 12        | 0.53%   |
| Sunplus Laptop_Integrated_Webcam_FHD     | 11        | 0.48%   |
| Silicon Motion WebCam SC-13HDL11939N     | 11        | 0.48%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 180       | 37.97%  |
| Synaptics                          | 103       | 21.73%  |
| Shenzhen Goodix Technology         | 56        | 11.81%  |
| AuthenTec                          | 56        | 11.81%  |
| Upek                               | 36        | 7.59%   |
| LighTuning Technology              | 15        | 3.16%   |
| Elan Microelectronics              | 14        | 2.95%   |
| STMicroelectronics                 | 13        | 2.74%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.21%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 38        | 8.02%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 38        | 8.02%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 35        | 7.38%   |
| Shenzhen Goodix  FingerPrint Device                                        | 31        | 6.54%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 24        | 5.06%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 23        | 4.85%   |
| AuthenTec AES2810                                                          | 23        | 4.85%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 20        | 4.22%   |
| Shenzhen Goodix Fingerprint Reader                                         | 20        | 4.22%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 17        | 3.59%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 14        | 2.95%   |
| STMicroelectronics Fingerprint Reader                                      | 13        | 2.74%   |
| Validity Sensors VFS491                                                    | 12        | 2.53%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 11        | 2.32%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 11        | 2.32%   |
| Elan ELAN:Fingerprint                                                      | 10        | 2.11%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 9         | 1.9%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 9         | 1.9%    |
| Validity Sensors Fingerprint scanner                                       | 9         | 1.9%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 8         | 1.69%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 8         | 1.69%   |
| Validity Sensors Synaptics WBDI                                            | 6         | 1.27%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 6         | 1.27%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 6         | 1.27%   |
| AuthenTec AES1600                                                          | 6         | 1.27%   |
| Validity Sensors VFS Fingerprint sensor                                    | 5         | 1.05%   |
| Shenzhen Goodix FingerPrint                                                | 5         | 1.05%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 1.05%   |
| AuthenTec Fingerprint Sensor                                               | 5         | 1.05%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 0.84%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 0.84%   |
| Synaptics WBDI                                                             | 4         | 0.84%   |
| Synaptics  WBDI                                                            | 4         | 0.84%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 0.84%   |
| LighTuning Fingerprint Reader                                              | 4         | 0.84%   |
| Elan ELAN:ARM-M4                                                           | 4         | 0.84%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 4         | 0.84%   |
| Synaptics WBDI Device                                                      | 3         | 0.63%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.42%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 0.42%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 210       | 57.07%  |
| Alcor Micro               | 73        | 19.84%  |
| O2 Micro                  | 41        | 11.14%  |
| Lenovo                    | 20        | 5.43%   |
| Upek                      | 19        | 5.16%   |
| Gemalto (was Gemplus)     | 4         | 1.09%   |
| Aladdin Knowledge Systems | 1         | 0.27%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 71        | 19.29%  |
| Broadcom BCM5880 Secure Applications Processor                               | 66        | 17.93%  |
| Broadcom 5880                                                                | 53        | 14.4%   |
| Broadcom 58200                                                               | 52        | 14.13%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 38        | 10.33%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 34        | 9.24%   |
| Lenovo Integrated Smart Card Reader                                          | 20        | 5.43%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 19        | 5.16%   |
| O2 Micro Oz776 SmartCard Reader                                              | 7         | 1.9%    |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.82%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.27%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.27%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.27%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.27%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.27%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1536      | 56.7%   |
| 1     | 892       | 32.93%  |
| 2     | 239       | 8.82%   |
| 3     | 34        | 1.26%   |
| 4     | 3         | 0.11%   |
| 7     | 2         | 0.07%   |
| 5     | 2         | 0.07%   |
| 6     | 1         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 469       | 32.23%  |
| Chipcard                 | 334       | 22.96%  |
| Graphics card            | 326       | 22.41%  |
| Net/wireless             | 89        | 6.12%   |
| Storage                  | 47        | 3.23%   |
| Multimedia controller    | 44        | 3.02%   |
| Bluetooth                | 40        | 2.75%   |
| Camera                   | 27        | 1.86%   |
| Communication controller | 25        | 1.72%   |
| Card reader              | 16        | 1.1%    |
| Sound                    | 10        | 0.69%   |
| Modem                    | 7         | 0.48%   |
| Firewire controller      | 5         | 0.34%   |
| Net/ethernet             | 4         | 0.27%   |
| Flash memory             | 3         | 0.21%   |
| Dvb card                 | 3         | 0.21%   |
| Network                  | 2         | 0.14%   |
| Wireless                 | 1         | 0.07%   |
| Unclassified device      | 1         | 0.07%   |
| Tv card                  | 1         | 0.07%   |
| Storage/raid             | 1         | 0.07%   |

