Linux in Poland - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Poland.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Poland/Desktop/README.md) and [notebooks](/Location/Poland/Notebook/README.md).

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

Total: 5866

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Acer          | Aspire 4733Z                | Notebook    | [4be4debbe5](https://linux-hardware.org/?probe=4be4debbe5) | Oct 01, 2022 |
| Lenovo        | ThinkPad SL500 27463ZG      | Notebook    | [34006e3b46](https://linux-hardware.org/?probe=34006e3b46) | Oct 01, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [aee33639b9](https://linux-hardware.org/?probe=aee33639b9) | Oct 01, 2022 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [bc6bcfe3f2](https://linux-hardware.org/?probe=bc6bcfe3f2) | Oct 01, 2022 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [2d1e938e68](https://linux-hardware.org/?probe=2d1e938e68) | Oct 01, 2022 |
| Acer          | Aspire A715-74G             | Notebook    | [17abc08754](https://linux-hardware.org/?probe=17abc08754) | Sep 30, 2022 |
| HP            | Pavilion Laptop 17-ar0xx    | Notebook    | [733654d30d](https://linux-hardware.org/?probe=733654d30d) | Sep 30, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [fcf7e031e3](https://linux-hardware.org/?probe=fcf7e031e3) | Sep 30, 2022 |
| Dell          | 0KJCC5 A00                  | Desktop     | [f9582eb0a8](https://linux-hardware.org/?probe=f9582eb0a8) | Sep 29, 2022 |
| Lenovo        | G500s 20245                 | Notebook    | [b9001f7817](https://linux-hardware.org/?probe=b9001f7817) | Sep 29, 2022 |
| HP            | ZBook Firefly 15.6 inch ... | Notebook    | [be74c01cca](https://linux-hardware.org/?probe=be74c01cca) | Sep 29, 2022 |
| Dell          | Latitude E6330              | Notebook    | [b075fbcb56](https://linux-hardware.org/?probe=b075fbcb56) | Sep 29, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [82528435d8](https://linux-hardware.org/?probe=82528435d8) | Sep 29, 2022 |
| MSI           | Creator Z17 A12UHST         | Notebook    | [4b9249b9b0](https://linux-hardware.org/?probe=4b9249b9b0) | Sep 29, 2022 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [d23d86be40](https://linux-hardware.org/?probe=d23d86be40) | Sep 28, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [a42a4722f7](https://linux-hardware.org/?probe=a42a4722f7) | Sep 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [bdc84f1b9b](https://linux-hardware.org/?probe=bdc84f1b9b) | Sep 28, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [1bdf72d415](https://linux-hardware.org/?probe=1bdf72d415) | Sep 27, 2022 |
| ASUSTek       | Zenbook UM5401QA_UM5401Q... | Notebook    | [04fbd64661](https://linux-hardware.org/?probe=04fbd64661) | Sep 27, 2022 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [f35f96af50](https://linux-hardware.org/?probe=f35f96af50) | Sep 27, 2022 |
| Dell          | Precision 3561              | Notebook    | [77a4030052](https://linux-hardware.org/?probe=77a4030052) | Sep 27, 2022 |
| Dell          | 0DC48C A02                  | Desktop     | [9292e820c5](https://linux-hardware.org/?probe=9292e820c5) | Sep 27, 2022 |
| Toshiba       | Satellite C850-1LK          | Notebook    | [f0240dcb2d](https://linux-hardware.org/?probe=f0240dcb2d) | Sep 27, 2022 |
| Lenovo        | ThinkPad SL500 27463ZG      | Notebook    | [70860ec433](https://linux-hardware.org/?probe=70860ec433) | Sep 26, 2022 |
| HP            | 805D                        | Desktop     | [b023737f63](https://linux-hardware.org/?probe=b023737f63) | Sep 26, 2022 |
| Lenovo        | ThinkPad Edge E430 3254A... | Notebook    | [cb5f6f279b](https://linux-hardware.org/?probe=cb5f6f279b) | Sep 26, 2022 |
| Lenovo        | ThinkPad Edge E430 3254A... | Notebook    | [3f11c520e0](https://linux-hardware.org/?probe=3f11c520e0) | Sep 26, 2022 |
| HP            | ZBook 15 G6                 | Notebook    | [476623a6a1](https://linux-hardware.org/?probe=476623a6a1) | Sep 26, 2022 |
| Dell          | Latitude 3190               | Notebook    | [27ac75e10c](https://linux-hardware.org/?probe=27ac75e10c) | Sep 26, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [6d3f575c3d](https://linux-hardware.org/?probe=6d3f575c3d) | Sep 26, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [c447921f07](https://linux-hardware.org/?probe=c447921f07) | Sep 25, 2022 |
| Valve         | Jupiter                     | Notebook    | [ebf3e70cf7](https://linux-hardware.org/?probe=ebf3e70cf7) | Sep 25, 2022 |
| Acer          | P5WE0                       | Notebook    | [124f7bdd77](https://linux-hardware.org/?probe=124f7bdd77) | Sep 25, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [d9f9db839d](https://linux-hardware.org/?probe=d9f9db839d) | Sep 25, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [8de01689b6](https://linux-hardware.org/?probe=8de01689b6) | Sep 24, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [dafafa97a4](https://linux-hardware.org/?probe=dafafa97a4) | Sep 24, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [89a1a3179d](https://linux-hardware.org/?probe=89a1a3179d) | Sep 24, 2022 |
| Toshiba       | Satellite P205              | Notebook    | [2a1450578e](https://linux-hardware.org/?probe=2a1450578e) | Sep 23, 2022 |
| Fujitsu       | LIFEBOOK S760               | Notebook    | [ceda61113a](https://linux-hardware.org/?probe=ceda61113a) | Sep 23, 2022 |
| Toshiba       | Satellite P205              | Notebook    | [98e97d946a](https://linux-hardware.org/?probe=98e97d946a) | Sep 23, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [36c369745a](https://linux-hardware.org/?probe=36c369745a) | Sep 23, 2022 |
| HP            | 3032h                       | Desktop     | [efb6671159](https://linux-hardware.org/?probe=efb6671159) | Sep 23, 2022 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | Notebook    | [17ff3f8067](https://linux-hardware.org/?probe=17ff3f8067) | Sep 22, 2022 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | Notebook    | [0121aac33a](https://linux-hardware.org/?probe=0121aac33a) | Sep 22, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [de7c138e21](https://linux-hardware.org/?probe=de7c138e21) | Sep 22, 2022 |
| MSI           | 760GM-P34                   | Desktop     | [af750add66](https://linux-hardware.org/?probe=af750add66) | Sep 22, 2022 |
| MSI           | Creator Z17 A12UHST         | Notebook    | [06c854fd7b](https://linux-hardware.org/?probe=06c854fd7b) | Sep 22, 2022 |
| MSI           | H81M-P33                    | Desktop     | [05d5a24774](https://linux-hardware.org/?probe=05d5a24774) | Sep 22, 2022 |
| Lenovo        | G505s 20255                 | Notebook    | [671c1cb6c4](https://linux-hardware.org/?probe=671c1cb6c4) | Sep 21, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [967110ef60](https://linux-hardware.org/?probe=967110ef60) | Sep 21, 2022 |
| MSI           | Z370 GAMING PRO CARBON      | Desktop     | [978c6dd9dd](https://linux-hardware.org/?probe=978c6dd9dd) | Sep 21, 2022 |
| Xunlong       | Orange Pi Zero              | Soc         | [0aa622cc13](https://linux-hardware.org/?probe=0aa622cc13) | Sep 21, 2022 |
| Dell          | 0D883F A06                  | Desktop     | [01c50a7a4c](https://linux-hardware.org/?probe=01c50a7a4c) | Sep 21, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [d22f082243](https://linux-hardware.org/?probe=d22f082243) | Sep 21, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [e4f1a8245a](https://linux-hardware.org/?probe=e4f1a8245a) | Sep 21, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [bdb353fd2c](https://linux-hardware.org/?probe=bdb353fd2c) | Sep 20, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [030ce84327](https://linux-hardware.org/?probe=030ce84327) | Sep 20, 2022 |
| Framework     | Laptop                      | Notebook    | [dd163cfa96](https://linux-hardware.org/?probe=dd163cfa96) | Sep 20, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [21c74278f8](https://linux-hardware.org/?probe=21c74278f8) | Sep 20, 2022 |
| Dell          | Latitude E4310              | Notebook    | [c77a454d4e](https://linux-hardware.org/?probe=c77a454d4e) | Sep 20, 2022 |
| Dell          | Latitude E4310              | Notebook    | [4e8bf046d8](https://linux-hardware.org/?probe=4e8bf046d8) | Sep 19, 2022 |
| Apple         | MacBook9,1                  | Notebook    | [e6898c8aa0](https://linux-hardware.org/?probe=e6898c8aa0) | Sep 19, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [85952e171d](https://linux-hardware.org/?probe=85952e171d) | Sep 19, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [eb67db5bff](https://linux-hardware.org/?probe=eb67db5bff) | Sep 19, 2022 |
| Lenovo        | ThinkPad T420 4180MY7       | Notebook    | [e6a930e933](https://linux-hardware.org/?probe=e6a930e933) | Sep 19, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [793fa18b58](https://linux-hardware.org/?probe=793fa18b58) | Sep 19, 2022 |
| ASUSTek       | GL502VSK                    | Notebook    | [a6dc9b627f](https://linux-hardware.org/?probe=a6dc9b627f) | Sep 19, 2022 |
| Toshiba       | PORTEGE Z30-A               | Notebook    | [419bf72e22](https://linux-hardware.org/?probe=419bf72e22) | Sep 19, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [1f2bd2202c](https://linux-hardware.org/?probe=1f2bd2202c) | Sep 19, 2022 |
| Dell          | Latitude 3190               | Notebook    | [f96d782326](https://linux-hardware.org/?probe=f96d782326) | Sep 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [52352bab7a](https://linux-hardware.org/?probe=52352bab7a) | Sep 19, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [eb1c0556c3](https://linux-hardware.org/?probe=eb1c0556c3) | Sep 19, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [5a9ab0de04](https://linux-hardware.org/?probe=5a9ab0de04) | Sep 18, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [b3cb8fc82e](https://linux-hardware.org/?probe=b3cb8fc82e) | Sep 18, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [e903dccaf1](https://linux-hardware.org/?probe=e903dccaf1) | Sep 18, 2022 |
| Gigabyte      | B560M D3H                   | Desktop     | [515d75e6b7](https://linux-hardware.org/?probe=515d75e6b7) | Sep 17, 2022 |
| HP            | Notebook                    | Notebook    | [d29681d2ed](https://linux-hardware.org/?probe=d29681d2ed) | Sep 17, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [9c23c7bb58](https://linux-hardware.org/?probe=9c23c7bb58) | Sep 17, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [5023f912e2](https://linux-hardware.org/?probe=5023f912e2) | Sep 16, 2022 |
| Lenovo        | ThinkPad T420 4180A32       | Notebook    | [44841341fd](https://linux-hardware.org/?probe=44841341fd) | Sep 16, 2022 |
| Dell          | Latitude 5511               | Notebook    | [9a2faa8d22](https://linux-hardware.org/?probe=9a2faa8d22) | Sep 16, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [b15d9e1fe4](https://linux-hardware.org/?probe=b15d9e1fe4) | Sep 16, 2022 |
| Pine Micro... | Pine64 Rock64               | Soc         | [dbd6ac01d6](https://linux-hardware.org/?probe=dbd6ac01d6) | Sep 16, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZX... | Notebook    | [099e5d3523](https://linux-hardware.org/?probe=099e5d3523) | Sep 16, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [fcdfa43a37](https://linux-hardware.org/?probe=fcdfa43a37) | Sep 15, 2022 |
| AMI           | Cherry Trail CR             | Desktop     | [1c131a1acb](https://linux-hardware.org/?probe=1c131a1acb) | Sep 15, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [f12132c99f](https://linux-hardware.org/?probe=f12132c99f) | Sep 14, 2022 |
| Dell          | Inspiron 5584               | Notebook    | [677d683644](https://linux-hardware.org/?probe=677d683644) | Sep 14, 2022 |
| Dell          | Latitude 5521               | Notebook    | [c342e3ab13](https://linux-hardware.org/?probe=c342e3ab13) | Sep 14, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [98ae2af06f](https://linux-hardware.org/?probe=98ae2af06f) | Sep 14, 2022 |
| Sun Micros... | ASSY,MOTHERBOARD,X4170 5... | Server      | [ea845ec5ea](https://linux-hardware.org/?probe=ea845ec5ea) | Sep 13, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [19eb66af9e](https://linux-hardware.org/?probe=19eb66af9e) | Sep 13, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [f06aa45765](https://linux-hardware.org/?probe=f06aa45765) | Sep 13, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [edbc81cc67](https://linux-hardware.org/?probe=edbc81cc67) | Sep 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [efc31007ac](https://linux-hardware.org/?probe=efc31007ac) | Sep 12, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [225bd59ba7](https://linux-hardware.org/?probe=225bd59ba7) | Sep 12, 2022 |
| Dell          | Latitude 3190               | Notebook    | [3c0abb17a9](https://linux-hardware.org/?probe=3c0abb17a9) | Sep 12, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [ed5273b278](https://linux-hardware.org/?probe=ed5273b278) | Sep 11, 2022 |
| Gigabyte      | G41MT-ES2L                  | Desktop     | [74ee0e38a3](https://linux-hardware.org/?probe=74ee0e38a3) | Sep 11, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [0c536307da](https://linux-hardware.org/?probe=0c536307da) | Sep 11, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [eff4400b7d](https://linux-hardware.org/?probe=eff4400b7d) | Sep 10, 2022 |
| Dell          | 01TKCC A01                  | Desktop     | [6d032338c0](https://linux-hardware.org/?probe=6d032338c0) | Sep 10, 2022 |
| Lenovo        | ThinkPad L420 7829H86       | Notebook    | [406535e915](https://linux-hardware.org/?probe=406535e915) | Sep 10, 2022 |
| Acer          | Nitro AN517-55              | Notebook    | [16fa00177a](https://linux-hardware.org/?probe=16fa00177a) | Sep 10, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [6248f4732d](https://linux-hardware.org/?probe=6248f4732d) | Sep 10, 2022 |
| Toshiba       | Satellite L40               | Notebook    | [ef6556670c](https://linux-hardware.org/?probe=ef6556670c) | Sep 09, 2022 |
| Dell          | Latitude E6330              | Notebook    | [9f2183ce75](https://linux-hardware.org/?probe=9f2183ce75) | Sep 09, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [90973f12a8](https://linux-hardware.org/?probe=90973f12a8) | Sep 08, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [c2f25bcea8](https://linux-hardware.org/?probe=c2f25bcea8) | Sep 08, 2022 |
| Gigabyte      | AORUS 15G XC                | Notebook    | [ea131dfe2c](https://linux-hardware.org/?probe=ea131dfe2c) | Sep 08, 2022 |
| Dell          | Latitude E6540              | Notebook    | [5700f37281](https://linux-hardware.org/?probe=5700f37281) | Sep 08, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [6812b52b92](https://linux-hardware.org/?probe=6812b52b92) | Sep 08, 2022 |
| Dell          | Inspiron 3541               | Notebook    | [2cc868e8f0](https://linux-hardware.org/?probe=2cc868e8f0) | Sep 08, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [bb2d82813c](https://linux-hardware.org/?probe=bb2d82813c) | Sep 08, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [e757b79169](https://linux-hardware.org/?probe=e757b79169) | Sep 08, 2022 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | Notebook    | [6ee5358914](https://linux-hardware.org/?probe=6ee5358914) | Sep 08, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | Notebook    | [63524aa492](https://linux-hardware.org/?probe=63524aa492) | Sep 07, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [5cf26fac4d](https://linux-hardware.org/?probe=5cf26fac4d) | Sep 07, 2022 |
| HP            | 1497                        | Desktop     | [3cf8f5d97a](https://linux-hardware.org/?probe=3cf8f5d97a) | Sep 07, 2022 |
| Samsung       | RC420/RC520/RC720           | Notebook    | [a6b07acfe5](https://linux-hardware.org/?probe=a6b07acfe5) | Sep 07, 2022 |
| Dell          | 0DR845                      | Desktop     | [f945fc3f5e](https://linux-hardware.org/?probe=f945fc3f5e) | Sep 07, 2022 |
| Lenovo        | 36D9 SDK0J40700 WIN 3258... | Desktop     | [a816f4f60b](https://linux-hardware.org/?probe=a816f4f60b) | Sep 07, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [4adadf9e6a](https://linux-hardware.org/?probe=4adadf9e6a) | Sep 06, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [4615004e85](https://linux-hardware.org/?probe=4615004e85) | Sep 06, 2022 |
| MSI           | MEG X570 ACE                | Desktop     | [5f7f592f25](https://linux-hardware.org/?probe=5f7f592f25) | Sep 05, 2022 |
| MSI           | B85M-E43 DASH               | Desktop     | [f52a53f4a7](https://linux-hardware.org/?probe=f52a53f4a7) | Sep 05, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [e0bb6ae251](https://linux-hardware.org/?probe=e0bb6ae251) | Sep 05, 2022 |
| Dell          | Latitude 3190               | Notebook    | [25c70ea2f3](https://linux-hardware.org/?probe=25c70ea2f3) | Sep 05, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [1d90e3b685](https://linux-hardware.org/?probe=1d90e3b685) | Sep 05, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [d802875fec](https://linux-hardware.org/?probe=d802875fec) | Sep 04, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [96d17dc188](https://linux-hardware.org/?probe=96d17dc188) | Sep 04, 2022 |
| Dell          | Latitude E6330              | Notebook    | [e4dcf51a84](https://linux-hardware.org/?probe=e4dcf51a84) | Sep 04, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [4f45b8e600](https://linux-hardware.org/?probe=4f45b8e600) | Sep 04, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [87a6f9162a](https://linux-hardware.org/?probe=87a6f9162a) | Sep 03, 2022 |
| HP            | 620                         | Notebook    | [096486e01d](https://linux-hardware.org/?probe=096486e01d) | Sep 03, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [6b62abaaaf](https://linux-hardware.org/?probe=6b62abaaaf) | Sep 03, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [ec466abbf7](https://linux-hardware.org/?probe=ec466abbf7) | Sep 03, 2022 |
| Dell          | Latitude E6330              | Notebook    | [626c1e28b1](https://linux-hardware.org/?probe=626c1e28b1) | Sep 03, 2022 |
| Dell          | Latitude E6330              | Notebook    | [6c7adba5b6](https://linux-hardware.org/?probe=6c7adba5b6) | Sep 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [6669ffa68e](https://linux-hardware.org/?probe=6669ffa68e) | Sep 02, 2022 |
| Dell          | Latitude E6220              | Notebook    | [e249853663](https://linux-hardware.org/?probe=e249853663) | Sep 02, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [8320ded55c](https://linux-hardware.org/?probe=8320ded55c) | Sep 02, 2022 |
| MSI           | B450 GAMING PLUS            | Desktop     | [3561723d92](https://linux-hardware.org/?probe=3561723d92) | Sep 02, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [5d85db2c66](https://linux-hardware.org/?probe=5d85db2c66) | Sep 02, 2022 |
| Valve         | Jupiter                     | Notebook    | [ad3ce497e7](https://linux-hardware.org/?probe=ad3ce497e7) | Sep 02, 2022 |
| MSI           | Creator Z17 A12UHST         | Notebook    | [3071865e76](https://linux-hardware.org/?probe=3071865e76) | Sep 02, 2022 |
| Dell          | Latitude E6220              | Notebook    | [99c8b865ad](https://linux-hardware.org/?probe=99c8b865ad) | Sep 02, 2022 |
| Dell          | Latitude E6330              | Notebook    | [179123f301](https://linux-hardware.org/?probe=179123f301) | Sep 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [21392e76a8](https://linux-hardware.org/?probe=21392e76a8) | Sep 01, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [12abd434b5](https://linux-hardware.org/?probe=12abd434b5) | Sep 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [e16313490d](https://linux-hardware.org/?probe=e16313490d) | Sep 01, 2022 |
| Dell          | 042P49 A00                  | Desktop     | [31efc1e75f](https://linux-hardware.org/?probe=31efc1e75f) | Sep 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [60db4bfa03](https://linux-hardware.org/?probe=60db4bfa03) | Aug 31, 2022 |
| ASUSTek       | P5K/EPU                     | Desktop     | [196d56922a](https://linux-hardware.org/?probe=196d56922a) | Aug 31, 2022 |
| Dell          | Latitude E6330              | Notebook    | [b5766d41fa](https://linux-hardware.org/?probe=b5766d41fa) | Aug 31, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [d146908413](https://linux-hardware.org/?probe=d146908413) | Aug 31, 2022 |
| ASRock        | N68C-S UCC                  | Desktop     | [f3389e42f8](https://linux-hardware.org/?probe=f3389e42f8) | Aug 30, 2022 |
| Unknown       | Unknown                     | Desktop     | [49c235aa0d](https://linux-hardware.org/?probe=49c235aa0d) | Aug 30, 2022 |
| Lenovo        | ThinkPad L490 20Q5001YPB    | Notebook    | [daae538154](https://linux-hardware.org/?probe=daae538154) | Aug 30, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | Desktop     | [1a8ff186c7](https://linux-hardware.org/?probe=1a8ff186c7) | Aug 29, 2022 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [4a96f9e792](https://linux-hardware.org/?probe=4a96f9e792) | Aug 29, 2022 |
| ASRock        | X370 Gaming X               | Desktop     | [e915bb3a8c](https://linux-hardware.org/?probe=e915bb3a8c) | Aug 29, 2022 |
| Dell          | Latitude 3190               | Notebook    | [0998f7a5d1](https://linux-hardware.org/?probe=0998f7a5d1) | Aug 29, 2022 |
| Dell          | Latitude 9420               | Notebook    | [0b8d883170](https://linux-hardware.org/?probe=0b8d883170) | Aug 29, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [72c01f3cf1](https://linux-hardware.org/?probe=72c01f3cf1) | Aug 29, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [3b245a809d](https://linux-hardware.org/?probe=3b245a809d) | Aug 28, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [dcb225651d](https://linux-hardware.org/?probe=dcb225651d) | Aug 28, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [499889da7e](https://linux-hardware.org/?probe=499889da7e) | Aug 28, 2022 |
| ASUSTek       | F3E                         | Notebook    | [1314dc63b6](https://linux-hardware.org/?probe=1314dc63b6) | Aug 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [7ed4b144d7](https://linux-hardware.org/?probe=7ed4b144d7) | Aug 28, 2022 |
| ASRock        | X370 Gaming X               | Desktop     | [489691c2e3](https://linux-hardware.org/?probe=489691c2e3) | Aug 28, 2022 |
| HP            | Pavilion dv6700             | Notebook    | [8fae050683](https://linux-hardware.org/?probe=8fae050683) | Aug 28, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [afde42fb41](https://linux-hardware.org/?probe=afde42fb41) | Aug 28, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [6c1db95864](https://linux-hardware.org/?probe=6c1db95864) | Aug 28, 2022 |
| Dell          | Latitude E6400              | Notebook    | [666ba32534](https://linux-hardware.org/?probe=666ba32534) | Aug 28, 2022 |
| ASUSTek       | G15DK                       | Desktop     | [231c2674a6](https://linux-hardware.org/?probe=231c2674a6) | Aug 28, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [054a02f33e](https://linux-hardware.org/?probe=054a02f33e) | Aug 28, 2022 |
| ASUSTek       | P8B WS                      | Desktop     | [5f89ab0d00](https://linux-hardware.org/?probe=5f89ab0d00) | Aug 27, 2022 |
| HP            | Pavilion dv6700             | Notebook    | [1912258e10](https://linux-hardware.org/?probe=1912258e10) | Aug 27, 2022 |
| HP            | 8054                        | Desktop     | [af4f950786](https://linux-hardware.org/?probe=af4f950786) | Aug 27, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [1813b94682](https://linux-hardware.org/?probe=1813b94682) | Aug 27, 2022 |
| HP            | 15                          | Notebook    | [310d617e09](https://linux-hardware.org/?probe=310d617e09) | Aug 26, 2022 |
| ASRock        | N68C-GS4 FX                 | Desktop     | [0462079328](https://linux-hardware.org/?probe=0462079328) | Aug 25, 2022 |
| ASUSTek       | X705UAP                     | Notebook    | [eacfc15b6c](https://linux-hardware.org/?probe=eacfc15b6c) | Aug 24, 2022 |
| ASUSTek       | P5B                         | Desktop     | [27c91a4b60](https://linux-hardware.org/?probe=27c91a4b60) | Aug 24, 2022 |
| Dell          | Inspiron 5402               | Notebook    | [936ea503c8](https://linux-hardware.org/?probe=936ea503c8) | Aug 24, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [d22f756c4c](https://linux-hardware.org/?probe=d22f756c4c) | Aug 24, 2022 |
| ASUSTek       | B85-PLUS                    | Desktop     | [1eba4b558d](https://linux-hardware.org/?probe=1eba4b558d) | Aug 23, 2022 |
| Dell          | 0T1D10 A01                  | Desktop     | [39e79a7077](https://linux-hardware.org/?probe=39e79a7077) | Aug 23, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [659e36b0ed](https://linux-hardware.org/?probe=659e36b0ed) | Aug 23, 2022 |
| MSI           | Z170A GAMING PRO CARBON     | Desktop     | [0796a8df9d](https://linux-hardware.org/?probe=0796a8df9d) | Aug 23, 2022 |
| HP            | EliteBook x360 1030 G4      | Convertible | [5e11bd516d](https://linux-hardware.org/?probe=5e11bd516d) | Aug 23, 2022 |
| Dell          | Latitude 5521               | Notebook    | [b14afc8c75](https://linux-hardware.org/?probe=b14afc8c75) | Aug 22, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [29d52f610c](https://linux-hardware.org/?probe=29d52f610c) | Aug 22, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [d37dfc0613](https://linux-hardware.org/?probe=d37dfc0613) | Aug 22, 2022 |
| Dell          | Latitude 3190               | Notebook    | [74fd1046be](https://linux-hardware.org/?probe=74fd1046be) | Aug 22, 2022 |
| Lenovo        | ThinkPad T400 6474B84       | Notebook    | [f8a6513790](https://linux-hardware.org/?probe=f8a6513790) | Aug 22, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [f38202db0d](https://linux-hardware.org/?probe=f38202db0d) | Aug 21, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [a80c24ae6b](https://linux-hardware.org/?probe=a80c24ae6b) | Aug 21, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [33a9a68b5d](https://linux-hardware.org/?probe=33a9a68b5d) | Aug 21, 2022 |
| ASUSTek       | P7P55D-E                    | Desktop     | [7c83845247](https://linux-hardware.org/?probe=7c83845247) | Aug 20, 2022 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [2f5ef1300f](https://linux-hardware.org/?probe=2f5ef1300f) | Aug 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [eb63fecd35](https://linux-hardware.org/?probe=eb63fecd35) | Aug 19, 2022 |
| Lenovo        | 3100 SDK0J40700 WIN 3258... | Desktop     | [d39161dc13](https://linux-hardware.org/?probe=d39161dc13) | Aug 19, 2022 |
| HP            | Compaq nx7300 (RH678EA#A... | Notebook    | [6fc01cef23](https://linux-hardware.org/?probe=6fc01cef23) | Aug 19, 2022 |
| Acer          | Aspire E5-475               | Notebook    | [f21f1687d5](https://linux-hardware.org/?probe=f21f1687d5) | Aug 19, 2022 |
| Acer          | Aspire E5-475               | Notebook    | [04b38f1dfd](https://linux-hardware.org/?probe=04b38f1dfd) | Aug 19, 2022 |
| ASUSTek       | A88XM-E                     | Desktop     | [04d716a25d](https://linux-hardware.org/?probe=04d716a25d) | Aug 19, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [ac7fb69037](https://linux-hardware.org/?probe=ac7fb69037) | Aug 19, 2022 |
| Dell          | Latitude 7280               | Notebook    | [63e00d0c9d](https://linux-hardware.org/?probe=63e00d0c9d) | Aug 18, 2022 |
| HP            | ZBook 17 G6                 | Notebook    | [fdcb40d147](https://linux-hardware.org/?probe=fdcb40d147) | Aug 18, 2022 |
| HP            | ZBook 17 G6                 | Notebook    | [cf5500d7b1](https://linux-hardware.org/?probe=cf5500d7b1) | Aug 18, 2022 |
| Lenovo        | ThinkPad E520 1143CWG       | Notebook    | [bc6f3f891a](https://linux-hardware.org/?probe=bc6f3f891a) | Aug 18, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [3d5404aaff](https://linux-hardware.org/?probe=3d5404aaff) | Aug 18, 2022 |
| ASRock        | H81M                        | Desktop     | [d59c4705a2](https://linux-hardware.org/?probe=d59c4705a2) | Aug 17, 2022 |
| MSI           | A320M-A PRO M2              | Desktop     | [abad46b854](https://linux-hardware.org/?probe=abad46b854) | Aug 17, 2022 |
| NEC Comput... | PC-LJ730MG6W                | Notebook    | [c0e6c7edb7](https://linux-hardware.org/?probe=c0e6c7edb7) | Aug 17, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [1ea309e90c](https://linux-hardware.org/?probe=1ea309e90c) | Aug 17, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [d8e60dcf09](https://linux-hardware.org/?probe=d8e60dcf09) | Aug 17, 2022 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [7b3d6b544c](https://linux-hardware.org/?probe=7b3d6b544c) | Aug 16, 2022 |
| MSI           | GT72S 6QE                   | Notebook    | [20121e68c8](https://linux-hardware.org/?probe=20121e68c8) | Aug 16, 2022 |
| Dell          | Latitude 3190               | Notebook    | [5564506d3c](https://linux-hardware.org/?probe=5564506d3c) | Aug 15, 2022 |
| ASUSTek       | P5K-E                       | Desktop     | [08bf3d620e](https://linux-hardware.org/?probe=08bf3d620e) | Aug 15, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [48637ddb10](https://linux-hardware.org/?probe=48637ddb10) | Aug 14, 2022 |
| HP            | 8054                        | Desktop     | [75e3136f50](https://linux-hardware.org/?probe=75e3136f50) | Aug 14, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [cc28c5783a](https://linux-hardware.org/?probe=cc28c5783a) | Aug 14, 2022 |
| MSI           | A320M-A PRO M2              | Desktop     | [d0831907e8](https://linux-hardware.org/?probe=d0831907e8) | Aug 14, 2022 |
| Dell          | Latitude E5430 vPro         | Notebook    | [08f713e80b](https://linux-hardware.org/?probe=08f713e80b) | Aug 13, 2022 |
| HP            | EliteBook 2760p             | Notebook    | [bb4c1e4c3a](https://linux-hardware.org/?probe=bb4c1e4c3a) | Aug 13, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [9d271daa54](https://linux-hardware.org/?probe=9d271daa54) | Aug 13, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [f0e405bc07](https://linux-hardware.org/?probe=f0e405bc07) | Aug 13, 2022 |
| Gigabyte      | B460M DS3H V2               | Desktop     | [2522ff1530](https://linux-hardware.org/?probe=2522ff1530) | Aug 13, 2022 |
| ASUSTek       | UX303LAB                    | Notebook    | [169419cea0](https://linux-hardware.org/?probe=169419cea0) | Aug 12, 2022 |
| HP            | ZBook 15 G4                 | Notebook    | [92cacb2a11](https://linux-hardware.org/?probe=92cacb2a11) | Aug 12, 2022 |
| Gigabyte      | H270-Gaming 3               | Desktop     | [434ba505a3](https://linux-hardware.org/?probe=434ba505a3) | Aug 12, 2022 |
| HP            | EliteBook 2760p             | Notebook    | [0ce6a49a7f](https://linux-hardware.org/?probe=0ce6a49a7f) | Aug 12, 2022 |
| Lenovo        | Z710 20250                  | Notebook    | [8c7b1d0773](https://linux-hardware.org/?probe=8c7b1d0773) | Aug 11, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [6a07e79eb7](https://linux-hardware.org/?probe=6a07e79eb7) | Aug 11, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [7e83b07cca](https://linux-hardware.org/?probe=7e83b07cca) | Aug 11, 2022 |
| HP            | 255 G4                      | Notebook    | [3ed3978b93](https://linux-hardware.org/?probe=3ed3978b93) | Aug 11, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [27eb779b2a](https://linux-hardware.org/?probe=27eb779b2a) | Aug 11, 2022 |
| Alienware     | M17xR4                      | Notebook    | [a9d3769b5b](https://linux-hardware.org/?probe=a9d3769b5b) | Aug 10, 2022 |
| Dell          | Latitude 5521               | Notebook    | [25f117c439](https://linux-hardware.org/?probe=25f117c439) | Aug 10, 2022 |
| MSI           | B365M PRO-VDH               | Desktop     | [213778bd3c](https://linux-hardware.org/?probe=213778bd3c) | Aug 10, 2022 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [f3dcea80d5](https://linux-hardware.org/?probe=f3dcea80d5) | Aug 10, 2022 |
| HP            | Pavilion HDX9200            | Notebook    | [079cb2197b](https://linux-hardware.org/?probe=079cb2197b) | Aug 10, 2022 |
| HP            | 255 G4                      | Notebook    | [44b5858d14](https://linux-hardware.org/?probe=44b5858d14) | Aug 10, 2022 |
| HP            | Compaq Presario CQ60        | Notebook    | [20f30b16e5](https://linux-hardware.org/?probe=20f30b16e5) | Aug 09, 2022 |
| Toshiba       | Satellite A300              | Notebook    | [4f83e69c06](https://linux-hardware.org/?probe=4f83e69c06) | Aug 09, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [1c9cd79646](https://linux-hardware.org/?probe=1c9cd79646) | Aug 09, 2022 |
| Lenovo        | ThinkPad L480 20LS001AMC    | Notebook    | [47d4f751e1](https://linux-hardware.org/?probe=47d4f751e1) | Aug 09, 2022 |
| ASUSTek       | A88XM-E                     | Desktop     | [f496954b96](https://linux-hardware.org/?probe=f496954b96) | Aug 08, 2022 |
| ASUSTek       | A88XM-E                     | Desktop     | [84dcf54ab8](https://linux-hardware.org/?probe=84dcf54ab8) | Aug 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [9943b58e25](https://linux-hardware.org/?probe=9943b58e25) | Aug 08, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [1f10876798](https://linux-hardware.org/?probe=1f10876798) | Aug 08, 2022 |
| Dell          | Latitude 3190               | Notebook    | [5818ff09cb](https://linux-hardware.org/?probe=5818ff09cb) | Aug 08, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [71390cb3ec](https://linux-hardware.org/?probe=71390cb3ec) | Aug 07, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [ac538e23dc](https://linux-hardware.org/?probe=ac538e23dc) | Aug 07, 2022 |
| MSI           | A320M PRO-M2                | Desktop     | [43f6f3c828](https://linux-hardware.org/?probe=43f6f3c828) | Aug 07, 2022 |
| PC Special... | Recoil II                   | Notebook    | [1e05c3546f](https://linux-hardware.org/?probe=1e05c3546f) | Aug 07, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [95f444c24c](https://linux-hardware.org/?probe=95f444c24c) | Aug 07, 2022 |
| ASUSTek       | ROG Flow X16 GV601RM_GV6... | Convertible | [a35a597a1d](https://linux-hardware.org/?probe=a35a597a1d) | Aug 07, 2022 |
| ASUSTek       | K52JT                       | Notebook    | [013f296b81](https://linux-hardware.org/?probe=013f296b81) | Aug 07, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [0ae52eddd8](https://linux-hardware.org/?probe=0ae52eddd8) | Aug 07, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [b18ee3a2ff](https://linux-hardware.org/?probe=b18ee3a2ff) | Aug 06, 2022 |
| Gigabyte      | B550 GAMING X               | Desktop     | [b158696344](https://linux-hardware.org/?probe=b158696344) | Aug 06, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [e0cfa37515](https://linux-hardware.org/?probe=e0cfa37515) | Aug 05, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [3c3a5af037](https://linux-hardware.org/?probe=3c3a5af037) | Aug 05, 2022 |
| MSI           | Creator Z17 A12UHST         | Notebook    | [ccbb6bb183](https://linux-hardware.org/?probe=ccbb6bb183) | Aug 05, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [70d84ddbc1](https://linux-hardware.org/?probe=70d84ddbc1) | Aug 05, 2022 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [0a34d32db6](https://linux-hardware.org/?probe=0a34d32db6) | Aug 05, 2022 |
| Lenovo        | ThinkPad T440s 20AR003SM... | Notebook    | [e835f1eca5](https://linux-hardware.org/?probe=e835f1eca5) | Aug 04, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [a249c68580](https://linux-hardware.org/?probe=a249c68580) | Aug 04, 2022 |
| Fujitsu Si... | AMILO Li1705                | Notebook    | [87d90381e1](https://linux-hardware.org/?probe=87d90381e1) | Aug 04, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [7f2e8ddf72](https://linux-hardware.org/?probe=7f2e8ddf72) | Aug 04, 2022 |
| ASUSTek       | G550JK                      | Notebook    | [e73f25c149](https://linux-hardware.org/?probe=e73f25c149) | Aug 03, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [fcef4276cb](https://linux-hardware.org/?probe=fcef4276cb) | Aug 03, 2022 |
| Lenovo        | Yoga 900-13ISK 80MK         | Notebook    | [1d0650ff70](https://linux-hardware.org/?probe=1d0650ff70) | Aug 03, 2022 |
| MSI           | Creator Z17 A12UHST         | Notebook    | [87533b4847](https://linux-hardware.org/?probe=87533b4847) | Aug 03, 2022 |
| ASUSTek       | G550JK                      | Notebook    | [76414b53ee](https://linux-hardware.org/?probe=76414b53ee) | Aug 03, 2022 |
| HP            | ProBook 650 G8 Notebook ... | Notebook    | [1b11fecca3](https://linux-hardware.org/?probe=1b11fecca3) | Aug 02, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [15bb5d1160](https://linux-hardware.org/?probe=15bb5d1160) | Aug 02, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [71c6ba6061](https://linux-hardware.org/?probe=71c6ba6061) | Aug 01, 2022 |
| Dell          | Latitude 3190               | Notebook    | [1f86e5fa57](https://linux-hardware.org/?probe=1f86e5fa57) | Aug 01, 2022 |
| HP            | EliteBook x360 1030 G4      | Convertible | [29295c7c8e](https://linux-hardware.org/?probe=29295c7c8e) | Aug 01, 2022 |
| HP            | EliteBook x360 1030 G4      | Convertible | [a56b47616c](https://linux-hardware.org/?probe=a56b47616c) | Aug 01, 2022 |
| Acer          | Aspire 5730                 | Notebook    | [1541bd94e2](https://linux-hardware.org/?probe=1541bd94e2) | Jul 31, 2022 |
| Acer          | Aspire V5-591G              | Notebook    | [80396b28bf](https://linux-hardware.org/?probe=80396b28bf) | Jul 31, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [097b95fdde](https://linux-hardware.org/?probe=097b95fdde) | Jul 31, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [1051593809](https://linux-hardware.org/?probe=1051593809) | Jul 31, 2022 |
| HP            | 550                         | Notebook    | [efc4b32963](https://linux-hardware.org/?probe=efc4b32963) | Jul 30, 2022 |
| Lenovo        | 1051L 60073                 | Tablet      | [4ae44495ba](https://linux-hardware.org/?probe=4ae44495ba) | Jul 30, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [10ece2cb6c](https://linux-hardware.org/?probe=10ece2cb6c) | Jul 30, 2022 |
| Dell          | XPS M1330                   | Notebook    | [2abad8da86](https://linux-hardware.org/?probe=2abad8da86) | Jul 30, 2022 |
| Lenovo        | 364A SDK0J40700 WIN 3258... | Desktop     | [13eff519f6](https://linux-hardware.org/?probe=13eff519f6) | Jul 30, 2022 |
| HP            | 21B4 A01                    | Desktop     | [474779f0b9](https://linux-hardware.org/?probe=474779f0b9) | Jul 30, 2022 |
| Acer          | Aspire 5730                 | Notebook    | [8ac8b8a87a](https://linux-hardware.org/?probe=8ac8b8a87a) | Jul 30, 2022 |
| Dell          | Precision 5550              | Notebook    | [e11d4be493](https://linux-hardware.org/?probe=e11d4be493) | Jul 30, 2022 |
| Lenovo        | ThinkPad L480 20LS002CPB    | Notebook    | [35764371d6](https://linux-hardware.org/?probe=35764371d6) | Jul 29, 2022 |
| MSI           | X470 GAMING PLUS            | Desktop     | [8415a45799](https://linux-hardware.org/?probe=8415a45799) | Jul 28, 2022 |
| Dell          | Latitude E7470              | Notebook    | [9f4d55071c](https://linux-hardware.org/?probe=9f4d55071c) | Jul 28, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [cb1458b51e](https://linux-hardware.org/?probe=cb1458b51e) | Jul 28, 2022 |
| HP            | ProLiant ML330 G6           | Desktop     | [7940deabb7](https://linux-hardware.org/?probe=7940deabb7) | Jul 28, 2022 |
| HP            | ProLiant ML330 G6           | Desktop     | [711602c0ac](https://linux-hardware.org/?probe=711602c0ac) | Jul 28, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [48e8d6fba9](https://linux-hardware.org/?probe=48e8d6fba9) | Jul 28, 2022 |
| MSI           | X470 GAMING PLUS            | Desktop     | [88ac64a1bd](https://linux-hardware.org/?probe=88ac64a1bd) | Jul 28, 2022 |
| Lenovo        | 1051L 60073                 | Tablet      | [2b505d28f7](https://linux-hardware.org/?probe=2b505d28f7) | Jul 27, 2022 |
| Lenovo        | 1051L 60073                 | Tablet      | [51bf4e60d3](https://linux-hardware.org/?probe=51bf4e60d3) | Jul 27, 2022 |
| MSI           | B250 PC MATE                | Desktop     | [dda7519d05](https://linux-hardware.org/?probe=dda7519d05) | Jul 27, 2022 |
| Dell          | Latitude 5421               | Notebook    | [ec91a9ea85](https://linux-hardware.org/?probe=ec91a9ea85) | Jul 27, 2022 |
| Dell          | 0G261D A00                  | Desktop     | [f7cb8645af](https://linux-hardware.org/?probe=f7cb8645af) | Jul 27, 2022 |
| Intel         | DH67VR AAG27177-201         | Desktop     | [3aeca135cd](https://linux-hardware.org/?probe=3aeca135cd) | Jul 26, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [05947b595a](https://linux-hardware.org/?probe=05947b595a) | Jul 26, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [4ddfbb6ad8](https://linux-hardware.org/?probe=4ddfbb6ad8) | Jul 26, 2022 |
| Toshiba       | Satellite L750D             | Notebook    | [c8e9ea3fdd](https://linux-hardware.org/?probe=c8e9ea3fdd) | Jul 26, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [aabcc30a17](https://linux-hardware.org/?probe=aabcc30a17) | Jul 25, 2022 |
| Dell          | Latitude 3190               | Notebook    | [2ec6ff1812](https://linux-hardware.org/?probe=2ec6ff1812) | Jul 25, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [e1e16aa154](https://linux-hardware.org/?probe=e1e16aa154) | Jul 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | Notebook    | [123fc55893](https://linux-hardware.org/?probe=123fc55893) | Jul 24, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [153acd77c2](https://linux-hardware.org/?probe=153acd77c2) | Jul 24, 2022 |
| ASRock        | AM1H-ITX                    | Desktop     | [a15c82ba0c](https://linux-hardware.org/?probe=a15c82ba0c) | Jul 24, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [542296a447](https://linux-hardware.org/?probe=542296a447) | Jul 24, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [5658129aa4](https://linux-hardware.org/?probe=5658129aa4) | Jul 24, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [2b7f8eb0df](https://linux-hardware.org/?probe=2b7f8eb0df) | Jul 24, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [570348c3f5](https://linux-hardware.org/?probe=570348c3f5) | Jul 23, 2022 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [dc8bafd932](https://linux-hardware.org/?probe=dc8bafd932) | Jul 23, 2022 |
| Lenovo        | IdeaPad 5 Pro 16IHU6 82L... | Notebook    | [b16e17a798](https://linux-hardware.org/?probe=b16e17a798) | Jul 23, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [597fb27e56](https://linux-hardware.org/?probe=597fb27e56) | Jul 23, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [8b1930ddbd](https://linux-hardware.org/?probe=8b1930ddbd) | Jul 22, 2022 |
| Apple         | Mac-42FD25EABCABB274 iMa... | All in one  | [c8e4c217c0](https://linux-hardware.org/?probe=c8e4c217c0) | Jul 22, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | Notebook    | [4e47525879](https://linux-hardware.org/?probe=4e47525879) | Jul 22, 2022 |
| Packard Be... | EasyNote TE11BZ             | Notebook    | [e1099c5342](https://linux-hardware.org/?probe=e1099c5342) | Jul 22, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [8e0cd55a28](https://linux-hardware.org/?probe=8e0cd55a28) | Jul 22, 2022 |
| ASUSTek       | X550CL                      | Notebook    | [abd0b78e41](https://linux-hardware.org/?probe=abd0b78e41) | Jul 21, 2022 |
| Dell          | Latitude E6540              | Notebook    | [4688c6f312](https://linux-hardware.org/?probe=4688c6f312) | Jul 21, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [03afe0a303](https://linux-hardware.org/?probe=03afe0a303) | Jul 20, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [63d34f24b6](https://linux-hardware.org/?probe=63d34f24b6) | Jul 20, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [83d1355e61](https://linux-hardware.org/?probe=83d1355e61) | Jul 19, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [ae8bbea84b](https://linux-hardware.org/?probe=ae8bbea84b) | Jul 19, 2022 |
| ASUSTek       | P5K-E                       | Desktop     | [68023f05e9](https://linux-hardware.org/?probe=68023f05e9) | Jul 18, 2022 |
| Gigabyte      | Z590 GAMING X               | Desktop     | [4a97996102](https://linux-hardware.org/?probe=4a97996102) | Jul 18, 2022 |
| ASRock        | Z170 Extreme4               | Desktop     | [4f4b63a026](https://linux-hardware.org/?probe=4f4b63a026) | Jul 18, 2022 |
| Dell          | Latitude 3190               | Notebook    | [4fa9fe26c1](https://linux-hardware.org/?probe=4fa9fe26c1) | Jul 18, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [8f2f1582e8](https://linux-hardware.org/?probe=8f2f1582e8) | Jul 17, 2022 |
| Intel         | DG31PR AAD97573-301         | Desktop     | [0ac01b7529](https://linux-hardware.org/?probe=0ac01b7529) | Jul 17, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [08446807d6](https://linux-hardware.org/?probe=08446807d6) | Jul 17, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [056d74f1a9](https://linux-hardware.org/?probe=056d74f1a9) | Jul 17, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [e454469a83](https://linux-hardware.org/?probe=e454469a83) | Jul 17, 2022 |
| MSI           | X370 KRAIT GAMING           | Desktop     | [e74a442ccc](https://linux-hardware.org/?probe=e74a442ccc) | Jul 17, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [18d1378620](https://linux-hardware.org/?probe=18d1378620) | Jul 16, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [e6b47dedd7](https://linux-hardware.org/?probe=e6b47dedd7) | Jul 15, 2022 |
| MSI           | MAG Z390 TOMAHAWK           | Desktop     | [75e4cc3704](https://linux-hardware.org/?probe=75e4cc3704) | Jul 15, 2022 |
| MSI           | Creator Z17 A12UHST         | Notebook    | [ef0c958c66](https://linux-hardware.org/?probe=ef0c958c66) | Jul 15, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [329ce2f7f8](https://linux-hardware.org/?probe=329ce2f7f8) | Jul 15, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [d6b737940e](https://linux-hardware.org/?probe=d6b737940e) | Jul 15, 2022 |
| HP            | Pavilion dv6700             | Notebook    | [4d653cf4e6](https://linux-hardware.org/?probe=4d653cf4e6) | Jul 15, 2022 |
| Lenovo        | ThinkCentre M58p 6234F73    | Desktop     | [c5695a430f](https://linux-hardware.org/?probe=c5695a430f) | Jul 15, 2022 |
| Lenovo        | ThinkCentre M58p 6234F73    | Desktop     | [0a0ad06ece](https://linux-hardware.org/?probe=0a0ad06ece) | Jul 15, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [ea97effc52](https://linux-hardware.org/?probe=ea97effc52) | Jul 14, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [57ef4db755](https://linux-hardware.org/?probe=57ef4db755) | Jul 14, 2022 |
| ASUSTek       | M4A78 PRO                   | Desktop     | [119c291cd5](https://linux-hardware.org/?probe=119c291cd5) | Jul 14, 2022 |
| Hyperbook     | Z15 Zen                     | Notebook    | [41129ecc5e](https://linux-hardware.org/?probe=41129ecc5e) | Jul 14, 2022 |
| Unknown       | Intel X79                   | Desktop     | [b0bb64b9ea](https://linux-hardware.org/?probe=b0bb64b9ea) | Jul 13, 2022 |
| MSI           | B250M PRO-VH                | Desktop     | [d0a4b76e78](https://linux-hardware.org/?probe=d0a4b76e78) | Jul 13, 2022 |
| HP            | 83E8                        | Desktop     | [a2dc0fc924](https://linux-hardware.org/?probe=a2dc0fc924) | Jul 13, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [c95dd7e491](https://linux-hardware.org/?probe=c95dd7e491) | Jul 13, 2022 |
| ASRock        | Z170 Extreme4               | Desktop     | [7ecf3ad1b7](https://linux-hardware.org/?probe=7ecf3ad1b7) | Jul 13, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [f422c77bb1](https://linux-hardware.org/?probe=f422c77bb1) | Jul 12, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [495c5afa4b](https://linux-hardware.org/?probe=495c5afa4b) | Jul 12, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [2566bb66dd](https://linux-hardware.org/?probe=2566bb66dd) | Jul 12, 2022 |
| Dell          | Latitude E6420              | Notebook    | [d3bbc4a899](https://linux-hardware.org/?probe=d3bbc4a899) | Jul 12, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [6b29072d9e](https://linux-hardware.org/?probe=6b29072d9e) | Jul 11, 2022 |
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [24dc866c51](https://linux-hardware.org/?probe=24dc866c51) | Jul 11, 2022 |
| MSI           | H81M-P33                    | Desktop     | [05099f85ea](https://linux-hardware.org/?probe=05099f85ea) | Jul 11, 2022 |
| MSI           | B350 GAMING PLUS            | Desktop     | [778b1989d4](https://linux-hardware.org/?probe=778b1989d4) | Jul 11, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [fd9365ab43](https://linux-hardware.org/?probe=fd9365ab43) | Jul 11, 2022 |
| Dell          | Latitude 3190               | Notebook    | [b3c7283cdb](https://linux-hardware.org/?probe=b3c7283cdb) | Jul 11, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [f49fb95b26](https://linux-hardware.org/?probe=f49fb95b26) | Jul 10, 2022 |
| HP            | ProBook 4740s               | Notebook    | [18ff2d02bd](https://linux-hardware.org/?probe=18ff2d02bd) | Jul 10, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [6ed9abc24e](https://linux-hardware.org/?probe=6ed9abc24e) | Jul 10, 2022 |
| Lenovo        | SKYBAY NOK                  | Desktop     | [5e8f90f865](https://linux-hardware.org/?probe=5e8f90f865) | Jul 10, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [9da782ecf0](https://linux-hardware.org/?probe=9da782ecf0) | Jul 10, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [c350afe818](https://linux-hardware.org/?probe=c350afe818) | Jul 10, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [0237c9df10](https://linux-hardware.org/?probe=0237c9df10) | Jul 10, 2022 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [65c661af95](https://linux-hardware.org/?probe=65c661af95) | Jul 09, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [b8c450d5fa](https://linux-hardware.org/?probe=b8c450d5fa) | Jul 08, 2022 |
| Lenovo        | ThinkPad R61 8932FJG        | Notebook    | [d783a022b3](https://linux-hardware.org/?probe=d783a022b3) | Jul 08, 2022 |
| Dell          | Latitude D420               | Notebook    | [2e3ded5234](https://linux-hardware.org/?probe=2e3ded5234) | Jul 08, 2022 |
| Acer          | Aspire A715-75G             | Notebook    | [4a6cc98dd6](https://linux-hardware.org/?probe=4a6cc98dd6) | Jul 08, 2022 |
| MSI           | GF63 Thin 8RCS              | Notebook    | [886728c1b6](https://linux-hardware.org/?probe=886728c1b6) | Jul 08, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [5cf26aa015](https://linux-hardware.org/?probe=5cf26aa015) | Jul 08, 2022 |
| Lenovo        | ThinkPad T410 2537W2L       | Notebook    | [a2e55ad8ac](https://linux-hardware.org/?probe=a2e55ad8ac) | Jul 07, 2022 |
| MSI           | B250M BAZOOKA               | Desktop     | [e04f1fc85c](https://linux-hardware.org/?probe=e04f1fc85c) | Jul 07, 2022 |
| ASRock        | P67 Pro3                    | Desktop     | [b70f0fde7a](https://linux-hardware.org/?probe=b70f0fde7a) | Jul 07, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [c75201835c](https://linux-hardware.org/?probe=c75201835c) | Jul 06, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [4009adaca2](https://linux-hardware.org/?probe=4009adaca2) | Jul 05, 2022 |
| Dell          | 09KPNV A00                  | Desktop     | [7eb69e794e](https://linux-hardware.org/?probe=7eb69e794e) | Jul 05, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [b4732a4bda](https://linux-hardware.org/?probe=b4732a4bda) | Jul 05, 2022 |
| Lenovo        | ThinkPad P53 20QNS00Y00     | Notebook    | [64dc631691](https://linux-hardware.org/?probe=64dc631691) | Jul 05, 2022 |
| HP            | ProBook 6475b               | Notebook    | [02eab8bd42](https://linux-hardware.org/?probe=02eab8bd42) | Jul 05, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [7d6a8718a8](https://linux-hardware.org/?probe=7d6a8718a8) | Jul 05, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [327086a8b8](https://linux-hardware.org/?probe=327086a8b8) | Jul 04, 2022 |
| Dell          | Latitude 7280               | Notebook    | [5333012df2](https://linux-hardware.org/?probe=5333012df2) | Jul 04, 2022 |
| Dell          | Latitude 3190               | Notebook    | [f5c0f0798a](https://linux-hardware.org/?probe=f5c0f0798a) | Jul 04, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [740ba48457](https://linux-hardware.org/?probe=740ba48457) | Jul 03, 2022 |
| Dell          | Latitude E6420              | Notebook    | [e1b517f8af](https://linux-hardware.org/?probe=e1b517f8af) | Jul 03, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [6918411ee2](https://linux-hardware.org/?probe=6918411ee2) | Jul 03, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [a57cf9cc46](https://linux-hardware.org/?probe=a57cf9cc46) | Jul 03, 2022 |
| ASUSTek       | X55U                        | Notebook    | [ed55b4ef39](https://linux-hardware.org/?probe=ed55b4ef39) | Jul 03, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [6a5bc93a4b](https://linux-hardware.org/?probe=6a5bc93a4b) | Jul 03, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [6ffcfe37d6](https://linux-hardware.org/?probe=6ffcfe37d6) | Jul 03, 2022 |
| Lenovo        | ThinkPad E470 20H1007MPB    | Notebook    | [7a20748cc1](https://linux-hardware.org/?probe=7a20748cc1) | Jul 03, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [565fb652b8](https://linux-hardware.org/?probe=565fb652b8) | Jul 03, 2022 |
| Lenovo        | ThinkPad Edge E430 3254A... | Notebook    | [8b717c6bdf](https://linux-hardware.org/?probe=8b717c6bdf) | Jul 02, 2022 |
| ASUSTek       | M4A78 PRO                   | Desktop     | [d76404df8d](https://linux-hardware.org/?probe=d76404df8d) | Jul 02, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [c8b31466ed](https://linux-hardware.org/?probe=c8b31466ed) | Jul 02, 2022 |
| Dell          | Latitude D420               | Notebook    | [162b346743](https://linux-hardware.org/?probe=162b346743) | Jul 02, 2022 |
| ASRock        | P67 Pro3                    | Desktop     | [9f1ed28d62](https://linux-hardware.org/?probe=9f1ed28d62) | Jul 02, 2022 |
| Dell          | 09KPNV A00                  | Desktop     | [163fad4354](https://linux-hardware.org/?probe=163fad4354) | Jul 02, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [10ff366630](https://linux-hardware.org/?probe=10ff366630) | Jul 01, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [8e6d23cf01](https://linux-hardware.org/?probe=8e6d23cf01) | Jul 01, 2022 |
| ASRock        | P67 Pro3                    | Desktop     | [403db88011](https://linux-hardware.org/?probe=403db88011) | Jul 01, 2022 |
| ASRock        | P67 Pro3                    | Desktop     | [4ba5c0b79e](https://linux-hardware.org/?probe=4ba5c0b79e) | Jul 01, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [a32cb9b3f1](https://linux-hardware.org/?probe=a32cb9b3f1) | Jul 01, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [2671f4ffe2](https://linux-hardware.org/?probe=2671f4ffe2) | Jul 01, 2022 |
| ASRock        | P67 Pro3                    | Desktop     | [632dbea587](https://linux-hardware.org/?probe=632dbea587) | Jul 01, 2022 |
| Lenovo        | ThinkPad T450s 20BX002NM... | Notebook    | [3bb2e1821b](https://linux-hardware.org/?probe=3bb2e1821b) | Jul 01, 2022 |
| Dell          | Latitude 3420               | Notebook    | [651ab17da0](https://linux-hardware.org/?probe=651ab17da0) | Jun 30, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [06ca24d4e1](https://linux-hardware.org/?probe=06ca24d4e1) | Jun 30, 2022 |
| ASRock        | P67 Pro3                    | Desktop     | [aaf8589ded](https://linux-hardware.org/?probe=aaf8589ded) | Jun 30, 2022 |
| Framework     | Laptop                      | Notebook    | [8a44001ebb](https://linux-hardware.org/?probe=8a44001ebb) | Jun 30, 2022 |
| Framework     | Laptop                      | Notebook    | [61a6480a38](https://linux-hardware.org/?probe=61a6480a38) | Jun 30, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [6cf63ca19e](https://linux-hardware.org/?probe=6cf63ca19e) | Jun 30, 2022 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [0e09c926c1](https://linux-hardware.org/?probe=0e09c926c1) | Jun 30, 2022 |
| Dell          | Inspiron M5040              | Notebook    | [64c8f1ad3f](https://linux-hardware.org/?probe=64c8f1ad3f) | Jun 29, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [dbe5fe496a](https://linux-hardware.org/?probe=dbe5fe496a) | Jun 29, 2022 |
| Getac         | B300-X                      | Notebook    | [eb752b6c15](https://linux-hardware.org/?probe=eb752b6c15) | Jun 29, 2022 |
| Lenovo        | ThinkPad T420 4180MY7       | Notebook    | [1e755c8031](https://linux-hardware.org/?probe=1e755c8031) | Jun 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6dc02ab574](https://linux-hardware.org/?probe=6dc02ab574) | Jun 29, 2022 |
| Lenovo        | ThinkPad T420 4180MY7       | Notebook    | [a57e4e84f8](https://linux-hardware.org/?probe=a57e4e84f8) | Jun 29, 2022 |
| ASRock        | P67 Pro3                    | Desktop     | [bdecafbe1d](https://linux-hardware.org/?probe=bdecafbe1d) | Jun 29, 2022 |
| Dell          | Inspiron M5040              | Notebook    | [a9522b8288](https://linux-hardware.org/?probe=a9522b8288) | Jun 28, 2022 |
| Gigabyte      | B150-HD3 DDR3-CF            | Desktop     | [3fe71d66c6](https://linux-hardware.org/?probe=3fe71d66c6) | Jun 28, 2022 |
| Dell          | Latitude D420               | Notebook    | [c531c131ec](https://linux-hardware.org/?probe=c531c131ec) | Jun 28, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f188fe2a3d](https://linux-hardware.org/?probe=f188fe2a3d) | Jun 28, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [4c0fa03f61](https://linux-hardware.org/?probe=4c0fa03f61) | Jun 28, 2022 |
| Dell          | Latitude 5511               | Notebook    | [c361c37273](https://linux-hardware.org/?probe=c361c37273) | Jun 28, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [0ea209fffe](https://linux-hardware.org/?probe=0ea209fffe) | Jun 28, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [d399933441](https://linux-hardware.org/?probe=d399933441) | Jun 28, 2022 |
| Lenovo        | ThinkPad T470 20HES07J00    | Notebook    | [4be29eb5f1](https://linux-hardware.org/?probe=4be29eb5f1) | Jun 27, 2022 |
| Dell          | Latitude 3190               | Notebook    | [3bf5b47ea1](https://linux-hardware.org/?probe=3bf5b47ea1) | Jun 27, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [a6555d107c](https://linux-hardware.org/?probe=a6555d107c) | Jun 27, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [79dca3a17c](https://linux-hardware.org/?probe=79dca3a17c) | Jun 26, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [f90172a9f9](https://linux-hardware.org/?probe=f90172a9f9) | Jun 26, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [1f3399d205](https://linux-hardware.org/?probe=1f3399d205) | Jun 26, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [02e93f831d](https://linux-hardware.org/?probe=02e93f831d) | Jun 26, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [c84ca40dae](https://linux-hardware.org/?probe=c84ca40dae) | Jun 26, 2022 |
| MSI           | H81M-P33                    | Desktop     | [d690a68389](https://linux-hardware.org/?probe=d690a68389) | Jun 25, 2022 |
| ASUSTek       | TUF Z370-PLUS GAMING        | Desktop     | [6c6d94e4b7](https://linux-hardware.org/?probe=6c6d94e4b7) | Jun 25, 2022 |
| ASRock        | H87 Pro4                    | Desktop     | [47cf388077](https://linux-hardware.org/?probe=47cf388077) | Jun 25, 2022 |
| ASRock        | A320M Pro4                  | Desktop     | [e1918d8aab](https://linux-hardware.org/?probe=e1918d8aab) | Jun 25, 2022 |
| MSI           | H81M-P33                    | Desktop     | [9ba6c64800](https://linux-hardware.org/?probe=9ba6c64800) | Jun 25, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [fe8f74c9c1](https://linux-hardware.org/?probe=fe8f74c9c1) | Jun 25, 2022 |
| ASRock        | H87 Pro4                    | Desktop     | [73eb3e0db6](https://linux-hardware.org/?probe=73eb3e0db6) | Jun 25, 2022 |
| Unknown       | K8NF3-VSTA                  | Desktop     | [f2ea6e0d83](https://linux-hardware.org/?probe=f2ea6e0d83) | Jun 24, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [6a5e82663e](https://linux-hardware.org/?probe=6a5e82663e) | Jun 24, 2022 |
| ASRock        | A320M Pro4                  | Desktop     | [f4f2e68e79](https://linux-hardware.org/?probe=f4f2e68e79) | Jun 24, 2022 |
| Dell          | 0HY9JP A00                  | Desktop     | [92c1597a97](https://linux-hardware.org/?probe=92c1597a97) | Jun 24, 2022 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [08e5f734f9](https://linux-hardware.org/?probe=08e5f734f9) | Jun 24, 2022 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [95d5fd3cd1](https://linux-hardware.org/?probe=95d5fd3cd1) | Jun 24, 2022 |
| ASUSTek       | X751LK                      | Notebook    | [d7f4b1678b](https://linux-hardware.org/?probe=d7f4b1678b) | Jun 24, 2022 |
| ASUSTek       | X751LK                      | Notebook    | [09dfab066c](https://linux-hardware.org/?probe=09dfab066c) | Jun 24, 2022 |
| Lenovo        | ThinkPad T450 20BUS0QT04    | Notebook    | [0c96d2bc24](https://linux-hardware.org/?probe=0c96d2bc24) | Jun 24, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [ac634d8aa9](https://linux-hardware.org/?probe=ac634d8aa9) | Jun 23, 2022 |
| ASRock        | H510M-ITX/ac                | Desktop     | [f1e5f3d686](https://linux-hardware.org/?probe=f1e5f3d686) | Jun 23, 2022 |
| Acer          | Aspire E1-570               | Notebook    | [906b1f465e](https://linux-hardware.org/?probe=906b1f465e) | Jun 23, 2022 |
| MSI           | B350 TOMAHAWK               | Desktop     | [5a66940742](https://linux-hardware.org/?probe=5a66940742) | Jun 23, 2022 |
| MSI           | B85M-E45                    | Desktop     | [f5e1312d31](https://linux-hardware.org/?probe=f5e1312d31) | Jun 22, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [43c1598008](https://linux-hardware.org/?probe=43c1598008) | Jun 22, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [212cd0ac63](https://linux-hardware.org/?probe=212cd0ac63) | Jun 22, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [f82628e802](https://linux-hardware.org/?probe=f82628e802) | Jun 21, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [402aec2b04](https://linux-hardware.org/?probe=402aec2b04) | Jun 21, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [d6c4bb6995](https://linux-hardware.org/?probe=d6c4bb6995) | Jun 21, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [23f396c697](https://linux-hardware.org/?probe=23f396c697) | Jun 21, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [551da1dbb6](https://linux-hardware.org/?probe=551da1dbb6) | Jun 20, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [490076a383](https://linux-hardware.org/?probe=490076a383) | Jun 20, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [401a520d39](https://linux-hardware.org/?probe=401a520d39) | Jun 20, 2022 |
| Xunlong       | Orange Pi Lite              | Soc         | [3584e25b54](https://linux-hardware.org/?probe=3584e25b54) | Jun 20, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [52aa806063](https://linux-hardware.org/?probe=52aa806063) | Jun 20, 2022 |
| Dell          | Latitude 3190               | Notebook    | [bb05f51a63](https://linux-hardware.org/?probe=bb05f51a63) | Jun 20, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [2028b239fc](https://linux-hardware.org/?probe=2028b239fc) | Jun 19, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [20c198dd50](https://linux-hardware.org/?probe=20c198dd50) | Jun 19, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [bdb03fcb5a](https://linux-hardware.org/?probe=bdb03fcb5a) | Jun 19, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [d9ac6a3f41](https://linux-hardware.org/?probe=d9ac6a3f41) | Jun 19, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [3c8a4e8226](https://linux-hardware.org/?probe=3c8a4e8226) | Jun 18, 2022 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [ee2f7822c9](https://linux-hardware.org/?probe=ee2f7822c9) | Jun 18, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [b9c65b6182](https://linux-hardware.org/?probe=b9c65b6182) | Jun 18, 2022 |
| ASRock        | P67 Pro3                    | Desktop     | [9804004de5](https://linux-hardware.org/?probe=9804004de5) | Jun 18, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [67757f27f2](https://linux-hardware.org/?probe=67757f27f2) | Jun 18, 2022 |
| ASUSTek       | P9X79 DELUXE                | Desktop     | [a6cb0e21fc](https://linux-hardware.org/?probe=a6cb0e21fc) | Jun 17, 2022 |
| Dell          | 0P9XHK A00                  | Desktop     | [e167c05dd2](https://linux-hardware.org/?probe=e167c05dd2) | Jun 17, 2022 |
| ASRock        | P67 Pro3                    | Desktop     | [2c0a807c9c](https://linux-hardware.org/?probe=2c0a807c9c) | Jun 17, 2022 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [f944290604](https://linux-hardware.org/?probe=f944290604) | Jun 17, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [83733f81bd](https://linux-hardware.org/?probe=83733f81bd) | Jun 17, 2022 |
| Dell          | Latitude E5450              | Notebook    | [42f5a53e24](https://linux-hardware.org/?probe=42f5a53e24) | Jun 16, 2022 |
| Fujitsu       | D2759 S26361-D2759-A13 W... | Server      | [2fc93b52d1](https://linux-hardware.org/?probe=2fc93b52d1) | Jun 16, 2022 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [29cfeda814](https://linux-hardware.org/?probe=29cfeda814) | Jun 15, 2022 |
| Acer          | Aspire E1-570G              | Notebook    | [060b0319ff](https://linux-hardware.org/?probe=060b0319ff) | Jun 15, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [b12643d9ac](https://linux-hardware.org/?probe=b12643d9ac) | Jun 15, 2022 |
| mPTech        | ARC 11.6 128GB HD           | Notebook    | [b9469e3ae8](https://linux-hardware.org/?probe=b9469e3ae8) | Jun 15, 2022 |
| Dell          | Latitude E6430s             | Notebook    | [a1043bd5bf](https://linux-hardware.org/?probe=a1043bd5bf) | Jun 14, 2022 |
| ASUSTek       | 1005P                       | Notebook    | [4bd178fe29](https://linux-hardware.org/?probe=4bd178fe29) | Jun 14, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [35cbb5ff8b](https://linux-hardware.org/?probe=35cbb5ff8b) | Jun 14, 2022 |
| ASRock        | P67 Pro3                    | Desktop     | [d56de69a04](https://linux-hardware.org/?probe=d56de69a04) | Jun 14, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [7ca7f789d8](https://linux-hardware.org/?probe=7ca7f789d8) | Jun 14, 2022 |
| Dell          | Latitude E5470              | Notebook    | [a4533cfbc7](https://linux-hardware.org/?probe=a4533cfbc7) | Jun 14, 2022 |
| Acer          | Aspire 7738                 | Notebook    | [39646d89f1](https://linux-hardware.org/?probe=39646d89f1) | Jun 14, 2022 |
| Acer          | TravelMate 5760             | Notebook    | [90e189c067](https://linux-hardware.org/?probe=90e189c067) | Jun 13, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [695e3a37d4](https://linux-hardware.org/?probe=695e3a37d4) | Jun 13, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [e33ea31f97](https://linux-hardware.org/?probe=e33ea31f97) | Jun 13, 2022 |
| HP            | EliteBook 850 G2            | Notebook    | [10b796ad9c](https://linux-hardware.org/?probe=10b796ad9c) | Jun 13, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [0a985a9f53](https://linux-hardware.org/?probe=0a985a9f53) | Jun 13, 2022 |
| MSI           | Bravo 17 A4DDR              | Notebook    | [fc31a9ec53](https://linux-hardware.org/?probe=fc31a9ec53) | Jun 13, 2022 |
| MSI           | Bravo 17 A4DDR              | Notebook    | [916ce4be3b](https://linux-hardware.org/?probe=916ce4be3b) | Jun 13, 2022 |
| ASRock        | P67 Pro3                    | Desktop     | [48cc60a732](https://linux-hardware.org/?probe=48cc60a732) | Jun 13, 2022 |
| Dell          | Latitude 3190               | Notebook    | [fb55b815b6](https://linux-hardware.org/?probe=fb55b815b6) | Jun 13, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [59350b295e](https://linux-hardware.org/?probe=59350b295e) | Jun 13, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [223b882103](https://linux-hardware.org/?probe=223b882103) | Jun 12, 2022 |
| HP            | ZBook Studio G3             | Notebook    | [0dda22b68b](https://linux-hardware.org/?probe=0dda22b68b) | Jun 12, 2022 |
| Lenovo        | ThinkPad T530 23923MG       | Notebook    | [cf21c4e831](https://linux-hardware.org/?probe=cf21c4e831) | Jun 12, 2022 |
| HP            | 3396                        | Desktop     | [4c0f1563a7](https://linux-hardware.org/?probe=4c0f1563a7) | Jun 12, 2022 |
| Lenovo        | M490s 20214                 | Notebook    | [961e8807e9](https://linux-hardware.org/?probe=961e8807e9) | Jun 12, 2022 |
| Gigabyte      | B75-D3V                     | Desktop     | [f0fe22dfe7](https://linux-hardware.org/?probe=f0fe22dfe7) | Jun 12, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [b1d8f7c281](https://linux-hardware.org/?probe=b1d8f7c281) | Jun 12, 2022 |
| ASUSTek       | K53BR                       | Notebook    | [b64b9e0f4a](https://linux-hardware.org/?probe=b64b9e0f4a) | Jun 12, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [4e830e41ec](https://linux-hardware.org/?probe=4e830e41ec) | Jun 11, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [e1f785770e](https://linux-hardware.org/?probe=e1f785770e) | Jun 11, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [0c1e336ddc](https://linux-hardware.org/?probe=0c1e336ddc) | Jun 11, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [b0e6137115](https://linux-hardware.org/?probe=b0e6137115) | Jun 11, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [1698782254](https://linux-hardware.org/?probe=1698782254) | Jun 11, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [785b725767](https://linux-hardware.org/?probe=785b725767) | Jun 10, 2022 |
| Dell          | Latitude 5310               | Notebook    | [fe0ffed6e4](https://linux-hardware.org/?probe=fe0ffed6e4) | Jun 10, 2022 |
| HP            | EliteBook 850 G3            | Notebook    | [e086b31446](https://linux-hardware.org/?probe=e086b31446) | Jun 10, 2022 |
| Acer          | WG43M                       | Desktop     | [bdd6d72374](https://linux-hardware.org/?probe=bdd6d72374) | Jun 10, 2022 |
| Lenovo        | ThinkPad P50 20EQS3B30R     | Notebook    | [c97b8918a0](https://linux-hardware.org/?probe=c97b8918a0) | Jun 10, 2022 |
| Dell          | Latitude E6420              | Notebook    | [a92cd16ef7](https://linux-hardware.org/?probe=a92cd16ef7) | Jun 10, 2022 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | Notebook    | [58d62f94d4](https://linux-hardware.org/?probe=58d62f94d4) | Jun 09, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [377aa877fc](https://linux-hardware.org/?probe=377aa877fc) | Jun 09, 2022 |
| Lenovo        | ThinkPad T500 2241A87       | Notebook    | [96b00f450d](https://linux-hardware.org/?probe=96b00f450d) | Jun 09, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [d14ead3bf7](https://linux-hardware.org/?probe=d14ead3bf7) | Jun 09, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [cec4cb4af4](https://linux-hardware.org/?probe=cec4cb4af4) | Jun 09, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [76a0fe2907](https://linux-hardware.org/?probe=76a0fe2907) | Jun 09, 2022 |
| Lenovo        | ThinkPad T530 2429B68       | Notebook    | [86e92f8a19](https://linux-hardware.org/?probe=86e92f8a19) | Jun 09, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [ebc62a50b4](https://linux-hardware.org/?probe=ebc62a50b4) | Jun 08, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [5af5c89f5e](https://linux-hardware.org/?probe=5af5c89f5e) | Jun 08, 2022 |
| Dell          | Latitude 5421               | Notebook    | [24665e8e4b](https://linux-hardware.org/?probe=24665e8e4b) | Jun 08, 2022 |
| Gigabyte      | H410M S2H V3                | Desktop     | [feaff6859d](https://linux-hardware.org/?probe=feaff6859d) | Jun 07, 2022 |
| Acer          | WG43M                       | Desktop     | [70d3c85c47](https://linux-hardware.org/?probe=70d3c85c47) | Jun 07, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [ffceb89203](https://linux-hardware.org/?probe=ffceb89203) | Jun 07, 2022 |
| Dell          | Precision 5550              | Notebook    | [a4bf41771c](https://linux-hardware.org/?probe=a4bf41771c) | Jun 07, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [4655b6a8ed](https://linux-hardware.org/?probe=4655b6a8ed) | Jun 07, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [74c4c38cae](https://linux-hardware.org/?probe=74c4c38cae) | Jun 07, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [a6feb9dcd2](https://linux-hardware.org/?probe=a6feb9dcd2) | Jun 07, 2022 |
| HP            | Pavilion dv6700             | Notebook    | [a688137dd3](https://linux-hardware.org/?probe=a688137dd3) | Jun 07, 2022 |
| Unknown       | Unknown                     | Notebook    | [c0625a957b](https://linux-hardware.org/?probe=c0625a957b) | Jun 06, 2022 |
| ASRock        | P67 Pro3                    | Desktop     | [30155bb328](https://linux-hardware.org/?probe=30155bb328) | Jun 06, 2022 |
| Lenovo        | SKYBAY No DPK               | All in one  | [c27da0faa9](https://linux-hardware.org/?probe=c27da0faa9) | Jun 06, 2022 |
| ASRock        | P67 Pro3                    | Desktop     | [a0cc6d57b8](https://linux-hardware.org/?probe=a0cc6d57b8) | Jun 06, 2022 |
| Dell          | Latitude 3190               | Notebook    | [190816b333](https://linux-hardware.org/?probe=190816b333) | Jun 06, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [fd5c0c6f83](https://linux-hardware.org/?probe=fd5c0c6f83) | Jun 06, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [cb81a60917](https://linux-hardware.org/?probe=cb81a60917) | Jun 05, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [aca6d1da03](https://linux-hardware.org/?probe=aca6d1da03) | Jun 05, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [c0eb59d595](https://linux-hardware.org/?probe=c0eb59d595) | Jun 05, 2022 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [8a23fb3b25](https://linux-hardware.org/?probe=8a23fb3b25) | Jun 05, 2022 |
| Dell          | Latitude E6430              | Notebook    | [95b7617708](https://linux-hardware.org/?probe=95b7617708) | Jun 05, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [80832b1c72](https://linux-hardware.org/?probe=80832b1c72) | Jun 05, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [51074b5c43](https://linux-hardware.org/?probe=51074b5c43) | Jun 05, 2022 |
| Unknown       | Unknown                     | Desktop     | [c6f9883076](https://linux-hardware.org/?probe=c6f9883076) | Jun 05, 2022 |
| MSI           | PR601/VR603                 | Notebook    | [9763977184](https://linux-hardware.org/?probe=9763977184) | Jun 05, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [bee0952f9d](https://linux-hardware.org/?probe=bee0952f9d) | Jun 05, 2022 |
| Fujitsu       | FMVA0800C                   | Notebook    | [bacd4a55bb](https://linux-hardware.org/?probe=bacd4a55bb) | Jun 05, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [07468743a9](https://linux-hardware.org/?probe=07468743a9) | Jun 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [4abb49be35](https://linux-hardware.org/?probe=4abb49be35) | Jun 04, 2022 |
| HP            | 8056                        | Desktop     | [a52dec67e2](https://linux-hardware.org/?probe=a52dec67e2) | Jun 04, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [4d3213676b](https://linux-hardware.org/?probe=4d3213676b) | Jun 04, 2022 |
| Gigabyte      | F2A88X-D3H                  | Desktop     | [5b7b255faf](https://linux-hardware.org/?probe=5b7b255faf) | Jun 04, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [8ac5eb21ad](https://linux-hardware.org/?probe=8ac5eb21ad) | Jun 04, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [8816abcee8](https://linux-hardware.org/?probe=8816abcee8) | Jun 03, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [fbfcffd093](https://linux-hardware.org/?probe=fbfcffd093) | Jun 03, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [ca44145e04](https://linux-hardware.org/?probe=ca44145e04) | Jun 03, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [ba5e3a5d77](https://linux-hardware.org/?probe=ba5e3a5d77) | Jun 02, 2022 |
| ASRock        | P67 Pro3                    | Desktop     | [be79ac4787](https://linux-hardware.org/?probe=be79ac4787) | Jun 02, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [2db8072ec9](https://linux-hardware.org/?probe=2db8072ec9) | Jun 02, 2022 |
| Dell          | 0GDG8Y A00                  | Desktop     | [ae659a73f9](https://linux-hardware.org/?probe=ae659a73f9) | Jun 02, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [5b88aad243](https://linux-hardware.org/?probe=5b88aad243) | Jun 02, 2022 |
| Lenovo        | ThinkPad P17 Gen 1 20SQS... | Notebook    | [491a4105d8](https://linux-hardware.org/?probe=491a4105d8) | Jun 01, 2022 |
| Dell          | Inspiron 5749               | Notebook    | [408e42beb8](https://linux-hardware.org/?probe=408e42beb8) | Jun 01, 2022 |
| ASRock        | P67 Pro3                    | Desktop     | [cd48749015](https://linux-hardware.org/?probe=cd48749015) | Jun 01, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [d12c2f9f7c](https://linux-hardware.org/?probe=d12c2f9f7c) | Jun 01, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [04e9ce0ba0](https://linux-hardware.org/?probe=04e9ce0ba0) | Jun 01, 2022 |
| Dell          | Inspiron 5521               | Notebook    | [4fdf9880d4](https://linux-hardware.org/?probe=4fdf9880d4) | May 31, 2022 |
| Huanan        | X99-F8 NALEX                | Desktop     | [5c3c77a5a0](https://linux-hardware.org/?probe=5c3c77a5a0) | May 31, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [1e6ab0f183](https://linux-hardware.org/?probe=1e6ab0f183) | May 31, 2022 |
| Huanan        | X99-F8 NALEX                | Desktop     | [11d242c4f4](https://linux-hardware.org/?probe=11d242c4f4) | May 31, 2022 |
| ASRock        | P67 Pro3                    | Desktop     | [0494b65f2c](https://linux-hardware.org/?probe=0494b65f2c) | May 31, 2022 |
| Dell          | 0J3C2F A02                  | Desktop     | [9ff329a1fd](https://linux-hardware.org/?probe=9ff329a1fd) | May 31, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [4df2d3c129](https://linux-hardware.org/?probe=4df2d3c129) | May 31, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [951bd2ea8d](https://linux-hardware.org/?probe=951bd2ea8d) | May 31, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [9b53c4df9d](https://linux-hardware.org/?probe=9b53c4df9d) | May 31, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [a08d3e5d4b](https://linux-hardware.org/?probe=a08d3e5d4b) | May 31, 2022 |
| Gigabyte      | EP45C-DS3R                  | Desktop     | [dc6dbe40d9](https://linux-hardware.org/?probe=dc6dbe40d9) | May 30, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [a6506e0582](https://linux-hardware.org/?probe=a6506e0582) | May 30, 2022 |
| Huanan        | X99-F8 NALEX                | Desktop     | [d6de670b16](https://linux-hardware.org/?probe=d6de670b16) | May 30, 2022 |
| Dell          | Latitude 5511               | Notebook    | [bc6fd9e79d](https://linux-hardware.org/?probe=bc6fd9e79d) | May 30, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [3192e3b512](https://linux-hardware.org/?probe=3192e3b512) | May 30, 2022 |
| Dell          | 0GWHMW A01                  | Desktop     | [f427859019](https://linux-hardware.org/?probe=f427859019) | May 30, 2022 |
| Dell          | Latitude 3190               | Notebook    | [e43c62a67a](https://linux-hardware.org/?probe=e43c62a67a) | May 30, 2022 |
| ASRock        | P67 Pro3                    | Desktop     | [e01dc9eb3d](https://linux-hardware.org/?probe=e01dc9eb3d) | May 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [c71a8e9817](https://linux-hardware.org/?probe=c71a8e9817) | May 29, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [bd36f27f9b](https://linux-hardware.org/?probe=bd36f27f9b) | May 29, 2022 |
| HP            | Compaq 6510b (KE135EA#AK... | Notebook    | [28c05654fc](https://linux-hardware.org/?probe=28c05654fc) | May 29, 2022 |
| MSI           | GP76 Leopard 10UE           | Notebook    | [9e74d767a6](https://linux-hardware.org/?probe=9e74d767a6) | May 29, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [8ad9f9f5d9](https://linux-hardware.org/?probe=8ad9f9f5d9) | May 29, 2022 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [8e577a4a1a](https://linux-hardware.org/?probe=8e577a4a1a) | May 29, 2022 |
| ASRock        | P67 Pro3                    | Desktop     | [40ac10c85e](https://linux-hardware.org/?probe=40ac10c85e) | May 29, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [a68b786241](https://linux-hardware.org/?probe=a68b786241) | May 29, 2022 |
| ASRock        | P67 Pro3                    | Desktop     | [bd8541bdaa](https://linux-hardware.org/?probe=bd8541bdaa) | May 28, 2022 |
| ASRock        | P67 Pro3                    | Desktop     | [79a9263b65](https://linux-hardware.org/?probe=79a9263b65) | May 28, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [cd40cf2e16](https://linux-hardware.org/?probe=cd40cf2e16) | May 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [ae044ab2d9](https://linux-hardware.org/?probe=ae044ab2d9) | May 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [b8c8e8baef](https://linux-hardware.org/?probe=b8c8e8baef) | May 27, 2022 |
| ASRock        | Z87 Extreme4                | Desktop     | [d3315c5c94](https://linux-hardware.org/?probe=d3315c5c94) | May 27, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [798f65546b](https://linux-hardware.org/?probe=798f65546b) | May 27, 2022 |
| Sony          | VPCEE3S1E                   | Notebook    | [f3c7988996](https://linux-hardware.org/?probe=f3c7988996) | May 27, 2022 |
| Dell          | 09M8Y8 A01                  | Desktop     | [7514f64b6e](https://linux-hardware.org/?probe=7514f64b6e) | May 26, 2022 |
| Dell          | 02P9X9 A05                  | Server      | [495ed7a7a4](https://linux-hardware.org/?probe=495ed7a7a4) | May 26, 2022 |
| Fujitsu       | D2759 S26361-D2759-A13 W... | Server      | [b4cf75e580](https://linux-hardware.org/?probe=b4cf75e580) | May 26, 2022 |
| Dell          | 0MY171 A01                  | Desktop     | [9500786a21](https://linux-hardware.org/?probe=9500786a21) | May 26, 2022 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | Notebook    | [cff9e3245c](https://linux-hardware.org/?probe=cff9e3245c) | May 25, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [29b8def5b3](https://linux-hardware.org/?probe=29b8def5b3) | May 25, 2022 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | Desktop     | [200070a992](https://linux-hardware.org/?probe=200070a992) | May 25, 2022 |
| Dell          | Latitude 5310               | Notebook    | [2117fbfccb](https://linux-hardware.org/?probe=2117fbfccb) | May 25, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [ea24b77e94](https://linux-hardware.org/?probe=ea24b77e94) | May 25, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [ce09b72069](https://linux-hardware.org/?probe=ce09b72069) | May 25, 2022 |
| Dell          | 0DT029 A00                  | Desktop     | [17b19530f5](https://linux-hardware.org/?probe=17b19530f5) | May 25, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [cee3591bcd](https://linux-hardware.org/?probe=cee3591bcd) | May 25, 2022 |
| Acer          | WG43M                       | Desktop     | [ae5adc512f](https://linux-hardware.org/?probe=ae5adc512f) | May 24, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [0517751353](https://linux-hardware.org/?probe=0517751353) | May 24, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [b253c6e007](https://linux-hardware.org/?probe=b253c6e007) | May 24, 2022 |
| Dell          | Latitude 5310               | Notebook    | [cb40714b3f](https://linux-hardware.org/?probe=cb40714b3f) | May 24, 2022 |
| Hardkernel    | ODROID-M1                   | Soc         | [16c06e9416](https://linux-hardware.org/?probe=16c06e9416) | May 24, 2022 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | Notebook    | [ed4df544d6](https://linux-hardware.org/?probe=ed4df544d6) | May 24, 2022 |
| HP            | Pavilion 15                 | Notebook    | [4140810d35](https://linux-hardware.org/?probe=4140810d35) | May 24, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [2f4c72e2a9](https://linux-hardware.org/?probe=2f4c72e2a9) | May 24, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [add67dab1a](https://linux-hardware.org/?probe=add67dab1a) | May 24, 2022 |
| ASUSTek       | B150M-A/M.2                 | Desktop     | [3aea6596c6](https://linux-hardware.org/?probe=3aea6596c6) | May 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [4e370a75aa](https://linux-hardware.org/?probe=4e370a75aa) | May 23, 2022 |
| HP            | 8158 A01                    | Mini pc     | [8a68f9f326](https://linux-hardware.org/?probe=8a68f9f326) | May 23, 2022 |
| HP            | 8158 A01                    | Mini pc     | [04bee24742](https://linux-hardware.org/?probe=04bee24742) | May 23, 2022 |
| Dell          | 02P9X9 A05                  | Server      | [9c274b7318](https://linux-hardware.org/?probe=9c274b7318) | May 23, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [f9e86bb522](https://linux-hardware.org/?probe=f9e86bb522) | May 23, 2022 |
| HP            | ProBook 6475b               | Notebook    | [5202cf8c75](https://linux-hardware.org/?probe=5202cf8c75) | May 23, 2022 |
| Fujitsu       | D2759 S26361-D2759-A13 W... | Server      | [f5aefeb81c](https://linux-hardware.org/?probe=f5aefeb81c) | May 23, 2022 |
| HP            | 1495                        | Desktop     | [adf94f2549](https://linux-hardware.org/?probe=adf94f2549) | May 23, 2022 |
| HP            | 1495                        | Desktop     | [be2c2cbd65](https://linux-hardware.org/?probe=be2c2cbd65) | May 23, 2022 |
| HP            | 1495                        | Desktop     | [9d476ad9d1](https://linux-hardware.org/?probe=9d476ad9d1) | May 23, 2022 |
| HP            | 1495                        | Desktop     | [61f2119a07](https://linux-hardware.org/?probe=61f2119a07) | May 23, 2022 |
| HP            | Pavilion 15                 | Notebook    | [ca77af8ab9](https://linux-hardware.org/?probe=ca77af8ab9) | May 23, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [f5ff0b74e4](https://linux-hardware.org/?probe=f5ff0b74e4) | May 23, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [9678842f4f](https://linux-hardware.org/?probe=9678842f4f) | May 23, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [f129f3b1d5](https://linux-hardware.org/?probe=f129f3b1d5) | May 22, 2022 |
| Lenovo        | ThinkPad T61 7661BM5        | Notebook    | [9a6d69d512](https://linux-hardware.org/?probe=9a6d69d512) | May 22, 2022 |
| Lenovo        | Yoga Slim 9 14ITL5 82D1     | Notebook    | [d728114b9b](https://linux-hardware.org/?probe=d728114b9b) | May 22, 2022 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | Desktop     | [70c677bafe](https://linux-hardware.org/?probe=70c677bafe) | May 22, 2022 |
| Acer          | Aspire E5-571G              | Notebook    | [8f47f3a71c](https://linux-hardware.org/?probe=8f47f3a71c) | May 22, 2022 |
| MSI           | Z97 GAMING 3                | Desktop     | [495bcbd710](https://linux-hardware.org/?probe=495bcbd710) | May 22, 2022 |
| MSI           | MS-7235                     | Desktop     | [cb9b6ded76](https://linux-hardware.org/?probe=cb9b6ded76) | May 22, 2022 |
| ASRock        | P67 Pro3                    | Desktop     | [6bb8448487](https://linux-hardware.org/?probe=6bb8448487) | May 22, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [1544360577](https://linux-hardware.org/?probe=1544360577) | May 22, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [ebf2b174b8](https://linux-hardware.org/?probe=ebf2b174b8) | May 22, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [04a8f20f28](https://linux-hardware.org/?probe=04a8f20f28) | May 21, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [38c450f343](https://linux-hardware.org/?probe=38c450f343) | May 21, 2022 |
| MSI           | MS-7235                     | Desktop     | [4dfaad64fd](https://linux-hardware.org/?probe=4dfaad64fd) | May 21, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [b6f469418c](https://linux-hardware.org/?probe=b6f469418c) | May 21, 2022 |
| ASRock        | P67 Pro3                    | Desktop     | [855045a0fa](https://linux-hardware.org/?probe=855045a0fa) | May 21, 2022 |
| Dell          | Latitude 5490               | Notebook    | [450756ee49](https://linux-hardware.org/?probe=450756ee49) | May 21, 2022 |
| ASRock        | P67 Pro3                    | Desktop     | [1cbf12b67a](https://linux-hardware.org/?probe=1cbf12b67a) | May 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [80d32848bf](https://linux-hardware.org/?probe=80d32848bf) | May 21, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [d14ff2c62e](https://linux-hardware.org/?probe=d14ff2c62e) | May 20, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [3f21c66d5c](https://linux-hardware.org/?probe=3f21c66d5c) | May 20, 2022 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | Desktop     | [73c9c54bb6](https://linux-hardware.org/?probe=73c9c54bb6) | May 20, 2022 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | Desktop     | [7dcdef576a](https://linux-hardware.org/?probe=7dcdef576a) | May 20, 2022 |
| HP            | EliteBook 850 G6            | Notebook    | [1b672f1faa](https://linux-hardware.org/?probe=1b672f1faa) | May 20, 2022 |
| HP            | EliteBook 850 G6            | Notebook    | [d2232927a7](https://linux-hardware.org/?probe=d2232927a7) | May 20, 2022 |
| Gigabyte      | B85M-D2V                    | Desktop     | [2bc6293c6a](https://linux-hardware.org/?probe=2bc6293c6a) | May 19, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [7a5744012f](https://linux-hardware.org/?probe=7a5744012f) | May 19, 2022 |
| HP            | 250 G4 Notebook PC          | Notebook    | [1472f65ca0](https://linux-hardware.org/?probe=1472f65ca0) | May 19, 2022 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [4a971be254](https://linux-hardware.org/?probe=4a971be254) | May 19, 2022 |
| Sony          | VGN-NR32L_S                 | Notebook    | [2709583292](https://linux-hardware.org/?probe=2709583292) | May 18, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [72747e63e5](https://linux-hardware.org/?probe=72747e63e5) | May 18, 2022 |
| HP            | 8054                        | Desktop     | [725f204fd0](https://linux-hardware.org/?probe=725f204fd0) | May 18, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [5e0b60c547](https://linux-hardware.org/?probe=5e0b60c547) | May 17, 2022 |
| Gigabyte      | B85M-D2V                    | Desktop     | [da9da96cda](https://linux-hardware.org/?probe=da9da96cda) | May 17, 2022 |
| Dell          | Latitude E6230              | Notebook    | [1afeba4362](https://linux-hardware.org/?probe=1afeba4362) | May 17, 2022 |
| Dell          | Inspiron 5735               | Notebook    | [b678e46de2](https://linux-hardware.org/?probe=b678e46de2) | May 17, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [1dbb37fcd0](https://linux-hardware.org/?probe=1dbb37fcd0) | May 17, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [1c9a384e09](https://linux-hardware.org/?probe=1c9a384e09) | May 17, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [d5477b3bb9](https://linux-hardware.org/?probe=d5477b3bb9) | May 17, 2022 |
| Sony          | VGN-FW51MF_H                | Notebook    | [084402167e](https://linux-hardware.org/?probe=084402167e) | May 17, 2022 |
| Toshiba       | Satellite L750D             | Notebook    | [6a84eb18c8](https://linux-hardware.org/?probe=6a84eb18c8) | May 16, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [798d2cee16](https://linux-hardware.org/?probe=798d2cee16) | May 16, 2022 |
| Dell          | Latitude 3190               | Notebook    | [e80556f7d6](https://linux-hardware.org/?probe=e80556f7d6) | May 16, 2022 |
| Dell          | 02P9X9 A05                  | Server      | [ecd211b72b](https://linux-hardware.org/?probe=ecd211b72b) | May 15, 2022 |
| Dell          | 02P9X9 A05                  | Server      | [182b2c11c5](https://linux-hardware.org/?probe=182b2c11c5) | May 15, 2022 |
| Dell          | Latitude 5580               | Notebook    | [c2f15d647a](https://linux-hardware.org/?probe=c2f15d647a) | May 15, 2022 |
| ASUSTek       | M4N68T-M-V2                 | Desktop     | [528659dab4](https://linux-hardware.org/?probe=528659dab4) | May 15, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [3589bb82ad](https://linux-hardware.org/?probe=3589bb82ad) | May 15, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [82b98a2f7e](https://linux-hardware.org/?probe=82b98a2f7e) | May 15, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [df38c8f603](https://linux-hardware.org/?probe=df38c8f603) | May 15, 2022 |
| HP            | Pavilion ZV6100 (EE984EA... | Notebook    | [59c5dbcb22](https://linux-hardware.org/?probe=59c5dbcb22) | May 15, 2022 |
| Lenovo        | ThinkPad T500 2241W2B       | Notebook    | [2bd7b2d9a4](https://linux-hardware.org/?probe=2bd7b2d9a4) | May 14, 2022 |
| Packard Be... | EasyNote ENTF71BM           | Notebook    | [e8808a770a](https://linux-hardware.org/?probe=e8808a770a) | May 14, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [5fad688f56](https://linux-hardware.org/?probe=5fad688f56) | May 14, 2022 |
| Dell          | 0HY9JP A02                  | Desktop     | [5f98aaf42c](https://linux-hardware.org/?probe=5f98aaf42c) | May 14, 2022 |
| Dell          | MXG061                      | Notebook    | [36b09ae01e](https://linux-hardware.org/?probe=36b09ae01e) | May 14, 2022 |
| HP            | 250 G4 Notebook PC          | Notebook    | [996bc01199](https://linux-hardware.org/?probe=996bc01199) | May 13, 2022 |
| Lenovo        | ThinkPad Edge E430 3254A... | Notebook    | [761f1a1cbd](https://linux-hardware.org/?probe=761f1a1cbd) | May 13, 2022 |
| Dell          | Inspiron 3541               | Notebook    | [7873185850](https://linux-hardware.org/?probe=7873185850) | May 12, 2022 |
| HP            | EliteBook 820 G1            | Notebook    | [dd51bb3592](https://linux-hardware.org/?probe=dd51bb3592) | May 12, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [c64195c6bb](https://linux-hardware.org/?probe=c64195c6bb) | May 12, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [a57e3f28c2](https://linux-hardware.org/?probe=a57e3f28c2) | May 12, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [1c124eec80](https://linux-hardware.org/?probe=1c124eec80) | May 12, 2022 |
| Lenovo        | ThinkPad X200 7458WAY       | Notebook    | [1d845e69bd](https://linux-hardware.org/?probe=1d845e69bd) | May 11, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [7d03983e37](https://linux-hardware.org/?probe=7d03983e37) | May 11, 2022 |
| Dell          | Precision 7530              | Notebook    | [d97721b6cf](https://linux-hardware.org/?probe=d97721b6cf) | May 11, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [5b2b56f445](https://linux-hardware.org/?probe=5b2b56f445) | May 11, 2022 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [b02040672d](https://linux-hardware.org/?probe=b02040672d) | May 11, 2022 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [1e1a8e1815](https://linux-hardware.org/?probe=1e1a8e1815) | May 10, 2022 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [56fc7bcca2](https://linux-hardware.org/?probe=56fc7bcca2) | May 10, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [bad0e8ce3b](https://linux-hardware.org/?probe=bad0e8ce3b) | May 10, 2022 |
| Lenovo        | Yoga 300-11IBY 80M0         | Notebook    | [af186fe9e3](https://linux-hardware.org/?probe=af186fe9e3) | May 10, 2022 |
| Lenovo        | Yoga 300-11IBY 80M0         | Notebook    | [b6fed1d4fe](https://linux-hardware.org/?probe=b6fed1d4fe) | May 10, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [5ccbf39183](https://linux-hardware.org/?probe=5ccbf39183) | May 10, 2022 |
| ASRock        | B660M-ITX/ac                | Desktop     | [88d7b71293](https://linux-hardware.org/?probe=88d7b71293) | May 10, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [015ede2e58](https://linux-hardware.org/?probe=015ede2e58) | May 09, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [840087bbed](https://linux-hardware.org/?probe=840087bbed) | May 09, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [9e81b04453](https://linux-hardware.org/?probe=9e81b04453) | May 09, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [d9779b1c50](https://linux-hardware.org/?probe=d9779b1c50) | May 09, 2022 |
| Dell          | 07T4MC A06                  | Desktop     | [34e338f194](https://linux-hardware.org/?probe=34e338f194) | May 09, 2022 |
| Dell          | MXG061                      | Notebook    | [119f6dd774](https://linux-hardware.org/?probe=119f6dd774) | May 09, 2022 |
| Google        | Relm                        | Notebook    | [37a9101768](https://linux-hardware.org/?probe=37a9101768) | May 09, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [c302d389bc](https://linux-hardware.org/?probe=c302d389bc) | May 08, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [81aa293c77](https://linux-hardware.org/?probe=81aa293c77) | May 08, 2022 |
| Dell          | Latitude E6220              | Notebook    | [f5ba7cbb31](https://linux-hardware.org/?probe=f5ba7cbb31) | May 08, 2022 |
| Dell          | Vostro 1440                 | Notebook    | [a44eb19e96](https://linux-hardware.org/?probe=a44eb19e96) | May 08, 2022 |
| Dell          | Vostro 1440                 | Notebook    | [356b0ae168](https://linux-hardware.org/?probe=356b0ae168) | May 08, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [8a5f88eca1](https://linux-hardware.org/?probe=8a5f88eca1) | May 08, 2022 |
| ASUSTek       | N76VZ                       | Notebook    | [f1e06f5c2f](https://linux-hardware.org/?probe=f1e06f5c2f) | May 08, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [9a1a0ce2f1](https://linux-hardware.org/?probe=9a1a0ce2f1) | May 08, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [880b5d5853](https://linux-hardware.org/?probe=880b5d5853) | May 07, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [027968f6e4](https://linux-hardware.org/?probe=027968f6e4) | May 07, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [72ae77348e](https://linux-hardware.org/?probe=72ae77348e) | May 07, 2022 |
| ASRock        | H270M Pro4                  | Desktop     | [7fb19cf73f](https://linux-hardware.org/?probe=7fb19cf73f) | May 07, 2022 |
| ASRock        | H270M Pro4                  | Desktop     | [1b6f35a5d0](https://linux-hardware.org/?probe=1b6f35a5d0) | May 07, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [ccb1cda445](https://linux-hardware.org/?probe=ccb1cda445) | May 06, 2022 |
| HP            | ProBook 4530s               | Notebook    | [76fc5ea6ce](https://linux-hardware.org/?probe=76fc5ea6ce) | May 06, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [adf601077e](https://linux-hardware.org/?probe=adf601077e) | May 06, 2022 |
| MSI           | B450-A PRO                  | Desktop     | [5b5ceb0f53](https://linux-hardware.org/?probe=5b5ceb0f53) | May 06, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [9f241088c2](https://linux-hardware.org/?probe=9f241088c2) | May 06, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [87e8930fcf](https://linux-hardware.org/?probe=87e8930fcf) | May 06, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [47982d615d](https://linux-hardware.org/?probe=47982d615d) | May 05, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [fb4cf43d54](https://linux-hardware.org/?probe=fb4cf43d54) | May 05, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [503e18f6cb](https://linux-hardware.org/?probe=503e18f6cb) | May 05, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [76d61df983](https://linux-hardware.org/?probe=76d61df983) | May 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [a9f5b77476](https://linux-hardware.org/?probe=a9f5b77476) | May 04, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [1d9a559405](https://linux-hardware.org/?probe=1d9a559405) | May 04, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [ee3b3dc380](https://linux-hardware.org/?probe=ee3b3dc380) | May 04, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [97185f1809](https://linux-hardware.org/?probe=97185f1809) | May 04, 2022 |
| Dell          | 0WR7PY A01                  | Desktop     | [9a18a890d4](https://linux-hardware.org/?probe=9a18a890d4) | May 03, 2022 |
| ASUSTek       | N76VZ                       | Notebook    | [b9c2a28ba0](https://linux-hardware.org/?probe=b9c2a28ba0) | May 03, 2022 |
| Lenovo        | ThinkPad T430 2349AK5       | Notebook    | [78f64f92f3](https://linux-hardware.org/?probe=78f64f92f3) | May 03, 2022 |
| ASUSTek       | X550CL                      | Notebook    | [b224821361](https://linux-hardware.org/?probe=b224821361) | May 03, 2022 |
| Toshiba       | Satellite C55t-C            | Notebook    | [7c1211e221](https://linux-hardware.org/?probe=7c1211e221) | May 02, 2022 |
| ASUSTek       | X705UAP                     | Notebook    | [5703c517d1](https://linux-hardware.org/?probe=5703c517d1) | May 02, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [d0b7db5920](https://linux-hardware.org/?probe=d0b7db5920) | May 02, 2022 |
| Acer          | Aspire E5-571G              | Notebook    | [8df6782398](https://linux-hardware.org/?probe=8df6782398) | May 02, 2022 |
| ASUSTek       | X550CL                      | Notebook    | [5340c940c2](https://linux-hardware.org/?probe=5340c940c2) | May 02, 2022 |
| ASUSTek       | X580VD                      | Notebook    | [920fb8f8d8](https://linux-hardware.org/?probe=920fb8f8d8) | May 01, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [112d0557c3](https://linux-hardware.org/?probe=112d0557c3) | May 01, 2022 |
| ASRock        | X370 Gaming X               | Desktop     | [b24677a908](https://linux-hardware.org/?probe=b24677a908) | May 01, 2022 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [6150343dc0](https://linux-hardware.org/?probe=6150343dc0) | May 01, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [317736e849](https://linux-hardware.org/?probe=317736e849) | May 01, 2022 |
| Gigabyte      | H310M S2P                   | Desktop     | [c5303ab540](https://linux-hardware.org/?probe=c5303ab540) | May 01, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [271a0aaed2](https://linux-hardware.org/?probe=271a0aaed2) | May 01, 2022 |
| Toshiba       | Satellite C55t-C            | Notebook    | [dd21a03b63](https://linux-hardware.org/?probe=dd21a03b63) | May 01, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [ea3bd2e330](https://linux-hardware.org/?probe=ea3bd2e330) | May 01, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [ac3f2c5c61](https://linux-hardware.org/?probe=ac3f2c5c61) | May 01, 2022 |
| Acer          | Extensa 5220                | Notebook    | [ebbd01171d](https://linux-hardware.org/?probe=ebbd01171d) | May 01, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [07e8a61019](https://linux-hardware.org/?probe=07e8a61019) | Apr 30, 2022 |
| Lenovo        | ThinkCentre M58 7627AD5     | Desktop     | [05a686b922](https://linux-hardware.org/?probe=05a686b922) | Apr 30, 2022 |
| ASUSTek       | UX303LAB                    | Notebook    | [4d47234d72](https://linux-hardware.org/?probe=4d47234d72) | Apr 30, 2022 |
| Intel         | DCP847SKE G80890-105        | Desktop     | [45dc47c8aa](https://linux-hardware.org/?probe=45dc47c8aa) | Apr 30, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [35b5fa2276](https://linux-hardware.org/?probe=35b5fa2276) | Apr 30, 2022 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [c2096251fc](https://linux-hardware.org/?probe=c2096251fc) | Apr 30, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [aab74c31b9](https://linux-hardware.org/?probe=aab74c31b9) | Apr 30, 2022 |
| ASUSTek       | X71Vn                       | Notebook    | [b31a7dce8b](https://linux-hardware.org/?probe=b31a7dce8b) | Apr 29, 2022 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [2c8a1c2444](https://linux-hardware.org/?probe=2c8a1c2444) | Apr 29, 2022 |
| Lenovo        | ThinkCentre M57 6072A5G     | Desktop     | [373677ac37](https://linux-hardware.org/?probe=373677ac37) | Apr 28, 2022 |
| ASRock        | G31M-S                      | Desktop     | [296df4a9d4](https://linux-hardware.org/?probe=296df4a9d4) | Apr 28, 2022 |
| Apple         | MacBook3,1                  | Notebook    | [5c90931c74](https://linux-hardware.org/?probe=5c90931c74) | Apr 28, 2022 |
| Lenovo        | ThinkPad Edge E430 3254A... | Notebook    | [00474d7e97](https://linux-hardware.org/?probe=00474d7e97) | Apr 28, 2022 |
| Lenovo        | SKYBAY No DPK               | All in one  | [41f38e1f81](https://linux-hardware.org/?probe=41f38e1f81) | Apr 28, 2022 |
| Lenovo        | ThinkPad Edge E430 3254A... | Notebook    | [3c9c9f209d](https://linux-hardware.org/?probe=3c9c9f209d) | Apr 28, 2022 |
| Dell          | Latitude 5420               | Notebook    | [26abde11eb](https://linux-hardware.org/?probe=26abde11eb) | Apr 28, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [2999ff1487](https://linux-hardware.org/?probe=2999ff1487) | Apr 28, 2022 |
| Dell          | 0J3C2F A00                  | Desktop     | [464c70eb8d](https://linux-hardware.org/?probe=464c70eb8d) | Apr 27, 2022 |
| Apple         | MacBook3,1                  | Notebook    | [c7da3d4c4f](https://linux-hardware.org/?probe=c7da3d4c4f) | Apr 27, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [d354934f98](https://linux-hardware.org/?probe=d354934f98) | Apr 27, 2022 |
| Acer          | Nitro AN515-43              | Notebook    | [99527fd065](https://linux-hardware.org/?probe=99527fd065) | Apr 26, 2022 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | Notebook    | [482bb47b36](https://linux-hardware.org/?probe=482bb47b36) | Apr 26, 2022 |
| HP            | EliteBook 8770w             | Notebook    | [4fa8e91f6d](https://linux-hardware.org/?probe=4fa8e91f6d) | Apr 26, 2022 |
| Dell          | Latitude 7520               | Notebook    | [674f3ca531](https://linux-hardware.org/?probe=674f3ca531) | Apr 26, 2022 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | Notebook    | [489a3a5798](https://linux-hardware.org/?probe=489a3a5798) | Apr 26, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [f37918f4d4](https://linux-hardware.org/?probe=f37918f4d4) | Apr 26, 2022 |
| Gigabyte      | Z590 D                      | Desktop     | [afad17a56d](https://linux-hardware.org/?probe=afad17a56d) | Apr 26, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [c854b74386](https://linux-hardware.org/?probe=c854b74386) | Apr 25, 2022 |
| Dell          | Precision 7510              | Notebook    | [484a851b85](https://linux-hardware.org/?probe=484a851b85) | Apr 25, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [06a00cfce7](https://linux-hardware.org/?probe=06a00cfce7) | Apr 25, 2022 |
| ASRock        | X570 Pro4                   | Desktop     | [678366aef2](https://linux-hardware.org/?probe=678366aef2) | Apr 25, 2022 |
| ASUSTek       | H81M-V3                     | Desktop     | [4d87f6f113](https://linux-hardware.org/?probe=4d87f6f113) | Apr 25, 2022 |
| HP            | Pavilion 17                 | Notebook    | [8a86695a31](https://linux-hardware.org/?probe=8a86695a31) | Apr 25, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [d4a06d7bbe](https://linux-hardware.org/?probe=d4a06d7bbe) | Apr 24, 2022 |
| Gigabyte      | H310M H                     | Desktop     | [5c94950753](https://linux-hardware.org/?probe=5c94950753) | Apr 24, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [6c64775a71](https://linux-hardware.org/?probe=6c64775a71) | Apr 24, 2022 |
| MSI           | PE60 2QE                    | Notebook    | [703b37d444](https://linux-hardware.org/?probe=703b37d444) | Apr 24, 2022 |
| HP            | 821D                        | Desktop     | [6a70c646a5](https://linux-hardware.org/?probe=6a70c646a5) | Apr 24, 2022 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [ac10947315](https://linux-hardware.org/?probe=ac10947315) | Apr 24, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [2b65eeae8d](https://linux-hardware.org/?probe=2b65eeae8d) | Apr 24, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [43098a1f34](https://linux-hardware.org/?probe=43098a1f34) | Apr 23, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [487f1a4924](https://linux-hardware.org/?probe=487f1a4924) | Apr 23, 2022 |
| Acer          | Aspire E1-531               | Notebook    | [c1cd0a61e1](https://linux-hardware.org/?probe=c1cd0a61e1) | Apr 23, 2022 |
| HP            | Pavilion 17                 | Notebook    | [851d01ca2e](https://linux-hardware.org/?probe=851d01ca2e) | Apr 23, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [e17b0d706a](https://linux-hardware.org/?probe=e17b0d706a) | Apr 23, 2022 |
| Lenovo        | ThinkPad 10 2nd 20E30013... | Tablet      | [0e7e04c683](https://linux-hardware.org/?probe=0e7e04c683) | Apr 22, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [0c301210d8](https://linux-hardware.org/?probe=0c301210d8) | Apr 22, 2022 |
| ASUSTek       | X541UJ                      | Notebook    | [4043c70a42](https://linux-hardware.org/?probe=4043c70a42) | Apr 22, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [3320719d25](https://linux-hardware.org/?probe=3320719d25) | Apr 22, 2022 |
| MSI           | GE60 2PC                    | Notebook    | [0614a4172b](https://linux-hardware.org/?probe=0614a4172b) | Apr 22, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | Notebook    | [b6a457c33a](https://linux-hardware.org/?probe=b6a457c33a) | Apr 21, 2022 |
| Gigabyte      | B450M GAMING                | Desktop     | [bf31ebdabe](https://linux-hardware.org/?probe=bf31ebdabe) | Apr 21, 2022 |
| Gigabyte      | Z170-Gaming K3              | Desktop     | [e21b7b0696](https://linux-hardware.org/?probe=e21b7b0696) | Apr 21, 2022 |
| Dell          | Latitude E6420              | Notebook    | [83b008961c](https://linux-hardware.org/?probe=83b008961c) | Apr 21, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [6af0b2a3c9](https://linux-hardware.org/?probe=6af0b2a3c9) | Apr 21, 2022 |
| MSI           | Z170A GAMING M3             | Desktop     | [84f6645ca5](https://linux-hardware.org/?probe=84f6645ca5) | Apr 20, 2022 |
| Samsung       | RC410/RC510/RC710           | Notebook    | [9adfada605](https://linux-hardware.org/?probe=9adfada605) | Apr 20, 2022 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [7beb17ef96](https://linux-hardware.org/?probe=7beb17ef96) | Apr 20, 2022 |
| Gigabyte      | H310M H                     | Desktop     | [9a462cda5a](https://linux-hardware.org/?probe=9a462cda5a) | Apr 20, 2022 |
| Gigabyte      | MZAPLBP-00                  | Desktop     | [62b2cada75](https://linux-hardware.org/?probe=62b2cada75) | Apr 20, 2022 |
| Dell          | Latitude E6420              | Notebook    | [85d321a02b](https://linux-hardware.org/?probe=85d321a02b) | Apr 20, 2022 |
| ASRock        | X470 Taichi Ultimate        | Desktop     | [a92dda8ded](https://linux-hardware.org/?probe=a92dda8ded) | Apr 20, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [b87e7c08ab](https://linux-hardware.org/?probe=b87e7c08ab) | Apr 19, 2022 |
| Lenovo        | ThinkStation C20 4263BA7    | Desktop     | [d162e9aa70](https://linux-hardware.org/?probe=d162e9aa70) | Apr 19, 2022 |
| HP            | ProBook 6440b               | Notebook    | [54a85fc99d](https://linux-hardware.org/?probe=54a85fc99d) | Apr 18, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [66ac59c0a3](https://linux-hardware.org/?probe=66ac59c0a3) | Apr 18, 2022 |
| Huanan        | X79 249PC V2.2              | Desktop     | [209e881793](https://linux-hardware.org/?probe=209e881793) | Apr 18, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [37fa300c26](https://linux-hardware.org/?probe=37fa300c26) | Apr 18, 2022 |
| Lenovo        | ThinkPad Edge E430 3254C... | Notebook    | [df0e3664e4](https://linux-hardware.org/?probe=df0e3664e4) | Apr 17, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [9ce44bf30d](https://linux-hardware.org/?probe=9ce44bf30d) | Apr 17, 2022 |
| MSI           | GF75 Thin 10UEK             | Notebook    | [866aa88f0f](https://linux-hardware.org/?probe=866aa88f0f) | Apr 17, 2022 |
| ASUSTek       | S551LB                      | Notebook    | [bb1d6d3623](https://linux-hardware.org/?probe=bb1d6d3623) | Apr 17, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [e28ee0bd42](https://linux-hardware.org/?probe=e28ee0bd42) | Apr 16, 2022 |
| HP            | Pavilion g6                 | Notebook    | [a7f800ed49](https://linux-hardware.org/?probe=a7f800ed49) | Apr 16, 2022 |
| Gigabyte      | G41MT-D3                    | Desktop     | [1785652200](https://linux-hardware.org/?probe=1785652200) | Apr 16, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [066d125002](https://linux-hardware.org/?probe=066d125002) | Apr 15, 2022 |
| Gigabyte      | EP31-DS3L                   | Desktop     | [a0a68f0980](https://linux-hardware.org/?probe=a0a68f0980) | Apr 15, 2022 |
| Gigabyte      | H370M DS3H-CF               | Desktop     | [c3eadb27ad](https://linux-hardware.org/?probe=c3eadb27ad) | Apr 15, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [254c1b1f97](https://linux-hardware.org/?probe=254c1b1f97) | Apr 15, 2022 |
| Acer          | Nitro AN515-42              | Notebook    | [f203fe95e5](https://linux-hardware.org/?probe=f203fe95e5) | Apr 15, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [8f490a29f3](https://linux-hardware.org/?probe=8f490a29f3) | Apr 15, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [77cf6f482e](https://linux-hardware.org/?probe=77cf6f482e) | Apr 15, 2022 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [13bfd82a49](https://linux-hardware.org/?probe=13bfd82a49) | Apr 14, 2022 |
| ASUSTek       | N61Jv                       | Notebook    | [959c5f2238](https://linux-hardware.org/?probe=959c5f2238) | Apr 14, 2022 |
| Sony          | VGN-FZ11M                   | Notebook    | [23731be3a1](https://linux-hardware.org/?probe=23731be3a1) | Apr 14, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [154eb4b040](https://linux-hardware.org/?probe=154eb4b040) | Apr 14, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [2decdc1731](https://linux-hardware.org/?probe=2decdc1731) | Apr 14, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [b8da99fd26](https://linux-hardware.org/?probe=b8da99fd26) | Apr 14, 2022 |
| Gigabyte      | Z690 AORUS MASTER           | Desktop     | [0f449aecbc](https://linux-hardware.org/?probe=0f449aecbc) | Apr 13, 2022 |
| Lenovo        | ThinkPad Edge E430 3254C... | Notebook    | [155a0f970f](https://linux-hardware.org/?probe=155a0f970f) | Apr 13, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [c8b5583e88](https://linux-hardware.org/?probe=c8b5583e88) | Apr 13, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [7e6cb72711](https://linux-hardware.org/?probe=7e6cb72711) | Apr 13, 2022 |
| Lenovo        | ThinkPad X260 20F5S4BY00    | Notebook    | [729b19eda3](https://linux-hardware.org/?probe=729b19eda3) | Apr 13, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [f2588a9d63](https://linux-hardware.org/?probe=f2588a9d63) | Apr 13, 2022 |
| Toshiba       | Satellite A300              | Notebook    | [1773d841d4](https://linux-hardware.org/?probe=1773d841d4) | Apr 13, 2022 |
| ASRock        | H97M Anniversary            | Desktop     | [4a73af14bf](https://linux-hardware.org/?probe=4a73af14bf) | Apr 13, 2022 |
| Dell          | Latitude E6420              | Notebook    | [7491167b48](https://linux-hardware.org/?probe=7491167b48) | Apr 13, 2022 |
| Dell          | Latitude E6420              | Notebook    | [3a6e6c7a62](https://linux-hardware.org/?probe=3a6e6c7a62) | Apr 13, 2022 |
| Dell          | Inspiron 17 7000 Series ... | Notebook    | [c8abf66820](https://linux-hardware.org/?probe=c8abf66820) | Apr 12, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [c3d7c67155](https://linux-hardware.org/?probe=c3d7c67155) | Apr 12, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [2202a95625](https://linux-hardware.org/?probe=2202a95625) | Apr 12, 2022 |
| Dell          | Latitude 5480               | Notebook    | [f733f24fdc](https://linux-hardware.org/?probe=f733f24fdc) | Apr 12, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [40d527cfe8](https://linux-hardware.org/?probe=40d527cfe8) | Apr 12, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [47cecc43f6](https://linux-hardware.org/?probe=47cecc43f6) | Apr 11, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [91037ebcec](https://linux-hardware.org/?probe=91037ebcec) | Apr 10, 2022 |
| Lenovo        | 3000 V200 076472G           | Notebook    | [11a06d9b03](https://linux-hardware.org/?probe=11a06d9b03) | Apr 10, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [7f5ccf9e6d](https://linux-hardware.org/?probe=7f5ccf9e6d) | Apr 10, 2022 |
| Dell          | 0HY9JP A02                  | Desktop     | [84b46b3236](https://linux-hardware.org/?probe=84b46b3236) | Apr 09, 2022 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [5b861faffd](https://linux-hardware.org/?probe=5b861faffd) | Apr 09, 2022 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | Desktop     | [73628a9025](https://linux-hardware.org/?probe=73628a9025) | Apr 09, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [68e49479b4](https://linux-hardware.org/?probe=68e49479b4) | Apr 09, 2022 |
| Gigabyte      | F2A88XN-WIFI                | Desktop     | [799106d1e6](https://linux-hardware.org/?probe=799106d1e6) | Apr 09, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [d42f8f3535](https://linux-hardware.org/?probe=d42f8f3535) | Apr 08, 2022 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [dc1db2125f](https://linux-hardware.org/?probe=dc1db2125f) | Apr 08, 2022 |
| Gigabyte      | TRX40 AORUS MASTER          | Desktop     | [cdf784520e](https://linux-hardware.org/?probe=cdf784520e) | Apr 08, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [414464db43](https://linux-hardware.org/?probe=414464db43) | Apr 08, 2022 |
| Dell          | 0804P1 A05                  | Server      | [24b220fddb](https://linux-hardware.org/?probe=24b220fddb) | Apr 08, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [76ed100020](https://linux-hardware.org/?probe=76ed100020) | Apr 08, 2022 |
| Dell          | Latitude 5480               | Notebook    | [6891954221](https://linux-hardware.org/?probe=6891954221) | Apr 08, 2022 |
| Dell          | Inspiron 5515               | Notebook    | [de3e7023c4](https://linux-hardware.org/?probe=de3e7023c4) | Apr 08, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [b929783867](https://linux-hardware.org/?probe=b929783867) | Apr 08, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [556d9d27ef](https://linux-hardware.org/?probe=556d9d27ef) | Apr 07, 2022 |
| Dell          | Latitude E4310              | Notebook    | [e89d84e0dd](https://linux-hardware.org/?probe=e89d84e0dd) | Apr 07, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [691c061ef4](https://linux-hardware.org/?probe=691c061ef4) | Apr 07, 2022 |
| Dell          | Latitude 5521               | Notebook    | [ce1e3c5551](https://linux-hardware.org/?probe=ce1e3c5551) | Apr 07, 2022 |
| Dell          | Latitude 5480               | Notebook    | [4e82478bdf](https://linux-hardware.org/?probe=4e82478bdf) | Apr 07, 2022 |
| Dell          | MXG061                      | Notebook    | [3ff1cc3367](https://linux-hardware.org/?probe=3ff1cc3367) | Apr 07, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [94f4873110](https://linux-hardware.org/?probe=94f4873110) | Apr 06, 2022 |
| Dell          | MXG061                      | Notebook    | [9c91bd9487](https://linux-hardware.org/?probe=9c91bd9487) | Apr 06, 2022 |
| ASUSTek       | VivoBook E14 E402YA_E402... | Notebook    | [9536873aca](https://linux-hardware.org/?probe=9536873aca) | Apr 06, 2022 |
| Acer          | Aspire E5-774G              | Notebook    | [2e61b0b4d5](https://linux-hardware.org/?probe=2e61b0b4d5) | Apr 05, 2022 |
| Intel         | DH55TC AAE70932-204         | Desktop     | [336fcaa613](https://linux-hardware.org/?probe=336fcaa613) | Apr 05, 2022 |
| Apple         | MacBookAir4,2               | Notebook    | [0c1f8b4efe](https://linux-hardware.org/?probe=0c1f8b4efe) | Apr 05, 2022 |
| Dell          | 0HY9JP A02                  | Desktop     | [ed1cda9998](https://linux-hardware.org/?probe=ed1cda9998) | Apr 05, 2022 |
| Gigabyte      | G31M-S2L                    | Desktop     | [7842a96018](https://linux-hardware.org/?probe=7842a96018) | Apr 05, 2022 |
| Gigabyte      | H97M-HD3                    | Desktop     | [fc7b16c289](https://linux-hardware.org/?probe=fc7b16c289) | Apr 05, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [d85f7abf8c](https://linux-hardware.org/?probe=d85f7abf8c) | Apr 05, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [81165aa277](https://linux-hardware.org/?probe=81165aa277) | Apr 05, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [d51c68f84e](https://linux-hardware.org/?probe=d51c68f84e) | Apr 05, 2022 |
| Acer          | TravelMate P215-41-G2       | Notebook    | [4e35add210](https://linux-hardware.org/?probe=4e35add210) | Apr 04, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [37b0484558](https://linux-hardware.org/?probe=37b0484558) | Apr 04, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [afc10b77f7](https://linux-hardware.org/?probe=afc10b77f7) | Apr 04, 2022 |
| Dell          | Latitude 5421               | Notebook    | [78ac6f00cd](https://linux-hardware.org/?probe=78ac6f00cd) | Apr 04, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [44a524bb2f](https://linux-hardware.org/?probe=44a524bb2f) | Apr 03, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [359bb41911](https://linux-hardware.org/?probe=359bb41911) | Apr 03, 2022 |
| Dell          | 0NDYHG A01                  | Desktop     | [26629406de](https://linux-hardware.org/?probe=26629406de) | Apr 03, 2022 |
| Gigabyte      | B450M S2H V2                | Desktop     | [f3fde51c72](https://linux-hardware.org/?probe=f3fde51c72) | Apr 03, 2022 |
| Acer          | Nitro AN515-43              | Notebook    | [e6e1af5316](https://linux-hardware.org/?probe=e6e1af5316) | Apr 03, 2022 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | Desktop     | [01c14c16ca](https://linux-hardware.org/?probe=01c14c16ca) | Apr 03, 2022 |
| HP            | Unknown                     | Notebook    | [e33741c278](https://linux-hardware.org/?probe=e33741c278) | Apr 03, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | Convertible | [6a09ec0e6a](https://linux-hardware.org/?probe=6a09ec0e6a) | Apr 03, 2022 |
| HP            | Pavilion g6                 | Notebook    | [6f774cb7a9](https://linux-hardware.org/?probe=6f774cb7a9) | Apr 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [f6bc1c6219](https://linux-hardware.org/?probe=f6bc1c6219) | Apr 03, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [51980559c7](https://linux-hardware.org/?probe=51980559c7) | Apr 03, 2022 |
| ASRock        | X370 Killer SLI             | Desktop     | [ffb866117c](https://linux-hardware.org/?probe=ffb866117c) | Apr 02, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [f13dbb1e06](https://linux-hardware.org/?probe=f13dbb1e06) | Apr 02, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [bd717d57c2](https://linux-hardware.org/?probe=bd717d57c2) | Apr 02, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [a7d794c2d8](https://linux-hardware.org/?probe=a7d794c2d8) | Apr 02, 2022 |
| HP            | Unknown                     | Notebook    | [761f0c08b2](https://linux-hardware.org/?probe=761f0c08b2) | Apr 02, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [ca95a8324a](https://linux-hardware.org/?probe=ca95a8324a) | Apr 02, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [a6f8e740aa](https://linux-hardware.org/?probe=a6f8e740aa) | Apr 02, 2022 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | Notebook    | [f1ceaa5222](https://linux-hardware.org/?probe=f1ceaa5222) | Apr 02, 2022 |
| Lenovo        | Legion 7 16ACHg6 82N6       | Notebook    | [ce4341b7b1](https://linux-hardware.org/?probe=ce4341b7b1) | Apr 01, 2022 |
| HP            | EliteBook 820 G2            | Notebook    | [5308b25e76](https://linux-hardware.org/?probe=5308b25e76) | Mar 31, 2022 |
| ASRock        | Z390 Taichi                 | Desktop     | [b5995c13e5](https://linux-hardware.org/?probe=b5995c13e5) | Mar 31, 2022 |
| ASRock        | Z390 Taichi                 | Desktop     | [308ec93236](https://linux-hardware.org/?probe=308ec93236) | Mar 31, 2022 |
| Intel         | DH55TC AAE70932-204         | Desktop     | [5b54f9a1e1](https://linux-hardware.org/?probe=5b54f9a1e1) | Mar 31, 2022 |
| MSI           | P45 Neo2-FR                 | Desktop     | [23fa0ec187](https://linux-hardware.org/?probe=23fa0ec187) | Mar 31, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [eeb03a5d88](https://linux-hardware.org/?probe=eeb03a5d88) | Mar 31, 2022 |
| Valve         | Jupiter                     | Notebook    | [d8625616de](https://linux-hardware.org/?probe=d8625616de) | Mar 30, 2022 |
| Acer          | Nitro AN515-43              | Notebook    | [d1c02dfaee](https://linux-hardware.org/?probe=d1c02dfaee) | Mar 29, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [fc7ebbef4e](https://linux-hardware.org/?probe=fc7ebbef4e) | Mar 29, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [ab2bed88a7](https://linux-hardware.org/?probe=ab2bed88a7) | Mar 29, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [426b141f91](https://linux-hardware.org/?probe=426b141f91) | Mar 29, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [5240890472](https://linux-hardware.org/?probe=5240890472) | Mar 29, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [405fedcff9](https://linux-hardware.org/?probe=405fedcff9) | Mar 28, 2022 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [18a5e10a64](https://linux-hardware.org/?probe=18a5e10a64) | Mar 28, 2022 |
| ASUSTek       | UX310UA                     | Notebook    | [b052cccfb8](https://linux-hardware.org/?probe=b052cccfb8) | Mar 27, 2022 |
| ASUSTek       | P7H55                       | Desktop     | [12a9db8849](https://linux-hardware.org/?probe=12a9db8849) | Mar 27, 2022 |
| Dell          | MXG071                      | Notebook    | [ac0158dcb9](https://linux-hardware.org/?probe=ac0158dcb9) | Mar 27, 2022 |
| Dell          | 0HY9JP A02                  | Desktop     | [693b66ce17](https://linux-hardware.org/?probe=693b66ce17) | Mar 27, 2022 |
| Gigabyte      | M61VME-S2                   | Desktop     | [4e68853105](https://linux-hardware.org/?probe=4e68853105) | Mar 27, 2022 |
| AMD           | 970A-D3                     | Desktop     | [010b978f01](https://linux-hardware.org/?probe=010b978f01) | Mar 26, 2022 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [fb365f1b1e](https://linux-hardware.org/?probe=fb365f1b1e) | Mar 26, 2022 |
| Dell          | Inspiron 5758               | Notebook    | [ddd5e24256](https://linux-hardware.org/?probe=ddd5e24256) | Mar 26, 2022 |
| MAXDATA       | ECO4510IW                   | Notebook    | [d731c99bf8](https://linux-hardware.org/?probe=d731c99bf8) | Mar 26, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [c53b2decec](https://linux-hardware.org/?probe=c53b2decec) | Mar 26, 2022 |
| ASRock        | P67 Pro3                    | Desktop     | [515f03c954](https://linux-hardware.org/?probe=515f03c954) | Mar 26, 2022 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [d8b099aefa](https://linux-hardware.org/?probe=d8b099aefa) | Mar 26, 2022 |
| MSI           | H170 GAMING M3              | Desktop     | [6467169a74](https://linux-hardware.org/?probe=6467169a74) | Mar 26, 2022 |
| Dell          | Latitude E7450              | Notebook    | [db931ebb1f](https://linux-hardware.org/?probe=db931ebb1f) | Mar 25, 2022 |
| MSI           | H170 GAMING M3              | Desktop     | [e1aeadc089](https://linux-hardware.org/?probe=e1aeadc089) | Mar 25, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [023e66a08d](https://linux-hardware.org/?probe=023e66a08d) | Mar 25, 2022 |
| Dell          | Latitude 5420               | Notebook    | [fed42f2345](https://linux-hardware.org/?probe=fed42f2345) | Mar 25, 2022 |
| Dell          | 00V62H A01                  | Desktop     | [309ea240bd](https://linux-hardware.org/?probe=309ea240bd) | Mar 25, 2022 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [2a51a62d10](https://linux-hardware.org/?probe=2a51a62d10) | Mar 25, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [744a69ec7d](https://linux-hardware.org/?probe=744a69ec7d) | Mar 25, 2022 |
| HP            | ProBook 6570b               | Notebook    | [41548696b7](https://linux-hardware.org/?probe=41548696b7) | Mar 23, 2022 |
| HP            | Pavilion ZV6100 (EE984EA... | Notebook    | [282dfe7eb0](https://linux-hardware.org/?probe=282dfe7eb0) | Mar 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [f7f7b2d459](https://linux-hardware.org/?probe=f7f7b2d459) | Mar 22, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [b2d23b47a5](https://linux-hardware.org/?probe=b2d23b47a5) | Mar 22, 2022 |
| ASUSTek       | B150I PRO GAMING/AURA       | Desktop     | [0839d5feb0](https://linux-hardware.org/?probe=0839d5feb0) | Mar 22, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [188fb139c3](https://linux-hardware.org/?probe=188fb139c3) | Mar 21, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Poland/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 564       | 13.68%  |
| OpenMandriva 4.2             | 309       | 7.49%   |
| Ubuntu 18.04                 | 279       | 6.77%   |
| OpenMandriva 4.3             | 164       | 3.98%   |
| ROSA R10                     | 98        | 2.38%   |
| Debian 11                    | 93        | 2.26%   |
| Ubuntu 22.04                 | 83        | 2.01%   |
| Arch Rolling                 | 81        | 1.96%   |
| ROSA R9                      | 70        | 1.7%    |
| ROSA R11                     | 69        | 1.67%   |
| Arch                         | 68        | 1.65%   |
| Linux Mint 20.1              | 66        | 1.6%    |
| Linux Mint 20.3              | 63        | 1.53%   |
| KDE neon 20.04               | 62        | 1.5%    |
| ROSA R11.1                   | 58        | 1.41%   |
| Manjaro                      | 58        | 1.41%   |
| Ubuntu 20.10                 | 56        | 1.36%   |
| Linux Mint 20.2              | 51        | 1.24%   |
| Ubuntu 21.04                 | 50        | 1.21%   |
| Ubuntu 19.10                 | 48        | 1.16%   |
| Linux Mint 20                | 48        | 1.16%   |
| Linux Mint 19.3              | 47        | 1.14%   |
| Zorin 16                     | 45        | 1.09%   |
| Fedora 36                    | 45        | 1.09%   |
| Ubuntu 21.10                 | 44        | 1.07%   |
| ROSA R8                      | 42        | 1.02%   |
| Fedora 35                    | 42        | 1.02%   |
| Fedora 33                    | 41        | 0.99%   |
| Xubuntu 20.04                | 38        | 0.92%   |
| Fedora 34                    | 38        | 0.92%   |
| Fedora 32                    | 38        | 0.92%   |
| Debian 10                    | 37        | 0.9%    |
| ROSA R8.1                    | 36        | 0.87%   |
| Zorin 15                     | 35        | 0.85%   |
| Pop!_OS 20.04                | 35        | 0.85%   |
| Ubuntu 19.04                 | 33        | 0.8%    |
| Kubuntu 20.04                | 33        | 0.8%    |
| Fedora 31                    | 30        | 0.73%   |
| Pop!_OS 20.10                | 26        | 0.63%   |
| openSUSE Tumbleweed-XXXXXXXX | 24        | 0.58%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1130      | 29.37%  |
| OpenMandriva  | 503       | 13.07%  |
| ROSA          | 322       | 8.37%   |
| Linux Mint    | 301       | 7.82%   |
| Fedora        | 228       | 5.93%   |
| Manjaro       | 167       | 4.34%   |
| Debian        | 158       | 4.11%   |
| Arch          | 146       | 3.79%   |
| Pop!_OS       | 111       | 2.88%   |
| Zorin         | 84        | 2.18%   |
| KDE neon      | 73        | 1.9%    |
| Kubuntu       | 70        | 1.82%   |
| Xubuntu       | 65        | 1.69%   |
| Gentoo        | 38        | 0.99%   |
| Endless       | 34        | 0.88%   |
| Kali          | 32        | 0.83%   |
| openSUSE      | 30        | 0.78%   |
| Lubuntu       | 27        | 0.7%    |
| Elementary    | 27        | 0.7%    |
| ArcoLinux     | 24        | 0.62%   |
| LMDE          | 20        | 0.52%   |
| EndeavourOS   | 19        | 0.49%   |
| Clear Linux   | 19        | 0.49%   |
| BlackPanther  | 17        | 0.44%   |
| Ubuntu Unity  | 14        | 0.36%   |
| Ubuntu MATE   | 13        | 0.34%   |
| CentOS        | 13        | 0.34%   |
| Ubuntu Budgie | 10        | 0.26%   |
| MX            | 10        | 0.26%   |
| LinuxFX       | 10        | 0.26%   |
| Garuda Linux  | 9         | 0.23%   |
| Raspbian      | 8         | 0.21%   |
| Peppermint    | 7         | 0.18%   |
| NixOS         | 7         | 0.18%   |
| SteamOS       | 6         | 0.16%   |
| Linux Lite    | 6         | 0.16%   |
| Xero          | 5         | 0.13%   |
| RHEL          | 5         | 0.13%   |
| Android       | 5         | 0.13%   |
| Void Linux    | 4         | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002        | 295       | 6.43%   |
| 5.16.7-desktop-1omv4003         | 156       | 3.4%    |
| 5.4.0-42-generic                | 78        | 1.7%    |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 54        | 1.18%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 53        | 1.16%   |
| 5.4.0-26-generic                | 40        | 0.87%   |
| 4.15.0-desktop-45.1rosa-x86_64  | 39        | 0.85%   |
| 5.4.0-52-generic                | 38        | 0.83%   |
| 5.4.0-48-generic                | 36        | 0.79%   |
| 5.4.0-58-generic                | 33        | 0.72%   |
| 5.4.0-29-generic                | 30        | 0.65%   |
| 5.3.0-46-generic                | 30        | 0.65%   |
| 5.4.0-54-generic                | 28        | 0.61%   |
| 5.13.0-39-generic               | 27        | 0.59%   |
| 5.11.0-37-generic               | 27        | 0.59%   |
| 5.8.0-43-generic                | 26        | 0.57%   |
| 5.4.0-40-generic                | 26        | 0.57%   |
| 5.4.0-37-generic                | 25        | 0.55%   |
| 4.1.34-nrj-desktop-2rosa-x86_64 | 24        | 0.52%   |
| 5.4.0-33-generic                | 23        | 0.5%    |
| 5.13.0-27-generic               | 23        | 0.5%    |
| 5.4.0-66-generic                | 22        | 0.48%   |
| 5.3.0-42-generic                | 22        | 0.48%   |
| 5.11.0-27-generic               | 22        | 0.48%   |
| 5.0.0-37-generic                | 22        | 0.48%   |
| 5.15.0-43-generic               | 21        | 0.46%   |
| 5.8.0-48-generic                | 20        | 0.44%   |
| 5.4.0-65-generic                | 20        | 0.44%   |
| 5.4.0-56-generic                | 20        | 0.44%   |
| 5.13.0-40-generic               | 20        | 0.44%   |
| 5.4.0-91-generic                | 19        | 0.41%   |
| 5.8.0-53-generic                | 18        | 0.39%   |
| 5.4.0-74-generic                | 18        | 0.39%   |
| 5.4.0-53-generic                | 18        | 0.39%   |
| 5.3.0-40-generic                | 18        | 0.39%   |
| 5.11.0-38-generic               | 18        | 0.39%   |
| 4.15.0-43-generic               | 18        | 0.39%   |
| 4.1.38-nrj-desktop-2rosa-x86_64 | 18        | 0.39%   |
| 5.8.0-50-generic                | 17        | 0.37%   |
| 5.4.0-72-generic                | 17        | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 735       | 17.05%  |
| 5.10.14 | 297       | 6.89%   |
| 4.15.0  | 281       | 6.52%   |
| 5.11.0  | 220       | 5.1%    |
| 5.8.0   | 219       | 5.08%   |
| 5.13.0  | 186       | 4.31%   |
| 5.3.0   | 166       | 3.85%   |
| 5.16.7  | 159       | 3.69%   |
| 5.15.0  | 140       | 3.25%   |
| 5.10.0  | 103       | 2.39%   |
| 5.0.0   | 101       | 2.34%   |
| 4.18.0  | 88        | 2.04%   |
| 4.9.60  | 66        | 1.53%   |
| 4.9.20  | 62        | 1.44%   |
| 4.19.0  | 51        | 1.18%   |
| 4.1.34  | 32        | 0.74%   |
| 4.1.38  | 28        | 0.65%   |
| 5.14.0  | 24        | 0.56%   |
| 5.17.5  | 19        | 0.44%   |
| 5.9.0   | 18        | 0.42%   |
| 5.4.32  | 17        | 0.39%   |
| 5.11.12 | 17        | 0.39%   |
| 4.9.76  | 16        | 0.37%   |
| 4.9.124 | 16        | 0.37%   |
| 4.9.155 | 14        | 0.32%   |
| 5.6.0   | 13        | 0.3%    |
| 5.17.0  | 13        | 0.3%    |
| 5.15.12 | 13        | 0.3%    |
| 5.12.4  | 12        | 0.28%   |
| 5.9.16  | 11        | 0.26%   |
| 5.4.83  | 11        | 0.26%   |
| 5.15.32 | 11        | 0.26%   |
| 4.18.16 | 11        | 0.26%   |
| 5.9.1   | 10        | 0.23%   |
| 5.16.0  | 10        | 0.23%   |
| 5.15.11 | 10        | 0.23%   |
| 5.11.16 | 10        | 0.23%   |
| 5.10.74 | 10        | 0.23%   |
| 4.9.95  | 10        | 0.23%   |
| 5.6.6   | 9         | 0.21%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 832       | 19.87%  |
| 5.10    | 509       | 12.15%  |
| 5.11    | 284       | 6.78%   |
| 4.15    | 281       | 6.71%   |
| 5.8     | 277       | 6.61%   |
| 5.15    | 257       | 6.14%   |
| 5.16    | 238       | 5.68%   |
| 5.13    | 216       | 5.16%   |
| 5.3     | 185       | 4.42%   |
| 4.9     | 181       | 4.32%   |
| 5.0     | 111       | 2.65%   |
| 4.18    | 100       | 2.39%   |
| 5.17    | 76        | 1.81%   |
| 5.14    | 76        | 1.81%   |
| 5.9     | 74        | 1.77%   |
| 5.6     | 69        | 1.65%   |
| 5.18    | 65        | 1.55%   |
| 4.19    | 64        | 1.53%   |
| 4.1     | 63        | 1.5%    |
| 5.12    | 60        | 1.43%   |
| 5.5     | 39        | 0.93%   |
| 5.7     | 35        | 0.84%   |
| 5.19    | 32        | 0.76%   |
| 4.4     | 16        | 0.38%   |
| 5.1     | 8         | 0.19%   |
| 3.10    | 7         | 0.17%   |
| 5.2     | 4         | 0.1%    |
| 4.20    | 4         | 0.1%    |
| 4.16    | 3         | 0.07%   |
| 4.13    | 3         | 0.07%   |
| 6.0     | 2         | 0.05%   |
| 4.8     | 2         | 0.05%   |
| 4.7     | 2         | 0.05%   |
| 4.14    | 2         | 0.05%   |
| 4.12    | 2         | 0.05%   |
| 4.10    | 2         | 0.05%   |
| 3.18    | 2         | 0.05%   |
| 4.17    | 1         | 0.02%   |
| 4.11    | 1         | 0.02%   |
| 3.16    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 3527      | 95.02%  |
| i686    | 142       | 3.83%   |
| aarch64 | 21        | 0.57%   |
| armv7l  | 15        | 0.4%    |
| armv8l  | 3         | 0.08%   |
| armv6l  | 2         | 0.05%   |
| ppc64   | 1         | 0.03%   |
| ppc     | 1         | 0.03%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 1377      | 35.19%  |
| KDE5            | 935       | 23.89%  |
| Unknown         | 458       | 11.7%   |
| XFCE            | 270       | 6.9%    |
| X-Cinnamon      | 199       | 5.09%   |
| KDE4            | 175       | 4.47%   |
| KDE             | 124       | 3.17%   |
| MATE            | 85        | 2.17%   |
| Cinnamon        | 62        | 1.58%   |
| LXQt            | 46        | 1.18%   |
| LXDE            | 41        | 1.05%   |
| i3              | 26        | 0.66%   |
| Pantheon        | 25        | 0.64%   |
| Budgie          | 17        | 0.43%   |
| Unity           | 16        | 0.41%   |
| Deepin          | 16        | 0.41%   |
| GNOME Flashback | 9         | 0.23%   |
| GNOME Classic   | 5         | 0.13%   |
| awesome         | 5         | 0.13%   |
| qtile           | 4         | 0.1%    |
| openbox         | 3         | 0.08%   |
| fluxbox         | 3         | 0.08%   |
| DWM             | 3         | 0.08%   |
| trinity         | 2         | 0.05%   |
| sway            | 2         | 0.05%   |
| stumpwm         | 1         | 0.03%   |
| qt5ct           | 1         | 0.03%   |
| jwm             | 1         | 0.03%   |
| ICEWM           | 1         | 0.03%   |
| GNUstep         | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 3152      | 82.62%  |
| Wayland | 370       | 9.7%    |
| Unknown | 220       | 5.77%   |
| Tty     | 73        | 1.91%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1735      | 44.61%  |
| SDDM    | 906       | 23.3%   |
| GDM     | 434       | 11.16%  |
| LightDM | 257       | 6.61%   |
| GDM3    | 200       | 5.14%   |
| KDM     | 185       | 4.76%   |
| TDM     | 152       | 3.91%   |
| XDM     | 10        | 0.26%   |
| Ly      | 3         | 0.08%   |
| SLiM    | 2         | 0.05%   |
| MDM     | 2         | 0.05%   |
| LXDM    | 2         | 0.05%   |
| SLIMSKI | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| pl_PL      | 2064      | 53.54%  |
| en_US      | 896       | 23.24%  |
| Unknown    | 642       | 16.65%  |
| en_GB      | 111       | 2.88%   |
| C          | 64        | 1.66%   |
| ru_RU      | 18        | 0.47%   |
| szl_PL     | 11        | 0.29%   |
| en_CA      | 7         | 0.18%   |
| de_DE      | 5         | 0.13%   |
| uk_UA      | 4         | 0.1%    |
| fr_FR      | 4         | 0.1%    |
| en_IE      | 4         | 0.1%    |
| ru_UA      | 3         | 0.08%   |
| en_DK      | 3         | 0.08%   |
| C.UTF8     | 3         | 0.08%   |
| nl_NL      | 2         | 0.05%   |
| it_IT      | 2         | 0.05%   |
| en_IN      | 2         | 0.05%   |
| en_AG      | 2         | 0.05%   |
| sv_SE      | 1         | 0.03%   |
| sk_SK      | 1         | 0.03%   |
| hu_HU      | 1         | 0.03%   |
| es_ES      | 1         | 0.03%   |
| en_US.UTF8 | 1         | 0.03%   |
| en_AU      | 1         | 0.03%   |
| el_GR      | 1         | 0.03%   |
| af_ZA      | 1         | 0.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2162      | 57.01%  |
| EFI  | 1630      | 42.99%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 2652      | 69.17%  |
| Overlay  | 505       | 13.17%  |
| Unknown  | 297       | 7.75%   |
| Btrfs    | 264       | 6.89%   |
| Xfs      | 54        | 1.41%   |
| Zfs      | 24        | 0.63%   |
| F2fs     | 16        | 0.42%   |
| Tmpfs    | 6         | 0.16%   |
| Ext3     | 5         | 0.13%   |
| Ext2     | 5         | 0.13%   |
| XXXXX    | 1         | 0.03%   |
| SquXshfs | 1         | 0.03%   |
| Rootfs   | 1         | 0.03%   |
| Jfs      | 1         | 0.03%   |
| Bcachefs | 1         | 0.03%   |
| Aufs     | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1976      | 51.75%  |
| GPT     | 1165      | 30.51%  |
| MBR     | 677       | 17.73%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3106      | 81.76%  |
| Yes       | 693       | 18.24%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2470      | 65.24%  |
| Yes       | 1316      | 34.76%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 647       | 17.47%  |
| Dell                    | 584       | 15.77%  |
| ASUSTek Computer        | 574       | 15.5%   |
| Hewlett-Packard         | 440       | 11.88%  |
| Gigabyte Technology     | 353       | 9.53%   |
| MSI                     | 286       | 7.72%   |
| Acer                    | 157       | 4.24%   |
| ASRock                  | 135       | 3.65%   |
| Toshiba                 | 65        | 1.76%   |
| Samsung Electronics     | 64        | 1.73%   |
| Fujitsu                 | 41        | 1.11%   |
| Sony                    | 31        | 0.84%   |
| Fujitsu Siemens         | 31        | 0.84%   |
| Apple                   | 25        | 0.68%   |
| Intel                   | 22        | 0.59%   |
| HUAWEI                  | 21        | 0.57%   |
| Raspberry Pi Foundation | 20        | 0.54%   |
| Unknown                 | 15        | 0.41%   |
| Packard Bell            | 12        | 0.32%   |
| Medion                  | 12        | 0.32%   |
| Notebook                | 11        | 0.3%    |
| eMachines               | 9         | 0.24%   |
| Google                  | 8         | 0.22%   |
| Foxconn                 | 8         | 0.22%   |
| AMI                     | 7         | 0.19%   |
| Timi                    | 6         | 0.16%   |
| Valve                   | 5         | 0.14%   |
| Kiano                   | 5         | 0.14%   |
| mPTech                  | 4         | 0.11%   |
| Inventec                | 4         | 0.11%   |
| ECS                     | 4         | 0.11%   |
| ZOTAC                   | 3         | 0.08%   |
| Supermicro              | 3         | 0.08%   |
| sunxi                   | 3         | 0.08%   |
| Pine Microsystems       | 3         | 0.08%   |
| Nvidia                  | 3         | 0.08%   |
| Huanan                  | 3         | 0.08%   |
| Hardkernel              | 3         | 0.08%   |
| Gateway                 | 3         | 0.08%   |
| Clevo                   | 3         | 0.08%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 35        | 0.95%   |
| Dell Inspiron 3451                  | 26        | 0.7%    |
| ASUS All Series                     | 26        | 0.7%    |
| ASUS SABERTOOTH Z77                 | 17        | 0.46%   |
| MSI MS-7817                         | 16        | 0.43%   |
| Gigabyte B450M DS3H                 | 16        | 0.43%   |
| MSI MS-7B86                         | 15        | 0.41%   |
| Dell Latitude E6400                 | 15        | 0.41%   |
| Dell OptiPlex 780                   | 13        | 0.35%   |
| Lenovo G50-30 80G0                  | 12        | 0.32%   |
| Dell Latitude E6540                 | 11        | 0.3%    |
| MSI MS-7C02                         | 10        | 0.27%   |
| Dell Latitude 5480                  | 10        | 0.27%   |
| Dell Latitude E6430                 | 9         | 0.24%   |
| Dell Latitude D630                  | 9         | 0.24%   |
| Dell Latitude 5490                  | 9         | 0.24%   |
| MSI MS-7B79                         | 8         | 0.22%   |
| Lenovo G580 20150                   | 8         | 0.22%   |
| HP Pavilion dv7                     | 8         | 0.22%   |
| Gigabyte B85M-D3H                   | 8         | 0.22%   |
| Gigabyte B450 AORUS ELITE           | 8         | 0.22%   |
| Dell Latitude E6420                 | 8         | 0.22%   |
| ASUS X555LJ                         | 8         | 0.22%   |
| ASUS TUF Gaming X570-PLUS           | 8         | 0.22%   |
| MSI MS-7A38                         | 7         | 0.19%   |
| HP Pavilion Gaming Laptop 15-ec1xxx | 7         | 0.19%   |
| HP EliteBook 6930p                  | 7         | 0.19%   |
| HP 15                               | 7         | 0.19%   |
| Dell OptiPlex 7010                  | 7         | 0.19%   |
| Dell Latitude E7440                 | 7         | 0.19%   |
| ASUS PRIME X470-PRO                 | 7         | 0.19%   |
| ASUS PRIME B450M-A                  | 7         | 0.19%   |
| Toshiba Satellite A300              | 6         | 0.16%   |
| MSI MS-7C37                         | 6         | 0.16%   |
| MSI MS-7721                         | 6         | 0.16%   |
| Lenovo Legion Y540-15IRH 81SX       | 6         | 0.16%   |
| Lenovo Legion Y530-15ICH 81FV       | 6         | 0.16%   |
| Lenovo Legion 5 15ARH05 82B5        | 6         | 0.16%   |
| Lenovo IdeaPad 100-15IBY 80MJ       | 6         | 0.16%   |
| Lenovo G500 20236                   | 6         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 268       | 7.24%   |
| Dell Latitude           | 239       | 6.45%   |
| Dell Inspiron           | 131       | 3.54%   |
| Lenovo IdeaPad          | 115       | 3.11%   |
| Acer Aspire             | 93        | 2.51%   |
| Dell OptiPlex           | 78        | 2.11%   |
| HP Pavilion             | 76        | 2.05%   |
| HP EliteBook            | 69        | 1.86%   |
| HP Compaq               | 55        | 1.49%   |
| Toshiba Satellite       | 52        | 1.4%    |
| HP ProBook              | 50        | 1.35%   |
| Dell Precision          | 50        | 1.35%   |
| ASUS PRIME              | 43        | 1.16%   |
| ASUS TUF                | 40        | 1.08%   |
| Lenovo ThinkCentre      | 36        | 0.97%   |
| Lenovo Legion           | 35        | 0.95%   |
| Unknown                 | 35        | 0.95%   |
| ASUS ROG                | 33        | 0.89%   |
| HP Laptop               | 30        | 0.81%   |
| ASUS VivoBook           | 30        | 0.81%   |
| Dell Vostro             | 29        | 0.78%   |
| ASUS All                | 26        | 0.7%    |
| Gigabyte B450M          | 23        | 0.62%   |
| Dell XPS                | 21        | 0.57%   |
| RPi Raspberry           | 20        | 0.54%   |
| ASUS SABERTOOTH         | 18        | 0.49%   |
| MSI MS-7817             | 16        | 0.43%   |
| HP 250                  | 16        | 0.43%   |
| MSI MS-7B86             | 15        | 0.41%   |
| Fujitsu LIFEBOOK        | 15        | 0.41%   |
| Fujitsu ESPRIMO         | 15        | 0.41%   |
| Lenovo Yoga             | 14        | 0.38%   |
| HP EliteDesk            | 14        | 0.38%   |
| ASUS ASUS               | 14        | 0.38%   |
| Acer Extensa            | 14        | 0.38%   |
| HP ZBook                | 13        | 0.35%   |
| Gigabyte X570           | 13        | 0.35%   |
| Fujitsu Siemens ESPRIMO | 13        | 0.35%   |
| Packard Bell EasyNote   | 12        | 0.32%   |
| Lenovo G50-30           | 12        | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2013    | 326       | 8.8%    |
| 2012    | 326       | 8.8%    |
| 2018    | 322       | 8.7%    |
| 2019    | 303       | 8.18%   |
| 2011    | 285       | 7.7%    |
| 2020    | 258       | 6.97%   |
| 2014    | 242       | 6.54%   |
| 2008    | 229       | 6.18%   |
| 2017    | 218       | 5.89%   |
| 2015    | 207       | 5.59%   |
| 2010    | 205       | 5.54%   |
| 2009    | 180       | 4.86%   |
| 2007    | 173       | 4.67%   |
| 2016    | 161       | 4.35%   |
| 2021    | 133       | 3.59%   |
| 2006    | 70        | 1.89%   |
| Unknown | 32        | 0.86%   |
| 2022    | 18        | 0.49%   |
| 2005    | 9         | 0.24%   |
| 2004    | 5         | 0.14%   |
| 2001    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2157      | 58.25%  |
| Desktop        | 1402      | 37.86%  |
| Convertible    | 36        | 0.97%   |
| System on chip | 34        | 0.92%   |
| Mini pc        | 25        | 0.68%   |
| Server         | 18        | 0.49%   |
| All in one     | 15        | 0.41%   |
| Tablet         | 11        | 0.3%    |
| Phone          | 5         | 0.14%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 3527      | 94.74%  |
| Enabled  | 196       | 5.26%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3692      | 99.7%   |
| Yes  | 11        | 0.3%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 860       | 22.8%   |
| 4.01-8.0        | 758       | 20.1%   |
| 8.01-16.0       | 687       | 18.21%  |
| 16.01-24.0      | 659       | 17.47%  |
| 32.01-64.0      | 358       | 9.49%   |
| 1.01-2.0        | 171       | 4.53%   |
| 2.01-3.0        | 107       | 2.84%   |
| 64.01-256.0     | 74        | 1.96%   |
| 24.01-32.0      | 58        | 1.54%   |
| 0.51-1.0        | 35        | 0.93%   |
| 0.01-0.5        | 4         | 0.11%   |
| More than 256.0 | 1         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1627      | 38.78%  |
| 2.01-3.0   | 851       | 20.28%  |
| 4.01-8.0   | 511       | 12.18%  |
| 3.01-4.0   | 469       | 11.18%  |
| 0.51-1.0   | 433       | 10.32%  |
| 8.01-16.0  | 174       | 4.15%   |
| 0.01-0.5   | 84        | 2%      |
| 16.01-24.0 | 33        | 0.79%   |
| 24.01-32.0 | 7         | 0.17%   |
| Unknown    | 4         | 0.1%    |
| 32.01-64.0 | 3         | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2257      | 58.76%  |
| 2       | 954       | 24.84%  |
| 3       | 330       | 8.59%   |
| 4       | 131       | 3.41%   |
| 0       | 64        | 1.67%   |
| 5       | 57        | 1.48%   |
| 6       | 23        | 0.6%    |
| 7       | 11        | 0.29%   |
| 8       | 6         | 0.16%   |
| 9       | 3         | 0.08%   |
| 11      | 2         | 0.05%   |
| 10      | 2         | 0.05%   |
| Unknown | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2037      | 54.25%  |
| Yes       | 1718      | 45.75%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3380      | 91.08%  |
| No        | 331       | 8.92%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2758      | 73.8%   |
| No        | 979       | 26.2%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2033      | 54.01%  |
| No        | 1731      | 45.99%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Poland  | 3703      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Warsaw                 | 839       | 20.86%  |
| Krakow                 | 300       | 7.46%   |
| Wroclaw                | 236       | 5.87%   |
| Poznan                 | 203       | 5.05%   |
| Gdansk                 | 122       | 3.03%   |
| Lodz                   | 118       | 2.93%   |
| Katowice               | 101       | 2.51%   |
| Lublin                 | 50        | 1.24%   |
| Gdynia                 | 48        | 1.19%   |
| Szczecin               | 45        | 1.12%   |
| Częstochowa           | 33        | 0.82%   |
| Bialystok              | 33        | 0.82%   |
| Gliwice                | 31        | 0.77%   |
| Rzeszów               | 30        | 0.75%   |
| Torun                  | 29        | 0.72%   |
| Ruda Śląska          | 28        | 0.7%    |
| Bydgoszcz              | 25        | 0.62%   |
| Bytom                  | 23        | 0.57%   |
| Płock                 | 21        | 0.52%   |
| Sosnowiec              | 20        | 0.5%    |
| Strzyzow               | 19        | 0.47%   |
| Kielce                 | 19        | 0.47%   |
| Chorzów               | 19        | 0.47%   |
| Bielsko-Biala          | 19        | 0.47%   |
| Rybnik                 | 17        | 0.42%   |
| Olsztyn                | 17        | 0.42%   |
| Elblag                 | 17        | 0.42%   |
| Opole                  | 16        | 0.4%    |
| Zabrze                 | 15        | 0.37%   |
| Radom                  | 15        | 0.37%   |
| Tarnów                | 14        | 0.35%   |
| Siemianowice Śląskie | 14        | 0.35%   |
| Cieszyn                | 13        | 0.32%   |
| Blizniew               | 13        | 0.32%   |
| Słupsk                | 12        | 0.3%    |
| Zielona Góra          | 11        | 0.27%   |
| Tychy                  | 11        | 0.27%   |
| Pabianice              | 10        | 0.25%   |
| Legnica                | 10        | 0.25%   |
| Jastrzębie Zdrój     | 10        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 828       | 1261   | 15.18%  |
| WDC                       | 793       | 1200   | 14.54%  |
| Samsung Electronics       | 726       | 1112   | 13.31%  |
| Toshiba                   | 354       | 529    | 6.49%   |
| GOODRAM                   | 349       | 503    | 6.4%    |
| Kingston                  | 208       | 290    | 3.81%   |
| Crucial                   | 207       | 334    | 3.8%    |
| A-DATA Technology         | 205       | 288    | 3.76%   |
| Hitachi                   | 195       | 262    | 3.58%   |
| Unknown                   | 188       | 271    | 3.45%   |
| SanDisk                   | 184       | 253    | 3.37%   |
| Intel                     | 142       | 188    | 2.6%    |
| SK hynix                  | 114       | 148    | 2.09%   |
| HGST                      | 89        | 115    | 1.63%   |
| Micron Technology         | 68        | 89     | 1.25%   |
| Patriot                   | 67        | 88     | 1.23%   |
| SPCC                      | 60        | 84     | 1.1%    |
| Plextor                   | 57        | 73     | 1.05%   |
| PNY                       | 40        | 44     | 0.73%   |
| XPG                       | 37        | 51     | 0.68%   |
| Phison                    | 32        | 47     | 0.59%   |
| KIOXIA                    | 30        | 35     | 0.55%   |
| Fujitsu                   | 29        | 33     | 0.53%   |
| Apacer                    | 29        | 44     | 0.53%   |
| OCZ                       | 25        | 27     | 0.46%   |
| Corsair                   | 23        | 30     | 0.42%   |
| China                     | 21        | 25     | 0.39%   |
| LITEON                    | 20        | 29     | 0.37%   |
| Maxtor                    | 18        | 18     | 0.33%   |
| Transcend                 | 17        | 18     | 0.31%   |
| Lite-On                   | 17        | 20     | 0.31%   |
| Realtek Semiconductor     | 15        | 25     | 0.28%   |
| KIOXIA-EXCERIA            | 15        | 20     | 0.28%   |
| ASMT                      | 15        | 16     | 0.28%   |
| LITEONIT                  | 12        | 13     | 0.22%   |
| JMicron Technology        | 12        | 13     | 0.22%   |
| HUAWEI                    | 11        | 13     | 0.2%    |
| Silicon Motion            | 10        | 12     | 0.18%   |
| Apple                     | 10        | 13     | 0.18%   |
| Micron/Crucial Technology | 9         | 9      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB     | 52        | 0.87%   |
| Seagate ST500LT012-1DG142 500GB    | 51        | 0.85%   |
| Toshiba HDWD110 1TB                | 47        | 0.79%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 46        | 0.77%   |
| Samsung SSD 850 EVO 250GB          | 44        | 0.74%   |
| GOODRAM SSD 120GB                  | 43        | 0.72%   |
| Crucial CT500MX500SSD1 500GB       | 43        | 0.72%   |
| Seagate ST500DM002-1BD142 500GB    | 37        | 0.62%   |
| Crucial CT1000MX500SSD1 1TB        | 34        | 0.57%   |
| Samsung NVMe SSD Drive 500GB       | 32        | 0.54%   |
| GOODRAM SSDPR-CX400-512 512GB      | 32        | 0.54%   |
| GOODRAM SSD 240GB                  | 32        | 0.54%   |
| Samsung SSD 860 EVO 250GB          | 31        | 0.52%   |
| Samsung SSD 860 EVO 500GB          | 30        | 0.5%    |
| Kingston SV300S37A120G 120GB SSD   | 29        | 0.49%   |
| Unknown MMC Card  32GB             | 28        | 0.47%   |
| Samsung NVMe SSD Drive 512GB       | 28        | 0.47%   |
| GOODRAM SSDPR-CX400-256-G2 256GB   | 28        | 0.47%   |
| Samsung NVMe SSD Drive 256GB       | 27        | 0.45%   |
| Seagate ST9500325AS 500GB          | 26        | 0.44%   |
| Seagate ST3500418AS 500GB          | 26        | 0.44%   |
| Intel NVMe SSD Drive 512GB         | 26        | 0.44%   |
| Patriot Burst 120GB SSD            | 25        | 0.42%   |
| A-DATA SU800 256GB SSD             | 25        | 0.42%   |
| Toshiba MQ01ABD100 1TB             | 24        | 0.4%    |
| Seagate ST1000DM003-1ER162 1TB     | 24        | 0.4%    |
| Unknown MMC Card  64GB             | 23        | 0.39%   |
| Kingston SA400S37240G 240GB SSD    | 23        | 0.39%   |
| Crucial CT240BX500SSD1 240GB       | 23        | 0.39%   |
| Seagate ST1000DM010-2EP102 1TB     | 22        | 0.37%   |
| Samsung HD502HJ 500GB              | 22        | 0.37%   |
| HGST HTS721010A9E630 1TB           | 22        | 0.37%   |
| Toshiba DT01ACA100 1TB             | 21        | 0.35%   |
| SanDisk SDSSDA240G 240GB           | 21        | 0.35%   |
| Kingston SA400S37480G 480GB SSD    | 21        | 0.35%   |
| Seagate Expansion 1TB              | 20        | 0.34%   |
| GOODRAM SSDPR-CX400-512-G2 512GB   | 20        | 0.34%   |
| GOODRAM SSDPR-CX400-256 256GB      | 20        | 0.34%   |
| GOODRAM SSDPR-CL100-120-G2 120GB   | 20        | 0.34%   |
| Toshiba MQ01ABF050 500GB           | 19        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 825       | 1256   | 36.17%  |
| WDC                 | 665       | 1018   | 29.15%  |
| Toshiba             | 279       | 437    | 12.23%  |
| Hitachi             | 195       | 262    | 8.55%   |
| Samsung Electronics | 146       | 211    | 6.4%    |
| HGST                | 89        | 115    | 3.9%    |
| Fujitsu             | 29        | 33     | 1.27%   |
| Maxtor              | 16        | 16     | 0.7%    |
| Unknown             | 6         | 6      | 0.26%   |
| ASMedia             | 5         | 6      | 0.22%   |
| Apple               | 5         | 5      | 0.22%   |
| USB3.0              | 3         | 3      | 0.13%   |
| ASMT                | 3         | 4      | 0.13%   |
| IBM/Hitachi         | 2         | 2      | 0.09%   |
| WD MediaMax         | 1         | 2      | 0.04%   |
| Synology            | 1         | 1      | 0.04%   |
| StoreJet            | 1         | 1      | 0.04%   |
| SATAFIRM            | 1         | 1      | 0.04%   |
| SAGE                | 1         | 1      | 0.04%   |
| PHD 3.0             | 1         | 1      | 0.04%   |
| MARVELL             | 1         | 1      | 0.04%   |
| LaCie               | 1         | 2      | 0.04%   |
| HPE                 | 1         | 1      | 0.04%   |
| Hewlett-Packard     | 1         | 1      | 0.04%   |
| ExcelStor           | 1         | 1      | 0.04%   |
| ASMT109x            | 1         | 1      | 0.04%   |
| Unknown             | 1         | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Goodram             | 343       | 491    | 17.19%  |
| Samsung Electronics | 339       | 475    | 16.99%  |
| Crucial             | 199       | 324    | 9.97%   |
| A-DATA Technology   | 168       | 232    | 8.42%   |
| Kingston            | 156       | 213    | 7.82%   |
| SanDisk             | 138       | 195    | 6.92%   |
| WDC                 | 71        | 83     | 3.56%   |
| Patriot             | 59        | 80     | 2.96%   |
| SPCC                | 55        | 77     | 2.76%   |
| Plextor             | 48        | 64     | 2.41%   |
| Intel               | 47        | 57     | 2.36%   |
| Micron Technology   | 44        | 58     | 2.21%   |
| Toshiba             | 37        | 40     | 1.85%   |
| SK hynix            | 31        | 39     | 1.55%   |
| PNY                 | 29        | 33     | 1.45%   |
| Apacer              | 27        | 42     | 1.35%   |
| OCZ                 | 25        | 27     | 1.25%   |
| LITEON              | 20        | 29     | 1%      |
| China               | 20        | 24     | 1%      |
| Transcend           | 16        | 17     | 0.8%    |
| LITEONIT            | 12        | 13     | 0.6%    |
| KIOXIA-EXCERIA      | 12        | 16     | 0.6%    |
| ASMT                | 12        | 12     | 0.6%    |
| Corsair             | 10        | 11     | 0.5%    |
| KingSpec            | 6         | 6      | 0.3%    |
| Apple               | 6         | 6      | 0.3%    |
| Intenso             | 5         | 10     | 0.25%   |
| Team                | 4         | 4      | 0.2%    |
| BIWIN               | 4         | 4      | 0.2%    |
| Argon               | 4         | 6      | 0.2%    |
| 2-Power             | 3         | 3      | 0.15%   |
| WDC WDS2            | 2         | 2      | 0.1%    |
| Union Memory        | 2         | 3      | 0.1%    |
| Phison              | 2         | 2      | 0.1%    |
| Maxtor              | 2         | 2      | 0.1%    |
| Lexar               | 2         | 2      | 0.1%    |
| HS-SSD-C100         | 2         | 2      | 0.1%    |
| Gigabyte Technology | 2         | 3      | 0.1%    |
| FORESEE             | 2         | 2      | 0.1%    |
| ADATA SU            | 2         | 2      | 0.1%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1930      | 3389   | 39.84%  |
| SSD     | 1752      | 2740   | 36.17%  |
| NVMe    | 933       | 1404   | 19.26%  |
| MMC     | 168       | 240    | 3.47%   |
| Unknown | 61        | 88     | 1.26%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2974      | 6003   | 70.26%  |
| NVMe | 926       | 1394   | 21.88%  |
| MMC  | 168       | 240    | 3.97%   |
| SAS  | 165       | 224    | 3.9%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2462      | 4045   | 66.22%  |
| 0.51-1.0   | 931       | 1487   | 25.04%  |
| 1.01-2.0   | 191       | 318    | 5.14%   |
| 3.01-4.0   | 53        | 101    | 1.43%   |
| 2.01-3.0   | 51        | 109    | 1.37%   |
| 4.01-10.0  | 26        | 59     | 0.7%    |
| 10.01-20.0 | 4         | 10     | 0.11%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1142      | 28.54%  |
| 251-500        | 748       | 18.69%  |
| 1-20           | 475       | 11.87%  |
| 501-1000       | 442       | 11.04%  |
| 51-100         | 348       | 8.7%    |
| 1001-2000      | 257       | 6.42%   |
| 21-50          | 211       | 5.27%   |
| Unknown        | 169       | 4.22%   |
| More than 3000 | 124       | 3.1%    |
| 2001-3000      | 86        | 2.15%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1736      | 42.11%  |
| 21-50          | 614       | 14.89%  |
| 101-250        | 479       | 11.62%  |
| 51-100         | 450       | 10.91%  |
| 251-500        | 264       | 6.4%    |
| 501-1000       | 211       | 5.12%   |
| Unknown        | 169       | 4.1%    |
| 1001-2000      | 118       | 2.86%   |
| 2001-3000      | 42        | 1.02%   |
| More than 3000 | 40        | 0.97%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB            | 10        | 13     | 1.83%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 9         | 10     | 1.65%   |
| Seagate ST500LT012-9WS142 500GB      | 8         | 25     | 1.46%   |
| Seagate ST3500418AS 500GB            | 8         | 11     | 1.46%   |
| Seagate ST500DM002-1BD142 500GB      | 6         | 6      | 1.1%    |
| Seagate ST500LT012-1DG142 500GB      | 5         | 7      | 0.91%   |
| Kingston SV300S37A120G 120GB SSD     | 5         | 5      | 0.91%   |
| HGST HTS545050A7E680 500GB           | 5         | 5      | 0.91%   |
| GOODRAM SSD 120GB                    | 5         | 5      | 0.91%   |
| WDC WD5000BEVT-22ZAT0 500GB          | 4         | 4      | 0.73%   |
| Toshiba MQ01ABD100 1TB               | 4         | 5      | 0.73%   |
| Seagate ST9500420AS 500GB            | 4         | 4      | 0.73%   |
| Seagate ST92505610AS 250GB           | 4         | 4      | 0.73%   |
| Seagate ST1000DM003-9YN162 1TB       | 4         | 4      | 0.73%   |
| Hitachi HTS541612J9SA00 120GB        | 4         | 5      | 0.73%   |
| ASMT 2135 120GB SSD                  | 4         | 4      | 0.73%   |
| WDC WD3200BPVT-80ZEST0 320GB         | 3         | 3      | 0.55%   |
| WDC WD10JPVX-22JC3T0 1TB             | 3         | 3      | 0.55%   |
| Toshiba MK3265GSX 320GB              | 3         | 3      | 0.55%   |
| Toshiba MK1637GSX 160GB              | 3         | 3      | 0.55%   |
| Toshiba MK1246GSX 120GB              | 3         | 3      | 0.55%   |
| SK hynix PC711 HFS512GDE9X073N 512GB | 3         | 3      | 0.55%   |
| Seagate ST9320325AS 320GB            | 3         | 3      | 0.55%   |
| Seagate ST9250827AS 250GB            | 3         | 3      | 0.55%   |
| Seagate ST9250410AS 250GB            | 3         | 3      | 0.55%   |
| Seagate ST9250315AS 250GB            | 3         | 3      | 0.55%   |
| Seagate ST9160821AS 160GB            | 3         | 4      | 0.55%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 3         | 3      | 0.55%   |
| Seagate ST3500312CS 500GB            | 3         | 3      | 0.55%   |
| Seagate ST3250410AS 250GB            | 3         | 3      | 0.55%   |
| Seagate ST31500341AS 1TB             | 3         | 4      | 0.55%   |
| Seagate ST1000LM014-1EJ164 1TB       | 3         | 3      | 0.55%   |
| Hitachi HTS542516K9SA00 160GB        | 3         | 5      | 0.55%   |
| HGST HTS545050A7E380 500GB           | 3         | 3      | 0.55%   |
| WDC WD5002ABYS-01B1B0 500GB          | 2         | 14     | 0.37%   |
| WDC WD5000AVDS-63U7B1 500GB          | 2         | 2      | 0.37%   |
| WDC WD5000AACS-00G8B1 500GB          | 2         | 2      | 0.37%   |
| WDC WD3200AAJS-00B4A0 320GB          | 2         | 4      | 0.37%   |
| WDC WD20EFRX-68EUZN0 2TB             | 2         | 10     | 0.37%   |
| WDC WD1600BEVT-75A23T0 160GB         | 2         | 2      | 0.37%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 160       | 218    | 30.53%  |
| WDC                   | 99        | 149    | 18.89%  |
| Toshiba               | 44        | 55     | 8.4%    |
| Hitachi               | 44        | 54     | 8.4%    |
| Samsung Electronics   | 39        | 45     | 7.44%   |
| A-DATA Technology     | 23        | 26     | 4.39%   |
| HGST                  | 14        | 15     | 2.67%   |
| SanDisk               | 13        | 16     | 2.48%   |
| Kingston              | 11        | 11     | 2.1%    |
| SK hynix              | 8         | 8      | 1.53%   |
| Intel                 | 7         | 7      | 1.34%   |
| GOODRAM               | 7         | 7      | 1.34%   |
| Fujitsu               | 7         | 9      | 1.34%   |
| ASMT                  | 5         | 6      | 0.95%   |
| Micron Technology     | 4         | 4      | 0.76%   |
| LITEON                | 4         | 4      | 0.76%   |
| SPCC                  | 3         | 3      | 0.57%   |
| Maxtor                | 3         | 3      | 0.57%   |
| LITEONIT              | 3         | 3      | 0.57%   |
| Hewlett-Packard       | 3         | 3      | 0.57%   |
| Crucial               | 3         | 4      | 0.57%   |
| ASMedia               | 3         | 3      | 0.57%   |
| Apacer                | 3         | 6      | 0.57%   |
| OCZ                   | 2         | 2      | 0.38%   |
| XPG                   | 1         | 1      | 0.19%   |
| WDC WDS2              | 1         | 1      | 0.19%   |
| WD MediaMax           | 1         | 2      | 0.19%   |
| SSSTC                 | 1         | 1      | 0.19%   |
| Realtek Semiconductor | 1         | 1      | 0.19%   |
| Plextor               | 1         | 1      | 0.19%   |
| Platinet              | 1         | 1      | 0.19%   |
| Patriot               | 1         | 3      | 0.19%   |
| Lexar                 | 1         | 1      | 0.19%   |
| Lenovo                | 1         | 1      | 0.19%   |
| Corsair               | 1         | 2      | 0.19%   |
| Unknown               | 1         | 1      | 0.19%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 160       | 218    | 39.8%   |
| WDC                 | 97        | 146    | 24.13%  |
| Hitachi             | 44        | 54     | 10.95%  |
| Toshiba             | 41        | 52     | 10.2%   |
| Samsung Electronics | 29        | 34     | 7.21%   |
| HGST                | 14        | 15     | 3.48%   |
| Fujitsu             | 7         | 9      | 1.74%   |
| Maxtor              | 3         | 3      | 0.75%   |
| ASMedia             | 3         | 3      | 0.75%   |
| WD MediaMax         | 1         | 2      | 0.25%   |
| Hewlett-Packard     | 1         | 1      | 0.25%   |
| ASMT                | 1         | 2      | 0.25%   |
| Unknown             | 1         | 1      | 0.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 376       | 540    | 75.81%  |
| SSD  | 101       | 116    | 20.36%  |
| NVMe | 19        | 21     | 3.83%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD800BEVS-75RST0 80GB         | 1         | 1      | 9.09%   |
| WDC WD3200BEVT-22ZCT0 320GB       | 1         | 1      | 9.09%   |
| WDC WD3200BEKT-75PVMT1 320GB      | 1         | 1      | 9.09%   |
| WDC WD2500BEVS-22UST0 250GB       | 1         | 1      | 9.09%   |
| WDC WD1600AAJS-75M0A0 160GB       | 1         | 1      | 9.09%   |
| Toshiba MK3265GSXN 320GB          | 1         | 1      | 9.09%   |
| Toshiba DT01ACA100 1TB            | 1         | 2      | 9.09%   |
| Seagate ST500DM002-1BC142 500GB   | 1         | 1      | 9.09%   |
| Seagate ST320LT020-9YG142 320GB   | 1         | 1      | 9.09%   |
| Samsung Electronics HD250HJ 250GB | 1         | 1      | 9.09%   |
| OCZ-AGIL ITY3 120GB SSD           | 1         | 1      | 9.09%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 45.45%  |
| Toshiba             | 2         | 3      | 18.18%  |
| Seagate             | 2         | 2      | 18.18%  |
| Samsung Electronics | 1         | 1      | 9.09%   |
| OCZ-AGIL            | 1         | 1      | 9.09%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1965      | 4078   | 48.54%  |
| Works    | 1590      | 3094   | 39.28%  |
| Malfunc  | 482       | 677    | 11.91%  |
| Failed   | 11        | 12     | 0.27%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2622      | 57.05%  |
| AMD                              | 682       | 14.84%  |
| Samsung Electronics              | 300       | 6.53%   |
| SanDisk                          | 113       | 2.46%   |
| JMicron Technology               | 85        | 1.85%   |
| Nvidia                           | 84        | 1.83%   |
| SK hynix                         | 80        | 1.74%   |
| ASMedia Technology               | 80        | 1.74%   |
| Phison Electronics               | 75        | 1.63%   |
| ADATA Technology                 | 71        | 1.54%   |
| Kingston Technology Company      | 55        | 1.2%    |
| Marvell Technology Group         | 42        | 0.91%   |
| Toshiba America Info Systems     | 40        | 0.87%   |
| KIOXIA                           | 36        | 0.78%   |
| Silicon Motion                   | 28        | 0.61%   |
| Realtek Semiconductor            | 27        | 0.59%   |
| Micron Technology                | 25        | 0.54%   |
| Lite-On Technology               | 24        | 0.52%   |
| VIA Technologies                 | 20        | 0.44%   |
| Micron/Crucial Technology        | 16        | 0.35%   |
| Union Memory (Shenzhen)          | 12        | 0.26%   |
| LSI Logic / Symbios Logic        | 12        | 0.26%   |
| Silicon Integrated Systems [SiS] | 11        | 0.24%   |
| Solid State Storage Technology   | 8         | 0.17%   |
| Shenzhen Longsys Electronics     | 8         | 0.17%   |
| Broadcom / LSI                   | 7         | 0.15%   |
| Silicon Image                    | 6         | 0.13%   |
| Lenovo                           | 6         | 0.13%   |
| Hewlett-Packard                  | 4         | 0.09%   |
| Yangtze Memory Technologies      | 2         | 0.04%   |
| Unknown                          | 2         | 0.04%   |
| ULi Electronics                  | 2         | 0.04%   |
| Apple                            | 2         | 0.04%   |
| Tekram Technology                | 1         | 0.02%   |
| OCZ Technology Group             | 1         | 0.02%   |
| O2 Micro                         | 1         | 0.02%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.02%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.02%   |
| Integrated Technology Express    | 1         | 0.02%   |
| Dell                             | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 445       | 8.1%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 197       | 3.59%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 183       | 3.33%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 176       | 3.2%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 150       | 2.73%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 139       | 2.53%   |
| AMD 400 Series Chipset SATA Controller                                         | 134       | 2.44%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 130       | 2.37%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 119       | 2.17%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 107       | 1.95%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 97        | 1.77%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 95        | 1.73%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 94        | 1.71%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 92        | 1.67%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 84        | 1.53%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 78        | 1.42%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 77        | 1.4%    |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 73        | 1.33%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 72        | 1.31%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 72        | 1.31%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 71        | 1.29%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 69        | 1.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 68        | 1.24%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 68        | 1.24%   |
| Intel SSD 660P Series                                                          | 65        | 1.18%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 65        | 1.18%   |
| Samsung NVMe SSD Controller 980                                                | 60        | 1.09%   |
| JMicron JMB363 SATA/IDE Controller                                             | 58        | 1.06%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 58        | 1.06%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 56        | 1.02%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 56        | 1.02%   |
| Intel Volume Management Device NVMe RAID Controller                            | 53        | 0.96%   |
| Intel SATA Controller [RAID mode]                                              | 53        | 0.96%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 50        | 0.91%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 43        | 0.78%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 40        | 0.73%   |
| Phison E12 NVMe Controller                                                     | 38        | 0.69%   |
| Nvidia MCP61 SATA Controller                                                   | 37        | 0.67%   |
| Nvidia MCP61 IDE                                                               | 36        | 0.66%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 33        | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2699      | 57.58%  |
| NVMe | 943       | 20.12%  |
| IDE  | 744       | 15.87%  |
| RAID | 279       | 5.95%   |
| SAS  | 12        | 0.26%   |
| SCSI | 10        | 0.21%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 2802      | 75.67%  |
| AMD          | 857       | 23.14%  |
| ARM          | 38        | 1.03%   |
| QUALCOMM     | 2         | 0.05%   |
| PowerMac11,2 | 1         | 0.03%   |
| PowerBook6,7 | 1         | 0.03%   |
| CentaurHauls | 1         | 0.03%   |
| AppliedMicro | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron CPU N2840 @ 2.16GHz             | 43        | 1.16%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 36        | 0.97%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 34        | 0.92%   |
| AMD Ryzen 5 3600 6-Core Processor             | 33        | 0.89%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 31        | 0.83%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 31        | 0.83%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 30        | 0.81%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 29        | 0.78%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 29        | 0.78%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 28        | 0.75%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 26        | 0.7%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 25        | 0.67%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 24        | 0.65%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 23        | 0.62%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 23        | 0.62%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 23        | 0.62%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 23        | 0.62%   |
| Intel Core i5-3570K CPU @ 3.40GHz             | 21        | 0.57%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 21        | 0.57%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 21        | 0.57%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 21        | 0.57%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 21        | 0.57%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 19        | 0.51%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 19        | 0.51%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 19        | 0.51%   |
| ARM Processor                                 | 19        | 0.51%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 18        | 0.48%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 18        | 0.48%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 18        | 0.48%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 18        | 0.48%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 18        | 0.48%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 17        | 0.46%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 17        | 0.46%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 17        | 0.46%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 17        | 0.46%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 16        | 0.43%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 16        | 0.43%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 16        | 0.43%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 16        | 0.43%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 16        | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 894       | 24.08%  |
| Intel Core i7           | 566       | 15.24%  |
| Intel Core i3           | 280       | 7.54%   |
| Intel Core 2 Duo        | 266       | 7.16%   |
| AMD Ryzen 5             | 226       | 6.09%   |
| Intel Celeron           | 157       | 4.23%   |
| AMD Ryzen 7             | 140       | 3.77%   |
| Other                   | 124       | 3.34%   |
| Intel Pentium           | 110       | 2.96%   |
| Intel Xeon              | 92        | 2.48%   |
| Intel Atom              | 67        | 1.8%    |
| Intel Pentium Dual-Core | 63        | 1.7%    |
| Intel Core 2 Quad       | 56        | 1.51%   |
| AMD FX                  | 46        | 1.24%   |
| Intel Core 2            | 40        | 1.08%   |
| AMD Ryzen 9             | 39        | 1.05%   |
| AMD Ryzen 3             | 33        | 0.89%   |
| AMD Phenom II X4        | 33        | 0.89%   |
| Intel Pentium Dual      | 31        | 0.83%   |
| AMD Athlon 64 X2        | 31        | 0.83%   |
| AMD A6                  | 29        | 0.78%   |
| AMD A8                  | 27        | 0.73%   |
| AMD Athlon II X2        | 26        | 0.7%    |
| AMD A10                 | 25        | 0.67%   |
| Intel Genuine           | 17        | 0.46%   |
| AMD A4                  | 17        | 0.46%   |
| AMD Athlon II X4        | 16        | 0.43%   |
| Intel Core i9           | 14        | 0.38%   |
| AMD Ryzen 7 PRO         | 13        | 0.35%   |
| AMD E                   | 13        | 0.35%   |
| ARM BCM                 | 11        | 0.3%    |
| AMD E1                  | 11        | 0.3%    |
| Intel Celeron M         | 10        | 0.27%   |
| AMD Ryzen Threadripper  | 9         | 0.24%   |
| AMD Athlon              | 9         | 0.24%   |
| Intel Pentium D         | 8         | 0.22%   |
| AMD Turion 64 X2 Mobile | 8         | 0.22%   |
| AMD GX                  | 8         | 0.22%   |
| AMD Athlon 64           | 8         | 0.22%   |
| Intel Pentium M         | 7         | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1668      | 44.74%  |
| 4       | 1263      | 33.88%  |
| 6       | 331       | 8.88%   |
| 8       | 209       | 5.61%   |
| 1       | 94        | 2.52%   |
| Unknown | 68        | 1.82%   |
| 12      | 42        | 1.13%   |
| 3       | 21        | 0.56%   |
| 16      | 11        | 0.3%    |
| 10      | 7         | 0.19%   |
| 14      | 4         | 0.11%   |
| 32      | 3         | 0.08%   |
| 24      | 2         | 0.05%   |
| 20      | 2         | 0.05%   |
| 192     | 1         | 0.03%   |
| 48      | 1         | 0.03%   |
| 5       | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3667      | 98.95%  |
| 2       | 34        | 0.92%   |
| Unknown | 4         | 0.11%   |
| 4       | 1         | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2157      | 57.91%  |
| 1       | 1500      | 40.27%  |
| Unknown | 68        | 1.83%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3581      | 96.44%  |
| Unknown        | 81        | 2.18%   |
| 32-bit         | 49        | 1.32%   |
| 64-bit         | 2         | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 692       | 18.11%  |
| 0x306a9    | 247       | 6.46%   |
| 0x206a7    | 235       | 6.15%   |
| 0x306c3    | 202       | 5.29%   |
| 0x1067a    | 196       | 5.13%   |
| 0x906ea    | 107       | 2.8%    |
| 0x40651    | 94        | 2.46%   |
| 0x506e3    | 93        | 2.43%   |
| 0x6fd      | 79        | 2.07%   |
| 0x20655    | 79        | 2.07%   |
| 0x906e9    | 77        | 2.01%   |
| 0x30678    | 75        | 1.96%   |
| 0x806ec    | 73        | 1.91%   |
| 0x306d4    | 67        | 1.75%   |
| 0x806ea    | 66        | 1.73%   |
| 0x10676    | 65        | 1.7%    |
| 0x406e3    | 57        | 1.49%   |
| 0x0800820d | 56        | 1.47%   |
| 0x806e9    | 55        | 1.44%   |
| 0x010000c8 | 54        | 1.41%   |
| 0x806c1    | 52        | 1.36%   |
| 0x08701021 | 47        | 1.23%   |
| 0x6fb      | 40        | 1.05%   |
| 0x06001119 | 35        | 0.92%   |
| 0x08108109 | 32        | 0.84%   |
| 0x6f6      | 31        | 0.81%   |
| 0x20652    | 31        | 0.81%   |
| 0x0a50000c | 27        | 0.71%   |
| 0x08701013 | 26        | 0.68%   |
| 0x806eb    | 23        | 0.6%    |
| 0xa0652    | 22        | 0.58%   |
| 0x08600106 | 22        | 0.58%   |
| 0x08108102 | 22        | 0.58%   |
| 0x06000852 | 22        | 0.58%   |
| 0x406c4    | 21        | 0.55%   |
| 0x106e5    | 21        | 0.55%   |
| 0x08001138 | 21        | 0.55%   |
| 0x706e5    | 20        | 0.52%   |
| 0x906ed    | 18        | 0.47%   |
| 0x406c3    | 17        | 0.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 514       | 13.84%  |
| Haswell          | 356       | 9.59%   |
| Penryn           | 299       | 8.05%   |
| IvyBridge        | 291       | 7.84%   |
| SandyBridge      | 277       | 7.46%   |
| Core             | 207       | 5.57%   |
| Skylake          | 187       | 5.04%   |
| Zen 2            | 177       | 4.77%   |
| Zen+             | 139       | 3.74%   |
| Westmere         | 135       | 3.63%   |
| Silvermont       | 131       | 3.53%   |
| K10              | 107       | 2.88%   |
| Broadwell        | 91        | 2.45%   |
| Zen              | 79        | 2.13%   |
| Unknown          | 79        | 2.13%   |
| Piledriver       | 75        | 2.02%   |
| Zen 3            | 63        | 1.7%    |
| K8 Hammer        | 62        | 1.67%   |
| TigerLake        | 58        | 1.56%   |
| CometLake        | 57        | 1.53%   |
| IceLake          | 42        | 1.13%   |
| Nehalem          | 35        | 0.94%   |
| Bonnell          | 30        | 0.81%   |
| Bobcat           | 30        | 0.81%   |
| P6               | 29        | 0.78%   |
| Jaguar           | 24        | 0.65%   |
| Goldmont plus    | 18        | 0.48%   |
| NetBurst         | 17        | 0.46%   |
| Steamroller      | 16        | 0.43%   |
| Excavator        | 16        | 0.43%   |
| K10 Llano        | 15        | 0.4%    |
| Puma             | 14        | 0.38%   |
| K8 & K10 hybrid  | 12        | 0.32%   |
| Goldmont         | 11        | 0.3%    |
| Bulldozer        | 11        | 0.3%    |
| Alderlake Hybrid | 10        | 0.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2047      | 46.68%  |
| Nvidia                           | 1365      | 31.13%  |
| AMD                              | 950       | 21.66%  |
| Matrox Electronics Systems       | 8         | 0.18%   |
| Silicon Integrated Systems [SiS] | 6         | 0.14%   |
| VIA Technologies                 | 5         | 0.11%   |
| ASPEED Technology                | 3         | 0.07%   |
| S3 Graphics                      | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 221       | 4.83%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 180       | 3.93%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 111       | 2.43%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 96        | 2.1%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 84        | 1.84%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 79        | 1.73%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 78        | 1.7%    |
| Intel UHD Graphics 620                                                                   | 76        | 1.66%   |
| Intel HD Graphics 5500                                                                   | 76        | 1.66%   |
| Intel Core Processor Integrated Graphics Controller                                      | 75        | 1.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 74        | 1.62%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 74        | 1.62%   |
| AMD Renoir                                                                               | 73        | 1.6%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 70        | 1.53%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 67        | 1.46%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 67        | 1.46%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 67        | 1.46%   |
| Intel HD Graphics 530                                                                    | 65        | 1.42%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 63        | 1.38%   |
| Intel HD Graphics 630                                                                    | 63        | 1.38%   |
| Intel HD Graphics 620                                                                    | 62        | 1.35%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 54        | 1.18%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 46        | 1.01%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 45        | 0.98%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 39        | 0.85%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 36        | 0.79%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 35        | 0.76%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 35        | 0.76%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 35        | 0.76%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 34        | 0.74%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 33        | 0.72%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 33        | 0.72%   |
| AMD Cezanne                                                                              | 32        | 0.7%    |
| Nvidia GT218 [GeForce 210]                                                               | 28        | 0.61%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 27        | 0.59%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 26        | 0.57%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 25        | 0.55%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 24        | 0.52%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 24        | 0.52%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 24        | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 1414      | 37.87%  |
| 1 x Nvidia      | 813       | 21.77%  |
| 1 x AMD         | 713       | 19.09%  |
| Intel + Nvidia  | 480       | 12.85%  |
| Intel + AMD     | 122       | 3.27%   |
| AMD + Nvidia    | 66        | 1.77%   |
| 2 x AMD         | 51        | 1.37%   |
| Other           | 43        | 1.15%   |
| 1 x Matrox      | 8         | 0.21%   |
| 1 x SiS         | 6         | 0.16%   |
| 1 x VIA         | 5         | 0.13%   |
| 2 x Nvidia      | 4         | 0.11%   |
| 2 x Intel       | 3         | 0.08%   |
| 3 x AMD         | 2         | 0.05%   |
| Nvidia + ASPEED | 2         | 0.05%   |
| 1 x S3 Graphics | 1         | 0.03%   |
| 1 x ASPEED      | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2924      | 77.4%   |
| Proprietary | 676       | 17.89%  |
| Unknown     | 178       | 4.71%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1853      | 48.31%  |
| 1.01-2.0   | 556       | 14.49%  |
| 0.01-0.5   | 513       | 13.37%  |
| 0.51-1.0   | 357       | 9.31%   |
| 3.01-4.0   | 269       | 7.01%   |
| 7.01-8.0   | 150       | 3.91%   |
| 5.01-6.0   | 100       | 2.61%   |
| 8.01-16.0  | 23        | 0.6%    |
| 2.01-3.0   | 12        | 0.31%   |
| 16.01-24.0 | 3         | 0.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 593       | 14.54%  |
| AU Optronics            | 468       | 11.48%  |
| LG Display              | 406       | 9.96%   |
| BOE                     | 287       | 7.04%   |
| Chimei Innolux          | 263       | 6.45%   |
| Dell                    | 250       | 6.13%   |
| Goldstar                | 231       | 5.66%   |
| Philips                 | 132       | 3.24%   |
| Iiyama                  | 132       | 3.24%   |
| BenQ                    | 109       | 2.67%   |
| Lenovo                  | 104       | 2.55%   |
| Hewlett-Packard         | 99        | 2.43%   |
| Acer                    | 99        | 2.43%   |
| Chi Mei Optoelectronics | 93        | 2.28%   |
| AOC                     | 83        | 2.04%   |
| NEC Computers           | 67        | 1.64%   |
| Eizo                    | 59        | 1.45%   |
| Ancor Communications    | 55        | 1.35%   |
| LG Philips              | 40        | 0.98%   |
| Sharp                   | 39        | 0.96%   |
| LG Electronics          | 32        | 0.78%   |
| Fujitsu Siemens         | 30        | 0.74%   |
| Sony                    | 29        | 0.71%   |
| PANDA                   | 27        | 0.66%   |
| InfoVision              | 18        | 0.44%   |
| Unknown                 | 17        | 0.42%   |
| ASUSTek Computer        | 17        | 0.42%   |
| Toshiba                 | 16        | 0.39%   |
| Apple                   | 16        | 0.39%   |
| ViewSonic               | 14        | 0.34%   |
| Panasonic               | 13        | 0.32%   |
| Idek Iiyama             | 12        | 0.29%   |
| HannStar                | 12        | 0.29%   |
| CPT                     | 12        | 0.29%   |
| Gateway                 | 11        | 0.27%   |
| Vestel Elektronik       | 8         | 0.2%    |
| LGD                     | 8         | 0.2%    |
| Belinea                 | 8         | 0.2%    |
| Seiko/Epson             | 7         | 0.17%   |
| MSI                     | 7         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch     | 27        | 0.64%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 27        | 0.64%   |
| BOE LCD Monitor BOE0629 1366x768 309x173mm 13.9-inch                     | 26        | 0.61%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 21        | 0.49%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 19        | 0.45%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 18        | 0.42%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 17        | 0.4%    |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                  | 15        | 0.35%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 15        | 0.35%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 15        | 0.35%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch     | 13        | 0.31%   |
| Philips 273PQPY PHLC096 1920x1080 597x336mm 27.0-inch                    | 13        | 0.31%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 13        | 0.31%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 13        | 0.31%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                  | 12        | 0.28%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 12        | 0.28%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 12        | 0.28%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 12        | 0.28%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 12        | 0.28%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 11        | 0.26%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch             | 11        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 11        | 0.26%   |
| BOE LCD Monitor BOE06FB 1920x1080 344x194mm 15.5-inch                    | 11        | 0.26%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 11        | 0.26%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 11        | 0.26%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 11        | 0.26%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 10        | 0.24%   |
| Goldstar 2D FHD TV GSM59C6 1920x1080 509x286mm 23.0-inch                 | 10        | 0.24%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 10        | 0.24%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 10        | 0.24%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 10        | 0.24%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 10        | 0.24%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch           | 10        | 0.24%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 9         | 0.21%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                  | 9         | 0.21%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch          | 9         | 0.21%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 9         | 0.21%   |
| Vestel Elektronik 24W_LCD_TV VES3700 1920x1080 706x398mm 31.9-inch       | 8         | 0.19%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 8         | 0.19%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                         | 8         | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1626      | 41.91%  |
| 1366x768 (WXGA)    | 683       | 17.6%   |
| 1280x1024 (SXGA)   | 186       | 4.79%   |
| 1600x900 (HD+)     | 175       | 4.51%   |
| 3840x2160 (4K)     | 172       | 4.43%   |
| 1280x800 (WXGA)    | 165       | 4.25%   |
| 1680x1050 (WSXGA+) | 156       | 4.02%   |
| 2560x1440 (QHD)    | 151       | 3.89%   |
| 1920x1200 (WUXGA)  | 125       | 3.22%   |
| 1440x900 (WXGA+)   | 117       | 3.02%   |
| Unknown            | 41        | 1.06%   |
| 2560x1080          | 31        | 0.8%    |
| 3440x1440          | 30        | 0.77%   |
| 1024x600           | 25        | 0.64%   |
| 1024x768 (XGA)     | 20        | 0.52%   |
| 1360x768           | 19        | 0.49%   |
| 3840x1080          | 18        | 0.46%   |
| 2560x1600          | 17        | 0.44%   |
| 1600x1200          | 17        | 0.44%   |
| 1920x540           | 9         | 0.23%   |
| 2160x1440          | 7         | 0.18%   |
| 3840x2400          | 6         | 0.15%   |
| 3200x1800 (QHD+)   | 6         | 0.15%   |
| 800x1280           | 5         | 0.13%   |
| 2048x1152          | 5         | 0.13%   |
| 1280x720 (HD)      | 5         | 0.13%   |
| 2288x1287          | 4         | 0.1%    |
| 1680x945           | 4         | 0.1%    |
| 1400x1050          | 4         | 0.1%    |
| 5120x1440          | 3         | 0.08%   |
| 3840x1600          | 3         | 0.08%   |
| 3286x1080          | 3         | 0.08%   |
| 3200x1080          | 3         | 0.08%   |
| 1280x960           | 3         | 0.08%   |
| 1280x768           | 3         | 0.08%   |
| 3840x1200          | 2         | 0.05%   |
| 3600x1080          | 2         | 0.05%   |
| 3000x2000          | 2         | 0.05%   |
| 2880x1800          | 2         | 0.05%   |
| 2256x1504          | 2         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1119      | 27.39%  |
| 24      | 322       | 7.88%   |
| 13      | 292       | 7.15%   |
| 14      | 283       | 6.93%   |
| 23      | 276       | 6.76%   |
| 17      | 260       | 6.36%   |
| 21      | 247       | 6.05%   |
| 27      | 236       | 5.78%   |
| Unknown | 230       | 5.63%   |
| 19      | 156       | 3.82%   |
| 22      | 93        | 2.28%   |
| 12      | 82        | 2.01%   |
| 18      | 64        | 1.57%   |
| 34      | 52        | 1.27%   |
| 31      | 49        | 1.2%    |
| 20      | 42        | 1.03%   |
| 11      | 30        | 0.73%   |
| 10      | 27        | 0.66%   |
| 84      | 26        | 0.64%   |
| 72      | 23        | 0.56%   |
| 25      | 23        | 0.56%   |
| 32      | 20        | 0.49%   |
| 54      | 18        | 0.44%   |
| 16      | 16        | 0.39%   |
| 48      | 11        | 0.27%   |
| 40      | 9         | 0.22%   |
| 42      | 8         | 0.2%    |
| 28      | 8         | 0.2%    |
| 65      | 7         | 0.17%   |
| 33      | 7         | 0.17%   |
| 49      | 6         | 0.15%   |
| 46      | 6         | 0.15%   |
| 26      | 6         | 0.15%   |
| 37      | 5         | 0.12%   |
| 39      | 4         | 0.1%    |
| 142     | 3         | 0.07%   |
| 43      | 3         | 0.07%   |
| 35      | 3         | 0.07%   |
| 29      | 3         | 0.07%   |
| 55      | 2         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1603      | 39.95%  |
| 501-600        | 793       | 19.76%  |
| 401-500        | 499       | 12.43%  |
| 351-400        | 327       | 8.15%   |
| 201-300        | 264       | 6.58%   |
| Unknown        | 230       | 5.73%   |
| 701-800        | 79        | 1.97%   |
| 601-700        | 77        | 1.92%   |
| 1001-1500      | 56        | 1.4%    |
| 1501-2000      | 49        | 1.22%   |
| 801-900        | 21        | 0.52%   |
| 901-1000       | 11        | 0.27%   |
| More than 2000 | 3         | 0.07%   |
| 1-100          | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2590      | 70.21%  |
| 16/10   | 551       | 14.94%  |
| Unknown | 202       | 5.48%   |
| 5/4     | 174       | 4.72%   |
| 21/9    | 59        | 1.6%    |
| 4/3     | 46        | 1.25%   |
| 3/2     | 42        | 1.14%   |
| 32/9    | 12        | 0.33%   |
| 6/5     | 5         | 0.14%   |
| 0.62    | 5         | 0.14%   |
| 1.00    | 3         | 0.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1114      | 27.53%  |
| 201-250        | 724       | 17.89%  |
| 81-90          | 463       | 11.44%  |
| 151-200        | 260       | 6.42%   |
| 301-350        | 240       | 5.93%   |
| Unknown        | 230       | 5.68%   |
| 251-300        | 160       | 3.95%   |
| 121-130        | 146       | 3.61%   |
| 351-500        | 137       | 3.39%   |
| 141-150        | 130       | 3.21%   |
| 71-80          | 106       | 2.62%   |
| More than 1000 | 94        | 2.32%   |
| 61-70          | 80        | 1.98%   |
| 501-1000       | 44        | 1.09%   |
| 131-140        | 34        | 0.84%   |
| 51-60          | 30        | 0.74%   |
| 41-50          | 27        | 0.67%   |
| 91-100         | 15        | 0.37%   |
| 111-120        | 12        | 0.3%    |
| 1-40           | 1         | 0.02%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1415      | 36.06%  |
| 121-160       | 1024      | 26.1%   |
| 101-120       | 999       | 25.46%  |
| Unknown       | 230       | 5.86%   |
| 161-240       | 124       | 3.16%   |
| 1-50          | 82        | 2.09%   |
| More than 240 | 50        | 1.27%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3001      | 78.99%  |
| 2     | 556       | 14.64%  |
| 0     | 152       | 4%      |
| 3     | 78        | 2.05%   |
| 4     | 12        | 0.32%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1883      | 32.88%  |
| Intel                                  | 1782      | 31.12%  |
| Qualcomm Atheros                       | 726       | 12.68%  |
| Broadcom                               | 332       | 5.8%    |
| Broadcom Limited                       | 106       | 1.85%   |
| Marvell Technology Group               | 78        | 1.36%   |
| TP-Link                                | 77        | 1.34%   |
| Huawei Technologies                    | 75        | 1.31%   |
| Ralink Technology                      | 62        | 1.08%   |
| Ralink                                 | 62        | 1.08%   |
| Nvidia                                 | 59        | 1.03%   |
| Dell                                   | 56        | 0.98%   |
| Qualcomm Atheros Communications        | 41        | 0.72%   |
| Xiaomi                                 | 30        | 0.52%   |
| Samsung Electronics                    | 30        | 0.52%   |
| Microsoft                              | 27        | 0.47%   |
| MediaTek                               | 26        | 0.45%   |
| Ericsson Business Mobile Networks      | 25        | 0.44%   |
| ASUSTek Computer                       | 23        | 0.4%    |
| Hewlett-Packard                        | 16        | 0.28%   |
| JMicron Technology                     | 15        | 0.26%   |
| Sierra Wireless                        | 14        | 0.24%   |
| Lenovo                                 | 11        | 0.19%   |
| VIA Technologies                       | 10        | 0.17%   |
| Motorola PCS                           | 10        | 0.17%   |
| ASIX Electronics                       | 10        | 0.17%   |
| Silicon Integrated Systems [SiS]       | 9         | 0.16%   |
| NetGear                                | 8         | 0.14%   |
| FIBOCOM                                | 8         | 0.14%   |
| Edimax Technology                      | 8         | 0.14%   |
| DisplayLink                            | 8         | 0.14%   |
| D-Link                                 | 8         | 0.14%   |
| Aquantia                               | 8         | 0.14%   |
| Qualcomm                               | 6         | 0.1%    |
| Sony Ericsson Mobile Communications AB | 5         | 0.09%   |
| OnePlus Technology (Shenzhen)          | 5         | 0.09%   |
| Microchip Technology                   | 5         | 0.09%   |
| Sagem                                  | 4         | 0.07%   |
| HTC (High Tech Computer)               | 4         | 0.07%   |
| ZTE WCDMA Technologies MSM             | 3         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 1379      | 20.61%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 216       | 3.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 193       | 2.88%   |
| Intel Wi-Fi 6 AX200                                                     | 130       | 1.94%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 104       | 1.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 100       | 1.49%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 98        | 1.46%   |
| Intel Wireless 8265 / 8275                                              | 96        | 1.43%   |
| Intel Wireless 7260                                                     | 96        | 1.43%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 83        | 1.24%   |
| Intel Wireless 8260                                                     | 74        | 1.11%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 70        | 1.05%   |
| Intel I211 Gigabit Network Connection                                   | 68        | 1.02%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 67        | 1%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 65        | 0.97%   |
| Intel Ethernet Connection I217-LM                                       | 60        | 0.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 59        | 0.88%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 59        | 0.88%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 58        | 0.87%   |
| Intel Wireless 7265                                                     | 55        | 0.82%   |
| Intel Wireless 3160                                                     | 50        | 0.75%   |
| Intel 82579V Gigabit Network Connection                                 | 48        | 0.72%   |
| Intel Ethernet Connection (2) I219-V                                    | 47        | 0.7%    |
| Intel 82567LM Gigabit Network Connection                                | 47        | 0.7%    |
| Intel Wireless 3165                                                     | 46        | 0.69%   |
| Intel Wi-Fi 6 AX201                                                     | 45        | 0.67%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 44        | 0.66%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 44        | 0.66%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 44        | 0.66%   |
| Realtek RTL8125 2.5GbE Controller                                       | 43        | 0.64%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 43        | 0.64%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 43        | 0.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 41        | 0.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 40        | 0.6%    |
| Huawei E353/E3131                                                       | 40        | 0.6%    |
| Intel Ethernet Connection I218-LM                                       | 39        | 0.58%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 38        | 0.57%   |
| Intel WiFi Link 5100                                                    | 38        | 0.57%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 38        | 0.57%   |
| Intel Centrino Ultimate-N 6300                                          | 37        | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1356      | 46.15%  |
| Qualcomm Atheros                  | 551       | 18.75%  |
| Realtek Semiconductor             | 365       | 12.42%  |
| Broadcom                          | 190       | 6.47%   |
| TP-Link                           | 72        | 2.45%   |
| Ralink Technology                 | 62        | 2.11%   |
| Ralink                            | 62        | 2.11%   |
| Broadcom Limited                  | 50        | 1.7%    |
| Qualcomm Atheros Communications   | 41        | 1.4%    |
| Dell                              | 35        | 1.19%   |
| Microsoft                         | 27        | 0.92%   |
| MediaTek                          | 23        | 0.78%   |
| ASUSTek Computer                  | 23        | 0.78%   |
| Sierra Wireless                   | 14        | 0.48%   |
| FIBOCOM                           | 8         | 0.27%   |
| Ericsson Business Mobile Networks | 8         | 0.27%   |
| Edimax Technology                 | 8         | 0.27%   |
| D-Link                            | 8         | 0.27%   |
| NetGear                           | 7         | 0.24%   |
| Hewlett-Packard                   | 5         | 0.17%   |
| Sagem                             | 4         | 0.14%   |
| Qualcomm                          | 4         | 0.14%   |
| ZyXEL Communications              | 2         | 0.07%   |
| ZyDAS                             | 2         | 0.07%   |
| Linksys                           | 2         | 0.07%   |
| D-Link System                     | 2         | 0.07%   |
| Belkin Components                 | 2         | 0.07%   |
| Wacom                             | 1         | 0.03%   |
| Tenda                             | 1         | 0.03%   |
| IMC Networks                      | 1         | 0.03%   |
| AVM                               | 1         | 0.03%   |
| Accton Technology                 | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 130       | 4.42%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 104       | 3.53%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 100       | 3.4%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 98        | 3.33%   |
| Intel Wireless 8265 / 8275                                              | 96        | 3.26%   |
| Intel Wireless 7260                                                     | 96        | 3.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 83        | 2.82%   |
| Intel Wireless 8260                                                     | 74        | 2.51%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 70        | 2.38%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 67        | 2.28%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 65        | 2.21%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 59        | 2%      |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 58        | 1.97%   |
| Intel Wireless 7265                                                     | 55        | 1.87%   |
| Intel Wireless 3160                                                     | 50        | 1.7%    |
| Intel Wireless 3165                                                     | 46        | 1.56%   |
| Intel Wi-Fi 6 AX201                                                     | 45        | 1.53%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 44        | 1.49%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 44        | 1.49%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 43        | 1.46%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 43        | 1.46%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 41        | 1.39%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 40        | 1.36%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 38        | 1.29%   |
| Intel WiFi Link 5100                                                    | 38        | 1.29%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 38        | 1.29%   |
| Intel Centrino Ultimate-N 6300                                          | 37        | 1.26%   |
| Broadcom BCM43142 802.11b/g/n                                           | 36        | 1.22%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 34        | 1.15%   |
| Qualcomm Atheros AR9271 802.11n                                         | 31        | 1.05%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 30        | 1.02%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 29        | 0.99%   |
| Intel Wireless-AC 9260                                                  | 29        | 0.99%   |
| Ralink MT7601U Wireless Adapter                                         | 28        | 0.95%   |
| Intel Centrino Advanced-N 6200                                          | 28        | 0.95%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 27        | 0.92%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 27        | 0.92%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 27        | 0.92%   |
| Intel Centrino Advanced-N 6235                                          | 27        | 0.92%   |
| Intel Centrino Wireless-N 2230                                          | 23        | 0.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1739      | 48.44%  |
| Intel                                  | 988       | 27.52%  |
| Qualcomm Atheros                       | 255       | 7.1%    |
| Broadcom                               | 174       | 4.85%   |
| Marvell Technology Group               | 78        | 2.17%   |
| Nvidia                                 | 59        | 1.64%   |
| Broadcom Limited                       | 57        | 1.59%   |
| Huawei Technologies                    | 48        | 1.34%   |
| Xiaomi                                 | 29        | 0.81%   |
| Samsung Electronics                    | 29        | 0.81%   |
| JMicron Technology                     | 15        | 0.42%   |
| Lenovo                                 | 11        | 0.31%   |
| VIA Technologies                       | 10        | 0.28%   |
| ASIX Electronics                       | 10        | 0.28%   |
| Silicon Integrated Systems [SiS]       | 9         | 0.25%   |
| Motorola PCS                           | 9         | 0.25%   |
| DisplayLink                            | 8         | 0.22%   |
| Aquantia                               | 8         | 0.22%   |
| TP-Link                                | 6         | 0.17%   |
| Microchip Technology                   | 5         | 0.14%   |
| Sony Ericsson Mobile Communications AB | 4         | 0.11%   |
| OnePlus Technology (Shenzhen)          | 3         | 0.08%   |
| HTC (High Tech Computer)               | 3         | 0.08%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.06%   |
| Research In Motion                     | 2         | 0.06%   |
| Qualcomm                               | 2         | 0.06%   |
| QLogic                                 | 2         | 0.06%   |
| MediaTek                               | 2         | 0.06%   |
| ICS Advent                             | 2         | 0.06%   |
| Hewlett-Packard                        | 2         | 0.06%   |
| Google                                 | 2         | 0.06%   |
| Attansic Technology                    | 2         | 0.06%   |
| Apple                                  | 2         | 0.06%   |
| 3Com                                   | 2         | 0.06%   |
| QinHeng Electronics                    | 1         | 0.03%   |
| OPPO Electronics                       | 1         | 0.03%   |
| NetXen Incorporated                    | 1         | 0.03%   |
| NetGear                                | 1         | 0.03%   |
| Mellanox Technologies                  | 1         | 0.03%   |
| LG Electronics                         | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1379      | 37.85%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 216       | 5.93%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 193       | 5.3%    |
| Intel I211 Gigabit Network Connection                             | 68        | 1.87%   |
| Intel Ethernet Connection I217-LM                                 | 60        | 1.65%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 59        | 1.62%   |
| Intel 82579V Gigabit Network Connection                           | 48        | 1.32%   |
| Intel Ethernet Connection (2) I219-V                              | 47        | 1.29%   |
| Intel 82567LM Gigabit Network Connection                          | 47        | 1.29%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 44        | 1.21%   |
| Realtek RTL8125 2.5GbE Controller                                 | 43        | 1.18%   |
| Huawei E353/E3131                                                 | 40        | 1.1%    |
| Intel Ethernet Connection I218-LM                                 | 39        | 1.07%   |
| Intel Ethernet Connection (7) I219-V                              | 36        | 0.99%   |
| Intel 82577LM Gigabit Network Connection                          | 36        | 0.99%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 34        | 0.93%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 30        | 0.82%   |
| Nvidia MCP61 Ethernet                                             | 30        | 0.82%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 29        | 0.8%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 28        | 0.77%   |
| Intel Ethernet Connection (2) I219-LM                             | 28        | 0.77%   |
| Intel Ethernet Connection (6) I219-V                              | 26        | 0.71%   |
| Intel Ethernet Connection (4) I219-LM                             | 26        | 0.71%   |
| Intel Ethernet Connection (3) I218-LM                             | 24        | 0.66%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 23        | 0.63%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 22        | 0.6%    |
| Intel Ethernet Connection (7) I219-LM                             | 22        | 0.6%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 21        | 0.58%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 21        | 0.58%   |
| Intel Ethernet Connection I219-LM                                 | 20        | 0.55%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 20        | 0.55%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 18        | 0.49%   |
| Intel Ethernet Connection (4) I219-V                              | 18        | 0.49%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 18        | 0.49%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 18        | 0.49%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 17        | 0.47%   |
| Intel Ethernet Connection (2) I218-V                              | 17        | 0.47%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 16        | 0.44%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 16        | 0.44%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 16        | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3374      | 54.12%  |
| WiFi     | 2757      | 44.23%  |
| Modem    | 94        | 1.51%   |
| Unknown  | 9         | 0.14%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2120      | 56.37%  |
| Ethernet | 1640      | 43.61%  |
| Unknown  | 1         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2168      | 58.31%  |
| 1     | 1399      | 37.63%  |
| 0     | 81        | 2.18%   |
| 3     | 53        | 1.43%   |
| 4     | 8         | 0.22%   |
| 5     | 3         | 0.08%   |
| 6     | 2         | 0.05%   |
| 17    | 1         | 0.03%   |
| 10    | 1         | 0.03%   |
| 9     | 1         | 0.03%   |
| 8     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3518      | 94.27%  |
| Yes  | 214       | 5.73%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 923       | 44.85%  |
| Qualcomm Atheros Communications | 208       | 10.11%  |
| Broadcom                        | 158       | 7.68%   |
| Realtek Semiconductor           | 134       | 6.51%   |
| Cambridge Silicon Radio         | 130       | 6.32%   |
| ASUSTek Computer                | 79        | 3.84%   |
| IMC Networks                    | 74        | 3.6%    |
| Dell                            | 71        | 3.45%   |
| Hewlett-Packard                 | 53        | 2.58%   |
| Lite-On Technology              | 48        | 2.33%   |
| Foxconn / Hon Hai               | 46        | 2.24%   |
| Apple                           | 24        | 1.17%   |
| Toshiba                         | 23        | 1.12%   |
| Ralink                          | 16        | 0.78%   |
| Foxconn International           | 14        | 0.68%   |
| Realtek                         | 10        | 0.49%   |
| Integrated System Solution      | 7         | 0.34%   |
| Chicony Electronics             | 6         | 0.29%   |
| Taiyo Yuden                     | 5         | 0.24%   |
| Edimax Technology               | 5         | 0.24%   |
| Alps Electric                   | 5         | 0.24%   |
| Ralink Technology               | 3         | 0.15%   |
| Micro Star International        | 2         | 0.1%    |
| MediaTek                        | 2         | 0.1%    |
| Conwise Technology              | 2         | 0.1%    |
| USI                             | 1         | 0.05%   |
| TP-Link                         | 1         | 0.05%   |
| SINO WEALTH                     | 1         | 0.05%   |
| Opticis                         | 1         | 0.05%   |
| Logitech                        | 1         | 0.05%   |
| Fujitsu                         | 1         | 0.05%   |
| Creative Technology             | 1         | 0.05%   |
| Askey Computer                  | 1         | 0.05%   |
| AboCom Systems                  | 1         | 0.05%   |
| Unknown                         | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 416       | 20.21%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 130       | 6.32%   |
| Intel AX200 Bluetooth                               | 126       | 6.12%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 120       | 5.83%   |
| Intel AX201 Bluetooth                               | 115       | 5.59%   |
| Qualcomm Atheros  Bluetooth Device                  | 86        | 4.18%   |
| Realtek Bluetooth Radio                             | 85        | 4.13%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 48        | 2.33%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 48        | 2.33%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 46        | 2.24%   |
| Intel Wireless-AC 3168 Bluetooth                    | 42        | 2.04%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 37        | 1.8%    |
| Broadcom BCM2045B (BDC-2.1)                         | 35        | 1.7%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 33        | 1.6%    |
| Realtek  Bluetooth 4.2 Adapter                      | 31        | 1.51%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 27        | 1.31%   |
| IMC Networks Bluetooth Radio                        | 25        | 1.21%   |
| Dell BCM20702A0 Bluetooth Module                    | 22        | 1.07%   |
| HP Broadcom 2070 Bluetooth Combo                    | 19        | 0.92%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 19        | 0.92%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 18        | 0.87%   |
| IMC Networks Bluetooth Device                       | 17        | 0.83%   |
| Dell DW375 Bluetooth Module                         | 17        | 0.83%   |
| Broadcom BCM2070 Bluetooth Device                   | 17        | 0.83%   |
| Ralink RT3290 Bluetooth                             | 16        | 0.78%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 16        | 0.78%   |
| Realtek RTL8723B Bluetooth                          | 15        | 0.73%   |
| Lite-On Bluetooth Device                            | 15        | 0.73%   |
| Lite-On Atheros AR3012 Bluetooth                    | 14        | 0.68%   |
| Foxconn International BCM43142A0 Bluetooth module   | 14        | 0.68%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 12        | 0.58%   |
| Broadcom BCM2045 Bluetooth                          | 12        | 0.58%   |
| Dell Wireless 370 Bluetooth Mini-card               | 11        | 0.53%   |
| Broadcom HP Portable SoftSailing                    | 11        | 0.53%   |
| Toshiba Integrated Bluetooth HCI                    | 10        | 0.49%   |
| Realtek Bluetooth Radio                             | 10        | 0.49%   |
| IMC Networks Wireless_Device                        | 10        | 0.49%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 10        | 0.49%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 10        | 0.49%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 9         | 0.44%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 2691      | 52.79%  |
| AMD                                  | 1001      | 19.64%  |
| Nvidia                               | 927       | 18.18%  |
| Creative Labs                        | 75        | 1.47%   |
| C-Media Electronics                  | 70        | 1.37%   |
| Creative Technology                  | 35        | 0.69%   |
| Logitech                             | 20        | 0.39%   |
| VIA Technologies                     | 19        | 0.37%   |
| Texas Instruments                    | 18        | 0.35%   |
| JMTek                                | 17        | 0.33%   |
| Realtek Semiconductor                | 16        | 0.31%   |
| Plantronics                          | 14        | 0.27%   |
| Lenovo                               | 12        | 0.24%   |
| Silicon Integrated Systems [SiS]     | 11        | 0.22%   |
| SteelSeries ApS                      | 10        | 0.2%    |
| GYROCOM C&C                          | 10        | 0.2%    |
| Dell                                 | 9         | 0.18%   |
| Kingston Technology                  | 8         | 0.16%   |
| Generalplus Technology               | 8         | 0.16%   |
| Focusrite-Novation                   | 7         | 0.14%   |
| SAVITECH                             | 6         | 0.12%   |
| Samson Technologies                  | 5         | 0.1%    |
| Razer USA                            | 5         | 0.1%    |
| GN Netcom                            | 5         | 0.1%    |
| BEHRINGER International              | 5         | 0.1%    |
| ASUSTek Computer                     | 5         | 0.1%    |
| Valve Software                       | 4         | 0.08%   |
| Hewlett-Packard                      | 4         | 0.08%   |
| Sennheiser Communications            | 3         | 0.06%   |
| PreSonus Audio Electronics           | 3         | 0.06%   |
| M-Audio                              | 3         | 0.06%   |
| Corsair                              | 3         | 0.06%   |
| AudioQuest                           | 3         | 0.06%   |
| XMOS                                 | 2         | 0.04%   |
| ULi Electronics                      | 2         | 0.04%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.04%   |
| Sony                                 | 2         | 0.04%   |
| SM900T Microphone                    | 2         | 0.04%   |
| RODE Microphones                     | 2         | 0.04%   |
| Giga-Byte Technology                 | 2         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 310       | 5.18%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 238       | 3.98%   |
| AMD Family 17h/19h HD Audio Controller                                     | 229       | 3.83%   |
| Intel Sunrise Point-LP HD Audio                                            | 218       | 3.64%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 195       | 3.26%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 189       | 3.16%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 163       | 2.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 155       | 2.59%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 145       | 2.42%   |
| Intel Cannon Lake PCH cAVS                                                 | 143       | 2.39%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 139       | 2.32%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 124       | 2.07%   |
| AMD Starship/Matisse HD Audio Controller                                   | 124       | 2.07%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 123       | 2.06%   |
| AMD FCH Azalia Controller                                                  | 119       | 1.99%   |
| Intel 8 Series HD Audio Controller                                         | 115       | 1.92%   |
| Intel Haswell-ULT HD Audio Controller                                      | 113       | 1.89%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 104       | 1.74%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 91        | 1.52%   |
| Nvidia GP107GL High Definition Audio Controller                            | 90        | 1.5%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 87        | 1.45%   |
| Intel Broadwell-U Audio Controller                                         | 86        | 1.44%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 85        | 1.42%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 78        | 1.3%    |
| Nvidia GF108 High Definition Audio Controller                              | 75        | 1.25%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 73        | 1.22%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 68        | 1.14%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 66        | 1.1%    |
| Nvidia GP106 High Definition Audio Controller                              | 58        | 0.97%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 58        | 0.97%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 54        | 0.9%    |
| Intel 200 Series PCH HD Audio                                              | 54        | 0.9%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 51        | 0.85%   |
| Intel CM238 HD Audio Controller                                            | 50        | 0.84%   |
| Nvidia GP104 High Definition Audio Controller                              | 49        | 0.82%   |
| Nvidia TU116 High Definition Audio Controller                              | 48        | 0.8%    |
| Nvidia High Definition Audio Controller                                    | 47        | 0.79%   |
| AMD Kabini HDMI/DP Audio                                                   | 43        | 0.72%   |
| Nvidia GK107 HDMI Audio Controller                                         | 41        | 0.69%   |
| Intel Comet Lake PCH-LP cAVS                                               | 41        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 549       | 20.6%   |
| SK hynix                     | 431       | 16.17%  |
| Kingston                     | 365       | 13.7%   |
| Unknown                      | 352       | 13.21%  |
| Micron Technology            | 204       | 7.65%   |
| Goodram                      | 157       | 5.89%   |
| Crucial                      | 126       | 4.73%   |
| G.Skill                      | 79        | 2.96%   |
| Corsair                      | 63        | 2.36%   |
| A-DATA Technology            | 59        | 2.21%   |
| Ramaxel Technology           | 48        | 1.8%    |
| Nanya Technology             | 44        | 1.65%   |
| Patriot                      | 42        | 1.58%   |
| Elpida                       | 38        | 1.43%   |
| Qimonda                      | 12        | 0.45%   |
| Unknown                      | 12        | 0.45%   |
| Unknown (ABCD)               | 9         | 0.34%   |
| ASint Technology             | 9         | 0.34%   |
| Wilk Elektronik              | 8         | 0.3%    |
| GeIL                         | 8         | 0.3%    |
| Wilk                         | 7         | 0.26%   |
| Apacer                       | 6         | 0.23%   |
| Unifosa                      | 4         | 0.15%   |
| 48spaces                     | 4         | 0.15%   |
| Patriot Memory (PDP Systems) | 3         | 0.11%   |
| OCZ                          | 3         | 0.11%   |
| Toshiba                      | 2         | 0.08%   |
| Silicon Power                | 2         | 0.08%   |
| Aeneon                       | 2         | 0.08%   |
| Unknown (8A02)               | 1         | 0.04%   |
| Unknown (0x0702)             | 1         | 0.04%   |
| Transcend                    | 1         | 0.04%   |
| tigo                         | 1         | 0.04%   |
| Team                         | 1         | 0.04%   |
| Swissbit                     | 1         | 0.04%   |
| Smart                        | 1         | 0.04%   |
| SHARETRONIC                  | 1         | 0.04%   |
| PNY                          | 1         | 0.04%   |
| ISD Technology Limited       | 1         | 0.04%   |
| Hewlett-Packard              | 1         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s      | 31        | 1.06%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s      | 26        | 0.89%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                 | 23        | 0.79%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s     | 23        | 0.79%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s  | 22        | 0.75%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s  | 22        | 0.75%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s      | 22        | 0.75%   |
| GOODRAM RAM GR2666S464L19/16G 16384MB SODIMM DDR4 2667MT/s | 19        | 0.65%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                     | 18        | 0.62%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s      | 18        | 0.62%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s      | 18        | 0.62%   |
| Kingston RAM 9905403-559.A00LF 8GB DIMM DDR3 1600MT/s      | 18        | 0.62%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s     | 17        | 0.58%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s      | 17        | 0.58%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s      | 17        | 0.58%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 15        | 0.51%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                    | 13        | 0.44%   |
| Kingston RAM KHX2400C14S4/16G 16GB SODIMM DDR4 2667MT/s    | 13        | 0.44%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s      | 13        | 0.44%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                    | 12        | 0.41%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s      | 12        | 0.41%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 12        | 0.41%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s      | 12        | 0.41%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s     | 12        | 0.41%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s      | 12        | 0.41%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3200MT/s         | 12        | 0.41%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s      | 12        | 0.41%   |
| GOODRAM RAM GR3200S464L22/16G 16384MB SODIMM DDR4 3200MT/s | 12        | 0.41%   |
| Unknown                                                    | 12        | 0.41%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s      | 11        | 0.38%   |
| Samsung RAM M471B5673FH0-CF8 2048MB SODIMM DDR3 1067MT/s   | 11        | 0.38%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s      | 11        | 0.38%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s        | 11        | 0.38%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s        | 11        | 0.38%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s     | 10        | 0.34%   |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s   | 10        | 0.34%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s      | 10        | 0.34%   |
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 8400MT/s  | 10        | 0.34%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s      | 10        | 0.34%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s    | 10        | 0.34%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 864       | 38.26%  |
| DDR3    | 843       | 37.33%  |
| DDR2    | 206       | 9.12%   |
| Unknown | 121       | 5.36%   |
| SDRAM   | 106       | 4.69%   |
| LPDDR4  | 42        | 1.86%   |
| LPDDR3  | 32        | 1.42%   |
| DDR     | 32        | 1.42%   |
| DRAM    | 6         | 0.27%   |
| DDR5    | 5         | 0.22%   |
| LPDDR5  | 1         | 0.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1322      | 59.5%   |
| DIMM         | 819       | 36.86%  |
| Row Of Chips | 65        | 2.93%   |
| Chip         | 9         | 0.41%   |
| Unknown      | 5         | 0.23%   |
| RIMM         | 2         | 0.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 8192    | 735       | 29.46%  |
| 4096    | 706       | 28.3%   |
| 2048    | 467       | 18.72%  |
| 16384   | 312       | 12.51%  |
| 1024    | 175       | 7.01%   |
| 32768   | 65        | 2.61%   |
| 512     | 26        | 1.04%   |
| Unknown | 4         | 0.16%   |
| 1536    | 2         | 0.08%   |
| 256     | 2         | 0.08%   |
| 64      | 1         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 582       | 23.35%  |
| 2667    | 328       | 13.16%  |
| 3200    | 259       | 10.39%  |
| 1333    | 175       | 7.02%   |
| 2400    | 142       | 5.7%    |
| 667     | 112       | 4.49%   |
| 800     | 105       | 4.21%   |
| 1334    | 104       | 4.17%   |
| 2133    | 96        | 3.85%   |
| Unknown | 68        | 2.73%   |
| 3600    | 59        | 2.37%   |
| 1067    | 49        | 1.97%   |
| 4199    | 31        | 1.24%   |
| 533     | 31        | 1.24%   |
| 1867    | 29        | 1.16%   |
| 1066    | 25        | 1%      |
| 2048    | 23        | 0.92%   |
| 3466    | 22        | 0.88%   |
| 2933    | 22        | 0.88%   |
| 975     | 22        | 0.88%   |
| 3000    | 18        | 0.72%   |
| 400     | 18        | 0.72%   |
| 4267    | 14        | 0.56%   |
| 1866    | 14        | 0.56%   |
| 1800    | 12        | 0.48%   |
| 3733    | 11        | 0.44%   |
| 3400    | 11        | 0.44%   |
| 3266    | 11        | 0.44%   |
| 8400    | 10        | 0.4%    |
| 333     | 10        | 0.4%    |
| 2666    | 9         | 0.36%   |
| 4800    | 7         | 0.28%   |
| 3800    | 7         | 0.28%   |
| 4266    | 5         | 0.2%    |
| 2866    | 5         | 0.2%    |
| 49926   | 4         | 0.16%   |
| 2800    | 4         | 0.16%   |
| 3866    | 3         | 0.12%   |
| 2000    | 3         | 0.12%   |
| 1639    | 3         | 0.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 44        | 46.81%  |
| Samsung Electronics   | 12        | 12.77%  |
| Brother Industries    | 11        | 11.7%   |
| Canon                 | 9         | 9.57%   |
| Seiko Epson           | 7         | 7.45%   |
| Prolific Technology   | 5         | 5.32%   |
| Zebra                 | 2         | 2.13%   |
| Xerox                 | 2         | 2.13%   |
| Lexmark International | 1         | 1.06%   |
| Datamax-O'Neil        | 1         | 1.06%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port           | 5         | 5.21%   |
| HP LaserJet 1020                        | 4         | 4.17%   |
| Canon iP7200 series                     | 3         | 3.13%   |
| Seiko Epson AL-M310DN                   | 2         | 2.08%   |
| Samsung ML-216x Series Laser Printer    | 2         | 2.08%   |
| Samsung ML-2010P Mono Laser Printer     | 2         | 2.08%   |
| HP LaserJet P2015 series                | 2         | 2.08%   |
| HP LaserJet P1102                       | 2         | 2.08%   |
| HP LaserJet M14-M17                     | 2         | 2.08%   |
| HP Deskjet F4500 series                 | 2         | 2.08%   |
| HP DeskJet F4100 Printer series         | 2         | 2.08%   |
| HP Deskjet F2280 series                 | 2         | 2.08%   |
| HP DeskJet 845c                         | 2         | 2.08%   |
| HP DeskJet 3700 series                  | 2         | 2.08%   |
| HP DeskJet 2620 All-in-One Printer      | 2         | 2.08%   |
| HP Deskjet 2540 series                  | 2         | 2.08%   |
| HP Deskjet 1050 J410                    | 2         | 2.08%   |
| Canon MG5600 series                     | 2         | 2.08%   |
| Brother DCP-J105                        | 2         | 2.08%   |
| Brother DCP-1610W                       | 2         | 2.08%   |
| Zebra ZTC GX420t                        | 1         | 1.04%   |
| Zebra LP2844 Printer                    | 1         | 1.04%   |
| Xerox WorkCentre PE16                   | 1         | 1.04%   |
| Xerox Phaser 6000B                      | 1         | 1.04%   |
| Seiko Epson Stylus NX230/SX235W Series  | 1         | 1.04%   |
| Seiko Epson L405 Series                 | 1         | 1.04%   |
| Seiko Epson L395 Series                 | 1         | 1.04%   |
| Seiko Epson L1110 Series                | 1         | 1.04%   |
| Seiko Epson ET-2710 Series              | 1         | 1.04%   |
| Samsung Xerox Phaser 3117 Laser Printer | 1         | 1.04%   |
| Samsung SCX-6545 Series                 | 1         | 1.04%   |
| Samsung SCX-4300 Series                 | 1         | 1.04%   |
| Samsung SCX-4200 series                 | 1         | 1.04%   |
| Samsung SCX-3400 Series                 | 1         | 1.04%   |
| Samsung ML-3050/ML-3051 Laser Printer   | 1         | 1.04%   |
| Samsung ML-2540 Series Laser Printer    | 1         | 1.04%   |
| Samsung M2020 Series                    | 1         | 1.04%   |
| Lexmark International Lexmark E352dn    | 1         | 1.04%   |
| HP Smart Tank 510 series                | 1         | 1.04%   |
| HP Printing Support                     | 1         | 1.04%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Canon                       | 10        | 58.82%  |
| Seiko Epson                 | 2         | 11.76%  |
| Plustek                     | 2         | 11.76%  |
| Ultima Electronics          | 1         | 5.88%   |
| Microtek International      | 1         | 5.88%   |
| Acer Peripherals (now BenQ) | 1         | 5.88%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 210                                  | 3         | 17.65%  |
| Canon CanoScan N670U/N676U/LiDE 20                       | 2         | 11.76%  |
| Canon CanoScan LiDE 110                                  | 2         | 11.76%  |
| Ultima Artec E+ 48U                                      | 1         | 5.88%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]      | 1         | 5.88%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 5.88%   |
| Plustek OpticSlim 1200 Scanner                           | 1         | 5.88%   |
| Plustek OpticPro 1248U Scanner #2                        | 1         | 5.88%   |
| Microtek International USB1200 Scanner                   | 1         | 5.88%   |
| Canon CanoScan N1240U/LiDE 30                            | 1         | 5.88%   |
| Canon CanoScan LIDE 25                                   | 1         | 5.88%   |
| Canon CanoScan LiDE 120                                  | 1         | 5.88%   |
| Acer Peripherals (now BenQ) S2W 3300U/4300U              | 1         | 5.88%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 469       | 22.67%  |
| Microdia                               | 209       | 10.1%   |
| IMC Networks                           | 207       | 10%     |
| Realtek Semiconductor                  | 177       | 8.55%   |
| Acer                                   | 145       | 7.01%   |
| Sunplus Innovation Technology          | 105       | 5.07%   |
| Suyin                                  | 88        | 4.25%   |
| Quanta                                 | 86        | 4.16%   |
| Logitech                               | 74        | 3.58%   |
| Cheng Uei Precision Industry (Foxlink) | 72        | 3.48%   |
| Syntek                                 | 59        | 2.85%   |
| Silicon Motion                         | 43        | 2.08%   |
| Lite-On Technology                     | 43        | 2.08%   |
| Creative Technology                    | 31        | 1.5%    |
| Ricoh                                  | 25        | 1.21%   |
| Apple                                  | 22        | 1.06%   |
| Alcor Micro                            | 22        | 1.06%   |
| Lenovo                                 | 21        | 1.01%   |
| Z-Star Microelectronics                | 18        | 0.87%   |
| Microsoft                              | 17        | 0.82%   |
| Luxvisions Innotech Limited            | 17        | 0.82%   |
| Samsung Electronics                    | 14        | 0.68%   |
| DigiTech                               | 11        | 0.53%   |
| Primax Electronics                     | 9         | 0.43%   |
| Generalplus Technology                 | 7         | 0.34%   |
| Cubeternet                             | 7         | 0.34%   |
| ALi                                    | 7         | 0.34%   |
| Intel                                  | 6         | 0.29%   |
| Hewlett-Packard                        | 6         | 0.29%   |
| LG Electronics                         | 4         | 0.19%   |
| GEMBIRD                                | 4         | 0.19%   |
| Aveo Technology                        | 4         | 0.19%   |
| Xiongmai                               | 3         | 0.14%   |
| Trust                                  | 3         | 0.14%   |
| Sunplus Technology                     | 3         | 0.14%   |
| Jieli Technology                       | 3         | 0.14%   |
| Importek                               | 3         | 0.14%   |
| Valve Software                         | 2         | 0.1%    |
| Sonix Technology                       | 2         | 0.1%    |
| Pixart Imaging                         | 2         | 0.1%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 92        | 4.43%   |
| Microdia Integrated_Webcam_HD            | 68        | 3.27%   |
| Realtek Integrated_Webcam_HD             | 58        | 2.79%   |
| IMC Networks Integrated Camera           | 55        | 2.65%   |
| IMC Networks USB2.0 HD UVC WebCam        | 50        | 2.41%   |
| Sunplus Integrated_Webcam_HD             | 44        | 2.12%   |
| Chicony Lenovo EasyCamera                | 39        | 1.88%   |
| Acer Lenovo EasyCamera                   | 34        | 1.64%   |
| Chicony HD WebCam                        | 31        | 1.49%   |
| Suyin Integrated_Webcam_HD               | 30        | 1.44%   |
| Microdia Integrated Webcam               | 29        | 1.4%    |
| Acer Integrated Camera                   | 27        | 1.3%    |
| Syntek Lenovo EasyCamera                 | 26        | 1.25%   |
| Realtek Lenovo EasyCamera                | 25        | 1.2%    |
| Realtek USB Camera                       | 21        | 1.01%   |
| Chicony USB2.0 HD UVC WebCam             | 21        | 1.01%   |
| Quanta HP TrueVision HD Camera           | 20        | 0.96%   |
| Lite-On Integrated Camera                | 20        | 0.96%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 19        | 0.91%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 18        | 0.87%   |
| Acer Lenovo Integrated Webcam            | 18        | 0.87%   |
| Syntek Integrated Camera                 | 17        | 0.82%   |
| Creative Live! Cam Sync HD [VF0770]      | 17        | 0.82%   |
| Realtek Integrated Webcam HD             | 16        | 0.77%   |
| Quanta HD User Facing                    | 15        | 0.72%   |
| Microdia Laptop_Integrated_Webcam_HD     | 15        | 0.72%   |
| Logitech Webcam C270                     | 15        | 0.72%   |
| IMC Networks Integrated Webcam           | 15        | 0.72%   |
| Chicony USB 2.0 Camera                   | 15        | 0.72%   |
| Chicony USB2.0 VGA UVC WebCam            | 14        | 0.67%   |
| Chicony HP HD Camera                     | 14        | 0.67%   |
| Samsung Galaxy A5 (MTP)                  | 13        | 0.63%   |
| Microdia Sonix USB 2.0 Camera            | 13        | 0.63%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 13        | 0.63%   |
| Acer SunplusIT Integrated Camera         | 13        | 0.63%   |
| Realtek Integrated Webcam                | 12        | 0.58%   |
| Chicony Integrated Camera (1280x720@30)  | 12        | 0.58%   |
| Chicony HP HD Webcam [Fixed]             | 12        | 0.58%   |
| Logitech HD Pro Webcam C920              | 11        | 0.53%   |
| Chicony EasyCamera                       | 11        | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 150       | 36.23%  |
| Synaptics                  | 102       | 24.64%  |
| AuthenTec                  | 52        | 12.56%  |
| Shenzhen Goodix Technology | 42        | 10.14%  |
| Upek                       | 30        | 7.25%   |
| LighTuning Technology      | 15        | 3.62%   |
| STMicroelectronics         | 13        | 3.14%   |
| Elan Microelectronics      | 10        | 2.42%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 34        | 8.21%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 30        | 7.25%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 29        | 7%      |
| Validity Sensors VFS5011 Fingerprint Reader                                | 22        | 5.31%   |
| Shenzhen Goodix  FingerPrint Device                                        | 22        | 5.31%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 20        | 4.83%   |
| AuthenTec AES2810                                                          | 20        | 4.83%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 18        | 4.35%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 17        | 4.11%   |
| Shenzhen Goodix Fingerprint Reader                                         | 16        | 3.86%   |
| Unknown                                                                    | 16        | 3.86%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 13        | 3.14%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 13        | 3.14%   |
| STMicroelectronics Fingerprint Reader                                      | 13        | 3.14%   |
| Validity Sensors VFS491                                                    | 11        | 2.66%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 9         | 2.17%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 8         | 1.93%   |
| Synaptics  WBDI                                                            | 8         | 1.93%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 7         | 1.69%   |
| Elan ELAN:Fingerprint                                                      | 7         | 1.69%   |
| AuthenTec AES1600                                                          | 7         | 1.69%   |
| Validity Sensors Fingerprint scanner                                       | 6         | 1.45%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 6         | 1.45%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 1.21%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 1.21%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 5         | 1.21%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 1.21%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 0.97%   |
| Validity Sensors VFS Fingerprint sensor                                    | 4         | 0.97%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 0.97%   |
| Shenzhen Goodix FingerPrint                                                | 4         | 0.97%   |
| LighTuning Fingerprint Reader                                              | 4         | 0.97%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 0.97%   |
| Synaptics WBDI Device                                                      | 3         | 0.72%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.72%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.48%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 0.48%   |
| Elan ELAN:ARM-M4                                                           | 2         | 0.48%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.24%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.24%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 166       | 54.97%  |
| Alcor Micro               | 57        | 18.87%  |
| O2 Micro                  | 36        | 11.92%  |
| Lenovo                    | 17        | 5.63%   |
| Upek                      | 14        | 4.64%   |
| Gemalto (was Gemplus)     | 5         | 1.66%   |
| OmniKey                   | 2         | 0.66%   |
| SCM Microsystems          | 1         | 0.33%   |
| Clay Logic                | 1         | 0.33%   |
| Cherry                    | 1         | 0.33%   |
| Aladdin Knowledge Systems | 1         | 0.33%   |
| Advanced Card Systems     | 1         | 0.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 57        | 18.87%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 54        | 17.88%  |
| Broadcom 5880                                                                | 42        | 13.91%  |
| Broadcom 58200                                                               | 35        | 11.59%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 31        | 10.26%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 29        | 9.6%    |
| Lenovo Integrated Smart Card Reader                                          | 17        | 5.63%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 14        | 4.64%   |
| O2 Micro Oz776 SmartCard Reader                                              | 7         | 2.32%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.99%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 0.66%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 2         | 0.66%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 0.66%   |
| SCM Microsystems SCR333 SmartCard Reader                                     | 1         | 0.33%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.33%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.33%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.33%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.33%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.33%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2632      | 69.32%  |
| 1     | 939       | 24.73%  |
| 2     | 190       | 5%      |
| 3     | 27        | 0.71%   |
| 4     | 4         | 0.11%   |
| 7     | 2         | 0.05%   |
| 5     | 2         | 0.05%   |
| 6     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 409       | 29.47%  |
| Graphics card            | 314       | 22.62%  |
| Chipcard                 | 275       | 19.81%  |
| Net/wireless             | 108       | 7.78%   |
| Multimedia controller    | 46        | 3.31%   |
| Storage                  | 41        | 2.95%   |
| Bluetooth                | 38        | 2.74%   |
| Communication controller | 37        | 2.67%   |
| Camera                   | 23        | 1.66%   |
| Sound                    | 20        | 1.44%   |
| Unassigned class         | 18        | 1.3%    |
| Card reader              | 14        | 1.01%   |
| Net/ethernet             | 7         | 0.5%    |
| Modem                    | 7         | 0.5%    |
| Firewire controller      | 7         | 0.5%    |
| Network                  | 6         | 0.43%   |
| Dvb card                 | 5         | 0.36%   |
| Storage/raid             | 4         | 0.29%   |
| Storage/ide              | 4         | 0.29%   |
| Flash memory             | 3         | 0.22%   |
| Wireless                 | 1         | 0.07%   |
| Tv card                  | 1         | 0.07%   |

