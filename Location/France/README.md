Linux in France - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in France.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/France/Desktop/README.md) and [notebooks](/Location/France/Notebook/README.md).

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

Total: 11121

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | Pavilion dv6                | Notebook    | [30ec83dbd4](https://linux-hardware.org/?probe=30ec83dbd4) | Dec 31, 2022 |
| ASUSTek       | PRIME B250M-K               | Desktop     | [9db6f0fda7](https://linux-hardware.org/?probe=9db6f0fda7) | Dec 31, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [ac397dc318](https://linux-hardware.org/?probe=ac397dc318) | Dec 31, 2022 |
| ASRock        | B550 Steel Legend           | Desktop     | [8705e10ac6](https://linux-hardware.org/?probe=8705e10ac6) | Dec 31, 2022 |
| Acer          | Aspire A514-54              | Notebook    | [5775c77a91](https://linux-hardware.org/?probe=5775c77a91) | Dec 31, 2022 |
| HP            | Laptop 17-cn1xxx            | Notebook    | [dde4bcd574](https://linux-hardware.org/?probe=dde4bcd574) | Dec 30, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [d44828a455](https://linux-hardware.org/?probe=d44828a455) | Dec 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [afa28ba4f3](https://linux-hardware.org/?probe=afa28ba4f3) | Dec 30, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [43f808e1e4](https://linux-hardware.org/?probe=43f808e1e4) | Dec 30, 2022 |
| Dell          | 05KX61 A00                  | Server      | [9f365307f3](https://linux-hardware.org/?probe=9f365307f3) | Dec 30, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [6de26a316e](https://linux-hardware.org/?probe=6de26a316e) | Dec 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [80abf89bc6](https://linux-hardware.org/?probe=80abf89bc6) | Dec 30, 2022 |
| MSI           | H61M-P22                    | Desktop     | [23b5356c0a](https://linux-hardware.org/?probe=23b5356c0a) | Dec 30, 2022 |
| ASRock        | 960GM-GS3 FX                | Desktop     | [1d8b5f0509](https://linux-hardware.org/?probe=1d8b5f0509) | Dec 30, 2022 |
| Intel         | NUC8BEB J72688-308          | Mini pc     | [b4a7d759f7](https://linux-hardware.org/?probe=b4a7d759f7) | Dec 30, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [0842d26251](https://linux-hardware.org/?probe=0842d26251) | Dec 30, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [d91b55f9f1](https://linux-hardware.org/?probe=d91b55f9f1) | Dec 30, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [47f838ca34](https://linux-hardware.org/?probe=47f838ca34) | Dec 30, 2022 |
| Intel         | NUC8BEB J72688-308          | Mini pc     | [d3daa756b4](https://linux-hardware.org/?probe=d3daa756b4) | Dec 30, 2022 |
| Gigabyte      | Z490I AORUS ULTRA           | Desktop     | [6cf8d26754](https://linux-hardware.org/?probe=6cf8d26754) | Dec 30, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [b0bfa9530a](https://linux-hardware.org/?probe=b0bfa9530a) | Dec 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [ce66958f69](https://linux-hardware.org/?probe=ce66958f69) | Dec 29, 2022 |
| ASUSTek       | G1                          | Notebook    | [1f8e426f96](https://linux-hardware.org/?probe=1f8e426f96) | Dec 29, 2022 |
| Toshiba       | Satellite C870-13V          | Notebook    | [5ad370d470](https://linux-hardware.org/?probe=5ad370d470) | Dec 29, 2022 |
| Acer          | Aspire 4820TG               | Notebook    | [77721c13c4](https://linux-hardware.org/?probe=77721c13c4) | Dec 29, 2022 |
| ASUSTek       | GL553VD                     | Notebook    | [9c4eab8774](https://linux-hardware.org/?probe=9c4eab8774) | Dec 29, 2022 |
| HP            | Pavilion 17                 | Notebook    | [4a8c3f4014](https://linux-hardware.org/?probe=4a8c3f4014) | Dec 29, 2022 |
| Shenzhen W... | TANK56                      | Notebook    | [4cd3e6c8e4](https://linux-hardware.org/?probe=4cd3e6c8e4) | Dec 29, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [6ece20ec58](https://linux-hardware.org/?probe=6ece20ec58) | Dec 29, 2022 |
| Acer          | Aspire X3960                | Desktop     | [f045d61192](https://linux-hardware.org/?probe=f045d61192) | Dec 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [499c91958a](https://linux-hardware.org/?probe=499c91958a) | Dec 29, 2022 |
| Acer          | Aspire X3960                | Desktop     | [75e053c90f](https://linux-hardware.org/?probe=75e053c90f) | Dec 29, 2022 |
| Dell          | 0T10XW A01                  | Desktop     | [8b16a66b73](https://linux-hardware.org/?probe=8b16a66b73) | Dec 29, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [b915fc0d47](https://linux-hardware.org/?probe=b915fc0d47) | Dec 28, 2022 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | Notebook    | [74c1f3a4c2](https://linux-hardware.org/?probe=74c1f3a4c2) | Dec 28, 2022 |
| ASRock        | H61M-ITX                    | Desktop     | [0ee8e9bb5b](https://linux-hardware.org/?probe=0ee8e9bb5b) | Dec 28, 2022 |
| ASUSTek       | X555BP                      | Notebook    | [6ddc84aa0d](https://linux-hardware.org/?probe=6ddc84aa0d) | Dec 28, 2022 |
| Dell          | 0YXT71 A01                  | Desktop     | [ed5e31a6bc](https://linux-hardware.org/?probe=ed5e31a6bc) | Dec 28, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [2966924363](https://linux-hardware.org/?probe=2966924363) | Dec 28, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [f3e27d230f](https://linux-hardware.org/?probe=f3e27d230f) | Dec 28, 2022 |
| Toshiba       | PORTEGE Z30T-A              | Notebook    | [cab72e8a11](https://linux-hardware.org/?probe=cab72e8a11) | Dec 28, 2022 |
| Dell          | G3 3500                     | Notebook    | [78e803b44e](https://linux-hardware.org/?probe=78e803b44e) | Dec 28, 2022 |
| ASUSTek       | PRIME B360M-K               | Desktop     | [48f161dfc8](https://linux-hardware.org/?probe=48f161dfc8) | Dec 27, 2022 |
| MSI           | GE62 2QC                    | Notebook    | [dbd69d70ac](https://linux-hardware.org/?probe=dbd69d70ac) | Dec 27, 2022 |
| MSI           | GP62 7QF                    | Notebook    | [3db82bd91e](https://linux-hardware.org/?probe=3db82bd91e) | Dec 27, 2022 |
| ASUSTek       | G56JR                       | Notebook    | [3acee33976](https://linux-hardware.org/?probe=3acee33976) | Dec 27, 2022 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [31f25029c1](https://linux-hardware.org/?probe=31f25029c1) | Dec 27, 2022 |
| Acer          | Aspire SW3-013              | Notebook    | [04286c0e93](https://linux-hardware.org/?probe=04286c0e93) | Dec 27, 2022 |
| Dell          | Inspiron 5579               | Notebook    | [6fbb0cbd09](https://linux-hardware.org/?probe=6fbb0cbd09) | Dec 27, 2022 |
| Dell          | Inspiron 5579               | Notebook    | [838cda532a](https://linux-hardware.org/?probe=838cda532a) | Dec 27, 2022 |
| Gigabyte      | 970-GAMING                  | Desktop     | [4a2d0b56d6](https://linux-hardware.org/?probe=4a2d0b56d6) | Dec 27, 2022 |
| Notebook      | L14xMU                      | Notebook    | [7644bc65e2](https://linux-hardware.org/?probe=7644bc65e2) | Dec 27, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [8ecb7e11b3](https://linux-hardware.org/?probe=8ecb7e11b3) | Dec 26, 2022 |
| Dell          | Inspiron 1012               | Notebook    | [3dd6b8a416](https://linux-hardware.org/?probe=3dd6b8a416) | Dec 26, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [f7c9b3538e](https://linux-hardware.org/?probe=f7c9b3538e) | Dec 26, 2022 |
| Gigabyte      | Z690 AORUS MASTER           | Desktop     | [ebf2a443c2](https://linux-hardware.org/?probe=ebf2a443c2) | Dec 26, 2022 |
| Acer          | Veriton NBU                 | Desktop     | [cca454d1bd](https://linux-hardware.org/?probe=cca454d1bd) | Dec 26, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [6703f01cfc](https://linux-hardware.org/?probe=6703f01cfc) | Dec 26, 2022 |
| ASUSTek       | K61IC                       | Notebook    | [4c34b8d5a1](https://linux-hardware.org/?probe=4c34b8d5a1) | Dec 26, 2022 |
| Lenovo        | Legion 5 15IAH7H 82RB       | Notebook    | [e47f890444](https://linux-hardware.org/?probe=e47f890444) | Dec 26, 2022 |
| Lenovo        | Legion 5 15IAH7H 82RB       | Notebook    | [c288ade12d](https://linux-hardware.org/?probe=c288ade12d) | Dec 26, 2022 |
| Dell          | 0H21J3 A07                  | Server      | [93e8563379](https://linux-hardware.org/?probe=93e8563379) | Dec 26, 2022 |
| Gigabyte      | 970-GAMING                  | Desktop     | [9df04c213d](https://linux-hardware.org/?probe=9df04c213d) | Dec 26, 2022 |
| HP            | 2AF7                        | Desktop     | [96344d97ba](https://linux-hardware.org/?probe=96344d97ba) | Dec 26, 2022 |
| Lenovo        | ThinkPad X250 20CLS1UB00    | Notebook    | [fc8b2899fa](https://linux-hardware.org/?probe=fc8b2899fa) | Dec 25, 2022 |
| MSI           | CR700                       | Notebook    | [92b97fec48](https://linux-hardware.org/?probe=92b97fec48) | Dec 25, 2022 |
| Intel         | NUC6CAYB J23203-405         | Mini pc     | [964f42356a](https://linux-hardware.org/?probe=964f42356a) | Dec 25, 2022 |
| MSI           | CR700                       | Notebook    | [df25c10894](https://linux-hardware.org/?probe=df25c10894) | Dec 25, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [5497596ef1](https://linux-hardware.org/?probe=5497596ef1) | Dec 25, 2022 |
| HONOR         | BOD-WXX9                    | Notebook    | [894521b876](https://linux-hardware.org/?probe=894521b876) | Dec 25, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [26c346f0ab](https://linux-hardware.org/?probe=26c346f0ab) | Dec 25, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [08af6df0dd](https://linux-hardware.org/?probe=08af6df0dd) | Dec 25, 2022 |
| HP            | ENVY 17                     | Notebook    | [f3458ee7d5](https://linux-hardware.org/?probe=f3458ee7d5) | Dec 25, 2022 |
| Dell          | 0MN1TX A02                  | Desktop     | [513af674c0](https://linux-hardware.org/?probe=513af674c0) | Dec 25, 2022 |
| HP            | ENVY Notebook               | Notebook    | [16af8b4da3](https://linux-hardware.org/?probe=16af8b4da3) | Dec 25, 2022 |
| Lenovo        | ThinkPad L530 24781P9       | Notebook    | [fd8de03405](https://linux-hardware.org/?probe=fd8de03405) | Dec 25, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [d66772a936](https://linux-hardware.org/?probe=d66772a936) | Dec 25, 2022 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [9d8bce4c41](https://linux-hardware.org/?probe=9d8bce4c41) | Dec 25, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [1762f53462](https://linux-hardware.org/?probe=1762f53462) | Dec 25, 2022 |
| Lenovo        | ThinkPad X220 4291UUC       | Notebook    | [6307be520e](https://linux-hardware.org/?probe=6307be520e) | Dec 25, 2022 |
| Gigabyte      | 970-GAMING                  | Desktop     | [ef0c06d132](https://linux-hardware.org/?probe=ef0c06d132) | Dec 25, 2022 |
| Gigabyte      | 970-GAMING                  | Desktop     | [9de3d146ff](https://linux-hardware.org/?probe=9de3d146ff) | Dec 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [a1f4999c28](https://linux-hardware.org/?probe=a1f4999c28) | Dec 25, 2022 |
| Toshiba       | Satellite C650              | Notebook    | [89b85889f9](https://linux-hardware.org/?probe=89b85889f9) | Dec 25, 2022 |
| ASUSTek       | G751JT                      | Notebook    | [16e989ff99](https://linux-hardware.org/?probe=16e989ff99) | Dec 25, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [42221f61fb](https://linux-hardware.org/?probe=42221f61fb) | Dec 25, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [6c809c224c](https://linux-hardware.org/?probe=6c809c224c) | Dec 24, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [8df9791e32](https://linux-hardware.org/?probe=8df9791e32) | Dec 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [2b71327126](https://linux-hardware.org/?probe=2b71327126) | Dec 24, 2022 |
| Lenovo        | ThinkPad T470s 20HGS0AY0... | Notebook    | [28e67f37bc](https://linux-hardware.org/?probe=28e67f37bc) | Dec 24, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | Notebook    | [dab48b870c](https://linux-hardware.org/?probe=dab48b870c) | Dec 23, 2022 |
| HP            | Pavilion 17                 | Notebook    | [0adc0d708b](https://linux-hardware.org/?probe=0adc0d708b) | Dec 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [0d1532282f](https://linux-hardware.org/?probe=0d1532282f) | Dec 23, 2022 |
| Dell          | 0J3C2F A00                  | Desktop     | [f993ebb9ed](https://linux-hardware.org/?probe=f993ebb9ed) | Dec 23, 2022 |
| Acer          | E1-510                      | Notebook    | [463c668d4e](https://linux-hardware.org/?probe=463c668d4e) | Dec 23, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [97749ab6b4](https://linux-hardware.org/?probe=97749ab6b4) | Dec 23, 2022 |
| ASRock        | H270 Pro4                   | Desktop     | [548ba72d05](https://linux-hardware.org/?probe=548ba72d05) | Dec 23, 2022 |
| Acer          | TravelMate 7730             | Notebook    | [8d166266b9](https://linux-hardware.org/?probe=8d166266b9) | Dec 23, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [41ec48c0e5](https://linux-hardware.org/?probe=41ec48c0e5) | Dec 23, 2022 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [e2e9b14a43](https://linux-hardware.org/?probe=e2e9b14a43) | Dec 23, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [bc197d71d8](https://linux-hardware.org/?probe=bc197d71d8) | Dec 23, 2022 |
| Danew         | Dbook 131                   | Notebook    | [25dbe464cd](https://linux-hardware.org/?probe=25dbe464cd) | Dec 23, 2022 |
| HP            | ProBook 440 G7              | Notebook    | [33a03f23cc](https://linux-hardware.org/?probe=33a03f23cc) | Dec 23, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [841b610817](https://linux-hardware.org/?probe=841b610817) | Dec 23, 2022 |
| Dell          | Inspiron 1546               | Notebook    | [7812af7998](https://linux-hardware.org/?probe=7812af7998) | Dec 23, 2022 |
| Unknown       | Unknown                     | Notebook    | [f9c4fecaf4](https://linux-hardware.org/?probe=f9c4fecaf4) | Dec 23, 2022 |
| Unknown       | Unknown                     | Notebook    | [3832db2827](https://linux-hardware.org/?probe=3832db2827) | Dec 23, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [360e473cf9](https://linux-hardware.org/?probe=360e473cf9) | Dec 22, 2022 |
| HP            | EliteBook x360 1040 G8 N... | Convertible | [7794581d04](https://linux-hardware.org/?probe=7794581d04) | Dec 22, 2022 |
| Dell          | 0YJPT1 A00                  | Desktop     | [f78b9b1a90](https://linux-hardware.org/?probe=f78b9b1a90) | Dec 22, 2022 |
| Lenovo        | IdeaPad 700-17ISK 80RV      | Notebook    | [59bf9e85bf](https://linux-hardware.org/?probe=59bf9e85bf) | Dec 22, 2022 |
| HP            | Pavilion 17                 | Notebook    | [65dcf1eead](https://linux-hardware.org/?probe=65dcf1eead) | Dec 22, 2022 |
| ASUSTek       | X555LF                      | Notebook    | [bed000b293](https://linux-hardware.org/?probe=bed000b293) | Dec 22, 2022 |
| Acer          | Predator PO3-600 V:1.1      | Desktop     | [4a49555de6](https://linux-hardware.org/?probe=4a49555de6) | Dec 22, 2022 |
| Acer          | Predator PO3-600 V:1.1      | Desktop     | [8cb7f41543](https://linux-hardware.org/?probe=8cb7f41543) | Dec 22, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [5bbf457036](https://linux-hardware.org/?probe=5bbf457036) | Dec 22, 2022 |
| ASUSTek       | 1015BXO                     | Notebook    | [7cce9a65ec](https://linux-hardware.org/?probe=7cce9a65ec) | Dec 22, 2022 |
| Gigabyte      | Z490I AORUS ULTRA           | Desktop     | [de140c1edd](https://linux-hardware.org/?probe=de140c1edd) | Dec 22, 2022 |
| HP            | 81C9                        | Desktop     | [cb40ddba01](https://linux-hardware.org/?probe=cb40ddba01) | Dec 22, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [be01b942ed](https://linux-hardware.org/?probe=be01b942ed) | Dec 22, 2022 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | Notebook    | [16cae3015a](https://linux-hardware.org/?probe=16cae3015a) | Dec 21, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [28013105ef](https://linux-hardware.org/?probe=28013105ef) | Dec 21, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [f39488c597](https://linux-hardware.org/?probe=f39488c597) | Dec 21, 2022 |
| MSI           | H97M-G43                    | Desktop     | [a34bd69442](https://linux-hardware.org/?probe=a34bd69442) | Dec 21, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [0243df6ce4](https://linux-hardware.org/?probe=0243df6ce4) | Dec 21, 2022 |
| Acer          | ERC410M                     | Desktop     | [e25233896a](https://linux-hardware.org/?probe=e25233896a) | Dec 21, 2022 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [6ec5c4fc19](https://linux-hardware.org/?probe=6ec5c4fc19) | Dec 21, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [47ac3ac319](https://linux-hardware.org/?probe=47ac3ac319) | Dec 21, 2022 |
| Gigabyte      | H170M-DS3H-CF               | Desktop     | [714dafad38](https://linux-hardware.org/?probe=714dafad38) | Dec 21, 2022 |
| MSI           | MAG B560M MORTAR            | Desktop     | [9b1e668d0a](https://linux-hardware.org/?probe=9b1e668d0a) | Dec 21, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [fd0cb86f82](https://linux-hardware.org/?probe=fd0cb86f82) | Dec 21, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [57182d09ed](https://linux-hardware.org/?probe=57182d09ed) | Dec 21, 2022 |
| ASUSTek       | VivoBook S14 X411UF         | Notebook    | [894f0ab5df](https://linux-hardware.org/?probe=894f0ab5df) | Dec 21, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [827c7f9bd3](https://linux-hardware.org/?probe=827c7f9bd3) | Dec 21, 2022 |
| Acer          | Aspire 7730ZG               | Notebook    | [bf9325456e](https://linux-hardware.org/?probe=bf9325456e) | Dec 20, 2022 |
| MSI           | GS73VR 7RF                  | Notebook    | [7f37920146](https://linux-hardware.org/?probe=7f37920146) | Dec 20, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [c0f4dfeb74](https://linux-hardware.org/?probe=c0f4dfeb74) | Dec 20, 2022 |
| Timi          | TM1701                      | Notebook    | [49f0865503](https://linux-hardware.org/?probe=49f0865503) | Dec 20, 2022 |
| Acer          | TravelMate 7730             | Notebook    | [8078925015](https://linux-hardware.org/?probe=8078925015) | Dec 20, 2022 |
| Gigabyte      | H61M-USB3V                  | Desktop     | [3161a64c4b](https://linux-hardware.org/?probe=3161a64c4b) | Dec 19, 2022 |
| LG Electro... | 17Z90P-G.AA56F              | Notebook    | [fa43417151](https://linux-hardware.org/?probe=fa43417151) | Dec 19, 2022 |
| ASUSTek       | S551LN                      | Notebook    | [df4a754b5d](https://linux-hardware.org/?probe=df4a754b5d) | Dec 19, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [1e7aff6742](https://linux-hardware.org/?probe=1e7aff6742) | Dec 19, 2022 |
| ASUSTek       | X75VC                       | Notebook    | [a16ed79c3d](https://linux-hardware.org/?probe=a16ed79c3d) | Dec 19, 2022 |
| ASUSTek       | X550MD                      | Notebook    | [16f09c5918](https://linux-hardware.org/?probe=16f09c5918) | Dec 19, 2022 |
| Lenovo        | ThinkCentre M70E 0830W4E    | Desktop     | [199c8776ef](https://linux-hardware.org/?probe=199c8776ef) | Dec 18, 2022 |
| Dell          | Inspiron 7720               | Notebook    | [f29071b4a8](https://linux-hardware.org/?probe=f29071b4a8) | Dec 18, 2022 |
| MSI           | Z87M GAMING                 | Desktop     | [bf27014217](https://linux-hardware.org/?probe=bf27014217) | Dec 18, 2022 |
| HP            | ProBook 4720s               | Notebook    | [cd684d5dbe](https://linux-hardware.org/?probe=cd684d5dbe) | Dec 18, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [e0f5a5db4c](https://linux-hardware.org/?probe=e0f5a5db4c) | Dec 18, 2022 |
| HP            | EliteBook 850 G3            | Notebook    | [72eccc0663](https://linux-hardware.org/?probe=72eccc0663) | Dec 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [83887c3224](https://linux-hardware.org/?probe=83887c3224) | Dec 18, 2022 |
| Gigabyte      | H310M S2H                   | Desktop     | [ed996739df](https://linux-hardware.org/?probe=ed996739df) | Dec 18, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [7895ac3dc1](https://linux-hardware.org/?probe=7895ac3dc1) | Dec 17, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [ed5d3570ef](https://linux-hardware.org/?probe=ed5d3570ef) | Dec 17, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [f15a27fd5e](https://linux-hardware.org/?probe=f15a27fd5e) | Dec 17, 2022 |
| Acer          | Aspire A317-51K             | Notebook    | [b02c6dccc2](https://linux-hardware.org/?probe=b02c6dccc2) | Dec 17, 2022 |
| Packard Be... | PT890-8237A                 | Desktop     | [bb9e8d2cd7](https://linux-hardware.org/?probe=bb9e8d2cd7) | Dec 17, 2022 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [278cdcd567](https://linux-hardware.org/?probe=278cdcd567) | Dec 17, 2022 |
| Toshiba       | Satellite C50D-A-12M        | Notebook    | [fa522940dd](https://linux-hardware.org/?probe=fa522940dd) | Dec 17, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [1e2531fdf1](https://linux-hardware.org/?probe=1e2531fdf1) | Dec 17, 2022 |
| Gigabyte      | F2A55M-DS2                  | Desktop     | [a38c2f49be](https://linux-hardware.org/?probe=a38c2f49be) | Dec 17, 2022 |
| Notebook      | W65_67SZ                    | Notebook    | [770c00f7d9](https://linux-hardware.org/?probe=770c00f7d9) | Dec 17, 2022 |
| HP            | Notebook                    | Notebook    | [844d855f78](https://linux-hardware.org/?probe=844d855f78) | Dec 17, 2022 |
| HP            | EliteBook 840 G4            | Notebook    | [25b640f2ed](https://linux-hardware.org/?probe=25b640f2ed) | Dec 16, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [00c328990f](https://linux-hardware.org/?probe=00c328990f) | Dec 16, 2022 |
| MSI           | X370 GAMING PLUS            | Desktop     | [893af38c43](https://linux-hardware.org/?probe=893af38c43) | Dec 16, 2022 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [1a8c883ac5](https://linux-hardware.org/?probe=1a8c883ac5) | Dec 16, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [3d5598a5eb](https://linux-hardware.org/?probe=3d5598a5eb) | Dec 16, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [f58cc5bcba](https://linux-hardware.org/?probe=f58cc5bcba) | Dec 16, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [655350654a](https://linux-hardware.org/?probe=655350654a) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [db670caadd](https://linux-hardware.org/?probe=db670caadd) | Dec 16, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [e80c6cf1e1](https://linux-hardware.org/?probe=e80c6cf1e1) | Dec 16, 2022 |
| Gigabyte      | H310M S2H                   | Desktop     | [2c008886c6](https://linux-hardware.org/?probe=2c008886c6) | Dec 16, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [719f489e01](https://linux-hardware.org/?probe=719f489e01) | Dec 15, 2022 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [ff5206e8e0](https://linux-hardware.org/?probe=ff5206e8e0) | Dec 15, 2022 |
| Dell          | Latitude E6430              | Notebook    | [1da4bd3e02](https://linux-hardware.org/?probe=1da4bd3e02) | Dec 15, 2022 |
| HP            | Presario CQ62               | Notebook    | [fce21eae2c](https://linux-hardware.org/?probe=fce21eae2c) | Dec 15, 2022 |
| ZOTAC         | ION                         | Desktop     | [f02f6b8382](https://linux-hardware.org/?probe=f02f6b8382) | Dec 15, 2022 |
| Intel         | NUC11TNBv7 K87766-405       | Mini pc     | [94d4fe9a93](https://linux-hardware.org/?probe=94d4fe9a93) | Dec 15, 2022 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [ffe60f958c](https://linux-hardware.org/?probe=ffe60f958c) | Dec 15, 2022 |
| ASRock        | FM2A78 Pro4+                | Desktop     | [51ea57e65f](https://linux-hardware.org/?probe=51ea57e65f) | Dec 15, 2022 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [31bf14c8d8](https://linux-hardware.org/?probe=31bf14c8d8) | Dec 15, 2022 |
| HP            | 2AFB                        | Desktop     | [4c57ea0ee7](https://linux-hardware.org/?probe=4c57ea0ee7) | Dec 15, 2022 |
| ASRock        | H310CM-HDV                  | Desktop     | [8f21b4e9c9](https://linux-hardware.org/?probe=8f21b4e9c9) | Dec 14, 2022 |
| ASRock        | H310CM-HDV                  | Desktop     | [b3c5f73f5a](https://linux-hardware.org/?probe=b3c5f73f5a) | Dec 14, 2022 |
| Toshiba       | Satellite Pro L300          | Notebook    | [6db5b50a6b](https://linux-hardware.org/?probe=6db5b50a6b) | Dec 14, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [02067db7ad](https://linux-hardware.org/?probe=02067db7ad) | Dec 14, 2022 |
| Apple         | MacBookPro5,4               | Notebook    | [902c809015](https://linux-hardware.org/?probe=902c809015) | Dec 14, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [db7a82e46c](https://linux-hardware.org/?probe=db7a82e46c) | Dec 14, 2022 |
| ASRock        | FM2A78 Pro4+                | Desktop     | [cb63c9ad7f](https://linux-hardware.org/?probe=cb63c9ad7f) | Dec 14, 2022 |
| Dell          | 0H8367                      | Desktop     | [7fff4bfffc](https://linux-hardware.org/?probe=7fff4bfffc) | Dec 14, 2022 |
| Toshiba       | PORTEGE R830                | Notebook    | [0d5af64ca4](https://linux-hardware.org/?probe=0d5af64ca4) | Dec 14, 2022 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [9bc1aec0dc](https://linux-hardware.org/?probe=9bc1aec0dc) | Dec 14, 2022 |
| Dell          | Latitude E7450              | Notebook    | [196b96ea5e](https://linux-hardware.org/?probe=196b96ea5e) | Dec 14, 2022 |
| Optimized ... | KVM                         | Desktop     | [d62625a751](https://linux-hardware.org/?probe=d62625a751) | Dec 13, 2022 |
| ASUSTek       | A88XM-A                     | Desktop     | [64176404e2](https://linux-hardware.org/?probe=64176404e2) | Dec 13, 2022 |
| HP            | 304Ah                       | Desktop     | [d8b600f39e](https://linux-hardware.org/?probe=d8b600f39e) | Dec 13, 2022 |
| Intel         | DH61AG AAG23736-505         | Desktop     | [352a377398](https://linux-hardware.org/?probe=352a377398) | Dec 13, 2022 |
| ASUSTek       | X705UAP                     | Notebook    | [8080afc7d4](https://linux-hardware.org/?probe=8080afc7d4) | Dec 13, 2022 |
| MSI           | MAG B660 TOMAHAWK WIFI      | Desktop     | [1beb5ff3c4](https://linux-hardware.org/?probe=1beb5ff3c4) | Dec 13, 2022 |
| Medion        | H61H2-LM3                   | Desktop     | [af98dc76b3](https://linux-hardware.org/?probe=af98dc76b3) | Dec 12, 2022 |
| Acer          | Nitro AN517-54              | Notebook    | [3896296ad1](https://linux-hardware.org/?probe=3896296ad1) | Dec 12, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [9704c6b7c4](https://linux-hardware.org/?probe=9704c6b7c4) | Dec 12, 2022 |
| Acer          | Aspire A515-56              | Notebook    | [5437de2b1b](https://linux-hardware.org/?probe=5437de2b1b) | Dec 12, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [349781adbb](https://linux-hardware.org/?probe=349781adbb) | Dec 12, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [8370a57760](https://linux-hardware.org/?probe=8370a57760) | Dec 12, 2022 |
| HP            | ProBook 6570b               | Notebook    | [a6b67497a1](https://linux-hardware.org/?probe=a6b67497a1) | Dec 12, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [665b87269c](https://linux-hardware.org/?probe=665b87269c) | Dec 12, 2022 |
| ASUSTek       | ROG Strix G713RM_G713RM     | Notebook    | [48e21506f4](https://linux-hardware.org/?probe=48e21506f4) | Dec 11, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | Notebook    | [257e692fa4](https://linux-hardware.org/?probe=257e692fa4) | Dec 11, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [d65a8640af](https://linux-hardware.org/?probe=d65a8640af) | Dec 11, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [25e5e8d887](https://linux-hardware.org/?probe=25e5e8d887) | Dec 11, 2022 |
| MSI           | B350 TOMAHAWK               | Desktop     | [0ce6563922](https://linux-hardware.org/?probe=0ce6563922) | Dec 11, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [f803c32eae](https://linux-hardware.org/?probe=f803c32eae) | Dec 11, 2022 |
| Dell          | 0Y5DDC A00                  | Desktop     | [22f4cdc5d7](https://linux-hardware.org/?probe=22f4cdc5d7) | Dec 11, 2022 |
| ASUSTek       | X75VD                       | Notebook    | [5cdd66c849](https://linux-hardware.org/?probe=5cdd66c849) | Dec 11, 2022 |
| MSI           | H81M-E34                    | Desktop     | [a9cc317647](https://linux-hardware.org/?probe=a9cc317647) | Dec 11, 2022 |
| Lenovo        | IdeaPad 320-17AST 80XW      | Notebook    | [474f4f4c43](https://linux-hardware.org/?probe=474f4f4c43) | Dec 11, 2022 |
| ASUSTek       | X75VD                       | Notebook    | [624ea43f9d](https://linux-hardware.org/?probe=624ea43f9d) | Dec 11, 2022 |
| ASRock        | X79 Extreme6                | Desktop     | [8ef84e95c1](https://linux-hardware.org/?probe=8ef84e95c1) | Dec 11, 2022 |
| ASUSTek       | H81I-PLUS                   | Desktop     | [b252b33238](https://linux-hardware.org/?probe=b252b33238) | Dec 11, 2022 |
| Gigabyte      | B150M-D2V DDR3-CF           | Desktop     | [9d689be2ab](https://linux-hardware.org/?probe=9d689be2ab) | Dec 11, 2022 |
| AZW           | Gemini T45                  | Desktop     | [e0b5dab1b4](https://linux-hardware.org/?probe=e0b5dab1b4) | Dec 11, 2022 |
| AZW           | Gemini T45                  | Desktop     | [d169b1be26](https://linux-hardware.org/?probe=d169b1be26) | Dec 11, 2022 |
| Dell          | Latitude E7240              | Notebook    | [591f0ad589](https://linux-hardware.org/?probe=591f0ad589) | Dec 11, 2022 |
| ASUSTek       | T101HA                      | Tablet      | [6fb942bf9d](https://linux-hardware.org/?probe=6fb942bf9d) | Dec 11, 2022 |
| ASUSTek       | X751SA                      | Notebook    | [2da53106a0](https://linux-hardware.org/?probe=2da53106a0) | Dec 11, 2022 |
| Alienware     | m17 R2                      | Notebook    | [76a2c6b1ca](https://linux-hardware.org/?probe=76a2c6b1ca) | Dec 11, 2022 |
| ASUSTek       | X751SA                      | Notebook    | [36b3666998](https://linux-hardware.org/?probe=36b3666998) | Dec 10, 2022 |
| Dell          | Latitude E7240              | Notebook    | [e0aca47e1b](https://linux-hardware.org/?probe=e0aca47e1b) | Dec 10, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [ec1e8e146a](https://linux-hardware.org/?probe=ec1e8e146a) | Dec 10, 2022 |
| ASUSTek       | ROG Flow X13 GV301RA_GV3... | Convertible | [d7ea1184a2](https://linux-hardware.org/?probe=d7ea1184a2) | Dec 10, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [05f65af47e](https://linux-hardware.org/?probe=05f65af47e) | Dec 10, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [6dd02812db](https://linux-hardware.org/?probe=6dd02812db) | Dec 10, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [350102190e](https://linux-hardware.org/?probe=350102190e) | Dec 10, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [688e981eee](https://linux-hardware.org/?probe=688e981eee) | Dec 10, 2022 |
| Dell          | Precision 5550              | Notebook    | [ad172b99ad](https://linux-hardware.org/?probe=ad172b99ad) | Dec 10, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [5625437112](https://linux-hardware.org/?probe=5625437112) | Dec 10, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [6466139b57](https://linux-hardware.org/?probe=6466139b57) | Dec 10, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [363ac45af6](https://linux-hardware.org/?probe=363ac45af6) | Dec 10, 2022 |
| MSI           | H97M-G43                    | Desktop     | [c62f2a0b49](https://linux-hardware.org/?probe=c62f2a0b49) | Dec 10, 2022 |
| Dell          | XPS 17 9700                 | Notebook    | [0426545e91](https://linux-hardware.org/?probe=0426545e91) | Dec 10, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [26e2759694](https://linux-hardware.org/?probe=26e2759694) | Dec 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [1e314d59ee](https://linux-hardware.org/?probe=1e314d59ee) | Dec 09, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [91b65d2fa1](https://linux-hardware.org/?probe=91b65d2fa1) | Dec 09, 2022 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [dfceb62f5d](https://linux-hardware.org/?probe=dfceb62f5d) | Dec 09, 2022 |
| MSI           | GS73VR 7RF                  | Notebook    | [31aa44b519](https://linux-hardware.org/?probe=31aa44b519) | Dec 09, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [a80714c4ec](https://linux-hardware.org/?probe=a80714c4ec) | Dec 09, 2022 |
| ASRock        | X570 Pro4                   | Desktop     | [347fc5c7ec](https://linux-hardware.org/?probe=347fc5c7ec) | Dec 09, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [6269ce6b15](https://linux-hardware.org/?probe=6269ce6b15) | Dec 08, 2022 |
| Toshiba       | Satellite L500              | Notebook    | [3258bb06ef](https://linux-hardware.org/?probe=3258bb06ef) | Dec 08, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [8cc721f649](https://linux-hardware.org/?probe=8cc721f649) | Dec 08, 2022 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | Desktop     | [19986ba651](https://linux-hardware.org/?probe=19986ba651) | Dec 08, 2022 |
| Dell          | Precision 7720              | Notebook    | [5e8014cc1b](https://linux-hardware.org/?probe=5e8014cc1b) | Dec 08, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [1a61a83764](https://linux-hardware.org/?probe=1a61a83764) | Dec 08, 2022 |
| MSI           | 760GM-P23                   | Desktop     | [29337f7359](https://linux-hardware.org/?probe=29337f7359) | Dec 08, 2022 |
| HP            | 339A                        | Desktop     | [64e1121397](https://linux-hardware.org/?probe=64e1121397) | Dec 08, 2022 |
| ASUSTek       | F2A55                       | Desktop     | [a8ed6d4071](https://linux-hardware.org/?probe=a8ed6d4071) | Dec 08, 2022 |
| MSI           | H97M-G43                    | Desktop     | [53754acfcb](https://linux-hardware.org/?probe=53754acfcb) | Dec 08, 2022 |
| HP            | x360 310 G1 PC              | Notebook    | [297806eac9](https://linux-hardware.org/?probe=297806eac9) | Dec 08, 2022 |
| Lenovo        | ThinkPad T420 4236PZ0       | Notebook    | [603c3b47a9](https://linux-hardware.org/?probe=603c3b47a9) | Dec 08, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [469f0a1d1f](https://linux-hardware.org/?probe=469f0a1d1f) | Dec 07, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [bf8647ecdc](https://linux-hardware.org/?probe=bf8647ecdc) | Dec 07, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [dfc7911df2](https://linux-hardware.org/?probe=dfc7911df2) | Dec 07, 2022 |
| HP            | ZBook 15 G6                 | Notebook    | [57a9a5fbf8](https://linux-hardware.org/?probe=57a9a5fbf8) | Dec 07, 2022 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [5abfdbdcba](https://linux-hardware.org/?probe=5abfdbdcba) | Dec 07, 2022 |
| MSI           | X399 SLI PLUS               | Desktop     | [c97bfe2139](https://linux-hardware.org/?probe=c97bfe2139) | Dec 07, 2022 |
| AZW           | U59                         | Desktop     | [ba4e2d8f5d](https://linux-hardware.org/?probe=ba4e2d8f5d) | Dec 07, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [82d49749a2](https://linux-hardware.org/?probe=82d49749a2) | Dec 07, 2022 |
| Dell          | Latitude E6410              | Notebook    | [0c768fd820](https://linux-hardware.org/?probe=0c768fd820) | Dec 07, 2022 |
| BESSTAR Te... | U820                        | Notebook    | [ea466e46b1](https://linux-hardware.org/?probe=ea466e46b1) | Dec 07, 2022 |
| HP            | Compaq 6910p                | Notebook    | [10b301f77e](https://linux-hardware.org/?probe=10b301f77e) | Dec 07, 2022 |
| Dell          | Inspiron 7720               | Notebook    | [180d05d4c1](https://linux-hardware.org/?probe=180d05d4c1) | Dec 06, 2022 |
| Acer          | Aspire E5-772               | Notebook    | [35c8c05d6c](https://linux-hardware.org/?probe=35c8c05d6c) | Dec 06, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | Notebook    | [ebf5cc9d6e](https://linux-hardware.org/?probe=ebf5cc9d6e) | Dec 06, 2022 |
| HP            | ZBook Firefly 14 inch G8... | Notebook    | [fccbb1fcec](https://linux-hardware.org/?probe=fccbb1fcec) | Dec 06, 2022 |
| HP            | EliteBook 2570p             | Notebook    | [fc7d866c16](https://linux-hardware.org/?probe=fc7d866c16) | Dec 06, 2022 |
| Lenovo        | ThinkPad L14 Gen 2a 20X6... | Notebook    | [1f1c509e41](https://linux-hardware.org/?probe=1f1c509e41) | Dec 06, 2022 |
| Lenovo        | ThinkPad T450s 20BWS2KM0... | Notebook    | [792c537a38](https://linux-hardware.org/?probe=792c537a38) | Dec 06, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [eaf904a47a](https://linux-hardware.org/?probe=eaf904a47a) | Dec 06, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [90af9a1be5](https://linux-hardware.org/?probe=90af9a1be5) | Dec 06, 2022 |
| ASUSTek       | K70IO                       | Notebook    | [193053a6ef](https://linux-hardware.org/?probe=193053a6ef) | Dec 05, 2022 |
| Fujitsu       | D3498-A1 S26361-D3498-A1    | Desktop     | [03cd265cef](https://linux-hardware.org/?probe=03cd265cef) | Dec 05, 2022 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | Notebook    | [5b72cdbdb8](https://linux-hardware.org/?probe=5b72cdbdb8) | Dec 05, 2022 |
| Apple         | MacBookPro5,4               | Notebook    | [bd98ec1bcb](https://linux-hardware.org/?probe=bd98ec1bcb) | Dec 05, 2022 |
| Dell          | Inspiron 5502               | Notebook    | [311215d00b](https://linux-hardware.org/?probe=311215d00b) | Dec 05, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [f11d4ebe40](https://linux-hardware.org/?probe=f11d4ebe40) | Dec 05, 2022 |
| Lenovo        | Yoga Slim 9 14ITL5 82D1     | Notebook    | [f90956a720](https://linux-hardware.org/?probe=f90956a720) | Dec 05, 2022 |
| Dell          | 0T10XW A00                  | Desktop     | [d6f876fa52](https://linux-hardware.org/?probe=d6f876fa52) | Dec 05, 2022 |
| ASUSTek       | A_F_K31AN                   | Desktop     | [440d9055ff](https://linux-hardware.org/?probe=440d9055ff) | Dec 05, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [f96de923f4](https://linux-hardware.org/?probe=f96de923f4) | Dec 05, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [b7b2f976e8](https://linux-hardware.org/?probe=b7b2f976e8) | Dec 05, 2022 |
| Lenovo        | ThinkPad Yoga 260 20FES4... | Convertible | [77dfa24689](https://linux-hardware.org/?probe=77dfa24689) | Dec 05, 2022 |
| eMachines     | E520 V1.06                  | Notebook    | [0ef424fa9b](https://linux-hardware.org/?probe=0ef424fa9b) | Dec 05, 2022 |
| Dell          | G3 3500                     | Notebook    | [5b23644904](https://linux-hardware.org/?probe=5b23644904) | Dec 05, 2022 |
| Lenovo        | ThinkPad P51 20HJS16Q0K     | Notebook    | [3dfd18754f](https://linux-hardware.org/?probe=3dfd18754f) | Dec 05, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [3027fc2c2f](https://linux-hardware.org/?probe=3027fc2c2f) | Dec 05, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [a07d55ca40](https://linux-hardware.org/?probe=a07d55ca40) | Dec 05, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [535444f416](https://linux-hardware.org/?probe=535444f416) | Dec 05, 2022 |
| Acer          | Veriton X2631G V:1.0        | Desktop     | [363d58e88d](https://linux-hardware.org/?probe=363d58e88d) | Dec 05, 2022 |
| Acer          | Veriton X2631G V:1.0        | Desktop     | [f8607ccc53](https://linux-hardware.org/?probe=f8607ccc53) | Dec 05, 2022 |
| Dell          | 0M863N A01                  | Desktop     | [ee8183087b](https://linux-hardware.org/?probe=ee8183087b) | Dec 04, 2022 |
| HP            | x360 310 G1 PC              | Notebook    | [b15b39727b](https://linux-hardware.org/?probe=b15b39727b) | Dec 04, 2022 |
| Sony          | VPCEL2S1E                   | Notebook    | [0c98b9d570](https://linux-hardware.org/?probe=0c98b9d570) | Dec 04, 2022 |
| Dell          | 0TDG4V A01                  | Desktop     | [1129691459](https://linux-hardware.org/?probe=1129691459) | Dec 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [a89e9e55cb](https://linux-hardware.org/?probe=a89e9e55cb) | Dec 04, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [7687bdc111](https://linux-hardware.org/?probe=7687bdc111) | Dec 04, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [db7cd6f0dc](https://linux-hardware.org/?probe=db7cd6f0dc) | Dec 04, 2022 |
| Acer          | Aspire VN7-572G             | Notebook    | [2147d11bad](https://linux-hardware.org/?probe=2147d11bad) | Dec 04, 2022 |
| Acer          | Aspire VN7-572G             | Notebook    | [5a456d1825](https://linux-hardware.org/?probe=5a456d1825) | Dec 04, 2022 |
| ASUSTek       | K53SD                       | Notebook    | [dbaf532969](https://linux-hardware.org/?probe=dbaf532969) | Dec 04, 2022 |
| Lenovo        | Win8 Pro DPK TPG            | Desktop     | [1dbda8e648](https://linux-hardware.org/?probe=1dbda8e648) | Dec 04, 2022 |
| ASUSTek       | LEUCITE3                    | Desktop     | [4f28bb5933](https://linux-hardware.org/?probe=4f28bb5933) | Dec 04, 2022 |
| HP            | 339A                        | Desktop     | [91ed08d2a9](https://linux-hardware.org/?probe=91ed08d2a9) | Dec 04, 2022 |
| MSI           | MAG B560M MORTAR            | Desktop     | [1725274555](https://linux-hardware.org/?probe=1725274555) | Dec 03, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [c7cf7a1604](https://linux-hardware.org/?probe=c7cf7a1604) | Dec 03, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [67c278b32e](https://linux-hardware.org/?probe=67c278b32e) | Dec 03, 2022 |
| Dell          | Latitude E5510              | Notebook    | [6027856ab6](https://linux-hardware.org/?probe=6027856ab6) | Dec 03, 2022 |
| HP            | Laptop 15s-fr2xxx           | Notebook    | [623e794238](https://linux-hardware.org/?probe=623e794238) | Dec 03, 2022 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [f6bb91c588](https://linux-hardware.org/?probe=f6bb91c588) | Dec 03, 2022 |
| ASUSTek       | ET1610PT                    | Desktop     | [d8b1840336](https://linux-hardware.org/?probe=d8b1840336) | Dec 03, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [6c05e05a15](https://linux-hardware.org/?probe=6c05e05a15) | Dec 03, 2022 |
| Lenovo        | ThinkPad T440p 20AWS17N0... | Notebook    | [716a6802ca](https://linux-hardware.org/?probe=716a6802ca) | Dec 03, 2022 |
| Fujitsu       | CELSIUS H720                | Notebook    | [a7eacb37c5](https://linux-hardware.org/?probe=a7eacb37c5) | Dec 03, 2022 |
| ASUSTek       | K70IO                       | Notebook    | [179ce76921](https://linux-hardware.org/?probe=179ce76921) | Dec 02, 2022 |
| HP            | Stream Notebook             | Notebook    | [dc16cc5c95](https://linux-hardware.org/?probe=dc16cc5c95) | Dec 02, 2022 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [4bae364a79](https://linux-hardware.org/?probe=4bae364a79) | Dec 02, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [78f2f440eb](https://linux-hardware.org/?probe=78f2f440eb) | Dec 02, 2022 |
| Valve         | Jupiter                     | Notebook    | [f54147a5ba](https://linux-hardware.org/?probe=f54147a5ba) | Dec 02, 2022 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [33b77409e5](https://linux-hardware.org/?probe=33b77409e5) | Dec 02, 2022 |
| HP            | Notebook                    | Notebook    | [c42eef153d](https://linux-hardware.org/?probe=c42eef153d) | Dec 02, 2022 |
| Dell          | Inspiron 16 5625            | Notebook    | [6e1523c2e8](https://linux-hardware.org/?probe=6e1523c2e8) | Dec 02, 2022 |
| Valve         | Jupiter                     | Notebook    | [4f32d4f1c2](https://linux-hardware.org/?probe=4f32d4f1c2) | Dec 02, 2022 |
| HP            | ProBook 6570b               | Notebook    | [be8f757095](https://linux-hardware.org/?probe=be8f757095) | Dec 02, 2022 |
| ASRock        | G41C-GS R2.0                | Desktop     | [87b13a5112](https://linux-hardware.org/?probe=87b13a5112) | Dec 02, 2022 |
| ASRock        | G41C-GS R2.0                | Desktop     | [82c0eb6155](https://linux-hardware.org/?probe=82c0eb6155) | Dec 02, 2022 |
| HP            | ProBook 6570b               | Notebook    | [1e40d6a94b](https://linux-hardware.org/?probe=1e40d6a94b) | Dec 02, 2022 |
| ASUSTek       | ROG Strix G731GU_G731GU     | Notebook    | [38ce706249](https://linux-hardware.org/?probe=38ce706249) | Dec 02, 2022 |
| ASUSTek       | ROG Strix G731GU_G731GU     | Notebook    | [546f2b82c9](https://linux-hardware.org/?probe=546f2b82c9) | Dec 02, 2022 |
| ASUSTek       | ROG Strix G731GU_G731GU     | Notebook    | [000d536e95](https://linux-hardware.org/?probe=000d536e95) | Dec 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [c19e5b9f4b](https://linux-hardware.org/?probe=c19e5b9f4b) | Dec 02, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [ed3886b135](https://linux-hardware.org/?probe=ed3886b135) | Dec 02, 2022 |
| Lenovo        | ThinkPad T61 6463WAP        | Notebook    | [e11baa0e49](https://linux-hardware.org/?probe=e11baa0e49) | Dec 02, 2022 |
| AZW           | SEi                         | Notebook    | [3cd2f7f657](https://linux-hardware.org/?probe=3cd2f7f657) | Dec 01, 2022 |
| Acer          | Aspire XC-705               | Desktop     | [86a503df2a](https://linux-hardware.org/?probe=86a503df2a) | Dec 01, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [5e7bc65683](https://linux-hardware.org/?probe=5e7bc65683) | Dec 01, 2022 |
| Samsung       | R540/R538/SA41/E452         | Notebook    | [afad3c8828](https://linux-hardware.org/?probe=afad3c8828) | Dec 01, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [1002df8858](https://linux-hardware.org/?probe=1002df8858) | Dec 01, 2022 |
| ASUSTek       | A88XM-A                     | Desktop     | [f883ed1fd1](https://linux-hardware.org/?probe=f883ed1fd1) | Dec 01, 2022 |
| Samsung       | 930XED                      | Notebook    | [38584fa129](https://linux-hardware.org/?probe=38584fa129) | Dec 01, 2022 |
| Dell          | Precision 5540              | Notebook    | [030dbd45f0](https://linux-hardware.org/?probe=030dbd45f0) | Dec 01, 2022 |
| ASUSTek       | S551LN                      | Notebook    | [b21b106fdf](https://linux-hardware.org/?probe=b21b106fdf) | Dec 01, 2022 |
| Gigabyte      | H170-HD3-CF                 | Desktop     | [1d293c6d72](https://linux-hardware.org/?probe=1d293c6d72) | Nov 30, 2022 |
| ASUSTek       | Z97-A                       | Desktop     | [da1400c491](https://linux-hardware.org/?probe=da1400c491) | Nov 30, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [e17d8c1694](https://linux-hardware.org/?probe=e17d8c1694) | Nov 30, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [183243daeb](https://linux-hardware.org/?probe=183243daeb) | Nov 30, 2022 |
| HP            | EliteBook x360 1040 G8 N... | Convertible | [4b635dd9ef](https://linux-hardware.org/?probe=4b635dd9ef) | Nov 30, 2022 |
| Packard Be... | EasyNote TE69CXP            | Notebook    | [919275eb73](https://linux-hardware.org/?probe=919275eb73) | Nov 30, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [09a9309a2a](https://linux-hardware.org/?probe=09a9309a2a) | Nov 30, 2022 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [bd1c91dba9](https://linux-hardware.org/?probe=bd1c91dba9) | Nov 30, 2022 |
| Apple         | Mac-B809C3757DA9BB8D iMa... | All in one  | [f698b715e4](https://linux-hardware.org/?probe=f698b715e4) | Nov 30, 2022 |
| HP            | ZBook 15v G5                | Notebook    | [aabc35ae2a](https://linux-hardware.org/?probe=aabc35ae2a) | Nov 30, 2022 |
| ASUSTek       | E403SA                      | Notebook    | [d3a1f181d5](https://linux-hardware.org/?probe=d3a1f181d5) | Nov 30, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [b585d891a8](https://linux-hardware.org/?probe=b585d891a8) | Nov 30, 2022 |
| Lenovo        | G70-80 80FF                 | Notebook    | [022ce8e2c8](https://linux-hardware.org/?probe=022ce8e2c8) | Nov 29, 2022 |
| HP            | Pavilion 17                 | Notebook    | [431ce9bd18](https://linux-hardware.org/?probe=431ce9bd18) | Nov 29, 2022 |
| Dell          | Latitude E6410              | Notebook    | [d7abefea4b](https://linux-hardware.org/?probe=d7abefea4b) | Nov 29, 2022 |
| Dell          | Latitude E6410              | Notebook    | [bac3e8c250](https://linux-hardware.org/?probe=bac3e8c250) | Nov 29, 2022 |
| Dell          | Latitude 5330               | Notebook    | [b8d907f2e8](https://linux-hardware.org/?probe=b8d907f2e8) | Nov 29, 2022 |
| MSI           | GT60                        | Notebook    | [07557bed1b](https://linux-hardware.org/?probe=07557bed1b) | Nov 29, 2022 |
| Dell          | Inspiron 16 5625            | Notebook    | [50912d5fa9](https://linux-hardware.org/?probe=50912d5fa9) | Nov 29, 2022 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [e9932df850](https://linux-hardware.org/?probe=e9932df850) | Nov 29, 2022 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [179ff76e75](https://linux-hardware.org/?probe=179ff76e75) | Nov 29, 2022 |
| Dell          | Latitude 7490               | Notebook    | [8934413cf0](https://linux-hardware.org/?probe=8934413cf0) | Nov 29, 2022 |
| Dell          | System Vostro 3750          | Notebook    | [ed88e2ae0c](https://linux-hardware.org/?probe=ed88e2ae0c) | Nov 29, 2022 |
| Thomson       | N17V3C8WH512                | Notebook    | [b89cd0328a](https://linux-hardware.org/?probe=b89cd0328a) | Nov 29, 2022 |
| ASRock        | FM2A78 Pro4+                | Desktop     | [7eae5fad47](https://linux-hardware.org/?probe=7eae5fad47) | Nov 29, 2022 |
| Razer         | Blade Stealth               | Notebook    | [e182c3c739](https://linux-hardware.org/?probe=e182c3c739) | Nov 29, 2022 |
| ASUSTek       | K70IO                       | Notebook    | [f91b4cdb61](https://linux-hardware.org/?probe=f91b4cdb61) | Nov 29, 2022 |
| Intel         | DH67BL AAG10189-213         | Desktop     | [11252af398](https://linux-hardware.org/?probe=11252af398) | Nov 28, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [ffe997080f](https://linux-hardware.org/?probe=ffe997080f) | Nov 28, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [1387bf11ea](https://linux-hardware.org/?probe=1387bf11ea) | Nov 28, 2022 |
| Dell          | Inspiron 16 5625            | Notebook    | [22da2f8729](https://linux-hardware.org/?probe=22da2f8729) | Nov 28, 2022 |
| ASUSTek       | X756UVK                     | Notebook    | [4745940cf9](https://linux-hardware.org/?probe=4745940cf9) | Nov 28, 2022 |
| Dell          | 0NK5PH A00                  | Desktop     | [d889c3c50a](https://linux-hardware.org/?probe=d889c3c50a) | Nov 28, 2022 |
| Dell          | 0773VG A00                  | Desktop     | [a21b1834c2](https://linux-hardware.org/?probe=a21b1834c2) | Nov 28, 2022 |
| Dell          | 0773VG A00                  | Desktop     | [04125afb72](https://linux-hardware.org/?probe=04125afb72) | Nov 28, 2022 |
| ASRock        | FM2A78 Pro4+                | Desktop     | [908283c378](https://linux-hardware.org/?probe=908283c378) | Nov 28, 2022 |
| ASUSTek       | K70IO                       | Notebook    | [4eabf9a0d4](https://linux-hardware.org/?probe=4eabf9a0d4) | Nov 28, 2022 |
| Lenovo        | ThinkPad T450 20BUS03J00    | Notebook    | [8423f90db0](https://linux-hardware.org/?probe=8423f90db0) | Nov 27, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [bc515374ae](https://linux-hardware.org/?probe=bc515374ae) | Nov 27, 2022 |
| Dell          | Latitude E6230              | Notebook    | [f3536b80de](https://linux-hardware.org/?probe=f3536b80de) | Nov 27, 2022 |
| Dell          | Latitude E6230              | Notebook    | [dbaae2beb7](https://linux-hardware.org/?probe=dbaae2beb7) | Nov 27, 2022 |
| Dell          | 05XGC8 A00                  | Desktop     | [e0e0efb9be](https://linux-hardware.org/?probe=e0e0efb9be) | Nov 27, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [7cb4ad7428](https://linux-hardware.org/?probe=7cb4ad7428) | Nov 27, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [54d005e599](https://linux-hardware.org/?probe=54d005e599) | Nov 27, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [2d1a576ee6](https://linux-hardware.org/?probe=2d1a576ee6) | Nov 27, 2022 |
| HP            | Compaq Presario CQ60        | Notebook    | [1f521f98cb](https://linux-hardware.org/?probe=1f521f98cb) | Nov 27, 2022 |
| Dell          | Studio 1558                 | Notebook    | [bc76adb105](https://linux-hardware.org/?probe=bc76adb105) | Nov 27, 2022 |
| Dell          | Studio 1558                 | Notebook    | [43438ab851](https://linux-hardware.org/?probe=43438ab851) | Nov 27, 2022 |
| Jumper        | EZbook                      | Notebook    | [a93aa75e5f](https://linux-hardware.org/?probe=a93aa75e5f) | Nov 27, 2022 |
| Panasonic     | CF-19AHN3BFF                | Notebook    | [a5989143a8](https://linux-hardware.org/?probe=a5989143a8) | Nov 26, 2022 |
| ASUSTek       | 1002HA                      | Notebook    | [15d5eb998d](https://linux-hardware.org/?probe=15d5eb998d) | Nov 26, 2022 |
| ASUSTek       | P7P55D-E LX                 | Desktop     | [8b913d5510](https://linux-hardware.org/?probe=8b913d5510) | Nov 26, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [02b1483a02](https://linux-hardware.org/?probe=02b1483a02) | Nov 26, 2022 |
| Dell          | Latitude 7310               | Notebook    | [46ed677d40](https://linux-hardware.org/?probe=46ed677d40) | Nov 26, 2022 |
| Dell          | 04MFRM A02                  | Desktop     | [43239e45b1](https://linux-hardware.org/?probe=43239e45b1) | Nov 26, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | Notebook    | [694d1d5e96](https://linux-hardware.org/?probe=694d1d5e96) | Nov 26, 2022 |
| MSI           | GL62M 7RDX                  | Notebook    | [1aa67b30d4](https://linux-hardware.org/?probe=1aa67b30d4) | Nov 26, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [1b3355afbc](https://linux-hardware.org/?probe=1b3355afbc) | Nov 26, 2022 |
| Dell          | Inspiron MP061              | Notebook    | [d70d7496df](https://linux-hardware.org/?probe=d70d7496df) | Nov 26, 2022 |
| ASUSTek       | Z97-A                       | Desktop     | [9163dc4b5d](https://linux-hardware.org/?probe=9163dc4b5d) | Nov 26, 2022 |
| Dell          | 05XGC8 A00                  | Desktop     | [6ea1a60122](https://linux-hardware.org/?probe=6ea1a60122) | Nov 26, 2022 |
| Dell          | Latitude E7240              | Notebook    | [634ebb2a88](https://linux-hardware.org/?probe=634ebb2a88) | Nov 25, 2022 |
| ASUSTek       | P8B75-M LX PLUS             | Desktop     | [7948a35f59](https://linux-hardware.org/?probe=7948a35f59) | Nov 25, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [2787600567](https://linux-hardware.org/?probe=2787600567) | Nov 25, 2022 |
| HP            | Pavilion 15                 | Notebook    | [b294971fc6](https://linux-hardware.org/?probe=b294971fc6) | Nov 25, 2022 |
| ASUSTek       | X555YI                      | Notebook    | [2626d57c13](https://linux-hardware.org/?probe=2626d57c13) | Nov 25, 2022 |
| Intel         | BTC-T37                     | Desktop     | [f52a08ae38](https://linux-hardware.org/?probe=f52a08ae38) | Nov 25, 2022 |
| Dell          | Latitude 7310               | Notebook    | [0f9c2a5623](https://linux-hardware.org/?probe=0f9c2a5623) | Nov 25, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [de56ed9d3f](https://linux-hardware.org/?probe=de56ed9d3f) | Nov 25, 2022 |
| Panasonic     | CF-19AHN3BFF                | Notebook    | [bfd184ea5c](https://linux-hardware.org/?probe=bfd184ea5c) | Nov 25, 2022 |
| Gigabyte      | G1.SNIPER B7-CF             | Desktop     | [c53295ce70](https://linux-hardware.org/?probe=c53295ce70) | Nov 25, 2022 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | Desktop     | [97ede0876f](https://linux-hardware.org/?probe=97ede0876f) | Nov 25, 2022 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | Desktop     | [1817579f89](https://linux-hardware.org/?probe=1817579f89) | Nov 25, 2022 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [ce586530e4](https://linux-hardware.org/?probe=ce586530e4) | Nov 24, 2022 |
| Lenovo        | ThinkCentre A70 7099A5G     | Desktop     | [dad5599996](https://linux-hardware.org/?probe=dad5599996) | Nov 24, 2022 |
| HP            | 0AE8h                       | Desktop     | [c49d643fae](https://linux-hardware.org/?probe=c49d643fae) | Nov 24, 2022 |
| Dell          | Latitude 7310               | Notebook    | [d7448aaff8](https://linux-hardware.org/?probe=d7448aaff8) | Nov 24, 2022 |
| Acer          | Aspire ES1-523              | Notebook    | [333d3583b1](https://linux-hardware.org/?probe=333d3583b1) | Nov 24, 2022 |
| MSI           | B75A-G43                    | Desktop     | [7f635dae7f](https://linux-hardware.org/?probe=7f635dae7f) | Nov 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [0904a442f0](https://linux-hardware.org/?probe=0904a442f0) | Nov 24, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | Notebook    | [4b6212908f](https://linux-hardware.org/?probe=4b6212908f) | Nov 24, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | Notebook    | [69c89370b7](https://linux-hardware.org/?probe=69c89370b7) | Nov 24, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [a4512e8a71](https://linux-hardware.org/?probe=a4512e8a71) | Nov 24, 2022 |
| Dell          | Latitude E6500              | Notebook    | [73d607f9e1](https://linux-hardware.org/?probe=73d607f9e1) | Nov 24, 2022 |
| Dell          | Latitude 7310               | Notebook    | [836fbd119c](https://linux-hardware.org/?probe=836fbd119c) | Nov 24, 2022 |
| Apple         | Mac-B809C3757DA9BB8D iMa... | All in one  | [b79f103dd5](https://linux-hardware.org/?probe=b79f103dd5) | Nov 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [9e1f0c4898](https://linux-hardware.org/?probe=9e1f0c4898) | Nov 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [ef378a135b](https://linux-hardware.org/?probe=ef378a135b) | Nov 24, 2022 |
| Gigabyte      | H97-HD3                     | Desktop     | [7c2db201dc](https://linux-hardware.org/?probe=7c2db201dc) | Nov 24, 2022 |
| Intel         | NUC7i3DNB J57625-508        | Mini pc     | [e65c082f84](https://linux-hardware.org/?probe=e65c082f84) | Nov 24, 2022 |
| Acer          | Aspire A315-54K             | Notebook    | [12f19e4fbe](https://linux-hardware.org/?probe=12f19e4fbe) | Nov 23, 2022 |
| ASUSTek       | K70IJ                       | Notebook    | [8df764e624](https://linux-hardware.org/?probe=8df764e624) | Nov 23, 2022 |
| MSI           | MAG B550 TORPEDO            | Desktop     | [ca3bcfa403](https://linux-hardware.org/?probe=ca3bcfa403) | Nov 23, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [a9d12017bb](https://linux-hardware.org/?probe=a9d12017bb) | Nov 23, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [b0e5869f2d](https://linux-hardware.org/?probe=b0e5869f2d) | Nov 23, 2022 |
| MSI           | Modern 14 C12M              | Notebook    | [51088606f5](https://linux-hardware.org/?probe=51088606f5) | Nov 23, 2022 |
| Acer          | FIH57                       | Desktop     | [008bcadcd9](https://linux-hardware.org/?probe=008bcadcd9) | Nov 23, 2022 |
| MSI           | H61M-E33                    | Desktop     | [d0277334cf](https://linux-hardware.org/?probe=d0277334cf) | Nov 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [f1d8974d71](https://linux-hardware.org/?probe=f1d8974d71) | Nov 23, 2022 |
| Gigabyte      | B650M DS3H                  | Desktop     | [fc9449798a](https://linux-hardware.org/?probe=fc9449798a) | Nov 23, 2022 |
| Unknown       | Unknown                     | Notebook    | [c119fbb804](https://linux-hardware.org/?probe=c119fbb804) | Nov 22, 2022 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [96205eb8d4](https://linux-hardware.org/?probe=96205eb8d4) | Nov 22, 2022 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [97571585cd](https://linux-hardware.org/?probe=97571585cd) | Nov 22, 2022 |
| ASUSTek       | H81M2                       | Desktop     | [f06b4252d7](https://linux-hardware.org/?probe=f06b4252d7) | Nov 22, 2022 |
| Acer          | Aspire A515-57              | Notebook    | [4692ce22fb](https://linux-hardware.org/?probe=4692ce22fb) | Nov 22, 2022 |
| Acer          | Aspire A515-57              | Notebook    | [cb82f6d418](https://linux-hardware.org/?probe=cb82f6d418) | Nov 22, 2022 |
| HP            | ENVY dv6                    | Notebook    | [0d28d09c70](https://linux-hardware.org/?probe=0d28d09c70) | Nov 22, 2022 |
| Dell          | Inspiron 7586               | Convertible | [ea152cdb94](https://linux-hardware.org/?probe=ea152cdb94) | Nov 22, 2022 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [29b92290e8](https://linux-hardware.org/?probe=29b92290e8) | Nov 22, 2022 |
| Dell          | Latitude E6520              | Notebook    | [1801edca03](https://linux-hardware.org/?probe=1801edca03) | Nov 22, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [c8d71bb807](https://linux-hardware.org/?probe=c8d71bb807) | Nov 22, 2022 |
| Acer          | Veriton X2631G V:1.0        | Desktop     | [af2a85dd3c](https://linux-hardware.org/?probe=af2a85dd3c) | Nov 22, 2022 |
| Timi          | TM1612                      | Notebook    | [abd08d53c7](https://linux-hardware.org/?probe=abd08d53c7) | Nov 22, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [54d3eed278](https://linux-hardware.org/?probe=54d3eed278) | Nov 21, 2022 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [8789b14e39](https://linux-hardware.org/?probe=8789b14e39) | Nov 21, 2022 |
| HP            | 8184 X4                     | Desktop     | [f38ad9d963](https://linux-hardware.org/?probe=f38ad9d963) | Nov 21, 2022 |
| ASUSTek       | V-P5G43 R1.04G              | Desktop     | [b400ca5e29](https://linux-hardware.org/?probe=b400ca5e29) | Nov 21, 2022 |
| Dell          | Precision 5510              | Notebook    | [63c0b8aa0c](https://linux-hardware.org/?probe=63c0b8aa0c) | Nov 21, 2022 |
| MSI           | MAG B560M MORTAR            | Desktop     | [18a3c1f2bf](https://linux-hardware.org/?probe=18a3c1f2bf) | Nov 21, 2022 |
| HP            | 3399                        | Desktop     | [bce6df1ffb](https://linux-hardware.org/?probe=bce6df1ffb) | Nov 21, 2022 |
| ASUSTek       | F1A55-M LE                  | Desktop     | [f2120128c1](https://linux-hardware.org/?probe=f2120128c1) | Nov 21, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [c3048ea26d](https://linux-hardware.org/?probe=c3048ea26d) | Nov 21, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [9599fd68a9](https://linux-hardware.org/?probe=9599fd68a9) | Nov 21, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [a93dbf13df](https://linux-hardware.org/?probe=a93dbf13df) | Nov 21, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [50ca61403f](https://linux-hardware.org/?probe=50ca61403f) | Nov 21, 2022 |
| Acer          | FIH57                       | Desktop     | [70bcc47286](https://linux-hardware.org/?probe=70bcc47286) | Nov 21, 2022 |
| Acer          | Veriton X2631G V:1.0        | Desktop     | [df71eef5cb](https://linux-hardware.org/?probe=df71eef5cb) | Nov 21, 2022 |
| Unknown       | Unknown                     | Notebook    | [5a06cde126](https://linux-hardware.org/?probe=5a06cde126) | Nov 20, 2022 |
| Acer          | Veriton N4640G              | Desktop     | [a7984c4a95](https://linux-hardware.org/?probe=a7984c4a95) | Nov 20, 2022 |
| Acer          | Aspire ES1-711G             | Notebook    | [8852f94b38](https://linux-hardware.org/?probe=8852f94b38) | Nov 20, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [eb43c3d5c0](https://linux-hardware.org/?probe=eb43c3d5c0) | Nov 20, 2022 |
| HP            | 339A                        | Desktop     | [f5f01373e9](https://linux-hardware.org/?probe=f5f01373e9) | Nov 20, 2022 |
| ASRock        | 990FX Extreme3              | Desktop     | [84b8daa5c4](https://linux-hardware.org/?probe=84b8daa5c4) | Nov 20, 2022 |
| MSI           | X299 RAIDER                 | Desktop     | [544b8ae2b7](https://linux-hardware.org/?probe=544b8ae2b7) | Nov 19, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [6a51b20cd4](https://linux-hardware.org/?probe=6a51b20cd4) | Nov 19, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [6c896ef17e](https://linux-hardware.org/?probe=6c896ef17e) | Nov 19, 2022 |
| HP            | Pavilion g7                 | Notebook    | [fae1d08109](https://linux-hardware.org/?probe=fae1d08109) | Nov 19, 2022 |
| Google        | Rammus                      | Notebook    | [23ed7badd5](https://linux-hardware.org/?probe=23ed7badd5) | Nov 19, 2022 |
| Dell          | Latitude 7410               | Notebook    | [ce222880fe](https://linux-hardware.org/?probe=ce222880fe) | Nov 18, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [fc7b21bd04](https://linux-hardware.org/?probe=fc7b21bd04) | Nov 18, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [a0495a1ea1](https://linux-hardware.org/?probe=a0495a1ea1) | Nov 18, 2022 |
| HP            | 8643 SMVB                   | Desktop     | [3556ffb814](https://linux-hardware.org/?probe=3556ffb814) | Nov 18, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [a5151a0db4](https://linux-hardware.org/?probe=a5151a0db4) | Nov 18, 2022 |
| Dell          | Latitude 7300               | Notebook    | [5ff7502b3e](https://linux-hardware.org/?probe=5ff7502b3e) | Nov 18, 2022 |
| Dell          | 0Y7WYT A00                  | Desktop     | [d5306443e9](https://linux-hardware.org/?probe=d5306443e9) | Nov 18, 2022 |
| Dell          | 0773VG A00                  | Desktop     | [754a16b847](https://linux-hardware.org/?probe=754a16b847) | Nov 18, 2022 |
| Dell          | Latitude 7310               | Notebook    | [525543a3dc](https://linux-hardware.org/?probe=525543a3dc) | Nov 18, 2022 |
| Dell          | Latitude 7300               | Notebook    | [5c7f8f6d8c](https://linux-hardware.org/?probe=5c7f8f6d8c) | Nov 18, 2022 |
| Dell          | 0Y7WYT A00                  | Desktop     | [516b201857](https://linux-hardware.org/?probe=516b201857) | Nov 18, 2022 |
| HP            | Pavilion 17                 | Notebook    | [ab34ec642d](https://linux-hardware.org/?probe=ab34ec642d) | Nov 18, 2022 |
| Dynabook      | TECRA A50-J                 | Notebook    | [c0ae8746e0](https://linux-hardware.org/?probe=c0ae8746e0) | Nov 18, 2022 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | Notebook    | [94bd888b25](https://linux-hardware.org/?probe=94bd888b25) | Nov 18, 2022 |
| Acer          | Aspire S5-371               | Notebook    | [6274604555](https://linux-hardware.org/?probe=6274604555) | Nov 18, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [12e2119f1c](https://linux-hardware.org/?probe=12e2119f1c) | Nov 18, 2022 |
| Dell          | Latitude 5520               | Notebook    | [72bcc12409](https://linux-hardware.org/?probe=72bcc12409) | Nov 18, 2022 |
| Acer          | Aspire S24-880              | All in one  | [a255155f98](https://linux-hardware.org/?probe=a255155f98) | Nov 18, 2022 |
| Dell          | Latitude 5490               | Notebook    | [70b8fb5e89](https://linux-hardware.org/?probe=70b8fb5e89) | Nov 18, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | Notebook    | [88336d65e7](https://linux-hardware.org/?probe=88336d65e7) | Nov 17, 2022 |
| Dynabook E... | PORTABLECD2021              | Notebook    | [17a064a3c3](https://linux-hardware.org/?probe=17a064a3c3) | Nov 17, 2022 |
| MSI           | Prestige 14 A12SC           | Notebook    | [008c444627](https://linux-hardware.org/?probe=008c444627) | Nov 17, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [cd753ace10](https://linux-hardware.org/?probe=cd753ace10) | Nov 17, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [6901439af7](https://linux-hardware.org/?probe=6901439af7) | Nov 17, 2022 |
| HP            | 245 G8 Notebook PC          | Notebook    | [4d4f9a0e10](https://linux-hardware.org/?probe=4d4f9a0e10) | Nov 17, 2022 |
| Dell          | Latitude 7300               | Notebook    | [462f090e8c](https://linux-hardware.org/?probe=462f090e8c) | Nov 17, 2022 |
| Dell          | Latitude 7380               | Notebook    | [c34f569e5a](https://linux-hardware.org/?probe=c34f569e5a) | Nov 17, 2022 |
| Dell          | Latitude 7380               | Notebook    | [ff8bc9f174](https://linux-hardware.org/?probe=ff8bc9f174) | Nov 17, 2022 |
| HP            | ZBook 14 G2                 | Notebook    | [c084bd4b99](https://linux-hardware.org/?probe=c084bd4b99) | Nov 17, 2022 |
| HP            | ZBook 14 G2                 | Notebook    | [e687234452](https://linux-hardware.org/?probe=e687234452) | Nov 17, 2022 |
| Dynabook E... | PORTABLECD2021              | Notebook    | [5d138b93b6](https://linux-hardware.org/?probe=5d138b93b6) | Nov 16, 2022 |
| Dell          | Inspiron 13 5310            | Notebook    | [3c9865d86e](https://linux-hardware.org/?probe=3c9865d86e) | Nov 16, 2022 |
| MSI           | Katana GF76 11UC            | Notebook    | [24ba2f8b12](https://linux-hardware.org/?probe=24ba2f8b12) | Nov 16, 2022 |
| ASUSTek       | T100TA                      | Notebook    | [3d49b98878](https://linux-hardware.org/?probe=3d49b98878) | Nov 16, 2022 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [f863546b0f](https://linux-hardware.org/?probe=f863546b0f) | Nov 16, 2022 |
| ASUSTek       | PN51-E1                     | Mini pc     | [d6bae26c19](https://linux-hardware.org/?probe=d6bae26c19) | Nov 16, 2022 |
| Google        | Rammus                      | Notebook    | [ef0f440314](https://linux-hardware.org/?probe=ef0f440314) | Nov 16, 2022 |
| Dell          | 04MFRM A02                  | Desktop     | [677ab8eb16](https://linux-hardware.org/?probe=677ab8eb16) | Nov 16, 2022 |
| AMI           | Intel                       | Notebook    | [36327e3aca](https://linux-hardware.org/?probe=36327e3aca) | Nov 16, 2022 |
| HP            | Notebook                    | Notebook    | [d40f2df5a8](https://linux-hardware.org/?probe=d40f2df5a8) | Nov 16, 2022 |
| HP            | EliteBook x360 830 G6       | Convertible | [d4b09c09f0](https://linux-hardware.org/?probe=d4b09c09f0) | Nov 15, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [12fe5843d1](https://linux-hardware.org/?probe=12fe5843d1) | Nov 15, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [439fe62e2e](https://linux-hardware.org/?probe=439fe62e2e) | Nov 15, 2022 |
| LDLC          | SPC-N                       | Notebook    | [acec489419](https://linux-hardware.org/?probe=acec489419) | Nov 15, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [ff63827781](https://linux-hardware.org/?probe=ff63827781) | Nov 15, 2022 |
| Intel         | NUC7i3DNB J57625-508        | Mini pc     | [8e3861630d](https://linux-hardware.org/?probe=8e3861630d) | Nov 15, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [5ffe9844bd](https://linux-hardware.org/?probe=5ffe9844bd) | Nov 15, 2022 |
| ASUSTek       | P5QL-ASUS-SE                | Desktop     | [6dd2bbbe51](https://linux-hardware.org/?probe=6dd2bbbe51) | Nov 15, 2022 |
| Dell          | 0UR033 A00                  | Server      | [2ff8924b15](https://linux-hardware.org/?probe=2ff8924b15) | Nov 15, 2022 |
| HP            | Pavilion 17                 | Notebook    | [de4e2c6446](https://linux-hardware.org/?probe=de4e2c6446) | Nov 15, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [21ea41871f](https://linux-hardware.org/?probe=21ea41871f) | Nov 14, 2022 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [7bf6427590](https://linux-hardware.org/?probe=7bf6427590) | Nov 14, 2022 |
| Acer          | Aspire E5-722               | Notebook    | [7e26ae7fe8](https://linux-hardware.org/?probe=7e26ae7fe8) | Nov 14, 2022 |
| Gigabyte      | H97-HD3                     | Desktop     | [8a2f5e3f03](https://linux-hardware.org/?probe=8a2f5e3f03) | Nov 14, 2022 |
| Gigabyte      | H97-HD3                     | Desktop     | [b99ae215e4](https://linux-hardware.org/?probe=b99ae215e4) | Nov 14, 2022 |
| Intel         | NUC7i3DNB J57625-508        | Mini pc     | [fbaa96eef7](https://linux-hardware.org/?probe=fbaa96eef7) | Nov 14, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [298f1bd357](https://linux-hardware.org/?probe=298f1bd357) | Nov 14, 2022 |
| Lenovo        | IdeaPad 320-17AST 80XW      | Notebook    | [d8e3815f50](https://linux-hardware.org/?probe=d8e3815f50) | Nov 14, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f532c6bdb1](https://linux-hardware.org/?probe=f532c6bdb1) | Nov 13, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2dddaa52cd](https://linux-hardware.org/?probe=2dddaa52cd) | Nov 13, 2022 |
| Dell          | Vostro 3578                 | Notebook    | [1fa1c16736](https://linux-hardware.org/?probe=1fa1c16736) | Nov 13, 2022 |
| UNOWHY        | Y13G012S4EI                 | Notebook    | [9a214b41ec](https://linux-hardware.org/?probe=9a214b41ec) | Nov 13, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [851afe02f6](https://linux-hardware.org/?probe=851afe02f6) | Nov 13, 2022 |
| Alienware     | M17xR4                      | Notebook    | [9dbd88c02e](https://linux-hardware.org/?probe=9dbd88c02e) | Nov 13, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [71c62efbb1](https://linux-hardware.org/?probe=71c62efbb1) | Nov 13, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [4ddae3c3a0](https://linux-hardware.org/?probe=4ddae3c3a0) | Nov 13, 2022 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [3b46bafe87](https://linux-hardware.org/?probe=3b46bafe87) | Nov 13, 2022 |
| MSI           | H97 GUARD-PRO               | Desktop     | [3ea9d7a74a](https://linux-hardware.org/?probe=3ea9d7a74a) | Nov 13, 2022 |
| ASUSTek       | M2NPV-VM                    | Desktop     | [db28f53298](https://linux-hardware.org/?probe=db28f53298) | Nov 12, 2022 |
| UNOWHY        | Y13G012S4EI                 | Notebook    | [51a7b4fca7](https://linux-hardware.org/?probe=51a7b4fca7) | Nov 12, 2022 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [deb10be02b](https://linux-hardware.org/?probe=deb10be02b) | Nov 12, 2022 |
| ASUSTek       | P7P55D-E LX                 | Desktop     | [cef5f6aa9f](https://linux-hardware.org/?probe=cef5f6aa9f) | Nov 12, 2022 |
| Intel         | DQ77KB AAG81483-500         | Desktop     | [eceaef0c0c](https://linux-hardware.org/?probe=eceaef0c0c) | Nov 12, 2022 |
| Biostar       | A70MD PRO                   | Desktop     | [8c9796cb09](https://linux-hardware.org/?probe=8c9796cb09) | Nov 12, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [904b7c0e89](https://linux-hardware.org/?probe=904b7c0e89) | Nov 12, 2022 |
| MSI           | B75MA-P45                   | Desktop     | [3db5e45a80](https://linux-hardware.org/?probe=3db5e45a80) | Nov 12, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [d77bd1633c](https://linux-hardware.org/?probe=d77bd1633c) | Nov 11, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [40468e1e7f](https://linux-hardware.org/?probe=40468e1e7f) | Nov 11, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [0e3e3c885a](https://linux-hardware.org/?probe=0e3e3c885a) | Nov 11, 2022 |
| MSI           | B75A-G43                    | Desktop     | [75822f5ac0](https://linux-hardware.org/?probe=75822f5ac0) | Nov 11, 2022 |
| Gigabyte      | H410M S2H V3                | Desktop     | [2172ca7325](https://linux-hardware.org/?probe=2172ca7325) | Nov 11, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [2421b6c5a4](https://linux-hardware.org/?probe=2421b6c5a4) | Nov 11, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [227f62cdb9](https://linux-hardware.org/?probe=227f62cdb9) | Nov 11, 2022 |
| Dell          | 0D441T A00                  | Desktop     | [8825499c05](https://linux-hardware.org/?probe=8825499c05) | Nov 11, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [332cc61ddc](https://linux-hardware.org/?probe=332cc61ddc) | Nov 11, 2022 |
| ASUSTek       | Benicia                     | Desktop     | [03ce113379](https://linux-hardware.org/?probe=03ce113379) | Nov 11, 2022 |
| ASUSTek       | EB1501P                     | Desktop     | [0664261b3a](https://linux-hardware.org/?probe=0664261b3a) | Nov 11, 2022 |
| ASUSTek       | EB1501P                     | Desktop     | [ad47bcfb8b](https://linux-hardware.org/?probe=ad47bcfb8b) | Nov 11, 2022 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [a1243611f4](https://linux-hardware.org/?probe=a1243611f4) | Nov 11, 2022 |
| Dell          | 0NNNCT A01                  | Desktop     | [472bcb70c1](https://linux-hardware.org/?probe=472bcb70c1) | Nov 10, 2022 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [784b2e30e1](https://linux-hardware.org/?probe=784b2e30e1) | Nov 10, 2022 |
| SHENZHEN Y... | A8S PRO                     | Notebook    | [354471ab24](https://linux-hardware.org/?probe=354471ab24) | Nov 10, 2022 |
| Dell          | 04YP6J A02                  | Desktop     | [6a3833051e](https://linux-hardware.org/?probe=6a3833051e) | Nov 10, 2022 |
| Lenovo        | ThinkPad T460 20FMS06V00    | Notebook    | [1fa4637d27](https://linux-hardware.org/?probe=1fa4637d27) | Nov 10, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [b9f262d40b](https://linux-hardware.org/?probe=b9f262d40b) | Nov 10, 2022 |
| ASUSTek       | ROG Strix G531GV_G531GV     | Notebook    | [cd4796484a](https://linux-hardware.org/?probe=cd4796484a) | Nov 10, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [e281a0277b](https://linux-hardware.org/?probe=e281a0277b) | Nov 10, 2022 |
| MSI           | GS75 Stealth 10SE           | Notebook    | [a13f6196b6](https://linux-hardware.org/?probe=a13f6196b6) | Nov 10, 2022 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [ddbdf3da0f](https://linux-hardware.org/?probe=ddbdf3da0f) | Nov 10, 2022 |
| MSI           | GS75 Stealth 10SE           | Notebook    | [eaed1093a4](https://linux-hardware.org/?probe=eaed1093a4) | Nov 10, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [e77f7ce44e](https://linux-hardware.org/?probe=e77f7ce44e) | Nov 09, 2022 |
| Acer          | RS880M05                    | Desktop     | [cb216f090c](https://linux-hardware.org/?probe=cb216f090c) | Nov 09, 2022 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [6e773a6bf0](https://linux-hardware.org/?probe=6e773a6bf0) | Nov 09, 2022 |
| ASUSTek       | B150M-C                     | Desktop     | [d2dd725b2e](https://linux-hardware.org/?probe=d2dd725b2e) | Nov 09, 2022 |
| Gigabyte      | Sabre 15                    | Notebook    | [1edede0895](https://linux-hardware.org/?probe=1edede0895) | Nov 09, 2022 |
| Apple         | Mac-F2268CC8                | All in one  | [0841a971e1](https://linux-hardware.org/?probe=0841a971e1) | Nov 09, 2022 |
| SHENZHEN Y... | A8S PRO                     | Notebook    | [e6b195843f](https://linux-hardware.org/?probe=e6b195843f) | Nov 09, 2022 |
| Dell          | Precision 5540              | Notebook    | [2d459a448d](https://linux-hardware.org/?probe=2d459a448d) | Nov 09, 2022 |
| Dell          | Latitude 5420               | Notebook    | [2eba4932bf](https://linux-hardware.org/?probe=2eba4932bf) | Nov 09, 2022 |
| BESSTAR Te... | TH50                        | Desktop     | [9e0784517f](https://linux-hardware.org/?probe=9e0784517f) | Nov 09, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [97ed2f1140](https://linux-hardware.org/?probe=97ed2f1140) | Nov 09, 2022 |
| Acer          | Aspire XC600 v1.0           | Desktop     | [9eddda7671](https://linux-hardware.org/?probe=9eddda7671) | Nov 09, 2022 |
| Apple         | Mac-F2268CC8                | All in one  | [b3db07cbc7](https://linux-hardware.org/?probe=b3db07cbc7) | Nov 08, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [08be836975](https://linux-hardware.org/?probe=08be836975) | Nov 08, 2022 |
| MSI           | MAG B560M MORTAR            | Desktop     | [d06c10f1cf](https://linux-hardware.org/?probe=d06c10f1cf) | Nov 08, 2022 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | Notebook    | [0a1efcf166](https://linux-hardware.org/?probe=0a1efcf166) | Nov 08, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [1cca3aa247](https://linux-hardware.org/?probe=1cca3aa247) | Nov 08, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [d2ab3af437](https://linux-hardware.org/?probe=d2ab3af437) | Nov 08, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [377df38ed7](https://linux-hardware.org/?probe=377df38ed7) | Nov 08, 2022 |
| ASUSTek       | VivoBook E14 E402WAS        | Notebook    | [9fe97ad66f](https://linux-hardware.org/?probe=9fe97ad66f) | Nov 08, 2022 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [2796faab6c](https://linux-hardware.org/?probe=2796faab6c) | Nov 08, 2022 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [6c277d54f9](https://linux-hardware.org/?probe=6c277d54f9) | Nov 07, 2022 |
| MSI           | MAG B560M MORTAR            | Desktop     | [5fe681b53d](https://linux-hardware.org/?probe=5fe681b53d) | Nov 07, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [d8a78ad824](https://linux-hardware.org/?probe=d8a78ad824) | Nov 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [dc375c11c7](https://linux-hardware.org/?probe=dc375c11c7) | Nov 07, 2022 |
| TUXEDO        | Pulse 15 Gen2               | Notebook    | [f0c2157642](https://linux-hardware.org/?probe=f0c2157642) | Nov 07, 2022 |
| Thomson       | N17V3C8WH512                | Notebook    | [f13487a2f3](https://linux-hardware.org/?probe=f13487a2f3) | Nov 07, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [e94c6ad334](https://linux-hardware.org/?probe=e94c6ad334) | Nov 07, 2022 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [29fd694ada](https://linux-hardware.org/?probe=29fd694ada) | Nov 07, 2022 |
| Dell          | G3 3500                     | Notebook    | [d3ae8a9d72](https://linux-hardware.org/?probe=d3ae8a9d72) | Nov 07, 2022 |
| Gigabyte      | X670 GAMING X AX            | Desktop     | [1a96ebec7a](https://linux-hardware.org/?probe=1a96ebec7a) | Nov 07, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [cbfa344eaa](https://linux-hardware.org/?probe=cbfa344eaa) | Nov 07, 2022 |
| Dell          | Latitude E5540              | Notebook    | [f2420e40cd](https://linux-hardware.org/?probe=f2420e40cd) | Nov 06, 2022 |
| Dell          | Latitude E5540              | Notebook    | [2456786404](https://linux-hardware.org/?probe=2456786404) | Nov 06, 2022 |
| Lenovo        | IdeaPad 320-17AST 80XW      | Notebook    | [08c701b06d](https://linux-hardware.org/?probe=08c701b06d) | Nov 06, 2022 |
| Dell          | Latitude E7470              | Notebook    | [1bd39e96d2](https://linux-hardware.org/?probe=1bd39e96d2) | Nov 06, 2022 |
| HP            | Unknown                     | Notebook    | [fe07901ad1](https://linux-hardware.org/?probe=fe07901ad1) | Nov 06, 2022 |
| HP            | Unknown                     | Notebook    | [495b046a6b](https://linux-hardware.org/?probe=495b046a6b) | Nov 06, 2022 |
| Timi          | Xiaomi Book Pro 16 2022     | Notebook    | [d1bcd9dd18](https://linux-hardware.org/?probe=d1bcd9dd18) | Nov 06, 2022 |
| Timi          | Xiaomi Book Pro 16 2022     | Notebook    | [2c0e88be3e](https://linux-hardware.org/?probe=2c0e88be3e) | Nov 06, 2022 |
| Thomson       | N17V3C8WH512                | Notebook    | [58d6a21b17](https://linux-hardware.org/?probe=58d6a21b17) | Nov 06, 2022 |
| Dell          | 0N826N A03                  | Desktop     | [2126bcff1e](https://linux-hardware.org/?probe=2126bcff1e) | Nov 06, 2022 |
| BESSTAR Te... | GB3                         | Mini pc     | [351c4d18c3](https://linux-hardware.org/?probe=351c4d18c3) | Nov 06, 2022 |
| HP            | EliteBook Folio 1040 G1     | Notebook    | [f2d6eec645](https://linux-hardware.org/?probe=f2d6eec645) | Nov 06, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [7e97bace0c](https://linux-hardware.org/?probe=7e97bace0c) | Nov 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E203... | Notebook    | [d793aac21d](https://linux-hardware.org/?probe=d793aac21d) | Nov 06, 2022 |
| Acer          | Aspire XC600 v1.0           | Desktop     | [440f3f42f9](https://linux-hardware.org/?probe=440f3f42f9) | Nov 06, 2022 |
| Dell          | Latitude E6520              | Notebook    | [9593951427](https://linux-hardware.org/?probe=9593951427) | Nov 06, 2022 |
| Dell          | Latitude E6520              | Notebook    | [53eedbde1f](https://linux-hardware.org/?probe=53eedbde1f) | Nov 06, 2022 |
| Thomson       | NEO14A-4SL128               | Notebook    | [5f6993914c](https://linux-hardware.org/?probe=5f6993914c) | Nov 05, 2022 |
| Apple         | Mac-F2218FC8                | All in one  | [8d633d6712](https://linux-hardware.org/?probe=8d633d6712) | Nov 05, 2022 |
| Apple         | Mac-F2218FC8                | All in one  | [d23c74b1f2](https://linux-hardware.org/?probe=d23c74b1f2) | Nov 05, 2022 |
| ASUSTek       | UX303UA                     | Notebook    | [0df719375b](https://linux-hardware.org/?probe=0df719375b) | Nov 05, 2022 |
| ASUSTek       | X756UWK                     | Notebook    | [2d165dd7b0](https://linux-hardware.org/?probe=2d165dd7b0) | Nov 05, 2022 |
| ASUSTek       | PRO H410T                   | Desktop     | [66a809ab24](https://linux-hardware.org/?probe=66a809ab24) | Nov 05, 2022 |
| ASUSTek       | UX303UA                     | Notebook    | [751669286c](https://linux-hardware.org/?probe=751669286c) | Nov 05, 2022 |
| ASUSTek       | P7P55D-E LX                 | Desktop     | [2a79c24ee2](https://linux-hardware.org/?probe=2a79c24ee2) | Nov 05, 2022 |
| ASUSTek       | X756UWK                     | Notebook    | [b89c7882f3](https://linux-hardware.org/?probe=b89c7882f3) | Nov 05, 2022 |
| Lenovo        | ThinkPad E570 20H50078FR    | Notebook    | [156f337a82](https://linux-hardware.org/?probe=156f337a82) | Nov 05, 2022 |
| HP            | 83E9                        | Desktop     | [837b4320c1](https://linux-hardware.org/?probe=837b4320c1) | Nov 05, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [ffb4ff83fd](https://linux-hardware.org/?probe=ffb4ff83fd) | Nov 05, 2022 |
| Lenovo        | ThinkPad X270 20HN0014FR    | Notebook    | [94abd977de](https://linux-hardware.org/?probe=94abd977de) | Nov 04, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [75884710cd](https://linux-hardware.org/?probe=75884710cd) | Nov 04, 2022 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [22bf532b1a](https://linux-hardware.org/?probe=22bf532b1a) | Nov 04, 2022 |
| ASUSTek       | X556URK                     | Notebook    | [c26a3705d3](https://linux-hardware.org/?probe=c26a3705d3) | Nov 04, 2022 |
| HP            | ProBook 6470b               | Notebook    | [78aa59a89a](https://linux-hardware.org/?probe=78aa59a89a) | Nov 04, 2022 |
| Gigabyte      | H97-HD3                     | Desktop     | [bb8dbe6d52](https://linux-hardware.org/?probe=bb8dbe6d52) | Nov 04, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [8fdaec6b5a](https://linux-hardware.org/?probe=8fdaec6b5a) | Nov 04, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [17bac11f6f](https://linux-hardware.org/?probe=17bac11f6f) | Nov 04, 2022 |
| HP            | 470 G7 Notebook PC          | Notebook    | [ae68dc3b2d](https://linux-hardware.org/?probe=ae68dc3b2d) | Nov 04, 2022 |
| UNOWHY        | Y13G011S4EI                 | Notebook    | [da784a5c82](https://linux-hardware.org/?probe=da784a5c82) | Nov 04, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [acb00ae29c](https://linux-hardware.org/?probe=acb00ae29c) | Nov 03, 2022 |
| Notebook      | NL40_50GU                   | Notebook    | [c74ffe668a](https://linux-hardware.org/?probe=c74ffe668a) | Nov 03, 2022 |
| MSI           | MAG B560M MORTAR            | Desktop     | [82a755ae03](https://linux-hardware.org/?probe=82a755ae03) | Nov 03, 2022 |
| Notebook      | NL40_50GU                   | Notebook    | [b3001401db](https://linux-hardware.org/?probe=b3001401db) | Nov 03, 2022 |
| HP            | ProBook 6470b               | Notebook    | [ea7c42479d](https://linux-hardware.org/?probe=ea7c42479d) | Nov 03, 2022 |
| Intel         | D33217GKE G76540-203        | Desktop     | [eb15ca5b98](https://linux-hardware.org/?probe=eb15ca5b98) | Nov 03, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [5ace066925](https://linux-hardware.org/?probe=5ace066925) | Nov 03, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [7e09b1e9bd](https://linux-hardware.org/?probe=7e09b1e9bd) | Nov 03, 2022 |
| Fujitsu Si... | AMILO Li3710                | Notebook    | [ce4f615c70](https://linux-hardware.org/?probe=ce4f615c70) | Nov 03, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [a189602082](https://linux-hardware.org/?probe=a189602082) | Nov 03, 2022 |
| ASUSTek       | P8Z77-V                     | Desktop     | [adb4579fb7](https://linux-hardware.org/?probe=adb4579fb7) | Nov 03, 2022 |
| Acer          | Swift SF314-57              | Notebook    | [8ab3b70362](https://linux-hardware.org/?probe=8ab3b70362) | Nov 03, 2022 |
| Intel         | D33217GKE G76540-203        | Desktop     | [20824af437](https://linux-hardware.org/?probe=20824af437) | Nov 03, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [fe4a007f99](https://linux-hardware.org/?probe=fe4a007f99) | Nov 03, 2022 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [2ac949f7f9](https://linux-hardware.org/?probe=2ac949f7f9) | Nov 03, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [d754cc7217](https://linux-hardware.org/?probe=d754cc7217) | Nov 03, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [dfe209bf08](https://linux-hardware.org/?probe=dfe209bf08) | Nov 03, 2022 |
| Dell          | G15 5511                    | Notebook    | [6965880757](https://linux-hardware.org/?probe=6965880757) | Nov 02, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [c54743b7e8](https://linux-hardware.org/?probe=c54743b7e8) | Nov 02, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [24a3f977bf](https://linux-hardware.org/?probe=24a3f977bf) | Nov 02, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [14184ac3d9](https://linux-hardware.org/?probe=14184ac3d9) | Nov 02, 2022 |
| Toshiba       | Satellite C70D-A            | Notebook    | [7a421ed810](https://linux-hardware.org/?probe=7a421ed810) | Nov 02, 2022 |
| Toshiba       | Satellite C70D-A            | Notebook    | [d82227846b](https://linux-hardware.org/?probe=d82227846b) | Nov 02, 2022 |
| Dell          | G3 3500                     | Notebook    | [c595a16f59](https://linux-hardware.org/?probe=c595a16f59) | Nov 02, 2022 |
| Dell          | 0JGM7F A00                  | Desktop     | [28f4800b2b](https://linux-hardware.org/?probe=28f4800b2b) | Nov 02, 2022 |
| Dell          | Latitude 5420               | Notebook    | [679fbcb14f](https://linux-hardware.org/?probe=679fbcb14f) | Nov 02, 2022 |
| Dell          | 0TWFTR A02                  | All in one  | [21b78069dd](https://linux-hardware.org/?probe=21b78069dd) | Nov 02, 2022 |
| Intel         | NUC7i3DNB J57625-508        | Mini pc     | [075f628a80](https://linux-hardware.org/?probe=075f628a80) | Nov 02, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [65231808f8](https://linux-hardware.org/?probe=65231808f8) | Nov 02, 2022 |
| Lenovo        | IdeaPad 320-17AST 80XW      | Notebook    | [9fa0489d64](https://linux-hardware.org/?probe=9fa0489d64) | Nov 01, 2022 |
| Lenovo        | IdeaPad 320-17AST 80XW      | Notebook    | [411a5da53c](https://linux-hardware.org/?probe=411a5da53c) | Nov 01, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [6a0d7d5f39](https://linux-hardware.org/?probe=6a0d7d5f39) | Nov 01, 2022 |
| Dell          | 0XR1GT A00                  | Desktop     | [8f551aaa52](https://linux-hardware.org/?probe=8f551aaa52) | Nov 01, 2022 |
| HP            | Pavilion dv5                | Notebook    | [fb23cec1a6](https://linux-hardware.org/?probe=fb23cec1a6) | Nov 01, 2022 |
| Toshiba       | Satellite C70D-B            | Notebook    | [ccf4e200fb](https://linux-hardware.org/?probe=ccf4e200fb) | Nov 01, 2022 |
| Lenovo        | 3130 SDK0J40697 WIN 3305... | Mini pc     | [08649bd1e9](https://linux-hardware.org/?probe=08649bd1e9) | Nov 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [cf9998e9b9](https://linux-hardware.org/?probe=cf9998e9b9) | Nov 01, 2022 |
| ASUSTek       | S551LN                      | Notebook    | [67e15a659d](https://linux-hardware.org/?probe=67e15a659d) | Oct 31, 2022 |
| Valve         | Jupiter                     | Notebook    | [9d237f0d30](https://linux-hardware.org/?probe=9d237f0d30) | Oct 31, 2022 |
| Dell          | 03NVJ6 A03                  | Desktop     | [adebd09dc4](https://linux-hardware.org/?probe=adebd09dc4) | Oct 31, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [71cf98e6e8](https://linux-hardware.org/?probe=71cf98e6e8) | Oct 31, 2022 |
| HP            | Compaq nc6320 (EV073AV)     | Notebook    | [b73f359ded](https://linux-hardware.org/?probe=b73f359ded) | Oct 31, 2022 |
| ASRock        | B560M Pro4                  | Desktop     | [865aef7529](https://linux-hardware.org/?probe=865aef7529) | Oct 31, 2022 |
| Acer          | Extensa 5635Z               | Notebook    | [35ce596e08](https://linux-hardware.org/?probe=35ce596e08) | Oct 31, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [fb96cd8e21](https://linux-hardware.org/?probe=fb96cd8e21) | Oct 31, 2022 |
| Dell          | Latitude E5500              | Notebook    | [c64399793c](https://linux-hardware.org/?probe=c64399793c) | Oct 31, 2022 |
| HP            | Compaq Presario CQ71        | Notebook    | [ea057ea9b9](https://linux-hardware.org/?probe=ea057ea9b9) | Oct 31, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [ce59648f62](https://linux-hardware.org/?probe=ce59648f62) | Oct 31, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [e993af2670](https://linux-hardware.org/?probe=e993af2670) | Oct 31, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [acfa0d90d6](https://linux-hardware.org/?probe=acfa0d90d6) | Oct 31, 2022 |
| Lenovo        | ThinkPad X270 20HN0014FR    | Notebook    | [d6fc7c48a1](https://linux-hardware.org/?probe=d6fc7c48a1) | Oct 30, 2022 |
| ASUSTek       | P7P55D-E PRO                | Desktop     | [1e0daee604](https://linux-hardware.org/?probe=1e0daee604) | Oct 30, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [ad558f1150](https://linux-hardware.org/?probe=ad558f1150) | Oct 30, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [e8a1f8f6bf](https://linux-hardware.org/?probe=e8a1f8f6bf) | Oct 30, 2022 |
| HP            | 158B                        | Desktop     | [9c02b7fe58](https://linux-hardware.org/?probe=9c02b7fe58) | Oct 30, 2022 |
| ASUSTek       | G74Sx                       | Notebook    | [c24c24ab27](https://linux-hardware.org/?probe=c24c24ab27) | Oct 30, 2022 |
| Dell          | XPS L322X                   | Notebook    | [cacebfe41e](https://linux-hardware.org/?probe=cacebfe41e) | Oct 30, 2022 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [d4552d84d5](https://linux-hardware.org/?probe=d4552d84d5) | Oct 30, 2022 |
| Intel         | D33217GKE G76540-203        | Desktop     | [95238cc6e8](https://linux-hardware.org/?probe=95238cc6e8) | Oct 30, 2022 |
| Intel         | D33217GKE G76540-203        | Desktop     | [51a91ba41f](https://linux-hardware.org/?probe=51a91ba41f) | Oct 30, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [6873e5b579](https://linux-hardware.org/?probe=6873e5b579) | Oct 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [d4c562a178](https://linux-hardware.org/?probe=d4c562a178) | Oct 30, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [da1b668449](https://linux-hardware.org/?probe=da1b668449) | Oct 30, 2022 |
| ASUSTek       | E200HA                      | Notebook    | [18ca81370b](https://linux-hardware.org/?probe=18ca81370b) | Oct 29, 2022 |
| ASUSTek       | E200HA                      | Notebook    | [0a95698cb6](https://linux-hardware.org/?probe=0a95698cb6) | Oct 29, 2022 |
| HP            | Compaq 615                  | Notebook    | [ae90fa3742](https://linux-hardware.org/?probe=ae90fa3742) | Oct 29, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [16815dacc1](https://linux-hardware.org/?probe=16815dacc1) | Oct 29, 2022 |
| HP            | OMEN by Laptop              | Notebook    | [610be75cca](https://linux-hardware.org/?probe=610be75cca) | Oct 29, 2022 |
| ASUSTek       | X751NV                      | Notebook    | [9ef2717db0](https://linux-hardware.org/?probe=9ef2717db0) | Oct 29, 2022 |
| HP            | 8653 A                      | Desktop     | [bc1f3b445b](https://linux-hardware.org/?probe=bc1f3b445b) | Oct 28, 2022 |
| IP3 Tech      | AP1                         | Notebook    | [0562a6a46d](https://linux-hardware.org/?probe=0562a6a46d) | Oct 28, 2022 |
| Notebook      | NV4xPZ                      | Notebook    | [86e7370778](https://linux-hardware.org/?probe=86e7370778) | Oct 28, 2022 |
| IP3 Tech      | AP1                         | Notebook    | [2a9c0ff1c5](https://linux-hardware.org/?probe=2a9c0ff1c5) | Oct 28, 2022 |
| Dell          | 02M8NY A01                  | Desktop     | [47c0e65f02](https://linux-hardware.org/?probe=47c0e65f02) | Oct 28, 2022 |
| Dell          | 0XHGV1 A00                  | Desktop     | [8fad928e72](https://linux-hardware.org/?probe=8fad928e72) | Oct 28, 2022 |
| Intel         | D33217GKE G76540-203        | Desktop     | [2501d67199](https://linux-hardware.org/?probe=2501d67199) | Oct 28, 2022 |
| Intel         | D33217GKE G76540-203        | Desktop     | [9827bdf3f6](https://linux-hardware.org/?probe=9827bdf3f6) | Oct 28, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [267b0a3f94](https://linux-hardware.org/?probe=267b0a3f94) | Oct 28, 2022 |
| Lenovo        | ThinkPad T560 20FHCTO1WW    | Notebook    | [05ff2d32fa](https://linux-hardware.org/?probe=05ff2d32fa) | Oct 28, 2022 |
| Lenovo        | ThinkPad T560 20FHCTO1WW    | Notebook    | [403a99d8b2](https://linux-hardware.org/?probe=403a99d8b2) | Oct 28, 2022 |
| ASUSTek       | ET2700I                     | Desktop     | [ce0d0e61eb](https://linux-hardware.org/?probe=ce0d0e61eb) | Oct 28, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | Notebook    | [0c6a68368c](https://linux-hardware.org/?probe=0c6a68368c) | Oct 27, 2022 |
| ASUSTek       | N501VW                      | Notebook    | [07f7d43f09](https://linux-hardware.org/?probe=07f7d43f09) | Oct 27, 2022 |
| Acer          | Extensa 2509                | Notebook    | [a27b3d38a9](https://linux-hardware.org/?probe=a27b3d38a9) | Oct 27, 2022 |
| Intel         | ArcherCity                  | Server      | [625da68153](https://linux-hardware.org/?probe=625da68153) | Oct 27, 2022 |
| Alienware     | m17 R4                      | Notebook    | [14770101cf](https://linux-hardware.org/?probe=14770101cf) | Oct 27, 2022 |
| MSI           | B85-G43                     | Desktop     | [48ac016cd9](https://linux-hardware.org/?probe=48ac016cd9) | Oct 27, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [8c9d6eb128](https://linux-hardware.org/?probe=8c9d6eb128) | Oct 27, 2022 |
| Dell          | Latitude 5310               | Notebook    | [10b8371dbd](https://linux-hardware.org/?probe=10b8371dbd) | Oct 27, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [6aaeaf667c](https://linux-hardware.org/?probe=6aaeaf667c) | Oct 27, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEP... | Notebook    | [9564d50ef8](https://linux-hardware.org/?probe=9564d50ef8) | Oct 27, 2022 |
| Acer          | Swift SF314-512             | Notebook    | [951c734c1b](https://linux-hardware.org/?probe=951c734c1b) | Oct 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [088235cbff](https://linux-hardware.org/?probe=088235cbff) | Oct 26, 2022 |
| Dell          | Precision 7560              | Notebook    | [c82d6a32a5](https://linux-hardware.org/?probe=c82d6a32a5) | Oct 26, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [6062baa35c](https://linux-hardware.org/?probe=6062baa35c) | Oct 26, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [34be38a48b](https://linux-hardware.org/?probe=34be38a48b) | Oct 26, 2022 |
| Dell          | 05WNJ2 A02                  | Server      | [97d42fd93a](https://linux-hardware.org/?probe=97d42fd93a) | Oct 26, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [6b0380ea4c](https://linux-hardware.org/?probe=6b0380ea4c) | Oct 26, 2022 |
| ASUSTek       | GL753VD                     | Notebook    | [08b067d2cf](https://linux-hardware.org/?probe=08b067d2cf) | Oct 25, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | Notebook    | [a128f79c0a](https://linux-hardware.org/?probe=a128f79c0a) | Oct 25, 2022 |
| ASUSTek       | VivoBook E14 E402WAS        | Notebook    | [eadb224c05](https://linux-hardware.org/?probe=eadb224c05) | Oct 25, 2022 |
| Raspberry ... | Raspberry Pi Zero Rev 1.... | Soc         | [80cd406dda](https://linux-hardware.org/?probe=80cd406dda) | Oct 25, 2022 |
| Dell          | Inspiron 7737               | Notebook    | [727b48a339](https://linux-hardware.org/?probe=727b48a339) | Oct 25, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [8f246bccb1](https://linux-hardware.org/?probe=8f246bccb1) | Oct 25, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [bc5adf7f4b](https://linux-hardware.org/?probe=bc5adf7f4b) | Oct 25, 2022 |
| Valve         | Jupiter                     | Notebook    | [6ed87cbcfb](https://linux-hardware.org/?probe=6ed87cbcfb) | Oct 25, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [055062356e](https://linux-hardware.org/?probe=055062356e) | Oct 25, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | Notebook    | [ec7f3834d1](https://linux-hardware.org/?probe=ec7f3834d1) | Oct 25, 2022 |
| Toshiba       | Satellite A505              | Notebook    | [41dafcbfb9](https://linux-hardware.org/?probe=41dafcbfb9) | Oct 25, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [4e2d4383c0](https://linux-hardware.org/?probe=4e2d4383c0) | Oct 25, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [a9e26a3899](https://linux-hardware.org/?probe=a9e26a3899) | Oct 25, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [3ab5922ddf](https://linux-hardware.org/?probe=3ab5922ddf) | Oct 25, 2022 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [814da05eec](https://linux-hardware.org/?probe=814da05eec) | Oct 25, 2022 |
| Lenovo        | G50-45 80MQ                 | Notebook    | [1c6d041ce2](https://linux-hardware.org/?probe=1c6d041ce2) | Oct 25, 2022 |
| ASUSTek       | TUF Z390-PRO GAMING         | Desktop     | [2c4d63c9b2](https://linux-hardware.org/?probe=2c4d63c9b2) | Oct 24, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [544988df6e](https://linux-hardware.org/?probe=544988df6e) | Oct 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [fe664e172e](https://linux-hardware.org/?probe=fe664e172e) | Oct 24, 2022 |
| Dell          | 0GX297                      | Desktop     | [a047bbd7a0](https://linux-hardware.org/?probe=a047bbd7a0) | Oct 24, 2022 |
| Dell          | Studio 1737                 | Notebook    | [d6e17c05b2](https://linux-hardware.org/?probe=d6e17c05b2) | Oct 24, 2022 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [af2163c4dd](https://linux-hardware.org/?probe=af2163c4dd) | Oct 24, 2022 |
| Packard Be... | H17HV                       | Notebook    | [2e94cfdd84](https://linux-hardware.org/?probe=2e94cfdd84) | Oct 24, 2022 |
| HP            | 8055                        | Desktop     | [624dddbaec](https://linux-hardware.org/?probe=624dddbaec) | Oct 24, 2022 |
| MSI           | Pulse GL76 12UEK            | Notebook    | [bb06dc4756](https://linux-hardware.org/?probe=bb06dc4756) | Oct 24, 2022 |
| Dell          | 0J3C2F A00                  | Desktop     | [d165241883](https://linux-hardware.org/?probe=d165241883) | Oct 24, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [646b07cc4c](https://linux-hardware.org/?probe=646b07cc4c) | Oct 24, 2022 |
| ASRock        | P45TS                       | Desktop     | [484f63b830](https://linux-hardware.org/?probe=484f63b830) | Oct 24, 2022 |
| Packard Be... | EasyNote ENTE70BH           | Notebook    | [2135a5aed7](https://linux-hardware.org/?probe=2135a5aed7) | Oct 23, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [17adb9ee1e](https://linux-hardware.org/?probe=17adb9ee1e) | Oct 23, 2022 |
| Sony          | VGN-SZ3XP_C                 | Notebook    | [72f83141a0](https://linux-hardware.org/?probe=72f83141a0) | Oct 23, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [50b6612f7d](https://linux-hardware.org/?probe=50b6612f7d) | Oct 23, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [42280c6145](https://linux-hardware.org/?probe=42280c6145) | Oct 23, 2022 |
| HP            | 805D                        | Desktop     | [916b6f09ac](https://linux-hardware.org/?probe=916b6f09ac) | Oct 23, 2022 |
| Dell          | Precision 7750              | Notebook    | [dd51bb7ccd](https://linux-hardware.org/?probe=dd51bb7ccd) | Oct 23, 2022 |
| HP            | 8055                        | Desktop     | [27793140bf](https://linux-hardware.org/?probe=27793140bf) | Oct 23, 2022 |
| Lenovo        | ThinkPad X240 20AMS01M00    | Notebook    | [2f1c7b7716](https://linux-hardware.org/?probe=2f1c7b7716) | Oct 23, 2022 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [e2d21dcb54](https://linux-hardware.org/?probe=e2d21dcb54) | Oct 23, 2022 |
| Dell          | Latitude E6510              | Notebook    | [73cd1082f8](https://linux-hardware.org/?probe=73cd1082f8) | Oct 22, 2022 |
| Dell          | Latitude 5420               | Notebook    | [dd9b95a216](https://linux-hardware.org/?probe=dd9b95a216) | Oct 22, 2022 |
| Acer          | TravelMate P256-M           | Notebook    | [7ca952de68](https://linux-hardware.org/?probe=7ca952de68) | Oct 22, 2022 |
| ASUSTek       | ZenBook UX534FAC_UX534FA    | Notebook    | [928997f65c](https://linux-hardware.org/?probe=928997f65c) | Oct 22, 2022 |
| MSI           | MAG Z690 TORPEDO            | Desktop     | [381a618ea5](https://linux-hardware.org/?probe=381a618ea5) | Oct 22, 2022 |
| Dell          | Latitude E6520              | Notebook    | [88af6c857c](https://linux-hardware.org/?probe=88af6c857c) | Oct 22, 2022 |
| Dell          | Latitude E6520              | Notebook    | [246517ceab](https://linux-hardware.org/?probe=246517ceab) | Oct 22, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [312828c6a3](https://linux-hardware.org/?probe=312828c6a3) | Oct 22, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [57bfd1e0e9](https://linux-hardware.org/?probe=57bfd1e0e9) | Oct 22, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [77463ad1d7](https://linux-hardware.org/?probe=77463ad1d7) | Oct 21, 2022 |
| HP            | ProBook 6550b               | Notebook    | [cc300bedc8](https://linux-hardware.org/?probe=cc300bedc8) | Oct 21, 2022 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [85bbd08363](https://linux-hardware.org/?probe=85bbd08363) | Oct 21, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [a22e54462c](https://linux-hardware.org/?probe=a22e54462c) | Oct 21, 2022 |
| HP            | Stream Notebook             | Notebook    | [685271f268](https://linux-hardware.org/?probe=685271f268) | Oct 21, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [45d7e6a1aa](https://linux-hardware.org/?probe=45d7e6a1aa) | Oct 21, 2022 |
| MAXDATA       | obook2-1                    | Notebook    | [c7e03dae2f](https://linux-hardware.org/?probe=c7e03dae2f) | Oct 21, 2022 |
| Radxa         | ROCK Pi X v1.4              | Notebook    | [133d713246](https://linux-hardware.org/?probe=133d713246) | Oct 21, 2022 |
| Gigabyte      | GA-790FXTA-UD5              | Desktop     | [78218a5b63](https://linux-hardware.org/?probe=78218a5b63) | Oct 21, 2022 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [3d5bfd2ba5](https://linux-hardware.org/?probe=3d5bfd2ba5) | Oct 21, 2022 |
| Lenovo        | ThinkPad R61 8935AC7        | Notebook    | [94d73589fc](https://linux-hardware.org/?probe=94d73589fc) | Oct 21, 2022 |
| HP            | EliteBook 830 G8 Noteboo... | Notebook    | [47ca27793e](https://linux-hardware.org/?probe=47ca27793e) | Oct 21, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [5e86d7b8a7](https://linux-hardware.org/?probe=5e86d7b8a7) | Oct 21, 2022 |
| ASUSTek       | M32CD4-K                    | Desktop     | [0b5131c630](https://linux-hardware.org/?probe=0b5131c630) | Oct 21, 2022 |
| Unknown       | Unknown                     | Desktop     | [26c773d138](https://linux-hardware.org/?probe=26c773d138) | Oct 21, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [a9f7d04fbd](https://linux-hardware.org/?probe=a9f7d04fbd) | Oct 21, 2022 |
| MSI           | H81M-P33                    | Desktop     | [4bc1726059](https://linux-hardware.org/?probe=4bc1726059) | Oct 21, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [7acb5493d7](https://linux-hardware.org/?probe=7acb5493d7) | Oct 21, 2022 |
| MAXDATA       | obook2-1                    | Notebook    | [0f73d884ff](https://linux-hardware.org/?probe=0f73d884ff) | Oct 21, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [d575515de3](https://linux-hardware.org/?probe=d575515de3) | Oct 20, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [02643d35a4](https://linux-hardware.org/?probe=02643d35a4) | Oct 20, 2022 |
| ASUSTek       | G75VW                       | Notebook    | [194959e65e](https://linux-hardware.org/?probe=194959e65e) | Oct 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [ea0d3e9186](https://linux-hardware.org/?probe=ea0d3e9186) | Oct 20, 2022 |
| Acer          | Aspire XC-705               | Desktop     | [535cc5230e](https://linux-hardware.org/?probe=535cc5230e) | Oct 20, 2022 |
| Gigabyte      | X7X7                        | Notebook    | [f2c35e3917](https://linux-hardware.org/?probe=f2c35e3917) | Oct 20, 2022 |
| HP            | ProBook 6550b               | Notebook    | [176fc347d2](https://linux-hardware.org/?probe=176fc347d2) | Oct 20, 2022 |
| HP            | EliteBook 840 Aero G8 No... | Notebook    | [80738ede80](https://linux-hardware.org/?probe=80738ede80) | Oct 20, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [c8e47b28fe](https://linux-hardware.org/?probe=c8e47b28fe) | Oct 20, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [ef1acaa7da](https://linux-hardware.org/?probe=ef1acaa7da) | Oct 20, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [3ec2887574](https://linux-hardware.org/?probe=3ec2887574) | Oct 20, 2022 |
| Dell          | Precision 5510              | Notebook    | [bb7788ce01](https://linux-hardware.org/?probe=bb7788ce01) | Oct 20, 2022 |
| Alienware     | x15 R2                      | Notebook    | [39d9f7988a](https://linux-hardware.org/?probe=39d9f7988a) | Oct 20, 2022 |
| ASUSTek       | ROG Maximus XI FORMULA      | Desktop     | [13830a8b2b](https://linux-hardware.org/?probe=13830a8b2b) | Oct 20, 2022 |
| Dell          | Latitude 5420               | Notebook    | [a6ef44d08a](https://linux-hardware.org/?probe=a6ef44d08a) | Oct 20, 2022 |
| Acer          | Veriton X2631G V:1.0        | Desktop     | [4becf50dac](https://linux-hardware.org/?probe=4becf50dac) | Oct 19, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [5a8ac06ce5](https://linux-hardware.org/?probe=5a8ac06ce5) | Oct 19, 2022 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [cd36bb86da](https://linux-hardware.org/?probe=cd36bb86da) | Oct 19, 2022 |
| Dell          | Latitude 7300               | Notebook    | [5674456b5d](https://linux-hardware.org/?probe=5674456b5d) | Oct 19, 2022 |
| Dell          | 0CRH6C A00                  | Desktop     | [457122aa94](https://linux-hardware.org/?probe=457122aa94) | Oct 19, 2022 |
| ASUSTek       | P8B75-M LX                  | Desktop     | [b97b4b3d9a](https://linux-hardware.org/?probe=b97b4b3d9a) | Oct 19, 2022 |
| ASUSTek       | P8B75-M LX                  | Desktop     | [827927ddce](https://linux-hardware.org/?probe=827927ddce) | Oct 19, 2022 |
| ASRock        | 970 Extreme3                | Desktop     | [23f7ae20e3](https://linux-hardware.org/?probe=23f7ae20e3) | Oct 19, 2022 |
| Dell          | 0Y7WYT A00                  | Desktop     | [285952dd76](https://linux-hardware.org/?probe=285952dd76) | Oct 19, 2022 |
| HP            | 1905                        | Desktop     | [34b81558fc](https://linux-hardware.org/?probe=34b81558fc) | Oct 19, 2022 |
| HP            | 620                         | Notebook    | [263e2a0ba9](https://linux-hardware.org/?probe=263e2a0ba9) | Oct 19, 2022 |
| Notebook      | NS50_70MU                   | Notebook    | [0f13ae1769](https://linux-hardware.org/?probe=0f13ae1769) | Oct 19, 2022 |
| Notebook      | NS50_70MU                   | Notebook    | [2df95e6892](https://linux-hardware.org/?probe=2df95e6892) | Oct 19, 2022 |
| HP            | 620                         | Notebook    | [ad17206515](https://linux-hardware.org/?probe=ad17206515) | Oct 18, 2022 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [e0c8c2fe15](https://linux-hardware.org/?probe=e0c8c2fe15) | Oct 18, 2022 |
| MSI           | H61M-E33                    | Desktop     | [7591f8fa5f](https://linux-hardware.org/?probe=7591f8fa5f) | Oct 18, 2022 |
| HP            | 1905                        | Desktop     | [37cd2f3dc2](https://linux-hardware.org/?probe=37cd2f3dc2) | Oct 18, 2022 |
| Dell          | Precision 7750              | Notebook    | [93dcf0527b](https://linux-hardware.org/?probe=93dcf0527b) | Oct 18, 2022 |
| Dell          | Precision 7750              | Notebook    | [d32782f149](https://linux-hardware.org/?probe=d32782f149) | Oct 18, 2022 |
| Dell          | 0K7CVF A03                  | Server      | [f5274874b0](https://linux-hardware.org/?probe=f5274874b0) | Oct 18, 2022 |
| ASUSTek       | G75VW                       | Notebook    | [5ee12be257](https://linux-hardware.org/?probe=5ee12be257) | Oct 18, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [aa5b8fb98e](https://linux-hardware.org/?probe=aa5b8fb98e) | Oct 18, 2022 |
| Insyde        | WindTab89                   | Notebook    | [8eb81874bb](https://linux-hardware.org/?probe=8eb81874bb) | Oct 18, 2022 |
| ASRock        | H310M-STX                   | Desktop     | [56f9a169fa](https://linux-hardware.org/?probe=56f9a169fa) | Oct 18, 2022 |
| UNOWHY        | Y13G010S4EI                 | Notebook    | [f7f13866aa](https://linux-hardware.org/?probe=f7f13866aa) | Oct 18, 2022 |
| Dell          | Latitude 7300               | Notebook    | [c9bc03da26](https://linux-hardware.org/?probe=c9bc03da26) | Oct 18, 2022 |
| HP            | ZBook 14 G2                 | Notebook    | [fde830d956](https://linux-hardware.org/?probe=fde830d956) | Oct 18, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [db3ce64578](https://linux-hardware.org/?probe=db3ce64578) | Oct 18, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [621cca0fca](https://linux-hardware.org/?probe=621cca0fca) | Oct 18, 2022 |
| Sony          | VPCEH3U1E                   | Notebook    | [aff8f19a59](https://linux-hardware.org/?probe=aff8f19a59) | Oct 18, 2022 |
| Sony          | VPCEH3U1E                   | Notebook    | [c33d20c223](https://linux-hardware.org/?probe=c33d20c223) | Oct 18, 2022 |
| HP            | Pavilion dv7                | Notebook    | [bb650e8400](https://linux-hardware.org/?probe=bb650e8400) | Oct 18, 2022 |
| ASUSTek       | TUF Gaming B460-PLUS        | Desktop     | [5823a0c5d0](https://linux-hardware.org/?probe=5823a0c5d0) | Oct 18, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [e61760eab3](https://linux-hardware.org/?probe=e61760eab3) | Oct 18, 2022 |
| Dell          | Precision 3570              | Notebook    | [90711415f5](https://linux-hardware.org/?probe=90711415f5) | Oct 18, 2022 |
| ASUSTek       | F9S                         | Notebook    | [c8df776935](https://linux-hardware.org/?probe=c8df776935) | Oct 17, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [bbff53957f](https://linux-hardware.org/?probe=bbff53957f) | Oct 17, 2022 |
| MSI           | H310M PRO-VD PLUS           | Desktop     | [359822ae5f](https://linux-hardware.org/?probe=359822ae5f) | Oct 17, 2022 |
| Gigabyte      | 970A-D3                     | Desktop     | [9f5d48a7c6](https://linux-hardware.org/?probe=9f5d48a7c6) | Oct 17, 2022 |
| Dell          | G3 3500                     | Notebook    | [64698d52bb](https://linux-hardware.org/?probe=64698d52bb) | Oct 17, 2022 |
| Dell          | G3 3500                     | Notebook    | [902fc2d51b](https://linux-hardware.org/?probe=902fc2d51b) | Oct 17, 2022 |
| ASUSTek       | G75VW                       | Notebook    | [10bcc184e7](https://linux-hardware.org/?probe=10bcc184e7) | Oct 17, 2022 |
| UNOWHY        | Y13G010S4EI                 | Notebook    | [fca234fc49](https://linux-hardware.org/?probe=fca234fc49) | Oct 17, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [a4ebad3748](https://linux-hardware.org/?probe=a4ebad3748) | Oct 17, 2022 |
| MSI           | B250M PRO-VD                | Desktop     | [28d9942c9f](https://linux-hardware.org/?probe=28d9942c9f) | Oct 17, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [9e37b60507](https://linux-hardware.org/?probe=9e37b60507) | Oct 16, 2022 |
| Lenovo        | 3307 NOK                    | Mini pc     | [df054eec71](https://linux-hardware.org/?probe=df054eec71) | Oct 16, 2022 |
| ASUSTek       | G75VW                       | Notebook    | [a88a291921](https://linux-hardware.org/?probe=a88a291921) | Oct 16, 2022 |
| ASUSTek       | M70Vn                       | Notebook    | [e9301bdee2](https://linux-hardware.org/?probe=e9301bdee2) | Oct 16, 2022 |
| Dell          | Latitude 3500               | Notebook    | [d578b45420](https://linux-hardware.org/?probe=d578b45420) | Oct 16, 2022 |
| Dell          | Latitude E5420              | Notebook    | [dcc7463646](https://linux-hardware.org/?probe=dcc7463646) | Oct 16, 2022 |
| HP            | ENVY 17                     | Notebook    | [ab25d54223](https://linux-hardware.org/?probe=ab25d54223) | Oct 16, 2022 |
| UNOWHY        | Y13G011S4EI                 | Notebook    | [c210cda35b](https://linux-hardware.org/?probe=c210cda35b) | Oct 16, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [d73a82b798](https://linux-hardware.org/?probe=d73a82b798) | Oct 15, 2022 |
| Valve         | Jupiter                     | Notebook    | [7559400f9a](https://linux-hardware.org/?probe=7559400f9a) | Oct 15, 2022 |
| ASUSTek       | X751NV                      | Notebook    | [174ee8f3e7](https://linux-hardware.org/?probe=174ee8f3e7) | Oct 15, 2022 |
| HP            | 1850                        | Desktop     | [eda9bb7861](https://linux-hardware.org/?probe=eda9bb7861) | Oct 15, 2022 |
| Dell          | Latitude 5400               | Notebook    | [645c7a01da](https://linux-hardware.org/?probe=645c7a01da) | Oct 15, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [6e45f7ecd7](https://linux-hardware.org/?probe=6e45f7ecd7) | Oct 15, 2022 |
| Acer          | AOD257                      | Notebook    | [41a717913c](https://linux-hardware.org/?probe=41a717913c) | Oct 15, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [5038f48b66](https://linux-hardware.org/?probe=5038f48b66) | Oct 15, 2022 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [1a0ed356d7](https://linux-hardware.org/?probe=1a0ed356d7) | Oct 15, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [3f3d531577](https://linux-hardware.org/?probe=3f3d531577) | Oct 15, 2022 |
| Acer          | Aspire 7730ZG               | Notebook    | [4796b36078](https://linux-hardware.org/?probe=4796b36078) | Oct 15, 2022 |
| Acer          | Aspire 7740                 | Notebook    | [a68780a6fd](https://linux-hardware.org/?probe=a68780a6fd) | Oct 15, 2022 |
| Lenovo        | ThinkPad L420 78545EG       | Notebook    | [d2c975644c](https://linux-hardware.org/?probe=d2c975644c) | Oct 15, 2022 |
| ASRock        | J5040-ITX                   | Desktop     | [aee52607f0](https://linux-hardware.org/?probe=aee52607f0) | Oct 14, 2022 |
| Medion        | MS-7797                     | Desktop     | [c6174b67dd](https://linux-hardware.org/?probe=c6174b67dd) | Oct 14, 2022 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [ebada4e791](https://linux-hardware.org/?probe=ebada4e791) | Oct 14, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [85766540b3](https://linux-hardware.org/?probe=85766540b3) | Oct 14, 2022 |
| Lenovo        | 3307 NOK                    | Mini pc     | [5bb64d91e9](https://linux-hardware.org/?probe=5bb64d91e9) | Oct 14, 2022 |
| Dell          | 0GY6Y8 A01                  | Desktop     | [06e46e98b4](https://linux-hardware.org/?probe=06e46e98b4) | Oct 14, 2022 |
| Dell          | Inspiron 7415 2-in-1        | Convertible | [5a0485a292](https://linux-hardware.org/?probe=5a0485a292) | Oct 14, 2022 |
| ZOTAC         | ZBOX-ECM73070C/53060C       | Mini pc     | [b93a697af0](https://linux-hardware.org/?probe=b93a697af0) | Oct 14, 2022 |
| Lenovo        | ThinkPad T420 4236JY2       | Notebook    | [fd260f87a9](https://linux-hardware.org/?probe=fd260f87a9) | Oct 14, 2022 |
| Dell          | G3 3500                     | Notebook    | [f7cc47bb67](https://linux-hardware.org/?probe=f7cc47bb67) | Oct 13, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | Notebook    | [e4c404552a](https://linux-hardware.org/?probe=e4c404552a) | Oct 13, 2022 |
| Pegatron      | 2A94                        | Desktop     | [038d49b359](https://linux-hardware.org/?probe=038d49b359) | Oct 13, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [fe9dde997d](https://linux-hardware.org/?probe=fe9dde997d) | Oct 13, 2022 |
| Unknown       | Unknown                     | Desktop     | [8a680cbcbe](https://linux-hardware.org/?probe=8a680cbcbe) | Oct 13, 2022 |
| MSI           | Z87 XPOWER                  | Desktop     | [5e73f5004a](https://linux-hardware.org/?probe=5e73f5004a) | Oct 13, 2022 |
| MSI           | GE70 2QE                    | Notebook    | [2825343a52](https://linux-hardware.org/?probe=2825343a52) | Oct 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [d1c1c4adea](https://linux-hardware.org/?probe=d1c1c4adea) | Oct 13, 2022 |
| Lenovo        | ThinkCentre M71e 3167B28    | Desktop     | [0cfbd3c2fc](https://linux-hardware.org/?probe=0cfbd3c2fc) | Oct 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 34481... | Notebook    | [adce18affa](https://linux-hardware.org/?probe=adce18affa) | Oct 13, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [679af656c1](https://linux-hardware.org/?probe=679af656c1) | Oct 13, 2022 |
| UNOWHY        | Y13G011S4EI                 | Notebook    | [2be4dc3fc2](https://linux-hardware.org/?probe=2be4dc3fc2) | Oct 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [dfc5a5f754](https://linux-hardware.org/?probe=dfc5a5f754) | Oct 13, 2022 |
| Dell          | Latitude E5550              | Notebook    | [fc1fa79f81](https://linux-hardware.org/?probe=fc1fa79f81) | Oct 13, 2022 |
| Dell          | Inspiron 5759               | Notebook    | [2656af4553](https://linux-hardware.org/?probe=2656af4553) | Oct 13, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.1    | Soc         | [d170871784](https://linux-hardware.org/?probe=d170871784) | Oct 13, 2022 |
| MSI           | B360I GMAING PRO AC         | Desktop     | [2584a31610](https://linux-hardware.org/?probe=2584a31610) | Oct 12, 2022 |
| ASUSTek       | PRIME B660M-A D4            | Desktop     | [f1fcb66794](https://linux-hardware.org/?probe=f1fcb66794) | Oct 12, 2022 |
| ASRock        | B550M Phantom Gaming 4      | Desktop     | [9744660229](https://linux-hardware.org/?probe=9744660229) | Oct 12, 2022 |
| HP            | Stream Notebook PC 13       | Notebook    | [173cd34bf9](https://linux-hardware.org/?probe=173cd34bf9) | Oct 12, 2022 |
| Acer          | EM61SM/EM61PM               | Desktop     | [191540e7bc](https://linux-hardware.org/?probe=191540e7bc) | Oct 12, 2022 |
| ASUSTek       | M70Vn                       | Notebook    | [62cb9744e6](https://linux-hardware.org/?probe=62cb9744e6) | Oct 12, 2022 |
| Thomson       | N14C4WH64                   | Notebook    | [bfc16b9ded](https://linux-hardware.org/?probe=bfc16b9ded) | Oct 12, 2022 |
| eMachines     | EL1352                      | Desktop     | [ff2899db03](https://linux-hardware.org/?probe=ff2899db03) | Oct 11, 2022 |
| ASUSTek       | M32CD4-K                    | Desktop     | [0e8ec5b69d](https://linux-hardware.org/?probe=0e8ec5b69d) | Oct 11, 2022 |
| Dell          | 0T656F A01                  | Desktop     | [1680fa50c0](https://linux-hardware.org/?probe=1680fa50c0) | Oct 11, 2022 |
| ASUSTek       | N53Jg                       | Notebook    | [0b4302ed6c](https://linux-hardware.org/?probe=0b4302ed6c) | Oct 11, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [cbadb49ecd](https://linux-hardware.org/?probe=cbadb49ecd) | Oct 11, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [33c86327c4](https://linux-hardware.org/?probe=33c86327c4) | Oct 11, 2022 |
| Dell          | Latitude E6410              | Notebook    | [9ed4124073](https://linux-hardware.org/?probe=9ed4124073) | Oct 11, 2022 |
| Acer          | Aspire 7750G                | Notebook    | [e0c71d09bb](https://linux-hardware.org/?probe=e0c71d09bb) | Oct 11, 2022 |
| Lenovo        | ThinkCentre M58 7359WES     | Desktop     | [1c00ee45c1](https://linux-hardware.org/?probe=1c00ee45c1) | Oct 11, 2022 |
| eMachines     | EL1352                      | Desktop     | [805958ae53](https://linux-hardware.org/?probe=805958ae53) | Oct 11, 2022 |
| Acer          | Aspire 7750G                | Notebook    | [4eacf977db](https://linux-hardware.org/?probe=4eacf977db) | Oct 11, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [3341f329c9](https://linux-hardware.org/?probe=3341f329c9) | Oct 11, 2022 |
| ASRock        | G41C-GS R2.0                | Desktop     | [92ab2501ea](https://linux-hardware.org/?probe=92ab2501ea) | Oct 11, 2022 |
| Acer          | Aspire XC-230               | Desktop     | [d213bca85f](https://linux-hardware.org/?probe=d213bca85f) | Oct 10, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [f96c4889db](https://linux-hardware.org/?probe=f96c4889db) | Oct 10, 2022 |
| Acer          | EM61SM/EM61PM               | Desktop     | [fb2dd76511](https://linux-hardware.org/?probe=fb2dd76511) | Oct 10, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [b90b027e31](https://linux-hardware.org/?probe=b90b027e31) | Oct 10, 2022 |
| AOpen         | D1007 0BBA                  | Desktop     | [b3597a7cbc](https://linux-hardware.org/?probe=b3597a7cbc) | Oct 10, 2022 |
| Letni         | Z156                        | Notebook    | [994c588906](https://linux-hardware.org/?probe=994c588906) | Oct 10, 2022 |
| Dell          | Latitude 5400               | Notebook    | [ff8eb160c9](https://linux-hardware.org/?probe=ff8eb160c9) | Oct 10, 2022 |
| HP            | Notebook                    | Notebook    | [2fd3bd5ee0](https://linux-hardware.org/?probe=2fd3bd5ee0) | Oct 10, 2022 |
| Alienware     | m15 R7                      | Notebook    | [79aa2b2dd4](https://linux-hardware.org/?probe=79aa2b2dd4) | Oct 10, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [02170aab85](https://linux-hardware.org/?probe=02170aab85) | Oct 09, 2022 |
| Lenovo        | Dory CRB                    | Desktop     | [33ae78632a](https://linux-hardware.org/?probe=33ae78632a) | Oct 09, 2022 |
| Notebook      | NLx0MU                      | Notebook    | [900e75392f](https://linux-hardware.org/?probe=900e75392f) | Oct 09, 2022 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [ec2b212e33](https://linux-hardware.org/?probe=ec2b212e33) | Oct 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [fef2c17618](https://linux-hardware.org/?probe=fef2c17618) | Oct 09, 2022 |
| Dell          | Inspiron 16 7610            | Notebook    | [fddf8f17bd](https://linux-hardware.org/?probe=fddf8f17bd) | Oct 08, 2022 |
| Dell          | 0NV103 A00                  | All in one  | [092f9c7f2b](https://linux-hardware.org/?probe=092f9c7f2b) | Oct 08, 2022 |
| Acer          | EM61SM/EM61PM               | Desktop     | [58d2cda88f](https://linux-hardware.org/?probe=58d2cda88f) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | Notebook    | [1b90e3cfa5](https://linux-hardware.org/?probe=1b90e3cfa5) | Oct 08, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [72f51c852d](https://linux-hardware.org/?probe=72f51c852d) | Oct 08, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [1a165faedb](https://linux-hardware.org/?probe=1a165faedb) | Oct 08, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [8f1aa49dc2](https://linux-hardware.org/?probe=8f1aa49dc2) | Oct 08, 2022 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | Notebook    | [1b720b4302](https://linux-hardware.org/?probe=1b720b4302) | Oct 08, 2022 |
| Lenovo        | ThinkCentre M71z 1741A7G    | Desktop     | [805de67dc2](https://linux-hardware.org/?probe=805de67dc2) | Oct 08, 2022 |
| Dell          | Latitude E6410              | Notebook    | [0b617be9dd](https://linux-hardware.org/?probe=0b617be9dd) | Oct 08, 2022 |
| Lenovo        | ThinkCentre M71z 1741A7G    | Desktop     | [900d02c2ab](https://linux-hardware.org/?probe=900d02c2ab) | Oct 08, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [2643af430d](https://linux-hardware.org/?probe=2643af430d) | Oct 08, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [f8bf937f1e](https://linux-hardware.org/?probe=f8bf937f1e) | Oct 08, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [ac8df9496c](https://linux-hardware.org/?probe=ac8df9496c) | Oct 08, 2022 |
| HP            | 3396                        | Desktop     | [c5924b78db](https://linux-hardware.org/?probe=c5924b78db) | Oct 08, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [9f434d86be](https://linux-hardware.org/?probe=9f434d86be) | Oct 08, 2022 |
| MSI           | H81M-E34                    | Desktop     | [154cb109bf](https://linux-hardware.org/?probe=154cb109bf) | Oct 08, 2022 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [5b543dbd16](https://linux-hardware.org/?probe=5b543dbd16) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | Notebook    | [9bb8f8e33b](https://linux-hardware.org/?probe=9bb8f8e33b) | Oct 07, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [9525ea0de3](https://linux-hardware.org/?probe=9525ea0de3) | Oct 07, 2022 |
| Acer          | Swift SF314-51              | Notebook    | [cfc56878f0](https://linux-hardware.org/?probe=cfc56878f0) | Oct 07, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [69e60dfe44](https://linux-hardware.org/?probe=69e60dfe44) | Oct 07, 2022 |
| Clevo         | W2xxHSQ                     | Notebook    | [3a05b61e0b](https://linux-hardware.org/?probe=3a05b61e0b) | Oct 07, 2022 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | Notebook    | [e6eac5c882](https://linux-hardware.org/?probe=e6eac5c882) | Oct 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [8901403de4](https://linux-hardware.org/?probe=8901403de4) | Oct 07, 2022 |
| MSI           | Modern 14 A10M              | Notebook    | [ae56e506c3](https://linux-hardware.org/?probe=ae56e506c3) | Oct 06, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [c1c51b96ef](https://linux-hardware.org/?probe=c1c51b96ef) | Oct 06, 2022 |
| Dell          | Latitude 7300               | Notebook    | [3eb18574b3](https://linux-hardware.org/?probe=3eb18574b3) | Oct 06, 2022 |
| ASUSTek       | X550LA                      | Notebook    | [c0c98c2051](https://linux-hardware.org/?probe=c0c98c2051) | Oct 06, 2022 |
| Dell          | Latitude 7480               | Notebook    | [aa3f8d08a6](https://linux-hardware.org/?probe=aa3f8d08a6) | Oct 06, 2022 |
| HP            | 3398                        | Desktop     | [c70e10b68b](https://linux-hardware.org/?probe=c70e10b68b) | Oct 06, 2022 |
| Toshiba       | Satellite NB10t-A-102       | Notebook    | [0bf17a1e92](https://linux-hardware.org/?probe=0bf17a1e92) | Oct 06, 2022 |
| PC Special... | PCX0DX                      | Notebook    | [35e44699ff](https://linux-hardware.org/?probe=35e44699ff) | Oct 06, 2022 |
| Gigabyte      | H87M-D3H                    | Desktop     | [8b9d7f32d1](https://linux-hardware.org/?probe=8b9d7f32d1) | Oct 06, 2022 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [1bf20fe68c](https://linux-hardware.org/?probe=1bf20fe68c) | Oct 05, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/France/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Ubuntu 20.04      | 1695      | 20.55%  |
| Ubuntu 18.04      | 548       | 6.64%   |
| Ubuntu 22.04      | 354       | 4.29%   |
| OpenMandriva 4.2  | 353       | 4.28%   |
| Debian 11         | 295       | 3.58%   |
| OpenMandriva 4.3  | 264       | 3.2%    |
| Xubuntu 20.04     | 190       | 2.3%    |
| Linux Mint 20.3   | 169       | 2.05%   |
| Debian 10         | 134       | 1.62%   |
| Arch              | 124       | 1.5%    |
| Ubuntu 21.10      | 121       | 1.47%   |
| Arch Rolling      | 120       | 1.45%   |
| Ubuntu 20.10      | 109       | 1.32%   |
| Ubuntu 21.04      | 105       | 1.27%   |
| Linux Mint 20.2   | 105       | 1.27%   |
| Linux Mint 20.1   | 105       | 1.27%   |
| Fedora 33         | 88        | 1.07%   |
| Linux Mint 19.3   | 87        | 1.05%   |
| Ubuntu 19.10      | 85        | 1.03%   |
| Manjaro           | 84        | 1.02%   |
| Kubuntu 20.04     | 82        | 0.99%   |
| Xubuntu 18.04     | 74        | 0.9%    |
| Linux Mint 20     | 74        | 0.9%    |
| Fedora 34         | 74        | 0.9%    |
| Zorin 16          | 71        | 0.86%   |
| Ubuntu 19.04      | 71        | 0.86%   |
| KDE neon 20.04    | 71        | 0.86%   |
| Fedora 32         | 69        | 0.84%   |
| Linux Mint 21     | 68        | 0.82%   |
| Fedora 35         | 67        | 0.81%   |
| Fedora 36         | 60        | 0.73%   |
| Ubuntu MATE 20.04 | 59        | 0.72%   |
| Lubuntu 20.04     | 56        | 0.68%   |
| Pop!_OS 21.04     | 50        | 0.61%   |
| Pop!_OS 20.04     | 49        | 0.59%   |
| OpenMandriva 4.50 | 49        | 0.59%   |
| Pop!_OS 22.04     | 48        | 0.58%   |
| ROSA R11          | 47        | 0.57%   |
| Pop!_OS 20.10     | 46        | 0.56%   |
| Debian Testing    | 46        | 0.56%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 3044      | 38.86%  |
| OpenMandriva  | 702       | 8.96%   |
| Linux Mint    | 627       | 8%      |
| Debian        | 520       | 6.64%   |
| Fedora        | 371       | 4.74%   |
| Xubuntu       | 338       | 4.31%   |
| Arch          | 240       | 3.06%   |
| Manjaro       | 219       | 2.8%    |
| Pop!_OS       | 207       | 2.64%   |
| Kubuntu       | 186       | 2.37%   |
| ROSA          | 171       | 2.18%   |
| Zorin         | 115       | 1.47%   |
| Ubuntu MATE   | 108       | 1.38%   |
| Lubuntu       | 92        | 1.17%   |
| KDE neon      | 83        | 1.06%   |
| Ubuntu Unity  | 64        | 0.82%   |
| openSUSE      | 61        | 0.78%   |
| Gentoo        | 52        | 0.66%   |
| Kali          | 50        | 0.64%   |
| Endless       | 49        | 0.63%   |
| ArcoLinux     | 44        | 0.56%   |
| Elementary    | 41        | 0.52%   |
| Ubuntu Budgie | 39        | 0.5%    |
| LMDE          | 32        | 0.41%   |
| EndeavourOS   | 32        | 0.41%   |
| BlackPanther  | 32        | 0.41%   |
| CentOS        | 24        | 0.31%   |
| Ubuntu Studio | 22        | 0.28%   |
| SteamOS       | 20        | 0.26%   |
| Parrot        | 19        | 0.24%   |
| Mageia        | 19        | 0.24%   |
| Clear Linux   | 19        | 0.24%   |
| MX            | 12        | 0.15%   |
| Kaisen        | 11        | 0.14%   |
| Artix         | 10        | 0.13%   |
| NixOS         | 9         | 0.11%   |
| Devuan        | 9         | 0.11%   |
| Manjaro-ARM   | 8         | 0.1%    |
| LinuxFX       | 8         | 0.1%    |
| Raspbian      | 7         | 0.09%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 336       | 3.72%   |
| 5.16.7-desktop-1omv4003  | 254       | 2.81%   |
| 5.4.0-42-generic         | 128       | 1.42%   |
| 5.4.0-58-generic         | 99        | 1.1%    |
| 5.15.0-52-generic        | 93        | 1.03%   |
| 5.15.0-56-generic        | 92        | 1.02%   |
| 5.4.0-52-generic         | 81        | 0.9%    |
| 5.11.0-38-generic        | 76        | 0.84%   |
| 5.11.0-27-generic        | 76        | 0.84%   |
| 5.15.0-48-generic        | 74        | 0.82%   |
| 5.4.0-26-generic         | 72        | 0.8%    |
| 5.4.0-48-generic         | 69        | 0.76%   |
| 5.8.0-43-generic         | 68        | 0.75%   |
| 5.15.0-46-generic        | 66        | 0.73%   |
| 5.11.0-37-generic        | 66        | 0.73%   |
| 5.4.0-65-generic         | 65        | 0.72%   |
| 5.8.0-50-generic         | 63        | 0.7%    |
| 5.11.0-40-generic        | 57        | 0.63%   |
| 5.4.0-29-generic         | 55        | 0.61%   |
| 5.13.0-28-generic        | 55        | 0.61%   |
| 5.8.0-44-generic         | 54        | 0.6%    |
| 5.4.0-91-generic         | 54        | 0.6%    |
| 5.4.0-54-generic         | 54        | 0.6%    |
| 5.15.0-47-generic        | 54        | 0.6%    |
| 5.8.0-48-generic         | 53        | 0.59%   |
| 5.4.0-37-generic         | 53        | 0.59%   |
| 5.13.0-39-generic        | 52        | 0.58%   |
| 5.11.0-43-generic        | 51        | 0.57%   |
| 5.15.0-43-generic        | 50        | 0.55%   |
| 5.4.0-81-generic         | 48        | 0.53%   |
| 5.11.0-34-generic        | 48        | 0.53%   |
| 5.8.0-59-generic         | 46        | 0.51%   |
| 5.15.0-53-generic        | 46        | 0.51%   |
| 5.15.0-41-generic        | 46        | 0.51%   |
| 5.4.0-31-generic         | 45        | 0.5%    |
| 5.13.0-40-generic        | 45        | 0.5%    |
| 5.8.0-53-generic         | 42        | 0.47%   |
| 5.13.0-27-generic        | 42        | 0.47%   |
| 5.4.0-73-generic         | 41        | 0.45%   |
| 5.10.0-8-amd64           | 41        | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 1725      | 20.34%  |
| 5.15.0  | 683       | 8.05%   |
| 5.11.0  | 627       | 7.39%   |
| 5.8.0   | 610       | 7.19%   |
| 5.13.0  | 511       | 6.03%   |
| 4.15.0  | 429       | 5.06%   |
| 5.10.14 | 339       | 4%      |
| 5.10.0  | 326       | 3.84%   |
| 5.3.0   | 288       | 3.4%    |
| 5.16.7  | 256       | 3.02%   |
| 5.0.0   | 164       | 1.93%   |
| 4.18.0  | 137       | 1.62%   |
| 4.19.0  | 128       | 1.51%   |
| 5.19.0  | 68        | 0.8%    |
| 5.14.0  | 37        | 0.44%   |
| 4.9.20  | 35        | 0.41%   |
| 5.18.12 | 31        | 0.37%   |
| 5.18.0  | 31        | 0.37%   |
| 5.11.12 | 31        | 0.37%   |
| 5.17.5  | 29        | 0.34%   |
| 4.18.16 | 29        | 0.34%   |
| 5.16.0  | 28        | 0.33%   |
| 6.0.0   | 27        | 0.32%   |
| 4.4.0   | 26        | 0.31%   |
| 5.9.0   | 25        | 0.29%   |
| 5.12.4  | 23        | 0.27%   |
| 4.9.60  | 23        | 0.27%   |
| 5.19.12 | 22        | 0.26%   |
| 5.13.19 | 19        | 0.22%   |
| 5.9.16  | 18        | 0.21%   |
| 5.9.11  | 18        | 0.21%   |
| 5.7.0   | 18        | 0.21%   |
| 5.6.0   | 18        | 0.21%   |
| 5.17.1  | 17        | 0.2%    |
| 4.9.0   | 17        | 0.2%    |
| 5.13.12 | 16        | 0.19%   |
| 6.0.9   | 15        | 0.18%   |
| 5.17.0  | 15        | 0.18%   |
| 5.14.14 | 15        | 0.18%   |
| 5.4.32  | 14        | 0.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.4      | 1819      | 21.72%  |
| 5.15     | 866       | 10.34%  |
| 5.10     | 805       | 9.61%   |
| 5.11     | 719       | 8.59%   |
| 5.8      | 699       | 8.35%   |
| 5.13     | 594       | 7.09%   |
| 4.15     | 430       | 5.13%   |
| 5.16     | 370       | 4.42%   |
| 5.3      | 328       | 3.92%   |
| 5.0      | 177       | 2.11%   |
| 4.18     | 169       | 2.02%   |
| 5.19     | 156       | 1.86%   |
| 4.19     | 145       | 1.73%   |
| 5.18     | 127       | 1.52%   |
| 5.14     | 120       | 1.43%   |
| 5.9      | 119       | 1.42%   |
| 4.9      | 119       | 1.42%   |
| 5.17     | 102       | 1.22%   |
| 6.0      | 100       | 1.19%   |
| 5.6      | 82        | 0.98%   |
| 5.7      | 73        | 0.87%   |
| 5.12     | 70        | 0.84%   |
| 5.5      | 39        | 0.47%   |
| 4.4      | 30        | 0.36%   |
| 4.1      | 24        | 0.29%   |
| 5.2      | 13        | 0.16%   |
| 3.10     | 13        | 0.16%   |
| 4.14     | 12        | 0.14%   |
| 6.1      | 10        | 0.12%   |
| 4.12     | 9         | 0.11%   |
| 4.20     | 7         | 0.08%   |
| 4.13     | 7         | 0.08%   |
| 5.1      | 6         | 0.07%   |
| 4.10     | 4         | 0.05%   |
| 4.8      | 3         | 0.04%   |
| 4.17     | 2         | 0.02%   |
| 3.4      | 2         | 0.02%   |
| 5        | 1         | 0.01%   |
| 4.9.273~ | 1         | 0.01%   |
| 3.14     | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 7353      | 96.48%  |
| i686    | 209       | 2.74%   |
| aarch64 | 39        | 0.51%   |
| armv7l  | 16        | 0.21%   |
| armv8l  | 2         | 0.03%   |
| armv6l  | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| GNOME             | 3527      | 44.58%  |
| KDE5              | 1301      | 16.44%  |
| Unknown           | 848       | 10.72%  |
| XFCE              | 715       | 9.04%   |
| X-Cinnamon        | 442       | 5.59%   |
| MATE              | 291       | 3.68%   |
| Cinnamon          | 118       | 1.49%   |
| KDE               | 115       | 1.45%   |
| KDE4              | 114       | 1.44%   |
| LXQt              | 97        | 1.23%   |
| Unity             | 65        | 0.82%   |
| i3                | 65        | 0.82%   |
| Budgie            | 46        | 0.58%   |
| Pantheon          | 42        | 0.53%   |
| LXDE              | 37        | 0.47%   |
| GNOME Flashback   | 23        | 0.29%   |
| GNOME Classic     | 13        | 0.16%   |
| Deepin            | 11        | 0.14%   |
| sway              | 5         | 0.06%   |
| qtile             | 5         | 0.06%   |
| bspwm             | 5         | 0.06%   |
| awesome           | 4         | 0.05%   |
| Trinity           | 3         | 0.04%   |
| i3-with-shmlog    | 3         | 0.04%   |
| Openbox           | 2         | 0.03%   |
| lightdm-xsession  | 2         | 0.03%   |
| ICEWM             | 2         | 0.03%   |
| Enlightenment     | 2         | 0.03%   |
| Yaru:ubuntu:GNOME | 1         | 0.01%   |
| xmonad            | 1         | 0.01%   |
| wmaker-common     | 1         | 0.01%   |
| Lubuntu           | 1         | 0.01%   |
| LeftWM            | 1         | 0.01%   |
| GNUstep           | 1         | 0.01%   |
| fluxbox           | 1         | 0.01%   |
| dwm-sc            | 1         | 0.01%   |
| DWM               | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 6222      | 79.47%  |
| Wayland | 972       | 12.42%  |
| Unknown | 418       | 5.34%   |
| Tty     | 217       | 2.77%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3188      | 40.27%  |
| GDM     | 1420      | 17.94%  |
| SDDM    | 1297      | 16.38%  |
| LightDM | 834       | 10.54%  |
| GDM3    | 703       | 8.88%   |
| TDM     | 334       | 4.22%   |
| KDM     | 111       | 1.4%    |
| XDM     | 11        | 0.14%   |
| SLiM    | 6         | 0.08%   |
| Ly      | 6         | 0.08%   |
| NODM    | 2         | 0.03%   |
| LXDM    | 2         | 0.03%   |
| WDM     | 1         | 0.01%   |
| MDM     | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| fr_FR       | 5353      | 69.04%  |
| en_US       | 1257      | 16.21%  |
| Unknown     | 742       | 9.57%   |
| en_GB       | 125       | 1.61%   |
| C           | 83        | 1.07%   |
| de_DE       | 21        | 0.27%   |
| ru_RU       | 19        | 0.25%   |
| it_IT       | 14        | 0.18%   |
| es_ES       | 14        | 0.18%   |
| nl_NL       | 12        | 0.15%   |
| pl_PL       | 10        | 0.13%   |
| fr_CH       | 10        | 0.13%   |
| fr_CA       | 9         | 0.12%   |
| pt_PT       | 7         | 0.09%   |
| fr_BE       | 7         | 0.09%   |
| POSIX       | 6         | 0.08%   |
| en_IE       | 4         | 0.05%   |
| en_AU       | 4         | 0.05%   |
| C.UTF8      | 4         | 0.05%   |
| sv_SE       | 3         | 0.04%   |
| ru_UA       | 3         | 0.04%   |
| pt_BR       | 3         | 0.04%   |
| fr_FR.UTF8  | 3         | 0.04%   |
| en_IN       | 3         | 0.04%   |
| hu_HU       | 2         | 0.03%   |
| fr_LU       | 2         | 0.03%   |
| en_DK       | 2         | 0.03%   |
| en_CA       | 2         | 0.03%   |
| en_AG       | 2         | 0.03%   |
| cs_CZ       | 2         | 0.03%   |
| tr_TR       | 1         | 0.01%   |
| sr_RS@latin | 1         | 0.01%   |
| sr_RS       | 1         | 0.01%   |
| sk_SK       | 1         | 0.01%   |
| ro_RO       | 1         | 0.01%   |
| nb_NO       | 1         | 0.01%   |
| fr_FR.utf-8 | 1         | 0.01%   |
| fi_FI       | 1         | 0.01%   |
| eu_ES       | 1         | 0.01%   |
| es_VE       | 1         | 0.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 3948      | 50.84%  |
| BIOS | 3817      | 49.16%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 6230      | 80.35%  |
| Overlay  | 692       | 8.92%   |
| Btrfs    | 441       | 5.69%   |
| Unknown  | 221       | 2.85%   |
| Xfs      | 78        | 1.01%   |
| Zfs      | 45        | 0.58%   |
| Ext2     | 15        | 0.19%   |
| F2fs     | 12        | 0.15%   |
| Ext3     | 12        | 0.15%   |
| Reiserfs | 3         | 0.04%   |
| Tmpfs    | 2         | 0.03%   |
| Rootfs   | 1         | 0.01%   |
| Jfs      | 1         | 0.01%   |
| Aufs     | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3424      | 43.95%  |
| GPT     | 3152      | 40.46%  |
| MBR     | 1215      | 15.59%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 6303      | 81.29%  |
| Yes       | 1451      | 18.71%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 5203      | 67.17%  |
| Yes       | 2543      | 32.83%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 1546      | 20.3%   |
| Dell                    | 1101      | 14.45%  |
| Hewlett-Packard         | 977       | 12.83%  |
| Lenovo                  | 837       | 10.99%  |
| MSI                     | 646       | 8.48%   |
| Gigabyte Technology     | 439       | 5.76%   |
| Acer                    | 389       | 5.11%   |
| ASRock                  | 188       | 2.47%   |
| Toshiba                 | 139       | 1.82%   |
| Apple                   | 135       | 1.77%   |
| Intel                   | 112       | 1.47%   |
| Packard Bell            | 87        | 1.14%   |
| Notebook                | 79        | 1.04%   |
| HUAWEI                  | 66        | 0.87%   |
| Samsung Electronics     | 62        | 0.81%   |
| Unknown                 | 61        | 0.8%    |
| Sony                    | 52        | 0.68%   |
| Foxconn                 | 44        | 0.58%   |
| Pegatron                | 37        | 0.49%   |
| Fujitsu                 | 34        | 0.45%   |
| eMachines               | 34        | 0.45%   |
| Raspberry Pi Foundation | 32        | 0.42%   |
| Medion                  | 29        | 0.38%   |
| TUXEDO                  | 24        | 0.32%   |
| Supermicro              | 23        | 0.3%    |
| Timi                    | 21        | 0.28%   |
| Microsoft               | 20        | 0.26%   |
| Clevo                   | 20        | 0.26%   |
| Alienware               | 20        | 0.26%   |
| Fujitsu Siemens         | 19        | 0.25%   |
| Thomson                 | 18        | 0.24%   |
| UNOWHY                  | 17        | 0.22%   |
| Valve                   | 16        | 0.21%   |
| AZW                     | 15        | 0.2%    |
| Shuttle                 | 14        | 0.18%   |
| PC Specialist           | 13        | 0.17%   |
| ECS                     | 13        | 0.17%   |
| Chuwi                   | 13        | 0.17%   |
| BESSTAR Tech            | 13        | 0.17%   |
| Razer                   | 12        | 0.16%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| ASUS All Series          | 109       | 1.43%   |
| Unknown                  | 79        | 1.04%   |
| HP Notebook              | 32        | 0.42%   |
| Gigabyte B450M DS3H      | 29        | 0.38%   |
| HP Pavilion dv6          | 25        | 0.33%   |
| HP Pavilion dv7          | 22        | 0.29%   |
| HP Pavilion 17           | 21        | 0.28%   |
| Dell OptiPlex 7010       | 18        | 0.24%   |
| Dell OptiPlex 390        | 18        | 0.24%   |
| HP Pavilion g7           | 17        | 0.22%   |
| Dell XPS 13 9310         | 17        | 0.22%   |
| Valve Jupiter            | 16        | 0.21%   |
| Dell OptiPlex 9020       | 16        | 0.21%   |
| MSI MS-7C91              | 15        | 0.2%    |
| ASUS PRIME A320M-K       | 15        | 0.2%    |
| HP Pavilion Notebook     | 14        | 0.18%   |
| Dell XPS 13 9380         | 14        | 0.18%   |
| Dell XPS 13 7390         | 14        | 0.18%   |
| ASUS S551LN              | 14        | 0.18%   |
| MSI MS-7C02              | 13        | 0.17%   |
| HP EliteBook 840 G2      | 13        | 0.17%   |
| Gigabyte 970A-DS3P       | 13        | 0.17%   |
| Dell XPS 15 7590         | 13        | 0.17%   |
| MSI MS-7C37              | 12        | 0.16%   |
| MSI MS-7817              | 12        | 0.16%   |
| MSI MS-7816              | 12        | 0.16%   |
| MSI MS-7758              | 12        | 0.16%   |
| MSI MS-7693              | 12        | 0.16%   |
| Dell XPS 15 9570         | 12        | 0.16%   |
| Dell OptiPlex 3020       | 12        | 0.16%   |
| Dell Latitude E6420      | 12        | 0.16%   |
| HUAWEI HVY-WXX9          | 11        | 0.14%   |
| HP Pavilion g6           | 11        | 0.14%   |
| HP Pavilion 15           | 11        | 0.14%   |
| HP EliteBook 840 G3      | 11        | 0.14%   |
| HP Compaq Elite 8300 SFF | 11        | 0.14%   |
| Dell Latitude 5420       | 11        | 0.14%   |
| MSI MS-7B79              | 10        | 0.13%   |
| MSI MS-7A38              | 10        | 0.13%   |
| Lenovo G50-30 80G0       | 10        | 0.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 412       | 5.41%   |
| Dell Latitude         | 318       | 4.17%   |
| Acer Aspire           | 257       | 3.37%   |
| HP Pavilion           | 216       | 2.84%   |
| Dell Precision        | 189       | 2.48%   |
| Dell OptiPlex         | 161       | 2.11%   |
| Dell XPS              | 159       | 2.09%   |
| Dell Inspiron         | 146       | 1.92%   |
| HP EliteBook          | 139       | 1.82%   |
| Lenovo IdeaPad        | 128       | 1.68%   |
| ASUS PRIME            | 124       | 1.63%   |
| Toshiba Satellite     | 118       | 1.55%   |
| HP ProBook            | 116       | 1.52%   |
| ASUS All              | 109       | 1.43%   |
| HP Compaq             | 104       | 1.37%   |
| ASUS ROG              | 101       | 1.33%   |
| ASUS VivoBook         | 100       | 1.31%   |
| Lenovo ThinkCentre    | 81        | 1.06%   |
| Unknown               | 79        | 1.04%   |
| ASUS TUF              | 71        | 0.93%   |
| HP Laptop             | 61        | 0.8%    |
| ASUS ZenBook          | 49        | 0.64%   |
| Packard Bell EasyNote | 46        | 0.6%    |
| Dell Vostro           | 43        | 0.56%   |
| Acer Swift            | 41        | 0.54%   |
| Lenovo Legion         | 34        | 0.45%   |
| Gigabyte B450M        | 34        | 0.45%   |
| HP ENVY               | 33        | 0.43%   |
| RPi Raspberry         | 32        | 0.42%   |
| HP Notebook           | 32        | 0.42%   |
| HP ZBook              | 29        | 0.38%   |
| Lenovo Yoga           | 28        | 0.37%   |
| Packard Bell IMEDIA   | 24        | 0.32%   |
| ASUS P8Z77-V          | 24        | 0.32%   |
| Dell PowerEdge        | 23        | 0.3%    |
| HP ProDesk            | 22        | 0.29%   |
| HP EliteDesk          | 22        | 0.29%   |
| Acer Nitro            | 21        | 0.28%   |
| Microsoft Surface     | 20        | 0.26%   |
| HP OMEN               | 20        | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 736       | 9.66%   |
| 2019    | 698       | 9.16%   |
| 2020    | 696       | 9.14%   |
| 2012    | 608       | 7.98%   |
| 2013    | 579       | 7.6%    |
| 2011    | 506       | 6.64%   |
| 2017    | 460       | 6.04%   |
| 2015    | 460       | 6.04%   |
| 2014    | 441       | 5.79%   |
| 2021    | 433       | 5.68%   |
| 2010    | 422       | 5.54%   |
| 2016    | 377       | 4.95%   |
| 2009    | 349       | 4.58%   |
| 2008    | 344       | 4.52%   |
| 2007    | 183       | 2.4%    |
| 2022    | 121       | 1.59%   |
| 2006    | 90        | 1.18%   |
| Unknown | 48        | 0.63%   |
| 2005    | 45        | 0.59%   |
| 2004    | 12        | 0.16%   |
| 2003    | 6         | 0.08%   |
| 2002    | 2         | 0.03%   |
| 2001    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 4211      | 55.28%  |
| Desktop        | 2934      | 38.52%  |
| Convertible    | 117       | 1.54%   |
| Mini pc        | 107       | 1.4%    |
| All in one     | 86        | 1.13%   |
| Server         | 61        | 0.8%    |
| Tablet         | 47        | 0.62%   |
| System on chip | 45        | 0.59%   |
| Phone          | 8         | 0.11%   |
| Firewall       | 1         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 7023      | 91.59%  |
| Enabled  | 645       | 8.41%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 7602      | 99.79%  |
| Yes  | 16        | 0.21%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1700      | 22.04%  |
| 3.01-4.0        | 1697      | 22%     |
| 16.01-24.0      | 1582      | 20.51%  |
| 8.01-16.0       | 1312      | 17.01%  |
| 32.01-64.0      | 620       | 8.04%   |
| 1.01-2.0        | 323       | 4.19%   |
| 64.01-256.0     | 161       | 2.09%   |
| 2.01-3.0        | 131       | 1.7%    |
| 24.01-32.0      | 105       | 1.36%   |
| 0.51-1.0        | 59        | 0.77%   |
| 0.01-0.5        | 10        | 0.13%   |
| More than 256.0 | 7         | 0.09%   |
| Unknown         | 5         | 0.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 3009      | 36.11%  |
| 2.01-3.0    | 2022      | 24.26%  |
| 4.01-8.0    | 1153      | 13.83%  |
| 3.01-4.0    | 1038      | 12.46%  |
| 0.51-1.0    | 585       | 7.02%   |
| 8.01-16.0   | 330       | 3.96%   |
| 0.01-0.5    | 114       | 1.37%   |
| 16.01-24.0  | 43        | 0.52%   |
| 24.01-32.0  | 16        | 0.19%   |
| 32.01-64.0  | 14        | 0.17%   |
| Unknown     | 9         | 0.11%   |
| 64.01-256.0 | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 4583      | 58.71%  |
| 2       | 1957      | 25.07%  |
| 3       | 638       | 8.17%   |
| 4       | 300       | 3.84%   |
| 5       | 140       | 1.79%   |
| 0       | 68        | 0.87%   |
| 6       | 65        | 0.83%   |
| 7       | 31        | 0.4%    |
| 8       | 11        | 0.14%   |
| 9       | 5         | 0.06%   |
| Unknown | 4         | 0.05%   |
| 22      | 1         | 0.01%   |
| 14      | 1         | 0.01%   |
| 11      | 1         | 0.01%   |
| 10      | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 4241      | 55.2%   |
| Yes       | 3442      | 44.8%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 6691      | 87.64%  |
| No        | 944       | 12.36%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5620      | 73.23%  |
| No        | 2054      | 26.77%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4265      | 55.33%  |
| No        | 3443      | 44.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| France  | 7617      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Paris            | 1198      | 14.67%  |
| Lyon             | 167       | 2.04%   |
| Marseille        | 136       | 1.66%   |
| Toulouse         | 117       | 1.43%   |
| Nantes           | 100       | 1.22%   |
| Strasbourg       | 87        | 1.07%   |
| Montpellier      | 76        | 0.93%   |
| Rennes           | 65        | 0.8%    |
| Lille            | 64        | 0.78%   |
| Bordeaux         | 60        | 0.73%   |
| Roubaix          | 58        | 0.71%   |
| Grenoble         | 57        | 0.7%    |
| Clichy-sous-Bois | 57        | 0.7%    |
| Nice             | 54        | 0.66%   |
| Brest            | 42        | 0.51%   |
| Tours            | 37        | 0.45%   |
| La Rochelle      | 35        | 0.43%   |
| Toulon           | 33        | 0.4%    |
| Villeurbanne     | 32        | 0.39%   |
| Rouen            | 29        | 0.36%   |
| Poitiers         | 29        | 0.36%   |
| Caen             | 28        | 0.34%   |
| Nîmes           | 26        | 0.32%   |
| Metz             | 26        | 0.32%   |
| Aix-en-Provence  | 25        | 0.31%   |
| Pau              | 24        | 0.29%   |
| Clermont-Ferrand | 24        | 0.29%   |
| Cergy            | 24        | 0.29%   |
| Besançon        | 24        | 0.29%   |
| Argenteuil       | 24        | 0.29%   |
| Amiens           | 24        | 0.29%   |
| Nancy            | 23        | 0.28%   |
| Limoges          | 22        | 0.27%   |
| Versailles       | 21        | 0.26%   |
| Perpignan        | 21        | 0.26%   |
| Dijon            | 21        | 0.26%   |
| Saint-Denis      | 20        | 0.24%   |
| Orléans         | 20        | 0.24%   |
| Aubervilliers    | 20        | 0.24%   |
| Angers           | 20        | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 1787      | 2688   | 16.03%  |
| Samsung Electronics       | 1712      | 2617   | 15.36%  |
| WDC                       | 1635      | 2465   | 14.67%  |
| Crucial                   | 772       | 1060   | 6.93%   |
| Toshiba                   | 740       | 963    | 6.64%   |
| SanDisk                   | 545       | 672    | 4.89%   |
| Kingston                  | 540       | 655    | 4.84%   |
| Unknown                   | 411       | 552    | 3.69%   |
| Hitachi                   | 362       | 447    | 3.25%   |
| SK hynix                  | 314       | 377    | 2.82%   |
| HGST                      | 296       | 388    | 2.66%   |
| Intel                     | 239       | 296    | 2.14%   |
| Micron Technology         | 180       | 215    | 1.61%   |
| PNY                       | 133       | 157    | 1.19%   |
| Maxtor                    | 93        | 120    | 0.83%   |
| LDLC                      | 83        | 126    | 0.74%   |
| KIOXIA                    | 80        | 91     | 0.72%   |
| Phison                    | 76        | 94     | 0.68%   |
| Transcend                 | 67        | 78     | 0.6%    |
| Corsair                   | 65        | 75     | 0.58%   |
| China                     | 64        | 79     | 0.57%   |
| Apple                     | 57        | 74     | 0.51%   |
| Micron/Crucial Technology | 51        | 66     | 0.46%   |
| OCZ                       | 48        | 65     | 0.43%   |
| Fujitsu                   | 45        | 62     | 0.4%    |
| LITEON                    | 41        | 46     | 0.37%   |
| SPCC                      | 37        | 48     | 0.33%   |
| A-DATA Technology         | 37        | 45     | 0.33%   |
| JMicron Technology        | 30        | 36     | 0.27%   |
| Unknown                   | 30        | 34     | 0.27%   |
| LITEONIT                  | 29        | 29     | 0.26%   |
| Silicon Motion            | 23        | 33     | 0.21%   |
| Gigabyte Technology       | 18        | 22     | 0.16%   |
| EMTEC                     | 18        | 21     | 0.16%   |
| ASMT                      | 18        | 21     | 0.16%   |
| Intenso                   | 16        | 18     | 0.14%   |
| Patriot                   | 15        | 21     | 0.13%   |
| KingSpec                  | 14        | 17     | 0.13%   |
| Hewlett-Packard           | 14        | 21     | 0.13%   |
| Phison Electronics        | 12        | 13     | 0.11%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB          | 126       | 1.03%   |
| Crucial CT240BX500SSD1 240GB       | 121       | 0.99%   |
| Crucial CT500MX500SSD1 500GB       | 115       | 0.94%   |
| HGST HTS721010A9E630 1TB           | 100       | 0.82%   |
| Seagate ST1000LM035-1RK172 1TB     | 98        | 0.8%    |
| Seagate ST1000LM024 HN-M101MBB 1TB | 90        | 0.73%   |
| Toshiba MQ01ABD100 1TB             | 88        | 0.72%   |
| Samsung SSD 850 EVO 250GB          | 87        | 0.71%   |
| Kingston SA400S37240G 240GB SSD    | 84        | 0.69%   |
| Seagate ST500DM002-1BD142 500GB    | 80        | 0.65%   |
| Seagate ST1000DM010-2EP102 1TB     | 78        | 0.64%   |
| Samsung SSD 850 EVO 500GB          | 75        | 0.61%   |
| Seagate ST2000DM008-2FR102 2TB     | 71        | 0.58%   |
| Crucial CT1000MX500SSD1 1TB        | 66        | 0.54%   |
| Unknown MMC Card  32GB             | 65        | 0.53%   |
| Samsung SSD 860 EVO 1TB            | 65        | 0.53%   |
| Seagate ST2000DM001-1ER164 2TB     | 59        | 0.48%   |
| Crucial CT480BX500SSD1 480GB       | 57        | 0.47%   |
| Seagate ST1000DM003-1ER162 1TB     | 56        | 0.46%   |
| Samsung SSD 860 EVO 250GB          | 56        | 0.46%   |
| Samsung NVMe SSD Drive 512GB       | 55        | 0.45%   |
| Kingston SA400S37120G 120GB SSD    | 54        | 0.44%   |
| Toshiba MQ04ABF100 1TB             | 53        | 0.43%   |
| Seagate ST1000DM003-1CH162 1TB     | 53        | 0.43%   |
| Unknown MMC Card  64GB             | 52        | 0.42%   |
| HGST HTS541010A9E680 1TB           | 51        | 0.42%   |
| Unknown SD/MMC/MS PRO 64GB         | 49        | 0.4%    |
| Toshiba DT01ACA100 1TB             | 49        | 0.4%    |
| Seagate ST2000DM001-1CH164 2TB     | 49        | 0.4%    |
| Samsung SSD 870 QVO 1TB            | 49        | 0.4%    |
| Samsung NVMe SSD Drive 500GB       | 47        | 0.38%   |
| Samsung SSD 860 QVO 1TB            | 46        | 0.38%   |
| Kingston SV300S37A120G 120GB SSD   | 46        | 0.38%   |
| Kingston SA400S37480G 480GB SSD    | 44        | 0.36%   |
| SanDisk NVMe SSD Drive 512GB       | 43        | 0.35%   |
| PNY CS900 240GB SSD                | 42        | 0.34%   |
| PNY CS900 120GB SSD                | 42        | 0.34%   |
| Seagate ST2000DM006-2DM164 2TB     | 39        | 0.32%   |
| Crucial CT120BX500SSD1 120GB       | 39        | 0.32%   |
| WDC WD10EZEX-08WN4A0 1TB           | 38        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1763      | 2629   | 36.28%  |
| WDC                 | 1364      | 2099   | 28.07%  |
| Toshiba             | 566       | 719    | 11.65%  |
| Hitachi             | 362       | 447    | 7.45%   |
| HGST                | 296       | 388    | 6.09%   |
| Samsung Electronics | 226       | 336    | 4.65%   |
| Maxtor              | 93        | 120    | 1.91%   |
| Unknown             | 55        | 64     | 1.13%   |
| Fujitsu             | 44        | 61     | 0.91%   |
| Apple               | 17        | 19     | 0.35%   |
| ASMT                | 13        | 15     | 0.27%   |
| Hewlett-Packard     | 7         | 13     | 0.14%   |
| Magnetic Data       | 6         | 6      | 0.12%   |
| Inateck             | 5         | 5      | 0.1%    |
| IBM/Hitachi         | 5         | 6      | 0.1%    |
| ASMedia             | 4         | 4      | 0.08%   |
| LaCie               | 3         | 3      | 0.06%   |
| JMicron Technology  | 3         | 4      | 0.06%   |
| Intenso             | 3         | 4      | 0.06%   |
| HGST HTS            | 3         | 3      | 0.06%   |
| ASMT109x            | 3         | 4      | 0.06%   |
| USB3.0              | 2         | 2      | 0.04%   |
| USB                 | 2         | 3      | 0.04%   |
| RSH-319             | 2         | 3      | 0.04%   |
| PHD 3.0             | 2         | 2      | 0.04%   |
| Storeva             | 1         | 1      | 0.02%   |
| SILICONMOTION       | 1         | 1      | 0.02%   |
| QEMU                | 1         | 1      | 0.02%   |
| MDT                 | 1         | 1      | 0.02%   |
| MARVELL             | 1         | 1      | 0.02%   |
| ICY BOX             | 1         | 1      | 0.02%   |
| H/W                 | 1         | 1      | 0.02%   |
| Generic-            | 1         | 1      | 0.02%   |
| DELLBOSS            | 1         | 1      | 0.02%   |
| APPLE HD            | 1         | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 946       | 1347   | 25.25%  |
| Crucial             | 698       | 957    | 18.63%  |
| Kingston            | 449       | 545    | 11.98%  |
| SanDisk             | 381       | 469    | 10.17%  |
| PNY                 | 122       | 142    | 3.26%   |
| WDC                 | 113       | 135    | 3.02%   |
| Intel               | 102       | 119    | 2.72%   |
| Micron Technology   | 79        | 105    | 2.11%   |
| SK hynix            | 78        | 97     | 2.08%   |
| Transcend           | 63        | 74     | 1.68%   |
| LDLC                | 61        | 82     | 1.63%   |
| China               | 61        | 76     | 1.63%   |
| OCZ                 | 47        | 61     | 1.25%   |
| Toshiba             | 45        | 60     | 1.2%    |
| Corsair             | 36        | 41     | 0.96%   |
| Apple               | 36        | 48     | 0.96%   |
| LITEON              | 35        | 38     | 0.93%   |
| SPCC                | 34        | 45     | 0.91%   |
| A-DATA Technology   | 30        | 38     | 0.8%    |
| LITEONIT            | 29        | 29     | 0.77%   |
| JMicron Technology  | 19        | 23     | 0.51%   |
| Unknown             | 19        | 22     | 0.51%   |
| Emtec               | 16        | 18     | 0.43%   |
| Patriot             | 14        | 19     | 0.37%   |
| KingSpec            | 14        | 17     | 0.37%   |
| Intenso             | 12        | 13     | 0.32%   |
| Plextor             | 10        | 11     | 0.27%   |
| Dogfish             | 10        | 16     | 0.27%   |
| TEXTORM             | 9         | 10     | 0.24%   |
| Netac               | 9         | 10     | 0.24%   |
| BHT                 | 9         | 12     | 0.24%   |
| KingDian            | 8         | 11     | 0.21%   |
| Apacer              | 8         | 8      | 0.21%   |
| Verbatim            | 7         | 7      | 0.19%   |
| BAITITON            | 7         | 7      | 0.19%   |
| Unknown             | 6         | 10     | 0.16%   |
| TCSUNBOW            | 6         | 9      | 0.16%   |
| Seagate             | 6         | 6      | 0.16%   |
| Gigabyte Technology | 6         | 9      | 0.16%   |
| TO Exter            | 5         | 5      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 4070      | 6969   | 40.9%   |
| SSD     | 3270      | 4869   | 32.86%  |
| NVMe    | 2094      | 2827   | 21.04%  |
| MMC     | 361       | 491    | 3.63%   |
| Unknown | 157       | 229    | 1.58%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 5887      | 11512  | 67.43%  |
| NVMe | 2084      | 2804   | 23.87%  |
| SAS  | 398       | 578    | 4.56%   |
| MMC  | 361       | 491    | 4.14%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 4363      | 6894   | 56.69%  |
| 0.51-1.0   | 2313      | 3315   | 30.05%  |
| 1.01-2.0   | 593       | 957    | 7.71%   |
| 3.01-4.0   | 208       | 324    | 2.7%    |
| 2.01-3.0   | 122       | 187    | 1.59%   |
| 4.01-10.0  | 81        | 134    | 1.05%   |
| 10.01-20.0 | 16        | 27     | 0.21%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 2028      | 25.33%  |
| 251-500        | 1783      | 22.27%  |
| 501-1000       | 1286      | 16.06%  |
| 1001-2000      | 639       | 7.98%   |
| 1-20           | 634       | 7.92%   |
| 51-100         | 450       | 5.62%   |
| More than 3000 | 365       | 4.56%   |
| 21-50          | 306       | 3.82%   |
| Unknown        | 272       | 3.4%    |
| 2001-3000      | 244       | 3.05%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 3012      | 36.4%   |
| 21-50          | 1280      | 15.47%  |
| 101-250        | 1052      | 12.71%  |
| 51-100         | 966       | 11.67%  |
| 251-500        | 687       | 8.3%    |
| 501-1000       | 503       | 6.08%   |
| 1001-2000      | 282       | 3.41%   |
| Unknown        | 272       | 3.29%   |
| More than 3000 | 123       | 1.49%   |
| 2001-3000      | 95        | 1.15%   |
| 0              | 3         | 0.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| HGST HTS721010A9E630 1TB              | 17        | 21     | 1.9%    |
| HGST HTS541010A9E680 1TB              | 12        | 12     | 1.34%   |
| Toshiba MQ01ABD100 1TB                | 10        | 12     | 1.11%   |
| Seagate ST500LM021-1KJ152 500GB       | 10        | 12     | 1.11%   |
| Seagate ST500DM002-1BD142 500GB       | 10        | 11     | 1.11%   |
| Seagate ST9500325AS 500GB             | 9         | 10     | 1%      |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 8         | 8      | 0.89%   |
| WDC WD10JPVX-22JC3T0 1TB              | 7         | 7      | 0.78%   |
| Seagate ST2000DM001-1CH164 2TB        | 7         | 8      | 0.78%   |
| Seagate ST1000LM035-1RK172 1TB        | 7         | 7      | 0.78%   |
| Kingston SV300S37A120G 120GB SSD      | 6         | 8      | 0.67%   |
| HGST HTS725050A7E630 500GB            | 6         | 8      | 0.67%   |
| Crucial CT525MX300SSD1 528GB          | 6         | 6      | 0.67%   |
| WDC WD10EADS-22M2B0 1TB               | 5         | 5      | 0.56%   |
| Toshiba MQ01ABD050 500GB              | 5         | 5      | 0.56%   |
| Toshiba DT01ACA100 1TB                | 5         | 6      | 0.56%   |
| Seagate ST500LT012-1DG142 500GB       | 5         | 5      | 0.56%   |
| Seagate ST31000524AS 1TB              | 5         | 5      | 0.56%   |
| Seagate ST1000DM003-1CH162 1TB        | 5         | 5      | 0.56%   |
| Hitachi HTS727575A9E364 752GB         | 5         | 5      | 0.56%   |
| Hitachi HTS545050B9A300 500GB         | 5         | 5      | 0.56%   |
| WDC WD5000AAKX-001CA0 500GB           | 4         | 5      | 0.45%   |
| WDC WD3200AAKS-00L9A0 320GB           | 4         | 4      | 0.45%   |
| WDC WD10EADS-00M2B0 1TB               | 4         | 6      | 0.45%   |
| Toshiba MK5055GSX 500GB               | 4         | 4      | 0.45%   |
| Toshiba MK3265GSX 320GB               | 4         | 5      | 0.45%   |
| SK hynix HFS256G39TND-N210A 256GB SSD | 4         | 4      | 0.45%   |
| Seagate ST3500320AS 500GB             | 4         | 4      | 0.45%   |
| Seagate ST31000528AS 1TB              | 4         | 4      | 0.45%   |
| Seagate ST1000LM048-2E7172 1TB        | 4         | 4      | 0.45%   |
| Samsung Electronics HD321KJ 320GB     | 4         | 4      | 0.45%   |
| Samsung Electronics HD103SJ 1TB       | 4         | 5      | 0.45%   |
| Maxtor STM3500320AS 500GB             | 4         | 5      | 0.45%   |
| LDLC SSD 120GB                        | 4         | 6      | 0.45%   |
| Hitachi HTS547575A9E384 752GB         | 4         | 4      | 0.45%   |
| Hitachi HTS545050A7E380 500GB         | 4         | 4      | 0.45%   |
| Hitachi HTS543232A7A384 320GB         | 4         | 6      | 0.45%   |
| Crucial CT275MX300SSD1 275GB          | 4         | 5      | 0.45%   |
| Crucial CT240M500SSD1 240GB           | 4         | 5      | 0.45%   |
| Crucial CT120M500SSD1 120GB           | 4         | 5      | 0.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 211       | 242    | 23.84%  |
| WDC                 | 189       | 225    | 21.36%  |
| Hitachi             | 82        | 91     | 9.27%   |
| Toshiba             | 65        | 75     | 7.34%   |
| Samsung Electronics | 64        | 70     | 7.23%   |
| HGST                | 49        | 55     | 5.54%   |
| Crucial             | 34        | 37     | 3.84%   |
| Maxtor              | 27        | 31     | 3.05%   |
| Intel               | 27        | 29     | 3.05%   |
| Kingston            | 25        | 28     | 2.82%   |
| SK hynix            | 22        | 28     | 2.49%   |
| SanDisk             | 21        | 24     | 2.37%   |
| Fujitsu             | 8         | 8      | 0.9%    |
| OCZ                 | 7         | 7      | 0.79%   |
| Micron Technology   | 6         | 8      | 0.68%   |
| LDLC                | 6         | 8      | 0.68%   |
| LITEONIT            | 4         | 4      | 0.45%   |
| Corsair             | 4         | 4      | 0.45%   |
| A-DATA Technology   | 4         | 4      | 0.45%   |
| Apacer              | 3         | 3      | 0.34%   |
| SPCC                | 2         | 2      | 0.23%   |
| LITEON              | 2         | 2      | 0.23%   |
| KingSpec            | 2         | 2      | 0.23%   |
| Dogfish             | 2         | 2      | 0.23%   |
| China               | 2         | 2      | 0.23%   |
| Apple               | 2         | 2      | 0.23%   |
| Unknown             | 1         | 1      | 0.11%   |
| TEXTORM             | 1         | 1      | 0.11%   |
| TakeMS              | 1         | 1      | 0.11%   |
| Phison              | 1         | 1      | 0.11%   |
| OCZ-VERTEX          | 1         | 1      | 0.11%   |
| Netac               | 1         | 1      | 0.11%   |
| Magnetic Data       | 1         | 1      | 0.11%   |
| JMicron Technology  | 1         | 1      | 0.11%   |
| Intenso             | 1         | 1      | 0.11%   |
| INNOVATION IT       | 1         | 1      | 0.11%   |
| IBM/Hitachi         | 1         | 1      | 0.11%   |
| Hewlett-Packard     | 1         | 1      | 0.11%   |
| ASMT                | 1         | 1      | 0.11%   |
| ASENNO              | 1         | 1      | 0.11%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 211       | 242    | 31.4%   |
| WDC                 | 186       | 222    | 27.68%  |
| Hitachi             | 82        | 91     | 12.2%   |
| Toshiba             | 61        | 71     | 9.08%   |
| HGST                | 49        | 55     | 7.29%   |
| Samsung Electronics | 42        | 45     | 6.25%   |
| Maxtor              | 27        | 31     | 4.02%   |
| Fujitsu             | 8         | 8      | 1.19%   |
| Unknown             | 1         | 1      | 0.15%   |
| Magnetic Data       | 1         | 1      | 0.15%   |
| IBM/Hitachi         | 1         | 1      | 0.15%   |
| Hewlett-Packard     | 1         | 1      | 0.15%   |
| ASMT                | 1         | 1      | 0.15%   |
| Apple               | 1         | 1      | 0.15%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 628       | 771    | 74.94%  |
| SSD     | 193       | 217    | 23.03%  |
| NVMe    | 16        | 19     | 1.91%   |
| Unknown | 1         | 1      | 0.12%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD7500BPVT-22HXZT1 752GB                     | 2         | 3      | 7.14%   |
| WDC WD3200BEVT-11ZCT0 320GB                      | 2         | 2      | 7.14%   |
| Samsung Electronics MZ7LN512HAJQ-00000 512GB SSD | 2         | 5      | 7.14%   |
| WDC WD5000BEVT-35A0RT0 500GB                     | 1         | 1      | 3.57%   |
| WDC WD4000FYYZ-01UL1B2 4TB                       | 1         | 1      | 3.57%   |
| WDC WD20EARS-00J99B0 2TB                         | 1         | 2      | 3.57%   |
| WDC WD10SPZX-21Z10T0 1TB                         | 1         | 1      | 3.57%   |
| WDC WD10EALX-759BA1 1TB                          | 1         | 1      | 3.57%   |
| Toshiba MQ02ABF050H 500GB                        | 1         | 1      | 3.57%   |
| Toshiba MQ01ABF050 500GB                         | 1         | 1      | 3.57%   |
| Toshiba MQ01ABD075 752GB                         | 1         | 1      | 3.57%   |
| Toshiba MK5055GSX 500GB                          | 1         | 1      | 3.57%   |
| Toshiba MK3259GSXP 320GB                         | 1         | 1      | 3.57%   |
| SK hynix HFS128G39TND-N210A 128GB SSD            | 1         | 1      | 3.57%   |
| Seagate ST3500418ASQ 500GB                       | 1         | 1      | 3.57%   |
| Seagate ST3500418AS 500GB                        | 1         | 1      | 3.57%   |
| Seagate ST3250318AS 250GB                        | 1         | 1      | 3.57%   |
| Seagate ST1000LM048-2E7172 1TB                   | 1         | 1      | 3.57%   |
| Samsung Electronics HM251JI 250GB                | 1         | 1      | 3.57%   |
| Samsung Electronics HE103SJ 1TB                  | 1         | 2      | 3.57%   |
| Samsung Electronics HD753LJ 752GB                | 1         | 1      | 3.57%   |
| Samsung Electronics HD501LJ 500GB                | 1         | 1      | 3.57%   |
| Kingston SMS200S360G 64GB SSD                    | 1         | 1      | 3.57%   |
| HGST HTS721010A9E630 1TB                         | 1         | 1      | 3.57%   |
| HGST HTS545050A7E380 500GB                       | 1         | 1      | 3.57%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 11     | 32.14%  |
| Samsung Electronics | 6         | 10     | 21.43%  |
| Toshiba             | 5         | 5      | 17.86%  |
| Seagate             | 4         | 4      | 14.29%  |
| HGST                | 2         | 2      | 7.14%   |
| SK hynix            | 1         | 1      | 3.57%   |
| Kingston            | 1         | 1      | 3.57%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 3833      | 7977   | 45.79%  |
| Works    | 3693      | 6365   | 44.12%  |
| Malfunc  | 815       | 1008   | 9.74%   |
| Failed   | 28        | 34     | 0.33%   |
| Limited  | 1         | 1      | 0.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 5230      | 55.67%  |
| AMD                                     | 1328      | 14.14%  |
| Samsung Electronics                     | 705       | 7.5%    |
| SanDisk                                 | 329       | 3.5%    |
| SK hynix                                | 230       | 2.45%   |
| Nvidia                                  | 186       | 1.98%   |
| Toshiba America Info Systems            | 151       | 1.61%   |
| Marvell Technology Group                | 149       | 1.59%   |
| Phison Electronics                      | 134       | 1.43%   |
| Micron/Crucial Technology               | 129       | 1.37%   |
| JMicron Technology                      | 124       | 1.32%   |
| ASMedia Technology                      | 120       | 1.28%   |
| Micron Technology                       | 108       | 1.15%   |
| Kingston Technology Company             | 108       | 1.15%   |
| KIOXIA                                  | 75        | 0.8%    |
| VIA Technologies                        | 50        | 0.53%   |
| Silicon Motion                          | 32        | 0.34%   |
| LSI Logic / Symbios Logic               | 23        | 0.24%   |
| Broadcom / LSI                          | 21        | 0.22%   |
| Silicon Image                           | 20        | 0.21%   |
| Union Memory (Shenzhen)                 | 18        | 0.19%   |
| Silicon Integrated Systems [SiS]        | 17        | 0.18%   |
| Lite-On Technology                      | 16        | 0.17%   |
| ADATA Technology                        | 11        | 0.12%   |
| Solid State Storage Technology          | 10        | 0.11%   |
| Adaptec                                 | 10        | 0.11%   |
| Yangtze Memory Technologies             | 8         | 0.09%   |
| Seagate Technology                      | 8         | 0.09%   |
| Lenovo                                  | 6         | 0.06%   |
| Integrated Technology Express           | 6         | 0.06%   |
| Hewlett-Packard                         | 6         | 0.06%   |
| Realtek Semiconductor                   | 5         | 0.05%   |
| Apple                                   | 5         | 0.05%   |
| ULi Electronics                         | 2         | 0.02%   |
| Promise Technology                      | 2         | 0.02%   |
| O2 Micro                                | 2         | 0.02%   |
| Transcend                               | 1         | 0.01%   |
| Tekram Technology                       | 1         | 0.01%   |
| Shenzhen Unionmemory Information System | 1         | 0.01%   |
| Shenzhen Longsys Electronics            | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 880       | 8.08%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 416       | 3.82%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 356       | 3.27%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 332       | 3.05%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 318       | 2.92%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 261       | 2.4%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 204       | 1.87%   |
| AMD 400 Series Chipset SATA Controller                                         | 200       | 1.84%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 194       | 1.78%   |
| Intel Volume Management Device NVMe RAID Controller                            | 185       | 1.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 184       | 1.69%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 181       | 1.66%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 180       | 1.65%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 178       | 1.63%   |
| Intel SATA Controller [RAID mode]                                              | 156       | 1.43%   |
| Samsung NVMe SSD Controller 980                                                | 153       | 1.4%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 153       | 1.4%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 149       | 1.37%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 144       | 1.32%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 139       | 1.28%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 130       | 1.19%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 128       | 1.18%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 118       | 1.08%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 116       | 1.07%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 110       | 1.01%   |
| Micron Non-Volatile memory controller                                          | 108       | 0.99%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 108       | 0.99%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 107       | 0.98%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 96        | 0.88%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 96        | 0.88%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 91        | 0.84%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 91        | 0.84%   |
| Intel Comet Lake SATA AHCI Controller                                          | 90        | 0.83%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 90        | 0.83%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 86        | 0.79%   |
| AMD 500 Series Chipset SATA Controller                                         | 85        | 0.78%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 83        | 0.76%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 82        | 0.75%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 74        | 0.68%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 74        | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 5460      | 57.43%  |
| NVMe | 2109      | 22.18%  |
| IDE  | 1172      | 12.33%  |
| RAID | 719       | 7.56%   |
| SAS  | 28        | 0.29%   |
| SCSI | 19        | 0.2%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 5896      | 77.41%  |
| AMD                   | 1661      | 21.81%  |
| ARM                   | 51        | 0.67%   |
| QUALCOMM              | 4         | 0.05%   |
| CentaurHauls          | 3         | 0.04%   |
| Marvell Semiconductor | 1         | 0.01%   |
| Unknown               | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 104       | 1.36%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 67        | 0.88%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 66        | 0.86%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 65        | 0.85%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 64        | 0.84%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 61        | 0.8%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 56        | 0.73%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 54        | 0.71%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 54        | 0.71%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 53        | 0.69%   |
| AMD Ryzen 5 3600 6-Core Processor             | 51        | 0.67%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 49        | 0.64%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 46        | 0.6%    |
| AMD Ryzen 7 3700X 8-Core Processor            | 46        | 0.6%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 46        | 0.6%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 45        | 0.59%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 45        | 0.59%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 45        | 0.59%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 43        | 0.56%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 43        | 0.56%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 43        | 0.56%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 40        | 0.52%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 40        | 0.52%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 38        | 0.5%    |
| Intel Core i5-8300H CPU @ 2.30GHz             | 36        | 0.47%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 36        | 0.47%   |
| ARM Processor                                 | 36        | 0.47%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 35        | 0.46%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 33        | 0.43%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 33        | 0.43%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 33        | 0.43%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 31        | 0.41%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 30        | 0.39%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 29        | 0.38%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 29        | 0.38%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 28        | 0.37%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 28        | 0.37%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 28        | 0.37%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 28        | 0.37%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 28        | 0.37%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1700      | 22.29%  |
| Intel Core i7           | 1423      | 18.66%  |
| Intel Core i3           | 602       | 7.89%   |
| Other                   | 460       | 6.03%   |
| AMD Ryzen 5             | 365       | 4.79%   |
| Intel Core 2 Duo        | 348       | 4.56%   |
| Intel Celeron           | 336       | 4.41%   |
| AMD Ryzen 7             | 278       | 3.64%   |
| Intel Pentium           | 228       | 2.99%   |
| Intel Xeon              | 195       | 2.56%   |
| Intel Atom              | 156       | 2.05%   |
| Intel Pentium Dual-Core | 109       | 1.43%   |
| Intel Core 2 Quad       | 85        | 1.11%   |
| AMD FX                  | 84        | 1.1%    |
| AMD Ryzen 9             | 82        | 1.08%   |
| AMD Ryzen 3             | 73        | 0.96%   |
| Intel Pentium Dual      | 63        | 0.83%   |
| AMD A4                  | 63        | 0.83%   |
| AMD Athlon II X2        | 59        | 0.77%   |
| Intel Core 2            | 56        | 0.73%   |
| AMD E1                  | 56        | 0.73%   |
| AMD Athlon 64 X2        | 53        | 0.69%   |
| Intel Core i9           | 51        | 0.67%   |
| AMD A6                  | 46        | 0.6%    |
| AMD A8                  | 45        | 0.59%   |
| AMD Phenom II X4        | 39        | 0.51%   |
| AMD E2                  | 38        | 0.5%    |
| AMD Ryzen 7 PRO         | 35        | 0.46%   |
| AMD E                   | 33        | 0.43%   |
| Intel Pentium 4         | 31        | 0.41%   |
| Intel Genuine           | 27        | 0.35%   |
| AMD Athlon              | 25        | 0.33%   |
| Intel Pentium Silver    | 20        | 0.26%   |
| AMD Ryzen 5 PRO         | 20        | 0.26%   |
| AMD Athlon 64           | 19        | 0.25%   |
| Intel Pentium D         | 18        | 0.24%   |
| AMD A10                 | 17        | 0.22%   |
| AMD Sempron             | 15        | 0.2%    |
| AMD Ryzen Threadripper  | 14        | 0.18%   |
| AMD Athlon II X4        | 14        | 0.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 3053      | 39.98%  |
| 4       | 2911      | 38.12%  |
| 6       | 694       | 9.09%   |
| 8       | 479       | 6.27%   |
| 1       | 217       | 2.84%   |
| 12      | 102       | 1.34%   |
| 3       | 44        | 0.58%   |
| Unknown | 35        | 0.46%   |
| 16      | 24        | 0.31%   |
| 10      | 23        | 0.3%    |
| 14      | 15        | 0.2%    |
| 20      | 12        | 0.16%   |
| 32      | 8         | 0.1%    |
| 24      | 8         | 0.1%    |
| 64      | 4         | 0.05%   |
| 40      | 2         | 0.03%   |
| 104     | 1         | 0.01%   |
| 48      | 1         | 0.01%   |
| 36      | 1         | 0.01%   |
| 28      | 1         | 0.01%   |
| 18      | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 7539      | 98.91%  |
| 2       | 75        | 0.98%   |
| Unknown | 5         | 0.07%   |
| 4       | 2         | 0.03%   |
| 3       | 1         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 4729      | 61.9%   |
| 1       | 2875      | 37.63%  |
| Unknown | 35        | 0.46%   |
| 4       | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 7451      | 97.64%  |
| Unknown        | 111       | 1.45%   |
| 32-bit         | 65        | 0.85%   |
| 64-bit         | 4         | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1421      | 18.08%  |
| 0x306c3    | 461       | 5.87%   |
| 0x206a7    | 461       | 5.87%   |
| 0x306a9    | 459       | 5.84%   |
| 0x1067a    | 325       | 4.14%   |
| 0x906ea    | 251       | 3.19%   |
| 0x506e3    | 207       | 2.63%   |
| 0x806c1    | 195       | 2.48%   |
| 0x806ec    | 186       | 2.37%   |
| 0x806ea    | 154       | 1.96%   |
| 0x40651    | 150       | 1.91%   |
| 0x906e9    | 147       | 1.87%   |
| 0x306d4    | 145       | 1.85%   |
| 0x406e3    | 143       | 1.82%   |
| 0x806e9    | 136       | 1.73%   |
| 0x20655    | 128       | 1.63%   |
| 0x6fd      | 126       | 1.6%    |
| 0x010000c8 | 95        | 1.21%   |
| 0x08108109 | 92        | 1.17%   |
| 0x10676    | 86        | 1.09%   |
| 0x08600106 | 82        | 1.04%   |
| 0x08701021 | 81        | 1.03%   |
| 0x406c4    | 75        | 0.95%   |
| 0x0800820d | 70        | 0.89%   |
| 0xa0652    | 65        | 0.83%   |
| 0x30678    | 65        | 0.83%   |
| 0x906ed    | 62        | 0.79%   |
| 0x106e5    | 60        | 0.76%   |
| 0x706e5    | 56        | 0.71%   |
| 0x06001119 | 54        | 0.69%   |
| 0x08701013 | 51        | 0.65%   |
| 0x06000852 | 51        | 0.65%   |
| 0x506c9    | 49        | 0.62%   |
| 0x07030105 | 49        | 0.62%   |
| 0x0a50000c | 48        | 0.61%   |
| 0x806eb    | 47        | 0.6%    |
| 0x406c3    | 47        | 0.6%    |
| 0x706a1    | 46        | 0.59%   |
| 0x6fb      | 45        | 0.57%   |
| 0x05000119 | 44        | 0.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 1221      | 16.02%  |
| Haswell          | 747       | 9.8%    |
| SandyBridge      | 542       | 7.11%   |
| IvyBridge        | 533       | 6.99%   |
| Penryn           | 472       | 6.19%   |
| Skylake          | 453       | 5.94%   |
| Zen 2            | 331       | 4.34%   |
| Core             | 270       | 3.54%   |
| Zen+             | 239       | 3.14%   |
| TigerLake        | 235       | 3.08%   |
| Silvermont       | 234       | 3.07%   |
| Westmere         | 214       | 2.81%   |
| Broadwell        | 193       | 2.53%   |
| K10              | 181       | 2.37%   |
| Unknown          | 173       | 2.27%   |
| CometLake        | 164       | 2.15%   |
| Zen 3            | 141       | 1.85%   |
| Piledriver       | 136       | 1.78%   |
| Zen              | 131       | 1.72%   |
| Icelake          | 123       | 1.61%   |
| K8 Hammer        | 109       | 1.43%   |
| Nehalem          | 103       | 1.35%   |
| Goldmont plus    | 96        | 1.26%   |
| Bobcat           | 76        | 1%      |
| Excavator        | 71        | 0.93%   |
| Puma             | 69        | 0.91%   |
| Bonnell          | 65        | 0.85%   |
| Goldmont         | 60        | 0.79%   |
| NetBurst         | 54        | 0.71%   |
| Alderlake Hybrid | 50        | 0.66%   |
| Jaguar           | 41        | 0.54%   |
| K10 Llano        | 25        | 0.33%   |
| P6               | 22        | 0.29%   |
| Steamroller      | 13        | 0.17%   |
| K8 & K10 hybrid  | 12        | 0.16%   |
| Bulldozer        | 12        | 0.16%   |
| Tremont          | 6         | 0.08%   |
| K6               | 5         | 0.07%   |
| Sapphire Rapids  | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 4292      | 47.54%  |
| Nvidia                                       | 2789      | 30.89%  |
| AMD                                          | 1854      | 20.54%  |
| Matrox Electronics Systems                   | 44        | 0.49%   |
| ASPEED Technology                            | 24        | 0.27%   |
| Silicon Integrated Systems [SiS]             | 10        | 0.11%   |
| VIA Technologies                             | 9         | 0.1%    |
| ATI Technologies                             | 3         | 0.03%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.01%   |
| S3 Graphics                                  | 1         | 0.01%   |
| Red Hat                                      | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 369       | 3.98%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 293       | 3.16%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 221       | 2.38%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 209       | 2.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 171       | 1.84%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 171       | 1.84%   |
| Intel UHD Graphics 620                                                                   | 155       | 1.67%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 153       | 1.65%   |
| AMD Renoir                                                                               | 152       | 1.64%   |
| Intel HD Graphics 530                                                                    | 149       | 1.61%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 148       | 1.59%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 147       | 1.58%   |
| Intel HD Graphics 620                                                                    | 147       | 1.58%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 144       | 1.55%   |
| Intel HD Graphics 5500                                                                   | 143       | 1.54%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 143       | 1.54%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 136       | 1.47%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 134       | 1.44%   |
| Intel Core Processor Integrated Graphics Controller                                      | 112       | 1.21%   |
| Intel HD Graphics 630                                                                    | 107       | 1.15%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 94        | 1.01%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 93        | 1%      |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 91        | 0.98%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 84        | 0.91%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 77        | 0.83%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 76        | 0.82%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 71        | 0.77%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 71        | 0.77%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 66        | 0.71%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 65        | 0.7%    |
| Nvidia GT218 [GeForce 210]                                                               | 62        | 0.67%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 61        | 0.66%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 61        | 0.66%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 55        | 0.59%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 51        | 0.55%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 50        | 0.54%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 49        | 0.53%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 48        | 0.52%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 48        | 0.52%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 48        | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| 1 x Intel            | 2953      | 38.48%  |
| 1 x Nvidia           | 1611      | 20.99%  |
| 1 x AMD              | 1463      | 19.06%  |
| Intel + Nvidia       | 1063      | 13.85%  |
| Intel + AMD          | 185       | 2.41%   |
| 2 x AMD              | 111       | 1.45%   |
| AMD + Nvidia         | 96        | 1.25%   |
| Other                | 63        | 0.82%   |
| 1 x Matrox           | 39        | 0.51%   |
| 2 x Nvidia           | 24        | 0.31%   |
| 1 x ASPEED           | 21        | 0.27%   |
| 1 x SiS              | 10        | 0.13%   |
| 2 x Intel            | 9         | 0.12%   |
| 1 x VIA              | 9         | 0.12%   |
| Nvidia + Matrox      | 4         | 0.05%   |
| 3 x AMD              | 2         | 0.03%   |
| Intel + 2 x Nvidia   | 2         | 0.03%   |
| AMD + ASPEED         | 2         | 0.03%   |
| 3 x Nvidia           | 1         | 0.01%   |
| 2 x AMD + 1 x Nvidia | 1         | 0.01%   |
| 1 x XGI              | 1         | 0.01%   |
| 1 x S3 Graphics      | 1         | 0.01%   |
| 1 x Red Hat          | 1         | 0.01%   |
| Nvidia + ASPEED      | 1         | 0.01%   |
| Intel + 2 x AMD      | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 6048      | 78.24%  |
| Proprietary | 1345      | 17.4%   |
| Unknown     | 337       | 4.36%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 4039      | 51.7%   |
| 0.01-0.5   | 1069      | 13.68%  |
| 1.01-2.0   | 996       | 12.75%  |
| 0.51-1.0   | 663       | 8.49%   |
| 3.01-4.0   | 497       | 6.36%   |
| 7.01-8.0   | 234       | 3%      |
| 5.01-6.0   | 172       | 2.2%    |
| 8.01-16.0  | 67        | 0.86%   |
| 2.01-3.0   | 64        | 0.82%   |
| 16.01-24.0 | 8         | 0.1%    |
| 4.01-5.0   | 4         | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 1071      | 12.74%  |
| AU Optronics            | 1025      | 12.19%  |
| LG Display              | 662       | 7.87%   |
| Chimei Innolux          | 655       | 7.79%   |
| BOE                     | 584       | 6.94%   |
| Iiyama                  | 443       | 5.27%   |
| Dell                    | 434       | 5.16%   |
| Hewlett-Packard         | 334       | 3.97%   |
| Acer                    | 296       | 3.52%   |
| Goldstar                | 292       | 3.47%   |
| Ancor Communications    | 237       | 2.82%   |
| Philips                 | 212       | 2.52%   |
| AOC                     | 183       | 2.18%   |
| Sharp                   | 174       | 2.07%   |
| BenQ                    | 164       | 1.95%   |
| Lenovo                  | 137       | 1.63%   |
| Chi Mei Optoelectronics | 136       | 1.62%   |
| Apple                   | 121       | 1.44%   |
| ViewSonic               | 110       | 1.31%   |
| PANDA                   | 64        | 0.76%   |
| LG Philips              | 61        | 0.73%   |
| ASUSTek Computer        | 61        | 0.73%   |
| InfoVision              | 59        | 0.7%    |
| HannStar                | 47        | 0.56%   |
| Unknown                 | 45        | 0.54%   |
| Sony                    | 44        | 0.52%   |
| Packard Bell            | 31        | 0.37%   |
| Fujitsu Siemens         | 30        | 0.36%   |
| LG Electronics          | 29        | 0.34%   |
| Idek Iiyama             | 28        | 0.33%   |
| Vestel Elektronik       | 27        | 0.32%   |
| NEC Computers           | 24        | 0.29%   |
| Medion                  | 22        | 0.26%   |
| Eizo                    | 22        | 0.26%   |
| Toshiba                 | 21        | 0.25%   |
| Panasonic               | 20        | 0.24%   |
| Hitachi                 | 20        | 0.24%   |
| CPT                     | 18        | 0.21%   |
| CSO                     | 17        | 0.2%    |
| MSI                     | 16        | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 42        | 0.48%   |
| Iiyama PLE2483H IVM6113 1920x1080 530x300mm 24.0-inch                     | 40        | 0.46%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 38        | 0.44%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 33        | 0.38%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 29        | 0.33%   |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 890x500mm 40.2-inch      | 27        | 0.31%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch         | 26        | 0.3%    |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch            | 25        | 0.29%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 25        | 0.29%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch      | 24        | 0.28%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch            | 24        | 0.28%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch         | 23        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 23        | 0.26%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 23        | 0.26%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch             | 23        | 0.26%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch           | 22        | 0.25%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 21        | 0.24%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 21        | 0.24%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 18        | 0.21%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch          | 18        | 0.21%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 382x214mm 17.2-inch           | 18        | 0.21%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 18        | 0.21%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch             | 18        | 0.21%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch             | 18        | 0.21%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 17        | 0.2%    |
| AU Optronics LCD Monitor AUO109E 1600x900 382x214mm 17.2-inch             | 17        | 0.2%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch         | 16        | 0.18%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 16        | 0.18%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch  | 16        | 0.18%   |
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch                    | 15        | 0.17%   |
| Iiyama PLX2783H IVM6611 1920x1080 598x336mm 27.0-inch                     | 15        | 0.17%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch           | 15        | 0.17%   |
| BenQ GW2270 BNQ78DB 1920x1080 480x270mm 21.7-inch                         | 15        | 0.17%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch             | 15        | 0.17%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch            | 15        | 0.17%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                   | 14        | 0.16%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                   | 14        | 0.16%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch         | 14        | 0.16%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch      | 14        | 0.16%   |
| Iiyama PL2530H IVM6132 1920x1080 544x303mm 24.5-inch                      | 14        | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 3596      | 45.1%   |
| 1366x768 (WXGA)    | 1180      | 14.8%   |
| 1600x900 (HD+)     | 510       | 6.4%    |
| 3840x2160 (4K)     | 367       | 4.6%    |
| 1680x1050 (WSXGA+) | 331       | 4.15%   |
| 2560x1440 (QHD)    | 328       | 4.11%   |
| 1280x1024 (SXGA)   | 308       | 3.86%   |
| 1440x900 (WXGA+)   | 247       | 3.1%    |
| 1920x1200 (WUXGA)  | 238       | 2.98%   |
| 1280x800 (WXGA)    | 173       | 2.17%   |
| Unknown            | 108       | 1.35%   |
| 3440x1440          | 52        | 0.65%   |
| 1360x768           | 50        | 0.63%   |
| 3840x1080          | 48        | 0.6%    |
| 2560x1080          | 45        | 0.56%   |
| 2560x1600          | 35        | 0.44%   |
| 1600x1200          | 31        | 0.39%   |
| 1024x600           | 31        | 0.39%   |
| 2160x1440          | 25        | 0.31%   |
| 2880x1800          | 24        | 0.3%    |
| 1024x768 (XGA)     | 24        | 0.3%    |
| 3840x2400          | 19        | 0.24%   |
| 800x1280           | 17        | 0.21%   |
| 1920x540           | 17        | 0.21%   |
| 3200x1800 (QHD+)   | 12        | 0.15%   |
| 2288x1287          | 9         | 0.11%   |
| 4480x1440          | 8         | 0.1%    |
| 3840x1600          | 7         | 0.09%   |
| 3200x1080          | 7         | 0.09%   |
| 3000x2000          | 7         | 0.09%   |
| 2736x1824          | 7         | 0.09%   |
| 3600x1080          | 6         | 0.08%   |
| 1680x945           | 6         | 0.08%   |
| 5760x2160          | 5         | 0.06%   |
| 3840x1200          | 5         | 0.06%   |
| 5760x1080          | 4         | 0.05%   |
| 2048x1152          | 4         | 0.05%   |
| 1920x515           | 4         | 0.05%   |
| 1400x1050          | 4         | 0.05%   |
| 1280x960           | 4         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1845      | 22.04%  |
| 17      | 819       | 9.78%   |
| 13      | 721       | 8.61%   |
| 24      | 682       | 8.15%   |
| 23      | 665       | 7.94%   |
| 27      | 615       | 7.35%   |
| 14      | 500       | 5.97%   |
| 21      | 488       | 5.83%   |
| Unknown | 417       | 4.98%   |
| 19      | 296       | 3.54%   |
| 22      | 226       | 2.7%    |
| 12      | 144       | 1.72%   |
| 20      | 139       | 1.66%   |
| 18      | 130       | 1.55%   |
| 31      | 95        | 1.13%   |
| 34      | 79        | 0.94%   |
| 11      | 70        | 0.84%   |
| 84      | 56        | 0.67%   |
| 16      | 52        | 0.62%   |
| 10      | 46        | 0.55%   |
| 72      | 40        | 0.48%   |
| 32      | 35        | 0.42%   |
| 25      | 35        | 0.42%   |
| 54      | 28        | 0.33%   |
| 26      | 20        | 0.24%   |
| 33      | 19        | 0.23%   |
| 46      | 12        | 0.14%   |
| 40      | 9         | 0.11%   |
| 48      | 8         | 0.1%    |
| 65      | 7         | 0.08%   |
| 52      | 7         | 0.08%   |
| 49      | 7         | 0.08%   |
| 29      | 6         | 0.07%   |
| 142     | 5         | 0.06%   |
| 43      | 5         | 0.06%   |
| 42      | 5         | 0.06%   |
| 37      | 5         | 0.06%   |
| 39      | 4         | 0.05%   |
| 38      | 4         | 0.05%   |
| 35      | 4         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 2762      | 33.69%  |
| 501-600        | 1800      | 21.95%  |
| 401-500        | 1095      | 13.36%  |
| 351-400        | 938       | 11.44%  |
| 201-300        | 664       | 8.1%    |
| Unknown        | 417       | 5.09%   |
| 601-700        | 170       | 2.07%   |
| 701-800        | 134       | 1.63%   |
| 1501-2000      | 98        | 1.2%    |
| 1001-1500      | 79        | 0.96%   |
| 801-900        | 27        | 0.33%   |
| 901-1000       | 8         | 0.1%    |
| More than 2000 | 5         | 0.06%   |
| 101-200        | 2         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 5566      | 73.91%  |
| 16/10   | 1027      | 13.64%  |
| Unknown | 335       | 4.45%   |
| 5/4     | 294       | 3.9%    |
| 21/9    | 94        | 1.25%   |
| 3/2     | 77        | 1.02%   |
| 4/3     | 73        | 0.97%   |
| 0.62    | 18        | 0.24%   |
| 6/5     | 14        | 0.19%   |
| 32/9    | 13        | 0.17%   |
| 1.00    | 5         | 0.07%   |
| 3.20    | 4         | 0.05%   |
| 3.73    | 3         | 0.04%   |
| 11/10   | 2         | 0.03%   |
| 0.56    | 2         | 0.03%   |
| 3.88    | 1         | 0.01%   |
| 2.00    | 1         | 0.01%   |
| 1.03    | 1         | 0.01%   |
| 0.45    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1859      | 22.45%  |
| 201-250        | 1648      | 19.9%   |
| 81-90          | 875       | 10.57%  |
| 301-350        | 636       | 7.68%   |
| 151-200        | 601       | 7.26%   |
| 121-130        | 572       | 6.91%   |
| Unknown        | 417       | 5.04%   |
| 71-80          | 356       | 4.3%    |
| 251-300        | 252       | 3.04%   |
| 351-500        | 233       | 2.81%   |
| 141-150        | 223       | 2.69%   |
| More than 1000 | 155       | 1.87%   |
| 61-70          | 125       | 1.51%   |
| 131-140        | 108       | 1.3%    |
| 51-60          | 70        | 0.85%   |
| 501-1000       | 60        | 0.72%   |
| 41-50          | 47        | 0.57%   |
| 111-120        | 29        | 0.35%   |
| 91-100         | 14        | 0.17%   |
| 1-40           | 2         | 0.02%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 2919      | 36.27%  |
| 101-120       | 2049      | 25.46%  |
| 121-160       | 1993      | 24.77%  |
| Unknown       | 417       | 5.18%   |
| 161-240       | 397       | 4.93%   |
| More than 240 | 149       | 1.85%   |
| 1-50          | 123       | 1.53%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 6030      | 77.48%  |
| 2     | 1231      | 15.82%  |
| 0     | 374       | 4.81%   |
| 3     | 140       | 1.8%    |
| 4     | 6         | 0.08%   |
| 6     | 1         | 0.01%   |
| 5     | 1         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 4076      | 35.93%  |
| Intel                             | 3608      | 31.81%  |
| Qualcomm Atheros                  | 1398      | 12.32%  |
| Broadcom                          | 642       | 5.66%   |
| Marvell Technology Group          | 173       | 1.53%   |
| Nvidia                            | 139       | 1.23%   |
| Broadcom Limited                  | 134       | 1.18%   |
| Ralink                            | 128       | 1.13%   |
| TP-Link                           | 91        | 0.8%    |
| MediaTek                          | 90        | 0.79%   |
| Ralink Technology                 | 68        | 0.6%    |
| NetGear                           | 64        | 0.56%   |
| Samsung Electronics               | 52        | 0.46%   |
| ASIX Electronics                  | 51        | 0.45%   |
| Dell                              | 42        | 0.37%   |
| D-Link System                     | 35        | 0.31%   |
| Xiaomi                            | 33        | 0.29%   |
| Huawei Technologies               | 25        | 0.22%   |
| Ericsson Business Mobile Networks | 25        | 0.22%   |
| DisplayLink                       | 25        | 0.22%   |
| D-Link                            | 24        | 0.21%   |
| VIA Technologies                  | 23        | 0.2%    |
| Sierra Wireless                   | 21        | 0.19%   |
| Microsoft                         | 21        | 0.19%   |
| Aquantia                          | 21        | 0.19%   |
| JMicron Technology                | 20        | 0.18%   |
| Lenovo                            | 19        | 0.17%   |
| Belkin Components                 | 19        | 0.17%   |
| Qualcomm                          | 17        | 0.15%   |
| Silicon Integrated Systems [SiS]  | 14        | 0.12%   |
| Qualcomm Atheros Communications   | 14        | 0.12%   |
| Attansic Technology               | 14        | 0.12%   |
| OPPO Electronics                  | 11        | 0.1%    |
| Hewlett-Packard                   | 11        | 0.1%    |
| Guillemot                         | 11        | 0.1%    |
| ASUSTek Computer                  | 11        | 0.1%    |
| OnePlus Technology (Shenzhen)     | 9         | 0.08%   |
| Google                            | 9         | 0.08%   |
| Edimax Technology                 | 9         | 0.08%   |
| Microchip Technology              | 8         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2838      | 21.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 406       | 3.05%   |
| Intel Wi-Fi 6 AX200                                               | 321       | 2.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 274       | 2.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 254       | 1.91%   |
| Intel Wireless 8265 / 8275                                        | 207       | 1.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 196       | 1.47%   |
| Intel Wireless 7265                                               | 188       | 1.41%   |
| Intel Wi-Fi 6 AX201                                               | 182       | 1.37%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 168       | 1.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 164       | 1.23%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 153       | 1.15%   |
| Intel Wireless 8260                                               | 146       | 1.1%    |
| Intel Wireless 7260                                               | 142       | 1.07%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 135       | 1.01%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 128       | 0.96%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 125       | 0.94%   |
| Intel I211 Gigabit Network Connection                             | 125       | 0.94%   |
| Realtek RTL8125 2.5GbE Controller                                 | 119       | 0.89%   |
| Intel Ethernet Connection (2) I219-V                              | 117       | 0.88%   |
| Intel Ethernet Connection I217-LM                                 | 113       | 0.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 112       | 0.84%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 109       | 0.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 107       | 0.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 103       | 0.77%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 99        | 0.74%   |
| Intel Wireless 3165                                               | 97        | 0.73%   |
| Intel Wireless-AC 9260                                            | 87        | 0.65%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 84        | 0.63%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 83        | 0.62%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 83        | 0.62%   |
| Intel 82579V Gigabit Network Connection                           | 82        | 0.62%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 75        | 0.56%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 69        | 0.52%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 69        | 0.52%   |
| Intel Ethernet Connection (7) I219-V                              | 69        | 0.52%   |
| Broadcom BCM43142 802.11b/g/n                                     | 65        | 0.49%   |
| Intel Ethernet Connection I217-V                                  | 62        | 0.47%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 60        | 0.45%   |
| Intel Ethernet Connection (4) I219-LM                             | 57        | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2673      | 45.68%  |
| Qualcomm Atheros                      | 1073      | 18.34%  |
| Realtek Semiconductor                 | 978       | 16.71%  |
| Broadcom                              | 390       | 6.66%   |
| Ralink                                | 128       | 2.19%   |
| TP-Link                               | 85        | 1.45%   |
| Broadcom Limited                      | 78        | 1.33%   |
| MediaTek                              | 77        | 1.32%   |
| Ralink Technology                     | 68        | 1.16%   |
| NetGear                               | 60        | 1.03%   |
| D-Link                                | 23        | 0.39%   |
| Sierra Wireless                       | 21        | 0.36%   |
| Microsoft                             | 21        | 0.36%   |
| Dell                                  | 21        | 0.36%   |
| D-Link System                         | 19        | 0.32%   |
| Belkin Components                     | 19        | 0.32%   |
| Marvell Technology Group              | 17        | 0.29%   |
| Qualcomm Atheros Communications       | 14        | 0.24%   |
| Guillemot                             | 11        | 0.19%   |
| ASUSTek Computer                      | 11        | 0.19%   |
| Qualcomm                              | 9         | 0.15%   |
| Edimax Technology                     | 9         | 0.15%   |
| Fibocom                               | 6         | 0.1%    |
| Sagem                                 | 5         | 0.09%   |
| IMC Networks                          | 5         | 0.09%   |
| Hewlett-Packard                       | 5         | 0.09%   |
| TRENDnet                              | 4         | 0.07%   |
| Gemtek                                | 3         | 0.05%   |
| Accton Technology                     | 3         | 0.05%   |
| ZyDAS                                 | 2         | 0.03%   |
| Toshiba                               | 2         | 0.03%   |
| Linksys                               | 2         | 0.03%   |
| Fujitsu Siemens Computers             | 2         | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.03%   |
| Wilocity                              | 1         | 0.02%   |
| Texas Instruments                     | 1         | 0.02%   |
| Tenda                                 | 1         | 0.02%   |
| Micro Star International              | 1         | 0.02%   |
| BUFFALO                               | 1         | 0.02%   |
| Apple                                 | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 321       | 5.45%   |
| Intel Wireless 8265 / 8275                                              | 207       | 3.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 196       | 3.33%   |
| Intel Wireless 7265                                                     | 188       | 3.19%   |
| Intel Wi-Fi 6 AX201                                                     | 182       | 3.09%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 168       | 2.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 164       | 2.79%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 153       | 2.6%    |
| Intel Wireless 8260                                                     | 146       | 2.48%   |
| Intel Wireless 7260                                                     | 142       | 2.41%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 135       | 2.29%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 128       | 2.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 125       | 2.12%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 112       | 1.9%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 109       | 1.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 107       | 1.82%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 103       | 1.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 99        | 1.68%   |
| Intel Wireless 3165                                                     | 97        | 1.65%   |
| Intel Wireless-AC 9260                                                  | 87        | 1.48%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 84        | 1.43%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 83        | 1.41%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 75        | 1.27%   |
| Broadcom BCM43142 802.11b/g/n                                           | 65        | 1.1%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 60        | 1.02%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 55        | 0.93%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 53        | 0.9%    |
| Intel Wireless 3160                                                     | 53        | 0.9%    |
| Realtek RTL8188EE Wireless Network Adapter                              | 52        | 0.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 51        | 0.87%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 49        | 0.83%   |
| Intel WiFi Link 5100                                                    | 49        | 0.83%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 47        | 0.8%    |
| Intel Centrino Wireless-N 2230                                          | 47        | 0.8%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 46        | 0.78%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 45        | 0.76%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 44        | 0.75%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 44        | 0.75%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 43        | 0.73%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 43        | 0.73%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 3718      | 52.27%  |
| Intel                             | 1838      | 25.84%  |
| Qualcomm Atheros                  | 480       | 6.75%   |
| Broadcom                          | 309       | 4.34%   |
| Marvell Technology Group          | 156       | 2.19%   |
| Nvidia                            | 139       | 1.95%   |
| Broadcom Limited                  | 59        | 0.83%   |
| Samsung Electronics               | 51        | 0.72%   |
| ASIX Electronics                  | 51        | 0.72%   |
| Xiaomi                            | 33        | 0.46%   |
| DisplayLink                       | 25        | 0.35%   |
| Aquantia                          | 21        | 0.3%    |
| VIA Technologies                  | 20        | 0.28%   |
| JMicron Technology                | 20        | 0.28%   |
| Lenovo                            | 19        | 0.27%   |
| Huawei Technologies               | 19        | 0.27%   |
| D-Link System                     | 16        | 0.22%   |
| Attansic Technology               | 14        | 0.2%    |
| Silicon Integrated Systems [SiS]  | 13        | 0.18%   |
| MediaTek                          | 12        | 0.17%   |
| OPPO Electronics                  | 11        | 0.15%   |
| Google                            | 9         | 0.13%   |
| Qualcomm                          | 8         | 0.11%   |
| OnePlus Technology (Shenzhen)     | 7         | 0.1%    |
| ICS Advent                        | 7         | 0.1%    |
| TP-Link                           | 6         | 0.08%   |
| Microchip Technology              | 5         | 0.07%   |
| NetGear                           | 4         | 0.06%   |
| Motorola PCS                      | 4         | 0.06%   |
| Mellanox Technologies             | 4         | 0.06%   |
| Apple                             | 4         | 0.06%   |
| QLogic                            | 3         | 0.04%   |
| 3Com                              | 3         | 0.04%   |
| Linksys                           | 2         | 0.03%   |
| HTC (High Tech Computer)          | 2         | 0.03%   |
| Cypress Semiconductor             | 2         | 0.03%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.01%   |
| ULi Electronics                   | 1         | 0.01%   |
| Tehuti Networks                   | 1         | 0.01%   |
| Sundance Technology Inc / IC Plus | 1         | 0.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2838      | 38.98%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 406       | 5.58%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 274       | 3.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 254       | 3.49%   |
| Intel I211 Gigabit Network Connection                             | 125       | 1.72%   |
| Realtek RTL8125 2.5GbE Controller                                 | 119       | 1.63%   |
| Intel Ethernet Connection (2) I219-V                              | 117       | 1.61%   |
| Intel Ethernet Connection I217-LM                                 | 113       | 1.55%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 83        | 1.14%   |
| Intel 82579V Gigabit Network Connection                           | 82        | 1.13%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 69        | 0.95%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 69        | 0.95%   |
| Intel Ethernet Connection (7) I219-V                              | 69        | 0.95%   |
| Intel Ethernet Connection I217-V                                  | 62        | 0.85%   |
| Intel Ethernet Connection (4) I219-LM                             | 57        | 0.78%   |
| Intel Ethernet Connection (2) I219-LM                             | 57        | 0.78%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 53        | 0.73%   |
| Intel Ethernet Connection (3) I218-LM                             | 53        | 0.73%   |
| Intel Ethernet Connection (7) I219-LM                             | 52        | 0.71%   |
| Nvidia MCP61 Ethernet                                             | 51        | 0.7%    |
| Intel Ethernet Connection I219-LM                                 | 50        | 0.69%   |
| Intel Ethernet Connection (6) I219-V                              | 48        | 0.66%   |
| Intel Ethernet Connection (2) I218-V                              | 46        | 0.63%   |
| ASIX AX88179 Gigabit Ethernet                                     | 45        | 0.62%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 42        | 0.58%   |
| Intel Ethernet Controller I225-V                                  | 42        | 0.58%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 41        | 0.56%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 40        | 0.55%   |
| Intel 82574L Gigabit Network Connection                           | 40        | 0.55%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 39        | 0.54%   |
| Intel I210 Gigabit Network Connection                             | 39        | 0.54%   |
| Intel Ethernet Connection I218-LM                                 | 39        | 0.54%   |
| Intel 82577LM Gigabit Network Connection                          | 38        | 0.52%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 37        | 0.51%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 36        | 0.49%   |
| Intel 82567LM Gigabit Network Connection                          | 34        | 0.47%   |
| Nvidia MCP79 Ethernet                                             | 33        | 0.45%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 31        | 0.43%   |
| Intel Ethernet Connection (4) I219-V                              | 31        | 0.43%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 30        | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 6685      | 53.75%  |
| WiFi     | 5619      | 45.18%  |
| Modem    | 117       | 0.94%   |
| Unknown  | 17        | 0.14%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 4175      | 52.52%  |
| Ethernet | 3773      | 47.47%  |
| Unknown  | 1         | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 4187      | 54.74%  |
| 1     | 3137      | 41.01%  |
| 3     | 146       | 1.91%   |
| 0     | 139       | 1.82%   |
| 4     | 29        | 0.38%   |
| 5     | 5         | 0.07%   |
| 8     | 3         | 0.04%   |
| 6     | 3         | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 5176      | 66.06%  |
| Yes  | 2659      | 33.94%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2135      | 49.57%  |
| Realtek Semiconductor           | 339       | 7.87%   |
| IMC Networks                    | 286       | 6.64%   |
| Cambridge Silicon Radio         | 284       | 6.59%   |
| Qualcomm Atheros Communications | 256       | 5.94%   |
| Broadcom                        | 203       | 4.71%   |
| Apple                           | 133       | 3.09%   |
| Lite-On Technology              | 128       | 2.97%   |
| Foxconn / Hon Hai               | 115       | 2.67%   |
| ASUSTek Computer                | 84        | 1.95%   |
| Dell                            | 78        | 1.81%   |
| Realtek                         | 42        | 0.98%   |
| Hewlett-Packard                 | 37        | 0.86%   |
| Toshiba                         | 35        | 0.81%   |
| Ralink                          | 30        | 0.7%    |
| Ralink Technology               | 19        | 0.44%   |
| Belkin Components               | 14        | 0.33%   |
| Marvell Semiconductor           | 13        | 0.3%    |
| Alps Electric                   | 13        | 0.3%    |
| MediaTek                        | 12        | 0.28%   |
| Foxconn International           | 12        | 0.28%   |
| TP-Link                         | 9         | 0.21%   |
| Integrated System Solution      | 6         | 0.14%   |
| Chicony Electronics             | 5         | 0.12%   |
| HTC (High Tech Computer)        | 3         | 0.07%   |
| USI                             | 2         | 0.05%   |
| Fujitsu                         | 2         | 0.05%   |
| Conwise Technology              | 2         | 0.05%   |
| TRENDnet                        | 1         | 0.02%   |
| Syntek                          | 1         | 0.02%   |
| Micro Star International        | 1         | 0.02%   |
| Logitech                        | 1         | 0.02%   |
| Kensington                      | 1         | 0.02%   |
| D-Link System                   | 1         | 0.02%   |
| D-Link                          | 1         | 0.02%   |
| Creative Technology             | 1         | 0.02%   |
| Corsair                         | 1         | 0.02%   |
| Com One                         | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 790       | 18.34%  |
| Intel AX201 Bluetooth                               | 414       | 9.61%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 327       | 7.59%   |
| Intel AX200 Bluetooth                               | 301       | 6.99%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 284       | 6.59%   |
| Realtek Bluetooth Radio                             | 221       | 5.13%   |
| IMC Networks Bluetooth Device                       | 116       | 2.69%   |
| Qualcomm Atheros  Bluetooth Device                  | 96        | 2.23%   |
| IMC Networks Bluetooth Radio                        | 88        | 2.04%   |
| Realtek  Bluetooth 4.2 Adapter                      | 85        | 1.97%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 78        | 1.81%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 69        | 1.6%    |
| Foxconn / Hon Hai Bluetooth Device                  | 54        | 1.25%   |
| Intel Wireless-AC 3168 Bluetooth                    | 49        | 1.14%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 48        | 1.11%   |
| Apple Bluetooth Host Controller                     | 48        | 1.11%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 46        | 1.07%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 45        | 1.04%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 44        | 1.02%   |
| Realtek Bluetooth Radio                             | 42        | 0.97%   |
| Apple Bluetooth USB Host Controller                 | 40        | 0.93%   |
| Intel AX210 Bluetooth                               | 39        | 0.91%   |
| Lite-On Bluetooth Device                            | 36        | 0.84%   |
| Intel Bluetooth Device                              | 36        | 0.84%   |
| Dell DW375 Bluetooth Module                         | 33        | 0.77%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 32        | 0.74%   |
| Ralink RT3290 Bluetooth                             | 30        | 0.7%    |
| Broadcom BCM2045B (BDC-2.1)                         | 26        | 0.6%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 24        | 0.56%   |
| Foxconn / Hon Hai Wireless_Device                   | 24        | 0.56%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 24        | 0.56%   |
| IMC Networks Wireless_Device                        | 23        | 0.53%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 23        | 0.53%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 23        | 0.53%   |
| Lite-On Atheros AR3012 Bluetooth                    | 22        | 0.51%   |
| HP Broadcom 2070 Bluetooth Combo                    | 20        | 0.46%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 20        | 0.46%   |
| Apple Bluetooth HCI                                 | 20        | 0.46%   |
| Realtek RTL8723B Bluetooth                          | 19        | 0.44%   |
| Dell BCM20702A0 Bluetooth Module                    | 17        | 0.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 5580      | 52.33%  |
| Nvidia                           | 1997      | 18.73%  |
| AMD                              | 1991      | 18.67%  |
| C-Media Electronics              | 160       | 1.5%    |
| Logitech                         | 98        | 0.92%   |
| Creative Labs                    | 72        | 0.68%   |
| Realtek Semiconductor            | 63        | 0.59%   |
| GN Netcom                        | 57        | 0.53%   |
| JMTek                            | 40        | 0.38%   |
| Kingston Technology              | 39        | 0.37%   |
| Texas Instruments                | 38        | 0.36%   |
| Plantronics                      | 38        | 0.36%   |
| Corsair                          | 38        | 0.36%   |
| VIA Technologies                 | 33        | 0.31%   |
| Focusrite-Novation               | 25        | 0.23%   |
| SteelSeries ApS                  | 23        | 0.22%   |
| Lenovo                           | 18        | 0.17%   |
| Silicon Integrated Systems [SiS] | 17        | 0.16%   |
| Razer USA                        | 17        | 0.16%   |
| Sennheiser Communications        | 16        | 0.15%   |
| Generalplus Technology           | 16        | 0.15%   |
| Hewlett-Packard                  | 13        | 0.12%   |
| XMOS                             | 11        | 0.1%    |
| Creative Technology              | 11        | 0.1%    |
| M-Audio                          | 9         | 0.08%   |
| Sony                             | 8         | 0.08%   |
| ASUSTek Computer                 | 8         | 0.08%   |
| Ensoniq                          | 7         | 0.07%   |
| DSEA A/S                         | 7         | 0.07%   |
| BEHRINGER International          | 7         | 0.07%   |
| RODE Microphones                 | 6         | 0.06%   |
| GYROCOM C&C                      | 6         | 0.06%   |
| Dell                             | 6         | 0.06%   |
| Yamaha                           | 5         | 0.05%   |
| Turtle Beach                     | 5         | 0.05%   |
| Tenx Technology                  | 5         | 0.05%   |
| PreSonus Audio Electronics       | 5         | 0.05%   |
| Medeli Electronics               | 5         | 0.05%   |
| Blue Microphones                 | 5         | 0.05%   |
| Unknown                          | 4         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 529       | 4.24%   |
| Intel Sunrise Point-LP HD Audio                                            | 500       | 4.01%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 487       | 3.91%   |
| AMD Family 17h/19h HD Audio Controller                                     | 479       | 3.84%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 452       | 3.63%   |
| Intel Cannon Lake PCH cAVS                                                 | 347       | 2.78%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 338       | 2.71%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 284       | 2.28%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 280       | 2.25%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 259       | 2.08%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 252       | 2.02%   |
| AMD FCH Azalia Controller                                                  | 244       | 1.96%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 242       | 1.94%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 234       | 1.88%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 230       | 1.85%   |
| AMD Starship/Matisse HD Audio Controller                                   | 229       | 1.84%   |
| Nvidia GP107GL High Definition Audio Controller                            | 191       | 1.53%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 189       | 1.52%   |
| Intel 8 Series HD Audio Controller                                         | 174       | 1.4%    |
| Intel Haswell-ULT HD Audio Controller                                      | 171       | 1.37%   |
| Intel Broadwell-U Audio Controller                                         | 171       | 1.37%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 167       | 1.34%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 166       | 1.33%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 158       | 1.27%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 155       | 1.24%   |
| Intel Comet Lake PCH-LP cAVS                                               | 146       | 1.17%   |
| Intel 200 Series PCH HD Audio                                              | 136       | 1.09%   |
| AMD Kabini HDMI/DP Audio                                                   | 124       | 1%      |
| Nvidia High Definition Audio Controller                                    | 123       | 0.99%   |
| Nvidia GF108 High Definition Audio Controller                              | 119       | 0.95%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 117       | 0.94%   |
| Intel Comet Lake PCH cAVS                                                  | 110       | 0.88%   |
| Nvidia TU106 High Definition Audio Controller                              | 104       | 0.83%   |
| Nvidia GP106 High Definition Audio Controller                              | 101       | 0.81%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 96        | 0.77%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 94        | 0.75%   |
| Intel CM238 HD Audio Controller                                            | 91        | 0.73%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 91        | 0.73%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 90        | 0.72%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 84        | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1233      | 22.03%  |
| SK hynix            | 1109      | 19.81%  |
| Unknown             | 589       | 10.52%  |
| Kingston            | 568       | 10.15%  |
| Micron Technology   | 531       | 9.49%   |
| Corsair             | 391       | 6.98%   |
| Crucial             | 356       | 6.36%   |
| G.Skill             | 260       | 4.64%   |
| Elpida              | 88        | 1.57%   |
| Nanya Technology    | 75        | 1.34%   |
| Ramaxel Technology  | 71        | 1.27%   |
| A-DATA Technology   | 52        | 0.93%   |
| Unknown (ABCD)      | 51        | 0.91%   |
| Transcend           | 29        | 0.52%   |
| Unknown             | 20        | 0.36%   |
| Patriot             | 16        | 0.29%   |
| Team                | 15        | 0.27%   |
| PNY                 | 15        | 0.27%   |
| Unifosa             | 9         | 0.16%   |
| Timetec             | 7         | 0.13%   |
| Qimonda             | 6         | 0.11%   |
| ASint Technology    | 6         | 0.11%   |
| Toshiba             | 5         | 0.09%   |
| Apacer              | 5         | 0.09%   |
| Unknown (0x0C97)    | 4         | 0.07%   |
| TEXTORM             | 4         | 0.07%   |
| Hewlett-Packard     | 4         | 0.07%   |
| V-Color             | 3         | 0.05%   |
| Swissbit            | 3         | 0.05%   |
| Silicon Power       | 3         | 0.05%   |
| SHARETRONIC         | 3         | 0.05%   |
| OCZ                 | 3         | 0.05%   |
| Lexar               | 3         | 0.05%   |
| Innodisk            | 3         | 0.05%   |
| Unknown (F301)      | 2         | 0.04%   |
| Unknown (07FB)      | 2         | 0.04%   |
| Ramos Technology    | 2         | 0.04%   |
| Kllisre             | 2         | 0.04%   |
| KLEVV               | 2         | 0.04%   |
| Goldkey             | 2         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 52        | 0.87%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 51        | 0.85%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 47        | 0.79%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 46        | 0.77%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 45        | 0.75%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 44        | 0.74%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 38        | 0.64%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 37        | 0.62%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 36        | 0.6%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 35        | 0.59%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 34        | 0.57%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 34        | 0.57%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 33        | 0.55%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 33        | 0.55%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 32        | 0.54%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 31        | 0.52%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 31        | 0.52%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 30        | 0.5%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 28        | 0.47%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 28        | 0.47%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 27        | 0.45%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 27        | 0.45%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 27        | 0.45%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 25        | 0.42%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 20        | 0.34%   |
| Unknown                                                          | 20        | 0.34%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s              | 19        | 0.32%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 18        | 0.3%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 17        | 0.28%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 17        | 0.28%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 17        | 0.28%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 16        | 0.27%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 16        | 0.27%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 16        | 0.27%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 16        | 0.27%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 16        | 0.27%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 16        | 0.27%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 16        | 0.27%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 16        | 0.27%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 15        | 0.25%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 2092      | 42.93%  |
| DDR3    | 1788      | 36.69%  |
| DDR2    | 293       | 6.01%   |
| LPDDR4  | 169       | 3.47%   |
| SDRAM   | 168       | 3.45%   |
| Unknown | 147       | 3.02%   |
| LPDDR3  | 111       | 2.28%   |
| DDR     | 55        | 1.13%   |
| LPDDR5  | 20        | 0.41%   |
| DDR5    | 20        | 0.41%   |
| DRAM    | 8         | 0.16%   |
| RAM     | 1         | 0.02%   |
| EEPROM  | 1         | 0.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 2671      | 55.3%   |
| DIMM         | 1828      | 37.85%  |
| Row Of Chips | 296       | 6.13%   |
| Chip         | 17        | 0.35%   |
| FB-DIMM      | 7         | 0.14%   |
| Unknown      | 6         | 0.12%   |
| RIMM         | 5         | 0.1%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 1833      | 34.75%  |
| 4096  | 1654      | 31.36%  |
| 2048  | 775       | 14.69%  |
| 16384 | 634       | 12.02%  |
| 1024  | 244       | 4.63%   |
| 32768 | 90        | 1.71%   |
| 512   | 38        | 0.72%   |
| 65536 | 3         | 0.06%   |
| 256   | 3         | 0.06%   |
| 1     | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 1162      | 22.16%  |
| 2667    | 720       | 13.73%  |
| 3200    | 677       | 12.91%  |
| 1333    | 373       | 7.11%   |
| 2400    | 370       | 7.06%   |
| 2133    | 269       | 5.13%   |
| 1334    | 159       | 3.03%   |
| 667     | 158       | 3.01%   |
| 800     | 144       | 2.75%   |
| 1867    | 107       | 2.04%   |
| 3600    | 102       | 1.95%   |
| Unknown | 96        | 1.83%   |
| 4267    | 77        | 1.47%   |
| 1066    | 77        | 1.47%   |
| 1067    | 63        | 1.2%    |
| 3266    | 52        | 0.99%   |
| 2048    | 41        | 0.78%   |
| 2933    | 39        | 0.74%   |
| 1866    | 39        | 0.74%   |
| 3000    | 38        | 0.72%   |
| 2666    | 37        | 0.71%   |
| 1800    | 30        | 0.57%   |
| 533     | 30        | 0.57%   |
| 4199    | 28        | 0.53%   |
| 3466    | 28        | 0.53%   |
| 4800    | 24        | 0.46%   |
| 3400    | 22        | 0.42%   |
| 6400    | 21        | 0.4%    |
| 3733    | 20        | 0.38%   |
| 400     | 20        | 0.38%   |
| 2800    | 18        | 0.34%   |
| 975     | 16        | 0.31%   |
| 4266    | 13        | 0.25%   |
| 333     | 13        | 0.25%   |
| 2465    | 11        | 0.21%   |
| 1639    | 11        | 0.21%   |
| 3800    | 10        | 0.19%   |
| 2000    | 10        | 0.19%   |
| 8400    | 8         | 0.15%   |
| 3866    | 8         | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 102       | 44.74%  |
| Canon               | 36        | 15.79%  |
| Brother Industries  | 33        | 14.47%  |
| Samsung Electronics | 27        | 11.84%  |
| Seiko Epson         | 17        | 7.46%   |
| Prolific Technology | 3         | 1.32%   |
| STMicroelectronics  | 2         | 0.88%   |
| Ricoh               | 2         | 0.88%   |
| QinHeng Electronics | 2         | 0.88%   |
| Xiaomi              | 1         | 0.44%   |
| Xerox               | 1         | 0.44%   |
| Kyocera             | 1         | 0.44%   |
| Apple               | 1         | 0.44%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Samsung M2070 Series                                      | 9         | 3.93%   |
| HP ENVY 4520 series                                       | 9         | 3.93%   |
| HP DeskJet 3630 series                                    | 9         | 3.93%   |
| HP DeskJet 2700 series                                    | 9         | 3.93%   |
| HP ENVY Photo 6200 series                                 | 6         | 2.62%   |
| Canon PIXMA MG3600 Series                                 | 6         | 2.62%   |
| HP DeskJet Plus 4100 series                               | 4         | 1.75%   |
| HP DeskJet 3700 series                                    | 4         | 1.75%   |
| Brother HL-2030 Laser Printer                             | 4         | 1.75%   |
| Seiko Epson XP-243 245 247 Series                         | 3         | 1.31%   |
| Samsung M2020 Series                                      | 3         | 1.31%   |
| Prolific PL2305 Parallel Port                             | 3         | 1.31%   |
| HP OfficeJet 3830 series                                  | 3         | 1.31%   |
| HP ENVY 5000 series                                       | 3         | 1.31%   |
| HP Deskjet 3050A                                          | 3         | 1.31%   |
| HP DeskJet 2620 All-in-One Printer                        | 3         | 1.31%   |
| Brother Printer                                           | 3         | 1.31%   |
| Brother MFC-L2710DW series                                | 3         | 1.31%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 2         | 0.87%   |
| Seiko Epson XP-255 257 Series                             | 2         | 0.87%   |
| Seiko Epson XP-2100 Series                                | 2         | 0.87%   |
| Seiko Epson WF-2830 Series                                | 2         | 0.87%   |
| Samsung SCX-3400 Series                                   | 2         | 0.87%   |
| Samsung SCX-3200 Series                                   | 2         | 0.87%   |
| Samsung CLX-3180 Series                                   | 2         | 0.87%   |
| Samsung CLX-3170 Series                                   | 2         | 0.87%   |
| QinHeng CH340S                                            | 2         | 0.87%   |
| HP OfficeJet Pro 69                                       | 2         | 0.87%   |
| HP ENVY 5540 series                                       | 2         | 0.87%   |
| HP ENVY 4500 series                                       | 2         | 0.87%   |
| HP DeskJet F4200 series                                   | 2         | 0.87%   |
| HP DeskJet 5550                                           | 2         | 0.87%   |
| HP Deskjet 3070 B611 series                               | 2         | 0.87%   |
| HP Deskjet 1510                                           | 2         | 0.87%   |
| Canon TS5100 series                                       | 2         | 0.87%   |
| Canon PIXMA MP270 All-In-One Printer                      | 2         | 0.87%   |
| Canon PIXMA MG3500 Series                                 | 2         | 0.87%   |
| Canon PIXMA MG2500 Series                                 | 2         | 0.87%   |
| Canon iP7200 series                                       | 2         | 0.87%   |
| Brother MFC-J5335DW                                       | 2         | 0.87%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 48        | 64%     |
| Seiko Epson     | 17        | 22.67%  |
| Hewlett-Packard | 8         | 10.67%  |
| AGFA-Gevaert NV | 2         | 2.67%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30                                 | 9         | 12%     |
| Canon CanoScan N670U/N676U/LiDE 20                            | 8         | 10.67%  |
| Canon CanoScan LIDE 25                                        | 7         | 9.33%   |
| Canon CanoScan LiDE 110                                       | 7         | 9.33%   |
| Seiko Epson GT-X770 [Perfection V500]                         | 4         | 5.33%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                        | 3         | 4%      |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]       | 2         | 2.67%   |
| Seiko Epson GT-9800F [Perfection 3200]                        | 2         | 2.67%   |
| HP ScanJet 3570c                                              | 2         | 2.67%   |
| Canon CanoScan N650U/N656U                                    | 2         | 2.67%   |
| Canon CanoScan LiDE 60                                        | 2         | 2.67%   |
| Canon CanoScan LiDE 220                                       | 2         | 2.67%   |
| Canon CanoScan LiDE 210                                       | 2         | 2.67%   |
| Canon CanoScan LiDE 200                                       | 2         | 2.67%   |
| Seiko Epson Scanner                                           | 1         | 1.33%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                   | 1         | 1.33%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]             | 1         | 1.33%   |
| Seiko Epson GT-F600 [Perfection 4180]                         | 1         | 1.33%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                 | 1         | 1.33%   |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1         | 1.33%   |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO]   | 1         | 1.33%   |
| Seiko Epson GT-7700U [Perfection 1240U]                       | 1         | 1.33%   |
| Seiko Epson GT-6600U [Perfection 610]                         | 1         | 1.33%   |
| HP ScanJet G4010                                              | 1         | 1.33%   |
| HP ScanJet 5200c                                              | 1         | 1.33%   |
| HP ScanJet 4570c                                              | 1         | 1.33%   |
| HP ScanJet 3500c                                              | 1         | 1.33%   |
| HP ScanJet 2300c                                              | 1         | 1.33%   |
| HP PSC 1200                                                   | 1         | 1.33%   |
| Canon CanoScan LiDE 120                                       | 1         | 1.33%   |
| Canon CanoScan 9000F Mark II                                  | 1         | 1.33%   |
| Canon CanoScan 4400F                                          | 1         | 1.33%   |
| Canon CanoScan 4200F                                          | 1         | 1.33%   |
| AGFA-Gevaert NV SnapScan e20                                  | 1         | 1.33%   |
| AGFA-Gevaert NV SnapScan 1212U (?)                            | 1         | 1.33%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 974       | 21.61%  |
| IMC Networks                           | 460       | 10.21%  |
| Microdia                               | 417       | 9.25%   |
| Realtek Semiconductor                  | 381       | 8.45%   |
| Acer                                   | 334       | 7.41%   |
| Logitech                               | 299       | 6.63%   |
| Sunplus Innovation Technology          | 258       | 5.72%   |
| Suyin                                  | 167       | 3.71%   |
| Cheng Uei Precision Industry (Foxlink) | 162       | 3.59%   |
| Quanta                                 | 146       | 3.24%   |
| Apple                                  | 121       | 2.68%   |
| Lite-On Technology                     | 108       | 2.4%    |
| Syntek                                 | 82        | 1.82%   |
| Alcor Micro                            | 54        | 1.2%    |
| Microsoft                              | 49        | 1.09%   |
| Samsung Electronics                    | 48        | 1.07%   |
| Ricoh                                  | 43        | 0.95%   |
| Silicon Motion                         | 42        | 0.93%   |
| Luxvisions Innotech Limited            | 40        | 0.89%   |
| Guillemot                              | 21        | 0.47%   |
| Lenovo                                 | 20        | 0.44%   |
| Sonix Technology                       | 19        | 0.42%   |
| Primax Electronics                     | 18        | 0.4%    |
| Z-Star Microelectronics                | 17        | 0.38%   |
| Importek                               | 14        | 0.31%   |
| GEMBIRD                                | 14        | 0.31%   |
| Creative Technology                    | 14        | 0.31%   |
| DigiTech                               | 13        | 0.29%   |
| Generalplus Technology                 | 12        | 0.27%   |
| ARC International                      | 12        | 0.27%   |
| ALi                                    | 11        | 0.24%   |
| Hewlett-Packard                        | 10        | 0.22%   |
| KYE Systems (Mouse Systems)            | 7         | 0.16%   |
| HD 2MP WEBCAM                          | 7         | 0.16%   |
| OmniVision Technologies                | 6         | 0.13%   |
| Cubeternet                             | 6         | 0.13%   |
| USB Camera                             | 5         | 0.11%   |
| Y Media                                | 4         | 0.09%   |
| Jieli Technology                       | 4         | 0.09%   |
| Intel                                  | 4         | 0.09%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD            | 214       | 4.73%   |
| Realtek Integrated_Webcam_HD             | 174       | 3.84%   |
| Chicony Integrated Camera                | 147       | 3.25%   |
| IMC Networks USB2.0 HD UVC WebCam        | 107       | 2.36%   |
| Chicony HD WebCam                        | 97        | 2.14%   |
| Acer Integrated Camera                   | 91        | 2.01%   |
| IMC Networks Integrated Camera           | 84        | 1.85%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 81        | 1.79%   |
| Logitech Webcam C270                     | 63        | 1.39%   |
| Sunplus Integrated_Webcam_HD             | 62        | 1.37%   |
| Samsung Galaxy A5 (MTP)                  | 48        | 1.06%   |
| Acer HD Webcam                           | 47        | 1.04%   |
| Realtek USB Camera                       | 45        | 0.99%   |
| Chicony USB2.0 VGA UVC WebCam            | 45        | 0.99%   |
| Chicony USB2.0 Camera                    | 43        | 0.95%   |
| Apple Built-in iSight                    | 43        | 0.95%   |
| Chicony USB2.0 HD UVC WebCam             | 40        | 0.88%   |
| Chicony HP HD Camera                     | 40        | 0.88%   |
| Sunplus Asus Webcam                      | 39        | 0.86%   |
| Microdia Integrated Webcam               | 38        | 0.84%   |
| Chicony TOSHIBA Web Camera - HD          | 37        | 0.82%   |
| Apple iPhone5/5C/5S/6                    | 37        | 0.82%   |
| Acer BisonCam,NB Pro                     | 36        | 0.79%   |
| Syntek Integrated Camera                 | 35        | 0.77%   |
| Chicony HP Truevision HD                 | 34        | 0.75%   |
| Chicony HP HD Webcam                     | 34        | 0.75%   |
| Logitech HD Pro Webcam C920              | 33        | 0.73%   |
| Lite-On Integrated Camera                | 33        | 0.73%   |
| Chicony USB 2.0 Camera                   | 32        | 0.71%   |
| Realtek USB2.0 HD UVC WebCam             | 31        | 0.68%   |
| Acer BisonCam, NB Pro                    | 30        | 0.66%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 29        | 0.64%   |
| Chicony HP TrueVision HD Camera          | 29        | 0.64%   |
| Logitech HD Webcam C525                  | 28        | 0.62%   |
| Alcor Micro USB 2.0 Camera               | 27        | 0.6%    |
| Sunplus HD WebCam                        | 25        | 0.55%   |
| Chicony VGA Webcam                       | 25        | 0.55%   |
| Acer Lenovo EasyCamera                   | 25        | 0.55%   |
| Quanta HP HD Camera                      | 24        | 0.53%   |
| Microdia USB 2.0 Camera                  | 24        | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 261       | 34.85%  |
| Synaptics                  | 170       | 22.7%   |
| Shenzhen Goodix Technology | 146       | 19.49%  |
| AuthenTec                  | 57        | 7.61%   |
| Elan Microelectronics      | 43        | 5.74%   |
| LighTuning Technology      | 35        | 4.67%   |
| Upek                       | 27        | 3.6%    |
| STMicroelectronics         | 9         | 1.2%    |
| Focal-systems.Corp         | 1         | 0.13%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 73        | 9.75%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 72        | 9.61%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 63        | 8.41%   |
| Unknown                                                                    | 49        | 6.54%   |
| Shenzhen Goodix FingerPrint                                                | 37        | 4.94%   |
| Shenzhen Goodix Fingerprint Reader                                         | 36        | 4.81%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 32        | 4.27%   |
| Elan ELAN:Fingerprint                                                      | 32        | 4.27%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 29        | 3.87%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 23        | 3.07%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 21        | 2.8%    |
| Validity Sensors VFS491                                                    | 20        | 2.67%   |
| AuthenTec AES2810                                                          | 20        | 2.67%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 17        | 2.27%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 16        | 2.14%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 16        | 2.14%   |
| Validity Sensors Fingerprint scanner                                       | 16        | 2.14%   |
| AuthenTec AES1600                                                          | 13        | 1.74%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 12        | 1.6%    |
| Validity Sensors Synaptics WBDI                                            | 12        | 1.6%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 12        | 1.6%    |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 12        | 1.6%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 11        | 1.47%   |
| AuthenTec Fingerprint Sensor                                               | 11        | 1.47%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 10        | 1.34%   |
| STMicroelectronics Fingerprint Reader                                      | 9         | 1.2%    |
| Elan ELAN:ARM-M4                                                           | 9         | 1.2%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 9         | 1.2%    |
| Synaptics  WBDI                                                            | 8         | 1.07%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 8         | 1.07%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 0.67%   |
| Validity Sensors VFS Fingerprint sensor                                    | 5         | 0.67%   |
| Synaptics WBDI Device                                                      | 5         | 0.67%   |
| Upek TCS5B Fingerprint sensor                                              | 4         | 0.53%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 3         | 0.4%    |
| Validity Sensors VFS300 Fingerprint Reader                                 | 3         | 0.4%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 0.4%    |
| AuthenTec AES1660 Fingerprint Sensor                                       | 3         | 0.4%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 0.27%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 0.27%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 203       | 53.14%  |
| Alcor Micro               | 79        | 20.68%  |
| O2 Micro                  | 32        | 8.38%   |
| Upek                      | 15        | 3.93%   |
| Lenovo                    | 12        | 3.14%   |
| Hewlett-Packard           | 9         | 2.36%   |
| Gemalto (was Gemplus)     | 9         | 2.36%   |
| Aladdin Knowledge Systems | 4         | 1.05%   |
| Yubico.com                | 3         | 0.79%   |
| Clay Logic                | 3         | 0.79%   |
| Chicony Electronics       | 3         | 0.79%   |
| SCM Microsystems          | 2         | 0.52%   |
| Feitian Technologies      | 2         | 0.52%   |
| ST-Ericsson               | 1         | 0.26%   |
| SpringCard                | 1         | 0.26%   |
| Realtek Semiconductor     | 1         | 0.26%   |
| OmniKey                   | 1         | 0.26%   |
| Cherry                    | 1         | 0.26%   |
| Advanced Card Systems     | 1         | 0.26%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 78        | 20.42%  |
| Broadcom BCM5880 Secure Applications Processor                               | 69        | 18.06%  |
| Broadcom 58200                                                               | 58        | 15.18%  |
| Broadcom 5880                                                                | 43        | 11.26%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 32        | 8.38%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 29        | 7.59%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 15        | 3.93%   |
| Lenovo Integrated Smart Card Reader                                          | 12        | 3.14%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 9         | 2.36%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 6         | 1.57%   |
| Aladdin Knowledge Systems Token JC                                           | 4         | 1.05%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 3         | 0.79%   |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 0.79%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 3         | 0.79%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 2         | 0.52%   |
| Clay Logic Nitrokey Pro                                                      | 2         | 0.52%   |
| ST-Ericsson Chipcard Reader                                                  | 1         | 0.26%   |
| SpringCard Two                                                               | 1         | 0.26%   |
| SCM Microsystems SCR335 SmartCard Reader                                     | 1         | 0.26%   |
| SCM Microsystems CLOUD 2700 F Smart Card Reader                              | 1         | 0.26%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.26%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.26%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.26%   |
| Feitian Technologies U2F CCID KB                                             | 1         | 0.26%   |
| Feitian Technologies FT SCR310                                               | 1         | 0.26%   |
| Clay Logic Nitrokey Start                                                    | 1         | 0.26%   |
| Cherry Cherry GmbH CHERRY SECURE BOARD 1.0                                   | 1         | 0.26%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.26%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.26%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.26%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 5579      | 71.52%  |
| 1     | 1761      | 22.57%  |
| 2     | 360       | 4.61%   |
| 3     | 67        | 0.86%   |
| 4     | 19        | 0.24%   |
| 5     | 7         | 0.09%   |
| 6     | 3         | 0.04%   |
| 8     | 2         | 0.03%   |
| 7     | 2         | 0.03%   |
| 9     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 739       | 27.39%  |
| Graphics card            | 636       | 23.57%  |
| Chipcard                 | 346       | 12.82%  |
| Net/wireless             | 287       | 10.64%  |
| Multimedia controller    | 128       | 4.74%   |
| Communication controller | 114       | 4.23%   |
| Camera                   | 90        | 3.34%   |
| Bluetooth                | 75        | 2.78%   |
| Unassigned class         | 62        | 2.3%    |
| Storage                  | 48        | 1.78%   |
| Sound                    | 43        | 1.59%   |
| Card reader              | 39        | 1.45%   |
| Net/ethernet             | 27        | 1%      |
| Modem                    | 20        | 0.74%   |
| Network                  | 13        | 0.48%   |
| Storage/raid             | 7         | 0.26%   |
| Firewire controller      | 6         | 0.22%   |
| Dvb card                 | 4         | 0.15%   |
| Storage/ide              | 3         | 0.11%   |
| Flash memory             | 3         | 0.11%   |
| Wireless                 | 2         | 0.07%   |
| Unclassified device      | 2         | 0.07%   |
| Tv card                  | 2         | 0.07%   |
| Storage/nvme             | 1         | 0.04%   |
| Storage/ata              | 1         | 0.04%   |

