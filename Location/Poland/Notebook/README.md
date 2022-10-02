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

Total: 3253

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | [17ff3f8067](https://linux-hardware.org/?probe=17ff3f8067) | Sep 22, 2022 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | [0121aac33a](https://linux-hardware.org/?probe=0121aac33a) | Sep 22, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [de7c138e21](https://linux-hardware.org/?probe=de7c138e21) | Sep 22, 2022 |
| MSI           | Creator Z17 A12UHST         | [06c854fd7b](https://linux-hardware.org/?probe=06c854fd7b) | Sep 22, 2022 |
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
| MSI           | Creator Z17 A12UHST         | [3071865e76](https://linux-hardware.org/?probe=3071865e76) | Sep 02, 2022 |
| Dell          | Latitude E6220              | [99c8b865ad](https://linux-hardware.org/?probe=99c8b865ad) | Sep 02, 2022 |
| Dell          | Latitude E6330              | [179123f301](https://linux-hardware.org/?probe=179123f301) | Sep 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [21392e76a8](https://linux-hardware.org/?probe=21392e76a8) | Sep 01, 2022 |
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
| Acer          | Aspire A515-51G             | [9d271daa54](https://linux-hardware.org/?probe=9d271daa54) | Aug 13, 2022 |
| Acer          | Aspire A515-51G             | [f0e405bc07](https://linux-hardware.org/?probe=f0e405bc07) | Aug 13, 2022 |
| ASUSTek       | UX303LAB                    | [169419cea0](https://linux-hardware.org/?probe=169419cea0) | Aug 12, 2022 |
| HP            | ZBook 15 G4                 | [92cacb2a11](https://linux-hardware.org/?probe=92cacb2a11) | Aug 12, 2022 |
| HP            | EliteBook 2760p             | [0ce6a49a7f](https://linux-hardware.org/?probe=0ce6a49a7f) | Aug 12, 2022 |
| Lenovo        | Z710 20250                  | [8c7b1d0773](https://linux-hardware.org/?probe=8c7b1d0773) | Aug 11, 2022 |
| Lenovo        | G580 20150                  | [6a07e79eb7](https://linux-hardware.org/?probe=6a07e79eb7) | Aug 11, 2022 |
| Lenovo        | G580 20150                  | [7e83b07cca](https://linux-hardware.org/?probe=7e83b07cca) | Aug 11, 2022 |
| HP            | 255 G4                      | [3ed3978b93](https://linux-hardware.org/?probe=3ed3978b93) | Aug 11, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | [27eb779b2a](https://linux-hardware.org/?probe=27eb779b2a) | Aug 11, 2022 |
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
| Dell          | Latitude D420               | [162b346743](https://linux-hardware.org/?probe=162b346743) | Jul 02, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [10ff366630](https://linux-hardware.org/?probe=10ff366630) | Jul 01, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [2671f4ffe2](https://linux-hardware.org/?probe=2671f4ffe2) | Jul 01, 2022 |
| Lenovo        | ThinkPad T450s 20BX002NM... | [3bb2e1821b](https://linux-hardware.org/?probe=3bb2e1821b) | Jul 01, 2022 |
| Dell          | Latitude 3420               | [651ab17da0](https://linux-hardware.org/?probe=651ab17da0) | Jun 30, 2022 |
| Framework     | Laptop                      | [8a44001ebb](https://linux-hardware.org/?probe=8a44001ebb) | Jun 30, 2022 |
| Framework     | Laptop                      | [61a6480a38](https://linux-hardware.org/?probe=61a6480a38) | Jun 30, 2022 |
| Dell          | Inspiron 3451               | [6cf63ca19e](https://linux-hardware.org/?probe=6cf63ca19e) | Jun 30, 2022 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [0e09c926c1](https://linux-hardware.org/?probe=0e09c926c1) | Jun 30, 2022 |
| Dell          | Inspiron M5040              | [64c8f1ad3f](https://linux-hardware.org/?probe=64c8f1ad3f) | Jun 29, 2022 |
| Lenovo        | G580 20150                  | [dbe5fe496a](https://linux-hardware.org/?probe=dbe5fe496a) | Jun 29, 2022 |
| Getac         | B300-X                      | [eb752b6c15](https://linux-hardware.org/?probe=eb752b6c15) | Jun 29, 2022 |
| Lenovo        | ThinkPad T420 4180MY7       | [1e755c8031](https://linux-hardware.org/?probe=1e755c8031) | Jun 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [6dc02ab574](https://linux-hardware.org/?probe=6dc02ab574) | Jun 29, 2022 |
| Lenovo        | ThinkPad T420 4180MY7       | [a57e4e84f8](https://linux-hardware.org/?probe=a57e4e84f8) | Jun 29, 2022 |
| Dell          | Inspiron M5040              | [a9522b8288](https://linux-hardware.org/?probe=a9522b8288) | Jun 28, 2022 |
| Dell          | Latitude D420               | [c531c131ec](https://linux-hardware.org/?probe=c531c131ec) | Jun 28, 2022 |
| Dell          | Latitude 5511               | [c361c37273](https://linux-hardware.org/?probe=c361c37273) | Jun 28, 2022 |
| Lenovo        | ThinkPad T470 20HES07J00    | [4be29eb5f1](https://linux-hardware.org/?probe=4be29eb5f1) | Jun 27, 2022 |
| Dell          | Latitude 3190               | [3bf5b47ea1](https://linux-hardware.org/?probe=3bf5b47ea1) | Jun 27, 2022 |
| ASUSTek       | X751LK                      | [d7f4b1678b](https://linux-hardware.org/?probe=d7f4b1678b) | Jun 24, 2022 |
| ASUSTek       | X751LK                      | [09dfab066c](https://linux-hardware.org/?probe=09dfab066c) | Jun 24, 2022 |
| Lenovo        | ThinkPad T450 20BUS0QT04    | [0c96d2bc24](https://linux-hardware.org/?probe=0c96d2bc24) | Jun 24, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [ac634d8aa9](https://linux-hardware.org/?probe=ac634d8aa9) | Jun 23, 2022 |
| Acer          | Aspire E1-570               | [906b1f465e](https://linux-hardware.org/?probe=906b1f465e) | Jun 23, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [212cd0ac63](https://linux-hardware.org/?probe=212cd0ac63) | Jun 22, 2022 |
| Lenovo        | G50-30 80G0                 | [f82628e802](https://linux-hardware.org/?probe=f82628e802) | Jun 21, 2022 |
| Lenovo        | G50-30 80G0                 | [402aec2b04](https://linux-hardware.org/?probe=402aec2b04) | Jun 21, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [d6c4bb6995](https://linux-hardware.org/?probe=d6c4bb6995) | Jun 21, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [23f396c697](https://linux-hardware.org/?probe=23f396c697) | Jun 21, 2022 |
| HP            | Pavilion Notebook           | [551da1dbb6](https://linux-hardware.org/?probe=551da1dbb6) | Jun 20, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [52aa806063](https://linux-hardware.org/?probe=52aa806063) | Jun 20, 2022 |
| Dell          | Latitude 3190               | [bb05f51a63](https://linux-hardware.org/?probe=bb05f51a63) | Jun 20, 2022 |
| Dell          | Inspiron 3451               | [d9ac6a3f41](https://linux-hardware.org/?probe=d9ac6a3f41) | Jun 19, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [3c8a4e8226](https://linux-hardware.org/?probe=3c8a4e8226) | Jun 18, 2022 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [ee2f7822c9](https://linux-hardware.org/?probe=ee2f7822c9) | Jun 18, 2022 |
| Lenovo        | B570e HuronRiver Platfor... | [f944290604](https://linux-hardware.org/?probe=f944290604) | Jun 17, 2022 |
| Dell          | Latitude E5450              | [42f5a53e24](https://linux-hardware.org/?probe=42f5a53e24) | Jun 16, 2022 |
| Acer          | Aspire E1-570G              | [060b0319ff](https://linux-hardware.org/?probe=060b0319ff) | Jun 15, 2022 |
| mPTech        | ARC 11.6 128GB HD           | [b9469e3ae8](https://linux-hardware.org/?probe=b9469e3ae8) | Jun 15, 2022 |
| Dell          | Latitude E6430s             | [a1043bd5bf](https://linux-hardware.org/?probe=a1043bd5bf) | Jun 14, 2022 |
| ASUSTek       | 1005P                       | [4bd178fe29](https://linux-hardware.org/?probe=4bd178fe29) | Jun 14, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [35cbb5ff8b](https://linux-hardware.org/?probe=35cbb5ff8b) | Jun 14, 2022 |
| Dell          | Inspiron 3451               | [7ca7f789d8](https://linux-hardware.org/?probe=7ca7f789d8) | Jun 14, 2022 |
| Dell          | Latitude E5470              | [a4533cfbc7](https://linux-hardware.org/?probe=a4533cfbc7) | Jun 14, 2022 |
| Acer          | Aspire 7738                 | [39646d89f1](https://linux-hardware.org/?probe=39646d89f1) | Jun 14, 2022 |
| Acer          | TravelMate 5760             | [90e189c067](https://linux-hardware.org/?probe=90e189c067) | Jun 13, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [e33ea31f97](https://linux-hardware.org/?probe=e33ea31f97) | Jun 13, 2022 |
| HP            | EliteBook 850 G2            | [10b796ad9c](https://linux-hardware.org/?probe=10b796ad9c) | Jun 13, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [0a985a9f53](https://linux-hardware.org/?probe=0a985a9f53) | Jun 13, 2022 |
| MSI           | Bravo 17 A4DDR              | [fc31a9ec53](https://linux-hardware.org/?probe=fc31a9ec53) | Jun 13, 2022 |
| MSI           | Bravo 17 A4DDR              | [916ce4be3b](https://linux-hardware.org/?probe=916ce4be3b) | Jun 13, 2022 |
| Dell          | Latitude 3190               | [fb55b815b6](https://linux-hardware.org/?probe=fb55b815b6) | Jun 13, 2022 |
| HP            | ZBook Studio G3             | [0dda22b68b](https://linux-hardware.org/?probe=0dda22b68b) | Jun 12, 2022 |
| Lenovo        | ThinkPad T530 23923MG       | [cf21c4e831](https://linux-hardware.org/?probe=cf21c4e831) | Jun 12, 2022 |
| Lenovo        | M490s 20214                 | [961e8807e9](https://linux-hardware.org/?probe=961e8807e9) | Jun 12, 2022 |
| ASUSTek       | K53BR                       | [b64b9e0f4a](https://linux-hardware.org/?probe=b64b9e0f4a) | Jun 12, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | [0c1e336ddc](https://linux-hardware.org/?probe=0c1e336ddc) | Jun 11, 2022 |
| Acer          | Aspire A515-51G             | [785b725767](https://linux-hardware.org/?probe=785b725767) | Jun 10, 2022 |
| Dell          | Latitude 5310               | [fe0ffed6e4](https://linux-hardware.org/?probe=fe0ffed6e4) | Jun 10, 2022 |
| HP            | EliteBook 850 G3            | [e086b31446](https://linux-hardware.org/?probe=e086b31446) | Jun 10, 2022 |
| Lenovo        | ThinkPad P50 20EQS3B30R     | [c97b8918a0](https://linux-hardware.org/?probe=c97b8918a0) | Jun 10, 2022 |
| Dell          | Latitude E6420              | [a92cd16ef7](https://linux-hardware.org/?probe=a92cd16ef7) | Jun 10, 2022 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | [58d62f94d4](https://linux-hardware.org/?probe=58d62f94d4) | Jun 09, 2022 |
| Lenovo        | ThinkPad T500 2241A87       | [96b00f450d](https://linux-hardware.org/?probe=96b00f450d) | Jun 09, 2022 |
| Acer          | Nitro AN515-54              | [d14ead3bf7](https://linux-hardware.org/?probe=d14ead3bf7) | Jun 09, 2022 |
| HP            | ProBook 450 G5              | [cec4cb4af4](https://linux-hardware.org/?probe=cec4cb4af4) | Jun 09, 2022 |
| Acer          | Nitro AN515-54              | [76a0fe2907](https://linux-hardware.org/?probe=76a0fe2907) | Jun 09, 2022 |
| Lenovo        | ThinkPad T530 2429B68       | [86e92f8a19](https://linux-hardware.org/?probe=86e92f8a19) | Jun 09, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | [ebc62a50b4](https://linux-hardware.org/?probe=ebc62a50b4) | Jun 08, 2022 |
| Acer          | Swift SF314-42              | [5af5c89f5e](https://linux-hardware.org/?probe=5af5c89f5e) | Jun 08, 2022 |
| Dell          | Latitude 5421               | [24665e8e4b](https://linux-hardware.org/?probe=24665e8e4b) | Jun 08, 2022 |
| Dell          | Precision 5550              | [a4bf41771c](https://linux-hardware.org/?probe=a4bf41771c) | Jun 07, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [4655b6a8ed](https://linux-hardware.org/?probe=4655b6a8ed) | Jun 07, 2022 |
| Dell          | Inspiron 3451               | [a6feb9dcd2](https://linux-hardware.org/?probe=a6feb9dcd2) | Jun 07, 2022 |
| HP            | Pavilion dv6700             | [a688137dd3](https://linux-hardware.org/?probe=a688137dd3) | Jun 07, 2022 |
| Unknown       | Unknown                     | [c0625a957b](https://linux-hardware.org/?probe=c0625a957b) | Jun 06, 2022 |
| Dell          | Latitude 3190               | [190816b333](https://linux-hardware.org/?probe=190816b333) | Jun 06, 2022 |
| Dell          | Latitude E6430              | [95b7617708](https://linux-hardware.org/?probe=95b7617708) | Jun 05, 2022 |
| MSI           | PR601/VR603                 | [9763977184](https://linux-hardware.org/?probe=9763977184) | Jun 05, 2022 |
| Fujitsu       | FMVA0800C                   | [bacd4a55bb](https://linux-hardware.org/?probe=bacd4a55bb) | Jun 05, 2022 |
| Acer          | Swift SF314-42              | [8816abcee8](https://linux-hardware.org/?probe=8816abcee8) | Jun 03, 2022 |
| Acer          | Swift SF314-42              | [fbfcffd093](https://linux-hardware.org/?probe=fbfcffd093) | Jun 03, 2022 |
| Lenovo        | G580 20150                  | [ca44145e04](https://linux-hardware.org/?probe=ca44145e04) | Jun 03, 2022 |
| Dell          | Inspiron 3451               | [ba5e3a5d77](https://linux-hardware.org/?probe=ba5e3a5d77) | Jun 02, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [2db8072ec9](https://linux-hardware.org/?probe=2db8072ec9) | Jun 02, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [5b88aad243](https://linux-hardware.org/?probe=5b88aad243) | Jun 02, 2022 |
| Lenovo        | ThinkPad P17 Gen 1 20SQS... | [491a4105d8](https://linux-hardware.org/?probe=491a4105d8) | Jun 01, 2022 |
| Dell          | Inspiron 5749               | [408e42beb8](https://linux-hardware.org/?probe=408e42beb8) | Jun 01, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [d12c2f9f7c](https://linux-hardware.org/?probe=d12c2f9f7c) | Jun 01, 2022 |
| Dell          | Inspiron 3451               | [04e9ce0ba0](https://linux-hardware.org/?probe=04e9ce0ba0) | Jun 01, 2022 |
| Dell          | Inspiron 5521               | [4fdf9880d4](https://linux-hardware.org/?probe=4fdf9880d4) | May 31, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [1e6ab0f183](https://linux-hardware.org/?probe=1e6ab0f183) | May 31, 2022 |
| HP            | EliteBook 8440p             | [4df2d3c129](https://linux-hardware.org/?probe=4df2d3c129) | May 31, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [9b53c4df9d](https://linux-hardware.org/?probe=9b53c4df9d) | May 31, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [a08d3e5d4b](https://linux-hardware.org/?probe=a08d3e5d4b) | May 31, 2022 |
| Dell          | Latitude 5511               | [bc6fd9e79d](https://linux-hardware.org/?probe=bc6fd9e79d) | May 30, 2022 |
| Dell          | Latitude 3190               | [e43c62a67a](https://linux-hardware.org/?probe=e43c62a67a) | May 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [c71a8e9817](https://linux-hardware.org/?probe=c71a8e9817) | May 29, 2022 |
| HP            | Compaq 6510b (KE135EA#AK... | [28c05654fc](https://linux-hardware.org/?probe=28c05654fc) | May 29, 2022 |
| MSI           | GP76 Leopard 10UE           | [9e74d767a6](https://linux-hardware.org/?probe=9e74d767a6) | May 29, 2022 |
| Dell          | Inspiron 3451               | [8ad9f9f5d9](https://linux-hardware.org/?probe=8ad9f9f5d9) | May 29, 2022 |
| Lenovo        | IdeaPad Z500 20202          | [8e577a4a1a](https://linux-hardware.org/?probe=8e577a4a1a) | May 29, 2022 |
| Lenovo        | Z50-70 20354                | [cd40cf2e16](https://linux-hardware.org/?probe=cd40cf2e16) | May 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [ae044ab2d9](https://linux-hardware.org/?probe=ae044ab2d9) | May 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [b8c8e8baef](https://linux-hardware.org/?probe=b8c8e8baef) | May 27, 2022 |
| Dell          | Inspiron 3451               | [798f65546b](https://linux-hardware.org/?probe=798f65546b) | May 27, 2022 |
| Sony          | VPCEE3S1E                   | [f3c7988996](https://linux-hardware.org/?probe=f3c7988996) | May 27, 2022 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [cff9e3245c](https://linux-hardware.org/?probe=cff9e3245c) | May 25, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [29b8def5b3](https://linux-hardware.org/?probe=29b8def5b3) | May 25, 2022 |
| Dell          | Latitude 5310               | [2117fbfccb](https://linux-hardware.org/?probe=2117fbfccb) | May 25, 2022 |
| HP            | 250 G8 Notebook PC          | [ce09b72069](https://linux-hardware.org/?probe=ce09b72069) | May 25, 2022 |
| HP            | 250 G8 Notebook PC          | [cee3591bcd](https://linux-hardware.org/?probe=cee3591bcd) | May 25, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [0517751353](https://linux-hardware.org/?probe=0517751353) | May 24, 2022 |
| Dell          | Latitude 5310               | [cb40714b3f](https://linux-hardware.org/?probe=cb40714b3f) | May 24, 2022 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | [ed4df544d6](https://linux-hardware.org/?probe=ed4df544d6) | May 24, 2022 |
| HP            | Pavilion 15                 | [4140810d35](https://linux-hardware.org/?probe=4140810d35) | May 24, 2022 |
| HP            | 250 G8 Notebook PC          | [2f4c72e2a9](https://linux-hardware.org/?probe=2f4c72e2a9) | May 24, 2022 |
| HP            | ProBook 6475b               | [5202cf8c75](https://linux-hardware.org/?probe=5202cf8c75) | May 23, 2022 |
| HP            | Pavilion 15                 | [ca77af8ab9](https://linux-hardware.org/?probe=ca77af8ab9) | May 23, 2022 |
| Lenovo        | ThinkPad T61 7661BM5        | [9a6d69d512](https://linux-hardware.org/?probe=9a6d69d512) | May 22, 2022 |
| Lenovo        | Yoga Slim 9 14ITL5 82D1     | [d728114b9b](https://linux-hardware.org/?probe=d728114b9b) | May 22, 2022 |
| Acer          | Aspire E5-571G              | [8f47f3a71c](https://linux-hardware.org/?probe=8f47f3a71c) | May 22, 2022 |
| Acer          | Nitro AN515-54              | [04a8f20f28](https://linux-hardware.org/?probe=04a8f20f28) | May 21, 2022 |
| Dell          | Inspiron 3451               | [38c450f343](https://linux-hardware.org/?probe=38c450f343) | May 21, 2022 |
| Lenovo        | G50-70 20351                | [b6f469418c](https://linux-hardware.org/?probe=b6f469418c) | May 21, 2022 |
| Dell          | Latitude 5490               | [450756ee49](https://linux-hardware.org/?probe=450756ee49) | May 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [80d32848bf](https://linux-hardware.org/?probe=80d32848bf) | May 21, 2022 |
| Dell          | Inspiron 3451               | [d14ff2c62e](https://linux-hardware.org/?probe=d14ff2c62e) | May 20, 2022 |
| HP            | EliteBook 8570w             | [3f21c66d5c](https://linux-hardware.org/?probe=3f21c66d5c) | May 20, 2022 |
| HP            | EliteBook 850 G6            | [1b672f1faa](https://linux-hardware.org/?probe=1b672f1faa) | May 20, 2022 |
| HP            | EliteBook 850 G6            | [d2232927a7](https://linux-hardware.org/?probe=d2232927a7) | May 20, 2022 |
| HP            | 250 G4 Notebook PC          | [1472f65ca0](https://linux-hardware.org/?probe=1472f65ca0) | May 19, 2022 |
| Sony          | VGN-NR32L_S                 | [2709583292](https://linux-hardware.org/?probe=2709583292) | May 18, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [5e0b60c547](https://linux-hardware.org/?probe=5e0b60c547) | May 17, 2022 |
| Dell          | Latitude E6230              | [1afeba4362](https://linux-hardware.org/?probe=1afeba4362) | May 17, 2022 |
| Dell          | Inspiron 5735               | [b678e46de2](https://linux-hardware.org/?probe=b678e46de2) | May 17, 2022 |
| Sony          | VGN-FW51MF_H                | [084402167e](https://linux-hardware.org/?probe=084402167e) | May 17, 2022 |
| Toshiba       | Satellite L750D             | [6a84eb18c8](https://linux-hardware.org/?probe=6a84eb18c8) | May 16, 2022 |
| Dell          | Latitude 3190               | [e80556f7d6](https://linux-hardware.org/?probe=e80556f7d6) | May 16, 2022 |
| Dell          | Latitude 5580               | [c2f15d647a](https://linux-hardware.org/?probe=c2f15d647a) | May 15, 2022 |
| Dell          | Inspiron 3583               | [3589bb82ad](https://linux-hardware.org/?probe=3589bb82ad) | May 15, 2022 |
| HP            | Pavilion ZV6100 (EE984EA... | [59c5dbcb22](https://linux-hardware.org/?probe=59c5dbcb22) | May 15, 2022 |
| Lenovo        | ThinkPad T500 2241W2B       | [2bd7b2d9a4](https://linux-hardware.org/?probe=2bd7b2d9a4) | May 14, 2022 |
| Packard Be... | EasyNote ENTF71BM           | [e8808a770a](https://linux-hardware.org/?probe=e8808a770a) | May 14, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [5fad688f56](https://linux-hardware.org/?probe=5fad688f56) | May 14, 2022 |
| Dell          | MXG061                      | [36b09ae01e](https://linux-hardware.org/?probe=36b09ae01e) | May 14, 2022 |
| HP            | 250 G4 Notebook PC          | [996bc01199](https://linux-hardware.org/?probe=996bc01199) | May 13, 2022 |
| Lenovo        | ThinkPad Edge E430 3254A... | [761f1a1cbd](https://linux-hardware.org/?probe=761f1a1cbd) | May 13, 2022 |
| Dell          | Inspiron 3541               | [7873185850](https://linux-hardware.org/?probe=7873185850) | May 12, 2022 |
| HP            | EliteBook 820 G1            | [dd51bb3592](https://linux-hardware.org/?probe=dd51bb3592) | May 12, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [c64195c6bb](https://linux-hardware.org/?probe=c64195c6bb) | May 12, 2022 |
| HP            | EliteBook 840 G1            | [a57e3f28c2](https://linux-hardware.org/?probe=a57e3f28c2) | May 12, 2022 |
| Lenovo        | ThinkPad X200 7458WAY       | [1d845e69bd](https://linux-hardware.org/?probe=1d845e69bd) | May 11, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [7d03983e37](https://linux-hardware.org/?probe=7d03983e37) | May 11, 2022 |
| Dell          | Precision 7530              | [d97721b6cf](https://linux-hardware.org/?probe=d97721b6cf) | May 11, 2022 |
| Dell          | Inspiron 3583               | [5b2b56f445](https://linux-hardware.org/?probe=5b2b56f445) | May 11, 2022 |
| Lenovo        | V15-IIL 82C5                | [b02040672d](https://linux-hardware.org/?probe=b02040672d) | May 11, 2022 |
| Lenovo        | Yoga 300-11IBY 80M0         | [af186fe9e3](https://linux-hardware.org/?probe=af186fe9e3) | May 10, 2022 |
| Lenovo        | Yoga 300-11IBY 80M0         | [b6fed1d4fe](https://linux-hardware.org/?probe=b6fed1d4fe) | May 10, 2022 |
| HP            | EliteBook 820 G3            | [015ede2e58](https://linux-hardware.org/?probe=015ede2e58) | May 09, 2022 |
| HP            | EliteBook 8570w             | [840087bbed](https://linux-hardware.org/?probe=840087bbed) | May 09, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [9e81b04453](https://linux-hardware.org/?probe=9e81b04453) | May 09, 2022 |
| HP            | EliteBook 8570w             | [d9779b1c50](https://linux-hardware.org/?probe=d9779b1c50) | May 09, 2022 |
| Dell          | MXG061                      | [119f6dd774](https://linux-hardware.org/?probe=119f6dd774) | May 09, 2022 |
| Google        | Relm                        | [37a9101768](https://linux-hardware.org/?probe=37a9101768) | May 09, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [c302d389bc](https://linux-hardware.org/?probe=c302d389bc) | May 08, 2022 |
| Dell          | Latitude E6220              | [f5ba7cbb31](https://linux-hardware.org/?probe=f5ba7cbb31) | May 08, 2022 |
| Dell          | Vostro 1440                 | [a44eb19e96](https://linux-hardware.org/?probe=a44eb19e96) | May 08, 2022 |
| Dell          | Vostro 1440                 | [356b0ae168](https://linux-hardware.org/?probe=356b0ae168) | May 08, 2022 |
| Lenovo        | G510 20238                  | [8a5f88eca1](https://linux-hardware.org/?probe=8a5f88eca1) | May 08, 2022 |
| ASUSTek       | N76VZ                       | [f1e06f5c2f](https://linux-hardware.org/?probe=f1e06f5c2f) | May 08, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [9a1a0ce2f1](https://linux-hardware.org/?probe=9a1a0ce2f1) | May 08, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [880b5d5853](https://linux-hardware.org/?probe=880b5d5853) | May 07, 2022 |
| HP            | ProBook 4530s               | [76fc5ea6ce](https://linux-hardware.org/?probe=76fc5ea6ce) | May 06, 2022 |
| Apple         | MacBookPro8,2               | [87e8930fcf](https://linux-hardware.org/?probe=87e8930fcf) | May 06, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [fb4cf43d54](https://linux-hardware.org/?probe=fb4cf43d54) | May 05, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [503e18f6cb](https://linux-hardware.org/?probe=503e18f6cb) | May 05, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [76d61df983](https://linux-hardware.org/?probe=76d61df983) | May 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [a9f5b77476](https://linux-hardware.org/?probe=a9f5b77476) | May 04, 2022 |
| Acer          | Nitro AN515-54              | [1d9a559405](https://linux-hardware.org/?probe=1d9a559405) | May 04, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [ee3b3dc380](https://linux-hardware.org/?probe=ee3b3dc380) | May 04, 2022 |
| ASUSTek       | N76VZ                       | [b9c2a28ba0](https://linux-hardware.org/?probe=b9c2a28ba0) | May 03, 2022 |
| Lenovo        | ThinkPad T430 2349AK5       | [78f64f92f3](https://linux-hardware.org/?probe=78f64f92f3) | May 03, 2022 |
| ASUSTek       | X550CL                      | [b224821361](https://linux-hardware.org/?probe=b224821361) | May 03, 2022 |
| Toshiba       | Satellite C55t-C            | [7c1211e221](https://linux-hardware.org/?probe=7c1211e221) | May 02, 2022 |
| ASUSTek       | X705UAP                     | [5703c517d1](https://linux-hardware.org/?probe=5703c517d1) | May 02, 2022 |
| Acer          | Aspire E5-571G              | [8df6782398](https://linux-hardware.org/?probe=8df6782398) | May 02, 2022 |
| ASUSTek       | X550CL                      | [5340c940c2](https://linux-hardware.org/?probe=5340c940c2) | May 02, 2022 |
| ASUSTek       | X580VD                      | [920fb8f8d8](https://linux-hardware.org/?probe=920fb8f8d8) | May 01, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [112d0557c3](https://linux-hardware.org/?probe=112d0557c3) | May 01, 2022 |
| Fujitsu       | LIFEBOOK S751               | [6150343dc0](https://linux-hardware.org/?probe=6150343dc0) | May 01, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [317736e849](https://linux-hardware.org/?probe=317736e849) | May 01, 2022 |
| Toshiba       | Satellite C55t-C            | [dd21a03b63](https://linux-hardware.org/?probe=dd21a03b63) | May 01, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [ea3bd2e330](https://linux-hardware.org/?probe=ea3bd2e330) | May 01, 2022 |
| Apple         | MacBookPro7,1               | [ac3f2c5c61](https://linux-hardware.org/?probe=ac3f2c5c61) | May 01, 2022 |
| Acer          | Extensa 5220                | [ebbd01171d](https://linux-hardware.org/?probe=ebbd01171d) | May 01, 2022 |
| Lenovo        | G510 20238                  | [07e8a61019](https://linux-hardware.org/?probe=07e8a61019) | Apr 30, 2022 |
| ASUSTek       | UX303LAB                    | [4d47234d72](https://linux-hardware.org/?probe=4d47234d72) | Apr 30, 2022 |
| Acer          | Aspire E5-571               | [35b5fa2276](https://linux-hardware.org/?probe=35b5fa2276) | Apr 30, 2022 |
| ASUSTek       | X71Vn                       | [b31a7dce8b](https://linux-hardware.org/?probe=b31a7dce8b) | Apr 29, 2022 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [2c8a1c2444](https://linux-hardware.org/?probe=2c8a1c2444) | Apr 29, 2022 |
| Apple         | MacBook3,1                  | [5c90931c74](https://linux-hardware.org/?probe=5c90931c74) | Apr 28, 2022 |
| Lenovo        | ThinkPad Edge E430 3254A... | [00474d7e97](https://linux-hardware.org/?probe=00474d7e97) | Apr 28, 2022 |
| Lenovo        | ThinkPad Edge E430 3254A... | [3c9c9f209d](https://linux-hardware.org/?probe=3c9c9f209d) | Apr 28, 2022 |
| Dell          | Latitude 5420               | [26abde11eb](https://linux-hardware.org/?probe=26abde11eb) | Apr 28, 2022 |
| Apple         | MacBook3,1                  | [c7da3d4c4f](https://linux-hardware.org/?probe=c7da3d4c4f) | Apr 27, 2022 |
| Acer          | Nitro AN515-43              | [99527fd065](https://linux-hardware.org/?probe=99527fd065) | Apr 26, 2022 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [482bb47b36](https://linux-hardware.org/?probe=482bb47b36) | Apr 26, 2022 |
| HP            | EliteBook 8770w             | [4fa8e91f6d](https://linux-hardware.org/?probe=4fa8e91f6d) | Apr 26, 2022 |
| Dell          | Latitude 7520               | [674f3ca531](https://linux-hardware.org/?probe=674f3ca531) | Apr 26, 2022 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | [489a3a5798](https://linux-hardware.org/?probe=489a3a5798) | Apr 26, 2022 |
| HP            | EliteBook 8440p             | [c854b74386](https://linux-hardware.org/?probe=c854b74386) | Apr 25, 2022 |
| Dell          | Precision 7510              | [484a851b85](https://linux-hardware.org/?probe=484a851b85) | Apr 25, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [06a00cfce7](https://linux-hardware.org/?probe=06a00cfce7) | Apr 25, 2022 |
| HP            | Pavilion 17                 | [8a86695a31](https://linux-hardware.org/?probe=8a86695a31) | Apr 25, 2022 |
| MSI           | PE60 2QE                    | [703b37d444](https://linux-hardware.org/?probe=703b37d444) | Apr 24, 2022 |
| Lenovo        | Yoga S740-14IIL 81RS        | [ac10947315](https://linux-hardware.org/?probe=ac10947315) | Apr 24, 2022 |
| HUAWEI        | HVY-WXX9                    | [43098a1f34](https://linux-hardware.org/?probe=43098a1f34) | Apr 23, 2022 |
| HP            | EliteBook 8440p             | [487f1a4924](https://linux-hardware.org/?probe=487f1a4924) | Apr 23, 2022 |
| Acer          | Aspire E1-531               | [c1cd0a61e1](https://linux-hardware.org/?probe=c1cd0a61e1) | Apr 23, 2022 |
| HP            | Pavilion 17                 | [851d01ca2e](https://linux-hardware.org/?probe=851d01ca2e) | Apr 23, 2022 |
| Dell          | Inspiron 3542               | [0c301210d8](https://linux-hardware.org/?probe=0c301210d8) | Apr 22, 2022 |
| ASUSTek       | X541UJ                      | [4043c70a42](https://linux-hardware.org/?probe=4043c70a42) | Apr 22, 2022 |
| HUAWEI        | HVY-WXX9                    | [3320719d25](https://linux-hardware.org/?probe=3320719d25) | Apr 22, 2022 |
| MSI           | GE60 2PC                    | [0614a4172b](https://linux-hardware.org/?probe=0614a4172b) | Apr 22, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [b6a457c33a](https://linux-hardware.org/?probe=b6a457c33a) | Apr 21, 2022 |
| Dell          | Latitude E6420              | [83b008961c](https://linux-hardware.org/?probe=83b008961c) | Apr 21, 2022 |
| Samsung       | RC410/RC510/RC710           | [9adfada605](https://linux-hardware.org/?probe=9adfada605) | Apr 20, 2022 |
| Dell          | Latitude E6420              | [85d321a02b](https://linux-hardware.org/?probe=85d321a02b) | Apr 20, 2022 |
| Dell          | Inspiron 15-3567            | [b87e7c08ab](https://linux-hardware.org/?probe=b87e7c08ab) | Apr 19, 2022 |
| HP            | ProBook 6440b               | [54a85fc99d](https://linux-hardware.org/?probe=54a85fc99d) | Apr 18, 2022 |
| Lenovo        | ThinkPad Edge E430 3254C... | [df0e3664e4](https://linux-hardware.org/?probe=df0e3664e4) | Apr 17, 2022 |
| MSI           | GF75 Thin 10UEK             | [866aa88f0f](https://linux-hardware.org/?probe=866aa88f0f) | Apr 17, 2022 |
| ASUSTek       | S551LB                      | [bb1d6d3623](https://linux-hardware.org/?probe=bb1d6d3623) | Apr 17, 2022 |
| HP            | Pavilion g6                 | [a7f800ed49](https://linux-hardware.org/?probe=a7f800ed49) | Apr 16, 2022 |
| Dell          | Inspiron 5570               | [066d125002](https://linux-hardware.org/?probe=066d125002) | Apr 15, 2022 |
| Acer          | Nitro AN515-42              | [f203fe95e5](https://linux-hardware.org/?probe=f203fe95e5) | Apr 15, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [77cf6f482e](https://linux-hardware.org/?probe=77cf6f482e) | Apr 15, 2022 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [13bfd82a49](https://linux-hardware.org/?probe=13bfd82a49) | Apr 14, 2022 |
| ASUSTek       | N61Jv                       | [959c5f2238](https://linux-hardware.org/?probe=959c5f2238) | Apr 14, 2022 |
| Sony          | VGN-FZ11M                   | [23731be3a1](https://linux-hardware.org/?probe=23731be3a1) | Apr 14, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [154eb4b040](https://linux-hardware.org/?probe=154eb4b040) | Apr 14, 2022 |
| Lenovo        | G500 20236                  | [2decdc1731](https://linux-hardware.org/?probe=2decdc1731) | Apr 14, 2022 |
| Lenovo        | ThinkPad Edge E430 3254C... | [155a0f970f](https://linux-hardware.org/?probe=155a0f970f) | Apr 13, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [7e6cb72711](https://linux-hardware.org/?probe=7e6cb72711) | Apr 13, 2022 |
| Lenovo        | ThinkPad X260 20F5S4BY00    | [729b19eda3](https://linux-hardware.org/?probe=729b19eda3) | Apr 13, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [f2588a9d63](https://linux-hardware.org/?probe=f2588a9d63) | Apr 13, 2022 |
| Toshiba       | Satellite A300              | [1773d841d4](https://linux-hardware.org/?probe=1773d841d4) | Apr 13, 2022 |
| Dell          | Latitude E6420              | [7491167b48](https://linux-hardware.org/?probe=7491167b48) | Apr 13, 2022 |
| Dell          | Latitude E6420              | [3a6e6c7a62](https://linux-hardware.org/?probe=3a6e6c7a62) | Apr 13, 2022 |
| Dell          | Inspiron 17 7000 Series ... | [c8abf66820](https://linux-hardware.org/?probe=c8abf66820) | Apr 12, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | [c3d7c67155](https://linux-hardware.org/?probe=c3d7c67155) | Apr 12, 2022 |
| Dell          | Latitude 5480               | [f733f24fdc](https://linux-hardware.org/?probe=f733f24fdc) | Apr 12, 2022 |
| HUAWEI        | KLVL-WXX9                   | [47cecc43f6](https://linux-hardware.org/?probe=47cecc43f6) | Apr 11, 2022 |
| Lenovo        | 3000 V200 076472G           | [11a06d9b03](https://linux-hardware.org/?probe=11a06d9b03) | Apr 10, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | [7f5ccf9e6d](https://linux-hardware.org/?probe=7f5ccf9e6d) | Apr 10, 2022 |
| ASUSTek       | X553MA                      | [68e49479b4](https://linux-hardware.org/?probe=68e49479b4) | Apr 09, 2022 |
| Lenovo        | Z51-70 80K6                 | [dc1db2125f](https://linux-hardware.org/?probe=dc1db2125f) | Apr 08, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [414464db43](https://linux-hardware.org/?probe=414464db43) | Apr 08, 2022 |
| Dell          | Latitude 5480               | [6891954221](https://linux-hardware.org/?probe=6891954221) | Apr 08, 2022 |
| Dell          | Inspiron 5515               | [de3e7023c4](https://linux-hardware.org/?probe=de3e7023c4) | Apr 08, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [556d9d27ef](https://linux-hardware.org/?probe=556d9d27ef) | Apr 07, 2022 |
| Dell          | Latitude E4310              | [e89d84e0dd](https://linux-hardware.org/?probe=e89d84e0dd) | Apr 07, 2022 |
| HP            | EliteBook 840 G2            | [691c061ef4](https://linux-hardware.org/?probe=691c061ef4) | Apr 07, 2022 |
| Dell          | Latitude 5521               | [ce1e3c5551](https://linux-hardware.org/?probe=ce1e3c5551) | Apr 07, 2022 |
| Dell          | Latitude 5480               | [4e82478bdf](https://linux-hardware.org/?probe=4e82478bdf) | Apr 07, 2022 |
| Dell          | MXG061                      | [3ff1cc3367](https://linux-hardware.org/?probe=3ff1cc3367) | Apr 07, 2022 |
| Dell          | MXG061                      | [9c91bd9487](https://linux-hardware.org/?probe=9c91bd9487) | Apr 06, 2022 |
| ASUSTek       | VivoBook E14 E402YA_E402... | [9536873aca](https://linux-hardware.org/?probe=9536873aca) | Apr 06, 2022 |
| Acer          | Aspire E5-774G              | [2e61b0b4d5](https://linux-hardware.org/?probe=2e61b0b4d5) | Apr 05, 2022 |
| Apple         | MacBookAir4,2               | [0c1f8b4efe](https://linux-hardware.org/?probe=0c1f8b4efe) | Apr 05, 2022 |
| Lenovo        | G580 20150                  | [d85f7abf8c](https://linux-hardware.org/?probe=d85f7abf8c) | Apr 05, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [81165aa277](https://linux-hardware.org/?probe=81165aa277) | Apr 05, 2022 |
| Acer          | TravelMate P215-41-G2       | [4e35add210](https://linux-hardware.org/?probe=4e35add210) | Apr 04, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [37b0484558](https://linux-hardware.org/?probe=37b0484558) | Apr 04, 2022 |
| Dell          | Latitude 5421               | [78ac6f00cd](https://linux-hardware.org/?probe=78ac6f00cd) | Apr 04, 2022 |
| Apple         | MacBookPro12,1              | [44a524bb2f](https://linux-hardware.org/?probe=44a524bb2f) | Apr 03, 2022 |
| Acer          | Nitro AN515-43              | [e6e1af5316](https://linux-hardware.org/?probe=e6e1af5316) | Apr 03, 2022 |
| HP            | Unknown                     | [e33741c278](https://linux-hardware.org/?probe=e33741c278) | Apr 03, 2022 |
| HP            | Pavilion g6                 | [6f774cb7a9](https://linux-hardware.org/?probe=6f774cb7a9) | Apr 03, 2022 |
| Acer          | Nitro AN515-52              | [51980559c7](https://linux-hardware.org/?probe=51980559c7) | Apr 03, 2022 |
| HP            | ProBook 650 G1              | [f13dbb1e06](https://linux-hardware.org/?probe=f13dbb1e06) | Apr 02, 2022 |
| HP            | 255 G7 Notebook PC          | [a7d794c2d8](https://linux-hardware.org/?probe=a7d794c2d8) | Apr 02, 2022 |
| HP            | Unknown                     | [761f0c08b2](https://linux-hardware.org/?probe=761f0c08b2) | Apr 02, 2022 |
| Dell          | Inspiron MM061              | [ca95a8324a](https://linux-hardware.org/?probe=ca95a8324a) | Apr 02, 2022 |
| Dell          | Inspiron MM061              | [a6f8e740aa](https://linux-hardware.org/?probe=a6f8e740aa) | Apr 02, 2022 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [f1ceaa5222](https://linux-hardware.org/?probe=f1ceaa5222) | Apr 02, 2022 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [ce4341b7b1](https://linux-hardware.org/?probe=ce4341b7b1) | Apr 01, 2022 |
| HP            | EliteBook 820 G2            | [5308b25e76](https://linux-hardware.org/?probe=5308b25e76) | Mar 31, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [eeb03a5d88](https://linux-hardware.org/?probe=eeb03a5d88) | Mar 31, 2022 |
| Valve         | Jupiter                     | [d8625616de](https://linux-hardware.org/?probe=d8625616de) | Mar 30, 2022 |
| Acer          | Nitro AN515-43              | [d1c02dfaee](https://linux-hardware.org/?probe=d1c02dfaee) | Mar 29, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [fc7ebbef4e](https://linux-hardware.org/?probe=fc7ebbef4e) | Mar 29, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [ab2bed88a7](https://linux-hardware.org/?probe=ab2bed88a7) | Mar 29, 2022 |
| Dell          | XPS 15 7590                 | [426b141f91](https://linux-hardware.org/?probe=426b141f91) | Mar 29, 2022 |
| ASUSTek       | UX310UA                     | [b052cccfb8](https://linux-hardware.org/?probe=b052cccfb8) | Mar 27, 2022 |
| Dell          | MXG071                      | [ac0158dcb9](https://linux-hardware.org/?probe=ac0158dcb9) | Mar 27, 2022 |
| Dell          | Inspiron 5758               | [ddd5e24256](https://linux-hardware.org/?probe=ddd5e24256) | Mar 26, 2022 |
| MAXDATA       | ECO4510IW                   | [d731c99bf8](https://linux-hardware.org/?probe=d731c99bf8) | Mar 26, 2022 |
| Dell          | Latitude E7450              | [db931ebb1f](https://linux-hardware.org/?probe=db931ebb1f) | Mar 25, 2022 |
| Dell          | Latitude 5420               | [fed42f2345](https://linux-hardware.org/?probe=fed42f2345) | Mar 25, 2022 |
| MSI           | Modern 14 B4MW              | [744a69ec7d](https://linux-hardware.org/?probe=744a69ec7d) | Mar 25, 2022 |
| HP            | ProBook 6570b               | [41548696b7](https://linux-hardware.org/?probe=41548696b7) | Mar 23, 2022 |
| HP            | Pavilion ZV6100 (EE984EA... | [282dfe7eb0](https://linux-hardware.org/?probe=282dfe7eb0) | Mar 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [f7f7b2d459](https://linux-hardware.org/?probe=f7f7b2d459) | Mar 22, 2022 |
| Packard Be... | EasyNote TK85               | [7b2ab61a6e](https://linux-hardware.org/?probe=7b2ab61a6e) | Mar 21, 2022 |
| Dell          | System Inspiron N7110       | [d3b1757cf5](https://linux-hardware.org/?probe=d3b1757cf5) | Mar 21, 2022 |
| Lenovo        | ThinkPad P72 20MBCTO1WW     | [ceb4f22239](https://linux-hardware.org/?probe=ceb4f22239) | Mar 20, 2022 |
| Lenovo        | ThinkPad X230 2325BA3       | [d4170940f0](https://linux-hardware.org/?probe=d4170940f0) | Mar 20, 2022 |
| Lenovo        | ThinkPad P72 20MBCTO1WW     | [7a5bd54a22](https://linux-hardware.org/?probe=7a5bd54a22) | Mar 19, 2022 |
| ASUSTek       | VivoBook S15 X510UF         | [93eefcdc91](https://linux-hardware.org/?probe=93eefcdc91) | Mar 19, 2022 |
| ASUSTek       | K50IJ                       | [5ee99a6dc2](https://linux-hardware.org/?probe=5ee99a6dc2) | Mar 19, 2022 |
| HP            | Laptop 15s-fq2xxx           | [3e69b565cd](https://linux-hardware.org/?probe=3e69b565cd) | Mar 19, 2022 |
| Dell          | MXG071                      | [aefb0e99b0](https://linux-hardware.org/?probe=aefb0e99b0) | Mar 18, 2022 |
| Dell          | Latitude 5285               | [662d409a76](https://linux-hardware.org/?probe=662d409a76) | Mar 18, 2022 |
| Dell          | Latitude 5285               | [fb9225d49b](https://linux-hardware.org/?probe=fb9225d49b) | Mar 18, 2022 |
| Sony          | VGN-NR11Z_S                 | [db19537f6e](https://linux-hardware.org/?probe=db19537f6e) | Mar 16, 2022 |
| Samsung       | N150P/N210P/N220P           | [a524460989](https://linux-hardware.org/?probe=a524460989) | Mar 16, 2022 |
| HUAWEI        | KLVL-WXX9                   | [91eab99551](https://linux-hardware.org/?probe=91eab99551) | Mar 15, 2022 |
| Dell          | Latitude E6410              | [a604ce30de](https://linux-hardware.org/?probe=a604ce30de) | Mar 14, 2022 |
| Dell          | Latitude D630               | [707be96775](https://linux-hardware.org/?probe=707be96775) | Mar 13, 2022 |
| Lenovo        | ThinkPad X230 2325DV5       | [c622952988](https://linux-hardware.org/?probe=c622952988) | Mar 13, 2022 |
| ASUSTek       | X540YA                      | [189a024100](https://linux-hardware.org/?probe=189a024100) | Mar 12, 2022 |
| ASUSTek       | X540YA                      | [5ad420d2d3](https://linux-hardware.org/?probe=5ad420d2d3) | Mar 12, 2022 |
| Lenovo        | G580 20150                  | [1eeedb6d3e](https://linux-hardware.org/?probe=1eeedb6d3e) | Mar 12, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [e1e251e8aa](https://linux-hardware.org/?probe=e1e251e8aa) | Mar 12, 2022 |
| Apple         | MacBookPro14,3              | [4d955ba9c5](https://linux-hardware.org/?probe=4d955ba9c5) | Mar 12, 2022 |
| Lenovo        | G780 20138                  | [276b115350](https://linux-hardware.org/?probe=276b115350) | Mar 12, 2022 |
| Dell          | XPS 15 9500                 | [f306866523](https://linux-hardware.org/?probe=f306866523) | Mar 11, 2022 |
| GPD           | MicroPC                     | [a572eb2b39](https://linux-hardware.org/?probe=a572eb2b39) | Mar 11, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [f031fb1a5a](https://linux-hardware.org/?probe=f031fb1a5a) | Mar 11, 2022 |
| Dell          | XPS 15 9500                 | [7d27557ebe](https://linux-hardware.org/?probe=7d27557ebe) | Mar 11, 2022 |
| HP            | ProBook 6570b               | [7c9eeb8608](https://linux-hardware.org/?probe=7c9eeb8608) | Mar 10, 2022 |
| Acer          | Aspire 5732Z                | [9f926d363e](https://linux-hardware.org/?probe=9f926d363e) | Mar 10, 2022 |
| Lenovo        | ThinkPad T490 20N2000KRT    | [4766fe6362](https://linux-hardware.org/?probe=4766fe6362) | Mar 10, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [05b4cceab2](https://linux-hardware.org/?probe=05b4cceab2) | Mar 10, 2022 |
| Acer          | Swift SF314-42              | [68e933e6a3](https://linux-hardware.org/?probe=68e933e6a3) | Mar 10, 2022 |
| Fujitsu Si... | AMILO Li3910                | [8762e9c632](https://linux-hardware.org/?probe=8762e9c632) | Mar 10, 2022 |
| Lenovo        | B590 20208                  | [46d63f7527](https://linux-hardware.org/?probe=46d63f7527) | Mar 10, 2022 |
| Acer          | Extensa 5220                | [fa85be94b2](https://linux-hardware.org/?probe=fa85be94b2) | Mar 09, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [d5e5a6fd60](https://linux-hardware.org/?probe=d5e5a6fd60) | Mar 09, 2022 |
| HP            | EliteBook 840 G2            | [b22eb4fbeb](https://linux-hardware.org/?probe=b22eb4fbeb) | Mar 09, 2022 |
| ASUSTek       | F3Sr                        | [ab9d32a3ff](https://linux-hardware.org/?probe=ab9d32a3ff) | Mar 08, 2022 |
| HP            | 15                          | [5b2f656c49](https://linux-hardware.org/?probe=5b2f656c49) | Mar 08, 2022 |
| Toshiba       | Satellite U400              | [e21b12ca9f](https://linux-hardware.org/?probe=e21b12ca9f) | Mar 07, 2022 |
| Dell          | Latitude D830               | [a1fd190f57](https://linux-hardware.org/?probe=a1fd190f57) | Mar 06, 2022 |
| Dell          | MXG071                      | [62a45db2eb](https://linux-hardware.org/?probe=62a45db2eb) | Mar 06, 2022 |
| Lenovo        | G580 20150                  | [a75c798641](https://linux-hardware.org/?probe=a75c798641) | Mar 06, 2022 |
| HUAWEI        | HVY-WXX9                    | [fc4d2904c3](https://linux-hardware.org/?probe=fc4d2904c3) | Mar 06, 2022 |
| MSI           | Vector GP66 12UGS           | [be60e729e2](https://linux-hardware.org/?probe=be60e729e2) | Mar 06, 2022 |
| Lenovo        | ThinkPad T420 4177R3U       | [2d58d0613a](https://linux-hardware.org/?probe=2d58d0613a) | Mar 05, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [7e97d74a65](https://linux-hardware.org/?probe=7e97d74a65) | Mar 05, 2022 |
| Acer          | Swift SF314-59              | [d549055064](https://linux-hardware.org/?probe=d549055064) | Mar 05, 2022 |
| Dell          | Inspiron 1545               | [bb9daa5ab1](https://linux-hardware.org/?probe=bb9daa5ab1) | Mar 05, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [d8b5a59b27](https://linux-hardware.org/?probe=d8b5a59b27) | Mar 05, 2022 |
| Dell          | Latitude E5500              | [0f590ac9e5](https://linux-hardware.org/?probe=0f590ac9e5) | Mar 05, 2022 |
| Toshiba       | TECRA M11                   | [ff568f1c19](https://linux-hardware.org/?probe=ff568f1c19) | Mar 05, 2022 |
| Lenovo        | G570 20079                  | [55a854b0c1](https://linux-hardware.org/?probe=55a854b0c1) | Mar 04, 2022 |
| ASUSTek       | F3E                         | [67c210b75c](https://linux-hardware.org/?probe=67c210b75c) | Mar 04, 2022 |
| ASUSTek       | UX303LAB                    | [019eeb069d](https://linux-hardware.org/?probe=019eeb069d) | Mar 03, 2022 |
| Lenovo        | ThinkPad T430 2349T7Z       | [b567c4922e](https://linux-hardware.org/?probe=b567c4922e) | Mar 03, 2022 |
| Dell          | Latitude E7240              | [7004ac549b](https://linux-hardware.org/?probe=7004ac549b) | Mar 03, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [12ab030882](https://linux-hardware.org/?probe=12ab030882) | Mar 02, 2022 |
| ASUSTek       | K50IJ                       | [fde5cc4a6c](https://linux-hardware.org/?probe=fde5cc4a6c) | Mar 01, 2022 |
| Dell          | Latitude 3190               | [964420352c](https://linux-hardware.org/?probe=964420352c) | Feb 28, 2022 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [58d47eab9c](https://linux-hardware.org/?probe=58d47eab9c) | Feb 28, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [c7db8c9806](https://linux-hardware.org/?probe=c7db8c9806) | Feb 27, 2022 |
| Dell          | G5 5590                     | [f553433011](https://linux-hardware.org/?probe=f553433011) | Feb 27, 2022 |
| Samsung       | NC210/NC110                 | [a593b663f7](https://linux-hardware.org/?probe=a593b663f7) | Feb 27, 2022 |
| Samsung       | NC210/NC110                 | [c9670fc791](https://linux-hardware.org/?probe=c9670fc791) | Feb 27, 2022 |
| Dell          | Latitude E5500              | [c84caad5a2](https://linux-hardware.org/?probe=c84caad5a2) | Feb 26, 2022 |
| Dell          | Latitude E5500              | [38a51b4721](https://linux-hardware.org/?probe=38a51b4721) | Feb 26, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [cd544b4dbb](https://linux-hardware.org/?probe=cd544b4dbb) | Feb 26, 2022 |
| Acer          | Aspire A515-56              | [bedf3d3105](https://linux-hardware.org/?probe=bedf3d3105) | Feb 26, 2022 |
| Lenovo        | Yoga Slim 7 14IIL05 82A1    | [0022f4a8cc](https://linux-hardware.org/?probe=0022f4a8cc) | Feb 26, 2022 |
| Sony          | VGN-FW21E                   | [930ce5581f](https://linux-hardware.org/?probe=930ce5581f) | Feb 25, 2022 |
| Lenovo        | ThinkPad T430 2350B58       | [f247d6c3ca](https://linux-hardware.org/?probe=f247d6c3ca) | Feb 25, 2022 |
| Lenovo        | ThinkPad T430 2350B58       | [ececeadefe](https://linux-hardware.org/?probe=ececeadefe) | Feb 25, 2022 |
| Google        | Stout                       | [5d6d43c8d1](https://linux-hardware.org/?probe=5d6d43c8d1) | Feb 25, 2022 |
| Google        | Snappy                      | [cf0b11bd65](https://linux-hardware.org/?probe=cf0b11bd65) | Feb 24, 2022 |
| HP            | Compaq 6730s                | [4ef0d3d150](https://linux-hardware.org/?probe=4ef0d3d150) | Feb 23, 2022 |
| ASUSTek       | U32U                        | [b7944a1493](https://linux-hardware.org/?probe=b7944a1493) | Feb 23, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [b27662968a](https://linux-hardware.org/?probe=b27662968a) | Feb 23, 2022 |
| HP            | Laptop 15-db1xxx            | [ad30c9f5ed](https://linux-hardware.org/?probe=ad30c9f5ed) | Feb 23, 2022 |
| Acer          | Aspire A517-52              | [52976ad94b](https://linux-hardware.org/?probe=52976ad94b) | Feb 23, 2022 |
| MSI           | Modern 14 B4MW              | [1527f67c84](https://linux-hardware.org/?probe=1527f67c84) | Feb 23, 2022 |
| Dell          | Latitude E5520              | [323ea2506d](https://linux-hardware.org/?probe=323ea2506d) | Feb 23, 2022 |
| HP            | Pavilion 17                 | [a764257e87](https://linux-hardware.org/?probe=a764257e87) | Feb 23, 2022 |
| HP            | Pavilion 17                 | [fb04348031](https://linux-hardware.org/?probe=fb04348031) | Feb 22, 2022 |
| Dell          | Latitude 5310               | [5ee9055243](https://linux-hardware.org/?probe=5ee9055243) | Feb 22, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [78e355e895](https://linux-hardware.org/?probe=78e355e895) | Feb 21, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [1adb30dfb2](https://linux-hardware.org/?probe=1adb30dfb2) | Feb 21, 2022 |
| Dell          | Latitude E6440              | [2585c1cfb6](https://linux-hardware.org/?probe=2585c1cfb6) | Feb 21, 2022 |
| Acer          | Aspire E5-511               | [6b5a96e6cf](https://linux-hardware.org/?probe=6b5a96e6cf) | Feb 19, 2022 |
| Toshiba       | dynabook Satellite B552/... | [b86bbc9d7c](https://linux-hardware.org/?probe=b86bbc9d7c) | Feb 19, 2022 |
| ASUSTek       | K50IJ                       | [e8a3ceb5a9](https://linux-hardware.org/?probe=e8a3ceb5a9) | Feb 18, 2022 |
| Lenovo        | ThinkPad T420s 41742AG      | [042758bceb](https://linux-hardware.org/?probe=042758bceb) | Feb 18, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [482b871e32](https://linux-hardware.org/?probe=482b871e32) | Feb 18, 2022 |
| HP            | Laptop 15-db0xxx            | [a59f3617da](https://linux-hardware.org/?probe=a59f3617da) | Feb 18, 2022 |
| Dell          | Precision M4500             | [7a7c096aa2](https://linux-hardware.org/?probe=7a7c096aa2) | Feb 18, 2022 |
| Lenovo        | ThinkPad T61 6458CTO        | [9081d7a51d](https://linux-hardware.org/?probe=9081d7a51d) | Feb 17, 2022 |
| Lenovo        | ThinkPad T61 6458CTO        | [4f0437053f](https://linux-hardware.org/?probe=4f0437053f) | Feb 17, 2022 |
| Dell          | Latitude XT3                | [fc930f1855](https://linux-hardware.org/?probe=fc930f1855) | Feb 17, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [d0e44d293a](https://linux-hardware.org/?probe=d0e44d293a) | Feb 16, 2022 |
| HP            | 250 G7 Notebook PC          | [ec267cea8d](https://linux-hardware.org/?probe=ec267cea8d) | Feb 15, 2022 |
| Dell          | Latitude E6430              | [e1de4e80fe](https://linux-hardware.org/?probe=e1de4e80fe) | Feb 15, 2022 |
| HP            | Grunt                       | [5d685ec102](https://linux-hardware.org/?probe=5d685ec102) | Feb 15, 2022 |
| Getac         | V100-X                      | [396c65c24c](https://linux-hardware.org/?probe=396c65c24c) | Feb 15, 2022 |
| Dell          | Inspiron 5502               | [79b0957899](https://linux-hardware.org/?probe=79b0957899) | Feb 14, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [25518083e9](https://linux-hardware.org/?probe=25518083e9) | Feb 14, 2022 |
| Toshiba       | Satellite Pro L650          | [8cc610d205](https://linux-hardware.org/?probe=8cc610d205) | Feb 14, 2022 |
| Samsung       | NC210/NC110                 | [bf2672168d](https://linux-hardware.org/?probe=bf2672168d) | Feb 14, 2022 |
| Google        | Ultima                      | [02007b3643](https://linux-hardware.org/?probe=02007b3643) | Feb 13, 2022 |
| Acer          | TravelMate 6592             | [a12fc5be70](https://linux-hardware.org/?probe=a12fc5be70) | Feb 13, 2022 |
| Acer          | Aspire ES1-523              | [594cf4fa2f](https://linux-hardware.org/?probe=594cf4fa2f) | Feb 13, 2022 |
| Samsung       | NC210/NC110                 | [bcbb1884aa](https://linux-hardware.org/?probe=bcbb1884aa) | Feb 13, 2022 |
| Fujitsu       | CELSIUS H700                | [80008ebc38](https://linux-hardware.org/?probe=80008ebc38) | Feb 13, 2022 |
| Lenovo        | Legion 5 17ACH6 82K0        | [c756082899](https://linux-hardware.org/?probe=c756082899) | Feb 13, 2022 |
| HP            | G72                         | [b27d05f546](https://linux-hardware.org/?probe=b27d05f546) | Feb 12, 2022 |
| ASUSTek       | X550EP                      | [4a316b0aef](https://linux-hardware.org/?probe=4a316b0aef) | Feb 12, 2022 |
| ASUSTek       | X550CA                      | [4fc3af48e2](https://linux-hardware.org/?probe=4fc3af48e2) | Feb 12, 2022 |
| Google        | Kefka                       | [de6a197771](https://linux-hardware.org/?probe=de6a197771) | Feb 12, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [889a7efca0](https://linux-hardware.org/?probe=889a7efca0) | Feb 12, 2022 |
| ASUSTek       | A8JR                        | [3fbe9d478e](https://linux-hardware.org/?probe=3fbe9d478e) | Feb 12, 2022 |
| Lenovo        | ThinkPad Edge 0301FAG       | [1f9694d47d](https://linux-hardware.org/?probe=1f9694d47d) | Feb 12, 2022 |
| Dell          | Latitude D630               | [b73fc865fd](https://linux-hardware.org/?probe=b73fc865fd) | Feb 11, 2022 |
| Lenovo        | ThinkPad X240 20AM007QMS    | [d1a972806c](https://linux-hardware.org/?probe=d1a972806c) | Feb 11, 2022 |
| Primux Tec... | Ioxbook1402MC               | [0127dcc4e7](https://linux-hardware.org/?probe=0127dcc4e7) | Feb 11, 2022 |
| Lenovo        | G510 20238                  | [0ab9f95484](https://linux-hardware.org/?probe=0ab9f95484) | Feb 11, 2022 |
| Lenovo        | IdeaPad Y580                | [37a6572cb9](https://linux-hardware.org/?probe=37a6572cb9) | Feb 10, 2022 |
| Lenovo        | G50-70 20351                | [0d63a077fb](https://linux-hardware.org/?probe=0d63a077fb) | Feb 10, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [37506ec01c](https://linux-hardware.org/?probe=37506ec01c) | Feb 10, 2022 |
| Lenovo        | ThinkPad T480 20L50007PB    | [a06da55ebe](https://linux-hardware.org/?probe=a06da55ebe) | Feb 10, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [a3c5f00a2a](https://linux-hardware.org/?probe=a3c5f00a2a) | Feb 10, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [e53fb31614](https://linux-hardware.org/?probe=e53fb31614) | Feb 10, 2022 |
| Acer          | TravelMate X349-G2-M        | [99296fdd45](https://linux-hardware.org/?probe=99296fdd45) | Feb 10, 2022 |
| Clevo         | W240BU                      | [dd745527d7](https://linux-hardware.org/?probe=dd745527d7) | Feb 10, 2022 |
| Dell          | Inspiron 5515               | [a3e3482bf8](https://linux-hardware.org/?probe=a3e3482bf8) | Feb 10, 2022 |
| Lenovo        | ThinkPad X240 20AMS36W0X    | [2bf21d3499](https://linux-hardware.org/?probe=2bf21d3499) | Feb 10, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [23251c9e05](https://linux-hardware.org/?probe=23251c9e05) | Feb 10, 2022 |
| ASUSTek       | F3E                         | [1715199afd](https://linux-hardware.org/?probe=1715199afd) | Feb 09, 2022 |
| HP            | Pavilion dv6500             | [c1302b751d](https://linux-hardware.org/?probe=c1302b751d) | Feb 09, 2022 |
| HP            | ProBook 470 G2              | [a2a21ce34a](https://linux-hardware.org/?probe=a2a21ce34a) | Feb 09, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | [545af13c86](https://linux-hardware.org/?probe=545af13c86) | Feb 09, 2022 |
| Acer          | Aspire A715-74G             | [f997cd1dda](https://linux-hardware.org/?probe=f997cd1dda) | Feb 09, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [c08078130a](https://linux-hardware.org/?probe=c08078130a) | Feb 09, 2022 |
| ASUSTek       | K52Je                       | [e1010983cf](https://linux-hardware.org/?probe=e1010983cf) | Feb 09, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [d7b75e7be7](https://linux-hardware.org/?probe=d7b75e7be7) | Feb 08, 2022 |
| Lenovo        | B570e HuronRiver Platfor... | [bedf7835b0](https://linux-hardware.org/?probe=bedf7835b0) | Feb 08, 2022 |
| Lenovo        | G50-30 80G0                 | [18bd9bbbe0](https://linux-hardware.org/?probe=18bd9bbbe0) | Feb 08, 2022 |
| Dell          | XPS 15 9500                 | [f9d02c76f2](https://linux-hardware.org/?probe=f9d02c76f2) | Feb 08, 2022 |
| HP            | 250 G6 Notebook PC          | [fe1ccafd2b](https://linux-hardware.org/?probe=fe1ccafd2b) | Feb 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [ad879b1190](https://linux-hardware.org/?probe=ad879b1190) | Feb 08, 2022 |
| Lenovo        | G50-30 80G0                 | [6d631d4a4d](https://linux-hardware.org/?probe=6d631d4a4d) | Feb 08, 2022 |
| Lenovo        | ThinkPad T460s 20FAS5WX0... | [6fa180d5fa](https://linux-hardware.org/?probe=6fa180d5fa) | Feb 06, 2022 |
| HUAWEI        | HVY-WXX9                    | [9ed4001ca5](https://linux-hardware.org/?probe=9ed4001ca5) | Feb 06, 2022 |
| ASUSTek       | X55C                        | [ff55557114](https://linux-hardware.org/?probe=ff55557114) | Feb 06, 2022 |
| Dell          | G3 3779                     | [c9185bcf1f](https://linux-hardware.org/?probe=c9185bcf1f) | Feb 06, 2022 |
| Primux Tec... | Ioxbook1402MC               | [2ea417a1d7](https://linux-hardware.org/?probe=2ea417a1d7) | Feb 06, 2022 |
| Dell          | Inspiron 3451               | [f00c7a8507](https://linux-hardware.org/?probe=f00c7a8507) | Feb 06, 2022 |
| Dell          | Inspiron 3451               | [9c87bc4fca](https://linux-hardware.org/?probe=9c87bc4fca) | Feb 05, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [7c19747b0a](https://linux-hardware.org/?probe=7c19747b0a) | Feb 05, 2022 |
| Acer          | Extensa 5620                | [d5048cae9a](https://linux-hardware.org/?probe=d5048cae9a) | Feb 05, 2022 |
| HUAWEI        | HVY-WXX9                    | [7b1b45a8ed](https://linux-hardware.org/?probe=7b1b45a8ed) | Feb 05, 2022 |
| Dell          | Inspiron 5502               | [acacc1d256](https://linux-hardware.org/?probe=acacc1d256) | Feb 05, 2022 |
| Acer          | Aspire SW7-272              | [920f676336](https://linux-hardware.org/?probe=920f676336) | Feb 04, 2022 |
| ASUSTek       | K56CB                       | [f8fa3c70d0](https://linux-hardware.org/?probe=f8fa3c70d0) | Feb 04, 2022 |
| HUAWEI        | KLVL-WXX9                   | [ca238c69a5](https://linux-hardware.org/?probe=ca238c69a5) | Feb 04, 2022 |
| ASUSTek       | K55VJ                       | [f0421851fa](https://linux-hardware.org/?probe=f0421851fa) | Feb 03, 2022 |
| Lenovo        | ThinkPad Edge 0301FAG       | [44efd2d456](https://linux-hardware.org/?probe=44efd2d456) | Feb 03, 2022 |
| Lenovo        | ThinkPad Edge 0301FAG       | [2e33681926](https://linux-hardware.org/?probe=2e33681926) | Feb 03, 2022 |
| Dell          | Latitude 5480               | [c96d03d27f](https://linux-hardware.org/?probe=c96d03d27f) | Feb 03, 2022 |
| Notebook      | NL5xRU                      | [448fbbbd68](https://linux-hardware.org/?probe=448fbbbd68) | Feb 03, 2022 |
| Dell          | Latitude E6230              | [05d9080c0c](https://linux-hardware.org/?probe=05d9080c0c) | Feb 03, 2022 |
| Samsung       | NC210/NC110                 | [cf9bd50b93](https://linux-hardware.org/?probe=cf9bd50b93) | Feb 02, 2022 |
| Dell          | Latitude D630               | [f7a31d8e3e](https://linux-hardware.org/?probe=f7a31d8e3e) | Feb 02, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [5a4297dbed](https://linux-hardware.org/?probe=5a4297dbed) | Feb 01, 2022 |
| Dell          | Inspiron 5502               | [b4ed3782aa](https://linux-hardware.org/?probe=b4ed3782aa) | Feb 01, 2022 |
| Dell          | Vostro 3500                 | [c9cae610a6](https://linux-hardware.org/?probe=c9cae610a6) | Feb 01, 2022 |
| ASUSTek       | X71Vn                       | [d780a75ddd](https://linux-hardware.org/?probe=d780a75ddd) | Feb 01, 2022 |
| HP            | Grunt                       | [315d957271](https://linux-hardware.org/?probe=315d957271) | Feb 01, 2022 |
| HP            | Grunt                       | [e95882e549](https://linux-hardware.org/?probe=e95882e549) | Jan 31, 2022 |
| Lenovo        | Yoga 700-14ISK 80QD         | [de0d67e8c4](https://linux-hardware.org/?probe=de0d67e8c4) | Jan 31, 2022 |
| Dell          | Inspiron 7559               | [0f6106ee3e](https://linux-hardware.org/?probe=0f6106ee3e) | Jan 31, 2022 |
| Dell          | Precision M4800             | [cb4d92b5ae](https://linux-hardware.org/?probe=cb4d92b5ae) | Jan 31, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [1f2faf4487](https://linux-hardware.org/?probe=1f2faf4487) | Jan 31, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [03cb9013e4](https://linux-hardware.org/?probe=03cb9013e4) | Jan 31, 2022 |
| Samsung       | R580                        | [b796f42cc3](https://linux-hardware.org/?probe=b796f42cc3) | Jan 31, 2022 |
| HP            | ProBook 6470b               | [86ba660bb5](https://linux-hardware.org/?probe=86ba660bb5) | Jan 30, 2022 |
| HP            | EliteBook 8540p             | [d4ac78c832](https://linux-hardware.org/?probe=d4ac78c832) | Jan 29, 2022 |
| Dell          | XPS 15 9500                 | [b5db02e326](https://linux-hardware.org/?probe=b5db02e326) | Jan 29, 2022 |
| ASUSTek       | Strix GL703GM_GL703GM       | [15b0649632](https://linux-hardware.org/?probe=15b0649632) | Jan 29, 2022 |
| HP            | Laptop 15-db0xxx            | [5dbc003da9](https://linux-hardware.org/?probe=5dbc003da9) | Jan 28, 2022 |
| Packard Be... | EasyNote TJ65               | [9770dbdaeb](https://linux-hardware.org/?probe=9770dbdaeb) | Jan 28, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [e72c21afc6](https://linux-hardware.org/?probe=e72c21afc6) | Jan 27, 2022 |
| ASUSTek       | X510UNR                     | [64f7ad2ba1](https://linux-hardware.org/?probe=64f7ad2ba1) | Jan 27, 2022 |
| Dell          | Latitude 5511               | [d2eb83845f](https://linux-hardware.org/?probe=d2eb83845f) | Jan 27, 2022 |
| Lenovo        | G550 20023                  | [8035475525](https://linux-hardware.org/?probe=8035475525) | Jan 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [dc0ea304b7](https://linux-hardware.org/?probe=dc0ea304b7) | Jan 26, 2022 |
| Primux Tec... | Ioxbook1402MC               | [75b13d530c](https://linux-hardware.org/?probe=75b13d530c) | Jan 26, 2022 |
| HP            | EliteBook 2570p             | [d79298d8f4](https://linux-hardware.org/?probe=d79298d8f4) | Jan 26, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [04c45929e9](https://linux-hardware.org/?probe=04c45929e9) | Jan 25, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [f38245d80d](https://linux-hardware.org/?probe=f38245d80d) | Jan 25, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [fd43369ab4](https://linux-hardware.org/?probe=fd43369ab4) | Jan 25, 2022 |
| Dell          | Latitude E5410              | [074ed63eb9](https://linux-hardware.org/?probe=074ed63eb9) | Jan 25, 2022 |
| HUAWEI        | KLVL-WXX9                   | [5846d2031f](https://linux-hardware.org/?probe=5846d2031f) | Jan 25, 2022 |
| Dell          | Inspiron 15-3567            | [e12cbc32ea](https://linux-hardware.org/?probe=e12cbc32ea) | Jan 24, 2022 |
| Dell          | Inspiron 3451               | [a212372095](https://linux-hardware.org/?probe=a212372095) | Jan 24, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [b0ac82e1b4](https://linux-hardware.org/?probe=b0ac82e1b4) | Jan 24, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [3f8cbf73ae](https://linux-hardware.org/?probe=3f8cbf73ae) | Jan 24, 2022 |
| Acer          | Aspire V3-571G              | [77e433fe30](https://linux-hardware.org/?probe=77e433fe30) | Jan 23, 2022 |
| Dell          | Latitude E6420              | [1cf74dd114](https://linux-hardware.org/?probe=1cf74dd114) | Jan 23, 2022 |
| HP            | G60                         | [acd0e22a1a](https://linux-hardware.org/?probe=acd0e22a1a) | Jan 23, 2022 |
| Dell          | Latitude 5310               | [424fadc888](https://linux-hardware.org/?probe=424fadc888) | Jan 23, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [427ce82d40](https://linux-hardware.org/?probe=427ce82d40) | Jan 22, 2022 |
| Lenovo        | Unknown                     | [b78e96aff8](https://linux-hardware.org/?probe=b78e96aff8) | Jan 22, 2022 |
| Toshiba       | Satellite L670D             | [51fb2a4a10](https://linux-hardware.org/?probe=51fb2a4a10) | Jan 22, 2022 |
| Dell          | Inspiron 3451               | [cf464f5bce](https://linux-hardware.org/?probe=cf464f5bce) | Jan 22, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [2de98fb4d8](https://linux-hardware.org/?probe=2de98fb4d8) | Jan 22, 2022 |
| Google        | Candy                       | [f050105bbf](https://linux-hardware.org/?probe=f050105bbf) | Jan 21, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [b122aab045](https://linux-hardware.org/?probe=b122aab045) | Jan 21, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [178c594c6a](https://linux-hardware.org/?probe=178c594c6a) | Jan 20, 2022 |
| Dell          | Inspiron 3451               | [e47bd66b78](https://linux-hardware.org/?probe=e47bd66b78) | Jan 20, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [cf4e41b312](https://linux-hardware.org/?probe=cf4e41b312) | Jan 19, 2022 |
| Dell          | Latitude 5410               | [a3ae63a084](https://linux-hardware.org/?probe=a3ae63a084) | Jan 19, 2022 |
| Acer          | Swift SF314-42              | [a2e70fe7b1](https://linux-hardware.org/?probe=a2e70fe7b1) | Jan 19, 2022 |
| Lenovo        | IdeaPad Y580                | [2a4100e03c](https://linux-hardware.org/?probe=2a4100e03c) | Jan 18, 2022 |
| ASUSTek       | K45VD                       | [206ce8c174](https://linux-hardware.org/?probe=206ce8c174) | Jan 18, 2022 |
| ASUSTek       | K45VD                       | [6eafcfd89d](https://linux-hardware.org/?probe=6eafcfd89d) | Jan 18, 2022 |
| Acer          | Aspire S3-391               | [a83705b242](https://linux-hardware.org/?probe=a83705b242) | Jan 16, 2022 |
| ASUSTek       | X540LA                      | [79a6d45df0](https://linux-hardware.org/?probe=79a6d45df0) | Jan 15, 2022 |
| Dell          | Inspiron 3451               | [6da7af33f8](https://linux-hardware.org/?probe=6da7af33f8) | Jan 15, 2022 |
| Lenovo        | IdeaPad Z585                | [a72e69708b](https://linux-hardware.org/?probe=a72e69708b) | Jan 14, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [b4ee61dfc0](https://linux-hardware.org/?probe=b4ee61dfc0) | Jan 14, 2022 |
| Dell          | XPS 15 9500                 | [9a887349f4](https://linux-hardware.org/?probe=9a887349f4) | Jan 14, 2022 |
| Dell          | Latitude 5480               | [d95c781c2e](https://linux-hardware.org/?probe=d95c781c2e) | Jan 14, 2022 |
| Dell          | Latitude 5480               | [d58108295c](https://linux-hardware.org/?probe=d58108295c) | Jan 14, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEP... | [7dbb72c69c](https://linux-hardware.org/?probe=7dbb72c69c) | Jan 14, 2022 |
| Lenovo        | ThinkPad T440p 20AWS2CH0... | [7f440733c2](https://linux-hardware.org/?probe=7f440733c2) | Jan 13, 2022 |
| Acer          | Aspire 5750G                | [dd5e1ff4bd](https://linux-hardware.org/?probe=dd5e1ff4bd) | Jan 13, 2022 |
| HP            | Notebook                    | [847afd8ac5](https://linux-hardware.org/?probe=847afd8ac5) | Jan 12, 2022 |
| Toshiba       | Satellite A300              | [59338f2a1a](https://linux-hardware.org/?probe=59338f2a1a) | Jan 12, 2022 |
| Lenovo        | ThinkPad T480 20L50007PB    | [da62520ddb](https://linux-hardware.org/?probe=da62520ddb) | Jan 12, 2022 |
| Lenovo        | ThinkPad T480 20L50007PB    | [818285955f](https://linux-hardware.org/?probe=818285955f) | Jan 12, 2022 |
| Dell          | Inspiron 7520               | [e433dbb39d](https://linux-hardware.org/?probe=e433dbb39d) | Jan 12, 2022 |
| Dell          | Inspiron 3593               | [9c5f9bb3c6](https://linux-hardware.org/?probe=9c5f9bb3c6) | Jan 12, 2022 |
| Acer          | Swift SF314-59              | [175b161d3f](https://linux-hardware.org/?probe=175b161d3f) | Jan 11, 2022 |
| Dell          | Latitude 5410               | [20fad714af](https://linux-hardware.org/?probe=20fad714af) | Jan 11, 2022 |
| Dell          | Inspiron 13 5310            | [fd57c1981b](https://linux-hardware.org/?probe=fd57c1981b) | Jan 11, 2022 |
| Dell          | Latitude 7480               | [acbc136d24](https://linux-hardware.org/?probe=acbc136d24) | Jan 10, 2022 |
| Razer         | Blade 15 Base Model (Mid... | [af7d37f35c](https://linux-hardware.org/?probe=af7d37f35c) | Jan 10, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [7225108b91](https://linux-hardware.org/?probe=7225108b91) | Jan 10, 2022 |
| Dell          | Inspiron 3451               | [053236f8c0](https://linux-hardware.org/?probe=053236f8c0) | Jan 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [0ca0e6ddd6](https://linux-hardware.org/?probe=0ca0e6ddd6) | Jan 08, 2022 |
| Acer          | Aspire 5750G                | [088c5ba19e](https://linux-hardware.org/?probe=088c5ba19e) | Jan 08, 2022 |
| Acer          | Aspire 5750G                | [b4a8ca7f90](https://linux-hardware.org/?probe=b4a8ca7f90) | Jan 08, 2022 |
| Timi          | RedmiBook Pro 15S           | [b09125b81f](https://linux-hardware.org/?probe=b09125b81f) | Jan 08, 2022 |
| ASUSTek       | G56JR                       | [2e4539087b](https://linux-hardware.org/?probe=2e4539087b) | Jan 08, 2022 |
| Timi          | RedmiBook Pro 15S           | [034079628f](https://linux-hardware.org/?probe=034079628f) | Jan 07, 2022 |
| Lenovo        | Legion 5 17ACH6 82K0        | [a9bef5b272](https://linux-hardware.org/?probe=a9bef5b272) | Jan 07, 2022 |
| Lenovo        | Legion 5 17ACH6 82K0        | [346c27c2c3](https://linux-hardware.org/?probe=346c27c2c3) | Jan 07, 2022 |
| Lenovo        | Legion 5 17ACH6 82K0        | [960db118f1](https://linux-hardware.org/?probe=960db118f1) | Jan 07, 2022 |
| Dell          | Latitude 5490               | [f4183e203c](https://linux-hardware.org/?probe=f4183e203c) | Jan 07, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [4815545f1c](https://linux-hardware.org/?probe=4815545f1c) | Jan 07, 2022 |
| Dell          | Latitude 5310               | [29e73cb4ff](https://linux-hardware.org/?probe=29e73cb4ff) | Jan 07, 2022 |
| Primux Tec... | Ioxbook1402MC               | [72a412217c](https://linux-hardware.org/?probe=72a412217c) | Jan 07, 2022 |
| Dell          | Inspiron 3451               | [b34e6337ae](https://linux-hardware.org/?probe=b34e6337ae) | Jan 05, 2022 |
| HUAWEI        | BOHB-WAX9                   | [89ff5af60e](https://linux-hardware.org/?probe=89ff5af60e) | Jan 05, 2022 |
| HUAWEI        | MACHC-WAX9                  | [b0df1464a1](https://linux-hardware.org/?probe=b0df1464a1) | Jan 05, 2022 |
| Dell          | Inspiron 5520               | [5ce6cac5cb](https://linux-hardware.org/?probe=5ce6cac5cb) | Jan 04, 2022 |
| HP            | 635                         | [aafd01b4db](https://linux-hardware.org/?probe=aafd01b4db) | Jan 04, 2022 |
| Lenovo        | ThinkPad E14 20RA001DPB     | [cb0f7db023](https://linux-hardware.org/?probe=cb0f7db023) | Jan 04, 2022 |
| Dell          | Precision 5530              | [b385c0a16e](https://linux-hardware.org/?probe=b385c0a16e) | Jan 04, 2022 |
| HP            | ProBook 440 G7              | [e5806fd9d0](https://linux-hardware.org/?probe=e5806fd9d0) | Jan 04, 2022 |
| HP            | Pavilion m6                 | [be191c0d05](https://linux-hardware.org/?probe=be191c0d05) | Jan 04, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [39c4fe86a8](https://linux-hardware.org/?probe=39c4fe86a8) | Jan 04, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | [95f33224e9](https://linux-hardware.org/?probe=95f33224e9) | Jan 04, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [0c37fe7bda](https://linux-hardware.org/?probe=0c37fe7bda) | Jan 03, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [d8b53c12c7](https://linux-hardware.org/?probe=d8b53c12c7) | Jan 03, 2022 |
| Acer          | Aspire E5-571G              | [75edf90312](https://linux-hardware.org/?probe=75edf90312) | Jan 03, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [22a9d41db0](https://linux-hardware.org/?probe=22a9d41db0) | Jan 02, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [6100abe0e1](https://linux-hardware.org/?probe=6100abe0e1) | Jan 02, 2022 |
| Dell          | XPS M1530                   | [edfbd4eb1c](https://linux-hardware.org/?probe=edfbd4eb1c) | Jan 02, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [cbceb1c15b](https://linux-hardware.org/?probe=cbceb1c15b) | Jan 01, 2022 |
| Dell          | Latitude 5591               | [98608743b7](https://linux-hardware.org/?probe=98608743b7) | Jan 01, 2022 |
| Dell          | Latitude 5591               | [21d6b609b1](https://linux-hardware.org/?probe=21d6b609b1) | Jan 01, 2022 |
| Acer          | Swift SF314-59              | [820456adab](https://linux-hardware.org/?probe=820456adab) | Dec 31, 2021 |
| HP            | 550                         | [e6c48cf2f4](https://linux-hardware.org/?probe=e6c48cf2f4) | Dec 31, 2021 |
| Lenovo        | ThinkPad T460 20FMS1R01K    | [c6dbec8e70](https://linux-hardware.org/?probe=c6dbec8e70) | Dec 31, 2021 |
| Toshiba       | Satellite L300              | [fc547136cc](https://linux-hardware.org/?probe=fc547136cc) | Dec 31, 2021 |
| HP            | ZBook 15 G4                 | [45c3b9ac54](https://linux-hardware.org/?probe=45c3b9ac54) | Dec 30, 2021 |
| HP            | ZBook 15 G4                 | [18501c3084](https://linux-hardware.org/?probe=18501c3084) | Dec 30, 2021 |
| Hyperbook     | Z15 Zen                     | [6fe0e1a6d0](https://linux-hardware.org/?probe=6fe0e1a6d0) | Dec 30, 2021 |
| Dell          | Inspiron 7559               | [6f1c16d0ed](https://linux-hardware.org/?probe=6f1c16d0ed) | Dec 30, 2021 |
| Dell          | Inspiron 7559               | [8d6558d025](https://linux-hardware.org/?probe=8d6558d025) | Dec 30, 2021 |
| Lenovo        | IdeaPad P500 20210          | [395d599207](https://linux-hardware.org/?probe=395d599207) | Dec 29, 2021 |
| Acer          | Aspire 5738                 | [86269a3e79](https://linux-hardware.org/?probe=86269a3e79) | Dec 29, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [5ce89f7099](https://linux-hardware.org/?probe=5ce89f7099) | Dec 29, 2021 |
| HP            | EliteBook 2570p             | [d4f5b3abd7](https://linux-hardware.org/?probe=d4f5b3abd7) | Dec 29, 2021 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | [a4a4581b6d](https://linux-hardware.org/?probe=a4a4581b6d) | Dec 28, 2021 |
| Lenovo        | ThinkPad E480 20KN001QPB    | [0615d7a112](https://linux-hardware.org/?probe=0615d7a112) | Dec 28, 2021 |
| Lenovo        | G50-30 80G0                 | [f74d67441b](https://linux-hardware.org/?probe=f74d67441b) | Dec 27, 2021 |
| HP            | EliteBook 2570p             | [4fe6dfc220](https://linux-hardware.org/?probe=4fe6dfc220) | Dec 27, 2021 |
| Dell          | Latitude E6440              | [11c17aeeaa](https://linux-hardware.org/?probe=11c17aeeaa) | Dec 27, 2021 |
| Lenovo        | ThinkPad T460s 20FAS4A20... | [958fdabaef](https://linux-hardware.org/?probe=958fdabaef) | Dec 27, 2021 |
| HP            | ZBook 14                    | [456906dfff](https://linux-hardware.org/?probe=456906dfff) | Dec 27, 2021 |
| HP            | Pavilion Notebook           | [20933f8817](https://linux-hardware.org/?probe=20933f8817) | Dec 26, 2021 |
| Dell          | Inspiron 3451               | [d0340265ee](https://linux-hardware.org/?probe=d0340265ee) | Dec 26, 2021 |
| Samsung       | R780/R778                   | [5bfacc89be](https://linux-hardware.org/?probe=5bfacc89be) | Dec 26, 2021 |
| Dell          | Latitude E4300              | [33f7188443](https://linux-hardware.org/?probe=33f7188443) | Dec 25, 2021 |
| Acer          | Aspire 5920G                | [f06229224a](https://linux-hardware.org/?probe=f06229224a) | Dec 25, 2021 |
| HP            | Pavilion g6                 | [1c7a0d3739](https://linux-hardware.org/?probe=1c7a0d3739) | Dec 25, 2021 |
| Dell          | Inspiron 3451               | [73576a9684](https://linux-hardware.org/?probe=73576a9684) | Dec 24, 2021 |
| Dell          | Latitude E6440              | [03c4e654a0](https://linux-hardware.org/?probe=03c4e654a0) | Dec 24, 2021 |
| Dell          | Latitude E6440              | [8861d2911f](https://linux-hardware.org/?probe=8861d2911f) | Dec 24, 2021 |
| Acer          | TravelMate 5760             | [71526c7767](https://linux-hardware.org/?probe=71526c7767) | Dec 23, 2021 |
| Lenovo        | V14-ADA 82C6                | [c8371f27fd](https://linux-hardware.org/?probe=c8371f27fd) | Dec 23, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [09799e1378](https://linux-hardware.org/?probe=09799e1378) | Dec 23, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [3b41746dad](https://linux-hardware.org/?probe=3b41746dad) | Dec 23, 2021 |
| HP            | Laptop 15s-eq1xxx           | [bdb88d3ef1](https://linux-hardware.org/?probe=bdb88d3ef1) | Dec 22, 2021 |
| HP            | ProBook 6550b               | [14f6337b9a](https://linux-hardware.org/?probe=14f6337b9a) | Dec 22, 2021 |
| HP            | Victus by Laptop 16-e0xx... | [254b5ea986](https://linux-hardware.org/?probe=254b5ea986) | Dec 22, 2021 |
| Dell          | Latitude 5490               | [11ae9aa9e4](https://linux-hardware.org/?probe=11ae9aa9e4) | Dec 21, 2021 |
| Dell          | Inspiron 3542               | [be6550186c](https://linux-hardware.org/?probe=be6550186c) | Dec 21, 2021 |
| Acer          | Aspire E5-571G              | [201e93fd24](https://linux-hardware.org/?probe=201e93fd24) | Dec 20, 2021 |
| Dell          | G5 5590                     | [d548c52867](https://linux-hardware.org/?probe=d548c52867) | Dec 20, 2021 |
| Sony          | VPCF23M1E                   | [a7e83ee775](https://linux-hardware.org/?probe=a7e83ee775) | Dec 20, 2021 |
| Sony          | VPCF23M1E                   | [f10ab27170](https://linux-hardware.org/?probe=f10ab27170) | Dec 20, 2021 |
| HP            | Laptop 15-db0xxx            | [450425f52d](https://linux-hardware.org/?probe=450425f52d) | Dec 20, 2021 |
| HP            | Laptop 15-db0xxx            | [95261c40a2](https://linux-hardware.org/?probe=95261c40a2) | Dec 20, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [18fbcba790](https://linux-hardware.org/?probe=18fbcba790) | Dec 20, 2021 |
| eMachines     | Unknown                     | [6b9767faba](https://linux-hardware.org/?probe=6b9767faba) | Dec 20, 2021 |
| Dell          | Precision M6500             | [931f365c60](https://linux-hardware.org/?probe=931f365c60) | Dec 20, 2021 |
| HP            | Laptop 15s-eq2xxx           | [899ca3371c](https://linux-hardware.org/?probe=899ca3371c) | Dec 20, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [8e7b51ffdd](https://linux-hardware.org/?probe=8e7b51ffdd) | Dec 19, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [5e3eff3ad0](https://linux-hardware.org/?probe=5e3eff3ad0) | Dec 19, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [90575747f7](https://linux-hardware.org/?probe=90575747f7) | Dec 18, 2021 |
| ASUSTek       | X551CAP                     | [cb7b24735e](https://linux-hardware.org/?probe=cb7b24735e) | Dec 18, 2021 |
| Dell          | Inspiron 5515               | [2e61608393](https://linux-hardware.org/?probe=2e61608393) | Dec 18, 2021 |
| Dell          | XPS 15 9500                 | [7bb94e89f6](https://linux-hardware.org/?probe=7bb94e89f6) | Dec 18, 2021 |
| Dell          | Inspiron 3451               | [bd37d8fdf8](https://linux-hardware.org/?probe=bd37d8fdf8) | Dec 18, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [5d09272eb0](https://linux-hardware.org/?probe=5d09272eb0) | Dec 17, 2021 |
| Schenker      | XMG PRO (Late 2021)         | [f78514a539](https://linux-hardware.org/?probe=f78514a539) | Dec 17, 2021 |
| HUAWEI        | KLVL-WXX9                   | [99473bac5d](https://linux-hardware.org/?probe=99473bac5d) | Dec 17, 2021 |
| Lenovo        | V14-ADA 82C6                | [a45f76da28](https://linux-hardware.org/?probe=a45f76da28) | Dec 17, 2021 |
| HP            | Laptop 15-db0xxx            | [52f6aa4a91](https://linux-hardware.org/?probe=52f6aa4a91) | Dec 17, 2021 |
| Lenovo        | Yoga S740-14IIL 81RS        | [6deb57beb2](https://linux-hardware.org/?probe=6deb57beb2) | Dec 17, 2021 |
| ASUSTek       | X550CC                      | [c7147f0bf8](https://linux-hardware.org/?probe=c7147f0bf8) | Dec 16, 2021 |
| Dell          | Latitude E6440              | [5e572f557c](https://linux-hardware.org/?probe=5e572f557c) | Dec 16, 2021 |
| Dell          | Latitude E6440              | [ac94463e37](https://linux-hardware.org/?probe=ac94463e37) | Dec 16, 2021 |
| HP            | Laptop 15s-eq2xxx           | [7d95335599](https://linux-hardware.org/?probe=7d95335599) | Dec 16, 2021 |
| ASUSTek       | X550CC                      | [f8a99e7645](https://linux-hardware.org/?probe=f8a99e7645) | Dec 16, 2021 |
| HP            | Laptop 15s-eq2xxx           | [81c5e26bcf](https://linux-hardware.org/?probe=81c5e26bcf) | Dec 16, 2021 |
| Dell          | Inspiron 5520               | [1e451e93a0](https://linux-hardware.org/?probe=1e451e93a0) | Dec 15, 2021 |
| MSI           | GV72 8RE                    | [6e135ecf11](https://linux-hardware.org/?probe=6e135ecf11) | Dec 15, 2021 |
| Acer          | Aspire E1-772               | [572a123789](https://linux-hardware.org/?probe=572a123789) | Dec 14, 2021 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [515080ae76](https://linux-hardware.org/?probe=515080ae76) | Dec 13, 2021 |
| Dell          | G5 5590                     | [d68d926208](https://linux-hardware.org/?probe=d68d926208) | Dec 13, 2021 |
| Dell          | G5 5590                     | [88f9dfa75d](https://linux-hardware.org/?probe=88f9dfa75d) | Dec 13, 2021 |
| Toshiba       | Satellite L40               | [207f5e1cfa](https://linux-hardware.org/?probe=207f5e1cfa) | Dec 12, 2021 |
| HP            | Compaq 6720s                | [b271663561](https://linux-hardware.org/?probe=b271663561) | Dec 12, 2021 |
| HP            | ENVY Laptop 14-eb0xxx       | [f3e7994b41](https://linux-hardware.org/?probe=f3e7994b41) | Dec 12, 2021 |
| HP            | ProBook 6470b               | [a950763fdb](https://linux-hardware.org/?probe=a950763fdb) | Dec 12, 2021 |
| Acer          | Aspire A517-52              | [a51b1f9eb7](https://linux-hardware.org/?probe=a51b1f9eb7) | Dec 11, 2021 |
| Acer          | Aspire A517-52              | [bbf5c7ea28](https://linux-hardware.org/?probe=bbf5c7ea28) | Dec 11, 2021 |
| Dell          | Inspiron 13 5310            | [7a721d2c05](https://linux-hardware.org/?probe=7a721d2c05) | Dec 10, 2021 |
| HP            | Compaq 6720s                | [2ef57026bc](https://linux-hardware.org/?probe=2ef57026bc) | Dec 10, 2021 |
| Dell          | Inspiron 13 5310            | [70a974c325](https://linux-hardware.org/?probe=70a974c325) | Dec 10, 2021 |
| HP            | 250 G4 Notebook PC          | [67b13e5bd6](https://linux-hardware.org/?probe=67b13e5bd6) | Dec 10, 2021 |
| Dell          | Latitude E6540              | [d88da2666e](https://linux-hardware.org/?probe=d88da2666e) | Dec 09, 2021 |
| Acer          | Aspire E5-571G              | [53fb790458](https://linux-hardware.org/?probe=53fb790458) | Dec 08, 2021 |
| Apple         | MacBookAir7,2               | [cd9c0a60f4](https://linux-hardware.org/?probe=cd9c0a60f4) | Dec 08, 2021 |
| Acer          | Aspire F5-573G              | [5ecda93d81](https://linux-hardware.org/?probe=5ecda93d81) | Dec 08, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [4173a9406a](https://linux-hardware.org/?probe=4173a9406a) | Dec 07, 2021 |
| HP            | Laptop 15-db1xxx            | [45c6fce683](https://linux-hardware.org/?probe=45c6fce683) | Dec 07, 2021 |
| HP            | Laptop 15-db1xxx            | [b630c2b983](https://linux-hardware.org/?probe=b630c2b983) | Dec 07, 2021 |
| HP            | Laptop 15                   | [da76eec83a](https://linux-hardware.org/?probe=da76eec83a) | Dec 07, 2021 |
| HP            | Laptop 15-db1xxx            | [0a6e6fb2e6](https://linux-hardware.org/?probe=0a6e6fb2e6) | Dec 07, 2021 |
| HP            | Laptop 15-db1xxx            | [f2a731f5bc](https://linux-hardware.org/?probe=f2a731f5bc) | Dec 07, 2021 |
| HP            | Laptop 15-db1xxx            | [438e75161a](https://linux-hardware.org/?probe=438e75161a) | Dec 07, 2021 |
| HP            | Laptop 15-db1xxx            | [8e20af97d9](https://linux-hardware.org/?probe=8e20af97d9) | Dec 07, 2021 |
| HP            | Laptop 15-db0xxx            | [2df4a34321](https://linux-hardware.org/?probe=2df4a34321) | Dec 07, 2021 |
| Acer          | Aspire 5741G                | [885dd449b6](https://linux-hardware.org/?probe=885dd449b6) | Dec 07, 2021 |
| Dell          | Latitude E6540              | [73d8738312](https://linux-hardware.org/?probe=73d8738312) | Dec 06, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [be3e1f65e6](https://linux-hardware.org/?probe=be3e1f65e6) | Dec 06, 2021 |
| RM            | NOTEBOOK 320                | [6998aef680](https://linux-hardware.org/?probe=6998aef680) | Dec 06, 2021 |
| Dell          | Latitude E6400              | [b8d03425c9](https://linux-hardware.org/?probe=b8d03425c9) | Dec 05, 2021 |
| Lenovo        | Legion Y540-15IRH 81SX      | [cddf64fd85](https://linux-hardware.org/?probe=cddf64fd85) | Dec 05, 2021 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [ba2a31df8f](https://linux-hardware.org/?probe=ba2a31df8f) | Dec 05, 2021 |
| HP            | Laptop 15s-eq2xxx           | [98d2c21ee0](https://linux-hardware.org/?probe=98d2c21ee0) | Dec 04, 2021 |
| MSI           | GL65 Leopard 9SCXR          | [53bdcf665a](https://linux-hardware.org/?probe=53bdcf665a) | Dec 03, 2021 |
| ASUSTek       | K53TK                       | [043ef58552](https://linux-hardware.org/?probe=043ef58552) | Dec 03, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [1adcfe3e5e](https://linux-hardware.org/?probe=1adcfe3e5e) | Dec 03, 2021 |
| HP            | Laptop 15-db0xxx            | [b7a0fe35eb](https://linux-hardware.org/?probe=b7a0fe35eb) | Dec 03, 2021 |
| Lenovo        | V14-ADA 82C6                | [7fd0e9e7cd](https://linux-hardware.org/?probe=7fd0e9e7cd) | Dec 03, 2021 |
| Dell          | Latitude E7440              | [c0bb49bb97](https://linux-hardware.org/?probe=c0bb49bb97) | Dec 02, 2021 |
| HP            | EliteBook 2570p             | [ae56da4786](https://linux-hardware.org/?probe=ae56da4786) | Dec 02, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [4459608572](https://linux-hardware.org/?probe=4459608572) | Dec 02, 2021 |
| mPTech        | ARC 11.6 128GB HD           | [cb2302b704](https://linux-hardware.org/?probe=cb2302b704) | Dec 02, 2021 |
| mPTech        | ARC 11.6 128GB HD           | [f580be444b](https://linux-hardware.org/?probe=f580be444b) | Dec 02, 2021 |
| mPTech        | ARC 11.6 128GB HD           | [e2fbd06e2a](https://linux-hardware.org/?probe=e2fbd06e2a) | Dec 02, 2021 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [562fd676d1](https://linux-hardware.org/?probe=562fd676d1) | Dec 01, 2021 |
| HP            | EliteBook 840 G6            | [b2fe2b3c55](https://linux-hardware.org/?probe=b2fe2b3c55) | Dec 01, 2021 |
| ASUSTek       | X501A                       | [eb126969cb](https://linux-hardware.org/?probe=eb126969cb) | Nov 29, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [12b910d10b](https://linux-hardware.org/?probe=12b910d10b) | Nov 29, 2021 |
| Lenovo        | V560                        | [83e5b46ba2](https://linux-hardware.org/?probe=83e5b46ba2) | Nov 28, 2021 |
| Toshiba       | Satellite L40               | [d031ddee30](https://linux-hardware.org/?probe=d031ddee30) | Nov 28, 2021 |
| HP            | Pavilion dv6                | [5300296119](https://linux-hardware.org/?probe=5300296119) | Nov 27, 2021 |
| Acer          | Ferrari One 200             | [57001d93d1](https://linux-hardware.org/?probe=57001d93d1) | Nov 27, 2021 |
| Lenovo        | V14-ADA 82C6                | [a0f72af8d9](https://linux-hardware.org/?probe=a0f72af8d9) | Nov 26, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [c207f61d91](https://linux-hardware.org/?probe=c207f61d91) | Nov 26, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [96c90ad6c9](https://linux-hardware.org/?probe=96c90ad6c9) | Nov 26, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [039dbf659a](https://linux-hardware.org/?probe=039dbf659a) | Nov 26, 2021 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [4305ff478f](https://linux-hardware.org/?probe=4305ff478f) | Nov 25, 2021 |
| HP            | EliteBook 8770w             | [9a2052fc8c](https://linux-hardware.org/?probe=9a2052fc8c) | Nov 25, 2021 |
| MSI           | Bravo 15 B5DD               | [fc7c1ff3c8](https://linux-hardware.org/?probe=fc7c1ff3c8) | Nov 24, 2021 |
| Dell          | Vostro 5515                 | [85d1947f69](https://linux-hardware.org/?probe=85d1947f69) | Nov 24, 2021 |
| Dell          | XPS 13 9360                 | [1feb70590c](https://linux-hardware.org/?probe=1feb70590c) | Nov 23, 2021 |
| Toshiba       | Satellite L40               | [43d9bb451a](https://linux-hardware.org/?probe=43d9bb451a) | Nov 23, 2021 |
| Sony          | VPCSA3N9E                   | [33a3597313](https://linux-hardware.org/?probe=33a3597313) | Nov 23, 2021 |
| Sony          | VPCSA3N9E                   | [c1bf05d67a](https://linux-hardware.org/?probe=c1bf05d67a) | Nov 23, 2021 |
| Lenovo        | ThinkPad T430 2349U2B       | [ff1910fdd1](https://linux-hardware.org/?probe=ff1910fdd1) | Nov 23, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [7e3d18d75e](https://linux-hardware.org/?probe=7e3d18d75e) | Nov 23, 2021 |
| Dell          | Latitude 5421               | [8eacead04b](https://linux-hardware.org/?probe=8eacead04b) | Nov 23, 2021 |
| ASUSTek       | TP300LJ                     | [f685935861](https://linux-hardware.org/?probe=f685935861) | Nov 22, 2021 |
| Alienware     | M17x                        | [4a2c0b1f38](https://linux-hardware.org/?probe=4a2c0b1f38) | Nov 22, 2021 |
| Alienware     | M17x                        | [13acf7a3f9](https://linux-hardware.org/?probe=13acf7a3f9) | Nov 22, 2021 |
| Dell          | G5 5590                     | [7704b7b3ea](https://linux-hardware.org/?probe=7704b7b3ea) | Nov 21, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6505        | [c99c5700f6](https://linux-hardware.org/?probe=c99c5700f6) | Nov 20, 2021 |
| HP            | Pavilion 15                 | [687ecf1c58](https://linux-hardware.org/?probe=687ecf1c58) | Nov 20, 2021 |
| Fujitsu       | LIFEBOOK E557               | [3012daea66](https://linux-hardware.org/?probe=3012daea66) | Nov 20, 2021 |
| HP            | ProBook 4530s               | [de11d1bb53](https://linux-hardware.org/?probe=de11d1bb53) | Nov 19, 2021 |
| Lenovo        | ThinkPad T520 4243ED3       | [973921bfad](https://linux-hardware.org/?probe=973921bfad) | Nov 19, 2021 |
| Lenovo        | ACLUAB                      | [902a5ebdf9](https://linux-hardware.org/?probe=902a5ebdf9) | Nov 19, 2021 |
| Lenovo        | G50-30 80G0                 | [1604bcdd0d](https://linux-hardware.org/?probe=1604bcdd0d) | Nov 19, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [2c4e68ac8d](https://linux-hardware.org/?probe=2c4e68ac8d) | Nov 18, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [bb94961cc9](https://linux-hardware.org/?probe=bb94961cc9) | Nov 18, 2021 |
| Toshiba       | Satellite P750              | [2b97e80bbb](https://linux-hardware.org/?probe=2b97e80bbb) | Nov 18, 2021 |
| Lenovo        | B590 20206                  | [c5d3f06c7e](https://linux-hardware.org/?probe=c5d3f06c7e) | Nov 18, 2021 |
| Lenovo        | ACLUAB                      | [e4959c53dd](https://linux-hardware.org/?probe=e4959c53dd) | Nov 18, 2021 |
| Lenovo        | Z50-70 20354                | [065c8c66d6](https://linux-hardware.org/?probe=065c8c66d6) | Nov 17, 2021 |
| Dell          | Inspiron 7720               | [c4c4707bb6](https://linux-hardware.org/?probe=c4c4707bb6) | Nov 17, 2021 |
| Dell          | Vostro 5568                 | [403ef45f63](https://linux-hardware.org/?probe=403ef45f63) | Nov 15, 2021 |
| Acer          | Aspire A517-52              | [b384c8f995](https://linux-hardware.org/?probe=b384c8f995) | Nov 15, 2021 |
| Acer          | Aspire A517-52              | [92fe187f42](https://linux-hardware.org/?probe=92fe187f42) | Nov 15, 2021 |
| HP            | Pavilion dv6                | [5120795ac2](https://linux-hardware.org/?probe=5120795ac2) | Nov 14, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [58edd5c8e6](https://linux-hardware.org/?probe=58edd5c8e6) | Nov 14, 2021 |
| HP            | EliteBook 2540p             | [f32282bac4](https://linux-hardware.org/?probe=f32282bac4) | Nov 14, 2021 |
| Dell          | Latitude 5511               | [dc7c10f4e2](https://linux-hardware.org/?probe=dc7c10f4e2) | Nov 13, 2021 |
| Dell          | Latitude 5511               | [b0ca679bc5](https://linux-hardware.org/?probe=b0ca679bc5) | Nov 13, 2021 |
| Lenovo        | IdeaPadFlex 14 20308        | [1734da4566](https://linux-hardware.org/?probe=1734da4566) | Nov 13, 2021 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [31e2521af4](https://linux-hardware.org/?probe=31e2521af4) | Nov 12, 2021 |
| Lenovo        | G710 20252                  | [752b6b8c82](https://linux-hardware.org/?probe=752b6b8c82) | Nov 11, 2021 |
| Dell          | Inspiron 5577               | [94a5f0e2cd](https://linux-hardware.org/?probe=94a5f0e2cd) | Nov 11, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6505        | [72dd15e9c5](https://linux-hardware.org/?probe=72dd15e9c5) | Nov 10, 2021 |
| Dell          | Latitude 5490               | [2401d254b6](https://linux-hardware.org/?probe=2401d254b6) | Nov 10, 2021 |
| HP            | ProBook 440 G7              | [de7daa7785](https://linux-hardware.org/?probe=de7daa7785) | Nov 09, 2021 |
| ASUSTek       | X550CC                      | [d45eb47123](https://linux-hardware.org/?probe=d45eb47123) | Nov 09, 2021 |
| Acer          | Aspire E5-575G              | [8d87b37dae](https://linux-hardware.org/?probe=8d87b37dae) | Nov 09, 2021 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | [aad3e601ad](https://linux-hardware.org/?probe=aad3e601ad) | Nov 09, 2021 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | [dd5b331a4c](https://linux-hardware.org/?probe=dd5b331a4c) | Nov 09, 2021 |
| Toshiba       | Satellite L40               | [14819265aa](https://linux-hardware.org/?probe=14819265aa) | Nov 09, 2021 |
| Dell          | Latitude E5470              | [affe63217a](https://linux-hardware.org/?probe=affe63217a) | Nov 07, 2021 |
| Lenovo        | Z50-70 20354                | [304acea090](https://linux-hardware.org/?probe=304acea090) | Nov 07, 2021 |
| Lenovo        | ThinkPad T430 2349KZ7       | [a0efe8f014](https://linux-hardware.org/?probe=a0efe8f014) | Nov 07, 2021 |
| Dell          | Latitude E7440              | [b2560457a5](https://linux-hardware.org/?probe=b2560457a5) | Nov 06, 2021 |
| Dell          | Latitude E6440              | [38e3c1e18a](https://linux-hardware.org/?probe=38e3c1e18a) | Nov 06, 2021 |
| MAXDATA       | ECO4000IW                   | [090bbdeb4a](https://linux-hardware.org/?probe=090bbdeb4a) | Nov 06, 2021 |
| MAXDATA       | ECO4000IW                   | [5a5fb011c7](https://linux-hardware.org/?probe=5a5fb011c7) | Nov 06, 2021 |

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
| Ubuntu 20.04                 | 329       | 13.87%  |
| OpenMandriva 4.2             | 182       | 7.67%   |
| Ubuntu 18.04                 | 165       | 6.96%   |
| OpenMandriva 4.3             | 79        | 3.33%   |
| Debian 11                    | 61        | 2.57%   |
| Ubuntu 22.04                 | 54        | 2.28%   |
| ROSA R10                     | 50        | 2.11%   |
| Linux Mint 20.1              | 42        | 1.77%   |
| Arch                         | 42        | 1.77%   |
| Linux Mint 20.3              | 40        | 1.69%   |
| ROSA R9                      | 39        | 1.64%   |
| KDE neon 20.04               | 38        | 1.6%    |
| Arch Rolling                 | 37        | 1.56%   |
| Linux Mint 20.2              | 33        | 1.39%   |
| Ubuntu 21.04                 | 32        | 1.35%   |
| Ubuntu 20.10                 | 32        | 1.35%   |
| ROSA R11.1                   | 31        | 1.31%   |
| Manjaro                      | 31        | 1.31%   |
| Linux Mint 19.3              | 31        | 1.31%   |
| ROSA R11                     | 29        | 1.22%   |
| Fedora 36                    | 28        | 1.18%   |
| Zorin 15                     | 27        | 1.14%   |
| Ubuntu 19.10                 | 27        | 1.14%   |
| Ubuntu 21.10                 | 26        | 1.1%    |
| Linux Mint 20                | 26        | 1.1%    |
| Xubuntu 20.04                | 25        | 1.05%   |
| ROSA R8                      | 25        | 1.05%   |
| Fedora 33                    | 25        | 1.05%   |
| Fedora 32                    | 24        | 1.01%   |
| Fedora 35                    | 23        | 0.97%   |
| Zorin 16                     | 22        | 0.93%   |
| Debian 10                    | 21        | 0.89%   |
| Fedora 34                    | 19        | 0.8%    |
| Pop!_OS 20.04                | 18        | 0.76%   |
| Kubuntu 20.04                | 18        | 0.76%   |
| ROSA R8.1                    | 17        | 0.72%   |
| Fedora 31                    | 17        | 0.72%   |
| Pop!_OS 20.10                | 16        | 0.67%   |
| openSUSE Tumbleweed-XXXXXXXX | 16        | 0.67%   |
| Ubuntu 19.04                 | 14        | 0.59%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 671       | 29.97%  |
| OpenMandriva  | 273       | 12.19%  |
| Linux Mint    | 183       | 8.17%   |
| ROSA          | 174       | 7.77%   |
| Fedora        | 141       | 6.3%    |
| Debian        | 99        | 4.42%   |
| Manjaro       | 96        | 4.29%   |
| Arch          | 77        | 3.44%   |
| Pop!_OS       | 60        | 2.68%   |
| Zorin         | 52        | 2.32%   |
| KDE neon      | 47        | 2.1%    |
| Xubuntu       | 41        | 1.83%   |
| Kubuntu       | 36        | 1.61%   |
| Kali          | 28        | 1.25%   |
| Endless       | 22        | 0.98%   |
| Lubuntu       | 21        | 0.94%   |
| openSUSE      | 18        | 0.8%    |
| Elementary    | 18        | 0.8%    |
| Gentoo        | 17        | 0.76%   |
| ArcoLinux     | 15        | 0.67%   |
| LMDE          | 13        | 0.58%   |
| Clear Linux   | 11        | 0.49%   |
| EndeavourOS   | 10        | 0.45%   |
| LinuxFX       | 8         | 0.36%   |
| Garuda Linux  | 8         | 0.36%   |
| Ubuntu Unity  | 6         | 0.27%   |
| Ubuntu MATE   | 6         | 0.27%   |
| Ubuntu Budgie | 6         | 0.27%   |
| Peppermint    | 6         | 0.27%   |
| BlackPanther  | 6         | 0.27%   |
| SteamOS       | 5         | 0.22%   |
| CentOS        | 5         | 0.22%   |
| MX            | 4         | 0.18%   |
| Linux Lite    | 4         | 0.18%   |
| Xero          | 3         | 0.13%   |
| Sparky        | 3         | 0.13%   |
| Solus         | 3         | 0.13%   |
| Parrot        | 3         | 0.13%   |
| NixOS         | 3         | 0.13%   |
| Deepin        | 3         | 0.13%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002        | 172       | 6.63%   |
| 5.16.7-desktop-1omv4003         | 79        | 3.05%   |
| 5.4.0-42-generic                | 44        | 1.7%    |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 26        | 1%      |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 24        | 0.93%   |
| 5.4.0-52-generic                | 22        | 0.85%   |
| 5.4.0-48-generic                | 22        | 0.85%   |
| 5.4.0-29-generic                | 20        | 0.77%   |
| 5.4.0-58-generic                | 19        | 0.73%   |
| 5.4.0-26-generic                | 19        | 0.73%   |
| 5.3.0-46-generic                | 18        | 0.69%   |
| 5.4.0-33-generic                | 17        | 0.66%   |
| 5.11.0-37-generic               | 17        | 0.66%   |
| 5.0.0-37-generic                | 17        | 0.66%   |
| 5.4.0-54-generic                | 16        | 0.62%   |
| 4.15.0-desktop-45.1rosa-x86_64  | 16        | 0.62%   |
| 4.1.34-nrj-desktop-2rosa-x86_64 | 16        | 0.62%   |
| 5.8.0-43-generic                | 15        | 0.58%   |
| 5.4.0-40-generic                | 14        | 0.54%   |
| 5.4.0-37-generic                | 14        | 0.54%   |
| 5.3.0-40-generic                | 14        | 0.54%   |
| 5.15.0-43-generic               | 14        | 0.54%   |
| 5.3.0-42-generic                | 13        | 0.5%    |
| 5.15.0-47-generic               | 13        | 0.5%    |
| 5.13.0-39-generic               | 13        | 0.5%    |
| 5.13.0-27-generic               | 13        | 0.5%    |
| 5.11.0-27-generic               | 13        | 0.5%    |
| 5.11.0-25-generic               | 13        | 0.5%    |
| 4.15.0-43-generic               | 13        | 0.5%    |
| 5.4.0-91-generic                | 12        | 0.46%   |
| 5.4.0-74-generic                | 12        | 0.46%   |
| 5.13.0-28-generic               | 12        | 0.46%   |
| 5.11.0-43-generic               | 12        | 0.46%   |
| 5.11.0-34-generic               | 12        | 0.46%   |
| 5.10.0-9-amd64                  | 12        | 0.46%   |
| 5.4.0-66-generic                | 11        | 0.42%   |
| 5.11.0-38-generic               | 11        | 0.42%   |
| 4.18.0-25-generic               | 11        | 0.42%   |
| 4.18.0-15-generic               | 11        | 0.42%   |
| 5.8.0-53-generic                | 10        | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 431       | 17.54%  |
| 5.10.14 | 173       | 7.04%   |
| 4.15.0  | 147       | 5.98%   |
| 5.11.0  | 142       | 5.78%   |
| 5.8.0   | 127       | 5.17%   |
| 5.13.0  | 109       | 4.44%   |
| 5.3.0   | 103       | 4.19%   |
| 5.15.0  | 86        | 3.5%    |
| 5.16.7  | 80        | 3.26%   |
| 5.10.0  | 71        | 2.89%   |
| 5.0.0   | 61        | 2.48%   |
| 4.18.0  | 57        | 2.32%   |
| 4.9.20  | 35        | 1.42%   |
| 4.9.60  | 32        | 1.3%    |
| 4.19.0  | 30        | 1.22%   |
| 4.1.34  | 22        | 0.9%    |
| 5.14.0  | 19        | 0.77%   |
| 4.1.38  | 14        | 0.57%   |
| 5.11.12 | 12        | 0.49%   |
| 5.9.0   | 11        | 0.45%   |
| 5.4.32  | 10        | 0.41%   |
| 5.17.5  | 10        | 0.41%   |
| 5.17.0  | 10        | 0.41%   |
| 5.5.0   | 8         | 0.33%   |
| 5.16.0  | 8         | 0.33%   |
| 4.9.76  | 8         | 0.33%   |
| 5.16.11 | 7         | 0.28%   |
| 5.15.12 | 7         | 0.28%   |
| 5.7.0   | 6         | 0.24%   |
| 5.6.0   | 6         | 0.24%   |
| 5.4.83  | 6         | 0.24%   |
| 5.18.0  | 6         | 0.24%   |
| 5.15.11 | 6         | 0.24%   |
| 5.13.12 | 6         | 0.24%   |
| 4.9.155 | 6         | 0.24%   |
| 4.9.124 | 6         | 0.24%   |
| 5.9.11  | 5         | 0.2%    |
| 5.8.16  | 5         | 0.2%    |
| 5.6.19  | 5         | 0.2%    |
| 5.6.14  | 5         | 0.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 487       | 20.27%  |
| 5.10    | 293       | 12.19%  |
| 5.11    | 178       | 7.41%   |
| 5.8     | 158       | 6.58%   |
| 4.15    | 147       | 6.12%   |
| 5.15    | 138       | 5.74%   |
| 5.16    | 129       | 5.37%   |
| 5.13    | 126       | 5.24%   |
| 5.3     | 115       | 4.79%   |
| 4.9     | 99        | 4.12%   |
| 5.0     | 67        | 2.79%   |
| 4.18    | 60        | 2.5%    |
| 5.14    | 49        | 2.04%   |
| 5.17    | 46        | 1.91%   |
| 5.9     | 42        | 1.75%   |
| 5.6     | 41        | 1.71%   |
| 5.18    | 36        | 1.5%    |
| 4.19    | 36        | 1.5%    |
| 4.1     | 35        | 1.46%   |
| 5.12    | 25        | 1.04%   |
| 5.5     | 23        | 0.96%   |
| 5.19    | 21        | 0.87%   |
| 5.7     | 20        | 0.83%   |
| 4.4     | 7         | 0.29%   |
| 5.1     | 6         | 0.25%   |
| 3.10    | 4         | 0.17%   |
| 5.2     | 3         | 0.12%   |
| 6.0     | 2         | 0.08%   |
| 4.20    | 2         | 0.08%   |
| 4.13    | 2         | 0.08%   |
| 4.10    | 2         | 0.08%   |
| 4.17    | 1         | 0.04%   |
| 4.14    | 1         | 0.04%   |
| 4.12    | 1         | 0.04%   |
| 4.11    | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 2058      | 95.23%  |
| i686    | 102       | 4.72%   |
| aarch64 | 1         | 0.05%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 828       | 36.54%  |
| KDE5            | 506       | 22.33%  |
| Unknown         | 249       | 10.99%  |
| XFCE            | 160       | 7.06%   |
| X-Cinnamon      | 125       | 5.52%   |
| KDE4            | 97        | 4.28%   |
| KDE             | 71        | 3.13%   |
| MATE            | 43        | 1.9%    |
| Cinnamon        | 40        | 1.77%   |
| LXQt            | 33        | 1.46%   |
| LXDE            | 32        | 1.41%   |
| Pantheon        | 16        | 0.71%   |
| i3              | 13        | 0.57%   |
| Budgie          | 12        | 0.53%   |
| Deepin          | 9         | 0.4%    |
| Unity           | 7         | 0.31%   |
| GNOME Flashback | 5         | 0.22%   |
| GNOME Classic   | 3         | 0.13%   |
| awesome         | 3         | 0.13%   |
| trinity         | 2         | 0.09%   |
| sway            | 2         | 0.09%   |
| qtile           | 2         | 0.09%   |
| fluxbox         | 2         | 0.09%   |
| DWM             | 2         | 0.09%   |
| stumpwm         | 1         | 0.04%   |
| qt5ct           | 1         | 0.04%   |
| openbox         | 1         | 0.04%   |
| GNUstep         | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 1823      | 82.27%  |
| Wayland | 245       | 11.06%  |
| Unknown | 125       | 5.64%   |
| Tty     | 23        | 1.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 990       | 43.84%  |
| SDDM    | 510       | 22.59%  |
| GDM     | 293       | 12.98%  |
| LightDM | 142       | 6.29%   |
| GDM3    | 119       | 5.27%   |
| KDM     | 99        | 4.38%   |
| TDM     | 95        | 4.21%   |
| XDM     | 5         | 0.22%   |
| Ly      | 2         | 0.09%   |
| SLiM    | 1         | 0.04%   |
| MDM     | 1         | 0.04%   |
| LXDM    | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| pl_PL   | 1174      | 52.6%   |
| en_US   | 546       | 24.46%  |
| Unknown | 368       | 16.49%  |
| en_GB   | 61        | 2.73%   |
| C       | 34        | 1.52%   |
| ru_RU   | 11        | 0.49%   |
| szl_PL  | 8         | 0.36%   |
| de_DE   | 5         | 0.22%   |
| uk_UA   | 3         | 0.13%   |
| fr_FR   | 3         | 0.13%   |
| en_IE   | 3         | 0.13%   |
| nl_NL   | 2         | 0.09%   |
| it_IT   | 2         | 0.09%   |
| en_DK   | 2         | 0.09%   |
| C.UTF8  | 2         | 0.09%   |
| sk_SK   | 1         | 0.04%   |
| ru_UA   | 1         | 0.04%   |
| hu_HU   | 1         | 0.04%   |
| es_ES   | 1         | 0.04%   |
| en_IN   | 1         | 0.04%   |
| en_CA   | 1         | 0.04%   |
| en_AU   | 1         | 0.04%   |
| af_ZA   | 1         | 0.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 1172      | 53.2%   |
| EFI  | 1031      | 46.8%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 1574      | 70.9%   |
| Overlay  | 262       | 11.8%   |
| Unknown  | 173       | 7.79%   |
| Btrfs    | 144       | 6.49%   |
| Xfs      | 32        | 1.44%   |
| Zfs      | 16        | 0.72%   |
| F2fs     | 9         | 0.41%   |
| Ext2     | 3         | 0.14%   |
| Tmpfs    | 2         | 0.09%   |
| Ext3     | 2         | 0.09%   |
| XXXXX    | 1         | 0.05%   |
| Rootfs   | 1         | 0.05%   |
| Bcachefs | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1140      | 51.61%  |
| GPT     | 711       | 32.19%  |
| MBR     | 358       | 16.21%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1880      | 85.38%  |
| Yes       | 322       | 14.62%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1487      | 67.78%  |
| Yes       | 707       | 32.22%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 569       | 26.38%  |
| Dell                | 461       | 21.37%  |
| Hewlett-Packard     | 330       | 15.3%   |
| ASUSTek Computer    | 262       | 12.15%  |
| Acer                | 141       | 6.54%   |
| Toshiba             | 65        | 3.01%   |
| Samsung Electronics | 63        | 2.92%   |
| MSI                 | 48        | 2.23%   |
| Sony                | 31        | 1.44%   |
| HUAWEI              | 21        | 0.97%   |
| Fujitsu Siemens     | 20        | 0.93%   |
| Fujitsu             | 17        | 0.79%   |
| Packard Bell        | 12        | 0.56%   |
| Notebook            | 11        | 0.51%   |
| Apple               | 11        | 0.51%   |
| eMachines           | 9         | 0.42%   |
| Google              | 8         | 0.37%   |
| Medion              | 7         | 0.32%   |
| Timi                | 6         | 0.28%   |
| Valve               | 5         | 0.23%   |
| Kiano               | 4         | 0.19%   |
| mPTech              | 3         | 0.14%   |
| Clevo               | 3         | 0.14%   |
| Alienware           | 3         | 0.14%   |
| Unknown             | 3         | 0.14%   |
| Teclast             | 2         | 0.09%   |
| System76            | 2         | 0.09%   |
| Star Labs           | 2         | 0.09%   |
| MODECOM             | 2         | 0.09%   |
| MAXDATA             | 2         | 0.09%   |
| Maibenben           | 2         | 0.09%   |
| Kruger&Matz         | 2         | 0.09%   |
| Intel               | 2         | 0.09%   |
| IBM                 | 2         | 0.09%   |
| Getac               | 2         | 0.09%   |
| Framework           | 2         | 0.09%   |
| TUXEDO              | 1         | 0.05%   |
| TrekStor            | 1         | 0.05%   |
| Schenker            | 1         | 0.05%   |
| RM                  | 1         | 0.05%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Dell Inspiron 3451                   | 26        | 1.21%   |
| Unknown                              | 21        | 0.97%   |
| Dell Latitude E6400                  | 15        | 0.7%    |
| Lenovo G50-30 80G0                   | 12        | 0.56%   |
| Dell Latitude E6540                  | 11        | 0.51%   |
| Dell Latitude 5480                   | 10        | 0.46%   |
| Dell Latitude E6430                  | 9         | 0.42%   |
| Dell Latitude D630                   | 9         | 0.42%   |
| Dell Latitude 5490                   | 9         | 0.42%   |
| Lenovo G580 20150                    | 8         | 0.37%   |
| HP Pavilion dv7                      | 8         | 0.37%   |
| Dell Latitude E6420                  | 8         | 0.37%   |
| ASUS X555LJ                          | 8         | 0.37%   |
| HP Pavilion Gaming Laptop 15-ec1xxx  | 7         | 0.32%   |
| HP EliteBook 6930p                   | 7         | 0.32%   |
| HP 15                                | 7         | 0.32%   |
| Dell Latitude E7440                  | 7         | 0.32%   |
| Toshiba Satellite A300               | 6         | 0.28%   |
| Lenovo Legion Y540-15IRH 81SX        | 6         | 0.28%   |
| Lenovo Legion Y530-15ICH 81FV        | 6         | 0.28%   |
| Lenovo Legion 5 15ARH05 82B5         | 6         | 0.28%   |
| Lenovo IdeaPad 100-15IBY 80MJ        | 6         | 0.28%   |
| Lenovo G500 20236                    | 6         | 0.28%   |
| HP Pavilion g6                       | 6         | 0.28%   |
| HP Laptop 15-db1xxx                  | 6         | 0.28%   |
| Dell Latitude E7450                  | 6         | 0.28%   |
| Dell Latitude E5430 non-vPro         | 6         | 0.28%   |
| Dell Inspiron 3542                   | 6         | 0.28%   |
| Valve Jupiter                        | 5         | 0.23%   |
| Samsung 550P5C/550P7C                | 5         | 0.23%   |
| Samsung 350V5C/351V5C/3540VC/3440VC  | 5         | 0.23%   |
| Lenovo Z50-70 20354                  | 5         | 0.23%   |
| Lenovo IdeaPad Y510P 20217           | 5         | 0.23%   |
| Lenovo IdeaPad S340-14API 81NB       | 5         | 0.23%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY | 5         | 0.23%   |
| Lenovo IdeaPad 700-15ISK 80RU        | 5         | 0.23%   |
| Lenovo IdeaPad 330-15ICH 81FK        | 5         | 0.23%   |
| Lenovo IdeaPad 100-15IBD 80QQ        | 5         | 0.23%   |
| Lenovo G510 20238                    | 5         | 0.23%   |
| HUAWEI NBLK-WAX9X                    | 5         | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 260       | 12.05%  |
| Dell Latitude           | 239       | 11.08%  |
| Dell Inspiron           | 127       | 5.89%   |
| Lenovo IdeaPad          | 115       | 5.33%   |
| Acer Aspire             | 88        | 4.08%   |
| HP Pavilion             | 74        | 3.43%   |
| HP EliteBook            | 66        | 3.06%   |
| Toshiba Satellite       | 52        | 2.41%   |
| HP ProBook              | 49        | 2.27%   |
| Lenovo Legion           | 34        | 1.58%   |
| HP Laptop               | 30        | 1.39%   |
| ASUS VivoBook           | 30        | 1.39%   |
| Dell Precision          | 29        | 1.34%   |
| Dell Vostro             | 22        | 1.02%   |
| Dell XPS                | 21        | 0.97%   |
| Unknown                 | 21        | 0.97%   |
| HP Compaq               | 19        | 0.88%   |
| HP 250                  | 16        | 0.74%   |
| Fujitsu LIFEBOOK        | 15        | 0.7%    |
| ASUS TUF                | 14        | 0.65%   |
| ASUS ASUS               | 14        | 0.65%   |
| Acer Extensa            | 14        | 0.65%   |
| HP ZBook                | 13        | 0.6%    |
| Packard Bell EasyNote   | 12        | 0.56%   |
| Lenovo G50-30           | 12        | 0.56%   |
| ASUS ROG                | 12        | 0.56%   |
| Acer TravelMate         | 11        | 0.51%   |
| Lenovo Yoga             | 9         | 0.42%   |
| Lenovo G580             | 9         | 0.42%   |
| Acer Swift              | 9         | 0.42%   |
| Lenovo ThinkBook        | 8         | 0.37%   |
| HP OMEN                 | 8         | 0.37%   |
| Fujitsu Siemens AMILO   | 8         | 0.37%   |
| Dell G3                 | 8         | 0.37%   |
| ASUS X555LJ             | 8         | 0.37%   |
| HP 15                   | 7         | 0.32%   |
| Fujitsu Siemens ESPRIMO | 7         | 0.32%   |
| Acer Nitro              | 7         | 0.32%   |
| Samsung 350V5C          | 6         | 0.28%   |
| Lenovo G500             | 6         | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2013    | 192       | 8.9%    |
| 2019    | 189       | 8.76%   |
| 2012    | 186       | 8.62%   |
| 2011    | 181       | 8.39%   |
| 2020    | 171       | 7.93%   |
| 2008    | 157       | 7.28%   |
| 2018    | 151       | 7%      |
| 2014    | 147       | 6.82%   |
| 2015    | 136       | 6.31%   |
| 2010    | 124       | 5.75%   |
| 2017    | 107       | 4.96%   |
| 2016    | 98        | 4.54%   |
| 2021    | 93        | 4.31%   |
| 2007    | 92        | 4.27%   |
| 2009    | 81        | 3.76%   |
| 2006    | 33        | 1.53%   |
| 2022    | 14        | 0.65%   |
| 2005    | 3         | 0.14%   |
| 2004    | 1         | 0.05%   |
| Unknown | 1         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2157      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 2006      | 92.4%   |
| Enabled  | 165       | 7.6%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2147      | 99.54%  |
| Yes  | 10        | 0.46%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 586       | 26.82%  |
| 4.01-8.0    | 509       | 23.3%   |
| 8.01-16.0   | 349       | 15.97%  |
| 16.01-24.0  | 330       | 15.1%   |
| 32.01-64.0  | 164       | 7.51%   |
| 1.01-2.0    | 107       | 4.9%    |
| 2.01-3.0    | 79        | 3.62%   |
| 24.01-32.0  | 24        | 1.1%    |
| 64.01-256.0 | 19        | 0.87%   |
| 0.51-1.0    | 18        | 0.82%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 933       | 38.76%  |
| 2.01-3.0   | 518       | 21.52%  |
| 3.01-4.0   | 293       | 12.17%  |
| 4.01-8.0   | 288       | 11.97%  |
| 0.51-1.0   | 230       | 9.56%   |
| 8.01-16.0  | 105       | 4.36%   |
| 0.01-0.5   | 28        | 1.16%   |
| 16.01-24.0 | 10        | 0.42%   |
| 24.01-32.0 | 2         | 0.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1615      | 73.28%  |
| 2      | 484       | 21.96%  |
| 3      | 58        | 2.63%   |
| 0      | 36        | 1.63%   |
| 4      | 9         | 0.41%   |
| 5      | 2         | 0.09%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1219      | 55.97%  |
| Yes       | 959       | 44.03%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1916      | 88.5%   |
| No        | 249       | 11.5%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2130      | 98.61%  |
| No        | 30        | 1.39%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1643      | 74.78%  |
| No        | 554       | 25.22%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Poland  | 2157      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Warsaw                 | 511       | 21.93%  |
| Krakow                 | 186       | 7.98%   |
| Wroclaw                | 137       | 5.88%   |
| Poznan                 | 129       | 5.54%   |
| Lodz                   | 79        | 3.39%   |
| Gdansk                 | 73        | 3.13%   |
| Katowice               | 58        | 2.49%   |
| Szczecin               | 29        | 1.24%   |
| Lublin                 | 29        | 1.24%   |
| Gdynia                 | 25        | 1.07%   |
| Ruda Śląska          | 20        | 0.86%   |
| Torun                  | 19        | 0.82%   |
| Rzeszów               | 18        | 0.77%   |
| Częstochowa           | 18        | 0.77%   |
| Bialystok              | 18        | 0.77%   |
| Bydgoszcz              | 17        | 0.73%   |
| Gliwice                | 15        | 0.64%   |
| Chorzów               | 13        | 0.56%   |
| Opole                  | 12        | 0.52%   |
| Olsztyn                | 12        | 0.52%   |
| Kielce                 | 12        | 0.52%   |
| Elblag                 | 12        | 0.52%   |
| Bytom                  | 12        | 0.52%   |
| Blizniew               | 11        | 0.47%   |
| Tarnów                | 10        | 0.43%   |
| Sosnowiec              | 10        | 0.43%   |
| Płock                 | 9         | 0.39%   |
| Zabrze                 | 8         | 0.34%   |
| Pruszków              | 8         | 0.34%   |
| Bielsko-Biala          | 8         | 0.34%   |
| Siemianowice Śląskie | 7         | 0.3%    |
| Rybnik                 | 7         | 0.3%    |
| Chojnice               | 7         | 0.3%    |
| Zielona Góra          | 6         | 0.26%   |
| Wejherowo              | 6         | 0.26%   |
| Puławy                | 6         | 0.26%   |
| Jastrzębie Zdrój     | 6         | 0.26%   |
| Gorzów Wielkopolski   | 6         | 0.26%   |
| Cieszyn                | 6         | 0.26%   |
| Tychy                  | 5         | 0.21%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 366       | 474    | 13.77%  |
| Seagate             | 337       | 418    | 12.68%  |
| WDC                 | 319       | 389    | 12.01%  |
| Toshiba             | 187       | 235    | 7.04%   |
| GOODRAM             | 165       | 215    | 6.21%   |
| Unknown             | 118       | 151    | 4.44%   |
| Hitachi             | 111       | 133    | 4.18%   |
| SanDisk             | 110       | 138    | 4.14%   |
| Intel               | 103       | 127    | 3.88%   |
| Kingston            | 99        | 128    | 3.73%   |
| SK hynix            | 97        | 121    | 3.65%   |
| A-DATA Technology   | 94        | 113    | 3.54%   |
| Crucial             | 93        | 132    | 3.5%    |
| HGST                | 63        | 79     | 2.37%   |
| Micron Technology   | 49        | 63     | 1.84%   |
| SPCC                | 25        | 31     | 0.94%   |
| Plextor             | 25        | 36     | 0.94%   |
| KIOXIA              | 25        | 29     | 0.94%   |
| Patriot             | 24        | 32     | 0.9%    |
| PNY                 | 19        | 20     | 0.72%   |
| Fujitsu             | 17        | 18     | 0.64%   |
| LITEON              | 14        | 18     | 0.53%   |
| Transcend           | 10        | 11     | 0.38%   |
| Phison              | 10        | 15     | 0.38%   |
| LITEONIT            | 10        | 11     | 0.38%   |
| KIOXIA-EXCERIA      | 10        | 11     | 0.38%   |
| Apacer              | 10        | 13     | 0.38%   |
| China               | 9         | 12     | 0.34%   |
| OCZ                 | 7         | 7      | 0.26%   |
| Lenovo              | 6         | 8      | 0.23%   |
| HUAWEI              | 6         | 8      | 0.23%   |
| Union Memory        | 5         | 8      | 0.19%   |
| Lite-On             | 5         | 6      | 0.19%   |
| JMicron Technology  | 5         | 5      | 0.19%   |
| XPG                 | 4         | 5      | 0.15%   |
| Phison Electronics  | 4         | 4      | 0.15%   |
| Corsair             | 4         | 5      | 0.15%   |
| ASMedia             | 4         | 4      | 0.15%   |
| USB3.0              | 3         | 3      | 0.11%   |
| Solid State Storage | 3         | 3      | 0.11%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST500LT012-1DG142 500GB     | 46        | 1.67%   |
| Seagate ST1000LM035-1RK172 1TB      | 42        | 1.53%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 34        | 1.24%   |
| Intel NVMe SSD Drive 512GB          | 25        | 0.91%   |
| Samsung NVMe SSD Drive 512GB        | 21        | 0.76%   |
| GOODRAM SSD 120GB                   | 21        | 0.76%   |
| Seagate ST9500325AS 500GB           | 19        | 0.69%   |
| Toshiba MQ01ABD100 1TB              | 18        | 0.66%   |
| GOODRAM SSDPR-CX400-256-G2 256GB    | 18        | 0.66%   |
| Unknown MMC Card  32GB              | 17        | 0.62%   |
| Intel SSDPEKNW512G8H 512GB          | 17        | 0.62%   |
| HGST HTS721010A9E630 1TB            | 17        | 0.62%   |
| Crucial CT500MX500SSD1 500GB        | 17        | 0.62%   |
| SanDisk NVMe SSD Drive 512GB        | 16        | 0.58%   |
| Crucial CT1000MX500SSD1 1TB         | 16        | 0.58%   |
| Toshiba MQ01ABF050 500GB            | 15        | 0.55%   |
| Samsung SSD 850 EVO 250GB           | 15        | 0.55%   |
| Samsung NVMe SSD Drive 256GB        | 15        | 0.55%   |
| GOODRAM SSD 240GB                   | 15        | 0.55%   |
| Kingston SA400S37240G 240GB SSD     | 14        | 0.51%   |
| GOODRAM SSDPR-CX400-512 512GB       | 13        | 0.47%   |
| WDC WD10JPCX-24UE4T0 1TB            | 12        | 0.44%   |
| Unknown MMC Card  64GB              | 12        | 0.44%   |
| SK hynix NVMe SSD Drive 512GB       | 12        | 0.44%   |
| Seagate Expansion 1TB               | 12        | 0.44%   |
| Samsung SSD 860 EVO 500GB           | 12        | 0.44%   |
| Toshiba NVMe SSD Drive 512GB        | 11        | 0.4%    |
| Seagate ST1000LM014-SSHD-8GB        | 11        | 0.4%    |
| Patriot Burst 120GB SSD             | 11        | 0.4%    |
| HGST HTS725050A7E630 500GB          | 11        | 0.4%    |
| HGST HTS545050A7E680 500GB          | 11        | 0.4%    |
| Crucial CT240BX500SSD1 240GB        | 11        | 0.4%    |
| Seagate ST9250315AS 250GB           | 10        | 0.36%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 10        | 0.36%   |
| SanDisk NVMe SSD Drive 256GB        | 10        | 0.36%   |
| Samsung SSD 860 EVO 250GB           | 10        | 0.36%   |
| GOODRAM SSDPR-CX400-512-G2 512GB    | 10        | 0.36%   |
| A-DATA SU800 256GB SSD              | 10        | 0.36%   |
| WDC WD10JPVX-22JC3T0 1TB            | 9         | 0.33%   |
| SPCC Solid State Disk 512GB         | 9         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 335       | 414    | 36.53%  |
| WDC                 | 218       | 260    | 23.77%  |
| Toshiba             | 126       | 160    | 13.74%  |
| Hitachi             | 111       | 133    | 12.1%   |
| HGST                | 63        | 79     | 6.87%   |
| Samsung Electronics | 30        | 31     | 3.27%   |
| Fujitsu             | 17        | 18     | 1.85%   |
| USB3.0              | 3         | 3      | 0.33%   |
| Unknown             | 3         | 3      | 0.33%   |
| ASMedia             | 3         | 3      | 0.33%   |
| ASMT                | 2         | 2      | 0.22%   |
| StoreJet            | 1         | 1      | 0.11%   |
| SATAFIRM            | 1         | 1      | 0.11%   |
| SAGE                | 1         | 1      | 0.11%   |
| PHD 3.0             | 1         | 1      | 0.11%   |
| LaCie               | 1         | 2      | 0.11%   |
| IBM/Hitachi         | 1         | 1      | 0.11%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 186       | 244    | 18.18%  |
| Goodram             | 164       | 214    | 16.03%  |
| Crucial             | 89        | 127    | 8.7%    |
| A-DATA Technology   | 79        | 96     | 7.72%   |
| Kingston            | 77        | 99     | 7.53%   |
| SanDisk             | 75        | 95     | 7.33%   |
| WDC                 | 45        | 50     | 4.4%    |
| Intel               | 31        | 36     | 3.03%   |
| SK hynix            | 29        | 37     | 2.83%   |
| Micron Technology   | 29        | 37     | 2.83%   |
| Toshiba             | 27        | 29     | 2.64%   |
| SPCC                | 24        | 30     | 2.35%   |
| Plextor             | 22        | 33     | 2.15%   |
| Patriot             | 22        | 30     | 2.15%   |
| PNY                 | 14        | 15     | 1.37%   |
| LITEON              | 14        | 18     | 1.37%   |
| LITEONIT            | 10        | 11     | 0.98%   |
| Transcend           | 9         | 10     | 0.88%   |
| KIOXIA-EXCERIA      | 9         | 10     | 0.88%   |
| China               | 9         | 12     | 0.88%   |
| Apacer              | 9         | 12     | 0.88%   |
| OCZ                 | 7         | 7      | 0.68%   |
| KingSpec            | 3         | 3      | 0.29%   |
| 2-Power             | 3         | 3      | 0.29%   |
| Union Memory        | 2         | 3      | 0.2%    |
| Team                | 2         | 2      | 0.2%    |
| HS-SSD-C100         | 2         | 2      | 0.2%    |
| Gigabyte Technology | 2         | 3      | 0.2%    |
| Corsair             | 2         | 2      | 0.2%    |
| BIWIN               | 2         | 2      | 0.2%    |
| Apple               | 2         | 2      | 0.2%    |
| Wolf                | 1         | 2      | 0.1%    |
| WDC WDS2            | 1         | 1      | 0.1%    |
| Verbatim            | 1         | 1      | 0.1%    |
| Teclast             | 1         | 1      | 0.1%    |
| Seagate             | 1         | 1      | 0.1%    |
| RDM-II              | 1         | 1      | 0.1%    |
| Ramaxel Technology  | 1         | 1      | 0.1%    |
| Platinet            | 1         | 1      | 0.1%    |
| Phison              | 1         | 1      | 0.1%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 941       | 1298   | 37.36%  |
| HDD     | 883       | 1113   | 35.05%  |
| NVMe    | 563       | 750    | 22.35%  |
| MMC     | 105       | 135    | 4.17%   |
| Unknown | 27        | 33     | 1.07%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1633      | 2353   | 68.73%  |
| NVMe | 559       | 744    | 23.53%  |
| MMC  | 105       | 135    | 4.42%   |
| SAS  | 79        | 97     | 3.32%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1332      | 1807   | 74.37%  |
| 0.51-1.0   | 421       | 558    | 23.51%  |
| 1.01-2.0   | 34        | 42     | 1.9%    |
| 3.01-4.0   | 2         | 2      | 0.11%   |
| 2.01-3.0   | 1         | 1      | 0.06%   |
| 4.01-10.0  | 1         | 1      | 0.06%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 718       | 31.23%  |
| 251-500        | 507       | 22.05%  |
| 1-20           | 283       | 12.31%  |
| 501-1000       | 244       | 10.61%  |
| 51-100         | 212       | 9.22%   |
| 21-50          | 112       | 4.87%   |
| 1001-2000      | 97        | 4.22%   |
| Unknown        | 81        | 3.52%   |
| 2001-3000      | 23        | 1%      |
| More than 3000 | 22        | 0.96%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1043      | 43.97%  |
| 21-50          | 391       | 16.48%  |
| 51-100         | 299       | 12.61%  |
| 101-250        | 298       | 12.56%  |
| 251-500        | 132       | 5.56%   |
| 501-1000       | 88        | 3.71%   |
| Unknown        | 81        | 3.41%   |
| 1001-2000      | 31        | 1.31%   |
| 2001-3000      | 7         | 0.3%    |
| More than 3000 | 2         | 0.08%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB             | 8         | 9      | 3.2%    |
| Seagate ST500LT012-9WS142 500GB                | 7         | 24     | 2.8%    |
| Seagate ST9500325AS 500GB                      | 6         | 6      | 2.4%    |
| WDC WD5000BEVT-22ZAT0 500GB                    | 4         | 4      | 1.6%    |
| Seagate ST500LT012-1DG142 500GB                | 4         | 6      | 1.6%    |
| Hitachi HTS541612J9SA00 120GB                  | 4         | 5      | 1.6%    |
| HGST HTS545050A7E680 500GB                     | 4         | 4      | 1.6%    |
| WDC WD3200BPVT-80ZEST0 320GB                   | 3         | 3      | 1.2%    |
| WDC WD10JPVX-22JC3T0 1TB                       | 3         | 3      | 1.2%    |
| Toshiba MQ01ABD100 1TB                         | 3         | 4      | 1.2%    |
| Toshiba MK1246GSX 120GB                        | 3         | 3      | 1.2%    |
| SK hynix PC711 HFS512GDE9X073N 512GB           | 3         | 3      | 1.2%    |
| Seagate ST9500420AS 500GB                      | 3         | 3      | 1.2%    |
| Seagate ST9250827AS 250GB                      | 3         | 3      | 1.2%    |
| Seagate ST9250410AS 250GB                      | 3         | 3      | 1.2%    |
| Seagate ST1000LM014-1EJ164 1TB                 | 3         | 3      | 1.2%    |
| WDC WD1600BEVT-75A23T0 160GB                   | 2         | 2      | 0.8%    |
| WDC WD1600BEVT-22A23T0 160GB                   | 2         | 2      | 0.8%    |
| Toshiba MK3265GSX 320GB                        | 2         | 2      | 0.8%    |
| Toshiba MK1637GSX 160GB                        | 2         | 2      | 0.8%    |
| Seagate ST980811AS 80GB                        | 2         | 2      | 0.8%    |
| Seagate ST9320325AS 320GB                      | 2         | 2      | 0.8%    |
| Seagate ST9250315AS 250GB                      | 2         | 2      | 0.8%    |
| Seagate ST9160821AS 160GB                      | 2         | 3      | 0.8%    |
| Seagate ST320LT020-9YG142 320GB                | 2         | 2      | 0.8%    |
| Seagate ST1000LM014-SSHD-8GB                   | 2         | 2      | 0.8%    |
| SanDisk SD9SN8W-128G-1006 128GB SSD            | 2         | 2      | 0.8%    |
| Micron Technology 1100_MTFDDAK256TBN 256GB SSD | 2         | 2      | 0.8%    |
| Kingston SV300S37A120G 120GB SSD               | 2         | 2      | 0.8%    |
| Hitachi HTS543232A7A384 320GB                  | 2         | 3      | 0.8%    |
| Hitachi HTS543225L9SA00 250GB                  | 2         | 2      | 0.8%    |
| Hitachi HTS542516K9SA00 160GB                  | 2         | 2      | 0.8%    |
| Hitachi HTS542512K9SA00 120GB                  | 2         | 2      | 0.8%    |
| HGST HTS725050A7E630 500GB                     | 2         | 3      | 0.8%    |
| HGST HTS545050A7E380 500GB                     | 2         | 2      | 0.8%    |
| HGST HTS541010A9E680 1TB                       | 2         | 2      | 0.8%    |
| A-DATA Technology SU800 512GB SSD              | 2         | 2      | 0.8%    |
| WDC WDS120G2G0A-00JH30 120GB SSD               | 1         | 1      | 0.4%    |
| WDC WD7500BPKT-00PK4T0 752GB                   | 1         | 1      | 0.4%    |
| WDC WD6400BPVT-80HXZT1 640GB                   | 1         | 1      | 0.4%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 66        | 90     | 26.51%  |
| Toshiba             | 33        | 43     | 13.25%  |
| WDC                 | 30        | 31     | 12.05%  |
| Hitachi             | 29        | 32     | 11.65%  |
| Samsung Electronics | 15        | 16     | 6.02%   |
| A-DATA Technology   | 14        | 16     | 5.62%   |
| HGST                | 12        | 13     | 4.82%   |
| SK hynix            | 8         | 8      | 3.21%   |
| Intel               | 6         | 6      | 2.41%   |
| SanDisk             | 5         | 6      | 2.01%   |
| Micron Technology   | 4         | 4      | 1.61%   |
| Kingston            | 4         | 4      | 1.61%   |
| LITEON              | 3         | 3      | 1.2%    |
| Fujitsu             | 3         | 3      | 1.2%    |
| Crucial             | 3         | 4      | 1.2%    |
| ASMedia             | 3         | 3      | 1.2%    |
| OCZ                 | 2         | 2      | 0.8%    |
| LITEONIT            | 2         | 2      | 0.8%    |
| SPCC                | 1         | 1      | 0.4%    |
| Plextor             | 1         | 1      | 0.4%    |
| Platinet            | 1         | 1      | 0.4%    |
| Patriot             | 1         | 3      | 0.4%    |
| Lexar               | 1         | 1      | 0.4%    |
| Lenovo              | 1         | 1      | 0.4%    |
| Apacer              | 1         | 1      | 0.4%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 66        | 90     | 36.67%  |
| Toshiba             | 30        | 40     | 16.67%  |
| WDC                 | 29        | 30     | 16.11%  |
| Hitachi             | 29        | 32     | 16.11%  |
| HGST                | 12        | 13     | 6.67%   |
| Samsung Electronics | 8         | 8      | 4.44%   |
| Fujitsu             | 3         | 3      | 1.67%   |
| ASMedia             | 3         | 3      | 1.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 179       | 219    | 72.76%  |
| SSD  | 54        | 61     | 21.95%  |
| NVMe | 13        | 15     | 5.28%   |

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
| Detected | 1118      | 1726   | 48.93%  |
| Works    | 922       | 1303   | 40.35%  |
| Malfunc  | 240       | 295    | 10.5%   |
| Failed   | 5         | 5      | 0.22%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1708      | 68.95%  |
| AMD                              | 204       | 8.24%   |
| Samsung Electronics              | 161       | 6.5%    |
| SanDisk                          | 91        | 3.67%   |
| SK hynix                         | 69        | 2.79%   |
| Toshiba America Info Systems     | 37        | 1.49%   |
| KIOXIA                           | 28        | 1.13%   |
| Phison Electronics               | 24        | 0.97%   |
| Kingston Technology Company      | 22        | 0.89%   |
| Micron Technology                | 20        | 0.81%   |
| Nvidia                           | 17        | 0.69%   |
| ADATA Technology                 | 16        | 0.65%   |
| Silicon Integrated Systems [SiS] | 11        | 0.44%   |
| Union Memory (Shenzhen)          | 10        | 0.4%    |
| Silicon Motion                   | 8         | 0.32%   |
| Lite-On Technology               | 8         | 0.32%   |
| Realtek Semiconductor            | 7         | 0.28%   |
| Solid State Storage Technology   | 6         | 0.24%   |
| Micron/Crucial Technology        | 6         | 0.24%   |
| Lenovo                           | 6         | 0.24%   |
| VIA Technologies                 | 5         | 0.2%    |
| JMicron Technology               | 4         | 0.16%   |
| Yangtze Memory Technologies      | 2         | 0.08%   |
| Silicon Image                    | 1         | 0.04%   |
| Shenzhen Longsys Electronics     | 1         | 0.04%   |
| O2 Micro                         | 1         | 0.04%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.04%   |
| Marvell Technology Group         | 1         | 0.04%   |
| ASMedia Technology               | 1         | 0.04%   |
| Apple                            | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 192       | 6.99%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 167       | 6.08%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 142       | 5.17%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 135       | 4.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 127       | 4.63%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 119       | 4.34%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 103       | 3.75%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 94        | 3.42%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 88        | 3.21%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 76        | 2.77%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 71        | 2.59%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 70        | 2.55%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 68        | 2.48%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 61        | 2.22%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 57        | 2.08%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 56        | 2.04%   |
| Intel SSD 660P Series                                                          | 54        | 1.97%   |
| Intel Volume Management Device NVMe RAID Controller                            | 52        | 1.89%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 46        | 1.68%   |
| Samsung NVMe SSD Controller 980                                                | 44        | 1.6%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 33        | 1.2%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 31        | 1.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 31        | 1.13%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 27        | 0.98%   |
| SK hynix Gold P31 SSD                                                          | 25        | 0.91%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 23        | 0.84%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 23        | 0.84%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 20        | 0.73%   |
| Micron Non-Volatile memory controller                                          | 20        | 0.73%   |
| Intel Comet Lake SATA AHCI Controller                                          | 20        | 0.73%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 18        | 0.66%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 18        | 0.66%   |
| SK hynix BC511                                                                 | 17        | 0.62%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 17        | 0.62%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 17        | 0.62%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 16        | 0.58%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 16        | 0.58%   |
| Intel Tiger Lake-LP SATA Controller                                            | 16        | 0.58%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 16        | 0.58%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 16        | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1573      | 60.18%  |
| NVMe | 568       | 21.73%  |
| IDE  | 275       | 10.52%  |
| RAID | 198       | 7.57%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 1848      | 85.67%  |
| AMD          | 307       | 14.23%  |
| QUALCOMM     | 1         | 0.05%   |
| CentaurHauls | 1         | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron CPU N2840 @ 2.16GHz             | 43        | 1.99%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 36        | 1.67%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 32        | 1.48%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 30        | 1.39%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 28        | 1.3%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 28        | 1.3%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 28        | 1.3%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 26        | 1.2%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 26        | 1.2%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 25        | 1.16%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 23        | 1.07%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 23        | 1.07%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 23        | 1.07%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 21        | 0.97%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 21        | 0.97%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 21        | 0.97%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 21        | 0.97%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 19        | 0.88%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 19        | 0.88%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 18        | 0.83%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 18        | 0.83%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 18        | 0.83%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 18        | 0.83%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 18        | 0.83%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 17        | 0.79%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 17        | 0.79%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 17        | 0.79%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 16        | 0.74%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 16        | 0.74%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 16        | 0.74%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 15        | 0.7%    |
| Intel Core i5-4200U CPU @ 1.60GHz             | 15        | 0.7%    |
| Intel Core i5-2410M CPU @ 2.30GHz             | 15        | 0.7%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 15        | 0.7%    |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 15        | 0.7%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 15        | 0.7%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 14        | 0.65%   |
| Intel Core i5-3340M CPU @ 2.70GHz             | 14        | 0.65%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 14        | 0.65%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 14        | 0.65%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 605       | 28.04%  |
| Intel Core i7                  | 416       | 19.28%  |
| Intel Core 2 Duo               | 194       | 8.99%   |
| Intel Core i3                  | 190       | 8.8%    |
| Intel Celeron                  | 113       | 5.24%   |
| AMD Ryzen 5                    | 92        | 4.26%   |
| Other                          | 82        | 3.8%    |
| Intel Pentium                  | 70        | 3.24%   |
| AMD Ryzen 7                    | 66        | 3.06%   |
| Intel Atom                     | 47        | 2.18%   |
| Intel Pentium Dual-Core        | 36        | 1.67%   |
| Intel Core 2                   | 20        | 0.93%   |
| AMD A6                         | 18        | 0.83%   |
| Intel Pentium Dual             | 17        | 0.79%   |
| Intel Genuine                  | 15        | 0.7%    |
| AMD A8                         | 13        | 0.6%    |
| AMD Ryzen 7 PRO                | 12        | 0.56%   |
| AMD A4                         | 11        | 0.51%   |
| Intel Celeron M                | 10        | 0.46%   |
| AMD E1                         | 10        | 0.46%   |
| AMD E                          | 10        | 0.46%   |
| AMD A10                        | 9         | 0.42%   |
| Intel Xeon                     | 7         | 0.32%   |
| Intel Pentium M                | 7         | 0.32%   |
| AMD Turion 64 X2 Mobile        | 7         | 0.32%   |
| AMD E2                         | 7         | 0.32%   |
| AMD Athlon X2                  | 6         | 0.28%   |
| Intel Core Duo                 | 5         | 0.23%   |
| AMD Ryzen 9                    | 5         | 0.23%   |
| AMD Ryzen 3                    | 5         | 0.23%   |
| Intel Celeron Dual-Core        | 4         | 0.19%   |
| AMD Turion X2 Dual-Core Mobile | 4         | 0.19%   |
| AMD Phenom II                  | 4         | 0.19%   |
| AMD Athlon II                  | 4         | 0.19%   |
| Intel Core i9                  | 3         | 0.14%   |
| AMD C-60                       | 3         | 0.14%   |
| Intel Pentium Silver           | 2         | 0.09%   |
| Intel Core m5                  | 2         | 0.09%   |
| Intel Core M                   | 2         | 0.09%   |
| Intel Core 2 Quad              | 2         | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1255      | 58.13%  |
| 4       | 601       | 27.84%  |
| 6       | 124       | 5.74%   |
| 8       | 91        | 4.21%   |
| 1       | 59        | 2.73%   |
| Unknown | 21        | 0.97%   |
| 14      | 4         | 0.19%   |
| 3       | 2         | 0.09%   |
| 192     | 1         | 0.05%   |
| 5       | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 2154      | 99.86%  |
| Unknown | 2         | 0.09%   |
| 2       | 1         | 0.05%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1474      | 68.18%  |
| 1       | 667       | 30.85%  |
| Unknown | 21        | 0.97%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2079      | 96.16%  |
| 32-bit         | 43        | 1.99%   |
| Unknown        | 39        | 1.8%    |
| 64-bit         | 1         | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 358       | 16.17%  |
| 0x206a7    | 163       | 7.36%   |
| 0x306a9    | 155       | 7%      |
| 0x1067a    | 100       | 4.52%   |
| 0x40651    | 89        | 4.02%   |
| 0x20655    | 76        | 3.43%   |
| 0x906ea    | 71        | 3.21%   |
| 0x806ec    | 67        | 3.03%   |
| 0x306c3    | 67        | 3.03%   |
| 0x30678    | 67        | 3.03%   |
| 0x306d4    | 66        | 2.98%   |
| 0x6fd      | 63        | 2.85%   |
| 0x806ea    | 61        | 2.76%   |
| 0x406e3    | 55        | 2.48%   |
| 0x806c1    | 52        | 2.35%   |
| 0x806e9    | 49        | 2.21%   |
| 0x10676    | 44        | 1.99%   |
| 0x506e3    | 41        | 1.85%   |
| 0x906e9    | 38        | 1.72%   |
| 0x20652    | 29        | 1.31%   |
| 0xa0652    | 22        | 0.99%   |
| 0x0a50000c | 22        | 0.99%   |
| 0x806eb    | 21        | 0.95%   |
| 0x08108109 | 21        | 0.95%   |
| 0x08108102 | 21        | 0.95%   |
| 0x08600106 | 20        | 0.9%    |
| 0x706e5    | 19        | 0.86%   |
| 0x6fb      | 18        | 0.81%   |
| 0x6f6      | 17        | 0.77%   |
| 0x08600104 | 16        | 0.72%   |
| 0x08600103 | 15        | 0.68%   |
| 0x06001119 | 15        | 0.68%   |
| 0x106ca    | 14        | 0.63%   |
| 0x106c2    | 13        | 0.59%   |
| 0x806d1    | 12        | 0.54%   |
| 0x6e8      | 12        | 0.54%   |
| 0x406c4    | 12        | 0.54%   |
| 0x05000119 | 12        | 0.54%   |
| 0x906ed    | 11        | 0.5%    |
| 0x406c3    | 11        | 0.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 375       | 17.38%  |
| Haswell          | 191       | 8.85%   |
| SandyBridge      | 184       | 8.53%   |
| IvyBridge        | 183       | 8.48%   |
| Penryn           | 159       | 7.37%   |
| Core             | 133       | 6.16%   |
| Skylake          | 114       | 5.28%   |
| Westmere         | 112       | 5.19%   |
| Silvermont       | 100       | 4.63%   |
| Broadwell        | 85        | 3.94%   |
| Zen 2            | 74        | 3.43%   |
| TigerLake        | 58        | 2.69%   |
| Zen+             | 53        | 2.46%   |
| Icelake          | 35        | 1.62%   |
| Zen 3            | 30        | 1.39%   |
| Bonnell          | 30        | 1.39%   |
| CometLake        | 29        | 1.34%   |
| P6               | 28        | 1.3%    |
| Bobcat           | 23        | 1.07%   |
| Unknown          | 21        | 0.97%   |
| Piledriver       | 19        | 0.88%   |
| Zen              | 16        | 0.74%   |
| K8 Hammer        | 12        | 0.56%   |
| K8 & K10 hybrid  | 12        | 0.56%   |
| Jaguar           | 12        | 0.56%   |
| Goldmont plus    | 12        | 0.56%   |
| Puma             | 11        | 0.51%   |
| K10              | 11        | 0.51%   |
| Excavator        | 9         | 0.42%   |
| K10 Llano        | 8         | 0.37%   |
| Goldmont         | 7         | 0.32%   |
| Nehalem          | 6         | 0.28%   |
| Alderlake Hybrid | 4         | 0.19%   |
| Steamroller      | 2         | 0.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1628      | 58.62%  |
| Nvidia                           | 664       | 23.91%  |
| AMD                              | 474       | 17.07%  |
| Silicon Integrated Systems [SiS] | 6         | 0.22%   |
| VIA Technologies                 | 5         | 0.18%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 177       | 6.07%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 171       | 5.87%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 106       | 3.64%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 96        | 3.29%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 78        | 2.68%   |
| Intel HD Graphics 5500                                                                   | 76        | 2.61%   |
| Intel Core Processor Integrated Graphics Controller                                      | 75        | 2.57%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 74        | 2.54%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 73        | 2.5%    |
| Intel UHD Graphics 620                                                                   | 70        | 2.4%    |
| AMD Renoir                                                                               | 69        | 2.37%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 67        | 2.3%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 67        | 2.3%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 63        | 2.16%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 61        | 2.09%   |
| Intel HD Graphics 620                                                                    | 56        | 1.92%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 54        | 1.85%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 54        | 1.85%   |
| Intel HD Graphics 630                                                                    | 45        | 1.54%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 43        | 1.48%   |
| Intel HD Graphics 530                                                                    | 38        | 1.3%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 36        | 1.23%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 34        | 1.17%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 34        | 1.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 27        | 0.93%   |
| AMD Cezanne                                                                              | 27        | 0.93%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 26        | 0.89%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 25        | 0.86%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 24        | 0.82%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 24        | 0.82%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 23        | 0.79%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 22        | 0.75%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 21        | 0.72%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 20        | 0.69%   |
| Nvidia GM108M [GeForce 840M]                                                             | 20        | 0.69%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 19        | 0.65%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 18        | 0.62%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 17        | 0.58%   |
| Nvidia TU117M                                                                            | 16        | 0.55%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 16        | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 1060      | 49.1%   |
| Intel + Nvidia | 456       | 21.12%  |
| 1 x AMD        | 276       | 12.78%  |
| 1 x Nvidia     | 156       | 7.23%   |
| Intel + AMD    | 111       | 5.14%   |
| AMD + Nvidia   | 52        | 2.41%   |
| 2 x AMD        | 34        | 1.57%   |
| 1 x SiS        | 6         | 0.28%   |
| 1 x VIA        | 5         | 0.23%   |
| Other          | 2         | 0.09%   |
| 2 x Intel      | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1815      | 83.14%  |
| Proprietary | 308       | 14.11%  |
| Unknown     | 60        | 2.75%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1274      | 57.57%  |
| 1.01-2.0   | 318       | 14.37%  |
| 0.01-0.5   | 288       | 13.01%  |
| 3.01-4.0   | 142       | 6.42%   |
| 0.51-1.0   | 139       | 6.28%   |
| 5.01-6.0   | 37        | 1.67%   |
| 7.01-8.0   | 12        | 0.54%   |
| 2.01-3.0   | 2         | 0.09%   |
| 8.01-16.0  | 1         | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 459       | 18.51%  |
| LG Display              | 403       | 16.25%  |
| Samsung Electronics     | 323       | 13.02%  |
| BOE                     | 277       | 11.17%  |
| Chimei Innolux          | 256       | 10.32%  |
| Chi Mei Optoelectronics | 91        | 3.67%   |
| Dell                    | 90        | 3.63%   |
| Lenovo                  | 78        | 3.15%   |
| Goldstar                | 49        | 1.98%   |
| Iiyama                  | 44        | 1.77%   |
| LG Philips              | 40        | 1.61%   |
| Sharp                   | 35        | 1.41%   |
| PANDA                   | 26        | 1.05%   |
| Philips                 | 24        | 0.97%   |
| BenQ                    | 22        | 0.89%   |
| NEC Computers           | 19        | 0.77%   |
| AOC                     | 18        | 0.73%   |
| Acer                    | 17        | 0.69%   |
| InfoVision              | 15        | 0.6%    |
| Ancor Communications    | 15        | 0.6%    |
| Hewlett-Packard         | 14        | 0.56%   |
| HannStar                | 12        | 0.48%   |
| CPT                     | 12        | 0.48%   |
| Eizo                    | 9         | 0.36%   |
| Apple                   | 9         | 0.36%   |
| Toshiba                 | 8         | 0.32%   |
| LGD                     | 8         | 0.32%   |
| Seiko/Epson             | 7         | 0.28%   |
| Fujitsu Siemens         | 6         | 0.24%   |
| Sony                    | 5         | 0.2%    |
| Panasonic               | 5         | 0.2%    |
| InnoLux Display         | 5         | 0.2%    |
| ASUSTek Computer        | 5         | 0.2%    |
| Vestel Elektronik       | 4         | 0.16%   |
| LPL                     | 4         | 0.16%   |
| Hitachi                 | 4         | 0.16%   |
| CSO                     | 4         | 0.16%   |
| ANX                     | 4         | 0.16%   |
| ViewSonic               | 3         | 0.12%   |
| TMX                     | 3         | 0.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch     | 27        | 1.07%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 27        | 1.07%   |
| BOE LCD Monitor BOE0629 1366x768 309x173mm 13.9-inch                     | 26        | 1.03%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 21        | 0.83%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 19        | 0.75%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 17        | 0.67%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 16        | 0.63%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                  | 15        | 0.59%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 15        | 0.59%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch     | 13        | 0.51%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 13        | 0.51%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 12        | 0.47%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 12        | 0.47%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch             | 11        | 0.44%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 11        | 0.44%   |
| BOE LCD Monitor BOE06FB 1920x1080 344x194mm 15.5-inch                    | 11        | 0.44%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 11        | 0.44%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 11        | 0.44%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 11        | 0.44%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 11        | 0.44%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 10        | 0.4%    |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 10        | 0.4%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 10        | 0.4%    |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 10        | 0.4%    |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch           | 10        | 0.4%    |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 9         | 0.36%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 9         | 0.36%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch          | 9         | 0.36%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 9         | 0.36%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 8         | 0.32%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 8         | 0.32%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 8         | 0.32%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 8         | 0.32%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 7         | 0.28%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch    | 7         | 0.28%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 7         | 0.28%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 7         | 0.28%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                         | 7         | 0.28%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 7         | 0.28%   |
| BOE LCD Monitor BOE0869 1920x1080 344x194mm 15.5-inch                    | 7         | 0.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 911       | 39.47%  |
| 1366x768 (WXGA)    | 648       | 28.08%  |
| 1600x900 (HD+)     | 165       | 7.15%   |
| 1280x800 (WXGA)    | 163       | 7.06%   |
| 3840x2160 (4K)     | 73        | 3.16%   |
| 2560x1440 (QHD)    | 57        | 2.47%   |
| 1440x900 (WXGA+)   | 55        | 2.38%   |
| 1920x1200 (WUXGA)  | 45        | 1.95%   |
| 1680x1050 (WSXGA+) | 44        | 1.91%   |
| 1024x600           | 25        | 1.08%   |
| 1280x1024 (SXGA)   | 20        | 0.87%   |
| 2560x1600          | 13        | 0.56%   |
| 3440x1440          | 10        | 0.43%   |
| 2560x1080          | 8         | 0.35%   |
| 1024x768 (XGA)     | 7         | 0.3%    |
| Unknown            | 7         | 0.3%    |
| 3840x2400          | 6         | 0.26%   |
| 2160x1440          | 6         | 0.26%   |
| 800x1280           | 5         | 0.22%   |
| 3200x1800 (QHD+)   | 4         | 0.17%   |
| 1680x945           | 4         | 0.17%   |
| 3286x1080          | 3         | 0.13%   |
| 1400x1050          | 3         | 0.13%   |
| 3840x1600          | 2         | 0.09%   |
| 3840x1080          | 2         | 0.09%   |
| 3000x2000          | 2         | 0.09%   |
| 2880x1800          | 2         | 0.09%   |
| 2288x1287          | 2         | 0.09%   |
| 2256x1504          | 2         | 0.09%   |
| 1280x768           | 2         | 0.09%   |
| 1280x720 (HD)      | 2         | 0.09%   |
| 6400x1600          | 1         | 0.04%   |
| 3456x2160          | 1         | 0.04%   |
| 3300x2200          | 1         | 0.04%   |
| 3200x2000          | 1         | 0.04%   |
| 2304x1440          | 1         | 0.04%   |
| 2048x1152          | 1         | 0.04%   |
| 1920x540           | 1         | 0.04%   |
| 1920x1280          | 1         | 0.04%   |
| 1600x1200          | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1097      | 44.14%  |
| 14      | 273       | 10.99%  |
| 13      | 273       | 10.99%  |
| 17      | 185       | 7.44%   |
| 24      | 102       | 4.1%    |
| 23      | 82        | 3.3%    |
| 12      | 80        | 3.22%   |
| 27      | 65        | 2.62%   |
| Unknown | 56        | 2.25%   |
| 21      | 50        | 2.01%   |
| 11      | 28        | 1.13%   |
| 10      | 26        | 1.05%   |
| 19      | 22        | 0.89%   |
| 22      | 21        | 0.85%   |
| 34      | 18        | 0.72%   |
| 18      | 18        | 0.72%   |
| 31      | 15        | 0.6%    |
| 16      | 15        | 0.6%    |
| 84      | 8         | 0.32%   |
| 20      | 8         | 0.32%   |
| 48      | 7         | 0.28%   |
| 25      | 6         | 0.24%   |
| 72      | 4         | 0.16%   |
| 40      | 4         | 0.16%   |
| 43      | 3         | 0.12%   |
| 37      | 3         | 0.12%   |
| 32      | 3         | 0.12%   |
| 54      | 2         | 0.08%   |
| 28      | 2         | 0.08%   |
| 26      | 2         | 0.08%   |
| 142     | 1         | 0.04%   |
| 52      | 1         | 0.04%   |
| 46      | 1         | 0.04%   |
| 35      | 1         | 0.04%   |
| 33      | 1         | 0.04%   |
| 29      | 1         | 0.04%   |
| 3       | 1         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 1497      | 61.08%  |
| 201-300        | 241       | 9.83%   |
| 351-400        | 236       | 9.63%   |
| 501-600        | 233       | 9.51%   |
| 401-500        | 106       | 4.32%   |
| Unknown        | 56        | 2.28%   |
| 601-700        | 24        | 0.98%   |
| 701-800        | 22        | 0.9%    |
| 1501-2000      | 12        | 0.49%   |
| 1001-1500      | 11        | 0.45%   |
| 801-900        | 8         | 0.33%   |
| 901-1000       | 3         | 0.12%   |
| More than 2000 | 1         | 0.04%   |
| 1-100          | 1         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1737      | 79.5%   |
| 16/10   | 315       | 14.42%  |
| Unknown | 42        | 1.92%   |
| 3/2     | 25        | 1.14%   |
| 5/4     | 21        | 0.96%   |
| 21/9    | 21        | 0.96%   |
| 4/3     | 15        | 0.69%   |
| 0.62    | 5         | 0.23%   |
| 32/9    | 2         | 0.09%   |
| 6/5     | 1         | 0.05%   |
| 1.00    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1096      | 44.32%  |
| 81-90          | 452       | 18.28%  |
| 201-250        | 193       | 7.8%    |
| 121-130        | 146       | 5.9%    |
| 71-80          | 90        | 3.64%   |
| 61-70          | 79        | 3.19%   |
| 301-350        | 67        | 2.71%   |
| Unknown        | 56        | 2.26%   |
| 251-300        | 52        | 2.1%    |
| 351-500        | 38        | 1.54%   |
| 151-200        | 37        | 1.5%    |
| 131-140        | 34        | 1.37%   |
| 51-60          | 28        | 1.13%   |
| 41-50          | 26        | 1.05%   |
| 141-150        | 25        | 1.01%   |
| More than 1000 | 22        | 0.89%   |
| 501-1000       | 12        | 0.49%   |
| 91-100         | 12        | 0.49%   |
| 111-120        | 7         | 0.28%   |
| 1-40           | 1         | 0.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 974       | 40.16%  |
| 101-120       | 729       | 30.06%  |
| 51-100        | 516       | 21.28%  |
| 161-240       | 86        | 3.55%   |
| Unknown       | 56        | 2.31%   |
| More than 240 | 47        | 1.94%   |
| 1-50          | 17        | 0.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1757      | 79.22%  |
| 2     | 355       | 16.01%  |
| 3     | 52        | 2.34%   |
| 0     | 48        | 2.16%   |
| 4     | 6         | 0.27%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1254      | 35.03%  |
| Realtek Semiconductor             | 1001      | 27.96%  |
| Qualcomm Atheros                  | 562       | 15.7%   |
| Broadcom                          | 245       | 6.84%   |
| Broadcom Limited                  | 78        | 2.18%   |
| Dell                              | 56        | 1.56%   |
| Marvell Technology Group          | 55        | 1.54%   |
| Huawei Technologies               | 51        | 1.42%   |
| Ralink                            | 31        | 0.87%   |
| Ericsson Business Mobile Networks | 25        | 0.7%    |
| MediaTek                          | 20        | 0.56%   |
| TP-Link                           | 18        | 0.5%    |
| Hewlett-Packard                   | 16        | 0.45%   |
| Samsung Electronics               | 15        | 0.42%   |
| JMicron Technology                | 15        | 0.42%   |
| Xiaomi                            | 13        | 0.36%   |
| Sierra Wireless                   | 13        | 0.36%   |
| Ralink Technology                 | 10        | 0.28%   |
| Lenovo                            | 10        | 0.28%   |
| Silicon Integrated Systems [SiS]  | 9         | 0.25%   |
| Nvidia                            | 9         | 0.25%   |
| Qualcomm Atheros Communications   | 8         | 0.22%   |
| FIBOCOM                           | 8         | 0.22%   |
| DisplayLink                       | 8         | 0.22%   |
| ASIX Electronics                  | 8         | 0.22%   |
| Qualcomm                          | 6         | 0.17%   |
| Motorola PCS                      | 5         | 0.14%   |
| ASUSTek Computer                  | 5         | 0.14%   |
| VIA Technologies                  | 4         | 0.11%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.06%   |
| NetGear                           | 2         | 0.06%   |
| Microsoft                         | 2         | 0.06%   |
| HTC (High Tech Computer)          | 2         | 0.06%   |
| Attansic Technology               | 2         | 0.06%   |
| Toshiba                           | 1         | 0.03%   |
| Tenda                             | 1         | 0.03%   |
| Shenzhen Goodix Technology        | 1         | 0.03%   |
| Sagem                             | 1         | 0.03%   |
| QinHeng Electronics               | 1         | 0.03%   |
| Linksys                           | 1         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 660       | 15.19%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 198       | 4.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 128       | 2.95%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 98        | 2.26%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 98        | 2.26%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 97        | 2.23%   |
| Intel Wireless 8265 / 8275                                              | 86        | 1.98%   |
| Intel Wireless 7260                                                     | 86        | 1.98%   |
| Intel Wi-Fi 6 AX200                                                     | 83        | 1.91%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 71        | 1.63%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 67        | 1.54%   |
| Intel Wireless 8260                                                     | 65        | 1.5%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 62        | 1.43%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 60        | 1.38%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 57        | 1.31%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 56        | 1.29%   |
| Intel Wireless 7265                                                     | 51        | 1.17%   |
| Intel Wireless 3160                                                     | 48        | 1.1%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 47        | 1.08%   |
| Intel 82567LM Gigabit Network Connection                                | 47        | 1.08%   |
| Intel Wi-Fi 6 AX201                                                     | 45        | 1.04%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 41        | 0.94%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 40        | 0.92%   |
| Intel Ethernet Connection I218-LM                                       | 39        | 0.9%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 38        | 0.87%   |
| Intel Wireless 3165                                                     | 38        | 0.87%   |
| Intel WiFi Link 5100                                                    | 38        | 0.87%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 37        | 0.85%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 37        | 0.85%   |
| Intel Centrino Ultimate-N 6300                                          | 37        | 0.85%   |
| Intel 82577LM Gigabit Network Connection                                | 36        | 0.83%   |
| Broadcom BCM43142 802.11b/g/n                                           | 36        | 0.83%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 33        | 0.76%   |
| Huawei E353/E3131                                                       | 31        | 0.71%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 30        | 0.69%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 30        | 0.69%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 30        | 0.69%   |
| Intel Ethernet Connection I217-LM                                       | 29        | 0.67%   |
| Intel Centrino Advanced-N 6200                                          | 28        | 0.64%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 27        | 0.62%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1190      | 52.42%  |
| Qualcomm Atheros                  | 471       | 20.75%  |
| Realtek Semiconductor             | 236       | 10.4%   |
| Broadcom                          | 163       | 7.18%   |
| Broadcom Limited                  | 42        | 1.85%   |
| Dell                              | 35        | 1.54%   |
| Ralink                            | 31        | 1.37%   |
| MediaTek                          | 18        | 0.79%   |
| TP-Link                           | 14        | 0.62%   |
| Sierra Wireless                   | 13        | 0.57%   |
| Ralink Technology                 | 10        | 0.44%   |
| Qualcomm Atheros Communications   | 8         | 0.35%   |
| FIBOCOM                           | 8         | 0.35%   |
| Ericsson Business Mobile Networks | 8         | 0.35%   |
| Hewlett-Packard                   | 5         | 0.22%   |
| ASUSTek Computer                  | 5         | 0.22%   |
| Qualcomm                          | 4         | 0.18%   |
| NetGear                           | 2         | 0.09%   |
| Microsoft                         | 2         | 0.09%   |
| Tenda                             | 1         | 0.04%   |
| Sagem                             | 1         | 0.04%   |
| Linksys                           | 1         | 0.04%   |
| Edimax Technology                 | 1         | 0.04%   |
| Belkin Components                 | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 98        | 4.31%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 98        | 4.31%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 97        | 4.27%   |
| Intel Wireless 8265 / 8275                                              | 86        | 3.78%   |
| Intel Wireless 7260                                                     | 86        | 3.78%   |
| Intel Wi-Fi 6 AX200                                                     | 83        | 3.65%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 71        | 3.12%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 67        | 2.95%   |
| Intel Wireless 8260                                                     | 65        | 2.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 62        | 2.73%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 60        | 2.64%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 57        | 2.51%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 56        | 2.46%   |
| Intel Wireless 7265                                                     | 51        | 2.24%   |
| Intel Wireless 3160                                                     | 48        | 2.11%   |
| Intel Wi-Fi 6 AX201                                                     | 45        | 1.98%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 41        | 1.8%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 40        | 1.76%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 38        | 1.67%   |
| Intel Wireless 3165                                                     | 38        | 1.67%   |
| Intel WiFi Link 5100                                                    | 38        | 1.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 37        | 1.63%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 37        | 1.63%   |
| Intel Centrino Ultimate-N 6300                                          | 37        | 1.63%   |
| Broadcom BCM43142 802.11b/g/n                                           | 36        | 1.58%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 33        | 1.45%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 30        | 1.32%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 30        | 1.32%   |
| Intel Centrino Advanced-N 6200                                          | 28        | 1.23%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 27        | 1.19%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 27        | 1.19%   |
| Intel Centrino Advanced-N 6235                                          | 26        | 1.14%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 25        | 1.1%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 23        | 1.01%   |
| Intel Centrino Wireless-N 2230                                          | 23        | 1.01%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 18        | 0.79%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 16        | 0.7%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 16        | 0.7%    |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 16        | 0.7%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 15        | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 917       | 46.2%   |
| Intel                            | 553       | 27.86%  |
| Qualcomm Atheros                 | 166       | 8.36%   |
| Broadcom                         | 111       | 5.59%   |
| Marvell Technology Group         | 55        | 2.77%   |
| Broadcom Limited                 | 37        | 1.86%   |
| Huawei Technologies              | 35        | 1.76%   |
| JMicron Technology               | 15        | 0.76%   |
| Samsung Electronics              | 14        | 0.71%   |
| Xiaomi                           | 12        | 0.6%    |
| Lenovo                           | 10        | 0.5%    |
| Silicon Integrated Systems [SiS] | 9         | 0.45%   |
| Nvidia                           | 9         | 0.45%   |
| DisplayLink                      | 8         | 0.4%    |
| ASIX Electronics                 | 8         | 0.4%    |
| Motorola PCS                     | 5         | 0.25%   |
| VIA Technologies                 | 4         | 0.2%    |
| TP-Link                          | 4         | 0.2%    |
| Qualcomm                         | 2         | 0.1%    |
| Hewlett-Packard                  | 2         | 0.1%    |
| Attansic Technology              | 2         | 0.1%    |
| ZTE WCDMA Technologies MSM       | 1         | 0.05%   |
| QinHeng Electronics              | 1         | 0.05%   |
| MediaTek                         | 1         | 0.05%   |
| LG Electronics                   | 1         | 0.05%   |
| ICS Advent                       | 1         | 0.05%   |
| HTC (High Tech Computer)         | 1         | 0.05%   |
| HMD Global                       | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 660       | 33.1%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 198       | 9.93%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 128       | 6.42%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 47        | 2.36%   |
| Intel 82567LM Gigabit Network Connection                          | 47        | 2.36%   |
| Intel Ethernet Connection I218-LM                                 | 39        | 1.96%   |
| Intel 82577LM Gigabit Network Connection                          | 36        | 1.81%   |
| Huawei E353/E3131                                                 | 31        | 1.55%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 30        | 1.5%    |
| Intel Ethernet Connection I217-LM                                 | 29        | 1.45%   |
| Intel Ethernet Connection (6) I219-V                              | 25        | 1.25%   |
| Intel Ethernet Connection (4) I219-LM                             | 24        | 1.2%    |
| Intel Ethernet Connection (3) I218-LM                             | 24        | 1.2%    |
| Intel Ethernet Connection I219-LM                                 | 20        | 1%      |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 19        | 0.95%   |
| Intel Ethernet Connection (7) I219-LM                             | 19        | 0.95%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 18        | 0.9%    |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 18        | 0.9%    |
| Intel Ethernet Connection (4) I219-V                              | 17        | 0.85%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 16        | 0.8%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 16        | 0.8%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 15        | 0.75%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 14        | 0.7%    |
| Intel 82579V Gigabit Network Connection                           | 14        | 0.7%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 13        | 0.65%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 13        | 0.65%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 12        | 0.6%    |
| Intel Ethernet Connection (2) I219-LM                             | 12        | 0.6%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 11        | 0.55%   |
| Intel 82566MM Gigabit Network Connection                          | 11        | 0.55%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 11        | 0.55%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 10        | 0.5%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 10        | 0.5%    |
| Intel Ethernet Connection (5) I219-LM                             | 10        | 0.5%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 10        | 0.5%    |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 10        | 0.5%    |
| Intel Ethernet Connection I219-V                                  | 9         | 0.45%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 8         | 0.4%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 8         | 0.4%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 8         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2130      | 51.67%  |
| Ethernet | 1914      | 46.43%  |
| Modem    | 76        | 1.84%   |
| Unknown  | 2         | 0.05%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1751      | 78%     |
| Ethernet | 494       | 22%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1800      | 83.33%  |
| 1     | 329       | 15.23%  |
| 0     | 23        | 1.06%   |
| 3     | 8         | 0.37%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2051      | 94.17%  |
| Yes  | 127       | 5.83%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 765       | 46.2%   |
| Qualcomm Atheros Communications | 195       | 11.78%  |
| Broadcom                        | 142       | 8.57%   |
| Realtek Semiconductor           | 115       | 6.94%   |
| IMC Networks                    | 73        | 4.41%   |
| Dell                            | 71        | 4.29%   |
| Hewlett-Packard                 | 53        | 3.2%    |
| Lite-On Technology              | 46        | 2.78%   |
| Foxconn / Hon Hai               | 45        | 2.72%   |
| ASUSTek Computer                | 25        | 1.51%   |
| Toshiba                         | 23        | 1.39%   |
| Cambridge Silicon Radio         | 22        | 1.33%   |
| Ralink                          | 16        | 0.97%   |
| Foxconn International           | 14        | 0.85%   |
| Realtek                         | 10        | 0.6%    |
| Apple                           | 9         | 0.54%   |
| Chicony Electronics             | 6         | 0.36%   |
| Taiyo Yuden                     | 5         | 0.3%    |
| Alps Electric                   | 5         | 0.3%    |
| Ralink Technology               | 3         | 0.18%   |
| Integrated System Solution      | 3         | 0.18%   |
| Micro Star International        | 2         | 0.12%   |
| USI                             | 1         | 0.06%   |
| Opticis                         | 1         | 0.06%   |
| MediaTek                        | 1         | 0.06%   |
| Fujitsu                         | 1         | 0.06%   |
| Edimax Technology               | 1         | 0.06%   |
| Creative Technology             | 1         | 0.06%   |
| Askey Computer                  | 1         | 0.06%   |
| AboCom Systems                  | 1         | 0.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 371       | 22.4%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 106       | 6.4%    |
| Intel AX201 Bluetooth                               | 105       | 6.34%   |
| Qualcomm Atheros  Bluetooth Device                  | 83        | 5.01%   |
| Intel AX200 Bluetooth                               | 79        | 4.77%   |
| Realtek Bluetooth Radio                             | 70        | 4.23%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 48        | 2.9%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 47        | 2.84%   |
| Broadcom BCM2045B (BDC-2.1)                         | 35        | 2.11%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 33        | 1.99%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 31        | 1.87%   |
| Realtek  Bluetooth 4.2 Adapter                      | 28        | 1.69%   |
| IMC Networks Bluetooth Radio                        | 25        | 1.51%   |
| Intel Wireless-AC 3168 Bluetooth                    | 23        | 1.39%   |
| Dell BCM20702A0 Bluetooth Module                    | 22        | 1.33%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 22        | 1.33%   |
| HP Broadcom 2070 Bluetooth Combo                    | 19        | 1.15%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 19        | 1.15%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 17        | 1.03%   |
| IMC Networks Bluetooth Device                       | 17        | 1.03%   |
| Dell DW375 Bluetooth Module                         | 17        | 1.03%   |
| Broadcom BCM2070 Bluetooth Device                   | 17        | 1.03%   |
| Ralink RT3290 Bluetooth                             | 16        | 0.97%   |
| Realtek RTL8723B Bluetooth                          | 15        | 0.91%   |
| Lite-On Bluetooth Device                            | 14        | 0.85%   |
| Lite-On Atheros AR3012 Bluetooth                    | 14        | 0.85%   |
| Foxconn International BCM43142A0 Bluetooth module   | 14        | 0.85%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 13        | 0.79%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 12        | 0.72%   |
| Dell Wireless 370 Bluetooth Mini-card               | 11        | 0.66%   |
| Broadcom HP Portable SoftSailing                    | 11        | 0.66%   |
| Toshiba Integrated Bluetooth HCI                    | 10        | 0.6%    |
| Realtek Bluetooth Radio                             | 10        | 0.6%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 10        | 0.6%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 10        | 0.6%    |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 10        | 0.6%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 9         | 0.54%   |
| IMC Networks Wireless_Device                        | 9         | 0.54%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 9         | 0.54%   |
| Foxconn / Hon Hai Bluetooth Device                  | 9         | 0.54%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1809      | 69.05%  |
| AMD                              | 356       | 13.59%  |
| Nvidia                           | 317       | 12.1%   |
| C-Media Electronics              | 14        | 0.53%   |
| Lenovo                           | 12        | 0.46%   |
| Silicon Integrated Systems [SiS] | 11        | 0.42%   |
| Realtek Semiconductor            | 11        | 0.42%   |
| Creative Technology              | 11        | 0.42%   |
| Plantronics                      | 8         | 0.31%   |
| Logitech                         | 8         | 0.31%   |
| VIA Technologies                 | 5         | 0.19%   |
| Texas Instruments                | 5         | 0.19%   |
| GN Netcom                        | 5         | 0.19%   |
| Dell                             | 5         | 0.19%   |
| SteelSeries ApS                  | 4         | 0.15%   |
| Focusrite-Novation               | 4         | 0.15%   |
| Samson Technologies              | 3         | 0.11%   |
| Hewlett-Packard                  | 3         | 0.11%   |
| Sennheiser Communications        | 2         | 0.08%   |
| JMTek                            | 2         | 0.08%   |
| Generalplus Technology           | 2         | 0.08%   |
| DSEA A/S                         | 2         | 0.08%   |
| Yamaha                           | 1         | 0.04%   |
| Silicon Motion                   | 1         | 0.04%   |
| SAVITECH                         | 1         | 0.04%   |
| Razer USA                        | 1         | 0.04%   |
| Native Instruments               | 1         | 0.04%   |
| MCS                              | 1         | 0.04%   |
| Mark of the Unicorn              | 1         | 0.04%   |
| M-Audio                          | 1         | 0.04%   |
| Kingston Technology              | 1         | 0.04%   |
| GYROCOM C&C                      | 1         | 0.04%   |
| FiiO Electronics Technology      | 1         | 0.04%   |
| fifinemicrophone.com             | 1         | 0.04%   |
| Earth Computer Technologies      | 1         | 0.04%   |
| DigiTech                         | 1         | 0.04%   |
| Digidesign                       | 1         | 0.04%   |
| DEXP BK-20                       | 1         | 0.04%   |
| DCMT Technology                  | 1         | 0.04%   |
| Cambridge Silicon Radio          | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 219       | 7.01%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 201       | 6.43%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 178       | 5.69%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 152       | 4.86%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 147       | 4.7%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 118       | 3.77%   |
| Intel 8 Series HD Audio Controller                                                                | 110       | 3.52%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 108       | 3.45%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 101       | 3.23%   |
| Intel Cannon Lake PCH cAVS                                                                        | 97        | 3.1%    |
| Intel Broadwell-U Audio Controller                                                                | 85        | 2.72%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 84        | 2.69%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 82        | 2.62%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 77        | 2.46%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 72        | 2.3%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 66        | 2.11%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 66        | 2.11%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 64        | 2.05%   |
| AMD FCH Azalia Controller                                                                         | 64        | 2.05%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 58        | 1.86%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 58        | 1.86%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 49        | 1.57%   |
| Intel CM238 HD Audio Controller                                                                   | 48        | 1.54%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 44        | 1.41%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 40        | 1.28%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 36        | 1.15%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 35        | 1.12%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 31        | 0.99%   |
| Intel Comet Lake PCH cAVS                                                                         | 27        | 0.86%   |
| AMD Kabini HDMI/DP Audio                                                                          | 25        | 0.8%    |
| Nvidia GT216 HDMI Audio Controller                                                                | 23        | 0.74%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 23        | 0.74%   |
| AMD Wrestler HDMI Audio                                                                           | 21        | 0.67%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 20        | 0.64%   |
| AMD Trinity HDMI Audio Controller                                                                 | 19        | 0.61%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 18        | 0.58%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 17        | 0.54%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 17        | 0.54%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 16        | 0.51%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 14        | 0.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 463       | 28.01%  |
| SK hynix                     | 342       | 20.69%  |
| Kingston                     | 181       | 10.95%  |
| Micron Technology            | 172       | 10.41%  |
| Unknown                      | 135       | 8.17%   |
| Goodram                      | 75        | 4.54%   |
| Crucial                      | 67        | 4.05%   |
| Ramaxel Technology           | 45        | 2.72%   |
| A-DATA Technology            | 37        | 2.24%   |
| Nanya Technology             | 31        | 1.88%   |
| Elpida                       | 29        | 1.75%   |
| Patriot                      | 13        | 0.79%   |
| Qimonda                      | 10        | 0.6%    |
| ASint Technology             | 7         | 0.42%   |
| Unknown                      | 7         | 0.42%   |
| Unknown (ABCD)               | 6         | 0.36%   |
| Corsair                      | 6         | 0.36%   |
| Wilk                         | 5         | 0.3%    |
| Unifosa                      | 3         | 0.18%   |
| G.Skill                      | 3         | 0.18%   |
| 48spaces                     | 3         | 0.18%   |
| Toshiba                      | 2         | 0.12%   |
| Unknown (8A02)               | 1         | 0.06%   |
| Swissbit                     | 1         | 0.06%   |
| Smart                        | 1         | 0.06%   |
| SHARETRONIC                  | 1         | 0.06%   |
| PNY                          | 1         | 0.06%   |
| Patriot Memory (PDP Systems) | 1         | 0.06%   |
| Goldkey                      | 1         | 0.06%   |
| fef5                         | 1         | 0.06%   |
| Apacer                       | 1         | 0.06%   |
| 430112204340C940             | 1         | 0.06%   |
| 430112174392063E             | 1         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s      | 31        | 1.75%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                 | 23        | 1.3%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s      | 23        | 1.3%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s     | 22        | 1.24%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s  | 21        | 1.18%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s  | 20        | 1.13%   |
| GOODRAM RAM GR2666S464L19/16G 16384MB SODIMM DDR4 2667MT/s | 19        | 1.07%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s      | 18        | 1.01%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s      | 17        | 0.96%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s      | 17        | 0.96%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s      | 17        | 0.96%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s      | 16        | 0.9%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s     | 15        | 0.85%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 14        | 0.79%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s      | 13        | 0.73%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s      | 12        | 0.68%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 12        | 0.68%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s      | 12        | 0.68%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s     | 12        | 0.68%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s      | 12        | 0.68%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s      | 12        | 0.68%   |
| Kingston RAM KHX2400C14S4/16G 16GB SODIMM DDR4 2667MT/s    | 12        | 0.68%   |
| GOODRAM RAM GR3200S464L22/16G 16384MB SODIMM DDR4 3200MT/s | 12        | 0.68%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s      | 11        | 0.62%   |
| Samsung RAM M471B5673FH0-CF8 2048MB SODIMM DDR3 1067MT/s   | 11        | 0.62%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s      | 11        | 0.62%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s     | 10        | 0.56%   |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s   | 10        | 0.56%   |
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 8400MT/s  | 10        | 0.56%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s      | 10        | 0.56%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s    | 10        | 0.56%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s     | 9         | 0.51%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s      | 9         | 0.51%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s   | 9         | 0.51%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s     | 9         | 0.51%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB SODIMM DDR4 3200MT/s    | 9         | 0.51%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s    | 9         | 0.51%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s    | 9         | 0.51%   |
| Unknown RAM Module 2GB SODIMM DDR2 533MT/s                 | 8         | 0.45%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                 | 8         | 0.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 543       | 40.16%  |
| DDR4    | 511       | 37.8%   |
| DDR2    | 142       | 10.5%   |
| SDRAM   | 59        | 4.36%   |
| LPDDR4  | 38        | 2.81%   |
| LPDDR3  | 29        | 2.14%   |
| DDR     | 10        | 0.74%   |
| Unknown | 10        | 0.74%   |
| DRAM    | 5         | 0.37%   |
| DDR5    | 4         | 0.3%    |
| LPDDR5  | 1         | 0.07%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1251      | 93.92%  |
| Row Of Chips | 60        | 4.5%    |
| Chip         | 9         | 0.68%   |
| DIMM         | 7         | 0.53%   |
| Unknown      | 5         | 0.38%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Notebooks | Percent |
|---------|-----------|---------|
| 4096    | 468       | 31.39%  |
| 8192    | 427       | 28.64%  |
| 2048    | 259       | 17.37%  |
| 16384   | 205       | 13.75%  |
| 1024    | 95        | 6.37%   |
| 32768   | 22        | 1.48%   |
| 512     | 9         | 0.6%    |
| Unknown | 4         | 0.27%   |
| 1536    | 1         | 0.07%   |
| 256     | 1         | 0.07%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 393       | 26.25%  |
| 2667    | 277       | 18.5%   |
| 3200    | 170       | 11.36%  |
| 1334    | 98        | 6.55%   |
| 2400    | 80        | 5.34%   |
| 667     | 70        | 4.68%   |
| 2133    | 68        | 4.54%   |
| 1333    | 61        | 4.07%   |
| Unknown | 47        | 3.14%   |
| 1067    | 33        | 2.2%    |
| 4199    | 31        | 2.07%   |
| 800     | 26        | 1.74%   |
| 2048    | 22        | 1.47%   |
| 975     | 22        | 1.47%   |
| 533     | 22        | 1.47%   |
| 4267    | 13        | 0.87%   |
| 3266    | 11        | 0.73%   |
| 8400    | 10        | 0.67%   |
| 1867    | 10        | 0.67%   |
| 1066    | 8         | 0.53%   |
| 4800    | 5         | 0.33%   |
| 4266    | 4         | 0.27%   |
| 400     | 4         | 0.27%   |
| 333     | 4         | 0.27%   |
| 3733    | 2         | 0.13%   |
| 6400    | 1         | 0.07%   |
| 2933    | 1         | 0.07%   |
| 2134    | 1         | 0.07%   |
| 1776    | 1         | 0.07%   |
| 1639    | 1         | 0.07%   |
| 933     | 1         | 0.07%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 10        | 50%     |
| Samsung Electronics | 3         | 15%     |
| Seiko Epson         | 2         | 10%     |
| Canon               | 2         | 10%     |
| Zebra               | 1         | 5%      |
| Xerox               | 1         | 5%      |
| Brother Industries  | 1         | 5%      |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| HP Deskjet F2280 series                 | 2         | 10%     |
| Zebra ZTC GX420t                        | 1         | 5%      |
| Xerox Phaser 6000B                      | 1         | 5%      |
| Seiko Epson L395 Series                 | 1         | 5%      |
| Seiko Epson AL-M310DN                   | 1         | 5%      |
| Samsung Xerox Phaser 3117 Laser Printer | 1         | 5%      |
| Samsung SCX-6545 Series                 | 1         | 5%      |
| Samsung M2020 Series                    | 1         | 5%      |
| HP LaserJet P1102                       | 1         | 5%      |
| HP LaserJet P1005                       | 1         | 5%      |
| HP LaserJet 1020                        | 1         | 5%      |
| HP LaserJet 1018                        | 1         | 5%      |
| HP Ink Tank Wireless 410 series         | 1         | 5%      |
| HP Deskjet Ink Advant K209a-z           | 1         | 5%      |
| HP Deskjet D1500 series                 | 1         | 5%      |
| HP Deskjet 2540 series                  | 1         | 5%      |
| Canon PIXMA MG3000 series               | 1         | 5%      |
| Canon MG5600 series                     | 1         | 5%      |
| Brother DCP-1610W                       | 1         | 5%      |

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
| Chicony Electronics                    | 454       | 24.74%  |
| IMC Networks                           | 203       | 11.06%  |
| Microdia                               | 190       | 10.35%  |
| Realtek Semiconductor                  | 172       | 9.37%   |
| Acer                                   | 141       | 7.68%   |
| Sunplus Innovation Technology          | 104       | 5.67%   |
| Suyin                                  | 88        | 4.8%    |
| Quanta                                 | 81        | 4.41%   |
| Cheng Uei Precision Industry (Foxlink) | 68        | 3.71%   |
| Syntek                                 | 57        | 3.11%   |
| Silicon Motion                         | 43        | 2.34%   |
| Lite-On Technology                     | 38        | 2.07%   |
| Ricoh                                  | 25        | 1.36%   |
| Lenovo                                 | 21        | 1.14%   |
| Alcor Micro                            | 20        | 1.09%   |
| Luxvisions Innotech Limited            | 17        | 0.93%   |
| Logitech                               | 14        | 0.76%   |
| Apple                                  | 12        | 0.65%   |
| DigiTech                               | 11        | 0.6%    |
| Z-Star Microelectronics                | 10        | 0.54%   |
| Primax Electronics                     | 9         | 0.49%   |
| Creative Technology                    | 9         | 0.49%   |
| ALi                                    | 7         | 0.38%   |
| Intel                                  | 6         | 0.33%   |
| Samsung Electronics                    | 4         | 0.22%   |
| Microsoft                              | 4         | 0.22%   |
| Generalplus Technology                 | 4         | 0.22%   |
| Importek                               | 3         | 0.16%   |
| Sunplus Technology                     | 2         | 0.11%   |
| Sonix Technology                       | 2         | 0.11%   |
| OmniVision Technologies                | 2         | 0.11%   |
| Foxconn / Hon Hai                      | 2         | 0.11%   |
| Cubeternet                             | 2         | 0.11%   |
| Trust                                  | 1         | 0.05%   |
| Nokia Mobile Phones                    | 1         | 0.05%   |
| Nebraska Furniture Mart                | 1         | 0.05%   |
| Mustek Systems                         | 1         | 0.05%   |
| MacroSilicon                           | 1         | 0.05%   |
| LG Electronics                         | 1         | 0.05%   |
| kingcome                               | 1         | 0.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 90        | 4.89%   |
| Microdia Integrated_Webcam_HD            | 67        | 3.64%   |
| Realtek Integrated_Webcam_HD             | 58        | 3.15%   |
| IMC Networks Integrated Camera           | 53        | 2.88%   |
| IMC Networks USB2.0 HD UVC WebCam        | 50        | 2.72%   |
| Sunplus Integrated_Webcam_HD             | 44        | 2.39%   |
| Chicony Lenovo EasyCamera                | 39        | 2.12%   |
| Acer Lenovo EasyCamera                   | 34        | 1.85%   |
| Chicony HD WebCam                        | 31        | 1.68%   |
| Suyin Integrated_Webcam_HD               | 30        | 1.63%   |
| Microdia Integrated Webcam               | 29        | 1.58%   |
| Syntek Lenovo EasyCamera                 | 26        | 1.41%   |
| Realtek Lenovo EasyCamera                | 25        | 1.36%   |
| Acer Integrated Camera                   | 24        | 1.3%    |
| Realtek USB Camera                       | 19        | 1.03%   |
| Quanta HP TrueVision HD Camera           | 19        | 1.03%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 19        | 1.03%   |
| Chicony USB2.0 HD UVC WebCam             | 19        | 1.03%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 18        | 0.98%   |
| Lite-On Integrated Camera                | 18        | 0.98%   |
| Acer Lenovo Integrated Webcam            | 18        | 0.98%   |
| Realtek Integrated Webcam HD             | 16        | 0.87%   |
| Syntek Integrated Camera                 | 15        | 0.81%   |
| Quanta HD User Facing                    | 15        | 0.81%   |
| Microdia Laptop_Integrated_Webcam_HD     | 15        | 0.81%   |
| IMC Networks Integrated Webcam           | 15        | 0.81%   |
| Chicony USB 2.0 Camera                   | 15        | 0.81%   |
| Chicony USB2.0 VGA UVC WebCam            | 14        | 0.76%   |
| Chicony HP HD Camera                     | 14        | 0.76%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 13        | 0.71%   |
| Acer SunplusIT Integrated Camera         | 13        | 0.71%   |
| Realtek Integrated Webcam                | 12        | 0.65%   |
| Chicony HP HD Webcam [Fixed]             | 12        | 0.65%   |
| Chicony Integrated Camera (1280x720@30)  | 11        | 0.6%    |
| Sunplus HD WebCam                        | 10        | 0.54%   |
| Silicon Motion WebCam SC-13HDL11939N     | 10        | 0.54%   |
| Quanta HP Webcam                         | 10        | 0.54%   |
| Lenovo Integrated Webcam                 | 10        | 0.54%   |
| Acer EasyCamera                          | 10        | 0.54%   |
| Microdia Sonix USB 2.0 Camera            | 9         | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 146       | 37.63%  |
| Synaptics                  | 86        | 22.16%  |
| AuthenTec                  | 51        | 13.14%  |
| Shenzhen Goodix Technology | 40        | 10.31%  |
| Upek                       | 30        | 7.73%   |
| LighTuning Technology      | 15        | 3.87%   |
| STMicroelectronics         | 12        | 3.09%   |
| Elan Microelectronics      | 8         | 2.06%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 33        | 8.51%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 30        | 7.73%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 29        | 7.47%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 22        | 5.67%   |
| Shenzhen Goodix  FingerPrint Device                                        | 22        | 5.67%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 20        | 5.15%   |
| AuthenTec AES2810                                                          | 20        | 5.15%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 18        | 4.64%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 17        | 4.38%   |
| Shenzhen Goodix Fingerprint Reader                                         | 14        | 3.61%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 13        | 3.35%   |
| STMicroelectronics Fingerprint Reader                                      | 12        | 3.09%   |
| Validity Sensors VFS491                                                    | 11        | 2.84%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 11        | 2.84%   |
| Unknown                                                                    | 11        | 2.84%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 8         | 2.06%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 8         | 2.06%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 1.55%   |
| Validity Sensors Fingerprint scanner                                       | 6         | 1.55%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 6         | 1.55%   |
| Elan ELAN:Fingerprint                                                      | 6         | 1.55%   |
| AuthenTec AES1600                                                          | 6         | 1.55%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 1.29%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 1.29%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 1.03%   |
| Validity Sensors VFS Fingerprint sensor                                    | 4         | 1.03%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 4         | 1.03%   |
| Shenzhen Goodix FingerPrint                                                | 4         | 1.03%   |
| LighTuning Fingerprint Reader                                              | 4         | 1.03%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 1.03%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 0.77%   |
| Synaptics WBDI Device                                                      | 3         | 0.77%   |
| Synaptics  WBDI                                                            | 3         | 0.77%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 0.77%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.77%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.52%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 0.52%   |
| Elan ELAN:ARM-M4                                                           | 2         | 0.52%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.26%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.26%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 166       | 56.66%  |
| Alcor Micro               | 55        | 18.77%  |
| O2 Micro                  | 36        | 12.29%  |
| Lenovo                    | 17        | 5.8%    |
| Upek                      | 14        | 4.78%   |
| Gemalto (was Gemplus)     | 4         | 1.37%   |
| Aladdin Knowledge Systems | 1         | 0.34%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 57        | 19.45%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 53        | 18.09%  |
| Broadcom 5880                                                                | 42        | 14.33%  |
| Broadcom 58200                                                               | 35        | 11.95%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 31        | 10.58%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 29        | 9.9%    |
| Lenovo Integrated Smart Card Reader                                          | 17        | 5.8%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 14        | 4.78%   |
| O2 Micro Oz776 SmartCard Reader                                              | 7         | 2.39%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 1.02%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.34%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.34%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.34%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.34%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.34%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1298      | 58.81%  |
| 1     | 717       | 32.49%  |
| 2     | 164       | 7.43%   |
| 3     | 21        | 0.95%   |
| 7     | 2         | 0.09%   |
| 5     | 2         | 0.09%   |
| 4     | 2         | 0.09%   |
| 6     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 383       | 34.69%  |
| Chipcard                 | 270       | 24.46%  |
| Graphics card            | 203       | 18.39%  |
| Net/wireless             | 63        | 5.71%   |
| Storage                  | 39        | 3.53%   |
| Bluetooth                | 32        | 2.9%    |
| Multimedia controller    | 31        | 2.81%   |
| Communication controller | 19        | 1.72%   |
| Camera                   | 15        | 1.36%   |
| Card reader              | 14        | 1.27%   |
| Sound                    | 10        | 0.91%   |
| Modem                    | 6         | 0.54%   |
| Firewire controller      | 5         | 0.45%   |
| Net/ethernet             | 4         | 0.36%   |
| Flash memory             | 3         | 0.27%   |
| Dvb card                 | 3         | 0.27%   |
| Wireless                 | 1         | 0.09%   |
| Tv card                  | 1         | 0.09%   |
| Storage/raid             | 1         | 0.09%   |
| Network                  | 1         | 0.09%   |

