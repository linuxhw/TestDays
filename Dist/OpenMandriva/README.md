OpenMandriva - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for OpenMandriva.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/OpenMandriva/Desktop/README.md) and [notebooks](/Dist/OpenMandriva/Notebook/README.md).

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

Total: 9775

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | M5A97 PLUS                  | Desktop     | [63820e3937](https://linux-hardware.org/?probe=63820e3937) | Dec 01, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [929550dc41](https://linux-hardware.org/?probe=929550dc41) | Dec 01, 2022 |
| ASUSTek       | S551LN                      | Notebook    | [b21b106fdf](https://linux-hardware.org/?probe=b21b106fdf) | Dec 01, 2022 |
| ASUSTek       | PRIME B250M-K               | Desktop     | [97a1793680](https://linux-hardware.org/?probe=97a1793680) | Dec 01, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [794fbb64f9](https://linux-hardware.org/?probe=794fbb64f9) | Dec 01, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [1ebd8b1b89](https://linux-hardware.org/?probe=1ebd8b1b89) | Dec 01, 2022 |
| ASUSTek       | P5K WS                      | Desktop     | [f3608476bf](https://linux-hardware.org/?probe=f3608476bf) | Dec 01, 2022 |
| Medion        | MS-7748                     | Desktop     | [0e92aa55ca](https://linux-hardware.org/?probe=0e92aa55ca) | Nov 30, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [2e53fa79ed](https://linux-hardware.org/?probe=2e53fa79ed) | Nov 30, 2022 |
| Lenovo        | ThinkPad T530 24297ZG       | Notebook    | [422f84a794](https://linux-hardware.org/?probe=422f84a794) | Nov 30, 2022 |
| Samsung       | 300E5K/300E5Q               | Notebook    | [f6bb652f5a](https://linux-hardware.org/?probe=f6bb652f5a) | Nov 30, 2022 |
| ASUSTek       | Z170-E                      | Desktop     | [5e68d23175](https://linux-hardware.org/?probe=5e68d23175) | Nov 30, 2022 |
| Samsung       | 550XDA                      | Notebook    | [7614fde301](https://linux-hardware.org/?probe=7614fde301) | Nov 30, 2022 |
| Medion        | MS-7800                     | Desktop     | [a5658a6933](https://linux-hardware.org/?probe=a5658a6933) | Nov 30, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [1d20e4ba6d](https://linux-hardware.org/?probe=1d20e4ba6d) | Nov 30, 2022 |
| Dell          | 0YHMCJ A01                  | Server      | [77f946c99b](https://linux-hardware.org/?probe=77f946c99b) | Nov 30, 2022 |
| MACHINIST     | X99-D8-MAX V1.0             | Desktop     | [c2430965a1](https://linux-hardware.org/?probe=c2430965a1) | Nov 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [9505f905e8](https://linux-hardware.org/?probe=9505f905e8) | Nov 30, 2022 |
| Philco        | 14H                         | Notebook    | [8d29065667](https://linux-hardware.org/?probe=8d29065667) | Nov 30, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [f1d4630160](https://linux-hardware.org/?probe=f1d4630160) | Nov 30, 2022 |
| Dell          | Inspiron 5423               | Notebook    | [db57850733](https://linux-hardware.org/?probe=db57850733) | Nov 29, 2022 |
| ASRock        | H470M-HDV/M.2               | Desktop     | [c01129a199](https://linux-hardware.org/?probe=c01129a199) | Nov 29, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [1a742c23df](https://linux-hardware.org/?probe=1a742c23df) | Nov 29, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [3f545fe7c9](https://linux-hardware.org/?probe=3f545fe7c9) | Nov 29, 2022 |
| MSI           | D2414 S26361-D2414-A10      | Desktop     | [ef1367a574](https://linux-hardware.org/?probe=ef1367a574) | Nov 29, 2022 |
| Toshiba       | Satellite L40               | Notebook    | [fa36933936](https://linux-hardware.org/?probe=fa36933936) | Nov 29, 2022 |
| Lenovo        | IdeaPad 110-15AST 80TR      | Notebook    | [cbb0c1dca7](https://linux-hardware.org/?probe=cbb0c1dca7) | Nov 29, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [9d7352a65d](https://linux-hardware.org/?probe=9d7352a65d) | Nov 29, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [f03f3a9325](https://linux-hardware.org/?probe=f03f3a9325) | Nov 29, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [20219ca82a](https://linux-hardware.org/?probe=20219ca82a) | Nov 29, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [0bd83a29f4](https://linux-hardware.org/?probe=0bd83a29f4) | Nov 29, 2022 |
| Sony          | VGN-NS150FJ                 | Notebook    | [e675a19a27](https://linux-hardware.org/?probe=e675a19a27) | Nov 29, 2022 |
| ECS           | 945P/PL-A                   | Desktop     | [ff47651dd8](https://linux-hardware.org/?probe=ff47651dd8) | Nov 29, 2022 |
| Biostar       | H81MHV3 5.0                 | Desktop     | [d89a05dd31](https://linux-hardware.org/?probe=d89a05dd31) | Nov 29, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [c506dd4125](https://linux-hardware.org/?probe=c506dd4125) | Nov 28, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [d20243efed](https://linux-hardware.org/?probe=d20243efed) | Nov 28, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [97c63f232d](https://linux-hardware.org/?probe=97c63f232d) | Nov 28, 2022 |
| Toshiba       | Satellite L875              | Notebook    | [2d5e211d72](https://linux-hardware.org/?probe=2d5e211d72) | Nov 28, 2022 |
| Toshiba       | PORTEGE Z30t-A              | Notebook    | [8af94993bd](https://linux-hardware.org/?probe=8af94993bd) | Nov 28, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [3433fd5db6](https://linux-hardware.org/?probe=3433fd5db6) | Nov 28, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [51d2b67ca3](https://linux-hardware.org/?probe=51d2b67ca3) | Nov 28, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [e479f87a66](https://linux-hardware.org/?probe=e479f87a66) | Nov 28, 2022 |
| ASUSTek       | X555YA                      | Notebook    | [0e9bb436b5](https://linux-hardware.org/?probe=0e9bb436b5) | Nov 27, 2022 |
| Medion        | E11201                      | Notebook    | [0838f9db75](https://linux-hardware.org/?probe=0838f9db75) | Nov 27, 2022 |
| Gateway       | M-1631U                     | Notebook    | [f0f0517dab](https://linux-hardware.org/?probe=f0f0517dab) | Nov 27, 2022 |
| HP            | Compaq Presario CQ60        | Notebook    | [1f521f98cb](https://linux-hardware.org/?probe=1f521f98cb) | Nov 27, 2022 |
| Medion        | E2292                       | Convertible | [98818a6a22](https://linux-hardware.org/?probe=98818a6a22) | Nov 27, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [31f70fbb3e](https://linux-hardware.org/?probe=31f70fbb3e) | Nov 27, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [c218724cb4](https://linux-hardware.org/?probe=c218724cb4) | Nov 27, 2022 |
| MSI           | Z77MA-G45                   | Desktop     | [feb165c344](https://linux-hardware.org/?probe=feb165c344) | Nov 27, 2022 |
| ASRock        | A88M-G                      | Desktop     | [323199813d](https://linux-hardware.org/?probe=323199813d) | Nov 27, 2022 |
| Lenovo        | 3000 N500 42336DS           | Notebook    | [f3d917b782](https://linux-hardware.org/?probe=f3d917b782) | Nov 26, 2022 |
| MSI           | P55-CD53                    | Desktop     | [a602949484](https://linux-hardware.org/?probe=a602949484) | Nov 26, 2022 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [b680eec959](https://linux-hardware.org/?probe=b680eec959) | Nov 26, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [02b1483a02](https://linux-hardware.org/?probe=02b1483a02) | Nov 26, 2022 |
| ASUSTek       | X550CL                      | Notebook    | [06c7fdf5c9](https://linux-hardware.org/?probe=06c7fdf5c9) | Nov 26, 2022 |
| Dell          | Latitude E6220              | Notebook    | [aa8d2d2fc7](https://linux-hardware.org/?probe=aa8d2d2fc7) | Nov 26, 2022 |
| HP            | 3397                        | Desktop     | [c943f7435d](https://linux-hardware.org/?probe=c943f7435d) | Nov 26, 2022 |
| Dell          | Inspiron MP061              | Notebook    | [d70d7496df](https://linux-hardware.org/?probe=d70d7496df) | Nov 26, 2022 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [9419d2017e](https://linux-hardware.org/?probe=9419d2017e) | Nov 26, 2022 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [1eb32c408c](https://linux-hardware.org/?probe=1eb32c408c) | Nov 26, 2022 |
| HP            | 0AECh D                     | Desktop     | [857616948b](https://linux-hardware.org/?probe=857616948b) | Nov 26, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [3413fb7947](https://linux-hardware.org/?probe=3413fb7947) | Nov 26, 2022 |
| HP            | 1589                        | Desktop     | [077a89fb54](https://linux-hardware.org/?probe=077a89fb54) | Nov 26, 2022 |
| Dell          | 0VRWRC A00                  | Desktop     | [26bfa13122](https://linux-hardware.org/?probe=26bfa13122) | Nov 25, 2022 |
| ASUSTek       | P8B75-M LX PLUS             | Desktop     | [7948a35f59](https://linux-hardware.org/?probe=7948a35f59) | Nov 25, 2022 |
| Acer          | Aspire ES1-512              | Notebook    | [85c0936ee0](https://linux-hardware.org/?probe=85c0936ee0) | Nov 25, 2022 |
| Acer          | Veriton L6620G v1.0         | Desktop     | [33f168992e](https://linux-hardware.org/?probe=33f168992e) | Nov 25, 2022 |
| Acer          | NC-ES1-512-C3AH             | Notebook    | [0670f9ed15](https://linux-hardware.org/?probe=0670f9ed15) | Nov 25, 2022 |
| Dell          | Inspiron 7559               | Notebook    | [620f0d5cec](https://linux-hardware.org/?probe=620f0d5cec) | Nov 25, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | Notebook    | [a7b7f4f100](https://linux-hardware.org/?probe=a7b7f4f100) | Nov 25, 2022 |
| HP            | 2215                        | Desktop     | [0134898651](https://linux-hardware.org/?probe=0134898651) | Nov 25, 2022 |
| Lenovo        | B590 20208                  | Notebook    | [9f49ff06cf](https://linux-hardware.org/?probe=9f49ff06cf) | Nov 24, 2022 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | Notebook    | [418849100f](https://linux-hardware.org/?probe=418849100f) | Nov 24, 2022 |
| HP            | 650                         | Notebook    | [15c69c43ca](https://linux-hardware.org/?probe=15c69c43ca) | Nov 24, 2022 |
| Acer          | Aspire ES1-523              | Notebook    | [333d3583b1](https://linux-hardware.org/?probe=333d3583b1) | Nov 24, 2022 |
| MSI           | B75A-G43                    | Desktop     | [7f635dae7f](https://linux-hardware.org/?probe=7f635dae7f) | Nov 24, 2022 |
| HP            | EliteBook 8560p             | Notebook    | [e7bf51183d](https://linux-hardware.org/?probe=e7bf51183d) | Nov 24, 2022 |
| Wistron       | ProLiant ML110 G6           | Desktop     | [7d448ab5cc](https://linux-hardware.org/?probe=7d448ab5cc) | Nov 24, 2022 |
| HP            | ProBook 430 G3              | Notebook    | [0fa29b61e3](https://linux-hardware.org/?probe=0fa29b61e3) | Nov 24, 2022 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [81a2eaf6e4](https://linux-hardware.org/?probe=81a2eaf6e4) | Nov 24, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [600e3f0f09](https://linux-hardware.org/?probe=600e3f0f09) | Nov 24, 2022 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [adcb4db30d](https://linux-hardware.org/?probe=adcb4db30d) | Nov 24, 2022 |
| Unknown       | Unknown                     | Notebook    | [9b50d75b30](https://linux-hardware.org/?probe=9b50d75b30) | Nov 24, 2022 |
| ASRock        | X670E Taichi Carrara        | Desktop     | [7e844d7172](https://linux-hardware.org/?probe=7e844d7172) | Nov 24, 2022 |
| Foxconn       | 2A92                        | Desktop     | [e21715c047](https://linux-hardware.org/?probe=e21715c047) | Nov 24, 2022 |
| Supermicro    | PDSMi+                      | Desktop     | [3a70b82d42](https://linux-hardware.org/?probe=3a70b82d42) | Nov 24, 2022 |
| Intel         | B75                         | Desktop     | [a8932d4a21](https://linux-hardware.org/?probe=a8932d4a21) | Nov 24, 2022 |
| Lenovo        | ThinkPad T420 4180GH5       | Notebook    | [8dba4b2123](https://linux-hardware.org/?probe=8dba4b2123) | Nov 23, 2022 |
| ASUSTek       | K70IJ                       | Notebook    | [8df764e624](https://linux-hardware.org/?probe=8df764e624) | Nov 23, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [3be30a3d31](https://linux-hardware.org/?probe=3be30a3d31) | Nov 23, 2022 |
| Wistron       | ProLiant ML110 G5           | Desktop     | [67cc68fbfe](https://linux-hardware.org/?probe=67cc68fbfe) | Nov 23, 2022 |
| HP            | 8582 01100                  | All in one  | [4977f9d91d](https://linux-hardware.org/?probe=4977f9d91d) | Nov 23, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [e4904d14cc](https://linux-hardware.org/?probe=e4904d14cc) | Nov 23, 2022 |
| Sony          | VPCEG16EG                   | Notebook    | [ee22559858](https://linux-hardware.org/?probe=ee22559858) | Nov 23, 2022 |
| Dell          | 0M863N A01                  | Desktop     | [ca7e5eab8d](https://linux-hardware.org/?probe=ca7e5eab8d) | Nov 23, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [681bcb945c](https://linux-hardware.org/?probe=681bcb945c) | Nov 23, 2022 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [eca478ef1d](https://linux-hardware.org/?probe=eca478ef1d) | Nov 23, 2022 |
| HP            | Notebook                    | Notebook    | [616c071073](https://linux-hardware.org/?probe=616c071073) | Nov 23, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [063ffbb0e8](https://linux-hardware.org/?probe=063ffbb0e8) | Nov 23, 2022 |
| Lenovo        | IdeaPad U310 Touch          | Notebook    | [09beadc5ae](https://linux-hardware.org/?probe=09beadc5ae) | Nov 22, 2022 |
| Intel         | DG41TY AAE47335-302         | Desktop     | [ae2fb8d0b3](https://linux-hardware.org/?probe=ae2fb8d0b3) | Nov 22, 2022 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [324b5a49e4](https://linux-hardware.org/?probe=324b5a49e4) | Nov 22, 2022 |
| Intel         | powered classmate PC        | Notebook    | [d74f69f66a](https://linux-hardware.org/?probe=d74f69f66a) | Nov 22, 2022 |
| Lenovo        | ThinkPad R500 2716AZJ       | Notebook    | [ecf18761e4](https://linux-hardware.org/?probe=ecf18761e4) | Nov 22, 2022 |
| Dell          | Latitude 7390               | Notebook    | [8364d36618](https://linux-hardware.org/?probe=8364d36618) | Nov 22, 2022 |
| HP            | Notebook                    | Notebook    | [a062aaddcd](https://linux-hardware.org/?probe=a062aaddcd) | Nov 21, 2022 |
| ASUSTek       | V-P5G43 R1.04G              | Desktop     | [b400ca5e29](https://linux-hardware.org/?probe=b400ca5e29) | Nov 21, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [1c7b4c3780](https://linux-hardware.org/?probe=1c7b4c3780) | Nov 21, 2022 |
| Dell          | Latitude E6410              | Notebook    | [22585074f3](https://linux-hardware.org/?probe=22585074f3) | Nov 21, 2022 |
| HP            | 3399                        | Desktop     | [bce6df1ffb](https://linux-hardware.org/?probe=bce6df1ffb) | Nov 21, 2022 |
| Gigabyte      | Z77-D3H                     | Desktop     | [aecddcf17e](https://linux-hardware.org/?probe=aecddcf17e) | Nov 21, 2022 |
| ASUSTek       | F1A55-M LE                  | Desktop     | [f2120128c1](https://linux-hardware.org/?probe=f2120128c1) | Nov 21, 2022 |
| Gigabyte      | H61M-DS2 x.x                | Desktop     | [cd65013120](https://linux-hardware.org/?probe=cd65013120) | Nov 21, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [4792cdbba2](https://linux-hardware.org/?probe=4792cdbba2) | Nov 21, 2022 |
| Lenovo        | 32E9 SDK0T76465 WIN 3422... | Desktop     | [ec30826806](https://linux-hardware.org/?probe=ec30826806) | Nov 21, 2022 |
| Lenovo        | MAHOBAY                     | Desktop     | [d74e4882d8](https://linux-hardware.org/?probe=d74e4882d8) | Nov 21, 2022 |
| Pegatron      | NARRA5                      | Desktop     | [d8632e2872](https://linux-hardware.org/?probe=d8632e2872) | Nov 21, 2022 |
| ASRock        | P67 Extreme4                | Desktop     | [569fd8178d](https://linux-hardware.org/?probe=569fd8178d) | Nov 21, 2022 |
| Pegatron      | NARRA5                      | Desktop     | [42e5fe9c22](https://linux-hardware.org/?probe=42e5fe9c22) | Nov 21, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [049f06f11d](https://linux-hardware.org/?probe=049f06f11d) | Nov 21, 2022 |
| AZW           | SEi                         | Desktop     | [a8e813c483](https://linux-hardware.org/?probe=a8e813c483) | Nov 21, 2022 |
| HP            | 2AF3                        | Desktop     | [babcb0bf93](https://linux-hardware.org/?probe=babcb0bf93) | Nov 21, 2022 |
| Dell          | 00NNT0 A00                  | Desktop     | [c25787d8b9](https://linux-hardware.org/?probe=c25787d8b9) | Nov 20, 2022 |
| ASUSTek       | M2N-E                       | Desktop     | [150565ed00](https://linux-hardware.org/?probe=150565ed00) | Nov 20, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [880e6565e8](https://linux-hardware.org/?probe=880e6565e8) | Nov 20, 2022 |
| Alienware     | M17xR3                      | Notebook    | [d472e55685](https://linux-hardware.org/?probe=d472e55685) | Nov 20, 2022 |
| Sony          | VPCEB2M1E                   | Notebook    | [eeefed51e4](https://linux-hardware.org/?probe=eeefed51e4) | Nov 20, 2022 |
| ASUSTek       | Z97-C                       | Desktop     | [733140c078](https://linux-hardware.org/?probe=733140c078) | Nov 20, 2022 |
| HP            | Compaq Presario CQ71        | Notebook    | [52c86bac3f](https://linux-hardware.org/?probe=52c86bac3f) | Nov 20, 2022 |
| Apple         | MacBookAir4,2               | Notebook    | [7d3f0e5604](https://linux-hardware.org/?probe=7d3f0e5604) | Nov 20, 2022 |
| MSI           | PRO Z690-A WIFI             | Desktop     | [5b31194732](https://linux-hardware.org/?probe=5b31194732) | Nov 20, 2022 |
| Chuwi         | LapBook SE                  | Notebook    | [ecc56a3703](https://linux-hardware.org/?probe=ecc56a3703) | Nov 19, 2022 |
| HP            | ProBook 4330s               | Notebook    | [5680f376db](https://linux-hardware.org/?probe=5680f376db) | Nov 19, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [45a5881e61](https://linux-hardware.org/?probe=45a5881e61) | Nov 19, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [61738f6d8a](https://linux-hardware.org/?probe=61738f6d8a) | Nov 19, 2022 |
| Shuttle       | FS61                        | Desktop     | [7a940c8fa3](https://linux-hardware.org/?probe=7a940c8fa3) | Nov 19, 2022 |
| Lenovo        | S145-15API 81UT             | Notebook    | [fd832d05e2](https://linux-hardware.org/?probe=fd832d05e2) | Nov 19, 2022 |
| HP            | Pavilion dv7                | Notebook    | [839266e415](https://linux-hardware.org/?probe=839266e415) | Nov 19, 2022 |
| HP            | Pavilion g7                 | Notebook    | [fae1d08109](https://linux-hardware.org/?probe=fae1d08109) | Nov 19, 2022 |
| Pegatron      | 2A94h                       | Desktop     | [be99475703](https://linux-hardware.org/?probe=be99475703) | Nov 19, 2022 |
| HP            | Pavilion dm4                | Notebook    | [d90ac7b5c2](https://linux-hardware.org/?probe=d90ac7b5c2) | Nov 19, 2022 |
| ECS           | G41T-M7                     | Desktop     | [f97036df33](https://linux-hardware.org/?probe=f97036df33) | Nov 18, 2022 |
| Intel         | X99                         | Desktop     | [c95c1d173b](https://linux-hardware.org/?probe=c95c1d173b) | Nov 18, 2022 |
| ASUSTek       | P8H61-M PLUS V2             | Desktop     | [ff279b1860](https://linux-hardware.org/?probe=ff279b1860) | Nov 18, 2022 |
| TPV-INVENT... | 2AC6 A01                    | Desktop     | [04b3ba4242](https://linux-hardware.org/?probe=04b3ba4242) | Nov 18, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [fc7b21bd04](https://linux-hardware.org/?probe=fc7b21bd04) | Nov 18, 2022 |
| Lenovo        | V15 G1 IML 82NB             | Notebook    | [a120cac88b](https://linux-hardware.org/?probe=a120cac88b) | Nov 18, 2022 |
| ASUSTek       | K53SM                       | Notebook    | [ea2f588ed8](https://linux-hardware.org/?probe=ea2f588ed8) | Nov 18, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [a61b66e4ed](https://linux-hardware.org/?probe=a61b66e4ed) | Nov 18, 2022 |
| Gigabyte      | A520M H                     | Desktop     | [c2ad29d3e8](https://linux-hardware.org/?probe=c2ad29d3e8) | Nov 18, 2022 |
| HP            | Notebook                    | Notebook    | [ded915d6cd](https://linux-hardware.org/?probe=ded915d6cd) | Nov 18, 2022 |
| Acer          | Aspire S24-880              | All in one  | [a255155f98](https://linux-hardware.org/?probe=a255155f98) | Nov 18, 2022 |
| Fujitsu Si... | D2364-A3 S26361-D2364-A3    | Desktop     | [62ce7f9a0b](https://linux-hardware.org/?probe=62ce7f9a0b) | Nov 18, 2022 |
| Huanan        | X99-8M-F V1.1               | Desktop     | [b1d1b0ad4c](https://linux-hardware.org/?probe=b1d1b0ad4c) | Nov 18, 2022 |
| HP            | Presario CQ43               | Notebook    | [0ed80872c0](https://linux-hardware.org/?probe=0ed80872c0) | Nov 18, 2022 |
| Acer          | Aspire one 1-431            | Notebook    | [c27978fdc4](https://linux-hardware.org/?probe=c27978fdc4) | Nov 18, 2022 |
| Acer          | Aspire 6930G                | Notebook    | [05ad62f97d](https://linux-hardware.org/?probe=05ad62f97d) | Nov 17, 2022 |
| Packard Be... | EasyNote TK81               | Notebook    | [c396423368](https://linux-hardware.org/?probe=c396423368) | Nov 17, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [dd25be7aef](https://linux-hardware.org/?probe=dd25be7aef) | Nov 17, 2022 |
| ASUSTek       | K54HR                       | Notebook    | [ba95174feb](https://linux-hardware.org/?probe=ba95174feb) | Nov 17, 2022 |
| Compaq        | 420                         | Notebook    | [07ab1c2b0f](https://linux-hardware.org/?probe=07ab1c2b0f) | Nov 17, 2022 |
| Dell          | Inspiron 13-5368            | Notebook    | [203df386a1](https://linux-hardware.org/?probe=203df386a1) | Nov 17, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [105a376344](https://linux-hardware.org/?probe=105a376344) | Nov 17, 2022 |
| Toshiba       | dynabook T653/46JR          | Notebook    | [09569f3154](https://linux-hardware.org/?probe=09569f3154) | Nov 17, 2022 |
| Dell          | 0FDT3J A03                  | Server      | [438f28559c](https://linux-hardware.org/?probe=438f28559c) | Nov 16, 2022 |
| ASUSTek       | P5KPL/1600                  | Desktop     | [24b13d1967](https://linux-hardware.org/?probe=24b13d1967) | Nov 16, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [15087fec90](https://linux-hardware.org/?probe=15087fec90) | Nov 16, 2022 |
| ASUSTek       | N53Jf                       | Notebook    | [61f5cf6214](https://linux-hardware.org/?probe=61f5cf6214) | Nov 16, 2022 |
| Acer          | Aspire 5720Z                | Notebook    | [930beb6857](https://linux-hardware.org/?probe=930beb6857) | Nov 16, 2022 |
| HP            | 843B                        | Desktop     | [373e5cc61d](https://linux-hardware.org/?probe=373e5cc61d) | Nov 16, 2022 |
| Intel         | H61                         | Desktop     | [faeac27433](https://linux-hardware.org/?probe=faeac27433) | Nov 16, 2022 |
| Medion        | MS-7728                     | Desktop     | [813d86814d](https://linux-hardware.org/?probe=813d86814d) | Nov 16, 2022 |
| MSI           | CR620                       | Notebook    | [4d90de18ca](https://linux-hardware.org/?probe=4d90de18ca) | Nov 16, 2022 |
| Acer          | Veriton N4630G              | Desktop     | [f4566a57a9](https://linux-hardware.org/?probe=f4566a57a9) | Nov 16, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [9c25ade74d](https://linux-hardware.org/?probe=9c25ade74d) | Nov 16, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [90662fa2e9](https://linux-hardware.org/?probe=90662fa2e9) | Nov 16, 2022 |
| Toshiba       | Satellite Pro U500          | Notebook    | [064a36a5bb](https://linux-hardware.org/?probe=064a36a5bb) | Nov 16, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [6f3ecf327d](https://linux-hardware.org/?probe=6f3ecf327d) | Nov 16, 2022 |
| ALDO          | C2016-BSWI-D2               | Desktop     | [0e4c4c6806](https://linux-hardware.org/?probe=0e4c4c6806) | Nov 16, 2022 |
| Fujitsu       | LIFEBOOK E554               | Notebook    | [df8344d098](https://linux-hardware.org/?probe=df8344d098) | Nov 16, 2022 |
| AZW           | Gemini M                    | Desktop     | [683123c4f5](https://linux-hardware.org/?probe=683123c4f5) | Nov 16, 2022 |
| HP            | EliteBook Folio 1040 G2     | Notebook    | [3f95d3f191](https://linux-hardware.org/?probe=3f95d3f191) | Nov 15, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [b139741f4f](https://linux-hardware.org/?probe=b139741f4f) | Nov 15, 2022 |
| LDLC          | SPC-N                       | Notebook    | [acec489419](https://linux-hardware.org/?probe=acec489419) | Nov 15, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [ff63827781](https://linux-hardware.org/?probe=ff63827781) | Nov 15, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [e7f05e6eac](https://linux-hardware.org/?probe=e7f05e6eac) | Nov 15, 2022 |
| Lenovo        | ThinkPad T490s 20NYS02B0... | Notebook    | [7d2cffcf6a](https://linux-hardware.org/?probe=7d2cffcf6a) | Nov 15, 2022 |
| Dell          | 0UR033 A00                  | Server      | [2ff8924b15](https://linux-hardware.org/?probe=2ff8924b15) | Nov 15, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [6cb0948dfd](https://linux-hardware.org/?probe=6cb0948dfd) | Nov 15, 2022 |
| Toshiba       | dynabook T653/46JR          | Notebook    | [69d4f912f9](https://linux-hardware.org/?probe=69d4f912f9) | Nov 15, 2022 |
| MSI           | H61M-P31/W8                 | Desktop     | [a7d3a01ab2](https://linux-hardware.org/?probe=a7d3a01ab2) | Nov 15, 2022 |
| ASUSTek       | N751JX                      | Notebook    | [cea52af467](https://linux-hardware.org/?probe=cea52af467) | Nov 14, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [298f1bd357](https://linux-hardware.org/?probe=298f1bd357) | Nov 14, 2022 |
| Dell          | XPS 9315                    | Notebook    | [9f97a6b66c](https://linux-hardware.org/?probe=9f97a6b66c) | Nov 14, 2022 |
| HP            | 22F8                        | Desktop     | [754ebee9c8](https://linux-hardware.org/?probe=754ebee9c8) | Nov 14, 2022 |
| Gigabyte      | H77-DS3H                    | Desktop     | [f28540c049](https://linux-hardware.org/?probe=f28540c049) | Nov 14, 2022 |
| Lenovo        | G550 20023                  | Notebook    | [80be7e8e25](https://linux-hardware.org/?probe=80be7e8e25) | Nov 14, 2022 |
| Lenovo        | ThinkPad T470p 20J6CTO1W... | Notebook    | [4121297e16](https://linux-hardware.org/?probe=4121297e16) | Nov 14, 2022 |
| Packard Be... | DOT S                       | Notebook    | [4e6d343f5c](https://linux-hardware.org/?probe=4e6d343f5c) | Nov 14, 2022 |
| Sony          | SVE1411EGXB                 | Notebook    | [dafea482eb](https://linux-hardware.org/?probe=dafea482eb) | Nov 14, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [2d904e2be7](https://linux-hardware.org/?probe=2d904e2be7) | Nov 13, 2022 |
| ASUSTek       | N50Vc                       | Notebook    | [36b3155007](https://linux-hardware.org/?probe=36b3155007) | Nov 13, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [9506350a75](https://linux-hardware.org/?probe=9506350a75) | Nov 13, 2022 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [27d4e1c496](https://linux-hardware.org/?probe=27d4e1c496) | Nov 13, 2022 |
| Lenovo        | 0x36C4 SDK0K17763 WIN 18... | All in one  | [7a3f735fc0](https://linux-hardware.org/?probe=7a3f735fc0) | Nov 13, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [9ef06fcef1](https://linux-hardware.org/?probe=9ef06fcef1) | Nov 13, 2022 |
| HP            | 84FD                        | Desktop     | [6ee4b6828c](https://linux-hardware.org/?probe=6ee4b6828c) | Nov 13, 2022 |
| Deltron       | H81H3-M4                    | Desktop     | [49530f2e0b](https://linux-hardware.org/?probe=49530f2e0b) | Nov 13, 2022 |
| MSI           | H97 GUARD-PRO               | Desktop     | [3ea9d7a74a](https://linux-hardware.org/?probe=3ea9d7a74a) | Nov 13, 2022 |
| Gigabyte      | H87-HD3                     | Desktop     | [e5a8d4700d](https://linux-hardware.org/?probe=e5a8d4700d) | Nov 12, 2022 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [c5952a73e7](https://linux-hardware.org/?probe=c5952a73e7) | Nov 12, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [052f42f29a](https://linux-hardware.org/?probe=052f42f29a) | Nov 12, 2022 |
| Fujitsu       | LIFEBOOK E782               | Notebook    | [f6b2530682](https://linux-hardware.org/?probe=f6b2530682) | Nov 12, 2022 |
| HP            | ProBook 455 G2              | Notebook    | [1a5d0a1618](https://linux-hardware.org/?probe=1a5d0a1618) | Nov 12, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [2677116eee](https://linux-hardware.org/?probe=2677116eee) | Nov 12, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [e974c2ceff](https://linux-hardware.org/?probe=e974c2ceff) | Nov 12, 2022 |
| Dell          | Vostro 3300                 | Notebook    | [be3a3b081d](https://linux-hardware.org/?probe=be3a3b081d) | Nov 12, 2022 |
| Acer          | Aspire 7741                 | Notebook    | [d5166a002a](https://linux-hardware.org/?probe=d5166a002a) | Nov 11, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [d710968897](https://linux-hardware.org/?probe=d710968897) | Nov 11, 2022 |
| Toshiba       | Satellite C870-D7K          | Notebook    | [b2f60a1b4d](https://linux-hardware.org/?probe=b2f60a1b4d) | Nov 11, 2022 |
| Lenovo        | 36DC SDK0J40709 WIN 3259... | All in one  | [929685d936](https://linux-hardware.org/?probe=929685d936) | Nov 11, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [fa27762189](https://linux-hardware.org/?probe=fa27762189) | Nov 11, 2022 |
| ASUSTek       | P5K SE/EPU                  | Desktop     | [d5e58b3718](https://linux-hardware.org/?probe=d5e58b3718) | Nov 11, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [ccd759a684](https://linux-hardware.org/?probe=ccd759a684) | Nov 11, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [19dc931962](https://linux-hardware.org/?probe=19dc931962) | Nov 10, 2022 |
| MSI           | U270DX                      | Notebook    | [2a68a6ba02](https://linux-hardware.org/?probe=2a68a6ba02) | Nov 10, 2022 |
| HP            | Pavilion 15                 | Notebook    | [d703e1c63c](https://linux-hardware.org/?probe=d703e1c63c) | Nov 10, 2022 |
| ASRock        | B365M Pro4-F                | Desktop     | [aa006ea111](https://linux-hardware.org/?probe=aa006ea111) | Nov 10, 2022 |
| Dell          | 04YP6J A02                  | Desktop     | [6a3833051e](https://linux-hardware.org/?probe=6a3833051e) | Nov 10, 2022 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [70d68c6ca1](https://linux-hardware.org/?probe=70d68c6ca1) | Nov 10, 2022 |
| Gigabyte      | H61M-DS2 x.x                | Desktop     | [4488e0a71a](https://linux-hardware.org/?probe=4488e0a71a) | Nov 10, 2022 |
| Toshiba       | dynabook T653/46JR          | Notebook    | [dfa4a8aa7f](https://linux-hardware.org/?probe=dfa4a8aa7f) | Nov 10, 2022 |
| Acer          | Nitro AN515-43              | Notebook    | [0e624570e1](https://linux-hardware.org/?probe=0e624570e1) | Nov 10, 2022 |
| Dell          | Inspiron N7010              | Notebook    | [8d43f2e3fc](https://linux-hardware.org/?probe=8d43f2e3fc) | Nov 10, 2022 |
| Lenovo        | Yoga 510-14ISK 80S7         | Convertible | [5a5633f611](https://linux-hardware.org/?probe=5a5633f611) | Nov 09, 2022 |
| Acer          | RS880M05                    | Desktop     | [cb216f090c](https://linux-hardware.org/?probe=cb216f090c) | Nov 09, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [673c961915](https://linux-hardware.org/?probe=673c961915) | Nov 09, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [8383f208a6](https://linux-hardware.org/?probe=8383f208a6) | Nov 09, 2022 |
| Fujitsu       | FMVXN4MN2Z                  | Notebook    | [7a08a94b1e](https://linux-hardware.org/?probe=7a08a94b1e) | Nov 09, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [fb87099a0d](https://linux-hardware.org/?probe=fb87099a0d) | Nov 09, 2022 |
| Dell          | 0V52N7 A02                  | Server      | [3151a21ebf](https://linux-hardware.org/?probe=3151a21ebf) | Nov 09, 2022 |
| Unknown       | Unknown                     | Notebook    | [c46b9195f3](https://linux-hardware.org/?probe=c46b9195f3) | Nov 09, 2022 |
| Gigabyte      | GA-MA78GM-S2H               | Desktop     | [ac916f47fc](https://linux-hardware.org/?probe=ac916f47fc) | Nov 08, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [08be836975](https://linux-hardware.org/?probe=08be836975) | Nov 08, 2022 |
| ASUSTek       | P5E-VM SE                   | Desktop     | [a41a51330d](https://linux-hardware.org/?probe=a41a51330d) | Nov 08, 2022 |
| HP            | Pavilion dv2700             | Notebook    | [a8e36a1579](https://linux-hardware.org/?probe=a8e36a1579) | Nov 08, 2022 |
| Acer          | Aspire X1700                | Desktop     | [764516b8f0](https://linux-hardware.org/?probe=764516b8f0) | Nov 08, 2022 |
| Dell          | 0VD92X A00                  | Desktop     | [a22087073b](https://linux-hardware.org/?probe=a22087073b) | Nov 08, 2022 |
| Acer          | Aspire 7741                 | Notebook    | [9fda4c3798](https://linux-hardware.org/?probe=9fda4c3798) | Nov 08, 2022 |
| Gigabyte      | EP45-UD3L                   | Desktop     | [2b3eb32895](https://linux-hardware.org/?probe=2b3eb32895) | Nov 07, 2022 |
| Gigabyte      | G41MT-S2                    | Desktop     | [4c91fc2a59](https://linux-hardware.org/?probe=4c91fc2a59) | Nov 07, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [6921f657bf](https://linux-hardware.org/?probe=6921f657bf) | Nov 07, 2022 |
| Dell          | Latitude E6400              | Notebook    | [22ccbac81a](https://linux-hardware.org/?probe=22ccbac81a) | Nov 07, 2022 |
| HP            | Notebook                    | Notebook    | [0164126ac9](https://linux-hardware.org/?probe=0164126ac9) | Nov 07, 2022 |
| ASRock        | Z170 Extreme4               | Desktop     | [f0b56da15d](https://linux-hardware.org/?probe=f0b56da15d) | Nov 07, 2022 |
| HP            | ProBook 4530s               | Notebook    | [afb0629ea9](https://linux-hardware.org/?probe=afb0629ea9) | Nov 07, 2022 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [b6768dd5b7](https://linux-hardware.org/?probe=b6768dd5b7) | Nov 07, 2022 |
| Acer          | TravelMate 5760             | Notebook    | [f645b36a78](https://linux-hardware.org/?probe=f645b36a78) | Nov 07, 2022 |
| ASUSTek       | K53E                        | Notebook    | [07d6d01b99](https://linux-hardware.org/?probe=07d6d01b99) | Nov 06, 2022 |
| HP            | Notebook                    | Notebook    | [59b70f4c7c](https://linux-hardware.org/?probe=59b70f4c7c) | Nov 06, 2022 |
| Dell          | Latitude E7470              | Notebook    | [1bd39e96d2](https://linux-hardware.org/?probe=1bd39e96d2) | Nov 06, 2022 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [09c5b6e39e](https://linux-hardware.org/?probe=09c5b6e39e) | Nov 06, 2022 |
| Gigabyte      | H81M-DS2                    | Desktop     | [5deb773641](https://linux-hardware.org/?probe=5deb773641) | Nov 06, 2022 |
| HP            | Pavilion dv6                | Notebook    | [f13b221630](https://linux-hardware.org/?probe=f13b221630) | Nov 06, 2022 |
| Pegatron      | 2AE3                        | Desktop     | [19ae75aacc](https://linux-hardware.org/?probe=19ae75aacc) | Nov 06, 2022 |
| Lenovo        | G485 20136                  | Notebook    | [f8ee5082f8](https://linux-hardware.org/?probe=f8ee5082f8) | Nov 06, 2022 |
| HP            | 245 G5 Notebook PC          | Notebook    | [4d52b15940](https://linux-hardware.org/?probe=4d52b15940) | Nov 06, 2022 |
| ASRock        | 4CoreDual-SATA2             | Desktop     | [e1a81edea7](https://linux-hardware.org/?probe=e1a81edea7) | Nov 05, 2022 |
| MSI           | GF615M-P33                  | Desktop     | [8aec7634ab](https://linux-hardware.org/?probe=8aec7634ab) | Nov 05, 2022 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [578079d456](https://linux-hardware.org/?probe=578079d456) | Nov 05, 2022 |
| Gigabyte      | GA-MA770-DS3                | Desktop     | [f435ef302a](https://linux-hardware.org/?probe=f435ef302a) | Nov 05, 2022 |
| Acer          | TravelMate P259-G2-M        | Notebook    | [4a85f586b3](https://linux-hardware.org/?probe=4a85f586b3) | Nov 05, 2022 |
| Acer          | TravelMate B118-M           | Notebook    | [8b7e60aef0](https://linux-hardware.org/?probe=8b7e60aef0) | Nov 05, 2022 |
| Acer          | Aspire A717-71G             | Notebook    | [a6fa794196](https://linux-hardware.org/?probe=a6fa794196) | Nov 05, 2022 |
| ASUSTek       | K56CM                       | Notebook    | [c93289dc28](https://linux-hardware.org/?probe=c93289dc28) | Nov 05, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [e2cadc512e](https://linux-hardware.org/?probe=e2cadc512e) | Nov 05, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [5ffd5ed23d](https://linux-hardware.org/?probe=5ffd5ed23d) | Nov 05, 2022 |
| HP            | 2820h                       | Desktop     | [6378a2e9c3](https://linux-hardware.org/?probe=6378a2e9c3) | Nov 05, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [7db5fcb7b0](https://linux-hardware.org/?probe=7db5fcb7b0) | Nov 05, 2022 |
| Dell          | 09D2HH A00                  | Desktop     | [7a4477cf7b](https://linux-hardware.org/?probe=7a4477cf7b) | Nov 05, 2022 |
| Toshiba       | Satellite C75D-B            | Notebook    | [c125fc089c](https://linux-hardware.org/?probe=c125fc089c) | Nov 05, 2022 |
| VS Company    | MCP61M                      | Desktop     | [ef6adc510d](https://linux-hardware.org/?probe=ef6adc510d) | Nov 05, 2022 |
| HP            | ProBook 440 G7              | Notebook    | [7a183bdeb7](https://linux-hardware.org/?probe=7a183bdeb7) | Nov 05, 2022 |
| Lenovo        | ThinkPad L520 78596CG       | Notebook    | [094f09bcf8](https://linux-hardware.org/?probe=094f09bcf8) | Nov 04, 2022 |
| HP            | Compaq Presario A900        | Notebook    | [4c48500597](https://linux-hardware.org/?probe=4c48500597) | Nov 04, 2022 |
| Toshiba       | Satellite Pro A200          | Notebook    | [09ae3b0b13](https://linux-hardware.org/?probe=09ae3b0b13) | Nov 04, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [3f2ef35b32](https://linux-hardware.org/?probe=3f2ef35b32) | Nov 04, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [75884710cd](https://linux-hardware.org/?probe=75884710cd) | Nov 04, 2022 |
| Lenovo        | ThinkPad L480 20LS001AMC    | Notebook    | [010fd86c32](https://linux-hardware.org/?probe=010fd86c32) | Nov 04, 2022 |
| Medion        | E6246 MD63200               | Notebook    | [211d565292](https://linux-hardware.org/?probe=211d565292) | Nov 04, 2022 |
| Lenovo        | B50-45 80F0                 | Notebook    | [2d36803ec6](https://linux-hardware.org/?probe=2d36803ec6) | Nov 04, 2022 |
| MSI           | Z97-G43                     | Desktop     | [85701968ed](https://linux-hardware.org/?probe=85701968ed) | Nov 04, 2022 |
| ASUSTek       | H170I-PLUS D3               | Desktop     | [74df37995c](https://linux-hardware.org/?probe=74df37995c) | Nov 04, 2022 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [afeb473322](https://linux-hardware.org/?probe=afeb473322) | Nov 04, 2022 |
| Sony          | VPCYB1S1E                   | Notebook    | [54d0a26de9](https://linux-hardware.org/?probe=54d0a26de9) | Nov 03, 2022 |
| ASUSTek       | K50IN                       | Notebook    | [8c069a1707](https://linux-hardware.org/?probe=8c069a1707) | Nov 03, 2022 |
| Notebook      | NJ50_70CU                   | Notebook    | [0427d9b80c](https://linux-hardware.org/?probe=0427d9b80c) | Nov 03, 2022 |
| Packard Be... | EasyNote MZ45               | Notebook    | [93dada1577](https://linux-hardware.org/?probe=93dada1577) | Nov 03, 2022 |
| Lenovo        | ThinkPad R500 2714AAG       | Notebook    | [456f21be22](https://linux-hardware.org/?probe=456f21be22) | Nov 03, 2022 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [1d618807a7](https://linux-hardware.org/?probe=1d618807a7) | Nov 03, 2022 |
| Fujitsu Si... | AMILO Li3710                | Notebook    | [ce4f615c70](https://linux-hardware.org/?probe=ce4f615c70) | Nov 03, 2022 |
| Acer          | Veriton M480                | Desktop     | [9aa34be941](https://linux-hardware.org/?probe=9aa34be941) | Nov 03, 2022 |
| ASUSTek       | PRIME B365M-K               | Desktop     | [e2e281d38d](https://linux-hardware.org/?probe=e2e281d38d) | Nov 03, 2022 |
| Fujitsu       | D3219-A1 S26361-D3219-A1    | Desktop     | [bdc77dbc53](https://linux-hardware.org/?probe=bdc77dbc53) | Nov 03, 2022 |
| Samsung       | 400B2B/400B2B               | Notebook    | [a909b4b203](https://linux-hardware.org/?probe=a909b4b203) | Nov 03, 2022 |
| Lenovo        | 3716                        | Desktop     | [5a04bbf315](https://linux-hardware.org/?probe=5a04bbf315) | Nov 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [f9f727f7e5](https://linux-hardware.org/?probe=f9f727f7e5) | Nov 02, 2022 |
| HP            | ENVY m6                     | Notebook    | [9043724da5](https://linux-hardware.org/?probe=9043724da5) | Nov 02, 2022 |
| ASUSTek       | ASUS BR1100FKA BR1100FKA... | Convertible | [83a1fc191a](https://linux-hardware.org/?probe=83a1fc191a) | Nov 02, 2022 |
| Lenovo        | IdeaPad 710S-13IKB 80VQ     | Notebook    | [dbacfbd3b0](https://linux-hardware.org/?probe=dbacfbd3b0) | Nov 02, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [0a79270558](https://linux-hardware.org/?probe=0a79270558) | Nov 02, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [a9f10f8922](https://linux-hardware.org/?probe=a9f10f8922) | Nov 02, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [3773260366](https://linux-hardware.org/?probe=3773260366) | Nov 02, 2022 |
| Gigabyte      | H97-HD3                     | Desktop     | [22214c7851](https://linux-hardware.org/?probe=22214c7851) | Nov 02, 2022 |
| Panasonic     | CF-C1BWFBZ1M                | Notebook    | [18a81d5db2](https://linux-hardware.org/?probe=18a81d5db2) | Nov 02, 2022 |
| ASRock        | N68-S3 FX                   | Desktop     | [22f68458d4](https://linux-hardware.org/?probe=22f68458d4) | Nov 02, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [44f768478e](https://linux-hardware.org/?probe=44f768478e) | Nov 02, 2022 |
| Acer          | Aspire X1430                | Desktop     | [f48a8d45d8](https://linux-hardware.org/?probe=f48a8d45d8) | Nov 01, 2022 |
| VS Company    | G31T-M                      | Desktop     | [75eb6866e0](https://linux-hardware.org/?probe=75eb6866e0) | Nov 01, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [44c6e56cd9](https://linux-hardware.org/?probe=44c6e56cd9) | Nov 01, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [06ea8207dc](https://linux-hardware.org/?probe=06ea8207dc) | Nov 01, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [0470f02ccb](https://linux-hardware.org/?probe=0470f02ccb) | Nov 01, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [a85aef0a90](https://linux-hardware.org/?probe=a85aef0a90) | Oct 31, 2022 |
| ASUSTek       | S551LN                      | Notebook    | [67e15a659d](https://linux-hardware.org/?probe=67e15a659d) | Oct 31, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [8b208b8383](https://linux-hardware.org/?probe=8b208b8383) | Oct 31, 2022 |
| Acer          | Extensa 5635Z               | Notebook    | [35ce596e08](https://linux-hardware.org/?probe=35ce596e08) | Oct 31, 2022 |
| ASUSTek       | M4A78 PLUS                  | Desktop     | [bac044cd22](https://linux-hardware.org/?probe=bac044cd22) | Oct 31, 2022 |
| Dell          | Latitude E5500              | Notebook    | [c64399793c](https://linux-hardware.org/?probe=c64399793c) | Oct 31, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [c23efa8caa](https://linux-hardware.org/?probe=c23efa8caa) | Oct 31, 2022 |
| Dell          | Latitude E6400              | Notebook    | [8f2639b285](https://linux-hardware.org/?probe=8f2639b285) | Oct 31, 2022 |
| Dell          | 0GXM1W A00                  | Desktop     | [598d815c17](https://linux-hardware.org/?probe=598d815c17) | Oct 31, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [acfa0d90d6](https://linux-hardware.org/?probe=acfa0d90d6) | Oct 31, 2022 |
| Pegatron      | IPPCR-SS                    | Desktop     | [9427da0212](https://linux-hardware.org/?probe=9427da0212) | Oct 31, 2022 |
| HP            | G72                         | Notebook    | [08a732911d](https://linux-hardware.org/?probe=08a732911d) | Oct 31, 2022 |
| Intel         | powered classmate PC        | Notebook    | [5555da7553](https://linux-hardware.org/?probe=5555da7553) | Oct 31, 2022 |
| Gigabyte      | H410M S2H V3                | Desktop     | [202065a62d](https://linux-hardware.org/?probe=202065a62d) | Oct 30, 2022 |
| HP            | 18E7                        | Desktop     | [6393aa1211](https://linux-hardware.org/?probe=6393aa1211) | Oct 30, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [dca18dced0](https://linux-hardware.org/?probe=dca18dced0) | Oct 30, 2022 |
| Lenovo        | ThinkPad L560 20F2S0DA00    | Notebook    | [bf8945db85](https://linux-hardware.org/?probe=bf8945db85) | Oct 30, 2022 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [5f7d9d2a04](https://linux-hardware.org/?probe=5f7d9d2a04) | Oct 30, 2022 |
| Prestigio     | PSB133S01ZFP                | Notebook    | [e10becbd35](https://linux-hardware.org/?probe=e10becbd35) | Oct 30, 2022 |
| Dell          | Latitude E7240              | Notebook    | [7605a5bf1c](https://linux-hardware.org/?probe=7605a5bf1c) | Oct 30, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [12b6232cdd](https://linux-hardware.org/?probe=12b6232cdd) | Oct 30, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [b7760774ca](https://linux-hardware.org/?probe=b7760774ca) | Oct 30, 2022 |
| ASUSTek       | X556UQK                     | Notebook    | [f8bdcbce4e](https://linux-hardware.org/?probe=f8bdcbce4e) | Oct 29, 2022 |
| Gigabyte      | Z690 AORUS MASTER           | Desktop     | [2a7d6b757b](https://linux-hardware.org/?probe=2a7d6b757b) | Oct 29, 2022 |
| Dell          | Studio 1737                 | Notebook    | [97f398804e](https://linux-hardware.org/?probe=97f398804e) | Oct 29, 2022 |
| HP            | Compaq 615                  | Notebook    | [ae90fa3742](https://linux-hardware.org/?probe=ae90fa3742) | Oct 29, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [6e9cb9c0e0](https://linux-hardware.org/?probe=6e9cb9c0e0) | Oct 29, 2022 |
| ASUSTek       | ROG Maximus XII HERO        | Desktop     | [048348c6ba](https://linux-hardware.org/?probe=048348c6ba) | Oct 29, 2022 |
| MSI           | P45 Platinum                | Desktop     | [5507d45c35](https://linux-hardware.org/?probe=5507d45c35) | Oct 29, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [ffb4369f83](https://linux-hardware.org/?probe=ffb4369f83) | Oct 29, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [fc7ef1ce9a](https://linux-hardware.org/?probe=fc7ef1ce9a) | Oct 29, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [1d3ff229c6](https://linux-hardware.org/?probe=1d3ff229c6) | Oct 29, 2022 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [345683b134](https://linux-hardware.org/?probe=345683b134) | Oct 29, 2022 |
| HP            | ProBook 6570b               | Notebook    | [b5d48f6adb](https://linux-hardware.org/?probe=b5d48f6adb) | Oct 29, 2022 |
| ASRock        | H81M-ITX                    | Desktop     | [56f93814ea](https://linux-hardware.org/?probe=56f93814ea) | Oct 28, 2022 |
| Samsung       | 670Z5E                      | Notebook    | [159f89858c](https://linux-hardware.org/?probe=159f89858c) | Oct 28, 2022 |
| Acer          | Aspire 5745                 | Notebook    | [2f79de6974](https://linux-hardware.org/?probe=2f79de6974) | Oct 28, 2022 |
| ASUSTek       | P5K                         | Desktop     | [6d87562df6](https://linux-hardware.org/?probe=6d87562df6) | Oct 28, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [2ca56cb740](https://linux-hardware.org/?probe=2ca56cb740) | Oct 28, 2022 |
| ASUSTek       | M5A87                       | Desktop     | [88e6b582c9](https://linux-hardware.org/?probe=88e6b582c9) | Oct 28, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [6b57390808](https://linux-hardware.org/?probe=6b57390808) | Oct 28, 2022 |
| Lenovo        | B560                        | Notebook    | [73a6da1bdc](https://linux-hardware.org/?probe=73a6da1bdc) | Oct 28, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [41e9e7aba7](https://linux-hardware.org/?probe=41e9e7aba7) | Oct 28, 2022 |
| HP            | Pavilion Laptop 15-cc0xx    | Notebook    | [0ca2ea7180](https://linux-hardware.org/?probe=0ca2ea7180) | Oct 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [8d93ee0286](https://linux-hardware.org/?probe=8d93ee0286) | Oct 28, 2022 |
| Intel         | DG965OT AAD63733-203        | Desktop     | [28ad26edff](https://linux-hardware.org/?probe=28ad26edff) | Oct 28, 2022 |
| MSI           | MPG Z390I GAMING EDGE AC    | Desktop     | [1627ad94ef](https://linux-hardware.org/?probe=1627ad94ef) | Oct 27, 2022 |
| ASUSTek       | P8B75-V                     | Desktop     | [ca5c26654a](https://linux-hardware.org/?probe=ca5c26654a) | Oct 27, 2022 |
| ASRock        | B550M-HDV                   | Desktop     | [4d5068a3be](https://linux-hardware.org/?probe=4d5068a3be) | Oct 27, 2022 |
| ASUSTek       | P8H61-M LE R2.0             | Desktop     | [6b01f2f498](https://linux-hardware.org/?probe=6b01f2f498) | Oct 27, 2022 |
| ASUSTek       | UX303LAB                    | Notebook    | [5748274da1](https://linux-hardware.org/?probe=5748274da1) | Oct 27, 2022 |
| Acer          | Aspire 8730                 | Notebook    | [86bffd9523](https://linux-hardware.org/?probe=86bffd9523) | Oct 27, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [22dedf6886](https://linux-hardware.org/?probe=22dedf6886) | Oct 27, 2022 |
| Chuwi         | CoreBox                     | Mini pc     | [033d6281bd](https://linux-hardware.org/?probe=033d6281bd) | Oct 27, 2022 |
| Acer          | Aspire E3-112               | Notebook    | [fd34f66305](https://linux-hardware.org/?probe=fd34f66305) | Oct 26, 2022 |
| Acer          | Veriton M275                | Desktop     | [c4604d6f2a](https://linux-hardware.org/?probe=c4604d6f2a) | Oct 26, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [d8343e2db5](https://linux-hardware.org/?probe=d8343e2db5) | Oct 26, 2022 |
| Toshiba       | Satellite L45-B             | Notebook    | [e2f30e0f1e](https://linux-hardware.org/?probe=e2f30e0f1e) | Oct 26, 2022 |
| Dell          | Precision 7560              | Notebook    | [c82d6a32a5](https://linux-hardware.org/?probe=c82d6a32a5) | Oct 26, 2022 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [b50585b578](https://linux-hardware.org/?probe=b50585b578) | Oct 26, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [2dd0f7f115](https://linux-hardware.org/?probe=2dd0f7f115) | Oct 26, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [fa0daeab26](https://linux-hardware.org/?probe=fa0daeab26) | Oct 26, 2022 |
| ASUSTek       | UX303LAB                    | Notebook    | [622aa11277](https://linux-hardware.org/?probe=622aa11277) | Oct 26, 2022 |
| ASUSTek       | X542URR                     | Notebook    | [fe6fb20830](https://linux-hardware.org/?probe=fe6fb20830) | Oct 25, 2022 |
| Acer          | Veriton NBU                 | Desktop     | [7be04cd3ed](https://linux-hardware.org/?probe=7be04cd3ed) | Oct 25, 2022 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [eca0e58bd8](https://linux-hardware.org/?probe=eca0e58bd8) | Oct 25, 2022 |
| HP            | 21B4 A01                    | Desktop     | [ec46b18fd5](https://linux-hardware.org/?probe=ec46b18fd5) | Oct 25, 2022 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [2fb43f4be2](https://linux-hardware.org/?probe=2fb43f4be2) | Oct 25, 2022 |
| Acer          | Aspire ES1-571              | Notebook    | [f9f7926da2](https://linux-hardware.org/?probe=f9f7926da2) | Oct 25, 2022 |
| ASUSTek       | M3N78-VM                    | Desktop     | [1c68e176b6](https://linux-hardware.org/?probe=1c68e176b6) | Oct 25, 2022 |
| ASRock        | G41C-GS                     | Desktop     | [218d55e0ca](https://linux-hardware.org/?probe=218d55e0ca) | Oct 25, 2022 |
| ASUSTek       | P5Q3 DELUXE                 | Desktop     | [a25c84e8f1](https://linux-hardware.org/?probe=a25c84e8f1) | Oct 25, 2022 |
| ASRock        | B660M Pro RS                | Desktop     | [e3b389cb66](https://linux-hardware.org/?probe=e3b389cb66) | Oct 25, 2022 |
| Panasonic     | CFSX4-1                     | Notebook    | [2ddae6e0e1](https://linux-hardware.org/?probe=2ddae6e0e1) | Oct 25, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [ede3bcd3f3](https://linux-hardware.org/?probe=ede3bcd3f3) | Oct 24, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [bfa28dd791](https://linux-hardware.org/?probe=bfa28dd791) | Oct 24, 2022 |
| Lenovo        | B560                        | Notebook    | [82125c56a3](https://linux-hardware.org/?probe=82125c56a3) | Oct 24, 2022 |
| Dell          | 0GX297                      | Desktop     | [a047bbd7a0](https://linux-hardware.org/?probe=a047bbd7a0) | Oct 24, 2022 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [82afa0e5bc](https://linux-hardware.org/?probe=82afa0e5bc) | Oct 24, 2022 |
| Medion        | P8612                       | Notebook    | [a5c437d5f8](https://linux-hardware.org/?probe=a5c437d5f8) | Oct 24, 2022 |
| Dell          | Studio 1737                 | Notebook    | [d6e17c05b2](https://linux-hardware.org/?probe=d6e17c05b2) | Oct 24, 2022 |
| Lenovo        | G400s VILG1                 | Notebook    | [b7315785a1](https://linux-hardware.org/?probe=b7315785a1) | Oct 24, 2022 |
| ASUSTek       | A7U                         | Notebook    | [867f26dde1](https://linux-hardware.org/?probe=867f26dde1) | Oct 24, 2022 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [cce2975614](https://linux-hardware.org/?probe=cce2975614) | Oct 24, 2022 |
| ASUSTek       | P5QL-E                      | Desktop     | [41810c587a](https://linux-hardware.org/?probe=41810c587a) | Oct 24, 2022 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [a995e58f10](https://linux-hardware.org/?probe=a995e58f10) | Oct 24, 2022 |
| ASUSTek       | K53U                        | Notebook    | [d178c463df](https://linux-hardware.org/?probe=d178c463df) | Oct 24, 2022 |
| Dell          | 0200DY A02                  | Desktop     | [69327d2615](https://linux-hardware.org/?probe=69327d2615) | Oct 24, 2022 |
| HP            | 8767 A                      | Desktop     | [7ecf583dab](https://linux-hardware.org/?probe=7ecf583dab) | Oct 24, 2022 |
| Acer          | TravelMate B311-31          | Notebook    | [010dd1e876](https://linux-hardware.org/?probe=010dd1e876) | Oct 24, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [683ac39f80](https://linux-hardware.org/?probe=683ac39f80) | Oct 24, 2022 |
| Packard Be... | EasyNote ENTE70BH           | Notebook    | [2135a5aed7](https://linux-hardware.org/?probe=2135a5aed7) | Oct 23, 2022 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [5ff7cf2e42](https://linux-hardware.org/?probe=5ff7cf2e42) | Oct 23, 2022 |
| ASUSTek       | PB62                        | Desktop     | [ddec39293d](https://linux-hardware.org/?probe=ddec39293d) | Oct 23, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [e59cef718b](https://linux-hardware.org/?probe=e59cef718b) | Oct 23, 2022 |
| Acer          | WMCP78M                     | Desktop     | [f4e3945dea](https://linux-hardware.org/?probe=f4e3945dea) | Oct 23, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [5b61c1c241](https://linux-hardware.org/?probe=5b61c1c241) | Oct 23, 2022 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | Notebook    | [edfb470814](https://linux-hardware.org/?probe=edfb470814) | Oct 23, 2022 |
| Lenovo        | ThinkPad X240 20AMS01M00    | Notebook    | [2f1c7b7716](https://linux-hardware.org/?probe=2f1c7b7716) | Oct 23, 2022 |
| ASUSTek       | F2A85-V PRO                 | Desktop     | [ff4b30eab7](https://linux-hardware.org/?probe=ff4b30eab7) | Oct 23, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [3d217d0a43](https://linux-hardware.org/?probe=3d217d0a43) | Oct 23, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [12b83ecfd4](https://linux-hardware.org/?probe=12b83ecfd4) | Oct 22, 2022 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [d806b92948](https://linux-hardware.org/?probe=d806b92948) | Oct 22, 2022 |
| Dell          | 0HX555                      | Desktop     | [86339c4a3f](https://linux-hardware.org/?probe=86339c4a3f) | Oct 22, 2022 |
| Philco        | DTC-A55                     | Desktop     | [5c7d64ff3f](https://linux-hardware.org/?probe=5c7d64ff3f) | Oct 22, 2022 |
| Acer          | WG43M                       | Desktop     | [e520a7dfca](https://linux-hardware.org/?probe=e520a7dfca) | Oct 22, 2022 |
| Sony          | VPCEB1S1R                   | Notebook    | [1e64f5427a](https://linux-hardware.org/?probe=1e64f5427a) | Oct 21, 2022 |
| ASUSTek       | H110M-A                     | Desktop     | [7bd1ee25b3](https://linux-hardware.org/?probe=7bd1ee25b3) | Oct 21, 2022 |
| Gigabyte      | GA-790FXTA-UD5              | Desktop     | [78218a5b63](https://linux-hardware.org/?probe=78218a5b63) | Oct 21, 2022 |
| MSI           | H310M PRO-VD                | Desktop     | [9ce99513bc](https://linux-hardware.org/?probe=9ce99513bc) | Oct 21, 2022 |
| Lenovo        | ThinkPad R61 8935AC7        | Notebook    | [94d73589fc](https://linux-hardware.org/?probe=94d73589fc) | Oct 21, 2022 |
| Microboard    | Cantiga & ICH9M Chipset     | Notebook    | [1fffce3846](https://linux-hardware.org/?probe=1fffce3846) | Oct 21, 2022 |
| Dell          | Precision M6800             | Notebook    | [9b909039ee](https://linux-hardware.org/?probe=9b909039ee) | Oct 21, 2022 |
| ZOTAC         | ZBOX-QCM7T3000/EN072080S... | Mini pc     | [612f0f6e06](https://linux-hardware.org/?probe=612f0f6e06) | Oct 21, 2022 |
| MSI           | H61M-P20                    | Desktop     | [a50648c486](https://linux-hardware.org/?probe=a50648c486) | Oct 21, 2022 |
| Lenovo        | ThinkPad T520 42434WU       | Notebook    | [d118d39c58](https://linux-hardware.org/?probe=d118d39c58) | Oct 21, 2022 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [1ad0ed065f](https://linux-hardware.org/?probe=1ad0ed065f) | Oct 21, 2022 |
| MSI           | GT70 0NC/GT70 0NC           | Notebook    | [592b788d62](https://linux-hardware.org/?probe=592b788d62) | Oct 20, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [6c32002395](https://linux-hardware.org/?probe=6c32002395) | Oct 20, 2022 |
| ASUSTek       | P7P55-M                     | Desktop     | [3ff254b938](https://linux-hardware.org/?probe=3ff254b938) | Oct 20, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [7a1b569725](https://linux-hardware.org/?probe=7a1b569725) | Oct 20, 2022 |
| Dell          | Latitude E5410              | Notebook    | [f3b5d196ef](https://linux-hardware.org/?probe=f3b5d196ef) | Oct 20, 2022 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [2ead6c088f](https://linux-hardware.org/?probe=2ead6c088f) | Oct 20, 2022 |
| Gigabyte      | AERO 17 XD                  | Notebook    | [ca3dd06f6b](https://linux-hardware.org/?probe=ca3dd06f6b) | Oct 20, 2022 |
| Sony          | SVE1513B1EW                 | Notebook    | [77ef0b542b](https://linux-hardware.org/?probe=77ef0b542b) | Oct 20, 2022 |
| Dell          | 0V52N7 A01                  | Server      | [c3990d0066](https://linux-hardware.org/?probe=c3990d0066) | Oct 19, 2022 |
| Acer          | Aspire E5-574               | Notebook    | [d9797d9fa7](https://linux-hardware.org/?probe=d9797d9fa7) | Oct 19, 2022 |
| Dell          | Inspiron 13-7359            | Notebook    | [239627f1d1](https://linux-hardware.org/?probe=239627f1d1) | Oct 19, 2022 |
| HP            | 1825                        | Desktop     | [e0a35f1d0f](https://linux-hardware.org/?probe=e0a35f1d0f) | Oct 19, 2022 |
| Samsung       | 550XDA                      | Notebook    | [fcfceeaf04](https://linux-hardware.org/?probe=fcfceeaf04) | Oct 19, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [e14791bb51](https://linux-hardware.org/?probe=e14791bb51) | Oct 19, 2022 |
| ASRock        | H81M-HG4 R4.0               | Desktop     | [de13cd2a09](https://linux-hardware.org/?probe=de13cd2a09) | Oct 19, 2022 |
| HP            | ProBook 4330s               | Notebook    | [088c42cbc9](https://linux-hardware.org/?probe=088c42cbc9) | Oct 19, 2022 |
| HP            | 805D                        | Desktop     | [a70ef30fce](https://linux-hardware.org/?probe=a70ef30fce) | Oct 19, 2022 |
| MSI           | GE62 6QC                    | Notebook    | [92ac4fbaa6](https://linux-hardware.org/?probe=92ac4fbaa6) | Oct 19, 2022 |
| Intel         | DH61BF AAG81311-101         | Desktop     | [770d8bf876](https://linux-hardware.org/?probe=770d8bf876) | Oct 19, 2022 |
| ASUSTek       | A88XM-A                     | Desktop     | [9622704d8f](https://linux-hardware.org/?probe=9622704d8f) | Oct 18, 2022 |
| Acer          | Aspire 6930G                | Notebook    | [d65e0cfe7a](https://linux-hardware.org/?probe=d65e0cfe7a) | Oct 18, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [e4c3a71575](https://linux-hardware.org/?probe=e4c3a71575) | Oct 18, 2022 |
| ASUSTek       | P5KPL-E                     | Desktop     | [2f1e1cbbf4](https://linux-hardware.org/?probe=2f1e1cbbf4) | Oct 18, 2022 |
| Lenovo        | G480                        | Notebook    | [984691a38d](https://linux-hardware.org/?probe=984691a38d) | Oct 18, 2022 |
| ASUSTek       | TUF Gaming B460-PLUS        | Desktop     | [5823a0c5d0](https://linux-hardware.org/?probe=5823a0c5d0) | Oct 18, 2022 |
| HP            | Unknown                     | Notebook    | [4a0df43034](https://linux-hardware.org/?probe=4a0df43034) | Oct 17, 2022 |
| ASUSTek       | F9S                         | Notebook    | [c8df776935](https://linux-hardware.org/?probe=c8df776935) | Oct 17, 2022 |
| Teclast       | F7 Plus                     | Notebook    | [e77cad05c2](https://linux-hardware.org/?probe=e77cad05c2) | Oct 17, 2022 |
| Dell          | Latitude E6330              | Notebook    | [d4d6ca7ae9](https://linux-hardware.org/?probe=d4d6ca7ae9) | Oct 17, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [a1e9be5323](https://linux-hardware.org/?probe=a1e9be5323) | Oct 17, 2022 |
| HP            | Pavilion dv8                | Notebook    | [d290113849](https://linux-hardware.org/?probe=d290113849) | Oct 17, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [29f6ba9612](https://linux-hardware.org/?probe=29f6ba9612) | Oct 17, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [c5beaeaf05](https://linux-hardware.org/?probe=c5beaeaf05) | Oct 17, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [5872b35f8c](https://linux-hardware.org/?probe=5872b35f8c) | Oct 17, 2022 |
| ASUSTek       | PRIME B560M-K               | Desktop     | [8d9bc873e4](https://linux-hardware.org/?probe=8d9bc873e4) | Oct 17, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [9e37b60507](https://linux-hardware.org/?probe=9e37b60507) | Oct 16, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [a45675d222](https://linux-hardware.org/?probe=a45675d222) | Oct 16, 2022 |
| Dell          | Latitude E6430              | Notebook    | [2e8f3bd664](https://linux-hardware.org/?probe=2e8f3bd664) | Oct 16, 2022 |
| ASRock        | Z87 Pro3                    | Desktop     | [364a0afaff](https://linux-hardware.org/?probe=364a0afaff) | Oct 16, 2022 |
| Dell          | 0XFWHV A00                  | Desktop     | [4a5716d169](https://linux-hardware.org/?probe=4a5716d169) | Oct 16, 2022 |
| Dell          | Latitude 3490               | Notebook    | [a739a29b72](https://linux-hardware.org/?probe=a739a29b72) | Oct 16, 2022 |
| Gigabyte      | F2A88XM-HD3P                | Desktop     | [b5c41a9fef](https://linux-hardware.org/?probe=b5c41a9fef) | Oct 16, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [76f457f2aa](https://linux-hardware.org/?probe=76f457f2aa) | Oct 16, 2022 |
| Dell          | Latitude E6420              | Notebook    | [913e2b1acd](https://linux-hardware.org/?probe=913e2b1acd) | Oct 15, 2022 |
| HP            | 1850                        | Desktop     | [eda9bb7861](https://linux-hardware.org/?probe=eda9bb7861) | Oct 15, 2022 |
| Lenovo        | ThinkPad L560 20F1000TJP    | Notebook    | [e9b7a4ffc2](https://linux-hardware.org/?probe=e9b7a4ffc2) | Oct 15, 2022 |
| Gigabyte      | H61M-D2H                    | Desktop     | [3c51ad7454](https://linux-hardware.org/?probe=3c51ad7454) | Oct 15, 2022 |
| Acer          | Aspire A515-44              | Notebook    | [a19fc69283](https://linux-hardware.org/?probe=a19fc69283) | Oct 15, 2022 |
| Intel         | DP45SG AAE27733-403         | Desktop     | [f391a78f4d](https://linux-hardware.org/?probe=f391a78f4d) | Oct 15, 2022 |
| Dell          | 0J3C2F A01                  | Desktop     | [b30840548a](https://linux-hardware.org/?probe=b30840548a) | Oct 15, 2022 |
| LG Electro... | S460-G.BG31P1               | Notebook    | [a0b3b8e905](https://linux-hardware.org/?probe=a0b3b8e905) | Oct 15, 2022 |
| HP            | 3648h                       | Desktop     | [ce5e78d7e3](https://linux-hardware.org/?probe=ce5e78d7e3) | Oct 14, 2022 |
| Dell          | Latitude 3340               | Notebook    | [d99dbe3b99](https://linux-hardware.org/?probe=d99dbe3b99) | Oct 14, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [720d282dfe](https://linux-hardware.org/?probe=720d282dfe) | Oct 14, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [bddc33ef5a](https://linux-hardware.org/?probe=bddc33ef5a) | Oct 14, 2022 |
| Gigabyte      | F2A55M-DS2                  | Desktop     | [1feb9942e8](https://linux-hardware.org/?probe=1feb9942e8) | Oct 14, 2022 |
| Packard Be... | EasyNote TJ66               | Notebook    | [e5f4bf84f8](https://linux-hardware.org/?probe=e5f4bf84f8) | Oct 14, 2022 |
| Compaq        | PRESARIOCQ18                | Notebook    | [5172032993](https://linux-hardware.org/?probe=5172032993) | Oct 14, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [60e6bd1280](https://linux-hardware.org/?probe=60e6bd1280) | Oct 14, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [57e988db9d](https://linux-hardware.org/?probe=57e988db9d) | Oct 14, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [8dc5e6f530](https://linux-hardware.org/?probe=8dc5e6f530) | Oct 14, 2022 |
| Dell          | Latitude E5440              | Notebook    | [432aa93109](https://linux-hardware.org/?probe=432aa93109) | Oct 14, 2022 |
| HP            | Compaq Presario CQ60        | Notebook    | [b040c6de83](https://linux-hardware.org/?probe=b040c6de83) | Oct 14, 2022 |
| Intel         | NUC8BEB J72693-306          | Mini pc     | [a9f67e3f57](https://linux-hardware.org/?probe=a9f67e3f57) | Oct 13, 2022 |
| Dell          | Inspiron 5551               | Notebook    | [64865d9bb5](https://linux-hardware.org/?probe=64865d9bb5) | Oct 13, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [6144d2247a](https://linux-hardware.org/?probe=6144d2247a) | Oct 13, 2022 |
| Dell          | Precision 7720              | Notebook    | [4cadd86832](https://linux-hardware.org/?probe=4cadd86832) | Oct 13, 2022 |
| Dell          | Studio 1555                 | Notebook    | [52104abe69](https://linux-hardware.org/?probe=52104abe69) | Oct 13, 2022 |
| HP            | ENVY 15                     | Notebook    | [71c0056a73](https://linux-hardware.org/?probe=71c0056a73) | Oct 13, 2022 |
| Lenovo        | ThinkCentre M71e 3167B28    | Desktop     | [0cfbd3c2fc](https://linux-hardware.org/?probe=0cfbd3c2fc) | Oct 13, 2022 |
| HP            | Laptop 14-bw0xx             | Notebook    | [3a190d5718](https://linux-hardware.org/?probe=3a190d5718) | Oct 13, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [37b9e0d491](https://linux-hardware.org/?probe=37b9e0d491) | Oct 13, 2022 |
| Apple         | MacBookPro5,3               | Notebook    | [814a533c23](https://linux-hardware.org/?probe=814a533c23) | Oct 13, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [bccf0a4ebe](https://linux-hardware.org/?probe=bccf0a4ebe) | Oct 13, 2022 |
| HP            | 3648h                       | Desktop     | [5b495e41ff](https://linux-hardware.org/?probe=5b495e41ff) | Oct 13, 2022 |
| Dell          | Vostro 3446                 | Notebook    | [da79693286](https://linux-hardware.org/?probe=da79693286) | Oct 13, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [bb386c7d60](https://linux-hardware.org/?probe=bb386c7d60) | Oct 13, 2022 |
| Toshiba       | Satellite C855              | Notebook    | [65e0a41b8d](https://linux-hardware.org/?probe=65e0a41b8d) | Oct 13, 2022 |
| Itautec       | ST 4254 ST-4254 Padrao 0... | Desktop     | [48ee58de23](https://linux-hardware.org/?probe=48ee58de23) | Oct 13, 2022 |
| Acer          | Aspire 7250G                | Notebook    | [34966259d6](https://linux-hardware.org/?probe=34966259d6) | Oct 13, 2022 |
| HP            | G42                         | Notebook    | [fd42e3aedb](https://linux-hardware.org/?probe=fd42e3aedb) | Oct 12, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [a122b26729](https://linux-hardware.org/?probe=a122b26729) | Oct 12, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [ad2b1ab7b8](https://linux-hardware.org/?probe=ad2b1ab7b8) | Oct 12, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [7fda9973db](https://linux-hardware.org/?probe=7fda9973db) | Oct 12, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ccdcc89519](https://linux-hardware.org/?probe=ccdcc89519) | Oct 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [88385d207c](https://linux-hardware.org/?probe=88385d207c) | Oct 12, 2022 |
| Star Labs     | StarLite                    | Notebook    | [627ad33197](https://linux-hardware.org/?probe=627ad33197) | Oct 12, 2022 |
| Apple         | MacBookPro13,2              | Notebook    | [8eaf391b08](https://linux-hardware.org/?probe=8eaf391b08) | Oct 12, 2022 |
| HP            | 1497                        | Desktop     | [ff6d690da4](https://linux-hardware.org/?probe=ff6d690da4) | Oct 12, 2022 |
| ASUSTek       | PRIME A320M-E               | Desktop     | [ff58ea3dc1](https://linux-hardware.org/?probe=ff58ea3dc1) | Oct 12, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [dc990d0395](https://linux-hardware.org/?probe=dc990d0395) | Oct 12, 2022 |
| Dell          | Latitude E6440              | Notebook    | [3b13c28e46](https://linux-hardware.org/?probe=3b13c28e46) | Oct 12, 2022 |
| AMD           | A88                         | Desktop     | [1ee2502537](https://linux-hardware.org/?probe=1ee2502537) | Oct 12, 2022 |
| Pegatron      | IPM31G                      | Desktop     | [75d4fc0b55](https://linux-hardware.org/?probe=75d4fc0b55) | Oct 12, 2022 |
| Lenovo        | ThinkPad T440s 20ARS4PR0... | Notebook    | [18c02300b9](https://linux-hardware.org/?probe=18c02300b9) | Oct 11, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [40adf0a5d8](https://linux-hardware.org/?probe=40adf0a5d8) | Oct 11, 2022 |
| Dell          | 0T656F A01                  | Desktop     | [1680fa50c0](https://linux-hardware.org/?probe=1680fa50c0) | Oct 11, 2022 |
| HP            | 2171                        | Desktop     | [105af7e899](https://linux-hardware.org/?probe=105af7e899) | Oct 11, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [4bc40092b2](https://linux-hardware.org/?probe=4bc40092b2) | Oct 11, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [87cfe8ed2e](https://linux-hardware.org/?probe=87cfe8ed2e) | Oct 11, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [33c86327c4](https://linux-hardware.org/?probe=33c86327c4) | Oct 11, 2022 |
| Lenovo        | ThinkCentre M58 7359WES     | Desktop     | [1c00ee45c1](https://linux-hardware.org/?probe=1c00ee45c1) | Oct 11, 2022 |
| Dell          | Latitude E6540              | Notebook    | [d1b0bd16b5](https://linux-hardware.org/?probe=d1b0bd16b5) | Oct 11, 2022 |
| Lenovo        | ThinkPad X220 42873LJ       | Notebook    | [b96b26c09b](https://linux-hardware.org/?probe=b96b26c09b) | Oct 11, 2022 |
| ASRock        | G41C-GS R2.0                | Desktop     | [92ab2501ea](https://linux-hardware.org/?probe=92ab2501ea) | Oct 11, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [f263785a18](https://linux-hardware.org/?probe=f263785a18) | Oct 11, 2022 |
| Lenovo        | ThinkPad P51 W10DG 20MNS... | Notebook    | [1680df8cd8](https://linux-hardware.org/?probe=1680df8cd8) | Oct 11, 2022 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [e5720c01a5](https://linux-hardware.org/?probe=e5720c01a5) | Oct 10, 2022 |
| ASRock        | B365M Pro4                  | Desktop     | [669c570a2e](https://linux-hardware.org/?probe=669c570a2e) | Oct 10, 2022 |
| HP            | Presario CQ57               | Notebook    | [b67f538b81](https://linux-hardware.org/?probe=b67f538b81) | Oct 10, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [22cf469faa](https://linux-hardware.org/?probe=22cf469faa) | Oct 10, 2022 |
| Acer          | Aspire XC-230               | Desktop     | [d213bca85f](https://linux-hardware.org/?probe=d213bca85f) | Oct 10, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [792528e3b2](https://linux-hardware.org/?probe=792528e3b2) | Oct 10, 2022 |
| Gigabyte      | 945GM-S2                    | Desktop     | [3087d063e3](https://linux-hardware.org/?probe=3087d063e3) | Oct 10, 2022 |
| Lenovo        | IdeaPad S510p 20298         | Notebook    | [f3a23a25c6](https://linux-hardware.org/?probe=f3a23a25c6) | Oct 10, 2022 |
| ASUSTek       | PRIME H410I-PLUS            | Desktop     | [10709dd95e](https://linux-hardware.org/?probe=10709dd95e) | Oct 10, 2022 |
| HP            | Notebook                    | Notebook    | [2fd3bd5ee0](https://linux-hardware.org/?probe=2fd3bd5ee0) | Oct 10, 2022 |
| HP            | 829E                        | Mini pc     | [465ec7a2fe](https://linux-hardware.org/?probe=465ec7a2fe) | Oct 10, 2022 |
| MSI           | P67A-GD65                   | Desktop     | [009f3853bf](https://linux-hardware.org/?probe=009f3853bf) | Oct 10, 2022 |
| Gigabyte      | F2A58M-HD2                  | Desktop     | [a219433035](https://linux-hardware.org/?probe=a219433035) | Oct 10, 2022 |
| AZW           | U59                         | Desktop     | [8300f61a93](https://linux-hardware.org/?probe=8300f61a93) | Oct 10, 2022 |
| HP            | 805D                        | Desktop     | [8938f51322](https://linux-hardware.org/?probe=8938f51322) | Oct 09, 2022 |
| Lenovo        | Dory CRB                    | Desktop     | [33ae78632a](https://linux-hardware.org/?probe=33ae78632a) | Oct 09, 2022 |
| Dell          | Latitude E6410              | Notebook    | [4f6730e0f2](https://linux-hardware.org/?probe=4f6730e0f2) | Oct 09, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [3e7ef86329](https://linux-hardware.org/?probe=3e7ef86329) | Oct 09, 2022 |
| ASUSTek       | X550VB                      | Notebook    | [a7c1c1cb1b](https://linux-hardware.org/?probe=a7c1c1cb1b) | Oct 09, 2022 |
| Dell          | Inspiron N7010              | Notebook    | [8d58156239](https://linux-hardware.org/?probe=8d58156239) | Oct 09, 2022 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [cf3661bb7c](https://linux-hardware.org/?probe=cf3661bb7c) | Oct 09, 2022 |
| ASUSTek       | P7P55D-E LX                 | Desktop     | [d6231f581c](https://linux-hardware.org/?probe=d6231f581c) | Oct 09, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [8918b1b82e](https://linux-hardware.org/?probe=8918b1b82e) | Oct 09, 2022 |
| Chuwi         | RZBOX                       | Desktop     | [76b6d7cd78](https://linux-hardware.org/?probe=76b6d7cd78) | Oct 08, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [d172225c0b](https://linux-hardware.org/?probe=d172225c0b) | Oct 08, 2022 |
| Dell          | 08HPGT A01                  | Desktop     | [1d59ae6f4a](https://linux-hardware.org/?probe=1d59ae6f4a) | Oct 08, 2022 |
| Dell          | Latitude 5580               | Notebook    | [77173e171f](https://linux-hardware.org/?probe=77173e171f) | Oct 08, 2022 |
| MSI           | A55M-P33                    | Desktop     | [127b8f180e](https://linux-hardware.org/?probe=127b8f180e) | Oct 08, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [0a30c048b8](https://linux-hardware.org/?probe=0a30c048b8) | Oct 08, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [3665682cc6](https://linux-hardware.org/?probe=3665682cc6) | Oct 08, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [9d44a35e48](https://linux-hardware.org/?probe=9d44a35e48) | Oct 08, 2022 |
| ASRock        | M3N78D FX                   | Desktop     | [e40ba3988f](https://linux-hardware.org/?probe=e40ba3988f) | Oct 08, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [feb96964b1](https://linux-hardware.org/?probe=feb96964b1) | Oct 08, 2022 |
| Dell          | 0MN1TX A01                  | Desktop     | [a9faf44fe8](https://linux-hardware.org/?probe=a9faf44fe8) | Oct 07, 2022 |
| Fujitsu       | LIFEBOOK E736               | Notebook    | [3e7cc2c14a](https://linux-hardware.org/?probe=3e7cc2c14a) | Oct 07, 2022 |
| HP            | 872E                        | Mini pc     | [651563d698](https://linux-hardware.org/?probe=651563d698) | Oct 07, 2022 |
| HP            | Laptop 15-da2xxx            | Notebook    | [b699753cc6](https://linux-hardware.org/?probe=b699753cc6) | Oct 07, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [29de9dfa4a](https://linux-hardware.org/?probe=29de9dfa4a) | Oct 07, 2022 |
| Dell          | Latitude E6400              | Notebook    | [509deb10b3](https://linux-hardware.org/?probe=509deb10b3) | Oct 07, 2022 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [9dc72dc357](https://linux-hardware.org/?probe=9dc72dc357) | Oct 07, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [c3ecfbe57b](https://linux-hardware.org/?probe=c3ecfbe57b) | Oct 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [8901403de4](https://linux-hardware.org/?probe=8901403de4) | Oct 07, 2022 |
| MSI           | X399 GAMING PRO CARBON A... | Desktop     | [60c519a7dd](https://linux-hardware.org/?probe=60c519a7dd) | Oct 07, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [8061516838](https://linux-hardware.org/?probe=8061516838) | Oct 06, 2022 |
| Toshiba       | Satellite R830              | Notebook    | [0a5299f7e0](https://linux-hardware.org/?probe=0a5299f7e0) | Oct 06, 2022 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | Desktop     | [7a7bc387f4](https://linux-hardware.org/?probe=7a7bc387f4) | Oct 06, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [f19e278e43](https://linux-hardware.org/?probe=f19e278e43) | Oct 06, 2022 |
| Medion        | MS-7797                     | Desktop     | [9137d0eacf](https://linux-hardware.org/?probe=9137d0eacf) | Oct 06, 2022 |
| Toshiba       | dynabook T653/46JR          | Notebook    | [d5f7a80d34](https://linux-hardware.org/?probe=d5f7a80d34) | Oct 06, 2022 |
| Gigabyte      | Z270X-Gaming 5              | Desktop     | [9ad9a1c969](https://linux-hardware.org/?probe=9ad9a1c969) | Oct 06, 2022 |
| ASUSTek       | M2V-MX                      | Desktop     | [55b3f7f6b0](https://linux-hardware.org/?probe=55b3f7f6b0) | Oct 06, 2022 |
| Toshiba       | Satellite C650D             | Notebook    | [69db41a0b6](https://linux-hardware.org/?probe=69db41a0b6) | Oct 06, 2022 |
| Lenovo        | 1031 SDK0E50510 WIN 2625... | Desktop     | [771e19629c](https://linux-hardware.org/?probe=771e19629c) | Oct 05, 2022 |
| HP            | 18E4                        | Desktop     | [d9deeda238](https://linux-hardware.org/?probe=d9deeda238) | Oct 05, 2022 |
| Gigabyte      | TRX40 AORUS PRO WIFI        | Desktop     | [85f2638273](https://linux-hardware.org/?probe=85f2638273) | Oct 05, 2022 |
| Positivo      | C14CR01                     | Notebook    | [7c0d0b2efd](https://linux-hardware.org/?probe=7c0d0b2efd) | Oct 05, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [f9224c972e](https://linux-hardware.org/?probe=f9224c972e) | Oct 05, 2022 |
| Lenovo        | ThinkPad L430 24641J9       | Notebook    | [4f4932300b](https://linux-hardware.org/?probe=4f4932300b) | Oct 05, 2022 |
| Lenovo        | Yoga 510-14IKB 80VB         | Convertible | [e328286003](https://linux-hardware.org/?probe=e328286003) | Oct 05, 2022 |
| HP            | Pavilion 17                 | Notebook    | [f7626421b2](https://linux-hardware.org/?probe=f7626421b2) | Oct 05, 2022 |
| Gigabyte      | H110M-S2PH-CF               | Desktop     | [580c13ac38](https://linux-hardware.org/?probe=580c13ac38) | Oct 05, 2022 |
| Lenovo        | ThinkPad T400 6474WPU       | Notebook    | [14423cc638](https://linux-hardware.org/?probe=14423cc638) | Oct 05, 2022 |
| Acer          | Aspire 5250                 | Notebook    | [8a18115a5b](https://linux-hardware.org/?probe=8a18115a5b) | Oct 04, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [612b4b36a1](https://linux-hardware.org/?probe=612b4b36a1) | Oct 04, 2022 |
| Dell          | XPS 9320                    | Notebook    | [c4888023c3](https://linux-hardware.org/?probe=c4888023c3) | Oct 04, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [b151ce6353](https://linux-hardware.org/?probe=b151ce6353) | Oct 04, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [1923c04bfc](https://linux-hardware.org/?probe=1923c04bfc) | Oct 04, 2022 |
| Dell          | 01TKCC A01                  | Desktop     | [65103a04c3](https://linux-hardware.org/?probe=65103a04c3) | Oct 04, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [b8ad7a8464](https://linux-hardware.org/?probe=b8ad7a8464) | Oct 04, 2022 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [1cceb45dea](https://linux-hardware.org/?probe=1cceb45dea) | Oct 04, 2022 |
| Acer          | Aspire 4736                 | Notebook    | [48b8af7bcf](https://linux-hardware.org/?probe=48b8af7bcf) | Oct 04, 2022 |
| Wortmann      | 1220676_1470204             | Tablet      | [09cdce1807](https://linux-hardware.org/?probe=09cdce1807) | Oct 04, 2022 |
| Dell          | Latitude 3120               | Convertible | [60de9a1977](https://linux-hardware.org/?probe=60de9a1977) | Oct 04, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [adde8098e4](https://linux-hardware.org/?probe=adde8098e4) | Oct 04, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [89400b60b0](https://linux-hardware.org/?probe=89400b60b0) | Oct 04, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [4994764371](https://linux-hardware.org/?probe=4994764371) | Oct 04, 2022 |
| HP            | 213D A01                    | Desktop     | [e81fd5fea5](https://linux-hardware.org/?probe=e81fd5fea5) | Oct 04, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [5e60e8faae](https://linux-hardware.org/?probe=5e60e8faae) | Oct 04, 2022 |
| ASUSTek       | P5W DH Deluxe               | Desktop     | [8d5a649ba5](https://linux-hardware.org/?probe=8d5a649ba5) | Oct 03, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [1348c5b5eb](https://linux-hardware.org/?probe=1348c5b5eb) | Oct 03, 2022 |
| HP            | 2AED                        | All in one  | [9092720ed6](https://linux-hardware.org/?probe=9092720ed6) | Oct 03, 2022 |
| Intel         | H55                         | Desktop     | [73719c58ab](https://linux-hardware.org/?probe=73719c58ab) | Oct 03, 2022 |
| MSI           | H110M GAMING                | Desktop     | [379aaceaab](https://linux-hardware.org/?probe=379aaceaab) | Oct 03, 2022 |
| Dell          | Latitude E6420              | Notebook    | [cc0d33aedb](https://linux-hardware.org/?probe=cc0d33aedb) | Oct 03, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [a055ed4d2c](https://linux-hardware.org/?probe=a055ed4d2c) | Oct 03, 2022 |
| Acer          | TravelMate 5744             | Notebook    | [4817d4810d](https://linux-hardware.org/?probe=4817d4810d) | Oct 03, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [80a70e8f6e](https://linux-hardware.org/?probe=80a70e8f6e) | Oct 03, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN         | Desktop     | [f6a6361e08](https://linux-hardware.org/?probe=f6a6361e08) | Oct 03, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [9bf3a4a735](https://linux-hardware.org/?probe=9bf3a4a735) | Oct 03, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [36b32fe8c0](https://linux-hardware.org/?probe=36b32fe8c0) | Oct 03, 2022 |
| ASRock        | G41C-GS R2.0                | Desktop     | [c6e6708366](https://linux-hardware.org/?probe=c6e6708366) | Oct 03, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [019702e62b](https://linux-hardware.org/?probe=019702e62b) | Oct 03, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [abfab502a6](https://linux-hardware.org/?probe=abfab502a6) | Oct 02, 2022 |
| Lenovo        | ThinkCentre M58p 6234FB9    | Desktop     | [3c772e3e1d](https://linux-hardware.org/?probe=3c772e3e1d) | Oct 02, 2022 |
| ASUSTek       | UX303UB                     | Notebook    | [d67f04fc6e](https://linux-hardware.org/?probe=d67f04fc6e) | Oct 02, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [47a7282318](https://linux-hardware.org/?probe=47a7282318) | Oct 02, 2022 |
| ASUSTek       | X550JX                      | Notebook    | [43694e5952](https://linux-hardware.org/?probe=43694e5952) | Oct 02, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [bfd8dc3c18](https://linux-hardware.org/?probe=bfd8dc3c18) | Oct 02, 2022 |
| MSI           | A75A-G35                    | Desktop     | [66b1d71092](https://linux-hardware.org/?probe=66b1d71092) | Oct 02, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [516795a4a8](https://linux-hardware.org/?probe=516795a4a8) | Oct 02, 2022 |
| Biostar       | A75MG                       | Desktop     | [ba1785b4b6](https://linux-hardware.org/?probe=ba1785b4b6) | Oct 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [be11beaedd](https://linux-hardware.org/?probe=be11beaedd) | Oct 02, 2022 |
| MSI           | B75MA-E33                   | Desktop     | [a14df6d116](https://linux-hardware.org/?probe=a14df6d116) | Oct 02, 2022 |
| ASRock        | Z97 Pro4                    | Desktop     | [d0465080bf](https://linux-hardware.org/?probe=d0465080bf) | Oct 02, 2022 |
| Lenovo        | ThinkCentre M91p 4518AU8    | Desktop     | [ce1567bb35](https://linux-hardware.org/?probe=ce1567bb35) | Oct 02, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [d4f76a4236](https://linux-hardware.org/?probe=d4f76a4236) | Oct 01, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [9c6340e585](https://linux-hardware.org/?probe=9c6340e585) | Oct 01, 2022 |
| ASRock        | J5005-ITX                   | Desktop     | [783c72d32e](https://linux-hardware.org/?probe=783c72d32e) | Oct 01, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [ba72c7ee42](https://linux-hardware.org/?probe=ba72c7ee42) | Oct 01, 2022 |
| MSI           | MS-7235                     | Desktop     | [838e2c27f1](https://linux-hardware.org/?probe=838e2c27f1) | Oct 01, 2022 |
| Lenovo        | 3000 N200 0769B4G           | Notebook    | [947f124efc](https://linux-hardware.org/?probe=947f124efc) | Oct 01, 2022 |
| Lenovo        | 0x30F617AA NOK              | Desktop     | [bb13b87bd5](https://linux-hardware.org/?probe=bb13b87bd5) | Oct 01, 2022 |
| Itautec       | Infoway a7420               | Notebook    | [bb52fe66cf](https://linux-hardware.org/?probe=bb52fe66cf) | Oct 01, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [7ff2c5ad1c](https://linux-hardware.org/?probe=7ff2c5ad1c) | Oct 01, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [a64cec6a4d](https://linux-hardware.org/?probe=a64cec6a4d) | Oct 01, 2022 |
| ASUSTek       | UX303UB                     | Notebook    | [e09f793c1a](https://linux-hardware.org/?probe=e09f793c1a) | Oct 01, 2022 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [68b0c0ca1a](https://linux-hardware.org/?probe=68b0c0ca1a) | Oct 01, 2022 |
| MSI           | B350M PRO-VDH               | Desktop     | [1a0d8b695d](https://linux-hardware.org/?probe=1a0d8b695d) | Oct 01, 2022 |
| Lenovo        | 3098 NOK                    | Desktop     | [a46521af41](https://linux-hardware.org/?probe=a46521af41) | Oct 01, 2022 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | Desktop     | [982b143d73](https://linux-hardware.org/?probe=982b143d73) | Oct 01, 2022 |
| ASUSTek       | K53SM                       | Notebook    | [f05f33fa9b](https://linux-hardware.org/?probe=f05f33fa9b) | Oct 01, 2022 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [d967f57569](https://linux-hardware.org/?probe=d967f57569) | Oct 01, 2022 |
| HP            | Pavilion dv2700             | Notebook    | [0da9fb0afd](https://linux-hardware.org/?probe=0da9fb0afd) | Oct 01, 2022 |
| ASUSTek       | M5A87                       | Desktop     | [89ca067566](https://linux-hardware.org/?probe=89ca067566) | Oct 01, 2022 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [8c24fa2271](https://linux-hardware.org/?probe=8c24fa2271) | Oct 01, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [aee33639b9](https://linux-hardware.org/?probe=aee33639b9) | Oct 01, 2022 |
| Gigabyte      | B360 AORUS GAMING 3-CF      | Desktop     | [87a1c21540](https://linux-hardware.org/?probe=87a1c21540) | Oct 01, 2022 |
| Sony          | VPCYB3V1E                   | Notebook    | [de50c8a304](https://linux-hardware.org/?probe=de50c8a304) | Oct 01, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [f50a823779](https://linux-hardware.org/?probe=f50a823779) | Oct 01, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [24aefc4138](https://linux-hardware.org/?probe=24aefc4138) | Oct 01, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [646f4ffa8e](https://linux-hardware.org/?probe=646f4ffa8e) | Oct 01, 2022 |
| Sony          | VPCEH2D0E                   | Notebook    | [a08d0148e2](https://linux-hardware.org/?probe=a08d0148e2) | Sep 30, 2022 |
| Intel         | H61                         | Desktop     | [37af3b0cdb](https://linux-hardware.org/?probe=37af3b0cdb) | Sep 30, 2022 |
| ASRock        | B450M Pro4-F                | Desktop     | [75b0aa3c75](https://linux-hardware.org/?probe=75b0aa3c75) | Sep 30, 2022 |
| Lenovo        | 0x36A017AA SDK0J40700 WI... | Desktop     | [a6b14fdcf3](https://linux-hardware.org/?probe=a6b14fdcf3) | Sep 30, 2022 |
| Dell          | Inspiron 11-3162            | Notebook    | [8cd15b2f0c](https://linux-hardware.org/?probe=8cd15b2f0c) | Sep 30, 2022 |
| Acer          | Batman A01                  | Desktop     | [f8ebe348e4](https://linux-hardware.org/?probe=f8ebe348e4) | Sep 30, 2022 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [f0eae50061](https://linux-hardware.org/?probe=f0eae50061) | Sep 30, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [cfe1aba7e6](https://linux-hardware.org/?probe=cfe1aba7e6) | Sep 30, 2022 |
| ASUSTek       | P5KPL-AM EPU                | Desktop     | [66877298d4](https://linux-hardware.org/?probe=66877298d4) | Sep 30, 2022 |
| Dell          | Latitude E6520              | Notebook    | [04817b4ceb](https://linux-hardware.org/?probe=04817b4ceb) | Sep 30, 2022 |
| Lenovo        | G460 20041                  | Notebook    | [9018f40ad5](https://linux-hardware.org/?probe=9018f40ad5) | Sep 30, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [11e4602764](https://linux-hardware.org/?probe=11e4602764) | Sep 30, 2022 |
| Dell          | Latitude 3310               | Notebook    | [3c4874fa51](https://linux-hardware.org/?probe=3c4874fa51) | Sep 30, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [7ed786bee9](https://linux-hardware.org/?probe=7ed786bee9) | Sep 30, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [26961d1b30](https://linux-hardware.org/?probe=26961d1b30) | Sep 29, 2022 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [d153a4f97a](https://linux-hardware.org/?probe=d153a4f97a) | Sep 29, 2022 |
| Toshiba       | Satellite L505              | Notebook    | [3e91e2bfaf](https://linux-hardware.org/?probe=3e91e2bfaf) | Sep 29, 2022 |
| Dell          | Latitude D531               | Notebook    | [331cad8b98](https://linux-hardware.org/?probe=331cad8b98) | Sep 29, 2022 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [3990ec6cb0](https://linux-hardware.org/?probe=3990ec6cb0) | Sep 29, 2022 |
| HP            | 3398                        | Desktop     | [c2190a0657](https://linux-hardware.org/?probe=c2190a0657) | Sep 29, 2022 |
| Dell          | 0Y5DDC A00                  | Desktop     | [f9efac58da](https://linux-hardware.org/?probe=f9efac58da) | Sep 29, 2022 |
| HP            | Compaq 6720s                | Notebook    | [ddb5163310](https://linux-hardware.org/?probe=ddb5163310) | Sep 29, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [88d57c6319](https://linux-hardware.org/?probe=88d57c6319) | Sep 29, 2022 |
| Huanan        | X79 (INTEL Xeon E5/Corei... | Desktop     | [a40d59533c](https://linux-hardware.org/?probe=a40d59533c) | Sep 29, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [9414d73ae0](https://linux-hardware.org/?probe=9414d73ae0) | Sep 29, 2022 |
| Acer          | Veriton M275                | Desktop     | [f871926a8e](https://linux-hardware.org/?probe=f871926a8e) | Sep 29, 2022 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [235930defb](https://linux-hardware.org/?probe=235930defb) | Sep 28, 2022 |
| Gigabyte      | Z87X-UD5H-CF                | Desktop     | [5a7ad7dba9](https://linux-hardware.org/?probe=5a7ad7dba9) | Sep 28, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [6f1ecca2f0](https://linux-hardware.org/?probe=6f1ecca2f0) | Sep 28, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [372cdc3726](https://linux-hardware.org/?probe=372cdc3726) | Sep 28, 2022 |
| Dell          | Latitude 3310               | Notebook    | [c21a321dce](https://linux-hardware.org/?probe=c21a321dce) | Sep 28, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [a42a4722f7](https://linux-hardware.org/?probe=a42a4722f7) | Sep 28, 2022 |
| Dell          | Latitude 3120               | Convertible | [2e9902fee0](https://linux-hardware.org/?probe=2e9902fee0) | Sep 28, 2022 |
| Dell          | Vostro 5391                 | Notebook    | [61a25cdb83](https://linux-hardware.org/?probe=61a25cdb83) | Sep 28, 2022 |
| Dell          | Latitude 3120               | Convertible | [932a938506](https://linux-hardware.org/?probe=932a938506) | Sep 28, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [c3041b210f](https://linux-hardware.org/?probe=c3041b210f) | Sep 28, 2022 |
| HP            | 18E7                        | Desktop     | [132a87f746](https://linux-hardware.org/?probe=132a87f746) | Sep 28, 2022 |
| Toshiba       | dynabook T653/46JR          | Notebook    | [9a613eaf66](https://linux-hardware.org/?probe=9a613eaf66) | Sep 28, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [ada186ce05](https://linux-hardware.org/?probe=ada186ce05) | Sep 27, 2022 |
| Biostar       | A10N-8800E                  | Desktop     | [d27bf09dc8](https://linux-hardware.org/?probe=d27bf09dc8) | Sep 27, 2022 |
| Sony          | VPCEH1S1R                   | Notebook    | [5214bb023f](https://linux-hardware.org/?probe=5214bb023f) | Sep 27, 2022 |
| Dell          | Latitude 3300               | Notebook    | [365349d964](https://linux-hardware.org/?probe=365349d964) | Sep 27, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [af23e43e99](https://linux-hardware.org/?probe=af23e43e99) | Sep 27, 2022 |
| Dell          | Latitude 3310               | Notebook    | [313ab64584](https://linux-hardware.org/?probe=313ab64584) | Sep 27, 2022 |
| HP            | 844C                        | Desktop     | [51cb0bca57](https://linux-hardware.org/?probe=51cb0bca57) | Sep 27, 2022 |
| HP            | 0A60h                       | Desktop     | [ccb90a4b31](https://linux-hardware.org/?probe=ccb90a4b31) | Sep 27, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [d46d96565b](https://linux-hardware.org/?probe=d46d96565b) | Sep 27, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [f5f99a7234](https://linux-hardware.org/?probe=f5f99a7234) | Sep 27, 2022 |
| Toshiba       | Satellite C850-1LK          | Notebook    | [f0240dcb2d](https://linux-hardware.org/?probe=f0240dcb2d) | Sep 27, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [7cea84adb2](https://linux-hardware.org/?probe=7cea84adb2) | Sep 27, 2022 |
| Lenovo        | IdeaPad Z580                | Notebook    | [a33ab40c8b](https://linux-hardware.org/?probe=a33ab40c8b) | Sep 27, 2022 |
| Dell          | Latitude 3120               | Convertible | [bc34bf4d73](https://linux-hardware.org/?probe=bc34bf4d73) | Sep 27, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [3bafc34ffc](https://linux-hardware.org/?probe=3bafc34ffc) | Sep 27, 2022 |
| Positivo      | SW6H                        | Notebook    | [4cfa6665bb](https://linux-hardware.org/?probe=4cfa6665bb) | Sep 27, 2022 |
| Packard Be... | EasyNote LS44SB             | Notebook    | [184a0768bd](https://linux-hardware.org/?probe=184a0768bd) | Sep 26, 2022 |
| Dell          | Latitude 3120               | Convertible | [56ac60a3dc](https://linux-hardware.org/?probe=56ac60a3dc) | Sep 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [898f9bf963](https://linux-hardware.org/?probe=898f9bf963) | Sep 26, 2022 |
| Dell          | Latitude 3120               | Convertible | [8736347f60](https://linux-hardware.org/?probe=8736347f60) | Sep 26, 2022 |
| Dell          | Latitude 3420               | Notebook    | [ee7c1fce66](https://linux-hardware.org/?probe=ee7c1fce66) | Sep 26, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [9d1392e945](https://linux-hardware.org/?probe=9d1392e945) | Sep 26, 2022 |
| MSI           | MAG B460 TOMAHAWK           | Desktop     | [a213c6d22a](https://linux-hardware.org/?probe=a213c6d22a) | Sep 26, 2022 |
| Dell          | Latitude 3310               | Notebook    | [0f1fb4687f](https://linux-hardware.org/?probe=0f1fb4687f) | Sep 26, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [6ce0a09785](https://linux-hardware.org/?probe=6ce0a09785) | Sep 26, 2022 |
| Dell          | Latitude 3310               | Notebook    | [a6ce17cd6b](https://linux-hardware.org/?probe=a6ce17cd6b) | Sep 26, 2022 |
| Acer          | Aspire V5-471               | Notebook    | [66437a2187](https://linux-hardware.org/?probe=66437a2187) | Sep 26, 2022 |
| Dell          | Latitude 3310               | Notebook    | [87af9a8980](https://linux-hardware.org/?probe=87af9a8980) | Sep 26, 2022 |
| Dell          | Latitude 3120               | Convertible | [9458cffde8](https://linux-hardware.org/?probe=9458cffde8) | Sep 26, 2022 |
| Dell          | Latitude E5250              | Notebook    | [e4ffe3583d](https://linux-hardware.org/?probe=e4ffe3583d) | Sep 26, 2022 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [8d3b235d4c](https://linux-hardware.org/?probe=8d3b235d4c) | Sep 25, 2022 |
| CCE           | Capella & IbexPeak-M Chi... | Notebook    | [07554a7a2b](https://linux-hardware.org/?probe=07554a7a2b) | Sep 25, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [8749a17d26](https://linux-hardware.org/?probe=8749a17d26) | Sep 25, 2022 |
| Intel         | NUC10i7FNB K61360-305       | Mini pc     | [a7aadaeed0](https://linux-hardware.org/?probe=a7aadaeed0) | Sep 25, 2022 |
| HP            | Laptop 17-by3xxx            | Notebook    | [41db205ec7](https://linux-hardware.org/?probe=41db205ec7) | Sep 25, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [21121aa007](https://linux-hardware.org/?probe=21121aa007) | Sep 25, 2022 |
| Lenovo        | ThinkPad SL500 27464DG      | Notebook    | [6c2b4ce4b1](https://linux-hardware.org/?probe=6c2b4ce4b1) | Sep 25, 2022 |
| ASUSTek       | CM1740                      | Desktop     | [6ebc913933](https://linux-hardware.org/?probe=6ebc913933) | Sep 25, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [6c6ae30eba](https://linux-hardware.org/?probe=6c6ae30eba) | Sep 24, 2022 |
| BESSTAR Te... | UM350                       | Desktop     | [8442ff18ca](https://linux-hardware.org/?probe=8442ff18ca) | Sep 24, 2022 |
| HP            | Pavilion 15                 | Notebook    | [32670a0451](https://linux-hardware.org/?probe=32670a0451) | Sep 24, 2022 |
| Dell          | 0NV0M7 A02                  | Desktop     | [02925c7220](https://linux-hardware.org/?probe=02925c7220) | Sep 24, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [e78a82387b](https://linux-hardware.org/?probe=e78a82387b) | Sep 24, 2022 |
| HP            | 198E                        | Desktop     | [ffa9a79cc0](https://linux-hardware.org/?probe=ffa9a79cc0) | Sep 24, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [c354f2b293](https://linux-hardware.org/?probe=c354f2b293) | Sep 24, 2022 |
| Dell          | Inspiron 3721               | Notebook    | [7411a700cf](https://linux-hardware.org/?probe=7411a700cf) | Sep 24, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [dafafa97a4](https://linux-hardware.org/?probe=dafafa97a4) | Sep 24, 2022 |
| Acidanther... | Mac-A369DDC4E67F1C45 iMa... | All in one  | [0e9b82f312](https://linux-hardware.org/?probe=0e9b82f312) | Sep 24, 2022 |
| Unknown       | WZBTDT1 R110                | Desktop     | [8b6b5af31a](https://linux-hardware.org/?probe=8b6b5af31a) | Sep 24, 2022 |
| Intel         | DG41WV AAE90316-103         | Desktop     | [425dd57672](https://linux-hardware.org/?probe=425dd57672) | Sep 24, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [815fe42722](https://linux-hardware.org/?probe=815fe42722) | Sep 23, 2022 |
| Fujitsu       | LIFEBOOK S760               | Notebook    | [ceda61113a](https://linux-hardware.org/?probe=ceda61113a) | Sep 23, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [991137f04f](https://linux-hardware.org/?probe=991137f04f) | Sep 23, 2022 |
| HP            | 0AA8h                       | Desktop     | [9c02e3fc31](https://linux-hardware.org/?probe=9c02e3fc31) | Sep 23, 2022 |
| Dell          | 0PTTT9 A00                  | Desktop     | [21bde061e9](https://linux-hardware.org/?probe=21bde061e9) | Sep 23, 2022 |
| Lenovo        | ThinkCentre M58p 6137CR4    | Desktop     | [72e0bfca3b](https://linux-hardware.org/?probe=72e0bfca3b) | Sep 23, 2022 |
| Dell          | Latitude 3120               | Convertible | [5281ee08e1](https://linux-hardware.org/?probe=5281ee08e1) | Sep 23, 2022 |
| Dell          | Latitude 3310               | Notebook    | [4c5dc33267](https://linux-hardware.org/?probe=4c5dc33267) | Sep 23, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [9c4d48864b](https://linux-hardware.org/?probe=9c4d48864b) | Sep 23, 2022 |
| Lenovo        | ThinkCentre Edge71 1578D... | Desktop     | [95dded89b8](https://linux-hardware.org/?probe=95dded89b8) | Sep 23, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [443df1ca5c](https://linux-hardware.org/?probe=443df1ca5c) | Sep 23, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [061ef6f153](https://linux-hardware.org/?probe=061ef6f153) | Sep 23, 2022 |
| ASUSTek       | PRIME B560M-A AC            | Desktop     | [a99682c38d](https://linux-hardware.org/?probe=a99682c38d) | Sep 23, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [69a66aefdd](https://linux-hardware.org/?probe=69a66aefdd) | Sep 23, 2022 |
| Dell          | Latitude 7480               | Notebook    | [e1a3ca1d32](https://linux-hardware.org/?probe=e1a3ca1d32) | Sep 22, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [2b37d81d4c](https://linux-hardware.org/?probe=2b37d81d4c) | Sep 22, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [2527dc6ea0](https://linux-hardware.org/?probe=2527dc6ea0) | Sep 22, 2022 |
| Acer          | Nitro AN515-31              | Notebook    | [9b451feb14](https://linux-hardware.org/?probe=9b451feb14) | Sep 22, 2022 |
| HP            | Compaq 15                   | Notebook    | [345fe48777](https://linux-hardware.org/?probe=345fe48777) | Sep 22, 2022 |
| Lenovo        | ThinkPad X200s 7470WWD      | Notebook    | [268aa65de3](https://linux-hardware.org/?probe=268aa65de3) | Sep 22, 2022 |
| HP            | 1998                        | Desktop     | [f8399e0d3a](https://linux-hardware.org/?probe=f8399e0d3a) | Sep 22, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [07477a078f](https://linux-hardware.org/?probe=07477a078f) | Sep 22, 2022 |
| ASUSTek       | K70AD                       | Notebook    | [49dff3ffb5](https://linux-hardware.org/?probe=49dff3ffb5) | Sep 22, 2022 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | Notebook    | [c1edc96aa7](https://linux-hardware.org/?probe=c1edc96aa7) | Sep 21, 2022 |
| ASUSTek       | X441BA                      | Notebook    | [e542a68ddf](https://linux-hardware.org/?probe=e542a68ddf) | Sep 21, 2022 |
| Lenovo        | 30BB SDK0J40697 WIN 3305... | All in one  | [989f23b214](https://linux-hardware.org/?probe=989f23b214) | Sep 21, 2022 |
| MSI           | Z370 GAMING PRO CARBON      | Desktop     | [978c6dd9dd](https://linux-hardware.org/?probe=978c6dd9dd) | Sep 21, 2022 |
| HP            | 1998                        | Desktop     | [5148539ae1](https://linux-hardware.org/?probe=5148539ae1) | Sep 21, 2022 |
| Toshiba       | dynabook T653/46JR          | Notebook    | [ee93820bdf](https://linux-hardware.org/?probe=ee93820bdf) | Sep 21, 2022 |
| Dell          | G5 5505                     | Notebook    | [82017aa2ae](https://linux-hardware.org/?probe=82017aa2ae) | Sep 21, 2022 |
| MACHINIST     | B75 PRO V1.0                | Desktop     | [752cb8efae](https://linux-hardware.org/?probe=752cb8efae) | Sep 21, 2022 |
| ASUSTek       | UX303LAB                    | Notebook    | [2165b4b046](https://linux-hardware.org/?probe=2165b4b046) | Sep 20, 2022 |
| Dell          | XPS 9320                    | Notebook    | [cd57903024](https://linux-hardware.org/?probe=cd57903024) | Sep 20, 2022 |
| Dell          | Precision M3800             | Notebook    | [2d5d8707dd](https://linux-hardware.org/?probe=2d5d8707dd) | Sep 20, 2022 |
| Gigabyte      | GA-780T-D3L                 | Desktop     | [3e0939e549](https://linux-hardware.org/?probe=3e0939e549) | Sep 20, 2022 |
| Acer          | Aspire A315-23              | Notebook    | [dd730980b1](https://linux-hardware.org/?probe=dd730980b1) | Sep 20, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [a82f4ceccc](https://linux-hardware.org/?probe=a82f4ceccc) | Sep 20, 2022 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | Desktop     | [4d5fc6b39f](https://linux-hardware.org/?probe=4d5fc6b39f) | Sep 20, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [9c483616f6](https://linux-hardware.org/?probe=9c483616f6) | Sep 20, 2022 |
| Acer          | Aspire V3-471               | Notebook    | [b04cc2ea05](https://linux-hardware.org/?probe=b04cc2ea05) | Sep 20, 2022 |
| Lenovo        | 3728 SDK0R32862 WIN 3258... | Desktop     | [d78d85bde3](https://linux-hardware.org/?probe=d78d85bde3) | Sep 20, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [8003baae8c](https://linux-hardware.org/?probe=8003baae8c) | Sep 19, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [a2d230d217](https://linux-hardware.org/?probe=a2d230d217) | Sep 19, 2022 |
| Acer          | Nitro AN515-31              | Notebook    | [33e582251a](https://linux-hardware.org/?probe=33e582251a) | Sep 19, 2022 |
| Lenovo        | G50-80 80R0                 | Notebook    | [f04ed15344](https://linux-hardware.org/?probe=f04ed15344) | Sep 19, 2022 |
| Samsung       | R530/R730                   | Notebook    | [0d4e13e70f](https://linux-hardware.org/?probe=0d4e13e70f) | Sep 19, 2022 |
| Dell          | Latitude 3310               | Notebook    | [0e1784b38d](https://linux-hardware.org/?probe=0e1784b38d) | Sep 19, 2022 |
| Dell          | Latitude 3120               | Convertible | [983266d6ba](https://linux-hardware.org/?probe=983266d6ba) | Sep 19, 2022 |
| Dell          | Latitude 3120               | Convertible | [374de3c13c](https://linux-hardware.org/?probe=374de3c13c) | Sep 19, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [bc2dd8505b](https://linux-hardware.org/?probe=bc2dd8505b) | Sep 19, 2022 |
| HP            | 2B34                        | Desktop     | [a9e82bbb40](https://linux-hardware.org/?probe=a9e82bbb40) | Sep 19, 2022 |
| Dell          | Latitude 3310               | Notebook    | [55332651e0](https://linux-hardware.org/?probe=55332651e0) | Sep 19, 2022 |
| Dell          | Latitude 3120               | Convertible | [e6b9b405e8](https://linux-hardware.org/?probe=e6b9b405e8) | Sep 19, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [448ba707f6](https://linux-hardware.org/?probe=448ba707f6) | Sep 19, 2022 |
| Dell          | Latitude 3120               | Notebook    | [558e95141d](https://linux-hardware.org/?probe=558e95141d) | Sep 19, 2022 |
| Toshiba       | PORTEGE Z30-A               | Notebook    | [419bf72e22](https://linux-hardware.org/?probe=419bf72e22) | Sep 19, 2022 |
| Dell          | Latitude 3300               | Notebook    | [a2513a9849](https://linux-hardware.org/?probe=a2513a9849) | Sep 19, 2022 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [c9ab60a094](https://linux-hardware.org/?probe=c9ab60a094) | Sep 19, 2022 |
| ECS           | A55F2-M4                    | Desktop     | [335d28e72c](https://linux-hardware.org/?probe=335d28e72c) | Sep 19, 2022 |
| ASUSTek       | M5A88-V EVO                 | Desktop     | [9dc35eec1a](https://linux-hardware.org/?probe=9dc35eec1a) | Sep 19, 2022 |
| Positivo      | C14CR21                     | Notebook    | [e72ef2677b](https://linux-hardware.org/?probe=e72ef2677b) | Sep 19, 2022 |
| Lenovo        | ThinkPad T400 6474WPU       | Notebook    | [892c3fb361](https://linux-hardware.org/?probe=892c3fb361) | Sep 18, 2022 |
| HP            | EliteBook 2740p             | Notebook    | [6643773237](https://linux-hardware.org/?probe=6643773237) | Sep 18, 2022 |
| NEC Comput... | PC-VK26MXZCE                | Notebook    | [db8f5e4181](https://linux-hardware.org/?probe=db8f5e4181) | Sep 18, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [f5fb874e1e](https://linux-hardware.org/?probe=f5fb874e1e) | Sep 18, 2022 |
| ASUSTek       | X510UQ                      | Notebook    | [eb619ed1c5](https://linux-hardware.org/?probe=eb619ed1c5) | Sep 18, 2022 |
| HP            | 2B29                        | Desktop     | [391e407d29](https://linux-hardware.org/?probe=391e407d29) | Sep 18, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [08bd4157a3](https://linux-hardware.org/?probe=08bd4157a3) | Sep 18, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [7f906bad42](https://linux-hardware.org/?probe=7f906bad42) | Sep 18, 2022 |
| HP            | 843F                        | Desktop     | [7694ed2ffa](https://linux-hardware.org/?probe=7694ed2ffa) | Sep 18, 2022 |
| Lenovo        | ThinkPad T430 23501M2       | Notebook    | [b9503c9c28](https://linux-hardware.org/?probe=b9503c9c28) | Sep 18, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [65c4f113d8](https://linux-hardware.org/?probe=65c4f113d8) | Sep 18, 2022 |
| HP            | ProBook 6470b               | Notebook    | [3821322b95](https://linux-hardware.org/?probe=3821322b95) | Sep 18, 2022 |
| Acer          | Switch SA5-271P             | Tablet      | [c9900a8e2f](https://linux-hardware.org/?probe=c9900a8e2f) | Sep 17, 2022 |
| HP            | Notebook                    | Notebook    | [d29681d2ed](https://linux-hardware.org/?probe=d29681d2ed) | Sep 17, 2022 |
| Lenovo        | B50-45 20388                | Notebook    | [d55d9fad24](https://linux-hardware.org/?probe=d55d9fad24) | Sep 17, 2022 |
| Lenovo        | ThinkPad E570 20H5009NUS    | Notebook    | [c64258edc0](https://linux-hardware.org/?probe=c64258edc0) | Sep 17, 2022 |
| Dell          | Latitude 7390               | Notebook    | [64c9b13553](https://linux-hardware.org/?probe=64c9b13553) | Sep 17, 2022 |
| Toshiba       | TECRA S10                   | Notebook    | [602d81b7c5](https://linux-hardware.org/?probe=602d81b7c5) | Sep 17, 2022 |
| NEC Comput... | PC-VY21AEZ75                | Notebook    | [a24d79ffc2](https://linux-hardware.org/?probe=a24d79ffc2) | Sep 17, 2022 |
| Toshiba       | Satellite P845T             | Notebook    | [0d5f5ac925](https://linux-hardware.org/?probe=0d5f5ac925) | Sep 17, 2022 |
| ASUSTek       | P8P67                       | Desktop     | [a790b35cc1](https://linux-hardware.org/?probe=a790b35cc1) | Sep 17, 2022 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [f75308c465](https://linux-hardware.org/?probe=f75308c465) | Sep 17, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [e55484acd4](https://linux-hardware.org/?probe=e55484acd4) | Sep 17, 2022 |
| Dell          | Precision 7720              | Notebook    | [9658507a0b](https://linux-hardware.org/?probe=9658507a0b) | Sep 17, 2022 |
| HP            | Laptop 15-ef0xxx            | Notebook    | [19d0260ef6](https://linux-hardware.org/?probe=19d0260ef6) | Sep 17, 2022 |
| HP            | 255 G5 Notebook PC          | Notebook    | [6d8f7ffe97](https://linux-hardware.org/?probe=6d8f7ffe97) | Sep 17, 2022 |
| Toshiba       | dynabook T653/46JR          | Notebook    | [7f9cf09305](https://linux-hardware.org/?probe=7f9cf09305) | Sep 17, 2022 |
| Intel         | H61                         | Desktop     | [d1b17183d7](https://linux-hardware.org/?probe=d1b17183d7) | Sep 16, 2022 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [21620af2bb](https://linux-hardware.org/?probe=21620af2bb) | Sep 16, 2022 |
| Apple         | MacBook6,1                  | Notebook    | [93b43e5bb5](https://linux-hardware.org/?probe=93b43e5bb5) | Sep 16, 2022 |
| Lenovo        | ThinkPad T420 4180A32       | Notebook    | [44841341fd](https://linux-hardware.org/?probe=44841341fd) | Sep 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [d5464b13f9](https://linux-hardware.org/?probe=d5464b13f9) | Sep 16, 2022 |
| HP            | 82F2 A01                    | Desktop     | [f97faeff54](https://linux-hardware.org/?probe=f97faeff54) | Sep 16, 2022 |
| Dell          | Latitude 3120               | Convertible | [e472e7fdde](https://linux-hardware.org/?probe=e472e7fdde) | Sep 16, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [1ccce4a76a](https://linux-hardware.org/?probe=1ccce4a76a) | Sep 16, 2022 |
| Dell          | Latitude 3120               | Convertible | [e04ec1834f](https://linux-hardware.org/?probe=e04ec1834f) | Sep 16, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [52fe410fe3](https://linux-hardware.org/?probe=52fe410fe3) | Sep 16, 2022 |
| HP            | Compaq Presario CQ50        | Notebook    | [41dcd9ffc4](https://linux-hardware.org/?probe=41dcd9ffc4) | Sep 16, 2022 |
| Sony          | VAIO                        | All in one  | [71ae1045da](https://linux-hardware.org/?probe=71ae1045da) | Sep 15, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [fcdfa43a37](https://linux-hardware.org/?probe=fcdfa43a37) | Sep 15, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [9a7d178f1b](https://linux-hardware.org/?probe=9a7d178f1b) | Sep 15, 2022 |
| Lenovo        | IdeaPad Y570 20091          | Notebook    | [5e2681360e](https://linux-hardware.org/?probe=5e2681360e) | Sep 15, 2022 |
| Lenovo        | ThinkPad T530 2429F33       | Notebook    | [790a0f2a25](https://linux-hardware.org/?probe=790a0f2a25) | Sep 14, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [0a91582802](https://linux-hardware.org/?probe=0a91582802) | Sep 14, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [b552f0482d](https://linux-hardware.org/?probe=b552f0482d) | Sep 14, 2022 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [8366bd494c](https://linux-hardware.org/?probe=8366bd494c) | Sep 14, 2022 |
| Dell          | Inspiron 14-3467            | Notebook    | [e92b56817a](https://linux-hardware.org/?probe=e92b56817a) | Sep 14, 2022 |
| BESSTAR Te... | HM50                        | Desktop     | [a2632415a2](https://linux-hardware.org/?probe=a2632415a2) | Sep 14, 2022 |
| Dell          | Latitude E7470              | Notebook    | [9d15a7c8a2](https://linux-hardware.org/?probe=9d15a7c8a2) | Sep 14, 2022 |
| HP            | 1495                        | Desktop     | [462389df36](https://linux-hardware.org/?probe=462389df36) | Sep 14, 2022 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [832824de54](https://linux-hardware.org/?probe=832824de54) | Sep 14, 2022 |
| HP            | 1496                        | Desktop     | [cb6033fc21](https://linux-hardware.org/?probe=cb6033fc21) | Sep 14, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [39b26715f0](https://linux-hardware.org/?probe=39b26715f0) | Sep 14, 2022 |
| ASUSTek       | ProArt B550-CREATOR         | Desktop     | [6ee9d3e2c4](https://linux-hardware.org/?probe=6ee9d3e2c4) | Sep 14, 2022 |
| Dell          | Inspiron 5584               | Notebook    | [677d683644](https://linux-hardware.org/?probe=677d683644) | Sep 14, 2022 |
| Timi          | TM1612                      | Notebook    | [536fc04dcb](https://linux-hardware.org/?probe=536fc04dcb) | Sep 14, 2022 |
| Gigabyte      | F2A88X-D3H                  | Desktop     | [06d4572f5e](https://linux-hardware.org/?probe=06d4572f5e) | Sep 14, 2022 |
| ASUSTek       | H81M-A/BR                   | Desktop     | [daab24c8b6](https://linux-hardware.org/?probe=daab24c8b6) | Sep 14, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [331a481ab0](https://linux-hardware.org/?probe=331a481ab0) | Sep 14, 2022 |
| Lenovo        | ThinkPad X230 2324GA1       | Notebook    | [c4e6cc1489](https://linux-hardware.org/?probe=c4e6cc1489) | Sep 14, 2022 |
| Lenovo        | ThinkCentre M71e 3157AE2    | Desktop     | [d88e0026dc](https://linux-hardware.org/?probe=d88e0026dc) | Sep 14, 2022 |
| Toshiba       | Satellite L55-B             | Notebook    | [b593ff9e20](https://linux-hardware.org/?probe=b593ff9e20) | Sep 14, 2022 |
| HP            | Notebook                    | Notebook    | [963af7e07b](https://linux-hardware.org/?probe=963af7e07b) | Sep 13, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [7858c98403](https://linux-hardware.org/?probe=7858c98403) | Sep 13, 2022 |
| Dell          | Latitude 3120               | Convertible | [a8315e1147](https://linux-hardware.org/?probe=a8315e1147) | Sep 13, 2022 |
| Sun Micros... | ASSY,MOTHERBOARD,X4170 5... | Server      | [ea845ec5ea](https://linux-hardware.org/?probe=ea845ec5ea) | Sep 13, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [f06aa45765](https://linux-hardware.org/?probe=f06aa45765) | Sep 13, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [bfd4a6b00a](https://linux-hardware.org/?probe=bfd4a6b00a) | Sep 13, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [e558fd5212](https://linux-hardware.org/?probe=e558fd5212) | Sep 13, 2022 |
| Medion        | E4251 MD61227               | Notebook    | [8b3475f65b](https://linux-hardware.org/?probe=8b3475f65b) | Sep 13, 2022 |
| MSI           | Z97 MPOWER                  | Desktop     | [a98aedda05](https://linux-hardware.org/?probe=a98aedda05) | Sep 13, 2022 |
| Compal        | NCL60/61                    | Notebook    | [f1f5499af8](https://linux-hardware.org/?probe=f1f5499af8) | Sep 12, 2022 |
| ASUSTek       | PRIME H310-PLUS             | Desktop     | [0937dcb89c](https://linux-hardware.org/?probe=0937dcb89c) | Sep 12, 2022 |
| ASRock        | X99 Taichi                  | Desktop     | [2eb979e980](https://linux-hardware.org/?probe=2eb979e980) | Sep 12, 2022 |
| Toshiba       | Satellite C655              | Notebook    | [16a4aa3cd8](https://linux-hardware.org/?probe=16a4aa3cd8) | Sep 12, 2022 |
| Dell          | 0H8052                      | Desktop     | [1ade497706](https://linux-hardware.org/?probe=1ade497706) | Sep 12, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [fbb3c09289](https://linux-hardware.org/?probe=fbb3c09289) | Sep 12, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [fccf3eb345](https://linux-hardware.org/?probe=fccf3eb345) | Sep 12, 2022 |
| Gigabyte      | EX58-UD3R                   | Desktop     | [e482e214bd](https://linux-hardware.org/?probe=e482e214bd) | Sep 12, 2022 |
| Shuttle       | XH310V2                     | Desktop     | [c99efae947](https://linux-hardware.org/?probe=c99efae947) | Sep 12, 2022 |
| MSI           | MAG Z390M MORTAR            | Desktop     | [175f37281b](https://linux-hardware.org/?probe=175f37281b) | Sep 12, 2022 |
| MSI           | GP73 Leopard 8RE            | Notebook    | [21744558cb](https://linux-hardware.org/?probe=21744558cb) | Sep 12, 2022 |
| HP            | 158B                        | Desktop     | [ba2366e9ad](https://linux-hardware.org/?probe=ba2366e9ad) | Sep 12, 2022 |
| HP            | ProBook 440 G1              | Notebook    | [58b48039ce](https://linux-hardware.org/?probe=58b48039ce) | Sep 12, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [73684f0e47](https://linux-hardware.org/?probe=73684f0e47) | Sep 12, 2022 |
| Intel         | D945GCNL AAD97184-106       | Desktop     | [a2bdc2d18c](https://linux-hardware.org/?probe=a2bdc2d18c) | Sep 11, 2022 |
| HP            | 304Bh                       | Desktop     | [0a7bcbdd9e](https://linux-hardware.org/?probe=0a7bcbdd9e) | Sep 11, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [5523f4050c](https://linux-hardware.org/?probe=5523f4050c) | Sep 11, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [b76fc41706](https://linux-hardware.org/?probe=b76fc41706) | Sep 11, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [5d0092ffc1](https://linux-hardware.org/?probe=5d0092ffc1) | Sep 11, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [910cdee832](https://linux-hardware.org/?probe=910cdee832) | Sep 11, 2022 |
| MSI           | B560M PRO                   | Desktop     | [6c43058545](https://linux-hardware.org/?probe=6c43058545) | Sep 11, 2022 |
| HP            | Notebook                    | Notebook    | [2984aef090](https://linux-hardware.org/?probe=2984aef090) | Sep 11, 2022 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | Desktop     | [4db3f9151e](https://linux-hardware.org/?probe=4db3f9151e) | Sep 11, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [0225ec89d7](https://linux-hardware.org/?probe=0225ec89d7) | Sep 11, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [6168b7089f](https://linux-hardware.org/?probe=6168b7089f) | Sep 11, 2022 |
| ASUSTek       | K46CA                       | Notebook    | [9e730cbd6a](https://linux-hardware.org/?probe=9e730cbd6a) | Sep 11, 2022 |
| MSI           | 0A48                        | Desktop     | [2619140b48](https://linux-hardware.org/?probe=2619140b48) | Sep 10, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [eff4400b7d](https://linux-hardware.org/?probe=eff4400b7d) | Sep 10, 2022 |
| Dell          | 01TKCC A01                  | Desktop     | [6d032338c0](https://linux-hardware.org/?probe=6d032338c0) | Sep 10, 2022 |
| Gigabyte      | GB-BRR7H-4800               | Desktop     | [5fb806b2c8](https://linux-hardware.org/?probe=5fb806b2c8) | Sep 10, 2022 |
| Lenovo        | Unknown                     | Notebook    | [b5842ca017](https://linux-hardware.org/?probe=b5842ca017) | Sep 10, 2022 |
| ASUSTek       | P8B75-M LX                  | Desktop     | [0533bc0e86](https://linux-hardware.org/?probe=0533bc0e86) | Sep 10, 2022 |
| HP            | 3396                        | Desktop     | [964f32cccf](https://linux-hardware.org/?probe=964f32cccf) | Sep 10, 2022 |
| Dell          | 03NVJ6 A00                  | Desktop     | [ef8c1a9dee](https://linux-hardware.org/?probe=ef8c1a9dee) | Sep 10, 2022 |
| Samsung       | R530/R730/R540              | Notebook    | [72aea277e6](https://linux-hardware.org/?probe=72aea277e6) | Sep 10, 2022 |
| ASRock        | G41M-VS3                    | Desktop     | [021bcda428](https://linux-hardware.org/?probe=021bcda428) | Sep 10, 2022 |
| Lenovo        | ThinkPad L420 7829H86       | Notebook    | [406535e915](https://linux-hardware.org/?probe=406535e915) | Sep 10, 2022 |
| HP            | Pavilion g6                 | Notebook    | [0774a3c97d](https://linux-hardware.org/?probe=0774a3c97d) | Sep 10, 2022 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [1ac8cbcc47](https://linux-hardware.org/?probe=1ac8cbcc47) | Sep 10, 2022 |
| LG Electro... | U560-G.BG31P1               | Notebook    | [741c3eddbe](https://linux-hardware.org/?probe=741c3eddbe) | Sep 10, 2022 |
| Dell          | 0J3C2F A00                  | Desktop     | [40c43aff10](https://linux-hardware.org/?probe=40c43aff10) | Sep 10, 2022 |
| Samsung       | SX60P                       | Notebook    | [1e0ea8e787](https://linux-hardware.org/?probe=1e0ea8e787) | Sep 09, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [c0353e7c9e](https://linux-hardware.org/?probe=c0353e7c9e) | Sep 09, 2022 |
| Acer          | Aspire E1-572               | Notebook    | [1cfbfd9b91](https://linux-hardware.org/?probe=1cfbfd9b91) | Sep 09, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [cd84312899](https://linux-hardware.org/?probe=cd84312899) | Sep 09, 2022 |
| Dell          | 04075X A00                  | All in one  | [e2ff438b3c](https://linux-hardware.org/?probe=e2ff438b3c) | Sep 09, 2022 |
| Dell          | Precision 7560              | Notebook    | [3e2d1a120c](https://linux-hardware.org/?probe=3e2d1a120c) | Sep 09, 2022 |
| Dell          | Latitude E4300              | Notebook    | [634c1467f8](https://linux-hardware.org/?probe=634c1467f8) | Sep 09, 2022 |
| Dell          | Latitude 3120               | Convertible | [6b2b6b7aa9](https://linux-hardware.org/?probe=6b2b6b7aa9) | Sep 09, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [36b349b529](https://linux-hardware.org/?probe=36b349b529) | Sep 09, 2022 |
| Acer          | Aspire 5738                 | Notebook    | [5c21c2acc6](https://linux-hardware.org/?probe=5c21c2acc6) | Sep 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [628d805267](https://linux-hardware.org/?probe=628d805267) | Sep 09, 2022 |
| Positivo      | H14BT58                     | Notebook    | [669a466b1c](https://linux-hardware.org/?probe=669a466b1c) | Sep 09, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [1a5c8e32b7](https://linux-hardware.org/?probe=1a5c8e32b7) | Sep 09, 2022 |
| Lenovo        | IdeaPad S400 20195          | Notebook    | [6bd3292f42](https://linux-hardware.org/?probe=6bd3292f42) | Sep 08, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [2154b21ff3](https://linux-hardware.org/?probe=2154b21ff3) | Sep 08, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [ee7071f4e7](https://linux-hardware.org/?probe=ee7071f4e7) | Sep 08, 2022 |
| ASUSTek       | K53U                        | Notebook    | [d13ff70895](https://linux-hardware.org/?probe=d13ff70895) | Sep 08, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [e3976254ee](https://linux-hardware.org/?probe=e3976254ee) | Sep 08, 2022 |
| Gigabyte      | A520M DS3H                  | Desktop     | [036c262ad4](https://linux-hardware.org/?probe=036c262ad4) | Sep 08, 2022 |
| Dell          | 0MN1TX A02                  | Desktop     | [c9d50b8db9](https://linux-hardware.org/?probe=c9d50b8db9) | Sep 08, 2022 |
| Dell          | G5 5505                     | Notebook    | [e26e58afac](https://linux-hardware.org/?probe=e26e58afac) | Sep 08, 2022 |
| Intel         | D33217CK G76541-301         | Desktop     | [1f1e6e67ab](https://linux-hardware.org/?probe=1f1e6e67ab) | Sep 07, 2022 |
| Lenovo        | B5400 20278                 | Notebook    | [1c9d752f91](https://linux-hardware.org/?probe=1c9d752f91) | Sep 07, 2022 |
| HP            | Pavilion dv7                | Notebook    | [4a39ae67d5](https://linux-hardware.org/?probe=4a39ae67d5) | Sep 07, 2022 |
| Lenovo        | G580                        | Notebook    | [922ede2a50](https://linux-hardware.org/?probe=922ede2a50) | Sep 07, 2022 |
| ASRock        | Z170 Extreme4               | Desktop     | [70e3d85420](https://linux-hardware.org/?probe=70e3d85420) | Sep 07, 2022 |
| MSI           | IONA                        | Desktop     | [11d081dfc3](https://linux-hardware.org/?probe=11d081dfc3) | Sep 07, 2022 |
| Positivo      | POS-PQ45AU                  | Desktop     | [2770dcd81a](https://linux-hardware.org/?probe=2770dcd81a) | Sep 07, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [22171cc2a6](https://linux-hardware.org/?probe=22171cc2a6) | Sep 07, 2022 |
| Unknown       | GSUO H61V10C                | Desktop     | [4eeb38bb0a](https://linux-hardware.org/?probe=4eeb38bb0a) | Sep 07, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [14f91e3a08](https://linux-hardware.org/?probe=14f91e3a08) | Sep 07, 2022 |
| Samsung       | RC420/RC520/RC720           | Notebook    | [a6b07acfe5](https://linux-hardware.org/?probe=a6b07acfe5) | Sep 07, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [cf398ae303](https://linux-hardware.org/?probe=cf398ae303) | Sep 07, 2022 |
| HP            | ProBook 430 G1              | Notebook    | [cca59cbb3c](https://linux-hardware.org/?probe=cca59cbb3c) | Sep 07, 2022 |
| Positivo      | Mobile                      | Notebook    | [1378222b07](https://linux-hardware.org/?probe=1378222b07) | Sep 07, 2022 |
| ASRock        | J3355B-ITX                  | Desktop     | [1cf7076b74](https://linux-hardware.org/?probe=1cf7076b74) | Sep 07, 2022 |
| Gigabyte      | VM900M                      | Desktop     | [c6eefaabf9](https://linux-hardware.org/?probe=c6eefaabf9) | Sep 07, 2022 |
| LG Electro... | A530-T.BE76P1               | Notebook    | [46161b573f](https://linux-hardware.org/?probe=46161b573f) | Sep 06, 2022 |
| Lenovo        | ThinkPad Edge E531 68856... | Notebook    | [498682ac13](https://linux-hardware.org/?probe=498682ac13) | Sep 06, 2022 |
| MSI           | A320M PRO-M2 V2             | Desktop     | [c211642362](https://linux-hardware.org/?probe=c211642362) | Sep 06, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [01ab1f5015](https://linux-hardware.org/?probe=01ab1f5015) | Sep 06, 2022 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [8a66fbdadd](https://linux-hardware.org/?probe=8a66fbdadd) | Sep 06, 2022 |
| Sony          | VPCSB3X9E                   | Notebook    | [03bd901e4f](https://linux-hardware.org/?probe=03bd901e4f) | Sep 06, 2022 |
| Acer          | TravelMate B118-M           | Notebook    | [614d44ff70](https://linux-hardware.org/?probe=614d44ff70) | Sep 06, 2022 |
| ECS           | GeForce 8000 series         | Desktop     | [7a60cea111](https://linux-hardware.org/?probe=7a60cea111) | Sep 06, 2022 |
| Lenovo        | ThinkPad T420 4236PNP       | Notebook    | [7c3dc0af20](https://linux-hardware.org/?probe=7c3dc0af20) | Sep 06, 2022 |
| Toshiba       | Satellite C75D-B            | Notebook    | [78e0cb1ca2](https://linux-hardware.org/?probe=78e0cb1ca2) | Sep 06, 2022 |
| Acer          | Aspire 5745                 | Notebook    | [39bc7728ac](https://linux-hardware.org/?probe=39bc7728ac) | Sep 06, 2022 |
| Dell          | Latitude E4300              | Notebook    | [4589ef4489](https://linux-hardware.org/?probe=4589ef4489) | Sep 06, 2022 |
| ASRock        | H61M-DGS                    | Desktop     | [51b15f6d34](https://linux-hardware.org/?probe=51b15f6d34) | Sep 06, 2022 |
| Lenovo        | B71-80 80RJ                 | Notebook    | [c16dc3a768](https://linux-hardware.org/?probe=c16dc3a768) | Sep 06, 2022 |
| Lenovo        | ThinkPad L440 20ASS11T00    | Notebook    | [526d97c730](https://linux-hardware.org/?probe=526d97c730) | Sep 06, 2022 |
| ASUSTek       | ET2040I                     | Desktop     | [44ab433428](https://linux-hardware.org/?probe=44ab433428) | Sep 06, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [537708f71a](https://linux-hardware.org/?probe=537708f71a) | Sep 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [5d61bcd114](https://linux-hardware.org/?probe=5d61bcd114) | Sep 06, 2022 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [6f848cd309](https://linux-hardware.org/?probe=6f848cd309) | Sep 06, 2022 |
| Dell          | Vostro 14-5480              | Notebook    | [fb3ae25db8](https://linux-hardware.org/?probe=fb3ae25db8) | Sep 06, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [5263a99ed8](https://linux-hardware.org/?probe=5263a99ed8) | Sep 05, 2022 |
| HP            | 18E4                        | Desktop     | [2c113164fd](https://linux-hardware.org/?probe=2c113164fd) | Sep 05, 2022 |
| Pegatron      | NARRA5                      | Desktop     | [b5e07ae97b](https://linux-hardware.org/?probe=b5e07ae97b) | Sep 05, 2022 |
| MSI           | B85M-E43 DASH               | Desktop     | [f52a53f4a7](https://linux-hardware.org/?probe=f52a53f4a7) | Sep 05, 2022 |
| Unknown       | SKYBAY                      | Desktop     | [6098d39f63](https://linux-hardware.org/?probe=6098d39f63) | Sep 05, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/OpenMandriva/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| OpenMandriva 4.2    | 4565      | 47.67%  |
| OpenMandriva 4.3    | 3890      | 40.62%  |
| OpenMandriva 4.50   | 778       | 8.12%   |
| OpenMandriva 4.90   | 316       | 3.3%    |
| OpenMandriva 4.1    | 14        | 0.15%   |
| OpenMandriva 22.11  | 4         | 0.04%   |
| OpenMandriva 2014.0 | 4         | 0.04%   |
| OpenMandriva 4.0    | 2         | 0.02%   |
| OpenMandriva 3.0    | 2         | 0.02%   |
| OpenMandriva 4.0.1  | 1         | 0.01%   |
| OpenMandriva 22.90  | 1         | 0.01%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| OpenMandriva | 9551      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                        | Computers | Percent |
|--------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002       | 4396      | 45.64%  |
| 5.16.7-desktop-1omv4003        | 3754      | 38.98%  |
| 5.12.4-desktop-1omv4050        | 367       | 3.81%   |
| 5.18.12-desktop-3omv4090       | 279       | 2.9%    |
| 5.11.12-desktop-1omv4002       | 188       | 1.95%   |
| 5.19.5-desktop-1omv4090        | 139       | 1.44%   |
| 5.16.13-desktop-1omv4003       | 108       | 1.12%   |
| 5.14.7-desktop-1omv4050        | 103       | 1.07%   |
| 5.19.12-desktop-2omv4090       | 74        | 0.77%   |
| 5.14.14-desktop-1omv4050       | 24        | 0.25%   |
| 5.12.7-desktop-1omv4003        | 22        | 0.23%   |
| 5.17.1-desktop-2omv4050        | 17        | 0.18%   |
| 5.5.12-desktop-1omv4001        | 12        | 0.12%   |
| 5.19.11-desktop-2omv4090       | 10        | 0.1%    |
| 5.11.0-desktop-clang-1omv4002  | 10        | 0.1%    |
| 5.19.1-desktop-1omv4090        | 6         | 0.06%   |
| 5.16.3-desktop-2omv4050        | 6         | 0.06%   |
| 5.18.13-desktop-1omv4090       | 5         | 0.05%   |
| 5.10.13-desktop-1omv4002       | 5         | 0.05%   |
| 6.0.2-desktop-1omv4090         | 4         | 0.04%   |
| 6.0.2-desktop-1omv4050         | 4         | 0.04%   |
| 5.18.9-desktop-gcc-1omv4090    | 4         | 0.04%   |
| 6.0.9-desktop-1omv22090        | 3         | 0.03%   |
| 5.19.0-desktop-1omv4090        | 3         | 0.03%   |
| 5.16.9-desktop-1omv4003        | 3         | 0.03%   |
| 5.16.5-desktop-2omv4003        | 3         | 0.03%   |
| 5.12.7-desktop-clang-1omv4003  | 3         | 0.03%   |
| 5.9.12-desktop-1omv4002        | 2         | 0.02%   |
| 5.5.0-desktop-1omv4001         | 2         | 0.02%   |
| 5.19.8-desktop-2omv4090        | 2         | 0.02%   |
| 5.19.3-desktop-1omv4090        | 2         | 0.02%   |
| 5.17.7-desktop-1omv4090        | 2         | 0.02%   |
| 5.17.1-desktop-clang-2omv4050  | 2         | 0.02%   |
| 5.16.0-desktop-1omv4050        | 2         | 0.02%   |
| 5.13.2-desktop-clang-1omv4050  | 2         | 0.02%   |
| 5.11.13-desktop-clang-1omv4050 | 2         | 0.02%   |
| 5.11.11-desktop-clang-1omv4050 | 2         | 0.02%   |
| 4.1.12-nrj-server-1omv         | 2         | 0.02%   |
| 6.0.9-desktop-gcc-1omv22090    | 1         | 0.01%   |
| 6.0.9-desktop-2.0omv4.3mjn     | 1         | 0.01%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.14 | 4396      | 45.64%  |
| 5.16.7  | 3756      | 39%     |
| 5.12.4  | 367       | 3.81%   |
| 5.18.12 | 279       | 2.9%    |
| 5.11.12 | 188       | 1.95%   |
| 5.19.5  | 139       | 1.44%   |
| 5.16.13 | 109       | 1.13%   |
| 5.14.7  | 103       | 1.07%   |
| 5.19.12 | 75        | 0.78%   |
| 5.12.7  | 25        | 0.26%   |
| 5.14.14 | 24        | 0.25%   |
| 5.17.1  | 19        | 0.2%    |
| 5.5.12  | 12        | 0.12%   |
| 5.11.0  | 12        | 0.12%   |
| 5.19.11 | 11        | 0.11%   |
| 6.0.2   | 8         | 0.08%   |
| 5.19.1  | 6         | 0.06%   |
| 5.16.3  | 6         | 0.06%   |
| 6.0.9   | 5         | 0.05%   |
| 5.18.13 | 5         | 0.05%   |
| 5.10.13 | 5         | 0.05%   |
| 6.0.0   | 4         | 0.04%   |
| 5.18.9  | 4         | 0.04%   |
| 5.16.9  | 4         | 0.04%   |
| 5.16.5  | 4         | 0.04%   |
| 5.13.2  | 4         | 0.04%   |
| 5.19.0  | 3         | 0.03%   |
| 5.11.11 | 3         | 0.03%   |
| 5.9.12  | 2         | 0.02%   |
| 5.8.13  | 2         | 0.02%   |
| 5.5.0   | 2         | 0.02%   |
| 5.19.8  | 2         | 0.02%   |
| 5.19.3  | 2         | 0.02%   |
| 5.18.11 | 2         | 0.02%   |
| 5.17.7  | 2         | 0.02%   |
| 5.16.0  | 2         | 0.02%   |
| 5.12.12 | 2         | 0.02%   |
| 5.12.1  | 2         | 0.02%   |
| 5.11.13 | 2         | 0.02%   |
| 4.1.15  | 2         | 0.02%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 4407      | 45.78%  |
| 5.16    | 3882      | 40.32%  |
| 5.12    | 397       | 4.12%   |
| 5.18    | 291       | 3.02%   |
| 5.19    | 239       | 2.48%   |
| 5.11    | 208       | 2.16%   |
| 5.14    | 128       | 1.33%   |
| 5.17    | 21        | 0.22%   |
| 6.0     | 18        | 0.19%   |
| 5.5     | 14        | 0.15%   |
| 5.13    | 5         | 0.05%   |
| 4.1     | 4         | 0.04%   |
| 5.15    | 3         | 0.03%   |
| 5.9     | 2         | 0.02%   |
| 5.8     | 2         | 0.02%   |
| 5.1     | 2         | 0.02%   |
| 4.19    | 2         | 0.02%   |
| 5.3     | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 9549      | 99.98%  |
| aarch64 | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| KDE5     | 9505      | 99.48%  |
| Unknown  | 18        | 0.19%   |
| LXQt     | 14        | 0.15%   |
| GNOME    | 10        | 0.1%    |
| KDE4     | 2         | 0.02%   |
| KDE      | 2         | 0.02%   |
| Cinnamon | 2         | 0.02%   |
| XFCE     | 1         | 0.01%   |
| Budgie   | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 9489      | 99.33%  |
| Wayland | 61        | 0.64%   |
| Unknown | 2         | 0.02%   |
| Tty     | 1         | 0.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 9535      | 99.82%  |
| GDM     | 8         | 0.08%   |
| Unknown | 5         | 0.05%   |
| LightDM | 2         | 0.02%   |
| KDM     | 2         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 5228      | 54.57%  |
| de_DE   | 776       | 8.1%    |
| ru_RU   | 532       | 5.55%   |
| fr_FR   | 518       | 5.41%   |
| pt_BR   | 392       | 4.09%   |
| pl_PL   | 349       | 3.64%   |
| it_IT   | 253       | 2.64%   |
| es_ES   | 219       | 2.29%   |
| cs_CZ   | 191       | 1.99%   |
| en_GB   | 181       | 1.89%   |
| es_AR   | 83        | 0.87%   |
| es_MX   | 75        | 0.78%   |
| de_AT   | 71        | 0.74%   |
| hu_HU   | 68        | 0.71%   |
| nl_NL   | 40        | 0.42%   |
| en_AU   | 39        | 0.41%   |
| fr_CA   | 35        | 0.37%   |
| en_IN   | 34        | 0.35%   |
| en_CA   | 33        | 0.34%   |
| es_CO   | 31        | 0.32%   |
| fr_BE   | 30        | 0.31%   |
| de_CH   | 29        | 0.3%    |
| pt_PT   | 28        | 0.29%   |
| ru_UA   | 26        | 0.27%   |
| tr_TR   | 24        | 0.25%   |
| es_CL   | 24        | 0.25%   |
| Unknown | 23        | 0.24%   |
| da_DK   | 22        | 0.23%   |
| nl_BE   | 19        | 0.2%    |
| ro_RO   | 18        | 0.19%   |
| es_VE   | 17        | 0.18%   |
| es_PE   | 15        | 0.16%   |
| fr_CH   | 12        | 0.13%   |
| nb_NO   | 11        | 0.11%   |
| uk_UA   | 9         | 0.09%   |
| es_UY   | 9         | 0.09%   |
| en_ZA   | 9         | 0.09%   |
| en_HK   | 9         | 0.09%   |
| es_CR   | 8         | 0.08%   |
| it_CH   | 7         | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 5148      | 53.87%  |
| EFI  | 4409      | 46.13%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Overlay  | 7788      | 81.01%  |
| Ext4     | 1729      | 17.98%  |
| Btrfs    | 42        | 0.44%   |
| F2fs     | 18        | 0.19%   |
| Xfs      | 11        | 0.11%   |
| Unknown  | 8         | 0.08%   |
| Ext2     | 7         | 0.07%   |
| Ext3     | 6         | 0.06%   |
| Jfs      | 3         | 0.03%   |
| Reiserfs | 2         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 5888      | 61.53%  |
| MBR     | 3652      | 38.16%  |
| Unknown | 30        | 0.31%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5427      | 56.63%  |
| No        | 4156      | 43.37%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4924      | 51.5%   |
| Yes       | 4638      | 48.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 1704      | 17.84%  |
| Hewlett-Packard     | 1232      | 12.9%   |
| Dell                | 1149      | 12.03%  |
| Lenovo              | 1087      | 11.38%  |
| Gigabyte Technology | 836       | 8.75%   |
| Acer                | 622       | 6.51%   |
| MSI                 | 560       | 5.86%   |
| ASRock              | 434       | 4.54%   |
| Toshiba             | 230       | 2.41%   |
| Intel               | 190       | 1.99%   |
| Apple               | 131       | 1.37%   |
| Sony                | 125       | 1.31%   |
| Fujitsu             | 121       | 1.27%   |
| Samsung Electronics | 107       | 1.12%   |
| Medion              | 88        | 0.92%   |
| Biostar             | 59        | 0.62%   |
| Positivo            | 57        | 0.6%    |
| Foxconn             | 57        | 0.6%    |
| Pegatron            | 56        | 0.59%   |
| Packard Bell        | 54        | 0.57%   |
| Unknown             | 54        | 0.57%   |
| ECS                 | 35        | 0.37%   |
| HUAWEI              | 24        | 0.25%   |
| Fujitsu Siemens     | 24        | 0.25%   |
| eMachines           | 23        | 0.24%   |
| Philco              | 22        | 0.23%   |
| Notebook            | 20        | 0.21%   |
| TUXEDO              | 18        | 0.19%   |
| Chuwi               | 17        | 0.18%   |
| BESSTAR Tech        | 17        | 0.18%   |
| LG Electronics      | 16        | 0.17%   |
| Gateway             | 16        | 0.17%   |
| Alienware           | 15        | 0.16%   |
| Supermicro          | 14        | 0.15%   |
| AZW                 | 14        | 0.15%   |
| Shuttle             | 13        | 0.14%   |
| Microsoft           | 13        | 0.14%   |
| PCWare              | 11        | 0.12%   |
| Compaq              | 9         | 0.09%   |
| ZOTAC               | 8         | 0.08%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| ASUS UX31E                  | 103       | 1.08%   |
| ASUS All Series             | 97        | 1.02%   |
| Unknown                     | 86        | 0.9%    |
| Dell Latitude 3120          | 48        | 0.5%    |
| HP Notebook                 | 47        | 0.49%   |
| Dell OptiPlex 780           | 34        | 0.36%   |
| Dell Latitude 3190 2-in-1   | 34        | 0.36%   |
| Dell OptiPlex 7010          | 31        | 0.32%   |
| Dell Inspiron 3451          | 31        | 0.32%   |
| Dell Latitude 3310          | 29        | 0.3%    |
| Gigabyte H410M H V3         | 27        | 0.28%   |
| HP Pavilion g6              | 23        | 0.24%   |
| HP Pavilion dv6             | 21        | 0.22%   |
| Gigabyte 970A-DS3P          | 21        | 0.22%   |
| ASUS SABERTOOTH Z77         | 20        | 0.21%   |
| ASUS PRIME A320M-K          | 20        | 0.21%   |
| Sony VGN-FZ31Z              | 19        | 0.2%    |
| Dell Latitude E6430         | 19        | 0.2%    |
| Intel H61                   | 18        | 0.19%   |
| Dell OptiPlex 9020          | 18        | 0.19%   |
| MSI MS-7C37                 | 17        | 0.18%   |
| HP EliteDesk 800 G1 SFF     | 17        | 0.18%   |
| HP Compaq Pro 6300 SFF      | 17        | 0.18%   |
| Gigabyte B450M DS3H         | 17        | 0.18%   |
| MSI MS-7817                 | 16        | 0.17%   |
| MSI MS-7721                 | 16        | 0.17%   |
| HP Pavilion 15              | 16        | 0.17%   |
| Gigabyte A320M-S2H          | 16        | 0.17%   |
| Dell OptiPlex 790           | 16        | 0.17%   |
| Dell OptiPlex 3020          | 16        | 0.17%   |
| Dell Latitude E6410         | 15        | 0.16%   |
| ASUS M5A78L-M/USB3          | 15        | 0.16%   |
| Medion E2292                | 14        | 0.15%   |
| HP Compaq 8200 Elite SFF PC | 14        | 0.15%   |
| Dell Latitude D630          | 14        | 0.15%   |
| ASUS TUF Gaming X570-PLUS   | 14        | 0.15%   |
| ASUS PRIME B450M-A          | 14        | 0.15%   |
| Dell Latitude E6420         | 13        | 0.14%   |
| ASUS PRIME B450M-A II       | 13        | 0.14%   |
| Positivo Mobile             | 12        | 0.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 443       | 4.64%   |
| Dell Latitude         | 432       | 4.52%   |
| Lenovo ThinkPad       | 342       | 3.58%   |
| Lenovo IdeaPad        | 276       | 2.89%   |
| Dell OptiPlex         | 250       | 2.62%   |
| Dell Inspiron         | 240       | 2.51%   |
| HP Pavilion           | 212       | 2.22%   |
| HP Compaq             | 208       | 2.18%   |
| ASUS PRIME            | 187       | 1.96%   |
| Toshiba Satellite     | 180       | 1.88%   |
| HP Laptop             | 124       | 1.3%    |
| Lenovo ThinkCentre    | 116       | 1.21%   |
| ASUS UX31E            | 103       | 1.08%   |
| ASUS All              | 97        | 1.02%   |
| HP ProBook            | 96        | 1.01%   |
| HP EliteBook          | 90        | 0.94%   |
| ASUS VivoBook         | 88        | 0.92%   |
| ASUS ROG              | 87        | 0.91%   |
| Unknown               | 86        | 0.9%    |
| ASUS TUF              | 68        | 0.71%   |
| Dell Vostro           | 61        | 0.64%   |
| HP EliteDesk          | 60        | 0.63%   |
| Dell Precision        | 58        | 0.61%   |
| Fujitsu LIFEBOOK      | 50        | 0.52%   |
| Fujitsu ESPRIMO       | 50        | 0.52%   |
| ASUS M5A78L-M         | 49        | 0.51%   |
| Lenovo IdeaCentre     | 48        | 0.5%    |
| HP ProDesk            | 47        | 0.49%   |
| HP Notebook           | 47        | 0.49%   |
| Dell XPS              | 46        | 0.48%   |
| Packard Bell EasyNote | 36        | 0.38%   |
| ASUS SABERTOOTH       | 36        | 0.38%   |
| Gigabyte B450M        | 34        | 0.36%   |
| Gigabyte H410M        | 32        | 0.34%   |
| Acer TravelMate       | 32        | 0.34%   |
| Gigabyte B450         | 30        | 0.31%   |
| ASUS P8H61-M          | 30        | 0.31%   |
| Acer Extensa          | 30        | 0.31%   |
| Gigabyte X570         | 28        | 0.29%   |
| HP ENVY               | 25        | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 984       | 10.3%   |
| 2012    | 976       | 10.22%  |
| 2013    | 784       | 8.21%   |
| 2019    | 719       | 7.53%   |
| 2014    | 689       | 7.21%   |
| 2010    | 671       | 7.03%   |
| 2018    | 669       | 7%      |
| 2020    | 606       | 6.34%   |
| 2017    | 516       | 5.4%    |
| 2008    | 511       | 5.35%   |
| 2009    | 505       | 5.29%   |
| 2016    | 486       | 5.09%   |
| 2015    | 481       | 5.04%   |
| 2021    | 430       | 4.5%    |
| 2007    | 319       | 3.34%   |
| 2006    | 127       | 1.33%   |
| 2022    | 45        | 0.47%   |
| 2005    | 21        | 0.22%   |
| 2004    | 6         | 0.06%   |
| Unknown | 6         | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 4531      | 47.44%  |
| Notebook       | 4524      | 47.37%  |
| Convertible    | 173       | 1.81%   |
| All in one     | 151       | 1.58%   |
| Mini pc        | 123       | 1.29%   |
| Tablet         | 27        | 0.28%   |
| Server         | 21        | 0.22%   |
| System on chip | 1         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 9551      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 9541      | 99.9%   |
| Yes  | 10        | 0.1%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 2782      | 29.1%   |
| 4.01-8.0        | 2513      | 26.28%  |
| 8.01-16.0       | 1741      | 18.21%  |
| 16.01-24.0      | 1337      | 13.98%  |
| 32.01-64.0      | 480       | 5.02%   |
| 1.01-2.0        | 363       | 3.8%    |
| 2.01-3.0        | 135       | 1.41%   |
| 24.01-32.0      | 98        | 1.02%   |
| 64.01-256.0     | 87        | 0.91%   |
| 0.51-1.0        | 19        | 0.2%    |
| More than 256.0 | 5         | 0.05%   |
| Unknown         | 1         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 7336      | 76.42%  |
| 0.51-1.0   | 1309      | 13.64%  |
| 2.01-3.0   | 657       | 6.84%   |
| 0.01-0.5   | 187       | 1.95%   |
| 3.01-4.0   | 64        | 0.67%   |
| 4.01-8.0   | 31        | 0.32%   |
| 8.01-16.0  | 13        | 0.14%   |
| 16.01-24.0 | 1         | 0.01%   |
| Unknown    | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 5735      | 59.98%  |
| 2      | 2273      | 23.77%  |
| 3      | 768       | 8.03%   |
| 4      | 367       | 3.84%   |
| 0      | 165       | 1.73%   |
| 5      | 141       | 1.47%   |
| 6      | 55        | 0.58%   |
| 7      | 25        | 0.26%   |
| 8      | 17        | 0.18%   |
| 9      | 6         | 0.06%   |
| 12     | 4         | 0.04%   |
| 15     | 2         | 0.02%   |
| 11     | 2         | 0.02%   |
| 18     | 1         | 0.01%   |
| 10     | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5296      | 55.41%  |
| No        | 4261      | 44.59%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 8796      | 92.1%   |
| No        | 755       | 7.9%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 6442      | 67.44%  |
| No        | 3110      | 32.56%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 5013      | 52.48%  |
| Yes       | 4539      | 47.52%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| Germany      | 1129      | 11.82%  |
| USA          | 1081      | 11.32%  |
| Russia       | 689       | 7.21%   |
| France       | 675       | 7.07%   |
| Brazil       | 653       | 6.84%   |
| Poland       | 538       | 5.63%   |
| Italy        | 420       | 4.4%    |
| Spain        | 317       | 3.32%   |
| UK           | 298       | 3.12%   |
| Netherlands  | 257       | 2.69%   |
| Canada       | 247       | 2.59%   |
| Czechia      | 233       | 2.44%   |
| Mexico       | 164       | 1.72%   |
| Australia    | 145       | 1.52%   |
| India        | 143       | 1.5%    |
| Ukraine      | 122       | 1.28%   |
| Argentina    | 112       | 1.17%   |
| Japan        | 111       | 1.16%   |
| Austria      | 107       | 1.12%   |
| Hungary      | 106       | 1.11%   |
| Portugal     | 96        | 1.01%   |
| Romania      | 92        | 0.96%   |
| Belgium      | 88        | 0.92%   |
| Indonesia    | 86        | 0.9%    |
| Sweden       | 85        | 0.89%   |
| Switzerland  | 79        | 0.83%   |
| Greece       | 66        | 0.69%   |
| Turkey       | 60        | 0.63%   |
| Finland      | 59        | 0.62%   |
| Slovakia     | 56        | 0.59%   |
| Bulgaria     | 53        | 0.55%   |
| Serbia       | 51        | 0.53%   |
| Colombia     | 50        | 0.52%   |
| China        | 49        | 0.51%   |
| Norway       | 41        | 0.43%   |
| Chile        | 41        | 0.43%   |
| Denmark      | 36        | 0.38%   |
| Belarus      | 36        | 0.38%   |
| Peru         | 35        | 0.37%   |
| South Africa | 34        | 0.36%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Schagen        | 137       | 1.43%   |
| Moscow         | 130       | 1.36%   |
| Prague         | 120       | 1.25%   |
| Paris          | 80        | 0.83%   |
| Warsaw         | 79        | 0.82%   |
| Sao Paulo      | 74        | 0.77%   |
| Berlin         | 71        | 0.74%   |
| St Petersburg  | 60        | 0.63%   |
| Milan          | 55        | 0.57%   |
| Vienna         | 53        | 0.55%   |
| Krakow         | 50        | 0.52%   |
| Munich         | 48        | 0.5%    |
| Mexico City    | 47        | 0.49%   |
| Rome           | 43        | 0.45%   |
| Rio de Janeiro | 43        | 0.45%   |
| Hamburg        | 35        | 0.37%   |
| Sydney         | 33        | 0.34%   |
| Madrid         | 32        | 0.33%   |
| Helsinki       | 30        | 0.31%   |
| Yekaterinburg  | 27        | 0.28%   |
| Buenos Aires   | 26        | 0.27%   |
| Athens         | 26        | 0.27%   |
| Wroclaw        | 25        | 0.26%   |
| Belgrade       | 25        | 0.26%   |
| Stuttgart      | 24        | 0.25%   |
| Porto Alegre   | 24        | 0.25%   |
| Melbourne      | 24        | 0.25%   |
| Lima           | 24        | 0.25%   |
| Istanbul       | 24        | 0.25%   |
| Budapest       | 24        | 0.25%   |
| Barcelona      | 24        | 0.25%   |
| Montreal       | 23        | 0.24%   |
| Kyiv           | 23        | 0.24%   |
| Krasnodar      | 23        | 0.24%   |
| Jakarta        | 22        | 0.23%   |
| Gonikoppal     | 22        | 0.23%   |
| Dortmund       | 21        | 0.22%   |
| Brisbane       | 21        | 0.22%   |
| Poznan         | 20        | 0.21%   |
| Nuremberg      | 20        | 0.21%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2538      | 3046   | 18.72%  |
| Seagate             | 2299      | 2716   | 16.96%  |
| Samsung Electronics | 1649      | 2002   | 12.16%  |
| Toshiba             | 980       | 1050   | 7.23%   |
| Kingston            | 807       | 870    | 5.95%   |
| SanDisk             | 592       | 639    | 4.37%   |
| Hitachi             | 571       | 599    | 4.21%   |
| Crucial             | 558       | 643    | 4.12%   |
| Unknown             | 360       | 395    | 2.66%   |
| A-DATA Technology   | 291       | 311    | 2.15%   |
| HGST                | 224       | 244    | 1.65%   |
| SK hynix            | 217       | 223    | 1.6%    |
| Intel               | 184       | 204    | 1.36%   |
| China               | 148       | 159    | 1.09%   |
| GOODRAM             | 96        | 105    | 0.71%   |
| PNY                 | 94        | 103    | 0.69%   |
| Micron Technology   | 91        | 93     | 0.67%   |
| Intenso             | 91        | 96     | 0.67%   |
| SPCC                | 81        | 84     | 0.6%    |
| Maxtor              | 80        | 90     | 0.59%   |
| Patriot             | 79        | 84     | 0.58%   |
| Fujitsu             | 63        | 63     | 0.46%   |
| OCZ                 | 60        | 61     | 0.44%   |
| Apacer              | 60        | 64     | 0.44%   |
| JMicron Technology  | 59        | 60     | 0.44%   |
| Transcend           | 58        | 60     | 0.43%   |
| Phison              | 57        | 68     | 0.42%   |
| Apple               | 56        | 61     | 0.41%   |
| Unknown             | 55        | 57     | 0.41%   |
| LITEON              | 53        | 53     | 0.39%   |
| Corsair             | 49        | 51     | 0.36%   |
| KIOXIA              | 42        | 44     | 0.31%   |
| ASMT                | 41        | 44     | 0.3%    |
| Gigabyte Technology | 40        | 42     | 0.3%    |
| Hewlett-Packard     | 39        | 44     | 0.29%   |
| Netac               | 34        | 35     | 0.25%   |
| KingSpec            | 32        | 32     | 0.24%   |
| Silicon Motion      | 30        | 33     | 0.22%   |
| Team                | 29        | 31     | 0.21%   |
| Plextor             | 26        | 28     | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD     | 168       | 1.14%   |
| Seagate ST500DM002-1BD142 500GB     | 155       | 1.05%   |
| Seagate ST1000DM010-2EP102 1TB      | 122       | 0.82%   |
| Seagate ST500LT012-1DG142 500GB     | 113       | 0.76%   |
| SanDisk SSD U100 256GB              | 103       | 0.7%    |
| Samsung SSD 860 EVO 500GB           | 100       | 0.68%   |
| Kingston SA400S37120G 120GB SSD     | 99        | 0.67%   |
| Toshiba MQ01ABF050 500GB            | 93        | 0.63%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 93        | 0.63%   |
| Toshiba DT01ACA100 1TB              | 86        | 0.58%   |
| Kingston SV300S37A120G 120GB SSD    | 86        | 0.58%   |
| Unknown SD/MMC/MS PRO 8GB           | 85        | 0.57%   |
| Kingston SA400S37480G 480GB SSD     | 84        | 0.57%   |
| Toshiba MQ01ABD100 1TB              | 83        | 0.56%   |
| Seagate ST1000LM035-1RK172 1TB      | 83        | 0.56%   |
| WDC WD10EZEX-08WN4A0 1TB            | 80        | 0.54%   |
| Samsung SSD 850 EVO 250GB           | 78        | 0.53%   |
| Crucial CT240BX500SSD1 240GB        | 78        | 0.53%   |
| Seagate ST2000DM008-2FR102 2TB      | 74        | 0.5%    |
| Crucial CT500MX500SSD1 500GB        | 74        | 0.5%    |
| Samsung SSD 860 EVO 250GB           | 73        | 0.49%   |
| Toshiba DT01ACA050 500GB            | 68        | 0.46%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 63        | 0.43%   |
| Seagate ST3500418AS 500GB           | 61        | 0.41%   |
| Samsung SSD 850 EVO 500GB           | 61        | 0.41%   |
| Seagate ST1000DM003-1ER162 1TB      | 60        | 0.41%   |
| Toshiba MQ04ABF100 1TB              | 56        | 0.38%   |
| Seagate ST9500325AS 500GB           | 56        | 0.38%   |
| Crucial CT1000MX500SSD1 1TB         | 55        | 0.37%   |
| Unknown                             | 55        | 0.37%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 53        | 0.36%   |
| HGST HTS721010A9E630 1TB            | 50        | 0.34%   |
| Toshiba HDWD110 1TB                 | 49        | 0.33%   |
| Samsung SSD 970 EVO Plus 500GB      | 49        | 0.33%   |
| Crucial CT480BX500SSD1 480GB        | 49        | 0.33%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 47        | 0.32%   |
| Seagate ST3500413AS 500GB           | 43        | 0.29%   |
| Seagate ST1000DM003-1SB102 1TB      | 43        | 0.29%   |
| Seagate ST1000DM003-1CH162 1TB      | 42        | 0.28%   |
| Seagate Expansion 1TB               | 42        | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2270      | 2673   | 33.42%  |
| WDC                 | 2106      | 2478   | 31%     |
| Toshiba             | 867       | 926    | 12.76%  |
| Hitachi             | 571       | 599    | 8.41%   |
| Samsung Electronics | 385       | 427    | 5.67%   |
| HGST                | 224       | 244    | 3.3%    |
| Unknown             | 88        | 88     | 1.3%    |
| Maxtor              | 77        | 87     | 1.13%   |
| Fujitsu             | 62        | 62     | 0.91%   |
| Apple               | 29        | 29     | 0.43%   |
| ASMT                | 25        | 28     | 0.37%   |
| WD MediaMax         | 8         | 9      | 0.12%   |
| Hewlett-Packard     | 8         | 8      | 0.12%   |
| ASMedia             | 7         | 7      | 0.1%    |
| Intenso             | 6         | 6      | 0.09%   |
| IBM/Hitachi         | 6         | 6      | 0.09%   |
| Quantum             | 4         | 4      | 0.06%   |
| HPE                 | 4         | 4      | 0.06%   |
| USB                 | 3         | 3      | 0.04%   |
| SAGE                | 3         | 3      | 0.04%   |
| SABRENT             | 3         | 4      | 0.04%   |
| Magnetic Data       | 3         | 3      | 0.04%   |
| JMicron Technology  | 3         | 3      | 0.04%   |
| ExcelStor           | 3         | 3      | 0.04%   |
| China               | 3         | 3      | 0.04%   |
| MDT                 | 2         | 2      | 0.03%   |
| KESU                | 2         | 2      | 0.03%   |
| Inateck             | 2         | 2      | 0.03%   |
| HGST HTS            | 2         | 2      | 0.03%   |
| Unknown             | 2         | 2      | 0.03%   |
| USB 3.0             | 1         | 2      | 0.01%   |
| TPH00800640GB       | 1         | 1      | 0.01%   |
| StoreJet            | 1         | 1      | 0.01%   |
| RSH-339             | 1         | 1      | 0.01%   |
| RSH-319             | 1         | 1      | 0.01%   |
| QC-FT-D             | 1         | 1      | 0.01%   |
| Promise             | 1         | 1      | 0.01%   |
| MARVELL             | 1         | 1      | 0.01%   |
| LaCie               | 1         | 1      | 0.01%   |
| Initio              | 1         | 1      | 0.01%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 903       | 1044   | 18.25%  |
| Kingston            | 692       | 742    | 13.99%  |
| SanDisk             | 545       | 584    | 11.01%  |
| Crucial             | 485       | 555    | 9.8%    |
| WDC                 | 302       | 321    | 6.1%    |
| A-DATA Technology   | 240       | 252    | 4.85%   |
| China               | 145       | 156    | 2.93%   |
| GOODRAM             | 93        | 100    | 1.88%   |
| Intel               | 86        | 91     | 1.74%   |
| PNY                 | 84        | 91     | 1.7%    |
| Toshiba             | 81        | 84     | 1.64%   |
| Intenso             | 81        | 86     | 1.64%   |
| SK hynix            | 72        | 74     | 1.46%   |
| Patriot             | 72        | 77     | 1.46%   |
| Micron Technology   | 67        | 69     | 1.35%   |
| SPCC                | 64        | 66     | 1.29%   |
| OCZ                 | 60        | 61     | 1.21%   |
| Apacer              | 55        | 58     | 1.11%   |
| Transcend           | 51        | 52     | 1.03%   |
| LITEON              | 48        | 48     | 0.97%   |
| JMicron Technology  | 39        | 40     | 0.79%   |
| Unknown             | 33        | 33     | 0.67%   |
| KingSpec            | 32        | 32     | 0.65%   |
| Netac               | 31        | 32     | 0.63%   |
| Corsair             | 28        | 29     | 0.57%   |
| Team                | 27        | 28     | 0.55%   |
| Unknown             | 26        | 27     | 0.53%   |
| LITEONIT            | 23        | 24     | 0.46%   |
| Hewlett-Packard     | 23        | 25     | 0.46%   |
| Gigabyte Technology | 22        | 22     | 0.44%   |
| Apple               | 22        | 22     | 0.44%   |
| Plextor             | 21        | 23     | 0.42%   |
| KingDian            | 16        | 17     | 0.32%   |
| Seagate             | 13        | 13     | 0.26%   |
| KingFast            | 13        | 14     | 0.26%   |
| ASMT                | 13        | 13     | 0.26%   |
| Lexar               | 12        | 12     | 0.24%   |
| Leven               | 11        | 11     | 0.22%   |
| KIOXIA-EXCERIA      | 11        | 11     | 0.22%   |
| Colorful            | 11        | 11     | 0.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 5777      | 7734   | 48.24%  |
| SSD     | 4262      | 5349   | 35.59%  |
| NVMe    | 1539      | 1822   | 12.85%  |
| MMC     | 279       | 302    | 2.33%   |
| Unknown | 119       | 144    | 0.99%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 8405      | 12585  | 78.05%  |
| NVMe | 1516      | 1784   | 14.08%  |
| SAS  | 569       | 680    | 5.28%   |
| MMC  | 279       | 302    | 2.59%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 6698      | 8634   | 64.5%   |
| 0.51-1.0   | 2672      | 3214   | 25.73%  |
| 1.01-2.0   | 627       | 750    | 6.04%   |
| 2.01-3.0   | 137       | 165    | 1.32%   |
| 3.01-4.0   | 127       | 169    | 1.22%   |
| 4.01-10.0  | 103       | 131    | 0.99%   |
| 10.01-20.0 | 20        | 20     | 0.19%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 5158      | 53.65%  |
| 101-250        | 1282      | 13.33%  |
| Unknown        | 1008      | 10.48%  |
| 251-500        | 850       | 8.84%   |
| 501-1000       | 423       | 4.4%    |
| 51-100         | 382       | 3.97%   |
| 21-50          | 327       | 3.4%    |
| 1001-2000      | 122       | 1.27%   |
| 2001-3000      | 35        | 0.36%   |
| More than 3000 | 28        | 0.29%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 7831      | 81.55%  |
| Unknown        | 1008      | 10.5%   |
| 21-50          | 198       | 2.06%   |
| 101-250        | 185       | 1.93%   |
| 51-100         | 152       | 1.58%   |
| 251-500        | 111       | 1.16%   |
| 501-1000       | 69        | 0.72%   |
| 1001-2000      | 33        | 0.34%   |
| More than 3000 | 9         | 0.09%   |
| 2001-3000      | 6         | 0.06%   |
| 0              | 1         | 0.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| SanDisk SSD U100 256GB              | 103       | 103    | 3.5%    |
| Seagate ST500DM002-1BD142 500GB     | 64        | 66     | 2.18%   |
| Seagate ST9500325AS 500GB           | 42        | 44     | 1.43%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 35        | 36     | 1.19%   |
| Seagate ST500LT012-1DG142 500GB     | 33        | 33     | 1.12%   |
| Seagate ST500LT012-9WS142 500GB     | 28        | 29     | 0.95%   |
| Seagate ST3500418AS 500GB           | 28        | 29     | 0.95%   |
| HGST HTS545050A7E680 500GB          | 27        | 27     | 0.92%   |
| Toshiba MQ01ABF050 500GB            | 26        | 26     | 0.88%   |
| Kingston SV300S37A120G 120GB SSD    | 24        | 24     | 0.82%   |
| Seagate ST9320325AS 320GB           | 22        | 22     | 0.75%   |
| HGST HTS541010A9E680 1TB            | 21        | 21     | 0.71%   |
| Toshiba MQ01ABD075 752GB            | 18        | 18     | 0.61%   |
| Hitachi HTS543232A7A384 320GB       | 17        | 17     | 0.58%   |
| WDC WD5000AAKX-001CA0 500GB         | 16        | 17     | 0.54%   |
| Samsung Electronics HD322HJ 320GB   | 16        | 16     | 0.54%   |
| Toshiba DT01ACA100 1TB              | 15        | 15     | 0.51%   |
| Seagate ST1000LM035-1RK172 1TB      | 15        | 15     | 0.51%   |
| Hitachi HTS545050A7E380 500GB       | 15        | 15     | 0.51%   |
| Crucial CT240M500SSD1 240GB         | 15        | 15     | 0.51%   |
| Toshiba MQ01ABD100 1TB              | 14        | 14     | 0.48%   |
| Toshiba MQ01ABD050 500GB            | 14        | 14     | 0.48%   |
| HGST HTS721010A9E630 1TB            | 14        | 15     | 0.48%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 13        | 13     | 0.44%   |
| WDC WD10JPVX-22JC3T0 1TB            | 13        | 13     | 0.44%   |
| Toshiba DT01ACA050 500GB            | 13        | 13     | 0.44%   |
| Seagate ST500LM021-1KJ152 500GB     | 13        | 13     | 0.44%   |
| Seagate ST31000524AS 1TB            | 13        | 13     | 0.44%   |
| HGST HTS545050A7E380 500GB          | 13        | 13     | 0.44%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 12        | 12     | 0.41%   |
| Seagate ST3500413AS 500GB           | 12        | 12     | 0.41%   |
| Seagate ST3320418AS 320GB           | 12        | 12     | 0.41%   |
| Seagate ST31000528AS 1TB            | 12        | 12     | 0.41%   |
| Seagate ST1000DM010-2EP102 1TB      | 12        | 12     | 0.41%   |
| Seagate ST1000DM003-9YN162 1TB      | 12        | 12     | 0.41%   |
| Hitachi HTS547550A9E384 500GB       | 12        | 13     | 0.41%   |
| Hitachi HDS721050CLA362 500GB       | 12        | 13     | 0.41%   |
| Samsung Electronics HD502HJ 500GB   | 11        | 11     | 0.37%   |
| Samsung Electronics HD161HJ 160GB   | 11        | 11     | 0.37%   |
| HGST HTS725050A7E630 500GB          | 11        | 11     | 0.37%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 767       | 817    | 26.89%  |
| WDC                 | 666       | 731    | 23.35%  |
| Hitachi             | 286       | 298    | 10.03%  |
| Toshiba             | 245       | 247    | 8.59%   |
| Samsung Electronics | 229       | 243    | 8.03%   |
| SanDisk             | 153       | 153    | 5.36%   |
| HGST                | 106       | 107    | 3.72%   |
| Kingston            | 70        | 72     | 2.45%   |
| Maxtor              | 47        | 48     | 1.65%   |
| Crucial             | 43        | 44     | 1.51%   |
| Intel               | 27        | 27     | 0.95%   |
| A-DATA Technology   | 26        | 27     | 0.91%   |
| Fujitsu             | 24        | 24     | 0.84%   |
| China               | 18        | 18     | 0.63%   |
| SK hynix            | 17        | 18     | 0.6%    |
| Micron Technology   | 11        | 11     | 0.39%   |
| OCZ                 | 9         | 9      | 0.32%   |
| GOODRAM             | 7         | 7      | 0.25%   |
| SPCC                | 6         | 6      | 0.21%   |
| LITEON              | 6         | 6      | 0.21%   |
| ASMT                | 6         | 6      | 0.21%   |
| Apple               | 6         | 6      | 0.21%   |
| Corsair             | 5         | 5      | 0.18%   |
| IBM/Hitachi         | 4         | 4      | 0.14%   |
| Transcend           | 3         | 3      | 0.11%   |
| KingSpec            | 3         | 3      | 0.11%   |
| Intenso             | 3         | 3      | 0.11%   |
| Hewlett-Packard     | 3         | 3      | 0.11%   |
| Unknown             | 3         | 3      | 0.11%   |
| WD MediaMax         | 2         | 2      | 0.07%   |
| Plextor             | 2         | 2      | 0.07%   |
| Patriot             | 2         | 2      | 0.07%   |
| Netac               | 2         | 2      | 0.07%   |
| LITEONIT            | 2         | 2      | 0.07%   |
| KingDian            | 2         | 2      | 0.07%   |
| HPE                 | 2         | 2      | 0.07%   |
| Dogfish             | 2         | 2      | 0.07%   |
| Colorful            | 2         | 2      | 0.07%   |
| ASMedia             | 2         | 2      | 0.07%   |
| Apacer              | 2         | 3      | 0.07%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 767       | 817    | 33.09%  |
| WDC                 | 637       | 699    | 27.48%  |
| Hitachi             | 286       | 298    | 12.34%  |
| Toshiba             | 241       | 243    | 10.4%   |
| Samsung Electronics | 186       | 198    | 8.02%   |
| HGST                | 106       | 107    | 4.57%   |
| Maxtor              | 47        | 48     | 2.03%   |
| Fujitsu             | 24        | 24     | 1.04%   |
| IBM/Hitachi         | 4         | 4      | 0.17%   |
| Apple               | 4         | 4      | 0.17%   |
| WD MediaMax         | 2         | 2      | 0.09%   |
| HPE                 | 2         | 2      | 0.09%   |
| ASMedia             | 2         | 2      | 0.09%   |
| RSH-339             | 1         | 1      | 0.04%   |
| Quantum             | 1         | 1      | 0.04%   |
| Magnetic Data       | 1         | 1      | 0.04%   |
| Initio              | 1         | 1      | 0.04%   |
| IB                  | 1         | 1      | 0.04%   |
| Hewlett-Packard     | 1         | 1      | 0.04%   |
| ExcelStor           | 1         | 1      | 0.04%   |
| China               | 1         | 1      | 0.04%   |
| ASMT                | 1         | 1      | 0.04%   |
| Unknown             | 1         | 1      | 0.04%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2157      | 2458   | 80.16%  |
| SSD     | 510       | 521    | 18.95%  |
| NVMe    | 23        | 23     | 0.85%   |
| Unknown | 1         | 1      | 0.04%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Apple HDD HTS541010A9E662 1TB         | 4         | 4      | 5.19%   |
| Seagate ST3250318AS 250GB             | 3         | 3      | 3.9%    |
| Samsung Electronics HD103SJ 1TB       | 3         | 3      | 3.9%    |
| WDC WD800JD-00LSA0 80GB               | 2         | 2      | 2.6%    |
| WDC WD3200BEVT-11ZCT0 320GB           | 2         | 2      | 2.6%    |
| WDC WD2500BEVS-22UST0 250GB           | 2         | 2      | 2.6%    |
| WDC WD20EZRX-00D8PB0 2TB              | 2         | 2      | 2.6%    |
| Toshiba MQ01ABD100 1TB                | 2         | 2      | 2.6%    |
| Seagate ST3500418AS 500GB             | 2         | 3      | 2.6%    |
| Hitachi HTS545050A7E380 500GB         | 2         | 2      | 2.6%    |
| Crucial CT500P2SSD8 500GB             | 2         | 2      | 2.6%    |
| WDC WD800JD-75MSA3 80GB               | 1         | 1      | 1.3%    |
| WDC WD5000M22K-24Z1LT0-SSHD-16GB      | 1         | 1      | 1.3%    |
| WDC WD5000LPLX-75ZNTT0 500GB          | 1         | 1      | 1.3%    |
| WDC WD5000BPVT-60HXZT1 500GB          | 1         | 1      | 1.3%    |
| WDC WD5000BEVT-22ZAT0 500GB           | 1         | 1      | 1.3%    |
| WDC WD5000BEVT-22A0RT0 500GB          | 1         | 1      | 1.3%    |
| WDC WD3200BEKT-60KA9T0 320GB          | 1         | 1      | 1.3%    |
| WDC WD3200AAJS-60Z0A0 320GB           | 1         | 1      | 1.3%    |
| WDC WD2500BEVT-60ZCT1 250GB           | 1         | 1      | 1.3%    |
| WDC WD20EARS-00MVWB0 2TB              | 1         | 1      | 1.3%    |
| WDC WD1600YS-23SHB0 160GB             | 1         | 1      | 1.3%    |
| WDC WD1600BEVT-75A23T0 160GB          | 1         | 1      | 1.3%    |
| WDC WD10JPVX-60JC3T0 1TB              | 1         | 1      | 1.3%    |
| WDC WD10JPVT-75A1YT0 1TB              | 1         | 1      | 1.3%    |
| WDC WD10EALX-759BA1 1TB               | 1         | 1      | 1.3%    |
| TPH00800640GB 640GB                   | 1         | 1      | 1.3%    |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 1.3%    |
| Toshiba MK3265GSXN 320GB              | 1         | 1      | 1.3%    |
| Toshiba MK3259GSXP 320GB              | 1         | 1      | 1.3%    |
| Toshiba MK3256GSY 320GB               | 1         | 1      | 1.3%    |
| SK hynix HFS128G39TND-N210A 128GB SSD | 1         | 1      | 1.3%    |
| Seagate STM3250318AS 250GB            | 1         | 1      | 1.3%    |
| Seagate STM31000528AS 1TB             | 1         | 1      | 1.3%    |
| Seagate ST980811AS 80GB               | 1         | 1      | 1.3%    |
| Seagate ST9500420AS 500GB             | 1         | 1      | 1.3%    |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1         | 1      | 1.3%    |
| Seagate ST500DM002-1BD142 500GB       | 1         | 1      | 1.3%    |
| Seagate ST3320418AS 320GB             | 1         | 1      | 1.3%    |
| Seagate ST3160215A 160GB              | 1         | 1      | 1.3%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 23        | 23     | 29.87%  |
| Seagate             | 14        | 15     | 18.18%  |
| Samsung Electronics | 13        | 13     | 16.88%  |
| Toshiba             | 6         | 6      | 7.79%   |
| Hitachi             | 6         | 6      | 7.79%   |
| Apple               | 5         | 5      | 6.49%   |
| Crucial             | 2         | 2      | 2.6%    |
| TPH00800640GB       | 1         | 1      | 1.3%    |
| SK hynix            | 1         | 1      | 1.3%    |
| Maxtor              | 1         | 1      | 1.3%    |
| Kingston            | 1         | 1      | 1.3%    |
| Intel               | 1         | 1      | 1.3%    |
| HGST                | 1         | 1      | 1.3%    |
| GOODRAM             | 1         | 1      | 1.3%    |
| External            | 1         | 1      | 1.3%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 7263      | 11077  | 66.44%  |
| Malfunc  | 2636      | 3003   | 24.11%  |
| Detected | 957       | 1193   | 8.75%   |
| Failed   | 76        | 78     | 0.7%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 6788      | 60.01%  |
| AMD                              | 2116      | 18.71%  |
| Samsung Electronics              | 485       | 4.29%   |
| SanDisk                          | 248       | 2.19%   |
| Nvidia                           | 225       | 1.99%   |
| JMicron Technology               | 181       | 1.6%    |
| ASMedia Technology               | 174       | 1.54%   |
| Marvell Technology Group         | 156       | 1.38%   |
| Phison Electronics               | 140       | 1.24%   |
| SK hynix                         | 133       | 1.18%   |
| Kingston Technology Company      | 125       | 1.11%   |
| Micron/Crucial Technology        | 78        | 0.69%   |
| Silicon Motion                   | 66        | 0.58%   |
| VIA Technologies                 | 57        | 0.5%    |
| KIOXIA                           | 45        | 0.4%    |
| ADATA Technology                 | 45        | 0.4%    |
| Toshiba America Info Systems     | 38        | 0.34%   |
| Micron Technology                | 31        | 0.27%   |
| Solid State Storage Technology   | 26        | 0.23%   |
| Realtek Semiconductor            | 25        | 0.22%   |
| Union Memory (Shenzhen)          | 18        | 0.16%   |
| Seagate Technology               | 14        | 0.12%   |
| Silicon Image                    | 13        | 0.11%   |
| Broadcom / LSI                   | 13        | 0.11%   |
| LSI Logic / Symbios Logic        | 10        | 0.09%   |
| Lite-On Technology               | 9         | 0.08%   |
| Silicon Integrated Systems [SiS] | 8         | 0.07%   |
| Integrated Technology Express    | 6         | 0.05%   |
| Adaptec                          | 6         | 0.05%   |
| Apple                            | 5         | 0.04%   |
| Shenzhen Longsys Electronics     | 4         | 0.04%   |
| Lite-On IT Corp. / Plextor       | 4         | 0.04%   |
| Biwin Storage Technology         | 4         | 0.04%   |
| MAXIO Technology (Hangzhou)      | 3         | 0.03%   |
| Yangtze Memory Technologies      | 2         | 0.02%   |
| Promise Technology               | 2         | 0.02%   |
| OCZ Technology Group             | 2         | 0.02%   |
| Lenovo                           | 2         | 0.02%   |
| 3ware                            | 2         | 0.02%   |
| INNOGRIT                         | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 1267      | 9.3%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 504       | 3.7%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 495       | 3.63%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 436       | 3.2%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 415       | 3.05%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 349       | 2.56%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 337       | 2.47%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 306       | 2.25%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 289       | 2.12%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 287       | 2.11%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 274       | 2.01%   |
| AMD 400 Series Chipset SATA Controller                                                  | 263       | 1.93%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 238       | 1.75%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 231       | 1.7%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 226       | 1.66%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 214       | 1.57%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 206       | 1.51%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 202       | 1.48%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 194       | 1.42%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 194       | 1.42%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 191       | 1.4%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 171       | 1.25%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 169       | 1.24%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 164       | 1.2%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 163       | 1.2%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 157       | 1.15%   |
| Intel SATA Controller [RAID mode]                                                       | 156       | 1.14%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 149       | 1.09%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 148       | 1.09%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 139       | 1.02%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 131       | 0.96%   |
| Samsung NVMe SSD Controller 980                                                         | 122       | 0.9%    |
| AMD 500 Series Chipset SATA Controller                                                  | 109       | 0.8%    |
| AMD FCH SATA Controller D                                                               | 106       | 0.78%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 103       | 0.76%   |
| Nvidia MCP61 SATA Controller                                                            | 97        | 0.71%   |
| Nvidia MCP61 IDE                                                                        | 88        | 0.65%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 88        | 0.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 88        | 0.65%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 84        | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 7487      | 64.58%  |
| IDE  | 2002      | 17.27%  |
| NVMe | 1510      | 13.03%  |
| RAID | 564       | 4.87%   |
| SAS  | 16        | 0.14%   |
| SCSI | 14        | 0.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 7123      | 74.58%  |
| AMD    | 2427      | 25.41%  |
| ARM    | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-2677M CPU @ 1.80GHz             | 103       | 1.08%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 81        | 0.85%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 75        | 0.79%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 69        | 0.72%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 65        | 0.68%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 62        | 0.65%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 61        | 0.64%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 58        | 0.61%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 56        | 0.59%   |
| AMD Ryzen 5 3600 6-Core Processor             | 56        | 0.59%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 56        | 0.59%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 54        | 0.57%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 54        | 0.57%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 53        | 0.55%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 51        | 0.53%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 50        | 0.52%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 49        | 0.51%   |
| AMD FX-8350 Eight-Core Processor              | 49        | 0.51%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 48        | 0.5%    |
| Intel Core i5-10400 CPU @ 2.90GHz             | 47        | 0.49%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 47        | 0.49%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 45        | 0.47%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 45        | 0.47%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 44        | 0.46%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 43        | 0.45%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 41        | 0.43%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 41        | 0.43%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 41        | 0.43%   |
| Intel Core i5-3570K CPU @ 3.40GHz             | 40        | 0.42%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 39        | 0.41%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 39        | 0.41%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 39        | 0.41%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 39        | 0.41%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 38        | 0.4%    |
| Intel Core i5-2410M CPU @ 2.30GHz             | 38        | 0.4%    |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 38        | 0.4%    |
| Intel Core i5-2450M CPU @ 2.50GHz             | 37        | 0.39%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 37        | 0.39%   |
| Intel Celeron N4100 CPU @ 1.10GHz             | 37        | 0.39%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 35        | 0.37%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 2064      | 21.61%  |
| Intel Core i7           | 1129      | 11.82%  |
| Intel Core i3           | 1093      | 11.44%  |
| Intel Celeron           | 678       | 7.1%    |
| Intel Core 2 Duo        | 645       | 6.75%   |
| AMD Ryzen 5             | 422       | 4.42%   |
| Intel Pentium           | 401       | 4.2%    |
| AMD Ryzen 7             | 257       | 2.69%   |
| AMD FX                  | 204       | 2.14%   |
| Other                   | 198       | 2.07%   |
| Intel Pentium Dual-Core | 198       | 2.07%   |
| Intel Core 2 Quad       | 145       | 1.52%   |
| AMD Ryzen 3             | 143       | 1.5%    |
| Intel Xeon              | 142       | 1.49%   |
| AMD A8                  | 132       | 1.38%   |
| Intel Pentium Silver    | 118       | 1.24%   |
| AMD A6                  | 105       | 1.1%    |
| AMD A4                  | 95        | 0.99%   |
| AMD A10                 | 94        | 0.98%   |
| Intel Pentium Dual      | 86        | 0.9%    |
| AMD Athlon II X2        | 81        | 0.85%   |
| Intel Core 2            | 77        | 0.81%   |
| AMD Phenom II X4        | 75        | 0.79%   |
| AMD E                   | 73        | 0.76%   |
| AMD Athlon              | 72        | 0.75%   |
| AMD Athlon 64 X2        | 71        | 0.74%   |
| AMD Ryzen 9             | 68        | 0.71%   |
| AMD E1                  | 64        | 0.67%   |
| Intel Atom              | 63        | 0.66%   |
| AMD E2                  | 40        | 0.42%   |
| AMD Athlon II X4        | 34        | 0.36%   |
| Intel Core i9           | 27        | 0.28%   |
| AMD Phenom              | 27        | 0.28%   |
| AMD Phenom II X6        | 25        | 0.26%   |
| Intel Pentium Gold      | 24        | 0.25%   |
| AMD Sempron             | 24        | 0.25%   |
| Intel Pentium 4         | 22        | 0.23%   |
| AMD C-60                | 22        | 0.23%   |
| Intel Pentium D         | 21        | 0.22%   |
| Intel Genuine           | 19        | 0.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 5178      | 54.21%  |
| 4       | 2950      | 30.88%  |
| 6       | 636       | 6.66%   |
| 8       | 351       | 3.67%   |
| 1       | 239       | 2.5%    |
| 3       | 82        | 0.86%   |
| 12      | 57        | 0.6%    |
| 16      | 28        | 0.29%   |
| 10      | 17        | 0.18%   |
| 14      | 4         | 0.04%   |
| 24      | 3         | 0.03%   |
| 32      | 2         | 0.02%   |
| 128     | 1         | 0.01%   |
| 44      | 1         | 0.01%   |
| 20      | 1         | 0.01%   |
| 5       | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 9523      | 99.7%   |
| 2      | 29        | 0.3%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 5124      | 53.65%  |
| 1       | 4411      | 46.18%  |
| 8       | 9         | 0.09%   |
| 4       | 5         | 0.05%   |
| 6       | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 9545      | 99.94%  |
| Unknown        | 6         | 0.06%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x206a7    | 935       | 9.78%   |
| 0x306a9    | 815       | 8.53%   |
| 0x1067a    | 662       | 6.93%   |
| 0x306c3    | 624       | 6.53%   |
| Unknown    | 292       | 3.06%   |
| 0x20655    | 262       | 2.74%   |
| 0x506e3    | 212       | 2.22%   |
| 0x6fd      | 207       | 2.17%   |
| 0x40651    | 206       | 2.16%   |
| 0x406e3    | 198       | 2.07%   |
| 0x906ea    | 195       | 2.04%   |
| 0x306d4    | 182       | 1.9%    |
| 0x806e9    | 180       | 1.88%   |
| 0x08701021 | 160       | 1.67%   |
| 0x10676    | 156       | 1.63%   |
| 0x08108109 | 155       | 1.62%   |
| 0x906e9    | 152       | 1.59%   |
| 0x30678    | 149       | 1.56%   |
| 0x806ea    | 147       | 1.54%   |
| 0x06001119 | 121       | 1.27%   |
| 0x806ec    | 120       | 1.26%   |
| 0x706a1    | 115       | 1.2%    |
| 0x010000c8 | 112       | 1.17%   |
| 0x6fb      | 100       | 1.05%   |
| 0x20652    | 95        | 0.99%   |
| 0x706a8    | 89        | 0.93%   |
| 0x406c4    | 89        | 0.93%   |
| 0x0800820d | 86        | 0.9%    |
| 0x506c9    | 83        | 0.87%   |
| 0x07030105 | 73        | 0.76%   |
| 0x706e5    | 72        | 0.75%   |
| 0x08101016 | 72        | 0.75%   |
| 0xa0653    | 69        | 0.72%   |
| 0x906c0    | 67        | 0.7%    |
| 0x106e5    | 67        | 0.7%    |
| 0x06006705 | 66        | 0.69%   |
| 0xa0655    | 65        | 0.68%   |
| 0x06000822 | 63        | 0.66%   |
| 0x06003106 | 60        | 0.63%   |
| 0x806c1    | 59        | 0.62%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| SandyBridge      | 969       | 10.15%  |
| KabyLake         | 937       | 9.81%   |
| Haswell          | 861       | 9.01%   |
| Penryn           | 850       | 8.9%    |
| IvyBridge        | 836       | 8.75%   |
| Skylake          | 433       | 4.53%   |
| Core             | 431       | 4.51%   |
| Westmere         | 374       | 3.92%   |
| K10              | 329       | 3.44%   |
| Zen+             | 324       | 3.39%   |
| Piledriver       | 309       | 3.24%   |
| Silvermont       | 298       | 3.12%   |
| Zen 2            | 294       | 3.08%   |
| Zen              | 229       | 2.4%    |
| Goldmont plus    | 204       | 2.14%   |
| Broadwell        | 196       | 2.05%   |
| CometLake        | 170       | 1.78%   |
| Bobcat           | 141       | 1.48%   |
| Excavator        | 140       | 1.47%   |
| Zen 3            | 131       | 1.37%   |
| K8 Hammer        | 127       | 1.33%   |
| Puma             | 112       | 1.17%   |
| Nehalem          | 104       | 1.09%   |
| IceLake          | 101       | 1.06%   |
| Goldmont         | 88        | 0.92%   |
| Steamroller      | 76        | 0.8%    |
| Tremont          | 67        | 0.7%    |
| TigerLake        | 64        | 0.67%   |
| Unknown          | 61        | 0.64%   |
| Jaguar           | 60        | 0.63%   |
| Bonnell          | 52        | 0.54%   |
| K10 Llano        | 51        | 0.53%   |
| NetBurst         | 49        | 0.51%   |
| Bulldozer        | 46        | 0.48%   |
| Alderlake Hybrid | 21        | 0.22%   |
| K8 & K10 hybrid  | 16        | 0.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 5240      | 49.78%  |
| Nvidia                           | 2667      | 25.34%  |
| AMD                              | 2591      | 24.62%  |
| Matrox Electronics Systems       | 12        | 0.11%   |
| VIA Technologies                 | 6         | 0.06%   |
| Silicon Integrated Systems [SiS] | 6         | 0.06%   |
| ATI Technologies                 | 2         | 0.02%   |
| ASPEED Technology                | 2         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 752       | 6.95%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 420       | 3.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 265       | 2.45%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 250       | 2.31%   |
| Intel Core Processor Integrated Graphics Controller                                      | 246       | 2.27%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 227       | 2.1%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 206       | 1.9%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 179       | 1.65%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 173       | 1.6%    |
| Intel HD Graphics 620                                                                    | 173       | 1.6%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 172       | 1.59%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 169       | 1.56%   |
| Intel HD Graphics 5500                                                                   | 158       | 1.46%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 142       | 1.31%   |
| Intel HD Graphics 530                                                                    | 136       | 1.26%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 134       | 1.24%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 131       | 1.21%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 125       | 1.15%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 125       | 1.15%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 125       | 1.15%   |
| Intel UHD Graphics 620                                                                   | 117       | 1.08%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 110       | 1.02%   |
| Nvidia GT218 [GeForce 210]                                                               | 108       | 1%      |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 107       | 0.99%   |
| Intel HD Graphics 630                                                                    | 93        | 0.86%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 92        | 0.85%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 92        | 0.85%   |
| AMD Renoir                                                                               | 92        | 0.85%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 83        | 0.77%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 78        | 0.72%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 77        | 0.71%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 76        | 0.7%    |
| Intel HD Graphics 500                                                                    | 71        | 0.66%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 70        | 0.65%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 68        | 0.63%   |
| Intel JasperLake [UHD Graphics]                                                          | 67        | 0.62%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 64        | 0.59%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 64        | 0.59%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 63        | 0.58%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 62        | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 4293      | 44.94%  |
| 1 x AMD                 | 2215      | 23.19%  |
| 1 x Nvidia              | 1918      | 20.08%  |
| Intel + Nvidia          | 673       | 7.05%   |
| Intel + AMD             | 168       | 1.76%   |
| 2 x AMD                 | 153       | 1.6%    |
| AMD + Nvidia            | 55        | 0.58%   |
| 2 x Intel               | 31        | 0.32%   |
| 2 x Nvidia              | 18        | 0.19%   |
| 1 x Matrox              | 9         | 0.09%   |
| 1 x VIA                 | 6         | 0.06%   |
| 1 x SiS                 | 6         | 0.06%   |
| Nvidia + Matrox         | 2         | 0.02%   |
| 1 x ASPEED              | 2         | 0.02%   |
| Other                   | 1         | 0.01%   |
| 3 x AMD                 | 1         | 0.01%   |
| 2 x Nvidia + 1 x Matrox | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 9344      | 97.8%   |
| Unknown     | 199       | 2.08%   |
| Proprietary | 11        | 0.12%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 4564      | 47.77%  |
| 0.01-0.5   | 1469      | 15.38%  |
| 1.01-2.0   | 1330      | 13.92%  |
| 0.51-1.0   | 1175      | 12.3%   |
| 3.01-4.0   | 473       | 4.95%   |
| 7.01-8.0   | 282       | 2.95%   |
| 5.01-6.0   | 150       | 1.57%   |
| 2.01-3.0   | 66        | 0.69%   |
| 8.01-16.0  | 39        | 0.41%   |
| 16.01-24.0 | 5         | 0.05%   |
| 4.01-5.0   | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 1422      | 14.87%  |
| AU Optronics            | 1019      | 10.65%  |
| LG Display              | 811       | 8.48%   |
| BOE                     | 666       | 6.96%   |
| Chimei Innolux          | 654       | 6.84%   |
| Goldstar                | 608       | 6.36%   |
| Dell                    | 458       | 4.79%   |
| Hewlett-Packard         | 449       | 4.69%   |
| Acer                    | 385       | 4.02%   |
| Philips                 | 318       | 3.32%   |
| AOC                     | 266       | 2.78%   |
| BenQ                    | 227       | 2.37%   |
| Ancor Communications    | 201       | 2.1%    |
| Lenovo                  | 199       | 2.08%   |
| Chi Mei Optoelectronics | 181       | 1.89%   |
| CPT                     | 121       | 1.26%   |
| ViewSonic               | 118       | 1.23%   |
| Apple                   | 114       | 1.19%   |
| Iiyama                  | 111       | 1.16%   |
| Eizo                    | 82        | 0.86%   |
| Sony                    | 71        | 0.74%   |
| Sharp                   | 69        | 0.72%   |
| LG Philips              | 66        | 0.69%   |
| ASUSTek Computer        | 59        | 0.62%   |
| InfoVision              | 51        | 0.53%   |
| Fujitsu Siemens         | 50        | 0.52%   |
| PANDA                   | 45        | 0.47%   |
| NEC Computers           | 44        | 0.46%   |
| HannStar                | 38        | 0.4%    |
| Toshiba                 | 36        | 0.38%   |
| Panasonic               | 27        | 0.28%   |
| Vizio                   | 23        | 0.24%   |
| Vestel Elektronik       | 22        | 0.23%   |
| Unknown                 | 21        | 0.22%   |
| Sceptre Tech            | 21        | 0.22%   |
| Medion                  | 21        | 0.22%   |
| Hitachi                 | 16        | 0.17%   |
| MStar                   | 15        | 0.16%   |
| ___                     | 14        | 0.15%   |
| InnoLux Display         | 14        | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| CPT LCD Monitor COR17DB 1600x900 293x164mm 13.2-inch                     | 103       | 1.07%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 54        | 0.56%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 42        | 0.44%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 41        | 0.42%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 40        | 0.41%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 40        | 0.41%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 40        | 0.41%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 37        | 0.38%   |
| Eizo EV3285 ENC2979 3840x2160 698x393mm 31.5-inch                        | 37        | 0.38%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 34        | 0.35%   |
| BOE LCD Monitor BOE093D 1366x768 256x144mm 11.6-inch                     | 33        | 0.34%   |
| BOE LCD Monitor BOE0629 1366x768 309x173mm 13.9-inch                     | 31        | 0.32%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 30        | 0.31%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 30        | 0.31%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch           | 27        | 0.28%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 26        | 0.27%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 24        | 0.25%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch              | 24        | 0.25%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 23        | 0.24%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch   | 22        | 0.23%   |
| Dell D1918H DEL2005 1366x768 410x230mm 18.5-inch                         | 22        | 0.23%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 22        | 0.23%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 22        | 0.23%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 22        | 0.23%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 22        | 0.23%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch        | 21        | 0.22%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 21        | 0.22%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 21        | 0.22%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                          | 21        | 0.22%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 20        | 0.21%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 20        | 0.21%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 20        | 0.21%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 20        | 0.21%   |
| AU Optronics LCD Monitor AUO202D 1920x1080 293x165mm 13.2-inch           | 20        | 0.21%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 19        | 0.2%    |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 18        | 0.19%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 18        | 0.19%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 18        | 0.19%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 17        | 0.18%   |
| PANDA LM116LF3L02 NCP000A 1920x1080 256x144mm 11.6-inch                  | 17        | 0.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 3619      | 38.43%  |
| 1366x768 (WXGA)    | 2486      | 26.4%   |
| 1600x900 (HD+)     | 607       | 6.45%   |
| 1280x1024 (SXGA)   | 448       | 4.76%   |
| 3840x2160 (4K)     | 444       | 4.71%   |
| 1680x1050 (WSXGA+) | 353       | 3.75%   |
| 1440x900 (WXGA+)   | 320       | 3.4%    |
| 1280x800 (WXGA)    | 292       | 3.1%    |
| 2560x1440 (QHD)    | 242       | 2.57%   |
| 1920x1200 (WUXGA)  | 155       | 1.65%   |
| 1360x768           | 96        | 1.02%   |
| 2560x1080          | 48        | 0.51%   |
| 3440x1440          | 41        | 0.44%   |
| 1920x540           | 33        | 0.35%   |
| 1024x768 (XGA)     | 33        | 0.35%   |
| 2560x1600          | 27        | 0.29%   |
| 1600x1200          | 20        | 0.21%   |
| 3200x1800 (QHD+)   | 17        | 0.18%   |
| 1024x600           | 16        | 0.17%   |
| 1280x720 (HD)      | 13        | 0.14%   |
| 2160x1440          | 10        | 0.11%   |
| 1280x960           | 10        | 0.11%   |
| 2880x1800          | 9         | 0.1%    |
| 1680x945           | 8         | 0.08%   |
| 3840x1080          | 7         | 0.07%   |
| 2736x1824          | 7         | 0.07%   |
| 2288x1287          | 6         | 0.06%   |
| 2256x1504          | 6         | 0.06%   |
| 2048x1152          | 6         | 0.06%   |
| 1920x1280          | 5         | 0.05%   |
| 3840x2400          | 4         | 0.04%   |
| 1400x1050          | 4         | 0.04%   |
| 1280x768           | 4         | 0.04%   |
| 3840x1600          | 3         | 0.03%   |
| 800x1280           | 2         | 0.02%   |
| 3456x2160          | 2         | 0.02%   |
| 1152x864           | 2         | 0.02%   |
| 3840x1200          | 1         | 0.01%   |
| 3840x1100          | 1         | 0.01%   |
| 3300x2200          | 1         | 0.01%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 2273      | 23.73%  |
| 13      | 815       | 8.51%   |
| 23      | 783       | 8.18%   |
| 21      | 733       | 7.65%   |
| 17      | 695       | 7.26%   |
| 27      | 614       | 6.41%   |
| 24      | 572       | 5.97%   |
| 14      | 537       | 5.61%   |
| 19      | 426       | 4.45%   |
| 18      | 332       | 3.47%   |
| 22      | 243       | 2.54%   |
| 31      | 238       | 2.49%   |
| 20      | 202       | 2.11%   |
| 11      | 201       | 2.1%    |
| 12      | 171       | 1.79%   |
| 34      | 83        | 0.87%   |
| 84      | 82        | 0.86%   |
| Unknown | 62        | 0.65%   |
| 32      | 58        | 0.61%   |
| 72      | 47        | 0.49%   |
| 54      | 47        | 0.49%   |
| 26      | 40        | 0.42%   |
| 25      | 36        | 0.38%   |
| 16      | 26        | 0.27%   |
| 10      | 26        | 0.27%   |
| 52      | 22        | 0.23%   |
| 40      | 20        | 0.21%   |
| 65      | 19        | 0.2%    |
| 48      | 14        | 0.15%   |
| 28      | 14        | 0.15%   |
| 37      | 13        | 0.14%   |
| 46      | 11        | 0.11%   |
| 39      | 11        | 0.11%   |
| 33      | 11        | 0.11%   |
| 29      | 10        | 0.1%    |
| 74      | 9         | 0.09%   |
| 60      | 8         | 0.08%   |
| 49      | 8         | 0.08%   |
| 43      | 8         | 0.08%   |
| 42      | 8         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 3362      | 35.44%  |
| 501-600        | 1903      | 20.06%  |
| 401-500        | 1715      | 18.08%  |
| 201-300        | 807       | 8.51%   |
| 351-400        | 793       | 8.36%   |
| 601-700        | 322       | 3.39%   |
| 701-800        | 154       | 1.62%   |
| 1001-1500      | 152       | 1.6%    |
| 1501-2000      | 140       | 1.48%   |
| Unknown        | 62        | 0.65%   |
| 801-900        | 52        | 0.55%   |
| 901-1000       | 17        | 0.18%   |
| More than 2000 | 6         | 0.06%   |
| 1-100          | 2         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 7240      | 79.1%   |
| 16/10   | 1184      | 12.94%  |
| 5/4     | 434       | 4.74%   |
| 4/3     | 91        | 0.99%   |
| 21/9    | 87        | 0.95%   |
| 3/2     | 76        | 0.83%   |
| 6/5     | 11        | 0.12%   |
| 32/9    | 11        | 0.12%   |
| 1.00    | 6         | 0.07%   |
| Unknown | 5         | 0.05%   |
| 1.96    | 2         | 0.02%   |
| 0.67    | 2         | 0.02%   |
| 3.40    | 1         | 0.01%   |
| 3.20    | 1         | 0.01%   |
| 2.01    | 1         | 0.01%   |
| 0.75    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 2252      | 23.65%  |
| 201-250        | 1893      | 19.88%  |
| 81-90          | 989       | 10.39%  |
| 151-200        | 895       | 9.4%    |
| 301-350        | 645       | 6.77%   |
| 141-150        | 500       | 5.25%   |
| 351-500        | 402       | 4.22%   |
| 121-130        | 381       | 4%      |
| 71-80          | 369       | 3.88%   |
| More than 1000 | 271       | 2.85%   |
| 251-300        | 237       | 2.49%   |
| 51-60          | 203       | 2.13%   |
| 61-70          | 157       | 1.65%   |
| 501-1000       | 101       | 1.06%   |
| 131-140        | 87        | 0.91%   |
| Unknown        | 62        | 0.65%   |
| 111-120        | 31        | 0.33%   |
| 41-50          | 25        | 0.26%   |
| 91-100         | 20        | 0.21%   |
| 1-40           | 2         | 0.02%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 3931      | 41.98%  |
| 101-120       | 3108      | 33.19%  |
| 121-160       | 1685      | 17.99%  |
| 161-240       | 280       | 2.99%   |
| 1-50          | 246       | 2.63%   |
| Unknown       | 62        | 0.66%   |
| More than 240 | 53        | 0.57%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 8744      | 91.52%  |
| 2     | 670       | 7.01%   |
| 0     | 99        | 1.04%   |
| 3     | 33        | 0.35%   |
| 4     | 4         | 0.04%   |
| 6     | 2         | 0.02%   |
| 7     | 1         | 0.01%   |
| 5     | 1         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 5551      | 39.67%  |
| Intel                             | 3678      | 26.28%  |
| Qualcomm Atheros                  | 2081      | 14.87%  |
| Broadcom                          | 703       | 5.02%   |
| Marvell Technology Group          | 213       | 1.52%   |
| Ralink                            | 195       | 1.39%   |
| Ralink Technology                 | 186       | 1.33%   |
| Nvidia                            | 180       | 1.29%   |
| Broadcom Limited                  | 176       | 1.26%   |
| Samsung Electronics               | 136       | 0.97%   |
| TP-Link                           | 102       | 0.73%   |
| Huawei Technologies               | 66        | 0.47%   |
| Qualcomm Atheros Communications   | 56        | 0.4%    |
| JMicron Technology                | 53        | 0.38%   |
| MediaTek                          | 50        | 0.36%   |
| Dell                              | 45        | 0.32%   |
| D-Link                            | 37        | 0.26%   |
| Ericsson Business Mobile Networks | 34        | 0.24%   |
| D-Link System                     | 34        | 0.24%   |
| ASIX Electronics                  | 26        | 0.19%   |
| VIA Technologies                  | 25        | 0.18%   |
| NetGear                           | 25        | 0.18%   |
| Motorola PCS                      | 22        | 0.16%   |
| Xiaomi                            | 19        | 0.14%   |
| Microsoft                         | 18        | 0.13%   |
| ASUSTek Computer                  | 18        | 0.13%   |
| Aquantia                          | 18        | 0.13%   |
| Sierra Wireless                   | 17        | 0.12%   |
| Belkin Components                 | 15        | 0.11%   |
| ZTE WCDMA Technologies MSM        | 14        | 0.1%    |
| Linksys                           | 13        | 0.09%   |
| Hewlett-Packard                   | 13        | 0.09%   |
| Edimax Technology                 | 12        | 0.09%   |
| DisplayLink                       | 12        | 0.09%   |
| IMC Networks                      | 11        | 0.08%   |
| 3Com                              | 10        | 0.07%   |
| Silicon Integrated Systems [SiS]  | 8         | 0.06%   |
| Qualcomm                          | 8         | 0.06%   |
| AVM                               | 8         | 0.06%   |
| OPPO Electronics                  | 6         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4023      | 24.98%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 799       | 4.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 407       | 2.53%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 338       | 2.1%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 308       | 1.91%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 274       | 1.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 263       | 1.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 205       | 1.27%   |
| Intel Wi-Fi 6 AX200                                               | 205       | 1.27%   |
| Intel Wireless 7265                                               | 173       | 1.07%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 166       | 1.03%   |
| Intel Ethernet Connection I217-LM                                 | 156       | 0.97%   |
| Intel Wireless 8265 / 8275                                        | 155       | 0.96%   |
| Intel I211 Gigabit Network Connection                             | 150       | 0.93%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 142       | 0.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 138       | 0.86%   |
| Intel Wireless 7260                                               | 135       | 0.84%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 133       | 0.83%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 130       | 0.81%   |
| Intel Ethernet Connection (2) I219-V                              | 124       | 0.77%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 117       | 0.73%   |
| Intel 82579V Gigabit Network Connection                           | 117       | 0.73%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 116       | 0.72%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 114       | 0.71%   |
| Intel Wireless 3165                                               | 114       | 0.71%   |
| Realtek RTL8125 2.5GbE Controller                                 | 112       | 0.7%    |
| Intel Wireless 8260                                               | 105       | 0.65%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 100       | 0.62%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 99        | 0.61%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 99        | 0.61%   |
| Nvidia MCP61 Ethernet                                             | 85        | 0.53%   |
| Intel WiFi Link 5100                                              | 83        | 0.52%   |
| Intel Wireless 3160                                               | 82        | 0.51%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 81        | 0.5%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 81        | 0.5%    |
| Ralink MT7601U Wireless Adapter                                   | 81        | 0.5%    |
| Intel 82577LM Gigabit Network Connection                          | 74        | 0.46%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 73        | 0.45%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 73        | 0.45%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 73        | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2494      | 37.45%  |
| Qualcomm Atheros                | 1654      | 24.84%  |
| Realtek Semiconductor           | 1233      | 18.52%  |
| Broadcom                        | 399       | 5.99%   |
| Ralink                          | 195       | 2.93%   |
| Ralink Technology               | 186       | 2.79%   |
| TP-Link                         | 79        | 1.19%   |
| Broadcom Limited                | 72        | 1.08%   |
| Qualcomm Atheros Communications | 56        | 0.84%   |
| MediaTek                        | 39        | 0.59%   |
| D-Link                          | 33        | 0.5%    |
| Dell                            | 25        | 0.38%   |
| NetGear                         | 21        | 0.32%   |
| ASUSTek Computer                | 18        | 0.27%   |
| Sierra Wireless                 | 17        | 0.26%   |
| Microsoft                       | 17        | 0.26%   |
| D-Link System                   | 16        | 0.24%   |
| Belkin Components               | 14        | 0.21%   |
| Linksys                         | 12        | 0.18%   |
| Edimax Technology               | 12        | 0.18%   |
| IMC Networks                    | 11        | 0.17%   |
| Marvell Technology Group        | 9         | 0.14%   |
| AVM                             | 8         | 0.12%   |
| Hewlett-Packard                 | 6         | 0.09%   |
| Wilocity                        | 4         | 0.06%   |
| Sitecom Europe                  | 4         | 0.06%   |
| ZyDAS                           | 3         | 0.05%   |
| Mercucys                        | 3         | 0.05%   |
| Guillemot                       | 3         | 0.05%   |
| Wacom                           | 2         | 0.03%   |
| Qcom                            | 2         | 0.03%   |
| Philips (or NXP)                | 2         | 0.03%   |
| Chu Yuen Enterprise             | 2         | 0.03%   |
| ZyXEL Communications            | 1         | 0.02%   |
| TRENDnet                        | 1         | 0.02%   |
| Senao                           | 1         | 0.02%   |
| PLANEX                          | 1         | 0.02%   |
| Logitec                         | 1         | 0.02%   |
| Fibocom                         | 1         | 0.02%   |
| BUFFALO                         | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 338       | 5.06%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 308       | 4.61%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 274       | 4.1%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 263       | 3.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 205       | 3.07%   |
| Intel Wi-Fi 6 AX200                                                     | 205       | 3.07%   |
| Intel Wireless 7265                                                     | 173       | 2.59%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 166       | 2.49%   |
| Intel Wireless 8265 / 8275                                              | 155       | 2.32%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 142       | 2.13%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 138       | 2.07%   |
| Intel Wireless 7260                                                     | 135       | 2.02%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 117       | 1.75%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 116       | 1.74%   |
| Intel Wireless 3165                                                     | 114       | 1.71%   |
| Intel Wireless 8260                                                     | 105       | 1.57%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 100       | 1.5%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 99        | 1.48%   |
| Intel WiFi Link 5100                                                    | 83        | 1.24%   |
| Intel Wireless 3160                                                     | 82        | 1.23%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 81        | 1.21%   |
| Ralink MT7601U Wireless Adapter                                         | 81        | 1.21%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 73        | 1.09%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 73        | 1.09%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 73        | 1.09%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 68        | 1.02%   |
| Intel Centrino Advanced-N 6200                                          | 65        | 0.97%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 65        | 0.97%   |
| Intel Wireless-AC 9260                                                  | 64        | 0.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 64        | 0.96%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 63        | 0.94%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 61        | 0.91%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 60        | 0.9%    |
| Intel Wi-Fi 6 AX201 160MHz                                              | 59        | 0.88%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 56        | 0.84%   |
| Intel Centrino Ultimate-N 6300                                          | 56        | 0.84%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 55        | 0.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 55        | 0.82%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 54        | 0.81%   |
| Broadcom BCM43142 802.11b/g/n                                           | 52        | 0.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 5131      | 55.89%  |
| Intel                             | 2014      | 21.94%  |
| Qualcomm Atheros                  | 640       | 6.97%   |
| Broadcom                          | 391       | 4.26%   |
| Marvell Technology Group          | 204       | 2.22%   |
| Nvidia                            | 179       | 1.95%   |
| Samsung Electronics               | 136       | 1.48%   |
| Broadcom Limited                  | 106       | 1.15%   |
| Huawei Technologies               | 59        | 0.64%   |
| JMicron Technology                | 53        | 0.58%   |
| ASIX Electronics                  | 26        | 0.28%   |
| TP-Link                           | 24        | 0.26%   |
| VIA Technologies                  | 23        | 0.25%   |
| Xiaomi                            | 19        | 0.21%   |
| D-Link System                     | 18        | 0.2%    |
| Aquantia                          | 18        | 0.2%    |
| Motorola PCS                      | 14        | 0.15%   |
| ZTE WCDMA Technologies MSM        | 13        | 0.14%   |
| DisplayLink                       | 12        | 0.13%   |
| MediaTek                          | 11        | 0.12%   |
| 3Com                              | 10        | 0.11%   |
| Silicon Integrated Systems [SiS]  | 8         | 0.09%   |
| Qualcomm                          | 8         | 0.09%   |
| OPPO Electronics                  | 6         | 0.07%   |
| ICS Advent                        | 5         | 0.05%   |
| T & A Mobile Phones               | 4         | 0.04%   |
| OnePlus Technology (Shenzhen)     | 4         | 0.04%   |
| NetGear                           | 4         | 0.04%   |
| Google                            | 4         | 0.04%   |
| D-Link                            | 4         | 0.04%   |
| HMD Global                        | 3         | 0.03%   |
| Apple                             | 3         | 0.03%   |
| Sundance Technology Inc / IC Plus | 2         | 0.02%   |
| Spreadtrum Communications         | 2         | 0.02%   |
| LG Electronics                    | 2         | 0.02%   |
| Lenovo                            | 2         | 0.02%   |
| HTC (High Tech Computer)          | 2         | 0.02%   |
| vivo                              | 1         | 0.01%   |
| Sitecom Europe                    | 1         | 0.01%   |
| Netchip Technology                | 1         | 0.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4023      | 43.14%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 799       | 8.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 407       | 4.36%   |
| Intel Ethernet Connection I217-LM                                 | 156       | 1.67%   |
| Intel I211 Gigabit Network Connection                             | 150       | 1.61%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 133       | 1.43%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 130       | 1.39%   |
| Intel Ethernet Connection (2) I219-V                              | 124       | 1.33%   |
| Intel 82579V Gigabit Network Connection                           | 117       | 1.25%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 114       | 1.22%   |
| Realtek RTL8125 2.5GbE Controller                                 | 112       | 1.2%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 99        | 1.06%   |
| Nvidia MCP61 Ethernet                                             | 85        | 0.91%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 81        | 0.87%   |
| Intel 82577LM Gigabit Network Connection                          | 74        | 0.79%   |
| Intel 82567LM Gigabit Network Connection                          | 66        | 0.71%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 64        | 0.69%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 59        | 0.63%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 57        | 0.61%   |
| Intel Ethernet Connection (7) I219-V                              | 56        | 0.6%    |
| Intel Ethernet Controller I225-V                                  | 54        | 0.58%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 52        | 0.56%   |
| Intel Ethernet Connection I217-V                                  | 51        | 0.55%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 51        | 0.55%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 45        | 0.48%   |
| Intel Ethernet Connection (3) I218-LM                             | 44        | 0.47%   |
| Intel Ethernet Connection (2) I219-LM                             | 44        | 0.47%   |
| Intel Ethernet Connection I218-LM                                 | 43        | 0.46%   |
| Huawei E353/E3131                                                 | 43        | 0.46%   |
| Intel Ethernet Connection I219-LM                                 | 41        | 0.44%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 39        | 0.42%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 39        | 0.42%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 38        | 0.41%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 38        | 0.41%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 34        | 0.36%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 33        | 0.35%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 33        | 0.35%   |
| Intel 82574L Gigabit Network Connection                           | 32        | 0.34%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 31        | 0.33%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 30        | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 8794      | 57.33%  |
| WiFi     | 6444      | 42.01%  |
| Modem    | 83        | 0.54%   |
| Unknown  | 19        | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 5428      | 57.94%  |
| WiFi     | 3940      | 42.05%  |
| Unknown  | 1         | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 4992      | 52.26%  |
| 1     | 4346      | 45.49%  |
| 3     | 127       | 1.33%   |
| 0     | 73        | 0.76%   |
| 4     | 11        | 0.12%   |
| 5     | 2         | 0.02%   |
| 10    | 1         | 0.01%   |
| 7     | 1         | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 7142      | 74.71%  |
| Yes     | 2417      | 25.28%  |
| Unknown | 1         | 0.01%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1735      | 38.02%  |
| Qualcomm Atheros Communications | 480       | 10.52%  |
| Realtek Semiconductor           | 472       | 10.34%  |
| Cambridge Silicon Radio         | 334       | 7.32%   |
| Broadcom                        | 321       | 7.03%   |
| Lite-On Technology              | 238       | 5.22%   |
| IMC Networks                    | 196       | 4.3%    |
| Foxconn / Hon Hai               | 142       | 3.11%   |
| Apple                           | 124       | 2.72%   |
| Dell                            | 101       | 2.21%   |
| ASUSTek Computer                | 84        | 1.84%   |
| Toshiba                         | 75        | 1.64%   |
| Hewlett-Packard                 | 65        | 1.42%   |
| Ralink                          | 49        | 1.07%   |
| Realtek                         | 19        | 0.42%   |
| Foxconn International           | 15        | 0.33%   |
| Alps Electric                   | 14        | 0.31%   |
| Ralink Technology               | 13        | 0.28%   |
| Chicony Electronics             | 11        | 0.24%   |
| Marvell Semiconductor           | 10        | 0.22%   |
| MediaTek                        | 9         | 0.2%    |
| Askey Computer                  | 8         | 0.18%   |
| Integrated System Solution      | 7         | 0.15%   |
| Belkin Components               | 6         | 0.13%   |
| Taiyo Yuden                     | 4         | 0.09%   |
| Fujitsu                         | 4         | 0.09%   |
| Unknown                         | 3         | 0.07%   |
| TP-Link                         | 3         | 0.07%   |
| Primax Electronics              | 3         | 0.07%   |
| Micro Star International        | 3         | 0.07%   |
| Edimax Technology               | 3         | 0.07%   |
| Dynex                           | 3         | 0.07%   |
| Unknown                         | 3         | 0.07%   |
| USI                             | 1         | 0.02%   |
| SINO WEALTH                     | 1         | 0.02%   |
| Qcom                            | 1         | 0.02%   |
| Opticis                         | 1         | 0.02%   |
| i.Tech Dynamic Limited          | 1         | 0.02%   |
| D-Link System                   | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 793       | 17.38%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 334       | 7.32%   |
| Realtek Bluetooth Radio                                                             | 286       | 6.27%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 237       | 5.19%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 218       | 4.78%   |
| Intel AX200 Bluetooth                                                               | 198       | 4.34%   |
| Intel AX201 Bluetooth                                                               | 176       | 3.86%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 130       | 2.85%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 116       | 2.54%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 88        | 1.93%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 85        | 1.86%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 79        | 1.73%   |
| IMC Networks Bluetooth Radio                                                        | 76        | 1.67%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 73        | 1.6%    |
| Broadcom BCM2045B (BDC-2.1)                                                         | 63        | 1.38%   |
| IMC Networks Bluetooth Device                                                       | 61        | 1.34%   |
| Lite-On Bluetooth Device                                                            | 58        | 1.27%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 58        | 1.27%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 56        | 1.23%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 53        | 1.16%   |
| Apple Bluetooth Host Controller                                                     | 50        | 1.1%    |
| Ralink RT3290 Bluetooth                                                             | 49        | 1.07%   |
| Dell DW375 Bluetooth Module                                                         | 47        | 1.03%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 45        | 0.99%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 44        | 0.96%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 42        | 0.92%   |
| Apple Bluetooth USB Host Controller                                                 | 39        | 0.85%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 36        | 0.79%   |
| Realtek RTL8723B Bluetooth                                                          | 33        | 0.72%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 33        | 0.72%   |
| Intel AX210 Bluetooth                                                               | 31        | 0.68%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 30        | 0.66%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 29        | 0.64%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 28        | 0.61%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 28        | 0.61%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 27        | 0.59%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 25        | 0.55%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 24        | 0.53%   |
| Broadcom BCM2045 Bluetooth                                                          | 23        | 0.5%    |
| Toshiba Bluetooth Device                                                            | 22        | 0.48%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 6933      | 54.81%  |
| AMD                                             | 2841      | 22.46%  |
| Nvidia                                          | 2090      | 16.52%  |
| C-Media Electronics                             | 168       | 1.33%   |
| Creative Labs                                   | 126       | 1%      |
| Logitech                                        | 61        | 0.48%   |
| Texas Instruments                               | 39        | 0.31%   |
| JMTek                                           | 32        | 0.25%   |
| Creative Technology                             | 29        | 0.23%   |
| VIA Technologies                                | 25        | 0.2%    |
| Generalplus Technology                          | 22        | 0.17%   |
| ASUSTek Computer                                | 19        | 0.15%   |
| Razer USA                                       | 12        | 0.09%   |
| Tenx Technology                                 | 10        | 0.08%   |
| Realtek Semiconductor                           | 10        | 0.08%   |
| GN Netcom                                       | 10        | 0.08%   |
| Focusrite-Novation                              | 10        | 0.08%   |
| Kingston Technology                             | 9         | 0.07%   |
| Silicon Integrated Systems [SiS]                | 8         | 0.06%   |
| XMOS                                            | 6         | 0.05%   |
| Thesycon Systemsoftware & Consulting            | 6         | 0.05%   |
| Samson Technologies                             | 6         | 0.05%   |
| Plantronics                                     | 6         | 0.05%   |
| M-Audio                                         | 6         | 0.05%   |
| Giga-Byte Technology                            | 6         | 0.05%   |
| Blue Microphones                                | 6         | 0.05%   |
| Yamaha                                          | 5         | 0.04%   |
| Sony                                            | 5         | 0.04%   |
| Dell                                            | 5         | 0.04%   |
| SteelSeries ApS                                 | 4         | 0.03%   |
| ROCCAT                                          | 4         | 0.03%   |
| PreSonus Audio Electronics                      | 4         | 0.03%   |
| Ensoniq                                         | 4         | 0.03%   |
| Corsair                                         | 4         | 0.03%   |
| Bose                                            | 4         | 0.03%   |
| Apple                                           | 4         | 0.03%   |
| SAVITECH                                        | 3         | 0.02%   |
| Licensed by Sony Computer Entertainment America | 3         | 0.02%   |
| Lenovo                                          | 3         | 0.02%   |
| KTMicro                                         | 3         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 910       | 6.02%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 846       | 5.59%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 581       | 3.84%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 565       | 3.74%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 552       | 3.65%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 521       | 3.45%   |
| AMD FCH Azalia Controller                                                                         | 497       | 3.29%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 441       | 2.92%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 418       | 2.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 415       | 2.74%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 352       | 2.33%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 324       | 2.14%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 259       | 1.71%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 253       | 1.67%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 243       | 1.61%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 236       | 1.56%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 214       | 1.42%   |
| Intel 8 Series HD Audio Controller                                                                | 208       | 1.38%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 206       | 1.36%   |
| AMD Kabini HDMI/DP Audio                                                                          | 205       | 1.36%   |
| Nvidia High Definition Audio Controller                                                           | 202       | 1.34%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 202       | 1.34%   |
| Intel Cannon Lake PCH cAVS                                                                        | 201       | 1.33%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 190       | 1.26%   |
| Intel Broadwell-U Audio Controller                                                                | 187       | 1.24%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 184       | 1.22%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 184       | 1.22%   |
| Intel 200 Series PCH HD Audio                                                                     | 180       | 1.19%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 173       | 1.14%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 164       | 1.08%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 136       | 0.9%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 135       | 0.89%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 134       | 0.89%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 127       | 0.84%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 119       | 0.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 116       | 0.77%   |
| AMD Wrestler HDMI Audio                                                                           | 110       | 0.73%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 107       | 0.71%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 105       | 0.69%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 103       | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 2086      | 18.51%  |
| SK hynix            | 1656      | 14.69%  |
| Unknown             | 1632      | 14.48%  |
| Kingston            | 1487      | 13.19%  |
| Micron Technology   | 832       | 7.38%   |
| Crucial             | 580       | 5.15%   |
| Corsair             | 465       | 4.13%   |
| G.Skill             | 330       | 2.93%   |
| Elpida              | 315       | 2.8%    |
| A-DATA Technology   | 251       | 2.23%   |
| Ramaxel Technology  | 214       | 1.9%    |
| Nanya Technology    | 189       | 1.68%   |
| Smart               | 127       | 1.13%   |
| Unknown (ABCD)      | 100       | 0.89%   |
| Patriot             | 90        | 0.8%    |
| Unknown             | 90        | 0.8%    |
| Team                | 76        | 0.67%   |
| Goodram             | 57        | 0.51%   |
| Transcend           | 49        | 0.43%   |
| AMD                 | 42        | 0.37%   |
| Apacer              | 40        | 0.35%   |
| Teikon              | 30        | 0.27%   |
| ASint Technology    | 30        | 0.27%   |
| Kingmax             | 26        | 0.23%   |
| Qimonda             | 25        | 0.22%   |
| Silicon Power       | 23        | 0.2%    |
| Toshiba             | 21        | 0.19%   |
| High Bridge         | 19        | 0.17%   |
| Unifosa             | 18        | 0.16%   |
| GeIL                | 18        | 0.16%   |
| Avant               | 17        | 0.15%   |
| PNY                 | 15        | 0.13%   |
| CSX                 | 14        | 0.12%   |
| Multilaser          | 13        | 0.12%   |
| Smart Brazil        | 11        | 0.1%    |
| Goldkey             | 9         | 0.08%   |
| Qumo                | 7         | 0.06%   |
| OCZ                 | 7         | 0.06%   |
| Atermiter           | 7         | 0.06%   |
| Timetec             | 6         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 122       | 1%      |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 113       | 0.92%   |
| Elpida RAM Module 2GB SODIMM DDR3 1333MT/s                       | 107       | 0.87%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 106       | 0.86%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 102       | 0.83%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 91        | 0.74%   |
| Unknown                                                          | 90        | 0.73%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 89        | 0.73%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 85        | 0.69%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 85        | 0.69%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 75        | 0.61%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 75        | 0.61%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 74        | 0.6%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 72        | 0.59%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 68        | 0.55%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 68        | 0.55%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 64        | 0.52%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 58        | 0.47%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 55        | 0.45%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 51        | 0.42%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 47        | 0.38%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 47        | 0.38%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 46        | 0.38%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 46        | 0.38%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 45        | 0.37%   |
| SK hynix RAM HCNNNBKMMLXR-NEE 1GB Row Of Chips LPDDR4 4267MT/s   | 44        | 0.36%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 43        | 0.35%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 42        | 0.34%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 41        | 0.33%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s         | 40        | 0.33%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 40        | 0.33%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s            | 39        | 0.32%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                         | 38        | 0.31%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                             | 37        | 0.3%    |
| Kingston RAM KHX1600C10D3/8G 8192MB DIMM DDR3 1600MT/s           | 37        | 0.3%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 36        | 0.29%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 35        | 0.29%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 35        | 0.29%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 35        | 0.29%   |
| Samsung RAM M378B5173QH0-CK0 4096MB DIMM DDR3 1600MT/s           | 35        | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 4544      | 47.23%  |
| DDR4    | 2820      | 29.31%  |
| DDR2    | 861       | 8.95%   |
| Unknown | 509       | 5.29%   |
| SDRAM   | 470       | 4.88%   |
| LPDDR4  | 239       | 2.48%   |
| DDR     | 83        | 0.86%   |
| LPDDR3  | 63        | 0.65%   |
| DRAM    | 24        | 0.25%   |
| DDR5    | 5         | 0.05%   |
| LPDDR5  | 4         | 0.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 4891      | 51.75%  |
| DIMM         | 4306      | 45.56%  |
| Row Of Chips | 218       | 2.31%   |
| Chip         | 19        | 0.2%    |
| Unknown      | 7         | 0.07%   |
| RIMM         | 5         | 0.05%   |
| FB-DIMM      | 5         | 0.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 4069      | 38.31%  |
| 8192  | 2846      | 26.8%   |
| 2048  | 2384      | 22.45%  |
| 16384 | 592       | 5.57%   |
| 1024  | 573       | 5.4%    |
| 32768 | 93        | 0.88%   |
| 512   | 57        | 0.54%   |
| 256   | 2         | 0.02%   |
| 65536 | 1         | 0.01%   |
| 3072  | 1         | 0.01%   |
| 64    | 1         | 0.01%   |
| 32    | 1         | 0.01%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 2797      | 26.11%  |
| 1333    | 1261      | 11.77%  |
| 2667    | 940       | 8.77%   |
| 2400    | 731       | 6.82%   |
| 3200    | 576       | 5.38%   |
| 1334    | 523       | 4.88%   |
| 667     | 476       | 4.44%   |
| 800     | 458       | 4.27%   |
| 2133    | 363       | 3.39%   |
| Unknown | 338       | 3.15%   |
| 1067    | 238       | 2.22%   |
| 3600    | 205       | 1.91%   |
| 1867    | 192       | 1.79%   |
| 1066    | 127       | 1.19%   |
| 1866    | 106       | 0.99%   |
| 4199    | 95        | 0.89%   |
| 2666    | 88        | 0.82%   |
| 3266    | 85        | 0.79%   |
| 2048    | 85        | 0.79%   |
| 533     | 84        | 0.78%   |
| 400     | 72        | 0.67%   |
| 4267    | 71        | 0.66%   |
| 3000    | 61        | 0.57%   |
| 1800    | 61        | 0.57%   |
| 3400    | 60        | 0.56%   |
| 975     | 57        | 0.53%   |
| 2933    | 50        | 0.47%   |
| 3466    | 46        | 0.43%   |
| 3733    | 33        | 0.31%   |
| 333     | 30        | 0.28%   |
| 3866    | 29        | 0.27%   |
| 2800    | 27        | 0.25%   |
| 3800    | 20        | 0.19%   |
| 2000    | 20        | 0.19%   |
| 1639    | 19        | 0.18%   |
| 1648    | 18        | 0.17%   |
| 49926   | 17        | 0.16%   |
| 3066    | 17        | 0.16%   |
| 8400    | 15        | 0.14%   |
| 4266    | 15        | 0.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 146       | 41.83%  |
| Brother Industries    | 66        | 18.91%  |
| Canon                 | 46        | 13.18%  |
| Samsung Electronics   | 35        | 10.03%  |
| Seiko Epson           | 28        | 8.02%   |
| Lexmark International | 7         | 2.01%   |
| QinHeng Electronics   | 4         | 1.15%   |
| Prolific Technology   | 4         | 1.15%   |
| Xerox                 | 3         | 0.86%   |
| Kyocera               | 3         | 0.86%   |
| Dymo-CoStar           | 3         | 0.86%   |
| Ricoh                 | 2         | 0.57%   |
| Oki Data              | 1         | 0.29%   |
| NXP Semiconductors    | 1         | 0.29%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| HP DeskJet 3630 series               | 7         | 1.99%   |
| HP ENVY 4520 series                  | 6         | 1.71%   |
| HP DeskJet 2620 All-in-One Printer   | 6         | 1.71%   |
| Samsung ML-1640 Series Laser Printer | 5         | 1.42%   |
| Samsung M2020 Series                 | 5         | 1.42%   |
| HP LaserJet 1020                     | 5         | 1.42%   |
| HP DeskJet 2700 series               | 5         | 1.42%   |
| Samsung M2070 Series                 | 4         | 1.14%   |
| QinHeng CH340S                       | 4         | 1.14%   |
| Prolific PL2305 Parallel Port        | 4         | 1.14%   |
| HP LaserJet P1006                    | 4         | 1.14%   |
| HP LaserJet 1018                     | 4         | 1.14%   |
| HP DeskJet 2130 series               | 4         | 1.14%   |
| Brother Printer                      | 4         | 1.14%   |
| Brother DCP-7055W                    | 4         | 1.14%   |
| Samsung SCX-3400 Series              | 3         | 0.85%   |
| HP LaserJet P1102                    | 3         | 0.85%   |
| HP LaserJet P1005                    | 3         | 0.85%   |
| HP LaserJet 1200                     | 3         | 0.85%   |
| HP LaserJet 1010                     | 3         | 0.85%   |
| HP Ink Tank Wireless 410 series      | 3         | 0.85%   |
| HP ENVY Photo 6200 series            | 3         | 0.85%   |
| HP Deskjet 1050 J410                 | 3         | 0.85%   |
| Canon PIXMA MX920 Series             | 3         | 0.85%   |
| Canon PIXMA MG2500 Series            | 3         | 0.85%   |
| Brother MFC-J470DW                   | 3         | 0.85%   |
| Seiko Epson XP-243 245 247 Series    | 2         | 0.57%   |
| Seiko Epson L365 Series              | 2         | 0.57%   |
| Seiko Epson L120 Series              | 2         | 0.57%   |
| Seiko Epson ET-4760 Series           | 2         | 0.57%   |
| Samsung ML-2010P Mono Laser Printer  | 2         | 0.57%   |
| Samsung CLP-310 Color Laser Printer  | 2         | 0.57%   |
| Kyocera ECOSYS P5021cdw              | 2         | 0.57%   |
| HP OfficeJet Pro 7720 series         | 2         | 0.57%   |
| HP OfficeJet Pro 6960                | 2         | 0.57%   |
| HP OfficeJet 6950                    | 2         | 0.57%   |
| HP LaserJet Pro M148f-M149f          | 2         | 0.57%   |
| HP LaserJet M14-M17                  | 2         | 0.57%   |
| HP LaserJet 1022                     | 2         | 0.57%   |
| HP LaserJet 1000                     | 2         | 0.57%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Canon                       | 36        | 52.94%  |
| Hewlett-Packard             | 13        | 19.12%  |
| Seiko Epson                 | 9         | 13.24%  |
| Mustek Systems              | 6         | 8.82%   |
| AGFA-Gevaert NV             | 2         | 2.94%   |
| Plustek                     | 1         | 1.47%   |
| KYE Systems (Mouse Systems) | 1         | 1.47%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 210                                  | 6         | 8.82%   |
| Canon CanoScan LiDE 110                                  | 6         | 8.82%   |
| Canon CanoScan LiDE 100                                  | 5         | 7.35%   |
| Canon CanoScan N1240U/LiDE 30                            | 3         | 4.41%   |
| Canon CanoScan LiDE 120                                  | 3         | 4.41%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 2         | 2.94%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]            | 2         | 2.94%   |
| Mustek Systems ScanExpress 1200 UB                       | 2         | 2.94%   |
| HP ScanJet 5590                                          | 2         | 2.94%   |
| HP ScanJet 4500C/5550C                                   | 2         | 2.94%   |
| Canon CanoScan N670U/N676U/LiDE 20                       | 2         | 2.94%   |
| Canon CanoScan LIDE 25                                   | 2         | 2.94%   |
| Seiko Epson Scanner                                      | 1         | 1.47%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]              | 1         | 1.47%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]  | 1         | 1.47%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]        | 1         | 1.47%   |
| Seiko Epson GT-7400U [Perfection 1270]                   | 1         | 1.47%   |
| Plustek 600DPI USB Scanner                               | 1         | 1.47%   |
| Mustek Systems SNAPSCAN e22                              | 1         | 1.47%   |
| Mustek Systems ScanExpress 1200 CU                       | 1         | 1.47%   |
| Mustek Systems BearPaw 2448 CU Pro                       | 1         | 1.47%   |
| Mustek Systems BearPaw 1200 CU Plus                      | 1         | 1.47%   |
| KYE Systems (Mouse Systems) ColorPage-Vivid4             | 1         | 1.47%   |
| HP ScanJet G4010                                         | 1         | 1.47%   |
| HP ScanJet 4570c                                         | 1         | 1.47%   |
| HP ScanJet 4370                                          | 1         | 1.47%   |
| HP ScanJet 3800c                                         | 1         | 1.47%   |
| HP ScanJet 3670                                          | 1         | 1.47%   |
| HP ScanJet 2400c                                         | 1         | 1.47%   |
| HP ScanJet 2300c                                         | 1         | 1.47%   |
| HP ScanJet 2200c                                         | 1         | 1.47%   |
| HP PSC 1200                                              | 1         | 1.47%   |
| Canon CanoScan N650U/N656U                               | 1         | 1.47%   |
| Canon CanoScan LiDE 700F                                 | 1         | 1.47%   |
| Canon CanoScan LiDE 70                                   | 1         | 1.47%   |
| Canon CanoScan LiDE 600F                                 | 1         | 1.47%   |
| Canon CanoScan LiDE 60                                   | 1         | 1.47%   |
| Canon CanoScan LiDE 500F                                 | 1         | 1.47%   |
| Canon CanoScan LiDE 220                                  | 1         | 1.47%   |
| Canon CanoScan LiDE 200                                  | 1         | 1.47%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1107      | 23.14%  |
| Realtek Semiconductor                  | 428       | 8.95%   |
| Microdia                               | 421       | 8.8%    |
| IMC Networks                           | 323       | 6.75%   |
| Acer                                   | 282       | 5.9%    |
| Suyin                                  | 269       | 5.62%   |
| Logitech                               | 248       | 5.19%   |
| Sunplus Innovation Technology          | 238       | 4.98%   |
| Cheng Uei Precision Industry (Foxlink) | 178       | 3.72%   |
| Quanta                                 | 156       | 3.26%   |
| Syntek                                 | 141       | 2.95%   |
| Apple                                  | 102       | 2.13%   |
| Silicon Motion                         | 90        | 1.88%   |
| Lite-On Technology                     | 89        | 1.86%   |
| Alcor Micro                            | 86        | 1.8%    |
| Ricoh                                  | 83        | 1.74%   |
| Microsoft                              | 52        | 1.09%   |
| Z-Star Microelectronics                | 41        | 0.86%   |
| Lenovo                                 | 41        | 0.86%   |
| Importek                               | 32        | 0.67%   |
| ALi                                    | 32        | 0.67%   |
| Primax Electronics                     | 27        | 0.56%   |
| Luxvisions Innotech Limited            | 26        | 0.54%   |
| GEMBIRD                                | 18        | 0.38%   |
| DigiTech                               | 16        | 0.33%   |
| Samsung Electronics                    | 15        | 0.31%   |
| Generalplus Technology                 | 14        | 0.29%   |
| Cubeternet                             | 14        | 0.29%   |
| Aveo Technology                        | 14        | 0.29%   |
| KYE Systems (Mouse Systems)            | 13        | 0.27%   |
| Sonix Technology                       | 12        | 0.25%   |
| OmniVision Technologies                | 11        | 0.23%   |
| Genesys Logic                          | 11        | 0.23%   |
| Creative Technology                    | 11        | 0.23%   |
| ARC International                      | 10        | 0.21%   |
| Unknown                                | 8         | 0.17%   |
| Huawei Technologies                    | 8         | 0.17%   |
| Trust                                  | 7         | 0.15%   |
| Sunplus Technology                     | 7         | 0.15%   |
| Hewlett-Packard                        | 7         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 134       | 2.78%   |
| Chicony Integrated Camera                               | 118       | 2.45%   |
| Chicony HD WebCam                                       | 113       | 2.34%   |
| Realtek Integrated_Webcam_HD                            | 90        | 1.87%   |
| Sunplus Integrated_Webcam_HD                            | 77        | 1.6%    |
| IMC Networks USB2.0 VGA UVC WebCam                      | 67        | 1.39%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 64        | 1.33%   |
| Realtek Integrated_Webcam_5M                            | 59        | 1.22%   |
| Logitech Webcam C270                                    | 59        | 1.22%   |
| Chicony USB 2.0 Camera                                  | 59        | 1.22%   |
| Realtek USB Camera                                      | 58        | 1.2%    |
| Syntek Integrated Camera                                | 52        | 1.08%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 52        | 1.08%   |
| Microdia Integrated Webcam                              | 49        | 1.02%   |
| IMC Networks Integrated Camera                          | 49        | 1.02%   |
| Chicony VGA WebCam                                      | 49        | 1.02%   |
| Acer Integrated Camera                                  | 49        | 1.02%   |
| Acer Lenovo EasyCamera                                  | 47        | 0.97%   |
| Chicony USB2.0 HD UVC WebCam                            | 41        | 0.85%   |
| Apple Built-in iSight                                   | 40        | 0.83%   |
| Chicony TOSHIBA Web Camera - HD                         | 39        | 0.81%   |
| Alcor Micro USB 2.0 Camera                              | 39        | 0.81%   |
| Chicony Lenovo EasyCamera                               | 37        | 0.77%   |
| Chicony HP TrueVision HD                                | 37        | 0.77%   |
| Suyin Integrated_Webcam_HD                              | 36        | 0.75%   |
| Sunplus HD WebCam                                       | 36        | 0.75%   |
| Chicony EasyCamera                                      | 36        | 0.75%   |
| Syntek Lenovo EasyCamera                                | 35        | 0.73%   |
| Chicony USB2.0 VGA UVC WebCam                           | 35        | 0.73%   |
| Logitech HD Pro Webcam C920                             | 33        | 0.68%   |
| Lite-On Integrated Camera                               | 32        | 0.66%   |
| Acer Lenovo Integrated Webcam                           | 32        | 0.66%   |
| Chicony FJ Camera                                       | 31        | 0.64%   |
| Syntek EasyCamera                                       | 29        | 0.6%    |
| Chicony HP Webcam                                       | 29        | 0.6%    |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 29        | 0.6%    |
| IMC Networks UVC VGA Webcam                             | 28        | 0.58%   |
| Chicony HP TrueVision HD Camera                         | 28        | 0.58%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 28        | 0.58%   |
| Acer EasyCamera                                         | 28        | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 197       | 37.74%  |
| AuthenTec                  | 85        | 16.28%  |
| Upek                       | 60        | 11.49%  |
| Synaptics                  | 52        | 9.96%   |
| Elan Microelectronics      | 39        | 7.47%   |
| Shenzhen Goodix Technology | 36        | 6.9%    |
| LighTuning Technology      | 26        | 4.98%   |
| STMicroelectronics         | 23        | 4.41%   |
| Focal-systems.Corp         | 2         | 0.38%   |
| Samsung Electronics        | 1         | 0.19%   |
| HOLTEK                     | 1         | 0.19%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 55        | 10.54%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 36        | 6.9%    |
| AuthenTec AES2810                                                          | 30        | 5.75%   |
| Shenzhen Goodix  Fingerprint Device                                        | 26        | 4.98%   |
| Elan ELAN:Fingerprint                                                      | 25        | 4.79%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 23        | 4.41%   |
| STMicroelectronics Fingerprint Reader                                      | 23        | 4.41%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 23        | 4.41%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 20        | 3.83%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 18        | 3.45%   |
| Validity Sensors VFS491                                                    | 17        | 3.26%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 14        | 2.68%   |
| Elan ELAN:ARM-M4                                                           | 14        | 2.68%   |
| AuthenTec AES1600                                                          | 14        | 2.68%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 13        | 2.49%   |
| Synaptics  WBDI                                                            | 13        | 2.49%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 12        | 2.3%    |
| AuthenTec Fingerprint Sensor                                               | 12        | 2.3%    |
| Unknown                                                                    | 12        | 2.3%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 11        | 2.11%   |
| Validity Sensors Fingerprint scanner                                       | 11        | 2.11%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 11        | 2.11%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 10        | 1.92%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 8         | 1.53%   |
| Shenzhen Goodix Fingerprint Reader                                         | 8         | 1.53%   |
| Validity Sensors Synaptics WBDI                                            | 7         | 1.34%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 6         | 1.15%   |
| Upek TCS5B Fingerprint sensor                                              | 5         | 0.96%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 5         | 0.96%   |
| Validity Sensors VFS Fingerprint sensor                                    | 4         | 0.77%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 4         | 0.77%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 3         | 0.57%   |
| Synaptics WBDI Device                                                      | 3         | 0.57%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 0.57%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 0.57%   |
| LighTuning Fingerprint Reader                                              | 3         | 0.57%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.38%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 0.38%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 0.38%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 0.38%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 163       | 51.1%   |
| Alcor Micro                       | 44        | 13.79%  |
| O2 Micro                          | 41        | 12.85%  |
| Lenovo                            | 24        | 7.52%   |
| Upek                              | 21        | 6.58%   |
| SCM Microsystems                  | 6         | 1.88%   |
| Gemalto (was Gemplus)             | 4         | 1.25%   |
| Realtek Semiconductor             | 3         | 0.94%   |
| OmniKey                           | 3         | 0.94%   |
| BIT4ID                            | 2         | 0.63%   |
| VASCO Data Security International | 1         | 0.31%   |
| Reiner SCT Kartensysteme          | 1         | 0.31%   |
| Microchip Technology              | 1         | 0.31%   |
| Hewlett-Packard                   | 1         | 0.31%   |
| Fujitsu Siemens Computers         | 1         | 0.31%   |
| Cherry                            | 1         | 0.31%   |
| Aladdin Knowledge Systems         | 1         | 0.31%   |
| Advanced Card Systems             | 1         | 0.31%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 91        | 28.53%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 42        | 13.17%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 41        | 12.85%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 40        | 12.54%  |
| Lenovo Integrated Smart Card Reader                                          | 24        | 7.52%   |
| Broadcom 5880                                                                | 24        | 7.52%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 21        | 6.58%   |
| Broadcom 58200                                                               | 5         | 1.57%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 3         | 0.94%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 3         | 0.94%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 0.63%   |
| BIT4ID miniLector EVO                                                        | 2         | 0.63%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 0.63%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.31%   |
| SCM Microsystems SCR335 SmartCard Reader                                     | 1         | 0.31%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.31%   |
| SCM Microsystems CLOUD 2700 F Smart Card Reader                              | 1         | 0.31%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.31%   |
| OmniKey CardMan 4321                                                         | 1         | 0.31%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.31%   |
| OmniKey CardMan 1021                                                         | 1         | 0.31%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.31%   |
| Microchip Technology SMSC USX101x Reader                                     | 1         | 0.31%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.31%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.31%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.31%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.31%   |
| Cherry Smart Terminal XX44                                                   | 1         | 0.31%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.31%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.31%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.31%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.31%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 8028      | 84.04%  |
| 1     | 1338      | 14.01%  |
| 2     | 172       | 1.8%    |
| 3     | 11        | 0.12%   |
| 6     | 2         | 0.02%   |
| 7     | 1         | 0.01%   |
| 4     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 522       | 30.69%  |
| Chipcard                 | 309       | 18.17%  |
| Graphics card            | 287       | 16.87%  |
| Net/wireless             | 175       | 10.29%  |
| Multimedia controller    | 107       | 6.29%   |
| Bluetooth                | 83        | 4.88%   |
| Storage                  | 59        | 3.47%   |
| Communication controller | 43        | 2.53%   |
| Camera                   | 38        | 2.23%   |
| Unassigned class         | 29        | 1.7%    |
| Network                  | 11        | 0.65%   |
| Sound                    | 10        | 0.59%   |
| Card reader              | 8         | 0.47%   |
| Flash memory             | 5         | 0.29%   |
| Wireless                 | 4         | 0.24%   |
| Modem                    | 4         | 0.24%   |
| Storage/ata              | 2         | 0.12%   |
| Net/ethernet             | 2         | 0.12%   |
| Unclassified device      | 1         | 0.06%   |
| Storage/raid             | 1         | 0.06%   |
| Dvb card                 | 1         | 0.06%   |

