Linux in Germany - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Germany.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Germany/Desktop/README.md) and [notebooks](/Location/Germany/Notebook/README.md).

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

Total: 22381

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [d7c94f5e83](https://linux-hardware.org/?probe=d7c94f5e83) | May 07, 2022 |
| MSI           | GP60 2QE                    | Notebook    | [50a45201e9](https://linux-hardware.org/?probe=50a45201e9) | May 07, 2022 |
| PC Special... | Recoil II                   | Notebook    | [4eeb154eea](https://linux-hardware.org/?probe=4eeb154eea) | May 07, 2022 |
| Medion        | B460H6-EM                   | Desktop     | [e2abcd94ce](https://linux-hardware.org/?probe=e2abcd94ce) | May 06, 2022 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [86bb047b79](https://linux-hardware.org/?probe=86bb047b79) | May 06, 2022 |
| Fujitsu       | CELSIUS H720                | Notebook    | [7c41d6fd4d](https://linux-hardware.org/?probe=7c41d6fd4d) | May 06, 2022 |
| Lenovo        | 0B98401 WIN                 | Desktop     | [b080a2bae5](https://linux-hardware.org/?probe=b080a2bae5) | May 06, 2022 |
| MSI           | X370 KRAIT GAMING           | Desktop     | [83101fe031](https://linux-hardware.org/?probe=83101fe031) | May 06, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [f3e4a840e8](https://linux-hardware.org/?probe=f3e4a840e8) | May 06, 2022 |
| Medion        | E7222                       | Notebook    | [658905b8e4](https://linux-hardware.org/?probe=658905b8e4) | May 06, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [033456f893](https://linux-hardware.org/?probe=033456f893) | May 06, 2022 |
| Lenovo        | ThinkPad E15 20RD0011GE     | Notebook    | [795365ba55](https://linux-hardware.org/?probe=795365ba55) | May 06, 2022 |
| MSI           | Z370-A PRO                  | Desktop     | [b8cd5b5109](https://linux-hardware.org/?probe=b8cd5b5109) | May 06, 2022 |
| Lenovo        | ThinkPad L470 20J4003WGE    | Notebook    | [79bb6b88d3](https://linux-hardware.org/?probe=79bb6b88d3) | May 06, 2022 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | Notebook    | [ac270166aa](https://linux-hardware.org/?probe=ac270166aa) | May 06, 2022 |
| Lenovo        | ThinkPad X200 7459N40       | Notebook    | [f3a5a2e374](https://linux-hardware.org/?probe=f3a5a2e374) | May 06, 2022 |
| Lenovo        | ThinkPad X200 7459N40       | Notebook    | [74b1da3699](https://linux-hardware.org/?probe=74b1da3699) | May 06, 2022 |
| HP            | Laptop 15s-fq3xxx           | Notebook    | [a229549e45](https://linux-hardware.org/?probe=a229549e45) | May 06, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [246c63d834](https://linux-hardware.org/?probe=246c63d834) | May 06, 2022 |
| Avell High... | G1713/C55 Fox               | Notebook    | [3967b8c677](https://linux-hardware.org/?probe=3967b8c677) | May 06, 2022 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [622ff28b28](https://linux-hardware.org/?probe=622ff28b28) | May 05, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [35746e52a6](https://linux-hardware.org/?probe=35746e52a6) | May 05, 2022 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | Notebook    | [5f62eb4b30](https://linux-hardware.org/?probe=5f62eb4b30) | May 05, 2022 |
| Google        | Boten                       | Notebook    | [6204cff7de](https://linux-hardware.org/?probe=6204cff7de) | May 05, 2022 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [7b7f29e504](https://linux-hardware.org/?probe=7b7f29e504) | May 05, 2022 |
| HP            | Laptop 15s-fq3xxx           | Notebook    | [789a4c7367](https://linux-hardware.org/?probe=789a4c7367) | May 05, 2022 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [b2b025fb12](https://linux-hardware.org/?probe=b2b025fb12) | May 05, 2022 |
| Medion        | E7222                       | Notebook    | [1e12090b57](https://linux-hardware.org/?probe=1e12090b57) | May 05, 2022 |
| ASUSTek       | X550CC                      | Notebook    | [8306d5b694](https://linux-hardware.org/?probe=8306d5b694) | May 05, 2022 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [fa323515aa](https://linux-hardware.org/?probe=fa323515aa) | May 05, 2022 |
| Medion        | B460H6-EM                   | Desktop     | [19650634fb](https://linux-hardware.org/?probe=19650634fb) | May 05, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [e4f2477273](https://linux-hardware.org/?probe=e4f2477273) | May 05, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [f26171e0fb](https://linux-hardware.org/?probe=f26171e0fb) | May 05, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [b0a2114a0f](https://linux-hardware.org/?probe=b0a2114a0f) | May 05, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [e133868179](https://linux-hardware.org/?probe=e133868179) | May 05, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [f255a41930](https://linux-hardware.org/?probe=f255a41930) | May 05, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [d7223d4b03](https://linux-hardware.org/?probe=d7223d4b03) | May 05, 2022 |
| MSI           | 770-C45                     | Desktop     | [0e9179888b](https://linux-hardware.org/?probe=0e9179888b) | May 05, 2022 |
| HP            | Laptop 15s-fq3xxx           | Notebook    | [926a1bd0ad](https://linux-hardware.org/?probe=926a1bd0ad) | May 05, 2022 |
| Dell          | Latitude E5440              | Notebook    | [a505dc0b3c](https://linux-hardware.org/?probe=a505dc0b3c) | May 05, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [93d6fb1610](https://linux-hardware.org/?probe=93d6fb1610) | May 05, 2022 |
| Medion        | E13203                      | Notebook    | [2a8cf1f516](https://linux-hardware.org/?probe=2a8cf1f516) | May 04, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [9498437701](https://linux-hardware.org/?probe=9498437701) | May 04, 2022 |
| ASRock        | A320M Pro4                  | Desktop     | [b51c7ae18b](https://linux-hardware.org/?probe=b51c7ae18b) | May 04, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [699a7ea54b](https://linux-hardware.org/?probe=699a7ea54b) | May 04, 2022 |
| MSI           | H55M-E23                    | Desktop     | [d42084b294](https://linux-hardware.org/?probe=d42084b294) | May 04, 2022 |
| ASUSTek       | K93SM                       | Notebook    | [e59c89868b](https://linux-hardware.org/?probe=e59c89868b) | May 04, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [90635adac4](https://linux-hardware.org/?probe=90635adac4) | May 04, 2022 |
| Acer          | Veriton M490G               | Desktop     | [f55983d536](https://linux-hardware.org/?probe=f55983d536) | May 04, 2022 |
| Fujitsu       | D3128-A1 S26361-D3128-A1    | Desktop     | [31eaff1b28](https://linux-hardware.org/?probe=31eaff1b28) | May 04, 2022 |
| Gigabyte      | G33M-DS2R                   | Desktop     | [d4dff7f002](https://linux-hardware.org/?probe=d4dff7f002) | May 04, 2022 |
| Lenovo        | 0B98401 WIN                 | Desktop     | [180a5d086f](https://linux-hardware.org/?probe=180a5d086f) | May 04, 2022 |
| Lenovo        | 0B98401 WIN                 | Desktop     | [f47683cd76](https://linux-hardware.org/?probe=f47683cd76) | May 04, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [c08ef3e666](https://linux-hardware.org/?probe=c08ef3e666) | May 04, 2022 |
| MSI           | MS-7100                     | Desktop     | [3f753d8582](https://linux-hardware.org/?probe=3f753d8582) | May 04, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [e5a11e0fdd](https://linux-hardware.org/?probe=e5a11e0fdd) | May 04, 2022 |
| MSI           | Z77A-GD65                   | Desktop     | [35fda687da](https://linux-hardware.org/?probe=35fda687da) | May 04, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [34dcc7bc0c](https://linux-hardware.org/?probe=34dcc7bc0c) | May 04, 2022 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [aea37c880d](https://linux-hardware.org/?probe=aea37c880d) | May 04, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [246546447c](https://linux-hardware.org/?probe=246546447c) | May 04, 2022 |
| MSI           | Z77A-GD65                   | Desktop     | [b6ddc1be0e](https://linux-hardware.org/?probe=b6ddc1be0e) | May 04, 2022 |
| HP            | Laptop 15s-fq3xxx           | Notebook    | [eda68b255e](https://linux-hardware.org/?probe=eda68b255e) | May 04, 2022 |
| Lenovo        | ThinkCentre M81 5049W16     | Desktop     | [4725dabbde](https://linux-hardware.org/?probe=4725dabbde) | May 04, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [ccb21427bf](https://linux-hardware.org/?probe=ccb21427bf) | May 04, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [bd1a249d54](https://linux-hardware.org/?probe=bd1a249d54) | May 04, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [9a2b895663](https://linux-hardware.org/?probe=9a2b895663) | May 04, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [362ea22fd2](https://linux-hardware.org/?probe=362ea22fd2) | May 04, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [0a2ba1d529](https://linux-hardware.org/?probe=0a2ba1d529) | May 04, 2022 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [7196bf2ec6](https://linux-hardware.org/?probe=7196bf2ec6) | May 03, 2022 |
| Lenovo        | ThinkPad T400 6474WPU       | Notebook    | [ce7e91802e](https://linux-hardware.org/?probe=ce7e91802e) | May 03, 2022 |
| MSI           | PRO H610M-G DDR4            | Desktop     | [04b90d62d9](https://linux-hardware.org/?probe=04b90d62d9) | May 03, 2022 |
| HP            | ProBook x360 435 G7         | Convertible | [8e8d49463e](https://linux-hardware.org/?probe=8e8d49463e) | May 03, 2022 |
| HP            | ProBook x360 435 G7         | Convertible | [8e512a77d7](https://linux-hardware.org/?probe=8e512a77d7) | May 03, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [aed319bae8](https://linux-hardware.org/?probe=aed319bae8) | May 03, 2022 |
| Lenovo        | ThinkPad X131e 336838U      | Notebook    | [543ee221b3](https://linux-hardware.org/?probe=543ee221b3) | May 03, 2022 |
| ASUSTek       | X550CC                      | Notebook    | [e4918450ce](https://linux-hardware.org/?probe=e4918450ce) | May 03, 2022 |
| HP            | 255 G6 Notebook PC          | Notebook    | [af004a928f](https://linux-hardware.org/?probe=af004a928f) | May 03, 2022 |
| Lenovo        | ThinkPad R500 27326FG       | Notebook    | [1ed6992177](https://linux-hardware.org/?probe=1ed6992177) | May 03, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [fd61db399b](https://linux-hardware.org/?probe=fd61db399b) | May 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [0a01ebfdb1](https://linux-hardware.org/?probe=0a01ebfdb1) | May 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [93f01096ca](https://linux-hardware.org/?probe=93f01096ca) | May 03, 2022 |
| Shuttle       | FG41 V20                    | Desktop     | [fd07bdf7b5](https://linux-hardware.org/?probe=fd07bdf7b5) | May 02, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [dadde1bbc0](https://linux-hardware.org/?probe=dadde1bbc0) | May 02, 2022 |
| Fujitsu       | LIFEBOOK A3510              | Notebook    | [d5908498e1](https://linux-hardware.org/?probe=d5908498e1) | May 02, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [046b01cae8](https://linux-hardware.org/?probe=046b01cae8) | May 02, 2022 |
| ASUSTek       | ZenBook UX325SA_UM325SA     | Notebook    | [4e21e1d28e](https://linux-hardware.org/?probe=4e21e1d28e) | May 02, 2022 |
| ASUSTek       | A6G                         | Notebook    | [a873db0112](https://linux-hardware.org/?probe=a873db0112) | May 02, 2022 |
| ASRock        | P55 Pro                     | Desktop     | [e626676348](https://linux-hardware.org/?probe=e626676348) | May 02, 2022 |
| HP            | ZBook Firefly 15 G7 Mobi... | Notebook    | [90d0e8adb2](https://linux-hardware.org/?probe=90d0e8adb2) | May 02, 2022 |
| ASUSTek       | ZenBook UX363JA_UX363JA     | Convertible | [1e03b90e28](https://linux-hardware.org/?probe=1e03b90e28) | May 02, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [dfac863695](https://linux-hardware.org/?probe=dfac863695) | May 02, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [7636de5c44](https://linux-hardware.org/?probe=7636de5c44) | May 02, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [fbd1c44f53](https://linux-hardware.org/?probe=fbd1c44f53) | May 02, 2022 |
| Foxconn       | 2A8C                        | Desktop     | [26e7765e3a](https://linux-hardware.org/?probe=26e7765e3a) | May 02, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [0c5f20e02c](https://linux-hardware.org/?probe=0c5f20e02c) | May 02, 2022 |
| MSI           | PRO H610M-G DDR4            | Desktop     | [152b42c7c6](https://linux-hardware.org/?probe=152b42c7c6) | May 02, 2022 |
| Acer          | FMP55                       | Desktop     | [264c50cbed](https://linux-hardware.org/?probe=264c50cbed) | May 02, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [332445f774](https://linux-hardware.org/?probe=332445f774) | May 02, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [0e40616573](https://linux-hardware.org/?probe=0e40616573) | May 02, 2022 |
| Medion        | E2292                       | Convertible | [6823c98493](https://linux-hardware.org/?probe=6823c98493) | May 01, 2022 |
| Lenovo        | ThinkPad T400 6474AL9       | Notebook    | [b303038c87](https://linux-hardware.org/?probe=b303038c87) | May 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [6c71a85fcc](https://linux-hardware.org/?probe=6c71a85fcc) | May 01, 2022 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [0b847ba92b](https://linux-hardware.org/?probe=0b847ba92b) | May 01, 2022 |
| Acer          | Aspire 7750G                | Notebook    | [abd7ed0c5c](https://linux-hardware.org/?probe=abd7ed0c5c) | May 01, 2022 |
| Acer          | Aspire A515-56              | Notebook    | [b728fa5844](https://linux-hardware.org/?probe=b728fa5844) | May 01, 2022 |
| ASRock        | G31M-VS2                    | Desktop     | [501dd7e38b](https://linux-hardware.org/?probe=501dd7e38b) | May 01, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [c37aaf2585](https://linux-hardware.org/?probe=c37aaf2585) | May 01, 2022 |
| Gigabyte      | X570S AERO G                | Desktop     | [ab6b8eaa71](https://linux-hardware.org/?probe=ab6b8eaa71) | May 01, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [e00cc77c41](https://linux-hardware.org/?probe=e00cc77c41) | May 01, 2022 |
| Fujitsu Si... | AMILO Xi 3650               | Notebook    | [f28a16f8de](https://linux-hardware.org/?probe=f28a16f8de) | May 01, 2022 |
| Schenker      | XMG CORE (TGL/M21)          | Notebook    | [7251434bdb](https://linux-hardware.org/?probe=7251434bdb) | May 01, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [5e020f2247](https://linux-hardware.org/?probe=5e020f2247) | May 01, 2022 |
| Acer          | TravelMate P253             | Notebook    | [89812a5d4a](https://linux-hardware.org/?probe=89812a5d4a) | May 01, 2022 |
| Biostar       | A960D+V2                    | Desktop     | [136145a59c](https://linux-hardware.org/?probe=136145a59c) | May 01, 2022 |
| Dell          | Vostro 1720                 | Notebook    | [fd52613ee2](https://linux-hardware.org/?probe=fd52613ee2) | May 01, 2022 |
| Intel         | DB85FL AAG89861-203         | Desktop     | [7d75948e9a](https://linux-hardware.org/?probe=7d75948e9a) | May 01, 2022 |
| HP            | 8459                        | Desktop     | [21d5d92fda](https://linux-hardware.org/?probe=21d5d92fda) | May 01, 2022 |
| Foxconn       | 2A8C                        | Desktop     | [205d18a183](https://linux-hardware.org/?probe=205d18a183) | May 01, 2022 |
| Intel         | DB85FL AAG89861-203         | Desktop     | [1d3dfb69e7](https://linux-hardware.org/?probe=1d3dfb69e7) | May 01, 2022 |
| HP            | ProBook x360 11 G3 EE       | Convertible | [e260e2021b](https://linux-hardware.org/?probe=e260e2021b) | May 01, 2022 |
| MSI           | MS-7267                     | Desktop     | [12ef52bd6d](https://linux-hardware.org/?probe=12ef52bd6d) | May 01, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [3761721b90](https://linux-hardware.org/?probe=3761721b90) | May 01, 2022 |
| Razer         | Blade Stealth 13 Late 20... | Notebook    | [ba8fa66c1c](https://linux-hardware.org/?probe=ba8fa66c1c) | May 01, 2022 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [b8194d3077](https://linux-hardware.org/?probe=b8194d3077) | May 01, 2022 |
| Dell          | 0M017G A01                  | Desktop     | [653212f53c](https://linux-hardware.org/?probe=653212f53c) | May 01, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [88fcea9210](https://linux-hardware.org/?probe=88fcea9210) | Apr 30, 2022 |
| Fujitsu Si... | AMILO A1650G                | Notebook    | [fbf6d9db93](https://linux-hardware.org/?probe=fbf6d9db93) | Apr 30, 2022 |
| Fujitsu Si... | AMILO A1650G                | Notebook    | [134f0a947b](https://linux-hardware.org/?probe=134f0a947b) | Apr 30, 2022 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [18daf9705b](https://linux-hardware.org/?probe=18daf9705b) | Apr 30, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [87542ba2c2](https://linux-hardware.org/?probe=87542ba2c2) | Apr 30, 2022 |
| Medion        | MS-7616                     | Desktop     | [f3572ea9a5](https://linux-hardware.org/?probe=f3572ea9a5) | Apr 30, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [dc1c0d091e](https://linux-hardware.org/?probe=dc1c0d091e) | Apr 30, 2022 |
| Dell          | Vostro 1720                 | Notebook    | [bc8f50b9fb](https://linux-hardware.org/?probe=bc8f50b9fb) | Apr 30, 2022 |
| Dell          | Vostro 1720                 | Notebook    | [56cc7a9a54](https://linux-hardware.org/?probe=56cc7a9a54) | Apr 30, 2022 |
| MSI           | PRO H610M-G DDR4            | Desktop     | [f7806fa6f0](https://linux-hardware.org/?probe=f7806fa6f0) | Apr 30, 2022 |
| HP            | 0AECh D                     | Desktop     | [89441b750f](https://linux-hardware.org/?probe=89441b750f) | Apr 30, 2022 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [058184d73c](https://linux-hardware.org/?probe=058184d73c) | Apr 30, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [b6cbc6e523](https://linux-hardware.org/?probe=b6cbc6e523) | Apr 30, 2022 |
| Lenovo        | ThinkPad T540p 20BFS26E0... | Notebook    | [06738e7bb8](https://linux-hardware.org/?probe=06738e7bb8) | Apr 30, 2022 |
| Acer          | Aspire E5-774G              | Notebook    | [32426089be](https://linux-hardware.org/?probe=32426089be) | Apr 30, 2022 |
| Acer          | Aspire E5-774G              | Notebook    | [0fce8f01ae](https://linux-hardware.org/?probe=0fce8f01ae) | Apr 30, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [6db8017245](https://linux-hardware.org/?probe=6db8017245) | Apr 30, 2022 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [10eb959775](https://linux-hardware.org/?probe=10eb959775) | Apr 30, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [18eb9a1e52](https://linux-hardware.org/?probe=18eb9a1e52) | Apr 30, 2022 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [0158bc69ec](https://linux-hardware.org/?probe=0158bc69ec) | Apr 30, 2022 |
| Lenovo        | 36C5 SDK0J40700 WIN 3258... | Desktop     | [d9ac32b17d](https://linux-hardware.org/?probe=d9ac32b17d) | Apr 30, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [b81ecfb2a3](https://linux-hardware.org/?probe=b81ecfb2a3) | Apr 30, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [13fd8e249d](https://linux-hardware.org/?probe=13fd8e249d) | Apr 30, 2022 |
| ASUSTek       | T100HAN                     | Notebook    | [5ee200cfbe](https://linux-hardware.org/?probe=5ee200cfbe) | Apr 30, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a1199bffe2](https://linux-hardware.org/?probe=a1199bffe2) | Apr 30, 2022 |
| HP            | 255 G6 Notebook PC          | Notebook    | [f639c7c8f5](https://linux-hardware.org/?probe=f639c7c8f5) | Apr 29, 2022 |
| Dell          | Inspiron N5050              | Notebook    | [7d3cb853e6](https://linux-hardware.org/?probe=7d3cb853e6) | Apr 29, 2022 |
| MSI           | A320M PRO-E                 | Desktop     | [655905bb3b](https://linux-hardware.org/?probe=655905bb3b) | Apr 29, 2022 |
| ASRock        | ALiveNF6G-GLAN              | Desktop     | [7dfb4ca9f5](https://linux-hardware.org/?probe=7dfb4ca9f5) | Apr 29, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [fe522bdf2e](https://linux-hardware.org/?probe=fe522bdf2e) | Apr 29, 2022 |
| Dell          | Precision 3551              | Notebook    | [b146dc2249](https://linux-hardware.org/?probe=b146dc2249) | Apr 29, 2022 |
| Dell          | Precision 3551              | Notebook    | [d5a3a490f4](https://linux-hardware.org/?probe=d5a3a490f4) | Apr 29, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [aadc641825](https://linux-hardware.org/?probe=aadc641825) | Apr 29, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [61bb949815](https://linux-hardware.org/?probe=61bb949815) | Apr 29, 2022 |
| ASUSTek       | Rampage IV EXTREME          | Desktop     | [111d072676](https://linux-hardware.org/?probe=111d072676) | Apr 29, 2022 |
| ASUSTek       | X411UN                      | Notebook    | [c864c65ec1](https://linux-hardware.org/?probe=c864c65ec1) | Apr 29, 2022 |
| HARDKERNEL    | ODROID-H2                   | Desktop     | [c3303164ff](https://linux-hardware.org/?probe=c3303164ff) | Apr 29, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [3a7104d6b4](https://linux-hardware.org/?probe=3a7104d6b4) | Apr 29, 2022 |
| Lenovo        | ThinkPad L560 20F1001YGE    | Notebook    | [c4021bd208](https://linux-hardware.org/?probe=c4021bd208) | Apr 29, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [6bb8f4af30](https://linux-hardware.org/?probe=6bb8f4af30) | Apr 29, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [94d74e9b78](https://linux-hardware.org/?probe=94d74e9b78) | Apr 29, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [e7ca44864b](https://linux-hardware.org/?probe=e7ca44864b) | Apr 29, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [e45e120b35](https://linux-hardware.org/?probe=e45e120b35) | Apr 29, 2022 |
| HP            | EliteBook x360 1040 G8 N... | Convertible | [8c70bea200](https://linux-hardware.org/?probe=8c70bea200) | Apr 29, 2022 |
| Fujitsu Si... | AMILO Xi 3650               | Notebook    | [61da560f18](https://linux-hardware.org/?probe=61da560f18) | Apr 29, 2022 |
| HP            | EliteBook x360 1040 G8 N... | Convertible | [aa5c3c28bf](https://linux-hardware.org/?probe=aa5c3c28bf) | Apr 29, 2022 |
| Dell          | 0T568R A00                  | Desktop     | [290f6d6b48](https://linux-hardware.org/?probe=290f6d6b48) | Apr 29, 2022 |
| Medion        | E3215 MD60929               | Convertible | [a84ba0d682](https://linux-hardware.org/?probe=a84ba0d682) | Apr 28, 2022 |
| Fujitsu       | LIFEBOOK S762               | Notebook    | [e168087bf0](https://linux-hardware.org/?probe=e168087bf0) | Apr 28, 2022 |
| Fujitsu       | LIFEBOOK S762               | Notebook    | [c258235d05](https://linux-hardware.org/?probe=c258235d05) | Apr 28, 2022 |
| LG Electro... | 16T90P-G.AA78G              | Convertible | [42a891a892](https://linux-hardware.org/?probe=42a891a892) | Apr 28, 2022 |
| Lenovo        | ThinkPad T420 4180PC4       | Notebook    | [6c69039594](https://linux-hardware.org/?probe=6c69039594) | Apr 28, 2022 |
| Lenovo        | ThinkCentre A57 98517HG     | Desktop     | [e8cab6c0fb](https://linux-hardware.org/?probe=e8cab6c0fb) | Apr 28, 2022 |
| Lenovo        | ThinkCentre A57 98517HG     | Desktop     | [f6bfd948e9](https://linux-hardware.org/?probe=f6bfd948e9) | Apr 28, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [21b89b5942](https://linux-hardware.org/?probe=21b89b5942) | Apr 28, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [efd0934b49](https://linux-hardware.org/?probe=efd0934b49) | Apr 28, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [cc6cd50096](https://linux-hardware.org/?probe=cc6cd50096) | Apr 28, 2022 |
| Lenovo        | ThinkPad T440s 20ARS3640... | Notebook    | [13ec979f89](https://linux-hardware.org/?probe=13ec979f89) | Apr 28, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [13f68cfe10](https://linux-hardware.org/?probe=13f68cfe10) | Apr 28, 2022 |
| Intel         | NUC10i7FNB K61360-305       | Mini pc     | [8ef2e84f50](https://linux-hardware.org/?probe=8ef2e84f50) | Apr 28, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [8d8cef9b7d](https://linux-hardware.org/?probe=8d8cef9b7d) | Apr 28, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [6f320b7fcb](https://linux-hardware.org/?probe=6f320b7fcb) | Apr 28, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [2514409f18](https://linux-hardware.org/?probe=2514409f18) | Apr 28, 2022 |
| Packard Be... | DOT S                       | Notebook    | [d0231bab8b](https://linux-hardware.org/?probe=d0231bab8b) | Apr 28, 2022 |
| Samsung       | RC530/RC730                 | Notebook    | [2e44e9228e](https://linux-hardware.org/?probe=2e44e9228e) | Apr 28, 2022 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [c4f91167bb](https://linux-hardware.org/?probe=c4f91167bb) | Apr 27, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [19e0445e6f](https://linux-hardware.org/?probe=19e0445e6f) | Apr 27, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [2ae652bf21](https://linux-hardware.org/?probe=2ae652bf21) | Apr 27, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [e3001e38a3](https://linux-hardware.org/?probe=e3001e38a3) | Apr 27, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [a4d49bf6d9](https://linux-hardware.org/?probe=a4d49bf6d9) | Apr 27, 2022 |
| Matsushita... | CF-30CTQAZBG                | Notebook    | [7935a074aa](https://linux-hardware.org/?probe=7935a074aa) | Apr 27, 2022 |
| Intel         | NUC11ATBPE M49844-202       | Mini pc     | [d5f3295927](https://linux-hardware.org/?probe=d5f3295927) | Apr 27, 2022 |
| ASUSTek       | H87-PRO                     | Desktop     | [476e417317](https://linux-hardware.org/?probe=476e417317) | Apr 27, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [c07e06f794](https://linux-hardware.org/?probe=c07e06f794) | Apr 27, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [e51ff27a5a](https://linux-hardware.org/?probe=e51ff27a5a) | Apr 27, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [127862c3f7](https://linux-hardware.org/?probe=127862c3f7) | Apr 27, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [b15f34dd41](https://linux-hardware.org/?probe=b15f34dd41) | Apr 27, 2022 |
| ASUSTek       | Zephyrus S GX531GXR_GX53... | Notebook    | [882dbf87c5](https://linux-hardware.org/?probe=882dbf87c5) | Apr 27, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f369da2680](https://linux-hardware.org/?probe=f369da2680) | Apr 27, 2022 |
| HP            | EliteBook x360 1040 G8 N... | Convertible | [fde127175d](https://linux-hardware.org/?probe=fde127175d) | Apr 27, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [e2461ef9a7](https://linux-hardware.org/?probe=e2461ef9a7) | Apr 27, 2022 |
| ASRockRack    | B565D4-V1L                  | Desktop     | [bf0b5a06c9](https://linux-hardware.org/?probe=bf0b5a06c9) | Apr 27, 2022 |
| Medion        | B460H6-EM                   | Desktop     | [82b4baa4ed](https://linux-hardware.org/?probe=82b4baa4ed) | Apr 27, 2022 |
| Medion        | B360H4-EM V1.0              | Desktop     | [9ed05797b0](https://linux-hardware.org/?probe=9ed05797b0) | Apr 27, 2022 |
| Medion        | B360H4-EM V1.0              | Desktop     | [7a35687e1d](https://linux-hardware.org/?probe=7a35687e1d) | Apr 27, 2022 |
| Acer          | Aspire E5-774G              | Notebook    | [be0fb85534](https://linux-hardware.org/?probe=be0fb85534) | Apr 27, 2022 |
| Alienware     | M18xR2                      | Notebook    | [3853b17e46](https://linux-hardware.org/?probe=3853b17e46) | Apr 27, 2022 |
| ASUSTek       | Zephyrus S GX531GXR_GX53... | Notebook    | [b540bb9d6f](https://linux-hardware.org/?probe=b540bb9d6f) | Apr 27, 2022 |
| Intel         | NUC11ATBPE M49844-202       | Mini pc     | [60b915c436](https://linux-hardware.org/?probe=60b915c436) | Apr 27, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [87cc990d93](https://linux-hardware.org/?probe=87cc990d93) | Apr 27, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [bd185a521b](https://linux-hardware.org/?probe=bd185a521b) | Apr 27, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [5721b7c107](https://linux-hardware.org/?probe=5721b7c107) | Apr 27, 2022 |
| MSI           | Z370 SLI PLUS               | Desktop     | [75dbc4ddab](https://linux-hardware.org/?probe=75dbc4ddab) | Apr 27, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [3c6aace75c](https://linux-hardware.org/?probe=3c6aace75c) | Apr 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [14f1d071ae](https://linux-hardware.org/?probe=14f1d071ae) | Apr 26, 2022 |
| Samsung       | 755XDA                      | Notebook    | [eea7e3a0d3](https://linux-hardware.org/?probe=eea7e3a0d3) | Apr 26, 2022 |
| Acer          | Swift SF316-51              | Notebook    | [fe42983639](https://linux-hardware.org/?probe=fe42983639) | Apr 26, 2022 |
| HP            | ProBook x360 11 G3 EE       | Convertible | [b55ed2fbd6](https://linux-hardware.org/?probe=b55ed2fbd6) | Apr 26, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [50c760fc94](https://linux-hardware.org/?probe=50c760fc94) | Apr 26, 2022 |
| Toshiba       | TECRA R940                  | Notebook    | [d841324245](https://linux-hardware.org/?probe=d841324245) | Apr 26, 2022 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [454d879501](https://linux-hardware.org/?probe=454d879501) | Apr 26, 2022 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [9468064cf9](https://linux-hardware.org/?probe=9468064cf9) | Apr 26, 2022 |
| Gigabyte      | H67MA-USB3-B3               | Desktop     | [f2fb45ef53](https://linux-hardware.org/?probe=f2fb45ef53) | Apr 26, 2022 |
| Gigabyte      | H67MA-USB3-B3               | Desktop     | [d1e23f1023](https://linux-hardware.org/?probe=d1e23f1023) | Apr 26, 2022 |
| ASUSTek       | Zephyrus S GX531GXR_GX53... | Notebook    | [9dee9219fd](https://linux-hardware.org/?probe=9dee9219fd) | Apr 26, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [727b677ecb](https://linux-hardware.org/?probe=727b677ecb) | Apr 26, 2022 |
| ASUSTek       | P55VA                       | Notebook    | [21c5b79768](https://linux-hardware.org/?probe=21c5b79768) | Apr 26, 2022 |
| Fujitsu Si... | AMILO Xi 3650               | Notebook    | [5661c025c7](https://linux-hardware.org/?probe=5661c025c7) | Apr 26, 2022 |
| Chuwi         | UBOOK                       | Convertible | [5899252c4d](https://linux-hardware.org/?probe=5899252c4d) | Apr 26, 2022 |
| Dell          | Latitude 7480               | Notebook    | [817415642f](https://linux-hardware.org/?probe=817415642f) | Apr 26, 2022 |
| Acer          | Aspire E1-570               | Notebook    | [b8257c292a](https://linux-hardware.org/?probe=b8257c292a) | Apr 26, 2022 |
| ASUSTek       | Zephyrus S GX531GXR_GX53... | Notebook    | [54b755397c](https://linux-hardware.org/?probe=54b755397c) | Apr 26, 2022 |
| Notebook      | W35xSTQ_370ST               | Notebook    | [ef4f066fba](https://linux-hardware.org/?probe=ef4f066fba) | Apr 26, 2022 |
| Fujitsu Si... | AMILO Xi 3650               | Notebook    | [c33c4a0ca2](https://linux-hardware.org/?probe=c33c4a0ca2) | Apr 26, 2022 |
| Fujitsu       | LIFEBOOK A531               | Notebook    | [4d2a2873fb](https://linux-hardware.org/?probe=4d2a2873fb) | Apr 26, 2022 |
| Intel         | Crestline & ICH8M Chipse... | Notebook    | [b410b890ef](https://linux-hardware.org/?probe=b410b890ef) | Apr 26, 2022 |
| Intel         | Crestline & ICH8M Chipse... | Notebook    | [4435386574](https://linux-hardware.org/?probe=4435386574) | Apr 26, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [bd827295e5](https://linux-hardware.org/?probe=bd827295e5) | Apr 26, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [8bd50984ef](https://linux-hardware.org/?probe=8bd50984ef) | Apr 25, 2022 |
| Lenovo        | ThinkPad T440 20B7S3UD00    | Notebook    | [9c66fd444a](https://linux-hardware.org/?probe=9c66fd444a) | Apr 25, 2022 |
| Lenovo        | ThinkPad T440 20B7S3UD00    | Notebook    | [942267c99b](https://linux-hardware.org/?probe=942267c99b) | Apr 25, 2022 |
| Medion        | S17402 MD63000              | Notebook    | [fe73d0023a](https://linux-hardware.org/?probe=fe73d0023a) | Apr 25, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [08d2d58a95](https://linux-hardware.org/?probe=08d2d58a95) | Apr 25, 2022 |
| Unknown       | Unknown                     | Desktop     | [f67ff826d9](https://linux-hardware.org/?probe=f67ff826d9) | Apr 25, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [ff35a6956d](https://linux-hardware.org/?probe=ff35a6956d) | Apr 25, 2022 |
| Acer          | Aspire A717-71G             | Notebook    | [55baa49b73](https://linux-hardware.org/?probe=55baa49b73) | Apr 25, 2022 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [9574f78f95](https://linux-hardware.org/?probe=9574f78f95) | Apr 25, 2022 |
| Lenovo        | ThinkPad T400 2767B77       | Notebook    | [54b2615503](https://linux-hardware.org/?probe=54b2615503) | Apr 25, 2022 |
| ASUSTek       | P5GC-MX/MEDION/SI           | Desktop     | [8801f8d20c](https://linux-hardware.org/?probe=8801f8d20c) | Apr 25, 2022 |
| ASUSTek       | A55BM-E                     | Desktop     | [b2b220b65d](https://linux-hardware.org/?probe=b2b220b65d) | Apr 25, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [9e7c80a9d0](https://linux-hardware.org/?probe=9e7c80a9d0) | Apr 25, 2022 |
| ASUSTek       | ROG Strix G733ZX_G733ZX     | Notebook    | [032acaf88c](https://linux-hardware.org/?probe=032acaf88c) | Apr 25, 2022 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [2d1a1334c6](https://linux-hardware.org/?probe=2d1a1334c6) | Apr 25, 2022 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [c76074f5e0](https://linux-hardware.org/?probe=c76074f5e0) | Apr 25, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [b24ac490a1](https://linux-hardware.org/?probe=b24ac490a1) | Apr 25, 2022 |
| HP            | ProBook 455R G6             | Notebook    | [3118a03e9b](https://linux-hardware.org/?probe=3118a03e9b) | Apr 25, 2022 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [e1731ce27f](https://linux-hardware.org/?probe=e1731ce27f) | Apr 25, 2022 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [a681022e30](https://linux-hardware.org/?probe=a681022e30) | Apr 25, 2022 |
| Acer          | Aspire VN7-792G             | Notebook    | [77f5ce42de](https://linux-hardware.org/?probe=77f5ce42de) | Apr 24, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [2fcb2f9b19](https://linux-hardware.org/?probe=2fcb2f9b19) | Apr 24, 2022 |
| ASRock        | Z270 Extreme4               | Desktop     | [b060c039ca](https://linux-hardware.org/?probe=b060c039ca) | Apr 24, 2022 |
| AMI           | Intel                       | Notebook    | [87e32073a4](https://linux-hardware.org/?probe=87e32073a4) | Apr 24, 2022 |
| Notebook      | NLx0MU                      | Notebook    | [5d65012d75](https://linux-hardware.org/?probe=5d65012d75) | Apr 24, 2022 |
| ASUSTek       | 1215N                       | Notebook    | [b921f6fbae](https://linux-hardware.org/?probe=b921f6fbae) | Apr 24, 2022 |
| HP            | 255 G3                      | Notebook    | [7f8bc209d0](https://linux-hardware.org/?probe=7f8bc209d0) | Apr 24, 2022 |
| Toshiba       | PORTEGE M800                | Notebook    | [20f2ac516c](https://linux-hardware.org/?probe=20f2ac516c) | Apr 24, 2022 |
| Acer          | Aspire E1-570               | Notebook    | [3ed79cff5c](https://linux-hardware.org/?probe=3ed79cff5c) | Apr 24, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | Notebook    | [b1895460f6](https://linux-hardware.org/?probe=b1895460f6) | Apr 24, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [c16cb4e0d6](https://linux-hardware.org/?probe=c16cb4e0d6) | Apr 24, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | Notebook    | [11e7429c51](https://linux-hardware.org/?probe=11e7429c51) | Apr 24, 2022 |
| Acer          | FX58M                       | Desktop     | [af1d52769d](https://linux-hardware.org/?probe=af1d52769d) | Apr 24, 2022 |
| Dell          | Latitude E6530              | Notebook    | [87a016871d](https://linux-hardware.org/?probe=87a016871d) | Apr 24, 2022 |
| Acer          | TravelMate Spin P614RN-5... | Convertible | [5850b85224](https://linux-hardware.org/?probe=5850b85224) | Apr 24, 2022 |
| Acer          | FX58M                       | Desktop     | [3074ddb372](https://linux-hardware.org/?probe=3074ddb372) | Apr 24, 2022 |
| Dell          | XPS 12-9Q33                 | Notebook    | [5cbe457f54](https://linux-hardware.org/?probe=5cbe457f54) | Apr 24, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [b36aa38e8a](https://linux-hardware.org/?probe=b36aa38e8a) | Apr 24, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [f7e2496340](https://linux-hardware.org/?probe=f7e2496340) | Apr 24, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [4d564b4038](https://linux-hardware.org/?probe=4d564b4038) | Apr 24, 2022 |
| Lenovo        | ThinkPad T520 4243WRK       | Notebook    | [3600152c79](https://linux-hardware.org/?probe=3600152c79) | Apr 24, 2022 |
| Lenovo        | ThinkPad T520 4243WRK       | Notebook    | [cf390615ba](https://linux-hardware.org/?probe=cf390615ba) | Apr 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [4c43342014](https://linux-hardware.org/?probe=4c43342014) | Apr 24, 2022 |
| HP            | Laptop 17-bs0xx             | Notebook    | [8a4835680a](https://linux-hardware.org/?probe=8a4835680a) | Apr 24, 2022 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [3aeeaee161](https://linux-hardware.org/?probe=3aeeaee161) | Apr 23, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [037b7180fd](https://linux-hardware.org/?probe=037b7180fd) | Apr 23, 2022 |
| ASUSTek       | X705UQR                     | Notebook    | [e4a27bf740](https://linux-hardware.org/?probe=e4a27bf740) | Apr 23, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [b6a4a77ba4](https://linux-hardware.org/?probe=b6a4a77ba4) | Apr 23, 2022 |
| HP            | 21EF                        | Desktop     | [9e37979ea3](https://linux-hardware.org/?probe=9e37979ea3) | Apr 23, 2022 |
| MSI           | E350IA-E45                  | Desktop     | [8271a7f1d5](https://linux-hardware.org/?probe=8271a7f1d5) | Apr 23, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d6d999cbc8](https://linux-hardware.org/?probe=d6d999cbc8) | Apr 23, 2022 |
| MSI           | E350IA-E45                  | Desktop     | [da7d376e11](https://linux-hardware.org/?probe=da7d376e11) | Apr 23, 2022 |
| Medion        | E7220                       | Notebook    | [c2d7457304](https://linux-hardware.org/?probe=c2d7457304) | Apr 23, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [e63c319457](https://linux-hardware.org/?probe=e63c319457) | Apr 23, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [61ab02b4e8](https://linux-hardware.org/?probe=61ab02b4e8) | Apr 23, 2022 |
| ASUSTek       | M4A78-EM                    | Desktop     | [5ef7775195](https://linux-hardware.org/?probe=5ef7775195) | Apr 23, 2022 |
| MSI           | H510M PRO                   | Desktop     | [62b9c33cba](https://linux-hardware.org/?probe=62b9c33cba) | Apr 23, 2022 |
| HP            | 0AECh D                     | Desktop     | [5fd33a9a4e](https://linux-hardware.org/?probe=5fd33a9a4e) | Apr 23, 2022 |
| Medion        | E6436 MD61150               | Notebook    | [999d2d1526](https://linux-hardware.org/?probe=999d2d1526) | Apr 23, 2022 |
| Dell          | XPS 17 9700                 | Notebook    | [2d275ba888](https://linux-hardware.org/?probe=2d275ba888) | Apr 23, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [f9b84e295a](https://linux-hardware.org/?probe=f9b84e295a) | Apr 23, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [7ad6e17281](https://linux-hardware.org/?probe=7ad6e17281) | Apr 23, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [73c09c4d29](https://linux-hardware.org/?probe=73c09c4d29) | Apr 23, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [7538f27511](https://linux-hardware.org/?probe=7538f27511) | Apr 23, 2022 |
| Intel         | NUC6CAYB J23203-402         | Mini pc     | [86964dccfd](https://linux-hardware.org/?probe=86964dccfd) | Apr 23, 2022 |
| ASUSTek       | PRIME A320M-C R2.0          | Desktop     | [ba551e9420](https://linux-hardware.org/?probe=ba551e9420) | Apr 23, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [3ce5eb80eb](https://linux-hardware.org/?probe=3ce5eb80eb) | Apr 22, 2022 |
| Lenovo        | E31-70 80KX                 | Notebook    | [21f5bdfbc7](https://linux-hardware.org/?probe=21f5bdfbc7) | Apr 22, 2022 |
| Lenovo        | E31-70 80KX                 | Notebook    | [6910bac4f7](https://linux-hardware.org/?probe=6910bac4f7) | Apr 22, 2022 |
| AWOW          | AL34                        | Notebook    | [cc4a446b9e](https://linux-hardware.org/?probe=cc4a446b9e) | Apr 22, 2022 |
| Lenovo        | NO DPK                      | Desktop     | [709f4d5f8c](https://linux-hardware.org/?probe=709f4d5f8c) | Apr 22, 2022 |
| Gigabyte      | G33M-DS2R                   | Desktop     | [d2cd51f72d](https://linux-hardware.org/?probe=d2cd51f72d) | Apr 22, 2022 |
| HP            | ENVY x360 Convert 15        | Convertible | [f3071c3072](https://linux-hardware.org/?probe=f3071c3072) | Apr 22, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [8ee6cabf43](https://linux-hardware.org/?probe=8ee6cabf43) | Apr 22, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [91fc5d74c6](https://linux-hardware.org/?probe=91fc5d74c6) | Apr 22, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [2c7cee55b7](https://linux-hardware.org/?probe=2c7cee55b7) | Apr 22, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [b8a5ec8483](https://linux-hardware.org/?probe=b8a5ec8483) | Apr 22, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [618d8cab02](https://linux-hardware.org/?probe=618d8cab02) | Apr 22, 2022 |
| ASRock        | G31M-VS2                    | Desktop     | [962b281504](https://linux-hardware.org/?probe=962b281504) | Apr 22, 2022 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [4d911b0d94](https://linux-hardware.org/?probe=4d911b0d94) | Apr 22, 2022 |
| Medion        | H110H4-EM                   | Desktop     | [bdbf84afd8](https://linux-hardware.org/?probe=bdbf84afd8) | Apr 22, 2022 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [aa854e0ae2](https://linux-hardware.org/?probe=aa854e0ae2) | Apr 22, 2022 |
| Acer          | Aspire E1-570               | Notebook    | [9b96999445](https://linux-hardware.org/?probe=9b96999445) | Apr 22, 2022 |
| Acer          | Aspire E1-570               | Notebook    | [b8e8a058d2](https://linux-hardware.org/?probe=b8e8a058d2) | Apr 22, 2022 |
| Acer          | Aspire V3-771               | Notebook    | [f36e209172](https://linux-hardware.org/?probe=f36e209172) | Apr 22, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [26b3b0efb2](https://linux-hardware.org/?probe=26b3b0efb2) | Apr 22, 2022 |
| Medion        | Erazer X7843 MD99996        | Notebook    | [02dd167b63](https://linux-hardware.org/?probe=02dd167b63) | Apr 22, 2022 |
| Dell          | Latitude 7285               | Tablet      | [0ec990ab1e](https://linux-hardware.org/?probe=0ec990ab1e) | Apr 22, 2022 |
| Acer          | Aspire 8930                 | Notebook    | [aaf1f1994a](https://linux-hardware.org/?probe=aaf1f1994a) | Apr 22, 2022 |
| Lenovo        | ThinkPad X230 2325HR9       | Notebook    | [a9d9d3fbb2](https://linux-hardware.org/?probe=a9d9d3fbb2) | Apr 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [8564bded7f](https://linux-hardware.org/?probe=8564bded7f) | Apr 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [d761657c3a](https://linux-hardware.org/?probe=d761657c3a) | Apr 21, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [0f748e86d4](https://linux-hardware.org/?probe=0f748e86d4) | Apr 21, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [58a8282067](https://linux-hardware.org/?probe=58a8282067) | Apr 21, 2022 |
| Dell          | Latitude 7320 Detachable    | Tablet      | [6906fd42bc](https://linux-hardware.org/?probe=6906fd42bc) | Apr 21, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [caebf74610](https://linux-hardware.org/?probe=caebf74610) | Apr 21, 2022 |
| Timi          | TM1701                      | Notebook    | [dba97f1875](https://linux-hardware.org/?probe=dba97f1875) | Apr 21, 2022 |
| HP            | EliteBook Folio 9470m       | Notebook    | [13136bcf8d](https://linux-hardware.org/?probe=13136bcf8d) | Apr 21, 2022 |
| Apple         | MacBookAir4,2               | Notebook    | [1535fd1e85](https://linux-hardware.org/?probe=1535fd1e85) | Apr 21, 2022 |
| HP            | Pavilion g6                 | Notebook    | [63f6b73d50](https://linux-hardware.org/?probe=63f6b73d50) | Apr 21, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [0da1d9833d](https://linux-hardware.org/?probe=0da1d9833d) | Apr 21, 2022 |
| HP            | 304Ah                       | Desktop     | [08fbf0f311](https://linux-hardware.org/?probe=08fbf0f311) | Apr 21, 2022 |
| Acer          | TravelMate P653-M           | Notebook    | [208913a075](https://linux-hardware.org/?probe=208913a075) | Apr 21, 2022 |
| ASUSTek       | Z170-P                      | Desktop     | [aa004d1627](https://linux-hardware.org/?probe=aa004d1627) | Apr 21, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [1fc4d30b49](https://linux-hardware.org/?probe=1fc4d30b49) | Apr 21, 2022 |
| Gigabyte      | AB350M-HD3-CF               | Desktop     | [dd16ab4768](https://linux-hardware.org/?probe=dd16ab4768) | Apr 21, 2022 |
| HP            | Laptop 15s-fq3xxx           | Notebook    | [676db10abf](https://linux-hardware.org/?probe=676db10abf) | Apr 21, 2022 |
| Lenovo        | 3000 N200 0769EQG           | Notebook    | [d9bbff0c4d](https://linux-hardware.org/?probe=d9bbff0c4d) | Apr 21, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [3b23a0c003](https://linux-hardware.org/?probe=3b23a0c003) | Apr 20, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [0ebad8c6f7](https://linux-hardware.org/?probe=0ebad8c6f7) | Apr 20, 2022 |
| Dell          | Latitude XT3                | Notebook    | [6db9585e20](https://linux-hardware.org/?probe=6db9585e20) | Apr 20, 2022 |
| Lenovo        | ThinkPad T430s 2356H83      | Notebook    | [714396bc62](https://linux-hardware.org/?probe=714396bc62) | Apr 20, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [f2bfb22fea](https://linux-hardware.org/?probe=f2bfb22fea) | Apr 20, 2022 |
| Dell          | Inspiron N5040              | Notebook    | [9069ecddb3](https://linux-hardware.org/?probe=9069ecddb3) | Apr 20, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [0d5a9fcacc](https://linux-hardware.org/?probe=0d5a9fcacc) | Apr 20, 2022 |
| HP            | 625                         | Notebook    | [1d14c84fe9](https://linux-hardware.org/?probe=1d14c84fe9) | Apr 20, 2022 |
| ASUSTek       | H87-PRO                     | Desktop     | [aa1df63f27](https://linux-hardware.org/?probe=aa1df63f27) | Apr 20, 2022 |
| Lenovo        | ThinkPad T400 64754B9       | Notebook    | [443f31afef](https://linux-hardware.org/?probe=443f31afef) | Apr 20, 2022 |
| Lenovo        | ThinkPad T400 64754B9       | Notebook    | [11ed3cef75](https://linux-hardware.org/?probe=11ed3cef75) | Apr 20, 2022 |
| Notebook      | NL5xNU                      | Notebook    | [bc83a39684](https://linux-hardware.org/?probe=bc83a39684) | Apr 20, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [d88db86125](https://linux-hardware.org/?probe=d88db86125) | Apr 20, 2022 |
| Lenovo        | ThinkPad T400 6474WBN       | Notebook    | [8bac0a70d6](https://linux-hardware.org/?probe=8bac0a70d6) | Apr 20, 2022 |
| Lenovo        | ThinkPad E480 20KN001QGE    | Notebook    | [6d0ba64623](https://linux-hardware.org/?probe=6d0ba64623) | Apr 19, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [fd661468b9](https://linux-hardware.org/?probe=fd661468b9) | Apr 19, 2022 |
| Lenovo        | ThinkPad T400 6474WBN       | Notebook    | [b7f4f882f3](https://linux-hardware.org/?probe=b7f4f882f3) | Apr 19, 2022 |
| Medion        | Akoya E6416 MD99610         | Notebook    | [5e6e51f206](https://linux-hardware.org/?probe=5e6e51f206) | Apr 19, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [208972e3b5](https://linux-hardware.org/?probe=208972e3b5) | Apr 19, 2022 |
| Medion        | H110H4-EM                   | Desktop     | [358d943521](https://linux-hardware.org/?probe=358d943521) | Apr 19, 2022 |
| Medion        | H81H3-EM2                   | Desktop     | [f9a0473778](https://linux-hardware.org/?probe=f9a0473778) | Apr 19, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [0579e465d1](https://linux-hardware.org/?probe=0579e465d1) | Apr 19, 2022 |
| Lenovo        | ThinkPad X230 2324A15       | Notebook    | [8ff57cadde](https://linux-hardware.org/?probe=8ff57cadde) | Apr 19, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [d300c598e0](https://linux-hardware.org/?probe=d300c598e0) | Apr 19, 2022 |
| MSI           | AMETHYST-M                  | Desktop     | [73864e97e4](https://linux-hardware.org/?probe=73864e97e4) | Apr 19, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [34c876e7e6](https://linux-hardware.org/?probe=34c876e7e6) | Apr 19, 2022 |
| Lenovo        | ThinkCentre M81 5049W16     | Desktop     | [0fd05faa69](https://linux-hardware.org/?probe=0fd05faa69) | Apr 19, 2022 |
| Inventec      | D CLASS A02                 | Desktop     | [d00d37285b](https://linux-hardware.org/?probe=d00d37285b) | Apr 19, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [73dbb7e52a](https://linux-hardware.org/?probe=73dbb7e52a) | Apr 19, 2022 |
| HP            | 470 G8                      | Notebook    | [fb6853bfde](https://linux-hardware.org/?probe=fb6853bfde) | Apr 18, 2022 |
| ASUSTek       | ZenBook UX325SA_UM325SA     | Notebook    | [d3d2e2fe8a](https://linux-hardware.org/?probe=d3d2e2fe8a) | Apr 18, 2022 |
| Toshiba       | Satellite C870-1C2          | Notebook    | [c8917c947b](https://linux-hardware.org/?probe=c8917c947b) | Apr 18, 2022 |
| HP            | ML110 G4                    | Desktop     | [f8ffa1a82a](https://linux-hardware.org/?probe=f8ffa1a82a) | Apr 18, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [068741773e](https://linux-hardware.org/?probe=068741773e) | Apr 18, 2022 |
| Dell          | 0TTDMJ A00                  | Desktop     | [4db6e91115](https://linux-hardware.org/?probe=4db6e91115) | Apr 18, 2022 |
| ASUSTek       | K53SD                       | Notebook    | [0b91570a33](https://linux-hardware.org/?probe=0b91570a33) | Apr 18, 2022 |
| ASUSTek       | G771JW                      | Notebook    | [9b04178e4d](https://linux-hardware.org/?probe=9b04178e4d) | Apr 18, 2022 |
| ASUSTek       | K53SD                       | Notebook    | [169b47991c](https://linux-hardware.org/?probe=169b47991c) | Apr 18, 2022 |
| ASUSTek       | WS C422 SAGE/10G            | Desktop     | [27db6c7db6](https://linux-hardware.org/?probe=27db6c7db6) | Apr 18, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [49d51ee541](https://linux-hardware.org/?probe=49d51ee541) | Apr 18, 2022 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [fefd073d6d](https://linux-hardware.org/?probe=fefd073d6d) | Apr 18, 2022 |
| Shuttle       | FH61V                       | Desktop     | [2fae1ee493](https://linux-hardware.org/?probe=2fae1ee493) | Apr 18, 2022 |
| Timi          | TM1604                      | Notebook    | [2c182df836](https://linux-hardware.org/?probe=2c182df836) | Apr 18, 2022 |
| Packard Be... | DOTM                        | Notebook    | [fc12f3ef5e](https://linux-hardware.org/?probe=fc12f3ef5e) | Apr 18, 2022 |
| Medion        | E6215                       | Notebook    | [39eedb46b2](https://linux-hardware.org/?probe=39eedb46b2) | Apr 18, 2022 |
| MSI           | Z87-GD65 GAMING             | Desktop     | [5bfeeef88e](https://linux-hardware.org/?probe=5bfeeef88e) | Apr 18, 2022 |
| ASRock        | Z87M Extreme4               | Desktop     | [83ffe21604](https://linux-hardware.org/?probe=83ffe21604) | Apr 18, 2022 |
| BESSTAR Te... | GB1B                        | Mini pc     | [c66ed31515](https://linux-hardware.org/?probe=c66ed31515) | Apr 18, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [70beb92c3b](https://linux-hardware.org/?probe=70beb92c3b) | Apr 18, 2022 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | Notebook    | [08f9942632](https://linux-hardware.org/?probe=08f9942632) | Apr 18, 2022 |
| MSI           | X470 GAMING PLUS            | Desktop     | [2ddbae278a](https://linux-hardware.org/?probe=2ddbae278a) | Apr 18, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [3bea0f2a6a](https://linux-hardware.org/?probe=3bea0f2a6a) | Apr 18, 2022 |
| MSI           | Katana GF76 11UG            | Notebook    | [f460a6924f](https://linux-hardware.org/?probe=f460a6924f) | Apr 18, 2022 |
| ASUSTek       | K73BR                       | Notebook    | [596b3b2df6](https://linux-hardware.org/?probe=596b3b2df6) | Apr 18, 2022 |
| Unknown       | Unknown                     | Soc         | [1d48b69381](https://linux-hardware.org/?probe=1d48b69381) | Apr 18, 2022 |
| Fujitsu       | D3162-C1 S26361-D3162-C1    | Desktop     | [3ef27dafd2](https://linux-hardware.org/?probe=3ef27dafd2) | Apr 17, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [f7008a1e16](https://linux-hardware.org/?probe=f7008a1e16) | Apr 17, 2022 |
| Dell          | Latitude E7440              | Notebook    | [bd010335eb](https://linux-hardware.org/?probe=bd010335eb) | Apr 17, 2022 |
| HP            | 86E9 A                      | Desktop     | [11004e6442](https://linux-hardware.org/?probe=11004e6442) | Apr 17, 2022 |
| MSI           | B350M PRO-VDH               | Desktop     | [884f15c1df](https://linux-hardware.org/?probe=884f15c1df) | Apr 17, 2022 |
| Toshiba       | Satellite P200              | Notebook    | [f7726b9903](https://linux-hardware.org/?probe=f7726b9903) | Apr 17, 2022 |
| MSI           | Z77A-GD65                   | Desktop     | [0350456f3b](https://linux-hardware.org/?probe=0350456f3b) | Apr 17, 2022 |
| TUXEDO        | Stellaris Intel Gen3 (TG... | Notebook    | [c1a5e02fa5](https://linux-hardware.org/?probe=c1a5e02fa5) | Apr 17, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [1bf9523120](https://linux-hardware.org/?probe=1bf9523120) | Apr 17, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U4S... | Notebook    | [e5c667382f](https://linux-hardware.org/?probe=e5c667382f) | Apr 17, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [1127f26185](https://linux-hardware.org/?probe=1127f26185) | Apr 17, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X2S... | Notebook    | [e0676b8bc5](https://linux-hardware.org/?probe=e0676b8bc5) | Apr 17, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X2S... | Notebook    | [61bf43c506](https://linux-hardware.org/?probe=61bf43c506) | Apr 17, 2022 |
| Fujitsu       | D3091-A1 S26361-D3091-A1    | Desktop     | [d2559a2f19](https://linux-hardware.org/?probe=d2559a2f19) | Apr 17, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c5bc86febb](https://linux-hardware.org/?probe=c5bc86febb) | Apr 17, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [063cead5c3](https://linux-hardware.org/?probe=063cead5c3) | Apr 17, 2022 |
| Dell          | Latitude XT3                | Notebook    | [c4d7d751b7](https://linux-hardware.org/?probe=c4d7d751b7) | Apr 17, 2022 |
| HP            | Laptop 15s-fq3xxx           | Notebook    | [1fef674c68](https://linux-hardware.org/?probe=1fef674c68) | Apr 17, 2022 |
| MSI           | H510M PRO                   | Desktop     | [a9ce7c295a](https://linux-hardware.org/?probe=a9ce7c295a) | Apr 17, 2022 |
| HP            | 1497                        | Desktop     | [6d2caeac34](https://linux-hardware.org/?probe=6d2caeac34) | Apr 16, 2022 |
| Framework     | Laptop                      | Notebook    | [25577a2915](https://linux-hardware.org/?probe=25577a2915) | Apr 16, 2022 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [0bfefd6499](https://linux-hardware.org/?probe=0bfefd6499) | Apr 16, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [7efbdedc5f](https://linux-hardware.org/?probe=7efbdedc5f) | Apr 16, 2022 |
| Lenovo        | ThinkPad T490 20N3S19L00    | Notebook    | [5812cc4868](https://linux-hardware.org/?probe=5812cc4868) | Apr 16, 2022 |
| Medion        | H110H4-EM                   | Desktop     | [b1fcc5abcf](https://linux-hardware.org/?probe=b1fcc5abcf) | Apr 16, 2022 |
| ASRock        | B550M Phantom Gaming 4      | Desktop     | [3e3e2fd22f](https://linux-hardware.org/?probe=3e3e2fd22f) | Apr 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [ed07e93435](https://linux-hardware.org/?probe=ed07e93435) | Apr 16, 2022 |
| Dell          | Inspiron 13-5378            | Notebook    | [3998a17f75](https://linux-hardware.org/?probe=3998a17f75) | Apr 16, 2022 |
| ASUSTek       | P52F                        | Notebook    | [0cb00534d0](https://linux-hardware.org/?probe=0cb00534d0) | Apr 16, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [a8582f6cb4](https://linux-hardware.org/?probe=a8582f6cb4) | Apr 16, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [d9c6549322](https://linux-hardware.org/?probe=d9c6549322) | Apr 16, 2022 |
| HP            | 1494                        | Desktop     | [6ad3ca1745](https://linux-hardware.org/?probe=6ad3ca1745) | Apr 16, 2022 |
| Acer          | TravelMate P643-M           | Notebook    | [eaec316f95](https://linux-hardware.org/?probe=eaec316f95) | Apr 16, 2022 |
| ASUSTek       | X550LN                      | Notebook    | [2a0b2ae677](https://linux-hardware.org/?probe=2a0b2ae677) | Apr 16, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [2a3f36f9c0](https://linux-hardware.org/?probe=2a3f36f9c0) | Apr 16, 2022 |
| Framework     | Laptop                      | Notebook    | [84da421304](https://linux-hardware.org/?probe=84da421304) | Apr 16, 2022 |
| Fujitsu Si... | D2750-A2 S26361-D2750-A2    | Desktop     | [44b99daa8e](https://linux-hardware.org/?probe=44b99daa8e) | Apr 16, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [2c395ea438](https://linux-hardware.org/?probe=2c395ea438) | Apr 15, 2022 |
| Raspberry ... | BCM2835                     | Soc         | [9ee10a70be](https://linux-hardware.org/?probe=9ee10a70be) | Apr 15, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | Notebook    | [48e04dd798](https://linux-hardware.org/?probe=48e04dd798) | Apr 15, 2022 |
| HP            | Pavilion x2 Detachable      | Tablet      | [fdcebf57ee](https://linux-hardware.org/?probe=fdcebf57ee) | Apr 15, 2022 |
| Samsung       | 930QDB                      | Convertible | [e04b517cae](https://linux-hardware.org/?probe=e04b517cae) | Apr 15, 2022 |
| Toshiba       | TECRA X40-E                 | Notebook    | [0ec808bca1](https://linux-hardware.org/?probe=0ec808bca1) | Apr 15, 2022 |
| Lenovo        | SDK0J40700 WIN              | Desktop     | [142a0092f1](https://linux-hardware.org/?probe=142a0092f1) | Apr 15, 2022 |
| Samsung       | 700T                        | Notebook    | [ff97fa9856](https://linux-hardware.org/?probe=ff97fa9856) | Apr 15, 2022 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [61cad5dcd7](https://linux-hardware.org/?probe=61cad5dcd7) | Apr 15, 2022 |
| ASUSTek       | 1001PX                      | Notebook    | [520db05629](https://linux-hardware.org/?probe=520db05629) | Apr 15, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [c9a7153c14](https://linux-hardware.org/?probe=c9a7153c14) | Apr 15, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [7ea86333a0](https://linux-hardware.org/?probe=7ea86333a0) | Apr 15, 2022 |
| Acer          | Aspire E5-774G              | Notebook    | [d6b3b8f04d](https://linux-hardware.org/?probe=d6b3b8f04d) | Apr 15, 2022 |
| BESSTAR Te... | TL50                        | Desktop     | [28dba12634](https://linux-hardware.org/?probe=28dba12634) | Apr 15, 2022 |
| Lenovo        | ThinkPad T495 20NK000MGE    | Notebook    | [558688bdc2](https://linux-hardware.org/?probe=558688bdc2) | Apr 15, 2022 |
| Sony          | VPCY21S1E                   | Notebook    | [48e798a45c](https://linux-hardware.org/?probe=48e798a45c) | Apr 15, 2022 |
| MSI           | Z87-GD65 GAMING             | Desktop     | [8c57fd797b](https://linux-hardware.org/?probe=8c57fd797b) | Apr 15, 2022 |
| Medion        | H110H4-EM                   | Desktop     | [d4c3d27956](https://linux-hardware.org/?probe=d4c3d27956) | Apr 15, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [078a3464bf](https://linux-hardware.org/?probe=078a3464bf) | Apr 15, 2022 |
| Acer          | TravelMate P643-M           | Notebook    | [92c833cf0b](https://linux-hardware.org/?probe=92c833cf0b) | Apr 15, 2022 |
| HP            | Laptop 15s-fq3xxx           | Notebook    | [1488e2a91f](https://linux-hardware.org/?probe=1488e2a91f) | Apr 15, 2022 |
| ASUSTek       | U33Jc                       | Notebook    | [8be18ca4d1](https://linux-hardware.org/?probe=8be18ca4d1) | Apr 15, 2022 |
| MSI           | B85I GAMING                 | Desktop     | [be865001b9](https://linux-hardware.org/?probe=be865001b9) | Apr 15, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [14f5389e9e](https://linux-hardware.org/?probe=14f5389e9e) | Apr 15, 2022 |
| MSI           | 790FX-GD70                  | Desktop     | [0a8776ac60](https://linux-hardware.org/?probe=0a8776ac60) | Apr 15, 2022 |
| HP            | Pavilion dv7                | Notebook    | [077e8282a3](https://linux-hardware.org/?probe=077e8282a3) | Apr 15, 2022 |
| Dell          | Latitude XT3                | Notebook    | [ce6c2e43a0](https://linux-hardware.org/?probe=ce6c2e43a0) | Apr 15, 2022 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [f52ef2faf2](https://linux-hardware.org/?probe=f52ef2faf2) | Apr 15, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [893e6a634e](https://linux-hardware.org/?probe=893e6a634e) | Apr 15, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [b6a3177491](https://linux-hardware.org/?probe=b6a3177491) | Apr 15, 2022 |
| HP            | EliteBook 2570p             | Notebook    | [6717b9e689](https://linux-hardware.org/?probe=6717b9e689) | Apr 14, 2022 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [da67065e13](https://linux-hardware.org/?probe=da67065e13) | Apr 14, 2022 |
| Framework     | Laptop                      | Notebook    | [4997cab79b](https://linux-hardware.org/?probe=4997cab79b) | Apr 14, 2022 |
| Framework     | Laptop                      | Notebook    | [e4c994f47a](https://linux-hardware.org/?probe=e4c994f47a) | Apr 14, 2022 |
| Fujitsu       | D3513-A1 S26361-D3513-A1    | Desktop     | [72b9c04a51](https://linux-hardware.org/?probe=72b9c04a51) | Apr 14, 2022 |
| Dell          | Latitude E6540              | Notebook    | [2ee68b5f38](https://linux-hardware.org/?probe=2ee68b5f38) | Apr 14, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0000... | Notebook    | [50325a2b5c](https://linux-hardware.org/?probe=50325a2b5c) | Apr 14, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [719a1712f2](https://linux-hardware.org/?probe=719a1712f2) | Apr 14, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [5781ceb5ca](https://linux-hardware.org/?probe=5781ceb5ca) | Apr 14, 2022 |
| Wortmann      | 1220663_1470189             | Notebook    | [59eed1073a](https://linux-hardware.org/?probe=59eed1073a) | Apr 14, 2022 |
| Fujitsu       | D3531-A1 S26361-D3531-A1    | Desktop     | [46dd533a5e](https://linux-hardware.org/?probe=46dd533a5e) | Apr 14, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [6bc3ced902](https://linux-hardware.org/?probe=6bc3ced902) | Apr 14, 2022 |
| TUXEDO        | PA70ES                      | Notebook    | [aa3ae14c59](https://linux-hardware.org/?probe=aa3ae14c59) | Apr 14, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [c372810f3f](https://linux-hardware.org/?probe=c372810f3f) | Apr 14, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [57a3a5a999](https://linux-hardware.org/?probe=57a3a5a999) | Apr 14, 2022 |
| Lenovo        | ThinkPad P52 20MAS17228     | Notebook    | [dac73320e9](https://linux-hardware.org/?probe=dac73320e9) | Apr 14, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [f9b71f206c](https://linux-hardware.org/?probe=f9b71f206c) | Apr 14, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [554040d7b4](https://linux-hardware.org/?probe=554040d7b4) | Apr 14, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [2f865445ce](https://linux-hardware.org/?probe=2f865445ce) | Apr 14, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [d32ffb065a](https://linux-hardware.org/?probe=d32ffb065a) | Apr 14, 2022 |
| Lenovo        | ThinkPad X230 2306CTO       | Notebook    | [7a0b2570f3](https://linux-hardware.org/?probe=7a0b2570f3) | Apr 14, 2022 |
| Chuwi         | MiniBook                    | Notebook    | [3a2e128ecd](https://linux-hardware.org/?probe=3a2e128ecd) | Apr 14, 2022 |
| Framework     | Laptop                      | Notebook    | [b8850e9dc8](https://linux-hardware.org/?probe=b8850e9dc8) | Apr 14, 2022 |
| Acer          | Aspire A717-71G             | Notebook    | [7bf2eeb5cc](https://linux-hardware.org/?probe=7bf2eeb5cc) | Apr 14, 2022 |
| Dell          | 0D24M8 A01                  | Desktop     | [fe4bb32aa1](https://linux-hardware.org/?probe=fe4bb32aa1) | Apr 14, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [ca66ed7272](https://linux-hardware.org/?probe=ca66ed7272) | Apr 14, 2022 |
| Lenovo        | ThinkPad T495s 20QKS01E0... | Notebook    | [4035ec75ce](https://linux-hardware.org/?probe=4035ec75ce) | Apr 14, 2022 |
| Gigabyte      | H97-D3H-CF                  | Desktop     | [e9ad69846b](https://linux-hardware.org/?probe=e9ad69846b) | Apr 14, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | Notebook    | [80572def69](https://linux-hardware.org/?probe=80572def69) | Apr 14, 2022 |
| Lenovo        | ThinkPad T410 2537E82       | Notebook    | [84026a1dd3](https://linux-hardware.org/?probe=84026a1dd3) | Apr 14, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [9715d61366](https://linux-hardware.org/?probe=9715d61366) | Apr 14, 2022 |
| Lenovo        | 30C9 SDK0J40697 WIN 3305... | Desktop     | [d00bde2a05](https://linux-hardware.org/?probe=d00bde2a05) | Apr 14, 2022 |
| Dell          | Precision 5540              | Notebook    | [6bd831ee00](https://linux-hardware.org/?probe=6bd831ee00) | Apr 14, 2022 |
| MSI           | MEG B550 UNIFY              | Desktop     | [8ebb61ef39](https://linux-hardware.org/?probe=8ebb61ef39) | Apr 14, 2022 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | Desktop     | [91a7810a37](https://linux-hardware.org/?probe=91a7810a37) | Apr 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [848f50a317](https://linux-hardware.org/?probe=848f50a317) | Apr 13, 2022 |
| HP            | EliteBook 8540p             | Notebook    | [f6c79e1461](https://linux-hardware.org/?probe=f6c79e1461) | Apr 13, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [003d57b6a3](https://linux-hardware.org/?probe=003d57b6a3) | Apr 13, 2022 |
| Dell          | G7 7700                     | Notebook    | [44407e056c](https://linux-hardware.org/?probe=44407e056c) | Apr 13, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [acd0ebed7c](https://linux-hardware.org/?probe=acd0ebed7c) | Apr 13, 2022 |
| Apple         | MacBookPro10,2              | Notebook    | [cf7c54ff19](https://linux-hardware.org/?probe=cf7c54ff19) | Apr 13, 2022 |
| Lenovo        | ThinkPad E590 20NB0029GE    | Notebook    | [1f9cb1427a](https://linux-hardware.org/?probe=1f9cb1427a) | Apr 13, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [e3cc5e949a](https://linux-hardware.org/?probe=e3cc5e949a) | Apr 13, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [7e03ed9f70](https://linux-hardware.org/?probe=7e03ed9f70) | Apr 13, 2022 |
| HARDKERNEL    | ODROID-H2                   | Desktop     | [63ab4fa5ac](https://linux-hardware.org/?probe=63ab4fa5ac) | Apr 13, 2022 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [6b11750e41](https://linux-hardware.org/?probe=6b11750e41) | Apr 13, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [0897999e8d](https://linux-hardware.org/?probe=0897999e8d) | Apr 13, 2022 |
| ASUSTek       | X99-A                       | Desktop     | [2ac66bb174](https://linux-hardware.org/?probe=2ac66bb174) | Apr 13, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [7a9f6e1de7](https://linux-hardware.org/?probe=7a9f6e1de7) | Apr 13, 2022 |
| Lenovo        | ThinkPad T530 24296HG       | Notebook    | [74191e7ffb](https://linux-hardware.org/?probe=74191e7ffb) | Apr 13, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [d198614ac8](https://linux-hardware.org/?probe=d198614ac8) | Apr 13, 2022 |
| Lenovo        | ThinkPad T480s 20L7001PI... | Notebook    | [53c7e12994](https://linux-hardware.org/?probe=53c7e12994) | Apr 13, 2022 |
| Sony          | SVE1713A1EW                 | Notebook    | [fda4c51d3c](https://linux-hardware.org/?probe=fda4c51d3c) | Apr 13, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [2ae073e712](https://linux-hardware.org/?probe=2ae073e712) | Apr 13, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [332355ddfa](https://linux-hardware.org/?probe=332355ddfa) | Apr 13, 2022 |
| ASUSTek       | Z87-PLUS                    | Desktop     | [22fe7aea72](https://linux-hardware.org/?probe=22fe7aea72) | Apr 13, 2022 |
| Dell          | Inspiron 5590               | Notebook    | [1605fca16d](https://linux-hardware.org/?probe=1605fca16d) | Apr 13, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [3e26cc6c66](https://linux-hardware.org/?probe=3e26cc6c66) | Apr 13, 2022 |
| Acer          | Aspire 7750G                | Notebook    | [64ff7776eb](https://linux-hardware.org/?probe=64ff7776eb) | Apr 13, 2022 |
| Dell          | Latitude 7400               | Notebook    | [2c32d69a57](https://linux-hardware.org/?probe=2c32d69a57) | Apr 13, 2022 |
| Acer          | Aspire E5-774G              | Notebook    | [ef43a63289](https://linux-hardware.org/?probe=ef43a63289) | Apr 13, 2022 |
| ASRock        | H97 Pro4                    | Desktop     | [db6bf8f1b9](https://linux-hardware.org/?probe=db6bf8f1b9) | Apr 13, 2022 |
| Samsung       | R505                        | Notebook    | [9ff46a8ca6](https://linux-hardware.org/?probe=9ff46a8ca6) | Apr 13, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [95cff2fbb1](https://linux-hardware.org/?probe=95cff2fbb1) | Apr 13, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [1a012021cb](https://linux-hardware.org/?probe=1a012021cb) | Apr 13, 2022 |
| Fujitsu       | D3162-C1 S26361-D3162-C1    | Desktop     | [5f4fac95df](https://linux-hardware.org/?probe=5f4fac95df) | Apr 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [4a91953dcb](https://linux-hardware.org/?probe=4a91953dcb) | Apr 13, 2022 |
| Dell          | Inspiron 5502               | Notebook    | [f39e4ba3dd](https://linux-hardware.org/?probe=f39e4ba3dd) | Apr 13, 2022 |
| ASUSTek       | PRIME Z690M-HZ              | Desktop     | [4bf977cb4d](https://linux-hardware.org/?probe=4bf977cb4d) | Apr 13, 2022 |
| Lenovo        | V130-15IKB 81HN             | Notebook    | [4228ebaeeb](https://linux-hardware.org/?probe=4228ebaeeb) | Apr 13, 2022 |
| Samsung       | 750XDA                      | Notebook    | [e2c10772c0](https://linux-hardware.org/?probe=e2c10772c0) | Apr 13, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [3440d2dd8c](https://linux-hardware.org/?probe=3440d2dd8c) | Apr 12, 2022 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [c74caa4194](https://linux-hardware.org/?probe=c74caa4194) | Apr 12, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [47404cf177](https://linux-hardware.org/?probe=47404cf177) | Apr 12, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [842cfcf606](https://linux-hardware.org/?probe=842cfcf606) | Apr 12, 2022 |
| Unknown       | Unknown                     | Soc         | [032d99b6df](https://linux-hardware.org/?probe=032d99b6df) | Apr 12, 2022 |
| Sony          | VGN-FZ21M                   | Notebook    | [a075507687](https://linux-hardware.org/?probe=a075507687) | Apr 12, 2022 |
| Dell          | Precision 5520              | Notebook    | [eb5bfc87ed](https://linux-hardware.org/?probe=eb5bfc87ed) | Apr 12, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [bdccad7bf9](https://linux-hardware.org/?probe=bdccad7bf9) | Apr 12, 2022 |
| Fujitsu       | LIFEBOOK A512               | Notebook    | [a477479700](https://linux-hardware.org/?probe=a477479700) | Apr 12, 2022 |
| Sony          | VGN-CS31S_W                 | Notebook    | [148f5f1564](https://linux-hardware.org/?probe=148f5f1564) | Apr 12, 2022 |
| MSI           | H510M PRO                   | Desktop     | [19dffc4e17](https://linux-hardware.org/?probe=19dffc4e17) | Apr 12, 2022 |
| MSI           | H510M PRO                   | Desktop     | [c4cd29bb7f](https://linux-hardware.org/?probe=c4cd29bb7f) | Apr 12, 2022 |
| Lenovo        | ThinkPad T430 2349T2A       | Notebook    | [344710cc3a](https://linux-hardware.org/?probe=344710cc3a) | Apr 12, 2022 |
| Sony          | VGN-FZ21M                   | Notebook    | [e8c7c66ae9](https://linux-hardware.org/?probe=e8c7c66ae9) | Apr 12, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [97bd95a7bb](https://linux-hardware.org/?probe=97bd95a7bb) | Apr 12, 2022 |
| Acer          | Aspire E5-774G              | Notebook    | [6c61158fd5](https://linux-hardware.org/?probe=6c61158fd5) | Apr 12, 2022 |
| Dell          | Precision 5520              | Notebook    | [0c7ae3171f](https://linux-hardware.org/?probe=0c7ae3171f) | Apr 12, 2022 |
| Fujitsu       | LIFEBOOK S760               | Notebook    | [6cb98b4c28](https://linux-hardware.org/?probe=6cb98b4c28) | Apr 12, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [7007f9e0fc](https://linux-hardware.org/?probe=7007f9e0fc) | Apr 12, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [15cf291bf3](https://linux-hardware.org/?probe=15cf291bf3) | Apr 12, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [b8ca5707e7](https://linux-hardware.org/?probe=b8ca5707e7) | Apr 11, 2022 |
| MSI           | Z170-A PRO                  | Desktop     | [db5ab86328](https://linux-hardware.org/?probe=db5ab86328) | Apr 11, 2022 |
| Lenovo        | 3178 SDK0J40700 WIN 3258... | Desktop     | [637023ab6d](https://linux-hardware.org/?probe=637023ab6d) | Apr 11, 2022 |
| Lenovo        | ThinkPad P51 20HJS1GU00     | Notebook    | [8f92a8ffda](https://linux-hardware.org/?probe=8f92a8ffda) | Apr 11, 2022 |
| Lenovo        | ThinkPad L13 Yoga 20R500... | Convertible | [683c394458](https://linux-hardware.org/?probe=683c394458) | Apr 11, 2022 |
| Xunlong       | Orange Pi PC                | Soc         | [6280e20fbe](https://linux-hardware.org/?probe=6280e20fbe) | Apr 11, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [7a90612309](https://linux-hardware.org/?probe=7a90612309) | Apr 11, 2022 |
| Lenovo        | ThinkCentre M81 5049W16     | Desktop     | [201076a42a](https://linux-hardware.org/?probe=201076a42a) | Apr 11, 2022 |
| Medion        | P6612                       | Notebook    | [14a3483a73](https://linux-hardware.org/?probe=14a3483a73) | Apr 11, 2022 |
| Medion        | P6612                       | Notebook    | [7ac5186e28](https://linux-hardware.org/?probe=7ac5186e28) | Apr 11, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [153f53dadd](https://linux-hardware.org/?probe=153f53dadd) | Apr 11, 2022 |
| Acer          | Aspire A515-54G             | Notebook    | [52b660d8fb](https://linux-hardware.org/?probe=52b660d8fb) | Apr 11, 2022 |
| Lenovo        | ThinkPad X230 23255Z6       | Notebook    | [4a9a1b9415](https://linux-hardware.org/?probe=4a9a1b9415) | Apr 11, 2022 |
| Lenovo        | ThinkPad L560 20F1001YGE    | Notebook    | [9a6b2ad9f9](https://linux-hardware.org/?probe=9a6b2ad9f9) | Apr 11, 2022 |
| HP            | Spectre x360 Conv 15-df1... | Convertible | [74cfc23ef9](https://linux-hardware.org/?probe=74cfc23ef9) | Apr 11, 2022 |
| Lenovo        | ThinkPad L560 20F1001YGE    | Notebook    | [574edf3e3b](https://linux-hardware.org/?probe=574edf3e3b) | Apr 11, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [355230b16d](https://linux-hardware.org/?probe=355230b16d) | Apr 11, 2022 |
| eMachines     | EL1850                      | Desktop     | [4c641c8e6a](https://linux-hardware.org/?probe=4c641c8e6a) | Apr 11, 2022 |
| Gigabyte      | Z97-HD3                     | Desktop     | [0f28cbb37d](https://linux-hardware.org/?probe=0f28cbb37d) | Apr 11, 2022 |
| Acer          | Aspire E5-571G              | Notebook    | [8afbbeeec0](https://linux-hardware.org/?probe=8afbbeeec0) | Apr 11, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [edebd20c8e](https://linux-hardware.org/?probe=edebd20c8e) | Apr 11, 2022 |
| Samsung       | SX10P                       | Notebook    | [818c4884b1](https://linux-hardware.org/?probe=818c4884b1) | Apr 11, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [5d36c5b15f](https://linux-hardware.org/?probe=5d36c5b15f) | Apr 11, 2022 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [17f7c92cc6](https://linux-hardware.org/?probe=17f7c92cc6) | Apr 11, 2022 |
| MSI           | B460M PRO-VDH WIFI          | Desktop     | [27cb501628](https://linux-hardware.org/?probe=27cb501628) | Apr 11, 2022 |
| Unknown       | Unknown                     | Soc         | [0bfb497ab1](https://linux-hardware.org/?probe=0bfb497ab1) | Apr 10, 2022 |
| Fujitsu       | D2912-A1 S26361-D2912-A1    | Desktop     | [210b897284](https://linux-hardware.org/?probe=210b897284) | Apr 10, 2022 |
| ASUSTek       | GL702VM                     | Notebook    | [70ff5129b4](https://linux-hardware.org/?probe=70ff5129b4) | Apr 10, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [c522f42e92](https://linux-hardware.org/?probe=c522f42e92) | Apr 10, 2022 |
| MSI           | Z170-A PRO                  | Desktop     | [3bd5bb8d08](https://linux-hardware.org/?probe=3bd5bb8d08) | Apr 10, 2022 |
| Lenovo        | IdeaPad Z585                | Notebook    | [5f84c70657](https://linux-hardware.org/?probe=5f84c70657) | Apr 10, 2022 |
| TUXEDO        | N15_17RD                    | Notebook    | [f4ad87db26](https://linux-hardware.org/?probe=f4ad87db26) | Apr 10, 2022 |
| HP            | 21F5 0A                     | Desktop     | [516f2dbc9e](https://linux-hardware.org/?probe=516f2dbc9e) | Apr 10, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e55b3bf73c](https://linux-hardware.org/?probe=e55b3bf73c) | Apr 10, 2022 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [71adeab793](https://linux-hardware.org/?probe=71adeab793) | Apr 10, 2022 |
| Gigabyte      | W480 VISION D               | Desktop     | [69e85ce80c](https://linux-hardware.org/?probe=69e85ce80c) | Apr 10, 2022 |
| ASRock        | H110M-ITX                   | Desktop     | [13dff6f000](https://linux-hardware.org/?probe=13dff6f000) | Apr 10, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [c19db93d49](https://linux-hardware.org/?probe=c19db93d49) | Apr 10, 2022 |
| Dell          | Latitude E6230              | Notebook    | [67750bdf0f](https://linux-hardware.org/?probe=67750bdf0f) | Apr 10, 2022 |
| Dell          | 0KC9NP A00                  | Desktop     | [7b3bb36e84](https://linux-hardware.org/?probe=7b3bb36e84) | Apr 10, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [76b5ee9d73](https://linux-hardware.org/?probe=76b5ee9d73) | Apr 10, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [4caf7ae4fc](https://linux-hardware.org/?probe=4caf7ae4fc) | Apr 10, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [6d3fe856b8](https://linux-hardware.org/?probe=6d3fe856b8) | Apr 10, 2022 |
| Medion        | H81H3-EM2 H81EM2W08.309     | Desktop     | [9d20eaf1f2](https://linux-hardware.org/?probe=9d20eaf1f2) | Apr 10, 2022 |
| Acer          | Aspire A517-52G             | Notebook    | [27d8eebf76](https://linux-hardware.org/?probe=27d8eebf76) | Apr 10, 2022 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [8cb4405c5f](https://linux-hardware.org/?probe=8cb4405c5f) | Apr 09, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [ad84faeb49](https://linux-hardware.org/?probe=ad84faeb49) | Apr 09, 2022 |
| Dell          | Latitude E6230              | Notebook    | [db52ca23d3](https://linux-hardware.org/?probe=db52ca23d3) | Apr 09, 2022 |
| Acer          | Spin SP513-55N              | Convertible | [e6c72ac537](https://linux-hardware.org/?probe=e6c72ac537) | Apr 09, 2022 |
| Dell          | Latitude 5590               | Notebook    | [6ba3c2dc45](https://linux-hardware.org/?probe=6ba3c2dc45) | Apr 09, 2022 |
| Dell          | Latitude 5590               | Notebook    | [4e85ea549a](https://linux-hardware.org/?probe=4e85ea549a) | Apr 09, 2022 |
| Lenovo        | ThinkPad T460 20FMS25902    | Notebook    | [8645c57fcc](https://linux-hardware.org/?probe=8645c57fcc) | Apr 09, 2022 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | Desktop     | [50cfb4d530](https://linux-hardware.org/?probe=50cfb4d530) | Apr 09, 2022 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [18045cb759](https://linux-hardware.org/?probe=18045cb759) | Apr 09, 2022 |
| LG Electro... | 16T90P-G.AA78G              | Convertible | [ce2baa0955](https://linux-hardware.org/?probe=ce2baa0955) | Apr 09, 2022 |
| Acer          | Aspire E5-774G              | Notebook    | [5d6cbe9aa4](https://linux-hardware.org/?probe=5d6cbe9aa4) | Apr 09, 2022 |
| ASUSTek       | X555LJ                      | Notebook    | [e7e9bc2b60](https://linux-hardware.org/?probe=e7e9bc2b60) | Apr 09, 2022 |
| Unknown       | Unknown                     | Soc         | [fe909d3555](https://linux-hardware.org/?probe=fe909d3555) | Apr 09, 2022 |
| Acer          | TravelMate P258-M           | Notebook    | [9f107a3174](https://linux-hardware.org/?probe=9f107a3174) | Apr 09, 2022 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [bd37b65123](https://linux-hardware.org/?probe=bd37b65123) | Apr 09, 2022 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [37392321fc](https://linux-hardware.org/?probe=37392321fc) | Apr 09, 2022 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [17216f9bb3](https://linux-hardware.org/?probe=17216f9bb3) | Apr 09, 2022 |
| Lenovo        | ThinkPad T470 20HES18R2C    | Notebook    | [2b0c006e2b](https://linux-hardware.org/?probe=2b0c006e2b) | Apr 09, 2022 |
| Unknown       | Unknown                     | Soc         | [2faa80e7bc](https://linux-hardware.org/?probe=2faa80e7bc) | Apr 09, 2022 |
| MSI           | MS-7369                     | Desktop     | [0a32c9427a](https://linux-hardware.org/?probe=0a32c9427a) | Apr 09, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [ce9698e187](https://linux-hardware.org/?probe=ce9698e187) | Apr 09, 2022 |
| MSI           | Z77A-G45 GAMING             | Desktop     | [622ecbb225](https://linux-hardware.org/?probe=622ecbb225) | Apr 09, 2022 |
| Samsung       | 870Z5E/880Z5E/680Z5E        | Notebook    | [19450f9d90](https://linux-hardware.org/?probe=19450f9d90) | Apr 09, 2022 |
| Foxconn       | A7DA 3 series               | Desktop     | [2fc0654e61](https://linux-hardware.org/?probe=2fc0654e61) | Apr 09, 2022 |
| Lenovo        | IdeaPad U430 Touch 20270    | Notebook    | [dc2a98fe3d](https://linux-hardware.org/?probe=dc2a98fe3d) | Apr 09, 2022 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | Notebook    | [10d0d3a721](https://linux-hardware.org/?probe=10d0d3a721) | Apr 09, 2022 |
| ASRock        | Z77 Pro4                    | Desktop     | [38eeb648af](https://linux-hardware.org/?probe=38eeb648af) | Apr 09, 2022 |
| ASUSTek       | P50IJ                       | Notebook    | [406b6b3862](https://linux-hardware.org/?probe=406b6b3862) | Apr 09, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [e349262622](https://linux-hardware.org/?probe=e349262622) | Apr 09, 2022 |
| MSI           | 2AE0                        | Desktop     | [57e29c9110](https://linux-hardware.org/?probe=57e29c9110) | Apr 09, 2022 |
| Lenovo        | ThinkPad S1 Yoga 20CDCTO... | Notebook    | [eebc86ccbe](https://linux-hardware.org/?probe=eebc86ccbe) | Apr 09, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [1a0e3a2e7d](https://linux-hardware.org/?probe=1a0e3a2e7d) | Apr 09, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [a5123ca9d5](https://linux-hardware.org/?probe=a5123ca9d5) | Apr 09, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [dc76bbdce6](https://linux-hardware.org/?probe=dc76bbdce6) | Apr 09, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [08f79499bd](https://linux-hardware.org/?probe=08f79499bd) | Apr 09, 2022 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [648d7a9a57](https://linux-hardware.org/?probe=648d7a9a57) | Apr 09, 2022 |
| Biostar       | B550MH                      | Desktop     | [abd373497b](https://linux-hardware.org/?probe=abd373497b) | Apr 09, 2022 |
| Gigabyte      | B360HD3PLM-CF               | Desktop     | [1c3d254151](https://linux-hardware.org/?probe=1c3d254151) | Apr 09, 2022 |
| Dell          | Latitude E6330              | Notebook    | [371edded6f](https://linux-hardware.org/?probe=371edded6f) | Apr 09, 2022 |
| Gigabyte      | B360HD3PLM-CF               | Desktop     | [d966170231](https://linux-hardware.org/?probe=d966170231) | Apr 09, 2022 |
| Medion        | TJ4125                      | Desktop     | [4541511f38](https://linux-hardware.org/?probe=4541511f38) | Apr 08, 2022 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [5dd55bbf65](https://linux-hardware.org/?probe=5dd55bbf65) | Apr 08, 2022 |
| Gigabyte      | MZBSWAP-K4                  | Desktop     | [8f7798d84a](https://linux-hardware.org/?probe=8f7798d84a) | Apr 08, 2022 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [1946a36c0f](https://linux-hardware.org/?probe=1946a36c0f) | Apr 08, 2022 |
| Lenovo        | IdeaPad S206 2638           | Notebook    | [6236abf04e](https://linux-hardware.org/?probe=6236abf04e) | Apr 08, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [03940a7514](https://linux-hardware.org/?probe=03940a7514) | Apr 08, 2022 |
| Sony          | SVE1511W1ESI                | Notebook    | [403773664b](https://linux-hardware.org/?probe=403773664b) | Apr 08, 2022 |
| Acer          | Aspire R3-131T              | Notebook    | [15f16fd968](https://linux-hardware.org/?probe=15f16fd968) | Apr 08, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [c0d7bcd89b](https://linux-hardware.org/?probe=c0d7bcd89b) | Apr 08, 2022 |
| Unknown       | Unknown                     | Soc         | [febedc6435](https://linux-hardware.org/?probe=febedc6435) | Apr 08, 2022 |
| Unknown       | Unknown                     | Soc         | [99029e9661](https://linux-hardware.org/?probe=99029e9661) | Apr 08, 2022 |
| EVGA          | 140-SS-E177                 | Desktop     | [4af369b993](https://linux-hardware.org/?probe=4af369b993) | Apr 08, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [d973a4378b](https://linux-hardware.org/?probe=d973a4378b) | Apr 08, 2022 |
| Fujitsu       | D3028-A1 S26361-D3028-A1    | Desktop     | [1a031845b1](https://linux-hardware.org/?probe=1a031845b1) | Apr 08, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [f21e5ade5d](https://linux-hardware.org/?probe=f21e5ade5d) | Apr 08, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [7438fcdda2](https://linux-hardware.org/?probe=7438fcdda2) | Apr 08, 2022 |
| ASRockRack    | B565D4-V1L                  | Desktop     | [12f3bc72ea](https://linux-hardware.org/?probe=12f3bc72ea) | Apr 08, 2022 |
| Lenovo        | ThinkPad T460 20FMS25902    | Notebook    | [ff290845fe](https://linux-hardware.org/?probe=ff290845fe) | Apr 08, 2022 |
| Lenovo        | ThinkPad T400 6475E13       | Notebook    | [cd49ac8445](https://linux-hardware.org/?probe=cd49ac8445) | Apr 08, 2022 |
| ASUSTek       | B150M-C                     | Desktop     | [008522be3f](https://linux-hardware.org/?probe=008522be3f) | Apr 08, 2022 |
| ASUSTek       | B150M-C                     | Desktop     | [5c4348526d](https://linux-hardware.org/?probe=5c4348526d) | Apr 08, 2022 |
| ASRock        | 990FX Extreme3              | Desktop     | [74624f8363](https://linux-hardware.org/?probe=74624f8363) | Apr 08, 2022 |
| Unknown       | HX90                        | Desktop     | [ab8a381a52](https://linux-hardware.org/?probe=ab8a381a52) | Apr 08, 2022 |
| Acer          | Spin SP513-55N              | Convertible | [df0eb8ce44](https://linux-hardware.org/?probe=df0eb8ce44) | Apr 07, 2022 |
| Lenovo        | ThinkPad T520 42404CG       | Notebook    | [cf8cc68083](https://linux-hardware.org/?probe=cf8cc68083) | Apr 07, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [bde8b0ab3c](https://linux-hardware.org/?probe=bde8b0ab3c) | Apr 07, 2022 |
| Lenovo        | 3130 SDK0J40700 WIN 3258... | Mini pc     | [b1de91e35f](https://linux-hardware.org/?probe=b1de91e35f) | Apr 07, 2022 |
| Biostar       | N68S3B                      | Desktop     | [9410ef1116](https://linux-hardware.org/?probe=9410ef1116) | Apr 07, 2022 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [c5ea221f34](https://linux-hardware.org/?probe=c5ea221f34) | Apr 07, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [b43ffa5ce5](https://linux-hardware.org/?probe=b43ffa5ce5) | Apr 07, 2022 |
| ASRock        | Z87 Extreme6                | Desktop     | [7d74be6897](https://linux-hardware.org/?probe=7d74be6897) | Apr 07, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [808661699f](https://linux-hardware.org/?probe=808661699f) | Apr 07, 2022 |
| Sony          | VGN-FZ21M                   | Notebook    | [74b2235e4d](https://linux-hardware.org/?probe=74b2235e4d) | Apr 07, 2022 |
| Acer          | Aspire A515-56              | Notebook    | [46f9e8b140](https://linux-hardware.org/?probe=46f9e8b140) | Apr 07, 2022 |
| Acer          | Aspire A515-56              | Notebook    | [db6408f394](https://linux-hardware.org/?probe=db6408f394) | Apr 07, 2022 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [5b3b1df897](https://linux-hardware.org/?probe=5b3b1df897) | Apr 07, 2022 |
| Gigabyte      | W480 VISION D               | Desktop     | [da6d84cf89](https://linux-hardware.org/?probe=da6d84cf89) | Apr 07, 2022 |
| Lenovo        | Yoga 730-15IWL 81JS         | Convertible | [9c8eb39bf5](https://linux-hardware.org/?probe=9c8eb39bf5) | Apr 07, 2022 |
| ASUSTek       | Z11PG-D16 Series            | Server      | [1126ae11ae](https://linux-hardware.org/?probe=1126ae11ae) | Apr 07, 2022 |
| ASUSTek       | Z10PG-D16 Series            | Desktop     | [9076954881](https://linux-hardware.org/?probe=9076954881) | Apr 07, 2022 |
| HP            | 625                         | Notebook    | [940d71be52](https://linux-hardware.org/?probe=940d71be52) | Apr 07, 2022 |
| Toshiba       | Satellite L755              | Notebook    | [be86a2f36e](https://linux-hardware.org/?probe=be86a2f36e) | Apr 07, 2022 |
| Unknown       | HX90                        | Desktop     | [a83217f763](https://linux-hardware.org/?probe=a83217f763) | Apr 07, 2022 |
| Unknown       | HX90                        | Desktop     | [fa9981d1bd](https://linux-hardware.org/?probe=fa9981d1bd) | Apr 07, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [224591ad3c](https://linux-hardware.org/?probe=224591ad3c) | Apr 07, 2022 |
| ASRock        | 990FX Extreme3              | Desktop     | [d7ca137052](https://linux-hardware.org/?probe=d7ca137052) | Apr 07, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [dea231bf61](https://linux-hardware.org/?probe=dea231bf61) | Apr 07, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [93aa02920a](https://linux-hardware.org/?probe=93aa02920a) | Apr 07, 2022 |
| Acer          | Aspire 7735                 | Notebook    | [e54c0831d6](https://linux-hardware.org/?probe=e54c0831d6) | Apr 07, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [b02ac7d8ce](https://linux-hardware.org/?probe=b02ac7d8ce) | Apr 07, 2022 |
| Fujitsu Si... | D2587-A1 S26361-D2587-A1    | Desktop     | [45c9919e96](https://linux-hardware.org/?probe=45c9919e96) | Apr 07, 2022 |
| Dell          | Latitude 7490               | Notebook    | [167ce24f1b](https://linux-hardware.org/?probe=167ce24f1b) | Apr 06, 2022 |
| Medion        | WIM2140                     | Notebook    | [881f38fd33](https://linux-hardware.org/?probe=881f38fd33) | Apr 06, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [c1e66c6b66](https://linux-hardware.org/?probe=c1e66c6b66) | Apr 06, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [b55c08dfe9](https://linux-hardware.org/?probe=b55c08dfe9) | Apr 06, 2022 |
| Dell          | Latitude 5511               | Notebook    | [2cb0a3e451](https://linux-hardware.org/?probe=2cb0a3e451) | Apr 06, 2022 |
| ASUSTek       | Z97-K                       | Desktop     | [605aa4f068](https://linux-hardware.org/?probe=605aa4f068) | Apr 06, 2022 |
| MSI           | MS-7358 Fab D               | Desktop     | [1867be94e3](https://linux-hardware.org/?probe=1867be94e3) | Apr 06, 2022 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [a3d3ff5ac5](https://linux-hardware.org/?probe=a3d3ff5ac5) | Apr 06, 2022 |
| Medion        | E2292                       | Convertible | [3302d8f658](https://linux-hardware.org/?probe=3302d8f658) | Apr 06, 2022 |
| Lenovo        | Yoga 720-13IKB 80X6         | Convertible | [fec8eba815](https://linux-hardware.org/?probe=fec8eba815) | Apr 06, 2022 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [59479b59ec](https://linux-hardware.org/?probe=59479b59ec) | Apr 06, 2022 |
| Gigabyte      | B360M D2V                   | Desktop     | [87f55ffa54](https://linux-hardware.org/?probe=87f55ffa54) | Apr 06, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [64c2c15492](https://linux-hardware.org/?probe=64c2c15492) | Apr 05, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [93dd14057b](https://linux-hardware.org/?probe=93dd14057b) | Apr 05, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [951f88b858](https://linux-hardware.org/?probe=951f88b858) | Apr 05, 2022 |
| Lenovo        | 3135 SDK0J40697 WIN 3305... | Mini pc     | [13aafa70b2](https://linux-hardware.org/?probe=13aafa70b2) | Apr 05, 2022 |
| Dell          | Latitude E6430              | Notebook    | [c974a805b2](https://linux-hardware.org/?probe=c974a805b2) | Apr 05, 2022 |
| Wortmann      | TERRA_MOBILE_1749           | Notebook    | [ee8ada5124](https://linux-hardware.org/?probe=ee8ada5124) | Apr 05, 2022 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [3c27532090](https://linux-hardware.org/?probe=3c27532090) | Apr 05, 2022 |
| LincPlus      | LINNCPLUS P1                | Notebook    | [742273ee3f](https://linux-hardware.org/?probe=742273ee3f) | Apr 05, 2022 |
| Microsoft     | Surface Pro 7               | Tablet      | [a4e35bec86](https://linux-hardware.org/?probe=a4e35bec86) | Apr 05, 2022 |
| ASRock        | Z97X Killer                 | Desktop     | [628d137846](https://linux-hardware.org/?probe=628d137846) | Apr 05, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [c95df20756](https://linux-hardware.org/?probe=c95df20756) | Apr 05, 2022 |
| HP            | 1494                        | Desktop     | [5d81c1dd3c](https://linux-hardware.org/?probe=5d81c1dd3c) | Apr 05, 2022 |
| HP            | EliteBook 6930p             | Notebook    | [7427928bef](https://linux-hardware.org/?probe=7427928bef) | Apr 05, 2022 |
| Lenovo        | MAHOBAY                     | Desktop     | [ad714d63bc](https://linux-hardware.org/?probe=ad714d63bc) | Apr 05, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [5600c7649a](https://linux-hardware.org/?probe=5600c7649a) | Apr 05, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [d2f9498bd2](https://linux-hardware.org/?probe=d2f9498bd2) | Apr 05, 2022 |
| Lenovo        | 1036 SDK0K17763 WIN 1801... | Desktop     | [eec98977a3](https://linux-hardware.org/?probe=eec98977a3) | Apr 05, 2022 |
| Razer         | Blade Stealth               | Notebook    | [426dc681c4](https://linux-hardware.org/?probe=426dc681c4) | Apr 05, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [493d8fa69d](https://linux-hardware.org/?probe=493d8fa69d) | Apr 05, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [3f086610fc](https://linux-hardware.org/?probe=3f086610fc) | Apr 05, 2022 |
| ASUSTek       | 1101HA                      | Notebook    | [c3d2458d59](https://linux-hardware.org/?probe=c3d2458d59) | Apr 04, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [92130ffb61](https://linux-hardware.org/?probe=92130ffb61) | Apr 04, 2022 |
| MSI           | H510M PRO                   | Desktop     | [0874882b3f](https://linux-hardware.org/?probe=0874882b3f) | Apr 04, 2022 |
| Foxconn       | 2A8C                        | Desktop     | [e4d8c4ccf0](https://linux-hardware.org/?probe=e4d8c4ccf0) | Apr 04, 2022 |
| ASUSTek       | N750JK                      | Notebook    | [c17c4c69dd](https://linux-hardware.org/?probe=c17c4c69dd) | Apr 04, 2022 |
| ASUSTek       | N750JK                      | Notebook    | [9c39cbaec6](https://linux-hardware.org/?probe=9c39cbaec6) | Apr 04, 2022 |
| ASUSTek       | ROG Strix G712LU_G712LU     | Notebook    | [288629b95d](https://linux-hardware.org/?probe=288629b95d) | Apr 04, 2022 |
| Dell          | 0WR7PY A02                  | Desktop     | [3086c641fb](https://linux-hardware.org/?probe=3086c641fb) | Apr 04, 2022 |
| MSI           | H510M PRO                   | Desktop     | [ee05ef80b8](https://linux-hardware.org/?probe=ee05ef80b8) | Apr 04, 2022 |
| Fujitsu       | LIFEBOOK S752               | Notebook    | [307e875610](https://linux-hardware.org/?probe=307e875610) | Apr 04, 2022 |
| ASUSTek       | P6T                         | Desktop     | [5ed6ed355f](https://linux-hardware.org/?probe=5ed6ed355f) | Apr 04, 2022 |
| Notebook      | NL40_50CU                   | Notebook    | [84ce11e08a](https://linux-hardware.org/?probe=84ce11e08a) | Apr 04, 2022 |
| MSI           | H97 PC Mate                 | Desktop     | [8e47753650](https://linux-hardware.org/?probe=8e47753650) | Apr 04, 2022 |
| MSI           | H97 PC Mate                 | Desktop     | [98788451c4](https://linux-hardware.org/?probe=98788451c4) | Apr 04, 2022 |
| Lenovo        | IdeaPad S12 20021,2959      | Notebook    | [e3fc33ffe1](https://linux-hardware.org/?probe=e3fc33ffe1) | Apr 04, 2022 |
| MSI           | H510M PRO                   | Desktop     | [e11c2453c5](https://linux-hardware.org/?probe=e11c2453c5) | Apr 04, 2022 |
| ASUSTek       | H81M-E                      | Desktop     | [2659a11330](https://linux-hardware.org/?probe=2659a11330) | Apr 04, 2022 |
| Lenovo        | SKYBAY SDK0J40709 WIN 32... | All in one  | [9f7bf085d3](https://linux-hardware.org/?probe=9f7bf085d3) | Apr 04, 2022 |
| HP            | 805D                        | Desktop     | [198cff1b8e](https://linux-hardware.org/?probe=198cff1b8e) | Apr 04, 2022 |
| Gigabyte      | Z690 UD AX                  | Desktop     | [e7083be036](https://linux-hardware.org/?probe=e7083be036) | Apr 04, 2022 |
| Shuttle       | FS35V4                      | Desktop     | [bfe34cde0c](https://linux-hardware.org/?probe=bfe34cde0c) | Apr 04, 2022 |
| Sony          | SVE1712C1EW                 | Notebook    | [989843d8cf](https://linux-hardware.org/?probe=989843d8cf) | Apr 04, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [55ad4e2b02](https://linux-hardware.org/?probe=55ad4e2b02) | Apr 04, 2022 |
| HP            | 630                         | Notebook    | [555bedb0cd](https://linux-hardware.org/?probe=555bedb0cd) | Apr 04, 2022 |
| Medion        | S6417 MD99651               | Notebook    | [2911120bc0](https://linux-hardware.org/?probe=2911120bc0) | Apr 04, 2022 |
| rockchip      | evb_rk3399                  | Soc         | [eb6d292832](https://linux-hardware.org/?probe=eb6d292832) | Apr 04, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [f067a2d929](https://linux-hardware.org/?probe=f067a2d929) | Apr 04, 2022 |
| Medion        | S561X                       | Notebook    | [468655cc72](https://linux-hardware.org/?probe=468655cc72) | Apr 03, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [5348103896](https://linux-hardware.org/?probe=5348103896) | Apr 03, 2022 |
| Wortmann      | M7x0S                       | Notebook    | [f25fe54ad4](https://linux-hardware.org/?probe=f25fe54ad4) | Apr 03, 2022 |
| Wortmann      | M7x0S                       | Notebook    | [364f9cbe89](https://linux-hardware.org/?probe=364f9cbe89) | Apr 03, 2022 |
| ZOTAC         | ZBOX-CI331NANO              | Mini pc     | [82755e6bda](https://linux-hardware.org/?probe=82755e6bda) | Apr 03, 2022 |
| TUXEDO        | InfinityBook S 14 v5        | Notebook    | [6a5061e741](https://linux-hardware.org/?probe=6a5061e741) | Apr 03, 2022 |
| Lenovo        | ThinkPad T480s 20L7001SG... | Notebook    | [440bfc13d9](https://linux-hardware.org/?probe=440bfc13d9) | Apr 03, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [adf5387ae0](https://linux-hardware.org/?probe=adf5387ae0) | Apr 03, 2022 |
| Sony          | SVE1712C1EW                 | Notebook    | [5e530d1a32](https://linux-hardware.org/?probe=5e530d1a32) | Apr 03, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [5bd412532b](https://linux-hardware.org/?probe=5bd412532b) | Apr 03, 2022 |
| Samsung       | R580/R590                   | Notebook    | [0b95325a5e](https://linux-hardware.org/?probe=0b95325a5e) | Apr 03, 2022 |
| ZOTAC         | ZBOX-CI331NANO              | Mini pc     | [6803d4bbe7](https://linux-hardware.org/?probe=6803d4bbe7) | Apr 03, 2022 |
| MSI           | GP76 Leopard 10UE           | Notebook    | [fa973d27a6](https://linux-hardware.org/?probe=fa973d27a6) | Apr 03, 2022 |
| ASUSTek       | PRIME H570-PLUS             | Desktop     | [4a9be0ab22](https://linux-hardware.org/?probe=4a9be0ab22) | Apr 03, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [70b67b462b](https://linux-hardware.org/?probe=70b67b462b) | Apr 03, 2022 |
| ASRock        | H670M-ITX/ax                | Desktop     | [d4dc39b64e](https://linux-hardware.org/?probe=d4dc39b64e) | Apr 03, 2022 |
| MSI           | X58M                        | Desktop     | [7484dce6ce](https://linux-hardware.org/?probe=7484dce6ce) | Apr 03, 2022 |
| Medion        | E6228                       | Notebook    | [c3fadd4b16](https://linux-hardware.org/?probe=c3fadd4b16) | Apr 03, 2022 |
| Packard Be... | M2N-NM                      | Desktop     | [7231602b33](https://linux-hardware.org/?probe=7231602b33) | Apr 03, 2022 |
| ASRock        | H670M-ITX/ax                | Desktop     | [d97f9a02fe](https://linux-hardware.org/?probe=d97f9a02fe) | Apr 03, 2022 |
| Medion        | E7419 MD60827               | Notebook    | [9b5701db0b](https://linux-hardware.org/?probe=9b5701db0b) | Apr 03, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [aea5a553d9](https://linux-hardware.org/?probe=aea5a553d9) | Apr 03, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [4a72f1de5f](https://linux-hardware.org/?probe=4a72f1de5f) | Apr 03, 2022 |
| Acer          | WMCP78M                     | Desktop     | [7c9d2a802f](https://linux-hardware.org/?probe=7c9d2a802f) | Apr 03, 2022 |
| HP            | 1998                        | Desktop     | [4b6628b734](https://linux-hardware.org/?probe=4b6628b734) | Apr 03, 2022 |
| MSI           | MEG X570 ACE                | Desktop     | [62b7931f9b](https://linux-hardware.org/?probe=62b7931f9b) | Apr 03, 2022 |
| Lenovo        | ThinkPad T460 20FMS07000    | Notebook    | [35057588b4](https://linux-hardware.org/?probe=35057588b4) | Apr 03, 2022 |
| Lenovo        | ThinkPad T460 20FMS07000    | Notebook    | [9050980874](https://linux-hardware.org/?probe=9050980874) | Apr 02, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [5dcb0a1847](https://linux-hardware.org/?probe=5dcb0a1847) | Apr 02, 2022 |
| HP            | Laptop 17-bs0xx             | Notebook    | [b7b9288166](https://linux-hardware.org/?probe=b7b9288166) | Apr 02, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [8865aba7b6](https://linux-hardware.org/?probe=8865aba7b6) | Apr 02, 2022 |
| Gigabyte      | MZBSWAP-K4                  | Desktop     | [dfcfb79dcb](https://linux-hardware.org/?probe=dfcfb79dcb) | Apr 02, 2022 |
| Gigabyte      | MZBSWAP-K4                  | Desktop     | [78665d8f57](https://linux-hardware.org/?probe=78665d8f57) | Apr 02, 2022 |
| Unknown       | Unknown                     | Soc         | [229995d834](https://linux-hardware.org/?probe=229995d834) | Apr 02, 2022 |
| Packard Be... | EasyNote LV11HC             | Notebook    | [82fef89dcc](https://linux-hardware.org/?probe=82fef89dcc) | Apr 02, 2022 |
| Lenovo        | ThinkPad E580 20KS0039GE    | Notebook    | [e6ef9c8232](https://linux-hardware.org/?probe=e6ef9c8232) | Apr 02, 2022 |
| Gigabyte      | H97-D3H-CF                  | Desktop     | [e7b9989223](https://linux-hardware.org/?probe=e7b9989223) | Apr 02, 2022 |
| HP            | Elite x2 1012 G1            | Notebook    | [6c5dee9e74](https://linux-hardware.org/?probe=6c5dee9e74) | Apr 02, 2022 |
| ASUSTek       | M5A78L-M LE                 | Desktop     | [2054f135d4](https://linux-hardware.org/?probe=2054f135d4) | Apr 02, 2022 |
| Timi          | TM1612                      | Notebook    | [7eb83bb23a](https://linux-hardware.org/?probe=7eb83bb23a) | Apr 02, 2022 |
| Medion        | E6228                       | Notebook    | [07c511bcb4](https://linux-hardware.org/?probe=07c511bcb4) | Apr 02, 2022 |
| Jumper        | EZbook                      | Notebook    | [82059d364a](https://linux-hardware.org/?probe=82059d364a) | Apr 02, 2022 |
| Jumper        | EZbook                      | Notebook    | [e27bed6542](https://linux-hardware.org/?probe=e27bed6542) | Apr 02, 2022 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [8f74b48f7c](https://linux-hardware.org/?probe=8f74b48f7c) | Apr 02, 2022 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [c80f6bbe22](https://linux-hardware.org/?probe=c80f6bbe22) | Apr 02, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [89f864e1d2](https://linux-hardware.org/?probe=89f864e1d2) | Apr 02, 2022 |
| Dell          | Latitude E6540              | Notebook    | [e087a37f5f](https://linux-hardware.org/?probe=e087a37f5f) | Apr 02, 2022 |
| Acer          | Aspire 5951G                | Notebook    | [845846fc58](https://linux-hardware.org/?probe=845846fc58) | Apr 02, 2022 |
| CSL-Comput... | R Evolve C14i               | Notebook    | [4b2a6fd90c](https://linux-hardware.org/?probe=4b2a6fd90c) | Apr 02, 2022 |
| MSI           | Z77A-GD65                   | Desktop     | [d7e7b28b04](https://linux-hardware.org/?probe=d7e7b28b04) | Apr 02, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [981ddceae1](https://linux-hardware.org/?probe=981ddceae1) | Apr 02, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [b88c7aef34](https://linux-hardware.org/?probe=b88c7aef34) | Apr 02, 2022 |
| Apple         | MacBookAir4,2               | Notebook    | [7fc2cd808d](https://linux-hardware.org/?probe=7fc2cd808d) | Apr 02, 2022 |
| Samsung       | 930QCA                      | Convertible | [d5991ba91f](https://linux-hardware.org/?probe=d5991ba91f) | Apr 02, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [290217f248](https://linux-hardware.org/?probe=290217f248) | Apr 01, 2022 |
| Notebook      | W65_67SZ                    | Notebook    | [1b085791cc](https://linux-hardware.org/?probe=1b085791cc) | Apr 01, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [a47ab656ab](https://linux-hardware.org/?probe=a47ab656ab) | Apr 01, 2022 |
| HP            | 250 G4                      | Notebook    | [cb7cd2ea49](https://linux-hardware.org/?probe=cb7cd2ea49) | Apr 01, 2022 |
| MSI           | MS-7816                     | Notebook    | [5641d3418b](https://linux-hardware.org/?probe=5641d3418b) | Apr 01, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [3d37374fae](https://linux-hardware.org/?probe=3d37374fae) | Apr 01, 2022 |
| Shuttle       | FG41 V20                    | Desktop     | [2db99e0b09](https://linux-hardware.org/?probe=2db99e0b09) | Apr 01, 2022 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | Notebook    | [78ca0e19c4](https://linux-hardware.org/?probe=78ca0e19c4) | Apr 01, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [5fdfbe6b61](https://linux-hardware.org/?probe=5fdfbe6b61) | Apr 01, 2022 |
| ASUSTek       | M4A77TD PRO                 | Desktop     | [3049a1dd96](https://linux-hardware.org/?probe=3049a1dd96) | Apr 01, 2022 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | Notebook    | [1eed2ff87d](https://linux-hardware.org/?probe=1eed2ff87d) | Apr 01, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | Desktop     | [07d499a6f9](https://linux-hardware.org/?probe=07d499a6f9) | Apr 01, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [a799c6c916](https://linux-hardware.org/?probe=a799c6c916) | Apr 01, 2022 |
| TrekStor      | Primetab S11B               | Tablet      | [c98cdfd7c7](https://linux-hardware.org/?probe=c98cdfd7c7) | Apr 01, 2022 |
| Lenovo        | ThinkPad T480s 20L70058G... | Notebook    | [d9fb78563a](https://linux-hardware.org/?probe=d9fb78563a) | Apr 01, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [1b1917729b](https://linux-hardware.org/?probe=1b1917729b) | Apr 01, 2022 |
| Medion        | E7419 MD60827               | Notebook    | [d4fc165219](https://linux-hardware.org/?probe=d4fc165219) | Apr 01, 2022 |
| ASUSTek       | 901                         | Notebook    | [d118ee90d5](https://linux-hardware.org/?probe=d118ee90d5) | Apr 01, 2022 |
| Toshiba       | Satellite C50t-B            | Notebook    | [bc09e75a32](https://linux-hardware.org/?probe=bc09e75a32) | Apr 01, 2022 |
| Fujitsu       | D3223-C1 S26361-D3223-C1    | Desktop     | [f0fdc95810](https://linux-hardware.org/?probe=f0fdc95810) | Apr 01, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [ff7f2845b0](https://linux-hardware.org/?probe=ff7f2845b0) | Apr 01, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [7cd6d9baad](https://linux-hardware.org/?probe=7cd6d9baad) | Apr 01, 2022 |
| Acer          | Nitro AN517-41              | Notebook    | [7bce36b9fa](https://linux-hardware.org/?probe=7bce36b9fa) | Apr 01, 2022 |
| MSI           | MPG Z590 GAMING CARBON W... | Desktop     | [f7946783ea](https://linux-hardware.org/?probe=f7946783ea) | Mar 31, 2022 |
| HP            | EliteBook 8730w             | Notebook    | [caade8e7ff](https://linux-hardware.org/?probe=caade8e7ff) | Mar 31, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [4db8daba6a](https://linux-hardware.org/?probe=4db8daba6a) | Mar 31, 2022 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | Notebook    | [c01344bd43](https://linux-hardware.org/?probe=c01344bd43) | Mar 31, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [b08e7d8589](https://linux-hardware.org/?probe=b08e7d8589) | Mar 31, 2022 |
| ASRock        | X570 Taichi                 | Desktop     | [1247f2f024](https://linux-hardware.org/?probe=1247f2f024) | Mar 31, 2022 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [0330b4bb9e](https://linux-hardware.org/?probe=0330b4bb9e) | Mar 31, 2022 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [45e05e692e](https://linux-hardware.org/?probe=45e05e692e) | Mar 31, 2022 |
| MSI           | GP76 Leopard 10UE           | Notebook    | [a0918b276a](https://linux-hardware.org/?probe=a0918b276a) | Mar 31, 2022 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [cd6ebcba97](https://linux-hardware.org/?probe=cd6ebcba97) | Mar 31, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [a167953088](https://linux-hardware.org/?probe=a167953088) | Mar 31, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [ad4ec3bdab](https://linux-hardware.org/?probe=ad4ec3bdab) | Mar 31, 2022 |
| Unknown       | Unknown                     | Soc         | [0169d940ca](https://linux-hardware.org/?probe=0169d940ca) | Mar 31, 2022 |
| BESSTAR Te... | JB9                         | Desktop     | [ad56d40441](https://linux-hardware.org/?probe=ad56d40441) | Mar 31, 2022 |
| Gigabyte      | H87-HD3                     | Desktop     | [e8f29093f9](https://linux-hardware.org/?probe=e8f29093f9) | Mar 31, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [6c25b53900](https://linux-hardware.org/?probe=6c25b53900) | Mar 31, 2022 |
| Gigabyte      | F2A88XM-DS2                 | Desktop     | [f265f5e3b1](https://linux-hardware.org/?probe=f265f5e3b1) | Mar 31, 2022 |
| Biostar       | X370GT5                     | Desktop     | [efe58d6ab1](https://linux-hardware.org/?probe=efe58d6ab1) | Mar 31, 2022 |
| HP            | ProBook 4340s               | Notebook    | [01f68c1cca](https://linux-hardware.org/?probe=01f68c1cca) | Mar 31, 2022 |
| Gigabyte      | GA-E6010N                   | Desktop     | [0ab26a135d](https://linux-hardware.org/?probe=0ab26a135d) | Mar 31, 2022 |
| Lenovo        | ThinkPad P50 20EQS4QL11     | Notebook    | [3c1ccf405a](https://linux-hardware.org/?probe=3c1ccf405a) | Mar 31, 2022 |
| ASRock        | 960GM-GS3 FX                | Desktop     | [2c9c93fcb5](https://linux-hardware.org/?probe=2c9c93fcb5) | Mar 31, 2022 |
| Schenker      | XMG NEO (M19, RTX 2060)     | Notebook    | [5c85c4efaf](https://linux-hardware.org/?probe=5c85c4efaf) | Mar 31, 2022 |
| ASUSTek       | ProArt B550-CREATOR         | Desktop     | [a33c598546](https://linux-hardware.org/?probe=a33c598546) | Mar 31, 2022 |
| Gigabyte      | H61M-DS2V                   | Desktop     | [830357fbc8](https://linux-hardware.org/?probe=830357fbc8) | Mar 31, 2022 |
| Packard Be... | EasyNote ENTG71BM           | Notebook    | [f236b5007a](https://linux-hardware.org/?probe=f236b5007a) | Mar 31, 2022 |
| HP            | 630                         | Notebook    | [889f8a3ade](https://linux-hardware.org/?probe=889f8a3ade) | Mar 31, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [1cab31778a](https://linux-hardware.org/?probe=1cab31778a) | Mar 30, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [43e45df9f5](https://linux-hardware.org/?probe=43e45df9f5) | Mar 30, 2022 |
| Lenovo        | ThinkPad T460 20FMS03600    | Notebook    | [530a787652](https://linux-hardware.org/?probe=530a787652) | Mar 30, 2022 |
| MSI           | 770-C45                     | Desktop     | [f77be5fea4](https://linux-hardware.org/?probe=f77be5fea4) | Mar 30, 2022 |
| Unknown       | Unknown                     | Soc         | [1b4a3f390d](https://linux-hardware.org/?probe=1b4a3f390d) | Mar 30, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [abacf8ed50](https://linux-hardware.org/?probe=abacf8ed50) | Mar 30, 2022 |
| ASUSTek       | N750JK                      | Notebook    | [64621bf859](https://linux-hardware.org/?probe=64621bf859) | Mar 30, 2022 |
| Rockchip      | RK3318 BOX                  | Soc         | [6098716d3e](https://linux-hardware.org/?probe=6098716d3e) | Mar 30, 2022 |
| Acer          | TravelMate 5720             | Notebook    | [3ce4630eb3](https://linux-hardware.org/?probe=3ce4630eb3) | Mar 30, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [c6726e85ab](https://linux-hardware.org/?probe=c6726e85ab) | Mar 30, 2022 |
| Dell          | 0F642F A00                  | Desktop     | [b3ae697cd6](https://linux-hardware.org/?probe=b3ae697cd6) | Mar 30, 2022 |
| ASUSTek       | P5K                         | Desktop     | [c62991184f](https://linux-hardware.org/?probe=c62991184f) | Mar 30, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [83f5079647](https://linux-hardware.org/?probe=83f5079647) | Mar 30, 2022 |
| Dell          | Latitude E7470              | Notebook    | [cf1faecffc](https://linux-hardware.org/?probe=cf1faecffc) | Mar 30, 2022 |
| Gigabyte      | F2A88XM-DS2                 | Desktop     | [69e5ad3c75](https://linux-hardware.org/?probe=69e5ad3c75) | Mar 30, 2022 |
| ASUSTek       | P50IJ                       | Notebook    | [7b544e4318](https://linux-hardware.org/?probe=7b544e4318) | Mar 30, 2022 |
| Schenker      | VISION 14                   | Notebook    | [f6c59875a1](https://linux-hardware.org/?probe=f6c59875a1) | Mar 30, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [5ef3a5fd60](https://linux-hardware.org/?probe=5ef3a5fd60) | Mar 30, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [99de1a9e9d](https://linux-hardware.org/?probe=99de1a9e9d) | Mar 30, 2022 |
| Lenovo        | G575 4383                   | Notebook    | [e1b18b8402](https://linux-hardware.org/?probe=e1b18b8402) | Mar 30, 2022 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [f21ef43d0f](https://linux-hardware.org/?probe=f21ef43d0f) | Mar 30, 2022 |
| LG Electro... | 16T90P-G.AA78G              | Convertible | [0fed75156c](https://linux-hardware.org/?probe=0fed75156c) | Mar 30, 2022 |
| Pegatron      | IPMSB-GS                    | Desktop     | [57ed5ec512](https://linux-hardware.org/?probe=57ed5ec512) | Mar 30, 2022 |
| Fujitsu Si... | LIFEBOOK E8420              | Notebook    | [1f81c3ef0a](https://linux-hardware.org/?probe=1f81c3ef0a) | Mar 30, 2022 |
| Toshiba       | Satellite C50-A             | Notebook    | [6616cb2c88](https://linux-hardware.org/?probe=6616cb2c88) | Mar 30, 2022 |
| Acer          | Swift SF313-53              | Notebook    | [15d4d13a68](https://linux-hardware.org/?probe=15d4d13a68) | Mar 30, 2022 |
| Lenovo        | Myrtle CRB SDK0J40700 WI... | Desktop     | [078946745f](https://linux-hardware.org/?probe=078946745f) | Mar 30, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | Convertible | [b78407edfa](https://linux-hardware.org/?probe=b78407edfa) | Mar 30, 2022 |
| Acer          | Aspire VN7-792G             | Notebook    | [31da1eb580](https://linux-hardware.org/?probe=31da1eb580) | Mar 30, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | Convertible | [eab41ef6e3](https://linux-hardware.org/?probe=eab41ef6e3) | Mar 30, 2022 |
| Unknown       | Unknown                     | Soc         | [838ae818e8](https://linux-hardware.org/?probe=838ae818e8) | Mar 30, 2022 |
| Apple         | MacBookPro5,2               | Notebook    | [3f0b633075](https://linux-hardware.org/?probe=3f0b633075) | Mar 30, 2022 |
| Lenovo        | ThinkPad W520 42823CG       | Notebook    | [81d5068bf3](https://linux-hardware.org/?probe=81d5068bf3) | Mar 29, 2022 |
| Maita         | NUCCF01                     | Desktop     | [ef888d0be5](https://linux-hardware.org/?probe=ef888d0be5) | Mar 29, 2022 |
| Maita         | NUCCF01                     | Desktop     | [c3c283c0f6](https://linux-hardware.org/?probe=c3c283c0f6) | Mar 29, 2022 |
| Acer          | Aspire ES1-572              | Notebook    | [bf6df72edf](https://linux-hardware.org/?probe=bf6df72edf) | Mar 29, 2022 |
| ASUSTek       | P5K                         | Desktop     | [0ba62d4144](https://linux-hardware.org/?probe=0ba62d4144) | Mar 29, 2022 |
| Acer          | Aspire E5-771               | Notebook    | [74e7884f94](https://linux-hardware.org/?probe=74e7884f94) | Mar 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [7a2f8d09f9](https://linux-hardware.org/?probe=7a2f8d09f9) | Mar 29, 2022 |
| ASUSTek       | ET2700I                     | Desktop     | [8379cf3a4a](https://linux-hardware.org/?probe=8379cf3a4a) | Mar 29, 2022 |
| MSI           | Stealth GS77 12UGS          | Notebook    | [d36f19cf34](https://linux-hardware.org/?probe=d36f19cf34) | Mar 29, 2022 |
| Acer          | Aspire E1-572G              | Notebook    | [3ea1291ab9](https://linux-hardware.org/?probe=3ea1291ab9) | Mar 29, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [de17fecb09](https://linux-hardware.org/?probe=de17fecb09) | Mar 28, 2022 |
| ASUSTek       | A88X-GAMER                  | Desktop     | [8340e366fc](https://linux-hardware.org/?probe=8340e366fc) | Mar 28, 2022 |
| HP            | Pavilion ze2000 (EK813EA... | Notebook    | [fc14123c0f](https://linux-hardware.org/?probe=fc14123c0f) | Mar 28, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [6a14049259](https://linux-hardware.org/?probe=6a14049259) | Mar 28, 2022 |
| Dell          | Latitude 7210 2-in-1        | Tablet      | [9cca062b32](https://linux-hardware.org/?probe=9cca062b32) | Mar 28, 2022 |
| MSI           | MPG Z590 GAMING FORCE       | Desktop     | [bb7fa2ac4b](https://linux-hardware.org/?probe=bb7fa2ac4b) | Mar 28, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [9aa5a3401d](https://linux-hardware.org/?probe=9aa5a3401d) | Mar 28, 2022 |
| Acer          | Predator G9-792             | Notebook    | [79ee722c5d](https://linux-hardware.org/?probe=79ee722c5d) | Mar 28, 2022 |
| Acer          | Predator G9-792             | Notebook    | [ad06ecca1d](https://linux-hardware.org/?probe=ad06ecca1d) | Mar 28, 2022 |
| Acer          | Aspire 5951G                | Notebook    | [46d759867e](https://linux-hardware.org/?probe=46d759867e) | Mar 28, 2022 |
| Radxa         | ROCK Pi 4B                  | Soc         | [9ae359b8f0](https://linux-hardware.org/?probe=9ae359b8f0) | Mar 28, 2022 |
| Acer          | Aspire 5951G                | Notebook    | [b177106df0](https://linux-hardware.org/?probe=b177106df0) | Mar 28, 2022 |
| Radxa         | ROCK Pi 4B                  | Soc         | [a8c2931b5a](https://linux-hardware.org/?probe=a8c2931b5a) | Mar 28, 2022 |
| Lenovo        | G575 4383                   | Notebook    | [7ad8a7f864](https://linux-hardware.org/?probe=7ad8a7f864) | Mar 28, 2022 |
| Acer          | Aspire 5951G                | Notebook    | [beb50b3ce1](https://linux-hardware.org/?probe=beb50b3ce1) | Mar 28, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [0e63a73617](https://linux-hardware.org/?probe=0e63a73617) | Mar 28, 2022 |
| HP            | Laptop                      | Notebook    | [5f35bcfa9d](https://linux-hardware.org/?probe=5f35bcfa9d) | Mar 28, 2022 |
| Toshiba       | Satellite C70-C-1G2         | Notebook    | [034bb894e8](https://linux-hardware.org/?probe=034bb894e8) | Mar 28, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [53cc2f0e19](https://linux-hardware.org/?probe=53cc2f0e19) | Mar 27, 2022 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [cbff113cb3](https://linux-hardware.org/?probe=cbff113cb3) | Mar 27, 2022 |
| ASUSTek       | H81M-R                      | Desktop     | [0d4d2c1358](https://linux-hardware.org/?probe=0d4d2c1358) | Mar 27, 2022 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [a725ee0e42](https://linux-hardware.org/?probe=a725ee0e42) | Mar 27, 2022 |
| ASUSTek       | K52Je                       | Notebook    | [647fc6e655](https://linux-hardware.org/?probe=647fc6e655) | Mar 27, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [a96405351a](https://linux-hardware.org/?probe=a96405351a) | Mar 27, 2022 |
| Dell          | Vostro 2520                 | Notebook    | [3e2f399fd8](https://linux-hardware.org/?probe=3e2f399fd8) | Mar 27, 2022 |
| HP            | 18E7                        | Desktop     | [18decc1420](https://linux-hardware.org/?probe=18decc1420) | Mar 27, 2022 |
| Acer          | Veriton X490G               | Desktop     | [d8283d82c4](https://linux-hardware.org/?probe=d8283d82c4) | Mar 27, 2022 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [11e1d2297b](https://linux-hardware.org/?probe=11e1d2297b) | Mar 27, 2022 |
| ASUSTek       | P5K                         | Desktop     | [6e11e7348c](https://linux-hardware.org/?probe=6e11e7348c) | Mar 27, 2022 |
| Gigabyte      | Q57M-S2H                    | Desktop     | [6f2b606477](https://linux-hardware.org/?probe=6f2b606477) | Mar 27, 2022 |
| Acer          | Predator G9-792             | Notebook    | [4720698441](https://linux-hardware.org/?probe=4720698441) | Mar 27, 2022 |
| Dell          | Latitude 5520               | Notebook    | [ca6e0db25d](https://linux-hardware.org/?probe=ca6e0db25d) | Mar 27, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [3bae64bb6f](https://linux-hardware.org/?probe=3bae64bb6f) | Mar 27, 2022 |
| MSI           | MS-B1711                    | Desktop     | [29b3da3fb7](https://linux-hardware.org/?probe=29b3da3fb7) | Mar 27, 2022 |
| Toshiba       | Satellite C70-C-1G2         | Notebook    | [52cd10acc4](https://linux-hardware.org/?probe=52cd10acc4) | Mar 27, 2022 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [09b7586491](https://linux-hardware.org/?probe=09b7586491) | Mar 27, 2022 |
| Acer          | Aspire E5-771               | Notebook    | [2a9d489c50](https://linux-hardware.org/?probe=2a9d489c50) | Mar 27, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [8252c302e2](https://linux-hardware.org/?probe=8252c302e2) | Mar 27, 2022 |
| AWOW          | TX33                        | Notebook    | [f47f001038](https://linux-hardware.org/?probe=f47f001038) | Mar 26, 2022 |
| Fujitsu       | LIFEBOOK E746               | Notebook    | [dc5e0a376b](https://linux-hardware.org/?probe=dc5e0a376b) | Mar 26, 2022 |
| HP            | 0A98h                       | Desktop     | [4b9c0556af](https://linux-hardware.org/?probe=4b9c0556af) | Mar 26, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [64e505d8d7](https://linux-hardware.org/?probe=64e505d8d7) | Mar 26, 2022 |
| Sony          | VGN-FW21E                   | Notebook    | [77c49f23fd](https://linux-hardware.org/?probe=77c49f23fd) | Mar 26, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | Desktop     | [b31460778c](https://linux-hardware.org/?probe=b31460778c) | Mar 26, 2022 |
| MSI           | B450 GAMING PLUS            | Desktop     | [31106ba339](https://linux-hardware.org/?probe=31106ba339) | Mar 26, 2022 |
| Intel         | NUC10i3FNB M38070-307       | Mini pc     | [92b85d6fa4](https://linux-hardware.org/?probe=92b85d6fa4) | Mar 26, 2022 |
| ASRock        | 970 Pro3                    | Desktop     | [1b877e6f7a](https://linux-hardware.org/?probe=1b877e6f7a) | Mar 26, 2022 |
| ASUSTek       | N750JK                      | Notebook    | [127ced7c7f](https://linux-hardware.org/?probe=127ced7c7f) | Mar 26, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [8341d3f6f9](https://linux-hardware.org/?probe=8341d3f6f9) | Mar 26, 2022 |
| HP            | OMEN by Laptop              | Notebook    | [bca24e362a](https://linux-hardware.org/?probe=bca24e362a) | Mar 26, 2022 |
| ASUSTek       | N750JK                      | Notebook    | [aebfecf42d](https://linux-hardware.org/?probe=aebfecf42d) | Mar 26, 2022 |
| HP            | OMEN by Laptop              | Notebook    | [1cd6d454ed](https://linux-hardware.org/?probe=1cd6d454ed) | Mar 26, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [02a3f1feaf](https://linux-hardware.org/?probe=02a3f1feaf) | Mar 26, 2022 |
| Toshiba       | Satellite C70D-A            | Notebook    | [c8b872d005](https://linux-hardware.org/?probe=c8b872d005) | Mar 26, 2022 |
| HP            | ProBook 6470b               | Notebook    | [02dd6d658c](https://linux-hardware.org/?probe=02dd6d658c) | Mar 26, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [3e12cb02f8](https://linux-hardware.org/?probe=3e12cb02f8) | Mar 26, 2022 |
| ASUSTek       | P50IJ                       | Notebook    | [4f3b835a1e](https://linux-hardware.org/?probe=4f3b835a1e) | Mar 26, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [c8a76eb9ae](https://linux-hardware.org/?probe=c8a76eb9ae) | Mar 25, 2022 |
| ASRock        | H110M-HDS                   | Desktop     | [4d571e07cc](https://linux-hardware.org/?probe=4d571e07cc) | Mar 25, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [243d5352ef](https://linux-hardware.org/?probe=243d5352ef) | Mar 25, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [88c6d60a0b](https://linux-hardware.org/?probe=88c6d60a0b) | Mar 25, 2022 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [27099d48f9](https://linux-hardware.org/?probe=27099d48f9) | Mar 25, 2022 |
| HP            | ProBook 6460b               | Notebook    | [fcba632427](https://linux-hardware.org/?probe=fcba632427) | Mar 25, 2022 |
| HP            | ProBook 6460b               | Notebook    | [c301eab574](https://linux-hardware.org/?probe=c301eab574) | Mar 25, 2022 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [f0a08eb35b](https://linux-hardware.org/?probe=f0a08eb35b) | Mar 25, 2022 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | Desktop     | [d975f1b581](https://linux-hardware.org/?probe=d975f1b581) | Mar 25, 2022 |
| MSI           | B550M PRO-VDH               | Desktop     | [acd7be917a](https://linux-hardware.org/?probe=acd7be917a) | Mar 25, 2022 |
| ASUSTek       | P5G41-M LX2/GB/LPT          | Desktop     | [38f567bb43](https://linux-hardware.org/?probe=38f567bb43) | Mar 25, 2022 |
| HP            | 843E A01                    | Desktop     | [8b6e63fbd4](https://linux-hardware.org/?probe=8b6e63fbd4) | Mar 25, 2022 |
| HP            | 630                         | Notebook    | [dcad0005cb](https://linux-hardware.org/?probe=dcad0005cb) | Mar 25, 2022 |
| Teclast       | F6                          | Notebook    | [d4e2f31492](https://linux-hardware.org/?probe=d4e2f31492) | Mar 25, 2022 |
| Lenovo        | ThinkPad Edge E545 20B20... | Notebook    | [2a5e23d326](https://linux-hardware.org/?probe=2a5e23d326) | Mar 25, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [5340d6cada](https://linux-hardware.org/?probe=5340d6cada) | Mar 25, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [eef252e4f2](https://linux-hardware.org/?probe=eef252e4f2) | Mar 25, 2022 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [0579061135](https://linux-hardware.org/?probe=0579061135) | Mar 25, 2022 |
| MSI           | GP76 Leopard 10UE           | Notebook    | [d012a7b505](https://linux-hardware.org/?probe=d012a7b505) | Mar 25, 2022 |
| TrekStor      | Primetab T13B               | Tablet      | [3c63b88471](https://linux-hardware.org/?probe=3c63b88471) | Mar 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [57c51a1a1c](https://linux-hardware.org/?probe=57c51a1a1c) | Mar 25, 2022 |
| TrekStor      | Primetab T13B               | Tablet      | [c3cd38fd2d](https://linux-hardware.org/?probe=c3cd38fd2d) | Mar 25, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [dfe9201f95](https://linux-hardware.org/?probe=dfe9201f95) | Mar 24, 2022 |
| ASRock        | B550 Taichi                 | Desktop     | [2c71d397fd](https://linux-hardware.org/?probe=2c71d397fd) | Mar 24, 2022 |
| HP            | 212B                        | Desktop     | [b7c0d8bedf](https://linux-hardware.org/?probe=b7c0d8bedf) | Mar 24, 2022 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | Desktop     | [80fa34cf94](https://linux-hardware.org/?probe=80fa34cf94) | Mar 24, 2022 |
| Gigabyte      | H55-UD3H                    | Desktop     | [1cf4bf2cfd](https://linux-hardware.org/?probe=1cf4bf2cfd) | Mar 24, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [5170bfb594](https://linux-hardware.org/?probe=5170bfb594) | Mar 24, 2022 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | Notebook    | [9fc0486da6](https://linux-hardware.org/?probe=9fc0486da6) | Mar 24, 2022 |
| ASUSTek       | T103HAF                     | Tablet      | [c42d11083f](https://linux-hardware.org/?probe=c42d11083f) | Mar 24, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [853a141588](https://linux-hardware.org/?probe=853a141588) | Mar 24, 2022 |
| Dell          | Latitude E7450              | Notebook    | [3d59fe35f1](https://linux-hardware.org/?probe=3d59fe35f1) | Mar 24, 2022 |
| Gigabyte      | EX58-UD5                    | Desktop     | [beb844045e](https://linux-hardware.org/?probe=beb844045e) | Mar 24, 2022 |
| Notebook      | NL5xRU                      | Notebook    | [2766f55bb8](https://linux-hardware.org/?probe=2766f55bb8) | Mar 24, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [346857be22](https://linux-hardware.org/?probe=346857be22) | Mar 24, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [bb1d6b4aae](https://linux-hardware.org/?probe=bb1d6b4aae) | Mar 24, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [689868473e](https://linux-hardware.org/?probe=689868473e) | Mar 24, 2022 |
| TrekStor      | Primetab T13B               | Tablet      | [b48b1f0de3](https://linux-hardware.org/?probe=b48b1f0de3) | Mar 24, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [b9aec6129a](https://linux-hardware.org/?probe=b9aec6129a) | Mar 23, 2022 |
| TrekStor      | Primetab T13B               | Tablet      | [43e7eab371](https://linux-hardware.org/?probe=43e7eab371) | Mar 23, 2022 |
| MSI           | Alpha 15 A3DDK              | Notebook    | [ba7e272251](https://linux-hardware.org/?probe=ba7e272251) | Mar 23, 2022 |
| AZW           | SER V01                     | Mini pc     | [57ee00cdcc](https://linux-hardware.org/?probe=57ee00cdcc) | Mar 23, 2022 |
| Dell          | 0HN7XN A01                  | Desktop     | [53f17c5666](https://linux-hardware.org/?probe=53f17c5666) | Mar 23, 2022 |
| HP            | Notebook                    | Notebook    | [7c948bb767](https://linux-hardware.org/?probe=7c948bb767) | Mar 23, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [7c4be75815](https://linux-hardware.org/?probe=7c4be75815) | Mar 23, 2022 |
| Gigabyte      | B660 GAMING X DDR4          | Desktop     | [1b81b37d97](https://linux-hardware.org/?probe=1b81b37d97) | Mar 23, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [bd0e0e448b](https://linux-hardware.org/?probe=bd0e0e448b) | Mar 23, 2022 |
| Samsung       | 950QDB                      | Convertible | [97642a3dca](https://linux-hardware.org/?probe=97642a3dca) | Mar 23, 2022 |
| Gigabyte      | H97-HD3                     | Desktop     | [33fa2b3eff](https://linux-hardware.org/?probe=33fa2b3eff) | Mar 23, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [ccfdbc46a0](https://linux-hardware.org/?probe=ccfdbc46a0) | Mar 23, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [3ec2149915](https://linux-hardware.org/?probe=3ec2149915) | Mar 23, 2022 |
| HP            | 1589                        | Desktop     | [8c1f30bb6f](https://linux-hardware.org/?probe=8c1f30bb6f) | Mar 23, 2022 |
| LG Electro... | 16T90P-G.AA78G              | Convertible | [98e1e7c871](https://linux-hardware.org/?probe=98e1e7c871) | Mar 23, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [81ba20b0d1](https://linux-hardware.org/?probe=81ba20b0d1) | Mar 23, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [388e425010](https://linux-hardware.org/?probe=388e425010) | Mar 23, 2022 |
| HP            | Elite x2 1012 G1            | Notebook    | [d8c3d46ad9](https://linux-hardware.org/?probe=d8c3d46ad9) | Mar 23, 2022 |
| Apple         | Mac-F2218EC8                | All in one  | [eed3af8969](https://linux-hardware.org/?probe=eed3af8969) | Mar 23, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [c5a0300da9](https://linux-hardware.org/?probe=c5a0300da9) | Mar 23, 2022 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | Notebook    | [6285900fd7](https://linux-hardware.org/?probe=6285900fd7) | Mar 22, 2022 |
| HUAWEI        | DRC-WXX                     | Tablet      | [cbac732b10](https://linux-hardware.org/?probe=cbac732b10) | Mar 22, 2022 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [21e6b2c7c3](https://linux-hardware.org/?probe=21e6b2c7c3) | Mar 22, 2022 |
| MSI           | CR643                       | Notebook    | [24e9c1fe40](https://linux-hardware.org/?probe=24e9c1fe40) | Mar 22, 2022 |
| HUAWEI        | DRC-WXX                     | Tablet      | [ba87d92608](https://linux-hardware.org/?probe=ba87d92608) | Mar 22, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [5298f9dcc9](https://linux-hardware.org/?probe=5298f9dcc9) | Mar 22, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [d24fcefe24](https://linux-hardware.org/?probe=d24fcefe24) | Mar 22, 2022 |
| Acer          | Aspire A515-51              | Notebook    | [d4a6d3de3e](https://linux-hardware.org/?probe=d4a6d3de3e) | Mar 22, 2022 |
| HP            | 1589                        | Desktop     | [a97fa22164](https://linux-hardware.org/?probe=a97fa22164) | Mar 22, 2022 |
| NU591         | 1.0                         | Desktop     | [a2e3eb7d41](https://linux-hardware.org/?probe=a2e3eb7d41) | Mar 22, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [1e89cedec2](https://linux-hardware.org/?probe=1e89cedec2) | Mar 22, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [dec65a823a](https://linux-hardware.org/?probe=dec65a823a) | Mar 22, 2022 |
| MSI           | GE70 2PE                    | Notebook    | [67066e47d3](https://linux-hardware.org/?probe=67066e47d3) | Mar 22, 2022 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [50fd3adf1a](https://linux-hardware.org/?probe=50fd3adf1a) | Mar 21, 2022 |
| HP            | 250 G3                      | Notebook    | [78f15f6ada](https://linux-hardware.org/?probe=78f15f6ada) | Mar 21, 2022 |
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [5cc0fe0f1e](https://linux-hardware.org/?probe=5cc0fe0f1e) | Mar 21, 2022 |
| MSI           | E350IA-E45                  | Desktop     | [84a19b6203](https://linux-hardware.org/?probe=84a19b6203) | Mar 21, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [4492e433cd](https://linux-hardware.org/?probe=4492e433cd) | Mar 21, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [366258c1f2](https://linux-hardware.org/?probe=366258c1f2) | Mar 21, 2022 |
| LincPlus      | LINNCPLUS P1                | Notebook    | [ae221ac3a7](https://linux-hardware.org/?probe=ae221ac3a7) | Mar 21, 2022 |
| Lenovo        | ThinkPad X131e 336838U      | Notebook    | [6f78ab8921](https://linux-hardware.org/?probe=6f78ab8921) | Mar 21, 2022 |
| Supermicro    | C2SBC-Q                     | Desktop     | [338275254e](https://linux-hardware.org/?probe=338275254e) | Mar 21, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [b033cd1c85](https://linux-hardware.org/?probe=b033cd1c85) | Mar 21, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [8ffacf54c4](https://linux-hardware.org/?probe=8ffacf54c4) | Mar 21, 2022 |
| Lenovo        | ThinkPad L470 20J4003WGE    | Notebook    | [62b1219002](https://linux-hardware.org/?probe=62b1219002) | Mar 21, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [f8561c65dc](https://linux-hardware.org/?probe=f8561c65dc) | Mar 21, 2022 |
| Gigabyte      | Z490 VISION D               | Desktop     | [da9773a25d](https://linux-hardware.org/?probe=da9773a25d) | Mar 21, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [feb07b5f78](https://linux-hardware.org/?probe=feb07b5f78) | Mar 21, 2022 |
| Lenovo        | 102F SDK0J40697 WIN 3305... | Desktop     | [adce0625d3](https://linux-hardware.org/?probe=adce0625d3) | Mar 20, 2022 |
| Dell          | 0XJ8C4 A00                  | Desktop     | [2b010e4e7c](https://linux-hardware.org/?probe=2b010e4e7c) | Mar 20, 2022 |
| HUAWEI        | DRC-WXX                     | Tablet      | [927252e84e](https://linux-hardware.org/?probe=927252e84e) | Mar 20, 2022 |
| HUAWEI        | DRC-WXX                     | Tablet      | [be2a3fd33b](https://linux-hardware.org/?probe=be2a3fd33b) | Mar 20, 2022 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [d4a63f4b81](https://linux-hardware.org/?probe=d4a63f4b81) | Mar 20, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [622384c18e](https://linux-hardware.org/?probe=622384c18e) | Mar 20, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [78df63a35f](https://linux-hardware.org/?probe=78df63a35f) | Mar 20, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [7504eeaaa1](https://linux-hardware.org/?probe=7504eeaaa1) | Mar 20, 2022 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [a4c3638822](https://linux-hardware.org/?probe=a4c3638822) | Mar 20, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [906f450dd5](https://linux-hardware.org/?probe=906f450dd5) | Mar 20, 2022 |
| MSI           | B450M GAMING PLUS           | Desktop     | [9f0ed452aa](https://linux-hardware.org/?probe=9f0ed452aa) | Mar 20, 2022 |
| Lenovo        | B560 43308VG                | Notebook    | [f1e07e69d0](https://linux-hardware.org/?probe=f1e07e69d0) | Mar 20, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [d4c7ecbc5e](https://linux-hardware.org/?probe=d4c7ecbc5e) | Mar 20, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [e2d7611daa](https://linux-hardware.org/?probe=e2d7611daa) | Mar 20, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [4e555a8efa](https://linux-hardware.org/?probe=4e555a8efa) | Mar 20, 2022 |
| ASUSTek       | G750JH                      | Notebook    | [18441af78a](https://linux-hardware.org/?probe=18441af78a) | Mar 20, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [f3ed30e261](https://linux-hardware.org/?probe=f3ed30e261) | Mar 20, 2022 |
| Unknown       | Unknown                     | Desktop     | [4f882f4865](https://linux-hardware.org/?probe=4f882f4865) | Mar 20, 2022 |
| Dell          | Precision M4800             | Notebook    | [71dd646f94](https://linux-hardware.org/?probe=71dd646f94) | Mar 20, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [949cc3d3c4](https://linux-hardware.org/?probe=949cc3d3c4) | Mar 20, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [cd26d78db2](https://linux-hardware.org/?probe=cd26d78db2) | Mar 20, 2022 |
| Framework     | Laptop                      | Notebook    | [b8fcafa943](https://linux-hardware.org/?probe=b8fcafa943) | Mar 20, 2022 |
| Lenovo        | ThinkPad Edge E330 33544... | Notebook    | [f7a309abe4](https://linux-hardware.org/?probe=f7a309abe4) | Mar 20, 2022 |
| HP            | 8158 A01                    | Mini pc     | [3ba669d072](https://linux-hardware.org/?probe=3ba669d072) | Mar 20, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [b3c770fb69](https://linux-hardware.org/?probe=b3c770fb69) | Mar 19, 2022 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [ae9d2db004](https://linux-hardware.org/?probe=ae9d2db004) | Mar 19, 2022 |
| Dell          | Latitude E6400              | Notebook    | [a4e3e37f01](https://linux-hardware.org/?probe=a4e3e37f01) | Mar 19, 2022 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [9ad4cf0954](https://linux-hardware.org/?probe=9ad4cf0954) | Mar 19, 2022 |
| ASUSTek       | 1001PXD                     | Notebook    | [dada1a7622](https://linux-hardware.org/?probe=dada1a7622) | Mar 19, 2022 |
| Gigabyte      | B450M GAMING                | Desktop     | [9cc0fc6cd0](https://linux-hardware.org/?probe=9cc0fc6cd0) | Mar 19, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [b1a437de4c](https://linux-hardware.org/?probe=b1a437de4c) | Mar 19, 2022 |
| TUXEDO        | N8xEJEK                     | Notebook    | [1201e9ffc3](https://linux-hardware.org/?probe=1201e9ffc3) | Mar 19, 2022 |
| Toshiba       | Satellite C70-C-1G2         | Notebook    | [ebd5bb48d0](https://linux-hardware.org/?probe=ebd5bb48d0) | Mar 19, 2022 |
| Toshiba       | Satellite P500              | Notebook    | [7ea81d88f5](https://linux-hardware.org/?probe=7ea81d88f5) | Mar 19, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [b77a3343c9](https://linux-hardware.org/?probe=b77a3343c9) | Mar 19, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [a763963402](https://linux-hardware.org/?probe=a763963402) | Mar 19, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [a129b881b0](https://linux-hardware.org/?probe=a129b881b0) | Mar 19, 2022 |
| Unknown       | Apple MacBook Pro (13-in... | Notebook    | [5ec586f8e5](https://linux-hardware.org/?probe=5ec586f8e5) | Mar 19, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [6004782573](https://linux-hardware.org/?probe=6004782573) | Mar 19, 2022 |
| Acer          | Aspire A517-52G             | Notebook    | [6c8231e47d](https://linux-hardware.org/?probe=6c8231e47d) | Mar 19, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [b71110144d](https://linux-hardware.org/?probe=b71110144d) | Mar 19, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [0bdc39720e](https://linux-hardware.org/?probe=0bdc39720e) | Mar 19, 2022 |
| ASUSTek       | P4P800                      | Desktop     | [0cb6a89491](https://linux-hardware.org/?probe=0cb6a89491) | Mar 19, 2022 |
| Samsung       | R509                        | Notebook    | [f557f45389](https://linux-hardware.org/?probe=f557f45389) | Mar 19, 2022 |
| Lenovo        | ThinkPad T495 20NK000MGE    | Notebook    | [fac11ffb8c](https://linux-hardware.org/?probe=fac11ffb8c) | Mar 19, 2022 |
| Samsung       | N150/N210/N220              | Notebook    | [7f8d86ea0e](https://linux-hardware.org/?probe=7f8d86ea0e) | Mar 19, 2022 |
| Acer          | Aspire VN7-572G             | Notebook    | [8e241919a3](https://linux-hardware.org/?probe=8e241919a3) | Mar 18, 2022 |
| Dell          | 08WKV3 A00                  | Desktop     | [147bdbc26d](https://linux-hardware.org/?probe=147bdbc26d) | Mar 18, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [d581be232a](https://linux-hardware.org/?probe=d581be232a) | Mar 18, 2022 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [0c7c91a687](https://linux-hardware.org/?probe=0c7c91a687) | Mar 18, 2022 |
| ASUSTek       | ZenBook UX325SA_UM325SA     | Notebook    | [05c0be34be](https://linux-hardware.org/?probe=05c0be34be) | Mar 18, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [3467378e7f](https://linux-hardware.org/?probe=3467378e7f) | Mar 18, 2022 |
| Panasonic     | FZ-M1CC-51BE                | Notebook    | [94e014ee40](https://linux-hardware.org/?probe=94e014ee40) | Mar 18, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [3de3cfea52](https://linux-hardware.org/?probe=3de3cfea52) | Mar 18, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [3f5738effb](https://linux-hardware.org/?probe=3f5738effb) | Mar 18, 2022 |
| ASRock        | H570M Pro4                  | Desktop     | [b04e0c4c1c](https://linux-hardware.org/?probe=b04e0c4c1c) | Mar 18, 2022 |
| Lenovo        | IdeaPad S340-15IML 81NA     | Notebook    | [f61d2bef93](https://linux-hardware.org/?probe=f61d2bef93) | Mar 18, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [6a2f913bcf](https://linux-hardware.org/?probe=6a2f913bcf) | Mar 18, 2022 |
| Fujitsu       | LIFEBOOK A3510              | Notebook    | [2072cd9c30](https://linux-hardware.org/?probe=2072cd9c30) | Mar 18, 2022 |
| Medion        | Erazer X7843 MD99996        | Notebook    | [5b02a95d5d](https://linux-hardware.org/?probe=5b02a95d5d) | Mar 18, 2022 |
| Lenovo        | ThinkPad P53 20QN000HGE     | Notebook    | [db71f4d011](https://linux-hardware.org/?probe=db71f4d011) | Mar 18, 2022 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [3c656a76fc](https://linux-hardware.org/?probe=3c656a76fc) | Mar 18, 2022 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [8b31578713](https://linux-hardware.org/?probe=8b31578713) | Mar 18, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [a3b5b7c37e](https://linux-hardware.org/?probe=a3b5b7c37e) | Mar 18, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [5d2c6c0279](https://linux-hardware.org/?probe=5d2c6c0279) | Mar 18, 2022 |
| ASRock        | Z87 Pro4                    | Desktop     | [7c46cc65dc](https://linux-hardware.org/?probe=7c46cc65dc) | Mar 18, 2022 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [ebe47e4312](https://linux-hardware.org/?probe=ebe47e4312) | Mar 17, 2022 |
| Toshiba       | Satellite C70D-B            | Notebook    | [461d8aa18b](https://linux-hardware.org/?probe=461d8aa18b) | Mar 17, 2022 |
| Medion        | TJ4125                      | Desktop     | [d8535f37cc](https://linux-hardware.org/?probe=d8535f37cc) | Mar 17, 2022 |
| Fujitsu       | LIFEBOOK U748               | Notebook    | [7451bcb3ef](https://linux-hardware.org/?probe=7451bcb3ef) | Mar 17, 2022 |
| Dell          | Latitude E6520              | Notebook    | [50f5e434e5](https://linux-hardware.org/?probe=50f5e434e5) | Mar 17, 2022 |
| Packard Be... | EasyNote TM85               | Notebook    | [ec7dd9aba3](https://linux-hardware.org/?probe=ec7dd9aba3) | Mar 17, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [b68926de8f](https://linux-hardware.org/?probe=b68926de8f) | Mar 17, 2022 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [d75cb4d8c6](https://linux-hardware.org/?probe=d75cb4d8c6) | Mar 17, 2022 |
| Fujitsu Si... | D2750-A2 S26361-D2750-A2    | Desktop     | [0a880e2e5c](https://linux-hardware.org/?probe=0a880e2e5c) | Mar 17, 2022 |
| MSI           | GE70 2PE                    | Notebook    | [f1223c0781](https://linux-hardware.org/?probe=f1223c0781) | Mar 17, 2022 |
| Lenovo        | 1046 NO DPK                 | Desktop     | [561b1c3324](https://linux-hardware.org/?probe=561b1c3324) | Mar 17, 2022 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [1268effe7d](https://linux-hardware.org/?probe=1268effe7d) | Mar 17, 2022 |
| ASRock        | H510M-HVS R2.0              | Desktop     | [0af153934b](https://linux-hardware.org/?probe=0af153934b) | Mar 17, 2022 |
| ASRock        | H510M-HVS R2.0              | Desktop     | [2071129adb](https://linux-hardware.org/?probe=2071129adb) | Mar 17, 2022 |
| MSI           | H61I-E35 V2/W8              | Desktop     | [172c4ac7f6](https://linux-hardware.org/?probe=172c4ac7f6) | Mar 17, 2022 |
| ASUSTek       | PRIME B460-PLUS             | Desktop     | [c0db7c9966](https://linux-hardware.org/?probe=c0db7c9966) | Mar 17, 2022 |
| Lenovo        | MIIX 2 10 20359             | Tablet      | [212388e78b](https://linux-hardware.org/?probe=212388e78b) | Mar 17, 2022 |
| HP            | ENVY 15                     | Notebook    | [dedaac11a1](https://linux-hardware.org/?probe=dedaac11a1) | Mar 17, 2022 |
| Supermicro    | X11SDV-4C-TP8F              | Server      | [5e05b6a115](https://linux-hardware.org/?probe=5e05b6a115) | Mar 17, 2022 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [3ced3829f5](https://linux-hardware.org/?probe=3ced3829f5) | Mar 17, 2022 |
| Supermicro    | X11SDV-4C-TP8F              | Server      | [f38b55e778](https://linux-hardware.org/?probe=f38b55e778) | Mar 17, 2022 |
| Lenovo        | ThinkPad T570 20HAS0QB00    | Notebook    | [b5b110b57d](https://linux-hardware.org/?probe=b5b110b57d) | Mar 17, 2022 |
| MSI           | GE70 2PE                    | Notebook    | [f0cd55f2b2](https://linux-hardware.org/?probe=f0cd55f2b2) | Mar 17, 2022 |
| ASUSTek       | P6X58D-E                    | Desktop     | [613580cf62](https://linux-hardware.org/?probe=613580cf62) | Mar 17, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [d62422fe16](https://linux-hardware.org/?probe=d62422fe16) | Mar 17, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [d0a87aedef](https://linux-hardware.org/?probe=d0a87aedef) | Mar 16, 2022 |
| HP            | 1790                        | Desktop     | [4dbf4f5f70](https://linux-hardware.org/?probe=4dbf4f5f70) | Mar 16, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [d2cf96d262](https://linux-hardware.org/?probe=d2cf96d262) | Mar 16, 2022 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [f2d0951af4](https://linux-hardware.org/?probe=f2d0951af4) | Mar 16, 2022 |
| Lenovo        | Larne CRB 31900058 STD      | All in one  | [ce45df58c2](https://linux-hardware.org/?probe=ce45df58c2) | Mar 16, 2022 |
| Lenovo        | ThinkPad X230 23331D9       | Notebook    | [6edcc3117e](https://linux-hardware.org/?probe=6edcc3117e) | Mar 16, 2022 |
| ASUSTek       | TUF X299 MARK 2             | Desktop     | [651e0fb5eb](https://linux-hardware.org/?probe=651e0fb5eb) | Mar 16, 2022 |
| ASUSTek       | Z87-A                       | Desktop     | [b671affabe](https://linux-hardware.org/?probe=b671affabe) | Mar 16, 2022 |
| Supermicro    | X11DPU                      | Server      | [b285661c3b](https://linux-hardware.org/?probe=b285661c3b) | Mar 16, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [67e6e7097c](https://linux-hardware.org/?probe=67e6e7097c) | Mar 16, 2022 |
| HP            | ProBook 430 G2              | Notebook    | [e2ad81141c](https://linux-hardware.org/?probe=e2ad81141c) | Mar 16, 2022 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | Desktop     | [c553d7cb4c](https://linux-hardware.org/?probe=c553d7cb4c) | Mar 16, 2022 |
| ASUSTek       | X756UQK                     | Notebook    | [f7ba1c3708](https://linux-hardware.org/?probe=f7ba1c3708) | Mar 16, 2022 |
| MSI           | B75MA-P45                   | Desktop     | [f617b8e30b](https://linux-hardware.org/?probe=f617b8e30b) | Mar 16, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [ca405b99d5](https://linux-hardware.org/?probe=ca405b99d5) | Mar 16, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [fe21b2c644](https://linux-hardware.org/?probe=fe21b2c644) | Mar 15, 2022 |
| Sony          | VGN-FZ21M                   | Notebook    | [9a1245c454](https://linux-hardware.org/?probe=9a1245c454) | Mar 15, 2022 |
| Sony          | VGN-FW21E                   | Notebook    | [1dbc74cf43](https://linux-hardware.org/?probe=1dbc74cf43) | Mar 15, 2022 |
| LincPlus      | LINNCPLUS P1                | Notebook    | [7ae63f253a](https://linux-hardware.org/?probe=7ae63f253a) | Mar 15, 2022 |
| Dell          | Latitude E6510              | Notebook    | [e7e17cfe4e](https://linux-hardware.org/?probe=e7e17cfe4e) | Mar 15, 2022 |
| Dell          | Latitude E6510              | Notebook    | [0b6a814b38](https://linux-hardware.org/?probe=0b6a814b38) | Mar 15, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [0927f69114](https://linux-hardware.org/?probe=0927f69114) | Mar 15, 2022 |
| ASUSTek       | P5KPL-AM                    | Desktop     | [4fc92e9a16](https://linux-hardware.org/?probe=4fc92e9a16) | Mar 15, 2022 |
| Lenovo        | G505 20240                  | Notebook    | [c21e84e1a7](https://linux-hardware.org/?probe=c21e84e1a7) | Mar 15, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [44175a7ff8](https://linux-hardware.org/?probe=44175a7ff8) | Mar 15, 2022 |
| Panasonic     | CF-52PFN820G                | Notebook    | [515d0d5c5b](https://linux-hardware.org/?probe=515d0d5c5b) | Mar 15, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [a4dd59149a](https://linux-hardware.org/?probe=a4dd59149a) | Mar 15, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [a9b38043c8](https://linux-hardware.org/?probe=a9b38043c8) | Mar 14, 2022 |
| AXDIA Inte... | MYBOOK 14 PRO               | Notebook    | [89baa8a149](https://linux-hardware.org/?probe=89baa8a149) | Mar 14, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [4728b42945](https://linux-hardware.org/?probe=4728b42945) | Mar 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [373fa69bd1](https://linux-hardware.org/?probe=373fa69bd1) | Mar 14, 2022 |
| Acer          | TravelMate 5720             | Notebook    | [5c3860eaa0](https://linux-hardware.org/?probe=5c3860eaa0) | Mar 14, 2022 |
| Acer          | Aspire VN7-572G             | Notebook    | [dc759490e1](https://linux-hardware.org/?probe=dc759490e1) | Mar 14, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [63ea3e99c5](https://linux-hardware.org/?probe=63ea3e99c5) | Mar 14, 2022 |
| ASUSTek       | A55BM-E                     | Desktop     | [7bbbcc53c1](https://linux-hardware.org/?probe=7bbbcc53c1) | Mar 14, 2022 |
| ASUSTek       | PRIME J4005I-C              | Desktop     | [707cb5ce3b](https://linux-hardware.org/?probe=707cb5ce3b) | Mar 14, 2022 |
| Medion        | E7416T MD99377              | Notebook    | [8ea102c9c4](https://linux-hardware.org/?probe=8ea102c9c4) | Mar 14, 2022 |
| Acer          | Extensa 5630                | Notebook    | [32cab1f9fc](https://linux-hardware.org/?probe=32cab1f9fc) | Mar 14, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [35fed967dd](https://linux-hardware.org/?probe=35fed967dd) | Mar 14, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [03e078e598](https://linux-hardware.org/?probe=03e078e598) | Mar 14, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [917b5794e9](https://linux-hardware.org/?probe=917b5794e9) | Mar 14, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [7dd9865dc1](https://linux-hardware.org/?probe=7dd9865dc1) | Mar 14, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [911881e47f](https://linux-hardware.org/?probe=911881e47f) | Mar 14, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [d555e645ce](https://linux-hardware.org/?probe=d555e645ce) | Mar 14, 2022 |
| HP            | Pavilion Laptop 14-bf1xx    | Notebook    | [35937c6572](https://linux-hardware.org/?probe=35937c6572) | Mar 14, 2022 |
| MSI           | X470 GAMING PLUS            | Desktop     | [45b54744d3](https://linux-hardware.org/?probe=45b54744d3) | Mar 13, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [3a5b71395a](https://linux-hardware.org/?probe=3a5b71395a) | Mar 13, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [8cfd0e9795](https://linux-hardware.org/?probe=8cfd0e9795) | Mar 13, 2022 |
| AOpen         | D1009 A1A4                  | Desktop     | [a7375d4581](https://linux-hardware.org/?probe=a7375d4581) | Mar 13, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [6645577bc5](https://linux-hardware.org/?probe=6645577bc5) | Mar 13, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | Notebook    | [08525a320d](https://linux-hardware.org/?probe=08525a320d) | Mar 13, 2022 |
| MSI           | Z87 MPOWER                  | Desktop     | [8010ef8dd6](https://linux-hardware.org/?probe=8010ef8dd6) | Mar 13, 2022 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [ee1dd1170b](https://linux-hardware.org/?probe=ee1dd1170b) | Mar 13, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [467c7871eb](https://linux-hardware.org/?probe=467c7871eb) | Mar 13, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [b31d818efe](https://linux-hardware.org/?probe=b31d818efe) | Mar 13, 2022 |
| ASUSTek       | F2A85-M                     | Desktop     | [36d17e4fdb](https://linux-hardware.org/?probe=36d17e4fdb) | Mar 13, 2022 |
| Lenovo        | ThinkPad X390 Yoga 20NN0... | Convertible | [180f57f283](https://linux-hardware.org/?probe=180f57f283) | Mar 13, 2022 |
| ASUSTek       | F2A85-M                     | Desktop     | [453d0816b3](https://linux-hardware.org/?probe=453d0816b3) | Mar 13, 2022 |
| ASRock        | H61 Pro BTC                 | Desktop     | [43528c8a20](https://linux-hardware.org/?probe=43528c8a20) | Mar 13, 2022 |
| Dell          | Latitude E7470              | Notebook    | [7ce09d403d](https://linux-hardware.org/?probe=7ce09d403d) | Mar 13, 2022 |
| Dell          | Latitude E7470              | Notebook    | [0d9c88498d](https://linux-hardware.org/?probe=0d9c88498d) | Mar 13, 2022 |
| HP            | Pavilion dv7                | Notebook    | [91b8a77019](https://linux-hardware.org/?probe=91b8a77019) | Mar 13, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [ec1783840e](https://linux-hardware.org/?probe=ec1783840e) | Mar 13, 2022 |
| Dell          | Latitude E7470              | Notebook    | [31b0bbe97f](https://linux-hardware.org/?probe=31b0bbe97f) | Mar 13, 2022 |
| Samsung       | SP55S                       | Notebook    | [8f80ddd945](https://linux-hardware.org/?probe=8f80ddd945) | Mar 13, 2022 |
| Gigabyte      | X79-UD3                     | Desktop     | [32e2e3a0f0](https://linux-hardware.org/?probe=32e2e3a0f0) | Mar 13, 2022 |
| ASUSTek       | Maximus VIII GENE           | Desktop     | [f264de34b1](https://linux-hardware.org/?probe=f264de34b1) | Mar 13, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [b2ae743e44](https://linux-hardware.org/?probe=b2ae743e44) | Mar 13, 2022 |
| Microsoft     | Surface Book                | Tablet      | [00d499f50c](https://linux-hardware.org/?probe=00d499f50c) | Mar 13, 2022 |
| Medion        | B560H6-EM2                  | Desktop     | [b60d99a16b](https://linux-hardware.org/?probe=b60d99a16b) | Mar 13, 2022 |
| Acer          | Aspire 5253G                | Notebook    | [a68548c466](https://linux-hardware.org/?probe=a68548c466) | Mar 12, 2022 |
| Acer          | Aspire 5253G                | Notebook    | [b3c693dcf5](https://linux-hardware.org/?probe=b3c693dcf5) | Mar 12, 2022 |
| HP            | Pavilion dv7                | Notebook    | [5645f0fbec](https://linux-hardware.org/?probe=5645f0fbec) | Mar 12, 2022 |
| MSI           | MS-7502 Fab D               | Desktop     | [8c29483032](https://linux-hardware.org/?probe=8c29483032) | Mar 12, 2022 |
| HP            | 86F7                        | All in one  | [5f5b9f5197](https://linux-hardware.org/?probe=5f5b9f5197) | Mar 12, 2022 |
| HP            | 86F7                        | All in one  | [581cdfee01](https://linux-hardware.org/?probe=581cdfee01) | Mar 12, 2022 |
| Gigabyte      | H61MA-D3V                   | Desktop     | [d8b0e137ea](https://linux-hardware.org/?probe=d8b0e137ea) | Mar 12, 2022 |
| Gigabyte      | G1.Sniper 3                 | Desktop     | [718c17782e](https://linux-hardware.org/?probe=718c17782e) | Mar 12, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [85920b5b34](https://linux-hardware.org/?probe=85920b5b34) | Mar 12, 2022 |
| BESSTAR Te... | DMAF5 V1.0                  | Desktop     | [64a01267e3](https://linux-hardware.org/?probe=64a01267e3) | Mar 12, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [2f53098049](https://linux-hardware.org/?probe=2f53098049) | Mar 12, 2022 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [733d90f097](https://linux-hardware.org/?probe=733d90f097) | Mar 12, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [72e05276c6](https://linux-hardware.org/?probe=72e05276c6) | Mar 12, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [1d740c1027](https://linux-hardware.org/?probe=1d740c1027) | Mar 12, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [382125d883](https://linux-hardware.org/?probe=382125d883) | Mar 12, 2022 |
| HP            | 0AECh D                     | Desktop     | [2c677684a5](https://linux-hardware.org/?probe=2c677684a5) | Mar 11, 2022 |
| MSI           | Indio                       | Desktop     | [a2b0e5c1e2](https://linux-hardware.org/?probe=a2b0e5c1e2) | Mar 11, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [67369297e2](https://linux-hardware.org/?probe=67369297e2) | Mar 11, 2022 |
| ASRock        | 970 Extreme3 R2.0           | Desktop     | [f417e6a6ef](https://linux-hardware.org/?probe=f417e6a6ef) | Mar 11, 2022 |
| Toshiba       | PORTEGE R600                | Notebook    | [0ef53cb367](https://linux-hardware.org/?probe=0ef53cb367) | Mar 11, 2022 |
| Acer          | TravelMate 5720             | Notebook    | [2dc6f60b5e](https://linux-hardware.org/?probe=2dc6f60b5e) | Mar 11, 2022 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [5989c71041](https://linux-hardware.org/?probe=5989c71041) | Mar 11, 2022 |
| Sony          | VGN-FW21E                   | Notebook    | [93205c5e40](https://linux-hardware.org/?probe=93205c5e40) | Mar 11, 2022 |
| ASUSTek       | P5G41-M LX2/GB/LPT          | Desktop     | [4dc5bfdc61](https://linux-hardware.org/?probe=4dc5bfdc61) | Mar 11, 2022 |
| Fujitsu       | Unknown                     | Notebook    | [f5e22dbcd5](https://linux-hardware.org/?probe=f5e22dbcd5) | Mar 11, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [30df05cc2f](https://linux-hardware.org/?probe=30df05cc2f) | Mar 11, 2022 |
| Pegatron      | 2AD5                        | Desktop     | [b4d7d04e65](https://linux-hardware.org/?probe=b4d7d04e65) | Mar 11, 2022 |
| Medion        | E6228                       | Notebook    | [47099a8c6c](https://linux-hardware.org/?probe=47099a8c6c) | Mar 11, 2022 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [016bf7f6ab](https://linux-hardware.org/?probe=016bf7f6ab) | Mar 11, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [1d6563ada3](https://linux-hardware.org/?probe=1d6563ada3) | Mar 11, 2022 |
| Intel         | NUC8BEB J72688-303          | Mini pc     | [f72047dc6d](https://linux-hardware.org/?probe=f72047dc6d) | Mar 11, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [0f0ef0f4a0](https://linux-hardware.org/?probe=0f0ef0f4a0) | Mar 10, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [304a1f3357](https://linux-hardware.org/?probe=304a1f3357) | Mar 10, 2022 |
| ASUSTek       | X510UAR                     | Notebook    | [3bef060804](https://linux-hardware.org/?probe=3bef060804) | Mar 10, 2022 |
| ASRock        | X99 Extreme4                | Desktop     | [d47819516a](https://linux-hardware.org/?probe=d47819516a) | Mar 10, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [589486d805](https://linux-hardware.org/?probe=589486d805) | Mar 10, 2022 |
| Dell          | Latitude 5411               | Notebook    | [b56bb115a0](https://linux-hardware.org/?probe=b56bb115a0) | Mar 10, 2022 |
| Acer          | Aspire A317-33              | Notebook    | [a4c0271977](https://linux-hardware.org/?probe=a4c0271977) | Mar 10, 2022 |
| Lenovo        | ThinkPad Edge E330 33544... | Notebook    | [3cb7da8e63](https://linux-hardware.org/?probe=3cb7da8e63) | Mar 10, 2022 |
| ASUSTek       | P10S-I Series               | Desktop     | [80dfcfd4bf](https://linux-hardware.org/?probe=80dfcfd4bf) | Mar 10, 2022 |
| Acer          | Aspire ES1-311              | Notebook    | [fcd769423d](https://linux-hardware.org/?probe=fcd769423d) | Mar 10, 2022 |
| MSI           | VR630                       | Notebook    | [323001418f](https://linux-hardware.org/?probe=323001418f) | Mar 10, 2022 |
| Acer          | Aspire A515-51              | Notebook    | [8e7b1db68f](https://linux-hardware.org/?probe=8e7b1db68f) | Mar 09, 2022 |
| Lenovo        | ThinkPad X220 4290EC5       | Notebook    | [508a68f09e](https://linux-hardware.org/?probe=508a68f09e) | Mar 09, 2022 |
| Medion        | Akoya THE TOUCH 10          | Notebook    | [be2c2c791c](https://linux-hardware.org/?probe=be2c2c791c) | Mar 09, 2022 |
| Lenovo        | G700 20251                  | Notebook    | [fb6977c476](https://linux-hardware.org/?probe=fb6977c476) | Mar 09, 2022 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [40e96f459b](https://linux-hardware.org/?probe=40e96f459b) | Mar 09, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [4a89454909](https://linux-hardware.org/?probe=4a89454909) | Mar 09, 2022 |
| Dell          | G7 7588                     | Notebook    | [6a2247e8e1](https://linux-hardware.org/?probe=6a2247e8e1) | Mar 09, 2022 |
| Toshiba       | Satellite L450D             | Notebook    | [343578bf21](https://linux-hardware.org/?probe=343578bf21) | Mar 09, 2022 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [0d20279113](https://linux-hardware.org/?probe=0d20279113) | Mar 09, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [c7b32ff620](https://linux-hardware.org/?probe=c7b32ff620) | Mar 09, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [257f76a0df](https://linux-hardware.org/?probe=257f76a0df) | Mar 09, 2022 |
| ASUSTek       | ROG CROSSHAIR VI EXTREME    | Desktop     | [19894bd1a8](https://linux-hardware.org/?probe=19894bd1a8) | Mar 09, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [b416ba575d](https://linux-hardware.org/?probe=b416ba575d) | Mar 09, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [f38279e396](https://linux-hardware.org/?probe=f38279e396) | Mar 09, 2022 |
| LG Electro... | 16T90P-G.AA78G              | Convertible | [00d2c1dc0e](https://linux-hardware.org/?probe=00d2c1dc0e) | Mar 09, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [ef06c07ea8](https://linux-hardware.org/?probe=ef06c07ea8) | Mar 08, 2022 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [cfd96dd963](https://linux-hardware.org/?probe=cfd96dd963) | Mar 08, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [0b073ea407](https://linux-hardware.org/?probe=0b073ea407) | Mar 08, 2022 |
| MSI           | H510M-A PRO                 | Desktop     | [bbd0c9e387](https://linux-hardware.org/?probe=bbd0c9e387) | Mar 08, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [bd1f2169bf](https://linux-hardware.org/?probe=bd1f2169bf) | Mar 08, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [5939b86f71](https://linux-hardware.org/?probe=5939b86f71) | Mar 08, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [68422c3f35](https://linux-hardware.org/?probe=68422c3f35) | Mar 08, 2022 |
| Acer          | Predator G3-710             | Desktop     | [5caa62791e](https://linux-hardware.org/?probe=5caa62791e) | Mar 08, 2022 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [3a5b474c25](https://linux-hardware.org/?probe=3a5b474c25) | Mar 08, 2022 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [bac5f3b0ba](https://linux-hardware.org/?probe=bac5f3b0ba) | Mar 08, 2022 |
| Gigabyte      | Z590M GAMING X              | Desktop     | [0f91bdb0c4](https://linux-hardware.org/?probe=0f91bdb0c4) | Mar 08, 2022 |
| Lenovo        | ThinkPad E15 20RD0016GE     | Notebook    | [b48a6240bf](https://linux-hardware.org/?probe=b48a6240bf) | Mar 08, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [33ce116b8a](https://linux-hardware.org/?probe=33ce116b8a) | Mar 08, 2022 |
| Packard Be... | EasyNote LS11HR             | Notebook    | [7a99940861](https://linux-hardware.org/?probe=7a99940861) | Mar 08, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f50abf2114](https://linux-hardware.org/?probe=f50abf2114) | Mar 08, 2022 |
| HP            | EliteBook 2760p             | Notebook    | [04f075f04a](https://linux-hardware.org/?probe=04f075f04a) | Mar 08, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [8639c407d7](https://linux-hardware.org/?probe=8639c407d7) | Mar 08, 2022 |
| Notebook      | PCx0Dx                      | Notebook    | [00b59d57b7](https://linux-hardware.org/?probe=00b59d57b7) | Mar 08, 2022 |
| HP            | 1589                        | Desktop     | [5a3c3065d0](https://linux-hardware.org/?probe=5a3c3065d0) | Mar 07, 2022 |
| Medion        | E2292 MD63390               | Convertible | [6f0eb8e6d7](https://linux-hardware.org/?probe=6f0eb8e6d7) | Mar 07, 2022 |
| Gigabyte      | GA-990FXA-D3                | Desktop     | [35e716f504](https://linux-hardware.org/?probe=35e716f504) | Mar 07, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [b5be57b7d1](https://linux-hardware.org/?probe=b5be57b7d1) | Mar 07, 2022 |
| Fujitsu       | LIFEBOOK T939               | Convertible | [aa341bdff4](https://linux-hardware.org/?probe=aa341bdff4) | Mar 07, 2022 |
| ASUSTek       | X99-A                       | Desktop     | [0a0f830750](https://linux-hardware.org/?probe=0a0f830750) | Mar 07, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [fb183bfd9b](https://linux-hardware.org/?probe=fb183bfd9b) | Mar 07, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [8b6d3c257a](https://linux-hardware.org/?probe=8b6d3c257a) | Mar 07, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b69a703ea3](https://linux-hardware.org/?probe=b69a703ea3) | Mar 07, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [38c79d4929](https://linux-hardware.org/?probe=38c79d4929) | Mar 07, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [a658bf2304](https://linux-hardware.org/?probe=a658bf2304) | Mar 07, 2022 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [6382c70064](https://linux-hardware.org/?probe=6382c70064) | Mar 07, 2022 |
| Packard Be... | EasyNote TM85               | Notebook    | [10c87bed94](https://linux-hardware.org/?probe=10c87bed94) | Mar 07, 2022 |
| Packard Be... | EasyNote TM85               | Notebook    | [2b3ba9a762](https://linux-hardware.org/?probe=2b3ba9a762) | Mar 07, 2022 |
| Intel         | DH87RL AAG74240-403         | Desktop     | [9c8ac31778](https://linux-hardware.org/?probe=9c8ac31778) | Mar 07, 2022 |
| Medion        | E3215 MD60929               | Convertible | [6dc47facf1](https://linux-hardware.org/?probe=6dc47facf1) | Mar 07, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [eccfe5b35c](https://linux-hardware.org/?probe=eccfe5b35c) | Mar 07, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [af11e24c3a](https://linux-hardware.org/?probe=af11e24c3a) | Mar 07, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [a789a0bd98](https://linux-hardware.org/?probe=a789a0bd98) | Mar 06, 2022 |
| AXDIA Inte... | MYBOOK 14 PRO               | Notebook    | [a02da9c610](https://linux-hardware.org/?probe=a02da9c610) | Mar 06, 2022 |
| AXDIA Inte... | WINBOOK 13                  | Notebook    | [6cf2cc07ed](https://linux-hardware.org/?probe=6cf2cc07ed) | Mar 06, 2022 |
| Lenovo        | ThinkPad X250 20CLS06L00    | Notebook    | [e6d00b85ed](https://linux-hardware.org/?probe=e6d00b85ed) | Mar 06, 2022 |
| ASUSTek       | PRIME X399-A                | Desktop     | [6ea4f3e080](https://linux-hardware.org/?probe=6ea4f3e080) | Mar 06, 2022 |
| Toshiba       | Satellite M50D-A            | Notebook    | [97beedb37f](https://linux-hardware.org/?probe=97beedb37f) | Mar 06, 2022 |
| HP            | EliteBook 820 G2            | Notebook    | [ecb1064b14](https://linux-hardware.org/?probe=ecb1064b14) | Mar 06, 2022 |
| Lenovo        | ThinkPad X230 2325ND9       | Notebook    | [02818352e0](https://linux-hardware.org/?probe=02818352e0) | Mar 06, 2022 |
| ASUSTek       | PRIME B250-PRO              | Desktop     | [aa3b366734](https://linux-hardware.org/?probe=aa3b366734) | Mar 06, 2022 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [fe252970ae](https://linux-hardware.org/?probe=fe252970ae) | Mar 06, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [783c8d9097](https://linux-hardware.org/?probe=783c8d9097) | Mar 06, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c0af09f04d](https://linux-hardware.org/?probe=c0af09f04d) | Mar 06, 2022 |
| Lenovo        | ThinkPad X230 2325ND9       | Notebook    | [24a601d3aa](https://linux-hardware.org/?probe=24a601d3aa) | Mar 06, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [3a889dd69f](https://linux-hardware.org/?probe=3a889dd69f) | Mar 06, 2022 |
| Acer          | H57M01                      | Desktop     | [7519d0fded](https://linux-hardware.org/?probe=7519d0fded) | Mar 06, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [aaee5488dd](https://linux-hardware.org/?probe=aaee5488dd) | Mar 06, 2022 |
| Acer          | Aspire 8943G                | Notebook    | [b7e82c9025](https://linux-hardware.org/?probe=b7e82c9025) | Mar 06, 2022 |
| MSI           | H61MA-E35                   | Desktop     | [f95f2cdf47](https://linux-hardware.org/?probe=f95f2cdf47) | Mar 06, 2022 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [ddc210f8d1](https://linux-hardware.org/?probe=ddc210f8d1) | Mar 06, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [f37fbd930e](https://linux-hardware.org/?probe=f37fbd930e) | Mar 06, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [2b748962fa](https://linux-hardware.org/?probe=2b748962fa) | Mar 06, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [4498ec2620](https://linux-hardware.org/?probe=4498ec2620) | Mar 06, 2022 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [f6f278aca1](https://linux-hardware.org/?probe=f6f278aca1) | Mar 06, 2022 |
| Dell          | 0KWVT8 A02                  | Desktop     | [d10f2fddcf](https://linux-hardware.org/?probe=d10f2fddcf) | Mar 06, 2022 |
| Gigabyte      | EP35-DS3                    | Desktop     | [dd1758aaa7](https://linux-hardware.org/?probe=dd1758aaa7) | Mar 05, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [dff6b97b90](https://linux-hardware.org/?probe=dff6b97b90) | Mar 05, 2022 |
| ASRock        | X570 Steel Legend           | Desktop     | [e7843ce1cf](https://linux-hardware.org/?probe=e7843ce1cf) | Mar 05, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [50f8055f7f](https://linux-hardware.org/?probe=50f8055f7f) | Mar 05, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [a95029db57](https://linux-hardware.org/?probe=a95029db57) | Mar 05, 2022 |
| Sony          | SVE1712L1EW                 | Notebook    | [7fbf3864bc](https://linux-hardware.org/?probe=7fbf3864bc) | Mar 05, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [d14c8653c5](https://linux-hardware.org/?probe=d14c8653c5) | Mar 05, 2022 |
| HP            | 8381 1000                   | All in one  | [0dc8027649](https://linux-hardware.org/?probe=0dc8027649) | Mar 05, 2022 |
| HP            | ZBook 15 G5                 | Notebook    | [f86a14c16d](https://linux-hardware.org/?probe=f86a14c16d) | Mar 05, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [072edd2dca](https://linux-hardware.org/?probe=072edd2dca) | Mar 05, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [0171fa003c](https://linux-hardware.org/?probe=0171fa003c) | Mar 05, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [efd8c169a2](https://linux-hardware.org/?probe=efd8c169a2) | Mar 05, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [5ad2748e93](https://linux-hardware.org/?probe=5ad2748e93) | Mar 05, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [c719d350e4](https://linux-hardware.org/?probe=c719d350e4) | Mar 05, 2022 |
| ASUSTek       | PRIME H310-PLUS R2.0        | Desktop     | [7514554127](https://linux-hardware.org/?probe=7514554127) | Mar 05, 2022 |
| Toshiba       | Satellite S50-B             | Notebook    | [96cc83a704](https://linux-hardware.org/?probe=96cc83a704) | Mar 05, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [707b59278e](https://linux-hardware.org/?probe=707b59278e) | Mar 05, 2022 |
| ASUSTek       | P6T                         | Desktop     | [fec110ebb0](https://linux-hardware.org/?probe=fec110ebb0) | Mar 05, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [17cc3f10df](https://linux-hardware.org/?probe=17cc3f10df) | Mar 05, 2022 |
| ASUSTek       | PRIME H310-PLUS R2.0        | Desktop     | [eb47ea883e](https://linux-hardware.org/?probe=eb47ea883e) | Mar 05, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [c6fa3e547d](https://linux-hardware.org/?probe=c6fa3e547d) | Mar 05, 2022 |
| MSI           | X99A SLI PLUS               | Desktop     | [b56033aa1d](https://linux-hardware.org/?probe=b56033aa1d) | Mar 05, 2022 |
| Dell          | Latitude E5500              | Notebook    | [0086493104](https://linux-hardware.org/?probe=0086493104) | Mar 04, 2022 |
| Foxconn       | A74ML/A74ML-K 3.0 1.0       | Desktop     | [61c50ec77f](https://linux-hardware.org/?probe=61c50ec77f) | Mar 04, 2022 |
| Apple         | MacBookPro5,2               | Notebook    | [a1728941bf](https://linux-hardware.org/?probe=a1728941bf) | Mar 04, 2022 |
| MSI           | Z77A-GD65                   | Desktop     | [c25ffc39db](https://linux-hardware.org/?probe=c25ffc39db) | Mar 04, 2022 |
| MSI           | Z77A-GD65                   | Desktop     | [261fc7fc09](https://linux-hardware.org/?probe=261fc7fc09) | Mar 04, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [87f171aaf2](https://linux-hardware.org/?probe=87f171aaf2) | Mar 04, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [058cafa79c](https://linux-hardware.org/?probe=058cafa79c) | Mar 04, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [504b20acce](https://linux-hardware.org/?probe=504b20acce) | Mar 04, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [61ae40f852](https://linux-hardware.org/?probe=61ae40f852) | Mar 04, 2022 |
| Lenovo        | 102F SDK0E50510 WIN 2625... | Desktop     | [efc3112f5a](https://linux-hardware.org/?probe=efc3112f5a) | Mar 04, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [8c13511a03](https://linux-hardware.org/?probe=8c13511a03) | Mar 03, 2022 |
| MSI           | H97 PC Mate                 | Desktop     | [4902f63911](https://linux-hardware.org/?probe=4902f63911) | Mar 03, 2022 |
| Dell          | 01TN68 A01                  | Desktop     | [f57cafd9b1](https://linux-hardware.org/?probe=f57cafd9b1) | Mar 03, 2022 |
| Dell          | 01TN68 A01                  | Desktop     | [a93c073676](https://linux-hardware.org/?probe=a93c073676) | Mar 03, 2022 |
| Acer          | Aspire ES1-531              | Notebook    | [fa2dbff255](https://linux-hardware.org/?probe=fa2dbff255) | Mar 03, 2022 |
| Acer          | Aspire ES1-531              | Notebook    | [8cdb809fce](https://linux-hardware.org/?probe=8cdb809fce) | Mar 03, 2022 |
| Medion        | Akoya P6638                 | Notebook    | [102c7910e5](https://linux-hardware.org/?probe=102c7910e5) | Mar 03, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [78089f6e8c](https://linux-hardware.org/?probe=78089f6e8c) | Mar 03, 2022 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [16268a74aa](https://linux-hardware.org/?probe=16268a74aa) | Mar 03, 2022 |
| Dell          | Studio 1737                 | Notebook    | [874afb5afd](https://linux-hardware.org/?probe=874afb5afd) | Mar 03, 2022 |
| Unknown       | Unknown                     | Notebook    | [40bfdf6d39](https://linux-hardware.org/?probe=40bfdf6d39) | Mar 03, 2022 |
| HP            | Pavilion dv6700             | Notebook    | [42079a88f3](https://linux-hardware.org/?probe=42079a88f3) | Mar 03, 2022 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [50f5b458cf](https://linux-hardware.org/?probe=50f5b458cf) | Mar 03, 2022 |
| Lenovo        | ThinkCentre M91p 4524WAP    | Desktop     | [1d01e4616b](https://linux-hardware.org/?probe=1d01e4616b) | Mar 03, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [154e9a732e](https://linux-hardware.org/?probe=154e9a732e) | Mar 02, 2022 |
| ASRock        | J5005-ITX                   | Desktop     | [39757e65f1](https://linux-hardware.org/?probe=39757e65f1) | Mar 02, 2022 |
| ASRock        | N68C-S UCC                  | Desktop     | [22b1e02dcd](https://linux-hardware.org/?probe=22b1e02dcd) | Mar 02, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [ea7eabcf23](https://linux-hardware.org/?probe=ea7eabcf23) | Mar 02, 2022 |
| ASUSTek       | P8P67 LE                    | Desktop     | [6cc4fbe484](https://linux-hardware.org/?probe=6cc4fbe484) | Mar 02, 2022 |
| ASRock        | Z77 Pro4                    | Desktop     | [ae5611419f](https://linux-hardware.org/?probe=ae5611419f) | Mar 02, 2022 |
| HP            | Pavilion dv7                | Notebook    | [baa28e6924](https://linux-hardware.org/?probe=baa28e6924) | Mar 02, 2022 |
| Otazak        | iPC45                       | Convertible | [9f49730dc3](https://linux-hardware.org/?probe=9f49730dc3) | Mar 02, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [053e9ac0e2](https://linux-hardware.org/?probe=053e9ac0e2) | Mar 02, 2022 |
| Otazak        | iPC45                       | Convertible | [5a1d628672](https://linux-hardware.org/?probe=5a1d628672) | Mar 02, 2022 |
| Lenovo        | ThinkPad X200 7459N40       | Notebook    | [ac28cda346](https://linux-hardware.org/?probe=ac28cda346) | Mar 02, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [b74317d80e](https://linux-hardware.org/?probe=b74317d80e) | Mar 02, 2022 |
| LG Electro... | 16T90P-G.AA78G              | Convertible | [a2e5097f1c](https://linux-hardware.org/?probe=a2e5097f1c) | Mar 02, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [ac1c3aef05](https://linux-hardware.org/?probe=ac1c3aef05) | Mar 02, 2022 |
| Lenovo        | ThinkPad Edge E545 20B20... | Notebook    | [fa187c3e66](https://linux-hardware.org/?probe=fa187c3e66) | Mar 02, 2022 |
| Schenker      | XMG CORE (CZN/E21)          | Notebook    | [c2aa5e4261](https://linux-hardware.org/?probe=c2aa5e4261) | Mar 02, 2022 |
| MSI           | X99A SLI PLUS               | Desktop     | [0c6f411b98](https://linux-hardware.org/?probe=0c6f411b98) | Mar 01, 2022 |
| HP            | Pavilion dv7                | Notebook    | [f1e2817a55](https://linux-hardware.org/?probe=f1e2817a55) | Mar 01, 2022 |
| Medion        | E2292                       | Convertible | [e7fb0bbd0d](https://linux-hardware.org/?probe=e7fb0bbd0d) | Mar 01, 2022 |
| Samsung       | R530/R730                   | Notebook    | [d28aae8671](https://linux-hardware.org/?probe=d28aae8671) | Mar 01, 2022 |
| Samsung       | R530/R730                   | Notebook    | [8e63f95f66](https://linux-hardware.org/?probe=8e63f95f66) | Mar 01, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [336ddc137d](https://linux-hardware.org/?probe=336ddc137d) | Mar 01, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [4935a5660c](https://linux-hardware.org/?probe=4935a5660c) | Mar 01, 2022 |
| ABIT          | AN8 32X                     | Desktop     | [bd11e8ebd1](https://linux-hardware.org/?probe=bd11e8ebd1) | Mar 01, 2022 |
| Acer          | TravelMate 5760Z            | Notebook    | [b22c36a345](https://linux-hardware.org/?probe=b22c36a345) | Mar 01, 2022 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [4bb09313d1](https://linux-hardware.org/?probe=4bb09313d1) | Mar 01, 2022 |
| Medion        | H81H3-EM2                   | Desktop     | [88c0b3ad37](https://linux-hardware.org/?probe=88c0b3ad37) | Mar 01, 2022 |
| Medion        | Akoya E7221                 | Notebook    | [a66540bc44](https://linux-hardware.org/?probe=a66540bc44) | Mar 01, 2022 |
| Gigabyte      | Z68A-D3H-B3                 | Desktop     | [3bba8576a0](https://linux-hardware.org/?probe=3bba8576a0) | Feb 28, 2022 |
| Chuwi         | LarkBook                    | Notebook    | [90fc748492](https://linux-hardware.org/?probe=90fc748492) | Feb 28, 2022 |
| HP            | Laptop 15-db1xxx            | Notebook    | [03394e745c](https://linux-hardware.org/?probe=03394e745c) | Feb 28, 2022 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [edfa6eb6e3](https://linux-hardware.org/?probe=edfa6eb6e3) | Feb 28, 2022 |
| Chuwi         | LarkBook                    | Notebook    | [4102a66a3e](https://linux-hardware.org/?probe=4102a66a3e) | Feb 28, 2022 |
| Fujitsu       | LIFEBOOK E544               | Notebook    | [0b2c8c1077](https://linux-hardware.org/?probe=0b2c8c1077) | Feb 28, 2022 |
| Gigabyte      | AX370-Gaming K5-CF          | Desktop     | [61f8410abd](https://linux-hardware.org/?probe=61f8410abd) | Feb 28, 2022 |
| HP            | Notebook                    | Notebook    | [f820b3f676](https://linux-hardware.org/?probe=f820b3f676) | Feb 28, 2022 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [0bb471d9a2](https://linux-hardware.org/?probe=0bb471d9a2) | Feb 28, 2022 |
| PC Engines    | APU2                        | Desktop     | [3865ba76a4](https://linux-hardware.org/?probe=3865ba76a4) | Feb 28, 2022 |
| BESSTAR Te... | TL50                        | Desktop     | [54383b0005](https://linux-hardware.org/?probe=54383b0005) | Feb 28, 2022 |
| Acer          | TravelMate 5760Z            | Notebook    | [da8a65dcfc](https://linux-hardware.org/?probe=da8a65dcfc) | Feb 28, 2022 |
| Schenker      | VIA 15                      | Notebook    | [c84aacc342](https://linux-hardware.org/?probe=c84aacc342) | Feb 28, 2022 |
| ASRock        | X370 Taichi                 | Desktop     | [9315349aa3](https://linux-hardware.org/?probe=9315349aa3) | Feb 28, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [2623cf5090](https://linux-hardware.org/?probe=2623cf5090) | Feb 28, 2022 |
| ASRock        | X370 Taichi                 | Desktop     | [4fe10bf579](https://linux-hardware.org/?probe=4fe10bf579) | Feb 28, 2022 |
| HP            | 350 G2                      | Notebook    | [61e56d2d17](https://linux-hardware.org/?probe=61e56d2d17) | Feb 28, 2022 |
| MAXDATA       | PRO6100IW                   | Notebook    | [023e60cf6e](https://linux-hardware.org/?probe=023e60cf6e) | Feb 28, 2022 |
| HP            | 255 G5                      | Notebook    | [050e7b02e7](https://linux-hardware.org/?probe=050e7b02e7) | Feb 28, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [fa94978a0b](https://linux-hardware.org/?probe=fa94978a0b) | Feb 28, 2022 |
| Lenovo        | ThinkPad X220 42912WU       | Notebook    | [71cc4e2875](https://linux-hardware.org/?probe=71cc4e2875) | Feb 28, 2022 |
| ASUSTek       | UX305FA                     | Notebook    | [6618b00369](https://linux-hardware.org/?probe=6618b00369) | Feb 28, 2022 |
| Medion        | MS-7728                     | Desktop     | [c1a78e4700](https://linux-hardware.org/?probe=c1a78e4700) | Feb 28, 2022 |
| HP            | Pavilion g7                 | Notebook    | [c9fa0137bd](https://linux-hardware.org/?probe=c9fa0137bd) | Feb 27, 2022 |
| Toshiba       | QOSMIO F60                  | Notebook    | [20bc8b40ec](https://linux-hardware.org/?probe=20bc8b40ec) | Feb 27, 2022 |
| Samsung       | 930XCJ/931XCJ/930XCR        | Notebook    | [b7db3a112d](https://linux-hardware.org/?probe=b7db3a112d) | Feb 27, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [40f6802b71](https://linux-hardware.org/?probe=40f6802b71) | Feb 27, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [a688333ca8](https://linux-hardware.org/?probe=a688333ca8) | Feb 27, 2022 |
| Acer          | EG43M                       | Desktop     | [eb63ef98be](https://linux-hardware.org/?probe=eb63ef98be) | Feb 27, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [de3e77f3b2](https://linux-hardware.org/?probe=de3e77f3b2) | Feb 27, 2022 |
| ASUSTek       | M2N-VM DVI                  | Desktop     | [9445334bf6](https://linux-hardware.org/?probe=9445334bf6) | Feb 27, 2022 |
| Foxconn       | G41MX/G41MX-K 2.0 1.0       | Desktop     | [b1e2e1baa3](https://linux-hardware.org/?probe=b1e2e1baa3) | Feb 27, 2022 |
| Acer          | Aspire X3950                | Desktop     | [29e02ae274](https://linux-hardware.org/?probe=29e02ae274) | Feb 27, 2022 |
| ECT           | ONE UNIQUE BOOK R4-0        | Notebook    | [e4cacb360f](https://linux-hardware.org/?probe=e4cacb360f) | Feb 27, 2022 |
| Toshiba       | Satellite M50D-A            | Notebook    | [9710eeef66](https://linux-hardware.org/?probe=9710eeef66) | Feb 27, 2022 |
| Dell          | 0Y958C A00                  | Desktop     | [e2abde1282](https://linux-hardware.org/?probe=e2abde1282) | Feb 27, 2022 |
| ASUSTek       | K73BY                       | Notebook    | [ea3bb81aaf](https://linux-hardware.org/?probe=ea3bb81aaf) | Feb 27, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [a2ab2cc330](https://linux-hardware.org/?probe=a2ab2cc330) | Feb 27, 2022 |
| Lenovo        | G560 0679                   | Notebook    | [7109402c58](https://linux-hardware.org/?probe=7109402c58) | Feb 27, 2022 |
| EVGA          | 132-CK-NF79 2               | Desktop     | [5fa52d2663](https://linux-hardware.org/?probe=5fa52d2663) | Feb 27, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [c1bee41eec](https://linux-hardware.org/?probe=c1bee41eec) | Feb 27, 2022 |
| Lenovo        | Legion S7 15IMH5 82BC       | Notebook    | [c11b3c6a72](https://linux-hardware.org/?probe=c11b3c6a72) | Feb 26, 2022 |
| Medion        | Erazer X7843 MD99996        | Notebook    | [40992abdec](https://linux-hardware.org/?probe=40992abdec) | Feb 26, 2022 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | Desktop     | [d595617abd](https://linux-hardware.org/?probe=d595617abd) | Feb 26, 2022 |
| ASRock        | H170M Pro4                  | Desktop     | [c86d644cbc](https://linux-hardware.org/?probe=c86d644cbc) | Feb 26, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [36aacb1723](https://linux-hardware.org/?probe=36aacb1723) | Feb 26, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [94863ceac1](https://linux-hardware.org/?probe=94863ceac1) | Feb 26, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f09e586977](https://linux-hardware.org/?probe=f09e586977) | Feb 26, 2022 |
| Lenovo        | ThinkPad T520 4243W4K       | Notebook    | [41c5dd8a4a](https://linux-hardware.org/?probe=41c5dd8a4a) | Feb 26, 2022 |
| HP            | EliteBook 8560p             | Notebook    | [d440e21050](https://linux-hardware.org/?probe=d440e21050) | Feb 26, 2022 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [7da971b4f7](https://linux-hardware.org/?probe=7da971b4f7) | Feb 26, 2022 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [9baeef9b55](https://linux-hardware.org/?probe=9baeef9b55) | Feb 26, 2022 |
| Medion        | Erazer X7843 MD99996        | Notebook    | [495ae782c5](https://linux-hardware.org/?probe=495ae782c5) | Feb 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [a9bcae50d2](https://linux-hardware.org/?probe=a9bcae50d2) | Feb 26, 2022 |
| Lenovo        | 40684WG                     | Notebook    | [a384c932ce](https://linux-hardware.org/?probe=a384c932ce) | Feb 26, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [73992b02d0](https://linux-hardware.org/?probe=73992b02d0) | Feb 26, 2022 |
| Fujitsu       | FARQ0200GZ                  | Notebook    | [a309120953](https://linux-hardware.org/?probe=a309120953) | Feb 26, 2022 |
| Gigabyte      | H77-D3H                     | Desktop     | [3ee9b2192f](https://linux-hardware.org/?probe=3ee9b2192f) | Feb 26, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [7fb770cac8](https://linux-hardware.org/?probe=7fb770cac8) | Feb 25, 2022 |
| AZW           | GTR V01                     | Mini pc     | [39d215e49d](https://linux-hardware.org/?probe=39d215e49d) | Feb 25, 2022 |
| Lenovo        | ThinkPad E15 20RD001CGE     | Notebook    | [caae85eba1](https://linux-hardware.org/?probe=caae85eba1) | Feb 25, 2022 |
| HP            | Pavilion g7                 | Notebook    | [66d6050018](https://linux-hardware.org/?probe=66d6050018) | Feb 25, 2022 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [e6b5acbb9e](https://linux-hardware.org/?probe=e6b5acbb9e) | Feb 25, 2022 |
| LG Electro... | 16T90P-G.AA78G              | Convertible | [0ba06521c5](https://linux-hardware.org/?probe=0ba06521c5) | Feb 25, 2022 |
| Acer          | Aspire ES1-520              | Notebook    | [a885962e63](https://linux-hardware.org/?probe=a885962e63) | Feb 25, 2022 |
| Acer          | Aspire ES1-520              | Notebook    | [8297e9e3c9](https://linux-hardware.org/?probe=8297e9e3c9) | Feb 25, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [cb5e72732d](https://linux-hardware.org/?probe=cb5e72732d) | Feb 25, 2022 |
| Lenovo        | G70-80 80FF                 | Notebook    | [0a349a2a70](https://linux-hardware.org/?probe=0a349a2a70) | Feb 25, 2022 |
| MSI           | B85-G41 PC Mate             | Desktop     | [ba28960b69](https://linux-hardware.org/?probe=ba28960b69) | Feb 25, 2022 |
| ASUSTek       | U33Jc                       | Notebook    | [c45cdff0f9](https://linux-hardware.org/?probe=c45cdff0f9) | Feb 25, 2022 |
| ASUSTek       | N82JV                       | Notebook    | [30b9ccdcc9](https://linux-hardware.org/?probe=30b9ccdcc9) | Feb 25, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [284a79d341](https://linux-hardware.org/?probe=284a79d341) | Feb 25, 2022 |
| MSI           | B450M GAMING PLUS           | Desktop     | [abb828286d](https://linux-hardware.org/?probe=abb828286d) | Feb 25, 2022 |
| LG Electro... | 16T90P-G.AA78G              | Convertible | [a5d0cdcf47](https://linux-hardware.org/?probe=a5d0cdcf47) | Feb 25, 2022 |
| MSI           | H81M-E34                    | Desktop     | [af63be0001](https://linux-hardware.org/?probe=af63be0001) | Feb 25, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [97284dc322](https://linux-hardware.org/?probe=97284dc322) | Feb 25, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [f904e185fb](https://linux-hardware.org/?probe=f904e185fb) | Feb 25, 2022 |
| Dell          | Inspiron 5505               | Notebook    | [42117b7c9e](https://linux-hardware.org/?probe=42117b7c9e) | Feb 25, 2022 |
| Packard Be... | Veriton M275                | Desktop     | [4957ee6cb9](https://linux-hardware.org/?probe=4957ee6cb9) | Feb 25, 2022 |
| Samsung       | R530/R730                   | Notebook    | [8786882929](https://linux-hardware.org/?probe=8786882929) | Feb 25, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [a8b2cacac9](https://linux-hardware.org/?probe=a8b2cacac9) | Feb 25, 2022 |
| ASUSTek       | P5G41T-M LE                 | Desktop     | [a8f77b99e9](https://linux-hardware.org/?probe=a8f77b99e9) | Feb 25, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [7fa418eb00](https://linux-hardware.org/?probe=7fa418eb00) | Feb 25, 2022 |
| ASUSTek       | X555LA                      | Notebook    | [35acd46342](https://linux-hardware.org/?probe=35acd46342) | Feb 25, 2022 |
| Apple         | MacBook8,1                  | Notebook    | [b7b8d7f677](https://linux-hardware.org/?probe=b7b8d7f677) | Feb 24, 2022 |
| ZOTAC         | ZBOX-MI/CI625/645/665NAN... | Mini pc     | [28eaf0b05c](https://linux-hardware.org/?probe=28eaf0b05c) | Feb 24, 2022 |
| Biostar       | A960D+V2                    | Desktop     | [44b785c006](https://linux-hardware.org/?probe=44b785c006) | Feb 24, 2022 |
| ASUSTek       | BU203UA                     | Notebook    | [20764e8ede](https://linux-hardware.org/?probe=20764e8ede) | Feb 24, 2022 |
| HP            | 81B7 1101                   | All in one  | [35ab480926](https://linux-hardware.org/?probe=35ab480926) | Feb 24, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [22061aea18](https://linux-hardware.org/?probe=22061aea18) | Feb 24, 2022 |
| Acer          | Aspire A517-52G             | Notebook    | [640aca6d9f](https://linux-hardware.org/?probe=640aca6d9f) | Feb 24, 2022 |
| Lenovo        | ThinkPad T61 6468AE1        | Notebook    | [8ce87acc24](https://linux-hardware.org/?probe=8ce87acc24) | Feb 24, 2022 |
| MSI           | H310M PRO-D                 | Desktop     | [e81725af53](https://linux-hardware.org/?probe=e81725af53) | Feb 24, 2022 |
| Dell          | Latitude E6400              | Notebook    | [1c966f91d9](https://linux-hardware.org/?probe=1c966f91d9) | Feb 24, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [5e9d5e778e](https://linux-hardware.org/?probe=5e9d5e778e) | Feb 24, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [393e833123](https://linux-hardware.org/?probe=393e833123) | Feb 24, 2022 |
| Dell          | Latitude E5570              | Notebook    | [c74046ca07](https://linux-hardware.org/?probe=c74046ca07) | Feb 24, 2022 |
| ASRock        | N68C-S UCC                  | Desktop     | [8bff68d779](https://linux-hardware.org/?probe=8bff68d779) | Feb 24, 2022 |
| Dell          | Latitude E6400              | Notebook    | [f60fbfa9f0](https://linux-hardware.org/?probe=f60fbfa9f0) | Feb 24, 2022 |
| Dell          | Latitude E4300              | Notebook    | [bfa3fa7218](https://linux-hardware.org/?probe=bfa3fa7218) | Feb 24, 2022 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [f82673bb20](https://linux-hardware.org/?probe=f82673bb20) | Feb 24, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [967d48cd30](https://linux-hardware.org/?probe=967d48cd30) | Feb 24, 2022 |
| Lenovo        | ThinkPad X230 2325ND9       | Notebook    | [e9341489f1](https://linux-hardware.org/?probe=e9341489f1) | Feb 24, 2022 |
| Medion        | MS-7501                     | Desktop     | [3f2b6c92b5](https://linux-hardware.org/?probe=3f2b6c92b5) | Feb 24, 2022 |
| Acer          | Aspire XC600 v1.0           | Desktop     | [164d113d00](https://linux-hardware.org/?probe=164d113d00) | Feb 24, 2022 |
| Lenovo        | ThinkPad T420 4236A26       | Notebook    | [c0129677c2](https://linux-hardware.org/?probe=c0129677c2) | Feb 24, 2022 |
| ASUSTek       | P5Q                         | Desktop     | [73b06b11d3](https://linux-hardware.org/?probe=73b06b11d3) | Feb 24, 2022 |
| Toshiba       | Satellite L300              | Notebook    | [9f42d69f9f](https://linux-hardware.org/?probe=9f42d69f9f) | Feb 24, 2022 |
| Lenovo        | ThinkPad T500 2056Y2Z       | Notebook    | [fcf18af227](https://linux-hardware.org/?probe=fcf18af227) | Feb 23, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [9a94ad6810](https://linux-hardware.org/?probe=9a94ad6810) | Feb 23, 2022 |
| Toshiba       | Satellite C50-A             | Notebook    | [b1f2dbfcc3](https://linux-hardware.org/?probe=b1f2dbfcc3) | Feb 23, 2022 |
| ASRock        | Q1900M                      | Desktop     | [428eb82cd0](https://linux-hardware.org/?probe=428eb82cd0) | Feb 23, 2022 |
| Lenovo        | ThinkPad T400 27658JG       | Notebook    | [e02ae1e879](https://linux-hardware.org/?probe=e02ae1e879) | Feb 23, 2022 |
| ASRock        | A320M-DGS                   | Desktop     | [f01c5c6bb8](https://linux-hardware.org/?probe=f01c5c6bb8) | Feb 23, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [717a30dca3](https://linux-hardware.org/?probe=717a30dca3) | Feb 23, 2022 |
| Lenovo        | ThinkPad T420 42367A4       | Notebook    | [8a65b38196](https://linux-hardware.org/?probe=8a65b38196) | Feb 23, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [974ddb36b1](https://linux-hardware.org/?probe=974ddb36b1) | Feb 23, 2022 |
| Medion        | MS-7707                     | Desktop     | [563fc4ee5a](https://linux-hardware.org/?probe=563fc4ee5a) | Feb 23, 2022 |
| Medion        | MS-7707                     | Desktop     | [f3b9e8796b](https://linux-hardware.org/?probe=f3b9e8796b) | Feb 23, 2022 |
| ASRock        | P67 Professional            | Desktop     | [3135f5a2d7](https://linux-hardware.org/?probe=3135f5a2d7) | Feb 23, 2022 |
| Lenovo        | ThinkPad T61 6464WBN        | Notebook    | [dde4e34ede](https://linux-hardware.org/?probe=dde4e34ede) | Feb 23, 2022 |
| ASUSTek       | Pro WS C621-64L SAGE Ser... | Desktop     | [17aa7b3d5b](https://linux-hardware.org/?probe=17aa7b3d5b) | Feb 23, 2022 |
| Acer          | Aspire 5920G                | Notebook    | [57bf2bd14b](https://linux-hardware.org/?probe=57bf2bd14b) | Feb 23, 2022 |
| Dell          | 0DRR0P A08                  | Server      | [5011114071](https://linux-hardware.org/?probe=5011114071) | Feb 23, 2022 |
| Sony          | VPCEC2S1E                   | Notebook    | [be321607b0](https://linux-hardware.org/?probe=be321607b0) | Feb 23, 2022 |
| MSI           | P35 Platinum                | Desktop     | [e9c24cd6e9](https://linux-hardware.org/?probe=e9c24cd6e9) | Feb 23, 2022 |
| Dell          | Latitude E6520              | Notebook    | [2e2e342f0f](https://linux-hardware.org/?probe=2e2e342f0f) | Feb 23, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [0908586213](https://linux-hardware.org/?probe=0908586213) | Feb 23, 2022 |
| TrekStor      | Primebook C13               | Convertible | [ddf3fa152c](https://linux-hardware.org/?probe=ddf3fa152c) | Feb 23, 2022 |
| Lenovo        | B71-80 80RJ                 | Notebook    | [a5b06f50bd](https://linux-hardware.org/?probe=a5b06f50bd) | Feb 22, 2022 |
| Lenovo        | IdeaPad N581 7505           | Notebook    | [1d5722d382](https://linux-hardware.org/?probe=1d5722d382) | Feb 22, 2022 |
| Dell          | Latitude E6520              | Notebook    | [20fdd52b94](https://linux-hardware.org/?probe=20fdd52b94) | Feb 22, 2022 |
| ASUSTek       | 1101HA                      | Notebook    | [b234cc741f](https://linux-hardware.org/?probe=b234cc741f) | Feb 22, 2022 |
| Dell          | Inspiron 3721               | Notebook    | [da9c47ddfc](https://linux-hardware.org/?probe=da9c47ddfc) | Feb 22, 2022 |
| ASUSTek       | 1101HA                      | Notebook    | [f8f8968f19](https://linux-hardware.org/?probe=f8f8968f19) | Feb 22, 2022 |
| HP            | 1589                        | Desktop     | [c7b43e89e4](https://linux-hardware.org/?probe=c7b43e89e4) | Feb 22, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [8b7ccdff57](https://linux-hardware.org/?probe=8b7ccdff57) | Feb 22, 2022 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | Desktop     | [7b9414055a](https://linux-hardware.org/?probe=7b9414055a) | Feb 22, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [3a16589adc](https://linux-hardware.org/?probe=3a16589adc) | Feb 22, 2022 |
| Lenovo        | IdeaPad N581 7505           | Notebook    | [92be6f1ea8](https://linux-hardware.org/?probe=92be6f1ea8) | Feb 22, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [2f36c10f42](https://linux-hardware.org/?probe=2f36c10f42) | Feb 22, 2022 |
| Medion        | MS-7707                     | Desktop     | [2e4723aea4](https://linux-hardware.org/?probe=2e4723aea4) | Feb 22, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [779dfa3e78](https://linux-hardware.org/?probe=779dfa3e78) | Feb 22, 2022 |
| Dell          | Latitude E5270              | Notebook    | [5d2d5947f3](https://linux-hardware.org/?probe=5d2d5947f3) | Feb 22, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [0a9140ff8f](https://linux-hardware.org/?probe=0a9140ff8f) | Feb 22, 2022 |
| ASUSTek       | M70Vn                       | Notebook    | [ae56cd459a](https://linux-hardware.org/?probe=ae56cd459a) | Feb 22, 2022 |
| Samsung       | R530/R730                   | Notebook    | [18c21aabf3](https://linux-hardware.org/?probe=18c21aabf3) | Feb 22, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [e24c41d802](https://linux-hardware.org/?probe=e24c41d802) | Feb 21, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [4a5f73ba98](https://linux-hardware.org/?probe=4a5f73ba98) | Feb 21, 2022 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [5df3f1805e](https://linux-hardware.org/?probe=5df3f1805e) | Feb 21, 2022 |
| ASRock        | H61M-GS                     | Desktop     | [00b85049e6](https://linux-hardware.org/?probe=00b85049e6) | Feb 21, 2022 |
| HP            | EliteBook Revolve 810 G1    | Notebook    | [838f13e574](https://linux-hardware.org/?probe=838f13e574) | Feb 21, 2022 |
| Medion        | TJ4125                      | Desktop     | [04d5f95a16](https://linux-hardware.org/?probe=04d5f95a16) | Feb 21, 2022 |
| Medion        | P6613                       | Notebook    | [bba96ca768](https://linux-hardware.org/?probe=bba96ca768) | Feb 21, 2022 |
| Lenovo        | ThinkPad T470 20HES18R2C    | Notebook    | [64d768d709](https://linux-hardware.org/?probe=64d768d709) | Feb 21, 2022 |
| ASUSTek       | TUF GAMING B550-PLUS        | Desktop     | [f6ac7c7952](https://linux-hardware.org/?probe=f6ac7c7952) | Feb 21, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [de98ed057a](https://linux-hardware.org/?probe=de98ed057a) | Feb 21, 2022 |
| MSI           | MPG B560I GAMING EDGE WI... | Desktop     | [62fc974ec7](https://linux-hardware.org/?probe=62fc974ec7) | Feb 21, 2022 |
| Pegatron      | 2AB5                        | Desktop     | [2bb0bac8e9](https://linux-hardware.org/?probe=2bb0bac8e9) | Feb 21, 2022 |
| TUXEDO        | P65xRP                      | Notebook    | [54fe2cd454](https://linux-hardware.org/?probe=54fe2cd454) | Feb 21, 2022 |
| Gigabyte      | H370M DS3H-CF               | Desktop     | [c6baf7375d](https://linux-hardware.org/?probe=c6baf7375d) | Feb 21, 2022 |
| Gigabyte      | Z68MX-UD2H-B3               | Desktop     | [2e649a1179](https://linux-hardware.org/?probe=2e649a1179) | Feb 21, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [ca3b04115c](https://linux-hardware.org/?probe=ca3b04115c) | Feb 20, 2022 |
| Alienware     | 0C92D0 A00                  | Desktop     | [5764fbfde4](https://linux-hardware.org/?probe=5764fbfde4) | Feb 20, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [d7cea444f3](https://linux-hardware.org/?probe=d7cea444f3) | Feb 20, 2022 |
| Lenovo        | IdeaPad N581 7505           | Notebook    | [cef4ec8fe6](https://linux-hardware.org/?probe=cef4ec8fe6) | Feb 20, 2022 |
| ASUSTek       | X751LK                      | Notebook    | [59056d9df8](https://linux-hardware.org/?probe=59056d9df8) | Feb 20, 2022 |
| ASRock        | N68-GS4 FX                  | Desktop     | [a73c8072f9](https://linux-hardware.org/?probe=a73c8072f9) | Feb 20, 2022 |
| ASUSTek       | X200CA                      | Notebook    | [eea123637a](https://linux-hardware.org/?probe=eea123637a) | Feb 20, 2022 |
| Lenovo        | B560 43308VG                | Notebook    | [609ffd75b7](https://linux-hardware.org/?probe=609ffd75b7) | Feb 20, 2022 |
| Packard Be... | TBGM01                      | Desktop     | [01fcf9c4ce](https://linux-hardware.org/?probe=01fcf9c4ce) | Feb 20, 2022 |
| Toshiba       | Satellite C650D             | Notebook    | [99c0e6257f](https://linux-hardware.org/?probe=99c0e6257f) | Feb 20, 2022 |
| Dell          | 0HY9JP A02                  | Desktop     | [3c4a78636b](https://linux-hardware.org/?probe=3c4a78636b) | Feb 20, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [100666467c](https://linux-hardware.org/?probe=100666467c) | Feb 20, 2022 |
| ASRock        | N68-GS4 FX                  | Desktop     | [a457ae32df](https://linux-hardware.org/?probe=a457ae32df) | Feb 20, 2022 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [b82091c19c](https://linux-hardware.org/?probe=b82091c19c) | Feb 20, 2022 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [24e82fe564](https://linux-hardware.org/?probe=24e82fe564) | Feb 20, 2022 |
| Apple         | MacBookAir3,1               | Notebook    | [48dcaa8622](https://linux-hardware.org/?probe=48dcaa8622) | Feb 20, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [7738c67892](https://linux-hardware.org/?probe=7738c67892) | Feb 20, 2022 |
| HP            | 304Bh                       | Desktop     | [5228a8de2d](https://linux-hardware.org/?probe=5228a8de2d) | Feb 20, 2022 |
| Supermicro    | X11SDV-8C-TP8F              | Server      | [9a0aaad7ed](https://linux-hardware.org/?probe=9a0aaad7ed) | Feb 20, 2022 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | Notebook    | [14748ba63b](https://linux-hardware.org/?probe=14748ba63b) | Feb 20, 2022 |
| HP            | EliteBook 850 G3            | Notebook    | [8fa5e6f026](https://linux-hardware.org/?probe=8fa5e6f026) | Feb 20, 2022 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [d521b9e2fa](https://linux-hardware.org/?probe=d521b9e2fa) | Feb 20, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [bcb5d92f02](https://linux-hardware.org/?probe=bcb5d92f02) | Feb 20, 2022 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [5b7a77242b](https://linux-hardware.org/?probe=5b7a77242b) | Feb 20, 2022 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [2d6eeb7dbc](https://linux-hardware.org/?probe=2d6eeb7dbc) | Feb 20, 2022 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [8e70b5fb30](https://linux-hardware.org/?probe=8e70b5fb30) | Feb 20, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [5ff1a9a4b3](https://linux-hardware.org/?probe=5ff1a9a4b3) | Feb 20, 2022 |
| ASUSTek       | K75VJ                       | Notebook    | [e0c07cf9d2](https://linux-hardware.org/?probe=e0c07cf9d2) | Feb 20, 2022 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [0f818bf6e7](https://linux-hardware.org/?probe=0f818bf6e7) | Feb 20, 2022 |
| Gigabyte      | EP35-DS4                    | Desktop     | [5810977ba5](https://linux-hardware.org/?probe=5810977ba5) | Feb 20, 2022 |
| Lenovo        | ThinkPad T470 20HES18R2C    | Notebook    | [ae520d865b](https://linux-hardware.org/?probe=ae520d865b) | Feb 20, 2022 |
| HP            | Pavilion dv9700             | Notebook    | [13e90c97af](https://linux-hardware.org/?probe=13e90c97af) | Feb 20, 2022 |
| ASUSTek       | VM62                        | Desktop     | [b94bd6bcf1](https://linux-hardware.org/?probe=b94bd6bcf1) | Feb 20, 2022 |
| HP            | Pavilion dv9700             | Notebook    | [b45ef36266](https://linux-hardware.org/?probe=b45ef36266) | Feb 20, 2022 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [6fd6345632](https://linux-hardware.org/?probe=6fd6345632) | Feb 20, 2022 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [f9923aebcb](https://linux-hardware.org/?probe=f9923aebcb) | Feb 20, 2022 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [9b8714532b](https://linux-hardware.org/?probe=9b8714532b) | Feb 20, 2022 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | Notebook    | [571c932872](https://linux-hardware.org/?probe=571c932872) | Feb 20, 2022 |
| Medion        | P6613                       | Notebook    | [43850e4c58](https://linux-hardware.org/?probe=43850e4c58) | Feb 20, 2022 |
| MSI           | MEG Z590I UNIFY             | Desktop     | [1656e263ab](https://linux-hardware.org/?probe=1656e263ab) | Feb 20, 2022 |
| ASRock        | J4205-ITX                   | Desktop     | [e7e09c80fa](https://linux-hardware.org/?probe=e7e09c80fa) | Feb 20, 2022 |
| Acer          | Aspire V5-573G              | Notebook    | [62bd52b74c](https://linux-hardware.org/?probe=62bd52b74c) | Feb 20, 2022 |
| Lex BayTra... | 2I385C                      | Notebook    | [380bbc4a32](https://linux-hardware.org/?probe=380bbc4a32) | Feb 19, 2022 |
| HP            | ProBook 6475b               | Notebook    | [d1ec585515](https://linux-hardware.org/?probe=d1ec585515) | Feb 19, 2022 |
| ASUSTek       | N76VZ                       | Notebook    | [2f54a2ead3](https://linux-hardware.org/?probe=2f54a2ead3) | Feb 19, 2022 |
| MSI           | X370 GAMING PLUS            | Desktop     | [07968f0946](https://linux-hardware.org/?probe=07968f0946) | Feb 19, 2022 |
| Wortmann      | Mobile 1511                 | Notebook    | [bc5fabbc04](https://linux-hardware.org/?probe=bc5fabbc04) | Feb 19, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [bca70f8674](https://linux-hardware.org/?probe=bca70f8674) | Feb 19, 2022 |
| ASRock        | H370M-ITX/ac                | Desktop     | [95b177e121](https://linux-hardware.org/?probe=95b177e121) | Feb 19, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [e58eb70913](https://linux-hardware.org/?probe=e58eb70913) | Feb 19, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [621f2c5bec](https://linux-hardware.org/?probe=621f2c5bec) | Feb 19, 2022 |
| Gigabyte      | GA-MA790XT-UD4P             | Desktop     | [f04139c372](https://linux-hardware.org/?probe=f04139c372) | Feb 19, 2022 |
| Packard Be... | ENLE11BZ                    | Notebook    | [f5aae267bc](https://linux-hardware.org/?probe=f5aae267bc) | Feb 19, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [1ad67d12e0](https://linux-hardware.org/?probe=1ad67d12e0) | Feb 19, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [5714c771cf](https://linux-hardware.org/?probe=5714c771cf) | Feb 19, 2022 |
| Gigabyte      | C246-WU4-CF                 | Desktop     | [e849c7b27b](https://linux-hardware.org/?probe=e849c7b27b) | Feb 19, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [f9daebc3cd](https://linux-hardware.org/?probe=f9daebc3cd) | Feb 19, 2022 |
| Nvidia        | Tegra                       | Soc         | [7cde4a4d40](https://linux-hardware.org/?probe=7cde4a4d40) | Feb 19, 2022 |
| MSI           | Z77A-GD65                   | Desktop     | [13dcc6145e](https://linux-hardware.org/?probe=13dcc6145e) | Feb 19, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [42d59b0801](https://linux-hardware.org/?probe=42d59b0801) | Feb 19, 2022 |
| Lenovo        | ThinkPad T61 6468AE1        | Notebook    | [3205d8494e](https://linux-hardware.org/?probe=3205d8494e) | Feb 19, 2022 |
| ASUSTek       | X756UXK                     | Notebook    | [b71ec18dba](https://linux-hardware.org/?probe=b71ec18dba) | Feb 19, 2022 |
| ASUSTek       | M50Vm                       | Notebook    | [c562a6a3ad](https://linux-hardware.org/?probe=c562a6a3ad) | Feb 19, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [bd096baf97](https://linux-hardware.org/?probe=bd096baf97) | Feb 19, 2022 |
| HP            | EliteBook 8540w (WD930EA... | Notebook    | [fff6280eed](https://linux-hardware.org/?probe=fff6280eed) | Feb 19, 2022 |
| ASUSTek       | H97-PLUS                    | Desktop     | [59eb7271ed](https://linux-hardware.org/?probe=59eb7271ed) | Feb 19, 2022 |
| ASUSTek       | H97-PLUS                    | Desktop     | [4d1f04bc66](https://linux-hardware.org/?probe=4d1f04bc66) | Feb 19, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [eccaa1c72e](https://linux-hardware.org/?probe=eccaa1c72e) | Feb 19, 2022 |
| Dell          | 0NW73C A00                  | Desktop     | [1ab4f3167b](https://linux-hardware.org/?probe=1ab4f3167b) | Feb 19, 2022 |
| ASUSTek       | TUF GAMING B550-PLUS        | Desktop     | [8b5be0871c](https://linux-hardware.org/?probe=8b5be0871c) | Feb 19, 2022 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | Notebook    | [49f5048540](https://linux-hardware.org/?probe=49f5048540) | Feb 19, 2022 |
| HP            | 3031h                       | Desktop     | [78b80c1159](https://linux-hardware.org/?probe=78b80c1159) | Feb 19, 2022 |
| Lenovo        | IdeaPad N581 7505           | Notebook    | [71d0987faf](https://linux-hardware.org/?probe=71d0987faf) | Feb 19, 2022 |
| Samsung       | SP55S                       | Notebook    | [3f39c45f19](https://linux-hardware.org/?probe=3f39c45f19) | Feb 19, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [c88beca866](https://linux-hardware.org/?probe=c88beca866) | Feb 19, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [16e742d300](https://linux-hardware.org/?probe=16e742d300) | Feb 19, 2022 |
| Acer          | Spin SP314-54N              | Convertible | [90e932e714](https://linux-hardware.org/?probe=90e932e714) | Feb 19, 2022 |
| Gigabyte      | B360M D2V                   | Desktop     | [7ddecfd5b6](https://linux-hardware.org/?probe=7ddecfd5b6) | Feb 19, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [16b6deff57](https://linux-hardware.org/?probe=16b6deff57) | Feb 19, 2022 |
| Acer          | Aspire 8943G                | Notebook    | [536e9e71da](https://linux-hardware.org/?probe=536e9e71da) | Feb 18, 2022 |
| Lenovo        | ThinkPad L430 2468CTO       | Notebook    | [9244a0f8f9](https://linux-hardware.org/?probe=9244a0f8f9) | Feb 18, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [f7adb86dce](https://linux-hardware.org/?probe=f7adb86dce) | Feb 18, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [6b77f8012b](https://linux-hardware.org/?probe=6b77f8012b) | Feb 18, 2022 |
| Lenovo        | ThinkPad P50 20EN0005GE     | Notebook    | [1f8abac9d7](https://linux-hardware.org/?probe=1f8abac9d7) | Feb 18, 2022 |
| Medion        | P7612                       | Notebook    | [7a8dc95cc8](https://linux-hardware.org/?probe=7a8dc95cc8) | Feb 18, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [74e488319b](https://linux-hardware.org/?probe=74e488319b) | Feb 18, 2022 |
| ASRock        | Z68 Extreme4 Gen3           | Desktop     | [91f7933c5b](https://linux-hardware.org/?probe=91f7933c5b) | Feb 18, 2022 |
| Apple         | MacBook10,1                 | Notebook    | [06c4fb71d0](https://linux-hardware.org/?probe=06c4fb71d0) | Feb 18, 2022 |
| Apple         | MacBook10,1                 | Notebook    | [ff5822c1cf](https://linux-hardware.org/?probe=ff5822c1cf) | Feb 18, 2022 |
| Lenovo        | ThinkPad T495 20NKS01Y00    | Notebook    | [76d3c2cfa2](https://linux-hardware.org/?probe=76d3c2cfa2) | Feb 18, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [0797e9e8e3](https://linux-hardware.org/?probe=0797e9e8e3) | Feb 18, 2022 |
| Acer          | Aspire A315-53              | Notebook    | [6134bb8cba](https://linux-hardware.org/?probe=6134bb8cba) | Feb 18, 2022 |
| Dell          | Inspiron 7773               | Notebook    | [f2f40a2b71](https://linux-hardware.org/?probe=f2f40a2b71) | Feb 18, 2022 |
| AZW           | SEi                         | Notebook    | [e6305c0c34](https://linux-hardware.org/?probe=e6305c0c34) | Feb 18, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [7814d1e2f8](https://linux-hardware.org/?probe=7814d1e2f8) | Feb 18, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [2bfd36f050](https://linux-hardware.org/?probe=2bfd36f050) | Feb 18, 2022 |
| MSI           | P55-GD80                    | Desktop     | [1b84542ad4](https://linux-hardware.org/?probe=1b84542ad4) | Feb 18, 2022 |
| Toshiba       | PORTEGE R600                | Notebook    | [b4dbc4297f](https://linux-hardware.org/?probe=b4dbc4297f) | Feb 18, 2022 |
| ASUSTek       | TUF GAMING B550-PLUS        | Desktop     | [d08ed1959b](https://linux-hardware.org/?probe=d08ed1959b) | Feb 18, 2022 |
| Fujitsu       | LIFEBOOK U9311X             | Convertible | [68ad6548f8](https://linux-hardware.org/?probe=68ad6548f8) | Feb 18, 2022 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [664d13320f](https://linux-hardware.org/?probe=664d13320f) | Feb 18, 2022 |
| Lenovo        | G710 20252                  | Notebook    | [d564ba78a8](https://linux-hardware.org/?probe=d564ba78a8) | Feb 18, 2022 |
| Lenovo        | SDK0J40700 WIN              | Desktop     | [01c12eb94c](https://linux-hardware.org/?probe=01c12eb94c) | Feb 18, 2022 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [a88902a823](https://linux-hardware.org/?probe=a88902a823) | Feb 18, 2022 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | Desktop     | [f064e4f947](https://linux-hardware.org/?probe=f064e4f947) | Feb 18, 2022 |
| Toshiba       | Satellite C50-A             | Notebook    | [ca857b9f5a](https://linux-hardware.org/?probe=ca857b9f5a) | Feb 18, 2022 |
| sunxi         | Banana Pi BPI-M2-Plus H3    | Soc         | [1f12724cce](https://linux-hardware.org/?probe=1f12724cce) | Feb 18, 2022 |
| Packard Be... | ENLK11BZ                    | Notebook    | [f4bd8ff9b0](https://linux-hardware.org/?probe=f4bd8ff9b0) | Feb 18, 2022 |
| ASRock        | A520M-HVS                   | Desktop     | [f9705ca187](https://linux-hardware.org/?probe=f9705ca187) | Feb 18, 2022 |
| Packard Be... | ENLK11BZ                    | Notebook    | [85f36d66f1](https://linux-hardware.org/?probe=85f36d66f1) | Feb 18, 2022 |
| ASRock        | A520M-HVS                   | Desktop     | [54887060c2](https://linux-hardware.org/?probe=54887060c2) | Feb 18, 2022 |
| LincPlus      | P1                          | Notebook    | [24e3b52251](https://linux-hardware.org/?probe=24e3b52251) | Feb 18, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [160f376cfa](https://linux-hardware.org/?probe=160f376cfa) | Feb 17, 2022 |
| Gigabyte      | B365M H                     | Desktop     | [b983a5173e](https://linux-hardware.org/?probe=b983a5173e) | Feb 17, 2022 |
| Gigabyte      | B365M H                     | Desktop     | [16b755cff8](https://linux-hardware.org/?probe=16b755cff8) | Feb 17, 2022 |
| ASUSTek       | X751LAB                     | Notebook    | [10ea8f6500](https://linux-hardware.org/?probe=10ea8f6500) | Feb 17, 2022 |
| Lenovo        | ThinkPad T430 2349H2G       | Notebook    | [f873bcc6c8](https://linux-hardware.org/?probe=f873bcc6c8) | Feb 17, 2022 |
| Acer          | Aspire 5749                 | Notebook    | [c2beca7751](https://linux-hardware.org/?probe=c2beca7751) | Feb 17, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [7cea4f8b0f](https://linux-hardware.org/?probe=7cea4f8b0f) | Feb 17, 2022 |
| Dell          | 0DR845                      | Desktop     | [1dd9b9acaa](https://linux-hardware.org/?probe=1dd9b9acaa) | Feb 17, 2022 |
| Lenovo        | G710 20252                  | Notebook    | [528af81a3a](https://linux-hardware.org/?probe=528af81a3a) | Feb 17, 2022 |
| ASUSTek       | TUF GAMING FX504GM_FX80G... | Notebook    | [e418af16aa](https://linux-hardware.org/?probe=e418af16aa) | Feb 17, 2022 |
| Lenovo        | G505s 20255                 | Notebook    | [2be9f6bed4](https://linux-hardware.org/?probe=2be9f6bed4) | Feb 17, 2022 |
| Acer          | Aspire M3420                | Desktop     | [93be723109](https://linux-hardware.org/?probe=93be723109) | Feb 17, 2022 |
| MSI           | Z77A-GD65                   | Desktop     | [75bab544df](https://linux-hardware.org/?probe=75bab544df) | Feb 17, 2022 |
| MSI           | CX600                       | Notebook    | [bbd815a6e9](https://linux-hardware.org/?probe=bbd815a6e9) | Feb 17, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [99909847e0](https://linux-hardware.org/?probe=99909847e0) | Feb 17, 2022 |
| HP            | Dratini                     | Notebook    | [bb3f3445ee](https://linux-hardware.org/?probe=bb3f3445ee) | Feb 17, 2022 |
| Intel         | DN2820FYK H24582-204        | Desktop     | [c79110bc16](https://linux-hardware.org/?probe=c79110bc16) | Feb 17, 2022 |
| Acer          | K8VM800MAE                  | Desktop     | [e4505f1541](https://linux-hardware.org/?probe=e4505f1541) | Feb 17, 2022 |
| Acer          | K8VM800MAE                  | Desktop     | [ac2f1dab87](https://linux-hardware.org/?probe=ac2f1dab87) | Feb 17, 2022 |
| Dell          | Inspiron 5505               | Notebook    | [ac3f9fa03e](https://linux-hardware.org/?probe=ac3f9fa03e) | Feb 17, 2022 |
| MSI           | Z170-A PRO                  | Desktop     | [9628754bf4](https://linux-hardware.org/?probe=9628754bf4) | Feb 17, 2022 |
| Dell          | 0J8G6F A03                  | Desktop     | [c4314fa1c4](https://linux-hardware.org/?probe=c4314fa1c4) | Feb 17, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [5becdcf643](https://linux-hardware.org/?probe=5becdcf643) | Feb 17, 2022 |
| Acer          | Extensa 215-51              | Notebook    | [e5599af3cc](https://linux-hardware.org/?probe=e5599af3cc) | Feb 17, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [fb47a70139](https://linux-hardware.org/?probe=fb47a70139) | Feb 17, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [56ca73dc6d](https://linux-hardware.org/?probe=56ca73dc6d) | Feb 17, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [d4b09f8302](https://linux-hardware.org/?probe=d4b09f8302) | Feb 17, 2022 |
| Intel         | NUC8BEB J72692-304          | Mini pc     | [4b198a6b46](https://linux-hardware.org/?probe=4b198a6b46) | Feb 17, 2022 |
| HP            | 8433 11                     | Desktop     | [879012c323](https://linux-hardware.org/?probe=879012c323) | Feb 17, 2022 |
| MSI           | A68HM GRENADE               | Desktop     | [ca74f33fe0](https://linux-hardware.org/?probe=ca74f33fe0) | Feb 17, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [3c099cd157](https://linux-hardware.org/?probe=3c099cd157) | Feb 17, 2022 |
| HP            | Presario CQ56               | Notebook    | [40d24470d0](https://linux-hardware.org/?probe=40d24470d0) | Feb 17, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [9f7425aac2](https://linux-hardware.org/?probe=9f7425aac2) | Feb 17, 2022 |
| Acer          | Predator G9-792             | Notebook    | [e516ba85b9](https://linux-hardware.org/?probe=e516ba85b9) | Feb 17, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [e8c4c665b1](https://linux-hardware.org/?probe=e8c4c665b1) | Feb 17, 2022 |
| Notebook      | W35xSTQ_370ST               | Notebook    | [dbace2cf5d](https://linux-hardware.org/?probe=dbace2cf5d) | Feb 17, 2022 |
| MSI           | Z77A-GD65                   | Desktop     | [b8f472be64](https://linux-hardware.org/?probe=b8f472be64) | Feb 17, 2022 |
| HP            | Laptop 17-by0xxx            | Notebook    | [6a79d148c8](https://linux-hardware.org/?probe=6a79d148c8) | Feb 17, 2022 |
| Packard Be... | EasyNote LS11HR             | Notebook    | [d8b9f8edb0](https://linux-hardware.org/?probe=d8b9f8edb0) | Feb 17, 2022 |
| ASUSTek       | GL702ZC                     | Notebook    | [4a213a20c0](https://linux-hardware.org/?probe=4a213a20c0) | Feb 17, 2022 |
| HP            | 8876 11                     | Desktop     | [4d3b19e49f](https://linux-hardware.org/?probe=4d3b19e49f) | Feb 17, 2022 |
| ASRock        | B660M Pro RS                | Desktop     | [e421d6584e](https://linux-hardware.org/?probe=e421d6584e) | Feb 17, 2022 |
| HP            | Laptop 17-by0xxx            | Notebook    | [432c2a8975](https://linux-hardware.org/?probe=432c2a8975) | Feb 16, 2022 |
| Lenovo        | ThinkPad X200 7459ZC2       | Notebook    | [897152c39c](https://linux-hardware.org/?probe=897152c39c) | Feb 16, 2022 |
| Toshiba       | Satellite C50-A             | Notebook    | [48ddc0e01d](https://linux-hardware.org/?probe=48ddc0e01d) | Feb 16, 2022 |
| Fujitsu       | LIFEBOOK A512               | Notebook    | [89c7cd2dd3](https://linux-hardware.org/?probe=89c7cd2dd3) | Feb 16, 2022 |
| ASUSTek       | M3A78-EM                    | Desktop     | [116a92ffa8](https://linux-hardware.org/?probe=116a92ffa8) | Feb 16, 2022 |
| ASUSTek       | Pro WS C621-64L SAGE Ser... | Desktop     | [922f3559c8](https://linux-hardware.org/?probe=922f3559c8) | Feb 16, 2022 |
| Biostar       | A68MD PRO                   | Desktop     | [da42cc4da7](https://linux-hardware.org/?probe=da42cc4da7) | Feb 16, 2022 |
| Dell          | 0HN7XN A00                  | Desktop     | [e5b4b833a4](https://linux-hardware.org/?probe=e5b4b833a4) | Feb 16, 2022 |
| Gigabyte      | P55-UD3L                    | Desktop     | [e7318489dd](https://linux-hardware.org/?probe=e7318489dd) | Feb 16, 2022 |
| Samsung       | N230                        | Notebook    | [f16e2ce417](https://linux-hardware.org/?probe=f16e2ce417) | Feb 16, 2022 |
| Samsung       | N230                        | Notebook    | [10be19ecbf](https://linux-hardware.org/?probe=10be19ecbf) | Feb 16, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [5a378e922a](https://linux-hardware.org/?probe=5a378e922a) | Feb 16, 2022 |
| Toshiba       | Satellite C870-19R          | Notebook    | [72755f69a8](https://linux-hardware.org/?probe=72755f69a8) | Feb 16, 2022 |
| Dell          | Latitude E6320              | Notebook    | [ae7b660be1](https://linux-hardware.org/?probe=ae7b660be1) | Feb 16, 2022 |
| HP            | 8433 11                     | Desktop     | [3e76b8876b](https://linux-hardware.org/?probe=3e76b8876b) | Feb 16, 2022 |
| Acer          | Aspire V3-771               | Notebook    | [1046915c3b](https://linux-hardware.org/?probe=1046915c3b) | Feb 16, 2022 |
| Lenovo        | ThinkPad T530 2394A11       | Notebook    | [c926008d79](https://linux-hardware.org/?probe=c926008d79) | Feb 16, 2022 |
| MSI           | H81M-E34                    | Desktop     | [d5d33c5ba1](https://linux-hardware.org/?probe=d5d33c5ba1) | Feb 16, 2022 |
| MSI           | Bravo 17 A4DDR              | Notebook    | [3dcfa13df7](https://linux-hardware.org/?probe=3dcfa13df7) | Feb 16, 2022 |
| HP            | 1495                        | Desktop     | [a66b522cfb](https://linux-hardware.org/?probe=a66b522cfb) | Feb 16, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [d8e8a1481a](https://linux-hardware.org/?probe=d8e8a1481a) | Feb 16, 2022 |
| ASUSTek       | Z97I-PLUS                   | Desktop     | [7da122cf5b](https://linux-hardware.org/?probe=7da122cf5b) | Feb 16, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [9abcb12076](https://linux-hardware.org/?probe=9abcb12076) | Feb 16, 2022 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [f3ee6f9dbb](https://linux-hardware.org/?probe=f3ee6f9dbb) | Feb 16, 2022 |
| Lenovo        | ThinkPad L460 20FVS07C00    | Notebook    | [e062302c48](https://linux-hardware.org/?probe=e062302c48) | Feb 16, 2022 |
| Lenovo        | ThinkPad X220 42912WU       | Notebook    | [05281aa81f](https://linux-hardware.org/?probe=05281aa81f) | Feb 16, 2022 |
| Lenovo        | ThinkPad X220 42912WU       | Notebook    | [1c04b9e65f](https://linux-hardware.org/?probe=1c04b9e65f) | Feb 16, 2022 |
| Gigabyte      | Z87X-UD4H-CF                | Desktop     | [b111f4af09](https://linux-hardware.org/?probe=b111f4af09) | Feb 16, 2022 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [9ef9950470](https://linux-hardware.org/?probe=9ef9950470) | Feb 15, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d9fab8e3ae](https://linux-hardware.org/?probe=d9fab8e3ae) | Feb 15, 2022 |
| ASUSTek       | P8P67                       | Desktop     | [e52f9b0748](https://linux-hardware.org/?probe=e52f9b0748) | Feb 15, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [0731118682](https://linux-hardware.org/?probe=0731118682) | Feb 15, 2022 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [af9220740f](https://linux-hardware.org/?probe=af9220740f) | Feb 15, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [1b2a216e13](https://linux-hardware.org/?probe=1b2a216e13) | Feb 15, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [752f501827](https://linux-hardware.org/?probe=752f501827) | Feb 15, 2022 |
| Fujitsu       | LIFEBOOK E556               | Notebook    | [b9f9511cb0](https://linux-hardware.org/?probe=b9f9511cb0) | Feb 15, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [40e4251b1c](https://linux-hardware.org/?probe=40e4251b1c) | Feb 15, 2022 |
| Toshiba       | Satellite C870-19R          | Notebook    | [4e0345b36d](https://linux-hardware.org/?probe=4e0345b36d) | Feb 15, 2022 |
| HP            | Notebook                    | Notebook    | [40c672794e](https://linux-hardware.org/?probe=40c672794e) | Feb 15, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [3db88acec8](https://linux-hardware.org/?probe=3db88acec8) | Feb 15, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [68f6b7dd88](https://linux-hardware.org/?probe=68f6b7dd88) | Feb 15, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [34d933c2f3](https://linux-hardware.org/?probe=34d933c2f3) | Feb 15, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [3442d4ea25](https://linux-hardware.org/?probe=3442d4ea25) | Feb 15, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [3bfd2622ae](https://linux-hardware.org/?probe=3bfd2622ae) | Feb 15, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [f65c6b2c80](https://linux-hardware.org/?probe=f65c6b2c80) | Feb 15, 2022 |
| Lenovo        | ThinkPad T450s 20BWS06K0... | Notebook    | [60cf03acd8](https://linux-hardware.org/?probe=60cf03acd8) | Feb 15, 2022 |
| Lenovo        | ThinkPad T450s 20BWS06K0... | Notebook    | [8305aa0d2e](https://linux-hardware.org/?probe=8305aa0d2e) | Feb 15, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [00241ec5d1](https://linux-hardware.org/?probe=00241ec5d1) | Feb 15, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [5fb9066caf](https://linux-hardware.org/?probe=5fb9066caf) | Feb 15, 2022 |
| Dell          | Latitude E7240              | Notebook    | [bed3e63b1e](https://linux-hardware.org/?probe=bed3e63b1e) | Feb 15, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [5026ea812a](https://linux-hardware.org/?probe=5026ea812a) | Feb 15, 2022 |
| Fujitsu       | LIFEBOOK A512               | Notebook    | [730023eb1b](https://linux-hardware.org/?probe=730023eb1b) | Feb 15, 2022 |
| Toshiba       | Satellite C870D-11F         | Notebook    | [eaac3ab809](https://linux-hardware.org/?probe=eaac3ab809) | Feb 14, 2022 |
| MSI           | Z77A-GD65                   | Desktop     | [c26a245a90](https://linux-hardware.org/?probe=c26a245a90) | Feb 14, 2022 |
| Fujitsu Si... | LIFEBOOK S6420              | Notebook    | [d42d70a45a](https://linux-hardware.org/?probe=d42d70a45a) | Feb 14, 2022 |
| Dell          | Latitude E6540              | Notebook    | [a06de7f66f](https://linux-hardware.org/?probe=a06de7f66f) | Feb 14, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [70a12c10dc](https://linux-hardware.org/?probe=70a12c10dc) | Feb 14, 2022 |
| Acer          | Aspire 8930                 | Notebook    | [863481c071](https://linux-hardware.org/?probe=863481c071) | Feb 14, 2022 |
| Acer          | Aspire 8930                 | Notebook    | [533ac86eee](https://linux-hardware.org/?probe=533ac86eee) | Feb 14, 2022 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [5f38fac8b4](https://linux-hardware.org/?probe=5f38fac8b4) | Feb 14, 2022 |
| Schenker      | XMG CORE (TGL/M21)          | Notebook    | [56e3cdba6d](https://linux-hardware.org/?probe=56e3cdba6d) | Feb 14, 2022 |
| Lenovo        | ThinkPad T410 2537AT1       | Notebook    | [7ecf503a63](https://linux-hardware.org/?probe=7ecf503a63) | Feb 14, 2022 |
| Fujitsu       | LIFEBOOK A3510              | Notebook    | [621c548147](https://linux-hardware.org/?probe=621c548147) | Feb 14, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [b1de32eb02](https://linux-hardware.org/?probe=b1de32eb02) | Feb 14, 2022 |
| Samsung       | 700T                        | Notebook    | [a8a433333d](https://linux-hardware.org/?probe=a8a433333d) | Feb 14, 2022 |
| Dell          | Latitude 5510               | Notebook    | [380cb3e46b](https://linux-hardware.org/?probe=380cb3e46b) | Feb 14, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [142f983ed2](https://linux-hardware.org/?probe=142f983ed2) | Feb 14, 2022 |
| ASUSTek       | X75VC                       | Notebook    | [3eb95222e2](https://linux-hardware.org/?probe=3eb95222e2) | Feb 14, 2022 |
| Dell          | Latitude 5510               | Notebook    | [37a6c67d71](https://linux-hardware.org/?probe=37a6c67d71) | Feb 14, 2022 |
| ASUSTek       | K52Je                       | Notebook    | [45a1a6ff08](https://linux-hardware.org/?probe=45a1a6ff08) | Feb 14, 2022 |
| HP            | 212B                        | Desktop     | [7ddf821817](https://linux-hardware.org/?probe=7ddf821817) | Feb 14, 2022 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | Notebook    | [c23130bb43](https://linux-hardware.org/?probe=c23130bb43) | Feb 14, 2022 |
| Acer          | Spin SP314-54N              | Convertible | [879969adee](https://linux-hardware.org/?probe=879969adee) | Feb 14, 2022 |
| Lenovo        | ThinkPad T460 20FMS0WN00    | Notebook    | [28be6b9f17](https://linux-hardware.org/?probe=28be6b9f17) | Feb 14, 2022 |
| Lenovo        | ThinkPad T460 20FMS0WN00    | Notebook    | [5819fc1b20](https://linux-hardware.org/?probe=5819fc1b20) | Feb 14, 2022 |
| Lenovo        | ThinkPad T495 20NK000MGE    | Notebook    | [af354b9537](https://linux-hardware.org/?probe=af354b9537) | Feb 14, 2022 |
| Lenovo        | ThinkPad T430 23476P9       | Notebook    | [e55e8897a7](https://linux-hardware.org/?probe=e55e8897a7) | Feb 14, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [2aad458cd3](https://linux-hardware.org/?probe=2aad458cd3) | Feb 14, 2022 |
| ASUSTek       | P8H61-M EVO                 | Desktop     | [40ed7abcc5](https://linux-hardware.org/?probe=40ed7abcc5) | Feb 14, 2022 |
| Gigabyte      | P55-UD3L                    | Desktop     | [bf852c386f](https://linux-hardware.org/?probe=bf852c386f) | Feb 14, 2022 |
| ASUSTek       | M3N78 PRO                   | Desktop     | [3625d4d1d0](https://linux-hardware.org/?probe=3625d4d1d0) | Feb 14, 2022 |
| ASUSTek       | PRIME B250-PRO              | Desktop     | [be377c733e](https://linux-hardware.org/?probe=be377c733e) | Feb 14, 2022 |
| Medion        | E7419 MD60025               | Notebook    | [dc41d8a6ad](https://linux-hardware.org/?probe=dc41d8a6ad) | Feb 14, 2022 |
| Lenovo        | V15-IGL 82C3                | Notebook    | [35d928e17b](https://linux-hardware.org/?probe=35d928e17b) | Feb 14, 2022 |
| Sony          | VPCEB3E1E                   | Notebook    | [a0be8de519](https://linux-hardware.org/?probe=a0be8de519) | Feb 13, 2022 |
| Lenovo        | ThinkPad T470 20HES18R2C    | Notebook    | [e267632853](https://linux-hardware.org/?probe=e267632853) | Feb 13, 2022 |
| Gigabyte      | M68M-S2P                    | Desktop     | [775639095e](https://linux-hardware.org/?probe=775639095e) | Feb 13, 2022 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [ae2c01b44b](https://linux-hardware.org/?probe=ae2c01b44b) | Feb 13, 2022 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | Notebook    | [5768ab0770](https://linux-hardware.org/?probe=5768ab0770) | Feb 13, 2022 |
| HARDKERNEL    | ODROID-H2                   | Desktop     | [c30826317d](https://linux-hardware.org/?probe=c30826317d) | Feb 13, 2022 |
| MSI           | B150I GAMING PRO AC         | Desktop     | [a69e146e71](https://linux-hardware.org/?probe=a69e146e71) | Feb 13, 2022 |
| MSI           | GV72 7RE                    | Notebook    | [d199f3e50a](https://linux-hardware.org/?probe=d199f3e50a) | Feb 13, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [eb68a95d51](https://linux-hardware.org/?probe=eb68a95d51) | Feb 13, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [95504fe909](https://linux-hardware.org/?probe=95504fe909) | Feb 13, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [a33ec560f6](https://linux-hardware.org/?probe=a33ec560f6) | Feb 13, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B3302FEA... | Convertible | [20d30ebe0b](https://linux-hardware.org/?probe=20d30ebe0b) | Feb 13, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [45c9189643](https://linux-hardware.org/?probe=45c9189643) | Feb 13, 2022 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [e87aaff114](https://linux-hardware.org/?probe=e87aaff114) | Feb 13, 2022 |
| Lenovo        | ThinkPad T530 24296KG       | Notebook    | [9940aacd34](https://linux-hardware.org/?probe=9940aacd34) | Feb 13, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [69c57efa90](https://linux-hardware.org/?probe=69c57efa90) | Feb 13, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [7c142a2edb](https://linux-hardware.org/?probe=7c142a2edb) | Feb 13, 2022 |
| Sony          | SVP1321L1EBI                | Notebook    | [b35a3fbfec](https://linux-hardware.org/?probe=b35a3fbfec) | Feb 13, 2022 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [990899de1e](https://linux-hardware.org/?probe=990899de1e) | Feb 13, 2022 |
| Intel         | NUC8BEB J72693-308          | Mini pc     | [dd2342ba11](https://linux-hardware.org/?probe=dd2342ba11) | Feb 13, 2022 |
| ASUSTek       | P8H61-M EVO                 | Desktop     | [94bcb91d02](https://linux-hardware.org/?probe=94bcb91d02) | Feb 13, 2022 |
| HP            | 255 G5                      | Notebook    | [a030b8f406](https://linux-hardware.org/?probe=a030b8f406) | Feb 13, 2022 |
| Medion        | Akoya THE TOUCH 10          | Notebook    | [220896c95e](https://linux-hardware.org/?probe=220896c95e) | Feb 13, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [6071bd2108](https://linux-hardware.org/?probe=6071bd2108) | Feb 13, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [30c1919c89](https://linux-hardware.org/?probe=30c1919c89) | Feb 13, 2022 |
| Sony          | SVF1521G6EW                 | Notebook    | [365ef21d2a](https://linux-hardware.org/?probe=365ef21d2a) | Feb 13, 2022 |
| Packard Be... | EasyNote LS11HR             | Notebook    | [3534b13bb3](https://linux-hardware.org/?probe=3534b13bb3) | Feb 13, 2022 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [c034584d73](https://linux-hardware.org/?probe=c034584d73) | Feb 13, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [186c62676c](https://linux-hardware.org/?probe=186c62676c) | Feb 13, 2022 |
| Toshiba       | Satellite L350              | Notebook    | [85b90b81ce](https://linux-hardware.org/?probe=85b90b81ce) | Feb 13, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [0d41a14486](https://linux-hardware.org/?probe=0d41a14486) | Feb 13, 2022 |
| HP            | ENVY Laptop 14-eb1xxx       | Notebook    | [e4d3cf0edd](https://linux-hardware.org/?probe=e4d3cf0edd) | Feb 13, 2022 |
| MSI           | B360M GAMING PLUS           | Desktop     | [6068e205c1](https://linux-hardware.org/?probe=6068e205c1) | Feb 13, 2022 |
| Acer          | Aspire E1-530               | Notebook    | [21e2a6f70a](https://linux-hardware.org/?probe=21e2a6f70a) | Feb 13, 2022 |
| Gigabyte      | H410M S2H V2                | Desktop     | [4dd3773193](https://linux-hardware.org/?probe=4dd3773193) | Feb 13, 2022 |
| HP            | Pavilion dm3                | Notebook    | [72e4b19e29](https://linux-hardware.org/?probe=72e4b19e29) | Feb 13, 2022 |
| Lenovo        | IdeaPad 330-17AST 81D7      | Notebook    | [0c52b3ab5c](https://linux-hardware.org/?probe=0c52b3ab5c) | Feb 13, 2022 |
| HP            | Laptop 17-ak0xx             | Notebook    | [874b22af5d](https://linux-hardware.org/?probe=874b22af5d) | Feb 13, 2022 |
| MSI           | A78-G41 PC Mate             | Desktop     | [38885f39bb](https://linux-hardware.org/?probe=38885f39bb) | Feb 13, 2022 |
| MSI           | A68HM GRENADE               | Desktop     | [ca0bc05e3d](https://linux-hardware.org/?probe=ca0bc05e3d) | Feb 13, 2022 |
| Acer          | Swift SF315-41              | Notebook    | [8e8ddcee99](https://linux-hardware.org/?probe=8e8ddcee99) | Feb 13, 2022 |
| Intel         | NUC5i7RYB H73774-101        | Mini pc     | [87a77e0618](https://linux-hardware.org/?probe=87a77e0618) | Feb 12, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3d94b9cb7b](https://linux-hardware.org/?probe=3d94b9cb7b) | Feb 12, 2022 |
| ASRock        | K8A780LM                    | Desktop     | [4ad26b4255](https://linux-hardware.org/?probe=4ad26b4255) | Feb 12, 2022 |
| ASUSTek       | PRIME H570M-PLUS            | Desktop     | [adc14fca30](https://linux-hardware.org/?probe=adc14fca30) | Feb 12, 2022 |
| ASRock        | K8A780LM                    | Desktop     | [d9641143f2](https://linux-hardware.org/?probe=d9641143f2) | Feb 12, 2022 |
| ASUSTek       | B150M-C                     | Desktop     | [40269e6b77](https://linux-hardware.org/?probe=40269e6b77) | Feb 12, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [393686a6c4](https://linux-hardware.org/?probe=393686a6c4) | Feb 12, 2022 |
| Gigabyte      | H81M-D2V                    | Desktop     | [1033adb0bf](https://linux-hardware.org/?probe=1033adb0bf) | Feb 12, 2022 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [bc22a75684](https://linux-hardware.org/?probe=bc22a75684) | Feb 12, 2022 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [00ffc660f1](https://linux-hardware.org/?probe=00ffc660f1) | Feb 12, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [cb9c4ddeb5](https://linux-hardware.org/?probe=cb9c4ddeb5) | Feb 12, 2022 |
| BESSTAR Te... | UM250 V1.0                  | Desktop     | [204eaf4081](https://linux-hardware.org/?probe=204eaf4081) | Feb 12, 2022 |
| ASUSTek       | B150M-C                     | Desktop     | [c4aa2fa626](https://linux-hardware.org/?probe=c4aa2fa626) | Feb 12, 2022 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [ef662fd605](https://linux-hardware.org/?probe=ef662fd605) | Feb 12, 2022 |
| HP            | Notebook                    | Notebook    | [7d0124e894](https://linux-hardware.org/?probe=7d0124e894) | Feb 12, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [9d3a4e4a04](https://linux-hardware.org/?probe=9d3a4e4a04) | Feb 12, 2022 |
| HP            | Compaq CQ58                 | Notebook    | [a7eac41f26](https://linux-hardware.org/?probe=a7eac41f26) | Feb 12, 2022 |
| ASRock        | 960GM-VGS3 FX               | Desktop     | [26ac1f4605](https://linux-hardware.org/?probe=26ac1f4605) | Feb 12, 2022 |
| TUXEDO        | N8xxEZ                      | Notebook    | [9293c685e7](https://linux-hardware.org/?probe=9293c685e7) | Feb 12, 2022 |
| HP            | Laptop 17-ak0xx             | Notebook    | [5ac054b0e2](https://linux-hardware.org/?probe=5ac054b0e2) | Feb 12, 2022 |
| Biostar       | AM1ML                       | Desktop     | [54e50bd790](https://linux-hardware.org/?probe=54e50bd790) | Feb 12, 2022 |
| Biostar       | AM1ML                       | Desktop     | [e933dbc718](https://linux-hardware.org/?probe=e933dbc718) | Feb 12, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [aac284c4db](https://linux-hardware.org/?probe=aac284c4db) | Feb 12, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [aaf3557539](https://linux-hardware.org/?probe=aaf3557539) | Feb 12, 2022 |
| Supermicro    | X10SDV-2C-TP4F              | Server      | [e60ec405af](https://linux-hardware.org/?probe=e60ec405af) | Feb 12, 2022 |
| Lenovo        | ThinkPad Edge E325 1297A... | Notebook    | [81d584f653](https://linux-hardware.org/?probe=81d584f653) | Feb 12, 2022 |
| ASUSTek       | WS C422 DC                  | Desktop     | [24c30b31f5](https://linux-hardware.org/?probe=24c30b31f5) | Feb 12, 2022 |
| Acer          | Aspire A317-53              | Notebook    | [32799e446c](https://linux-hardware.org/?probe=32799e446c) | Feb 12, 2022 |
| TUXEDO        | Pulse 14 Gen1               | Notebook    | [08833de386](https://linux-hardware.org/?probe=08833de386) | Feb 11, 2022 |
| Acer          | Aspire A317-53              | Notebook    | [adfe16b8de](https://linux-hardware.org/?probe=adfe16b8de) | Feb 11, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [62d94ae03d](https://linux-hardware.org/?probe=62d94ae03d) | Feb 11, 2022 |
| Gigabyte      | X399 AORUS XTREME-CF        | Desktop     | [562f2116cd](https://linux-hardware.org/?probe=562f2116cd) | Feb 11, 2022 |
| MSI           | H81M-P33                    | Desktop     | [e40a9cf57a](https://linux-hardware.org/?probe=e40a9cf57a) | Feb 11, 2022 |
| Lenovo        | ThinkPad T430 2351AK9       | Notebook    | [59d473ded9](https://linux-hardware.org/?probe=59d473ded9) | Feb 11, 2022 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [4f53e07ed1](https://linux-hardware.org/?probe=4f53e07ed1) | Feb 11, 2022 |
| MSI           | B250M BAZOOKA               | Desktop     | [4a8f0501a2](https://linux-hardware.org/?probe=4a8f0501a2) | Feb 11, 2022 |
| HP            | 1494                        | Desktop     | [b8af49b874](https://linux-hardware.org/?probe=b8af49b874) | Feb 11, 2022 |
| Dell          | Latitude E7450              | Notebook    | [d3eeb3ec1b](https://linux-hardware.org/?probe=d3eeb3ec1b) | Feb 11, 2022 |
| Dell          | G3 3590                     | Notebook    | [2e84266d29](https://linux-hardware.org/?probe=2e84266d29) | Feb 11, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [3f6c7b343f](https://linux-hardware.org/?probe=3f6c7b343f) | Feb 11, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [674524b893](https://linux-hardware.org/?probe=674524b893) | Feb 11, 2022 |
| Fujitsu       | D3348-A1 S26361-D3348-A1    | Desktop     | [267cf29034](https://linux-hardware.org/?probe=267cf29034) | Feb 11, 2022 |
| Toshiba       | Satellite C70D-B            | Notebook    | [da80f94d2d](https://linux-hardware.org/?probe=da80f94d2d) | Feb 11, 2022 |
| Lenovo        | ThinkPad T470 20HES18R2C    | Notebook    | [527186459e](https://linux-hardware.org/?probe=527186459e) | Feb 11, 2022 |
| Gigabyte      | H81M-D2V                    | Desktop     | [2146c426fa](https://linux-hardware.org/?probe=2146c426fa) | Feb 11, 2022 |
| MSI           | MAG Z390 TOMAHAWK           | Desktop     | [e58751112a](https://linux-hardware.org/?probe=e58751112a) | Feb 11, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [a36bb76b5e](https://linux-hardware.org/?probe=a36bb76b5e) | Feb 11, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [4cbfb2942d](https://linux-hardware.org/?probe=4cbfb2942d) | Feb 11, 2022 |
| ASUSTek       | 1001PXD                     | Notebook    | [4b2384eb8f](https://linux-hardware.org/?probe=4b2384eb8f) | Feb 11, 2022 |
| HP            | Pavilion dv8000 (RE428EA... | Notebook    | [2c68e5e29b](https://linux-hardware.org/?probe=2c68e5e29b) | Feb 11, 2022 |
| HP            | ProBook 655 G1              | Notebook    | [1c6a5c6e55](https://linux-hardware.org/?probe=1c6a5c6e55) | Feb 11, 2022 |
| HP            | Pavilion dv8000 (RE428EA... | Notebook    | [548187b430](https://linux-hardware.org/?probe=548187b430) | Feb 11, 2022 |
| Dell          | 0YXT71 A01                  | Desktop     | [aab6383ad8](https://linux-hardware.org/?probe=aab6383ad8) | Feb 11, 2022 |
| Gigabyte      | H87M-D3H                    | Desktop     | [50d11c7fd7](https://linux-hardware.org/?probe=50d11c7fd7) | Feb 11, 2022 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | Notebook    | [63be20cf71](https://linux-hardware.org/?probe=63be20cf71) | Feb 11, 2022 |
| ASUSTek       | X751SA                      | Notebook    | [007765d1b3](https://linux-hardware.org/?probe=007765d1b3) | Feb 11, 2022 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | Notebook    | [a7d5970d58](https://linux-hardware.org/?probe=a7d5970d58) | Feb 11, 2022 |
| Beelink       | Gemini N                    | Notebook    | [fa50b7bb95](https://linux-hardware.org/?probe=fa50b7bb95) | Feb 11, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [9e9b592889](https://linux-hardware.org/?probe=9e9b592889) | Feb 11, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [285b0fc2fd](https://linux-hardware.org/?probe=285b0fc2fd) | Feb 11, 2022 |
| Dell          | Latitude 5511               | Notebook    | [418c4bc399](https://linux-hardware.org/?probe=418c4bc399) | Feb 11, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d41fb38b28](https://linux-hardware.org/?probe=d41fb38b28) | Feb 11, 2022 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [13fe160642](https://linux-hardware.org/?probe=13fe160642) | Feb 11, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [bee4fb458f](https://linux-hardware.org/?probe=bee4fb458f) | Feb 11, 2022 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [156061600c](https://linux-hardware.org/?probe=156061600c) | Feb 11, 2022 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [8b833fe2a1](https://linux-hardware.org/?probe=8b833fe2a1) | Feb 11, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [c12a459084](https://linux-hardware.org/?probe=c12a459084) | Feb 11, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [73a1a64560](https://linux-hardware.org/?probe=73a1a64560) | Feb 11, 2022 |
| HP            | EliteBook 8530w             | Notebook    | [4588f74e2e](https://linux-hardware.org/?probe=4588f74e2e) | Feb 11, 2022 |
| Acer          | Predator PO3-630            | Desktop     | [96dccc1214](https://linux-hardware.org/?probe=96dccc1214) | Feb 11, 2022 |
| HP            | 650                         | Notebook    | [7369d6635b](https://linux-hardware.org/?probe=7369d6635b) | Feb 11, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | Notebook    | [0576901513](https://linux-hardware.org/?probe=0576901513) | Feb 11, 2022 |
| Gigabyte      | GA-MA785GMT-UD2H            | Desktop     | [362be85e1e](https://linux-hardware.org/?probe=362be85e1e) | Feb 11, 2022 |
| HP            | 2B2C                        | Desktop     | [e5b45f315c](https://linux-hardware.org/?probe=e5b45f315c) | Feb 11, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [0d80dc8143](https://linux-hardware.org/?probe=0d80dc8143) | Feb 11, 2022 |
| ASRock        | B550 Taichi                 | Desktop     | [ccf0482689](https://linux-hardware.org/?probe=ccf0482689) | Feb 11, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [1b98c3db08](https://linux-hardware.org/?probe=1b98c3db08) | Feb 11, 2022 |
| Acer          | Aspire V3-771               | Notebook    | [6d7e8d32fe](https://linux-hardware.org/?probe=6d7e8d32fe) | Feb 10, 2022 |
| HP            | 2B2C                        | Desktop     | [08d8d29478](https://linux-hardware.org/?probe=08d8d29478) | Feb 10, 2022 |
| Acer          | Aspire V3-771               | Notebook    | [369d44b5b9](https://linux-hardware.org/?probe=369d44b5b9) | Feb 10, 2022 |
| HP            | Presario CQ56               | Notebook    | [8dfee6fb14](https://linux-hardware.org/?probe=8dfee6fb14) | Feb 10, 2022 |
| MSI           | A320M PRO-VD/S              | Desktop     | [70fb79e62b](https://linux-hardware.org/?probe=70fb79e62b) | Feb 10, 2022 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [c462619a26](https://linux-hardware.org/?probe=c462619a26) | Feb 10, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [cb0abbfe2d](https://linux-hardware.org/?probe=cb0abbfe2d) | Feb 10, 2022 |
| ASUSTek       | P5Q-WS                      | Desktop     | [068af08645](https://linux-hardware.org/?probe=068af08645) | Feb 10, 2022 |
| Toshiba       | Satellite P200              | Notebook    | [31e65951de](https://linux-hardware.org/?probe=31e65951de) | Feb 10, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [aab268e083](https://linux-hardware.org/?probe=aab268e083) | Feb 10, 2022 |
| Medion        | H81H3-EM2 H81EM2W08.309     | Desktop     | [849ce8b82a](https://linux-hardware.org/?probe=849ce8b82a) | Feb 10, 2022 |
| Gigabyte      | Z690 AORUS ELITE DDR4       | Desktop     | [cdc87c7a4d](https://linux-hardware.org/?probe=cdc87c7a4d) | Feb 10, 2022 |
| Google        | Nami                        | Notebook    | [5f1ba9ab72](https://linux-hardware.org/?probe=5f1ba9ab72) | Feb 10, 2022 |
| Toshiba       | TECRA R950                  | Notebook    | [cb85483d3d](https://linux-hardware.org/?probe=cb85483d3d) | Feb 10, 2022 |
| ASRock        | 960GM/U3S3 FX               | Desktop     | [4225e4762c](https://linux-hardware.org/?probe=4225e4762c) | Feb 10, 2022 |
| ASUSTek       | M2N                         | Desktop     | [1f54a226be](https://linux-hardware.org/?probe=1f54a226be) | Feb 10, 2022 |
| Lenovo        | Yoga 500-15IBD 80N6         | Notebook    | [33a40b952e](https://linux-hardware.org/?probe=33a40b952e) | Feb 10, 2022 |
| PC Engines    | APU2                        | Desktop     | [e82abd224c](https://linux-hardware.org/?probe=e82abd224c) | Feb 10, 2022 |
| MSI           | MS-7502 Fab D               | Desktop     | [16d13ffcd0](https://linux-hardware.org/?probe=16d13ffcd0) | Feb 10, 2022 |
| AZW           | GTR V01                     | Mini pc     | [1b95862ca6](https://linux-hardware.org/?probe=1b95862ca6) | Feb 10, 2022 |
| MSI           | X58 Pro                     | Desktop     | [b2b7d3ff51](https://linux-hardware.org/?probe=b2b7d3ff51) | Feb 10, 2022 |
| Samsung       | N150/N210/N220              | Notebook    | [62ec97c0fb](https://linux-hardware.org/?probe=62ec97c0fb) | Feb 10, 2022 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [afb3c1d02c](https://linux-hardware.org/?probe=afb3c1d02c) | Feb 10, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [ba9d045c2d](https://linux-hardware.org/?probe=ba9d045c2d) | Feb 10, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [1382b7bcc6](https://linux-hardware.org/?probe=1382b7bcc6) | Feb 10, 2022 |
| HP            | Compaq Presario CQ71        | Notebook    | [497c6a5a22](https://linux-hardware.org/?probe=497c6a5a22) | Feb 10, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [cdc67cf287](https://linux-hardware.org/?probe=cdc67cf287) | Feb 10, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [9b2e1bb715](https://linux-hardware.org/?probe=9b2e1bb715) | Feb 10, 2022 |
| Acer          | Aspire TC-895 V:1.0         | Desktop     | [fb0408c4ea](https://linux-hardware.org/?probe=fb0408c4ea) | Feb 10, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [5836ccecc2](https://linux-hardware.org/?probe=5836ccecc2) | Feb 10, 2022 |
| Supermicro    | X10SDV-2C-TP4F              | Server      | [e761a368c3](https://linux-hardware.org/?probe=e761a368c3) | Feb 10, 2022 |
| Acer          | Veriton M4630G V:1.0        | Desktop     | [d0c6871bff](https://linux-hardware.org/?probe=d0c6871bff) | Feb 10, 2022 |
| Lenovo        | ThinkPad T460 20FMS07000    | Notebook    | [9a91ce673b](https://linux-hardware.org/?probe=9a91ce673b) | Feb 10, 2022 |
| ASRock        | J3455M                      | Desktop     | [ad065cc2d7](https://linux-hardware.org/?probe=ad065cc2d7) | Feb 10, 2022 |
| ASUSTek       | A320M-C                     | Desktop     | [11443172e0](https://linux-hardware.org/?probe=11443172e0) | Feb 10, 2022 |
| Lenovo        | Unknown                     | Notebook    | [a3a3ea2bd9](https://linux-hardware.org/?probe=a3a3ea2bd9) | Feb 10, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [fd3d0e2409](https://linux-hardware.org/?probe=fd3d0e2409) | Feb 09, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [a45f27f8f3](https://linux-hardware.org/?probe=a45f27f8f3) | Feb 09, 2022 |
| Lenovo        | ThinkPad L530 24813QG       | Notebook    | [c051e2ad9b](https://linux-hardware.org/?probe=c051e2ad9b) | Feb 09, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [afc31097cd](https://linux-hardware.org/?probe=afc31097cd) | Feb 09, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [8df3c1d7cb](https://linux-hardware.org/?probe=8df3c1d7cb) | Feb 09, 2022 |
| Lenovo        | ThinkPad T430 2349U2B       | Notebook    | [dd76d59ffd](https://linux-hardware.org/?probe=dd76d59ffd) | Feb 09, 2022 |
| Acer          | Aspire XC-895 V:1.0         | Desktop     | [56bdbd5cc9](https://linux-hardware.org/?probe=56bdbd5cc9) | Feb 09, 2022 |
| Lenovo        | ThinkPad T430 23501B3       | Notebook    | [565edc6010](https://linux-hardware.org/?probe=565edc6010) | Feb 09, 2022 |
| Acer          | Veriton M4610G              | Desktop     | [ca02feda72](https://linux-hardware.org/?probe=ca02feda72) | Feb 09, 2022 |
| Lenovo        | ThinkPad T480s 20L8S3FG0... | Notebook    | [3a6e35daab](https://linux-hardware.org/?probe=3a6e35daab) | Feb 09, 2022 |
| Fujitsu       | LIFEBOOK NH532              | Notebook    | [b161688ec9](https://linux-hardware.org/?probe=b161688ec9) | Feb 09, 2022 |
| ASRock        | Z77 Extreme4                | Desktop     | [ef5bb8ff46](https://linux-hardware.org/?probe=ef5bb8ff46) | Feb 09, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [38bb8e64f6](https://linux-hardware.org/?probe=38bb8e64f6) | Feb 09, 2022 |
| ASUSTek       | 1005PXD                     | Notebook    | [bf74331771](https://linux-hardware.org/?probe=bf74331771) | Feb 09, 2022 |
| MSI           | H81M-P33                    | Desktop     | [d45239c6f0](https://linux-hardware.org/?probe=d45239c6f0) | Feb 09, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [e6177878f8](https://linux-hardware.org/?probe=e6177878f8) | Feb 09, 2022 |
| PC Special... | PA70Hx                      | Notebook    | [c42b9bab78](https://linux-hardware.org/?probe=c42b9bab78) | Feb 09, 2022 |
| Lenovo        | V320-17IKB 81CN             | Notebook    | [07f4b5fa29](https://linux-hardware.org/?probe=07f4b5fa29) | Feb 09, 2022 |
| ASUSTek       | M11AD                       | Desktop     | [a6fd984676](https://linux-hardware.org/?probe=a6fd984676) | Feb 09, 2022 |
| Toshiba       | Satellite P200              | Notebook    | [f5c17b2b2a](https://linux-hardware.org/?probe=f5c17b2b2a) | Feb 09, 2022 |
| ASRock        | AB350 Pro4                  | Desktop     | [1564cdd40b](https://linux-hardware.org/?probe=1564cdd40b) | Feb 09, 2022 |
| Packard Be... | FMP55                       | Desktop     | [f83c583918](https://linux-hardware.org/?probe=f83c583918) | Feb 09, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [6c540fe1cb](https://linux-hardware.org/?probe=6c540fe1cb) | Feb 09, 2022 |
| Dell          | Inspiron 7706 2n1           | Convertible | [60c47d2f55](https://linux-hardware.org/?probe=60c47d2f55) | Feb 09, 2022 |
| Acer          | Aspire M3870                | Desktop     | [e718b5d2e4](https://linux-hardware.org/?probe=e718b5d2e4) | Feb 09, 2022 |
| ASRock        | 960GM/U3S3 FX               | Desktop     | [2660c70aaf](https://linux-hardware.org/?probe=2660c70aaf) | Feb 09, 2022 |
| ASUSTek       | E202SA                      | Notebook    | [ced358c593](https://linux-hardware.org/?probe=ced358c593) | Feb 09, 2022 |
| Gigabyte      | 990XA-UD3                   | Desktop     | [7e801d22d8](https://linux-hardware.org/?probe=7e801d22d8) | Feb 09, 2022 |
| Lenovo        | ThinkPad T430s 2356H83      | Notebook    | [a5201c533e](https://linux-hardware.org/?probe=a5201c533e) | Feb 09, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [ee8d9394ff](https://linux-hardware.org/?probe=ee8d9394ff) | Feb 09, 2022 |
| Dell          | 0YJPT1 A00                  | Desktop     | [455ada7882](https://linux-hardware.org/?probe=455ada7882) | Feb 09, 2022 |
| HP            | EliteBook 2170p             | Notebook    | [8abee6201f](https://linux-hardware.org/?probe=8abee6201f) | Feb 09, 2022 |
| Packard Be... | EasyNote LJ65               | Notebook    | [c93188ee11](https://linux-hardware.org/?probe=c93188ee11) | Feb 09, 2022 |
| Lenovo        | ThinkCentre A70z 0401G6G    | Desktop     | [96fedec8a8](https://linux-hardware.org/?probe=96fedec8a8) | Feb 09, 2022 |
| Wortmann      | TERRA_MOBILE_1512/1712      | Notebook    | [6715b531e2](https://linux-hardware.org/?probe=6715b531e2) | Feb 09, 2022 |
| Acer          | Swift SF314-59              | Notebook    | [67a0a393d1](https://linux-hardware.org/?probe=67a0a393d1) | Feb 09, 2022 |
| Unknown       | Unknown                     | Notebook    | [736a64df69](https://linux-hardware.org/?probe=736a64df69) | Feb 09, 2022 |
| Fujitsu       | LIFEBOOK E5510              | Notebook    | [1d2114c1b6](https://linux-hardware.org/?probe=1d2114c1b6) | Feb 09, 2022 |
| Fujitsu       | LIFEBOOK E5510              | Notebook    | [34c2c0477f](https://linux-hardware.org/?probe=34c2c0477f) | Feb 09, 2022 |
| Acer          | Aspire A515-44              | Notebook    | [22f1b96e9a](https://linux-hardware.org/?probe=22f1b96e9a) | Feb 09, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [010f1c23a9](https://linux-hardware.org/?probe=010f1c23a9) | Feb 09, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [b596d9fdb1](https://linux-hardware.org/?probe=b596d9fdb1) | Feb 09, 2022 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [5cda79bc7f](https://linux-hardware.org/?probe=5cda79bc7f) | Feb 09, 2022 |
| Acer          | Aspire TC-895 V:1.0         | Desktop     | [4fe66f8af6](https://linux-hardware.org/?probe=4fe66f8af6) | Feb 09, 2022 |
| Dell          | 0J3C2F A02                  | Desktop     | [2a3e957626](https://linux-hardware.org/?probe=2a3e957626) | Feb 09, 2022 |
| MSI           | MS-168A                     | Notebook    | [12e8387951](https://linux-hardware.org/?probe=12e8387951) | Feb 09, 2022 |
| Gigabyte      | H81M-D2V                    | Desktop     | [3e5f48037c](https://linux-hardware.org/?probe=3e5f48037c) | Feb 09, 2022 |
| ASUSTek       | B150M-A/M.2                 | Desktop     | [3098c1fdf3](https://linux-hardware.org/?probe=3098c1fdf3) | Feb 09, 2022 |
| MSI           | MPG Z590 GAMING FORCE       | Desktop     | [961be2a608](https://linux-hardware.org/?probe=961be2a608) | Feb 09, 2022 |
| MSI           | MPG Z590 GAMING FORCE       | Desktop     | [4ab26645c2](https://linux-hardware.org/?probe=4ab26645c2) | Feb 09, 2022 |
| Dell          | Precision 3520              | Notebook    | [c2e3e54c45](https://linux-hardware.org/?probe=c2e3e54c45) | Feb 09, 2022 |
| ASRock        | G31M-GS                     | Desktop     | [b6e2355249](https://linux-hardware.org/?probe=b6e2355249) | Feb 09, 2022 |
| Fujitsu       | D3403-A1 S26361-D3403-A1    | Desktop     | [e44d50036a](https://linux-hardware.org/?probe=e44d50036a) | Feb 09, 2022 |
| Lenovo        | ThinkPad T460p 20FXS0MF0... | Notebook    | [4071e2b845](https://linux-hardware.org/?probe=4071e2b845) | Feb 09, 2022 |
| Alienware     | m15 Ryzen Ed. R5            | Notebook    | [d13b0ff958](https://linux-hardware.org/?probe=d13b0ff958) | Feb 08, 2022 |
| MSI           | 970A-G43 PLUS               | Desktop     | [39a6b91358](https://linux-hardware.org/?probe=39a6b91358) | Feb 08, 2022 |
| Acer          | Aspire 6935                 | Notebook    | [d0dd380298](https://linux-hardware.org/?probe=d0dd380298) | Feb 08, 2022 |
| Fujitsu Si... | D2811-A1 S26361-D2811-A1    | Desktop     | [c2c63c372d](https://linux-hardware.org/?probe=c2c63c372d) | Feb 08, 2022 |
| Unknown       | Amlogic Meson GXL (S905X... | Soc         | [71f0e328a1](https://linux-hardware.org/?probe=71f0e328a1) | Feb 08, 2022 |
| Acer          | Aspire A515-44              | Notebook    | [618a9f3a35](https://linux-hardware.org/?probe=618a9f3a35) | Feb 08, 2022 |
| Lenovo        | ThinkPad W500 40624DG       | Notebook    | [2d9ffc1ce5](https://linux-hardware.org/?probe=2d9ffc1ce5) | Feb 08, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [692e311416](https://linux-hardware.org/?probe=692e311416) | Feb 08, 2022 |
| Medion        | P2A4-EM                     | Desktop     | [4af039380f](https://linux-hardware.org/?probe=4af039380f) | Feb 08, 2022 |
| Lenovo        | ThinkPad SL510 28477MG      | Notebook    | [8c6f03c8f7](https://linux-hardware.org/?probe=8c6f03c8f7) | Feb 08, 2022 |
| Acer          | Aspire 7740                 | Notebook    | [3963a3b387](https://linux-hardware.org/?probe=3963a3b387) | Feb 08, 2022 |
| Lenovo        | IdeaPad S206 2638           | Notebook    | [704b267347](https://linux-hardware.org/?probe=704b267347) | Feb 08, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [cd6d825a3e](https://linux-hardware.org/?probe=cd6d825a3e) | Feb 08, 2022 |
| Pegatron      | 2AB6                        | Desktop     | [1700ea2cb1](https://linux-hardware.org/?probe=1700ea2cb1) | Feb 08, 2022 |
| MSI           | B75A-G43                    | Desktop     | [5decf8afd5](https://linux-hardware.org/?probe=5decf8afd5) | Feb 08, 2022 |
| Medion        | MS-7748                     | Desktop     | [51b6c04c53](https://linux-hardware.org/?probe=51b6c04c53) | Feb 08, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [bb826e0f4e](https://linux-hardware.org/?probe=bb826e0f4e) | Feb 08, 2022 |
| Lenovo        | ThinkPad T420 4180AT9       | Notebook    | [d83b7599cb](https://linux-hardware.org/?probe=d83b7599cb) | Feb 08, 2022 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [0808be878f](https://linux-hardware.org/?probe=0808be878f) | Feb 08, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [8f66106772](https://linux-hardware.org/?probe=8f66106772) | Feb 08, 2022 |
| Samsung       | 600B4B/600B5B               | Notebook    | [2558403513](https://linux-hardware.org/?probe=2558403513) | Feb 08, 2022 |
| Packard Be... | TBGM01                      | Desktop     | [20ab04387b](https://linux-hardware.org/?probe=20ab04387b) | Feb 08, 2022 |
| MSI           | B250M PRO-VDH               | Desktop     | [264a4470eb](https://linux-hardware.org/?probe=264a4470eb) | Feb 08, 2022 |
| Dell          | 0Y2MRG A00                  | Desktop     | [2503dd3cc9](https://linux-hardware.org/?probe=2503dd3cc9) | Feb 08, 2022 |
| HP            | 18E5                        | Desktop     | [f47102a5ea](https://linux-hardware.org/?probe=f47102a5ea) | Feb 08, 2022 |
| Lenovo        | ThinkPad SL510 28752NG      | Notebook    | [eafad796e8](https://linux-hardware.org/?probe=eafad796e8) | Feb 08, 2022 |
| Lenovo        | IdeaPad 110-17IKB 80VK      | Notebook    | [df89a1b937](https://linux-hardware.org/?probe=df89a1b937) | Feb 08, 2022 |
| Medion        | H81H3-EM2 H81EM2W08.309     | Desktop     | [d15b5662dc](https://linux-hardware.org/?probe=d15b5662dc) | Feb 08, 2022 |
| Medion        | Akoya P2214T                | Notebook    | [55708cb128](https://linux-hardware.org/?probe=55708cb128) | Feb 08, 2022 |
| Samsung       | 600B4B/600B5B               | Notebook    | [f37984fec2](https://linux-hardware.org/?probe=f37984fec2) | Feb 08, 2022 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [6d72583104](https://linux-hardware.org/?probe=6d72583104) | Feb 08, 2022 |
| Packard Be... | EasyNote LM98               | Notebook    | [21d535f4e4](https://linux-hardware.org/?probe=21d535f4e4) | Feb 08, 2022 |
| Intel         | NUC6i3SYB H81132-502        | Mini pc     | [db86e412b7](https://linux-hardware.org/?probe=db86e412b7) | Feb 08, 2022 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [4158d10717](https://linux-hardware.org/?probe=4158d10717) | Feb 08, 2022 |
| Lenovo        | MAHOBAY                     | Desktop     | [5939855fc2](https://linux-hardware.org/?probe=5939855fc2) | Feb 08, 2022 |
| Dell          | Latitude 5520               | Notebook    | [4c6abde0d6](https://linux-hardware.org/?probe=4c6abde0d6) | Feb 08, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [0b17c19b0f](https://linux-hardware.org/?probe=0b17c19b0f) | Feb 08, 2022 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [1ce92ab181](https://linux-hardware.org/?probe=1ce92ab181) | Feb 08, 2022 |
| Gigabyte      | Z87X-UD3H-CF                | Desktop     | [507a073b3b](https://linux-hardware.org/?probe=507a073b3b) | Feb 08, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [935de1698b](https://linux-hardware.org/?probe=935de1698b) | Feb 08, 2022 |
| TUXEDO        | InfinityBook S 14 Gen6      | Notebook    | [3d7b583aeb](https://linux-hardware.org/?probe=3d7b583aeb) | Feb 08, 2022 |
| Gigabyte      | H87-HD3                     | Desktop     | [8262493e8d](https://linux-hardware.org/?probe=8262493e8d) | Feb 08, 2022 |
| Lenovo        | ThinkPad T420s 4174NEG      | Notebook    | [dbb4a7778e](https://linux-hardware.org/?probe=dbb4a7778e) | Feb 08, 2022 |
| HP            | G6000 (GH831EA#ABD)         | Notebook    | [26992ff697](https://linux-hardware.org/?probe=26992ff697) | Feb 08, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [539119f529](https://linux-hardware.org/?probe=539119f529) | Feb 08, 2022 |
| Acer          | TravelMate 5760G            | Notebook    | [3024952eba](https://linux-hardware.org/?probe=3024952eba) | Feb 08, 2022 |
| HP            | 339A                        | Desktop     | [55b76d666c](https://linux-hardware.org/?probe=55b76d666c) | Feb 08, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [d2d157214f](https://linux-hardware.org/?probe=d2d157214f) | Feb 08, 2022 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [e1f5370987](https://linux-hardware.org/?probe=e1f5370987) | Feb 08, 2022 |
| Dell          | Latitude E4300              | Notebook    | [07ce1c5924](https://linux-hardware.org/?probe=07ce1c5924) | Feb 08, 2022 |
| Acer          | Aspire XC-886 V:2.0         | Desktop     | [44cd92d342](https://linux-hardware.org/?probe=44cd92d342) | Feb 08, 2022 |
| Fujitsu       | D3432-A1 S26361-D3432-A1    | Desktop     | [76f58a410b](https://linux-hardware.org/?probe=76f58a410b) | Feb 08, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [decf9c65a0](https://linux-hardware.org/?probe=decf9c65a0) | Feb 08, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [f0ffadac92](https://linux-hardware.org/?probe=f0ffadac92) | Feb 08, 2022 |
| ASRock        | A320M-HDV                   | Desktop     | [1090fc46ed](https://linux-hardware.org/?probe=1090fc46ed) | Feb 08, 2022 |
| HP            | 2B2C                        | Desktop     | [524718f4ab](https://linux-hardware.org/?probe=524718f4ab) | Feb 08, 2022 |
| Intel         | DZ68DB AAG27985-104         | Desktop     | [bc0462d8e3](https://linux-hardware.org/?probe=bc0462d8e3) | Feb 08, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [df943fa94a](https://linux-hardware.org/?probe=df943fa94a) | Feb 08, 2022 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [ccc2ed8c61](https://linux-hardware.org/?probe=ccc2ed8c61) | Feb 08, 2022 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | Notebook    | [397136d976](https://linux-hardware.org/?probe=397136d976) | Feb 08, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [3192836e87](https://linux-hardware.org/?probe=3192836e87) | Feb 08, 2022 |
| ASRock        | 970 Extreme4                | Desktop     | [ec794a0697](https://linux-hardware.org/?probe=ec794a0697) | Feb 08, 2022 |
| Gigabyte      | Z87X-UD3H-CF                | Desktop     | [7fb23c35de](https://linux-hardware.org/?probe=7fb23c35de) | Feb 08, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [1f6b5440d5](https://linux-hardware.org/?probe=1f6b5440d5) | Feb 08, 2022 |
| HP            | 8446                        | All in one  | [46a47ab08e](https://linux-hardware.org/?probe=46a47ab08e) | Feb 08, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [f63e17bd4c](https://linux-hardware.org/?probe=f63e17bd4c) | Feb 08, 2022 |
| ASUSTek       | M4A87TD EVO                 | Desktop     | [ba1c658949](https://linux-hardware.org/?probe=ba1c658949) | Feb 08, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [6ddacf7875](https://linux-hardware.org/?probe=6ddacf7875) | Feb 08, 2022 |
| Acer          | Aspire E5-774G              | Notebook    | [791321d27d](https://linux-hardware.org/?probe=791321d27d) | Feb 08, 2022 |
| Fujitsu       | LIFEBOOK U9310X             | Convertible | [372f02f59c](https://linux-hardware.org/?probe=372f02f59c) | Feb 08, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [422c043d76](https://linux-hardware.org/?probe=422c043d76) | Feb 08, 2022 |
| MSI           | GP60 2PE                    | Notebook    | [e597f61177](https://linux-hardware.org/?probe=e597f61177) | Feb 08, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [2dd47c0a4b](https://linux-hardware.org/?probe=2dd47c0a4b) | Feb 08, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [6fc44d8cf2](https://linux-hardware.org/?probe=6fc44d8cf2) | Feb 08, 2022 |
| ASRock        | H67M-GE/HT                  | Desktop     | [c804a0cb49](https://linux-hardware.org/?probe=c804a0cb49) | Feb 08, 2022 |
| ASUSTek       | P53E                        | Notebook    | [b05ea988a5](https://linux-hardware.org/?probe=b05ea988a5) | Feb 08, 2022 |
| Lenovo        | G580 2189                   | Notebook    | [12cb40d9b7](https://linux-hardware.org/?probe=12cb40d9b7) | Feb 08, 2022 |
| Acer          | Nitro AN517-51              | Notebook    | [250845433c](https://linux-hardware.org/?probe=250845433c) | Feb 08, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [b23b568543](https://linux-hardware.org/?probe=b23b568543) | Feb 08, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [6eeae24799](https://linux-hardware.org/?probe=6eeae24799) | Feb 08, 2022 |
| ASRock        | Z77 Extreme4                | Desktop     | [b9391856c6](https://linux-hardware.org/?probe=b9391856c6) | Feb 08, 2022 |
| Gigabyte      | H81M-D2W                    | Desktop     | [43a458cd6d](https://linux-hardware.org/?probe=43a458cd6d) | Feb 08, 2022 |
| Dell          | Latitude E7440              | Notebook    | [e244c28777](https://linux-hardware.org/?probe=e244c28777) | Feb 08, 2022 |
| Lenovo        | B51-35 80LH                 | Notebook    | [4dc8595d0d](https://linux-hardware.org/?probe=4dc8595d0d) | Feb 08, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [739bf4f36a](https://linux-hardware.org/?probe=739bf4f36a) | Feb 08, 2022 |
| Samsung       | RF510/RF410/RF710           | Notebook    | [8bb90d9533](https://linux-hardware.org/?probe=8bb90d9533) | Feb 08, 2022 |
| HP            | ENVY Laptop 17-ch0xxx       | Notebook    | [d2034ed9f7](https://linux-hardware.org/?probe=d2034ed9f7) | Feb 08, 2022 |
| Gigabyte      | H510M S2H                   | Desktop     | [24368cd6ce](https://linux-hardware.org/?probe=24368cd6ce) | Feb 08, 2022 |
| Gigabyte      | Z490M                       | Desktop     | [f61241414c](https://linux-hardware.org/?probe=f61241414c) | Feb 08, 2022 |
| MSI           | Z370 GAMING PRO CARBON      | Desktop     | [2485a2de04](https://linux-hardware.org/?probe=2485a2de04) | Feb 08, 2022 |
| Morshow       | rev1.0                      | All in one  | [10e8b5b5bd](https://linux-hardware.org/?probe=10e8b5b5bd) | Feb 08, 2022 |
| Gigabyte      | GA-78LMT-USB3 x.x           | Desktop     | [0defb36db4](https://linux-hardware.org/?probe=0defb36db4) | Feb 08, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [b400a64d30](https://linux-hardware.org/?probe=b400a64d30) | Feb 07, 2022 |
| Dell          | Vostro 5490                 | Notebook    | [011e0963bd](https://linux-hardware.org/?probe=011e0963bd) | Feb 07, 2022 |
| HP            | Pavilion 17                 | Notebook    | [6343416eef](https://linux-hardware.org/?probe=6343416eef) | Feb 07, 2022 |
| Apple         | MacBookPro4,1               | Notebook    | [87e9ca3a01](https://linux-hardware.org/?probe=87e9ca3a01) | Feb 07, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [2bf75fae6b](https://linux-hardware.org/?probe=2bf75fae6b) | Feb 07, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [26ae09cc1a](https://linux-hardware.org/?probe=26ae09cc1a) | Feb 07, 2022 |
| Medion        | MS-7646                     | Desktop     | [2102f0dbc0](https://linux-hardware.org/?probe=2102f0dbc0) | Feb 07, 2022 |
| Acer          | Swift SF113-31              | Notebook    | [04cad1ea2f](https://linux-hardware.org/?probe=04cad1ea2f) | Feb 07, 2022 |
| Gigabyte      | Z68XP-UD3P                  | Desktop     | [e442030d39](https://linux-hardware.org/?probe=e442030d39) | Feb 07, 2022 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [4605034148](https://linux-hardware.org/?probe=4605034148) | Feb 07, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [b45a25dc18](https://linux-hardware.org/?probe=b45a25dc18) | Feb 07, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [5dbb969bd8](https://linux-hardware.org/?probe=5dbb969bd8) | Feb 07, 2022 |
| Dataton       | WATCHPAX 3362               | Notebook    | [a46a99f5f7](https://linux-hardware.org/?probe=a46a99f5f7) | Feb 07, 2022 |
| Lenovo        | ThinkPad SL410 2842AKG      | Notebook    | [d5e2c893f5](https://linux-hardware.org/?probe=d5e2c893f5) | Feb 07, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [dd43a073ac](https://linux-hardware.org/?probe=dd43a073ac) | Feb 07, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [e7524a8c81](https://linux-hardware.org/?probe=e7524a8c81) | Feb 07, 2022 |
| Acer          | TravelMate 8172             | Notebook    | [76e402e3d6](https://linux-hardware.org/?probe=76e402e3d6) | Feb 07, 2022 |
| HP            | ProBook 430 G2              | Notebook    | [789e7207f3](https://linux-hardware.org/?probe=789e7207f3) | Feb 07, 2022 |
| ASUSTek       | N56VZ                       | Notebook    | [b1702aa9ef](https://linux-hardware.org/?probe=b1702aa9ef) | Feb 07, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [34a6010fb2](https://linux-hardware.org/?probe=34a6010fb2) | Feb 07, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [33521d7a03](https://linux-hardware.org/?probe=33521d7a03) | Feb 07, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [d018a94552](https://linux-hardware.org/?probe=d018a94552) | Feb 07, 2022 |
| TUXEDO        | InfinityBook Pro 15 v4      | Notebook    | [46ad65f3ca](https://linux-hardware.org/?probe=46ad65f3ca) | Feb 07, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V6555        | Notebook    | [7131b16e91](https://linux-hardware.org/?probe=7131b16e91) | Feb 07, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [f619840852](https://linux-hardware.org/?probe=f619840852) | Feb 07, 2022 |
| Medion        | H81H3-EM2                   | Desktop     | [22d484c88a](https://linux-hardware.org/?probe=22d484c88a) | Feb 07, 2022 |
| Dell          | 0HR330                      | Desktop     | [564cd3050e](https://linux-hardware.org/?probe=564cd3050e) | Feb 07, 2022 |
| Lenovo        | SKYBAY SDK0J40700 WIN 32... | Desktop     | [54ebd54640](https://linux-hardware.org/?probe=54ebd54640) | Feb 07, 2022 |
| Toshiba       | PORTEGE Z30-C               | Notebook    | [e5376ce528](https://linux-hardware.org/?probe=e5376ce528) | Feb 07, 2022 |
| HP            | 8643 SMVB                   | Desktop     | [f6fe9d077a](https://linux-hardware.org/?probe=f6fe9d077a) | Feb 07, 2022 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [a7b70904a2](https://linux-hardware.org/?probe=a7b70904a2) | Feb 07, 2022 |
| MSI           | B150M BAZOOKA               | Desktop     | [1aa14df65c](https://linux-hardware.org/?probe=1aa14df65c) | Feb 07, 2022 |
| ASUSTek       | K56CM                       | Notebook    | [0e8b8d95e4](https://linux-hardware.org/?probe=0e8b8d95e4) | Feb 07, 2022 |
| ASUSTek       | H110M-R                     | Desktop     | [4ba54a77df](https://linux-hardware.org/?probe=4ba54a77df) | Feb 07, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [9ab57d4641](https://linux-hardware.org/?probe=9ab57d4641) | Feb 07, 2022 |
| Acer          | Aspire 5732Z                | Notebook    | [bc1767bd42](https://linux-hardware.org/?probe=bc1767bd42) | Feb 07, 2022 |
| ASUSTek       | PN40                        | Mini pc     | [1264eac747](https://linux-hardware.org/?probe=1264eac747) | Feb 07, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [baa251b3db](https://linux-hardware.org/?probe=baa251b3db) | Feb 07, 2022 |
| Lenovo        | 102F NO DPK                 | Desktop     | [ef9434937d](https://linux-hardware.org/?probe=ef9434937d) | Feb 07, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [8233b1191c](https://linux-hardware.org/?probe=8233b1191c) | Feb 07, 2022 |
| Lenovo        | ThinkPad X13 Yoga Gen 2 ... | Convertible | [661baafcd7](https://linux-hardware.org/?probe=661baafcd7) | Feb 07, 2022 |
| ASUSTek       | P55VA                       | Notebook    | [b6cdbbcb90](https://linux-hardware.org/?probe=b6cdbbcb90) | Feb 07, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [9e2a944be5](https://linux-hardware.org/?probe=9e2a944be5) | Feb 07, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [776a8f55b3](https://linux-hardware.org/?probe=776a8f55b3) | Feb 07, 2022 |
| ASRock        | A320M Pro4 R2.0             | Desktop     | [aeb7d17744](https://linux-hardware.org/?probe=aeb7d17744) | Feb 07, 2022 |
| ASUSTek       | ROG STRIX B360-H GAMING     | Desktop     | [92d9fdcc97](https://linux-hardware.org/?probe=92d9fdcc97) | Feb 07, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [c473a69c44](https://linux-hardware.org/?probe=c473a69c44) | Feb 07, 2022 |
| HP            | Pavilion dv7                | Notebook    | [e8cd45b30d](https://linux-hardware.org/?probe=e8cd45b30d) | Feb 07, 2022 |
| ASRock        | X570 Extreme4               | Desktop     | [2046886414](https://linux-hardware.org/?probe=2046886414) | Feb 07, 2022 |
| MSI           | GF75 Thin 10SDR             | Notebook    | [12d6260c75](https://linux-hardware.org/?probe=12d6260c75) | Feb 07, 2022 |
| ASRock        | X570 Extreme4               | Desktop     | [662f470f73](https://linux-hardware.org/?probe=662f470f73) | Feb 07, 2022 |
| Intel         | NUC7i5BNB J31144-304        | Mini pc     | [6434338413](https://linux-hardware.org/?probe=6434338413) | Feb 07, 2022 |
| HP            | 81B3                        | Desktop     | [aecaad32ad](https://linux-hardware.org/?probe=aecaad32ad) | Feb 07, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [77691e80a4](https://linux-hardware.org/?probe=77691e80a4) | Feb 07, 2022 |
| ASUSTek       | 901                         | Notebook    | [77c14174fd](https://linux-hardware.org/?probe=77c14174fd) | Feb 06, 2022 |
| HP            | 1497                        | Desktop     | [2a41e081da](https://linux-hardware.org/?probe=2a41e081da) | Feb 06, 2022 |
| Fujitsu Si... | AMILO Pa 1538               | Notebook    | [5715780bfc](https://linux-hardware.org/?probe=5715780bfc) | Feb 06, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [587efdf773](https://linux-hardware.org/?probe=587efdf773) | Feb 06, 2022 |
| Acer          | Aspire VN7-792G             | Notebook    | [cc47c7e512](https://linux-hardware.org/?probe=cc47c7e512) | Feb 06, 2022 |
| ASRock        | H510M-HDV/M.2               | Desktop     | [11b7d331bc](https://linux-hardware.org/?probe=11b7d331bc) | Feb 06, 2022 |
| MSI           | 760GA-P43                   | Desktop     | [6212c219c8](https://linux-hardware.org/?probe=6212c219c8) | Feb 06, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [4a7d691fa6](https://linux-hardware.org/?probe=4a7d691fa6) | Feb 06, 2022 |
| Lenovo        | NO DPK                      | Desktop     | [4bb7cedbd8](https://linux-hardware.org/?probe=4bb7cedbd8) | Feb 06, 2022 |
| Packard Be... | TBGM01                      | Desktop     | [295ffc3ec6](https://linux-hardware.org/?probe=295ffc3ec6) | Feb 06, 2022 |
| Dell          | Latitude E6530              | Notebook    | [ba102745b3](https://linux-hardware.org/?probe=ba102745b3) | Feb 06, 2022 |
| Lenovo        | ThinkCentre M91p 7052A9G    | Desktop     | [0375c86d72](https://linux-hardware.org/?probe=0375c86d72) | Feb 06, 2022 |
| Dell          | Latitude E6410              | Notebook    | [e8e62d3cde](https://linux-hardware.org/?probe=e8e62d3cde) | Feb 06, 2022 |
| Fujitsu       | D3403-A1 S26361-D3403-A1    | Desktop     | [adcbe6fd5f](https://linux-hardware.org/?probe=adcbe6fd5f) | Feb 06, 2022 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [79d2578788](https://linux-hardware.org/?probe=79d2578788) | Feb 06, 2022 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [2aa19eb2b7](https://linux-hardware.org/?probe=2aa19eb2b7) | Feb 06, 2022 |
| ASRock        | Z68 Extreme4 Gen3           | Desktop     | [29ea90b598](https://linux-hardware.org/?probe=29ea90b598) | Feb 06, 2022 |
| Packard Be... | GA-T671MG                   | Desktop     | [6b8d22e40e](https://linux-hardware.org/?probe=6b8d22e40e) | Feb 06, 2022 |
| Lenovo        | ThinkPad X260 20F5S0V400    | Notebook    | [78266452a2](https://linux-hardware.org/?probe=78266452a2) | Feb 06, 2022 |
| IBM           | ThinkPad T43 2668BU7        | Notebook    | [2586bf5e87](https://linux-hardware.org/?probe=2586bf5e87) | Feb 06, 2022 |
| Notebook      | W35xSTQ_370ST               | Notebook    | [eefc90186a](https://linux-hardware.org/?probe=eefc90186a) | Feb 06, 2022 |
| Notebook      | W35xSTQ_370ST               | Notebook    | [c9302cd36e](https://linux-hardware.org/?probe=c9302cd36e) | Feb 06, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [f1f4bcd2bc](https://linux-hardware.org/?probe=f1f4bcd2bc) | Feb 06, 2022 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | Desktop     | [06f1cfec0c](https://linux-hardware.org/?probe=06f1cfec0c) | Feb 06, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [7a203bf128](https://linux-hardware.org/?probe=7a203bf128) | Feb 06, 2022 |
| Gigabyte      | G1.Sniper Z97               | Desktop     | [5ef683a8ed](https://linux-hardware.org/?probe=5ef683a8ed) | Feb 06, 2022 |
| Dell          | 0C27VV A02                  | Desktop     | [f6bb9b0ffd](https://linux-hardware.org/?probe=f6bb9b0ffd) | Feb 06, 2022 |
| ASRock        | H570M Pro4                  | Desktop     | [0e3a001264](https://linux-hardware.org/?probe=0e3a001264) | Feb 06, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [425dcf3bb9](https://linux-hardware.org/?probe=425dcf3bb9) | Feb 06, 2022 |
| HP            | Pavilion g7                 | Notebook    | [6e6d2c79fd](https://linux-hardware.org/?probe=6e6d2c79fd) | Feb 06, 2022 |
| HP            | Pavilion g7                 | Notebook    | [334aee9a72](https://linux-hardware.org/?probe=334aee9a72) | Feb 06, 2022 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [36c068678e](https://linux-hardware.org/?probe=36c068678e) | Feb 06, 2022 |
| Dell          | Latitude 7370               | Notebook    | [f308a9e24e](https://linux-hardware.org/?probe=f308a9e24e) | Feb 06, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [429dd68374](https://linux-hardware.org/?probe=429dd68374) | Feb 06, 2022 |
| Dell          | Latitude E4310              | Notebook    | [50190cb420](https://linux-hardware.org/?probe=50190cb420) | Feb 06, 2022 |
| Gigabyte      | P55-UD3R                    | Desktop     | [a3398260e2](https://linux-hardware.org/?probe=a3398260e2) | Feb 05, 2022 |
| Lenovo        | ThinkPad T470 20HES18R2C    | Notebook    | [4598d6b2bb](https://linux-hardware.org/?probe=4598d6b2bb) | Feb 05, 2022 |
| Supermicro    | A1SRM-2758F                 | Desktop     | [33b8806332](https://linux-hardware.org/?probe=33b8806332) | Feb 05, 2022 |
| Lenovo        | ThinkPad T495 20NK000MGE    | Notebook    | [5783821de9](https://linux-hardware.org/?probe=5783821de9) | Feb 05, 2022 |
| Lenovo        | Flex 2-15D 20377            | Notebook    | [deb06aeda3](https://linux-hardware.org/?probe=deb06aeda3) | Feb 05, 2022 |
| Acer          | Predator PO3-630            | Desktop     | [7d12bf5399](https://linux-hardware.org/?probe=7d12bf5399) | Feb 05, 2022 |
| Dell          | Inspiron 7773               | Notebook    | [c99ba0c5b7](https://linux-hardware.org/?probe=c99ba0c5b7) | Feb 05, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [b8aa657ab7](https://linux-hardware.org/?probe=b8aa657ab7) | Feb 05, 2022 |
| Lenovo        | ThinkPad T495 20NK000MGE    | Notebook    | [d1f7916bfd](https://linux-hardware.org/?probe=d1f7916bfd) | Feb 05, 2022 |
| Dell          | Precision 5560              | Notebook    | [f4b2c34d3c](https://linux-hardware.org/?probe=f4b2c34d3c) | Feb 05, 2022 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [92200b80f7](https://linux-hardware.org/?probe=92200b80f7) | Feb 05, 2022 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [f960601cd0](https://linux-hardware.org/?probe=f960601cd0) | Feb 05, 2022 |
| Lenovo        | ThinkPad E490 20N80029GE    | Notebook    | [463f54f91a](https://linux-hardware.org/?probe=463f54f91a) | Feb 05, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [70125d2629](https://linux-hardware.org/?probe=70125d2629) | Feb 05, 2022 |
| Lenovo        | G70-70 80HW002UGE           | Notebook    | [9f901c16b5](https://linux-hardware.org/?probe=9f901c16b5) | Feb 05, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [2fb86c0c90](https://linux-hardware.org/?probe=2fb86c0c90) | Feb 05, 2022 |
| Dell          | 0T568R A00                  | Desktop     | [78286bc201](https://linux-hardware.org/?probe=78286bc201) | Feb 05, 2022 |
| Supermicro    | X9DRW                       | Desktop     | [432d4db3ea](https://linux-hardware.org/?probe=432d4db3ea) | Feb 05, 2022 |
| Lenovo        | ThinkStation S30 056834G    | Desktop     | [654f88d25b](https://linux-hardware.org/?probe=654f88d25b) | Feb 05, 2022 |
| Dell          | 0J190T A00                  | Desktop     | [14c0b99201](https://linux-hardware.org/?probe=14c0b99201) | Feb 05, 2022 |
| Dell          | Precision M4700             | Notebook    | [5de24590cc](https://linux-hardware.org/?probe=5de24590cc) | Feb 05, 2022 |
| Lenovo        | G550 2958                   | Notebook    | [e23451d062](https://linux-hardware.org/?probe=e23451d062) | Feb 05, 2022 |
| MSI           | Z270I GAMING PRO CARBON ... | Desktop     | [424f798e37](https://linux-hardware.org/?probe=424f798e37) | Feb 05, 2022 |
| Acer          | Swift SF314-41              | Notebook    | [61007dacfd](https://linux-hardware.org/?probe=61007dacfd) | Feb 05, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [a147de0139](https://linux-hardware.org/?probe=a147de0139) | Feb 05, 2022 |
| Lenovo        | G550 2958                   | Notebook    | [f3966e661a](https://linux-hardware.org/?probe=f3966e661a) | Feb 05, 2022 |
| ASUSTek       | H110M-R                     | Desktop     | [db1ac3b47e](https://linux-hardware.org/?probe=db1ac3b47e) | Feb 05, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [b8f7e7d9d8](https://linux-hardware.org/?probe=b8f7e7d9d8) | Feb 05, 2022 |
| Lenovo        | G550 2958                   | Notebook    | [a933b9c8f4](https://linux-hardware.org/?probe=a933b9c8f4) | Feb 05, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [652229b720](https://linux-hardware.org/?probe=652229b720) | Feb 05, 2022 |
| Fujitsu       | LIFEBOOK E754               | Notebook    | [1c3771e62d](https://linux-hardware.org/?probe=1c3771e62d) | Feb 05, 2022 |
| Toshiba       | Satellite L300              | Notebook    | [24713a7953](https://linux-hardware.org/?probe=24713a7953) | Feb 05, 2022 |
| Sony          | VPCF115FM                   | Notebook    | [c3ab12f992](https://linux-hardware.org/?probe=c3ab12f992) | Feb 05, 2022 |
| Sony          | VPCF22C5E                   | Notebook    | [1887e093ef](https://linux-hardware.org/?probe=1887e093ef) | Feb 05, 2022 |
| Gigabyte      | GA-MA785GMT-UD2H            | Desktop     | [71245e433d](https://linux-hardware.org/?probe=71245e433d) | Feb 05, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [ed9e69a65f](https://linux-hardware.org/?probe=ed9e69a65f) | Feb 05, 2022 |
| ASUSTek       | X751SA                      | Notebook    | [c3a63f9d86](https://linux-hardware.org/?probe=c3a63f9d86) | Feb 04, 2022 |
| Fujitsu       | D3128-A1 S26361-D3128-A1    | Desktop     | [80996b75ff](https://linux-hardware.org/?probe=80996b75ff) | Feb 04, 2022 |
| Fujitsu       | LIFEBOOK E556               | Notebook    | [58ec473b99](https://linux-hardware.org/?probe=58ec473b99) | Feb 04, 2022 |
| Dell          | Latitude 7370               | Notebook    | [2a5373b0f9](https://linux-hardware.org/?probe=2a5373b0f9) | Feb 04, 2022 |
| HP            | Pavilion 15                 | Notebook    | [fd92bbd20e](https://linux-hardware.org/?probe=fd92bbd20e) | Feb 04, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [46ba4fcc12](https://linux-hardware.org/?probe=46ba4fcc12) | Feb 04, 2022 |
| LG Electro... | X170-LS10K                  | Notebook    | [903d819a69](https://linux-hardware.org/?probe=903d819a69) | Feb 04, 2022 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [5b34840f92](https://linux-hardware.org/?probe=5b34840f92) | Feb 04, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [1a0186c0a7](https://linux-hardware.org/?probe=1a0186c0a7) | Feb 04, 2022 |
| Medion        | P6816                       | Notebook    | [7ff5ab5b0f](https://linux-hardware.org/?probe=7ff5ab5b0f) | Feb 04, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [d30cab784e](https://linux-hardware.org/?probe=d30cab784e) | Feb 04, 2022 |
| Framework     | Laptop                      | Notebook    | [64e6669cbc](https://linux-hardware.org/?probe=64e6669cbc) | Feb 04, 2022 |
| WeiBu         | rev1.0                      | All in one  | [4cbad8a144](https://linux-hardware.org/?probe=4cbad8a144) | Feb 04, 2022 |
| Fujitsu       | LIFEBOOK A3510              | Notebook    | [09f190d4b4](https://linux-hardware.org/?probe=09f190d4b4) | Feb 04, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [7f87e3773a](https://linux-hardware.org/?probe=7f87e3773a) | Feb 04, 2022 |
| ASUSTek       | B150M-C                     | Desktop     | [237bbb0cf5](https://linux-hardware.org/?probe=237bbb0cf5) | Feb 04, 2022 |
| ASRock        | 970 Extreme3                | Desktop     | [2ea42468c2](https://linux-hardware.org/?probe=2ea42468c2) | Feb 04, 2022 |
| Fujitsu       | LIFEBOOK A3510              | Notebook    | [abe18af5e7](https://linux-hardware.org/?probe=abe18af5e7) | Feb 04, 2022 |
| ASUSTek       | 901                         | Notebook    | [972a6c0937](https://linux-hardware.org/?probe=972a6c0937) | Feb 04, 2022 |
| ASUSTek       | 901                         | Notebook    | [27a497fdf8](https://linux-hardware.org/?probe=27a497fdf8) | Feb 04, 2022 |
| Schenker      | XMG CORE 14 (XCO14M20)      | Notebook    | [a4839e7109](https://linux-hardware.org/?probe=a4839e7109) | Feb 04, 2022 |
| Dell          | Latitude E6510              | Notebook    | [cd2f303041](https://linux-hardware.org/?probe=cd2f303041) | Feb 04, 2022 |
| Toshiba       | TECRA A11                   | Notebook    | [d4ea43cacd](https://linux-hardware.org/?probe=d4ea43cacd) | Feb 04, 2022 |
| HP            | 2B2C                        | Desktop     | [45c409ba35](https://linux-hardware.org/?probe=45c409ba35) | Feb 04, 2022 |
| ASRockRack    | X470D4U2/1N1                | Desktop     | [735bc0f806](https://linux-hardware.org/?probe=735bc0f806) | Feb 04, 2022 |
| Medion        | E2292                       | Convertible | [10a64531f1](https://linux-hardware.org/?probe=10a64531f1) | Feb 04, 2022 |
| Acer          | Aspire 8940G                | Notebook    | [686119ea77](https://linux-hardware.org/?probe=686119ea77) | Feb 03, 2022 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [48688703fe](https://linux-hardware.org/?probe=48688703fe) | Feb 03, 2022 |
| HC            | HCAR357-MI V1.0             | Desktop     | [37a019edd2](https://linux-hardware.org/?probe=37a019edd2) | Feb 03, 2022 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [5ceb1517d8](https://linux-hardware.org/?probe=5ceb1517d8) | Feb 03, 2022 |
| Dell          | Latitude E6530              | Notebook    | [a465763aa6](https://linux-hardware.org/?probe=a465763aa6) | Feb 03, 2022 |
| MSI           | H81M-E34                    | Desktop     | [0c134a78ad](https://linux-hardware.org/?probe=0c134a78ad) | Feb 03, 2022 |
| Acer          | Aspire ES1-571              | Notebook    | [80e97bbb78](https://linux-hardware.org/?probe=80e97bbb78) | Feb 03, 2022 |
| Foxconn       | NETBOX nT-435/535 Ver       | Desktop     | [c7d50db62b](https://linux-hardware.org/?probe=c7d50db62b) | Feb 03, 2022 |
| Foxconn       | 2A8C                        | Desktop     | [3c8e7bd3eb](https://linux-hardware.org/?probe=3c8e7bd3eb) | Feb 03, 2022 |
| Foxconn       | NETBOX nT-435/535 Ver       | Desktop     | [2ee2be7ccf](https://linux-hardware.org/?probe=2ee2be7ccf) | Feb 03, 2022 |
| HP            | 82A5                        | Mini pc     | [c47d9b3ae0](https://linux-hardware.org/?probe=c47d9b3ae0) | Feb 03, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [e79d569eac](https://linux-hardware.org/?probe=e79d569eac) | Feb 03, 2022 |
| Notebook      | W35xSTQ_370ST               | Notebook    | [ceedb7d678](https://linux-hardware.org/?probe=ceedb7d678) | Feb 03, 2022 |
| HP            | 0AECh D                     | Desktop     | [0faad8b8f3](https://linux-hardware.org/?probe=0faad8b8f3) | Feb 03, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [e02c6336d6](https://linux-hardware.org/?probe=e02c6336d6) | Feb 03, 2022 |
| Lenovo        | IdeaPadFlex 5 15ALC05 82... | Convertible | [8cbd3411bb](https://linux-hardware.org/?probe=8cbd3411bb) | Feb 03, 2022 |
| Dell          | 0XR1GT A00                  | Desktop     | [436259c69f](https://linux-hardware.org/?probe=436259c69f) | Feb 03, 2022 |
| Gigabyte      | P43-ES3G                    | Desktop     | [2c8817d959](https://linux-hardware.org/?probe=2c8817d959) | Feb 03, 2022 |
| ASRock        | A320M-DGS                   | Desktop     | [c8857db260](https://linux-hardware.org/?probe=c8857db260) | Feb 03, 2022 |
| ASRock        | A320M-DGS                   | Desktop     | [be8b394e63](https://linux-hardware.org/?probe=be8b394e63) | Feb 03, 2022 |
| Lenovo        | IdeaPad U330p 20267         | Notebook    | [b8645533ae](https://linux-hardware.org/?probe=b8645533ae) | Feb 02, 2022 |
| MSI           | B550M PRO                   | Desktop     | [bf3292945e](https://linux-hardware.org/?probe=bf3292945e) | Feb 02, 2022 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [a5f676a32a](https://linux-hardware.org/?probe=a5f676a32a) | Feb 02, 2022 |
| Dell          | XPS 13 9350                 | Notebook    | [ab4b14a2fd](https://linux-hardware.org/?probe=ab4b14a2fd) | Feb 02, 2022 |
| Dell          | Latitude E6400              | Notebook    | [c55769f459](https://linux-hardware.org/?probe=c55769f459) | Feb 02, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [4297068908](https://linux-hardware.org/?probe=4297068908) | Feb 02, 2022 |
| Fujitsu Si... | MS-7504VP-PV                | Desktop     | [8b92af27e3](https://linux-hardware.org/?probe=8b92af27e3) | Feb 02, 2022 |
| ASUSTek       | ZenBook UX434FAC_UX434FA    | Notebook    | [c5cf391447](https://linux-hardware.org/?probe=c5cf391447) | Feb 02, 2022 |
| Dell          | Latitude 14 Rugged (5404... | Notebook    | [e416e71401](https://linux-hardware.org/?probe=e416e71401) | Feb 02, 2022 |
| Acer          | Aspire R7-572               | Notebook    | [cc4a5e9f7d](https://linux-hardware.org/?probe=cc4a5e9f7d) | Feb 02, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [2707a539f1](https://linux-hardware.org/?probe=2707a539f1) | Feb 02, 2022 |
| Lenovo        | G710 20252                  | Notebook    | [5683d776e0](https://linux-hardware.org/?probe=5683d776e0) | Feb 02, 2022 |
| HP            | 8105                        | Desktop     | [8e49155614](https://linux-hardware.org/?probe=8e49155614) | Feb 02, 2022 |
| Schenker      | XMG NEO (TGL/M21)           | Notebook    | [3cfaf3e233](https://linux-hardware.org/?probe=3cfaf3e233) | Feb 02, 2022 |
| Acer          | Aspire X3950                | Desktop     | [d80e213b52](https://linux-hardware.org/?probe=d80e213b52) | Feb 02, 2022 |
| Lenovo        | SKYBAY SDK0J40700 WIN 32... | Desktop     | [9f9648d05c](https://linux-hardware.org/?probe=9f9648d05c) | Feb 02, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [26a4917db5](https://linux-hardware.org/?probe=26a4917db5) | Feb 02, 2022 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [28280d252b](https://linux-hardware.org/?probe=28280d252b) | Feb 02, 2022 |
| Lenovo        | ThinkPad W700 27526LG       | Notebook    | [06b01ba136](https://linux-hardware.org/?probe=06b01ba136) | Feb 02, 2022 |
| Gigabyte      | B75M-D3V                    | Desktop     | [bf085b398d](https://linux-hardware.org/?probe=bf085b398d) | Feb 02, 2022 |
| Gigabyte      | B75M-D3V                    | Desktop     | [020982ee77](https://linux-hardware.org/?probe=020982ee77) | Feb 02, 2022 |
| HP            | 2B4B                        | Desktop     | [4205ceb454](https://linux-hardware.org/?probe=4205ceb454) | Feb 01, 2022 |
| Notebook      | W35xSTQ_370ST               | Notebook    | [8ca6ba0666](https://linux-hardware.org/?probe=8ca6ba0666) | Feb 01, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [ad29a7f260](https://linux-hardware.org/?probe=ad29a7f260) | Feb 01, 2022 |
| ASUSTek       | M4A87TD EVO                 | Desktop     | [8eab19298c](https://linux-hardware.org/?probe=8eab19298c) | Feb 01, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [55dc5e6e08](https://linux-hardware.org/?probe=55dc5e6e08) | Feb 01, 2022 |
| HP            | Pavilion 17                 | Notebook    | [22ba4146a4](https://linux-hardware.org/?probe=22ba4146a4) | Feb 01, 2022 |
| PIPO          | Cherry Trail CR             | Notebook    | [eb92e7ef7f](https://linux-hardware.org/?probe=eb92e7ef7f) | Feb 01, 2022 |
| ASUSTek       | M51Tr                       | Notebook    | [d9f7af9fd5](https://linux-hardware.org/?probe=d9f7af9fd5) | Feb 01, 2022 |
| ASUSTek       | P5QL-CM                     | Desktop     | [dfcb53da8c](https://linux-hardware.org/?probe=dfcb53da8c) | Feb 01, 2022 |
| ASRock        | 980DE3/U3S3                 | Desktop     | [bfc99c3e13](https://linux-hardware.org/?probe=bfc99c3e13) | Feb 01, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [08a40b3e98](https://linux-hardware.org/?probe=08a40b3e98) | Feb 01, 2022 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [64874bde42](https://linux-hardware.org/?probe=64874bde42) | Feb 01, 2022 |
| Wortmann      | 1220663_1470189             | Notebook    | [3f09a29186](https://linux-hardware.org/?probe=3f09a29186) | Feb 01, 2022 |
| Dell          | Precision M6800             | Notebook    | [560b1d25be](https://linux-hardware.org/?probe=560b1d25be) | Feb 01, 2022 |
| Acer          | FX58M                       | Desktop     | [e68b127961](https://linux-hardware.org/?probe=e68b127961) | Feb 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [629972c689](https://linux-hardware.org/?probe=629972c689) | Feb 01, 2022 |
| Dell          | Latitude 7370               | Notebook    | [2f8111fcee](https://linux-hardware.org/?probe=2f8111fcee) | Feb 01, 2022 |
| Medion        | E16402                      | Notebook    | [1abbc6f368](https://linux-hardware.org/?probe=1abbc6f368) | Feb 01, 2022 |
| Acer          | Swift SF114-32              | Notebook    | [1a0b7da0df](https://linux-hardware.org/?probe=1a0b7da0df) | Feb 01, 2022 |
| Acer          | Swift SF114-32              | Notebook    | [ce9e5f5d44](https://linux-hardware.org/?probe=ce9e5f5d44) | Feb 01, 2022 |
| Dell          | Inspiron 7720               | Notebook    | [ffe5569ab0](https://linux-hardware.org/?probe=ffe5569ab0) | Feb 01, 2022 |
| Fujitsu       | D3613-A1 S26361-D3613-A1    | Desktop     | [27b9e98a16](https://linux-hardware.org/?probe=27b9e98a16) | Feb 01, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [fb9c5fac50](https://linux-hardware.org/?probe=fb9c5fac50) | Feb 01, 2022 |
| Fujitsu       | D3600-A1 S26361-D3600-A1    | Desktop     | [9ba4b1306f](https://linux-hardware.org/?probe=9ba4b1306f) | Jan 31, 2022 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | Notebook    | [213079780b](https://linux-hardware.org/?probe=213079780b) | Jan 31, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [512c8c256a](https://linux-hardware.org/?probe=512c8c256a) | Jan 31, 2022 |
| Medion        | P2A4-EM                     | Desktop     | [330e43b195](https://linux-hardware.org/?probe=330e43b195) | Jan 31, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [b16ba2b14a](https://linux-hardware.org/?probe=b16ba2b14a) | Jan 31, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [a7e485dbef](https://linux-hardware.org/?probe=a7e485dbef) | Jan 31, 2022 |
| ASUSTek       | H110M-R                     | Desktop     | [38a03d3718](https://linux-hardware.org/?probe=38a03d3718) | Jan 31, 2022 |
| ASUSTek       | VivoBook Flip 14_ASUS Fl... | Convertible | [fc5490ffca](https://linux-hardware.org/?probe=fc5490ffca) | Jan 31, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [dd9f492694](https://linux-hardware.org/?probe=dd9f492694) | Jan 31, 2022 |
| Gigabyte      | H81M-D2V                    | Desktop     | [83d98b94dd](https://linux-hardware.org/?probe=83d98b94dd) | Jan 31, 2022 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [53ea0036b1](https://linux-hardware.org/?probe=53ea0036b1) | Jan 31, 2022 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [2609297f16](https://linux-hardware.org/?probe=2609297f16) | Jan 31, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [9990fdf430](https://linux-hardware.org/?probe=9990fdf430) | Jan 31, 2022 |
| Fujitsu       | LIFEBOOK U9311X             | Convertible | [b8ec37a94b](https://linux-hardware.org/?probe=b8ec37a94b) | Jan 31, 2022 |
| Intel         | NUC7i3BNB J22859-313        | Mini pc     | [8f83ae693d](https://linux-hardware.org/?probe=8f83ae693d) | Jan 31, 2022 |
| Dell          | Latitude 7370               | Notebook    | [42b6b1684b](https://linux-hardware.org/?probe=42b6b1684b) | Jan 31, 2022 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [72ad880143](https://linux-hardware.org/?probe=72ad880143) | Jan 31, 2022 |
| Dell          | Latitude E5570              | Notebook    | [87ec93dcdc](https://linux-hardware.org/?probe=87ec93dcdc) | Jan 31, 2022 |
| ASUSTek       | 1005PXD                     | Notebook    | [43666c16cb](https://linux-hardware.org/?probe=43666c16cb) | Jan 31, 2022 |
| MSI           | Creator 17 B11UH            | Notebook    | [25663dceb9](https://linux-hardware.org/?probe=25663dceb9) | Jan 31, 2022 |
| Acer          | TravelMate 6460             | Notebook    | [97aabaa620](https://linux-hardware.org/?probe=97aabaa620) | Jan 31, 2022 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [f3ed6567f9](https://linux-hardware.org/?probe=f3ed6567f9) | Jan 31, 2022 |
| Lenovo        | ThinkPad T460 20FMS2J000    | Notebook    | [f75f8240a4](https://linux-hardware.org/?probe=f75f8240a4) | Jan 31, 2022 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [41d464f5f8](https://linux-hardware.org/?probe=41d464f5f8) | Jan 30, 2022 |
| Dell          | Latitude 7320 Detachable    | Tablet      | [255ffc0493](https://linux-hardware.org/?probe=255ffc0493) | Jan 30, 2022 |
| PC Engines    | APU2                        | Desktop     | [92bee3c45e](https://linux-hardware.org/?probe=92bee3c45e) | Jan 30, 2022 |
| MSI           | Z77A-GD65                   | Desktop     | [582fc22a3b](https://linux-hardware.org/?probe=582fc22a3b) | Jan 30, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [577ab5937c](https://linux-hardware.org/?probe=577ab5937c) | Jan 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [3b9602c67c](https://linux-hardware.org/?probe=3b9602c67c) | Jan 30, 2022 |
| ASUSTek       | P6T WS PRO                  | Desktop     | [007b4193a0](https://linux-hardware.org/?probe=007b4193a0) | Jan 30, 2022 |
| Gigabyte      | GA-890FXA-UD5               | Desktop     | [a7a2a13e23](https://linux-hardware.org/?probe=a7a2a13e23) | Jan 30, 2022 |
| HP            | Elite x2 1012 G1            | Notebook    | [13b478195a](https://linux-hardware.org/?probe=13b478195a) | Jan 30, 2022 |
| Lenovo        | ThinkPad T480s 20L8S02E0... | Notebook    | [e35fffc0dd](https://linux-hardware.org/?probe=e35fffc0dd) | Jan 30, 2022 |
| PC Engines    | APU2                        | Desktop     | [c2c55a3278](https://linux-hardware.org/?probe=c2c55a3278) | Jan 30, 2022 |
| Dell          | 0NKW6Y A02                  | Desktop     | [f01b040659](https://linux-hardware.org/?probe=f01b040659) | Jan 30, 2022 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [d74e691baf](https://linux-hardware.org/?probe=d74e691baf) | Jan 30, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TES... | Notebook    | [d899ce769f](https://linux-hardware.org/?probe=d899ce769f) | Jan 30, 2022 |
| Packard Be... | MCP73                       | Desktop     | [cd16e68670](https://linux-hardware.org/?probe=cd16e68670) | Jan 30, 2022 |
| Medion        | E7214                       | Notebook    | [c20aa5c58d](https://linux-hardware.org/?probe=c20aa5c58d) | Jan 30, 2022 |
| Acer          | Aspire X3950                | Desktop     | [c3e1066388](https://linux-hardware.org/?probe=c3e1066388) | Jan 30, 2022 |
| ASRock        | H510M-HVS                   | Desktop     | [5873b06924](https://linux-hardware.org/?probe=5873b06924) | Jan 30, 2022 |
| HP            | Compaq Presario CQ70        | Notebook    | [e1139570a4](https://linux-hardware.org/?probe=e1139570a4) | Jan 30, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [e618d0e8f6](https://linux-hardware.org/?probe=e618d0e8f6) | Jan 30, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [7b47741e03](https://linux-hardware.org/?probe=7b47741e03) | Jan 30, 2022 |
| Google        | Kench                       | Desktop     | [f9982ebf7b](https://linux-hardware.org/?probe=f9982ebf7b) | Jan 30, 2022 |
| Packard Be... | MCP73                       | Desktop     | [256d182a40](https://linux-hardware.org/?probe=256d182a40) | Jan 30, 2022 |
| HP            | 350 G1                      | Notebook    | [f0f4e8f688](https://linux-hardware.org/?probe=f0f4e8f688) | Jan 30, 2022 |
| Toshiba       | Satellite A300              | Notebook    | [a909d3702b](https://linux-hardware.org/?probe=a909d3702b) | Jan 30, 2022 |
| Toshiba       | Satellite A300              | Notebook    | [b02315f2c0](https://linux-hardware.org/?probe=b02315f2c0) | Jan 30, 2022 |
| Fujitsu       | LIFEBOOK U9311X             | Convertible | [253fa769df](https://linux-hardware.org/?probe=253fa769df) | Jan 30, 2022 |
| Lenovo        | ThinkPad T430 2349GCG       | Notebook    | [9c94c598d3](https://linux-hardware.org/?probe=9c94c598d3) | Jan 30, 2022 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [67505d4784](https://linux-hardware.org/?probe=67505d4784) | Jan 30, 2022 |
| MSI           | Z77A-GD65                   | Desktop     | [908fbe05d3](https://linux-hardware.org/?probe=908fbe05d3) | Jan 29, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [af5eb12b7b](https://linux-hardware.org/?probe=af5eb12b7b) | Jan 29, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [c9528e87c0](https://linux-hardware.org/?probe=c9528e87c0) | Jan 29, 2022 |
| Toshiba       | Satellite A300              | Notebook    | [ddf886b767](https://linux-hardware.org/?probe=ddf886b767) | Jan 29, 2022 |
| Gigabyte      | H81M-D2V                    | Desktop     | [5dc80948c0](https://linux-hardware.org/?probe=5dc80948c0) | Jan 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [6158642c8d](https://linux-hardware.org/?probe=6158642c8d) | Jan 29, 2022 |
| Acer          | Aspire 5920G                | Notebook    | [130c29c76e](https://linux-hardware.org/?probe=130c29c76e) | Jan 29, 2022 |
| Acer          | RS740DVF                    | Desktop     | [88322439c0](https://linux-hardware.org/?probe=88322439c0) | Jan 29, 2022 |
| MSI           | GF75 Thin 10SDR             | Notebook    | [dadcf8d49c](https://linux-hardware.org/?probe=dadcf8d49c) | Jan 29, 2022 |
| MSI           | Boston                      | Desktop     | [cf8bef5290](https://linux-hardware.org/?probe=cf8bef5290) | Jan 29, 2022 |
| Fujitsu       | LIFEBOOK U9311X             | Convertible | [a98a9e9993](https://linux-hardware.org/?probe=a98a9e9993) | Jan 29, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [08b0a66098](https://linux-hardware.org/?probe=08b0a66098) | Jan 29, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [2390502c8f](https://linux-hardware.org/?probe=2390502c8f) | Jan 29, 2022 |
| Dell          | Latitude E5420              | Notebook    | [89a74ff338](https://linux-hardware.org/?probe=89a74ff338) | Jan 29, 2022 |
| ASRock        | B150M Pro4S/D3              | Desktop     | [b7a65f897c](https://linux-hardware.org/?probe=b7a65f897c) | Jan 29, 2022 |
| Medion        | S4216                       | Notebook    | [44f51b925b](https://linux-hardware.org/?probe=44f51b925b) | Jan 29, 2022 |
| MSI           | Boston                      | Desktop     | [2a9f7de116](https://linux-hardware.org/?probe=2a9f7de116) | Jan 29, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | Notebook    | [7697915441](https://linux-hardware.org/?probe=7697915441) | Jan 29, 2022 |
| ZOTAC         | ZBOX-CI527/CI547            | Mini pc     | [e4bbe42b5a](https://linux-hardware.org/?probe=e4bbe42b5a) | Jan 29, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [1ce7d1b347](https://linux-hardware.org/?probe=1ce7d1b347) | Jan 29, 2022 |
| Lenovo        | ThinkPad T430 2349GCG       | Notebook    | [79073707f7](https://linux-hardware.org/?probe=79073707f7) | Jan 29, 2022 |
| HP            | ProBook 4720s               | Notebook    | [c17f5dcf26](https://linux-hardware.org/?probe=c17f5dcf26) | Jan 29, 2022 |
| Teclast       | X6 plus                     | Tablet      | [a84fba541b](https://linux-hardware.org/?probe=a84fba541b) | Jan 29, 2022 |
| Gigabyte      | Z87X-UD3H-CF                | Desktop     | [533df9d207](https://linux-hardware.org/?probe=533df9d207) | Jan 28, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [6ba91410f8](https://linux-hardware.org/?probe=6ba91410f8) | Jan 28, 2022 |
| ASUSTek       | X555BA                      | Notebook    | [526e03cf05](https://linux-hardware.org/?probe=526e03cf05) | Jan 28, 2022 |
| ASRock        | H570M-ITX/ac                | Desktop     | [e901364a26](https://linux-hardware.org/?probe=e901364a26) | Jan 28, 2022 |
| ASRock        | 970 Extreme3                | Desktop     | [82d0c3e60e](https://linux-hardware.org/?probe=82d0c3e60e) | Jan 28, 2022 |
| MSI           | B560M PRO                   | Desktop     | [00b3d4717d](https://linux-hardware.org/?probe=00b3d4717d) | Jan 28, 2022 |
| ASUSTek       | P50IJ                       | Notebook    | [28f19cf5c5](https://linux-hardware.org/?probe=28f19cf5c5) | Jan 28, 2022 |
| Acer          | Swift SF315-41              | Notebook    | [b25a81b248](https://linux-hardware.org/?probe=b25a81b248) | Jan 28, 2022 |
| ASRock        | H570M-ITX/ac                | Desktop     | [7295dda221](https://linux-hardware.org/?probe=7295dda221) | Jan 28, 2022 |
| Fujitsu Si... | G31T-M2 V3.02               | Desktop     | [1cff880d91](https://linux-hardware.org/?probe=1cff880d91) | Jan 28, 2022 |
| Dell          | 0TTDMJ A00                  | Desktop     | [599bb60663](https://linux-hardware.org/?probe=599bb60663) | Jan 28, 2022 |
| Lenovo        | ThinkPad T420 4180ED3       | Notebook    | [b115732b3b](https://linux-hardware.org/?probe=b115732b3b) | Jan 28, 2022 |
| MSI           | A68HM GRENADE               | Desktop     | [ea2a58f958](https://linux-hardware.org/?probe=ea2a58f958) | Jan 28, 2022 |
| HP            | ProBook 6560b               | Notebook    | [6644889929](https://linux-hardware.org/?probe=6644889929) | Jan 28, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [0143cbef50](https://linux-hardware.org/?probe=0143cbef50) | Jan 28, 2022 |
| MSI           | B560M PRO                   | Desktop     | [b3a84eebc3](https://linux-hardware.org/?probe=b3a84eebc3) | Jan 28, 2022 |
| Fujitsu Si... | AMILO La1703                | Notebook    | [e5a36c2f32](https://linux-hardware.org/?probe=e5a36c2f32) | Jan 28, 2022 |
| Samsung       | 750XDA                      | Notebook    | [e83c271e2e](https://linux-hardware.org/?probe=e83c271e2e) | Jan 28, 2022 |
| Sony          | VPCSB1B9E                   | Notebook    | [2b1ede014c](https://linux-hardware.org/?probe=2b1ede014c) | Jan 28, 2022 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [c969e228f3](https://linux-hardware.org/?probe=c969e228f3) | Jan 28, 2022 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [67424a014e](https://linux-hardware.org/?probe=67424a014e) | Jan 28, 2022 |
| MSI           | Z270 KRAIT GAMING           | Desktop     | [17ccbf9c76](https://linux-hardware.org/?probe=17ccbf9c76) | Jan 28, 2022 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [3e66e21a1e](https://linux-hardware.org/?probe=3e66e21a1e) | Jan 28, 2022 |
| Lenovo        | ThinkPad T480s 20L8S02E0... | Notebook    | [999e47c570](https://linux-hardware.org/?probe=999e47c570) | Jan 28, 2022 |
| Lenovo        | ThinkPad T430 2349QM6       | Notebook    | [5b8b11206e](https://linux-hardware.org/?probe=5b8b11206e) | Jan 28, 2022 |
| Lenovo        | ThinkPad T430 2349QM6       | Notebook    | [93b54d612d](https://linux-hardware.org/?probe=93b54d612d) | Jan 28, 2022 |
| HP            | 1497                        | Desktop     | [3a3b4fe530](https://linux-hardware.org/?probe=3a3b4fe530) | Jan 27, 2022 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | Notebook    | [29594870b8](https://linux-hardware.org/?probe=29594870b8) | Jan 27, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [bfc2cf603f](https://linux-hardware.org/?probe=bfc2cf603f) | Jan 27, 2022 |
| Fujitsu Si... | AMILO Xi 1526               | Notebook    | [5acf0f5805](https://linux-hardware.org/?probe=5acf0f5805) | Jan 27, 2022 |
| HP            | Laptop 15-da2xxx            | Notebook    | [46a8013ef6](https://linux-hardware.org/?probe=46a8013ef6) | Jan 27, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [dd98714aa0](https://linux-hardware.org/?probe=dd98714aa0) | Jan 27, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [24b7566606](https://linux-hardware.org/?probe=24b7566606) | Jan 27, 2022 |
| MSI           | H81M-E34                    | Desktop     | [fc61aaf589](https://linux-hardware.org/?probe=fc61aaf589) | Jan 27, 2022 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [a1cda00de3](https://linux-hardware.org/?probe=a1cda00de3) | Jan 27, 2022 |
| Intel         | NUC7i7BNB J31145-303        | Mini pc     | [3b632063e5](https://linux-hardware.org/?probe=3b632063e5) | Jan 27, 2022 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [6e695b85fb](https://linux-hardware.org/?probe=6e695b85fb) | Jan 27, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [1330d31221](https://linux-hardware.org/?probe=1330d31221) | Jan 27, 2022 |
| TUXEDO        | Book XP1511                 | Notebook    | [12a1ab9ddb](https://linux-hardware.org/?probe=12a1ab9ddb) | Jan 27, 2022 |
| MSI           | G41M-P26                    | Desktop     | [3d8dd4cb0a](https://linux-hardware.org/?probe=3d8dd4cb0a) | Jan 27, 2022 |
| ASRock        | H87 Performance             | Desktop     | [0972f4e6db](https://linux-hardware.org/?probe=0972f4e6db) | Jan 27, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [c4490b9719](https://linux-hardware.org/?probe=c4490b9719) | Jan 27, 2022 |
| ASRock        | AM1H-ITX                    | Desktop     | [e945292f54](https://linux-hardware.org/?probe=e945292f54) | Jan 27, 2022 |
| Fujitsu       | LIFEBOOK A530               | Notebook    | [bda3f36826](https://linux-hardware.org/?probe=bda3f36826) | Jan 27, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [ee5c4855a1](https://linux-hardware.org/?probe=ee5c4855a1) | Jan 27, 2022 |
| Dell          | Latitude 7480               | Notebook    | [03d42cf11e](https://linux-hardware.org/?probe=03d42cf11e) | Jan 27, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [7133090590](https://linux-hardware.org/?probe=7133090590) | Jan 27, 2022 |
| Fujitsu Si... | AMILO Xi 1526               | Notebook    | [0b4735d586](https://linux-hardware.org/?probe=0b4735d586) | Jan 27, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [07192f2b7d](https://linux-hardware.org/?probe=07192f2b7d) | Jan 27, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [b225cb9fe5](https://linux-hardware.org/?probe=b225cb9fe5) | Jan 27, 2022 |
| Acer          | Aspire E1-570G              | Notebook    | [e119b0a5ef](https://linux-hardware.org/?probe=e119b0a5ef) | Jan 26, 2022 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [a8678e1dc3](https://linux-hardware.org/?probe=a8678e1dc3) | Jan 26, 2022 |
| Intel         | DG31PR AAD97573-306         | Desktop     | [8b3d53834f](https://linux-hardware.org/?probe=8b3d53834f) | Jan 26, 2022 |
| Medion        | MS-7728                     | Desktop     | [ca561d8bda](https://linux-hardware.org/?probe=ca561d8bda) | Jan 26, 2022 |
| Intel         | DG31PR AAD97573-306         | Desktop     | [5e11b9b4e3](https://linux-hardware.org/?probe=5e11b9b4e3) | Jan 26, 2022 |
| Clevo         | W2xxHSQ                     | Notebook    | [5dd572e97b](https://linux-hardware.org/?probe=5dd572e97b) | Jan 26, 2022 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [4a7b39821e](https://linux-hardware.org/?probe=4a7b39821e) | Jan 26, 2022 |
| Intel         | NUC8BEB J72692-310          | Mini pc     | [f6af641a5e](https://linux-hardware.org/?probe=f6af641a5e) | Jan 26, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [fe518d8966](https://linux-hardware.org/?probe=fe518d8966) | Jan 26, 2022 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [2d908d8204](https://linux-hardware.org/?probe=2d908d8204) | Jan 26, 2022 |
| Acer          | Mammoth                     | Notebook    | [de58dffeaf](https://linux-hardware.org/?probe=de58dffeaf) | Jan 26, 2022 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [7ecb97de3d](https://linux-hardware.org/?probe=7ecb97de3d) | Jan 26, 2022 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | Notebook    | [24ae03e093](https://linux-hardware.org/?probe=24ae03e093) | Jan 26, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [95d6e59e28](https://linux-hardware.org/?probe=95d6e59e28) | Jan 26, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [3a25d57a74](https://linux-hardware.org/?probe=3a25d57a74) | Jan 26, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [dc01d09a1d](https://linux-hardware.org/?probe=dc01d09a1d) | Jan 26, 2022 |
| ASRock        | N68-VS3 FX                  | Desktop     | [f6341b79f7](https://linux-hardware.org/?probe=f6341b79f7) | Jan 26, 2022 |
| Lenovo        | ThinkPad X61 7673C44        | Notebook    | [ab461bd99e](https://linux-hardware.org/?probe=ab461bd99e) | Jan 26, 2022 |
| HP            | ProBook 6550b               | Notebook    | [02d7f3125e](https://linux-hardware.org/?probe=02d7f3125e) | Jan 26, 2022 |
| Lenovo        | V155-15API 81V5             | Notebook    | [25e8674c5b](https://linux-hardware.org/?probe=25e8674c5b) | Jan 26, 2022 |
| ASUSTek       | M5A97                       | Desktop     | [eb7b653d12](https://linux-hardware.org/?probe=eb7b653d12) | Jan 26, 2022 |
| ASUSTek       | M5A97                       | Desktop     | [495ec36875](https://linux-hardware.org/?probe=495ec36875) | Jan 26, 2022 |
| ASRock        | Z77 Pro4                    | Desktop     | [8062682731](https://linux-hardware.org/?probe=8062682731) | Jan 25, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [115b4f412c](https://linux-hardware.org/?probe=115b4f412c) | Jan 25, 2022 |
| Packard Be... | EasyNote TE11BZ             | Notebook    | [1f3f4d2107](https://linux-hardware.org/?probe=1f3f4d2107) | Jan 25, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [3254fbfc4f](https://linux-hardware.org/?probe=3254fbfc4f) | Jan 25, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [510e973c9d](https://linux-hardware.org/?probe=510e973c9d) | Jan 25, 2022 |
| TUXEDO        | Book XP1511                 | Notebook    | [9a62ad3fe4](https://linux-hardware.org/?probe=9a62ad3fe4) | Jan 25, 2022 |
| Unknown       | T3 MRD                      | Notebook    | [2a812850f1](https://linux-hardware.org/?probe=2a812850f1) | Jan 25, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [0f6c39f50e](https://linux-hardware.org/?probe=0f6c39f50e) | Jan 25, 2022 |
| ASUSTek       | P7H55-USB3                  | Desktop     | [1f4b756d04](https://linux-hardware.org/?probe=1f4b756d04) | Jan 25, 2022 |
| Unknown       | Unknown                     | Notebook    | [84effb261a](https://linux-hardware.org/?probe=84effb261a) | Jan 24, 2022 |
| Acer          | ConceptD CM100-51A V:1.1    | Desktop     | [663bbd709d](https://linux-hardware.org/?probe=663bbd709d) | Jan 24, 2022 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [be8285fe69](https://linux-hardware.org/?probe=be8285fe69) | Jan 24, 2022 |
| Sony          | VPCS11V9E                   | Notebook    | [f161e5d26c](https://linux-hardware.org/?probe=f161e5d26c) | Jan 24, 2022 |
| Dell          | Latitude E7250              | Notebook    | [2ebc0c7092](https://linux-hardware.org/?probe=2ebc0c7092) | Jan 24, 2022 |
| Acer          | Aspire 1810TZ               | Notebook    | [ee1d4236c9](https://linux-hardware.org/?probe=ee1d4236c9) | Jan 24, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [1364acf470](https://linux-hardware.org/?probe=1364acf470) | Jan 24, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [656da02110](https://linux-hardware.org/?probe=656da02110) | Jan 24, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [a4f6a4a38e](https://linux-hardware.org/?probe=a4f6a4a38e) | Jan 24, 2022 |
| HP            | Elite x2 1012 G1            | Notebook    | [64fdc4c525](https://linux-hardware.org/?probe=64fdc4c525) | Jan 24, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [9e4f498056](https://linux-hardware.org/?probe=9e4f498056) | Jan 24, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [1721bed3e1](https://linux-hardware.org/?probe=1721bed3e1) | Jan 24, 2022 |
| Sony          | VGN-N31S_W                  | Notebook    | [ce8de203fb](https://linux-hardware.org/?probe=ce8de203fb) | Jan 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [dfe95d1e0a](https://linux-hardware.org/?probe=dfe95d1e0a) | Jan 24, 2022 |
| Acer          | Extensa 2540                | Notebook    | [27a41f2533](https://linux-hardware.org/?probe=27a41f2533) | Jan 24, 2022 |
| Medion        | P2A4-EM                     | Desktop     | [6e80bcdcd1](https://linux-hardware.org/?probe=6e80bcdcd1) | Jan 24, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [8f632f06f1](https://linux-hardware.org/?probe=8f632f06f1) | Jan 24, 2022 |
| Fujitsu       | LIFEBOOK U9311X             | Convertible | [9918c37b0c](https://linux-hardware.org/?probe=9918c37b0c) | Jan 24, 2022 |
| Sony          | VGN-N31S_W                  | Notebook    | [fed17ac82e](https://linux-hardware.org/?probe=fed17ac82e) | Jan 24, 2022 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [1f1008ad86](https://linux-hardware.org/?probe=1f1008ad86) | Jan 24, 2022 |
| Lenovo        | ThinkPad T580 20LAS4KG0Q    | Notebook    | [b552b967e4](https://linux-hardware.org/?probe=b552b967e4) | Jan 24, 2022 |
| Apple         | Mac-F2238AC8                | All in one  | [b0e0d985c9](https://linux-hardware.org/?probe=b0e0d985c9) | Jan 24, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [9f5905c095](https://linux-hardware.org/?probe=9f5905c095) | Jan 24, 2022 |
| Dell          | Precision 5520              | Notebook    | [315d733003](https://linux-hardware.org/?probe=315d733003) | Jan 24, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [4ecee40dc7](https://linux-hardware.org/?probe=4ecee40dc7) | Jan 24, 2022 |
| Fujitsu       | LIFEBOOK U758               | Notebook    | [c386ed263b](https://linux-hardware.org/?probe=c386ed263b) | Jan 24, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [e0197893fc](https://linux-hardware.org/?probe=e0197893fc) | Jan 24, 2022 |
| ASUSTek       | H110M-R                     | Desktop     | [3eafb8a2af](https://linux-hardware.org/?probe=3eafb8a2af) | Jan 24, 2022 |
| Lenovo        | G550 2958                   | Notebook    | [fd2872d2d8](https://linux-hardware.org/?probe=fd2872d2d8) | Jan 24, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [3a0e9b68fb](https://linux-hardware.org/?probe=3a0e9b68fb) | Jan 24, 2022 |
| MSI           | Z77A-G41                    | Desktop     | [8e4a87ce17](https://linux-hardware.org/?probe=8e4a87ce17) | Jan 24, 2022 |
| HP            | Pavilion 17                 | Notebook    | [d2c545576e](https://linux-hardware.org/?probe=d2c545576e) | Jan 24, 2022 |
| Lenovo        | ThinkPad P50 20ENS1KF00     | Notebook    | [530c7cf41b](https://linux-hardware.org/?probe=530c7cf41b) | Jan 24, 2022 |
| Lenovo        | ThinkPad P50 20ENS1KF00     | Notebook    | [2a59b11e02](https://linux-hardware.org/?probe=2a59b11e02) | Jan 24, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [db8b77c1ff](https://linux-hardware.org/?probe=db8b77c1ff) | Jan 23, 2022 |
| Acer          | Aspire MM1-571              | Notebook    | [981399b18e](https://linux-hardware.org/?probe=981399b18e) | Jan 23, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [86e6d5c19a](https://linux-hardware.org/?probe=86e6d5c19a) | Jan 23, 2022 |
| Dell          | Inspiron 7706 2n1           | Convertible | [ca24741e67](https://linux-hardware.org/?probe=ca24741e67) | Jan 23, 2022 |
| Dell          | Inspiron 7706 2n1           | Convertible | [d5f89af9ae](https://linux-hardware.org/?probe=d5f89af9ae) | Jan 23, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [58c14af83d](https://linux-hardware.org/?probe=58c14af83d) | Jan 23, 2022 |
| Acer          | Aspire A517-51              | Notebook    | [62a28ff4d9](https://linux-hardware.org/?probe=62a28ff4d9) | Jan 23, 2022 |
| Lenovo        | G550 2958                   | Notebook    | [506ee71418](https://linux-hardware.org/?probe=506ee71418) | Jan 23, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [37e7b98af1](https://linux-hardware.org/?probe=37e7b98af1) | Jan 23, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [739904e65c](https://linux-hardware.org/?probe=739904e65c) | Jan 23, 2022 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [22757e0dd9](https://linux-hardware.org/?probe=22757e0dd9) | Jan 23, 2022 |
| ASRock        | Z77 Extreme4                | Desktop     | [1d9246a4f9](https://linux-hardware.org/?probe=1d9246a4f9) | Jan 23, 2022 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [b63214b1e1](https://linux-hardware.org/?probe=b63214b1e1) | Jan 23, 2022 |
| Lenovo        | ThinkCentre M57 9172A13     | Desktop     | [b98c3a53e0](https://linux-hardware.org/?probe=b98c3a53e0) | Jan 23, 2022 |
| Acer          | Aspire 7720                 | Notebook    | [20a42368f1](https://linux-hardware.org/?probe=20a42368f1) | Jan 23, 2022 |
| ASUSTek       | B85M-G PLUS/USB             | Desktop     | [f02501a8a9](https://linux-hardware.org/?probe=f02501a8a9) | Jan 23, 2022 |
| MSI           | U90/U100                    | Notebook    | [a87163f5ea](https://linux-hardware.org/?probe=a87163f5ea) | Jan 23, 2022 |
| ASUSTek       | K95VM                       | Notebook    | [8345888a5e](https://linux-hardware.org/?probe=8345888a5e) | Jan 23, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [8d888fc583](https://linux-hardware.org/?probe=8d888fc583) | Jan 23, 2022 |
| ASUSTek       | K95VM                       | Notebook    | [fb24768fa2](https://linux-hardware.org/?probe=fb24768fa2) | Jan 23, 2022 |
| Lenovo        | ThinkCentre M57 9172A13     | Desktop     | [b92524a5c1](https://linux-hardware.org/?probe=b92524a5c1) | Jan 23, 2022 |
| Intel         | DP67BG AAG10491-400         | Desktop     | [854d730053](https://linux-hardware.org/?probe=854d730053) | Jan 23, 2022 |
| Acer          | Aspire MM1-571              | Notebook    | [e2a322209e](https://linux-hardware.org/?probe=e2a322209e) | Jan 23, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [6e711f3f7d](https://linux-hardware.org/?probe=6e711f3f7d) | Jan 23, 2022 |
| HP            | 17E2                        | Mini pc     | [ae54c309d5](https://linux-hardware.org/?probe=ae54c309d5) | Jan 23, 2022 |
| HP            | ProBook 440 G6              | Notebook    | [b7fb25920a](https://linux-hardware.org/?probe=b7fb25920a) | Jan 23, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [586c28a98a](https://linux-hardware.org/?probe=586c28a98a) | Jan 23, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [3363e2fdb0](https://linux-hardware.org/?probe=3363e2fdb0) | Jan 23, 2022 |
| Dell          | 0HY9JP A00                  | Desktop     | [57d9a51438](https://linux-hardware.org/?probe=57d9a51438) | Jan 23, 2022 |
| Dell          | Latitude 7490               | Notebook    | [fea8be783a](https://linux-hardware.org/?probe=fea8be783a) | Jan 23, 2022 |
| MSI           | U90/U100                    | Notebook    | [a005adaf94](https://linux-hardware.org/?probe=a005adaf94) | Jan 23, 2022 |
| MSI           | Z170A GAMING M3             | Desktop     | [3913d07acf](https://linux-hardware.org/?probe=3913d07acf) | Jan 23, 2022 |
| eii           | WSA116                      | Notebook    | [ecff258a89](https://linux-hardware.org/?probe=ecff258a89) | Jan 23, 2022 |
| MSI           | GP76 Leopard 10UE           | Notebook    | [0b34910675](https://linux-hardware.org/?probe=0b34910675) | Jan 22, 2022 |
| ASUSTek       | E200HA                      | Notebook    | [d4a762079e](https://linux-hardware.org/?probe=d4a762079e) | Jan 22, 2022 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [bd309bc0ae](https://linux-hardware.org/?probe=bd309bc0ae) | Jan 22, 2022 |
| ASUSTek       | M5A78L-M LE                 | Desktop     | [a7209bb34a](https://linux-hardware.org/?probe=a7209bb34a) | Jan 22, 2022 |
| ASUSTek       | M5A78L-M LE                 | Desktop     | [5f7c38d0d5](https://linux-hardware.org/?probe=5f7c38d0d5) | Jan 22, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [a0034083eb](https://linux-hardware.org/?probe=a0034083eb) | Jan 22, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [ab4793dc5e](https://linux-hardware.org/?probe=ab4793dc5e) | Jan 22, 2022 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [e477b84aa1](https://linux-hardware.org/?probe=e477b84aa1) | Jan 22, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [7a52dda8cc](https://linux-hardware.org/?probe=7a52dda8cc) | Jan 22, 2022 |
| Dell          | Inspiron 1110               | Notebook    | [da43d699a4](https://linux-hardware.org/?probe=da43d699a4) | Jan 22, 2022 |
| Medion        | MS-7713                     | Desktop     | [e3eb63e81f](https://linux-hardware.org/?probe=e3eb63e81f) | Jan 22, 2022 |
| Gigabyte      | Z97-HD3                     | Desktop     | [0206126edb](https://linux-hardware.org/?probe=0206126edb) | Jan 22, 2022 |
| HP            | 339A                        | Desktop     | [ee8bf5c45e](https://linux-hardware.org/?probe=ee8bf5c45e) | Jan 22, 2022 |
| Lenovo        | G780 20138                  | Notebook    | [4b5e81151e](https://linux-hardware.org/?probe=4b5e81151e) | Jan 22, 2022 |
| Fujitsu Si... | LIFEBOOK E8010              | Notebook    | [82d1bc5db0](https://linux-hardware.org/?probe=82d1bc5db0) | Jan 22, 2022 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [9eaa5ec16f](https://linux-hardware.org/?probe=9eaa5ec16f) | Jan 22, 2022 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [dc2fed01f8](https://linux-hardware.org/?probe=dc2fed01f8) | Jan 22, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [85e77e3834](https://linux-hardware.org/?probe=85e77e3834) | Jan 22, 2022 |
| Lenovo        | V155-15API 81V5             | Notebook    | [64455c2436](https://linux-hardware.org/?probe=64455c2436) | Jan 22, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [75d4eef3ba](https://linux-hardware.org/?probe=75d4eef3ba) | Jan 22, 2022 |
| MSI           | P45 Platinum                | Desktop     | [d6025ae24d](https://linux-hardware.org/?probe=d6025ae24d) | Jan 22, 2022 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [c706f6dd55](https://linux-hardware.org/?probe=c706f6dd55) | Jan 21, 2022 |
| ASUSTek       | ROG STRIX B360-H GAMING     | Desktop     | [d1505fe489](https://linux-hardware.org/?probe=d1505fe489) | Jan 21, 2022 |
| HP            | Elite x2 1012 G1            | Notebook    | [2c73df6abc](https://linux-hardware.org/?probe=2c73df6abc) | Jan 21, 2022 |
| Dell          | Studio 1737                 | Notebook    | [d2d85d9b73](https://linux-hardware.org/?probe=d2d85d9b73) | Jan 21, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [ab31e5f54c](https://linux-hardware.org/?probe=ab31e5f54c) | Jan 21, 2022 |
| MSI           | Z77A-GD65                   | Desktop     | [d4ebf1228f](https://linux-hardware.org/?probe=d4ebf1228f) | Jan 21, 2022 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [77545529dc](https://linux-hardware.org/?probe=77545529dc) | Jan 21, 2022 |
| Dell          | 0HN7XN A01                  | Desktop     | [1de8a60923](https://linux-hardware.org/?probe=1de8a60923) | Jan 21, 2022 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [2890d013eb](https://linux-hardware.org/?probe=2890d013eb) | Jan 21, 2022 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [7599c2d302](https://linux-hardware.org/?probe=7599c2d302) | Jan 21, 2022 |
| Lenovo        | ThinkPad X220 4291B60       | Notebook    | [94a949025b](https://linux-hardware.org/?probe=94a949025b) | Jan 21, 2022 |
| Lenovo        | ThinkPad X390 Yoga 20NN0... | Convertible | [c5dea592e4](https://linux-hardware.org/?probe=c5dea592e4) | Jan 21, 2022 |
| Medion        | MS-7748                     | Desktop     | [4f7fd0ee2a](https://linux-hardware.org/?probe=4f7fd0ee2a) | Jan 21, 2022 |
| Dell          | Inspiron 1110               | Notebook    | [e45c3422f3](https://linux-hardware.org/?probe=e45c3422f3) | Jan 21, 2022 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [c2bec0fc16](https://linux-hardware.org/?probe=c2bec0fc16) | Jan 21, 2022 |
| Fujitsu       | CELSIUS H780                | Notebook    | [ce41095f91](https://linux-hardware.org/?probe=ce41095f91) | Jan 21, 2022 |
| ASUSTek       | K52Dr                       | Notebook    | [2a8b6d5bf4](https://linux-hardware.org/?probe=2a8b6d5bf4) | Jan 21, 2022 |
| Fujitsu       | CELSIUS H780                | Notebook    | [942aeb3b0f](https://linux-hardware.org/?probe=942aeb3b0f) | Jan 21, 2022 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [16dc35d7f3](https://linux-hardware.org/?probe=16dc35d7f3) | Jan 21, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [849871b55d](https://linux-hardware.org/?probe=849871b55d) | Jan 21, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [37730388fd](https://linux-hardware.org/?probe=37730388fd) | Jan 21, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [caa12c2897](https://linux-hardware.org/?probe=caa12c2897) | Jan 21, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [09c6c38d95](https://linux-hardware.org/?probe=09c6c38d95) | Jan 21, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [f9ebd05659](https://linux-hardware.org/?probe=f9ebd05659) | Jan 21, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [4f653d2816](https://linux-hardware.org/?probe=4f653d2816) | Jan 21, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [e40957f661](https://linux-hardware.org/?probe=e40957f661) | Jan 21, 2022 |
| Dell          | Inspiron 3482               | Notebook    | [f13427c9b0](https://linux-hardware.org/?probe=f13427c9b0) | Jan 21, 2022 |
| Mediacom      | GTZS                        | Notebook    | [cf77087188](https://linux-hardware.org/?probe=cf77087188) | Jan 21, 2022 |
| Acer          | Aspire F5-771G              | Notebook    | [dd9a69f04d](https://linux-hardware.org/?probe=dd9a69f04d) | Jan 20, 2022 |
| Notebook      | W35xSTQ_370ST               | Notebook    | [d18a3e9db5](https://linux-hardware.org/?probe=d18a3e9db5) | Jan 20, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [f772b2fd3c](https://linux-hardware.org/?probe=f772b2fd3c) | Jan 20, 2022 |
| MSI           | MS-7469 100                 | Desktop     | [8476ffa27e](https://linux-hardware.org/?probe=8476ffa27e) | Jan 20, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [0a8fb964eb](https://linux-hardware.org/?probe=0a8fb964eb) | Jan 20, 2022 |
| HP            | 1589                        | Desktop     | [79882b1033](https://linux-hardware.org/?probe=79882b1033) | Jan 20, 2022 |
| Acer          | Extensa 2511                | Notebook    | [c1b88d129e](https://linux-hardware.org/?probe=c1b88d129e) | Jan 20, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [bcb3fa334d](https://linux-hardware.org/?probe=bcb3fa334d) | Jan 20, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [9d58c5796d](https://linux-hardware.org/?probe=9d58c5796d) | Jan 20, 2022 |
| Notebook      | W35xSTQ_370ST               | Notebook    | [8f642142b5](https://linux-hardware.org/?probe=8f642142b5) | Jan 20, 2022 |
| Intel         | S1200RP G62251-406          | Server      | [f257c969da](https://linux-hardware.org/?probe=f257c969da) | Jan 20, 2022 |
| Dell          | Latitude E5470              | Notebook    | [c97c4b19b1](https://linux-hardware.org/?probe=c97c4b19b1) | Jan 20, 2022 |
| Intel         | S1200RP G62251-406          | Server      | [981732655f](https://linux-hardware.org/?probe=981732655f) | Jan 20, 2022 |
| MSI           | Z77A-GD65                   | Desktop     | [b7eb1484b1](https://linux-hardware.org/?probe=b7eb1484b1) | Jan 20, 2022 |
| Samsung       | 600B4B/600B5B               | Notebook    | [c9ead0a4c9](https://linux-hardware.org/?probe=c9ead0a4c9) | Jan 20, 2022 |
| ASUSTek       | Z97-K                       | Desktop     | [7d370214de](https://linux-hardware.org/?probe=7d370214de) | Jan 20, 2022 |
| Dell          | Latitude 5520               | Notebook    | [edc7ac80ef](https://linux-hardware.org/?probe=edc7ac80ef) | Jan 20, 2022 |
| HP            | 0AE8h C                     | Desktop     | [686981f251](https://linux-hardware.org/?probe=686981f251) | Jan 20, 2022 |
| Dell          | Vostro1710                  | Notebook    | [926079196f](https://linux-hardware.org/?probe=926079196f) | Jan 20, 2022 |
| MSI           | X470 GAMING PLUS            | Desktop     | [8433f6a685](https://linux-hardware.org/?probe=8433f6a685) | Jan 20, 2022 |
| Acer          | Aspire VN7-792G             | Notebook    | [889532fa70](https://linux-hardware.org/?probe=889532fa70) | Jan 20, 2022 |
| Timi          | A34R                        | Notebook    | [fcf594f19a](https://linux-hardware.org/?probe=fcf594f19a) | Jan 20, 2022 |
| Timi          | A34R                        | Notebook    | [046409a8e2](https://linux-hardware.org/?probe=046409a8e2) | Jan 20, 2022 |
| Lenovo        | Myrtle CRB SDK0J40700 WI... | Desktop     | [44b718700d](https://linux-hardware.org/?probe=44b718700d) | Jan 19, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [df4c38dba6](https://linux-hardware.org/?probe=df4c38dba6) | Jan 19, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [512b021ab8](https://linux-hardware.org/?probe=512b021ab8) | Jan 19, 2022 |
| Lenovo        | MIIX 720-12IKB 80VV         | Tablet      | [67e1bdd5f1](https://linux-hardware.org/?probe=67e1bdd5f1) | Jan 19, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [838fd0c9cb](https://linux-hardware.org/?probe=838fd0c9cb) | Jan 19, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [a846ee2ac3](https://linux-hardware.org/?probe=a846ee2ac3) | Jan 19, 2022 |
| HP            | 18EB                        | Desktop     | [59cce3a9a2](https://linux-hardware.org/?probe=59cce3a9a2) | Jan 19, 2022 |
| Lenovo        | V155-15API 81V5             | Notebook    | [09e824f68b](https://linux-hardware.org/?probe=09e824f68b) | Jan 19, 2022 |
| Lenovo        | Yoga 300-11IBY 80M0         | Notebook    | [087fb6774c](https://linux-hardware.org/?probe=087fb6774c) | Jan 19, 2022 |
| ASRock        | H470 Steel Legend           | Desktop     | [9242aab8fa](https://linux-hardware.org/?probe=9242aab8fa) | Jan 19, 2022 |
| MSI           | FM2-A75IA-E53               | Desktop     | [e2b013c3eb](https://linux-hardware.org/?probe=e2b013c3eb) | Jan 19, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [9af982ddf0](https://linux-hardware.org/?probe=9af982ddf0) | Jan 19, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [eac4c9509d](https://linux-hardware.org/?probe=eac4c9509d) | Jan 19, 2022 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | Desktop     | [cbc94c270d](https://linux-hardware.org/?probe=cbc94c270d) | Jan 19, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [c4d285b6e5](https://linux-hardware.org/?probe=c4d285b6e5) | Jan 19, 2022 |
| Gigabyte      | GA-990FXA-UD3               | Desktop     | [630c1a087a](https://linux-hardware.org/?probe=630c1a087a) | Jan 19, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [47eae3d6b2](https://linux-hardware.org/?probe=47eae3d6b2) | Jan 19, 2022 |
| ASRock        | B85M-HDS                    | Desktop     | [08a10e8f68](https://linux-hardware.org/?probe=08a10e8f68) | Jan 19, 2022 |
| Gigabyte      | GA-990FXA-UD3               | Desktop     | [e90aff774e](https://linux-hardware.org/?probe=e90aff774e) | Jan 19, 2022 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | Desktop     | [62c465d499](https://linux-hardware.org/?probe=62c465d499) | Jan 19, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [533f74b810](https://linux-hardware.org/?probe=533f74b810) | Jan 19, 2022 |
| HUAWEI        | MateBook X                  | Notebook    | [b8def0a48d](https://linux-hardware.org/?probe=b8def0a48d) | Jan 19, 2022 |
| Gigabyte      | B560M H                     | Desktop     | [8d57aad6be](https://linux-hardware.org/?probe=8d57aad6be) | Jan 19, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [8cf30a73c8](https://linux-hardware.org/?probe=8cf30a73c8) | Jan 19, 2022 |
| Lenovo        | ThinkCentre M91p 4524WAP    | Desktop     | [bb0d1c1c68](https://linux-hardware.org/?probe=bb0d1c1c68) | Jan 19, 2022 |
| Lenovo        | ThinkPad L440 20AT002YGE    | Notebook    | [303ee02c20](https://linux-hardware.org/?probe=303ee02c20) | Jan 18, 2022 |
| Acer          | Aspire A715-71G             | Notebook    | [9b9e5af3f6](https://linux-hardware.org/?probe=9b9e5af3f6) | Jan 18, 2022 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | Desktop     | [3dd363739d](https://linux-hardware.org/?probe=3dd363739d) | Jan 18, 2022 |
| Wortmann      | TERRA_MOBILE_1512/1712      | Notebook    | [121b9f4443](https://linux-hardware.org/?probe=121b9f4443) | Jan 18, 2022 |
| Fujitsu Si... | AMILO Pa 1538               | Notebook    | [4828d5f734](https://linux-hardware.org/?probe=4828d5f734) | Jan 18, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [2d05af003e](https://linux-hardware.org/?probe=2d05af003e) | Jan 18, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [262dcaf21e](https://linux-hardware.org/?probe=262dcaf21e) | Jan 18, 2022 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [53b6312ff6](https://linux-hardware.org/?probe=53b6312ff6) | Jan 18, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [5187874180](https://linux-hardware.org/?probe=5187874180) | Jan 18, 2022 |
| Acer          | Aspire VN7-792G             | Notebook    | [d67f44cc19](https://linux-hardware.org/?probe=d67f44cc19) | Jan 18, 2022 |
| MSI           | H510M PRO                   | Desktop     | [80761af465](https://linux-hardware.org/?probe=80761af465) | Jan 18, 2022 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [ca37e4f3e0](https://linux-hardware.org/?probe=ca37e4f3e0) | Jan 18, 2022 |
| DFI           | LP 925X-T2                  | Desktop     | [7c615bd7de](https://linux-hardware.org/?probe=7c615bd7de) | Jan 18, 2022 |
| DFI           | LP 925X-T2                  | Desktop     | [cbc72841ed](https://linux-hardware.org/?probe=cbc72841ed) | Jan 18, 2022 |
| ONDA          | OBOOK 11                    | Notebook    | [5fe65e1ffe](https://linux-hardware.org/?probe=5fe65e1ffe) | Jan 18, 2022 |
| ASUSTek       | M5A78L-M LE                 | Desktop     | [06f155ab72](https://linux-hardware.org/?probe=06f155ab72) | Jan 18, 2022 |
| Dell          | 0HN7XN A01                  | Desktop     | [d639b1deb0](https://linux-hardware.org/?probe=d639b1deb0) | Jan 18, 2022 |
| Acer          | Aspire XC-105               | Desktop     | [890e3a285f](https://linux-hardware.org/?probe=890e3a285f) | Jan 18, 2022 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [e88e9c2f3d](https://linux-hardware.org/?probe=e88e9c2f3d) | Jan 17, 2022 |
| LG Electro... | X170-LS10K                  | Notebook    | [6a9d7893ee](https://linux-hardware.org/?probe=6a9d7893ee) | Jan 17, 2022 |
| MSI           | Z77A-GD65                   | Desktop     | [705984b378](https://linux-hardware.org/?probe=705984b378) | Jan 17, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [30edae47a1](https://linux-hardware.org/?probe=30edae47a1) | Jan 17, 2022 |
| Dell          | 0TTDMJ A00                  | Desktop     | [99e6e8d48e](https://linux-hardware.org/?probe=99e6e8d48e) | Jan 17, 2022 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [882906d968](https://linux-hardware.org/?probe=882906d968) | Jan 17, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [7dd316af53](https://linux-hardware.org/?probe=7dd316af53) | Jan 17, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [b90f0a3131](https://linux-hardware.org/?probe=b90f0a3131) | Jan 17, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [f8018a96fb](https://linux-hardware.org/?probe=f8018a96fb) | Jan 17, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [744cfeb340](https://linux-hardware.org/?probe=744cfeb340) | Jan 17, 2022 |
| Acer          | Predator G9-792             | Notebook    | [06a6edfaae](https://linux-hardware.org/?probe=06a6edfaae) | Jan 17, 2022 |
| ASUSTek       | A78M-E                      | Desktop     | [08b4a65622](https://linux-hardware.org/?probe=08b4a65622) | Jan 17, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [7855a0a207](https://linux-hardware.org/?probe=7855a0a207) | Jan 17, 2022 |
| Gigabyte      | Z690 AORUS ELITE DDR4       | Desktop     | [1668e6dc43](https://linux-hardware.org/?probe=1668e6dc43) | Jan 17, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [bfd22356b2](https://linux-hardware.org/?probe=bfd22356b2) | Jan 17, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [93dfa22733](https://linux-hardware.org/?probe=93dfa22733) | Jan 17, 2022 |
| Gigabyte      | Z270X-Gaming 5              | Desktop     | [d1cf9b9344](https://linux-hardware.org/?probe=d1cf9b9344) | Jan 17, 2022 |
| HP            | Pavilion dv7                | Notebook    | [db0283f6c6](https://linux-hardware.org/?probe=db0283f6c6) | Jan 17, 2022 |
| Intel         | NUC8BEB J72688-308          | Mini pc     | [c28502d4bb](https://linux-hardware.org/?probe=c28502d4bb) | Jan 17, 2022 |
| Acer          | Spin SP111-31               | Convertible | [21bfc2a904](https://linux-hardware.org/?probe=21bfc2a904) | Jan 16, 2022 |
| Lenovo        | ThinkPad T410 253725G       | Notebook    | [3e1c463980](https://linux-hardware.org/?probe=3e1c463980) | Jan 16, 2022 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | Notebook    | [03293e9384](https://linux-hardware.org/?probe=03293e9384) | Jan 16, 2022 |
| HUAWEI        | WRTD-WXX9                   | Notebook    | [8f9db79811](https://linux-hardware.org/?probe=8f9db79811) | Jan 16, 2022 |
| Dell          | Vostro 14 5410              | Notebook    | [e3486517d4](https://linux-hardware.org/?probe=e3486517d4) | Jan 16, 2022 |
| MSI           | MS-AA1511                   | All in one  | [bf5395a5d3](https://linux-hardware.org/?probe=bf5395a5d3) | Jan 16, 2022 |
| MSI           | MS-AA1511                   | All in one  | [a54115e872](https://linux-hardware.org/?probe=a54115e872) | Jan 16, 2022 |
| Gigabyte      | GA-78LMT-USB3 x.x           | Desktop     | [91d1d727ec](https://linux-hardware.org/?probe=91d1d727ec) | Jan 16, 2022 |
| HP            | 1497                        | Desktop     | [47f5df0da8](https://linux-hardware.org/?probe=47f5df0da8) | Jan 16, 2022 |
| HP            | Notebook                    | Notebook    | [5d45aad44f](https://linux-hardware.org/?probe=5d45aad44f) | Jan 16, 2022 |
| ASUSTek       | Z97-K                       | Desktop     | [4b03f84c93](https://linux-hardware.org/?probe=4b03f84c93) | Jan 16, 2022 |
| Fujitsu Si... | D2812-A1 S26361-D2812-A1    | Desktop     | [7f01a1ab15](https://linux-hardware.org/?probe=7f01a1ab15) | Jan 16, 2022 |
| MSI           | B350M MORTAR                | Desktop     | [5f93713b6d](https://linux-hardware.org/?probe=5f93713b6d) | Jan 16, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [2098bc3881](https://linux-hardware.org/?probe=2098bc3881) | Jan 16, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V6505        | Notebook    | [4ceae99710](https://linux-hardware.org/?probe=4ceae99710) | Jan 15, 2022 |
| Medion        | WIM2160                     | Notebook    | [5e529f33bc](https://linux-hardware.org/?probe=5e529f33bc) | Jan 15, 2022 |
| AZW           | U59                         | Desktop     | [d036a94aac](https://linux-hardware.org/?probe=d036a94aac) | Jan 15, 2022 |
| Medion        | WIM2160                     | Notebook    | [758e2a7717](https://linux-hardware.org/?probe=758e2a7717) | Jan 15, 2022 |
| Toshiba       | Satellite L50-B             | Notebook    | [c0f3709a57](https://linux-hardware.org/?probe=c0f3709a57) | Jan 15, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [6d015ef040](https://linux-hardware.org/?probe=6d015ef040) | Jan 15, 2022 |
| Notebook      | W230ST                      | Notebook    | [3dacf0aea8](https://linux-hardware.org/?probe=3dacf0aea8) | Jan 15, 2022 |
| Dell          | Latitude E4300              | Notebook    | [9112d33b24](https://linux-hardware.org/?probe=9112d33b24) | Jan 15, 2022 |
| Lenovo        | ThinkPad T420 4236SWF       | Notebook    | [eff9f0ec21](https://linux-hardware.org/?probe=eff9f0ec21) | Jan 15, 2022 |
| Notebook      | W94_95_97SU2,SUY,-C,-T      | Notebook    | [786f091b04](https://linux-hardware.org/?probe=786f091b04) | Jan 15, 2022 |
| HP            | 255 G4 Notebook PC          | Notebook    | [34060f3357](https://linux-hardware.org/?probe=34060f3357) | Jan 15, 2022 |
| MSI           | Z77A-GD65                   | Desktop     | [d6c5cd3656](https://linux-hardware.org/?probe=d6c5cd3656) | Jan 15, 2022 |
| MSI           | X58 Pro-E                   | Desktop     | [32b53a700a](https://linux-hardware.org/?probe=32b53a700a) | Jan 15, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [d423649ed2](https://linux-hardware.org/?probe=d423649ed2) | Jan 15, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e741963fd0](https://linux-hardware.org/?probe=e741963fd0) | Jan 15, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [de49cbdac7](https://linux-hardware.org/?probe=de49cbdac7) | Jan 15, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [7b3700265a](https://linux-hardware.org/?probe=7b3700265a) | Jan 15, 2022 |
| Fujitsu       | D2709 S26361-D2709-A13 W... | Server      | [9ec6cffc99](https://linux-hardware.org/?probe=9ec6cffc99) | Jan 14, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [8ed424ecb0](https://linux-hardware.org/?probe=8ed424ecb0) | Jan 14, 2022 |
| Lenovo        | ThinkPad X240 20AMS4SL00    | Notebook    | [3888a941b9](https://linux-hardware.org/?probe=3888a941b9) | Jan 14, 2022 |
| Fujitsu       | D2709 S26361-D2709-A13 W... | Server      | [c6cf3db6df](https://linux-hardware.org/?probe=c6cf3db6df) | Jan 14, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [1414842f81](https://linux-hardware.org/?probe=1414842f81) | Jan 14, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [d60c747d92](https://linux-hardware.org/?probe=d60c747d92) | Jan 14, 2022 |
| Acer          | Swift SF315-41              | Notebook    | [406aefba8a](https://linux-hardware.org/?probe=406aefba8a) | Jan 14, 2022 |
| ASUSTek       | H110M-C                     | Desktop     | [5dde58c339](https://linux-hardware.org/?probe=5dde58c339) | Jan 14, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [91ac362b29](https://linux-hardware.org/?probe=91ac362b29) | Jan 14, 2022 |
| Pegatron      | IPM31G                      | Desktop     | [7ca6a7c129](https://linux-hardware.org/?probe=7ca6a7c129) | Jan 14, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [f695de13bf](https://linux-hardware.org/?probe=f695de13bf) | Jan 14, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [923572a92b](https://linux-hardware.org/?probe=923572a92b) | Jan 14, 2022 |
| LG Electro... | X170-LS10K                  | Notebook    | [cfd887ad1b](https://linux-hardware.org/?probe=cfd887ad1b) | Jan 14, 2022 |
| ASUSTek       | P50IJ                       | Notebook    | [d9634f128a](https://linux-hardware.org/?probe=d9634f128a) | Jan 14, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [e69fb99ebf](https://linux-hardware.org/?probe=e69fb99ebf) | Jan 14, 2022 |
| Medion        | WIM2100                     | Notebook    | [04cebe2ee2](https://linux-hardware.org/?probe=04cebe2ee2) | Jan 14, 2022 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [6eea3739a1](https://linux-hardware.org/?probe=6eea3739a1) | Jan 14, 2022 |
| Fujitsu Si... | D2464-B1 S26361-D2464-B1    | Desktop     | [962a3a8bb0](https://linux-hardware.org/?probe=962a3a8bb0) | Jan 14, 2022 |
| Dell          | Latitude 3420               | Notebook    | [6577d229a0](https://linux-hardware.org/?probe=6577d229a0) | Jan 14, 2022 |
| ASRock        | Z87 Killer                  | Desktop     | [268b4e1ed2](https://linux-hardware.org/?probe=268b4e1ed2) | Jan 14, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [ba70a4c2dc](https://linux-hardware.org/?probe=ba70a4c2dc) | Jan 14, 2022 |
| Lenovo        | ThinkPad E14 20RA0016GE     | Notebook    | [46eeb2d4b8](https://linux-hardware.org/?probe=46eeb2d4b8) | Jan 14, 2022 |
| HP            | 0AECh D                     | Desktop     | [c42b2d840d](https://linux-hardware.org/?probe=c42b2d840d) | Jan 14, 2022 |
| Lenovo        | G710 20252                  | Notebook    | [136ff28eb8](https://linux-hardware.org/?probe=136ff28eb8) | Jan 14, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [fae944592d](https://linux-hardware.org/?probe=fae944592d) | Jan 14, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [ebdb392f57](https://linux-hardware.org/?probe=ebdb392f57) | Jan 14, 2022 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [7723b652d9](https://linux-hardware.org/?probe=7723b652d9) | Jan 13, 2022 |
| HP            | Pavilion dv9700             | Notebook    | [d91d90792c](https://linux-hardware.org/?probe=d91d90792c) | Jan 13, 2022 |
| HP            | Notebook                    | Notebook    | [61d5ea5f13](https://linux-hardware.org/?probe=61d5ea5f13) | Jan 13, 2022 |
| MSI           | Z77A-GD65                   | Desktop     | [6b97a34c09](https://linux-hardware.org/?probe=6b97a34c09) | Jan 13, 2022 |
| MSI           | GT70                        | Notebook    | [ae15bd941d](https://linux-hardware.org/?probe=ae15bd941d) | Jan 13, 2022 |
| Nvidia        | Tegra                       | Soc         | [a938bbd87f](https://linux-hardware.org/?probe=a938bbd87f) | Jan 13, 2022 |
| Nvidia        | Tegra                       | Soc         | [143a4e3c60](https://linux-hardware.org/?probe=143a4e3c60) | Jan 13, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [03a777b7b1](https://linux-hardware.org/?probe=03a777b7b1) | Jan 13, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [00a00c3cac](https://linux-hardware.org/?probe=00a00c3cac) | Jan 13, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [ad49cdde74](https://linux-hardware.org/?probe=ad49cdde74) | Jan 13, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [3050abff3a](https://linux-hardware.org/?probe=3050abff3a) | Jan 13, 2022 |
| Acer          | Aspire E5-774G              | Notebook    | [bd6fa29ee0](https://linux-hardware.org/?probe=bd6fa29ee0) | Jan 13, 2022 |
| Packard Be... | IMEDIA S1360                | Desktop     | [93a8fdf43c](https://linux-hardware.org/?probe=93a8fdf43c) | Jan 13, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [c0cb966fb7](https://linux-hardware.org/?probe=c0cb966fb7) | Jan 13, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [051ac4ce21](https://linux-hardware.org/?probe=051ac4ce21) | Jan 13, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [eedded0ee5](https://linux-hardware.org/?probe=eedded0ee5) | Jan 13, 2022 |
| MSI           | B75MA-P45                   | Desktop     | [dc73e7a540](https://linux-hardware.org/?probe=dc73e7a540) | Jan 12, 2022 |
| MSI           | B75MA-P45                   | Desktop     | [60d7670ca3](https://linux-hardware.org/?probe=60d7670ca3) | Jan 12, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [e01d513669](https://linux-hardware.org/?probe=e01d513669) | Jan 12, 2022 |
| Lenovo        | ThinkPad E470 20H2S00400    | Notebook    | [d717ae7a04](https://linux-hardware.org/?probe=d717ae7a04) | Jan 12, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [13b34d87ce](https://linux-hardware.org/?probe=13b34d87ce) | Jan 12, 2022 |
| AURES         | W-TOUCH                     | Desktop     | [adc4279e12](https://linux-hardware.org/?probe=adc4279e12) | Jan 12, 2022 |
| Acer          | Spin SP314-54N              | Convertible | [8ae8b9f712](https://linux-hardware.org/?probe=8ae8b9f712) | Jan 12, 2022 |
| Medion        | Akoya THE TOUCH 10          | Notebook    | [7606a573d6](https://linux-hardware.org/?probe=7606a573d6) | Jan 12, 2022 |
| Lenovo        | ThinkPad T420 4180F65       | Notebook    | [be3640daf0](https://linux-hardware.org/?probe=be3640daf0) | Jan 12, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [43ea5ed123](https://linux-hardware.org/?probe=43ea5ed123) | Jan 12, 2022 |
| MSI           | Z370 TOMAHAWK               | Desktop     | [d110296eb8](https://linux-hardware.org/?probe=d110296eb8) | Jan 12, 2022 |
| Supermicro    | X11SDV-4C-TP8F              | Server      | [36434c8979](https://linux-hardware.org/?probe=36434c8979) | Jan 12, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [729fd5a406](https://linux-hardware.org/?probe=729fd5a406) | Jan 12, 2022 |
| ASRock        | 4X4-4000 Series             | Desktop     | [172d5b0abc](https://linux-hardware.org/?probe=172d5b0abc) | Jan 12, 2022 |
| Pegatron      | IPMSB-GS                    | Desktop     | [62ad0508ac](https://linux-hardware.org/?probe=62ad0508ac) | Jan 12, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [46d42db225](https://linux-hardware.org/?probe=46d42db225) | Jan 12, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [5c58aa5b86](https://linux-hardware.org/?probe=5c58aa5b86) | Jan 12, 2022 |
| Acer          | Spin SP314-54N              | Convertible | [fa6a2e7a0e](https://linux-hardware.org/?probe=fa6a2e7a0e) | Jan 12, 2022 |
| Fujitsu       | LIFEBOOK S782               | Notebook    | [054e0bda78](https://linux-hardware.org/?probe=054e0bda78) | Jan 11, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [7ada292e47](https://linux-hardware.org/?probe=7ada292e47) | Jan 11, 2022 |
| MSI           | X99S GAMING 7               | Desktop     | [66556a15be](https://linux-hardware.org/?probe=66556a15be) | Jan 11, 2022 |
| Lenovo        | ThinkPad T500 2089A35       | Notebook    | [7d6198b88a](https://linux-hardware.org/?probe=7d6198b88a) | Jan 11, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [db2f4d2084](https://linux-hardware.org/?probe=db2f4d2084) | Jan 11, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [7a7ddf7315](https://linux-hardware.org/?probe=7a7ddf7315) | Jan 11, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [10dea3ac81](https://linux-hardware.org/?probe=10dea3ac81) | Jan 11, 2022 |
| Fujitsu       | Unknown                     | Notebook    | [676535d4a5](https://linux-hardware.org/?probe=676535d4a5) | Jan 11, 2022 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [672d80e216](https://linux-hardware.org/?probe=672d80e216) | Jan 11, 2022 |
| Gigabyte      | G1.Sniper A88X-CF           | Desktop     | [7dc2a420d0](https://linux-hardware.org/?probe=7dc2a420d0) | Jan 11, 2022 |
| Lenovo        | SKYBAY SDK0J40697 WIN 33... | Desktop     | [368df270dc](https://linux-hardware.org/?probe=368df270dc) | Jan 11, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [1e08ba87bd](https://linux-hardware.org/?probe=1e08ba87bd) | Jan 11, 2022 |
| Acer          | Predator G9-792             | Notebook    | [870f7b6ea5](https://linux-hardware.org/?probe=870f7b6ea5) | Jan 11, 2022 |
| ASUSTek       | P50IJ                       | Notebook    | [1376c55324](https://linux-hardware.org/?probe=1376c55324) | Jan 11, 2022 |
| Lenovo        | ThinkPad T420 4180DY4       | Notebook    | [968c8c3b82](https://linux-hardware.org/?probe=968c8c3b82) | Jan 11, 2022 |
| Medion        | P6612                       | Notebook    | [5329dc71cf](https://linux-hardware.org/?probe=5329dc71cf) | Jan 11, 2022 |
| ASRock        | T48EM1                      | Desktop     | [940b643114](https://linux-hardware.org/?probe=940b643114) | Jan 11, 2022 |
| ASUSTek       | P50IJ                       | Notebook    | [3b1832fd6f](https://linux-hardware.org/?probe=3b1832fd6f) | Jan 11, 2022 |
| Packard Be... | EasyNote LJ65               | Notebook    | [8cc4799786](https://linux-hardware.org/?probe=8cc4799786) | Jan 11, 2022 |
| Acer          | Predator G9-792             | Notebook    | [908edac358](https://linux-hardware.org/?probe=908edac358) | Jan 11, 2022 |
| ASRock        | T48EM1                      | Desktop     | [2dc47923df](https://linux-hardware.org/?probe=2dc47923df) | Jan 11, 2022 |
| Lenovo        | ThinkPad T495s 20QJ0012G... | Notebook    | [57b3cff7ce](https://linux-hardware.org/?probe=57b3cff7ce) | Jan 11, 2022 |
| HP            | Pavilion 17                 | Notebook    | [426745a6c0](https://linux-hardware.org/?probe=426745a6c0) | Jan 11, 2022 |
| Dell          | Latitude E6410              | Notebook    | [8cd72717eb](https://linux-hardware.org/?probe=8cd72717eb) | Jan 11, 2022 |
| Gigabyte      | GA-880GM-D2H                | Desktop     | [140f1ced79](https://linux-hardware.org/?probe=140f1ced79) | Jan 11, 2022 |
| Gigabyte      | GA-880GM-D2H                | Desktop     | [f63fbfe3b2](https://linux-hardware.org/?probe=f63fbfe3b2) | Jan 11, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [f21bede8f0](https://linux-hardware.org/?probe=f21bede8f0) | Jan 11, 2022 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [cda49a0b67](https://linux-hardware.org/?probe=cda49a0b67) | Jan 10, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [4c9489e27a](https://linux-hardware.org/?probe=4c9489e27a) | Jan 10, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | Notebook    | [f922873be6](https://linux-hardware.org/?probe=f922873be6) | Jan 10, 2022 |
| Notebook      | W35xSTQ_370ST               | Notebook    | [3941188ea5](https://linux-hardware.org/?probe=3941188ea5) | Jan 10, 2022 |
| HP            | ProBook x360 11 G5 EE       | Convertible | [2000988c8b](https://linux-hardware.org/?probe=2000988c8b) | Jan 10, 2022 |
| Medion        | MS-7708                     | Desktop     | [730133d40b](https://linux-hardware.org/?probe=730133d40b) | Jan 10, 2022 |
| Gigabyte      | Z87M-D3H                    | Desktop     | [7e4fe3d952](https://linux-hardware.org/?probe=7e4fe3d952) | Jan 10, 2022 |
| Dell          | Inspiron 5758               | Notebook    | [02481ebfaa](https://linux-hardware.org/?probe=02481ebfaa) | Jan 10, 2022 |
| Acer          | Aspire 8930                 | Notebook    | [f6a0d1a6db](https://linux-hardware.org/?probe=f6a0d1a6db) | Jan 10, 2022 |
| Notebook      | W35xSTQ_370ST               | Notebook    | [bc72b6b571](https://linux-hardware.org/?probe=bc72b6b571) | Jan 10, 2022 |
| Dell          | 0XR1GT A00                  | Desktop     | [1c534662b8](https://linux-hardware.org/?probe=1c534662b8) | Jan 10, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [a1afced389](https://linux-hardware.org/?probe=a1afced389) | Jan 10, 2022 |
| Lenovo        | ThinkCentre M91p 4524WAP    | Desktop     | [ce5b35b77b](https://linux-hardware.org/?probe=ce5b35b77b) | Jan 10, 2022 |
| Dell          | Latitude 7420               | Notebook    | [3966cafb18](https://linux-hardware.org/?probe=3966cafb18) | Jan 10, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [6e76d9068e](https://linux-hardware.org/?probe=6e76d9068e) | Jan 10, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [9224684769](https://linux-hardware.org/?probe=9224684769) | Jan 10, 2022 |
| BESSTAR Te... | GB1B                        | Mini pc     | [57a4a3a3ab](https://linux-hardware.org/?probe=57a4a3a3ab) | Jan 10, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [70ba3d0f9d](https://linux-hardware.org/?probe=70ba3d0f9d) | Jan 10, 2022 |
| Lenovo        | IdeaPad S205 1038DHG        | Notebook    | [0ca3d0f485](https://linux-hardware.org/?probe=0ca3d0f485) | Jan 10, 2022 |
| MSI           | Z270 GAMING M5              | Desktop     | [02d70182fd](https://linux-hardware.org/?probe=02d70182fd) | Jan 10, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [6a8c354065](https://linux-hardware.org/?probe=6a8c354065) | Jan 10, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [c658920fd7](https://linux-hardware.org/?probe=c658920fd7) | Jan 10, 2022 |
| Medion        | E2292                       | Convertible | [b3b81f7289](https://linux-hardware.org/?probe=b3b81f7289) | Jan 10, 2022 |
| Lenovo        | ThinkPad L440 20ASS25V00    | Notebook    | [b91a7cb8ae](https://linux-hardware.org/?probe=b91a7cb8ae) | Jan 10, 2022 |
| Lenovo        | ThinkPad T440s 20ARS32P0... | Notebook    | [68cf5d4d4f](https://linux-hardware.org/?probe=68cf5d4d4f) | Jan 09, 2022 |
| HP            | EliteBook 2570p             | Notebook    | [c757e559b0](https://linux-hardware.org/?probe=c757e559b0) | Jan 09, 2022 |
| Supermicro    | X8DTG-QF                    | Server      | [fc83f2123d](https://linux-hardware.org/?probe=fc83f2123d) | Jan 09, 2022 |
| ASUSTek       | TUF GAMING Z690-PLUS D4     | Desktop     | [5066e9278a](https://linux-hardware.org/?probe=5066e9278a) | Jan 09, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [c98201c522](https://linux-hardware.org/?probe=c98201c522) | Jan 09, 2022 |
| Packard Be... | EasyNote LS11HR             | Notebook    | [5a0fc3c36a](https://linux-hardware.org/?probe=5a0fc3c36a) | Jan 09, 2022 |
| Lenovo        | G700 20251                  | Notebook    | [fa5244fec6](https://linux-hardware.org/?probe=fa5244fec6) | Jan 09, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [9545ad4277](https://linux-hardware.org/?probe=9545ad4277) | Jan 09, 2022 |
| Gigabyte      | H110M-D2P-WG-CF             | Desktop     | [74c908ffe6](https://linux-hardware.org/?probe=74c908ffe6) | Jan 09, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [9fc01215dd](https://linux-hardware.org/?probe=9fc01215dd) | Jan 09, 2022 |
| HP            | 0AECh D                     | Desktop     | [f755fbe60f](https://linux-hardware.org/?probe=f755fbe60f) | Jan 09, 2022 |
| ASUSTek       | Z97-K                       | Desktop     | [78f18e59c9](https://linux-hardware.org/?probe=78f18e59c9) | Jan 09, 2022 |
| ASUSTek       | Z97-K                       | Desktop     | [569783a078](https://linux-hardware.org/?probe=569783a078) | Jan 09, 2022 |
| ASUSTek       | PRIME B250-PLUS             | Desktop     | [42ba344da9](https://linux-hardware.org/?probe=42ba344da9) | Jan 09, 2022 |
| Packard Be... | EasyNote LJ65               | Notebook    | [2a2925c947](https://linux-hardware.org/?probe=2a2925c947) | Jan 09, 2022 |
| HP            | Pavilion g7                 | Notebook    | [0f87ff2f9a](https://linux-hardware.org/?probe=0f87ff2f9a) | Jan 09, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [10f53d4021](https://linux-hardware.org/?probe=10f53d4021) | Jan 09, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [7111cfb0e9](https://linux-hardware.org/?probe=7111cfb0e9) | Jan 09, 2022 |
| Dell          | Inspiron 5758               | Notebook    | [c266ccc525](https://linux-hardware.org/?probe=c266ccc525) | Jan 09, 2022 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [45f4229804](https://linux-hardware.org/?probe=45f4229804) | Jan 09, 2022 |
| Packard Be... | EasyNote LJ65               | Notebook    | [a5f94a8daf](https://linux-hardware.org/?probe=a5f94a8daf) | Jan 09, 2022 |
| Biostar       | H81MGV3                     | Desktop     | [533d05d210](https://linux-hardware.org/?probe=533d05d210) | Jan 09, 2022 |
| Acer          | Aspire V3-772               | Notebook    | [ad0599b618](https://linux-hardware.org/?probe=ad0599b618) | Jan 09, 2022 |
| Acer          | Aspire V3-772               | Notebook    | [a5a3785bd4](https://linux-hardware.org/?probe=a5a3785bd4) | Jan 09, 2022 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [7bb3d0ab76](https://linux-hardware.org/?probe=7bb3d0ab76) | Jan 09, 2022 |
| Packard Be... | EasyNote LJ65               | Notebook    | [da49e3e0ae](https://linux-hardware.org/?probe=da49e3e0ae) | Jan 09, 2022 |
| Dell          | Latitude XT2                | Notebook    | [65adc4cb22](https://linux-hardware.org/?probe=65adc4cb22) | Jan 09, 2022 |
| Acer          | Aspire SW5-111              | Notebook    | [7407c41377](https://linux-hardware.org/?probe=7407c41377) | Jan 09, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [8e5e7a9260](https://linux-hardware.org/?probe=8e5e7a9260) | Jan 09, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [4b13bad9ae](https://linux-hardware.org/?probe=4b13bad9ae) | Jan 09, 2022 |
| Supermicro    | X8DTG-QF                    | Server      | [ed8399e2cc](https://linux-hardware.org/?probe=ed8399e2cc) | Jan 09, 2022 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [c6da06ae31](https://linux-hardware.org/?probe=c6da06ae31) | Jan 09, 2022 |
| Sony          | SVS13A1C5E                  | Notebook    | [891a2d4782](https://linux-hardware.org/?probe=891a2d4782) | Jan 09, 2022 |
| Fujitsu Si... | D2156-A1 S26361-D2156-A1    | Desktop     | [dcc677848e](https://linux-hardware.org/?probe=dcc677848e) | Jan 09, 2022 |
| Acer          | Aspire S7-391               | Notebook    | [1c31255215](https://linux-hardware.org/?probe=1c31255215) | Jan 08, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | Notebook    | [947371a733](https://linux-hardware.org/?probe=947371a733) | Jan 08, 2022 |
| Lenovo        | ThinkPad E595 20NFS0NG00    | Notebook    | [74f08c1917](https://linux-hardware.org/?probe=74f08c1917) | Jan 08, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | Notebook    | [8f77dde028](https://linux-hardware.org/?probe=8f77dde028) | Jan 08, 2022 |
| Lenovo        | ThinkPad R500 2714AAG       | Notebook    | [e53d263950](https://linux-hardware.org/?probe=e53d263950) | Jan 08, 2022 |
| Medion        | BEAST X25                   | Notebook    | [5687f78ea3](https://linux-hardware.org/?probe=5687f78ea3) | Jan 08, 2022 |
| Medion        | BEAST X25                   | Notebook    | [7e8d4b82bc](https://linux-hardware.org/?probe=7e8d4b82bc) | Jan 08, 2022 |
| Dell          | Inspiron 7706 2n1           | Convertible | [6f35279114](https://linux-hardware.org/?probe=6f35279114) | Jan 08, 2022 |
| Gigabyte      | MJPLNAB-00                  | Desktop     | [79d90bf440](https://linux-hardware.org/?probe=79d90bf440) | Jan 08, 2022 |
| ASUSTek       | Z97-K                       | Desktop     | [87ffc81034](https://linux-hardware.org/?probe=87ffc81034) | Jan 08, 2022 |
| HP            | 3398                        | Desktop     | [b36bba1dac](https://linux-hardware.org/?probe=b36bba1dac) | Jan 08, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [14e41b405a](https://linux-hardware.org/?probe=14e41b405a) | Jan 08, 2022 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [dd061ae267](https://linux-hardware.org/?probe=dd061ae267) | Jan 08, 2022 |
| Medion        | Akoya THE TOUCH 10          | Notebook    | [753fcd1661](https://linux-hardware.org/?probe=753fcd1661) | Jan 08, 2022 |
| Medion        | Akoya THE TOUCH 10          | Notebook    | [af239c06c8](https://linux-hardware.org/?probe=af239c06c8) | Jan 08, 2022 |
| ASUSTek       | B43E                        | Notebook    | [885fc6e55b](https://linux-hardware.org/?probe=885fc6e55b) | Jan 08, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [9d29b20f2d](https://linux-hardware.org/?probe=9d29b20f2d) | Jan 08, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [4026f1e18c](https://linux-hardware.org/?probe=4026f1e18c) | Jan 08, 2022 |
| ASUSTek       | Z97-K                       | Desktop     | [43b421ad06](https://linux-hardware.org/?probe=43b421ad06) | Jan 08, 2022 |
| Wortmann      | TERRA_PC                    | Desktop     | [16239fb870](https://linux-hardware.org/?probe=16239fb870) | Jan 08, 2022 |
| HP            | 3398                        | Desktop     | [9f6575f374](https://linux-hardware.org/?probe=9f6575f374) | Jan 08, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [d3b89ef42a](https://linux-hardware.org/?probe=d3b89ef42a) | Jan 08, 2022 |
| Acer          | Aspire C27-962              | All in one  | [f15ca34264](https://linux-hardware.org/?probe=f15ca34264) | Jan 08, 2022 |
| Schenker      | N24_25JU                    | Notebook    | [b847cd914a](https://linux-hardware.org/?probe=b847cd914a) | Jan 08, 2022 |
| HP            | 1496                        | Desktop     | [9b373bd8f1](https://linux-hardware.org/?probe=9b373bd8f1) | Jan 08, 2022 |
| Acer          | Aspire XC-105               | Desktop     | [3c3281b716](https://linux-hardware.org/?probe=3c3281b716) | Jan 08, 2022 |
| HP            | 3048h                       | Desktop     | [8580cdd56f](https://linux-hardware.org/?probe=8580cdd56f) | Jan 08, 2022 |
| HP            | 8643 SMVB                   | Desktop     | [0ab2fce296](https://linux-hardware.org/?probe=0ab2fce296) | Jan 08, 2022 |
| BESSTAR Te... | AB1A                        | Mini pc     | [6874bc3566](https://linux-hardware.org/?probe=6874bc3566) | Jan 08, 2022 |
| Notebook      | NH5x_NH7x_HHx_HJx_HKx       | Notebook    | [2aefd7833a](https://linux-hardware.org/?probe=2aefd7833a) | Jan 07, 2022 |
| Dell          | Precision 5510              | Notebook    | [98a122eac7](https://linux-hardware.org/?probe=98a122eac7) | Jan 07, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [ca93455055](https://linux-hardware.org/?probe=ca93455055) | Jan 07, 2022 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [ea6b18dff1](https://linux-hardware.org/?probe=ea6b18dff1) | Jan 07, 2022 |
| Gigabyte      | B85-HD3                     | Desktop     | [e18e4826c0](https://linux-hardware.org/?probe=e18e4826c0) | Jan 07, 2022 |
| Sony          | VPCEB2Z1E                   | Notebook    | [40bc339ad3](https://linux-hardware.org/?probe=40bc339ad3) | Jan 07, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [39baad1df0](https://linux-hardware.org/?probe=39baad1df0) | Jan 07, 2022 |
| ASRock        | AM1B-ITX                    | Desktop     | [c374329271](https://linux-hardware.org/?probe=c374329271) | Jan 07, 2022 |
| ASUSTek       | K70IO                       | Notebook    | [f4332a9d8c](https://linux-hardware.org/?probe=f4332a9d8c) | Jan 07, 2022 |
| Sony          | VPCEB2Z1E                   | Notebook    | [4e59f301b2](https://linux-hardware.org/?probe=4e59f301b2) | Jan 07, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [f24fe9346e](https://linux-hardware.org/?probe=f24fe9346e) | Jan 07, 2022 |
| Medion        | H110H4-EM                   | Desktop     | [5d991fa9a1](https://linux-hardware.org/?probe=5d991fa9a1) | Jan 07, 2022 |
| eMachines     | G625                        | Notebook    | [1c60347748](https://linux-hardware.org/?probe=1c60347748) | Jan 07, 2022 |
| eMachines     | G625                        | Notebook    | [834d67571c](https://linux-hardware.org/?probe=834d67571c) | Jan 07, 2022 |
| Lenovo        | ThinkPad SL510 28476NG      | Notebook    | [8377f84130](https://linux-hardware.org/?probe=8377f84130) | Jan 07, 2022 |
| ZOTAC         | ZBOX-AD04                   | Mini pc     | [be96f10577](https://linux-hardware.org/?probe=be96f10577) | Jan 07, 2022 |
| HP            | ProBook x360 435 G8 Note... | Convertible | [e4575333f4](https://linux-hardware.org/?probe=e4575333f4) | Jan 07, 2022 |
| HUAWEI        | HN-WX9X                     | Notebook    | [8627687145](https://linux-hardware.org/?probe=8627687145) | Jan 07, 2022 |
| Dell          | Inspiron 7706 2n1           | Convertible | [1820072259](https://linux-hardware.org/?probe=1820072259) | Jan 07, 2022 |
| Sony          | VPCEA3S1E                   | Notebook    | [670b7a5d31](https://linux-hardware.org/?probe=670b7a5d31) | Jan 07, 2022 |
| Lenovo        | ThinkPad T440s 20AQ009DG... | Notebook    | [61f5e99aff](https://linux-hardware.org/?probe=61f5e99aff) | Jan 07, 2022 |
| Acer          | Aspire ES1-523              | Notebook    | [23c9b1e776](https://linux-hardware.org/?probe=23c9b1e776) | Jan 07, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [ee6b48f115](https://linux-hardware.org/?probe=ee6b48f115) | Jan 07, 2022 |
| Chuwi         | Hi10 X                      | Tablet      | [5d8b5e0c8e](https://linux-hardware.org/?probe=5d8b5e0c8e) | Jan 07, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [79be6c615c](https://linux-hardware.org/?probe=79be6c615c) | Jan 07, 2022 |
| Dell          | Latitude E6500              | Notebook    | [8355df56a3](https://linux-hardware.org/?probe=8355df56a3) | Jan 07, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [596fafa091](https://linux-hardware.org/?probe=596fafa091) | Jan 07, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [639c7cbb68](https://linux-hardware.org/?probe=639c7cbb68) | Jan 06, 2022 |
| Acer          | Aspire ES1-523              | Notebook    | [cf4fa3b6c2](https://linux-hardware.org/?probe=cf4fa3b6c2) | Jan 06, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [5007c527a3](https://linux-hardware.org/?probe=5007c527a3) | Jan 06, 2022 |
| ASRock        | Z75 Pro3                    | Desktop     | [e7c4424882](https://linux-hardware.org/?probe=e7c4424882) | Jan 06, 2022 |
| Dell          | 0TTDMJ A00                  | Desktop     | [34c426e4e4](https://linux-hardware.org/?probe=34c426e4e4) | Jan 06, 2022 |
| Dell          | 0K240Y A01                  | Desktop     | [2542ffac8a](https://linux-hardware.org/?probe=2542ffac8a) | Jan 06, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [3d1225c6e9](https://linux-hardware.org/?probe=3d1225c6e9) | Jan 06, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [8a245360d3](https://linux-hardware.org/?probe=8a245360d3) | Jan 06, 2022 |
| BESSTAR Te... | HM50                        | Desktop     | [1ca6712001](https://linux-hardware.org/?probe=1ca6712001) | Jan 06, 2022 |
| HP            | 3396                        | Desktop     | [939dc1ef96](https://linux-hardware.org/?probe=939dc1ef96) | Jan 06, 2022 |
| HP            | 3396                        | Desktop     | [39df16b288](https://linux-hardware.org/?probe=39df16b288) | Jan 06, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [15431686d8](https://linux-hardware.org/?probe=15431686d8) | Jan 06, 2022 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | Desktop     | [7a166402d8](https://linux-hardware.org/?probe=7a166402d8) | Jan 06, 2022 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [3412915dd0](https://linux-hardware.org/?probe=3412915dd0) | Jan 06, 2022 |
| TrekStor      | Primetab T13B               | Tablet      | [47bf32530f](https://linux-hardware.org/?probe=47bf32530f) | Jan 06, 2022 |
| Toshiba       | Satellite A200              | Notebook    | [613096a5ad](https://linux-hardware.org/?probe=613096a5ad) | Jan 06, 2022 |
| Gigabyte      | D525TUD                     | Desktop     | [bc75234559](https://linux-hardware.org/?probe=bc75234559) | Jan 06, 2022 |
| Lenovo        | ThinkPad T420 4180AJ3       | Notebook    | [d744cfb251](https://linux-hardware.org/?probe=d744cfb251) | Jan 06, 2022 |
| Medion        | E3222 MD63150               | Convertible | [5d9e80840a](https://linux-hardware.org/?probe=5d9e80840a) | Jan 06, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [d331d91cd7](https://linux-hardware.org/?probe=d331d91cd7) | Jan 06, 2022 |
| Lenovo        | ThinkPad E480 20KN009QGE    | Notebook    | [2f0f726202](https://linux-hardware.org/?probe=2f0f726202) | Jan 06, 2022 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | Notebook    | [7ff88b76ff](https://linux-hardware.org/?probe=7ff88b76ff) | Jan 06, 2022 |
| HP            | ProBook 6460b               | Notebook    | [344d4bf578](https://linux-hardware.org/?probe=344d4bf578) | Jan 06, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [5e3bc2958f](https://linux-hardware.org/?probe=5e3bc2958f) | Jan 06, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [6b366d0bda](https://linux-hardware.org/?probe=6b366d0bda) | Jan 06, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [fbc46e16c6](https://linux-hardware.org/?probe=fbc46e16c6) | Jan 06, 2022 |
| Notebook      | W35xSTQ_370ST               | Notebook    | [f5948a8093](https://linux-hardware.org/?probe=f5948a8093) | Jan 05, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [13caf15327](https://linux-hardware.org/?probe=13caf15327) | Jan 05, 2022 |
| Lenovo        | ThinkPad T61 6463WCH        | Notebook    | [b0936c6830](https://linux-hardware.org/?probe=b0936c6830) | Jan 05, 2022 |
| Acer          | Aspire TC-605               | Desktop     | [14c214290f](https://linux-hardware.org/?probe=14c214290f) | Jan 05, 2022 |
| Gigabyte      | H67MA-USB3-B3               | Desktop     | [aae3c5234f](https://linux-hardware.org/?probe=aae3c5234f) | Jan 05, 2022 |
| Acer          | Aspire ES1-311              | Notebook    | [29f8e6e5ca](https://linux-hardware.org/?probe=29f8e6e5ca) | Jan 05, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [bc5837ca50](https://linux-hardware.org/?probe=bc5837ca50) | Jan 05, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [63a33e04a8](https://linux-hardware.org/?probe=63a33e04a8) | Jan 05, 2022 |
| ASUSTek       | ZenBook UX363EA_UX371EA     | Convertible | [270f24627b](https://linux-hardware.org/?probe=270f24627b) | Jan 05, 2022 |
| Gigabyte      | D525TUD                     | Desktop     | [3d44173eda](https://linux-hardware.org/?probe=3d44173eda) | Jan 05, 2022 |
| HP            | Pavilion dv7                | Notebook    | [fff293f7e9](https://linux-hardware.org/?probe=fff293f7e9) | Jan 05, 2022 |
| Notebook      | W35xSTQ_370ST               | Notebook    | [8c30052212](https://linux-hardware.org/?probe=8c30052212) | Jan 05, 2022 |
| MSI           | MS-B0A1                     | Desktop     | [110935722f](https://linux-hardware.org/?probe=110935722f) | Jan 05, 2022 |
| Lenovo        | ThinkPad X220 4290EC5       | Notebook    | [4ae7cf7f34](https://linux-hardware.org/?probe=4ae7cf7f34) | Jan 05, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [fc860fdb7a](https://linux-hardware.org/?probe=fc860fdb7a) | Jan 05, 2022 |
| Notebook      | NL5xRU                      | Notebook    | [39b60e131a](https://linux-hardware.org/?probe=39b60e131a) | Jan 05, 2022 |
| Lenovo        | ThinkPad E480 20KN009QGE    | Notebook    | [1d12aa3fa9](https://linux-hardware.org/?probe=1d12aa3fa9) | Jan 05, 2022 |
| Gigabyte      | D525TUD                     | Desktop     | [759f405820](https://linux-hardware.org/?probe=759f405820) | Jan 05, 2022 |
| Fujitsu       | LIFEBOOK U7510              | Notebook    | [6e5d25e99f](https://linux-hardware.org/?probe=6e5d25e99f) | Jan 05, 2022 |
| MSI           | Z270 GAMING PRO CARBON      | Desktop     | [f00aac4419](https://linux-hardware.org/?probe=f00aac4419) | Jan 05, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [8e11cb731a](https://linux-hardware.org/?probe=8e11cb731a) | Jan 05, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [7d66181ba1](https://linux-hardware.org/?probe=7d66181ba1) | Jan 05, 2022 |
| MSI           | H61MU-E35                   | Desktop     | [5694489e55](https://linux-hardware.org/?probe=5694489e55) | Jan 05, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | Desktop     | [c05eb652bd](https://linux-hardware.org/?probe=c05eb652bd) | Jan 05, 2022 |
| Raspberry ... | rpi                         | Soc         | [9806b5ab79](https://linux-hardware.org/?probe=9806b5ab79) | Jan 05, 2022 |
| MSI           | H61MU-E35                   | Desktop     | [c9ece2a64e](https://linux-hardware.org/?probe=c9ece2a64e) | Jan 05, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [7873064c34](https://linux-hardware.org/?probe=7873064c34) | Jan 05, 2022 |
| Medion        | MS-7728                     | Desktop     | [c450aeb1bf](https://linux-hardware.org/?probe=c450aeb1bf) | Jan 05, 2022 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [a03672b4e9](https://linux-hardware.org/?probe=a03672b4e9) | Jan 05, 2022 |
| Medion        | H81H3-EM2                   | Desktop     | [90043844f2](https://linux-hardware.org/?probe=90043844f2) | Jan 05, 2022 |
| Acer          | Aspire E1-570               | Notebook    | [2ff1ed4b2c](https://linux-hardware.org/?probe=2ff1ed4b2c) | Jan 05, 2022 |
| Gigabyte      | GA-880GA-UD3H               | Desktop     | [40324b4766](https://linux-hardware.org/?probe=40324b4766) | Jan 05, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [d4b7cd87ac](https://linux-hardware.org/?probe=d4b7cd87ac) | Jan 05, 2022 |
| ASRock        | Z77 Pro4                    | Desktop     | [d83cbe9961](https://linux-hardware.org/?probe=d83cbe9961) | Jan 05, 2022 |
| Lenovo        | ThinkCentre M81 5049W16     | Desktop     | [09727504a3](https://linux-hardware.org/?probe=09727504a3) | Jan 05, 2022 |
| Samsung       | 900X3C/900X3D/900X3E/900... | Notebook    | [520ced18c4](https://linux-hardware.org/?probe=520ced18c4) | Jan 05, 2022 |
| TUXEDO        | BC1510 1710                 | Notebook    | [6f516d87e2](https://linux-hardware.org/?probe=6f516d87e2) | Jan 05, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [2226b8f419](https://linux-hardware.org/?probe=2226b8f419) | Jan 05, 2022 |
| Dell          | Vostro 5471                 | Notebook    | [4057935870](https://linux-hardware.org/?probe=4057935870) | Jan 05, 2022 |
| AXDIA Inte... | MYBOOK 14 PRO               | Notebook    | [f691531281](https://linux-hardware.org/?probe=f691531281) | Jan 05, 2022 |
| HP            | ProBook 450 G2              | Notebook    | [86890c8e71](https://linux-hardware.org/?probe=86890c8e71) | Jan 04, 2022 |
| HP            | ProBook 450 G2              | Notebook    | [9e2ac77ec4](https://linux-hardware.org/?probe=9e2ac77ec4) | Jan 04, 2022 |
| ASUSTek       | F5R                         | Notebook    | [466253c124](https://linux-hardware.org/?probe=466253c124) | Jan 04, 2022 |
| Lenovo        | ThinkPad T420 4236SWF       | Notebook    | [469e243f80](https://linux-hardware.org/?probe=469e243f80) | Jan 04, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [c84b603f92](https://linux-hardware.org/?probe=c84b603f92) | Jan 04, 2022 |
| ASRock        | N68-S                       | Desktop     | [2336710edb](https://linux-hardware.org/?probe=2336710edb) | Jan 04, 2022 |
| Lenovo        | ThinkPad W541 20EGS1VV00    | Notebook    | [5d88eb323c](https://linux-hardware.org/?probe=5d88eb323c) | Jan 04, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [3d15bf4d48](https://linux-hardware.org/?probe=3d15bf4d48) | Jan 04, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [b53f61eeab](https://linux-hardware.org/?probe=b53f61eeab) | Jan 04, 2022 |
| ASUSTek       | X751LK                      | Notebook    | [c155fbdd7b](https://linux-hardware.org/?probe=c155fbdd7b) | Jan 04, 2022 |
| MSI           | H61MU-E35                   | Desktop     | [2c3f24c851](https://linux-hardware.org/?probe=2c3f24c851) | Jan 04, 2022 |
| Medion        | P6620                       | Notebook    | [dbf6822c89](https://linux-hardware.org/?probe=dbf6822c89) | Jan 04, 2022 |
| Lenovo        | ThinkPad L390 Yoga 20NT0... | Convertible | [c91feb11a8](https://linux-hardware.org/?probe=c91feb11a8) | Jan 04, 2022 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | Notebook    | [c10faa4e15](https://linux-hardware.org/?probe=c10faa4e15) | Jan 04, 2022 |
| Fujitsu       | LIFEBOOK E556               | Notebook    | [efedaea970](https://linux-hardware.org/?probe=efedaea970) | Jan 04, 2022 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | Notebook    | [27d434def2](https://linux-hardware.org/?probe=27d434def2) | Jan 04, 2022 |
| Lenovo        | ThinkPad T430s 2356BQ5      | Notebook    | [217fe39d3f](https://linux-hardware.org/?probe=217fe39d3f) | Jan 04, 2022 |
| Acer          | Aspire 6930G                | Notebook    | [929cea53e3](https://linux-hardware.org/?probe=929cea53e3) | Jan 04, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [5154f6ffe2](https://linux-hardware.org/?probe=5154f6ffe2) | Jan 04, 2022 |
| Dell          | Inspiron 1750               | Notebook    | [827adb411f](https://linux-hardware.org/?probe=827adb411f) | Jan 04, 2022 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | Desktop     | [c778e8e570](https://linux-hardware.org/?probe=c778e8e570) | Jan 04, 2022 |
| Dell          | 032W55 A03                  | Desktop     | [e68d1bd4aa](https://linux-hardware.org/?probe=e68d1bd4aa) | Jan 04, 2022 |
| Lenovo        | ThinkPad X250 20CLS0E705    | Notebook    | [80a5a608e3](https://linux-hardware.org/?probe=80a5a608e3) | Jan 04, 2022 |
| Dell          | 032W55 A03                  | Desktop     | [f3838abaaf](https://linux-hardware.org/?probe=f3838abaaf) | Jan 04, 2022 |
| Dell          | 0TTDMJ A00                  | Desktop     | [e43e4e661d](https://linux-hardware.org/?probe=e43e4e661d) | Jan 04, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [b838b1e1cc](https://linux-hardware.org/?probe=b838b1e1cc) | Jan 04, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [d595df0e84](https://linux-hardware.org/?probe=d595df0e84) | Jan 04, 2022 |
| HP            | 1497                        | Desktop     | [a75c612918](https://linux-hardware.org/?probe=a75c612918) | Jan 04, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [9f198f45b9](https://linux-hardware.org/?probe=9f198f45b9) | Jan 04, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [c8a27beaf7](https://linux-hardware.org/?probe=c8a27beaf7) | Jan 04, 2022 |
| Gigabyte      | H57M-USB3                   | Desktop     | [71d90e1797](https://linux-hardware.org/?probe=71d90e1797) | Jan 04, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Germany/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 2622      | 18.23%  |
| Ubuntu 18.04        | 1241      | 8.63%   |
| Linux Mint 20.2     | 547       | 3.8%    |
| OpenMandriva 4.2    | 539       | 3.75%   |
| Linux Mint 20.1     | 350       | 2.43%   |
| Ubuntu 20.10        | 344       | 2.39%   |
| OpenMandriva 4.3    | 342       | 2.38%   |
| Ubuntu 21.10        | 326       | 2.27%   |
| Linux Mint 20       | 281       | 1.95%   |
| Linux Mint 19.3     | 273       | 1.9%    |
| Manjaro             | 269       | 1.87%   |
| Arch                | 261       | 1.81%   |
| Linux Mint 20.3     | 259       | 1.8%    |
| Ubuntu 21.04        | 239       | 1.66%   |
| Xubuntu 20.04       | 238       | 1.65%   |
| Debian 11           | 225       | 1.56%   |
| Ubuntu 19.10        | 219       | 1.52%   |
| KDE neon 20.04      | 211       | 1.47%   |
| Ubuntu 19.04        | 202       | 1.4%    |
| Arch Rolling        | 182       | 1.27%   |
| Debian 10           | 160       | 1.11%   |
| Zorin 16            | 152       | 1.06%   |
| BlackPanther 18.1   | 139       | 0.97%   |
| Pop!_OS 20.10       | 137       | 0.95%   |
| Fedora 33           | 137       | 0.95%   |
| Kubuntu 20.04       | 123       | 0.86%   |
| Pop!_OS 21.04       | 114       | 0.79%   |
| Pop!_OS 20.04       | 114       | 0.79%   |
| Fedora 32           | 113       | 0.79%   |
| Linux Mint 19.2     | 107       | 0.74%   |
| Zorin 15            | 104       | 0.72%   |
| Fedora 34           | 104       | 0.72%   |
| Ubuntu 16.04        | 103       | 0.72%   |
| Ubuntu 18.10        | 101       | 0.7%    |
| Fedora 35           | 96        | 0.67%   |
| Linux Mint 19.1     | 90        | 0.63%   |
| Xubuntu 18.04       | 88        | 0.61%   |
| ROSA R11            | 84        | 0.58%   |
| ROSA R10            | 84        | 0.58%   |
| Gentoo 2.7          | 80        | 0.56%   |
| ArcoLinux Rolling   | 78        | 0.54%   |
| Debian Testing      | 74        | 0.51%   |
| Pop!_OS 21.10       | 72        | 0.5%    |
| Gentoo 2.6          | 69        | 0.48%   |
| Fedora 31           | 67        | 0.47%   |
| ROSA R9             | 56        | 0.39%   |
| Ubuntu MATE 20.04   | 55        | 0.38%   |
| ROSA R8.1           | 52        | 0.36%   |
| ROSA R11.1          | 51        | 0.35%   |
| openSUSE Leap-15.2  | 51        | 0.35%   |
| Elementary 6.1      | 50        | 0.35%   |
| Ubuntu 22.04        | 49        | 0.34%   |
| Linux Mint 19       | 47        | 0.33%   |
| LMDE 4              | 46        | 0.32%   |
| Ubuntu Budgie 20.04 | 43        | 0.3%    |
| OpenMandriva 4.50   | 42        | 0.29%   |
| Manjaro 20.2.1      | 38        | 0.26%   |
| Manjaro 20.2        | 37        | 0.26%   |
| Debian 9            | 36        | 0.25%   |
| Kubuntu 20.10       | 35        | 0.24%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 5195      | 38.19%  |
| Linux Mint    | 1830      | 13.45%  |
| OpenMandriva  | 925       | 6.8%    |
| Manjaro       | 585       | 4.3%    |
| Debian        | 516       | 3.79%   |
| Fedora        | 497       | 3.65%   |
| Arch          | 431       | 3.17%   |
| Pop!_OS       | 430       | 3.16%   |
| Xubuntu       | 408       | 3%      |
| ROSA          | 319       | 2.35%   |
| Zorin         | 276       | 2.03%   |
| Kubuntu       | 270       | 1.99%   |
| KDE neon      | 233       | 1.71%   |
| openSUSE      | 231       | 1.7%    |
| Gentoo        | 158       | 1.16%   |
| BlackPanther  | 150       | 1.1%    |
| Endless       | 127       | 0.93%   |
| Ubuntu MATE   | 108       | 0.79%   |
| Elementary    | 106       | 0.78%   |
| ArcoLinux     | 90        | 0.66%   |
| Ubuntu Budgie | 69        | 0.51%   |
| Kali          | 56        | 0.41%   |
| Lubuntu       | 55        | 0.4%    |
| LMDE          | 49        | 0.36%   |
| EndeavourOS   | 42        | 0.31%   |
| CentOS        | 42        | 0.31%   |
| Clear Linux   | 37        | 0.27%   |
| MX            | 26        | 0.19%   |
| Garuda Linux  | 25        | 0.18%   |
| Peppermint    | 24        | 0.18%   |
| QTS           | 21        | 0.15%   |
| Parrot        | 20        | 0.15%   |
| LinuxFX       | 17        | 0.12%   |
| RHEL          | 15        | 0.11%   |
| Raspbian      | 15        | 0.11%   |
| Artix         | 15        | 0.11%   |
| Deepin        | 12        | 0.09%   |
| Siduction     | 11        | 0.08%   |
| Reborn OS     | 11        | 0.08%   |
| antergos      | 10        | 0.07%   |
| Void Linux    | 9         | 0.07%   |
| Mageia        | 9         | 0.07%   |
| Solus         | 8         | 0.06%   |
| NixOS         | 8         | 0.06%   |
| Oracle Linux  | 7         | 0.05%   |
| PureOS        | 6         | 0.04%   |
| Slackware     | 5         | 0.04%   |
| Manjaro-ARM   | 5         | 0.04%   |
| Makulu        | 5         | 0.04%   |
| Devuan        | 5         | 0.04%   |
| antiX         | 5         | 0.04%   |
| Xero          | 4         | 0.03%   |
| SteamOS       | 4         | 0.03%   |
| Sparky        | 4         | 0.03%   |
| Linux Lite    | 4         | 0.03%   |
| Android       | 4         | 0.03%   |
| Alpine        | 4         | 0.03%   |
| PostmarketOS  | 3         | 0.02%   |
| Hefftor       | 3         | 0.02%   |
| AlmaLinux     | 3         | 0.02%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 516       | 3.16%   |
| 5.16.7-desktop-1omv4003  | 338       | 2.07%   |
| 5.4.0-42-generic         | 311       | 1.91%   |
| 5.4.0-58-generic         | 226       | 1.39%   |
| 5.4.0-52-generic         | 182       | 1.12%   |
| 5.4.0-48-generic         | 179       | 1.1%    |
| 5.4.0-91-generic         | 167       | 1.02%   |
| 5.4.0-26-generic         | 136       | 0.83%   |
| 5.4.0-65-generic         | 121       | 0.74%   |
| 5.11.0-37-generic        | 118       | 0.72%   |
| 5.8.0-43-generic         | 117       | 0.72%   |
| 5.4.0-40-generic         | 117       | 0.72%   |
| 5.4.0-54-generic         | 116       | 0.71%   |
| 5.11.0-38-generic        | 115       | 0.71%   |
| 5.11.0-27-generic        | 115       | 0.71%   |
| 5.13.0-28-generic        | 114       | 0.7%    |
| 5.13.0-39-generic        | 111       | 0.68%   |
| 5.4.0-29-generic         | 110       | 0.67%   |
| 5.3.0-40-generic         | 108       | 0.66%   |
| 5.11.0-40-generic        | 106       | 0.65%   |
| 5.4.0-33-generic         | 104       | 0.64%   |
| 5.4.0-72-generic         | 99        | 0.61%   |
| 5.4.0-56-generic         | 99        | 0.61%   |
| 4.18.16-desktop-1bP      | 99        | 0.61%   |
| 5.4.0-37-generic         | 94        | 0.58%   |
| 5.13.0-30-generic        | 94        | 0.58%   |
| 5.4.0-81-generic         | 92        | 0.56%   |
| 5.4.0-80-generic         | 92        | 0.56%   |
| 5.8.0-44-generic         | 91        | 0.56%   |
| 5.4.0-90-generic         | 91        | 0.56%   |
| 5.4.0-74-generic         | 90        | 0.55%   |
| 5.4.0-47-generic         | 89        | 0.55%   |
| 5.11.0-43-generic        | 87        | 0.53%   |
| 5.8.0-59-generic         | 86        | 0.53%   |
| 5.11.0-25-generic        | 85        | 0.52%   |
| 5.4.0-70-generic         | 83        | 0.51%   |
| 5.11.0-34-generic        | 83        | 0.51%   |
| 5.4.0-77-generic         | 82        | 0.5%    |
| 5.4.0-66-generic         | 82        | 0.5%    |
| 5.11.0-41-generic        | 81        | 0.5%    |
| 5.0.0-37-generic         | 81        | 0.5%    |
| 5.8.0-53-generic         | 80        | 0.49%   |
| 5.13.0-27-generic        | 80        | 0.49%   |
| 5.3.0-28-generic         | 79        | 0.48%   |
| 5.8.0-7630-generic       | 78        | 0.48%   |
| 5.4.0-89-generic         | 78        | 0.48%   |
| 5.4.0-88-generic         | 77        | 0.47%   |
| 5.3.0-46-generic         | 76        | 0.47%   |
| 5.8.0-48-generic         | 74        | 0.45%   |
| 5.8.0-50-generic         | 73        | 0.45%   |
| 5.4.0-73-generic         | 73        | 0.45%   |
| 5.13.0-22-generic        | 73        | 0.45%   |
| 5.8.0-41-generic         | 71        | 0.44%   |
| 5.3.0-42-generic         | 71        | 0.44%   |
| 5.4.0-45-generic         | 69        | 0.42%   |
| 5.4.0-31-generic         | 68        | 0.42%   |
| 5.0.0-32-generic         | 66        | 0.4%    |
| 4.15.0-43-generic        | 66        | 0.4%    |
| 4.18.0-15-generic        | 64        | 0.39%   |
| 5.4.0-28-generic         | 63        | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 3624      | 24.41%  |
| 5.8.0   | 1203      | 8.1%    |
| 4.15.0  | 1151      | 7.75%   |
| 5.11.0  | 1114      | 7.5%    |
| 5.13.0  | 838       | 5.65%   |
| 5.3.0   | 696       | 4.69%   |
| 5.10.14 | 521       | 3.51%   |
| 5.0.0   | 488       | 3.29%   |
| 4.18.0  | 357       | 2.41%   |
| 5.16.7  | 347       | 2.34%   |
| 5.10.0  | 265       | 1.79%   |
| 4.19.0  | 167       | 1.13%   |
| 4.18.16 | 108       | 0.73%   |
| 5.15.0  | 100       | 0.67%   |
| 5.3.18  | 69        | 0.46%   |
| 4.9.20  | 60        | 0.4%    |
| 4.4.0   | 59        | 0.4%    |
| 4.9.60  | 58        | 0.39%   |
| 5.14.0  | 48        | 0.32%   |
| 5.9.16  | 47        | 0.32%   |
| 5.9.0   | 46        | 0.31%   |
| 5.6.0   | 44        | 0.3%    |
| 5.6.14  | 43        | 0.29%   |
| 5.12.4  | 43        | 0.29%   |
| 5.11.12 | 43        | 0.29%   |
| 5.9.11  | 42        | 0.28%   |
| 5.17.1  | 40        | 0.27%   |
| 5.8.16  | 36        | 0.24%   |
| 5.7.0   | 35        | 0.24%   |
| 4.12.14 | 34        | 0.23%   |
| 5.9.8   | 32        | 0.22%   |
| 5.11.16 | 30        | 0.2%    |
| 5.15.12 | 29        | 0.2%    |
| 5.13.19 | 29        | 0.2%    |
| 4.9.0   | 29        | 0.2%    |
| 5.16.0  | 28        | 0.19%   |
| 5.8.18  | 27        | 0.18%   |
| 5.9.1   | 26        | 0.18%   |
| 5.8.11  | 26        | 0.18%   |
| 5.13.8  | 26        | 0.18%   |
| 5.14.14 | 25        | 0.17%   |
| 4.1.38  | 25        | 0.17%   |
| 5.16.11 | 24        | 0.16%   |
| 5.15.8  | 24        | 0.16%   |
| 5.9.10  | 23        | 0.15%   |
| 5.15.7  | 23        | 0.15%   |
| 5.11.11 | 23        | 0.15%   |
| 5.10.7  | 23        | 0.15%   |
| 4.13.0  | 23        | 0.15%   |
| 5.6.15  | 22        | 0.15%   |
| 3.10.0  | 22        | 0.15%   |
| 5.13.13 | 21        | 0.14%   |
| 5.11.6  | 21        | 0.14%   |
| 5.5.0   | 20        | 0.13%   |
| 5.15.5  | 20        | 0.13%   |
| 5.15.15 | 20        | 0.13%   |
| 5.1.15  | 20        | 0.13%   |
| 5.8.6   | 19        | 0.13%   |
| 5.7.9   | 19        | 0.13%   |
| 4.14.24 | 19        | 0.13%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 3863      | 26.37%  |
| 5.8     | 1437      | 9.81%   |
| 5.11    | 1329      | 9.07%   |
| 4.15    | 1160      | 7.92%   |
| 5.10    | 1100      | 7.51%   |
| 5.13    | 999       | 6.82%   |
| 5.3     | 830       | 5.67%   |
| 5.16    | 543       | 3.71%   |
| 5.0     | 511       | 3.49%   |
| 4.18    | 479       | 3.27%   |
| 5.15    | 370       | 2.53%   |
| 5.9     | 281       | 1.92%   |
| 4.9     | 235       | 1.6%    |
| 5.6     | 228       | 1.56%   |
| 4.19    | 217       | 1.48%   |
| 5.14    | 180       | 1.23%   |
| 5.12    | 172       | 1.17%   |
| 5.7     | 153       | 1.04%   |
| 5.5     | 100       | 0.68%   |
| 5.17    | 85        | 0.58%   |
| 4.4     | 68        | 0.46%   |
| 5.1     | 44        | 0.3%    |
| 5.2     | 42        | 0.29%   |
| 4.1     | 40        | 0.27%   |
| 4.14    | 34        | 0.23%   |
| 4.12    | 34        | 0.23%   |
| 4.13    | 27        | 0.18%   |
| 3.10    | 26        | 0.18%   |
| 4.20    | 14        | 0.1%    |
| 4.17    | 11        | 0.08%   |
| 5       | 6         | 0.04%   |
| 4.8     | 5         | 0.03%   |
| 4.10    | 5         | 0.03%   |
| 4.11    | 4         | 0.03%   |
| 4.16    | 3         | 0.02%   |
| 4.6     | 2         | 0.01%   |
| 4.3     | 2         | 0.01%   |
| 4.2     | 2         | 0.01%   |
| Unknown | 2         | 0.01%   |
| 5.4.104 | 1         | 0.01%   |
| 5.18    | 1         | 0.01%   |
| 4.7     | 1         | 0.01%   |
| 3.4     | 1         | 0.01%   |
| 3.19    | 1         | 0.01%   |
| 3.16    | 1         | 0.01%   |
| 3.12    | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| x86_64   | 12633     | 95.41%  |
| i686     | 447       | 3.38%   |
| aarch64  | 125       | 0.94%   |
| armv7l   | 23        | 0.17%   |
| ppc      | 5         | 0.04%   |
| armv6l   | 5         | 0.04%   |
| armv8l   | 2         | 0.02%   |
| armv5tel | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| GNOME                        | 5469      | 39.51%  |
| KDE5                         | 2017      | 14.57%  |
| Unknown                      | 2015      | 14.56%  |
| X-Cinnamon                   | 1343      | 9.7%    |
| XFCE                         | 1026      | 7.41%   |
| KDE                          | 467       | 3.37%   |
| MATE                         | 418       | 3.02%   |
| Cinnamon                     | 211       | 1.52%   |
| KDE4                         | 195       | 1.41%   |
| Unity                        | 110       | 0.79%   |
| Pantheon                     | 101       | 0.73%   |
| Budgie                       | 85        | 0.61%   |
| LXQt                         | 72        | 0.52%   |
| i3                           | 71        | 0.51%   |
| LXDE                         | 63        | 0.46%   |
| Deepin                       | 34        | 0.25%   |
| GNOME Flashback              | 29        | 0.21%   |
| GNOME Classic                | 20        | 0.14%   |
| awesome                      | 17        | 0.12%   |
| openbox                      | 11        | 0.08%   |
| lightdm-xsession             | 10        | 0.07%   |
| sway                         | 9         | 0.07%   |
| dwm                          | 8         | 0.06%   |
| qtile                        | 6         | 0.04%   |
| Herbstluftwm                 | 6         | 0.04%   |
| trinity                      | 5         | 0.04%   |
| bspwm                        | 5         | 0.04%   |
| xmonad                       | 4         | 0.03%   |
| Yaru:ubuntu:GNOME            | 2         | 0.01%   |
| leftwm                       | 2         | 0.01%   |
| default                      | 2         | 0.01%   |
| xubuntu                      | 1         | 0.01%   |
| ubuntustudio                 | 1         | 0.01%   |
| pearl:GNOME                  | 1         | 0.01%   |
| nxde                         | 1         | 0.01%   |
| icewm                        | 1         | 0.01%   |
| i3-with-shmlog               | 1         | 0.01%   |
| GNOME:Phosh                  | 1         | 0.01%   |
| GNOME-Subgraph-Classic:GNOME | 1         | 0.01%   |
| enlightenment                | 1         | 0.01%   |
| /usr/local/bin/i3            | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 11084     | 81.75%  |
| Wayland     | 1201      | 8.86%   |
| Unknown     | 1042      | 7.68%   |
| Tty         | 227       | 1.67%   |
| Unspecified | 3         | 0.02%   |
| Web         | 2         | 0.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 7773      | 56.61%  |
| SDDM    | 1883      | 13.71%  |
| GDM     | 1190      | 8.67%   |
| LightDM | 1104      | 8.04%   |
| GDM3    | 896       | 6.52%   |
| TDM     | 630       | 4.59%   |
| KDM     | 197       | 1.43%   |
| XDM     | 24        | 0.17%   |
| SLiM    | 18        | 0.13%   |
| NODM    | 9         | 0.07%   |
| MDM     | 5         | 0.04%   |
| Ly      | 1         | 0.01%   |
| LXDM    | 1         | 0.01%   |
| GREETD  | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang                 | Computers | Percent |
|----------------------|-----------|---------|
| de_DE                | 8573      | 63.26%  |
| en_US                | 2105      | 15.53%  |
| Unknown              | 2055      | 15.16%  |
| en_GB                | 227       | 1.68%   |
| C                    | 197       | 1.45%   |
| ru_RU                | 55        | 0.41%   |
| pl_PL                | 36        | 0.27%   |
| en_DE                | 32        | 0.24%   |
| POSIX                | 23        | 0.17%   |
| fr_FR                | 22        | 0.16%   |
| de_AT                | 20        | 0.15%   |
| it_IT                | 19        | 0.14%   |
| es_ES                | 19        | 0.14%   |
| de_CH                | 14        | 0.1%    |
| en_IE                | 12        | 0.09%   |
| en_CA                | 11        | 0.08%   |
| hu_HU                | 10        | 0.07%   |
| ro_RO                | 9         | 0.07%   |
| nl_NL                | 8         | 0.06%   |
| C.UTF8               | 8         | 0.06%   |
| de_BE                | 7         | 0.05%   |
| pt_BR                | 5         | 0.04%   |
| en_IN                | 5         | 0.04%   |
| en_DK                | 5         | 0.04%   |
| en_AU                | 5         | 0.04%   |
| bg_BG                | 5         | 0.04%   |
| tr_TR                | 4         | 0.03%   |
| el_GR                | 4         | 0.03%   |
| sk_SK                | 3         | 0.02%   |
| ru_UA                | 3         | 0.02%   |
| pt_PT                | 3         | 0.02%   |
| nds_DE               | 3         | 0.02%   |
| hr_HR                | 3         | 0.02%   |
| de_IT                | 3         | 0.02%   |
| de_DE.UTF8           | 3         | 0.02%   |
| ar_EG                | 3         | 0.02%   |
| ja_JP                | 2         | 0.01%   |
| en_IL                | 2         | 0.01%   |
| de_LI                | 2         | 0.01%   |
| de_DE.utf-8          | 2         | 0.01%   |
| da_DK                | 2         | 0.01%   |
| cs_CZ                | 2         | 0.01%   |
| bs_BA                | 2         | 0.01%   |
| aa_DJ                | 2         | 0.01%   |
| zh_TW                | 1         | 0.01%   |
| sv_SE                | 1         | 0.01%   |
| sl_SI                | 1         | 0.01%   |
| fr_CA                | 1         | 0.01%   |
| es_CU                | 1         | 0.01%   |
| eo                   | 1         | 0.01%   |
| en_US.UTF8           | 1         | 0.01%   |
| en_US-UTF-8          | 1         | 0.01%   |
| en_NZ                | 1         | 0.01%   |
| en_CM                | 1         | 0.01%   |
| en_AT                | 1         | 0.01%   |
| en_150               | 1         | 0.01%   |
| en-US                | 1         | 0.01%   |
| de_DE@utf8           | 1         | 0.01%   |
| de_DE.iso885915@euro | 1         | 0.01%   |
| be_BY                | 1         | 0.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 7558      | 56.07%  |
| EFI  | 5922      | 43.93%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 10595     | 78.62%  |
| Overlay  | 1141      | 8.47%   |
| Btrfs    | 741       | 5.5%    |
| Unknown  | 604       | 4.48%   |
| Xfs      | 163       | 1.21%   |
| Zfs      | 69        | 0.51%   |
| Ext2     | 65        | 0.48%   |
| Ext3     | 47        | 0.35%   |
| F2fs     | 22        | 0.16%   |
| Tmpfs    | 11        | 0.08%   |
| Reiserfs | 6         | 0.04%   |
| Aufs     | 4         | 0.03%   |
| Rootfs   | 3         | 0.02%   |
| Jfs      | 2         | 0.01%   |
| XXXXX    | 1         | 0.01%   |
| XXXX     | 1         | 0.01%   |
| OveXlay  | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 8404      | 62.54%  |
| GPT     | 3552      | 26.43%  |
| MBR     | 1482      | 11.03%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 11375     | 84.3%   |
| Yes       | 2118      | 15.7%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 9418      | 69.9%   |
| Yes       | 4055      | 30.1%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 2054      | 15.52%  |
| ASUSTek Computer        | 1949      | 14.73%  |
| Hewlett-Packard         | 1469      | 11.1%   |
| Dell                    | 1124      | 8.49%   |
| Acer                    | 933       | 7.05%   |
| MSI                     | 918       | 6.94%   |
| Gigabyte Technology     | 909       | 6.87%   |
| ASRock                  | 684       | 5.17%   |
| Fujitsu                 | 401       | 3.03%   |
| Medion                  | 385       | 2.91%   |
| Apple                   | 229       | 1.73%   |
| Toshiba                 | 205       | 1.55%   |
| Samsung Electronics     | 166       | 1.25%   |
| Intel                   | 160       | 1.21%   |
| Fujitsu Siemens         | 137       | 1.04%   |
| Sony                    | 131       | 0.99%   |
| TUXEDO                  | 117       | 0.88%   |
| Unknown                 | 114       | 0.86%   |
| Packard Bell            | 86        | 0.65%   |
| Raspberry Pi Foundation | 84        | 0.63%   |
| Notebook                | 67        | 0.51%   |
| HUAWEI                  | 58        | 0.44%   |
| Biostar                 | 53        | 0.4%    |
| Schenker                | 44        | 0.33%   |
| Foxconn                 | 43        | 0.32%   |
| Supermicro              | 41        | 0.31%   |
| Wortmann AG             | 40        | 0.3%    |
| Microsoft               | 37        | 0.28%   |
| Pegatron                | 31        | 0.23%   |
| TrekStor                | 30        | 0.23%   |
| AMI                     | 28        | 0.21%   |
| ZOTAC                   | 27        | 0.2%    |
| Shuttle                 | 26        | 0.2%    |
| IBM                     | 23        | 0.17%   |
| BESSTAR Tech            | 21        | 0.16%   |
| eMachines               | 18        | 0.14%   |
| Chuwi                   | 14        | 0.11%   |
| Alienware               | 14        | 0.11%   |
| Panasonic               | 13        | 0.1%    |
| ECS                     | 13        | 0.1%    |
| Clevo                   | 13        | 0.1%    |
| AZW                     | 12        | 0.09%   |
| AXDIA International     | 12        | 0.09%   |
| LG Electronics          | 10        | 0.08%   |
| Google                  | 10        | 0.08%   |
| Timi                    | 9         | 0.07%   |
| ASRockRack              | 9         | 0.07%   |
| Teclast                 | 8         | 0.06%   |
| Pine Microsystems       | 8         | 0.06%   |
| AWOW                    | 8         | 0.06%   |
| Razer                   | 7         | 0.05%   |
| Nvidia                  | 7         | 0.05%   |
| Hardkernel              | 7         | 0.05%   |
| AOpen                   | 7         | 0.05%   |
| ABIT                    | 7         | 0.05%   |
| LincPlus                | 6         | 0.05%   |
| Framework               | 6         | 0.05%   |
| EVGA                    | 5         | 0.04%   |
| CSL-Computer            | 5         | 0.04%   |
| Valve                   | 4         | 0.03%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                          | Computers | Percent |
|-------------------------------|-----------|---------|
| Unknown                       | 176       | 1.33%   |
| ASUS All Series               | 105       | 0.79%   |
| RPi Raspberry Pi              | 49        | 0.37%   |
| MSI MS-7C37                   | 45        | 0.34%   |
| MSI MS-7B86                   | 43        | 0.32%   |
| HP Notebook                   | 41        | 0.31%   |
| MSI MS-7A38                   | 33        | 0.25%   |
| ASUS PRIME B350-PLUS          | 31        | 0.23%   |
| ASUS PRIME A320M-K            | 29        | 0.22%   |
| MSI MS-7B89                   | 28        | 0.21%   |
| ASUS P50IJ                    | 27        | 0.2%    |
| MSI MS-7C02                   | 26        | 0.2%    |
| ASUS M5A78L-M/USB3            | 26        | 0.2%    |
| Gigabyte X570 AORUS ELITE     | 24        | 0.18%   |
| Gigabyte 970A-DS3P            | 24        | 0.18%   |
| Lenovo IdeaPad 5 15ARE05 81YQ | 23        | 0.17%   |
| ASRock B450M Pro4             | 23        | 0.17%   |
| MSI MS-7B79                   | 22        | 0.17%   |
| Dell OptiPlex 790             | 22        | 0.17%   |
| ASUS A68HM-PLUS               | 22        | 0.17%   |
| MSI MS-7693                   | 21        | 0.16%   |
| Dell OptiPlex 7010            | 21        | 0.16%   |
| Dell Latitude E6420           | 21        | 0.16%   |
| Gigabyte GA-78LMT-USB3 6.0    | 20        | 0.15%   |
| ASUS PRIME X370-PRO           | 20        | 0.15%   |
| ASUS PRIME B450M-A            | 20        | 0.15%   |
| Dell Latitude E6410           | 19        | 0.14%   |
| ASRock 970 Pro3 R2.0          | 19        | 0.14%   |
| HP 255 G7 Notebook PC         | 18        | 0.14%   |
| Gigabyte GA-78LMT-S2P         | 18        | 0.14%   |
| ASUS TUF GAMING X570-PLUS     | 18        | 0.14%   |
| MSI MS-7816                   | 17        | 0.13%   |
| HP Laptop 17-ca1xxx           | 17        | 0.13%   |
| HP Laptop 17-ca0xxx           | 17        | 0.13%   |
| Dell XPS 15 9570              | 17        | 0.13%   |
| Dell XPS 13 9370              | 17        | 0.13%   |
| ASUS PRIME X470-PRO           | 17        | 0.13%   |
| ASUS A0000001                 | 17        | 0.13%   |
| Acer Swift SF114-34           | 17        | 0.13%   |
| MSI MS-7C91                   | 16        | 0.12%   |
| MSI MS-7A34                   | 16        | 0.12%   |
| MSI MS-7A32                   | 16        | 0.12%   |
| HP EliteBook 8470p            | 16        | 0.12%   |
| Dell Latitude E6430           | 16        | 0.12%   |
| ASUS M5A97 R2.0               | 16        | 0.12%   |
| HP Pavilion dv7               | 15        | 0.11%   |
| HP EliteBook 8460p            | 15        | 0.11%   |
| HP 250 G7 Notebook PC         | 15        | 0.11%   |
| Gigabyte B450M DS3H           | 15        | 0.11%   |
| MSI MS-7C56                   | 14        | 0.11%   |
| MSI MS-7C35                   | 14        | 0.11%   |
| Medion MS-7728                | 14        | 0.11%   |
| HP Laptop 15-db1xxx           | 14        | 0.11%   |
| Fujitsu ESPRIMO P720          | 14        | 0.11%   |
| ASRock N68C-S UCC             | 14        | 0.11%   |
| ASRock B450 Pro4              | 14        | 0.11%   |
| Acer Aspire 7750G             | 14        | 0.11%   |
| MSI MS-7A33                   | 13        | 0.1%    |
| HP Pavilion dv6               | 13        | 0.1%    |
| HP EliteBook 8440p            | 13        | 0.1%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 1190      | 8.99%   |
| Acer Aspire             | 626       | 4.73%   |
| Dell Latitude           | 386       | 2.92%   |
| Lenovo IdeaPad          | 285       | 2.15%   |
| ASUS PRIME              | 234       | 1.77%   |
| HP EliteBook            | 225       | 1.7%    |
| HP Pavilion             | 191       | 1.44%   |
| Unknown                 | 176       | 1.33%   |
| HP Compaq               | 172       | 1.3%    |
| Dell OptiPlex           | 172       | 1.3%    |
| HP Laptop               | 168       | 1.27%   |
| Toshiba Satellite       | 162       | 1.22%   |
| Fujitsu LIFEBOOK        | 161       | 1.22%   |
| Dell Inspiron           | 159       | 1.2%    |
| Dell XPS                | 157       | 1.19%   |
| Fujitsu ESPRIMO         | 156       | 1.18%   |
| HP ProBook              | 146       | 1.1%    |
| ASUS ROG                | 141       | 1.07%   |
| Dell Precision          | 129       | 0.97%   |
| Lenovo ThinkCentre      | 108       | 0.82%   |
| ASUS All                | 105       | 0.79%   |
| ASUS TUF                | 83        | 0.63%   |
| RPi Raspberry           | 82        | 0.62%   |
| Lenovo Yoga             | 74        | 0.56%   |
| Acer Swift              | 71        | 0.54%   |
| HP ENVY                 | 68        | 0.51%   |
| ASUS M5A78L-M           | 64        | 0.48%   |
| Acer TravelMate         | 64        | 0.48%   |
| Medion Akoya            | 58        | 0.44%   |
| Dell Vostro             | 54        | 0.41%   |
| Packard Bell EasyNote   | 52        | 0.39%   |
| Gigabyte X570           | 51        | 0.39%   |
| ASUS VivoBook           | 51        | 0.39%   |
| MSI MS-7C37             | 45        | 0.34%   |
| Fujitsu Siemens ESPRIMO | 45        | 0.34%   |
| MSI MS-7B86             | 43        | 0.32%   |
| ASUS ZenBook            | 43        | 0.32%   |
| HP Notebook             | 41        | 0.31%   |
| ASRock 970              | 41        | 0.31%   |
| HP 255                  | 40        | 0.3%    |
| Gigabyte GA-78LMT-USB3  | 40        | 0.3%    |
| ASUS M5A97              | 40        | 0.3%    |
| Lenovo IdeaCentre       | 38        | 0.29%   |
| Microsoft Surface       | 37        | 0.28%   |
| Gigabyte B450           | 37        | 0.28%   |
| HP 250                  | 36        | 0.27%   |
| Fujitsu Siemens AMILO   | 35        | 0.26%   |
| Fujitsu CELSIUS         | 34        | 0.26%   |
| MSI MS-7A38             | 33        | 0.25%   |
| HP EliteDesk            | 33        | 0.25%   |
| Acer Extensa            | 32        | 0.24%   |
| Gigabyte B450M          | 30        | 0.23%   |
| HP ZBook                | 29        | 0.22%   |
| ASRock B450             | 29        | 0.22%   |
| MSI MS-7B89             | 28        | 0.21%   |
| HP Spectre              | 28        | 0.21%   |
| ASUS P50IJ              | 27        | 0.2%    |
| MSI MS-7C02             | 26        | 0.2%    |
| Lenovo MIIX             | 26        | 0.2%    |
| Gigabyte 970A-DS3P      | 26        | 0.2%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 1268      | 9.58%   |
| 2019    | 1237      | 9.35%   |
| 2012    | 1205      | 9.11%   |
| 2011    | 1088      | 8.22%   |
| 2020    | 1066      | 8.06%   |
| 2013    | 922       | 6.97%   |
| 2017    | 898       | 6.79%   |
| 2010    | 842       | 6.36%   |
| 2014    | 826       | 6.24%   |
| 2015    | 653       | 4.93%   |
| 2009    | 652       | 4.93%   |
| 2016    | 645       | 4.87%   |
| 2008    | 616       | 4.65%   |
| 2021    | 482       | 3.64%   |
| 2007    | 365       | 2.76%   |
| 2006    | 168       | 1.27%   |
| Unknown | 162       | 1.22%   |
| 2005    | 71        | 0.54%   |
| 2004    | 25        | 0.19%   |
| 2022    | 21        | 0.16%   |
| 2003    | 11        | 0.08%   |
| 2000    | 5         | 0.04%   |
| 2002    | 4         | 0.03%   |
| 2001    | 1         | 0.01%   |
| 1999    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 6756      | 51.05%  |
| Desktop        | 5476      | 41.38%  |
| Convertible    | 333       | 2.52%   |
| Mini pc        | 192       | 1.45%   |
| System on chip | 135       | 1.02%   |
| Tablet         | 132       | 1%      |
| All in one     | 124       | 0.94%   |
| Server         | 76        | 0.57%   |
| Phone          | 9         | 0.07%   |
| Stick pc       | 1         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 12383     | 93.12%  |
| Enabled  | 915       | 6.88%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 13209     | 99.81%  |
| Yes  | 25        | 0.19%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 2935      | 21.84%  |
| 3.01-4.0        | 2831      | 21.07%  |
| 16.01-24.0      | 2642      | 19.66%  |
| 8.01-16.0       | 2467      | 18.36%  |
| 32.01-64.0      | 1171      | 8.71%   |
| 1.01-2.0        | 525       | 3.91%   |
| 64.01-256.0     | 316       | 2.35%   |
| 2.01-3.0        | 205       | 1.53%   |
| 24.01-32.0      | 202       | 1.5%    |
| 0.51-1.0        | 110       | 0.82%   |
| 0.01-0.5        | 16        | 0.12%   |
| More than 256.0 | 13        | 0.1%    |
| Unknown         | 4         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 6325      | 42.92%  |
| 2.01-3.0    | 3368      | 22.86%  |
| 4.01-8.0    | 1623      | 11.01%  |
| 3.01-4.0    | 1407      | 9.55%   |
| 0.51-1.0    | 1236      | 8.39%   |
| 8.01-16.0   | 429       | 2.91%   |
| 0.01-0.5    | 227       | 1.54%   |
| 16.01-24.0  | 63        | 0.43%   |
| 24.01-32.0  | 27        | 0.18%   |
| 32.01-64.0  | 17        | 0.12%   |
| Unknown     | 8         | 0.05%   |
| 64.01-256.0 | 5         | 0.03%   |
| 0           | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 7765      | 56.79%  |
| 2       | 3436      | 25.13%  |
| 3       | 1194      | 8.73%   |
| 4       | 593       | 4.34%   |
| 5       | 276       | 2.02%   |
| 0       | 161       | 1.18%   |
| 6       | 120       | 0.88%   |
| 7       | 56        | 0.41%   |
| 8       | 26        | 0.19%   |
| Unknown | 11        | 0.08%   |
| 9       | 10        | 0.07%   |
| 10      | 9         | 0.07%   |
| 11      | 4         | 0.03%   |
| 13      | 3         | 0.02%   |
| 17      | 2         | 0.01%   |
| 14      | 2         | 0.01%   |
| 12      | 2         | 0.01%   |
| 22      | 1         | 0.01%   |
| 20      | 1         | 0.01%   |
| 16      | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 6880      | 51.53%  |
| No        | 6472      | 48.47%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 11858     | 89.42%  |
| No        | 1403      | 10.58%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 9217      | 69.16%  |
| No        | 4110      | 30.84%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 6895      | 51.32%  |
| No        | 6540      | 48.68%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Germany | 13234     | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Berlin                 | 1203      | 8.33%   |
| Munich                 | 610       | 4.22%   |
| Hamburg                | 562       | 3.89%   |
| Frankfurt am Main      | 472       | 3.27%   |
| Stuttgart              | 319       | 2.21%   |
| Cologne                | 288       | 1.99%   |
| Leipzig                | 223       | 1.54%   |
| Nuremberg              | 183       | 1.27%   |
| Essen                  | 181       | 1.25%   |
| DГјsseldorf          | 158       | 1.09%   |
| Dresden                | 156       | 1.08%   |
| Karlsruhe              | 149       | 1.03%   |
| Dortmund               | 127       | 0.88%   |
| Mannheim               | 96        | 0.66%   |
| Mainz                  | 92        | 0.64%   |
| Bremen                 | 91        | 0.63%   |
| Bielefeld              | 91        | 0.63%   |
| Bonn                   | 90        | 0.62%   |
| Chemnitz               | 88        | 0.61%   |
| Braunschweig           | 87        | 0.6%    |
| Wuppertal              | 79        | 0.55%   |
| Hanover                | 71        | 0.49%   |
| Wiesbaden              | 69        | 0.48%   |
| Oldenburg              | 66        | 0.46%   |
| Darmstadt              | 66        | 0.46%   |
| Augsburg               | 65        | 0.45%   |
| Halle                  | 64        | 0.44%   |
| Ulm                    | 57        | 0.39%   |
| Bamberg                | 56        | 0.39%   |
| Freiburg im Breisgau   | 55        | 0.38%   |
| Regensburg             | 52        | 0.36%   |
| Heilbronn              | 52        | 0.36%   |
| Falkenstein            | 52        | 0.36%   |
| Bochum                 | 52        | 0.36%   |
| Ludwigshafen am Rhein  | 51        | 0.35%   |
| Kiel                   | 51        | 0.35%   |
| Duisburg               | 51        | 0.35%   |
| DÃ¼sseldorf          | 51        | 0.35%   |
| Erfurt                 | 49        | 0.34%   |
| Kassel                 | 47        | 0.33%   |
| Aachen                 | 47        | 0.33%   |
| Giessen                | 46        | 0.32%   |
| Offenbach              | 45        | 0.31%   |
| Oberhausen             | 43        | 0.3%    |
| Langenhagen            | 43        | 0.3%    |
| Rostock                | 42        | 0.29%   |
| Krefeld                | 42        | 0.29%   |
| Reutlingen             | 41        | 0.28%   |
| Ludwigsburg            | 41        | 0.28%   |
| Kaiserslautern         | 38        | 0.26%   |
| Gelsenkirchen          | 38        | 0.26%   |
| Salzgitter             | 35        | 0.24%   |
| Koblenz                | 35        | 0.24%   |
| Solingen               | 34        | 0.24%   |
| Magdeburg              | 34        | 0.24%   |
| Heidelberg             | 33        | 0.23%   |
| MГ¶nchengladbach     | 32        | 0.22%   |
| Recklinghausen         | 31        | 0.21%   |
| Villingen-Schwenningen | 30        | 0.21%   |
| Potsdam                | 30        | 0.21%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 4113      | 6474   | 21.08%  |
| WDC                       | 2823      | 4582   | 14.47%  |
| Seagate                   | 2617      | 4040   | 13.41%  |
| SanDisk                   | 1472      | 2105   | 7.54%   |
| Toshiba                   | 1319      | 1833   | 6.76%   |
| Crucial                   | 923       | 1321   | 4.73%   |
| Unknown                   | 889       | 1272   | 4.56%   |
| Hitachi                   | 648       | 849    | 3.32%   |
| Kingston                  | 610       | 796    | 3.13%   |
| Intenso                   | 508       | 702    | 2.6%    |
| Intel                     | 406       | 568    | 2.08%   |
| SK Hynix                  | 396       | 507    | 2.03%   |
| HGST                      | 288       | 412    | 1.48%   |
| Micron Technology         | 245       | 317    | 1.26%   |
| Phison                    | 163       | 230    | 0.84%   |
| A-DATA Technology         | 155       | 200    | 0.79%   |
| OCZ                       | 124       | 155    | 0.64%   |
| Transcend                 | 113       | 139    | 0.58%   |
| Fujitsu                   | 105       | 137    | 0.54%   |
| Apple                     | 81        | 104    | 0.42%   |
| KIOXIA                    | 73        | 86     | 0.37%   |
| LITEON                    | 70        | 75     | 0.36%   |
| Patriot                   | 64        | 91     | 0.33%   |
| MAXTOR                    | 62        | 103    | 0.32%   |
| Corsair                   | 62        | 79     | 0.32%   |
| China                     | 60        | 70     | 0.31%   |
| Micron/Crucial Technology | 50        | 70     | 0.26%   |
| JMicron                   | 50        | 55     | 0.26%   |
| SPCC                      | 49        | 65     | 0.25%   |
| LITEONIT                  | 44        | 52     | 0.23%   |
| Silicon Motion            | 42        | 59     | 0.22%   |
| ASMT                      | 39        | 56     | 0.2%    |
| Leven                     | 37        | 47     | 0.19%   |
| INNOVATION IT             | 31        | 36     | 0.16%   |
| Unknown                   | 31        | 37     | 0.16%   |
| Hewlett-Packard           | 30        | 39     | 0.15%   |
| SABRENT                   | 29        | 32     | 0.15%   |
| PNY                       | 27        | 41     | 0.14%   |
| WD MediaMax               | 24        | 31     | 0.12%   |
| XPG                       | 23        | 27     | 0.12%   |
| Apacer                    | 22        | 25     | 0.11%   |
| Lenovo                    | 19        | 23     | 0.1%    |
| KingDian                  | 19        | 21     | 0.1%    |
| Asmedia                   | 19        | 23     | 0.1%    |
| Mushkin                   | 18        | 27     | 0.09%   |
| Netac                     | 17        | 21     | 0.09%   |
| PLEXTOR                   | 16        | 16     | 0.08%   |
| Verbatim                  | 15        | 20     | 0.08%   |
| TCSUNBOW                  | 15        | 33     | 0.08%   |
| ExcelStor                 | 14        | 15     | 0.07%   |
| KingSpec                  | 13        | 21     | 0.07%   |
| EMTEC                     | 13        | 14     | 0.07%   |
| TrekStor                  | 12        | 12     | 0.06%   |
| Gigabyte Technology       | 12        | 19     | 0.06%   |
| DOGFISH                   | 12        | 27     | 0.06%   |
| IBM/Hitachi               | 11        | 11     | 0.06%   |
| Team                      | 10        | 14     | 0.05%   |
| KIOXIA-EXCERIA            | 9         | 9      | 0.05%   |
| DREVO                     | 9         | 14     | 0.05%   |
| USB3.0                    | 8         | 9      | 0.04%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB          | 286       | 1.31%   |
| Samsung SSD 860 EVO 500GB          | 247       | 1.14%   |
| Samsung SSD 850 EVO 500GB          | 214       | 0.98%   |
| Samsung NVMe SSD Drive 500GB       | 171       | 0.79%   |
| Unknown MMC Card  32GB             | 159       | 0.73%   |
| Unknown MMC Card  64GB             | 158       | 0.73%   |
| Samsung NVMe SSD Drive 512GB       | 150       | 0.69%   |
| Samsung SSD 860 EVO 1TB            | 147       | 0.68%   |
| Crucial CT500MX500SSD1 500GB       | 144       | 0.66%   |
| Crucial CT1000MX500SSD1 1TB        | 137       | 0.63%   |
| Samsung NVMe SSD Drive 1TB         | 130       | 0.6%    |
| Samsung SSD 860 EVO 250GB          | 125       | 0.57%   |
| Toshiba MQ01ABD100 1TB             | 117       | 0.54%   |
| SanDisk SSD PLUS 240GB             | 116       | 0.53%   |
| Seagate ST500DM002-1BD142 500GB    | 114       | 0.52%   |
| Toshiba DT01ACA100 1TB             | 108       | 0.5%    |
| Seagate ST1000LM024 HN-M101MBB 1TB | 108       | 0.5%    |
| Samsung SSD 840 EVO 250GB          | 107       | 0.49%   |
| Sandisk NVMe SSD Drive 512GB       | 102       | 0.47%   |
| Samsung NVMe SSD Drive 256GB       | 101       | 0.46%   |
| SanDisk SSD PLUS 1000GB            | 97        | 0.45%   |
| Crucial CT240BX500SSD1 240GB       | 93        | 0.43%   |
| Seagate ST9500325AS 500GB          | 90        | 0.41%   |
| Seagate ST1000LM035-1RK172 1TB     | 81        | 0.37%   |
| Unknown SD/MMC/MS PRO 128GB        | 80        | 0.37%   |
| Samsung SSD 970 EVO Plus 1TB       | 80        | 0.37%   |
| Toshiba HDWD110 1TB                | 76        | 0.35%   |
| Kingston SA400S37240G 240GB SSD    | 76        | 0.35%   |
| Samsung SSD 840 EVO 120GB          | 75        | 0.34%   |
| Seagate ST1000DM010-2EP102 1TB     | 74        | 0.34%   |
| Samsung SSD 860 QVO 1TB            | 74        | 0.34%   |
| Unknown MMC Card  128GB            | 73        | 0.34%   |
| SanDisk SSD PLUS 480GB             | 71        | 0.33%   |
| Samsung SSD 840 EVO 500GB          | 71        | 0.33%   |
| Intenso SSD SATAIII 512GB          | 69        | 0.32%   |
| Samsung NVMe SSD Drive 1024GB      | 68        | 0.31%   |
| Samsung SSD 850 PRO 256GB          | 66        | 0.3%    |
| WDC WD10EZEX-08WN4A0 1TB           | 65        | 0.3%    |
| Seagate ST2000DM008-2FR102 2TB     | 65        | 0.3%    |
| Intel NVMe SSD Drive 512GB         | 65        | 0.3%    |
| SK Hynix NVMe SSD Drive 512GB      | 64        | 0.29%   |
| Seagate ST1000DM003-1CH162 1TB     | 64        | 0.29%   |
| Toshiba MQ01ABF050 500GB           | 63        | 0.29%   |
| Samsung SSD 970 EVO Plus 500GB     | 63        | 0.29%   |
| SanDisk SSD PLUS 120GB             | 62        | 0.28%   |
| WDC WD20EZRZ-00Z5HB0 2TB           | 61        | 0.28%   |
| WDC WD10JPVX-22JC3T0 1TB           | 61        | 0.28%   |
| SanDisk SDSSDA240G 240GB           | 61        | 0.28%   |
| Toshiba DT01ACA200 2TB             | 60        | 0.28%   |
| Seagate Expansion+ 2TB             | 60        | 0.28%   |
| Kingston SV300S37A120G 120GB SSD   | 60        | 0.28%   |
| Kingston SA400S37120G 120GB SSD    | 59        | 0.27%   |
| Samsung NVMe SSD Drive 250GB       | 57        | 0.26%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 55        | 0.25%   |
| Seagate ST500LT012-1DG142 500GB    | 55        | 0.25%   |
| SanDisk SDSSDA120G 120GB           | 55        | 0.25%   |
| SanDisk SDSSDP128G 128GB           | 52        | 0.24%   |
| Samsung SSD 840 PRO Series 256GB   | 52        | 0.24%   |
| Samsung HD103SJ 1TB                | 52        | 0.24%   |
| Samsung SSD 840 Series 120GB       | 51        | 0.23%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2565      | 3961   | 32.33%  |
| WDC                 | 2368      | 3893   | 29.85%  |
| Toshiba             | 950       | 1333   | 11.98%  |
| Hitachi             | 648       | 849    | 8.17%   |
| Samsung Electronics | 618       | 906    | 7.79%   |
| HGST                | 288       | 412    | 3.63%   |
| Fujitsu             | 105       | 137    | 1.32%   |
| Unknown             | 86        | 137    | 1.08%   |
| MAXTOR              | 60        | 96     | 0.76%   |
| Intenso             | 58        | 92     | 0.73%   |
| ASMT                | 34        | 48     | 0.43%   |
| SABRENT             | 23        | 26     | 0.29%   |
| Apple               | 23        | 25     | 0.29%   |
| Asmedia             | 14        | 17     | 0.18%   |
| WD MediaMax         | 13        | 17     | 0.16%   |
| IBM/Hitachi         | 11        | 11     | 0.14%   |
| ExcelStor           | 10        | 11     | 0.13%   |
| USB3.0              | 6         | 6      | 0.08%   |
| Dell                | 5         | 9      | 0.06%   |
| USB                 | 4         | 4      | 0.05%   |
| Inateck             | 4         | 4      | 0.05%   |
| IBM                 | 4         | 5      | 0.05%   |
| HGST HTS            | 4         | 4      | 0.05%   |
| LIO-ORG             | 3         | 9      | 0.04%   |
| SILICONMOTION       | 2         | 5      | 0.03%   |
| MDT                 | 2         | 2      | 0.03%   |
| MARVELL             | 2         | 2      | 0.03%   |
| KESU                | 2         | 2      | 0.03%   |
| IET                 | 2         | 2      | 0.03%   |
| HPE                 | 2         | 6      | 0.03%   |
| Hewlett-Packard     | 2         | 2      | 0.03%   |
| China               | 2         | 2      | 0.03%   |
| TPH00800640GB       | 1         | 1      | 0.01%   |
| SYNOLOGY            | 1         | 1      | 0.01%   |
| QUANTUM             | 1         | 1      | 0.01%   |
| PHD 3.0             | 1         | 2      | 0.01%   |
| Maxone              | 1         | 1      | 0.01%   |
| LaCie               | 1         | 1      | 0.01%   |
| JMicron             | 1         | 1      | 0.01%   |
| IB                  | 1         | 2      | 0.01%   |
| Fantom              | 1         | 1      | 0.01%   |
| DeLOCK              | 1         | 1      | 0.01%   |
| Config              | 1         | 1      | 0.01%   |
| ASMT109x            | 1         | 1      | 0.01%   |
| 3ware               | 1         | 2      | 0.01%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2451      | 3569   | 32.83%  |
| SanDisk             | 1192      | 1734   | 15.97%  |
| Crucial             | 869       | 1243   | 11.64%  |
| Kingston            | 442       | 577    | 5.92%   |
| Intenso             | 383       | 506    | 5.13%   |
| WDC                 | 283       | 373    | 3.79%   |
| Intel               | 167       | 229    | 2.24%   |
| Toshiba             | 164       | 204    | 2.2%    |
| Micron Technology   | 146       | 180    | 1.96%   |
| A-DATA Technology   | 129       | 168    | 1.73%   |
| OCZ                 | 120       | 148    | 1.61%   |
| SK Hynix            | 114       | 142    | 1.53%   |
| Transcend           | 103       | 121    | 1.38%   |
| LITEON              | 66        | 71     | 0.88%   |
| Patriot             | 61        | 87     | 0.82%   |
| China               | 56        | 66     | 0.75%   |
| LITEONIT            | 44        | 52     | 0.59%   |
| SPCC                | 43        | 56     | 0.58%   |
| Apple               | 40        | 47     | 0.54%   |
| Corsair             | 38        | 50     | 0.51%   |
| Leven               | 36        | 45     | 0.48%   |
| JMicron             | 33        | 36     | 0.44%   |
| INNOVATION IT       | 31        | 36     | 0.42%   |
| PNY                 | 23        | 37     | 0.31%   |
| Unknown             | 21        | 22     | 0.28%   |
| Hewlett-Packard     | 21        | 22     | 0.28%   |
| Apacer              | 20        | 23     | 0.27%   |
| KingDian            | 19        | 21     | 0.25%   |
| Seagate             | 18        | 22     | 0.24%   |
| Netac               | 16        | 20     | 0.21%   |
| Unknown             | 16        | 21     | 0.21%   |
| Verbatim            | 15        | 20     | 0.2%    |
| PHISON              | 15        | 23     | 0.2%    |
| Mushkin             | 14        | 23     | 0.19%   |
| PLEXTOR             | 13        | 13     | 0.17%   |
| EMTEC               | 13        | 14     | 0.17%   |
| KingSpec            | 12        | 20     | 0.16%   |
| Dogfish             | 12        | 27     | 0.16%   |
| TCSUNBOW            | 10        | 23     | 0.13%   |
| Team                | 9         | 13     | 0.12%   |
| DREVO               | 9         | 14     | 0.12%   |
| TrekStor            | 8         | 8      | 0.11%   |
| TO Exter            | 8         | 12     | 0.11%   |
| Lexar               | 8         | 10     | 0.11%   |
| GOODRAM             | 8         | 12     | 0.11%   |
| FORESEE             | 6         | 9      | 0.08%   |
| OCZ-VERTEX2         | 5         | 6      | 0.07%   |
| ViperTeq            | 4         | 5      | 0.05%   |
| OCZ-VERTEX3         | 4         | 5      | 0.05%   |
| KIOXIA-EXCERIA      | 4         | 4      | 0.05%   |
| Gigabyte Technology | 4         | 5      | 0.05%   |
| BHT                 | 4         | 6      | 0.05%   |
| Zheino              | 3         | 3      | 0.04%   |
| Vaseky              | 3         | 11     | 0.04%   |
| TSA                 | 3         | 3      | 0.04%   |
| Teclast             | 3         | 3      | 0.04%   |
| StoreJet            | 3         | 3      | 0.04%   |
| SMI                 | 3         | 3      | 0.04%   |
| NGFF                | 3         | 3      | 0.04%   |
| lntenso             | 3         | 3      | 0.04%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 6613      | 12051  | 37.82%  |
| SSD     | 6463      | 10342  | 36.96%  |
| NVMe    | 3343      | 4834   | 19.12%  |
| MMC     | 776       | 1036   | 4.44%   |
| Unknown | 291       | 449    | 1.66%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 10454     | 21596  | 68.09%  |
| NVMe | 3340      | 4826   | 21.75%  |
| SAS  | 783       | 1254   | 5.1%    |
| MMC  | 776       | 1036   | 5.05%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB  | Computers | Drives | Percent |
|-------------|-----------|--------|---------|
| 0.01-0.5    | 8090      | 13036  | 58.66%  |
| 0.51-1.0    | 3653      | 5710   | 26.49%  |
| 1.01-2.0    | 1138      | 1950   | 8.25%   |
| 3.01-4.0    | 411       | 766    | 2.98%   |
| 2.01-3.0    | 293       | 509    | 2.12%   |
| 4.01-10.0   | 173       | 356    | 1.25%   |
| 10.01-20.0  | 27        | 53     | 0.2%    |
| 20.01-50.0  | 4         | 8      | 0.03%   |
| 50.01-100.0 | 1         | 4      | 0.01%   |
| 0           | 1         | 1      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 3742      | 26.58%  |
| 251-500        | 3054      | 21.7%   |
| 501-1000       | 1998      | 14.19%  |
| 1001-2000      | 1062      | 7.54%   |
| 1-20           | 1014      | 7.2%    |
| 51-100         | 962       | 6.83%   |
| More than 3000 | 712       | 5.06%   |
| 21-50          | 576       | 4.09%   |
| Unknown        | 534       | 3.79%   |
| 2001-3000      | 422       | 3%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 5755      | 39.26%  |
| 21-50          | 2361      | 16.11%  |
| 101-250        | 1733      | 11.82%  |
| 51-100         | 1560      | 10.64%  |
| 251-500        | 1043      | 7.12%   |
| 501-1000       | 755       | 5.15%   |
| Unknown        | 534       | 3.64%   |
| 1001-2000      | 486       | 3.32%   |
| More than 3000 | 254       | 1.73%   |
| 2001-3000      | 175       | 1.19%   |
| 0              | 3         | 0.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                     | 13        | 15     | 1.42%   |
| Seagate ST9500325AS 500GB                           | 12        | 18     | 1.31%   |
| Samsung Electronics HD103UJ 1TB                     | 12        | 12     | 1.31%   |
| Crucial CT525MX300SSD1 528GB                        | 11        | 12     | 1.2%    |
| Toshiba MQ01ABD100 1TB                              | 9         | 11     | 0.98%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 9         | 11     | 0.98%   |
| Samsung Electronics HD501LJ 500GB                   | 9         | 12     | 0.98%   |
| WDC WD20EARS-00MVWB0 2TB                            | 7         | 9      | 0.77%   |
| Seagate ST9320325AS 320GB                           | 7         | 8      | 0.77%   |
| Seagate ST500LT012-9WS142 500GB                     | 7         | 8      | 0.77%   |
| Seagate ST500LT012-1DG142 500GB                     | 7         | 7      | 0.77%   |
| Seagate ST500LM000-1EJ162 500GB                     | 7         | 8      | 0.77%   |
| Seagate ST1000LM035-1RK172 1TB                      | 7         | 7      | 0.77%   |
| Samsung Electronics SP2504C 250GB                   | 7         | 7      | 0.77%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 6         | 6      | 0.66%   |
| Seagate ST9250315AS 250GB                           | 6         | 6      | 0.66%   |
| Seagate ST500LM000-SSHD-8GB                         | 6         | 6      | 0.66%   |
| Seagate ST31000528AS 1TB                            | 6         | 6      | 0.66%   |
| Samsung Electronics HD160JJ 160GB                   | 6         | 9      | 0.66%   |
| HGST HTS725050A7E630 500GB                          | 6         | 6      | 0.66%   |
| HGST HTS545050A7E680 500GB                          | 6         | 10     | 0.66%   |
| WDC WD20EARX-00PASB0 2TB                            | 5         | 5      | 0.55%   |
| Seagate ST1000DM003-9YN162 1TB                      | 5         | 5      | 0.55%   |
| Seagate ST1000DM003-1CH162 1TB                      | 5         | 8      | 0.55%   |
| Hitachi HTS545050A7E380 500GB                       | 5         | 5      | 0.55%   |
| HGST HTS545050A7E380 500GB                          | 5         | 7      | 0.55%   |
| WDC WD5000AADS-00S9B0 500GB                         | 4         | 5      | 0.44%   |
| WDC WD40EFRX-68N32N0 4TB                            | 4         | 8      | 0.44%   |
| WDC WD20EFRX-68EUZN0 2TB                            | 4         | 5      | 0.44%   |
| WDC WD10EARS-00Y5B1 1TB                             | 4         | 4      | 0.44%   |
| WDC WD10EADS-00L5B1 1TB                             | 4         | 4      | 0.44%   |
| Seagate ST9500420AS 500GB                           | 4         | 4      | 0.44%   |
| Seagate ST500LM021-1KJ152 500GB                     | 4         | 4      | 0.44%   |
| Seagate ST3500418AS 500GB                           | 4         | 5      | 0.44%   |
| SanDisk SDSSDA120G 120GB                            | 4         | 4      | 0.44%   |
| Samsung Electronics HD642JJ 640GB                   | 4         | 4      | 0.44%   |
| Samsung Electronics HD103SI 1TB                     | 4         | 4      | 0.44%   |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB SSD | 4         | 4      | 0.44%   |
| Kingston SV300S37A120G 120GB SSD                    | 4         | 5      | 0.44%   |
| Hitachi HTS547575A9E384 752GB                       | 4         | 4      | 0.44%   |
| Hitachi HTS541616J9SA00 160GB                       | 4         | 5      | 0.44%   |
| Hitachi HDS721010CLA332 1TB                         | 4         | 5      | 0.44%   |
| HGST HTS721010A9E630 1TB                            | 4         | 4      | 0.44%   |
| HGST HTS541010A9E680 1TB                            | 4         | 4      | 0.44%   |
| Fujitsu MHZ2320BH G2 320GB                          | 4         | 5      | 0.44%   |
| WDC WD5000BPVT-22HXZT1 500GB                        | 3         | 3      | 0.33%   |
| WDC WD30EFRX-68EUZN0 3TB                            | 3         | 4      | 0.33%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 3         | 8      | 0.33%   |
| WDC WD20EZRX-00DC0B0 2TB                            | 3         | 6      | 0.33%   |
| WDC WD2000FYYZ-01UL1B1 2TB                          | 3         | 6      | 0.33%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 3         | 5      | 0.33%   |
| WDC WD10EFRX-68JCSN0 1TB                            | 3         | 4      | 0.33%   |
| WDC WD10EARS-22Y5B1 1TB                             | 3         | 3      | 0.33%   |
| WDC WD10EADS-00M2B0 1TB                             | 3         | 3      | 0.33%   |
| WDC WD10EACS-22D6B0 1TB                             | 3         | 3      | 0.33%   |
| WDC WD1002FAEX-00Z3A0 1TB                           | 3         | 5      | 0.33%   |
| Toshiba MQ01ACF050 500GB                            | 3         | 3      | 0.33%   |
| Toshiba MQ01ABD075 752GB                            | 3         | 3      | 0.33%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD             | 3         | 3      | 0.33%   |
| SK Hynix HFS256G39TND-N210A 256GB SSD               | 3         | 3      | 0.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 237       | 285    | 26.42%  |
| WDC                 | 182       | 256    | 20.29%  |
| Samsung Electronics | 112       | 137    | 12.49%  |
| Hitachi             | 80        | 103    | 8.92%   |
| Toshiba             | 52        | 56     | 5.8%    |
| SanDisk             | 39        | 45     | 4.35%   |
| HGST                | 32        | 41     | 3.57%   |
| Crucial             | 29        | 31     | 3.23%   |
| SK Hynix            | 18        | 21     | 2.01%   |
| Fujitsu             | 16        | 21     | 1.78%   |
| Intel               | 15        | 15     | 1.67%   |
| Micron Technology   | 13        | 15     | 1.45%   |
| Kingston            | 10        | 11     | 1.11%   |
| MAXTOR              | 7         | 11     | 0.78%   |
| Intenso             | 6         | 7      | 0.67%   |
| Transcend           | 5         | 6      | 0.56%   |
| Apple               | 5         | 5      | 0.56%   |
| A-DATA Technology   | 4         | 5      | 0.45%   |
| WD MediaMax         | 3         | 3      | 0.33%   |
| LITEONIT            | 3         | 3      | 0.33%   |
| IBM                 | 3         | 3      | 0.33%   |
| Unknown             | 2         | 2      | 0.22%   |
| OCZ                 | 2         | 4      | 0.22%   |
| MDT                 | 2         | 2      | 0.22%   |
| IBM/Hitachi         | 2         | 2      | 0.22%   |
| ASMedia             | 2         | 2      | 0.22%   |
| XPG                 | 1         | 1      | 0.11%   |
| TO Exter            | 1         | 1      | 0.11%   |
| SSSTC               | 1         | 1      | 0.11%   |
| PNY                 | 1         | 1      | 0.11%   |
| PHISON              | 1         | 1      | 0.11%   |
| OCZ-VERTEX2         | 1         | 1      | 0.11%   |
| Neo Forza           | 1         | 1      | 0.11%   |
| Mushkin             | 1         | 1      | 0.11%   |
| LITEON              | 1         | 1      | 0.11%   |
| KingSpec            | 1         | 1      | 0.11%   |
| INNOVATION IT       | 1         | 1      | 0.11%   |
| IB                  | 1         | 1      | 0.11%   |
| HP Phison           | 1         | 1      | 0.11%   |
| GOODRAM             | 1         | 1      | 0.11%   |
| Corsair             | 1         | 1      | 0.11%   |
| Unknown             | 1         | 1      | 0.11%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 237       | 285    | 34.45%  |
| WDC                 | 173       | 247    | 25.15%  |
| Samsung Electronics | 81        | 100    | 11.77%  |
| Hitachi             | 80        | 103    | 11.63%  |
| Toshiba             | 46        | 49     | 6.69%   |
| HGST                | 32        | 41     | 4.65%   |
| Fujitsu             | 16        | 21     | 2.33%   |
| MAXTOR              | 7         | 11     | 1.02%   |
| WD MediaMax         | 3         | 3      | 0.44%   |
| IBM                 | 3         | 3      | 0.44%   |
| Apple               | 3         | 3      | 0.44%   |
| MDT                 | 2         | 2      | 0.29%   |
| IBM/Hitachi         | 2         | 2      | 0.29%   |
| ASMedia             | 2         | 2      | 0.29%   |
| IB                  | 1         | 1      | 0.15%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 649       | 873    | 75.55%  |
| SSD  | 187       | 206    | 21.77%  |
| NVMe | 23        | 29     | 2.68%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Samsung Electronics HD103UJ 1TB                  | 2         | 2      | 9.52%   |
| WDC WD5000BEVT-00A0RT0 500GB                     | 1         | 1      | 4.76%   |
| WDC WD40EZRZ-00GXCB0 4TB                         | 1         | 2      | 4.76%   |
| WDC WD30EZRS-00J99B0 3TB                         | 1         | 1      | 4.76%   |
| WDC PC SN520 SDAPMUW-512G-1001 512GB             | 1         | 1      | 4.76%   |
| TPH00800640GB 640GB                              | 1         | 1      | 4.76%   |
| Toshiba MK5065GSX 500GB                          | 1         | 1      | 4.76%   |
| Toshiba MK1059GSM 1TB                            | 1         | 1      | 4.76%   |
| Seagate ST9500325AS 500GB                        | 1         | 1      | 4.76%   |
| Seagate ST9320325AS 320GB                        | 1         | 1      | 4.76%   |
| Seagate ST3640323AS 640GB                        | 1         | 1      | 4.76%   |
| Samsung Electronics MZVLB1T0HALR-00000 1TB       | 1         | 2      | 4.76%   |
| Samsung Electronics MZ7LN256HCHP-00000 256GB SSD | 1         | 2      | 4.76%   |
| Samsung Electronics HD252HJ 250GB                | 1         | 1      | 4.76%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD   | 1         | 1      | 4.76%   |
| MAXTOR STM3500320AS 500GB                        | 1         | 1      | 4.76%   |
| Intenso SSD SATAIII 512GB                        | 1         | 1      | 4.76%   |
| Intel SSDSCKGF256A5 SATA 256GB                   | 1         | 1      | 4.76%   |
| Hitachi HTS541010G9SA00 100GB                    | 1         | 1      | 4.76%   |
| Hitachi HDP725040GLA360 400GB                    | 1         | 1      | 4.76%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 7      | 23.81%  |
| WDC                 | 4         | 5      | 19.05%  |
| Seagate             | 3         | 3      | 14.29%  |
| Toshiba             | 2         | 2      | 9.52%   |
| Hitachi             | 2         | 2      | 9.52%   |
| TPH00800640GB       | 1         | 1      | 4.76%   |
| Micron Technology   | 1         | 1      | 4.76%   |
| MAXTOR              | 1         | 1      | 4.76%   |
| Intenso             | 1         | 1      | 4.76%   |
| Intel               | 1         | 1      | 4.76%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 8766      | 18973  | 62.09%  |
| Works    | 4489      | 8606   | 31.8%   |
| Malfunc  | 841       | 1108   | 5.96%   |
| Failed   | 21        | 24     | 0.15%   |
| Limited  | 1         | 1      | 0.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 8568      | 52.55%  |
| AMD                              | 2953      | 18.11%  |
| Samsung Electronics              | 1514      | 9.29%   |
| Sandisk                          | 495       | 3.04%   |
| ASMedia Technology               | 324       | 1.99%   |
| Nvidia                           | 291       | 1.78%   |
| SK Hynix                         | 263       | 1.61%   |
| JMicron Technology               | 246       | 1.51%   |
| Marvell Technology Group         | 235       | 1.44%   |
| Toshiba America Info Systems     | 209       | 1.28%   |
| Phison Electronics               | 190       | 1.17%   |
| Kingston Technology Company      | 172       | 1.05%   |
| Micron/Crucial Technology        | 115       | 0.71%   |
| Micron Technology                | 100       | 0.61%   |
| KIOXIA                           | 85        | 0.52%   |
| VIA Technologies                 | 67        | 0.41%   |
| Silicon Motion                   | 63        | 0.39%   |
| ADATA Technology                 | 53        | 0.33%   |
| Silicon Image                    | 49        | 0.3%    |
| LSI Logic / Symbios Logic        | 42        | 0.26%   |
| Adaptec                          | 40        | 0.25%   |
| Broadcom / LSI                   | 36        | 0.22%   |
| Silicon Integrated Systems [SiS] | 26        | 0.16%   |
| Seagate Technology               | 20        | 0.12%   |
| Lenovo                           | 19        | 0.12%   |
| Lite-On Technology               | 15        | 0.09%   |
| Apple                            | 15        | 0.09%   |
| Union Memory (Shenzhen)          | 14        | 0.09%   |
| Realtek Semiconductor            | 13        | 0.08%   |
| Hewlett-Packard                  | 10        | 0.06%   |
| Solid State Storage Technology   | 9         | 0.06%   |
| Integrated Technology Express    | 8         | 0.05%   |
| Shenzhen Longsys Electronics     | 7         | 0.04%   |
| OCZ Technology Group             | 7         | 0.04%   |
| 3ware                            | 7         | 0.04%   |
| Unknown                          | 3         | 0.02%   |
| ULi Electronics                  | 3         | 0.02%   |
| Advanced System Products         | 3         | 0.02%   |
| Yangtze Memory Technologies      | 2         | 0.01%   |
| Promise Technology               | 2         | 0.01%   |
| Lite-On IT Corp. / Plextor       | 2         | 0.01%   |
| HighPoint Technologies           | 2         | 0.01%   |
| Chelsio Communications           | 2         | 0.01%   |
| Tekram Technology                | 1         | 0.01%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.01%   |
| Broadcom                         | 1         | 0.01%   |
| Artop Electronic                 | 1         | 0.01%   |
| Unknown                          | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 1838      | 9.51%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 955       | 4.94%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 656       | 3.39%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 615       | 3.18%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 591       | 3.06%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 499       | 2.58%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 489       | 2.53%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 487       | 2.52%   |
| AMD 400 Series Chipset SATA Controller                                                  | 471       | 2.44%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 397       | 2.05%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 341       | 1.76%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 329       | 1.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 328       | 1.7%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 302       | 1.56%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 289       | 1.49%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 276       | 1.43%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 272       | 1.41%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 244       | 1.26%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 227       | 1.17%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 226       | 1.17%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 223       | 1.15%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 218       | 1.13%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 204       | 1.06%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 199       | 1.03%   |
| Samsung NVMe SSD Controller 980                                                         | 193       | 1%      |
| AMD 500 Series Chipset SATA Controller                                                  | 188       | 0.97%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 187       | 0.97%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 183       | 0.95%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 178       | 0.92%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 162       | 0.84%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 154       | 0.8%    |
| JMicron JMB363 SATA/IDE Controller                                                      | 149       | 0.77%   |
| Intel SATA Controller [RAID mode]                                                       | 142       | 0.73%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 142       | 0.73%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 129       | 0.67%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 128       | 0.66%   |
| Intel SSD 660P Series                                                                   | 126       | 0.65%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 121       | 0.63%   |
| AMD 300 Series Chipset SATA Controller                                                  | 119       | 0.62%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 114       | 0.59%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 112       | 0.58%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 111       | 0.57%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 110       | 0.57%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 107       | 0.55%   |
| Phison E12 NVMe Controller                                                              | 104       | 0.54%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 100       | 0.52%   |
| Micron Non-Volatile memory controller                                                   | 99        | 0.51%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 95        | 0.49%   |
| Nvidia MCP61 SATA Controller                                                            | 95        | 0.49%   |
| AMD X370 Series Chipset SATA Controller                                                 | 93        | 0.48%   |
| AMD FCH SATA Controller D                                                               | 93        | 0.48%   |
| Nvidia MCP61 IDE                                                                        | 86        | 0.44%   |
| SK Hynix BC501 NVMe Solid State Drive                                                   | 83        | 0.43%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 80        | 0.41%   |
| KIOXIA Non-Volatile memory controller                                                   | 80        | 0.41%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 80        | 0.41%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 79        | 0.41%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 76        | 0.39%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 74        | 0.38%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 74        | 0.38%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 10047     | 60.3%   |
| NVMe | 3398      | 20.39%  |
| IDE  | 2324      | 13.95%  |
| RAID | 779       | 4.68%   |
| SAS  | 58        | 0.35%   |
| SCSI | 56        | 0.34%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 9548      | 72.15%  |
| AMD                   | 3522      | 26.61%  |
| ARM                   | 148       | 1.12%   |
| QUALCOMM              | 5         | 0.04%   |
| Unknown               | 4         | 0.03%   |
| PowerMac3,6           | 1         | 0.01%   |
| PowerMac10,2          | 1         | 0.01%   |
| PowerBook5,6          | 1         | 0.01%   |
| PowerBook5,4          | 1         | 0.01%   |
| PowerBook3,4          | 1         | 0.01%   |
| Marvell Semiconductor | 1         | 0.01%   |
| CentaurHauls          | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 147       | 1.11%   |
| AMD Ryzen 5 3600 6-Core Processor             | 133       | 1%      |
| Intel Core i5-2520M CPU @ 2.50GHz             | 122       | 0.92%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 121       | 0.91%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 119       | 0.9%    |
| ARM Processor                                 | 119       | 0.9%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 111       | 0.84%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 108       | 0.81%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 107       | 0.81%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 102       | 0.77%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 100       | 0.75%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 98        | 0.74%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 95        | 0.72%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 91        | 0.69%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 89        | 0.67%   |
| AMD FX-8350 Eight-Core Processor              | 85        | 0.64%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 83        | 0.63%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 74        | 0.56%   |
| AMD FX-6300 Six-Core Processor                | 74        | 0.56%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 71        | 0.54%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 69        | 0.52%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 69        | 0.52%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 66        | 0.5%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 65        | 0.49%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 64        | 0.48%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 63        | 0.47%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 62        | 0.47%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 60        | 0.45%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 59        | 0.44%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 58        | 0.44%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 58        | 0.44%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 56        | 0.42%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 56        | 0.42%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 56        | 0.42%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 56        | 0.42%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 56        | 0.42%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 55        | 0.41%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 52        | 0.39%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 52        | 0.39%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 52        | 0.39%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 51        | 0.38%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 51        | 0.38%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 51        | 0.38%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 51        | 0.38%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 51        | 0.38%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 49        | 0.37%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 48        | 0.36%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 47        | 0.35%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 45        | 0.34%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 45        | 0.34%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 44        | 0.33%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 44        | 0.33%   |
| AMD FX-4300 Quad-Core Processor               | 44        | 0.33%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 43        | 0.32%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 43        | 0.32%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 43        | 0.32%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 43        | 0.32%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 42        | 0.32%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 42        | 0.32%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 42        | 0.32%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 2881      | 21.74%  |
| Intel Core i7           | 2358      | 17.79%  |
| Intel Core i3           | 824       | 6.22%   |
| AMD Ryzen 5             | 785       | 5.92%   |
| Intel Core 2 Duo        | 732       | 5.52%   |
| AMD Ryzen 7             | 656       | 4.95%   |
| Intel Celeron           | 514       | 3.88%   |
| Other                   | 472       | 3.56%   |
| Intel Pentium           | 408       | 3.08%   |
| AMD FX                  | 347       | 2.62%   |
| Intel Atom              | 315       | 2.38%   |
| Intel Xeon              | 301       | 2.27%   |
| Intel Pentium Dual-Core | 175       | 1.32%   |
| Intel Core 2 Quad       | 169       | 1.28%   |
| AMD Ryzen 9             | 147       | 1.11%   |
| AMD Phenom II X4        | 136       | 1.03%   |
| AMD Ryzen 3             | 133       | 1%      |
| AMD A8                  | 131       | 0.99%   |
| AMD A4                  | 104       | 0.78%   |
| AMD A10                 | 99        | 0.75%   |
| Intel Core 2            | 98        | 0.74%   |
| AMD Athlon II X2        | 95        | 0.72%   |
| AMD A6                  | 86        | 0.65%   |
| AMD Ryzen 7 PRO         | 82        | 0.62%   |
| Intel Pentium Silver    | 78        | 0.59%   |
| AMD E                   | 73        | 0.55%   |
| Intel Core i9           | 63        | 0.48%   |
| Intel Pentium Dual      | 61        | 0.46%   |
| AMD Athlon 64 X2        | 58        | 0.44%   |
| Intel Genuine           | 53        | 0.4%    |
| AMD Athlon              | 52        | 0.39%   |
| Intel Pentium 4         | 51        | 0.38%   |
| AMD Athlon II X4        | 48        | 0.36%   |
| AMD Ryzen 5 PRO         | 41        | 0.31%   |
| Intel Pentium M         | 38        | 0.29%   |
| AMD E2                  | 36        | 0.27%   |
| AMD Turion 64 X2 Mobile | 34        | 0.26%   |
| AMD Phenom II X6        | 30        | 0.23%   |
| AMD Ryzen Threadripper  | 24        | 0.18%   |
| AMD E1                  | 24        | 0.18%   |
| Intel Celeron M         | 22        | 0.17%   |
| AMD Phenom              | 22        | 0.17%   |
| ARM BCM                 | 21        | 0.16%   |
| Intel Pentium D         | 20        | 0.15%   |
| AMD Athlon X2           | 19        | 0.14%   |
| Intel Core m3           | 17        | 0.13%   |
| AMD Athlon 64           | 17        | 0.13%   |
| Intel Core M            | 16        | 0.12%   |
| AMD Athlon X4           | 15        | 0.11%   |
| AMD Athlon II           | 14        | 0.11%   |
| AMD Athlon Dual Core    | 14        | 0.11%   |
| AMD GX                  | 13        | 0.1%    |
| Intel Pentium Gold      | 12        | 0.09%   |
| AMD Turion 64 Mobile    | 11        | 0.08%   |
| AMD Sempron             | 11        | 0.08%   |
| Intel Core m5           | 9         | 0.07%   |
| AMD Phenom II X2        | 9         | 0.07%   |
| AMD G                   | 9         | 0.07%   |
| AMD Athlon II X3        | 9         | 0.07%   |
| Intel Pentium III       | 8         | 0.06%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 5401      | 40.72%  |
| 4       | 5018      | 37.83%  |
| 6       | 1127      | 8.5%    |
| 8       | 872       | 6.57%   |
| 1       | 409       | 3.08%   |
| 3       | 128       | 0.96%   |
| 12      | 124       | 0.93%   |
| 16      | 77        | 0.58%   |
| Unknown | 41        | 0.31%   |
| 10      | 30        | 0.23%   |
| 14      | 9         | 0.07%   |
| 32      | 8         | 0.06%   |
| 24      | 7         | 0.05%   |
| 40      | 4         | 0.03%   |
| 5       | 3         | 0.02%   |
| 20      | 2         | 0.02%   |
| 18      | 2         | 0.02%   |
| 68      | 1         | 0.01%   |
| 64      | 1         | 0.01%   |
| 36      | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 13126     | 99.18%  |
| 2       | 96        | 0.73%   |
| Unknown | 8         | 0.06%   |
| 4       | 5         | 0.04%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 8194      | 61.79%  |
| 1       | 5022      | 37.87%  |
| Unknown | 41        | 0.31%   |
| 4       | 2         | 0.02%   |
| 8       | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 12702     | 95.65%  |
| Unknown        | 376       | 2.83%   |
| 32-bit         | 187       | 1.41%   |
| 64-bit         | 14        | 0.11%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2541      | 18.61%  |
| 0x206a7    | 892       | 6.53%   |
| 0x306a9    | 814       | 5.96%   |
| 0x306c3    | 663       | 4.86%   |
| 0x1067a    | 585       | 4.29%   |
| 0x906ea    | 307       | 2.25%   |
| 0x806ea    | 301       | 2.2%    |
| 0x506e3    | 292       | 2.14%   |
| 0x806ec    | 267       | 1.96%   |
| 0x20655    | 264       | 1.93%   |
| 0x40651    | 257       | 1.88%   |
| 0x406e3    | 242       | 1.77%   |
| 0x806e9    | 223       | 1.63%   |
| 0x08701021 | 209       | 1.53%   |
| 0x906e9    | 200       | 1.47%   |
| 0x06000852 | 200       | 1.47%   |
| 0x806c1    | 196       | 1.44%   |
| 0x306d4    | 193       | 1.41%   |
| 0x010000c8 | 191       | 1.4%    |
| 0x0800820d | 176       | 1.29%   |
| 0x6fd      | 173       | 1.27%   |
| 0x10676    | 167       | 1.22%   |
| 0x406c4    | 151       | 1.11%   |
| 0x08108109 | 143       | 1.05%   |
| 0x30678    | 137       | 1%      |
| 0x06001119 | 136       | 1%      |
| 0x20652    | 131       | 0.96%   |
| 0x08108102 | 125       | 0.92%   |
| 0x6fb      | 122       | 0.89%   |
| 0x08701013 | 118       | 0.86%   |
| 0x706a1    | 111       | 0.81%   |
| 0x08600106 | 108       | 0.79%   |
| 0x506c9    | 103       | 0.75%   |
| 0x806eb    | 100       | 0.73%   |
| 0x106e5    | 100       | 0.73%   |
| 0xa0652    | 74        | 0.54%   |
| 0x906ed    | 74        | 0.54%   |
| 0x6f6      | 73        | 0.53%   |
| 0x08600103 | 72        | 0.53%   |
| 0x0810100b | 72        | 0.53%   |
| 0x706e5    | 71        | 0.52%   |
| 0x08001138 | 69        | 0.51%   |
| 0x08608103 | 66        | 0.48%   |
| 0x106ca    | 64        | 0.47%   |
| 0x0a50000c | 64        | 0.47%   |
| 0x05000119 | 64        | 0.47%   |
| 0x406c3    | 62        | 0.45%   |
| 0x06006705 | 61        | 0.45%   |
| 0x106c2    | 54        | 0.4%    |
| 0x07030105 | 54        | 0.4%    |
| 0x0600063e | 54        | 0.4%    |
| 0x08001137 | 51        | 0.37%   |
| 0x010000db | 51        | 0.37%   |
| 0x0a201009 | 50        | 0.37%   |
| 0x706a8    | 47        | 0.34%   |
| 0x08101016 | 41        | 0.3%    |
| 0x106a5    | 40        | 0.29%   |
| 0x0700010f | 40        | 0.29%   |
| 0x06003106 | 40        | 0.29%   |
| 0xa0655    | 38        | 0.28%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 1797      | 13.56%  |
| Haswell          | 1132      | 8.54%   |
| SandyBridge      | 1069      | 8.07%   |
| IvyBridge        | 975       | 7.36%   |
| Penryn           | 869       | 6.56%   |
| Zen 2            | 706       | 5.33%   |
| Skylake          | 678       | 5.12%   |
| Zen+             | 563       | 4.25%   |
| Westmere         | 496       | 3.74%   |
| Core             | 470       | 3.55%   |
| Piledriver       | 435       | 3.28%   |
| Silvermont       | 419       | 3.16%   |
| K10              | 411       | 3.1%    |
| Zen              | 349       | 2.63%   |
| Unknown          | 316       | 2.38%   |
| Broadwell        | 248       | 1.87%   |
| TigerLake        | 224       | 1.69%   |
| Zen 3            | 207       | 1.56%   |
| Goldmont plus    | 181       | 1.37%   |
| CometLake        | 173       | 1.31%   |
| Nehalem          | 170       | 1.28%   |
| K8 Hammer        | 159       | 1.2%    |
| Bonnell          | 144       | 1.09%   |
| Excavator        | 136       | 1.03%   |
| Goldmont         | 130       | 0.98%   |
| IceLake          | 114       | 0.86%   |
| Bobcat           | 109       | 0.82%   |
| P6               | 99        | 0.75%   |
| Puma             | 89        | 0.67%   |
| NetBurst         | 85        | 0.64%   |
| Bulldozer        | 67        | 0.51%   |
| Jaguar           | 58        | 0.44%   |
| Steamroller      | 57        | 0.43%   |
| K10 Llano        | 48        | 0.36%   |
| K8 & K10 hybrid  | 27        | 0.2%    |
| Tremont          | 20        | 0.15%   |
| Alderlake Hybrid | 13        | 0.1%    |
| K6               | 6         | 0.05%   |
| CannonLake       | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 6910      | 46.07%  |
| Nvidia                                       | 4155      | 27.7%   |
| AMD                                          | 3784      | 25.23%  |
| Matrox Electronics Systems                   | 60        | 0.4%    |
| ASPEED Technology                            | 47        | 0.31%   |
| Silicon Integrated Systems [SiS]             | 14        | 0.09%   |
| VIA Technologies                             | 11        | 0.07%   |
| S3 Graphics                                  | 8         | 0.05%   |
| ATI Technologies                             | 5         | 0.03%   |
| XGI Technology (eXtreme Graphics Innovation) | 3         | 0.02%   |
| Neomagic                                     | 1         | 0.01%   |
| Dome Imaging Systems                         | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 736       | 4.75%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 585       | 3.77%   |
| Intel UHD Graphics 620                                                                   | 312       | 2.01%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 305       | 1.97%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 301       | 1.94%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 299       | 1.93%   |
| AMD Renoir                                                                               | 288       | 1.86%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 283       | 1.83%   |
| Intel Core Processor Integrated Graphics Controller                                      | 264       | 1.7%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 250       | 1.61%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 239       | 1.54%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 235       | 1.52%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 233       | 1.5%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 231       | 1.49%   |
| Intel HD Graphics 620                                                                    | 220       | 1.42%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 207       | 1.34%   |
| Intel HD Graphics 530                                                                    | 185       | 1.19%   |
| Intel HD Graphics 5500                                                                   | 183       | 1.18%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 183       | 1.18%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 179       | 1.15%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 178       | 1.15%   |
| Intel HD Graphics 630                                                                    | 155       | 1%      |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 154       | 0.99%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 137       | 0.88%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 135       | 0.87%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 129       | 0.83%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 125       | 0.81%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 119       | 0.77%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 108       | 0.7%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 104       | 0.67%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 104       | 0.67%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 102       | 0.66%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 100       | 0.64%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 99        | 0.64%   |
| AMD Lucienne                                                                             | 95        | 0.61%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 88        | 0.57%   |
| Intel HD Graphics 500                                                                    | 85        | 0.55%   |
| AMD Cezanne                                                                              | 83        | 0.54%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 82        | 0.53%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 81        | 0.52%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 81        | 0.52%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 75        | 0.48%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 74        | 0.48%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 73        | 0.47%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 68        | 0.44%   |
| Nvidia GT218 [GeForce 210]                                                               | 65        | 0.42%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 64        | 0.41%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 64        | 0.41%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 62        | 0.4%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 61        | 0.39%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 60        | 0.39%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 60        | 0.39%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 59        | 0.38%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 59        | 0.38%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 58        | 0.37%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 58        | 0.37%   |
| AMD RS780L [Radeon 3000]                                                                 | 57        | 0.37%   |
| Nvidia GP108M [GeForce MX150]                                                            | 56        | 0.36%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 55        | 0.35%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 54        | 0.35%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| 1 x Intel                         | 5177      | 38.85%  |
| 1 x AMD                           | 3213      | 24.11%  |
| 1 x Nvidia                        | 2685      | 20.15%  |
| Intel + Nvidia                    | 1303      | 9.78%   |
| Intel + AMD                       | 304       | 2.28%   |
| Other                             | 170       | 1.28%   |
| 2 x AMD                           | 168       | 1.26%   |
| AMD + Nvidia                      | 92        | 0.69%   |
| 2 x Nvidia                        | 61        | 0.46%   |
| 1 x Matrox                        | 52        | 0.39%   |
| 1 x ASPEED                        | 31        | 0.23%   |
| 1 x SiS                           | 14        | 0.11%   |
| 1 x VIA                           | 11        | 0.08%   |
| Nvidia + ASPEED                   | 11        | 0.08%   |
| 1 x S3 Graphics                   | 8         | 0.06%   |
| Nvidia + Matrox                   | 5         | 0.04%   |
| AMD + Matrox                      | 3         | 0.02%   |
| AMD + ASPEED                      | 3         | 0.02%   |
| Nvidia + XGI                      | 2         | 0.02%   |
| Intel + AMD + 1 x Nvidia          | 2         | 0.02%   |
| 5 x AMD                           | 1         | 0.01%   |
| 4 x Nvidia                        | 1         | 0.01%   |
| 2 x Nvidia + 1 x ASPEED           | 1         | 0.01%   |
| 2 x Intel                         | 1         | 0.01%   |
| 2 x AMD + 1 x Nvidia + 1 x ASPEED | 1         | 0.01%   |
| Nvidia + Dome Imaging Systems     | 1         | 0.01%   |
| 1 x Neomagic                      | 1         | 0.01%   |
| 1 x Intel + 4 x AMD               | 1         | 0.01%   |
| AMD + XGI                         | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 10654     | 79.14%  |
| Proprietary | 2108      | 15.66%  |
| Unknown     | 700       | 5.2%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 6787      | 49.6%   |
| 1.01-2.0   | 1887      | 13.79%  |
| 0.01-0.5   | 1756      | 12.83%  |
| 0.51-1.0   | 1248      | 9.12%   |
| 3.01-4.0   | 916       | 6.69%   |
| 7.01-8.0   | 608       | 4.44%   |
| 5.01-6.0   | 262       | 1.91%   |
| 8.01-16.0  | 117       | 0.86%   |
| 2.01-3.0   | 89        | 0.65%   |
| 4.01-5.0   | 7         | 0.05%   |
| 16.01-24.0 | 7         | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 1839      | 12.98%  |
| AU Optronics            | 1627      | 11.49%  |
| LG Display              | 1289      | 9.1%    |
| Chimei Innolux          | 906       | 6.4%    |
| BOE                     | 741       | 5.23%   |
| Goldstar                | 731       | 5.16%   |
| Dell                    | 676       | 4.77%   |
| Acer                    | 569       | 4.02%   |
| BenQ                    | 534       | 3.77%   |
| Ancor Communications    | 392       | 2.77%   |
| Hewlett-Packard         | 379       | 2.68%   |
| Lenovo                  | 372       | 2.63%   |
| Philips                 | 289       | 2.04%   |
| AOC                     | 281       | 1.98%   |
| Fujitsu Siemens         | 238       | 1.68%   |
| Iiyama                  | 222       | 1.57%   |
| Chi Mei Optoelectronics | 222       | 1.57%   |
| Sharp                   | 208       | 1.47%   |
| Apple                   | 208       | 1.47%   |
| Eizo                    | 175       | 1.24%   |
| Medion                  | 165       | 1.17%   |
| Unknown                 | 108       | 0.76%   |
| PANDA                   | 107       | 0.76%   |
| Sony                    | 105       | 0.74%   |
| LG Philips              | 104       | 0.73%   |
| HannStar                | 102       | 0.72%   |
| LG Electronics          | 94        | 0.66%   |
| NEC Computers           | 90        | 0.64%   |
| InfoVision              | 84        | 0.59%   |
| Panasonic               | 80        | 0.56%   |
| ASUSTek Computer        | 80        | 0.56%   |
| ViewSonic               | 66        | 0.47%   |
| Vestel Elektronik       | 61        | 0.43%   |
| Belinea                 | 51        | 0.36%   |
| Toshiba                 | 47        | 0.33%   |
| CPT                     | 47        | 0.33%   |
| Compal                  | 44        | 0.31%   |
| Grundig                 | 40        | 0.28%   |
| Idek Iiyama             | 39        | 0.28%   |
| Seiko/Epson             | 28        | 0.2%    |
| MSI                     | 26        | 0.18%   |
| CSO                     | 26        | 0.18%   |
| LGD                     | 25        | 0.18%   |
| FUS                     | 22        | 0.16%   |
| DENON                   | 22        | 0.16%   |
| Hitachi                 | 19        | 0.13%   |
| Plain Tree Systems      | 18        | 0.13%   |
| AUS                     | 17        | 0.12%   |
| InnoLux Display         | 16        | 0.11%   |
| HPN                     | 16        | 0.11%   |
| ___                     | 15        | 0.11%   |
| Packard Bell            | 15        | 0.11%   |
| MStar                   | 15        | 0.11%   |
| HannStar Display        | 15        | 0.11%   |
| Quanta Display          | 13        | 0.09%   |
| Hyundai ImageQuest      | 13        | 0.09%   |
| Denver                  | 13        | 0.09%   |
| IBM                     | 12        | 0.08%   |
| HKC                     | 12        | 0.08%   |
| CHD                     | 12        | 0.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x390mm 31.5-inch      | 61        | 0.41%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch             | 61        | 0.41%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 54        | 0.37%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 54        | 0.37%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 47        | 0.32%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                        | 46        | 0.31%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch      | 45        | 0.31%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch              | 42        | 0.28%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                   | 42        | 0.28%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 37        | 0.25%   |
| Grundig UHD GRU4448 3840x2160 1210x680mm 54.6-inch                        | 37        | 0.25%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                     | 37        | 0.25%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 37        | 0.25%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch          | 37        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 36        | 0.24%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch            | 35        | 0.24%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 35        | 0.24%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch             | 35        | 0.24%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 33        | 0.22%   |
| BOE LCD Monitor BOE0660 1600x900 382x215mm 17.3-inch                      | 33        | 0.22%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                   | 31        | 0.21%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch         | 30        | 0.2%    |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch               | 30        | 0.2%    |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 30        | 0.2%    |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 30        | 0.2%    |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch     | 30        | 0.2%    |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch          | 29        | 0.2%    |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch             | 29        | 0.2%    |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch      | 28        | 0.19%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch         | 28        | 0.19%   |
| Panasonic TV MEIA296 1280x1024 698x392mm 31.5-inch                        | 28        | 0.19%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch               | 28        | 0.19%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                      | 28        | 0.19%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch            | 28        | 0.19%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch            | 28        | 0.19%   |
| LG Display LCD Monitor LGD056D 1920x1080 382x215mm 17.3-inch              | 27        | 0.18%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch           | 27        | 0.18%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 27        | 0.18%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch         | 26        | 0.18%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                  | 26        | 0.18%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 26        | 0.18%   |
| AU Optronics LCD Monitor AUO129E 1600x900 382x214mm 17.2-inch             | 26        | 0.18%   |
| Panasonic LCD Monitor MEI96A2 2880x1620 344x193mm 15.5-inch               | 25        | 0.17%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch               | 25        | 0.17%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch             | 25        | 0.17%   |
| Ancor Communications VS278 ACI27A1 1920x1080 598x336mm 27.0-inch          | 25        | 0.17%   |
| Lenovo LCD Monitor LEN40B0 1366x768 345x194mm 15.6-inch                   | 24        | 0.16%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                 | 24        | 0.16%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch             | 24        | 0.16%   |
| AU Optronics LCD Monitor AUO219E 1600x900 382x214mm 17.2-inch             | 24        | 0.16%   |
| AU Optronics LCD Monitor AUO119E 1600x900 382x214mm 17.2-inch             | 24        | 0.16%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 23        | 0.16%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 23        | 0.16%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch      | 22        | 0.15%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch              | 22        | 0.15%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x194mm 15.5-inch             | 22        | 0.15%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 353x198mm 15.9-inch      | 21        | 0.14%   |
| Lenovo LCD Monitor LEN4050 1280x800 331x207mm 15.4-inch                   | 21        | 0.14%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch                   | 21        | 0.14%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                         | 21        | 0.14%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 5828      | 42.64%  |
| 1366x768 (WXGA)    | 1734      | 12.69%  |
| 3840x2160 (4K)     | 898       | 6.57%   |
| 1600x900 (HD+)     | 838       | 6.13%   |
| 2560x1440 (QHD)    | 677       | 4.95%   |
| 1280x1024 (SXGA)   | 609       | 4.46%   |
| 1680x1050 (WSXGA+) | 601       | 4.4%    |
| 1920x1200 (WUXGA)  | 450       | 3.29%   |
| 1280x800 (WXGA)    | 403       | 2.95%   |
| 1440x900 (WXGA+)   | 293       | 2.14%   |
| Unknown            | 242       | 1.77%   |
| 3440x1440          | 123       | 0.9%    |
| 3840x1080          | 107       | 0.78%   |
| 2560x1080          | 78        | 0.57%   |
| 1024x600           | 72        | 0.53%   |
| 1600x1200          | 57        | 0.42%   |
| 1024x768 (XGA)     | 56        | 0.41%   |
| 1920x540           | 55        | 0.4%    |
| 2560x1600          | 50        | 0.37%   |
| 1360x768           | 50        | 0.37%   |
| 2160x1440          | 32        | 0.23%   |
| 2880x1800          | 30        | 0.22%   |
| 3200x1800 (QHD+)   | 26        | 0.19%   |
| 3840x2400          | 23        | 0.17%   |
| 3840x1600          | 20        | 0.15%   |
| 3840x1200          | 18        | 0.13%   |
| 2736x1824          | 16        | 0.12%   |
| 1680x945           | 16        | 0.12%   |
| 4480x1440          | 15        | 0.11%   |
| 1400x1050          | 15        | 0.11%   |
| 2256x1504          | 14        | 0.1%    |
| 5760x2160          | 13        | 0.1%    |
| 2048x1152          | 13        | 0.1%    |
| 1920x1280          | 12        | 0.09%   |
| 1280x720 (HD)      | 12        | 0.09%   |
| 3200x1080          | 11        | 0.08%   |
| 3000x2000          | 11        | 0.08%   |
| 1280x768           | 9         | 0.07%   |
| 3600x1080          | 8         | 0.06%   |
| 5760x1080          | 6         | 0.04%   |
| 2288x1287          | 6         | 0.04%   |
| 7680x2160          | 5         | 0.04%   |
| 6400x2160          | 5         | 0.04%   |
| 5120x1440          | 5         | 0.04%   |
| 3360x1080          | 5         | 0.04%   |
| 2880x1920          | 5         | 0.04%   |
| 800x1280           | 4         | 0.03%   |
| 3360x1050          | 4         | 0.03%   |
| 2304x1440          | 4         | 0.03%   |
| 1800x1200          | 4         | 0.03%   |
| 2560x1024          | 3         | 0.02%   |
| 1280x854           | 3         | 0.02%   |
| 1024x576           | 3         | 0.02%   |
| 7680x1440          | 2         | 0.01%   |
| 7680x1080          | 2         | 0.01%   |
| 5520x1080          | 2         | 0.01%   |
| 5360x1440          | 2         | 0.01%   |
| 5280x1080          | 2         | 0.01%   |
| 4240x1440          | 2         | 0.01%   |
| 3286x1080          | 2         | 0.01%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 2958      | 21.01%  |
| 24      | 1281      | 9.1%    |
| 27      | 1262      | 8.96%   |
| 17      | 1149      | 8.16%   |
| 13      | 1017      | 7.22%   |
| Unknown | 972       | 6.9%    |
| 14      | 902       | 6.41%   |
| 23      | 886       | 6.29%   |
| 21      | 601       | 4.27%   |
| 19      | 495       | 3.52%   |
| 22      | 441       | 3.13%   |
| 12      | 289       | 2.05%   |
| 31      | 209       | 1.48%   |
| 11      | 165       | 1.17%   |
| 34      | 160       | 1.14%   |
| 84      | 158       | 1.12%   |
| 20      | 150       | 1.07%   |
| 18      | 134       | 0.95%   |
| 10      | 105       | 0.75%   |
| 54      | 92        | 0.65%   |
| 25      | 80        | 0.57%   |
| 72      | 79        | 0.56%   |
| 32      | 72        | 0.51%   |
| 16      | 56        | 0.4%    |
| 40      | 48        | 0.34%   |
| 28      | 37        | 0.26%   |
| 26      | 31        | 0.22%   |
| 65      | 29        | 0.21%   |
| 33      | 24        | 0.17%   |
| 37      | 23        | 0.16%   |
| 48      | 19        | 0.13%   |
| 52      | 18        | 0.13%   |
| 49      | 16        | 0.11%   |
| 42      | 14        | 0.1%    |
| 46      | 11        | 0.08%   |
| 39      | 11        | 0.08%   |
| 43      | 10        | 0.07%   |
| 29      | 10        | 0.07%   |
| 55      | 9         | 0.06%   |
| 35      | 9         | 0.06%   |
| 8       | 9         | 0.06%   |
| 50      | 7         | 0.05%   |
| 47      | 6         | 0.04%   |
| 142     | 5         | 0.04%   |
| 30      | 4         | 0.03%   |
| 64      | 3         | 0.02%   |
| 95      | 2         | 0.01%   |
| 60      | 2         | 0.01%   |
| 41      | 2         | 0.01%   |
| 7       | 2         | 0.01%   |
| 75      | 1         | 0.01%   |
| 66      | 1         | 0.01%   |
| 63      | 1         | 0.01%   |
| 59      | 1         | 0.01%   |
| 57      | 1         | 0.01%   |
| 36      | 1         | 0.01%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 4364      | 31.51%  |
| 501-600        | 3176      | 22.93%  |
| 351-400        | 1516      | 10.95%  |
| 401-500        | 1423      | 10.28%  |
| 201-300        | 1162      | 8.39%   |
| Unknown        | 972       | 7.02%   |
| 601-700        | 395       | 2.85%   |
| 701-800        | 256       | 1.85%   |
| 1501-2000      | 238       | 1.72%   |
| 1001-1500      | 216       | 1.56%   |
| 801-900        | 90        | 0.65%   |
| 901-1000       | 24        | 0.17%   |
| 101-200        | 11        | 0.08%   |
| More than 2000 | 5         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 9085      | 70.38%  |
| 16/10   | 1804      | 13.98%  |
| Unknown | 850       | 6.59%   |
| 5/4     | 561       | 4.35%   |
| 21/9    | 204       | 1.58%   |
| 3/2     | 160       | 1.24%   |
| 4/3     | 148       | 1.15%   |
| 32/9    | 39        | 0.3%    |
| 6/5     | 35        | 0.27%   |
| 0.62    | 7         | 0.05%   |
| 1.00    | 6         | 0.05%   |
| 3.20    | 3         | 0.02%   |
| 3.73    | 1         | 0.01%   |
| 1.96    | 1         | 0.01%   |
| 0.89    | 1         | 0.01%   |
| 0.65    | 1         | 0.01%   |
| 0.56    | 1         | 0.01%   |
| 0.45    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 2959      | 21.18%  |
| 201-250        | 2477      | 17.73%  |
| 81-90          | 1403      | 10.04%  |
| 301-350        | 1285      | 9.2%    |
| Unknown        | 972       | 6.96%   |
| 121-130        | 847       | 6.06%   |
| 151-200        | 826       | 5.91%   |
| 251-300        | 589       | 4.22%   |
| 71-80          | 521       | 3.73%   |
| 351-500        | 510       | 3.65%   |
| More than 1000 | 411       | 2.94%   |
| 61-70          | 271       | 1.94%   |
| 141-150        | 261       | 1.87%   |
| 51-60          | 166       | 1.19%   |
| 131-140        | 160       | 1.15%   |
| 501-1000       | 147       | 1.05%   |
| 41-50          | 103       | 0.74%   |
| 91-100         | 25        | 0.18%   |
| 111-120        | 24        | 0.17%   |
| 1-40           | 11        | 0.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 4923      | 36.28%  |
| 121-160       | 3246      | 23.92%  |
| 101-120       | 3214      | 23.69%  |
| Unknown       | 972       | 7.16%   |
| 161-240       | 733       | 5.4%    |
| 1-50          | 247       | 1.82%   |
| More than 240 | 233       | 1.72%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 10698     | 78.98%  |
| 2     | 1873      | 13.83%  |
| 0     | 711       | 5.25%   |
| 3     | 239       | 1.76%   |
| 4     | 23        | 0.17%   |
| 5     | 2         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 6701      | 34.51%  |
| Intel                             | 6494      | 33.44%  |
| Qualcomm Atheros                  | 2137      | 11.01%  |
| Broadcom                          | 1089      | 5.61%   |
| Marvell Technology Group          | 275       | 1.42%   |
| Nvidia                            | 240       | 1.24%   |
| Broadcom Limited                  | 218       | 1.12%   |
| Ralink Technology                 | 167       | 0.86%   |
| Sierra Wireless                   | 142       | 0.73%   |
| Ralink                            | 142       | 0.73%   |
| Ericsson Business Mobile Networks | 142       | 0.73%   |
| TP-Link                           | 135       | 0.7%    |
| Dell                              | 119       | 0.61%   |
| AVM                               | 86        | 0.44%   |
| Microsoft                         | 85        | 0.44%   |
| Lenovo                            | 78        | 0.4%    |
| ASIX Electronics                  | 74        | 0.38%   |
| Edimax Technology                 | 62        | 0.32%   |
| MEDIATEK                          | 60        | 0.31%   |
| Samsung Electronics               | 57        | 0.29%   |
| DisplayLink                       | 57        | 0.29%   |
| Hewlett-Packard                   | 56        | 0.29%   |
| Huawei Technologies               | 55        | 0.28%   |
| D-Link System                     | 55        | 0.28%   |
| IMC Networks                      | 47        | 0.24%   |
| ASUSTek Computer                  | 46        | 0.24%   |
| Qualcomm Atheros Communications   | 40        | 0.21%   |
| VIA Technologies                  | 34        | 0.18%   |
| D-Link                            | 34        | 0.18%   |
| Aquantia                          | 34        | 0.18%   |
| Fibocom                           | 31        | 0.16%   |
| NetGear                           | 28        | 0.14%   |
| JMicron Technology                | 27        | 0.14%   |
| Belkin Components                 | 22        | 0.11%   |
| Silicon Integrated Systems [SiS]  | 19        | 0.1%    |
| Sitecom Europe                    | 17        | 0.09%   |
| Xiaomi                            | 16        | 0.08%   |
| 3Com                              | 15        | 0.08%   |
| Microchip Technology              | 14        | 0.07%   |
| Mellanox Technologies             | 13        | 0.07%   |
| Arduino SA                        | 12        | 0.06%   |
| Attansic Technology               | 11        | 0.06%   |
| Apple                             | 11        | 0.06%   |
| Qualcomm                          | 10        | 0.05%   |
| ZyXEL Communications              | 8         | 0.04%   |
| ZyDAS                             | 8         | 0.04%   |
| U-Blox                            | 8         | 0.04%   |
| Google                            | 8         | 0.04%   |
| AMD                               | 7         | 0.04%   |
| Toshiba                           | 6         | 0.03%   |
| Standard Microsystems             | 6         | 0.03%   |
| Texas Instruments                 | 5         | 0.03%   |
| Linksys                           | 5         | 0.03%   |
| Intersil                          | 5         | 0.03%   |
| HMD Global                        | 5         | 0.03%   |
| American Megatrends               | 5         | 0.03%   |
| ADMtek                            | 5         | 0.03%   |
| Wacom                             | 4         | 0.02%   |
| ICS Advent                        | 4         | 0.02%   |
| Holtek Semiconductor              | 4         | 0.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 5071      | 22.01%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 654       | 2.84%   |
| Intel Wi-Fi 6 AX200                                                     | 567       | 2.46%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 514       | 2.23%   |
| Intel Wireless 8265 / 8275                                              | 380       | 1.65%   |
| Intel I211 Gigabit Network Connection                                   | 378       | 1.64%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 345       | 1.5%    |
| Intel Wireless 7260                                                     | 322       | 1.4%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 313       | 1.36%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 305       | 1.32%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 266       | 1.15%   |
| Intel Wireless 8260                                                     | 247       | 1.07%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 240       | 1.04%   |
| Intel Wireless 7265                                                     | 232       | 1.01%   |
| Intel Ethernet Connection (2) I219-V                                    | 229       | 0.99%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 205       | 0.89%   |
| Realtek RTL8125 2.5GbE Controller                                       | 199       | 0.86%   |
| Intel Ethernet Connection I217-LM                                       | 189       | 0.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 187       | 0.81%   |
| Intel Wireless 3165                                                     | 186       | 0.81%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 174       | 0.76%   |
| Intel 82579V Gigabit Network Connection                                 | 173       | 0.75%   |
| Intel Wireless-AC 9260                                                  | 172       | 0.75%   |
| Intel Wi-Fi 6 AX201                                                     | 164       | 0.71%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 164       | 0.71%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 159       | 0.69%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 155       | 0.67%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 144       | 0.62%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 139       | 0.6%    |
| Intel Centrino Ultimate-N 6300                                          | 134       | 0.58%   |
| Intel Wireless 3160                                                     | 133       | 0.58%   |
| Intel 82577LM Gigabit Network Connection                                | 133       | 0.58%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 130       | 0.56%   |
| Intel Ethernet Connection I217-V                                        | 126       | 0.55%   |
| Intel WiFi Link 5100                                                    | 120       | 0.52%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 119       | 0.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 119       | 0.52%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 118       | 0.51%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 114       | 0.49%   |
| Intel Ethernet Connection (7) I219-V                                    | 112       | 0.49%   |
| Intel 82567LM Gigabit Network Connection                                | 110       | 0.48%   |
| Intel Ethernet Connection (4) I219-V                                    | 106       | 0.46%   |
| Broadcom BCM43142 802.11b/g/n                                           | 105       | 0.46%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 97        | 0.42%   |
| Intel Centrino Advanced-N 6200                                          | 97        | 0.42%   |
| Intel I210 Gigabit Network Connection                                   | 96        | 0.42%   |
| Intel Ethernet Connection I219-LM                                       | 96        | 0.42%   |
| Intel Centrino Wireless-N 2230                                          | 95        | 0.41%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 93        | 0.4%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 93        | 0.4%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 92        | 0.4%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 90        | 0.39%   |
| Intel Ethernet Connection I218-LM                                       | 90        | 0.39%   |
| Intel Ethernet Connection (6) I219-V                                    | 90        | 0.39%   |
| Intel Ethernet Connection (2) I219-LM                                   | 90        | 0.39%   |
| Nvidia MCP61 Ethernet                                                   | 89        | 0.39%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 86        | 0.37%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 85        | 0.37%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 83        | 0.36%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 82        | 0.36%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 4677      | 47.84%  |
| Qualcomm Atheros                      | 1623      | 16.6%   |
| Realtek Semiconductor                 | 1461      | 14.94%  |
| Broadcom                              | 637       | 6.52%   |
| Ralink Technology                     | 167       | 1.71%   |
| Ralink                                | 142       | 1.45%   |
| TP-Link                               | 129       | 1.32%   |
| Sierra Wireless                       | 107       | 1.09%   |
| Broadcom Limited                      | 98        | 1%      |
| AVM                                   | 86        | 0.88%   |
| Microsoft                             | 81        | 0.83%   |
| Edimax Technology                     | 62        | 0.63%   |
| MEDIATEK                              | 58        | 0.59%   |
| Dell                                  | 52        | 0.53%   |
| IMC Networks                          | 47        | 0.48%   |
| ASUSTek Computer                      | 46        | 0.47%   |
| D-Link System                         | 44        | 0.45%   |
| Qualcomm Atheros Communications       | 40        | 0.41%   |
| D-Link                                | 32        | 0.33%   |
| Netgear                               | 28        | 0.29%   |
| Marvell Technology Group              | 27        | 0.28%   |
| Fibocom                               | 23        | 0.24%   |
| Belkin Components                     | 20        | 0.2%    |
| Sitecom Europe                        | 17        | 0.17%   |
| Hewlett-Packard                       | 12        | 0.12%   |
| ZyXEL Communications                  | 8         | 0.08%   |
| ZyDAS                                 | 8         | 0.08%   |
| Qualcomm                              | 7         | 0.07%   |
| Linksys                               | 5         | 0.05%   |
| Wacom                                 | 4         | 0.04%   |
| Samsung Electronics                   | 3         | 0.03%   |
| Fujitsu Siemens Computers             | 3         | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.03%   |
| Winbond Electronics                   | 2         | 0.02%   |
| Texas Instruments                     | 2         | 0.02%   |
| Micro Star International              | 2         | 0.02%   |
| Lenovo                                | 2         | 0.02%   |
| Gemtek                                | 2         | 0.02%   |
| Wilocity                              | 1         | 0.01%   |
| Quectel Wireless Solutions            | 1         | 0.01%   |
| Qcom                                  | 1         | 0.01%   |
| PLANEX                                | 1         | 0.01%   |
| Philips (or NXP)                      | 1         | 0.01%   |
| Intersil                              | 1         | 0.01%   |
| Fiberline                             | 1         | 0.01%   |
| BUFFALO                               | 1         | 0.01%   |
| Acer NeWeb                            | 1         | 0.01%   |
| Accton Technology                     | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 567       | 5.75%   |
| Intel Wireless 8265 / 8275                                              | 380       | 3.86%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 345       | 3.5%    |
| Intel Wireless 7260                                                     | 322       | 3.27%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 313       | 3.18%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 266       | 2.7%    |
| Intel Wireless 8260                                                     | 247       | 2.51%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 240       | 2.44%   |
| Intel Wireless 7265                                                     | 232       | 2.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 205       | 2.08%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 187       | 1.9%    |
| Intel Wireless 3165                                                     | 186       | 1.89%   |
| Intel Wireless-AC 9260                                                  | 172       | 1.75%   |
| Intel Wi-Fi 6 AX201                                                     | 164       | 1.66%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 164       | 1.66%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 159       | 1.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 155       | 1.57%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 144       | 1.46%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 139       | 1.41%   |
| Intel Centrino Ultimate-N 6300                                          | 134       | 1.36%   |
| Intel Wireless 3160                                                     | 133       | 1.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 130       | 1.32%   |
| Intel WiFi Link 5100                                                    | 120       | 1.22%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 119       | 1.21%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 119       | 1.21%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 118       | 1.2%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 114       | 1.16%   |
| Broadcom BCM43142 802.11b/g/n                                           | 105       | 1.07%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 97        | 0.98%   |
| Intel Centrino Advanced-N 6200                                          | 97        | 0.98%   |
| Intel Centrino Wireless-N 2230                                          | 95        | 0.96%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 93        | 0.94%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 90        | 0.91%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 86        | 0.87%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 85        | 0.86%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 83        | 0.84%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 82        | 0.83%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 80        | 0.81%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 74        | 0.75%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 73        | 0.74%   |
| Intel Centrino Advanced-N 6235                                          | 71        | 0.72%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 68        | 0.69%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 62        | 0.63%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 62        | 0.63%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 60        | 0.61%   |
| Intel Ultimate N WiFi Link 5300                                         | 59        | 0.6%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 55        | 0.56%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 52        | 0.53%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 52        | 0.53%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 51        | 0.52%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 48        | 0.49%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 47        | 0.48%   |
| Realtek 802.11ac NIC                                                    | 46        | 0.47%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 46        | 0.47%   |
| Sierra Wireless EM7455                                                  | 42        | 0.43%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 41        | 0.42%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 40        | 0.41%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 39        | 0.4%    |
| Broadcom BCM43224 802.11a/b/g/n                                         | 38        | 0.39%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 37        | 0.38%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 6175      | 49.38%  |
| Intel                                  | 3730      | 29.83%  |
| Qualcomm Atheros                       | 775       | 6.2%    |
| Broadcom                               | 583       | 4.66%   |
| Marvell Technology Group               | 248       | 1.98%   |
| Nvidia                                 | 240       | 1.92%   |
| Broadcom Limited                       | 124       | 0.99%   |
| Lenovo                                 | 76        | 0.61%   |
| ASIX Electronics                       | 74        | 0.59%   |
| DisplayLink                            | 57        | 0.46%   |
| Samsung Electronics                    | 44        | 0.35%   |
| Sierra Wireless                        | 35        | 0.28%   |
| VIA Technologies                       | 34        | 0.27%   |
| Aquantia                               | 34        | 0.27%   |
| JMicron Technology                     | 27        | 0.22%   |
| Huawei Technologies                    | 27        | 0.22%   |
| Silicon Integrated Systems [SiS]       | 17        | 0.14%   |
| Xiaomi                                 | 16        | 0.13%   |
| 3Com                                   | 15        | 0.12%   |
| Microchip Technology                   | 12        | 0.1%    |
| Mellanox Technologies                  | 11        | 0.09%   |
| Hewlett-Packard                        | 11        | 0.09%   |
| D-Link System                          | 11        | 0.09%   |
| Attansic Technology                    | 11        | 0.09%   |
| Apple                                  | 11        | 0.09%   |
| Google                                 | 7         | 0.06%   |
| Fibocom                                | 7         | 0.06%   |
| TP-Link                                | 6         | 0.05%   |
| Standard Microsystems                  | 6         | 0.05%   |
| HMD Global                             | 5         | 0.04%   |
| American Megatrends                    | 5         | 0.04%   |
| ADMtek                                 | 5         | 0.04%   |
| Microsoft                              | 4         | 0.03%   |
| ICS Advent                             | 4         | 0.03%   |
| ZTE WCDMA Technologies MSM             | 3         | 0.02%   |
| T & A Mobile Phones                    | 3         | 0.02%   |
| Qualcomm                               | 3         | 0.02%   |
| Netchip Technology                     | 3         | 0.02%   |
| IBM                                    | 3         | 0.02%   |
| Emulex                                 | 3         | 0.02%   |
| Davicom Semiconductor                  | 3         | 0.02%   |
| Chelsio Communications                 | 3         | 0.02%   |
| ULi Electronics                        | 2         | 0.02%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.02%   |
| OPPO Electronics                       | 2         | 0.02%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.02%   |
| National Semiconductor                 | 2         | 0.02%   |
| Foxconn / Hon Hai                      | 2         | 0.02%   |
| D-Link                                 | 2         | 0.02%   |
| Compal Electronics                     | 2         | 0.02%   |
| Belkin Components                      | 2         | 0.02%   |
| Total Phase                            | 1         | 0.01%   |
| SysKonnect                             | 1         | 0.01%   |
| Sundance Technology Inc / IC Plus      | 1         | 0.01%   |
| Research In Motion                     | 1         | 0.01%   |
| QNAP System                            | 1         | 0.01%   |
| QLogic                                 | 1         | 0.01%   |
| Pioneer DJ                             | 1         | 0.01%   |
| NetXen Incorporated                    | 1         | 0.01%   |
| Motorola BCS                           | 1         | 0.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 5071      | 39.74%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 654       | 5.12%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 514       | 4.03%   |
| Intel I211 Gigabit Network Connection                                          | 378       | 2.96%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 305       | 2.39%   |
| Intel Ethernet Connection (2) I219-V                                           | 229       | 1.79%   |
| Realtek RTL8125 2.5GbE Controller                                              | 199       | 1.56%   |
| Intel Ethernet Connection I217-LM                                              | 189       | 1.48%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 174       | 1.36%   |
| Intel 82579V Gigabit Network Connection                                        | 173       | 1.36%   |
| Intel 82577LM Gigabit Network Connection                                       | 133       | 1.04%   |
| Intel Ethernet Connection I217-V                                               | 126       | 0.99%   |
| Intel Ethernet Connection (7) I219-V                                           | 112       | 0.88%   |
| Intel 82567LM Gigabit Network Connection                                       | 110       | 0.86%   |
| Intel Ethernet Connection (4) I219-V                                           | 106       | 0.83%   |
| Intel I210 Gigabit Network Connection                                          | 96        | 0.75%   |
| Intel Ethernet Connection I219-LM                                              | 96        | 0.75%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 93        | 0.73%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 92        | 0.72%   |
| Intel Ethernet Connection I218-LM                                              | 90        | 0.71%   |
| Intel Ethernet Connection (6) I219-V                                           | 90        | 0.71%   |
| Intel Ethernet Connection (2) I219-LM                                          | 90        | 0.71%   |
| Nvidia MCP61 Ethernet                                                          | 89        | 0.7%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 78        | 0.61%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 78        | 0.61%   |
| Intel Ethernet Connection (3) I218-LM                                          | 77        | 0.6%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 76        | 0.6%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 75        | 0.59%   |
| Intel Ethernet Controller I225-V                                               | 69        | 0.54%   |
| Intel Ethernet Connection (7) I219-LM                                          | 67        | 0.52%   |
| Intel Ethernet Connection (2) I218-V                                           | 65        | 0.51%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 63        | 0.49%   |
| Intel Ethernet Connection (4) I219-LM                                          | 62        | 0.49%   |
| Intel 82574L Gigabit Network Connection                                        | 60        | 0.47%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 59        | 0.46%   |
| Intel Ethernet Connection (10) I219-V                                          | 55        | 0.43%   |
| Intel Ethernet Connection I219-V                                               | 53        | 0.42%   |
| Nvidia MCP79 Ethernet                                                          | 49        | 0.38%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 48        | 0.38%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 47        | 0.37%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 46        | 0.36%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 44        | 0.34%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 43        | 0.34%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 42        | 0.33%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 42        | 0.33%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 41        | 0.32%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 40        | 0.31%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 38        | 0.3%    |
| Intel 82566MM Gigabit Network Connection                                       | 37        | 0.29%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 36        | 0.28%   |
| Sierra Wireless EM7345 4G LTE                                                  | 35        | 0.27%   |
| Intel Ethernet Connection (5) I219-LM                                          | 34        | 0.27%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 33        | 0.26%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 31        | 0.24%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 31        | 0.24%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 31        | 0.24%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 30        | 0.24%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]              | 30        | 0.24%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 28        | 0.22%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                              | 27        | 0.21%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 11849     | 55.17%  |
| WiFi     | 9206      | 42.86%  |
| Modem    | 393       | 1.83%   |
| Unknown  | 29        | 0.14%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 8560      | 53.46%  |
| WiFi     | 7408      | 46.27%  |
| Modem    | 39        | 0.24%   |
| Unknown  | 5         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 7106      | 53.55%  |
| 1     | 5563      | 41.92%  |
| 0     | 285       | 2.15%   |
| 3     | 239       | 1.8%    |
| 4     | 47        | 0.35%   |
| 6     | 11        | 0.08%   |
| 5     | 7         | 0.05%   |
| 8     | 6         | 0.05%   |
| 18    | 2         | 0.02%   |
| 10    | 2         | 0.02%   |
| 7     | 2         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 10099     | 74.08%  |
| Yes  | 3533      | 25.92%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 3253      | 46.64%  |
| Realtek Semiconductor           | 706       | 10.12%  |
| Cambridge Silicon Radio         | 574       | 8.23%   |
| Broadcom                        | 496       | 7.11%   |
| Qualcomm Atheros Communications | 384       | 5.51%   |
| Lite-On Technology              | 274       | 3.93%   |
| Foxconn / Hon Hai               | 225       | 3.23%   |
| Apple                           | 214       | 3.07%   |
| IMC Networks                    | 176       | 2.52%   |
| Dell                            | 137       | 1.96%   |
| ASUSTek Computer                | 121       | 1.73%   |
| Hewlett-Packard                 | 75        | 1.08%   |
| Toshiba                         | 57        | 0.82%   |
| Foxconn International           | 32        | 0.46%   |
| Realtek                         | 29        | 0.42%   |
| Alps Electric                   | 26        | 0.37%   |
| Marvell Semiconductor           | 24        | 0.34%   |
| Askey Computer                  | 23        | 0.33%   |
| Ralink                          | 22        | 0.32%   |
| Belkin Components               | 19        | 0.27%   |
| Integrated System Solution      | 18        | 0.26%   |
| Taiyo Yuden                     | 15        | 0.22%   |
| MediaTek                        | 10        | 0.14%   |
| Chicony Electronics             | 10        | 0.14%   |
| Qcom                            | 9         | 0.13%   |
| Ralink Technology               | 8         | 0.11%   |
| Edimax Technology               | 7         | 0.1%    |
| Logitech                        | 6         | 0.09%   |
| HTC (High Tech Computer)        | 4         | 0.06%   |
| TP-Link                         | 3         | 0.04%   |
| Micro Star International        | 3         | 0.04%   |
| Fujitsu                         | 3         | 0.04%   |
| Conwise Technology              | 2         | 0.03%   |
| USI                             | 1         | 0.01%   |
| Syntek                          | 1         | 0.01%   |
| Sitecom Europe                  | 1         | 0.01%   |
| SINO WEALTH                     | 1         | 0.01%   |
| National Semiconductor          | 1         | 0.01%   |
| Motorola PCS                    | 1         | 0.01%   |
| i.Tech Dynamic Limited          | 1         | 0.01%   |
| Fujitsu Siemens Computers       | 1         | 0.01%   |
| D-Link System                   | 1         | 0.01%   |
| AVM                             | 1         | 0.01%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 1393      | 19.96%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 573       | 8.21%   |
| Intel AX200 Bluetooth                                                               | 521       | 7.47%   |
| Realtek Bluetooth Radio                                                             | 426       | 6.1%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 401       | 5.75%   |
| Intel AX201 Bluetooth                                                               | 399       | 5.72%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 166       | 2.38%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 160       | 2.29%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 148       | 2.12%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 141       | 2.02%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 129       | 1.85%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 103       | 1.48%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 101       | 1.45%   |
| Lite-On Bluetooth Device                                                            | 95        | 1.36%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 90        | 1.29%   |
| Apple Bluetooth Host Controller                                                     | 82        | 1.17%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 81        | 1.16%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 73        | 1.05%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 71        | 1.02%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 65        | 0.93%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 58        | 0.83%   |
| IMC Networks Bluetooth Radio                                                        | 58        | 0.83%   |
| Dell DW375 Bluetooth Module                                                         | 58        | 0.83%   |
| IMC Networks Bluetooth Device                                                       | 57        | 0.82%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 57        | 0.82%   |
| Intel Bluetooth Device                                                              | 53        | 0.76%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 51        | 0.73%   |
| Realtek 802.11n WLAN Adapter                                                        | 50        | 0.72%   |
| Apple Bluetooth USB Host Controller                                                 | 50        | 0.72%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 47        | 0.67%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 44        | 0.63%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 41        | 0.59%   |
| Realtek RTL8723B Bluetooth                                                          | 39        | 0.56%   |
| Intel AX210 Bluetooth                                                               | 38        | 0.54%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 38        | 0.54%   |
| Broadcom BCM2045 Bluetooth                                                          | 36        | 0.52%   |
| Apple Bluetooth HCI                                                                 | 34        | 0.49%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 32        | 0.46%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 32        | 0.46%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 31        | 0.44%   |
| Realtek Bluetooth Radio                                                             | 29        | 0.42%   |
| Broadcom HP Portable SoftSailing                                                    | 27        | 0.39%   |
| Realtek RTL8821A Bluetooth                                                          | 24        | 0.34%   |
| Askey Bluetooth Device                                                              | 23        | 0.33%   |
| Ralink RT3290 Bluetooth                                                             | 22        | 0.32%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 19        | 0.27%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 19        | 0.27%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 17        | 0.24%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 17        | 0.24%   |
| ASUS Bluetooth Radio                                                                | 17        | 0.24%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 16        | 0.23%   |
| Marvell Bluetooth and Wireless LAN Composite                                        | 14        | 0.2%    |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                               | 14        | 0.2%    |
| Toshiba RT Bluetooth Radio                                                          | 13        | 0.19%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 13        | 0.19%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 13        | 0.19%   |
| Broadcom HP Portable Bumble Bee                                                     | 13        | 0.19%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 13        | 0.19%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 13        | 0.19%   |
| Toshiba Integrated Bluetooth HCI                                                    | 12        | 0.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 8983      | 49.5%   |
| AMD                              | 4187      | 23.07%  |
| Nvidia                           | 3022      | 16.65%  |
| C-Media Electronics              | 335       | 1.85%   |
| Creative Labs                    | 166       | 0.91%   |
| Logitech                         | 150       | 0.83%   |
| GN Netcom                        | 102       | 0.56%   |
| Texas Instruments                | 90        | 0.5%    |
| Lenovo                           | 77        | 0.42%   |
| Realtek Semiconductor            | 72        | 0.4%    |
| Plantronics                      | 58        | 0.32%   |
| VIA Technologies                 | 54        | 0.3%    |
| Creative Technology              | 54        | 0.3%    |
| Sennheiser Communications        | 50        | 0.28%   |
| Focusrite-Novation               | 49        | 0.27%   |
| JMTek                            | 47        | 0.26%   |
| Kingston Technology              | 46        | 0.25%   |
| Razer USA                        | 27        | 0.15%   |
| Yamaha                           | 26        | 0.14%   |
| Silicon Integrated Systems [SiS] | 24        | 0.13%   |
| Generalplus Technology           | 23        | 0.13%   |
| SteelSeries ApS                  | 22        | 0.12%   |
| Samson Technologies              | 22        | 0.12%   |
| Corsair                          | 22        | 0.12%   |
| RODE Microphones                 | 21        | 0.12%   |
| BEHRINGER International          | 19        | 0.1%    |
| ASUSTek Computer                 | 18        | 0.1%    |
| TerraTec Electronic              | 17        | 0.09%   |
| Hewlett-Packard                  | 16        | 0.09%   |
| M-Audio                          | 15        | 0.08%   |
| Dell                             | 14        | 0.08%   |
| GYROCOM C&C                      | 13        | 0.07%   |
| Native Instruments               | 11        | 0.06%   |
| Conexant Systems                 | 10        | 0.06%   |
| Blue Microphones                 | 9         | 0.05%   |
| AKAI Professional M.I.           | 9         | 0.05%   |
| XMOS                             | 8         | 0.04%   |
| Valve Software                   | 8         | 0.04%   |
| ROCCAT                           | 8         | 0.04%   |
| Microsoft                        | 8         | 0.04%   |
| Cambridge Silicon Radio          | 8         | 0.04%   |
| Apple                            | 8         | 0.04%   |
| SAVITECH                         | 7         | 0.04%   |
| USB MICROPHONE                   | 6         | 0.03%   |
| Tenx Technology                  | 6         | 0.03%   |
| Trust                            | 5         | 0.03%   |
| Sony                             | 5         | 0.03%   |
| No brand                         | 5         | 0.03%   |
| Guillemot                        | 5         | 0.03%   |
| ESS Technology                   | 5         | 0.03%   |
| Bose                             | 5         | 0.03%   |
| ATI Technologies                 | 5         | 0.03%   |
| ZOOM                             | 4         | 0.02%   |
| Unknown                          | 4         | 0.02%   |
| QinHeng Electronics              | 4         | 0.02%   |
| Arturia                          | 4         | 0.02%   |
| Alesis                           | 4         | 0.02%   |
| Xilinx                           | 3         | 0.02%   |
| ULi Electronics                  | 3         | 0.02%   |
| Turtle Beach                     | 3         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 998       | 4.61%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 941       | 4.35%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 928       | 4.29%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 880       | 4.07%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 783       | 3.62%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 640       | 2.96%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 565       | 2.61%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 563       | 2.6%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 496       | 2.29%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 481       | 2.22%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 434       | 2.01%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 431       | 1.99%   |
| AMD FCH Azalia Controller                                                                         | 430       | 1.99%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 422       | 1.95%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 404       | 1.87%   |
| Intel Cannon Lake PCH cAVS                                                                        | 389       | 1.8%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 362       | 1.67%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 305       | 1.41%   |
| Intel 8 Series HD Audio Controller                                                                | 303       | 1.4%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 284       | 1.31%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 273       | 1.26%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 258       | 1.19%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 237       | 1.1%    |
| Intel Broadwell-U Audio Controller                                                                | 226       | 1.04%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 224       | 1.04%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 224       | 1.04%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 221       | 1.02%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 219       | 1.01%   |
| Intel 200 Series PCH HD Audio                                                                     | 212       | 0.98%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 196       | 0.91%   |
| Nvidia High Definition Audio Controller                                                           | 183       | 0.85%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 178       | 0.82%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 176       | 0.81%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 175       | 0.81%   |
| AMD Kabini HDMI/DP Audio                                                                          | 172       | 0.8%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 167       | 0.77%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 154       | 0.71%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 148       | 0.68%   |
| AMD Navi 10 HDMI Audio                                                                            | 143       | 0.66%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 142       | 0.66%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 139       | 0.64%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 136       | 0.63%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 135       | 0.62%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 134       | 0.62%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 128       | 0.59%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 128       | 0.59%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 127       | 0.59%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 123       | 0.57%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 119       | 0.55%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 114       | 0.53%   |
| Intel Comet Lake PCH cAVS                                                                         | 114       | 0.53%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 114       | 0.53%   |
| AMD Trinity HDMI Audio Controller                                                                 | 110       | 0.51%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 108       | 0.5%    |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 108       | 0.5%    |
| Intel CM238 HD Audio Controller                                                                   | 100       | 0.46%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 100       | 0.46%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 95        | 0.44%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 92        | 0.43%   |
| Nvidia MCP61 High Definition Audio                                                                | 91        | 0.42%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 1635      | 23.21%  |
| SK Hynix                                         | 1144      | 16.24%  |
| Unknown                                          | 810       | 11.5%   |
| Kingston                                         | 697       | 9.9%    |
| Micron Technology                                | 606       | 8.6%    |
| Crucial                                          | 521       | 7.4%    |
| G.Skill                                          | 435       | 6.18%   |
| Corsair                                          | 386       | 5.48%   |
| Ramaxel Technology                               | 135       | 1.92%   |
| Elpida                                           | 112       | 1.59%   |
| Nanya Technology                                 | 104       | 1.48%   |
| A-DATA Technology                                | 100       | 1.42%   |
| Unknown (ABCD)                                   | 84        | 1.19%   |
| Team                                             | 35        | 0.5%    |
| Transcend                                        | 26        | 0.37%   |
| Patriot                                          | 22        | 0.31%   |
| Unknown                                          | 22        | 0.31%   |
| GeIL                                             | 12        | 0.17%   |
| Avant                                            | 12        | 0.17%   |
| ASint Technology                                 | 12        | 0.17%   |
| 48spaces                                         | 12        | 0.17%   |
| GOODRAM                                          | 11        | 0.16%   |
| Unifosa                                          | 9         | 0.13%   |
| Toshiba                                          | 7         | 0.1%    |
| CSX                                              | 7         | 0.1%    |
| Qimonda                                          | 5         | 0.07%   |
| Lexar                                            | 5         | 0.07%   |
| Apacer                                           | 5         | 0.07%   |
| Aeneon                                           | 4         | 0.06%   |
| SHARETRONIC                                      | 3         | 0.04%   |
| PNY                                              | 3         | 0.04%   |
| Mushkin                                          | 3         | 0.04%   |
| Hewlett-Packard                                  | 3         | 0.04%   |
| Unknown (AB)                                     | 2         | 0.03%   |
| TIMETEC                                          | 2         | 0.03%   |
| Swissbit                                         | 2         | 0.03%   |
| Silicon Power                                    | 2         | 0.03%   |
| S                                                | 2         | 0.03%   |
| Patriot Memory                                   | 2         | 0.03%   |
| MCI Computer                                     | 2         | 0.03%   |
| Golden Empire                                    | 2         | 0.03%   |
| Exceleram                                        | 2         | 0.03%   |
| ATP                                              | 2         | 0.03%   |
| ZIFEI                                            | 1         | 0.01%   |
| V-Color                                          | 1         | 0.01%   |
| Unknown (0x8551)                                 | 1         | 0.01%   |
| Unknown (0x5D00000000000000)                     | 1         | 0.01%   |
| Unknown (0x4D342037305435363633515A332D43463720) | 1         | 0.01%   |
| Unknown (0x36345431323830323045444C322E35433220) | 1         | 0.01%   |
| Unknown (0x29E)                                  | 1         | 0.01%   |
| Unknown (0x198)                                  | 1         | 0.01%   |
| Unknown (09C7)                                   | 1         | 0.01%   |
| TECMAR                                           | 1         | 0.01%   |
| TeamGroup                                        | 1         | 0.01%   |
| TakeMS                                           | 1         | 0.01%   |
| Smart                                            | 1         | 0.01%   |
| SGS/Thomson                                      | 1         | 0.01%   |
| Sesame                                           | 1         | 0.01%   |
| ProMos/Mosel Vitelic                             | 1         | 0.01%   |
| Pioneer                                          | 1         | 0.01%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 64        | 0.85%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 64        | 0.85%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s              | 61        | 0.81%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 59        | 0.78%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 55        | 0.73%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s            | 54        | 0.71%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 48        | 0.63%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 46        | 0.61%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 44        | 0.58%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 42        | 0.55%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 41        | 0.54%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 41        | 0.54%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 41        | 0.54%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s            | 39        | 0.52%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 38        | 0.5%    |
| Unknown RAM Module 4096MB DIMM 1333MT/s                             | 37        | 0.49%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 36        | 0.48%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 36        | 0.48%   |
| G.Skill RAM F4-3200C16-8GVKB 8192MB DIMM DDR4 3200MT/s              | 36        | 0.48%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s            | 34        | 0.45%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s               | 34        | 0.45%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 33        | 0.44%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 33        | 0.44%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s                | 32        | 0.42%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 30        | 0.4%    |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s            | 29        | 0.38%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8192MB SODIMM DDR4 2667MT/s             | 28        | 0.37%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 27        | 0.36%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 26        | 0.34%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s              | 26        | 0.34%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s                  | 26        | 0.34%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                             | 25        | 0.33%   |
| Unknown (ABCD) RAM 123456789012345678 8GB DIMM DDR4 2400MT/s        | 25        | 0.33%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s               | 25        | 0.33%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 25        | 0.33%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s              | 25        | 0.33%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 24        | 0.32%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                       | 22        | 0.29%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s              | 22        | 0.29%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s              | 22        | 0.29%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 22        | 0.29%   |
| Unknown                                                             | 22        | 0.29%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s          | 21        | 0.28%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s              | 20        | 0.26%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 19        | 0.25%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 19        | 0.25%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 19        | 0.25%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s               | 19        | 0.25%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 19        | 0.25%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s             | 19        | 0.25%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 18        | 0.24%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 18        | 0.24%   |
| Samsung RAM U6E3S4AA-MGCR 1GB Row Of Chips LPDDR4 4267MT/s          | 18        | 0.24%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s              | 18        | 0.24%   |
| Micron RAM 16KTF51264HZ-1G6M1 4096MB SODIMM DDR3 1600MT/s           | 18        | 0.24%   |
| Corsair RAM CMX8GX3M2A1333C9 4096MB DIMM DDR3 1333MT/s              | 18        | 0.24%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                                | 17        | 0.22%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 17        | 0.22%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s               | 17        | 0.22%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1866MT/s                 | 17        | 0.22%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 2785      | 44.54%  |
| DDR3    | 2273      | 36.35%  |
| DDR2    | 325       | 5.2%    |
| Unknown | 242       | 3.87%   |
| LPDDR4  | 221       | 3.53%   |
| SDRAM   | 191       | 3.05%   |
| LPDDR3  | 145       | 2.32%   |
| DDR     | 52        | 0.83%   |
| DRAM    | 19        | 0.3%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| SODIMM          | 3407      | 54.77%  |
| DIMM            | 2422      | 38.93%  |
| Row Of Chips    | 329       | 5.29%   |
| Chip            | 42        | 0.68%   |
| FB-DIMM         | 9         | 0.14%   |
| RIMM            | 7         | 0.11%   |
| Unknown         | 4         | 0.06%   |
| Proprietary Car | 1         | 0.02%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size   | Computers | Percent |
|--------|-----------|---------|
| 8192   | 2479      | 37.13%  |
| 4096   | 1972      | 29.53%  |
| 2048   | 918       | 13.75%  |
| 16384  | 878       | 13.15%  |
| 1024   | 232       | 3.47%   |
| 32768  | 155       | 2.32%   |
| 512    | 32        | 0.48%   |
| 256    | 4         | 0.06%   |
| 128    | 4         | 0.06%   |
| 65536  | 2         | 0.03%   |
| 129408 | 1         | 0.01%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 1436      | 21.28%  |
| 2667    | 983       | 14.57%  |
| 3200    | 808       | 11.98%  |
| 1333    | 559       | 8.29%   |
| 2400    | 506       | 7.5%    |
| 2133    | 342       | 5.07%   |
| 1334    | 253       | 3.75%   |
| 667     | 179       | 2.65%   |
| Unknown | 171       | 2.53%   |
| 800     | 170       | 2.52%   |
| 3600    | 169       | 2.5%    |
| 1067    | 113       | 1.67%   |
| 1867    | 107       | 1.59%   |
| 4267    | 83        | 1.23%   |
| 1066    | 72        | 1.07%   |
| 3000    | 65        | 0.96%   |
| 1866    | 63        | 0.93%   |
| 3266    | 62        | 0.92%   |
| 3466    | 60        | 0.89%   |
| 2666    | 51        | 0.76%   |
| 4199    | 45        | 0.67%   |
| 2933    | 45        | 0.67%   |
| 3733    | 34        | 0.5%    |
| 2048    | 32        | 0.47%   |
| 1800    | 28        | 0.41%   |
| 400     | 27        | 0.4%    |
| 533     | 26        | 0.39%   |
| 3800    | 22        | 0.33%   |
| 975     | 22        | 0.33%   |
| 4266    | 17        | 0.25%   |
| 333     | 15        | 0.22%   |
| 3533    | 14        | 0.21%   |
| 3400    | 14        | 0.21%   |
| 2800    | 14        | 0.21%   |
| 1400    | 14        | 0.21%   |
| 3500    | 12        | 0.18%   |
| 4000    | 9         | 0.13%   |
| 1639    | 9         | 0.13%   |
| 2465    | 8         | 0.12%   |
| 3100    | 7         | 0.1%    |
| 2000    | 7         | 0.1%    |
| 3334    | 6         | 0.09%   |
| 2200    | 6         | 0.09%   |
| 4800    | 5         | 0.07%   |
| 3666    | 5         | 0.07%   |
| 3066    | 5         | 0.07%   |
| 2747    | 3         | 0.04%   |
| 2733    | 3         | 0.04%   |
| 2267    | 3         | 0.04%   |
| 200     | 3         | 0.04%   |
| 4333    | 2         | 0.03%   |
| 4133    | 2         | 0.03%   |
| 3333    | 2         | 0.03%   |
| 3067    | 2         | 0.03%   |
| 2134    | 2         | 0.03%   |
| 1777    | 2         | 0.03%   |
| 933     | 2         | 0.03%   |
| 266     | 2         | 0.03%   |
| 133     | 2         | 0.03%   |
| 65535   | 1         | 0.01%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Hewlett-Packard          | 164       | 30.89%  |
| Canon                    | 97        | 18.27%  |
| Brother Industries       | 92        | 17.33%  |
| Samsung Electronics      | 69        | 12.99%  |
| Seiko Epson              | 33        | 6.21%   |
| Kyocera                  | 19        | 3.58%   |
| Prolific Technology      | 15        | 2.82%   |
| Lexmark International    | 9         | 1.69%   |
| Dymo-CoStar              | 9         | 1.69%   |
| QinHeng Electronics      | 8         | 1.51%   |
| Dell                     | 3         | 0.56%   |
| Xerox                    | 2         | 0.38%   |
| Oki Data                 | 2         | 0.38%   |
| Magic Control Technology | 2         | 0.38%   |
| STMicroelectronics       | 1         | 0.19%   |
| Seiko Instruments        | 1         | 0.19%   |
| Ricoh                    | 1         | 0.19%   |
| MIIIW                    | 1         | 0.19%   |
| ATEN International       | 1         | 0.19%   |
| Agere Systems (Lucent)   | 1         | 0.19%   |
| Unknown                  | 1         | 0.19%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port                              | 15        | 2.81%   |
| Samsung M2020 Series                                       | 13        | 2.43%   |
| Brother HL-2030 Laser Printer                              | 11        | 2.06%   |
| HP ENVY 4520 series                                        | 9         | 1.69%   |
| QinHeng CH340S                                             | 8         | 1.5%    |
| Canon PIXMA MX920 Series                                   | 8         | 1.5%    |
| Canon iP7200 series                                        | 8         | 1.5%    |
| Canon PIXMA MG3600 Series                                  | 7         | 1.31%   |
| HP Deskjet 2540 series                                     | 6         | 1.12%   |
| Canon CanoScan LiDE 300                                    | 6         | 1.12%   |
| Samsung ML-1640 Series Laser Printer                       | 5         | 0.94%   |
| Samsung C48x Series Color Laser Multifunction Printer      | 5         | 0.94%   |
| HP ENVY 4500 series                                        | 5         | 0.94%   |
| HP DeskJet F4200 series                                    | 5         | 0.94%   |
| HP DeskJet 2600 series                                     | 5         | 0.94%   |
| Samsung SCX-472x Series                                    | 4         | 0.75%   |
| Samsung M283x Series                                       | 4         | 0.75%   |
| Samsung M2070 Series                                       | 4         | 0.75%   |
| HP Officejet Pro 8100                                      | 4         | 0.75%   |
| HP Officejet 4620 series                                   | 4         | 0.75%   |
| HP Officejet 2620 series                                   | 4         | 0.75%   |
| HP DeskJet 3700 series                                     | 4         | 0.75%   |
| Canon PIXMA MG2500 Series                                  | 4         | 0.75%   |
| Canon Pixma iP4500 Printer                                 | 4         | 0.75%   |
| Brother MFC-L3750CDW                                       | 4         | 0.75%   |
| Brother MFC-L2710DW series                                 | 4         | 0.75%   |
| Brother HL-3142CW series                                   | 4         | 0.75%   |
| Seiko Epson XP-4100 Series                                 | 3         | 0.56%   |
| Seiko Epson XP-2100 Series                                 | 3         | 0.56%   |
| Seiko Epson WF-2530 Series                                 | 3         | 0.56%   |
| Seiko Epson ET-2710 Series                                 | 3         | 0.56%   |
| Samsung CLX-3300 Series                                    | 3         | 0.56%   |
| Samsung CLX-3180 Series                                    | 3         | 0.56%   |
| Kyocera Mita FS-820                                        | 3         | 0.56%   |
| Kyocera FS-1030D printer                                   | 3         | 0.56%   |
| HP OfficeJet 5200 series                                   | 3         | 0.56%   |
| HP OfficeJet 4650 series                                   | 3         | 0.56%   |
| HP OfficeJet 3830 series                                   | 3         | 0.56%   |
| HP LaserJet 1018                                           | 3         | 0.56%   |
| HP Deskjet 3520 series                                     | 3         | 0.56%   |
| HP DeskJet 2700 series                                     | 3         | 0.56%   |
| HP Deskjet 1050 J410                                       | 3         | 0.56%   |
| Canon TS700 series                                         | 3         | 0.56%   |
| Canon TS5100 series                                        | 3         | 0.56%   |
| Canon TR4500 series                                        | 3         | 0.56%   |
| Canon PIXMA MX720 Series                                   | 3         | 0.56%   |
| Canon LiDE 400                                             | 3         | 0.56%   |
| Brother MFC-J470DW                                         | 3         | 0.56%   |
| Brother MFC-7320                                           | 3         | 0.56%   |
| Brother HL-L3210CW series                                  | 3         | 0.56%   |
| Brother HL-52x0 series                                     | 3         | 0.56%   |
| Brother HL-2250DN Laser Printer                            | 3         | 0.56%   |
| Brother HL-2140 series                                     | 3         | 0.56%   |
| Brother DCP-7030                                           | 3         | 0.56%   |
| Seiko Epson XP-7100 Series                                 | 2         | 0.37%   |
| Seiko Epson Printer                                        | 2         | 0.37%   |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F     | 2         | 0.37%   |
| Seiko Epson ET-4750 [WorkForce ET-4750 EcoTank All-in-One] | 2         | 0.37%   |
| Samsung SCX-3400 Series                                    | 2         | 0.37%   |
| Samsung SCX-3200 Series                                    | 2         | 0.37%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Canon                  | 136       | 69.74%  |
| Seiko Epson            | 33        | 16.92%  |
| Hewlett-Packard        | 12        | 6.15%   |
| AGFA-Gevaert NV        | 6         | 3.08%   |
| Mustek Systems         | 5         | 2.56%   |
| Plustek                | 1         | 0.51%   |
| Nikon                  | 1         | 0.51%   |
| Microtek International | 1         | 0.51%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 210                                       | 20        | 10.26%  |
| Canon CanoScan LiDE 220                                       | 19        | 9.74%   |
| Canon CanoScan LIDE 25                                        | 16        | 8.21%   |
| Canon CanoScan LiDE 110                                       | 16        | 8.21%   |
| Canon CanoScan N670U/N676U/LiDE 20                            | 12        | 6.15%   |
| Canon CanoScan LiDE 120                                       | 9         | 4.62%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]           | 7         | 3.59%   |
| Canon CanoScan LiDE 100                                       | 7         | 3.59%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                        | 6         | 3.08%   |
| Seiko Epson GT-X770 [Perfection V500]                         | 5         | 2.56%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                 | 5         | 2.56%   |
| Canon CanoScan LiDE 90                                        | 4         | 2.05%   |
| Canon CanoScan LiDE 60                                        | 4         | 2.05%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]      | 3         | 1.54%   |
| HP ScanJet 3970c                                              | 3         | 1.54%   |
| Canon CanoScan N1240U/LiDE 30                                 | 3         | 1.54%   |
| Canon CanoScan LiDE 600F                                      | 3         | 1.54%   |
| Canon CanoScan LiDE 500F                                      | 3         | 1.54%   |
| Canon CanoScan 9000F Mark II                                  | 3         | 1.54%   |
| Canon CanoScan 8800F                                          | 3         | 1.54%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]            | 2         | 1.03%   |
| Mustek Systems ScanExpress 1200 CU                            | 2         | 1.03%   |
| HP HP4470C                                                    | 2         | 1.03%   |
| Canon CanoScan LiDE 700F                                      | 2         | 1.03%   |
| Canon CanoScan LiDE 200                                       | 2         | 1.03%   |
| AGFA-Gevaert NV SnapScan 1212U (?)                            | 2         | 1.03%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                   | 1         | 0.51%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]       | 1         | 0.51%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo]       | 1         | 0.51%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]             | 1         | 0.51%   |
| Seiko Epson GT-9700F [Perfection 2450 PHOTO]                  | 1         | 0.51%   |
| Seiko Epson GT-9400UF [Perfection 3170]                       | 1         | 0.51%   |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1         | 0.51%   |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO]   | 1         | 0.51%   |
| Seiko Epson GT-7700U [Perfection 1240U]                       | 1         | 0.51%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]             | 1         | 0.51%   |
| Seiko Epson CC-570L [Stylus CX3100/CX3200]                    | 1         | 0.51%   |
| Plustek OpticPro UT12/16/24 Scanner                           | 1         | 0.51%   |
| Nikon Coolscan LS 40 ED                                       | 1         | 0.51%   |
| Mustek Systems SNAPSCAN e22                                   | 1         | 0.51%   |
| Mustek Systems ScanExpress A3 USB                             | 1         | 0.51%   |
| Mustek Systems ScanExpress 1200 CU Plus                       | 1         | 0.51%   |
| Microtek International USB1200 Scanner                        | 1         | 0.51%   |
| HP ScanJet Pro 2500 f1                                        | 1         | 0.51%   |
| HP ScanJet G3010                                              | 1         | 0.51%   |
| HP ScanJet 7650                                               | 1         | 0.51%   |
| HP ScanJet 5590                                               | 1         | 0.51%   |
| HP ScanJet 4370                                               | 1         | 0.51%   |
| HP ScanJet 3400cse                                            | 1         | 0.51%   |
| HP Scanjet 300                                                | 1         | 0.51%   |
| Canon CanoScan 8000F                                          | 1         | 0.51%   |
| Canon CanoScan 5200F                                          | 1         | 0.51%   |
| Canon CanoScan 4400F                                          | 1         | 0.51%   |
| Canon CanoScan 3200F                                          | 1         | 0.51%   |
| AGFA-Gevaert NV SnapScan Touch                                | 1         | 0.51%   |
| AGFA-Gevaert NV SnapScan e26                                  | 1         | 0.51%   |
| AGFA-Gevaert NV SnapScan e20                                  | 1         | 0.51%   |
| AGFA-Gevaert NV SnapScan 1212U                                | 1         | 0.51%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1888      | 26.3%   |
| IMC Networks                           | 560       | 7.8%    |
| Acer                                   | 542       | 7.55%   |
| Logitech                               | 496       | 6.91%   |
| Realtek Semiconductor                  | 473       | 6.59%   |
| Microdia                               | 472       | 6.57%   |
| Sunplus Innovation Technology          | 305       | 4.25%   |
| Quanta                                 | 273       | 3.8%    |
| Cheng Uei Precision Industry (Foxlink) | 249       | 3.47%   |
| Suyin                                  | 248       | 3.45%   |
| Apple                                  | 186       | 2.59%   |
| Lite-On Technology                     | 177       | 2.47%   |
| Syntek                                 | 154       | 2.15%   |
| Alcor Micro                            | 118       | 1.64%   |
| Microsoft                              | 115       | 1.6%    |
| Silicon Motion                         | 92        | 1.28%   |
| Ricoh                                  | 85        | 1.18%   |
| Lenovo                                 | 70        | 0.98%   |
| Z-Star Microelectronics                | 60        | 0.84%   |
| Samsung Electronics                    | 59        | 0.82%   |
| Luxvisions Innotech Limited            | 43        | 0.6%    |
| ALi                                    | 40        | 0.56%   |
| Generalplus Technology                 | 35        | 0.49%   |
| Creative Technology                    | 35        | 0.49%   |
| Primax Electronics                     | 27        | 0.38%   |
| Importek                               | 23        | 0.32%   |
| ARC International                      | 23        | 0.32%   |
| DigiTech                               | 21        | 0.29%   |
| Sunplus Technology                     | 17        | 0.24%   |
| Cubeternet                             | 16        | 0.22%   |
| Trust                                  | 13        | 0.18%   |
| Genesys Logic                          | 13        | 0.18%   |
| GEMBIRD                                | 13        | 0.18%   |
| webcam                                 | 10        | 0.14%   |
| Unknown                                | 10        | 0.14%   |
| Sonix Technology                       | 10        | 0.14%   |
| Intel                                  | 10        | 0.14%   |
| MacroSilicon                           | 9         | 0.13%   |
| Jieli Technology                       | 9         | 0.13%   |
| Valve Software                         | 8         | 0.11%   |
| OmniVision Technologies                | 8         | 0.11%   |
| eMPIA Technology                       | 8         | 0.11%   |
| KYE Systems (Mouse Systems)            | 7         | 0.1%    |
| Google                                 | 7         | 0.1%    |
| Arkmicro Technologies                  | 7         | 0.1%    |
| Philips (or NXP)                       | 6         | 0.08%   |
| Huawei Technologies                    | 6         | 0.08%   |
| DJJHFA1BIF5CB0                         | 6         | 0.08%   |
| SunplusIT                              | 5         | 0.07%   |
| Razer USA                              | 5         | 0.07%   |
| Guillemot                              | 5         | 0.07%   |
| Aveo Technology                        | 5         | 0.07%   |
| Alpha Imaging Technology               | 5         | 0.07%   |
| Y Media                                | 4         | 0.06%   |
| WaveRider Communications               | 4         | 0.06%   |
| SJ-180517-N                            | 4         | 0.06%   |
| Mimaki Engineering                     | 4         | 0.06%   |
| HTC (High Tech Computer)               | 4         | 0.06%   |
| Hewlett-Packard                        | 4         | 0.06%   |
| YGTek                                  | 3         | 0.04%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 361       | 4.99%   |
| Chicony HD Webcam                                | 220       | 3.04%   |
| IMC Networks Integrated Camera                   | 198       | 2.74%   |
| Acer Integrated Camera                           | 146       | 2.02%   |
| Microdia Integrated_Webcam_HD                    | 130       | 1.8%    |
| Realtek Integrated_Webcam_HD                     | 128       | 1.77%   |
| Logitech Webcam C270                             | 111       | 1.54%   |
| IMC Networks USB2.0 HD UVC WebCam                | 94        | 1.3%    |
| Chicony USB2.0 Camera                            | 93        | 1.29%   |
| Chicony FJ Camera                                | 92        | 1.27%   |
| Chicony USB 2.0 Camera                           | 80        | 1.11%   |
| Syntek Integrated Camera                         | 75        | 1.04%   |
| Sunplus Integrated_Webcam_HD                     | 75        | 1.04%   |
| Lite-On Integrated Camera                        | 72        | 1%      |
| Logitech HD Pro Webcam C920                      | 68        | 0.94%   |
| Apple Built-in iSight                            | 67        | 0.93%   |
| Acer Lenovo EasyCamera                           | 61        | 0.84%   |
| Samsung Galaxy A5 (MTP)                          | 58        | 0.8%    |
| Acer BisonCam, NB Pro                            | 58        | 0.8%    |
| Chicony Integrated Camera (1280x720@30)          | 57        | 0.79%   |
| Microdia Integrated Webcam                       | 55        | 0.76%   |
| Alcor Micro USB 2.0 Camera                       | 55        | 0.76%   |
| Microdia USB 2.0 Camera                          | 54        | 0.75%   |
| Microsoft LifeCam HD-3000                        | 52        | 0.72%   |
| Chicony HD User Facing                           | 52        | 0.72%   |
| Sunplus HD WebCam                                | 51        | 0.71%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 50        | 0.69%   |
| Quanta HD User Facing                            | 49        | 0.68%   |
| Chicony USB2.0 HD UVC WebCam                     | 49        | 0.68%   |
| Acer SunplusIT Integrated Camera                 | 49        | 0.68%   |
| Quanta HP Webcam                                 | 48        | 0.66%   |
| Chicony HP Webcam                                | 48        | 0.66%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 47        | 0.65%   |
| Chicony TOSHIBA Web Camera - HD                  | 46        | 0.64%   |
| Realtek USB Camera                               | 45        | 0.62%   |
| Chicony ThinkPad T490 Webcam                     | 42        | 0.58%   |
| Chicony HP HD Camera                             | 42        | 0.58%   |
| Suyin Acer/HP Integrated Webcam [CN0314]         | 39        | 0.54%   |
| Apple FaceTime HD Camera (Built-in)              | 39        | 0.54%   |
| Microdia Sonix USB 2.0 Camera                    | 38        | 0.53%   |
| Chicony VGA Webcam                               | 38        | 0.53%   |
| Chicony EasyCamera                               | 38        | 0.53%   |
| Apple iPhone 5/5C/5S/6/SE                        | 38        | 0.53%   |
| Logitech HD Webcam C525                          | 37        | 0.51%   |
| Chicony Lenovo Integrated Camera (0.3MP)         | 37        | 0.51%   |
| Chicony Lenovo EasyCamera                        | 37        | 0.51%   |
| Acer Lenovo Integrated Webcam                    | 36        | 0.5%    |
| Syntek Lenovo EasyCamera                         | 34        | 0.47%   |
| Realtek Lenovo EasyCamera                        | 34        | 0.47%   |
| Quanta HD Webcam                                 | 34        | 0.47%   |
| ALi Gateway Webcam                               | 33        | 0.46%   |
| Acer EasyCamera                                  | 33        | 0.46%   |
| Chicony HP TrueVision HD Camera                  | 32        | 0.44%   |
| Lite-On HP Webcam                                | 31        | 0.43%   |
| Quanta HP HD Camera                              | 30        | 0.41%   |
| Logitech C922 Pro Stream Webcam                  | 29        | 0.4%    |
| Chicony USB2.0 VGA UVC WebCam                    | 29        | 0.4%    |
| Cheng Uei Precision Industry (Foxlink) Webcam    | 29        | 0.4%    |
| Logitech Webcam C310                             | 28        | 0.39%   |
| IMC Networks USB2.0 UVC VGA WebCam               | 28        | 0.39%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 495       | 30.88%  |
| Synaptics                  | 434       | 27.07%  |
| Shenzhen Goodix Technology | 179       | 11.17%  |
| AuthenTec                  | 156       | 9.73%   |
| Upek                       | 120       | 7.49%   |
| LighTuning Technology      | 110       | 6.86%   |
| Elan Microelectronics      | 71        | 4.43%   |
| STMicroelectronics         | 31        | 1.93%   |
| HOLTEK                     | 4         | 0.25%   |
| Samsung Electronics        | 3         | 0.19%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 158       | 9.86%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 114       | 7.11%   |
| Unknown                                                                    | 98        | 6.11%   |
| Shenzhen Goodix  Fingerprint Device                                        | 88        | 5.49%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 82        | 5.12%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 81        | 5.05%   |
| Shenzhen Goodix Fingerprint Reader                                         | 61        | 3.81%   |
| Validity Sensors Synaptics WBDI                                            | 59        | 3.68%   |
| AuthenTec AES2810                                                          | 58        | 3.62%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 48        | 2.99%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 48        | 2.99%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 47        | 2.93%   |
| Elan ELAN:Fingerprint                                                      | 43        | 2.68%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 40        | 2.5%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 37        | 2.31%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 36        | 2.25%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 36        | 2.25%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 34        | 2.12%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 34        | 2.12%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 34        | 2.12%   |
| STMicroelectronics Fingerprint Reader                                      | 31        | 1.93%   |
| Shenzhen Goodix FingerPrint                                                | 30        | 1.87%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 28        | 1.75%   |
| Validity Sensors VFS491                                                    | 26        | 1.62%   |
| AuthenTec AES1600                                                          | 26        | 1.62%   |
| LighTuning Fingerprint Reader                                              | 24        | 1.5%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 21        | 1.31%   |
| AuthenTec Fingerprint Sensor                                               | 21        | 1.31%   |
| Synaptics  WBDI                                                            | 20        | 1.25%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 20        | 1.25%   |
| Elan ELAN:ARM-M4                                                           | 19        | 1.19%   |
| Validity Sensors Fingerprint scanner                                       | 15        | 0.94%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 13        | 0.81%   |
| Synaptics WBDI Device                                                      | 11        | 0.69%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 9         | 0.56%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 9         | 0.56%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 7         | 0.44%   |
| Validity Sensors VFS Fingerprint sensor                                    | 6         | 0.37%   |
| Upek TCS5B Fingerprint sensor                                              | 6         | 0.37%   |
| HOLTEK FocalTech Fingerprint Device                                        | 4         | 0.25%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 3         | 0.19%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 0.19%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 3         | 0.19%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 3         | 0.19%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 3         | 0.19%   |
| LighTuning Fingerprint Sensor                                              | 3         | 0.19%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 2         | 0.12%   |
| AuthenTec AES3500 TruePrint Sensor                                         | 1         | 0.06%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 340       | 36.6%   |
| Broadcom                  | 278       | 29.92%  |
| O2 Micro                  | 87        | 9.36%   |
| Lenovo                    | 85        | 9.15%   |
| Upek                      | 55        | 5.92%   |
| Reiner SCT Kartensysteme  | 18        | 1.94%   |
| Yubico.com                | 10        | 1.08%   |
| OmniKey                   | 8         | 0.86%   |
| Gemalto (was Gemplus)     | 8         | 0.86%   |
| SCM Microsystems          | 7         | 0.75%   |
| Clay Logic                | 7         | 0.75%   |
| Cherry                    | 6         | 0.65%   |
| Fujitsu Siemens Computers | 5         | 0.54%   |
| Kobil Systems             | 4         | 0.43%   |
| Realtek Semiconductor     | 2         | 0.22%   |
| In Focus Systems          | 2         | 0.22%   |
| Advanced Card Systems     | 2         | 0.22%   |
| Purism, SPC               | 1         | 0.11%   |
| NXP Semiconductors        | 1         | 0.11%   |
| Microchip Technology      | 1         | 0.11%   |
| Chicony Electronics       | 1         | 0.11%   |
| Aladdin Knowledge Systems | 1         | 0.11%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 338       | 36.38%  |
| Broadcom BCM5880 Secure Applications Processor                               | 120       | 12.92%  |
| Lenovo Integrated Smart Card Reader                                          | 84        | 9.04%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 76        | 8.18%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 62        | 6.67%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 55        | 5.92%   |
| Broadcom 5880                                                                | 54        | 5.81%   |
| Broadcom 58200                                                               | 38        | 4.09%   |
| O2 Micro Oz776 SmartCard Reader                                              | 11        | 1.18%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 7         | 0.75%   |
| Reiner SCT Kartensysteme cyberJack one                                       | 7         | 0.75%   |
| Clay Logic Nitrokey Pro                                                      | 7         | 0.75%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 6         | 0.65%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 5         | 0.54%   |
| OmniKey CardMan 3021 / 3121                                                  | 4         | 0.43%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 4         | 0.43%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 4         | 0.43%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 3         | 0.32%   |
| SCM Microsystems SCR335 SmartCard Reader                                     | 3         | 0.32%   |
| Reiner SCT Kartensysteme tanJack USB                                         | 3         | 0.32%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 3         | 0.32%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 0.22%   |
| Reiner SCT Kartensysteme cyberJack e-com/pinpad                              | 2         | 0.22%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 0.22%   |
| OmniKey CardMan 4321                                                         | 2         | 0.22%   |
| Kobil Systems Smart Token                                                    | 2         | 0.22%   |
| Kobil Systems KOBIL Class 3 Reader                                           | 2         | 0.22%   |
| In Focus Systems EMV Smartcard Reader                                        | 2         | 0.22%   |
| Fujitsu Siemens Computers Keyboard KB SCR                                    | 2         | 0.22%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 0.22%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 0.11%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 0.11%   |
| Purism, SPC Librem Key                                                       | 1         | 0.11%   |
| OmniKey CardMan 3121 (HID Technologies)                                      | 1         | 0.11%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.11%   |
| NXP Semiconductors PR533                                                     | 1         | 0.11%   |
| Microchip Technology SMSC USX101x Reader                                     | 1         | 0.11%   |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.11%   |
| Fujitsu Siemens Computers Smartcard Reader D323                              | 1         | 0.11%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.11%   |
| Fujitsu Siemens Computers Keyboard KB100 SCR eSIG                            | 1         | 0.11%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.11%   |
| Cherry SmartTerminal XX44                                                    | 1         | 0.11%   |
| Cherry Smart Card Reader USB                                                 | 1         | 0.11%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.11%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.11%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.11%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 9455      | 69.73%  |
| 1     | 3105      | 22.9%   |
| 2     | 787       | 5.8%    |
| 3     | 141       | 1.04%   |
| 4     | 45        | 0.33%   |
| 5     | 19        | 0.14%   |
| 7     | 5         | 0.04%   |
| 9     | 1         | 0.01%   |
| 6     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 1586      | 30.69%  |
| Graphics card            | 920       | 17.8%   |
| Chipcard                 | 827       | 16%     |
| Net/wireless             | 588       | 11.38%  |
| Multimedia controller    | 271       | 5.24%   |
| Communication controller | 233       | 4.51%   |
| Storage                  | 124       | 2.4%    |
| Card reader              | 111       | 2.15%   |
| Unassigned class         | 98        | 1.9%    |
| Camera                   | 93        | 1.8%    |
| Sound                    | 78        | 1.51%   |
| Bluetooth                | 75        | 1.45%   |
| Modem                    | 39        | 0.75%   |
| Net/ethernet             | 32        | 0.62%   |
| Network                  | 26        | 0.5%    |
| Storage/ide              | 15        | 0.29%   |
| Dvb card                 | 11        | 0.21%   |
| Storage/raid             | 10        | 0.19%   |
| Flash memory             | 9         | 0.17%   |
| Firewire controller      | 7         | 0.14%   |
| Tv card                  | 5         | 0.1%    |
| Unclassified device      | 4         | 0.08%   |
| Storage/ata              | 3         | 0.06%   |
| Storage/nvme             | 2         | 0.04%   |
| Video                    | 1         | 0.02%   |

