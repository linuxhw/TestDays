Linux in Mexico - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Mexico.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Mexico/Desktop/README.md) and [notebooks](/Location/Mexico/Notebook/README.md).

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

Total: 3820

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Toshiba       | Satellite L735              | Notebook    | [c969a72669](https://linux-hardware.org/?probe=c969a72669) | Oct 01, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [4fa536be5c](https://linux-hardware.org/?probe=4fa536be5c) | Oct 01, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [efc04e4b27](https://linux-hardware.org/?probe=efc04e4b27) | Oct 01, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [d17d6d2b70](https://linux-hardware.org/?probe=d17d6d2b70) | Oct 01, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [7eebcdc80b](https://linux-hardware.org/?probe=7eebcdc80b) | Oct 01, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [bee067d5dd](https://linux-hardware.org/?probe=bee067d5dd) | Sep 30, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [3d40d7878a](https://linux-hardware.org/?probe=3d40d7878a) | Sep 30, 2023 |
| Sony          | VPCEG10EL                   | Notebook    | [8271942cc2](https://linux-hardware.org/?probe=8271942cc2) | Sep 30, 2023 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [6f19668c91](https://linux-hardware.org/?probe=6f19668c91) | Sep 29, 2023 |
| Pegatron      | Benicia                     | Desktop     | [840b02e356](https://linux-hardware.org/?probe=840b02e356) | Sep 29, 2023 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [da030ed703](https://linux-hardware.org/?probe=da030ed703) | Sep 28, 2023 |
| ASUSTek       | Z97-A-USB31                 | Desktop     | [b7e5fb069c](https://linux-hardware.org/?probe=b7e5fb069c) | Sep 28, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [797275028d](https://linux-hardware.org/?probe=797275028d) | Sep 28, 2023 |
| Acer          | Aspire E1-531               | Notebook    | [6b981869d7](https://linux-hardware.org/?probe=6b981869d7) | Sep 27, 2023 |
| Sony          | VPCEG10EL                   | Notebook    | [7bfbe9b21d](https://linux-hardware.org/?probe=7bfbe9b21d) | Sep 27, 2023 |
| Acer          | Aspire E1-531               | Notebook    | [d47b59c89b](https://linux-hardware.org/?probe=d47b59c89b) | Sep 27, 2023 |
| Toshiba       | dynabook T350/46BW          | Notebook    | [26ffaa1c0f](https://linux-hardware.org/?probe=26ffaa1c0f) | Sep 27, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [0ba9157463](https://linux-hardware.org/?probe=0ba9157463) | Sep 27, 2023 |
| HP            | Pavilion 14                 | Notebook    | [a7589d8c93](https://linux-hardware.org/?probe=a7589d8c93) | Sep 26, 2023 |
| HP            | Pavilion 14                 | Notebook    | [1aed6aba04](https://linux-hardware.org/?probe=1aed6aba04) | Sep 26, 2023 |
| Lenovo        | ThinkPad T460 20FMS0RN1S    | Notebook    | [598d621f0d](https://linux-hardware.org/?probe=598d621f0d) | Sep 26, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [897f671915](https://linux-hardware.org/?probe=897f671915) | Sep 25, 2023 |
| Dell          | Latitude E5470              | Notebook    | [64c20e3e21](https://linux-hardware.org/?probe=64c20e3e21) | Sep 25, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [2af47d0dca](https://linux-hardware.org/?probe=2af47d0dca) | Sep 24, 2023 |
| GPU Compan... | GWNR71517                   | Notebook    | [93b975d65b](https://linux-hardware.org/?probe=93b975d65b) | Sep 24, 2023 |
| Lenovo        | ThinkPad T440 20B6006DUS    | Notebook    | [4428a91f65](https://linux-hardware.org/?probe=4428a91f65) | Sep 23, 2023 |
| Lenovo        | ThinkPad P17 Gen 1 20SQS... | Notebook    | [05bf70d208](https://linux-hardware.org/?probe=05bf70d208) | Sep 22, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [312172129f](https://linux-hardware.org/?probe=312172129f) | Sep 22, 2023 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [3a965cb7e3](https://linux-hardware.org/?probe=3a965cb7e3) | Sep 22, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [90c9ffe2e0](https://linux-hardware.org/?probe=90c9ffe2e0) | Sep 22, 2023 |
| Dell          | Inspiron 1464               | Notebook    | [026e1e3391](https://linux-hardware.org/?probe=026e1e3391) | Sep 21, 2023 |
| Valve         | Jupiter                     | Notebook    | [2b2966eb3d](https://linux-hardware.org/?probe=2b2966eb3d) | Sep 21, 2023 |
| Dell          | Inspiron 1464               | Notebook    | [bdb084e4a8](https://linux-hardware.org/?probe=bdb084e4a8) | Sep 20, 2023 |
| Lenovo        | ThinkPad L420 78564ES       | Notebook    | [a6f3af802d](https://linux-hardware.org/?probe=a6f3af802d) | Sep 20, 2023 |
| ASRock        | H55M-LE                     | Desktop     | [6b7e52fd8c](https://linux-hardware.org/?probe=6b7e52fd8c) | Sep 20, 2023 |
| ASRock        | H55M-LE                     | Desktop     | [ceefe742e2](https://linux-hardware.org/?probe=ceefe742e2) | Sep 20, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [43edd5f49f](https://linux-hardware.org/?probe=43edd5f49f) | Sep 20, 2023 |
| ASUSTek       | X453MA                      | Notebook    | [8eacbd2f7a](https://linux-hardware.org/?probe=8eacbd2f7a) | Sep 19, 2023 |
| HP            | ProBook 6475b               | Notebook    | [43c4870e11](https://linux-hardware.org/?probe=43c4870e11) | Sep 19, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [9d59b2b43d](https://linux-hardware.org/?probe=9d59b2b43d) | Sep 19, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [f40bb3790e](https://linux-hardware.org/?probe=f40bb3790e) | Sep 18, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [0a5f29963e](https://linux-hardware.org/?probe=0a5f29963e) | Sep 18, 2023 |
| HP            | Dragonfly Pro               | Notebook    | [0c5d439504](https://linux-hardware.org/?probe=0c5d439504) | Sep 18, 2023 |
| Gigabyte      | Z270-Gaming 3               | Desktop     | [9e795a05f1](https://linux-hardware.org/?probe=9e795a05f1) | Sep 18, 2023 |
| ECS           | VX900-I                     | Desktop     | [0a69c91f6b](https://linux-hardware.org/?probe=0a69c91f6b) | Sep 17, 2023 |
| Dell          | Inspiron 1464               | Notebook    | [9830a0345b](https://linux-hardware.org/?probe=9830a0345b) | Sep 17, 2023 |
| Fanless Mi... | Rev JSL62                   | Mini pc     | [adbe2f1ead](https://linux-hardware.org/?probe=adbe2f1ead) | Sep 17, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [a53b964a47](https://linux-hardware.org/?probe=a53b964a47) | Sep 17, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [648af5d937](https://linux-hardware.org/?probe=648af5d937) | Sep 17, 2023 |
| Dell          | Inspiron 5505               | Notebook    | [cf501dc9f9](https://linux-hardware.org/?probe=cf501dc9f9) | Sep 16, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [c3791ba730](https://linux-hardware.org/?probe=c3791ba730) | Sep 16, 2023 |
| Dell          | Latitude 9330               | Convertible | [622af30925](https://linux-hardware.org/?probe=622af30925) | Sep 16, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b4dcc89eae](https://linux-hardware.org/?probe=b4dcc89eae) | Sep 15, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [c424e240c8](https://linux-hardware.org/?probe=c424e240c8) | Sep 15, 2023 |
| Gigabyte      | A55M-DS2                    | Desktop     | [6bc7d0b74c](https://linux-hardware.org/?probe=6bc7d0b74c) | Sep 15, 2023 |
| A-DATA Tec... | XENIAXe15TI5G11GXELX        | Notebook    | [6c2fdbd791](https://linux-hardware.org/?probe=6c2fdbd791) | Sep 14, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [361c6cb056](https://linux-hardware.org/?probe=361c6cb056) | Sep 14, 2023 |
| Toshiba       | Satellite L735              | Notebook    | [fee724f874](https://linux-hardware.org/?probe=fee724f874) | Sep 14, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [28116ad85d](https://linux-hardware.org/?probe=28116ad85d) | Sep 13, 2023 |
| ASUSTek       | Leonite2                    | Desktop     | [6e387e015f](https://linux-hardware.org/?probe=6e387e015f) | Sep 13, 2023 |
| Dell          | Inspiron 5537               | Notebook    | [4ff9edf944](https://linux-hardware.org/?probe=4ff9edf944) | Sep 12, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [26b3fd07ae](https://linux-hardware.org/?probe=26b3fd07ae) | Sep 12, 2023 |
| HUAWEI        | NBM-WXX9                    | Notebook    | [74914c875f](https://linux-hardware.org/?probe=74914c875f) | Sep 12, 2023 |
| Dell          | Precision 7520              | Notebook    | [803e67f286](https://linux-hardware.org/?probe=803e67f286) | Sep 12, 2023 |
| Dell          | 05XGC8 A01                  | Desktop     | [c09c04e44a](https://linux-hardware.org/?probe=c09c04e44a) | Sep 12, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [92762d264f](https://linux-hardware.org/?probe=92762d264f) | Sep 11, 2023 |
| ASUSTek       | X541UA                      | Notebook    | [a8184365b8](https://linux-hardware.org/?probe=a8184365b8) | Sep 10, 2023 |
| Dell          | 0782GW A00                  | Desktop     | [e763eb02b7](https://linux-hardware.org/?probe=e763eb02b7) | Sep 10, 2023 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [8c5abbf5a2](https://linux-hardware.org/?probe=8c5abbf5a2) | Sep 10, 2023 |
| Intel         | DX58SO AAE29331-501         | Desktop     | [26d87ed353](https://linux-hardware.org/?probe=26d87ed353) | Sep 09, 2023 |
| ASUSTek       | G750JW                      | Notebook    | [2e81baa143](https://linux-hardware.org/?probe=2e81baa143) | Sep 09, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [178d6df21a](https://linux-hardware.org/?probe=178d6df21a) | Sep 08, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [c5f5d76ac5](https://linux-hardware.org/?probe=c5f5d76ac5) | Sep 08, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [8a48280ff2](https://linux-hardware.org/?probe=8a48280ff2) | Sep 08, 2023 |
| Unknown       | W1415A                      | Notebook    | [67fc8d5ea8](https://linux-hardware.org/?probe=67fc8d5ea8) | Sep 08, 2023 |
| Google        | Pirika                      | Notebook    | [fc27e22f1c](https://linux-hardware.org/?probe=fc27e22f1c) | Sep 08, 2023 |
| Acer          | Predator PH315-51           | Notebook    | [89e33145c3](https://linux-hardware.org/?probe=89e33145c3) | Sep 08, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [7bdd695dc3](https://linux-hardware.org/?probe=7bdd695dc3) | Sep 07, 2023 |
| Dell          | Latitude 5480               | Notebook    | [166d57f310](https://linux-hardware.org/?probe=166d57f310) | Sep 07, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b982251e82](https://linux-hardware.org/?probe=b982251e82) | Sep 07, 2023 |
| Dell          | Latitude E5450              | Notebook    | [a705913b6e](https://linux-hardware.org/?probe=a705913b6e) | Sep 07, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a5506bdc30](https://linux-hardware.org/?probe=a5506bdc30) | Sep 07, 2023 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [d9509a0fa0](https://linux-hardware.org/?probe=d9509a0fa0) | Sep 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [c4829899c3](https://linux-hardware.org/?probe=c4829899c3) | Sep 06, 2023 |
| Apple         | MacBookPro13,1              | Notebook    | [54f48be7f6](https://linux-hardware.org/?probe=54f48be7f6) | Sep 06, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [ce6860153d](https://linux-hardware.org/?probe=ce6860153d) | Sep 06, 2023 |
| Google        | Pirika                      | Notebook    | [e05149e1de](https://linux-hardware.org/?probe=e05149e1de) | Sep 06, 2023 |
| Acer          | Aspire E1-531               | Notebook    | [9d5880bc6c](https://linux-hardware.org/?probe=9d5880bc6c) | Sep 06, 2023 |
| Acer          | Aspire E1-531               | Notebook    | [6ffc334cf9](https://linux-hardware.org/?probe=6ffc334cf9) | Sep 06, 2023 |
| Apple         | MacBookPro13,1              | Notebook    | [d6b6455af2](https://linux-hardware.org/?probe=d6b6455af2) | Sep 06, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [3c55d4d55b](https://linux-hardware.org/?probe=3c55d4d55b) | Sep 05, 2023 |
| Acer          | Aspire V3-572P              | Notebook    | [1b021435e8](https://linux-hardware.org/?probe=1b021435e8) | Sep 05, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [ab9c556dc7](https://linux-hardware.org/?probe=ab9c556dc7) | Sep 05, 2023 |
| Dell          | 0Y2MRG A00                  | Desktop     | [893bd8a261](https://linux-hardware.org/?probe=893bd8a261) | Sep 04, 2023 |
| Acer          | Aspire E1-531               | Notebook    | [7f9460a97c](https://linux-hardware.org/?probe=7f9460a97c) | Sep 04, 2023 |
| Dell          | 0GWHMW A00                  | Desktop     | [b02b2cb5f0](https://linux-hardware.org/?probe=b02b2cb5f0) | Sep 04, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [b7d2eae326](https://linux-hardware.org/?probe=b7d2eae326) | Sep 04, 2023 |
| Chuwi         | GemiBook XPro               | Notebook    | [acf39c0e3f](https://linux-hardware.org/?probe=acf39c0e3f) | Sep 04, 2023 |
| Lenovo        | ThinkPad T400 64758S4       | Notebook    | [efcb0a82e1](https://linux-hardware.org/?probe=efcb0a82e1) | Sep 04, 2023 |
| ASUSTek       | PRIME B550M-A AC            | Desktop     | [6ca26976b6](https://linux-hardware.org/?probe=6ca26976b6) | Sep 04, 2023 |
| HP            | 240 G3                      | Notebook    | [24381b91f7](https://linux-hardware.org/?probe=24381b91f7) | Sep 03, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [6b895a5320](https://linux-hardware.org/?probe=6b895a5320) | Sep 03, 2023 |
| Valve         | Jupiter                     | Notebook    | [9e037b28bc](https://linux-hardware.org/?probe=9e037b28bc) | Sep 03, 2023 |
| eMachines     | EL1852G                     | Desktop     | [e9234028f1](https://linux-hardware.org/?probe=e9234028f1) | Sep 03, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [e05acf231c](https://linux-hardware.org/?probe=e05acf231c) | Sep 03, 2023 |
| Biostar       | A10N-9630E                  | Desktop     | [823a9c1693](https://linux-hardware.org/?probe=823a9c1693) | Sep 03, 2023 |
| ASUSTek       | X540NA                      | Notebook    | [69ccd7d6f2](https://linux-hardware.org/?probe=69ccd7d6f2) | Sep 02, 2023 |
| Intel         | S2600CP G50768-512          | Server      | [f05f130786](https://linux-hardware.org/?probe=f05f130786) | Sep 02, 2023 |
| Lenovo        | ThinkPad L570 20J9S07N00    | Notebook    | [88d1350771](https://linux-hardware.org/?probe=88d1350771) | Sep 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [de36e26c21](https://linux-hardware.org/?probe=de36e26c21) | Sep 01, 2023 |
| Lenovo        | ThinkPad L570 20J9S07N00    | Notebook    | [fe660fb390](https://linux-hardware.org/?probe=fe660fb390) | Sep 01, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | Notebook    | [5db10955f8](https://linux-hardware.org/?probe=5db10955f8) | Sep 01, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [57ecd81ed7](https://linux-hardware.org/?probe=57ecd81ed7) | Aug 31, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [ffa39e6acd](https://linux-hardware.org/?probe=ffa39e6acd) | Aug 31, 2023 |
| HP            | 2215                        | Desktop     | [3b3b45d0ce](https://linux-hardware.org/?probe=3b3b45d0ce) | Aug 31, 2023 |
| HP            | 1587h                       | Desktop     | [fe659d3db6](https://linux-hardware.org/?probe=fe659d3db6) | Aug 31, 2023 |
| MSI           | Boston                      | Desktop     | [f43cd6df24](https://linux-hardware.org/?probe=f43cd6df24) | Aug 31, 2023 |
| HP            | ProBook 6460b               | Notebook    | [18deeb6be6](https://linux-hardware.org/?probe=18deeb6be6) | Aug 30, 2023 |
| Dell          | Inspiron 1464               | Notebook    | [1020c99eec](https://linux-hardware.org/?probe=1020c99eec) | Aug 30, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [84f61e2225](https://linux-hardware.org/?probe=84f61e2225) | Aug 30, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [3032b93bc8](https://linux-hardware.org/?probe=3032b93bc8) | Aug 30, 2023 |
| Lenovo        | Yoga 720-13IKB 80X6         | Convertible | [e38546c509](https://linux-hardware.org/?probe=e38546c509) | Aug 30, 2023 |
| Dell          | 0D28YY A00                  | Desktop     | [9f2585c0aa](https://linux-hardware.org/?probe=9f2585c0aa) | Aug 29, 2023 |
| Dell          | Inspiron 20 Model 3043      | All in one  | [f44b99ca67](https://linux-hardware.org/?probe=f44b99ca67) | Aug 29, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [863b7d7901](https://linux-hardware.org/?probe=863b7d7901) | Aug 29, 2023 |
| Intel         | S2600CP G50768-512          | Server      | [eba7f74017](https://linux-hardware.org/?probe=eba7f74017) | Aug 29, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [c3065668c8](https://linux-hardware.org/?probe=c3065668c8) | Aug 29, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [3c4c019ee5](https://linux-hardware.org/?probe=3c4c019ee5) | Aug 28, 2023 |
| Google        | Treeya                      | Notebook    | [396f71a402](https://linux-hardware.org/?probe=396f71a402) | Aug 28, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [cc89933ff1](https://linux-hardware.org/?probe=cc89933ff1) | Aug 28, 2023 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [bdd515fe27](https://linux-hardware.org/?probe=bdd515fe27) | Aug 28, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [89044ad89b](https://linux-hardware.org/?probe=89044ad89b) | Aug 28, 2023 |
| Unknown       | V00                         | Mini pc     | [b63adaac28](https://linux-hardware.org/?probe=b63adaac28) | Aug 27, 2023 |
| Dell          | 0HR330                      | Desktop     | [700643ac0e](https://linux-hardware.org/?probe=700643ac0e) | Aug 27, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [f8a316e74c](https://linux-hardware.org/?probe=f8a316e74c) | Aug 27, 2023 |
| Acer          | Aspire V5-471P              | Notebook    | [fcbacf6769](https://linux-hardware.org/?probe=fcbacf6769) | Aug 26, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [2bbc495ee5](https://linux-hardware.org/?probe=2bbc495ee5) | Aug 25, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [270cd028cf](https://linux-hardware.org/?probe=270cd028cf) | Aug 25, 2023 |
| Dell          | 0M017G A00                  | Desktop     | [f5e52dc9f9](https://linux-hardware.org/?probe=f5e52dc9f9) | Aug 24, 2023 |
| Dell          | G15 5510                    | Notebook    | [f9e857e751](https://linux-hardware.org/?probe=f9e857e751) | Aug 24, 2023 |
| Gateway       | ZX4800                      | All in one  | [8d9b55b788](https://linux-hardware.org/?probe=8d9b55b788) | Aug 24, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [3898bac5d4](https://linux-hardware.org/?probe=3898bac5d4) | Aug 24, 2023 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [62a1cc3d3b](https://linux-hardware.org/?probe=62a1cc3d3b) | Aug 23, 2023 |
| Gateway       | ZX4800                      | All in one  | [ca5095843f](https://linux-hardware.org/?probe=ca5095843f) | Aug 23, 2023 |
| Google        | Pirika                      | Notebook    | [f0937aba65](https://linux-hardware.org/?probe=f0937aba65) | Aug 23, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [69d3db7d28](https://linux-hardware.org/?probe=69d3db7d28) | Aug 23, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [523acf034e](https://linux-hardware.org/?probe=523acf034e) | Aug 23, 2023 |
| Unknown       | Unknown                     | Notebook    | [176f1e45e9](https://linux-hardware.org/?probe=176f1e45e9) | Aug 22, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | Notebook    | [3e831762f2](https://linux-hardware.org/?probe=3e831762f2) | Aug 22, 2023 |
| Dell          | Latitude E6430              | Notebook    | [8125ef4bf1](https://linux-hardware.org/?probe=8125ef4bf1) | Aug 22, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [d63bd363bc](https://linux-hardware.org/?probe=d63bd363bc) | Aug 22, 2023 |
| Acer          | Aspire E1-531               | Notebook    | [ca5348bd31](https://linux-hardware.org/?probe=ca5348bd31) | Aug 22, 2023 |
| GMKtec        | NucBox K2                   | Desktop     | [3cc85b0145](https://linux-hardware.org/?probe=3cc85b0145) | Aug 22, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [55e95b21f1](https://linux-hardware.org/?probe=55e95b21f1) | Aug 22, 2023 |
| Lenovo        | ThinkPad T530 23945ZS       | Notebook    | [07f7243392](https://linux-hardware.org/?probe=07f7243392) | Aug 21, 2023 |
| HP            | 18E7                        | Desktop     | [49957c261d](https://linux-hardware.org/?probe=49957c261d) | Aug 21, 2023 |
| Dell          | Latitude E6430              | Notebook    | [839ae55173](https://linux-hardware.org/?probe=839ae55173) | Aug 21, 2023 |
| Dell          | Latitude E7440              | Notebook    | [edae1bc7d3](https://linux-hardware.org/?probe=edae1bc7d3) | Aug 21, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [ca9423253c](https://linux-hardware.org/?probe=ca9423253c) | Aug 21, 2023 |
| Gigabyte      | MZGLKCP-00                  | Desktop     | [c6f294e543](https://linux-hardware.org/?probe=c6f294e543) | Aug 21, 2023 |
| Gigabyte      | MZGLKCP-00                  | Desktop     | [d6e0b89f34](https://linux-hardware.org/?probe=d6e0b89f34) | Aug 21, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [277050ce29](https://linux-hardware.org/?probe=277050ce29) | Aug 20, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [3c24c755d6](https://linux-hardware.org/?probe=3c24c755d6) | Aug 20, 2023 |
| Lenovo        | Win8 Pro DPK TPG            | Desktop     | [455882ed8d](https://linux-hardware.org/?probe=455882ed8d) | Aug 20, 2023 |
| Dell          | Latitude E6430              | Notebook    | [4fc5a7442a](https://linux-hardware.org/?probe=4fc5a7442a) | Aug 20, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [54c2ded452](https://linux-hardware.org/?probe=54c2ded452) | Aug 19, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [68df495196](https://linux-hardware.org/?probe=68df495196) | Aug 19, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [c3d45a0b50](https://linux-hardware.org/?probe=c3d45a0b50) | Aug 18, 2023 |
| Dell          | 0M017G A00                  | Desktop     | [d480387600](https://linux-hardware.org/?probe=d480387600) | Aug 18, 2023 |
| Dell          | 0YJMC0 A02                  | Desktop     | [f4818214d5](https://linux-hardware.org/?probe=f4818214d5) | Aug 18, 2023 |
| Lenovo        | Rev B 82KU                  | Notebook    | [114345f952](https://linux-hardware.org/?probe=114345f952) | Aug 18, 2023 |
| Lenovo        | S10-3                       | Notebook    | [d1c8fb66ec](https://linux-hardware.org/?probe=d1c8fb66ec) | Aug 18, 2023 |
| Lenovo        | G40-30 80FY                 | Notebook    | [6574b3e96d](https://linux-hardware.org/?probe=6574b3e96d) | Aug 16, 2023 |
| ASUSTek       | Leonite2                    | Desktop     | [439a4ee1fb](https://linux-hardware.org/?probe=439a4ee1fb) | Aug 15, 2023 |
| Dell          | Latitude D630               | Notebook    | [878b00d959](https://linux-hardware.org/?probe=878b00d959) | Aug 15, 2023 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [de166e8654](https://linux-hardware.org/?probe=de166e8654) | Aug 15, 2023 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [b2f8b7afb0](https://linux-hardware.org/?probe=b2f8b7afb0) | Aug 15, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [876d7e9992](https://linux-hardware.org/?probe=876d7e9992) | Aug 15, 2023 |
| Gigabyte      | AX370-Gaming 5              | Desktop     | [0bd04d6cc0](https://linux-hardware.org/?probe=0bd04d6cc0) | Aug 15, 2023 |
| AMI           | INTEL                       | Convertible | [21596eaf06](https://linux-hardware.org/?probe=21596eaf06) | Aug 14, 2023 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | Desktop     | [da00873a9d](https://linux-hardware.org/?probe=da00873a9d) | Aug 14, 2023 |
| Dell          | Inspiron 3505               | Notebook    | [53717914de](https://linux-hardware.org/?probe=53717914de) | Aug 14, 2023 |
| Gigabyte      | G41MT-S2                    | Desktop     | [da23ffa8ca](https://linux-hardware.org/?probe=da23ffa8ca) | Aug 13, 2023 |
| ASRock        | H55M-LE                     | Desktop     | [3751d5807e](https://linux-hardware.org/?probe=3751d5807e) | Aug 12, 2023 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [4fe6eb4d59](https://linux-hardware.org/?probe=4fe6eb4d59) | Aug 12, 2023 |
| HP            | 0A04h                       | Desktop     | [61b0d9bc15](https://linux-hardware.org/?probe=61b0d9bc15) | Aug 12, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [4d26902a65](https://linux-hardware.org/?probe=4d26902a65) | Aug 12, 2023 |
| Valve         | Jupiter                     | Notebook    | [069bfd618c](https://linux-hardware.org/?probe=069bfd618c) | Aug 11, 2023 |
| Lenovo        | IdeaCentre B320             | Desktop     | [175fb6f041](https://linux-hardware.org/?probe=175fb6f041) | Aug 11, 2023 |
| Biostar       | A10N-8800E                  | Desktop     | [5ccf8e7d00](https://linux-hardware.org/?probe=5ccf8e7d00) | Aug 11, 2023 |
| Lenovo        | G40-45 80E1                 | Notebook    | [d6f18c79f6](https://linux-hardware.org/?probe=d6f18c79f6) | Aug 10, 2023 |
| Dell          | 0MGK50 A01                  | Desktop     | [ac0ed4109e](https://linux-hardware.org/?probe=ac0ed4109e) | Aug 10, 2023 |
| Toshiba       | Satellite L745D             | Notebook    | [9576dab2b0](https://linux-hardware.org/?probe=9576dab2b0) | Aug 09, 2023 |
| Lenovo        | 30C1                        | Desktop     | [dda7ed4e8b](https://linux-hardware.org/?probe=dda7ed4e8b) | Aug 09, 2023 |
| Dell          | Precision 3551              | Notebook    | [a9b776ade0](https://linux-hardware.org/?probe=a9b776ade0) | Aug 09, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [6047747c8f](https://linux-hardware.org/?probe=6047747c8f) | Aug 09, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [8a11b56d79](https://linux-hardware.org/?probe=8a11b56d79) | Aug 09, 2023 |
| ASUSTek       | X455LA                      | Notebook    | [8b60fb0411](https://linux-hardware.org/?probe=8b60fb0411) | Aug 08, 2023 |
| Lenovo        | Y720-15IKB 80VR             | Notebook    | [7a088aea04](https://linux-hardware.org/?probe=7a088aea04) | Aug 08, 2023 |
| MSI           | B350 GAMING PLUS            | Desktop     | [951597859a](https://linux-hardware.org/?probe=951597859a) | Aug 08, 2023 |
| GPU Compan... | GWNR71517                   | Notebook    | [3fea8d650e](https://linux-hardware.org/?probe=3fea8d650e) | Aug 08, 2023 |
| ASUSTek       | N550LF                      | Notebook    | [57f7da9570](https://linux-hardware.org/?probe=57f7da9570) | Aug 08, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [72bb72d2aa](https://linux-hardware.org/?probe=72bb72d2aa) | Aug 08, 2023 |
| System76      | Oryx Pro                    | Notebook    | [c5b97761d3](https://linux-hardware.org/?probe=c5b97761d3) | Aug 07, 2023 |
| HUAWEI        | WRTD-WXX9                   | Notebook    | [dc02eefe63](https://linux-hardware.org/?probe=dc02eefe63) | Aug 06, 2023 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | Desktop     | [f670b492a9](https://linux-hardware.org/?probe=f670b492a9) | Aug 06, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [0c8aef568d](https://linux-hardware.org/?probe=0c8aef568d) | Aug 06, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [597f8ddaf2](https://linux-hardware.org/?probe=597f8ddaf2) | Aug 06, 2023 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [8618a7051f](https://linux-hardware.org/?probe=8618a7051f) | Aug 06, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | Notebook    | [8b6db0bfbb](https://linux-hardware.org/?probe=8b6db0bfbb) | Aug 05, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [32f8bbeff7](https://linux-hardware.org/?probe=32f8bbeff7) | Aug 05, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [ab9328165e](https://linux-hardware.org/?probe=ab9328165e) | Aug 05, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [9f813efccc](https://linux-hardware.org/?probe=9f813efccc) | Aug 05, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [349326315f](https://linux-hardware.org/?probe=349326315f) | Aug 05, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [d2d45c853b](https://linux-hardware.org/?probe=d2d45c853b) | Aug 05, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [f18b2ff744](https://linux-hardware.org/?probe=f18b2ff744) | Aug 05, 2023 |
| Gigabyte      | GA-MA69VM-S2                | Desktop     | [197a9b0139](https://linux-hardware.org/?probe=197a9b0139) | Aug 03, 2023 |
| INET          | Z12B                        | Mini pc     | [6acbb961c7](https://linux-hardware.org/?probe=6acbb961c7) | Aug 03, 2023 |
| Dell          | Latitude 5490               | Notebook    | [e93c786075](https://linux-hardware.org/?probe=e93c786075) | Aug 03, 2023 |
| Dell          | Latitude E6440              | Notebook    | [c00884f2cd](https://linux-hardware.org/?probe=c00884f2cd) | Aug 03, 2023 |
| Microsoft     | Surface Pro 7+              | Tablet      | [1a39b68c7f](https://linux-hardware.org/?probe=1a39b68c7f) | Aug 03, 2023 |
| Lenovo        | ThinkPad T450 20BU000QLM    | Notebook    | [610fdfd850](https://linux-hardware.org/?probe=610fdfd850) | Aug 03, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [451bfcf27d](https://linux-hardware.org/?probe=451bfcf27d) | Aug 02, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [cfce53f1a3](https://linux-hardware.org/?probe=cfce53f1a3) | Aug 02, 2023 |
| HUAWEI        | WRTD-WXX9                   | Notebook    | [18396303b8](https://linux-hardware.org/?probe=18396303b8) | Aug 02, 2023 |
| Anbernic      | Win600                      | Notebook    | [6d076e4bc9](https://linux-hardware.org/?probe=6d076e4bc9) | Aug 02, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [6f220fcf23](https://linux-hardware.org/?probe=6f220fcf23) | Aug 01, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [d6c2eae395](https://linux-hardware.org/?probe=d6c2eae395) | Aug 01, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [39774f9f5d](https://linux-hardware.org/?probe=39774f9f5d) | Aug 01, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [1dfc12fc6c](https://linux-hardware.org/?probe=1dfc12fc6c) | Jul 31, 2023 |
| Dell          | 0D8M0M A00                  | Desktop     | [3ac6740883](https://linux-hardware.org/?probe=3ac6740883) | Jul 31, 2023 |
| VPU Compan... | VWNC71429-S                 | Notebook    | [2a21ab7b53](https://linux-hardware.org/?probe=2a21ab7b53) | Jul 31, 2023 |
| Dell          | 0RF705                      | Desktop     | [9370437c75](https://linux-hardware.org/?probe=9370437c75) | Jul 30, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [9d93bef2df](https://linux-hardware.org/?probe=9d93bef2df) | Jul 30, 2023 |
| ASUSTek       | X540NA                      | Notebook    | [68b0d7d1fb](https://linux-hardware.org/?probe=68b0d7d1fb) | Jul 30, 2023 |
| Dell          | 0RF705                      | Desktop     | [fe3118bd3c](https://linux-hardware.org/?probe=fe3118bd3c) | Jul 30, 2023 |
| Biostar       | A320MH                      | Desktop     | [8fbc21fb3e](https://linux-hardware.org/?probe=8fbc21fb3e) | Jul 29, 2023 |
| HONOR         | BMH-WCX9                    | Notebook    | [c098429c68](https://linux-hardware.org/?probe=c098429c68) | Jul 29, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [fb2ba2d3eb](https://linux-hardware.org/?probe=fb2ba2d3eb) | Jul 29, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [8d3733b439](https://linux-hardware.org/?probe=8d3733b439) | Jul 29, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [28bd5d7d66](https://linux-hardware.org/?probe=28bd5d7d66) | Jul 29, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [dd2b310ecf](https://linux-hardware.org/?probe=dd2b310ecf) | Jul 29, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [b8e059a47d](https://linux-hardware.org/?probe=b8e059a47d) | Jul 29, 2023 |
| Lenovo        | G40-45 80E1                 | Notebook    | [27af99ec54](https://linux-hardware.org/?probe=27af99ec54) | Jul 28, 2023 |
| HP            | 0A04h                       | Desktop     | [aaf7bb9453](https://linux-hardware.org/?probe=aaf7bb9453) | Jul 28, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [4d413cb864](https://linux-hardware.org/?probe=4d413cb864) | Jul 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [e46fa3639e](https://linux-hardware.org/?probe=e46fa3639e) | Jul 27, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [1e0ad64e6f](https://linux-hardware.org/?probe=1e0ad64e6f) | Jul 27, 2023 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [01110b1f21](https://linux-hardware.org/?probe=01110b1f21) | Jul 27, 2023 |
| HONOR         | BMH-WCX9                    | Notebook    | [865315bd06](https://linux-hardware.org/?probe=865315bd06) | Jul 27, 2023 |
| Dell          | Latitude 5530               | Notebook    | [165d2cd3b1](https://linux-hardware.org/?probe=165d2cd3b1) | Jul 27, 2023 |
| ASUSTek       | B250 MINING EXPERT          | Desktop     | [0236b3ce26](https://linux-hardware.org/?probe=0236b3ce26) | Jul 26, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [c950e4d2f9](https://linux-hardware.org/?probe=c950e4d2f9) | Jul 25, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [fb125d5fcb](https://linux-hardware.org/?probe=fb125d5fcb) | Jul 25, 2023 |
| Acer          | Aspire A114-33              | Notebook    | [a8c1a06e1a](https://linux-hardware.org/?probe=a8c1a06e1a) | Jul 25, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [156d74ec26](https://linux-hardware.org/?probe=156d74ec26) | Jul 24, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [d3ba6058c7](https://linux-hardware.org/?probe=d3ba6058c7) | Jul 24, 2023 |
| Biostar       | A68MDE                      | Desktop     | [8ab5498633](https://linux-hardware.org/?probe=8ab5498633) | Jul 24, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | Notebook    | [92c6b0de0c](https://linux-hardware.org/?probe=92c6b0de0c) | Jul 23, 2023 |
| Dell          | Latitude E6400              | Notebook    | [77a598aa4d](https://linux-hardware.org/?probe=77a598aa4d) | Jul 23, 2023 |
| Dell          | 0F373D A00                  | Desktop     | [fd337bb7ab](https://linux-hardware.org/?probe=fd337bb7ab) | Jul 23, 2023 |
| Dell          | 0F373D A00                  | Desktop     | [026854a02c](https://linux-hardware.org/?probe=026854a02c) | Jul 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [28340d4ad4](https://linux-hardware.org/?probe=28340d4ad4) | Jul 23, 2023 |
| HP            | 18E7                        | Desktop     | [1638b42b8b](https://linux-hardware.org/?probe=1638b42b8b) | Jul 23, 2023 |
| HP            | 18E7                        | Desktop     | [909788f739](https://linux-hardware.org/?probe=909788f739) | Jul 23, 2023 |
| HP            | Pavilion Plus Laptop 14-... | Notebook    | [a6e2f105ed](https://linux-hardware.org/?probe=a6e2f105ed) | Jul 23, 2023 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | Desktop     | [c4890b8f34](https://linux-hardware.org/?probe=c4890b8f34) | Jul 23, 2023 |
| HP            | Pavilion dv2500             | Notebook    | [6e86c0a75b](https://linux-hardware.org/?probe=6e86c0a75b) | Jul 23, 2023 |
| ASRock        | B550M-HDV                   | Desktop     | [af255054c3](https://linux-hardware.org/?probe=af255054c3) | Jul 22, 2023 |
| MSI           | Boston                      | Desktop     | [d71010f2a7](https://linux-hardware.org/?probe=d71010f2a7) | Jul 22, 2023 |
| Dell          | Latitude E7450              | Notebook    | [d7a8f0a599](https://linux-hardware.org/?probe=d7a8f0a599) | Jul 22, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [d10701a88b](https://linux-hardware.org/?probe=d10701a88b) | Jul 22, 2023 |
| HP            | Pavilion dv6700             | Notebook    | [aed45c2e40](https://linux-hardware.org/?probe=aed45c2e40) | Jul 21, 2023 |
| HP            | 3048h                       | Desktop     | [1be902df43](https://linux-hardware.org/?probe=1be902df43) | Jul 21, 2023 |
| Acer          | Aspire SW3-013              | Notebook    | [b503fa1044](https://linux-hardware.org/?probe=b503fa1044) | Jul 21, 2023 |
| HP            | Pavilion Plus Laptop 14-... | Notebook    | [937715a75f](https://linux-hardware.org/?probe=937715a75f) | Jul 20, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [39ea43d323](https://linux-hardware.org/?probe=39ea43d323) | Jul 20, 2023 |
| HP            | 2B26 A01                    | All in one  | [41de8f48f0](https://linux-hardware.org/?probe=41de8f48f0) | Jul 20, 2023 |
| Dell          | Latitude 5420               | Notebook    | [ea97d72c47](https://linux-hardware.org/?probe=ea97d72c47) | Jul 20, 2023 |
| HP            | ENVY Notebook               | Notebook    | [0055da01e2](https://linux-hardware.org/?probe=0055da01e2) | Jul 19, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [d79851836e](https://linux-hardware.org/?probe=d79851836e) | Jul 19, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [c4ab55ea69](https://linux-hardware.org/?probe=c4ab55ea69) | Jul 18, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [666c1c0162](https://linux-hardware.org/?probe=666c1c0162) | Jul 18, 2023 |
| HP            | G42                         | Notebook    | [d42b44461e](https://linux-hardware.org/?probe=d42b44461e) | Jul 18, 2023 |
| HP            | 805A                        | Desktop     | [d4e6fca09f](https://linux-hardware.org/?probe=d4e6fca09f) | Jul 17, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [a83e3b42b3](https://linux-hardware.org/?probe=a83e3b42b3) | Jul 17, 2023 |
| MSI           | GE72MVR 7RG                 | Notebook    | [c1834b63c2](https://linux-hardware.org/?probe=c1834b63c2) | Jul 16, 2023 |
| HP            | Laptop 14-fq1xxx            | Notebook    | [2687ecdde1](https://linux-hardware.org/?probe=2687ecdde1) | Jul 14, 2023 |
| ASUSTek       | PRIME B550M-A AC            | Desktop     | [ed49c9c5e0](https://linux-hardware.org/?probe=ed49c9c5e0) | Jul 14, 2023 |
| Dell          | Inspiron 5555               | Notebook    | [a63fbcabfb](https://linux-hardware.org/?probe=a63fbcabfb) | Jul 14, 2023 |
| MSI           | MPG Z590 GAMING CARBON W... | Desktop     | [7e1752f29c](https://linux-hardware.org/?probe=7e1752f29c) | Jul 14, 2023 |
| GPU Compan... | GWTC51427                   | Notebook    | [138ef93d27](https://linux-hardware.org/?probe=138ef93d27) | Jul 13, 2023 |
| Dell          | 0D28YY A00                  | Desktop     | [1976f92f56](https://linux-hardware.org/?probe=1976f92f56) | Jul 12, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a167d41a74](https://linux-hardware.org/?probe=a167d41a74) | Jul 12, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [dd19bc7fee](https://linux-hardware.org/?probe=dd19bc7fee) | Jul 12, 2023 |
| Dell          | 0Y2MRG A00                  | Desktop     | [3866c4a7ff](https://linux-hardware.org/?probe=3866c4a7ff) | Jul 12, 2023 |
| Lenovo        | ThinkPad L390 Yoga 20NUS... | Convertible | [a1334a7b0f](https://linux-hardware.org/?probe=a1334a7b0f) | Jul 11, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | Notebook    | [052461ef4d](https://linux-hardware.org/?probe=052461ef4d) | Jul 11, 2023 |
| HP            | Pavilion g4                 | Notebook    | [6e76f09416](https://linux-hardware.org/?probe=6e76f09416) | Jul 11, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [ea833bb195](https://linux-hardware.org/?probe=ea833bb195) | Jul 11, 2023 |
| ASUSTek       | Zenbook UX562UG_Q508UG      | Convertible | [058522b2ca](https://linux-hardware.org/?probe=058522b2ca) | Jul 11, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [a0fd2eeb7b](https://linux-hardware.org/?probe=a0fd2eeb7b) | Jul 11, 2023 |
| ASRock        | B460M Pro4                  | Desktop     | [c972293107](https://linux-hardware.org/?probe=c972293107) | Jul 10, 2023 |
| Dell          | 04Y8V0 A02                  | Desktop     | [b1b3d1eedc](https://linux-hardware.org/?probe=b1b3d1eedc) | Jul 10, 2023 |
| Acer          | Aspire ES1-511              | Notebook    | [1e7434d3b0](https://linux-hardware.org/?probe=1e7434d3b0) | Jul 10, 2023 |
| ASRock        | N68-VS3 FX                  | Desktop     | [9934022e9b](https://linux-hardware.org/?probe=9934022e9b) | Jul 09, 2023 |
| Dell          | Precision M6700             | Notebook    | [ec5b230e37](https://linux-hardware.org/?probe=ec5b230e37) | Jul 09, 2023 |
| ECS           | A790GXM-AD3                 | Desktop     | [d88aa3d8d1](https://linux-hardware.org/?probe=d88aa3d8d1) | Jul 09, 2023 |
| Sony          | VPCF236FM                   | Notebook    | [21a805fe1d](https://linux-hardware.org/?probe=21a805fe1d) | Jul 08, 2023 |
| Dell          | Inspiron 5565               | Notebook    | [d1df053096](https://linux-hardware.org/?probe=d1df053096) | Jul 08, 2023 |
| HP            | Stream Laptop 14-cb1XX      | Notebook    | [883185ea85](https://linux-hardware.org/?probe=883185ea85) | Jul 07, 2023 |
| Toshiba       | Satellite L745              | Notebook    | [cda3474ee7](https://linux-hardware.org/?probe=cda3474ee7) | Jul 07, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [905af6686d](https://linux-hardware.org/?probe=905af6686d) | Jul 06, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [8d64c46d1d](https://linux-hardware.org/?probe=8d64c46d1d) | Jul 06, 2023 |
| HP            | 895C                        | Desktop     | [8a7f102530](https://linux-hardware.org/?probe=8a7f102530) | Jul 05, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [e59862f167](https://linux-hardware.org/?probe=e59862f167) | Jul 05, 2023 |
| Lenovo        | C205                        | All in one  | [04e0a62210](https://linux-hardware.org/?probe=04e0a62210) | Jul 05, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [9d57d6a85f](https://linux-hardware.org/?probe=9d57d6a85f) | Jul 05, 2023 |
| Acer          | Aspire V5-472               | Notebook    | [663adbe947](https://linux-hardware.org/?probe=663adbe947) | Jul 05, 2023 |
| Dell          | 0MWYPT A02                  | Desktop     | [bbfc788fae](https://linux-hardware.org/?probe=bbfc788fae) | Jul 05, 2023 |
| Gigabyte      | AX370-Gaming 5              | Desktop     | [5e07b39a67](https://linux-hardware.org/?probe=5e07b39a67) | Jul 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [8553179448](https://linux-hardware.org/?probe=8553179448) | Jul 04, 2023 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | Desktop     | [6ce7d33591](https://linux-hardware.org/?probe=6ce7d33591) | Jul 03, 2023 |
| Lenovo        | Aptio CRB SDK0J40679 WIN... | Mini pc     | [40f510325d](https://linux-hardware.org/?probe=40f510325d) | Jul 02, 2023 |
| Dell          | Inspiron 5555               | Notebook    | [011aa45cc1](https://linux-hardware.org/?probe=011aa45cc1) | Jul 01, 2023 |
| HP            | 550                         | Notebook    | [7681694808](https://linux-hardware.org/?probe=7681694808) | Jul 01, 2023 |
| PCChips       | P17G ECS                    | Desktop     | [c1181f8ae7](https://linux-hardware.org/?probe=c1181f8ae7) | Jul 01, 2023 |
| Dell          | 0YXT71 A00                  | Desktop     | [031599c8b1](https://linux-hardware.org/?probe=031599c8b1) | Jul 01, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [4d4d992cb0](https://linux-hardware.org/?probe=4d4d992cb0) | Jul 01, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [3c3ddffa8b](https://linux-hardware.org/?probe=3c3ddffa8b) | Jul 01, 2023 |
| Lenovo        | ThinkPad L430 246634S       | Notebook    | [5368d4410f](https://linux-hardware.org/?probe=5368d4410f) | Jun 30, 2023 |
| Dell          | Inspiron 5555               | Notebook    | [7c07dbad40](https://linux-hardware.org/?probe=7c07dbad40) | Jun 29, 2023 |
| Alienware     | 17 R4                       | Notebook    | [e7f3110f1f](https://linux-hardware.org/?probe=e7f3110f1f) | Jun 29, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [2f50312c02](https://linux-hardware.org/?probe=2f50312c02) | Jun 29, 2023 |
| Dell          | 0H1TR9 A00                  | All in one  | [b4be8eaa80](https://linux-hardware.org/?probe=b4be8eaa80) | Jun 27, 2023 |
| HP            | Pavilion dv6700             | Notebook    | [182bf6e4a7](https://linux-hardware.org/?probe=182bf6e4a7) | Jun 27, 2023 |
| HP            | Pavilion dv6700             | Notebook    | [c5e6819ca8](https://linux-hardware.org/?probe=c5e6819ca8) | Jun 26, 2023 |
| HP            | 339A                        | Desktop     | [ff38f43250](https://linux-hardware.org/?probe=ff38f43250) | Jun 25, 2023 |
| Lenovo        | ThinkPad T480 20L6S01G00    | Notebook    | [a66d6dba45](https://linux-hardware.org/?probe=a66d6dba45) | Jun 25, 2023 |
| Acer          | AOD270                      | Notebook    | [af596f2c11](https://linux-hardware.org/?probe=af596f2c11) | Jun 24, 2023 |
| Acer          | AOD270                      | Notebook    | [d3204f80d5](https://linux-hardware.org/?probe=d3204f80d5) | Jun 24, 2023 |
| MSI           | GE66 Raider 10SFS           | Notebook    | [683b7b2dc2](https://linux-hardware.org/?probe=683b7b2dc2) | Jun 24, 2023 |
| MSI           | GE66 Raider 10SFS           | Notebook    | [558a5b8a7f](https://linux-hardware.org/?probe=558a5b8a7f) | Jun 24, 2023 |
| Lenovo        | IdeaPad Gaming 3 16IAH7 ... | Notebook    | [ef5eb06f90](https://linux-hardware.org/?probe=ef5eb06f90) | Jun 24, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [44b5bb5453](https://linux-hardware.org/?probe=44b5bb5453) | Jun 23, 2023 |
| Dell          | Latitude E5470              | Notebook    | [e10153b4c9](https://linux-hardware.org/?probe=e10153b4c9) | Jun 23, 2023 |
| Dell          | 0G9322                      | Desktop     | [a742a26282](https://linux-hardware.org/?probe=a742a26282) | Jun 22, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [2e654ead73](https://linux-hardware.org/?probe=2e654ead73) | Jun 21, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [2ebfd9c347](https://linux-hardware.org/?probe=2ebfd9c347) | Jun 21, 2023 |
| Gateway       | ZX4800                      | All in one  | [fbb23975d9](https://linux-hardware.org/?probe=fbb23975d9) | Jun 21, 2023 |
| Gateway       | ZX4800                      | All in one  | [eea8b39580](https://linux-hardware.org/?probe=eea8b39580) | Jun 21, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [696e42eaba](https://linux-hardware.org/?probe=696e42eaba) | Jun 20, 2023 |
| ASUSTek       | TP501UA                     | Notebook    | [e883c61561](https://linux-hardware.org/?probe=e883c61561) | Jun 19, 2023 |
| Gigabyte      | GA-E350N                    | Desktop     | [dc5ab95b15](https://linux-hardware.org/?probe=dc5ab95b15) | Jun 19, 2023 |
| Dell          | Latitude 5531               | Notebook    | [bf22616526](https://linux-hardware.org/?probe=bf22616526) | Jun 18, 2023 |
| HP            | 2B3B                        | All in one  | [5e96206d26](https://linux-hardware.org/?probe=5e96206d26) | Jun 17, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [a2bbc6abd3](https://linux-hardware.org/?probe=a2bbc6abd3) | Jun 17, 2023 |
| MSI           | B360M PRO-VH                | Desktop     | [e628906fc2](https://linux-hardware.org/?probe=e628906fc2) | Jun 16, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [dc892cf2b0](https://linux-hardware.org/?probe=dc892cf2b0) | Jun 16, 2023 |
| Dell          | Latitude E6320              | Notebook    | [f1552f3016](https://linux-hardware.org/?probe=f1552f3016) | Jun 16, 2023 |
| Chuwi         | LarkBook X                  | Notebook    | [1869c3f4dc](https://linux-hardware.org/?probe=1869c3f4dc) | Jun 16, 2023 |
| Chuwi         | LarkBook X                  | Notebook    | [2aed95c237](https://linux-hardware.org/?probe=2aed95c237) | Jun 16, 2023 |
| Dell          | Inspiron 5548               | Notebook    | [547ffd8db7](https://linux-hardware.org/?probe=547ffd8db7) | Jun 16, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [67ed3346c2](https://linux-hardware.org/?probe=67ed3346c2) | Jun 15, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [07f1089ee7](https://linux-hardware.org/?probe=07f1089ee7) | Jun 15, 2023 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [ae9d05ff3a](https://linux-hardware.org/?probe=ae9d05ff3a) | Jun 15, 2023 |
| Acer          | Aspire V5-472               | Notebook    | [58dc632831](https://linux-hardware.org/?probe=58dc632831) | Jun 15, 2023 |
| Lenovo        | ThinkPad T495 20NKS0TG00    | Notebook    | [628c8fb554](https://linux-hardware.org/?probe=628c8fb554) | Jun 15, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [ca0a511cd7](https://linux-hardware.org/?probe=ca0a511cd7) | Jun 14, 2023 |
| HP            | G61                         | Notebook    | [52e962e82d](https://linux-hardware.org/?probe=52e962e82d) | Jun 14, 2023 |
| Dell          | Latitude 5590               | Notebook    | [56f8f9bbaf](https://linux-hardware.org/?probe=56f8f9bbaf) | Jun 14, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [f444f44a49](https://linux-hardware.org/?probe=f444f44a49) | Jun 13, 2023 |
| Gateway       | NE572                       | Notebook    | [771f8d0d63](https://linux-hardware.org/?probe=771f8d0d63) | Jun 13, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [2794a5aa86](https://linux-hardware.org/?probe=2794a5aa86) | Jun 12, 2023 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | Notebook    | [98a4801b23](https://linux-hardware.org/?probe=98a4801b23) | Jun 12, 2023 |
| Toshiba       | Mobile Intel 4 Series/IC... | Desktop     | [45696e1d1b](https://linux-hardware.org/?probe=45696e1d1b) | Jun 12, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [4cf431ecc8](https://linux-hardware.org/?probe=4cf431ecc8) | Jun 12, 2023 |
| ASUSTek       | PRIME B650M-A AX            | Desktop     | [f39a1874f7](https://linux-hardware.org/?probe=f39a1874f7) | Jun 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [2c5f9d83bd](https://linux-hardware.org/?probe=2c5f9d83bd) | Jun 12, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [b31d9c8e55](https://linux-hardware.org/?probe=b31d9c8e55) | Jun 12, 2023 |
| Dell          | Latitude 5590               | Notebook    | [f6347f5d6b](https://linux-hardware.org/?probe=f6347f5d6b) | Jun 11, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [f3a04ea109](https://linux-hardware.org/?probe=f3a04ea109) | Jun 11, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [d9ad875572](https://linux-hardware.org/?probe=d9ad875572) | Jun 11, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [7e6a1fa5ff](https://linux-hardware.org/?probe=7e6a1fa5ff) | Jun 11, 2023 |
| Lenovo        | Legion Slim 7 16IRH8 82Y... | Notebook    | [e9e79a1c3b](https://linux-hardware.org/?probe=e9e79a1c3b) | Jun 11, 2023 |
| HP            | Stream Laptop 11-ah0XX      | Notebook    | [a3e566ad38](https://linux-hardware.org/?probe=a3e566ad38) | Jun 11, 2023 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [e3311e26b6](https://linux-hardware.org/?probe=e3311e26b6) | Jun 11, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [03f0e4060e](https://linux-hardware.org/?probe=03f0e4060e) | Jun 10, 2023 |
| Google        | Pirika                      | Notebook    | [67fce0a645](https://linux-hardware.org/?probe=67fce0a645) | Jun 10, 2023 |
| Dell          | Vostro 3560                 | Notebook    | [86f646e00f](https://linux-hardware.org/?probe=86f646e00f) | Jun 10, 2023 |
| Dell          | Vostro 3560                 | Notebook    | [1bb9178df2](https://linux-hardware.org/?probe=1bb9178df2) | Jun 10, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [881d5dc409](https://linux-hardware.org/?probe=881d5dc409) | Jun 09, 2023 |
| Dell          | Inspiron 7348               | Notebook    | [a2bd4ab5b9](https://linux-hardware.org/?probe=a2bd4ab5b9) | Jun 09, 2023 |
| Dell          | 0YXT71 A00                  | Desktop     | [477afe615b](https://linux-hardware.org/?probe=477afe615b) | Jun 09, 2023 |
| Dell          | 0YXT71 A00                  | Desktop     | [463dfa5d83](https://linux-hardware.org/?probe=463dfa5d83) | Jun 09, 2023 |
| ASUSTek       | PRIME A520M-A II            | Desktop     | [176b4ca0bb](https://linux-hardware.org/?probe=176b4ca0bb) | Jun 09, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | Notebook    | [a579703f97](https://linux-hardware.org/?probe=a579703f97) | Jun 09, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [c35e22de2b](https://linux-hardware.org/?probe=c35e22de2b) | Jun 09, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [68be9da7f1](https://linux-hardware.org/?probe=68be9da7f1) | Jun 09, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [e28668e147](https://linux-hardware.org/?probe=e28668e147) | Jun 08, 2023 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [5861bc7cef](https://linux-hardware.org/?probe=5861bc7cef) | Jun 08, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [f1100ce875](https://linux-hardware.org/?probe=f1100ce875) | Jun 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [59ff5486a9](https://linux-hardware.org/?probe=59ff5486a9) | Jun 08, 2023 |
| ASUSTek       | X455LA                      | Notebook    | [583596672d](https://linux-hardware.org/?probe=583596672d) | Jun 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [3acaedf40f](https://linux-hardware.org/?probe=3acaedf40f) | Jun 08, 2023 |
| Dell          | 0G9322                      | Desktop     | [e81a7f788a](https://linux-hardware.org/?probe=e81a7f788a) | Jun 07, 2023 |
| Gigabyte      | B550 VISION D               | Desktop     | [94cf7f5675](https://linux-hardware.org/?probe=94cf7f5675) | Jun 07, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [99b42755e8](https://linux-hardware.org/?probe=99b42755e8) | Jun 07, 2023 |
| Dell          | Latitude E6400              | Notebook    | [ced90af89e](https://linux-hardware.org/?probe=ced90af89e) | Jun 06, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [a9ea51ea77](https://linux-hardware.org/?probe=a9ea51ea77) | Jun 06, 2023 |
| Lenovo        | ThinkPad W520 427637U       | Notebook    | [1bec07891b](https://linux-hardware.org/?probe=1bec07891b) | Jun 05, 2023 |
| HP            | Pavilion g4                 | Notebook    | [af0c33de44](https://linux-hardware.org/?probe=af0c33de44) | Jun 05, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [bfce53d6f5](https://linux-hardware.org/?probe=bfce53d6f5) | Jun 05, 2023 |
| HP            | 240 G3                      | Notebook    | [475e3e63ef](https://linux-hardware.org/?probe=475e3e63ef) | Jun 05, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [d275c3c00b](https://linux-hardware.org/?probe=d275c3c00b) | Jun 05, 2023 |
| ASUSTek       | H81M-A                      | Desktop     | [9636642e65](https://linux-hardware.org/?probe=9636642e65) | Jun 04, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [9ee7eff678](https://linux-hardware.org/?probe=9ee7eff678) | Jun 04, 2023 |
| MSI           | Boston                      | Desktop     | [95b4d5183d](https://linux-hardware.org/?probe=95b4d5183d) | Jun 04, 2023 |
| Lanix         | AL V9                       | Notebook    | [3bd23fdde7](https://linux-hardware.org/?probe=3bd23fdde7) | Jun 04, 2023 |
| Dell          | 0G9322                      | Desktop     | [a1c5ec8909](https://linux-hardware.org/?probe=a1c5ec8909) | Jun 03, 2023 |
| Dell          | Inspiron 5555               | Notebook    | [e14ab40d68](https://linux-hardware.org/?probe=e14ab40d68) | Jun 03, 2023 |
| ASUSTek       | PRIME B650M-A AX            | Desktop     | [983a81f19e](https://linux-hardware.org/?probe=983a81f19e) | Jun 03, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [8933e1b0ad](https://linux-hardware.org/?probe=8933e1b0ad) | Jun 03, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [b546b2e7f1](https://linux-hardware.org/?probe=b546b2e7f1) | Jun 02, 2023 |
| Dell          | Latitude E5470              | Notebook    | [daa15a6cb0](https://linux-hardware.org/?probe=daa15a6cb0) | Jun 02, 2023 |
| Dell          | Latitude E5470              | Notebook    | [92d3a8b502](https://linux-hardware.org/?probe=92d3a8b502) | Jun 02, 2023 |
| Dell          | Inspiron N4030              | Notebook    | [1a01fbae46](https://linux-hardware.org/?probe=1a01fbae46) | Jun 02, 2023 |
| Lenovo        | ThinkPad T430 2350BG7       | Notebook    | [29d6e72544](https://linux-hardware.org/?probe=29d6e72544) | Jun 02, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [bc606409ff](https://linux-hardware.org/?probe=bc606409ff) | Jun 01, 2023 |
| Valve         | Jupiter                     | Notebook    | [30a2370d6e](https://linux-hardware.org/?probe=30a2370d6e) | Jun 01, 2023 |
| Acer          | AO756                       | Notebook    | [e135dbe37e](https://linux-hardware.org/?probe=e135dbe37e) | Jun 01, 2023 |
| Lenovo        | ThinkPad L440 20ASA20VLM    | Notebook    | [1d59682589](https://linux-hardware.org/?probe=1d59682589) | Jun 01, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [560680687c](https://linux-hardware.org/?probe=560680687c) | May 31, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [65b03710b2](https://linux-hardware.org/?probe=65b03710b2) | May 31, 2023 |
| Lenovo        | ThinkPad T430 2350BG7       | Notebook    | [a09171afde](https://linux-hardware.org/?probe=a09171afde) | May 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [32ba69494b](https://linux-hardware.org/?probe=32ba69494b) | May 31, 2023 |
| Gigabyte      | GA-E6010N                   | Desktop     | [563074319d](https://linux-hardware.org/?probe=563074319d) | May 31, 2023 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [54b872a39b](https://linux-hardware.org/?probe=54b872a39b) | May 31, 2023 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | Desktop     | [6dbaa9e2ff](https://linux-hardware.org/?probe=6dbaa9e2ff) | May 30, 2023 |
| TPV-INVENT... | 2AC6 A01                    | Desktop     | [1ac394c97c](https://linux-hardware.org/?probe=1ac394c97c) | May 30, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [d2ce08a746](https://linux-hardware.org/?probe=d2ce08a746) | May 30, 2023 |
| Alienware     | m15 Ryzen Ed. R5            | Notebook    | [ed1996aaeb](https://linux-hardware.org/?probe=ed1996aaeb) | May 30, 2023 |
| Alienware     | m15 Ryzen Ed. R5            | Notebook    | [3b8f9077db](https://linux-hardware.org/?probe=3b8f9077db) | May 30, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [bb05a8a89b](https://linux-hardware.org/?probe=bb05a8a89b) | May 30, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [f23e90acce](https://linux-hardware.org/?probe=f23e90acce) | May 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [7816244e1a](https://linux-hardware.org/?probe=7816244e1a) | May 30, 2023 |
| Biostar       | H310MHP                     | Desktop     | [7bfe35481d](https://linux-hardware.org/?probe=7bfe35481d) | May 29, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [6dca0624e2](https://linux-hardware.org/?probe=6dca0624e2) | May 29, 2023 |
| Acer          | Aspire E5-573               | Notebook    | [fc839b0b6f](https://linux-hardware.org/?probe=fc839b0b6f) | May 29, 2023 |
| Biostar       | H310MHP                     | Desktop     | [7138f287c8](https://linux-hardware.org/?probe=7138f287c8) | May 29, 2023 |
| HP            | Compaq 6910p (GY174UP#AB... | Notebook    | [43ee52e798](https://linux-hardware.org/?probe=43ee52e798) | May 28, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [412b42ae92](https://linux-hardware.org/?probe=412b42ae92) | May 28, 2023 |
| HP            | Mini 110-3700               | Notebook    | [0f9528a8d2](https://linux-hardware.org/?probe=0f9528a8d2) | May 28, 2023 |
| Pegatron      | 2ACB                        | Desktop     | [cc1c8b2941](https://linux-hardware.org/?probe=cc1c8b2941) | May 28, 2023 |
| ASUSTek       | H81M-A                      | Desktop     | [70714d71f5](https://linux-hardware.org/?probe=70714d71f5) | May 28, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [3f6fc3ec0c](https://linux-hardware.org/?probe=3f6fc3ec0c) | May 27, 2023 |
| PCChips       | P17G ECS                    | Desktop     | [0518fce589](https://linux-hardware.org/?probe=0518fce589) | May 27, 2023 |
| Dell          | 0G9322                      | Desktop     | [4d1450ba3a](https://linux-hardware.org/?probe=4d1450ba3a) | May 27, 2023 |
| Biostar       | A10N-8800E                  | Desktop     | [6b8c135c5d](https://linux-hardware.org/?probe=6b8c135c5d) | May 27, 2023 |
| HP            | 1497                        | Desktop     | [94f79f2f74](https://linux-hardware.org/?probe=94f79f2f74) | May 27, 2023 |
| Dell          | 0G9322                      | Desktop     | [d742ccb0c4](https://linux-hardware.org/?probe=d742ccb0c4) | May 27, 2023 |
| HP            | 1497                        | Desktop     | [d2cca6c2a1](https://linux-hardware.org/?probe=d2cca6c2a1) | May 27, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [3715c09ad3](https://linux-hardware.org/?probe=3715c09ad3) | May 27, 2023 |
| HP            | 895C                        | Desktop     | [f0986c3613](https://linux-hardware.org/?probe=f0986c3613) | May 26, 2023 |
| HP            | 2B3B                        | All in one  | [7819836b92](https://linux-hardware.org/?probe=7819836b92) | May 26, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [df5ea78282](https://linux-hardware.org/?probe=df5ea78282) | May 25, 2023 |
| Acer          | Aspire E5-575               | Notebook    | [45ac56e70c](https://linux-hardware.org/?probe=45ac56e70c) | May 25, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [922428b203](https://linux-hardware.org/?probe=922428b203) | May 25, 2023 |
| Dell          | Latitude E5470              | Notebook    | [6054d2ee2b](https://linux-hardware.org/?probe=6054d2ee2b) | May 25, 2023 |
| Apple         | MacBookPro6,1               | Notebook    | [c8eb2c32b3](https://linux-hardware.org/?probe=c8eb2c32b3) | May 25, 2023 |
| Gigabyte      | G41MT-S2P                   | Desktop     | [edfd6dd6d9](https://linux-hardware.org/?probe=edfd6dd6d9) | May 24, 2023 |
| Gigabyte      | G41MT-S2P                   | Desktop     | [43cf78743a](https://linux-hardware.org/?probe=43cf78743a) | May 24, 2023 |
| Apple         | MacBookPro6,1               | Notebook    | [a8da820b95](https://linux-hardware.org/?probe=a8da820b95) | May 24, 2023 |
| Dell          | Inspiron 5548               | Notebook    | [5665ccbc0a](https://linux-hardware.org/?probe=5665ccbc0a) | May 23, 2023 |
| Toshiba       | Satellite C645D             | Notebook    | [97abd98fdd](https://linux-hardware.org/?probe=97abd98fdd) | May 23, 2023 |
| MSI           | GF65 Thin 9SE               | Notebook    | [c485674a13](https://linux-hardware.org/?probe=c485674a13) | May 23, 2023 |
| Pegatron      | 2ACB                        | Desktop     | [e9c0ee4659](https://linux-hardware.org/?probe=e9c0ee4659) | May 23, 2023 |
| HP            | Pavilion dm4                | Notebook    | [81f264e4ef](https://linux-hardware.org/?probe=81f264e4ef) | May 22, 2023 |
| HP            | Pavilion dm4                | Notebook    | [1f1a9e3f62](https://linux-hardware.org/?probe=1f1a9e3f62) | May 22, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [ab21a2a608](https://linux-hardware.org/?probe=ab21a2a608) | May 22, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [a4b0d5fd13](https://linux-hardware.org/?probe=a4b0d5fd13) | May 22, 2023 |
| HP            | Pavilion dm4                | Notebook    | [e25186a486](https://linux-hardware.org/?probe=e25186a486) | May 22, 2023 |
| HUAWEI        | NBM-WXX9                    | Notebook    | [e3ea42dd02](https://linux-hardware.org/?probe=e3ea42dd02) | May 22, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [2ae04bd0d4](https://linux-hardware.org/?probe=2ae04bd0d4) | May 21, 2023 |
| HP            | 2B3B                        | All in one  | [2ed92e9c21](https://linux-hardware.org/?probe=2ed92e9c21) | May 21, 2023 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [b2c9a1cd71](https://linux-hardware.org/?probe=b2c9a1cd71) | May 21, 2023 |
| Lenovo        | ThinkPad W530 24382LU       | Notebook    | [908f53f58b](https://linux-hardware.org/?probe=908f53f58b) | May 20, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [c25d920f3d](https://linux-hardware.org/?probe=c25d920f3d) | May 20, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [03c6d7a815](https://linux-hardware.org/?probe=03c6d7a815) | May 19, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [f76ac6d7b5](https://linux-hardware.org/?probe=f76ac6d7b5) | May 19, 2023 |
| Lenovo        | C205                        | All in one  | [16ecd2d81d](https://linux-hardware.org/?probe=16ecd2d81d) | May 19, 2023 |
| Lenovo        | C205                        | All in one  | [dfb0b6c8f3](https://linux-hardware.org/?probe=dfb0b6c8f3) | May 19, 2023 |
| ASUSTek       | PRIME B550M-A AC            | Desktop     | [916931d01a](https://linux-hardware.org/?probe=916931d01a) | May 19, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C2C... | Notebook    | [a0f983e519](https://linux-hardware.org/?probe=a0f983e519) | May 18, 2023 |
| ASUSTek       | G73Sw                       | Notebook    | [ec9817e3d1](https://linux-hardware.org/?probe=ec9817e3d1) | May 16, 2023 |
| Dell          | Inspiron 20 Model 3043      | All in one  | [2401d72219](https://linux-hardware.org/?probe=2401d72219) | May 16, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [496f6048ec](https://linux-hardware.org/?probe=496f6048ec) | May 15, 2023 |
| Samsung       | R530/R730                   | Notebook    | [d7674fa203](https://linux-hardware.org/?probe=d7674fa203) | May 15, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [2df8fbd5a5](https://linux-hardware.org/?probe=2df8fbd5a5) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [204400bcf7](https://linux-hardware.org/?probe=204400bcf7) | May 13, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [275f194797](https://linux-hardware.org/?probe=275f194797) | May 13, 2023 |
| HP            | 2B3B                        | All in one  | [4785289345](https://linux-hardware.org/?probe=4785289345) | May 13, 2023 |
| ASRock        | H55M-LE                     | Desktop     | [e31e211aa2](https://linux-hardware.org/?probe=e31e211aa2) | May 13, 2023 |
| ASRock        | H55M-LE                     | Desktop     | [8f2f79fb45](https://linux-hardware.org/?probe=8f2f79fb45) | May 13, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [f8c0bd3176](https://linux-hardware.org/?probe=f8c0bd3176) | May 12, 2023 |
| HP            | 2B3B                        | All in one  | [a4c65ac28f](https://linux-hardware.org/?probe=a4c65ac28f) | May 12, 2023 |
| HP            | 2B3B                        | All in one  | [ca83ed5e3f](https://linux-hardware.org/?probe=ca83ed5e3f) | May 12, 2023 |
| HP            | 0A58h                       | Desktop     | [b48452bdd9](https://linux-hardware.org/?probe=b48452bdd9) | May 12, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [ecb43775d1](https://linux-hardware.org/?probe=ecb43775d1) | May 11, 2023 |
| Biostar       | B450MH                      | Desktop     | [e5dac06f4e](https://linux-hardware.org/?probe=e5dac06f4e) | May 11, 2023 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [e644ef3b24](https://linux-hardware.org/?probe=e644ef3b24) | May 11, 2023 |
| Biostar       | B450MH                      | Desktop     | [12659ad2e2](https://linux-hardware.org/?probe=12659ad2e2) | May 11, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [f02c2abaab](https://linux-hardware.org/?probe=f02c2abaab) | May 11, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [9ff409cce8](https://linux-hardware.org/?probe=9ff409cce8) | May 11, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | Notebook    | [79d149ff5c](https://linux-hardware.org/?probe=79d149ff5c) | May 11, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [e360693145](https://linux-hardware.org/?probe=e360693145) | May 11, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [b791be35c2](https://linux-hardware.org/?probe=b791be35c2) | May 10, 2023 |
| eMachines     | E625                        | Notebook    | [1271e33078](https://linux-hardware.org/?probe=1271e33078) | May 10, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [7058baf75d](https://linux-hardware.org/?probe=7058baf75d) | May 10, 2023 |
| eMachines     | E625                        | Notebook    | [3160c872b8](https://linux-hardware.org/?probe=3160c872b8) | May 10, 2023 |
| Lenovo        | ThinkPad T480 20L6S91L00    | Notebook    | [82c3d7dd74](https://linux-hardware.org/?probe=82c3d7dd74) | May 09, 2023 |
| Lanix Amer... | A V19                       | Notebook    | [31e64dbd5d](https://linux-hardware.org/?probe=31e64dbd5d) | May 08, 2023 |
| HP            | 15                          | Notebook    | [fd2af6a225](https://linux-hardware.org/?probe=fd2af6a225) | May 08, 2023 |
| HP            | Laptop 15-da2xxx            | Notebook    | [8f08aa189f](https://linux-hardware.org/?probe=8f08aa189f) | May 08, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [75fe05267b](https://linux-hardware.org/?probe=75fe05267b) | May 08, 2023 |
| AZW           | SER V01                     | Mini pc     | [6097531bfc](https://linux-hardware.org/?probe=6097531bfc) | May 08, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [a8d45ac430](https://linux-hardware.org/?probe=a8d45ac430) | May 07, 2023 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | Desktop     | [dbeb828b17](https://linux-hardware.org/?probe=dbeb828b17) | May 07, 2023 |
| ASUSTek       | Q405UA                      | Convertible | [f8f69fc110](https://linux-hardware.org/?probe=f8f69fc110) | May 06, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [c3ef7b4de9](https://linux-hardware.org/?probe=c3ef7b4de9) | May 06, 2023 |
| HP            | Pavilion g4                 | Notebook    | [55a4a7978e](https://linux-hardware.org/?probe=55a4a7978e) | May 04, 2023 |
| Lenovo        | IdeaPad Yoga 11S 20246      | Notebook    | [fde0845fa4](https://linux-hardware.org/?probe=fde0845fa4) | May 04, 2023 |
| Gigabyte      | H410M H                     | Desktop     | [3e13b2bc4a](https://linux-hardware.org/?probe=3e13b2bc4a) | May 04, 2023 |
| Lenovo        | IdeaPad Yoga 11S 20246      | Notebook    | [1a15177f0a](https://linux-hardware.org/?probe=1a15177f0a) | May 04, 2023 |
| Lenovo        | Yoga 300-11IBY 80M0         | Notebook    | [a4a894bb7a](https://linux-hardware.org/?probe=a4a894bb7a) | May 03, 2023 |
| Dell          | Inspiron 20 Model 3043      | All in one  | [8a25091e19](https://linux-hardware.org/?probe=8a25091e19) | May 03, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [3a9a2590e3](https://linux-hardware.org/?probe=3a9a2590e3) | May 01, 2023 |
| Dell          | 0D6H9T A00                  | Desktop     | [0e46a82cca](https://linux-hardware.org/?probe=0e46a82cca) | May 01, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [c2b7a8dbe1](https://linux-hardware.org/?probe=c2b7a8dbe1) | May 01, 2023 |
| Lenovo        | ThinkPad T480 20L6S91L00    | Notebook    | [fe2f2e420f](https://linux-hardware.org/?probe=fe2f2e420f) | May 01, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [0784fc9b1c](https://linux-hardware.org/?probe=0784fc9b1c) | Apr 30, 2023 |
| Dell          | Latitude 5580               | Notebook    | [556abc1561](https://linux-hardware.org/?probe=556abc1561) | Apr 30, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [9c07454907](https://linux-hardware.org/?probe=9c07454907) | Apr 30, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [3056c07eb6](https://linux-hardware.org/?probe=3056c07eb6) | Apr 29, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [4490476bd2](https://linux-hardware.org/?probe=4490476bd2) | Apr 29, 2023 |
| Gigabyte      | H410M H                     | Desktop     | [3ea3271f4a](https://linux-hardware.org/?probe=3ea3271f4a) | Apr 29, 2023 |
| Biostar       | A10N-9630E                  | Desktop     | [e9df412284](https://linux-hardware.org/?probe=e9df412284) | Apr 28, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [210ceedb6d](https://linux-hardware.org/?probe=210ceedb6d) | Apr 28, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [7aa3832621](https://linux-hardware.org/?probe=7aa3832621) | Apr 28, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [155ce08a00](https://linux-hardware.org/?probe=155ce08a00) | Apr 27, 2023 |
| ASUSTek       | AM1M-A                      | Desktop     | [ab3c4ea199](https://linux-hardware.org/?probe=ab3c4ea199) | Apr 26, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [1fb0741f20](https://linux-hardware.org/?probe=1fb0741f20) | Apr 26, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [f43777b85b](https://linux-hardware.org/?probe=f43777b85b) | Apr 26, 2023 |
| Lenovo        | 30FD SDK0J40697 WIN 3305... | Desktop     | [07e9099105](https://linux-hardware.org/?probe=07e9099105) | Apr 26, 2023 |
| Lenovo        | Y720-15IKB 80VR             | Notebook    | [c9ef115a29](https://linux-hardware.org/?probe=c9ef115a29) | Apr 26, 2023 |
| Dell          | 0WR7PY A01                  | Desktop     | [6eeb692185](https://linux-hardware.org/?probe=6eeb692185) | Apr 25, 2023 |
| Lenovo        | Y720-15IKB 80VR             | Notebook    | [1602540ab8](https://linux-hardware.org/?probe=1602540ab8) | Apr 25, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [93b15a590f](https://linux-hardware.org/?probe=93b15a590f) | Apr 25, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [e05975b1cc](https://linux-hardware.org/?probe=e05975b1cc) | Apr 25, 2023 |
| Dell          | 03FV9K A00                  | Server      | [4d9f06ca7b](https://linux-hardware.org/?probe=4d9f06ca7b) | Apr 24, 2023 |
| DERE          | X16                         | Notebook    | [8c51699ade](https://linux-hardware.org/?probe=8c51699ade) | Apr 23, 2023 |
| HP            | 805D                        | Desktop     | [091e90cae0](https://linux-hardware.org/?probe=091e90cae0) | Apr 23, 2023 |
| Acer          | AOD270                      | Notebook    | [d7d653d3d6](https://linux-hardware.org/?probe=d7d653d3d6) | Apr 23, 2023 |
| Gigabyte      | G41MT-S2P                   | Desktop     | [9f5177c657](https://linux-hardware.org/?probe=9f5177c657) | Apr 23, 2023 |
| Gigabyte      | G41MT-S2P                   | Desktop     | [e263516539](https://linux-hardware.org/?probe=e263516539) | Apr 23, 2023 |
| Toshiba       | Satellite C845              | Notebook    | [8174d09074](https://linux-hardware.org/?probe=8174d09074) | Apr 21, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [880ee85934](https://linux-hardware.org/?probe=880ee85934) | Apr 21, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [7215ce49dd](https://linux-hardware.org/?probe=7215ce49dd) | Apr 21, 2023 |
| Dell          | G15 5510                    | Notebook    | [724945ee92](https://linux-hardware.org/?probe=724945ee92) | Apr 20, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d8025962bf](https://linux-hardware.org/?probe=d8025962bf) | Apr 20, 2023 |
| ASUSTek       | T100TAF                     | Notebook    | [9e59d428d2](https://linux-hardware.org/?probe=9e59d428d2) | Apr 19, 2023 |
| Dell          | 0HR330                      | Desktop     | [1619f09258](https://linux-hardware.org/?probe=1619f09258) | Apr 19, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [2cb8ecb34d](https://linux-hardware.org/?probe=2cb8ecb34d) | Apr 19, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [33b92210c7](https://linux-hardware.org/?probe=33b92210c7) | Apr 19, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [fe26aeffdd](https://linux-hardware.org/?probe=fe26aeffdd) | Apr 19, 2023 |
| HP            | Unknown                     | Notebook    | [5a295b02bc](https://linux-hardware.org/?probe=5a295b02bc) | Apr 19, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [39057bb60a](https://linux-hardware.org/?probe=39057bb60a) | Apr 18, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [ebfd8fec1b](https://linux-hardware.org/?probe=ebfd8fec1b) | Apr 18, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [28f6e6e6c6](https://linux-hardware.org/?probe=28f6e6e6c6) | Apr 18, 2023 |
| Intel         | DZ68DB AAG27985-105         | Desktop     | [aa030a4054](https://linux-hardware.org/?probe=aa030a4054) | Apr 18, 2023 |
| Gigabyte      | H370 AORUS GAMING 3-CF      | Desktop     | [8b585cf135](https://linux-hardware.org/?probe=8b585cf135) | Apr 18, 2023 |
| HP            | ProBook 645 G1              | Notebook    | [e7d992accf](https://linux-hardware.org/?probe=e7d992accf) | Apr 17, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [ad381ae6d8](https://linux-hardware.org/?probe=ad381ae6d8) | Apr 17, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [94f62c41e5](https://linux-hardware.org/?probe=94f62c41e5) | Apr 17, 2023 |
| Gigabyte      | GA-IMB410TN                 | Desktop     | [44293ba6b9](https://linux-hardware.org/?probe=44293ba6b9) | Apr 17, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [4644eb92ef](https://linux-hardware.org/?probe=4644eb92ef) | Apr 17, 2023 |
| Gigabyte      | GA-IMB410TN                 | Desktop     | [983906ed11](https://linux-hardware.org/?probe=983906ed11) | Apr 17, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [52e4ec34e1](https://linux-hardware.org/?probe=52e4ec34e1) | Apr 16, 2023 |
| HP            | 1850                        | Desktop     | [9ba17e1d9c](https://linux-hardware.org/?probe=9ba17e1d9c) | Apr 16, 2023 |
| Biostar       | A10N-8800E                  | Desktop     | [31557d5e8c](https://linux-hardware.org/?probe=31557d5e8c) | Apr 15, 2023 |
| HP            | 1850                        | Desktop     | [d30cea781b](https://linux-hardware.org/?probe=d30cea781b) | Apr 15, 2023 |
| Dell          | 0HR330                      | Desktop     | [4fd4f887bd](https://linux-hardware.org/?probe=4fd4f887bd) | Apr 14, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [2e6b5600aa](https://linux-hardware.org/?probe=2e6b5600aa) | Apr 14, 2023 |
| Dell          | Inspiron 20 Model 3043      | All in one  | [73b41d39ba](https://linux-hardware.org/?probe=73b41d39ba) | Apr 14, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [9ab8e04a20](https://linux-hardware.org/?probe=9ab8e04a20) | Apr 14, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [1a327ce647](https://linux-hardware.org/?probe=1a327ce647) | Apr 13, 2023 |
| HP            | 1589                        | Desktop     | [b1ca06250e](https://linux-hardware.org/?probe=b1ca06250e) | Apr 13, 2023 |
| Dell          | Vostro 14-3468              | Notebook    | [947f70ebf7](https://linux-hardware.org/?probe=947f70ebf7) | Apr 13, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [bc3ccff50c](https://linux-hardware.org/?probe=bc3ccff50c) | Apr 13, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [77384847ef](https://linux-hardware.org/?probe=77384847ef) | Apr 12, 2023 |
| Gigabyte      | G1.Sniper M3-CF             | Desktop     | [d3ecd3c066](https://linux-hardware.org/?probe=d3ecd3c066) | Apr 12, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [23c158b19b](https://linux-hardware.org/?probe=23c158b19b) | Apr 12, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [4c217a8a03](https://linux-hardware.org/?probe=4c217a8a03) | Apr 11, 2023 |
| HP            | ProBook 655 G1              | Notebook    | [aaef8a36db](https://linux-hardware.org/?probe=aaef8a36db) | Apr 10, 2023 |
| eMachines     | EL1852G                     | Desktop     | [e99e4b1fac](https://linux-hardware.org/?probe=e99e4b1fac) | Apr 10, 2023 |
| Lanix         | ChiefRiver                  | Desktop     | [ef23ac88e4](https://linux-hardware.org/?probe=ef23ac88e4) | Apr 10, 2023 |
| ASRock        | X570 Pro4                   | Desktop     | [feb08fab62](https://linux-hardware.org/?probe=feb08fab62) | Apr 09, 2023 |
| Gateway       | M-6812M                     | Notebook    | [6101b79a06](https://linux-hardware.org/?probe=6101b79a06) | Apr 08, 2023 |
| eMachines     | EL1852G                     | Desktop     | [e9dde876e9](https://linux-hardware.org/?probe=e9dde876e9) | Apr 08, 2023 |
| Samsung       | RV415/RV515                 | Notebook    | [fe77afbdfa](https://linux-hardware.org/?probe=fe77afbdfa) | Apr 07, 2023 |
| HP            | ProBook 6360b               | Notebook    | [bfa6c44b14](https://linux-hardware.org/?probe=bfa6c44b14) | Apr 07, 2023 |
| HP            | 895C                        | Desktop     | [27de3e2244](https://linux-hardware.org/?probe=27de3e2244) | Apr 06, 2023 |
| HP            | 895C                        | Desktop     | [3c87e6de19](https://linux-hardware.org/?probe=3c87e6de19) | Apr 05, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [fb0dc3cc20](https://linux-hardware.org/?probe=fb0dc3cc20) | Apr 05, 2023 |
| Acer          | Aspire 3680                 | Notebook    | [b5511d9060](https://linux-hardware.org/?probe=b5511d9060) | Apr 05, 2023 |
| HP            | 8522 A01                    | Mini pc     | [28b79ea28b](https://linux-hardware.org/?probe=28b79ea28b) | Apr 04, 2023 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [f17cf21fbe](https://linux-hardware.org/?probe=f17cf21fbe) | Apr 04, 2023 |
| Apple         | MacBookPro10,2              | Notebook    | [ad5d8f611a](https://linux-hardware.org/?probe=ad5d8f611a) | Apr 04, 2023 |
| Notebook      | L140PU                      | Notebook    | [628319771e](https://linux-hardware.org/?probe=628319771e) | Apr 04, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [9da88b2a33](https://linux-hardware.org/?probe=9da88b2a33) | Apr 04, 2023 |
| HP            | 1850                        | Desktop     | [04243d9db8](https://linux-hardware.org/?probe=04243d9db8) | Apr 03, 2023 |
| HP            | 1850                        | Desktop     | [62b8f8056b](https://linux-hardware.org/?probe=62b8f8056b) | Apr 03, 2023 |
| Sony          | VPCF236FM                   | Notebook    | [d02623453c](https://linux-hardware.org/?probe=d02623453c) | Apr 03, 2023 |
| Valve         | Jupiter                     | Notebook    | [7a6dcc077f](https://linux-hardware.org/?probe=7a6dcc077f) | Apr 03, 2023 |
| HP            | Unknown                     | Notebook    | [bd783cf180](https://linux-hardware.org/?probe=bd783cf180) | Apr 03, 2023 |
| HP            | 2000                        | Notebook    | [3fffec7875](https://linux-hardware.org/?probe=3fffec7875) | Apr 03, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [a225e27910](https://linux-hardware.org/?probe=a225e27910) | Apr 03, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [63d38ddebf](https://linux-hardware.org/?probe=63d38ddebf) | Apr 02, 2023 |
| Gateway       | ZX6900                      | All in one  | [83a5f64b3f](https://linux-hardware.org/?probe=83a5f64b3f) | Apr 02, 2023 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [5b3fcb351b](https://linux-hardware.org/?probe=5b3fcb351b) | Apr 02, 2023 |
| Dell          | System XPS L502X            | Notebook    | [2ed08c70a9](https://linux-hardware.org/?probe=2ed08c70a9) | Apr 01, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [111eeac3b3](https://linux-hardware.org/?probe=111eeac3b3) | Apr 01, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [2fcab6a925](https://linux-hardware.org/?probe=2fcab6a925) | Apr 01, 2023 |
| ASUSTek       | PRIME B550M-A AC            | Desktop     | [2cc7a15de5](https://linux-hardware.org/?probe=2cc7a15de5) | Apr 01, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [f8e723a8dc](https://linux-hardware.org/?probe=f8e723a8dc) | Mar 31, 2023 |
| Gigabyte      | B460M AORUS ELITE           | Desktop     | [87145cd4b2](https://linux-hardware.org/?probe=87145cd4b2) | Mar 31, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [4693b65922](https://linux-hardware.org/?probe=4693b65922) | Mar 31, 2023 |
| EVOO          | EVC156-1                    | Notebook    | [8e665ae8b2](https://linux-hardware.org/?probe=8e665ae8b2) | Mar 31, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [f5db7a6030](https://linux-hardware.org/?probe=f5db7a6030) | Mar 30, 2023 |
| HP            | Notebook                    | Notebook    | [e631e8e62a](https://linux-hardware.org/?probe=e631e8e62a) | Mar 29, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [31d94ffb5f](https://linux-hardware.org/?probe=31d94ffb5f) | Mar 29, 2023 |
| Apple         | MacBookPro8,3               | Notebook    | [90fadbf903](https://linux-hardware.org/?probe=90fadbf903) | Mar 28, 2023 |
| Dell          | 073MMW A02                  | Desktop     | [311057a095](https://linux-hardware.org/?probe=311057a095) | Mar 28, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [bce7f8b531](https://linux-hardware.org/?probe=bce7f8b531) | Mar 27, 2023 |
| Alienware     | 17 R4                       | Notebook    | [4a61d300b5](https://linux-hardware.org/?probe=4a61d300b5) | Mar 27, 2023 |
| Lenovo        | IdeaPad Y910-17ISK 80V1     | Notebook    | [5e4e7975c1](https://linux-hardware.org/?probe=5e4e7975c1) | Mar 26, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [4cc097dbcf](https://linux-hardware.org/?probe=4cc097dbcf) | Mar 26, 2023 |
| Toshiba       | Satellite C845D             | Notebook    | [32341bde2a](https://linux-hardware.org/?probe=32341bde2a) | Mar 26, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [c47ec8c99a](https://linux-hardware.org/?probe=c47ec8c99a) | Mar 26, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [61897b32de](https://linux-hardware.org/?probe=61897b32de) | Mar 25, 2023 |
| American M... | XA133PR110                  | Notebook    | [7e49d89ca8](https://linux-hardware.org/?probe=7e49d89ca8) | Mar 25, 2023 |
| Biostar       | A10N-9630E                  | Desktop     | [46af7d1f6d](https://linux-hardware.org/?probe=46af7d1f6d) | Mar 25, 2023 |
| ASUSTek       | N56VJ                       | Notebook    | [da2c5d6ff1](https://linux-hardware.org/?probe=da2c5d6ff1) | Mar 24, 2023 |
| HP            | Unknown                     | Notebook    | [c27dcda931](https://linux-hardware.org/?probe=c27dcda931) | Mar 24, 2023 |
| Gigabyte      | GA-880GM-USB3               | Desktop     | [e6219dd355](https://linux-hardware.org/?probe=e6219dd355) | Mar 24, 2023 |
| Dell          | Inspiron 7559               | Notebook    | [51aab276a2](https://linux-hardware.org/?probe=51aab276a2) | Mar 23, 2023 |
| MSI           | B360M PRO-VH                | Desktop     | [2706ed39b7](https://linux-hardware.org/?probe=2706ed39b7) | Mar 23, 2023 |
| ASUSTek       | X202EP                      | Notebook    | [5cc1f3216b](https://linux-hardware.org/?probe=5cc1f3216b) | Mar 23, 2023 |
| HP            | Unknown                     | Notebook    | [913aa678bf](https://linux-hardware.org/?probe=913aa678bf) | Mar 23, 2023 |
| Lenovo        | Yoga 500-14IBD 80N4         | Notebook    | [f364402e8a](https://linux-hardware.org/?probe=f364402e8a) | Mar 23, 2023 |
| HONOR         | BBR-WAX9                    | Notebook    | [b16e6324ed](https://linux-hardware.org/?probe=b16e6324ed) | Mar 22, 2023 |
| Dell          | G15 5511                    | Notebook    | [6d71997e08](https://linux-hardware.org/?probe=6d71997e08) | Mar 21, 2023 |
| Dell          | G15 5510                    | Notebook    | [3ddfc82bcd](https://linux-hardware.org/?probe=3ddfc82bcd) | Mar 21, 2023 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [7ccc7e9ae1](https://linux-hardware.org/?probe=7ccc7e9ae1) | Mar 21, 2023 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [4544e68d4a](https://linux-hardware.org/?probe=4544e68d4a) | Mar 21, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [8a70a156a4](https://linux-hardware.org/?probe=8a70a156a4) | Mar 21, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [6dc3256710](https://linux-hardware.org/?probe=6dc3256710) | Mar 21, 2023 |
| HP            | Unknown                     | Notebook    | [66723d18e0](https://linux-hardware.org/?probe=66723d18e0) | Mar 21, 2023 |
| Acer          | Aspire 5253                 | Notebook    | [56b1138062](https://linux-hardware.org/?probe=56b1138062) | Mar 21, 2023 |
| Acer          | Aspire 5253                 | Notebook    | [1fe782c379](https://linux-hardware.org/?probe=1fe782c379) | Mar 21, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [417d3cf9b7](https://linux-hardware.org/?probe=417d3cf9b7) | Mar 19, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [cb27b0fbaf](https://linux-hardware.org/?probe=cb27b0fbaf) | Mar 19, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [b939c61b5a](https://linux-hardware.org/?probe=b939c61b5a) | Mar 18, 2023 |
| Biostar       | A10N-9630E                  | Desktop     | [a38995d817](https://linux-hardware.org/?probe=a38995d817) | Mar 18, 2023 |
| Lenovo        | G40-80 80E4                 | Notebook    | [70b2fab92b](https://linux-hardware.org/?probe=70b2fab92b) | Mar 17, 2023 |
| Lenovo        | ThinkPad A485 20MVS0C300    | Notebook    | [70812fb9c8](https://linux-hardware.org/?probe=70812fb9c8) | Mar 17, 2023 |
| Dell          | 0V52N7 A02                  | Server      | [f22446cb1d](https://linux-hardware.org/?probe=f22446cb1d) | Mar 16, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [40c232c45d](https://linux-hardware.org/?probe=40c232c45d) | Mar 16, 2023 |
| ASUSTek       | Z10PE-D16 WS                | Server      | [74269b72b0](https://linux-hardware.org/?probe=74269b72b0) | Mar 15, 2023 |
| Toshiba       | Satellite P55t-B            | Notebook    | [7bd981d445](https://linux-hardware.org/?probe=7bd981d445) | Mar 15, 2023 |
| ASUSTek       | Q525UAR                     | Convertible | [42443a4950](https://linux-hardware.org/?probe=42443a4950) | Mar 14, 2023 |
| Lenovo        | ThinkPad A485 20MVS0C300    | Notebook    | [f3dd1409f6](https://linux-hardware.org/?probe=f3dd1409f6) | Mar 14, 2023 |
| ASUSTek       | Q525UAR                     | Convertible | [5bd1e69a10](https://linux-hardware.org/?probe=5bd1e69a10) | Mar 14, 2023 |
| HUAWEI        | NBM-WXX9                    | Notebook    | [27b710cd68](https://linux-hardware.org/?probe=27b710cd68) | Mar 12, 2023 |
| Dell          | Inspiron 5593               | Notebook    | [631b554e46](https://linux-hardware.org/?probe=631b554e46) | Mar 12, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [fd63e92774](https://linux-hardware.org/?probe=fd63e92774) | Mar 12, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [6a0426cb65](https://linux-hardware.org/?probe=6a0426cb65) | Mar 12, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [f91bf005b0](https://linux-hardware.org/?probe=f91bf005b0) | Mar 11, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [158d246d65](https://linux-hardware.org/?probe=158d246d65) | Mar 11, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [e2b7d998d8](https://linux-hardware.org/?probe=e2b7d998d8) | Mar 11, 2023 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [2e94546c02](https://linux-hardware.org/?probe=2e94546c02) | Mar 11, 2023 |
| Acer          | Aspire R3-131T              | Notebook    | [94435f58ed](https://linux-hardware.org/?probe=94435f58ed) | Mar 11, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [9535f3676b](https://linux-hardware.org/?probe=9535f3676b) | Mar 10, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [fca941c098](https://linux-hardware.org/?probe=fca941c098) | Mar 10, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [e770c2f24c](https://linux-hardware.org/?probe=e770c2f24c) | Mar 10, 2023 |
| Samsung       | R430/R480/R440              | Notebook    | [cdb2525b51](https://linux-hardware.org/?probe=cdb2525b51) | Mar 10, 2023 |
| Dell          | G3 3500                     | Notebook    | [5cfed5bee9](https://linux-hardware.org/?probe=5cfed5bee9) | Mar 10, 2023 |
| HP            | Pavilion dv4                | Notebook    | [79a8c505ef](https://linux-hardware.org/?probe=79a8c505ef) | Mar 09, 2023 |
| Gigabyte      | GA-MA69VM-S2                | Desktop     | [c81f97ee71](https://linux-hardware.org/?probe=c81f97ee71) | Mar 09, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [b7fd2dfa30](https://linux-hardware.org/?probe=b7fd2dfa30) | Mar 09, 2023 |
| Dell          | 0HR330                      | Desktop     | [314bd7b2be](https://linux-hardware.org/?probe=314bd7b2be) | Mar 08, 2023 |
| Lenovo        | ThinkCentre M91p 4524CB9    | Desktop     | [a56b16b410](https://linux-hardware.org/?probe=a56b16b410) | Mar 08, 2023 |
| Dell          | 0HR330                      | Desktop     | [a652a631f1](https://linux-hardware.org/?probe=a652a631f1) | Mar 08, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | Notebook    | [d677609a51](https://linux-hardware.org/?probe=d677609a51) | Mar 07, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [ade979391f](https://linux-hardware.org/?probe=ade979391f) | Mar 07, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [67d9219fc2](https://linux-hardware.org/?probe=67d9219fc2) | Mar 07, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [780dc15bcc](https://linux-hardware.org/?probe=780dc15bcc) | Mar 06, 2023 |
| Dell          | 0VRWRC A00                  | Desktop     | [4810cd01e3](https://linux-hardware.org/?probe=4810cd01e3) | Mar 06, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f163816260](https://linux-hardware.org/?probe=f163816260) | Mar 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [6f7e8084e5](https://linux-hardware.org/?probe=6f7e8084e5) | Mar 04, 2023 |
| Biostar       | A10N-9630E                  | Desktop     | [e1bd95af21](https://linux-hardware.org/?probe=e1bd95af21) | Mar 03, 2023 |
| HP            | ProBook 6360b               | Notebook    | [8b6826988f](https://linux-hardware.org/?probe=8b6826988f) | Mar 03, 2023 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | Notebook    | [c3113c9da6](https://linux-hardware.org/?probe=c3113c9da6) | Mar 02, 2023 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | Notebook    | [73efff8199](https://linux-hardware.org/?probe=73efff8199) | Mar 02, 2023 |
| Dell          | 073MMW A02                  | Desktop     | [5915c17b3a](https://linux-hardware.org/?probe=5915c17b3a) | Mar 01, 2023 |
| Dell          | 073MMW A02                  | Desktop     | [e3ba0ef4b7](https://linux-hardware.org/?probe=e3ba0ef4b7) | Mar 01, 2023 |
| Gigabyte      | Z77X-UP4 TH                 | Desktop     | [b80cb49656](https://linux-hardware.org/?probe=b80cb49656) | Mar 01, 2023 |
| HP            | Pavilion 14                 | Notebook    | [ae0e65f5d1](https://linux-hardware.org/?probe=ae0e65f5d1) | Feb 28, 2023 |
| Dell          | Latitude E7270              | Notebook    | [2718026d03](https://linux-hardware.org/?probe=2718026d03) | Feb 28, 2023 |
| Dell          | Latitude E7450              | Notebook    | [0e5fe9d2a7](https://linux-hardware.org/?probe=0e5fe9d2a7) | Feb 28, 2023 |
| Gigabyte      | Z97M-D3H                    | Desktop     | [d93d9bff7f](https://linux-hardware.org/?probe=d93d9bff7f) | Feb 27, 2023 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | Notebook    | [d6e0c6c0ac](https://linux-hardware.org/?probe=d6e0c6c0ac) | Feb 26, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [f589c3687b](https://linux-hardware.org/?probe=f589c3687b) | Feb 26, 2023 |
| Dell          | 0HR330                      | Desktop     | [9110acd156](https://linux-hardware.org/?probe=9110acd156) | Feb 26, 2023 |
| HP            | Pavilion 14                 | Notebook    | [c9b9f213b5](https://linux-hardware.org/?probe=c9b9f213b5) | Feb 26, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [8a2a361aff](https://linux-hardware.org/?probe=8a2a361aff) | Feb 26, 2023 |
| Lenovo        | B40-45 20394                | Notebook    | [8472ed364a](https://linux-hardware.org/?probe=8472ed364a) | Feb 26, 2023 |
| HUAWEI        | WRT-WX9                     | Notebook    | [d49316c5e8](https://linux-hardware.org/?probe=d49316c5e8) | Feb 25, 2023 |
| Quanta        | 2AC7 011                    | Desktop     | [3505fadb68](https://linux-hardware.org/?probe=3505fadb68) | Feb 25, 2023 |
| Alienware     | 17 R4                       | Notebook    | [bfeccbf9f3](https://linux-hardware.org/?probe=bfeccbf9f3) | Feb 25, 2023 |
| Acer          | Aspire X3990                | Desktop     | [c83e31d66b](https://linux-hardware.org/?probe=c83e31d66b) | Feb 25, 2023 |
| Acer          | Aspire X3990                | Desktop     | [4be9f68049](https://linux-hardware.org/?probe=4be9f68049) | Feb 25, 2023 |
| Valve         | Jupiter                     | Notebook    | [0ec37b6ef2](https://linux-hardware.org/?probe=0ec37b6ef2) | Feb 25, 2023 |
| ASRock        | FM2A58M-VG3+ R2.0           | Desktop     | [92ac86c31b](https://linux-hardware.org/?probe=92ac86c31b) | Feb 25, 2023 |
| Chuwi         | HeroBook Air                | Notebook    | [8daed679c2](https://linux-hardware.org/?probe=8daed679c2) | Feb 24, 2023 |
| ASUSTek       | PRIME B460M-A R2.0          | Desktop     | [0ccac8edb4](https://linux-hardware.org/?probe=0ccac8edb4) | Feb 24, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [bfd3019210](https://linux-hardware.org/?probe=bfd3019210) | Feb 22, 2023 |
| Dell          | Latitude E6430              | Notebook    | [80c9785ef0](https://linux-hardware.org/?probe=80c9785ef0) | Feb 21, 2023 |
| HP            | 158B                        | Desktop     | [4d6199df48](https://linux-hardware.org/?probe=4d6199df48) | Feb 20, 2023 |
| Toshiba       | Satellite C50D-A            | Notebook    | [3e9201a0fe](https://linux-hardware.org/?probe=3e9201a0fe) | Feb 20, 2023 |
| Gigabyte      | B460 AORUS PRO AC           | Desktop     | [dc6b25dcef](https://linux-hardware.org/?probe=dc6b25dcef) | Feb 19, 2023 |
| HP            | Pavilion g6                 | Notebook    | [2b4de6efbe](https://linux-hardware.org/?probe=2b4de6efbe) | Feb 18, 2023 |
| Gigabyte      | GA-MA69VM-S2                | Desktop     | [b01f6d7a1f](https://linux-hardware.org/?probe=b01f6d7a1f) | Feb 17, 2023 |
| Biostar       | B450MH                      | Desktop     | [963e90387d](https://linux-hardware.org/?probe=963e90387d) | Feb 17, 2023 |
| ASRock        | FM2A58M-VG3+ R2.0           | Desktop     | [27501ca342](https://linux-hardware.org/?probe=27501ca342) | Feb 17, 2023 |
| Dell          | Studio 1558                 | Notebook    | [4a2f0524b9](https://linux-hardware.org/?probe=4a2f0524b9) | Feb 17, 2023 |
| Lenovo        | ThinkCentre M91 4518E4S     | Desktop     | [91b1fb7e03](https://linux-hardware.org/?probe=91b1fb7e03) | Feb 16, 2023 |
| Dell          | G15 5515                    | Notebook    | [17ff15f50e](https://linux-hardware.org/?probe=17ff15f50e) | Feb 16, 2023 |
| Dell          | Latitude E7440              | Notebook    | [86f8d34ba7](https://linux-hardware.org/?probe=86f8d34ba7) | Feb 16, 2023 |
| Biostar       | B450MH                      | Desktop     | [34591a7516](https://linux-hardware.org/?probe=34591a7516) | Feb 15, 2023 |
| Biostar       | B450MH                      | Desktop     | [12142a9f86](https://linux-hardware.org/?probe=12142a9f86) | Feb 15, 2023 |
| Lenovo        | ThinkPad A485 20MVS0C300    | Notebook    | [269420c3fe](https://linux-hardware.org/?probe=269420c3fe) | Feb 15, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [de592b6218](https://linux-hardware.org/?probe=de592b6218) | Feb 14, 2023 |
| Dell          | Latitude E7270              | Notebook    | [03199b7612](https://linux-hardware.org/?probe=03199b7612) | Feb 14, 2023 |
| Lenovo        | 30FD SDK0J40697 WIN 3305... | Desktop     | [b6b09f6455](https://linux-hardware.org/?probe=b6b09f6455) | Feb 14, 2023 |
| HP            | Laptop 15-da2xxx            | Notebook    | [41bf5d50f8](https://linux-hardware.org/?probe=41bf5d50f8) | Feb 14, 2023 |
| Dell          | Inspiron 5555               | Notebook    | [395077145c](https://linux-hardware.org/?probe=395077145c) | Feb 13, 2023 |
| HP            | 1493                        | Desktop     | [641106a383](https://linux-hardware.org/?probe=641106a383) | Feb 13, 2023 |
| ZOTAC         | ZBOX                        | Mini pc     | [762cb319c6](https://linux-hardware.org/?probe=762cb319c6) | Feb 13, 2023 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [cfeb6479d1](https://linux-hardware.org/?probe=cfeb6479d1) | Feb 13, 2023 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [6d428a3fb9](https://linux-hardware.org/?probe=6d428a3fb9) | Feb 13, 2023 |
| Apple         | MacBookPro10,2              | Notebook    | [4a6ea9bd99](https://linux-hardware.org/?probe=4a6ea9bd99) | Feb 12, 2023 |
| Apple         | MacBookPro10,2              | Notebook    | [063d6eb482](https://linux-hardware.org/?probe=063d6eb482) | Feb 12, 2023 |
| Dell          | Latitude E7270              | Notebook    | [c684709755](https://linux-hardware.org/?probe=c684709755) | Feb 11, 2023 |
| HP            | Laptop 15-da2xxx            | Notebook    | [200150e4e3](https://linux-hardware.org/?probe=200150e4e3) | Feb 10, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [d5bb6335d4](https://linux-hardware.org/?probe=d5bb6335d4) | Feb 08, 2023 |
| ZOTAC         | ZBOX                        | Mini pc     | [04b52cc9f4](https://linux-hardware.org/?probe=04b52cc9f4) | Feb 08, 2023 |
| ZOTAC         | ZBOX                        | Mini pc     | [4206b31f46](https://linux-hardware.org/?probe=4206b31f46) | Feb 08, 2023 |
| HP            | 240 G3                      | Notebook    | [e3a0318824](https://linux-hardware.org/?probe=e3a0318824) | Feb 07, 2023 |
| HP            | 1905                        | Desktop     | [a442e1de06](https://linux-hardware.org/?probe=a442e1de06) | Feb 07, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [da8dac3c03](https://linux-hardware.org/?probe=da8dac3c03) | Feb 07, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [f7c5e9e498](https://linux-hardware.org/?probe=f7c5e9e498) | Feb 06, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [781dc9da09](https://linux-hardware.org/?probe=781dc9da09) | Feb 06, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [413341361a](https://linux-hardware.org/?probe=413341361a) | Feb 05, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [44aed7e81a](https://linux-hardware.org/?probe=44aed7e81a) | Feb 04, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [5acc007668](https://linux-hardware.org/?probe=5acc007668) | Feb 04, 2023 |
| HP            | 240 G3                      | Notebook    | [43e56d3ae5](https://linux-hardware.org/?probe=43e56d3ae5) | Feb 03, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [909d48ecda](https://linux-hardware.org/?probe=909d48ecda) | Feb 03, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [5b3fa12024](https://linux-hardware.org/?probe=5b3fa12024) | Feb 03, 2023 |
| HP            | 240 G3                      | Notebook    | [a977b66ced](https://linux-hardware.org/?probe=a977b66ced) | Feb 02, 2023 |
| HP            | 240 G3                      | Notebook    | [816a3f4b28](https://linux-hardware.org/?probe=816a3f4b28) | Feb 02, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [6546c6e279](https://linux-hardware.org/?probe=6546c6e279) | Feb 02, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [73230e9490](https://linux-hardware.org/?probe=73230e9490) | Feb 02, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [4f59d41c11](https://linux-hardware.org/?probe=4f59d41c11) | Feb 02, 2023 |
| ASUSTek       | N56VB                       | Notebook    | [d5b5c983c9](https://linux-hardware.org/?probe=d5b5c983c9) | Feb 02, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [cad4d19ab7](https://linux-hardware.org/?probe=cad4d19ab7) | Feb 02, 2023 |
| Apple         | MacBookPro15,2              | Notebook    | [7c17db143e](https://linux-hardware.org/?probe=7c17db143e) | Feb 01, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [13467e9e83](https://linux-hardware.org/?probe=13467e9e83) | Feb 01, 2023 |
| Dell          | Latitude 5430               | Notebook    | [2afa57d0fa](https://linux-hardware.org/?probe=2afa57d0fa) | Feb 01, 2023 |
| Gigabyte      | GA-MA69VM-S2                | Desktop     | [72dae43046](https://linux-hardware.org/?probe=72dae43046) | Feb 01, 2023 |
| Apple         | MacBookPro15,2              | Notebook    | [7612aba4cb](https://linux-hardware.org/?probe=7612aba4cb) | Jan 31, 2023 |
| Lenovo        | ThinkPad T430 2349A44       | Notebook    | [9f8528c5da](https://linux-hardware.org/?probe=9f8528c5da) | Jan 31, 2023 |
| Dell          | G15 5511                    | Notebook    | [36214ba4de](https://linux-hardware.org/?probe=36214ba4de) | Jan 30, 2023 |
| ASUSTek       | PRIME B550M-A AC            | Desktop     | [c11ff840dd](https://linux-hardware.org/?probe=c11ff840dd) | Jan 29, 2023 |
| Dell          | G15 5515                    | Notebook    | [1be125c3cd](https://linux-hardware.org/?probe=1be125c3cd) | Jan 29, 2023 |
| HP            | Laptop 15-da2xxx            | Notebook    | [8384a02b4b](https://linux-hardware.org/?probe=8384a02b4b) | Jan 28, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [1aa83fb987](https://linux-hardware.org/?probe=1aa83fb987) | Jan 28, 2023 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [fa464af5fb](https://linux-hardware.org/?probe=fa464af5fb) | Jan 27, 2023 |
| Chuwi         | UBook X                     | Tablet      | [3f983d6ce7](https://linux-hardware.org/?probe=3f983d6ce7) | Jan 27, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [edfd032f00](https://linux-hardware.org/?probe=edfd032f00) | Jan 26, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [75e92725f5](https://linux-hardware.org/?probe=75e92725f5) | Jan 26, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [c7d825c34c](https://linux-hardware.org/?probe=c7d825c34c) | Jan 26, 2023 |
| Dell          | 0773VG A00                  | Desktop     | [328dae4014](https://linux-hardware.org/?probe=328dae4014) | Jan 26, 2023 |
| AZW           | U59                         | Desktop     | [6d2b672b77](https://linux-hardware.org/?probe=6d2b672b77) | Jan 25, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [bd58d910f7](https://linux-hardware.org/?probe=bd58d910f7) | Jan 25, 2023 |
| Dell          | Latitude E5440              | Notebook    | [f8e7f1785b](https://linux-hardware.org/?probe=f8e7f1785b) | Jan 24, 2023 |
| PCChips       | P49G                        | Desktop     | [24a7d0e02b](https://linux-hardware.org/?probe=24a7d0e02b) | Jan 24, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [65b6391803](https://linux-hardware.org/?probe=65b6391803) | Jan 24, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [fd6d2ec3c2](https://linux-hardware.org/?probe=fd6d2ec3c2) | Jan 23, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [bf87467519](https://linux-hardware.org/?probe=bf87467519) | Jan 23, 2023 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [af23cdf7e9](https://linux-hardware.org/?probe=af23cdf7e9) | Jan 23, 2023 |
| ASRock        | N68-VGS3 FX                 | Desktop     | [d25d4580a9](https://linux-hardware.org/?probe=d25d4580a9) | Jan 23, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [57ed6980d4](https://linux-hardware.org/?probe=57ed6980d4) | Jan 22, 2023 |
| Lenovo        | ThinkPad T470s 20HGS27Y0... | Notebook    | [e1678320fc](https://linux-hardware.org/?probe=e1678320fc) | Jan 22, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | Notebook    | [0667ad7cee](https://linux-hardware.org/?probe=0667ad7cee) | Jan 22, 2023 |
| Lenovo        | 31900004 STD                | All in one  | [55c11b6b87](https://linux-hardware.org/?probe=55c11b6b87) | Jan 21, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [863666d76f](https://linux-hardware.org/?probe=863666d76f) | Jan 20, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [019527cd61](https://linux-hardware.org/?probe=019527cd61) | Jan 20, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [9732bb65cd](https://linux-hardware.org/?probe=9732bb65cd) | Jan 20, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [17bdbada47](https://linux-hardware.org/?probe=17bdbada47) | Jan 20, 2023 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | Desktop     | [0f21d67175](https://linux-hardware.org/?probe=0f21d67175) | Jan 20, 2023 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [4b76c154f3](https://linux-hardware.org/?probe=4b76c154f3) | Jan 20, 2023 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | Notebook    | [9c9279b845](https://linux-hardware.org/?probe=9c9279b845) | Jan 19, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [b48e8ac2ee](https://linux-hardware.org/?probe=b48e8ac2ee) | Jan 19, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W5... | Notebook    | [393e6cd6d2](https://linux-hardware.org/?probe=393e6cd6d2) | Jan 18, 2023 |
| Intel         | DG41RQ AAE54511-205         | Desktop     | [1125db7cfd](https://linux-hardware.org/?probe=1125db7cfd) | Jan 18, 2023 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [7be5d0d09b](https://linux-hardware.org/?probe=7be5d0d09b) | Jan 18, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [7e61f98275](https://linux-hardware.org/?probe=7e61f98275) | Jan 18, 2023 |
| ECS           | Iris8                       | Desktop     | [ed85f79aaa](https://linux-hardware.org/?probe=ed85f79aaa) | Jan 16, 2023 |
| Acer          | IAXBT-BL                    | All in one  | [ff4762d139](https://linux-hardware.org/?probe=ff4762d139) | Jan 15, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [5661d09dd0](https://linux-hardware.org/?probe=5661d09dd0) | Jan 15, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [d667bf6bb2](https://linux-hardware.org/?probe=d667bf6bb2) | Jan 15, 2023 |
| HUAWEI        | EMD-WXX                     | Notebook    | [3709c83303](https://linux-hardware.org/?probe=3709c83303) | Jan 15, 2023 |
| HUAWEI        | EMD-WXX                     | Notebook    | [6eeac14bb9](https://linux-hardware.org/?probe=6eeac14bb9) | Jan 15, 2023 |
| Gigabyte      | H410M H                     | Desktop     | [85605e8c5b](https://linux-hardware.org/?probe=85605e8c5b) | Jan 14, 2023 |
| Dell          | Latitude E6440              | Notebook    | [d04d05f246](https://linux-hardware.org/?probe=d04d05f246) | Jan 14, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [aade436557](https://linux-hardware.org/?probe=aade436557) | Jan 14, 2023 |
| Lenovo        | B490 20205                  | Notebook    | [14243e79d2](https://linux-hardware.org/?probe=14243e79d2) | Jan 13, 2023 |
| HP            | 2ADC                        | Desktop     | [69bb1386c0](https://linux-hardware.org/?probe=69bb1386c0) | Jan 13, 2023 |
| HP            | ProBook 4230s               | Notebook    | [63a87864b9](https://linux-hardware.org/?probe=63a87864b9) | Jan 12, 2023 |
| HP            | ProBook 4230s               | Notebook    | [9a6505c0aa](https://linux-hardware.org/?probe=9a6505c0aa) | Jan 12, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [64ec4b6816](https://linux-hardware.org/?probe=64ec4b6816) | Jan 12, 2023 |
| Lenovo        | ThinkPad P1 20MDCTO1WW      | Notebook    | [d859e0ff10](https://linux-hardware.org/?probe=d859e0ff10) | Jan 12, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [306315e4d8](https://linux-hardware.org/?probe=306315e4d8) | Jan 12, 2023 |
| Gateway       | M-6854m                     | Notebook    | [76f293b62b](https://linux-hardware.org/?probe=76f293b62b) | Jan 12, 2023 |
| Dell          | Precision M4400             | Notebook    | [27da7825fb](https://linux-hardware.org/?probe=27da7825fb) | Jan 12, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [8c1eb7fc02](https://linux-hardware.org/?probe=8c1eb7fc02) | Jan 11, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [9cd68b4513](https://linux-hardware.org/?probe=9cd68b4513) | Jan 11, 2023 |
| Sony          | VPCEH1AFX                   | Notebook    | [3f64681bc7](https://linux-hardware.org/?probe=3f64681bc7) | Jan 11, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [1058c3d279](https://linux-hardware.org/?probe=1058c3d279) | Jan 11, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [2132701432](https://linux-hardware.org/?probe=2132701432) | Jan 11, 2023 |
| Dell          | 0D28YY A00                  | Desktop     | [736f7a2f65](https://linux-hardware.org/?probe=736f7a2f65) | Jan 11, 2023 |
| MSI           | Boston                      | Desktop     | [00949f3199](https://linux-hardware.org/?probe=00949f3199) | Jan 10, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [04a9deb0c1](https://linux-hardware.org/?probe=04a9deb0c1) | Jan 10, 2023 |
| Valve         | Jupiter                     | Notebook    | [57b570af42](https://linux-hardware.org/?probe=57b570af42) | Jan 09, 2023 |
| ASUSTek       | Leonite2                    | Desktop     | [cf4fe3c8d7](https://linux-hardware.org/?probe=cf4fe3c8d7) | Jan 09, 2023 |
| Intel         | NUC11ATBC4 M53051-303       | Mini pc     | [fcc9b4bbcc](https://linux-hardware.org/?probe=fcc9b4bbcc) | Jan 09, 2023 |
| HP            | Pavilion 15                 | Notebook    | [2937882035](https://linux-hardware.org/?probe=2937882035) | Jan 08, 2023 |
| Notebook      | W9x0LU                      | Notebook    | [a81dd09b0c](https://linux-hardware.org/?probe=a81dd09b0c) | Jan 07, 2023 |
| HP            | 1497                        | Desktop     | [71550a0f21](https://linux-hardware.org/?probe=71550a0f21) | Jan 07, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f09e26eaa3](https://linux-hardware.org/?probe=f09e26eaa3) | Jan 07, 2023 |
| ASUSTek       | H61M-C                      | Desktop     | [494e552521](https://linux-hardware.org/?probe=494e552521) | Jan 07, 2023 |
| Gigabyte      | Z390 UD                     | Desktop     | [74859544a4](https://linux-hardware.org/?probe=74859544a4) | Jan 06, 2023 |
| HP            | Stream Laptop 11-y0XX       | Notebook    | [b40a3e32e9](https://linux-hardware.org/?probe=b40a3e32e9) | Jan 06, 2023 |
| HP            | Stream Laptop 11-y0XX       | Notebook    | [73db1ffcf6](https://linux-hardware.org/?probe=73db1ffcf6) | Jan 06, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [3245d27cb7](https://linux-hardware.org/?probe=3245d27cb7) | Jan 05, 2023 |
| Lenovo        | G580 20157                  | Notebook    | [c0199fa7bf](https://linux-hardware.org/?probe=c0199fa7bf) | Jan 05, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [c64a1198cd](https://linux-hardware.org/?probe=c64a1198cd) | Jan 04, 2023 |
| Lenovo        | ThinkPad P1 20MDCTO1WW      | Notebook    | [23bfcb7f4c](https://linux-hardware.org/?probe=23bfcb7f4c) | Jan 04, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [f7bf32067f](https://linux-hardware.org/?probe=f7bf32067f) | Jan 03, 2023 |
| Lenovo        | ThinkPad T590 20N5S2NC1V    | Notebook    | [c621679405](https://linux-hardware.org/?probe=c621679405) | Jan 03, 2023 |
| Dell          | 0MM599                      | Desktop     | [95763443e3](https://linux-hardware.org/?probe=95763443e3) | Jan 03, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [3365055862](https://linux-hardware.org/?probe=3365055862) | Jan 02, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [45184e1f70](https://linux-hardware.org/?probe=45184e1f70) | Jan 02, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [8c76b9ad8e](https://linux-hardware.org/?probe=8c76b9ad8e) | Jan 01, 2023 |
| HP            | Laptop 15-da2xxx            | Notebook    | [a96e5b892b](https://linux-hardware.org/?probe=a96e5b892b) | Jan 01, 2023 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | Notebook    | [0179007813](https://linux-hardware.org/?probe=0179007813) | Jan 01, 2023 |
| ASUSTek       | E410                        | Desktop     | [d284787f09](https://linux-hardware.org/?probe=d284787f09) | Jan 01, 2023 |
| ASUSTek       | E410                        | Desktop     | [4dabf86358](https://linux-hardware.org/?probe=4dabf86358) | Jan 01, 2023 |
| Chuwi         | UBook X                     | Tablet      | [cc5cc14d77](https://linux-hardware.org/?probe=cc5cc14d77) | Jan 01, 2023 |
| Chuwi         | UBook X                     | Tablet      | [735746822f](https://linux-hardware.org/?probe=735746822f) | Jan 01, 2023 |
| Acer          | Aspire A114-33              | Notebook    | [bba53b0159](https://linux-hardware.org/?probe=bba53b0159) | Jan 01, 2023 |
| Toshiba       | Satellite A305D             | Notebook    | [b85a377462](https://linux-hardware.org/?probe=b85a377462) | Dec 31, 2022 |
| ASUSTek       | E410                        | Desktop     | [98e0007b65](https://linux-hardware.org/?probe=98e0007b65) | Dec 31, 2022 |
| Acer          | Aspire R7-371T              | Notebook    | [057e717cb7](https://linux-hardware.org/?probe=057e717cb7) | Dec 30, 2022 |
| HP            | 240 G7 Notebook PC          | Notebook    | [414db30bff](https://linux-hardware.org/?probe=414db30bff) | Dec 30, 2022 |
| ASUSTek       | N56VB                       | Notebook    | [6201ddc028](https://linux-hardware.org/?probe=6201ddc028) | Dec 30, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [41a9d09ec8](https://linux-hardware.org/?probe=41a9d09ec8) | Dec 29, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [51f9de5f53](https://linux-hardware.org/?probe=51f9de5f53) | Dec 29, 2022 |
| GPU Compan... | GWNR71517                   | Notebook    | [bc9e41ea0d](https://linux-hardware.org/?probe=bc9e41ea0d) | Dec 29, 2022 |
| GPU Compan... | GWNR71517                   | Notebook    | [65f3d3dd65](https://linux-hardware.org/?probe=65f3d3dd65) | Dec 29, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [34804f8a34](https://linux-hardware.org/?probe=34804f8a34) | Dec 29, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [47f95e17c5](https://linux-hardware.org/?probe=47f95e17c5) | Dec 28, 2022 |
| Lanix         | P55M-UD2 LNXACT             | Desktop     | [5575ce838c](https://linux-hardware.org/?probe=5575ce838c) | Dec 28, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [069f0917d6](https://linux-hardware.org/?probe=069f0917d6) | Dec 28, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [0f15c0b801](https://linux-hardware.org/?probe=0f15c0b801) | Dec 28, 2022 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [e020678b51](https://linux-hardware.org/?probe=e020678b51) | Dec 28, 2022 |
| Dell          | 0M017G A00                  | Desktop     | [5c41315695](https://linux-hardware.org/?probe=5c41315695) | Dec 27, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [8e2393e7b4](https://linux-hardware.org/?probe=8e2393e7b4) | Dec 26, 2022 |
| Acer          | Aspire E1-522               | Notebook    | [8bf37cf82d](https://linux-hardware.org/?probe=8bf37cf82d) | Dec 26, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d90a9cdcd3](https://linux-hardware.org/?probe=d90a9cdcd3) | Dec 26, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [fc0eac877c](https://linux-hardware.org/?probe=fc0eac877c) | Dec 26, 2022 |
| HP            | ProBook 6470b               | Notebook    | [880f8d51d3](https://linux-hardware.org/?probe=880f8d51d3) | Dec 24, 2022 |
| HP            | ProBook 6470b               | Notebook    | [315e362044](https://linux-hardware.org/?probe=315e362044) | Dec 24, 2022 |
| Google        | Bobba360                    | Notebook    | [bdad461cec](https://linux-hardware.org/?probe=bdad461cec) | Dec 23, 2022 |
| Lenovo        | ThinkBook 14s Yoga G2 IA... | Convertible | [3ea5c420b1](https://linux-hardware.org/?probe=3ea5c420b1) | Dec 23, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [77e30fee83](https://linux-hardware.org/?probe=77e30fee83) | Dec 23, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [bc1c9956b3](https://linux-hardware.org/?probe=bc1c9956b3) | Dec 23, 2022 |
| Schenker      | VIA 15 Pro                  | Notebook    | [b1a40c91d2](https://linux-hardware.org/?probe=b1a40c91d2) | Dec 22, 2022 |
| Schenker      | VIA 15 Pro                  | Notebook    | [75efe6fb52](https://linux-hardware.org/?probe=75efe6fb52) | Dec 22, 2022 |
| Dell          | Inspiron 7559               | Notebook    | [52cf8ddc0f](https://linux-hardware.org/?probe=52cf8ddc0f) | Dec 22, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [482001243a](https://linux-hardware.org/?probe=482001243a) | Dec 22, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [95a82bb7e0](https://linux-hardware.org/?probe=95a82bb7e0) | Dec 22, 2022 |
| ASUSTek       | H110M-E/M.2                 | Desktop     | [82584d7e83](https://linux-hardware.org/?probe=82584d7e83) | Dec 20, 2022 |
| Biostar       | A10N-9630E                  | Desktop     | [bc183b5af7](https://linux-hardware.org/?probe=bc183b5af7) | Dec 20, 2022 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [6fdcb5b8b4](https://linux-hardware.org/?probe=6fdcb5b8b4) | Dec 20, 2022 |
| Acer          | Aspire A515-51              | Notebook    | [29af4c3712](https://linux-hardware.org/?probe=29af4c3712) | Dec 20, 2022 |
| Biostar       | A10N-9630E                  | Desktop     | [65c72d297e](https://linux-hardware.org/?probe=65c72d297e) | Dec 19, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [b5c4e6cf61](https://linux-hardware.org/?probe=b5c4e6cf61) | Dec 19, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [743b2176f1](https://linux-hardware.org/?probe=743b2176f1) | Dec 19, 2022 |
| Google        | Coral                       | Notebook    | [8e2407d4b2](https://linux-hardware.org/?probe=8e2407d4b2) | Dec 19, 2022 |
| Lenovo        | Y720-15IKB 80VR             | Notebook    | [96dcb47ba1](https://linux-hardware.org/?probe=96dcb47ba1) | Dec 18, 2022 |
| Dell          | 0M858N A00                  | Desktop     | [e46a95080d](https://linux-hardware.org/?probe=e46a95080d) | Dec 18, 2022 |
| Acer          | Aspire A515-46              | Notebook    | [fab35bfa42](https://linux-hardware.org/?probe=fab35bfa42) | Dec 18, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7adfddc31e](https://linux-hardware.org/?probe=7adfddc31e) | Dec 16, 2022 |
| Biostar       | A10N-9630E                  | Desktop     | [5dce29a057](https://linux-hardware.org/?probe=5dce29a057) | Dec 16, 2022 |
| Biostar       | A10N-9630E                  | Desktop     | [702d391e89](https://linux-hardware.org/?probe=702d391e89) | Dec 16, 2022 |
| Dell          | 0RW203                      | Desktop     | [2f5bede488](https://linux-hardware.org/?probe=2f5bede488) | Dec 16, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [7c678e18cd](https://linux-hardware.org/?probe=7c678e18cd) | Dec 16, 2022 |
| Biostar       | A10N-9630E                  | Desktop     | [a884fddf53](https://linux-hardware.org/?probe=a884fddf53) | Dec 16, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [5c6f8cd52d](https://linux-hardware.org/?probe=5c6f8cd52d) | Dec 16, 2022 |
| Lenovo        | ThinkPad X240 20AMA40QLM    | Notebook    | [ec9133f05d](https://linux-hardware.org/?probe=ec9133f05d) | Dec 16, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [87603a034e](https://linux-hardware.org/?probe=87603a034e) | Dec 15, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [535643e246](https://linux-hardware.org/?probe=535643e246) | Dec 15, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [7d15ecff86](https://linux-hardware.org/?probe=7d15ecff86) | Dec 15, 2022 |
| Valve         | Jupiter                     | Notebook    | [f89644c711](https://linux-hardware.org/?probe=f89644c711) | Dec 15, 2022 |
| Biostar       | A10N-9630E                  | Desktop     | [b90f6a6980](https://linux-hardware.org/?probe=b90f6a6980) | Dec 14, 2022 |
| HP            | Laptop 15-da2xxx            | Notebook    | [cd64f27416](https://linux-hardware.org/?probe=cd64f27416) | Dec 14, 2022 |
| MSI           | GL75 Leopard 10SDK          | Notebook    | [03dc950ee5](https://linux-hardware.org/?probe=03dc950ee5) | Dec 14, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [b2d808ab85](https://linux-hardware.org/?probe=b2d808ab85) | Dec 14, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [0a564c9f0f](https://linux-hardware.org/?probe=0a564c9f0f) | Dec 14, 2022 |
| Acer          | Aspire ES1-531              | Notebook    | [36bd6688bb](https://linux-hardware.org/?probe=36bd6688bb) | Dec 14, 2022 |
| Acer          | Aspire ES1-531              | Notebook    | [ed5d274c1a](https://linux-hardware.org/?probe=ed5d274c1a) | Dec 14, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [5ea80edee8](https://linux-hardware.org/?probe=5ea80edee8) | Dec 14, 2022 |
| Alienware     | 15 R4                       | Notebook    | [f365266667](https://linux-hardware.org/?probe=f365266667) | Dec 14, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [14f87b8695](https://linux-hardware.org/?probe=14f87b8695) | Dec 13, 2022 |
| Toshiba       | TECRA A10                   | Notebook    | [760bda2b7d](https://linux-hardware.org/?probe=760bda2b7d) | Dec 13, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [469a37f1e4](https://linux-hardware.org/?probe=469a37f1e4) | Dec 12, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [bdddbb7807](https://linux-hardware.org/?probe=bdddbb7807) | Dec 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [4a5f657daf](https://linux-hardware.org/?probe=4a5f657daf) | Dec 12, 2022 |
| Toshiba       | Satellite L855              | Notebook    | [932d8fec2d](https://linux-hardware.org/?probe=932d8fec2d) | Dec 12, 2022 |
| Sony          | VGN-NS220TH                 | Notebook    | [29e1373be4](https://linux-hardware.org/?probe=29e1373be4) | Dec 11, 2022 |
| Sony          | VPCEE27FL                   | Notebook    | [dd2bc8b6ff](https://linux-hardware.org/?probe=dd2bc8b6ff) | Dec 10, 2022 |
| Dell          | Latitude E6420              | Notebook    | [acd81c73d0](https://linux-hardware.org/?probe=acd81c73d0) | Dec 09, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [38d274571d](https://linux-hardware.org/?probe=38d274571d) | Dec 09, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [1595cc246a](https://linux-hardware.org/?probe=1595cc246a) | Dec 09, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [94c151e95d](https://linux-hardware.org/?probe=94c151e95d) | Dec 09, 2022 |
| HP            | Pavilion dv5                | Notebook    | [cdd08235ff](https://linux-hardware.org/?probe=cdd08235ff) | Dec 09, 2022 |
| Acer          | TravelMate 5720             | Notebook    | [d0a54f621e](https://linux-hardware.org/?probe=d0a54f621e) | Dec 09, 2022 |
| GPU Compan... | GWNR71517                   | Notebook    | [148040d1fd](https://linux-hardware.org/?probe=148040d1fd) | Dec 09, 2022 |
| Acer          | TravelMate B117-M           | Notebook    | [00ff19b078](https://linux-hardware.org/?probe=00ff19b078) | Dec 08, 2022 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [4a41ed7fae](https://linux-hardware.org/?probe=4a41ed7fae) | Dec 07, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [3ab56a93d6](https://linux-hardware.org/?probe=3ab56a93d6) | Dec 07, 2022 |
| HP            | Pavilion dv6000 (RV009UA... | Notebook    | [6dcd661136](https://linux-hardware.org/?probe=6dcd661136) | Dec 05, 2022 |
| HP            | EliteBook x360 1040 G5      | Convertible | [02c80899f7](https://linux-hardware.org/?probe=02c80899f7) | Dec 05, 2022 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [a7f86279b6](https://linux-hardware.org/?probe=a7f86279b6) | Dec 04, 2022 |
| HP            | 15                          | Notebook    | [132fad5c38](https://linux-hardware.org/?probe=132fad5c38) | Dec 04, 2022 |
| Acer          | TravelMate B117-M           | Notebook    | [0b86a9c3b9](https://linux-hardware.org/?probe=0b86a9c3b9) | Dec 03, 2022 |
| HP            | Pavilion g4                 | Notebook    | [c6a564dce1](https://linux-hardware.org/?probe=c6a564dce1) | Dec 02, 2022 |
| Gigabyte      | GA-E6010N                   | Desktop     | [5fddeb1852](https://linux-hardware.org/?probe=5fddeb1852) | Dec 02, 2022 |
| MSI           | GE75 Raider 10SE            | Notebook    | [88245a0df3](https://linux-hardware.org/?probe=88245a0df3) | Nov 30, 2022 |
| HP            | Pavilion 14                 | Notebook    | [dedd30adc4](https://linux-hardware.org/?probe=dedd30adc4) | Nov 30, 2022 |
| Sony          | VGN-NS150FJ                 | Notebook    | [e675a19a27](https://linux-hardware.org/?probe=e675a19a27) | Nov 29, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [7ba1690c68](https://linux-hardware.org/?probe=7ba1690c68) | Nov 28, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | Notebook    | [a7b7f4f100](https://linux-hardware.org/?probe=a7b7f4f100) | Nov 25, 2022 |
| Lenovo        | ThinkPad X250 20CLS3AX05    | Notebook    | [c4a2ce46ca](https://linux-hardware.org/?probe=c4a2ce46ca) | Nov 24, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [240694e932](https://linux-hardware.org/?probe=240694e932) | Nov 23, 2022 |
| HP            | Notebook                    | Notebook    | [616c071073](https://linux-hardware.org/?probe=616c071073) | Nov 23, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [69d71bba75](https://linux-hardware.org/?probe=69d71bba75) | Nov 23, 2022 |
| Dell          | G3 3579                     | Notebook    | [7f4d27ea26](https://linux-hardware.org/?probe=7f4d27ea26) | Nov 23, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [9cbe89c328](https://linux-hardware.org/?probe=9cbe89c328) | Nov 22, 2022 |
| Unknown       | Unknown                     | Notebook    | [1de34b67e2](https://linux-hardware.org/?probe=1de34b67e2) | Nov 22, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [9a74fdb05b](https://linux-hardware.org/?probe=9a74fdb05b) | Nov 22, 2022 |
| Toshiba       | Satellite L45Dt-B           | Notebook    | [9cdcee20dc](https://linux-hardware.org/?probe=9cdcee20dc) | Nov 22, 2022 |
| OEM           | SHARKBAY JHS695             | Desktop     | [03c915bbd9](https://linux-hardware.org/?probe=03c915bbd9) | Nov 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [e9f2caddf6](https://linux-hardware.org/?probe=e9f2caddf6) | Nov 21, 2022 |
| MSI           | Stealth GS66 12UGS          | Notebook    | [ca3d88f38d](https://linux-hardware.org/?probe=ca3d88f38d) | Nov 21, 2022 |
| Intel         | JSL MRD                     | Desktop     | [469567b71f](https://linux-hardware.org/?probe=469567b71f) | Nov 20, 2022 |
| Dell          | Latitude E5440              | Notebook    | [f423bbe9b0](https://linux-hardware.org/?probe=f423bbe9b0) | Nov 19, 2022 |
| Dell          | 02YRK5 A02                  | Desktop     | [da08e08dec](https://linux-hardware.org/?probe=da08e08dec) | Nov 18, 2022 |
| TPV-INVENT... | 2AC6 A01                    | Desktop     | [04b3ba4242](https://linux-hardware.org/?probe=04b3ba4242) | Nov 18, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [41266bf8f0](https://linux-hardware.org/?probe=41266bf8f0) | Nov 18, 2022 |
| Dell          | Latitude E5440              | Notebook    | [0f98fe6066](https://linux-hardware.org/?probe=0f98fe6066) | Nov 18, 2022 |
| HP            | Laptop 15-da2xxx            | Notebook    | [e55a0e2ae1](https://linux-hardware.org/?probe=e55a0e2ae1) | Nov 18, 2022 |
| HP            | 2B3B                        | All in one  | [ae8821c392](https://linux-hardware.org/?probe=ae8821c392) | Nov 18, 2022 |
| HP            | 2B3B                        | All in one  | [84028321b8](https://linux-hardware.org/?probe=84028321b8) | Nov 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [c08218542c](https://linux-hardware.org/?probe=c08218542c) | Nov 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [4830cb0a27](https://linux-hardware.org/?probe=4830cb0a27) | Nov 17, 2022 |
| ASUSTek       | X556UQK                     | Notebook    | [fb33c2bdea](https://linux-hardware.org/?probe=fb33c2bdea) | Nov 16, 2022 |
| ASUSTek       | X556UQK                     | Notebook    | [b4f8d67230](https://linux-hardware.org/?probe=b4f8d67230) | Nov 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [f29e7d7659](https://linux-hardware.org/?probe=f29e7d7659) | Nov 16, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Mexico/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 276       | 10.25%  |
| Ubuntu 18.04       | 174       | 6.46%   |
| Ubuntu 22.04       | 157       | 5.83%   |
| OpenMandriva 4.2   | 91        | 3.38%   |
| OpenMandriva 4.3   | 86        | 3.19%   |
| Debian 11          | 79        | 2.93%   |
| Zorin 16           | 67        | 2.49%   |
| Fedora 38          | 59        | 2.19%   |
| Manjaro            | 51        | 1.89%   |
| KDE neon 20.04     | 51        | 1.89%   |
| Linux Mint 20.3    | 46        | 1.71%   |
| Pop!_OS 22.04      | 44        | 1.63%   |
| Fedora 36          | 43        | 1.6%    |
| Arch               | 34        | 1.26%   |
| Pop!_OS 20.04      | 33        | 1.23%   |
| OpenMandriva 23.03 | 33        | 1.23%   |
| ArcoLinux Rolling  | 33        | 1.23%   |
| Zorin 15           | 29        | 1.08%   |
| Ubuntu 19.10       | 26        | 0.97%   |
| Linux Mint 20      | 26        | 0.97%   |
| Fedora 35          | 26        | 0.97%   |
| Ubuntu 21.10       | 25        | 0.93%   |
| Linux Mint 21.1    | 25        | 0.93%   |
| Fedora 37          | 25        | 0.93%   |
| OpenMandriva 23.01 | 24        | 0.89%   |
| Linux Mint 19.3    | 24        | 0.89%   |
| Arch Rolling       | 24        | 0.89%   |
| Ubuntu 19.04       | 23        | 0.85%   |
| KDE neon 22.04     | 23        | 0.85%   |
| Debian 10          | 23        | 0.85%   |
| Ubuntu 20.10       | 22        | 0.82%   |
| Pop!_OS 21.04      | 22        | 0.82%   |
| Linux Mint 21      | 22        | 0.82%   |
| Ubuntu 22.10       | 21        | 0.78%   |
| Linux Mint 20.1    | 20        | 0.74%   |
| Kubuntu 20.04      | 20        | 0.74%   |
| Fedora 34          | 19        | 0.71%   |
| Xubuntu 18.04      | 18        | 0.67%   |
| Ubuntu 23.04       | 18        | 0.67%   |
| Xubuntu 20.04      | 17        | 0.63%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 753       | 29.28%  |
| OpenMandriva  | 252       | 9.8%    |
| Fedora        | 209       | 8.13%   |
| Linux Mint    | 204       | 7.93%   |
| Debian        | 119       | 4.63%   |
| Pop!_OS       | 114       | 4.43%   |
| Zorin         | 101       | 3.93%   |
| Manjaro       | 99        | 3.85%   |
| KDE neon      | 75        | 2.92%   |
| Arch          | 58        | 2.26%   |
| Kubuntu       | 53        | 2.06%   |
| Endless       | 48        | 1.87%   |
| Xubuntu       | 47        | 1.83%   |
| ROSA          | 46        | 1.79%   |
| Elementary    | 40        | 1.56%   |
| ArcoLinux     | 33        | 1.28%   |
| Kali          | 31        | 1.21%   |
| openSUSE      | 29        | 1.13%   |
| Lubuntu       | 17        | 0.66%   |
| Nobara        | 16        | 0.62%   |
| EndeavourOS   | 16        | 0.62%   |
| Clear Linux   | 15        | 0.58%   |
| LMDE          | 14        | 0.54%   |
| Gentoo        | 13        | 0.51%   |
| Ubuntu MATE   | 12        | 0.47%   |
| Ubuntu Budgie | 12        | 0.47%   |
| Ubuntu Unity  | 10        | 0.39%   |
| Parrot        | 10        | 0.39%   |
| CentOS        | 10        | 0.39%   |
| Xero          | 9         | 0.35%   |
| SteamOS       | 9         | 0.35%   |
| MX            | 9         | 0.35%   |
| Garuda Linux  | 8         | 0.31%   |
| Archcraft     | 6         | 0.23%   |
| Peppermint    | 5         | 0.19%   |
| Linux Lite    | 5         | 0.19%   |
| RHEL          | 4         | 0.16%   |
| Reborn OS     | 4         | 0.16%   |
| BlackPanther  | 4         | 0.16%   |
| UbuntuDDE     | 3         | 0.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 91        | 3.09%   |
| 5.16.7-desktop-1omv4003  | 80        | 2.72%   |
| 5.4.0-42-generic         | 44        | 1.49%   |
| 6.2.6-desktop-1omv2390   | 28        | 0.95%   |
| 5.4.0-58-generic         | 27        | 0.92%   |
| 5.15.0-56-generic        | 27        | 0.92%   |
| 6.1.1-desktop-1omv2290   | 22        | 0.75%   |
| 5.15.0-58-generic        | 22        | 0.75%   |
| 5.8.0-14-generic         | 21        | 0.71%   |
| 5.4.0-91-generic         | 20        | 0.68%   |
| 5.3.0-40-generic         | 20        | 0.68%   |
| 5.11.0-27-generic        | 19        | 0.65%   |
| 5.4.0-52-generic         | 18        | 0.61%   |
| 5.4.0-48-generic         | 18        | 0.61%   |
| 5.15.0-52-generic        | 18        | 0.61%   |
| 5.4.0-40-generic         | 17        | 0.58%   |
| 5.19.0-35-generic        | 17        | 0.58%   |
| 5.15.0-48-generic        | 17        | 0.58%   |
| 5.15.0-47-generic        | 17        | 0.58%   |
| 5.3.0-46-generic         | 16        | 0.54%   |
| 5.11.0-37-generic        | 16        | 0.54%   |
| 6.2.6-76060206-generic   | 15        | 0.51%   |
| 5.4.0-65-generic         | 15        | 0.51%   |
| 5.13.0-40-generic        | 15        | 0.51%   |
| 6.4.11-desktop-1omv2390  | 14        | 0.48%   |
| 5.4.0-54-generic         | 14        | 0.48%   |
| 5.4.0-37-generic         | 14        | 0.48%   |
| 5.3.0-42-generic         | 14        | 0.48%   |
| 5.3.0-28-generic         | 14        | 0.48%   |
| 5.19.0-38-generic        | 14        | 0.48%   |
| 5.19.0-43-generic        | 13        | 0.44%   |
| 5.13.0-39-generic        | 13        | 0.44%   |
| 5.11.0-7620-generic      | 13        | 0.44%   |
| 6.2.0-26-generic         | 12        | 0.41%   |
| 5.4.0-7642-generic       | 12        | 0.41%   |
| 5.4.0-33-generic         | 12        | 0.41%   |
| 5.15.0-78-generic        | 12        | 0.41%   |
| 5.15.0-60-generic        | 12        | 0.41%   |
| 5.15.0-46-generic        | 12        | 0.41%   |
| 5.15.0-43-generic        | 12        | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 394       | 14.2%   |
| 5.15.0  | 244       | 8.8%    |
| 5.11.0  | 134       | 4.83%   |
| 5.13.0  | 125       | 4.51%   |
| 5.8.0   | 120       | 4.33%   |
| 5.3.0   | 111       | 4%      |
| 4.15.0  | 111       | 4%      |
| 5.19.0  | 98        | 3.53%   |
| 5.10.14 | 91        | 3.28%   |
| 5.10.0  | 84        | 3.03%   |
| 5.16.7  | 81        | 2.92%   |
| 4.18.0  | 74        | 2.67%   |
| 5.0.0   | 72        | 2.6%    |
| 6.2.0   | 49        | 1.77%   |
| 6.2.6   | 43        | 1.55%   |
| 4.19.0  | 35        | 1.26%   |
| 6.1.1   | 29        | 1.05%   |
| 6.1.0   | 26        | 0.94%   |
| 6.4.11  | 22        | 0.79%   |
| 6.4.6   | 11        | 0.4%    |
| 6.0.12  | 11        | 0.4%    |
| 5.14.0  | 11        | 0.4%    |
| 6.2.15  | 10        | 0.36%   |
| 6.0.0   | 10        | 0.36%   |
| 5.17.5  | 10        | 0.36%   |
| 5.16.13 | 10        | 0.36%   |
| 6.3.5   | 9         | 0.32%   |
| 6.2.14  | 9         | 0.32%   |
| 4.9.20  | 9         | 0.32%   |
| 6.4.12  | 8         | 0.29%   |
| 6.4.4   | 7         | 0.25%   |
| 6.2.9   | 7         | 0.25%   |
| 6.0.11  | 7         | 0.25%   |
| 5.12.4  | 7         | 0.25%   |
| 5.11.12 | 7         | 0.25%   |
| 6.4.10  | 6         | 0.22%   |
| 6.2.2   | 6         | 0.22%   |
| 5.9.16  | 6         | 0.22%   |
| 5.3.18  | 6         | 0.22%   |
| 5.18.0  | 6         | 0.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 424       | 15.5%   |
| 5.15    | 315       | 11.52%  |
| 5.10    | 216       | 7.9%    |
| 5.11    | 152       | 5.56%   |
| 5.13    | 143       | 5.23%   |
| 6.2     | 137       | 5.01%   |
| 5.8     | 135       | 4.94%   |
| 5.19    | 134       | 4.9%    |
| 5.3     | 128       | 4.68%   |
| 5.16    | 123       | 4.5%    |
| 4.15    | 111       | 4.06%   |
| 6.1     | 86        | 3.14%   |
| 6.4     | 80        | 2.93%   |
| 4.18    | 76        | 2.78%   |
| 5.0     | 73        | 2.67%   |
| 6.0     | 54        | 1.97%   |
| 4.19    | 41        | 1.5%    |
| 6.3     | 38        | 1.39%   |
| 5.18    | 37        | 1.35%   |
| 5.17    | 35        | 1.28%   |
| 5.14    | 32        | 1.17%   |
| 5.9     | 25        | 0.91%   |
| 4.9     | 25        | 0.91%   |
| 5.7     | 22        | 0.8%    |
| 5.12    | 21        | 0.77%   |
| 5.6     | 19        | 0.69%   |
| 6.5     | 17        | 0.62%   |
| 5.5     | 9         | 0.33%   |
| 4.4     | 6         | 0.22%   |
| 5.2     | 4         | 0.15%   |
| 4.12    | 4         | 0.15%   |
| 4.13    | 3         | 0.11%   |
| 4.1     | 3         | 0.11%   |
| 4.10    | 2         | 0.07%   |
| 3.10    | 2         | 0.07%   |
| 5.1     | 1         | 0.04%   |
| 4.20    | 1         | 0.04%   |
| 3.2     | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 2390      | 96.8%   |
| i686    | 75        | 3.04%   |
| aarch64 | 3         | 0.12%   |
| armv7l  | 1         | 0.04%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| GNOME             | 1141      | 44.24%  |
| KDE5              | 519       | 20.12%  |
| Unknown           | 229       | 8.88%   |
| XFCE              | 189       | 7.33%   |
| X-Cinnamon        | 156       | 6.05%   |
| MATE              | 75        | 2.91%   |
| KDE               | 73        | 2.83%   |
| Pantheon          | 38        | 1.47%   |
| Cinnamon          | 28        | 1.09%   |
| LXQt              | 23        | 0.89%   |
| KDE4              | 22        | 0.85%   |
| LXDE              | 16        | 0.62%   |
| Budgie            | 16        | 0.62%   |
| Unity             | 10        | 0.39%   |
| Deepin            | 8         | 0.31%   |
| openbox           | 5         | 0.19%   |
| i3                | 5         | 0.19%   |
| GNOME Classic     | 4         | 0.16%   |
| trinity           | 3         | 0.12%   |
| qtile             | 3         | 0.12%   |
| lightdm-xsession  | 3         | 0.12%   |
| Enlightenment     | 3         | 0.12%   |
| Hyprland          | 2         | 0.08%   |
| GNOME Flashback   | 2         | 0.08%   |
| awesome           | 2         | 0.08%   |
| Yaru:ubuntu:GNOME | 1         | 0.04%   |
| xmonad            | 1         | 0.04%   |
| chadwm            | 1         | 0.04%   |
| bspwm             | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1917      | 75.09%  |
| Wayland | 479       | 18.76%  |
| Unknown | 139       | 5.44%   |
| Tty     | 18        | 0.71%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1263      | 49.22%  |
| SDDM    | 436       | 16.99%  |
| GDM3    | 280       | 10.91%  |
| GDM     | 252       | 9.82%   |
| LightDM | 246       | 9.59%   |
| TDM     | 53        | 2.07%   |
| KDM     | 23        | 0.9%    |
| XDM     | 4         | 0.16%   |
| SLiM    | 4         | 0.16%   |
| LXDM    | 3         | 0.12%   |
| MDM     | 1         | 0.04%   |
| Ly      | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| es_MX      | 1246      | 49.17%  |
| en_US      | 795       | 31.37%  |
| Unknown    | 223       | 8.8%    |
| es_ES      | 164       | 6.47%   |
| C          | 44        | 1.74%   |
| en_GB      | 20        | 0.79%   |
| es_US      | 8         | 0.32%   |
| en_CA      | 5         | 0.2%    |
| fr_FR      | 3         | 0.12%   |
| POSIX      | 2         | 0.08%   |
| it_IT      | 2         | 0.08%   |
| es_MX.UTF8 | 2         | 0.08%   |
| es_AR      | 2         | 0.08%   |
| en_MX      | 2         | 0.08%   |
| en_DK      | 2         | 0.08%   |
| C.UTF8     | 2         | 0.08%   |
| uk_UA      | 1         | 0.04%   |
| ru_RU      | 1         | 0.04%   |
| pt_BR      | 1         | 0.04%   |
| nhn_MX     | 1         | 0.04%   |
| es_PE      | 1         | 0.04%   |
| es_CR      | 1         | 0.04%   |
| es_CO      | 1         | 0.04%   |
| es_419     | 1         | 0.04%   |
| en_US.UTF8 | 1         | 0.04%   |
| en_IE      | 1         | 0.04%   |
| de_DE      | 1         | 0.04%   |
| Default    | 1         | 0.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 1333      | 52.79%  |
| EFI  | 1192      | 47.21%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type                | Computers | Percent |
|---------------------|-----------|---------|
| Ext4                | 1860      | 73.49%  |
| Overlay             | 245       | 9.68%   |
| Btrfs               | 237       | 9.36%   |
| Unknown             | 68        | 2.69%   |
| Tmpfs               | 57        | 2.25%   |
| Xfs                 | 34        | 1.34%   |
| Zfs                 | 12        | 0.47%   |
| Ext2                | 8         | 0.32%   |
| XXXXXXX             | 2         | 0.08%   |
| Reiserfs            | 2         | 0.08%   |
| F2fs                | 2         | 0.08%   |
| Ext3                | 2         | 0.08%   |
| Fuse.fuse-overlayfs | 1         | 0.04%   |
| Aufs                | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1377      | 54.43%  |
| GPT     | 864       | 34.15%  |
| MBR     | 289       | 11.42%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2188      | 87.1%   |
| Yes       | 324       | 12.9%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1702      | 67.54%  |
| Yes       | 818       | 32.46%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 480       | 19.45%  |
| Lenovo                  | 356       | 14.42%  |
| Dell                    | 343       | 13.9%   |
| ASUSTek Computer        | 271       | 10.98%  |
| Gigabyte Technology     | 175       | 7.09%   |
| Acer                    | 132       | 5.35%   |
| Apple                   | 80        | 3.24%   |
| Toshiba                 | 75        | 3.04%   |
| HUAWEI                  | 65        | 2.63%   |
| MSI                     | 56        | 2.27%   |
| Sony                    | 41        | 1.66%   |
| ASRock                  | 38        | 1.54%   |
| Intel                   | 35        | 1.42%   |
| ECS                     | 32        | 1.3%    |
| Biostar                 | 28        | 1.13%   |
| Gateway                 | 22        | 0.89%   |
| Samsung Electronics     | 20        | 0.81%   |
| Pegatron                | 17        | 0.69%   |
| Lanix                   | 16        | 0.65%   |
| Google                  | 16        | 0.65%   |
| Alienware               | 15        | 0.61%   |
| Chuwi                   | 11        | 0.45%   |
| Unknown                 | 11        | 0.45%   |
| PCChips                 | 8         | 0.32%   |
| Microsoft               | 8         | 0.32%   |
| AMI                     | 8         | 0.32%   |
| Valve                   | 7         | 0.28%   |
| Foxconn                 | 7         | 0.28%   |
| eMachines               | 7         | 0.28%   |
| GPU Company             | 6         | 0.24%   |
| GHIA                    | 5         | 0.2%    |
| A-DATA Technology       | 5         | 0.2%    |
| System76                | 4         | 0.16%   |
| Raspberry Pi Foundation | 4         | 0.16%   |
| HONOR                   | 4         | 0.16%   |
| EVOO                    | 4         | 0.16%   |
| TPV-INVENTA             | 3         | 0.12%   |
| Timi                    | 3         | 0.12%   |
| Supermicro              | 3         | 0.12%   |
| Notebook                | 3         | 0.12%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                          | Computers | Percent |
|-------------------------------|-----------|---------|
| HP Notebook                   | 27        | 1.09%   |
| Unknown                       | 25        | 1.01%   |
| ASUS PRIME A320M-K            | 20        | 0.81%   |
| HUAWEI HVY-WXX9               | 18        | 0.73%   |
| HP Pavilion Laptop 15-cw0xxx  | 17        | 0.69%   |
| HP Pavilion g4                | 15        | 0.61%   |
| HP Pavilion Notebook          | 14        | 0.57%   |
| HP Pavilion Laptop 15-cw1xxx  | 10        | 0.41%   |
| Dell Latitude E6430           | 10        | 0.41%   |
| ASUS All Series               | 10        | 0.41%   |
| Apple MacBookPro9,2           | 10        | 0.41%   |
| Apple MacBookPro8,1           | 10        | 0.41%   |
| HP Laptop 15-da0xxx           | 9         | 0.36%   |
| Gigabyte B450M DS3H           | 9         | 0.36%   |
| Lenovo IdeaPad 330-14AST 81D5 | 8         | 0.32%   |
| HP Laptop 15-bw0xx            | 8         | 0.32%   |
| HP EliteBook 8460p            | 8         | 0.32%   |
| Dell OptiPlex 7010            | 8         | 0.32%   |
| Valve Jupiter                 | 7         | 0.28%   |
| HP Pavilion dv4               | 7         | 0.28%   |
| ECS A320AM4-M3D               | 7         | 0.28%   |
| Dell OptiPlex 9020            | 7         | 0.28%   |
| Dell OptiPlex 745             | 7         | 0.28%   |
| Dell Inspiron 5559            | 7         | 0.28%   |
| ASUS PRIME B450M-A II         | 7         | 0.28%   |
| Apple MacBookPro12,1          | 7         | 0.28%   |
| HUAWEI NBLB-WAX9N             | 6         | 0.24%   |
| HP Pavilion dv5               | 6         | 0.24%   |
| HP Pavilion 14                | 6         | 0.24%   |
| HP Laptop 15-db0xxx           | 6         | 0.24%   |
| HP Laptop 14-cm0xxx           | 6         | 0.24%   |
| HP Compaq 6200 Pro SFF PC     | 6         | 0.24%   |
| Gigabyte A320M-S2H            | 6         | 0.24%   |
| Dell Inspiron 3421            | 6         | 0.24%   |
| Acer Aspire E5-573            | 6         | 0.24%   |
| Lenovo Y720-15IKB 80VR        | 5         | 0.2%    |
| Lenovo Y50-70 20378           | 5         | 0.2%    |
| Lenovo G50-30 80G0            | 5         | 0.2%    |
| Lenovo G40-45 80E1            | 5         | 0.2%    |
| HUAWEI NBLK-WAX9X             | 5         | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| HP Pavilion        | 127       | 5.15%   |
| Lenovo ThinkPad    | 117       | 4.74%   |
| Lenovo IdeaPad     | 107       | 4.34%   |
| Dell Inspiron      | 105       | 4.25%   |
| Dell Latitude      | 95        | 3.85%   |
| Acer Aspire        | 93        | 3.77%   |
| Toshiba Satellite  | 67        | 2.71%   |
| HP Laptop          | 66        | 2.67%   |
| Dell OptiPlex      | 62        | 2.51%   |
| ASUS PRIME         | 62        | 2.51%   |
| HP Compaq          | 45        | 1.82%   |
| HP EliteBook       | 28        | 1.13%   |
| HP Notebook        | 27        | 1.09%   |
| HP ProBook         | 26        | 1.05%   |
| ASUS VivoBook      | 26        | 1.05%   |
| Unknown            | 25        | 1.01%   |
| Lenovo ThinkCentre | 23        | 0.93%   |
| ASUS ROG           | 23        | 0.93%   |
| HUAWEI HVY-WXX9    | 18        | 0.73%   |
| Dell Precision     | 18        | 0.73%   |
| HP ENVY            | 16        | 0.65%   |
| Lenovo Yoga        | 15        | 0.61%   |
| Dell Vostro        | 13        | 0.53%   |
| Lenovo Legion      | 12        | 0.49%   |
| Gigabyte B450M     | 12        | 0.49%   |
| Dell XPS           | 12        | 0.49%   |
| HP 240             | 11        | 0.45%   |
| Dell Studio        | 11        | 0.45%   |
| ASUS TUF           | 11        | 0.45%   |
| Apple MacBookPro9  | 11        | 0.45%   |
| Apple MacBookPro8  | 11        | 0.45%   |
| HP ProDesk         | 10        | 0.41%   |
| Gigabyte A320M-S2H | 10        | 0.41%   |
| ASUS All           | 10        | 0.41%   |
| HP OMEN            | 9         | 0.36%   |
| ASUS ASUS          | 9         | 0.36%   |
| Microsoft Surface  | 8         | 0.32%   |
| Gigabyte X570      | 8         | 0.32%   |
| ASUS M5A78L-M      | 8         | 0.32%   |
| Acer Nitro         | 8         | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 233       | 9.44%   |
| 2011    | 217       | 8.79%   |
| 2012    | 199       | 8.06%   |
| 2019    | 197       | 7.98%   |
| 2020    | 189       | 7.66%   |
| 2017    | 188       | 7.62%   |
| 2014    | 161       | 6.52%   |
| 2013    | 159       | 6.44%   |
| 2015    | 157       | 6.36%   |
| 2021    | 143       | 5.79%   |
| 2010    | 125       | 5.06%   |
| 2016    | 122       | 4.94%   |
| 2008    | 105       | 4.25%   |
| 2009    | 98        | 3.97%   |
| 2007    | 64        | 2.59%   |
| 2022    | 52        | 2.11%   |
| 2006    | 26        | 1.05%   |
| 2023    | 14        | 0.57%   |
| 2005    | 11        | 0.45%   |
| Unknown | 5         | 0.2%    |
| 2004    | 2         | 0.08%   |
| 2003    | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1536      | 62.24%  |
| Desktop        | 761       | 30.83%  |
| All in one     | 52        | 2.11%   |
| Convertible    | 47        | 1.9%    |
| Mini pc        | 26        | 1.05%   |
| Tablet         | 25        | 1.01%   |
| Server         | 17        | 0.69%   |
| System on chip | 4         | 0.16%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 2270      | 91.16%  |
| Enabled  | 220       | 8.84%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2450      | 99.27%  |
| Yes  | 18        | 0.73%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 678       | 27.04%  |
| 3.01-4.0        | 551       | 21.98%  |
| 8.01-16.0       | 493       | 19.66%  |
| 16.01-24.0      | 342       | 13.64%  |
| 1.01-2.0        | 151       | 6.02%   |
| 32.01-64.0      | 133       | 5.31%   |
| 2.01-3.0        | 50        | 1.99%   |
| 24.01-32.0      | 43        | 1.72%   |
| 64.01-256.0     | 39        | 1.56%   |
| 0.51-1.0        | 23        | 0.92%   |
| More than 256.0 | 3         | 0.12%   |
| 0.01-0.5        | 1         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 996       | 36.55%  |
| 2.01-3.0    | 727       | 26.68%  |
| 3.01-4.0    | 349       | 12.81%  |
| 4.01-8.0    | 342       | 12.55%  |
| 0.51-1.0    | 178       | 6.53%   |
| 8.01-16.0   | 92        | 3.38%   |
| 0.01-0.5    | 22        | 0.81%   |
| 16.01-24.0  | 12        | 0.44%   |
| 24.01-32.0  | 3         | 0.11%   |
| 32.01-64.0  | 2         | 0.07%   |
| 64.01-256.0 | 1         | 0.04%   |
| Unknown     | 1         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1677      | 65.84%  |
| 2       | 610       | 23.95%  |
| 3       | 132       | 5.18%   |
| 4       | 57        | 2.24%   |
| 0       | 32        | 1.26%   |
| 5       | 17        | 0.67%   |
| 6       | 14        | 0.55%   |
| 7       | 4         | 0.16%   |
| 37      | 1         | 0.04%   |
| 18      | 1         | 0.04%   |
| 8       | 1         | 0.04%   |
| Unknown | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1561      | 62.79%  |
| Yes       | 925       | 37.21%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2117      | 85.74%  |
| No        | 352       | 14.26%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2035      | 82.06%  |
| No        | 445       | 17.94%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1470      | 58.78%  |
| No        | 1031      | 41.22%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Mexico  | 2468      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Mexico City           | 519       | 19.82%  |
| Guadalajara           | 136       | 5.19%   |
| Monterrey             | 90        | 3.44%   |
| Zapopan               | 76        | 2.9%    |
| Puebla City           | 70        | 2.67%   |
| Tijuana               | 69        | 2.63%   |
| Queretaro             | 54        | 2.06%   |
| Mérida               | 52        | 1.99%   |
| Toluca                | 38        | 1.45%   |
| Hermosillo            | 36        | 1.37%   |
| Ciudad Juárez        | 34        | 1.3%    |
| Cancún               | 34        | 1.3%    |
| Tlalnepantla          | 33        | 1.26%   |
| Morelia               | 33        | 1.26%   |
| Mexicali              | 30        | 1.15%   |
| León                 | 29        | 1.11%   |
| Naucalpan             | 28        | 1.07%   |
| Ecatepec              | 28        | 1.07%   |
| Ciudad Lopez Mateos   | 28        | 1.07%   |
| Chihuahua City        | 26        | 0.99%   |
| Apodaca               | 26        | 0.99%   |
| Oaxaca City           | 25        | 0.95%   |
| Xalapa                | 24        | 0.92%   |
| Veracruz              | 24        | 0.92%   |
| San Luis Potosí City | 24        | 0.92%   |
| Mexico                | 24        | 0.92%   |
| Culiacán             | 24        | 0.92%   |
| Cuernavaca            | 24        | 0.92%   |
| Ciudad Nezahualcoyotl | 23        | 0.88%   |
| Villahermosa          | 20        | 0.76%   |
| Guadalupe             | 20        | 0.76%   |
| Saltillo              | 18        | 0.69%   |
| Iztapalapa            | 18        | 0.69%   |
| Querétaro City       | 17        | 0.65%   |
| Gustavo Adolfo Madero | 17        | 0.65%   |
| Ensenada              | 17        | 0.65%   |
| Aguascalientes        | 17        | 0.65%   |
| Zacatecas City        | 15        | 0.57%   |
| Puerto Vallarta       | 15        | 0.57%   |
| Pachuca               | 15        | 0.57%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 599       | 880    | 17.85%  |
| WDC                         | 523       | 708    | 15.59%  |
| Kingston                    | 331       | 430    | 9.87%   |
| Toshiba                     | 292       | 355    | 8.7%    |
| A-DATA Technology           | 243       | 301    | 7.24%   |
| Samsung Electronics         | 217       | 282    | 6.47%   |
| Hitachi                     | 164       | 207    | 4.89%   |
| Unknown                     | 152       | 199    | 4.53%   |
| SanDisk                     | 99        | 124    | 2.95%   |
| HGST                        | 87        | 101    | 2.59%   |
| Intel                       | 61        | 96     | 1.82%   |
| SK hynix                    | 56        | 73     | 1.67%   |
| Crucial                     | 43        | 53     | 1.28%   |
| Apple                       | 35        | 47     | 1.04%   |
| XPG                         | 32        | 43     | 0.95%   |
| Micron Technology           | 26        | 33     | 0.77%   |
| Fujitsu                     | 25        | 30     | 0.75%   |
| Realtek Semiconductor       | 22        | 28     | 0.66%   |
| PNY                         | 21        | 28     | 0.63%   |
| ADATA Technology            | 17        | 19     | 0.51%   |
| Silicon Motion              | 15        | 16     | 0.45%   |
| Phison                      | 15        | 16     | 0.45%   |
| KIOXIA                      | 15        | 17     | 0.45%   |
| Unknown                     | 15        | 15     | 0.45%   |
| LITEON                      | 14        | 19     | 0.42%   |
| China                       | 14        | 15     | 0.42%   |
| Netac                       | 10        | 12     | 0.3%    |
| JMicron Technology          | 9         | 9      | 0.27%   |
| YMTC                        | 8         | 9      | 0.24%   |
| Phison Electronics          | 8         | 10     | 0.24%   |
| Patriot                     | 8         | 12     | 0.24%   |
| Maxtor                      | 8         | 10     | 0.24%   |
| Kingston Technology Company | 8         | 8      | 0.24%   |
| Hewlett-Packard             | 8         | 8      | 0.24%   |
| Gigabyte Technology         | 8         | 9      | 0.24%   |
| Micron/Crucial Technology   | 7         | 10     | 0.21%   |
| Acer                        | 7         | 9      | 0.21%   |
| AS201                       | 6         | 6      | 0.18%   |
| UMIS                        | 5         | 6      | 0.15%   |
| Wibtek                      | 4         | 4      | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 86        | 2.39%   |
| Kingston SA400S37480G 480GB SSD                     | 73        | 2.03%   |
| Seagate ST1000LM035-1RK172 1TB                      | 68        | 1.89%   |
| Toshiba MQ01ABD100 1TB                              | 49        | 1.36%   |
| A-DATA SU650 120GB SSD                              | 48        | 1.33%   |
| Toshiba MQ04ABF100 1TB                              | 41        | 1.14%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 40        | 1.11%   |
| A-DATA SU630 240GB SSD                              | 35        | 0.97%   |
| Unknown MMC Card  32GB                              | 34        | 0.94%   |
| Seagate ST500DM002-1BD142 500GB                     | 30        | 0.83%   |
| Kingston SA400S37120G 120GB SSD                     | 28        | 0.78%   |
| Toshiba MQ01ABF050 500GB                            | 27        | 0.75%   |
| Seagate ST500LT012-1DG142 500GB                     | 26        | 0.72%   |
| Kingston SA400S37960G 960GB SSD                     | 24        | 0.67%   |
| Seagate ST1000DM010-2EP102 1TB                      | 23        | 0.64%   |
| A-DATA SU650 240GB SSD                              | 21        | 0.58%   |
| A-DATA SU630 480GB SSD                              | 21        | 0.58%   |
| Unknown MMC Card  64GB                              | 18        | 0.5%    |
| Unknown MMC Card  16GB                              | 17        | 0.47%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 16        | 0.44%   |
| Toshiba DT01ACA050 500GB                            | 15        | 0.42%   |
| Seagate ST3500418AS 500GB                           | 15        | 0.42%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 15        | 0.42%   |
| HGST HTS541010A9E680 1TB                            | 15        | 0.42%   |
| Unknown                                             | 15        | 0.42%   |
| XPG GAMMIX S11 Pro 1TB                              | 14        | 0.39%   |
| Unknown SD/MMC/MS PRO 128GB                         | 14        | 0.39%   |
| Seagate ST500LM021-1KJ152 500GB                     | 14        | 0.39%   |
| Kingston SV300S37A120G 120GB SSD                    | 14        | 0.39%   |
| Seagate ST9500325AS 500GB                           | 13        | 0.36%   |
| Seagate ST2000LM007-1R8174 2TB                      | 13        | 0.36%   |
| Samsung NVMe SSD Drive 512GB                        | 13        | 0.36%   |
| HGST HTS725050A7E630 500GB                          | 13        | 0.36%   |
| A-DATA SU800 512GB SSD                              | 13        | 0.36%   |
| WDC WD5000LPCX-60VHAT0 500GB                        | 12        | 0.33%   |
| Toshiba DT01ACA100 1TB                              | 12        | 0.33%   |
| Seagate ST1000DM003-1CH162 1TB                      | 12        | 0.33%   |
| HGST HTS721010A9E630 1TB                            | 12        | 0.33%   |
| HGST HTS545050A7E680 500GB                          | 12        | 0.33%   |
| A-DATA SU650 480GB SSD                              | 12        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 595       | 874    | 35.69%  |
| WDC                 | 452       | 597    | 27.11%  |
| Toshiba             | 261       | 319    | 15.66%  |
| Hitachi             | 164       | 207    | 9.84%   |
| HGST                | 87        | 101    | 5.22%   |
| Samsung Electronics | 35        | 40     | 2.1%    |
| Fujitsu             | 25        | 30     | 1.5%    |
| Unknown             | 14        | 15     | 0.84%   |
| Apple               | 10        | 15     | 0.6%    |
| Maxtor              | 8         | 10     | 0.48%   |
| Hewlett-Packard     | 3         | 3      | 0.18%   |
| USB3.0              | 2         | 2      | 0.12%   |
| Pioneer             | 2         | 3      | 0.12%   |
| LaCie               | 2         | 3      | 0.12%   |
| SAGE                | 1         | 1      | 0.06%   |
| SABRENT             | 1         | 1      | 0.06%   |
| QUANTUM             | 1         | 2      | 0.06%   |
| MaxDigital          | 1         | 4      | 0.06%   |
| IBM/Hitachi         | 1         | 1      | 0.06%   |
| HPE                 | 1         | 1      | 0.06%   |
| DELLBOSS            | 1         | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 299       | 382    | 31.24%  |
| A-DATA Technology   | 227       | 284    | 23.72%  |
| Samsung Electronics | 67        | 78     | 7%      |
| WDC                 | 58        | 77     | 6.06%   |
| SanDisk             | 39        | 45     | 4.08%   |
| Crucial             | 38        | 43     | 3.97%   |
| PNY                 | 21        | 28     | 2.19%   |
| Apple               | 20        | 22     | 2.09%   |
| SK hynix            | 17        | 25     | 1.78%   |
| Intel               | 14        | 19     | 1.46%   |
| China               | 14        | 15     | 1.46%   |
| LITEON              | 13        | 18     | 1.36%   |
| Micron Technology   | 11        | 14     | 1.15%   |
| Netac               | 10        | 12     | 1.04%   |
| Patriot             | 7         | 11     | 0.73%   |
| Gigabyte Technology | 7         | 8      | 0.73%   |
| AS201               | 6         | 6      | 0.63%   |
| Acer                | 6         | 7      | 0.63%   |
| JMicron Technology  | 5         | 5      | 0.52%   |
| Unknown             | 5         | 5      | 0.52%   |
| Toshiba             | 4         | 4      | 0.42%   |
| SPCC                | 4         | 4      | 0.42%   |
| LITEONIT            | 4         | 4      | 0.42%   |
| Hewlett-Packard     | 4         | 4      | 0.42%   |
| Yeyian              | 3         | 5      | 0.31%   |
| Wibtek              | 3         | 3      | 0.31%   |
| Unknown             | 3         | 3      | 0.31%   |
| Transcend           | 3         | 3      | 0.31%   |
| Blackpcs            | 3         | 3      | 0.31%   |
| BHT                 | 3         | 3      | 0.31%   |
| Team                | 2         | 2      | 0.21%   |
| Quaroni             | 2         | 2      | 0.21%   |
| OCZ                 | 2         | 4      | 0.21%   |
| Lexar               | 2         | 2      | 0.21%   |
| KingSpec            | 2         | 7      | 0.21%   |
| Dogfish             | 2         | 5      | 0.21%   |
| ZTC                 | 1         | 1      | 0.1%    |
| ZOTAC               | 1         | 1      | 0.1%    |
| Zheino              | 1         | 1      | 0.1%    |
| WDC WDS4            | 1         | 1      | 0.1%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1476      | 2230   | 48.28%  |
| SSD     | 863       | 1192   | 28.23%  |
| NVMe    | 539       | 746    | 17.63%  |
| MMC     | 138       | 181    | 4.51%   |
| Unknown | 41        | 55     | 1.34%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2008      | 3335   | 71.71%  |
| NVMe | 537       | 743    | 19.18%  |
| MMC  | 138       | 181    | 4.93%   |
| SAS  | 117       | 145    | 4.18%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1462      | 2128   | 61.27%  |
| 0.51-1.0   | 718       | 957    | 30.09%  |
| 1.01-2.0   | 135       | 191    | 5.66%   |
| 3.01-4.0   | 31        | 60     | 1.3%    |
| 2.01-3.0   | 22        | 29     | 0.92%   |
| 4.01-10.0  | 14        | 35     | 0.59%   |
| 10.01-20.0 | 4         | 22     | 0.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 662       | 25.33%  |
| 251-500        | 604       | 23.12%  |
| 501-1000       | 411       | 15.73%  |
| 1-20           | 227       | 8.69%   |
| 51-100         | 210       | 8.04%   |
| 1001-2000      | 192       | 7.35%   |
| 21-50          | 128       | 4.9%    |
| More than 3000 | 77        | 2.95%   |
| 2001-3000      | 57        | 2.18%   |
| Unknown        | 45        | 1.72%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1124      | 41.52%  |
| 21-50          | 518       | 19.14%  |
| 101-250        | 310       | 11.45%  |
| 51-100         | 296       | 10.93%  |
| 251-500        | 181       | 6.69%   |
| 501-1000       | 126       | 4.65%   |
| 1001-2000      | 71        | 2.62%   |
| Unknown        | 45        | 1.66%   |
| More than 3000 | 23        | 0.85%   |
| 2001-3000      | 13        | 0.48%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB              | 8         | 9      | 2.85%   |
| Seagate ST500LT012-1DG142 500GB     | 6         | 7      | 2.14%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 6         | 6      | 2.14%   |
| Toshiba MQ04ABF100 1TB              | 5         | 5      | 1.78%   |
| HGST HTS541010A9E680 1TB            | 5         | 5      | 1.78%   |
| Seagate ST500LM021-1KJ152 500GB     | 4         | 4      | 1.42%   |
| Seagate ST3160815AS 160GB           | 4         | 4      | 1.42%   |
| Hitachi HTS545050B9A300 500GB       | 4         | 4      | 1.42%   |
| HGST HTS541075A9E680 752GB          | 4         | 4      | 1.42%   |
| Toshiba MQ01ABF050 500GB            | 3         | 3      | 1.07%   |
| Seagate ST9500420AS 500GB           | 3         | 3      | 1.07%   |
| Seagate ST3500418AS 500GB           | 3         | 3      | 1.07%   |
| Seagate ST2000DL003-9VT166 2TB      | 3         | 3      | 1.07%   |
| Seagate ST1000LM035-1RK172 1TB      | 3         | 3      | 1.07%   |
| LITEON CV8-8E128-HP 128GB SSD       | 3         | 3      | 1.07%   |
| HGST HTS545050A7E380 500GB          | 3         | 5      | 1.07%   |
| HGST HTS541010A7E630 1TB            | 3         | 3      | 1.07%   |
| China SSD 256GB                     | 3         | 3      | 1.07%   |
| A-DATA Technology SU650 240GB SSD   | 3         | 3      | 1.07%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 2         | 2      | 0.71%   |
| WDC WD5000LPCX-60VHAT0 500GB        | 2         | 2      | 0.71%   |
| WDC WD3200AAJS-00YZCA0 320GB        | 2         | 3      | 0.71%   |
| WDC WD2500BEVS-60UST0 250GB         | 2         | 2      | 0.71%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 2         | 2      | 0.71%   |
| WDC WD10JPVX-60JC3T0 1TB            | 2         | 2      | 0.71%   |
| Toshiba DT01ACA100 1TB              | 2         | 2      | 0.71%   |
| Seagate ST9320325AS 320GB           | 2         | 4      | 0.71%   |
| Seagate ST500LT012-9WS142 500GB     | 2         | 2      | 0.71%   |
| Seagate ST31000524AS 1TB            | 2         | 4      | 0.71%   |
| Seagate ST2000DM001-1CH164 2TB      | 2         | 2      | 0.71%   |
| Seagate ST1500DL003-9VT16L 1TB      | 2         | 2      | 0.71%   |
| Seagate ST1000DM003-9YN162 1TB      | 2         | 2      | 0.71%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD | 2         | 2      | 0.71%   |
| Maxtor 6Y080M0 80GB                 | 2         | 2      | 0.71%   |
| Kingston SUV400S37480G 480GB SSD    | 2         | 2      | 0.71%   |
| Kingston SA400S37240G 240GB SSD     | 2         | 2      | 0.71%   |
| Kingston SA400S37120G 120GB SSD     | 2         | 2      | 0.71%   |
| Hitachi HUA722020ALA331 2TB         | 2         | 2      | 0.71%   |
| Hitachi HTS723232A7A364 320GB       | 2         | 2      | 0.71%   |
| Hitachi HTS547550A9E384 500GB       | 2         | 2      | 0.71%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 81        | 112    | 29.67%  |
| WDC                       | 54        | 65     | 19.78%  |
| Hitachi                   | 36        | 39     | 13.19%  |
| Toshiba                   | 35        | 47     | 12.82%  |
| HGST                      | 18        | 20     | 6.59%   |
| Kingston                  | 13        | 13     | 4.76%   |
| Samsung Electronics       | 8         | 8      | 2.93%   |
| A-DATA Technology         | 7         | 7      | 2.56%   |
| Fujitsu                   | 5         | 5      | 1.83%   |
| SanDisk                   | 4         | 4      | 1.47%   |
| LITEON                    | 3         | 3      | 1.1%    |
| China                     | 3         | 3      | 1.1%    |
| Maxtor                    | 2         | 2      | 0.73%   |
| Micron/Crucial Technology | 1         | 2      | 0.37%   |
| Micron Technology         | 1         | 1      | 0.37%   |
| Intel                     | 1         | 1      | 0.37%   |
| Crucial                   | 1         | 1      | 0.37%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 81        | 112    | 34.03%  |
| WDC                 | 54        | 65     | 22.69%  |
| Hitachi             | 36        | 39     | 15.13%  |
| Toshiba             | 35        | 47     | 14.71%  |
| HGST                | 18        | 20     | 7.56%   |
| Samsung Electronics | 7         | 7      | 2.94%   |
| Fujitsu             | 5         | 5      | 2.1%    |
| Maxtor              | 2         | 2      | 0.84%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 225       | 297    | 86.54%  |
| SSD  | 30        | 30     | 11.54%  |
| NVMe | 5         | 6      | 1.92%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD1600BEVT-75A23T0 160GB      | 1         | 1      | 16.67%  |
| Toshiba MK1234GSX 120GB           | 1         | 1      | 16.67%  |
| Seagate ST3500410AS 500GB         | 1         | 2      | 16.67%  |
| Seagate ST31500341AS 1TB          | 1         | 2      | 16.67%  |
| Samsung Electronics HD161GJ 160GB | 1         | 1      | 16.67%  |
| Hitachi HTS545016B9A300 160GB     | 1         | 1      | 16.67%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 20%     |
| Toshiba             | 1         | 1      | 20%     |
| Seagate             | 1         | 4      | 20%     |
| Samsung Electronics | 1         | 1      | 20%     |
| Hitachi             | 1         | 1      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1566      | 2708   | 59.27%  |
| Works    | 816       | 1355   | 30.89%  |
| Malfunc  | 255       | 333    | 9.65%   |
| Failed   | 5         | 8      | 0.19%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 1543      | 54.64%  |
| AMD                                     | 626       | 22.17%  |
| Samsung Electronics                     | 125       | 4.43%   |
| SanDisk                                 | 81        | 2.87%   |
| Nvidia                                  | 61        | 2.16%   |
| ADATA Technology                        | 49        | 1.74%   |
| Kingston Technology Company             | 44        | 1.56%   |
| SK hynix                                | 38        | 1.35%   |
| Realtek Semiconductor                   | 36        | 1.27%   |
| Toshiba America Info Systems            | 28        | 0.99%   |
| Phison Electronics                      | 24        | 0.85%   |
| Marvell Technology Group                | 22        | 0.78%   |
| KIOXIA                                  | 16        | 0.57%   |
| Silicon Motion                          | 15        | 0.53%   |
| Micron Technology                       | 15        | 0.53%   |
| Micron/Crucial Technology               | 13        | 0.46%   |
| Union Memory (Shenzhen)                 | 12        | 0.42%   |
| ASMedia Technology                      | 10        | 0.35%   |
| Yangtze Memory Technologies             | 9         | 0.32%   |
| JMicron Technology                      | 9         | 0.32%   |
| LSI Logic / Symbios Logic               | 7         | 0.25%   |
| MAXIO Technology (Hangzhou)             | 6         | 0.21%   |
| VIA Technologies                        | 5         | 0.18%   |
| Apple                                   | 5         | 0.18%   |
| Silicon Image                           | 3         | 0.11%   |
| Hewlett-Packard                         | 3         | 0.11%   |
| Broadcom / LSI                          | 3         | 0.11%   |
| Solid State Storage Technology          | 2         | 0.07%   |
| Seagate Technology                      | 2         | 0.07%   |
| Lite-On Technology                      | 2         | 0.07%   |
| Lenovo                                  | 2         | 0.07%   |
| Solidigm                                | 1         | 0.04%   |
| Silicon Integrated Systems [SiS]        | 1         | 0.04%   |
| Shenzhen Unionmemory Information System | 1         | 0.04%   |
| INNOGRIT                                | 1         | 0.04%   |
| Broadcom                                | 1         | 0.04%   |
| Biwin Storage Technology                | 1         | 0.04%   |
| Adaptec                                 | 1         | 0.04%   |
| Unknown                                 | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 444       | 13.34%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 124       | 3.72%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 121       | 3.63%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 106       | 3.18%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 87        | 2.61%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 70        | 2.1%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 63        | 1.89%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 58        | 1.74%   |
| AMD 400 Series Chipset SATA Controller                                                  | 55        | 1.65%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 54        | 1.62%   |
| Intel SATA Controller [RAID mode]                                                       | 52        | 1.56%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 52        | 1.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 49        | 1.47%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 48        | 1.44%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 46        | 1.38%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 46        | 1.38%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 45        | 1.35%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 45        | 1.35%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 42        | 1.26%   |
| AMD FCH SATA Controller D                                                               | 40        | 1.2%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 39        | 1.17%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 39        | 1.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 39        | 1.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 36        | 1.08%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 36        | 1.08%   |
| Samsung NVMe SSD Controller 980                                                         | 34        | 1.02%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 33        | 0.99%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 31        | 0.93%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 29        | 0.87%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 28        | 0.84%   |
| AMD 500 Series Chipset SATA Controller                                                  | 27        | 0.81%   |
| Nvidia MCP61 SATA Controller                                                            | 26        | 0.78%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 25        | 0.75%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 24        | 0.72%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 24        | 0.72%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 24        | 0.72%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 24        | 0.72%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 24        | 0.72%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 23        | 0.69%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 22        | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1803      | 60.81%  |
| NVMe | 538       | 18.15%  |
| IDE  | 374       | 12.61%  |
| RAID | 235       | 7.93%   |
| SAS  | 14        | 0.47%   |
| SCSI | 1         | 0.03%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 1717      | 69.57%  |
| AMD          | 746       | 30.23%  |
| ARM          | 4         | 0.16%   |
| CentaurHauls | 1         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 4600H with Radeon Graphics        | 24        | 0.97%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 23        | 0.93%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 23        | 0.93%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 23        | 0.93%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 21        | 0.85%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 19        | 0.77%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 19        | 0.77%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 18        | 0.73%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 18        | 0.73%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 18        | 0.73%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 18        | 0.73%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 17        | 0.69%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 17        | 0.69%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 16        | 0.65%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 16        | 0.65%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 16        | 0.65%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 16        | 0.65%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 15        | 0.61%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 14        | 0.57%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 14        | 0.57%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 14        | 0.57%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 14        | 0.57%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 14        | 0.57%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 14        | 0.57%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 13        | 0.53%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 13        | 0.53%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 12        | 0.49%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 12        | 0.49%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 12        | 0.49%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 12        | 0.49%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 12        | 0.49%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 12        | 0.49%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 12        | 0.49%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 12        | 0.49%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 12        | 0.49%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 12        | 0.49%   |
| AMD Ryzen 3 2300U with Radeon Vega Mobile Gfx | 12        | 0.49%   |
| AMD Athlon 3000G with Radeon Vega Graphics    | 12        | 0.49%   |
| AMD A4-9125 RADEON R3, 4 COMPUTE CORES 2C+2G  | 12        | 0.49%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 11        | 0.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 441       | 17.84%  |
| Intel Core i7           | 372       | 15.05%  |
| Intel Celeron           | 212       | 8.58%   |
| Intel Core i3           | 205       | 8.29%   |
| AMD Ryzen 5             | 151       | 6.11%   |
| Other                   | 119       | 4.81%   |
| Intel Core 2 Duo        | 105       | 4.25%   |
| AMD Ryzen 7             | 83        | 3.36%   |
| Intel Atom              | 61        | 2.47%   |
| Intel Pentium           | 50        | 2.02%   |
| Intel Xeon              | 49        | 1.98%   |
| AMD Ryzen 3             | 49        | 1.98%   |
| AMD A6                  | 49        | 1.98%   |
| AMD A8                  | 47        | 1.9%    |
| AMD A4                  | 37        | 1.5%    |
| AMD FX                  | 34        | 1.38%   |
| AMD E                   | 29        | 1.17%   |
| AMD A10                 | 29        | 1.17%   |
| Intel Pentium Dual      | 28        | 1.13%   |
| AMD Athlon              | 28        | 1.13%   |
| Intel Pentium Dual-Core | 26        | 1.05%   |
| AMD Ryzen 9             | 25        | 1.01%   |
| Intel Core 2 Quad       | 16        | 0.65%   |
| AMD Athlon II X2        | 16        | 0.65%   |
| Intel Core 2            | 15        | 0.61%   |
| AMD E1                  | 15        | 0.61%   |
| Intel Pentium 4         | 12        | 0.49%   |
| AMD Athlon 64 X2        | 12        | 0.49%   |
| AMD Sempron             | 11        | 0.44%   |
| AMD Turion 64 X2 Mobile | 10        | 0.4%    |
| AMD Athlon II           | 10        | 0.4%    |
| Intel Genuine           | 9         | 0.36%   |
| AMD Ryzen 5 PRO         | 9         | 0.36%   |
| AMD Phenom II X4        | 8         | 0.32%   |
| Intel Pentium Silver    | 6         | 0.24%   |
| AMD Ryzen 3 PRO         | 6         | 0.24%   |
| AMD Phenom II X6        | 6         | 0.24%   |
| AMD E2                  | 6         | 0.24%   |
| Intel Core i9           | 5         | 0.2%    |
| AMD A12                 | 5         | 0.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1229      | 49.7%   |
| 4       | 757       | 30.61%  |
| 6       | 204       | 8.25%   |
| 1       | 124       | 5.01%   |
| 8       | 98        | 3.96%   |
| 12      | 18        | 0.73%   |
| 10      | 11        | 0.44%   |
| 3       | 11        | 0.44%   |
| 16      | 8         | 0.32%   |
| 14      | 6         | 0.24%   |
| 28      | 3         | 0.12%   |
| 56      | 1         | 0.04%   |
| 32      | 1         | 0.04%   |
| 24      | 1         | 0.04%   |
| Unknown | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 2452      | 99.35%  |
| 2      | 16        | 0.65%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1485      | 60.07%  |
| 1       | 985       | 39.85%  |
| 4       | 1         | 0.04%   |
| Unknown | 1         | 0.04%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2407      | 97.33%  |
| Unknown        | 34        | 1.37%   |
| 32-bit         | 21        | 0.85%   |
| 64-bit         | 11        | 0.44%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 664       | 25.75%  |
| 0x206a7    | 148       | 5.74%   |
| 0x306a9    | 111       | 4.3%    |
| 0x1067a    | 77        | 2.99%   |
| 0x306c3    | 62        | 2.4%    |
| 0x40651    | 55        | 2.13%   |
| 0x30678    | 51        | 1.98%   |
| 0x806ec    | 50        | 1.94%   |
| 0x08108109 | 49        | 1.9%    |
| 0x806e9    | 47        | 1.82%   |
| 0x906ea    | 42        | 1.63%   |
| 0x806ea    | 41        | 1.59%   |
| 0x306d4    | 41        | 1.59%   |
| 0x6fd      | 38        | 1.47%   |
| 0x806c1    | 36        | 1.4%    |
| 0x506e3    | 36        | 1.4%    |
| 0x406e3    | 36        | 1.4%    |
| 0x06006705 | 34        | 1.32%   |
| 0x010000c8 | 33        | 1.28%   |
| 0x406c4    | 32        | 1.24%   |
| 0x20655    | 31        | 1.2%    |
| 0x906e9    | 30        | 1.16%   |
| 0x06001119 | 30        | 1.16%   |
| 0x10676    | 28        | 1.09%   |
| 0x0810100b | 27        | 1.05%   |
| 0x406c3    | 25        | 0.97%   |
| 0x08600106 | 25        | 0.97%   |
| 0x07030105 | 24        | 0.93%   |
| 0x106ca    | 22        | 0.85%   |
| 0x08108102 | 21        | 0.81%   |
| 0x08101016 | 21        | 0.81%   |
| 0x0600611a | 21        | 0.81%   |
| 0x0800820d | 20        | 0.78%   |
| 0x706a1    | 19        | 0.74%   |
| 0x20652    | 19        | 0.74%   |
| 0x05000119 | 19        | 0.74%   |
| 0x6fb      | 18        | 0.7%    |
| 0x506c9    | 17        | 0.66%   |
| 0x08608103 | 17        | 0.66%   |
| 0xa0652    | 16        | 0.62%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 305       | 12.34%  |
| SandyBridge      | 199       | 8.05%   |
| Haswell          | 168       | 6.8%    |
| IvyBridge        | 156       | 6.31%   |
| Silvermont       | 127       | 5.14%   |
| Penryn           | 123       | 4.98%   |
| Zen+             | 113       | 4.57%   |
| Skylake          | 107       | 4.33%   |
| Excavator        | 95        | 3.84%   |
| Core             | 90        | 3.64%   |
| Zen 2            | 74        | 2.99%   |
| Zen              | 72        | 2.91%   |
| Broadwell        | 66        | 2.67%   |
| Unknown          | 64        | 2.59%   |
| K10              | 62        | 2.51%   |
| Westmere         | 61        | 2.47%   |
| Piledriver       | 57        | 2.31%   |
| Zen 3            | 52        | 2.1%    |
| CometLake        | 49        | 1.98%   |
| TigerLake        | 46        | 1.86%   |
| Goldmont plus    | 45        | 1.82%   |
| K8 Hammer        | 41        | 1.66%   |
| Bobcat           | 41        | 1.66%   |
| Bonnell          | 38        | 1.54%   |
| Puma             | 35        | 1.42%   |
| IceLake          | 27        | 1.09%   |
| Goldmont         | 25        | 1.01%   |
| Steamroller      | 17        | 0.69%   |
| Alderlake Hybrid | 17        | 0.69%   |
| NetBurst         | 16        | 0.65%   |
| Nehalem          | 16        | 0.65%   |
| Jaguar           | 16        | 0.65%   |
| K10 Llano        | 13        | 0.53%   |
| P6               | 10        | 0.4%    |
| Bulldozer        | 10        | 0.4%    |
| K8 & K10 hybrid  | 9         | 0.36%   |
| Tremont          | 8         | 0.32%   |
| Gracemont        | 1         | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1456      | 52.32%  |
| AMD                              | 784       | 28.17%  |
| Nvidia                           | 522       | 18.76%  |
| Matrox Electronics Systems       | 12        | 0.43%   |
| VIA Technologies                 | 3         | 0.11%   |
| ASPEED Technology                | 3         | 0.11%   |
| ATI Technologies                 | 2         | 0.07%   |
| Silicon Integrated Systems [SiS] | 1         | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 166       | 5.74%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 95        | 3.28%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 87        | 3.01%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 70        | 2.42%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 66        | 2.28%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 61        | 2.11%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 55        | 1.9%    |
| Intel HD Graphics 620                                                                    | 53        | 1.83%   |
| Intel HD Graphics 5500                                                                   | 53        | 1.83%   |
| Intel Core Processor Integrated Graphics Controller                                      | 49        | 1.69%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 49        | 1.69%   |
| Intel UHD Graphics 620                                                                   | 46        | 1.59%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 44        | 1.52%   |
| AMD Renoir                                                                               | 44        | 1.52%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 43        | 1.49%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 43        | 1.49%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 41        | 1.42%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 41        | 1.42%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 41        | 1.42%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 41        | 1.42%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 37        | 1.28%   |
| Intel HD Graphics 530                                                                    | 37        | 1.28%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 33        | 1.14%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 33        | 1.14%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 33        | 1.14%   |
| Intel HD Graphics 630                                                                    | 31        | 1.07%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 29        | 1%      |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 28        | 0.97%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 27        | 0.93%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 27        | 0.93%   |
| AMD Lucienne                                                                             | 27        | 0.93%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 26        | 0.9%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 23        | 0.8%    |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 23        | 0.8%    |
| Intel HD Graphics 500                                                                    | 22        | 0.76%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 20        | 0.69%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 20        | 0.69%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 19        | 0.66%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 19        | 0.66%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 18        | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 1176      | 47.38%  |
| 1 x AMD         | 658       | 26.51%  |
| 1 x Nvidia      | 276       | 11.12%  |
| Intel + Nvidia  | 199       | 8.02%   |
| Intel + AMD     | 49        | 1.97%   |
| 2 x AMD         | 46        | 1.85%   |
| AMD + Nvidia    | 35        | 1.41%   |
| 1 x Matrox      | 10        | 0.4%    |
| Other           | 8         | 0.32%   |
| 2 x Intel       | 8         | 0.32%   |
| 2 x Nvidia      | 7         | 0.28%   |
| 1 x ASPEED      | 3         | 0.12%   |
| 1 x VIA         | 2         | 0.08%   |
| Nvidia + Matrox | 2         | 0.08%   |
| 3 x AMD         | 1         | 0.04%   |
| 1 x SiS         | 1         | 0.04%   |
| Nvidia + VIA    | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2174      | 87.31%  |
| Proprietary | 258       | 10.36%  |
| Unknown     | 58        | 2.33%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1482      | 58.46%  |
| 0.01-0.5   | 374       | 14.75%  |
| 1.01-2.0   | 251       | 9.9%    |
| 0.51-1.0   | 205       | 8.09%   |
| 3.01-4.0   | 94        | 3.71%   |
| 7.01-8.0   | 58        | 2.29%   |
| 5.01-6.0   | 46        | 1.81%   |
| 2.01-3.0   | 16        | 0.63%   |
| 8.01-16.0  | 6         | 0.24%   |
| 16.01-24.0 | 3         | 0.12%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 307       | 11.41%  |
| BOE                     | 300       | 11.15%  |
| Samsung Electronics     | 291       | 10.81%  |
| Chimei Innolux          | 260       | 9.66%   |
| LG Display              | 248       | 9.22%   |
| Hewlett-Packard         | 197       | 7.32%   |
| Dell                    | 160       | 5.95%   |
| Goldstar                | 91        | 3.38%   |
| Apple                   | 80        | 2.97%   |
| BenQ                    | 76        | 2.82%   |
| Acer                    | 73        | 2.71%   |
| AOC                     | 53        | 1.97%   |
| Lenovo                  | 46        | 1.71%   |
| Chi Mei Optoelectronics | 42        | 1.56%   |
| Unknown                 | 35        | 1.3%    |
| LG Philips              | 23        | 0.85%   |
| Sony                    | 22        | 0.82%   |
| Sharp                   | 22        | 0.82%   |
| ASUSTek Computer        | 21        | 0.78%   |
| Gateway                 | 20        | 0.74%   |
| Ancor Communications    | 20        | 0.74%   |
| ViewSonic               | 19        | 0.71%   |
| PANDA                   | 19        | 0.71%   |
| InfoVision              | 13        | 0.48%   |
| HannStar                | 11        | 0.41%   |
| ___                     | 9         | 0.33%   |
| VOR                     | 9         | 0.33%   |
| Insignia                | 8         | 0.3%    |
| LG Electronics          | 7         | 0.26%   |
| Hitachi                 | 7         | 0.26%   |
| FOX                     | 7         | 0.26%   |
| Vizio                   | 6         | 0.22%   |
| Valve                   | 6         | 0.22%   |
| Toshiba                 | 6         | 0.22%   |
| SAC                     | 6         | 0.22%   |
| HUAWEI                  | 6         | 0.22%   |
| Unknown                 | 6         | 0.22%   |
| Unknown (AAA)           | 5         | 0.19%   |
| Sceptre Tech            | 5         | 0.19%   |
| RTK                     | 5         | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 21        | 0.77%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 17        | 0.62%   |
| BOE LCD Monitor BOE076F 1366x768 344x194mm 15.5-inch                 | 17        | 0.62%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                | 16        | 0.58%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 15        | 0.55%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 15        | 0.55%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 14        | 0.51%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                 | 14        | 0.51%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch        | 13        | 0.47%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 12        | 0.44%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch          | 12        | 0.44%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch        | 12        | 0.44%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch          | 11        | 0.4%    |
| Hewlett-Packard w1907 HWP26A2 1440x900 408x255mm 18.9-inch           | 11        | 0.4%    |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 11        | 0.4%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 10        | 0.36%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 10        | 0.36%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 340x190mm 15.3-inch        | 10        | 0.36%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 10        | 0.36%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch            | 9         | 0.33%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 9         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 9         | 0.33%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch      | 9         | 0.33%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                | 9         | 0.33%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch      | 8         | 0.29%   |
| Chimei Innolux LCD Monitor CMN1487 1366x768 309x173mm 13.9-inch      | 8         | 0.29%   |
| Chimei Innolux LCD Monitor CMN1476 1366x768 309x174mm 14.0-inch      | 8         | 0.29%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                | 8         | 0.29%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                    | 8         | 0.29%   |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch               | 8         | 0.29%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch         | 7         | 0.26%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch             | 7         | 0.26%   |
| Insignia NS19D220NA16A BBY0019 1680x1050 640x384mm 29.4-inch         | 7         | 0.26%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                 | 7         | 0.26%   |
| Chimei Innolux LCD Monitor CMN15FD 1366x768 344x193mm 15.5-inch      | 7         | 0.26%   |
| Chimei Innolux LCD Monitor CMN1472 1366x768 309x174mm 14.0-inch      | 7         | 0.26%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                    | 7         | 0.26%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch       | 7         | 0.26%   |
| AU Optronics LCD Monitor AUO333C 1366x768 309x173mm 13.9-inch        | 7         | 0.26%   |
| AU Optronics LCD Monitor AUO323C 1366x768 309x173mm 13.9-inch        | 7         | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 912       | 35.43%  |
| 1920x1080 (FHD)    | 840       | 32.63%  |
| 1600x900 (HD+)     | 113       | 4.39%   |
| 1280x800 (WXGA)    | 102       | 3.96%   |
| 1440x900 (WXGA+)   | 92        | 3.57%   |
| 1280x1024 (SXGA)   | 79        | 3.07%   |
| 3840x2160 (4K)     | 77        | 2.99%   |
| 2560x1440 (QHD)    | 33        | 1.28%   |
| 1680x1050 (WSXGA+) | 33        | 1.28%   |
| 1360x768           | 29        | 1.13%   |
| 1024x768 (XGA)     | 27        | 1.05%   |
| 2560x1080          | 26        | 1.01%   |
| 1024x600           | 26        | 1.01%   |
| Unknown            | 21        | 0.82%   |
| 3440x1440          | 18        | 0.7%    |
| 2160x1440          | 18        | 0.7%    |
| 1920x1200 (WUXGA)  | 18        | 0.7%    |
| 2560x1600          | 17        | 0.66%   |
| 3840x1080          | 9         | 0.35%   |
| 1600x1200          | 8         | 0.31%   |
| 800x1280           | 7         | 0.27%   |
| 2880x1800          | 7         | 0.27%   |
| 2288x1287          | 7         | 0.27%   |
| 3200x1800 (QHD+)   | 5         | 0.19%   |
| 3000x2000          | 5         | 0.19%   |
| 2736x1824          | 5         | 0.19%   |
| 1280x960           | 5         | 0.19%   |
| 2520x1680          | 3         | 0.12%   |
| 3840x2400          | 2         | 0.08%   |
| 3600x1080          | 2         | 0.08%   |
| 3360x1080          | 2         | 0.08%   |
| 2240x1400          | 2         | 0.08%   |
| 1920x540           | 2         | 0.08%   |
| 1400x1050          | 2         | 0.08%   |
| 1280x768           | 2         | 0.08%   |
| 1152x864           | 2         | 0.08%   |
| 7280x2160          | 1         | 0.04%   |
| 6720x1440          | 1         | 0.04%   |
| 6000x1440          | 1         | 0.04%   |
| 5560x2160          | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 698       | 26.09%  |
| 13      | 360       | 13.46%  |
| 14      | 287       | 10.73%  |
| 21      | 145       | 5.42%   |
| 23      | 128       | 4.79%   |
| 18      | 109       | 4.07%   |
| 19      | 107       | 4%      |
| 17      | 102       | 3.81%   |
| 24      | 96        | 3.59%   |
| 27      | 90        | 3.36%   |
| Unknown | 85        | 3.18%   |
| 20      | 71        | 2.65%   |
| 11      | 64        | 2.39%   |
| 12      | 42        | 1.57%   |
| 31      | 39        | 1.46%   |
| 34      | 38        | 1.42%   |
| 16      | 28        | 1.05%   |
| 10      | 26        | 0.97%   |
| 22      | 25        | 0.93%   |
| 72      | 20        | 0.75%   |
| 84      | 18        | 0.67%   |
| 40      | 13        | 0.49%   |
| 54      | 11        | 0.41%   |
| 32      | 9         | 0.34%   |
| 29      | 8         | 0.3%    |
| 7       | 6         | 0.22%   |
| 46      | 5         | 0.19%   |
| 26      | 5         | 0.19%   |
| 25      | 5         | 0.19%   |
| 142     | 4         | 0.15%   |
| 52      | 4         | 0.15%   |
| 48      | 3         | 0.11%   |
| 39      | 3         | 0.11%   |
| 8       | 3         | 0.11%   |
| 49      | 2         | 0.07%   |
| 42      | 2         | 0.07%   |
| 37      | 2         | 0.07%   |
| 86      | 1         | 0.04%   |
| 74      | 1         | 0.04%   |
| 64      | 1         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1246      | 47.16%  |
| 401-500        | 411       | 15.56%  |
| 501-600        | 306       | 11.58%  |
| 201-300        | 262       | 9.92%   |
| 351-400        | 123       | 4.66%   |
| Unknown        | 85        | 3.22%   |
| 601-700        | 54        | 2.04%   |
| 701-800        | 49        | 1.85%   |
| 1501-2000      | 39        | 1.48%   |
| 1001-1500      | 30        | 1.14%   |
| 801-900        | 20        | 0.76%   |
| 1-100          | 7         | 0.26%   |
| More than 2000 | 4         | 0.15%   |
| 101-200        | 3         | 0.11%   |
| 901-1000       | 3         | 0.11%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1857      | 76.67%  |
| 16/10   | 279       | 11.52%  |
| 5/4     | 77        | 3.18%   |
| Unknown | 67        | 2.77%   |
| 4/3     | 45        | 1.86%   |
| 21/9    | 40        | 1.65%   |
| 3/2     | 36        | 1.49%   |
| 0.67    | 6         | 0.25%   |
| 1.00    | 5         | 0.21%   |
| 6/5     | 4         | 0.17%   |
| 32/9    | 3         | 0.12%   |
| 0.56    | 2         | 0.08%   |
| 0.62    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 713       | 26.93%  |
| 81-90          | 572       | 21.6%   |
| 201-250        | 324       | 12.24%  |
| 151-200        | 220       | 8.31%   |
| 141-150        | 142       | 5.36%   |
| 301-350        | 93        | 3.51%   |
| 351-500        | 87        | 3.29%   |
| Unknown        | 85        | 3.21%   |
| 71-80          | 80        | 3.02%   |
| More than 1000 | 65        | 2.45%   |
| 51-60          | 64        | 2.42%   |
| 121-130        | 38        | 1.44%   |
| 61-70          | 33        | 1.25%   |
| 251-300        | 31        | 1.17%   |
| 501-1000       | 31        | 1.17%   |
| 41-50          | 26        | 0.98%   |
| 131-140        | 15        | 0.57%   |
| 111-120        | 15        | 0.57%   |
| 1-40           | 10        | 0.38%   |
| 91-100         | 4         | 0.15%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 964       | 37.35%  |
| 51-100        | 780       | 30.22%  |
| 121-160       | 539       | 20.88%  |
| 161-240       | 100       | 3.87%   |
| Unknown       | 85        | 3.29%   |
| 1-50          | 81        | 3.14%   |
| More than 240 | 32        | 1.24%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 2031      | 80.28%  |
| 2     | 384       | 15.18%  |
| 0     | 76        | 3%      |
| 3     | 37        | 1.46%   |
| 4     | 2         | 0.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 1451      | 39.03%  |
| Intel                                 | 916       | 24.64%  |
| Qualcomm Atheros                      | 468       | 12.59%  |
| Broadcom                              | 283       | 7.61%   |
| Ralink Technology                     | 74        | 1.99%   |
| Ralink                                | 68        | 1.83%   |
| Broadcom Limited                      | 63        | 1.69%   |
| Nvidia                                | 52        | 1.4%    |
| TP-Link                               | 50        | 1.34%   |
| Marvell Technology Group              | 48        | 1.29%   |
| Qualcomm Atheros Communications       | 33        | 0.89%   |
| MediaTek                              | 30        | 0.81%   |
| Huawei Technologies                   | 19        | 0.51%   |
| ASIX Electronics                      | 18        | 0.48%   |
| Samsung Electronics                   | 11        | 0.3%    |
| Motorola PCS                          | 11        | 0.3%    |
| Mercucys                              | 11        | 0.3%    |
| DisplayLink                           | 10        | 0.27%   |
| Xiaomi                                | 9         | 0.24%   |
| Linksys                               | 6         | 0.16%   |
| D-Link                                | 6         | 0.16%   |
| Qualcomm                              | 5         | 0.13%   |
| ICS Advent                            | 5         | 0.13%   |
| VIA Technologies                      | 4         | 0.11%   |
| Spreadtrum Communications             | 4         | 0.11%   |
| Lenovo                                | 4         | 0.11%   |
| Google                                | 4         | 0.11%   |
| Dell                                  | 4         | 0.11%   |
| D-Link System                         | 4         | 0.11%   |
| OPPO Electronics                      | 3         | 0.08%   |
| NetGear                               | 3         | 0.08%   |
| Microchip Technology                  | 3         | 0.08%   |
| IBM                                   | 3         | 0.08%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.08%   |
| ZTE WCDMA Technologies MSM            | 2         | 0.05%   |
| Wacom                                 | 2         | 0.05%   |
| LG Electronics                        | 2         | 0.05%   |
| JMicron Technology                    | 2         | 0.05%   |
| Tenda                                 | 1         | 0.03%   |
| T & A Mobile Phones                   | 1         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 848       | 18.98%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 316       | 7.07%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 107       | 2.39%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 101       | 2.26%   |
| Intel Wi-Fi 6 AX200                                               | 74        | 1.66%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 73        | 1.63%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 65        | 1.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 60        | 1.34%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 58        | 1.3%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 58        | 1.3%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 54        | 1.21%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 53        | 1.19%   |
| Broadcom BCM43142 802.11b/g/n                                     | 46        | 1.03%   |
| Intel Wireless 8265 / 8275                                        | 45        | 1.01%   |
| Intel Wireless 7265                                               | 43        | 0.96%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 39        | 0.87%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 38        | 0.85%   |
| Intel Wi-Fi 6 AX201                                               | 38        | 0.85%   |
| Intel Ethernet Connection I217-LM                                 | 38        | 0.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 37        | 0.83%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 35        | 0.78%   |
| Intel Wireless 7260                                               | 35        | 0.78%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 35        | 0.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 34        | 0.76%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 32        | 0.72%   |
| Intel Wireless 8260                                               | 32        | 0.72%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 31        | 0.69%   |
| Intel I211 Gigabit Network Connection                             | 31        | 0.69%   |
| Intel Wireless 3165                                               | 30        | 0.67%   |
| Ralink MT7601U Wireless Adapter                                   | 28        | 0.63%   |
| Qualcomm Atheros AR9271 802.11n                                   | 28        | 0.63%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 27        | 0.6%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 26        | 0.58%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 24        | 0.54%   |
| Realtek 802.11ac NIC                                              | 23        | 0.51%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 23        | 0.51%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 23        | 0.51%   |
| Realtek RTL8125 2.5GbE Controller                                 | 22        | 0.49%   |
| Intel Wireless 3160                                               | 22        | 0.49%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 22        | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 671       | 31.09%  |
| Realtek Semiconductor                 | 550       | 25.49%  |
| Qualcomm Atheros                      | 389       | 18.03%  |
| Broadcom                              | 208       | 9.64%   |
| Ralink Technology                     | 74        | 3.43%   |
| Ralink                                | 68        | 3.15%   |
| TP-Link                               | 48        | 2.22%   |
| Broadcom Limited                      | 43        | 1.99%   |
| Qualcomm Atheros Communications       | 33        | 1.53%   |
| MediaTek                              | 25        | 1.16%   |
| Mercucys                              | 11        | 0.51%   |
| Marvell Technology Group              | 6         | 0.28%   |
| D-Link                                | 6         | 0.28%   |
| Linksys                               | 4         | 0.19%   |
| Qualcomm                              | 3         | 0.14%   |
| NetGear                               | 3         | 0.14%   |
| Dell                                  | 3         | 0.14%   |
| D-Link System                         | 3         | 0.14%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.14%   |
| Wacom                                 | 2         | 0.09%   |
| Tenda                                 | 1         | 0.05%   |
| Qualcomm Technologies                 | 1         | 0.05%   |
| Micro Star International              | 1         | 0.05%   |
| Gemtek                                | 1         | 0.05%   |
| Belkin Components                     | 1         | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 107       | 4.89%   |
| Intel Wi-Fi 6 AX200                                            | 74        | 3.38%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 73        | 3.34%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 65        | 2.97%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 60        | 2.74%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 58        | 2.65%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 58        | 2.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 54        | 2.47%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 53        | 2.42%   |
| Broadcom BCM43142 802.11b/g/n                                  | 46        | 2.1%    |
| Intel Wireless 8265 / 8275                                     | 45        | 2.06%   |
| Intel Wireless 7265                                            | 43        | 1.97%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 39        | 1.78%   |
| Intel Wi-Fi 6 AX201                                            | 38        | 1.74%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 37        | 1.69%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 35        | 1.6%    |
| Intel Wireless 7260                                            | 35        | 1.6%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 35        | 1.6%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 34        | 1.55%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 32        | 1.46%   |
| Intel Wireless 8260                                            | 32        | 1.46%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 31        | 1.42%   |
| Intel Wireless 3165                                            | 30        | 1.37%   |
| Ralink MT7601U Wireless Adapter                                | 28        | 1.28%   |
| Qualcomm Atheros AR9271 802.11n                                | 28        | 1.28%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 27        | 1.23%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 24        | 1.1%    |
| Realtek 802.11ac NIC                                           | 23        | 1.05%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 23        | 1.05%   |
| Intel Wireless 3160                                            | 22        | 1.01%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 22        | 1.01%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 21        | 0.96%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 20        | 0.91%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 19        | 0.87%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 19        | 0.87%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 19        | 0.87%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 18        | 0.82%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 18        | 0.82%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 17        | 0.78%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 16        | 0.73%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1238      | 55.57%  |
| Intel                                  | 483       | 21.68%  |
| Qualcomm Atheros                       | 143       | 6.42%   |
| Broadcom                               | 119       | 5.34%   |
| Nvidia                                 | 52        | 2.33%   |
| Marvell Technology Group               | 42        | 1.89%   |
| Broadcom Limited                       | 20        | 0.9%    |
| Huawei Technologies                    | 18        | 0.81%   |
| ASIX Electronics                       | 18        | 0.81%   |
| Samsung Electronics                    | 11        | 0.49%   |
| DisplayLink                            | 10        | 0.45%   |
| Xiaomi                                 | 9         | 0.4%    |
| Motorola PCS                           | 7         | 0.31%   |
| MediaTek                               | 5         | 0.22%   |
| ICS Advent                             | 5         | 0.22%   |
| VIA Technologies                       | 4         | 0.18%   |
| Spreadtrum Communications              | 4         | 0.18%   |
| Google                                 | 4         | 0.18%   |
| OPPO Electronics                       | 3         | 0.13%   |
| Lenovo                                 | 3         | 0.13%   |
| IBM                                    | 3         | 0.13%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.09%   |
| TP-Link                                | 2         | 0.09%   |
| Qualcomm                               | 2         | 0.09%   |
| Microchip Technology                   | 2         | 0.09%   |
| Linksys                                | 2         | 0.09%   |
| LG Electronics                         | 2         | 0.09%   |
| JMicron Technology                     | 2         | 0.09%   |
| T & A Mobile Phones                    | 1         | 0.04%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.04%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.04%   |
| Microsoft                              | 1         | 0.04%   |
| Lab126                                 | 1         | 0.04%   |
| Insyde Software                        | 1         | 0.04%   |
| HTC (High Tech Computer)               | 1         | 0.04%   |
| Hisense                                | 1         | 0.04%   |
| Foxconn / Hon Hai                      | 1         | 0.04%   |
| D-Link System                          | 1         | 0.04%   |
| ADMtek                                 | 1         | 0.04%   |
| Accton Technology                      | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 848       | 37.51%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 316       | 13.98%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 101       | 4.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 38        | 1.68%   |
| Intel Ethernet Connection I217-LM                                 | 38        | 1.68%   |
| Intel I211 Gigabit Network Connection                             | 31        | 1.37%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 26        | 1.15%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 23        | 1.02%   |
| Realtek RTL8125 2.5GbE Controller                                 | 22        | 0.97%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 21        | 0.93%   |
| Nvidia MCP61 Ethernet                                             | 21        | 0.93%   |
| Intel Ethernet Connection I218-LM                                 | 19        | 0.84%   |
| Intel Ethernet Connection (2) I219-V                              | 17        | 0.75%   |
| Huawei JKM-LX1                                                    | 16        | 0.71%   |
| Intel Ethernet Connection (7) I219-V                              | 15        | 0.66%   |
| Intel Ethernet Connection (4) I219-LM                             | 15        | 0.66%   |
| Intel Ethernet Connection (3) I218-LM                             | 15        | 0.66%   |
| Intel Ethernet Connection (2) I219-LM                             | 15        | 0.66%   |
| Intel 82579V Gigabit Network Connection                           | 15        | 0.66%   |
| ASIX AX88179 Gigabit Ethernet                                     | 15        | 0.66%   |
| Intel 82567LM Gigabit Network Connection                          | 14        | 0.62%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 13        | 0.57%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 12        | 0.53%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 12        | 0.53%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 12        | 0.53%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 12        | 0.53%   |
| Nvidia MCP79 Ethernet                                             | 12        | 0.53%   |
| Intel 82577LM Gigabit Network Connection                          | 12        | 0.53%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 12        | 0.53%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 11        | 0.49%   |
| Intel Ethernet Controller I225-V                                  | 11        | 0.49%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 10        | 0.44%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 10        | 0.44%   |
| Intel Ethernet Connection I217-V                                  | 10        | 0.44%   |
| Intel 82574L Gigabit Network Connection                           | 10        | 0.44%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 10        | 0.44%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 9         | 0.4%    |
| Intel Ethernet Connection (6) I219-V                              | 9         | 0.4%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 8         | 0.35%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 8         | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2115      | 50.73%  |
| WiFi     | 2033      | 48.76%  |
| Modem    | 12        | 0.29%   |
| Unknown  | 9         | 0.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1593      | 61.25%  |
| Ethernet | 1006      | 38.68%  |
| Unknown  | 2         | 0.08%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1446      | 58.45%  |
| 1     | 951       | 38.44%  |
| 0     | 45        | 1.82%   |
| 3     | 22        | 0.89%   |
| 4     | 6         | 0.24%   |
| 8     | 3         | 0.12%   |
| 6     | 1         | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1735      | 68.36%  |
| Yes  | 803       | 31.64%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 506       | 34.07%  |
| Realtek Semiconductor           | 259       | 17.44%  |
| Qualcomm Atheros Communications | 129       | 8.69%   |
| Cambridge Silicon Radio         | 111       | 7.47%   |
| Broadcom                        | 92        | 6.2%    |
| Apple                           | 71        | 4.78%   |
| Lite-On Technology              | 54        | 3.64%   |
| IMC Networks                    | 52        | 3.5%    |
| Foxconn / Hon Hai               | 43        | 2.9%    |
| Dell                            | 30        | 2.02%   |
| Realtek                         | 27        | 1.82%   |
| Hewlett-Packard                 | 23        | 1.55%   |
| Toshiba                         | 19        | 1.28%   |
| Ralink                          | 18        | 1.21%   |
| ASUSTek Computer                | 13        | 0.88%   |
| Ralink Technology               | 7         | 0.47%   |
| TP-Link                         | 6         | 0.4%    |
| Marvell Semiconductor           | 6         | 0.4%    |
| MediaTek                        | 5         | 0.34%   |
| Foxconn International           | 4         | 0.27%   |
| Alps Electric                   | 4         | 0.27%   |
| USI                             | 1         | 0.07%   |
| Roper                           | 1         | 0.07%   |
| Micro Star International        | 1         | 0.07%   |
| Integrated System Solution      | 1         | 0.07%   |
| Dynex                           | 1         | 0.07%   |
| Chicony Electronics             | 1         | 0.07%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 198       | 13.32%  |
| Realtek Bluetooth Radio                                                             | 115       | 7.73%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 111       | 7.46%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 109       | 7.33%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 94        | 6.32%   |
| Intel AX201 Bluetooth                                                               | 77        | 5.18%   |
| Intel AX200 Bluetooth                                                               | 72        | 4.84%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 64        | 4.3%    |
| Apple Bluetooth Host Controller                                                     | 31        | 2.08%   |
| Realtek Bluetooth Radio                                                             | 27        | 1.82%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 26        | 1.75%   |
| IMC Networks Bluetooth Radio                                                        | 24        | 1.61%   |
| Apple Bluetooth USB Host Controller                                                 | 22        | 1.48%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 19        | 1.28%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 19        | 1.28%   |
| Ralink RT3290 Bluetooth                                                             | 18        | 1.21%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 18        | 1.21%   |
| Lite-On Bluetooth Device                                                            | 17        | 1.14%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 16        | 1.08%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 16        | 1.08%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 16        | 1.08%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 16        | 1.08%   |
| Realtek RTL8723B Bluetooth                                                          | 15        | 1.01%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 14        | 0.94%   |
| Realtek RTL8821A Bluetooth                                                          | 12        | 0.81%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 12        | 0.81%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 11        | 0.74%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 11        | 0.74%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 11        | 0.74%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 10        | 0.67%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 10        | 0.67%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 9         | 0.61%   |
| Intel Bluetooth Device                                                              | 9         | 0.61%   |
| IMC Networks Wireless_Device                                                        | 9         | 0.61%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 8         | 0.54%   |
| IMC Networks Bluetooth Device                                                       | 8         | 0.54%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 8         | 0.54%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 8         | 0.54%   |
| Apple Bluetooth HCI                                                                 | 8         | 0.54%   |
| Intel AX210 Bluetooth                                                               | 7         | 0.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1651      | 54.13%  |
| AMD                                          | 788       | 25.84%  |
| Nvidia                                       | 404       | 13.25%  |
| C-Media Electronics                          | 29        | 0.95%   |
| Logitech                                     | 21        | 0.69%   |
| Generalplus Technology                       | 16        | 0.52%   |
| Texas Instruments                            | 15        | 0.49%   |
| Realtek Semiconductor                        | 8         | 0.26%   |
| Kingston Technology                          | 8         | 0.26%   |
| Creative Labs                                | 8         | 0.26%   |
| JMTek                                        | 7         | 0.23%   |
| GN Netcom                                    | 7         | 0.23%   |
| VIA Technologies                             | 6         | 0.2%    |
| Plantronics                                  | 6         | 0.2%    |
| ASUSTek Computer                             | 6         | 0.2%    |
| Tenx Technology                              | 5         | 0.16%   |
| Razer USA                                    | 5         | 0.16%   |
| Lenovo                                       | 5         | 0.16%   |
| Syntek                                       | 4         | 0.13%   |
| Creative Technology                          | 4         | 0.13%   |
| Corsair                                      | 4         | 0.13%   |
| Focusrite-Novation                           | 3         | 0.1%    |
| Synaptics                                    | 2         | 0.07%   |
| SAVITECH                                     | 2         | 0.07%   |
| Samson Technologies                          | 2         | 0.07%   |
| M-Audio                                      | 2         | 0.07%   |
| BR23                                         | 2         | 0.07%   |
| ATI Technologies                             | 2         | 0.07%   |
| Apple                                        | 2         | 0.07%   |
| Anlya.cn                                     | 2         | 0.07%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.03%   |
| Yamaha                                       | 1         | 0.03%   |
| Thesycon Systemsoftware & Consulting         | 1         | 0.03%   |
| Sony                                         | 1         | 0.03%   |
| Silicon Integrated Systems [SiS]             | 1         | 0.03%   |
| Shure                                        | 1         | 0.03%   |
| Sennheiser Communications                    | 1         | 0.03%   |
| Samsung Electronics                          | 1         | 0.03%   |
| Microsoft                                    | 1         | 0.03%   |
| Micro Star International                     | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 230       | 6.02%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 173       | 4.53%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 166       | 4.34%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 156       | 4.08%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 139       | 3.64%   |
| AMD FCH Azalia Controller                                                                         | 138       | 3.61%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 114       | 2.98%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 93        | 2.43%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 92        | 2.41%   |
| AMD Kabini HDMI/DP Audio                                                                          | 92        | 2.41%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 92        | 2.41%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 85        | 2.22%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 72        | 1.88%   |
| Intel 8 Series HD Audio Controller                                                                | 71        | 1.86%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 70        | 1.83%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 70        | 1.83%   |
| Intel Cannon Lake PCH cAVS                                                                        | 67        | 1.75%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 63        | 1.65%   |
| Intel Broadwell-U Audio Controller                                                                | 62        | 1.62%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 61        | 1.6%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 59        | 1.54%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 56        | 1.47%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 54        | 1.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 50        | 1.31%   |
| AMD High Definition Audio Controller                                                              | 49        | 1.28%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 47        | 1.23%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 46        | 1.2%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 45        | 1.18%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 40        | 1.05%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 40        | 1.05%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 37        | 0.97%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 37        | 0.97%   |
| AMD Trinity HDMI Audio Controller                                                                 | 37        | 0.97%   |
| Intel Comet Lake PCH cAVS                                                                         | 33        | 0.86%   |
| Intel 200 Series PCH HD Audio                                                                     | 28        | 0.73%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 27        | 0.71%   |
| Nvidia MCP61 High Definition Audio                                                                | 26        | 0.68%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 26        | 0.68%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 25        | 0.65%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 25        | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                                           | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 344       | 22.9%   |
| SK hynix                                         | 263       | 17.51%  |
| Kingston                                         | 241       | 16.05%  |
| Micron Technology                                | 165       | 10.99%  |
| Unknown                                          | 121       | 8.06%   |
| A-DATA Technology                                | 117       | 7.79%   |
| Ramaxel Technology                               | 38        | 2.53%   |
| Corsair                                          | 38        | 2.53%   |
| Crucial                                          | 29        | 1.93%   |
| Elpida                                           | 27        | 1.8%    |
| Nanya Technology                                 | 21        | 1.4%    |
| Unknown (ABCD)                                   | 15        | 1%      |
| Team                                             | 13        | 0.87%   |
| Patriot                                          | 9         | 0.6%    |
| Qimonda                                          | 7         | 0.47%   |
| PNY                                              | 7         | 0.47%   |
| Unknown                                          | 7         | 0.47%   |
| Timetec                                          | 5         | 0.33%   |
| G.Skill                                          | 5         | 0.33%   |
| Transcend                                        | 4         | 0.27%   |
| ChangXin Memory                                  | 3         | 0.2%    |
| Hewlett-Packard                                  | 2         | 0.13%   |
| CSX                                              | 2         | 0.13%   |
| Avant                                            | 2         | 0.13%   |
| Unknown (0x8AF1)                                 | 1         | 0.07%   |
| Unknown (0x4D342037305435363633515A332D43453620) | 1         | 0.07%   |
| Unknown (0x29E)                                  | 1         | 0.07%   |
| Unknown (0x0E9D)                                 | 1         | 0.07%   |
| Unifosa                                          | 1         | 0.07%   |
| Silicon Power                                    | 1         | 0.07%   |
| SHARETRONIC                                      | 1         | 0.07%   |
| SGS/Thomson                                      | 1         | 0.07%   |
| S                                                | 1         | 0.07%   |
| Patriot Memory                                   | 1         | 0.07%   |
| MKF_SMBIOS_TYPE17_MANUFACTURER                   | 1         | 0.07%   |
| Goldkey                                          | 1         | 0.07%   |
| Gigabyte Technology                              | 1         | 0.07%   |
| Apacer                                           | 1         | 0.07%   |
| Aeneon                                           | 1         | 0.07%   |
| 3235CB0010E4                                     | 1         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 25        | 1.53%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 17        | 1.04%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 17        | 1.04%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s                      | 15        | 0.92%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 14        | 0.86%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 14        | 0.86%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 13        | 0.79%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 12        | 0.73%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 12        | 0.73%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 12        | 0.73%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 11        | 0.67%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 11        | 0.67%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 11        | 0.67%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 10        | 0.61%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s         | 10        | 0.61%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 9         | 0.55%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 9         | 0.55%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s              | 9         | 0.55%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 8         | 0.49%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 8         | 0.49%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 8         | 0.49%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 8         | 0.49%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s          | 8         | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 7         | 0.43%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.43%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.43%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 0.43%   |
| Unknown                                                          | 7         | 0.43%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 6         | 0.37%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 6         | 0.37%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 6         | 0.37%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 6         | 0.37%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 6         | 0.37%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 6         | 0.37%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.37%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 6         | 0.37%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 6         | 0.37%   |
| A-DATA RAM DDR4 2666 8GB DIMM DDR4 3200MT/s                      | 6         | 0.37%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 5         | 0.31%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 2933MT/s               | 5         | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 523       | 42.11%  |
| DDR3    | 474       | 38.16%  |
| DDR2    | 85        | 6.84%   |
| SDRAM   | 41        | 3.3%    |
| LPDDR4  | 40        | 3.22%   |
| Unknown | 27        | 2.17%   |
| LPDDR3  | 26        | 2.09%   |
| DDR     | 13        | 1.05%   |
| DDR5    | 6         | 0.48%   |
| LPDDR5  | 5         | 0.4%    |
| RAM     | 1         | 0.08%   |
| DRAM    | 1         | 0.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 754       | 61.4%   |
| DIMM         | 364       | 29.64%  |
| Row Of Chips | 100       | 8.14%   |
| Chip         | 5         | 0.41%   |
| RIMM         | 2         | 0.16%   |
| Unknown      | 2         | 0.16%   |
| FB-DIMM      | 1         | 0.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 503       | 35.57%  |
| 4096  | 432       | 30.55%  |
| 2048  | 220       | 15.56%  |
| 16384 | 132       | 9.34%   |
| 1024  | 67        | 4.74%   |
| 32768 | 47        | 3.32%   |
| 512   | 8         | 0.57%   |
| 256   | 2         | 0.14%   |
| 65536 | 1         | 0.07%   |
| 32767 | 1         | 0.07%   |
| 128   | 1         | 0.07%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 320       | 23.29%  |
| 2667    | 199       | 14.48%  |
| 3200    | 154       | 11.21%  |
| 1333    | 104       | 7.57%   |
| 2400    | 83        | 6.04%   |
| 2133    | 68        | 4.95%   |
| 667     | 47        | 3.42%   |
| 1334    | 44        | 3.2%    |
| 3600    | 40        | 2.91%   |
| 800     | 36        | 2.62%   |
| Unknown | 31        | 2.26%   |
| 3266    | 27        | 1.97%   |
| 1867    | 19        | 1.38%   |
| 1067    | 19        | 1.38%   |
| 4267    | 16        | 1.16%   |
| 533     | 13        | 0.95%   |
| 2048    | 12        | 0.87%   |
| 1866    | 12        | 0.87%   |
| 1066    | 11        | 0.8%    |
| 3733    | 10        | 0.73%   |
| 2933    | 8         | 0.58%   |
| 3000    | 7         | 0.51%   |
| 2800    | 7         | 0.51%   |
| 975     | 7         | 0.51%   |
| 4199    | 6         | 0.44%   |
| 3466    | 6         | 0.44%   |
| 3400    | 6         | 0.44%   |
| 8400    | 5         | 0.36%   |
| 6400    | 5         | 0.36%   |
| 4800    | 5         | 0.36%   |
| 2666    | 5         | 0.36%   |
| 49926   | 4         | 0.29%   |
| 3933    | 4         | 0.29%   |
| 1331    | 4         | 0.29%   |
| 3800    | 3         | 0.22%   |
| 400     | 3         | 0.22%   |
| 2000    | 2         | 0.15%   |
| 1800    | 2         | 0.15%   |
| 1639    | 2         | 0.15%   |
| 1332    | 2         | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Seiko Epson            | 15        | 24.59%  |
| Hewlett-Packard        | 15        | 24.59%  |
| Brother Industries     | 13        | 21.31%  |
| Canon                  | 7         | 11.48%  |
| Samsung Electronics    | 6         | 9.84%   |
| Kyocera                | 2         | 3.28%   |
| TSC Auto ID Technology | 1         | 1.64%   |
| QinHeng Electronics    | 1         | 1.64%   |
| BIXOLON                | 1         | 1.64%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Seiko Epson L120 Series                 | 6         | 9.68%   |
| HP DeskJet 1110 series                  | 3         | 4.84%   |
| HP LaserJet Professional P 1102w        | 2         | 3.23%   |
| HP DeskJet 2300 series                  | 2         | 3.23%   |
| Canon G3000 series                      | 2         | 3.23%   |
| Brother MFC-J470DW                      | 2         | 3.23%   |
| Brother HL-1110 series                  | 2         | 3.23%   |
| TSC Auto ID Printer                     | 1         | 1.61%   |
| Seiko Epson XP-230 Series               | 1         | 1.61%   |
| Seiko Epson Printer                     | 1         | 1.61%   |
| Seiko Epson L805 Series                 | 1         | 1.61%   |
| Seiko Epson L6160 Series                | 1         | 1.61%   |
| Seiko Epson L555 Series                 | 1         | 1.61%   |
| Seiko Epson L300 Series                 | 1         | 1.61%   |
| Seiko Epson L210 Series                 | 1         | 1.61%   |
| Seiko Epson L200 Series                 | 1         | 1.61%   |
| Seiko Epson L1300 Series                | 1         | 1.61%   |
| Seiko Epson ET-2700 Series              | 1         | 1.61%   |
| Samsung Xerox Phaser 3117 Laser Printer | 1         | 1.61%   |
| Samsung SCX-4600 Series                 | 1         | 1.61%   |
| Samsung ML-1660 Series                  | 1         | 1.61%   |
| Samsung ML-1640 Series Laser Printer    | 1         | 1.61%   |
| Samsung M283x Series                    | 1         | 1.61%   |
| Samsung M2020 Series                    | 1         | 1.61%   |
| QinHeng CH340S                          | 1         | 1.61%   |
| Kyocera FS-1116MFP                      | 1         | 1.61%   |
| Kyocera FS-1030D printer                | 1         | 1.61%   |
| HP OfficeJet Pro 7740 series            | 1         | 1.61%   |
| HP LaserJet P3010 Series                | 1         | 1.61%   |
| HP DeskJet F4200 series                 | 1         | 1.61%   |
| HP DeskJet F300 series                  | 1         | 1.61%   |
| HP DeskJet 4720 series                  | 1         | 1.61%   |
| HP DeskJet 3700 series                  | 1         | 1.61%   |
| HP DeskJet 2600 series                  | 1         | 1.61%   |
| HP Deskjet 2540 series                  | 1         | 1.61%   |
| Canon PIXMA MG3500 Series               | 1         | 1.61%   |
| Canon PIXMA iP3000x Printer             | 1         | 1.61%   |
| Canon iP2600 series                     | 1         | 1.61%   |
| Canon G2010 series                      | 1         | 1.61%   |
| Canon G1010 series                      | 1         | 1.61%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 5         | 83.33%  |
| Seiko Epson     | 1         | 16.67%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| HP ScanJet 5590                                    | 2         | 33.33%  |
| HP ScanJet 4500C/5550C                             | 2         | 33.33%  |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO] | 1         | 16.67%  |
| HP ScanJet 3300c                                   | 1         | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 349       | 20.95%  |
| Microdia                               | 155       | 9.3%    |
| IMC Networks                           | 151       | 9.06%   |
| Realtek Semiconductor                  | 111       | 6.66%   |
| Cheng Uei Precision Industry (Foxlink) | 89        | 5.34%   |
| Sunplus Innovation Technology          | 81        | 4.86%   |
| Bison Electronics                      | 73        | 4.38%   |
| Quanta                                 | 71        | 4.26%   |
| Suyin                                  | 70        | 4.2%    |
| Apple                                  | 59        | 3.54%   |
| Logitech                               | 58        | 3.48%   |
| Syntek                                 | 52        | 3.12%   |
| Lite-On Technology                     | 44        | 2.64%   |
| Acer                                   | 26        | 1.56%   |
| Generalplus Technology                 | 24        | 1.44%   |
| Silicon Motion                         | 21        | 1.26%   |
| Ricoh                                  | 21        | 1.26%   |
| Alcor Micro                            | 18        | 1.08%   |
| Importek                               | 17        | 1.02%   |
| Luxvisions Innotech Limited            | 14        | 0.84%   |
| Microsoft                              | 12        | 0.72%   |
| Samsung Electronics                    | 11        | 0.66%   |
| Jieli Technology                       | 10        | 0.6%    |
| Z-Star Microelectronics                | 9         | 0.54%   |
| GEMBIRD                                | 8         | 0.48%   |
| ALi                                    | 8         | 0.48%   |
| Y Media                                | 7         | 0.42%   |
| Sonix Technology                       | 7         | 0.42%   |
| OmniVision Technologies                | 7         | 0.42%   |
| Primax Electronics                     | 6         | 0.36%   |
| Genesys Logic                          | 6         | 0.36%   |
| HRY                                    | 5         | 0.3%    |
| MacroSilicon                           | 4         | 0.24%   |
| LG Electronics                         | 4         | 0.24%   |
| Lenovo                                 | 4         | 0.24%   |
| KYE Systems (Mouse Systems)            | 4         | 0.24%   |
| Xiongmai                               | 3         | 0.18%   |
| Sunplus Technology                     | 3         | 0.18%   |
| icSpring                               | 3         | 0.18%   |
| Hewlett-Packard                        | 3         | 0.18%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 48        | 2.86%   |
| Microdia Integrated_Webcam_HD                                              | 46        | 2.74%   |
| IMC Networks Integrated Camera                                             | 35        | 2.09%   |
| Chicony HD WebCam                                                          | 33        | 1.97%   |
| Realtek Integrated_Webcam_HD                                               | 28        | 1.67%   |
| Sunplus Integrated_Webcam_HD                                               | 27        | 1.61%   |
| IMC Networks HD Camera                                                     | 25        | 1.49%   |
| Bison Integrated Camera                                                    | 24        | 1.43%   |
| Chicony HP Webcam                                                          | 22        | 1.31%   |
| Logitech HD Pro Webcam C920                                                | 21        | 1.25%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 21        | 1.25%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 20        | 1.19%   |
| Apple FaceTime HD Camera                                                   | 20        | 1.19%   |
| Generalplus CAMERA - UVC                                                   | 19        | 1.13%   |
| Chicony HP Truevision HD camera                                            | 19        | 1.13%   |
| Syntek Integrated Camera                                                   | 18        | 1.07%   |
| Quanta HP Webcam                                                           | 18        | 1.07%   |
| Lite-On HP Wide Vision HD Camera                                           | 18        | 1.07%   |
| Microdia Integrated Webcam                                                 | 17        | 1.01%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                           | 17        | 1.01%   |
| Chicony HP Truevision HD                                                   | 16        | 0.95%   |
| Syntek Lenovo EasyCamera                                                   | 15        | 0.89%   |
| Sunplus HD WebCam                                                          | 15        | 0.89%   |
| IMC Networks EasyCamera                                                    | 15        | 0.89%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 14        | 0.83%   |
| Acer Integrated Camera                                                     | 14        | 0.83%   |
| Logitech Webcam C270                                                       | 13        | 0.77%   |
| Chicony USB 2.0 Camera                                                     | 13        | 0.77%   |
| Chicony HP Wide Vision HD Camera                                           | 12        | 0.72%   |
| Apple Built-in iSight                                                      | 12        | 0.72%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 11        | 0.66%   |
| Microdia Lenovo EasyCamera                                                 | 11        | 0.66%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                           | 11        | 0.66%   |
| Apple FaceTime HD Camera (Built-in)                                        | 11        | 0.66%   |
| Suyin HP Truevision HD                                                     | 10        | 0.6%    |
| Quanta HP TrueVision HD Camera                                             | 10        | 0.6%    |
| Microdia Sonix USB 2.0 Camera                                              | 10        | 0.6%    |
| Jieli USB PHY 2.0                                                          | 10        | 0.6%    |
| Chicony HP HD Camera                                                       | 10        | 0.6%    |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 10        | 0.6%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 89        | 32.36%  |
| Shenzhen Goodix Technology         | 66        | 24%     |
| Synaptics                          | 48        | 17.45%  |
| AuthenTec                          | 24        | 8.73%   |
| Upek                               | 18        | 6.55%   |
| Elan Microelectronics              | 10        | 3.64%   |
| Focal-systems.Corp                 | 7         | 2.55%   |
| STMicroelectronics                 | 5         | 1.82%   |
| LighTuning Technology              | 3         | 1.09%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.73%   |
| Suprema                            | 1         | 0.36%   |
| Samsung Electronics                | 1         | 0.36%   |
| DigitalPersona                     | 1         | 0.36%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 57        | 20.73%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 19        | 6.91%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 17        | 6.18%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 16        | 5.82%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 13        | 4.73%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 13        | 4.73%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 11        | 4%      |
| Validity Sensors VFS5011 Fingerprint Reader                                | 10        | 3.64%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 10        | 3.64%   |
| Shenzhen Goodix Fingerprint Reader                                         | 8         | 2.91%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 7         | 2.55%   |
| Validity Sensors VFS491                                                    | 6         | 2.18%   |
| AuthenTec AES2810                                                          | 6         | 2.18%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 1.82%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 1.82%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 1.82%   |
| STMicroelectronics Fingerprint Reader                                      | 5         | 1.82%   |
| Elan ELAN:ARM-M4                                                           | 5         | 1.82%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 1.45%   |
| Elan ELAN:Fingerprint                                                      | 4         | 1.45%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 1.09%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 1.09%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 3         | 1.09%   |
| Synaptics WBDI                                                             | 3         | 1.09%   |
| Synaptics Fingerprint reader [HP G6]                                       | 3         | 1.09%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 1.09%   |
| AuthenTec AES1600                                                          | 3         | 1.09%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.73%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 0.73%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.73%   |
| Synaptics UWP WBDI Device                                                  | 2         | 0.73%   |
| Synaptics UWP WBDI                                                         | 2         | 0.73%   |
| Synaptics  WBDI                                                            | 2         | 0.73%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 0.73%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 0.73%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 0.73%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.36%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.36%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 1         | 0.36%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.36%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 48        | 63.16%  |
| Alcor Micro           | 13        | 17.11%  |
| Upek                  | 7         | 9.21%   |
| Lenovo                | 6         | 7.89%   |
| O2 Micro              | 1         | 1.32%   |
| Gemalto (was Gemplus) | 1         | 1.32%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 19        | 25%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 13        | 17.11%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 13        | 17.11%  |
| Broadcom 5880                                                                | 8         | 10.53%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 7         | 9.21%   |
| Broadcom 58200                                                               | 7         | 9.21%   |
| Lenovo Integrated Smart Card Reader                                          | 6         | 7.89%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 1.32%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.32%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 1.32%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1739      | 69.01%  |
| 1     | 639       | 25.36%  |
| 2     | 122       | 4.84%   |
| 3     | 14        | 0.56%   |
| 6     | 2         | 0.08%   |
| 5     | 2         | 0.08%   |
| 7     | 1         | 0.04%   |
| 4     | 1         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 272       | 29.34%  |
| Graphics card            | 181       | 19.53%  |
| Net/wireless             | 151       | 16.29%  |
| Chipcard                 | 72        | 7.77%   |
| Multimedia controller    | 71        | 7.66%   |
| Communication controller | 43        | 4.64%   |
| Bluetooth                | 30        | 3.24%   |
| Camera                   | 29        | 3.13%   |
| Unassigned class         | 14        | 1.51%   |
| Net/ethernet             | 13        | 1.4%    |
| Storage                  | 11        | 1.19%   |
| Sound                    | 11        | 1.19%   |
| Card reader              | 7         | 0.76%   |
| Network                  | 6         | 0.65%   |
| Modem                    | 6         | 0.65%   |
| Storage/raid             | 3         | 0.32%   |
| Storage/ide              | 2         | 0.22%   |
| Firewire controller      | 2         | 0.22%   |
| Video                    | 1         | 0.11%   |
| Tv card                  | 1         | 0.11%   |
| Dvb card                 | 1         | 0.11%   |

